<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iGSn8Dc)" clip-rule="evenodd" class="uylc3es2x"/><path fill="url(#iYin6db)" clip-rule="evenodd" class="uylc3es2x"/><g filter="url(#i5lDQXb)"><path stroke="url(#iZ8AUhe)" class="rfksyecjs"/></g><path fill="url(#ijf66ub)" clip-rule="evenodd" class="itisl1bsn"/><path fill="url(#itUwzHc)" clip-rule="evenodd" class="itisl1bsn"/><g filter="url(#iZ4w9ud)"><path stroke="url(#i1I4aae)" class="pgkimacqn"/></g><path fill="url(#icmzFec)" clip-rule="evenodd" class="e314ej6ax"/><path fill="url(#iAf8Hpe)" clip-rule="evenodd" class="e314ej6ax"/><g filter="url(#ivK6sKb)"><path stroke="url(#ixwriRw)" class="k3z32yv2o"/></g><path fill="url(#ik1sdFc)" clip-rule="evenodd" class="or_xa3b0i"/><path class="qpugwjd8e"/><path fill="url(#iZqNyxU)" class="r5wm-vlaj"/><path fill="url(#ikAMzBa)" class="r5wm-vlaj"/><path fill="url(#iYE41Zf)" class="r5wm-vlaj"/><path fill="url(#igXiHgc)" class="r5wm-vlaj"/><path fill="url(#iselgIc)" class="r5wm-vlaj"/><g filter="url(#irMOgKb)"><path class="ypv5ckobw"/><path fill="url(#ixEuNeb)" class="itdn4bbbj"/></g><path fill="url(#iB98R1c)" clip-rule="evenodd" class="tghnx9bfm"/><path fill="url(#iFouQGe)" clip-rule="evenodd" class="tghnx9bfm"/><path fill="url(#idKcIze)" clip-rule="evenodd" class="tghnx9bfm"/><path fill="url(#iQSy4ic)" clip-rule="evenodd" class="tghnx9bfm"/><path fill="url(#iLE8Epb)" clip-rule="evenodd" class="a1_a0ybzq"/><path fill="url(#iVRG0wb)" clip-rule="evenodd" class="a1_a0ybzq"/><path fill="url(#iGPTVhC)" clip-rule="evenodd" class="a1_a0ybzq"/><path fill="url(#icJYonc)" clip-rule="evenodd" class="a1_a0ybzq"/><path fill="url(#iDJAbBe)" clip-rule="evenodd" class="ktv_vnokm"/><path fill="url(#iSSu21b)" clip-rule="evenodd" class="ktv_vnokm"/><path fill="url(#iqDXrhc)" clip-rule="evenodd" class="ktv_vnokm"/><path fill="url(#iU8GJbe)" clip-rule="evenodd" class="ktv_vnokm"/><path fill="url(#iyjUVad)" clip-rule="evenodd" class="s83e-pbfa"/><path fill="url(#ipBX8Gd)" clip-rule="evenodd" class="s83e-pbfa"/><path fill="url(#iLGTcye)" clip-rule="evenodd" class="s83e-pbfa"/><path fill="url(#iqyCCll)" class="jno7r7bdm"/><path fill="url(#iPi2bUd)" class="jno7r7bdm"/><path fill="url(#iQV4DEo)" class="akc1ait7x"/><path fill="url(#iJwYWJb)" class="akc1ait7x"/><path fill="url(#ihbUWac)" class="akc1ait7x"/><g filter="url(#iWnR5cc)"><path fill="url(#iE8lrIy)" class="n5s5_2bqw"/><path fill="url(#iJJFMTk)" class="n5s5_2bqw"/><path fill="url(#iu5waGs)" class="n5s5_2bqw"/><path fill="url(#ixdOqdb)" class="n5s5_2bqw"/><path fill="url(#iiRqTNB)" class="n5s5_2bqw"/></g><path fill="url(#iRRM7jb)" class="mhi8h1c0n"/><path fill="url(#iy6md2c)" class="mhi8h1c0n"/><g filter="url(#iVMGJne)"><path stroke="url(#iTHmK7L)" class="v4-mqdbdd"/></g><g filter="url(#izpoLhc)"><path class="m-astwb5v"/></g><g filter="url(#ipLCIkc)"><path class="amgf4bf3l"/></g><g filter="url(#iWE9jZv)"><path stroke="url(#iJ8BkQc)" class="t59-q-b0g"/></g><g filter="url(#ihaCmzx)"><path fill="url(#it74iZb)" class="vrhzrlsql"/></g><circle fill="url(#iWChsfc)" transform="rotate(-4.735 11.265 13.321)" class="s0_x4gaeh"/><g filter="url(#inX9zeV)"><circle fill="url(#irkK8Be)" transform="rotate(-4.735 11.265 13.321)" class="he72j9f4v"/></g><g filter="url(#iyB4oje)"><circle fill="url(#iBFzzye)" transform="rotate(-4.735 19.922 12.604)" class="tyxt6ybtg"/><circle fill="url(#ip02IIb)" transform="rotate(-4.735 19.922 12.604)" class="tyxt6ybtg"/></g><g filter="url(#iAC4L0c)"><circle transform="rotate(-4.735 19.922 12.604)" class="g_w80shpd"/><circle fill="url(#iZ3goge)" transform="rotate(-4.735 19.922 12.604)" class="zw94qgwtc"/><circle fill="url(#i47KO2b)" transform="rotate(-4.735 19.922 12.604)" class="zw94qgwtc"/></g><path fill="url(#iqHtr6b)" class="nfreikb7g"/><path fill="url(#iJXJ81c)" class="nfreikb7g"/><path fill="url(#iItogwd)" class="nfreikb7g"/><path fill="url(#i0UCOjb)" class="nfreikb7g"/><path fill="url(#iydomjB)" class="nfreikb7g"/><g filter="url(#iXQyemG)"><path class="ay0rcabjq"/><path fill="url(#iBSqfXb)" class="m0-gi4b7q"/><path fill="url(#ix2q7LE)" class="m0-gi4b7q"/><path fill="url(#iWXplrc)" class="m0-gi4b7q"/><path fill="url(#ilhsVId)" class="m0-gi4b7q"/><path fill="url(#i1ArZ8b)" class="m0-gi4b7q"/><path fill="url(#iSZ3bCd)" class="m0-gi4b7q"/></g><path fill="url(#iawMycc)" class="m0-gi4b7q"/><path fill="url(#ikzcZTd)" class="m0-gi4b7q"/><path fill="url(#irIgRDc)" class="m0-gi4b7q"/><g filter="url(#iwx1sRi)"><path class="vna6-fw8e"/></g><g filter="url(#i5kglBe)"><path class="cfwfdddxe"/><path fill="url(#iqyH1Yd)" class="a5p34_47j"/><path fill="url(#i8I82Uz)" class="a5p34_47j"/><path fill="url(#iq1IGEc)" class="a5p34_47j"/></g><path fill="url(#icyiBBD)" class="a5p34_47j"/><path class="l2yb3ct7g"/><path fill="url(#iEcyoRb)" class="x_bbe2uvb"/><path class="oukztv91p"/><g filter="url(#ibcNw8b)"><path class="d2swribtn"/><path fill="url(#ijIzJKb)" class="ixm2lel8b"/></g><g filter="url(#iJ88OtD)"><path fill="url(#iWFoRZd)" class="vmbm81b0c"/></g><path class="aceshxxms"/><path fill="url(#irTxZjb)" class="lgfn4tb7n"/><path class="ckcnwob5z"/><g filter="url(#iMuXSTc)"><path fill="url(#ifSWKKe)" class="i-nrqt5ai"/></g><g filter="url(#iwnAGOw)"><ellipse transform="rotate(-32.65 13.292 12.44)" class="vctalobnj"/><ellipse fill="url(#ivahjab)" transform="rotate(-32.65 13.292 12.44)" class="jkci_3jif"/></g><g filter="url(#iy4sKse)"><path fill="url(#iLXQKKb)" clip-rule="evenodd" class="u3460qbsj"/></g><g filter="url(#iOu15Nd)"><path class="m5b8rab0g"/></g><g filter="url(#i323Utb)"><path fill="url(#iXzqkKb)" clip-rule="evenodd" class="iyk8lwb6j"/></g><g filter="url(#iFAQKxb)"><path class="fobjl-bzk"/></g><g filter="url(#i2EeoTd)"><ellipse stroke="url(#izklaic)" class="d5rgtwblc"/></g><ellipse class="o1x20n91f"/><defs><radialGradient id="iYin6db" cx="0" cy="0" r="1" gradientTransform="rotate(160.563 1.553 6.597)scale(1.8701 4.54015)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="snr00mg_h"/><stop offset=".902" class="p9i49dbyg"/></radialGradient><radialGradient id="itUwzHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17357 1.11344 -2.78778 -2.93833 3.824 12.676)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="snr00mg_h"/><stop offset=".902" class="p9i49dbyg"/></radialGradient><radialGradient id="iAf8Hpe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26983 1.10163 -2.12498 -2.44943 4.03 13.622)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="snr00mg_h"/><stop offset=".925" class="p9i49dbyg"/></radialGradient><radialGradient id="iZqNyxU" cx="0" cy="0" r="1" gradientTransform="matrix(2.0625 .72055 -1.49936 4.29176 5 14.06)" gradientUnits="userSpaceOnUse"><stop class="tomvsgg1z"/><stop offset="1" class="w1ze_ourm"/></radialGradient><radialGradient id="igXiHgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.52138 .86916 -1.0215 -.61276 7.166 11.483)" gradientUnits="userSpaceOnUse"><stop class="xnz12146t"/><stop offset="1" class="kss0s4bml"/></radialGradient><radialGradient id="iselgIc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.01562 .20314 -.08201 -.81376 6.447 16.269)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="sal1d01zm"/><stop offset="1" class="csb_25bkg"/></radialGradient><radialGradient id="iFouQGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.87189 .7983 -.7298 -.79708 28.847 12.057)" gradientUnits="userSpaceOnUse"><stop class="ula9ko11i"/><stop offset="1" class="jr88e7bxh"/></radialGradient><radialGradient id="idKcIze" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 1.54687 -3.48696 4.43799 26.158 12.269)" gradientUnits="userSpaceOnUse"><stop offset=".675" class="k7amnqbjh"/><stop offset=".927" class="hslupxxwt"/></radialGradient><radialGradient id="iQSy4ic" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 -.78125 .88576 -.99206 27.822 13.487)" gradientUnits="userSpaceOnUse"><stop class="xs1396byz"/><stop offset="1" class="t-vhu5osi"/></radialGradient><radialGradient id="iVRG0wb" cx="0" cy="0" r="1" gradientTransform="rotate(131.73 12.166 12.9)scale(1.16966 1.06648)" gradientUnits="userSpaceOnUse"><stop class="ula9ko11i"/><stop offset="1" class="jr88e7bxh"/></radialGradient><radialGradient id="iGPTVhC" cx="0" cy="0" r="1" gradientTransform="matrix(1.08542 1.24122 -5.12978 4.48588 28.12 13.365)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="k7amnqbjh"/><stop offset=".912" class="hslupxxwt"/></radialGradient><radialGradient id="icJYonc" cx="0" cy="0" r="1" gradientTransform="rotate(-134.288 17.405 .891)scale(1.55128 1.67148)" gradientUnits="userSpaceOnUse"><stop class="xs1396byz"/><stop offset="1" class="t-vhu5osi"/></radialGradient><radialGradient id="iSSu21b" cx="0" cy="0" r="1" gradientTransform="matrix(1.10937 .9375 -3.17994 3.76294 27.869 14.237)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="k7amnqbjh"/><stop offset="1" class="hslupxxwt"/></radialGradient><radialGradient id="iqDXrhc" cx="0" cy="0" r="1" gradientTransform="rotate(138.972 12.45 12.286)scale(1.18852 1.0803)" gradientUnits="userSpaceOnUse"><stop class="ula9ko11i"/><stop offset="1" class="jr88e7bxh"/></radialGradient><radialGradient id="iU8GJbe" cx="0" cy="0" r="1" gradientTransform="rotate(-137.781 17.28 1.82)scale(1.45679 1.64014)" gradientUnits="userSpaceOnUse"><stop class="xs1396byz"/><stop offset="1" class="t-vhu5osi"/></radialGradient><radialGradient id="ipBX8Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73437 1.86015 -3.71825 1.46794 27.337 14.722)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="davf0hbbe"/><stop offset="1" class="ewsia9bsk"/></radialGradient><radialGradient id="iLGTcye" cx="0" cy="0" r="1" gradientTransform="matrix(-.89843 .6875 -.60902 -.79588 29.595 14.37)" gradientUnits="userSpaceOnUse"><stop class="ula9ko11i"/><stop offset="1" class="jr88e7bxh"/></radialGradient><radialGradient id="iqyCCll" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94297 -2.39063 0 26.203 16.425)" gradientUnits="userSpaceOnUse"><stop class="gqn4jccjs"/><stop offset="1" class="wjksmgbzx"/></radialGradient><radialGradient id="iJwYWJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.14902 -.68994 0 7.563 16.656)" gradientUnits="userSpaceOnUse"><stop class="ne51g8a0v"/><stop offset="1" class="opxc931wt"/></radialGradient><radialGradient id="iE8lrIy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4411 10.6867 0 19.921 29.41)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="lrtmembqg"/><stop offset="1" class="wex0y_b-c"/></radialGradient><radialGradient id="iJJFMTk" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01666 3.53393 -1.57189 -1.3418 9.813 20.024)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="o0f91ub3g"/><stop offset="1" class="mtrk0zxts"/><stop offset="1" class="ddt_3pbvb"/></radialGradient><radialGradient id="iu5waGs" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.46944 -4.08022 0 27.015 16.972)" gradientUnits="userSpaceOnUse"><stop class="xq9fh8b3s"/><stop offset="1" class="j072wlbar"/></radialGradient><radialGradient id="ixdOqdb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2344 3.40893 -.45438 -.29783 9.719 20.149)" gradientUnits="userSpaceOnUse"><stop class="o18y7cctk"/><stop offset="1" class="p8zx0emkh"/></radialGradient><radialGradient id="iiRqTNB" cx="0" cy="0" r="1" gradientTransform="matrix(-5.68753 3.4062 -1.542 -2.57478 14.422 17.899)" gradientUnits="userSpaceOnUse"><stop offset=".066" class="owv1iubqi"/><stop offset="1" class="ggk_44bdp"/></radialGradient><radialGradient id="iRRM7jb" cx="0" cy="0" r="1" gradientTransform="matrix(2.0625 2.17783 -3.3043 3.12931 15.594 18.135)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="goew_cc_s"/><stop offset="1" class="k9g61-xec"/></radialGradient><radialGradient id="iWChsfc" cx="0" cy="0" r="1" gradientTransform="matrix(1.60238 0 0 2.80418 9.74 13.321)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ip02IIb" cx="0" cy="0" r="1" gradientTransform="matrix(.75487 -.54966 .62737 .86159 20.262 12.362)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iZ3goge" cx="0" cy="0" r="1" gradientTransform="matrix(.7499 -1.37928 .8073 .43892 19.884 13.354)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="i47KO2b" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -5.364 30.524)scale(.33313 .42946)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iItogwd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 8.1875 -13.33132 -1.73002 18 11.687)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="k_g_adbjp"/><stop offset=".799" class="te9s5-bxm"/><stop offset="1" class="i9o-tbowi"/></radialGradient><radialGradient id="i0UCOjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.09853 -1.18944 1.46392 -.12126 17.624 11.63)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iydomjB" cx="0" cy="0" r="1" gradientTransform="matrix(-.10484 -1.26568 1.57398 -.13037 13.473 11.943)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iBSqfXb" cx="0" cy="0" r="1" gradientTransform="rotate(123.071 7.646 7.811)scale(5.11905 8.7054)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iWXplrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.31807 -1.79926 .88366 -.15621 11.547 9.964)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="ilhsVId" cx="0" cy="0" r="1" gradientTransform="matrix(.63358 -1.85424 1.51227 .51674 19.3 11.064)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="i1ArZ8b" cx="0" cy="0" r="1" gradientTransform="matrix(.99628 1.04615 -.92367 .87965 14.232 5.195)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iSZ3bCd" cx="0" cy="0" r="1" gradientTransform="rotate(-69.188 15.925 -9.427)scale(3.07224 1.0615)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iawMycc" cx="0" cy="0" r="1" gradientTransform="matrix(.31416 .90387 -1.486 .5165 15.57 5.084)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="ikzcZTd" cx="0" cy="0" r="1" gradientTransform="matrix(1.12784 1.37157 -2.85422 2.34702 11.044 6.614)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="irIgRDc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.314 3.49803 -4.37704 -7.90061 16.305 8.905)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iEcyoRb" cx="0" cy="0" r="1" gradientTransform="matrix(.06808 .82187 -.97248 .08055 17.542 12.481)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ijIzJKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23352 -.25442 .35027 -.3215 17.316 12.272)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irTxZjb" cx="0" cy="0" r="1" gradientTransform="matrix(.06808 .8219 -.97253 .08056 13.572 12.81)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ivahjab" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.904 -.172)scale(.4511 .54225)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLXQKKb" cx="0" cy="0" r="1" gradientTransform="matrix(.11789 -.75353 1.65313 .25863 17.65 10.777)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iXzqkKb" cx="0" cy="0" r="1" gradientTransform="rotate(-108.362 10.617 .814)scale(.7627 1.67323)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><linearGradient id="iGSn8Dc" x1="3.186" x2="5.185" y1="11.319" y2="13.656" gradientUnits="userSpaceOnUse"><stop class="qql0_6xdf"/><stop offset="1" class="q8bnjpbvp"/></linearGradient><linearGradient id="iZ8AUhe" x1="4.368" x2="6.779" y1="12.068" y2="14.282" gradientUnits="userSpaceOnUse"><stop class="px7lweb9d"/><stop offset="1" class="xdt-8bbcb"/></linearGradient><linearGradient id="ijf66ub" x1="2.313" x2="5.301" y1="12.167" y2="13.333" gradientUnits="userSpaceOnUse"><stop class="qql0_6xdf"/><stop offset=".988" class="q8bnjpbvp"/></linearGradient><linearGradient id="i1I4aae" x1="3.305" x2="5.715" y1="12.441" y2="14.655" gradientUnits="userSpaceOnUse"><stop class="px7lweb9d"/><stop offset="1" class="xdt-8bbcb"/></linearGradient><linearGradient id="icmzFec" x1="2.119" x2="6.853" y1="12.659" y2="14.753" gradientUnits="userSpaceOnUse"><stop class="qql0_6xdf"/><stop offset=".709" class="q8bnjpbvp"/></linearGradient><linearGradient id="ixwriRw" x1="3.229" x2="5.82" y1="13.432" y2="15.431" gradientUnits="userSpaceOnUse"><stop class="px7lweb9d"/><stop offset="1" class="xdt-8bbcb"/></linearGradient><linearGradient id="ik1sdFc" x1="3.337" x2="6.134" y1="15.237" y2="15.237" gradientUnits="userSpaceOnUse"><stop class="qql0_6xdf"/><stop offset="1" class="q8bnjpbvp"/></linearGradient><linearGradient id="ikAMzBa" x1="7.805" x2="7.805" y1="16.639" y2="15.313" gradientUnits="userSpaceOnUse"><stop class="d4zyoh72j"/><stop offset="1" class="qzjk6tgvq"/></linearGradient><linearGradient id="iYE41Zf" x1="8.865" x2="8.024" y1="15.716" y2="15.716" gradientUnits="userSpaceOnUse"><stop offset=".005" class="zhlpa-bmw"/><stop offset="1" class="gp6jyoetb"/></linearGradient><linearGradient id="ixEuNeb" x1="23.159" x2="25.615" y1="15.615" y2="15.615" gradientUnits="userSpaceOnUse"><stop class="lx3uihbvp"/><stop offset="1" class="mqki6tbbj"/></linearGradient><linearGradient id="iB98R1c" x1="28.173" x2="26.036" y1="12.511" y2="14.212" gradientUnits="userSpaceOnUse"><stop class="b93mgob3x"/><stop offset="1" class="frlmzd7od"/></linearGradient><linearGradient id="iLE8Epb" x1="29.064" x2="26.541" y1="13.073" y2="14.765" gradientUnits="userSpaceOnUse"><stop class="b93mgob3x"/><stop offset="1" class="frlmzd7od"/></linearGradient><linearGradient id="iDJAbBe" x1="29.343" x2="26.573" y1="15.155" y2="15.111" gradientUnits="userSpaceOnUse"><stop class="b93mgob3x"/><stop offset="1" class="frlmzd7od"/></linearGradient><linearGradient id="iyjUVad" x1="29.029" x2="26.254" y1="15.934" y2="15.884" gradientUnits="userSpaceOnUse"><stop class="b93mgob3x"/><stop offset="1" class="frlmzd7od"/></linearGradient><linearGradient id="iPi2bUd" x1="23.662" x2="24.149" y1="17.407" y2="17.399" gradientUnits="userSpaceOnUse"><stop class="g15pupb2m"/><stop offset="1" class="dqcsylboi"/></linearGradient><linearGradient id="iQV4DEo" x1="7.031" x2="9.719" y1="17.115" y2="17.115" gradientUnits="userSpaceOnUse"><stop class="gy5j7812b"/><stop offset="1" class="vw_f_cbup"/></linearGradient><linearGradient id="ihbUWac" x1="6.873" x2="6.873" y1="16.425" y2="16.688" gradientUnits="userSpaceOnUse"><stop class="z96fdub7f"/><stop offset="1" class="j3txnddmt"/></linearGradient><linearGradient id="iy6md2c" x1="13.125" x2="15.688" y1="19.812" y2="19.812" gradientUnits="userSpaceOnUse"><stop class="vn5e6ebgx"/><stop offset="1" class="hdmzrbcfp"/></linearGradient><linearGradient id="iTHmK7L" x1="3.518" x2="6.325" y1="14.46" y2="16.141" gradientUnits="userSpaceOnUse"><stop class="px7lweb9d"/><stop offset="1" class="xdt-8bbcb"/></linearGradient><linearGradient id="iJ8BkQc" x1="9.86" x2="12.86" y1="26.144" y2="20.487" gradientUnits="userSpaceOnUse"><stop class="m41kspb0z"/><stop offset="1" class="gev2t0bey"/></linearGradient><linearGradient id="it74iZb" x1="25.449" x2="21.21" y1="26.229" y2="21.515" gradientUnits="userSpaceOnUse"><stop class="z108ppbpv"/><stop offset="1" class="sv_dn8bha"/></linearGradient><linearGradient id="irkK8Be" x1="11.265" x2="10.68" y1="13.576" y2="13.576" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iBFzzye" x1="20.914" x2="20.166" y1="11.607" y2="13.923" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iqHtr6b" x1="19.287" x2="12.424" y1="13.013" y2="14.624" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset="1" class="x2e45tbep"/></linearGradient><linearGradient id="iJXJ81c" x1="10.908" x2="12.989" y1="16.177" y2="15.729" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="ix2q7LE" x1="11.142" x2="13.394" y1="13.086" y2="8.177" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iqyH1Yd" x1="14.878" x2="15.732" y1="13.983" y2="13.912" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="i8I82Uz" x1="16.543" x2="15.608" y1="14.14" y2="14.204" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iq1IGEc" x1="15.922" x2="15.879" y1="14.872" y2="14.35" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="icyiBBD" x1="15.862" x2="15.85" y1="14.915" y2="14.763" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="iWFoRZd" x1="18.229" x2="17.958" y1="12.169" y2="12.368" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifSWKKe" x1="14.227" x2="13.956" y1="12.5" y2="12.7" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izklaic" x1="15.535" x2="15.852" y1="17.049" y2="15.914" gradientUnits="userSpaceOnUse"><stop class="e42abaczg"/><stop offset="1" class="lrj4dijcb"/></linearGradient><filter id="i5lDQXb" width="3.652" height="3.139" x="3.372" y="11.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".25"/></filter><filter id="iZ4w9ud" width="3.727" height="3.323" x="2.293" y="11.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".25"/></filter><filter id="ivK6sKb" width="3.867" height="3.135" x="2.223" y="12.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".25"/></filter><filter id="irMOgKb" width="3.408" height="5.156" x="23.701" y="11.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.701961 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4181"/></filter><filter id="iWnR5cc" width="23.107" height="13.423" x="4.624" y="16.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.411765 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4181"/></filter><filter id="iVMGJne" width="4.031" height="2.858" x="2.522" y="13.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".25"/></filter><filter id="izpoLhc" width="8.199" height="8.945" x="5.11" y="16.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".75"/></filter><filter id="ipLCIkc" width="7.102" height="8.493" x="20.783" y="16.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".625"/></filter><filter id="iWE9jZv" width="3.956" height="6.956" x="9.209" y="19.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".25"/></filter><filter id="ihaCmzx" width="5.986" height="5.519" x="20.41" y="21.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".4"/></filter><filter id="inX9zeV" width="2.817" height="2.817" x="9.856" y="11.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".25"/></filter><filter id="iyB4oje" width="3.299" height="3.299" x="18.397" y="10.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4181"/></filter><filter id="iAC4L0c" width="2.817" height="2.817" x="18.513" y="11.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".25"/></filter><filter id="iXQyemG" width="11.476" height="8.197" x="9.51" y="4.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4181"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4181" result="effect2_innerShadow_4002_4181"/></filter><filter id="iwx1sRi" width="3.105" height="3.982" x="13.946" y="11.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".375"/></filter><filter id="i5kglBe" width="2.211" height="2.973" x="14.598" y="12.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".125"/></filter><filter id="ibcNw8b" width=".713" height=".679" x="16.843" y="11.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".05"/></filter><filter id="iJ88OtD" width=".86" height=".878" x="17.604" y="11.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".1"/></filter><filter id="iMuXSTc" width=".953" height=".991" x="13.557" y="12.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".1"/></filter><filter id="iwnAGOw" width=".83" height=".689" x="12.877" y="12.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".05"/></filter><filter id="iy4sKse" width="2.404" height="1.427" x="16.532" y="9.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4181"/></filter><filter id="iOu15Nd" width="2.591" height="1.365" x="16.43" y="9.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".2"/></filter><filter id="i323Utb" width="2.338" height="1.638" x="11.898" y="9.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4181"/></filter><filter id="iFAQKxb" width="2.525" height="1.575" x="11.796" y="10.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".2"/></filter><filter id="i2EeoTd" width="1.869" height="1.911" x="14.965" y="15.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4181" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-shrugging" /></template>
<style>
.a1_a0ybzq {
  fill-rule: evenodd;
  d: path("M29.647 12.147a.7.7 0 0 0-.978.157q-.05.071-.115.168c-.261.39-.92 1.113-1.732 1.46c-.356.153-.503.45-.32.876c.152.355.733.502 1.088.35c1.246-.533 1.935-1.603 2.156-1.945l.058-.089a.7.7 0 0 0-.157-.977");
}

.a5p34_47j {
  d: path("m15.216 12.732l-.355 1.587a.492.492 0 0 0 .526.597l.715-.06a.494.494 0 0 0 .421-.675l-.611-1.506c-.132-.334-.616-.294-.696.057");
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.aceshxxms {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.3 11.842c-.594.049-1.062.5-1.153 1.065a.25.25 0 0 0 .27.29l2.03-.168a.21.21 0 0 0 .185-.265a1.28 1.28 0 0 0-1.332-.922");
}

.akc1ait7x {
  d: path("M5.158 16.675a.25.25 0 0 1 .25-.25h2.93a.25.25 0 0 1 .25.25v1.13h-3.43z");
}

.amgf4bf3l {
  stroke: var(--svg-color--4abeff, #4ABEFF);
  stroke-linecap: square;
  d: path("M26.134 18.413v3.99a1 1 0 0 1-1.567.824l-1.839-1.265");
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.ay0rcabjq {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m19.482 6.705l.407.162c.711.283 1.166 1.027 1.088 1.865l-.308 2.81c-.024.29-.197.498-.48.529c-.006-.461-.037-1.203-.035-1.32c.008-.398-.064-.51-.455-.839a1.15 1.15 0 0 1-.406-.748l-.064-.776a.525.525 0 0 0-.431-.453c-.598-.097-1.838-.239-3.596-.093c-1.757.145-2.957.489-3.53.683a.475.475 0 0 0-.351.518l.064.776c.024.291-.05.59-.277.805l-.134.158c-.184.162-.257.474-.237.717c.025.14.112.954.161 1.291a.58.58 0 0 1-.58-.439L9.55 9.63c-.162-.768.164-1.577.82-1.974c.889-.48 1.174-1.122 1.864-1.815a1.79 1.79 0 0 1 1.977-.457c.5.105 1.037.06 1.514-.126c.712-.303 1.557-.178 2.187.308l.793.667c.215.227.471.352.776.473");
}

.b93mgob3x {
  stop-color: var(--svg-color--ffb620, #FFB620);
}

.cfwfdddxe {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.216 12.732l-.355 1.587a.492.492 0 0 0 .526.597l.715-.06a.494.494 0 0 0 .421-.675l-.611-1.506c-.132-.334-.616-.294-.696.057");
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckcnwob5z {
  fill: var(--svg-color--000, #000);
  d: path("M14.04 12.847a.465.465 0 0 0-.503-.427a.465.465 0 0 0-.357.714l.823-.069a.46.46 0 0 0 .038-.218");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.csb_25bkg {
  stop-color: var(--svg-color--f4a82e, #F4A82E);
  stop-opacity: 0;
}

.d2swribtn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.437 11.92c.064.073-.049.178-.178.292s-.225.195-.289.122c-.064-.072-.012-.224.117-.338c.13-.114.286-.148.35-.075");
}

.d4zyoh72j {
  stop-color: var(--svg-color--f0a330, #F0A330);
}

.d5rgtwblc {
  cx: 15.899px;
  cy: 16.294px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  rx: 0.734px;
  ry: 0.755px;
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.davf0hbbe {
  stop-color: var(--svg-color--e08f52, #E08F52);
  stop-opacity: 0;
}

.ddt_3pbvb {
  stop-color: var(--svg-color--1a78c7, #1A78C7);
  stop-opacity: 0;
}

.dqcsylboi {
  stop-color: var(--svg-color--257fbf, #257FBF);
  stop-opacity: 0;
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e314ej6ax {
  fill-rule: evenodd;
  d: path("M2.57 13.169a.7.7 0 0 1 .98.142q.042.054.087.118c.301.42.763 1.062 1.778 1.062a.7.7 0 1 1 0 1.4c-1.775 0-2.636-1.24-2.924-1.655l-.062-.087a.7.7 0 0 1 .142-.98");
}

.e42abaczg {
  stop-color: var(--svg-color--ffb63a, #FFB63A);
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ewsia9bsk {
  stop-color: var(--svg-color--e08f52, #E08F52);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fobjl-bzk {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.32 11.083c.177-.19.692-.533 1.476-.525");
}

.frlmzd7od {
  stop-color: var(--svg-color--ffd02e, #FFD02E);
}

.ft5dv1b6b {
  fill: none;
}

.g_w80shpd {
  cx: 19.922px;
  cy: 12.604px;
  r: 0.909px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.g15pupb2m {
  stop-color: var(--svg-color--257fbf, #257FBF);
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.gev2t0bey {
  stop-color: var(--svg-color--2e6efa, #2E6EFA);
  stop-opacity: 0;
}

.ggk_44bdp {
  stop-color: var(--svg-color--2069a2, #2069A2);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.goew_cc_s {
  stop-color: var(--svg-color--e6983b, #E6983B);
}

.gp6jyoetb {
  stop-color: var(--svg-color--d6933e, #D6933E);
  stop-opacity: 0;
}

.gqn4jccjs {
  stop-color: var(--svg-color--47adf9, #47ADF9);
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.gy5j7812b {
  stop-color: var(--svg-color--4a9ee0, #4A9EE0);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hdmzrbcfp {
  stop-color: var(--svg-color--c29a3f, #C29A3F);
  stop-opacity: 0;
}

.he72j9f4v {
  cx: 11.265px;
  cy: 13.321px;
  r: 0.909px;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hslupxxwt {
  stop-color: var(--svg-color--e6b03b, #E6B03B);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i-nrqt5ai {
  d: path("M14.31 12.729c-.022-.263-.25-.42-.312-.468l-.241.275l.188.316z");
}

.i9o-tbowi {
  stop-color: var(--svg-color--b17b57, #B17B57);
}

.itdn4bbbj {
  d: path("M26.127 11.638a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.675v2.141h3.258v-2.698h-1.626q.053-.108.127-.204l.805-1.047a.75.75 0 0 0-.138-1.052");
}

.itisl1bsn {
  fill-rule: evenodd;
  d: path("M2.603 12.147a.7.7 0 0 1 .977.157q.05.071.115.168c.262.39.704 1.052 1.516 1.4a.7.7 0 0 1-.551 1.286c-1.246-.533-1.935-1.603-2.156-1.945l-.058-.089a.7.7 0 0 1 .157-.977");
}

.ixm2lel8b {
  d: path("M17.437 11.92c.064.073-.049.178-.178.292s-.225.195-.289.122c-.064-.072-.012-.224.117-.338c.13-.114.286-.148.35-.075");
}

.iyk8lwb6j {
  fill-rule: evenodd;
  d: path("M13.8 11.09c-.66-.007-1.06.284-1.154.386a.431.431 0 0 1-.634-.584c.257-.28.889-.674 1.797-.664a.431.431 0 1 1-.01.862");
}

.j072wlbar {
  stop-color: var(--svg-color--3dbeff, #3DBEFF);
  stop-opacity: 0;
}

.j3txnddmt {
  stop-color: var(--svg-color--3481c0, #3481C0);
  stop-opacity: 0;
}

.jkci_3jif {
  cx: 13.292px;
  cy: 12.441px;
  rx: 0.356px;
  ry: 0.18px;
}

.jno7r7bdm {
  d: path("M27.092 16.675a.25.25 0 0 0-.25-.25h-2.93a.25.25 0 0 0-.25.25v1.318h3.43z");
}

.jr88e7bxh {
  stop-color: var(--svg-color--ffdb42, #FFDB42);
  stop-opacity: 0;
}

.k_g_adbjp {
  stop-color: var(--svg-color--fda42b, #FDA42B);
  stop-opacity: 0;
}

.k3z32yv2o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M3.023 13.507c.239.483.967 1.38 2.267 1.534");
}

.k7amnqbjh {
  stop-color: var(--svg-color--e6b03b, #E6B03B);
  stop-opacity: 0;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.k9g61-xec {
  stop-color: var(--svg-color--ffcd40, #FFCD40);
}

.kss0s4bml {
  stop-color: var(--svg-color--eaa82a, #EAA82A);
  stop-opacity: 0;
}

.ktv_vnokm {
  fill-rule: evenodd;
  d: path("M29.679 13.169a.7.7 0 0 0-.98.142l-.086.118c-.302.42-.763 1.062-1.779 1.062a.7.7 0 1 0 0 1.4c1.776 0 2.637-1.24 2.925-1.655q.037-.054.062-.087a.7.7 0 0 0-.142-.98");
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l2yb3ct7g {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.65 11.481c.595-.049 1.13.32 1.313.861a.25.25 0 0 1-.218.33l-2.03.169a.21.21 0 0 1-.227-.23a1.276 1.276 0 0 1 1.162-1.13");
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lgfn4tb7n {
  d: path("M13.509 12.073a.815.815 0 0 0-.698 1.091l1.569-.13a.82.82 0 0 0-.871-.96");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lrj4dijcb {
  stop-color: var(--svg-color--ffb63a, #FFB63A);
  stop-opacity: 0;
}

.lrtmembqg {
  stop-color: var(--svg-color--34b2ff, #34B2FF);
}

.lx3uihbvp {
  stop-color: var(--svg-color--f4a421, #F4A421);
}

.m-astwb5v {
  stroke: var(--svg-color--40a1ff, #40A1FF);
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.36 18.993v3.442a1 1 0 0 0 1.566.823l1.84-1.265");
}

.m0-gi4b7q {
  d: path("m19.482 6.705l.407.162c.711.283 1.166 1.027 1.088 1.865l-.308 2.81c-.024.29-.197.498-.48.529c-.006-.461-.037-1.203-.035-1.32c.008-.398-.064-.51-.455-.839a1.15 1.15 0 0 1-.406-.748l-.064-.776a.525.525 0 0 0-.431-.453c-.598-.097-1.838-.239-3.596-.093c-1.757.145-2.957.489-3.53.683a.475.475 0 0 0-.351.518l.064.776c.024.291-.05.59-.277.805l-.134.158c-.184.162-.257.474-.237.717c.025.14.112.954.161 1.291a.58.58 0 0 1-.58-.439L9.55 9.63c-.162-.768.164-1.577.82-1.974c.889-.48 1.174-1.122 1.864-1.815a1.79 1.79 0 0 1 1.977-.457c.5.105 1.037.06 1.514-.126c.712-.303 1.557-.178 2.187.308l.793.667c.215.227.471.352.776.473");
}

.m41kspb0z {
  stop-color: var(--svg-color--2e6efa, #2E6EFA);
}

.m5b8rab0g {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.496 10.572c-.205-.16-.77-.413-1.541-.275");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mhi8h1c0n {
  d: path("M16.025 21.078c-1.104 0-2-.95-2-1.867v-2.358c0-.918.896-1.662 2-1.662s2 .744 2 1.661v2.359c0 .917-.895 1.867-2 1.867");
}

.mqki6tbbj {
  stop-color: var(--svg-color--f4a421, #F4A421);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mtrk0zxts {
  stop-color: var(--svg-color--51aaff, #51AAFF);
  stop-opacity: 0;
}

.n5s5_2bqw {
  d: path("M9.484 20.903a.25.25 0 0 1-.375-.216v-2.563a.6.6 0 0 0-.6-.6H5.224a.6.6 0 0 0-.6.6v4.286c-.005.849.112 2.507 1.485 3.383c1.148.733 2.5.57 3.213.347a.16.16 0 0 1 .208.148v3.706c0 .083.068.15.15.15h12.994a.15.15 0 0 0 .15-.15v-3.706c0-.106.108-.18.209-.148c.713.222 2.065.386 3.213-.347c1.373-.876 1.49-2.534 1.485-3.383v-4.286a.6.6 0 0 0-.6-.6h-3.285a.6.6 0 0 0-.6.6v2.563a.25.25 0 0 1-.375.216l-6.694-3.931z");
}

.ne51g8a0v {
  stop-color: var(--svg-color--3990dd, #3990DD);
}

.nfreikb7g {
  d: path("M10.898 12.79a27 27 0 0 1-.161-1.305c-.02-.242.053-.542.237-.703l.134-.158c.228-.214.301-.514.277-.805l-.064-.776a.475.475 0 0 1 .35-.518c.574-.194 1.774-.538 3.531-.684c1.758-.145 2.998-.004 3.596.094c.199.032.41.21.43.453l.065.776c.024.291.195.57.406.748c.483.283.47.461.463.842c-.002.117.04 1.09.027 1.316l.056 3.623c-.012 1.622-1.185 2.85-2.695 2.974l-2.921.242c-1.558.13-2.868-.892-3.148-2.49z");
}

.o0f91ub3g {
  stop-color: var(--svg-color--1a78c7, #1A78C7);
}

.o18y7cctk {
  stop-color: var(--svg-color--389bfa, #389BFA);
}

.o1x20n91f {
  cx: 15.899px;
  cy: 16.294px;
  fill: var(--svg-color--88004d, #88004D);
  rx: 0.734px;
  ry: 0.755px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.opxc931wt {
  stop-color: var(--svg-color--3990dd, #3990DD);
  stop-opacity: 0;
}

.or_xa3b0i {
  fill-rule: evenodd;
  d: path("M2.883 14.2a.7.7 0 0 1 .98.142c.181.242.653.84 1.873.84a.7.7 0 1 1 0 1.4c-1.827 0-2.668-.965-2.995-1.402a.7.7 0 0 1 .142-.98");
}

.oukztv91p {
  fill: var(--svg-color--000, #000);
  d: path("M17.085 12.595a.465.465 0 0 1 .426-.504a.465.465 0 0 1 .47.645l-.823.068a.4.4 0 0 1-.073-.21");
}

.owv1iubqi {
  stop-color: var(--svg-color--2069a2, #2069A2);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.p8zx0emkh {
  stop-color: var(--svg-color--389bfa, #389BFA);
  stop-opacity: 0;
}

.p9i49dbyg {
  stop-color: var(--svg-color--cd9143, #CD9143);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pgkimacqn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M3.094 12.497c.196.502.844 1.459 2.127 1.723");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px7lweb9d {
  stop-color: var(--svg-color--ffba34, #FFBA34);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q8bnjpbvp {
  stop-color: var(--svg-color--e0a32a, #E0A32A);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qpugwjd8e {
  fill: var(--svg-color--d2a530, #D2A530);
  d: path("M6.123 11.638a.75.75 0 0 1 1.051.138l.805 1.047c.37.48.57 1.07.57 1.675v2.141H5.29v-2.698h1.626a1.3 1.3 0 0 0-.128-.204l-.804-1.047a.75.75 0 0 1 .138-1.052");
}

.qql0_6xdf {
  stop-color: var(--svg-color--ea9c30, #EA9C30);
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzjk6tgvq {
  stop-color: var(--svg-color--d3a630, #D3A630);
  stop-opacity: 0;
}

.r5wm-vlaj {
  d: path("M6.123 11.638a.75.75 0 0 1 1.051.138l.805 1.047c.37.48.57 1.07.57 1.675v2.141H5.29v-2.698h1.626a1.3 1.3 0 0 0-.128-.204l-.804-1.047a.75.75 0 0 1 .138-1.052");
}

.rfksyecjs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M4.172 12.217c.196.502 1.018 1.388 2.052 1.54");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s0_x4gaeh {
  cx: 11.265px;
  cy: 13.321px;
  r: 1.524px;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s83e-pbfa {
  fill-rule: evenodd;
  d: path("M29.367 14.2a.7.7 0 0 0-.98.142c-.181.242-.654.84-1.873.84a.7.7 0 1 0 0 1.4c1.827 0 2.668-.965 2.994-1.402a.7.7 0 0 0-.142-.98");
}

.sal1d01zm {
  stop-color: var(--svg-color--f4a82e, #F4A82E);
}

.snr00mg_h {
  stop-color: var(--svg-color--cd9143, #CD9143);
  stop-opacity: 0;
}

.sv_dn8bha {
  stop-color: var(--svg-color--1e72ff, #1E72FF);
  stop-opacity: 0;
}

.t-vhu5osi {
  stop-color: var(--svg-color--dda01e, #DDA01E);
  stop-opacity: 0;
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t59-q-b0g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.86 25.675c.177-1.146.956-3.881 2.656-5.656");
}

.te9s5-bxm {
  stop-color: var(--svg-color--e5883f, #E5883F);
}

.tghnx9bfm {
  fill-rule: evenodd;
  d: path("M28.608 11.83a.7.7 0 0 0-.978.157a2 2 0 0 0-.115.183l-.006.01v.002l-.105.174a2 2 0 0 1-.294.37c-.233.228-.608.468-1.267.5a.7.7 0 1 0 .068 1.398c1.025-.05 1.718-.447 2.179-.898c.223-.22.382-.442.495-.618c.053-.084.098-.16.13-.216l.004-.007l.044-.075l.002-.002a.7.7 0 0 0-.157-.978");
}

.tomvsgg1z {
  stop-color: var(--svg-color--e9a92e, #E9A92E);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tyxt6ybtg {
  cx: 19.922px;
  cy: 12.604px;
  r: 1.524px;
}

.u3460qbsj {
  fill-rule: evenodd;
  d: path("M17.039 10.822c.65-.116 1.09.105 1.2.19a.431.431 0 1 0 .53-.68c-.3-.234-.987-.518-1.881-.36a.431.431 0 1 0 .15.85");
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.ula9ko11i {
  stop-color: var(--svg-color--ffdb42, #FFDB42);
}

.uylc3es2x {
  fill-rule: evenodd;
  d: path("M3.642 11.83a.7.7 0 0 1 .977.157a2 2 0 0 1 .121.193l.001.002c.034.057.066.113.105.174c.077.12.17.25.294.37c.232.228.607.468 1.267.5a.7.7 0 0 1-.069 1.398c-1.024-.05-1.717-.447-2.178-.898a3.5 3.5 0 0 1-.495-.618a6 6 0 0 1-.13-.216l-.004-.007c-.029-.049-.04-.069-.045-.075l-.001-.002a.7.7 0 0 1 .157-.978");
}

.v4-mqdbdd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M3.322 14.558c.293.451 1.121 1.257 2.431 1.257");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vctalobnj {
  cx: 13.292px;
  cy: 12.441px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.356px;
  ry: 0.18px;
}

.vmbm81b0c {
  d: path("M18.264 12.39a.77.77 0 0 0-.245-.404l-.215.279l.124.199z");
}

.vn5e6ebgx {
  stop-color: var(--svg-color--c29a3f, #C29A3F);
}

.vna6-fw8e {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.326 12.873l-.619 1.608c-.066.326.182.626.497.6l.67-.056c.315-.026.51-.367.392-.673l-.581-1.509c-.126-.335-.286-.321-.36.03");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vrhzrlsql {
  d: path("m21.21 22.153l1.542 3.67c1.207.44 2.534.203 2.844 0z");
}

.vw_f_cbup {
  stop-color: var(--svg-color--227bc3, #227BC3);
}

.w1ze_ourm {
  stop-color: var(--svg-color--e9a92e, #E9A92E);
  stop-opacity: 0;
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wex0y_b-c {
  stop-color: var(--svg-color--3395fe, #3395FE);
}

.wjksmgbzx {
  stop-color: var(--svg-color--308bdb, #308BDB);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x_bbe2uvb {
  d: path("M17.483 11.744a.815.815 0 0 1 .867.961l-1.569.13a.818.818 0 0 1 .701-1.091");
}

.x2e45tbep {
  stop-color: var(--svg-color--ffac1b, #FFAC1B);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xdt-8bbcb {
  stop-color: var(--svg-color--ffba34, #FFBA34);
  stop-opacity: 0;
}

.xnz12146t {
  stop-color: var(--svg-color--eaa82a, #EAA82A);
}

.xq9fh8b3s {
  stop-color: var(--svg-color--3dbeff, #3DBEFF);
}

.xs1396byz {
  stop-color: var(--svg-color--dda01e, #DDA01E);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ypv5ckobw {
  fill: var(--svg-color--ffd02e, #FFD02E);
  d: path("M26.127 11.638a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.675v2.141h3.258v-2.698h-1.626q.053-.108.127-.204l.805-1.047a.75.75 0 0 0-.138-1.052");
}

.z108ppbpv {
  stop-color: var(--svg-color--1e72ff, #1E72FF);
}

.z96fdub7f {
  stop-color: var(--svg-color--3481c0, #3481C0);
}

.zhlpa-bmw {
  stop-color: var(--svg-color--d6933e, #D6933E);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zw94qgwtc {
  cx: 19.922px;
  cy: 12.604px;
  r: 0.909px;
}

</style>
