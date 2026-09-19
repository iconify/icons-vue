<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iT6kUee)" class="e5ucantjx"/><path fill="url(#i3qRNTb)" class="a6yq75bbi"/><g filter="url(#iAb8vwb)"><path fill="url(#iu3Bnyc)" class="omftgvbac"/></g><path fill="url(#i4DNdYc)" class="omftgvbac"/><path fill="url(#i7nvwJe)" class="omftgvbac"/><path fill="url(#iR9fpWb)" class="omftgvbac"/><path fill="url(#iojhEFb)" class="omftgvbac"/><path fill="url(#iD4l1cd)" class="omftgvbac"/><path fill="url(#iIpT8te)" class="omftgvbac"/><path fill="url(#iaOuFYb)" class="omftgvbac"/><path fill="url(#iQw3iDb)" class="omftgvbac"/><path fill="url(#iXiJpXd)" class="omftgvbac"/><g filter="url(#ienfj5b)"><path class="u5the8b6m"/></g><g filter="url(#igJ3z5g)"><path class="nk372pbat"/><path fill="url(#iuBaLTc)" class="ofx_u9bwq"/><path fill="url(#iD63YMb)" class="ofx_u9bwq"/><path fill="url(#iTCVlid)" class="ofx_u9bwq"/><path fill="url(#ilCuYEb)" class="ofx_u9bwq"/><path fill="url(#itLvxfe)" class="ofx_u9bwq"/></g><g filter="url(#iKBgOTc)"><path fill="url(#iOdqWdd)" class="dx6yu9cnd"/><path fill="url(#iCDNjgc)" class="dx6yu9cnd"/><path fill="url(#iw43Bzb)" class="dx6yu9cnd"/><path fill="url(#i9o9XPd)" class="dx6yu9cnd"/><path fill="url(#izmLBvd)" class="dx6yu9cnd"/></g><g filter="url(#iRDmQhe)"><path class="ww2kv0bto"/><path fill="url(#ilqQ6Nb)" class="rbbulnz3l"/><path fill="url(#iMydfGc)" class="rbbulnz3l"/></g><g filter="url(#iphBApb)"><path class="m_ovc62ju"/><path fill="url(#iQKLrob)" class="t-faq4izi"/><path fill="url(#iDiRxhc)" class="t-faq4izi"/><path fill="url(#igGkLzc)" class="t-faq4izi"/></g><path class="utrmehb1k"/><path fill="url(#iPjnENe)" class="cswzjcx6u"/><path class="iitgd8bac"/><g filter="url(#iVoS3Xd)"><path class="dodqfog5q"/><path fill="url(#i9QUMfK)" class="nsn8oes0z"/></g><g filter="url(#igIXigb)"><path fill="url(#iKnUjve)" class="t0_upib5g"/></g><path class="ub8ckabiz"/><path fill="url(#iOPziAb)" class="fqu12ubrd"/><path class="ebo5c_0lf"/><g filter="url(#iruKohb)"><path fill="url(#i7aVE8b)" class="q5hvggldb"/></g><g filter="url(#ivbmfLD)"><ellipse transform="rotate(-27.914 12.844 12.236)" class="z-qcyfbze"/><ellipse fill="url(#i8Ldsle)" transform="rotate(-27.914 12.844 12.236)" class="a3xscqbym"/></g><path fill="url(#iDsBVLb)" class="nl8aomm7e"/><path fill="url(#it8cTDb)" class="nl8aomm7e"/><path fill="url(#ikOSjml)" class="nl8aomm7e"/><path fill="url(#iJxktPd)" class="nl8aomm7e"/><path fill="url(#iUF9DtR)" class="kxyn74b4t"/><path fill="url(#iaIc6hc)" class="kxyn74b4t"/><g filter="url(#idR256v)"><path fill="url(#i6Bojlb)" class="um2k303ln"/></g><g filter="url(#iZTqKxd)"><path fill="url(#iNkBD3A)" class="tmrtimg7x"/></g><g filter="url(#iWjvpnd)"><path class="aat5s3d3v"/></g><g filter="url(#iUGrUre)"><path class="q_zb4wpiz"/></g><g filter="url(#iFixTec)"><path stroke="url(#iWnIcyH)" class="gspwrdz1o"/></g><g filter="url(#iGDVpDd)"><path stroke="url(#iLuuInb)" class="wq0eljlkx"/></g><path class="cgq0w6bpf"/><path class="w73iq3bud"/><path fill="url(#iY2ScGe)" class="akki1obxr"/><path fill="url(#inirSwb)" class="akki1obxr"/><path fill="url(#ikeLGbe)" class="u4cp3820t"/><path fill="url(#ihqOLGc)" class="cuomu7bqz"/><path fill="url(#iRbdh4d)" class="cuomu7bqz"/><path fill="url(#i16tupc)" class="cuomu7bqz"/><path fill="url(#isBeo5c)" class="cuomu7bqz"/><path fill="url(#izAvOPb)" class="cuomu7bqz"/><path fill="url(#igdf08b)" class="cuomu7bqz"/><path fill="url(#iiwVwQd)" class="twmiqpbxq"/><path fill="url(#iDDcgbe)" class="v3eonib4h"/><path fill="url(#iwGAPQd)" class="v3eonib4h"/><path fill="url(#ixh7Cge)" class="v3eonib4h"/><path fill="url(#iCA2ycb)" class="e3jco7qba"/><path fill="url(#inBpZ2t)" class="e3jco7qba"/><path fill="url(#inu29Tb)" class="e3jco7qba"/><path fill="url(#iNbfGdc)" class="i4fzwzbpd"/><path fill="url(#iMR1U6b)" class="i4fzwzbpd"/><path fill="url(#ipksTOc)" class="vzu9-mfnh"/><path fill="url(#iUraDKd)" class="vzu9-mfnh"/><path fill="url(#ilEGLxb)" class="vzu9-mfnh"/><g filter="url(#iDtPqTd)"><path fill="url(#iqaftOG)" class="cw3sn1brq"/><path fill="url(#i20yS7d)" class="cw3sn1brq"/></g><path fill="url(#iY08Qdd)" class="cw3sn1brq"/><g filter="url(#ifqEshb)"><path fill="url(#iwNFpkb)" class="j_0xl5h8m"/></g><defs><radialGradient id="iT6kUee" cx="0" cy="0" r="1" gradientTransform="matrix(.96166 2.5937 -3.08112 1.14238 22.1 14.564)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="i3qRNTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.89623 .59596 -1.83857 5.85 8.217 15.194)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iu3Bnyc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.71417 0 0 -11.8773 19.601 13.355)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="i7nvwJe" cx="0" cy="0" r="1" gradientTransform="rotate(94.704 6.36 11.182)scale(16.0095 13.2578)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="iR9fpWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.47484 1.82511 0 19.138 11.669)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iojhEFb" cx="0" cy="0" r="1" gradientTransform="matrix(.00505 -1.4054 1.5294 .0055 13.041 11.729)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iD4l1cd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.971 7.634)scale(10.9332 27.9288)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iIpT8te" cx="0" cy="0" r="1" gradientTransform="matrix(5.23098 -3.40122 1.24509 1.9149 8.973 7.8)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iaOuFYb" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.184 15.327)scale(3.2216 1.28781)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iQw3iDb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23876 3.7026 -3.0568 -1.84827 19.112 6.96)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iXiJpXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.47939 8.89382 0 16.055 21.28)" gradientUnits="userSpaceOnUse"><stop class="xc3cwzl8h"/><stop offset=".264" class="e1s_iwb5s"/><stop offset=".647" class="zr40zg26a"/></radialGradient><radialGradient id="iD63YMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3135 -.9853 0 16.594 15.102)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="ilCuYEb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.95362 .89572 -1.43949 -3.13962 16.743 14.37)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iCDNjgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.49678 11.3718 0 9.279 9.64)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iw43Bzb" cx="0" cy="0" r="1" gradientTransform="matrix(.14646 -3.22688 5.7174 .2595 22.238 11.323)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i9o9XPd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02947 -1.99249 1.46259 -2.22378 21.269 3.262)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="izmLBvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.16245 1.89434 -4.3864 2.69168 14.832 1.217)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="ilqQ6Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.82692 0 0 -1.04918 16.32 4.119)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iMydfGc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.84 -3.592)scale(7.74003 8.57516)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iQKLrob" cx="0" cy="0" r="1" gradientTransform="matrix(3.92791 0 0 1.53575 20.38 5.252)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iDiRxhc" cx="0" cy="0" r="1" gradientTransform="matrix(3.4403 -3.27777 6.00076 6.29832 19.377 9.153)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="igGkLzc" cx="0" cy="0" r="1" gradientTransform="matrix(4.17171 .4876 -.20415 1.74662 18.24 7.256)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iPjnENe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04198 -1.65739 0 18.798 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i9QUMfK" cx="0" cy="0" r="1" gradientTransform="matrix(-.29785 -.38382 .52843 -.41007 18.504 12.467)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOPziAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04204 -1.65748 0 13.193 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8Ldsle" cx="0" cy="0" r="1" gradientTransform="matrix(-.00994 -.63455 .76277 -.01194 12.825 12.642)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="it8cTDb" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 2.921 20.555)scale(2.99201 2.85461)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="ikOSjml" cx="0" cy="0" r="1" gradientTransform="matrix(1.01175 -1.38847 1.16382 .84805 22.388 12.895)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iJxktPd" cx="0" cy="0" r="1" gradientTransform="rotate(-69.263 20.763 -9.755)scale(2.12915 2.84485)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iaIc6hc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -.475 9.995)scale(2.71847 2.67251)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="i6Bojlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17705 .20204 -.08911 -.51914 9.745 13.023)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="iY2ScGe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.445)" gradientUnits="userSpaceOnUse"><stop class="prd44wbso"/><stop offset="1" class="c5khawelw"/></radialGradient><radialGradient id="inirSwb" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.227)" gradientUnits="userSpaceOnUse"><stop class="u1hhhxbfd"/><stop offset="1" class="cl_cdxbgs"/></radialGradient><radialGradient id="ikeLGbe" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 1.25 -2.6929 5.58776 8.406 17.32)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="sy-f5ccgl"/><stop offset="1" class="i26rr_0fw"/></radialGradient><radialGradient id="ihqOLGc" cx="0" cy="0" r="1" gradientTransform="matrix(17.51082 8.75543 -2.15289 4.30577 13.551 19.209)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="v3bwo4btz"/><stop offset="1" class="kd1_xhb_o"/></radialGradient><radialGradient id="iRbdh4d" cx="0" cy="0" r="1" gradientTransform="rotate(159.944 11.543 15.187)scale(2.90693 2.17455)" gradientUnits="userSpaceOnUse"><stop class="cq9p23brg"/><stop offset="1" class="cwmsguygo"/></radialGradient><radialGradient id="i16tupc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11963 5.31578 -8.32746 -1.75396 14.245 17.692)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="w58mn6r_g"/><stop offset="1" class="xrn2z6b6u"/></radialGradient><radialGradient id="izAvOPb" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.455 -3.07)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="mq0gl8bsz"/><stop offset="1" class="w-vsz3bnm"/></radialGradient><radialGradient id="iiwVwQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 .6475 -1.4343 -3.32276 24.094 18.195)" gradientUnits="userSpaceOnUse"><stop class="qxiqgebpn"/><stop offset="1" class="m_8hwoksz"/></radialGradient><radialGradient id="iDDcgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.883)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="jbd_cz55y"/><stop offset="1" class="m7o64xbbx"/></radialGradient><radialGradient id="iCA2ycb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.469)" gradientUnits="userSpaceOnUse"><stop class="thafvacgt"/><stop offset=".615" class="n42kk7pqk"/></radialGradient><radialGradient id="iNbfGdc" cx="0" cy="0" r="1" gradientTransform="matrix(1.74664 .85478 -1.17534 2.40165 3.176 17.648)" gradientUnits="userSpaceOnUse"><stop class="camp3gbri"/><stop offset=".697" class="d-rprdjqx"/></radialGradient><radialGradient id="iMR1U6b" cx="0" cy="0" r="1" gradientTransform="rotate(162.607 1.083 8.97)scale(.89785 1.70016)" gradientUnits="userSpaceOnUse"><stop class="lqt9uqtub"/><stop offset="1" class="off4cm2_g"/></radialGradient><radialGradient id="ipksTOc" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.294 6.356)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="sq5l9g8_d"/><stop offset="1" class="sst8orbli"/></radialGradient><radialGradient id="iUraDKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07812 .5625 -.19373 -.37132 30 13.273)" gradientUnits="userSpaceOnUse"><stop class="kbuu85jbe"/><stop offset="1" class="q59v_vbuo"/></radialGradient><radialGradient id="i20yS7d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.288)" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="gxtn60bqm"/></radialGradient><radialGradient id="iY08Qdd" cx="0" cy="0" r="1" gradientTransform="matrix(1.05293 -.08258 .27016 3.4445 4.334 18.013)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="ryyyekfgi"/><stop offset="1" class="bhv0cwbcf"/></radialGradient><linearGradient id="i4DNdYc" x1="22.619" x2="17.028" y1="15.52" y2="15.52" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iuBaLTc" x1="17.072" x2="15.995" y1="14.222" y2="14.266" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iTCVlid" x1="15.995" x2="15.995" y1="15.685" y2="15.087" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="itLvxfe" x1="15.995" x2="15.995" y1="11.89" y2="12.912" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iOdqWdd" x1="24.795" x2="9.881" y1="6.082" y2="6.082" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iKnUjve" x1="19.798" x2="19.394" y1="12.429" y2="12.678" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7aVE8b" x1="14.148" x2="13.745" y1="12.428" y2="12.677" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDsBVLb" x1="24.261" x2="22.711" y1="12.282" y2="15.077" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iUF9DtR" x1="8.482" x2="10.355" y1="13.185" y2="13.022" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iNkBD3A" x1="22.975" x2="22.975" y1="11.796" y2="14.241" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iWnIcyH" x1="13.921" x2="11.175" y1="9.208" y2="9.928" gradientUnits="userSpaceOnUse"><stop offset=".333" class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="iLuuInb" x1="18.178" x2="20.924" y1="9.208" y2="9.928" gradientUnits="userSpaceOnUse"><stop offset=".333" class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="isBeo5c" x1="9.156" x2="10.344" y1="18.508" y2="18.883" gradientUnits="userSpaceOnUse"><stop class="psrrqcksv"/><stop offset="1" class="rbkr51v-c"/></linearGradient><linearGradient id="igdf08b" x1="17.406" x2="17.906" y1="26.977" y2="25.758" gradientUnits="userSpaceOnUse"><stop class="gd1of5hxe"/><stop offset="1" class="v1z821b6o"/></linearGradient><linearGradient id="iwGAPQd" x1="14.83" x2="14.461" y1="26.816" y2="25.927" gradientUnits="userSpaceOnUse"><stop class="q9mg64b4e"/><stop offset="1" class="vzmhuwavr"/></linearGradient><linearGradient id="ixh7Cge" x1="22.827" x2="21.613" y1="18.819" y2="19.382" gradientUnits="userSpaceOnUse"><stop class="smo9u60ba"/><stop offset="1" class="ktas3sbvn"/></linearGradient><linearGradient id="inBpZ2t" x1="28.085" x2="27.547" y1="19.514" y2="18.683" gradientUnits="userSpaceOnUse"><stop offset=".198" class="jkm4jmgye"/><stop offset="1" class="svnghenix"/></linearGradient><linearGradient id="inu29Tb" x1="26.75" x2="27.494" y1="17.398" y2="18.158" gradientUnits="userSpaceOnUse"><stop offset=".353" class="mfwhtqbpf"/><stop offset="1" class="f2y_cno1u"/></linearGradient><linearGradient id="ilEGLxb" x1="25.489" x2="25.997" y1="14.289" y2="15.189" gradientUnits="userSpaceOnUse"><stop class="xlrzicczw"/><stop offset="1" class="ikzehdbwc"/></linearGradient><linearGradient id="iqaftOG" x1="8" x2="4.375" y1="15.758" y2="20.008" gradientUnits="userSpaceOnUse"><stop offset=".206" class="gbpxfde5c"/><stop offset="1" class="fz359gsqc"/></linearGradient><linearGradient id="iwNFpkb" x1="29.179" x2="24.036" y1="14.953" y2="17.82" gradientUnits="userSpaceOnUse"><stop class="ept1d-nvv"/><stop offset="1" class="z2eb7q_dp"/></linearGradient><filter id="iAb8vwb" width="14.126" height="16.05" x="9.492" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24794"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24794" result="effect2_innerShadow_3987_24794"/></filter><filter id="ienfj5b" width="4.411" height="5.725" x="13.524" y="11.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".5"/></filter><filter id="igJ3z5g" width="2.811" height="4.125" x="14.59" y="11.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".1"/></filter><filter id="iKBgOTc" width="16.532" height="10.59" x="7.729" y="1.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24794"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24794" result="effect2_innerShadow_3987_24794"/></filter><filter id="iRDmQhe" width="8.814" height="8.053" x="8.006" y="2.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24794"/><feGaussianBlur result="effect2_foregroundBlur_3987_24794" stdDeviation=".25"/></filter><filter id="iphBApb" width="8.596" height="7.796" x="15.543" y="3.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".25"/></filter><filter id="iVoS3Xd" width=".954" height=".837" x="17.883" y="11.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".05"/></filter><filter id="igIXigb" width="1.033" height="1.061" x="18.99" y="11.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".1"/></filter><filter id="iruKohb" width="1.153" height="1.222" x="13.284" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".1"/></filter><filter id="ivbmfLD" width="1.116" height=".848" x="12.286" y="11.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".05"/></filter><filter id="idR256v" width="1.565" height="2.914" x="8.318" y="11.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".125"/></filter><filter id="iZTqKxd" width="2.216" height="3.444" x="21.867" y="11.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".25"/></filter><filter id="iWjvpnd" width="2.884" height="1.34" x="11.376" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24794"/></filter><filter id="iUGrUre" width="2.884" height="1.34" x="17.939" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24794"/></filter><filter id="iFixTec" width="2.717" height="1.234" x="11.486" y="8.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".125"/></filter><filter id="iGDVpDd" width="2.717" height="1.234" x="17.896" y="8.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".125"/></filter><filter id="iDtPqTd" width="7.3" height="8.016" x="2" y="12.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.137255 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24794"/></filter><filter id="ifqEshb" width="5.538" height="5.423" x="24.159" y="13.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24794" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-no-dark" /></template>
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

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a6yq75bbi {
  d: path("M9.752 14.96a2.1 2.1 0 0 1-1.162-.396v1.195a2.79 2.79 0 0 0 1.722 2.593a5.3 5.3 0 0 1-.444-1.515z");
}

.aat5s3d3v {
  fill: var(--svg-color--0b090a, #0B090A);
  d: path("M11.388 9.94a.35.35 0 0 1 .25-.426l2.086-.542a.349.349 0 1 1 .175.675l-2.086.542a.35.35 0 0 1-.425-.249");
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akki1obxr {
  d: path("M25.5 30.008h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bhv0cwbcf {
  stop-color: var(--svg-color--53403d, #53403D);
  stop-opacity: 0;
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c5khawelw {
  stop-color: var(--svg-color--ff9540, #FF9540);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.camp3gbri {
  stop-color: var(--svg-color--402f2d, #402F2D);
}

.cgq0w6bpf {
  fill: var(--svg-color--290018, #290018);
  d: path("M15.989 19.458c.791 0 1.433-.688 1.433-1.537c0-.85-.642-1.538-1.433-1.538s-1.433.688-1.433 1.538c0 .849.642 1.537 1.433 1.537");
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

.d-rprdjqx {
  stop-color: var(--svg-color--311a22, #311A22);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dodqfog5q {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dwxodwo3m {
  stop-color: var(--svg-color--343434, #343434);
}

.dx6yu9cnd {
  d: path("M22.23 4.823c.66.228 1.253.69 1.628 1.35a3.04 3.04 0 0 1-.136 3.245a2 2 0 0 0-.348 1.123v1.526a2.2 2.2 0 0 0-.856-.345l.1-2.063a1.86 1.86 0 0 0-1.77-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34l.04 1.974c-.327.048-.667.157-.925.338v-1.541c0-.4-.123-.792-.348-1.123a3.07 3.07 0 0 1-.184-3.141a3 3 0 0 1 1.67-1.447a3.44 3.44 0 0 0 1.777-1.426a2.99 2.99 0 0 1 2.534-1.412c.416 0 .81.09 1.179.241c.49.214 1.042.214 1.532 0a3 3 0 0 1 1.172-.24c1.083 0 2.03.585 2.554 1.453a3.24 3.24 0 0 0 1.737 1.377");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1s_iwb5s {
  stop-color: var(--svg-color--4a1c1c, #4A1C1C);
}

.e3jco7qba {
  d: path("M24.75 19.811a.885.885 0 0 1 .35-1.203l2.609-1.428a.899.899 0 1 1 .856 1.581l-2.621 1.404a.885.885 0 0 1-1.194-.354");
}

.e5ucantjx {
  d: path("M22.239 14.96c.43-.014.833-.16 1.161-.396v1.195a2.79 2.79 0 0 1-1.722 2.593c.219-.465.37-.973.444-1.515z");
}

.ebo5c_0lf {
  fill: var(--svg-color--000, #000);
  d: path("M13.847 12.893a.654.654 0 0 0-.657-.657a.654.654 0 0 0-.583.959h1.162a.65.65 0 0 0 .078-.302");
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ept1d-nvv {
  stop-color: var(--svg-color--655351, #655351);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f2y_cno1u {
  stop-color: var(--svg-color--33211e, #33211E);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fqu12ubrd {
  d: path("M13.19 11.747a1.146 1.146 0 0 0-1.104 1.448H14.3q.04-.147.041-.302a1.154 1.154 0 0 0-1.15-1.147");
}

.ft5dv1b6b {
  fill: none;
}

.fz359gsqc {
  stop-color: var(--svg-color--391d25, #391D25);
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.gbpxfde5c {
  stop-color: var(--svg-color--4f312d, #4F312D);
}

.gd1of5hxe {
  stop-color: var(--svg-color--eb4e66, #EB4E66);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gspwrdz1o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.836 9.76l2.017-.534");
}

.gxtn60bqm {
  stop-color: var(--svg-color--635251, #635251);
  stop-opacity: 0;
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i26rr_0fw {
  stop-color: var(--svg-color--b9321e, #B9321E);
}

.i4fzwzbpd {
  d: path("M7.152 19.747c.236-.43.228-.904-.201-1.14L4.342 17.18a.899.899 0 1 0-.856 1.581l2.622 1.404c.427.229.81.007 1.044-.418");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iitgd8bac {
  fill: var(--svg-color--000, #000);
  d: path("M18.144 12.893c0-.365.291-.657.656-.657a.654.654 0 0 1 .584.959h-1.162a.6.6 0 0 1-.078-.302");
}

.ikzehdbwc {
  stop-color: var(--svg-color--3a221f, #3A221F);
  stop-opacity: 0;
}

.j_0xl5h8m {
  d: path("M26.653 15.73c.527-.847 1.795-1.665 2.462-1.988a.13.13 0 0 1 .152.034a.132.132 0 0 1-.033.196c-2.06 1.273-1.875 1.785-2.645 3.097c-.355.604-1.177 1.112-1.556 1.284l-.474-.899c.53-.28 1.462-.711 2.094-1.725");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jkm4jmgye {
  stop-color: var(--svg-color--3e2124, #3E2124);
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kbuu85jbe {
  stop-color: var(--svg-color--624e4c, #624E4C);
}

.kd1_xhb_o {
  stop-color: var(--svg-color--ff4c31, #FF4C31);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.ktas3sbvn {
  stop-color: var(--svg-color--ffa842, #FFA842);
  stop-opacity: 0;
}

.kxyn74b4t {
  d: path("M9.504 10.967a2.067 2.067 0 0 0 .178 4.11a100 100 0 0 1-.178-4.11");
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqt9uqtub {
  stop-color: var(--svg-color--210f10, #210F10);
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m_8hwoksz {
  stop-color: var(--svg-color--f54617, #F54617);
}

.m_ovc62ju {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m22.69 10.474l-.038-.811c-.014-.98-.824-1.79-1.805-1.83H19.05a3.11 3.11 0 0 1-2.728-1.619s-.16-.372-.258-.96c-.165-.989.75-1.717 1.74-1.554c1.354.222 3.024.66 4.218 1.438c2.24 1.462 1.848 4.095.669 5.336");
}

.m7o64xbbx {
  stop-color: var(--svg-color--ff4923, #FF4923);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mfwhtqbpf {
  stop-color: var(--svg-color--33211e, #33211E);
}

.mq0gl8bsz {
  stop-color: var(--svg-color--e4764e, #E4764E);
}

.n42kk7pqk {
  stop-color: var(--svg-color--472c31, #472C31);
}

.nk372pbat {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.504 12.437l-.682 2.361c-.14.486.195.971.668.971h1.01c.474 0 .808-.493.669-.971l-.683-2.361c-.146-.523-.829-.523-.982 0");
}

.nl8aomm7e {
  d: path("M22.316 15.077q.129-2.05.237-4.099a2.067 2.067 0 0 1-.237 4.099");
}

.ns3cxsbdp {
  stop-color: var(--svg-color--343434, #343434);
  stop-opacity: 0;
}

.nsn8oes0z {
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.off4cm2_g {
  stop-color: var(--svg-color--210f10, #210F10);
  stop-opacity: 0;
}

.ofx_u9bwq {
  d: path("m15.504 12.437l-.682 2.361c-.14.486.195.971.668.971h1.01c.474 0 .808-.493.669-.971l-.683-2.361c-.146-.523-.829-.523-.982 0");
}

.omftgvbac {
  d: path("M9.798 16.906a5.03 5.03 0 0 0 4.99 4.374h2.424a5.03 5.03 0 0 0 4.99-4.374c.152-2.42.304-4.829.417-7.247a1.86 1.86 0 0 0-1.771-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34c0 2.39.15 4.74.306 7.136");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prd44wbso {
  stop-color: var(--svg-color--ff9540, #FF9540);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.psrrqcksv {
  stop-color: var(--svg-color--ff730a, #FF730A);
}

.q_zb4wpiz {
  fill: var(--svg-color--0b090a, #0B090A);
  d: path("M20.711 9.94a.35.35 0 0 0-.25-.426l-2.086-.542a.349.349 0 0 0-.175.675l2.086.542a.35.35 0 0 0 .425-.249");
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q59v_vbuo {
  stop-color: var(--svg-color--624e4c, #624E4C);
  stop-opacity: 0;
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

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxiqgebpn {
  stop-color: var(--svg-color--ff6732, #FF6732);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rbbulnz3l {
  d: path("M16.294 6.143a3 3 0 0 1-.085-.176a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34v.353c-.436-.333-.986-1.033-.986-2.168c0-1.376 1.004-2.072 1.645-2.516c.18-.125.332-.23.425-.325l.128-.135c.448-.476 1.248-1.324 2.645-1.695a7.2 7.2 0 0 1 2.167-.203c.472.026.805.434.805.907v2.137z");
}

.rbkr51v-c {
  stop-color: var(--svg-color--ff730a, #FF730A);
  stop-opacity: 0;
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.ryyyekfgi {
  stop-color: var(--svg-color--53403d, #53403D);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.smo9u60ba {
  stop-color: var(--svg-color--ffa842, #FFA842);
}

.sq5l9g8_d {
  stop-color: var(--svg-color--533836, #533836);
}

.sst8orbli {
  stop-color: var(--svg-color--432e2b, #432E2B);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.svnghenix {
  stop-color: var(--svg-color--3e2124, #3E2124);
  stop-opacity: 0;
}

.sy-f5ccgl {
  stop-color: var(--svg-color--e76b2f, #E76B2F);
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t-faq4izi {
  d: path("m22.69 10.474l-.038-.811c-.014-.98-.824-1.79-1.805-1.83H19.05a3.11 3.11 0 0 1-2.728-1.619s-.16-.372-.258-.96c-.165-.989.75-1.717 1.74-1.554c1.354.222 3.024.66 4.218 1.438c2.24 1.462 1.848 4.095.669 5.336");
}

.t0_upib5g {
  d: path("M19.823 12.744a1.1 1.1 0 0 0-.298-.596l-.335.367l.151.294z");
}

.thafvacgt {
  stop-color: var(--svg-color--655452, #655452);
}

.tmrtimg7x {
  d: path("M22.367 14.24q.076-1.221.142-2.444a1.227 1.227 0 0 1-.142 2.445");
}

.twmiqpbxq {
  d: path("m25.19 20.578l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u1hhhxbfd {
  stop-color: var(--svg-color--e2632d, #E2632D);
}

.u4cp3820t {
  d: path("m6.81 20.578l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.u5the8b6m {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.37 12.689l-.815 2.36c-.139.486.196.972.67.972h1.009c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.696-.524-.85 0");
}

.ub8ckabiz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.924 11.398c-.838 0-1.547.578-1.74 1.36a.352.352 0 0 0 .344.437h2.866a.296.296 0 0 0 .291-.35a1.8 1.8 0 0 0-1.76-1.447");
}

.um2k303ln {
  d: path("M9.526 11.817a1.227 1.227 0 0 0 .107 2.413a100 100 0 0 1-.107-2.413");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.utrmehb1k {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.066 11.398c.839 0 1.547.578 1.74 1.36a.352.352 0 0 1-.344.437h-2.865a.296.296 0 0 1-.292-.35a1.795 1.795 0 0 1 1.76-1.447");
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

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vzmhuwavr {
  stop-color: var(--svg-color--f35e74, #F35E74);
  stop-opacity: 0;
}

.vzu9-mfnh {
  d: path("m23 16.078l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.w-vsz3bnm {
  stop-color: var(--svg-color--e4764e, #E4764E);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w58mn6r_g {
  stop-color: var(--svg-color--ff9a32, #FF9A32);
}

.w73iq3bud {
  fill: var(--svg-color--f53b19, #F53B19);
  d: path("M25.5 30.008h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.wq0eljlkx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.263 9.76l-2.017-.534");
}

.ww2kv0bto {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M16.294 6.143a3 3 0 0 1-.085-.176a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34v.353c-.436-.333-.986-1.033-.986-2.168c0-1.376 1.004-2.072 1.645-2.516c.18-.125.332-.23.425-.325l.128-.135c.448-.476 1.248-1.324 2.645-1.695a7.2 7.2 0 0 1 2.167-.203c.472.026.805.434.805.907v2.137z");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xc3cwzl8h {
  stop-color: var(--svg-color--35161b, #35161B);
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xlrzicczw {
  stop-color: var(--svg-color--3a221f, #3A221F);
}

.xrn2z6b6u {
  stop-color: var(--svg-color--ff8c11, #FF8C11);
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

.z2eb7q_dp {
  stop-color: var(--svg-color--655351, #655351);
  stop-opacity: 0;
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zr40zg26a {
  stop-color: var(--svg-color--4a1c1c, #4A1C1C);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
