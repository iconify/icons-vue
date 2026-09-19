<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFGOkwe)"><path fill="url(#iAO6TiE)" clip-rule="evenodd" class="bv6krxq7x"/><path fill="url(#ivUjGMe)" clip-rule="evenodd" class="bv6krxq7x"/><path fill="url(#iddHdqd)" clip-rule="evenodd" class="bv6krxq7x"/><path fill="url(#i8KLqmd)" clip-rule="evenodd" class="bv6krxq7x"/><path fill="url(#iDsYvDc)" clip-rule="evenodd" class="bv6krxq7x"/><path fill="url(#ijuvWbA)" clip-rule="evenodd" class="bv6krxq7x"/><path fill="url(#iRnncZX)" clip-rule="evenodd" class="bv6krxq7x"/><path fill="url(#iqYw9dc)" clip-rule="evenodd" class="bv6krxq7x"/><path fill="url(#iLFNFyd)" clip-rule="evenodd" class="bv6krxq7x"/><path fill="url(#iPdxsxp)" clip-rule="evenodd" class="bv6krxq7x"/><path fill="url(#iBH0pxW)" clip-rule="evenodd" class="bv6krxq7x"/></g><path fill="url(#iOTSjsd)" class="iwijhb8cc"/><path fill="url(#iVt7Kmd)" class="iwijhb8cc"/><path fill="url(#ijJWFGd)" class="iwijhb8cc"/><path fill="url(#iuyr1tn)" class="iwijhb8cc"/><path fill="url(#iwTkvTT)" class="iwijhb8cc"/><path fill="url(#iGY3pLe)" class="z77pc-39f"/><path fill="url(#iOmSTFf)" class="z77pc-39f"/><g filter="url(#i6Ls2Cd)"><path fill="url(#iHafYHb)" class="uoh3u9bsv"/><path fill="url(#irRAuOe)" class="uoh3u9bsv"/></g><path fill="url(#iosNevc)" class="bv7-wxb3q"/><g filter="url(#iixJzAe)"><path fill="url(#i0qUINb)" class="wsuqc2bol"/><path fill="url(#iDSTCFe)" class="wsuqc2bol"/></g><g filter="url(#iNeD8td)"><path clip-rule="evenodd" class="nzd5pi4db"/></g><path fill="url(#iQD9ace)" class="pwzf73bct"/><path fill="url(#iulJYbe)" class="pwzf73bct"/><path fill="url(#i4qDnic)" class="pwzf73bct"/><path fill="url(#ig0Fqhd)" class="pwzf73bct"/><path fill="url(#i3hbZ4w)" class="d0ocvmu4d"/><path fill="url(#ivP7kqb)" class="d0ocvmu4d"/><path fill="url(#iwDR1wV)" class="d0ocvmu4d"/><path fill="url(#i1L7Mpd)" class="d0ocvmu4d"/><g filter="url(#iFQi3Ec)"><path fill="url(#i6XAUBd)" class="d60lbkuym"/></g><g filter="url(#ilCirrd)"><path fill="url(#iLOUAXd)" class="wx6gjqipl"/></g><path fill="url(#iHd26xe)" class="wx6gjqipl"/><path fill="url(#i1wfFqd)" class="wx6gjqipl"/><path fill="url(#ixvOk5d)" class="wx6gjqipl"/><g filter="url(#iP2Dsje)"><path class="bq80azb_e"/></g><g filter="url(#iyP6N8d)"><circle class="mvlg1lb-a"/></g><g filter="url(#i7RvtEb)"><circle class="tao08pzef"/></g><g filter="url(#iKXHP9d)"><circle fill="url(#iGv238b)" class="qsy44ybab"/></g><g filter="url(#iScwVmd)"><circle fill="url(#iUdTZPc)" class="zgcak206m"/></g><rect fill="url(#i8kOvub)" class="otslbtbht"/><rect fill="url(#i8O71Zd)" class="otslbtbht"/><rect fill="url(#i2qYNXd)" class="otslbtbht"/><rect fill="url(#if3NOAe)" class="otslbtbht"/><g filter="url(#i4EpBtF)"><path fill="url(#i7lfzIe)" class="o-ok2ibcd"/></g><path fill="url(#iBWIq2c)" class="o-ok2ibcd"/><g filter="url(#iX06XHV)"><path class="ku2lh6uuy"/><path fill="url(#isKdouB)" class="pbpjm1bhy"/><path fill="url(#iXYh5ub)" class="pbpjm1bhy"/><path fill="url(#ipN7wmd)" class="pbpjm1bhy"/></g><g filter="url(#irXXcyb)"><circle fill="url(#icPlPbd)" class="wui8nqfgb"/><circle fill="url(#iAsT4et)" class="wui8nqfgb"/></g><path fill="url(#iigPUwc)" class="lmkyvq38o"/><path fill="url(#iiIRDCc)" class="dc_z0_bxw"/><g filter="url(#iHU8m4b)"><path fill="url(#iVWQegQ)" class="jrtmrs0np"/></g><g filter="url(#iFZYs4T)"><path fill="url(#izBA3qd)" class="houfji2bh"/><path fill="url(#icv5kQb)" class="houfji2bh"/></g><g filter="url(#ilUxuOZ)"><path class="rh5eacc3r"/><path fill="url(#iOWqIrd)" class="x7qb6jv9m"/></g><g filter="url(#ideUMEe)"><path class="oy1dmeb0c"/><path fill="url(#iqa03kj)" class="tmzj3tblv"/></g><g filter="url(#iUrGYsb)"><path fill="url(#i4A6Ize)" class="s76wahyla"/><path fill="url(#ioODhjc)" class="s76wahyla"/><path fill="url(#ik4LgUb)" class="s76wahyla"/><path fill="url(#iRHIJke)" class="s76wahyla"/><path fill="url(#ia0iEye)" class="s76wahyla"/><path fill="url(#iS7iaHe)" class="s76wahyla"/><path fill="url(#iEP1iBd)" class="s76wahyla"/></g><path fill="url(#iY9lOyd)" class="s76wahyla"/><path fill="url(#ipveiTc)" class="s76wahyla"/><g filter="url(#iZO98fc)"><path class="seofz017v"/></g><g filter="url(#itB1RUd)"><path class="jpuvv5kcj"/><path fill="url(#iMmCjWq)" class="kzfo1kqfu"/><path fill="url(#iUE8GQd)" class="kzfo1kqfu"/><path fill="url(#iUwWLtb)" class="kzfo1kqfu"/><path fill="url(#iGFkxtc)" class="kzfo1kqfu"/></g><g filter="url(#iSb6kfe)"><path stroke="url(#iNgFXrb)" class="jt2yl9bzh"/></g><path class="ji0_rxb0x"/><g filter="url(#imi12ie)"><path class="ewuajhwfa"/></g><g filter="url(#iuDso5d)"><path class="kbgv6mydd"/></g><g filter="url(#iwqEIke)"><path class="ei1xh1g7h"/></g><g filter="url(#iCAtR2c)"><path clip-rule="evenodd" class="lc_expbnn"/></g><path class="a5vl8k3fo"/><path fill="url(#icRIRud)" class="pee7z8bbo"/><path class="ms13w9b-h"/><g filter="url(#iNrhb5b)"><path class="nd3ot0mac"/><path fill="url(#iyVP5Gb)" class="k-1cipnwc"/></g><g filter="url(#izSzqRc)"><path fill="url(#ihk4Q0b)" class="pxehlrooi"/></g><path class="saasnfb9u"/><path fill="url(#iZqUeob)" class="acv0-54tn"/><path class="ja60d45nf"/><g filter="url(#i3VWhcd)"><path fill="url(#ic0v1Vc)" class="xzv69vbgz"/></g><g filter="url(#iQHzC5P)"><ellipse transform="rotate(-27.914 13.594 9.862)" class="v_27a5b7h"/><ellipse fill="url(#i88IAcd)" transform="rotate(-27.914 13.594 9.862)" class="sa32mmbla"/></g><g filter="url(#iMUVoei)"><path class="bgsvhgb7w"/></g><g filter="url(#ijEAjeh)"><path class="h37jikbqa"/></g><g filter="url(#i3cyWXd)"><path class="fyrp3_zin"/><path fill="url(#iPt9rkc)" class="v54e1qjta"/></g><g filter="url(#ieOZwie)"><path class="ti8ohw8wk"/><path fill="url(#ipfIo9c)" class="pi6jtfb-k"/><path fill="url(#iXETu0d)" class="pi6jtfb-k"/></g><g filter="url(#ivxlqjc)"><path stroke="url(#imjcKKb)" class="eprq_uh3q"/></g><g filter="url(#iIvU7tW)"><path class="xfwhq5b-f"/></g><defs><radialGradient id="ivUjGMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.746 13.056)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iddHdqd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.93 13.324)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i8KLqmd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.94 8.157)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iDsYvDc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.375 7.643)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ijuvWbA" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 12.528 2.496)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iRnncZX" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.993 6.82)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iqYw9dc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 23.557 9.704)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iLFNFyd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.669 7.974)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iPdxsxp" cx="0" cy="0" r="1" gradientTransform="matrix(-.90444 -2.65026 2.0962 -.71536 20.78 7.27)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iBH0pxW" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.906 9.668)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iOTSjsd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.376)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="iVt7Kmd" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.756 10.843)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="ijJWFGd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.287)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iGY3pLe" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.271 2.64)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iOmSTFf" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.187)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="iHafYHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.443)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="iosNevc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.599)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="i0qUINb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.568)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iDSTCFe" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.33 13.055)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="iulJYbe" cx="0" cy="0" r="1" gradientTransform="rotate(-148.052 10.537 8.072)scale(1.21384 4.09383)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="i4qDnic" cx="0" cy="0" r="1" gradientTransform="matrix(.7959 -.2721 .77398 2.26394 13.24 18.359)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="ivP7kqb" cx="0" cy="0" r="1" gradientTransform="rotate(16.487 -55.161 68.502)scale(1.44847 6.30545)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iwDR1wV" cx="0" cy="0" r="1" gradientTransform="matrix(-.2731 .4204 -1.76025 -1.14347 17.274 19.237)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="iLOUAXd" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.073 11.886)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="iHd26xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91837 1.77673 -4.30254 -2.22394 13.135 16.373)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="i1wfFqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.92462 -.4885 0 11.747 16.43)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="ixvOk5d" cx="0" cy="0" r="1" gradientTransform="rotate(86.901 -5.602 15.98)scale(1.69986 .36274)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iGv238b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.862 16.074)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iUdTZPc" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.48 14.57)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="i8O71Zd" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.54688 1.51805 2.0819 14.212 18.122)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="nq0eho54j"/><stop offset="1" class="yw6diibio"/></radialGradient><radialGradient id="i2qYNXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.74927 .5625 -.2661 -1.30057 15.93 15.992)" gradientUnits="userSpaceOnUse"><stop offset=".389" class="f-gtf3b7m"/><stop offset="1" class="vuyutg00f"/></radialGradient><radialGradient id="if3NOAe" cx="0" cy="0" r="1" gradientTransform="matrix(2.82813 .30688 -.49369 4.54966 15.414 17.34)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="k-nm5qbub"/><stop offset="1" class="i89zb5bnw"/></radialGradient><radialGradient id="i7lfzIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.79)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iBWIq2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.166)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="iXYh5ub" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.448 6.885)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="ipN7wmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 19.021)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="icPlPbd" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.362 12.614)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iAsT4et" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.38)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="izBA3qd" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 23.196 -17.263)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="icv5kQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 21.118 8.874)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iOWqIrd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.439 10.668)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iqa03kj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.447 10.555)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="i4A6Ize" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 18.907 10.018)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="ioODhjc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.3 11.38)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="ik4LgUb" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.667 17.347)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iRHIJke" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -9.85659 0 16.047 9.8)" gradientUnits="userSpaceOnUse"><stop offset=".692" class="p1yzgib1u"/><stop offset=".966" class="iowfurbbi"/></radialGradient><radialGradient id="ia0iEye" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.358 6.742)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iS7iaHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.349 9.6)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iEP1iBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.971 9.37)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="iY9lOyd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.143 11.087)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="ipveiTc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 13.863 4.02)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iMmCjWq" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.832 11.813)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iGFkxtc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.592 12.025)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="icRIRud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.23 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iyVP5Gb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.001 10.042)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZqUeob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.865 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i88IAcd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.8 -1.596)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPt9rkc" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.3 -4.174)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ipfIo9c" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.152 6.96)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iXETu0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 16.258 3)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iFGOkwe" width="15.268" height="15.768" x="8.538" y="1.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="i6Ls2Cd" width="4.081" height="11.683" x="5.07" y="18.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="iixJzAe" width="5.909" height="14.117" x="12.858" y="15.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="iNeD8td" width="7.13" height="5.229" x="12.285" y="16.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".3"/></filter><filter id="iFQi3Ec" width="7.239" height="14.645" x="9.195" y="15.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".5"/></filter><filter id="ilCirrd" width="5.917" height="14.259" x="10.326" y="15.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3336" result="effect2_innerShadow_4002_3336"/></filter><filter id="iP2Dsje" width="6.567" height="14.209" x="15.297" y="15.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3336" result="effect2_innerShadow_4002_3336"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3336" result="effect3_innerShadow_4002_3336"/></filter><filter id="iyP6N8d" width="2" height="2" x="14.731" y="24.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".25"/></filter><filter id="i7RvtEb" width="2" height="2" x="14.731" y="21.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".25"/></filter><filter id="iKXHP9d" width="1.05" height="1.05" x="15.504" y="25.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="iScwVmd" width="1.05" height="1.05" x="15.504" y="22.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="i4EpBtF" width="2.465" height="2.95" x="16.029" y="17.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3336" result="effect2_innerShadow_4002_3336"/></filter><filter id="iX06XHV" width="2.365" height="2.9" x="13.731" y="17.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="irXXcyb" width="1.717" height="1.717" x="15.204" y="17.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="iHU8m4b" width="3.368" height="3.218" x="9.753" y="8.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="iFZYs4T" width="3.218" height="3.468" x="19.266" y="8.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="ilUxuOZ" width="3.148" height="3.148" x="19.301" y="8.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".25"/></filter><filter id="ideUMEe" width="2.948" height="2.948" x="9.907" y="9.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".2"/></filter><filter id="iUrGYsb" width="10.191" height="11.277" x="10.952" y="5.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="iZO98fc" width="2.877" height="3.682" x="14.447" y="9.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".25"/></filter><filter id="itB1RUd" width="2.377" height="3.182" x="14.859" y="9.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".125"/></filter><filter id="iSb6kfe" width="3.702" height="1.526" x="14.196" y="12.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".05"/></filter><filter id="imi12ie" width="3.001" height="1.285" x="16.99" y="9.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="iuDso5d" width="3.001" height="1.285" x="12.104" y="9.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="iwqEIke" width="2.453" height="1.091" x="12.239" y="7.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="iCAtR2c" width="2.453" height="1.091" x="17.657" y="7.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/></filter><filter id="iNrhb5b" width=".787" height=".696" x="17.495" y="9.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".05"/></filter><filter id="izSzqRc" width=".891" height=".913" x="18.335" y="9.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".1"/></filter><filter id="i3VWhcd" width=".986" height="1.04" x="13.892" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".1"/></filter><filter id="iQHzC5P" width=".913" height=".705" x="13.138" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".05"/></filter><filter id="iMUVoei" width="2.261" height=".978" x="17.687" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".1"/></filter><filter id="ijEAjeh" width="2.261" height=".978" x="12.235" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".1"/></filter><filter id="i3cyWXd" width="4.212" height="4.513" x="9.793" y="3.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/><feGaussianBlur result="effect2_foregroundBlur_4002_3336" stdDeviation=".15"/></filter><filter id="ieOZwie" width="8.767" height="5.782" x="12.877" y="2.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3336"/><feGaussianBlur result="effect2_foregroundBlur_4002_3336" stdDeviation=".125"/></filter><filter id="ivxlqjc" width="1.145" height="2.31" x="12.856" y="3.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".1"/></filter><filter id="iIvU7tW" width="6.427" height="3.372" x="15.466" y="4.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3336" stdDeviation=".375"/></filter><linearGradient id="iAO6TiE" x1="20.741" x2="13.936" y1="3.603" y2="16.207" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iuyr1tn" x1="23.131" x2="22.971" y1="29.966" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iwTkvTT" x1="8.858" x2="9.061" y1="29.966" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="irRAuOe" x1="9.19" x2="7.596" y1="29.973" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="iQD9ace" x1="14.707" x2="12.794" y1="19.947" y2="16.473" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="ig0Fqhd" x1="15.518" x2="15.198" y1="20.04" y2="19.939" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="i3hbZ4w" x1="16.798" x2="18.955" y1="19.966" y2="16.867" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="i1L7Mpd" x1="16.486" x2="16.722" y1="19.727" y2="19.649" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="i6XAUBd" x1="12.815" x2="12.815" y1="16.834" y2="29.479" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="i8kOvub" x1="17.493" x2="14.351" y1="18.58" y2="18.199" gradientUnits="userSpaceOnUse"><stop class="zuarvyx2f"/><stop offset="1" class="wui2c9bqc"/></linearGradient><linearGradient id="isKdouB" x1="15.205" x2="14.838" y1="19.49" y2="19.037" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="iigPUwc" x1="8.894" x2="23.27" y1="15.419" y2="15.419" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iiIRDCc" x1="8.894" x2="23.27" y1="15.389" y2="15.389" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iVWQegQ" x1="9.753" x2="12.712" y1="10.642" y2="10.642" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iUE8GQd" x1="15.109" x2="16.047" y1="11.886" y2="11.886" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iUwWLtb" x1="16.047" x2="16.047" y1="12.685" y2="12.075" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iNgFXrb" x1="14.983" x2="15.444" y1="14.095" y2="13.383" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="ihk4Q0b" x1="19.008" x2="18.694" y1="10.012" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ic0v1Vc" x1="14.609" x2="14.296" y1="10.012" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imjcKKb" x1="13.156" x2="13.701" y1="4.357" y2="5.63" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-tuxedo-light" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.a5vl8k3fo {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.439 9.21c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.acv0-54tn {
  d: path("M13.863 9.481a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bgsvhgb7w {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.987 8.183c.323-.079 1.125-.04 1.66.344");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bq80azb_e {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.332 17.603c0-1.277-.933-1.774-1.555-1.617v5.737c0 3.873-1.452 6.261-2.711 8.087c-.063.091.047.2.138.138c2.976-2.036 4.915-4.003 5.26-9.226a.203.203 0 0 0-.188-.215c-.321-.02-.606-.047-.809-.066a.204.204 0 0 1-.185-.206c.011-.575.023-1.659.05-2.632");
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bv6krxq7x {
  fill-rule: evenodd;
  d: path("M23.233 11.965a3.25 3.25 0 0 0 .324-1.427c0-.467-.097-.906-.269-1.305h.005a3 3 0 0 0-.28-.513l-.003-.004a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.681 1.376a.56.56 0 0 1-.456.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.581a3.213 3.213 0 0 0 2.895-4.625a.52.52 0 0 1 0-.455m-12.26-2.672h-.013l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.46.051l-.083.194a2.3 2.3 0 0 1-1.24 1.255q-.027.012-.052.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.bv7-wxb3q {
  d: path("M8.901 18.29a10.68 10.68 0 0 0-3.831 8.18v3.496H8.9z");
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d0ocvmu4d {
  d: path("M17.598 20.338c1.186-1.235 1.368-4.254 1.368-4.254c-.681-.36-1.548-.406-1.548-.406l-1.421.789l-.036 2.222l.774 1.52c.148.308.608.394.863.129");
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d60lbkuym {
  d: path("M11.242 18.4c-.03-1.01.55-1.42.819-1.501l.617-.065v5.372c0 3.575.239 4.663 2.733 7.12l.011.016c.047.082-.05.176-.132.12c-2.75-1.881-4.776-3.355-5.094-8.18a.19.19 0 0 1 .174-.198c.297-.02.56-.044.747-.061a.19.19 0 0 0 .171-.191c-.01-.531-.02-1.533-.046-2.431");
}

.dc_z0_bxw {
  d: path("M16.104 15.39h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.ei1xh1g7h {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.65 8.777l-.005.003a.268.268 0 0 1-.275-.46l.001-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.329-.11a.268.268 0 1 1-.094.53a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.455.193");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.eprq_uh3q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.156 4.013c.024.243.235 1.156.545 1.71");
}

.ewuajhwfa {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.19 9.986c.265-.467.668-.835 1.537-.835c.38 0 .747.105 1.073.368c.269.218.233.495.024.6l-.556.317c-.652-.21-1.372-.24-2.078-.45");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f-gtf3b7m {
  stop-color: var(--svg-color--c18488, #C18488);
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fyrp3_zin {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.978 4.567c.566-.6 1.637-.6 2.131-.51l.396 1.29c-.253-.04-.478.05-.668.234c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.11-2.38.845-3.16");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h37jikbqa {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.196 8.183c-.322-.079-1.124-.04-1.66.344");
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.houfji2bh {
  d: path("M20.875 12.164a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i89zb5bnw {
  stop-color: var(--svg-color--dfb3a8, #DFB3A8);
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iowfurbbi {
  stop-color: var(--svg-color--bc7e89, #BC7E89);
}

.iwijhb8cc {
  d: path("M5.07 26.47c0-5.796 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.824 10.5 10.62v3.496H5.07z");
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.ja60d45nf {
  fill: var(--svg-color--000, #000);
  d: path("M14.375 10.373a.51.51 0 0 0-.512-.51a.51.51 0 0 0-.454.745h.905a.5.5 0 0 0 .06-.235");
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.ji0_rxb0x {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.048 13.467c-.521 0-1.01-.126-1.422-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jpuvv5kcj {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.665 10.194l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.jrtmrs0np {
  d: path("M11.362 12.164a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.jt2yl9bzh {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.048 13.467c-.521 0-1.01-.126-1.422-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345Z");
}

.k-1cipnwc {
  d: path("M18.166 9.67c.064.084-.07.188-.22.301c-.152.113-.264.193-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.k-nm5qbub {
  stop-color: var(--svg-color--dfb3a8, #DFB3A8);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.kbgv6mydd {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.906 9.986c-.266-.467-.67-.835-1.538-.835c-.38 0-.747.105-1.072.368c-.27.218-.233.495-.025.6l.556.317c.652-.21 1.373-.24 2.079-.45");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ku2lh6uuy {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.535l1.813 1.252l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.kzfo1kqfu {
  d: path("m15.665 10.194l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lc_expbnn {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.779 8.32l-.138.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.989 0 1.328.11a3.3 3.3 0 0 1 .559.238l.01.005l.002.002z");
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lmkyvq38o {
  d: path("M16.434 15.39c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.ms13w9b-h {
  fill: var(--svg-color--000, #000);
  d: path("M17.72 10.373c0-.284.228-.51.512-.51a.51.51 0 0 1 .454.745h-.905a.46.46 0 0 1-.06-.235");
}

.mvlg1lb-a {
  cx: 15.731px;
  cy: 25.909px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.nd3ot0mac {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.166 9.67c.064.084-.07.188-.22.301c-.152.113-.264.193-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nq0eho54j {
  stop-color: var(--svg-color--c79088, #C79088);
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.nzd5pi4db {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.741c-.037.825.18 2.636 1.367 3.871c.255.266.715.18.863-.129l.73-1.435l.731 1.435c.149.309.608.395.863.13c1.186-1.236 1.404-3.047 1.368-3.872z");
}

.o-ok2ibcd {
  d: path("m17.892 17.535l-1.813 1.252l1.795 1.258a.246.246 0 0 0 .388-.187c.041-.791.041-1.57.008-2.144a.239.239 0 0 0-.378-.179");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.otslbtbht {
  width: 3.875px;
  height: 6.133px;
  x: 13.993px;
  y: 12.783px;
  rx: 1.938px;
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.oy1dmeb0c {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.381 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.p1yzgib1u {
  stop-color: var(--svg-color--cb9193, #CB9193);
  stop-opacity: 0;
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pbpjm1bhy {
  d: path("m14.133 17.535l1.813 1.252l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.pee7z8bbo {
  d: path("M18.232 9.481a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.pi6jtfb-k {
  d: path("M15.444 2.764c-1.133-.25-2.15.88-2.267 1.3c1.052 3.545 3.713 3.35 6.34 3.058c1.573-.174 1.743.542 1.877.889c0-3.933-3.344-4.671-5.921-5.24z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.pwzf73bct {
  d: path("M14.41 20.338c-1.185-1.235-1.367-4.254-1.367-4.254c.681-.36 1.548-.406 1.548-.406l1.421.789l.035 2.222l-.773 1.52c-.148.308-.608.394-.863.129");
}

.pxehlrooi {
  d: path("M19.027 10.256a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qsy44ybab {
  cx: 16.004px;
  cy: 25.636px;
  r: 0.5px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.rh5eacc3r {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.875 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s76wahyla {
  d: path("M10.96 9.292h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439l.051-.02q.027-.012.052-.02a2.3 2.3 0 0 0 1.19-1.235l.081-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.189 1.672h3.22c.18 0 1.082.088 1.136 1.333l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.sa32mmbla {
  cx: 13.594px;
  cy: 9.862px;
  rx: 0.39px;
  ry: 0.197px;
}

.saasnfb9u {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.657 9.21c-.654 0-1.205.45-1.355 1.058a.273.273 0 0 0 .267.34H14.8a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.seofz017v {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.655 10.333l-.684 1.7a.54.54 0 0 0 .521.699h.786a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.376-.493-.376-.612 0");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.tao08pzef {
  cx: 15.731px;
  cy: 22.761px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.ti8ohw8wk {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.444 2.764c-1.133-.25-2.15.88-2.267 1.3c1.052 3.545 3.713 3.35 6.34 3.058c1.573-.174 1.743.542 1.877.889c0-3.933-3.344-4.671-5.921-5.24z");
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tmzj3tblv {
  d: path("M11.381 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.uoh3u9bsv {
  d: path("M8.901 18.29a10.69 10.69 0 0 0-3.831 8.185v3.498H8.9z");
}

.v_27a5b7h {
  cx: 13.594px;
  cy: 9.862px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v54e1qjta {
  d: path("M10.978 4.567c.566-.6 1.637-.6 2.131-.51l.396 1.29c-.253-.04-.478.05-.668.234c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.11-2.38.845-3.16");
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vuyutg00f {
  stop-color: var(--svg-color--c18488, #C18488);
  stop-opacity: 0;
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wsuqc2bol {
  d: path("M18.767 16.117a10.3 10.3 0 0 0-2.337-.267h-.86a10.3 10.3 0 0 0-2.312.261v5.423c0 4.175 1.065 5.971 2.654 8.432h.285c1.59-2.46 2.57-4.257 2.57-8.432z");
}

.wui2c9bqc {
  stop-color: var(--svg-color--c58a85, #C58A85);
}

.wui8nqfgb {
  cx: 16.012px;
  cy: 18.756px;
  r: 0.809px;
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.wx6gjqipl {
  d: path("M11.709 17.603c0-1.277.933-1.774 1.554-1.617v5.737c0 3.873 1.453 6.261 2.712 8.087c.063.091-.047.2-.138.138c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.206c-.011-.575-.023-1.659-.05-2.632");
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x7qb6jv9m {
  d: path("M20.875 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfwhq5b-f {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.454 6.374l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.899 1.872a3.15 3.15 0 0 0-2.69-.769");
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xzv69vbgz {
  d: path("M14.679 10.269c0-.289-.235-.481-.298-.54l-.289.28l.178.36z");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yw6diibio {
  stop-color: var(--svg-color--c79088, #C79088);
  stop-opacity: 0;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z77pc-39f {
  d: path("M23.099 18.29a10.68 10.68 0 0 1 3.831 8.18v3.496H23.1z");
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.zgcak206m {
  cx: 16.004px;
  cy: 22.628px;
  r: 0.5px;
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zuarvyx2f {
  stop-color: var(--svg-color--d59f9b, #D59F9B);
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

</style>
