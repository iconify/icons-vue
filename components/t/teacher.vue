<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iAVre4d)"><path fill="url(#iIkQWxc)" class="r18win3fg"/></g><path fill="url(#ijtLpSb)" class="phm5rwbri"/><path fill="url(#iGEtBKc)" class="phm5rwbri"/><path fill="url(#ikXNyFd)" class="phm5rwbri"/><g filter="url(#iguRmFc)"><path stroke="url(#iIzewyc)" class="bjss4qb7y"/></g><g filter="url(#ioD5OCb)"><path fill="url(#iMxlm5b)" class="g-7jpubav"/><path fill="url(#ioBMZ8b)" class="g-7jpubav"/><path fill="url(#iennlTj)" class="g-7jpubav"/></g><path fill="url(#ipzHQNb)" class="s5ydg5rnt"/><path fill="url(#iFe9Cte)" class="s5ydg5rnt"/><path fill="url(#iuo5d4z)" class="s5ydg5rnt"/><path fill="url(#irefMrd)" class="ho9t--bxm"/><path fill="url(#ivUbVne)" class="ho9t--bxm"/><path fill="url(#irnMn5d)" class="ho9t--bxm"/><path fill="url(#iXpcHIc)" class="hm6n9mbhu"/><path fill="url(#ilBxWBc)" class="hm6n9mbhu"/><path fill="url(#iCnqSvd)" class="qahsn1brm"/><g filter="url(#iSu724c)"><path fill="url(#iZHG0Gq)" class="kpv0uqbdt"/><path fill="url(#iyeUfub)" class="kpv0uqbdt"/><path fill="url(#izlD84c)" class="kpv0uqbdt"/><path fill="url(#ikfWlWd)" class="kpv0uqbdt"/></g><g filter="url(#io0sstG)"><path fill="url(#ibtimqd)" class="br2-j9bdi"/><path fill="url(#ioqF7wd)" class="br2-j9bdi"/><path fill="url(#i94AZbd)" class="br2-j9bdi"/><path fill="url(#in1NIsb)" class="br2-j9bdi"/></g><path fill="url(#iuBrRJe)" class="r7lb1kd5g"/><path fill="url(#i2u4oNK)" class="jnmuldpbd"/><path fill="url(#i1yCyIc)" class="oymugd-ic"/><path fill="url(#iKbjaTc)" class="biz1lvp0h"/><path clip-rule="evenodd" class="c9o350lct"/><path fill="url(#iiM8Oze)" clip-rule="evenodd" class="q8sarnbwy"/><g filter="url(#iRescEb)"><path fill="url(#ik93t1b)" class="a6yxc7b5z"/></g><g filter="url(#iJbcfJb)"><path fill="url(#imeWPNE)" class="pe4gumbtl"/></g><path fill="url(#iqAUjZb)" class="cgnvhgbjg"/><path fill="url(#iGK648b)" class="zs-gb8-xd"/><path fill="url(#igef7ld)" class="zs-gb8-xd"/><path fill="url(#iZ4pD0c)" class="xk_zazbvs"/><path fill="url(#ibUkYve)" class="xk_zazbvs"/><g filter="url(#iBM4frd)"><path fill="url(#ia8V8Tc)" class="p8y0cvbfk"/></g><path fill="url(#iNxFZpb)" class="p8y0cvbfk"/><path fill="url(#iMmAPcc)" class="p8y0cvbfk"/><path fill="url(#iSP8WEe)" class="p8y0cvbfk"/><path fill="url(#i5dNcOd)" class="p8y0cvbfk"/><g filter="url(#iyOREvt)"><path class="mpsa1s2ul"/></g><g filter="url(#iRJuIob)"><path fill="url(#ilDsCPi)" class="lewet796p"/><path fill="url(#idcEeXc)" class="lewet796p"/><path fill="url(#io2YKfb)" class="lewet796p"/><path fill="url(#i15os7D)" class="lewet796p"/></g><g filter="url(#iSITiOb)"><path stroke="url(#i0CbOjh)" class="xpkp7pbbl"/></g><path fill="url(#ivyt4HO)" class="wb1jw4d_c"/><g filter="url(#iYzCglb)"><path fill="url(#inY6XoW)" class="v6j97yb7y"/><path fill="url(#igIUbTd)" class="v6j97yb7y"/><path fill="url(#iOvqrYc)" class="v6j97yb7y"/><path fill="url(#i9cmNfe)" class="v6j97yb7y"/><path fill="url(#i4DkVbb)" class="v6j97yb7y"/></g><g filter="url(#iipsJTV)"><path class="mx8rrbctz"/></g><g filter="url(#iSEI5gd)"><path class="mf-huiiiu"/></g><g filter="url(#ilmucib)"><path fill="url(#iPxQW7b)" class="xeiwvjbsm"/><path fill="url(#iBah5gb)" class="xeiwvjbsm"/></g><g filter="url(#ilXLfib)"><path fill="url(#ieAYYwz)" class="ks24vacvm"/><path fill="url(#iJ8atgv)" class="ks24vacvm"/><path fill="url(#ihV08sd)" class="ks24vacvm"/><path fill="url(#i4BdZEc)" class="ks24vacvm"/><path fill="url(#ixWkiSb)" class="ks24vacvm"/></g><path class="u002vnx_k"/><path fill="url(#ig3R6Rc)" class="e2h9w1b6l"/><path class="qmj2ygbtg"/><g filter="url(#iXtBCwe)"><path class="o17ge-m6a"/><path fill="url(#ii7pLTb)" class="ps3h6zben"/></g><g filter="url(#iz2D3nd)"><path fill="url(#iBJh0lc)" class="xs6drzw0l"/></g><path class="kxrm6eq0x"/><path fill="url(#iY39kwb)" class="n6hhroldr"/><path class="yo8odn-5y"/><g filter="url(#iodCLFd)"><path fill="url(#iqJEmSc)" class="ro58p9b2v"/></g><g filter="url(#iytBjZc)"><ellipse transform="rotate(-27.914 13.624 9.868)" class="fh1huwu8g"/><ellipse fill="url(#iUVKBDc)" transform="rotate(-27.914 13.624 9.868)" class="i-5pstbpb"/></g><path fill="url(#izfYyUb)" class="zq_vtfiyq"/><path fill="url(#iKUAPuc)" class="zq_vtfiyq"/><path fill="url(#iFe3wZb)" class="zq_vtfiyq"/><path fill="url(#iuG8Iod)" class="x68xoccvj"/><path fill="url(#i0OMo7c)" class="x68xoccvj"/><g filter="url(#iI3BaBv)"><path class="br248dbes"/></g><g filter="url(#iO1eHkc)"><path class="xpzxw-8tv"/></g><g filter="url(#iC3QNAe)"><path class="nrib-rbxe"/></g><g filter="url(#ioAqH2n)"><path class="rwr3-6x4g"/></g><g filter="url(#io8ksKc)"><path fill="url(#ijEXTjc)" class="vp5zpbcof"/><path fill="url(#iQOAw9b)" class="vp5zpbcof"/></g><path fill="url(#iWpdied)" class="en_17izwf"/><g filter="url(#iEy123c)"><path stroke="url(#iv1CYrb)" class="lce_ol_cu"/></g><g filter="url(#iAJBe4b)"><path stroke="url(#ik6dBWc)" class="hb0n7t-_a"/></g><g filter="url(#i21T2nd)"><path stroke="url(#iD4eZ1d)" class="p7y8wcb3n"/></g><g filter="url(#ixUaJ3c)"><path stroke="url(#icACLuK)" class="av520kbob"/></g><g filter="url(#iNslJIF)"><path stroke="url(#i54RiXb)" class="z7egokwqq"/></g><g filter="url(#inCVzpc)"><path stroke="url(#igQuY7b)" class="r5vhzbcfw"/></g><defs><radialGradient id="iGEtBKc" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 26.942 6.853)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="ikXNyFd" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.563 25.375)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="iennlTj" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.004 4.21)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="ipzHQNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16 15.844)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="iFe9Cte" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.656 20.375)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iuo5d4z" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.718 18.97)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="irefMrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 26.994 28.125)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="ilBxWBc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.458 29.674)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="iCnqSvd" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.188 20.188)" gradientUnits="userSpaceOnUse"><stop class="tp0kp63lp"/><stop offset="1" class="ei_98vf4e"/></radialGradient><radialGradient id="iyeUfub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.23 19.335)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="izlD84c" cx="0" cy="0" r="1" gradientTransform="rotate(-125.283 15.1 5.082)scale(1.63656 .29806)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="ikfWlWd" cx="0" cy="0" r="1" gradientTransform="rotate(69.677 -2.769 21.087)scale(.94974 1.77776)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="ioqF7wd" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.516 20.25)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="in1NIsb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 1 -1.87182 -.87742 14.031 16.36)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iuBrRJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.34375 -2.51976 0 16.004 17.125)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="hxpahgbbh"/><stop offset="1" class="dd0k-ab5f"/></radialGradient><radialGradient id="i2u4oNK" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1 -1.11832 -1.11832 23.047 23.523)" gradientUnits="userSpaceOnUse"><stop class="yomsttbzk"/><stop offset=".814" class="gchclybws"/></radialGradient><radialGradient id="i1yCyIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.59343 0 0 4.99275 9.063 24.516)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ydne4ly1n"/><stop offset="1" class="h55048b_d"/></radialGradient><radialGradient id="iGK648b" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 6.128 14.49)scale(3.83308 4.5534)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="igef7ld" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -1.448 26.586)scale(.49839 .42339)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iZ4pD0c" cx="0" cy="0" r="1" gradientTransform="matrix(1.3345 3.92766 -1.7853 .6066 10.525 11.941)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="ibUkYve" cx="0" cy="0" r="1" gradientTransform="matrix(.3188 .99836 -.87578 .27966 11.188 11.933)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="ia8V8Tc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.23346 0 0 -9.25793 18.89 10.881)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iNxFZpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.38945 13.1853 0 15.885 17.224)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="iMmAPcc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40294 6.10847 -2.24573 -.14814 21.242 10.65)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iSP8WEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41538 1.70404 0 13.986 9.7)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="i5dNcOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53689 1.99339 0 18.57 9.288)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="i0CbOjh" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.572 -5.672)scale(.71086 2.06861)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="ivyt4HO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.7215 2.90282 0 16.08 14.425)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="igIUbTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.72511 10.1438 0 10.844 9.298)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iOvqrYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63655 6.44325 0 20.945 9.298)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="i9cmNfe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.11092 -1.44236 .76815 -2.18933 20.19 3.015)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="i4DkVbb" cx="0" cy="0" r="1" gradientTransform="matrix(.90608 1.47658 -3.41906 2.09806 15.173 1.42)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iPxQW7b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.811 1.37505 -.3827 -1.06069 16.333 2.864)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iBah5gb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.242 -5.84)scale(6.03308 6.68403)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="ieAYYwz" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -7.404 86.466)scale(3.48294 1.9479)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iJ8atgv" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1509 -3.70767 2.06774 -1.19954 21.214 8.635)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="ihV08sd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 12.669 -1.694)scale(2.56386 1.83638)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="i4BdZEc" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 10.208 3.19)scale(4.93988 5.3402)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="ixWkiSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11746 .38414 -1.75623 -.537 19.536 3.784)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="ig3R6Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81219 -1.29188 0 18.264 9.964)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ii7pLTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23245 -.29954 .4124 -.32003 18.036 10.049)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iY39kwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81223 -1.29194 0 13.895 9.964)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iUVKBDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00775 -.49522 .59527 -.00932 13.609 10.184)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKUAPuc" cx="0" cy="0" r="1" gradientTransform="matrix(.62922 2.24568 -2.14255 .60033 20.702 9.978)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iFe3wZb" cx="0" cy="0" r="1" gradientTransform="matrix(.78862 -1.08226 .90715 .66102 21.063 10.523)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i0OMo7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.41331 2.07825 -2.0431 -.40633 10.81 10.145)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iQOAw9b" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.375 9.89)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><linearGradient id="iIkQWxc" x1="11.819" x2="31.261" y1="4.5" y2="22.735" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="ijtLpSb" x1="30.063" x2="9.125" y1="13.188" y2="13.188" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="iIzewyc" x1="13.438" x2="31.25" y1="3.44" y2="24.253" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="iMxlm5b" x1="-4.906" x2="28.906" y1="25.531" y2="25.531" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="ioBMZ8b" x1="3.094" x2="3.094" y1="5.094" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="ivUbVne" x1="25.174" x2="25.174" y1="30.345" y2="26.528" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="irnMn5d" x1="22.406" x2="23.219" y1="29.156" y2="29.141" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iXpcHIc" x1="7.134" x2="9.529" y1="28.038" y2="28.038" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="iZHG0Gq" x1="18.054" x2="20.851" y1="18.265" y2="18.265" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="ibtimqd" x1="13.944" x2="11.147" y1="18.265" y2="18.265" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="i94AZbd" x1="12.109" x2="12.672" y1="16.828" y2="17.047" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="iKbjaTc" x1="21.844" x2="17.469" y1="24.688" y2="24.688" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="iiM8Oze" x1="10.314" x2="10.742" y1="23.469" y2="23.469" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="ik93t1b" x1="12.5" x2="8.563" y1="27.906" y2="27.906" gradientUnits="userSpaceOnUse"><stop class="dsswvpb9g"/><stop offset="1" class="w9napxb6c"/><stop offset="1" class="wi-1d9bnt"/></linearGradient><linearGradient id="imeWPNE" x1="22.469" x2="18.654" y1="27.5" y2="27.5" gradientUnits="userSpaceOnUse"><stop class="u44n60b3i"/><stop offset="1" class="w9napxb6c"/><stop offset="1" class="g0o1xozbh"/></linearGradient><linearGradient id="iqAUjZb" x1="10.781" x2="21.654" y1="21.844" y2="21.844" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="ilDsCPi" x1="16.079" x2="16.935" y1="11.711" y2="11.711" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="idcEeXc" x1="15.005" x2="16.081" y1="11.555" y2="11.614" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="io2YKfb" x1="16.079" x2="16.079" y1="12.11" y2="12.963" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="i15os7D" x1="16.079" x2="16.079" y1="9.86" y2="10.28" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="inY6XoW" x1="21.448" x2="11.314" y1="5.213" y2="5.213" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iBJh0lc" x1="19.043" x2="18.728" y1="10.018" y2="10.212" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqJEmSc" x1="14.64" x2="14.326" y1="10.018" y2="10.212" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izfYyUb" x1="22.522" x2="21.314" y1="10.045" y2="12.224" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iuG8Iod" x1="10.223" x2="11.683" y1="10.749" y2="10.622" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="ijEXTjc" x1="22.93" x2="16.08" y1="6.765" y2="13.616" gradientUnits="userSpaceOnUse"><stop class="xrqg_7scz"/><stop offset="1" class="nq67yg_fv"/></linearGradient><linearGradient id="iWpdied" x1="16.401" x2="16.401" y1="20.906" y2="22.078" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="iv1CYrb" x1="19.023" x2="20.852" y1="26.008" y2="26.008" gradientUnits="userSpaceOnUse"><stop class="d2n_fybiv"/><stop offset="1" class="dt611t2tz"/></linearGradient><linearGradient id="ik6dBWc" x1="12.932" x2="10.734" y1="26.008" y2="26.008" gradientUnits="userSpaceOnUse"><stop class="e-u8dsp0m"/><stop offset="1" class="iv0ea6b5j"/></linearGradient><linearGradient id="iD4eZ1d" x1="19.023" x2="20.852" y1="27.273" y2="27.273" gradientUnits="userSpaceOnUse"><stop class="d2n_fybiv"/><stop offset="1" class="dt611t2tz"/></linearGradient><linearGradient id="icACLuK" x1="12.932" x2="10.734" y1="27.273" y2="27.273" gradientUnits="userSpaceOnUse"><stop class="e-u8dsp0m"/><stop offset="1" class="iv0ea6b5j"/></linearGradient><linearGradient id="i54RiXb" x1="19.023" x2="20.852" y1="28.539" y2="28.539" gradientUnits="userSpaceOnUse"><stop class="d2n_fybiv"/><stop offset="1" class="dt611t2tz"/></linearGradient><linearGradient id="igQuY7b" x1="12.932" x2="10.734" y1="28.539" y2="28.539" gradientUnits="userSpaceOnUse"><stop class="e-u8dsp0m"/><stop offset="1" class="iv0ea6b5j"/></linearGradient><filter id="iAVre4d" width="27.98" height="21.09" x="2.004" y="3.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/></filter><filter id="iguRmFc" width="27.413" height="20.785" x="2.669" y="3.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".2"/></filter><filter id="ioD5OCb" width="27.91" height="20.96" x="2.004" y="3.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/></filter><filter id="iSu724c" width="2.797" height="14.04" x="18.054" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/></filter><filter id="io0sstG" width="2.797" height="14.04" x="11.147" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/></filter><filter id="iRescEb" width="4.593" height="5.591" x="8.951" y="24.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.588235 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/></filter><filter id="iJbcfJb" width="4.593" height="5.591" x="18.654" y="24.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.458824 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/></filter><filter id="iBM4frd" width="10.731" height="12.555" x="11.011" y="4.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1652" result="effect2_innerShadow_4002_1652"/></filter><filter id="iyOREvt" width="3.879" height="4.903" x="13.932" y="9.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".5"/></filter><filter id="iRJuIob" width="2.079" height="3.103" x="15.04" y="9.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".05"/></filter><filter id="iSITiOb" width="3.722" height="1.574" x="14.218" y="13.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".05"/></filter><filter id="iYzCglb" width="12.886" height="8.365" x="9.636" y="1.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1652" result="effect2_innerShadow_4002_1652"/></filter><filter id="iipsJTV" width="2.341" height="1.191" x="17.67" y="7.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/></filter><filter id="iSEI5gd" width="2.341" height="1.177" x="12.408" y="7.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/></filter><filter id="ilmucib" width="6.591" height="5.998" x="9.992" y="2.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".125"/></filter><filter id="ilXLfib" width="6.368" height="5.742" x="15.92" y="3.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".125"/></filter><filter id="iXtBCwe" width=".788" height=".698" x="17.529" y="9.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".05"/></filter><filter id="iz2D3nd" width=".892" height=".915" x="18.37" y="9.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".1"/></filter><filter id="iodCLFd" width=".988" height="1.042" x="13.922" y="9.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".1"/></filter><filter id="iytBjZc" width=".915" height=".706" x="13.166" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".05"/></filter><filter id="iI3BaBv" width="1.33" height="2.381" x="10.041" y="9.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".125"/></filter><filter id="iO1eHkc" width="1.448" height="2.405" x="20.796" y="9.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".125"/></filter><filter id="iC3QNAe" width="2.407" height="1.161" x="12.327" y="7.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".125"/></filter><filter id="ioAqH2n" width="2.407" height="1.161" x="17.612" y="7.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".125"/></filter><filter id="io8ksKc" width="10.29" height="4.06" x="10.884" y="8.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376863 0 0 0 0 0.313721 0 0 0 0 0.444863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1652"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.160784 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1652" result="effect2_innerShadow_4002_1652"/></filter><filter id="iEy123c" width="2.222" height=".3" x="18.873" y="25.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".05"/></filter><filter id="iAJBe4b" width="2.222" height=".3" x="10.861" y="25.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".05"/></filter><filter id="i21T2nd" width="2.222" height=".3" x="18.873" y="27.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".05"/></filter><filter id="ixUaJ3c" width="2.222" height=".3" x="10.861" y="27.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".05"/></filter><filter id="iNslJIF" width="2.222" height=".3" x="18.873" y="28.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".05"/></filter><filter id="inCVzpc" width="2.222" height=".3" x="10.861" y="28.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1652" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:teacher" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a6yxc7b5z {
  d: path("M13.344 25.26a.81.81 0 0 1-.303.667a.8.8 0 0 1 .303.637a.77.77 0 0 1-.303.636a.8.8 0 0 1 .303.637a.77.77 0 0 1-.303.637c.187.143.303.39.303.667c-.01.421-.32.75-.685.75H9.724c-.426 0-.773-.4-.773-.894v-3.604c0-.493.347-.893.773-.893h2.842c.475 0 .77.39.778.76");
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
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

.av520kbob {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 27.195h-1.921");
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.biz1lvp0h {
  d: path("M10.314 21.77v8.12h11.34V20.7c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bjss4qb7y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.219 4.284H29.43a.1.1 0 0 1 .1.1v19.585");
}

.bkz_cdc-o {
  stop-color: var(--svg-color--e27426, #E27426);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.br2-j9bdi {
  d: path("m12.654 15.95l-1.36 2.93c-.09.19.05.41.26.41l.964-.266c.422-.106.436.276.276.436l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V15.95z");
}

.br248dbes {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M11.037 9.683a.957.957 0 0 0 .084 1.881a78 78 0 0 1-.084-1.881");
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.c9o350lct {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.408 29.89v-8.406h-2.094v8.407z");
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.cgnvhgbjg {
  d: path("M21.654 22.875V20.59c0-.388-.36-.698-.81-.698h-8.658c-1.042 0-1.872.73-1.872 1.621c0 .753.61 1.363 1.363 1.363z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d2n_fybiv {
  stop-color: var(--svg-color--d27619, #D27619);
}

.dd0k-ab5f {
  stop-color: var(--svg-color--6c3a0b, #6C3A0B);
}

.dsswvpb9g {
  stop-color: var(--svg-color--ffd743, #FFD743);
}

.dt611t2tz {
  stop-color: var(--svg-color--d27619, #D27619);
  stop-opacity: 0;
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e-u8dsp0m {
  stop-color: var(--svg-color--ffb60a, #FFB60A);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e2h9w1b6l {
  d: path("M18.266 9.487a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.ei_98vf4e {
  stop-color: var(--svg-color--7a5d72, #7A5D72);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.en_17izwf {
  d: path("M11.147 21.383c0-.384.312-.695.696-.695h9.811v1.39h-9.811a.695.695 0 0 1-.696-.695");
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

.fh1huwu8g {
  cx: 13.624px;
  cy: 9.868px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.391px;
  ry: 0.198px;
}

.ft5dv1b6b {
  fill: none;
}

.g-7jpubav {
  d: path("M28.994 23.88H3.004V4.89l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g0o1xozbh {
  stop-color: var(--svg-color--ffab30, #FFAB30);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gchclybws {
  stop-color: var(--svg-color--feae1b, #FEAE1B);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h55048b_d {
  stop-color: var(--svg-color--b36c17, #B36C17);
}

.hb0n7t-_a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 25.93h-1.921");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hm6n9mbhu {
  d: path("M9.294 29.89V17.647a10.98 10.98 0 0 0-4.32 8.745v3.5z");
}

.ho9t--bxm {
  d: path("M22.674 29.89V17.647a10.98 10.98 0 0 1 4.32 8.745v3.5z");
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hxpahgbbh {
  stop-color: var(--svg-color--bc7120, #BC7120);
}

.i-5pstbpb {
  cx: 13.624px;
  cy: 9.868px;
  rx: 0.391px;
  ry: 0.198px;
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.iv0ea6b5j {
  stop-color: var(--svg-color--ffb60a, #FFB60A);
  stop-opacity: 0;
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jnmuldpbd {
  d: path("M22.048 22.999c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.kpv0uqbdt {
  d: path("m19.344 15.95l1.36 2.93c.09.19-.05.41-.26.41l-.963-.266c-.422-.106-.437.276-.277.436l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V15.95z");
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.ks24vacvm {
  d: path("m21.297 8.635l-.029-.631c-.01-.765-.642-1.395-1.407-1.427H18.46c-.89 0-1.702-.487-2.126-1.261c0 0-.06-.137-.121-.37c-.256-.97.671-1.713 1.656-1.522c.975.189 2.086.517 2.907 1.053c1.746 1.139 1.44 3.192.521 4.158");
}

.kxrm6eq0x {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.686 9.215c-.654 0-1.207.45-1.357 1.06a.274.274 0 0 0 .268.34h2.234a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.13");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lce_ol_cu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 25.93h1.922");
}

.lewet796p {
  d: path("m15.697 10.166l-.533 1.84c-.108.379.152.757.522.757h.787c.369 0 .63-.384.521-.757l-.532-1.84c-.114-.408-.646-.408-.765 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf-huiiiu {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.665 7.79a2.78 2.78 0 0 1 1.74-.36a.278.278 0 1 1-.067.55a2.22 2.22 0 0 0-1.388.286a1 1 0 0 0-.092.06l-.003.002a.278.278 0 0 1-.34-.44z");
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mpsa1s2ul {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.593 10.362l-.636 1.84c-.109.379.152.757.521.757h.787c.37 0 .63-.384.521-.757l-.532-1.84c-.114-.408-.542-.408-.662 0");
}

.mx8rrbctz {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.816 7.899a1.9 1.9 0 0 0-.688-.412c-.305-.096-.686-.122-1.214-.057a.278.278 0 0 0 .067.55c.482-.058.777-.028.98.036c.199.063.333.164.49.301a.278.278 0 0 0 .365-.418");
}

.n6hhroldr {
  d: path("M13.893 9.487a.893.893 0 0 0-.861 1.129h1.726a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nq67yg_fv {
  stop-color: var(--svg-color--3c2850, #3C2850);
}

.nrib-rbxe {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.702 8.07c.258-.185.899-.51 1.657-.382");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o17ge-m6a {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.2 9.675c.064.085-.069.19-.22.303c-.152.113-.264.193-.328.107c-.064-.085.008-.246.159-.36c.151-.112.326-.135.39-.05");
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.oymugd-ic {
  d: path("M9.95 22.99c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.p7y8wcb3n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 27.195h1.922");
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.p8y0cvbfk {
  d: path("M11.249 13.65a3.92 3.92 0 0 0 3.89 3.409h1.889a3.92 3.92 0 0 0 3.89-3.41c.117-1.885.236-3.764.324-5.648a1.45 1.45 0 0 0-1.38-1.434H18.46a2.42 2.42 0 0 1-2.214-1.444a.665.665 0 0 0-.616-.42h-1.275c-1.847 0-3.344 1.515-3.344 3.384c0 1.862.116 3.695.238 5.562");
}

.pe4gumbtl {
  d: path("M18.655 25.26a.81.81 0 0 0 .302.667a.8.8 0 0 0-.302.637c0 .267.115.503.302.636a.8.8 0 0 0-.302.637c0 .267.115.503.302.637a.84.84 0 0 0-.302.667c.009.421.32.75.684.75h2.935c.427 0 .774-.4.774-.894v-3.604c0-.493-.347-.893-.774-.893h-2.842c-.475 0-.77.39-.777.76");
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.phm5rwbri {
  d: path("M3.004 23.88V4.89h25.99v18.99z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.ps3h6zben {
  d: path("M18.2 9.675c.064.085-.069.19-.22.303c-.152.113-.264.193-.328.107c-.064-.085.008-.246.159-.36c.151-.112.326-.135.39-.05");
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q8sarnbwy {
  fill-rule: evenodd;
  d: path("M12.408 29.89v-8.406h-2.094v8.407z");
}

.qahsn1brm {
  d: path("M18.054 16.71h-4.11v13.18h4.11z");
}

.qmj2ygbtg {
  fill: var(--svg-color--000, #000);
  d: path("M17.754 10.38a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .454.748h-.905a.46.46 0 0 1-.061-.236");
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r18win3fg {
  d: path("M29.374 24.88H2.624c-.34 0-.62-.28-.62-.62V4.51c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.r5vhzbcfw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 28.46h-1.921");
}

.r7lb1kd5g {
  d: path("M16.004 18.56c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.ro58p9b2v {
  d: path("M14.71 10.276c0-.29-.235-.482-.299-.54l-.289.28l.178.361z");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.rwr3-6x4g {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.644 8.023c-.257-.184-.899-.51-1.657-.382");
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s5ydg5rnt {
  d: path("M16.004 15.39c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.tp0kp63lp {
  stop-color: var(--svg-color--bfaaba, #BFAABA);
}

.u002vnx_k {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.473 9.215c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.373-1.13");
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.u44n60b3i {
  stop-color: var(--svg-color--ffe243, #FFE243);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
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

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6j97yb7y {
  d: path("M20.94 4.231c.514.178.976.537 1.268 1.053a2.37 2.37 0 0 1-.106 2.529c-.175.258-.27.564-.27.875v1.19a1.75 1.75 0 0 0-.669-.27l.079-1.607a1.45 1.45 0 0 0-1.38-1.434H18.46a2.42 2.42 0 0 1-2.214-1.444a.665.665 0 0 0-.616-.419h-1.275c-1.847 0-3.344 1.514-3.344 3.383l.03 1.539c-.254.037-.52.122-.72.264V8.688c0-.311-.096-.617-.271-.875a2.39 2.39 0 0 1-.144-2.449c.292-.553.765-.94 1.301-1.127a2.7 2.7 0 0 0 1.386-1.112a2.33 2.33 0 0 1 2.893-.912c.383.166.813.166 1.195 0a2.3 2.3 0 0 1 .913-.188c.845 0 1.582.456 1.991 1.133c.308.51.791.88 1.354 1.073");
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vp5zpbcof {
  d: path("M20.834 8.38h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91V9.32c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.w9napxb6c {
  stop-color: var(--svg-color--f5891f, #F5891F);
}

.wb1jw4d_c {
  d: path("M16.08 13.781c-.509 0-.986-.12-1.388-.329c-.137-.07-.284.085-.198.21c.335.508.92.846 1.585.846c.666 0 1.25-.338 1.585-.846c.087-.13-.06-.28-.198-.21c-.401.21-.874.33-1.387.33");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
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

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x68xoccvj {
  d: path("M11.02 9.02a1.611 1.611 0 0 0 .138 3.203a78 78 0 0 1-.138-3.203");
}

.xeiwvjbsm {
  d: path("m16.312 5.26l-.066-.137a.665.665 0 0 0-.616-.42h-1.275c-1.847 0-3.344 1.515-3.344 3.383v.276c-.34-.26-.769-.805-.769-1.69c0-1.073.783-1.615 1.282-1.961c.14-.098.26-.18.33-.254q.047-.046.1-.104c.35-.372.974-1.033 2.063-1.322a5.5 5.5 0 0 1 1.51-.165c.473.012.806.42.806.893v1.487z");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xk_zazbvs {
  d: path("M11.213 12.133a1.64 1.64 0 0 1-.906-.31v.933c0 .894.533 1.69 1.342 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.xpkp7pbbl {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.727 13.386a.23.23 0 0 0-.272.046a.21.21 0 0 0-.023.271c.349.529.956.88 1.647.88a1.97 1.97 0 0 0 1.648-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.002c-.39.203-.85.32-1.352.32c-.496 0-.962-.117-1.352-.32Z");
}

.xpzxw-8tv {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M21.046 11.572q.058-.953.111-1.905a.957.957 0 0 1-.11 1.905");
}

.xrqg_7scz {
  stop-color: var(--svg-color--52336d, #52336D);
}

.xs6drzw0l {
  d: path("M19.062 10.263a.84.84 0 0 0-.232-.464l-.26.286l.117.229z");
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

.ydne4ly1n {
  stop-color: var(--svg-color--df9a32, #DF9A32);
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.yo8odn-5y {
  fill: var(--svg-color--000, #000);
  d: path("M14.404 10.38a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.748h.906c.036-.07.06-.15.06-.236");
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.z7egokwqq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 28.46h1.922");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zq_vtfiyq {
  d: path("M21.006 12.224q.1-1.598.185-3.195a1.611 1.611 0 0 1-.185 3.195");
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zs-gb8-xd {
  d: path("M20.946 12.133c.335-.011.65-.125.905-.31v.933c0 .894-.532 1.69-1.342 2.02c.17-.362.288-.758.346-1.18z");
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

</style>
