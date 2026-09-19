<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iSXdcSd)" class="exhoyw4gv"/><path fill="url(#i5t0I4d)" class="exhoyw4gv"/><path fill="url(#ilrrOeb)" class="j-rqk6bkz"/><path fill="url(#i7CGhId)" class="j-rqk6bkz"/><path fill="url(#itrfWKb)" class="j-rqk6bkz"/><path fill="url(#iwnZWic)" class="j-rqk6bkz"/><path fill="url(#iCrVExb)" class="j-rqk6bkz"/><g filter="url(#ie452Qd)"><path class="fz4i6_bsf"/></g><path fill="url(#iBUiiWb)" class="z5frrpbgn"/><path fill="url(#ifewWId)" class="z5frrpbgn"/><path fill="url(#iPrfeAc)" class="z5frrpbgn"/><g filter="url(#iNrkXve)"><path fill="url(#iokuTQb)" class="de912vbfs"/></g><g filter="url(#iyg4a7R)"><path fill="url(#i7PZCCe)" clip-rule="evenodd" class="j69t2yrkf"/></g><g filter="url(#ivJvi8b)"><path stroke="url(#iiVml3d)" class="mjmu89cnj"/></g><path fill="url(#iLBtCGF)" class="ljc9dbbzn"/><path fill="url(#iHiKdsd)" class="ljc9dbbzn"/><path fill="url(#iqx6LOb)" class="ljc9dbbzn"/><g filter="url(#inV1Nxn)"><path fill="url(#id4pOse)" class="avuz8ebyo"/></g><g filter="url(#iVNPyZc)"><path fill="url(#imvxnuP)" class="iqrj5nfwk"/></g><path fill="url(#iP49B7d)" class="ra-4vdbyd"/><path fill="url(#iyWmrWc)" class="jgstdab2d"/><path fill="url(#ioJB0Ac)" class="jgstdab2d"/><path fill="url(#iPjBdbe)" class="jgstdab2d"/><path fill="url(#im5luKe)" transform="rotate(7.73 23.43 11.001)" class="dlraiibvv"/><g filter="url(#ipZlExp)"><path fill="url(#iSJ7dse)" class="a4xm33bri"/><path fill="url(#iq6ylJe)" class="a4xm33bri"/></g><path fill="url(#ig8mmfd)" clip-rule="evenodd" class="tmedxbboz"/><path fill="url(#ieFOhpe)" clip-rule="evenodd" class="nscvqsiaa"/><path fill="url(#iwYrO7c)" clip-rule="evenodd" class="nscvqsiaa"/><path clip-rule="evenodd" class="agn080pkg"/><g filter="url(#iwa8Zad)"><path class="rhnx6biwv"/><path fill="url(#iNFFwWd)" class="pbwuh0bbp"/></g><path class="sxbxtqb0b"/><g filter="url(#iWBTfTc)"><path class="shz7m9m-p"/><path fill="url(#imTW2Mi)" class="t1erqr98v"/><path fill="url(#ioFYgwH)" class="t1erqr98v"/></g><path class="wdsa_sbiu"/><path fill="url(#iAJlGib)" class="sn8e_p67d"/><path fill="url(#i6EFUSd)" class="sn8e_p67d"/><path fill="url(#izTByQb)" class="sn8e_p67d"/><path fill="url(#i3hp6fc)" class="sn8e_p67d"/><path fill="url(#ixmo5ab)" class="el5u7db5i"/><path class="b1qfl8b_f"/><circle class="a51d5sdhe"/><path fill="url(#i82y4jc)" class="ftiqeqbxy"/><path fill="url(#imJvRsd)" class="ftiqeqbxy"/><path fill="url(#ifa3zXE)" class="ftiqeqbxy"/><path fill="url(#iCvQpgb)" class="ftiqeqbxy"/><path fill="url(#imC4aWc)" class="ftiqeqbxy"/><g filter="url(#ifMgJTN)"><path class="fj-lmyb6m"/><path fill="url(#idSjXae)" class="mqqs0kbbm"/><path fill="url(#idqYkAc)" class="mqqs0kbbm"/><path fill="url(#iM7mEvc)" class="mqqs0kbbm"/></g><g filter="url(#i8GYjuc)"><path class="x7ff7ib8i"/><path fill="url(#i4RNbAc)" class="fmo-98jta"/></g><g filter="url(#iny4qNb)"><path class="nkhcf68rc"/><path fill="url(#iUpBUbd)" class="a5wft4_ea"/><path fill="url(#iBXaDcb)" class="a5wft4_ea"/><path fill="url(#i0T2S4b)" class="a5wft4_ea"/></g><g filter="url(#i3u8JYb)"><path class="iydqu8bvk"/><path fill="url(#iUpBUbd)" class="a5wft4_ea"/><path fill="url(#iBXaDcb)" class="a5wft4_ea"/><path fill="url(#i0T2S4b)" class="a5wft4_ea"/></g><g filter="url(#iYkHS7d)"><path class="hnc4-pujk"/><path fill="url(#iqDG6Dc)" class="e83-v1b6f"/></g><path fill="url(#iT7mK9l)" clip-rule="evenodd" class="zb73g1tas"/><path fill="url(#i5LtgHa)" clip-rule="evenodd" class="zb73g1tas"/><path fill="url(#i7TTe7m)" clip-rule="evenodd" class="zb73g1tas"/><path class="b9oq9ts0c"/><path fill="url(#i8gPIBu)" class="vy-vc-f0u"/><path fill="url(#itGorbc)" class="vy-vc-f0u"/><path class="ft6_co-qu"/><path fill="url(#inQxtgb)" class="v76f38t0i"/><path class="atigifbtz"/><path fill="url(#iauzR9d)" class="fzjurab7d"/><path class="tl_19pogq"/><path fill="url(#i7Lf7ce)" class="lz4x7vbbr"/><circle fill="url(#ijMYXxd)" class="xqetjrb9g"/><path clip-rule="evenodd" class="ui3hoghjy"/><path fill="url(#iNUqpxd)" clip-rule="evenodd" class="hygvrybwv"/><path fill="url(#iKr72sd)" clip-rule="evenodd" class="hygvrybwv"/><path fill="url(#iZmd4nd)" clip-rule="evenodd" class="hygvrybwv"/><g filter="url(#ipMCwYc)"><path fill="url(#iDt66qI)" class="cm39qmshq"/></g><g filter="url(#iCnADbb)"><path fill="url(#iKc3Dbx)" class="irkc5sbub"/></g><path class="klj9gobqi"/><path fill="url(#iFUsBFb)" class="pj7hgb2dn"/><g filter="url(#iLI9x4d)"><path clip-rule="evenodd" class="r7-auccou"/></g><path fill="url(#iDVlKNd)" class="udu923b8w"/><path fill="url(#iD8wQHz)" class="udu923b8w"/><path fill="url(#icpfwni)" class="udu923b8w"/><path fill="url(#itpQxce)" class="lgzakwuyo"/><path fill="url(#iQ95zvc)" class="lgzakwuyo"/><path fill="url(#idpvhfu)" class="lgzakwuyo"/><path class="rvk2agfis"/><path class="su75v0bqb"/><g filter="url(#iZcVkce)"><path class="cnlidqbft"/></g><defs><radialGradient id="iSXdcSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.205 28.698)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="itrfWKb" cx="0" cy="0" r="1" gradientTransform="rotate(-83.29 17.156 5.452)scale(2.67447 5.21781)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="iwnZWic" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 2.981 10.703)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="iCrVExb" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.611 21.573)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="iPrfeAc" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.336 5.354)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="i7PZCCe" cx="0" cy="0" r="1" gradientTransform="rotate(66.687 4.396 18.905)scale(6.35158 4.4947)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="t9yd8jl3c"/><stop offset="1" class="kg0zi9bal"/></radialGradient><radialGradient id="iHiKdsd" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.054 8.736)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="id4pOse" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 12.861 7.573)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="iP49B7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.10714 .67871 -.5326 -.08407 22.68 8.25)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="jg6j2gjjx"/><stop offset="1" class="b1fyieb0q"/></radialGradient><radialGradient id="ioJB0Ac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.252 21.776)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="iPjBdbe" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.174 19.296)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="im5luKe" cx="0" cy="0" r="1" gradientTransform="matrix(.00508 -1.12418 .93572 .00423 24.738 12.07)" gradientUnits="userSpaceOnUse"><stop class="xri9f-s_b"/><stop offset="1" class="gpbachbzq"/></radialGradient><radialGradient id="iSJ7dse" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 22.862 8.87)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="ij41a3b_y"/><stop offset="1" class="zp1heiwjd"/></radialGradient><radialGradient id="iq6ylJe" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.135 11.99)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="wuaq-3yri"/><stop offset="1" class="xt6ohhk1p"/></radialGradient><radialGradient id="iwYrO7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 25.709 19.667)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="iNFFwWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7533 -.625 .19855 -.2393 25.82 10.959)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jsa0_reur"/><stop offset="1" class="l-nb061ot"/></radialGradient><radialGradient id="ioFYgwH" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23438 -.90624 .39526 -.97452 21.344 22.146)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="tir_n7ltq"/><stop offset="1" class="eio20ib8u"/></radialGradient><radialGradient id="iAJlGib" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.099 10.043)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="i6EFUSd" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.7 13.346)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="i3hp6fc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 22.799 28.386)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="imJvRsd" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 9.964 11.769)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="qksuzsbug"/><stop offset="1" class="se__e0blq"/></radialGradient><radialGradient id="ifa3zXE" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.549 11.87)" gradientUnits="userSpaceOnUse"><stop class="jfz0xgwum"/><stop offset="1" class="k2u_13bdd"/></radialGradient><radialGradient id="iCvQpgb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06251 1.12498 -.6497 -1.19113 22.627 14.245)" gradientUnits="userSpaceOnUse"><stop class="n_geicc-w"/><stop offset="1" class="bn_1vkbwm"/></radialGradient><radialGradient id="imC4aWc" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.205 15.401)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="nvv1klhll"/><stop offset="1" class="ilft87v6y"/></radialGradient><radialGradient id="idSjXae" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.393 21.917)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="idqYkAc" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 19.94 19.792)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="iM7mEvc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 21.814 19.714)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="iUpBUbd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.299 17.98)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="i0T2S4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.002 17.323)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="iqDG6Dc" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.236 19.48)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="i7TTe7m" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.658 16.276)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="i8gPIBu" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.09375 .03207 .24052 19.68 6.88)" gradientUnits="userSpaceOnUse"><stop class="jmdfmwvec"/><stop offset="1" class="zf9ktoban"/></radialGradient><radialGradient id="itGorbc" cx="0" cy="0" r="1" gradientTransform="matrix(.8086 -.23047 .16066 .56368 19.414 7.672)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="dhgcuzsfj"/><stop offset="1" class="acezg1zki"/></radialGradient><radialGradient id="ijMYXxd" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.307 18.757)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="joi_unb8q"/><stop offset="1" class="heqi_9hpg"/></radialGradient><radialGradient id="iZmd4nd" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.65 9.776)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="iDt66qI" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.518 9.954)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="iKc3Dbx" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45313 1.162 .94162 25.361 8.48)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="iDVlKNd" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.401 6.971)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="iD8wQHz" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 -3.3125 9.2644 3.2338 19.44 19.73)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="nuwcoob-p"/><stop offset="1" class="gzdogx1hl"/></radialGradient><radialGradient id="icpfwni" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -2.224 19.778)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="itpQxce" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.192 16.156)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="o6w7f1w7w"/><stop offset="1" class="v5m-xebtg"/></radialGradient><radialGradient id="idpvhfu" cx="0" cy="0" r="1" gradientTransform="matrix(-.92187 .21875 -.25309 -1.06657 24.393 13.198)" gradientUnits="userSpaceOnUse"><stop class="xapik5b0z"/><stop offset="1" class="npx64-mvq"/></radialGradient><linearGradient id="i5t0I4d" x1="11.136" x2="11.136" y1="30.245" y2="28.95" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="ilrrOeb" x1="5.018" x2="6.174" y1="17.823" y2="21.105" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="i7CGhId" x1="5.518" x2="5.861" y1="17.823" y2="18.792" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="iBUiiWb" x1="13.111" x2="11.268" y1="2.136" y2="15.261" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="ifewWId" x1="2.299" x2="12.83" y1="18.011" y2="13.854" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="iokuTQb" x1="13.967" x2="16.568" y1="10.962" y2="15.479" gradientUnits="userSpaceOnUse"><stop offset=".368" class="d6jlrzbaa"/><stop offset="1" class="w5vd7udwg"/></linearGradient><linearGradient id="iiVml3d" x1="19.141" x2="21.359" y1="7.969" y2="11.906" gradientUnits="userSpaceOnUse"><stop class="slosmsfdt"/><stop offset="1" class="c66243b1p"/></linearGradient><linearGradient id="iLBtCGF" x1="4.205" x2="6.58" y1="5.542" y2="13.823" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="iqx6LOb" x1="5.486" x2="5.205" y1="14.433" y2="13.433" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="imvxnuP" x1="19.274" x2="20.633" y1="11.244" y2="15.904" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="iyWmrWc" x1="24.799" x2="26.205" y1="20.589" y2="20.589" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="ig8mmfd" x1="24.573" x2="24.299" y1="18.851" y2="18.851" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="ieFOhpe" x1="26.189" x2="24.173" y1="20.129" y2="19.292" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="imTW2Mi" x1="22.438" x2="21.037" y1="25.672" y2="26.266" gradientUnits="userSpaceOnUse"><stop class="f1spnwyxm"/><stop offset="1" class="e9dmvq9mi"/><stop offset="1" class="eplugbbfg"/></linearGradient><linearGradient id="izTByQb" x1="22.959" x2="22.854" y1="28.21" y2="28.128" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="ixmo5ab" x1="23.357" x2="23.604" y1="8.534" y2="8.097" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="i82y4jc" x1="24.58" x2="22.393" y1="16.104" y2="12.292" gradientUnits="userSpaceOnUse"><stop class="af5ecjb0e"/><stop offset="1" class="bg5vqlb1m"/></linearGradient><linearGradient id="i4RNbAc" x1="13.875" x2="14.5" y1="17.146" y2="18.145" gradientUnits="userSpaceOnUse"><stop class="lyhnd3axp"/><stop offset="1" class="prhc75bwt"/></linearGradient><linearGradient id="iBXaDcb" x1="19.83" x2="20.799" y1="20.393" y2="17.417" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="iT7mK9l" x1="22.801" x2="22.801" y1="16.98" y2="18.417" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="i5LtgHa" x1="23.994" x2="24.225" y1="18.507" y2="18.062" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="inQxtgb" x1="15.315" x2="15.643" y1="12.003" y2="11.62" gradientUnits="userSpaceOnUse"><stop offset=".002" class="xw072qbqh"/><stop offset="1" class="oyjtz6bgf"/></linearGradient><linearGradient id="iauzR9d" x1="15.523" x2="15.918" y1="11.574" y2="11.113" gradientUnits="userSpaceOnUse"><stop offset=".002" class="xw072qbqh"/><stop offset="1" class="oyjtz6bgf"/></linearGradient><linearGradient id="i7Lf7ce" x1="15.789" x2="16.226" y1="11.178" y2="10.659" gradientUnits="userSpaceOnUse"><stop offset=".002" class="xw072qbqh"/><stop offset="1" class="oyjtz6bgf"/></linearGradient><linearGradient id="iNUqpxd" x1="24.643" x2="24.322" y1="10.13" y2="9.886" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="iKr72sd" x1="23.189" x2="23.627" y1="10.683" y2="10.972" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="iFUsBFb" x1="16.207" x2="16.651" y1="10.95" y2="10.505" gradientUnits="userSpaceOnUse"><stop offset=".002" class="xw072qbqh"/><stop offset="1" class="oyjtz6bgf"/></linearGradient><linearGradient id="iQ95zvc" x1="22.908" x2="22.783" y1="15.011" y2="14.089" gradientUnits="userSpaceOnUse"><stop class="wd5xhxb1x"/><stop offset="1" class="r_k29qxtj"/></linearGradient><filter id="ie452Qd" width="8.743" height="7.346" x="1.654" y="23.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_855" result="effect2_innerShadow_4002_855"/></filter><filter id="iNrkXve" width="4.276" height="5.599" x="13.043" y="9.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_855" stdDeviation=".375"/></filter><filter id="iyg4a7R" width="6.514" height="7.799" x="17.846" y="6.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.462745 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="ivJvi8b" width="3.383" height="4.772" x="18.714" y="7.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_855" stdDeviation=".15"/></filter><filter id="inV1Nxn" width="3.479" height="7.738" x="13.618" y="2.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="iVNPyZc" width="2.822" height="15.029" x="18.984" y="2.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="ipZlExp" width="4.68" height="4.407" x="21.69" y="7.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.211765 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.396078 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_855" result="effect2_innerShadow_4002_855"/></filter><filter id="iwa8Zad" width="2.054" height="2.454" x="25.067" y="9.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0156863 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="iWBTfTc" width="5.316" height="9.197" x="18.453" y="20.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.439216 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="ifMgJTN" width="5.527" height="3.544" x="18.662" y="18.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="i8GYjuc" width="9.577" height="5.489" x="9.343" y="15.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.278431 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="iny4qNb" width="6.672" height="5.002" x="17.83" y="15.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="i3u8JYb" width="6.922" height="5.002" x="17.83" y="15.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.364706 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="iYkHS7d" width="2.568" height="3.646" x="9.32" y="17.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="ipMCwYc" width="4.913" height="4.647" x="23.084" y="5.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="iCnADbb" width="1.588" height="1.361" x="24.746" y="7.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="iLI9x4d" width="6.514" height="4.796" x="15.307" y="10.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.301961 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_855"/></filter><filter id="iZcVkce" width="3.862" height="3.738" x="15.944" y="10.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_855" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-climbing-medium-dark" /></template>
<style>
.a4xm33bri {
  d: path("M22.01 9.722c.277-.875.95-1.815 1.21-2.188l2.9 1.867l-.594 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.a51d5sdhe {
  cx: 23.462px;
  cy: 8.178px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.a5wft4_ea {
  d: path("m20.791 16.675l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.257-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.acezg1zki {
  stop-color: var(--svg-color--6c3738, #6C3738);
  stop-opacity: 0;
}

.af5ecjb0e {
  stop-color: var(--svg-color--ff712f, #FF712F);
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.agn080pkg {
  fill: var(--svg-color--86004d, #86004D);
  fill-rule: evenodd;
  d: path("M22.375 9.44a.1.1 0 0 1 .139-.028c.085.055.25.102.52.04a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.atigifbtz {
  fill: var(--svg-color--825c5a, #825C5A);
  d: path("M14.738 10.961a.28.28 0 0 1 .367-.42l1.5 1.31l-.367.42z");
}

.avuz8ebyo {
  d: path("M13.638 2.256c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.b1fyieb0q {
  stop-color: var(--svg-color--704a44, #704A44);
}

.b1qfl8b_f {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.37 8.538l.053-.07c.073-.12.081-.25.019-.288c-.064-.038-.174.028-.247.148l-.035.071z");
}

.b9oq9ts0c {
  fill: var(--svg-color--7d5452, #7D5452);
  d: path("M20.182 7.175a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
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

.cm39qmshq {
  d: path("M26.808 10.306L23.18 7.61a.22.22 0 0 1-.069-.288a4.8 4.8 0 0 1 .655-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
}

.cnlidqbft {
  stroke: var(--svg-color--916c65, #916C65);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.594 11.336l2.562 2.437");
}

.d6jlrzbaa {
  stop-color: var(--svg-color--908790, #908790);
}

.de912vbfs {
  d: path("m16.568 12.555l-.06.425c-.113.802-.39 1.194-.87 1.488l-.857-1.286l-.946-1.329a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .291-.433l-.023-.033a.28.28 0 1 1 .455-.323l.106.146a.28.28 0 0 1 .5-.223l.5.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345a4 4 0 0 0-.06.6c.001.39.072.613.158.788");
}

.dfv3zlvmf {
  stop-color: var(--svg-color--648431, #648431);
}

.dhgcuzsfj {
  stop-color: var(--svg-color--6c3738, #6C3738);
}

.dlraiibvv {
  d: path("M23.43 11.001h1.905v1.844H23.43z");
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

.e83-v1b6f {
  d: path("m11.838 20.304l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.095 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
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

.el5u7db5i {
  d: path("m23.528 8.642l.026-.04c.132-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
}

.eplugbbfg {
  stop-color: var(--svg-color--9a756e, #9A756E);
  stop-opacity: 0;
}

.exhoyw4gv {
  d: path("M2.054 30.245v-8.953l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.112 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.557l5 4.752z");
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

.fj-lmyb6m {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.162 20.958l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.235.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.fmo-98jta {
  d: path("m18.123 15.655l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.ft5dv1b6b {
  fill: none;
}

.ft6_co-qu {
  fill: var(--svg-color--825c5a, #825C5A);
  d: path("M14.663 11.494a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.ftiqeqbxy {
  d: path("m22.322 13.198l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.101-1.766c-.317-.171-1.026-.28-1.399-.16s-.73.664-.883 1.09");
}

.fwnzc4ctw {
  stop-color: var(--svg-color--5a332d, #5A332D);
}

.fy9sosv6u {
  stop-color: var(--svg-color--417c62, #417C62);
  stop-opacity: 0;
}

.fz4i6_bsf {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.054 23.3v6.945h8.343a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.524c-.065-.14-.186-.45-.371-.924l-.285-.724c-.322-.816-.953-1.219-1.437-1.422z");
}

.fzjurab7d {
  d: path("M14.738 10.961a.28.28 0 0 1 .367-.42l1.5 1.31l-.367.42z");
}

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
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

.gzdogx1hl {
  stop-color: var(--svg-color--7e7776, #7E7776);
}

.heqi_9hpg {
  stop-color: var(--svg-color--6d3647, #6D3647);
}

.hnc4-pujk {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m11.838 20.304l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.095 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.hygvrybwv {
  fill-rule: evenodd;
  d: path("M25.412 8.74a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.ij41a3b_y {
  stop-color: var(--svg-color--75554d, #75554D);
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.ilft87v6y {
  stop-color: var(--svg-color--f8736b, #F8736B);
  stop-opacity: 0;
}

.iqrj5nfwk {
  d: path("M18.984 2.3v9.588c0 .132.027.263.079.384l1.706 3.989l.42.137c.05.114.166.978.28.929a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V2.3z");
}

.irkc5sbub {
  d: path("M24.809 7.688a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.368.479l-.984-.758a.3.3 0 0 1-.055-.423");
}

.iydqu8bvk {
  fill: var(--svg-color--9f97a9, #9F97A9);
  d: path("m20.791 16.675l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.257-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.j-c4i6bgu {
  stop-color: var(--svg-color--5e598c, #5E598C);
  stop-opacity: 0;
}

.j-rqk6bkz {
  d: path("M9.29 17.239a.93.93 0 0 1 .456-.698l-7.692 2.651v2.661c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.j69t2yrkf {
  fill-rule: evenodd;
  d: path("M23.362 14.06c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.341c.33 2.085 1.175 4.09 4.47 5.868z");
}

.jbbp6_bdq {
  stop-color: var(--svg-color--716170, #716170);
  stop-opacity: 0;
}

.jfz0xgwum {
  stop-color: var(--svg-color--e2452b, #E2452B);
}

.jg6j2gjjx {
  stop-color: var(--svg-color--785c53, #785C53);
}

.jgstdab2d {
  d: path("m24.299 19.296l1.906.63v.73a.953.953 0 0 1-1.906 0z");
}

.jmdfmwvec {
  stop-color: var(--svg-color--91736a, #91736A);
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.joi_unb8q {
  stop-color: var(--svg-color--714c53, #714C53);
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jsa0_reur {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k2u_13bdd {
  stop-color: var(--svg-color--e2452b, #E2452B);
  stop-opacity: 0;
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

.klj9gobqi {
  fill: var(--svg-color--825c5a, #825C5A);
  d: path("M15.463 10.215a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.l-nb061ot {
  stop-color: var(--svg-color--1d191c, #1D191C);
  stop-opacity: 0;
}

.lgzakwuyo {
  d: path("m21.218 15.284l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
}

.ljc9dbbzn {
  d: path("M9.918 2.3c.551 1.054 1.37 2.957 1.85 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V2.3z");
}

.lyhnd3axp {
  stop-color: var(--svg-color--856660, #856660);
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.lz4x7vbbr {
  d: path("M14.89 10.446a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.mjmu89cnj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.264 8.094c.07.492.767 2.437 2.283 3.672");
}

.mmu9u7bsf {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
}

.mn787q_6r {
  stop-color: var(--svg-color--c7c5c9, #C7C5C9);
}

.mqqs0kbbm {
  d: path("m19.162 20.958l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.235.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
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

.nkhcf68rc {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m20.791 16.675l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.257-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
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

.nscvqsiaa {
  fill-rule: evenodd;
  d: path("M24.184 19.258a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
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

.o6w7f1w7w {
  stop-color: var(--svg-color--ff722c, #FF722C);
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

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pbwuh0bbp {
  d: path("m25.127 10.67l.488-1.366l1.356 1.015c-.2.301-.727.563-.938.625a.435.435 0 0 1-.074.657c-.14.09-.508.105-.758-.203c-.2-.247-.133-.588-.074-.727");
}

.pids_pbns {
  stop-color: var(--svg-color--948f8f, #948F8F);
}

.pj7hgb2dn {
  d: path("M15.463 10.215a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.prhc75bwt {
  stop-color: var(--svg-color--7c544c, #7C544C);
  stop-opacity: 0;
}

.ps4wek9uf {
  stop-color: var(--svg-color--4a4476, #4A4476);
  stop-opacity: 0;
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.qksuzsbug {
  stop-color: var(--svg-color--ff7857, #FF7857);
}

.r_k29qxtj {
  stop-color: var(--svg-color--fb5139, #FB5139);
  stop-opacity: 0;
}

.r7-auccou {
  fill: var(--svg-color--825757, #825757);
  fill-rule: evenodd;
  d: path("m17.962 14.49l-2.655-2.436l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.423l.433 1.696l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.r8uyz9bqp {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
}

.ra-4vdbyd {
  d: path("M22.15 8.534c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.rdr27y14e {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
  stop-opacity: 0;
}

.reex3410h {
  stop-color: var(--svg-color--e2dfe2, #E2DFE2);
}

.rhnx6biwv {
  fill: var(--svg-color--1b131d, #1B131D);
  d: path("m25.127 10.67l.488-1.366l1.356 1.015c-.2.301-.727.563-.938.625a.435.435 0 0 1-.074.657c-.14.09-.508.105-.758-.203c-.2-.247-.133-.588-.074-.727");
}

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.rvk2agfis {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("m16.478 10.262l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
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

.shz7m9m-p {
  fill: var(--svg-color--7b4b56, #7B4B56);
  d: path("m18.893 21.245l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.slosmsfdt {
  stop-color: var(--svg-color--85635d, #85635D);
}

.sn8e_p67d {
  d: path("m22.738 26.45l.799.574a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.su75v0bqb {
  fill: var(--svg-color--815657, #815657);
  d: path("m16.478 10.262l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.sxbxtqb0b {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.502 8.05c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.t-qeblb7d {
  stop-color: var(--svg-color--e2e0e4, #E2E0E4);
}

.t1erqr98v {
  d: path("m18.893 21.245l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
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

.tl_19pogq {
  fill: var(--svg-color--825c5a, #825C5A);
  d: path("M14.89 10.446a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.tmedxbboz {
  fill-rule: evenodd;
  d: path("M24.373 18.21a.2.2 0 0 1 .2.2v.882a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
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

.tylpo8bot {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
  stop-opacity: 0;
}

.udu923b8w {
  d: path("M20.793 16.67c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014c-.906-.21-1.484-.406-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

.ui3hoghjy {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.412 8.74a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
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

.v5m-xebtg {
  stop-color: var(--svg-color--f94b3a, #F94B3A);
}

.v76f38t0i {
  d: path("M14.663 11.494a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.vp6yj4xxl {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
}

.vps27w8pe {
  stop-color: var(--svg-color--413b69, #413B69);
  stop-opacity: 0;
}

.vy-vc-f0u {
  d: path("M20.182 7.175a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.w5vd7udwg {
  stop-color: var(--svg-color--908790, #908790);
  stop-opacity: 0;
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wd5xhxb1x {
  stop-color: var(--svg-color--e43e1c, #E43E1C);
}

.wdsa_sbiu {
  fill: var(--svg-color--544583, #544583);
  d: path("m22.738 26.45l.799.574a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
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

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x7ff7ib8i {
  fill: var(--svg-color--7c554d, #7C554D);
  d: path("m18.123 15.655l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xapik5b0z {
  stop-color: var(--svg-color--ff9057, #FF9057);
}

.xqetjrb9g {
  cx: 25.146px;
  cy: 9.591px;
  r: 0.559px;
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

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.z5frrpbgn {
  d: path("M14.501 14.98L2.054 19.342V2.3h15.944c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.zb73g1tas {
  fill-rule: evenodd;
  d: path("M20.77 16.042a.25.25 0 0 1 .341-.092l3.629 2.09a.25.25 0 1 1-.25.434l-3.628-2.09a.25.25 0 0 1-.092-.342");
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

.zp0x88wix {
  stop-color: var(--svg-color--aaa6ae, #AAA6AE);
  stop-opacity: 0;
}

.zp1heiwjd {
  stop-color: var(--svg-color--73474c, #73474C);
}

</style>
