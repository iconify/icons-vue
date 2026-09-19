<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iR8NYhd)" class="e5ucantjx"/><path fill="url(#im2mq1w)" class="a6yq75bbi"/><g filter="url(#iPfjFee)"><path fill="url(#iZPuzLc)" class="omftgvbac"/><path fill="url(#iIrO6tO)" class="omftgvbac"/></g><path fill="url(#iODrN7d)" class="omftgvbac"/><path fill="url(#iDoctsc)" class="omftgvbac"/><path fill="url(#ilxKaYb)" class="omftgvbac"/><path fill="url(#iFOAEtb)" class="omftgvbac"/><path fill="url(#itPxmpd)" class="omftgvbac"/><path fill="url(#iopOaVd)" class="omftgvbac"/><path fill="url(#iL3Ilze)" class="omftgvbac"/><g filter="url(#iVzC1tA)"><path class="s0h6qabck"/></g><g filter="url(#iStMdEc)"><path class="qltvyfb3b"/><path fill="url(#i5fDXGc)" class="e-zb_sb0t"/><path fill="url(#iAxVu2b)" class="e-zb_sb0t"/><path fill="url(#iM8vtDb)" class="e-zb_sb0t"/><path fill="url(#i3sRjsb)" class="e-zb_sb0t"/><path fill="url(#iFjOfUp)" class="e-zb_sb0t"/></g><g filter="url(#ikZb7Xc)"><path fill="url(#iuKrsIb)" class="bnbr98b0b"/><path fill="url(#iCDNjgc)" class="bnbr98b0b"/><path fill="url(#iw43Bzb)" class="bnbr98b0b"/><path fill="url(#iRP9kZd)" class="bnbr98b0b"/><path fill="url(#izmLBvd)" class="bnbr98b0b"/></g><g filter="url(#iW9w88c)"><path class="q_yq25bad"/><path fill="url(#ilqQ6Nb)" class="rbbulnz3l"/><path fill="url(#iMydfGc)" class="rbbulnz3l"/></g><g filter="url(#iIsew1d)"><path class="jmecmib9q"/><path fill="url(#i8BSf1c)" class="t-faq4izi"/><path fill="url(#i1hxgRS)" class="t-faq4izi"/><path fill="url(#iMWYBDc)" class="t-faq4izi"/></g><path class="utrmehb1k"/><path fill="url(#iPjnENe)" class="cswzjcx6u"/><path class="iitgd8bac"/><g filter="url(#iIs4ipe)"><path class="dodqfog5q"/><path fill="url(#i9QUMfK)" class="nsn8oes0z"/></g><g filter="url(#iFxthed)"><path fill="url(#iKnUjve)" class="t0_upib5g"/></g><path class="ub8ckabiz"/><path fill="url(#iOPziAb)" class="fqu12ubrd"/><path class="ebo5c_0lf"/><g filter="url(#iWYKwPb)"><path fill="url(#i7aVE8b)" class="q5hvggldb"/></g><g filter="url(#iucXUhb)"><ellipse transform="rotate(-27.914 12.844 12.236)" class="z-qcyfbze"/><ellipse fill="url(#i8Ldsle)" transform="rotate(-27.914 12.844 12.236)" class="a3xscqbym"/></g><path fill="url(#ilL3FtY)" class="nl8aomm7e"/><path fill="url(#iMkxljC)" class="nl8aomm7e"/><path fill="url(#in0tI3O)" class="nl8aomm7e"/><path fill="url(#iHv5rJd)" class="nl8aomm7e"/><path fill="url(#idcDsob)" class="l3e-mtbcj"/><path fill="url(#iuRXVib)" class="l3e-mtbcj"/><g filter="url(#iYkDlWc)"><path fill="url(#iYDkXVo)" class="ibf0x1bat"/></g><g filter="url(#ilrtgmb)"><path fill="url(#iTfubCc)" class="tmrtimg7x"/></g><g filter="url(#iffuK5c)"><path class="jqtuckbvl"/></g><g filter="url(#iGZaVOd)"><path class="fdhnkacbc"/></g><g filter="url(#ioSpFbe)"><path stroke="url(#i565Yid)" class="gspwrdz1o"/></g><g filter="url(#iKJGCmb)"><path stroke="url(#igsFxVc)" class="wq0eljlkx"/></g><path class="uv3zckjhy"/><path class="w73iq3bud"/><path fill="url(#iY2ScGe)" class="akki1obxr"/><path fill="url(#inirSwb)" class="akki1obxr"/><path fill="url(#ikeLGbe)" class="u4cp3820t"/><path fill="url(#ihqOLGc)" class="cuomu7bqz"/><path fill="url(#iRbdh4d)" class="cuomu7bqz"/><path fill="url(#i16tupc)" class="cuomu7bqz"/><path fill="url(#isBeo5c)" class="cuomu7bqz"/><path fill="url(#izAvOPb)" class="cuomu7bqz"/><path fill="url(#igdf08b)" class="cuomu7bqz"/><path fill="url(#iiwVwQd)" class="twmiqpbxq"/><path fill="url(#iDDcgbe)" class="v3eonib4h"/><path fill="url(#iwGAPQd)" class="v3eonib4h"/><path fill="url(#ixh7Cge)" class="v3eonib4h"/><path fill="url(#ijpiCfc)" class="e3jco7qba"/><path fill="url(#i1sECPb)" class="e3jco7qba"/><path fill="url(#ig6z7Ce)" class="e3jco7qba"/><path fill="url(#iwXkjye)" class="i4fzwzbpd"/><path fill="url(#iILk5Os)" class="i4fzwzbpd"/><path fill="url(#i1Yiqzc)" class="vzu9-mfnh"/><path fill="url(#ieKYcud)" class="vzu9-mfnh"/><path fill="url(#im9ZupF)" class="vzu9-mfnh"/><path fill="url(#iDpYHJs)" class="vzu9-mfnh"/><g filter="url(#iLCoaTc)"><path fill="url(#iZCDnoA)" class="cw3sn1brq"/><path fill="url(#iFL936D)" class="cw3sn1brq"/></g><path fill="url(#iGtsxhb)" class="cw3sn1brq"/><g filter="url(#iNJOcPc)"><path fill="url(#iNZxpEe)" class="j_0xl5h8m"/></g><defs><radialGradient id="iR8NYhd" cx="0" cy="0" r="1" gradientTransform="matrix(.96166 2.5937 -3.08112 1.14238 22.1 14.564)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="im2mq1w" cx="0" cy="0" r="1" gradientTransform="matrix(1.89623 .59596 -1.83857 5.85 8.217 15.194)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iZPuzLc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.71417 0 0 -11.8773 19.601 13.355)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iIrO6tO" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23876 3.7026 -3.0568 -1.84827 19.112 6.96)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iDoctsc" cx="0" cy="0" r="1" gradientTransform="rotate(94.704 6.36 11.182)scale(16.0095 13.2578)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="axnqidyuu"/><stop offset="1" class="j7pnfkbxw"/></radialGradient><radialGradient id="ilxKaYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.47484 1.82511 0 19.138 11.669)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iFOAEtb" cx="0" cy="0" r="1" gradientTransform="matrix(.00505 -1.4054 1.5294 .0055 13.041 11.729)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="itPxmpd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.971 7.634)scale(10.9332 27.9288)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iopOaVd" cx="0" cy="0" r="1" gradientTransform="rotate(-40.741 16.893 -4.87)scale(5.73919 1.69526)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iL3Ilze" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.184 15.327)scale(3.2216 1.28781)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iAxVu2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3135 -.9853 0 16.594 15.124)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="i3sRjsb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.95362 .89572 -1.43949 -3.13962 16.743 14.392)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iCDNjgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.49678 11.3718 0 9.279 9.64)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iw43Bzb" cx="0" cy="0" r="1" gradientTransform="matrix(.14646 -3.22688 5.7174 .2595 22.238 11.323)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iRP9kZd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02947 -1.99249 1.46259 -2.22378 21.269 3.262)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="izmLBvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.16245 1.89434 -4.3864 2.69168 14.832 1.217)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="ilqQ6Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.82692 0 0 -1.04918 16.32 4.119)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iMydfGc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.84 -3.592)scale(7.74003 8.57516)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="i8BSf1c" cx="0" cy="0" r="1" gradientTransform="matrix(3.96541 0 0 1.53575 20.422 5.252)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="i1hxgRS" cx="0" cy="0" r="1" gradientTransform="matrix(3.47316 -3.27775 5.9977 6.35527 19.41 9.153)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iMWYBDc" cx="0" cy="0" r="1" gradientTransform="matrix(4.21154 .48759 -.20227 1.74706 18.26 7.256)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iPjnENe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04198 -1.65739 0 18.798 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i9QUMfK" cx="0" cy="0" r="1" gradientTransform="matrix(-.29785 -.38382 .52843 -.41007 18.504 12.467)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOPziAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04204 -1.65748 0 13.193 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8Ldsle" cx="0" cy="0" r="1" gradientTransform="matrix(-.00994 -.63455 .76277 -.01194 12.825 12.642)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMkxljC" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 2.921 20.555)scale(2.99201 2.85461)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="in0tI3O" cx="0" cy="0" r="1" gradientTransform="matrix(1.01175 -1.38847 1.16382 .84805 22.388 12.895)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iHv5rJd" cx="0" cy="0" r="1" gradientTransform="rotate(-69.263 20.763 -9.755)scale(2.12915 2.84485)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iuRXVib" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12971 0 0 -2.3746 9.682 13.022)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iYDkXVo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17705 .20204 -.20716 -1.20684 9.745 13.023)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="iY2ScGe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.445)" gradientUnits="userSpaceOnUse"><stop class="prd44wbso"/><stop offset="1" class="c5khawelw"/></radialGradient><radialGradient id="inirSwb" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.227)" gradientUnits="userSpaceOnUse"><stop class="u1hhhxbfd"/><stop offset="1" class="cl_cdxbgs"/></radialGradient><radialGradient id="ikeLGbe" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 1.25 -2.6929 5.58776 8.406 17.32)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="sy-f5ccgl"/><stop offset="1" class="i26rr_0fw"/></radialGradient><radialGradient id="ihqOLGc" cx="0" cy="0" r="1" gradientTransform="matrix(17.51082 8.75543 -2.15289 4.30577 13.551 19.209)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="v3bwo4btz"/><stop offset="1" class="kd1_xhb_o"/></radialGradient><radialGradient id="iRbdh4d" cx="0" cy="0" r="1" gradientTransform="rotate(159.944 11.543 15.187)scale(2.90693 2.17455)" gradientUnits="userSpaceOnUse"><stop class="cq9p23brg"/><stop offset="1" class="cwmsguygo"/></radialGradient><radialGradient id="i16tupc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11963 5.31578 -8.32746 -1.75396 14.245 17.692)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="w58mn6r_g"/><stop offset="1" class="xrn2z6b6u"/></radialGradient><radialGradient id="izAvOPb" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.455 -3.07)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="mq0gl8bsz"/><stop offset="1" class="w-vsz3bnm"/></radialGradient><radialGradient id="iiwVwQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 .6475 -1.4343 -3.32276 24.094 18.195)" gradientUnits="userSpaceOnUse"><stop class="qxiqgebpn"/><stop offset="1" class="m_8hwoksz"/></radialGradient><radialGradient id="iDDcgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.883)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="jbd_cz55y"/><stop offset="1" class="m7o64xbbx"/></radialGradient><radialGradient id="ijpiCfc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.469)" gradientUnits="userSpaceOnUse"><stop class="qyctpef7w"/><stop offset=".615" class="cskv_pboi"/></radialGradient><radialGradient id="iwXkjye" cx="0" cy="0" r="1" gradientTransform="matrix(1.74664 .85478 -1.17534 2.40165 3.176 17.648)" gradientUnits="userSpaceOnUse"><stop class="t0phas2np"/><stop offset=".697" class="f1gbiwx_q"/></radialGradient><radialGradient id="iILk5Os" cx="0" cy="0" r="1" gradientTransform="rotate(162.607 1.083 8.97)scale(.89785 1.70016)" gradientUnits="userSpaceOnUse"><stop class="w_6w3opsv"/><stop offset="1" class="u9mvxzbci"/></radialGradient><radialGradient id="i1Yiqzc" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.294 6.356)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="g4wyz37uu"/><stop offset="1" class="xjh-ixbfp"/></radialGradient><radialGradient id="ieKYcud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 .59376 -.2045 -.35517 30.161 13.225)" gradientUnits="userSpaceOnUse"><stop class="d-by8cbiw"/><stop offset="1" class="hqjfx29jv"/></radialGradient><radialGradient id="iDpYHJs" cx="0" cy="0" r="1" gradientTransform="rotate(-25.641 56.32 -43.992)scale(2.59977 2.78402)" gradientUnits="userSpaceOnUse"><stop class="ma1u1iuqv"/><stop offset="1" class="rizivib-o"/></radialGradient><radialGradient id="iFL936D" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.288)" gradientUnits="userSpaceOnUse"><stop class="whmlezbbn"/><stop offset="1" class="r8d20-6qp"/></radialGradient><radialGradient id="iGtsxhb" cx="0" cy="0" r="1" gradientTransform="matrix(1.00475 -.26214 .85754 3.28688 4.382 18.192)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="bwst52bsk"/><stop offset="1" class="br5e4xb7k"/></radialGradient><linearGradient id="iODrN7d" x1="22.619" x2="19.371" y1="15.52" y2="15.52" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="i5fDXGc" x1="17.072" x2="15.995" y1="14.243" y2="14.288" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iM8vtDb" x1="15.995" x2="15.995" y1="15.706" y2="15.109" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iFjOfUp" x1="15.995" x2="15.995" y1="12.232" y2="12.934" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iuKrsIb" x1="24.795" x2="9.881" y1="6.082" y2="6.082" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iKnUjve" x1="19.798" x2="19.394" y1="12.429" y2="12.678" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7aVE8b" x1="14.148" x2="13.745" y1="12.428" y2="12.677" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilL3FtY" x1="24.261" x2="22.711" y1="12.282" y2="15.077" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="idcDsob" x1="8.482" x2="10.355" y1="13.188" y2="13.024" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iTfubCc" x1="22.975" x2="22.975" y1="11.796" y2="14.241" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="i565Yid" x1="13.921" x2="11.175" y1="9.208" y2="9.928" gradientUnits="userSpaceOnUse"><stop offset=".333" class="bfhgpjbxp"/><stop offset="1" class="jz-x_6ndp"/></linearGradient><linearGradient id="igsFxVc" x1="18.178" x2="20.924" y1="9.208" y2="9.928" gradientUnits="userSpaceOnUse"><stop offset=".333" class="bfhgpjbxp"/><stop offset="1" class="jz-x_6ndp"/></linearGradient><linearGradient id="isBeo5c" x1="9.156" x2="10.344" y1="18.508" y2="18.883" gradientUnits="userSpaceOnUse"><stop class="psrrqcksv"/><stop offset="1" class="rbkr51v-c"/></linearGradient><linearGradient id="igdf08b" x1="17.406" x2="17.906" y1="26.977" y2="25.758" gradientUnits="userSpaceOnUse"><stop class="gd1of5hxe"/><stop offset="1" class="v1z821b6o"/></linearGradient><linearGradient id="iwGAPQd" x1="14.83" x2="14.461" y1="26.816" y2="25.927" gradientUnits="userSpaceOnUse"><stop class="q9mg64b4e"/><stop offset="1" class="vzmhuwavr"/></linearGradient><linearGradient id="ixh7Cge" x1="22.827" x2="21.613" y1="18.819" y2="19.382" gradientUnits="userSpaceOnUse"><stop class="smo9u60ba"/><stop offset="1" class="ktas3sbvn"/></linearGradient><linearGradient id="i1sECPb" x1="28.085" x2="27.547" y1="19.514" y2="18.683" gradientUnits="userSpaceOnUse"><stop offset=".198" class="y5l4vob7e"/><stop offset="1" class="yemvrmxbd"/></linearGradient><linearGradient id="ig6z7Ce" x1="26.75" x2="27.494" y1="17.398" y2="18.158" gradientUnits="userSpaceOnUse"><stop offset=".353" class="vhav-abny"/><stop offset="1" class="m754bqf9r"/></linearGradient><linearGradient id="im9ZupF" x1="25.489" x2="25.997" y1="14.289" y2="15.189" gradientUnits="userSpaceOnUse"><stop class="sghkjcc6n"/><stop offset="1" class="n39i5izax"/></linearGradient><linearGradient id="iZCDnoA" x1="8" x2="5.5" y1="15.758" y2="19.524" gradientUnits="userSpaceOnUse"><stop offset=".206" class="inmwvkbzn"/><stop offset="1" class="myckyxb_u"/></linearGradient><linearGradient id="iNZxpEe" x1="29.179" x2="24.036" y1="14.953" y2="17.82" gradientUnits="userSpaceOnUse"><stop class="hdh7eybjd"/><stop offset="1" class="d3plm5x9f"/></linearGradient><filter id="iPfjFee" width="14.126" height="16.05" x="9.492" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24797"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24797" result="effect2_innerShadow_3987_24797"/></filter><filter id="iVzC1tA" width="4.411" height="5.725" x="13.524" y="11.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".5"/></filter><filter id="iStMdEc" width="2.811" height="4.125" x="14.59" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".1"/></filter><filter id="ikZb7Xc" width="16.532" height="10.59" x="7.729" y="1.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24797"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24797" result="effect2_innerShadow_3987_24797"/></filter><filter id="iW9w88c" width="8.814" height="8.053" x="8.006" y="2.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24797"/><feGaussianBlur result="effect2_foregroundBlur_3987_24797" stdDeviation=".25"/></filter><filter id="iIsew1d" width="8.596" height="7.796" x="15.543" y="3.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".25"/></filter><filter id="iIs4ipe" width=".954" height=".837" x="17.883" y="11.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".05"/></filter><filter id="iFxthed" width="1.033" height="1.061" x="18.99" y="11.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".1"/></filter><filter id="iWYKwPb" width="1.153" height="1.222" x="13.284" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".1"/></filter><filter id="iucXUhb" width="1.116" height=".848" x="12.286" y="11.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".05"/></filter><filter id="iYkDlWc" width="1.565" height="2.914" x="8.318" y="11.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".125"/></filter><filter id="ilrtgmb" width="2.216" height="3.444" x="21.867" y="11.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".25"/></filter><filter id="iffuK5c" width="2.884" height="1.34" x="11.376" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0784314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24797"/></filter><filter id="iGZaVOd" width="2.884" height="1.34" x="17.939" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0784314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24797"/></filter><filter id="ioSpFbe" width="2.717" height="1.234" x="11.486" y="8.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".125"/></filter><filter id="iKJGCmb" width="2.717" height="1.234" x="17.896" y="8.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".125"/></filter><filter id="iLCoaTc" width="7.3" height="8.016" x="2" y="12.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.290196 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24797"/></filter><filter id="iNJOcPc" width="5.538" height="5.423" x="24.159" y="13.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24797" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-no-medium-dark" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a3xscqbym {
  cx: 12.844px;
  cy: 12.236px;
  rx: 0.5px;
  ry: 0.253px;
}

