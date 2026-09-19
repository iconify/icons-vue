<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iBLOIwZ)"><path fill="url(#iXWEY2b)" class="py6xm8bqh"/></g><path fill="url(#itSxsxb)" class="jyi503hrb"/><g filter="url(#iw0vUFd)"><path class="niaaygfag"/><path fill="url(#iL45iVd)" class="b7b9e6b0u"/><path fill="url(#i2MTerb)" class="b7b9e6b0u"/></g><path fill="url(#ijDjueb)" clip-rule="evenodd" class="r-65_82is"/><path fill="url(#iz76VtZ)" clip-rule="evenodd" class="jmhzor_lw"/><path fill="url(#iFJdgKe)" clip-rule="evenodd" class="ooxfyv-aw"/><path fill="url(#i16W2gd)" clip-rule="evenodd" class="a6zlob7-x"/><path fill="url(#iLEzxfd)" clip-rule="evenodd" class="a6zlob7-x"/><path fill="url(#ijbIOwc)" clip-rule="evenodd" class="wt-hn3yze"/><path fill="url(#irC1Ocd)" class="ctecrac_o"/><g filter="url(#iGZUjNc)"><path clip-rule="evenodd" class="dvqfxlb2t"/><path fill="url(#ibAijGc)" clip-rule="evenodd" class="a-rm-zxil"/><path fill="url(#ioWbAkO)" clip-rule="evenodd" class="a-rm-zxil"/></g><g filter="url(#iwwomxc)"><path fill="url(#ibPfXWc)" class="mtpoepbyz"/></g><path fill="url(#iemapbP)" class="g6m53cbwz"/><path fill="url(#iH3fUdc)" class="x03fa-b4r"/><path fill="url(#i6S7xAd)" class="x03fa-b4r"/><path fill="url(#iZU7VRc)" class="xekx4ab0f"/><path fill="url(#irrlWld)" class="egqn6fbww"/><path fill="url(#ijNPPxe)" class="egqn6fbww"/><path fill="url(#i0Hr4Xb)" class="ducmbebld"/><path fill="url(#ifkH9Db)" class="ducmbebld"/><path fill="url(#i1SfOae)" class="ducmbebld"/><g filter="url(#imUqk5d)"><path fill="url(#izgH8db)" class="sz6cbeb_j"/></g><g filter="url(#iVqceQb)"><path fill="url(#iCY5ZTb)" class="dgv5vobce"/></g><path fill="url(#ilPnByc)" class="ab2qf0umn"/><path fill="url(#i0DF8id)" class="ab2qf0umn"/><path fill="url(#idFnyRd)" class="afy1macji"/><path fill="url(#ikQnpgb)" class="afy1macji"/><path fill="url(#iJGOZ5c)" class="kw2cbbczi"/><path fill="url(#iusgpbd)" class="kw2cbbczi"/><path fill="url(#iq1508T)" class="jtpb4qi3h"/><path fill="url(#iaTzYMq)" class="jtpb4qi3h"/><path fill="url(#i9RVpHd)" class="jtpb4qi3h"/><path fill="url(#imnxaDc)" class="jtpb4qi3h"/><path fill="url(#iVC9u0X)" class="jtpb4qi3h"/><path fill="url(#ifPeT5S)" class="jtpb4qi3h"/><path fill="url(#ii9TfKd)" class="or1v7ccby"/><path fill="url(#ixez9sl)" class="or1v7ccby"/><path fill="url(#i6nCSbw)" class="or1v7ccby"/><g filter="url(#imy3geb)"><path fill="url(#ihIlmye)" class="j15wz5dqx"/><path fill="url(#iMEioxT)" class="j15wz5dqx"/><path fill="url(#ioVz2Eb)" class="j15wz5dqx"/></g><path clip-rule="evenodd" class="sjd5zkbdm"/><g filter="url(#iG5HZfe)"><path class="f7cl91b7n"/></g><g filter="url(#iDH57Ed)"><path fill="url(#ihXsqsd)" class="x7wf8bb9k"/><path fill="url(#ijBw7md)" class="x7wf8bb9k"/></g><path stroke="url(#i0kTpQe)" class="rvaghwbsu"/><path class="ck9eysb8r"/><path fill="url(#i028EUb)" class="xbbe_nbvg"/><path class="j95z4_w8q"/><g filter="url(#iRKZFOx)"><path class="zc4a7s-lt"/><path fill="url(#iBmUkJK)" class="zu_6ow2qk"/></g><g filter="url(#i9LO9ob)"><path fill="url(#iiITKue)" class="qj_hytbqn"/></g><path class="nezdxyb3x"/><path fill="url(#iSMlGSc)" class="pmnl_0bxq"/><path class="r6oa105rp"/><g filter="url(#i60buVc)"><path fill="url(#ievdc5b)" class="n1jti7bmr"/></g><g filter="url(#ivByVed)"><ellipse transform="rotate(-17.442 16.29 10.76)" class="r6gvahbyk"/><ellipse fill="url(#ikJBLnd)" transform="rotate(-17.442 16.29 10.76)" class="lltkvqb6g"/></g><g filter="url(#iglsgjc)"><path fill="url(#iNLJTIf)" class="lx7vkbc9m"/></g><path fill="url(#iJ24sxd)" class="uusmdck_a"/><path fill="url(#iU0Raob)" class="uusmdck_a"/><path fill="url(#iCUfmjM)" class="uusmdck_a"/><path fill="url(#i4PZghe)" class="uusmdck_a"/><path fill="url(#iJ24sxd)" class="uusmdck_a"/><path fill="url(#iU0Raob)" class="uusmdck_a"/><path fill="url(#iCUfmjM)" class="uusmdck_a"/><path fill="url(#i4PZghe)" class="uusmdck_a"/><g filter="url(#iZzWKZd)"><path fill="url(#iasJmib)" class="abbistd2i"/></g><g filter="url(#iJbi4yc)"><path clip-rule="evenodd" class="c-cpyob2f"/></g><g filter="url(#iSAbXxd)"><path class="fdcar974t"/></g><g filter="url(#iRvWD4c)"><path clip-rule="evenodd" class="pwm6c7b8r"/></g><g filter="url(#i76BEtd)"><path class="j8x1vn0ks"/></g><defs><radialGradient id="iL45iVd" cx="0" cy="0" r="1" gradientTransform="rotate(-171.733 7.546 7.162)scale(3.69464 3.85482)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="j72ij_b9t"/><stop offset="1" class="tvqvznkkw"/></radialGradient><radialGradient id="ijDjueb" cx="0" cy="0" r="1" gradientTransform="rotate(103.829 7.435 15.985)scale(2.12588 1.61875)" gradientUnits="userSpaceOnUse"><stop class="zmhergcsk"/><stop offset=".359" class="h2ddnbh-b"/></radialGradient><radialGradient id="iFJdgKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.47167 2.0178 -1.4673 -.343 25.37 12.142)" gradientUnits="userSpaceOnUse"><stop class="zmhergcsk"/><stop offset=".359" class="ris78_9sh"/></radialGradient><radialGradient id="i16W2gd" cx="0" cy="0" r="1" gradientTransform="rotate(113.89 9.22 14.834)scale(1.87125 1.68165)" gradientUnits="userSpaceOnUse"><stop class="dbphouvft"/><stop offset=".467" class="o52n_hqhs"/></radialGradient><radialGradient id="iLEzxfd" cx="0" cy="0" r="1" gradientTransform="rotate(113.89 9.22 14.834)scale(1.87125 1.68165)" gradientUnits="userSpaceOnUse"><stop class="gj42dtb1r"/><stop offset=".467" class="hty4pzg0h"/></radialGradient><radialGradient id="ijbIOwc" cx="0" cy="0" r="1" gradientTransform="matrix(-.67866 1.61156 -1.399 -.58915 27.186 13.204)" gradientUnits="userSpaceOnUse"><stop class="ybbdkp2ua"/><stop offset=".467" class="uzk5vp72a"/></radialGradient><radialGradient id="irC1Ocd" cx="0" cy="0" r="1" gradientTransform="matrix(-.424 .6523 -1.8923 -1.23 24.825 15.617)" gradientUnits="userSpaceOnUse"><stop class="lewi9xb7p"/><stop offset=".438" class="r22hbpu9p"/></radialGradient><radialGradient id="ibAijGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.467 -1.9886 6.33088 4.67033 20.855 20.266)" gradientUnits="userSpaceOnUse"><stop class="k_meu68sj"/><stop offset="1" class="o0abx5bzz"/></radialGradient><radialGradient id="ioWbAkO" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.83537 -1.45884 0 25.19 15.767)" gradientUnits="userSpaceOnUse"><stop class="m618cgh3i"/><stop offset="1" class="oh9s2ccbv"/></radialGradient><radialGradient id="iemapbP" cx="0" cy="0" r="1" gradientTransform="matrix(-.90626 2.21874 -3.49772 -1.42868 4.656 4.388)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t1ffwv_yc"/><stop offset="1" class="he60mdbwm"/></radialGradient><radialGradient id="iH3fUdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.96014 1.99895 -3.51333 -1.68753 4.503 6.09)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="c6s8j5o0k"/><stop offset="1" class="upn6hw37x"/></radialGradient><radialGradient id="i6S7xAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.51562 1.39063 -3.21171 -1.19085 5.281 6.841)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="w4-c1u12h"/><stop offset="1" class="db6hxbc6j"/></radialGradient><radialGradient id="iZU7VRc" cx="0" cy="0" r="1" gradientTransform="matrix(.41141 1.3754 -2.82798 .8459 3.504 8.008)" gradientUnits="userSpaceOnUse"><stop offset=".05" class="w3225dbjw"/><stop offset="1" class="rwcn2nbsr"/></radialGradient><radialGradient id="irrlWld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1467 4.65626 -2.92783 -.72104 8.344 5.482)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="idibcljtc"/><stop offset="1" class="rlocznbrk"/></radialGradient><radialGradient id="i0Hr4Xb" cx="0" cy="0" r="1" gradientTransform="rotate(84.147 1.986 7.458)scale(3.98377 3.9383)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="kkkpn9_8c"/><stop offset="1" class="qsi2djbas"/></radialGradient><radialGradient id="ifkH9Db" cx="0" cy="0" r="1" gradientTransform="matrix(.55769 3.79546 -10.478 1.5396 8.345 5.904)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="jbim1r-8q"/><stop offset=".887" class="jx__8ve1w"/></radialGradient><radialGradient id="i1SfOae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10157 -3.50206 7.04927 -2.21735 9.695 8.224)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="w1-vbdbpq"/><stop offset="1" class="vi9q-fb9u"/></radialGradient><radialGradient id="izgH8db" cx="0" cy="0" r="1" gradientTransform="matrix(.95313 1.7322 -1.31372 .72286 9.75 4.892)" gradientUnits="userSpaceOnUse"><stop class="pwyc_ob2i"/><stop offset="1" class="x114bxlro"/></radialGradient><radialGradient id="iCY5ZTb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.141 6.19 -1.215)scale(1.5807 2.46179)" gradientUnits="userSpaceOnUse"><stop class="jh6rb_-if"/><stop offset="1" class="btbmkccji"/></radialGradient><radialGradient id="ilPnByc" cx="0" cy="0" r="1" gradientTransform="rotate(-100.73 5.349 -1.264)scale(1.84923 2.37953)" gradientUnits="userSpaceOnUse"><stop class="jh6rb_-if"/><stop offset="1" class="btbmkccji"/></radialGradient><radialGradient id="i0DF8id" cx="0" cy="0" r="1" gradientTransform="rotate(151.204 3.296 3.135)scale(2.69231 1.10958)" gradientUnits="userSpaceOnUse"><stop offset=".874" class="pv-xo4bei"/><stop offset="1" class="w86h2iq4q"/></radialGradient><radialGradient id="idFnyRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.9922 -.60156 1.5104 -2.49122 5.43 3.224)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="hgt5uebfs"/><stop offset="1" class="vvex-7byg"/></radialGradient><radialGradient id="ikQnpgb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55468 1.19532 -.2462 -.32022 6.087 2.755)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="oqaibvbqb"/><stop offset="1" class="jj-ghzbrk"/></radialGradient><radialGradient id="iJGOZ5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -6.9375 10.4709 -.04717 6.188 10.325)" gradientUnits="userSpaceOnUse"><stop class="x9d7jz1fb"/><stop offset="1" class="nil-nrb9t"/></radialGradient><radialGradient id="iusgpbd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 -2.87499 4.0482 -7.17238 8.469 6.857)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="aljt7ncuz"/><stop offset="1" class="q3hk4_bla"/></radialGradient><radialGradient id="iq1508T" cx="0" cy="0" r="1" gradientTransform="matrix(-3.68754 8.59373 -8.59905 -3.68982 18.938 17.732)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="rmpzr1bpn"/><stop offset="1" class="eysgdi55n"/></radialGradient><radialGradient id="i9RVpHd" cx="0" cy="0" r="1" gradientTransform="rotate(99.197 1.007 13.505)scale(3.32398 6.99637)" gradientUnits="userSpaceOnUse"><stop class="xf6fc56wi"/><stop offset="1" class="oz1prabcs"/></radialGradient><radialGradient id="imnxaDc" cx="0" cy="0" r="1" gradientTransform="matrix(2.70313 .32813 -.1097 .90377 19.54 15.97)" gradientUnits="userSpaceOnUse"><stop class="cp11-1gcm"/><stop offset="1" class="srsgrxbbq"/></radialGradient><radialGradient id="iVC9u0X" cx="0" cy="0" r="1" gradientTransform="matrix(.30078 2.59375 -2.78882 .3234 17.281 16.18)" gradientUnits="userSpaceOnUse"><stop offset=".906" class="c9s-hpbqa"/><stop offset="1" class="gkz0xj0po"/></radialGradient><radialGradient id="ifPeT5S" cx="0" cy="0" r="1" gradientTransform="matrix(.29688 2.5625 -2.75522 .3192 17.281 16.18)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="uayuyob5b"/><stop offset=".954" class="uqh6nu2wx"/></radialGradient><radialGradient id="ii9TfKd" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 4 -6.15337 4.1343 15.625 14.888)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="nattj0bij"/><stop offset=".876" class="mg6y3qeip"/></radialGradient><radialGradient id="ixez9sl" cx="0" cy="0" r="1" gradientTransform="rotate(165.192 8.129 8.502)scale(5.7551 2.40041)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="c-h80obgn"/><stop offset="1" class="t3ga4ibtc"/></radialGradient><radialGradient id="i6nCSbw" cx="0" cy="0" r="1" gradientTransform="rotate(157.999 8.412 9.776)scale(1.66837 .64809)" gradientUnits="userSpaceOnUse"><stop class="hv_0dkosg"/><stop offset="1" class="t-6g_0b7g"/></radialGradient><radialGradient id="ihIlmye" cx="0" cy="0" r="1" gradientTransform="rotate(151.705 8.042 8.575)scale(4.5073 3.94979)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="rl7ir4szc"/><stop offset="1" class="p93njvi5m"/></radialGradient><radialGradient id="iMEioxT" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -.84375 .99271 .29414 16.516 10.529)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="lom2e0u5t"/><stop offset="1" class="itzskw0ez"/></radialGradient><radialGradient id="ioVz2Eb" cx="0" cy="0" r="1" gradientTransform="matrix(.30378 -1.00727 1.1851 .35741 19.408 11.02)" gradientUnits="userSpaceOnUse"><stop class="b3mdh_wyh"/><stop offset="1" class="y1-ru4g2h"/></radialGradient><radialGradient id="ihXsqsd" cx="0" cy="0" r="1" gradientTransform="rotate(178.156 8.98 6.27)scale(1.07184 3.25765)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="bec90zboa"/><stop offset=".491" class="jzkbzcg7n"/></radialGradient><radialGradient id="ijBw7md" cx="0" cy="0" r="1" gradientTransform="matrix(-.32092 1.22102 -1.83089 -.48121 17.874 11.637)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="nwz3krwdd"/><stop offset=".983" class="zusf43kae"/></radialGradient><radialGradient id="i0kTpQe" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 -.32813 1.229 1.17048 16.523 13.68)" gradientUnits="userSpaceOnUse"><stop class="m7wei-y5y"/><stop offset="1" class="xpbv08bvr"/></radialGradient><radialGradient id="i028EUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2953 .56697 -.67087 -.34941 19.293 11.305)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="tdiqapb8p"/><stop offset="1" class="mu1lsrbfz"/></radialGradient><radialGradient id="iBmUkJK" cx="0" cy="0" r="1" gradientTransform="rotate(-117.34 13 -.078)scale(.24737 .34057)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSMlGSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29297 .5625 -.66558 -.34666 16.546 10.75)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="tdiqapb8p"/><stop offset="1" class="mu1lsrbfz"/></radialGradient><radialGradient id="ikJBLnd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.538 -2.532)scale(.32222 .38731)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJ24sxd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.78124 5.34377 -6.51613 -5.83019 20.563 6.107)" gradientUnits="userSpaceOnUse"><stop class="iz96j8ojk"/><stop offset="1" class="i2-vql0bm"/></radialGradient><radialGradient id="iU0Raob" cx="0" cy="0" r="1" gradientTransform="matrix(.30078 -1.59375 3.79885 .71694 18.152 9.2)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="n2b8gu5vw"/><stop offset="1" class="nj1er27qb"/></radialGradient><radialGradient id="iCUfmjM" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 1.59375 -3.9358 4.01296 15 5.888)" gradientUnits="userSpaceOnUse"><stop class="gmg8hcbdj"/><stop offset="1" class="m2ds08s7w"/></radialGradient><radialGradient id="i4PZghe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40626 -2.65624 1.89737 -1.7188 21.531 7.326)" gradientUnits="userSpaceOnUse"><stop class="ht2yfkjwb"/><stop offset="1" class="q_druvruw"/></radialGradient><filter id="iBLOIwZ" width="28.306" height="11.645" x="1.897" y="17.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.572549 0 0 0 0 0.819608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.619608 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23711" result="effect2_innerShadow_3987_23711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.886275 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_23711" result="effect3_innerShadow_3987_23711"/></filter><filter id="iw0vUFd" width="8.631" height="9.819" x="4.869" y="8.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.419608 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23711"/></filter><filter id="iGZUjNc" width="9.358" height="9.592" x="18.864" y="14.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.45098 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23711"/></filter><filter id="iwwomxc" width="5.441" height="5.972" x="20.208" y="15.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23711" stdDeviation=".2"/></filter><filter id="imUqk5d" width="1.134" height="3.026" x="9.669" y="4.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23711"/></filter><filter id="iVqceQb" width="4.669" height="2.54" x="5.72" y="3.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.768627 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23711"/></filter><filter id="imy3geb" width="6.713" height="7.553" x="14.563" y="8.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.419608 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23711"/></filter><filter id="iG5HZfe" width="2.2" height="2.754" x="16.334" y="10.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23711" stdDeviation=".25"/></filter><filter id="iDH57Ed" width="1.4" height="1.954" x="16.916" y="11.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23711" stdDeviation=".05"/></filter><filter id="iRKZFOx" width=".514" height=".381" x="18.732" y="11.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23711" stdDeviation=".025"/></filter><filter id="i9LO9ob" width=".395" height=".425" x="19.334" y="11.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23711" stdDeviation=".025"/></filter><filter id="i60buVc" width=".45" height=".496" x="16.544" y="10.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23711" stdDeviation=".025"/></filter><filter id="ivByVed" width=".591" height=".389" x="15.995" y="10.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23711" stdDeviation=".025"/></filter><filter id="iglsgjc" width="28.306" height="6.762" x="1.897" y="23.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.368627 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.458824 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23711" result="effect2_innerShadow_3987_23711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.619608 0 0 0 0 0.988235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_23711" result="effect3_innerShadow_3987_23711"/></filter><filter id="iZzWKZd" width="2.176" height="6.768" x="6.255" y="9.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23711" stdDeviation=".2"/></filter><filter id="iJbi4yc" width="1.725" height=".918" x="15.68" y="8.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23711"/></filter><filter id="iSAbXxd" width="1.425" height=".418" x="15.83" y="9.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23711" stdDeviation=".05"/></filter><filter id="iRvWD4c" width="1.608" height="1.292" x="19.001" y="9.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23711"/></filter><filter id="i76BEtd" width="1.308" height=".792" x="19.205" y="9.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23711" stdDeviation=".05"/></filter><linearGradient id="iXWEY2b" x1="29.953" x2="6.802" y1="21.45" y2="30.871" gradientUnits="userSpaceOnUse"><stop class="t77dcut_r"/><stop offset=".78" class="qvl3f1svv"/></linearGradient><linearGradient id="itSxsxb" x1="8.234" x2="9.469" y1="10.491" y2="8.835" gradientUnits="userSpaceOnUse"><stop offset=".174" class="y0urfl-9x"/><stop offset="1" class="ezbu0lfar"/></linearGradient><linearGradient id="i2MTerb" x1="5.069" x2="5.89" y1="14.495" y2="14.495" gradientUnits="userSpaceOnUse"><stop class="e455qlg6j"/><stop offset="1" class="llsmmnb0k"/></linearGradient><linearGradient id="iz76VtZ" x1="4.781" x2="6.297" y1="9.607" y2="10.248" gradientUnits="userSpaceOnUse"><stop class="nr7c7pb7v"/><stop offset="1" class="n4sb7zk9f"/></linearGradient><linearGradient id="ibPfXWc" x1="24.718" x2="17.952" y1="20.75" y2="14.313" gradientUnits="userSpaceOnUse"><stop offset=".298" class="h5nwt-bbc"/><stop offset="1" class="iu8i86lxh"/></linearGradient><linearGradient id="ijNPPxe" x1="7.336" x2="7.547" y1="5.646" y2="5.81" gradientUnits="userSpaceOnUse"><stop offset=".139" class="pdlduxt0m"/><stop offset="1" class="xtrjnaccv"/></linearGradient><linearGradient id="iaTzYMq" x1="11.25" x2="13.969" y1="20.763" y2="21.451" gradientUnits="userSpaceOnUse"><stop class="rzd60jbst"/><stop offset="1" class="w8l-j4b1q"/></linearGradient><linearGradient id="iiITKue" x1="19.695" x2="19.471" y1="11.535" y2="11.622" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ievdc5b" x1="16.924" x2="16.701" y1="10.975" y2="11.062" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iNLJTIf" x1="20.094" x2="1.406" y1="28.7" y2="21.075" gradientUnits="userSpaceOnUse"><stop class="l-fqg0bdm"/><stop offset="1" class="wda4yc_iv"/></linearGradient><linearGradient id="iasJmib" x1="7.608" x2="7.468" y1="10.188" y2="18.625" gradientUnits="userSpaceOnUse"><stop class="k10stfbid"/><stop offset="1" class="ysa1wwbdb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-playing-water-polo-medium-light" /></template>
<style>
.a-rm-zxil {
  fill-rule: evenodd;
  d: path("M26.148 14.513c.857 0 1.574.425 1.574 1.281v5.857c0 1.69-2.004 2.58-3.258 1.447l-5.09-4.6a1.55 1.55 0 0 1 2.08-2.3l3.008 2.72a.1.1 0 0 0 .167-.071l.098-3.053c0-.856.565-1.281 1.421-1.281");
}

.a6zlob7-x {
  fill-rule: evenodd;
  d: path("M25.766 12.323a.5.5 0 0 1 .703.075c.267.332.83 1.208.57 2.568a.5.5 0 0 1-.982-.187c.186-.976-.212-1.561-.367-1.753a.5.5 0 0 1 .076-.703");
}

.ab2qf0umn {
  d: path("M8.967 2.781c.037.026.023.085-.023.09a5 5 0 0 0-1.395.396a4.9 4.9 0 0 0-2.218 1.948a.05.05 0 0 1-.072.014a2.7 2.7 0 0 1-.597-.64a.05.05 0 0 1 0-.054a5.5 5.5 0 0 1 2.05-1.905a4 4 0 0 1 .95-.343c.361-.086.938.247 1.303.495");
}

.abbistd2i {
  d: path("M6.719 11.658c.162-1.363.942-1.735 1.312-1.75c-.487.4-.651 1.562-.672 2.093l.172 3.234l-.812.64c.041-.864-.163-2.855 0-4.217");
}

.afy1macji {
  d: path("M4.147 3.217c-.014.013-.011.037-.008.056q.084.42.22.747a.05.05 0 0 0 .086.01a6 6 0 0 1 2.06-1.808c.03-.02.017-.071-.02-.068c-.904.08-1.72.47-2.338 1.063");
}

.aljt7ncuz {
  stop-color: var(--svg-color--d9d1be, #D9D1BE);
  stop-opacity: 0;
}

.b3mdh_wyh {
  stop-color: var(--svg-color--d79a86, #D79A86);
}

.b7b9e6b0u {
  d: path("m5.071 15.611l.335-6.413L8.5 8.823l-.257 5.484a.2.2 0 0 0 .177.209l5.08.572l-.953 2.954l-5.904-.598A1.75 1.75 0 0 1 5.07 15.61");
}

.bec90zboa {
  stop-color: var(--svg-color--f8c7a7, #F8C7A7);
}

.btbmkccji {
  stop-color: var(--svg-color--fbcd40, #FBCD40);
}

.c-cpyob2f {
  fill: var(--svg-color--9b6432, #9B6432);
  fill-rule: evenodd;
  d: path("M17.039 9.798c-.467-.106-.808-.012-.94.045a.3.3 0 0 1-.238-.55c.236-.103.707-.217 1.31-.08a.3.3 0 0 1-.132.585");
}

.c-h80obgn {
  stop-color: var(--svg-color--a9756c, #A9756C);
}

.c6s8j5o0k {
  stop-color: var(--svg-color--daae44, #DAAE44);
}

.c9s-hpbqa {
  stop-color: var(--svg-color--44adff, #44ADFF);
}

.ck9eysb8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.425 10.949a.92.92 0 0 1 .75.847a.18.18 0 0 1-.213.189l-1.445-.267a.15.15 0 0 1-.114-.203a.92.92 0 0 1 1.022-.566");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cp11-1gcm {
  stop-color: var(--svg-color--5cc5ff, #5CC5FF);
}

.ctecrac_o {
  d: path("M24.117 16.107c.288.175.57.5.676.64l.7-1.21c-.192-.113-.67-.394-1.052-.622a.58.58 0 0 0-.906.454c.004.351.223.52.582.738");
}

.db6hxbc6j {
  stop-color: var(--svg-color--d39c52, #D39C52);
}

.dbphouvft {
  stop-color: var(--svg-color--685957, #685957);
}

.dgv5vobce {
  d: path("M6.75 5.771c.223-.34.846-1.163 1.907-1.439a3.2 3.2 0 0 1 1.57-.001c.041.01.077-.032.057-.07a3.9 3.9 0 0 0-.673-.944c-.019-.019-.054-.013-.081-.013a4.3 4.3 0 0 0-1.793.38c-1.136.503-1.76 1.374-2.01 1.783a.05.05 0 0 0 .021.07c.4.19.76.243.958.256a.05.05 0 0 0 .044-.022");
}

.ducmbebld {
  d: path("M9.527 8.795c.026-.025.013-.08.023-.114v-.004c.588-1.715-.152-3.418-.408-3.929a.05.05 0 0 0-.049-.026a2.4 2.4 0 0 0-.863.275a.05.05 0 0 0-.018.068c.246.43.682 1.366.591 2.517c-.073.872-.357 1.518-.68 1.988c-.027.04.012.094.058.077c.508-.19.965-.482 1.346-.852");
}

.dvqfxlb2t {
  fill: var(--svg-color--ebb48c, #EBB48C);
  fill-rule: evenodd;
  d: path("M26.148 14.513c.857 0 1.574.425 1.574 1.281v5.857c0 1.69-2.004 2.58-3.258 1.447l-5.09-4.6a1.55 1.55 0 0 1 2.08-2.3l3.008 2.72a.1.1 0 0 0 .167-.071l.098-3.053c0-.856.565-1.281 1.421-1.281");
}

.e455qlg6j {
  stop-color: var(--svg-color--dea486, #DEA486);
}

.egqn6fbww {
  d: path("M7.24 9.868c.032-.004.052-.044.075-.066c.42-.4.923-1.1 1.018-2.252c.08-.989-.29-1.816-.505-2.206a.048.048 0 0 0-.073-.013c-.325.27-.535.568-.632.716a.05.05 0 0 0-.006.042c.076.246.221.846.16 1.524a3.2 3.2 0 0 1-.418 1.322l-.003.008l-.013.024l-.007.01a2.8 2.8 0 0 1-.695.766c-.035.027-.022.082.02.09a4 4 0 0 0 1.08.035");
}

.eysgdi55n {
  stop-color: var(--svg-color--2175c0, #2175C0);
}

.ezbu0lfar {
  stop-color: var(--svg-color--e4b290, #E4B290);
}

.f7cl91b7n {
  fill: var(--svg-color--c18476, #C18476);
  d: path("m17.41 11.434l-.536 1.014c-.11.209.015.46.248.504l.498.092a.348.348 0 0 0 .411-.382l-.137-1.139c-.028-.251-.365-.313-.484-.089");
}

.fdcar974t {
  stroke: var(--svg-color--99663d, #99663D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.98 9.509c.184-.08.59-.184 1.125-.063");
}

.ft5dv1b6b {
  fill: none;
}

.g6m53cbwz {
  d: path("M3.198 4.657a.04.04 0 0 0-.003.025c.03.13.289 1.023 1.178 1.688c.687.502 1.455.753 2.412.782a.05.05 0 0 0 .05-.053a4.2 4.2 0 0 0-.133-.81a.05.05 0 0 0-.045-.036a3.1 3.1 0 0 1-1.208-.354a3.2 3.2 0 0 1-1.247-1.174a.1.1 0 0 1-.02-.033l-.016-.042l-.004-.009a4 4 0 0 1-.376-.895a.05.05 0 0 0-.088-.017a4 4 0 0 0-.5.928");
}

.gj42dtb1r {
  stop-color: var(--svg-color--f1c2a3, #F1C2A3);
}

.gkz0xj0po {
  stop-color: var(--svg-color--44abff, #44ABFF);
  stop-opacity: 0;
}

.gmg8hcbdj {
  stop-color: var(--svg-color--3c7dbf, #3C7DBF);
}

.h2ddnbh-b {
  stop-color: var(--svg-color--c98271, #C98271);
}

.h5nwt-bbc {
  stop-color: var(--svg-color--f5c2a1, #F5C2A1);
}

.he60mdbwm {
  stop-color: var(--svg-color--f1bd46, #F1BD46);
}

.hgt5uebfs {
  stop-color: var(--svg-color--ddbe40, #DDBE40);
}

.ht2yfkjwb {
  stop-color: var(--svg-color--5dd2ff, #5DD2FF);
}

.hty4pzg0h {
  stop-color: var(--svg-color--e0a586, #E0A586);
}

.hv_0dkosg {
  stop-color: var(--svg-color--e3b291, #E3B291);
}

.i2-vql0bm {
  stop-color: var(--svg-color--3385fa, #3385FA);
}

.idibcljtc {
  stop-color: var(--svg-color--ffe15b, #FFE15B);
}

.itzskw0ez {
  stop-color: var(--svg-color--cc9682, #CC9682);
  stop-opacity: 0;
}

.iu8i86lxh {
  stop-color: var(--svg-color--f5c2a1, #F5C2A1);
  stop-opacity: 0;
}

.iz96j8ojk {
  stop-color: var(--svg-color--40bbff, #40BBFF);
}

.j15wz5dqx {
  d: path("M14.957 9.556c.148-1.182.828-1.271 1.277-1.23c1.075.097 2.836.48 3.899.789c.998.29.994.8.992 1.11v.042c0 .187-.067.533-.154.956l-.872 2.981a1.9 1.9 0 0 1-2.197 1.33l-1.813-.364a1.9 1.9 0 0 1-1.517-2.049l.232-2.361c.029-.188.057-.42.092-.708z");
}

.j72ij_b9t {
  stop-color: var(--svg-color--b98664, #B98664);
}

.j8x1vn0ks {
  stroke: var(--svg-color--99663d, #99663D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M20.363 10.353c-.156-.176-.418-.473-1.008-.492");
}

.j95z4_w8q {
  fill: var(--svg-color--000, #000);
  d: path("M18.82 11.617a.335.335 0 0 1 .393-.27a.335.335 0 0 1 .205.537l-.586-.108a.3.3 0 0 1-.011-.16");
}

.jbim1r-8q {
  stop-color: var(--svg-color--dca35e, #DCA35E);
  stop-opacity: 0;
}

.jh6rb_-if {
  stop-color: var(--svg-color--fff75e, #FFF75E);
}

.jj-ghzbrk {
  stop-color: var(--svg-color--f8d84f, #F8D84F);
  stop-opacity: 0;
}

.jmhzor_lw {
  fill-rule: evenodd;
  d: path("M3.597 7.761a.5.5 0 0 1 .64.302c.08.225.493.986 1.71 1.372a.5.5 0 0 1-.301.953C4.1 9.9 3.47 8.89 3.295 8.4a.5.5 0 0 1 .302-.639");
}

.jtpb4qi3h {
  d: path("m12.688 15.857l-2.141 7.86l4.61 2.171l4.421-1.953c.584-2.38 1.756-7.16 1.781-7.234c.032-.094.22-.844-.64-.97c-2.61-.359-6.328-.655-7.063-.687c-.587-.025-.89.531-.969.813");
}

.jx__8ve1w {
  stop-color: var(--svg-color--dca35e, #DCA35E);
}

.jyi503hrb {
  d: path("m8.398 8.445l.459.045c.064.006.127.02.181.055c.243.159.338.484.138.896l-.871 2.062l-.891-.84z");
}

.jzkbzcg7n {
  stop-color: var(--svg-color--d09b7e, #D09B7E);
}

.k_meu68sj {
  stop-color: var(--svg-color--d28476, #D28476);
}

.k10stfbid {
  stop-color: var(--svg-color--ecb497, #ECB497);
}

.kkkpn9_8c {
  stop-color: var(--svg-color--fff96d, #FFF96D);
}

.kw2cbbczi {
  d: path("M8.657 4.332c-1.06.276-1.684 1.099-1.907 1.439a.05.05 0 0 1-.044.022a2.7 2.7 0 0 1-.958-.256a.05.05 0 0 1-.02-.07c.25-.41.873-1.28 2.01-1.782a4.3 4.3 0 0 1 1.792-.381c.046 0 .07-.055.037-.087a4 4 0 0 0-.414-.357a.05.05 0 0 0-.034-.01a5.1 5.1 0 0 0-1.57.417a4.9 4.9 0 0 0-2.218 1.948a.05.05 0 0 1-.072.014a2.7 2.7 0 0 1-.597-.64a.05.05 0 0 1 0-.054A5.5 5.5 0 0 1 6.713 2.63c.318-.167.663-.274.95-.343c.05-.012.052-.083.001-.095a3.8 3.8 0 0 0-.837-.095h-.06l-.023.006c-.08.039-.16.07-.24.12a6 6 0 0 0-2.06 1.807a.05.05 0 0 1-.086-.009a4 4 0 0 1-.22-.747c-.007-.039-.055-.055-.083-.027a4 4 0 0 0-.294.336a.05.05 0 0 0-.01.043a4.2 4.2 0 0 0 .414 1.025a.2.2 0 0 0 .043.084A3.2 3.2 0 0 0 5.45 5.9c.489.26.95.338 1.208.354a.05.05 0 0 1 .045.036c.05.175.11.47.134.81a.05.05 0 0 1-.051.053c-.957-.029-1.725-.28-2.412-.782c-.95-.71-1.18-1.682-1.18-1.703c0-.026-.036-.025-.045 0a4.6 4.6 0 0 0-.182.672a.05.05 0 0 0 .004.032c.2.396.544.92 1.132 1.354c.948.704 1.926.86 2.662.886a.05.05 0 0 1 .048.055a2.7 2.7 0 0 1-.26.888a.05.05 0 0 1-.051.027c-2.542-.3-3.33-1.522-3.34-1.543a.2.2 0 0 0-.075-.077c-.03-.019-.06.012-.051.047c.092.333.22.64.382.93l.013.015c.512.387 1.371.842 2.722 1.047a.05.05 0 0 1 .03.082a2.6 2.6 0 0 1-.664.526c-.038.021-.035.078.006.092q.225.082.468.134a.05.05 0 0 0 .04-.008c.354-.257.619-.543.804-.85l.007-.01l.014-.023q.004-.014.01-.026a3.2 3.2 0 0 0 .41-1.304a4.2 4.2 0 0 0-.16-1.524a.05.05 0 0 1 .006-.042c.097-.148.307-.446.632-.716a.048.048 0 0 1 .074.013c.215.39.584 1.217.504 2.206c-.095 1.151-.597 1.852-1.018 2.252c-.035.034-.008.095.041.088q.32-.046.617-.13a.05.05 0 0 0 .025-.018c.372-.48.722-1.177.805-2.16c.09-1.151-.345-2.087-.591-2.517a.05.05 0 0 1 .018-.068a2.4 2.4 0 0 1 .863-.275a.05.05 0 0 1 .049.026c.256.511.996 2.214.409 3.929c-.018.05.044.092.081.054a4 4 0 0 0 .545-.702l.007-.019c.197-1.369-.236-2.602-.51-3.225a.05.05 0 0 1 .049-.07c.33.034.594.123.77.202c.04.018.085-.02.072-.061a5 5 0 0 0-.175-.461a.05.05 0 0 0-.03-.027a3.2 3.2 0 0 0-1.703-.036");
}

.l-fqg0bdm {
  stop-color: var(--svg-color--4087f7, #4087F7);
}

.lewi9xb7p {
  stop-color: var(--svg-color--e1af93, #E1AF93);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llsmmnb0k {
  stop-color: var(--svg-color--dea486, #DEA486);
  stop-opacity: 0;
}

.lltkvqb6g {
  cx: 16.291px;
  cy: 10.76px;
  rx: 0.254px;
  ry: 0.129px;
}

.lom2e0u5t {
  stop-color: var(--svg-color--be8677, #BE8677);
}

.lx7vkbc9m {
  d: path("M29.953 29.904v-6.508c-1.258-.305-2.197.101-2.875.664l-.3.251c-.982.822-1.38 1.155-2.434 1.155c-.819 0-1.343-.467-1.904-.967c-.644-.573-1.335-1.19-2.573-1.19c-1.172 0-1.858.48-2.503.93c-.572.398-1.11.774-1.927.774c-.711 0-1.16-.336-1.657-.71c-.622-.467-1.322-.993-2.714-.993c-1.097 0-1.755.569-2.394 1.122c-.605.524-1.194 1.034-2.125 1.034c-.969 0-1.56-.558-2.195-1.157q-.167-.16-.344-.32c-.625-.562-1.612-.705-1.961-.68v6.595z");
}

.m2ds08s7w {
  stop-color: var(--svg-color--2c89f2, #2C89F2);
  stop-opacity: 0;
}

.m618cgh3i {
  stop-color: var(--svg-color--cf8d73, #CF8D73);
}

.m7wei-y5y {
  stop-color: var(--svg-color--d2a391, #D2A391);
}

.mg6y3qeip {
  stop-color: var(--svg-color--e8b295, #E8B295);
}

.mtpoepbyz {
  d: path("m25.249 21.482l-4.64-4.266l.077-.906l4.141 3.828z");
}

.mu1lsrbfz {
  stop-color: var(--svg-color--6d4c42, #6D4C42);
}

.n1jti7bmr {
  d: path("M16.938 11.148c.034-.185-.093-.335-.126-.38l-.218.144l.071.252z");
}

.n2b8gu5vw {
  stop-color: var(--svg-color--5472f7, #5472F7);
}

.n4sb7zk9f {
  stop-color: var(--svg-color--c69272, #C69272);
}

.nattj0bij {
  stop-color: var(--svg-color--c89883, #C89883);
}

.nezdxyb3x {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.409 10.348a.91.91 0 0 0-.996.519c-.05.107.017.23.132.25l1.432.265a.15.15 0 0 0 .179-.147a.915.915 0 0 0-.747-.887");
}

.niaaygfag {
  fill: var(--svg-color--d59f85, #D59F85);
  d: path("m5.071 15.611l.335-6.413L8.5 8.823l-.257 5.484a.2.2 0 0 0 .177.209l5.08.572l-.953 2.954l-5.904-.598A1.75 1.75 0 0 1 5.07 15.61");
}

.nil-nrb9t {
  stop-color: var(--svg-color--ffffe9, #FFFFE9);
}

.nj1er27qb {
  stop-color: var(--svg-color--2c8bf2, #2C8BF2);
  stop-opacity: 0;
}

.nr7c7pb7v {
  stop-color: var(--svg-color--b77a70, #B77A70);
}

.nwz3krwdd {
  stop-color: var(--svg-color--c4857c, #C4857C);
  stop-opacity: 0;
}

.o0abx5bzz {
  stop-color: var(--svg-color--d28476, #D28476);
  stop-opacity: 0;
}

.o52n_hqhs {
  stop-color: var(--svg-color--412830, #412830);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh9s2ccbv {
  stop-color: var(--svg-color--cf8d73, #CF8D73);
  stop-opacity: 0;
}

.ooxfyv-aw {
  fill-rule: evenodd;
  d: path("M24.922 12.302a.5.5 0 0 1 .708.143c.189.27.824 1.181.696 2.537a.5.5 0 0 1-.996-.094a2.73 2.73 0 0 0-.524-1.876l-.01-.014a.5.5 0 0 1 .126-.696");
}

.oqaibvbqb {
  stop-color: var(--svg-color--f8d84f, #F8D84F);
}

.or1v7ccby {
  d: path("M14.585 15.505c.079-.437.325-.41.364-.418l4.347.38c.17-.017.503.091.485.647c-.117 1.329-1.25 2.618-3.035 2.329c-1.84-.278-2.321-1.895-2.16-2.938");
}

.oz1prabcs {
  stop-color: var(--svg-color--267dc5, #267DC5);
  stop-opacity: 0;
}

.p93njvi5m {
  stop-color: var(--svg-color--be897b, #BE897B);
}

.pdlduxt0m {
  stop-color: var(--svg-color--ffd739, #FFD739);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmnl_0bxq {
  d: path("M16.51 10.547a.583.583 0 0 0-.687.622l1.107.205a.587.587 0 0 0-.421-.827");
}

.pv-xo4bei {
  stop-color: var(--svg-color--fff665, #FFF665);
}

.pwm6c7b8r {
  fill: var(--svg-color--9b6432, #9B6432);
  fill-rule: evenodd;
  d: path("M19 9.929a.3.3 0 0 0 .29.31c.243.008.405.071.519.142c.118.074.197.162.275.25a.3.3 0 1 0 .449-.4l-.006-.005a1.8 1.8 0 0 0-.402-.354a1.6 1.6 0 0 0-.814-.233a.3.3 0 0 0-.31.29");
}

.pwyc_ob2i {
  stop-color: var(--svg-color--fff662, #FFF662);
}

.py6xm8bqh {
  d: path("M29.953 29.357V17.966c-1.258-.305-2.197.102-2.875.664l-.3.252c-.982.822-1.38 1.154-2.434 1.154c-.819 0-1.343-.467-1.904-.967c-.644-.573-1.335-1.189-2.573-1.189c-1.172 0-1.858.479-2.503.929c-.572.398-1.11.774-1.927.774c-.711 0-1.16-.336-1.657-.71c-.622-.467-1.322-.993-2.714-.993c-1.097 0-1.755.57-2.394 1.123c-.605.523-1.194 1.033-2.125 1.033c-.969 0-1.56-.557-2.195-1.156a20 20 0 0 0-.344-.32c-.625-.563-1.612-.706-1.961-.68v11.477z");
}

.q_druvruw {
  stop-color: var(--svg-color--3fb2ff, #3FB2FF);
  stop-opacity: 0;
}

.q3hk4_bla {
  stop-color: var(--svg-color--d9d1be, #D9D1BE);
}

.qj_hytbqn {
  d: path("M19.679 11.694a.55.55 0 0 0-.094-.325l-.201.153l.048.16z");
}

.qsi2djbas {
  stop-color: var(--svg-color--eaae49, #EAAE49);
}

.qvl3f1svv {
  stop-color: var(--svg-color--46a4f6, #46A4F6);
}

.r-65_82is {
  fill-rule: evenodd;
  d: path("M24.234 12.747a.5.5 0 0 1 .696.125l.04.056c.214.293.921 1.264.797 2.573a.5.5 0 0 1-.995-.094c.086-.915-.402-1.598-.617-1.9l-.046-.064a.5.5 0 0 1 .125-.696");
}

.r22hbpu9p {
  stop-color: var(--svg-color--ca8470, #CA8470);
}

.r6gvahbyk {
  cx: 16.291px;
  cy: 10.76px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.254px;
  ry: 0.129px;
}

.r6oa105rp {
  fill: var(--svg-color--000, #000);
  d: path("M16.732 11.18a.333.333 0 0 0-.268-.388a.333.333 0 0 0-.38.425l.58.107a.3.3 0 0 0 .068-.143");
}

.ris78_9sh {
  stop-color: var(--svg-color--ce8d7e, #CE8D7E);
}

.rl7ir4szc {
  stop-color: var(--svg-color--fdc69e, #FDC69E);
}

.rlocznbrk {
  stop-color: var(--svg-color--e59a2b, #E59A2B);
}

.rmpzr1bpn {
  stop-color: var(--svg-color--41aaff, #41AAFF);
}

.rvaghwbsu {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.56 13.083c.22.178.5.311.815.374c.317.064.624.048.897-.031a.15.15 0 0 1 .168.063a.14.14 0 0 1-.02.178m-1.86-.585l1.825.55m-1.826-.55a.15.15 0 0 0-.18-.005a.14.14 0 0 0-.05.171m.23-.165l-.183.146m2.044.438l-.035-.035m.035.035l-.035-.035m.035.035a1.27 1.27 0 0 1-1.157.349a1.27 1.27 0 0 1-.934-.768m2.056.384c-.277.279-.69.42-1.112.335a1.23 1.23 0 0 1-.897-.738m-.047.02l.047-.02m-.047.02v-.001l.047-.02");
}

.rwcn2nbsr {
  stop-color: var(--svg-color--d9944a, #D9944A);
}

.rzd60jbst {
  stop-color: var(--svg-color--3569a0, #3569A0);
}

.sjd5zkbdm {
  fill: var(--svg-color--2a71bb, #2A71BB);
  fill-rule: evenodd;
  d: path("m13.975 13.062l.305-3.094l.597.059l-.305 3.094a1.9 1.9 0 0 0 1.517 2.05l1.813.363a1.9 1.9 0 0 0 2.197-1.33l1.082-3.697l.576.168l-1.082 3.698a2.5 2.5 0 0 1-2.89 1.749l-1.813-.363a2.5 2.5 0 0 1-1.997-2.697");
}

.srsgrxbbq {
  stop-color: var(--svg-color--40b6ff, #40B6FF);
  stop-opacity: 0;
}

.sz6cbeb_j {
  d: path("M10.56 4.965c-.008-.026-.043-.037-.067-.048a2.5 2.5 0 0 0-.77-.201a.05.05 0 0 0-.05.069c.253.573.64 1.664.546 2.901c-.004.055.068.078.092.028a3.88 3.88 0 0 0 .248-2.75");
}

.t-6g_0b7g {
  stop-color: var(--svg-color--e9b79b, #E9B79B);
  stop-opacity: 0;
}

.t1ffwv_yc {
  stop-color: var(--svg-color--e0b93f, #E0B93F);
}

.t3ga4ibtc {
  stop-color: var(--svg-color--b68776, #B68776);
  stop-opacity: 0;
}

.t77dcut_r {
  stop-color: var(--svg-color--51c9ff, #51C9FF);
}

.tdiqapb8p {
  stop-color: var(--svg-color--795348, #795348);
}

.tvqvznkkw {
  stop-color: var(--svg-color--c89472, #C89472);
  stop-opacity: 0;
}

.uayuyob5b {
  stop-color: var(--svg-color--6aa5ea, #6AA5EA);
}

.upn6hw37x {
  stop-color: var(--svg-color--e2a548, #E2A548);
}

.uqh6nu2wx {
  stop-color: var(--svg-color--6aa5ea, #6AA5EA);
  stop-opacity: 0;
}

.uusmdck_a {
  d: path("M14.957 9.556c.148-1.182.828-1.271 1.277-1.23c1.075.097 2.836.48 3.899.789c1.044.303.992.847.992 1.152s-.18 1.035-.328 1.832c-.119.637.08.849.195.875c.117.02.4-.081.594-.656c.336-1.242 1.07-3.672.398-5.016s-1.718-1.789-2.937-2.023s-2.617-.25-3.656.656c-1.227.953-1.336 3.406-1.344 4.312s.086 1.344.406 1.243c.32-.102.324-.504.504-1.934");
}

.uzk5vp72a {
  stop-color: var(--svg-color--eab38c, #EAB38C);
}

.vi9q-fb9u {
  stop-color: var(--svg-color--ffcd36, #FFCD36);
}

.vvex-7byg {
  stop-color: var(--svg-color--c5ae5f, #C5AE5F);
}

.w1-vbdbpq {
  stop-color: var(--svg-color--fffa6e, #FFFA6E);
  stop-opacity: 0;
}

.w3225dbjw {
  stop-color: var(--svg-color--db9c35, #DB9C35);
}

.w4-c1u12h {
  stop-color: var(--svg-color--d39c52, #D39C52);
  stop-opacity: 0;
}

.w86h2iq4q {
  stop-color: var(--svg-color--ffe451, #FFE451);
  stop-opacity: 0;
}

.w8l-j4b1q {
  stop-color: var(--svg-color--2280cb, #2280CB);
  stop-opacity: 0;
}

.wda4yc_iv {
  stop-color: var(--svg-color--3f83e6, #3F83E6);
}

.wt-hn3yze {
  fill-rule: evenodd;
  d: path("M26.543 13.12a.5.5 0 0 1 .7.092c.268.346.663 1.257.366 2.406a.5.5 0 0 1-.968-.25c.211-.818-.09-1.416-.19-1.546a.5.5 0 0 1 .091-.701");
}

.x03fa-b4r {
  d: path("M3.161 7.038c.01.021.797 1.243 3.34 1.543a.05.05 0 0 0 .05-.027c.148-.296.227-.6.261-.888a.05.05 0 0 0-.048-.055c-.736-.026-1.714-.182-2.662-.886A3.75 3.75 0 0 1 3.07 5.559c-.024-.042-.088-.03-.093.017a4 4 0 0 0-.025.438c0 .37.029.727.208 1.024");
}

.x114bxlro {
  stop-color: var(--svg-color--f9cd54, #F9CD54);
}

.x7wf8bb9k {
  d: path("m17.592 11.295l-.535 1.014c-.11.208.014.46.247.503l.498.092a.348.348 0 0 0 .411-.381l-.137-1.139c-.028-.252-.365-.314-.484-.09");
}

.x9d7jz1fb {
  stop-color: var(--svg-color--d9afcd, #D9AFCD);
}

.xbbe_nbvg {
  d: path("M19.259 11.1a.588.588 0 0 1 .422.833l-1.117-.206a.59.59 0 0 1 .694-.627");
}

.xekx4ab0f {
  d: path("M5.378 9.612a.25.25 0 0 0 .14-.004a2.6 2.6 0 0 0 .664-.526a.05.05 0 0 0-.03-.082c-1.133-.172-1.92-.52-2.446-.855c-.045-.03-.1.023-.07.068a3.73 3.73 0 0 0 1.742 1.399");
}

.xf6fc56wi {
  stop-color: var(--svg-color--3072a5, #3072A5);
}

.xpbv08bvr {
  stop-color: var(--svg-color--d2a391, #D2A391);
  stop-opacity: 0;
}

.xtrjnaccv {
  stop-color: var(--svg-color--ffd739, #FFD739);
  stop-opacity: 0;
}

.y0urfl-9x {
  stop-color: var(--svg-color--b47a78, #B47A78);
}

.y1-ru4g2h {
  stop-color: var(--svg-color--e1a992, #E1A992);
  stop-opacity: 0;
}

.ybbdkp2ua {
  stop-color: var(--svg-color--eebd9f, #EEBD9F);
}

.ysa1wwbdb {
  stop-color: var(--svg-color--ecb497, #ECB497);
  stop-opacity: 0;
}

.zc4a7s-lt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.19 11.215c.031.062-.066.113-.177.168c-.11.054-.192.092-.223.03c-.03-.062.034-.157.145-.212s.225-.048.256.014");
}

.zmhergcsk {
  stop-color: var(--svg-color--d09980, #D09980);
}

.zu_6ow2qk {
  d: path("M19.19 11.215c.031.062-.066.113-.177.168c-.11.054-.192.092-.223.03c-.03-.062.034-.157.145-.212s.225-.048.256.014");
}

.zusf43kae {
  stop-color: var(--svg-color--c4857c, #C4857C);
}

</style>
