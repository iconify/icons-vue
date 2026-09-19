<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ifQ6gab)" class="r7kbphb4b"/><path fill="url(#iRp6xod)" class="r7kbphb4b"/><path fill="url(#ibWwPHc)" class="c25f_sbth"/><path fill="url(#iFlMVYb)" class="c25f_sbth"/><path fill="url(#iqoC68c)" class="c25f_sbth"/><path fill="url(#iccdl1b)" class="c25f_sbth"/><path fill="url(#iieHBqb)" class="c25f_sbth"/><g filter="url(#ixgbVlg)"><path class="krg9n8z9t"/></g><path fill="url(#ihisnxd)" class="dcz1c4ucy"/><path fill="url(#iizXltc)" class="dcz1c4ucy"/><path fill="url(#i1Wufhe)" class="dcz1c4ucy"/><g filter="url(#iH8kYhe)"><path fill="url(#iFFflFb)" class="pakm8bbxn"/></g><g filter="url(#ilLAYlb)"><path fill="url(#iaM8M2c)" clip-rule="evenodd" class="h9tibob5t"/></g><g filter="url(#i1FKIsd)"><path stroke="url(#ic6kJse)" class="ogmix5qhd"/></g><path fill="url(#iIrzLmd)" class="mq0vc5bgt"/><path fill="url(#i2qAked)" class="mq0vc5bgt"/><path fill="url(#iTDZL8b)" class="mq0vc5bgt"/><g filter="url(#i650MFe)"><path fill="url(#iy4tecc)" class="mmzxmtb4e"/></g><g filter="url(#ifmSiqp)"><path fill="url(#ip9h1Qb)" class="ylz3su2nd"/></g><path fill="url(#i4AGlWd)" class="y8oyb8_wv"/><path fill="url(#iAhXNnb)" class="nmgtefyoc"/><path fill="url(#i1wqMye)" class="nmgtefyoc"/><path fill="url(#i7NLoNc)" class="nmgtefyoc"/><path fill="url(#ioW9Hyd)" transform="rotate(7.73 23.58 11.001)" class="k0noc9bih"/><g filter="url(#i7Hbiqz)"><path fill="url(#ixrcw1d)" class="bl2o45l4z"/><path fill="url(#i75Y7Bc)" class="bl2o45l4z"/></g><path fill="url(#ieMLlKd)" clip-rule="evenodd" class="suf6l7a-t"/><path fill="url(#i8tMsyc)" clip-rule="evenodd" class="z30lfab3d"/><path fill="url(#irNoEvb)" clip-rule="evenodd" class="z30lfab3d"/><path clip-rule="evenodd" class="e8z-tzh2f"/><path class="hdzekacho"/><path class="gp4ch5blx"/><g filter="url(#ipH16EA)"><path class="neop56bxi"/><path fill="url(#iSUm9If)" class="ono3exbxo"/><path fill="url(#iEklsGc)" class="ono3exbxo"/></g><path class="narrz_b5q"/><path fill="url(#isRhI0E)" class="lnlc-vbsw"/><path fill="url(#iOsnscb)" class="lnlc-vbsw"/><path fill="url(#iKXvYCe)" class="lnlc-vbsw"/><path fill="url(#iaWee1c)" class="lnlc-vbsw"/><path fill="url(#iKzsDkb)" class="yjcpi3bip"/><path class="alt1adrwy"/><circle class="i8gfmnbdz"/><path fill="url(#iYcB3Fe)" class="epcmms0zy"/><path fill="url(#i70ZFUg)" class="epcmms0zy"/><path fill="url(#if1hgLe)" class="epcmms0zy"/><path fill="url(#iIq38Tb)" class="epcmms0zy"/><path fill="url(#iv8K54y)" class="epcmms0zy"/><path fill="url(#ib6vutu)" class="epcmms0zy"/><g filter="url(#imJeqkc)"><path class="ci79phxuv"/><path fill="url(#iDEKJJe)" class="lhjz7hb8n"/><path fill="url(#iqAw2gc)" class="lhjz7hb8n"/><path fill="url(#i4pqyyc)" class="lhjz7hb8n"/></g><g filter="url(#i0n3gze)"><path fill="url(#itrjTZd)" class="y0juufb3x"/></g><g filter="url(#inUIKCb)"><path class="m0b4z07jx"/><path fill="url(#iQBxzZb)" class="mnbrbkx5z"/></g><g filter="url(#iLiGDOb)"><path class="lijtiubny"/><path fill="url(#ibGRDJd)" class="p9zv0obed"/><path fill="url(#iX01yjb)" class="p9zv0obed"/><path fill="url(#i2xhoZt)" class="p9zv0obed"/></g><g filter="url(#ifXueSd)"><path class="bc3a8n-pc"/><path fill="url(#ibGRDJd)" class="p9zv0obed"/><path fill="url(#iX01yjb)" class="p9zv0obed"/><path fill="url(#i2xhoZt)" class="p9zv0obed"/></g><g filter="url(#i7Z5FPe)"><path class="w3qnt7kyr"/><path fill="url(#irtsJFf)" class="jwdwo-avn"/></g><path fill="url(#iYsLzde)" clip-rule="evenodd" class="ifm14ibym"/><path fill="url(#iKu7Fbd)" clip-rule="evenodd" class="ifm14ibym"/><path fill="url(#i1VNSFb)" clip-rule="evenodd" class="ifm14ibym"/><path class="rgumaubtj"/><path fill="url(#iSmRItb)" class="pscyhiiow"/><path fill="url(#iOm6twd)" class="pscyhiiow"/><path class="jierttbyl"/><path fill="url(#itfhQbb)" class="i15ar5ass"/><path class="jnobxqotv"/><path fill="url(#isIiBkd)" class="ap4u8r-er"/><path class="c2fud_lji"/><path fill="url(#iNGE9Mb)" class="gxwajlbrw"/><circle fill="url(#ixDVKkc)" class="rytzdrlsx"/><path clip-rule="evenodd" class="py47dn14e"/><path fill="url(#iciyK6b)" clip-rule="evenodd" class="tnnyn8beg"/><path fill="url(#iHGdkub)" clip-rule="evenodd" class="tnnyn8beg"/><path fill="url(#iptUguc)" clip-rule="evenodd" class="tnnyn8beg"/><g filter="url(#iuIJNqc)"><path fill="url(#i72ESLd)" class="rut3vfbcr"/></g><g filter="url(#i2Ru8Ab)"><path fill="url(#iIBh0HN)" class="hcd6u4bul"/></g><path class="gm9654a6l"/><path fill="url(#i4QbuBc)" class="tm8i4p2sy"/><g filter="url(#ikfu8Gr)"><path clip-rule="evenodd" class="ph37ggb-h"/></g><path fill="url(#i76fUTS)" class="h5-l_mbzw"/><path fill="url(#i1Cr7ee)" class="h5-l_mbzw"/><path fill="url(#i3Q9Aie)" class="h5-l_mbzw"/><path fill="url(#iNj1SFb)" class="ctres3b9w"/><path fill="url(#iHetjjb)" class="ctres3b9w"/><path fill="url(#iUtecEb)" class="ctres3b9w"/><path class="qglwsi2-w"/><path class="ym-wmdbaz"/><g filter="url(#iAIon6q)"><path class="jqb-r8buk"/></g><defs><radialGradient id="ifQ6gab" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.356 28.698)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="iqoC68c" cx="0" cy="0" r="1" gradientTransform="rotate(-83.29 17.231 5.367)scale(2.67447 5.21781)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="iccdl1b" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 3.057 10.72)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="iieHBqb" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.762 21.573)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="i1Wufhe" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.411 5.357)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="iaM8M2c" cx="0" cy="0" r="1" gradientTransform="rotate(66.687 4.472 19.02)scale(6.35158 4.4947)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="t9yd8jl3c"/><stop offset="1" class="kg0zi9bal"/></radialGradient><radialGradient id="i2qAked" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.205 8.736)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="iy4tecc" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 13.012 7.573)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="i4AGlWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10714 .67871 -.5326 -.08407 22.83 8.25)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="jg6j2gjjx"/><stop offset="1" class="b1fyieb0q"/></radialGradient><radialGradient id="i1wqMye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.403 21.776)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="i7NLoNc" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.325 19.296)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="ioW9Hyd" cx="0" cy="0" r="1" gradientTransform="matrix(.00508 -1.12418 .93572 .00423 24.888 12.069)" gradientUnits="userSpaceOnUse"><stop class="xri9f-s_b"/><stop offset="1" class="gpbachbzq"/></radialGradient><radialGradient id="ixrcw1d" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 23.012 8.87)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="ij41a3b_y"/><stop offset="1" class="zp1heiwjd"/></radialGradient><radialGradient id="i75Y7Bc" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.21 12.034)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="wuaq-3yri"/><stop offset="1" class="xt6ohhk1p"/></radialGradient><radialGradient id="irNoEvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 25.86 19.667)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="iEklsGc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23438 -.90624 .39526 -.97452 21.495 22.146)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="tir_n7ltq"/><stop offset="1" class="eio20ib8u"/></radialGradient><radialGradient id="isRhI0E" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.174 10.02)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="iOsnscb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.775 13.34)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="iaWee1c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 22.95 28.386)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="i70ZFUg" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 10.04 11.799)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="u005aj31u"/><stop offset="1" class="mg4rwjbbx"/></radialGradient><radialGradient id="if1hgLe" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.7 11.87)" gradientUnits="userSpaceOnUse"><stop class="mq4z99xlk"/><stop offset="1" class="l-wqt88hf"/></radialGradient><radialGradient id="iIq38Tb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92138 1.06381 -.61436 -1.10962 22.637 14.306)" gradientUnits="userSpaceOnUse"><stop class="ojet8cb1m"/><stop offset="1" class="sc-4z3bze"/></radialGradient><radialGradient id="iv8K54y" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.356 15.401)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="x3_nmbc0c"/><stop offset="1" class="zfzerzb4h"/></radialGradient><radialGradient id="ib6vutu" cx="0" cy="0" r="1" gradientTransform="matrix(-.57812 .45313 -.91434 -1.16656 25.42 12.573)" gradientUnits="userSpaceOnUse"><stop class="ycpxb2wjj"/><stop offset="1" class="yp3ph2bir"/></radialGradient><radialGradient id="iDEKJJe" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.544 21.917)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="iqAw2gc" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 20.09 19.792)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="i4pqyyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 21.965 19.714)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="itrjTZd" cx="0" cy="0" r="1" gradientTransform="rotate(174.089 13.28 6.12)scale(2.24975 3.24434)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="x_oix9_zz"/><stop offset="1" class="kkbgq1b-u"/></radialGradient><radialGradient id="ibGRDJd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.45 17.98)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="i2xhoZt" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.153 17.323)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="irtsJFf" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.387 19.48)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="i1VNSFb" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.81 16.276)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="iSmRItb" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.09375 .03207 .24052 19.83 6.88)" gradientUnits="userSpaceOnUse"><stop class="jmdfmwvec"/><stop offset="1" class="zf9ktoban"/></radialGradient><radialGradient id="iOm6twd" cx="0" cy="0" r="1" gradientTransform="matrix(.8086 -.23047 .16066 .56368 19.565 7.672)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="dhgcuzsfj"/><stop offset="1" class="acezg1zki"/></radialGradient><radialGradient id="ixDVKkc" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.382 18.84)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="joi_unb8q"/><stop offset="1" class="heqi_9hpg"/></radialGradient><radialGradient id="iptUguc" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.801 9.776)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="i72ESLd" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.593 9.99)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="iIBh0HN" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45313 1.162 .94162 25.512 8.48)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="i76fUTS" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.477 6.958)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="i1Cr7ee" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 -3.3125 9.2644 3.2338 19.59 19.73)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="nuwcoob-p"/><stop offset="1" class="gzdogx1hl"/></radialGradient><radialGradient id="i3Q9Aie" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -2.149 19.87)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="iNj1SFb" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.267 16.22)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="xcafsktgp"/><stop offset="1" class="x0t8b2bhw"/></radialGradient><radialGradient id="iUtecEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.97442 .66902 -.77403 -1.12736 24.407 12.854)" gradientUnits="userSpaceOnUse"><stop class="yjh8oi0bq"/><stop offset="1" class="cshe_hl2j"/></radialGradient><linearGradient id="iRp6xod" x1="11.287" x2="11.287" y1="30.245" y2="28.95" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="ibWwPHc" x1="5.169" x2="6.325" y1="17.823" y2="21.105" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="iFlMVYb" x1="5.669" x2="6.012" y1="17.823" y2="18.792" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="ihisnxd" x1="13.262" x2="11.419" y1="2.136" y2="15.261" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="iizXltc" x1="2.45" x2="12.981" y1="18.011" y2="13.854" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="iFFflFb" x1="14.118" x2="16.719" y1="10.962" y2="15.479" gradientUnits="userSpaceOnUse"><stop offset=".368" class="d6jlrzbaa"/><stop offset="1" class="w5vd7udwg"/></linearGradient><linearGradient id="ic6kJse" x1="19.33" x2="21.303" y1="7.991" y2="10.936" gradientUnits="userSpaceOnUse"><stop class="slosmsfdt"/><stop offset="1" class="c66243b1p"/></linearGradient><linearGradient id="iIrzLmd" x1="4.356" x2="6.731" y1="5.542" y2="13.823" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="iTDZL8b" x1="5.637" x2="5.356" y1="14.433" y2="13.433" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="ip9h1Qb" x1="19.425" x2="20.784" y1="11.244" y2="15.904" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="iAhXNnb" x1="24.95" x2="26.356" y1="20.589" y2="20.589" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="ieMLlKd" x1="24.724" x2="24.45" y1="18.851" y2="18.851" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="i8tMsyc" x1="26.34" x2="24.324" y1="20.129" y2="19.292" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="iSUm9If" x1="22.588" x2="21.188" y1="25.672" y2="26.266" gradientUnits="userSpaceOnUse"><stop class="f1spnwyxm"/><stop offset="1" class="e9dmvq9mi"/><stop offset="1" class="eplugbbfg"/></linearGradient><linearGradient id="iKXvYCe" x1="23.11" x2="23.005" y1="28.21" y2="28.128" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="iKzsDkb" x1="23.508" x2="23.755" y1="8.534" y2="8.097" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="iYcB3Fe" x1="24.731" x2="22.544" y1="16.104" y2="12.292" gradientUnits="userSpaceOnUse"><stop class="n_z8kdbjp"/><stop offset="1" class="pcd65pbuz"/></linearGradient><linearGradient id="iQBxzZb" x1="14.026" x2="14.651" y1="17.146" y2="18.145" gradientUnits="userSpaceOnUse"><stop class="lyhnd3axp"/><stop offset="1" class="prhc75bwt"/></linearGradient><linearGradient id="iX01yjb" x1="19.981" x2="20.95" y1="20.393" y2="17.417" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="iYsLzde" x1="22.952" x2="22.952" y1="16.98" y2="18.417" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="iKu7Fbd" x1="24.145" x2="24.376" y1="18.507" y2="18.062" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="itfhQbb" x1="15.466" x2="15.794" y1="12.003" y2="11.62" gradientUnits="userSpaceOnUse"><stop offset=".002" class="xw072qbqh"/><stop offset="1" class="oyjtz6bgf"/></linearGradient><linearGradient id="isIiBkd" x1="15.674" x2="16.069" y1="11.574" y2="11.113" gradientUnits="userSpaceOnUse"><stop offset=".002" class="xw072qbqh"/><stop offset="1" class="oyjtz6bgf"/></linearGradient><linearGradient id="iNGE9Mb" x1="15.94" x2="16.377" y1="11.178" y2="10.659" gradientUnits="userSpaceOnUse"><stop offset=".002" class="xw072qbqh"/><stop offset="1" class="oyjtz6bgf"/></linearGradient><linearGradient id="iciyK6b" x1="24.794" x2="24.473" y1="10.13" y2="9.886" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="iHGdkub" x1="23.34" x2="23.778" y1="10.683" y2="10.972" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="i4QbuBc" x1="16.358" x2="16.802" y1="10.95" y2="10.505" gradientUnits="userSpaceOnUse"><stop offset=".002" class="xw072qbqh"/><stop offset="1" class="oyjtz6bgf"/></linearGradient><linearGradient id="iHetjjb" x1="23.059" x2="22.934" y1="15.011" y2="14.089" gradientUnits="userSpaceOnUse"><stop class="b2cvh2xce"/><stop offset="1" class="s4ygnfbfl"/></linearGradient><filter id="ixgbVlg" width="8.743" height="7.346" x="1.805" y="23.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_856" result="effect2_innerShadow_4002_856"/></filter><filter id="iH8kYhe" width="4.276" height="5.599" x="13.194" y="9.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_856" stdDeviation=".375"/></filter><filter id="ilLAYlb" width="6.514" height="7.799" x="17.997" y="6.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.462745 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="i1FKIsd" width="2.679" height="4.12" x="18.865" y="7.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_856" stdDeviation=".15"/></filter><filter id="i650MFe" width="3.479" height="7.738" x="13.769" y="2.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="ifmSiqp" width="2.822" height="15.029" x="19.135" y="2.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="i7Hbiqz" width="4.68" height="4.407" x="21.841" y="7.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.211765 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.396078 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_856" result="effect2_innerShadow_4002_856"/></filter><filter id="ipH16EA" width="5.316" height="9.197" x="18.605" y="20.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.439216 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="imJeqkc" width="5.527" height="3.544" x="18.813" y="18.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="i0n3gze" width="2.864" height="4.018" x="24.407" y="8.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0666667 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="inUIKCb" width="9.577" height="5.489" x="9.494" y="15.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.278431 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="iLiGDOb" width="6.672" height="5.002" x="17.981" y="15.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="ifXueSd" width="6.922" height="5.002" x="17.981" y="15.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.364706 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="i7Z5FPe" width="2.568" height="3.646" x="9.471" y="17.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="iuIJNqc" width="4.913" height="4.647" x="23.235" y="5.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="i2Ru8Ab" width="1.588" height="1.361" x="24.897" y="7.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="ikfu8Gr" width="6.514" height="4.796" x="15.458" y="10.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.301961 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_856"/></filter><filter id="iAIon6q" width="3.862" height="3.738" x="15.977" y="10.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_856" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-climbing-medium-dark" /></template>
<style>
.acezg1zki {
  stop-color: var(--svg-color--6c3738, #6C3738);
  stop-opacity: 0;
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.alt1adrwy {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.521 8.538l.053-.07c.073-.12.081-.25.018-.288c-.062-.038-.173.028-.246.148l-.035.071z");
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.ap4u8r-er {
  d: path("M14.89 10.961a.28.28 0 0 1 .367-.42l1.5 1.31l-.368.42z");
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.b1fyieb0q {
  stop-color: var(--svg-color--704a44, #704A44);
}

.b2cvh2xce {
  stop-color: var(--svg-color--5a3e95, #5A3E95);
}

.bc3a8n-pc {
  fill: var(--svg-color--9f97a9, #9F97A9);
  d: path("m20.942 16.675l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.257-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biyiff5mh {
  stop-color: var(--svg-color--333061, #333061);
}

.bl2o45l4z {
  d: path("M22.16 9.722c.278-.875.951-1.815 1.212-2.188l2.898 1.867l-.593 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.boi6lnlog {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
}

.bpm5gvbdi {
  stop-color: var(--svg-color--e5e3e5, #E5E3E5);
}

.c25f_sbth {
  d: path("M9.44 17.239a.93.93 0 0 1 .457-.698l-7.692 2.651v2.661c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.c2fud_lji {
  fill: var(--svg-color--825c5a, #825C5A);
  d: path("M15.041 10.446a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.c66243b1p {
  stop-color: var(--svg-color--85635d, #85635D);
  stop-opacity: 0;
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.ci79phxuv {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.313 20.958l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.cshe_hl2j {
  stop-color: var(--svg-color--9e83ce, #9E83CE);
  stop-opacity: 0;
}

.ctres3b9w {
  d: path("m21.369 15.284l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
}

.d6jlrzbaa {
  stop-color: var(--svg-color--908790, #908790);
}

.dcz1c4ucy {
  d: path("M14.652 14.98L2.205 19.342V2.3H18.15c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.dfv3zlvmf {
  stop-color: var(--svg-color--648431, #648431);
}

.dhgcuzsfj {
  stop-color: var(--svg-color--6c3738, #6C3738);
}

.dnpfueb4s {
  stop-color: var(--svg-color--40347f, #40347F);
}

.e_59tbbed {
  stop-color: var(--svg-color--292557, #292557);
}

.e2k-esbpn {
  stop-color: var(--svg-color--c3c0c6, #C3C0C6);
  stop-opacity: 0;
}

.e8z-tzh2f {
  fill: var(--svg-color--86004d, #86004D);
  fill-rule: evenodd;
  d: path("M22.526 9.44a.1.1 0 0 1 .139-.028c.085.055.25.102.52.04a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.e9dmvq9mi {
  stop-color: var(--svg-color--635050, #635050);
  stop-opacity: 0;
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.eio20ib8u {
  stop-color: var(--svg-color--774a56, #774A56);
  stop-opacity: 0;
}

.eky141x3a {
  stop-color: var(--svg-color--489778, #489778);
}

.epcmms0zy {
  d: path("m22.473 13.198l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.102-1.766c-.316-.171-1.025-.28-1.398-.16s-.73.664-.883 1.09");
}

.eplugbbfg {
  stop-color: var(--svg-color--9a756e, #9A756E);
  stop-opacity: 0;
}

.f1spnwyxm {
  stop-color: var(--svg-color--9a756e, #9A756E);
}

.f2xkzabrk {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
  stop-opacity: 0;
}

.f2yuiwowd {
  stop-color: var(--svg-color--948b99, #948B99);
}

.fiw9fyalo {
  stop-color: var(--svg-color--4b4386, #4B4386);
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

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
}

.gm9654a6l {
  fill: var(--svg-color--825c5a, #825C5A);
  d: path("M15.614 10.215a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.gp4ch5blx {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.653 8.05c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.gpbachbzq {
  stop-color: var(--svg-color--69463e, #69463E);
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.gu1w6obkb {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
  stop-opacity: 0;
}

.gxwajlbrw {
  d: path("M15.041 10.446a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.gzdogx1hl {
  stop-color: var(--svg-color--7e7776, #7E7776);
}

.h5-l_mbzw {
  d: path("M20.944 16.67c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014c-.906-.21-1.484-.406-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

.h9tibob5t {
  fill-rule: evenodd;
  d: path("M23.513 14.06c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.341c.33 2.085 1.175 4.09 4.47 5.868z");
}

.hcd6u4bul {
  d: path("M24.96 7.688a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.367.48l-.984-.758a.3.3 0 0 1-.055-.423");
}

.hdzekacho {
  fill: var(--svg-color--1b131c, #1B131C);
  d: path("M24.234 8.631a.7.7 0 0 0-.223-.45c-.009.272-.167.4-.094.515c.096.15.33.117.317-.065");
}

.heqi_9hpg {
  stop-color: var(--svg-color--6d3647, #6D3647);
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.i15ar5ass {
  d: path("M14.814 11.494a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.i8gfmnbdz {
  cx: 23.613px;
  cy: 8.178px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.ifm14ibym {
  fill-rule: evenodd;
  d: path("M20.92 16.042a.25.25 0 0 1 .342-.092l3.629 2.09a.25.25 0 1 1-.25.434l-3.628-2.09a.25.25 0 0 1-.092-.342");
}

.ij41a3b_y {
  stop-color: var(--svg-color--75554d, #75554D);
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.j-c4i6bgu {
  stop-color: var(--svg-color--5e598c, #5E598C);
  stop-opacity: 0;
}

.jbbp6_bdq {
  stop-color: var(--svg-color--716170, #716170);
  stop-opacity: 0;
}

.jg6j2gjjx {
  stop-color: var(--svg-color--785c53, #785C53);
}

.jierttbyl {
  fill: var(--svg-color--825c5a, #825C5A);
  d: path("M14.814 11.494a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.jmdfmwvec {
  stop-color: var(--svg-color--91736a, #91736A);
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.jnobxqotv {
  fill: var(--svg-color--825c5a, #825C5A);
  d: path("M14.89 10.961a.28.28 0 0 1 .367-.42l1.5 1.31l-.368.42z");
}

.joi_unb8q {
  stop-color: var(--svg-color--714c53, #714C53);
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jqb-r8buk {
  stroke: var(--svg-color--916c65, #916C65);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.627 11.336l2.562 2.437");
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.jwdwo-avn {
  d: path("m11.989 20.304l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.095 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.k0noc9bih {
  d: path("M23.581 11.001h1.905v1.844h-1.905z");
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kao1--wwn {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
}

.kg0zi9bal {
  stop-color: var(--svg-color--5b2d2f, #5B2D2F);
}

.kkbgq1b-u {
  stop-color: var(--svg-color--1d0f22, #1D0F22);
}

.krg9n8z9t {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.205 23.3v6.945h8.343a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.524c-.065-.14-.186-.45-.371-.924l-.285-.724c-.322-.816-.953-1.219-1.437-1.422z");
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.l-wqt88hf {
  stop-color: var(--svg-color--6d4e68, #6D4E68);
  stop-opacity: 0;
}

.lhjz7hb8n {
  d: path("m19.313 20.958l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.lijtiubny {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m20.942 16.675l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.257-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.lnlc-vbsw {
  d: path("m22.889 26.45l.799.574a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.lyhnd3axp {
  stop-color: var(--svg-color--856660, #856660);
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.m0b4z07jx {
  fill: var(--svg-color--7c554d, #7C554D);
  d: path("m18.274 15.655l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.mg4rwjbbx {
  stop-color: var(--svg-color--8a6dc0, #8A6DC0);
  stop-opacity: 0;
}

.mmu9u7bsf {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
}

.mmzxmtb4e {
  d: path("M13.789 2.256c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
}

.mn787q_6r {
  stop-color: var(--svg-color--c7c5c9, #C7C5C9);
}

.mnbrbkx5z {
  d: path("m18.274 15.655l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.mq0vc5bgt {
  d: path("M10.07 2.3c.55 1.054 1.37 2.957 1.849 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V2.3z");
}

.mq4z99xlk {
  stop-color: var(--svg-color--6d4e68, #6D4E68);
}

.mr6mdpt1g {
  stop-color: var(--svg-color--716170, #716170);
}

.msti5wbjw {
  stop-color: var(--svg-color--8c7786, #8C7786);
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

.n_z8kdbjp {
  stop-color: var(--svg-color--8663c2, #8663C2);
}

.n7jws8bws {
  stop-color: var(--svg-color--4b4386, #4B4386);
  stop-opacity: 0;
}

.n7r2-292q {
  stop-color: var(--svg-color--958e9b, #958E9B);
}

.narrz_b5q {
  fill: var(--svg-color--544583, #544583);
  d: path("m22.889 26.45l.799.574a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.neop56bxi {
  fill: var(--svg-color--7b4b56, #7B4B56);
  d: path("m19.044 21.245l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.njdjvcttb {
  stop-color: var(--svg-color--ae9ea8, #AE9EA8);
}

.nkzm4gb5h {
  stop-color: var(--svg-color--a297ad, #A297AD);
}

.nmgtefyoc {
  d: path("m24.45 19.296l1.906.63v.73a.953.953 0 1 1-1.906 0z");
}

.nmynr_cvx {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nuwcoob-p {
  stop-color: var(--svg-color--a49ba8, #A49BA8);
  stop-opacity: 0;
}

.nwhi_fa4f {
  stop-color: var(--svg-color--413b69, #413B69);
}

.ogmix5qhd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.415 8.094c.07.492.482 1.784 1.58 3.02");
}

.ojet8cb1m {
  stop-color: var(--svg-color--4c3384, #4C3384);
}

.ono3exbxo {
  d: path("m19.044 21.245l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.os32btykc {
  stop-color: var(--svg-color--66619b, #66619B);
}

.oyjtz6bgf {
  stop-color: var(--svg-color--7d4f58, #7D4F58);
  stop-opacity: 0;
}

.p2417ob0x {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
  stop-opacity: 0;
}

.p9zv0obed {
  d: path("m20.942 16.675l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.257-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.pakm8bbxn {
  d: path("m16.719 12.555l-.06.425c-.113.802-.39 1.194-.87 1.488l-.857-1.286l-.946-1.329a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .292-.433l-.024-.033a.28.28 0 1 1 .455-.323l.106.146a.28.28 0 0 1 .5-.223l.5.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345a4 4 0 0 0-.06.6c.001.39.072.613.158.788");
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pcd65pbuz {
  stop-color: var(--svg-color--7753a0, #7753A0);
}

.ph37ggb-h {
  fill: var(--svg-color--825757, #825757);
  fill-rule: evenodd;
  d: path("m18.113 14.49l-2.655-2.436l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.423l.433 1.696l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.pids_pbns {
  stop-color: var(--svg-color--948f8f, #948F8F);
}

.prhc75bwt {
  stop-color: var(--svg-color--7c544c, #7C544C);
  stop-opacity: 0;
}

.ps4wek9uf {
  stop-color: var(--svg-color--4a4476, #4A4476);
  stop-opacity: 0;
}

.pscyhiiow {
  d: path("M20.333 7.175a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.py47dn14e {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.563 8.74a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.qglwsi2-w {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("m16.629 10.262l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.r7kbphb4b {
  d: path("M2.205 30.245v-8.953l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.113 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.557l5 4.752z");
}

.r8uyz9bqp {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
}

.rdr27y14e {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
  stop-opacity: 0;
}

.reex3410h {
  stop-color: var(--svg-color--e2dfe2, #E2DFE2);
}

.rgumaubtj {
  fill: var(--svg-color--7d5452, #7D5452);
  d: path("M20.333 7.175a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.rut3vfbcr {
  d: path("M26.96 10.306L23.33 7.61a.22.22 0 0 1-.067-.288a4.8 4.8 0 0 1 .654-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
}

.rytzdrlsx {
  cx: 25.297px;
  cy: 9.591px;
  r: 0.559px;
}

.s4ygnfbfl {
  stop-color: var(--svg-color--7850b4, #7850B4);
  stop-opacity: 0;
}

.sc-4z3bze {
  stop-color: var(--svg-color--634b8b, #634B8B);
  stop-opacity: 0;
}

.sf7z4ybcf {
  stop-color: var(--svg-color--d1cfd2, #D1CFD2);
  stop-opacity: 0;
}

.shmkg3ete {
  stop-color: var(--svg-color--7a7996, #7A7996);
}

.slosmsfdt {
  stop-color: var(--svg-color--85635d, #85635D);
}

.suf6l7a-t {
  fill-rule: evenodd;
  d: path("M24.524 18.21a.2.2 0 0 1 .2.2v.882a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
}

.t-qeblb7d {
  stop-color: var(--svg-color--e2e0e4, #E2E0E4);
}

.t20d06bem {
  stop-color: var(--svg-color--816878, #816878);
  stop-opacity: 0;
}

.t20fa7b7o {
  stop-color: var(--svg-color--9d94a6, #9D94A6);
}

.t9yd8jl3c {
  stop-color: var(--svg-color--784f4b, #784F4B);
}

.tir_n7ltq {
  stop-color: var(--svg-color--774a56, #774A56);
}

.tm8i4p2sy {
  d: path("M15.614 10.215a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tnnyn8beg {
  fill-rule: evenodd;
  d: path("M25.563 8.74a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.tslw4_1qu {
  stop-color: var(--svg-color--63608c, #63608C);
}

.tvjmrrbpc {
  stop-color: var(--svg-color--5e505b, #5E505B);
}

.tylpo8bot {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
  stop-opacity: 0;
}

.u005aj31u {
  stop-color: var(--svg-color--9480c2, #9480C2);
}

.uubye-mwc {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
}

.uuc-lrj5h {
  stop-color: var(--svg-color--7a7996, #7A7996);
  stop-opacity: 0;
}

.v5_ahxl8w {
  stop-color: var(--svg-color--554682, #554682);
}

.vp6yj4xxl {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
}

.vps27w8pe {
  stop-color: var(--svg-color--413b69, #413B69);
  stop-opacity: 0;
}

.w3qnt7kyr {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m11.989 20.304l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.095 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.w5vd7udwg {
  stop-color: var(--svg-color--908790, #908790);
  stop-opacity: 0;
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wlyubdb4v {
  stop-color: var(--svg-color--d6d4d7, #D6D4D7);
}

.ws0t5un5c {
  stop-color: var(--svg-color--816878, #816878);
}

.wuaq-3yri {
  stop-color: var(--svg-color--5a3342, #5A3342);
}

.x_oix9_zz {
  stop-color: var(--svg-color--2b2427, #2B2427);
}

.x0t8b2bhw {
  stop-color: var(--svg-color--7b53b7, #7B53B7);
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x3_nmbc0c {
  stop-color: var(--svg-color--877d9d, #877D9D);
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xcafsktgp {
  stop-color: var(--svg-color--8e6bb9, #8E6BB9);
}

.xri9f-s_b {
  stop-color: var(--svg-color--7c574a, #7C574A);
}

.xt6ohhk1p {
  stop-color: var(--svg-color--69484b, #69484B);
  stop-opacity: 0;
}

.xw072qbqh {
  stop-color: var(--svg-color--7d4f58, #7D4F58);
}

.xzhs54baa {
  stop-color: var(--svg-color--948f8f, #948F8F);
  stop-opacity: 0;
}

.y0juufb3x {
  d: path("m24.496 10.845l.445-1.156l.508-.758l1.672 1.32c-.052.087-.136.373-.055.829c.102.57-.14.969-.273 1.156c-.133.188-.813.883-1.758.258c-.756-.5-.675-1.307-.54-1.649");
}

.y8oyb8_wv {
  d: path("M22.301 8.534c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.ycpxb2wjj {
  stop-color: var(--svg-color--412949, #412949);
}

.yjcpi3bip {
  d: path("m23.679 8.642l.026-.04c.132-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
}

.yjh8oi0bq {
  stop-color: var(--svg-color--9e83ce, #9E83CE);
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.ylz3su2nd {
  d: path("M19.135 2.3v9.588c0 .132.027.263.079.384l1.706 3.989l.42.137c.05.114.166.978.28.929a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V2.3z");
}

.ym-wmdbaz {
  fill: var(--svg-color--815657, #815657);
  d: path("m16.629 10.262l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.yp3ph2bir {
  stop-color: var(--svg-color--765890, #765890);
  stop-opacity: 0;
}

.z30lfab3d {
  fill-rule: evenodd;
  d: path("M24.335 19.258a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zf7t0yb1u {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
}

.zf9ktoban {
  stop-color: var(--svg-color--88695b, #88695B);
  stop-opacity: 0;
}

.zfzerzb4h {
  stop-color: var(--svg-color--877d9d, #877D9D);
  stop-opacity: 0;
}

.zp0x88wix {
  stop-color: var(--svg-color--aaa6ae, #AAA6AE);
  stop-opacity: 0;
}

.zp1heiwjd {
  stop-color: var(--svg-color--73474c, #73474C);
}

</style>
