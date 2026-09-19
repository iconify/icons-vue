<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#idgyKfd)"><path class="mgz0e9bgo"/><path fill="url(#iYHUIfF)" class="m0r2shmnv"/></g><path fill="url(#iT6LM6X)" class="ikan01biz"/><path fill="url(#i4NNVDX)" class="ikan01biz"/><path fill="url(#i4Lhncd)" class="n-e13gbqy"/><path fill="url(#i5pRw5W)" class="n-e13gbqy"/><path fill="url(#iTBk8Vd)" class="zakn8hfha"/><path fill="url(#inQoOEq)" class="zakn8hfha"/><path fill="url(#iLy7jzd)" class="zakn8hfha"/><path fill="url(#iLovVHb)" class="zakn8hfha"/><path fill="url(#idkDDNd)" class="yoe2fy8iq"/><path fill="url(#izHqxhc)" class="yoe2fy8iq"/><path fill="url(#iZ5Tvtd)" class="yoe2fy8iq"/><path fill="url(#iRWdjce)" class="yoe2fy8iq"/><path fill="url(#iluqQsd)" class="yoe2fy8iq"/><path fill="url(#icp5lKc)" class="t_n_cwbft"/><path fill="url(#it060re)" class="ekw2c2fxt"/><path fill="url(#icaMlXc)" class="pcf3ofbyz"/><path fill="url(#iYF0W6g)" class="s8nm5zbxc"/><path fill="url(#i9jR5Vb)" class="s8nm5zbxc"/><path fill="url(#iRvOJKe)" class="s8nm5zbxc"/><path fill="url(#iZhzexc)" class="hcsxltfci"/><path fill="url(#itrGLHc)" class="hcsxltfci"/><path fill="url(#iX2jM5d)" class="t_d_hcclh"/><path fill="url(#iRpgU5m)" class="t_d_hcclh"/><path fill="url(#iF3r9sb)" class="t_d_hcclh"/><path fill="url(#iFmJfvb)" class="t_d_hcclh"/><g filter="url(#iST4aHb)"><path fill="url(#ihp02zd)" class="kxkx5kfke"/><path fill="url(#iytDpCe)" class="kxkx5kfke"/><path fill="url(#iNlU4qe)" class="kxkx5kfke"/></g><path fill="url(#iADf7pd)" class="uc7o5pbpu"/><path fill="url(#iK2iP8c)" class="uc7o5pbpu"/><path fill="url(#i7w24yc)" class="uc7o5pbpu"/><g filter="url(#iIrkwjQ)"><path fill="url(#ikimp3b)" class="q3uzgebbz"/></g><g filter="url(#i7NMNzb)"><circle fill="url(#ibrrZTY)" class="x7omq0bvx"/></g><g filter="url(#izbssTc)"><circle fill="url(#iB8QvhC)" class="weui8osko"/><circle fill="url(#itxn0oc)" class="weui8osko"/></g><g filter="url(#iSkki1c)"><path fill="url(#ioJT1wb)" class="rk6j68bhd"/><path fill="url(#iELAaFc)" class="rk6j68bhd"/><path fill="url(#iFrvaca)" class="rk6j68bhd"/><path fill="url(#ifwTy3b)" class="rk6j68bhd"/><path fill="url(#iGL8Z4c)" class="rk6j68bhd"/></g><g filter="url(#iPACLBe)"><path fill="url(#iUTG8Mc)" class="rk6j68bhd"/><path fill="url(#iGV70gc)" class="rk6j68bhd"/><path fill="url(#iymeNee)" class="rk6j68bhd"/><path fill="url(#iFfZt8t)" class="rk6j68bhd"/><path fill="url(#iTQOaqc)" class="rk6j68bhd"/></g><path fill="url(#i0aEdjb)" class="rk6j68bhd"/><g filter="url(#iFc4N8c)"><path stroke="url(#iaqgdKc)" class="qcej8hbyf"/></g><g filter="url(#i9e45Kr)"><path stroke="url(#i75SdFj)" class="i98yq5blv"/></g><g filter="url(#iDbJbJb)"><path stroke="url(#iNrwJme)" class="qhr695bog"/></g><g filter="url(#if4iAva)"><circle fill="url(#ihvmSKd)" class="p0kdb-eay"/></g><g filter="url(#iLmeind)"><circle fill="url(#iZsMuwc)" class="lya432q3n"/></g><g filter="url(#iORb7dd)"><circle fill="url(#iy8ilne)" class="ct-uzm47t"/><circle fill="url(#iUT97Zo)" class="ct-uzm47t"/></g><g filter="url(#iKMq3xd)"><circle class="se40-pr3g"/><circle fill="url(#i94dhwc)" class="acjl_f-ty"/><circle fill="url(#im8GJme)" class="acjl_f-ty"/></g><g filter="url(#iakklPb)"><path fill="url(#iuNtIid)" class="quz_fjzco"/><path fill="url(#iHWfLuB)" class="quz_fjzco"/><path fill="url(#ibczYWd)" class="quz_fjzco"/><path fill="url(#iwG26yb)" class="quz_fjzco"/><path fill="url(#iMD1ssb)" class="quz_fjzco"/><path fill="url(#iaNJvCS)" class="quz_fjzco"/></g><g filter="url(#iXTtqfe)"><path fill="url(#i3MTGeD)" class="el_trbcqu"/></g><g filter="url(#i0f7dob)"><path class="bzyfxrbvp"/><path fill="url(#ingLkle)" class="umvlo82vr"/><path fill="url(#iQ1Okvc)" class="umvlo82vr"/><path fill="url(#ibaUXGh)" class="umvlo82vr"/><path fill="url(#iWpeMjd)" class="umvlo82vr"/></g><g filter="url(#i9xXktb)"><path class="hu-xsvbmv"/></g><g filter="url(#iHPKZPc)"><path class="y9ijw_6_e"/><path fill="url(#ijIGSye)" class="eqiyjytvm"/><path fill="url(#i5OUYnm)" class="eqiyjytvm"/><path fill="url(#ikgOBzD)" class="eqiyjytvm"/><path fill="url(#iMxqsnd)" class="eqiyjytvm"/></g><path fill="url(#iZhGjpb)" class="eqiyjytvm"/><path fill="url(#inv3Tve)" class="b2yaby8wi"/><path fill="url(#iKElqVW)" class="b2yaby8wi"/><path fill="url(#inwNTKM)" class="b2yaby8wi"/><path stroke="url(#ibYFeSb)" class="medc3dbxd"/><g filter="url(#iSo6bab)"><path class="igkmnnmew"/></g><g filter="url(#iC7MBqe)"><path class="zja74brvl"/></g><path class="pn3itgrui"/><path fill="url(#ibYZtTc)" class="lsxcn4bfz"/><path class="t620_nb8y"/><g filter="url(#ii7OYqd)"><path class="h0u13vboz"/><path fill="url(#iqv4XPd)" class="rsdkd7bet"/></g><g filter="url(#i2gVKBg)"><path fill="url(#ijpRPsb)" class="fu2ep6afb"/></g><path class="dqxippkig"/><path fill="url(#iJxMBee)" class="ctk9r0bck"/><path class="hi_lf-b6x"/><g filter="url(#iuySt1d)"><path fill="url(#inNi7dd)" class="fia60pksa"/></g><g filter="url(#ih1UYIZ)"><ellipse transform="rotate(-27.914 12.554 11.443)" class="atb2q5h3d"/><ellipse fill="url(#iFiShgj)" transform="rotate(-27.914 12.554 11.443)" class="pfw33cdrd"/></g><g filter="url(#iz7FBrb)"><path stroke="url(#iLjl0Dq)" class="ve34ncchz"/></g><g filter="url(#iCSq32d)"><path stroke="url(#isomTTb)" class="g7kuvkbic"/></g><defs><radialGradient id="iT6LM6X" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.628 25.736)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="i4Lhncd" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.585 19.58)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="iLy7jzd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.16 18.017)" gradientUnits="userSpaceOnUse"><stop class="mnp72frot"/><stop offset="1" class="l4rg4-bid"/></radialGradient><radialGradient id="izHqxhc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.597 18.17 9.023)scale(6.81742 .9881)" gradientUnits="userSpaceOnUse"><stop class="rzqjthgas"/><stop offset="1" class="ejynn6b3w"/></radialGradient><radialGradient id="iRWdjce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80897 .6578 -1.95135 -5.36624 12.107 17.902)" gradientUnits="userSpaceOnUse"><stop class="i03-jcbks"/><stop offset="1" class="m27qtcbgg"/></radialGradient><radialGradient id="iYF0W6g" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.026 20.384)" gradientUnits="userSpaceOnUse"><stop offset=".092" class="vla5fnbfs"/><stop offset=".905" class="oi9-i7f4a"/></radialGradient><radialGradient id="i9jR5Vb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.026 24.327)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="qgzgmyhdj"/><stop offset=".937" class="dzrlfbban"/></radialGradient><radialGradient id="iZhzexc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36264 1.13067 -1.10926 -2.3179 28.862 21.975)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="itrGLHc" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .49204 .64628 28.006 21.484)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iRpgU5m" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.242 12.13)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="iF3r9sb" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.762 15.332)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="iFmJfvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.832 16.69)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="iytDpCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.426 17.081)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="ikimp3b" cx="0" cy="0" r="1" gradientTransform="rotate(127.034 7.731 16.928)scale(.82985)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="ibrrZTY" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39063 -2.6875 6.04551 -3.1282 15.845 20.226)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="q1ssh2bkr"/><stop offset="1" class="bxgr47tif"/></radialGradient><radialGradient id="iB8QvhC" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5843 -1.90116 0 15.07 18.562)" gradientUnits="userSpaceOnUse"><stop class="gni8qzbvw"/><stop offset=".678" class="s562n-brd"/></radialGradient><radialGradient id="itxn0oc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.20271 -3.11798 0 13.448 17.887)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="l47zbgb1p"/><stop offset="1" class="j7xq08bnc"/></radialGradient><radialGradient id="iELAaFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 25.994 23.49)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iFrvaca" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 25.994 24.91)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ifwTy3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 25.994 26.28)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iGL8Z4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 25.994 27.761)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iGV70gc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 25.994 23.49)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iymeNee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 25.994 24.91)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iFfZt8t" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 25.994 26.28)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iTQOaqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 25.994 27.761)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i0aEdjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49946 -4.50112 0 28.526 23.138)" gradientUnits="userSpaceOnUse"><stop class="b4rjnnb6m"/><stop offset="1" class="bgp-eqwmb"/></radialGradient><radialGradient id="ihvmSKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07077 8.592 12.22)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iUT97Zo" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 20.146 11.956)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="i94dhwc" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 19.733 13.042)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="im8GJme" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -4.972 30.153)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iHWfLuB" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.43448 -12.8068 0 15.038 10.296)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="omg1bbptb"/><stop offset=".952" class="g100vyjzt"/></radialGradient><radialGradient id="iMD1ssb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 17.355 10.95)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iaNJvCS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 12.797 10.916)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="ingLkle" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.974 -8.577)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iQ1Okvc" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -60.35 196.05)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ibaUXGh" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.01 3.62)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iWpeMjd" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 8.561 10.438)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iMxqsnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 15.336 13.827)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="inv3Tve" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91167 6.5247 -8.23847 -3.67645 14.587 6.834)" gradientUnits="userSpaceOnUse"><stop class="po4m-u0pm"/><stop offset="1" class="f13vhyddz"/></radialGradient><radialGradient id="iKElqVW" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29692 1.23651 0 13.053 11.303)" gradientUnits="userSpaceOnUse"><stop class="hkf1_jbsj"/><stop offset="1" class="wrhkd7bsy"/></radialGradient><radialGradient id="inwNTKM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.61362 7.44672 0 13.053 12.21)" gradientUnits="userSpaceOnUse"><stop offset=".958" class="di5ujabpk"/><stop offset="1" class="k959jsblr"/></radialGradient><radialGradient id="ibYZtTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 17.188 11.539)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iqv4XPd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 16.96 11.623)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJxMBee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 12.825 11.539)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iFiShgj" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.057 -.293)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iYHUIfF" x1="16.822" x2="15.424" y1="26.257" y2="25.955" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="i4NNVDX" x1="7.119" x2="5.947" y1="26.056" y2="26.056" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="i5pRw5W" x1="23.048" x2="23.69" y1="26.142" y2="26.111" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iTBk8Vd" x1="22.69" x2="18.315" y1="16.127" y2="28.637" gradientUnits="userSpaceOnUse"><stop class="qm8srpk6b"/><stop offset="1" class="knnk86b5x"/></linearGradient><linearGradient id="inQoOEq" x1="16.744" x2="17.352" y1="26.628" y2="26.692" gradientUnits="userSpaceOnUse"><stop class="o_frn_b6l"/><stop offset="1" class="ohgvqyqas"/></linearGradient><linearGradient id="iLovVHb" x1="20.707" x2="20.707" y1="16.127" y2="16.949" gradientUnits="userSpaceOnUse"><stop offset=".165" class="oy7fe6bjb"/><stop offset="1" class="ivc982b0q"/></linearGradient><linearGradient id="idkDDNd" x1="7.815" x2="11.815" y1="17.767" y2="29.017" gradientUnits="userSpaceOnUse"><stop class="e55i1-bjj"/><stop offset="1" class="rqyrdfbps"/></linearGradient><linearGradient id="iZ5Tvtd" x1="8.27" x2="8.983" y1="15.381" y2="19.437" gradientUnits="userSpaceOnUse"><stop class="agyv0c9kf"/><stop offset="1" class="vxg8xmb_d"/></linearGradient><linearGradient id="iluqQsd" x1="7.815" x2="8.229" y1="22.705" y2="22.502" gradientUnits="userSpaceOnUse"><stop class="maqiohbml"/><stop offset="1" class="qndc1xila"/></linearGradient><linearGradient id="icp5lKc" x1="23.315" x2="21.534" y1="26.173" y2="26.173" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="it060re" x1="8.034" x2="10.315" y1="27.986" y2="26.83" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="icaMlXc" x1="15.032" x2="15.032" y1="17.527" y2="28.631" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iRvOJKe" x1="17.806" x2="15.845" y1="22.217" y2="21.889" gradientUnits="userSpaceOnUse"><stop offset=".196" class="ipymgraih"/><stop offset=".671" class="nazw5jbsw"/></linearGradient><linearGradient id="iX2jM5d" x1="25.659" x2="25.659" y1="15.823" y2="19.88" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="ihp02zd" x1="25.854" x2="25.712" y1="16.759" y2="17.963" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="iNlU4qe" x1="23.156" x2="23.283" y1="16.696" y2="17.133" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="iADf7pd" x1="26.856" x2="24.569" y1="21.266" y2="21.266" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="iK2iP8c" x1="24.386" x2="24.767" y1="21.109" y2="21.081" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="i7w24yc" x1="27.004" x2="26.742" y1="20.98" y2="20.956" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="ioJT1wb" x1="27.917" x2="23.048" y1="26.514" y2="26.514" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="iUTG8Mc" x1="27.917" x2="23.048" y1="26.514" y2="26.514" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="iaqgdKc" x1="23.663" x2="25.583" y1="24.311" y2="24.311" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i75SdFj" x1="23.663" x2="25.583" y1="25.753" y2="25.753" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iNrwJme" x1="23.663" x2="25.583" y1="27.183" y2="27.183" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iZsMuwc" x1="10.262" x2="9.621" y1="12.499" y2="12.499" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iy8ilne" x1="20.86" x2="20.042" y1="11.129" y2="13.665" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iuNtIid" x1="19.045" x2="11.409" y1="12.61" y2="13.748" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="ibczYWd" x1="9.367" x2="12.725" y1="14.137" y2="14.251" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iwG26yb" x1="9.614" x2="11.495" y1="15.306" y2="15.239" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="i3MTGeD" x1="14.478" x2="22.621" y1="9.626" y2="6.71" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="ijIGSye" x1="14.145" x2="15.083" y1="13.269" y2="13.269" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="i5OUYnm" x1="15.947" x2="14.922" y1="13.592" y2="13.577" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="ikgOBzD" x1="15.204" x2="15.204" y1="14.334" y2="13.761" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iZhGjpb" x1="15.135" x2="15.135" y1="14.376" y2="14.209" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="ibYFeSb" x1="13.972" x2="14.407" y1="15.949" y2="15.262" gradientUnits="userSpaceOnUse"><stop class="bci7l0baj"/><stop offset=".663" class="o_o8tpbqw"/></linearGradient><linearGradient id="ijpRPsb" x1="17.966" x2="17.652" y1="11.593" y2="11.786" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inNi7dd" x1="13.569" x2="13.255" y1="11.593" y2="11.786" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLjl0Dq" x1="17.981" x2="17.561" y1="9.453" y2="8.595" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="isomTTb" x1="12.677" x2="11.488" y1="9.326" y2="8.827" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><filter id="idgyKfd" width="5.513" height="4.74" x="12.768" y="23.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/></filter><filter id="iST4aHb" width="6.102" height="1.228" x="22.711" y="16.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/></filter><filter id="iIrkwjQ" width="1.075" height="1.075" x="25.119" y="20.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2326" result="effect2_innerShadow_4002_2326"/></filter><filter id="i7NMNzb" width="5.967" height="5.967" x="12.086" y="14.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".125"/></filter><filter id="izbssTc" width="5.612" height="5.612" x="12.264" y="15.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".2"/></filter><filter id="iSkki1c" width="5.369" height="6.076" x="23.048" y="22.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/></filter><filter id="iPACLBe" width="5.369" height="6.076" x="23.048" y="22.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/></filter><filter id="iFc4N8c" width="2.319" height=".3" x="23.513" y="24.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".05"/></filter><filter id="i9e45Kr" width="2.319" height=".3" x="23.513" y="25.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".05"/></filter><filter id="iDbJbJb" width="2.319" height=".3" x="23.513" y="26.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".05"/></filter><filter id="if4iAva" width="3.539" height="3.339" x="8.592" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/></filter><filter id="iLmeind" width="2.99" height="2.99" x="8.767" y="10.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".25"/></filter><filter id="iORb7dd" width="3.589" height="3.589" x="18.105" y="10.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/></filter><filter id="iKMq3xd" width="2.99" height="2.99" x="18.279" y="10.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".25"/></filter><filter id="iakklPb" width="10.373" height="12.127" x="9.852" y="6.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/></filter><filter id="iXTtqfe" width="8.246" height="7.066" x="13.179" y="4.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation="1"/></filter><filter id="i0f7dob" width="12.601" height="8.543" x="8.709" y="3.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/></filter><filter id="i9xXktb" width="3.26" height="4.181" x="13.14" y="11.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".375"/></filter><filter id="iHPKZPc" width="2.377" height="3.181" x="13.821" y="11.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".125"/></filter><filter id="iSo6bab" width="2.979" height="1.873" x="16.191" y="8.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/></filter><filter id="iC7MBqe" width="2.98" height="1.873" x="11.044" y="8.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2326"/></filter><filter id="ii7OYqd" width=".787" height=".696" x="16.454" y="11.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".05"/></filter><filter id="i2gVKBg" width=".891" height=".913" x="17.294" y="11.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".1"/></filter><filter id="iuySt1d" width=".986" height="1.04" x="12.852" y="11.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".1"/></filter><filter id="ih1UYIZ" width=".913" height=".704" x="12.097" y="11.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".05"/></filter><filter id="iz7FBrb" width="2.599" height="1.181" x="16.295" y="8.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".125"/></filter><filter id="iCSq32d" width="2.677" height="1.238" x="11.076" y="9.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2326" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-singer-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.acjl_f-ty {
  cx: 19.774px;
  cy: 12.221px;
  r: 0.995px;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.agyv0c9kf {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.atb2q5h3d {
  cx: 12.554px;
  cy: 11.443px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b2yaby8wi {
  d: path("M14.964 6.597c-.901.004-1.671.066-2.299.146l-2.106 6.202h1.809l-.508 2.687l3.688-5.132h-1.883z");
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

.bci7l0baj {
  stop-color: var(--svg-color--ecb5aa, #ECB5AA);
}

.bgp-eqwmb {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
  stop-opacity: 0;
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.bxgr47tif {
  stop-color: var(--svg-color--d48070, #D48070);
}

.bzyfxrbvp {
  fill: var(--svg-color--242324, #242324);
  d: path("m19.828 5.744l.429.213c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.215-.213-.376-.533-.376-.853v-.853c0-.267-.214-.48-.428-.534c-.644-.16-1.985-.426-3.916-.426s-3.272.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.429-.212c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.587");
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.ct-uzm47t {
  cx: 19.774px;
  cy: 12.221px;
  r: 1.669px;
}

.ctk9r0bck {
  d: path("M12.823 11.062a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.di5ujabpk {
  stop-color: var(--svg-color--f0276f, #F0276F);
  stop-opacity: 0;
}

.dqxippkig {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.616 10.79c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.dzrlfbban {
  stop-color: var(--svg-color--c1745e, #C1745E);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e55i1-bjj {
  stop-color: var(--svg-color--e86b1f, #E86B1F);
}

.ejynn6b3w {
  stop-color: var(--svg-color--ef5945, #EF5945);
  stop-opacity: 0;
}

.ekw2c2fxt {
  d: path("M6.998 28.627h3.87l-3.87-7.596z");
}

.el_trbcqu {
  d: path("m18.972 6.597l-3.077 1.026a1.047 1.047 0 0 0 .47 2.03l3.06-.409z");
}

.eqiyjytvm {
  d: path("m14.627 11.936l-.531 1.699a.54.54 0 0 0 .52.7h.786a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.f13vhyddz {
  stop-color: var(--svg-color--e9295e, #E9295E);
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fia60pksa {
  d: path("M13.638 11.85c0-.289-.234-.481-.298-.54l-.288.28l.178.36z");
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.fu2ep6afb {
  d: path("M17.985 11.837a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g100vyjzt {
  stop-color: var(--svg-color--cb8ba1, #CB8BA1);
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g7kuvkbic {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.45 9.875c.328-.29 1.042-.594 1.928-.452");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gni8qzbvw {
  stop-color: var(--svg-color--ce7d85, #CE7D85);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h0u13vboz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.124 11.25c.064.086-.069.19-.22.302c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hcsxltfci {
  d: path("M27.197 20.952c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hi_lf-b6x {
  fill: var(--svg-color--000, #000);
  d: path("M13.334 11.954a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.745h.904a.5.5 0 0 0 .061-.235");
}

.hkf1_jbsj {
  stop-color: var(--svg-color--be2252, #BE2252);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hu-xsvbmv {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m14.734 12.099l-.82 1.7c-.102.349.142.698.488.698h.737c.345 0 .59-.355.488-.699l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.i03-jcbks {
  stop-color: var(--svg-color--d14708, #D14708);
}

.i98yq5blv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.663 25.674h2.019");
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.igkmnnmew {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m18.729 9.501l-.002-.001l-.002-.001l-.004-.004l-.012-.01l-.036-.027a2.6 2.6 0 0 0-.539-.291a2.83 2.83 0 0 0-1.492-.158a.534.534 0 0 0 .166 1.054c.398-.063.716.01.934.097a1.5 1.5 0 0 1 .3.16l.008.005a.534.534 0 0 0 .678-.824");
}

.ikan01biz {
  d: path("M6.998 28.627v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.ipymgraih {
  stop-color: var(--svg-color--bf7161, #BF7161);
}

.ivc982b0q {
  stop-color: var(--svg-color--e48043, #E48043);
  stop-opacity: 0;
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j7xq08bnc {
  stop-color: var(--svg-color--e08a82, #E08A82);
  stop-opacity: 0;
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k959jsblr {
  stop-color: var(--svg-color--f0276f, #F0276F);
}

.knnk86b5x {
  stop-color: var(--svg-color--d53939, #D53939);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.kxkx5kfke {
  d: path("m28.134 16.668l-4.844-.02a.57.57 0 0 0-.579.578c0 .325.254.579.58.579l4.843.02a.57.57 0 0 0 .579-.579a.585.585 0 0 0-.58-.578");
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l47zbgb1p {
  stop-color: var(--svg-color--e08a82, #E08A82);
}

.l4rg4-bid {
  stop-color: var(--svg-color--f6874a, #F6874A);
  stop-opacity: 0;
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lsxcn4bfz {
  d: path("M17.19 11.062a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lya432q3n {
  cx: 10.262px;
  cy: 12.221px;
  r: 0.995px;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m0r2shmnv {
  d: path("M12.768 23.887v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.m27qtcbgg {
  stop-color: var(--svg-color--d14708, #D14708);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.maqiohbml {
  stop-color: var(--svg-color--ec7046, #EC7046);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.medc3dbxd {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.647 14.978c.394.205.862.322 1.362.322a2.94 2.94 0 0 0 1.362-.322a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.24m-2.986-.28l2.945.253m-2.945-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.22.253m3.207.028l-.042-.028m.042.028l-.042-.028m.042.028a1.94 1.94 0 0 1-1.625.868c-.682 0-1.28-.347-1.624-.868m3.207-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.mgz0e9bgo {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.768 23.887v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.mnp72frot {
  stop-color: var(--svg-color--f6874a, #F6874A);
}

.n-e13gbqy {
  d: path("M26.938 28.627c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nazw5jbsw {
  stop-color: var(--svg-color--db9282, #DB9282);
  stop-opacity: 0;
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.o_frn_b6l {
  stop-color: var(--svg-color--cc2820, #CC2820);
}

.o_o8tpbqw {
  stop-color: var(--svg-color--ecb5aa, #ECB5AA);
  stop-opacity: 0;
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.ohgvqyqas {
  stop-color: var(--svg-color--cc2820, #CC2820);
  stop-opacity: 0;
}

.oi9-i7f4a {
  stop-color: var(--svg-color--d17e71, #D17E71);
}

.omg1bbptb {
  stop-color: var(--svg-color--e7abac, #E7ABAC);
  stop-opacity: 0;
}

.oy7fe6bjb {
  stop-color: var(--svg-color--e48043, #E48043);
}

.p0kdb-eay {
  cx: 10.262px;
  cy: 12.221px;
  r: 1.669px;
}

.pcf3ofbyz {
  d: path("M15.038 17.527c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.pfw33cdrd {
  cx: 12.554px;
  cy: 11.443px;
  rx: 0.389px;
  ry: 0.197px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn3itgrui {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.397 10.79c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.po4m-u0pm {
  stop-color: var(--svg-color--ff338e, #FF338E);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q1ssh2bkr {
  stop-color: var(--svg-color--edaa9c, #EDAA9C);
}

.q3uzgebbz {
  d: path("M25.656 21.755a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
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

.qcej8hbyf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.663 24.233h2.019");
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qgzgmyhdj {
  stop-color: var(--svg-color--c1745e, #C1745E);
  stop-opacity: 0;
}

.qhr695bog {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.663 27.105h2.019");
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qm8srpk6b {
  stop-color: var(--svg-color--f98026, #F98026);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qndc1xila {
  stop-color: var(--svg-color--ec7046, #EC7046);
  stop-opacity: 0;
}

.quz_fjzco {
  d: path("M9.852 10.17c0-.267.107-.587.321-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.534c.643-.16 1.984-.426 3.915-.426s3.272.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.546.43.96c-.055.534-.108 1.44-.108 1.44h.018l-.266 3.958c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.234-3.21-3.003c-.14-1.816-.2-3.638-.366-5.451");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rk6j68bhd {
  d: path("M23.048 23.514a.81.81 0 0 1 .816-.802h3.055c.744 0 1.348.588 1.348 1.315v3.514c0 .605-.503 1.096-1.124 1.096h-3.279a.81.81 0 0 1-.816-.802c0-.314.187-.589.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.721a.8.8 0 0 1-.458-.72");
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rqyrdfbps {
  stop-color: var(--svg-color--e22f38, #E22F38);
}

.rsdkd7bet {
  d: path("M17.124 11.25c.064.086-.069.19-.22.302c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rzqjthgas {
  stop-color: var(--svg-color--ef5945, #EF5945);
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s562n-brd {
  stop-color: var(--svg-color--d78889, #D78889);
}

.s8nm5zbxc {
  d: path("M15.038 16.44c-1.16 0-2.486.209-3.566.58l1.29 6.873c.72.325 1.496.434 2.316.434c.77 0 1.51-.074 2.19-.352l1.313-6.955c-1.05-.383-2.383-.58-3.543-.58");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.se40-pr3g {
  cx: 19.774px;
  cy: 12.221px;
  r: 0.995px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.t_d_hcclh {
  d: path("M25.687 19.826a2.498 2.498 0 1 0 0-4.996a2.498 2.498 0 0 0 0 4.996");
}

.t_n_cwbft {
  d: path("M23.048 28.627V21.36l-3.52 7.268z");
}

.t620_nb8y {
  fill: var(--svg-color--000, #000);
  d: path("M16.679 11.954c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.745h-.904a.46.46 0 0 1-.061-.235");
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.uc7o5pbpu {
  d: path("M25.646 26.467a.784.784 0 0 1-.782-.71l-.67-6.429l2.975.01l-.73 6.428a.8.8 0 0 1-.793.701");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.umvlo82vr {
  d: path("m19.828 5.744l.429.213c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.215-.213-.376-.533-.376-.853v-.853c0-.267-.214-.48-.428-.534c-.644-.16-1.985-.426-3.916-.426s-3.272.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.429-.212c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.587");
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.ve34ncchz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.67 9.356c.43-.075 1.268-.053 1.849.398");
}

.vla5fnbfs {
  stop-color: var(--svg-color--f7b6a5, #F7B6A5);
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.vxg8xmb_d {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
  stop-opacity: 0;
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.weui8osko {
  cx: 15.07px;
  cy: 17.887px;
  r: 2.406px;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wrhkd7bsy {
  stop-color: var(--svg-color--be2252, #BE2252);
  stop-opacity: 0;
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x7omq0bvx {
  cx: 15.07px;
  cy: 17.777px;
  r: 2.734px;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.y9ijw_6_e {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m14.627 11.936l-.531 1.699a.54.54 0 0 0 .52.7h.786a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yoe2fy8iq {
  d: path("M5.325 16.648h6.086l2.248 11.99h-2.79l-5.88-11.53c-.086-.124-.07-.46.336-.46");
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zakn8hfha {
  d: path("M24.233 16.64h-5.58L16.38 28.638h3.148l5.325-11.016a.685.685 0 0 0-.62-.98");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zja74brvl {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.236 9.501l.002-.001l.001-.001l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.063.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.16a.534.534 0 1 1-.167 1.055a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.3.16l-.008.005a.534.534 0 0 1-.68-.824");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
