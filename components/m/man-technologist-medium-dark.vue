<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iXfuvfb)" class="t33_u7ubh"/><path fill="url(#iMZ8Eib)" class="t33_u7ubh"/><path class="oylgkib-f"/><path fill="url(#iSnFPVc)" class="e894g4uve"/><path fill="url(#iP2bdsd)" class="e894g4uve"/><path fill="url(#i0ssEFe)" class="gsb4pmijh"/><path fill="url(#icQek1d)" class="ck7n5tgmp"/><path fill="url(#iKsVOQe)" class="ofy_3cbpe"/><g filter="url(#ieYXCOb)"><circle fill="url(#iqtYH3N)" class="nfhvlubqq"/></g><g filter="url(#isLlzkd)"><circle fill="url(#ibhsULm)" class="vwpcicbfm"/></g><g filter="url(#iM9z5uP)"><circle fill="url(#iwjplsc)" class="jpgm3tbkg"/><circle fill="url(#iA7ThOT)" class="jpgm3tbkg"/></g><g filter="url(#i6Hbkpd)"><circle class="zsaest8xc"/><circle fill="url(#iZsF8cc)" class="y7e0xvbzp"/><circle fill="url(#iStbv9c)" class="y7e0xvbzp"/></g><g filter="url(#iHwtN9q)"><path fill="url(#iT5CMsc)" class="jd5r3t3ng"/><path fill="url(#iOQqoFN)" class="jd5r3t3ng"/><path fill="url(#iseXwOc)" class="jd5r3t3ng"/></g><path fill="url(#iwyKyqC)" class="lxd2cfblj"/><path fill="url(#i0JJywd)" class="lxd2cfblj"/><path fill="url(#i1YesFc)" class="lxd2cfblj"/><path fill="url(#iYwnuXc)" class="lxd2cfblj"/><path fill="url(#iIzrrXd)" class="lxd2cfblj"/><g filter="url(#iPKshCe)"><path fill="url(#izXILYd)" class="oov_job6w"/></g><g filter="url(#iIFqlPd)"><path class="hgy5xclcz"/><path fill="url(#iXYU3kj)" class="rojh-xb-t"/><path fill="url(#iky4W4d)" class="rojh-xb-t"/><path fill="url(#iLr0U9X)" class="rojh-xb-t"/><path fill="url(#iRje9xc)" class="rojh-xb-t"/></g><g filter="url(#iyQSggc)"><path class="nqst9n0_f"/></g><g filter="url(#iDlScde)"><path class="gcx7izcfd"/><path fill="url(#iq85Xec)" class="f7dil5b8w"/><path fill="url(#iG7a1td)" class="f7dil5b8w"/><path fill="url(#iyt0gcw)" class="f7dil5b8w"/><path fill="url(#iQoXnxb)" class="f7dil5b8w"/></g><path fill="url(#iHM84le)" class="f7dil5b8w"/><path stroke="url(#iuzIKtS)" class="rgtci2n8n"/><g filter="url(#iV5PDvd)"><path class="c7xw5lv6b"/><path fill="url(#iy9a8Zc)" class="wrkny_8zn"/></g><g filter="url(#idMMOFb)"><path class="dv-r9qbkl"/><path fill="url(#if4sCfe)" class="p59ia8_vz"/></g><path class="diccegtzr"/><path fill="url(#iE3ID0w)" class="dbruw5zjj"/><path class="uh1bc69mr"/><g filter="url(#iQBc5md)"><path class="xyaiqyb1d"/><path fill="url(#iQFt9ze)" class="yjh853bae"/></g><g filter="url(#iGUd0bc)"><path fill="url(#iFqIuGd)" class="hzd4ywoql"/></g><path class="eem5nwbbx"/><path fill="url(#ivAnQod)" class="g49k12bkp"/><path class="ubfq5hbjz"/><g filter="url(#iJlibCF)"><path fill="url(#iU2Zckg)" class="gsipefysf"/></g><g filter="url(#iCsBCCc)"><ellipse transform="rotate(-27.914 13.529 10.166)" class="xf3coib0e"/><ellipse fill="url(#iN3uMDe)" transform="rotate(-27.914 13.529 10.166)" class="i04-0zb8e"/></g><g filter="url(#iURfpAc)"><path stroke="url(#isksIyb)" class="puthitbkq"/></g><g filter="url(#iagua3b)"><path stroke="url(#ir1O7bd)" class="t058gv1zl"/></g><g filter="url(#iSMx1Zc)"><path stroke="url(#ilcSQDe)" class="odcp9s_mm"/></g><g filter="url(#iWcRCec)"><path fill="url(#ih7UPDc)" class="rlusx7b3t"/><path fill="url(#ibqe71c)" class="rlusx7b3t"/><path fill="url(#iPSTseb)" class="rlusx7b3t"/><path fill="url(#iwBvMZb)" class="rlusx7b3t"/><path fill="url(#idR73sb)" class="rlusx7b3t"/><path fill="url(#i2ot4bu)" class="rlusx7b3t"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><linearGradient id="iP2bdsd" x1="26.966" x2="27.302" y1="28.483" y2="28.483" gradientUnits="userSpaceOnUse"><stop class="wdf1v2bbt"/><stop offset="1" class="zo7wqerog"/></linearGradient><linearGradient id="i0ssEFe" x1="16" x2="16" y1="6.348" y2="34.257" gradientUnits="userSpaceOnUse"><stop class="zaeth0b6d"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="icQek1d" x1="10.918" x2="1.428" y1="23.649" y2="23.69" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="iKsVOQe" x1="22.998" x2="28.652" y1="23.666" y2="23.666" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ibhsULm" x1="11.234" x2="10.593" y1="11.223" y2="11.223" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iwjplsc" x1="21.844" x2="21.025" y1="9.852" y2="12.391" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iT5CMsc" x1="20.026" x2="12.382" y1="11.334" y2="12.473" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iwyKyqC" x1="10.586" x2="12.469" y1="14.033" y2="13.966" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="i0JJywd" x1="20.855" x2="19.799" y1="13.194" y2="13.093" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="izXILYd" x1="15.454" x2="23.606" y1="8.346" y2="5.428" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iq85Xec" x1="15.122" x2="16.061" y1="11.994" y2="11.994" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iG7a1td" x1="16.926" x2="15.899" y1="12.317" y2="12.302" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iyt0gcw" x1="16.181" x2="16.181" y1="13.06" y2="12.486" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iHM84le" x1="16.112" x2="16.112" y1="13.102" y2="12.934" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="iuzIKtS" x1="14.948" x2="15.384" y1="14.677" y2="13.988" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iFqIuGd" x1="18.946" x2="18.632" y1="10.316" y2="10.509" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iU2Zckg" x1="14.545" x2="14.231" y1="10.316" y2="10.509" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isksIyb" x1="18.962" x2="18.541" y1="8.174" y2="7.315" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ir1O7bd" x1="13.652" x2="12.462" y1="8.046" y2="7.547" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ilcSQDe" x1="11.32" x2="11.32" y1="6.03" y2="8.189" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="ih7UPDc" x1="7.493" x2="11.284" y1="19.4" y2="30.45" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="iPSTseb" x1="16" x2="16" y1="15.665" y2="17.025" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="iwBvMZb" x1="5" x2="6.055" y1="23.9" y2="23.9" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="idR73sb" x1="27" x2="25.524" y1="24.837" y2="24.837" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><radialGradient id="iXfuvfb" cx="0" cy="0" r="1" gradientTransform="matrix(2.80769 -1.3591 1.47615 3.04949 2.748 29.664)" gradientUnits="userSpaceOnUse"><stop offset=".406" class="b2ikzlbxr"/><stop offset="1" class="h9k8kg5xs"/></radialGradient><radialGradient id="iMZ8Eib" cx="0" cy="0" r="1" gradientTransform="rotate(177.157 2.336 14.816)scale(3.35044 4.79049)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="j571032gg"/><stop offset=".927" class="l_zar3b8g"/></radialGradient><radialGradient id="iSnFPVc" cx="0" cy="0" r="1" gradientTransform="matrix(5.64062 -3.71875 1.03844 1.57511 27.091 29.764)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="d_syq5qya"/><stop offset="1" class="no4na2b-l"/></radialGradient><radialGradient id="iqtYH3N" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.563 10.944)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iA7ThOT" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.129 10.68)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iZsF8cc" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.715 11.766)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iStbv9c" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.757 10.944)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iOQqoFN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.335 9.672)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iseXwOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 13.773 9.806)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="i1YesFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.99354 9.17734 -12.4577 -1.34868 16.678 8.846)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset=".89" class="ryqb3lb7d"/></radialGradient><radialGradient id="iYwnuXc" cx="0" cy="0" r="1" gradientTransform="rotate(-146.07 12.7 5.344)scale(2.07148 1.17905)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="iIzrrXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.54454 .34491 1.64288 12.347 17.898)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="iXYU3kj" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.63 -9.858)scale(3.06527 1.47592)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iky4W4d" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.692 5.073)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iLr0U9X" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.987 2.335)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iRje9xc" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.532 9.16)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iQoXnxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.314 12.552)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iy9a8Zc" cx="0" cy="0" r="1" gradientTransform="matrix(.1043 -.60384 1.78641 .30854 18.432 8.858)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="if4sCfe" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.9 -3.456)scale(.61278 1.81296)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iE3ID0w" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.168 10.261)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iQFt9ze" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.939 10.346)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivAnQod" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.8 10.262)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iN3uMDe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.916 -1.412)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibqe71c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 30.712)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="i2ot4bu" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.306)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><filter id="ieYXCOb" width="3.542" height="3.342" x="9.563" y="9.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_990"/></filter><filter id="isLlzkd" width="2.992" height="2.992" x="9.738" y="9.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".25"/></filter><filter id="iM9z5uP" width="3.592" height="3.592" x="19.085" y="9.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_990"/></filter><filter id="i6Hbkpd" width="2.992" height="2.992" x="19.261" y="9.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".25"/></filter><filter id="iHwtN9q" width="10.383" height="12.189" x="10.824" y="5.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_990"/></filter><filter id="iPKshCe" width="8.25" height="7.07" x="14.157" y="3.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation="1"/></filter><filter id="iIFqlPd" width="12.614" height="8.551" x="9.68" y="1.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_990"/></filter><filter id="iyQSggc" width="3.262" height="4.184" x="14.117" y="9.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".375"/></filter><filter id="iDlScde" width="2.379" height="3.184" x="14.797" y="10.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".125"/></filter><filter id="iV5PDvd" width="2.982" height="1.874" x="17.17" y="7.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_990"/></filter><filter id="idMMOFb" width="2.982" height="1.874" x="12.017" y="7.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_990"/></filter><filter id="iQBc5md" width=".787" height=".697" x="17.433" y="9.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".05"/></filter><filter id="iGUd0bc" width=".892" height=".914" x="18.274" y="9.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".1"/></filter><filter id="iJlibCF" width=".987" height="1.041" x="13.828" y="9.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".1"/></filter><filter id="iCsBCCc" width=".914" height=".705" x="13.072" y="9.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".05"/></filter><filter id="iURfpAc" width="3.101" height="1.681" x="17.024" y="7.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".25"/></filter><filter id="iagua3b" width="3.179" height="1.739" x="11.799" y="7.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".25"/></filter><filter id="iSMx1Zc" width="1.008" height="2.271" x="10.816" y="5.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_990" stdDeviation=".125"/></filter><filter id="iWcRCec" width="22" height="14.1" x="5" y="15.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_990"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-technologist-medium-dark" /></template>
<style>
.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.auud8yb7i {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

.b2ikzlbxr {
  stop-color: var(--svg-color--86615a, #86615A);
}

.bowxt9bwr {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c7xw5lv6b {
  fill: var(--svg-color--352827, #352827);
  d: path("m19.71 8.222l-.002-.001l-.001-.002l-.005-.003l-.012-.01a2 2 0 0 0-.155-.108c-.1-.062-.241-.14-.42-.21a2.84 2.84 0 0 0-1.494-.159a.534.534 0 0 0 .166 1.055c.399-.062.717.01.935.097a1.5 1.5 0 0 1 .309.166a.534.534 0 0 0 .679-.825");
}

.ck7n5tgmp {
  d: path("M8.98 17.665a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d_syq5qya {
  stop-color: var(--svg-color--a78075, #A78075);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.dbruw5zjj {
  d: path("M18.17 9.784a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.diccegtzr {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.377 9.512c.653 0 1.205.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.dv-r9qbkl {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.21 8.222l.002-.002l.004-.003l.012-.01a2 2 0 0 1 .155-.108c.1-.062.242-.14.42-.21a2.83 2.83 0 0 1 1.495-.159a.534.534 0 0 1-.167 1.055a1.77 1.77 0 0 0-.935.097a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.68-.825");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e894g4uve {
  d: path("M29.938 29.665q.005-.08.005-.163a3.138 3.138 0 1 0-6.272.163z");
}

.eem5nwbbx {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.591 9.512c-.653 0-1.205.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f7dil5b8w {
  d: path("m15.604 10.659l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.ft5dv1b6b {
  fill: none;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.g49k12bkp {
  d: path("M13.798 9.784a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gcx7izcfd {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.604 10.659l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gsb4pmijh {
  d: path("M16 15.165c-6.07 0-11 4.92-11 11v3.5h22v-3.5c0-6.08-4.93-11-11-11");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gsipefysf {
  d: path("M14.614 10.572c0-.288-.234-.48-.298-.539l-.289.28l.178.36z");
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.h9k8kg5xs {
  stop-color: var(--svg-color--714d45, #714D45);
}

.hgy5xclcz {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m20.81 4.46l.43.214c.751.374 1.18 1.228 1.02 2.135l-.59 3.043c-.054.315-.261.526-.573.534h-.019s.054-.907.108-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854v-.854c0-.267-.215-.481-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.747c.053.588.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.59-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.362.533l.806.801c.215.267.483.427.805.587");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hzd4ywoql {
  d: path("M18.965 10.56a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.i04-0zb8e {
  cx: 13.529px;
  cy: 10.166px;
  rx: 0.39px;
  ry: 0.197px;
}

.j571032gg {
  stop-color: var(--svg-color--9b7469, #9B7469);
  stop-opacity: 0;
}

.jd5r3t3ng {
  d: path("m10.882 10.33l.05.003s-.055-.855-.108-1.442c0-.267.107-.587.322-.747l.16-.16c.27-.214.377-.534.377-.854v-.855a.52.52 0 0 1 .43-.533c.644-.16 1.986-.428 3.919-.428s3.275.267 3.919.428c.215.053.43.266.43.533v.855c0 .32.16.64.375.854c.503.352.472.546.43.96a46 46 0 0 0-.108 1.442h.019l-.267 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.213c-1.714 0-3.053-1.235-3.214-3.006z");
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jpgm3tbkg {
  cx: 20.756px;
  cy: 10.944px;
  r: 1.671px;
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
}

.l_zar3b8g {
  stop-color: var(--svg-color--9b7469, #9B7469);
}

.l17xqebtl {
  stop-color: var(--svg-color--594170, #594170);
}

.l294t3zvi {
  stop-color: var(--svg-color--847498, #847498);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lxd2cfblj {
  d: path("M10.824 8.891c0-.267.107-.587.322-.747l.16-.16c.27-.214.377-.534.377-.854v-.855a.52.52 0 0 1 .43-.533c.644-.16 1.986-.428 3.919-.428s3.275.267 3.919.428c.215.053.43.266.43.533v.855c0 .32.16.64.375.854c.503.352.472.546.43.96a46 46 0 0 0-.108 1.442h.019l-.267 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.213c-1.714 0-3.053-1.235-3.214-3.006c-.14-1.818-.2-3.642-.366-5.457");
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nfhvlubqq {
  cx: 11.234px;
  cy: 10.944px;
  r: 1.671px;
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.no4na2b-l {
  stop-color: var(--svg-color--a78075, #A78075);
  stop-opacity: 0;
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.nqst9n0_f {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.71 10.822l-.82 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.489-.7l-.499-1.7c-.107-.378-.283-.378-.395 0");
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odcp9s_mm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.45 6.128v.899c-.008.149-.071.481-.259.622");
}

.ofy_3cbpe {
  d: path("M23 17.675v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.ohv650iba {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

.oov_job6w {
  d: path("m19.954 5.314l-3.08 1.027a1.048 1.048 0 0 0 .47 2.034l3.063-.41z");
}

.oylgkib-f {
  fill: var(--svg-color--936e5f, #936E5F);
  d: path("M29.938 29.665q.005-.08.005-.163a3.138 3.138 0 1 0-6.272.163z");
}

.p59ia8_vz {
  d: path("m12.21 8.222l.002-.002l.004-.003l.012-.01a2 2 0 0 1 .155-.108c.1-.062.242-.14.42-.21a2.83 2.83 0 0 1 1.495-.159a.534.534 0 0 1-.167 1.055a1.77 1.77 0 0 0-.935.097a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.68-.825");
}

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.puthitbkq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.649 8.077c.43-.075 1.27-.054 1.85.398");
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qqk6g6zlh {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

.qufyc6r7b {
  stop-color: var(--svg-color--56416b, #56416B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rgtci2n8n {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.623 13.704a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24c.344.521.943.868 1.625.868c.683 0 1.282-.347 1.627-.868a.19.19 0 0 0-.021-.242a.204.204 0 0 0-.242-.04a2.94 2.94 0 0 1-1.364.323c-.5 0-.969-.117-1.363-.323Z");
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.rlusx7b3t {
  d: path("M26.03 15.665H5.97a.97.97 0 0 0-.97.97v13.03h22v-13.03a.97.97 0 0 0-.97-.97");
}

.rojh-xb-t {
  d: path("m20.81 4.46l.43.214c.751.374 1.18 1.228 1.02 2.135l-.59 3.043c-.054.315-.261.526-.573.534h-.019s.054-.907.108-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854v-.854c0-.267-.215-.481-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.747c.053.588.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.59-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.362.533l.806.801c.215.267.483.427.805.587");
}

.ryqb3lb7d {
  stop-color: var(--svg-color--6f3f4d, #6F3F4D);
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.t058gv1zl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.424 8.596c.328-.29 1.043-.594 1.93-.453");
}

.t33_u7ubh {
  d: path("M8.329 29.665q.004-.08.004-.163a3.138 3.138 0 1 0-6.271.163z");
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.ubfq5hbjz {
  fill: var(--svg-color--000, #000);
  d: path("M14.31 10.678a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.236");
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uem0lbchq {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

.uh1bc69mr {
  fill: var(--svg-color--000, #000);
  d: path("M17.658 10.678a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.236");
}

.ux-m5bn7d {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

.v1n2dlbml {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.vwpcicbfm {
  cx: 11.234px;
  cy: 10.944px;
  r: 0.996px;
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.wdf1v2bbt {
  stop-color: var(--svg-color--8c655d, #8C655D);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wrkny_8zn {
  d: path("m19.71 8.222l-.002-.001l-.001-.002l-.005-.003l-.012-.01a2 2 0 0 0-.155-.108c-.1-.062-.241-.14-.42-.21a2.84 2.84 0 0 0-1.494-.159a.534.534 0 0 0 .166 1.055c.399-.062.717.01.935.097a1.5 1.5 0 0 1 .309.166a.534.534 0 0 0 .679-.825");
}

.xf3coib0e {
  cx: 13.529px;
  cy: 10.166px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.xyaiqyb1d {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.104 9.973c.064.085-.07.189-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.36c.151-.112.325-.135.389-.05");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y7e0xvbzp {
  cx: 20.756px;
  cy: 10.944px;
  r: 0.996px;
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yjh853bae {
  d: path("M18.104 9.973c.064.085-.07.189-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.36c.151-.112.325-.135.389-.05");
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zo7wqerog {
  stop-color: var(--svg-color--8c655d, #8C655D);
  stop-opacity: 0;
}

.zsaest8xc {
  cx: 20.756px;
  cy: 10.944px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

</style>
