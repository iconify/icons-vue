<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijK0ZYc)"><path class="ao9v_ib1w"/><path fill="url(#iXrZEFe)" class="haugm6bsg"/></g><path fill="url(#ivqc5Vc)" class="fbhvyb6st"/><path fill="url(#iZcj6sb)" class="fbhvyb6st"/><path fill="url(#ihHiYdd)" class="l99r7fx7y"/><path fill="url(#iFh65bR)" class="l99r7fx7y"/><path fill="url(#ictroZb)" class="i1-qsabbu"/><path fill="url(#iFv7ZAb)" class="i1-qsabbu"/><path fill="url(#ipnAsMd)" class="i1-qsabbu"/><path fill="url(#iv5iesd)" class="i1-qsabbu"/><path fill="url(#iU7QFeb)" class="qikzdjbyp"/><path fill="url(#ieBSRmd)" class="qikzdjbyp"/><path fill="url(#ib3p2Ae)" class="qikzdjbyp"/><path fill="url(#iynvEse)" class="qikzdjbyp"/><path fill="url(#ip9Aodc)" class="qikzdjbyp"/><path fill="url(#i24I8vc)" class="qikzdjbyp"/><path fill="url(#i7OhlHc)" class="ved81pban"/><path fill="url(#i62iSae)" class="gfh00n4vd"/><path fill="url(#iQWAfJe)" class="xtbxq5duj"/><path fill="url(#ijPYblc)" class="f3wkvacjs"/><path fill="url(#i1bt9xc)" class="f3wkvacjs"/><path fill="url(#iuSamud)" class="f3wkvacjs"/><path fill="url(#ihnOxje)" class="f3wkvacjs"/><path fill="url(#ibZSbsb)" class="uge15129f"/><path fill="url(#i0eToyd)" class="uge15129f"/><path fill="url(#iKzl1fw)" class="khxs02b6y"/><path fill="url(#iVqUqUc)" class="khxs02b6y"/><path fill="url(#i4CdQNd)" class="khxs02b6y"/><path fill="url(#i9Qkgub)" class="khxs02b6y"/><g filter="url(#ip7aznc)"><path fill="url(#i9A9oce)" class="xwpvxmbgh"/><path fill="url(#iOnFX1c)" class="xwpvxmbgh"/><path fill="url(#iZKwIld)" class="xwpvxmbgh"/></g><path fill="url(#iLCjjqS)" class="lj32lct6b"/><path fill="url(#iWGG2sb)" class="lj32lct6b"/><path fill="url(#i1dhwpb)" class="lj32lct6b"/><g filter="url(#ipZfOIc)"><path fill="url(#ijDJpXb)" class="x6myoqb7i"/></g><g filter="url(#iPAFJDc)"><circle fill="url(#iRQCDBM)" class="qr-_elu4a"/></g><g filter="url(#ifg1hGd)"><circle fill="url(#iaXB1ZI)" class="mfw0klb6w"/></g><g filter="url(#i9oSxVc)"><path fill="url(#iwQcXuc)" class="yu6cb6biv"/><path fill="url(#ioktqJe)" class="yu6cb6biv"/><path fill="url(#ibNcSge)" class="yu6cb6biv"/><path fill="url(#iCN1Z6c)" class="yu6cb6biv"/><path fill="url(#igMNuHc)" class="yu6cb6biv"/></g><g filter="url(#ilJmODc)"><path stroke="url(#iCdpYMM)" class="m_-etovmb"/></g><g filter="url(#iaVjpRY)"><path stroke="url(#iBCTSKd)" class="lhawg_b-g"/></g><g filter="url(#igYAjwE)"><path stroke="url(#ilnzxwb)" class="mn7alob1f"/></g><g filter="url(#ikpIL6c)"><circle fill="url(#iNXW26b)" class="l894vvxes"/></g><g filter="url(#iAI26yd)"><circle fill="url(#imHA78d)" class="gmnzz-ong"/></g><g filter="url(#inBSyOe)"><circle fill="url(#iv8zDab)" class="ukttorshw"/><circle fill="url(#iCF2T7J)" class="ukttorshw"/></g><g filter="url(#iA9IDad)"><circle class="tj_3r_brb"/><circle fill="url(#ipqtvxd)" class="yz3tpg78q"/><circle fill="url(#i33Py6p)" class="yz3tpg78q"/></g><g filter="url(#iv6NdLz)"><path fill="url(#iYEZPdd)" class="i0hl09b2m"/><path fill="url(#irRA07b)" class="i0hl09b2m"/><path fill="url(#iHpwd0c)" class="i0hl09b2m"/><path fill="url(#i75LyqD)" class="i0hl09b2m"/><path fill="url(#iNt8Pdc)" class="i0hl09b2m"/><path fill="url(#iU575Ie)" class="i0hl09b2m"/></g><path fill="url(#iEeZB7c)" class="i0hl09b2m"/><g filter="url(#igMZktb)"><path fill="url(#i7fCQ4b)" class="lpybms5mc"/></g><g filter="url(#ilVjWAb)"><path class="aen5x7b8k"/><path fill="url(#iCUyOgd)" class="xfk0y3ime"/><path fill="url(#iAwqIac)" class="xfk0y3ime"/><path fill="url(#iALvYyd)" class="xfk0y3ime"/><path fill="url(#iDHTxtd)" class="xfk0y3ime"/></g><g filter="url(#iZBbjoe)"><path class="ng0ejzb8n"/></g><g filter="url(#iuhZ57d)"><path class="i0-837b6d"/><path fill="url(#icFIk2b)" class="arw7mga5q"/><path fill="url(#imflKXx)" class="arw7mga5q"/><path fill="url(#iBqZLGd)" class="arw7mga5q"/><path fill="url(#ik8X3Sb)" class="arw7mga5q"/></g><path fill="url(#iyM7nMb)" class="arw7mga5q"/><path fill="url(#is9TmIG)" class="hmf6ejbkj"/><path fill="url(#i0hVx7d)" class="hmf6ejbkj"/><path stroke="url(#iHGcQmc)" class="yr1859r8h"/><g filter="url(#iT20G4b)"><path class="ihb1t9bfx"/></g><g filter="url(#i8cb0rc)"><path class="qk4k87bcx"/></g><path class="wu02gccan"/><path fill="url(#iDAeGFI)" class="fh82i2npv"/><path class="x85pfg-xp"/><g filter="url(#imOFm0b)"><path class="zrbup-xrj"/><path fill="url(#iNZ4SQb)" class="eqf4f3bwg"/></g><g filter="url(#isVEW9c)"><path fill="url(#ibsnaZy)" class="rrcmywbio"/></g><path class="t879hhm6v"/><path fill="url(#im2kydg)" class="rl3444x7a"/><path class="n-zrsq1ye"/><g filter="url(#iR5XYDN)"><path fill="url(#i72nE1d)" class="ublps9bzm"/></g><g filter="url(#ii4zpgb)"><ellipse transform="rotate(-27.914 12.631 11.582)" class="c79qzxbom"/><ellipse fill="url(#idl5PQq)" transform="rotate(-27.914 12.631 11.582)" class="ylcbsob5v"/></g><g filter="url(#iGML5wc)"><path stroke="url(#iaY7g8d)" class="emwebgbmi"/></g><g filter="url(#inQCZSb)"><path stroke="url(#ijJllBc)" class="bchk33flk"/></g><g filter="url(#ixPpJlx)"><path stroke="url(#ij3amgb)" class="yoh3s7tvl"/></g><defs><radialGradient id="ivqc5Vc" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.84)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="ihHiYdd" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.588 19.66)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="ipnAsMd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.239 18.122)" gradientUnits="userSpaceOnUse"><stop class="m4vk7-mbl"/><stop offset="1" class="esw1hmivn"/></radialGradient><radialGradient id="ieBSRmd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55616 -6.67822 .6506 -.1516 13.25 28.741)" gradientUnits="userSpaceOnUse"><stop class="o4j1rvu5g"/><stop offset="1" class="yp-hr1bpr"/></radialGradient><radialGradient id="i24I8vc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.17874 .81494 -1.02635 -2.74392 12.187 18.007)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="k910dfb4a"/><stop offset="1" class="vm-pj7b0c"/></radialGradient><radialGradient id="ijPYblc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.1 20.491)" gradientUnits="userSpaceOnUse"><stop class="ciisz2bnx"/><stop offset=".766" class="q289q0b5r"/></radialGradient><radialGradient id="i1bt9xc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.106 24.432)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="x9ass5qdk"/><stop offset=".937" class="jzj-p5npf"/></radialGradient><radialGradient id="ihnOxje" cx="0" cy="0" r="1" gradientTransform="matrix(1.32816 -5.1875 .72473 .18555 15.998 25.074)" gradientUnits="userSpaceOnUse"><stop class="uv8l2wb3q"/><stop offset="1" class="gw6xrksmk"/></radialGradient><radialGradient id="ibZSbsb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86746 1.86213 -2.30086 -2.30745 28.446 21.349)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="i0eToyd" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .3353 .44041 28.086 21.589)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="iVqUqUc" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.268 12.194)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="i4CdQNd" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.437)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="i9Qkgub" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.795)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="iOnFX1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 17.186)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="ijDJpXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.981 21.057)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="iRQCDBM" cx="0" cy="0" r="1" gradientTransform="rotate(-118.985 14.14 5.437)scale(1.96318)" gradientUnits="userSpaceOnUse"><stop class="u8i6mckyj"/><stop offset="1" class="gainhdclb"/></radialGradient><radialGradient id="iaXB1ZI" cx="0" cy="0" r="1" gradientTransform="rotate(43.152 -16.065 26.67)scale(2.9724 3.56688)" gradientUnits="userSpaceOnUse"><stop class="bc18wu-1h"/><stop offset=".865" class="m5aoovb9d"/></radialGradient><radialGradient id="ioktqJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.596)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ibNcSge" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 25.015)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iCN1Z6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.385)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="igMNuHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.866)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iNXW26b" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.665 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iCF2T7J" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 28.695 -25.03)scale(1.02361 1.16832)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="ipqtvxd" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 19.817 13.183)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="i33Py6p" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 19.859 12.361)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iHpwd0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 14.77 12.161)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset=".955" class="d0-ni672l"/></radialGradient><radialGradient id="i75LyqD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 17.437 11.088)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iNt8Pdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 12.875 11.055)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iU575Ie" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 10.785 8.11)scale(2.92567 1.71902)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iCUyOgd" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 19.438 8.25)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iAwqIac" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 17.794 6.489)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iALvYyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.089 3.751)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iDHTxtd" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 8.634 10.575)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="ik8X3Sb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 15.416 13.969)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="is9TmIG" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9117 6.52447 -8.23836 -3.67657 14.67 6.98)" gradientUnits="userSpaceOnUse"><stop class="jy25td8rp"/><stop offset="1" class="xftsofb3t"/></radialGradient><radialGradient id="i0hVx7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29688 1.23651 0 13.137 11.449)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="hkf1_jbsj"/><stop offset="1" class="wrhkd7bsy"/></radialGradient><radialGradient id="iDAeGFI" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 17.27 11.678)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iNZ4SQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.041 11.762)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="im2kydg" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 12.903 11.678)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="idl5PQq" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.164 -.261)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iXrZEFe" x1="16.902" x2="15.504" y1="26.362" y2="26.06" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iZcj6sb" x1="7.199" x2="6.027" y1="26.162" y2="26.162" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iFh65bR" x1="23.127" x2="23.77" y1="26.247" y2="26.216" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="ictroZb" x1="22.77" x2="18.395" y1="16.232" y2="28.742" gradientUnits="userSpaceOnUse"><stop class="c08ew-b0i"/><stop offset="1" class="exuz4sbao"/></linearGradient><linearGradient id="iFv7ZAb" x1="16.824" x2="17.53" y1="26.733" y2="26.827" gradientUnits="userSpaceOnUse"><stop class="q5z4iwf2u"/><stop offset="1" class="t7ud1ab5b"/></linearGradient><linearGradient id="iv5iesd" x1="20.787" x2="20.787" y1="16.232" y2="17.331" gradientUnits="userSpaceOnUse"><stop offset=".457" class="tffk3lifv"/><stop offset="1" class="e4yz8gz4u"/></linearGradient><linearGradient id="iU7QFeb" x1="7.895" x2="11.895" y1="17.872" y2="29.122" gradientUnits="userSpaceOnUse"><stop class="m3gjwjbhl"/><stop offset="1" class="c9zswtx-n"/></linearGradient><linearGradient id="ib3p2Ae" x1="8.365" x2="9.063" y1="15.978" y2="19.542" gradientUnits="userSpaceOnUse"><stop class="s434a46or"/><stop offset="1" class="qrv_44bpu"/></linearGradient><linearGradient id="iynvEse" x1="7.895" x2="8.309" y1="22.81" y2="22.606" gradientUnits="userSpaceOnUse"><stop class="bwk0n7bpz"/><stop offset="1" class="oinrtsbml"/></linearGradient><linearGradient id="ip9Aodc" x1="13.739" x2="13.328" y1="28.438" y2="28.524" gradientUnits="userSpaceOnUse"><stop class="ifhx39w3y"/><stop offset="1" class="tmbtljdgb"/></linearGradient><linearGradient id="i7OhlHc" x1="23.395" x2="21.614" y1="26.278" y2="26.278" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="i62iSae" x1="8.114" x2="10.395" y1="28.091" y2="26.934" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="iQWAfJe" x1="15.111" x2="15.111" y1="17.633" y2="28.736" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iuSamud" x1="17.905" x2="16.316" y1="22.339" y2="22.046" gradientUnits="userSpaceOnUse"><stop offset=".061" class="n9lqzvocu"/><stop offset=".066" class="n9lqzvocu"/><stop offset="1" class="komjktb1e"/></linearGradient><linearGradient id="iKzl1fw" x1="25.739" x2="25.739" y1="15.928" y2="19.985" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="i9A9oce" x1="25.934" x2="25.792" y1="16.864" y2="18.068" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="iZKwIld" x1="23.236" x2="23.363" y1="16.801" y2="17.237" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="iLCjjqS" x1="26.936" x2="24.649" y1="21.371" y2="21.371" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="iWGG2sb" x1="24.466" x2="24.847" y1="21.214" y2="21.186" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="i1dhwpb" x1="27.084" x2="26.822" y1="21.085" y2="21.061" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="iwQcXuc" x1="27.996" x2="23.127" y1="26.619" y2="26.619" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iCdpYMM" x1="23.742" x2="25.663" y1="24.416" y2="24.416" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iBCTSKd" x1="23.742" x2="25.663" y1="25.858" y2="25.858" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="ilnzxwb" x1="23.742" x2="25.663" y1="27.288" y2="27.288" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="imHA78d" x1="10.336" x2="9.695" y1="12.64" y2="12.64" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iv8zDab" x1="20.946" x2="20.127" y1="11.268" y2="13.807" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iYEZPdd" x1="19.129" x2="11.485" y1="12.751" y2="13.89" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="irRA07b" x1="9.688" x2="11.955" y1="15.449" y2="15.307" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iEeZB7c" x1="20.086" x2="19.653" y1="13.579" y2="13.548" gradientUnits="userSpaceOnUse"><stop offset=".151" class="lon_-ybsm"/><stop offset="1" class="aqmmdtb6o"/></linearGradient><linearGradient id="i7fCQ4b" x1="16.049" x2="24.674" y1="9.37" y2="6.401" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="icFIk2b" x1="14.224" x2="15.163" y1="13.41" y2="13.41" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="imflKXx" x1="16.028" x2="15.001" y1="13.733" y2="13.719" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iBqZLGd" x1="15.283" x2="15.283" y1="14.476" y2="13.903" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iyM7nMb" x1="15.214" x2="15.214" y1="14.518" y2="14.35" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="iHGcQmc" x1="14.051" x2="14.486" y1="16.093" y2="15.405" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ibsnaZy" x1="18.048" x2="17.734" y1="11.732" y2="11.925" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i72nE1d" x1="13.647" x2="13.333" y1="11.732" y2="11.925" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaY7g8d" x1="18.064" x2="17.643" y1="9.59" y2="8.731" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ijJllBc" x1="12.754" x2="11.564" y1="9.462" y2="8.963" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ij3amgb" x1="10.422" x2="10.422" y1="7.446" y2="9.605" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><filter id="ijK0ZYc" width="5.513" height="4.74" x="12.848" y="23.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2314"/></filter><filter id="ip7aznc" width="6.102" height="1.228" x="22.791" y="16.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2314"/></filter><filter id="ipZfOIc" width="1.075" height="1.075" x="25.198" y="20.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2314"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2314" result="effect2_innerShadow_4002_2314"/></filter><filter id="iPAFJDc" width="5.967" height="5.967" x="12.166" y="15.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".125"/></filter><filter id="ifg1hGd" width="5.813" height="5.813" x="12.243" y="15.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".25"/></filter><filter id="i9oSxVc" width="5.369" height="6.076" x="23.127" y="22.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2314"/></filter><filter id="ilJmODc" width="2.319" height=".3" x="23.592" y="24.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".05"/></filter><filter id="iaVjpRY" width="2.319" height=".3" x="23.592" y="25.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".05"/></filter><filter id="igYAjwE" width="2.319" height=".3" x="23.592" y="27.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".05"/></filter><filter id="ikpIL6c" width="3.542" height="3.342" x="8.665" y="10.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2314"/></filter><filter id="iAI26yd" width="2.992" height="2.992" x="8.841" y="10.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".25"/></filter><filter id="inBSyOe" width="3.592" height="3.592" x="18.188" y="10.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2314"/></filter><filter id="iA9IDad" width="2.992" height="2.992" x="18.363" y="10.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".25"/></filter><filter id="iv6NdLz" width="10.383" height="12.189" x="9.926" y="6.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2314"/></filter><filter id="igMZktb" width="6.25" height="5.07" x="14.259" y="5.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".5"/></filter><filter id="ilVjWAb" width="12.614" height="8.551" x="8.782" y="3.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2314"/></filter><filter id="iZBbjoe" width="3.262" height="4.184" x="13.219" y="11.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".375"/></filter><filter id="iuhZ57d" width="2.379" height="3.184" x="13.899" y="11.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".125"/></filter><filter id="iT20G4b" width="2.982" height="1.874" x="16.272" y="8.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2314"/></filter><filter id="i8cb0rc" width="2.982" height="1.874" x="11.119" y="8.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2314"/></filter><filter id="imOFm0b" width=".787" height=".697" x="16.535" y="11.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".05"/></filter><filter id="isVEW9c" width=".892" height=".914" x="17.376" y="11.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".1"/></filter><filter id="iR5XYDN" width=".987" height="1.041" x="12.93" y="11.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".1"/></filter><filter id="ii4zpgb" width=".914" height=".705" x="12.174" y="11.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".05"/></filter><filter id="iGML5wc" width="2.701" height="1.282" x="16.326" y="9.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".15"/></filter><filter id="inQCZSb" width="2.779" height="1.339" x="11.102" y="9.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".15"/></filter><filter id="ixPpJlx" width="1.008" height="2.271" x="9.918" y="7.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2314" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-singer-dark" /></template>
<style>
.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.aen5x7b8k {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m19.912 5.877l.43.213c.751.374 1.18 1.228 1.02 2.136l-.59 3.043c-.053.314-.261.525-.573.533h-.018s.053-.907.107-1.441c.044-.434-.032-.566-.43-.96c-.214-.214-.375-.535-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.748c.053.587.107 1.441.107 1.441l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.708 1.073-2.082l.43-.213c.268-.16.537-.374.805-.587l.966-1.015c.591-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.363.534l.805.8c.215.267.483.428.805.588");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ao9v_ib1w {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 23.992v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.aqmmdtb6o {
  stop-color: var(--svg-color--533731, #533731);
  stop-opacity: 0;
}

.arw7mga5q {
  d: path("m14.706 12.075l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.378-.646-.378-.765 0");
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.bc18wu-1h {
  stop-color: var(--svg-color--33191c, #33191C);
}

.bchk33flk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.527 10.012c.327-.289 1.042-.594 1.929-.452");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bwk0n7bpz {
  stop-color: var(--svg-color--3e8ed5, #3E8ED5);
}

.c08ew-b0i {
  stop-color: var(--svg-color--2ca9dd, #2CA9DD);
}

.c79qzxbom {
  cx: 12.631px;
  cy: 11.582px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.c9zswtx-n {
  stop-color: var(--svg-color--3073d6, #3073D6);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.ciisz2bnx {
  stop-color: var(--svg-color--472f2e, #472F2E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d0-ni672l {
  stop-color: var(--svg-color--442442, #442442);
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

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4yz8gz4u {
  stop-color: var(--svg-color--2ea1dc, #2EA1DC);
  stop-opacity: 0;
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.emwebgbmi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.751 9.493c.43-.075 1.27-.053 1.851.399");
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.eqf4f3bwg {
  d: path("M17.206 11.39c.064.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.136.389-.05");
}

.esw1hmivn {
  stop-color: var(--svg-color--2796d4, #2796D4);
  stop-opacity: 0;
}

.exuz4sbao {
  stop-color: var(--svg-color--3069c9, #3069C9);
}

.f3wkvacjs {
  d: path("M15.118 16.545c-1.16 0-2.487.209-3.567.58l1.29 6.873c.72.325 1.497.434 2.317.434c.77 0 1.51-.073 2.19-.352l1.313-6.955c-1.05-.383-2.384-.58-3.544-.58");
}

.fbhvyb6st {
  d: path("M7.078 28.732v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fh82i2npv {
  d: path("M17.272 11.2a.893.893 0 0 1 .86 1.13h-1.725a.897.897 0 0 1 .865-1.129");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.gainhdclb {
  stop-color: var(--svg-color--564746, #564746);
  stop-opacity: 0;
}

.gfh00n4vd {
  d: path("M7.078 28.732h3.87l-3.87-7.596z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gmnzz-ong {
  cx: 10.336px;
  cy: 12.361px;
  r: 0.996px;
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.gw6xrksmk {
  stop-color: var(--svg-color--503f3f, #503F3F);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.haugm6bsg {
  d: path("M12.848 23.992v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hkf1_jbsj {
  stop-color: var(--svg-color--be2252, #BE2252);
}

.hmf6ejbkj {
  d: path("M15.052 6.731c-.9.003-1.67.065-2.299.145l-2.11 6.214h1.809l-.508 2.688l3.687-5.133h-1.883z");
}

.i0-837b6d {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m14.706 12.075l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.378-.646-.378-.765 0");
}

.i0hl09b2m {
  d: path("m9.984 11.747l.05.002s-.054-.854-.108-1.441c0-.267.107-.588.322-.748l.161-.16c.269-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.053.429.267.429.534v.854c0 .32.161.64.376.854c.502.352.471.546.43.961a47 47 0 0 0-.108 1.441h.018l-.266 3.963c-.16 1.77-1.553 3.005-3.213 3.005h-3.214c-1.714 0-3.053-1.234-3.213-3.005z");
}

.i1-qsabbu {
  d: path("M24.313 16.746h-5.58l-2.274 11.996h3.149l5.325-11.016a.685.685 0 0 0-.62-.98");
}

.ifhx39w3y {
  stop-color: var(--svg-color--3469bc, #3469BC);
}

.ihb1t9bfx {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m18.812 9.638l-.001-.001l-.002-.002l-.005-.003l-.012-.01l-.036-.027a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.159a.534.534 0 0 0 .167 1.056c.398-.063.717.01.934.096a1.5 1.5 0 0 1 .301.16l.008.006a.534.534 0 0 0 .679-.825");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jy25td8rp {
  stop-color: var(--svg-color--e82d86, #E82D86);
}

.jzj-p5npf {
  stop-color: var(--svg-color--2a1a19, #2A1A19);
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.k910dfb4a {
  stop-color: var(--svg-color--2c649b, #2C649B);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.khxs02b6y {
  d: path("M25.766 19.93a2.498 2.498 0 1 0 0-4.995a2.498 2.498 0 0 0 0 4.996");
}

.komjktb1e {
  stop-color: var(--svg-color--412a29, #412A29);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l894vvxes {
  cx: 10.336px;
  cy: 12.361px;
  r: 1.671px;
}

.l99r7fx7y {
  d: path("M27.017 28.732c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhawg_b-g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.78h2.02");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lj32lct6b {
  d: path("M25.726 26.572a.784.784 0 0 1-.782-.71l-.67-6.429l2.975.01l-.731 6.428a.8.8 0 0 1-.792.701");
}

.lon_-ybsm {
  stop-color: var(--svg-color--5d4947, #5D4947);
}

.lpybms5mc {
  d: path("m19.056 6.731l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_-etovmb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.338h2.02");
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m3gjwjbhl {
  stop-color: var(--svg-color--258ec6, #258EC6);
}

.m4vk7-mbl {
  stop-color: var(--svg-color--40a8ea, #40A8EA);
}

.m5aoovb9d {
  stop-color: var(--svg-color--3a1d23, #3A1D23);
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfw0klb6w {
  cx: 15.15px;
  cy: 17.992px;
  r: 2.406px;
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mn7alob1f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 27.21h2.02");
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n-zrsq1ye {
  fill: var(--svg-color--000, #000);
  d: path("M13.412 12.094a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.235");
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n9lqzvocu {
  stop-color: var(--svg-color--2b1417, #2B1417);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ng0ejzb8n {
  fill: var(--svg-color--332024, #332024);
  d: path("m14.813 12.238l-.821 1.702c-.102.35.142.7.489.7h.738c.346 0 .59-.356.488-.7l-.499-1.702c-.107-.376-.283-.376-.395 0");
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o4j1rvu5g {
  stop-color: var(--svg-color--3778d0, #3778D0);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
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

.oinrtsbml {
  stop-color: var(--svg-color--2a85ce, #2A85CE);
  stop-opacity: 0;
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q289q0b5r {
  stop-color: var(--svg-color--281314, #281314);
}

.q5z4iwf2u {
  stop-color: var(--svg-color--3466b9, #3466B9);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qikzdjbyp {
  d: path("M5.405 16.753h6.086l2.248 11.99h-2.79l-5.88-11.53c-.086-.124-.07-.46.336-.46");
}

.qk4k87bcx {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.312 9.638l.002-.002l.005-.003l.012-.01l.036-.027q.044-.033.119-.08c.1-.063.24-.14.42-.211a2.84 2.84 0 0 1 1.494-.159a.534.534 0 0 1-.167 1.056a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.301.16l-.008.006a.534.534 0 0 1-.68-.825");
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qr-_elu4a {
  cx: 15.149px;
  cy: 17.992px;
  r: 2.734px;
}

.qrv_44bpu {
  stop-color: var(--svg-color--2987cc, #2987CC);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.rl3444x7a {
  d: path("M12.9 11.2a.893.893 0 0 0-.86 1.13h1.725a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.893");
}

.rrcmywbio {
  d: path("M18.067 11.976a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s434a46or {
  stop-color: var(--svg-color--3a90be, #3A90BE);
}

.t7ud1ab5b {
  stop-color: var(--svg-color--3073cd, #3073CD);
  stop-opacity: 0;
}

.t879hhm6v {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.694 10.929c-.654 0-1.206.45-1.357 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.373-1.128");
}

.tffk3lifv {
  stop-color: var(--svg-color--3ca6cf, #3CA6CF);
}

.tj_3r_brb {
  cx: 19.859px;
  cy: 12.361px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.tmbtljdgb {
  stop-color: var(--svg-color--2e7fd1, #2E7FD1);
  stop-opacity: 0;
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.u8i6mckyj {
  stop-color: var(--svg-color--564746, #564746);
}

.ublps9bzm {
  d: path("M13.717 11.989c0-.289-.235-.481-.299-.54l-.288.28l.177.361z");
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.uge15129f {
  d: path("M27.277 21.057c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ukttorshw {
  cx: 19.859px;
  cy: 12.361px;
  r: 1.671px;
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.uv8l2wb3q {
  stop-color: var(--svg-color--503f3f, #503F3F);
}

.ved81pban {
  d: path("M23.128 28.732v-7.268l-3.52 7.268z");
}

.vm-pj7b0c {
  stop-color: var(--svg-color--288acb, #288ACB);
  stop-opacity: 0;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
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

.wu02gccan {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.479 10.929c.653 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x6myoqb7i {
  d: path("M25.736 21.86a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.x85pfg-xp {
  fill: var(--svg-color--000, #000);
  d: path("M16.76 12.094a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.235");
}

.x9ass5qdk {
  stop-color: var(--svg-color--2a1a19, #2A1A19);
  stop-opacity: 0;
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xfk0y3ime {
  d: path("m19.912 5.877l.43.213c.751.374 1.18 1.228 1.02 2.136l-.59 3.043c-.053.314-.261.525-.573.533h-.018s.053-.907.107-1.441c.044-.434-.032-.566-.43-.96c-.214-.214-.375-.535-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.748c.053.587.107 1.441.107 1.441l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.708 1.073-2.082l.43-.213c.268-.16.537-.374.805-.587l.966-1.015c.591-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.363.534l.805.8c.215.267.483.428.805.588");
}

.xftsofb3t {
  stop-color: var(--svg-color--d42552, #D42552);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtbxq5duj {
  d: path("M15.118 17.632c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xwpvxmbgh {
  d: path("m28.214 16.773l-4.844-.02a.57.57 0 0 0-.579.578c0 .325.254.579.579.579l4.844.02a.57.57 0 0 0 .579-.579a.585.585 0 0 0-.58-.578");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ylcbsob5v {
  cx: 12.631px;
  cy: 11.582px;
  rx: 0.39px;
  ry: 0.197px;
}

.yoh3s7tvl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.552 7.545v.898c-.008.15-.07.482-.259.623");
}

.yp-hr1bpr {
  stop-color: var(--svg-color--3778d0, #3778D0);
  stop-opacity: 0;
}

.yr1859r8h {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.725 15.12c.394.206.864.324 1.364.324c.505 0 .97-.118 1.363-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.24m-2.989-.28l2.948.253m-2.948-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.22.253m3.21.028l-.042-.028m.042.028l-.042-.028m.042.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.869m3.21-.028c-.335.508-.919.847-1.584.847s-1.25-.339-1.585-.847m-.041.028l.041-.028m-.041.028l.041-.028");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yu6cb6biv {
  d: path("M23.127 23.619c0-.44.366-.802.817-.802h3.054c.745 0 1.349.588 1.349 1.315v3.514c0 .605-.504 1.096-1.124 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.314.187-.589.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.721a.8.8 0 0 1-.458-.72");
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.yz3tpg78q {
  cx: 19.859px;
  cy: 12.361px;
  r: 0.996px;
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zrbup-xrj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.206 11.39c.064.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.136.389-.05");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
