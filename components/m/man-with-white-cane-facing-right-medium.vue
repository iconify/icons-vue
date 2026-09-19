<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVczLdC)"><path clip-rule="evenodd" class="wbet_dbvt"/><path fill="url(#iKuiyrf)" clip-rule="evenodd" class="j92jtbb2k"/><path fill="url(#ipBsZQd)" clip-rule="evenodd" class="j92jtbb2k"/></g><path class="mvw8vhw3e"/><g filter="url(#innvwRc)"><path stroke="url(#ipIbL7d)" class="lufyf2brv"/></g><g filter="url(#i8BjkSd)"><path fill="url(#iUFgF8U)" clip-rule="evenodd" class="vwf3bac9u"/></g><path fill="url(#idWr8ge)" class="atwsljbqf"/><path fill="url(#iwnPkIc)" class="atwsljbqf"/><g filter="url(#iclJABM)"><circle fill="url(#iUctc4d)" transform="matrix(-1 0 0 1 28.424 28.227)" class="ghq9gsa-q"/><circle fill="url(#iETpATd)" transform="matrix(-1 0 0 1 28.424 28.227)" class="ghq9gsa-q"/><circle fill="url(#iPmd0rd)" transform="matrix(-1 0 0 1 28.424 28.227)" class="ghq9gsa-q"/></g><g filter="url(#ii6p63c)"><path fill="url(#ilL6Tbe)" class="vi11a8djh"/><path fill="url(#iJ0Krse)" class="vi11a8djh"/></g><g filter="url(#iRpfw0c)"><rect transform="scale(-1 1)rotate(-7.657 106.615 156.548)" class="lqtvazhgp"/></g><path fill="url(#iZ4WEvc)" class="ov-p8go0b"/><path fill="url(#ieTuutc)" transform="scale(-1 1)rotate(-4.337 81.567 185.245)" class="z8jy9-b3h"/><path fill="url(#iMY10ed)" transform="scale(-1 1)rotate(-4.337 81.567 185.245)" class="z8jy9-b3h"/><path fill="url(#idpQOIe)" transform="scale(-1 1)rotate(-4.337 81.567 185.245)" class="z8jy9-b3h"/><path fill="url(#idfdkhc)" class="jea1nljqt"/><path fill="url(#iQ8nZzd)" class="jea1nljqt"/><g filter="url(#iL05APd)"><path fill="url(#iicG1mc)" class="h8x7joblq"/><path fill="url(#iiMK9xe)" class="h8x7joblq"/><path fill="url(#iIX5Cdc)" class="h8x7joblq"/><path fill="url(#i1wDbUb)" class="h8x7joblq"/></g><g filter="url(#izhDzsF)"><path fill="url(#i7votqc)" class="qqm4th_px"/><path fill="url(#inPVvJr)" class="qqm4th_px"/><path fill="url(#iygqFje)" class="qqm4th_px"/></g><path fill="url(#iOyrVDF)" class="dipyuzbpy"/><path fill="url(#i2uGWCe)" class="dipyuzbpy"/><path fill="url(#ikMCxvb)" class="dipyuzbpy"/><g filter="url(#iG7jqPe)"><path fill="url(#ip2Hjkc)" class="snyu1wb4r"/><path fill="url(#isFWonG)" class="snyu1wb4r"/><path fill="url(#icdRTOd)" class="snyu1wb4r"/></g><g filter="url(#idOMuBJ)"><path class="vxqcofbqp"/><path fill="url(#iJpqzmW)" class="ish_ajbgy"/><path fill="url(#iYhnnJd)" class="ish_ajbgy"/><path fill="url(#iNtnRje)" class="ish_ajbgy"/><path fill="url(#itOBcab)" class="ish_ajbgy"/><path fill="url(#iF5XwGb)" class="ish_ajbgy"/></g><path fill="url(#ix972wN)" class="a7ior2ecw"/><path fill="url(#ihtVHub)" class="a7ior2ecw"/><path fill="url(#iU4mdfe)" class="a7ior2ecw"/><path fill="url(#iKcxXOe)" class="a7ior2ecw"/><path fill="url(#iofn4te)" class="a7ior2ecw"/><path class="lf9s3z4la"/><path fill="url(#iX2pOde)" class="fyvbkb8db"/><path fill="url(#iLUR7MC)" class="fyvbkb8db"/><path fill="url(#i95mKlc)" class="fyvbkb8db"/><path class="r9il63bci"/><path fill="url(#iEAmlqe)" class="a89_v_bcc"/><path fill="url(#iE3RZYd)" class="a89_v_bcc"/><path fill="url(#ieGYpvb)" class="a89_v_bcc"/><path fill="url(#iNWExSb)" class="a89_v_bcc"/><path fill="url(#i4nICib)" class="a89_v_bcc"/><circle fill="url(#iO9G6Yb)" transform="matrix(-1 0 0 1 7.412 17.433)" class="am9uocbqt"/><g filter="url(#ixcLLsc)"><path class="dl278mblr"/></g><g filter="url(#iK6i9os)"><path clip-rule="evenodd" class="berzq5wwi"/></g><g filter="url(#i3CtsNc)"><path class="rs-uzvy4c"/></g><g filter="url(#iZ7iNae)"><path fill="url(#ipD5Oqb)" class="thq9kiblh"/><path fill="url(#i07lyzq)" class="thq9kiblh"/><path fill="url(#ibE8WVd)" class="thq9kiblh"/></g><path fill="url(#iiCRQBc)" class="thq9kiblh"/><path clip-rule="evenodd" class="h2vf1mt3g"/><path class="cxrv1-b5b"/><path fill="url(#iEyXTmd)" class="bmg6367-m"/><path fill="url(#imoZfrd)" class="y9d6-sb7h"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -19.503 -32.822)" class="m1l7k9jve"/><g filter="url(#imRFAwd)"><path fill="url(#iU69EDb)" class="nvzddhbxg"/></g><g filter="url(#ivin02b)"><path fill="url(#iXbCm5b)" class="k-u87vbol"/></g><g filter="url(#i0TRJVd)"><path clip-rule="evenodd" class="r5xnzcbol"/></g><defs><radialGradient id="iKuiyrf" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 2.75 -.60904 .51907 15.498 12.5)" gradientUnits="userSpaceOnUse"><stop class="dl48aepdi"/><stop offset="1" class="pr310ga5h"/></radialGradient><radialGradient id="ipBsZQd" cx="0" cy="0" r="1" gradientTransform="rotate(176.424 9.307 8.44)scale(1.50293 1.62478)" gradientUnits="userSpaceOnUse"><stop class="ql4avvisg"/><stop offset="1" class="k5q572hpz"/></radialGradient><radialGradient id="iUctc4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.57031 -1.46069 0 .84 .234)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="ygdc80fko"/><stop offset="1" class="a5_lx-bnb"/></radialGradient><radialGradient id="iETpATd" cx="0" cy="0" r="1" gradientTransform="rotate(-14.821 2.856 -4.348)scale(.48867)" gradientUnits="userSpaceOnUse"><stop class="tl0sw7mkk"/><stop offset="1" class="xu259ab4x"/></radialGradient><radialGradient id="iPmd0rd" cx="0" cy="0" r="1" gradientTransform="matrix(.50415 0 0 .66877 0 .727)" gradientUnits="userSpaceOnUse"><stop class="hyb__5ivb"/><stop offset="1" class="wfraawh3t"/></radialGradient><radialGradient id="ieTuutc" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 1.708 2.01)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="cxkrfuqzt"/><stop offset="1" class="g_3zxnbav"/></radialGradient><radialGradient id="iMY10ed" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 2.062 .438)" gradientUnits="userSpaceOnUse"><stop class="zz_g2hbek"/><stop offset="1" class="qnz-ctb1c"/></radialGradient><radialGradient id="idpQOIe" cx="0" cy="0" r="1" gradientTransform="matrix(.01105 -.86884 .23985 .00305 .214 2.413)" gradientUnits="userSpaceOnUse"><stop class="ty0uj7bex"/><stop offset="1" class="n3m07owib"/></radialGradient><radialGradient id="idfdkhc" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 7.521 5.206)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="iQ8nZzd" cx="0" cy="0" r="1" gradientTransform="matrix(.12006 -.29152 .4375 .18019 16.208 6.524)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="iiMK9xe" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 12.951 5.503)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="iIX5Cdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 15.848 6.69)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="i1wDbUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 15.02 5.55)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="i7votqc" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 3.125 -3.54355 3.8979 11.076 2.841)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="i2p5fqtly"/><stop offset="1" class="pw8a02b5q"/></radialGradient><radialGradient id="inPVvJr" cx="0" cy="0" r="1" gradientTransform="matrix(-.39452 2.68273 -1.18513 -.17428 11.183 3.59)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="ltxof3fvo"/><stop offset="1" class="nj0viubvx"/></radialGradient><radialGradient id="iygqFje" cx="0" cy="0" r="1" gradientTransform="rotate(-176.424 8.24 1.473)scale(1.50293 2.94932)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="id9lp4hub"/><stop offset="1" class="fed4ggbgk"/></radialGradient><radialGradient id="iOyrVDF" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 6.97 1.756)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="i2uGWCe" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 4.47 7.976)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="isFWonG" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45369 2.93958 -5.96661 -4.98038 10.838 17.98)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="icdRTOd" cx="0" cy="0" r="1" gradientTransform="rotate(143.616 2.456 11.33)scale(1.10629 6.64432)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="iJpqzmW" cx="0" cy="0" r="1" gradientTransform="rotate(-122.302 11.708 7.132)scale(6.08182 1.60193)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="iYhnnJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 11.123 16.136)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="itOBcab" cx="0" cy="0" r="1" gradientTransform="matrix(-.14062 -.17969 .6458 -.50541 15.819 28.05)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="iF5XwGb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 -1.81248 4.6745 -16.4415 15.498 19.183)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="ix972wN" cx="0" cy="0" r="1" gradientTransform="matrix(.09374 -1.53125 2.45635 .15037 16.952 29.401)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="ihtVHub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -.21876 .15137 -.73521 20.06 28.464)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="iU4mdfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.59376 -1.71875 .84778 -.29287 16.045 29.698)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="i95mKlc" cx="0" cy="0" r="1" gradientTransform="rotate(-47.125 33 9.042)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="iEAmlqe" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -.54688 .76306 2.18017 11.92 9.67)" gradientUnits="userSpaceOnUse"><stop offset=".266" class="anxjqssms"/><stop offset="1" class="p0binz11r"/></radialGradient><radialGradient id="iE3RZYd" cx="0" cy="0" r="1" gradientTransform="rotate(-88.915 13.836 2.347)scale(4.95211 1.34022)" gradientUnits="userSpaceOnUse"><stop class="ba65pd9sy"/><stop offset="1" class="c0n24ybhp"/></radialGradient><radialGradient id="ieGYpvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65186 0 0 -15.6875 13.103 14.247)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="l7vpqwwuy"/><stop offset="1" class="r5z1pjbbo"/></radialGradient><radialGradient id="iNWExSb" cx="0" cy="0" r="1" gradientTransform="matrix(4.78125 .78125 -1.79108 10.96143 9.728 15.06)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="gxh5rg5pu"/><stop offset=".931" class="x45bnccdq"/></radialGradient><radialGradient id="iO9G6Yb" cx="0" cy="0" r="1" gradientTransform="rotate(90 .008 .406)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="h40q0rjti"/><stop offset="1" class="knd8fccgb"/></radialGradient><radialGradient id="i07lyzq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0907 .20313 -.4206 -2.25834 12.912 10.294)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="c7e6m9b-c"/><stop offset="1" class="kqn0y5w2b"/></radialGradient><radialGradient id="ibE8WVd" cx="0" cy="0" r="1" gradientTransform="matrix(2.15627 -2.31248 .88731 .82738 8.826 11.638)" gradientUnits="userSpaceOnUse"><stop class="mpu3do46a"/><stop offset="1" class="ftb4gxmwr"/></radialGradient><radialGradient id="iiCRQBc" cx="0" cy="0" r="1" gradientTransform="rotate(112.307 3.192 8.48)scale(1.23495 2.7533)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="jogzo_66p"/><stop offset="1" class="hir3rg47y"/></radialGradient><radialGradient id="iEyXTmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 15.315 5.577)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="imoZfrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 15.482 5.599)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="ipIbL7d" x1="17.709" x2="19.591" y1="15.523" y2="17.563" gradientUnits="userSpaceOnUse"><stop class="o52vxyscb"/><stop offset="1" class="u-867gbtx"/></linearGradient><linearGradient id="iUFgF8U" x1="23.154" x2="21.904" y1="21.813" y2="22.75" gradientUnits="userSpaceOnUse"><stop class="n6l6ilaec"/><stop offset="1" class="vjqn9lx3p"/></linearGradient><linearGradient id="idWr8ge" x1="26.818" x2="25.084" y1="28.656" y2="26.313" gradientUnits="userSpaceOnUse"><stop class="uug2ubxhk"/><stop offset="1" class="deyia0bkx"/></linearGradient><linearGradient id="iwnPkIc" x1="26.763" x2="26.405" y1="27.094" y2="27.344" gradientUnits="userSpaceOnUse"><stop class="p8mdyfi9b"/><stop offset="1" class="g6zbvk7ui"/></linearGradient><linearGradient id="ilL6Tbe" x1="18.294" x2="20.044" y1="16.359" y2="18.656" gradientUnits="userSpaceOnUse"><stop class="ly5_jc0cc"/><stop offset="1" class="sxo3xwbvl"/></linearGradient><linearGradient id="iJ0Krse" x1="18.185" x2="18.709" y1="16.422" y2="17.188" gradientUnits="userSpaceOnUse"><stop offset=".098" class="iykv72k7v"/><stop offset="1" class="qg5pcsysc"/></linearGradient><linearGradient id="iZ4WEvc" x1="14.533" x2="15.119" y1="12.833" y2="12.122" gradientUnits="userSpaceOnUse"><stop class="f8fpq6bgz"/><stop offset="1" class="w48m3830t"/></linearGradient><linearGradient id="iicG1mc" x1="13.264" x2="16.126" y1="6.245" y2="6.417" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="ikMCxvb" x1="13.231" x2="13.082" y1="5.455" y2="5.466" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="ip2Hjkc" x1="9.818" x2="7.59" y1="22.839" y2="20.896" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="iNtnRje" x1="12.045" x2="12.045" y1="16.027" y2="16.37" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="iKcxXOe" x1="17.514" x2="17.428" y1="29.573" y2="29.261" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iofn4te" x1="15.545" x2="16.123" y1="29.948" y2="29.73" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="iX2pOde" x1="6.936" x2="6.342" y1="27.933" y2="28.105" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="iLUR7MC" x1="4.811" x2="4.99" y1="28.007" y2="27.859" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="i4nICib" x1="11.733" x2="11.733" y1="16.169" y2="15.989" gradientUnits="userSpaceOnUse"><stop class="znpkhwbgq"/><stop offset="1" class="z629lk5yz"/></linearGradient><linearGradient id="ipD5Oqb" x1="11.061" x2="9.951" y1="9.073" y2="12.527" gradientUnits="userSpaceOnUse"><stop offset=".118" class="bds_ezblb"/><stop offset="1" class="y3zdm1aic"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iU69EDb" x1="15.717" x2="11.092" y1="27.37" y2="17.23" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="iXbCm5b" x1="5.573" x2="9.883" y1="25.279" y2="19.907" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="iVczLdC" width="7.179" height="6.928" x="12.731" y="10.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.305882 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/></filter><filter id="innvwRc" width="2.607" height="2.722" x="17.102" y="15.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3233" stdDeviation=".05"/></filter><filter id="i8BjkSd" width="8.674" height="11.796" x="19.184" y="17.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.647059 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/></filter><filter id="iclJABM" width="1.68" height="1.68" x="26.744" y="28.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.819608 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/></filter><filter id="ii6p63c" width="2.726" height="3.079" x="17.776" y="15.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.133333 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/></filter><filter id="iRpfw0c" width="1.093" height="1.661" x="18.764" y="15.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.427451 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/></filter><filter id="iL05APd" width="4.443" height="5.249" x="11.683" y="3.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.329412 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/></filter><filter id="izhDzsF" width="6.391" height="5.479" x="10.268" y="1.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.266667 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.137255 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3233" result="effect2_innerShadow_2_3233"/></filter><filter id="iG7jqPe" width="8.674" height="14.771" x="3.679" y="15.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3233" result="effect2_innerShadow_2_3233"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_2_3233" result="effect3_innerShadow_2_3233"/></filter><filter id="idOMuBJ" width="10.972" height="14.104" x="9.437" y="15.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/></filter><filter id="ixcLLsc" width="5.586" height="5.875" x="7.945" y="8.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3233" stdDeviation=".375"/></filter><filter id="iK6i9os" width="7.59" height="10.511" x="4.311" y="9.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.403922 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.6 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3233" result="effect2_innerShadow_2_3233"/></filter><filter id="i3CtsNc" width="6.084" height="9.069" x="4.72" y="9.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3233" stdDeviation=".3"/></filter><filter id="iZ7iNae" width="4.758" height="4.525" x="8.404" y="8.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.47451 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/></filter><filter id="imRFAwd" width="6.844" height="12.891" x="10.092" y="16.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3233" stdDeviation=".5"/></filter><filter id="ivin02b" width="6.45" height="8.475" x="4.537" y="17.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3233" stdDeviation=".375"/></filter><filter id="i0TRJVd" width="1.117" height=".649" x="14.406" y="4.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3233"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-white-cane-facing-right-medium" /></template>
<style>
.a5_lx-bnb {
  stop-color: var(--svg-color--ccaae9, #CCAAE9);
}

.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.a7ior2ecw {
  d: path("m15.197 28.577l.392 1.286a.25.25 0 0 0 .314.165l3.738-1.182c.194-.062.325-.266.244-.453c-.108-.244-.333-.499-.887-.656c-.59-.167-1.672-.261-2.306-.317l-.21-.019V27.4z");
}

.a89_v_bcc {
  d: path("M12.268 8.554c-.891 0-1.137.215-1.434.406l-1.023 2.598c-.3 1.4-.365 3.635-.36 4.578h4.747c.258-.656.696-2.675.535-4.578c-.165-1.93-1.208-2.902-2.465-3.004");
}

.am9uocbqt {
  cx: 0.551px;
  cy: 0.551px;
  r: 0.551px;
}

.anxjqssms {
  stop-color: var(--svg-color--3d98c9, #3D98C9);
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.atwsljbqf {
  d: path("m24.952 26.214l2.092 2.879a.45.45 0 1 0 .728-.53l-2.092-2.878z");
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.ba65pd9sy {
  stop-color: var(--svg-color--407bbe, #407BBE);
}

.bds_ezblb {
  stop-color: var(--svg-color--2e83d0, #2E83D0);
}

.berzq5wwi {
  fill: var(--svg-color--aa7974, #AA7974);
  fill-rule: evenodd;
  d: path("M5.955 19.18a.614.614 0 0 0 .776-.407c1.215-3.922 3.166-6.29 4.541-7.545c.438-.4.516-1.082.129-1.53c-.347-.402-.945-.473-1.349-.13c-1.626 1.38-3.91 3.976-5.316 8.605a.59.59 0 0 0 .383.729z");
}

.bmg6367-m {
  d: path("M14.987 5.599v-.004c0-.32.137-.58.306-.58c.17 0 .307.26.307.58v.004z");
}

.c0n24ybhp {
  stop-color: var(--svg-color--407bbe, #407BBE);
  stop-opacity: 0;
}

.c7e6m9b-c {
  stop-color: var(--svg-color--5696dc, #5696DC);
}

.ckhjb_bgt {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
}

.cl2mlwbhs {
  stop-color: var(--svg-color--4a4b75, #4A4B75);
}

.cnh3p8b3x {
  stop-color: var(--svg-color--817076, #817076);
  stop-opacity: 0;
}

.csaq2_bel {
  stop-color: var(--svg-color--444571, #444571);
  stop-opacity: 0;
}

.cxkrfuqzt {
  stop-color: var(--svg-color--ae907b, #AE907B);
}

.cxrv1-b5b {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.592 5.599h-.988c0-.392.22-.71.494-.71c.273 0 .494.318.494.71");
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.deyia0bkx {
  stop-color: var(--svg-color--f3386a, #F3386A);
}

.dipyuzbpy {
  d: path("m13.328 6.26l-.2-1.44a.727.727 0 0 0 .2 1.44");
}

.dl278mblr {
  fill: var(--svg-color--1049ac, #1049AC);
  d: path("M12.319 11.232c.31-.249.462-.639.462-1.067c0-.749-.185-1.16-.934-1.16a1.35 1.35 0 0 0-.882.327c-.951.691-1.79 1.591-2.27 2.134l2.039 1.914a347 347 0 0 0 1.585-2.148");
}

.dl48aepdi {
  stop-color: var(--svg-color--af8771, #AF8771);
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.ex23x-brg {
  stop-color: var(--svg-color--8c8388, #8C8388);
  stop-opacity: 0;
}

.ezcqmvbni {
  stop-color: var(--svg-color--443a80, #443A80);
}

.f3j6dkfip {
  stop-color: var(--svg-color--99919a, #99919A);
}

.f8fpq6bgz {
  stop-color: var(--svg-color--3981ca, #3981CA);
}

.fed4ggbgk {
  stop-color: var(--svg-color--634d4a, #634D4A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftb4gxmwr {
  stop-color: var(--svg-color--4d95e1, #4D95E1);
  stop-opacity: 0;
}

.fxoxl0blj {
  stop-color: var(--svg-color--8c8393, #8C8393);
  stop-opacity: 0;
}

.fyvbkb8db {
  d: path("m4.756 25.61l1.638.677l-.021.02q.046.157.107.356c.216.712.535 1.763.62 2.27c.077.462-.145.768-.351.952c-.094.084-.235.064-.318-.029l-2.688-2.995a.25.25 0 0 1 .019-.353l.986-.888z");
}

.g_3zxnbav {
  stop-color: var(--svg-color--967269, #967269);
}

.g24ahctiy {
  stop-color: var(--svg-color--94899e, #94899E);
  stop-opacity: 0;
}

.g6zbvk7ui {
  stop-color: var(--svg-color--f35886, #F35886);
  stop-opacity: 0;
}

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.ghq9gsa-q {
  cx: 0.84px;
  cy: 0.84px;
  r: 0.84px;
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gxh5rg5pu {
  stop-color: var(--svg-color--588fc4, #588FC4);
  stop-opacity: 0;
}

.h2vf1mt3g {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M14.846 6.713a.125.125 0 0 0 .002.176c.238.234.583.294.692.305a.125.125 0 1 0 .026-.249c-.094-.01-.367-.062-.543-.234a.125.125 0 0 0-.177.002");
}

.h40q0rjti {
  stop-color: var(--svg-color--a2726b, #A2726B);
}

.h8x7joblq {
  d: path("M16.098 4.805c-.038-.801-.298-1.187-.42-1.3h-3.732l-.063 3.163c.867 2.122 3.512 2.213 3.907 1.446s.353-2.381.308-3.31");
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hir3rg47y {
  stop-color: var(--svg-color--4080be, #4080BE);
  stop-opacity: 0;
}

.hyb__5ivb {
  stop-color: var(--svg-color--e4d4ea, #E4D4EA);
}

.i2p5fqtly {
  stop-color: var(--svg-color--52343b, #52343B);
}

.id9lp4hub {
  stop-color: var(--svg-color--634d4a, #634D4A);
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.ish_ajbgy {
  d: path("M14.975 18.519c-.383-1.051-.716-2.029-.774-2.383H9.46c-.1 1.375.144 1.712.774 2.422c.692.781 2.171 2.43 2.539 2.894c.35.35.5.79.554.98l2.263 7.431a.25.25 0 0 0 .314.166l3.738-1.183c.194-.062.325-.266.244-.453c-.108-.244-.333-.499-.887-.655c-.662-.188-1.943-.284-2.515-.336a948 948 0 0 0-.735-5.97c-.094-.671-.226-1.413-.773-2.913");
}

.iykv72k7v {
  stop-color: var(--svg-color--62516b, #62516B);
}

.j92jtbb2k {
  fill-rule: evenodd;
  d: path("M13.822 11.735a1.05 1.05 0 0 0-.485 1.404c1.832 3.77 4.235 4.912 5.72 4.627a1.05 1.05 0 0 0-.396-2.063s-.026.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.803-.404c-.65-.457-1.494-1.354-2.31-3.034a1.05 1.05 0 0 0-1.404-.486");
}

.jea1nljqt {
  d: path("M16.322 5.769a1 1 0 0 1-.258-.457h-.18v1.125c.216.136.523.115.614-.09c.078-.176.02-.395-.176-.578");
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jogzo_66p {
  stop-color: var(--svg-color--5b789d, #5B789D);
}

.k-u87vbol {
  d: path("m8.764 21.084l-3.477 4.428l.514.199l3.485-3.708a3 3 0 0 0 .76-1.494l.191-1l-.751-.773l-.544 1.993a1 1 0 0 1-.178.355");
}

.k5q572hpz {
  stop-color: var(--svg-color--6e473c, #6E473C);
  stop-opacity: 0;
}

.knd8fccgb {
  stop-color: var(--svg-color--9d6081, #9D6081);
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.kqn0y5w2b {
  stop-color: var(--svg-color--5696dc, #5696DC);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l138bfbcs {
  stop-color: var(--svg-color--282955, #282955);
}

.l3_0v7cyw {
  stop-color: var(--svg-color--ab826c, #AB826C);
}

.l7vpqwwuy {
  stop-color: var(--svg-color--4475a6, #4475A6);
  stop-opacity: 0;
}

.lf9s3z4la {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m4.756 25.61l1.638.677l-.021.02q.046.157.107.356c.216.712.535 1.763.62 2.27c.077.462-.145.768-.351.952c-.094.084-.235.064-.318-.029l-2.688-2.995a.25.25 0 0 1 .019-.353l.986-.888z");
}

.lhdz7oxfj {
  stop-color: var(--svg-color--444571, #444571);
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.lqtvazhgp {
  width: 0.832px;
  height: 1.669px;
  fill: var(--svg-color--ac7f74, #AC7F74);
  rx: 0.416px;
}

.ltxof3fvo {
  stop-color: var(--svg-color--624646, #624646);
}

.lufyf2brv {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.563 16.006a1.211 1.211 0 1 0-.117 1.212");
}

.ly5_jc0cc {
  stop-color: var(--svg-color--4d3b5c, #4D3B5C);
}

.m_uy2vb_d {
  stop-color: var(--svg-color--695c75, #695C75);
  stop-opacity: 0;
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.m3n9jy0fh {
  stop-color: var(--svg-color--63617e, #63617E);
}

.mngz2ebss {
  stop-color: var(--svg-color--897998, #897998);
}

.mpu3do46a {
  stop-color: var(--svg-color--4d95e1, #4D95E1);
}

.mvw8vhw3e {
  stroke: var(--svg-color--33241a, #33241A);
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M19.55 15.976a1.21 1.21 0 1 0-.102 1.24");
}

.n3m07owib {
  stop-color: var(--svg-color--9a746d, #9A746D);
  stop-opacity: 0;
}

.n6l6ilaec {
  stop-color: var(--svg-color--d4c6dc, #D4C6DC);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.nj0viubvx {
  stop-color: var(--svg-color--624646, #624646);
  stop-opacity: 0;
}

.nvzddhbxg {
  d: path("m14.592 21.136l1.344 6.5l-.36.313l-1.469-6.532l-3.015-3.875l.703-.484z");
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.o52vxyscb {
  stop-color: var(--svg-color--443d44, #443D44);
}

.oiy_54b9a {
  stop-color: var(--svg-color--887e8b, #887E8B);
}

.ov-p8go0b {
  d: path("M14.658 10.456c-.281-.712-.841-1.208-1.052-1.374l.107 4.452l1.785-.836c-.278-.523-.489-1.351-.84-2.242");
}

.oxce79bcz {
  stop-color: var(--svg-color--282955, #282955);
  stop-opacity: 0;
}

.oxg1n1wjw {
  stop-color: var(--svg-color--5a577e, #5A577E);
}

.p0binz11r {
  stop-color: var(--svg-color--3d98c9, #3D98C9);
  stop-opacity: 0;
}

.p6qc3nb-j {
  stop-color: var(--svg-color--492d85, #492D85);
}

.p8mdyfi9b {
  stop-color: var(--svg-color--f35886, #F35886);
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.pr310ga5h {
  stop-color: var(--svg-color--af8771, #AF8771);
  stop-opacity: 0;
}

.pw8a02b5q {
  stop-color: var(--svg-color--492b38, #492B38);
}

.qg5pcsysc {
  stop-color: var(--svg-color--483a55, #483A55);
  stop-opacity: 0;
}

.ql4avvisg {
  stop-color: var(--svg-color--6e473c, #6E473C);
}

.qnz-ctb1c {
  stop-color: var(--svg-color--9c7c6a, #9C7C6A);
  stop-opacity: 0;
}

.qqm4th_px {
  d: path("M15.46 4.052c.656 0 .968-.371 1-.836c0-.656-.502-.796-.696-.816c-.219-.024-.305-.047-.61-.262a.9.9 0 0 0-.91-.098c-.148.07-.476.106-.71.035c-.391-.117-.696-.113-.997.118c-.208.16-.362.16-.613.16c-.344 0-.635.154-.855.32c-.658.497-.582 2.207-.258 3.168c.31.92.777 1.027 1.168.992c.47-.042.59-.398.66-.695c.056-.238.2-.99.266-1.238c.135-.062.43-.086.53-.473c.1-.388.493-.432.759-.406c.161.015.61.03 1.265.03");
}

.r5xnzcbol {
  fill: var(--svg-color--513a3c, #513A3C);
  fill-rule: evenodd;
  d: path("M14.822 4.742c.148-.106.363-.111.5-.111a.2.2 0 1 0 0-.4h-.009c-.128 0-.464 0-.724.186a.2.2 0 1 0 .233.325");
}

.r5z1pjbbo {
  stop-color: var(--svg-color--4475a6, #4475A6);
}

.r9il63bci {
  fill: var(--svg-color--397ec9, #397EC9);
  d: path("M12.268 8.554c-.891 0-1.137.215-1.434.406l-1.023 2.598c-.3 1.4-.365 3.635-.36 4.578h4.747c.258-.656.696-2.675.535-4.578c-.165-1.93-1.208-2.902-2.465-3.004");
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.rm4aiz5dn {
  stop-color: var(--svg-color--887e8b, #887E8B);
  stop-opacity: 0;
}

.rnrhdzckq {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
  stop-opacity: 0;
}

.rs-uzvy4c {
  stroke: var(--svg-color--c09887, #C09887);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.005 10.644c-.97.906-3.157 3.218-4.485 7.468");
}

.ryq0o3qru {
  stop-color: var(--svg-color--a19da6, #A19DA6);
}

.snyu1wb4r {
  d: path("m8.623 19.902l.89-3.735h1.781c.053.615.152 2.216.29 3.516s-.492 2.031-.766 2.312l-4.445 4.313c.198.661.627 2.025.727 2.625c.077.462-.145.768-.351.952c-.094.084-.235.064-.319-.029l-2.687-2.995a.25.25 0 0 1 .019-.353l.986-.888c1.041-1.364 3.19-4.193 3.453-4.593c.181-.277.39-.917.422-1.125");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.stwbr2bhy {
  stop-color: var(--svg-color--46437b, #46437B);
  stop-opacity: 0;
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.thq9kiblh {
  d: path("M12.403 11.16a1.355 1.355 0 1 0-1.729-2.088c-.95.692-1.79 1.591-2.27 2.134l2.04 1.914c.307-.32 1.381-1.392 1.96-1.96");
}

.tl0sw7mkk {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.ty0uj7bex {
  stop-color: var(--svg-color--b08a7d, #B08A7D);
}

.u-867gbtx {
  stop-color: var(--svg-color--443d44, #443D44);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uug2ubxhk {
  stop-color: var(--svg-color--e82b8e, #E82B8E);
}

.ux4w7lb6c {
  stop-color: var(--svg-color--8c8388, #8C8388);
}

.v5lz4sb9o {
  stop-color: var(--svg-color--695c75, #695C75);
}

.v9kimlbms {
  stop-color: var(--svg-color--94899e, #94899E);
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vi11a8djh {
  d: path("M18.956 16.001a.2.2 0 0 0-.28-.045l-.817.59a.2.2 0 0 0-.045.28l1.51 2.089a.2.2 0 0 0 .279.045l.817-.59a.2.2 0 0 0 .045-.28z");
}

.vjqn9lx3p {
  stop-color: var(--svg-color--cdb4e3, #CDB4E3);
}

.vwf3bac9u {
  fill-rule: evenodd;
  d: path("M19.37 17.769a.45.45 0 0 0-.1.629l7.774 10.695a.45.45 0 0 0 .728-.53l-7.773-10.695a.45.45 0 0 0-.629-.1");
}

.vxqcofbqp {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M14.975 18.519c-.383-1.051-.716-2.029-.774-2.383H9.46c-.1 1.375.144 1.712.774 2.422c.692.781 2.171 2.43 2.539 2.894c.35.35.5.79.554.98l2.263 7.431a.25.25 0 0 0 .314.166l3.738-1.183c.194-.062.325-.266.244-.453c-.108-.244-.333-.499-.887-.655c-.662-.188-1.943-.284-2.515-.336a948 948 0 0 0-.735-5.97c-.094-.671-.226-1.413-.773-2.913");
}

.w48m3830t {
  stop-color: var(--svg-color--4e98d7, #4E98D7);
}

.wbet_dbvt {
  fill: var(--svg-color--a37b64, #A37B64);
  fill-rule: evenodd;
  d: path("M13.822 11.735a1.05 1.05 0 0 0-.485 1.404c1.832 3.77 4.235 4.912 5.72 4.627a1.05 1.05 0 0 0-.396-2.063s-.026.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.803-.404c-.65-.457-1.494-1.354-2.31-3.034a1.05 1.05 0 0 0-1.404-.486");
}

.wfraawh3t {
  stop-color: var(--svg-color--e4d4ea, #E4D4EA);
  stop-opacity: 0;
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.x45bnccdq {
  stop-color: var(--svg-color--588fc4, #588FC4);
}

.x5p6yzbmf {
  stop-color: var(--svg-color--817076, #817076);
}

.xh_da2q2q {
  stop-color: var(--svg-color--60618d, #60618D);
}

.xu259ab4x {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
  stop-opacity: 0;
}

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.y3zdm1aic {
  stop-color: var(--svg-color--3384e0, #3384E0);
}

.y9d6-sb7h {
  d: path("m15.182 5.599l-.004-.072c0-.186.079-.336.176-.336s.175.15.175.336l-.004.072z");
}

.yfqxgqb1h {
  stop-color: var(--svg-color--a19da6, #A19DA6);
  stop-opacity: 0;
}

.ygdc80fko {
  stop-color: var(--svg-color--d8cbdd, #D8CBDD);
}

.yvuyjoqpy {
  stop-color: var(--svg-color--47456f, #47456F);
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.z629lk5yz {
  stop-color: var(--svg-color--417ab5, #417AB5);
  stop-opacity: 0;
}

.z8jy9-b3h {
  d: path("M0 0h1.946v3.44H0z");
}

.zc8ie-1dg {
  stop-color: var(--svg-color--515279, #515279);
  stop-opacity: 0;
}

.znpkhwbgq {
  stop-color: var(--svg-color--445b8b, #445B8B);
}

.zz_g2hbek {
  stop-color: var(--svg-color--77584a, #77584A);
}

</style>
