<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iparF4b)"><path fill="url(#iY04xFe)" class="rpw8j8b4h"/></g><path fill="url(#iG7z4GB)" class="ljuykfefc"/><path fill="url(#i0Dkwke)" class="ljuykfefc"/><path fill="url(#i0I3H7c)" class="ljuykfefc"/><g filter="url(#ip4CqOF)"><path stroke="url(#iUVofAZ)" class="yo_q2mbqu"/></g><g filter="url(#is8BBhb)"><path fill="url(#iT5RT0b)" class="cxokcbbev"/><path fill="url(#iSfhgmd)" class="cxokcbbev"/><path fill="url(#iTp4ocd)" class="cxokcbbev"/></g><path fill="url(#irHdl3b)" class="olh24vs_a"/><path fill="url(#iClOADd)" class="olh24vs_a"/><path fill="url(#iRgM8fb)" class="olh24vs_a"/><path fill="url(#i3Qo81b)" class="pl0d81bak"/><path fill="url(#iNBY2Bd)" class="pl0d81bak"/><path fill="url(#ipIVble)" class="pl0d81bak"/><path fill="url(#iQJH8tX)" class="gwajdsbxg"/><path fill="url(#iyka1ye)" class="gwajdsbxg"/><path fill="url(#iwcf5ad)" class="yq7ib-b9j"/><g filter="url(#i82fSue)"><path fill="url(#iaMJFnm)" class="gbjh34bvk"/><path fill="url(#iEgFIYd)" class="gbjh34bvk"/><path fill="url(#iHj3fTb)" class="gbjh34bvk"/><path fill="url(#ihSkxmc)" class="gbjh34bvk"/></g><g filter="url(#in2UwAh)"><path fill="url(#isj9bad)" class="r9l0ibbra"/><path fill="url(#ik74l0d)" class="r9l0ibbra"/><path fill="url(#ioQQxZb)" class="r9l0ibbra"/><path fill="url(#iHPa8Jc)" class="r9l0ibbra"/></g><path fill="url(#iR6EQae)" class="rznl_to3i"/><g filter="url(#iUbu3qb)"><path fill="url(#iZnugwb)" class="jvw8d5j2f"/><path fill="url(#iLn49dO)" class="jvw8d5j2f"/></g><g filter="url(#i9KaMxb)"><path fill="url(#iiI4VWb)" class="x_sjfxb1s"/></g><path fill="url(#iPQorRb)" class="houzovuhv"/><path clip-rule="evenodd" class="obr62n_1z"/><path fill="url(#i1zVlXc)" clip-rule="evenodd" class="jumpe2bmh"/><g filter="url(#iRJ9WSd)"><path fill="url(#i5coZic)" class="aez6qbc2q"/><path fill="url(#i5QYQAN)" class="aez6qbc2q"/><path fill="url(#iiMeafe)" class="aez6qbc2q"/><path fill="url(#iVQnNnK)" class="aez6qbc2q"/><path fill="url(#iUS1D6c)" class="aez6qbc2q"/></g><g filter="url(#i5a3FRd)"><path fill="url(#ivWcP9d)" class="fyuz5q9bl"/><path fill="url(#i9KhXhe)" class="fyuz5q9bl"/><path fill="url(#ixs4T1b)" class="fyuz5q9bl"/><path fill="url(#iqzUjuK)" class="fyuz5q9bl"/><path fill="url(#iJIN8Ad)" class="fyuz5q9bl"/></g><path fill="url(#isBOq9c)" class="pp8uz1tye"/><path fill="url(#i0grD2c)" class="x6pudybhm"/><g filter="url(#ivNseQn)"><path stroke="url(#ihpyqLb)" class="hxjkjvf3k"/></g><g filter="url(#iZRjCzc)"><path stroke="url(#iscLSge)" class="cd7t-qb8m"/></g><g filter="url(#iG20aIe)"><path stroke="url(#iMnEABA)" class="ou40qgbwq"/></g><g filter="url(#iR9u6pc)"><path stroke="url(#iXvLU2i)" class="j6826vf7l"/></g><g filter="url(#iJyGJtb)"><path stroke="url(#isUaIHb)" class="pcfkb9b7n"/></g><g filter="url(#iBuhWuc)"><path stroke="url(#i1GbJnb)" class="v5kwcrbdc"/></g><g filter="url(#i9NYiqd)"><circle fill="url(#i3GnIlb)" class="xghgj-sys"/></g><circle fill="url(#iN3imJb)" class="xghgj-sys"/><g filter="url(#ib9J53c)"><circle fill="url(#i87Znfe)" class="m7i5pwb0j"/></g><g filter="url(#izKLb6T)"><circle fill="url(#imCZHec)" class="w4hwo1bzp"/><circle fill="url(#ioR3qFc)" class="w4hwo1bzp"/></g><g filter="url(#iEsDDDe)"><circle class="mpg2dsb-x"/><circle fill="url(#iDWDUYb)" class="f3cqx5agr"/><circle fill="url(#i2NAXRd)" class="f3cqx5agr"/></g><g filter="url(#iCTpqNY)"><path fill="url(#idEz3Od)" class="rkyys5bsd"/><path fill="url(#izFuuFT)" class="rkyys5bsd"/><path fill="url(#izzBSPc)" class="rkyys5bsd"/></g><path fill="url(#iY8CdzN)" class="r2356rbuw"/><path fill="url(#ioxeTRd)" class="r2356rbuw"/><path fill="url(#i7R4rxb)" class="r2356rbuw"/><g filter="url(#idFTr0c)"><path fill="url(#i3oT47d)" class="u_yr-mb_z"/></g><g filter="url(#iepPhrb)"><path class="vj24fcbug"/><path fill="url(#iMSdJ1L)" class="al_1kbwdg"/><path fill="url(#ildKWGd)" class="al_1kbwdg"/><path fill="url(#iN3bmpd)" class="al_1kbwdg"/><path fill="url(#i5uW3Tp)" class="al_1kbwdg"/></g><g filter="url(#ilUuNKc)"><path class="jelyons9y"/></g><g filter="url(#iRDlsfc)"><path class="zdyj8-bfn"/><path fill="url(#iNUsGjd)" class="jt3x-n5zy"/><path fill="url(#iselgEc)" class="jt3x-n5zy"/><path fill="url(#iV7Mosc)" class="jt3x-n5zy"/><path fill="url(#iVdUGAe)" class="jt3x-n5zy"/></g><path fill="url(#iEcdpCc)" class="jt3x-n5zy"/><path stroke="url(#igfImje)" class="lcnsf39eq"/><g filter="url(#iiQb0ye)"><path class="mcgri742c"/><path fill="url(#iwXInHb)" class="w9m5zbcfz"/></g><g filter="url(#i17crvd)"><path class="cgmx7cc8p"/><path fill="url(#ibw1kNb)" class="f9myhkvti"/></g><path class="e87ddh09o"/><path fill="url(#iah9tra)" class="fro33_b8l"/><path class="wkh4nmbzy"/><g filter="url(#icZpboe)"><path class="znwapg9gx"/><path fill="url(#iV83Ikq)" class="qbqjoxmut"/></g><g filter="url(#ijIRAke)"><path fill="url(#iwm1FBd)" class="j453ds4te"/></g><path class="joeu01eav"/><path fill="url(#ieevZLb)" class="ej5veyb7l"/><path class="ijvou3b-v"/><g filter="url(#i9FSCpS)"><path fill="url(#iI84zws)" class="r2hcjcbjh"/></g><g filter="url(#iVbAs9c)"><ellipse transform="rotate(-27.914 13.682 9.978)" class="sdpc6s5sh"/><ellipse fill="url(#i8Q1z8d)" transform="rotate(-27.914 13.682 9.978)" class="v46szh05n"/></g><g filter="url(#i6ak69d)"><path stroke="url(#iLdv5Yc)" class="th9vab0hj"/></g><g filter="url(#iHiFa7i)"><path stroke="url(#iqQA2db)" class="gw2cokb-t"/></g><g filter="url(#i50Rlwe)"><path stroke="url(#i3nygje)" class="u3kyqg55g"/></g><g filter="url(#ij6hADb)"><path fill="url(#iJ9A1dd)" class="vrr8_ab8z"/><path fill="url(#iwmXgyc)" class="vrr8_ab8z"/></g><defs><radialGradient id="i0Dkwke" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.063 6.895)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="i0I3H7c" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.582 25.495)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="iTp4ocd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.024 4.331)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="irHdl3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.02 15.964)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="iClOADd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.676 20.495)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iRgM8fb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.737 19.09)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="i3Qo81b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.014 28.245)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="iyka1ye" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.478 29.794)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="iwcf5ad" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.207 20.308)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="iEgFIYd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.25 19.455)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="iHj3fTb" cx="0" cy="0" r="1" gradientTransform="rotate(-125.283 15.14 5.138)scale(1.63656 .29806)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="ihSkxmc" cx="0" cy="0" r="1" gradientTransform="rotate(69.677 -2.845 21.16)scale(.94974 1.77776)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="ik74l0d" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.535 20.37)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="iHPa8Jc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 1 -1.87182 -.87742 14.05 16.48)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iR6EQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.81101 -2.05629 0 16.024 17.245)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="tg8dncaxu"/><stop offset="1" class="i5ttn-9gd"/></radialGradient><radialGradient id="iZnugwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.656 23.782)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="rf65-tbna"/><stop offset="1" class="olouyqb7y"/></radialGradient><radialGradient id="iLn49dO" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.799 23.5)" gradientUnits="userSpaceOnUse"><stop class="n9nuck1yg"/><stop offset="1" class="owhpyrhoe"/></radialGradient><radialGradient id="iiI4VWb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.113 24.024)" gradientUnits="userSpaceOnUse"><stop class="q0hc7-7mg"/><stop offset="1" class="morvzvhzu"/></radialGradient><radialGradient id="i5QYQAN" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.207 25.376)" gradientUnits="userSpaceOnUse"><stop class="u61ge8dhn"/><stop offset="1" class="jwhs8hbdr"/></radialGradient><radialGradient id="iiMeafe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.223 26.657)" gradientUnits="userSpaceOnUse"><stop class="u61ge8dhn"/><stop offset="1" class="jwhs8hbdr"/></radialGradient><radialGradient id="iVQnNnK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.27 27.938)" gradientUnits="userSpaceOnUse"><stop class="u61ge8dhn"/><stop offset="1" class="jwhs8hbdr"/></radialGradient><radialGradient id="iUS1D6c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.34 29.297)" gradientUnits="userSpaceOnUse"><stop class="u61ge8dhn"/><stop offset="1" class="jwhs8hbdr"/></radialGradient><radialGradient id="i9KhXhe" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.27 25.376)" gradientUnits="userSpaceOnUse"><stop class="du8z2ybjf"/><stop offset="1" class="da14u2f6i"/></radialGradient><radialGradient id="ixs4T1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.207 26.657)" gradientUnits="userSpaceOnUse"><stop class="du8z2ybjf"/><stop offset="1" class="da14u2f6i"/></radialGradient><radialGradient id="iqzUjuK" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.113 27.938)" gradientUnits="userSpaceOnUse"><stop class="du8z2ybjf"/><stop offset="1" class="da14u2f6i"/></radialGradient><radialGradient id="iJIN8Ad" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.973 29.297)" gradientUnits="userSpaceOnUse"><stop class="du8z2ybjf"/><stop offset="1" class="da14u2f6i"/></radialGradient><radialGradient id="i3GnIlb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 9.72 10.756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iN3imJb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.93 3.247)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="ioR3qFc" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.274 10.491)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iDWDUYb" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.86 11.577)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="i2NAXRd" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.627 30.792)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="izFuuFT" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.483 9.484)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="izzBSPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 13.925 9.619)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="i7R4rxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.32774 -10.3217 0 16.009 9.222)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="dcym8repk"/><stop offset="1" class="an_-aznlj"/><stop offset="1" class="v7s5ycc2u"/></radialGradient><radialGradient id="iMSdJ1L" cx="0" cy="0" r="1" gradientTransform="matrix(.79775 -2.95637 1.09632 .29583 20.482 6.65)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="ildKWGd" cx="0" cy="0" r="1" gradientTransform="matrix(3.82451 .35195 -.18924 2.05641 18.84 4.89)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iN3bmpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 16.137 2.155)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="i5uW3Tp" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.689 8.973)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iVdUGAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.464 12.362)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iwXInHb" cx="0" cy="0" r="1" gradientTransform="matrix(.10418 -.60322 1.78457 .30822 18.58 8.672)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="ibw1kNb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.865 -3.64)scale(.61215 1.81109)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iah9tra" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.316 10.074)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iV83Ikq" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 18.088 10.158)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieevZLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.953 10.074)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i8Q1z8d" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.9 -1.58)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwmXgyc" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.395 10.582)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><linearGradient id="iY04xFe" x1="11.838" x2="31.281" y1="4.62" y2="22.855" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="iG7z4GB" x1="30.082" x2="9.145" y1="13.308" y2="13.308" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="iUVofAZ" x1="13.457" x2="31.27" y1="3.561" y2="24.373" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="iT5RT0b" x1="-4.887" x2="28.926" y1="25.652" y2="25.652" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iSfhgmd" x1="3.113" x2="3.113" y1="5.214" y2="23.652" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iNBY2Bd" x1="25.193" x2="25.193" y1="30.465" y2="26.648" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="ipIVble" x1="22.426" x2="23.238" y1="29.276" y2="29.261" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iQJH8tX" x1="7.154" x2="9.548" y1="28.158" y2="28.158" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="iaMJFnm" x1="18.074" x2="20.87" y1="18.385" y2="18.385" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="isj9bad" x1="13.964" x2="11.167" y1="18.385" y2="18.385" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="ioQQxZb" x1="12.129" x2="12.691" y1="16.948" y2="17.167" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="iPQorRb" x1="21.863" x2="17.488" y1="24.808" y2="24.808" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="i1zVlXc" x1="10.334" x2="10.762" y1="23.589" y2="23.589" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="i5coZic" x1="12.883" x2="8.582" y1="28.027" y2="28.027" gradientUnits="userSpaceOnUse"><stop class="tplfgobyn"/><stop offset=".716" class="w6vvgpbob"/></linearGradient><linearGradient id="ivWcP9d" x1="22.488" x2="18.674" y1="27.62" y2="27.62" gradientUnits="userSpaceOnUse"><stop class="jpe7sib4k"/><stop offset=".807" class="hr5lgosjh"/></linearGradient><linearGradient id="isBOq9c" x1="10.801" x2="21.674" y1="21.964" y2="21.964" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="i0grD2c" x1="16.42" x2="16.42" y1="21.027" y2="22.198" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="ihpyqLb" x1="19.043" x2="20.871" y1="26.128" y2="26.128" gradientUnits="userSpaceOnUse"><stop class="kdu0rpbvx"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="xn5lfsbnz"/></linearGradient><linearGradient id="iscLSge" x1="12.952" x2="10.754" y1="26.128" y2="26.128" gradientUnits="userSpaceOnUse"><stop class="lyeznboty"/><stop offset="1" class="go3uclbeq"/></linearGradient><linearGradient id="iMnEABA" x1="19.043" x2="20.871" y1="27.394" y2="27.394" gradientUnits="userSpaceOnUse"><stop class="kdu0rpbvx"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="xn5lfsbnz"/></linearGradient><linearGradient id="iXvLU2i" x1="12.952" x2="10.754" y1="27.394" y2="27.394" gradientUnits="userSpaceOnUse"><stop class="lyeznboty"/><stop offset="1" class="go3uclbeq"/></linearGradient><linearGradient id="isUaIHb" x1="19.043" x2="20.871" y1="28.659" y2="28.659" gradientUnits="userSpaceOnUse"><stop class="kdu0rpbvx"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="xn5lfsbnz"/></linearGradient><linearGradient id="i1GbJnb" x1="12.952" x2="10.754" y1="28.659" y2="28.659" gradientUnits="userSpaceOnUse"><stop class="lyeznboty"/><stop offset="1" class="go3uclbeq"/></linearGradient><linearGradient id="i87Znfe" x1="11.389" x2="10.749" y1="11.034" y2="11.034" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="imCZHec" x1="21.988" x2="21.17" y1="9.665" y2="12.201" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="idEz3Od" x1="20.172" x2="12.536" y1="11.145" y2="12.283" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iY8CdzN" x1="10.742" x2="12.623" y1="13.841" y2="13.774" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="ioxeTRd" x1="21.057" x2="19.945" y1="13" y2="12.903" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="i3oT47d" x1="15.605" x2="23.749" y1="8.161" y2="5.245" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iNUsGjd" x1="15.273" x2="16.211" y1="11.805" y2="11.805" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iselgEc" x1="17.075" x2="16.05" y1="12.127" y2="12.112" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iV7Mosc" x1="16.332" x2="16.332" y1="12.869" y2="12.296" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iEcdpCc" x1="16.263" x2="16.263" y1="12.911" y2="12.743" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="igfImje" x1="15.1" x2="15.535" y1="14.484" y2="13.797" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iwm1FBd" x1="19.093" x2="18.78" y1="10.128" y2="10.321" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iI84zws" x1="14.697" x2="14.383" y1="10.128" y2="10.321" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLdv5Yc" x1="19.109" x2="18.689" y1="7.988" y2="7.13" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iqQA2db" x1="13.805" x2="12.616" y1="7.861" y2="7.362" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="i3nygje" x1="11.476" x2="11.476" y1="5.846" y2="8.003" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="iJ9A1dd" x1="16.099" x2="16.099" y1="9.478" y2="13.259" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient><filter id="iparF4b" width="27.98" height="21.09" x="2.024" y="4.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="ip4CqOF" width="27.413" height="20.785" x="2.688" y="3.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".2"/></filter><filter id="is8BBhb" width="27.91" height="20.96" x="2.024" y="4.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="i82fSue" width="2.797" height="14.04" x="18.074" y="15.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="in2UwAh" width="2.797" height="14.04" x="11.167" y="15.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="iUbu3qb" width="2.1" height="3.39" x="20.967" y="23.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.647059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="i9KaMxb" width="2.1" height="3.29" x="8.97" y="23.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="iRJ9WSd" width="4.793" height="5.391" x="8.97" y="24.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.458824 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="i5a3FRd" width="4.793" height="5.591" x="18.474" y="24.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.309804 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.592157 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1663" result="effect2_innerShadow_4002_1663"/></filter><filter id="ivNseQn" width="2.222" height=".3" x="18.893" y="25.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".05"/></filter><filter id="iZRjCzc" width="2.222" height=".3" x="10.88" y="25.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".05"/></filter><filter id="iG20aIe" width="2.222" height=".3" x="18.893" y="27.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".05"/></filter><filter id="iR9u6pc" width="2.222" height=".3" x="10.88" y="27.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".05"/></filter><filter id="iJyGJtb" width="2.222" height=".3" x="18.893" y="28.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".05"/></filter><filter id="iBuhWuc" width="2.222" height=".3" x="10.88" y="28.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".05"/></filter><filter id="i9NYiqd" width="3.539" height="3.339" x="9.72" y="9.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="ib9J53c" width="2.99" height="2.99" x="9.895" y="9.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".25"/></filter><filter id="izKLb6T" width="3.589" height="3.589" x="19.233" y="8.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="iEsDDDe" width="2.99" height="2.99" x="19.407" y="9.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".25"/></filter><filter id="iCTpqNY" width="10.373" height="12.177" x="10.979" y="5.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="idFTr0c" width="8.246" height="7.066" x="14.307" y="3.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation="1"/></filter><filter id="iepPhrb" width="12.601" height="8.543" x="9.837" y="1.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="ilUuNKc" width="3.26" height="4.181" x="14.268" y="9.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".375"/></filter><filter id="iRDlsfc" width="2.377" height="3.181" x="14.949" y="9.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".125"/></filter><filter id="iiQb0ye" width="2.979" height="1.873" x="17.319" y="7.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="i17crvd" width="2.98" height="1.873" x="12.172" y="7.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/></filter><filter id="icZpboe" width=".787" height=".696" x="17.582" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".05"/></filter><filter id="ijIRAke" width=".891" height=".913" x="18.421" y="9.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".1"/></filter><filter id="i9FSCpS" width=".986" height="1.04" x="13.98" y="9.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".1"/></filter><filter id="iVbAs9c" width=".913" height=".704" x="13.225" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".05"/></filter><filter id="i6ak69d" width="3.099" height="1.681" x="17.172" y="7.233" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".25"/></filter><filter id="iHiFa7i" width="3.177" height="1.738" x="11.953" y="7.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".25"/></filter><filter id="i50Rlwe" width="1.008" height="2.269" x="10.971" y="5.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1663" stdDeviation=".125"/></filter><filter id="ij6hADb" width="10.29" height="4.16" x="10.904" y="8.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1663"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1663" result="effect2_innerShadow_4002_1663"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-teacher-medium" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.aez6qbc2q {
  d: path("M13.363 25.38a.81.81 0 0 1-.302.668a.8.8 0 0 1 .302.636a.77.77 0 0 1-.302.637a.8.8 0 0 1 .302.636a.77.77 0 0 1-.302.637c.187.144.302.39.302.667c-.009.421-.32.75-.685.75H9.744c-.427 0-.774-.4-.774-.893v-3.604c0-.493.347-.894.774-.894h2.842c.475 0 .77.39.777.76");
}

