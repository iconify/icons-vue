<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#il4J9vb)" class="rxk-dwzrq"/><path fill="url(#iqkzpyc)" class="rxk-dwzrq"/><path fill="url(#iT2RwTd)" class="rxk-dwzrq"/><path fill="url(#i6myPqe)" class="rxk-dwzrq"/><path fill="url(#iQagAqd)" class="rxk-dwzrq"/><path fill="url(#iixI3Ud)" class="rxk-dwzrq"/><g filter="url(#iR5Lgse)"><rect class="fd4k_dqsw"/></g><g filter="url(#iOBQkyF)"><path fill="url(#iam3T6c)" class="e49iksl1f"/></g><path fill="url(#iqxBlzb)" class="hd70gpsna"/><g filter="url(#i2Tl6xd)"><path fill="url(#i7k3wWb)" class="mzovwmbki"/></g><g filter="url(#iXzm1Ce)"><path class="dzd5qvslm"/></g><g filter="url(#iNUJ5Nc)"><path fill="url(#iG4bo7c)" class="kefjadc-o"/></g><g filter="url(#iRHv27e)"><path stroke="url(#iQB44qF)" class="tvl9t-b0t"/></g><g filter="url(#iPMOx9c)"><path stroke="url(#iykM49d)" class="n0bal_b7g"/></g><path stroke="url(#iASJqdb)" class="q7buqnska"/><g filter="url(#iGCyZnh)"><path class="g5dbetbbm"/></g><g filter="url(#inE8rHc)"><ellipse transform="rotate(-22.745 29.606 20.58)" class="hu6330bec"/></g><path stroke="url(#ioFXBFO)" class="n-ph5qbbj"/><g filter="url(#iptn1Qc)"><path class="mwl3qxlxv"/></g><g filter="url(#inMA5ie)"><ellipse transform="rotate(28.298 29.54 26.368)" class="o20jgpb8q"/></g><path stroke="url(#iwhvLne)" class="sakyj2bhc"/><g filter="url(#iG9zi8p)"><path class="ufk_01b0k"/></g><g filter="url(#iKc1Dkc)"><ellipse transform="scale(-1 1)rotate(-19.477 68.068 31.615)" class="i4304abpf"/></g><path stroke="url(#iH0emWc)" class="g9_ds3b0i"/><g filter="url(#if96nDe)"><path clip-rule="evenodd" class="skfljc-8u"/></g><path stroke="url(#irRIv8k)" class="ezaf-kb1p"/><path stroke="url(#iWLfZEc)" class="u5h_98cwl"/><path fill="url(#iytCGTB)" class="ssnr9cbbx"/><g filter="url(#i0DPhvd)"><ellipse fill="url(#iM6i3qc)" class="g20o161qg"/></g><g filter="url(#iOS3TUd)"><path class="h5j26nbxj"/></g><g filter="url(#i0OF4Pe)"><ellipse transform="scale(-1 1)rotate(-70.238 12.624 16.051)" class="i4304abpf"/></g><g filter="url(#i3V4RJe)"><path fill="url(#iptlgmb)" class="s6w5cqbyq"/></g><g filter="url(#ifW3Uec)"><path fill="url(#i8hFuzd)" class="rylbswdym"/></g><g filter="url(#iHHhE0d)"><circle class="fhnjzlb3q"/></g><g filter="url(#iye8COd)"><circle class="g2q-dqbhe"/></g><g filter="url(#ip1rCVb)"><path fill="url(#ibd07ic)" class="f93ztlbco"/></g><path class="ezljnbc0s"/><path fill="url(#i7iSbLD)" class="uq8kcdb_k"/><g filter="url(#iX0GcOc)"><path fill="url(#iZRdlmd)" class="r8xfcfbfw"/></g><g filter="url(#iMvveOK)"><path stroke="url(#iih8w9b)" class="adegsgbqe"/></g><g filter="url(#ihrDCMd)"><path class="o9vbcib6u"/></g><g filter="url(#ipIpukc)"><path class="gc94w1i4z"/></g><g filter="url(#ivvkRDd)"><path class="sl1uq0kgn"/></g><g filter="url(#ic5U7Kc)"><path class="ak88u7r-q"/></g><path fill="url(#iGrL84c)" class="qn29azbrl"/><path fill="url(#iifv5Ub)" class="qn29azbrl"/><path fill="url(#iXZ3wke)" class="ovfsnxuet"/><path fill="url(#iL0iDcb)" class="ovfsnxuet"/><path stroke="url(#i1El51X)" class="plgps0gwf"/><path stroke="url(#iuNC6oe)" class="a9vs0dbts"/><defs><filter id="iR5Lgse" width="5.727" height="6.698" x="3.554" y="20.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".75"/></filter><filter id="iOBQkyF" width="9.009" height="11.636" x="19.098" y="4.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".5"/></filter><filter id="i2Tl6xd" width="3.417" height="4.625" x="24.805" y="4.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".5"/></filter><filter id="iXzm1Ce" width="8.95" height="10.729" x="2.946" y="3.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation="1"/></filter><filter id="iNUJ5Nc" width="3.661" height="3.024" x="13.748" y="20.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="iRHv27e" width="6.005" height="4.013" x="23.685" y="19.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="iPMOx9c" width="4.127" height="3.566" x="23.685" y="23.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="iGCyZnh" width="5.105" height="3.113" x="24.916" y="20.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="inE8rHc" width="1.363" height="1.337" x="28.924" y="19.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="iptn1Qc" width="5.102" height="3.119" x="24.848" y="23.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="inMA5ie" width="1.36" height="1.34" x="28.86" y="25.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="iG9zi8p" width="5.102" height="3.119" x="2.142" y="23.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="iKc1Dkc" width="1.364" height="1.336" x="5.964" y="23.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="if96nDe" width="2.317" height="4.85" x="14.506" y="20.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="i0DPhvd" width="2.723" height="1.748" x="14.909" y="19.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".3"/></filter><filter id="iOS3TUd" width="5.114" height="3.094" x="2.21" y="20.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="i0OF4Pe" width="1.336" height="1.364" x="6.083" y="21.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="i3V4RJe" width="2.551" height="3.941" x="18.932" y="17.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="ifW3Uec" width="2.551" height="3.941" x="9.055" y="16.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="iHHhE0d" width="1.472" height="1.472" x="19.471" y="17.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="iye8COd" width="1.472" height="1.472" x="11.529" y="17.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="ip1rCVb" width="12.585" height="22.186" x="18.102" y="6.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation="2"/></filter><filter id="iX0GcOc" width="4.825" height="7.138" x="22.409" y="6.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".3"/></filter><filter id="iMvveOK" width="4.531" height="4.734" x="22.727" y="9.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".375"/></filter><filter id="ihrDCMd" width="4.469" height="6.908" x="4.723" y="6.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="ipIpukc" width="1.15" height="6.337" x="4.648" y="7.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".25"/></filter><filter id="ivvkRDd" width="5.487" height="5.076" x="17.291" y="14.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation=".45"/></filter><filter id="ic5U7Kc" width="8.251" height="7.093" x="6.674" y="13.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6981_5056" stdDeviation="1"/></filter><linearGradient id="il4J9vb" x1="7.907" x2="7.907" y1="1.35" y2="30.99" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ce9hnwylf"/><stop offset=".762" class="gq9h7lsld"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="iqkzpyc" x1="8.831" x2="1.17" y1="12.033" y2="12.033" gradientUnits="userSpaceOnUse"><stop class="f6xjhkepg"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="iT2RwTd" x1="26.791" x2="30.245" y1="12.033" y2="12.033" gradientUnits="userSpaceOnUse"><stop class="f6xjhkepg"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="i6myPqe" x1="16.001" x2="16" y1="-1.595" y2="30.99" gradientUnits="userSpaceOnUse"><stop offset=".771" class="og2_-db3e"/><stop offset="1" class="iedbks3oi"/></linearGradient><linearGradient id="iQagAqd" x1="16" x2="16" y1="11.252" y2="32.475" gradientUnits="userSpaceOnUse"><stop offset=".854" class="stui2mbih"/><stop offset=".985" class="vc--wpv5i"/></linearGradient><linearGradient id="iam3T6c" x1="21.908" x2="28.165" y1="6.852" y2="13.695" gradientUnits="userSpaceOnUse"><stop class="x5la94b6u"/><stop offset="1" class="t246kz1qf"/></linearGradient><linearGradient id="iqxBlzb" x1="10.602" x2="4.743" y1="10.617" y2="10.07" gradientUnits="userSpaceOnUse"><stop offset=".437" class="xon4_gnbq"/><stop offset="1" class="q5x9unbmu"/></linearGradient><linearGradient id="i7k3wWb" x1="27.04" x2="26.444" y1="4.961" y2="7.302" gradientUnits="userSpaceOnUse"><stop offset=".286" class="j_4i6w0ng"/><stop offset="1" class="z84gitb5w"/></linearGradient><linearGradient id="iG4bo7c" x1="15.751" x2="15.079" y1="22.351" y2="23.445" gradientUnits="userSpaceOnUse"><stop class="fd6xzxk0h"/><stop offset="1" class="xvb0lxf4e"/></linearGradient><linearGradient id="iQB44qF" x1="24.29" x2="28.024" y1="23.236" y2="21.32" gradientUnits="userSpaceOnUse"><stop class="p3zloackg"/><stop offset="1" class="enakum12e"/></linearGradient><linearGradient id="iykM49d" x1="24.29" x2="28.024" y1="24.58" y2="26.495" gradientUnits="userSpaceOnUse"><stop offset=".286" class="mlskkyb7u"/><stop offset=".818" class="enakum12e"/></linearGradient><linearGradient id="iASJqdb" x1="25.29" x2="29.371" y1="22.945" y2="21.008" gradientUnits="userSpaceOnUse"><stop offset=".156" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="ioFXBFO" x1="25.074" x2="29.146" y1="24.71" y2="26.665" gradientUnits="userSpaceOnUse"><stop offset=".156" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="iwhvLne" x1="7.018" x2="2.945" y1="24.721" y2="26.677" gradientUnits="userSpaceOnUse"><stop offset=".156" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="iH0emWc" x1="6.818" x2="2.728" y1="22.929" y2="21.012" gradientUnits="userSpaceOnUse"><stop offset=".156" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="iWLfZEc" x1="18.194" x2="10.897" y1="22.885" y2="22.885" gradientUnits="userSpaceOnUse"><stop offset=".135" class="ovz69fb_x"/><stop offset=".276" class="hd0nr3bzk"/><stop offset=".411" class="ccr58nbuz"/></linearGradient><linearGradient id="iM6i3qc" x1="17.204" x2="15.68" y1="20.741" y2="20.741" gradientUnits="userSpaceOnUse"><stop class="mno0o_bwq"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iptlgmb" x1="21.464" x2="22.464" y1="19.679" y2="23.14" gradientUnits="userSpaceOnUse"><stop class="poldyt64s"/><stop offset="1" class="xvb0lxf4e"/></linearGradient><linearGradient id="i8hFuzd" x1="11.587" x2="12.587" y1="19.347" y2="22.808" gradientUnits="userSpaceOnUse"><stop class="fy9ven5ui"/><stop offset="1" class="xvb0lxf4e"/></linearGradient><linearGradient id="ibd07ic" x1="23.352" x2="22.956" y1="10.838" y2="22.889" gradientUnits="userSpaceOnUse"><stop offset=".548" class="n5rbp-b1w"/><stop offset="1" class="z84gitb5w"/></linearGradient><linearGradient id="i7iSbLD" x1="26.54" x2="25.29" y1="15.508" y2="12.039" gradientUnits="userSpaceOnUse"><stop class="f1yr_dbcd"/><stop offset="1" class="id4j66bti"/></linearGradient><linearGradient id="iih8w9b" x1="25.055" x2="25.055" y1="10.477" y2="12.82" gradientUnits="userSpaceOnUse"><stop offset=".432" class="g5d5gfbbl"/><stop offset="1" class="uekqj6-lf"/></linearGradient><linearGradient id="iGrL84c" x1="13.835" x2="9.366" y1="18.104" y2="18.104" gradientUnits="userSpaceOnUse"><stop class="dcdi0_bfz"/><stop offset=".568" class="ixqsitb8q"/><stop offset=".766" class="whjaerb5v"/></linearGradient><linearGradient id="iifv5Ub" x1="11.257" x2="11.257" y1="17.948" y2="20.245" gradientUnits="userSpaceOnUse"><stop offset=".327" class="n7wvbnb3x"/><stop offset="1" class="whjaerb5v"/></linearGradient><linearGradient id="iXZ3wke" x1="23.803" x2="19.335" y1="18.104" y2="18.104" gradientUnits="userSpaceOnUse"><stop class="dcdi0_bfz"/><stop offset=".568" class="ixqsitb8q"/><stop offset=".766" class="whjaerb5v"/></linearGradient><linearGradient id="iL0iDcb" x1="21.225" x2="21.225" y1="17.948" y2="20.245" gradientUnits="userSpaceOnUse"><stop offset=".327" class="n7wvbnb3x"/><stop offset="1" class="whjaerb5v"/></linearGradient><radialGradient id="iixI3Ud" cx="0" cy="0" r="1" gradientTransform="matrix(3.04569 4.424 -8.78922 6.0509 22.175 4.477)" gradientUnits="userSpaceOnUse"><stop class="x5la94b6u"/><stop offset=".921" class="t246kz1qf"/></radialGradient><radialGradient id="irRIv8k" cx="0" cy="0" r="1" gradientTransform="matrix(-.01653 -5.21875 10.18765 -.03227 16.21 25.713)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ccr58nbuz"/><stop offset=".312" class="hd0nr3bzk"/><stop offset=".386" class="cqs25qqpc"/></radialGradient><radialGradient id="iytCGTB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.89063 -.95312 .95876 -1.9018 16.446 21.18)" gradientUnits="userSpaceOnUse"><stop class="rj5_8-btj"/><stop offset="1" class="px6tpwb-q"/></radialGradient><radialGradient id="iZRdlmd" cx="0" cy="0" r="1" gradientTransform="matrix(4.40625 6.46875 -7.7559 5.283 22.868 7.773)" gradientUnits="userSpaceOnUse"><stop class="n_w31cdgy"/><stop offset="1" class="prf81acwx"/></radialGradient><radialGradient id="i1El51X" cx="0" cy="0" r="1" gradientTransform="matrix(2.37496 3.0625 -6.75506 5.23852 20.672 15.612)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="ovz69fb_x"/><stop offset=".276" class="gvfj_gdms"/><stop offset=".479" class="ccr58nbuz"/><stop offset=".479" class="ccr58nbuz"/></radialGradient><radialGradient id="iuNC6oe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.63243 3.28511 -5.82005 -4.66374 11.835 16.264)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="ovz69fb_x"/><stop offset=".276" class="gvfj_gdms"/><stop offset=".385" class="ccr58nbuz"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pouting-cat" /></template>
<style>
.a9vs0dbts {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M12.541 17.752c-.758 0-2.195-.375-2.805-2.172");
}

