<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iI6LZQb)" class="j0vrx6bvn"/><path fill="url(#i8gaKjd)" class="j0vrx6bvn"/><path fill="url(#iXLgNPa)" class="z4spfobgt"/><path fill="url(#iWeyo5c)" class="z4spfobgt"/><path fill="url(#iezPOKc)" class="z4spfobgt"/><path fill="url(#iBp1A1d)" class="z4spfobgt"/><path fill="url(#iOvXTXd)" class="z4spfobgt"/><g filter="url(#iL8K3vd)"><path class="yc4gimbqr"/></g><path fill="url(#iBsnGpc)" class="jsbpk9bkc"/><path fill="url(#iTv5Gxc)" class="jsbpk9bkc"/><path fill="url(#irVQ6ec)" class="jsbpk9bkc"/><g filter="url(#inM3r8b)"><path fill="url(#idJUBEg)" class="altra7bfc"/></g><g filter="url(#iwKRk7d)"><path fill="url(#izsyxyb)" clip-rule="evenodd" class="w7bim1b_c"/></g><g filter="url(#i3liiLc)"><path stroke="url(#ipSZzwb)" class="y98a87uix"/></g><path fill="url(#i6TKMCn)" class="esaz51-0q"/><path fill="url(#iUMIiKc)" class="esaz51-0q"/><path fill="url(#i5SP2nd)" class="esaz51-0q"/><g filter="url(#irONfXh)"><path fill="url(#iDX3I6d)" class="x--zxyb9a"/></g><g filter="url(#iMJSyBb)"><path fill="url(#ieb6lmb)" class="n8-sscbcs"/></g><path fill="url(#i2bjduE)" class="r004zbc7a"/><path fill="url(#isOrXCd)" class="dz6owpvak"/><path fill="url(#iwF9juq)" class="dz6owpvak"/><path fill="url(#iLAc1ec)" class="dz6owpvak"/><path fill="url(#iXuqVSc)" transform="rotate(7.73 23.58 10.897)" class="d_8kj491g"/><g filter="url(#iv99DEd)"><path fill="url(#iNwFHOc)" class="ijp7u7nkv"/><path fill="url(#il2xD8b)" class="ijp7u7nkv"/></g><path fill="url(#iDlCVBg)" clip-rule="evenodd" class="p-qyixqwk"/><path fill="url(#ipACOzd)" clip-rule="evenodd" class="vd0w6m1tw"/><path fill="url(#iCV9NyV)" clip-rule="evenodd" class="vd0w6m1tw"/><path clip-rule="evenodd" class="glncw8bwg"/><path class="olalv5p_g"/><path class="p9woy_1wh"/><g filter="url(#i0deUsw)"><path class="ho6ognbdf"/><path fill="url(#iWVbN5c)" class="akhpnhy_i"/><path fill="url(#inwUtzc)" class="akhpnhy_i"/></g><path class="o1-p4ybsa"/><path fill="url(#ilBXd3Y)" class="grmki_b2y"/><path fill="url(#iSY2qsb)" class="grmki_b2y"/><path fill="url(#i3aoAvc)" class="grmki_b2y"/><path fill="url(#i7KSwMd)" class="grmki_b2y"/><path fill="url(#iju3tqe)" class="btf2jab4e"/><path class="rnnzvvb9z"/><g filter="url(#iXZDAmc)"><path fill="url(#iTUqgpd)" class="tk_a4ibow"/></g><circle class="e7fgbqppd"/><path fill="url(#ivuEgvM)" class="e1x5fgbaj"/><path fill="url(#ienGFpe)" class="e1x5fgbaj"/><path fill="url(#id3DZpb)" class="e1x5fgbaj"/><path fill="url(#iAHUAlc)" class="e1x5fgbaj"/><path fill="url(#iryrSGb)" class="e1x5fgbaj"/><path fill="url(#i6IB3Xd)" class="e1x5fgbaj"/><g filter="url(#i4Y5Qsc)"><path class="gawwfibke"/><path fill="url(#i6qVH5d)" class="hjct2zbcj"/><path fill="url(#inUG1Ld)" class="hjct2zbcj"/><path fill="url(#iXOgUWd)" class="hjct2zbcj"/></g><g filter="url(#i2BfjEc)"><path class="b_vd3qpoc"/><path fill="url(#i6HCxyb)" class="zrjrssbvc"/></g><g filter="url(#iWYoLqd)"><path class="bbxs-e46n"/><path fill="url(#i4z9Rtb)" class="amzy5692m"/><path fill="url(#i3qBxdb)" class="amzy5692m"/><path fill="url(#i9hNy3s)" class="amzy5692m"/></g><g filter="url(#i898mFc)"><path class="itkv95dhm"/><path fill="url(#i4z9Rtb)" class="amzy5692m"/><path fill="url(#i3qBxdb)" class="amzy5692m"/><path fill="url(#i9hNy3s)" class="amzy5692m"/></g><g filter="url(#iB6Ifvb)"><path class="ju80-yb6q"/><path fill="url(#iq7Dihc)" class="e784002am"/></g><path fill="url(#ig6jGre)" clip-rule="evenodd" class="md1x-bb_r"/><path fill="url(#iOI3atb)" clip-rule="evenodd" class="md1x-bb_r"/><path fill="url(#iFE2Afc)" clip-rule="evenodd" class="md1x-bb_r"/><path class="mg4s00w7b"/><path fill="url(#iiVYztd)" class="j4m0po66p"/><path fill="url(#i4U3QPb)" class="j4m0po66p"/><path class="yelz-umev"/><path fill="url(#iogfTAb)" class="uskwimbnj"/><path class="ob13unr5n"/><path fill="url(#iSAdewe)" class="qo07u2b9p"/><path class="smv_aqb3z"/><path fill="url(#iR93uiV)" class="waoqorb7a"/><circle fill="url(#i5KQVGs)" class="w6qb8tbjg"/><path clip-rule="evenodd" class="zdly7i1an"/><path fill="url(#iWsV7Mb)" clip-rule="evenodd" class="zf_mfmbxn"/><path fill="url(#ilXqvub)" clip-rule="evenodd" class="zf_mfmbxn"/><path fill="url(#isDKrJe)" clip-rule="evenodd" class="zf_mfmbxn"/><g filter="url(#iECEoCd)"><path fill="url(#iktOZsd)" class="s0mn5z5qq"/></g><g filter="url(#inM2wEb)"><path fill="url(#irae2oe)" class="v6skbb3bx"/></g><path class="i-c5fwbwi"/><path fill="url(#iN4G2ld)" class="b6_1mmb1m"/><g filter="url(#iDxjJ1c)"><path clip-rule="evenodd" class="l7gu2-m-u"/></g><path fill="url(#iNCJJEd)" class="y7qyzyb5d"/><path fill="url(#irQx0Gb)" class="y7qyzyb5d"/><path fill="url(#iFiI0Vd)" class="y7qyzyb5d"/><path fill="url(#iWAckTb)" class="k6thccsxs"/><path fill="url(#iOuN3Yb)" class="k6thccsxs"/><path fill="url(#icao1Yb)" class="k6thccsxs"/><path class="sc7rv5bwb"/><path class="i72xohbjt"/><g filter="url(#iQG20Md)"><path class="sjt__ehso"/></g><defs><radialGradient id="iI6LZQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.355 28.595)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="iezPOKc" cx="0" cy="0" r="1" gradientTransform="rotate(-83.29 17.173 5.315)scale(2.67447 5.21781)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="iBp1A1d" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 3.068 10.667)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="iOvXTXd" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.762 21.47)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="irVQ6ec" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.414 5.305)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="izsyxyb" cx="0" cy="0" r="1" gradientTransform="rotate(66.687 4.55 18.967)scale(6.35158 4.4947)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="f_1v57bhd"/><stop offset="1" class="pl76o5b_i"/></radialGradient><radialGradient id="iUMIiKc" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.205 8.632)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="iDX3I6d" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 13.012 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="i2bjduE" cx="0" cy="0" r="1" gradientTransform="matrix(-.10714 .67871 -.5326 -.08407 22.83 8.146)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="p62i0qb1k"/><stop offset="1" class="d7aonq0wf"/></radialGradient><radialGradient id="iwF9juq" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.403 21.672)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="iLAc1ec" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.325 19.192)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="iXuqVSc" cx="0" cy="0" r="1" gradientTransform="matrix(.00508 -1.12418 .93572 .00423 24.889 11.965)" gradientUnits="userSpaceOnUse"><stop class="nk-mbmbtk"/><stop offset="1" class="db1j3cbeu"/></radialGradient><radialGradient id="iNwFHOc" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 23.012 8.766)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gro4u4t-y"/><stop offset="1" class="x8-nb-ihc"/></radialGradient><radialGradient id="il2xD8b" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.24 11.982)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="wxl7pfshq"/><stop offset="1" class="ghwh3eklg"/></radialGradient><radialGradient id="iCV9NyV" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 25.86 19.563)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="inwUtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23438 -.90624 .39526 -.97452 21.495 22.042)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="bylttzbhe"/><stop offset="1" class="f7ds2glhm"/></radialGradient><radialGradient id="ilBXd3Y" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.158 9.967)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="iSY2qsb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.77 13.288)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="i7KSwMd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 22.95 28.282)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="iTUqgpd" cx="0" cy="0" r="1" gradientTransform="rotate(174.089 13.283 6.068)scale(2.24975 3.24434)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="gs2o78_ix"/><stop offset="1" class="kjuj_ebnl"/></radialGradient><radialGradient id="ienGFpe" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 10.06 11.747)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="u005aj31u"/><stop offset="1" class="mg4rwjbbx"/></radialGradient><radialGradient id="id3DZpb" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.7 11.766)" gradientUnits="userSpaceOnUse"><stop class="mq4z99xlk"/><stop offset="1" class="l-wqt88hf"/></radialGradient><radialGradient id="iAHUAlc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92138 1.06381 -.61436 -1.10962 22.637 14.202)" gradientUnits="userSpaceOnUse"><stop class="ojet8cb1m"/><stop offset="1" class="sc-4z3bze"/></radialGradient><radialGradient id="iryrSGb" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.356 15.297)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="x3_nmbc0c"/><stop offset="1" class="zfzerzb4h"/></radialGradient><radialGradient id="i6IB3Xd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57812 .45313 -.91434 -1.16656 25.422 12.468)" gradientUnits="userSpaceOnUse"><stop class="ycpxb2wjj"/><stop offset="1" class="yp3ph2bir"/></radialGradient><radialGradient id="i6qVH5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.544 21.813)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="inUG1Ld" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 20.09 19.688)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="iXOgUWd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 21.965 19.61)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="i4z9Rtb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.45 17.875)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="i9hNy3s" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.153 17.22)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="iq7Dihc" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.387 19.376)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="iFE2Afc" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.81 16.172)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="iiVYztd" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.09375 .03207 .24052 19.83 6.776)" gradientUnits="userSpaceOnUse"><stop class="r_5s-tw4v"/><stop offset="1" class="kqp9fdbzy"/></radialGradient><radialGradient id="i4U3QPb" cx="0" cy="0" r="1" gradientTransform="matrix(.8086 -.23047 .16066 .56368 19.565 7.568)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="czdn7vy6a"/><stop offset="1" class="gk9uazn2k"/></radialGradient><radialGradient id="i5KQVGs" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.44 18.789)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="a0px9dj6c"/><stop offset="1" class="ufi1sccsl"/></radialGradient><radialGradient id="isDKrJe" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.801 9.672)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="iktOZsd" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.618 9.937)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="irae2oe" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45313 1.162 .94162 25.512 8.375)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="iNCJJEd" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.468 6.906)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="irQx0Gb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15626 -3.3125 9.2644 3.23382 19.59 19.625)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="nuwcoob-p"/><stop offset="1" class="gzdogx1hl"/></radialGradient><radialGradient id="iFiI0Vd" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -2.086 19.818)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="iWAckTb" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.312 16.168)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="xcafsktgp"/><stop offset="1" class="x0t8b2bhw"/></radialGradient><radialGradient id="icao1Yb" cx="0" cy="0" r="1" gradientTransform="matrix(-.97442 .66902 -.77403 -1.12736 24.407 12.75)" gradientUnits="userSpaceOnUse"><stop class="yjh8oi0bq"/><stop offset="1" class="cshe_hl2j"/></radialGradient><linearGradient id="i8gaKjd" x1="11.287" x2="11.287" y1="30.141" y2="28.846" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="iXLgNPa" x1="5.169" x2="6.325" y1="17.719" y2="21" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="iWeyo5c" x1="5.669" x2="6.012" y1="17.719" y2="18.688" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="iBsnGpc" x1="13.262" x2="11.419" y1="2.032" y2="15.157" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="iTv5Gxc" x1="2.45" x2="12.981" y1="17.907" y2="13.751" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="idJUBEg" x1="14.118" x2="16.719" y1="10.858" y2="15.376" gradientUnits="userSpaceOnUse"><stop offset=".368" class="d6jlrzbaa"/><stop offset="1" class="w5vd7udwg"/></linearGradient><linearGradient id="ipSZzwb" x1="19.33" x2="21.303" y1="7.887" y2="10.832" gradientUnits="userSpaceOnUse"><stop class="v8ombmbjb"/><stop offset="1" class="r1g9oggar"/></linearGradient><linearGradient id="i6TKMCn" x1="4.356" x2="6.731" y1="5.438" y2="13.719" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="i5SP2nd" x1="5.637" x2="5.356" y1="14.329" y2="13.329" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="ieb6lmb" x1="19.425" x2="20.784" y1="11.14" y2="15.8" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="isOrXCd" x1="24.95" x2="26.356" y1="20.485" y2="20.485" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="iDlCVBg" x1="24.724" x2="24.45" y1="18.747" y2="18.747" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="ipACOzd" x1="26.34" x2="24.324" y1="20.025" y2="19.188" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="iWVbN5c" x1="22.588" x2="21.188" y1="25.568" y2="26.203" gradientUnits="userSpaceOnUse"><stop class="ckxh1ljog"/><stop offset="1" class="om1zr9boo"/></linearGradient><linearGradient id="i3aoAvc" x1="23.11" x2="23.005" y1="28.106" y2="28.024" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="iju3tqe" x1="23.508" x2="23.755" y1="8.43" y2="7.993" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="ivuEgvM" x1="24.731" x2="22.544" y1="16" y2="12.188" gradientUnits="userSpaceOnUse"><stop class="n_z8kdbjp"/><stop offset="1" class="pcd65pbuz"/></linearGradient><linearGradient id="i6HCxyb" x1="14.026" x2="14.651" y1="17.042" y2="18.041" gradientUnits="userSpaceOnUse"><stop class="eizi_gdki"/><stop offset="1" class="pbgm9vhci"/></linearGradient><linearGradient id="i3qBxdb" x1="19.981" x2="20.95" y1="20.29" y2="17.313" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="ig6jGre" x1="22.952" x2="22.952" y1="16.875" y2="18.313" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="iOI3atb" x1="24.145" x2="24.376" y1="18.403" y2="17.958" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="iogfTAb" x1="15.466" x2="15.605" y1="11.899" y2="11.731" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="iSAdewe" x1="15.674" x2="15.842" y1="11.47" y2="11.268" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="iR93uiV" x1="15.94" x2="16.126" y1="11.074" y2="10.847" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="iWsV7Mb" x1="24.794" x2="24.473" y1="10.026" y2="9.782" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="ilXqvub" x1="23.34" x2="23.778" y1="10.579" y2="10.868" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="iN4G2ld" x1="16.358" x2="16.548" y1="10.846" y2="10.65" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="iOuN3Yb" x1="23.059" x2="22.934" y1="14.907" y2="13.985" gradientUnits="userSpaceOnUse"><stop class="b2cvh2xce"/><stop offset="1" class="s4ygnfbfl"/></linearGradient><filter id="iL8K3vd" width="8.743" height="7.346" x="1.805" y="23.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_862" result="effect2_innerShadow_4002_862"/></filter><filter id="inM3r8b" width="4.276" height="5.599" x="13.194" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_862" stdDeviation=".375"/></filter><filter id="iwKRk7d" width="6.514" height="7.799" x="17.997" y="6.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.721569 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="i3liiLc" width="2.679" height="4.12" x="18.865" y="7.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_862" stdDeviation=".15"/></filter><filter id="irONfXh" width="3.479" height="7.738" x="13.769" y="2.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="iMJSyBb" width="2.822" height="15.029" x="19.135" y="2.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="iv99DEd" width="4.68" height="4.407" x="21.841" y="7.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.423529 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.670588 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_862" result="effect2_innerShadow_4002_862"/></filter><filter id="i0deUsw" width="5.316" height="9.197" x="18.605" y="20.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.639216 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="iXZDAmc" width="2.864" height="4.018" x="24.407" y="8.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.607843 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="i4Y5Qsc" width="5.527" height="3.544" x="18.813" y="18.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="i2BfjEc" width="9.577" height="5.489" x="9.494" y="15.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.47451 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="iWYoLqd" width="6.672" height="5.002" x="17.981" y="15.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="i898mFc" width="6.922" height="5.002" x="17.981" y="15.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.364706 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="iB6Ifvb" width="2.568" height="3.646" x="9.471" y="17.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="iECEoCd" width="4.913" height="4.647" x="23.235" y="5.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="inM2wEb" width="1.588" height="1.361" x="24.897" y="7.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="iDxjJ1c" width="6.514" height="4.796" x="15.458" y="10.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.509804 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_862"/></filter><filter id="iQG20Md" width="3.862" height="3.738" x="15.977" y="10.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_862" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-climbing-medium-light" /></template>
<style>
.a0px9dj6c {
  stop-color: var(--svg-color--c3958d, #C3958D);
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.akhpnhy_i {
  d: path("m19.044 21.141l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.127-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203a448 448 0 0 1-2.75-3.945c-.613-.9-.167-1.636.133-1.89");
}

.altra7bfc {
  d: path("m16.719 12.45l-.06.426c-.113.802-.39 1.194-.87 1.488l-.857-1.286l-.946-1.329a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .292-.433l-.024-.033a.28.28 0 1 1 .455-.323l.106.146a.28.28 0 0 1 .5-.223l.5.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345a4 4 0 0 0-.06.6c.001.39.072.613.158.788");
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.amzy5692m {
  d: path("m20.942 16.57l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.b_vd3qpoc {
  fill: var(--svg-color--d8a283, #D8A283);
  d: path("m18.274 15.551l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.b2cvh2xce {
  stop-color: var(--svg-color--5a3e95, #5A3E95);
}

.b6_1mmb1m {
  d: path("M15.614 10.111a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.bbxs-e46n {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m20.942 16.57l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biyiff5mh {
  stop-color: var(--svg-color--333061, #333061);
}

.boi6lnlog {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
}

.bpm5gvbdi {
  stop-color: var(--svg-color--e5e3e5, #E5E3E5);
}

.btf2jab4e {
  d: path("m23.679 8.538l.026-.04c.132-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
}

.bylttzbhe {
  stop-color: var(--svg-color--bf7f81, #BF7F81);
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.ckxh1ljog {
  stop-color: var(--svg-color--f0bea1, #F0BEA1);
}

.cshe_hl2j {
  stop-color: var(--svg-color--9e83ce, #9E83CE);
  stop-opacity: 0;
}

.czdn7vy6a {
  stop-color: var(--svg-color--b9745e, #B9745E);
}

.d_8kj491g {
  d: path("M23.581 10.897h1.905v1.844h-1.905z");
}

.d6jlrzbaa {
  stop-color: var(--svg-color--908790, #908790);
}

.d7aonq0wf {
  stop-color: var(--svg-color--d4997b, #D4997B);
}

.db1j3cbeu {
  stop-color: var(--svg-color--cb7a6a, #CB7A6A);
}

.dfv3zlvmf {
  stop-color: var(--svg-color--648431, #648431);
}

.dnpfueb4s {
  stop-color: var(--svg-color--40347f, #40347F);
}

.dz6owpvak {
  d: path("m24.45 19.192l1.906.63v.73a.953.953 0 1 1-1.906 0z");
}

.e_59tbbed {
  stop-color: var(--svg-color--292557, #292557);
}

.e1x5fgbaj {
  d: path("m22.473 13.094l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.102-1.765c-.316-.172-1.025-.28-1.398-.16s-.73.663-.883 1.09");
}

.e2k-esbpn {
  stop-color: var(--svg-color--c3c0c6, #C3C0C6);
  stop-opacity: 0;
}

.e784002am {
  d: path("m11.989 20.2l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.e7fgbqppd {
  cx: 23.613px;
  cy: 8.074px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.eizi_gdki {
  stop-color: var(--svg-color--dca888, #DCA888);
}

.eky141x3a {
  stop-color: var(--svg-color--489778, #489778);
}

.esaz51-0q {
  d: path("M10.07 2.196c.55 1.054 1.37 2.957 1.849 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V2.196z");
}

.f_1v57bhd {
  stop-color: var(--svg-color--d59b81, #D59B81);
}

.f2xkzabrk {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
  stop-opacity: 0;
}

.f2yuiwowd {
  stop-color: var(--svg-color--948b99, #948B99);
}

.f7ds2glhm {
  stop-color: var(--svg-color--bf7f81, #BF7F81);
  stop-opacity: 0;
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

.gawwfibke {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.313 20.854l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
}

.ghwh3eklg {
  stop-color: var(--svg-color--a46f70, #A46F70);
  stop-opacity: 0;
}

.gk9uazn2k {
  stop-color: var(--svg-color--b9745e, #B9745E);
  stop-opacity: 0;
}

.glncw8bwg {
  fill: var(--svg-color--86004d, #86004D);
  fill-rule: evenodd;
  d: path("M22.526 9.336a.1.1 0 0 1 .139-.029c.085.056.25.103.52.041a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.grmki_b2y {
  d: path("m22.889 26.345l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.gro4u4t-y {
  stop-color: var(--svg-color--d19f82, #D19F82);
}

.gs2o78_ix {
  stop-color: var(--svg-color--fee0b4, #FEE0B4);
}

.gu1w6obkb {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
  stop-opacity: 0;
}

.gzdogx1hl {
  stop-color: var(--svg-color--7e7776, #7E7776);
}

.hjct2zbcj {
  d: path("m19.313 20.854l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.ho6ognbdf {
  fill: var(--svg-color--ce9087, #CE9087);
  d: path("m19.044 21.141l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.127-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203a448 448 0 0 1-2.75-3.945c-.613-.9-.167-1.636.133-1.89");
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.i-c5fwbwi {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M15.614 10.111a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.i72xohbjt {
  fill: var(--svg-color--dfa690, #DFA690);
  d: path("m16.629 10.158l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.ijp7u7nkv {
  d: path("M22.16 9.618c.278-.875.951-1.815 1.212-2.188l2.898 1.867l-.593 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.itkv95dhm {
  fill: var(--svg-color--9f97a9, #9F97A9);
  d: path("m20.942 16.57l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.j-c4i6bgu {
  stop-color: var(--svg-color--5e598c, #5E598C);
  stop-opacity: 0;
}

.j0vrx6bvn {
  d: path("M2.205 30.141v-8.953l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.113 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.556l5 4.753z");
}

.j4m0po66p {
  d: path("M20.333 7.07c.003.395-.166.71-.25.817l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.jbbp6_bdq {
  stop-color: var(--svg-color--716170, #716170);
  stop-opacity: 0;
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jsbpk9bkc {
  d: path("M14.652 14.876L2.205 19.238V2.196H18.15c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.ju80-yb6q {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m11.989 20.2l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k6thccsxs {
  d: path("m21.369 15.18l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kao1--wwn {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
}

.kjuj_ebnl {
  stop-color: var(--svg-color--e7bca0, #E7BCA0);
}

.kqp9fdbzy {
  stop-color: var(--svg-color--e8bb9d, #E8BB9D);
  stop-opacity: 0;
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.l-wqt88hf {
  stop-color: var(--svg-color--6d4e68, #6D4E68);
  stop-opacity: 0;
}

.l7gu2-m-u {
  fill: var(--svg-color--dfa68f, #DFA68F);
  fill-rule: evenodd;
  d: path("m18.113 14.385l-2.655-2.435l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.423l.433 1.696l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.md1x-bb_r {
  fill-rule: evenodd;
  d: path("M20.92 15.938a.25.25 0 0 1 .342-.092l3.629 2.09a.25.25 0 1 1-.25.433l-3.628-2.09a.25.25 0 0 1-.092-.34");
}

.mg4rwjbbx {
  stop-color: var(--svg-color--8a6dc0, #8A6DC0);
  stop-opacity: 0;
}

.mg4s00w7b {
  fill: var(--svg-color--dfb491, #DFB491);
  d: path("M20.333 7.07c.003.395-.166.71-.25.817l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
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

.n8-sscbcs {
  d: path("M19.135 2.196v9.588c0 .132.027.263.079.384l1.706 3.989l.42.137c.05.114.166.978.28.929a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V2.196z");
}

.njdjvcttb {
  stop-color: var(--svg-color--ae9ea8, #AE9EA8);
}

.nk-mbmbtk {
  stop-color: var(--svg-color--e5a08a, #E5A08A);
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

.o1-p4ybsa {
  fill: var(--svg-color--544583, #544583);
  d: path("m22.889 26.345l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.ob13unr5n {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M14.89 10.857a.28.28 0 0 1 .367-.42l1.5 1.31l-.368.42z");
}

.ojet8cb1m {
  stop-color: var(--svg-color--4c3384, #4C3384);
}

.olalv5p_g {
  fill: var(--svg-color--1b131c, #1B131C);
  d: path("M24.234 8.527a.7.7 0 0 0-.223-.45c-.009.272-.167.4-.094.515c.096.15.33.117.317-.065");
}

.om1zr9boo {
  stop-color: var(--svg-color--f0bea1, #F0BEA1);
  stop-opacity: 0;
}

.os32btykc {
  stop-color: var(--svg-color--66619b, #66619B);
}

.p-qyixqwk {
  fill-rule: evenodd;
  d: path("M24.524 18.105c.11 0 .2.09.2.2v.883a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
}

.p2417ob0x {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
  stop-opacity: 0;
}

.p62i0qb1k {
  stop-color: var(--svg-color--cc9778, #CC9778);
}

.p9woy_1wh {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.653 7.946c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pbgm9vhci {
  stop-color: var(--svg-color--dca888, #DCA888);
  stop-opacity: 0;
}

.pcd65pbuz {
  stop-color: var(--svg-color--7753a0, #7753A0);
}

.pids_pbns {
  stop-color: var(--svg-color--948f8f, #948F8F);
}

.pktfr7bne {
  stop-color: var(--svg-color--d28f83, #D28F83);
}

.pl76o5b_i {
  stop-color: var(--svg-color--af6c57, #AF6C57);
}

.ps4wek9uf {
  stop-color: var(--svg-color--4a4476, #4A4476);
  stop-opacity: 0;
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.qo07u2b9p {
  d: path("M14.89 10.857a.28.28 0 0 1 .367-.42l1.5 1.31l-.368.42z");
}

.r_5s-tw4v {
  stop-color: var(--svg-color--e8bb9d, #E8BB9D);
}

.r004zbc7a {
  d: path("M22.301 8.43c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.r1g9oggar {
  stop-color: var(--svg-color--d9a288, #D9A288);
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

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.rnnzvvb9z {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.521 8.434l.053-.07c.073-.12.081-.25.018-.288c-.062-.038-.173.028-.246.148l-.035.071z");
}

.s0mn5z5qq {
  d: path("m26.96 10.202l-3.63-2.696a.22.22 0 0 1-.067-.288a4.8 4.8 0 0 1 .654-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
}

.s4ygnfbfl {
  stop-color: var(--svg-color--7850b4, #7850B4);
  stop-opacity: 0;
}

.sc-4z3bze {
  stop-color: var(--svg-color--634b8b, #634B8B);
  stop-opacity: 0;
}

.sc7rv5bwb {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("m16.629 10.158l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.sf7z4ybcf {
  stop-color: var(--svg-color--d1cfd2, #D1CFD2);
  stop-opacity: 0;
}

.shmkg3ete {
  stop-color: var(--svg-color--7a7996, #7A7996);
}

.sjt__ehso {
  stroke: var(--svg-color--e9b397, #E9B397);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.627 11.232l2.562 2.437");
}

.smv_aqb3z {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M15.041 10.342a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
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

.tk_a4ibow {
  d: path("m24.496 10.741l.445-1.156l.508-.758l1.672 1.32c-.052.086-.136.373-.055.829c.102.57-.14.968-.273 1.156s-.813.883-1.758.258c-.756-.5-.675-1.308-.54-1.649");
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

.u005aj31u {
  stop-color: var(--svg-color--9480c2, #9480C2);
}

.ufi1sccsl {
  stop-color: var(--svg-color--bd7475, #BD7475);
}

.uskwimbnj {
  d: path("M14.814 11.39a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
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

.v6skbb3bx {
  d: path("M24.96 7.584a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.368.479l-.984-.758a.3.3 0 0 1-.055-.423");
}

.v8ombmbjb {
  stop-color: var(--svg-color--d9a288, #D9A288);
}

.vd0w6m1tw {
  fill-rule: evenodd;
  d: path("M24.335 19.154a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
}

.vp6yj4xxl {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
}

.vps27w8pe {
  stop-color: var(--svg-color--413b69, #413B69);
  stop-opacity: 0;
}

.w5vd7udwg {
  stop-color: var(--svg-color--908790, #908790);
  stop-opacity: 0;
}

.w6qb8tbjg {
  cx: 25.297px;
  cy: 9.487px;
  r: 0.559px;
}

.w7bim1b_c {
  fill-rule: evenodd;
  d: path("M23.513 13.956c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.341c.33 2.085 1.175 4.09 4.47 5.869z");
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.waoqorb7a {
  d: path("M15.041 10.342a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.wlyubdb4v {
  stop-color: var(--svg-color--d6d4d7, #D6D4D7);
}

.ws0t5un5c {
  stop-color: var(--svg-color--816878, #816878);
}

.wxl7pfshq {
  stop-color: var(--svg-color--a46f70, #A46F70);
}

.x--zxyb9a {
  d: path("M13.789 2.152c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
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

.x8-nb-ihc {
  stop-color: var(--svg-color--cf9388, #CF9388);
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xcafsktgp {
  stop-color: var(--svg-color--8e6bb9, #8E6BB9);
}

.xgvx5wb1m {
  stop-color: var(--svg-color--d28f83, #D28F83);
  stop-opacity: 0;
}

.xzhs54baa {
  stop-color: var(--svg-color--948f8f, #948F8F);
  stop-opacity: 0;
}

.y7qyzyb5d {
  d: path("M20.944 16.566c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014c-.906-.21-1.484-.406-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

.y98a87uix {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.415 7.99c.07.492.482 1.784 1.58 3.02");
}

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.yc4gimbqr {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.205 23.196v6.945h8.343a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.523c-.065-.141-.186-.451-.371-.924l-.285-.725c-.322-.816-.953-1.219-1.437-1.422z");
}

.ycpxb2wjj {
  stop-color: var(--svg-color--412949, #412949);
}

.yelz-umev {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M14.814 11.39a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.yjh8oi0bq {
  stop-color: var(--svg-color--9e83ce, #9E83CE);
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.yp3ph2bir {
  stop-color: var(--svg-color--765890, #765890);
  stop-opacity: 0;
}

.z4spfobgt {
  d: path("M9.44 17.135a.93.93 0 0 1 .457-.698l-7.692 2.651v2.661c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zdly7i1an {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.563 8.636a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32L25.21 8.67a.25.25 0 0 1 .352-.033");
}

.zf_mfmbxn {
  fill-rule: evenodd;
  d: path("M25.563 8.636a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32L25.21 8.67a.25.25 0 0 1 .352-.033");
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

.zrjrssbvc {
  d: path("m18.274 15.551l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

</style>