.al_1kbwdg {
  d: path("m20.955 4.279l.43.213c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.747c.054.587.108 1.44.108 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.854.322-1.707 1.073-2.08l.429-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.054 2.36.533l.805.8c.214.267.483.427.804.587");
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.an_-aznlj {
  stop-color: var(--svg-color--7c5267, #7C5267);
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

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
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

.cgmx7cc8p {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m12.364 8.036l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.099-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.678-.824");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cxokcbbev {
  d: path("M29.014 24.001H3.024V5.011l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.da14u2f6i {
  stop-color: var(--svg-color--bb8c7c, #BB8C7C);
  stop-opacity: 0;
}

.dcym8repk {
  stop-color: var(--svg-color--9b7168, #9B7168);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.du8z2ybjf {
  stop-color: var(--svg-color--cfa591, #CFA591);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e87ddh09o {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.525 9.325c.652 0 1.204.45 1.354 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ej5veyb7l {
  d: path("M13.951 9.597a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.f3cqx5agr {
  cx: 20.902px;
  cy: 10.756px;
  r: 0.995px;
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f9myhkvti {
  d: path("m12.364 8.036l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.099-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.678-.824");
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

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.fro33_b8l {
  d: path("M18.318 9.597a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.127");
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fyuz5q9bl {
  d: path("M18.674 25.38a.81.81 0 0 0 .303.668a.8.8 0 0 0-.303.636c0 .267.116.503.303.637a.8.8 0 0 0-.303.636c0 .267.116.503.303.637a.84.84 0 0 0-.303.667c.01.421.32.75.685.75h2.935c.426 0 .773-.4.773-.893v-3.604c0-.493-.347-.894-.773-.894H19.45a.776.776 0 0 0-.777.76");
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.gbjh34bvk {
  d: path("m19.364 16.071l1.36 2.928c.09.19-.05.41-.26.41l-.964-.265c-.422-.105-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87v-13.94z");
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.go3uclbeq {
  stop-color: var(--svg-color--9c6c55, #9C6C55);
  stop-opacity: 0;
}

.gugba3b_v {
  stop-color: var(--svg-color--33141c, #33141C);
  stop-opacity: 0;
}

.gw2cokb-t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.578 8.41c.328-.289 1.042-.593 1.927-.452");
}

.gwajdsbxg {
  d: path("M9.314 30.01V17.767a10.98 10.98 0 0 0-4.32 8.745v3.5z");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.houzovuhv {
  d: path("M10.334 21.89v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hr5lgosjh {
  stop-color: var(--svg-color--90605d, #90605D);
}

.hxjkjvf3k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 26.05h1.922");
}

.i5ttn-9gd {
  stop-color: var(--svg-color--462d27, #462D27);
}

.ijvou3b-v {
  fill: var(--svg-color--000, #000);
  d: path("M14.462 10.49a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.904a.5.5 0 0 0 .061-.236");
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j453ds4te {
  d: path("M19.112 10.372a.84.84 0 0 0-.23-.463l-.26.285l.117.228z");
}

.j6826vf7l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 27.316H11.03");
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jelyons9y {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.862 10.634l-.82 1.7c-.102.349.142.698.488.698h.737c.345 0 .59-.355.488-.699l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.joeu01eav {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.744 9.325c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.jpe7sib4k {
  stop-color: var(--svg-color--ca9d86, #CA9D86);
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jt3x-n5zy {
  d: path("m15.755 10.47l-.532 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.jumpe2bmh {
  fill-rule: evenodd;
  d: path("M12.428 30.011v-8.406h-2.094v8.406z");
}

.jvw8d5j2f {
  d: path("M22.067 23.119c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.jwhs8hbdr {
  stop-color: var(--svg-color--a97d6f, #A97D6F);
  stop-opacity: 0;
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.kdu0rpbvx {
  stop-color: var(--svg-color--773e41, #773E41);
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lcnsf39eq {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.775 13.513a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24c.344.52.942.867 1.624.867s1.28-.347 1.625-.868a.19.19 0 0 0-.021-.242a.2.2 0 0 0-.242-.04a2.94 2.94 0 0 1-1.362.324c-.5 0-.969-.118-1.362-.323Z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.ljuykfefc {
  d: path("M3.024 24.001V5.011h25.99v18.99z");
}

.lyeznboty {
  stop-color: var(--svg-color--9c6c55, #9C6C55);
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m7i5pwb0j {
  cx: 11.389px;
  cy: 10.756px;
  r: 0.995px;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcgri742c {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M19.856 8.036h-.001l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 0 0 .166 1.054c.398-.063.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.morvzvhzu {
  stop-color: var(--svg-color--86645b, #86645B);
}

.mpg2dsb-x {
  cx: 20.902px;
  cy: 10.756px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.n9nuck1yg {
  stop-color: var(--svg-color--cca48e, #CCA48E);
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.obr62n_1z {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.428 30.011v-8.406h-2.094v8.406z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.olh24vs_a {
  d: path("M16.024 15.511c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.olouyqb7y {
  stop-color: var(--svg-color--865f46, #865F46);
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.ou40qgbwq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 27.316h1.922");
}

.owhpyrhoe {
  stop-color: var(--svg-color--cca48e, #CCA48E);
  stop-opacity: 0;
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.pcfkb9b7n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 28.581h1.922");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl0d81bak {
  d: path("M22.694 30.01V17.767a10.98 10.98 0 0 1 4.32 8.745v3.5z");
}

.pp8uz1tye {
  d: path("M21.674 22.995V20.71c0-.388-.36-.698-.81-.698h-8.659c-1.041 0-1.871.73-1.871 1.621c0 .753.61 1.363 1.363 1.363z");
}

.q0hc7-7mg {
  stop-color: var(--svg-color--58382a, #58382A);
}

.qbqjoxmut {
  d: path("M18.252 9.786c.064.085-.07.188-.22.301c-.151.113-.263.193-.327.108c-.063-.085.007-.246.159-.359c.15-.113.325-.135.388-.05");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r2356rbuw {
  d: path("M10.98 8.705c0-.267.107-.587.321-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.534c.643-.16 1.984-.426 3.915-.426c1.93 0 3.272.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003c-.14-1.816-.2-3.638-.367-5.451");
}

.r2hcjcbjh {
  d: path("M14.766 10.384c0-.288-.234-.48-.298-.538l-.288.278l.177.362z");
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.r9l0ibbra {
  d: path("m12.674 16.071l-1.36 2.928c-.09.19.05.41.26.41l.963-.265c.422-.105.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87v-13.94z");
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rf65-tbna {
  stop-color: var(--svg-color--b78876, #B78876);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rkyys5bsd {
  d: path("m11.038 10.143l.049.002s-.054-.853-.108-1.44c0-.267.108-.587.322-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.534c.643-.16 1.984-.426 3.915-.426c1.93 0 3.272.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003z");
}

.rpw8j8b4h {
  d: path("M29.394 25.001H2.644c-.34 0-.62-.28-.62-.62V4.631c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.rznl_to3i {
  d: path("M16.024 18.681c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.sdpc6s5sh {
  cx: 13.682px;
  cy: 9.978px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.tg8dncaxu {
  stop-color: var(--svg-color--754f48, #754F48);
}

.th9vab0hj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.798 7.892c.43-.076 1.268-.054 1.849.397");
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tplfgobyn {
  stop-color: var(--svg-color--b78c74, #B78C74);
}

.u_yr-mb_z {
  d: path("m20.1 5.132l-3.077 1.026a1.047 1.047 0 0 0 .47 2.03l3.06-.409z");
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.u3kyqg55g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.605 5.945v.898c-.008.148-.07.48-.259.621");
}

.u61ge8dhn {
  stop-color: var(--svg-color--c59c8b, #C59C8B);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v46szh05n {
  cx: 13.682px;
  cy: 9.978px;
  rx: 0.389px;
  ry: 0.197px;
}

.v5kwcrbdc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 28.581H11.03");
}

.v7s5ycc2u {
  stop-color: var(--svg-color--6b403e, #6B403E);
}

.vj24fcbug {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m20.955 4.279l.43.213c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.747c.054.587.108 1.44.108 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.854.322-1.707 1.073-2.08l.429-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.054 2.36.533l.805.8c.214.267.483.427.804.587");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vrr8_ab8z {
  d: path("M20.854 9.072h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-1.11c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w4hwo1bzp {
  cx: 20.902px;
  cy: 10.756px;
  r: 1.669px;
}

.w6vvgpbob {
  stop-color: var(--svg-color--936567, #936567);
}

.w9m5zbcfz {
  d: path("M19.856 8.036h-.001l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 0 0 .166 1.054c.398-.063.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wkh4nmbzy {
  fill: var(--svg-color--000, #000);
  d: path("M17.807 10.49c0-.285.227-.512.51-.512a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.x_sjfxb1s {
  d: path("M9.97 23.11c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x6pudybhm {
  d: path("M11.167 21.503c0-.384.311-.695.695-.695h9.812v1.39h-9.812a.695.695 0 0 1-.695-.695");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xghgj-sys {
  cx: 11.389px;
  cy: 10.756px;
  r: 1.669px;
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xn5lfsbnz {
  stop-color: var(--svg-color--773e41, #773E41);
  stop-opacity: 0;
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
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

.yo_q2mbqu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.238 4.404h26.213a.1.1 0 0 1 .1.1V24.09");
}

.yq7ib-b9j {
  d: path("M18.074 16.831h-4.11v13.18h4.11z");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zdyj8-bfn {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.755 10.47l-.532 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.znwapg9gx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.252 9.786c.064.085-.07.188-.22.301c-.151.113-.263.193-.327.108c-.063-.085.007-.246.159-.359c.15-.113.325-.135.388-.05");
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