.a6yq75bbi {
  d: path("M9.752 14.96a2.1 2.1 0 0 1-1.162-.396v1.195a2.79 2.79 0 0 0 1.722 2.593a5.3 5.3 0 0 1-.444-1.515z");
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.akki1obxr {
  d: path("M25.5 30.008h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.axnqidyuu {
  stop-color: var(--svg-color--804776, #804776);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bfhgpjbxp {
  stop-color: var(--svg-color--463c3b, #463C3B);
}

.bnbr98b0b {
  d: path("M22.23 4.823c.66.228 1.253.69 1.628 1.35a3.04 3.04 0 0 1-.136 3.245a2 2 0 0 0-.348 1.123v1.526a2.2 2.2 0 0 0-.856-.345l.1-2.063a1.86 1.86 0 0 0-1.77-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34l.028 1.976c-.326.048-.655.155-.913.336v-1.541c0-.4-.123-.792-.348-1.123a3.07 3.07 0 0 1-.184-3.141a3 3 0 0 1 1.67-1.447a3.44 3.44 0 0 0 1.777-1.426a2.99 2.99 0 0 1 2.534-1.412c.416 0 .81.09 1.179.241c.49.214 1.042.214 1.532 0a3 3 0 0 1 1.172-.24c1.083 0 2.03.585 2.554 1.453a3.24 3.24 0 0 0 1.737 1.377");
}

.br5e4xb7k {
  stop-color: var(--svg-color--805c58, #805C58);
  stop-opacity: 0;
}

.bwst52bsk {
  stop-color: var(--svg-color--805c58, #805C58);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c5khawelw {
  stop-color: var(--svg-color--ff9540, #FF9540);
  stop-opacity: 0;
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl_cdxbgs {
  stop-color: var(--svg-color--e2632d, #E2632D);
  stop-opacity: 0;
}

.cq9p23brg {
  stop-color: var(--svg-color--ff7d48, #FF7D48);
}

.cskv_pboi {
  stop-color: var(--svg-color--794f40, #794F40);
}

.cswzjcx6u {
  d: path("M18.8 11.747a1.146 1.146 0 0 1 1.105 1.448H17.69a1.15 1.15 0 0 1 1.11-1.448");
}

.cuomu7bqz {
  d: path("m11.56 16.106l15.407 7.178a3.53 3.53 0 0 1 1.7 4.687a3.52 3.52 0 0 1-4.679 1.704L8.581 22.487a1 1 0 0 1-.483-1.34l2.123-4.567a1.004 1.004 0 0 1 1.339-.474");
}

.cw3sn1brq {
  d: path("m9 16.078l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.cwmsguygo {
  stop-color: var(--svg-color--ff7d48, #FF7D48);
  stop-opacity: 0;
}

.d-by8cbiw {
  stop-color: var(--svg-color--9d7d73, #9D7D73);
}

.d3plm5x9f {
  stop-color: var(--svg-color--9c7b72, #9C7B72);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dodqfog5q {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e-zb_sb0t {
  d: path("m15.504 12.458l-.683 2.361c-.139.486.196.972.67.972H16.5c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.829-.524-.982 0");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3jco7qba {
  d: path("M24.75 19.811a.885.885 0 0 1 .35-1.203l2.609-1.428a.899.899 0 1 1 .856 1.581l-2.621 1.404a.885.885 0 0 1-1.194-.354");
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e5ucantjx {
  d: path("M22.239 14.96c.43-.014.833-.16 1.161-.396v1.195a2.79 2.79 0 0 1-1.722 2.593c.219-.465.37-.973.444-1.515z");
}

.ebo5c_0lf {
  fill: var(--svg-color--000, #000);
  d: path("M13.847 12.893a.654.654 0 0 0-.657-.657a.654.654 0 0 0-.583.959h1.162a.65.65 0 0 0 .078-.302");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f1gbiwx_q {
  stop-color: var(--svg-color--6a3849, #6A3849);
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdhnkacbc {
  fill: var(--svg-color--2f1e1d, #2F1E1D);
  d: path("M20.711 9.94a.35.35 0 0 0-.25-.426l-2.086-.542a.349.349 0 0 0-.175.675l2.086.542a.35.35 0 0 0 .425-.249");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fqu12ubrd {
  d: path("M13.19 11.747a1.146 1.146 0 0 0-1.104 1.448H14.3q.04-.147.041-.302a1.154 1.154 0 0 0-1.15-1.147");
}

.ft5dv1b6b {
  fill: none;
}

.g4wyz37uu {
  stop-color: var(--svg-color--8f655e, #8F655E);
}

.gd1of5hxe {
  stop-color: var(--svg-color--eb4e66, #EB4E66);
}

.gspwrdz1o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.836 9.76l2.017-.534");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hdh7eybjd {
  stop-color: var(--svg-color--9c7b72, #9C7B72);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hqjfx29jv {
  stop-color: var(--svg-color--9d7d73, #9D7D73);
  stop-opacity: 0;
}

.i26rr_0fw {
  stop-color: var(--svg-color--b9321e, #B9321E);
}

.i4fzwzbpd {
  d: path("M7.152 19.747c.236-.43.228-.904-.201-1.14L4.342 17.18a.899.899 0 1 0-.856 1.581l2.622 1.404c.427.229.81.007 1.044-.418");
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibf0x1bat {
  d: path("M9.526 11.817a1.228 1.228 0 0 0 .107 2.413a100 100 0 0 1-.107-2.413");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iitgd8bac {
  fill: var(--svg-color--000, #000);
  d: path("M18.144 12.893c0-.365.291-.657.656-.657a.654.654 0 0 1 .584.959h-1.162a.6.6 0 0 1-.078-.302");
}

.inmwvkbzn {
  stop-color: var(--svg-color--916a5a, #916A5A);
}

.j_0xl5h8m {
  d: path("M26.653 15.73c.527-.847 1.795-1.665 2.462-1.988a.13.13 0 0 1 .152.034a.132.132 0 0 1-.033.196c-2.06 1.273-1.875 1.785-2.645 3.097c-.355.604-1.177 1.112-1.556 1.284l-.474-.899c.53-.28 1.462-.711 2.094-1.725");
}

.j7pnfkbxw {
  stop-color: var(--svg-color--804776, #804776);
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jmecmib9q {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m22.69 10.474l-.038-.811c-.014-.98-.824-1.79-1.805-1.83H19.05a3.11 3.11 0 0 1-2.728-1.619s-.16-.372-.258-.96c-.165-.989.75-1.717 1.74-1.554c1.354.222 3.024.66 4.218 1.438c2.24 1.462 1.848 4.095.669 5.336");
}

.jqtuckbvl {
  fill: var(--svg-color--2f1e1d, #2F1E1D);
  d: path("M11.388 9.94a.35.35 0 0 1 .25-.426l2.086-.542a.349.349 0 1 1 .175.675l-2.086.542a.35.35 0 0 1-.425-.249");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jz-x_6ndp {
  stop-color: var(--svg-color--463c3b, #463C3B);
  stop-opacity: 0;
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kd1_xhb_o {
  stop-color: var(--svg-color--ff4c31, #FF4C31);
}

.ktas3sbvn {
  stop-color: var(--svg-color--ffa842, #FFA842);
  stop-opacity: 0;
}

.l3e-mtbcj {
  d: path("M9.513 10.96a2.08 2.08 0 0 0-1.784 2.053c0 1.103.864 2.005 1.953 2.063a101 101 0 0 1-.17-4.115");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_8hwoksz {
  stop-color: var(--svg-color--f54617, #F54617);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m754bqf9r {
  stop-color: var(--svg-color--734a39, #734A39);
  stop-opacity: 0;
}

.m7o64xbbx {
  stop-color: var(--svg-color--ff4923, #FF4923);
}

.ma1u1iuqv {
  stop-color: var(--svg-color--7e4a51, #7E4A51);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mq0gl8bsz {
  stop-color: var(--svg-color--e4764e, #E4764E);
}

.myckyxb_u {
  stop-color: var(--svg-color--713e45, #713E45);
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n39i5izax {
  stop-color: var(--svg-color--704b3d, #704B3D);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nl8aomm7e {
  d: path("M22.316 15.077q.129-2.05.237-4.099a2.067 2.067 0 0 1-.237 4.099");
}

.nsn8oes0z {
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omftgvbac {
  d: path("M9.798 16.906a5.03 5.03 0 0 0 4.99 4.374h2.424a5.03 5.03 0 0 0 4.99-4.374c.152-2.42.304-4.829.417-7.247a1.86 1.86 0 0 0-1.771-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34c0 2.39.15 4.74.306 7.136");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.prd44wbso {
  stop-color: var(--svg-color--ff9540, #FF9540);
}

.psrrqcksv {
  stop-color: var(--svg-color--ff730a, #FF730A);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q_yq25bad {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("M16.294 6.143a3 3 0 0 1-.085-.176a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34v.353c-.436-.333-.986-1.033-.986-2.168c0-1.376 1.004-2.072 1.645-2.516c.18-.125.332-.23.425-.325l.128-.135c.448-.476 1.248-1.324 2.645-1.695a7.2 7.2 0 0 1 2.167-.203c.472.026.805.434.805.907v2.137z");
}

.q5hvggldb {
  d: path("M14.237 12.758c0-.37-.3-.617-.382-.692l-.37.358l.227.464z");
}

.q9mg64b4e {
  stop-color: var(--svg-color--f35e74, #F35E74);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qltvyfb3b {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.504 12.458l-.683 2.361c-.139.486.196.972.67.972H16.5c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.829-.524-.982 0");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.qxiqgebpn {
  stop-color: var(--svg-color--ff6732, #FF6732);
}

.qyctpef7w {
  stop-color: var(--svg-color--9a7b71, #9A7B71);
}

.r8d20-6qp {
  stop-color: var(--svg-color--8d6d68, #8D6D68);
  stop-opacity: 0;
}

.rbbulnz3l {
  d: path("M16.294 6.143a3 3 0 0 1-.085-.176a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34v.353c-.436-.333-.986-1.033-.986-2.168c0-1.376 1.004-2.072 1.645-2.516c.18-.125.332-.23.425-.325l.128-.135c.448-.476 1.248-1.324 2.645-1.695a7.2 7.2 0 0 1 2.167-.203c.472.026.805.434.805.907v2.137z");
}

.rbkr51v-c {
  stop-color: var(--svg-color--ff730a, #FF730A);
  stop-opacity: 0;
}

.rizivib-o {
  stop-color: var(--svg-color--7e4a51, #7E4A51);
  stop-opacity: 0;
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.s0h6qabck {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.37 12.689l-.815 2.36c-.139.486.196.972.67.972h1.009c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.696-.524-.85 0");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sghkjcc6n {
  stop-color: var(--svg-color--704b3d, #704B3D);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.smo9u60ba {
  stop-color: var(--svg-color--ffa842, #FFA842);
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.sy-f5ccgl {
  stop-color: var(--svg-color--e76b2f, #E76B2F);
}

.t-faq4izi {
  d: path("m22.69 10.474l-.038-.811c-.014-.98-.824-1.79-1.805-1.83H19.05a3.11 3.11 0 0 1-2.728-1.619s-.16-.372-.258-.96c-.165-.989.75-1.717 1.74-1.554c1.354.222 3.024.66 4.218 1.438c2.24 1.462 1.848 4.095.669 5.336");
}

.t0_upib5g {
  d: path("M19.823 12.744a1.1 1.1 0 0 0-.298-.596l-.335.367l.151.294z");
}

.t0phas2np {
  stop-color: var(--svg-color--694641, #694641);
}

.tmrtimg7x {
  d: path("M22.367 14.24q.076-1.221.142-2.444a1.227 1.227 0 0 1-.142 2.445");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.twmiqpbxq {
  d: path("m25.19 20.578l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.u1hhhxbfd {
  stop-color: var(--svg-color--e2632d, #E2632D);
}

.u4cp3820t {
  d: path("m6.81 20.578l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.u9mvxzbci {
  stop-color: var(--svg-color--592f28, #592F28);
  stop-opacity: 0;
}

.ub8ckabiz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.924 11.398c-.838 0-1.547.578-1.74 1.36a.352.352 0 0 0 .344.437h2.866a.296.296 0 0 0 .291-.35a1.8 1.8 0 0 0-1.76-1.447");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.utrmehb1k {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.066 11.398c.839 0 1.547.578 1.74 1.36a.352.352 0 0 1-.344.437h-2.865a.296.296 0 0 1-.292-.35a1.795 1.795 0 0 1 1.76-1.447");
}

.uv3zckjhy {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M15.989 19.458c.791 0 1.433-.688 1.433-1.537c0-.85-.642-1.538-1.433-1.538s-1.433.688-1.433 1.538c0 .849.642 1.537 1.433 1.537");
}

.v1z821b6o {
  stop-color: var(--svg-color--eb4e66, #EB4E66);
  stop-opacity: 0;
}

.v3bwo4btz {
  stop-color: var(--svg-color--ff7132, #FF7132);
}

.v3eonib4h {
  d: path("M20.44 16.106L5.033 23.28a3.53 3.53 0 0 0-1.7 4.69a3.516 3.516 0 0 0 4.679 1.705l15.407-7.182c.503-.232.724-.837.483-1.342l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vhav-abny {
  stop-color: var(--svg-color--734a39, #734A39);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vzmhuwavr {
  stop-color: var(--svg-color--f35e74, #F35E74);
  stop-opacity: 0;
}

.vzu9-mfnh {
  d: path("m23 16.078l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.w_6w3opsv {
  stop-color: var(--svg-color--592f28, #592F28);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-vsz3bnm {
  stop-color: var(--svg-color--e4764e, #E4764E);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w58mn6r_g {
  stop-color: var(--svg-color--ff9a32, #FF9A32);
}

.w73iq3bud {
  fill: var(--svg-color--f53b19, #F53B19);
  d: path("M25.5 30.008h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.whmlezbbn {
  stop-color: var(--svg-color--8d6d68, #8D6D68);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wq0eljlkx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.263 9.76l-2.017-.534");
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xrn2z6b6u {
  stop-color: var(--svg-color--ff8c11, #FF8C11);
  stop-opacity: 0;
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y5l4vob7e {
  stop-color: var(--svg-color--7e4a52, #7E4A52);
}

.yemvrmxbd {
  stop-color: var(--svg-color--7e4a52, #7E4A52);
  stop-opacity: 0;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z-qcyfbze {
  cx: 12.844px;
  cy: 12.236px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.5px;
  ry: 0.253px;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
