<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fgyy3cclr"/><path fill="url(#il4bdjb)" class="u43ch0b3o"/><path fill="url(#iW8yVeb)" class="u43ch0b3o"/><path fill="url(#ilwSyMe)" class="u43ch0b3o"/><path fill="url(#ipMQjDc)" class="u43ch0b3o"/><path fill="url(#ieEwfyb)" class="job-vz29n"/><path fill="url(#ibPlbGX)" class="job-vz29n"/><path fill="url(#i1LfFnc)" class="job-vz29n"/><path fill="url(#idbpoub)" class="zc_ep_0uq"/><path fill="url(#iXwlnbA)" class="zc_ep_0uq"/><path fill="url(#ibfF9pc)" class="g8oaksl8k"/><path fill="url(#iSVIuZb)" class="g8oaksl8k"/><path fill="url(#iyT5utc)" class="g8oaksl8k"/><path fill="url(#iwDqPAI)" class="g8oaksl8k"/><path fill="url(#ipFI5hc)" class="g8oaksl8k"/><path fill="url(#iqYNBEd)" class="g8oaksl8k"/><path fill="url(#iAsh0Wp)" class="g8oaksl8k"/><g filter="url(#iMB6idE)"><path class="edkhrwbqz"/><path fill="url(#iqTZBPc)" class="g43afac9g"/><path fill="url(#inhs3Gr)" class="g43afac9g"/><path fill="url(#iQdlE2c)" class="g43afac9g"/><path stroke="url(#iXHj40b)" class="xp31u8b0s"/></g><g filter="url(#iWsBvQe)"><path class="fnql1cbvy"/><path fill="url(#in8LAQc)" class="xr99hwbgq"/></g><g filter="url(#iLbEwOe)"><path fill="url(#iOxWFad)" class="d86qxubue"/><path fill="url(#ir99qxd)" class="d86qxubue"/></g><path fill="url(#iDiuhqc)" class="zcpjvdbuo"/><path fill="url(#iDiuhqc)" class="zcpjvdbuo"/><path fill="url(#iDqN3pV)" class="p7xat6cnl"/><path fill="url(#iirSkZf)" class="p7xat6cnl"/><path fill="url(#iIjIJec)" class="p7xat6cnl"/><path fill="url(#ixovgFc)" class="w879bpb0e"/><path fill="url(#iAwNGNd)" class="w879bpb0e"/><path fill="url(#i4jnpHd)" class="w879bpb0e"/><path fill="url(#ighCgpe)" class="h-e6v32ai"/><path fill="url(#ix5gnYc)" class="h-e6v32ai"/><path fill="url(#iJEWtud)" class="h-e6v32ai"/><path fill="url(#i2e03Ec)" class="h-e6v32ai"/><path fill="url(#i7Hsxxd)" class="h-e6v32ai"/><path fill="url(#iuAwBNe)" class="h-e6v32ai"/><path fill="url(#isDXaed)" class="h-e6v32ai"/><g filter="url(#iLLTiPb)"><path fill="url(#i7AVd4b)" class="p8qfg6btl"/></g><g filter="url(#iO5x27f)"><path fill="url(#iU7U3XT)" class="hbrxqdets"/><path fill="url(#isPRIKd)" class="hbrxqdets"/><path fill="url(#iJ9f8Uc)" class="hbrxqdets"/><path fill="url(#iGFMqWH)" class="hbrxqdets"/><path fill="url(#iRjmOQY)" class="hbrxqdets"/><path fill="url(#iheSTgO)" class="hbrxqdets"/><path stroke="url(#iGAAS2d)" class="lgnz4ib3a"/></g><g filter="url(#irxH7Fw)"><path fill="url(#i8ElAPc)" class="b43uiy30g"/><path fill="url(#ieaWAvd)" class="b43uiy30g"/><path fill="url(#ikytyIb)" class="b43uiy30g"/><path fill="url(#iW4kXJz)" class="b43uiy30g"/></g><path fill="url(#iUDojFc)" class="d-kfqjw9b"/><path fill="url(#iNZ1RrM)" class="d-kfqjw9b"/><g filter="url(#iH1ZBve)"><path fill="url(#iNWjjGA)" class="honnlt_-k"/><path fill="url(#iJ9Nnwe)" class="honnlt_-k"/><path fill="url(#idtl0Rc)" class="honnlt_-k"/><path fill="url(#ixSFL6b)" class="honnlt_-k"/><path fill="url(#iE8rTiR)" class="honnlt_-k"/></g><g filter="url(#i6vfMvd)"><path stroke="url(#iocIDDc)" class="fr6brjbjg"/></g><g filter="url(#iAwVt7b)"><path stroke="url(#iScf76d)" class="qw3x8lb9a"/></g><g filter="url(#iAXDZIW)"><path stroke="url(#i8Runfb)" class="jh5xrccmm"/></g><path fill="url(#i63AZyd)" class="bn4p-sbtt"/><g filter="url(#i0v67Yc)"><path stroke="url(#i2O0dbd)" class="lehnoh0zf"/></g><path fill="url(#i6eBaBe)" class="vww-fqhwh"/><path fill="url(#i11YRMe)" class="vww-fqhwh"/><path fill="url(#i6LROXb)" class="vj4jwbgtj"/><circle fill="url(#iaubL2c)" class="haiup_bzr"/><circle fill="url(#iMrXwDb)" class="haiup_bzr"/><circle fill="url(#i7anBhe)" class="l0dpenbvj"/><circle fill="url(#imcKh6b)" class="l0dpenbvj"/><g filter="url(#i07x69c)"><circle class="nnq1nccuf"/></g><g filter="url(#imNpmFb)"><circle fill="url(#irythzk)" class="h79oecc1t"/></g><g filter="url(#iVXhzcb)"><path fill="url(#iP2JtEc)" class="yj5dctbip"/><path fill="url(#io1421b)" class="yj5dctbip"/><path fill="url(#imQzlYd)" class="yj5dctbip"/></g><path fill="url(#iyycoMc)" class="yj5dctbip"/><g filter="url(#iaGQRvJ)"><path stroke="url(#iwu9b3c)" class="vzg4cacsm"/></g><path class="b75ag19ij"/><g filter="url(#ib5K6zd)"><path class="ki_cky2sb"/></g><g filter="url(#ippRroT)"><path class="kml76ybhm"/><path fill="url(#ia78PcO)" class="j_2ccnt5p"/></g><path fill="url(#iO99dqG)" class="j_2ccnt5p"/><path class="qz94s4bip"/><path fill="url(#icC4OUb)" class="cedz8lbio"/><path class="a07exk92a"/><g filter="url(#ixZmGzb)"><path class="xo9yuc7kj"/><path fill="url(#ihfUwfd)" class="haktz9bdu"/></g><g filter="url(#iUIboCd)"><path fill="url(#ix5afEe)" class="a4o2qybrp"/></g><path class="x9uzmjbio"/><path fill="url(#ijtxEoe)" class="etcccebor"/><path class="cfof8-eyu"/><g filter="url(#iLRB8ee)"><path fill="url(#iKY1KDc)" class="uj99bl4ra"/></g><g filter="url(#ilyINHe)"><ellipse transform="rotate(-27.914 13.293 14.206)" class="f_5qi3ocn"/><ellipse fill="url(#iHvtRfe)" transform="rotate(-27.914 13.293 14.206)" class="vjxojz0pl"/></g><path clip-rule="evenodd" class="lhtf8acxx"/><path clip-rule="evenodd" class="kshibytih"/><g filter="url(#i5to2Yb)"><path class="oqax_hbok"/></g><g filter="url(#ihTXNsb)"><path class="q9zmrccen"/></g><g filter="url(#iPZwcid)"><path fill="url(#iSLGJHd)" clip-rule="evenodd" class="ouyjj2-hs"/></g><defs><radialGradient id="il4bdjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.03125 7.18055 0 20.738 30.442)" gradientUnits="userSpaceOnUse"><stop class="xhqrsjbac"/><stop offset="1" class="ebcvm6lto"/></radialGradient><radialGradient id="iW8yVeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.6875 .78125 0 22.988 29.817)" gradientUnits="userSpaceOnUse"><stop class="wup_v_x-y"/><stop offset="1" class="rec-1hb8e"/></radialGradient><radialGradient id="ilwSyMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 0 0 19.1959 8.613 29.996)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mr4lhnuux"/><stop offset="1" class="q-3947b0q"/></radialGradient><radialGradient id="ipMQjDc" cx="0" cy="0" r="1" gradientTransform="rotate(-136.837 16.423 12.118)scale(15.1664 18.2252)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="q-3947b0q"/><stop offset="1" class="dgbyghhck"/></radialGradient><radialGradient id="ieEwfyb" cx="0" cy="0" r="1" gradientTransform="matrix(.30005 -6.75 3.83344 .1704 8.594 29.88)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="e7_y1ioqg"/><stop offset="1" class="o8c2nzb0a"/></radialGradient><radialGradient id="ibPlbGX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.125 3.97458 0 6.734 30.192)" gradientUnits="userSpaceOnUse"><stop class="dn-ogvbjy"/><stop offset="1" class="inpzxhbwc"/></radialGradient><radialGradient id="i1LfFnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.63745 0 0 -7.24389 8.594 29.996)" gradientUnits="userSpaceOnUse"><stop class="a3c-8ubyu"/><stop offset="1" class="x9tw1mbfn"/></radialGradient><radialGradient id="idbpoub" cx="0" cy="0" r="1" gradientTransform="rotate(82.372 -.267 24.058)scale(8.94581 3.16756)" gradientUnits="userSpaceOnUse"><stop class="embu-7brp"/><stop offset="1" class="veybn72ma"/></radialGradient><radialGradient id="iXwlnbA" cx="0" cy="0" r="1" gradientTransform="matrix(.83557 0 0 8.41461 22.84 29.996)" gradientUnits="userSpaceOnUse"><stop class="rj_n-mbmd"/><stop offset=".85" class="sfuw4b7fs"/></radialGradient><radialGradient id="iSVIuZb" cx="0" cy="0" r="1" gradientTransform="rotate(124.902 .777 14.461)scale(1.63847 5.18259)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="dekz5-i5a"/><stop offset="1" class="takbm9boj"/></radialGradient><radialGradient id="iyT5utc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.625 -11.4392 0 15.709 19.723)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="tclwz7mny"/><stop offset="1" class="c5r226cip"/></radialGradient><radialGradient id="iwDqPAI" cx="0" cy="0" r="1" gradientTransform="matrix(4.9375 -2.78125 .65585 1.16432 19.27 21.973)" gradientUnits="userSpaceOnUse"><stop class="zm3svk-ip"/><stop offset="1" class="f-m4mzz6d"/></radialGradient><radialGradient id="ipFI5hc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75002 2.37497 -1.68941 -2.66754 10.738 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="d45gne0nz"/><stop offset="1" class="f283fd8-c"/></radialGradient><radialGradient id="iqYNBEd" cx="0" cy="0" r="1" gradientTransform="rotate(-69.233 29.08 .534)scale(10.4881 22.9861)" gradientUnits="userSpaceOnUse"><stop offset=".677" class="nypzj9bha"/><stop offset=".949" class="nvdrdzbmz"/></radialGradient><radialGradient id="iAsh0Wp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.88478 14.4983 0 15.709 24.613)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="bgqsi-bps"/><stop offset=".985" class="f-3q63keb"/></radialGradient><radialGradient id="iqTZBPc" cx="0" cy="0" r="1" gradientTransform="matrix(.76562 -.87496 3.20566 2.80509 14.77 24.473)" gradientUnits="userSpaceOnUse"><stop class="rdaygdbpu"/><stop offset="1" class="zajsytjse"/></radialGradient><radialGradient id="iQdlE2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 -.46875 4.21008 -3.78904 19.441 22.223)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="i2wlb99xo"/><stop offset="1" class="l15dqlbvn"/></radialGradient><radialGradient id="iXHj40b" cx="0" cy="0" r="1" gradientTransform="matrix(.8298 -1.3125 2.13746 1.35137 14.879 24.238)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="fqpzwo9rb"/><stop offset="1" class="vyxwjf9nd"/></radialGradient><radialGradient id="in8LAQc" cx="0" cy="0" r="1" gradientTransform="matrix(2.15282 1.92743 -3.57495 3.993 14.056 21.223)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="h2g-zwdna"/><stop offset="1" class="c7hder97f"/></radialGradient><radialGradient id="iOxWFad" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 .96875 -.2841 1.50295 17.082 3.16)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="s_1mw_rhq"/><stop offset="1" class="pql562bff"/></radialGradient><radialGradient id="iDqN3pV" cx="0" cy="0" r="1" gradientTransform="matrix(-4.62501 2.59374 -3.8683 -6.89775 17.988 3.817)" gradientUnits="userSpaceOnUse"><stop offset=".063" class="uhl03ccti"/><stop offset="1" class="uuh3gfbsu"/></radialGradient><radialGradient id="iIjIJec" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 -1.30125 2.428 -12.47818 18.77 7.535)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="tsk-k9bvn"/><stop offset="1" class="phlvo2b_b"/></radialGradient><radialGradient id="ighCgpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15156 -24.7184 0 15.75 9.333)" gradientUnits="userSpaceOnUse"><stop class="r-yilwbra"/><stop offset=".652" class="vxkgnhd4n"/></radialGradient><radialGradient id="ix5gnYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.64742 -17.2274 0 13.022 8.98)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="huu-ickwn"/><stop offset="1" class="t4ibp7bdp"/></radialGradient><radialGradient id="iJEWtud" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68356 0 0 -2.80263 25.977 10.71)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="p5_1r5b0y"/><stop offset="1" class="bkffn87la"/></radialGradient><radialGradient id="i2e03Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-10.1661 0 0 -1.56292 25.094 9.554)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="zdk8j6bjz"/><stop offset="1" class="lmlq_xbrl"/></radialGradient><radialGradient id="i7Hsxxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.15365 1.28841 0 24.918 11.91)" gradientUnits="userSpaceOnUse"><stop offset=".051" class="o8p2_blib"/><stop offset="1" class="szwxs1ffj"/></radialGradient><radialGradient id="iuAwBNe" cx="0" cy="0" r="1" gradientTransform="rotate(-119.268 10.579 6.104)scale(3.2599 6.67388)" gradientUnits="userSpaceOnUse"><stop class="vmjr7rbhn"/><stop offset="1" class="zxip0bczk"/></radialGradient><radialGradient id="isDXaed" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 0 0 1.78125 21.332 18.192)" gradientUnits="userSpaceOnUse"><stop class="iusprebiv"/><stop offset="1" class="n4ma-nbis"/></radialGradient><radialGradient id="i7AVd4b" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 6.823 20.03)scale(1.88642 1.51516)" gradientUnits="userSpaceOnUse"><stop class="id09adcid"/><stop offset=".828" class="gtmq6ja1j"/></radialGradient><radialGradient id="iU7U3XT" cx="0" cy="0" r="1" gradientTransform="matrix(-8.43067 -6.22495 7.88718 -10.6819 24.176 17.817)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="qxprq_b_n"/><stop offset="1" class="id0y_n31u"/></radialGradient><radialGradient id="isPRIKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.19531 0 0 .58033 20.863 13.285)" gradientUnits="userSpaceOnUse"><stop class="azeqcu15x"/><stop offset="1" class="sda7dac5x"/></radialGradient><radialGradient id="iJ9f8Uc" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 .70313 -.43994 .44972 20.066 11.723)" gradientUnits="userSpaceOnUse"><stop class="vnbqzxbma"/><stop offset="1" class="k10k6_baq"/></radialGradient><radialGradient id="iGFMqWH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60937 0 0 -.8125 10.926 13.473)" gradientUnits="userSpaceOnUse"><stop class="x9q-1ua-h"/><stop offset="1" class="d_y83zkbz"/></radialGradient><radialGradient id="iRjmOQY" cx="0" cy="0" r="1" gradientTransform="rotate(-177.049 5.42 8.54)scale(3.03527 4.59892)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="ftdzlkbpm"/><stop offset="1" class="iu-l6acky"/></radialGradient><radialGradient id="iheSTgO" cx="0" cy="0" r="1" gradientTransform="rotate(-50.886 21.06 3.067)scale(3.51696 3.66873)" gradientUnits="userSpaceOnUse"><stop class="ap_fa_bgx"/><stop offset="1" class="wnm2vg-zq"/></radialGradient><radialGradient id="ieaWAvd" cx="0" cy="0" r="1" gradientTransform="matrix(3 3.65625 -3.78158 3.10283 22.894 7.317)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="vas9tjbit"/><stop offset="1" class="ny-1wemya"/></radialGradient><radialGradient id="ikytyIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.61462 -2.0661 0 25.705 7.453)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="viuzncbxq"/><stop offset="1" class="ej1v0hbca"/></radialGradient><radialGradient id="iW4kXJz" cx="0" cy="0" r="1" gradientTransform="rotate(145.359 13.401 8.53)scale(3.99771 2.68184)" gradientUnits="userSpaceOnUse"><stop class="uvv0p6btj"/><stop offset="1" class="elep40b9c"/></radialGradient><radialGradient id="iUDojFc" cx="0" cy="0" r="1" gradientTransform="rotate(144.673 12.844 7.022)scale(4.07349 4.5687)" gradientUnits="userSpaceOnUse"><stop class="a-lhjfbpa"/><stop offset="1" class="begh2ub5w"/></radialGradient><radialGradient id="iNZ1RrM" cx="0" cy="0" r="1" gradientTransform="rotate(-133.348 14.9 -2.216)scale(4.59811 4.64228)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="po1nyh2al"/><stop offset=".913" class="cjnv6q4jy"/></radialGradient><radialGradient id="iJ9Nnwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.68 24.59)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="idtl0Rc" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 23.548 25.966)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="ixSFL6b" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 23.362 27.293)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="iE8rTiR" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 23.267 28.56)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="i63AZyd" cx="0" cy="0" r="1" gradientTransform="rotate(-111.272 15.595 -6.12)scale(2.19652 2.90326)" gradientUnits="userSpaceOnUse"><stop offset=".052" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="i6eBaBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.94125 .375 -1.09725 -2.75404 10.894 17.442)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hg8rz2nvg"/><stop offset="1" class="lwh18t5gz"/></radialGradient><radialGradient id="i11YRMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 -1.35937 1.36127 -1.0327 11.347 19.38)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="b85todb1f"/><stop offset="1" class="vl6e3-baw"/></radialGradient><radialGradient id="i6LROXb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32561 -.24315 .57714 -3.14644 21.566 17.606)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="v7ferz-rr"/><stop offset="1" class="oluafiuzi"/></radialGradient><radialGradient id="iaubL2c" cx="0" cy="0" r="1" gradientTransform="matrix(1.29688 0 0 3.51563 9.613 15.114)" gradientUnits="userSpaceOnUse"><stop class="vtioj5kbd"/><stop offset="1" class="ky8pxwbxb"/></radialGradient><radialGradient id="iMrXwDb" cx="0" cy="0" r="1" gradientTransform="rotate(-104.593 11.658 3.485)scale(2.72866)" gradientUnits="userSpaceOnUse"><stop offset=".607" class="qq0-nslsd"/><stop offset=".968" class="k275oh7lz"/></radialGradient><radialGradient id="i7anBhe" cx="0" cy="0" r="1" gradientTransform="rotate(-96.824 17.787 -1.41)scale(3.68233 4.93437)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="b5vgm5bee"/><stop offset="1" class="iw-vclu3c"/></radialGradient><radialGradient id="imcKh6b" cx="0" cy="0" r="1" gradientTransform="rotate(94.366 3.493 16.918)scale(1.89674)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="caki2bbqc"/><stop offset="1" class="hkouycb-m"/></radialGradient><radialGradient id="irythzk" cx="0" cy="0" r="1" gradientTransform="matrix(.375 -1.65564 1.39563 .3161 20.832 15.535)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="lckgg6b7b"/><stop offset="1" class="mykk3-3_k"/></radialGradient><radialGradient id="iP2JtEc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -5.34375 18.832 16.004)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="sfodr7bel"/><stop offset="1" class="mp__eybbt"/></radialGradient><radialGradient id="io1421b" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -1.0625 .84812 -.79823 13.8 13.91)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="e9xiz6boh"/><stop offset="1" class="lsbbypgwj"/></radialGradient><radialGradient id="imQzlYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.03906 1.50975 0 18.09 13.926)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ea_xfm2ty"/><stop offset="1" class="bs61zmb7g"/></radialGradient><radialGradient id="iyycoMc" cx="0" cy="0" r="1" gradientTransform="scale(9.72937 8.5)rotate(90 .04 1.578)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="wodu9bbyy"/><stop offset="1" class="n_caw02nm"/></radialGradient><radialGradient id="iwu9b3c" cx="0" cy="0" r="1" gradientTransform="matrix(.33594 -.4453 .60326 .4551 14.707 18.535)" gradientUnits="userSpaceOnUse"><stop class="xj1ts9b8a"/><stop offset="1" class="h2cw72ssr"/></radialGradient><radialGradient id="ia78PcO" cx="0" cy="0" r="1" gradientTransform="matrix(-.69154 -2.40962 .94402 -.27092 16.662 16.398)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="r37rgng3f"/><stop offset="1" class="cv-bsn7fp"/></radialGradient><radialGradient id="icC4OUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81359 -1.2941 0 17.941 14.302)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ihfUwfd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.379 2.856)scale(.37895 .52172)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijtxEoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81363 -1.29417 0 13.565 14.301)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iHvtRfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00775 -.49495 .59495 -.00931 13.277 14.52)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSLGJHd" cx="0" cy="0" r="1" gradientTransform="matrix(.03906 -.46875 3.61875 .30156 18.191 11.903)" gradientUnits="userSpaceOnUse"><stop class="v-u_vjbio"/><stop offset=".899" class="xb7h3z26h"/></radialGradient><filter id="iMB6idE" width="12.098" height="6.858" x="9.659" y="17.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".1"/></filter><filter id="iWsBvQe" width="3.75" height="3.003" x="13.834" y="21.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.333333 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1068"/></filter><filter id="iLbEwOe" width="6.328" height="3.25" x="15.66" y="1.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.521569 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1068"/></filter><filter id="iLLTiPb" width="2.584" height="3.682" x="26.124" y="22.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1068"/></filter><filter id="iO5x27f" width="23.09" height="7.66" x="4.2" y="10.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".125"/></filter><filter id="irxH7Fw" width="5.46" height="21.857" x="23.1" y="5.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.45098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1068"/></filter><filter id="iH1ZBve" width="4.996" height="5.556" x="23.362" y="24.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.513726 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1068"/></filter><filter id="i6vfMvd" width="2.047" height=".25" x="23.757" y="25.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".05"/></filter><filter id="iAwVt7b" width="2.047" height=".25" x="23.678" y="27.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".05"/></filter><filter id="iAXDZIW" width="2.047" height=".25" x="23.757" y="28.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".05"/></filter><filter id="i0v67Yc" width="1.8" height="17.408" x="25.202" y="9.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".325"/></filter><filter id="i07x69c" width="2.625" height="2.625" x="9.703" y="13.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".125"/></filter><filter id="imNpmFb" width="2.425" height="2.425" x="19.272" y="13.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".075"/></filter><filter id="iVXhzcb" width="11.175" height="10.15" x="10.386" y="11.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.52549 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1068"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.498039 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1068" result="effect2_innerShadow_4002_1068"/></filter><filter id="iaGQRvJ" width="3.813" height="1.561" x="13.842" y="17.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".05"/></filter><filter id="ib5K6zd" width="2.707" height="3.647" x="14.235" y="14.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".25"/></filter><filter id="ippRroT" width="2.118" height="3.018" x="14.845" y="14.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.615686 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1068"/></filter><filter id="ixZmGzb" width=".788" height=".697" x="17.205" y="13.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".05"/></filter><filter id="iUIboCd" width=".892" height=".914" x="18.048" y="13.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".1"/></filter><filter id="iLRB8ee" width=".987" height="1.041" x="13.593" y="13.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".1"/></filter><filter id="ilyINHe" width=".914" height=".705" x="12.835" y="13.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1068" stdDeviation=".05"/></filter><filter id="i5to2Yb" width="2.242" height="1.109" x="11.984" y="12.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.45098 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1068"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.490196 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1068" result="effect2_innerShadow_4002_1068"/></filter><filter id="ihTXNsb" width="2.242" height="1.109" x="17.289" y="12.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.45098 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1068"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.490196 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1068" result="effect2_innerShadow_4002_1068"/></filter><filter id="iPZwcid" width="4.368" height=".847" x="16.494" y="11.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.568627 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1068"/></filter><linearGradient id="ibfF9pc" x1="21.582" x2="10.613" y1="21.66" y2="21.66" gradientUnits="userSpaceOnUse"><stop class="q8c8skp1q"/><stop offset="1" class="n7c2bfbtc"/></linearGradient><linearGradient id="inhs3Gr" x1="16.175" x2="16.925" y1="19.567" y2="23.848" gradientUnits="userSpaceOnUse"><stop offset=".287" class="cvgk3kbak"/><stop offset="1" class="c6lp81bhp"/></linearGradient><linearGradient id="ir99qxd" x1="19.144" x2="19.472" y1="5.207" y2="3.848" gradientUnits="userSpaceOnUse"><stop class="guc8z7bij"/><stop offset="1" class="iov6rh-pq"/></linearGradient><linearGradient id="iDiuhqc" x1="7.907" x2="22.372" y1="19.98" y2="19.98" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kdl2hbbyb"/><stop offset="1" class="valdy-bly"/></linearGradient><linearGradient id="iirSkZf" x1="17.363" x2="17.363" y1="8.504" y2="7.317" gradientUnits="userSpaceOnUse"><stop class="u3wf8s8gl"/><stop offset="1" class="pt6842k6d"/></linearGradient><linearGradient id="ixovgFc" x1="14.176" x2="20.238" y1="9.91" y2="9.754" gradientUnits="userSpaceOnUse"><stop class="p-go_8bpa"/><stop offset="1" class="tp_ivrbui"/></linearGradient><linearGradient id="iAwNGNd" x1="21.863" x2="19.269" y1="9.285" y2="9.285" gradientUnits="userSpaceOnUse"><stop class="xrhcfrbuk"/><stop offset="1" class="psjmui2lw"/></linearGradient><linearGradient id="i4jnpHd" x1="9.738" x2="11.957" y1="9.519" y2="10.534" gradientUnits="userSpaceOnUse"><stop class="cvjhjoe1h"/><stop offset="1" class="wmajqfcti"/></linearGradient><linearGradient id="iGAAS2d" x1="15.745" x2="15.745" y1="11.364" y2="16.817" gradientUnits="userSpaceOnUse"><stop class="flda2eefx"/><stop offset="1" class="leei8_8-z"/></linearGradient><linearGradient id="i8ElAPc" x1="24.372" x2="28.31" y1="10.532" y2="10.532" gradientUnits="userSpaceOnUse"><stop class="kytdhlviv"/><stop offset="1" class="bf9jtobby"/></linearGradient><linearGradient id="iNWjjGA" x1="27.39" x2="23.362" y1="28.058" y2="28.058" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="xwbtobibq"/></linearGradient><linearGradient id="iocIDDc" x1="25.562" x2="23.726" y1="25.974" y2="25.974" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iScf76d" x1="25.484" x2="23.648" y1="27.278" y2="27.278" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="i8Runfb" x1="25.562" x2="23.726" y1="28.583" y2="28.583" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="i2O0dbd" x1="26.602" x2="26.602" y1="9.925" y2="25.533" gradientUnits="userSpaceOnUse"><stop class="pafpa8b3r"/><stop offset="1" class="irkpemyfq"/></linearGradient><linearGradient id="iO99dqG" x1="15.753" x2="15.753" y1="14.226" y2="15.239" gradientUnits="userSpaceOnUse"><stop class="i-gn0i9xi"/><stop offset="1" class="syzqtdrnf"/></linearGradient><linearGradient id="ix5afEe" x1="18.721" x2="18.407" y1="14.355" y2="14.549" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKY1KDc" x1="14.31" x2="13.996" y1="14.355" y2="14.549" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-mage" /></template>
<style>
.a-lhjfbpa {
  stop-color: var(--svg-color--4ddcff, #4DDCFF);
}

.a07exk92a {
  fill: var(--svg-color--000, #000);
  d: path("M17.43 14.718a.51.51 0 0 1 .514-.513a.51.51 0 0 1 .455.749h-.907a.46.46 0 0 1-.061-.236");
}

.a3c-8ubyu {
  stop-color: var(--svg-color--41a8ff, #41A8FF);
}

.a4o2qybrp {
  d: path("M18.74 14.6a.84.84 0 0 0-.232-.464l-.26.286l.117.228z");
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

.b5vgm5bee {
  stop-color: var(--svg-color--dba632, #DBA632);
}

.b75ag19ij {
  fill: var(--svg-color--89024e, #89024E);
  d: path("M15.749 18.065c-.54 0-1.04-.13-1.47-.35c-.14-.08-.3.09-.21.23a2.006 2.006 0 0 0 3.36 0c.09-.14-.07-.3-.21-.23c-.43.22-.93.35-1.47.35");
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

.bs61zmb7g {
  stop-color: var(--svg-color--fdae21, #FDAE21);
  stop-opacity: 0;
}

.c5r226cip {
  stop-color: var(--svg-color--2483f6, #2483F6);
}

.c6lp81bhp {
  stop-color: var(--svg-color--307099, #307099);
  stop-opacity: 0;
}

.c7hder97f {
  stop-color: var(--svg-color--b0690b, #B0690B);
  stop-opacity: 0;
}

.caki2bbqc {
  stop-color: var(--svg-color--d29a44, #D29A44);
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

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.cv-bsn7fp {
  stop-color: var(--svg-color--ffe235, #FFE235);
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

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
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

.e7_y1ioqg {
  stop-color: var(--svg-color--2e99f4, #2E99F4);
}

.e9xiz6boh {
  stop-color: var(--svg-color--ea9324, #EA9324);
}

.ea_xfm2ty {
  stop-color: var(--svg-color--fdae21, #FDAE21);
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

.f-m4mzz6d {
  stop-color: var(--svg-color--3f9de9, #3F9DE9);
  stop-opacity: 0;
}

.f283fd8-c {
  stop-color: var(--svg-color--1b67ab, #1B67AB);
  stop-opacity: 0;
}

.fgyy3cclr {
  fill: var(--svg-color--39a7ff, #39A7FF);
  d: path("M4.875 29.996c0-2.883 2.987-9.76 10.777-9.76c7.791 0 10.628 6.396 10.868 9.76z");
}

.flda2eefx {
  stop-color: var(--svg-color--4478e6, #4478E6);
}

.fnql1cbvy {
  fill: var(--svg-color--c38d26, #C38D26);
  d: path("m15.45 23.977l-1.616-2.754h3.75l-1.617 2.754a.3.3 0 0 1-.517 0");
}

.fqpzwo9rb {
  stop-color: var(--svg-color--43aaf7, #43AAF7);
}

.fr6brjbjg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.882 25.974h1.796");
}

.ft5dv1b6b {
  fill: none;
}

.ftdzlkbpm {
  stop-color: var(--svg-color--1956ae, #1956AE);
}

.g43afac9g {
  d: path("M15.708 24.473c-.183 0-.687-.155-1.405-.738a192 192 0 0 1-3.762-3.18c-.216-.187-.671-.668-.566-1.192c.164-.82 1.359-1.148 3.203-1.148h5.061c1.844 0 3.04.328 3.203 1.148c.105.524-.35 1.005-.566 1.192a194 194 0 0 1-3.762 3.18c-.718.583-1.155.738-1.405.738z");
}

.g8oaksl8k {
  d: path("M15.694 24.614c-.395 0-1.172-.032-2.446-.477l-.078-.036c-1.438-.657-4.997-2.284-4.851-4.363c0-2.15 3.458-2.156 5.187-1.89h4.405c1.73-.266 5.188-.26 5.188 1.89c.145 2.08-3.414 3.706-4.852 4.363l-.078.036c-1.274.445-2.05.476-2.476.476");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gtmq6ja1j {
  stop-color: var(--svg-color--ffd235, #FFD235);
}

.guc8z7bij {
  stop-color: var(--svg-color--2caafc, #2CAAFC);
}

.gzbsswvik {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
}

.h-e6v32ai {
  d: path("m23.34 18.484l-15.2-.01c-2.45 0-4.45-2-4.45-4.46s2-4.46 4.46-4.46l15.2.01c2.46 0 4.46 2 4.46 4.46a4.48 4.48 0 0 1-4.47 4.46");
}

.h2cw72ssr {
  stop-color: var(--svg-color--ffb236, #FFB236);
  stop-opacity: 0;
}

.h2g-zwdna {
  stop-color: var(--svg-color--954f10, #954F10);
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

.hg8rz2nvg {
  stop-color: var(--svg-color--be9f9c, #BE9F9C);
}

.hkouycb-m {
  stop-color: var(--svg-color--d1954c, #D1954C);
}

.honnlt_-k {
  d: path("M23.362 25.321c0-.4.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.406-.657");
}

.huu-ickwn {
  stop-color: var(--svg-color--2fb4f5, #2FB4F5);
}

.i-gn0i9xi {
  stop-color: var(--svg-color--feb937, #FEB937);
}

.i2wlb99xo {
  stop-color: var(--svg-color--3e6082, #3E6082);
}

.id09adcid {
  stop-color: var(--svg-color--ffe047, #FFE047);
}

.id0y_n31u {
  stop-color: var(--svg-color--2e65d4, #2E65D4);
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

.iw-vclu3c {
  stop-color: var(--svg-color--9b7723, #9B7723);
}

.j_2ccnt5p {
  d: path("m15.383 14.523l-.514 1.786c-.105.367.147.735.504.735h.761c.357 0 .61-.373.504-.735l-.514-1.786c-.11-.396-.625-.396-.74 0");
}

.jh5xrccmm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.882 28.583h1.796");
}

.job-vz29n {
  d: path("M8.594 22.752c-2.616 2.263-3.72 5.491-3.72 7.244h3.72z");
}

.k10k6_baq {
  stop-color: var(--svg-color--0d50a5, #0D50A5);
  stop-opacity: 0;
}

.k275oh7lz {
  stop-color: var(--svg-color--8d6022, #8D6022);
}

.kdl2hbbyb {
  stop-color: var(--svg-color--cacaca, #CACACA);
}

.ki_cky2sb {
  fill: var(--svg-color--f49830, #F49830);
  d: path("m15.241 14.842l-.483 1.677c-.099.345.138.69.473.69h.715c.336 0 .572-.35.474-.69l-.484-1.677c-.103-.372-.586-.372-.695 0");
}

.kml76ybhm {
  fill: var(--svg-color--ffc927, #FFC927);
  d: path("m15.383 14.523l-.514 1.786c-.105.367.147.735.504.735h.761c.357 0 .61-.373.504-.735l-.514-1.786c-.11-.396-.625-.396-.74 0");
}

.kshibytih {
  fill: var(--svg-color--ffbc18, #FFBC18);
  fill-rule: evenodd;
  d: path("M17.235 15.409a.3.3 0 0 0 .013.424c.253.238.573.387.854.478s.55.133.718.142a.3.3 0 1 0 .033-.6a2.4 2.4 0 0 1-.566-.113a1.7 1.7 0 0 1-.628-.344a.3.3 0 0 0-.424.013");
}

.ky8pxwbxb {
  stop-color: var(--svg-color--c57b37, #C57B37);
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

.lckgg6b7b {
  stop-color: var(--svg-color--d09a2d, #D09A2D);
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

.lhtf8acxx {
  fill: var(--svg-color--ffa20d, #FFA20D);
  fill-rule: evenodd;
  d: path("M14.278 15.409a.3.3 0 0 1-.013.424a2.3 2.3 0 0 1-.854.478a3 3 0 0 1-.718.142a.3.3 0 0 1-.033-.6c.118-.006.333-.037.566-.113c.234-.076.462-.189.628-.344a.3.3 0 0 1 .424.013");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmlq_xbrl {
  stop-color: var(--svg-color--2fa3f0, #2FA3F0);
  stop-opacity: 0;
}

.lsbbypgwj {
  stop-color: var(--svg-color--ea9324, #EA9324);
  stop-opacity: 0;
}

.lwh18t5gz {
  stop-color: var(--svg-color--8d868f, #8D868F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mp__eybbt {
  stop-color: var(--svg-color--fba43b, #FBA43B);
}

.mr4lhnuux {
  stop-color: var(--svg-color--2787f2, #2787F2);
}

.mykk3-3_k {
  stop-color: var(--svg-color--c08a25, #C08A25);
}

.n_caw02nm {
  stop-color: var(--svg-color--c57658, #C57658);
}

.n4ma-nbis {
  stop-color: var(--svg-color--1868c3, #1868C3);
  stop-opacity: 0;
}

.n7c2bfbtc {
  stop-color: var(--svg-color--3f7ec7, #3F7EC7);
}

.nnq1nccuf {
  cx: 11.015px;
  cy: 14.942px;
  r: 1.063px;
  fill: var(--svg-color--bc7226, #BC7226);
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

.oluafiuzi {
  stop-color: var(--svg-color--9fa4ab, #9FA4AB);
}

.oqax_hbok {
  stroke: var(--svg-color--b29f9a, #B29F9A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.234 12.99c.222-.17.856-.52 1.742-.376");
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

.p8qfg6btl {
  d: path("M27.09 23.04a.97.97 0 0 1 .968.967v2.214h-1.934v-2.214a.976.976 0 0 1 .967-.967");
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

.q0u2bl4sa {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
  stop-opacity: 0;
}

.q8c8skp1q {
  stop-color: var(--svg-color--3291c8, #3291C8);
}

.q9zmrccen {
  stroke: var(--svg-color--b29f9a, #B29F9A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.281 12.99c-.221-.17-.855-.52-1.742-.376");
}

.qq0-nslsd {
  stop-color: var(--svg-color--c4822a, #C4822A);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3x8lb9a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.804 27.278H25.6");
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

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
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

.s_1mw_rhq {
  stop-color: var(--svg-color--4cdbff, #4CDBFF);
}

.sda7dac5x {
  stop-color: var(--svg-color--215a98, #215A98);
  stop-opacity: 0;
}

.sfodr7bel {
  stop-color: var(--svg-color--ffce30, #FFCE30);
}

.sfuw4b7fs {
  stop-color: var(--svg-color--267adb, #267ADB);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.syzqtdrnf {
  stop-color: var(--svg-color--feb937, #FEB937);
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

.tp_ivrbui {
  stop-color: var(--svg-color--584d65, #584D65);
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
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

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.uuh3gfbsu {
  stop-color: var(--svg-color--2cb1f7, #2CB1F7);
}

.uvv0p6btj {
  stop-color: var(--svg-color--cc8c6f, #CC8C6F);
}

.v-u_vjbio {
  stop-color: var(--svg-color--b4a3a0, #B4A3A0);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7ferz-rr {
  stop-color: var(--svg-color--e4e1e5, #E4E1E5);
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

.vtioj5kbd {
  stop-color: var(--svg-color--c28128, #C28128);
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

.wmajqfcti {
  stop-color: var(--svg-color--423952, #423952);
  stop-opacity: 0;
}

.wnm2vg-zq {
  stop-color: var(--svg-color--3171db, #3171DB);
  stop-opacity: 0;
}

.wodu9bbyy {
  stop-color: var(--svg-color--e99344, #E99344);
  stop-opacity: 0;
}

.wup_v_x-y {
  stop-color: var(--svg-color--46a7ed, #46A7ED);
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

.xb7h3z26h {
  stop-color: var(--svg-color--9c939c, #9C939C);
}

.xhqrsjbac {
  stop-color: var(--svg-color--3180ec, #3180EC);
}

.xj1ts9b8a {
  stop-color: var(--svg-color--ffb236, #FFB236);
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

.xwbtobibq {
  stop-color: var(--svg-color--ffae37, #FFAE37);
}

.yj5dctbip {
  d: path("M20.955 13.26q0-.015 0 0c.026-.695 0-1.087-.577-1.576c-.293-.218-.523-.32-1.365-.32H12.59c-.82 0-1.466.304-1.727.598c-.26.293-.367.574-.312 1.298l.27 4.69c.265 1.958 1.952 3.414 3.955 3.414h1.92c2.003 0 3.69-1.466 3.955-3.414z");
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
