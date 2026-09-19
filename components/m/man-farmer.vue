<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ibyunQb)" class="g5g5_ccex"/><path fill="url(#ij9QFBe)" class="tkpjnib0w"/><path fill="url(#ixeWGJb)" class="tkpjnib0w"/><g filter="url(#i3yexcb)"><path fill="url(#iFeXpQd)" class="shtjutbna"/><path fill="url(#ix36RWc)" class="shtjutbna"/></g><path class="d3j40lb9a"/><path fill="url(#iUk8kMh)" class="okpg_tb3s"/><path fill="url(#ijSlXui)" class="ttginrqzc"/><path fill="url(#iE14WHb)" class="ttginrqzc"/><path fill="url(#iaOXYOc)" class="n14mmkbvj"/><path fill="url(#iJlK1gb)" class="n14mmkbvj"/><g filter="url(#iqPdpPd)"><path fill="url(#i6bY5kb)" class="lxkbubrzd"/><path fill="url(#iOIpW3d)" class="lxkbubrzd"/><path fill="url(#igShF8c)" class="lxkbubrzd"/></g><path fill="url(#iZB5Nle)" class="lxkbubrzd"/><path fill="url(#igmJiNd)" class="lxkbubrzd"/><path fill="url(#iCagjAC)" class="u6kiehv-f"/><path fill="url(#iy3VLZd)" class="ih7yjybap"/><path fill="url(#i3wB8Ev)" class="ih7yjybap"/><path fill="url(#iJh5G3l)" class="varca-bcz"/><g filter="url(#iBUE6Ld)"><path class="yofl1erhy"/></g><g filter="url(#iuYdxtj)"><path fill="url(#incyNLb)" class="rm70xxj2b"/><path fill="url(#iuiRl2b)" class="rm70xxj2b"/></g><g filter="url(#i3aiFyb)"><path class="i23o_5b4n"/><path fill="url(#iImBbUb)" class="ii3vlubko"/><path fill="url(#isveqtd)" class="ii3vlubko"/></g><path fill="url(#iapBWIb)" class="tbfm_db-e"/><path fill="url(#iJs708d)" class="tbfm_db-e"/><path fill="url(#i6d1bQc)" class="f8k-7ysnu"/><path fill="url(#izoS0Bb)" class="f8k-7ysnu"/><path fill="url(#iTklm1Q)" class="ed-_1nbwe"/><path fill="url(#i2Cy5md)" class="ed-_1nbwe"/><path fill="url(#iZpHEjv)" class="ed-_1nbwe"/><path fill="url(#iXHI9De)" class="ed-_1nbwe"/><path fill="url(#i8YGcde)" class="ed-_1nbwe"/><g filter="url(#iq1Oloc)"><path class="lbgxku_tn"/></g><g filter="url(#iGp528c)"><path fill="url(#irsSoRj)" class="v9udbt8po"/></g><g filter="url(#iBzZbHt)"><path fill="url(#i7HrTje)" class="nl8u09oql"/></g><path fill="url(#ivQHUvq)" class="nl8u09oql"/><path fill="url(#ihYVqPT)" class="nl8u09oql"/><path fill="url(#ifCEUNe)" class="nl8u09oql"/><g filter="url(#iNKWCOc)"><path class="ynfo-lk5x"/></g><g filter="url(#ikLhwIe)"><path class="yidmhu6xw"/><path fill="url(#iKAmL4d)" class="scw4plmtu"/><path fill="url(#iX8Xivr)" class="scw4plmtu"/><path fill="url(#i0cTrmJ)" class="scw4plmtu"/></g><path fill="url(#i8ucsye)" class="scw4plmtu"/><g filter="url(#ityrzmb)"><path stroke="url(#iLXejVd)" class="wrx6pfbnu"/></g><path class="yt-8axwmn"/><path fill="url(#ixFFWbc)" class="bvtonq6lk"/><path fill="url(#ibW4FZd)" class="bvtonq6lk"/><path fill="url(#iZLLtFd)" class="bvtonq6lk"/><path fill="url(#i7sLIOd)" class="ci74o-q2a"/><path fill="url(#i8tC9fD)" class="ci74o-q2a"/><path fill="url(#iogHfjM)" class="zhkis3bpm"/><path fill="url(#ie4eCEe)" class="zhkis3bpm"/><path fill="url(#ih9PXOc)" class="zhkis3bpm"/><g filter="url(#iT1wu4d)"><path class="bjx9jjb2h"/></g><path class="ek0q_4ubo"/><path fill="url(#ieYxzAd)" class="hnjx_kyri"/><path class="q39-2-sga"/><g filter="url(#inrNlTb)"><path class="ubkt_lbza"/><path fill="url(#iaVBvad)" class="nb3f2vhac"/></g><g filter="url(#iiVfYHe)"><path fill="url(#iNEvqyb)" class="e5-w0m04u"/></g><path class="n_7gbriho"/><path fill="url(#ic0lQkc)" class="v83zxobbg"/><path class="ox1nctxqu"/><g filter="url(#iqIj0Fc)"><path fill="url(#iJphPLb)" class="mvtrlk78b"/></g><g filter="url(#iDIkBCb)"><ellipse transform="rotate(-27.914 12.722 9.883)" class="l167bxb6u"/><ellipse fill="url(#iCdQAOe)" transform="rotate(-27.914 12.722 9.883)" class="hcefr617c"/></g><g filter="url(#inRmCgc)"><path fill="url(#idiMSAb)" class="a-o4_l0ya"/><path fill="url(#ipEvPqc)" class="a-o4_l0ya"/><path fill="url(#iEdeRQb)" class="a-o4_l0ya"/><path fill="url(#iHZi9Ef)" class="a-o4_l0ya"/><path fill="url(#itkFtdd)" class="a-o4_l0ya"/></g><g filter="url(#iLiQy1b)"><path stroke="url(#imtbMKd)" class="o3vceabcc"/></g><g filter="url(#ivoWsJZ)"><path stroke="url(#iVEeu2d)" class="lod-pubnh"/></g><g filter="url(#iyWDtYN)"><path stroke="url(#iiGIjFe)" class="ouqevybdq"/></g><g filter="url(#iBYCTqe)"><path clip-rule="evenodd" class="t38a-jd3s"/></g><g filter="url(#iHHXfue)"><path clip-rule="evenodd" class="bh2m3ivdl"/></g><g filter="url(#ioIfdSd)"><path stroke="url(#iVvpq8b)" class="p2sp74idh"/></g><g filter="url(#iAMQdmc)"><path stroke="url(#i1HaBlc)" class="odoauw8ii"/></g><defs><radialGradient id="ibyunQb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.03 3.97)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="ij9QFBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 18.904 5.132)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="ix36RWc" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.22 4.17)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="iUk8kMh" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.14 16.295)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="iE14WHb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 2.998 25.257)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="iJlK1gb" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.17 24.72)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="i6bY5kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 15.21 16.163)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="igShF8c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 14.356 19.561)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="igmJiNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 14.604 15.98)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iCagjAC" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.13 19.662)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iy3VLZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.43272 -4.29817 0 15.819 16.585)" gradientUnits="userSpaceOnUse"><stop class="vooh3tegw"/><stop offset="1" class="xlyybr0fb"/></radialGradient><radialGradient id="i3wB8Ev" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.38565 -2.76771 0 15.14 15.34)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="bnge9kbad"/><stop offset="1" class="aum_h2loy"/></radialGradient><radialGradient id="iJh5G3l" cx="0" cy="0" r="1" gradientTransform="matrix(1.75543 0 0 3.07202 8.57 10.6)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iuiRl2b" cx="0" cy="0" r="1" gradientTransform="matrix(.82697 -.60216 .6873 .94388 20.403 10.335)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iImBbUb" cx="0" cy="0" r="1" gradientTransform="matrix(.96029 -1.76625 1.03379 .56206 19.982 11.56)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="isveqtd" cx="0" cy="0" r="1" gradientTransform="matrix(.30318 .3001 -.38688 .39084 20.03 10.6)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iapBWIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03903 -.98438 2.30833 2.4365 19.61 8.46)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="m6onrbbbm"/><stop offset=".879" class="srlhzqudp"/></radialGradient><radialGradient id="iJs708d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94487 -3.41373 0 20.267 8.317)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="pc4aesbtv"/><stop offset="1" class="w2csk89pk"/></radialGradient><radialGradient id="i6d1bQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1641 -.71876 1.18661 -1.92181 10.812 8.788)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="vwg1f_bua"/><stop offset="1" class="n8a3-cbkw"/></radialGradient><radialGradient id="izoS0Bb" cx="0" cy="0" r="1" gradientTransform="rotate(93.18 .98 9.55)scale(1.6901 .72718)" gradientUnits="userSpaceOnUse"><stop offset=".445" class="q8qs28dhk"/><stop offset="1" class="acg6vzboz"/></radialGradient><radialGradient id="i2Cy5md" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.135 11.699)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="i8YGcde" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90625 3.00378 3.94458 8.15 18.82)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="i7HrTje" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9544 1.19435 -2.01845 -10.06296 18.662 10.391)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="ivQHUvq" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13592 1.13266 0 13.306 9.663)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="f4d_slbvt"/><stop offset="1" class="mjltbqb6d"/></radialGradient><radialGradient id="ihYVqPT" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31725 1.46187 0 17.638 9.741)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="qtwfj5bch"/><stop offset="1" class="wtzd4lbuc"/></radialGradient><radialGradient id="ifCEUNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.73704 -10.9444 0 15.21 8.469)" gradientUnits="userSpaceOnUse"><stop offset=".582" class="ba9c-9ben"/><stop offset="1" class="y_r2qxwfl"/></radialGradient><radialGradient id="iLXejVd" cx="0" cy="0" r="1" gradientTransform="matrix(.28922 -.7681 1.9316 .72733 14.189 14.31)" gradientUnits="userSpaceOnUse"><stop class="f71zwr8du"/><stop offset="1" class="yxjq9v5jp"/></radialGradient><radialGradient id="ixFFWbc" cx="0" cy="0" r="1" gradientTransform="rotate(137.811 8.927 17.036)scale(1.65559 1.3064)" gradientUnits="userSpaceOnUse"><stop class="rht-9g91b"/><stop offset="1" class="fk-65dr-t"/></radialGradient><radialGradient id="ibW4FZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45313 1.43733 0 25.366 25.163)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="ap8mygb2m"/><stop offset="1" class="qayu9abrk"/></radialGradient><radialGradient id="iZLLtFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79687 0 0 -3.09375 26.678 24.538)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="nb-_v43xz"/><stop offset=".922" class="ugwoxpb1x"/></radialGradient><radialGradient id="i8tC9fD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 25.324 24.78)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iogHfjM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 25.347 21.6)" gradientUnits="userSpaceOnUse"><stop class="vwnwx2byo"/><stop offset="1" class="vzaknebes"/></radialGradient><radialGradient id="ie4eCEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 24.85 21.983)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="gr2susb2n"/><stop offset="1" class="vnxqexb9a"/></radialGradient><radialGradient id="ieYxzAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82316 -1.30932 0 17.424 9.98)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iaVBvad" cx="0" cy="0" r="1" gradientTransform="matrix(-.2353 -.30322 .41746 -.32395 17.193 10.065)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ic0lQkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8232 -1.30939 0 12.997 9.98)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iCdQAOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00785 -.5013 .60257 -.00943 12.706 10.202)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipEvPqc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 26.983 24.584)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="iEdeRQb" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 22.851 25.96)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iHZi9Ef" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 22.665 27.287)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="itkFtdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 22.57 28.554)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><linearGradient id="ixeWGJb" x1="15.131" x2="15.131" y1="4.02" y2="4.073" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="iFeXpQd" x1="15.211" x2="15.211" y1="4.819" y2="14.851" gradientUnits="userSpaceOnUse"><stop class="ht4fz-b9x"/><stop offset="1" class="rk4knin1y"/></linearGradient><linearGradient id="ijSlXui" x1="8.151" x2="4.56" y1="28.444" y2="28.444" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iaOXYOc" x1="25.713" x2="22.171" y1="22.874" y2="29.18" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="iOIpW3d" x1="19.211" x2="18.276" y1="18.507" y2="18.507" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="iZB5Nle" x1="11.211" x2="11.545" y1="18.507" y2="18.507" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="incyNLb" x1="21.117" x2="20.299" y1="9.508" y2="12.045" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iTklm1Q" x1="16.373" x2="15.161" y1="29.132" y2="22.007" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="iZpHEjv" x1="22.224" x2="21.998" y1="29.663" y2="29.663" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iXHI9De" x1="8.151" x2="8.275" y1="29.663" y2="29.663" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="irsSoRj" x1="12.998" x2="19.529" y1="28.351" y2="28.351" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="iKAmL4d" x1="14.349" x2="15.284" y1="11.66" y2="11.66" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iX8Xivr" x1="16.146" x2="15.124" y1="11.984" y2="11.97" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="i0cTrmJ" x1="15.405" x2="15.405" y1="12.73" y2="12.154" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="i8ucsye" x1="15.336" x2="15.336" y1="12.772" y2="12.604" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="i7sLIOd" x1="24.821" x2="24.821" y1="21.601" y2="24.78" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="ih9PXOc" x1="24.849" x2="24.849" y1="22.304" y2="21.71" gradientUnits="userSpaceOnUse"><stop class="tun7z-ngg"/><stop offset="1" class="z3nh0_7nl"/></linearGradient><linearGradient id="iNEvqyb" x1="18.214" x2="17.895" y1="10.034" y2="10.23" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJphPLb" x1="13.752" x2="13.433" y1="10.034" y2="10.231" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idiMSAb" x1="26.693" x2="22.665" y1="28.052" y2="28.052" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="imtbMKd" x1="24.866" x2="23.03" y1="25.968" y2="25.968" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="iVEeu2d" x1="24.788" x2="22.952" y1="27.273" y2="27.273" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="iiGIjFe" x1="24.866" x2="23.03" y1="28.577" y2="28.577" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="iVvpq8b" x1="18.476" x2="16.304" y1="8.163" y2="7.784" gradientUnits="userSpaceOnUse"><stop class="ir7sbob7a"/><stop offset="1" class="bvhzavbph"/></linearGradient><linearGradient id="i1HaBlc" x1="11.928" x2="14.773" y1="8.163" y2="7.784" gradientUnits="userSpaceOnUse"><stop class="ir7sbob7a"/><stop offset="1" class="bvhzavbph"/></linearGradient><filter id="i3yexcb" width="20.537" height="10.328" x="4.692" y="4.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1800"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1800" result="effect2_innerShadow_4002_1800"/></filter><filter id="iqPdpPd" width="8" height="6.44" x="11.211" y="15.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1800"/></filter><filter id="iBUE6Ld" width="3.24" height="3.24" x="8.621" y="8.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".25"/></filter><filter id="iuYdxtj" width="3.59" height="3.59" x="18.361" y="8.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1800"/></filter><filter id="i3aiFyb" width="3.327" height="3.327" x="18.367" y="8.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".25"/></filter><filter id="iq1Oloc" width="8.45" height="4.612" x="10.941" y="25.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".125"/></filter><filter id="iGp528c" width="8.05" height="4.28" x="11.091" y="25.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1800"/></filter><filter id="iBzZbHt" width="10.66" height="10.004" x="10.131" y="6.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1800"/></filter><filter id="iNKWCOc" width="3.371" height="4.195" x="13.332" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".375"/></filter><filter id="ikLhwIe" width="2.371" height="3.195" x="14.025" y="9.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".125"/></filter><filter id="ityrzmb" width="3.833" height="1.572" x="13.234" y="13.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".05"/></filter><filter id="iT1wu4d" width="7.625" height="9.853" x="21.064" y="10.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.490196 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1800"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.788235 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1800" result="effect2_innerShadow_4002_1800"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.552941 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1800" result="effect3_innerShadow_4002_1800"/></filter><filter id="inrNlTb" width=".795" height=".703" x="16.681" y="9.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".05"/></filter><filter id="iiVfYHe" width=".898" height=".921" x="17.535" y="9.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".1"/></filter><filter id="iqIj0Fc" width=".995" height="1.05" x="13.027" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".1"/></filter><filter id="iDIkBCb" width=".923" height=".712" x="12.26" y="9.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".05"/></filter><filter id="inRmCgc" width="4.618" height="5.556" x="22.665" y="24.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1800"/></filter><filter id="iLiQy1b" width="2.047" height=".25" x="23.06" y="25.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".05"/></filter><filter id="ivoWsJZ" width="2.047" height=".25" x="22.982" y="27.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".05"/></filter><filter id="iyWDtYN" width="2.047" height=".25" x="23.06" y="28.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".05"/></filter><filter id="iBYCTqe" width="2.573" height="1.518" x="11.344" y="7.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.620016 0 0 0 0 0.227137 0 0 0 0 0.093707 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1800"/></filter><filter id="iHHXfue" width="2.573" height="1.518" x="16.504" y="7.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.620016 0 0 0 0 0.227137 0 0 0 0 0.093707 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1800"/></filter><filter id="ioIfdSd" width="2.523" height="1.268" x="16.57" y="7.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".15"/></filter><filter id="iAMQdmc" width="2.523" height="1.268" x="11.31" y="7.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1800" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-farmer" /></template>
<style>
.a-o4_l0ya {
  d: path("M22.665 25.316a.73.73 0 0 1 .727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.acg6vzboz {
  stop-color: var(--svg-color--c25400, #C25400);
  stop-opacity: 0;
}

.ap8mygb2m {
  stop-color: var(--svg-color--cf9826, #CF9826);
}

.aum_h2loy {
  stop-color: var(--svg-color--9a6904, #9A6904);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.ba9c-9ben {
  stop-color: var(--svg-color--f99e3c, #F99E3C);
  stop-opacity: 0;
}

.bh2m3ivdl {
  fill: var(--svg-color--b14424, #B14424);
  fill-rule: evenodd;
  d: path("M18.36 8.678a.425.425 0 0 0 .588-.614c-.494.51 0 0 0 0l-.002-.001l-.001-.002l-.004-.004l-.01-.01a1 1 0 0 0-.144-.113a2.3 2.3 0 0 0-.403-.227a2.85 2.85 0 0 0-1.505-.208a.425.425 0 0 0 .1.844c.477-.056.83.04 1.06.141a1.5 1.5 0 0 1 .312.186z");
}

.bjx9jjb2h {
  fill: var(--svg-color--c7b3db, #C7B3DB);
  d: path("M21.966 11.054a.6.6 0 0 0-.602.601v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.852a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.6.6 0 0 0-.601-.601");
}

.bnge9kbad {
  stop-color: var(--svg-color--9a6904, #9A6904);
  stop-opacity: 0;
}

.bvhzavbph {
  stop-color: var(--svg-color--cb6e5a, #CB6E5A);
  stop-opacity: 0;
}

.bvtonq6lk {
  d: path("M25.983 23.13c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.ci74o-q2a {
  d: path("M25.324 21.78h-1v3h1z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d3j40lb9a {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.14 15.51c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.e5-w0m04u {
  d: path("M18.233 10.282a.85.85 0 0 0-.235-.47l-.263.29l.119.231z");
}

.ed-_1nbwe {
  d: path("M22.17 18.05c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.ek0q_4ubo {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.637 9.22c.662 0 1.222.457 1.374 1.074a.278.278 0 0 1-.271.346h-2.264a.234.234 0 0 1-.23-.276c.127-.65.7-1.144 1.39-1.144");
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f4d_slbvt {
  stop-color: var(--svg-color--f59732, #F59732);
}

.f71zwr8du {
  stop-color: var(--svg-color--ffb032, #FFB032);
}

.f8k-7ysnu {
  d: path("M9.719 7.73c.418-.64 1.996-.738 2.566-.738l-1.727 3.18h-.53c-.176 0-.349-.075-.432-.23c-.286-.528-.438-1.467.123-2.211");
}

.fk-65dr-t {
  stop-color: var(--svg-color--ffca2c, #FFCA2C);
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.g5g5_ccex {
  d: path("M21.13 5.92h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gr2susb2n {
  stop-color: var(--svg-color--947ca9, #947CA9);
  stop-opacity: 0;
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h3q0cq17v {
  stop-color: var(--svg-color--3560c5, #3560C5);
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.hcefr617c {
  cx: 12.722px;
  cy: 9.883px;
  rx: 0.395px;
  ry: 0.2px;
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hnjx_kyri {
  d: path("M17.427 9.496a.905.905 0 0 1 .872 1.144h-1.75a.91.91 0 0 1 .877-1.144");
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.ht4fz-b9x {
  stop-color: var(--svg-color--6a3d3e, #6A3D3E);
}

.i23o_5b4n {
  fill: var(--svg-color--ffbf34, #FFBF34);
  d: path("M20.03 11.763a1.163 1.163 0 1 0 0-2.326a1.163 1.163 0 0 0 0 2.326");
}

.ih7yjybap {
  d: path("M15.14 18.68c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.ii3vlubko {
  d: path("M20.03 11.763a1.163 1.163 0 1 0 0-2.326a1.163 1.163 0 0 0 0 2.326");
}

.ir7sbob7a {
  stop-color: var(--svg-color--cb6e5a, #CB6E5A);
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kehse99iu {
  stop-color: var(--svg-color--389dff, #389DFF);
}

.l167bxb6u {
  cx: 12.722px;
  cy: 9.883px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lbgxku_tn {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M18.63 25.82h-6.94a.49.49 0 0 0-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lod-pubnh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.107 27.273h1.797");
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lxkbubrzd {
  d: path("m12.175 21.484l3.036-2.124l2.987 2.084c.42.325 1.013.465 1.013-.354v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.691c0 .953.594.823.964.563");
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m6onrbbbm {
  stop-color: var(--svg-color--ee8a19, #EE8A19);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjltbqb6d {
  stop-color: var(--svg-color--f59732, #F59732);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mvtrlk78b {
  d: path("M13.822 10.295c0-.293-.238-.488-.302-.547l-.293.283l.18.367z");
}

.n_7gbriho {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.785 9.22c-.663 0-1.223.457-1.375 1.074a.278.278 0 0 0 .272.346h2.264a.233.233 0 0 0 .23-.276a1.42 1.42 0 0 0-1.391-1.144");
}

.n14mmkbvj {
  d: path("M22.17 29.99V18.02h.007a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.n8a3-cbkw {
  stop-color: var(--svg-color--d48732, #D48732);
}

.nb-_v43xz {
  stop-color: var(--svg-color--cd9d3e, #CD9D3E);
  stop-opacity: 0;
}

.nb3f2vhac {
  d: path("M17.36 9.687c.064.086-.07.192-.224.306c-.153.115-.267.196-.331.11c-.065-.087.007-.25.16-.365c.154-.114.33-.137.395-.05");
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.nl8u09oql {
  d: path("M18.293 6.992h-6.168c-1.128 0-2.086 1.008-1.987 2.126l.184 4.942c.168 1.71 1.532 2.936 3.193 2.936h3.394c1.661 0 3.026-1.226 3.194-2.936l.187-5.04c.04-1.078-.91-2.028-1.997-2.028");
}

.o3vceabcc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.185 25.968h1.797");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odoauw8ii {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.71 8.252s.601-.581 1.724-.448");
}

.okpg_tb3s {
  d: path("M15.14 15.51c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.ouqevybdq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.185 28.577h1.797");
}

.ox1nctxqu {
  fill: var(--svg-color--000, #000);
  d: path("M13.513 10.401a.516.516 0 0 0-.518-.518a.516.516 0 0 0-.461.757h.918a.5.5 0 0 0 .061-.239");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p2sp74idh {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.694 8.252s-.601-.581-1.724-.448");
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pc4aesbtv {
  stop-color: var(--svg-color--e27d14, #E27D14);
  stop-opacity: 0;
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.q39-2-sga {
  fill: var(--svg-color--000, #000);
  d: path("M16.908 10.401c0-.288.23-.518.518-.518a.516.516 0 0 1 .462.757h-.918a.47.47 0 0 1-.062-.239");
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.q8qs28dhk {
  stop-color: var(--svg-color--c25400, #C25400);
}

.qayu9abrk {
  stop-color: var(--svg-color--cf9826, #CF9826);
  stop-opacity: 0;
}

.qtwfj5bch {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rht-9g91b {
  stop-color: var(--svg-color--ffd740, #FFD740);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rk4knin1y {
  stop-color: var(--svg-color--6e4e4c, #6E4E4C);
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rm70xxj2b {
  d: path("M20.03 12.27a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.scw4plmtu {
  d: path("m14.83 10.32l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.shtjutbna {
  d: path("M10.774 4.82c-.849.03-2.678.228-4.101 1.335c-1.238.963-1.477 2.117-1.477 3.086v.477c-.094 1.781 1.445 4.93 6.883 4.93h6.264c5.437 0 6.976-3.149 6.883-4.93V9.24c0-.969-.24-2.123-1.477-3.086c-1.424-1.107-3.253-1.304-4.102-1.336z");
}

.srlhzqudp {
  stop-color: var(--svg-color--ffca2f, #FFCA2F);
}

.t38a-jd3s {
  fill: var(--svg-color--b14424, #B14424);
  fill-rule: evenodd;
  d: path("M12.061 8.678a.425.425 0 0 1-.587-.614l.295.305l-.295-.305l.001-.001l.002-.002l.004-.004l.01-.01a1 1 0 0 1 .144-.113a2.3 2.3 0 0 1 .403-.227a2.85 2.85 0 0 1 1.504-.208a.425.425 0 0 1-.1.844a2 2 0 0 0-1.06.141a1.5 1.5 0 0 0-.312.186z");
}

.tbfm_db-e {
  d: path("M20.703 7.73c-.418-.64-1.996-.738-2.566-.738l1.726 3.18h.53c.177 0 .349-.075.433-.23c.285-.528.438-1.467-.123-2.211");
}

.tkpjnib0w {
  d: path("m9.31 5.56l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.ttginrqzc {
  d: path("M8.15 29.99V18.02h-.006a10.95 10.95 0 0 0-3.993 8.47v3.5z");
}

.tun7z-ngg {
  stop-color: var(--svg-color--9e83be, #9E83BE);
}

.u6kiehv-f {
  d: path("m16.06 19.7l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.ubkt_lbza {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.36 9.687c.064.086-.07.192-.224.306c-.153.115-.267.196-.331.11c-.065-.087.007-.25.16-.365c.154-.114.33-.137.395-.05");
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.ugwoxpb1x {
  stop-color: var(--svg-color--cd9d3e, #CD9D3E);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v83zxobbg {
  d: path("M12.995 9.496a.906.906 0 0 0-.873 1.144h1.75a1 1 0 0 0 .032-.239a.91.91 0 0 0-.91-.905");
}

.v9udbt8po {
  d: path("M18.63 25.82h-6.94c-.28 0-.5.22-.5.5V30h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.varca-bcz {
  d: path("M10.24 12.27a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.vnxqexb9a {
  stop-color: var(--svg-color--947ca9, #947CA9);
}

.vooh3tegw {
  stop-color: var(--svg-color--cd8a31, #CD8A31);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.vwg1f_bua {
  stop-color: var(--svg-color--f18026, #F18026);
}

.vwnwx2byo {
  stop-color: var(--svg-color--d2c4e1, #D2C4E1);
}

.vzaknebes {
  stop-color: var(--svg-color--b198c9, #B198C9);
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w2csk89pk {
  stop-color: var(--svg-color--e27d14, #E27D14);
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wrx6pfbnu {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.15 13.7c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36Z");
}

.wtzd4lbuc {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
  stop-opacity: 0;
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xlyybr0fb {
  stop-color: var(--svg-color--c6912a, #C6912A);
}

.y_r2qxwfl {
  stop-color: var(--svg-color--c38035, #C38035);
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.yidmhu6xw {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m14.83 10.32l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.yidy664bk {
  stop-color: var(--svg-color--c88714, #C88714);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.ynfo-lk5x {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m14.638 10.545l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.yofl1erhy {
  fill: var(--svg-color--da821c, #DA821C);
  d: path("M10.24 11.72a1.12 1.12 0 1 0 0-2.24a1.12 1.12 0 0 0 0 2.24");
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yt-8axwmn {
  fill: var(--svg-color--89004e, #89004E);
  d: path("M15.15 13.7c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36");
}

.yxjq9v5jp {
  stop-color: var(--svg-color--ffb032, #FFB032);
  stop-opacity: 0;
}

.z3nh0_7nl {
  stop-color: var(--svg-color--9e83be, #9E83BE);
  stop-opacity: 0;
}

.zhkis3bpm {
  d: path("M24.087 19.999h1.524v1.734a.25.25 0 0 1-.25.25h-1.024a.25.25 0 0 1-.25-.25z");
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

</style>
