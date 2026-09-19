<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iJptaNb)" class="h-jczlzen"/><path fill="url(#i4cKQJd)" class="ze-agacxi"/><rect fill="url(#i5Q8CJc)" class="gyc1lm0xs"/><rect fill="url(#iMhCq0d)" class="gyc1lm0xs"/><g filter="url(#i0naiMd)"><path fill="url(#iwPHoGe)" class="fsxm9dwni"/><path fill="url(#iE1Iudc)" class="fsxm9dwni"/><path fill="url(#imfrFob)" class="fsxm9dwni"/><path fill="url(#i2I1S3d)" class="fsxm9dwni"/><path fill="url(#i5HHI1d)" class="fsxm9dwni"/><path fill="url(#iRpUQec)" class="fsxm9dwni"/></g><path fill="url(#iYDpJid)" class="fsxm9dwni"/><path fill="url(#iTJB4le)" class="fsxm9dwni"/><path fill="url(#iOcLhxb)" class="fsxm9dwni"/><g filter="url(#i4edOvb)"><path class="uuj2cmbsf"/></g><g filter="url(#iJX2DbF)"><path fill="url(#ige5Ixg)" class="h9nb3dbmm"/><path fill="url(#iLBuYYI)" class="h9nb3dbmm"/><path fill="url(#ibHBJ2c)" class="h9nb3dbmm"/><path fill="url(#i5OHlzy)" class="h9nb3dbmm"/><path fill="url(#iy4NCve)" class="h9nb3dbmm"/><path fill="url(#iU1fZOd)" class="h9nb3dbmm"/><path fill="url(#in4A7jb)" class="h9nb3dbmm"/></g><g filter="url(#iZe5Bkc)"><path class="ol4pjzgjs"/><path fill="url(#ilmoTzc)" class="fk9nbx4th"/><path fill="url(#i3pI6Ec)" class="fk9nbx4th"/><path fill="url(#i2cjtuc)" class="fk9nbx4th"/></g><path fill="url(#i37Ptac)" class="fk9nbx4th"/><path fill="url(#iAz39wc)" class="fk9nbx4th"/><g filter="url(#i0snLmc)"><path class="gulr-t6qo"/><path fill="url(#imqWqJb)" class="dqa_-7bzp"/><path fill="url(#iza40Md)" class="dqa_-7bzp"/></g><g filter="url(#idy5Jmc)"><path class="bi7rg6bpw"/><path fill="url(#iaRzphc)" class="l9mu020_s"/><path fill="url(#iuj2q4f)" class="l9mu020_s"/></g><path class="wiieli2ej"/><path fill="url(#iGoekNb)" class="hi0vjzatb"/><path class="dain57iqy"/><g filter="url(#iX0Xw1b)"><path class="mxpallb1y"/><path fill="url(#iSDDtpb)" class="d879qkbvi"/></g><g filter="url(#itpkTJF)"><path fill="url(#ivuPxEJ)" class="gfer3rbfb"/></g><path class="hwvoaqesi"/><path fill="url(#ieU5R2d)" class="wu2h8jb4k"/><path class="uaxsyh7oh"/><g filter="url(#i4q0ZxU)"><path fill="url(#iqDZooO)" class="afwn1lnfh"/></g><g filter="url(#iB2Ybif)"><ellipse transform="rotate(-27.914 13.272 14.777)" class="lulnx3bbe"/><ellipse fill="url(#i9ZqFNd)" transform="rotate(-27.914 13.272 14.777)" class="f0qoe92_d"/></g><path fill="url(#iJVEkSd)" class="ppk0kktky"/><path fill="url(#idPmTOb)" class="nrnvctv1v"/><g filter="url(#iPN79wB)"><path fill="url(#iJ2XgUC)" class="ygjg_lb-n"/></g><g filter="url(#ik1rB1d)"><path fill="url(#iampGFO)" class="fv_h9xbci"/></g><g filter="url(#iAVmXKv)"><path clip-rule="evenodd" class="l4dfd7h4n"/></g><g filter="url(#iu4YBcc)"><path stroke="url(#iPwMb0R)" class="dg217h9if"/></g><g filter="url(#idk2axN)"><path clip-rule="evenodd" class="msdhbgd-s"/></g><g filter="url(#i36Ydme)"><path stroke="url(#ivQnCgb)" class="bxh6ncchi"/></g><path stroke="url(#iyKI9gu)" class="xz29lgbft"/><path fill="url(#iqa8jUb)" class="i-377o6ky"/><path fill="url(#iOklChe)" class="i-377o6ky"/><path fill="url(#in5utCd)" class="i-377o6ky"/><path fill="url(#ianvqSH)" class="i-377o6ky"/><path fill="url(#iOAhnad)" class="i-377o6ky"/><path fill="url(#i50HDKe)" class="i-377o6ky"/><path fill="url(#iu922je)" class="i-377o6ky"/><path fill="url(#iJj6fAb)" class="i-377o6ky"/><path fill="url(#iT1p4BP)" class="i-377o6ky"/><path fill="url(#i3YXDxb)" class="i-377o6ky"/><path fill="url(#iVR9uyi)" class="i-377o6ky"/><path fill="url(#ij88k2b)" class="i-377o6ky"/><path fill="url(#icHg3Rj)" class="dges7ib9m"/><path fill="url(#ictyttc)" class="dges7ib9m"/><path fill="url(#i4olntC)" class="vtekkxd_w"/><path fill="url(#ipIrvKd)" class="vtekkxd_w"/><path fill="url(#iu6jDXd)" class="vtekkxd_w"/><path fill="url(#iZLh4td)" class="cb1ljub6x"/><path fill="url(#iQrSg7d)" class="cb1ljub6x"/><path fill="url(#iwX5lDc)" class="rrphcb4zv"/><path fill="url(#id26DLc)" class="rrphcb4zv"/><path fill="url(#invl7nc)" class="rrphcb4zv"/><g filter="url(#i5pwlpd)"><path fill="url(#iQl0Rod)" class="bf8qmd23r"/></g><g filter="url(#iKfEBub)"><path stroke="url(#iGMk6Lh)" class="eusvtmb2r"/></g><path stroke="url(#ipi6PkK)" class="v61f_wbit"/><path stroke="url(#iOEpAGc)" class="v61f_wbit"/><path stroke="url(#iZiA9rd)" class="nh2kw4_uc"/><path stroke="url(#igu4Wib)" class="nh2kw4_uc"/><path stroke="url(#igekahc)" class="nh2kw4_uc"/><path stroke="url(#iYXqbGe)" class="nh2kw4_uc"/><path stroke="url(#ifbMRrb)" class="d8ptwz9tw"/><path stroke="url(#iZNf98c)" class="d8ptwz9tw"/><path stroke="url(#i8mm96n)" class="dbid5acei"/><path stroke="url(#iRA8qre)" class="dbid5acei"/><path stroke="url(#itaqete)" class="dbid5acei"/><path stroke="url(#i2IfsZd)" class="dbid5acei"/><path stroke="url(#iWsBnDd)" class="jx3zfg-wy"/><path stroke="url(#iRIzrFb)" class="jx3zfg-wy"/><path stroke="url(#iV6w3Db)" class="gg4pweb1t"/><path stroke="url(#iPDf5to)" class="gg4pweb1t"/><path stroke="url(#iHg6ZDc)" class="gg4pweb1t"/><path stroke="url(#i6G8AGb)" class="gg4pweb1t"/><path stroke="url(#iJc5Lab)" class="ipg0cn99k"/><path stroke="url(#iiSsDhd)" class="ipg0cn99k"/><path stroke="url(#ix736Uq)" class="u-qvctb2c"/><path stroke="url(#iCeCWXu)" class="u-qvctb2c"/><path stroke="url(#iJVtyHd)" class="u-qvctb2c"/><path stroke="url(#i5wzGyb)" class="u-qvctb2c"/><path fill="url(#istGYAd)" class="uz3hg9bsf"/><path fill="url(#iZ10Vsd)" class="uz3hg9bsf"/><path fill="url(#ic4L3td)" class="igo7pk_ym"/><path fill="url(#ipv3xCc)" class="igo7pk_ym"/><g filter="url(#idMQqqc)"><path stroke="url(#iX2Ogeb)" class="fohmhtbju"/></g><g filter="url(#iNHRIPe)"><path stroke="url(#ivPD1Mb)" class="nh7q47k8r"/></g><g filter="url(#i5bwBAd)"><path stroke="url(#itkI9Ic)" class="vxljdps-k"/></g><g filter="url(#i86vvxb)"><path stroke="url(#iDZBald)" class="wgy-qlbik"/></g><defs><radialGradient id="iJptaNb" cx="0" cy="0" r="1" gradientTransform="matrix(-.83944 3.44902 -4.09716 -.99719 21.983 16.75)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="c2cw8kbzt"/><stop offset=".837" class="bw-0wlb6v"/></radialGradient><radialGradient id="i4cKQJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.12646 -.03884 .11746 3.40643 9.608 18.052)" gradientUnits="userSpaceOnUse"><stop class="jp6tlutdp"/><stop offset=".944" class="eq5c-0bja"/></radialGradient><radialGradient id="i5Q8CJc" cx="0" cy="0" r="1" gradientTransform="rotate(45 -18.936 28.915)scale(3.69687 4.54701)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="luzwsybtw"/><stop offset="1" class="jss2kw0gn"/></radialGradient><radialGradient id="iMhCq0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.19776 1.08529 0 16.977 25.298)" gradientUnits="userSpaceOnUse"><stop class="aqyw8xbsm"/><stop offset="1" class="cs4tu-bfg"/></radialGradient><radialGradient id="iwPHoGe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.21203 0 0 -3.008 15.994 18.235)" gradientUnits="userSpaceOnUse"><stop class="jx57xnbtd"/><stop offset="1" class="kyvc_ob9l"/></radialGradient><radialGradient id="iE1Iudc" cx="0" cy="0" r="1" gradientTransform="rotate(105.939 5.022 11.943)scale(4.69997 4.25479)" gradientUnits="userSpaceOnUse"><stop class="i4c630b-n"/><stop offset="1" class="ib6gywlbs"/></radialGradient><radialGradient id="imfrFob" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -5 10.62498 3.18748 13.533 23.038)" gradientUnits="userSpaceOnUse"><stop class="u7dfrl2ct"/><stop offset="1" class="gxxikzvvd"/></radialGradient><radialGradient id="i2I1S3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.03328 1.81347 0 13.579 14.561)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="c_m5awbrz"/><stop offset="1" class="w0t99db7r"/></radialGradient><radialGradient id="i5HHI1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34636 1.7402 0 18.488 14.149)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="fjq8urb1u"/><stop offset="1" class="l1tokglcj"/></radialGradient><radialGradient id="iRpUQec" cx="0" cy="0" r="1" gradientTransform="rotate(-154.375 12.92 6.964)scale(6.48931 11.4178)" gradientUnits="userSpaceOnUse"><stop class="zdhvrqmhr"/><stop offset="1" class="tpbiu1b7n"/></radialGradient><radialGradient id="iTJB4le" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 6.3125 -1.34311 -.11303 10.189 15.163)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="hdcvmhbib"/><stop offset="1" class="a0r1cac4o"/></radialGradient><radialGradient id="iOcLhxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.9417 -2.80617 .56113 .38826 10.227 11.813)" gradientUnits="userSpaceOnUse"><stop class="l5z8v8buo"/><stop offset="1" class="pa76eg1ox"/></radialGradient><radialGradient id="i5OHlzy" cx="0" cy="0" r="1" gradientTransform="matrix(0 .1875 -.73438 0 16.384 17.218)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="gd0ml22cv"/><stop offset="1" class="z9pz_x6lh"/></radialGradient><radialGradient id="ilmoTzc" cx="0" cy="0" r="1" gradientTransform="rotate(59.323 -.448 13.29)scale(3.14567 7.82114)" gradientUnits="userSpaceOnUse"><stop class="k999twbbe"/><stop offset="1" class="ycd3jvtwj"/></radialGradient><radialGradient id="i3pI6Ec" cx="0" cy="0" r="1" gradientTransform="rotate(125.395 8.317 8.834)scale(2.13755 3.18469)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="k999twbbe"/><stop offset=".905" class="ycd3jvtwj"/></radialGradient><radialGradient id="i2cjtuc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49955 .43561 -.73415 -4.21257 22.95 11.527)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="dajc8pb1s"/><stop offset="1" class="vdsilzblf"/></radialGradient><radialGradient id="i37Ptac" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -2.34375 3.84014 .40961 9.845 14.1)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="kg5wfpbcx"/><stop offset="1" class="lfjjhubys"/></radialGradient><radialGradient id="iAz39wc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46062 1.68536 -2.72587 -2.36239 20.799 8.236)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="qy05b9bsw"/><stop offset="1" class="aqwz8eb5i"/></radialGradient><radialGradient id="imqWqJb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70756 0 0 -.70728 16.54 7.8)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="d6r-hbcax"/><stop offset="1" class="mdoiiwbdb"/></radialGradient><radialGradient id="iza40Md" cx="0" cy="0" r="1" gradientTransform="matrix(3.50375 -5.54762 8.14343 5.14321 10.03 12.188)" gradientUnits="userSpaceOnUse"><stop class="jtm80bvmo"/><stop offset=".288" class="j-racdxto"/></radialGradient><radialGradient id="iaRzphc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.03126 .584 -.63293 -5.45279 21.288 8.817)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="alx2et7wd"/><stop offset="1" class="owipfybjq"/></radialGradient><radialGradient id="iuj2q4f" cx="0" cy="0" r="1" gradientTransform="matrix(3.02827 .7705 -.33418 1.31341 19.37 8.882)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="wsfk1t4wo"/><stop offset="1" class="z_e7pbcya"/></radialGradient><radialGradient id="iGoekNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88332 -1.40502 0 18.319 14.882)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="au361rb0r"/></radialGradient><radialGradient id="iSDDtpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2525 -.32538 .44797 -.34763 18.07 14.973)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieU5R2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88336 -1.40509 0 13.567 14.882)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="au361rb0r"/></radialGradient><radialGradient id="i9ZqFNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00842 -.53793 .64661 -.01012 13.256 15.12)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJVEkSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.42879 0 0 1.59032 21.416 15.335)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="brwqb-bhb"/><stop offset="1" class="g5jsf5l8p"/></radialGradient><radialGradient id="idPmTOb" cx="0" cy="0" r="1" gradientTransform="rotate(-175.776 5.511 7.612)scale(1.29257 2.20938)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="wz834g6bz"/><stop offset="1" class="usrzeqb5b"/></radialGradient><radialGradient id="iJ2XgUC" cx="0" cy="0" r="1" gradientTransform="matrix(-.65365 0 0 -1.07747 10.491 15.499)" gradientUnits="userSpaceOnUse"><stop class="pistvdbbt"/><stop offset="1" class="oey3hsxgc"/></radialGradient><radialGradient id="iampGFO" cx="0" cy="0" r="1" gradientTransform="matrix(.96094 .04287 -.03776 .84633 21.369 15.448)" gradientUnits="userSpaceOnUse"><stop class="zoedh-kcq"/><stop offset=".809" class="yo0f3rety"/></radialGradient><radialGradient id="iOklChe" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 -1.091 15.5)scale(7.05349 6.17563)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="m_2922ixt"/><stop offset="1" class="a-2r3fbgq"/></radialGradient><radialGradient id="in5utCd" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.957 8.251)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="h9fb5bbiv"/><stop offset="1" class="j1090kf1c"/></radialGradient><radialGradient id="ianvqSH" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.98 14.584)" gradientUnits="userSpaceOnUse"><stop class="hiycpfc4f"/><stop offset="1" class="mqq2pckgy"/></radialGradient><radialGradient id="iOAhnad" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.167 6.772)" gradientUnits="userSpaceOnUse"><stop class="ew56wjbup"/><stop offset="1" class="qd38sjb7e"/></radialGradient><radialGradient id="i50HDKe" cx="0" cy="0" r="1" gradientTransform="rotate(123.092 2.574 5.633)scale(1.65986 2.90522)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="jbd_cz55y"/><stop offset="1" class="by6guy4wy"/></radialGradient><radialGradient id="iu922je" cx="0" cy="0" r="1" gradientTransform="rotate(158.664 4.7 10.01)scale(5.43502 6.37816)" gradientUnits="userSpaceOnUse"><stop class="bps78hksv"/><stop offset="1" class="fh1_5ac_k"/></radialGradient><radialGradient id="iJj6fAb" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 .71875 -2.2725 1.03746 23.543 6.146)" gradientUnits="userSpaceOnUse"><stop class="ze5ugdbxr"/><stop offset="1" class="pr8brkb_h"/></radialGradient><radialGradient id="iT1p4BP" cx="0" cy="0" r="1" gradientTransform="matrix(5.0625 -2.5 8.03057 16.26191 2.533 21.976)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="aeh-ojcyt"/><stop offset="1" class="eg11r1-xe"/></radialGradient><radialGradient id="i3YXDxb" cx="0" cy="0" r="1" gradientTransform="matrix(5.3125 1.875 -1.76947 5.01351 20.72 14.6)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="g1bdywbbk"/><stop offset="1" class="woz3hacrx"/></radialGradient><radialGradient id="iVR9uyi" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 -1.5 3.12608 5.73115 20.845 10.35)" gradientUnits="userSpaceOnUse"><stop class="g1bdywbbk"/><stop offset="1" class="woz3hacrx"/></radialGradient><radialGradient id="ij88k2b" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 1.625 -3.0178 6.26772 20.783 16.976)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="g1bdywbbk"/><stop offset="1" class="woz3hacrx"/></radialGradient><radialGradient id="icHg3Rj" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 1 -2.31305 -1.3011 9.058 6.272)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="ictyttc" cx="0" cy="0" r="1" gradientTransform="rotate(123.118 3.117 5.629)scale(.58626 1.5796)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="qso4uy3-n"/><stop offset="1" class="b_rfybbbi"/></radialGradient><radialGradient id="i4olntC" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1 -2.31306 1.3011 23.088 6.272)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="ipIrvKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.2431 1.58204 -3.03843 2.38745 24.031 4.959)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="j26seachc"/><stop offset=".74" class="rsdjdrd8e"/></radialGradient><radialGradient id="iu6jDXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.64397 -.80986 .45783 .92938 23.225 5.166)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="vj5muxz_t"/><stop offset="1" class="tdhijwbfm"/></radialGradient><radialGradient id="iZLh4td" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.23 5.866)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="jwb4ndb5j"/><stop offset="1" class="iskwzzbgz"/></radialGradient><radialGradient id="iQrSg7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.25052 1.35191 -6.0911 5.63427 8.073 2.829)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="n1zjiicmq"/><stop offset="1" class="h38v_uqzc"/></radialGradient><radialGradient id="iwX5lDc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.568 1.57046 -2.49003 -4.07165 24.454 4.389)" gradientUnits="userSpaceOnUse"><stop class="r20qsbc_c"/><stop offset=".469" class="k05e99b6a"/></radialGradient><radialGradient id="id26DLc" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.105 1.85)" gradientUnits="userSpaceOnUse"><stop class="pa_nigs1j"/><stop offset="1" class="igdnfmbpz"/></radialGradient><radialGradient id="iQl0Rod" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.21 16.602)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop class="y1z543b6m"/><stop offset="1" class="qetg81_po"/></radialGradient><radialGradient id="iOEpAGc" cx="0" cy="0" r="1" gradientTransform="rotate(-93.478 7.828 -4.237)scale(1.41667 3.55456)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="igekahc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05476 2.51663 -2.82772 -3.43237 20.344 .745)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="iYXqbGe" cx="0" cy="0" r="1" gradientTransform="matrix(.2932 -1.02712 5.11536 1.46024 19.44 3.236)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="hxfs4uq1u"/><stop offset=".928" class="oxual4umn"/></radialGradient><radialGradient id="iZNf98c" cx="0" cy="0" r="1" gradientTransform="matrix(.01563 -1.60937 4.07454 .03956 13.83 3.96)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="itaqete" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49679 3.90397 -3.9658 -2.53634 19.116 .353)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="i2IfsZd" cx="0" cy="0" r="1" gradientTransform="matrix(.18011 -1.3052 4.75684 .65644 18.493 3.953)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="hxfs4uq1u"/><stop offset=".961" class="oxual4umn"/></radialGradient><radialGradient id="iRIzrFb" cx="0" cy="0" r="1" gradientTransform="matrix(.02344 -1.14844 3.51652 .07176 13.712 4.577)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="iHg6ZDc" cx="0" cy="0" r="1" gradientTransform="rotate(136.107 8.8 5.252)scale(2.80418 3.18917)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="i6G8AGb" cx="0" cy="0" r="1" gradientTransform="matrix(.08594 -1.03125 3.07583 .25632 18.462 4.562)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="hxfs4uq1u"/><stop offset=".928" class="oxual4umn"/></radialGradient><radialGradient id="iiSsDhd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05102 -1.35157 3.65385 -.13794 13.38 5.796)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="iJVtyHd" cx="0" cy="0" r="1" gradientTransform="rotate(126.357 9.01 6.49)scale(3.42495 3.7672)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="i5wzGyb" cx="0" cy="0" r="1" gradientTransform="matrix(.11829 -1.13281 3.5915 .37502 18.766 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="hxfs4uq1u"/><stop offset=".928" class="oxual4umn"/></radialGradient><radialGradient id="istGYAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.84377 4.59374 -16.3905 -3.01059 20.845 2.6)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="kave1bcji"/><stop offset="1" class="cttfyfb4x"/></radialGradient><radialGradient id="iZ10Vsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.50682 -3.31996 -1.79016 22.814 2.882)" gradientUnits="userSpaceOnUse"><stop class="vah6rkr4l"/><stop offset="1" class="m57mo2r3b"/></radialGradient><radialGradient id="ic4L3td" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 8.998 -1.336)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="qnsxe8b8l"/><stop offset="1" class="tiwzfl9rq"/></radialGradient><radialGradient id="ipv3xCc" cx="0" cy="0" r="1" gradientTransform="rotate(-36.852 14.11 -9.57)scale(3.60415 1.2911)" gradientUnits="userSpaceOnUse"><stop class="bl99nbbnz"/><stop offset="1" class="nddsbvhqr"/></radialGradient><linearGradient id="iYDpJid" x1="21.457" x2="21.034" y1="16.579" y2="16.556" gradientUnits="userSpaceOnUse"><stop class="dfadynwhb"/><stop offset="1" class="ks6l0q0jc"/></linearGradient><linearGradient id="ige5Ixg" x1="16.308" x2="16.308" y1="17.565" y2="14.615" gradientUnits="userSpaceOnUse"><stop offset=".683" class="gpxc7t0si"/><stop offset="1" class="ram2tx4_p"/></linearGradient><linearGradient id="iLBuYYI" x1="17.151" x2="15.943" y1="16.194" y2="16.301" gradientUnits="userSpaceOnUse"><stop class="ugjqw0bgi"/><stop offset="1" class="rsxq6wbbl"/></linearGradient><linearGradient id="ibHBJ2c" x1="16.095" x2="16.095" y1="17.772" y2="16.988" gradientUnits="userSpaceOnUse"><stop offset=".101" class="yj9m5xbqx"/><stop offset="1" class="q7_s_7b5y"/></linearGradient><linearGradient id="iy4NCve" x1="14.921" x2="15.264" y1="16.655" y2="16.747" gradientUnits="userSpaceOnUse"><stop offset=".269" class="o42fgjhpg"/><stop offset="1" class="hy82m0yne"/></linearGradient><linearGradient id="iU1fZOd" x1="15.829" x2="15.829" y1="17.898" y2="17.444" gradientUnits="userSpaceOnUse"><stop offset=".138" class="o42fgjhpg"/><stop offset=".655" class="hy82m0yne"/></linearGradient><linearGradient id="in4A7jb" x1="15.943" x2="15.943" y1="14.615" y2="15.234" gradientUnits="userSpaceOnUse"><stop offset=".063" class="huk-m1bdc"/><stop offset="1" class="h3lnwrb9u"/></linearGradient><linearGradient id="ivuPxEJ" x1="19.166" x2="18.824" y1="14.94" y2="15.151" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqDZooO" x1="14.377" x2="14.036" y1="14.94" y2="15.151" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPwMb0R" x1="14.072" x2="11.494" y1="12.32" y2="12.32" gradientUnits="userSpaceOnUse"><stop offset=".333" class="upoucm8pi"/><stop offset="1" class="pz46uffpz"/></linearGradient><linearGradient id="ivQnCgb" x1="17.814" x2="20.392" y1="12.32" y2="12.32" gradientUnits="userSpaceOnUse"><stop offset=".333" class="upoucm8pi"/><stop offset="1" class="pz46uffpz"/></linearGradient><linearGradient id="iyKI9gu" x1="14.97" x2="15.458" y1="19.495" y2="18.613" gradientUnits="userSpaceOnUse"><stop class="iiih_t14k"/><stop offset=".537" class="qh77xqbfv"/></linearGradient><linearGradient id="iqa8jUb" x1="24.522" x2="10.056" y1="12.742" y2="32.591" gradientUnits="userSpaceOnUse"><stop class="eod5jnblz"/><stop offset="1" class="afa9xwbaj"/></linearGradient><linearGradient id="invl7nc" x1="16.299" x2="20.377" y1="3.726" y2="3.788" gradientUnits="userSpaceOnUse"><stop class="bmtycdcmz"/><stop offset=".719" class="cu4loobdh"/></linearGradient><linearGradient id="iGMk6Lh" x1="11.261" x2="7.292" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="j2t7368de"/><stop offset=".582" class="x05lq4b2v"/></linearGradient><linearGradient id="ipi6PkK" x1="14.256" x2="10.454" y1="2.588" y2="4.774" gradientUnits="userSpaceOnUse"><stop offset=".332" class="g0a9imbkr"/><stop offset=".777" class="gv_f6obqq"/></linearGradient><linearGradient id="iZiA9rd" x1="18.212" x2="20.9" y1="2.499" y2="3.267" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="igu4Wib" x1="16.136" x2="21.631" y1="3.099" y2="3.827" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="ifbMRrb" x1="15.281" x2="11.966" y1="3.297" y2="4.747" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="i8mm96n" x1="17.178" x2="19.996" y1="3.124" y2="3.463" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="iRA8qre" x1="15.165" x2="20.757" y1="4.282" y2="4.359" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="iWsBnDd" x1="14.951" x2="12.292" y1="4.165" y2="5.572" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="iV6w3Db" x1="17.416" x2="19.353" y1="4.093" y2="4.487" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="iPDf5to" x1="15.995" x2="19.94" y1="4.577" y2="4.668" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="iJc5Lab" x1="14.466" x2="11.783" y1="5.127" y2="5.741" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="ix736Uq" x1="17.888" x2="19.775" y1="4.994" y2="5.191" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="iCeCWXu" x1="16.545" x2="20.277" y1="5.886" y2="5.93" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="iX2Ogeb" x1="14.645" x2="11.594" y1="5.259" y2="5.98" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="ivPD1Mb" x1="15.116" x2="11.594" y1="4.207" y2="5.388" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="itkI9Ic" x1="15.249" x2="11.729" y1="3.221" y2="4.402" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="iDZBald" x1="14.43" x2="11.184" y1="2.409" y2="4.432" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><filter id="i0naiMd" width="11.877" height="14.137" x="10.431" y="8.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.219608 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3719"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.188235 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3719" result="effect2_innerShadow_4002_3719"/></filter><filter id="i4edOvb" width="4.044" height="5.157" x="13.696" y="13.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".5"/></filter><filter id="iJX2DbF" width="2.244" height="3.357" x="14.821" y="14.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".05"/></filter><filter id="iZe5Bkc" width="14.015" height="9.054" x="8.935" y="5.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.054902 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3719"/></filter><filter id="i0snLmc" width="7.25" height="6.272" x="9.295" y="6.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.2 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3719"/><feGaussianBlur result="effect2_foregroundBlur_4002_3719" stdDeviation=".15"/></filter><filter id="idy5Jmc" width="6.779" height="6.015" x="15.919" y="7.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.192157 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3719"/><feGaussianBlur result="effect2_foregroundBlur_4002_3719" stdDeviation=".15"/></filter><filter id="iX0Xw1b" width=".839" height=".74" x="17.528" y="14.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".05"/></filter><filter id="itpkTJF" width=".935" height=".959" x="18.452" y="14.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".1"/></filter><filter id="i4q0ZxU" width="1.038" height="1.097" x="13.615" y="14.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".1"/></filter><filter id="iB2Ybif" width=".976" height=".749" x="12.784" y="14.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".05"/></filter><filter id="iPN79wB" width="1.402" height="2.546" x="9.397" y="14.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".125"/></filter><filter id="ik1rB1d" width="1.531" height="2.572" x="21.158" y="14.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".125"/></filter><filter id="iAVmXKv" width="2.544" height="1.086" x="11.838" y="11.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3719"/></filter><filter id="iu4YBcc" width="2.594" height="1.136" x="11.763" y="11.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".125"/></filter><filter id="idk2axN" width="2.544" height="1.086" x="17.604" y="11.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3719"/></filter><filter id="i36Ydme" width="2.594" height="1.136" x="17.529" y="11.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".125"/></filter><filter id="i5pwlpd" width="16.188" height="8.656" x="9.167" y="21.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".5"/></filter><filter id="iKfEBub" width="4.094" height="4.656" x="7.917" y="22.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".25"/></filter><filter id="idMQqqc" width="3.508" height="1.177" x="11.47" y="4.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".125"/></filter><filter id="iNHRIPe" width="4.104" height="1.115" x="11.336" y="3.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".125"/></filter><filter id="i5bwBAd" width="4.104" height="1.115" x="11.47" y="2.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".125"/></filter><filter id="i86vvxb" width="4.288" height="1.471" x="10.456" y="1.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3719" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-ok-medium-dark" /></template>
<style>
.a-2r3fbgq {
  stop-color: var(--svg-color--9d4635, #9D4635);
  stop-opacity: 0;
}

.a0r1cac4o {
  stop-color: var(--svg-color--7a5651, #7A5651);
  stop-opacity: 0;
}

.aeh-ojcyt {
  stop-color: var(--svg-color--c7482a, #C7482A);
}

.afa9xwbaj {
  stop-color: var(--svg-color--db4f17, #DB4F17);
}

.afwn1lnfh {
  d: path("M14.453 15.22c0-.314-.255-.524-.324-.587l-.314.304l.193.393z");
}

.alx2et7wd {
  stop-color: var(--svg-color--250e14, #250E14);
  stop-opacity: 0;
}

.aqwz8eb5i {
  stop-color: var(--svg-color--494748, #494748);
  stop-opacity: 0;
}

.aqyw8xbsm {
  stop-color: var(--svg-color--926864, #926864);
}

.au361rb0r {
  stop-color: var(--svg-color--5f443e, #5F443E);
}

.b_rfybbbi {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
  stop-opacity: 0;
}

.bf8qmd23r {
  d: path("M23.933 27.147c-1.95-1.2-3.036-3.417-3.36-4.157c-5.174 0-9.28 1.97-10.406 6.657h14.188c0-.9-.156-1.938-.422-2.5");
}

.bi7rg6bpw {
  fill: var(--svg-color--2a0e2a, #2A0E2A);
  d: path("m21.618 12.986l-.032-.687c-.011-.832-.698-1.518-1.53-1.553h-1.524c-1.237 0-1.936-.897-2.273-1.948c-.236-.735.631-1.32 1.395-1.215c.905.126 1.914.21 3.342 1.142c1.899 1.239 1.622 3.21.622 4.26");
}

.bl99nbbnz {
  stop-color: var(--svg-color--8c5e58, #8C5E58);
}

.bmtycdcmz {
  stop-color: var(--svg-color--705247, #705247);
}

.bps78hksv {
  stop-color: var(--svg-color--942d01, #942D01);
}

.brwqb-bhb {
  stop-color: var(--svg-color--653e42, #653E42);
}

.bw-0wlb6v {
  stop-color: var(--svg-color--130303, #130303);
}

.bxh6ncchi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.773 12.757c-.266-.194-1.017-.545-1.894-.404");
}

.by6guy4wy {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
  stop-opacity: 0;
}

.c_m5awbrz {
  stop-color: var(--svg-color--71404c, #71404C);
}

.c2cw8kbzt {
  stop-color: var(--svg-color--2b2728, #2B2728);
}

.cb1ljub6x {
  d: path("M9.51 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.968 1.625 3.038 2.013q.017.006.034.006c.941-.005 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.219.696-.414c.063-.133.064-.316-.03-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .057-.625c.156-.062.336-.304.312-.648c-.037-.538-.494-.371-.713-.366l-.232-.29c.012-.55-.585-.6-.815-.575l-1.717.098a.98.98 0 0 0-.765-.133c-.432.123-1.264.339-2.094 1.047");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cs4tu-bfg {
  stop-color: var(--svg-color--926864, #926864);
  stop-opacity: 0;
}

.cttfyfb4x {
  stop-color: var(--svg-color--542a30, #542A30);
}

.cu4loobdh {
  stop-color: var(--svg-color--705247, #705247);
  stop-opacity: 0;
}

.d6r-hbcax {
  stop-color: var(--svg-color--3f2e34, #3F2E34);
}

.d879qkbvi {
  d: path("M18.25 14.568c.069.092-.076.205-.24.328c-.165.123-.287.21-.356.117c-.07-.092.008-.267.172-.39c.165-.123.354-.148.424-.055");
}

.d8ptwz9tw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.615 3.49c.43-.109 1.65-.273 2.666-.148");
}

.dain57iqy {
  fill: var(--svg-color--000, #000);
  d: path("M17.765 15.334c0-.31.247-.557.556-.557a.554.554 0 0 1 .495.813h-.985a.5.5 0 0 1-.066-.256");
}

.dajc8pb1s {
  stop-color: var(--svg-color--3a3636, #3A3636);
}

.dbid5acei {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.12 3.627c-.43-.11-2.375-.477-3.254-.266");
}

.dfadynwhb {
  stop-color: var(--svg-color--805d55, #805D55);
}

.dg217h9if {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.113 12.757c.266-.194 1.017-.545 1.894-.404");
}

.dges7ib9m {
  d: path("m7.392 4.635l-.428.666a.24.24 0 0 0 .01.278c.898 1.155 2.373 1.801 3.283 2.087a.244.244 0 0 0 .28-.107c.151-.248.354-.585.41-.69c.068-.131-.03-.232-.086-.265L7.845 4.775l.125-.273c-.35-.106-.531.044-.578.133");
}

.dqa_-7bzp {
  d: path("M16.222 9.305a3 3 0 0 1-.072-.15a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.823 1.647-3.823 3.68v.299c-.37-.282-.676-.57-.676-1.53c0-1.61 2.705-3.59 4.105-3.96a6 6 0 0 1 1.723-.178c.468.017.8.42.805.888l.016 1.391z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eg11r1-xe {
  stop-color: var(--svg-color--c7482a, #C7482A);
  stop-opacity: 0;
}

.eod5jnblz {
  stop-color: var(--svg-color--ff5918, #FF5918);
}

.eq5c-0bja {
  stop-color: var(--svg-color--130405, #130405);
}

.eusvtmb2r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.667 26.678c.48-.448 1.67-1.706 2.594-3.156");
}

.ew56wjbup {
  stop-color: var(--svg-color--ff7532, #FF7532);
}

.f-iegb-dq {
  stop-color: var(--svg-color--ff5930, #FF5930);
}

.f0qoe92_d {
  cx: 13.272px;
  cy: 14.777px;
  rx: 0.424px;
  ry: 0.215px;
}

.fh1_5ac_k {
  stop-color: var(--svg-color--942d01, #942D01);
  stop-opacity: 0;
}

.fjq8urb1u {
  stop-color: var(--svg-color--865352, #865352);
}

.fk9nbx4th {
  d: path("M21.229 8.493a2.53 2.53 0 0 1 1.38 1.145a2.58 2.58 0 0 1-.116 2.75a1.7 1.7 0 0 0-.294.952v1.294a1.9 1.9 0 0 0-.727-.292l.086-1.75a1.58 1.58 0 0 0-1.502-1.559h-1.524c-1.04 0-1.98-.613-2.408-1.57a.72.72 0 0 0-.67-.456h-1.386c-2.01 0-3.638 1.647-3.638 3.68l.034 1.673c-.277.04-.566.133-.784.287V13.34c0-.339-.104-.671-.295-.952a2.6 2.6 0 0 1-.156-2.663A2.55 2.55 0 0 1 10.644 8.5c.624-.222 1.026-.607 1.378-1.174c.45-.718 1.37-1.232 2.277-1.232c.353 0 .687.046.999.174c.416.181.883.181 1.299 0c.306-.128.641-.174.994-.174c.918 0 1.72.497 2.165 1.232c.335.555.86.958 1.473 1.168");
}

.fohmhtbju {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.845 5.561c.391-.173 1.476-.503 2.758-.41");
}

.fpbrm58zk {
  stop-color: var(--svg-color--6e5148, #6E5148);
}

.fsxm9dwni {
  d: path("M10.69 18.736a4.26 4.26 0 0 0 4.23 3.708h2.055a4.26 4.26 0 0 0 4.23-3.708c.129-2.051.258-4.094.353-6.143a1.58 1.58 0 0 0-1.501-1.56h-1.525c-1.04 0-1.98-.613-2.408-1.57a.72.72 0 0 0-.67-.456H14.07c-2.01 0-3.638 1.647-3.638 3.68c0 2.025.126 4.018.26 6.049");
}

.ft5dv1b6b {
  fill: none;
}

.fv_h9xbci {
  d: path("M21.408 16.484q.063-1.035.12-2.072a1.04 1.04 0 0 1-.12 2.072");
}

.g0a9imbkr {
  stop-color: var(--svg-color--866253, #866253);
}

.g1bdywbbk {
  stop-color: var(--svg-color--ad4002, #AD4002);
}

.g5jsf5l8p {
  stop-color: var(--svg-color--643b36, #643B36);
}

.gd0ml22cv {
  stop-color: var(--svg-color--98746f, #98746F);
}

.gfer3rbfb {
  d: path("M19.186 15.206a.9.9 0 0 0-.252-.504l-.282.31l.127.25z");
}

.gg4pweb1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.492 4.303c-.43-.11-1.28-.203-2.296-.078");
}

.gpxc7t0si {
  stop-color: var(--svg-color--744b44, #744B44);
}

.gulr-t6qo {
  fill: var(--svg-color--2a0e27, #2A0E27);
  d: path("M16.222 9.305a3 3 0 0 1-.072-.15a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.823 1.647-3.823 3.68v.299c-.37-.282-.676-.57-.676-1.53c0-1.61 2.705-3.59 4.105-3.96a6 6 0 0 1 1.723-.178c.468.017.8.42.805.888l.016 1.391z");
}

.gv_f6obqq {
  stop-color: var(--svg-color--866253, #866253);
  stop-opacity: 0;
}

.gxxikzvvd {
  stop-color: var(--svg-color--773c50, #773C50);
  stop-opacity: 0;
}

.gyc1lm0xs {
  width: 4.615px;
  height: 6.587px;
  x: 13.663px;
  y: 17.985px;
  rx: 2.307px;
}

.h-jczlzen {
  d: path("M21.236 17.086c.365-.011.706-.135.985-.336v1.014c0 .972-.58 1.839-1.46 2.198q.28-.594.376-1.285z");
}

.h38v_uqzc {
  stop-color: var(--svg-color--785b4f, #785B4F);
  stop-opacity: 0;
}

.h3lnwrb9u {
  stop-color: var(--svg-color--724943, #724943);
  stop-opacity: 0;
}

.h9fb5bbiv {
  stop-color: var(--svg-color--ffa143, #FFA143);
}

.h9nb3dbmm {
  d: path("m15.527 14.948l-.579 2.001c-.118.412.165.823.567.823h.856c.402 0 .685-.418.567-.823l-.579-2.002c-.124-.443-.702-.443-.832 0");
}

.hdcvmhbib {
  stop-color: var(--svg-color--7a5651, #7A5651);
}

.hi0vjzatb {
  d: path("M18.321 14.362a.972.972 0 0 1 .936 1.228H17.38a.975.975 0 0 1 .94-1.228");
}

.hiycpfc4f {
  stop-color: var(--svg-color--ff711c, #FF711C);
}

.huk-m1bdc {
  stop-color: var(--svg-color--724943, #724943);
}

.hwvoaqesi {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.34 14.066a1.52 1.52 0 0 0-1.475 1.153a.3.3 0 0 0 .291.371h2.43a.25.25 0 0 0 .247-.296a1.525 1.525 0 0 0-1.493-1.228");
}

.hxfs4uq1u {
  stop-color: var(--svg-color--826559, #826559);
  stop-opacity: 0;
}

.hy82m0yne {
  stop-color: var(--svg-color--703f39, #703F39);
  stop-opacity: 0;
}

.i-377o6ky {
  d: path("M7.307 5.365c-.203-.057-.677-.154-.945-.086c-.336.086-.594.329-.813.688c-.175.287-1.469 2.48-2.094 3.539c-.562.823-1.625 3.088-1.375 5.563c.1 1.662.782 3.338 1.11 3.968l4.132 7.855c.173.33.187.719.08 1.076c-.157.529-.322 1.28-.322 2.022h17.828c0-.743-.164-1.493-.322-2.022a1.43 1.43 0 0 1 .08-1.076l4.133-7.855c.328-.63 1.01-2.306 1.11-3.968c.25-2.476-.813-4.74-1.375-5.563a915 915 0 0 0-2.094-3.54c-.219-.358-.477-.6-.813-.687c-.268-.068-.742.03-.945.086L21.494 7.53c-.351.415-.19.967-.054 1.18l2.075 3.512a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a14 14 0 0 0-1.12-.484a4.3 4.3 0 0 1-.775.336v.024a2.307 2.307 0 1 1-4.614 0v-.01a4.3 4.3 0 0 1-.782-.328c-.395.155-.762.312-1.064.462a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382l2.075-3.512c.136-.213.297-.765-.055-1.18z");
}

.i2_v3t4-e {
  stop-color: var(--svg-color--957870, #957870);
  stop-opacity: 0;
}

.i4c630b-n {
  stop-color: var(--svg-color--8e6762, #8E6762);
}

.ib6gywlbs {
  stop-color: var(--svg-color--8f6a64, #8F6A64);
  stop-opacity: 0;
}

.igdnfmbpz {
  stop-color: var(--svg-color--5a4947, #5A4947);
  stop-opacity: 0;
}

.igo7pk_ym {
  d: path("M9.51 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.968 1.625 3.038 2.013q.017.006.034.006c.941-.005 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.219.696-.414c.063-.133.064-.316-.03-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .057-.625c.156-.062.336-.304.312-.648c-.037-.538-.562-.662-.781-.656H14.9c.012-.55-.585-.6-.815-.575l-1.717.098a.98.98 0 0 0-.765-.133c-.432.123-1.264.339-2.094 1.047");
}

.iiih_t14k {
  stop-color: var(--svg-color--856061, #856061);
}

.ipg0cn99k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.295 5.381c.273-.102 1.101-.305 2.171-.242");
}

.iskwzzbgz {
  stop-color: var(--svg-color--866555, #866555);
}

.j-racdxto {
  stop-color: var(--svg-color--19040c, #19040C);
  stop-opacity: 0;
}

.j1090kf1c {
  stop-color: var(--svg-color--ff6428, #FF6428);
  stop-opacity: 0;
}

.j26seachc {
  stop-color: var(--svg-color--ff8547, #FF8547);
}

.j2t7368de {
  stop-color: var(--svg-color--ef6736, #EF6736);
}

.j664pvbhu {
  stop-color: var(--svg-color--6e5148, #6E5148);
  stop-opacity: 0;
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jp6tlutdp {
  stop-color: var(--svg-color--3c312e, #3C312E);
}

.jss2kw0gn {
  stop-color: var(--svg-color--8d5a50, #8D5A50);
}

.jtm80bvmo {
  stop-color: var(--svg-color--19040c, #19040C);
}

.jwb4ndb5j {
  stop-color: var(--svg-color--856152, #856152);
}

.jx3zfg-wy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.654 4.303c.43-.11 1.281-.203 2.297-.078");
}

.jx57xnbtd {
  stop-color: var(--svg-color--85575e, #85575E);
}

.k05e99b6a {
  stop-color: var(--svg-color--856253, #856253);
}

.k999twbbe {
  stop-color: var(--svg-color--393333, #393333);
}

.kave1bcji {
  stop-color: var(--svg-color--542a30, #542A30);
  stop-opacity: 0;
}

.kg5wfpbcx {
  stop-color: var(--svg-color--413735, #413735);
}

.ks6l0q0jc {
  stop-color: var(--svg-color--805d55, #805D55);
  stop-opacity: 0;
}

.kyvc_ob9l {
  stop-color: var(--svg-color--704740, #704740);
}

.l1tokglcj {
  stop-color: var(--svg-color--865352, #865352);
  stop-opacity: 0;
}

.l2846gaef {
  stop-color: var(--svg-color--856253, #856253);
  stop-opacity: 0;
}

.l4dfd7h4n {
  fill: var(--svg-color--2e1f1e, #2E1F1E);
  fill-rule: evenodd;
  d: path("M13.964 12.624c-.79-.126-1.468.194-1.69.355a.275.275 0 1 1-.323-.445c.31-.226 1.134-.608 2.1-.453a.275.275 0 1 1-.087.543");
}

.l5z8v8buo {
  stop-color: var(--svg-color--532220, #532220);
}

.l9mu020_s {
  d: path("m21.618 12.986l-.032-.687c-.011-.832-.698-1.518-1.53-1.553h-1.524c-1.237 0-1.936-.897-2.273-1.948c-.236-.735.631-1.32 1.395-1.215c.905.126 1.914.21 3.342 1.142c1.899 1.239 1.622 3.21.622 4.26");
}

.lfjjhubys {
  stop-color: var(--svg-color--413735, #413735);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lulnx3bbe {
  cx: 13.272px;
  cy: 14.777px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.424px;
  ry: 0.215px;
}

.luzwsybtw {
  stop-color: var(--svg-color--642d32, #642D32);
}

.m_2922ixt {
  stop-color: var(--svg-color--9d4635, #9D4635);
}

.m57mo2r3b {
  stop-color: var(--svg-color--937262, #937262);
  stop-opacity: 0;
}

.mdoiiwbdb {
  stop-color: var(--svg-color--3f2e34, #3F2E34);
  stop-opacity: 0;
}

.mqq2pckgy {
  stop-color: var(--svg-color--ff711c, #FF711C);
  stop-opacity: 0;
}

.msdhbgd-s {
  fill: var(--svg-color--2e1f1e, #2E1F1E);
  fill-rule: evenodd;
  d: path("M17.922 12.624c.79-.126 1.468.194 1.69.355a.275.275 0 1 0 .323-.445c-.31-.226-1.134-.608-2.1-.453a.275.275 0 0 0 .087.543");
}

.mxpallb1y {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.25 14.568c.069.092-.076.205-.24.328c-.165.123-.287.21-.356.117c-.07-.092.008-.267.172-.39c.165-.123.354-.148.424-.055");
}

.n1zjiicmq {
  stop-color: var(--svg-color--785b4f, #785B4F);
}

.nddsbvhqr {
  stop-color: var(--svg-color--8c5e58, #8C5E58);
  stop-opacity: 0;
}

.nh2kw4_uc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.07 3.186c-.68-.344-2.469-.57-3.188-.524");
}

.nh7q47k8r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.711 4.465c.46-.173 1.847-.438 3.354-.346");
}

.nrnvctv1v {
  d: path("M10.45 13.714a1.75 1.75 0 0 0-1.515 1.723c0 .935.733 1.699 1.656 1.749a84 84 0 0 1-.14-3.472");
}

.o42fgjhpg {
  stop-color: var(--svg-color--703f39, #703F39);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oey3hsxgc {
  stop-color: var(--svg-color--5d2d33, #5D2D33);
}

.ol4pjzgjs {
  fill: var(--svg-color--2b1d20, #2B1D20);
  d: path("M21.229 8.493a2.53 2.53 0 0 1 1.38 1.145a2.58 2.58 0 0 1-.116 2.75a1.7 1.7 0 0 0-.294.952v1.294a1.9 1.9 0 0 0-.727-.292l.086-1.75a1.58 1.58 0 0 0-1.502-1.559h-1.524c-1.04 0-1.98-.613-2.408-1.57a.72.72 0 0 0-.67-.456h-1.386c-2.01 0-3.638 1.647-3.638 3.68l.034 1.673c-.277.04-.566.133-.784.287V13.34c0-.339-.104-.671-.295-.952a2.6 2.6 0 0 1-.156-2.663A2.55 2.55 0 0 1 10.644 8.5c.624-.222 1.026-.607 1.378-1.174c.45-.718 1.37-1.232 2.277-1.232c.353 0 .687.046.999.174c.416.181.883.181 1.299 0c.306-.128.641-.174.994-.174c.918 0 1.72.497 2.165 1.232c.335.555.86.958 1.473 1.168");
}

.owipfybjq {
  stop-color: var(--svg-color--250e14, #250E14);
}

.oxual4umn {
  stop-color: var(--svg-color--826559, #826559);
}

.pa_nigs1j {
  stop-color: var(--svg-color--5a4947, #5A4947);
}

.pa76eg1ox {
  stop-color: var(--svg-color--532220, #532220);
  stop-opacity: 0;
}

.pistvdbbt {
  stop-color: var(--svg-color--5a2c32, #5A2C32);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppk0kktky {
  d: path("M21.302 17.185q.108-1.736.2-3.474a1.753 1.753 0 0 1-.2 3.474");
}

.pr8brkb_h {
  stop-color: var(--svg-color--ff7840, #FF7840);
  stop-opacity: 0;
}

.pz46uffpz {
  stop-color: var(--svg-color--443939, #443939);
  stop-opacity: 0;
}

.q2wcuxbjh {
  stop-color: var(--svg-color--684034, #684034);
  stop-opacity: 0;
}

.q7_s_7b5y {
  stop-color: var(--svg-color--7d4757, #7D4757);
  stop-opacity: 0;
}

.qbu0-dbjp {
  stop-color: var(--svg-color--613a35, #613A35);
  stop-opacity: 0;
}

.qd38sjb7e {
  stop-color: var(--svg-color--ff7532, #FF7532);
  stop-opacity: 0;
}

.qetg81_po {
  stop-color: var(--svg-color--ff8543, #FF8543);
  stop-opacity: 0;
}

.qh77xqbfv {
  stop-color: var(--svg-color--856061, #856061);
  stop-opacity: 0;
}

.qnsxe8b8l {
  stop-color: var(--svg-color--6d3d43, #6D3D43);
}

.qso4uy3-n {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
}

.qy05b9bsw {
  stop-color: var(--svg-color--494748, #494748);
}

.r20qsbc_c {
  stop-color: var(--svg-color--9b7565, #9B7565);
}

.ram2tx4_p {
  stop-color: var(--svg-color--744b44, #744B44);
  stop-opacity: 0;
}

.rrphcb4zv {
  d: path("M22.637 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .027.054c.032.573-1.969 1.625-3.039 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.726-.336-1.476-.309-1.867-.309c-.39 0-.602-.219-.695-.414c-.064-.133-.065-.316.029-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.056-.625c-.157-.062-.337-.304-.313-.648c.038-.538.592-.465.81-.46l.136-.196c-.013-.55.585-.6.814-.575l1.717.098a.98.98 0 0 1 .766-.133c.432.123 1.263.339 2.093 1.047");
}

.rsdjdrd8e {
  stop-color: var(--svg-color--ff8547, #FF8547);
  stop-opacity: 0;
}

.rsxq6wbbl {
  stop-color: var(--svg-color--997369, #997369);
  stop-opacity: 0;
}

.spq9hx54c {
  stop-color: var(--svg-color--684034, #684034);
}

.tdhijwbfm {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
  stop-opacity: 0;
}

.tiwzfl9rq {
  stop-color: var(--svg-color--6d3d43, #6D3D43);
  stop-opacity: 0;
}

.tpbiu1b7n {
  stop-color: var(--svg-color--93625b, #93625B);
  stop-opacity: 0;
}

.u-qvctb2c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.852 5.381c-.274-.102-1.102-.305-2.172-.242");
}

.u7dfrl2ct {
  stop-color: var(--svg-color--773c50, #773C50);
}

.uaxsyh7oh {
  fill: var(--svg-color--000, #000);
  d: path("M14.122 15.334a.554.554 0 0 0-.557-.557a.554.554 0 0 0-.494.813h.985a.55.55 0 0 0 .066-.256");
}

.ugjqw0bgi {
  stop-color: var(--svg-color--997369, #997369);
}

.upoucm8pi {
  stop-color: var(--svg-color--443939, #443939);
}

.usrzeqb5b {
  stop-color: var(--svg-color--5d292e, #5D292E);
}

.uuj2cmbsf {
  fill: var(--svg-color--75454a, #75454A);
  d: path("m15.414 15.16l-.691 2.002c-.119.412.165.823.566.823h.857c.401 0 .684-.418.566-.823l-.578-2.001c-.124-.444-.59-.444-.72 0");
}

.uz3hg9bsf {
  d: path("M22.637 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .027.054c.032.573-1.969 1.625-3.039 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.726-.336-1.476-.309-1.867-.309c-.39 0-.602-.219-.695-.414c-.064-.133-.065-.316.029-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.056-.625c-.157-.062-.337-.304-.313-.648c.038-.538.563-.662.782-.656h.164c-.013-.55.585-.6.814-.575l1.717.098a.98.98 0 0 1 .766-.133c.432.123 1.263.339 2.093 1.047");
}

.v61f_wbit {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.077 3.186c.68-.344 2.468-.57 3.187-.524");
}

.vah6rkr4l {
  stop-color: var(--svg-color--937262, #937262);
}

.vdsilzblf {
  stop-color: var(--svg-color--3a3636, #3A3636);
  stop-opacity: 0;
}

.vj5muxz_t {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
}

.vtekkxd_w {
  d: path("m24.755 4.635l.428.666a.24.24 0 0 1-.01.278c-.9 1.155-2.374 1.801-3.283 2.087a.244.244 0 0 1-.281-.107a22 22 0 0 1-.409-.69c-.069-.131.029-.232.086-.265L24.3 4.775l-.124-.273c.35-.106.53.044.578.133");
}

.vxljdps-k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.845 3.48c.46-.173 1.847-.439 3.353-.347");
}

.w0t99db7r {
  stop-color: var(--svg-color--71404c, #71404C);
  stop-opacity: 0;
}

.wgy-qlbik {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.83 3.08c.434-.236 2.033-.622 3.539-.722");
}

.wiieli2ej {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.546 14.066c.711 0 1.312.49 1.475 1.153a.298.298 0 0 1-.291.371H17.3a.25.25 0 0 1-.247-.296a1.52 1.52 0 0 1 1.493-1.228");
}

.woz3hacrx {
  stop-color: var(--svg-color--ad4002, #AD4002);
  stop-opacity: 0;
}

.wsfk1t4wo {
  stop-color: var(--svg-color--423137, #423137);
}

.wu2h8jb4k {
  d: path("M13.565 14.362a.972.972 0 0 0-.936 1.228h1.877a1 1 0 0 0 .035-.256a.98.98 0 0 0-.976-.972");
}

.wz834g6bz {
  stop-color: var(--svg-color--64373f, #64373F);
}

.x05lq4b2v {
  stop-color: var(--svg-color--ef6736, #EF6736);
  stop-opacity: 0;
}

.xz29lgbft {
  fill: var(--svg-color--89004e, #89004E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.446 18.332c.44.23.965.36 1.524.36a3.3 3.3 0 0 0 1.524-.36a.22.22 0 0 1 .263.043a.205.205 0 0 1 .023.262m-3.334-.305l3.292.277m-3.292-.277a.22.22 0 0 0-.263.045a.2.2 0 0 0-.022.26m.285-.305l-.244.277m3.578.028l-.042-.027m.042.027l-.042-.027m.042.027c-.383.58-1.05.967-1.81.967s-1.426-.386-1.81-.966m3.578-.029a2.11 2.11 0 0 1-1.768.945a2.11 2.11 0 0 1-1.768-.944m-.041.027v.001l.04-.029m-.04.028l.04-.027");
}

.xzobpebba {
  stop-color: var(--svg-color--957870, #957870);
}

.y1z543b6m {
  stop-color: var(--svg-color--ff8543, #FF8543);
}

.ycd3jvtwj {
  stop-color: var(--svg-color--393333, #393333);
  stop-opacity: 0;
}

.ygjg_lb-n {
  d: path("M10.459 14.422a1.04 1.04 0 0 0 .09 2.046a85 85 0 0 1-.09-2.046");
}

.yj9m5xbqx {
  stop-color: var(--svg-color--7d4757, #7D4757);
}

.ym0brebyc {
  stop-color: var(--svg-color--ff6a31, #FF6A31);
}

.yo0f3rety {
  stop-color: var(--svg-color--5e3537, #5E3537);
}

.z_e7pbcya {
  stop-color: var(--svg-color--423137, #423137);
  stop-opacity: 0;
}

.z1x4vc35k {
  stop-color: var(--svg-color--613a35, #613A35);
}

.z9pz_x6lh {
  stop-color: var(--svg-color--98746f, #98746F);
  stop-opacity: 0;
}

.zdhvrqmhr {
  stop-color: var(--svg-color--93625b, #93625B);
}

.ze-agacxi {
  d: path("M10.65 17.086a1.8 1.8 0 0 1-.984-.336v1.014c0 .972.579 1.839 1.46 2.198a4.5 4.5 0 0 1-.377-1.285z");
}

.ze5ugdbxr {
  stop-color: var(--svg-color--ff7840, #FF7840);
}

.zoedh-kcq {
  stop-color: var(--svg-color--623f42, #623F42);
}

</style>
