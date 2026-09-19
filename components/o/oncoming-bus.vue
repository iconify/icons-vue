<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i5OgAvd)" class="uz4v66b9d"/><path fill="url(#idNXQRd)" class="uz4v66b9d"/><path fill="url(#iRZZMjd)" class="uz4v66b9d"/><g filter="url(#i2MkMLd)"><path fill="url(#i2d3N8d)" class="itcuebc2u"/></g><path fill="url(#iPTCHre)" class="itcuebc2u"/><path fill="url(#ieEL9ce)" class="itcuebc2u"/><path fill="url(#i1MCzxl)" class="itcuebc2u"/><path fill="url(#iwyyX7b)" class="mou24-q5s"/><path fill="url(#iqZuSee)" class="mou24-q5s"/><path fill="url(#iCu4Chd)" class="mou24-q5s"/><g filter="url(#i0C5SZb)"><path fill="url(#iKyowqQ)" class="qq9vw43od"/></g><path fill="url(#iHheWdd)" class="qq9vw43od"/><path fill="url(#iTAnycb)" class="qq9vw43od"/><path fill="url(#iLgM8pb)" class="v4edsdbor"/><path fill="url(#i8Ajf2c)" class="v4edsdbor"/><path fill="url(#ilRTABc)" class="v4edsdbor"/><path fill="url(#ibrkymd)" class="v4edsdbor"/><path fill="url(#iryh2rc)" class="v4edsdbor"/><path fill="url(#i1KKtDb)" class="yh0lhc3ie"/><path fill="url(#ifnwycb)" class="yh0lhc3ie"/><path fill="url(#iLkHTNb)" class="yh0lhc3ie"/><path fill="url(#ivkK5dc)" class="yh0lhc3ie"/><path fill="url(#iOLpodP)" class="yh0lhc3ie"/><g filter="url(#iMCYRVb)"><path fill="url(#ijQAoFb)" class="cposyecbc"/><path fill="url(#iZ7jQyd)" class="cposyecbc"/></g><g filter="url(#ilPqfle)"><path fill="url(#iRZwPtd)" class="a5tzb62_e"/><path fill="url(#i0ukzNc)" class="a5tzb62_e"/></g><g filter="url(#iKZDswc)"><path stroke="url(#iQ4m2fd)" class="xz75nk1_k"/></g><g filter="url(#iRIP0cc)"><path fill="url(#ixdQ9sc)" class="dqy90wtiv"/></g><path fill="url(#iFGQx3a)" class="dqy90wtiv"/><path fill="url(#illtnnj)" class="dqy90wtiv"/><path fill="url(#iFi0UNb)" class="dqy90wtiv"/><path fill="url(#ifgseKd)" class="dqy90wtiv"/><g filter="url(#iq4BKLe)"><path stroke="url(#iN5nRGb)" class="tyim3vbao"/></g><g filter="url(#igzROwf)"><path class="u_w_x8bga"/></g><g filter="url(#i3M8BZL)"><path stroke="url(#iSVCSBe)" class="bvi7o5-pr"/></g><g filter="url(#ihTwTGc)"><path class="heapiqb7o"/></g><g filter="url(#iQLQCmc)" class="h_1ye1b_p"><path stroke="url(#iaf2A8b)" class="aj_gv9x_w"/><path stroke="url(#iDKhboc)" class="aj_gv9x_w"/></g><g filter="url(#ikqbH6R)"><path fill="url(#ikvcdmc)" class="pj53b77_z"/></g><g filter="url(#i0WHAnc)" class="h_1ye1b_p"><path stroke="url(#itacd4d)" class="eqeyou3qk"/><path stroke="url(#igDUEfb)" class="eqeyou3qk"/></g><g filter="url(#iioDXle)"><path fill="url(#ioUqcje)" class="lpztz2bpd"/></g><path fill="url(#idIyvOE)" class="lpztz2bpd"/><path fill="url(#iCDhofc)" class="lpztz2bpd"/><path fill="url(#ilYeYhV)" class="lpztz2bpd"/><g filter="url(#iRh89qb)"><path fill="url(#iomCV1b)" class="i89ih6bux"/></g><g filter="url(#iLybn0d)"><path stroke="url(#i0lr9me)" class="phei630ry"/></g><defs><linearGradient id="i5OgAvd" x1="7.878" x2="7.878" y1="27.775" y2="30" gradientUnits="userSpaceOnUse"><stop class="b953yyb6p"/><stop offset="1" class="ylcu-sbni"/></linearGradient><linearGradient id="idNXQRd" x1="5" x2="5.731" y1="27.989" y2="27.989" gradientUnits="userSpaceOnUse"><stop class="o4-cm52qu"/><stop offset="1" class="b4kt9zb3x"/></linearGradient><linearGradient id="iRZZMjd" x1="7.144" x2="7.144" y1="30.297" y2="29.609" gradientUnits="userSpaceOnUse"><stop class="k-a0i-0hr"/><stop offset="1" class="r6eglm1rp"/></linearGradient><linearGradient id="i2d3N8d" x1="12.522" x2="12.522" y1="20.586" y2="4.884" gradientUnits="userSpaceOnUse"><stop class="drwutwk8n"/><stop offset="1" class="biy93mebn"/></linearGradient><linearGradient id="iPTCHre" x1="27" x2="26.144" y1="16.826" y2="16.826" gradientUnits="userSpaceOnUse"><stop class="ebv21eb1a"/><stop offset="1" class="wv-zehbaz"/></linearGradient><linearGradient id="i1MCzxl" x1="16" x2="16" y1="3.624" y2="4.904" gradientUnits="userSpaceOnUse"><stop offset=".3" class="mcdrc7blw"/><stop offset="1" class="gwhuu2bjm"/></linearGradient><linearGradient id="iwyyX7b" x1="25.871" x2="25.871" y1="27.778" y2="30" gradientUnits="userSpaceOnUse"><stop class="b953yyb6p"/><stop offset="1" class="ylcu-sbni"/></linearGradient><linearGradient id="iqZuSee" x1="23" x2="23.729" y1="27.992" y2="27.992" gradientUnits="userSpaceOnUse"><stop class="o4-cm52qu"/><stop offset="1" class="b4kt9zb3x"/></linearGradient><linearGradient id="iCu4Chd" x1="25.138" x2="25.138" y1="30.296" y2="29.61" gradientUnits="userSpaceOnUse"><stop class="k-a0i-0hr"/><stop offset="1" class="r6eglm1rp"/></linearGradient><linearGradient id="iKyowqQ" x1="16" x2="16" y1="24.355" y2="27" gradientUnits="userSpaceOnUse"><stop class="lkdxl0brh"/><stop offset="1" class="nrte85bat"/></linearGradient><linearGradient id="iHheWdd" x1="30.43" x2="25.458" y1="27" y2="27" gradientUnits="userSpaceOnUse"><stop class="gvntniubt"/><stop offset="1" class="frvyil58y"/></linearGradient><linearGradient id="iTAnycb" x1="5" x2="6.708" y1="27" y2="27" gradientUnits="userSpaceOnUse"><stop class="p8we0rbux"/><stop offset="1" class="jpyhojb_l"/></linearGradient><linearGradient id="iLgM8pb" x1="27" x2="28" y1="15.003" y2="15.003" gradientUnits="userSpaceOnUse"><stop class="ehr6_5zhf"/><stop offset="1" class="bxpzj8b7v"/></linearGradient><linearGradient id="i8Ajf2c" x1="27.55" x2="27.55" y1="16" y2="15.813" gradientUnits="userSpaceOnUse"><stop class="w53ij1uru"/><stop offset="1" class="c2-j6_1sg"/></linearGradient><linearGradient id="ilRTABc" x1="26.956" x2="27.136" y1="15.195" y2="15.195" gradientUnits="userSpaceOnUse"><stop class="u1qzmrn5s"/><stop offset="1" class="qo4ntbceu"/></linearGradient><linearGradient id="ibrkymd" x1="28" x2="27.745" y1="15.195" y2="15.195" gradientUnits="userSpaceOnUse"><stop class="u1qzmrn5s"/><stop offset="1" class="qo4ntbceu"/></linearGradient><linearGradient id="iryh2rc" x1="27.862" x2="27.862" y1="14.031" y2="14.195" gradientUnits="userSpaceOnUse"><stop class="vjbk5ranb"/><stop offset="1" class="ofgpdub6k"/></linearGradient><linearGradient id="i1KKtDb" x1="3" x2="4" y1="15.003" y2="15.003" gradientUnits="userSpaceOnUse"><stop class="ehr6_5zhf"/><stop offset="1" class="bxpzj8b7v"/></linearGradient><linearGradient id="ifnwycb" x1="3.55" x2="3.55" y1="16" y2="15.813" gradientUnits="userSpaceOnUse"><stop class="w53ij1uru"/><stop offset="1" class="c2-j6_1sg"/></linearGradient><linearGradient id="iLkHTNb" x1="2.956" x2="3.136" y1="15.195" y2="15.195" gradientUnits="userSpaceOnUse"><stop class="u1qzmrn5s"/><stop offset="1" class="qo4ntbceu"/></linearGradient><linearGradient id="ivkK5dc" x1="4" x2="3.745" y1="15.195" y2="15.195" gradientUnits="userSpaceOnUse"><stop class="u1qzmrn5s"/><stop offset="1" class="qo4ntbceu"/></linearGradient><linearGradient id="iOLpodP" x1="3.862" x2="3.862" y1="14.031" y2="14.195" gradientUnits="userSpaceOnUse"><stop class="vjbk5ranb"/><stop offset="1" class="ofgpdub6k"/></linearGradient><linearGradient id="ijQAoFb" x1="3.503" x2="3.503" y1="17" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="dd_np-brq"/><stop offset="1" class="hjab-zlqf"/></linearGradient><linearGradient id="iZ7jQyd" x1="3" x2="3" y1="12" y2="12.703" gradientUnits="userSpaceOnUse"><stop offset=".222" class="chhnvjbqw"/><stop offset="1" class="gzdfjub1o"/></linearGradient><linearGradient id="iRZwPtd" x1="29.503" x2="29.503" y1="17" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="dd_np-brq"/><stop offset="1" class="hjab-zlqf"/></linearGradient><linearGradient id="i0ukzNc" x1="29" x2="29" y1="12" y2="12.703" gradientUnits="userSpaceOnUse"><stop offset=".222" class="chhnvjbqw"/><stop offset="1" class="gzdfjub1o"/></linearGradient><linearGradient id="iQ4m2fd" x1="16.417" x2="16.417" y1="19.537" y2="10.213" gradientUnits="userSpaceOnUse"><stop class="owujtefmt"/><stop offset="1" class="xtbtb5izz"/></linearGradient><linearGradient id="ixdQ9sc" x1="7" x2="25" y1="14.498" y2="14.5" gradientUnits="userSpaceOnUse"><stop class="v7scl85hw"/><stop offset="1" class="yfpx07b_r"/></linearGradient><linearGradient id="iFGQx3a" x1="6.472" x2="7.472" y1="15.656" y2="15.656" gradientUnits="userSpaceOnUse"><stop class="vfrvp8eqe"/><stop offset="1" class="q357wdhqo"/></linearGradient><linearGradient id="illtnnj" x1="16" x2="16" y1="9.695" y2="12.002" gradientUnits="userSpaceOnUse"><stop offset=".159" class="nnk78sbcy"/><stop offset="1" class="dany5liim"/></linearGradient><linearGradient id="iFi0UNb" x1="16" x2="16" y1="10" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="i0oe88m0c"/><stop offset="1" class="origppbiv"/></linearGradient><linearGradient id="iN5nRGb" x1="16.185" x2="16.185" y1="23.781" y2="23.024" gradientUnits="userSpaceOnUse"><stop class="twzrd6b1c"/><stop offset="1" class="x6owwybuw"/></linearGradient><linearGradient id="iSVCSBe" x1="16.278" x2="16.278" y1="21.781" y2="21.024" gradientUnits="userSpaceOnUse"><stop class="twzrd6b1c"/><stop offset="1" class="x6owwybuw"/></linearGradient><linearGradient id="iaf2A8b" x1="7.675" x2="6.722" y1="25.141" y2="23.938" gradientUnits="userSpaceOnUse"><stop class="twzrd6b1c"/><stop offset="1" class="phxyrxzud"/></linearGradient><linearGradient id="iDKhboc" x1="6.36" x2="7.766" y1="23" y2="20.897" gradientUnits="userSpaceOnUse"><stop class="sl30-9-0s"/><stop offset="1" class="x6owwybuw"/></linearGradient><linearGradient id="ikvcdmc" x1="6.5" x2="6.5" y1="21" y2="25" gradientUnits="userSpaceOnUse"><stop class="vm3dc8m8p"/><stop offset="1" class="cse81i8zu"/></linearGradient><linearGradient id="itacd4d" x1="24.441" x2="26.001" y1="25.094" y2="23.625" gradientUnits="userSpaceOnUse"><stop class="zbpuyv_rm"/><stop offset="1" class="oepd4cc2j"/></linearGradient><linearGradient id="igDUEfb" x1="24.806" x2="26.96" y1="22.827" y2="20.719" gradientUnits="userSpaceOnUse"><stop class="b0hbe2e9p"/><stop offset="1" class="bgcorqb3k"/></linearGradient><linearGradient id="ioUqcje" x1="25.5" x2="25.5" y1="21" y2="25" gradientUnits="userSpaceOnUse"><stop class="b71idvbpx"/><stop offset="1" class="um1r83bso"/></linearGradient><linearGradient id="idIyvOE" x1="27.431" x2="26.471" y1="23.36" y2="23.36" gradientUnits="userSpaceOnUse"><stop class="b61bfmb0h"/><stop offset="1" class="ci86sseux"/></linearGradient><linearGradient id="iCDhofc" x1="25.004" x2="25.055" y1="25.433" y2="24.093" gradientUnits="userSpaceOnUse"><stop class="m-w0dia4e"/><stop offset="1" class="ki0188hyi"/></linearGradient><linearGradient id="ilYeYhV" x1="23.563" x2="25.737" y1="21" y2="23" gradientUnits="userSpaceOnUse"><stop offset=".09" class="jnsprlbqz"/><stop offset="1" class="wgorh_bif"/></linearGradient><linearGradient id="iomCV1b" x1="7" x2="24.004" y1="8.503" y2="8.503" gradientUnits="userSpaceOnUse"><stop class="dt2-hrbth"/><stop offset="1" class="tlrv9weeh"/></linearGradient><linearGradient id="i0lr9me" x1="8.179" x2="23.266" y1="18.692" y2="18.692" gradientUnits="userSpaceOnUse"><stop class="p9ef-ifzr"/><stop offset="1" class="rh0y8fg4g"/></linearGradient><filter id="i2MkMLd" width="23" height="18.556" x="5" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.980392 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9860"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.584314 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9860" result="effect2_innerShadow_18_9860"/></filter><filter id="i0C5SZb" width="22" height="8" x="5" y="19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.34902 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9860"/></filter><filter id="iMCYRVb" width="2.2" height="5.2" x="2" y="11.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.0784314 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9860"/></filter><filter id="ilPqfle" width="2.2" height="5.2" x="28" y="11.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.0784314 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9860"/></filter><filter id="iKZDswc" width="18.4" height="9.4" x="6.8" y="9.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9860" stdDeviation=".05"/></filter><filter id="iRIP0cc" width="19" height="10" x="6" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.54902 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9860"/></filter><filter id="iq4BKLe" width="8.4" height="1.4" x="11.8" y="22.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9860" stdDeviation=".05"/></filter><filter id="igzROwf" width="8" height="1.4" x="12" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9860"/></filter><filter id="i3M8BZL" width="12.4" height="1.4" x="9.8" y="20.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9860" stdDeviation=".05"/></filter><filter id="ihTwTGc" width="12" height="1.4" x="10" y="21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9860"/></filter><filter id="iQLQCmc" width="3.191" height="4.35" x="4.984" y="20.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9860" stdDeviation=".05"/></filter><filter id="ikqbH6R" width="3.5" height="4.5" x="4.5" y="21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.721569 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9860"/></filter><filter id="i0WHAnc" width="3.25" height="4.35" x="23.825" y="20.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9860" stdDeviation=".05"/></filter><filter id="iioDXle" width="3.5" height="4.5" x="24" y="21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.592157 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9860"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.694118 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9860" result="effect2_innerShadow_18_9860"/></filter><filter id="iRh89qb" width="18" height="3.15" x="7" y="6.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0509804 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9860"/></filter><filter id="iLybn0d" width="17.305" height="1.25" x="7.185" y="17.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9860" stdDeviation=".25"/></filter><radialGradient id="ieEL9ce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.15815 12.6696 0 14.05 21.556)" gradientUnits="userSpaceOnUse"><stop class="d1e5c8h4k"/><stop offset="1" class="z0n8m4jnx"/></radialGradient><radialGradient id="ifgseKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.0625 7.0625 0 19.19 21.25)" gradientUnits="userSpaceOnUse"><stop class="j8l0cjz9u"/><stop offset="1" class="z4-4z88ew"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oncoming-bus" /></template>
<style>
.a5tzb62_e {
  d: path("M28.78 17h.44c.43 0 .78-.35.78-.78v-3.44c0-.43-.35-.78-.78-.78h-.44c-.43 0-.78.35-.78.78v3.44c0 .43.35.78.78.78");
}

.aj_gv9x_w {
  d: path("M8 22c0-.55-.426-1-.947-1H5.159v4h1.894c.52 0 .947-.45.947-1z");
}

.b0hbe2e9p {
  stop-color: var(--svg-color--8e5d32, #8E5D32);
  stop-opacity: 0;
}

.b4kt9zb3x {
  stop-color: var(--svg-color--453e52, #453E52);
  stop-opacity: 0;
}

.b61bfmb0h {
  stop-color: var(--svg-color--ccc0cd, #CCC0CD);
}

.b71idvbpx {
  stop-color: var(--svg-color--b1a2b4, #B1A2B4);
}

.b953yyb6p {
  stop-color: var(--svg-color--260e3b, #260E3B);
}

.bgcorqb3k {
  stop-color: var(--svg-color--8e5d32, #8E5D32);
}

.biy93mebn {
  stop-color: var(--svg-color--d8d4dd, #D8D4DD);
}

.bvi7o5-pr {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.5 22h-11c-.28 0-.5-.22-.5-.5c0-.27.22-.5.5-.5h11c.28 0 .5.22.5.5s-.22.5-.5.5Z");
}

.bxpzj8b7v {
  stop-color: var(--svg-color--32293e, #32293E);
}

.c2-j6_1sg {
  stop-color: var(--svg-color--1e0e2d, #1E0E2D);
  stop-opacity: 0;
}

.chhnvjbqw {
  stop-color: var(--svg-color--4c4457, #4C4457);
}

.ci86sseux {
  stop-color: var(--svg-color--ccc0cd, #CCC0CD);
  stop-opacity: 0;
}

.cposyecbc {
  d: path("M2.78 17h.44c.43 0 .78-.35.78-.78v-3.44c0-.43-.35-.78-.78-.78h-.44c-.43 0-.78.35-.78.78v3.44c0 .43.35.78.78.78");
}

.cse81i8zu {
  stop-color: var(--svg-color--f3f0e9, #F3F0E9);
}

.d1e5c8h4k {
  stop-color: var(--svg-color--c7bed2, #C7BED2);
}

.dany5liim {
  stop-color: var(--svg-color--144e97, #144E97);
  stop-opacity: 0;
}

.dd_np-brq {
  stop-color: var(--svg-color--2b2533, #2B2533);
}

.dqy90wtiv {
  d: path("M24.01 19H7.99c-.55 0-.99-.45-.99-.99V10h18v8.01c0 .54-.44.99-.99.99");
}

.drwutwk8n {
  stop-color: var(--svg-color--b3aabc, #B3AABC);
}

.dt2-hrbth {
  stop-color: var(--svg-color--2b2731, #2B2731);
}

.ebv21eb1a {
  stop-color: var(--svg-color--b8b6bb, #B8B6BB);
}

.ehr6_5zhf {
  stop-color: var(--svg-color--302a3a, #302A3A);
}

.eqeyou3qk {
  d: path("M24 24c0 .55.435 1 .966 1H26.9v-4h-1.933c-.532 0-.967.45-.967 1z");
}

.frvyil58y {
  stop-color: var(--svg-color--98732c, #98732C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gvntniubt {
  stop-color: var(--svg-color--98732c, #98732C);
}

.gwhuu2bjm {
  stop-color: var(--svg-color--fafafa, #FAFAFA);
  stop-opacity: 0;
}

.gzdfjub1o {
  stop-color: var(--svg-color--4c4457, #4C4457);
  stop-opacity: 0;
}

.h_1ye1b_p {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.heapiqb7o {
  fill: var(--svg-color--656466, #656466);
  d: path("M21.5 22h-11c-.28 0-.5-.22-.5-.5c0-.27.22-.5.5-.5h11c.28 0 .5.22.5.5s-.22.5-.5.5");
}

.hjab-zlqf {
  stop-color: var(--svg-color--342943, #342943);
}

.i0oe88m0c {
  stop-color: var(--svg-color--1f53a9, #1F53A9);
}

.i89ih6bux {
  d: path("M25 10H7V7.99c0-.55.44-.99.99-.99h16.03c.54 0 .98.44.98.99z");
}

.itcuebc2u {
  d: path("M23.59 4H8.41C6.52 4 5 5.47 5 7.29v14.266h22V7.29C27 5.47 25.48 4 23.59 4");
}

.j8l0cjz9u {
  stop-color: var(--svg-color--3acafc, #3ACAFC);
}

.jnsprlbqz {
  stop-color: var(--svg-color--b3a1b8, #B3A1B8);
}

.jpyhojb_l {
  stop-color: var(--svg-color--c6a860, #C6A860);
  stop-opacity: 0;
}

.k-a0i-0hr {
  stop-color: var(--svg-color--602c86, #602C86);
}

.ki0188hyi {
  stop-color: var(--svg-color--ede8e2, #EDE8E2);
  stop-opacity: 0;
}

.lkdxl0brh {
  stop-color: var(--svg-color--f6c34a, #F6C34A);
}

.lpztz2bpd {
  d: path("M24 24c0 .55.45 1 1 1h2v-4h-2c-.55 0-1 .45-1 1z");
}

.m-w0dia4e {
  stop-color: var(--svg-color--ede8e2, #EDE8E2);
}

.mcdrc7blw {
  stop-color: var(--svg-color--fafafa, #FAFAFA);
}

.mou24-q5s {
  d: path("M26.06 30h-2.11c-.53 0-.95-.42-.95-.94v-4.11c0-.52.42-.94.94-.94h2.11c.52 0 .94.42.94.94v4.11c.01.52-.41.94-.93.94");
}

.nnk78sbcy {
  stop-color: var(--svg-color--144e97, #144E97);
}

.nrte85bat {
  stop-color: var(--svg-color--d99d43, #D99D43);
}

.o4-cm52qu {
  stop-color: var(--svg-color--453e52, #453E52);
}

.oepd4cc2j {
  stop-color: var(--svg-color--f4c86e, #F4C86E);
  stop-opacity: 0;
}

.ofgpdub6k {
  stop-color: var(--svg-color--4c4656, #4C4656);
  stop-opacity: 0;
}

.origppbiv {
  stop-color: var(--svg-color--1e53aa, #1E53AA);
  stop-opacity: 0;
}

.owujtefmt {
  stop-color: var(--svg-color--dfdde3, #DFDDE3);
}

.p8we0rbux {
  stop-color: var(--svg-color--c6a860, #C6A860);
}

.p9ef-ifzr {
  stop-color: var(--svg-color--4ab8ff, #4AB8FF);
}

.phei630ry {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.81 18.138h16.056");
}

.phxyrxzud {
  stop-color: var(--svg-color--ffde69, #FFDE69);
  stop-opacity: 0;
}

.pj53b77_z {
  d: path("M8 22c0-.55-.45-1-1-1H5v4h2c.55 0 1-.45 1-1z");
}

.q357wdhqo {
  stop-color: var(--svg-color--0787e1, #0787E1);
  stop-opacity: 0;
}

.qo4ntbceu {
  stop-color: var(--svg-color--271e33, #271E33);
  stop-opacity: 0;
}

.qq9vw43od {
  d: path("M5 20v5.58c0 .79.64 1.42 1.42 1.42h19.16c.78 0 1.42-.63 1.42-1.42V20z");
}

.r6eglm1rp {
  stop-color: var(--svg-color--602c86, #602C86);
  stop-opacity: 0;
}

.rh0y8fg4g {
  stop-color: var(--svg-color--50cefc, #50CEFC);
}

.sl30-9-0s {
  stop-color: var(--svg-color--ca9049, #CA9049);
  stop-opacity: 0;
}

.tlrv9weeh {
  stop-color: var(--svg-color--362a46, #362A46);
}

.twzrd6b1c {
  stop-color: var(--svg-color--ffde69, #FFDE69);
}

.tyim3vbao {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.5 24h-7c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h7c.28 0 .5.22.5.5s-.22.5-.5.5Z");
}

.u_w_x8bga {
  fill: var(--svg-color--656466, #656466);
  d: path("M19.5 24h-7c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h7c.28 0 .5.22.5.5s-.22.5-.5.5");
}

.u1qzmrn5s {
  stop-color: var(--svg-color--271e33, #271E33);
}

.um1r83bso {
  stop-color: var(--svg-color--ebe7e2, #EBE7E2);
}

.uz4v66b9d {
  d: path("M8.06 30H5.94c-.52 0-.94-.42-.94-.94v-4.11c0-.52.42-.95.94-.95h2.11c.53 0 .95.43.95.95v4.11c0 .52-.42.94-.94.94");
}

.v4edsdbor {
  d: path("M27 16h2v-2h-2z");
}

.v7scl85hw {
  stop-color: var(--svg-color--2a99f1, #2A99F1);
}

.vfrvp8eqe {
  stop-color: var(--svg-color--0787e1, #0787E1);
}

.vjbk5ranb {
  stop-color: var(--svg-color--4c4656, #4C4656);
}

.vm3dc8m8p {
  stop-color: var(--svg-color--beb0bf, #BEB0BF);
}

.w53ij1uru {
  stop-color: var(--svg-color--1e0e2d, #1E0E2D);
}

.wgorh_bif {
  stop-color: var(--svg-color--b3a1b8, #B3A1B8);
  stop-opacity: 0;
}

.wv-zehbaz {
  stop-color: var(--svg-color--bab7bd, #BAB7BD);
  stop-opacity: 0;
}

.x6owwybuw {
  stop-color: var(--svg-color--ca9049, #CA9049);
}

.xtbtb5izz {
  stop-color: var(--svg-color--dfdde3, #DFDDE3);
  stop-opacity: 0;
}

.xz75nk1_k {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M24.01 19H7.99c-.55 0-.99-.45-.99-.99V10h18v8.01c0 .54-.44.99-.99.99Z");
}

.yfpx07b_r {
  stop-color: var(--svg-color--41b0e5, #41B0E5);
}

.yh0lhc3ie {
  d: path("M5 14H3v2h2z");
}

.ylcu-sbni {
  stop-color: var(--svg-color--401361, #401361);
}

.z0n8m4jnx {
  stop-color: var(--svg-color--c7bed2, #C7BED2);
  stop-opacity: 0;
}

.z4-4z88ew {
  stop-color: var(--svg-color--3acafc, #3ACAFC);
  stop-opacity: 0;
}

.zbpuyv_rm {
  stop-color: var(--svg-color--f4c86e, #F4C86E);
}

</style>
