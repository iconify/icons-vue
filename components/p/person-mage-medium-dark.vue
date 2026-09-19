<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fgyy3cclr"/><path fill="url(#il4bdjb)" class="u43ch0b3o"/><path fill="url(#iW8yVeb)" class="u43ch0b3o"/><path fill="url(#ilwSyMe)" class="u43ch0b3o"/><path fill="url(#ipMQjDc)" class="u43ch0b3o"/><path fill="url(#ieEwfyb)" class="r-bbuzbzm"/><path fill="url(#ibPlbGX)" class="r-bbuzbzm"/><path fill="url(#i1LfFnc)" class="r-bbuzbzm"/><path fill="url(#idbpoub)" class="zc_ep_0uq"/><path fill="url(#iXwlnbA)" class="zc_ep_0uq"/><path fill="url(#ibfF9pc)" class="g8oaksl8k"/><path fill="url(#iSVIuZb)" class="g8oaksl8k"/><path fill="url(#iyT5utc)" class="g8oaksl8k"/><path fill="url(#iwDqPAI)" class="g8oaksl8k"/><path fill="url(#ipFI5hc)" class="g8oaksl8k"/><path fill="url(#iqYNBEd)" class="g8oaksl8k"/><path fill="url(#iAsh0Wp)" class="g8oaksl8k"/><g filter="url(#i30dyhd)"><path class="edkhrwbqz"/><path fill="url(#iqTZBPc)" class="g43afac9g"/><path fill="url(#inhs3Gr)" class="g43afac9g"/><path fill="url(#iQdlE2c)" class="g43afac9g"/><path stroke="url(#iXHj40b)" class="xp31u8b0s"/></g><g filter="url(#id3R9Wd)"><path class="fgnpzdbsz"/><path fill="url(#i5MO2Qc)" class="xr99hwbgq"/><path fill="url(#iwcC1ye)" class="xr99hwbgq"/></g><g filter="url(#ingAewb)"><path fill="url(#iOxWFad)" class="d86qxubue"/><path fill="url(#ir99qxd)" class="d86qxubue"/></g><path fill="url(#iDiuhqc)" class="zcpjvdbuo"/><path fill="url(#ixa9Eae)" class="h-lv1ubvk"/><path fill="url(#inbbnEd)" class="h-lv1ubvk"/><path fill="url(#iDiuhqc)" class="zcpjvdbuo"/><path fill="url(#iDqN3pV)" class="p7xat6cnl"/><path fill="url(#iirSkZf)" class="p7xat6cnl"/><path fill="url(#iIjIJec)" class="p7xat6cnl"/><path fill="url(#ixovgFc)" class="w879bpb0e"/><path fill="url(#iAwNGNd)" class="w879bpb0e"/><path fill="url(#i4jnpHd)" class="w879bpb0e"/><path fill="url(#ighCgpe)" class="h-e6v32ai"/><path fill="url(#ix5gnYc)" class="h-e6v32ai"/><path fill="url(#iJEWtud)" class="h-e6v32ai"/><path fill="url(#i2e03Ec)" class="h-e6v32ai"/><path fill="url(#i7Hsxxd)" class="h-e6v32ai"/><path fill="url(#iuAwBNe)" class="h-e6v32ai"/><path fill="url(#isDXaed)" class="h-e6v32ai"/><g filter="url(#i4FXF1c)"><path fill="url(#iU7U3XT)" class="hbrxqdets"/><path fill="url(#isPRIKd)" class="hbrxqdets"/><path fill="url(#iJ9f8Uc)" class="hbrxqdets"/><path fill="url(#iGFMqWH)" class="hbrxqdets"/><path fill="url(#iRjmOQY)" class="hbrxqdets"/><path fill="url(#iheSTgO)" class="hbrxqdets"/><path stroke="url(#iGAAS2d)" class="lgnz4ib3a"/></g><g filter="url(#i53MkXd)"><path fill="url(#i8ElAPc)" class="b43uiy30g"/><path fill="url(#ieaWAvd)" class="b43uiy30g"/><path fill="url(#ikytyIb)" class="b43uiy30g"/><path fill="url(#iW4kXJz)" class="b43uiy30g"/></g><path fill="url(#iUDojFc)" class="d-kfqjw9b"/><path fill="url(#iNZ1RrM)" class="d-kfqjw9b"/><path fill="url(#i63AZyd)" class="bn4p-sbtt"/><g filter="url(#iznWdVc)"><path stroke="url(#i2O0dbd)" class="lehnoh0zf"/></g><path fill="url(#i9PjRok)" class="vww-fqhwh"/><path fill="url(#i11YRMe)" class="vww-fqhwh"/><path fill="url(#iaiUvYc)" class="vj4jwbgtj"/><circle fill="url(#itASXpZ)" class="haiup_bzr"/><circle fill="url(#ieyP0Kc)" class="l0dpenbvj"/><circle fill="url(#iSHUzze)" class="l0dpenbvj"/><g filter="url(#inhGePb)"><circle class="jeutamw8k"/></g><g filter="url(#inUCy5c)"><circle fill="url(#iCmNmGe)" class="h79oecc1t"/></g><g filter="url(#ibG28ed)"><path fill="url(#iTPcINe)" class="yj5dctbip"/><path fill="url(#ix1axLb)" class="yj5dctbip"/><path fill="url(#i94kxeM)" class="yj5dctbip"/></g><path fill="url(#ivjOnxd)" class="yj5dctbip"/><path fill="url(#iQviYld)" class="yj5dctbip"/><path fill="url(#itxYMui)" class="yj5dctbip"/><path fill="url(#iW52wyd)" class="yj5dctbip"/><g filter="url(#iUOc6Dc)"><path stroke="url(#iinIBYb)" class="vzg4cacsm"/></g><path class="be44ofbje"/><g filter="url(#izGJGdc)"><path class="qh9br6b2y"/></g><g filter="url(#iMmC4sb)"><path class="d02_y4bfv"/><path fill="url(#icbeije)" class="j_2ccnt5p"/><path fill="url(#iRa2Rvr)" class="j_2ccnt5p"/><path fill="url(#im0r3kc)" class="j_2ccnt5p"/><path fill="url(#imfzu7C)" class="j_2ccnt5p"/></g><path class="qz94s4bip"/><path fill="url(#i59hpcb)" class="cedz8lbio"/><path class="a07exk92a"/><g filter="url(#ip1z1ib)"><path class="xo9yuc7kj"/><path fill="url(#ihfUwfd)" class="haktz9bdu"/></g><g filter="url(#ibJXLwb)"><path fill="url(#ix5afEe)" class="a4o2qybrp"/></g><path class="x9uzmjbio"/><path fill="url(#isqlRBC)" class="etcccebor"/><path class="cfof8-eyu"/><g filter="url(#igRYMIc)"><path fill="url(#iKY1KDc)" class="uj99bl4ra"/></g><g filter="url(#iqmZkAd)"><ellipse transform="rotate(-27.914 13.293 14.206)" class="f_5qi3ocn"/><ellipse fill="url(#iHvtRfe)" transform="rotate(-27.914 13.293 14.206)" class="vjxojz0pl"/></g><path clip-rule="evenodd" class="m_369jc1y"/><path clip-rule="evenodd" class="fw75m5zrv"/><g filter="url(#iTNKbQs)"><path class="f4tj_uwsg"/></g><g filter="url(#ip3QFCe)"><path class="f-4jpbbcr"/></g><g filter="url(#iIxNDfb)"><path fill="url(#iP3ZHLd)" clip-rule="evenodd" class="ouyjj2-hs"/></g><g filter="url(#iKvName)"><path fill="url(#iOkpe4c)" class="wx5i2acfu"/><path fill="url(#iUd8Xmt)" class="wx5i2acfu"/><path fill="url(#iXWhjQc)" class="wx5i2acfu"/><path fill="url(#iTEmuTb)" class="wx5i2acfu"/><path fill="url(#i9uxlvc)" class="wx5i2acfu"/></g><g filter="url(#i97cutB)"><path stroke="url(#icP7Vbc)" class="m52m3hl4m"/></g><g filter="url(#i5xmhac)"><path stroke="url(#ieBFIyc)" class="fdfbu9b0b"/></g><g filter="url(#iC9bpAd)"><path stroke="url(#i1bO7Vd)" class="n2acyj-6i"/></g><defs><radialGradient id="il4bdjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.03125 7.18055 0 20.738 30.442)" gradientUnits="userSpaceOnUse"><stop class="xhqrsjbac"/><stop offset="1" class="ebcvm6lto"/></radialGradient><radialGradient id="iW8yVeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.6875 .78125 0 22.988 29.817)" gradientUnits="userSpaceOnUse"><stop class="wup_v_x-y"/><stop offset="1" class="rec-1hb8e"/></radialGradient><radialGradient id="ilwSyMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 0 0 19.1959 8.613 29.996)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mr4lhnuux"/><stop offset="1" class="q-3947b0q"/></radialGradient><radialGradient id="ipMQjDc" cx="0" cy="0" r="1" gradientTransform="rotate(-136.837 16.423 12.118)scale(15.1664 18.2252)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="q-3947b0q"/><stop offset="1" class="dgbyghhck"/></radialGradient><radialGradient id="ieEwfyb" cx="0" cy="0" r="1" gradientTransform="matrix(.30005 -6.75 3.83344 .1704 8.594 29.88)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="e7_y1ioqg"/><stop offset="1" class="o8c2nzb0a"/></radialGradient><radialGradient id="ibPlbGX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.125 3.97458 0 6.734 30.192)" gradientUnits="userSpaceOnUse"><stop class="dn-ogvbjy"/><stop offset="1" class="inpzxhbwc"/></radialGradient><radialGradient id="i1LfFnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.63745 0 0 -7.24389 8.594 29.996)" gradientUnits="userSpaceOnUse"><stop class="a3c-8ubyu"/><stop offset="1" class="x9tw1mbfn"/></radialGradient><radialGradient id="idbpoub" cx="0" cy="0" r="1" gradientTransform="rotate(82.372 -.267 24.058)scale(8.94581 3.16756)" gradientUnits="userSpaceOnUse"><stop class="embu-7brp"/><stop offset="1" class="veybn72ma"/></radialGradient><radialGradient id="iXwlnbA" cx="0" cy="0" r="1" gradientTransform="matrix(.83557 0 0 8.41461 22.84 29.996)" gradientUnits="userSpaceOnUse"><stop class="rj_n-mbmd"/><stop offset=".85" class="sfuw4b7fs"/></radialGradient><radialGradient id="iSVIuZb" cx="0" cy="0" r="1" gradientTransform="rotate(124.902 .777 14.461)scale(1.63847 5.18259)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="dekz5-i5a"/><stop offset="1" class="takbm9boj"/></radialGradient><radialGradient id="iyT5utc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.625 -11.4392 0 15.709 19.723)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="tclwz7mny"/><stop offset="1" class="c5r226cip"/></radialGradient><radialGradient id="iwDqPAI" cx="0" cy="0" r="1" gradientTransform="matrix(4.9375 -2.78125 .65585 1.16432 19.27 21.973)" gradientUnits="userSpaceOnUse"><stop class="zm3svk-ip"/><stop offset="1" class="f-m4mzz6d"/></radialGradient><radialGradient id="ipFI5hc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75002 2.37497 -1.68941 -2.66754 10.738 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="d45gne0nz"/><stop offset="1" class="f283fd8-c"/></radialGradient><radialGradient id="iqYNBEd" cx="0" cy="0" r="1" gradientTransform="rotate(-69.233 29.08 .534)scale(10.4881 22.9861)" gradientUnits="userSpaceOnUse"><stop offset=".677" class="nypzj9bha"/><stop offset=".949" class="nvdrdzbmz"/></radialGradient><radialGradient id="iAsh0Wp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.88478 14.4983 0 15.709 24.613)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="bgqsi-bps"/><stop offset=".985" class="f-3q63keb"/></radialGradient><radialGradient id="iqTZBPc" cx="0" cy="0" r="1" gradientTransform="matrix(.76562 -.87496 3.20566 2.80509 14.77 24.473)" gradientUnits="userSpaceOnUse"><stop class="rdaygdbpu"/><stop offset="1" class="zajsytjse"/></radialGradient><radialGradient id="iQdlE2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 -.46875 4.21008 -3.78904 19.441 22.223)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="i2wlb99xo"/><stop offset="1" class="l15dqlbvn"/></radialGradient><radialGradient id="iXHj40b" cx="0" cy="0" r="1" gradientTransform="matrix(.8298 -1.3125 2.13746 1.35137 14.879 24.238)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="fqpzwo9rb"/><stop offset="1" class="vyxwjf9nd"/></radialGradient><radialGradient id="i5MO2Qc" cx="0" cy="0" r="1" gradientTransform="rotate(36.011 -25.62 32.235)scale(2.77909 5.15458)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="ma34zez7p"/><stop offset="1" class="b82y5bb4i"/></radialGradient><radialGradient id="iwcC1ye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48318 3.03117 -.28115 -.13757 17.117 21.223)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="j3sr9ikcc"/><stop offset="1" class="e8h8o5b_y"/></radialGradient><radialGradient id="iOxWFad" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 .96875 -.2841 1.50295 17.082 3.16)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="s_1mw_rhq"/><stop offset="1" class="pql562bff"/></radialGradient><radialGradient id="ixa9Eae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59797 1.31329 -1.29023 -1.56991 28.053 23.673)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="inbbnEd" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 27.817 23.52)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="iDqN3pV" cx="0" cy="0" r="1" gradientTransform="matrix(-4.62501 2.59374 -3.8683 -6.89775 17.988 3.817)" gradientUnits="userSpaceOnUse"><stop offset=".063" class="uhl03ccti"/><stop offset="1" class="uuh3gfbsu"/></radialGradient><radialGradient id="iIjIJec" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 -1.30125 2.428 -12.47818 18.77 7.535)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="tsk-k9bvn"/><stop offset="1" class="phlvo2b_b"/></radialGradient><radialGradient id="ighCgpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15156 -24.7184 0 15.75 9.333)" gradientUnits="userSpaceOnUse"><stop class="r-yilwbra"/><stop offset=".652" class="vxkgnhd4n"/></radialGradient><radialGradient id="ix5gnYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.64742 -17.2274 0 13.022 8.98)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="huu-ickwn"/><stop offset="1" class="t4ibp7bdp"/></radialGradient><radialGradient id="iJEWtud" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68356 0 0 -2.80263 25.977 10.71)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="p5_1r5b0y"/><stop offset="1" class="bkffn87la"/></radialGradient><radialGradient id="i2e03Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-10.1661 0 0 -1.56292 25.094 9.554)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="zdk8j6bjz"/><stop offset="1" class="lmlq_xbrl"/></radialGradient><radialGradient id="i7Hsxxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.15365 1.28841 0 24.918 11.91)" gradientUnits="userSpaceOnUse"><stop offset=".051" class="o8p2_blib"/><stop offset="1" class="szwxs1ffj"/></radialGradient><radialGradient id="iuAwBNe" cx="0" cy="0" r="1" gradientTransform="rotate(-119.268 10.579 6.104)scale(3.2599 6.67388)" gradientUnits="userSpaceOnUse"><stop class="vmjr7rbhn"/><stop offset="1" class="zxip0bczk"/></radialGradient><radialGradient id="isDXaed" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 0 0 1.78125 21.332 18.192)" gradientUnits="userSpaceOnUse"><stop class="iusprebiv"/><stop offset="1" class="n4ma-nbis"/></radialGradient><radialGradient id="iU7U3XT" cx="0" cy="0" r="1" gradientTransform="matrix(-8.43067 -6.22495 7.88718 -10.6819 24.176 17.817)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="qxprq_b_n"/><stop offset="1" class="id0y_n31u"/></radialGradient><radialGradient id="isPRIKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.19531 0 0 .58033 20.863 13.285)" gradientUnits="userSpaceOnUse"><stop class="azeqcu15x"/><stop offset="1" class="sda7dac5x"/></radialGradient><radialGradient id="iJ9f8Uc" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 .70313 -.43994 .44972 20.066 11.723)" gradientUnits="userSpaceOnUse"><stop class="vnbqzxbma"/><stop offset="1" class="k10k6_baq"/></radialGradient><radialGradient id="iGFMqWH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60937 0 0 -.8125 10.926 13.473)" gradientUnits="userSpaceOnUse"><stop class="x9q-1ua-h"/><stop offset="1" class="d_y83zkbz"/></radialGradient><radialGradient id="iRjmOQY" cx="0" cy="0" r="1" gradientTransform="rotate(-177.049 5.42 8.54)scale(3.03527 4.59892)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="ftdzlkbpm"/><stop offset="1" class="iu-l6acky"/></radialGradient><radialGradient id="iheSTgO" cx="0" cy="0" r="1" gradientTransform="rotate(-50.886 21.06 3.067)scale(3.51696 3.66873)" gradientUnits="userSpaceOnUse"><stop class="ap_fa_bgx"/><stop offset="1" class="wnm2vg-zq"/></radialGradient><radialGradient id="ieaWAvd" cx="0" cy="0" r="1" gradientTransform="matrix(3 3.65625 -3.78158 3.10283 22.894 7.317)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="vas9tjbit"/><stop offset="1" class="ny-1wemya"/></radialGradient><radialGradient id="ikytyIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.61462 -2.0661 0 25.705 7.453)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="viuzncbxq"/><stop offset="1" class="ej1v0hbca"/></radialGradient><radialGradient id="iW4kXJz" cx="0" cy="0" r="1" gradientTransform="rotate(145.359 13.401 8.53)scale(3.99771 2.68184)" gradientUnits="userSpaceOnUse"><stop class="uvv0p6btj"/><stop offset="1" class="elep40b9c"/></radialGradient><radialGradient id="iUDojFc" cx="0" cy="0" r="1" gradientTransform="rotate(144.673 12.844 7.022)scale(4.07349 4.5687)" gradientUnits="userSpaceOnUse"><stop class="a-lhjfbpa"/><stop offset="1" class="begh2ub5w"/></radialGradient><radialGradient id="iNZ1RrM" cx="0" cy="0" r="1" gradientTransform="rotate(-133.348 14.9 -2.216)scale(4.59811 4.64228)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="po1nyh2al"/><stop offset=".913" class="cjnv6q4jy"/></radialGradient><radialGradient id="i63AZyd" cx="0" cy="0" r="1" gradientTransform="rotate(-111.272 15.595 -6.12)scale(2.19652 2.90326)" gradientUnits="userSpaceOnUse"><stop offset=".052" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="i9PjRok" cx="0" cy="0" r="1" gradientTransform="rotate(169.078 4.613 9.242)scale(.86923 2.54329)" gradientUnits="userSpaceOnUse"><stop class="x8lzjv-mn"/><stop offset="1" class="ijlg4dfja"/></radialGradient><radialGradient id="i11YRMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 -1.35937 1.36127 -1.0327 11.347 19.38)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="b85todb1f"/><stop offset="1" class="vl6e3-baw"/></radialGradient><radialGradient id="iaiUvYc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32561 -.24315 .57714 -3.14644 21.566 17.606)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="a32mo4bai"/><stop offset="1" class="z3h5ugg6t"/></radialGradient><radialGradient id="itASXpZ" cx="0" cy="0" r="1" gradientTransform="rotate(-60.154 18.405 -.377)scale(2.19774 5.95774)" gradientUnits="userSpaceOnUse"><stop class="jtzlp7blu"/><stop offset="1" class="w046tx_lz"/></radialGradient><radialGradient id="ieyP0Kc" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -2.48438 1.76846 1.17897 20.322 15.852)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="j0knl-bek"/><stop offset="1" class="u7y-6sbyz"/></radialGradient><radialGradient id="iSHUzze" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.41407 .58923 .86715 21.088 14.665)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="dmjfo93kp"/><stop offset="1" class="lqnuf6baa"/></radialGradient><radialGradient id="iCmNmGe" cx="0" cy="0" r="1" gradientTransform="matrix(1.22473 0 0 1.03239 20.322 14.712)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="dlxwu6bpa"/><stop offset="1" class="lo9_6kbiu"/></radialGradient><radialGradient id="iTPcINe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -5.71423 18.832 16.004)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="rw5rd891q"/><stop offset=".94" class="jwu3k5bsp"/></radialGradient><radialGradient id="ix1axLb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -1.0625 .84812 -.79823 13.8 13.91)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="vklgwpbyn"/><stop offset="1" class="auta49apj"/></radialGradient><radialGradient id="i94kxeM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.03906 1.50975 0 18.09 13.926)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="qlvogd8br"/><stop offset="1" class="fn1aitbjk"/><stop offset="1" class="n_s9xabrk"/></radialGradient><radialGradient id="ivjOnxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5 -9.72937 0 15.742 13.073)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="x2sxr1bvv"/><stop offset="1" class="f6-zdvnns"/></radialGradient><radialGradient id="iQviYld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 8.42578 -1.56064 -.1968 10.697 11.364)" gradientUnits="userSpaceOnUse"><stop class="t1tmf5v5r"/><stop offset="1" class="xxi96hb7e"/></radialGradient><radialGradient id="itxYMui" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 -.625 1.54622 2.55127 11.416 19.727)" gradientUnits="userSpaceOnUse"><stop class="lhw3utjfk"/><stop offset="1" class="llz8xsvjs"/></radialGradient><radialGradient id="iW52wyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 -.5 1.32692 -1.99038 19.76 20.321)" gradientUnits="userSpaceOnUse"><stop class="aaaczob2m"/><stop offset="1" class="foe_-bbwz"/></radialGradient><radialGradient id="iinIBYb" cx="0" cy="0" r="1" gradientTransform="matrix(.33594 -.4453 .60326 .4551 14.707 18.535)" gradientUnits="userSpaceOnUse"><stop class="n6xpe4bqb"/><stop offset="1" class="y9ad_d9-m"/></radialGradient><radialGradient id="imfzu7C" cx="0" cy="0" r="1" gradientTransform="matrix(0 .20695 -.61269 0 16.07 16.511)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="i59hpcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81359 -1.2941 0 17.941 14.302)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ihfUwfd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.379 2.856)scale(.37895 .52172)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isqlRBC" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81363 -1.29417 0 13.565 14.301)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iHvtRfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00775 -.49495 .59495 -.00931 13.277 14.52)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iP3ZHLd" cx="0" cy="0" r="1" gradientTransform="matrix(.06839 -.65954 5.09164 .52797 18.191 11.903)" gradientUnits="userSpaceOnUse"><stop class="ktr4-_bkr"/><stop offset=".899" class="yffndbb9h"/></radialGradient><radialGradient id="iUd8Xmt" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.007 25.3)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iXWhjQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.007 26.595)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iTEmuTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.007 27.845)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i9uxlvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.007 29.196)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><filter id="i30dyhd" width="12.098" height="6.858" x="9.659" y="17.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".1"/></filter><filter id="id3R9Wd" width="3.75" height="3.003" x="13.834" y="21.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.14902 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1074"/></filter><filter id="ingAewb" width="6.328" height="3.25" x="15.66" y="1.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.521569 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1074"/></filter><filter id="i4FXF1c" width="23.09" height="7.66" x="4.2" y="10.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".125"/></filter><filter id="i53MkXd" width="5.46" height="21.857" x="23.1" y="5.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.45098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1074"/></filter><filter id="iznWdVc" width="1.8" height="17.408" x="25.202" y="9.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".325"/></filter><filter id="inhGePb" width="2.625" height="2.625" x="9.703" y="13.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".125"/></filter><filter id="inUCy5c" width="2.425" height="2.425" x="19.272" y="13.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".075"/></filter><filter id="ibG28ed" width="11.175" height="10.15" x="10.386" y="11.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.352941 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1074"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.243137 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1074" result="effect2_innerShadow_4002_1074"/></filter><filter id="iUOc6Dc" width="3.813" height="1.561" x="13.842" y="17.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".05"/></filter><filter id="izGJGdc" width="2.707" height="3.647" x="14.235" y="14.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".25"/></filter><filter id="iMmC4sb" width="9.818" height="10.818" x="10.845" y="14.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1074"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1074" result="shape"/></filter><filter id="ip1z1ib" width=".788" height=".697" x="17.205" y="13.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".05"/></filter><filter id="ibJXLwb" width=".892" height=".914" x="18.048" y="13.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".1"/></filter><filter id="igRYMIc" width=".987" height="1.041" x="13.593" y="13.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".1"/></filter><filter id="iqmZkAd" width=".914" height=".705" x="12.835" y="13.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".05"/></filter><filter id="iTNKbQs" width="2.242" height="1.109" x="11.984" y="12.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.454902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1074"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.588235 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1074" result="effect2_innerShadow_4002_1074"/></filter><filter id="ip3QFCe" width="2.242" height="1.109" x="17.289" y="12.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.454902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1074"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.588235 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1074" result="effect2_innerShadow_4002_1074"/></filter><filter id="iIxNDfb" width="4.368" height=".847" x="16.494" y="11.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.427451 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1074"/></filter><filter id="iKvName" width="4.846" height="5.556" x="23.357" y="24.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1074"/></filter><filter id="i97cutB" width="2.097" height=".3" x="23.727" y="25.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".05"/></filter><filter id="i5xmhac" width="2.097" height=".3" x="23.649" y="27.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".05"/></filter><filter id="iC9bpAd" width="2.097" height=".3" x="23.727" y="28.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1074" stdDeviation=".05"/></filter><linearGradient id="ibfF9pc" x1="21.582" x2="10.613" y1="21.66" y2="21.66" gradientUnits="userSpaceOnUse"><stop class="q8c8skp1q"/><stop offset="1" class="n7c2bfbtc"/></linearGradient><linearGradient id="inhs3Gr" x1="16.175" x2="16.925" y1="19.567" y2="23.848" gradientUnits="userSpaceOnUse"><stop offset=".287" class="cvgk3kbak"/><stop offset="1" class="c6lp81bhp"/></linearGradient><linearGradient id="ir99qxd" x1="19.144" x2="19.472" y1="5.207" y2="3.848" gradientUnits="userSpaceOnUse"><stop class="guc8z7bij"/><stop offset="1" class="iov6rh-pq"/></linearGradient><linearGradient id="iDiuhqc" x1="7.907" x2="22.372" y1="19.98" y2="19.98" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kdl2hbbyb"/><stop offset="1" class="valdy-bly"/></linearGradient><linearGradient id="iirSkZf" x1="17.363" x2="17.363" y1="8.504" y2="7.317" gradientUnits="userSpaceOnUse"><stop class="u3wf8s8gl"/><stop offset="1" class="pt6842k6d"/></linearGradient><linearGradient id="ixovgFc" x1="14.176" x2="20.238" y1="9.91" y2="9.754" gradientUnits="userSpaceOnUse"><stop class="p-go_8bpa"/><stop offset="1" class="tp_ivrbui"/></linearGradient><linearGradient id="iAwNGNd" x1="21.863" x2="19.269" y1="9.285" y2="9.285" gradientUnits="userSpaceOnUse"><stop class="xrhcfrbuk"/><stop offset="1" class="psjmui2lw"/></linearGradient><linearGradient id="i4jnpHd" x1="9.738" x2="11.957" y1="9.519" y2="10.534" gradientUnits="userSpaceOnUse"><stop class="cvjhjoe1h"/><stop offset="1" class="wmajqfcti"/></linearGradient><linearGradient id="iGAAS2d" x1="15.745" x2="15.745" y1="11.364" y2="16.817" gradientUnits="userSpaceOnUse"><stop class="flda2eefx"/><stop offset="1" class="leei8_8-z"/></linearGradient><linearGradient id="i8ElAPc" x1="24.372" x2="28.31" y1="10.532" y2="10.532" gradientUnits="userSpaceOnUse"><stop class="kytdhlviv"/><stop offset="1" class="bf9jtobby"/></linearGradient><linearGradient id="i2O0dbd" x1="26.602" x2="26.602" y1="9.925" y2="25.533" gradientUnits="userSpaceOnUse"><stop class="pafpa8b3r"/><stop offset="1" class="irkpemyfq"/></linearGradient><linearGradient id="icbeije" x1="14.916" x2="15.825" y1="15.925" y2="15.925" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iRa2Rvr" x1="16.662" x2="15.669" y1="16.264" y2="16.251" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="im0r3kc" x1="15.942" x2="15.942" y1="17.044" y2="16.442" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="ix5afEe" x1="18.721" x2="18.407" y1="14.355" y2="14.549" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKY1KDc" x1="14.31" x2="13.996" y1="14.355" y2="14.549" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iOkpe4c" x1="27.738" x2="23.357" y1="28.058" y2="28.058" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="icP7Vbc" x1="23.877" x2="25.586" y1="26.052" y2="26.052" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ieBFIyc" x1="23.799" x2="25.508" y1="27.356" y2="27.356" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i1bO7Vd" x1="23.877" x2="25.586" y1="28.661" y2="28.661" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-mage-medium-dark" /></template>
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

.a4o2qybrp {
  d: path("M18.74 14.6a.84.84 0 0 0-.232-.464l-.26.286l.117.228z");
}

.aaaczob2m {
  stop-color: var(--svg-color--815e64, #815E64);
}

.ap_fa_bgx {
  stop-color: var(--svg-color--3171db, #3171DB);
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.auta49apj {
  stop-color: var(--svg-color--6e414e, #6E414E);
  stop-opacity: 0;
}

.azeqcu15x {
  stop-color: var(--svg-color--215a98, #215A98);
}

.b43uiy30g {
  d: path("M26.94 5.304c-.2-.11-.45.04-.45.27v1.62c0 .44-.36.81-.8.8a.786.786 0 0 1-.77-.78v-1.64c0-.23-.25-.38-.45-.27c-.81.44-1.36 1.29-1.37 2.27c-.01 1.01.58 1.9 1.43 2.34c.1.05.16.15.16.26v15.91c0 .57.47 1.04 1.04 1.04s1.04-.47 1.04-1.04v-15.93c0-.11.06-.21.16-.26a2.605 2.605 0 0 0 .01-4.59");
}

.b82y5bb4i {
  stop-color: var(--svg-color--402231, #402231);
  stop-opacity: 0;
}

.b85todb1f {
  stop-color: var(--svg-color--717181, #717181);
}

.be44ofbje {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M15.749 18.065c-.54 0-1.04-.13-1.47-.35c-.14-.08-.3.09-.21.23a2.006 2.006 0 0 0 3.36 0c.09-.14-.07-.3-.21-.23c-.43.22-.93.35-1.47.35");
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

.d02_y4bfv {
  fill: var(--svg-color--805952, #805952);
  d: path("m15.383 14.523l-.514 1.786c-.105.367.147.735.504.735h.761c.357 0 .61-.373.504-.735l-.514-1.786c-.11-.396-.625-.396-.74 0");
}

.d45gne0nz {
  stop-color: var(--svg-color--073880, #073880);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d86qxubue {
  d: path("M15.66 2.004c2.84 0 4.71.95 5.81 1.77c.52.39.23 1.22-.42 1.22l-5.31.01z");
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dekz5-i5a {
  stop-color: var(--svg-color--3395e6, #3395E6);
}

.dgbyghhck {
  stop-color: var(--svg-color--2f79b8, #2F79B8);
}

.dlxwu6bpa {
  stop-color: var(--svg-color--694d4d, #694D4D);
}

.dmjfo93kp {
  stop-color: var(--svg-color--695156, #695156);
}

.dn-ogvbjy {
  stop-color: var(--svg-color--2982ee, #2982EE);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7_y1ioqg {
  stop-color: var(--svg-color--2e99f4, #2E99F4);
}

.e8h8o5b_y {
  stop-color: var(--svg-color--5a484e, #5A484E);
  stop-opacity: 0;
}

.ebcvm6lto {
  stop-color: var(--svg-color--39a7ff, #39A7FF);
  stop-opacity: 0;
}

.edkhrwbqz {
  fill: var(--svg-color--3978a9, #3978A9);
  d: path("M15.708 24.473c-.183 0-.687-.155-1.405-.738a192 192 0 0 1-3.762-3.18c-.216-.187-.671-.668-.566-1.192c.164-.82 1.359-1.148 3.203-1.148h5.061c1.844 0 3.04.328 3.203 1.148c.105.524-.35 1.005-.566 1.192a194 194 0 0 1-3.762 3.18c-.718.583-1.155.738-1.405.738z");
}

.ej1v0hbca {
  stop-color: var(--svg-color--ba795b, #BA795B);
  stop-opacity: 0;
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.elep40b9c {
  stop-color: var(--svg-color--cc8c6f, #CC8C6F);
  stop-opacity: 0;
}

.embu-7brp {
  stop-color: var(--svg-color--4ab4f4, #4AB4F4);
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

.f6-zdvnns {
  stop-color: var(--svg-color--693b61, #693B61);
}

.fdfbu9b0b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.799 27.278h1.797");
}

.fgnpzdbsz {
  fill: var(--svg-color--53383d, #53383D);
  d: path("m15.45 23.977l-1.616-2.754h3.75l-1.617 2.754a.3.3 0 0 1-.517 0");
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

.foe_-bbwz {
  stop-color: var(--svg-color--815e64, #815E64);
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

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.fw75m5zrv {
  fill: var(--svg-color--7f544f, #7F544F);
  fill-rule: evenodd;
  d: path("M17.235 15.409a.3.3 0 0 0 .013.424c.253.238.573.387.854.478s.55.133.718.142a.3.3 0 1 0 .033-.6a2.4 2.4 0 0 1-.566-.113a1.7 1.7 0 0 1-.628-.344a.3.3 0 0 0-.424.013");
}

.g43afac9g {
  d: path("M15.708 24.473c-.183 0-.687-.155-1.405-.738a192 192 0 0 1-3.762-3.18c-.216-.187-.671-.668-.566-1.192c.164-.82 1.359-1.148 3.203-1.148h5.061c1.844 0 3.04.328 3.203 1.148c.105.524-.35 1.005-.566 1.192a194 194 0 0 1-3.762 3.18c-.718.583-1.155.738-1.405.738z");
}

.g8oaksl8k {
  d: path("M15.694 24.614c-.395 0-1.172-.032-2.446-.477l-.078-.036c-1.438-.657-4.997-2.284-4.851-4.363c0-2.15 3.458-2.156 5.187-1.89h4.405c1.73-.266 5.188-.26 5.188 1.89c.145 2.08-3.414 3.706-4.852 4.363l-.078.036c-1.274.445-2.05.476-2.476.476");
}

.guc8z7bij {
  stop-color: var(--svg-color--2caafc, #2CAAFC);
}

.h-e6v32ai {
  d: path("m23.34 18.484l-15.2-.01c-2.45 0-4.45-2-4.45-4.46s2-4.46 4.46-4.46l15.2.01c2.46 0 4.46 2 4.46 4.46a4.48 4.48 0 0 1-4.47 4.46");
}

.h-lv1ubvk {
  d: path("M27.086 23.04a.97.97 0 0 1 .967.967v2.214h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.h79oecc1t {
  cx: 20.484px;
  cy: 14.942px;
  r: 1.063px;
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

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
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

.j0knl-bek {
  stop-color: var(--svg-color--704b51, #704B51);
}

.j3sr9ikcc {
  stop-color: var(--svg-color--5a484e, #5A484E);
}

.jeutamw8k {
  cx: 11.015px;
  cy: 14.942px;
  r: 1.063px;
  fill: var(--svg-color--52303b, #52303B);
}

.jtzlp7blu {
  stop-color: var(--svg-color--5b3b47, #5B3B47);
}

.jwu3k5bsp {
  stop-color: var(--svg-color--734b4c, #734B4C);
}

.k10k6_baq {
  stop-color: var(--svg-color--0d50a5, #0D50A5);
  stop-opacity: 0;
}

.kdl2hbbyb {
  stop-color: var(--svg-color--cacaca, #CACACA);
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
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

.leei8_8-z {
  stop-color: var(--svg-color--4478e6, #4478E6);
  stop-opacity: 0;
}

.lehnoh0zf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M26.102 9.925v15.608");
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lgnz4ib3a {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m8.75 11.264l13.99.01m-13.99-.01v.1c-2.26 0-4.1 1.51-4.1 3.38s1.83 3.38 4.1 3.38h13.99c2.26 0 4.1-1.51 4.1-3.37c0-1.87-1.83-3.38-4.1-3.38v-.1m-13.99-.01c-2.296 0-4.2 1.538-4.2 3.48s1.894 3.48 4.2 3.48h13.99c2.296 0 4.2-1.537 4.2-3.47c0-1.942-1.894-3.48-4.2-3.48m-13.99-.01l13.99.01");
}

.lhw3utjfk {
  stop-color: var(--svg-color--7e575a, #7E575A);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llz8xsvjs {
  stop-color: var(--svg-color--7e575a, #7E575A);
  stop-opacity: 0;
}

.lmlq_xbrl {
  stop-color: var(--svg-color--2fa3f0, #2FA3F0);
  stop-opacity: 0;
}

.lo9_6kbiu {
  stop-color: var(--svg-color--5e3c42, #5E3C42);
}

.lqnuf6baa {
  stop-color: var(--svg-color--695156, #695156);
  stop-opacity: 0;
}

.m_369jc1y {
  fill: var(--svg-color--6a4644, #6A4644);
  fill-rule: evenodd;
  d: path("M14.278 15.409a.3.3 0 0 1-.013.424a2.3 2.3 0 0 1-.854.478a3 3 0 0 1-.718.142a.3.3 0 0 1-.033-.6c.118-.006.333-.037.566-.113c.234-.076.462-.189.628-.344a.3.3 0 0 1 .424.013");
}

.m52m3hl4m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.877 25.974h1.797");
}

.ma34zez7p {
  stop-color: var(--svg-color--402231, #402231);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mr4lhnuux {
  stop-color: var(--svg-color--2787f2, #2787F2);
}

.n_s9xabrk {
  stop-color: var(--svg-color--7c4d4f, #7C4D4F);
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

.n6xpe4bqb {
  stop-color: var(--svg-color--856264, #856264);
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

.o8c2nzb0a {
  stop-color: var(--svg-color--307fc2, #307FC2);
}

.o8p2_blib {
  stop-color: var(--svg-color--2e74cb, #2E74CB);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
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

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q-3947b0q {
  stop-color: var(--svg-color--39a8ff, #39A8FF);
  stop-opacity: 0;
}

.q8c8skp1q {
  stop-color: var(--svg-color--3291c8, #3291C8);
}

.qh9br6b2y {
  fill: var(--svg-color--76424d, #76424D);
  d: path("m15.241 14.842l-.483 1.677c-.099.345.138.69.473.69h.715c.336 0 .572-.35.474-.69l-.484-1.677c-.103-.372-.586-.372-.695 0");
}

.qlvogd8br {
  stop-color: var(--svg-color--7c4d4f, #7C4D4F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxprq_b_n {
  stop-color: var(--svg-color--257bd2, #257BD2);
}

.qz94s4bip {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.151 13.55a1.4 1.4 0 0 1 1.359 1.062a.275.275 0 0 1-.269.342h-2.237a.23.23 0 0 1-.228-.273a1.4 1.4 0 0 1 1.375-1.13");
}

.r-bbuzbzm {
  d: path("M8.594 22.752c-2.616 2.262-3.72 5.491-3.72 7.244h3.72z");
}

.r-yilwbra {
  stop-color: var(--svg-color--35acfa, #35ACFA);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rdaygdbpu {
  stop-color: var(--svg-color--3aa4e9, #3AA4E9);
}

.rec-1hb8e {
  stop-color: var(--svg-color--3797f8, #3797F8);
  stop-opacity: 0;
}

.rj_n-mbmd {
  stop-color: var(--svg-color--267adb, #267ADB);
}

.rw5rd891q {
  stop-color: var(--svg-color--8d6059, #8D6059);
}

.s_1mw_rhq {
  stop-color: var(--svg-color--4cdbff, #4CDBFF);
}

.sda7dac5x {
  stop-color: var(--svg-color--215a98, #215A98);
  stop-opacity: 0;
}

.sfuw4b7fs {
  stop-color: var(--svg-color--267adb, #267ADB);
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

.t1tmf5v5r {
  stop-color: var(--svg-color--4e395c, #4E395C);
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

.tp_ivrbui {
  stop-color: var(--svg-color--584d65, #584D65);
}

.tsk-k9bvn {
  stop-color: var(--svg-color--2fa9e7, #2FA9E7);
  stop-opacity: 0;
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u3wf8s8gl {
  stop-color: var(--svg-color--50b2e2, #50B2E2);
}

.u43ch0b3o {
  d: path("M4.875 29.996c0-2.883 2.987-9.76 10.777-9.76c7.791 0 10.628 6.396 10.868 9.76z");
}

.u7y-6sbyz {
  stop-color: var(--svg-color--533543, #533543);
}

.uhl03ccti {
  stop-color: var(--svg-color--4bdaff, #4BDAFF);
}

.uj99bl4ra {
  d: path("M14.38 14.612c0-.289-.235-.481-.298-.54l-.29.28l.178.362z");
}

.uuh3gfbsu {
  stop-color: var(--svg-color--2cb1f7, #2CB1F7);
}

.uvv0p6btj {
  stop-color: var(--svg-color--cc8c6f, #CC8C6F);
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

.vklgwpbyn {
  stop-color: var(--svg-color--6e414e, #6E414E);
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

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w046tx_lz {
  stop-color: var(--svg-color--4a2e40, #4A2E40);
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w879bpb0e {
  d: path("m9.48 10.154l-.19.38h12.74l-.18-.36a7.1 7.1 0 0 0-1.19-1.67h-10a7.5 7.5 0 0 0-1.18 1.65");
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

.x2sxr1bvv {
  stop-color: var(--svg-color--754460, #754460);
  stop-opacity: 0;
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

.xxi96hb7e {
  stop-color: var(--svg-color--4e395c, #4E395C);
  stop-opacity: 0;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y9ad_d9-m {
  stop-color: var(--svg-color--856264, #856264);
  stop-opacity: 0;
}

.yffndbb9h {
  stop-color: var(--svg-color--757bab, #757BAB);
}

.yj5dctbip {
  d: path("M20.955 13.26q0-.015 0 0c.026-.695 0-1.087-.577-1.576c-.293-.218-.523-.32-1.365-.32H12.59c-.82 0-1.466.304-1.727.598c-.26.293-.367.574-.312 1.298l.27 4.69c.265 1.958 1.952 3.414 3.955 3.414h1.92c2.003 0 3.69-1.466 3.955-3.414z");
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.z3h5ugg6t {
  stop-color: var(--svg-color--9a9fab, #9A9FAB);
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

.zm3svk-ip {
  stop-color: var(--svg-color--4ab3f9, #4AB3F9);
}

.zxip0bczk {
  stop-color: var(--svg-color--104e9b, #104E9B);
  stop-opacity: 0;
}

</style>
