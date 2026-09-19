<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iODkT1c)" class="f_dqn9bui"/><path fill="url(#iCTR0Nd)" class="f_dqn9bui"/><path fill="url(#izkOAme)" class="f_dqn9bui"/><path fill="url(#iPJevdc)" class="f_dqn9bui"/><path fill="url(#izGWUPq)" class="j5bn--brl"/><path fill="url(#iowDs3d)" class="j5bn--brl"/><path class="hec31nz-i"/><path fill="url(#iNWuYjd)" class="q6d9chb6i"/><path fill="url(#idrEd2d)" class="q6d9chb6i"/><path class="wpjcl98mu"/><path fill="url(#i3pckke)" class="dvpk_pb9t"/><path fill="url(#iCQEdHe)" class="dvpk_pb9t"/><path fill="url(#i2w0M7c)" class="gc6fjsb5u"/><path fill="url(#iGFPDJb)" class="gc6fjsb5u"/><path fill="url(#iernlpd)" class="pxil76bvn"/><path fill="url(#itlPTfd)" class="pxil76bvn"/><g filter="url(#ipMaU5b)"><path fill="url(#itYvv4b)" class="ga67bmbvt"/></g><path fill="url(#imKRTgd)" class="ga67bmbvt"/><path fill="url(#iJ8AiQe)" class="ga67bmbvt"/><path fill="url(#iM0NHqd)" class="ga67bmbvt"/><path fill="url(#iUQRayd)" class="ga67bmbvt"/><g filter="url(#iKdU3Rc)"><path class="q_-3x0bre"/></g><g filter="url(#ikjPpnb)"><path fill="url(#iuHrWsc)" class="w2awujb0r"/><path fill="url(#i8K0Gob)" class="w2awujb0r"/><path fill="url(#iy1NLSb)" class="w2awujb0r"/><path fill="url(#i65aPXc)" class="w2awujb0r"/></g><g filter="url(#iSG3iwe)"><path stroke="url(#iDs80db)" class="lqmdqwbqt"/></g><path fill="url(#iw4MgNb)" class="ep1xl26do"/><g filter="url(#iCt7e0d)"><path fill="url(#iHVaL3o)" class="nizjyhbdl"/><path fill="url(#iTIdZxd)" class="nizjyhbdl"/><path fill="url(#iwzeGdA)" class="nizjyhbdl"/><path fill="url(#iO0yxYd)" class="nizjyhbdl"/><path fill="url(#iVCmwic)" class="nizjyhbdl"/></g><g filter="url(#iuAJP3b)"><path class="zxea8rb4l"/></g><g filter="url(#iPBkz3c)"><path class="mwcry6xux"/></g><g filter="url(#iRgp4pc)"><path fill="url(#i6V2O0d)" class="a_a3bkbwl"/><path fill="url(#id6x0lc)" class="a_a3bkbwl"/></g><g filter="url(#iSLLOfe)"><path fill="url(#iNjv0Ud)" class="s9_etybdf"/><path fill="url(#iXGtVkd)" class="s9_etybdf"/><path fill="url(#iqdxAFo)" class="s9_etybdf"/><path fill="url(#iVPSced)" class="s9_etybdf"/><path fill="url(#iChvd0c)" class="s9_etybdf"/></g><path class="ezbhtnvyv"/><path fill="url(#ivA57zd)" class="yrvy1um-n"/><path class="r0psavbkl"/><g filter="url(#i6tLJ8b)"><path class="z9nfyenkj"/><path fill="url(#iVNJN4c)" class="jmpwsm3qn"/></g><g filter="url(#ixVJ3ve)"><path fill="url(#iHu7Cxd)" class="vil7z8bvl"/></g><path class="p0efj3bpa"/><path fill="url(#iQ5Nwcd)" class="c6nycvb2a"/><path class="zoccuzhds"/><g filter="url(#islfrtb)"><path fill="url(#iabQf0b)" class="ggpj3rncf"/></g><g filter="url(#iut2tmb)"><ellipse transform="rotate(-27.914 12.004 12.866)" class="hhsu1nz5n"/><ellipse fill="url(#ivr8oac)" transform="rotate(-27.914 12.004 12.866)" class="d3edp4b4u"/></g><path fill="url(#itmeTYX)" class="dngd2dbzk"/><path fill="url(#i4cfNuB)" class="dngd2dbzk"/><path fill="url(#iaeOHOc)" class="dngd2dbzk"/><path fill="url(#iX8ChUc)" class="nal96ybpi"/><path fill="url(#isvUFub)" class="nal96ybpi"/><g filter="url(#iaZLhEe)"><path class="ik2qgibwj"/></g><g filter="url(#iuCcuub)"><path class="ta5vx1bgg"/></g><g filter="url(#iJr4beA)"><path class="cjcnthbvh"/></g><g filter="url(#itDf3kd)"><path class="lt1z663xi"/></g><g filter="url(#iboKHTe)"><path fill="url(#iRqeX2d)" class="djxyedkfl"/><path fill="url(#idwqwNd)" class="djxyedkfl"/><path fill="url(#i39Ji2b)" class="djxyedkfl"/><path fill="url(#i6BR3Oc)" class="djxyedkfl"/><path fill="url(#iSKB3NS)" class="djxyedkfl"/></g><path fill="url(#iHDDABd)" class="djxyedkfl"/><path fill="url(#iKIATJP)" class="lsh_h0bry"/><path fill="url(#iNiqr2b)" class="lsh_h0bry"/><path fill="url(#iiGlCCe)" class="lslgy3bhv"/><path fill="url(#ihOm0xb)" class="lslgy3bhv"/><g filter="url(#iY1LG5b)"><circle fill="url(#iMW3MDe)" class="yj0fj8b7g"/><circle fill="url(#ikkwKQe)" class="yj0fj8b7g"/><circle fill="url(#i847jRd)" class="yj0fj8b7g"/></g><g filter="url(#iWbbwGb)"><path fill="url(#ibYocKd)" clip-rule="evenodd" class="cra6babxk"/></g><path fill="url(#iI29QDc)" clip-rule="evenodd" class="cra6babxk"/><g filter="url(#ibXT4Db)"><path fill="url(#iPqeiHe)" clip-rule="evenodd" class="skh-3d3mm"/></g><g filter="url(#iW1mA5b)"><circle stroke="url(#ijdHIVd)" class="jtnrtob6n"/></g><g filter="url(#iRoenbc)"><circle stroke="url(#iy9lkAe)" class="z35u5jb7x"/></g><g filter="url(#iLeSBqc)"><circle stroke="url(#iBN2qsc)" class="l4c37zijh"/></g><g filter="url(#iqs2W8g)"><circle stroke="url(#is8VCTb)" class="xy4r3kbok"/></g><defs><radialGradient id="iODkT1c" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.2 14.197)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="qwzbgbcpc"/><stop offset="1" class="yrgygrb-x"/></radialGradient><radialGradient id="iCTR0Nd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90627 -10.81244 15.55864 -11.37678 17.382 30.471)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="znj-7lelt"/><stop offset="1" class="w53rld2zh"/></radialGradient><radialGradient id="izkOAme" cx="0" cy="0" r="1" gradientTransform="matrix(-10.23463 3.91089 -1.18367 -3.09762 12.577 19.086)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u-ogyggtr"/><stop offset="1" class="tr4934b7k"/></radialGradient><radialGradient id="iPJevdc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.46 29.966)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="pujgjpbud"/><stop offset="1" class="dstba7uva"/></radialGradient><radialGradient id="izGWUPq" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.49 29.188)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="teikdvrbz"/><stop offset="1" class="v5czltblq"/></radialGradient><radialGradient id="iowDs3d" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.49 29.966)" gradientUnits="userSpaceOnUse"><stop class="gbso5obkm"/><stop offset="1" class="x7u0pvbam"/></radialGradient><radialGradient id="iNWuYjd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.224 29.966)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="ajnorac8k"/><stop offset="1" class="o0jyspbad"/></radialGradient><radialGradient id="idrEd2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.224 29.966)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="w5_5qkbkk"/><stop offset="1" class="h6pm4_bbg"/></radialGradient><radialGradient id="i3pckke" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.614 19.602)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="goe-gxbsc"/><stop offset="1" class="xopp2n_uw"/></radialGradient><radialGradient id="iCQEdHe" cx="0" cy="0" r="1" gradientTransform="rotate(139.583 4.321 13.598)scale(2.48229 1.07513)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="adrtxocdw"/><stop offset="1" class="dy253plrj"/></radialGradient><radialGradient id="i2w0M7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.88352 3.77609 -4.4857 -1.04955 20.109 14.844)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iGFPDJb" cx="0" cy="0" r="1" gradientTransform="matrix(.29708 .40743 -.34612 .25238 19.353 15.116)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iernlpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.35015 3.97377 -1.80626 .6137 8.87 14.962)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="itlPTfd" cx="0" cy="0" r="1" gradientTransform="matrix(.32255 1.01009 -.88606 .28294 9.54 14.954)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="itYvv4b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.29489 0 0 -9.3666 17.333 13.89)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="imKRTgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.42924 13.3401 0 14.293 20.307)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="iJ8AiQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.40772 6.18017 -2.27208 -.1499 19.712 13.656)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iM0NHqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.43199 1.72404 0 12.371 12.695)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iUQRayd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.55493 2.01679 0 17.01 12.278)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iDs80db" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 21.371 -2.78)scale(.7192 2.0929)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iw4MgNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72998 2.93689 0 14.49 17.476)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iTIdZxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.7923 10.2628 0 9.193 12.288)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iwzeGdA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.67923 6.51888 0 19.412 12.288)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iO0yxYd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.15917 -1.4593 .77717 -2.21504 18.648 5.932)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iVCmwic" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 2.928 14.286)scale(1.75275 4.05855)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="i6V2O0d" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 6.868 4.18)scale(4.09903 1.14086)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="id6x0lc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25944 -5.16078 5.71761 3.61112 8.99 10.6)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iNjv0Ud" cx="0" cy="0" r="1" gradientTransform="matrix(3.4292 .8111 -.45362 1.91784 18.156 6.955)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iXGtVkd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.188 .14)scale(4.33672 2.41855)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iqdxAFo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32413 -2.23053 1.59764 -.94842 19.056 11.314)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iVPSced" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 9.268 4.562)scale(4.99786 5.40288)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="iChvd0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.11884 .38865 -1.77686 -.5433 17.986 6.71)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="ivA57zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82172 -1.30704 0 16.7 12.963)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iVNJN4c" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.429 2.491)scale(.38274 .52695)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQ5Nwcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82176 -1.30711 0 12.28 12.963)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ivr8oac" cx="0" cy="0" r="1" gradientTransform="matrix(-.00783 -.4999 .6009 -.0094 11.989 13.184)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4cfNuB" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.027 19.126)scale(2.35954 2.25118)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iaeOHOc" cx="0" cy="0" r="1" gradientTransform="matrix(.79788 -1.09496 .9178 .66879 19.531 13.528)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="isvUFub" cx="0" cy="0" r="1" gradientTransform="matrix(-.41817 2.10264 -2.06709 -.4111 9.159 13.146)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="idwqwNd" cx="0" cy="0" r="1" gradientTransform="rotate(29.165 -4.035 35.206)scale(7.08585 4.36379)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="y5q1mwb4n"/><stop offset="1" class="wg35f48yx"/></radialGradient><radialGradient id="i39Ji2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 .5 -.49802 -.43577 23.458 5.446)" gradientUnits="userSpaceOnUse"><stop offset=".089" class="hhhm45baq"/><stop offset="1" class="w-7-nyb5u"/></radialGradient><radialGradient id="i6BR3Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 .33637 -.10706 -.85537 21.535 7.298)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="jnxl-jbuy"/><stop offset="1" class="g-rk0ebtv"/></radialGradient><radialGradient id="iSKB3NS" cx="0" cy="0" r="1" gradientTransform="rotate(-116.563 13.81 -3.865)scale(.4193 2.2743)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="gh5qv9b-h"/><stop offset="1" class="ft0qf3z8a"/></radialGradient><radialGradient id="iHDDABd" cx="0" cy="0" r="1" gradientTransform="rotate(62.85 3.126 16.036)scale(1.91228 1.72006)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="p4i2fcbpl"/><stop offset="1" class="apqz6whpk"/></radialGradient><radialGradient id="iMW3MDe" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.676 7.986)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="ikkwKQe" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.68 7.957)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="i847jRd" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.455 7.52)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="ibYocKd" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.483 10.707)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="iPqeiHe" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.629 8.883)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="ipMaU5b" width="10.851" height="12.7" x="9.361" y="7.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_21"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_21" result="effect2_innerShadow_4002_21"/></filter><filter id="iKdU3Rc" width="3.901" height="4.937" x="12.329" y="12.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".5"/></filter><filter id="ikjPpnb" width="2.101" height="3.137" x="13.439" y="12.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".05"/></filter><filter id="iSG3iwe" width="3.76" height="1.587" x="12.609" y="16.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".05"/></filter><filter id="iCt7e0d" width="13.038" height="8.457" x="7.97" y="4.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_21"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_21" result="effect2_innerShadow_4002_21"/></filter><filter id="iuAJP3b" width="2.368" height="1.203" x="16.099" y="10.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_21"/></filter><filter id="iPBkz3c" width="2.368" height="1.188" x="10.775" y="10.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_21"/></filter><filter id="iRgp4pc" width="6.662" height="6.062" x="8.334" y="5.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".125"/></filter><filter id="iSLLOfe" width="6.44" height="5.806" x="14.328" y="6.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".125"/></filter><filter id="i6tLJ8b" width=".794" height=".702" x="15.957" y="12.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".05"/></filter><filter id="ixVJ3ve" width=".897" height=".92" x="16.809" y="12.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".1"/></filter><filter id="islfrtb" width=".993" height="1.048" x="12.309" y="12.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".1"/></filter><filter id="iut2tmb" width=".921" height=".71" x="11.543" y="12.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".05"/></filter><filter id="iaZLhEe" width="1.34" height="2.404" x="8.383" y="12.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".125"/></filter><filter id="iuCcuub" width="1.459" height="2.428" x="19.265" y="12.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".125"/></filter><filter id="iJr4beA" width="2.426" height="1.166" x="10.698" y="10.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".125"/></filter><filter id="itDf3kd" width="2.426" height="1.166" x="16.044" y="10.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".125"/></filter><filter id="iboKHTe" width="9.109" height="4.371" x="14.746" y="4.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.545098 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_21"/></filter><filter id="iY1LG5b" width=".726" height=".726" x="23.512" y="7.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_21"/></filter><filter id="iWbbwGb" width="3.834" height="4.387" x="21.054" y="7.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_21"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_21" result="effect2_innerShadow_4002_21"/></filter><filter id="ibXT4Db" width="4.283" height="3.734" x="24.252" y="6.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_21"/></filter><filter id="iW1mA5b" width="3.843" height="3.843" x="24.723" y="6.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".1"/></filter><filter id="iRoenbc" width="2.734" height="2.734" x="25.278" y="7.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".1"/></filter><filter id="iLeSBqc" width="2.734" height="2.734" x="21.629" y="9.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".1"/></filter><filter id="iqs2W8g" width="3.805" height="3.805" x="21.093" y="8.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_21" stdDeviation=".1"/></filter><linearGradient id="iuHrWsc" x1="14.489" x2="15.355" y1="14.73" y2="14.73" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="i8K0Gob" x1="13.403" x2="14.491" y1="14.572" y2="14.632" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iy1NLSb" x1="14.489" x2="14.489" y1="15.134" y2="15.997" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="i65aPXc" x1="14.489" x2="14.489" y1="12.857" y2="13.282" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iHVaL3o" x1="19.922" x2="9.668" y1="8.155" y2="8.155" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iHu7Cxd" x1="17.487" x2="17.169" y1="13.017" y2="13.213" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iabQf0b" x1="13.032" x2="12.715" y1="13.017" y2="13.213" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itmeTYX" x1="21.008" x2="19.786" y1="13.045" y2="15.249" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iX8ChUc" x1="8.565" x2="10.042" y1="13.758" y2="13.629" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iRqeX2d" x1="23.605" x2="17.52" y1="5.571" y2="9.258" gradientUnits="userSpaceOnUse"><stop class="m-7wcrpke"/><stop offset="1" class="y9i32rbed"/></linearGradient><linearGradient id="iKIATJP" x1="25.035" x2="23.843" y1="5.66" y2="5.315" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iNiqr2b" x1="23.887" x2="23.961" y1="7.153" y2="6.864" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iiGlCCe" x1="22.973" x2="23.238" y1="8.008" y2="6.711" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="ihOm0xb" x1="24.384" x2="24.186" y1="8.09" y2="8.034" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="iI29QDc" x1="23.723" x2="23.664" y1="8.18" y2="8.406" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="ijdHIVd" x1="24.973" x2="28.163" y1="8.782" y2="7.31" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="iy9lkAe" x1="25.528" x2="27.66" y1="8.66" y2="7.676" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iBN2qsc" x1="21.879" x2="24.011" y1="10.674" y2="9.69" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="is8VCTb" x1="24.648" x2="22.996" y1="9.887" y2="10.428" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-haircut" /></template>
<style>
.a_a3bkbwl {
  d: path("m14.725 8.203l-.067-.139a.67.67 0 0 0-.623-.423h-1.29c-1.869 0-3.384 1.532-3.384 3.422v.279c-.344-.262-.777-.815-.777-1.71c0-1.085.792-1.634 1.297-1.984c.142-.099.262-.182.335-.257l.1-.106c.354-.375.985-1.044 2.087-1.337a5.5 5.5 0 0 1 1.537-.166c.473.012.806.42.806.893v1.514z");
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

.adrtxocdw {
  stop-color: var(--svg-color--ffc328, #FFC328);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.ajnorac8k {
  stop-color: var(--svg-color--e36750, #E36750);
  stop-opacity: 0;
}

.apqz6whpk {
  stop-color: var(--svg-color--f3d037, #F3D037);
  stop-opacity: 0;
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
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

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c6nycvb2a {
  d: path("M12.277 12.48a.904.904 0 0 0-.87 1.142h1.745a1 1 0 0 0 .033-.239a.91.91 0 0 0-.908-.903");
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.cjcnthbvh {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.073 11.046c.26-.187.91-.516 1.676-.387");
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

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cra6babxk {
  fill-rule: evenodd;
  d: path("M23.099 8.053a.1.1 0 0 0-.124.068l-.104.357a.22.22 0 0 1-.174.148a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.101-.348a.1.1 0 0 0-.068-.124zm.74 2.39a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d3edp4b4u {
  cx: 12.004px;
  cy: 12.866px;
  rx: 0.394px;
  ry: 0.2px;
}

.djxyedkfl {
  d: path("M18.614 9.29c3.492-.378 4.66-1.907 4.922-2.868c.055-.17.122-.601 0-.957c-.097-.285-.437-.348-.593.067c-.367.89-1.172 1.304-2.04 1.453c-.866.148-1.655.226-3.062-.399c-1.004-.446-1.578-.61-2.18-.406c-.601.203-1.195.86-.773 1.867c.376.898 1.125 1.524 3.726 1.242");
}

.dngd2dbzk {
  d: path("M19.474 15.249q.102-1.617.187-3.232a1.63 1.63 0 0 1-.187 3.232");
}

.dstba7uva {
  stop-color: var(--svg-color--ff7543, #FF7543);
  stop-opacity: 0;
}

.dvpk_pb9t {
  d: path("M12.545 18.586h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.713-1.992-1.813z");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.dy253plrj {
  stop-color: var(--svg-color--ffc328, #FFC328);
  stop-opacity: 0;
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ep1xl26do {
  d: path("M14.49 16.825c-.515 0-.998-.122-1.404-.333c-.139-.07-.288.085-.2.211c.339.515.93.857 1.603.857c.674 0 1.265-.342 1.604-.857c.087-.13-.062-.282-.2-.211a3 3 0 0 1-1.404.332");
}

.ezbhtnvyv {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.911 12.204c.662 0 1.22.456 1.372 1.073a.278.278 0 0 1-.27.345h-2.26a.233.233 0 0 1-.23-.275a1.416 1.416 0 0 1 1.388-1.143");
}

.f_dqn9bui {
  d: path("M3.515 29.503c0-5.915 4.854-10.71 10.842-10.71s10.842 4.795 10.842 10.71v.463H3.515z");
}

.ft0qf3z8a {
  stop-color: var(--svg-color--b47731, #B47731);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-rk0ebtv {
  stop-color: var(--svg-color--faa429, #FAA429);
  stop-opacity: 0;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.ga67bmbvt {
  d: path("M9.602 16.691a3.966 3.966 0 0 0 3.936 3.45h1.91a3.966 3.966 0 0 0 3.936-3.45c.12-1.908.24-3.808.328-5.715a1.47 1.47 0 0 0-1.396-1.45h-1.418c-.967 0-1.843-.57-2.24-1.462a.67.67 0 0 0-.623-.423h-1.29c-1.87 0-3.384 1.532-3.384 3.422c0 1.885.118 3.739.241 5.628");
}

.gbso5obkm {
  stop-color: var(--svg-color--ff5130, #FF5130);
}

.gc6fjsb5u {
  d: path("M19.413 15.157c.34-.011.658-.127.916-.313v.943a2.2 2.2 0 0 1-1.358 2.045q.26-.553.35-1.195z");
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.ggpj3rncf {
  d: path("M13.103 13.277c0-.292-.238-.487-.302-.546l-.292.283l.18.365z");
}

.gh5qv9b-h {
  stop-color: var(--svg-color--b47731, #B47731);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.goe-gxbsc {
  stop-color: var(--svg-color--ea7908, #EA7908);
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h6pm4_bbg {
  stop-color: var(--svg-color--ff6640, #FF6640);
  stop-opacity: 0;
}

.hec31nz-i {
  fill: var(--svg-color--ff4f19, #FF4F19);
  d: path("M7.224 21.437c-2.273 1.963-3.71 4.849-3.71 8.066v.463h3.71z");
}

.hhhm45baq {
  stop-color: var(--svg-color--ffc432, #FFC432);
}

.hhsu1nz5n {
  cx: 12.004px;
  cy: 12.866px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.394px;
  ry: 0.2px;
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
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

.ik2qgibwj {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M9.388 12.678a.968.968 0 0 0 .084 1.903a79 79 0 0 1-.084-1.903");
}

.j5bn--brl {
  d: path("M21.49 29.966h3.71v-.463c0-3.217-1.437-6.103-3.71-8.066z");
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.jmpwsm3qn {
  d: path("M16.634 12.671c.065.086-.07.191-.223.305c-.153.115-.266.195-.33.109c-.065-.086.007-.249.16-.363s.329-.137.393-.051");
}

.jnxl-jbuy {
  stop-color: var(--svg-color--da8219, #DA8219);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jtnrtob6n {
  cx: 26.645px;
  cy: 8.414px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
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

.l4c37zijh {
  cx: 22.996px;
  cy: 10.428px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lqmdqwbqt {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.12 16.425a.23.23 0 0 0-.273.047a.214.214 0 0 0-.024.273c.353.535.967.89 1.666.89c.7 0 1.314-.356 1.666-.89a.216.216 0 0 0-.023-.275a.23.23 0 0 0-.274-.045a2.95 2.95 0 0 1-1.369.325c-.502 0-.973-.119-1.368-.325Z");
}

.lsh_h0bry {
  d: path("M24.428 3.254L23.04 8.085l1.187.345l1.071-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.lslgy3bhv {
  d: path("m19.78 5.831l5.42 1.536l-.338 1.189l-4.313-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.lt1z663xi {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.096 10.999c-.26-.187-.91-.515-1.677-.386");
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m-7wcrpke {
  stop-color: var(--svg-color--e3871a, #E3871A);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mwcry6xux {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M11.035 10.762a2.8 2.8 0 0 1 1.761-.364a.28.28 0 1 1-.068.558a2.25 2.25 0 0 0-1.405.288q-.052.031-.076.049l-.017.012l-.002.002a.281.281 0 0 1-.344-.444z");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nal96ybpi {
  d: path("M9.37 12.008a1.63 1.63 0 0 0 .14 3.241a79 79 0 0 1-.14-3.24");
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nizjyhbdl {
  d: path("M19.406 7.163a2.35 2.35 0 0 1 1.284 1.064a2.4 2.4 0 0 1-.107 2.56c-.177.26-.274.57-.274.884v1.204c-.19-.132-.44-.23-.676-.272l.08-1.627a1.47 1.47 0 0 0-1.397-1.45h-1.418c-.967 0-1.843-.57-2.24-1.462a.67.67 0 0 0-.623-.423h-1.29c-1.869 0-3.384 1.532-3.384 3.422l.031 1.557a1.7 1.7 0 0 0-.73.267v-1.216a1.6 1.6 0 0 0-.273-.885a2.42 2.42 0 0 1-.145-2.477c.295-.56.773-.95 1.316-1.14a2.7 2.7 0 0 0 1.402-1.125a2.355 2.355 0 0 1 2.928-.924a1.5 1.5 0 0 0 1.208 0c.285-.12.596-.19.924-.19c.854 0 1.601.462 2.015 1.146c.311.516.8.891 1.37 1.087");
}

.o0jyspbad {
  stop-color: var(--svg-color--e36750, #E36750);
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p0efj3bpa {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.068 12.204c-.662 0-1.22.456-1.373 1.072a.278.278 0 0 0 .272.346h2.26a.233.233 0 0 0 .23-.276a1.42 1.42 0 0 0-1.39-1.142");
}

.p4i2fcbpl {
  stop-color: var(--svg-color--f3d037, #F3D037);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
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

.pujgjpbud {
  stop-color: var(--svg-color--ff7543, #FF7543);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.pxil76bvn {
  d: path("M9.566 15.157a1.66 1.66 0 0 1-.917-.313v.943a2.2 2.2 0 0 0 1.359 2.045a4.1 4.1 0 0 1-.35-1.195z");
}

.q_-3x0bre {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m13.997 13.365l-.643 1.862c-.11.383.154.766.527.766h.797c.373 0 .637-.389.527-.766l-.538-1.862c-.116-.412-.55-.412-.67 0");
}

.q6d9chb6i {
  d: path("M7.224 21.437c-2.273 1.963-3.71 4.849-3.71 8.066v.463h3.71z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwzbgbcpc {
  stop-color: var(--svg-color--ff702c, #FF702C);
}

.r0psavbkl {
  fill: var(--svg-color--000, #000);
  d: path("M16.184 13.383c0-.287.23-.517.517-.517a.516.516 0 0 1 .46.756h-.916a.47.47 0 0 1-.061-.239");
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s9_etybdf {
  d: path("m19.769 11.618l-.03-.639c-.01-.773-.65-1.411-1.423-1.444h-1.418c-.9 0-1.721-.492-2.151-1.275c0 0-.063-.146-.127-.395c-.251-.971.675-1.713 1.66-1.523c.991.19 2.125.523 2.961 1.069c1.767 1.152 1.458 3.23.528 4.207");
}

.skh-3d3mm {
  fill-rule: evenodd;
  d: path("M24.543 7.266a.1.1 0 0 1 .123-.071l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.172l-.351-.093a.1.1 0 0 1-.07-.123zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.444");
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.ta5vx1bgg {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M19.515 14.59q.058-.965.112-1.928a.968.968 0 0 1-.112 1.927");
}

.teikdvrbz {
  stop-color: var(--svg-color--ff7646, #FF7646);
}

.tr4934b7k {
  stop-color: var(--svg-color--ff5915, #FF5915);
  stop-opacity: 0;
}

.u-ogyggtr {
  stop-color: var(--svg-color--e73f04, #E73F04);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.v5czltblq {
  stop-color: var(--svg-color--ff6635, #FF6635);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vil7z8bvl {
  d: path("M17.506 13.264a.85.85 0 0 0-.234-.468l-.263.289l.119.23z");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.w-7-nyb5u {
  stop-color: var(--svg-color--ffc432, #FFC432);
  stop-opacity: 0;
}

.w2awujb0r {
  d: path("m14.102 13.167l-.538 1.862c-.11.383.153.766.527.766h.797c.373 0 .637-.39.527-.766l-.538-1.862c-.116-.413-.654-.413-.775 0");
}

.w5_5qkbkk {
  stop-color: var(--svg-color--ff6640, #FF6640);
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.w53rld2zh {
  stop-color: var(--svg-color--e65d38, #E65D38);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wg35f48yx {
  stop-color: var(--svg-color--fe9a28, #FE9A28);
  stop-opacity: 0;
}

.wpjcl98mu {
  fill: var(--svg-color--ffaa16, #FFAA16);
  d: path("M12.545 18.586h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.713-1.992-1.813z");
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

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.x7u0pvbam {
  stop-color: var(--svg-color--ff5130, #FF5130);
  stop-opacity: 0;
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xopp2n_uw {
  stop-color: var(--svg-color--ea7908, #EA7908);
  stop-opacity: 0;
}

.xy4r3kbok {
  cx: 22.996px;
  cy: 10.428px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.y5q1mwb4n {
  stop-color: var(--svg-color--ffd435, #FFD435);
}

.y9i32rbed {
  stop-color: var(--svg-color--fe9a2b, #FE9A2B);
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.yj0fj8b7g {
  cx: 23.825px;
  cy: 7.61px;
  r: 0.313px;
}

.yrgygrb-x {
  stop-color: var(--svg-color--ff521f, #FF521F);
}

.yrvy1um-n {
  d: path("M16.701 12.48a.904.904 0 0 1 .871 1.142h-1.746a.907.907 0 0 1 .875-1.142");
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z35u5jb7x {
  cx: 26.645px;
  cy: 8.414px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.z9nfyenkj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.634 12.671c.065.086-.07.191-.223.305c-.153.115-.266.195-.33.109c-.065-.086.007-.249.16-.363s.329-.137.393-.051");
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zi0lb2bns {
  stop-color: var(--svg-color--ff5185, #FF5185);
  stop-opacity: 0;
}

.zk512ndyg {
  stop-color: var(--svg-color--a4888c, #A4888C);
}

.zl0fwhbas {
  stop-color: var(--svg-color--a28b95, #A28B95);
}

.znj-7lelt {
  stop-color: var(--svg-color--e65d38, #E65D38);
  stop-opacity: 0;
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

.zoccuzhds {
  fill: var(--svg-color--000, #000);
  d: path("M12.795 13.383a.515.515 0 0 0-.518-.517a.516.516 0 0 0-.46.756h.916a.5.5 0 0 0 .062-.239");
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zxea8rb4l {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M18.27 10.873a1.9 1.9 0 0 0-.696-.417c-.308-.097-.694-.123-1.228-.058a.28.28 0 0 0 .068.558c.487-.06.786-.029.991.036c.2.063.337.165.496.304a.281.281 0 0 0 .369-.423");
}

</style>
