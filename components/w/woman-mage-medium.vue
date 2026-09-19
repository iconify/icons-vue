<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="oo5510bhp"/><path fill="url(#il4bdjb)" class="tewy4hawl"/><path fill="url(#iW8yVeb)" class="tewy4hawl"/><path fill="url(#ilwSyMe)" class="tewy4hawl"/><path fill="url(#ipMQjDc)" class="tewy4hawl"/><path fill="url(#ieEwfyb)" class="job-vz29n"/><path fill="url(#ibPlbGX)" class="job-vz29n"/><path fill="url(#i1LfFnc)" class="job-vz29n"/><path fill="url(#idbpoub)" class="zc_ep_0uq"/><path fill="url(#iXwlnbA)" class="zc_ep_0uq"/><path fill="url(#ibfF9pc)" class="pyqbi2bgp"/><path fill="url(#iSVIuZb)" class="pyqbi2bgp"/><path fill="url(#iyT5utc)" class="pyqbi2bgp"/><path fill="url(#iwDqPAI)" class="pyqbi2bgp"/><path fill="url(#ipFI5hc)" class="pyqbi2bgp"/><path fill="url(#iqYNBEd)" class="pyqbi2bgp"/><path fill="url(#ighkArc)" class="pyqbi2bgp"/><g filter="url(#ipA8rdd)"><path class="m8fu3dcdl"/><path fill="url(#iqTZBPc)" class="tyl332bef"/><path fill="url(#ijdnghj)" class="tyl332bef"/><path fill="url(#iQdlE2c)" class="tyl332bef"/><path fill="url(#iZau3ke)" class="tyl332bef"/><path stroke="url(#isTPw6G)" class="pm0qvz33e"/></g><g filter="url(#ii7pxfc)"><path class="o2exr8bcw"/><path fill="url(#iGpUZue)" class="xr99hwbgq"/><path fill="url(#irQgoee)" class="xr99hwbgq"/></g><g filter="url(#iJpGSub)"><path fill="url(#iOxWFad)" class="d86qxubue"/><path fill="url(#ir99qxd)" class="d86qxubue"/></g><path fill="url(#iDiuhqc)" class="zcpjvdbuo"/><path fill="url(#iDiuhqc)" class="zcpjvdbuo"/><path fill="url(#iDqN3pV)" class="p7xat6cnl"/><path fill="url(#iirSkZf)" class="p7xat6cnl"/><path fill="url(#iIjIJec)" class="p7xat6cnl"/><path fill="url(#ixovgFc)" class="cil1djb_x"/><path fill="url(#iAwNGNd)" class="cil1djb_x"/><path fill="url(#i4jnpHd)" class="cil1djb_x"/><path fill="url(#ighCgpe)" class="h-e6v32ai"/><path fill="url(#ix5gnYc)" class="h-e6v32ai"/><path fill="url(#iJEWtud)" class="h-e6v32ai"/><path fill="url(#i2e03Ec)" class="h-e6v32ai"/><path fill="url(#i7Hsxxd)" class="h-e6v32ai"/><path fill="url(#iuAwBNe)" class="h-e6v32ai"/><path fill="url(#isDXaed)" class="h-e6v32ai"/><path fill="url(#isL6jeb)" class="p8qfg6btl"/><path fill="url(#idCAavb)" class="p8qfg6btl"/><g filter="url(#iKZ4W7b)"><path fill="url(#iU7U3XT)" class="hbrxqdets"/><path fill="url(#iZSIOUd)" class="hbrxqdets"/><path fill="url(#iGFMqWH)" class="hbrxqdets"/><path fill="url(#iRjmOQY)" class="hbrxqdets"/><path fill="url(#iheSTgO)" class="hbrxqdets"/><path fill="url(#i3xa2Qb)" class="hbrxqdets"/><path stroke="url(#iGAAS2d)" class="p8-_ecblh"/></g><g filter="url(#iCDGfmg)"><path fill="url(#iCutbnP)" class="b43uiy30g"/><path fill="url(#ieaWAvd)" class="b43uiy30g"/><path fill="url(#ikytyIb)" class="b43uiy30g"/><path fill="url(#iW4kXJz)" class="b43uiy30g"/></g><path fill="url(#iUDojFc)" class="d-kfqjw9b"/><path fill="url(#iNZ1RrM)" class="d-kfqjw9b"/><path fill="url(#i63AZyd)" class="bn4p-sbtt"/><g filter="url(#i3ZfVEb)"><path stroke="url(#i2O0dbd)" class="lehnoh0zf"/></g><g filter="url(#iQpIyeb)"><path class="rty5inbwp"/><path fill="url(#iIXmjnb)" class="ltxfj9mwp"/><path fill="url(#i45kSDe)" class="ltxfj9mwp"/><path fill="url(#ifl02dd)" class="ltxfj9mwp"/><path fill="url(#iJk7q8d)" class="ltxfj9mwp"/></g><path class="v10pf3b-m"/><path fill="url(#iFGWO1c)" class="bvuy6-btx"/><path fill="url(#idWQnAb)" class="bvuy6-btx"/><path fill="url(#iJeSElc)" class="bvuy6-btx"/><path fill="url(#ilE1csb)" class="bvuy6-btx"/><circle fill="url(#iHCMT2c)" class="sagflfyry"/><circle fill="url(#ibz8VQb)" class="sagflfyry"/><circle fill="url(#imIjzOc)" class="n0dan8b9v"/><circle fill="url(#i5nxhvd)" class="n0dan8b9v"/><g filter="url(#iwt45vd)"><circle fill="url(#iRfpHUb)" class="lnfso8l6k"/></g><g filter="url(#iI1ixrb)"><circle fill="url(#iaPm7Qd)" class="j0bdllbjm"/></g><g filter="url(#i2rgoAb)"><path fill="url(#ir2EfVb)" class="ky591i9tr"/><path fill="url(#ileoUcd)" class="ky591i9tr"/><path fill="url(#ibfHPOg)" class="ky591i9tr"/><path fill="url(#iVzUyVc)" class="ky591i9tr"/><path fill="url(#i8gIuwe)" class="ky591i9tr"/></g><path fill="url(#iRCqf6b)" class="ky591i9tr"/><path fill="url(#isgY88y)" class="ky591i9tr"/><path fill="url(#i4pjnCc)" class="ky591i9tr"/><path fill="url(#iYwZRQd)" class="ky591i9tr"/><g filter="url(#iA34Dlb)"><path stroke="url(#ilPniwb)" class="levh51jdk"/></g><path class="fc7m68b6w"/><g filter="url(#i5QI3De)"><path class="knsifjbov"/></g><g filter="url(#iKb7E0b)"><path class="mo2haytot"/><path fill="url(#i0bJymb)" class="us6rbhbed"/><path fill="url(#iwJZ4Wd)" class="us6rbhbed"/><path fill="url(#iupmGAe)" class="us6rbhbed"/><path fill="url(#iaroCQG)" class="us6rbhbed"/></g><g filter="url(#iRnTXee)"><path class="g1n33qbpu"/></g><g filter="url(#icxZpQb)"><path class="wmwyugb7z"/></g><path class="h6-csrbqg"/><path fill="url(#i5pVYQc)" class="j3frkab0z"/><path class="is58fbc8j"/><g filter="url(#iq639Ke)"><path class="rmuhh-bus"/><path fill="url(#i8emz2W)" class="nt3-fwyuq"/></g><g filter="url(#iOwai1d)"><path fill="url(#i7MmYAd)" class="j47g61b-d"/></g><path class="ef0gzvaho"/><path fill="url(#ivqLgcc)" class="ht9-5hb4m"/><path class="t9x94gnsu"/><g filter="url(#iCzLmSb)"><path fill="url(#iLaCD5c)" class="rim2o2bpf"/></g><g filter="url(#iDfDOTd)"><ellipse transform="rotate(-27.914 13.3 15.503)" class="vba4otbgo"/><ellipse fill="url(#ioyNiBd)" transform="rotate(-27.914 13.3 15.503)" class="o8l12hb_l"/></g><path clip-rule="evenodd" class="t6bpp7bbn"/><path clip-rule="evenodd" class="uarz-hbos"/><g filter="url(#ieVHNvc)"><path class="g1f_xubas"/><path stroke="url(#i9Nr5tS)" class="s6-sglb_h"/></g><g filter="url(#i5yV3Nd)"><path class="agqp17aah"/><path stroke="url(#ioZwABe)" class="iv5z78bmx"/></g><g filter="url(#iG2QLVb)"><path fill="url(#icw7MVb)" class="i6qu45wbj"/><path fill="url(#iF8q6ld)" class="i6qu45wbj"/><path fill="url(#iWDYsZJ)" class="i6qu45wbj"/><path fill="url(#iRDkZwd)" class="i6qu45wbj"/><path fill="url(#ic4CIJd)" class="i6qu45wbj"/></g><g filter="url(#igKPqjd)"><path stroke="url(#igcjOee)" class="k5utdqyeu"/></g><g filter="url(#iZ1WXCZ)"><path stroke="url(#iKAHesc)" class="a6su9fb1l"/></g><g filter="url(#iVjRqud)"><path stroke="url(#iV9QKab)" class="ip_9wm34q"/></g><defs><radialGradient id="il4bdjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.03125 7.18055 0 20.738 30.442)" gradientUnits="userSpaceOnUse"><stop class="xhqrsjbac"/><stop offset="1" class="ebcvm6lto"/></radialGradient><radialGradient id="iW8yVeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.6875 .78125 0 22.988 29.817)" gradientUnits="userSpaceOnUse"><stop class="wup_v_x-y"/><stop offset="1" class="rec-1hb8e"/></radialGradient><radialGradient id="ilwSyMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 0 0 19.1959 8.613 29.996)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mr4lhnuux"/><stop offset="1" class="q-3947b0q"/></radialGradient><radialGradient id="ipMQjDc" cx="0" cy="0" r="1" gradientTransform="rotate(-136.837 16.423 12.118)scale(15.1664 18.2252)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="q-3947b0q"/><stop offset="1" class="dgbyghhck"/></radialGradient><radialGradient id="ieEwfyb" cx="0" cy="0" r="1" gradientTransform="matrix(.30005 -6.75 3.83344 .1704 8.594 29.88)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="e7_y1ioqg"/><stop offset="1" class="o8c2nzb0a"/></radialGradient><radialGradient id="ibPlbGX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.125 3.97458 0 6.734 30.192)" gradientUnits="userSpaceOnUse"><stop class="dn-ogvbjy"/><stop offset="1" class="inpzxhbwc"/></radialGradient><radialGradient id="i1LfFnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.63745 0 0 -7.24389 8.594 29.996)" gradientUnits="userSpaceOnUse"><stop class="a3c-8ubyu"/><stop offset="1" class="x9tw1mbfn"/></radialGradient><radialGradient id="idbpoub" cx="0" cy="0" r="1" gradientTransform="rotate(82.372 -.267 24.058)scale(8.94581 3.16756)" gradientUnits="userSpaceOnUse"><stop class="embu-7brp"/><stop offset="1" class="veybn72ma"/></radialGradient><radialGradient id="iXwlnbA" cx="0" cy="0" r="1" gradientTransform="matrix(.83557 0 0 8.41461 22.84 29.996)" gradientUnits="userSpaceOnUse"><stop class="rj_n-mbmd"/><stop offset=".85" class="sfuw4b7fs"/></radialGradient><radialGradient id="iSVIuZb" cx="0" cy="0" r="1" gradientTransform="rotate(124.902 .777 14.461)scale(1.63847 5.18259)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="dekz5-i5a"/><stop offset="1" class="takbm9boj"/></radialGradient><radialGradient id="iyT5utc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.625 -11.4392 0 15.709 19.723)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="tclwz7mny"/><stop offset="1" class="c5r226cip"/></radialGradient><radialGradient id="iwDqPAI" cx="0" cy="0" r="1" gradientTransform="matrix(4.9375 -2.78125 .65585 1.16432 19.27 21.973)" gradientUnits="userSpaceOnUse"><stop class="zm3svk-ip"/><stop offset="1" class="f-m4mzz6d"/></radialGradient><radialGradient id="ipFI5hc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75002 2.37497 -1.68941 -2.66754 10.738 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="d45gne0nz"/><stop offset="1" class="f283fd8-c"/></radialGradient><radialGradient id="iqYNBEd" cx="0" cy="0" r="1" gradientTransform="rotate(-69.233 29.08 .534)scale(10.4881 22.9861)" gradientUnits="userSpaceOnUse"><stop offset=".677" class="nypzj9bha"/><stop offset=".949" class="nvdrdzbmz"/></radialGradient><radialGradient id="ighkArc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.88478 14.4983 0 15.709 24.614)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="bgqsi-bps"/><stop offset=".985" class="f-3q63keb"/></radialGradient><radialGradient id="iqTZBPc" cx="0" cy="0" r="1" gradientTransform="matrix(.76562 -.87496 3.20566 2.80509 14.77 24.473)" gradientUnits="userSpaceOnUse"><stop class="rdaygdbpu"/><stop offset="1" class="zajsytjse"/></radialGradient><radialGradient id="iQdlE2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 -.46875 4.21008 -3.78904 19.441 22.223)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="i2wlb99xo"/><stop offset="1" class="l15dqlbvn"/></radialGradient><radialGradient id="iZau3ke" cx="0" cy="0" r="1" gradientTransform="rotate(142.134 5.394 14.516)scale(3.61466 .90443)" gradientUnits="userSpaceOnUse"><stop class="ogllkib3n"/><stop offset="1" class="h-njqxe6y"/></radialGradient><radialGradient id="isTPw6G" cx="0" cy="0" r="1" gradientTransform="matrix(.8298 -1.3125 2.13746 1.35137 14.879 24.239)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="fqpzwo9rb"/><stop offset="1" class="vyxwjf9nd"/></radialGradient><radialGradient id="iGpUZue" cx="0" cy="0" r="1" gradientTransform="matrix(1.24797 2.09203 -3.88024 2.3147 15.056 20.765)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="ourq4tvcl"/><stop offset="1" class="qzdo-ebjz"/></radialGradient><radialGradient id="irQgoee" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48318 3.03117 -.28115 -.13757 17.117 21.223)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="ozb_z_jjy"/><stop offset="1" class="e99mbykis"/></radialGradient><radialGradient id="iOxWFad" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 .96875 -.2841 1.50295 17.082 3.16)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="s_1mw_rhq"/><stop offset="1" class="pql562bff"/></radialGradient><radialGradient id="iDqN3pV" cx="0" cy="0" r="1" gradientTransform="matrix(-4.62501 2.59374 -3.8683 -6.89775 17.988 3.817)" gradientUnits="userSpaceOnUse"><stop offset=".063" class="uhl03ccti"/><stop offset="1" class="uuh3gfbsu"/></radialGradient><radialGradient id="iIjIJec" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 -1.30125 2.428 -12.47818 18.77 7.535)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="tsk-k9bvn"/><stop offset="1" class="phlvo2b_b"/></radialGradient><radialGradient id="ighCgpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15156 -24.7184 0 15.75 9.333)" gradientUnits="userSpaceOnUse"><stop class="r-yilwbra"/><stop offset=".652" class="vxkgnhd4n"/></radialGradient><radialGradient id="ix5gnYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.64742 -17.2274 0 13.022 8.98)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="huu-ickwn"/><stop offset="1" class="t4ibp7bdp"/></radialGradient><radialGradient id="iJEWtud" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68356 0 0 -2.80263 25.977 10.71)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="p5_1r5b0y"/><stop offset="1" class="bkffn87la"/></radialGradient><radialGradient id="i2e03Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-10.1661 0 0 -1.56292 25.094 9.554)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="zdk8j6bjz"/><stop offset="1" class="lmlq_xbrl"/></radialGradient><radialGradient id="i7Hsxxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.15365 1.28841 0 24.918 11.91)" gradientUnits="userSpaceOnUse"><stop offset=".051" class="o8p2_blib"/><stop offset="1" class="szwxs1ffj"/></radialGradient><radialGradient id="iuAwBNe" cx="0" cy="0" r="1" gradientTransform="rotate(-119.268 10.579 6.104)scale(3.2599 6.67388)" gradientUnits="userSpaceOnUse"><stop class="vmjr7rbhn"/><stop offset="1" class="zxip0bczk"/></radialGradient><radialGradient id="isDXaed" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 0 0 1.78125 21.332 18.192)" gradientUnits="userSpaceOnUse"><stop class="iusprebiv"/><stop offset="1" class="n4ma-nbis"/></radialGradient><radialGradient id="isL6jeb" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.544 16.216)scale(2.34093 2.29861)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="ga9rerbuy"/><stop offset="1" class="nzebcsqxz"/></radialGradient><radialGradient id="idCAavb" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 27.822 23.52)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="xd1qixbwn"/><stop offset="1" class="xp3m0tmzy"/></radialGradient><radialGradient id="iU7U3XT" cx="0" cy="0" r="1" gradientTransform="matrix(-8.43067 -6.22495 7.88718 -10.6819 24.176 17.817)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="qxprq_b_n"/><stop offset="1" class="id0y_n31u"/></radialGradient><radialGradient id="iZSIOUd" cx="0" cy="0" r="1" gradientTransform="matrix(1.19531 0 0 .58033 20.863 13.286)" gradientUnits="userSpaceOnUse"><stop class="azeqcu15x"/><stop offset="1" class="sda7dac5x"/></radialGradient><radialGradient id="iGFMqWH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60937 0 0 -.8125 10.926 13.473)" gradientUnits="userSpaceOnUse"><stop class="x9q-1ua-h"/><stop offset="1" class="d_y83zkbz"/></radialGradient><radialGradient id="iRjmOQY" cx="0" cy="0" r="1" gradientTransform="rotate(-177.049 5.42 8.54)scale(3.03527 4.59892)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="ftdzlkbpm"/><stop offset="1" class="iu-l6acky"/></radialGradient><radialGradient id="iheSTgO" cx="0" cy="0" r="1" gradientTransform="rotate(-50.886 21.06 3.067)scale(3.51696 3.66873)" gradientUnits="userSpaceOnUse"><stop class="ap_fa_bgx"/><stop offset="1" class="wnm2vg-zq"/></radialGradient><radialGradient id="i3xa2Qb" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 0 0 5.40625 21.062 11.79)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="c53rjnbho"/><stop offset="1" class="z3taopbho"/></radialGradient><radialGradient id="ieaWAvd" cx="0" cy="0" r="1" gradientTransform="matrix(3 3.65625 -3.78158 3.10283 22.894 7.317)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="vas9tjbit"/><stop offset="1" class="ny-1wemya"/></radialGradient><radialGradient id="ikytyIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.61462 -2.0661 0 25.705 7.453)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="viuzncbxq"/><stop offset="1" class="ej1v0hbca"/></radialGradient><radialGradient id="iW4kXJz" cx="0" cy="0" r="1" gradientTransform="rotate(145.359 13.401 8.53)scale(3.99771 2.68184)" gradientUnits="userSpaceOnUse"><stop class="uvv0p6btj"/><stop offset="1" class="elep40b9c"/></radialGradient><radialGradient id="iUDojFc" cx="0" cy="0" r="1" gradientTransform="rotate(144.673 12.844 7.022)scale(4.07349 4.5687)" gradientUnits="userSpaceOnUse"><stop class="a-lhjfbpa"/><stop offset="1" class="begh2ub5w"/></radialGradient><radialGradient id="iNZ1RrM" cx="0" cy="0" r="1" gradientTransform="rotate(-133.348 14.9 -2.216)scale(4.59811 4.64228)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="po1nyh2al"/><stop offset=".913" class="cjnv6q4jy"/></radialGradient><radialGradient id="i63AZyd" cx="0" cy="0" r="1" gradientTransform="rotate(-111.272 15.595 -6.12)scale(2.19652 2.90326)" gradientUnits="userSpaceOnUse"><stop offset=".052" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="iIXmjnb" cx="0" cy="0" r="1" gradientTransform="matrix(4.21875 0 0 1.2718 16.75 11.852)" gradientUnits="userSpaceOnUse"><stop class="ouurtaccv"/><stop offset="1" class="xr0zhtbtu"/></radialGradient><radialGradient id="i45kSDe" cx="0" cy="0" r="1" gradientTransform="matrix(4.37205 1.15625 -2.08826 7.8962 18.065 14.759)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="nfs1x8y7a"/><stop offset="1" class="v25xlcb-w"/></radialGradient><radialGradient id="ifl02dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.53516 1.10937 0 20.843 15.169)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="briue9bpm"/><stop offset="1" class="u7z6ngbib"/></radialGradient><radialGradient id="iJk7q8d" cx="0" cy="0" r="1" gradientTransform="matrix(3.62206 -3.85156 7.57442 7.12308 18.065 15.384)" gradientUnits="userSpaceOnUse"><stop offset=".809" class="ag1ksrb9e"/><stop offset=".989" class="gtvkj1bzh"/></radialGradient><radialGradient id="iFGWO1c" cx="0" cy="0" r="1" gradientTransform="rotate(162.216 5.016 8.618)scale(3.13201 5.57814)" gradientUnits="userSpaceOnUse"><stop offset=".669" class="h7bve-ieg"/><stop offset=".931" class="bob4ejbbv"/></radialGradient><radialGradient id="idWQnAb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78218 1.96086 -.96988 -.8815 11.28 13.712)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="v4785wmtk"/><stop offset="1" class="ylc4ncdmx"/></radialGradient><radialGradient id="iJeSElc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33643 .94957 -.27358 -.38504 11.693 12)" gradientUnits="userSpaceOnUse"><stop class="jwpaqlbcq"/><stop offset="1" class="in01aqbzo"/></radialGradient><radialGradient id="iHCMT2c" cx="0" cy="0" r="1" gradientTransform="rotate(-56.991 20.505 -.285)scale(2.29233 6.21415)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="dogy1idjp"/><stop offset="1" class="vlw0vp06u"/></radialGradient><radialGradient id="ibz8VQb" cx="0" cy="0" r="1" gradientTransform="rotate(140.314 2.622 10.013)scale(1.85656 2.30328)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="zpwwz9sjy"/><stop offset="1" class="vfs0l5bbp"/></radialGradient><radialGradient id="imIjzOc" cx="0" cy="0" r="1" gradientTransform="matrix(1.6756 -2.5134 1.78912 1.19275 20.302 17.144)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="eloxbm3be"/><stop offset="1" class="at72a731h"/></radialGradient><radialGradient id="i5nxhvd" cx="0" cy="0" r="1" gradientTransform="matrix(.6165 -.4189 .5961 .87729 21.076 15.943)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kwnlw8b2e"/><stop offset="1" class="qa8kaoboe"/></radialGradient><radialGradient id="iRfpHUb" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.382 8.151)scale(.79067)" gradientUnits="userSpaceOnUse"><stop class="iyv-k2olk"/><stop offset="1" class="nj65_z_ia"/></radialGradient><radialGradient id="iaPm7Qd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3328 0 0 1.12348 20.29 15.973)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="ml9grxb-k"/><stop offset="1" class="l9h9mvb7n"/></radialGradient><radialGradient id="ir2EfVb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.40625 0 0 -6.38191 17.906 16.849)" gradientUnits="userSpaceOnUse"><stop class="xrq3j3blh"/><stop offset="1" class="sb7mrhbpq"/></radialGradient><radialGradient id="ileoUcd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5625 0 0 -7.59237 21.187 13.977)" gradientUnits="userSpaceOnUse"><stop class="ak9awcv4y"/><stop offset="1" class="kouy7yb0k"/></radialGradient><radialGradient id="ibfHPOg" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 -1 .7631 2.09852 17.859 12.337)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="xq-an8bsm"/><stop offset="1" class="fvgz27qdw"/></radialGradient><radialGradient id="iVzUyVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.46076 1.875 0 18.006 15.235)" gradientUnits="userSpaceOnUse"><stop class="l18oipbpq"/><stop offset="1" class="e93xw4gch"/></radialGradient><radialGradient id="i8gIuwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.26453 1.11192 0 13.733 15.126)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iRCqf6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.8125 -7.55046 0 15.69 14.571)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="y3wvqjg-f"/><stop offset=".995" class="qlhrxccpe"/></radialGradient><radialGradient id="isgY88y" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.4375 -1.71875 0 10.218 12.071)" gradientUnits="userSpaceOnUse"><stop class="kpnv42byp"/><stop offset="1" class="qe1ga47gr"/></radialGradient><radialGradient id="i4pjnCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.21875 -7.70283 0 13.093 11.009)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="p0bnytmkj"/><stop offset="1" class="jk70tbpqx"/></radialGradient><radialGradient id="iYwZRQd" cx="0" cy="0" r="1" gradientTransform="rotate(141.318 3.605 7.742)scale(3.21254 .93832)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="bb9uhccyv"/><stop offset="1" class="sdgg7h5xl"/></radialGradient><radialGradient id="ilPniwb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.018 24.526 -2.719)scale(.46901 1.37903)" gradientUnits="userSpaceOnUse"><stop class="ih5l3rlhu"/><stop offset="1" class="ajofcvdjj"/></radialGradient><radialGradient id="iaroCQG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19695 -.60038 0 16.064 17.801)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="i5pVYQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.935 15.599)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i8emz2W" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.694 3.505)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivqLgcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.571 15.599)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ioyNiBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.284 15.818)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9Nr5tS" cx="0" cy="0" r="1" gradientTransform="matrix(-.33594 .0079 -.01842 -.7833 14.204 13.639)" gradientUnits="userSpaceOnUse"><stop class="s4irvhbcf"/><stop offset="1" class="g2tp3zwoc"/></radialGradient><radialGradient id="ioZwABe" cx="0" cy="0" r="1" gradientTransform="rotate(-154.746 11.375 4.87)scale(.45782 1.06747)" gradientUnits="userSpaceOnUse"><stop class="s4irvhbcf"/><stop offset="1" class="g2tp3zwoc"/></radialGradient><radialGradient id="iF8q6ld" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.012 25.3)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iWDYsZJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.012 26.595)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iRDkZwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.012 27.845)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ic4CIJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.012 29.196)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><filter id="ipA8rdd" width="12.098" height="6.858" x="9.659" y="17.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".1"/></filter><filter id="ii7pxfc" width="3.75" height="3.003" x="13.834" y="21.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.219608 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1078"/></filter><filter id="iJpGSub" width="6.328" height="3.25" x="15.66" y="1.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.521569 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1078"/></filter><filter id="iKZ4W7b" width="23.09" height="7.66" x="4.2" y="10.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".125"/></filter><filter id="iCDGfmg" width="5.46" height="21.857" x="23.1" y="5.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.45098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1078"/></filter><filter id="i3ZfVEb" width="1.8" height="17.408" x="25.202" y="9.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".325"/></filter><filter id="iQpIyeb" width="8.081" height="7.473" x="14.024" y="11.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.443137 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1078"/></filter><filter id="iwt45vd" width="2.813" height="2.813" x="9.628" y="14.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".125"/></filter><filter id="iI1ixrb" width="2.913" height="2.913" x="19.01" y="14.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".15"/></filter><filter id="i2rgoAb" width="11.026" height="10.833" x="10.551" y="11.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.431373 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1078"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.352941 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1078" result="effect2_innerShadow_4002_1078"/></filter><filter id="iA34Dlb" width="3.679" height="1.482" x="13.849" y="18.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".05"/></filter><filter id="i5QI3De" width="2.781" height="3.682" x="14.238" y="15.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".25"/></filter><filter id="iKb7E0b" width="1.981" height="2.882" x="14.762" y="15.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".05"/></filter><filter id="iRnTXee" width="3.001" height="1.285" x="16.695" y="14.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1078"/></filter><filter id="icxZpQb" width="3.001" height="1.285" x="11.81" y="14.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1078"/></filter><filter id="iq639Ke" width=".786" height=".696" x="17.201" y="15.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".05"/></filter><filter id="iOwai1d" width=".891" height=".913" x="18.041" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".1"/></filter><filter id="iCzLmSb" width=".986" height="1.04" x="13.598" y="15.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".1"/></filter><filter id="iDfDOTd" width=".912" height=".704" x="12.843" y="15.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".05"/></filter><filter id="ieVHNvc" width="2.377" height="1.141" x="11.915" y="13.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.384314 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1078"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.643137 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1078" result="effect2_innerShadow_4002_1078"/></filter><filter id="i5yV3Nd" width="2.377" height="1.141" x="17.275" y="13.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.384314 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1078"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.643137 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1078" result="effect2_innerShadow_4002_1078"/></filter><filter id="iG2QLVb" width="4.846" height="5.556" x="23.362" y="24.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.352941 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1078"/></filter><filter id="igKPqjd" width="2.097" height=".3" x="23.732" y="25.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".05"/></filter><filter id="iZ1WXCZ" width="2.097" height=".3" x="23.654" y="27.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".05"/></filter><filter id="iVjRqud" width="2.097" height=".3" x="23.732" y="28.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1078" stdDeviation=".05"/></filter><linearGradient id="ibfF9pc" x1="21.582" x2="10.613" y1="21.66" y2="21.66" gradientUnits="userSpaceOnUse"><stop class="q8c8skp1q"/><stop offset="1" class="n7c2bfbtc"/></linearGradient><linearGradient id="ijdnghj" x1="16.175" x2="16.925" y1="19.567" y2="23.848" gradientUnits="userSpaceOnUse"><stop offset=".391" class="cvgk3kbak"/><stop offset="1" class="c6lp81bhp"/></linearGradient><linearGradient id="ir99qxd" x1="19.144" x2="19.472" y1="5.207" y2="3.848" gradientUnits="userSpaceOnUse"><stop class="guc8z7bij"/><stop offset="1" class="iov6rh-pq"/></linearGradient><linearGradient id="iDiuhqc" x1="7.907" x2="22.372" y1="19.98" y2="19.98" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kdl2hbbyb"/><stop offset="1" class="valdy-bly"/></linearGradient><linearGradient id="iirSkZf" x1="17.363" x2="17.363" y1="8.504" y2="7.317" gradientUnits="userSpaceOnUse"><stop class="u3wf8s8gl"/><stop offset="1" class="pt6842k6d"/></linearGradient><linearGradient id="ixovgFc" x1="14.176" x2="20.238" y1="9.91" y2="9.754" gradientUnits="userSpaceOnUse"><stop class="p-go_8bpa"/><stop offset="1" class="tp_ivrbui"/></linearGradient><linearGradient id="iAwNGNd" x1="21.863" x2="19.269" y1="9.285" y2="9.285" gradientUnits="userSpaceOnUse"><stop class="xrhcfrbuk"/><stop offset="1" class="psjmui2lw"/></linearGradient><linearGradient id="i4jnpHd" x1="9.738" x2="11.957" y1="9.519" y2="10.534" gradientUnits="userSpaceOnUse"><stop class="cvjhjoe1h"/><stop offset="1" class="wmajqfcti"/></linearGradient><linearGradient id="iGAAS2d" x1="15.745" x2="15.745" y1="11.364" y2="16.817" gradientUnits="userSpaceOnUse"><stop class="flda2eefx"/><stop offset="1" class="leei8_8-z"/></linearGradient><linearGradient id="iCutbnP" x1="24.372" x2="28.31" y1="10.533" y2="10.533" gradientUnits="userSpaceOnUse"><stop class="kytdhlviv"/><stop offset="1" class="bf9jtobby"/></linearGradient><linearGradient id="i2O0dbd" x1="26.602" x2="26.602" y1="9.925" y2="25.533" gradientUnits="userSpaceOnUse"><stop class="pafpa8b3r"/><stop offset="1" class="irkpemyfq"/></linearGradient><linearGradient id="ilE1csb" x1="10.721" x2="10.721" y1="11.54" y2="12.087" gradientUnits="userSpaceOnUse"><stop class="ujfp-d7qs"/><stop offset="1" class="my23gcbcn"/></linearGradient><linearGradient id="i0bJymb" x1="14.933" x2="15.823" y1="17.243" y2="17.243" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iwJZ4Wd" x1="17.015" x2="15.974" y1="17.404" y2="17.501" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iupmGAe" x1="15.938" x2="15.938" y1="18.308" y2="17.735" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="i7MmYAd" x1="18.713" x2="18.399" y1="15.653" y2="15.846" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLaCD5c" x1="14.315" x2="14.001" y1="15.653" y2="15.846" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icw7MVb" x1="27.743" x2="23.362" y1="28.058" y2="28.058" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="a87gyab7w"/></linearGradient><linearGradient id="igcjOee" x1="23.882" x2="25.591" y1="26.052" y2="26.052" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iKAHesc" x1="23.803" x2="25.513" y1="27.356" y2="27.356" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iV9QKab" x1="23.882" x2="25.591" y1="28.661" y2="28.661" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-mage-medium" /></template>
<style>
.a-lhjfbpa {
  stop-color: var(--svg-color--4ddcff, #4DDCFF);
}

.a3c-8ubyu {
  stop-color: var(--svg-color--41a8ff, #41A8FF);
}

.a6su9fb1l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.804 27.278H25.6");
}

.a87gyab7w {
  stop-color: var(--svg-color--a57c6f, #A57C6F);
}

.ag1ksrb9e {
  stop-color: var(--svg-color--6a75b9, #6A75B9);
  stop-opacity: 0;
}

.agqp17aah {
  stroke: var(--svg-color--a8a9af, #A8A9AF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.327 14.04c-.297-.187-.855-.45-1.777-.293");
}

.ajofcvdjj {
  stop-color: var(--svg-color--a87f7e, #A87F7E);
  stop-opacity: 0;
}

.ak9awcv4y {
  stop-color: var(--svg-color--937171, #937171);
}

.ap_fa_bgx {
  stop-color: var(--svg-color--3171db, #3171DB);
}

.at72a731h {
  stop-color: var(--svg-color--665059, #665059);
}

.azeqcu15x {
  stop-color: var(--svg-color--215a98, #215A98);
}

.b43uiy30g {
  d: path("M26.94 5.304c-.2-.11-.45.04-.45.27v1.62c0 .44-.36.81-.8.8a.786.786 0 0 1-.77-.78v-1.64c0-.23-.25-.38-.45-.27c-.81.44-1.36 1.29-1.37 2.27c-.01 1.01.58 1.9 1.43 2.34c.1.05.16.15.16.26v15.91c0 .57.47 1.04 1.04 1.04s1.04-.47 1.04-1.04v-15.93c0-.11.06-.21.16-.26a2.605 2.605 0 0 0 .01-4.59");
}

.bb9uhccyv {
  stop-color: var(--svg-color--643e3f, #643E3F);
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

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bvuy6-btx {
  d: path("M10.568 15.541v-.118c-.007-.73-.014-1.52-.014-2.245a.7.7 0 0 1 .297-.552c.156-.138.337-.257.517-.375c.311-.204.622-.408.806-.711H9.845c-.23.605-.828 2.07-.46 4.32c.407 1.423.989 2.313 1.508 2.818a4.4 4.4 0 0 1-.198-.857c-.07-.577-.107-1.439-.127-2.28");
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

.cil1djb_x {
  d: path("m9.48 10.154l-.19.38h12.74l-.18-.36a7.1 7.1 0 0 0-1.19-1.67h-10c-.46.49-.86 1.04-1.18 1.65");
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

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
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

.dogy1idjp {
  stop-color: var(--svg-color--7f5562, #7F5562);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7_y1ioqg {
  stop-color: var(--svg-color--2e99f4, #2E99F4);
}

.e93xw4gch {
  stop-color: var(--svg-color--a77470, #A77470);
  stop-opacity: 0;
}

.e99mbykis {
  stop-color: var(--svg-color--7f6364, #7F6364);
  stop-opacity: 0;
}

.ebcvm6lto {
  stop-color: var(--svg-color--39a7ff, #39A7FF);
  stop-opacity: 0;
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

.eloxbm3be {
  stop-color: var(--svg-color--9c7471, #9C7471);
}

.embu-7brp {
  stop-color: var(--svg-color--4ab4f4, #4AB4F4);
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

.fc7m68b6w {
  fill: var(--svg-color--88024f, #88024F);
  d: path("M15.689 19.389a3.14 3.14 0 0 1-1.434-.342c-.137-.078-.293.088-.205.225a1.957 1.957 0 0 0 3.278 0c.088-.137-.068-.293-.205-.225c-.42.215-.907.342-1.434.342");
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
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

.fvgz27qdw {
  stop-color: var(--svg-color--b0867b, #B0867B);
  stop-opacity: 0;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g1f_xubas {
  stroke: var(--svg-color--a9aaaf, #A9AAAF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.19 14.04c.297-.187.856-.45 1.778-.293");
}

.g1n33qbpu {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.895 15.627c.266-.467.67-.836 1.538-.836c.38 0 .747.106 1.073.37c.268.216.232.494.024.598l-.556.318c-.652-.21-1.372-.24-2.079-.45");
}

.g2tp3zwoc {
  stop-color: var(--svg-color--b2b2b8, #B2B2B8);
  stop-opacity: 0;
}

.ga9rerbuy {
  stop-color: var(--svg-color--bc9479, #BC9479);
}

.gtvkj1bzh {
  stop-color: var(--svg-color--6a75b9, #6A75B9);
}

.guc8z7bij {
  stop-color: var(--svg-color--2caafc, #2CAAFC);
}

.h-e6v32ai {
  d: path("m23.34 18.484l-15.2-.01c-2.45 0-4.45-2-4.45-4.46s2-4.46 4.46-4.46l15.2.01c2.46 0 4.46 2 4.46 4.46a4.48 4.48 0 0 1-4.47 4.46");
}

.h-njqxe6y {
  stop-color: var(--svg-color--0a5185, #0A5185);
  stop-opacity: 0;
}

.h6-csrbqg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.144 14.85c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34H17a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.h7bve-ieg {
  stop-color: var(--svg-color--6b76ad, #6B76AD);
  stop-opacity: 0;
}

.hbrxqdets {
  d: path("M22.74 18.124H8.75c-2.27 0-4.1-1.51-4.1-3.38s1.84-3.38 4.1-3.38l13.99.01c2.27 0 4.1 1.51 4.1 3.38c0 1.86-1.84 3.37-4.1 3.37");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.ht9-5hb4m {
  d: path("M13.569 15.122a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.huu-ickwn {
  stop-color: var(--svg-color--2fb4f5, #2FB4F5);
}

.i2wlb99xo {
  stop-color: var(--svg-color--3e6082, #3E6082);
}

.i6qu45wbj {
  d: path("M23.362 25.321c0-.4.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.658");
}

.id0y_n31u {
  stop-color: var(--svg-color--2e65d4, #2E65D4);
}

.ih5l3rlhu {
  stop-color: var(--svg-color--a87f7e, #A87F7E);
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

.iv5z78bmx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.327 14.04c-.297-.187-.855-.45-1.777-.293");
}

.iyv-k2olk {
  stop-color: var(--svg-color--6a4853, #6A4853);
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

.jk70tbpqx {
  stop-color: var(--svg-color--7e5a5d, #7E5A5D);
  stop-opacity: 0;
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

.kdl2hbbyb {
  stop-color: var(--svg-color--cacaca, #CACACA);
}

.knsifjbov {
  fill: var(--svg-color--8e5665, #8E5665);
  d: path("m15.266 16.043l-.505 1.7c-.103.35.144.7.494.7h.746c.35 0 .597-.356.494-.7l-.504-1.7a.374.374 0 0 0-.725 0");
}

.kouy7yb0k {
  stop-color: var(--svg-color--937171, #937171);
  stop-opacity: 0;
}

.kpnv42byp {
  stop-color: var(--svg-color--695059, #695059);
}

.kwnlw8b2e {
  stop-color: var(--svg-color--8a6b6c, #8A6B6C);
}

.ky591i9tr {
  d: path("M10.554 13.4v-.196a.7.7 0 0 1 .297-.578c.156-.138.337-.257.517-.375c.314-.206.627-.411.81-.719h1.868c.315.294.984.883 2.57.883h2.797c.448-.018 1.406.223 1.406.898v.086h.005c.01.995-.003 3.272-.141 4.422c-.2 1.657-1.71 4.344-4.994 4.344s-4.794-2.687-4.993-4.344c-.14-1.15-.153-3.427-.142-4.422");
}

.kytdhlviv {
  stop-color: var(--svg-color--d98350, #D98350);
}

.l15dqlbvn {
  stop-color: var(--svg-color--3e6082, #3E6082);
  stop-opacity: 0;
}

.l18oipbpq {
  stop-color: var(--svg-color--a77470, #A77470);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9h9mvb7n {
  stop-color: var(--svg-color--7d5554, #7D5554);
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

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmlq_xbrl {
  stop-color: var(--svg-color--2fa3f0, #2FA3F0);
  stop-opacity: 0;
}

.lnfso8l6k {
  cx: 11.034px;
  cy: 16.224px;
  r: 1.156px;
}

.ltxfj9mwp {
  d: path("M20.252 18.806c1.265-.875 1.871-3.08 1.853-4.414c-.019-1.382-.367-2.247-.734-2.86h-7.347c.316.294.985.883 2.57.883h2.798c.448-.018 1.406.223 1.406.898v.086h.005c.009.823-.47 4.193-.552 5.407");
}

.m8fu3dcdl {
  fill: var(--svg-color--3978a9, #3978A9);
  d: path("M15.708 24.473c-.183 0-.687-.155-1.405-.738a193 193 0 0 1-3.762-3.18c-.216-.187-.671-.668-.566-1.191c.164-.82 1.359-1.149 3.203-1.149h5.061c1.844 0 3.04.328 3.203 1.149c.105.523-.35 1.004-.566 1.191a194 194 0 0 1-3.762 3.18c-.718.583-1.155.738-1.405.738z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.ml9grxb-k {
  stop-color: var(--svg-color--8c6964, #8C6964);
}

.mo2haytot {
  fill: var(--svg-color--ab8473, #AB8473);
  d: path("m15.39 15.91l-.504 1.7c-.103.349.144.698.494.698h.746c.35 0 .597-.355.494-.699l-.504-1.7a.374.374 0 0 0-.726 0");
}

.mr4lhnuux {
  stop-color: var(--svg-color--2787f2, #2787F2);
}

.my23gcbcn {
  stop-color: var(--svg-color--757ba3, #757BA3);
  stop-opacity: 0;
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
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

.nj65_z_ia {
  stop-color: var(--svg-color--6c454c, #6C454C);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nt3-fwyuq {
  d: path("M17.871 15.31c.064.086-.07.19-.22.302c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.112.325-.135.388-.05");
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

.nzebcsqxz {
  stop-color: var(--svg-color--aa7756, #AA7756);
}

.o2exr8bcw {
  fill: var(--svg-color--815b5a, #815B5A);
  d: path("m15.45 23.977l-1.616-2.754h3.75l-1.617 2.754a.3.3 0 0 1-.517 0");
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

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ogllkib3n {
  stop-color: var(--svg-color--0a5185, #0A5185);
}

.oo5510bhp {
  fill: var(--svg-color--39a7ff, #39A7FF);
  d: path("M4.875 29.996c0-2.883 2.987-9.761 10.777-9.761c7.791 0 10.628 6.397 10.868 9.76z");
}

.ourq4tvcl {
  stop-color: var(--svg-color--683f48, #683F48);
}

.ouurtaccv {
  stop-color: var(--svg-color--b8b9c0, #B8B9C0);
}

.ozb_z_jjy {
  stop-color: var(--svg-color--7f6364, #7F6364);
}

.p-go_8bpa {
  stop-color: var(--svg-color--423851, #423851);
}

.p0bnytmkj {
  stop-color: var(--svg-color--65465e, #65465E);
}

.p5_1r5b0y {
  stop-color: var(--svg-color--3da9f9, #3DA9F9);
}

.p7xat6cnl {
  d: path("M21.61 10.464H9.71l.18-.35c1.12-2.16 3.34-8.11 5.77-8.11c2.44 0 4.67 5.96 5.78 8.13z");
}

.p8-_ecblh {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m8.75 11.264l13.99.01m-13.99-.01v.1c-2.26 0-4.1 1.51-4.1 3.38s1.83 3.38 4.1 3.38h13.99c2.26 0 4.1-1.51 4.1-3.37c0-1.87-1.83-3.38-4.1-3.38v-.1m-13.99-.01c-2.296 0-4.2 1.538-4.2 3.48c0 1.943 1.894 3.48 4.2 3.48h13.99c2.296 0 4.2-1.537 4.2-3.47c0-1.942-1.894-3.48-4.2-3.48m-13.99-.01l13.99.01");
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

.pm0qvz33e {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.271 23.774c.362.293.67.48.914.594c.241.113.421.155.523.155h.001c.268 0 .717-.164 1.437-.75c1.024-.832 2.795-2.34 3.763-3.18c.11-.096.282-.267.413-.482c.13-.214.225-.479.17-.757c-.088-.436-.448-.733-1.006-.92c-.557-.187-1.323-.269-2.247-.269h-5.061c-.924 0-1.69.082-2.248.27c-.557.186-.917.483-1.004.919c-.056.279.038.543.169.757c.131.215.303.386.413.482c.968.84 2.74 2.348 3.763 3.18Z");
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

.pyqbi2bgp {
  d: path("M15.694 24.614c-.395 0-1.172-.032-2.446-.477l-.078-.036c-1.438-.657-4.997-2.284-4.851-4.362c0-2.15 3.458-2.157 5.187-1.891h4.405c1.73-.266 5.188-.26 5.188 1.89c.145 2.08-3.414 3.706-4.852 4.363l-.078.036c-1.274.445-2.05.477-2.476.477");
}

.q-3947b0q {
  stop-color: var(--svg-color--39a8ff, #39A8FF);
  stop-opacity: 0;
}

.q8c8skp1q {
  stop-color: var(--svg-color--3291c8, #3291C8);
}

.qa8kaoboe {
  stop-color: var(--svg-color--8a6b6c, #8A6B6C);
  stop-opacity: 0;
}

.qe1ga47gr {
  stop-color: var(--svg-color--695059, #695059);
  stop-opacity: 0;
}

.qlhrxccpe {
  stop-color: var(--svg-color--825072, #825072);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.qxprq_b_n {
  stop-color: var(--svg-color--257bd2, #257BD2);
}

.qzdo-ebjz {
  stop-color: var(--svg-color--683f48, #683F48);
  stop-opacity: 0;
}

.r-yilwbra {
  stop-color: var(--svg-color--35acfa, #35ACFA);
}

.rdaygdbpu {
  stop-color: var(--svg-color--3aa4e9, #3AA4E9);
}

.rec-1hb8e {
  stop-color: var(--svg-color--3797f8, #3797F8);
  stop-opacity: 0;
}

.rim2o2bpf {
  d: path("M14.384 15.91c0-.289-.234-.481-.298-.54l-.288.28l.177.36z");
}

.rj_n-mbmd {
  stop-color: var(--svg-color--267adb, #267ADB);
}

.rmuhh-bus {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.871 15.31c.064.086-.07.19-.22.302c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.112.325-.135.388-.05");
}

.rty5inbwp {
  fill: var(--svg-color--9998a1, #9998A1);
  d: path("M20.252 18.806c1.265-.875 1.871-3.08 1.853-4.414c-.019-1.382-.367-2.247-.734-2.86h-7.347c.316.294.985.883 2.57.883h2.798c.448-.018 1.406.223 1.406.898v.086h.005c.009.823-.47 4.193-.552 5.407");
}

.s_1mw_rhq {
  stop-color: var(--svg-color--4cdbff, #4CDBFF);
}

.s4irvhbcf {
  stop-color: var(--svg-color--b2b2b8, #B2B2B8);
}

.s6-sglb_h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.19 14.04c.297-.187.856-.45 1.778-.293");
}

.sagflfyry {
  cx: 11.034px;
  cy: 16.224px;
  r: 1.691px;
}

.sb7mrhbpq {
  stop-color: var(--svg-color--94626b, #94626B);
}

.sda7dac5x {
  stop-color: var(--svg-color--215a98, #215A98);
  stop-opacity: 0;
}

.sdgg7h5xl {
  stop-color: var(--svg-color--643e3f, #643E3F);
  stop-opacity: 0;
}

.sfuw4b7fs {
  stop-color: var(--svg-color--267adb, #267ADB);
  stop-opacity: 0;
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
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

.t6bpp7bbn {
  fill: var(--svg-color--a57669, #A57669);
  fill-rule: evenodd;
  d: path("M17.242 16.662a.3.3 0 0 1 .424.02c.153.167.478.429 1.153.429a.3.3 0 1 1 0 .6c-.863 0-1.343-.348-1.596-.625a.3.3 0 0 1 .02-.424");
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

.tewy4hawl {
  d: path("M4.875 29.996c0-2.883 2.987-9.761 10.777-9.761c7.791 0 10.628 6.397 10.868 9.76z");
}

.tp_ivrbui {
  stop-color: var(--svg-color--584d65, #584D65);
}

.tsk-k9bvn {
  stop-color: var(--svg-color--2fa9e7, #2FA9E7);
  stop-opacity: 0;
}

.tyl332bef {
  d: path("M15.708 24.473c-.183 0-.687-.155-1.405-.738a193 193 0 0 1-3.762-3.18c-.216-.187-.671-.668-.566-1.191c.164-.82 1.359-1.149 3.203-1.149h5.061c1.844 0 3.04.328 3.203 1.149c.105.523-.35 1.004-.566 1.191a194 194 0 0 1-3.762 3.18c-.718.583-1.155.738-1.405.738z");
}

.u3wf8s8gl {
  stop-color: var(--svg-color--50b2e2, #50B2E2);
}

.u7z6ngbib {
  stop-color: var(--svg-color--636368, #636368);
  stop-opacity: 0;
}

.uarz-hbos {
  fill: var(--svg-color--8b615b, #8B615B);
  fill-rule: evenodd;
  d: path("M14.271 16.662a.3.3 0 0 0-.424.02c-.152.167-.477.429-1.153.429a.3.3 0 0 0 0 .6c.863 0 1.343-.348 1.597-.625a.3.3 0 0 0-.02-.424");
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uhl03ccti {
  stop-color: var(--svg-color--4bdaff, #4BDAFF);
}

.ujfp-d7qs {
  stop-color: var(--svg-color--757ba3, #757BA3);
}

.us6rbhbed {
  d: path("m15.39 15.91l-.504 1.7c-.103.349.144.698.494.698h.746c.35 0 .597-.355.494-.699l-.504-1.7a.374.374 0 0 0-.726 0");
}

.uuh3gfbsu {
  stop-color: var(--svg-color--2cb1f7, #2CB1F7);
}

.uvv0p6btj {
  stop-color: var(--svg-color--cc8c6f, #CC8C6F);
}

.v10pf3b-m {
  fill: var(--svg-color--8a8b92, #8A8B92);
  d: path("M10.568 15.541v-.118c-.007-.73-.014-1.52-.014-2.245a.7.7 0 0 1 .297-.552c.156-.138.337-.257.517-.375c.311-.204.622-.408.806-.711H9.845c-.23.605-.828 2.07-.46 4.32c.407 1.423.989 2.313 1.508 2.818a4.4 4.4 0 0 1-.198-.857c-.07-.577-.107-1.439-.127-2.28");
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v25xlcb-w {
  stop-color: var(--svg-color--b7b0b7, #B7B0B7);
}

.v4785wmtk {
  stop-color: var(--svg-color--413e41, #413E41);
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

.vfs0l5bbp {
  stop-color: var(--svg-color--855f6f, #855F6F);
}

.viuzncbxq {
  stop-color: var(--svg-color--ba795b, #BA795B);
}

.vlw0vp06u {
  stop-color: var(--svg-color--5a4153, #5A4153);
}

.vmjr7rbhn {
  stop-color: var(--svg-color--104e9b, #104E9B);
}

.vxkgnhd4n {
  stop-color: var(--svg-color--3171da, #3171DA);
}

.vyxwjf9nd {
  stop-color: var(--svg-color--43aaf7, #43AAF7);
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

.xd1qixbwn {
  stop-color: var(--svg-color--cfa78e, #CFA78E);
}

.xhqrsjbac {
  stop-color: var(--svg-color--3180ec, #3180EC);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xp3m0tmzy {
  stop-color: var(--svg-color--cfa78e, #CFA78E);
  stop-opacity: 0;
}

.xq-an8bsm {
  stop-color: var(--svg-color--b0867b, #B0867B);
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

.xrq3j3blh {
  stop-color: var(--svg-color--bc907b, #BC907B);
}

.y3wvqjg-f {
  stop-color: var(--svg-color--a0697b, #A0697B);
  stop-opacity: 0;
}

.ylc4ncdmx {
  stop-color: var(--svg-color--54555e, #54555E);
  stop-opacity: 0;
}

.z3taopbho {
  stop-color: var(--svg-color--2863cb, #2863CB);
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

.zm3svk-ip {
  stop-color: var(--svg-color--4ab3f9, #4AB3F9);
}

.zpwwz9sjy {
  stop-color: var(--svg-color--855f6f, #855F6F);
  stop-opacity: 0;
}

.zxip0bczk {
  stop-color: var(--svg-color--104e9b, #104E9B);
  stop-opacity: 0;
}

</style>
