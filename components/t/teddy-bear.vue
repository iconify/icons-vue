<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="v9fj7ubjn"/><circle fill="url(#ib7x7pk)" class="mzpme7d0f"/><circle fill="url(#ilzZynq)" class="mzpme7d0f"/><circle fill="url(#iwBz26S)" class="mzpme7d0f"/><circle class="k29ixq3pv"/><circle fill="url(#iyfOZDe)" class="balo6sb9q"/><circle fill="url(#i0aLSIb)" class="balo6sb9q"/><g filter="url(#i8Iixhd)"><circle stroke="url(#iPZSrCc)" class="quud0g0ia"/></g><circle fill="url(#i2CO3Kb)" class="rb2t10bdg"/><circle class="ivctto4sj"/><circle fill="url(#isnOO8b)" class="ey96j5viv"/><g filter="url(#ijhfuZb)"><rect transform="rotate(31.389 19.087 12.797)" class="hni2rhbgu"/><rect fill="url(#iUgrJwb)" transform="rotate(31.389 19.087 12.797)" class="p6a90ny3i"/><rect fill="url(#i9A2r3d)" transform="rotate(31.389 19.087 12.797)" class="p6a90ny3i"/><rect fill="url(#ijqyf5b)" transform="rotate(31.389 19.087 12.797)" class="p6a90ny3i"/><rect fill="url(#iSQr4Rc)" transform="rotate(31.389 19.087 12.797)" class="p6a90ny3i"/></g><g filter="url(#iabecdc)"><rect transform="rotate(-30 .962 19.906)" class="rxo9rqvlj"/><rect fill="url(#ijBHVdb)" transform="rotate(-30 .962 19.906)" class="fl3t3lbqn"/><rect fill="url(#ixE9Gpc)" transform="rotate(-30 .962 19.906)" class="fl3t3lbqn"/><rect fill="url(#iZFys5c)" transform="rotate(-30 .962 19.906)" class="fl3t3lbqn"/><rect fill="url(#i3bHJZb)" transform="rotate(-30 .962 19.906)" class="fl3t3lbqn"/></g><g filter="url(#isMuPte)"><path class="fyqry5btj"/></g><circle fill="url(#iFz98Fc)" class="w1w__9bek"/><circle fill="url(#iygHqCc)" class="w1w__9bek"/><circle fill="url(#icTH3Ge)" class="w1w__9bek"/><circle fill="url(#iWJxBxd)" class="w1w__9bek"/><circle fill="url(#ikvmuPt)" class="w1w__9bek"/><circle fill="url(#isjzPAc)" class="w1w__9bek"/><circle fill="url(#iuHFZUR)" class="w1w__9bek"/><circle fill="url(#iS06Oud)" class="w1w__9bek"/><circle fill="url(#iPR2m3b)" class="w1w__9bek"/><circle fill="url(#idzr4He)" class="bb9empbbe"/><circle fill="url(#iFhFzQd)" class="bb9empbbe"/><circle fill="url(#idG1z4y)" class="bb9empbbe"/><circle fill="url(#icNpGeb)" class="bb9empbbe"/><g filter="url(#iGgE8Bb)"><path fill="url(#i587H0b)" class="vdtorojdb"/><path fill="url(#ingQnic)" class="vdtorojdb"/><path fill="url(#ivWrtLe)" class="vdtorojdb"/><path fill="url(#iPjRaNb)" class="vdtorojdb"/></g><circle fill="url(#igsatcb)" class="ohb6jub4j"/><circle fill="url(#iSrlJUb)" class="y7bs_obzr"/><g filter="url(#iGTSwxS)"><path fill="url(#izcIRFc)" class="audp7ccjm"/><path fill="url(#iA0OScx)" class="audp7ccjm"/></g><g filter="url(#ibUMHMb)"><rect fill="url(#iS0NvMd)" transform="scale(-1 1)rotate(29.237 -43.88 -8.814)" class="jyc5o24ck"/><rect fill="url(#imO2rKb)" transform="scale(-1 1)rotate(29.237 -43.88 -8.814)" class="jyc5o24ck"/></g><g filter="url(#iIoAG5C)"><rect fill="url(#iyg11Nb)" transform="rotate(29.237 22.032 20.308)" class="q40s_bbco"/></g><rect fill="url(#ifLdYDd)" transform="rotate(29.237 22.032 20.308)" class="q40s_bbco"/><rect fill="url(#i2i6Dob)" transform="scale(-1 1)rotate(29.237 -47.558 -6.73)" class="nx5zx9b4w"/><rect fill="url(#i4Qh8Qb)" transform="rotate(29.237 22.581 22.37)" class="wsqdq9etk"/><g filter="url(#irGE4Sc)"><path class="ja25vxt3s"/></g><path fill="url(#ipYEPlO)" class="nvxwnz1ab"/><path fill="url(#ieitkvb)" class="nvxwnz1ab"/><g filter="url(#i4Yz04c)"><path class="tq5ncrblq"/></g><defs><radialGradient id="ib7x7pk" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -1.6875 .50703 -.60093 13.5 3.187)" gradientUnits="userSpaceOnUse"><stop class="vgldytb3a"/><stop offset="1" class="i9xl7o8ji"/></radialGradient><radialGradient id="ilzZynq" cx="0" cy="0" r="1" gradientTransform="rotate(99.562 3.75 7.03)scale(2.12238)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="jwvoze28a"/><stop offset="1" class="wwszs9luy"/></radialGradient><radialGradient id="iwBz26S" cx="0" cy="0" r="1" gradientTransform="rotate(-135 6.585 -.091)scale(2.64742 3.25371)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="uw6xk5b0c"/><stop offset=".979" class="kgx9ntbgv"/></radialGradient><radialGradient id="iyfOZDe" cx="0" cy="0" r="1" gradientTransform="rotate(99.51 8.627 11.164)scale(2.12206)" gradientUnits="userSpaceOnUse"><stop offset=".659" class="vhqsctbie"/><stop offset="1" class="f-s6n3bmn"/></radialGradient><radialGradient id="i0aLSIb" cx="0" cy="0" r="1" gradientTransform="rotate(-143.383 11.45 -1.245)scale(3.18284 2.61524)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="peqo57r7q"/><stop offset=".924" class="mmeo32bod"/></radialGradient><radialGradient id="i2CO3Kb" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 1.48438 -2.7437 2.33937 10.375 3.484)" gradientUnits="userSpaceOnUse"><stop class="av1-h5suw"/><stop offset="1" class="xsl-l-ydr"/></radialGradient><radialGradient id="isnOO8b" cx="0" cy="0" r="1" gradientTransform="rotate(6.915 -25.355 168.826)scale(2.40814)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="r23to2bbq"/><stop offset=".906" class="y2qx6zbae"/></radialGradient><radialGradient id="iUgrJwb" cx="0" cy="0" r="1" gradientTransform="matrix(.49837 -5.06304 7.10362 .69923 28.591 19.901)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="suy9nen1j"/><stop offset="1" class="d02k9hb-w"/></radialGradient><radialGradient id="ijqyf5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.23879 2.48857 -1.63941 -.1573 31.6 13.673)" gradientUnits="userSpaceOnUse"><stop class="mc7qfdqjn"/><stop offset="1" class="kkbtj5bsq"/></radialGradient><radialGradient id="iSQr4Rc" cx="0" cy="0" r="1" gradientTransform="matrix(2.412 -2.49665 3.37173 3.2574 23.912 17.631)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="yj3cfwb4c"/><stop offset="1" class="h4b13sm5j"/></radialGradient><radialGradient id="ixE9Gpc" cx="0" cy="0" r="1" gradientTransform="rotate(153.857 .812 13.509)scale(5.05601 3.6258)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="gy-ksq4cn"/><stop offset="1" class="eq8wpzvsw"/></radialGradient><radialGradient id="iZFys5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.45342 .77775 -.74288 1.38825 2.576 22.315)" gradientUnits="userSpaceOnUse"><stop class="kdhb8bdkj"/><stop offset="1" class="uc1--qr0f"/></radialGradient><radialGradient id="i3bHJZb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64047 -1.3307 2.64549 -3.26132 8.707 24.398)" gradientUnits="userSpaceOnUse"><stop offset=".923" class="c73p6ob0z"/><stop offset="1" class="htt0p9b1b"/></radialGradient><radialGradient id="iygHqCc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.21828 7.81269 -5.09154 -4.05246 22.857 16.509)" gradientUnits="userSpaceOnUse"><stop class="om3wyl1ts"/><stop offset="1" class="yq4d8r-9h"/></radialGradient><radialGradient id="icTH3Ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.87977 -6.87021 0 15.962 14.17)" gradientUnits="userSpaceOnUse"><stop offset=".466" class="haau0jr6r"/><stop offset="1" class="yvh0_2bxk"/></radialGradient><radialGradient id="iWJxBxd" cx="0" cy="0" r="1" gradientTransform="rotate(-125.505 13.914 6.775)scale(10.707 11.7823)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="qumexibjl"/><stop offset=".924" class="zk-zpiszh"/></radialGradient><radialGradient id="ikvmuPt" cx="0" cy="0" r="1" gradientTransform="matrix(2.60423 -.37203 .95666 6.6966 8.4 22.727)" gradientUnits="userSpaceOnUse"><stop class="dqbyczbjf"/><stop offset="1" class="xsxthqbxm"/></radialGradient><radialGradient id="isjzPAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.64755 2.39165 -1.87111 1.28896 11.829 27.086)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="g0ehyjbch"/><stop offset="1" class="nrljhk8yv"/></radialGradient><radialGradient id="iuHFZUR" cx="0" cy="0" r="1" gradientTransform="rotate(136.5 4.883 17.492)scale(3.59022 2.07018)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="x65rjkb3j"/><stop offset="1" class="kn1wetb0m"/></radialGradient><radialGradient id="iS06Oud" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.672 16.634)scale(11.4908)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="n1sa_4xqn"/><stop offset="1" class="ic2uv7oif"/></radialGradient><radialGradient id="iPR2m3b" cx="0" cy="0" r="1" gradientTransform="matrix(1.2224 -2.41821 1.74068 .8799 21.953 23.63)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="qtnth0b-s"/><stop offset="1" class="xlxqo898i"/></radialGradient><radialGradient id="iFhFzQd" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.443 17.405)scale(8.55676)" gradientUnits="userSpaceOnUse"><stop offset=".588" class="vdf-bkbgo"/><stop offset="1" class="pdqvp8k_m"/></radialGradient><radialGradient id="idG1z4y" cx="0" cy="0" r="1" gradientTransform="rotate(151.504 8.484 12.157)scale(4.23316)" gradientUnits="userSpaceOnUse"><stop class="r2vbmqpmh"/><stop offset="1" class="gg6kii_po"/></radialGradient><radialGradient id="icNpGeb" cx="0" cy="0" r="1" gradientTransform="matrix(2.17905 -1.16925 1.98996 3.70856 10.5 24.8)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="q9z2wrb4q"/><stop offset="1" class="n-k-vsbzr"/></radialGradient><radialGradient id="ingQnic" cx="0" cy="0" r="1" gradientTransform="rotate(118.974 8.162 9.967)scale(6.35176 7.55636)" gradientUnits="userSpaceOnUse"><stop class="oi3_akjkh"/><stop offset="1" class="vm_sz40cl"/></radialGradient><radialGradient id="ivWrtLe" cx="0" cy="0" r="1" gradientTransform="rotate(81.87 4.563 11.663)scale(12.015 13.8879)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="jmoupfbeb"/><stop offset="1" class="wlf82t9rv"/></radialGradient><radialGradient id="iPjRaNb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67184 4.01238 -3.33574 -1.3899 15.192 13.026)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="vngvobbex"/><stop offset="1" class="ptsffybue"/></radialGradient><radialGradient id="igsatcb" cx="0" cy="0" r="1" gradientTransform="rotate(142.751 5.604 6.439)scale(.7966)" gradientUnits="userSpaceOnUse"><stop class="q2xrko7st"/><stop offset="1" class="mxmklzbyg"/></radialGradient><radialGradient id="iSrlJUb" cx="0" cy="0" r="1" gradientTransform="rotate(142.561 8.056 7.291)scale(.4627)" gradientUnits="userSpaceOnUse"><stop class="q2xrko7st"/><stop offset="1" class="mxmklzbyg"/></radialGradient><radialGradient id="izcIRFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.85139 -10.7808 0 15.962 9.85)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="qgk8-ccrp"/><stop offset=".965" class="v0lm_7v2w"/></radialGradient><radialGradient id="iA0OScx" cx="0" cy="0" r="1" gradientTransform="rotate(146.39 8.092 7.91)scale(2.11419 2.83605)" gradientUnits="userSpaceOnUse"><stop class="uilz30bbs"/><stop offset="1" class="uae15mswe"/></radialGradient><radialGradient id="imO2rKb" cx="0" cy="0" r="1" gradientTransform="matrix(4.58873 -.35808 .56641 7.25851 -.485 4.612)" gradientUnits="userSpaceOnUse"><stop class="kzaimjh1a"/><stop offset="1" class="e44feabrq"/></radialGradient><radialGradient id="ifLdYDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.76625 .91614 -1.92842 -1.61293 27.322 21.215)" gradientUnits="userSpaceOnUse"><stop class="ldmki_brr"/><stop offset="1" class="t03wtbxnc"/></radialGradient><radialGradient id="ieitkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37347 0 0 -.61667 17.145 10.055)" gradientUnits="userSpaceOnUse"><stop class="psuz65f3v"/><stop offset="1" class="weff0cjzz"/></radialGradient><linearGradient id="iPZSrCc" x1="22.892" x2="22.164" y1="3.593" y2="3.968" gradientUnits="userSpaceOnUse"><stop class="ufehicc4u"/><stop offset="1" class="sqa7i0bti"/></linearGradient><linearGradient id="i9A2r3d" x1="26.099" x2="25.903" y1="12.636" y2="14.476" gradientUnits="userSpaceOnUse"><stop class="wyyqnsb3g"/><stop offset="1" class="xao-tjnxb"/></linearGradient><linearGradient id="ijBHVdb" x1="7.965" x2="7.932" y1="19.198" y2="21.542" gradientUnits="userSpaceOnUse"><stop offset=".203" class="wzyd3t66m"/><stop offset="1" class="uqxq11_cf"/></linearGradient><linearGradient id="iFz98Fc" x1="18.074" x2="18.074" y1="27.723" y2="15.074" gradientUnits="userSpaceOnUse"><stop class="tzkcnpb3n"/><stop offset="1" class="t8nww8bzw"/></linearGradient><linearGradient id="idzr4He" x1="15.962" x2="15.962" y1="16.509" y2="24.694" gradientUnits="userSpaceOnUse"><stop class="d1ldtzbah"/><stop offset="1" class="n8bfwdbok"/></linearGradient><linearGradient id="i587H0b" x1="15.962" x2="15.962" y1="3.889" y2="16.151" gradientUnits="userSpaceOnUse"><stop class="amptegbbc"/><stop offset="1" class="rpnx7_brv"/></linearGradient><linearGradient id="iS0NvMd" x1="3.424" x2="3.671" y1="-.194" y2="8.693" gradientUnits="userSpaceOnUse"><stop class="sgyng1bws"/><stop offset="1" class="fl-ldgbyx"/></linearGradient><linearGradient id="iyg11Nb" x1="25.532" x2="25.532" y1="20.308" y2="28.808" gradientUnits="userSpaceOnUse"><stop class="kknzjndoj"/><stop offset="1" class="fv2p1h30y"/></linearGradient><linearGradient id="i2i6Dob" x1="1.806" x2="1.846" y1=".855" y2="5.918" gradientUnits="userSpaceOnUse"><stop class="l2u_o5cvk"/><stop offset="1" class="hxas9wbft"/></linearGradient><linearGradient id="i4Qh8Qb" x1="24.521" x2="24.554" y1="24.083" y2="29.005" gradientUnits="userSpaceOnUse"><stop class="h91gk7bys"/><stop offset="1" class="hxas9wbft"/></linearGradient><linearGradient id="ipYEPlO" x1="15.962" x2="15.962" y1="9.717" y2="11.348" gradientUnits="userSpaceOnUse"><stop class="pcc287nkr"/><stop offset="1" class="df_125_tk"/></linearGradient><filter id="i8Iixhd" width="5.152" height="5.152" x="18.191" y="1.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3767" stdDeviation=".15"/></filter><filter id="ijhfuZb" width="12.98" height="10.318" x="17.085" y="13.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.25098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3767"/></filter><filter id="iabecdc" width="13.429" height="10.501" x="1.559" y="13.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.341176 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3767"/></filter><filter id="isMuPte" width="11.438" height="8.938" x="18.906" y="13.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3767" stdDeviation="1"/></filter><filter id="iGgE8Bb" width="16.279" height="13.901" x="8.073" y="2.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.498039 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3767"/></filter><filter id="iGTSwxS" width="6.596" height="5.631" x="12.714" y="9.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.568627 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3767"/></filter><filter id="ibUMHMb" width="8.034" height="8.91" x="4.9" y="21.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.407843 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3767"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.4 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3767" result="effect2_innerShadow_18_3767"/></filter><filter id="iIoAG5C" width="8.034" height="8.91" x="18.993" y="21.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.356863 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3767"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.384314 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3767" result="effect2_innerShadow_18_3767"/></filter><filter id="irGE4Sc" width="3.165" height="2.398" x="13.938" y="9.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3767" stdDeviation=".25"/></filter><filter id="i4Yz04c" width="4.25" height="4.824" x="8.608" y="21.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3767" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:teddy-bear" /></template>
<style>
.amptegbbc {
  stop-color: var(--svg-color--ec9d55, #EC9D55);
}

.audp7ccjm {
  d: path("M15.962 9.109c-.473 0-1.506 0-2.515.656c-.85.553-.93 1.875-.4 3.015c.528 1.141 1.425 1.86 2.915 1.86s2.387-.719 2.915-1.86c.529-1.14.45-2.462-.4-3.015c-1.01-.656-2.042-.656-2.515-.656");
}

.av1-h5suw {
  stop-color: var(--svg-color--fecc85, #FECC85);
}

.balo6sb9q {
  cx: 20.712px;
  cy: 4.5px;
  r: 2.5px;
}

.bb9empbbe {
  cx: 15.962px;
  cy: 21.797px;
  r: 5px;
}

.c73p6ob0z {
  stop-color: var(--svg-color--d77c46, #D77C46);
}

.d02k9hb-w {
  stop-color: var(--svg-color--983c50, #983C50);
  stop-opacity: 0;
}

.d1ldtzbah {
  stop-color: var(--svg-color--e6a04e, #E6A04E);
}

.df_125_tk {
  stop-color: var(--svg-color--45323f, #45323F);
}

.dqbyczbjf {
  stop-color: var(--svg-color--c7733e, #C7733E);
}

.e44feabrq {
  stop-color: var(--svg-color--e68f58, #E68F58);
  stop-opacity: 0;
}

.eq8wpzvsw {
  stop-color: var(--svg-color--bb5124, #BB5124);
  stop-opacity: 0;
}

.ey96j5viv {
  cx: 20.712px;
  cy: 4.57px;
  r: 1.618px;
}

.f-s6n3bmn {
  stop-color: var(--svg-color--dc692a, #DC692A);
  stop-opacity: 0;
}

.fl-ldgbyx {
  stop-color: var(--svg-color--da835d, #DA835D);
}

.fl3t3lbqn {
  width: 14px;
  height: 6px;
  x: 0.962px;
  y: 19.906px;
  rx: 3px;
}

.ft5dv1b6b {
  fill: none;
}

.fv2p1h30y {
  stop-color: var(--svg-color--d48461, #D48461);
}

.fyqry5btj {
  stroke: var(--svg-color--fa9c66, #FA9C66);
  stroke-linecap: round;
  d: path("m21.406 16.343l6.438 3.937");
}

.g0ehyjbch {
  stop-color: var(--svg-color--a03434, #A03434);
}

.gg6kii_po {
  stop-color: var(--svg-color--ffd992, #FFD992);
  stop-opacity: 0;
}

.gy-ksq4cn {
  stop-color: var(--svg-color--bb5124, #BB5124);
}

.h4b13sm5j {
  stop-color: var(--svg-color--ffaa6f, #FFAA6F);
  stop-opacity: 0;
}

.h91gk7bys {
  stop-color: var(--svg-color--f7b678, #F7B678);
}

.haau0jr6r {
  stop-color: var(--svg-color--b54322, #B54322);
}

.hni2rhbgu {
  width: 14px;
  height: 6px;
  x: 19.087px;
  y: 12.797px;
  fill: var(--svg-color--de773d, #DE773D);
  rx: 3px;
}

.htt0p9b1b {
  stop-color: var(--svg-color--d77c46, #D77C46);
  stop-opacity: 0;
}

.hxas9wbft {
  stop-color: var(--svg-color--ffdda2, #FFDDA2);
}

.i9xl7o8ji {
  stop-color: var(--svg-color--f4a161, #F4A161);
  stop-opacity: 0;
}

.ic2uv7oif {
  stop-color: var(--svg-color--ac4f52, #AC4F52);
}

.ivctto4sj {
  cx: 20.712px;
  cy: 4.57px;
  r: 1.618px;
  fill: var(--svg-color--f9bf76, #F9BF76);
}

.ja25vxt3s {
  fill: var(--svg-color--d18a74, #D18A74);
  d: path("M14.836 10.124c-.293 0-.498.273-.346.524c.17.281.442.598.847.826a.38.38 0 0 0 .369 0c.404-.228.675-.545.846-.826c.152-.251-.053-.524-.346-.524z");
}

.jmoupfbeb {
  stop-color: var(--svg-color--ba5137, #BA5137);
  stop-opacity: 0;
}

.jwvoze28a {
  stop-color: var(--svg-color--ce7032, #CE7032);
}

.jyc5o24ck {
  width: 7px;
  height: 8.5px;
  rx: 3.5px;
}

.k29ixq3pv {
  cx: 20.712px;
  cy: 4.5px;
  r: 2.5px;
  fill: var(--svg-color--d68640, #D68640);
}

.kdhb8bdkj {
  stop-color: var(--svg-color--e38b4d, #E38B4D);
}

.kgx9ntbgv {
  stop-color: var(--svg-color--c17b3b, #C17B3B);
}

.kkbtj5bsq {
  stop-color: var(--svg-color--ffb075, #FFB075);
  stop-opacity: 0;
}

.kknzjndoj {
  stop-color: var(--svg-color--e17341, #E17341);
}

.kn1wetb0m {
  stop-color: var(--svg-color--a14750, #A14750);
  stop-opacity: 0;
}

.kzaimjh1a {
  stop-color: var(--svg-color--e68f58, #E68F58);
}

.l2u_o5cvk {
  stop-color: var(--svg-color--ffbe7b, #FFBE7B);
}

.ldmki_brr {
  stop-color: var(--svg-color--fd9c79, #FD9C79);
}

.mc7qfdqjn {
  stop-color: var(--svg-color--ffb075, #FFB075);
}

.mmeo32bod {
  stop-color: var(--svg-color--b56e32, #B56E32);
}

.mxmklzbyg {
  stop-color: var(--svg-color--452b30, #452B30);
}

.mzpme7d0f {
  cx: 11.306px;
  cy: 4.5px;
  r: 2.5px;
}

.n-k-vsbzr {
  stop-color: var(--svg-color--bc8a66, #BC8A66);
  stop-opacity: 0;
}

.n1sa_4xqn {
  stop-color: var(--svg-color--ac4f52, #AC4F52);
  stop-opacity: 0;
}

.n8bfwdbok {
  stop-color: var(--svg-color--ffc286, #FFC286);
}

.nrljhk8yv {
  stop-color: var(--svg-color--a03434, #A03434);
  stop-opacity: 0;
}

.nvxwnz1ab {
  d: path("M15.213 9.82c-.32 0-.545.298-.378.572c.186.308.483.654.925.903a.41.41 0 0 0 .404 0c.441-.25.738-.595.925-.903c.166-.274-.058-.573-.378-.573z");
}

.nx5zx9b4w {
  width: 4px;
  height: 5.5px;
  rx: 2px;
}

.ohb6jub4j {
  cx: 13.462px;
  cy: 8.422px;
  r: 0.5px;
}

.oi3_akjkh {
  stop-color: var(--svg-color--ffbe88, #FFBE88);
}

.om3wyl1ts {
  stop-color: var(--svg-color--ffa66f, #FFA66F);
}

.p6a90ny3i {
  width: 14px;
  height: 6px;
  x: 19.087px;
  y: 12.797px;
  rx: 3px;
}

.pcc287nkr {
  stop-color: var(--svg-color--49393f, #49393F);
}

.pdqvp8k_m {
  stop-color: var(--svg-color--e2a48d, #E2A48D);
}

.peqo57r7q {
  stop-color: var(--svg-color--b56e32, #B56E32);
  stop-opacity: 0;
}

.psuz65f3v {
  stop-color: var(--svg-color--635759, #635759);
}

.ptsffybue {
  stop-color: var(--svg-color--ce6d54, #CE6D54);
  stop-opacity: 0;
}

.q2xrko7st {
  stop-color: var(--svg-color--635556, #635556);
}

.q40s_bbco {
  width: 7px;
  height: 8.5px;
  x: 22.032px;
  y: 20.308px;
  rx: 3.5px;
}

.q9z2wrb4q {
  stop-color: var(--svg-color--bc8a66, #BC8A66);
}

.qgk8-ccrp {
  stop-color: var(--svg-color--ffbd96, #FFBD96);
}

.qtnth0b-s {
  stop-color: var(--svg-color--dc6a27, #DC6A27);
}

.qumexibjl {
  stop-color: var(--svg-color--a3633d, #A3633D);
  stop-opacity: 0;
}

.quud0g0ia {
  cx: 20.767px;
  cy: 4.5px;
  r: 2.126px;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
}

.r23to2bbq {
  stop-color: var(--svg-color--e8a869, #E8A869);
  stop-opacity: 0;
}

.r2vbmqpmh {
  stop-color: var(--svg-color--ffd992, #FFD992);
}

.rb2t10bdg {
  cx: 11.306px;
  cy: 4.57px;
  r: 1.618px;
}

.rpnx7_brv {
  stop-color: var(--svg-color--de7944, #DE7944);
}

.rxo9rqvlj {
  width: 14px;
  height: 6px;
  x: 0.962px;
  y: 19.906px;
  fill: var(--svg-color--d77940, #D77940);
  rx: 3px;
}

.sgyng1bws {
  stop-color: var(--svg-color--e27749, #E27749);
}

.sqa7i0bti {
  stop-color: var(--svg-color--ffaf7e, #FFAF7E);
  stop-opacity: 0;
}

.suy9nen1j {
  stop-color: var(--svg-color--983c50, #983C50);
}

.t03wtbxnc {
  stop-color: var(--svg-color--fd9c79, #FD9C79);
  stop-opacity: 0;
}

.t8nww8bzw {
  stop-color: var(--svg-color--d57e40, #D57E40);
}

.tq5ncrblq {
  stroke: var(--svg-color--fa9e75, #FA9E75);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.608 22.557c.184.084.643.363 1.01.804c.368.44.98 1.53 1.24 2.02");
}

.tzkcnpb3n {
  stop-color: var(--svg-color--ca6645, #CA6645);
}

.uae15mswe {
  stop-color: var(--svg-color--ffdfaf, #FFDFAF);
  stop-opacity: 0;
}

.uc1--qr0f {
  stop-color: var(--svg-color--e38b4d, #E38B4D);
  stop-opacity: 0;
}

.ufehicc4u {
  stop-color: var(--svg-color--ffaf7e, #FFAF7E);
}

.uilz30bbs {
  stop-color: var(--svg-color--ffdfaf, #FFDFAF);
}

.uqxq11_cf {
  stop-color: var(--svg-color--a2643b, #A2643B);
  stop-opacity: 0;
}

.uw6xk5b0c {
  stop-color: var(--svg-color--c17b3b, #C17B3B);
  stop-opacity: 0;
}

.v0lm_7v2w {
  stop-color: var(--svg-color--d27067, #D27067);
}

.v9fj7ubjn {
  cx: 11.306px;
  cy: 4.5px;
  r: 2.5px;
  fill: var(--svg-color--de904c, #DE904C);
}

.vdf-bkbgo {
  stop-color: var(--svg-color--e2a48d, #E2A48D);
  stop-opacity: 0;
}

.vdtorojdb {
  d: path("M23.851 10.166c0 4.468-3.532 5.985-7.89 5.985c-4.356 0-7.888-1.517-7.888-5.985c0-4.467 4.022-7.666 7.889-7.666c3.986 0 7.89 3.199 7.89 7.666");
}

.vgldytb3a {
  stop-color: var(--svg-color--f4a161, #F4A161);
}

.vhqsctbie {
  stop-color: var(--svg-color--dc692a, #DC692A);
}

.vm_sz40cl {
  stop-color: var(--svg-color--ffbe88, #FFBE88);
  stop-opacity: 0;
}

.vngvobbex {
  stop-color: var(--svg-color--ce6d54, #CE6D54);
}

.w1w__9bek {
  cx: 15.962px;
  cy: 20.797px;
  r: 8px;
}

.weff0cjzz {
  stop-color: var(--svg-color--635759, #635759);
  stop-opacity: 0;
}

.wlf82t9rv {
  stop-color: var(--svg-color--ba5137, #BA5137);
}

.wsqdq9etk {
  width: 4px;
  height: 5.5px;
  x: 22.581px;
  y: 22.371px;
  rx: 2px;
}

.wwszs9luy {
  stop-color: var(--svg-color--ce7032, #CE7032);
  stop-opacity: 0;
}

.wyyqnsb3g {
  stop-color: var(--svg-color--eb9251, #EB9251);
}

.wzyd3t66m {
  stop-color: var(--svg-color--a2643b, #A2643B);
}

.x65rjkb3j {
  stop-color: var(--svg-color--a14750, #A14750);
}

.xao-tjnxb {
  stop-color: var(--svg-color--eb9251, #EB9251);
  stop-opacity: 0;
}

.xlxqo898i {
  stop-color: var(--svg-color--dc6a27, #DC6A27);
  stop-opacity: 0;
}

.xsl-l-ydr {
  stop-color: var(--svg-color--dca86a, #DCA86A);
}

.xsxthqbxm {
  stop-color: var(--svg-color--c7733e, #C7733E);
  stop-opacity: 0;
}

.y2qx6zbae {
  stop-color: var(--svg-color--e8a869, #E8A869);
}

.y7bs_obzr {
  cx: 18.462px;
  cy: 8.422px;
  r: 0.5px;
}

.yj3cfwb4c {
  stop-color: var(--svg-color--ffaa6f, #FFAA6F);
}

.yq4d8r-9h {
  stop-color: var(--svg-color--ffa66f, #FFA66F);
  stop-opacity: 0;
}

.yvh0_2bxk {
  stop-color: var(--svg-color--b54322, #B54322);
  stop-opacity: 0;
}

.zk-zpiszh {
  stop-color: var(--svg-color--a3633d, #A3633D);
}

</style>
