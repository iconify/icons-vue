<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i5747Oe)" class="e5ucantjx"/><path fill="url(#ig5arCc)" class="a6yq75bbi"/><g filter="url(#iAzfYcc)"><path fill="url(#ii3PBuc)" class="omftgvbac"/></g><path fill="url(#iQIliwV)" class="omftgvbac"/><path fill="url(#iwXIF9d)" class="omftgvbac"/><path fill="url(#iDNH7Qd)" class="omftgvbac"/><path fill="url(#iBwBVJe)" class="omftgvbac"/><path fill="url(#iyFtBZc)" class="omftgvbac"/><path fill="url(#iifwZMe)" class="omftgvbac"/><path fill="url(#ivKG6Zc)" class="omftgvbac"/><path fill="url(#iny7tke)" class="omftgvbac"/><g filter="url(#iZqZ7wc)"><path class="w-ach6bru"/></g><g filter="url(#i3fJnRy)"><path class="ofishsryn"/><path fill="url(#iR2Uuad)" class="e-zb_sb0t"/><path fill="url(#i2K5awe)" class="e-zb_sb0t"/><path fill="url(#iysrvQq)" class="e-zb_sb0t"/></g><g filter="url(#iaIZ8hS)"><path fill="url(#iOdqWdd)" class="bnbr98b0b"/><path fill="url(#iCDNjgc)" class="bnbr98b0b"/><path fill="url(#iw43Bzb)" class="bnbr98b0b"/><path fill="url(#i9o9XPd)" class="bnbr98b0b"/><path fill="url(#izmLBvd)" class="bnbr98b0b"/></g><g filter="url(#iUWhvmb)"><path class="ww2kv0bto"/><path fill="url(#ilqQ6Nb)" class="rbbulnz3l"/><path fill="url(#iMydfGc)" class="rbbulnz3l"/></g><g filter="url(#itHxbSY)"><path class="m_ovc62ju"/><path fill="url(#iQKLrob)" class="t-faq4izi"/><path fill="url(#iDiRxhc)" class="t-faq4izi"/><path fill="url(#igGkLzc)" class="t-faq4izi"/></g><path class="utrmehb1k"/><path fill="url(#iPjnENe)" class="cswzjcx6u"/><path class="iitgd8bac"/><g filter="url(#iGCuwXb)"><path class="dodqfog5q"/><path fill="url(#i9QUMfK)" class="nsn8oes0z"/></g><g filter="url(#ilpWs7d)"><path fill="url(#iKnUjve)" class="t0_upib5g"/></g><path class="ub8ckabiz"/><path fill="url(#iOPziAb)" class="fqu12ubrd"/><path class="ebo5c_0lf"/><g filter="url(#iU8NCMb)"><path fill="url(#i7aVE8b)" class="q5hvggldb"/></g><g filter="url(#ivhyR1Y)"><ellipse transform="rotate(-27.914 12.844 12.236)" class="z-qcyfbze"/><ellipse fill="url(#i8Ldsle)" transform="rotate(-27.914 12.844 12.236)" class="a3xscqbym"/></g><path fill="url(#iGj1ufv)" class="nl8aomm7e"/><path fill="url(#iXVlanb)" class="nl8aomm7e"/><path fill="url(#iskuZtc)" class="nl8aomm7e"/><path fill="url(#i7A6d2b)" class="nl8aomm7e"/><path fill="url(#iZpxtxY)" class="l3e-mtbcj"/><path fill="url(#itKTire)" class="l3e-mtbcj"/><g filter="url(#iOM8aed)"><path class="gwy14vbat"/></g><g filter="url(#i6K5hae)"><path fill="url(#i0K5nga)" class="tmrtimg7x"/></g><g filter="url(#ihcFhLc)"><path class="j677s7bvu"/></g><g filter="url(#iHYj6sb)"><path class="dfcs42bel"/></g><g filter="url(#ilKk98c)"><path class="j0dy1fkyn"/></g><g filter="url(#ihf5PJe)"><path class="oyndzbcov"/></g><path class="fq1gvacsb"/><path class="w73iq3bud"/><path fill="url(#iY2ScGe)" class="akki1obxr"/><path fill="url(#inirSwb)" class="akki1obxr"/><path fill="url(#iMsUfGe)" class="u4cp3820t"/><path fill="url(#ihqOLGc)" class="cuomu7bqz"/><path fill="url(#iRbdh4d)" class="cuomu7bqz"/><path fill="url(#i16tupc)" class="cuomu7bqz"/><path fill="url(#isBeo5c)" class="cuomu7bqz"/><path fill="url(#izAvOPb)" class="cuomu7bqz"/><path fill="url(#igdf08b)" class="cuomu7bqz"/><path fill="url(#iiwVwQd)" class="twmiqpbxq"/><path fill="url(#iDDcgbe)" class="v3eonib4h"/><path fill="url(#iwGAPQd)" class="v3eonib4h"/><path fill="url(#ixh7Cge)" class="v3eonib4h"/><path fill="url(#iV6ZNtn)" class="e3jco7qba"/><path fill="url(#iPkcave)" class="e3jco7qba"/><path fill="url(#irM2Nkc)" class="e3jco7qba"/><path fill="url(#irSg8vb)" class="i4fzwzbpd"/><path fill="url(#i5MMlGe)" class="i4fzwzbpd"/><path fill="url(#inVreMe)" class="vzu9-mfnh"/><path fill="url(#i62ILNd)" class="vzu9-mfnh"/><path fill="url(#i7Dr2Wc)" class="vzu9-mfnh"/><path fill="url(#iE1WvDb)" class="vzu9-mfnh"/><g filter="url(#iGoUUEc)"><path fill="url(#i6YVNlb)" class="cw3sn1brq"/><path fill="url(#ivai8Id)" class="cw3sn1brq"/></g><path fill="url(#ifJZSjb)" class="cw3sn1brq"/><path fill="url(#iL9455d)" class="cw3sn1brq"/><g filter="url(#iBYMhIj)"><path fill="url(#iIsWn0o)" class="j_0xl5h8m"/></g><defs><radialGradient id="i5747Oe" cx="0" cy="0" r="1" gradientTransform="matrix(.96166 2.5937 -3.08112 1.14238 22.1 14.564)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="ig5arCc" cx="0" cy="0" r="1" gradientTransform="matrix(1.89623 .59596 -1.83857 5.85 8.217 15.194)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="ii3PBuc" cx="0" cy="0" r="1" gradientTransform="rotate(129.552 6.655 11.294)scale(7.99483 14.1428)" gradientUnits="userSpaceOnUse"><stop class="c3i7elbzy"/><stop offset="1" class="bjvwooyju"/></radialGradient><radialGradient id="iwXIF9d" cx="0" cy="0" r="1" gradientTransform="rotate(94.47 6.35 11.216)scale(16.448 13.6209)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="ja6wjacpw"/><stop offset=".988" class="klddmnahu"/></radialGradient><radialGradient id="iDNH7Qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.47484 1.82511 0 19.138 11.669)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="ybsadsbmk"/><stop offset="1" class="jnvagkbvb"/></radialGradient><radialGradient id="iBwBVJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.06849 2.251 0 13.041 11.729)" gradientUnits="userSpaceOnUse"><stop class="slp963bhh"/><stop offset="1" class="bkt9uvbaj"/></radialGradient><radialGradient id="iyFtBZc" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.971 7.634)scale(10.9332 27.9288)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iifwZMe" cx="0" cy="0" r="1" gradientTransform="matrix(4.366 -5.04595 1.84717 1.59826 7.746 8.032)" gradientUnits="userSpaceOnUse"><stop class="ryekzubnm"/><stop offset="1" class="zuutxqbtm"/></radialGradient><radialGradient id="ivKG6Zc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23876 3.7026 -3.0568 -1.84827 19.112 6.96)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iCDNjgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.49678 11.3718 0 9.279 9.64)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iw43Bzb" cx="0" cy="0" r="1" gradientTransform="matrix(.14646 -3.22688 5.7174 .2595 22.238 11.323)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i9o9XPd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02947 -1.99249 1.46259 -2.22378 21.269 3.262)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="izmLBvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.16245 1.89434 -4.3864 2.69168 14.832 1.217)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="ilqQ6Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.82692 0 0 -1.04918 16.32 4.119)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iMydfGc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.84 -3.592)scale(7.74003 8.57516)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iQKLrob" cx="0" cy="0" r="1" gradientTransform="matrix(3.92791 0 0 1.53575 20.38 5.252)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iDiRxhc" cx="0" cy="0" r="1" gradientTransform="matrix(3.4403 -3.27777 6.00076 6.29832 19.377 9.153)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="igGkLzc" cx="0" cy="0" r="1" gradientTransform="matrix(4.17171 .4876 -.20415 1.74662 18.24 7.256)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iPjnENe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04198 -1.65739 0 18.798 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i9QUMfK" cx="0" cy="0" r="1" gradientTransform="matrix(-.29785 -.38382 .52843 -.41007 18.504 12.467)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOPziAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04204 -1.65748 0 13.193 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8Ldsle" cx="0" cy="0" r="1" gradientTransform="matrix(-.00994 -.63455 .76277 -.01194 12.825 12.642)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXVlanb" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 2.921 20.555)scale(2.99201 2.85461)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iskuZtc" cx="0" cy="0" r="1" gradientTransform="matrix(1.01175 -1.38847 1.16382 .84805 22.388 12.895)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="i7A6d2b" cx="0" cy="0" r="1" gradientTransform="rotate(-69.263 20.763 -9.755)scale(2.12915 2.84485)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="itKTire" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0718 -.25343 .27238 -2.22668 9.682 13.019)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iY2ScGe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.445)" gradientUnits="userSpaceOnUse"><stop class="prd44wbso"/><stop offset="1" class="c5khawelw"/></radialGradient><radialGradient id="inirSwb" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.227)" gradientUnits="userSpaceOnUse"><stop class="u1hhhxbfd"/><stop offset="1" class="cl_cdxbgs"/></radialGradient><radialGradient id="iMsUfGe" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 1.25 -2.6929 5.58776 8.406 17.32)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="vxb86i-rd"/><stop offset="1" class="rowsrjblg"/></radialGradient><radialGradient id="ihqOLGc" cx="0" cy="0" r="1" gradientTransform="matrix(17.51082 8.75543 -2.15289 4.30577 13.551 19.209)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="v3bwo4btz"/><stop offset="1" class="kd1_xhb_o"/></radialGradient><radialGradient id="iRbdh4d" cx="0" cy="0" r="1" gradientTransform="rotate(159.944 11.543 15.187)scale(2.90693 2.17455)" gradientUnits="userSpaceOnUse"><stop class="cq9p23brg"/><stop offset="1" class="cwmsguygo"/></radialGradient><radialGradient id="i16tupc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11963 5.31578 -8.32746 -1.75396 14.245 17.692)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="w58mn6r_g"/><stop offset="1" class="xrn2z6b6u"/></radialGradient><radialGradient id="izAvOPb" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.455 -3.07)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="mq0gl8bsz"/><stop offset="1" class="w-vsz3bnm"/></radialGradient><radialGradient id="iiwVwQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 .6475 -1.4343 -3.32276 24.094 18.195)" gradientUnits="userSpaceOnUse"><stop class="qxiqgebpn"/><stop offset="1" class="m_8hwoksz"/></radialGradient><radialGradient id="iDDcgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.883)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="jbd_cz55y"/><stop offset="1" class="m7o64xbbx"/></radialGradient><radialGradient id="iV6ZNtn" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.469)" gradientUnits="userSpaceOnUse"><stop class="pgf79f9wa"/><stop offset=".615" class="xv-pxlqsu"/></radialGradient><radialGradient id="irSg8vb" cx="0" cy="0" r="1" gradientTransform="matrix(1.74664 .85478 -1.17534 2.40165 3.176 17.648)" gradientUnits="userSpaceOnUse"><stop class="uiznndb6j"/><stop offset=".697" class="cd2vywbdh"/></radialGradient><radialGradient id="i5MMlGe" cx="0" cy="0" r="1" gradientTransform="rotate(162.607 1.083 8.97)scale(.89785 1.70016)" gradientUnits="userSpaceOnUse"><stop class="djew4vbxv"/><stop offset="1" class="qgkg7gbyq"/></radialGradient><radialGradient id="inVreMe" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.294 6.356)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="k06as4b5x"/><stop offset="1" class="xfmd1de7c"/></radialGradient><radialGradient id="i62ILNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 .59376 -.2045 -.35517 30.161 13.225)" gradientUnits="userSpaceOnUse"><stop class="z-bv-oxvq"/><stop offset="1" class="ba2ysf3ct"/></radialGradient><radialGradient id="iE1WvDb" cx="0" cy="0" r="1" gradientTransform="matrix(2.96386 -2.56198 2.74355 3.17391 24.182 21.076)" gradientUnits="userSpaceOnUse"><stop class="jrj308b2k"/><stop offset="1" class="sbo-zor_o"/></radialGradient><radialGradient id="ivai8Id" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.288)" gradientUnits="userSpaceOnUse"><stop class="ypu5blbsz"/><stop offset="1" class="evh185ecb"/></radialGradient><radialGradient id="ifJZSjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4554 -4.55404 4.5889 -.4589 7.38 23.254)" gradientUnits="userSpaceOnUse"><stop class="pcgaf6bek"/><stop offset="1" class="d9c9r_gmq"/></radialGradient><radialGradient id="iL9455d" cx="0" cy="0" r="1" gradientTransform="matrix(1.03449 -.40327 1.31923 3.38417 4.578 18.206)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="th3on_b5q"/><stop offset="1" class="jztexxbfv"/></radialGradient><linearGradient id="iQIliwV" x1="22.619" x2="17.028" y1="15.52" y2="15.52" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iny7tke" x1="16.055" x2="16.055" y1="21.762" y2="20.477" gradientUnits="userSpaceOnUse"><stop class="vf4wk19pd"/><stop offset="1" class="lkt8amb4a"/></linearGradient><linearGradient id="iR2Uuad" x1="17.201" x2="15.875" y1="14.045" y2="14.306" gradientUnits="userSpaceOnUse"><stop offset=".074" class="icd8fhbfu"/><stop offset="1" class="uh7nbdb2t"/></linearGradient><linearGradient id="i2K5awe" x1="14.602" x2="15.737" y1="15.118" y2="15.272" gradientUnits="userSpaceOnUse"><stop class="r7k4-jbyd"/><stop offset="1" class="yget2qbjb"/></linearGradient><linearGradient id="iysrvQq" x1="15.995" x2="15.995" y1="15.706" y2="15.109" gradientUnits="userSpaceOnUse"><stop class="v3jo9_yzp"/><stop offset="1" class="ual7fec4r"/></linearGradient><linearGradient id="iOdqWdd" x1="24.795" x2="9.881" y1="6.082" y2="6.082" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iKnUjve" x1="19.798" x2="19.394" y1="12.429" y2="12.678" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7aVE8b" x1="14.148" x2="13.745" y1="12.428" y2="12.677" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGj1ufv" x1="24.261" x2="22.711" y1="12.282" y2="15.077" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iZpxtxY" x1="8.482" x2="10.355" y1="13.183" y2="13.02" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="i0K5nga" x1="22.975" x2="22.975" y1="11.796" y2="14.241" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="isBeo5c" x1="9.156" x2="10.344" y1="18.508" y2="18.883" gradientUnits="userSpaceOnUse"><stop class="psrrqcksv"/><stop offset="1" class="rbkr51v-c"/></linearGradient><linearGradient id="igdf08b" x1="17.406" x2="17.906" y1="26.977" y2="25.758" gradientUnits="userSpaceOnUse"><stop class="gd1of5hxe"/><stop offset="1" class="v1z821b6o"/></linearGradient><linearGradient id="iwGAPQd" x1="14.83" x2="14.461" y1="26.816" y2="25.927" gradientUnits="userSpaceOnUse"><stop class="q9mg64b4e"/><stop offset="1" class="vzmhuwavr"/></linearGradient><linearGradient id="ixh7Cge" x1="22.827" x2="21.613" y1="18.819" y2="19.382" gradientUnits="userSpaceOnUse"><stop class="smo9u60ba"/><stop offset="1" class="ktas3sbvn"/></linearGradient><linearGradient id="iPkcave" x1="27.52" x2="26.84" y1="19.664" y2="18.102" gradientUnits="userSpaceOnUse"><stop class="nrxa3zsae"/><stop offset="1" class="bnl8ulbdv"/></linearGradient><linearGradient id="irM2Nkc" x1="26.75" x2="27.494" y1="17.398" y2="18.158" gradientUnits="userSpaceOnUse"><stop offset=".353" class="jxqufcbzg"/><stop offset="1" class="o24g7qb2o"/></linearGradient><linearGradient id="i7Dr2Wc" x1="25.489" x2="25.997" y1="14.289" y2="15.189" gradientUnits="userSpaceOnUse"><stop class="odlbd947j"/><stop offset="1" class="izl0csmmw"/><stop offset="1" class="yjwkbfbeo"/></linearGradient><linearGradient id="i6YVNlb" x1="8" x2="5.5" y1="15.758" y2="19.524" gradientUnits="userSpaceOnUse"><stop offset=".206" class="h8_gk412t"/><stop offset="1" class="wrh5y-bmk"/></linearGradient><linearGradient id="iIsWn0o" x1="29.179" x2="24.036" y1="14.953" y2="17.82" gradientUnits="userSpaceOnUse"><stop class="wvl4ponzh"/><stop offset="1" class="sa15ql7ok"/></linearGradient><filter id="iAzfYcc" width="14.126" height="16.05" x="9.492" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24806"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24806" result="effect2_innerShadow_3987_24806"/></filter><filter id="iZqZ7wc" width="4.411" height="5.725" x="13.524" y="11.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".5"/></filter><filter id="i3fJnRy" width="2.811" height="4.125" x="14.59" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".1"/></filter><filter id="iaIZ8hS" width="16.532" height="10.59" x="7.729" y="1.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24806"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24806" result="effect2_innerShadow_3987_24806"/></filter><filter id="iUWhvmb" width="8.814" height="8.053" x="8.006" y="2.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24806"/><feGaussianBlur result="effect2_foregroundBlur_3987_24806" stdDeviation=".25"/></filter><filter id="itHxbSY" width="8.596" height="7.796" x="15.543" y="3.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".25"/></filter><filter id="iGCuwXb" width=".954" height=".837" x="17.883" y="11.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".05"/></filter><filter id="ilpWs7d" width="1.033" height="1.061" x="18.99" y="11.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".1"/></filter><filter id="iU8NCMb" width="1.153" height="1.222" x="13.284" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".1"/></filter><filter id="ivhyR1Y" width="1.116" height=".848" x="12.286" y="11.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".05"/></filter><filter id="iOM8aed" width="1.565" height="2.914" x="8.318" y="11.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".125"/></filter><filter id="i6K5hae" width="2.216" height="3.444" x="21.867" y="11.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".25"/></filter><filter id="ihcFhLc" width="2.884" height="1.34" x="11.376" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0980392 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24806"/></filter><filter id="iHYj6sb" width="2.884" height="1.34" x="17.939" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0980392 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24806"/></filter><filter id="ilKk98c" width="2.767" height="1.284" x="11.461" y="8.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".125"/></filter><filter id="ihf5PJe" width="2.767" height="1.284" x="17.871" y="8.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".125"/></filter><filter id="iGoUUEc" width="7.3" height="8.016" x="2" y="12.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.627451 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24806"/></filter><filter id="iBYMhIj" width="5.538" height="5.423" x="24.159" y="13.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24806" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-no-light" /></template>
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

.akki1obxr {
  d: path("M25.5 30.008h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ba2ysf3ct {
  stop-color: var(--svg-color--ffd7c0, #FFD7C0);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bjvwooyju {
  stop-color: var(--svg-color--ef9f81, #EF9F81);
}

.bkt9uvbaj {
  stop-color: var(--svg-color--e19981, #E19981);
  stop-opacity: 0;
}

.bnbr98b0b {
  d: path("M22.23 4.823c.66.228 1.253.69 1.628 1.35a3.04 3.04 0 0 1-.136 3.245a2 2 0 0 0-.348 1.123v1.526a2.2 2.2 0 0 0-.856-.345l.1-2.063a1.86 1.86 0 0 0-1.77-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34l.028 1.976c-.326.048-.655.155-.913.336v-1.541c0-.4-.123-.792-.348-1.123a3.07 3.07 0 0 1-.184-3.141a3 3 0 0 1 1.67-1.447a3.44 3.44 0 0 0 1.777-1.426a2.99 2.99 0 0 1 2.534-1.412c.416 0 .81.09 1.179.241c.49.214 1.042.214 1.532 0a3 3 0 0 1 1.172-.24c1.083 0 2.03.585 2.554 1.453a3.24 3.24 0 0 0 1.737 1.377");
}

.bnl8ulbdv {
  stop-color: var(--svg-color--d99793, #D99793);
  stop-opacity: 0;
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c3i7elbzy {
  stop-color: var(--svg-color--ffdab8, #FFDAB8);
}

.c5khawelw {
  stop-color: var(--svg-color--ff9540, #FF9540);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cd2vywbdh {
  stop-color: var(--svg-color--cd857c, #CD857C);
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

.d9c9r_gmq {
  stop-color: var(--svg-color--c87670, #C87670);
  stop-opacity: 0;
}

.dfcs42bel {
  fill: var(--svg-color--1c1918, #1C1918);
  d: path("M20.711 9.94a.35.35 0 0 0-.25-.426l-2.086-.542a.349.349 0 1 0-.175.675l2.086.542a.35.35 0 0 0 .425-.249");
}

.djew4vbxv {
  stop-color: var(--svg-color--d28c70, #D28C70);
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

.e5ucantjx {
  d: path("M22.239 14.96c.43-.014.833-.16 1.161-.396v1.195a2.79 2.79 0 0 1-1.722 2.593c.219-.465.37-.973.444-1.515z");
}

.ebo5c_0lf {
  fill: var(--svg-color--000, #000);
  d: path("M13.847 12.893a.654.654 0 0 0-.657-.657a.654.654 0 0 0-.583.959h1.162a.65.65 0 0 0 .078-.302");
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.evh185ecb {
  stop-color: var(--svg-color--fbc7b5, #FBC7B5);
  stop-opacity: 0;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fq1gvacsb {
  fill: var(--svg-color--88004c, #88004C);
  d: path("M15.989 19.458c.791 0 1.433-.688 1.433-1.537c0-.85-.642-1.538-1.433-1.538s-1.433.688-1.433 1.538c0 .849.642 1.537 1.433 1.537");
}

.fqu12ubrd {
  d: path("M13.19 11.747a1.146 1.146 0 0 0-1.104 1.448H14.3q.04-.147.041-.302a1.154 1.154 0 0 0-1.15-1.147");
}

.ft5dv1b6b {
  fill: none;
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gd1of5hxe {
  stop-color: var(--svg-color--eb4e66, #EB4E66);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gwy14vbat {
  fill: var(--svg-color--cb896f, #CB896F);
  d: path("M9.526 11.817a1.228 1.228 0 0 0 .107 2.413q-.069-1.206-.107-2.413");
}

.h8_gk412t {
  stop-color: var(--svg-color--ffd5b9, #FFD5B9);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
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

.icd8fhbfu {
  stop-color: var(--svg-color--ffdabe, #FFDABE);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.iitgd8bac {
  fill: var(--svg-color--000, #000);
  d: path("M18.144 12.893c0-.365.291-.657.656-.657a.654.654 0 0 1 .584.959h-1.162a.6.6 0 0 1-.078-.302");
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.izl0csmmw {
  stop-color: var(--svg-color--c6916f, #C6916F);
  stop-opacity: 0;
}

.j_0xl5h8m {
  d: path("M26.653 15.73c.527-.847 1.795-1.665 2.462-1.988a.13.13 0 0 1 .152.034a.132.132 0 0 1-.033.196c-2.06 1.273-1.875 1.785-2.645 3.097c-.355.604-1.177 1.112-1.556 1.284l-.474-.899c.53-.28 1.462-.711 2.094-1.725");
}

.j0dy1fkyn {
  stroke: var(--svg-color--2d2c2d, #2D2C2D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m11.836 9.76l2.017-.534");
}

.j677s7bvu {
  fill: var(--svg-color--1c1918, #1C1918);
  d: path("M11.388 9.94a.35.35 0 0 1 .25-.426l2.086-.542a.349.349 0 1 1 .175.675l-2.086.542a.35.35 0 0 1-.425-.249");
}

.ja6wjacpw {
  stop-color: var(--svg-color--cd8c92, #CD8C92);
  stop-opacity: 0;
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jnvagkbvb {
  stop-color: var(--svg-color--ffbb9d, #FFBB9D);
  stop-opacity: 0;
}

.jrj308b2k {
  stop-color: var(--svg-color--d98a84, #D98A84);
}

.jxqufcbzg {
  stop-color: var(--svg-color--dfaf96, #DFAF96);
}

.jztexxbfv {
  stop-color: var(--svg-color--e2a594, #E2A594);
  stop-opacity: 0;
}

.k06as4b5x {
  stop-color: var(--svg-color--fccbb6, #FCCBB6);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kd1_xhb_o {
  stop-color: var(--svg-color--ff4c31, #FF4C31);
}

.klddmnahu {
  stop-color: var(--svg-color--cc7c80, #CC7C80);
}

.ktas3sbvn {
  stop-color: var(--svg-color--ffa842, #FFA842);
  stop-opacity: 0;
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l3e-mtbcj {
  d: path("M9.513 10.96a2.08 2.08 0 0 0-1.784 2.053c0 1.103.864 2.005 1.953 2.063a101 101 0 0 1-.17-4.115");
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkt8amb4a {
  stop-color: var(--svg-color--e27d6e, #E27D6E);
  stop-opacity: 0;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
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

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mq0gl8bsz {
  stop-color: var(--svg-color--e4764e, #E4764E);
}

.nl8aomm7e {
  d: path("M22.316 15.077q.129-2.05.237-4.099a2.067 2.067 0 0 1-.237 4.099");
}

.nrxa3zsae {
  stop-color: var(--svg-color--d99793, #D99793);
}

.nsn8oes0z {
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.o24g7qb2o {
  stop-color: var(--svg-color--dfaf96, #DFAF96);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odlbd947j {
  stop-color: var(--svg-color--d6af98, #D6AF98);
}

.ofishsryn {
  fill: var(--svg-color--ffc4a9, #FFC4A9);
  d: path("m15.504 12.458l-.683 2.361c-.139.486.196.972.67.972H16.5c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.829-.524-.982 0");
}

.omftgvbac {
  d: path("M9.798 16.906a5.03 5.03 0 0 0 4.99 4.374h2.424a5.03 5.03 0 0 0 4.99-4.374c.152-2.42.304-4.829.417-7.247a1.86 1.86 0 0 0-1.771-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34c0 2.39.15 4.74.306 7.136");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oyndzbcov {
  stroke: var(--svg-color--2d2c2d, #2D2C2D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m20.263 9.76l-2.017-.534");
}

.pcgaf6bek {
  stop-color: var(--svg-color--c87670, #C87670);
}

.pgf79f9wa {
  stop-color: var(--svg-color--ffd2be, #FFD2BE);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prd44wbso {
  stop-color: var(--svg-color--ff9540, #FF9540);
}

.psrrqcksv {
  stop-color: var(--svg-color--ff730a, #FF730A);
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
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

.qgkg7gbyq {
  stop-color: var(--svg-color--d28c70, #D28C70);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxiqgebpn {
  stop-color: var(--svg-color--ff6732, #FF6732);
}

.r7k4-jbyd {
  stop-color: var(--svg-color--f2a585, #F2A585);
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rbbulnz3l {
  d: path("M16.294 6.143a3 3 0 0 1-.085-.176a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34v.353c-.436-.333-.986-1.033-.986-2.168c0-1.376 1.004-2.072 1.645-2.516c.18-.125.332-.23.425-.325l.128-.135c.448-.476 1.248-1.324 2.645-1.695a7.2 7.2 0 0 1 2.167-.203c.472.026.805.434.805.907v2.137z");
}

.rbkr51v-c {
  stop-color: var(--svg-color--ff730a, #FF730A);
  stop-opacity: 0;
}

.rowsrjblg {
  stop-color: var(--svg-color--d93738, #D93738);
}

.ryekzubnm {
  stop-color: var(--svg-color--b68069, #B68069);
}

.sa15ql7ok {
  stop-color: var(--svg-color--ffd0bc, #FFD0BC);
  stop-opacity: 0;
}

.sbo-zor_o {
  stop-color: var(--svg-color--d98a84, #D98A84);
  stop-opacity: 0;
}

.slp963bhh {
  stop-color: var(--svg-color--e19981, #E19981);
}

.smo9u60ba {
  stop-color: var(--svg-color--ffa842, #FFA842);
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t-faq4izi {
  d: path("m22.69 10.474l-.038-.811c-.014-.98-.824-1.79-1.805-1.83H19.05a3.11 3.11 0 0 1-2.728-1.619s-.16-.372-.258-.96c-.165-.989.75-1.717 1.74-1.554c1.354.222 3.024.66 4.218 1.438c2.24 1.462 1.848 4.095.669 5.336");
}

.t0_upib5g {
  d: path("M19.823 12.744a1.1 1.1 0 0 0-.298-.596l-.335.367l.151.294z");
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.th3on_b5q {
  stop-color: var(--svg-color--e2a594, #E2A594);
}

.tmrtimg7x {
  d: path("M22.367 14.24q.076-1.221.142-2.444a1.227 1.227 0 0 1-.142 2.445");
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

.ual7fec4r {
  stop-color: var(--svg-color--f69b76, #F69B76);
  stop-opacity: 0;
}

.ub8ckabiz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.924 11.398c-.838 0-1.547.578-1.74 1.36a.352.352 0 0 0 .344.437h2.866a.296.296 0 0 0 .291-.35a1.8 1.8 0 0 0-1.76-1.447");
}

.uh7nbdb2t {
  stop-color: var(--svg-color--ffdabe, #FFDABE);
  stop-opacity: 0;
}

.uiznndb6j {
  stop-color: var(--svg-color--e8ad95, #E8AD95);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.utrmehb1k {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.066 11.398c.839 0 1.547.578 1.74 1.36a.352.352 0 0 1-.344.437h-2.865a.296.296 0 0 1-.292-.35a1.795 1.795 0 0 1 1.76-1.447");
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
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

.v3jo9_yzp {
  stop-color: var(--svg-color--f69b76, #F69B76);
}

.vf4wk19pd {
  stop-color: var(--svg-color--e27d6e, #E27D6E);
}

.vxb86i-rd {
  stop-color: var(--svg-color--ff7130, #FF7130);
}

.vzmhuwavr {
  stop-color: var(--svg-color--f35e74, #F35E74);
  stop-opacity: 0;
}

.vzu9-mfnh {
  d: path("m23 16.078l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.w-ach6bru {
  fill: var(--svg-color--f29b77, #F29B77);
  d: path("m15.37 12.689l-.815 2.36c-.139.486.196.972.67.972h1.009c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.696-.524-.85 0");
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

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wrh5y-bmk {
  stop-color: var(--svg-color--d99386, #D99386);
}

.wvl4ponzh {
  stop-color: var(--svg-color--ffd0bc, #FFD0BC);
}

.ww2kv0bto {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M16.294 6.143a3 3 0 0 1-.085-.176a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34v.353c-.436-.333-.986-1.033-.986-2.168c0-1.376 1.004-2.072 1.645-2.516c.18-.125.332-.23.425-.325l.128-.135c.448-.476 1.248-1.324 2.645-1.695a7.2 7.2 0 0 1 2.167-.203c.472.026.805.434.805.907v2.137z");
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.xfmd1de7c {
  stop-color: var(--svg-color--e2ae96, #E2AE96);
}

.xrn2z6b6u {
  stop-color: var(--svg-color--ff8c11, #FF8C11);
  stop-opacity: 0;
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xv-pxlqsu {
  stop-color: var(--svg-color--f3c1a8, #F3C1A8);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.ybsadsbmk {
  stop-color: var(--svg-color--ffbb9d, #FFBB9D);
}

.yget2qbjb {
  stop-color: var(--svg-color--f2a585, #F2A585);
  stop-opacity: 0;
}

.yjwkbfbeo {
  stop-color: var(--svg-color--d6af98, #D6AF98);
  stop-opacity: 0;
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.ypu5blbsz {
  stop-color: var(--svg-color--fbc7b5, #FBC7B5);
}

.z-bv-oxvq {
  stop-color: var(--svg-color--ffd7c0, #FFD7C0);
}

.z-qcyfbze {
  cx: 12.844px;
  cy: 12.236px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.5px;
  ry: 0.253px;
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zuutxqbtm {
  stop-color: var(--svg-color--b68069, #B68069);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
