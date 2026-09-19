<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iyHrKVd)" class="wazmnkp7g"/><path fill="url(#iM0mjJb)" class="wazmnkp7g"/><path fill="url(#izs5vhb)" class="wazmnkp7g"/><path fill="url(#iaGZsYz)" class="wazmnkp7g"/><path fill="url(#i4yBY2b)" class="wazmnkp7g"/><rect fill="url(#i7EPzNb)" class="qm8bcbjeu"/><g filter="url(#ioRCAud)"><circle fill="url(#iLgeBeb)" class="zwcxt1kkr"/></g><g filter="url(#iqVzaqd)"><circle fill="url(#ilJ5rHb)" class="j57p6wb3r"/></g><g filter="url(#iky3TWc)"><circle fill="url(#ioddtvd)" class="zormo03zk"/><circle fill="url(#i969cze)" class="zormo03zk"/></g><g filter="url(#imtCXyh)"><circle class="p46uncbbr"/><circle fill="url(#iLjEJue)" class="j7ljmrt8g"/><circle fill="url(#ij0MBTb)" class="j7ljmrt8g"/></g><g filter="url(#iRG8ihc)"><path fill="url(#i7t6ycd)" class="w2jejf1db"/><path fill="url(#iAsbB6d)" class="w2jejf1db"/><path fill="url(#iIQ7Jsb)" class="w2jejf1db"/></g><path fill="url(#isQeQde)" class="d-160sbmp"/><path fill="url(#iLT7sTG)" class="d-160sbmp"/><path fill="url(#it8hApe)" class="d-160sbmp"/><path fill="url(#iOh2jtQ)" class="d-160sbmp"/><g filter="url(#ipbJlDj)"><path fill="url(#iB44DVb)" class="pun2iva9e"/></g><g filter="url(#iDQSCdB)"><path class="l08ia0bpv"/><path fill="url(#iGP84rd)" class="zah0vsbek"/><path fill="url(#iebNLHb)" class="zah0vsbek"/><path fill="url(#if55Q0b)" class="zah0vsbek"/><path fill="url(#i9ZDWge)" class="zah0vsbek"/></g><g filter="url(#iWQvqbc)"><path class="l44lotb-q"/></g><g filter="url(#ivbR3rU)"><path class="h_i2o6ial"/><path fill="url(#i9KIl6b)" class="gtibzib9q"/><path fill="url(#ip9WBJG)" class="gtibzib9q"/><path fill="url(#iJiXMwj)" class="gtibzib9q"/><path fill="url(#iWPbkee)" class="gtibzib9q"/></g><path fill="url(#is4z64b)" class="gtibzib9q"/><path class="gqk74qb3p"/><path fill="url(#iFpDzyb)" class="rbyge-7nb"/><path class="sl8o9bcct"/><g filter="url(#iDZhaCb)"><path class="f0-n0abyh"/><path fill="url(#iRdfUFe)" class="ag53t8bfc"/></g><g filter="url(#iT5LyOb)"><path fill="url(#izlRFCb)" class="i2x_pr8xq"/></g><path class="m4xo_8ahv"/><path fill="url(#itMbFfe)" class="ljjlcab3m"/><path class="te2649brs"/><g filter="url(#i2Vnr8b)"><path fill="url(#ibHHm2U)" class="t0xb6jbhd"/></g><g filter="url(#iXI85yb)"><ellipse transform="rotate(-27.914 12.818 12.299)" class="gzy0dgimh"/><ellipse fill="url(#iI87IEe)" transform="rotate(-27.914 12.818 12.299)" class="npi58w5py"/></g><g filter="url(#iIIPP6d)"><path stroke="url(#iIMwCtc)" class="ic7h8io-u"/></g><g filter="url(#i8HXESc)"><path clip-rule="evenodd" class="gbkx3hlzk"/></g><g filter="url(#iFuoMTb)"><path clip-rule="evenodd" class="cnh344vmv"/></g><g filter="url(#idp5Lzb)"><path class="sei8yqbib"/></g><g filter="url(#iDTsdZc)"><path class="rlonanb3x"/></g><g filter="url(#i9Ltcic)"><path stroke="url(#iPlRsab)" clip-rule="evenodd" class="b4v223b4i"/><path stroke="url(#iK10u2d)" clip-rule="evenodd" class="b4v223b4i"/></g><path clip-rule="evenodd" class="sb18a8bxa"/><defs><radialGradient id="iyHrKVd" cx="0" cy="0" r="1" gradientTransform="rotate(160.481 9.331 14.06)scale(12.5328 12.8728)" gradientUnits="userSpaceOnUse"><stop class="ly599bb8t"/><stop offset=".578" class="sj3b9accl"/></radialGradient><radialGradient id="iM0mjJb" cx="0" cy="0" r="1" gradientTransform="matrix(-20.8125 0 0 -13.0625 25.199 29.069)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="j7m096d8q"/><stop offset="1" class="t2in4vbqy"/></radialGradient><radialGradient id="izs5vhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.43107 5.625 0 10.836 30.148)" gradientUnits="userSpaceOnUse"><stop class="qew-7dtdq"/><stop offset="1" class="l3o3sjq6c"/></radialGradient><radialGradient id="i4yBY2b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.61736 0 0 -2.43441 15.703 21.083)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="m97vr3bka"/><stop offset="1" class="mn2ubysev"/></radialGradient><radialGradient id="i7EPzNb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 2.96875 -4.68169 4.04104 15.25 20.758)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="v8t4bs_gr"/><stop offset=".963" class="e45ljsbts"/></radialGradient><radialGradient id="iLgeBeb" cx="0" cy="0" r="1" gradientTransform="matrix(2.26599 0 0 3.9655 7.702 13.303)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="i969cze" cx="0" cy="0" r="1" gradientTransform="matrix(1.0675 -.77729 .88717 1.2184 22.622 12.96)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iLjEJue" cx="0" cy="0" r="1" gradientTransform="matrix(1.06046 -1.95049 1.14163 .6207 22.089 14.364)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="ij0MBTb" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -5.104 33.573)scale(.47109 .60731)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iAsbB6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.68778 2.07727 0 19.018 11.661)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iIQ7Jsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.77433 2.20654 0 13.133 11.835)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="it8hApe" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.5595 -14.3339 0 15.6 11.012)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="expufxtqh"/><stop offset="1" class="cpvcnac5k"/></radialGradient><radialGradient id="iGP84rd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0302 -3.81777 1.41575 .38203 21.6 8)" gradientUnits="userSpaceOnUse"><stop class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iebNLHb" cx="0" cy="0" r="1" gradientTransform="matrix(4.93886 .4545 -.24438 2.65559 19.479 5.728)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="if55Q0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.16825 -3.35801 0 15.989 2.197)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="i9ZDWge" cx="0" cy="0" r="1" gradientTransform="matrix(3.96926 -2.90878 4.5571 6.21854 7.662 11)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iWPbkee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25425 -.81684 0 16.411 15.378)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iFpDzyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04738 -1.66598 0 18.802 12.423)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRdfUFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.2994 -.38581 .53117 -.4122 18.508 12.531)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="itMbFfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04744 -1.66606 0 13.168 12.422)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iI87IEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00999 -.63784 .76671 -.012 12.799 12.706)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPlRsab" cx="0" cy="0" r="1" gradientTransform="matrix(-.08594 .28125 -1.54727 -.47278 16.265 17.371)" gradientUnits="userSpaceOnUse"><stop class="hwrv3873j"/><stop offset="1" class="rqtpvy9py"/></radialGradient><radialGradient id="iK10u2d" cx="0" cy="0" r="1" gradientTransform="matrix(.191 -.14453 .57285 .75707 14.332 17.688)" gradientUnits="userSpaceOnUse"><stop class="hwrv3873j"/><stop offset="1" class="rqtpvy9py"/></radialGradient><filter id="ioRCAud" width="4.511" height="4.311" x="7.702" y="11.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21941"/></filter><filter id="iqVzaqd" width="3.57" height="3.57" x="8.073" y="11.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".25"/></filter><filter id="iky3TWc" width="4.561" height="4.561" x="19.986" y="10.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21941"/></filter><filter id="imtCXyh" width="3.57" height="3.57" x="20.357" y="11.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".25"/></filter><filter id="iRG8ihc" width="13.395" height="15.781" x="9.328" y="6.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21941"/></filter><filter id="ipbJlDj" width="9.483" height="7.96" x="14.208" y="4.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation="1"/></filter><filter id="iDQSCdB" width="16.272" height="10.886" x="7.853" y="1.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21941"/></filter><filter id="iWQvqbc" width="3.773" height="4.962" x="13.794" y="12.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".375"/></filter><filter id="ivbR3rU" width="2.923" height="3.962" x="14.527" y="12.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".125"/></filter><filter id="iDZhaCb" width=".958" height=".841" x="17.884" y="11.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".05"/></filter><filter id="iT5LyOb" width="1.034" height="1.063" x="18.997" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".1"/></filter><filter id="i2Vnr8b" width="1.157" height="1.226" x="13.261" y="11.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".1"/></filter><filter id="iXI85yb" width="1.121" height=".851" x="12.258" y="11.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".05"/></filter><filter id="iIIPP6d" width="1.083" height="2.712" x="9.427" y="6.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".125"/></filter><filter id="i8HXESc" width="3.582" height="2.502" x="10.928" y="8.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0980392 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21941"/></filter><filter id="iFuoMTb" width="3.582" height="2.502" x="17.717" y="8.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0980392 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21941"/></filter><filter id="idp5Lzb" width="3.282" height="2.052" x="10.953" y="9.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".2"/></filter><filter id="iDTsdZc" width="3.282" height="2.052" x="17.824" y="8.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".2"/></filter><filter id="i9Ltcic" width="3.695" height="1.445" x="14.082" y="16.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21941" stdDeviation=".05"/></filter><linearGradient id="iaGZsYz" x1="16" x2="16" y1="29.889" y2="29.303" gradientUnits="userSpaceOnUse"><stop class="ld3t7r4-o"/><stop offset="1" class="e_8zkvbjm"/></linearGradient><linearGradient id="ilJ5rHb" x1="9.858" x2="9.031" y1="13.663" y2="13.663" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="ioddtvd" x1="23.545" x2="22.488" y1="11.894" y2="15.169" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="i7t6ycd" x1="21.2" x2="11.339" y1="13.806" y2="15.276" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="isQeQde" x1="9.021" x2="11.451" y1="17.287" y2="17.201" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iLT7sTG" x1="22.27" x2="20.907" y1="16.205" y2="16.076" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iOh2jtQ" x1="16.026" x2="16.026" y1="20.383" y2="21.738" gradientUnits="userSpaceOnUse"><stop offset=".533" class="m8c2yi15h"/><stop offset="1" class="vbfhreb6b"/></linearGradient><linearGradient id="iB44DVb" x1="15.302" x2="25.819" y1="9.952" y2="6.187" gradientUnits="userSpaceOnUse"><stop class="y3qu8-b1b"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="i9KIl6b" x1="14.873" x2="16.084" y1="14.657" y2="14.657" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="ip9WBJG" x1="17.201" x2="15.876" y1="15.074" y2="15.055" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iJiXMwj" x1="16.24" x2="16.24" y1="16.032" y2="15.292" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="is4z64b" x1="16.151" x2="16.151" y1="16.086" y2="15.87" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="izlRFCb" x1="19.806" x2="19.401" y1="12.492" y2="12.742" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibHHm2U" x1="14.129" x2="13.724" y1="12.492" y2="12.742" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIMwCtc" x1="9.969" x2="9.969" y1="6.963" y2="9.748" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-frowning-medium-dark" /></template>
<style>
.ag53t8bfc {
  d: path("M18.72 12.05c.082.11-.09.244-.284.39c-.196.146-.34.248-.422.138s.01-.317.204-.462c.195-.146.42-.176.502-.066");
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.b4v223b4i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M17.097 17.67c-.919-.627-1.93-.26-2.34.005a.275.275 0 0 1-.298-.462c.495-.319 1.765-.806 2.948.004a.275.275 0 1 1-.31.454Z");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnh344vmv {
  fill: var(--svg-color--3e3231, #3E3231);
  fill-rule: evenodd;
  d: path("M17.89 9.371a.625.625 0 0 0 .02.884a3.66 3.66 0 0 0 2.514 1.025a.625.625 0 1 0 0-1.25a2.4 2.4 0 0 1-1.65-.678a.625.625 0 0 0-.883.02");
}

.cpvcnac5k {
  stop-color: var(--svg-color--7d4371, #7D4371);
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d-160sbmp {
  d: path("M9.328 10.655c0-.345.139-.758.416-.964l.208-.207c.346-.276.485-.689.485-1.102V7.28c0-.344.207-.62.554-.689c.83-.206 2.562-.55 5.056-.55c2.493 0 4.225.344 5.056.55c.277.07.554.345.554.69v1.101c0 .413.208.826.485 1.102c.648.454.608.704.554 1.24c-.07.688-.139 1.859-.139 1.859h.024l-.343 5.111c-.208 2.285-2.004 3.878-4.146 3.878h-4.145c-2.211 0-3.938-1.593-4.146-3.878c-.18-2.345-.259-4.698-.473-7.04");
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.e_8zkvbjm {
  stop-color: var(--svg-color--1b70c9, #1B70C9);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e45ljsbts {
  stop-color: var(--svg-color--8c6560, #8C6560);
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.expufxtqh {
  stop-color: var(--svg-color--7d4371, #7D4371);
  stop-opacity: 0;
}

.f0-n0abyh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.72 12.05c.082.11-.09.244-.284.39c-.196.146-.34.248-.422.138s.01-.317.204-.462c.195-.146.42-.176.502-.066");
}

.ft5dv1b6b {
  fill: none;
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gbkx3hlzk {
  fill: var(--svg-color--121212, #121212);
  fill-rule: evenodd;
  d: path("M14.087 9.371c.238.25.23.645-.02.884a3.66 3.66 0 0 1-2.514 1.025a.625.625 0 1 1 0-1.25a2.4 2.4 0 0 0 1.65-.678a.625.625 0 0 1 .884.02");
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gqk74qb3p {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.072 11.456c.843 0 1.555.581 1.75 1.367a.354.354 0 0 1-.346.44h-2.88a.297.297 0 0 1-.294-.351a1.805 1.805 0 0 1 1.77-1.456");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gtibzib9q {
  d: path("m15.495 12.935l-.686 2.194a.696.696 0 0 0 .672.903h1.015a.698.698 0 0 0 .672-.903l-.686-2.194c-.147-.486-.833-.486-.987 0");
}

.gzy0dgimh {
  cx: 12.818px;
  cy: 12.299px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.503px;
  ry: 0.255px;
}

.h_i2o6ial {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.495 12.935l-.686 2.194a.696.696 0 0 0 .672.903h1.015a.698.698 0 0 0 .672-.903l-.686-2.194c-.147-.486-.833-.486-.987 0");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hwrv3873j {
  stop-color: var(--svg-color--936b67, #936B67);
}

.i2x_pr8xq {
  d: path("M19.831 12.807a1.1 1.1 0 0 0-.299-.597l-.335.368l.151.295z");
}

.ic7h8io-u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.136 7.09v1.16c-.01.191-.091.62-.334.802");
}

.j57p6wb3r {
  cx: 9.858px;
  cy: 13.303px;
  r: 1.285px;
}

.j7ljmrt8g {
  cx: 22.142px;
  cy: 13.303px;
  r: 1.285px;
}

.j7m096d8q {
  stop-color: var(--svg-color--3891c9, #3891C9);
  stop-opacity: 0;
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l08ia0bpv {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m22.211 4.939l.554.275c.97.482 1.524 1.584 1.316 2.755l-.762 3.925c-.067.406-.335.679-.738.689h-.023s.069-1.17.138-1.86c.056-.559-.041-.73-.554-1.24c-.277-.275-.485-.688-.485-1.101V7.28c0-.344-.277-.62-.554-.689c-.831-.206-2.563-.55-5.056-.55c-2.494 0-4.225.344-5.056.55c-.347.07-.554.345-.554.69v1.101c0 .413-.139.826-.485 1.102l-.208.207c-.277.206-.416.62-.416.964c.07.757.139 1.86.139 1.86l-.063-.003a.82.82 0 0 1-.768-.687L7.874 7.9c-.139-1.102.415-2.204 1.385-2.686l.554-.275c.346-.207.693-.482 1.04-.758l1.246-1.308c.762-.69 1.87-.896 2.84-.414a3.8 3.8 0 0 0 2.147 0c1.039-.344 2.216-.068 3.047.69l1.04 1.032c.276.344.623.551 1.038.758");
}

.l3o3sjq6c {
  stop-color: var(--svg-color--2683d3, #2683D3);
  stop-opacity: 0;
}

.l44lotb-q {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.633 13.145l-1.06 2.195c-.13.451.185.903.631.903h.952c.447 0 .762-.458.63-.903l-.643-2.195c-.138-.486-.365-.486-.51 0");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ld3t7r4-o {
  stop-color: var(--svg-color--1b70c9, #1B70C9);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljjlcab3m {
  d: path("M13.166 11.807a1.152 1.152 0 0 0-1.11 1.456h2.225q.041-.149.042-.304a1.16 1.16 0 0 0-1.157-1.152");
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.ly599bb8t {
  stop-color: var(--svg-color--47b4ff, #47B4FF);
}

.m4xo_8ahv {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.899 11.456c-.843 0-1.556.581-1.75 1.367a.354.354 0 0 0 .346.44h2.88c.184 0 .33-.168.294-.351a1.81 1.81 0 0 0-1.77-1.456");
}

.m8c2yi15h {
  stop-color: var(--svg-color--8e5b8e, #8E5B8E);
  stop-opacity: 0;
}

.m97vr3bka {
  stop-color: var(--svg-color--045d9a, #045D9A);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mn2ubysev {
  stop-color: var(--svg-color--045d9a, #045D9A);
  stop-opacity: 0;
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.npi58w5py {
  cx: 12.818px;
  cy: 12.299px;
  rx: 0.503px;
  ry: 0.255px;
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

.p46uncbbr {
  cx: 22.142px;
  cy: 13.303px;
  r: 1.285px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pun2iva9e {
  d: path("m21.107 6.04l-3.974 1.325a1.352 1.352 0 0 0 .607 2.623l3.951-.529z");
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.qew-7dtdq {
  stop-color: var(--svg-color--2683d3, #2683D3);
}

.qm8bcbjeu {
  width: 5.188px;
  height: 6.789px;
  x: 13.451px;
  y: 17.141px;
  rx: 2.594px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rbyge-7nb {
  d: path("M18.805 11.807a1.152 1.152 0 0 1 1.11 1.456h-2.226a1.157 1.157 0 0 1 1.115-1.456");
}

.rlonanb3x {
  stroke: var(--svg-color--453a3b, #453A3B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M20.506 10.413a3.03 3.03 0 0 1-2.082-.852");
}

.rqtpvy9py {
  stop-color: var(--svg-color--936b67, #936B67);
  stop-opacity: 0;
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sb18a8bxa {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M17.097 17.67c-.919-.627-1.93-.26-2.34.005a.275.275 0 0 1-.298-.462c.495-.319 1.765-.806 2.948.004a.275.275 0 1 1-.31.454");
}

.sei8yqbib {
  stroke: var(--svg-color--453a3b, #453A3B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.553 10.499c.656 0 1.442-.239 2.082-.852");
}

.sj3b9accl {
  stop-color: var(--svg-color--2e8bd7, #2E8BD7);
}

.sl8o9bcct {
  fill: var(--svg-color--000, #000);
  d: path("M18.145 12.959c0-.367.293-.66.66-.66a.657.657 0 0 1 .586.963h-1.167a.6.6 0 0 1-.079-.303");
}

.t0xb6jbhd {
  d: path("M14.219 12.824c0-.373-.303-.621-.385-.696l-.373.36l.23.466z");
}

.t2in4vbqy {
  stop-color: var(--svg-color--3891c9, #3891C9);
}

.te2649brs {
  fill: var(--svg-color--000, #000);
  d: path("M13.826 12.959a.657.657 0 0 0-.66-.66a.657.657 0 0 0-.587.964h1.168a.66.66 0 0 0 .079-.304");
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

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v8t4bs_gr {
  stop-color: var(--svg-color--5e353e, #5E353E);
}

.vbfhreb6b {
  stop-color: var(--svg-color--8e5b8e, #8E5B8E);
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w2jejf1db {
  d: path("m9.404 12.512l.063.002s-.07-1.102-.139-1.86c0-.344.139-.757.416-.963l.208-.207c.346-.276.485-.689.485-1.102V7.28c0-.344.207-.62.554-.689c.83-.206 2.562-.55 5.056-.55c2.493 0 4.225.344 5.056.55c.277.07.554.345.554.69v1.101c0 .413.208.826.485 1.102c.648.454.608.704.554 1.24c-.07.688-.139 1.859-.139 1.859h.024l-.343 5.111c-.208 2.285-2.004 3.878-4.146 3.878h-4.145c-2.211 0-3.938-1.593-4.146-3.878z");
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wazmnkp7g {
  d: path("M16 19.632c-5.502 0-9.963 4.46-9.963 9.962v.21h19.926v-.21c0-5.502-4.46-9.963-9.963-9.963");
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y3qu8-b1b {
  stop-color: var(--svg-color--a27b71, #A27B71);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
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

.zah0vsbek {
  d: path("m22.211 4.939l.554.275c.97.482 1.524 1.584 1.316 2.755l-.762 3.925c-.067.406-.335.679-.738.689h-.023s.069-1.17.138-1.86c.056-.559-.041-.73-.554-1.24c-.277-.275-.485-.688-.485-1.101V7.28c0-.344-.277-.62-.554-.689c-.831-.206-2.563-.55-5.056-.55c-2.494 0-4.225.344-5.056.55c-.347.07-.554.345-.554.69v1.101c0 .413-.139.826-.485 1.102l-.208.207c-.277.206-.416.62-.416.964c.07.757.139 1.86.139 1.86l-.063-.003a.82.82 0 0 1-.768-.687L7.874 7.9c-.139-1.102.415-2.204 1.385-2.686l.554-.275c.346-.207.693-.482 1.04-.758l1.246-1.308c.762-.69 1.87-.896 2.84-.414a3.8 3.8 0 0 0 2.147 0c1.039-.344 2.216-.068 3.047.69l1.04 1.032c.276.344.623.551 1.038.758");
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zormo03zk {
  cx: 22.142px;
  cy: 13.303px;
  r: 2.156px;
}

.zwcxt1kkr {
  cx: 9.858px;
  cy: 13.303px;
  r: 2.156px;
}

</style>
