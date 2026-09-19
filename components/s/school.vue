<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOX4ywY)"><path fill="url(#ibl4UWc)" class="gwn_1ccuu"/><path fill="url(#iDkC88S)" class="gwn_1ccuu"/></g><g filter="url(#iKgPtMd)"><path fill="url(#iqcQfPd)" class="p7v72j76i"/></g><g filter="url(#ihEUsdb)"><rect class="ic-c_abvr"/></g><g filter="url(#ixc4xsb)"><path class="ng-ypcb8s"/><path fill="url(#iJA3WAd)" class="jc__lxoxw"/></g><path fill="url(#iUmMVSc)" class="nvbochb-g"/><path fill="url(#i8pLDwC)" class="nvbochb-g"/><path fill="url(#iHQBone)" class="j6d_wpbqx"/><path fill="url(#iZHW9Rd)" class="j6d_wpbqx"/><path fill="url(#igEvTcb)" class="j6d_wpbqx"/><path fill="url(#irpKvmz)" class="j6d_wpbqx"/><path fill="url(#i2ToPjd)" class="ov5cz3brp"/><path fill="url(#iPe0oKd)" class="ov5cz3brp"/><path fill="url(#ipI9Lrc)" class="ov5cz3brp"/><path fill="url(#ibJRRne)" class="ov5cz3brp"/><g filter="url(#i8Q9l7d)"><path class="p60-2gwhx"/></g><path fill="url(#iFUrgQc)" class="r7by9lkxi"/><path fill="url(#i3v2bae)" class="r7by9lkxi"/><path fill="url(#ifjTukb)" class="r7by9lkxi"/><path fill="url(#iTDTdpc)" class="r7by9lkxi"/><path fill="url(#iLaXwCe)" class="r7by9lkxi"/><path fill="url(#i7s8hXd)" class="r7by9lkxi"/><path fill="url(#iDkjIuM)" class="r7by9lkxi"/><g filter="url(#iPSJ7Yb)"><path fill="url(#iHf94Ad)" class="ugk3dybkd"/><path fill="url(#iAuTaid)" class="ugk3dybkd"/></g><g filter="url(#iwAGWrd)"><path fill="url(#iZ8aQ4x)" class="k1e101klk"/><path fill="url(#iRZawQb)" class="k1e101klk"/></g><g filter="url(#iqkopCe)"><path fill="url(#iNxGJ3i)" class="vv2yptbdp"/><path fill="url(#iQTUyhe)" class="vv2yptbdp"/></g><g filter="url(#ilLinGo)"><path fill="url(#i4rmWnd)" class="j3kqcudxt"/><path fill="url(#ifISSfd)" class="j3kqcudxt"/></g><g filter="url(#ic940Cb)"><path fill="url(#iuAMOwe)" class="ikgt1kboh"/><path fill="url(#iYKVHph)" class="ikgt1kboh"/></g><g filter="url(#igJxSmd)"><path fill="url(#iEtH5Fb)" class="gwxgqq3zg"/><path fill="url(#issEqpd)" class="gwxgqq3zg"/></g><g filter="url(#iltJwme)"><path fill="url(#idKHd9b)" class="fqnnowsgd"/><path fill="url(#iZMigLd)" class="fqnnowsgd"/></g><g filter="url(#iTNT3ib)"><path fill="url(#ik0imFd)" class="h9q5bgbwz"/><path fill="url(#iNcW9wc)" class="h9q5bgbwz"/></g><g filter="url(#ienjnhd)"><path class="icxqqsfrr"/></g><path fill="url(#i4EFH8b)" class="rgyc0q40a"/><path fill="url(#iC6pcSb)" class="rgyc0q40a"/><path fill="url(#ivMHlpe)" class="x51rrrrnr"/><g filter="url(#iW8kJVd)"><path fill="url(#iGv2lKb)" class="ltj-lab6n"/></g><path fill="url(#izWIkkb)" class="r8ip0ltfb"/><path fill="url(#i2usdCc)" class="r8ip0ltfb"/><path fill="url(#iBoej6E)" class="r8ip0ltfb"/><g filter="url(#ixqUgCd)"><path fill="url(#icp2pcS)" class="ntik9obwh"/><path fill="url(#iSG8SMb)" class="ntik9obwh"/></g><g filter="url(#iQ2cFdB)"><path stroke="url(#ikeVZEe)" class="nnz77-3to"/></g><g filter="url(#ikTgcEc)"><path stroke="url(#ia6NvHe)" class="sc6z3hbsw"/></g><defs><linearGradient id="ibl4UWc" x1="16.015" x2="16.015" y1="11.194" y2="15.829" gradientUnits="userSpaceOnUse"><stop class="qw9tlsbfl"/><stop offset="1" class="tanwxjbmp"/></linearGradient><linearGradient id="iDkC88S" x1="2.859" x2="3.436" y1="14.319" y2="14.49" gradientUnits="userSpaceOnUse"><stop class="tikb45b7e"/><stop offset="1" class="afurvzb-t"/></linearGradient><linearGradient id="iqcQfPd" x1="17.796" x2="19.921" y1="4.632" y2="4.632" gradientUnits="userSpaceOnUse"><stop class="xb86ftbak"/><stop offset="1" class="ffr-nmfyg"/></linearGradient><linearGradient id="iJA3WAd" x1="17.765" x2="17.765" y1="4.406" y2="3.783" gradientUnits="userSpaceOnUse"><stop class="tniinjbbu"/><stop offset="1" class="u087gebjh"/></linearGradient><linearGradient id="iHQBone" x1="5.533" x2="5.533" y1="15.819" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="shswahwug"/><stop offset="1" class="i5e8_oeqc"/></linearGradient><linearGradient id="iZHW9Rd" x1="9.621" x2="6.567" y1="23.599" y2="23.599" gradientUnits="userSpaceOnUse"><stop class="wa6_x7b-y"/><stop offset="1" class="lh4chpbje"/></linearGradient><linearGradient id="igEvTcb" x1="2.015" x2="2.765" y1="27.288" y2="27.288" gradientUnits="userSpaceOnUse"><stop class="wsbkp0baj"/><stop offset="1" class="tqr70_b4f"/></linearGradient><linearGradient id="irpKvmz" x1="5.533" x2="5.533" y1="14.657" y2="16.557" gradientUnits="userSpaceOnUse"><stop class="sscrw9bhg"/><stop offset="1" class="xe_r_zrms"/></linearGradient><linearGradient id="i2ToPjd" x1="23.015" x2="30.015" y1="26.874" y2="26.874" gradientUnits="userSpaceOnUse"><stop class="kk_rf8b9y"/><stop offset="1" class="yp6fmsbhu"/></linearGradient><linearGradient id="iPe0oKd" x1="30.015" x2="29.375" y1="25.033" y2="25.033" gradientUnits="userSpaceOnUse"><stop class="mks9mwbhm"/><stop offset="1" class="fwm3kcbrh"/></linearGradient><linearGradient id="ipI9Lrc" x1="25.545" x2="25.545" y1="15.664" y2="16.208" gradientUnits="userSpaceOnUse"><stop class="xwcna_djh"/><stop offset="1" class="dn61jwb-a"/></linearGradient><linearGradient id="iFUrgQc" x1="11.203" x2="22.328" y1="21.507" y2="23.882" gradientUnits="userSpaceOnUse"><stop class="k1zutcbgw"/><stop offset="1" class="hqfhebbmr"/></linearGradient><linearGradient id="i3v2bae" x1="8.703" x2="9.796" y1="24.78" y2="24.78" gradientUnits="userSpaceOnUse"><stop offset=".214" class="ght76j3wf"/><stop offset=".657" class="pivub0baf"/><stop offset=".914" class="tyxfc_81u"/></linearGradient><linearGradient id="ifjTukb" x1="23.025" x2="22.465" y1="24.205" y2="24.205" gradientUnits="userSpaceOnUse"><stop offset=".403" class="xukqp8q9i"/><stop offset="1" class="qdi930onq"/></linearGradient><linearGradient id="iTDTdpc" x1="20.053" x2="19.241" y1="10.873" y2="11.686" gradientUnits="userSpaceOnUse"><stop offset=".19" class="fbmx0n_ts"/><stop offset="1" class="jmbyp5lny"/></linearGradient><linearGradient id="iLaXwCe" x1="12.343" x2="12.828" y1="10.46" y2="10.944" gradientUnits="userSpaceOnUse"><stop class="rnf7azazi"/><stop offset="1" class="uv6jp-ebe"/></linearGradient><linearGradient id="iHf94Ad" x1="24.416" x2="26.014" y1="19.692" y2="19.731" gradientUnits="userSpaceOnUse"><stop class="z8a72bc2q"/><stop offset=".842" class="t18t3l_hk"/><stop offset="1" class="wvpwzbcdc"/></linearGradient><linearGradient id="iAuTaid" x1="24.015" x2="24.288" y1="19.319" y2="19.319" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iZ8aQ4x" x1="27.416" x2="29.014" y1="19.692" y2="19.731" gradientUnits="userSpaceOnUse"><stop class="z8a72bc2q"/><stop offset=".842" class="t18t3l_hk"/><stop offset="1" class="wvpwzbcdc"/></linearGradient><linearGradient id="iRZawQb" x1="27.015" x2="27.288" y1="19.319" y2="19.319" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iNxGJ3i" x1="24.416" x2="26.014" y1="23.692" y2="23.731" gradientUnits="userSpaceOnUse"><stop class="z8a72bc2q"/><stop offset=".842" class="t18t3l_hk"/><stop offset="1" class="wvpwzbcdc"/></linearGradient><linearGradient id="iQTUyhe" x1="24.015" x2="24.288" y1="23.319" y2="23.319" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="i4rmWnd" x1="27.416" x2="29.014" y1="23.692" y2="23.731" gradientUnits="userSpaceOnUse"><stop class="z8a72bc2q"/><stop offset=".842" class="t18t3l_hk"/><stop offset="1" class="wvpwzbcdc"/></linearGradient><linearGradient id="ifISSfd" x1="27.015" x2="27.288" y1="23.319" y2="23.319" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iuAMOwe" x1="3.48" x2="5.378" y1="20.292" y2="17.684" gradientUnits="userSpaceOnUse"><stop class="v7s5807mx"/><stop offset="1" class="t18t3l_hk"/></linearGradient><linearGradient id="iYKVHph" x1="3.035" x2="3.308" y1="19.319" y2="19.319" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iEtH5Fb" x1="6.48" x2="8.378" y1="20.292" y2="17.684" gradientUnits="userSpaceOnUse"><stop class="v7s5807mx"/><stop offset="1" class="t18t3l_hk"/></linearGradient><linearGradient id="issEqpd" x1="6.035" x2="6.308" y1="19.319" y2="19.319" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="idKHd9b" x1="3.48" x2="5.378" y1="24.292" y2="21.684" gradientUnits="userSpaceOnUse"><stop class="v7s5807mx"/><stop offset="1" class="t18t3l_hk"/></linearGradient><linearGradient id="iZMigLd" x1="3.035" x2="3.308" y1="23.319" y2="23.319" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="ik0imFd" x1="6.48" x2="8.378" y1="24.292" y2="21.684" gradientUnits="userSpaceOnUse"><stop class="v7s5807mx"/><stop offset="1" class="t18t3l_hk"/></linearGradient><linearGradient id="iNcW9wc" x1="6.035" x2="6.308" y1="23.319" y2="23.319" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="ivMHlpe" x1="15.515" x2="17.837" y1="14.329" y2="16.651" gradientUnits="userSpaceOnUse"><stop class="p5-nbbcqi"/><stop offset="1" class="qcskxlr5n"/></linearGradient><linearGradient id="iGv2lKb" x1="16.015" x2="16.015" y1="5.877" y2="16.329" gradientUnits="userSpaceOnUse"><stop class="vkmtrvjyw"/><stop offset="1" class="iiinxpb6m"/></linearGradient><linearGradient id="izWIkkb" x1="20.106" x2="19.825" y1="9.504" y2="9.785" gradientUnits="userSpaceOnUse"><stop class="gl3z79bzr"/><stop offset="1" class="n7o01cbji"/></linearGradient><linearGradient id="i2usdCc" x1="16.015" x2="16.015" y1="16.819" y2="15.658" gradientUnits="userSpaceOnUse"><stop class="kq2ruuocq"/><stop offset="1" class="g4yfurb0c"/></linearGradient><linearGradient id="icp2pcS" x1="12.975" x2="19.025" y1="27.304" y2="27.304" gradientUnits="userSpaceOnUse"><stop class="pahuys4ro"/><stop offset="1" class="sonoorbys"/></linearGradient><linearGradient id="iSG8SMb" x1="12.975" x2="13.616" y1="27.328" y2="27.328" gradientUnits="userSpaceOnUse"><stop offset=".347" class="lyo8oqjef"/><stop offset="1" class="ts_yhlsui"/></linearGradient><linearGradient id="ikeVZEe" x1="17.719" x2="15.908" y1="16.359" y2="14.652" gradientUnits="userSpaceOnUse"><stop class="hbseibcpc"/><stop offset="1" class="s7lhanb_o"/></linearGradient><linearGradient id="ia6NvHe" x1="23.718" x2="16.304" y1="14.042" y2="6.17" gradientUnits="userSpaceOnUse"><stop class="m55yq8b6f"/><stop offset="1" class="u5rofobgi"/></linearGradient><filter id="iOX4ywY" width="28.25" height="5.27" x="1.765" y="10.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.435294 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="iKgPtMd" width="3.28" height="2.3" x="17.375" y="2.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 1 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.447059 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6570" result="effect2_innerShadow_18_6570"/></filter><filter id="ihEUsdb" width="1.843" height=".43" x="17.518" y="3.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6570" stdDeviation=".05"/></filter><filter id="ixc4xsb" width="3.65" height="2.15" x="15.865" y="2.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.937255 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="i8Q9l7d" width="6.703" height="5.402" x="5.036" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6570" stdDeviation="1"/></filter><filter id="iPSJ7Yb" width="2.15" height="3.05" x="23.865" y="17.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="iwAGWrd" width="2.15" height="3.05" x="26.865" y="17.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="iqkopCe" width="2.15" height="3.05" x="23.865" y="21.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="ilLinGo" width="2.15" height="3.05" x="26.865" y="21.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="ic940Cb" width="2.15" height="3.05" x="2.885" y="17.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="igJxSmd" width="2.15" height="3.05" x="5.885" y="17.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="iltJwme" width="2.15" height="3.05" x="2.885" y="21.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="iTNT3ib" width="2.15" height="3.05" x="5.885" y="21.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="ienjnhd" width="6.6" height="6.6" x="12.715" y="11.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.592157 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6570" result="effect2_innerShadow_18_6570"/></filter><filter id="iW8kJVd" width="16.5" height="10.703" x="7.815" y="5.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.258824 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.466667 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6570" result="effect2_innerShadow_18_6570"/></filter><filter id="ixqUgCd" width="6.3" height="6.25" x="12.725" y="23.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.12549 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6570"/></filter><filter id="iQ2cFdB" width="2.804" height="2.813" x="15.424" y="14.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6570" stdDeviation=".25"/></filter><filter id="ikTgcEc" width="8.284" height="8.304" x="15.706" y="5.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6570" stdDeviation=".2"/></filter><radialGradient id="iUmMVSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.3447 -1.98139 0 16.525 2.813)" gradientUnits="userSpaceOnUse"><stop class="fkiwvbbcs"/><stop offset=".868" class="b493f2b9b"/></radialGradient><radialGradient id="i8pLDwC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06047 0 0 -1.04878 16.732 1.82)" gradientUnits="userSpaceOnUse"><stop class="s5ncrac6g"/><stop offset="1" class="e9qk_jaff"/></radialGradient><radialGradient id="ibJRRne" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.17186 -.9375 0 22.906 15.82)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="xwcna_djh"/><stop offset="1" class="dn61jwb-a"/></radialGradient><radialGradient id="i7s8hXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.79688 -.76001 0 23.025 14.366)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="e527z_bbr"/><stop offset="1" class="n5cp0l83n"/></radialGradient><radialGradient id="iDkjIuM" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.4375 -.82813 0 8.843 14.303)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="e527z_bbr"/><stop offset="1" class="gebwcjbgu"/></radialGradient><radialGradient id="i4EFH8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.85923 -.85276 0 16.222 13.37)" gradientUnits="userSpaceOnUse"><stop class="glf1wpbfz"/><stop offset="1" class="hlonkzbio"/><stop offset="1" class="s7qld4btd"/></radialGradient><radialGradient id="iC6pcSb" cx="0" cy="0" r="1" gradientTransform="matrix(.47677 0 0 .25583 16.235 13.17)" gradientUnits="userSpaceOnUse"><stop class="ddcj7dbdv"/><stop offset="1" class="sb6873bis"/></radialGradient><radialGradient id="iBoej6E" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.96417 1.31017 0 16.015 8.837)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="ygpb4egnx"/><stop offset="1" class="bq70yhbbu"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:school" /></template>
<style>
.aclvogb1n {
  stop-color: var(--svg-color--5adfff, #5ADFFF);
  stop-opacity: 0;
}

.afurvzb-t {
  stop-color: var(--svg-color--735348, #735348);
  stop-opacity: 0;
}

.b493f2b9b {
  stop-color: var(--svg-color--523c35, #523C35);
}

.bq70yhbbu {
  stop-color: var(--svg-color--7e4541, #7E4541);
  stop-opacity: 0;
}

.ddcj7dbdv {
  stop-color: var(--svg-color--be8370, #BE8370);
}

.dn61jwb-a {
  stop-color: var(--svg-color--a97469, #A97469);
  stop-opacity: 0;
}

.e527z_bbr {
  stop-color: var(--svg-color--1d0c0b, #1D0C0B);
}

.e9qk_jaff {
  stop-color: var(--svg-color--d19580, #D19580);
  stop-opacity: 0;
}

.fbmx0n_ts {
  stop-color: var(--svg-color--8a594a, #8A594A);
}

.ffr-nmfyg {
  stop-color: var(--svg-color--a1e16d, #A1E16D);
}

.fkiwvbbcs {
  stop-color: var(--svg-color--b27c6d, #B27C6D);
}

.fqnnowsgd {
  d: path("M4.755 24.82h-1.44c-.15 0-.28-.13-.28-.28V22.1c0-.15.13-.28.28-.28h1.44c.15 0 .28.13.28.28v2.44c0 .16-.12.28-.28.28");
}

.ft5dv1b6b {
  fill: none;
}

.fwm3kcbrh {
  stop-color: var(--svg-color--eec9a8, #EEC9A8);
  stop-opacity: 0;
}

.g4yfurb0c {
  stop-color: var(--svg-color--543c46, #543C46);
  stop-opacity: 0;
}

.gebwcjbgu {
  stop-color: var(--svg-color--1d0c0b, #1D0C0B);
  stop-opacity: 0;
}

.ght76j3wf {
  stop-color: var(--svg-color--a3785b, #A3785B);
}

.gl3z79bzr {
  stop-color: var(--svg-color--bf8b78, #BF8B78);
}

.glf1wpbfz {
  stop-color: var(--svg-color--b1786c, #B1786C);
}

.gwn_1ccuu {
  d: path("M30.015 15.83h-28l1.72-4.31c.17-.43.58-.71 1.04-.71h22.48c.46 0 .87.28 1.04.71z");
}

.gwxgqq3zg {
  d: path("M7.755 20.82h-1.44c-.15 0-.28-.13-.28-.28V18.1c0-.15.13-.28.28-.28h1.44c.15 0 .28.13.28.28v2.44c0 .16-.12.28-.28.28");
}

.h9q5bgbwz {
  d: path("M7.755 24.82h-1.44c-.15 0-.28-.13-.28-.28V22.1c0-.15.13-.28.28-.28h1.44c.15 0 .28.13.28.28v2.44c0 .16-.12.28-.28.28");
}

.hbseibcpc {
  stop-color: var(--svg-color--c38878, #C38878);
}

.hlonkzbio {
  stop-color: var(--svg-color--6a4532, #6A4532);
}

.hqfhebbmr {
  stop-color: var(--svg-color--ffd7ab, #FFD7AB);
}

.i5e8_oeqc {
  stop-color: var(--svg-color--e79f6a, #E79F6A);
}

.ic-c_abvr {
  width: 1.643px;
  height: 0.23px;
  x: 17.618px;
  y: 4.014px;
  fill: var(--svg-color--51834c, #51834C);
  rx: 0.115px;
}

.icxqqsfrr {
  fill: var(--svg-color--eddef1, #EDDEF1);
  d: path("M16.015 17.82a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.iiinxpb6m {
  stop-color: var(--svg-color--825e59, #825E59);
}

.ikgt1kboh {
  d: path("M4.755 20.82h-1.44c-.15 0-.28-.13-.28-.28V18.1c0-.15.13-.28.28-.28h1.44c.15 0 .28.13.28.28v2.44c0 .16-.12.28-.28.28");
}

.j3kqcudxt {
  d: path("M28.735 24.82h-1.44c-.15 0-.28-.13-.28-.28V22.1c0-.15.13-.28.28-.28h1.44c.15 0 .28.13.28.28v2.44c0 .16-.12.28-.28.28");
}

.j6d_wpbqx {
  d: path("M9.05 15.82H2.015v14H9.05z");
}

.jc__lxoxw {
  d: path("M19.115 4.15h-3.1v-2h3.1c.22 0 .4.18.4.4v1.19c.01.23-.17.41-.4.41");
}

.jmbyp5lny {
  stop-color: var(--svg-color--986658, #986658);
  stop-opacity: 0;
}

.k1e101klk {
  d: path("M28.735 20.82h-1.44c-.15 0-.28-.13-.28-.28V18.1c0-.15.13-.28.28-.28h1.44c.15 0 .28.13.28.28v2.44c0 .16-.12.28-.28.28");
}

.k1zutcbgw {
  stop-color: var(--svg-color--f2b98e, #F2B98E);
}

.kk_rf8b9y {
  stop-color: var(--svg-color--ffd19e, #FFD19E);
}

.kq2ruuocq {
  stop-color: var(--svg-color--543c46, #543C46);
}

.lh4chpbje {
  stop-color: var(--svg-color--b67358, #B67358);
  stop-opacity: 0;
}

.ltj-lab6n {
  d: path("M24.015 13.96c0-.3-.12-.58-.33-.79l-7.03-7.03a.91.91 0 0 0-1.28 0l-7.03 7.03c-.21.21-.33.5-.33.79v1.87c0 .28.22.5.5.5s.5-.22.5-.5v-1.26c0-.26.1-.51.29-.69l6.15-6.15a.79.79 0 0 1 1.12 0l6.15 6.15c.18.18.29.43.29.69v1.26c0 .28.22.5.5.5s.5-.22.5-.5c0-.62-.003-1.248 0-1.87");
}

.lyo8oqjef {
  stop-color: var(--svg-color--695282, #695282);
}

.m55yq8b6f {
  stop-color: var(--svg-color--d4967e, #D4967E);
  stop-opacity: 0;
}

.mks9mwbhm {
  stop-color: var(--svg-color--eec9a8, #EEC9A8);
}

.n5cp0l83n {
  stop-color: var(--svg-color--ac7c6c, #AC7C6C);
  stop-opacity: 0;
}

.n7o01cbji {
  stop-color: var(--svg-color--bf8b78, #BF8B78);
  stop-opacity: 0;
}

.ng-ypcb8s {
  fill: var(--svg-color--4ad680, #4AD680);
  d: path("M19.115 4.15h-3.1v-2h3.1c.22 0 .4.18.4.4v1.19c.01.23-.17.41-.4.41");
}

.ngob4nbyz {
  stop-color: var(--svg-color--5adfff, #5ADFFF);
}

.nnz77-3to {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m16.05 14.841l1.553 1.564");
}

.ntik9obwh {
  d: path("M19.025 29.82h-6.05v-5.3c0-.39.31-.7.7-.7h4.65c.39 0 .7.31.7.7z");
}

.nvbochb-g {
  d: path("M16.055 6.65h-.06a.47.47 0 0 1-.47-.47V2.29c0-.26.21-.47.47-.47h.06c.26 0 .47.21.47.47v3.89c0 .26-.21.47-.47.47");
}

.ov5cz3brp {
  d: path("M23.015 15.82h7v14h-7z");
}

.p5-nbbcqi {
  stop-color: var(--svg-color--6c4b40, #6C4B40);
}

.p60-2gwhx {
  fill: var(--svg-color--8e5745, #8E5745);
  d: path("M7.036 16h2.703v1.402H7.036z");
}

.p7v72j76i {
  d: path("M17.525 3.15h2.69c.16 0 .29.13.29.29v1.42c0 .16-.13.29-.29.29h-2.08c-.33 0-.6-.27-.6-.6v-1.4z");
}

.pahuys4ro {
  stop-color: var(--svg-color--534264, #534264);
}

.pivub0baf {
  stop-color: var(--svg-color--b27e5b, #B27E5B);
}

.qcskxlr5n {
  stop-color: var(--svg-color--b16f60, #B16F60);
}

.qdi930onq {
  stop-color: var(--svg-color--ffe4b3, #FFE4B3);
  stop-opacity: 0;
}

.qw9tlsbfl {
  stop-color: var(--svg-color--a77060, #A77060);
}

.r7by9lkxi {
  d: path("m22.735 13.78l-6.15-6.06a.79.79 0 0 0-1.12 0l-6.15 6.06a.98.98 0 0 0-.29.68v15.37h14V14.45c-.01-.25-.11-.49-.29-.67");
}

.r8ip0ltfb {
  d: path("M24.015 13.96c0-.3-.12-.58-.33-.79l-7.03-7.03a.91.91 0 0 0-1.28 0l-7.03 7.03c-.21.21-.33.5-.33.79v1.82h.01c0 .02-.01.03-.01.05c0 .28.22.5.5.5s.5-.22.5-.5c0-.02-.01-.03-.01-.05h.01v-1.21c0-.26.1-.51.29-.69l6.15-6.15a.79.79 0 0 1 1.12 0l6.15 6.15c.18.18.29.43.29.69v1.26c0 .28.22.5.5.5s.5-.22.5-.5c0-.62-.003-1.248 0-1.87");
}

.rgyc0q40a {
  d: path("M16.015 15.23c-.28 0-.5-.22-.5-.5v-1.41c0-.28.22-.5.5-.5s.5.22.5.5v1.41c0 .28-.23.5-.5.5");
}

.rnf7azazi {
  stop-color: var(--svg-color--794d30, #794D30);
}

.s5ncrac6g {
  stop-color: var(--svg-color--d19580, #D19580);
}

.s7lhanb_o {
  stop-color: var(--svg-color--a57a6d, #A57A6D);
}

.s7qld4btd {
  stop-color: var(--svg-color--735351, #735351);
}

.sb6873bis {
  stop-color: var(--svg-color--be8370, #BE8370);
  stop-opacity: 0;
}

.sc6z3hbsw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m16.306 6.34l7.084 7.105");
}

.shswahwug {
  stop-color: var(--svg-color--c9885b, #C9885B);
}

.sonoorbys {
  stop-color: var(--svg-color--423b49, #423B49);
}

.sscrw9bhg {
  stop-color: var(--svg-color--8b5243, #8B5243);
}

.t18t3l_hk {
  stop-color: var(--svg-color--44acfa, #44ACFA);
}

.tanwxjbmp {
  stop-color: var(--svg-color--6e504c, #6E504C);
}

.tikb45b7e {
  stop-color: var(--svg-color--554540, #554540);
}

.tniinjbbu {
  stop-color: var(--svg-color--308649, #308649);
}

.tqr70_b4f {
  stop-color: var(--svg-color--a1714d, #A1714D);
  stop-opacity: 0;
}

.ts_yhlsui {
  stop-color: var(--svg-color--695282, #695282);
  stop-opacity: 0;
}

.tyxfc_81u {
  stop-color: var(--svg-color--dea072, #DEA072);
  stop-opacity: 0;
}

.u087gebjh {
  stop-color: var(--svg-color--308649, #308649);
  stop-opacity: 0;
}

.u5rofobgi {
  stop-color: var(--svg-color--d4967e, #D4967E);
}

.ugk3dybkd {
  d: path("M25.735 20.82h-1.44c-.15 0-.28-.13-.28-.28V18.1c0-.15.13-.28.28-.28h1.44c.15 0 .28.13.28.28v2.44c0 .16-.12.28-.28.28");
}

.uv6jp-ebe {
  stop-color: var(--svg-color--794d30, #794D30);
  stop-opacity: 0;
}

.v7s5807mx {
  stop-color: var(--svg-color--54d3ff, #54D3FF);
}

.vkmtrvjyw {
  stop-color: var(--svg-color--b67a6c, #B67A6C);
}

.vv2yptbdp {
  d: path("M25.735 24.82h-1.44c-.15 0-.28-.13-.28-.28V22.1c0-.15.13-.28.28-.28h1.44c.15 0 .28.13.28.28v2.44c0 .16-.12.28-.28.28");
}

.wa6_x7b-y {
  stop-color: var(--svg-color--935b42, #935B42);
}

.wsbkp0baj {
  stop-color: var(--svg-color--a1714d, #A1714D);
}

.wvpwzbcdc {
  stop-color: var(--svg-color--3ea2ed, #3EA2ED);
}

.x51rrrrnr {
  d: path("M17.495 16.82a.47.47 0 0 1-.35-.15l-1.48-1.48c-.2-.2-.2-.51 0-.71s.51-.2.71 0l1.48 1.48c.2.2.2.51 0 .71q-.165.15-.36.15");
}

.xb86ftbak {
  stop-color: var(--svg-color--67c175, #67C175);
}

.xe_r_zrms {
  stop-color: var(--svg-color--8b5243, #8B5243);
  stop-opacity: 0;
}

.xukqp8q9i {
  stop-color: var(--svg-color--ffe4b3, #FFE4B3);
}

.xwcna_djh {
  stop-color: var(--svg-color--a97469, #A97469);
}

.ygpb4egnx {
  stop-color: var(--svg-color--7e4541, #7E4541);
}

.yp6fmsbhu {
  stop-color: var(--svg-color--f2bea5, #F2BEA5);
}

.z8a72bc2q {
  stop-color: var(--svg-color--53c7ff, #53C7FF);
}

</style>
