<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fgyy3cclr"/><path fill="url(#il4bdjb)" class="u43ch0b3o"/><path fill="url(#iW8yVeb)" class="u43ch0b3o"/><path fill="url(#ilwSyMe)" class="u43ch0b3o"/><path fill="url(#ipMQjDc)" class="u43ch0b3o"/><path fill="url(#ieEwfyb)" class="job-vz29n"/><path fill="url(#ibPlbGX)" class="job-vz29n"/><path fill="url(#i1LfFnc)" class="job-vz29n"/><path fill="url(#idbpoub)" class="zc_ep_0uq"/><path fill="url(#iXwlnbA)" class="zc_ep_0uq"/><path fill="url(#ibfF9pc)" class="g8oaksl8k"/><path fill="url(#iSVIuZb)" class="g8oaksl8k"/><path fill="url(#iyT5utc)" class="g8oaksl8k"/><path fill="url(#iwDqPAI)" class="g8oaksl8k"/><path fill="url(#ipFI5hc)" class="g8oaksl8k"/><path fill="url(#iqYNBEd)" class="g8oaksl8k"/><path fill="url(#iAsh0Wp)" class="g8oaksl8k"/><g filter="url(#iR5wycd)"><path class="edkhrwbqz"/><path fill="url(#iqTZBPc)" class="g43afac9g"/><path fill="url(#ijdnghj)" class="g43afac9g"/><path fill="url(#iQdlE2c)" class="g43afac9g"/><path fill="url(#iZau3ke)" class="g43afac9g"/><path stroke="url(#iXHj40b)" class="xp31u8b0s"/></g><g filter="url(#iKDjAle)"><path class="h5iei_ivh"/><path fill="url(#ihdS4Xd)" class="xr99hwbgq"/><path fill="url(#iiaVL3o)" class="xr99hwbgq"/></g><g filter="url(#iq0aN8c)"><path fill="url(#iOxWFad)" class="d86qxubue"/><path fill="url(#ir99qxd)" class="d86qxubue"/></g><path fill="url(#iDiuhqc)" class="zcpjvdbuo"/><path fill="url(#iDiuhqc)" class="zcpjvdbuo"/><path fill="url(#iDqN3pV)" class="p7xat6cnl"/><path fill="url(#iirSkZf)" class="p7xat6cnl"/><path fill="url(#iIjIJec)" class="p7xat6cnl"/><path fill="url(#ixovgFc)" class="w879bpb0e"/><path fill="url(#iAwNGNd)" class="w879bpb0e"/><path fill="url(#i4jnpHd)" class="w879bpb0e"/><path fill="url(#ighCgpe)" class="h-e6v32ai"/><path fill="url(#ix5gnYc)" class="h-e6v32ai"/><path fill="url(#iJEWtud)" class="h-e6v32ai"/><path fill="url(#i2e03Ec)" class="h-e6v32ai"/><path fill="url(#i7Hsxxd)" class="h-e6v32ai"/><path fill="url(#iuAwBNe)" class="h-e6v32ai"/><path fill="url(#isDXaed)" class="h-e6v32ai"/><path fill="url(#iNEkG2c)" class="p8qfg6btl"/><path fill="url(#iBVzrkb)" class="p8qfg6btl"/><g filter="url(#iCa6lBe)"><path fill="url(#iU7U3XT)" class="hbrxqdets"/><path fill="url(#isPRIKd)" class="hbrxqdets"/><path fill="url(#iGFMqWH)" class="hbrxqdets"/><path fill="url(#iRjmOQY)" class="hbrxqdets"/><path fill="url(#iheSTgO)" class="hbrxqdets"/><path fill="url(#i3xa2Qb)" class="hbrxqdets"/><path stroke="url(#iGAAS2d)" class="lgnz4ib3a"/></g><g filter="url(#iP8ruob)"><path fill="url(#i8ElAPc)" class="b43uiy30g"/><path fill="url(#ieaWAvd)" class="b43uiy30g"/><path fill="url(#ikytyIb)" class="b43uiy30g"/><path fill="url(#iW4kXJz)" class="b43uiy30g"/></g><path fill="url(#iUDojFc)" class="d-kfqjw9b"/><path fill="url(#iNZ1RrM)" class="d-kfqjw9b"/><g filter="url(#iECybde)"><path fill="url(#ibFShid)" class="honnlt_-k"/><path fill="url(#i8vIFMd)" class="honnlt_-k"/><path fill="url(#iUYakNX)" class="honnlt_-k"/><path fill="url(#ipW7b6e)" class="honnlt_-k"/><path fill="url(#iXTLObd)" class="honnlt_-k"/></g><g filter="url(#iNDGWXd)"><path stroke="url(#iRIbUVd)" class="k5utdqyeu"/></g><g filter="url(#i5WbD0b)"><path stroke="url(#iOR4BIb)" class="a6su9fb1l"/></g><g filter="url(#ifLmWjd)"><path stroke="url(#iAOWJUc)" class="ip_9wm34q"/></g><path fill="url(#i63AZyd)" class="bn4p-sbtt"/><g filter="url(#i5ZHb0W)"><path stroke="url(#i2O0dbd)" class="lehnoh0zf"/></g><g filter="url(#iqbnete)"><path class="vuytovdqu"/><path fill="url(#iIXmjnb)" class="q5i0a9bwz"/><path fill="url(#i45kSDe)" class="q5i0a9bwz"/><path fill="url(#ifl02dd)" class="q5i0a9bwz"/><path fill="url(#iJk7q8d)" class="q5i0a9bwz"/></g><path class="o1d5qg3pu"/><path fill="url(#iFGWO1c)" class="vsd8sfd_d"/><path fill="url(#idWQnAb)" class="vsd8sfd_d"/><path fill="url(#iJeSElc)" class="vsd8sfd_d"/><path fill="url(#ilE1csb)" class="vsd8sfd_d"/><circle fill="url(#iT6aAZc)" class="sagflfyry"/><circle fill="url(#iqyykyd)" class="n0dan8b9v"/><g filter="url(#izzavsc)"><circle class="cxdw6g70z"/></g><g filter="url(#iAahzQb)"><circle fill="url(#i9mSNSJ)" class="j0bdllbjm"/></g><g filter="url(#i4zwvdd)"><path fill="url(#i6WoQjc)" class="ky591i9tr"/><path fill="url(#ipAdbxe)" class="ky591i9tr"/><path fill="url(#i0FA6wd)" class="ky591i9tr"/></g><path fill="url(#iMmj9fb)" class="ky591i9tr"/><path fill="url(#iFfYpkX)" class="ky591i9tr"/><path fill="url(#iMWqHDb)" class="ky591i9tr"/><g filter="url(#iudPAJd)"><path stroke="url(#iBfaUjb)" class="levh51jdk"/></g><path class="ak0pd42ye"/><g filter="url(#iQ3Hjsq)"><path class="z6ppokb8f"/></g><g filter="url(#iek4Ooc)"><path class="tuhucxbhy"/><path fill="url(#iAulCCy)" class="wp3rp0tep"/></g><path class="gj17nkbbl"/><path fill="url(#ieJNRkc)" class="wp3rp0tep"/><path fill="url(#iIJmree)" class="wp3rp0tep"/><path fill="url(#ixX8M7d)" class="wp3rp0tep"/><path fill="url(#iv4WNyc)" class="wp3rp0tep"/><g filter="url(#iys2cwe)"><path class="g1n33qbpu"/></g><g filter="url(#iVjdw0d)"><path class="wmwyugb7z"/></g><path class="h6-csrbqg"/><path fill="url(#iQNpkLH)" class="j3frkab0z"/><path class="is58fbc8j"/><g filter="url(#izIGUJc)"><path class="i9a1drbux"/><path fill="url(#i8emz2W)" class="zed3qmbmr"/></g><g filter="url(#iJGUGab)"><path fill="url(#i7MmYAd)" class="j47g61b-d"/></g><path class="ef0gzvaho"/><path fill="url(#iKOD9Pf)" class="b-6c_bccd"/><path class="t9x94gnsu"/><g filter="url(#iQ8Aw9k)"><path fill="url(#iLaCD5c)" class="w8ll1ib0l"/></g><g filter="url(#iJv4Eux)"><ellipse transform="rotate(-27.914 13.3 15.503)" class="vba4otbgo"/><ellipse fill="url(#ioyNiBd)" transform="rotate(-27.914 13.3 15.503)" class="o8l12hb_l"/></g><path clip-rule="evenodd" class="vrxagqoeq"/><path clip-rule="evenodd" class="hrpwn2zwe"/><g filter="url(#ixK9Ivb)"><path class="bao-05v2t"/><path stroke="url(#i9Nr5tS)" class="e819d0vit"/></g><g filter="url(#i5m4fVb)"><path class="g5a0xac4q"/><path stroke="url(#ioZwABe)" class="l_-nnctap"/></g><defs><radialGradient id="il4bdjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.03125 7.18055 0 20.738 30.442)" gradientUnits="userSpaceOnUse"><stop class="xhqrsjbac"/><stop offset="1" class="ebcvm6lto"/></radialGradient><radialGradient id="iW8yVeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.6875 .78125 0 22.988 29.817)" gradientUnits="userSpaceOnUse"><stop class="wup_v_x-y"/><stop offset="1" class="rec-1hb8e"/></radialGradient><radialGradient id="ilwSyMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 0 0 19.1959 8.613 29.996)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mr4lhnuux"/><stop offset="1" class="q-3947b0q"/></radialGradient><radialGradient id="ipMQjDc" cx="0" cy="0" r="1" gradientTransform="rotate(-136.837 16.423 12.118)scale(15.1664 18.2252)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="q-3947b0q"/><stop offset="1" class="dgbyghhck"/></radialGradient><radialGradient id="ieEwfyb" cx="0" cy="0" r="1" gradientTransform="matrix(.30005 -6.75 3.83344 .1704 8.594 29.88)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="e7_y1ioqg"/><stop offset="1" class="o8c2nzb0a"/></radialGradient><radialGradient id="ibPlbGX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.125 3.97458 0 6.734 30.192)" gradientUnits="userSpaceOnUse"><stop class="dn-ogvbjy"/><stop offset="1" class="inpzxhbwc"/></radialGradient><radialGradient id="i1LfFnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.63745 0 0 -7.24389 8.594 29.996)" gradientUnits="userSpaceOnUse"><stop class="a3c-8ubyu"/><stop offset="1" class="x9tw1mbfn"/></radialGradient><radialGradient id="idbpoub" cx="0" cy="0" r="1" gradientTransform="rotate(82.372 -.267 24.058)scale(8.94581 3.16756)" gradientUnits="userSpaceOnUse"><stop class="embu-7brp"/><stop offset="1" class="veybn72ma"/></radialGradient><radialGradient id="iXwlnbA" cx="0" cy="0" r="1" gradientTransform="matrix(.83557 0 0 8.41461 22.84 29.996)" gradientUnits="userSpaceOnUse"><stop class="rj_n-mbmd"/><stop offset=".85" class="sfuw4b7fs"/></radialGradient><radialGradient id="iSVIuZb" cx="0" cy="0" r="1" gradientTransform="rotate(124.902 .777 14.461)scale(1.63847 5.18259)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="dekz5-i5a"/><stop offset="1" class="takbm9boj"/></radialGradient><radialGradient id="iyT5utc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.625 -11.4392 0 15.709 19.723)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="tclwz7mny"/><stop offset="1" class="c5r226cip"/></radialGradient><radialGradient id="iwDqPAI" cx="0" cy="0" r="1" gradientTransform="matrix(4.9375 -2.78125 .65585 1.16432 19.27 21.973)" gradientUnits="userSpaceOnUse"><stop class="zm3svk-ip"/><stop offset="1" class="f-m4mzz6d"/></radialGradient><radialGradient id="ipFI5hc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75002 2.37497 -1.68941 -2.66754 10.738 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="d45gne0nz"/><stop offset="1" class="f283fd8-c"/></radialGradient><radialGradient id="iqYNBEd" cx="0" cy="0" r="1" gradientTransform="rotate(-69.233 29.08 .534)scale(10.4881 22.9861)" gradientUnits="userSpaceOnUse"><stop offset=".677" class="nypzj9bha"/><stop offset=".949" class="nvdrdzbmz"/></radialGradient><radialGradient id="iAsh0Wp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.88478 14.4983 0 15.709 24.613)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="bgqsi-bps"/><stop offset=".985" class="f-3q63keb"/></radialGradient><radialGradient id="iqTZBPc" cx="0" cy="0" r="1" gradientTransform="matrix(.76562 -.87496 3.20566 2.80509 14.77 24.473)" gradientUnits="userSpaceOnUse"><stop class="rdaygdbpu"/><stop offset="1" class="zajsytjse"/></radialGradient><radialGradient id="iQdlE2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 -.46875 4.21008 -3.78904 19.441 22.223)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="i2wlb99xo"/><stop offset="1" class="l15dqlbvn"/></radialGradient><radialGradient id="iZau3ke" cx="0" cy="0" r="1" gradientTransform="rotate(142.134 5.394 14.516)scale(3.61466 .90443)" gradientUnits="userSpaceOnUse"><stop class="ogllkib3n"/><stop offset="1" class="h-njqxe6y"/></radialGradient><radialGradient id="iXHj40b" cx="0" cy="0" r="1" gradientTransform="matrix(.8298 -1.3125 2.13746 1.35137 14.879 24.238)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="fqpzwo9rb"/><stop offset="1" class="vyxwjf9nd"/></radialGradient><radialGradient id="ihdS4Xd" cx="0" cy="0" r="1" gradientTransform="matrix(2.15282 1.92743 -3.57495 3.993 14.056 21.223)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="kjht8876i"/><stop offset="1" class="m2k7t6jeu"/></radialGradient><radialGradient id="iiaVL3o" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48318 3.03117 -.28115 -.13757 17.117 21.223)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="a4bu2nb4b"/><stop offset="1" class="re9u_5b4n"/></radialGradient><radialGradient id="iOxWFad" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 .96875 -.2841 1.50295 17.082 3.16)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="s_1mw_rhq"/><stop offset="1" class="pql562bff"/></radialGradient><radialGradient id="iDqN3pV" cx="0" cy="0" r="1" gradientTransform="matrix(-4.62501 2.59374 -3.8683 -6.89775 17.988 3.817)" gradientUnits="userSpaceOnUse"><stop offset=".063" class="uhl03ccti"/><stop offset="1" class="uuh3gfbsu"/></radialGradient><radialGradient id="iIjIJec" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 -1.30125 2.428 -12.47818 18.77 7.535)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="tsk-k9bvn"/><stop offset="1" class="phlvo2b_b"/></radialGradient><radialGradient id="ighCgpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15156 -24.7184 0 15.75 9.333)" gradientUnits="userSpaceOnUse"><stop class="r-yilwbra"/><stop offset=".652" class="vxkgnhd4n"/></radialGradient><radialGradient id="ix5gnYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.64742 -17.2274 0 13.022 8.98)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="huu-ickwn"/><stop offset="1" class="t4ibp7bdp"/></radialGradient><radialGradient id="iJEWtud" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68356 0 0 -2.80263 25.977 10.71)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="p5_1r5b0y"/><stop offset="1" class="bkffn87la"/></radialGradient><radialGradient id="i2e03Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-10.1661 0 0 -1.56292 25.094 9.554)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="zdk8j6bjz"/><stop offset="1" class="lmlq_xbrl"/></radialGradient><radialGradient id="i7Hsxxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.15365 1.28841 0 24.918 11.91)" gradientUnits="userSpaceOnUse"><stop offset=".051" class="o8p2_blib"/><stop offset="1" class="szwxs1ffj"/></radialGradient><radialGradient id="iuAwBNe" cx="0" cy="0" r="1" gradientTransform="rotate(-119.268 10.579 6.104)scale(3.2599 6.67388)" gradientUnits="userSpaceOnUse"><stop class="vmjr7rbhn"/><stop offset="1" class="zxip0bczk"/></radialGradient><radialGradient id="isDXaed" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 0 0 1.78125 21.332 18.192)" gradientUnits="userSpaceOnUse"><stop class="iusprebiv"/><stop offset="1" class="n4ma-nbis"/></radialGradient><radialGradient id="iNEkG2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68781 1.6831 -2.07966 -2.08548 28.148 23.303)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iBVzrkb" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 27.822 23.52)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="iU7U3XT" cx="0" cy="0" r="1" gradientTransform="matrix(-8.43067 -6.22495 7.88718 -10.6819 24.176 17.817)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="qxprq_b_n"/><stop offset="1" class="id0y_n31u"/></radialGradient><radialGradient id="isPRIKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.19531 0 0 .58033 20.863 13.285)" gradientUnits="userSpaceOnUse"><stop class="azeqcu15x"/><stop offset="1" class="sda7dac5x"/></radialGradient><radialGradient id="iGFMqWH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60937 0 0 -.8125 10.926 13.473)" gradientUnits="userSpaceOnUse"><stop class="x9q-1ua-h"/><stop offset="1" class="d_y83zkbz"/></radialGradient><radialGradient id="iRjmOQY" cx="0" cy="0" r="1" gradientTransform="rotate(-177.049 5.42 8.54)scale(3.03527 4.59892)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="ftdzlkbpm"/><stop offset="1" class="iu-l6acky"/></radialGradient><radialGradient id="iheSTgO" cx="0" cy="0" r="1" gradientTransform="rotate(-50.886 21.06 3.067)scale(3.51696 3.66873)" gradientUnits="userSpaceOnUse"><stop class="ap_fa_bgx"/><stop offset="1" class="wnm2vg-zq"/></radialGradient><radialGradient id="i3xa2Qb" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 0 0 5.40625 21.062 11.79)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="c53rjnbho"/><stop offset="1" class="z3taopbho"/></radialGradient><radialGradient id="ieaWAvd" cx="0" cy="0" r="1" gradientTransform="matrix(3 3.65625 -3.78158 3.10283 22.894 7.317)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="vas9tjbit"/><stop offset="1" class="ny-1wemya"/></radialGradient><radialGradient id="ikytyIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.61462 -2.0661 0 25.705 7.453)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="viuzncbxq"/><stop offset="1" class="ej1v0hbca"/></radialGradient><radialGradient id="iW4kXJz" cx="0" cy="0" r="1" gradientTransform="rotate(145.359 13.401 8.53)scale(3.99771 2.68184)" gradientUnits="userSpaceOnUse"><stop class="uvv0p6btj"/><stop offset="1" class="elep40b9c"/></radialGradient><radialGradient id="iUDojFc" cx="0" cy="0" r="1" gradientTransform="rotate(144.673 12.844 7.022)scale(4.07349 4.5687)" gradientUnits="userSpaceOnUse"><stop class="a-lhjfbpa"/><stop offset="1" class="begh2ub5w"/></radialGradient><radialGradient id="iNZ1RrM" cx="0" cy="0" r="1" gradientTransform="rotate(-133.348 14.9 -2.216)scale(4.59811 4.64228)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="po1nyh2al"/><stop offset=".913" class="cjnv6q4jy"/></radialGradient><radialGradient id="i8vIFMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.012 25.3)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iUYakNX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.012 26.595)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ipW7b6e" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.012 27.845)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iXTLObd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.012 29.196)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="i63AZyd" cx="0" cy="0" r="1" gradientTransform="rotate(-111.272 15.595 -6.12)scale(2.19652 2.90326)" gradientUnits="userSpaceOnUse"><stop offset=".052" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="iIXmjnb" cx="0" cy="0" r="1" gradientTransform="matrix(4.21875 0 0 1.2718 16.75 11.852)" gradientUnits="userSpaceOnUse"><stop class="ouurtaccv"/><stop offset="1" class="xr0zhtbtu"/></radialGradient><radialGradient id="i45kSDe" cx="0" cy="0" r="1" gradientTransform="matrix(4.37205 1.15625 -2.08826 7.8962 18.065 14.759)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="nfs1x8y7a"/><stop offset="1" class="v25xlcb-w"/></radialGradient><radialGradient id="ifl02dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.53516 1.10937 0 20.843 15.169)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="briue9bpm"/><stop offset="1" class="u7z6ngbib"/></radialGradient><radialGradient id="iJk7q8d" cx="0" cy="0" r="1" gradientTransform="matrix(3.62206 -3.85156 7.57442 7.12308 18.065 15.384)" gradientUnits="userSpaceOnUse"><stop offset=".809" class="ag1ksrb9e"/><stop offset=".989" class="gtvkj1bzh"/></radialGradient><radialGradient id="iFGWO1c" cx="0" cy="0" r="1" gradientTransform="rotate(162.216 5.016 8.618)scale(3.13201 5.57814)" gradientUnits="userSpaceOnUse"><stop offset=".669" class="h7bve-ieg"/><stop offset=".931" class="bob4ejbbv"/></radialGradient><radialGradient id="idWQnAb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78218 1.96086 -.96988 -.8815 11.28 13.712)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="v4785wmtk"/><stop offset="1" class="ylc4ncdmx"/></radialGradient><radialGradient id="iJeSElc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33643 .94957 -.27358 -.38504 11.693 12)" gradientUnits="userSpaceOnUse"><stop class="jwpaqlbcq"/><stop offset="1" class="in01aqbzo"/></radialGradient><radialGradient id="iT6aAZc" cx="0" cy="0" r="1" gradientTransform="matrix(1.31203 0 0 3.5567 9.615 16.397)" gradientUnits="userSpaceOnUse"><stop class="mh2c_fbnn"/><stop offset="1" class="oluxj4fur"/></radialGradient><radialGradient id="iqyykyd" cx="0" cy="0" r="1" gradientTransform="matrix(1.6756 -2.5134 1.27676 .85118 20.302 17.144)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="af7g4xwlv"/><stop offset="1" class="dq3narb_o"/></radialGradient><radialGradient id="i9mSNSJ" cx="0" cy="0" r="1" gradientTransform="matrix(1.3328 0 0 1.12348 20.29 15.973)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="kmiii3bcp"/><stop offset="1" class="tnz7odosx"/></radialGradient><radialGradient id="i6WoQjc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.40625 0 0 -6.38191 17.906 16.849)" gradientUnits="userSpaceOnUse"><stop class="trd9_ubam"/><stop offset="1" class="gyvlymobj"/></radialGradient><radialGradient id="ipAdbxe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20264 0 0 -5.84375 20.827 13.977)" gradientUnits="userSpaceOnUse"><stop class="zebejbccq"/><stop offset="1" class="lmmcg9zod"/></radialGradient><radialGradient id="i0FA6wd" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 -1 .7631 2.09852 17.859 12.337)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="vi9njcc_v"/><stop offset=".997" class="w0tqq_bpv"/></radialGradient><radialGradient id="iMmj9fb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.8125 -7.55046 0 15.69 14.571)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="vofdj6ror"/><stop offset="1" class="dq6qhab8i"/></radialGradient><radialGradient id="iFfYpkX" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.21875 -7.70283 0 13.093 11.009)" gradientUnits="userSpaceOnUse"><stop offset=".056" class="kzandbcfp"/><stop offset="1" class="tw2c8iblg"/></radialGradient><radialGradient id="iMWqHDb" cx="0" cy="0" r="1" gradientTransform="rotate(141.318 3.605 7.742)scale(3.21254 .93832)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="zy380ub3a"/><stop offset="1" class="ijglzsb6p"/></radialGradient><radialGradient id="iBfaUjb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.018 24.526 -2.719)scale(.46901 1.37903)" gradientUnits="userSpaceOnUse"><stop class="wf44ko9cr"/><stop offset="1" class="q977sk--x"/></radialGradient><radialGradient id="iAulCCy" cx="0" cy="0" r="1" gradientTransform="rotate(-106.463 14.933 2.629)scale(2.39117 .96019)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="r37rgng3f"/><stop offset="1" class="cv-bsn7fp"/></radialGradient><radialGradient id="iv4WNyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19695 -.60038 0 16.064 17.801)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iQNpkLH" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.935 15.599)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i8emz2W" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.694 3.505)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKOD9Pf" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.571 15.599)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ioyNiBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.284 15.818)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9Nr5tS" cx="0" cy="0" r="1" gradientTransform="matrix(-.33594 .0079 -.01842 -.7833 14.204 13.639)" gradientUnits="userSpaceOnUse"><stop class="s4irvhbcf"/><stop offset="1" class="g2tp3zwoc"/></radialGradient><radialGradient id="ioZwABe" cx="0" cy="0" r="1" gradientTransform="rotate(-154.746 11.375 4.87)scale(.45782 1.06747)" gradientUnits="userSpaceOnUse"><stop class="s4irvhbcf"/><stop offset="1" class="g2tp3zwoc"/></radialGradient><filter id="iR5wycd" width="12.098" height="6.858" x="9.659" y="17.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".1"/></filter><filter id="iKDjAle" width="3.75" height="3.003" x="13.834" y="21.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.105882 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/></filter><filter id="iq0aN8c" width="6.328" height="3.25" x="15.66" y="1.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.521569 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/></filter><filter id="iCa6lBe" width="23.09" height="7.66" x="4.2" y="10.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".125"/></filter><filter id="iP8ruob" width="5.46" height="21.857" x="23.1" y="5.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.45098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/></filter><filter id="iECybde" width="4.846" height="5.556" x="23.362" y="24.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/></filter><filter id="iNDGWXd" width="2.097" height=".3" x="23.732" y="25.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".05"/></filter><filter id="i5WbD0b" width="2.097" height=".3" x="23.654" y="27.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".05"/></filter><filter id="ifLmWjd" width="2.097" height=".3" x="23.732" y="28.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".05"/></filter><filter id="i5ZHb0W" width="1.8" height="17.408" x="25.202" y="9.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".325"/></filter><filter id="iqbnete" width="8.081" height="7.473" x="14.024" y="11.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.443137 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/></filter><filter id="izzavsc" width="2.813" height="2.813" x="9.628" y="14.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".125"/></filter><filter id="iAahzQb" width="2.612" height="2.612" x="19.16" y="14.917" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".075"/></filter><filter id="i4zwvdd" width="11.026" height="10.833" x="10.551" y="11.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.239216 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.12549 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1072" result="effect2_innerShadow_4002_1072"/></filter><filter id="iudPAJd" width="3.679" height="1.482" x="13.849" y="18.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".05"/></filter><filter id="iQ3Hjsq" width="2.781" height="3.682" x="14.238" y="15.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".25"/></filter><filter id="iek4Ooc" width="2.081" height="2.882" x="14.863" y="15.427" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.615686 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/></filter><filter id="iys2cwe" width="3.001" height="1.285" x="16.695" y="14.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/></filter><filter id="iVjdw0d" width="3.001" height="1.285" x="11.81" y="14.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/></filter><filter id="izIGUJc" width=".786" height=".696" x="17.201" y="15.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".05"/></filter><filter id="iJGUGab" width=".891" height=".913" x="18.041" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".1"/></filter><filter id="iQ8Aw9k" width=".986" height="1.04" x="13.598" y="15.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".1"/></filter><filter id="iJv4Eux" width=".912" height=".704" x="12.843" y="15.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1072" stdDeviation=".05"/></filter><filter id="ixK9Ivb" width="2.377" height="1.141" x="11.915" y="13.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.384314 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.643137 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1072" result="effect2_innerShadow_4002_1072"/></filter><filter id="i5m4fVb" width="2.377" height="1.141" x="17.275" y="13.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.384314 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1072"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.643137 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1072" result="effect2_innerShadow_4002_1072"/></filter><linearGradient id="ibfF9pc" x1="21.582" x2="10.613" y1="21.66" y2="21.66" gradientUnits="userSpaceOnUse"><stop class="q8c8skp1q"/><stop offset="1" class="n7c2bfbtc"/></linearGradient><linearGradient id="ijdnghj" x1="16.175" x2="16.925" y1="19.567" y2="23.848" gradientUnits="userSpaceOnUse"><stop offset=".391" class="cvgk3kbak"/><stop offset="1" class="c6lp81bhp"/></linearGradient><linearGradient id="ir99qxd" x1="19.144" x2="19.472" y1="5.207" y2="3.848" gradientUnits="userSpaceOnUse"><stop class="guc8z7bij"/><stop offset="1" class="iov6rh-pq"/></linearGradient><linearGradient id="iDiuhqc" x1="7.907" x2="22.372" y1="19.98" y2="19.98" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kdl2hbbyb"/><stop offset="1" class="valdy-bly"/></linearGradient><linearGradient id="iirSkZf" x1="17.363" x2="17.363" y1="8.504" y2="7.317" gradientUnits="userSpaceOnUse"><stop class="u3wf8s8gl"/><stop offset="1" class="pt6842k6d"/></linearGradient><linearGradient id="ixovgFc" x1="14.176" x2="20.238" y1="9.91" y2="9.754" gradientUnits="userSpaceOnUse"><stop class="p-go_8bpa"/><stop offset="1" class="tp_ivrbui"/></linearGradient><linearGradient id="iAwNGNd" x1="21.863" x2="19.269" y1="9.285" y2="9.285" gradientUnits="userSpaceOnUse"><stop class="xrhcfrbuk"/><stop offset="1" class="psjmui2lw"/></linearGradient><linearGradient id="i4jnpHd" x1="9.738" x2="11.957" y1="9.519" y2="10.534" gradientUnits="userSpaceOnUse"><stop class="cvjhjoe1h"/><stop offset="1" class="wmajqfcti"/></linearGradient><linearGradient id="iGAAS2d" x1="15.745" x2="15.745" y1="11.364" y2="16.817" gradientUnits="userSpaceOnUse"><stop class="flda2eefx"/><stop offset="1" class="leei8_8-z"/></linearGradient><linearGradient id="i8ElAPc" x1="24.372" x2="28.31" y1="10.532" y2="10.532" gradientUnits="userSpaceOnUse"><stop class="kytdhlviv"/><stop offset="1" class="bf9jtobby"/></linearGradient><linearGradient id="ibFShid" x1="27.743" x2="23.362" y1="28.058" y2="28.058" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iRIbUVd" x1="23.882" x2="25.591" y1="26.052" y2="26.052" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iOR4BIb" x1="23.803" x2="25.513" y1="27.356" y2="27.356" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iAOWJUc" x1="23.882" x2="25.591" y1="28.661" y2="28.661" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="i2O0dbd" x1="26.602" x2="26.602" y1="9.925" y2="25.533" gradientUnits="userSpaceOnUse"><stop class="pafpa8b3r"/><stop offset="1" class="irkpemyfq"/></linearGradient><linearGradient id="ilE1csb" x1="10.721" x2="10.721" y1="11.54" y2="12.087" gradientUnits="userSpaceOnUse"><stop class="ujfp-d7qs"/><stop offset="1" class="my23gcbcn"/></linearGradient><linearGradient id="ieJNRkc" x1="14.933" x2="15.823" y1="17.243" y2="17.243" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iIJmree" x1="16.644" x2="15.67" y1="17.566" y2="17.553" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="ixX8M7d" x1="15.938" x2="15.938" y1="18.308" y2="17.735" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="i7MmYAd" x1="18.713" x2="18.399" y1="15.653" y2="15.846" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLaCD5c" x1="14.315" x2="14.001" y1="15.653" y2="15.846" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-mage-dark" /></template>
<style>
.a-lhjfbpa {
  stop-color: var(--svg-color--4ddcff, #4DDCFF);
}

.a3c-8ubyu {
  stop-color: var(--svg-color--41a8ff, #41A8FF);
}

.a4bu2nb4b {
  stop-color: var(--svg-color--433a3c, #433A3C);
}

.a6su9fb1l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.804 27.278H25.6");
}

.af7g4xwlv {
  stop-color: var(--svg-color--3f292c, #3F292C);
}

.ag1ksrb9e {
  stop-color: var(--svg-color--6a75b9, #6A75B9);
  stop-opacity: 0;
}

.ak0pd42ye {
  fill: var(--svg-color--290118, #290118);
  d: path("M15.689 19.389a3.14 3.14 0 0 1-1.434-.342c-.137-.078-.293.088-.205.225a1.957 1.957 0 0 0 3.278 0c.088-.137-.068-.293-.205-.225c-.42.215-.907.342-1.434.342");
}

.ap_fa_bgx {
  stop-color: var(--svg-color--3171db, #3171DB);
}

.azeqcu15x {
  stop-color: var(--svg-color--215a98, #215A98);
}

.b-6c_bccd {
  d: path("M13.569 15.122a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.b43uiy30g {
  d: path("M26.94 5.304c-.2-.11-.45.04-.45.27v1.62c0 .44-.36.81-.8.8a.786.786 0 0 1-.77-.78v-1.64c0-.23-.25-.38-.45-.27c-.81.44-1.36 1.29-1.37 2.27c-.01 1.01.58 1.9 1.43 2.34c.1.05.16.15.16.26v15.91c0 .57.47 1.04 1.04 1.04s1.04-.47 1.04-1.04v-15.93c0-.11.06-.21.16-.26a2.605 2.605 0 0 0 .01-4.59");
}

.bao-05v2t {
  stroke: var(--svg-color--a9aaaf, #A9AAAF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.19 14.04c.297-.188.856-.45 1.778-.293");
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

.bob4ejbbv {
  stop-color: var(--svg-color--6b76ad, #6B76AD);
}

.briue9bpm {
  stop-color: var(--svg-color--636368, #636368);
}

.c53rjnbho {
  stop-color: var(--svg-color--2863cb, #2863CB);
}

.c5r226cip {
  stop-color: var(--svg-color--2483f6, #2483F6);
}

.c6lp81bhp {
  stop-color: var(--svg-color--307099, #307099);
  stop-opacity: 0;
}

.cjnv6q4jy {
  stop-color: var(--svg-color--4093be, #4093BE);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
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

.cxdw6g70z {
  cx: 11.034px;
  cy: 16.224px;
  r: 1.156px;
  fill: var(--svg-color--26161e, #26161E);
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

.dq6qhab8i {
  stop-color: var(--svg-color--3a2851, #3A2851);
}

.e7_y1ioqg {
  stop-color: var(--svg-color--2e99f4, #2E99F4);
}

.e819d0vit {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.19 14.04c.297-.188.856-.45 1.778-.293");
}

.ebcvm6lto {
  stop-color: var(--svg-color--39a7ff, #39A7FF);
  stop-opacity: 0;
}

.edkhrwbqz {
  fill: var(--svg-color--3978a9, #3978A9);
  d: path("M15.708 24.473c-.183 0-.687-.155-1.405-.738a192 192 0 0 1-3.762-3.18c-.216-.187-.671-.668-.566-1.192c.164-.82 1.359-1.148 3.203-1.148h5.061c1.844 0 3.04.328 3.203 1.148c.105.524-.35 1.005-.566 1.192a194 194 0 0 1-3.762 3.18c-.718.583-1.155.738-1.405.738z");
}

.ef0gzvaho {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.362 14.85c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
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

.fqpzwo9rb {
  stop-color: var(--svg-color--43aaf7, #43AAF7);
}

.ft5dv1b6b {
  fill: none;
}

.ftdzlkbpm {
  stop-color: var(--svg-color--1956ae, #1956AE);
}

.g1n33qbpu {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.895 15.627c.266-.467.67-.836 1.538-.836c.38 0 .747.106 1.073.37c.268.216.232.494.024.598l-.556.318c-.652-.21-1.372-.24-2.079-.45");
}

.g2tp3zwoc {
  stop-color: var(--svg-color--b2b2b8, #B2B2B8);
  stop-opacity: 0;
}

.g43afac9g {
  d: path("M15.708 24.473c-.183 0-.687-.155-1.405-.738a192 192 0 0 1-3.762-3.18c-.216-.187-.671-.668-.566-1.192c.164-.82 1.359-1.148 3.203-1.148h5.061c1.844 0 3.04.328 3.203 1.148c.105.524-.35 1.005-.566 1.192a194 194 0 0 1-3.762 3.18c-.718.583-1.155.738-1.405.738z");
}

.g5a0xac4q {
  stroke: var(--svg-color--a8a9af, #A8A9AF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.327 14.04c-.297-.188-.855-.45-1.777-.293");
}

.g8oaksl8k {
  d: path("M15.694 24.614c-.395 0-1.172-.032-2.446-.477l-.078-.036c-1.438-.657-4.997-2.284-4.851-4.363c0-2.15 3.458-2.156 5.187-1.89h4.405c1.73-.266 5.188-.26 5.188 1.89c.145 2.08-3.414 3.706-4.852 4.363l-.078.036c-1.274.445-2.05.476-2.476.476");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gj17nkbbl {
  fill: var(--svg-color--472f2f, #472F2F);
  d: path("m15.39 15.909l-.504 1.7c-.103.35.144.7.494.7h.746c.35 0 .597-.356.494-.7l-.504-1.7a.374.374 0 0 0-.726 0");
}

.gtvkj1bzh {
  stop-color: var(--svg-color--6a75b9, #6A75B9);
}

.guc8z7bij {
  stop-color: var(--svg-color--2caafc, #2CAAFC);
}

.gyvlymobj {
  stop-color: var(--svg-color--3c2529, #3C2529);
}

.h-e6v32ai {
  d: path("m23.34 18.484l-15.2-.01c-2.45 0-4.45-2-4.45-4.46s2-4.46 4.46-4.46l15.2.01c2.46 0 4.46 2 4.46 4.46a4.48 4.48 0 0 1-4.47 4.46");
}

.h-njqxe6y {
  stop-color: var(--svg-color--0a5185, #0A5185);
  stop-opacity: 0;
}

.h5iei_ivh {
  fill: var(--svg-color--311d20, #311D20);
  d: path("m15.45 23.977l-1.616-2.754h3.75l-1.617 2.754a.3.3 0 0 1-.517 0");
}

.h6-csrbqg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.144 14.85c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34H17a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.h7bve-ieg {
  stop-color: var(--svg-color--6b76ad, #6B76AD);
  stop-opacity: 0;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hbrxqdets {
  d: path("M22.74 18.124H8.75c-2.27 0-4.1-1.51-4.1-3.38s1.84-3.38 4.1-3.38l13.99.01c2.27 0 4.1 1.51 4.1 3.38c0 1.86-1.84 3.37-4.1 3.37");
}

.honnlt_-k {
  d: path("M23.362 25.321c0-.4.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.406-.657");
}

.hrpwn2zwe {
  fill: var(--svg-color--352122, #352122);
  fill-rule: evenodd;
  d: path("M14.271 16.662a.3.3 0 0 0-.424.02c-.152.167-.477.429-1.153.429a.3.3 0 0 0 0 .6c.863 0 1.343-.348 1.597-.625a.3.3 0 0 0-.02-.424");
}

.huu-ickwn {
  stop-color: var(--svg-color--2fb4f5, #2FB4F5);
}

.i2wlb99xo {
  stop-color: var(--svg-color--3e6082, #3E6082);
}

.i9a1drbux {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.871 15.31c.064.086-.07.19-.22.302c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.id0y_n31u {
  stop-color: var(--svg-color--2e65d4, #2E65D4);
}

.ijglzsb6p {
  stop-color: var(--svg-color--1c0f1e, #1C0F1E);
  stop-opacity: 0;
}

.in01aqbzo {
  stop-color: var(--svg-color--7d7e84, #7D7E84);
  stop-opacity: 0;
}

.inpzxhbwc {
  stop-color: var(--svg-color--2982ee, #2982EE);
  stop-opacity: 0;
}

.iov6rh-pq {
  stop-color: var(--svg-color--2caafc, #2CAAFC);
  stop-opacity: 0;
}

.ip_9wm34q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.882 28.583h1.796");
}

.irkpemyfq {
  stop-color: var(--svg-color--e3a984, #E3A984);
  stop-opacity: 0;
}

.is58fbc8j {
  fill: var(--svg-color--000, #000);
  d: path("M17.426 16.014a.51.51 0 0 1 .511-.51a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.236");
}

.iu-l6acky {
  stop-color: var(--svg-color--1956ae, #1956AE);
  stop-opacity: 0;
}

.iusprebiv {
  stop-color: var(--svg-color--1868c3, #1868C3);
}

.j0bdllbjm {
  cx: 20.466px;
  cy: 16.224px;
  r: 1.156px;
}

.j3frkab0z {
  d: path("M17.937 15.122a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.j47g61b-d {
  d: path("M18.732 15.897a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.job-vz29n {
  d: path("M8.594 22.752c-2.616 2.263-3.72 5.491-3.72 7.244h3.72z");
}

.jwpaqlbcq {
  stop-color: var(--svg-color--7d7e84, #7D7E84);
}

.k5utdqyeu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.882 25.974h1.796");
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

.ky591i9tr {
  d: path("M10.554 13.4v-.196a.7.7 0 0 1 .297-.578c.156-.138.337-.257.517-.375c.314-.206.627-.411.81-.719h1.868c.315.294.984.883 2.57.883h2.797c.448-.018 1.406.223 1.406.898v.086h.005c.01.995-.003 3.272-.141 4.422c-.2 1.657-1.71 4.344-4.994 4.344s-4.794-2.687-4.993-4.344c-.14-1.15-.153-3.427-.142-4.422");
}

.kytdhlviv {
  stop-color: var(--svg-color--d98350, #D98350);
}

.kzandbcfp {
  stop-color: var(--svg-color--22152a, #22152A);
}

.l_-nnctap {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.327 14.04c-.297-.188-.855-.45-1.777-.293");
}

.l15dqlbvn {
  stop-color: var(--svg-color--3e6082, #3E6082);
  stop-opacity: 0;
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

.levh51jdk {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.689 19.389a3.14 3.14 0 0 1-1.434-.342c-.137-.078-.293.088-.205.225a1.957 1.957 0 0 0 3.278 0c.088-.137-.068-.293-.205-.225c-.42.215-.907.342-1.434.342Z");
}

.lgnz4ib3a {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m8.75 11.264l13.99.01m-13.99-.01v.1c-2.26 0-4.1 1.51-4.1 3.38s1.83 3.38 4.1 3.38h13.99c2.26 0 4.1-1.51 4.1-3.37c0-1.87-1.83-3.38-4.1-3.38v-.1m-13.99-.01c-2.296 0-4.2 1.538-4.2 3.48s1.894 3.48 4.2 3.48h13.99c2.296 0 4.2-1.537 4.2-3.47c0-1.942-1.894-3.48-4.2-3.48m-13.99-.01l13.99.01");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmlq_xbrl {
  stop-color: var(--svg-color--2fa3f0, #2FA3F0);
  stop-opacity: 0;
}

.lmmcg9zod {
  stop-color: var(--svg-color--412e38, #412E38);
  stop-opacity: 0;
}

.m2k7t6jeu {
  stop-color: var(--svg-color--1b0d13, #1B0D13);
  stop-opacity: 0;
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

.my23gcbcn {
  stop-color: var(--svg-color--757ba3, #757BA3);
  stop-opacity: 0;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n0dan8b9v {
  cx: 20.466px;
  cy: 16.224px;
  r: 1.691px;
}

.n4ma-nbis {
  stop-color: var(--svg-color--1868c3, #1868C3);
  stop-opacity: 0;
}

.n7c2bfbtc {
  stop-color: var(--svg-color--3f7ec7, #3F7EC7);
}

.nfs1x8y7a {
  stop-color: var(--svg-color--b7b0b7, #B7B0B7);
  stop-opacity: 0;
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

.o1d5qg3pu {
  fill: var(--svg-color--8a8b92, #8A8B92);
  d: path("M10.568 15.541v-.118c-.007-.73-.014-1.52-.014-2.245a.7.7 0 0 1 .297-.552c.156-.138.337-.257.517-.375c.311-.204.622-.408.806-.711H9.845c-.23.605-.828 2.07-.46 4.32c.407 1.423.989 2.312 1.508 2.818a4.4 4.4 0 0 1-.198-.857c-.07-.577-.107-1.439-.127-2.28");
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

.o8l12hb_l {
  cx: 13.3px;
  cy: 15.503px;
  rx: 0.389px;
  ry: 0.197px;
}

.o8p2_blib {
  stop-color: var(--svg-color--2e74cb, #2E74CB);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogllkib3n {
  stop-color: var(--svg-color--0a5185, #0A5185);
}

.oluxj4fur {
  stop-color: var(--svg-color--32222b, #32222B);
}

.ouurtaccv {
  stop-color: var(--svg-color--b8b9c0, #B8B9C0);
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

.q5i0a9bwz {
  d: path("M20.252 18.806c1.265-.876 1.871-3.08 1.853-4.414c-.019-1.382-.367-2.247-.734-2.86h-7.347c.316.294.985.883 2.57.883h2.798c.448-.018 1.406.223 1.406.898v.086h.005c.009.823-.47 4.193-.552 5.406");
}

.q8c8skp1q {
  stop-color: var(--svg-color--3291c8, #3291C8);
}

.q977sk--x {
  stop-color: var(--svg-color--594c4c, #594C4C);
  stop-opacity: 0;
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

.r-yilwbra {
  stop-color: var(--svg-color--35acfa, #35ACFA);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
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

.s4irvhbcf {
  stop-color: var(--svg-color--b2b2b8, #B2B2B8);
}

.sagflfyry {
  cx: 11.034px;
  cy: 16.224px;
  r: 1.691px;
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

.t4ibp7bdp {
  stop-color: var(--svg-color--359cf2, #359CF2);
  stop-opacity: 0;
}

.t9x94gnsu {
  fill: var(--svg-color--000, #000);
  d: path("M14.08 16.014a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.236");
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

.trd9_ubam {
  stop-color: var(--svg-color--4e3534, #4E3534);
}

.tsk-k9bvn {
  stop-color: var(--svg-color--2fa9e7, #2FA9E7);
  stop-opacity: 0;
}

.tuhucxbhy {
  fill: var(--svg-color--ffc927, #FFC927);
  d: path("m15.39 15.909l-.504 1.7c-.103.35.144.7.494.7h.746c.35 0 .597-.356.494-.7l-.504-1.7a.374.374 0 0 0-.726 0");
}

.tw2c8iblg {
  stop-color: var(--svg-color--22152a, #22152A);
  stop-opacity: 0;
}

.u3wf8s8gl {
  stop-color: var(--svg-color--50b2e2, #50B2E2);
}

.u43ch0b3o {
  d: path("M4.875 29.996c0-2.883 2.987-9.76 10.777-9.76c7.791 0 10.628 6.396 10.868 9.76z");
}

.u7z6ngbib {
  stop-color: var(--svg-color--636368, #636368);
  stop-opacity: 0;
}

.uhl03ccti {
  stop-color: var(--svg-color--4bdaff, #4BDAFF);
}

.ujfp-d7qs {
  stop-color: var(--svg-color--757ba3, #757BA3);
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

.v25xlcb-w {
  stop-color: var(--svg-color--b7b0b7, #B7B0B7);
}

.v4785wmtk {
  stop-color: var(--svg-color--413e41, #413E41);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.valdy-bly {
  stop-color: var(--svg-color--e4e4e4, #E4E4E4);
}

.vas9tjbit {
  stop-color: var(--svg-color--ba756c, #BA756C);
}

.vba4otbgo {
  cx: 13.3px;
  cy: 15.503px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.veybn72ma {
  stop-color: var(--svg-color--2d82d6, #2D82D6);
}

.vi9njcc_v {
  stop-color: var(--svg-color--534142, #534142);
}

.viuzncbxq {
  stop-color: var(--svg-color--ba795b, #BA795B);
}

.vmjr7rbhn {
  stop-color: var(--svg-color--104e9b, #104E9B);
}

.vofdj6ror {
  stop-color: var(--svg-color--3c2338, #3C2338);
  stop-opacity: 0;
}

.vrxagqoeq {
  fill: var(--svg-color--412828, #412828);
  fill-rule: evenodd;
  d: path("M17.242 16.662a.3.3 0 0 1 .424.02c.153.167.478.429 1.153.429a.3.3 0 1 1 0 .6c-.863 0-1.343-.348-1.596-.625a.3.3 0 0 1 .02-.424");
}

.vsd8sfd_d {
  d: path("M10.568 15.541v-.118c-.007-.73-.014-1.52-.014-2.245a.7.7 0 0 1 .297-.552c.156-.138.337-.257.517-.375c.311-.204.622-.408.806-.711H9.845c-.23.605-.828 2.07-.46 4.32c.407 1.423.989 2.312 1.508 2.818a4.4 4.4 0 0 1-.198-.857c-.07-.577-.107-1.439-.127-2.28");
}

.vuytovdqu {
  fill: var(--svg-color--9998a1, #9998A1);
  d: path("M20.252 18.806c1.265-.876 1.871-3.08 1.853-4.414c-.019-1.382-.367-2.247-.734-2.86h-7.347c.316.294.985.883 2.57.883h2.798c.448-.018 1.406.223 1.406.898v.086h.005c.009.823-.47 4.193-.552 5.406");
}

.vxkgnhd4n {
  stop-color: var(--svg-color--3171da, #3171DA);
}

.vyxwjf9nd {
  stop-color: var(--svg-color--43aaf7, #43AAF7);
  stop-opacity: 0;
}

.w0tqq_bpv {
  stop-color: var(--svg-color--534142, #534142);
  stop-opacity: 0;
}

.w879bpb0e {
  d: path("m9.48 10.154l-.19.38h12.74l-.18-.36a7.1 7.1 0 0 0-1.19-1.67h-10a7.5 7.5 0 0 0-1.18 1.65");
}

.w8ll1ib0l {
  d: path("M14.384 15.91c0-.29-.234-.481-.298-.54l-.288.28l.177.36z");
}

.wf44ko9cr {
  stop-color: var(--svg-color--594c4c, #594C4C);
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

.wmwyugb7z {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.611 15.627c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.106-1.073.37c-.269.216-.233.494-.025.598l.556.318c.652-.21 1.373-.24 2.08-.45");
}

.wnm2vg-zq {
  stop-color: var(--svg-color--3171db, #3171DB);
  stop-opacity: 0;
}

.wp3rp0tep {
  d: path("m15.39 15.909l-.504 1.7c-.103.35.144.7.494.7h.746c.35 0 .597-.356.494-.7l-.504-1.7a.374.374 0 0 0-.726 0");
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

.xhqrsjbac {
  stop-color: var(--svg-color--3180ec, #3180EC);
}

.xp31u8b0s {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.271 23.773c.362.294.67.481.914.595c.241.113.421.155.523.155h.001c.268 0 .717-.165 1.437-.75c1.024-.832 2.795-2.34 3.763-3.18c.11-.096.282-.267.413-.482c.13-.214.225-.479.17-.757c-.088-.436-.448-.733-1.006-.92c-.557-.187-1.323-.269-2.247-.269h-5.061c-.924 0-1.69.082-2.248.27c-.557.186-.917.483-1.004.919c-.056.279.038.543.169.757c.131.215.303.386.413.482c.968.84 2.74 2.348 3.763 3.18Z");
}

.xr0zhtbtu {
  stop-color: var(--svg-color--b8b9c0, #B8B9C0);
  stop-opacity: 0;
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

.ylc4ncdmx {
  stop-color: var(--svg-color--54555e, #54555E);
  stop-opacity: 0;
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z3taopbho {
  stop-color: var(--svg-color--2863cb, #2863CB);
  stop-opacity: 0;
}

.z6ppokb8f {
  fill: var(--svg-color--30161f, #30161F);
  d: path("m15.266 16.043l-.505 1.7c-.103.35.144.7.494.7h.746c.35 0 .597-.356.494-.7l-.504-1.7a.374.374 0 0 0-.725 0");
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

.zebejbccq {
  stop-color: var(--svg-color--412e38, #412E38);
}

.zed3qmbmr {
  d: path("M17.871 15.31c.064.086-.07.19-.22.302c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
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

.zy380ub3a {
  stop-color: var(--svg-color--1c0f1e, #1C0F1E);
}

</style>
