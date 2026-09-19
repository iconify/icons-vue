<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iZZXosk)" class="n6umd-8wf"/><path fill="url(#it5H58d)" class="n6umd-8wf"/><path fill="url(#iB984zb)" class="z3r4yfb1i"/><path fill="url(#iK0Kggb)" class="q4tn1k0pt"/><g filter="url(#iRjAVNc)"><path stroke="url(#iEqb4OX)" class="c84sbdcdc"/></g><path fill="url(#iD0KNNc)" class="qqohlvbcu"/><path fill="url(#idACNGL)" class="qqohlvbcu"/><path fill="url(#ifiEDQb)" class="qqohlvbcu"/><path fill="url(#iOGlzod)" class="qqohlvbcu"/><g filter="url(#izgjomb)"><ellipse transform="rotate(-23.4 23.418 9.91)" class="rr70jqe_l"/></g><g filter="url(#iYQD0rd)"><path class="qnz8b090o"/></g><g filter="url(#iKyonie)"><path class="uy70yzmbt"/></g><path fill="url(#iyzAeli)" class="crgr_sy3k"/><path fill="url(#iWdA2Jb)" class="crgr_sy3k"/><path fill="url(#icCjRLd)" class="crgr_sy3k"/><path fill="url(#ipGFJ0c)" class="crgr_sy3k"/><g filter="url(#iCSNq7b)"><path stroke="url(#i4hRjGb)" class="q6qj69lfx"/></g><g filter="url(#i4FdCIb)"><path stroke="url(#iZQBzLc)" class="hpwp6sbnw"/></g><g filter="url(#iUE5oCm)"><path stroke="url(#i0Lwape)" class="got_y4bcm"/></g><g filter="url(#iUsAaPd)"><path stroke="url(#i3qkUFc)" class="qcbmo3b6x"/></g><g filter="url(#iQweJOc)"><rect class="dzdowjbsg"/></g><g filter="url(#ilXpKiC)"><rect class="p5x69hxwb"/></g><rect fill="url(#ixWJoNH)" class="it3s3hbgk"/><rect fill="url(#i17qjeb)" class="it3s3hbgk"/><rect fill="url(#iLoB7Tc)" class="vo38q3bgp"/><rect fill="url(#i1MxZ7c)" class="vo38q3bgp"/><g filter="url(#i8Dewqe)"><rect class="x31kd8bmz"/></g><rect fill="url(#ixvIiIe)" class="sqcq8ybeh"/><rect fill="url(#iNdH3ux)" class="sqcq8ybeh"/><circle fill="url(#i5FAX3c)" class="liejmwbeq"/><circle fill="url(#isRBXsb)" class="o9c8hnbkt"/><g filter="url(#iPbqgJd)"><circle class="fntwfcc5d"/></g><g filter="url(#iftWU8b)"><circle class="u85lrhbmd"/></g><g filter="url(#izHFa2b)"><path stroke="url(#ik7Oxdb)" class="il925c-yb"/></g><rect fill="url(#i1Zonli)" transform="scale(1 -1)rotate(-59.424 -11.293 -17.086)" class="imv1jj11w"/><rect fill="url(#irKkGDb)" transform="scale(1 -1)rotate(-59.424 -11.293 -17.086)" class="imv1jj11w"/><rect fill="url(#itKPg7c)" transform="scale(1 -1)rotate(-59.424 -11.293 -17.086)" class="imv1jj11w"/><rect fill="url(#iKielJe)" transform="scale(1 -1)rotate(-7.275 -181.534 -84.843)" class="alz950-ad"/><g filter="url(#iLSm0Rc)"><path class="nbtt56b4o"/></g><rect fill="url(#im3jRGb)" transform="scale(1 -1)rotate(-59.424 -13.959 -21.138)" class="imv1jj11w"/><rect fill="url(#i28Yc3c)" transform="scale(1 -1)rotate(-59.424 -13.959 -21.138)" class="imv1jj11w"/><rect fill="url(#iZrDpRJ)" transform="scale(1 -1)rotate(-59.424 -13.959 -21.138)" class="imv1jj11w"/><rect fill="url(#inn0tAb)" transform="scale(1 -1)rotate(-59.424 -13.959 -21.138)" class="imv1jj11w"/><rect fill="url(#i6tJbtd)" transform="scale(1 -1)rotate(-59.424 -12.288 -19.333)" class="q8vi0hbch"/><rect fill="url(#iBWmurc)" transform="scale(1 -1)rotate(-59.424 -12.288 -19.333)" class="q8vi0hbch"/><g filter="url(#ijw9nxb)"><path class="p0pgtybjg"/></g><g filter="url(#iKu92ve)"><path class="d2w_msw-o"/></g><g filter="url(#iluqvBb)"><path class="s1-80if6l"/></g><g filter="url(#ihPSJUv)"><path class="g96opbeoa"/></g><path fill="url(#isu0aPe)" class="we9f_j1si"/><path fill="url(#ieyyS0b)" class="we9f_j1si"/><path fill="url(#iKHxkwd)" class="we9f_j1si"/><path fill="url(#iTUP2ue)" class="we9f_j1si"/><path fill="url(#iBlHuac)" class="we9f_j1si"/><path fill="url(#iN2FHjT)" class="we9f_j1si"/><g filter="url(#i1tFkPc)" class="mc2zb0bvp"><rect fill="url(#iTrJtrc)" transform="scale(-1 1)rotate(-59.424 10.023 23.504)" class="a3b5ivb2o"/></g><path fill="url(#idhpF3c)" class="huaau96bm"/><rect fill="url(#ivqDwFc)" transform="rotate(120.576 23.095 18.108)" class="axpc9z9fg"/><rect fill="url(#ig3M2Ie)" transform="rotate(120.576 23.095 18.108)" class="axpc9z9fg"/><rect fill="url(#isfyfud)" transform="rotate(120.576 23.095 18.108)" class="axpc9z9fg"/><rect fill="url(#iVgafDc)" transform="rotate(172.725 22.975 23.66)" class="dbd109bmz"/><rect fill="url(#invcAfd)" transform="rotate(120.576 20.916 22.393)" class="vrzzu0qhm"/><rect fill="url(#iMdTyDF)" transform="rotate(120.576 20.916 22.393)" class="vrzzu0qhm"/><rect fill="url(#im9SBzv)" transform="rotate(120.576 20.916 22.393)" class="vrzzu0qhm"/><rect fill="url(#iLxcuVc)" transform="rotate(120.576 20.916 22.393)" class="vrzzu0qhm"/><rect fill="url(#ikw31Sc)" transform="rotate(120.576 21.649 20.068)" class="pq2xikbvb"/><rect fill="url(#ivv35ad)" transform="rotate(120.576 21.649 20.068)" class="pq2xikbvb"/><g filter="url(#iz9B90c)"><path class="vh8pidbig"/></g><g filter="url(#icMgT2b)"><path class="w2g84vbed"/></g><g filter="url(#iRwwR3c)"><path class="gpn4-bydf"/></g><g filter="url(#iOJoUVj)"><path class="xhq4p5b6u"/></g><path fill="url(#ildqvrd)" class="hhcsq5cbe"/><path fill="url(#io5xKOc)" class="hhcsq5cbe"/><path fill="url(#i900rQc)" class="hhcsq5cbe"/><path fill="url(#iGQeFMb)" class="hhcsq5cbe"/><path fill="url(#ivsshSd)" class="hhcsq5cbe"/><g filter="url(#iDLyfob)"><rect fill="url(#iPQ5s5c)" transform="rotate(-59.424 17.081 18.823)" class="rdbzxqbqj"/></g><g filter="url(#if7wCpb)"><path class="uuuiv4j7f"/></g><path fill="url(#iHwKQqc)" class="ilz9nndwh"/></g><defs><linearGradient id="iZZXosk" x1="6.516" x2="6.516" y1="10.175" y2="21.112" gradientUnits="userSpaceOnUse"><stop class="ck7f4woko"/><stop offset="1" class="eiejd2bux"/></linearGradient><linearGradient id="it5H58d" x1="6.516" x2="6.516" y1="13.425" y2="21.612" gradientUnits="userSpaceOnUse"><stop class="ua19fnf6s"/><stop offset="1" class="qb49ptbxt"/></linearGradient><linearGradient id="iK0Kggb" x1="25.433" x2="25.433" y1="11.362" y2="21.612" gradientUnits="userSpaceOnUse"><stop offset=".094" class="i3zfssahs"/><stop offset="1" class="tklvtbcin"/></linearGradient><linearGradient id="idACNGL" x1="16" x2="16" y1="14.395" y2="31.252" gradientUnits="userSpaceOnUse"><stop class="m4eoz0qca"/><stop offset="1" class="qt5w41b2y"/></linearGradient><linearGradient id="iyzAeli" x1="16" x2="16" y1="5.87" y2="23.917" gradientUnits="userSpaceOnUse"><stop class="yrar24m3w"/><stop offset=".188" class="i3zfssahs"/><stop offset=".895" class="ppkfmqblg"/></linearGradient><linearGradient id="iWdA2Jb" x1="16" x2="16" y1="13.452" y2="23.191" gradientUnits="userSpaceOnUse"><stop class="rqliug_er"/><stop offset="1" class="g8586jk9w"/></linearGradient><linearGradient id="i4hRjGb" x1="6.646" x2="4.184" y1="20.553" y2="7.884" gradientUnits="userSpaceOnUse"><stop class="p9uo3pblo"/><stop offset=".503" class="qf38a13vx"/><stop offset="1" class="p9uo3pblo"/></linearGradient><linearGradient id="iZQBzLc" x1="24.978" x2="28.269" y1="19.925" y2="11.984" gradientUnits="userSpaceOnUse"><stop class="v3_xnsbbc"/><stop offset=".296" class="oi7ddwbfc"/><stop offset=".808" class="v3_xnsbbc"/></linearGradient><linearGradient id="i0Lwape" x1="24.528" x2="20.916" y1="11.802" y2="6.384" gradientUnits="userSpaceOnUse"><stop class="g-3jcm1lb"/><stop offset=".557" class="mebto9quo"/><stop offset="1" class="g-3jcm1lb"/></linearGradient><linearGradient id="i3qkUFc" x1="22.767" x2="22.087" y1="19.679" y2="15.605" gradientUnits="userSpaceOnUse"><stop offset=".026" class="g-3jcm1lb"/><stop offset="1" class="mebto9quo"/></linearGradient><linearGradient id="ixWJoNH" x1="15.811" x2="11.128" y1="10.282" y2="10.282" gradientUnits="userSpaceOnUse"><stop class="dcdi0_bfz"/><stop offset=".568" class="ixqsitb8q"/><stop offset=".766" class="whjaerb5v"/></linearGradient><linearGradient id="i17qjeb" x1="13.109" x2="13.109" y1="10.11" y2="12.648" gradientUnits="userSpaceOnUse"><stop offset=".327" class="n7wvbnb3x"/><stop offset="1" class="whjaerb5v"/></linearGradient><linearGradient id="iLoB7Tc" x1="22.327" x2="17.644" y1="10.282" y2="10.282" gradientUnits="userSpaceOnUse"><stop class="dcdi0_bfz"/><stop offset=".568" class="ixqsitb8q"/><stop offset=".766" class="whjaerb5v"/></linearGradient><linearGradient id="i1MxZ7c" x1="19.625" x2="19.625" y1="10.11" y2="12.648" gradientUnits="userSpaceOnUse"><stop offset=".327" class="n7wvbnb3x"/><stop offset="1" class="whjaerb5v"/></linearGradient><linearGradient id="ixvIiIe" x1="16" x2="16" y1="13.357" y2="15.495" gradientUnits="userSpaceOnUse"><stop class="sq6bhdbbn"/><stop offset="1" class="p6w626lsj"/></linearGradient><linearGradient id="iNdH3ux" x1="15.493" x2="14.753" y1="18.292" y2="14.677" gradientUnits="userSpaceOnUse"><stop offset=".07" class="xh0ps3bnm"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="ik7Oxdb" x1="17.68" x2="17.68" y1="13.96" y2="14.683" gradientUnits="userSpaceOnUse"><stop class="g-3jcm1lb"/><stop offset=".349" class="vpk0l0bon"/></linearGradient><linearGradient id="irKkGDb" x1="5.815" x2="1.148" y1="4.018" y2="4.518" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ypq_y2bvs"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="itKPg7c" x1="3.499" x2="1.977" y1="5.104" y2="5.224" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="iKielJe" x1="1.767" x2=".985" y1="8.105" y2="5.245" gradientUnits="userSpaceOnUse"><stop class="xgbxb0f0n"/><stop offset=".831" class="nkw7_sb2b"/></linearGradient><linearGradient id="i28Yc3c" x1="6.555" x2="-1.043" y1="2.715" y2="6.446" gradientUnits="userSpaceOnUse"><stop offset=".386" class="y4ijtcxdz"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="iZrDpRJ" x1="3.824" x2=".999" y1="5.247" y2="5.34" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="inn0tAb" x1=".303" x2="1.354" y1="5.133" y2="5.26" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="iBWmurc" x1="7.922" x2=".48" y1="3.743" y2="4.517" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ypq_y2bvs"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="isu0aPe" x1="6.963" x2="6.587" y1="14.463" y2="21.934" gradientUnits="userSpaceOnUse"><stop class="lyklk88ly"/><stop offset="1" class="eh2madfru"/></linearGradient><linearGradient id="iKHxkwd" x1="11.85" x2="7.013" y1="28.789" y2="21.197" gradientUnits="userSpaceOnUse"><stop offset=".114" class="he8j2s-gt"/><stop offset="1" class="m4eoz0qca"/></linearGradient><linearGradient id="iTrJtrc" x1=".868" x2=".868" y1="0" y2="12.118" gradientUnits="userSpaceOnUse"><stop class="sc0snxbpi"/><stop offset="1" class="c8z2d5d6a"/></linearGradient><linearGradient id="idhpF3c" x1="15.123" x2="13.526" y1="17.108" y2="17.756" gradientUnits="userSpaceOnUse"><stop class="iwdm90bel"/><stop offset="1" class="z-2ijsx5t"/></linearGradient><linearGradient id="ig3M2Ie" x1="26.514" x2="23.773" y1="22.797" y2="24.622" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ypq_y2bvs"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="isfyfud" x1="26.594" x2="25.073" y1="23.212" y2="23.332" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="iVgafDc" x1="23.55" x2="25.608" y1="31.136" y2="31.654" gradientUnits="userSpaceOnUse"><stop class="cqx30cy3u"/><stop offset=".756" class="t2i434iwt"/></linearGradient><linearGradient id="iMdTyDF" x1="24.099" x2="18.302" y1="24.111" y2="31.401" gradientUnits="userSpaceOnUse"><stop class="cei85q-8g"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="im9SBzv" x1="24.529" x2="23.849" y1="27.051" y2="27.035" gradientUnits="userSpaceOnUse"><stop class="rnq27fbef"/><stop offset="1" class="t7bltqbvv"/></linearGradient><linearGradient id="iLxcuVc" x1="21.22" x2="22.27" y1="27.527" y2="27.654" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="ivv35ad" x1="25.089" x2="21.298" y1="23.549" y2="26.81" gradientUnits="userSpaceOnUse"><stop offset=".259" class="rkbd28wnq"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="ildqvrd" x1="26.17" x2="23.401" y1="19.744" y2="24.575" gradientUnits="userSpaceOnUse"><stop class="lyklk88ly"/><stop offset="1" class="eh2madfru"/></linearGradient><linearGradient id="i900rQc" x1="18.461" x2="25.308" y1="30.785" y2="21.254" gradientUnits="userSpaceOnUse"><stop offset=".114" class="he8j2s-gt"/><stop offset="1" class="m4eoz0qca"/></linearGradient><linearGradient id="iPQ5s5c" x1="18.495" x2="18.495" y1="18.823" y2="30.942" gradientUnits="userSpaceOnUse"><stop class="sc0snxbpi"/><stop offset="1" class="c8z2d5d6a"/></linearGradient><linearGradient id="iHwKQqc" x1="17.134" x2="18.731" y1="17.098" y2="17.747" gradientUnits="userSpaceOnUse"><stop class="iwdm90bel"/><stop offset="1" class="z-2ijsx5t"/></linearGradient><filter id="iRjAVNc" width="4.75" height="9.763" x="26.187" y="8.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".2"/></filter><filter id="izgjomb" width="11.833" height="15.089" x="17.501" y="2.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation="1.75"/></filter><filter id="iYQD0rd" width="13.721" height="7.966" x="8.991" y=".388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation="1.75"/></filter><filter id="iKyonie" width="21.121" height="21.129" x="5.118" y="4.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation="1"/></filter><filter id="iCSNq7b" width="3.023" height="13.73" x="3.818" y="6.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".2"/></filter><filter id="i4FdCIb" width="2.477" height="11.2" x="25.57" y="9.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".2"/></filter><filter id="iUE5oCm" width="4.02" height="7.085" x="20.82" y="5.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".2"/></filter><filter id="iUsAaPd" width="2.619" height="6.931" x="20.97" y="13.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".2"/></filter><filter id="iQweJOc" width="3.625" height="5.25" x="10.685" y="8.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".5"/></filter><filter id="ilXpKiC" width="3.625" height="5.25" x="17.154" y="8.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".5"/></filter><filter id="i8Dewqe" width="7.344" height="4.418" x="12.102" y="12.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".5"/></filter><filter id="iPbqgJd" width="2.567" height="2.567" x="11.742" y="8.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".5"/></filter><filter id="iftWU8b" width="2.567" height="2.567" x="18.212" y="8.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".5"/></filter><filter id="izHFa2b" width="1.305" height="1.15" x="17.038" y="13.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".1"/></filter><filter id="iLSm0Rc" width="2.271" height="2.515" x="11.43" y="14.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".25"/></filter><filter id="ijw9nxb" width="4.051" height="3.326" x="14.754" y="15.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".375"/></filter><filter id="iKu92ve" width="4.742" height="3.563" x="15.141" y="18.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".375"/></filter><filter id="iluqvBb" width="4.126" height="3.453" x="13.476" y="13.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".375"/></filter><filter id="ihPSJUv" width="5.503" height="9.827" x="11.636" y="14.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".5"/></filter><filter id="i1tFkPc" width="15.675" height="12.017" x="1.816" y="16.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation="1.25"/></filter><filter id="iz9B90c" width="4.051" height="3.326" x="13.451" y="15.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".375"/></filter><filter id="icMgT2b" width="3.248" height="2.7" x="12.805" y="18.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".375"/></filter><filter id="iRwwR3c" width="4.126" height="3.453" x="14.655" y="13.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".375"/></filter><filter id="iOJoUVj" width="5.503" height="9.827" x="15.118" y="14.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".5"/></filter><filter id="iDLyfob" width="15.827" height="12.554" x="15.104" y="14.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation="1.25"/></filter><filter id="if7wCpb" width="2.251" height="2.525" x="19.96" y="14.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5131" stdDeviation=".25"/></filter><radialGradient id="iB984zb" cx="0" cy="0" r="1" gradientTransform="matrix(-11.25001 -11.12504 13.27885 -13.42801 10.385 20.05)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="tbqmcsbon"/><stop offset="1" class="d91dz_s7m"/></radialGradient><radialGradient id="iEqb4OX" cx="0" cy="0" r="1" gradientTransform="matrix(-5.49997 -6.31252 13.2979 -11.5862 29.02 17.518)" gradientUnits="userSpaceOnUse"><stop class="g-3jcm1lb"/><stop offset=".448" class="mebto9quo"/><stop offset="1" class="g-3jcm1lb"/></radialGradient><radialGradient id="iD0KNNc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.93739 18.417 -32.63847 -19.38316 24.26 7.925)" gradientUnits="userSpaceOnUse"><stop class="lyklk88ly"/><stop offset="1" class="j823ctb-q"/></radialGradient><radialGradient id="ifiEDQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 20.6725 -18.4611 0 16.006 11.432)" gradientUnits="userSpaceOnUse"><stop offset=".688" class="qudiit10p"/><stop offset="1" class="yw57-9naf"/></radialGradient><radialGradient id="iOGlzod" cx="0" cy="0" r="1" gradientTransform="rotate(126.103 10.803 9.307)scale(14.0013)" gradientUnits="userSpaceOnUse"><stop class="v290nq5uq"/><stop offset="1" class="ragfnwbnv"/></radialGradient><radialGradient id="icCjRLd" cx="0" cy="0" r="1" gradientTransform="rotate(159.382 11.808 6.948)scale(20.2335 27.146)" gradientUnits="userSpaceOnUse"><stop offset=".818" class="ovqobxb3d"/><stop offset="1" class="kt15-irns"/></radialGradient><radialGradient id="ipGFJ0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.00069 12.7039 -10.8463 -.00059 16 12.366)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="t9ynm6bcv"/><stop offset="1" class="iedbks3oi"/></radialGradient><radialGradient id="i5FAX3c" cx="0" cy="0" r="1" gradientTransform="rotate(133.174 4.31 10.484)scale(1.90311 1.14415)" gradientUnits="userSpaceOnUse"><stop class="sf_wn9jlw"/><stop offset="1" class="ixqsitb8q"/></radialGradient><radialGradient id="isRBXsb" cx="0" cy="0" r="1" gradientTransform="matrix(-.774 .94202 -1.47397 -1.21107 17.608 14.514)" gradientUnits="userSpaceOnUse"><stop class="go-58hbeq"/><stop offset="1" class="ixqsitb8q"/></radialGradient><radialGradient id="i1Zonli" cx="0" cy="0" r="1" gradientTransform="rotate(59.013 -4.25 2.95)scale(5.27251 20.0471)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="byswvb0yr"/><stop offset=".906" class="uexfrlbgb"/></radialGradient><radialGradient id="im3jRGb" cx="0" cy="0" r="1" gradientTransform="rotate(73.488 -2.562 3.35)scale(4.23632 16.1073)" gradientUnits="userSpaceOnUse"><stop class="qu6c0n3kh"/><stop offset="1" class="uexfrlbgb"/></radialGradient><radialGradient id="i6tJbtd" cx="0" cy="0" r="1" gradientTransform="matrix(.49622 6.35615 -22.99952 1.79556 1.31 4.855)" gradientUnits="userSpaceOnUse"><stop class="qu6c0n3kh"/><stop offset="1" class="uexfrlbgb"/></radialGradient><radialGradient id="ieyyS0b" cx="0" cy="0" r="1" gradientTransform="rotate(-68.461 25.15 11.24)scale(8.66893 8.83779)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="y7p5z931p"/><stop offset="1" class="m4eoz0qca"/></radialGradient><radialGradient id="iTUP2ue" cx="0" cy="0" r="1" gradientTransform="rotate(-9.846 145.569 1.388)scale(5.17453 5.27532)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="ekz-dyqpv"/><stop offset="1" class="yyc-z4k8n"/></radialGradient><radialGradient id="iBlHuac" cx="0" cy="0" r="1" gradientTransform="matrix(1.90818 2.90085 -18.42376 12.11914 6.469 19.08)" gradientUnits="userSpaceOnUse"><stop class="xf_16zgyk"/><stop offset=".437" class="m9wdx7_yx"/></radialGradient><radialGradient id="iN2FHjT" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73405 -5.05293 29.8015 -16.12504 12.01 27.385)" gradientUnits="userSpaceOnUse"><stop class="n43ik0btk"/><stop offset=".344" class="lv6eztbmt"/></radialGradient><radialGradient id="ivqDwFc" cx="0" cy="0" r="1" gradientTransform="rotate(59.013 -8.701 32.41)scale(5.27251 20.0471)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="byswvb0yr"/><stop offset=".906" class="uexfrlbgb"/></radialGradient><radialGradient id="invcAfd" cx="0" cy="0" r="1" gradientTransform="rotate(73.488 -7.102 28.556)scale(4.23633 16.1073)" gradientUnits="userSpaceOnUse"><stop class="qu6c0n3kh"/><stop offset="1" class="uexfrlbgb"/></radialGradient><radialGradient id="ikw31Sc" cx="0" cy="0" r="1" gradientTransform="matrix(.49622 6.35615 -22.99952 1.79556 22.96 24.924)" gradientUnits="userSpaceOnUse"><stop class="qu6c0n3kh"/><stop offset="1" class="uexfrlbgb"/></radialGradient><radialGradient id="io5xKOc" cx="0" cy="0" r="1" gradientTransform="rotate(-111.539 23.772 6.134)scale(8.66893 8.83779)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="y7p5z931p"/><stop offset="1" class="m4eoz0qca"/></radialGradient><radialGradient id="iGQeFMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90819 2.90085 -18.42374 -12.11917 25.788 19.07)" gradientUnits="userSpaceOnUse"><stop class="xf_16zgyk"/><stop offset=".437" class="m9wdx7_yx"/></radialGradient><radialGradient id="ivsshSd" cx="0" cy="0" r="1" gradientTransform="rotate(-61.583 33.092 -3.3)scale(5.74518 33.8843)" gradientUnits="userSpaceOnUse"><stop class="n43ik0btk"/><stop offset=".344" class="lv6eztbmt"/></radialGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:speak-no-evil-monkey" /></template>
<style>
.a3b5ivb2o {
  width: 1.735px;
  height: 12.118px;
  rx: 0.868px;
}

.alz950-ad {
  width: 3.269px;
  height: 9.295px;
  rx: 1.635px;
}

.axpc9z9fg {
  width: 3.081px;
  height: 9.295px;
  x: 23.095px;
  y: 18.108px;
  rx: 1.54px;
}

.bkm85hboo {
  stop-color: var(--svg-color--d79d95, #D79D95);
  stop-opacity: 0;
}

.byswvb0yr {
  stop-color: var(--svg-color--fbbeab, #FBBEAB);
}

.c84sbdcdc {
  stroke-linecap: round;
  stroke-opacity: 0.8;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M26.837 9.368c.98.148 2.874 1.438 3.293 3.51c.484 1.781-.172 4.062-1.672 4.953");
}

.c8z2d5d6a {
  stop-color: var(--svg-color--a07a76, #A07A76);
}

.cei85q-8g {
  stop-color: var(--svg-color--c558ae, #C558AE);
}

.ck7f4woko {
  stop-color: var(--svg-color--a67874, #A67874);
}

.cqx30cy3u {
  stop-color: var(--svg-color--ffc5b7, #FFC5B7);
}

.crgr_sy3k {
  d: path("M12.156 5.87a4.812 4.812 0 0 0-3.692 7.9a.55.55 0 0 1 .122.458a7.547 7.547 0 1 0 14.828 0a.55.55 0 0 1 .122-.458a4.812 4.812 0 0 0-3.692-7.9z");
}

.d2w_msw-o {
  fill: var(--svg-color--ffd5c9, #FFD5C9);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("m19.132 19.513l-.177-.299l-3.064 1.764l.177.299z");
}

.d91dz_s7m {
  stop-color: var(--svg-color--f39585, #F39585);
}

.dbd109bmz {
  width: 3.269px;
  height: 9.295px;
  x: 22.975px;
  y: 23.66px;
  rx: 1.635px;
}

.dcdi0_bfz {
  stop-color: var(--svg-color--432a3d, #432A3D);
}

.dzdowjbsg {
  width: 1.625px;
  height: 3.25px;
  x: 11.685px;
  y: 9.347px;
  fill: var(--svg-color--bb6f89, #BB6F89);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.813px;
}

.eh2madfru {
  stop-color: var(--svg-color--6b423e, #6B423E);
}

.eiejd2bux {
  stop-color: var(--svg-color--8f5872, #8F5872);
}

.ekz-dyqpv {
  stop-color: var(--svg-color--5a383a, #5A383A);
}

.fntwfcc5d {
  cx: 13.026px;
  cy: 9.712px;
  r: 0.284px;
  fill: var(--svg-color--795d72, #795D72);
}

.ft5dv1b6b {
  fill: none;
}

.g-3jcm1lb {
  stop-color: var(--svg-color--ffdacc, #FFDACC);
  stop-opacity: 0;
}

.g8586jk9w {
  stop-color: var(--svg-color--7d3838, #7D3838);
  stop-opacity: 0.5;
}

.g96opbeoa {
  fill: var(--svg-color--b16962, #B16962);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m14.425 15.746l-1.79 1.01l1.59 6.816c3.368-2.733 1.537-6.356.2-7.826");
}

.go-58hbeq {
  stop-color: var(--svg-color--3c2737, #3C2737);
}

.got_y4bcm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.42 6.485c1.296.51 3.69 2.496 2.495 5.885");
}

.gpn4-bydf {
  fill: var(--svg-color--ffd5c9, #FFD5C9);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m15.405 14.863l.364-.616l2.262 1.336l-.364.616z");
}

.he8j2s-gt {
  stop-color: var(--svg-color--923a7f, #923A7F);
}

.hhcsq5cbe {
  d: path("M18.92 15.641a.5.5 0 0 0-.684.177l-.594 1.004a6.75 6.75 0 0 0 2.378 9.245l3.535 2.088a4.208 4.208 0 1 0 4.281-7.247z");
}

.hpwp6sbnw {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M26.92 9.925c.83 3.28.75 7.562-.75 10");
}

.huaau96bm {
  d: path("m12.922 15.874l.414-.223a.5.5 0 0 1 .685.176l.593 1.005a6.75 6.75 0 0 1-.28 7.306c.697-1.78.754-4.11.142-5.808c-.323-.895-.956-1.927-1.555-2.456");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.i3zfssahs {
  stop-color: var(--svg-color--fab8a9, #FAB8A9);
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.il925c-yb {
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M17.243 13.972c.344-.07.82.187.875.71");
}

.ilz9nndwh {
  d: path("m19.335 15.865l-.414-.224a.5.5 0 0 0-.685.177l-.594 1.004a6.75 6.75 0 0 0 .281 7.306c-.698-1.78-.754-4.11-.142-5.808c.323-.895.956-1.927 1.554-2.456");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.imv1jj11w {
  width: 3.081px;
  height: 9.295px;
  rx: 1.54px;
}

.it3s3hbgk {
  width: 1.625px;
  height: 3.25px;
  x: 11.93px;
  y: 9.105px;
  rx: 0.813px;
}

.iwdm90bel {
  stop-color: var(--svg-color--5a3129, #5A3129);
}

.ixqsitb8q {
  stop-color: var(--svg-color--684e61, #684E61);
}

.j823ctb-q {
  stop-color: var(--svg-color--5b3838, #5B3838);
}

.kt15-irns {
  stop-color: var(--svg-color--a55f89, #A55F89);
}

.liejmwbeq {
  cx: 14.549px;
  cy: 14.874px;
  r: 0.512px;
}

.lv6eztbmt {
  stop-color: var(--svg-color--7f5575, #7F5575);
  stop-opacity: 0;
}

.lyklk88ly {
  stop-color: var(--svg-color--a06857, #A06857);
}

.m4eoz0qca {
  stop-color: var(--svg-color--682b5b, #682B5B);
  stop-opacity: 0;
}

.m9wdx7_yx {
  stop-color: var(--svg-color--705c5a, #705C5A);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mebto9quo {
  stop-color: var(--svg-color--ffdacc, #FFDACC);
}

.n43ik0btk {
  stop-color: var(--svg-color--915d88, #915D88);
}

.n6umd-8wf {
  d: path("M6.516 19.394c3.029 0 5.484-2.417 5.484-5.399c0-2.981-2.455-5.398-5.484-5.398S1.03 11.014 1.03 13.995c0 2.982 2.456 5.399 5.485 5.399");
}

.n7wvbnb3x {
  stop-color: var(--svg-color--43253d, #43253D);
  stop-opacity: 0;
}

.nbtt56b4o {
  fill: var(--svg-color--f2b9ad, #F2B9AD);
  d: path("M12.202 16.655c.334-.034.953-.416.999-1.078l-1.271-.437z");
}

.nkw7_sb2b {
  stop-color: var(--svg-color--c27f74, #C27F74);
}

.o9c8hnbkt {
  cx: 17.346px;
  cy: 14.874px;
  r: 0.512px;
}

.oi7ddwbfc {
  stop-color: var(--svg-color--be8b89, #BE8B89);
  stop-opacity: 0.6;
}

.oiv2fhbci {
  stop-color: var(--svg-color--dc90cc, #DC90CC);
  stop-opacity: 0;
}

.ovqobxb3d {
  stop-color: var(--svg-color--a55f89, #A55F89);
  stop-opacity: 0;
}

.p0pgtybjg {
  fill: var(--svg-color--ffd5c9, #FFD5C9);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m18.055 17.107l-.29-.49l-2.26 1.336l.289.49z");
}

.p5x69hxwb {
  width: 1.625px;
  height: 3.25px;
  x: 18.154px;
  y: 9.347px;
  fill: var(--svg-color--bb6f89, #BB6F89);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.813px;
}

.p6w626lsj {
  stop-color: var(--svg-color--dc89a8, #DC89A8);
}

.p9uo3pblo {
  stop-color: var(--svg-color--7c6160, #7C6160);
  stop-opacity: 0;
}

.ppkfmqblg {
  stop-color: var(--svg-color--ac628e, #AC628E);
}

.pq2xikbvb {
  width: 2.93px;
  height: 9.295px;
  x: 21.649px;
  y: 20.068px;
  rx: 1.465px;
}

.q4tn1k0pt {
  d: path("M25.433 19.394c3.029 0 5.484-2.417 5.484-5.399c0-2.981-2.455-5.398-5.484-5.398s-5.485 2.417-5.485 5.398c0 2.982 2.456 5.399 5.485 5.399");
}

.q6qj69lfx {
  stroke-linecap: round;
  stroke-opacity: 0.4;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M5.71 7.795c-1.593 3.93-1.411 9.682.33 12.13");
}

.q8vi0hbch {
  width: 2.93px;
  height: 9.295px;
  rx: 1.465px;
}

.qb49ptbxt {
  stop-color: var(--svg-color--ca6fa6, #CA6FA6);
}

.qcbmo3b6x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.013 14.23c.5 2.937-.593 5.125-1.593 6.03");
}

.qf38a13vx {
  stop-color: var(--svg-color--7c6160, #7C6160);
}

.qnz8b090o {
  fill: var(--svg-color--c58e7d, #C58E7D);
  d: path("M15.851 3.888c1.856 0 3.36.216 3.36.483s-1.504.483-3.36.483s-3.36-.216-3.36-.483s1.504-.483 3.36-.483");
}

.qqohlvbcu {
  d: path("M16 26.342c7.966 0 11.947-5.35 11.947-11.947c0-6.599-3.98-11.948-11.947-11.948S4.053 7.797 4.053 14.395S8.033 26.342 16 26.342");
}

.qt5w41b2y {
  stop-color: var(--svg-color--682b5b, #682B5B);
}

.qu6c0n3kh {
  stop-color: var(--svg-color--f9b4a9, #F9B4A9);
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.ragfnwbnv {
  stop-color: var(--svg-color--ac7463, #AC7463);
  stop-opacity: 0;
}

.rdbzxqbqj {
  width: 2.828px;
  height: 12.118px;
  x: 17.081px;
  y: 18.823px;
  rx: 1.414px;
}

.rkbd28wnq {
  stop-color: var(--svg-color--de81ca, #DE81CA);
}

.rnq27fbef {
  stop-color: var(--svg-color--e197db, #E197DB);
}

.rqliug_er {
  stop-color: var(--svg-color--7d3838, #7D3838);
  stop-opacity: 0;
}

.rr70jqe_l {
  cx: 23.418px;
  cy: 9.909px;
  fill: var(--svg-color--c58e7d, #C58E7D);
  rx: 1.849px;
  ry: 4.333px;
}

.rvow0325u {
  stop-color: var(--svg-color--aa6c64, #AA6C64);
}

.s1-80if6l {
  fill: var(--svg-color--ffd5c9, #FFD5C9);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m16.852 14.873l-.364-.616l-2.262 1.336l.365.616z");
}

.sc0snxbpi {
  stop-color: var(--svg-color--bc938f, #BC938F);
}

.sf_wn9jlw {
  stop-color: var(--svg-color--3e2739, #3E2739);
}

.sq6bhdbbn {
  stop-color: var(--svg-color--e9a4a2, #E9A4A2);
}

.sqcq8ybeh {
  width: 4.891px;
  height: 2.232px;
  x: 13.555px;
  y: 13.357px;
  rx: 1.116px;
}

.t2i434iwt {
  stop-color: var(--svg-color--ffbba3, #FFBBA3);
}

.t7bltqbvv {
  stop-color: var(--svg-color--e197db, #E197DB);
  stop-opacity: 0;
}

.t9ynm6bcv {
  stop-color: var(--svg-color--ef5cf2, #EF5CF2);
  stop-opacity: 0;
}

.tbqmcsbon {
  stop-color: var(--svg-color--f39585, #F39585);
  stop-opacity: 0;
}

.tklvtbcin {
  stop-color: var(--svg-color--b56595, #B56595);
}

.u85lrhbmd {
  cx: 19.495px;
  cy: 9.712px;
  r: 0.284px;
  fill: var(--svg-color--795d72, #795D72);
}

.ua19fnf6s {
  stop-color: var(--svg-color--b56595, #B56595);
  stop-opacity: 0;
}

.uexfrlbgb {
  stop-color: var(--svg-color--d79d95, #D79D95);
}

.uuuiv4j7f {
  fill: var(--svg-color--ffd5c9, #FFD5C9);
  d: path("M20.668 14.855c.335.02.97.375 1.043 1.034l-1.25.49z");
}

.uy70yzmbt {
  fill: var(--svg-color--561e25, #561E25);
  d: path("M11.877 6.118a4.76 4.76 0 0 0-3.653 7.81a.55.55 0 0 1 .122.458q-.13.68-.13 1.398a7.464 7.464 0 1 0 14.796-1.398a.56.56 0 0 1 .121-.458a4.76 4.76 0 0 0-3.653-7.81z");
}

.v290nq5uq {
  stop-color: var(--svg-color--ac7463, #AC7463);
}

.v3_xnsbbc {
  stop-color: var(--svg-color--be8b89, #BE8B89);
  stop-opacity: 0;
}

.vh8pidbig {
  fill: var(--svg-color--ffd5c9, #FFD5C9);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m14.201 17.098l.29-.49l2.261 1.336l-.29.49z");
}

.vo38q3bgp {
  width: 1.625px;
  height: 3.25px;
  x: 18.445px;
  y: 9.105px;
  rx: 0.813px;
}

.vpk0l0bon {
  stop-color: var(--svg-color--ffebe3, #FFEBE3);
}

.vrzzu0qhm {
  width: 3.081px;
  height: 9.295px;
  x: 20.916px;
  y: 22.393px;
  rx: 1.54px;
}

.w2g84vbed {
  fill: var(--svg-color--ffd5c9, #FFD5C9);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("m13.555 19.394l.177-.3l1.571.9l-.177.3z");
}

.we9f_j1si {
  d: path("M13.336 15.651a.5.5 0 0 1 .685.177l.593 1.004a6.75 6.75 0 0 1-2.378 9.245l-3.534 2.088a4.208 4.208 0 0 1-4.281-7.246z");
}

.whjaerb5v {
  stop-color: var(--svg-color--43253d, #43253D);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x31kd8bmz {
  width: 5.344px;
  height: 2.418px;
  x: 13.102px;
  y: 13.761px;
  fill: var(--svg-color--bb6f89, #BB6F89);
  rx: 1.116px;
}

.xf_16zgyk {
  stop-color: var(--svg-color--ac928f, #AC928F);
}

.xgbxb0f0n {
  stop-color: var(--svg-color--edada3, #EDADA3);
}

.xh0ps3bnm {
  stop-color: var(--svg-color--c971b6, #C971B6);
}

.xhq4p5b6u {
  fill: var(--svg-color--b05a93, #B05A93);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m17.832 15.736l1.79 1.01l-1.59 6.817c-3.368-2.734-1.537-6.357-.2-7.827");
}

.y4ijtcxdz {
  stop-color: var(--svg-color--cf6aba, #CF6ABA);
}

.y7p5z931p {
  stop-color: var(--svg-color--7a326b, #7A326B);
}

.ypq_y2bvs {
  stop-color: var(--svg-color--dc90cc, #DC90CC);
}

.yrar24m3w {
  stop-color: var(--svg-color--ffc8bc, #FFC8BC);
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

.yyc-z4k8n {
  stop-color: var(--svg-color--5a383a, #5A383A);
  stop-opacity: 0;
}

.z-2ijsx5t {
  stop-color: var(--svg-color--5a3129, #5A3129);
  stop-opacity: 0;
}

.z3r4yfb1i {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M6.516 19.394c3.029 0 5.484-2.417 5.484-5.399c0-2.981-2.455-5.398-5.484-5.398S1.03 11.014 1.03 13.995c0 2.982 2.456 5.399 5.485 5.399");
}

</style>
