<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iS306lc)"><path fill="url(#iFcjRfb)" class="rpgn8tomk"/></g><path fill="url(#iaJo67C)" class="ne_510bff"/><path fill="url(#iHF4rFc)" class="ne_510bff"/><path fill="url(#izBU1Od)" class="ne_510bff"/><g filter="url(#isPNZId)"><path stroke="url(#ix2inHp)" class="mvwlpibcd"/></g><g filter="url(#i5r1RBc)"><path fill="url(#iSR6R9c)" class="i7zauacob"/><path fill="url(#id4tsrc)" class="i7zauacob"/><path fill="url(#iUOzHxd)" class="i7zauacob"/></g><path fill="url(#i8bc5sc)" class="c8qtn6b6q"/><path fill="url(#i06S3ze)" class="c8qtn6b6q"/><path fill="url(#i7gZkLb)" class="c8qtn6b6q"/><path fill="url(#ir97Mde)" class="ktrz-63en"/><path fill="url(#iZmFcmb)" class="ktrz-63en"/><path fill="url(#iaIhw6d)" class="ktrz-63en"/><path fill="url(#io1YyHd)" class="o-nhfej7r"/><path fill="url(#iRmFsFS)" class="o-nhfej7r"/><path fill="url(#iVz50Ge)" class="tv63_pb3n"/><g filter="url(#iaZCBfd)"><path fill="url(#iAKQjey)" class="q-p4fcc8x"/><path fill="url(#ijtGVCc)" class="q-p4fcc8x"/><path fill="url(#ivTAbAd)" class="q-p4fcc8x"/><path fill="url(#i20lHve)" class="q-p4fcc8x"/></g><g filter="url(#iljZPst)"><path fill="url(#iv1cHzb)" class="ecx-4mnlf"/><path fill="url(#iq9XJAd)" class="ecx-4mnlf"/><path fill="url(#iV1yX6b)" class="ecx-4mnlf"/><path fill="url(#iWHRKYb)" class="ecx-4mnlf"/></g><path fill="url(#impAl9s)" class="wxe_wdbqk"/><path fill="url(#iHVM7Pc)" class="wsgzsnb4q"/><path fill="url(#irGB22h)" class="qu_s29bvx"/><path fill="url(#id9fxfX)" class="l2gllsb1x"/><path clip-rule="evenodd" class="ujp-b1brq"/><path fill="url(#i4hY6eb)" clip-rule="evenodd" class="b91z8s82l"/><g filter="url(#i3TgOmc)"><path fill="url(#iOxvYXd)" class="i35xvkbct"/></g><g filter="url(#iLPW3Jb)"><path fill="url(#iffNgZb)" class="l27iszgcs"/></g><path fill="url(#ignxcib)" class="zzalbbbun"/><path fill="url(#i2E7PUe)" class="im7b7lz4m"/><g filter="url(#iZGAdkc)"><path stroke="url(#iL63Zub)" class="vg9ose7-a"/></g><g filter="url(#iHs93te)"><path stroke="url(#i0Y2REc)" class="clp58z8vu"/></g><g filter="url(#iOl2bqJ)"><path stroke="url(#iiyluAb)" class="u34g7ww8i"/></g><g filter="url(#i2ECuOH)"><path stroke="url(#ivMTlcD)" class="n6z0avo-m"/></g><g filter="url(#izfiRIc)"><path stroke="url(#iG58tbb)" class="pk1540nca"/></g><g filter="url(#iKZY0de)"><path stroke="url(#i3uQqad)" class="o14v0jbig"/></g><circle fill="url(#iQGrNhe)" class="j5iktke8b"/><g filter="url(#iknovuc)"><circle fill="url(#ivQVmPd)" class="zx1nsdblg"/></g><g filter="url(#irutFrd)"><circle fill="url(#ir1z33b)" class="aig_cxbbh"/><circle fill="url(#i1jx8Pd)" class="aig_cxbbh"/></g><g filter="url(#igRD7sn)"><circle class="lkmljb8mv"/><circle fill="url(#ihPR0Eh)" class="qzei_xb9o"/><circle fill="url(#iBXiP5c)" class="qzei_xb9o"/></g><path fill="url(#iz6D7hc)" class="y6d3gybmz"/><path fill="url(#iToyNGv)" class="y6d3gybmz"/><path fill="url(#iZ5Nffe)" class="y6d3gybmz"/><path fill="url(#iMo2tfc)" class="y6d3gybmz"/><path fill="url(#iiDSj4c)" class="y6d3gybmz"/><g filter="url(#iT83SXb)"><path class="omop9fo5u"/><path fill="url(#iaXYLve)" class="az-vx471y"/><path fill="url(#iPTPbCc)" class="az-vx471y"/><path fill="url(#iUL8x1d)" class="az-vx471y"/><path fill="url(#i2PMUEd)" class="az-vx471y"/><path fill="url(#idLDmab)" class="az-vx471y"/><path fill="url(#iBuimXQ)" class="az-vx471y"/></g><path fill="url(#idlK6Ec)" class="az-vx471y"/><path fill="url(#iRaUCfT)" class="az-vx471y"/><path fill="url(#ixRg8wd)" class="az-vx471y"/><g filter="url(#i0mrpkd)"><path class="x-xufh6qb"/></g><g filter="url(#iPqWWBb)"><path class="ej6rok05i"/><path fill="url(#i0n1qIc)" class="g_rztifly"/><path fill="url(#iUZEZwc)" class="g_rztifly"/><path fill="url(#i9uX4he)" class="g_rztifly"/></g><path fill="url(#iZ0pJeb)" class="g_rztifly"/><g filter="url(#iB1pJlu)"><path stroke="url(#iIGOtez)" class="sahcy-j_t"/></g><path class="fgn4nl1qq"/><path class="xixbuo9hh"/><path fill="url(#ijr2Xab)" class="jya_o6bif"/><path class="m-n20ybmy"/><g filter="url(#ipymU8s)"><path class="uehsdacwh"/><path fill="url(#iVRDzlA)" class="a-j19kb7l"/></g><g filter="url(#iKgqced)"><path fill="url(#iBb5Glb)" class="xum0pqrej"/></g><path class="dkzedu77e"/><path fill="url(#iNCRPVc)" class="y_d5bspca"/><path class="yd1g_ga6o"/><g filter="url(#ivVY6pc)"><path fill="url(#iIxXmie)" class="o-p9b3b0d"/></g><g filter="url(#iNdjH4b)"><ellipse transform="rotate(-27.914 13.632 9.871)" class="uqksp7bth"/><ellipse fill="url(#ioWkjub)" transform="rotate(-27.914 13.632 9.871)" class="sch519bng"/></g><g filter="url(#iFKNbab)"><path fill="url(#imoJbxb)" clip-rule="evenodd" class="e2t276r-s"/></g><g filter="url(#icTuLEe)"><path class="xz35debxn"/></g><g filter="url(#ieTNA2d)"><path fill="url(#inRv2hd)" clip-rule="evenodd" class="l3-9vppbx"/></g><g filter="url(#ivPcZOc)"><path class="bl2fvpbnr"/></g><g filter="url(#iSq8NfA)"><path fill="url(#inrtSfb)" class="ozv89eber"/><path fill="url(#iYgOyme)" class="ozv89eber"/></g><defs><radialGradient id="iHF4rFc" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 26.952 6.835)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="izBU1Od" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.582 25.375)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="iUOzHxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.024 4.21)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="i8bc5sc" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.02 15.844)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="i06S3ze" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.676 20.375)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="i7gZkLb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.738 18.97)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="ir97Mde" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.014 28.125)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="iRmFsFS" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.478 29.674)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="iVz50Ge" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.207 20.188)" gradientUnits="userSpaceOnUse"><stop class="tp0kp63lp"/><stop offset="1" class="ei_98vf4e"/></radialGradient><radialGradient id="ijtGVCc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.25 19.335)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="ivTAbAd" cx="0" cy="0" r="1" gradientTransform="rotate(-125.283 15.109 5.077)scale(1.63656 .29806)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="i20lHve" cx="0" cy="0" r="1" gradientTransform="rotate(69.677 -2.759 21.1)scale(.94974 1.77776)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iq9XJAd" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.535 20.25)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="iWHRKYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 1 -1.87182 -.87742 14.05 16.36)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="impAl9s" cx="0" cy="0" r="1" gradientTransform="scale(2.51976 3.34375)rotate(90 .619 5.74)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="hxpahgbbh"/><stop offset="1" class="dd0k-ab5f"/></radialGradient><radialGradient id="iHVM7Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1 -1.11832 -1.11832 23.067 23.523)" gradientUnits="userSpaceOnUse"><stop class="yomsttbzk"/><stop offset=".814" class="gchclybws"/></radialGradient><radialGradient id="irGB22h" cx="0" cy="0" r="1" gradientTransform="matrix(1.59343 0 0 4.99275 9.082 24.516)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ydne4ly1n"/><stop offset="1" class="h55048b_d"/></radialGradient><radialGradient id="iQGrNhe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.667 10.65)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="i1jx8Pd" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.232 10.384)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="ihPR0Eh" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.819 11.471)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iBXiP5c" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33458 20.86 10.65)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iZ5Nffe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.59375 -9.8125 0 16.581 9.057)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="iMo2tfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.438 9.377)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iiDSj4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.876 9.343)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iaXYLve" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43986 4.43352 -7.5396 -5.84979 19.786 2.93)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iUL8x1d" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 9.17 -1.943)scale(2.00292 .98368)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="i2PMUEd" cx="0" cy="0" r="1" gradientTransform="matrix(.85996 -1.96834 1.60534 .70136 20.32 8.91)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="idLDmab" cx="0" cy="0" r="1" gradientTransform="matrix(.99373 1.23303 -1.08867 .87739 15.314 2.04)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iBuimXQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.45237 -3.03851 1.04984 .50181 20.283 6.426)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="idlK6Ec" cx="0" cy="0" r="1" gradientTransform="matrix(.26142 1.01586 -1.67013 .42978 16.785 2.04)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iRaUCfT" cx="0" cy="0" r="1" gradientTransform="matrix(1.108 1.60044 -3.3305 2.30572 11.704 3.303)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="ixRg8wd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.21429 3.2501 -4.0668 -9.02713 17.244 6.281)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iIGOtez" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 16.005 14.665)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="ijr2Xab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90401 -1.06968 0 18.271 10.3)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iVRDzlA" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18.043 10.051)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNCRPVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90406 -1.06973 0 13.904 10.3)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ioWkjub" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.823 -1.61)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imoJbxb" cx="0" cy="0" r="1" gradientTransform="matrix(.19698 -.81253 1.78256 .43214 18.543 8.448)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="inRv2hd" cx="0" cy="0" r="1" gradientTransform="matrix(-.19698 -.81253 1.78256 -.43214 13.636 8.447)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iYgOyme" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.395 10.383)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><linearGradient id="iFcjRfb" x1="11.838" x2="31.281" y1="4.5" y2="22.735" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="iaJo67C" x1="30.082" x2="9.145" y1="13.188" y2="13.188" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="ix2inHp" x1="13.457" x2="31.27" y1="3.44" y2="24.253" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="iSR6R9c" x1="-4.887" x2="28.926" y1="25.531" y2="25.531" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="id4tsrc" x1="3.113" x2="3.113" y1="5.094" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iZmFcmb" x1="25.193" x2="25.193" y1="30.345" y2="26.528" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="iaIhw6d" x1="22.426" x2="23.238" y1="29.156" y2="29.141" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="io1YyHd" x1="7.154" x2="9.548" y1="28.038" y2="28.038" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="iAKQjey" x1="18.074" x2="20.87" y1="18.265" y2="18.265" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="iv1cHzb" x1="13.964" x2="11.167" y1="18.265" y2="18.265" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iV1yX6b" x1="12.129" x2="12.691" y1="16.828" y2="17.047" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="id9fxfX" x1="21.863" x2="17.488" y1="24.688" y2="24.688" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="i4hY6eb" x1="10.334" x2="10.762" y1="23.469" y2="23.469" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="iOxvYXd" x1="12.52" x2="8.582" y1="27.906" y2="27.906" gradientUnits="userSpaceOnUse"><stop class="dsswvpb9g"/><stop offset="1" class="w9napxb6c"/><stop offset="1" class="wi-1d9bnt"/></linearGradient><linearGradient id="iffNgZb" x1="22.488" x2="18.674" y1="27.5" y2="27.5" gradientUnits="userSpaceOnUse"><stop class="u44n60b3i"/><stop offset="1" class="w9napxb6c"/><stop offset="1" class="g0o1xozbh"/></linearGradient><linearGradient id="ignxcib" x1="10.801" x2="21.674" y1="21.844" y2="21.844" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="i2E7PUe" x1="16.42" x2="16.42" y1="20.906" y2="22.078" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="iL63Zub" x1="19.043" x2="20.871" y1="26.008" y2="26.008" gradientUnits="userSpaceOnUse"><stop class="d2n_fybiv"/><stop offset="1" class="dt611t2tz"/></linearGradient><linearGradient id="i0Y2REc" x1="12.952" x2="10.754" y1="26.008" y2="26.008" gradientUnits="userSpaceOnUse"><stop class="e-u8dsp0m"/><stop offset="1" class="iv0ea6b5j"/></linearGradient><linearGradient id="iiyluAb" x1="19.043" x2="20.871" y1="27.273" y2="27.273" gradientUnits="userSpaceOnUse"><stop class="d2n_fybiv"/><stop offset="1" class="dt611t2tz"/></linearGradient><linearGradient id="ivMTlcD" x1="12.952" x2="10.754" y1="27.273" y2="27.273" gradientUnits="userSpaceOnUse"><stop class="e-u8dsp0m"/><stop offset="1" class="iv0ea6b5j"/></linearGradient><linearGradient id="iG58tbb" x1="19.043" x2="20.871" y1="28.539" y2="28.539" gradientUnits="userSpaceOnUse"><stop class="d2n_fybiv"/><stop offset="1" class="dt611t2tz"/></linearGradient><linearGradient id="i3uQqad" x1="12.952" x2="10.754" y1="28.539" y2="28.539" gradientUnits="userSpaceOnUse"><stop class="e-u8dsp0m"/><stop offset="1" class="iv0ea6b5j"/></linearGradient><linearGradient id="ivQVmPd" x1="11.338" x2="10.696" y1="10.928" y2="10.928" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="ir1z33b" x1="21.947" x2="21.128" y1="9.557" y2="12.095" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iz6D7hc" x1="20.13" x2="12.486" y1="11.039" y2="12.178" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iToyNGv" x1="10.689" x2="13.004" y1="13.738" y2="13.436" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iPTPbCc" x1="11.224" x2="14.129" y1="10.382" y2="5.222" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="i0n1qIc" x1="15.225" x2="16.164" y1="11.699" y2="11.699" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iUZEZwc" x1="17.029" x2="16.003" y1="12.022" y2="12.007" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="i9uX4he" x1="16.285" x2="16.285" y1="12.765" y2="12.191" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iZ0pJeb" x1="16.216" x2="16.216" y1="12.807" y2="12.639" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="iBb5Glb" x1="19.049" x2="18.735" y1="10.021" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIxXmie" x1="14.648" x2="14.334" y1="10.021" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inrtSfb" x1="22.95" x2="16.099" y1="7.258" y2="14.108" gradientUnits="userSpaceOnUse"><stop class="xrqg_7scz"/><stop offset="1" class="nq67yg_fv"/></linearGradient><filter id="iS306lc" width="27.98" height="21.09" x="2.024" y="3.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/></filter><filter id="isPNZId" width="27.413" height="20.785" x="2.688" y="3.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".2"/></filter><filter id="i5r1RBc" width="27.91" height="20.96" x="2.024" y="3.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/></filter><filter id="iaZCBfd" width="2.797" height="14.04" x="18.074" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/></filter><filter id="iljZPst" width="2.797" height="14.04" x="11.167" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/></filter><filter id="i3TgOmc" width="4.593" height="5.591" x="8.97" y="24.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.588235 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/></filter><filter id="iLPW3Jb" width="4.593" height="5.591" x="18.674" y="24.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.458824 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/></filter><filter id="iZGAdkc" width="2.222" height=".3" x="18.893" y="25.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".05"/></filter><filter id="iHs93te" width="2.222" height=".3" x="10.88" y="25.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".05"/></filter><filter id="iOl2bqJ" width="2.222" height=".3" x="18.893" y="27.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".05"/></filter><filter id="i2ECuOH" width="2.222" height=".3" x="10.88" y="27.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".05"/></filter><filter id="izfiRIc" width="2.222" height=".3" x="18.893" y="28.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".05"/></filter><filter id="iKZY0de" width="2.222" height=".3" x="10.88" y="28.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".05"/></filter><filter id="iknovuc" width="2.992" height="2.992" x="9.842" y="9.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".25"/></filter><filter id="irutFrd" width="3.592" height="3.592" x="19.189" y="8.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/></filter><filter id="igRD7sn" width="2.992" height="2.992" x="19.364" y="9.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".25"/></filter><filter id="iT83SXb" width="12.614" height="8.301" x="9.783" y="1.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1654" result="effect2_innerShadow_4002_1654"/></filter><filter id="i0mrpkd" width="3.262" height="4.184" x="14.22" y="9.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".375"/></filter><filter id="iPqWWBb" width="2.379" height="3.184" x="14.901" y="9.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".125"/></filter><filter id="iB1pJlu" width="3.621" height="1.474" x="14.28" y="13.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".05"/></filter><filter id="ipymU8s" width=".787" height=".697" x="17.536" y="9.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".05"/></filter><filter id="iKgqced" width=".892" height=".914" x="18.377" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".1"/></filter><filter id="ivVY6pc" width=".987" height="1.041" x="13.931" y="9.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".1"/></filter><filter id="iNdjH4b" width=".914" height=".705" x="13.175" y="9.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".05"/></filter><filter id="iFKNbab" width="2.604" height="1.648" x="17.355" y="7.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/></filter><filter id="icTuLEe" width="2.709" height="1.502" x="17.302" y="7.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".2"/></filter><filter id="ieTNA2d" width="2.604" height="1.648" x="12.221" y="7.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/></filter><filter id="ivPcZOc" width="2.709" height="1.502" x="12.169" y="7.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1654" stdDeviation=".2"/></filter><filter id="iSq8NfA" width="10.29" height="4.06" x="10.904" y="8.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376863 0 0 0 0 0.313721 0 0 0 0 0.444863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1654"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.160784 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1654" result="effect2_innerShadow_4002_1654"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-teacher" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a-j19kb7l {
  d: path("M18.207 9.678c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.36c.151-.112.326-.135.39-.05");
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.aig_cxbbh {
  cx: 20.86px;
  cy: 10.649px;
  r: 1.671px;
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.az-vx471y {
  d: path("m20.913 4.166l.43.213c.752.374 1.181 1.228 1.02 2.135l-.59 3.043c-.053.315-.26.526-.573.534c.036-.504.069-1.317.082-1.446c.043-.433-.025-.56-.422-.956c-.215-.214-.376-.534-.376-.854V5.98c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.324.495-.324.762c.014.155.035 1.052.06 1.425a.634.634 0 0 1-.596-.532L9.8 6.461c-.108-.854.322-1.708 1.073-2.082c1.015-.445 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.2-.32c.538.16 1.128.16 1.665 0c.806-.267 1.718-.054 2.363.534l.805.8c.215.267.483.427.805.588");
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.b91z8s82l {
  fill-rule: evenodd;
  d: path("M12.428 29.89v-8.406h-2.094v8.407z");
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bl2fvpbnr {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.694 8.3c.209-.192.803-.52 1.659-.44");
}

.c8qtn6b6q {
  d: path("M16.024 15.39c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clp58z8vu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 25.93H11.03");
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d2n_fybiv {
  stop-color: var(--svg-color--d27619, #D27619);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dd0k-ab5f {
  stop-color: var(--svg-color--6c3a0b, #6C3A0B);
}

.dkzedu77e {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.695 9.217c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.dsswvpb9g {
  stop-color: var(--svg-color--ffd743, #FFD743);
}

.dt611t2tz {
  stop-color: var(--svg-color--d27619, #D27619);
  stop-opacity: 0;
}

.e-u8dsp0m {
  stop-color: var(--svg-color--ffb60a, #FFB60A);
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e2t276r-s {
  fill-rule: evenodd;
  d: path("M17.872 8.442c.72-.068 1.182.213 1.294.317a.473.473 0 1 0 .64-.696c-.306-.282-1.032-.655-2.023-.563a.473.473 0 1 0 .088.942");
}

.ecx-4mnlf {
  d: path("m12.674 15.95l-1.36 2.93c-.09.19.05.41.26.41l.963-.266c.422-.106.437.276.277.436l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V15.95z");
}

.ei_98vf4e {
  stop-color: var(--svg-color--7a5d72, #7A5D72);
}

.ej6rok05i {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.708 10.364l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.fgn4nl1qq {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.09 13.782c-.508 0-.985-.12-1.386-.328c-.138-.07-.285.084-.199.209c.336.508.92.846 1.585.846s1.25-.338 1.584-.846c.087-.13-.06-.28-.198-.21c-.4.21-.873.33-1.386.33");
}

.ft5dv1b6b {
  fill: none;
}

.g_rztifly {
  d: path("m15.708 10.364l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g0o1xozbh {
  stop-color: var(--svg-color--ffab30, #FFAB30);
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.gchclybws {
  stop-color: var(--svg-color--feae1b, #FEAE1B);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.h55048b_d {
  stop-color: var(--svg-color--b36c17, #B36C17);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hxpahgbbh {
  stop-color: var(--svg-color--bc7120, #BC7120);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i35xvkbct {
  d: path("M13.363 25.26a.81.81 0 0 1-.302.667a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.636a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.637c.187.143.302.39.302.667c-.009.421-.32.75-.684.75H9.744c-.427 0-.774-.4-.774-.894v-3.604c0-.493.347-.893.774-.893h2.842c.475 0 .77.39.777.76");
}

.i7zauacob {
  d: path("M29.014 23.88H3.024V4.89l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.im7b7lz4m {
  d: path("M11.167 21.383c0-.384.311-.695.695-.695h9.812v1.39h-9.812a.695.695 0 0 1-.695-.695");
}

.iv0ea6b5j {
  stop-color: var(--svg-color--ffb60a, #FFB60A);
  stop-opacity: 0;
}

.j5iktke8b {
  cx: 11.338px;
  cy: 10.649px;
  r: 1.671px;
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jya_o6bif {
  d: path("M18.273 9.49a.893.893 0 0 1 .86 1.128h-1.725a.897.897 0 0 1 .865-1.129");
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.ktrz-63en {
  d: path("M22.694 29.89V17.647a10.98 10.98 0 0 1 4.32 8.745v3.5z");
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l27iszgcs {
  d: path("M18.674 25.26a.81.81 0 0 0 .303.667a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.8.8 0 0 0-.303.637c0 .267.116.503.303.637a.84.84 0 0 0-.303.667c.01.421.32.75.685.75h2.935c.426 0 .773-.4.773-.894v-3.604c0-.493-.347-.893-.773-.893H19.45a.776.776 0 0 0-.777.76");
}

.l2gllsb1x {
  d: path("M10.334 21.77v8.12h11.34V20.7c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.l3-9vppbx {
  fill-rule: evenodd;
  d: path("M14.309 8.442c-.72-.068-1.183.213-1.295.317a.473.473 0 0 1-.64-.696c.306-.282 1.032-.655 2.023-.563a.473.473 0 1 1-.088.942");
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.lkmljb8mv {
  cx: 20.86px;
  cy: 10.649px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.m-n20ybmy {
  fill: var(--svg-color--000, #000);
  d: path("M17.762 10.382a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.906a.46.46 0 0 1-.06-.236");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mvwlpibcd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.238 4.284h26.213a.1.1 0 0 1 .1.1v19.585");
}

.n6z0avo-m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 27.195H11.03");
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.ne_510bff {
  d: path("M3.024 23.88V4.89h25.99v18.99z");
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.nq67yg_fv {
  stop-color: var(--svg-color--3c2850, #3C2850);
}

.o-nhfej7r {
  d: path("M9.314 29.89V17.647a10.98 10.98 0 0 0-4.32 8.745v3.5z");
}

.o-p9b3b0d {
  d: path("M14.718 10.278c0-.29-.235-.482-.298-.54l-.289.28l.178.361z");
}

.o14v0jbig {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 28.46H11.03");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.omop9fo5u {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m20.913 4.166l.43.213c.752.374 1.181 1.228 1.02 2.135l-.59 3.043c-.053.315-.26.526-.573.534c.036-.504.069-1.317.082-1.446c.043-.433-.025-.56-.422-.956c-.215-.214-.376-.534-.376-.854V5.98c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.324.495-.324.762c.014.155.035 1.052.06 1.425a.634.634 0 0 1-.596-.532L9.8 6.461c-.108-.854.322-1.708 1.073-2.082c1.015-.445 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.2-.32c.538.16 1.128.16 1.665 0c.806-.267 1.718-.054 2.363.534l.805.8c.215.267.483.427.805.588");
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.ozv89eber {
  d: path("M20.854 8.873h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-1.11c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pk1540nca {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 28.46h1.922");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q-p4fcc8x {
  d: path("m19.364 15.95l1.36 2.93c.09.19-.05.41-.26.41l-.964-.266c-.422-.106-.436.276-.276.436l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V15.95z");
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qu_s29bvx {
  d: path("M9.97 22.99c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzei_xb9o {
  cx: 20.86px;
  cy: 10.649px;
  r: 0.996px;
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rpgn8tomk {
  d: path("M29.394 24.88H2.644c-.34 0-.62-.28-.62-.62V4.51c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sahcy-j_t {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.09 13.782c-.508 0-.985-.12-1.386-.328c-.138-.07-.285.084-.199.209c.336.508.92.846 1.585.846s1.25-.338 1.584-.846c.087-.13-.06-.28-.198-.21c-.4.21-.873.33-1.386.33Z");
}

.sch519bng {
  cx: 13.632px;
  cy: 9.871px;
  rx: 0.39px;
  ry: 0.197px;
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tp0kp63lp {
  stop-color: var(--svg-color--bfaaba, #BFAABA);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tv63_pb3n {
  d: path("M18.074 16.71h-4.11v13.18h4.11z");
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.u34g7ww8i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 27.195h1.922");
}

.u44n60b3i {
  stop-color: var(--svg-color--ffe243, #FFE243);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.uehsdacwh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.207 9.678c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.36c.151-.112.326-.135.39-.05");
}

.ujp-b1brq {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.428 29.89v-8.406h-2.094v8.407z");
}

.uqksp7bth {
  cx: 13.632px;
  cy: 9.871px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
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

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vg9ose7-a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 25.93h1.922");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.w9napxb6c {
  stop-color: var(--svg-color--f5891f, #F5891F);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wi-1d9bnt {
  stop-color: var(--svg-color--f19e2d, #F19E2D);
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wsgzsnb4q {
  d: path("M22.067 22.999c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.wxe_wdbqk {
  d: path("M16.024 18.56c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.x-xufh6qb {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.814 10.527l-.82 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.701c-.107-.377-.284-.377-.396 0");
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xixbuo9hh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.48 9.217c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.xrqg_7scz {
  stop-color: var(--svg-color--52336d, #52336D);
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.xum0pqrej {
  d: path("M19.069 10.265a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.xz35debxn {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.486 8.3c-.209-.192-.803-.52-1.659-.44");
}

.y_d5bspca {
  d: path("M13.902 9.49a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.y6d3gybmz {
  d: path("M10.985 10.036a30 30 0 0 1-.058-1.44c0-.267.107-.587.322-.747l.161-.16c.269-.214.376-.534.376-.854V5.98a.52.52 0 0 1 .43-.533c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.266 3.919.427c.214.053.429.267.429.533v.855c0 .32.161.64.376.854c.502.352.471.546.43.96c-.014.13-.054 1.196-.09 1.442l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.714 0-3.053-1.235-3.213-3.006z");
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.yd1g_ga6o {
  fill: var(--svg-color--000, #000);
  d: path("M14.413 10.382a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.236");
}

.ydne4ly1n {
  stop-color: var(--svg-color--df9a32, #DF9A32);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zx1nsdblg {
  cx: 11.338px;
  cy: 10.649px;
  r: 0.996px;
}

.zzalbbbun {
  d: path("M21.674 22.875V20.59c0-.388-.36-.698-.81-.698h-8.659c-1.041 0-1.871.73-1.871 1.621c0 .753.61 1.363 1.363 1.363z");
}

</style>
