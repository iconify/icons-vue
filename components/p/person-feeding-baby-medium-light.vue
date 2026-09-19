<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iYyuwNe)" class="dzjitptyt"/><path fill="url(#i2duqtb)" class="s_51gm69o"/><path fill="url(#ipvMyDd)" class="gorl-d3ks"/><path fill="url(#i3tESIc)" class="g7osupb7r"/><path fill="url(#iyDZKJd)" class="g7osupb7r"/><path fill="url(#i3tESIc)" class="g7osupb7r"/><path fill="url(#iyDZKJd)" class="g7osupb7r"/><g filter="url(#irjaTXd)"><path fill="url(#i6H5bWv)" class="pie3lznez"/></g><path fill="url(#inB4Ffc)" class="pie3lznez"/><path fill="url(#ik2alZb)" class="pie3lznez"/><path fill="url(#ifCdx7L)" class="pie3lznez"/><path fill="url(#ikRSqAj)" class="pie3lznez"/><path fill="url(#iMNvlxc)" class="pie3lznez"/><path fill="url(#i3mSNoe)" class="pie3lznez"/><path fill="url(#i3ljuBc)" class="pie3lznez"/><g filter="url(#iF38Ifc)"><path class="xvsb4lbua"/></g><g filter="url(#iyTNHPq)"><path fill="url(#i6di1Ad)" class="xwvw-6byu"/><path fill="url(#ilZqVAH)" class="xwvw-6byu"/><path fill="url(#iswGayc)" class="xwvw-6byu"/><path fill="url(#iVu86he)" class="xwvw-6byu"/></g><g filter="url(#iTeQ5hK)"><path stroke="url(#iKFA72K)" class="lh9tgacmj"/></g><path fill="url(#iZN4pfe)" class="q4qw-3jpk"/><g filter="url(#iN4fcAe)"><path fill="url(#ivj4Vhd)" class="h3e3juv2r"/><path fill="url(#i2jV0yd)" class="h3e3juv2r"/><path fill="url(#i2ThP1c)" class="h3e3juv2r"/><path fill="url(#iHFoPfb)" class="h3e3juv2r"/><path fill="url(#incSQMd)" class="h3e3juv2r"/></g><g filter="url(#ibGiIIo)"><path class="pdc6bbcoh"/></g><g filter="url(#i2AVSde)"><path class="bwu_vnbxe"/></g><g filter="url(#iiji0ob)"><path fill="url(#i8VLqQR)" class="oyvgukskf"/><path fill="url(#iQzYeqd)" class="oyvgukskf"/></g><g filter="url(#iT2i4Tz)"><path fill="url(#iXET2SR)" class="lb1-9jboq"/><path fill="url(#icSkbyd)" class="lb1-9jboq"/><path fill="url(#i1YnMHd)" class="lb1-9jboq"/><path fill="url(#i6nWvxd)" class="lb1-9jboq"/><path fill="url(#iXCFZMd)" class="lb1-9jboq"/><path fill="url(#iPFZWpd)" class="lb1-9jboq"/></g><path fill="url(#ivGo2sc)" class="d1hejvj_q"/><path fill="url(#iND3Dvd)" class="d1hejvj_q"/><path fill="url(#ie1lOcb)" class="d1hejvj_q"/><path fill="url(#i0LPPeb)" class="n3g0g-byb"/><path fill="url(#itETcBe)" class="n3g0g-byb"/><g filter="url(#ibR6Wje)"><path class="rw9b8ul_k"/></g><g filter="url(#iuTwJMc)"><path class="a65doibwy"/></g><g filter="url(#iGJBrzd)"><path class="rwjg04fmi"/></g><g filter="url(#iYZGiEd)"><path class="ra3pdeoog"/></g><path fill="url(#idxYUlc)" class="khs5o_1jg"/><path fill="url(#icI4EIL)" class="z7o095spk"/><path fill="url(#inBg3ae)" class="z7o095spk"/><path fill="url(#iqYO8qb)" class="z7o095spk"/><path fill="url(#iOQsZVb)" class="z7o095spk"/><path fill="url(#iZ9vaBe)" class="z7o095spk"/><path fill="url(#it4o9od)" class="z7o095spk"/><g filter="url(#ihJ9Yxb)"><path fill="url(#ibw3Wgw)" class="z9xh4xkpu"/><path fill="url(#iGLeYjf)" class="z9xh4xkpu"/><path fill="url(#iJmKPxd)" class="z9xh4xkpu"/></g><path fill="url(#ip7AqGZ)" class="hcsjmwbaq"/><g filter="url(#ipSqpfd)"><path fill="url(#iIHGOsb)" class="jw0tmkgly"/><path fill="url(#iy2jlsc)" class="jw0tmkgly"/></g><g filter="url(#iOwlHRb)"><path class="gueri_bqi"/><path fill="url(#iJK0Xvc)" class="el0upzbnh"/><path fill="url(#iGpddWd)" class="el0upzbnh"/><path fill="url(#i7ccBXc)" class="el0upzbnh"/><path fill="url(#iPzQ3Hd)" class="el0upzbnh"/></g><path fill="url(#iU2QYde)" class="apj-c5bpf"/><path fill="url(#i5i5Ffe)" class="apj-c5bpf"/><path fill="url(#iW5fQgb)" class="si6i9vb1t"/><path fill="url(#in5zP8b)" class="si6i9vb1t"/><path fill="url(#i8wzsQd)" class="idwps0b8z"/><path fill="url(#iMhlLwd)" class="idwps0b8z"/><path fill="url(#imoktec)" class="idwps0b8z"/><path fill="url(#i2FOtwb)" class="idwps0b8z"/><path fill="url(#izQxWJd)" class="w0pwsab7o"/><path fill="url(#iMaxcze)" class="td96-d_gv"/><path fill="url(#iuFOzpc)" class="h15jngl9k"/><path fill="url(#ipGXH3b)" class="h15jngl9k"/><path fill="url(#iwq9VJP)" class="h15jngl9k"/><g filter="url(#ihUEoyd)"><path stroke="url(#i89FWte)" class="grpgooxhk"/></g><path fill="url(#i34MXse)" class="vs2nrrbhb"/><path fill="url(#iGM0Doe)" class="vs2nrrbhb"/><path fill="url(#iyfnKNk)" class="u2ti54bnp"/><g filter="url(#i4moELe)"><path fill="url(#iTTCvvc)" class="hki09zl4s"/><path fill="url(#iQ4pvye)" class="hki09zl4s"/><path fill="url(#imCTYek)" class="hki09zl4s"/></g><path fill="url(#iE9uMVT)" class="njemumwdh"/><path fill="url(#i4XTJve)" class="njemumwdh"/><path fill="url(#itLQSTL)" class="njemumwdh"/><path fill="url(#ilo8IId)" class="njemumwdh"/><path fill="url(#i4Cqycf)" class="njemumwdh"/><path class="qoqjsdb8z"/><path fill="url(#iMPlZvg)" class="s8qj-4x_q"/><path fill="url(#iYw3z8J)" class="s8qj-4x_q"/><path class="u6bxf4b2y"/><path fill="url(#ijlo1dd)" class="lu5a7abcq"/><path fill="url(#iL8pRhd)" class="lu5a7abcq"/><path fill="url(#iZV1BFb)" class="c2o2brscj"/><path fill="url(#iGVsUdb)" class="c2o2brscj"/><path fill="url(#iPPYZoe)" class="c2o2brscj"/><path fill="url(#iE1fa1c)" class="c2o2brscj"/><path fill="url(#ib5T59d)" class="f8w6vk9zf"/><path fill="url(#i1JTPie)" class="f8w6vk9zf"/><path fill="url(#iJm1cae)" class="f8w6vk9zf"/><path fill="url(#iHKqDzC)" class="f8w6vk9zf"/><path fill="url(#iVnPYne)" class="duzuxixvb"/><path fill="url(#i7VuqIe)" class="duzuxixvb"/><path fill="url(#igud7hz)" class="duzuxixvb"/><path fill="url(#iB0kd4f)" class="duzuxixvb"/><g filter="url(#iyMYk2d)"><path stroke="url(#iYNggRb)" class="wj5sb5bda"/></g><g filter="url(#iGh0kGk)" class="mc2zb0bvp"><path class="xohd9o-1e"/></g><g filter="url(#i8JrmkT)" class="mc2zb0bvp"><path class="o8qu79bty"/></g><g filter="url(#iOubAlV)"><circle fill="url(#i5te3xe)" class="y9as00b0p"/></g><g filter="url(#iQltYlU)"><circle fill="url(#i151UnC)" class="xhgfmqa2q"/></g><path fill="url(#icqp0Ff)" class="qklmkjbjl"/><path fill="url(#iZYYOhc)" class="pptfqcb0f"/><g filter="url(#i3gGr2d)" class="i5de26xkm"><path stroke="url(#iRHVZAV)" class="ienoccb3u"/><path stroke="url(#i9EQ1xb)" class="ienoccb3u"/></g><g filter="url(#ipbDtzX)" class="i5de26xkm"><path stroke="url(#ilv3ivb)" class="o7o0zjb4n"/><path stroke="url(#iXdWwvJ)" class="o7o0zjb4n"/></g><defs><radialGradient id="ipvMyDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05187 3.65998 -4.34777 -.06162 20.447 11.367)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="i3tESIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.7109 2.50077 -1.13671 .77768 9.395 13.403)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iyDZKJd" cx="0" cy="0" r="1" gradientTransform="matrix(.37068 1.17474 -1.0305 .32517 10.17 13.07)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="i6H5bWv" cx="0" cy="0" r="1" gradientTransform="matrix(-5.27008 .83187 -1.47157 -9.32272 17.65 11.007)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="ik2alZb" cx="0" cy="0" r="1" gradientTransform="matrix(1.21657 -.19203 .97605 6.18352 9.961 12.618)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="ifCdx7L" cx="0" cy="0" r="1" gradientTransform="matrix(2.05443 -4.09956 .92856 .46533 8.442 9.359)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="ikRSqAj" cx="0" cy="0" r="1" gradientTransform="matrix(-4.06297 -9.94161 10.95106 -4.47551 15.313 15.583)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iMNvlxc" cx="0" cy="0" r="1" gradientTransform="matrix(2.17608 .4012 -.24067 1.30541 15.938 5.718)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="i3mSNoe" cx="0" cy="0" r="1" gradientTransform="matrix(1.06867 -2.75 9.7442 3.78665 13.799 17.52)" gradientUnits="userSpaceOnUse"><stop class="b7yotfbum"/><stop offset="1" class="dqi7sbofo"/></radialGradient><radialGradient id="i3ljuBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 -2.65625 11.12703 -1.04725 15.768 18.05)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="bacrstbty"/><stop offset="1" class="wxf4d8bhs"/></radialGradient><radialGradient id="iKFA72K" cx="0" cy="0" r="1" gradientTransform="matrix(.2514 -.6797 1.97792 .73158 14.207 14.948)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="iZN4pfe" cx="0" cy="0" r="1" gradientTransform="rotate(-98.97 14.11 .938)scale(.73555 2.95934)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i2jV0yd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57803 -3.662 6.48834 -1.02416 9.296 10.69)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="i2ThP1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.57803 -3.662 6.48834 -1.02416 19.468 9.084)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iHFoPfb" cx="0" cy="0" r="1" gradientTransform="rotate(-168.091 9.005 .515)scale(3.55177 1.89156)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="incSQMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.14713 1.34289 -3.1095 2.6562 12.404 2.07)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="i8VLqQR" cx="0" cy="0" r="1" gradientTransform="rotate(151.19 6.471 3.442)scale(4.13034 1.14957)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iQzYeqd" cx="0" cy="0" r="1" gradientTransform="matrix(2.43337 -5.64868 6.25816 2.69593 8.828 9.041)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iXET2SR" cx="0" cy="0" r="1" gradientTransform="matrix(3.54057 .26855 -.1502 1.98013 17.38 3.973)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="icSkbyd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.7553 -3.39173 1.89154 -1.53661 19.634 8.375)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="i1YnMHd" cx="0" cy="0" r="1" gradientTransform="rotate(-129.665 11.4 -.369)scale(2.61377 1.87213)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="i6nWvxd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.654 1.92404 -2.07996 -5.03116 18.544 3.669)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iXCFZMd" cx="0" cy="0" r="1" gradientTransform="rotate(98.032 6.955 9.338)scale(.40952 1.87225)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iPFZWpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41331 4.10224 -10.57849 -3.64453 17.038 2.928)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iND3Dvd" cx="0" cy="0" r="1" gradientTransform="rotate(65.378 2.023 19.966)scale(2.37756 2.26838)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="ie1lOcb" cx="0" cy="0" r="1" gradientTransform="matrix(.62212 -1.21519 1.01857 .52146 19.781 10.3)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="itETcBe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72753 .0196 -.01927 -1.69831 9.823 11.975)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="iqYO8qb" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 3.1875 -3.62585 .24883 8.64 21.115)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="bzi-27bxc"/><stop offset="1" class="brh-pzb_h"/></radialGradient><radialGradient id="iOQsZVb" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.39 19.834)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="lwl1xgbup"/><stop offset="1" class="kar3bi73q"/></radialGradient><radialGradient id="iZ9vaBe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.598 30.49)" gradientUnits="userSpaceOnUse"><stop class="ijdg6fbam"/><stop offset="1" class="sjvismp2t"/></radialGradient><radialGradient id="ibw3Wgw" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 16.937 25.27)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iGLeYjf" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.968 10.39)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="iJmKPxd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 26.208)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="ip7AqGZ" cx="0" cy="0" r="1" gradientTransform="matrix(-6.038 1.01561 -1.51165 -8.987 27.271 23.319)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="iIHGOsb" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.026 12.967)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="iy2jlsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 25.99)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iJK0Xvc" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.637 40.676)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="h47r5ibay"/><stop offset="1" class="jjp_mfbio"/></radialGradient><radialGradient id="iGpddWd" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 12.924 30.49)" gradientUnits="userSpaceOnUse"><stop class="nbcoryb1h"/><stop offset="1" class="r8owzxbqs"/></radialGradient><radialGradient id="iPzQ3Hd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02913 0 0 -3.40472 19.265 29.427)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="uxh2dv17l"/><stop offset="1" class="u1zlaqbml"/></radialGradient><radialGradient id="in5zP8b" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.807 15)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="kcxizyr3a"/><stop offset="1" class="uz8nvn0bw"/></radialGradient><radialGradient id="i8wzsQd" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.765 20.365)" gradientUnits="userSpaceOnUse"><stop class="phzm4snim"/><stop offset="1" class="czerk-92m"/></radialGradient><radialGradient id="iMhlLwd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 21.337)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="wyqcze2zy"/><stop offset="1" class="r6dyzpbfo"/></radialGradient><radialGradient id="imoktec" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.163 20.974)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="r1y6vkpka"/><stop offset="1" class="xrzwqzb7j"/></radialGradient><radialGradient id="i2FOtwb" cx="0" cy="0" r="1" gradientTransform="rotate(153.654 1.817 11.495)scale(2.61542 2.57494)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tz2l_he6k"/><stop offset="1" class="twkrvc03o"/></radialGradient><radialGradient id="iwq9VJP" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.01 18.965)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="i89FWte" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 23.505)" gradientUnits="userSpaceOnUse"><stop class="gmelrdffb"/><stop offset="1" class="khl528bkl"/></radialGradient><radialGradient id="iGM0Doe" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 18.305)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iQ4pvye" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -35.729 34.5)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="i4XTJve" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.455 18.952)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="b1a3scalr"/><stop offset="1" class="z_gh6vsyy"/></radialGradient><radialGradient id="itLQSTL" cx="0" cy="0" r="1" gradientTransform="rotate(119.595 -.192 11.973)scale(3.70167 1.33422)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="ie-bysyvv"/><stop offset="1" class="bpneozbdy"/></radialGradient><radialGradient id="ilo8IId" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.275 18.606)" gradientUnits="userSpaceOnUse"><stop class="uxpb5qzbn"/><stop offset="1" class="ip8fcq0ak"/></radialGradient><radialGradient id="i4Cqycf" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 1.04772 -1.07633 .16052 9.01 21.13)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="ohwd33b2n"/><stop offset="1" class="y0dl1gblq"/></radialGradient><radialGradient id="iMPlZvg" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.72 18.014)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="nu_77rrcl"/><stop offset="1" class="dnayrdbzp"/></radialGradient><radialGradient id="iYw3z8J" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 5.21 10.061)scale(.78612 .35637)" gradientUnits="userSpaceOnUse"><stop class="sok9f40_l"/><stop offset="1" class="jg12b2kug"/></radialGradient><radialGradient id="ijlo1dd" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.503 2.53)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="sg8a2viwh"/><stop offset="1" class="vsvz-xe_v"/></radialGradient><radialGradient id="iL8pRhd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.814 18.011)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="dzyo4sbbn"/><stop offset="1" class="o-ef0ac2e"/></radialGradient><radialGradient id="iZV1BFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.51562 -5.32458 -2.85442 11.143 19.263)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="zx-utrb8d"/><stop offset="1" class="rb5pqrony"/></radialGradient><radialGradient id="iGVsUdb" cx="0" cy="0" r="1" gradientTransform="matrix(2.29688 1.78687 -.45885 .58982 11.518 19.535)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="kaygmvbyu"/><stop offset="1" class="zq2cu-lqa"/></radialGradient><radialGradient id="iPPYZoe" cx="0" cy="0" r="1" gradientTransform="rotate(136.002 2.33 12.075)scale(.96996 1.97716)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="kwfaklb2u"/><stop offset="1" class="a3cf45xpc"/></radialGradient><radialGradient id="iE1fa1c" cx="0" cy="0" r="1" gradientTransform="matrix(.48047 -.3496 .60677 .83392 8.94 19.341)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="kss7lepmr"/><stop offset="1" class="z8oy8ibbe"/></radialGradient><radialGradient id="ib5T59d" cx="0" cy="0" r="1" gradientTransform="matrix(1.09945 -1.69165 1.88005 1.2219 8.869 21.96)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="fjk2vysly"/><stop offset="1" class="pll5kd_nw"/></radialGradient><radialGradient id="i1JTPie" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .84935 -.34383 .46806 10.768 20.513)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="tjgs2ub-w"/><stop offset="1" class="jtvtg3bqw"/></radialGradient><radialGradient id="iJm1cae" cx="0" cy="0" r="1" gradientTransform="rotate(97.522 -3.873 14.703)scale(2.32995 4.84987)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="aiyo-ztfk"/><stop offset=".962" class="tlxyqtbtq"/></radialGradient><radialGradient id="iHKqDzC" cx="0" cy="0" r="1" gradientTransform="matrix(.54646 -.48802 1.62742 1.82231 7.87 21.276)" gradientUnits="userSpaceOnUse"><stop class="j4c7dkb7m"/><stop offset="1" class="gt-69vbgu"/></radialGradient><radialGradient id="i7VuqIe" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .846 16.043)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="igud7hz" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .727 16.519)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iB0kd4f" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.343 10.536)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="iYNggRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 22.305)" gradientUnits="userSpaceOnUse"><stop class="zmq4c2bxg"/><stop offset="1" class="trma59b_r"/></radialGradient><radialGradient id="i5te3xe" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 15.277 -4.485)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="pfjyiqgya"/><stop offset=".876" class="ro5jldbid"/></radialGradient><radialGradient id="i151UnC" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 16.973 -8.621)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="ps228g2nk"/><stop offset=".535" class="t9y-_dh4s"/></radialGradient><radialGradient id="icqp0Ff" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .3557 2.1855 11.307 11.643)" gradientUnits="userSpaceOnUse"><stop class="b1gl30tyq"/><stop offset="1" class="sk7ylfhdv"/></radialGradient><radialGradient id="iZYYOhc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 15.937 10.834)" gradientUnits="userSpaceOnUse"><stop class="b1gl30tyq"/><stop offset="1" class="sk7ylfhdv"/></radialGradient><radialGradient id="i9EQ1xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.479 11.278)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="yq-9ytfqn"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="bh1-orbck"/></radialGradient><radialGradient id="iXdWwvJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 18.109 10.47)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="yq-9ytfqn"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="bh1-orbck"/></radialGradient><linearGradient id="iYyuwNe" x1="19.224" x2="12.336" y1="19.094" y2="30.771" gradientUnits="userSpaceOnUse"><stop class="iezg62obf"/><stop offset="1" class="w444cbj2i"/></linearGradient><linearGradient id="i2duqtb" x1="15.685" x2="17.218" y1="17.724" y2="18.709" gradientUnits="userSpaceOnUse"><stop offset=".177" class="h186-31qp"/><stop offset="1" class="bhxj81oas"/></linearGradient><linearGradient id="inB4Ffc" x1="20.287" x2="15.899" y1="12.332" y2="13.025" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="i6di1Ad" x1="14.952" x2="15.813" y1="12.288" y2="12.152" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="ilZqVAH" x1="13.846" x2="14.938" y1="12.302" y2="12.191" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iswGayc" x1="15.015" x2="15.151" y1="12.69" y2="13.549" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iVu86he" x1="14.658" x2="14.724" y1="10.424" y2="10.847" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="ivj4Vhd" x1="19.326" x2="9.12" y1="4.891" y2="6.502" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="ivGo2sc" x1="21.175" x2="20.305" y1="9.586" y2="11.972" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="i0LPPeb" x1="8.902" x2="10.352" y1="12.252" y2="11.892" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="idxYUlc" x1="23.269" x2="27.114" y1="24.832" y2="29.408" gradientUnits="userSpaceOnUse"><stop class="d0ocakaur"/><stop offset="1" class="u_vqqhk3b"/></linearGradient><linearGradient id="icI4EIL" x1="9.109" x2="3.64" y1="26.802" y2="25.334" gradientUnits="userSpaceOnUse"><stop class="hbzm4jmfo"/><stop offset="1" class="hzk1ijbie"/></linearGradient><linearGradient id="inBg3ae" x1="3.515" x2="5.328" y1="26.427" y2="27.084" gradientUnits="userSpaceOnUse"><stop class="dm21qhbor"/><stop offset="1" class="xvwmp6tlw"/></linearGradient><linearGradient id="it4o9od" x1="9.229" x2="8.836" y1="28.82" y2="28.695" gradientUnits="userSpaceOnUse"><stop class="icorotc4i"/><stop offset="1" class="deg8fdc9j"/></linearGradient><linearGradient id="i7ccBXc" x1="18.227" x2="17.566" y1="26.764" y2="27.659" gradientUnits="userSpaceOnUse"><stop offset=".175" class="jl9fiab1w"/><stop offset="1" class="j9aoxmbfm"/></linearGradient><linearGradient id="iU2QYde" x1="19.395" x2="19.395" y1="27.123" y2="30.49" gradientUnits="userSpaceOnUse"><stop class="di46q3nvv"/><stop offset="1" class="bhzzakkbd"/></linearGradient><linearGradient id="i5i5Ffe" x1="19.523" x2="19.437" y1="27.052" y2="27.56" gradientUnits="userSpaceOnUse"><stop class="m9orc9b3r"/><stop offset="1" class="zegip2beb"/></linearGradient><linearGradient id="iW5fQgb" x1="26.546" x2="26.984" y1="27.27" y2="30.989" gradientUnits="userSpaceOnUse"><stop class="xyrntivgr"/><stop offset="1" class="cjhyb2bbj"/></linearGradient><linearGradient id="izQxWJd" x1="11.144" x2="10.997" y1="22.562" y2="19.919" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iMaxcze" x1="12.351" x2="11.964" y1="20.753" y2="18.771" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iuFOzpc" x1="16.078" x2="15.296" y1="18.552" y2="21.538" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="ipGXH3b" x1="15.205" x2="15.428" y1="21.758" y2="20.867" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="i34MXse" x1="14.953" x2="13.828" y1="17.787" y2="22.115" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="iyfnKNk" x1="15.265" x2="14.156" y1="18.162" y2="17.802" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="iTTCvvc" x1="14.453" x2="13.223" y1="17.677" y2="22.427" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="imCTYek" x1="12.549" x2="12.768" y1="21.493" y2="20.415" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="iE9uMVT" x1="8.421" x2="8.964" y1="17.177" y2="21.677" gradientUnits="userSpaceOnUse"><stop class="rvz7hrbgf"/><stop offset="1" class="c6pq05twi"/></linearGradient><linearGradient id="iVnPYne" x1="16.521" x2="15.937" y1="19.052" y2="21.552" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><linearGradient id="iRHVZAV" x1="11.4" x2="13.682" y1="11.685" y2="11.84" gradientUnits="userSpaceOnUse"><stop class="wiexblb8s"/><stop offset="1" class="cbopwmb0o"/></linearGradient><linearGradient id="ilv3ivb" x1="16.031" x2="18.312" y1="10.877" y2="11.033" gradientUnits="userSpaceOnUse"><stop class="wiexblb8s"/><stop offset="1" class="cbopwmb0o"/></linearGradient><filter id="irjaTXd" width="11.655" height="12.777" x="9.229" y="5.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3541"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3541" result="effect2_innerShadow_4002_3541"/></filter><filter id="iF38Ifc" width="3.785" height="4.938" x="12.894" y="9.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".5"/></filter><filter id="iyTNHPq" width="2.108" height="3.198" x="13.973" y="10.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".05"/></filter><filter id="iTeQ5hK" width="3.747" height="1.839" x="13.376" y="13.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".05"/></filter><filter id="iN4fcAe" width="13.036" height="9.605" x="7.6" y="1.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3541"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3541" result="effect2_innerShadow_4002_3541"/></filter><filter id="ibGiIIo" width="2.428" height="1.049" x="15.914" y="7.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3541"/></filter><filter id="i2AVSde" width="2.3" height="1.44" x="10.679" y="8.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3541"/></filter><filter id="iiji0ob" width="6.433" height="6.761" x="7.996" y="3.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".125"/></filter><filter id="iT2i4Tz" width="6.799" height="5.205" x="13.644" y="3.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".125"/></filter><filter id="ibR6Wje" width="1.498" height="2.382" x="8.686" y="10.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".125"/></filter><filter id="iuTwJMc" width="1.506" height="2.437" x="19.49" y="9.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".125"/></filter><filter id="iGJBrzd" width="2.358" height="1.398" x="10.597" y="8.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".125"/></filter><filter id="iYZGiEd" width="2.479" height=".983" x="15.851" y="7.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".125"/></filter><filter id="ihJ9Yxb" width="11.192" height="8.359" x="11.466" y="22.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3541"/></filter><filter id="ipSqpfd" width="7.407" height="8.444" x="19.048" y="19.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3541"/></filter><filter id="iOwlHRb" width="8.208" height="4.667" x="12.416" y="25.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.505882 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3541"/></filter><filter id="ihUEoyd" width="3.456" height="1.701" x="7.381" y="22.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".1"/></filter><filter id="i4moELe" width="4.309" height="4.662" x="11.043" y="16.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3541"/></filter><filter id="iyMYk2d" width="3.647" height="2.753" x="6.263" y="20.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".05"/></filter><filter id="iGh0kGk" width="2.634" height="2.141" x="16.374" y="26.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".125"/></filter><filter id="i8JrmkT" width="4.536" height="1" x="12.746" y="29.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".15"/></filter><filter id="iOubAlV" width="3.987" height="3.987" x="10.4" y="8.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".325"/></filter><filter id="iQltYlU" width="3.987" height="3.987" x="14.989" y="8.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".325"/></filter><filter id="i3gGr2d" width="2.323" height=".964" x="11.305" y="11.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".05"/></filter><filter id="ipbDtzX" width="2.323" height=".964" x="15.935" y="10.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3541" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-feeding-baby-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a3cf45xpc {
  stop-color: var(--svg-color--bf8a6b, #BF8A6B);
  stop-opacity: 0;
}

.a65doibwy {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M19.932 11.359q-.093-.969-.192-1.937a.975.975 0 0 1 .192 1.937");
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.aiyo-ztfk {
  stop-color: var(--svg-color--b56e74, #B56E74);
  stop-opacity: 0;
}

.apj-c5bpf {
  d: path("M18.998 27.273a.15.15 0 0 1 .15-.15h.643v3.367h-.793z");
}

.b1a3scalr {
  stop-color: var(--svg-color--b57176, #B57176);
  stop-opacity: 0;
}

.b1gl30tyq {
  stop-color: var(--svg-color--844c26, #844C26);
}

.b7yotfbum {
  stop-color: var(--svg-color--b87066, #B87066);
}

.bacrstbty {
  stop-color: var(--svg-color--c36256, #C36256);
}

.bh1-orbck {
  stop-color: var(--svg-color--98643a, #98643A);
  stop-opacity: 0;
}

.bhxj81oas {
  stop-color: var(--svg-color--efa27d, #EFA27D);
}

.bhzzakkbd {
  stop-color: var(--svg-color--d4453a, #D4453A);
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bpneozbdy {
  stop-color: var(--svg-color--dbac8a, #DBAC8A);
  stop-opacity: 0;
}

.brh-pzb_h {
  stop-color: var(--svg-color--f36716, #F36716);
  stop-opacity: 0;
}

.bwu_vnbxe {
  fill: var(--svg-color--8f5c2e, #8F5C2E);
  d: path("M10.89 8.882a2.83 2.83 0 0 1 1.696-.639a.283.283 0 1 1 .02.566a2.26 2.26 0 0 0-1.353.507l-.083.075l-.002.003a.283.283 0 0 1-.413-.388z");
}

.bzi-27bxc {
  stop-color: var(--svg-color--f36716, #F36716);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c2o2brscj {
  d: path("M8.521 18.97a.28.28 0 0 1 .133-.27c.981-.69 2.005-.304 2.383 0c.304.236 1 .79 1.363 1.082c.446.36.372.962.043 1.317c-.276.298-.751.24-.93.148l-2.097-1.312c-.055-.313-.235-.563-.48-.637c-.247-.074-.403-.133-.415-.328");
}

.c6pq05twi {
  stop-color: var(--svg-color--be8777, #BE8777);
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cbopwmb0o {
  stop-color: var(--svg-color--9a663d, #9A663D);
  stop-opacity: 0;
}

.cjhyb2bbj {
  stop-color: var(--svg-color--ff5641, #FF5641);
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.czerk-92m {
  stop-color: var(--svg-color--cf482d, #CF482D);
}

.d0ocakaur {
  stop-color: var(--svg-color--ff3200, #FF3200);
}

.d1hejvj_q {
  d: path("M19.995 12.021a334 334 0 0 0-.322-3.246a1.643 1.643 0 0 1 .322 3.246");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.deg8fdc9j {
  stop-color: var(--svg-color--ff451c, #FF451C);
  stop-opacity: 0;
}

.di46q3nvv {
  stop-color: var(--svg-color--ce5621, #CE5621);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm21qhbor {
  stop-color: var(--svg-color--d46751, #D46751);
}

.dnayrdbzp {
  stop-color: var(--svg-color--c7977a, #C7977A);
  stop-opacity: 0;
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.duzuxixvb {
  d: path("m15.454 21.255l.227.068a.5.5 0 0 0 .492-.12l.363-.352a.13.13 0 0 1 .128-.034l.315.084a.484.484 0 0 0 .253-.935l-.304-.083a.13.13 0 0 1-.097-.109l-.069-.44a.5.5 0 0 0-.36-.403l-.26-.072z");
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.dzjitptyt {
  d: path("M7.155 30.49c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.dzyo4sbbn {
  stop-color: var(--svg-color--eabea3, #EABEA3);
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.el0upzbnh {
  d: path("M17.18 26.172a.937.937 0 0 0-1.12 1.497l.931.802a.1.1 0 0 1-.063.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.226z");
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f8w6vk9zf {
  d: path("M8.857 21.42c-.315.22-.723.21-.906-.11c-.391-.948.72-1.58 1.5-1.598c1.167-.027 1.75.63 1.937 1.121c.188.493.227 1.477-.672 1.54c-.803.055-.847-.5-.98-.743c-.133-.242-.594-.41-.879-.21");
}

.fjk2vysly {
  stop-color: var(--svg-color--ba7a7c, #BA7A7C);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
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

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g7osupb7r {
  d: path("M10.118 13.487a1.67 1.67 0 0 1-.96-.167l.147.938c.142.9.805 1.618 1.673 1.822a4.2 4.2 0 0 1-.536-1.134z");
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.gorl-d3ks {
  d: path("M19.92 11.94c.335-.064.634-.229.862-.455l.148.938a2.22 2.22 0 0 1-1.03 2.25q.172-.592.16-1.245z");
}

.grpgooxhk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23.521c.579.14 1.92.172 2.657-.828");
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.gt-69vbgu {
  stop-color: var(--svg-color--bb8072, #BB8072);
  stop-opacity: 0;
}

.gueri_bqi {
  fill: var(--svg-color--d29d8b, #D29D8B);
  d: path("M17.18 26.172a.937.937 0 0 0-1.12 1.497l.931.802a.1.1 0 0 1-.063.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.226z");
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h15jngl9k {
  d: path("m15.53 18.355l.554.16a.15.15 0 0 1 .103.185l-.784 2.73a.15.15 0 0 1-.185.102l-.555-.159z");
}

.h186-31qp {
  stop-color: var(--svg-color--c7695c, #C7695C);
}

.h3e3juv2r {
  d: path("M18.657 3.984a2.37 2.37 0 0 1 1.445.858a2.42 2.42 0 0 1 .295 2.563a1.6 1.6 0 0 0-.133.925l.189 1.197a1.8 1.8 0 0 0-.716-.164l-.176-1.632a1.48 1.48 0 0 0-1.618-1.224l-1.412.223a2.47 2.47 0 0 1-2.459-1.103a.68.68 0 0 0-.687-.324l-1.283.203c-1.86.294-3.128 2.056-2.83 3.938l.275 1.545c-.25.078-.504.206-.684.38l-.191-1.21a1.6 1.6 0 0 0-.412-.838a2.44 2.44 0 0 1-.533-2.443a2.4 2.4 0 0 1 1.13-1.342a2.74 2.74 0 0 0 1.22-1.34a2.37 2.37 0 0 1 2.768-1.379a1.52 1.52 0 0 0 1.203-.19a2.4 2.4 0 0 1 .89-.334a2.37 2.37 0 0 1 2.185.825c.391.464.936.76 1.534.866");
}

.h47r5ibay {
  stop-color: var(--svg-color--bd8677, #BD8677);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.hbzm4jmfo {
  stop-color: var(--svg-color--f54c3c, #F54C3C);
}

.hcsjmwbaq {
  d: path("M23.695 27.619a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hki09zl4s {
  d: path("m12.167 16.955l2.635.734c.357.104.645.406.521.797l-.779 2.704c-.096.329-.442.504-.851.393l-2.6-.733z");
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.hzk1ijbie {
  stop-color: var(--svg-color--e2492a, #E2492A);
}

.i5de26xkm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.icorotc4i {
  stop-color: var(--svg-color--ff451c, #FF451C);
}

.idwps0b8z {
  d: path("M10.214 22.176c-.284.88-1.448 1.292-2.6.92c-1.152-.37-1.793-1.177-1.573-2.265c.18-.888.884-1.75 2.738-1.24c1.153.372 1.719 1.705 1.435 2.585");
}

.ie-bysyvv {
  stop-color: var(--svg-color--dbac8a, #DBAC8A);
}

.ienoccb3u {
  d: path("M11.455 11.676c.151.14.548.371 1.063.274c.562-.106.888-.459.96-.64");
}

.iezg62obf {
  stop-color: var(--svg-color--ff8427, #FF8427);
}

.ijdg6fbam {
  stop-color: var(--svg-color--fc4a51, #FC4A51);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.ip8fcq0ak {
  stop-color: var(--svg-color--cd9b7f, #CD9B7F);
  stop-opacity: 0;
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j4c7dkb7m {
  stop-color: var(--svg-color--b97d70, #B97D70);
}

.j9aoxmbfm {
  stop-color: var(--svg-color--cfae8c, #CFAE8C);
  stop-opacity: 0;
}

.jg12b2kug {
  stop-color: var(--svg-color--efc3a5, #EFC3A5);
  stop-opacity: 0;
}

.jjp_mfbio {
  stop-color: var(--svg-color--bd8677, #BD8677);
  stop-opacity: 0;
}

.jl9fiab1w {
  stop-color: var(--svg-color--cfae8c, #CFAE8C);
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jtvtg3bqw {
  stop-color: var(--svg-color--efc3a7, #EFC3A7);
  stop-opacity: 0;
}

.jw0tmkgly {
  d: path("M21.575 24.43a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.kar3bi73q {
  stop-color: var(--svg-color--d25e22, #D25E22);
  stop-opacity: 0;
}

.kaygmvbyu {
  stop-color: var(--svg-color--e3b69c, #E3B69C);
}

.kcxizyr3a {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
}

.khl528bkl {
  stop-color: var(--svg-color--ff8040, #FF8040);
  stop-opacity: 0;
}

.khs5o_1jg {
  d: path("m29.145 25.83l-4.94-6.05l-3.16 8.57z");
}

.kloinabmx {
  stop-color: var(--svg-color--c26f5c, #C26F5C);
  stop-opacity: 0;
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kss7lepmr {
  stop-color: var(--svg-color--d1a082, #D1A082);
}

.kwfaklb2u {
  stop-color: var(--svg-color--bf8a6b, #BF8A6B);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.lb1-9jboq {
  d: path("m19.718 8.362l-.13-.632c-.132-.768-.869-1.302-1.643-1.213l-1.412.223a2.47 2.47 0 0 1-2.342-.932s-.088-.14-.193-.385c-.396-.922.402-1.798 1.405-1.766c1.02.033 2.206.187 3.129.6c1.94.87 1.958 2.985 1.186 4.105");
}

.lh9tgacmj {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.856 14.191c.425.143.913.187 1.413.108c.505-.08.95-.271 1.312-.538a.23.23 0 0 1 .278.001a.22.22 0 0 1 .067.27m-3.07.159l3.002-.19m-3.002.19a.23.23 0 0 0-.265.09a.215.215 0 0 0 .02.274m.245-.364l-.19.313m3.26-.472L16.858 14m.068.032L16.858 14m.068.032a2.01 2.01 0 0 1-1.518 1.147a2 2 0 0 1-1.797-.624M16.858 14a1.93 1.93 0 0 1-1.462 1.105a1.93 1.93 0 0 1-1.73-.6m-.055.05v.001l.055-.052m-.055.051l.055-.05");
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.lu5a7abcq {
  d: path("M9.67 17.873c.243.25.33.526.343.632l.485.47l2.34.406a.89.89 0 0 0 1.025-.692a.9.9 0 0 0-.774-1.08c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.61");
}

.lwl1xgbup {
  stop-color: var(--svg-color--d25e22, #D25E22);
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.m9orc9b3r {
  stop-color: var(--svg-color--ae4614, #AE4614);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n3g0g-byb {
  d: path("M9.43 10.384a1.643 1.643 0 0 0 .648 3.204a80 80 0 0 1-.649-3.204");
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.nbcoryb1h {
  stop-color: var(--svg-color--bf7c89, #BF7C89);
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.njemumwdh {
  d: path("M8.13 17.732c1.031-1.086 1.92-1.37 2.32-1.375l.797.867l-.93 3.516c-.179.315-.563.996-.695 1.152c-.164.195-.734.63-1.765.238c-.888-.337-1.15-.898-1.176-1.148c.234-1.168.649-2.358 1.45-3.25");
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nu_77rrcl {
  stop-color: var(--svg-color--c7977a, #C7977A);
}

.o-ef0ac2e {
  stop-color: var(--svg-color--d8a788, #D8A788);
  stop-opacity: 0;
}

.o7o0zjb4n {
  d: path("M16.085 10.869c.151.14.548.37 1.063.273c.562-.106.888-.458.96-.64");
}

.o8qu79bty {
  stroke: var(--svg-color--e1ae9b, #E1AE9B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.246 29.585h3.536");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.ohwd33b2n {
  stop-color: var(--svg-color--b8757a, #B8757A);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.oyvgukskf {
  d: path("M14.16 5.754a3 3 0 0 1-.089-.127a.68.68 0 0 0-.686-.324l-1.283.203c-1.861.293-3.128 2.056-2.831 3.938l.044.277c-.384-.207-.902-.689-1.043-1.58c-.17-1.08.531-1.75.98-2.178c.126-.12.232-.222.292-.308l.084-.121c.293-.43.816-1.195 1.867-1.659c.52-.23 1.063-.35 1.51-.408c.468-.061.861.29.935.757l.239 1.513z");
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.pdc6bbcoh {
  fill: var(--svg-color--9a6533, #9A6533);
  d: path("M18.109 7.856a1.9 1.9 0 0 0-.759-.305c-.322-.049-.71-.014-1.23.135a.283.283 0 0 0 .155.544c.475-.136.777-.152.992-.12c.21.032.36.112.541.226a.283.283 0 1 0 .301-.48");
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.pfjyiqgya {
  stop-color: var(--svg-color--ce9a7f, #CE9A7F);
}

.phzm4snim {
  stop-color: var(--svg-color--ce6122, #CE6122);
}

.pie3lznez {
  d: path("M10.396 15.009a3.996 3.996 0 0 0 4.46 2.815l1.9-.3a4 4 0 0 0 3.376-4.052c-.18-1.918-.36-3.828-.571-5.74a1.48 1.48 0 0 0-1.618-1.224l-1.412.223a2.47 2.47 0 0 1-2.459-1.103a.68.68 0 0 0-.686-.324l-1.284.203c-1.86.294-3.127 2.056-2.83 3.938c.296 1.876.704 3.703 1.124 5.564");
}

.pll5kd_nw {
  stop-color: var(--svg-color--dfae8f, #DFAE8F);
}

.pptfqcb0f {
  d: path("M16.043 10.6c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.ps228g2nk {
  stop-color: var(--svg-color--f8bf96, #F8BF96);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q4qw-3jpk {
  d: path("M15.28 14.373a3.1 3.1 0 0 1-1.448-.11c-.15-.05-.273.13-.166.241c.418.459 1.06.707 1.73.601A1.93 1.93 0 0 0 16.858 14c.066-.144-.106-.27-.233-.179a3.05 3.05 0 0 1-1.344.552");
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qklmkjbjl {
  d: path("M11.413 11.409c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.qoqjsdb8z {
  fill: var(--svg-color--d9aa86, #D9AA86);
  d: path("M10.099 16.95c.356.126.482.331.515.454l.446.39l2.291.363a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r1y6vkpka {
  stop-color: var(--svg-color--b42c01, #B42C01);
}

.r6dyzpbfo {
  stop-color: var(--svg-color--a62302, #A62302);
  stop-opacity: 0;
}

.r8owzxbqs {
  stop-color: var(--svg-color--bf7c89, #BF7C89);
  stop-opacity: 0;
}

.ra3pdeoog {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.955 8.009c-.288-.145-.985-.37-1.729-.121");
}

.rb5pqrony {
  stop-color: var(--svg-color--d5a079, #D5A079);
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.ro5jldbid {
  stop-color: var(--svg-color--c38771, #C38771);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rvz7hrbgf {
  stop-color: var(--svg-color--cb9c79, #CB9C79);
}

.rw9b8ul_k {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M9.551 11.047a.975.975 0 0 0 .384 1.881a80 80 0 0 1-.384-1.881");
}

.rwjg04fmi {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.972 9.158c.23-.227.824-.655 1.608-.648");
}

.s_51gm69o {
  d: path("M15.685 19.02c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.s8qj-4x_q {
  d: path("M10.099 16.95c.356.126.482.331.515.454l.446.39l2.291.363a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.sg8a2viwh {
  stop-color: var(--svg-color--c58b71, #C58B71);
}

.si6i9vb1t {
  d: path("M20.615 26.267c1.598-.23 4.567-.809 6.543-1.27c1.522-.263 2.641 1.203 2.641 2.781c0 1.371-1.022 2.236-1.747 2.618a.86.86 0 0 1-.403.093h-8.014v-3.086c0-.797.281-1 .98-1.136");
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.sjvismp2t {
  stop-color: var(--svg-color--fc4a51, #FC4A51);
  stop-opacity: 0;
}

.sk7ylfhdv {
  stop-color: var(--svg-color--905b2c, #905B2C);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.sok9f40_l {
  stop-color: var(--svg-color--efc3a5, #EFC3A5);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.t9y-_dh4s {
  stop-color: var(--svg-color--edb18c, #EDB18C);
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.td96-d_gv {
  d: path("M10.565 19.06c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.tjgs2ub-w {
  stop-color: var(--svg-color--efc3a7, #EFC3A7);
}

.tlxyqtbtq {
  stop-color: var(--svg-color--b56e74, #B56E74);
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.trma59b_r {
  stop-color: var(--svg-color--d1623d, #D1623D);
  stop-opacity: 0;
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

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u_vqqhk3b {
  stop-color: var(--svg-color--ff9400, #FF9400);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u1zlaqbml {
  stop-color: var(--svg-color--bc7b6b, #BC7B6B);
  stop-opacity: 0;
}

.u2ti54bnp {
  d: path("m14.826 17.588l-2.636-.735l-1.073 3.895l2.6.734c.408.11.755-.065.85-.394l.78-2.703c.123-.391-.164-.694-.521-.798");
}

.u6bxf4b2y {
  fill: var(--svg-color--d8a888, #D8A888);
  d: path("M9.67 17.873c.243.25.33.526.343.632l.485.47l2.34.406a.89.89 0 0 0 1.025-.692a.9.9 0 0 0-.774-1.08c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.61");
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uxh2dv17l {
  stop-color: var(--svg-color--bc7b6b, #BC7B6B);
}

.uxpb5qzbn {
  stop-color: var(--svg-color--cd9b7f, #CD9B7F);
}

.uz8nvn0bw {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
  stop-opacity: 0;
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.vs2nrrbhb {
  d: path("m11.939 16.524l3.172.884c.43.125.744.558.627.96l-.9 3.086c-.115.396-.532.606-1.024.473l-3.129-.883z");
}

.vsvz-xe_v {
  stop-color: var(--svg-color--c58b71, #C58B71);
  stop-opacity: 0;
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w0pwsab7o {
  d: path("m11.845 21.09l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.w444cbj2i {
  stop-color: var(--svg-color--fa362a, #FA362A);
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wiexblb8s {
  stop-color: var(--svg-color--9a663d, #9A663D);
}

.wj5sb5bda {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 20.24c-.206.432-.319 1.448.875 2.054c1.194.607 1.992.149 2.242-.156");
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wxf4d8bhs {
  stop-color: var(--svg-color--cf9981, #CF9981);
  stop-opacity: 0;
}

.wyqcze2zy {
  stop-color: var(--svg-color--a62302, #A62302);
}

.xhgfmqa2q {
  cx: 16.983px;
  cy: 10.011px;
  r: 1.344px;
}

.xohd9o-1e {
  stroke: var(--svg-color--e2b79f, #E2B79F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.874 26.78l1.634 1.14");
}

.xrzwqzb7j {
  stop-color: var(--svg-color--b42c01, #B42C01);
  stop-opacity: 0;
}

.xvsb4lbua {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m14.332 11.183l-.434 1.779c-.042.397.264.74.61.685l.742-.117c.347-.055.531-.48.37-.84l-.793-1.774c-.172-.394-.447-.162-.495.267");
}

.xvwmp6tlw {
  stop-color: var(--svg-color--e6422d, #E6422D);
  stop-opacity: 0;
}

.xwvw-6byu {
  d: path("m14.32 10.793l-.242 1.938c-.05.398.273.738.645.68l.792-.126c.372-.058.573-.487.405-.845l-.828-1.769c-.18-.392-.716-.307-.771.122");
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.xyrntivgr {
  stop-color: var(--svg-color--ff7c1e, #FF7C1E);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y0dl1gblq {
  stop-color: var(--svg-color--b8757a, #B8757A);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y9as00b0p {
  cx: 12.394px;
  cy: 10.74px;
  r: 1.344px;
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yq-9ytfqn {
  stop-color: var(--svg-color--98643a, #98643A);
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.z_gh6vsyy {
  stop-color: var(--svg-color--ab6850, #AB6850);
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.z7o095spk {
  d: path("m2.201 30.49l2.93-9.156c.351-1.414 2.07-2.104 3.65-1.614s2.49 2.332 2.006 3.692L8.571 30.49z");
}

.z8oy8ibbe {
  stop-color: var(--svg-color--d1a082, #D1A082);
  stop-opacity: 0;
}

.z9xh4xkpu {
  d: path("M21.835 24.51c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.zegip2beb {
  stop-color: var(--svg-color--ae4614, #AE4614);
  stop-opacity: 0;
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.zmq4c2bxg {
  stop-color: var(--svg-color--d1623d, #D1623D);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zq2cu-lqa {
  stop-color: var(--svg-color--dcaa8a, #DCAA8A);
  stop-opacity: 0;
}

.zx-utrb8d {
  stop-color: var(--svg-color--dcab8c, #DCAB8C);
}

</style>
