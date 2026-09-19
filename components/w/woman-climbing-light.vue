<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iA8lr2b)" class="u8i7gybfj"/><path fill="url(#iizuprx)" class="u8i7gybfj"/><path fill="url(#i8GFWHb)" class="mjys6ib5d"/><path fill="url(#iURq9Id)" class="mjys6ib5d"/><path fill="url(#isxWJyc)" class="mjys6ib5d"/><path fill="url(#iLeldOq)" class="mjys6ib5d"/><path fill="url(#icV0TYb)" class="mjys6ib5d"/><g filter="url(#i6YJNMc)"><path class="xg77vyb2k"/></g><path fill="url(#i9Ek1ti)" class="pl-jvubpl"/><path fill="url(#iIpYA3d)" class="pl-jvubpl"/><path fill="url(#ih2CFvb)" class="pl-jvubpl"/><g filter="url(#iThAnrc)"><path fill="url(#iYbRPkd)" class="hqf6gbb1c"/></g><g filter="url(#ieukoye)"><path fill="url(#ibQMjYb)" clip-rule="evenodd" class="b3zivtcmv"/></g><g filter="url(#iy4YHuC)"><path stroke="url(#itFXwgc)" class="yqhi4tbir"/></g><path fill="url(#iSfC9Wb)" class="e0ks_9bia"/><path fill="url(#iPvJ0Ee)" class="e0ks_9bia"/><path fill="url(#iLJr7Kc)" class="e0ks_9bia"/><g filter="url(#iiSZonA)"><path fill="url(#iI5RK7b)" class="v-_-ueu4j"/></g><g filter="url(#i3QRT6c)"><path fill="url(#iZDp7hb)" class="spjvjpz5c"/></g><path fill="url(#izRtf4D)" class="mfsyvjbhi"/><path fill="url(#iMqzFec)" class="hy6uac56w"/><path fill="url(#icBJ7Me)" class="hy6uac56w"/><path fill="url(#is9vdCu)" class="hy6uac56w"/><path fill="url(#ilNEJUb)" transform="rotate(7.73 23.58 10.44)" class="jq4f7kb6s"/><g filter="url(#igwLqiA)"><path fill="url(#ii0B36b)" class="n2e9n7b0j"/><path fill="url(#ibiXFLc)" class="n2e9n7b0j"/></g><path fill="url(#inoJQNe)" clip-rule="evenodd" class="mjdrz4bgr"/><path fill="url(#iqK7svb)" clip-rule="evenodd" class="ps52acb0d"/><path fill="url(#iX84qNd)" clip-rule="evenodd" class="ps52acb0d"/><path clip-rule="evenodd" class="mdq_5nstu"/><path class="af8wlvbyi"/><path class="od6yh_b9n"/><g filter="url(#iJhKrxd)"><path class="p1n5b3bnd"/><path fill="url(#iAhg1Wd)" class="gssyix_5u"/><path fill="url(#iaYMwQb)" class="gssyix_5u"/></g><path class="cn7sexksj"/><path fill="url(#iY7eOCc)" class="plhy87b9n"/><path fill="url(#iENT0Nd)" class="plhy87b9n"/><path fill="url(#iENkpuc)" class="plhy87b9n"/><path fill="url(#iUg2TKP)" class="plhy87b9n"/><path fill="url(#ia06Che)" class="b269pl2wo"/><path class="rf6ryxbuv"/><g filter="url(#ijO6Pzc)"><path fill="url(#i6fBpjc)" class="a7x5jzbxh"/></g><circle class="sjn3-sirc"/><path fill="url(#ioHq0hb)" class="acff5jbet"/><path fill="url(#iHu9tHd)" class="acff5jbet"/><path fill="url(#iSupeJb)" class="acff5jbet"/><path fill="url(#iNzRbye)" class="acff5jbet"/><path fill="url(#iL6Effd)" class="acff5jbet"/><path fill="url(#i3rXy2b)" class="acff5jbet"/><g filter="url(#imHx1Xd)"><path class="i8tv2acaz"/><path fill="url(#i3AIwqb)" class="qv89y8z6c"/><path fill="url(#iqi1vub)" class="qv89y8z6c"/><path fill="url(#ih5KgNc)" class="qv89y8z6c"/></g><g filter="url(#iv57LEe)"><path class="ati1yu2bn"/><path fill="url(#inXXM1h)" class="w_pvwit4g"/></g><g filter="url(#isZNOQc)"><path class="qx_tabu_r"/><path fill="url(#i24vmKc)" class="ot159kbtf"/><path fill="url(#i2Cnitc)" class="ot159kbtf"/><path fill="url(#iHVFTxc)" class="ot159kbtf"/></g><g filter="url(#iSBQsuc)"><path class="l-t30tb4t"/><path fill="url(#i24vmKc)" class="ot159kbtf"/><path fill="url(#i2Cnitc)" class="ot159kbtf"/><path fill="url(#iHVFTxc)" class="ot159kbtf"/></g><g filter="url(#irxLOeb)"><path class="ryv_t0bce"/><path fill="url(#iQ6fKvd)" class="ahi_o-dnn"/></g><path fill="url(#iwZwTvc)" clip-rule="evenodd" class="h908q10jg"/><path fill="url(#iDsUhmc)" clip-rule="evenodd" class="h908q10jg"/><path fill="url(#ihDnpOb)" clip-rule="evenodd" class="h908q10jg"/><path class="ftvq1r83m"/><path fill="url(#iLMmo9L)" class="tssb1i4-p"/><path fill="url(#iS29Wpd)" class="tssb1i4-p"/><path class="dxloeybev"/><path fill="url(#iOJnu9b)" class="jmehbxb_u"/><path class="bm650xbtp"/><path fill="url(#iYF8ABd)" class="f5zbgrb8w"/><path class="ylacwac1s"/><path fill="url(#itApIJc)" class="l7jv9hbpg"/><circle fill="url(#iL0dcEc)" class="t-t-nsbdu"/><path clip-rule="evenodd" class="hfunh6h0q"/><path fill="url(#iPman2P)" clip-rule="evenodd" class="x5vhiv_yo"/><path fill="url(#iAWXpxc)" clip-rule="evenodd" class="x5vhiv_yo"/><path fill="url(#iC45JBx)" clip-rule="evenodd" class="x5vhiv_yo"/><g filter="url(#iColrbd)"><path fill="url(#i1o6ood)" class="na4iq12cx"/></g><g filter="url(#iK0XpHe)"><path fill="url(#iSAP1BS)" class="oskm_qx7q"/></g><path class="hgj-7sbqc"/><path fill="url(#ifrE9ZN)" class="p9xgsjbvt"/><g filter="url(#i0IfIZT)"><path clip-rule="evenodd" class="aplsg90bk"/></g><path fill="url(#iJOtzEd)" class="ix9uk0b3q"/><path fill="url(#i6aiFbb)" class="ix9uk0b3q"/><path fill="url(#im6290d)" class="ix9uk0b3q"/><path fill="url(#iRNVYhb)" class="ub96xch2f"/><path fill="url(#iFpoZhe)" class="ub96xch2f"/><path fill="url(#iMzucmb)" class="ub96xch2f"/><path class="y7ruvdr-s"/><path class="sfp346ylz"/><g filter="url(#ieWIm6c)"><path class="bcro-nfnp"/></g><defs><radialGradient id="iA8lr2b" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.356 28.136)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="isxWJyc" cx="0" cy="0" r="1" gradientTransform="rotate(-83.29 16.915 5.086)scale(2.67447 5.21781)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="iLeldOq" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 3.118 10.438)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="icV0TYb" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.762 21.011)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="ih2CFvb" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.424 5.076)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="ibQMjYb" cx="0" cy="0" r="1" gradientTransform="rotate(66.687 4.899 18.738)scale(6.35158 4.4947)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="idf7iis4m"/><stop offset="1" class="i483pbbvh"/></radialGradient><radialGradient id="iPvJ0Ee" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.205 8.174)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="iI5RK7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 13.012 7.011)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="izRtf4D" cx="0" cy="0" r="1" gradientTransform="matrix(-.10714 .67871 -.5326 -.08407 22.83 7.688)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="jxqufcbzg"/><stop offset="1" class="cuptu7i6i"/></radialGradient><radialGradient id="icBJ7Me" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.403 21.214)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="is9vdCu" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.325 18.734)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="ilNEJUb" cx="0" cy="0" r="1" gradientTransform="matrix(.00508 -1.12418 .93572 .00423 24.889 11.507)" gradientUnits="userSpaceOnUse"><stop class="uxdjasbcp"/><stop offset="1" class="mqiy0z14h"/></radialGradient><radialGradient id="ii0B36b" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 23.013 8.308)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="tnn6d9lnt"/><stop offset="1" class="w0i7s3bkp"/></radialGradient><radialGradient id="ibiXFLc" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.375 11.753)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="ur7lpnbek"/><stop offset="1" class="ja_424b_z"/></radialGradient><radialGradient id="iX84qNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 25.86 19.105)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="iaYMwQb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23438 -.90624 .39526 -.97452 21.495 21.584)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="s7tjmje9c"/><stop offset="1" class="jq6elebrt"/></radialGradient><radialGradient id="iY7eOCc" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.084 9.738)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="iENT0Nd" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.753 13.06)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="iUg2TKP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 22.95 27.824)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="i6fBpjc" cx="0" cy="0" r="1" gradientTransform="rotate(174.089 13.295 5.84)scale(2.24975 3.24434)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="x_oix9_zz"/><stop offset="1" class="kkbgq1b-u"/></radialGradient><radialGradient id="iHu9tHd" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 10.152 11.518)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="u005aj31u"/><stop offset="1" class="mg4rwjbbx"/></radialGradient><radialGradient id="iSupeJb" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.7 11.308)" gradientUnits="userSpaceOnUse"><stop class="mq4z99xlk"/><stop offset="1" class="l-wqt88hf"/></radialGradient><radialGradient id="iNzRbye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92138 1.06381 -.61436 -1.10962 22.637 13.744)" gradientUnits="userSpaceOnUse"><stop class="ojet8cb1m"/><stop offset="1" class="sc-4z3bze"/></radialGradient><radialGradient id="iL6Effd" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.356 14.84)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="x3_nmbc0c"/><stop offset="1" class="zfzerzb4h"/></radialGradient><radialGradient id="i3rXy2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.57812 .45313 -.91434 -1.16656 25.422 12.01)" gradientUnits="userSpaceOnUse"><stop class="ycpxb2wjj"/><stop offset="1" class="yp3ph2bir"/></radialGradient><radialGradient id="i3AIwqb" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.544 21.355)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="iqi1vub" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 20.09 19.23)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="ih5KgNc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 21.965 19.152)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="i24vmKc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.45 17.418)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="iHVFTxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.153 16.761)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="iQ6fKvd" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.387 18.918)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="ihDnpOb" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.81 15.714)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="iLMmo9L" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.09375 .03207 .24052 19.83 6.318)" gradientUnits="userSpaceOnUse"><stop class="vhvhb3zhp"/><stop offset="1" class="lgscsz-mk"/></radialGradient><radialGradient id="iS29Wpd" cx="0" cy="0" r="1" gradientTransform="matrix(.8086 -.23047 .16066 .56368 19.565 7.11)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="c6_l-7bxo"/><stop offset="1" class="p5js8vl2d"/></radialGradient><radialGradient id="iL0dcEc" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.696 18.56)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="dhib36bjr"/><stop offset="1" class="uucs6l1bh"/></radialGradient><radialGradient id="iC45JBx" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.801 9.214)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="i1o6ood" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.725 9.708)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="iSAP1BS" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45313 1.162 .94162 25.512 7.917)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="iJOtzEd" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.427 6.677)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="i6aiFbb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15626 -3.3125 9.2644 3.23382 19.59 19.167)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="nuwcoob-p"/><stop offset="1" class="gzdogx1hl"/></radialGradient><radialGradient id="im6290d" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -1.807 19.59)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="iRNVYhb" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.508 15.94)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="xcafsktgp"/><stop offset="1" class="x0t8b2bhw"/></radialGradient><radialGradient id="iMzucmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.97442 .66902 -.77403 -1.12736 24.407 12.292)" gradientUnits="userSpaceOnUse"><stop class="yjh8oi0bq"/><stop offset="1" class="cshe_hl2j"/></radialGradient><linearGradient id="iizuprx" x1="11.287" x2="11.287" y1="29.683" y2="28.388" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="i8GFWHb" x1="5.169" x2="6.325" y1="17.261" y2="20.543" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="iURq9Id" x1="5.669" x2="6.012" y1="17.261" y2="18.23" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="i9Ek1ti" x1="13.262" x2="11.419" y1="1.574" y2="14.699" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="iIpYA3d" x1="2.45" x2="12.981" y1="17.449" y2="13.293" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="iYbRPkd" x1="14.118" x2="16.719" y1="10.4" y2="14.918" gradientUnits="userSpaceOnUse"><stop offset=".368" class="d6jlrzbaa"/><stop offset="1" class="w5vd7udwg"/></linearGradient><linearGradient id="itFXwgc" x1="19.33" x2="21.303" y1="7.429" y2="10.374" gradientUnits="userSpaceOnUse"><stop class="p9znm86eq"/><stop offset="1" class="wik1ebe6f"/></linearGradient><linearGradient id="iSfC9Wb" x1="4.356" x2="6.731" y1="4.98" y2="13.261" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="iLJr7Kc" x1="5.637" x2="5.356" y1="13.871" y2="12.871" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="iZDp7hb" x1="19.425" x2="20.784" y1="10.682" y2="15.342" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="iMqzFec" x1="24.95" x2="26.356" y1="20.027" y2="20.027" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="inoJQNe" x1="24.724" x2="24.45" y1="18.289" y2="18.289" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="iqK7svb" x1="26.34" x2="24.324" y1="19.567" y2="18.73" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="iAhg1Wd" x1="22.588" x2="21.188" y1="25.11" y2="25.745" gradientUnits="userSpaceOnUse"><stop class="cnnf9s-0l"/><stop offset="1" class="bvpo-tbla"/></linearGradient><linearGradient id="iENkpuc" x1="23.11" x2="23.005" y1="27.648" y2="27.566" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="ia06Che" x1="23.508" x2="23.755" y1="7.972" y2="7.535" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="ioHq0hb" x1="24.731" x2="22.544" y1="15.542" y2="11.73" gradientUnits="userSpaceOnUse"><stop class="n_z8kdbjp"/><stop offset="1" class="pcd65pbuz"/></linearGradient><linearGradient id="inXXM1h" x1="14.026" x2="14.651" y1="16.584" y2="17.583" gradientUnits="userSpaceOnUse"><stop class="b8uuy5liy"/><stop offset="1" class="yk2k1_b7i"/></linearGradient><linearGradient id="i2Cnitc" x1="19.981" x2="20.95" y1="19.831" y2="16.855" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="iwZwTvc" x1="22.952" x2="22.952" y1="16.418" y2="17.855" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="iDsUhmc" x1="24.145" x2="24.376" y1="17.945" y2="17.5" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="iOJnu9b" x1="15.466" x2="15.605" y1="11.441" y2="11.273" gradientUnits="userSpaceOnUse"><stop offset=".002" class="sz_3d1b0d"/><stop offset="1" class="g_7w59bka"/></linearGradient><linearGradient id="iYF8ABd" x1="15.674" x2="15.842" y1="11.012" y2="10.81" gradientUnits="userSpaceOnUse"><stop offset=".002" class="sz_3d1b0d"/><stop offset="1" class="g_7w59bka"/></linearGradient><linearGradient id="itApIJc" x1="15.94" x2="16.126" y1="10.616" y2="10.389" gradientUnits="userSpaceOnUse"><stop offset=".002" class="sz_3d1b0d"/><stop offset="1" class="g_7w59bka"/></linearGradient><linearGradient id="iPman2P" x1="24.794" x2="24.473" y1="9.568" y2="9.324" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="iAWXpxc" x1="23.34" x2="23.778" y1="10.121" y2="10.41" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="ifrE9ZN" x1="16.358" x2="16.548" y1="10.388" y2="10.192" gradientUnits="userSpaceOnUse"><stop offset=".002" class="sz_3d1b0d"/><stop offset="1" class="g_7w59bka"/></linearGradient><linearGradient id="iFpoZhe" x1="23.059" x2="22.934" y1="14.449" y2="13.527" gradientUnits="userSpaceOnUse"><stop class="b2cvh2xce"/><stop offset="1" class="s4ygnfbfl"/></linearGradient><filter id="i6YJNMc" width="8.743" height="7.346" x="1.805" y="22.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_865" result="effect2_innerShadow_4002_865"/></filter><filter id="iThAnrc" width="4.276" height="5.599" x="13.194" y="9.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_865" stdDeviation=".375"/></filter><filter id="ieukoye" width="6.514" height="7.799" x="17.997" y="5.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.784314 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="iy4YHuC" width="2.679" height="4.12" x="18.865" y="6.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_865" stdDeviation=".15"/></filter><filter id="iiSZonA" width="3.479" height="7.738" x="13.769" y="1.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="i3QRT6c" width="2.822" height="15.029" x="19.135" y="1.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="igwLqiA" width="4.68" height="4.407" x="21.841" y="6.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.486275 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.745098 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_865" result="effect2_innerShadow_4002_865"/></filter><filter id="iJhKrxd" width="5.316" height="9.197" x="18.605" y="20.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.784314 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="ijO6Pzc" width="2.864" height="4.018" x="24.407" y="8.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0666667 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="imHx1Xd" width="5.527" height="3.544" x="18.813" y="18.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="iv57LEe" width="9.577" height="5.489" x="9.494" y="14.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.505882 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="isZNOQc" width="6.672" height="5.002" x="17.981" y="14.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="iSBQsuc" width="6.922" height="5.002" x="17.981" y="14.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.364706 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="irxLOeb" width="2.568" height="3.646" x="9.471" y="16.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="iColrbd" width="4.913" height="4.647" x="23.235" y="5.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="iK0XpHe" width="1.588" height="1.361" x="24.897" y="7.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="i0IfIZT" width="6.514" height="4.796" x="15.458" y="9.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.619608 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_865"/></filter><filter id="ieWIm6c" width="3.862" height="3.738" x="15.977" y="10.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_865" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-climbing-light" /></template>
<style>
.a7x5jzbxh {
  d: path("m24.496 10.283l.445-1.156l.508-.758l1.672 1.32c-.052.087-.136.373-.055.829c.102.57-.14.968-.273 1.156s-.813.883-1.758.258c-.756-.5-.675-1.308-.54-1.649");
}

.acff5jbet {
  d: path("m22.473 12.636l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.102-1.765c-.316-.172-1.025-.28-1.398-.16s-.73.663-.883 1.09");
}

.af8wlvbyi {
  fill: var(--svg-color--1b131c, #1B131C);
  d: path("M24.234 8.07a.7.7 0 0 0-.223-.451c-.009.272-.167.4-.094.515c.096.15.33.117.317-.065");
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.ahi_o-dnn {
  d: path("m11.989 19.742l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.aplsg90bk {
  fill: var(--svg-color--f2bba9, #F2BBA9);
  fill-rule: evenodd;
  d: path("m18.113 13.927l-2.655-2.435l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.423l.433 1.696l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.ati1yu2bn {
  fill: var(--svg-color--e9b4a4, #E9B4A4);
  d: path("m18.274 15.093l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01L11.12 20.18a.2.2 0 0 1-.27-.091L9.52 17.33c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.b269pl2wo {
  d: path("m23.679 8.08l.026-.04c.132-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
}

.b2cvh2xce {
  stop-color: var(--svg-color--5a3e95, #5A3E95);
}

.b3zivtcmv {
  fill-rule: evenodd;
  d: path("M23.513 13.498c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.34c.33 2.086 1.175 4.092 4.47 5.87z");
}

.b8uuy5liy {
  stop-color: var(--svg-color--eebba3, #EEBBA3);
}

.bcro-nfnp {
  stroke: var(--svg-color--ffceb7, #FFCEB7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.627 10.774l2.562 2.437");
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biyiff5mh {
  stop-color: var(--svg-color--333061, #333061);
}

.bm650xbtp {
  fill: var(--svg-color--f6bca8, #F6BCA8);
  d: path("M14.89 10.4a.28.28 0 1 1 .367-.421l1.5 1.31l-.368.42z");
}

.boi6lnlog {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
}

.bpm5gvbdi {
  stop-color: var(--svg-color--e5e3e5, #E5E3E5);
}

.bvpo-tbla {
  stop-color: var(--svg-color--ffd4bd, #FFD4BD);
  stop-opacity: 0;
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.c6_l-7bxo {
  stop-color: var(--svg-color--d8937c, #D8937C);
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.cn7sexksj {
  fill: var(--svg-color--544583, #544583);
  d: path("m22.889 25.887l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.cnnf9s-0l {
  stop-color: var(--svg-color--ffd4bd, #FFD4BD);
}

.cshe_hl2j {
  stop-color: var(--svg-color--9e83ce, #9E83CE);
  stop-opacity: 0;
}

.cuptu7i6i {
  stop-color: var(--svg-color--e8ac93, #E8AC93);
}

.d6jlrzbaa {
  stop-color: var(--svg-color--908790, #908790);
}

.dfv3zlvmf {
  stop-color: var(--svg-color--648431, #648431);
}

.dhib36bjr {
  stop-color: var(--svg-color--cf9f9d, #CF9F9D);
}

.dnpfueb4s {
  stop-color: var(--svg-color--40347f, #40347F);
}

.dxloeybev {
  fill: var(--svg-color--f6bca8, #F6BCA8);
  d: path("M14.814 10.932a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.e_59tbbed {
  stop-color: var(--svg-color--292557, #292557);
}

.e0ks_9bia {
  d: path("M10.07 1.738c.55 1.054 1.37 2.957 1.849 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V1.738z");
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

.f2xkzabrk {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
  stop-opacity: 0;
}

.f2yuiwowd {
  stop-color: var(--svg-color--948b99, #948B99);
}

.f5zbgrb8w {
  d: path("M14.89 10.4a.28.28 0 1 1 .367-.421l1.5 1.31l-.368.42z");
}

.fiw9fyalo {
  stop-color: var(--svg-color--4b4386, #4B4386);
}

.ft5dv1b6b {
  fill: none;
}

.ftvq1r83m {
  fill: var(--svg-color--f2c2a9, #F2C2A9);
  d: path("M20.333 6.613a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.fwnzc4ctw {
  stop-color: var(--svg-color--5a332d, #5A332D);
}

.fy9sosv6u {
  stop-color: var(--svg-color--417c62, #417C62);
  stop-opacity: 0;
}

.g_7w59bka {
  stop-color: var(--svg-color--ecae9b, #ECAE9B);
  stop-opacity: 0;
}

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.gssyix_5u {
  d: path("m19.044 20.683l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.gu1w6obkb {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
  stop-opacity: 0;
}

.gzdogx1hl {
  stop-color: var(--svg-color--7e7776, #7E7776);
}

.h908q10jg {
  fill-rule: evenodd;
  d: path("M20.92 15.48a.25.25 0 0 1 .342-.092l3.629 2.09a.25.25 0 1 1-.25.433l-3.628-2.09a.25.25 0 0 1-.092-.34");
}

.hfunh6h0q {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.563 8.178a.25.25 0 0 1 .032.352l-1.992 2.395a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.hgj-7sbqc {
  fill: var(--svg-color--f6bca8, #F6BCA8);
  d: path("M15.614 9.653a.28.28 0 0 1 .367-.42l1.41 1.419l-.226.512z");
}

.hqf6gbb1c {
  d: path("m16.719 11.993l-.06.425c-.113.802-.39 1.194-.87 1.488l-.857-1.286l-.946-1.329a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .292-.433l-.024-.033a.28.28 0 1 1 .455-.323l.106.147a.28.28 0 0 1 .5-.224l.5.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345c-.031.201-.061.44-.06.6c.001.39.072.613.158.788");
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.hy6uac56w {
  d: path("m24.45 18.734l1.906.63v.73a.953.953 0 1 1-1.906 0z");
}

.i483pbbvh {
  stop-color: var(--svg-color--cb7e70, #CB7E70);
}

.i8tv2acaz {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.313 20.396l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.idf7iis4m {
  stop-color: var(--svg-color--e8ad9b, #E8AD9B);
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.ix9uk0b3q {
  d: path("M20.944 16.108c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014a18 18 0 0 1-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

.j-c4i6bgu {
  stop-color: var(--svg-color--5e598c, #5E598C);
  stop-opacity: 0;
}

.ja_424b_z {
  stop-color: var(--svg-color--b27d80, #B27D80);
  stop-opacity: 0;
}

.jbbp6_bdq {
  stop-color: var(--svg-color--716170, #716170);
  stop-opacity: 0;
}

.jmehbxb_u {
  d: path("M14.814 10.932a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jq4f7kb6s {
  d: path("M23.581 10.439h1.905v1.844h-1.905z");
}

.jq6elebrt {
  stop-color: var(--svg-color--cf9297, #CF9297);
  stop-opacity: 0;
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.jxqufcbzg {
  stop-color: var(--svg-color--dfaf96, #DFAF96);
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kao1--wwn {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
}

.kkbgq1b-u {
  stop-color: var(--svg-color--1d0f22, #1D0F22);
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.l-t30tb4t {
  fill: var(--svg-color--9f97a9, #9F97A9);
  d: path("m20.942 16.113l.195-.438l3.516 2.024c-.034.106-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.l-wqt88hf {
  stop-color: var(--svg-color--6d4e68, #6D4E68);
  stop-opacity: 0;
}

.l7jv9hbpg {
  d: path("M15.041 9.883a.28.28 0 0 1 .368-.42l1.754 1.506l-.368.42z");
}

.lgscsz-mk {
  stop-color: var(--svg-color--fbcdb7, #FBCDB7);
  stop-opacity: 0;
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.mdq_5nstu {
  fill: var(--svg-color--86004d, #86004D);
  fill-rule: evenodd;
  d: path("M22.526 8.878a.1.1 0 0 1 .139-.028c.085.055.25.102.52.04a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.mfsyvjbhi {
  d: path("M22.301 7.972c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.mg4rwjbbx {
  stop-color: var(--svg-color--8a6dc0, #8A6DC0);
  stop-opacity: 0;
}

.mjdrz4bgr {
  fill-rule: evenodd;
  d: path("M24.524 17.647c.11 0 .2.09.2.2v.883a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
}

.mjys6ib5d {
  d: path("M9.44 16.677a.93.93 0 0 1 .457-.698L2.205 18.63v2.661c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.mmu9u7bsf {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
}

.mn787q_6r {
  stop-color: var(--svg-color--c7c5c9, #C7C5C9);
}

.mq4z99xlk {
  stop-color: var(--svg-color--6d4e68, #6D4E68);
}

.mqiy0z14h {
  stop-color: var(--svg-color--e19384, #E19384);
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

.n2e9n7b0j {
  d: path("M22.16 9.16c.278-.875.951-1.815 1.212-2.188L26.27 8.84l-.593 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.n7jws8bws {
  stop-color: var(--svg-color--4b4386, #4B4386);
  stop-opacity: 0;
}

.n7r2-292q {
  stop-color: var(--svg-color--958e9b, #958E9B);
}

.na4iq12cx {
  d: path("m26.96 9.744l-3.63-2.696a.22.22 0 0 1-.067-.288a4.8 4.8 0 0 1 .654-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
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

.od6yh_b9n {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.653 7.488c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.ojet8cb1m {
  stop-color: var(--svg-color--4c3384, #4C3384);
}

.os32btykc {
  stop-color: var(--svg-color--66619b, #66619B);
}

.oskm_qx7q {
  d: path("M24.96 7.126a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.368.479l-.984-.758a.3.3 0 0 1-.055-.423");
}

.ot159kbtf {
  d: path("m20.942 16.113l.195-.438l3.516 2.024c-.034.106-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.p1n5b3bnd {
  fill: var(--svg-color--dda49e, #DDA49E);
  d: path("m19.044 20.683l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.p2417ob0x {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
  stop-opacity: 0;
}

.p5js8vl2d {
  stop-color: var(--svg-color--d8937c, #D8937C);
  stop-opacity: 0;
}

.p9xgsjbvt {
  d: path("M15.614 9.653a.28.28 0 0 1 .367-.42l1.41 1.419l-.226.512z");
}

.p9znm86eq {
  stop-color: var(--svg-color--f4bda7, #F4BDA7);
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pcd65pbuz {
  stop-color: var(--svg-color--7753a0, #7753A0);
}

.pids_pbns {
  stop-color: var(--svg-color--948f8f, #948F8F);
}

.pl-jvubpl {
  d: path("M14.652 14.418L2.205 18.78V1.738H18.15c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.plhy87b9n {
  d: path("m22.889 25.887l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.ps4wek9uf {
  stop-color: var(--svg-color--4a4476, #4A4476);
  stop-opacity: 0;
}

.ps52acb0d {
  fill-rule: evenodd;
  d: path("M24.335 18.696a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.qv89y8z6c {
  d: path("m19.313 20.396l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.qx_tabu_r {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m20.942 16.113l.195-.438l3.516 2.024c-.034.106-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
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

.rf6ryxbuv {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.521 7.976l.053-.07c.073-.12.081-.25.018-.288c-.062-.038-.173.028-.246.148l-.035.071z");
}

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.ryv_t0bce {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m11.989 19.742l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.s4ygnfbfl {
  stop-color: var(--svg-color--7850b4, #7850B4);
  stop-opacity: 0;
}

.s7tjmje9c {
  stop-color: var(--svg-color--cf9297, #CF9297);
}

.sc-4z3bze {
  stop-color: var(--svg-color--634b8b, #634B8B);
  stop-opacity: 0;
}

.sf7z4ybcf {
  stop-color: var(--svg-color--d1cfd2, #D1CFD2);
  stop-opacity: 0;
}

.sfp346ylz {
  fill: var(--svg-color--f2bba9, #F2BBA9);
  d: path("m16.629 9.7l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.shmkg3ete {
  stop-color: var(--svg-color--7a7996, #7A7996);
}

.sjn3-sirc {
  cx: 23.613px;
  cy: 7.616px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.spjvjpz5c {
  d: path("M19.135 1.738v9.588c0 .132.027.263.079.384l1.706 3.989l.42.136c.05.115.166.979.28.93a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V1.738z");
}

.sz_3d1b0d {
  stop-color: var(--svg-color--ecae9b, #ECAE9B);
}

.t-qeblb7d {
  stop-color: var(--svg-color--e2e0e4, #E2E0E4);
}

.t-t-nsbdu {
  cx: 25.297px;
  cy: 9.029px;
  r: 0.559px;
}

.t20d06bem {
  stop-color: var(--svg-color--816878, #816878);
  stop-opacity: 0;
}

.t20fa7b7o {
  stop-color: var(--svg-color--9d94a6, #9D94A6);
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tnn6d9lnt {
  stop-color: var(--svg-color--ddac9a, #DDAC9A);
}

.tslw4_1qu {
  stop-color: var(--svg-color--63608c, #63608C);
}

.tssb1i4-p {
  d: path("M20.333 6.613a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
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

.u8i7gybfj {
  d: path("M2.205 29.683V20.73l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.113 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.556l5 4.753z");
}

.ub96xch2f {
  d: path("m21.369 14.722l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
}

.ur7lpnbek {
  stop-color: var(--svg-color--b27d80, #B27D80);
}

.uubye-mwc {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
}

.uuc-lrj5h {
  stop-color: var(--svg-color--7a7996, #7A7996);
  stop-opacity: 0;
}

.uucs6l1bh {
  stop-color: var(--svg-color--c58284, #C58284);
}

.uxdjasbcp {
  stop-color: var(--svg-color--f0ad9f, #F0AD9F);
}

.v-_-ueu4j {
  d: path("M13.789 1.694c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
}

.v5_ahxl8w {
  stop-color: var(--svg-color--554682, #554682);
}

.vhvhb3zhp {
  stop-color: var(--svg-color--fbcdb7, #FBCDB7);
}

.vp6yj4xxl {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
}

.vps27w8pe {
  stop-color: var(--svg-color--413b69, #413B69);
  stop-opacity: 0;
}

.w_pvwit4g {
  d: path("m18.274 15.093l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01L11.12 20.18a.2.2 0 0 1-.27-.091L9.52 17.33c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.w0i7s3bkp {
  stop-color: var(--svg-color--d79f9b, #D79F9B);
}

.w5vd7udwg {
  stop-color: var(--svg-color--908790, #908790);
  stop-opacity: 0;
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wik1ebe6f {
  stop-color: var(--svg-color--f4bda7, #F4BDA7);
  stop-opacity: 0;
}

.wlyubdb4v {
  stop-color: var(--svg-color--d6d4d7, #D6D4D7);
}

.ws0t5un5c {
  stop-color: var(--svg-color--816878, #816878);
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

.x5vhiv_yo {
  fill-rule: evenodd;
  d: path("M25.563 8.178a.25.25 0 0 1 .032.352l-1.992 2.395a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xcafsktgp {
  stop-color: var(--svg-color--8e6bb9, #8E6BB9);
}

.xg77vyb2k {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.205 22.738v6.945h8.343a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.524c-.065-.14-.186-.45-.371-.924l-.285-.724c-.322-.816-.953-1.219-1.437-1.422z");
}

.xzhs54baa {
  stop-color: var(--svg-color--948f8f, #948F8F);
  stop-opacity: 0;
}

.y7ruvdr-s {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("m16.629 9.7l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.ycpxb2wjj {
  stop-color: var(--svg-color--412949, #412949);
}

.yjh8oi0bq {
  stop-color: var(--svg-color--9e83ce, #9E83CE);
}

.yk2k1_b7i {
  stop-color: var(--svg-color--eebba3, #EEBBA3);
  stop-opacity: 0;
}

.ylacwac1s {
  fill: var(--svg-color--f6bca8, #F6BCA8);
  d: path("M15.041 9.883a.28.28 0 0 1 .368-.42l1.754 1.506l-.368.42z");
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.yp3ph2bir {
  stop-color: var(--svg-color--765890, #765890);
  stop-opacity: 0;
}

.yqhi4tbir {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.415 7.532c.07.492.482 1.784 1.58 3.02");
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zf7t0yb1u {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
}

.zfzerzb4h {
  stop-color: var(--svg-color--877d9d, #877D9D);
  stop-opacity: 0;
}

.zp0x88wix {
  stop-color: var(--svg-color--aaa6ae, #AAA6AE);
  stop-opacity: 0;
}

</style>
