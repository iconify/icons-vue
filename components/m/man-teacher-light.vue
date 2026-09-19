<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iRNuXde)"><path fill="url(#iHZpQKe)" class="jli53cv-u"/></g><path fill="url(#iSnOUoc)" class="zraeqozoi"/><path fill="url(#itKpcGd)" class="zraeqozoi"/><path fill="url(#iRfwUve)" class="zraeqozoi"/><g filter="url(#iBhayqd)"><path stroke="url(#iBOyX6c)" class="goh858bdb"/></g><g filter="url(#ia2Y9Fb)"><path fill="url(#ikVwmKa)" class="nh1as9b4q"/><path fill="url(#iBHd7id)" class="nh1as9b4q"/><path fill="url(#iezhsbc)" class="nh1as9b4q"/></g><path fill="url(#i3h4ZXb)" class="tq_mie6fm"/><path fill="url(#iQFhhEA)" class="tq_mie6fm"/><path fill="url(#iB5tvPd)" class="tq_mie6fm"/><path fill="url(#i5ueHne)" class="rm1wsmb1x"/><path fill="url(#imfWJXd)" class="rm1wsmb1x"/><path fill="url(#iD7gVxb)" class="rm1wsmb1x"/><path fill="url(#iHYiFXW)" class="jj6lcwb9y"/><path fill="url(#iQ9wOYb)" class="jj6lcwb9y"/><path fill="url(#iHFfVJb)" class="zc7-gzpvh"/><g filter="url(#is8oqFd)"><path fill="url(#iyTCnEe)" class="de42tiuik"/><path fill="url(#itDd3ne)" class="de42tiuik"/><path fill="url(#iOHdnHb)" class="de42tiuik"/><path fill="url(#ihSkxmc)" class="de42tiuik"/></g><g filter="url(#iquM5ge)"><path fill="url(#iqVXOvd)" class="epi--hb-k"/><path fill="url(#ik74l0d)" class="epi--hb-k"/><path fill="url(#iAM72pc)" class="epi--hb-k"/><path fill="url(#i7SDynb)" class="epi--hb-k"/></g><path fill="url(#i0AkxuM)" class="kjgqvmbzk"/><g filter="url(#iu4FDvc)"><path fill="url(#iuUNJup)" class="wbvf9_b5o"/><path fill="url(#it1Kdie)" class="wbvf9_b5o"/></g><g filter="url(#icTIMAz)"><path fill="url(#iyr8fze)" class="x_sjfxb1s"/></g><path fill="url(#ik3PP3c)" class="houzovuhv"/><path clip-rule="evenodd" class="pp-mi7b-u"/><path fill="url(#iSj9EAb)" clip-rule="evenodd" class="qr4-l_b8g"/><g filter="url(#ilBqVdd)"><path fill="url(#iKS5LKe)" class="jbixw0b2w"/><path fill="url(#iBd1ftN)" class="jbixw0b2w"/><path fill="url(#iUZi4gc)" class="jbixw0b2w"/><path fill="url(#iF7XL4b)" class="jbixw0b2w"/><path fill="url(#i2JBwpp)" class="jbixw0b2w"/><path fill="url(#iZZVJFd)" class="jbixw0b2w"/></g><g filter="url(#iengYid)"><path fill="url(#ih0p7Vc)" class="oggavrtaz"/><path fill="url(#il14EZc)" class="oggavrtaz"/><path fill="url(#iDOtOWb)" class="oggavrtaz"/><path fill="url(#idfxEpk)" class="oggavrtaz"/><path fill="url(#igQhMbc)" class="oggavrtaz"/></g><path fill="url(#iymLEtc)" class="yt272mvqf"/><path fill="url(#inBeqkb)" class="ziwnmubsl"/><g filter="url(#ijILXUc)"><path stroke="url(#imjcyhe)" class="hxjkjvf3k"/></g><g filter="url(#iuJoXCb)"><path stroke="url(#idRtqHb)" class="cd7t-qb8m"/></g><g filter="url(#iRW5NLc)"><path stroke="url(#iFrptqc)" class="g63ig_4bx"/></g><g filter="url(#if7QTqd)"><path stroke="url(#i7Yvvxb)" class="ytldnib7g"/></g><g filter="url(#iVn6yOd)"><path stroke="url(#iFyFAde)" class="tiafd6tjw"/></g><g filter="url(#iG3cD6g)"><path stroke="url(#itJmOgd)" class="k4i9h32su"/></g><g filter="url(#iyIAINh)"><circle fill="url(#iz3v4de)" class="yvqshxbik"/></g><g filter="url(#iSY9Mxb)"><circle fill="url(#iYC5Uqi)" class="pmldncclv"/></g><g filter="url(#i3pzZCc)"><circle fill="url(#iL2UgTb)" class="ctg-lub6r"/><circle fill="url(#iybytUc)" class="ctg-lub6r"/></g><g filter="url(#iSmN5xc)"><circle class="zmwu6mbqg"/><circle fill="url(#iRUNgib)" class="g854kabda"/><circle fill="url(#iBWK7nd)" class="g854kabda"/></g><g filter="url(#iezeZWb)"><path fill="url(#iDQJRmd)" class="zz-58sbun"/><path fill="url(#i6GIdDc)" class="zz-58sbun"/><path fill="url(#iMgZWJd)" class="zz-58sbun"/><path fill="url(#iVqs95c)" class="zz-58sbun"/><path fill="url(#imoUl1b)" class="zz-58sbun"/><path fill="url(#iUsegKW)" class="zz-58sbun"/></g><g filter="url(#inSwmNc)"><path fill="url(#iFYVrPb)" class="bhm9ywbab"/></g><g filter="url(#iVqATCj)"><path class="qg8dsh4bf"/><path fill="url(#iwLgnwd)" class="vz047_h_m"/><path fill="url(#int86tb)" class="vz047_h_m"/><path fill="url(#iaY63id)" class="vz047_h_m"/><path fill="url(#iIcBz9c)" class="vz047_h_m"/></g><g filter="url(#iclSckD)"><path class="o9voltb9h"/></g><g filter="url(#iapF9Ce)"><path class="sak67t5wm"/><path fill="url(#iJbTTNe)" class="eg76w5baj"/><path fill="url(#iHpfkec)" class="eg76w5baj"/><path fill="url(#iIPODUS)" class="eg76w5baj"/><path fill="url(#i8sTueb)" class="eg76w5baj"/></g><path fill="url(#iKLu3jd)" class="eg76w5baj"/><path stroke="url(#ihm1pDq)" class="gfbzderpa"/><g filter="url(#iWLAgFb)"><path class="kx45vnk8d"/></g><g filter="url(#ikYDPid)"><path class="m1kw5mb4s"/></g><path class="k444mub1v"/><path fill="url(#i3eUIvd)" class="gt7_12abh"/><path class="s56mnnbws"/><g filter="url(#irtR9hi)"><path class="mm7rn7bmr"/><path fill="url(#iFmt9Dc)" class="n_8430l9b"/></g><g filter="url(#isicvDd)"><path fill="url(#iwWkhyb)" class="irym0bcji"/></g><path class="wz43c4bnm"/><path fill="url(#iFuZQAi)" class="mp-cl2b8g"/><path class="pg9f95rjo"/><g filter="url(#iZghrnc)"><path fill="url(#iOS1lYY)" class="cqeohebjt"/></g><g filter="url(#iBWZ0Ne)"><ellipse transform="rotate(-27.914 13.635 10.063)" class="v8rrm3b3d"/><ellipse fill="url(#i71Fhce)" transform="rotate(-27.914 13.635 10.063)" class="wnm_28gyh"/></g><g filter="url(#iQ9Eabc)"><path stroke="url(#iqtA4zd)" class="mp4ps3ipx"/></g><g filter="url(#iaGeZjb)"><path stroke="url(#izrAGkc)" class="oq7d04nrf"/></g><g filter="url(#ieW1WYd)"><path stroke="url(#ixSBtHe)" class="bi5logplh"/></g><g filter="url(#i7mLase)"><path fill="url(#iBfDxWb)" class="p70_6ubgi"/><path fill="url(#iVYRkKc)" class="p70_6ubgi"/></g><defs><radialGradient id="itKpcGd" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.062 6.894)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="iRfwUve" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.582 25.494)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="iezhsbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.024 4.33)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="i3h4ZXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.02 15.963)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="iQFhhEA" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.676 20.494)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iB5tvPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.738 19.088)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="i5ueHne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.014 28.244)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="iQ9wOYb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.478 29.793)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="iHFfVJb" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.207 20.307)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="itDd3ne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.25 19.454)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="iOHdnHb" cx="0" cy="0" r="1" gradientTransform="rotate(-125.283 15.14 5.137)scale(1.63656 .29806)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="ihSkxmc" cx="0" cy="0" r="1" gradientTransform="rotate(69.677 -2.845 21.16)scale(.94974 1.77776)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="ik74l0d" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.535 20.37)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="i7SDynb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 1 -1.87182 -.87742 14.05 16.479)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="i0AkxuM" cx="0" cy="0" r="1" gradientTransform="scale(2.05629 2.81101)rotate(90 .83 6.964)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="g67o2_phx"/><stop offset="1" class="nnb3_mk0j"/></radialGradient><radialGradient id="iuUNJup" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.656 23.781)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="p4dnf-6nl"/><stop offset="1" class="hi3h5mb3p"/></radialGradient><radialGradient id="it1Kdie" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.798 23.5)" gradientUnits="userSpaceOnUse"><stop class="rcibyxbcc"/><stop offset="1" class="xcsexhsni"/></radialGradient><radialGradient id="iyr8fze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.113 24.023)" gradientUnits="userSpaceOnUse"><stop class="esia20bko"/><stop offset="1" class="pycm_h7mj"/></radialGradient><radialGradient id="iBd1ftN" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.207 25.375)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="iUZi4gc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.223 26.656)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="iF7XL4b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.27 27.937)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="i2JBwpp" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.34 29.297)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="il14EZc" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.27 25.375)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="iDOtOWb" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.207 26.656)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="idfxEpk" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.113 27.937)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="igQhMbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.973 29.297)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="iz3v4de" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07077 9.673 10.84)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iybytUc" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.227 10.576)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iRUNgib" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.814 11.662)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iBWK7nd" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.753 30.777)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="i6GIdDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.77035 -11.9053 0 16.119 8.916)" gradientUnits="userSpaceOnUse"><stop offset=".489" class="pg8t7-bob"/><stop offset="1" class="sexbwohhy"/></radialGradient><radialGradient id="imoUl1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.436 9.57)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iUsegKW" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.878 9.536)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iwLgnwd" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.614 -9.973)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="int86tb" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -44.778 207.13)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iaY63id" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 16.09 2.24)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iIcBz9c" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.642 9.057)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="i8sTueb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.417 12.447)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="i3eUIvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.269 10.159)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iFmt9Dc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 18.04 10.243)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFuZQAi" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.906 10.159)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i71Fhce" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.918 -1.515)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVYRkKc" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.395 10.547)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><linearGradient id="iHZpQKe" x1="11.838" x2="31.281" y1="4.619" y2="22.854" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="iSnOUoc" x1="30.082" x2="9.145" y1="13.307" y2="13.307" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="iBOyX6c" x1="13.457" x2="31.27" y1="3.56" y2="24.372" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="ikVwmKa" x1="-4.887" x2="28.926" y1="25.651" y2="25.651" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iBHd7id" x1="3.113" x2="3.113" y1="5.213" y2="23.651" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="imfWJXd" x1="25.193" x2="25.193" y1="30.464" y2="26.647" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="iD7gVxb" x1="22.426" x2="23.238" y1="29.276" y2="29.26" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iHYiFXW" x1="7.154" x2="9.548" y1="28.157" y2="28.157" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="iyTCnEe" x1="18.074" x2="20.87" y1="18.384" y2="18.384" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="iqVXOvd" x1="13.964" x2="11.167" y1="18.384" y2="18.384" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iAM72pc" x1="12.129" x2="12.691" y1="16.948" y2="17.166" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="ik3PP3c" x1="21.863" x2="17.488" y1="24.807" y2="24.807" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="iSj9EAb" x1="10.334" x2="10.762" y1="23.588" y2="23.588" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="iKS5LKe" x1="12.883" x2="8.582" y1="28.026" y2="28.026" gradientUnits="userSpaceOnUse"><stop class="z-u-gxbip"/><stop offset=".716" class="ru_e7vq8a"/></linearGradient><linearGradient id="iZZVJFd" x1="11.082" x2="11.082" y1="30.28" y2="29.202" gradientUnits="userSpaceOnUse"><stop class="qgefhk3_g"/><stop offset="1" class="fz4o7ndqt"/></linearGradient><linearGradient id="ih0p7Vc" x1="22.488" x2="18.674" y1="27.619" y2="27.619" gradientUnits="userSpaceOnUse"><stop class="tug0m0bta"/><stop offset=".807" class="t9hl_kbdf"/></linearGradient><linearGradient id="iymLEtc" x1="10.801" x2="21.674" y1="21.963" y2="21.963" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="inBeqkb" x1="16.42" x2="16.42" y1="21.026" y2="22.198" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="imjcyhe" x1="19.043" x2="20.871" y1="26.127" y2="26.127" gradientUnits="userSpaceOnUse"><stop class="e_ivvgb2p"/><stop offset="1" class="ccj4ms20h"/></linearGradient><linearGradient id="idRtqHb" x1="12.952" x2="10.754" y1="26.127" y2="26.127" gradientUnits="userSpaceOnUse"><stop class="xiz-7cblr"/><stop offset="1" class="n1yz-o_0e"/><stop offset="1" class="d33s3sdpm"/></linearGradient><linearGradient id="iFrptqc" x1="19.043" x2="20.871" y1="27.393" y2="27.393" gradientUnits="userSpaceOnUse"><stop class="e_ivvgb2p"/><stop offset="1" class="ccj4ms20h"/></linearGradient><linearGradient id="i7Yvvxb" x1="12.952" x2="10.754" y1="27.393" y2="27.393" gradientUnits="userSpaceOnUse"><stop class="xiz-7cblr"/><stop offset="1" class="n1yz-o_0e"/><stop offset="1" class="d33s3sdpm"/></linearGradient><linearGradient id="iFyFAde" x1="19.043" x2="20.871" y1="28.658" y2="28.658" gradientUnits="userSpaceOnUse"><stop class="e_ivvgb2p"/><stop offset="1" class="ccj4ms20h"/></linearGradient><linearGradient id="itJmOgd" x1="12.952" x2="10.754" y1="28.658" y2="28.658" gradientUnits="userSpaceOnUse"><stop class="xiz-7cblr"/><stop offset="1" class="n1yz-o_0e"/><stop offset="1" class="d33s3sdpm"/></linearGradient><linearGradient id="iYC5Uqi" x1="11.342" x2="10.702" y1="11.119" y2="11.119" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iL2UgTb" x1="21.941" x2="21.123" y1="9.749" y2="12.285" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iDQJRmd" x1="20.125" x2="12.489" y1="11.23" y2="12.368" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="iMgZWJd" x1="10.448" x2="13.806" y1="12.757" y2="12.871" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iVqs95c" x1="10.694" x2="12.576" y1="13.926" y2="13.859" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iFYVrPb" x1="15.559" x2="23.702" y1="8.245" y2="5.33" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iJbTTNe" x1="15.226" x2="16.164" y1="11.889" y2="11.889" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iHpfkec" x1="17.028" x2="16.003" y1="12.212" y2="12.197" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iIPODUS" x1="16.285" x2="16.285" y1="12.954" y2="12.381" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iKLu3jd" x1="16.216" x2="16.216" y1="12.996" y2="12.828" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="ihm1pDq" x1="15.053" x2="15.488" y1="14.569" y2="13.881" gradientUnits="userSpaceOnUse"><stop class="ve3kg1kud"/><stop offset=".663" class="lt9womo5w"/></linearGradient><linearGradient id="iwWkhyb" x1="19.046" x2="18.733" y1="10.213" y2="10.406" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iOS1lYY" x1="14.65" x2="14.336" y1="10.212" y2="10.406" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqtA4zd" x1="19.062" x2="18.642" y1="8.073" y2="7.214" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="izrAGkc" x1="13.758" x2="12.569" y1="7.945" y2="7.446" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ixSBtHe" x1="11.428" x2="11.428" y1="5.931" y2="8.088" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="iBfDxWb" x1="16.099" x2="16.099" y1="9.443" y2="13.224" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient><filter id="iRNuXde" width="27.98" height="21.09" x="2.024" y="4.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="iBhayqd" width="27.413" height="20.785" x="2.688" y="3.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".2"/></filter><filter id="ia2Y9Fb" width="27.91" height="20.96" x="2.024" y="4.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="is8oqFd" width="2.797" height="14.04" x="18.074" y="15.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="iquM5ge" width="2.797" height="14.04" x="11.167" y="15.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="iu4FDvc" width="2.1" height="3.39" x="20.967" y="23.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.803922 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="icTIMAz" width="2.1" height="3.29" x="8.97" y="23.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.670588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="ilBqVdd" width="4.793" height="5.391" x="8.97" y="24.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.670588 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="iengYid" width="4.793" height="5.591" x="18.474" y="24.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.490196 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.796078 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1669" result="effect2_innerShadow_4002_1669"/></filter><filter id="ijILXUc" width="2.222" height=".3" x="18.893" y="25.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".05"/></filter><filter id="iuJoXCb" width="2.222" height=".3" x="10.88" y="25.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".05"/></filter><filter id="iRW5NLc" width="2.222" height=".3" x="18.893" y="27.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".05"/></filter><filter id="if7QTqd" width="2.222" height=".3" x="10.88" y="27.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".05"/></filter><filter id="iVn6yOd" width="2.222" height=".3" x="18.893" y="28.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".05"/></filter><filter id="iG3cD6g" width="2.222" height=".3" x="10.88" y="28.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".05"/></filter><filter id="iyIAINh" width="3.539" height="3.339" x="9.673" y="9.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="iSY9Mxb" width="2.99" height="2.99" x="9.848" y="9.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".25"/></filter><filter id="i3pzZCc" width="3.589" height="3.589" x="19.186" y="8.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="iSmN5xc" width="2.99" height="2.99" x="19.36" y="9.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".25"/></filter><filter id="iezeZWb" width="10.373" height="12.277" x="10.932" y="5.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="inSwmNc" width="8.246" height="7.066" x="14.26" y="3.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation="1"/></filter><filter id="iVqATCj" width="12.601" height="8.543" x="9.79" y="1.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="iclSckD" width="3.26" height="4.181" x="14.221" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".375"/></filter><filter id="iapF9Ce" width="2.377" height="3.181" x="14.902" y="10.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".125"/></filter><filter id="iWLAgFb" width="2.979" height="1.873" x="17.272" y="7.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="ikYDPid" width="2.98" height="1.873" x="12.125" y="7.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/></filter><filter id="irtR9hi" width=".787" height=".696" x="17.535" y="9.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".05"/></filter><filter id="isicvDd" width=".891" height=".913" x="18.374" y="9.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".1"/></filter><filter id="iZghrnc" width=".986" height="1.04" x="13.933" y="9.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".1"/></filter><filter id="iBWZ0Ne" width=".913" height=".704" x="13.178" y="9.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".05"/></filter><filter id="iQ9Eabc" width="3.099" height="1.681" x="17.125" y="7.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".25"/></filter><filter id="iaGeZjb" width="3.177" height="1.738" x="11.906" y="7.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".25"/></filter><filter id="ieW1WYd" width="1.008" height="2.269" x="10.924" y="5.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1669" stdDeviation=".125"/></filter><filter id="i7mLase" width="10.29" height="4.16" x="10.904" y="8.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1669"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1669" result="effect2_innerShadow_4002_1669"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-teacher-light" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a1g7dradx {
  stop-color: var(--svg-color--f2c6bb, #F2C6BB);
  stop-opacity: 0;
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avo9uebvh {
  stop-color: var(--svg-color--544b50, #544B50);
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bhm9ywbab {
  d: path("m20.053 5.217l-3.077 1.025a1.047 1.047 0 0 0 .47 2.032l3.06-.41z");
}

.bi5logplh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.558 6.03v.897c-.008.149-.07.481-.259.622");
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

.ccj4ms20h {
  stop-color: var(--svg-color--b6736c, #B6736C);
  stop-opacity: 0;
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cd7t-qb8m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 26.05H11.03");
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqeohebjt {
  d: path("M14.72 10.469c0-.288-.235-.48-.299-.539l-.288.28l.177.36z");
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.ctg-lub6r {
  cx: 20.855px;
  cy: 10.841px;
  r: 1.669px;
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d33s3sdpm {
  stop-color: var(--svg-color--e4af9d, #E4AF9D);
  stop-opacity: 0;
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.de42tiuik {
  d: path("m19.364 16.07l1.36 2.928c.09.19-.05.41-.26.41l-.964-.265c-.422-.105-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V16.07z");
}

.djg-vfjkd {
  stop-color: var(--svg-color--ffd6c4, #FFD6C4);
}

.e_ivvgb2p {
  stop-color: var(--svg-color--b6736c, #B6736C);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.eg76w5baj {
  d: path("m15.708 10.555l-.531 1.7a.538.538 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.115-.376-.646-.376-.765 0");
}

.epi--hb-k {
  d: path("m12.674 16.07l-1.36 2.928c-.09.19.05.41.26.41l.963-.265c.422-.105.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V16.07z");
}

.esia20bko {
  stop-color: var(--svg-color--b88165, #B88165);
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fz4o7ndqt {
  stop-color: var(--svg-color--c38792, #C38792);
  stop-opacity: 0;
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g63ig_4bx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 27.315h1.922");
}

.g67o2_phx {
  stop-color: var(--svg-color--a87366, #A87366);
}

.g854kabda {
  cx: 20.855px;
  cy: 10.841px;
  r: 0.995px;
}

.gfbzderpa {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.728 13.597a2.94 2.94 0 0 0 1.362.323c.505 0 .968-.117 1.362-.323a.2.2 0 0 1 .242.04c.057.06.078.155.02.241m-2.986-.28l2.945.253m-2.945-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.254m3.207.027l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.868c-.682 0-1.28-.347-1.624-.867m3.207-.028a1.9 1.9 0 0 1-1.583.845a1.9 1.9 0 0 1-1.583-.845m-.041.028l.041-.028m-.041.028l.041-.028");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.goh858bdb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.238 4.403h26.213a.1.1 0 0 1 .1.1v19.585");
}

.gt7_12abh {
  d: path("M18.27 9.682a.892.892 0 0 1 .86 1.127h-1.723a.896.896 0 0 1 .864-1.127");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hi3h5mb3p {
  stop-color: var(--svg-color--dda88b, #DDA88B);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.houzovuhv {
  d: path("M10.334 21.89v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hxjkjvf3k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 26.05h1.922");
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.irym0bcji {
  d: path("M19.065 10.457a.84.84 0 0 0-.23-.463l-.26.285l.117.228z");
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jbixw0b2w {
  d: path("M13.363 25.38a.81.81 0 0 1-.302.667a.8.8 0 0 1 .302.636a.77.77 0 0 1-.302.637a.8.8 0 0 1 .302.636a.77.77 0 0 1-.302.637c.187.144.302.39.302.668c-.009.42-.32.749-.685.749H9.744c-.427 0-.774-.4-.774-.893v-3.604c0-.493.347-.894.774-.894h2.842c.475 0 .77.39.777.76");
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jj6lcwb9y {
  d: path("M9.314 30.01V17.765a10.98 10.98 0 0 0-4.32 8.745v3.5z");
}

.jli53cv-u {
  d: path("M29.394 25H2.644c-.34 0-.62-.28-.62-.62V4.63c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jtdjejbjn {
  stop-color: var(--svg-color--ffd6c4, #FFD6C4);
  stop-opacity: 0;
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k444mub1v {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.478 9.41c.652 0 1.204.45 1.354 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.37-1.127");
}

.k4i9h32su {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 28.58H11.03");
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kjgqvmbzk {
  d: path("M16.024 18.68c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.kx45vnk8d {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M19.81 8.12h-.002l-.002-.002l-.004-.003l-.012-.01a1.4 1.4 0 0 0-.155-.107a2.6 2.6 0 0 0-.42-.211a2.83 2.83 0 0 0-1.492-.158a.534.534 0 0 0 .166 1.054c.398-.063.716.01.934.096a1.5 1.5 0 0 1 .308.166a.534.534 0 0 0 .678-.824");
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.lt9womo5w {
  stop-color: var(--svg-color--d7a397, #D7A397);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m1kw5mb4s {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.317 8.121l.002-.002l.005-.003l.012-.01a2 2 0 0 1 .155-.107c.1-.063.24-.14.42-.211a2.83 2.83 0 0 1 1.492-.158a.534.534 0 1 1-.167 1.054a1.77 1.77 0 0 0-.933.096a1.5 1.5 0 0 0-.309.166a.534.534 0 0 1-.678-.824");
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mm7rn7bmr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.205 9.87c.064.085-.07.19-.22.302c-.151.113-.263.192-.327.107s.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.mp-cl2b8g {
  d: path("M13.904 9.682a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.mp4ps3ipx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.75 7.976c.43-.075 1.27-.054 1.85.398");
}

.n_8430l9b {
  d: path("M18.205 9.87c.064.085-.07.19-.22.302c-.151.113-.263.192-.327.107s.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.n1yz-o_0e {
  stop-color: var(--svg-color--d29c80, #D29C80);
  stop-opacity: 0;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.nh1as9b4q {
  d: path("M29.014 24H3.024V5.01l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.nnb3_mk0j {
  stop-color: var(--svg-color--875841, #875841);
}

.o9voltb9h {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.815 10.718l-.82 1.7c-.102.35.142.699.488.699h.737c.345 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.395 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.oggavrtaz {
  d: path("M18.674 25.38a.81.81 0 0 0 .303.667a.8.8 0 0 0-.303.636c0 .267.116.503.303.637a.8.8 0 0 0-.303.636c0 .267.116.504.303.637a.84.84 0 0 0-.303.668c.01.42.32.749.685.749h2.935c.426 0 .773-.4.773-.893v-3.604c0-.493-.347-.894-.773-.894H19.45a.776.776 0 0 0-.777.76");
}

.oq7d04nrf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.531 8.495c.327-.29 1.042-.594 1.927-.453");
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.p4dnf-6nl {
  stop-color: var(--svg-color--e9bda6, #E9BDA6);
}

.p70_6ubgi {
  d: path("M20.854 9.037h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-1.11c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.pg8t7-bob {
  stop-color: var(--svg-color--d19d8f, #D19D8F);
  stop-opacity: 0;
}

.pg9f95rjo {
  fill: var(--svg-color--000, #000);
  d: path("M14.415 10.574a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmldncclv {
  cx: 11.342px;
  cy: 10.841px;
  r: 0.995px;
}

.pn577vz6t {
  stop-color: var(--svg-color--f2c6bb, #F2C6BB);
}

.pp-mi7b-u {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.428 30.01v-8.406h-2.094v8.406z");
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.pycm_h7mj {
  stop-color: var(--svg-color--cd9a86, #CD9A86);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qg8dsh4bf {
  fill: var(--svg-color--242324, #242324);
  d: path("m20.909 4.363l.429.214c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.313-.26.525-.572.533h-.018s.053-.907.107-1.44c.044-.433-.032-.565-.43-.96a1.25 1.25 0 0 1-.374-.853v-.854c0-.266-.215-.48-.43-.533c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.266-3.915.426a.52.52 0 0 0-.43.533v.854c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.747c.054.586.108 1.44.108 1.44l-.05-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.429-.213c.268-.16.536-.373.804-.586l.966-1.014c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.266 1.716-.053 2.36.534l.804.8c.215.266.483.426.805.586");
}

.qgefhk3_g {
  stop-color: var(--svg-color--c38792, #C38792);
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qr4-l_b8g {
  fill-rule: evenodd;
  d: path("M12.428 30.01v-8.406h-2.094v8.406z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.rcibyxbcc {
  stop-color: var(--svg-color--fcd2bc, #FCD2BC);
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rm1wsmb1x {
  d: path("M22.694 30.01V17.765a10.98 10.98 0 0 1 4.32 8.745v3.5z");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.ru_e7vq8a {
  stop-color: var(--svg-color--d4a093, #D4A093);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s56mnnbws {
  fill: var(--svg-color--000, #000);
  d: path("M17.76 10.574c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.sak67t5wm {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.708 10.555l-.531 1.7a.538.538 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.115-.376-.646-.376-.765 0");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sexbwohhy {
  stop-color: var(--svg-color--a76e61, #A76E61);
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.t9hl_kbdf {
  stop-color: var(--svg-color--d19890, #D19890);
}

.tiafd6tjw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 28.58h1.922");
}

.tq_mie6fm {
  d: path("M16.024 15.51c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tug0m0bta {
  stop-color: var(--svg-color--ffd7c3, #FFD7C3);
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.v8rrm3b3d {
  cx: 13.635px;
  cy: 10.063px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.ve3kg1kud {
  stop-color: var(--svg-color--d7a397, #D7A397);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.vz047_h_m {
  d: path("m20.909 4.363l.429.214c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.313-.26.525-.572.533h-.018s.053-.907.107-1.44c.044-.433-.032-.565-.43-.96a1.25 1.25 0 0 1-.374-.853v-.854c0-.266-.215-.48-.43-.533c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.266-3.915.426a.52.52 0 0 0-.43.533v.854c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.747c.054.586.108 1.44.108 1.44l-.05-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.429-.213c.268-.16.536-.373.804-.586l.966-1.014c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.266 1.716-.053 2.36.534l.804.8c.215.266.483.426.805.586");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wbvf9_b5o {
  d: path("M22.067 23.118c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wnm_28gyh {
  cx: 13.635px;
  cy: 10.063px;
  rx: 0.389px;
  ry: 0.197px;
}

.wz43c4bnm {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.697 9.41c-.653 0-1.204.45-1.354 1.058a.274.274 0 0 0 .267.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.x_sjfxb1s {
  d: path("M9.97 23.11c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xcsexhsni {
  stop-color: var(--svg-color--fcd2bc, #FCD2BC);
  stop-opacity: 0;
}

.xiz-7cblr {
  stop-color: var(--svg-color--e4af9d, #E4AF9D);
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yt272mvqf {
  d: path("M21.674 22.995v-2.286c0-.388-.36-.699-.81-.699h-8.659c-1.041 0-1.871.73-1.871 1.622c0 .752.61 1.362 1.363 1.362z");
}

.ytldnib7g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 27.315H11.03");
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.yvqshxbik {
  cx: 11.342px;
  cy: 10.841px;
  r: 1.669px;
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z-u-gxbip {
  stop-color: var(--svg-color--eab9ad, #EAB9AD);
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zc7-gzpvh {
  d: path("M18.074 16.83h-4.11v13.18h4.11z");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.ziwnmubsl {
  d: path("M11.167 21.502c0-.384.311-.695.695-.695h9.812v1.39h-9.812a.695.695 0 0 1-.695-.695");
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zmwu6mbqg {
  cx: 20.855px;
  cy: 10.841px;
  r: 0.995px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zraeqozoi {
  d: path("M3.024 24V5.01h25.99V24z");
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zz-58sbun {
  d: path("M10.932 8.79c0-.267.108-.587.322-.747l.161-.16c.268-.213.376-.533.376-.853v-.854c0-.266.16-.48.429-.533c.643-.16 1.984-.426 3.915-.426c1.93 0 3.272.266 3.915.426c.215.054.43.267.43.533v.854c0 .32.16.64.375.853c.502.352.47.545.429.96c-.054.533-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.002-3.21 3.002h-3.21c-1.712 0-3.05-1.233-3.21-3.002c-.14-1.817-.2-3.638-.367-5.451");
}

</style>
