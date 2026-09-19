<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixZMyPl)" class="s_296qbql"/><path fill="url(#iCcUMZb)" class="s_296qbql"/><path fill="url(#iHUuxSB)" class="yxg-bcbqu"/><path fill="url(#iYoEi2c)" class="yxg-bcbqu"/><path fill="url(#isCHdqw)" class="yxg-bcbqu"/><path fill="url(#iCTEXWc)" class="yxg-bcbqu"/><path fill="url(#iYf2PDD)" class="yxg-bcbqu"/><g filter="url(#icc0IFc)"><path class="c53r7cb7u"/></g><path fill="url(#iyN7OKF)" class="c3ui19bbs"/><path fill="url(#inmEKQc)" class="c3ui19bbs"/><path fill="url(#iXuIbBe)" class="c3ui19bbs"/><g filter="url(#iC6Fmqd)"><path fill="url(#iwZaV6A)" class="x67sj11nn"/></g><g filter="url(#iSdUbne)"><path fill="url(#iQh089d)" clip-rule="evenodd" class="o-axgkb8f"/></g><g filter="url(#i0VZyuc)"><path stroke="url(#iMhTpab)" class="wcf5rh81b"/></g><path fill="url(#imwX48c)" class="k_1mn1btr"/><path fill="url(#iz6tmoc)" class="k_1mn1btr"/><path fill="url(#iBh4AqT)" class="k_1mn1btr"/><g filter="url(#iW1zGld)"><path fill="url(#iUx7Ylb)" class="zn_k87xtn"/></g><g filter="url(#iLqDInb)"><path fill="url(#i9gtpmc)" class="e7d5bbckx"/></g><path fill="url(#i9KIqhe)" class="mi15_86qf"/><path fill="url(#iGxvjJd)" class="y9puldbfz"/><path fill="url(#i3XKHEj)" class="y9puldbfz"/><path fill="url(#iJuWXOc)" class="y9puldbfz"/><path fill="url(#iKc4k6d)" transform="rotate(7.73 23.43 10.44)" class="rfv__7srr"/><g filter="url(#iC6A54b)"><path fill="url(#iHkksCe)" class="py2j-eb8k"/><path fill="url(#iGY90rb)" class="py2j-eb8k"/></g><path fill="url(#iJG7bOe)" clip-rule="evenodd" class="idnhod_ns"/><path fill="url(#iQKbK4d)" clip-rule="evenodd" class="xthpsjb0p"/><path fill="url(#ivgk6we)" clip-rule="evenodd" class="xthpsjb0p"/><path clip-rule="evenodd" class="gox8fu80e"/><g filter="url(#igvNrLc)"><path class="evu_i_b3j"/><path fill="url(#i46ruyd)" class="xtb_t7q6w"/></g><path class="qi9--6bbx"/><g filter="url(#ixmsrrc)"><path class="t4lrhnb4n"/><path fill="url(#ilUkKKW)" class="t4y9t702f"/><path fill="url(#is93Dzd)" class="t4y9t702f"/></g><path class="kcln8hz7k"/><path fill="url(#iJpW8Bc)" class="s84dqqbgl"/><path fill="url(#iobAatc)" class="s84dqqbgl"/><path fill="url(#iYwOryd)" class="s84dqqbgl"/><path fill="url(#iPykmVq)" class="s84dqqbgl"/><path fill="url(#i9jdbEb)" class="w-vr8zi9m"/><path class="md-4--lgv"/><circle class="oes15pbkf"/><path fill="url(#iiVAYab)" class="db52ou1og"/><path fill="url(#iUEyW3I)" class="db52ou1og"/><path fill="url(#i2OHkKd)" class="db52ou1og"/><path fill="url(#iuQdT5d)" class="db52ou1og"/><path fill="url(#iZrA7qb)" class="db52ou1og"/><g filter="url(#iSmGuGd)"><path class="x_-8kbbtt"/><path fill="url(#i1rSjtc)" class="l260hfbmf"/><path fill="url(#iJQLmuc)" class="l260hfbmf"/><path fill="url(#iqyaECc)" class="l260hfbmf"/></g><g filter="url(#ijbJgqb)"><path class="n-izhdceg"/><path fill="url(#iHJjtyd)" class="a31jws0qg"/></g><g filter="url(#ipKBe3t)"><path class="u3q9i3u8m"/><path fill="url(#iEYY6ic)" class="vrt4g-pnz"/><path fill="url(#iR3upvi)" class="vrt4g-pnz"/><path fill="url(#iAWJwQc)" class="vrt4g-pnz"/></g><g filter="url(#iahcQmb)"><path class="cnvn3r8bp"/><path fill="url(#iEYY6ic)" class="vrt4g-pnz"/><path fill="url(#iR3upvi)" class="vrt4g-pnz"/><path fill="url(#iAWJwQc)" class="vrt4g-pnz"/></g><g filter="url(#iZYWwrc)"><path class="jc0_0ksoa"/><path fill="url(#iONgGPb)" class="vfizx5bjt"/></g><path fill="url(#iSiTckc)" clip-rule="evenodd" class="ip8omlxzv"/><path fill="url(#iUydJWd)" clip-rule="evenodd" class="ip8omlxzv"/><path fill="url(#iG7PWJx)" clip-rule="evenodd" class="ip8omlxzv"/><path class="b9yi6-bzj"/><path fill="url(#i1C9v5K)" class="tpihfdcpn"/><path fill="url(#iTtRuPd)" class="tpihfdcpn"/><path class="tcaotyooh"/><path fill="url(#i6eGOId)" class="fzkq57bzl"/><path class="yht1-dbom"/><path fill="url(#iwIPz3c)" class="b__xtt01t"/><path class="falxks22x"/><path fill="url(#i4pzY2c)" class="kt69p55if"/><circle fill="url(#iAPgfkZ)" class="zrznt0bqi"/><path clip-rule="evenodd" class="vyu2vwqby"/><path fill="url(#iaa5JYc)" clip-rule="evenodd" class="aauiffbjw"/><path fill="url(#ivCn5wd)" clip-rule="evenodd" class="aauiffbjw"/><path fill="url(#iVkfBvb)" clip-rule="evenodd" class="aauiffbjw"/><g filter="url(#itYFlPb)"><path fill="url(#iYhXnqK)" class="k5x4o5bkr"/></g><g filter="url(#ixt35Ja)"><path fill="url(#i2JYTfX)" class="t0o3kkckx"/></g><path class="yyd0qux2f"/><path fill="url(#iezclad)" class="a5ywlb6bf"/><g filter="url(#i1rNvCx)"><path clip-rule="evenodd" class="gkb_96b9j"/></g><path fill="url(#iIm5fid)" class="gvhh4_b0f"/><path fill="url(#iXu3VpT)" class="gvhh4_b0f"/><path fill="url(#iU8qjid)" class="gvhh4_b0f"/><path fill="url(#i4UvsVc)" class="un4ucfbvi"/><path fill="url(#ikDkixc)" class="un4ucfbvi"/><path fill="url(#iveENAd)" class="un4ucfbvi"/><path class="srxj-kbhv"/><path class="ya9kcr2sb"/><g filter="url(#ijjiOob)"><path class="ac_y7t1ap"/></g><defs><radialGradient id="ixZMyPl" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.205 28.136)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="isCHdqw" cx="0" cy="0" r="1" gradientTransform="rotate(-83.29 16.84 5.171)scale(2.67447 5.21781)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="iCTEXWc" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 3.042 10.422)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="iYf2PDD" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.611 21.011)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="iXuIbBe" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.348 5.073)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="iQh089d" cx="0" cy="0" r="1" gradientTransform="rotate(66.687 4.823 18.624)scale(6.35158 4.4947)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="idf7iis4m"/><stop offset="1" class="i483pbbvh"/></radialGradient><radialGradient id="iz6tmoc" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.054 8.174)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="iUx7Ylb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 12.861 7.011)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="i9KIqhe" cx="0" cy="0" r="1" gradientTransform="matrix(-.10714 .67871 -.5326 -.08407 22.68 7.688)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="jxqufcbzg"/><stop offset="1" class="cuptu7i6i"/></radialGradient><radialGradient id="i3XKHEj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.252 21.214)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="iJuWXOc" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.174 18.734)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="iKc4k6d" cx="0" cy="0" r="1" gradientTransform="matrix(.00508 -1.12418 .93572 .00423 24.738 11.508)" gradientUnits="userSpaceOnUse"><stop class="uxdjasbcp"/><stop offset="1" class="mqiy0z14h"/></radialGradient><radialGradient id="iHkksCe" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 22.862 8.308)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="tnn6d9lnt"/><stop offset="1" class="w0i7s3bkp"/></radialGradient><radialGradient id="iGY90rb" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.3 11.709)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="ur7lpnbek"/><stop offset="1" class="ja_424b_z"/></radialGradient><radialGradient id="ivgk6we" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 25.709 19.105)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="i46ruyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7533 -.625 .19855 -.2393 25.82 10.396)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jsa0_reur"/><stop offset="1" class="l-nb061ot"/></radialGradient><radialGradient id="is93Dzd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23438 -.90624 .39526 -.97452 21.344 21.584)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="s7tjmje9c"/><stop offset="1" class="jq6elebrt"/></radialGradient><radialGradient id="iJpW8Bc" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.009 9.762)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="iobAatc" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.678 13.065)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="iPykmVq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 22.799 27.824)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="iUEyW3I" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 10.077 11.488)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="qksuzsbug"/><stop offset="1" class="se__e0blq"/></radialGradient><radialGradient id="i2OHkKd" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.549 11.308)" gradientUnits="userSpaceOnUse"><stop class="jfz0xgwum"/><stop offset="1" class="k2u_13bdd"/></radialGradient><radialGradient id="iuQdT5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06251 1.12498 -.6497 -1.19113 22.627 13.683)" gradientUnits="userSpaceOnUse"><stop class="n_geicc-w"/><stop offset="1" class="bn_1vkbwm"/></radialGradient><radialGradient id="iZrA7qb" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.205 14.84)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="nvv1klhll"/><stop offset="1" class="ilft87v6y"/></radialGradient><radialGradient id="i1rSjtc" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.393 21.355)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="iJQLmuc" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 19.94 19.23)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="iqyaECc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 21.814 19.152)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="iEYY6ic" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.299 17.418)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="iAWJwQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.002 16.761)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="iONgGPb" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.237 18.918)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="iG7PWJx" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.658 15.714)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="i1C9v5K" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.09375 .03207 .24052 19.68 6.318)" gradientUnits="userSpaceOnUse"><stop class="vhvhb3zhp"/><stop offset="1" class="lgscsz-mk"/></radialGradient><radialGradient id="iTtRuPd" cx="0" cy="0" r="1" gradientTransform="matrix(.8086 -.23047 .16066 .56368 19.414 7.11)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="c6_l-7bxo"/><stop offset="1" class="p5js8vl2d"/></radialGradient><radialGradient id="iAPgfkZ" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.62 18.475)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="dhib36bjr"/><stop offset="1" class="uucs6l1bh"/></radialGradient><radialGradient id="iVkfBvb" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.65 9.214)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="iYhXnqK" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.65 9.673)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="i2JYTfX" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45313 1.162 .94162 25.361 7.917)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="iIm5fid" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.352 6.69)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="iXu3VpT" cx="0" cy="0" r="1" gradientTransform="matrix(1.15626 -3.3125 9.2644 3.23382 19.44 19.168)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="nuwcoob-p"/><stop offset="1" class="gzdogx1hl"/></radialGradient><radialGradient id="iU8qjid" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -1.883 19.497)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="i4UvsVc" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.432 15.875)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="o6w7f1w7w"/><stop offset="1" class="v5m-xebtg"/></radialGradient><radialGradient id="iveENAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.92187 .21875 -.25309 -1.06657 24.393 12.636)" gradientUnits="userSpaceOnUse"><stop class="xapik5b0z"/><stop offset="1" class="npx64-mvq"/></radialGradient><linearGradient id="iCcUMZb" x1="11.136" x2="11.136" y1="29.683" y2="28.388" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="iHUuxSB" x1="5.018" x2="6.174" y1="17.261" y2="20.543" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="iYoEi2c" x1="5.518" x2="5.861" y1="17.261" y2="18.23" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="iyN7OKF" x1="13.111" x2="11.268" y1="1.574" y2="14.699" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="inmEKQc" x1="2.299" x2="12.83" y1="17.449" y2="13.293" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="iwZaV6A" x1="13.967" x2="16.568" y1="10.4" y2="14.918" gradientUnits="userSpaceOnUse"><stop offset=".368" class="d6jlrzbaa"/><stop offset="1" class="w5vd7udwg"/></linearGradient><linearGradient id="iMhTpab" x1="19.141" x2="21.359" y1="7.407" y2="11.344" gradientUnits="userSpaceOnUse"><stop class="p9znm86eq"/><stop offset="1" class="wik1ebe6f"/></linearGradient><linearGradient id="imwX48c" x1="4.205" x2="6.58" y1="4.98" y2="13.261" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="iBh4AqT" x1="5.486" x2="5.205" y1="13.871" y2="12.871" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="i9gtpmc" x1="19.274" x2="20.633" y1="10.682" y2="15.342" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="iGxvjJd" x1="24.799" x2="26.205" y1="20.027" y2="20.027" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="iJG7bOe" x1="24.573" x2="24.299" y1="18.289" y2="18.289" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="iQKbK4d" x1="26.189" x2="24.173" y1="19.567" y2="18.73" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="ilUkKKW" x1="22.438" x2="21.037" y1="25.11" y2="25.745" gradientUnits="userSpaceOnUse"><stop class="cnnf9s-0l"/><stop offset="1" class="bvpo-tbla"/></linearGradient><linearGradient id="iYwOryd" x1="22.959" x2="22.854" y1="27.648" y2="27.566" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="i9jdbEb" x1="23.357" x2="23.604" y1="7.972" y2="7.535" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="iiVAYab" x1="24.58" x2="22.393" y1="15.542" y2="11.73" gradientUnits="userSpaceOnUse"><stop class="af5ecjb0e"/><stop offset="1" class="bg5vqlb1m"/></linearGradient><linearGradient id="iHJjtyd" x1="13.875" x2="14.5" y1="16.584" y2="17.583" gradientUnits="userSpaceOnUse"><stop class="b8uuy5liy"/><stop offset="1" class="yk2k1_b7i"/></linearGradient><linearGradient id="iR3upvi" x1="19.83" x2="20.799" y1="19.831" y2="16.855" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="iSiTckc" x1="22.801" x2="22.801" y1="16.418" y2="17.855" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="iUydJWd" x1="23.994" x2="24.225" y1="17.945" y2="17.5" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="i6eGOId" x1="15.315" x2="15.59" y1="11.441" y2="11.117" gradientUnits="userSpaceOnUse"><stop offset=".002" class="sz_3d1b0d"/><stop offset="1" class="g_7w59bka"/></linearGradient><linearGradient id="iwIPz3c" x1="15.523" x2="15.691" y1="11.012" y2="10.81" gradientUnits="userSpaceOnUse"><stop offset=".002" class="sz_3d1b0d"/><stop offset="1" class="g_7w59bka"/></linearGradient><linearGradient id="i4pzY2c" x1="15.789" x2="15.975" y1="10.616" y2="10.389" gradientUnits="userSpaceOnUse"><stop offset=".002" class="sz_3d1b0d"/><stop offset="1" class="g_7w59bka"/></linearGradient><linearGradient id="iaa5JYc" x1="24.643" x2="24.322" y1="9.568" y2="9.324" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="ivCn5wd" x1="23.189" x2="23.627" y1="10.121" y2="10.41" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="iezclad" x1="16.207" x2="16.397" y1="10.388" y2="10.192" gradientUnits="userSpaceOnUse"><stop offset=".002" class="sz_3d1b0d"/><stop offset="1" class="g_7w59bka"/></linearGradient><linearGradient id="ikDkixc" x1="22.908" x2="22.783" y1="14.449" y2="13.527" gradientUnits="userSpaceOnUse"><stop class="wd5xhxb1x"/><stop offset="1" class="r_k29qxtj"/></linearGradient><filter id="icc0IFc" width="8.743" height="7.346" x="1.654" y="22.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_864" result="effect2_innerShadow_4002_864"/></filter><filter id="iC6Fmqd" width="4.276" height="5.599" x="13.043" y="9.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_864" stdDeviation=".375"/></filter><filter id="iSdUbne" width="6.514" height="7.799" x="17.846" y="5.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.784314 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="i0VZyuc" width="3.383" height="4.772" x="18.714" y="6.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_864" stdDeviation=".15"/></filter><filter id="iW1zGld" width="3.479" height="7.738" x="13.618" y="1.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="iLqDInb" width="2.822" height="15.029" x="18.984" y="1.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="iC6A54b" width="4.68" height="4.407" x="21.69" y="6.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.486275 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.745098 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_864" result="effect2_innerShadow_4002_864"/></filter><filter id="igvNrLc" width="2.054" height="2.454" x="25.067" y="8.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0156863 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="ixmsrrc" width="5.316" height="9.197" x="18.453" y="20.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.784314 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="iSmGuGd" width="5.527" height="3.544" x="18.662" y="18.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="ijbJgqb" width="9.577" height="5.489" x="9.343" y="14.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.505882 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="ipKBe3t" width="6.672" height="5.002" x="17.83" y="14.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="iahcQmb" width="6.922" height="5.002" x="17.83" y="14.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.364706 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="iZYWwrc" width="2.568" height="3.646" x="9.32" y="16.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="itYFlPb" width="4.913" height="4.647" x="23.084" y="5.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="ixt35Ja" width="1.588" height="1.361" x="24.746" y="7.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="i1rNvCx" width="6.514" height="4.796" x="15.307" y="9.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.619608 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_864"/></filter><filter id="ijjiOob" width="3.862" height="3.738" x="15.944" y="10.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_864" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-climbing-light" /></template>
<style>
.a31jws0qg {
  d: path("m18.123 15.093l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01L10.97 20.18a.2.2 0 0 1-.27-.091L9.37 17.33c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.a5ywlb6bf {
  d: path("M15.463 9.653a.28.28 0 0 1 .367-.42l1.41 1.419l-.226.512z");
}

.aauiffbjw {
  fill-rule: evenodd;
  d: path("M25.412 8.178a.25.25 0 0 1 .032.352l-1.992 2.395a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.ac_y7t1ap {
  stroke: var(--svg-color--ffceb7, #FFCEB7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.594 10.774l2.562 2.437");
}

.af5ecjb0e {
  stop-color: var(--svg-color--ff712f, #FF712F);
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.b__xtt01t {
  d: path("M14.738 10.4a.28.28 0 1 1 .367-.421l1.5 1.31l-.367.42z");
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.b8uuy5liy {
  stop-color: var(--svg-color--eebba3, #EEBBA3);
}

.b9yi6-bzj {
  fill: var(--svg-color--f2c2a9, #F2C2A9);
  d: path("M20.182 6.613a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.bg5vqlb1m {
  stop-color: var(--svg-color--ff2f0b, #FF2F0B);
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biyiff5mh {
  stop-color: var(--svg-color--333061, #333061);
}

.bn_1vkbwm {
  stop-color: var(--svg-color--f52715, #F52715);
  stop-opacity: 0;
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

.c3ui19bbs {
  d: path("M14.501 14.418L2.054 18.78V1.738h15.944c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.c53r7cb7u {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.054 22.738v6.945h8.343a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.524c-.065-.14-.186-.45-.371-.924l-.285-.724c-.322-.816-.953-1.219-1.437-1.422z");
}

.c6_l-7bxo {
  stop-color: var(--svg-color--d8937c, #D8937C);
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.cnnf9s-0l {
  stop-color: var(--svg-color--ffd4bd, #FFD4BD);
}

.cnvn3r8bp {
  fill: var(--svg-color--9f97a9, #9F97A9);
  d: path("m20.791 16.113l.195-.438l3.516 2.024c-.034.106-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.cuptu7i6i {
  stop-color: var(--svg-color--e8ac93, #E8AC93);
}

.d6jlrzbaa {
  stop-color: var(--svg-color--908790, #908790);
}

.db52ou1og {
  d: path("m22.322 12.636l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.101-1.765c-.317-.172-1.026-.28-1.399-.16s-.73.663-.883 1.09");
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

.e_59tbbed {
  stop-color: var(--svg-color--292557, #292557);
}

.e2k-esbpn {
  stop-color: var(--svg-color--c3c0c6, #C3C0C6);
  stop-opacity: 0;
}

.e7d5bbckx {
  d: path("M18.984 1.738v9.588c0 .132.027.263.079.384l1.706 3.989l.42.136c.05.115.166.979.28.93a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V1.738z");
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.eky141x3a {
  stop-color: var(--svg-color--489778, #489778);
}

.evu_i_b3j {
  fill: var(--svg-color--1b131d, #1B131D);
  d: path("m25.127 10.109l.488-1.367l1.356 1.015c-.2.301-.727.563-.938.625a.435.435 0 0 1-.074.657c-.14.09-.508.105-.758-.204c-.2-.246-.133-.587-.074-.726");
}

.f2xkzabrk {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
  stop-opacity: 0;
}

.f2yuiwowd {
  stop-color: var(--svg-color--948b99, #948B99);
}

.falxks22x {
  fill: var(--svg-color--f6bca8, #F6BCA8);
  d: path("M14.89 9.883a.28.28 0 0 1 .368-.42l1.754 1.506l-.368.42z");
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

.fzkq57bzl {
  d: path("M14.663 10.932a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.g_7w59bka {
  stop-color: var(--svg-color--ecae9b, #ECAE9B);
  stop-opacity: 0;
}

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
}

.gkb_96b9j {
  fill: var(--svg-color--f2bba9, #F2BBA9);
  fill-rule: evenodd;
  d: path("m17.962 13.927l-2.655-2.435l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.423l.433 1.696l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.gox8fu80e {
  fill: var(--svg-color--86014d, #86014D);
  fill-rule: evenodd;
  d: path("M22.375 8.878a.1.1 0 0 1 .139-.028c.085.055.25.102.52.04a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.gu1w6obkb {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
  stop-opacity: 0;
}

.gvhh4_b0f {
  d: path("M20.793 16.108c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014a18 18 0 0 1-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

.gzdogx1hl {
  stop-color: var(--svg-color--7e7776, #7E7776);
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.i483pbbvh {
  stop-color: var(--svg-color--cb7e70, #CB7E70);
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.idf7iis4m {
  stop-color: var(--svg-color--e8ad9b, #E8AD9B);
}

.idnhod_ns {
  fill-rule: evenodd;
  d: path("M24.373 17.647c.11 0 .2.09.2.2v.883a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.ilft87v6y {
  stop-color: var(--svg-color--f8736b, #F8736B);
  stop-opacity: 0;
}

.ip8omlxzv {
  fill-rule: evenodd;
  d: path("M20.77 15.48a.25.25 0 0 1 .341-.092l3.629 2.09a.25.25 0 1 1-.25.433l-3.628-2.09a.25.25 0 0 1-.092-.34");
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

.jc0_0ksoa {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m11.838 19.742l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.jfz0xgwum {
  stop-color: var(--svg-color--e2452b, #E2452B);
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jq6elebrt {
  stop-color: var(--svg-color--cf9297, #CF9297);
  stop-opacity: 0;
}

.jsa0_reur {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.jxqufcbzg {
  stop-color: var(--svg-color--dfaf96, #DFAF96);
}

.k_1mn1btr {
  d: path("M9.918 1.738c.551 1.054 1.37 2.957 1.85 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V1.738z");
}

.k2u_13bdd {
  stop-color: var(--svg-color--e2452b, #E2452B);
  stop-opacity: 0;
}

.k5x4o5bkr {
  d: path("M26.808 9.744L23.18 7.048a.22.22 0 0 1-.069-.288a4.8 4.8 0 0 1 .655-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kao1--wwn {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
}

.kcln8hz7k {
  fill: var(--svg-color--544583, #544583);
  d: path("m22.738 25.887l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.kt69p55if {
  d: path("M14.89 9.883a.28.28 0 0 1 .368-.42l1.754 1.506l-.368.42z");
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.l-nb061ot {
  stop-color: var(--svg-color--1d191c, #1D191C);
  stop-opacity: 0;
}

.l260hfbmf {
  d: path("m19.162 20.396l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.235.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.lgscsz-mk {
  stop-color: var(--svg-color--fbcdb7, #FBCDB7);
  stop-opacity: 0;
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.md-4--lgv {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.37 7.976l.053-.07c.073-.12.081-.25.019-.288c-.064-.038-.174.028-.247.148l-.035.071z");
}

.mi15_86qf {
  d: path("M22.15 7.972c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.mmu9u7bsf {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
}

.mn787q_6r {
  stop-color: var(--svg-color--c7c5c9, #C7C5C9);
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

.n_geicc-w {
  stop-color: var(--svg-color--f52715, #F52715);
}

.n-izhdceg {
  fill: var(--svg-color--e9b4a4, #E9B4A4);
  d: path("m18.123 15.093l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01L10.97 20.18a.2.2 0 0 1-.27-.091L9.37 17.33c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.n7jws8bws {
  stop-color: var(--svg-color--4b4386, #4B4386);
  stop-opacity: 0;
}

.n7r2-292q {
  stop-color: var(--svg-color--958e9b, #958E9B);
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

.npx64-mvq {
  stop-color: var(--svg-color--ff9057, #FF9057);
  stop-opacity: 0;
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nuwcoob-p {
  stop-color: var(--svg-color--a49ba8, #A49BA8);
  stop-opacity: 0;
}

.nvv1klhll {
  stop-color: var(--svg-color--f8736b, #F8736B);
}

.nwhi_fa4f {
  stop-color: var(--svg-color--413b69, #413B69);
}

.o-axgkb8f {
  fill-rule: evenodd;
  d: path("M23.362 13.498c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.34c.33 2.086 1.175 4.092 4.47 5.87z");
}

.o6w7f1w7w {
  stop-color: var(--svg-color--ff722c, #FF722C);
}

.oes15pbkf {
  cx: 23.462px;
  cy: 7.616px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.os32btykc {
  stop-color: var(--svg-color--66619b, #66619B);
}

.p2417ob0x {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
  stop-opacity: 0;
}

.p5js8vl2d {
  stop-color: var(--svg-color--d8937c, #D8937C);
  stop-opacity: 0;
}

.p9znm86eq {
  stop-color: var(--svg-color--f4bda7, #F4BDA7);
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

.py2j-eb8k {
  d: path("M22.01 9.16c.277-.875.95-1.815 1.21-2.188l2.9 1.867l-.594 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.qi9--6bbx {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.502 7.488c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.qksuzsbug {
  stop-color: var(--svg-color--ff7857, #FF7857);
}

.r_k29qxtj {
  stop-color: var(--svg-color--fb5139, #FB5139);
  stop-opacity: 0;
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

.rfv__7srr {
  d: path("M23.43 10.439h1.905v1.844H23.43z");
}

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.s_296qbql {
  d: path("M2.054 29.683V20.73l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.112 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.556l5 4.753z");
}

.s7tjmje9c {
  stop-color: var(--svg-color--cf9297, #CF9297);
}

.s84dqqbgl {
  d: path("m22.738 25.887l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.se__e0blq {
  stop-color: var(--svg-color--ff7857, #FF7857);
  stop-opacity: 0;
}

.sf7z4ybcf {
  stop-color: var(--svg-color--d1cfd2, #D1CFD2);
  stop-opacity: 0;
}

.shmkg3ete {
  stop-color: var(--svg-color--7a7996, #7A7996);
}

.srxj-kbhv {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("m16.478 9.7l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.sz_3d1b0d {
  stop-color: var(--svg-color--ecae9b, #ECAE9B);
}

.t-qeblb7d {
  stop-color: var(--svg-color--e2e0e4, #E2E0E4);
}

.t0o3kkckx {
  d: path("M24.809 7.126a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.368.479l-.984-.758a.3.3 0 0 1-.055-.423");
}

.t20d06bem {
  stop-color: var(--svg-color--816878, #816878);
  stop-opacity: 0;
}

.t20fa7b7o {
  stop-color: var(--svg-color--9d94a6, #9D94A6);
}

.t4lrhnb4n {
  fill: var(--svg-color--dda49e, #DDA49E);
  d: path("m18.893 20.683l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.t4y9t702f {
  d: path("m18.893 20.683l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.tcaotyooh {
  fill: var(--svg-color--f6bca8, #F6BCA8);
  d: path("M14.663 10.932a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tnn6d9lnt {
  stop-color: var(--svg-color--ddac9a, #DDAC9A);
}

.tpihfdcpn {
  d: path("M20.182 6.613a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
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

.u3q9i3u8m {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m20.791 16.113l.195-.438l3.516 2.024c-.034.106-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.un4ucfbvi {
  d: path("m21.218 14.722l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
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

.v5_ahxl8w {
  stop-color: var(--svg-color--554682, #554682);
}

.v5m-xebtg {
  stop-color: var(--svg-color--f94b3a, #F94B3A);
}

.vfizx5bjt {
  d: path("m11.838 19.742l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
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

.vrt4g-pnz {
  d: path("m20.791 16.113l.195-.438l3.516 2.024c-.034.106-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.vyu2vwqby {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.412 8.178a.25.25 0 0 1 .032.352l-1.992 2.395a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.w-vr8zi9m {
  d: path("m23.528 8.08l.026-.04c.132-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
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

.wcf5rh81b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.264 7.532c.07.492.767 2.437 2.283 3.672");
}

.wd5xhxb1x {
  stop-color: var(--svg-color--e43e1c, #E43E1C);
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

.x_-8kbbtt {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.162 20.396l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.235.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x67sj11nn {
  d: path("m16.568 11.993l-.06.425c-.113.802-.39 1.194-.87 1.488l-.857-1.286l-.946-1.329a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .291-.433l-.023-.033a.28.28 0 1 1 .455-.323l.106.147a.28.28 0 0 1 .5-.224l.5.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345c-.031.201-.061.44-.06.6c.001.39.072.613.158.788");
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xapik5b0z {
  stop-color: var(--svg-color--ff9057, #FF9057);
}

.xtb_t7q6w {
  d: path("m25.127 10.109l.488-1.367l1.356 1.015c-.2.301-.727.563-.938.625a.435.435 0 0 1-.074.657c-.14.09-.508.105-.758-.204c-.2-.246-.133-.587-.074-.726");
}

.xthpsjb0p {
  fill-rule: evenodd;
  d: path("M24.184 18.696a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
}

.xzhs54baa {
  stop-color: var(--svg-color--948f8f, #948F8F);
  stop-opacity: 0;
}

.y9puldbfz {
  d: path("m24.299 18.734l1.906.63v.73a.953.953 0 0 1-1.906 0z");
}

.ya9kcr2sb {
  fill: var(--svg-color--f2bba9, #F2BBA9);
  d: path("m16.478 9.7l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.yht1-dbom {
  fill: var(--svg-color--f6bca8, #F6BCA8);
  d: path("M14.738 10.4a.28.28 0 1 1 .367-.421l1.5 1.31l-.367.42z");
}

.yk2k1_b7i {
  stop-color: var(--svg-color--eebba3, #EEBBA3);
  stop-opacity: 0;
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.yxg-bcbqu {
  d: path("M9.29 16.677a.93.93 0 0 1 .456-.698L2.054 18.63v2.661c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.yyd0qux2f {
  fill: var(--svg-color--f6bca8, #F6BCA8);
  d: path("M15.463 9.653a.28.28 0 0 1 .367-.42l1.41 1.419l-.226.512z");
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zf7t0yb1u {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
}

.zn_k87xtn {
  d: path("M13.638 1.694c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
}

.zp0x88wix {
  stop-color: var(--svg-color--aaa6ae, #AAA6AE);
  stop-opacity: 0;
}

.zrznt0bqi {
  cx: 25.146px;
  cy: 9.029px;
  r: 0.559px;
}

</style>
