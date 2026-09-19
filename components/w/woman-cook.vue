<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#icELUgW)"><path fill="url(#i4ugH8a)" class="jr673vojc"/><path fill="url(#i1TuJoc)" class="jr673vojc"/><path fill="url(#imDabrc)" class="jr673vojc"/><path fill="url(#iqCIgwc)" class="jr673vojc"/></g><path fill="url(#ivbTNOc)" class="nhiplpbid"/><path fill="url(#iB7NrPd)" class="nhiplpbid"/><path fill="url(#it0dZPb)" class="nhiplpbid"/><path fill="url(#iaOvNPb)" class="eze2rhbqa"/><path fill="url(#i0UM0LD)" class="eze2rhbqa"/><g filter="url(#iTGrCCb)"><path class="fvfz9ra4u"/></g><g filter="url(#imPwLte)"><path class="ocwbw1bfb"/></g><path class="bwu2-2wyh"/><path fill="url(#iHidXke)" class="ysgnr6bpv"/><path fill="url(#iQ2ko3d)" class="ppe49ccog"/><path fill="url(#ihPqkfc)" class="ppe49ccog"/><path fill="url(#iN1PdZq)" class="vt32lr6la"/><path fill="url(#i0Wq4WI)" class="vt32lr6la"/><path fill="url(#iB8wYVz)" class="vt32lr6la"/><g filter="url(#iy5chxe)"><path fill="url(#ih8fEFb)" class="v86u-prji"/><path fill="url(#iY1SS5b)" class="v86u-prji"/></g><path fill="url(#iF13Zub)" class="v86u-prji"/><path fill="url(#iEmVfrc)" class="v86u-prji"/><g filter="url(#iio1fAe)"><path fill="url(#injVVud)" class="pi2b9hbek"/></g><path fill="url(#ikPvBae)" class="mtsctzv2d"/><path fill="url(#iQzT0we)" class="mtsctzv2d"/><g filter="url(#isfq9uj)"><path class="pfz9oobhy"/></g><g filter="url(#iAgUYyb)"><path class="en78occrq"/></g><g filter="url(#iNMSCDb)"><path class="h7p6_nr3r"/></g><g filter="url(#i0BkE8b)"><path fill="url(#ixLTEWb)" class="bfzcp6bwm"/></g><g filter="url(#i4suNhd)"><path fill="url(#iyhhPMd)" class="da588nbds"/></g><g filter="url(#iDeepVc)"><path fill="url(#ilewkNS)" class="at6a40j7p"/></g><g filter="url(#i6pg0Tc)"><path fill="url(#iQ1m9ie)" class="gz3n1jouz"/></g><path fill="url(#iEgPt6c)" class="sxxvir8ge"/><path fill="url(#iN71iFe)" class="sxxvir8ge"/><path fill="url(#i95Sfsb)" class="sxxvir8ge"/><path fill="url(#iqaCsjk)" class="bsq_nvbhc"/><path fill="url(#igSwaEd)" class="bsq_nvbhc"/><path fill="url(#ieAUSEe)" class="bsq_nvbhc"/><path fill="url(#iOrUtUZ)" class="bsq_nvbhc"/><g filter="url(#idM8kFd)"><path fill="url(#iTUreAm)" class="vazf9obcy"/></g><g filter="url(#i4V3Tyc)"><path class="l8-517ayn"/><path fill="url(#iLUWkPb)" class="rmxffvb1r"/></g><g filter="url(#iGfC4td)"><ellipse fill="url(#i5dXj7b)" class="n3m1ezf2x"/></g><g filter="url(#iOxSv1d)"><path fill="url(#ilWVfxH)" class="tuhkblbbb"/><path fill="url(#i12Edsc)" class="tuhkblbbb"/><path fill="url(#iDjEvPd)" class="tuhkblbbb"/><path fill="url(#iWe8iye)" class="tuhkblbbb"/><path fill="url(#iY5kxqz)" class="tuhkblbbb"/></g><g filter="url(#iwNnkVb)"><path stroke="url(#it5Mcpe)" class="yrbhdtb5l"/></g><g filter="url(#iFBVcFe)"><path stroke="url(#iCntard)" class="pf8e19bhl"/></g><g filter="url(#ibxEctb)"><path stroke="url(#iBcw8Fd)" class="txvr2mg9h"/></g><g filter="url(#i0HcVNA)"><path fill="url(#iwJu5mb)" class="ijtsnweaq"/><path fill="url(#iF398Wm)" class="ijtsnweaq"/><path fill="url(#irg0u9d)" class="ijtsnweaq"/><path fill="url(#iJD33hc)" class="ijtsnweaq"/><path fill="url(#ijVxf6b)" class="ijtsnweaq"/><path fill="url(#iiVLc8a)" class="ijtsnweaq"/><path fill="url(#iqpB8sb)" class="ijtsnweaq"/></g><path fill="url(#ir0DJYd)" class="ijtsnweaq"/><path fill="url(#iW0OTHd)" class="ijtsnweaq"/><g filter="url(#ik5Xdzc)"><path class="fye21xbob"/></g><g filter="url(#iqUPzkv)"><path fill="url(#iDtveyb)" class="r2y81xbdv"/><path fill="url(#i8WbTSb)" class="r2y81xbdv"/><path fill="url(#iAbViEe)" class="r2y81xbdv"/><path fill="url(#i4dOyde)" class="r2y81xbdv"/></g><g filter="url(#ie32LRt)"><path stroke="url(#iwSJJ8d)" class="e0vlk9b5p"/></g><path fill="url(#iEVmgme)" class="ed-0_pbdm"/><g filter="url(#ijfn9Ed)"><path class="cxx4_cgxb"/></g><g filter="url(#ipn5JKe)"><path class="z_-5ztb3t"/></g><g filter="url(#iQp3Y9c)"><path class="khuqv_blc"/></g><g filter="url(#i7y3Z6d)"><path class="sznpyw3vg"/></g><g filter="url(#igjg1cb)"><path fill="url(#i4SBeXc)" class="sebbmcv5r"/><path fill="url(#ik6gntc)" class="sebbmcv5r"/></g><path fill="url(#iww4FVb)" class="w4scbcb6a"/><path fill="url(#iP6uMLb)" class="w4scbcb6a"/><g filter="url(#iSipXSO)"><path fill="url(#iN04oRc)" class="vyfoh_bai"/></g><g filter="url(#i9Jj0Sd)"><path fill="url(#i5SixOe)" class="kb3z53baa"/></g><g filter="url(#i0WMNuT)"><path fill="url(#iIkhyOc)" class="fr8y_ibbz"/></g><g filter="url(#iGTT1rb)"><path class="qgrespbqh"/></g><g filter="url(#iAXC7Ud)"><path class="pobhhfhpo"/></g><path class="gm83zy8rh"/><path fill="url(#ir0jK2d)" class="hrk8a5b8c"/><path class="k70x9fbeh"/><g filter="url(#isCBLMe)"><path class="udhq7ablm"/><path fill="url(#iu8dHbz)" class="h0z263bik"/></g><g filter="url(#iWEt65d)"><path fill="url(#iEvuIud)" class="vg9fp6e2d"/></g><path class="i8yd0cbcz"/><path fill="url(#ikCxSFc)" class="wn_wkkbea"/><path class="xl0z3lbkl"/><g filter="url(#iNbd1WL)"><path fill="url(#ivy4pqd)" class="d8am9zbor"/></g><g filter="url(#iRkMoBb)"><ellipse transform="rotate(-27.914 13.651 9.933)" class="pbjnplbdd"/><ellipse fill="url(#iEAE4JY)" transform="rotate(-27.914 13.651 9.933)" class="zibvjpbta"/></g><defs><radialGradient id="i1TuJoc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35936 2.32814 -1.13833 -.66466 11.297 7.766)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="l-jt33s2g"/><stop offset="1" class="qakha17bf"/></radialGradient><radialGradient id="imDabrc" cx="0" cy="0" r="1" gradientTransform="matrix(1.82081 0 0 2.98547 20.61 7.667)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="hc4bqpbdd"/><stop offset="1" class="o3lv9vb9b"/></radialGradient><radialGradient id="iqCIgwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90841 -5.85233 0 15.152 12.62)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="jjgs19bwd"/><stop offset="1" class="ofju7ulzd"/></radialGradient><radialGradient id="iB7NrPd" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.722 9.927)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="it0dZPb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.082 10.472)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i0UM0LD" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.278 9.496)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iHidXke" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.371 58.636)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="ihPqkfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 24.142 30.153)" gradientUnits="userSpaceOnUse"><stop class="br4vp4byh"/><stop offset="1" class="fs29nabkl"/></radialGradient><radialGradient id="iB8wYVz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.583 30.656)" gradientUnits="userSpaceOnUse"><stop class="gt-1-ac7u"/><stop offset="1" class="yrzv-0byt"/></radialGradient><radialGradient id="ih8fEFb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 21.184 19.628)" gradientUnits="userSpaceOnUse"><stop class="b3mtuebqr"/><stop offset="1" class="txq537bby"/></radialGradient><radialGradient id="iY1SS5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.848 32.4)" gradientUnits="userSpaceOnUse"><stop class="ygyrfpbde"/><stop offset="1" class="r7svlnonw"/></radialGradient><radialGradient id="iF13Zub" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.239 16.3)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="ikPvBae" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 9.227 10.119)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="iQzT0we" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.835 8.622)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="arr7-5bxc"/><stop offset="1" class="mejh1wbdq"/></radialGradient><radialGradient id="iQ1m9ie" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 6.844 20.02)scale(1.88642 1.51516)" gradientUnits="userSpaceOnUse"><stop class="phvlv-hdf"/><stop offset=".828" class="ty_drcd_b"/></radialGradient><radialGradient id="iEgPt6c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 15.317 19.234)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="iN71iFe" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.677 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="i95Sfsb" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.788 20.406)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="iqaCsjk" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.654 18.525)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="ieAUSEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 16.209 18.828)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="iOrUtUZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 19.145 21.234)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="iLUWkPb" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.932 11.27)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="j0jku5-3m"/><stop offset="1" class="r37diw65a"/></radialGradient><radialGradient id="i5dXj7b" cx="0" cy="0" r="1" gradientTransform="rotate(96.148 5.41 20.242)scale(2.87591 2.5871)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dsgtjgbbb"/><stop offset=".746" class="ofpn5ibfj"/></radialGradient><radialGradient id="i12Edsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 28.08 24.514)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="iDjEvPd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 23.948 25.89)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iWe8iye" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 23.762 27.218)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iY5kxqz" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 23.666 28.484)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iwJu5mb" cx="0" cy="0" r="1" gradientTransform="rotate(155.58 8.829 6.972)scale(8.06812 16.7964)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iF398Wm" cx="0" cy="0" r="1" gradientTransform="rotate(152.301 7.745 7.56)scale(2.45508 2.07416)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="irg0u9d" cx="0" cy="0" r="1" gradientTransform="matrix(.8623 -4.13673 5.28493 1.10165 13.913 16.875)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iJD33hc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.60908 -12.1761 0 15.889 9.444)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="ijVxf6b" cx="0" cy="0" r="1" gradientTransform="rotate(164.652 7.619 6.949)scale(5.79367 9.91095)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iiVLc8a" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17683 1.45515 0 18.53 9.511)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iqpB8sb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3908 1.60593 0 14.182 9.6)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="ir0DJYd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38781 0 0 -4.53462 21.409 11.032)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iW0OTHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.01445 -12.1273 0 16.159 6.719)" gradientUnits="userSpaceOnUse"><stop class="eqbzb2b6l"/><stop offset="1" class="i95005_3u"/></radialGradient><radialGradient id="iwSJJ8d" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.538 -5.722)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iEVmgme" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16.104 14.369)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i4SBeXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.989 6)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="zqw5laobm"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="ik6gntc" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.802 2.844)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="iww4FVb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.46875 8.0624 -.10205 19.239 7.25)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="rfhmcsbwp"/><stop offset="1" class="n6auyzb6w"/></radialGradient><radialGradient id="ir0jK2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.286 10.029)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iu8dHbz" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.506 .634)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikCxSFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.922 10.03)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iEAE4JY" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.636 10.248)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="icELUgW" width="16.15" height="13.5" x="7.909" y="4.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.352941 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1872" result="effect2_innerShadow_4002_1872"/></filter><filter id="iTGrCCb" width="1.329" height="2.379" x="10.072" y="9.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".125"/></filter><filter id="imPwLte" width="1.447" height="2.403" x="20.816" y="9.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".125"/></filter><filter id="iy5chxe" width="14.3" height="12.3" x="8.829" y="17.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/></filter><filter id="iio1fAe" width="6.538" height="5.771" x="12.472" y="16.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".325"/></filter><filter id="isfq9uj" width="2.5" height="2.5" x="18.92" y="26.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".25"/></filter><filter id="iAgUYyb" width="2.5" height="2.5" x="18.92" y="23.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".25"/></filter><filter id="iNMSCDb" width="2.5" height="2.5" x="18.92" y="19.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".25"/></filter><filter id="i0BkE8b" width="1.7" height="1.7" x="19.59" y="27.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1872" result="effect2_innerShadow_4002_1872"/></filter><filter id="i4suNhd" width="1.7" height="1.7" x="19.59" y="23.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1872" result="effect2_innerShadow_4002_1872"/></filter><filter id="iDeepVc" width="1.7" height="1.7" x="19.59" y="19.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1872" result="effect2_innerShadow_4002_1872"/></filter><filter id="i6pg0Tc" width="2.584" height="3.682" x="26.145" y="22.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.529412 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/></filter><filter id="idM8kFd" width="2.238" height="1.809" x="14.98" y="17.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1872" result="effect2_innerShadow_4002_1872"/></filter><filter id="i4V3Tyc" width="5.047" height="11.336" x="23.532" y="14.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.552941 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/></filter><filter id="iGfC4td" width="3.672" height="4.703" x="23.995" y="15.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.662745 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/><feGaussianBlur result="effect2_foregroundBlur_4002_1872" stdDeviation=".05"/></filter><filter id="iOxSv1d" width="4.618" height="5.556" x="23.762" y="24.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/></filter><filter id="iwNnkVb" width="2.047" height=".25" x="24.157" y="25.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".05"/></filter><filter id="iFBVcFe" width="2.047" height=".25" x="24.078" y="27.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".05"/></filter><filter id="ibxEctb" width="2.047" height=".25" x="24.157" y="28.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".05"/></filter><filter id="i0HcVNA" width="10.5" height="11.523" x="10.909" y="5.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/></filter><filter id="ik5Xdzc" width="3.877" height="4.9" x="13.959" y="9.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".5"/></filter><filter id="iqUPzkv" width="2.077" height="3.1" x="15.066" y="9.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".05"/></filter><filter id="ie32LRt" width="3.718" height="1.573" x="14.245" y="13.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".05"/></filter><filter id="ijfn9Ed" width="2.339" height="1.19" x="17.694" y="7.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/></filter><filter id="ipn5JKe" width="2.339" height="1.176" x="12.437" y="7.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/></filter><filter id="iQp3Y9c" width="2.305" height="1.06" x="12.406" y="7.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".125"/></filter><filter id="i7y3Z6d" width="2.305" height="1.069" x="17.685" y="7.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".125"/></filter><filter id="igjg1cb" width="14.779" height="5.543" x="8.765" y="2.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/></filter><filter id="iSipXSO" width=".675" height="2.047" x="13.012" y="3.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".05"/></filter><filter id="i9Jj0Sd" width=".675" height="2.047" x="18.6" y="3.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".05"/></filter><filter id="i0WMNuT" width=".98" height="2.537" x="15.669" y="3.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".1"/></filter><filter id="iGTT1rb" width="2.611" height="1.227" x="17.394" y="9.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/></filter><filter id="iAXC7Ud" width="2.611" height="1.227" x="12.206" y="9.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1872"/></filter><filter id="isCBLMe" width=".787" height=".696" x="17.552" y="9.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".05"/></filter><filter id="iWEt65d" width=".891" height=".913" x="18.392" y="9.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".1"/></filter><filter id="iNbd1WL" width=".986" height="1.04" x="13.949" y="9.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".1"/></filter><filter id="iRkMoBb" width=".913" height=".705" x="13.194" y="9.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1872" stdDeviation=".05"/></filter><linearGradient id="i4ugH8a" x1="23.387" x2="15.35" y1="6.381" y2="18.719" gradientUnits="userSpaceOnUse"><stop class="mn9zv68ct"/><stop offset=".845" class="btu9i2bec"/></linearGradient><linearGradient id="ivbTNOc" x1="22.541" x2="21.334" y1="9.994" y2="12.171" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iaOvNPb" x1="10.255" x2="11.713" y1="10.698" y2="10.571" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iQ2ko3d" x1="23.287" x2="26.53" y1="25.819" y2="25.819" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="iN1PdZq" x1="8.27" x2="8.27" y1="30.938" y2="16.875" gradientUnits="userSpaceOnUse"><stop class="da7b97bvf"/><stop offset="1" class="si_znv48i"/></linearGradient><linearGradient id="i0Wq4WI" x1="9.129" x2="8.551" y1="26.563" y2="26.563" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="iEmVfrc" x1="9.129" x2="13.066" y1="27.149" y2="27.149" gradientUnits="userSpaceOnUse"><stop class="t81o0ct1j"/><stop offset="1" class="v6vn_tcph"/></linearGradient><linearGradient id="injVVud" x1="16.738" x2="13.777" y1="22.069" y2="18.684" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="ixLTEWb" x1="20.958" x2="19.689" y1="27.582" y2="28.989" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iyhhPMd" x1="20.958" x2="19.689" y1="23.943" y2="25.349" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="ilewkNS" x1="20.958" x2="19.689" y1="20.312" y2="21.719" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="igSwaEd" x1="16.833" x2="17.817" y1="17.938" y2="19.109" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="iTUreAm" x1="16.348" x2="16.348" y1="18.828" y2="17.389" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="ilWVfxH" x1="27.79" x2="23.762" y1="27.983" y2="27.983" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="it5Mcpe" x1="25.962" x2="24.126" y1="25.898" y2="25.898" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="iCntard" x1="25.884" x2="24.048" y1="27.203" y2="27.203" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="iBcw8Fd" x1="25.962" x2="24.126" y1="28.508" y2="28.508" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="iDtveyb" x1="16.105" x2="16.959" y1="11.658" y2="11.658" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="i8WbTSb" x1="15.032" x2="16.106" y1="11.503" y2="11.562" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iAbViEe" x1="16.105" x2="16.105" y1="12.057" y2="12.909" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="i4dOyde" x1="16.105" x2="16.105" y1="9.81" y2="10.229" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iP6uMLb" x1="16.739" x2="16.739" y1="7.719" y2="7.031" gradientUnits="userSpaceOnUse"><stop class="co6smusrg"/><stop offset="1" class="bs-097z7j"/></linearGradient><linearGradient id="iN04oRc" x1="13.485" x2="12.907" y1="5.571" y2="5.474" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ka0ki7btw"/><stop offset="1" class="r64vbvf7r"/></linearGradient><linearGradient id="i5SixOe" x1="18.747" x2="19.38" y1="5.38" y2="5.474" gradientUnits="userSpaceOnUse"><stop offset=".246" class="qu7pewj0n"/><stop offset="1" class="g79jbcb8w"/></linearGradient><linearGradient id="iIkhyOc" x1="16.448" x2="16.448" y1="5.716" y2="3.688" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mzy53gozy"/><stop offset="1" class="zwaih9noa"/></linearGradient><linearGradient id="iEvuIud" x1="19.064" x2="18.751" y1="10.083" y2="10.276" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivy4pqd" x1="14.666" x2="14.352" y1="10.083" y2="10.276" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-cook" /></template>
<style>
.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.arr7-5bxc {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
}

