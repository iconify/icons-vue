<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iv8XkMe" class="wzdctp9kn"/></defs><g class="ft5dv1b6b"><path fill="url(#idHi0yd)" class="ahgesybkv"/><path fill="url(#igIIhob)" class="ahgesybkv"/><path fill="url(#iIh9GPb)" class="v61sblb7d"/><path fill="url(#ittsDUY)" class="v61sblb7d"/><path fill="url(#iryW3Mb)" class="v61sblb7d"/><path fill="url(#ibnmEae)" class="v61sblb7d"/><path fill="url(#ijEdY9I)" class="v61sblb7d"/><g filter="url(#ity7VSc)"><path class="mo447j6oa"/></g><path fill="url(#igtyVBb)" class="fp9nigtju"/><path fill="url(#iOLiG5c)" class="fp9nigtju"/><path fill="url(#iEa5YZb)" class="fp9nigtju"/><g filter="url(#i0t9JmT)"><path fill="url(#iiBL37x)" class="c9pld-b_v"/></g><path fill="url(#ijYXwTb)" clip-rule="evenodd" class="rbn6gq-_t"/><path fill="url(#isbi4Ud)" clip-rule="evenodd" class="rbn6gq-_t"/><path fill="url(#i6qK5Tc)" class="x23lmh86f"/><path fill="url(#iiqnAFS)" class="x23lmh86f"/><path fill="url(#ibQDhye)" class="x23lmh86f"/><g filter="url(#iuJStHe)"><path fill="url(#isiuShe)" class="s741zy-bl"/></g><g filter="url(#ipGUmje)"><path fill="url(#iX65Ucd)" class="oak20zbgw"/></g><path fill="url(#iYIBYqb)" class="vz_jd7bpk"/><path fill="url(#i3DNVfq)" class="gjsehwwuq"/><path fill="url(#i5T9Npq)" class="gjsehwwuq"/><path fill="url(#ixQ5Nsd)" class="gjsehwwuq"/><path fill="url(#itOZStd)" transform="rotate(7.73 23.732 10.71)" class="fccgeqb8w"/><g filter="url(#iqx0J0d)"><path fill="url(#iVDx1Oc)" class="a4lkrc58w"/><path fill="url(#ic3txJd)" class="a4lkrc58w"/></g><path fill="url(#iTXPOSb)" clip-rule="evenodd" class="frrxlabhk"/><path fill="url(#iDhoExb)" clip-rule="evenodd" class="tvxb7fbew"/><path fill="url(#iOUwsOe)" clip-rule="evenodd" class="tvxb7fbew"/><path clip-rule="evenodd" class="xv3ew_rhj"/><path class="yeh75achz"/><path class="p3xx7436g"/><path fill="url(#ifRF47d)" class="ertkgkbxh"/><path fill="url(#iaiXqcc)" class="ertkgkbxh"/><path class="h5dbk_bsu"/><path fill="url(#iPQxqYb)" class="mhphw6beu"/><path fill="url(#i0Nh4vd)" class="mhphw6beu"/><path fill="url(#i6z08ge)" class="mhphw6beu"/><path fill="url(#iYzRJAc)" class="mhphw6beu"/><path fill="url(#ibinEue)" class="fm0afk-vi"/><path class="wj6gnkm5z"/><circle class="rwh4nem5s"/><path fill="url(#iUMKGue)" class="zeblypklz"/><path fill="url(#iPP3FMc)" class="zeblypklz"/><path fill="url(#ia11ELd)" class="zeblypklz"/><path fill="url(#iZJqswd)" class="zeblypklz"/><path fill="url(#ijPohLc)" class="zeblypklz"/><g filter="url(#iesxtBc)"><path class="c4-xgac8o"/><path fill="url(#iLosAnc)" class="l--a2qfwv"/><path fill="url(#iuHQaCc)" class="l--a2qfwv"/><path fill="url(#ixUqaxd)" class="l--a2qfwv"/></g><g filter="url(#iKrNtke)"><path class="uih7j62uq"/><path fill="url(#iCQSFhd)" class="oityxhb6t"/></g><g filter="url(#itAF40R)"><use href="#iv8XkMe"/><path fill="url(#icBx3md)" class="gniigpvgz"/><path fill="url(#iDhPGTb)" class="gniigpvgz"/><path fill="url(#irz0EMe)" class="gniigpvgz"/></g><g filter="url(#itAF40R)"><use href="#iv8XkMe"/><path fill="url(#icBx3md)" class="gniigpvgz"/><path fill="url(#iDhPGTb)" class="gniigpvgz"/><path fill="url(#irz0EMe)" class="gniigpvgz"/></g><g filter="url(#ii5Gzvt)"><path class="f7u0jwbsk"/><path fill="url(#iVt987c)" class="x-rptobqt"/></g><path fill="url(#ihR3u7b)" clip-rule="evenodd" class="eqotxcc-k"/><path fill="url(#iXpDYXd)" clip-rule="evenodd" class="eqotxcc-k"/><path fill="url(#iJoYojc)" clip-rule="evenodd" class="eqotxcc-k"/><path class="pwtzxgbrf"/><path fill="url(#inHlC3d)" class="b0o7t_zgm"/><path class="far36mbdt"/><path class="hyc27rbhn"/><path fill="url(#isQtXVb)" class="hcvg7nkpf"/><path class="b_mvr5wmr"/><path fill="url(#iW3Yvoe)" class="t1a_1erft"/><path class="uxjdqcbxn"/><path fill="url(#iOrISFc)" class="ojugehbmx"/><g filter="url(#i9mwqEc)"><path fill="url(#iUOKGbK)" class="nc9r4es_c"/></g><circle fill="url(#iyKzFpP)" class="n_ty1xo5o"/><path clip-rule="evenodd" class="l1g-dybni"/><path fill="url(#iy3k66d)" clip-rule="evenodd" class="ybhyf2epg"/><path fill="url(#iHVd2fc)" clip-rule="evenodd" class="ybhyf2epg"/><path fill="url(#iI72Ljg)" clip-rule="evenodd" class="ybhyf2epg"/><g filter="url(#iFzLNre)"><path fill="url(#iuanAjb)" class="mg-3dob_j"/></g><g filter="url(#i03349j)"><path fill="url(#izBtN2d)" class="acayj_b_q"/></g><path class="h6ph56q8k"/><path fill="url(#iSjiw4b)" class="d1woopb1r"/><g filter="url(#iiz5QIc)"><path clip-rule="evenodd" class="f55p1ttmn"/></g><path fill="url(#iMmEoiT)" class="zqorby9td"/><path fill="url(#iDvf2id)" class="zqorby9td"/><path fill="url(#iX1MF7J)" class="zqorby9td"/><path fill="url(#idBZpMd)" class="i5y-62b3j"/><path fill="url(#i6AshMd)" class="i5y-62b3j"/><path fill="url(#iYczeFp)" class="i5y-62b3j"/><defs><radialGradient id="idHi0yd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.507 28.406)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="iryW3Mb" cx="0" cy="0" r="1" gradientTransform="rotate(-83.29 17.143 5.136)scale(2.67447 5.21781)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="ibnmEae" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 3.164 10.59)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="ijEdY9I" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.913 21.281)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="iEa5YZb" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.493 5.214)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="ijYXwTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 5.5625 -3.9363 .81822 20.32 7.094)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="evtzj4w-l"/><stop offset=".835" class="w2qvy2bqh"/></radialGradient><radialGradient id="isbi4Ud" cx="0" cy="0" r="1" gradientTransform="rotate(128.66 8.976 10.988)scale(2.00098 3.31295)" gradientUnits="userSpaceOnUse"><stop offset=".282" class="fyz-jkb0e"/><stop offset="1" class="hpk6n8y3i"/></radialGradient><radialGradient id="iiqnAFS" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.356 8.444)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="isiuShe" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 13.163 7.281)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="iYIBYqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00002 .65234 -.82062 -.00003 22.875 7.986)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="b-0qxxbtd"/><stop offset="1" class="ql-kjsbnq"/></radialGradient><radialGradient id="i5T9Npq" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.554 21.484)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="ixQ5Nsd" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.476 19.004)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="itOZStd" cx="0" cy="0" r="1" gradientTransform="matrix(.02504 1.46228 -1.51109 .02587 25.118 11.572)" gradientUnits="userSpaceOnUse"><stop class="f71zwr8du"/><stop offset="1" class="tcd28tbzr"/></radialGradient><radialGradient id="iVDx1Oc" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 23.164 8.578)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="epfp24bqk"/><stop offset="1" class="l8ufshbax"/></radialGradient><radialGradient id="ic3txJd" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.371 11.932)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="n4-no9-8p"/><stop offset="1" class="vq765rbep"/></radialGradient><radialGradient id="iOUwsOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 26.011 19.375)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="ifRF47d" cx="0" cy="0" r="1" gradientTransform="matrix(.85473 .16352 -.6869 3.5905 18.756 21.7)" gradientUnits="userSpaceOnUse"><stop class="no6b1u88o"/><stop offset="1" class="i4mykacuf"/></radialGradient><radialGradient id="iaiXqcc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.812 19.045 6.267)scale(6.15653 2.09594)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="ozlo8mb6b"/><stop offset="1" class="bg6f0-hut"/></radialGradient><radialGradient id="iPQxqYb" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.203 9.849)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="i0Nh4vd" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.84 13.188)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="iYzRJAc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 23.1 28.094)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="iPP3FMc" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 10.173 11.683)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="aamjxwftu"/><stop offset="1" class="kbmwaf_hi"/></radialGradient><radialGradient id="ia11ELd" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.85 11.578)" gradientUnits="userSpaceOnUse"><stop class="xs_2ilnpm"/><stop offset="1" class="p8p5c3bvm"/></radialGradient><radialGradient id="iZJqswd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06251 1.12498 -.6497 -1.19113 22.929 13.953)" gradientUnits="userSpaceOnUse"><stop class="am3w7_blp"/><stop offset="1" class="couxg3lqo"/></radialGradient><radialGradient id="ijPohLc" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.507 15.11)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="dq08bkdrq"/><stop offset="1" class="wqel62b_c"/></radialGradient><radialGradient id="iLosAnc" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.695 21.625)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="iuHQaCc" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 20.241 19.5)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="ixUqaxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 22.116 19.422)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="icBx3md" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.6 17.688)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="irz0EMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.304 17.031)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="iVt987c" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.539 19.188)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="iJoYojc" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.96 15.984)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="inHlC3d" cx="0" cy="0" r="1" gradientTransform="matrix(.6333 -1.00782 1.01131 .6355 19.85 7.852)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="ew7s9bbrw"/><stop offset="1" class="en8gd7b2r"/></radialGradient><radialGradient id="iUOKGbK" cx="0" cy="0" r="1" gradientTransform="rotate(126.754 10.935 11.63)scale(1.54063 1.00944)" gradientUnits="userSpaceOnUse"><stop class="je1gq9b0e"/><stop offset="1" class="bmetj0s5v"/></radialGradient><radialGradient id="iyKzFpP" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.62 18.78)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="hihmuwfbc"/><stop offset="1" class="ykx68ubdn"/></radialGradient><radialGradient id="iI72Ljg" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.952 9.484)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="iuanAjb" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.737 9.879)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="izBtN2d" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45313 1.162 .94162 25.663 8.187)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="iMmEoiT" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.527 6.799)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="iDvf2id" cx="0" cy="0" r="1" gradientTransform="matrix(1.15626 -3.3125 9.2644 3.23382 19.74 19.439)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="xq-3t8b8y"/><stop offset="1" class="wy97-4axq"/></radialGradient><radialGradient id="iX1MF7J" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -1.896 19.816)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="idBZpMd" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.468 16.139)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="k2smfncym"/><stop offset="1" class="nr_9l6l2k"/></radialGradient><radialGradient id="iYczeFp" cx="0" cy="0" r="1" gradientTransform="matrix(-.92187 .21875 -.25309 -1.06657 24.695 12.906)" gradientUnits="userSpaceOnUse"><stop class="vgv_qabik"/><stop offset="1" class="muvudkmkj"/></radialGradient><linearGradient id="igIIhob" x1="11.438" x2="11.438" y1="29.953" y2="28.658" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="iIh9GPb" x1="5.32" x2="6.476" y1="17.531" y2="20.813" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="ittsDUY" x1="5.82" x2="6.163" y1="17.531" y2="18.5" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="igtyVBb" x1="13.413" x2="11.57" y1="1.844" y2="14.969" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="iOLiG5c" x1="2.601" x2="13.132" y1="17.719" y2="13.563" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="iiBL37x" x1="14.269" x2="16.87" y1="10.67" y2="15.188" gradientUnits="userSpaceOnUse"><stop offset=".368" class="scgoxofxx"/><stop offset="1" class="f0ht81bay"/></linearGradient><linearGradient id="i6qK5Tc" x1="4.507" x2="6.882" y1="5.25" y2="13.531" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="ibQDhye" x1="5.788" x2="5.507" y1="14.141" y2="13.141" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="iX65Ucd" x1="19.576" x2="20.935" y1="10.952" y2="15.612" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="i3DNVfq" x1="25.101" x2="26.507" y1="20.297" y2="20.297" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="iTXPOSb" x1="24.875" x2="24.601" y1="18.559" y2="18.559" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="iDhoExb" x1="26.491" x2="24.475" y1="19.837" y2="19" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="i6z08ge" x1="23.261" x2="23.155" y1="27.918" y2="27.836" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="ibinEue" x1="23.659" x2="23.905" y1="8.242" y2="7.805" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="iUMKGue" x1="24.882" x2="22.695" y1="15.812" y2="12" gradientUnits="userSpaceOnUse"><stop class="r1kmajh1r"/><stop offset="1" class="dwwl7kmwu"/></linearGradient><linearGradient id="iCQSFhd" x1="18.648" x2="18.304" y1="15.328" y2="15.984" gradientUnits="userSpaceOnUse"><stop class="i8moqbc4d"/><stop offset="1" class="t2uzah3ri"/><stop offset="1" class="okfvj-bpf"/></linearGradient><linearGradient id="iDhPGTb" x1="20.132" x2="21.101" y1="20.102" y2="17.125" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="ihR3u7b" x1="23.103" x2="23.103" y1="16.688" y2="18.125" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="iXpDYXd" x1="24.296" x2="24.527" y1="18.215" y2="17.77" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="isQtXVb" x1="15.617" x2="15.945" y1="11.711" y2="11.328" gradientUnits="userSpaceOnUse"><stop offset=".002" class="qkaxllo7y"/><stop offset=".991" class="c9rmxacdl"/></linearGradient><linearGradient id="iW3Yvoe" x1="15.757" x2="15.96" y1="11.328" y2="11.125" gradientUnits="userSpaceOnUse"><stop class="gqq-31bxk"/><stop offset="1" class="m9e3ckbiz"/></linearGradient><linearGradient id="iOrISFc" x1="16.015" x2="16.24" y1="10.937" y2="10.708" gradientUnits="userSpaceOnUse"><stop class="gqq-31bxk"/><stop offset="1" class="m9e3ckbiz"/></linearGradient><linearGradient id="iy3k66d" x1="24.945" x2="24.624" y1="9.838" y2="9.594" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="iHVd2fc" x1="23.491" x2="23.929" y1="10.391" y2="10.68" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="iSjiw4b" x1="16.444" x2="16.668" y1="10.71" y2="10.518" gradientUnits="userSpaceOnUse"><stop class="gqq-31bxk"/><stop offset="1" class="m9e3ckbiz"/></linearGradient><linearGradient id="i6AshMd" x1="23.21" x2="23.085" y1="14.719" y2="13.797" gradientUnits="userSpaceOnUse"><stop class="m3e4macxz"/><stop offset="1" class="j6phqvxik"/></linearGradient><filter id="ity7VSc" width="8.743" height="7.346" x="1.956" y="23.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_851" result="effect2_innerShadow_4002_851"/></filter><filter id="i0t9JmT" width="4.276" height="5.599" x="13.345" y="9.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_851" stdDeviation=".375"/></filter><filter id="iuJStHe" width="3.479" height="7.738" x="13.92" y="1.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter><filter id="ipGUmje" width="2.822" height="15.029" x="19.286" y="2.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter><filter id="iqx0J0d" width="4.43" height="4.257" x="21.992" y="6.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.458824 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter><filter id="iesxtBc" width="5.527" height="3.544" x="18.964" y="18.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter><filter id="iKrNtke" width="9.577" height="5.489" x="9.645" y="14.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.505882 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter><filter id="itAF40R" width="6.672" height="5.002" x="18.132" y="15.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter><filter id="ii5Gzvt" width="2.568" height="3.646" x="9.622" y="16.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter><filter id="i9mwqEc" width="2.604" height="2.473" x="25.109" y="8.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.388235 0 0 0 0 0.00784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter><filter id="iFzLNre" width="4.913" height="4.647" x="23.386" y="5.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter><filter id="i03349j" width="1.588" height="1.361" x="25.048" y="7.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter><filter id="iiz5QIc" width="6.514" height="4.796" x="15.609" y="10.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.615686 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_851"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-climbing" /></template>
<style>
.a4lkrc58w {
  d: path("M22.312 9.43c.277-.875.95-1.815 1.21-2.188l2.9 1.867l-.594 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.aamjxwftu {
  stop-color: var(--svg-color--53bfff, #53BFFF);
}

.acayj_b_q {
  d: path("M25.111 7.396a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.368.479l-.984-.758a.3.3 0 0 1-.055-.423");
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.ahgesybkv {
  d: path("M2.356 29.953V21l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.113 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.557l5 4.752z");
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.am3w7_blp {
  stop-color: var(--svg-color--1b7eec, #1B7EEC);
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.b_mvr5wmr {
  fill: var(--svg-color--ffbe3a, #FFBE3A);
  d: path("M15.04 10.67a.28.28 0 1 1 .368-.421l1.5 1.31l-.368.42z");
}

.b-0qxxbtd {
  stop-color: var(--svg-color--ebab2a, #EBAB2A);
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.b0o7t_zgm {
  d: path("M20.484 6.883a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.bg6f0-hut {
  stop-color: var(--svg-color--f9ad35, #F9AD35);
  stop-opacity: 0;
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biyiff5mh {
  stop-color: var(--svg-color--333061, #333061);
}

.bmetj0s5v {
  stop-color: var(--svg-color--ea8e18, #EA8E18);
}

.boi6lnlog {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
}

.bpm5gvbdi {
  stop-color: var(--svg-color--e5e3e5, #E5E3E5);
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.c4-xgac8o {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.464 20.666l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.c9pld-b_v {
  d: path("m16.87 12.263l-.06.425c-.113.802-.39 1.194-.87 1.488l-.857-1.286l-.946-1.329a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .292-.433l-.024-.033a.28.28 0 1 1 .455-.323l.107.146a.28.28 0 0 1 .5-.223l.499.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345a4 4 0 0 0-.06.6c.001.39.072.613.158.788");
}

.c9rmxacdl {
  stop-color: var(--svg-color--eda33a, #EDA33A);
  stop-opacity: 0;
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.couxg3lqo {
  stop-color: var(--svg-color--1b7eec, #1B7EEC);
  stop-opacity: 0;
}

.d1woopb1r {
  d: path("M15.765 9.923a.28.28 0 0 1 .367-.42l1.41 1.419l-.226.512z");
}

.dfv3zlvmf {
  stop-color: var(--svg-color--648431, #648431);
}

.dnpfueb4s {
  stop-color: var(--svg-color--40347f, #40347F);
}

.dq08bkdrq {
  stop-color: var(--svg-color--67a3db, #67A3DB);
}

.dwwl7kmwu {
  stop-color: var(--svg-color--4d94cd, #4D94CD);
}

.e_59tbbed {
  stop-color: var(--svg-color--292557, #292557);
}

.e2k-esbpn {
  stop-color: var(--svg-color--c3c0c6, #C3C0C6);
  stop-opacity: 0;
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.eky141x3a {
  stop-color: var(--svg-color--489778, #489778);
}

.en8gd7b2r {
  stop-color: var(--svg-color--e7a61e, #E7A61E);
  stop-opacity: 0;
}

.epfp24bqk {
  stop-color: var(--svg-color--f5b63d, #F5B63D);
}

.eqotxcc-k {
  fill-rule: evenodd;
  d: path("M21.072 15.75a.25.25 0 0 1 .341-.092l3.629 2.09a.25.25 0 1 1-.25.433l-3.628-2.09a.25.25 0 0 1-.092-.34");
}

.ertkgkbxh {
  d: path("m19.195 20.953l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.evtzj4w-l {
  stop-color: var(--svg-color--fcc338, #FCC338);
}

.ew7s9bbrw {
  stop-color: var(--svg-color--e7a61e, #E7A61E);
}

.f0ht81bay {
  stop-color: var(--svg-color--ba9f92, #BA9F92);
  stop-opacity: 0;
}

.f2xkzabrk {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
  stop-opacity: 0;
}

.f2yuiwowd {
  stop-color: var(--svg-color--948b99, #948B99);
}

.f55p1ttmn {
  fill: var(--svg-color--ffc22a, #FFC22A);
  fill-rule: evenodd;
  d: path("m18.264 14.197l-2.655-2.435l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.422l.433 1.695l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.f71zwr8du {
  stop-color: var(--svg-color--ffb032, #FFB032);
}

.f7u0jwbsk {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m12.14 20.012l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.113c.381.2 1.143.894 1.492 1.214l.012-.008z");
}

.far36mbdt {
  fill: var(--svg-color--fdbe2c, #FDBE2C);
  d: path("m16.78 9.97l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.fccgeqb8w {
  d: path("M23.732 10.709h1.905v1.844h-1.905z");
}

.fiw9fyalo {
  stop-color: var(--svg-color--4b4386, #4B4386);
}

.fm0afk-vi {
  d: path("m23.83 8.35l.026-.04c.131-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
}

.fp9nigtju {
  d: path("M14.803 14.688L2.356 19.05V2.008H18.3c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.frrxlabhk {
  fill-rule: evenodd;
  d: path("M24.675 17.917c.11 0 .2.09.2.2V19a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
}

.ft5dv1b6b {
  fill: none;
}

.fwnzc4ctw {
  stop-color: var(--svg-color--5a332d, #5A332D);
}

.fy9sosv6u {
  stop-color: var(--svg-color--417c62, #417C62);
  stop-opacity: 0;
}

.fyz-jkb0e {
  stop-color: var(--svg-color--bb8d40, #BB8D40);
}

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
}

.gjsehwwuq {
  d: path("m24.6 19.004l1.907.63v.73a.953.953 0 1 1-1.906 0z");
}

.gniigpvgz {
  d: path("m21.093 16.383l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.gqq-31bxk {
  stop-color: var(--svg-color--f9a925, #F9A925);
}

.gu1w6obkb {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
  stop-opacity: 0;
}

.h5dbk_bsu {
  fill: var(--svg-color--544583, #544583);
  d: path("m23.04 26.157l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.h6ph56q8k {
  fill: var(--svg-color--ffbe3a, #FFBE3A);
  d: path("M15.765 9.923a.28.28 0 0 1 .367-.42l1.41 1.419l-.226.512z");
}

.hcvg7nkpf {
  d: path("M14.965 11.202a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.hihmuwfbc {
  stop-color: var(--svg-color--e1a337, #E1A337);
}

.hpk6n8y3i {
  stop-color: var(--svg-color--ea9425, #EA9425);
  stop-opacity: 0;
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.hyc27rbhn {
  fill: var(--svg-color--ffc22a, #FFC22A);
  d: path("M14.965 11.202a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.i4mykacuf {
  stop-color: var(--svg-color--f7c060, #F7C060);
  stop-opacity: 0;
}

.i5y-62b3j {
  d: path("m21.52 14.992l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
}

.i8moqbc4d {
  stop-color: var(--svg-color--e2a539, #E2A539);
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.j-c4i6bgu {
  stop-color: var(--svg-color--5e598c, #5E598C);
  stop-opacity: 0;
}

.j6phqvxik {
  stop-color: var(--svg-color--2280e0, #2280E0);
  stop-opacity: 0;
}

.jbbp6_bdq {
  stop-color: var(--svg-color--716170, #716170);
  stop-opacity: 0;
}

.je1gq9b0e {
  stop-color: var(--svg-color--ffb32b, #FFB32B);
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k2smfncym {
  stop-color: var(--svg-color--34aef0, #34AEF0);
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kao1--wwn {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
}

.kbmwaf_hi {
  stop-color: var(--svg-color--53bfff, #53BFFF);
  stop-opacity: 0;
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.l--a2qfwv {
  d: path("m19.464 20.666l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.l1g-dybni {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.714 8.448a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.l8ufshbax {
  stop-color: var(--svg-color--eaa131, #EAA131);
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.m3e4macxz {
  stop-color: var(--svg-color--2280e0, #2280E0);
}

.m9e3ckbiz {
  stop-color: var(--svg-color--f9a925, #F9A925);
  stop-opacity: 0;
}

.mg-3dob_j {
  d: path("m27.11 10.014l-3.628-2.696a.22.22 0 0 1-.069-.288a4.8 4.8 0 0 1 .655-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
}

.mhphw6beu {
  d: path("m23.04 26.157l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.mmu9u7bsf {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
}

.mn787q_6r {
  stop-color: var(--svg-color--c7c5c9, #C7C5C9);
}

.mo447j6oa {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.356 23.008v6.945H10.7a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.523a25 25 0 0 1-.371-.925l-.285-.724c-.322-.816-.953-1.219-1.437-1.422z");
}

.mr6mdpt1g {
  stop-color: var(--svg-color--716170, #716170);
}

.msti5wbjw {
  stop-color: var(--svg-color--8c7786, #8C7786);
}

.muvudkmkj {
  stop-color: var(--svg-color--56c0ff, #56C0FF);
  stop-opacity: 0;
}

.mwbu5sbnw {
  stop-color: var(--svg-color--4a4476, #4A4476);
}

.mzz_2wq-t {
  stop-color: var(--svg-color--c2bfc5, #C2BFC5);
}

.n_3yhnb8a {
  stop-color: var(--svg-color--958e9b, #958E9B);
  stop-opacity: 0;
}

.n_ty1xo5o {
  cx: 25.448px;
  cy: 9.299px;
  r: 0.559px;
}

.n4-no9-8p {
  stop-color: var(--svg-color--ca7d27, #CA7D27);
}

.n7jws8bws {
  stop-color: var(--svg-color--4b4386, #4B4386);
  stop-opacity: 0;
}

.n7r2-292q {
  stop-color: var(--svg-color--958e9b, #958E9B);
}

.nc9r4es_c {
  d: path("m25.161 10.243l.488-1.367l1.663 1.17c-.182.277-.795 1.022-1.025 1.104c-.318.113-.785.19-1.035-.118c-.2-.246-.15-.65-.091-.789");
}

.njdjvcttb {
  stop-color: var(--svg-color--ae9ea8, #AE9EA8);
}

.nkzm4gb5h {
  stop-color: var(--svg-color--a297ad, #A297AD);
}

.nmynr_cvx {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
}

.no6b1u88o {
  stop-color: var(--svg-color--f7c060, #F7C060);
}

.nr_9l6l2k {
  stop-color: var(--svg-color--3a9cf8, #3A9CF8);
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nwhi_fa4f {
  stop-color: var(--svg-color--413b69, #413B69);
}

.oak20zbgw {
  d: path("M19.286 2.008v9.588c0 .132.027.263.079.384l1.706 3.989l.42.136c.05.115.166.979.28.93a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V2.008z");
}

.oityxhb6t {
  d: path("m18.425 15.363l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091L9.67 17.6c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.ojugehbmx {
  d: path("M15.192 10.154a.28.28 0 1 1 .368-.421l1.754 1.506l-.368.42z");
}

.okfvj-bpf {
  stop-color: var(--svg-color--ffbd32, #FFBD32);
  stop-opacity: 0;
}

.os32btykc {
  stop-color: var(--svg-color--66619b, #66619B);
}

.ozlo8mb6b {
  stop-color: var(--svg-color--ffd443, #FFD443);
}

.p2417ob0x {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
  stop-opacity: 0;
}

.p3xx7436g {
  fill: var(--svg-color--ed9f3c, #ED9F3C);
  d: path("m19.195 20.953l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.p8p5c3bvm {
  stop-color: var(--svg-color--4788c0, #4788C0);
  stop-opacity: 0;
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pids_pbns {
  stop-color: var(--svg-color--948f8f, #948F8F);
}

.ps4wek9uf {
  stop-color: var(--svg-color--4a4476, #4A4476);
  stop-opacity: 0;
}

.pwtzxgbrf {
  fill: var(--svg-color--ffc63b, #FFC63B);
  d: path("M20.484 6.883a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.qkaxllo7y {
  stop-color: var(--svg-color--eda33a, #EDA33A);
}

.ql-kjsbnq {
  stop-color: var(--svg-color--eaa630, #EAA630);
}

.r1kmajh1r {
  stop-color: var(--svg-color--3aadff, #3AADFF);
}

.r8uyz9bqp {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
}

.rbn6gq-_t {
  fill-rule: evenodd;
  d: path("M23.664 13.768c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.341c.33 2.085 1.175 4.09 4.47 5.868z");
}

.rdr27y14e {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
  stop-opacity: 0;
}

.reex3410h {
  stop-color: var(--svg-color--e2dfe2, #E2DFE2);
}

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.rwh4nem5s {
  cx: 23.764px;
  cy: 7.886px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.s741zy-bl {
  d: path("M13.94 1.964c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
}

.scgoxofxx {
  stop-color: var(--svg-color--ba9f92, #BA9F92);
}

.sf7z4ybcf {
  stop-color: var(--svg-color--d1cfd2, #D1CFD2);
  stop-opacity: 0;
}

.shmkg3ete {
  stop-color: var(--svg-color--7a7996, #7A7996);
}

.t-qeblb7d {
  stop-color: var(--svg-color--e2e0e4, #E2E0E4);
}

.t1a_1erft {
  d: path("M15.04 10.67a.28.28 0 1 1 .368-.421l1.5 1.31l-.368.42z");
}

.t20d06bem {
  stop-color: var(--svg-color--816878, #816878);
  stop-opacity: 0;
}

.t20fa7b7o {
  stop-color: var(--svg-color--9d94a6, #9D94A6);
}

.t2uzah3ri {
  stop-color: var(--svg-color--e2a539, #E2A539);
  stop-opacity: 0;
}

.tcd28tbzr {
  stop-color: var(--svg-color--d88020, #D88020);
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tslw4_1qu {
  stop-color: var(--svg-color--63608c, #63608C);
}

.tvjmrrbpc {
  stop-color: var(--svg-color--5e505b, #5E505B);
}

.tvxb7fbew {
  fill-rule: evenodd;
  d: path("M24.486 18.966a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
}

.tylpo8bot {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
  stop-opacity: 0;
}

.uih7j62uq {
  fill: var(--svg-color--ffbd32, #FFBD32);
  d: path("m18.425 15.363l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091L9.67 17.6c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.uubye-mwc {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
}

.uuc-lrj5h {
  stop-color: var(--svg-color--7a7996, #7A7996);
  stop-opacity: 0;
}

.uxjdqcbxn {
  fill: var(--svg-color--ffbe3a, #FFBE3A);
  d: path("M15.192 10.154a.28.28 0 1 1 .368-.421l1.754 1.506l-.368.42z");
}

.v5_ahxl8w {
  stop-color: var(--svg-color--554682, #554682);
}

.v61sblb7d {
  d: path("M9.591 16.947a.93.93 0 0 1 .458-.698L2.356 18.9v2.661c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.vgv_qabik {
  stop-color: var(--svg-color--56c0ff, #56C0FF);
}

.vp6yj4xxl {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
}

.vps27w8pe {
  stop-color: var(--svg-color--413b69, #413B69);
  stop-opacity: 0;
}

.vq765rbep {
  stop-color: var(--svg-color--ca7d27, #CA7D27);
  stop-opacity: 0;
}

.vz_jd7bpk {
  d: path("M22.452 8.242c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.w2qvy2bqh {
  stop-color: var(--svg-color--e58a1f, #E58A1F);
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wj6gnkm5z {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.672 8.246l.053-.07c.073-.12.081-.25.018-.288c-.062-.038-.173.028-.246.148l-.035.071z");
}

.wlyubdb4v {
  stop-color: var(--svg-color--d6d4d7, #D6D4D7);
}

.wqel62b_c {
  stop-color: var(--svg-color--67a3db, #67A3DB);
  stop-opacity: 0;
}

.ws0t5un5c {
  stop-color: var(--svg-color--816878, #816878);
}

.wy97-4axq {
  stop-color: var(--svg-color--8b826e, #8B826E);
}

.wzdctp9kn {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m21.093 16.383l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.x-rptobqt {
  d: path("m12.14 20.012l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.113c.381.2 1.143.894 1.492 1.214l.012-.008z");
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x23lmh86f {
  d: path("M10.22 2.008c.551 1.054 1.37 2.957 1.85 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V2.008z");
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xq-3t8b8y {
  stop-color: var(--svg-color--a69494, #A69494);
  stop-opacity: 0;
}

.xs_2ilnpm {
  stop-color: var(--svg-color--4788c0, #4788C0);
}

.xv3ew_rhj {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M22.677 9.148a.1.1 0 0 1 .139-.028c.085.055.25.102.52.04a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.xzhs54baa {
  stop-color: var(--svg-color--948f8f, #948F8F);
  stop-opacity: 0;
}

.ybhyf2epg {
  fill-rule: evenodd;
  d: path("M25.714 8.448a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.yeh75achz {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.804 7.758c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.ykx68ubdn {
  stop-color: var(--svg-color--ce780d, #CE780D);
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zeblypklz {
  d: path("m22.624 12.906l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.102-1.766c-.316-.171-1.025-.28-1.398-.16s-.73.664-.883 1.09");
}

.zf7t0yb1u {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
}

.zp0x88wix {
  stop-color: var(--svg-color--aaa6ae, #AAA6AE);
  stop-opacity: 0;
}

.zqorby9td {
  d: path("M21.095 16.378c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014c-.906-.21-1.484-.406-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

</style>