.adegsgbqe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m23.727 10.29l2.532 2.733");
}

.ak88u7r-q {
  stroke: var(--svg-color--d37c04, #D37C04);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M12.375 18.508c-.758 0-2.541-.196-3.15-1.993");
}

.bc88ifbby {
  stop-color: var(--svg-color--d64a38, #D64A38);
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.ce9hnwylf {
  stop-color: var(--svg-color--f2cc26, #F2CC26);
}

.cqs25qqpc {
  stop-color: var(--svg-color--483334, #483334);
}

.dcdi0_bfz {
  stop-color: var(--svg-color--432a3d, #432A3D);
}

.dzd5qvslm {
  stroke: var(--svg-color--ffdf70, #FFDF70);
  stroke-linecap: round;
  d: path("m5.446 5.727l3.375 3.22c.754.718.768 1.918.031 2.655v0");
}

.e49iksl1f {
  d: path("M20.75 10.2c-2.983.108 5.227 4.954 5.227 4.954l1.125-9.062c.055-.461-.364-.954-1.25-.131L21.84 9.913c-.187.184-.408.25-.702.288c-.15.02-.236-.006-.386 0");
}

.enakum12e {
  stop-color: var(--svg-color--e37d02, #E37D02);
  stop-opacity: 0;
}

.ezaf-kb1p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M13.151 25.322c.922-.911 3.204-2.148 5.735 0");
}

.ezljnbc0s {
  fill: var(--svg-color--ffb915, #FFB915);
  d: path("m25.833 13.503l-2.8-2.6a.716.716 0 0 1 0-1.07l3.015-2.677c.382-.336 1.175-.226 1.175.607v5.2c0 .834-.88 1.02-1.39.54");
}

.f1yr_dbcd {
  stop-color: var(--svg-color--ef8a47, #EF8A47);
}

.f6xjhkepg {
  stop-color: var(--svg-color--e99e20, #E99E20);
  stop-opacity: 0;
}

.f93ztlbco {
  d: path("M22.102 10.102h4.585v14.186h-4.585z");
}

.fd4k_dqsw {
  width: 2.727px;
  height: 3.698px;
  x: 5.054px;
  y: 21.82px;
  fill: var(--svg-color--d67908, #D67908);
  rx: 1.363px;
}

.fd6xzxk0h {
  stop-color: var(--svg-color--e3900e, #E3900E);
}

.fhnjzlb3q {
  cx: 20.207px;
  cy: 17.764px;
  r: 0.236px;
  fill: var(--svg-color--775b70, #775B70);
}

.ft5dv1b6b {
  fill: none;
}

.fy9ven5ui {
  stop-color: var(--svg-color--e89311, #E89311);
}

.g20o161qg {
  cx: 16.27px;
  cy: 20.741px;
  rx: 0.762px;
  ry: 0.274px;
}

.g2q-dqbhe {
  cx: 12.265px;
  cy: 17.764px;
  r: 0.236px;
  fill: var(--svg-color--775b70, #775B70);
}

.g5d5gfbbl {
  stop-color: var(--svg-color--ffe7a3, #FFE7A3);
}

.g5dbetbbm {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m25.566 22.71l3.805-1.812");
}

.g9_ds3b0i {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("M6.54 22.524L2.726 20.73");
}

.gc94w1i4z {
  stroke: var(--svg-color--ffe7a3, #FFE7A3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.223 7.727v5.187");
}

.gq9h7lsld {
  stop-color: var(--svg-color--e99e20, #E99E20);
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h5j26nbxj {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M6.674 22.499L2.86 20.705");
}

.hd0nr3bzk {
  stop-color: var(--svg-color--594253, #594253);
}

.hd70gpsna {
  d: path("m6.133 13.503l2.8-2.6c.32-.3.32-.78 0-1.07L5.918 7.156c-.383-.336-1.175-.226-1.175.607v5.2c0 .834.88 1.02 1.39.54");
}

.hu6330bec {
  cx: 29.606px;
  cy: 20.581px;
  fill: var(--svg-color--ffdd86, #FFDD86);
  rx: 0.184px;
  ry: 0.166px;
}

.i4304abpf {
  fill: var(--svg-color--ffdd86, #FFDD86);
  rx: 0.184px;
  ry: 0.166px;
}

.id4j66bti {
  stop-color: var(--svg-color--ef8a47, #EF8A47);
  stop-opacity: 0;
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.ixqsitb8q {
  stop-color: var(--svg-color--684e61, #684E61);
}

.j_4i6w0ng {
  stop-color: var(--svg-color--ffe792, #FFE792);
}

.kefjadc-o {
  d: path("m14.805 20.65l.065-.015a3 3 0 0 1 1.438.015c.52.098.832.696.392 1.126l-.55.601c-.27.27-.864.27-1.134 0l-.543-.601c-.449-.508-.168-1.016.332-1.126");
}

.mlskkyb7u {
  stop-color: var(--svg-color--de7d07, #DE7D07);
}

.mno0o_bwq {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.9;
}

.mwl3qxlxv {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m25.498 24.55l3.802 1.818");
}

.mzovwmbki {
  d: path("M26.49 5.652a.38.38 0 0 1 .732.142v2.245l-1.417-.687z");
}

.n_w31cdgy {
  stop-color: var(--svg-color--ffdf70, #FFDF70);
}

.n-ph5qbbj {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m25.564 24.67l3.801 1.818");
}

.n0bal_b7g {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m24.785 24.924l1.927 1.365");
}

.n5rbp-b1w {
  stop-color: var(--svg-color--ffdd65, #FFDD65);
}

.n7wvbnb3x {
  stop-color: var(--svg-color--43253d, #43253D);
  stop-opacity: 0;
}

.o20jgpb8q {
  cx: 29.54px;
  cy: 26.368px;
  fill: var(--svg-color--ffdd86, #FFDD86);
  rx: 0.184px;
  ry: 0.166px;
}

.o9vbcib6u {
  fill: var(--svg-color--feb33e, #FEB33E);
  d: path("M5.223 7.5v5.907l3.469-3.09z");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ovfsnxuet {
  d: path("M20.875 19.98a.77.77 0 0 1-.775-.76v-1.422c0-.416.35-.76.775-.76s.775.344.775.76v1.422c0 .428-.35.76-.775.76");
}

.ovz69fb_x {
  stop-color: var(--svg-color--483637, #483637);
}

.p3zloackg {
  stop-color: var(--svg-color--e88105, #E88105);
}

.plgps0gwf {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M19.236 17.752c.758 0 2.196-.375 2.805-2.172");
}

.poldyt64s {
  stop-color: var(--svg-color--ec9611, #EC9611);
}

.prf81acwx {
  stop-color: var(--svg-color--ffdf70, #FFDF70);
  stop-opacity: 0;
}

.pt1exccow {
  stop-color: var(--svg-color--e3801d, #E3801D);
}

.px6tpwb-q {
  stop-color: var(--svg-color--e61e27, #E61E27);
}

.q5x9unbmu {
  stop-color: var(--svg-color--ffb03a, #FFB03A);
}

.q7buqnska {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m25.566 22.54l3.805-1.813");
}

.qn29azbrl {
  d: path("M10.906 19.98a.77.77 0 0 1-.775-.76v-1.422c0-.416.35-.76.775-.76s.775.344.775.76v1.422c0 .428-.35.76-.775.76");
}

.r8xfcfbfw {
  d: path("m26.634 7.367l-3.625 3.125l3.546 2.813z");
}

.rj5_8-btj {
  stop-color: var(--svg-color--ea088b, #EA088B);
}

.rxk-dwzrq {
  d: path("M4 25.942C4 28.174 5.763 30 7.918 30h16.164C26.237 30 28 28.073 28 25.84V6.43c0-1.3-1.59-1.9-2.485-1L20.975 10h-9.812L6.5 5.43c-.9-.9-2.5-.3-2.5 1z");
}

.rylbswdym {
  d: path("M10.33 20.135a.77.77 0 0 1-.775-.76v-1.42c0-.417.35-.76.775-.76s.775.343.775.76v1.42c0 .43-.35.76-.775.76");
}

.s6w5cqbyq {
  d: path("M20.207 20.467a.77.77 0 0 1-.775-.76v-1.42c0-.417.35-.76.775-.76s.775.343.775.76v1.42c0 .43-.35.76-.775.76");
}

.sakyj2bhc {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("M6.528 24.681L2.727 26.5");
}

.skfljc-8u {
  fill: var(--svg-color--dc8400, #DC8400);
  fill-rule: evenodd;
  d: path("M15.665 20.712c.364 0 .658.246.658.55v2.75c0 .303-.294.55-.658.55s-.659-.247-.659-.55v-2.75c0-.304.295-.55.659-.55");
}

.sl1uq0kgn {
  stroke: var(--svg-color--d37c04, #D37C04);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M18.741 18.287c.758 0 1.978-.378 2.587-2.175");
}

.ssnr9cbbx {
  d: path("m15.227 20.207l.064-.015a3 3 0 0 1 1.438.015c.521.098.832.695.392 1.125l-.55.602c-.27.27-.864.27-1.134 0l-.542-.602c-.45-.508-.168-1.016.332-1.125");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t246kz1qf {
  stop-color: var(--svg-color--ffa720, #FFA720);
  stop-opacity: 0;
}

.tvl9t-b0t {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m24.785 22.892l3.805-1.812");
}

.u5h_98cwl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M16.01 23.651v-1.34");
}

.uekqj6-lf {
  stop-color: var(--svg-color--ffdf83, #FFDF83);
  stop-opacity: 0;
}

.ufk_01b0k {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m6.593 24.56l-3.801 1.82");
}

.uq8kcdb_k {
  d: path("m25.833 13.503l-2.8-2.6a.716.716 0 0 1 0-1.07l3.015-2.677c.382-.336 1.175-.226 1.175.607v5.2c0 .834-.88 1.02-1.39.54");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wf44tw33q {
  stop-color: var(--svg-color--e3821d, #E3821D);
}

.whjaerb5v {
  stop-color: var(--svg-color--43253d, #43253D);
}

.x5la94b6u {
  stop-color: var(--svg-color--ffa720, #FFA720);
}

.xon4_gnbq {
  stop-color: var(--svg-color--ed8c1b, #ED8C1B);
}

.xvb0lxf4e {
  stop-color: var(--svg-color--ea9d26, #EA9D26);
  stop-opacity: 0;
}

.ycz1ylytj {
  stop-color: var(--svg-color--fb7425, #FB7425);
}

.z84gitb5w {
  stop-color: var(--svg-color--ffdd65, #FFDD65);
  stop-opacity: 0;
}

</style>
