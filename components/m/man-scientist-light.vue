<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ippHexe)" class="naelpkfgy"/><path fill="url(#ilppoMc)" class="eq3rppbvk"/><path fill="url(#iubETLe)" class="eq3rppbvk"/><path fill="url(#i2jEDob)" class="j9ey30b2g"/><path fill="url(#iLVQjmc)" class="j9ey30b2g"/><path fill="url(#iQAWpQG)" class="j9ey30b2g"/><path fill="url(#iCo8ulc)" class="j9ey30b2g"/><path fill="url(#i8uYfFc)" class="e5incvi1b"/><path fill="url(#iPcazNb)" class="e5incvi1b"/><path fill="url(#i9u2jgc)" class="e5incvi1b"/><path fill="url(#iV63qab)" class="e5incvi1b"/><g filter="url(#iAVoo7c)"><path fill="url(#iav9pvc)" class="mekugg6av"/></g><g filter="url(#ifoqxwf)"><path fill="url(#iiV9cCd)" class="nvn2iy7-d"/></g><g filter="url(#iqJcgBd)"><path fill="url(#iFYUGnb)" class="d-qqn8bjq"/></g><path fill="url(#ibnSXkV)" class="p-obsc5hd"/><path fill="url(#iXIz2Xd)" class="p-obsc5hd"/><path fill="url(#iPkR49b)" class="p-obsc5hd"/><path fill="url(#ivftDrd)" class="p-obsc5hd"/><path fill="url(#iH0vHOc)" class="p-obsc5hd"/><path fill="url(#iecDELe)" class="v7p6bhbpd"/><path fill="url(#iVANVBb)" class="v7p6bhbpd"/><path fill="url(#iyUmNeb)" class="v7p6bhbpd"/><path fill="url(#ilDstmM)" class="v7p6bhbpd"/><path fill="url(#iQjJF6b)" class="nvn2iy7-d"/><path fill="url(#iXJNlbd)" class="l0p3fkz8i"/><path fill="url(#iCAqrOd)" class="l0p3fkz8i"/><path fill="url(#ippHexe)" class="naelpkfgy"/><path fill="url(#iMcPUCc)" class="q5imiaboc"/><path fill="url(#iCwroib)" class="q5imiaboc"/><path fill="url(#ikHliQb)" class="g6r91acok"/><path fill="url(#i2bIQGb)" class="g6r91acok"/><path fill="url(#ipbXshc)" class="z-bhsabjt"/><path fill="url(#iM5du6b)" class="z-bhsabjt"/><path fill="url(#i5pfcHe)" class="z-bhsabjt"/><g filter="url(#iGOLEXd)"><rect class="u_ji_6ffx"/><rect fill="url(#iI1jvXd)" class="yej4ptjro"/><rect fill="url(#iu24Oyc)" class="yej4ptjro"/><rect fill="url(#iVQgtub)" class="yej4ptjro"/></g><path fill="url(#i5nqlae)" class="rfapv98pn"/><path fill="url(#iU4Thtb)" class="rfapv98pn"/><path fill="url(#idbHWHd)" class="rfapv98pn"/><path fill="url(#iOmncPa)" class="rfapv98pn"/><path fill="url(#ia2eTMb)" class="c2yme5bjn"/><path fill="url(#ieXiiyd)" class="jocw6wbkd"/><g filter="url(#iaRhEKe)"><path fill="url(#iq9eIBe)" class="h85toedyq"/><path fill="url(#ibsvhWe)" class="h85toedyq"/><path fill="url(#i8GO1nL)" class="h85toedyq"/><path fill="url(#iFLfbBb)" class="h85toedyq"/><path fill="url(#icugr6b)" class="h85toedyq"/></g><path fill="url(#iYLJtkm)" class="h85toedyq"/><g filter="url(#i2RbFeb)"><path stroke="url(#izHZz5U)" class="n1dh5je_j"/></g><g filter="url(#iZhEDvQ)"><path stroke="url(#iLMjMth)" class="oqn_fmbzg"/></g><g filter="url(#irk5aWU)"><path stroke="url(#ifXqgyb)" class="lqgzdkb4h"/></g><g filter="url(#iwIVxgd)"><circle fill="url(#iKjfodM)" class="x8misgbrk"/></g><g filter="url(#iARALPc)"><circle fill="url(#iYIe5gc)" class="pyvs2kbks"/></g><g filter="url(#i1VtcOe)"><circle fill="url(#irlpDYd)" class="tk5yh1ftj"/><circle fill="url(#iwJbseb)" class="tk5yh1ftj"/></g><g filter="url(#ib15oXd)"><circle class="yvbv9454b"/><circle fill="url(#i2Mu1tb)" class="h39fwsbnd"/><circle fill="url(#iTKikmc)" class="h39fwsbnd"/></g><g filter="url(#iiSrSxc)"><path fill="url(#igKEiod)" class="yn84zvtfr"/><path fill="url(#ihzNfce)" class="yn84zvtfr"/><path fill="url(#iMDAOzd)" class="yn84zvtfr"/><path fill="url(#iMkZJTp)" class="yn84zvtfr"/><path fill="url(#ir8oYbb)" class="yn84zvtfr"/><path fill="url(#inhOdkb)" class="yn84zvtfr"/></g><g filter="url(#iWt4Fxc)"><path fill="url(#i22waFd)" class="uvuqtknlv"/></g><g filter="url(#iJAV7Ec)"><path class="b2l33ibon"/><path fill="url(#igPpfWz)" class="dsru2dhfm"/><path fill="url(#iZKAwmd)" class="dsru2dhfm"/><path fill="url(#iXsJBdk)" class="dsru2dhfm"/><path fill="url(#i2aEKib)" class="dsru2dhfm"/></g><g filter="url(#ipJu20U)"><path class="emuavhuga"/></g><g filter="url(#iEPo6Od)"><path class="z7o2hmb6x"/><path fill="url(#iRG3MGC)" class="lnq7hbciy"/><path fill="url(#ikrKXfc)" class="lnq7hbciy"/><path fill="url(#irxnyad)" class="lnq7hbciy"/><path fill="url(#ipBH2Vc)" class="lnq7hbciy"/></g><path fill="url(#iJWQXsd)" class="lnq7hbciy"/><path stroke="url(#il5pfZx)" class="gkkkcr6fz"/><g filter="url(#i1MEHQe)"><path class="vsr8kkset"/></g><g filter="url(#iwfX7Cc)"><path class="p2i1f7yqc"/></g><path class="tvsfdrftt"/><path fill="url(#iempZZd)" class="y7y-mpblw"/><path class="h_68dpmjj"/><g filter="url(#iGzTlwv)"><path class="gegwt69sr"/><path fill="url(#i6yVoUu)" class="x1grikbbn"/></g><g filter="url(#iTjaPic)"><path fill="url(#iLgHOed)" class="a1omozbjg"/></g><path class="ihyyw4b1c"/><path fill="url(#isofbEd)" class="nj59msbyw"/><path class="c40xl0bbc"/><g filter="url(#iX0RUsd)"><path fill="url(#iFCqzXb)" class="jvg94-bfj"/></g><g filter="url(#iC11Pee)"><ellipse transform="rotate(-27.914 12.982 9.842)" class="is4y9v5or"/><ellipse fill="url(#iWk7HWc)" transform="rotate(-27.914 12.982 9.842)" class="oqka3qqdi"/></g><g filter="url(#iIh5XHe)"><path stroke="url(#iHEXoxE)" class="wlz_l_byo"/></g><g filter="url(#iRXofyb)"><path stroke="url(#inhp2Zb)" class="fu4hkwrpp"/></g><g filter="url(#iFmrBId)"><path stroke="url(#izxtK7d)" class="l4ubv256g"/></g><path fill="url(#ixv2IEd)" class="nnl12eb7l"/><g filter="url(#iUs50je)"><path clip-rule="evenodd" class="o93ayxbvn"/></g><defs><radialGradient id="ilppoMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.309)" gradientUnits="userSpaceOnUse"><stop class="h-vnc5n6a"/><stop offset="1" class="buwur_dqz"/></radialGradient><radialGradient id="iubETLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.309)" gradientUnits="userSpaceOnUse"><stop class="iufxq5boh"/><stop offset="1" class="w4j6xtngg"/></radialGradient><radialGradient id="i2jEDob" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.493 14.557)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="iCo8ulc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.403)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="i8uYfFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.278)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="iPcazNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.528)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iiV9cCd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.902)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="ibnSXkV" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.684)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="iXIz2Xd" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.301 -.258)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="iPkR49b" cx="0" cy="0" r="1" gradientTransform="rotate(111.826 5.24 14.376)scale(3.56729 6.41649)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ycu0bme2d"/><stop offset="1" class="zt127j5os"/></radialGradient><radialGradient id="iecDELe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.105)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iyUmNeb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.96)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iQjJF6b" cx="0" cy="0" r="1" gradientTransform="rotate(114.365 1.785 11.82)scale(4.20765 8.70789)" gradientUnits="userSpaceOnUse"><stop class="zqbntluns"/><stop offset="1" class="v6bhjtbbk"/></radialGradient><radialGradient id="iXJNlbd" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.871)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="iMcPUCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.41281 -3.18655 0 15.426 16.56)" gradientUnits="userSpaceOnUse"><stop class="pjmu-bbno"/><stop offset=".632" class="y_k_aubst"/></radialGradient><radialGradient id="iCwroib" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -.875 0 13.766 15.921)" gradientUnits="userSpaceOnUse"><stop class="yyk2ffbyt"/><stop offset="1" class="c42dpwbpe"/></radialGradient><radialGradient id="ikHliQb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25223 1.07928 -1.05974 -2.21144 28.021 23.927)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="i2bIQGb" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .46984 .6163 27.206 23.458)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="i5pfcHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.371)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="iI1jvXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.059)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iu24Oyc" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.005 18.91)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="iVQgtub" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.27)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="iOmncPa" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.215)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="ibsvhWe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.285)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i8GO1nL" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.58)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iFLfbBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.83)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="icugr6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.181)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iYLJtkm" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.01752 -3.72384 0 27.668 24.963)" gradientUnits="userSpaceOnUse"><stop class="b4rjnnb6m"/><stop offset="1" class="bgp-eqwmb"/></radialGradient><radialGradient id="iKjfodM" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07077 9.02 10.62)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iwJbseb" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 20.574 10.355)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="i2Mu1tb" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.16 11.441)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iTKikmc" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.812 29.873)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="ihzNfce" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.43448 -12.8068 0 15.466 8.695)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="mv8xcx_bt"/><stop offset="1" class="y2uhs-btv"/></radialGradient><radialGradient id="ir8oYbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 17.783 9.349)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="inhOdkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.225 9.315)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="igPpfWz" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.143 -9.657)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iZKAwmd" cx="0" cy="0" r="1" gradientTransform="matrix(3.8245 .35196 -.18925 2.05641 18.14 4.755)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iXsJBdk" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.437 2.02)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="i2aEKib" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 8.989 8.837)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="ipBH2Vc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 15.764 12.227)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="iempZZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 17.616 9.938)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i6yVoUu" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.388 10.022)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isofbEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.253 9.938)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iWk7HWc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.483 -1.304)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="ippHexe" x1="8.23" x2="22.659" y1="15.289" y2="15.289" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iLVQjmc" x1="11.239" x2="11.239" y1="30.403" y2="29.09" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iQAWpQG" x1="15.177" x2="14.208" y1="29.09" y2="29.09" gradientUnits="userSpaceOnUse"><stop offset=".129" class="hu0w8ibzb"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="i9u2jgc" x1="19.74" x2="19.74" y1="30.403" y2="29.09" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iV63qab" x1="15.802" x2="16.505" y1="27.965" y2="27.965" gradientUnits="userSpaceOnUse"><stop class="o77zymbyt"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iav9pvc" x1="10.677" x2="12.896" y1="17.934" y2="24.621" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="iFYUGnb" x1="20.45" x2="18.099" y1="18.963" y2="23.664" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="ivftDrd" x1="18.958" x2="17.552" y1="24.09" y2="22.59" gradientUnits="userSpaceOnUse"><stop class="dhui3nlqd"/><stop offset="1" class="ifg4wbcuq"/><stop offset="1" class="kzdc46tfj"/></linearGradient><linearGradient id="iH0vHOc" x1="17.146" x2="17.974" y1="18.871" y2="19.215" gradientUnits="userSpaceOnUse"><stop offset=".081" class="foy77stiz"/><stop offset="1" class="i3p8g97ol"/></linearGradient><linearGradient id="iVANVBb" x1="6.567" x2="6.567" y1="30.345" y2="29.211" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="ilDstmM" x1="8.38" x2="7.935" y1="29.379" y2="29.376" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="iCAqrOd" x1="22.753" x2="23.162" y1="27.652" y2="27.637" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="ipbXshc" x1="23.825" x2="26.529" y1="20.84" y2="20.84" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iM5du6b" x1="26.529" x2="26.18" y1="20.824" y2="20.824" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="i5nqlae" x1="26.529" x2="25.177" y1="23.152" y2="23.152" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iU4Thtb" x1="26.529" x2="26.129" y1="23.301" y2="23.301" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="idbHWHd" x1="23.696" x2="24.227" y1="23.301" y2="23.301" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="ia2eTMb" x1="24.782" x2="23.892" y1="21.793" y2="21.793" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="ieXiiyd" x1="24.782" x2="23.892" y1="23.574" y2="23.574" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iq9eIBe" x1="27.165" x2="23.137" y1="28.043" y2="28.043" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="izHZz5U" x1="23.754" x2="25.463" y1="26.061" y2="26.061" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iLMjMth" x1="23.676" x2="25.385" y1="27.365" y2="27.365" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="ifXqgyb" x1="23.754" x2="25.463" y1="28.67" y2="28.67" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iYIe5gc" x1="10.69" x2="10.049" y1="10.899" y2="10.899" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="irlpDYd" x1="21.288" x2="20.47" y1="9.529" y2="12.065" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="igKEiod" x1="19.473" x2="11.836" y1="11.009" y2="12.147" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="iMDAOzd" x1="9.795" x2="13.153" y1="12.537" y2="12.651" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iMkZJTp" x1="10.042" x2="11.923" y1="13.705" y2="13.638" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="i22waFd" x1="14.906" x2="23.049" y1="8.025" y2="5.109" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iRG3MGC" x1="14.573" x2="15.511" y1="11.669" y2="11.669" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="ikrKXfc" x1="16.375" x2="15.35" y1="11.991" y2="11.977" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="irxnyad" x1="15.632" x2="15.632" y1="12.733" y2="12.161" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iJWQXsd" x1="15.563" x2="15.563" y1="12.775" y2="12.608" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="il5pfZx" x1="14.4" x2="14.835" y1="14.348" y2="13.661" gradientUnits="userSpaceOnUse"><stop class="kv1t0ybkp"/><stop offset=".663" class="huj4n22eg"/></linearGradient><linearGradient id="iLgHOed" x1="18.394" x2="18.08" y1="9.992" y2="10.185" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFCqzXb" x1="13.997" x2="13.683" y1="9.992" y2="10.185" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHEXoxE" x1="18.409" x2="17.989" y1="7.853" y2="6.994" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="inhp2Zb" x1="13.105" x2="11.916" y1="7.725" y2="7.226" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="izxtK7d" x1="10.775" x2="10.775" y1="5.71" y2="7.867" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="ixv2IEd" x1="10.588" x2="22.177" y1="9.592" y2="9.592" gradientUnits="userSpaceOnUse"><stop class="z473rkg5k"/><stop offset=".115" class="f-zxjbc7n"/><stop offset=".257" class="f-zxjbc7n"/><stop offset=".917" class="l7b4ixb5j"/></linearGradient><filter id="iAVoo7c" width="7.023" height="11.703" x="8.591" y="15.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".375"/></filter><filter id="ifoqxwf" width="5.673" height="10.453" x="9.476" y="15.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2180"/></filter><filter id="iqJcgBd" width="6.388" height="10.529" x="15.499" y="16.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".375"/></filter><filter id="iGOLEXd" width="4.008" height=".781" x="23.173" y="18.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2180"/></filter><filter id="iaRhEKe" width="4.468" height="5.556" x="23.137" y="24.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2180"/></filter><filter id="i2RbFeb" width="2.097" height=".3" x="23.604" y="25.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".05"/></filter><filter id="iZhEDvQ" width="2.097" height=".3" x="23.526" y="27.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".05"/></filter><filter id="irk5aWU" width="2.097" height=".3" x="23.604" y="28.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".05"/></filter><filter id="iwIVxgd" width="3.539" height="3.339" x="9.02" y="8.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2180"/></filter><filter id="iARALPc" width="2.99" height="2.99" x="9.195" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".25"/></filter><filter id="i1VtcOe" width="3.589" height="3.589" x="18.533" y="8.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2180"/></filter><filter id="ib15oXd" width="2.99" height="2.99" x="18.707" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".25"/></filter><filter id="iiSrSxc" width="10.373" height="12.277" x="10.28" y="4.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2180"/></filter><filter id="iWt4Fxc" width="8.246" height="7.066" x="13.607" y="2.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation="1"/></filter><filter id="iJAV7Ec" width="12.601" height="8.543" x="9.137" y="1.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2180"/></filter><filter id="ipJu20U" width="3.26" height="4.181" x="13.568" y="9.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".375"/></filter><filter id="iEPo6Od" width="2.377" height="3.181" x="14.249" y="9.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".125"/></filter><filter id="i1MEHQe" width="2.979" height="1.873" x="16.619" y="6.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2180"/></filter><filter id="iwfX7Cc" width="2.98" height="1.873" x="11.472" y="6.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2180"/></filter><filter id="iGzTlwv" width=".787" height=".696" x="16.882" y="9.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".05"/></filter><filter id="iTjaPic" width=".891" height=".913" x="17.721" y="9.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".1"/></filter><filter id="iX0RUsd" width=".986" height="1.04" x="13.28" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".1"/></filter><filter id="iC11Pee" width=".913" height=".704" x="12.525" y="9.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".05"/></filter><filter id="iIh5XHe" width="3.099" height="1.681" x="16.473" y="7.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".25"/></filter><filter id="iRXofyb" width="3.177" height="1.738" x="11.254" y="7.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".25"/></filter><filter id="iFmrBId" width="1.008" height="2.269" x="10.271" y="5.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2180" stdDeviation=".125"/></filter><filter id="iUs50je" width="11.479" height="6.324" x="9.611" y="5.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.537255 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2180"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.760784 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2180" result="effect2_innerShadow_4002_2180"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-scientist-light" /></template>
<style>
.a1omozbjg {
  d: path("M18.413 10.236a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b2l33ibon {
  fill: var(--svg-color--242324, #242324);
  d: path("m20.256 4.143l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.215-.213-.376-.533-.376-.853v-.853c0-.267-.214-.48-.429-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.854l-.16.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.429-.213a8 8 0 0 0 .805-.587l.965-1.013c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.b4rjnnb6m {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bgp-eqwmb {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
  stop-opacity: 0;
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.buwur_dqz {
  stop-color: var(--svg-color--2f649d, #2F649D);
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c2yme5bjn {
  d: path("M23.825 22.027v-.468h.805a.234.234 0 1 1 0 .468z");
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c40xl0bbc {
  fill: var(--svg-color--000, #000);
  d: path("M13.762 10.354a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.236");
}

.c42dpwbpe {
  stop-color: var(--svg-color--da9890, #DA9890);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d-qqn8bjq {
  d: path("m21.02 18.134l.115 1.534a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.076.22l.554.611a.44.44 0 0 1-.012.607L16.552 26a.177.177 0 0 1-.303-.124v-2.991c0-.25.053-.497.155-.725l2.306-5.136c.822.264 1.599.64 2.31 1.111");
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.dhui3nlqd {
  stop-color: var(--svg-color--d6baf6, #D6BAF6);
}

.dsru2dhfm {
  d: path("m20.256 4.143l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.215-.213-.376-.533-.376-.853v-.853c0-.267-.214-.48-.429-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.854l-.16.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.429-.213a8 8 0 0 0 .805-.587l.965-1.013c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e5incvi1b {
  d: path("M19.865 16.273a10.5 10.5 0 0 1 2.878 1.918v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.52z");
}

.emuavhuga {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.162 10.498l-.82 1.7c-.102.349.142.698.488.698h.737c.345 0 .59-.354.488-.699l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.eq3rppbvk {
  d: path("M15.466 15.34c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.f-zxjbc7n {
  stop-color: var(--svg-color--8ac5a2, #8AC5A2);
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.foy77stiz {
  stop-color: var(--svg-color--9f98a7, #9F98A7);
}

.ft5dv1b6b {
  fill: none;
}

.fu4hkwrpp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.879 8.274c.327-.289 1.041-.593 1.927-.452");
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g6r91acok {
  d: path("M26.434 22.95c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.gegwt69sr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.552 9.65c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.246.159-.358c.15-.113.325-.136.388-.051");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gkkkcr6fz {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.075 13.377a2.96 2.96 0 0 0 1.362.323c.505 0 .969-.118 1.362-.323a.2.2 0 0 1 .242.04c.057.06.078.155.02.241m-2.986-.28l2.945.252m-2.945-.253a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.253m3.207.028l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.868c-.682 0-1.28-.347-1.624-.867m3.207-.029a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.041.028v.001l.041-.029m-.041.028l.041-.027");
}

.h_68dpmjj {
  fill: var(--svg-color--000, #000);
  d: path("M17.107 10.354c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-vnc5n6a {
  stop-color: var(--svg-color--3a6fb4, #3A6FB4);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h39fwsbnd {
  cx: 20.202px;
  cy: 10.62px;
  r: 0.995px;
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.h85toedyq {
  d: path("M23.137 25.306c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hu0w8ibzb {
  stop-color: var(--svg-color--b5a2c9, #B5A2C9);
}

.huj4n22eg {
  stop-color: var(--svg-color--e5b2a5, #E5B2A5);
  stop-opacity: 0;
}

.i3p8g97ol {
  stop-color: var(--svg-color--e2d6f0, #E2D6F0);
  stop-opacity: 0;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ihyyw4b1c {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.044 9.19c-.653 0-1.204.45-1.354 1.058a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.is4y9v5or {
  cx: 12.982px;
  cy: 9.842px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.iufxq5boh {
  stop-color: var(--svg-color--3971d9, #3971D9);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j9ey30b2g {
  d: path("M11.114 16.273a10.5 10.5 0 0 0-2.878 1.918v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.jocw6wbkd {
  d: path("M23.825 23.809v-.47h.805a.234.234 0 0 1 0 .47z");
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.jvg94-bfj {
  d: path("M14.066 10.249c0-.289-.234-.481-.298-.539l-.288.279l.178.361z");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv1t0ybkp {
  stop-color: var(--svg-color--e5b2a5, #E5B2A5);
}

.kzdc46tfj {
  stop-color: var(--svg-color--e7cfff, #E7CFFF);
  stop-opacity: 0;
}

.l0p3fkz8i {
  d: path("M22.753 29.98V18.19c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l4ubv256g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.905 5.81v.897c-.008.148-.07.48-.258.621");
}

.l7b4ixb5j {
  stop-color: var(--svg-color--b2d5c0, #B2D5C0);
  stop-opacity: 0.63;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lnq7hbciy {
  d: path("m15.055 10.335l-.531 1.7a.54.54 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.lqgzdkb4h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.592h1.797");
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mekugg6av {
  d: path("m9.474 17.713l-.131 1.733a.6.6 0 0 0 .494.636l.48.085a.15.15 0 0 1 .084.248l-.626.691a.5.5 0 0 0 .015.686l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.mv8xcx_bt {
  stop-color: var(--svg-color--d1969c, #D1969C);
  stop-opacity: 0;
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.n1dh5je_j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.982h1.797");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.naelpkfgy {
  d: path("M15.466 15.29h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nj59msbyw {
  d: path("M13.251 9.461a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.nnl12eb7l {
  d: path("M18.083 6.33h-5.275c-1.497 0-2.737 1.2-2.746 2.706a2.72 2.72 0 0 0 2.716 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.269 2.618-2.677a2.71 2.71 0 0 0-2.707-2.736");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.nvn2iy7-d {
  d: path("m9.608 17.104l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .085.249l-.626.69a.5.5 0 0 0 .014.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803a10.6 10.6 0 0 0-2.61 1.255");
}

.o77zymbyt {
  stop-color: var(--svg-color--a588b8, #A588B8);
}

.o93ayxbvn {
  fill: var(--svg-color--ada3b0, #ADA3B0);
  fill-rule: evenodd;
  d: path("M9.761 9.034C9.773 7.36 11.15 6.03 12.808 6.03h5.275a3.01 3.01 0 0 1 3.007 3.04c-.022 1.568-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.341c-.045-.066-.09-.077-.112-.077s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.003a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34a.74.74 0 0 1 .609.34v.002a2.46 2.46 0 0 0 2.114 1.076c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.432h-5.275c-1.336 0-2.437 1.07-2.447 2.407");
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oqka3qqdi {
  cx: 12.982px;
  cy: 9.842px;
  rx: 0.389px;
  ry: 0.197px;
}

.oqn_fmbzg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.287h1.797");
}

.p-obsc5hd {
  d: path("m21.37 17.104l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.249l.626.69a.5.5 0 0 1-.014.687l-4.732 4.808a.2.2 0 0 1-.343-.14v-3.38a2 2 0 0 1 .175-.82l2.606-5.803a10.6 10.6 0 0 1 2.61 1.255");
}

.p2i1f7yqc {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.664 7.9l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.68-.823");
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pjmu-bbno {
  stop-color: var(--svg-color--ca8995, #CA8995);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.pyvs2kbks {
  cx: 10.69px;
  cy: 10.62px;
  r: 0.995px;
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.q5imiaboc {
  d: path("M15.426 18.61a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rfapv98pn {
  d: path("M26.529 21.215v4.172h-2.704v-4.172z");
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tk5yh1ftj {
  cx: 20.202px;
  cy: 10.62px;
  r: 1.669px;
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.tvsfdrftt {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.825 9.19c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.27a1.4 1.4 0 0 1 1.37-1.128");
}

.u_ji_6ffx {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.668px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uvuqtknlv {
  d: path("m19.4 4.996l-3.077 1.026a1.047 1.047 0 0 0 .47 2.031l3.06-.41z");
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v6bhjtbbk {
  stop-color: var(--svg-color--a8a1ad, #A8A1AD);
  stop-opacity: 0;
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.v7p6bhbpd {
  d: path("M8.226 29.98V18.19c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vsr8kkset {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.156 7.9l-.003-.002l-.004-.004l-.012-.01a2 2 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 1 0 .166 1.054c.398-.062.716.011.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w4j6xtngg {
  stop-color: var(--svg-color--3971d9, #3971D9);
  stop-opacity: 0;
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wlz_l_byo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.098 7.756c.43-.075 1.268-.054 1.849.398");
}

.x1grikbbn {
  d: path("M17.552 9.65c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.246.159-.358c.15-.113.325-.136.388-.051");
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.x8misgbrk {
  cx: 10.69px;
  cy: 10.62px;
  r: 1.669px;
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.y_k_aubst {
  stop-color: var(--svg-color--dba1a5, #DBA1A5);
}

.y2uhs-btv {
  stop-color: var(--svg-color--bf809a, #BF809A);
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.y7y-mpblw {
  d: path("M17.618 9.461a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.127");
}

.ycu0bme2d {
  stop-color: var(--svg-color--c2bfc3, #C2BFC3);
}

.yej4ptjro {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.668px;
  rx: 0.391px;
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yn84zvtfr {
  d: path("M10.28 8.57c0-.267.107-.587.321-.747l.161-.16c.268-.214.376-.534.376-.854v-.853c0-.267.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427s3.272.267 3.916.427c.214.053.429.266.429.533v.853c0 .32.16.64.375.854c.502.351.47.545.43.96c-.055.533-.108 1.44-.108 1.44h.018l-.266 3.957c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003c-.14-1.816-.2-3.638-.367-5.45");
}

.yvbv9454b {
  cx: 20.202px;
  cy: 10.62px;
  r: 0.995px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.yyk2ffbyt {
  stop-color: var(--svg-color--da9890, #DA9890);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z-bhsabjt {
  d: path("M23.825 19.449h2.703v5.938h-2.703z");
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z473rkg5k {
  stop-color: var(--svg-color--b2d5c0, #B2D5C0);
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.z7o2hmb6x {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.055 10.335l-.531 1.7a.54.54 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zqbntluns {
  stop-color: var(--svg-color--746e77, #746E77);
}

.zt127j5os {
  stop-color: var(--svg-color--ddd8e2, #DDD8E2);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