.at6a40j7p {
  d: path("M20.44 21.56a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b3mtuebqr {
  stop-color: var(--svg-color--e9dae3, #E9DAE3);
}

.bfzcp6bwm {
  d: path("M21.19 28.08a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.br4vp4byh {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
}

.bs-097z7j {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
  stop-opacity: 0;
}

.bsq_nvbhc {
  d: path("M18.312 18.634c-.67-.923-1.704-1.194-2.096-1.245c-.205.83-.308 2.667.684 3.564c.635.574 1.077.722 1.67.786c.163.018.268-.164.221-.321c-.03-.1-.051-.22-.053-.366c-.01-.634.109-1.68-.426-2.418");
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bwu2-2wyh {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M16.11 15.42c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.5c0-3.421-1.554-6.482-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co6smusrg {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
}

.cxx4_cgxb {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.837 8.115a1.85 1.85 0 0 0-.687-.412c-.304-.096-.685-.121-1.213-.057a.277.277 0 1 0 .068.55c.48-.058.776-.028.978.036c.198.063.333.164.49.3a.277.277 0 0 0 .364-.417");
}

.d8am9zbor {
  d: path("M14.736 10.34c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.d8t95rbxw {
  stop-color: var(--svg-color--aa7aa4, #AA7AA4);
}

.d9jlp6fce {
  stop-color: var(--svg-color--b1203d, #B1203D);
}

.da588nbds {
  d: path("M20.44 25.19a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.da7b97bvf {
  stop-color: var(--svg-color--b59ccc, #B59CCC);
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dsgtjgbbb {
  stop-color: var(--svg-color--e4976b, #E4976B);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e0vlk9b5p {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.754 13.331c.39.204.854.32 1.35.32c.501 0 .961-.116 1.351-.32a.23.23 0 0 1 .272.045a.214.214 0 0 1 .023.272m-2.996-.317l2.934.276m-2.934-.276h-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27m.295-.317l-.233.276m3.23.041l-.063-.041m.062.041l-.062-.041m.062.041c-.348.528-.955.88-1.646.88c-.69 0-1.297-.351-1.645-.88m3.229-.041a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.062.042l.062-.042m-.062.042l.062-.042");
}

.ed-0_pbdm {
  d: path("M16.104 13.726c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.085-.198.209c.335.508.919.846 1.583.846c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.en78occrq {
  fill: var(--svg-color--bfa9d1, #BFA9D1);
  d: path("M20.17 25.335a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.eqbzb2b6l {
  stop-color: var(--svg-color--db8a27, #DB8A27);
}

.eze2rhbqa {
  d: path("M11.05 8.97a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.199");
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fr8y_ibbz {
  d: path("M15.869 3.688h.58v2.137h-.58z");
}

.frvthebdh {
  stop-color: var(--svg-color--a498b2, #A498B2);
  stop-opacity: 0;
}

.fs29nabkl {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvfz9ra4u {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M11.067 9.632a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.fye21xbob {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.618 10.31l-.635 1.84c-.108.377.152.755.52.755h.787c.37 0 .63-.383.52-.756l-.53-1.838c-.114-.407-.542-.407-.662 0");
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g79jbcb8w {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
  stop-opacity: 0;
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gm83zy8rh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.496 9.28c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.231a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gt-1-ac7u {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
}

.gz3n1jouz {
  d: path("M27.112 23.008a.97.97 0 0 1 .967.967v2.214h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.h0z263bik {
  d: path("M18.223 9.74c.063.086-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.h7p6_nr3r {
  fill: var(--svg-color--c1a0c0, #C1A0C0);
  d: path("M20.17 21.706a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hc4bqpbdd {
  stop-color: var(--svg-color--cb7812, #CB7812);
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.hrk8a5b8c {
  d: path("M18.289 9.552a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.i8yd0cbcz {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.714 9.28c-.654 0-1.205.45-1.355 1.059a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.i95005_3u {
  stop-color: var(--svg-color--db8a27, #DB8A27);
  stop-opacity: 0;
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijtsnweaq {
  d: path("M20.194 7.248H16.88c-1.314 0-2.508-.595-3.244-1.657a.272.272 0 0 0-.478.048l-.08.195a2.34 2.34 0 0 1-1.234 1.238a.4.4 0 0 1-.11.049c-.248.117-.816.487-.825 1.452l.139 3.236c.12 2.865 2.379 4.785 5.115 4.785c2.738 0 4.997-1.92 5.116-4.785l.13-3.08c-.02-1.355-1.026-1.481-1.215-1.481");
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.j0jku5-3m {
  stop-color: var(--svg-color--f4b183, #F4B183);
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jjgs19bwd {
  stop-color: var(--svg-color--b95510, #B95510);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jr673vojc {
  d: path("M23.909 10.697a3.5 3.5 0 0 0-.562-1.911c-.545-.847-1.488-1.201-1.488-1.862v-.01c0-.92-.138-1.761-.493-2.382H11.05c-.305.62-.394 1.461-.394 2.382v.01c0 .66-1.203 1.127-1.685 1.862a3.5 3.5 0 0 0-.561 1.911c0 .54.118 1.04.335 1.501c.069.15.069.33 0 .48c-.217.45-.335.951-.335 1.482c0 1.861 1.487 3.372 3.32 3.372h8.859c1.833 0 3.32-1.51 3.32-3.372c0-.53-.118-1.031-.335-1.482a.58.58 0 0 1 0-.48c.217-.46.336-.97.336-1.501");
}

.k70x9fbeh {
  fill: var(--svg-color--000, #000);
  d: path("M17.777 10.445a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.236");
}

.ka0ki7btw {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
}

.kb3z53baa {
  d: path("m18.7 5.825l.474-1.847v1.847z");
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.khuqv_blc {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.731 8.278c.257-.184.898-.509 1.655-.381");
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.l-jt33s2g {
  stop-color: var(--svg-color--c8680b, #C8680B);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l8-517ayn {
  fill: var(--svg-color--eca779, #ECA779);
  d: path("M26.51 21.124c0-.406.259-.758.567-1.021c.605-.517 1.002-1.392 1.002-2.384c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.568.615.568 1.02v5.057h1.406z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.mejh1wbdq {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
  stop-opacity: 0;
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mn9zv68ct {
  stop-color: var(--svg-color--ffc92e, #FFC92E);
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.mtsctzv2d {
  d: path("M23.539 18.306H8.69a10.94 10.94 0 0 1 7.42-2.885c3.483 0 5.152.811 7.429 2.885");
}

.mzy53gozy {
  stop-color: var(--svg-color--a990c1, #A990C1);
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n3m1ezf2x {
  cx: 25.806px;
  cy: 17.664px;
  rx: 1.711px;
  ry: 2.227px;
}

.n6auyzb6w {
  stop-color: var(--svg-color--b1a3bf, #B1A3BF);
}

.nhiplpbid {
  d: path("M21.026 12.17q.1-1.596.185-3.19a1.61 1.61 0 0 1-.185 3.19");
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.o3lv9vb9b {
  stop-color: var(--svg-color--cb7812, #CB7812);
  stop-opacity: 0;
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.ocwbw1bfb {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M21.066 11.52q.059-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofju7ulzd {
  stop-color: var(--svg-color--b95510, #B95510);
  stop-opacity: 0;
}

.ofpn5ibfj {
  stop-color: var(--svg-color--e29457, #E29457);
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pbjnplbdd {
  cx: 13.651px;
  cy: 9.933px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.pf8e19bhl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.204 27.203H26");
}

.pfz9oobhy {
  fill: var(--svg-color--c4abda, #C4ABDA);
  d: path("M20.92 28.226a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.phvlv-hdf {
  stop-color: var(--svg-color--ffdf46, #FFDF46);
}

.pi2b9hbek {
  d: path("M15.843 17.446c-.385.032-1.405.252-2.103 1.143c-.469.599-.498 1.44-.52 2.068q-.004.177-.013.326a1.4 1.4 0 0 1-.07.363c-.054.154.04.342.2.332c.58-.036 1.018-.163 1.664-.706c.492-.413.742-1.062.85-1.716c.044.662.23 1.332.678 1.792c.59.604 1.013.773 1.587.866c.158.026.27-.151.231-.31a1.4 1.4 0 0 1-.034-.368q.007-.15.019-.326c.04-.627.095-1.467-.313-2.11c-.607-.954-1.6-1.274-1.98-1.344a5 5 0 0 0-.127.583a5 5 0 0 0-.07-.593");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pobhhfhpo {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M13.598 9.215c.766.039 1.1.422 1.219.613l-2.012.461c-.14.008-.484-.086-.562-.246a.31.31 0 0 1 .05-.363c.176-.203.675-.497 1.305-.465");
}

.ppe49ccog {
  d: path("M23.13 29.95h4v-3.5c0-3.421-1.554-6.482-4-8.498z");
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.qakha17bf {
  stop-color: var(--svg-color--c8680b, #C8680B);
  stop-opacity: 0;
}

.qgrespbqh {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M18.613 9.215c-.766.039-1.099.422-1.219.613l2.012.461c.14.008.484-.086.562-.246a.31.31 0 0 0-.05-.363c-.176-.203-.674-.497-1.305-.465");
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qu7pewj0n {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2y81xbdv {
  d: path("m15.722 10.115l-.531 1.838c-.109.379.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.r37diw65a {
  stop-color: var(--svg-color--f4b183, #F4B183);
  stop-opacity: 0;
}

.r64vbvf7r {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
  stop-opacity: 0;
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.r7svlnonw {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
  stop-opacity: 0;
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rfhmcsbwp {
  stop-color: var(--svg-color--eee3f8, #EEE3F8);
}

.rmxffvb1r {
  d: path("M26.51 21.124c0-.406.259-.758.567-1.021c.605-.517 1.002-1.392 1.002-2.384c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.568.615.568 1.02v5.057h1.406z");
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.sebbmcv5r {
  d: path("M10.699 2.036a1.933 1.933 0 0 0-.682 3.743a.215.215 0 0 1 .143.198v1.051c0 .249.201.45.45.45h11.099a.45.45 0 0 0 .45-.45V5.973c0-.088.059-.165.142-.197a1.934 1.934 0 0 0-.69-3.74z");
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.sxxvir8ge {
  d: path("M13.917 18.634c.67-.923 1.704-1.194 2.096-1.245c.206.83.308 2.667-.683 3.564c-.635.574-1.078.722-1.67.786c-.164.018-.27-.164-.222-.321c.03-.1.051-.22.053-.366c.01-.634-.109-1.68.426-2.418");
}

.sznpyw3vg {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.665 8.24c-.282-.298-.897-.51-1.655-.382");
}

.t81o0ct1j {
  stop-color: var(--svg-color--9e8fad, #9E8FAD);
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tuhkblbbb {
  d: path("M23.762 25.246c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.406-.657");
}

.txq537bby {
  stop-color: var(--svg-color--d8c4e9, #D8C4E9);
}

.txvr2mg9h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.282 28.508h1.796");
}

.ty_drcd_b {
  stop-color: var(--svg-color--f9c116, #F9C116);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.udhq7ablm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.223 9.74c.063.086-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6vn_tcph {
  stop-color: var(--svg-color--c0b0d1, #C0B0D1);
  stop-opacity: 0;
}

.v86u-prji {
  d: path("M9.13 17.95h10.052c2.176 0 3.947 1.797 3.947 4.004v7.997h-14z");
}

.vazf9obcy {
  d: path("M15.442 17.508c.19-.063.44-.119.707-.119s.517.056.707.12a.39.39 0 0 1 .254.45c-.092.486-.269.8-.463.989a.5.5 0 0 1-.268.13a1.5 1.5 0 0 1-.476 0a.43.43 0 0 1-.252-.13c-.194-.189-.371-.503-.464-.99a.39.39 0 0 1 .255-.45");
}

.vg9fp6e2d {
  d: path("M19.083 10.327a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vt32lr6la {
  d: path("M9.13 17.924a10.96 10.96 0 0 0-4 8.477v3.55h4z");
}

.vyfoh_bai {
  d: path("m13.587 5.825l-.475-1.847v1.847z");
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w4scbcb6a {
  d: path("M22.185 5.875H10.132a.2.2 0 0 1 .028.102v1.051c0 .249.201.45.45.45h11.1a.45.45 0 0 0 .45-.45V5.973a.2.2 0 0 1 .025-.098");
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wn_wkkbea {
  d: path("M13.92 9.552a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xl0z3lbkl {
  fill: var(--svg-color--000, #000);
  d: path("M14.431 10.445a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.236");
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.ygyrfpbde {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
}

.yidy664bk {
  stop-color: var(--svg-color--c88714, #C88714);
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.yrbhdtb5l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.282 25.898h1.796");
}

.yrzv-0byt {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
  stop-opacity: 0;
}

.ysgnr6bpv {
  d: path("M16.11 15.42c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.5c0-3.421-1.554-6.482-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.z_-5ztb3t {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.694 7.998a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zibvjpbta {
  cx: 13.651px;
  cy: 9.933px;
  rx: 0.39px;
  ry: 0.197px;
}

.zqw5laobm {
  stop-color: var(--svg-color--aa92c2, #AA92C2);
}

.zwaih9noa {
  stop-color: var(--svg-color--a990c1, #A990C1);
  stop-opacity: 0;
}

</style>
