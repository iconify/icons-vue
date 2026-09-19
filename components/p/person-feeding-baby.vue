<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#izDIpGI)" class="hc-rroyys"/><path fill="url(#i6vOmTb)" class="f799e9b5y"/><path fill="url(#i13OAIc)" class="fjwei2sqt"/><path fill="url(#iPH7ksY)" class="v7mqa86aw"/><path fill="url(#iS8VRNd)" class="v7mqa86aw"/><path fill="url(#i22TuMd)" class="yur6jcbnc"/><path fill="url(#iAKF7hd)" class="yur6jcbnc"/><g filter="url(#iVb6gze)"><path fill="url(#inXPNrb)" class="t2fsv4u8r"/></g><path fill="url(#iQHt2zy)" class="t2fsv4u8r"/><path fill="url(#id6OgSU)" class="t2fsv4u8r"/><path fill="url(#ioyKrOe)" class="t2fsv4u8r"/><g filter="url(#iBkCAvb)"><path class="i-8858epm"/></g><g filter="url(#id98zvd)"><path fill="url(#ibe2JbT)" class="pi621bcbp"/><path fill="url(#iqCNEwd)" class="pi621bcbp"/><path fill="url(#if2UIZo)" class="pi621bcbp"/></g><g filter="url(#ir4P6Hb)"><path fill="url(#iv0971b)" class="i5aigkb6x"/></g><g filter="url(#iU6ZqRx)"><path stroke="url(#iz3yjSd)" class="z_bmhqbcp"/></g><path fill="url(#iSc5yvb)" class="thwuaobth"/><g filter="url(#iMCu6Sd)"><path fill="url(#idoZHkK)" class="xuzj-rmvv"/><path fill="url(#izP83Td)" class="xuzj-rmvv"/><path fill="url(#ipsXMUc)" class="xuzj-rmvv"/><path fill="url(#iNIGMSd)" class="xuzj-rmvv"/><path fill="url(#iwu48De)" class="xuzj-rmvv"/></g><g filter="url(#i3AEIzb)"><path class="ca4lblf_y"/></g><g filter="url(#iew218d)"><path class="grkp4mpkf"/></g><g filter="url(#iGGiwfd)"><path fill="url(#isVmaCc)" class="a3mmcrybx"/><path fill="url(#iJeskCk)" class="a3mmcrybx"/></g><g filter="url(#i6iGQle)"><path fill="url(#iZI5h8d)" class="khw2k1t4b"/><path fill="url(#iPU0zQu)" class="khw2k1t4b"/><path fill="url(#iRQQwUb)" class="khw2k1t4b"/><path fill="url(#iyhiJFc)" class="khw2k1t4b"/><path fill="url(#iK9tKle)" class="khw2k1t4b"/></g><path fill="url(#iPLqorb)" class="melpg4b7w"/><path fill="url(#ij6K77S)" class="melpg4b7w"/><path fill="url(#inaNFhT)" class="melpg4b7w"/><path fill="url(#iTzRaIe)" class="mnftvuoip"/><path fill="url(#ine66ec)" class="mnftvuoip"/><g filter="url(#inyG3Nc)"><path class="z8waemv6a"/></g><g filter="url(#ig7B2Ud)"><path class="eozaybb7s"/></g><g filter="url(#i1uBNpc)"><circle fill="url(#iSTMhPc)" class="ojjguhbxb"/></g><g filter="url(#iyQpoDW)"><circle fill="url(#iiBxgqd)" class="e-5kccbup"/></g><g filter="url(#iBLbMxd)"><path class="bwrde0bgj"/></g><g filter="url(#iHA6X6c)"><path class="tidk69b9o"/></g><path fill="url(#irJHsuc)" class="bgjr1qyjt"/><path fill="url(#ia0QbTb)" class="jdn_f6nvp"/><path fill="url(#iHFjznl)" class="l4ntciztz"/><path fill="url(#iqdXKHd)" class="l4ntciztz"/><path fill="url(#iYUwKyc)" class="l4ntciztz"/><path fill="url(#iB4yPLY)" class="l4ntciztz"/><path fill="url(#ikvIW7c)" class="l4ntciztz"/><path fill="url(#iNpo34c)" class="l4ntciztz"/><g filter="url(#izbPCtd)"><path fill="url(#i3WV8Wd)" class="mez46pm7q"/><path fill="url(#ivb1vbe)" class="mez46pm7q"/><path fill="url(#inLyzYA)" class="mez46pm7q"/></g><path fill="url(#iRM8afM)" class="ianmnabph"/><path fill="url(#iNWAFYd)" class="ianmnabph"/><g filter="url(#iT8SgBP)"><path fill="url(#iZdqwMd)" class="z402o6byo"/><path fill="url(#i9jtq6b)" class="z402o6byo"/></g><g filter="url(#ihtPbHb)"><path class="z01siobnd"/><path fill="url(#ilHKooD)" class="drqucsbwa"/><path fill="url(#iYWhq0y)" class="drqucsbwa"/><path fill="url(#iGJcCQb)" class="drqucsbwa"/><path fill="url(#isCxQod)" class="drqucsbwa"/></g><path fill="url(#ie2deRc)" class="x92stbbki"/><path fill="url(#iOzB4nd)" class="x92stbbki"/><path fill="url(#iyZBbHc)" class="pj4_1w2fx"/><path fill="url(#imLbKVb)" class="pj4_1w2fx"/><path fill="url(#iLLmtlc)" class="i_0ecpbqb"/><path fill="url(#iXv679d)" class="i_0ecpbqb"/><path fill="url(#ismM7ne)" class="i_0ecpbqb"/><path fill="url(#iQhZlib)" class="i_0ecpbqb"/><path fill="url(#iLXCuYI)" class="ylz5-n52e"/><path fill="url(#ieSzbIc)" class="j8ijue5pt"/><path fill="url(#ivQ4cSR)" class="uvylau6jy"/><path fill="url(#ii8Ssxs)" class="uvylau6jy"/><path fill="url(#iEEF6He)" class="uvylau6jy"/><g filter="url(#iGGFRFd)"><path stroke="url(#iklFr1C)" class="bu0uqndnd"/></g><path fill="url(#iyA1Umd)" class="gp398ybvb"/><path fill="url(#iPgXlSL)" class="gp398ybvb"/><path fill="url(#io0Bdfa)" class="kmc3_jbxl"/><g filter="url(#iGu3r4Z)"><path fill="url(#iubV9Ie)" class="k5r64gbwh"/><path fill="url(#itE5u4b)" class="k5r64gbwh"/><path fill="url(#i3oZIxd)" class="k5r64gbwh"/></g><path fill="url(#iKL3tbb)" class="cwyjx8bza"/><path fill="url(#iTTftUb)" class="cwyjx8bza"/><path fill="url(#ieERBEb)" class="cwyjx8bza"/><path class="n--7tcc6g"/><path fill="url(#ixMrWbe)" class="tr96-43js"/><path fill="url(#iOtwXrb)" class="tr96-43js"/><path fill="url(#iJDuzEd)" class="tr96-43js"/><path class="n0wuz0xqf"/><path fill="url(#imLLFQb)" class="dikpzpbpa"/><path fill="url(#iSMa81d)" class="dikpzpbpa"/><path fill="url(#iAfwRhd)" class="dikpzpbpa"/><path fill="url(#iFGROEC)" class="dikpzpbpa"/><path fill="url(#imGgQGd)" class="loiep4bfy"/><path fill="url(#iVuFGtt)" class="loiep4bfy"/><path fill="url(#ihaYkwj)" class="loiep4bfy"/><path fill="url(#icHie6d)" class="loiep4bfy"/><path fill="url(#inznrid)" class="vdq5bhtrl"/><path fill="url(#inFbUZb)" class="vdq5bhtrl"/><path fill="url(#ihXBj0w)" class="vdq5bhtrl"/><path fill="url(#itfZJGb)" class="m-9o0wbkc"/><path fill="url(#iaEPQiG)" class="m-9o0wbkc"/><path fill="url(#iDtdoVa)" class="m-9o0wbkc"/><path fill="url(#iCqdH9c)" class="m-9o0wbkc"/><g filter="url(#iAsTeVq)"><path stroke="url(#iYbYzGb)" class="fe6rv_q2a"/></g><g filter="url(#iyKyThb)" class="i5de26xkm"><path stroke="url(#iqrV6pd)" class="w2b-pkb4s"/><path stroke="url(#ivEcJOk)" class="w2b-pkb4s"/></g><g filter="url(#iuDARwb)" class="i5de26xkm"><path stroke="url(#iN9mVSn)" class="iv1-o86rw"/><path stroke="url(#i8zU91c)" class="iv1-o86rw"/></g><defs><radialGradient id="iPH7ksY" cx="0" cy="0" r="1" gradientTransform="matrix(-.21915 3.87497 -4.60316 -.26034 20.671 10.91)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iS8VRNd" cx="0" cy="0" r="1" gradientTransform="matrix(.3632 .35036 -.29763 .30854 19.974 11.309)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="i22TuMd" cx="0" cy="0" r="1" gradientTransform="matrix(2.01692 3.68428 -1.67467 .91678 9.615 12.968)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="iAKF7hd" cx="0" cy="0" r="1" gradientTransform="matrix(.49233 .94006 -.82463 .43187 10.275 12.844)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="inXPNrb" cx="0" cy="0" r="1" gradientTransform="rotate(170.068 8.432 5.997)scale(5.29856 9.37311)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iQHt2zy" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -4.59375 12.20893 5.73073 14.542 16.613)" gradientUnits="userSpaceOnUse"><stop offset=".035" class="o8a1bw32d"/><stop offset="1" class="if6ipfb_h"/></radialGradient><radialGradient id="id6OgSU" cx="0" cy="0" r="1" gradientTransform="matrix(.44919 7.35718 -3.56447 .21763 20.292 8.613)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="ioyKrOe" cx="0" cy="0" r="1" gradientTransform="rotate(80.291 1.818 13.173)scale(8.33819 12.1916)" gradientUnits="userSpaceOnUse"><stop offset=".918" class="lq18di4am"/><stop offset=".992" class="l2geonbqq"/></radialGradient><radialGradient id="iz3yjSd" cx="0" cy="0" r="1" gradientTransform="matrix(.23832 -.67917 1.97642 .69352 14.42 14.422)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iSc5yvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.126 -.71961 2.89518 -.50696 15.587 14.475)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="izP83Td" cx="0" cy="0" r="1" gradientTransform="matrix(-.99976 -5.70946 10.11608 -1.77138 9.471 10.275)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="ipsXMUc" cx="0" cy="0" r="1" gradientTransform="rotate(-99.932 13.348 -3.954)scale(3.68179 6.5234)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iNIGMSd" cx="0" cy="0" r="1" gradientTransform="rotate(-170.598 8.945 .461)scale(4.41081 2.34905)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iwu48De" cx="0" cy="0" r="1" gradientTransform="matrix(1.16146 1.31432 -3.04334 2.68939 12.413 1.664)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="isVmaCc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5608 2.03706 -.56696 -.99106 13.822 2.9)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iJeskCk" cx="0" cy="0" r="1" gradientTransform="matrix(2.32231 -5.65013 6.25976 2.57288 8.978 8.646)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iZI5h8d" cx="0" cy="0" r="1" gradientTransform="matrix(3.52051 .20762 -.11611 1.9689 17.385 3.47)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iPU0zQu" cx="0" cy="0" r="1" gradientTransform="rotate(-130.051 11.667 -.685)scale(4.34018 2.42048)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iRQQwUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69039 -1.97026 1.41121 -1.21075 19.026 7.613)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iyhiJFc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.58967 1.98832 -2.14945 -4.96161 18.538 3.15)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="iK9tKle" cx="0" cy="0" r="1" gradientTransform="matrix(-.05006 .40365 -1.8454 -.22884 17.178 3.259)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="ij6K77S" cx="0" cy="0" r="1" gradientTransform="matrix(1.01976 2.12988 -2.03207 .97293 19.42 9.233)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="inaNFhT" cx="0" cy="0" r="1" gradientTransform="matrix(.59754 -1.21714 1.02022 .50086 19.876 9.714)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="ine66ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.04928 2.14496 -2.1087 -.04844 9.587 11.127)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iSTMhPc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 14.858 -4.841)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="fmfutibqt"/><stop offset=".876" class="h5yjhacpr"/></radialGradient><radialGradient id="iiBxgqd" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 16.554 -8.977)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="iq8swxtlk"/><stop offset=".535" class="yebujlt_w"/></radialGradient><radialGradient id="irJHsuc" cx="0" cy="0" r="1" gradientTransform="matrix(2.43078 -.21576 .21899 2.46713 11.397 11.079)" gradientUnits="userSpaceOnUse"><stop offset=".528" class="ygbxxwbma"/><stop offset="1" class="imr_v6bhk"/></radialGradient><radialGradient id="ia0QbTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 16.027 10.27)" gradientUnits="userSpaceOnUse"><stop class="eekbq1fbt"/><stop offset="1" class="a_eywrbvf"/></radialGradient><radialGradient id="iYUwKyc" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 3.1875 -3.62585 .24883 8.73 20.55)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="bzi-27bxc"/><stop offset="1" class="brh-pzb_h"/></radialGradient><radialGradient id="iB4yPLY" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.48 19.27)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="lwl1xgbup"/><stop offset="1" class="kar3bi73q"/></radialGradient><radialGradient id="ikvIW7c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.687 29.925)" gradientUnits="userSpaceOnUse"><stop class="ijdg6fbam"/><stop offset="1" class="sjvismp2t"/></radialGradient><radialGradient id="i3WV8Wd" cx="0" cy="0" r="1" gradientTransform="rotate(109.107 -.28 18.414)scale(6.34981 4.72781)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="ivb1vbe" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.89 10.088)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="inLyzYA" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.199 25.644)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="iRM8afM" cx="0" cy="0" r="1" gradientTransform="matrix(-5.34372 2.81254 -2.95164 -5.608 26.417 20.988)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="iZdqwMd" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.108 12.69)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="i9jtq6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.891 25.425)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="ilHKooD" cx="0" cy="0" r="1" gradientTransform="matrix(2.60938 1.92187 -.5328 .7234 17.245 26.065)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="dubz53-6i"/><stop offset="1" class="fc5g8ruvh"/></radialGradient><radialGradient id="iYWhq0y" cx="0" cy="0" r="1" gradientTransform="matrix(3.90625 0 0 .92188 13.48 28.175)" gradientUnits="userSpaceOnUse"><stop class="dubz53-6i"/><stop offset="1" class="fc5g8ruvh"/></radialGradient><radialGradient id="iGJcCQb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -5.73004 19.355 28.862)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="b7isyt1qh"/><stop offset="1" class="mmnqgv5yf"/></radialGradient><radialGradient id="isCxQod" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -37.644 40.545)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="vw31h25pz"/><stop offset="1" class="qdgjyci2c"/></radialGradient><radialGradient id="imLbKVb" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.882 14.723)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="kcxizyr3a"/><stop offset="1" class="uz8nvn0bw"/></radialGradient><radialGradient id="iLLmtlc" cx="0" cy="0" r="1" gradientTransform="matrix(.84204 2.73001 -2.93117 .90409 6.855 19.8)" gradientUnits="userSpaceOnUse"><stop class="phzm4snim"/><stop offset="1" class="czerk-92m"/></radialGradient><radialGradient id="iXv679d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.995 20.772)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="wyqcze2zy"/><stop offset="1" class="r6dyzpbfo"/></radialGradient><radialGradient id="ismM7ne" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.253 20.41)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="r1y6vkpka"/><stop offset="1" class="xrzwqzb7j"/></radialGradient><radialGradient id="iQhZlib" cx="0" cy="0" r="1" gradientTransform="rotate(153.654 1.928 11.223)scale(2.61542 2.57494)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tz2l_he6k"/><stop offset="1" class="twkrvc03o"/></radialGradient><radialGradient id="iEEF6He" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.1 18.4)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iklFr1C" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.402 22.942)" gradientUnits="userSpaceOnUse"><stop class="gmelrdffb"/><stop offset="1" class="khl528bkl"/></radialGradient><radialGradient id="iPgXlSL" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.912 17.741)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="itE5u4b" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -34.452 34.413)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="iTTftUb" cx="0" cy="0" r="1" gradientTransform="rotate(53.038 -14.16 16.857)scale(3.87188 5.62527)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="k2dydacno"/><stop offset="1" class="x5utb7s2j"/></radialGradient><radialGradient id="ieERBEb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82813 3.21874 -1.86644 -1.06007 10.214 17.488)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="b8excebxy"/><stop offset="1" class="hnp1-q05e"/></radialGradient><radialGradient id="iOtwXrb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08606 .48023 -.48372 -1.09394 14.503 16.206)" gradientUnits="userSpaceOnUse"><stop class="wzg23bc3x"/><stop offset="1" class="tp27ezb_z"/></radialGradient><radialGradient id="iJDuzEd" cx="0" cy="0" r="1" gradientTransform="rotate(-94.844 15.026 2.637)scale(.92518 1.63477)" gradientUnits="userSpaceOnUse"><stop class="ag6qdsamj"/><stop offset="1" class="mbdelibus"/></radialGradient><radialGradient id="iSMa81d" cx="0" cy="0" r="1" gradientTransform="matrix(.1875 -.92074 2.28193 .4647 12.199 18.83)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="rvlxae6dq"/><stop offset="1" class="wxdz3ub6w"/></radialGradient><radialGradient id="iAfwRhd" cx="0" cy="0" r="1" gradientTransform="rotate(76.139 -4.21 16.328)scale(2.47842 4.24901)" gradientUnits="userSpaceOnUse"><stop offset=".749" class="s4yd9bb_d"/><stop offset="1" class="zjrohm9wd"/></radialGradient><radialGradient id="iFGROEC" cx="0" cy="0" r="1" gradientTransform="rotate(150.154 4.574 10.55)scale(1.09887 .84775)" gradientUnits="userSpaceOnUse"><stop offset=".137" class="vo33qub4y"/><stop offset="1" class="r5v36mb_f"/></radialGradient><radialGradient id="imGgQGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 .84374 -2.96419 -2.14083 11.464 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="l4z1-1b1s"/><stop offset="1" class="ri1yzijvp"/></radialGradient><radialGradient id="iVuFGtt" cx="0" cy="0" r="1" gradientTransform="rotate(-41.07 29.752 -2.144)scale(1.45077 3.00819)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="xh9neyo3y"/><stop offset="1" class="bcsnf_bcy"/></radialGradient><radialGradient id="ihaYkwj" cx="0" cy="0" r="1" gradientTransform="rotate(-84.677 17.335 3.936)scale(1.26326 3.54275)" gradientUnits="userSpaceOnUse"><stop class="wlb38ob3l"/><stop offset="1" class="en81-_tdq"/></radialGradient><radialGradient id="icHie6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 12.152 18.722)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="f8laadbbd"/><stop offset="1" class="ncukxx3rx"/></radialGradient><radialGradient id="inznrid" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33928 1.42858 -2.02518 -1.89858 10.958 19.51)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="guytmftkt"/></radialGradient><radialGradient id="inFbUZb" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 -.98437 4.71032 .82244 10.527 21.925)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="h3osul2wz"/><stop offset="1" class="iwn92ct1p"/></radialGradient><radialGradient id="ihXBj0w" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -.875 1.67102 3.163 8.292 21.035)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="ho57by_ce"/><stop offset="1" class="eq0h2gj5z"/></radialGradient><radialGradient id="iaEPQiG" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 1.105 15.795)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iDtdoVa" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .988 16.271)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iCqdH9c" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.4 10.256)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="iYbYzGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.858 21.74)" gradientUnits="userSpaceOnUse"><stop class="zmq4c2bxg"/><stop offset="1" class="trma59b_r"/></radialGradient><radialGradient id="ivEcJOk" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.569 10.713)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="ttw98lbjw"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="emm-a3pcx"/></radialGradient><radialGradient id="i8zU91c" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 18.199 9.906)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="prh97g4sh"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="ez8_35bdx"/></radialGradient><linearGradient id="izDIpGI" x1="19.314" x2="12.426" y1="18.53" y2="30.207" gradientUnits="userSpaceOnUse"><stop class="iezg62obf"/><stop offset="1" class="w444cbj2i"/></linearGradient><linearGradient id="i6vOmTb" x1="15.775" x2="17.308" y1="17.16" y2="18.144" gradientUnits="userSpaceOnUse"><stop offset=".177" class="kbxoz_bbz"/><stop offset="1" class="pvs35ab_t"/></linearGradient><linearGradient id="i13OAIc" x1="23.359" x2="27.204" y1="24.267" y2="28.843" gradientUnits="userSpaceOnUse"><stop class="d0ocakaur"/><stop offset="1" class="u_vqqhk3b"/></linearGradient><linearGradient id="ibe2JbT" x1="15.114" x2="15.968" y1="11.768" y2="11.619" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iqCNEwd" x1="14.016" x2="15.099" y1="11.8" y2="11.672" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="if2UIZo" x1="15.184" x2="15.333" y1="12.166" y2="13.017" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iv0971b" x1="14.691" x2="14.944" y1="9.731" y2="11.093" gradientUnits="userSpaceOnUse"><stop class="eyvjr2bdv"/><stop offset="1" class="bul815skd"/></linearGradient><linearGradient id="idoZHkK" x1="19.333" x2="9.226" y1="4.349" y2="6.119" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iPLqorb" x1="21.248" x2="20.424" y1="8.982" y2="11.365" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iTzRaIe" x1="9.106" x2="10.54" y1="11.832" y2="11.45" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iHFjznl" x1="9.199" x2="3.73" y1="26.238" y2="24.769" gradientUnits="userSpaceOnUse"><stop class="hbzm4jmfo"/><stop offset="1" class="hzk1ijbie"/></linearGradient><linearGradient id="iqdXKHd" x1="3.605" x2="5.417" y1="25.863" y2="26.519" gradientUnits="userSpaceOnUse"><stop class="dm21qhbor"/><stop offset="1" class="xvwmp6tlw"/></linearGradient><linearGradient id="iNpo34c" x1="9.319" x2="8.926" y1="28.256" y2="28.131" gradientUnits="userSpaceOnUse"><stop class="icorotc4i"/><stop offset="1" class="deg8fdc9j"/></linearGradient><linearGradient id="iNWAFYd" x1="24.699" x2="24.386" y1="25.269" y2="23.8" gradientUnits="userSpaceOnUse"><stop class="dy155dxdg"/><stop offset="1" class="dypnkmnss"/></linearGradient><linearGradient id="ie2deRc" x1="19.485" x2="19.485" y1="26.558" y2="29.925" gradientUnits="userSpaceOnUse"><stop class="di46q3nvv"/><stop offset="1" class="bhzzakkbd"/></linearGradient><linearGradient id="iOzB4nd" x1="19.613" x2="19.527" y1="26.488" y2="26.996" gradientUnits="userSpaceOnUse"><stop class="m9orc9b3r"/><stop offset="1" class="zegip2beb"/></linearGradient><linearGradient id="iyZBbHc" x1="26.636" x2="27.074" y1="26.706" y2="30.425" gradientUnits="userSpaceOnUse"><stop class="xyrntivgr"/><stop offset="1" class="cjhyb2bbj"/></linearGradient><linearGradient id="iLXCuYI" x1="11.234" x2="11.087" y1="21.998" y2="19.355" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="ieSzbIc" x1="12.44" x2="12.053" y1="20.189" y2="18.207" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="ivQ4cSR" x1="16.167" x2="15.386" y1="17.987" y2="20.974" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="ii8Ssxs" x1="15.295" x2="15.518" y1="21.194" y2="20.303" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iyA1Umd" x1="15.042" x2="13.917" y1="17.222" y2="21.55" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="io0Bdfa" x1="15.355" x2="14.245" y1="17.597" y2="17.238" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="iubV9Ie" x1="14.542" x2="13.313" y1="17.113" y2="21.863" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="i3oZIxd" x1="12.639" x2="12.857" y1="20.928" y2="19.85" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="iKL3tbb" x1="8.511" x2="9.054" y1="16.613" y2="21.113" gradientUnits="userSpaceOnUse"><stop class="w5h00ebej"/><stop offset="1" class="ix3yrkb0h"/></linearGradient><linearGradient id="ixMrWbe" x1="9.949" x2="11.324" y1="16.394" y2="16.214" gradientUnits="userSpaceOnUse"><stop offset=".136" class="uqhi6sb2j"/><stop offset="1" class="qynlkiyit"/></linearGradient><linearGradient id="imLLFQb" x1="9.644" x2="11.199" y1="17.316" y2="17.316" gradientUnits="userSpaceOnUse"><stop class="bmz8w2byx"/><stop offset="1" class="w6wkm7xob"/></linearGradient><linearGradient id="itfZJGb" x1="16.611" x2="16.027" y1="18.488" y2="20.988" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><linearGradient id="iqrV6pd" x1="11.49" x2="13.772" y1="11.12" y2="11.276" gradientUnits="userSpaceOnUse"><stop class="mmoejgb4j"/><stop offset="1" class="ob6i98bby"/></linearGradient><linearGradient id="iN9mVSn" x1="16.12" x2="18.402" y1="10.313" y2="10.468" gradientUnits="userSpaceOnUse"><stop class="bo389tbht"/><stop offset="1" class="aphc613gk"/></linearGradient><filter id="iVb6gze" width="11.407" height="12.677" x="9.373" y="4.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3529"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3529" result="effect2_innerShadow_4002_3529"/></filter><filter id="iBkCAvb" width="3.893" height="4.986" x="13.077" y="9.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".5"/></filter><filter id="id98zvd" width="2.093" height="3.179" x="14.15" y="9.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".05"/></filter><filter id="ir4P6Hb" width="2.093" height="3.179" x="14.049" y="9.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".05"/></filter><filter id="iU6ZqRx" width="3.717" height="1.858" x="13.582" y="12.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".05"/></filter><filter id="iMCu6Sd" width="12.924" height="9.649" x="7.735" y="1.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3529"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3529" result="effect2_innerShadow_4002_3529"/></filter><filter id="i3AEIzb" width="2.414" height=".981" x="15.942" y="7.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3529"/></filter><filter id="iew218d" width="2.273" height="1.458" x="10.806" y="7.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3529"/></filter><filter id="iGGiwfd" width="6.357" height="6.781" x="8.13" y="2.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".125"/></filter><filter id="i6iGQle" width="6.784" height="5.1" x="13.694" y="2.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".125"/></filter><filter id="inyG3Nc" width="1.508" height="2.363" x="8.885" y="10.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".125"/></filter><filter id="ig7B2Ud" width="1.515" height="2.421" x="19.57" y="8.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".125"/></filter><filter id="i1uBNpc" width="3.987" height="3.987" x="10.49" y="8.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".325"/></filter><filter id="iyQpoDW" width="3.987" height="3.987" x="15.079" y="7.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".325"/></filter><filter id="iBLbMxd" width="2.336" height="1.42" x="10.722" y="7.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".125"/></filter><filter id="iHA6X6c" width="2.369" height=".864" x="15.925" y="7.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".125"/></filter><filter id="izbPCtd" width="11.192" height="8.359" x="11.556" y="21.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3529"/></filter><filter id="iT8SgBP" width="7.407" height="8.444" x="19.138" y="18.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3529"/></filter><filter id="ihtPbHb" width="8.208" height="4.667" x="12.506" y="25.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.592157 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3529"/></filter><filter id="iGGFRFd" width="3.456" height="1.701" x="7.47" y="21.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".1"/></filter><filter id="iGu3r4Z" width="4.309" height="4.662" x="11.133" y="16.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3529"/></filter><filter id="iAsTeVq" width="3.647" height="2.753" x="6.353" y="19.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".05"/></filter><filter id="iyKyThb" width="2.323" height=".964" x="11.395" y="10.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".05"/></filter><filter id="iuDARwb" width="2.323" height=".964" x="16.025" y="9.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3529" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-feeding-baby" /></template>
<style>
.a_eywrbvf {
  stop-color: var(--svg-color--a2413a, #A2413A);
}

.a3mmcrybx {
  d: path("m14.219 5.293l-.09-.125a.67.67 0 0 0-.687-.31l-1.271.223c-1.843.322-3.072 2.094-2.746 3.958l.048.274c-.384-.199-.907-.669-1.061-1.55c-.188-1.07.498-1.748.936-2.18c.123-.123.227-.225.285-.311l.082-.122c.284-.432.79-1.2 1.826-1.678a5.6 5.6 0 0 1 1.487-.43c.468-.07.867.275.948.74l.261 1.494z");
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
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

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.ag6qdsamj {
  stop-color: var(--svg-color--caa166, #CAA166);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.aphc613gk {
  stop-color: var(--svg-color--c35e51, #C35E51);
  stop-opacity: 0;
}

.b7isyt1qh {
  stop-color: var(--svg-color--eb861b, #EB861B);
}

.b8excebxy {
  stop-color: var(--svg-color--ffb725, #FFB725);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bcsnf_bcy {
  stop-color: var(--svg-color--ffb425, #FFB425);
  stop-opacity: 0;
}

.bgjr1qyjt {
  d: path("M11.503 10.844c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.bhzzakkbd {
  stop-color: var(--svg-color--d4453a, #D4453A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bmz8w2byx {
  stop-color: var(--svg-color--f6b12c, #F6B12C);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bo389tbht {
  stop-color: var(--svg-color--c35e51, #C35E51);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.brh-pzb_h {
  stop-color: var(--svg-color--f36716, #F36716);
  stop-opacity: 0;
}

.bu0uqndnd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.87 22.958c.579.14 1.92.171 2.657-.829");
}

.bul815skd {
  stop-color: var(--svg-color--f9bd35, #F9BD35);
  stop-opacity: 0;
}

.bwrde0bgj {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.097 8.938c.225-.229.808-.664 1.586-.67");
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.bzi-27bxc {
  stop-color: var(--svg-color--f36716, #F36716);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.ca4lblf_y {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M18.12 7.509a2.75 2.75 0 0 0-1.979-.136a.281.281 0 1 0 .164.538c.443-.135.955-.138 1.525.079a.281.281 0 0 0 .29-.481");
}

.cjhyb2bbj {
  stop-color: var(--svg-color--ff5641, #FF5641);
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cwyjx8bza {
  d: path("M8.22 17.168c1.031-1.087 1.92-1.37 2.32-1.375l.797.867l-.93 3.515c-.18.315-.563.996-.695 1.153c-.164.195-.735.63-1.765.238c-.888-.338-1.15-.898-1.176-1.148c.233-1.168.649-2.358 1.45-3.25");
}

.czerk-92m {
  stop-color: var(--svg-color--cf482d, #CF482D);
}

.d0ocakaur {
  stop-color: var(--svg-color--ff3200, #FF3200);
}

.deg8fdc9j {
  stop-color: var(--svg-color--ff451c, #FF451C);
  stop-opacity: 0;
}

.di46q3nvv {
  stop-color: var(--svg-color--ce5621, #CE5621);
}

.dikpzpbpa {
  d: path("M9.76 17.308c.243.25.33.526.343.633l.484.469l2.342.407a.89.89 0 0 0 1.024-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.78-.346c-.612-.07-.945.297-.64.61");
}

.dm21qhbor {
  stop-color: var(--svg-color--d46751, #D46751);
}

.drqucsbwa {
  d: path("M17.27 25.607a.937.937 0 0 0-1.12 1.498l.93.801a.1.1 0 0 1-.062.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.dubz53-6i {
  stop-color: var(--svg-color--ffd73e, #FFD73E);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.dy155dxdg {
  stop-color: var(--svg-color--33c966, #33C966);
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dypnkmnss {
  stop-color: var(--svg-color--33c966, #33C966);
  stop-opacity: 0;
}

.e-5kccbup {
  cx: 17.072px;
  cy: 9.447px;
  r: 1.344px;
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eekbq1fbt {
  stop-color: var(--svg-color--c74c24, #C74C24);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.emm-a3pcx {
  stop-color: var(--svg-color--b6614e, #B6614E);
  stop-opacity: 0;
}

.en81-_tdq {
  stop-color: var(--svg-color--ffc52d, #FFC52D);
  stop-opacity: 0;
}

.eozaybb7s {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.043 10.762a323 323 0 0 0-.223-1.92a.969.969 0 0 1 .223 1.92");
}

.eq0h2gj5z {
  stop-color: var(--svg-color--fda537, #FDA537);
  stop-opacity: 0;
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.eyvjr2bdv {
  stop-color: var(--svg-color--f9bd35, #F9BD35);
}

.ez8_35bdx {
  stop-color: var(--svg-color--c4725e, #C4725E);
  stop-opacity: 0;
}

.f799e9b5y {
  d: path("M15.775 18.456c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.f8laadbbd {
  stop-color: var(--svg-color--df970a, #DF970A);
}

.fc5g8ruvh {
  stop-color: var(--svg-color--ffd73e, #FFD73E);
  stop-opacity: 0;
}

.fe6rv_q2a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.683 19.675c-.206.433-.319 1.449.875 2.055s1.992.148 2.242-.156");
}

.fjwei2sqt {
  d: path("m29.235 25.265l-4.94-6.05l-3.16 8.57z");
}

.fmfutibqt {
  stop-color: var(--svg-color--ffb12b, #FFB12B);
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.gp398ybvb {
  d: path("m12.029 15.96l3.172.883c.43.125.744.559.627.96l-.9 3.086c-.115.396-.532.607-1.024.474l-3.129-.883z");
}

.grkp4mpkf {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M11.01 8.665a2.8 2.8 0 0 1 1.673-.663a.281.281 0 0 1 .03.562a2.25 2.25 0 0 0-1.335.527a1 1 0 0 0-.08.075l-.003.003a.281.281 0 0 1-.416-.378z");
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.guytmftkt {
  stop-color: var(--svg-color--fba335, #FBA335);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h3osul2wz {
  stop-color: var(--svg-color--cd7a48, #CD7A48);
}

.h5yjhacpr {
  stop-color: var(--svg-color--e99420, #E99420);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.hbzm4jmfo {
  stop-color: var(--svg-color--f54c3c, #F54C3C);
}

.hc-rroyys {
  d: path("M7.245 29.925c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hnp1-q05e {
  stop-color: var(--svg-color--e1a038, #E1A038);
  stop-opacity: 0;
}

.ho57by_ce {
  stop-color: var(--svg-color--e3992c, #E3992C);
}

.hzk1ijbie {
  stop-color: var(--svg-color--e2492a, #E2492A);
}

.i_0ecpbqb {
  d: path("M10.304 21.612c-.284.88-1.448 1.292-2.6.92c-1.152-.371-1.793-1.177-1.573-2.266c.18-.888.883-1.75 2.738-1.24c1.152.372 1.719 1.706 1.435 2.586");
}

.i-8858epm {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m14.393 10.508l-.312 1.947c-.042.396.284.729.652.664l.785-.137c.368-.065.56-.494.387-.847l-.851-1.742c-.185-.387-.613-.312-.66.115");
}

.i5aigkb6x {
  d: path("m14.362 10.103l-.209 1.928c-.042.397.284.729.652.664l.785-.137c.368-.065.561-.494.388-.846l-.852-1.743c-.185-.387-.716-.294-.764.134");
}

.i5de26xkm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.ianmnabph {
  d: path("M23.535 27.085a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.icorotc4i {
  stop-color: var(--svg-color--ff451c, #FF451C);
}

.iezg62obf {
  stop-color: var(--svg-color--ff8427, #FF8427);
}

.if6ipfb_h {
  stop-color: var(--svg-color--f5b02e, #F5B02E);
  stop-opacity: 0;
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ijdg6fbam {
  stop-color: var(--svg-color--fc4a51, #FC4A51);
}

.imr_v6bhk {
  stop-color: var(--svg-color--ab4620, #AB4620);
}

.iq8swxtlk {
  stop-color: var(--svg-color--ffde30, #FFDE30);
}

.iv1-o86rw {
  d: path("M16.175 10.304c.151.14.548.37 1.063.274c.562-.107.888-.459.96-.641");
}

.iwn92ct1p {
  stop-color: var(--svg-color--fda837, #FDA837);
  stop-opacity: 0;
}

.ix3yrkb0h {
  stop-color: var(--svg-color--e49627, #E49627);
}

.j8ijue5pt {
  d: path("M10.655 18.495c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.jdn_f6nvp {
  d: path("M16.133 10.035c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k2dydacno {
  stop-color: var(--svg-color--e69828, #E69828);
  stop-opacity: 0;
}

.k5r64gbwh {
  d: path("m12.256 16.39l2.636.735c.357.104.645.406.521.797l-.779 2.703c-.096.33-.443.504-.851.394l-2.6-.734z");
}

.kar3bi73q {
  stop-color: var(--svg-color--d25e22, #D25E22);
  stop-opacity: 0;
}

.kbxoz_bbz {
  stop-color: var(--svg-color--db721c, #DB721C);
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.kcxizyr3a {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.khl528bkl {
  stop-color: var(--svg-color--ff8040, #FF8040);
  stop-opacity: 0;
}

.khw2k1t4b {
  d: path("m19.782 7.79l-.14-.625c-.144-.76-.884-1.28-1.652-1.178l-1.398.245a2.46 2.46 0 0 1-2.341-.886s-.087-.134-.194-.368c-.414-.914.37-1.804 1.373-1.788c1.01.017 2.186.15 3.105.543c1.941.832 1.995 2.932 1.247 4.057");
}

.kloinabmx {
  stop-color: var(--svg-color--c26f5c, #C26F5C);
  stop-opacity: 0;
}

.kmc3_jbxl {
  d: path("m14.915 17.023l-2.635-.734l-1.074 3.895l2.6.733c.409.11.756-.064.852-.393l.779-2.704c.123-.39-.165-.693-.522-.797");
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.l2geonbqq {
  stop-color: var(--svg-color--d8680f, #D8680F);
}

.l4ntciztz {
  d: path("m2.29 29.926l2.93-9.157c.352-1.414 2.07-2.103 3.65-1.613s2.491 2.332 2.007 3.691L8.66 29.925z");
}

.l4z1-1b1s {
  stop-color: var(--svg-color--ffd23e, #FFD23E);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.loiep4bfy {
  d: path("M8.61 18.405a.28.28 0 0 1 .134-.27c.981-.69 2.005-.304 2.383 0c.304.237 1 .79 1.363 1.083c.446.36.372.961.043 1.316c-.276.298-.752.241-.93.149L9.505 19.37c-.054-.312-.234-.562-.48-.637s-.402-.132-.414-.328");
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lq18di4am {
  stop-color: var(--svg-color--d4802a, #D4802A);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.lwl1xgbup {
  stop-color: var(--svg-color--d25e22, #D25E22);
}

.m-9o0wbkc {
  d: path("m15.544 20.691l.227.068a.5.5 0 0 0 .491-.12l.364-.352a.13.13 0 0 1 .128-.033l.315.084a.484.484 0 0 0 .252-.936l-.303-.082a.13.13 0 0 1-.097-.11l-.07-.439a.5.5 0 0 0-.36-.404l-.26-.072z");
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.m9orc9b3r {
  stop-color: var(--svg-color--ae4614, #AE4614);
}

.mbdelibus {
  stop-color: var(--svg-color--caa166, #CAA166);
  stop-opacity: 0;
}

.melpg4b7w {
  d: path("M20.117 11.42q-.179-1.611-.374-3.22a1.632 1.632 0 0 1 .374 3.22");
}

.mez46pm7q {
  d: path("M21.925 23.945c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mmnqgv5yf {
  stop-color: var(--svg-color--ffba27, #FFBA27);
  stop-opacity: 0;
}

.mmoejgb4j {
  stop-color: var(--svg-color--b16251, #B16251);
}

.mnftvuoip {
  d: path("M9.598 9.969a1.631 1.631 0 0 0 .698 3.17a79 79 0 0 1-.698-3.17");
}

.n--7tcc6g {
  fill: var(--svg-color--ffc126, #FFC126);
  d: path("M10.189 16.386c.356.125.481.331.515.453l.446.391l2.291.362a.92.92 0 0 0 1.062-.871a.913.913 0 0 0-.922-.95c-1.175.013-2.688.035-3.044.025c-.586-.015-.794.434-.348.59");
}

.n0wuz0xqf {
  fill: var(--svg-color--ffc225, #FFC225);
  d: path("M9.76 17.308c.243.25.33.526.343.633l.484.469l2.342.407a.89.89 0 0 0 1.024-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.78-.346c-.612-.07-.945.297-.64.61");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.ncukxx3rx {
  stop-color: var(--svg-color--ffd03a, #FFD03A);
  stop-opacity: 0;
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o8a1bw32d {
  stop-color: var(--svg-color--ce7829, #CE7829);
}

.ob6i98bby {
  stop-color: var(--svg-color--b16251, #B16251);
  stop-opacity: 0;
}

.ojjguhbxb {
  cx: 12.484px;
  cy: 10.175px;
  r: 1.344px;
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.phzm4snim {
  stop-color: var(--svg-color--ce6122, #CE6122);
}

.pi621bcbp {
  d: path("m14.463 10.294l-.21 1.928c-.042.397.284.73.652.665l.786-.138c.368-.064.56-.493.387-.846l-.852-1.743c-.185-.386-.715-.293-.763.134");
}

.pj4_1w2fx {
  d: path("M20.705 25.702c1.598-.23 4.567-.808 6.543-1.27c1.522-.262 2.64 1.204 2.64 2.782c0 1.37-1.022 2.236-1.746 2.618a.86.86 0 0 1-.404.093h-8.013v-3.086c0-.797.281-1 .98-1.137");
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.prh97g4sh {
  stop-color: var(--svg-color--c4725e, #C4725E);
}

.pvs35ab_t {
  stop-color: var(--svg-color--ffbd16, #FFBD16);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.qdgjyci2c {
  stop-color: var(--svg-color--e38f1d, #E38F1D);
  stop-opacity: 0;
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.qynlkiyit {
  stop-color: var(--svg-color--f5b12d, #F5B12D);
  stop-opacity: 0;
}

.r1y6vkpka {
  stop-color: var(--svg-color--b42c01, #B42C01);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r5v36mb_f {
  stop-color: var(--svg-color--ffe247, #FFE247);
  stop-opacity: 0;
}

.r6dyzpbfo {
  stop-color: var(--svg-color--a62302, #A62302);
  stop-opacity: 0;
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.ri1yzijvp {
  stop-color: var(--svg-color--ffbe24, #FFBE24);
}

.rvlxae6dq {
  stop-color: var(--svg-color--f9a325, #F9A325);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s4yd9bb_d {
  stop-color: var(--svg-color--fdb326, #FDB326);
  stop-opacity: 0;
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.sjvismp2t {
  stop-color: var(--svg-color--fc4a51, #FC4A51);
  stop-opacity: 0;
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t2fsv4u8r {
  d: path("M10.635 14.545a3.97 3.97 0 0 0 4.475 2.72l1.883-.329a3.97 3.97 0 0 0 3.284-4.08c-.212-1.9-.421-3.794-.663-5.69a1.47 1.47 0 0 0-1.627-1.188l-1.398.245a2.46 2.46 0 0 1-2.46-1.054a.67.67 0 0 0-.687-.31l-1.271.222C10.328 5.404 9.1 7.176 9.426 9.04c.325 1.858.761 3.665 1.21 5.506");
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.thwuaobth {
  d: path("M15.476 13.833a3.05 3.05 0 0 1-1.441-.085c-.149-.046-.269.134-.161.243a1.92 1.92 0 0 0 1.729.568a1.92 1.92 0 0 0 1.433-1.122c.063-.144-.11-.267-.235-.174a3 3 0 0 1-1.325.57");
}

.tidk69b9o {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.97 7.664c-.29-.14-.986-.351-1.72-.091");
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tp27ezb_z {
  stop-color: var(--svg-color--ffdf42, #FFDF42);
  stop-opacity: 0;
}

.tr96-43js {
  d: path("M10.189 16.386c.356.125.481.331.515.453l.446.391l2.291.362a.92.92 0 0 0 1.062-.871a.913.913 0 0 0-.922-.95c-1.175.013-2.688.035-3.044.025c-.586-.015-.794.434-.348.59");
}

.trma59b_r {
  stop-color: var(--svg-color--d1623d, #D1623D);
  stop-opacity: 0;
}

.ttw98lbjw {
  stop-color: var(--svg-color--b6614e, #B6614E);
}

.twkrvc03o {
  stop-color: var(--svg-color--c24713, #C24713);
}

.tz2l_he6k {
  stop-color: var(--svg-color--c24713, #C24713);
  stop-opacity: 0;
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u_vqqhk3b {
  stop-color: var(--svg-color--ff9400, #FF9400);
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.uqhi6sb2j {
  stop-color: var(--svg-color--ecaa34, #ECAA34);
}

.uvylau6jy {
  d: path("m15.62 17.79l.554.16a.15.15 0 0 1 .103.185l-.784 2.73a.15.15 0 0 1-.185.103l-.555-.16z");
}

.uz8nvn0bw {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
  stop-opacity: 0;
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v7mqa86aw {
  d: path("M20.04 11.339c.333-.07.627-.238.85-.466l.162.93a2.2 2.2 0 0 1-.985 2.25q.16-.59.139-1.24z");
}

.vdq5bhtrl {
  d: path("M8.947 20.855c-.315.22-.723.21-.906-.11c-.392-.948.72-1.579 1.5-1.597c1.167-.027 1.75.629 1.937 1.12c.188.493.227 1.477-.672 1.54c-.804.056-.847-.5-.98-.742s-.594-.41-.88-.211");
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vo33qub4y {
  stop-color: var(--svg-color--ffe247, #FFE247);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vw31h25pz {
  stop-color: var(--svg-color--e38f1d, #E38F1D);
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w2b-pkb4s {
  d: path("M11.545 11.112c.151.14.548.37 1.063.273c.562-.106.888-.458.96-.64");
}

.w444cbj2i {
  stop-color: var(--svg-color--fa362a, #FA362A);
}

.w5h00ebej {
  stop-color: var(--svg-color--dea33f, #DEA33F);
}

.w6wkm7xob {
  stop-color: var(--svg-color--ffb826, #FFB826);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wlb38ob3l {
  stop-color: var(--svg-color--cd7c46, #CD7C46);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wxdz3ub6w {
  stop-color: var(--svg-color--f9a325, #F9A325);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.wyqcze2zy {
  stop-color: var(--svg-color--a62302, #A62302);
}

.wzg23bc3x {
  stop-color: var(--svg-color--ffdf42, #FFDF42);
}

.x5utb7s2j {
  stop-color: var(--svg-color--be672a, #BE672A);
}

.x92stbbki {
  d: path("M19.088 26.708a.15.15 0 0 1 .15-.15h.643v3.367h-.793z");
}

.xh9neyo3y {
  stop-color: var(--svg-color--eea92f, #EEA92F);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xrzwqzb7j {
  stop-color: var(--svg-color--b42c01, #B42C01);
  stop-opacity: 0;
}

.xuzj-rmvv {
  d: path("M18.654 3.46a2.35 2.35 0 0 1 1.45.828c.609.737.712 1.73.335 2.54a1.6 1.6 0 0 0-.117.92l.208 1.187a1.8 1.8 0 0 0-.713-.152l-.203-1.617a1.47 1.47 0 0 0-1.627-1.189l-1.398.245a2.46 2.46 0 0 1-2.46-1.054a.67.67 0 0 0-.687-.31l-1.271.223c-1.843.322-3.072 2.094-2.745 3.957l.3 1.53a1.7 1.7 0 0 0-.674.389l-.21-1.198a1.6 1.6 0 0 0-.422-.826a2.42 2.42 0 0 1-.571-2.417a2.38 2.38 0 0 1 1.1-1.351a2.72 2.72 0 0 0 1.188-1.35a2.36 2.36 0 0 1 2.727-1.416c.41.099.839.024 1.191-.209c.26-.167.555-.29.878-.347a2.36 2.36 0 0 1 2.183.782c.397.455.943.74 1.538.835");
}

.xvwmp6tlw {
  stop-color: var(--svg-color--e6422d, #E6422D);
  stop-opacity: 0;
}

.xyrntivgr {
  stop-color: var(--svg-color--ff7c1e, #FF7C1E);
}

.yebujlt_w {
  stop-color: var(--svg-color--ffc81d, #FFC81D);
}

.ygbxxwbma {
  stop-color: var(--svg-color--993330, #993330);
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.ylz5-n52e {
  d: path("m11.935 20.525l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.yur6jcbnc {
  d: path("M10.334 13.04a1.7 1.7 0 0 1-.957-.15l.163.929a2.2 2.2 0 0 0 1.692 1.781a4.1 4.1 0 0 1-.552-1.118z");
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.z_bmhqbcp {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.058 13.676c.425.135.91.17 1.405.083c.5-.087.94-.284 1.293-.555a.23.23 0 0 1 .277-.004a.216.216 0 0 1 .071.267m-3.046.21l2.978-.24m-2.978.24l-.001-.001a.23.23 0 0 0-.261.094a.214.214 0 0 0 .024.273m.238-.367l-.184.315m3.23-.524l-.068-.03m.068.03l-.068-.03m.068.03a2 2 0 0 1-1.488 1.166a2 2 0 0 1-1.796-.59m3.216-.606a1.92 1.92 0 0 1-1.433 1.122a1.92 1.92 0 0 1-1.73-.568m-.053.052l.054-.052m-.054.052l.054-.052");
}

.z01siobnd {
  fill: var(--svg-color--ffb926, #FFB926);
  d: path("M17.27 25.607a.937.937 0 0 0-1.12 1.498l.93.801a.1.1 0 0 1-.062.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z402o6byo {
  d: path("M21.665 23.865a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.z8waemv6a {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M9.73 10.626a.969.969 0 0 0 .413 1.862q-.218-.93-.412-1.862");
}

.zegip2beb {
  stop-color: var(--svg-color--ae4614, #AE4614);
  stop-opacity: 0;
}

.zjrohm9wd {
  stop-color: var(--svg-color--d99540, #D99540);
}

.zmq4c2bxg {
  stop-color: var(--svg-color--d1623d, #D1623D);
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
