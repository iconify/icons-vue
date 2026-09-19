<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8In7qd)"><path fill="url(#i2A1b1b)" class="cd_p-9blu"/></g><g filter="url(#iT3JMJj)"><path fill="url(#ig43Egd)" class="rj64x8b-f"/></g><g filter="url(#io7Hajb)"><path fill="url(#i8kSQTb)" class="bj7q6ebjw"/></g><g filter="url(#istRHYb)"><path fill="url(#ix87b0b)" class="rn-__nk_y"/></g><g filter="url(#iFWWQ5d)"><path fill="url(#iTbluWb)" class="vgc652-ck"/></g><g filter="url(#iVpYipc)"><path fill="url(#iFhS6vb)" class="dfq2-66to"/></g><g filter="url(#ih46jqc)"><path fill="url(#i4KCOQd)" class="hw0karqid"/></g><g filter="url(#if1GIKe)"><path fill="url(#iXJYRGc)" class="xl4jfwb2p"/></g><g filter="url(#imONc0x)"><path fill="url(#ib5dEZE)" class="n8sww8ycp"/></g><g filter="url(#i2uUfEb)"><path fill="url(#iydPJid)" class="qv9jfabme"/></g><g filter="url(#imIp1Sd)"><path fill="url(#iSp9lje)" class="u5l-jmbtq"/></g><path fill="url(#ihmDWPb)" class="nnbpx21zd"/><path class="v0vxky7tf"/><path class="plza5ccxz"/><path class="sthm4ntwl"/><path class="lp057bbcg"/><path class="pwj64qgdq"/><path class="cmkekgetr"/><path class="dwucvrkbl"/><path class="v13kbsb4e"/><path class="wgpa89bxq"/><path class="btpi9qb0m"/><path class="c8o1x9jtg"/><path class="ztuy1ib2v"/><path class="affks_buj"/><path class="tfi9e1bkp"/><path class="rzbsyx2ca"/><path class="fvf0w2bpv"/><path class="cyg2-jbrv"/><path class="pevyw7npa"/><path class="ps1vum79n"/><path class="gymy9h2-v"/><path class="ql8z9qeiv"/><path class="f2jjtac9l"/><path fill="url(#icoQUjc)" class="ynzzttbpu"/><path fill="url(#iBbTlVc)" class="afby5ze3i"/><path fill="url(#itx1fib)" class="y2guwm-1z"/><path fill="url(#ieaSZvb)" class="f3muymbql"/><path fill="url(#i03Fn8c)" clip-rule="evenodd" class="ayjz2abhx"/><path fill="url(#iJzvDEc)" class="drpbptstb"/><path fill="url(#iHghHjd)" class="drpbptstb"/><path fill="url(#iLj6lsb)" class="y70mlg5_t"/><path fill="url(#iwyrdKb)" class="y70mlg5_t"/><path fill="url(#ibRFLQd)" class="vpcngmopr"/><path fill="url(#iINci5Q)" class="vpcngmopr"/><path fill="url(#iEOYhKd)" class="ddul8pboi"/><path fill="url(#iZ7VzOd)" class="ddul8pboi"/><path fill="url(#iVRTL2b)" class="lqudwibip"/><path fill="url(#iSvskXd)" class="lqudwibip"/><path fill="url(#iVRTL2b)" class="xk1gd1dbl"/><path fill="url(#iSvskXd)" class="xk1gd1dbl"/><path fill="url(#i9QhvUc)" class="svexzijcj"/><path fill="url(#iPe31pC)" class="yasa7wb3i"/><path class="aihyutb-t"/><path fill="url(#ioql23b)" class="rz-0m0fpi"/><path fill="url(#iB3iaXd)" class="l_334t98h"/><path fill="url(#iG1zLZR)" class="rz-0m0fpi"/><path class="kxrn_8fmd"/><path fill="url(#ioHRP3b)" class="thgftzbvq"/><path fill="url(#iJLVWcb)" class="thgftzbvq"/><path fill="url(#imXsM3c)" class="so88etl_h"/><path fill="url(#i13G0fc)" class="so88etl_h"/><path fill="url(#iJXmajc)" class="so88etl_h"/><path fill="url(#i2z25ae)" class="cmj-yob3m"/><path fill="url(#izusAde)" class="cmj-yob3m"/><path fill="url(#iGFQ6fd)" class="cmj-yob3m"/><path fill="url(#i4XWmad)" class="cmj-yob3m"/><g filter="url(#ih4nuAd)"><path class="s9g5_n5vc"/></g><path fill="url(#iCXYlCd)" class="x8ugri1sy"/><path fill="url(#iEy6v0U)" class="x8ugri1sy"/><path fill="url(#i4p5Sbd)" class="kxfv0d3jx"/><path fill="url(#iSh3Wmb)" class="kxfv0d3jx"/><path fill="url(#iHqvJ0n)" class="kxfv0d3jx"/><g filter="url(#icOjcWb)"><path class="xt6te7bal"/></g><g filter="url(#ieunjir)"><path class="mpox7eh9k"/></g><g filter="url(#i96LIje)"><path fill="url(#iEg0aOe)" class="ukn92sasg"/></g><g filter="url(#iZh73vZ)"><path fill="url(#idA1Y8b)" class="hd8dqccmn"/></g><defs><linearGradient id="icoQUjc" x1="21.245" x2="13.557" y1="14.685" y2="19.435" gradientUnits="userSpaceOnUse"><stop class="y4f0v-bnu"/><stop offset="1" class="r4uvyddzz"/></linearGradient><linearGradient id="iBbTlVc" x1="9.901" x2="14.417" y1="19.997" y2="15.842" gradientUnits="userSpaceOnUse"><stop class="gjsikvb1v"/><stop offset="1" class="rdal98o9d"/></linearGradient><linearGradient id="itx1fib" x1="10.182" x2="12.063" y1="19.498" y2="14.872" gradientUnits="userSpaceOnUse"><stop class="gjsikvb1v"/><stop offset="1" class="rdal98o9d"/></linearGradient><linearGradient id="ieaSZvb" x1="12.198" x2="12.015" y1="20.857" y2="16.617" gradientUnits="userSpaceOnUse"><stop class="gjsikvb1v"/><stop offset="1" class="rdal98o9d"/></linearGradient><linearGradient id="i03Fn8c" x1="11.651" x2="10.995" y1="21.091" y2="18.623" gradientUnits="userSpaceOnUse"><stop class="gjsikvb1v"/><stop offset="1" class="rdal98o9d"/></linearGradient><linearGradient id="iJzvDEc" x1="16.386" x2="16.919" y1="14.154" y2="14.221" gradientUnits="userSpaceOnUse"><stop class="y4agq-04l"/><stop offset="1" class="myjv66buv"/><stop offset="1" class="ds50n1bpc"/></linearGradient><linearGradient id="iHghHjd" x1="15.511" x2="18.165" y1="12.138" y2="12.865" gradientUnits="userSpaceOnUse"><stop class="y4agq-04l"/><stop offset="1" class="myjv66buv"/><stop offset="1" class="ds50n1bpc"/></linearGradient><linearGradient id="iLj6lsb" x1="17.433" x2="17.714" y1="14.794" y2="14.935" gradientUnits="userSpaceOnUse"><stop class="y4agq-04l"/><stop offset="1" class="myjv66buv"/><stop offset="1" class="ds50n1bpc"/></linearGradient><linearGradient id="iwyrdKb" x1="18.104" x2="19.856" y1="11.576" y2="12.354" gradientUnits="userSpaceOnUse"><stop class="y4agq-04l"/><stop offset="1" class="myjv66buv"/><stop offset="1" class="ds50n1bpc"/></linearGradient><linearGradient id="ibRFLQd" x1="17.229" x2="20.141" y1="12.638" y2="15.845" gradientUnits="userSpaceOnUse"><stop class="y4agq-04l"/><stop offset="1" class="myjv66buv"/><stop offset="1" class="ds50n1bpc"/></linearGradient><linearGradient id="iINci5Q" x1="19.714" x2="20.145" y1="13.982" y2="14.557" gradientUnits="userSpaceOnUse"><stop class="y4agq-04l"/><stop offset="1" class="myjv66buv"/><stop offset="1" class="ds50n1bpc"/></linearGradient><linearGradient id="iEOYhKd" x1="18.683" x2="19.009" y1="18.122" y2="16.758" gradientUnits="userSpaceOnUse"><stop class="y4agq-04l"/><stop offset="1" class="myjv66buv"/><stop offset="1" class="ds50n1bpc"/></linearGradient><linearGradient id="iZ7VzOd" x1="20.104" x2="20.203" y1="16.005" y2="16.482" gradientUnits="userSpaceOnUse"><stop class="y4agq-04l"/><stop offset="1" class="ds50n1bpc"/><stop offset="1" class="myjv66buv"/></linearGradient><linearGradient id="iVRTL2b" x1="18.808" x2="19.073" y1="19.201" y2="18.81" gradientUnits="userSpaceOnUse"><stop class="y4agq-04l"/><stop offset="1" class="myjv66buv"/><stop offset="1" class="ds50n1bpc"/></linearGradient><linearGradient id="iSvskXd" x1="19.222" x2="19.159" y1="17.544" y2="17.959" gradientUnits="userSpaceOnUse"><stop class="y4agq-04l"/><stop offset="1" class="ds50n1bpc"/><stop offset="1" class="myjv66buv"/></linearGradient><linearGradient id="i9QhvUc" x1="16.589" x2="15.69" y1="23.779" y2="28.185" gradientUnits="userSpaceOnUse"><stop class="l0na836kg"/><stop offset="1" class="hirmu1bim"/></linearGradient><linearGradient id="iPe31pC" x1="19.589" x2="18.792" y1="23.779" y2="27.998" gradientUnits="userSpaceOnUse"><stop class="l0na836kg"/><stop offset="1" class="d4ehd0uag"/></linearGradient><linearGradient id="ioql23b" x1="15.008" x2="15.008" y1="29.224" y2="28.732" gradientUnits="userSpaceOnUse"><stop class="qeudmbbqr"/><stop offset="1" class="w-qrc6bga"/></linearGradient><linearGradient id="ioHRP3b" x1="18.321" x2="18.321" y1="29.224" y2="28.732" gradientUnits="userSpaceOnUse"><stop class="qeudmbbqr"/><stop offset="1" class="w-qrc6bga"/></linearGradient><linearGradient id="imXsM3c" x1="15.589" x2="16.287" y1="9.685" y2="8.278" gradientUnits="userSpaceOnUse"><stop class="u4phyi77o"/><stop offset="1" class="zx9irmbkz"/></linearGradient><linearGradient id="i2z25ae" x1="15.307" x2="15.307" y1="10.123" y2="24.06" gradientUnits="userSpaceOnUse"><stop class="g-monbn-t"/><stop offset="1" class="vsr2_ob8p"/></linearGradient><linearGradient id="izusAde" x1="17.113" x2="17.113" y1="24.591" y2="22.873" gradientUnits="userSpaceOnUse"><stop class="s5ml4ibxa"/><stop offset="1" class="no-l0kb3e"/></linearGradient><linearGradient id="i4XWmad" x1="12.089" x2="12.917" y1="15.685" y2="15.826" gradientUnits="userSpaceOnUse"><stop class="ska2-uh4o"/><stop offset="1" class="d-3o38bsv"/></linearGradient><linearGradient id="iCXYlCd" x1="11.495" x2="12.464" y1="11.466" y2="9.248" gradientUnits="userSpaceOnUse"><stop class="u4phyi77o"/><stop offset="1" class="zx9irmbkz"/></linearGradient><linearGradient id="iEy6v0U" x1="13.432" x2="12.768" y1="9.138" y2="10.162" gradientUnits="userSpaceOnUse"><stop class="ko2vygbol"/><stop offset="1" class="fpw7gp92a"/></linearGradient><linearGradient id="iHqvJ0n" x1="14.397" x2="14.053" y1="10.183" y2="9.964" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="idA1Y8b" x1="17.375" x2="21.499" y1="19.738" y2="21.194" gradientUnits="userSpaceOnUse"><stop class="dc018zbdm"/><stop offset="1" class="kceo08bfp"/></linearGradient><radialGradient id="i2A1b1b" cx="0" cy="0" r="1" gradientTransform="rotate(11.708 -97.253 34.894)scale(6.95725 9.66585)" gradientUnits="userSpaceOnUse"><stop class="n4n4jhb5e"/><stop offset="1" class="n9uzh9wnc"/></radialGradient><radialGradient id="ig43Egd" cx="0" cy="0" r="1" gradientTransform="matrix(6.375 1.3125 -.7246 3.51954 4.183 16.498)" gradientUnits="userSpaceOnUse"><stop class="b9sb2trlq"/><stop offset="1" class="sj9ng07_p"/></radialGradient><radialGradient id="i8kSQTb" cx="0" cy="0" r="1" gradientTransform="matrix(4.8125 4 -2.61084 3.14116 5.995 10.81)" gradientUnits="userSpaceOnUse"><stop class="k83948b6w"/><stop offset="1" class="vei161n9z"/></radialGradient><radialGradient id="ix87b0b" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 7.125 -21.9236 10.38487 8.557 6.998)" gradientUnits="userSpaceOnUse"><stop class="jfg2seb_f"/><stop offset="1" class="iolbbgdbc"/></radialGradient><radialGradient id="iTbluWb" cx="0" cy="0" r="1" gradientTransform="matrix(.52362 11.49999 -24.40851 1.11137 12.596 4.623)" gradientUnits="userSpaceOnUse"><stop class="zon8518hh"/><stop offset=".958" class="aintevxed"/></radialGradient><radialGradient id="iFhS6vb" cx="0" cy="0" r="1" gradientTransform="rotate(103.457 7.129 9.146)scale(7.22975 10.6305)" gradientUnits="userSpaceOnUse"><stop class="au7epcb_l"/><stop offset="1" class="wsbjij2jl"/></radialGradient><radialGradient id="i4KCOQd" cx="0" cy="0" r="1" gradientTransform="rotate(114.727 8.908 10.374)scale(5.2295 10.3665)" gradientUnits="userSpaceOnUse"><stop class="o7b85ac2m"/><stop offset="1" class="gf4_w-bwq"/><stop offset="1" class="tb-2tw0to"/></radialGradient><radialGradient id="iXJYRGc" cx="0" cy="0" r="1" gradientTransform="rotate(136.223 11.07 9.554)scale(6.07559 14.3727)" gradientUnits="userSpaceOnUse"><stop class="nm-07mb5n"/><stop offset="1" class="gf4_w-bwq"/></radialGradient><radialGradient id="ib5dEZE" cx="0" cy="0" r="1" gradientTransform="rotate(155.862 12.742 8.867)scale(7.25976 13.6966)" gradientUnits="userSpaceOnUse"><stop class="nm-07mb5n"/><stop offset="1" class="gf4_w-bwq"/></radialGradient><radialGradient id="iydPJid" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 0 0 -7.78953 28.87 17.065)" gradientUnits="userSpaceOnUse"><stop class="nfovzcb5l"/><stop offset="1" class="u_c-lyb9q"/></radialGradient><radialGradient id="iSp9lje" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 -1.6747 3.22575 -9.39008 28.183 22.123)" gradientUnits="userSpaceOnUse"><stop class="nfovzcb5l"/><stop offset="1" class="u_c-lyb9q"/></radialGradient><radialGradient id="ihmDWPb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.74999 -2.77574 1.37832 -1.36553 12.182 13.46)" gradientUnits="userSpaceOnUse"><stop class="xdw1w3ewj"/><stop offset="1" class="i8g2c0r-b"/></radialGradient><radialGradient id="iB3iaXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.21875 0 0 .9336 12.323 28.533)" gradientUnits="userSpaceOnUse"><stop class="j0vai4u7g"/><stop offset="1" class="f4lmhxbah"/></radialGradient><radialGradient id="iG1zLZR" cx="0" cy="0" r="1" gradientTransform="matrix(-2.32813 0 0 -1.56819 17.886 29.06)" gradientUnits="userSpaceOnUse"><stop class="qs47v_bmm"/><stop offset="1" class="ie6b5r7cr"/></radialGradient><radialGradient id="iJLVWcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71875 0 0 -.26466 20.933 28.533)" gradientUnits="userSpaceOnUse"><stop class="j0vai4u7g"/><stop offset="1" class="f4lmhxbah"/></radialGradient><radialGradient id="i13G0fc" cx="0" cy="0" r="1" gradientTransform="rotate(133.272 6.708 7.927)scale(2.35441 1.95304)" gradientUnits="userSpaceOnUse"><stop class="fpw7gp92a"/><stop offset="1" class="ko2vygbol"/></radialGradient><radialGradient id="iJXmajc" cx="0" cy="0" r="1" gradientTransform="matrix(1.01562 -.14062 .1276 .92152 16.683 9.06)" gradientUnits="userSpaceOnUse"><stop class="dq29i76rc"/><stop offset="1" class="dmgxs5a6s"/></radialGradient><radialGradient id="iGFQ6fd" cx="0" cy="0" r="1" gradientTransform="rotate(-168.299 13.071 10.17)scale(4.46849 1.29516)" gradientUnits="userSpaceOnUse"><stop class="hl4awjy6a"/><stop offset="1" class="b49ky5onl"/></radialGradient><radialGradient id="i4p5Sbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 14.645 10.414)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iSh3Wmb" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 5.316 8.07)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iEg0aOe" cx="0" cy="0" r="1" gradientTransform="matrix(2.54688 .8125 -.1632 .51157 10.745 9.388)" gradientUnits="userSpaceOnUse"><stop class="st87z2bmx"/><stop offset="1" class="i4i29lbal"/></radialGradient><filter id="i8In7qd" width="13.121" height="7.001" x="2.874" y="16.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="iT3JMJj" width="14" height="4.87" x="1.995" y="14.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="io7Hajb" width="13.107" height="6.997" x="2.888" y="10.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="istRHYb" width="10.582" height="10.783" x="5.412" y="6.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="iFWWQ5d" width="6.797" height="13.312" x="9.198" y="3.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="iVpYipc" width="4.67" height="14.2" x="13.665" y="2.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="ih46jqc" width="6.797" height="13.307" x="15.995" y="3.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="if1GIKe" width="10.582" height="10.783" x="15.995" y="6.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="imONc0x" width="13.121" height="7.001" x="15.995" y="10.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="i2uUfEb" width="14" height="4.87" x="15.995" y="14.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="imIp1Sd" width="13.107" height="6.976" x="15.995" y="16.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.839216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 0 0.623529 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_5206" result="effect2_innerShadow_28327_5206"/></filter><filter id="ih4nuAd" width="4.505" height="13.406" x="12.216" y="8.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5206" stdDeviation=".75"/></filter><filter id="icOjcWb" width="8.118" height="6.359" x="15.685" y="16.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5206" stdDeviation=".15"/></filter><filter id="ieunjir" width="7.862" height="6.81" x="15.985" y="15.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.278431 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5206"/></filter><filter id="i96LIje" width="3.188" height="2.328" x="10.245" y="8.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5206" stdDeviation=".25"/></filter><filter id="iZh73vZ" width="6.441" height="4.342" x="16.486" y="18.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5206" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:peacock" /></template>
<style>
.afby5ze3i {
  d: path("M12.682 12.054a6.5 6.5 0 0 0-1.823 1.61l5.136 3.396z");
}

.affks_buj {
  fill: var(--svg-color--3e9af8, #3E9AF8);
  d: path("M4.065 17.06c0 .48.29.89.71 1.06c.42-.17.71-.59.71-1.06s-.29-.89-.71-1.06c-.42.17-.71.58-.71 1.06");
}

.aihyutb-t {
  fill: var(--svg-color--f1a237, #F1A237);
  d: path("M16.363 28.005h-2.767c-.42 0-.911.37-.911.823c0 .128.104.232.232.232h4.182a.23.23 0 0 0 .232-.232c0-.453-.538-.823-.968-.823");
}

.aintevxed {
  stop-color: var(--svg-color--3ed988, #3ED988);
}

.au7epcb_l {
  stop-color: var(--svg-color--4aee91, #4AEE91);
}

.ayjz2abhx {
  fill-rule: evenodd;
  d: path("m15.995 17.06l-6.461 1.252c.094.92.381 1.784.815 2.558l5.64-3.806z");
}

.b49ky5onl {
  stop-color: var(--svg-color--52a6ff, #52A6FF);
  stop-opacity: 0;
}

.b9sb2trlq {
  stop-color: var(--svg-color--41d485, #41D485);
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bj7q6ebjw {
  d: path("M6.425 10.6c-.1-.06-.2-.11-.31-.16c-1.2-.49-2.56.07-3.05 1.26a2.336 2.336 0 0 0 1.72 3.19l11.21 2.17l-9.37-6.33c-.07-.05-.13-.09-.2-.13");
}

.btpi9qb0m {
  fill: var(--svg-color--fff864, #FFF864);
  d: path("M27.665 18.21a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.c8o1x9jtg {
  fill: var(--svg-color--fff664, #FFF664);
  d: path("M26.775 22.67a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.cd_p-9blu {
  d: path("M4.655 19.26c-.11.03-.22.06-.34.11a2.327 2.327 0 0 0-1.26 3.05a2.327 2.327 0 0 0 3.47 1.03l9.47-6.39l-11.1 2.15c-.08.01-.16.03-.24.05");
}

.cmj-yob3m {
  d: path("M23.795 23.48c-.167-.896-.222-1.373-1.82-2.36l-5.12-3.39c-.01 0-.01-.01-.02-.01c-.51-.35-.85-.94-.85-1.6v-4.7a2.35 2.35 0 0 0-2.35-2.36h-2.89c-.29 0-.43.34-.24.55l1.6 1.71c.44.47.64 1.11.54 1.74l-1.1 7.34a3.183 3.183 0 0 0 3.15 3.66h8.69c.3 0 .474-.238.41-.58");
}

.cmkekgetr {
  fill: var(--svg-color--ffed4b, #FFED4B);
  d: path("M15.995 6.54a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.cyg2-jbrv {
  fill: var(--svg-color--43a9fc, #43A9FC);
  d: path("M15.995 5.13c-.48 0-.89.29-1.06.71c.17.42.59.71 1.06.71s.89-.29 1.06-.71c-.17-.42-.58-.71-1.06-.71");
}

.d-3o38bsv {
  stop-color: var(--svg-color--378cc7, #378CC7);
  stop-opacity: 0;
}

.d4ehd0uag {
  stop-color: var(--svg-color--faaa3c, #FAAA3C);
}

.dc018zbdm {
  stop-color: var(--svg-color--6882c3, #6882C3);
}

.ddul8pboi {
  d: path("M22.226 15.79L15.8 17.217l6.66 1.082c.018-.157.019-.237.025-.398a6.5 6.5 0 0 0-.26-2.11");
}

.dfq2-66to {
  d: path("M18.305 5.75c.02-.11.03-.23.03-.35a2.343 2.343 0 0 0-2.34-2.34a2.326 2.326 0 0 0-2.28 2.81l2.28 11.19l2.26-11.08c.02-.08.03-.16.05-.23");
}

.dmgxs5a6s {
  stop-color: var(--svg-color--695f74, #695F74);
  stop-opacity: 0;
}

.dq29i76rc {
  stop-color: var(--svg-color--695f74, #695F74);
}

.drpbptstb {
  d: path("M19.3 12.048a6.1 6.1 0 0 0-2.179-.806l-1.204 6.052z");
}

.ds50n1bpc {
  stop-color: var(--svg-color--c0de46, #C0DE46);
  stop-opacity: 0;
}

.dwucvrkbl {
  fill: var(--svg-color--fff154, #FFF154);
  d: path("M20.455 7.43a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.f2jjtac9l {
  fill: var(--svg-color--5fb9ff, #5FB9FF);
  d: path("M27.015 21.63c.18-.44.07-.93-.25-1.26c-.45 0-.88.27-1.06.71s-.07.93.25 1.26c.45 0 .88-.27 1.06-.71");
}

.f3muymbql {
  d: path("m15.995 17.06l-6.227-1.27a6.5 6.5 0 0 0-.228 2.585z");
}

.f4lmhxbah {
  stop-color: var(--svg-color--ffc76a, #FFC76A);
  stop-opacity: 0;
}

.fpw7gp92a {
  stop-color: var(--svg-color--403751, #403751);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvf0w2bpv {
  fill: var(--svg-color--3ea6f9, #3EA6F9);
  d: path("M11.425 6.04c-.44.18-.71.61-.71 1.06c.32.32.81.43 1.26.25c.44-.18.71-.61.71-1.06c-.32-.32-.81-.44-1.26-.25");
}

.g-monbn-t {
  stop-color: var(--svg-color--3e93ef, #3E93EF);
}

.gf4_w-bwq {
  stop-color: var(--svg-color--42e591, #42E591);
}

.gjsikvb1v {
  stop-color: var(--svg-color--a7af42, #A7AF42);
}

.gymy9h2-v {
  fill: var(--svg-color--5ab5ff, #5AB5FF);
  d: path("M27.015 12.49c-.18-.44-.61-.71-1.06-.71c-.32.32-.43.81-.25 1.26s.61.71 1.06.71c.32-.32.44-.81.25-1.26");
}

.hd8dqccmn {
  d: path("m22.526 21.961l-5.64-3.542v1.542a2 2 0 0 0 2 2z");
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hirmu1bim {
  stop-color: var(--svg-color--f1a237, #F1A237);
}

.hl4awjy6a {
  stop-color: var(--svg-color--52a6ff, #52A6FF);
}

.hw0karqid {
  d: path("M22.455 7.49c.06-.1.11-.2.16-.31c.49-1.19-.07-2.56-1.26-3.05a2.336 2.336 0 0 0-3.19 1.72l-2.17 11.21l6.33-9.37c.05-.07.09-.13.13-.2");
}

.i4i29lbal {
  stop-color: var(--svg-color--776787, #776787);
  stop-opacity: 0;
}

.i8g2c0r-b {
  stop-color: var(--svg-color--37a06b, #37A06B);
  stop-opacity: 0;
}

.ie6b5r7cr {
  stop-color: var(--svg-color--c77e33, #C77E33);
  stop-opacity: 0;
}

.iolbbgdbc {
  stop-color: var(--svg-color--3ac581, #3AC581);
}

.j0vai4u7g {
  stop-color: var(--svg-color--ffc76a, #FFC76A);
}

.jfg2seb_f {
  stop-color: var(--svg-color--3de28a, #3DE28A);
}

.k83948b6w {
  stop-color: var(--svg-color--40db87, #40DB87);
}

.kceo08bfp {
  stop-color: var(--svg-color--6882c3, #6882C3);
  stop-opacity: 0;
}

.ko2vygbol {
  stop-color: var(--svg-color--403751, #403751);
}

.kxfv0d3jx {
  d: path("M14.495 11.076a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.kxrn_8fmd {
  fill: var(--svg-color--faaa3c, #FAAA3C);
  d: path("M19.675 28.005h-2.767c-.42 0-.91.37-.91.823c0 .128.103.232.232.232h4.182a.23.23 0 0 0 .232-.232c0-.453-.539-.823-.969-.823");
}

.l_334t98h {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M16.363 28.005h-2.767c-.42 0-.911.37-.911.823c0 .128.104.232.232.232h4.182a.23.23 0 0 0 .232-.232c0-.453-.538-.823-.968-.823");
}

.l0na836kg {
  stop-color: var(--svg-color--bc6e37, #BC6E37);
}

.lp057bbcg {
  fill: var(--svg-color--ffe546, #FFE546);
  d: path("M7.745 9.96a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.lqudwibip {
  d: path("m22.456 18.305l-6.461-1.078v2.02l3.905 3.587a6.5 6.5 0 0 0 2.556-4.53");
}

.mpox7eh9k {
  fill: var(--svg-color--6775c4, #6775C4);
  d: path("m21.975 21.12l-5.12-3.39c-.01 0-.01-.01-.02-.01c-.51-.35-.85-.94-.85-1.6v4.08a2.48 2.48 0 0 0 2.48 2.48h5.132c-.204-.651-1.012-1.16-1.622-1.56");
}

.myjv66buv {
  stop-color: var(--svg-color--c2ec46, #C2EC46);
  stop-opacity: 0;
}

.n4n4jhb5e {
  stop-color: var(--svg-color--42d087, #42D087);
}

.n8sww8ycp {
  d: path("M27.335 14.86c.11-.03.22-.06.34-.11a2.327 2.327 0 0 0 1.26-3.05a2.33 2.33 0 0 0-3.47-1.03l-9.47 6.39l11.1-2.15c.08-.01.16-.03.24-.05");
}

.n9uzh9wnc {
  stop-color: var(--svg-color--39b386, #39B386);
}

.nfovzcb5l {
  stop-color: var(--svg-color--69fca7, #69FCA7);
}

.nm-07mb5n {
  stop-color: var(--svg-color--5ef49d, #5EF49D);
}

.nnbpx21zd {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m15.995 17.06l-9.47 6.39a2.327 2.327 0 0 1-3.47-1.03a2.33 2.33 0 0 1 1.214-3.03a2.326 2.326 0 0 1-2.274-2.33c0-1.265 1-2.29 2.264-2.338A2.336 2.336 0 0 1 3.065 11.7a2.33 2.33 0 0 1 2.986-1.285a2.336 2.336 0 0 1 .044-3.255a2.336 2.336 0 0 1 3.26-.038a2.33 2.33 0 0 1 1.28-2.992a2.33 2.33 0 0 1 3.03 1.205a2.326 2.326 0 0 1 2.33-2.275c1.265 0 2.29 1 2.338 2.264a2.336 2.336 0 0 1 3.022-1.194a2.335 2.335 0 0 1 1.285 2.986a2.336 2.336 0 0 1 3.255.044c.897.897.91 2.347.039 3.26a2.33 2.33 0 0 1 3.001 1.28a2.327 2.327 0 0 1-1.214 3.03a2.326 2.326 0 0 1 2.274 2.33c0 1.265-1 2.29-2.264 2.338a2.337 2.337 0 0 1 1.194 3.022c-.594 1.444-2.422 1.823-3.64.953z");
}

.no-l0kb3e {
  stop-color: var(--svg-color--6263f5, #6263F5);
  stop-opacity: 0;
}

.o7b85ac2m {
  stop-color: var(--svg-color--51f096, #51F096);
}

.pevyw7npa {
  fill: var(--svg-color--4daeff, #4DAEFF);
  d: path("M20.565 6.04a1.17 1.17 0 0 0-1.26.25c0 .45.27.88.71 1.06s.93.07 1.26-.25c0-.45-.27-.88-.71-1.06");
}

.plza5ccxz {
  fill: var(--svg-color--ffd847, #FFD847);
  d: path("M4.325 18.21a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.ps1vum79n {
  fill: var(--svg-color--53b1ff, #53B1FF);
  d: path("M24.435 8.62a1.15 1.15 0 0 0-1.25-.25a1.15 1.15 0 0 0 1.5 1.5c.17-.41.09-.91-.25-1.25");
}

.pwj64qgdq {
  fill: var(--svg-color--ffe946, #FFE946);
  d: path("M11.535 7.43a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.qeudmbbqr {
  stop-color: var(--svg-color--ff884f, #FF884F);
}

.ql8z9qeiv {
  fill: var(--svg-color--5db7ff, #5DB7FF);
  d: path("M27.925 17.06c0-.48-.29-.89-.71-1.06c-.42.17-.71.59-.71 1.06s.29.89.71 1.06c.42-.17.71-.58.71-1.06");
}

.qs47v_bmm {
  stop-color: var(--svg-color--c77e33, #C77E33);
}

.qv9jfabme {
  d: path("M29.995 17.06a2.326 2.326 0 0 0-2.81-2.28l-11.19 2.28l11.08 2.26c.08.02.15.04.23.05c.11.02.23.03.35.03c1.3-.01 2.34-1.05 2.34-2.34");
}

.r4uvyddzz {
  stop-color: var(--svg-color--b3cd3b, #B3CD3B);
}

.rdal98o9d {
  stop-color: var(--svg-color--a7af42, #A7AF42);
  stop-opacity: 0;
}

.rj64x8b-f {
  d: path("M1.995 17.06a2.326 2.326 0 0 0 2.81 2.28l11.19-2.28l-11.08-2.26c-.08-.02-.15-.04-.23-.05c-.11-.02-.23-.03-.35-.03c-1.3.01-2.34 1.05-2.34 2.34");
}

.rn-__nk_y {
  d: path("M9.625 7.43c-.07-.1-.15-.18-.23-.27c-.91-.91-2.39-.91-3.3 0a2.336 2.336 0 0 0 .37 3.6l9.53 6.3l-6.24-9.43c-.04-.07-.08-.14-.13-.2");
}

.rz-0m0fpi {
  d: path("M16.363 28.005h-2.767c-.42 0-.911.37-.911.823c0 .128.104.232.232.232h4.182a.23.23 0 0 0 .232-.232c0-.453-.538-.823-.968-.823");
}

.rzbsyx2ca {
  fill: var(--svg-color--3ca3fc, #3CA3FC);
  d: path("M7.555 8.62c-.34.34-.42.84-.25 1.26a1.15 1.15 0 0 0 1.5-1.5c-.41-.18-.91-.1-1.25.24");
}

.s5ml4ibxa {
  stop-color: var(--svg-color--6263f5, #6263F5);
}

.s9g5_n5vc {
  fill: var(--svg-color--52a6ff, #52A6FF);
  d: path("m15.221 10.39l-.14 9.31a.683.683 0 1 1-1.363-.06l.67-9.286a.418.418 0 0 1 .833.036");
}

.sj9ng07_p {
  stop-color: var(--svg-color--3fc78d, #3FC78D);
}

.ska2-uh4o {
  stop-color: var(--svg-color--378cc7, #378CC7);
}

.so88etl_h {
  d: path("M15.265 8.46v1.46c0 .15.12.27.27.27h1.46c.16 0 .28-.14.25-.3c-.13-.87-.81-1.55-1.68-1.68c-.16-.03-.3.09-.3.25");
}

.st87z2bmx {
  stop-color: var(--svg-color--776787, #776787);
}

.sthm4ntwl {
  fill: var(--svg-color--ffde47, #FFDE47);
  d: path("M5.215 13.75a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.svexzijcj {
  d: path("M15.684 28.826h-1.082l1.094-5.047h1.082z");
}

.tb-2tw0to {
  stop-color: var(--svg-color--46e693, #46E693);
}

.tfi9e1bkp {
  fill: var(--svg-color--3d9cf9, #3D9CF9);
  d: path("M4.975 12.49c-.18.44-.07.93.25 1.26c.45 0 .88-.27 1.06-.71s.07-.93-.25-1.26c-.45 0-.88.27-1.06.71");
}

.thgftzbvq {
  d: path("M19.675 28.005h-2.767c-.42 0-.91.37-.91.823c0 .128.103.232.232.232h4.182a.23.23 0 0 0 .232-.232c0-.453-.539-.823-.969-.823");
}

.u_c-lyb9q {
  stop-color: var(--svg-color--59eda1, #59EDA1);
}

.u4phyi77o {
  stop-color: var(--svg-color--493a5f, #493A5F);
}

.u5l-jmbtq {
  d: path("M28.925 22.42a2.336 2.336 0 0 0-1.72-3.19l-11.21-2.17l9.29 6.313c1.218.87 3.046.49 3.64-.953");
}

.ukn92sasg {
  d: path("m10.745 9.388l1.71 1.328l.477-1.328z");
}

.v0vxky7tf {
  fill: var(--svg-color--fed548, #FED548);
  d: path("M5.215 22.67a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.v13kbsb4e {
  fill: var(--svg-color--fff45d, #FFF45D);
  d: path("M24.245 9.96a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.vei161n9z {
  stop-color: var(--svg-color--3eca87, #3ECA87);
}

.vgc652-ck {
  d: path("M13.795 5.72c-.03-.11-.06-.22-.11-.34a2.33 2.33 0 0 0-3.05-1.25c-1.19.5-1.75 1.85-1.26 3.04c.06.15.14.29.23.42l6.39 9.47l-2.15-11.1c-.01-.08-.03-.16-.05-.24");
}

.vpcngmopr {
  d: path("M22.222 15.79a6.2 6.2 0 0 0-1.124-2.173l-5.142 3.576z");
}

.vsr2_ob8p {
  stop-color: var(--svg-color--4478ff, #4478FF);
}

.w-qrc6bga {
  stop-color: var(--svg-color--ff884f, #FF884F);
  stop-opacity: 0;
}

.wgpa89bxq {
  fill: var(--svg-color--fff764, #FFF764);
  d: path("M26.775 13.75a1.15 1.15 0 1 0 0-2.3a1.15 1.15 0 0 0 0 2.3");
}

.wsbjij2jl {
  stop-color: var(--svg-color--3fdf88, #3FDF88);
}

.x8ugri1sy {
  d: path("m12.595 13.39l.76-4.33h-2.61c-.29 0-.43.34-.24.55l1.6 1.71c.44.47.64 1.11.54 1.74z");
}

.xdw1w3ewj {
  stop-color: var(--svg-color--37a06b, #37A06B);
}

.xk1gd1dbl {
  d: path("m14.624 17.988l1.173-.794l-2.49-.415z");
}

.xl4jfwb2p {
  d: path("M25.625 10.69c.09-.07.18-.15.27-.23c.91-.91.91-2.39 0-3.3a2.336 2.336 0 0 0-3.6.37l-6.3 9.53l9.43-6.24c.07-.04.14-.08.2-.13");
}

.xt6te7bal {
  fill: var(--svg-color--2a6dfe, #2A6DFE);
  d: path("m21.243 21.51l-4.494-2.977c-.01 0-.01-.008-.018-.008a1.71 1.71 0 0 1-.746-1.405v3.582c0 1.202.974 2.177 2.177 2.177l5.34-.217c-.859-.475-1.723-.801-2.259-1.153");
}

.y2guwm-1z {
  d: path("M10.897 13.616a6.5 6.5 0 0 0-1.147 2.235l6.245 1.21z");
}

.y4agq-04l {
  stop-color: var(--svg-color--c0de46, #C0DE46);
}

.y4f0v-bnu {
  stop-color: var(--svg-color--defd59, #DEFD59);
}

.y70mlg5_t {
  d: path("M21.1 13.619a6.3 6.3 0 0 0-1.792-1.57l-3.344 5.156z");
}

.yasa7wb3i {
  d: path("M18.684 28.826h-1.082l1.094-5.047h1.082z");
}

.ynzzttbpu {
  d: path("M16.255 11.15a6.496 6.496 0 0 0-6.75 6.24c-.05 1.27.27 2.46.85 3.49l5.64-3.82v7.08c3.47 0 6.35-2.74 6.49-6.24a6.49 6.49 0 0 0-6.23-6.75");
}

.zon8518hh {
  stop-color: var(--svg-color--3ce78a, #3CE78A);
}

.ztuy1ib2v {
  fill: var(--svg-color--3e99fa, #3E99FA);
  d: path("M4.975 21.63c.18.44.61.71 1.06.71c.32-.32.43-.81.25-1.26c-.18-.44-.61-.71-1.06-.71c-.32.32-.44.81-.25 1.26");
}

.zx9irmbkz {
  stop-color: var(--svg-color--5d4f6b, #5D4F6B);
}

</style>
