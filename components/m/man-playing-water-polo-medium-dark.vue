<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iR2tayb)"><path fill="url(#iUOMohd)" class="j7u5_7b5u"/></g><path fill="url(#iTtD1Je)" class="fzu3zcawf"/><g filter="url(#iP0ex0b)"><path class="e49-6r6yi"/><path fill="url(#iWQtB3c)" class="jm45idbtg"/></g><path fill="url(#iJBWyde)" clip-rule="evenodd" class="sy7-q781r"/><path fill="url(#ivLQbEd)" clip-rule="evenodd" class="zvs-cxsdn"/><path fill="url(#iMKZ7sd)" clip-rule="evenodd" class="j8to7olee"/><path fill="url(#icvkWuZ)" clip-rule="evenodd" class="lc3ez7bfp"/><path fill="url(#iOByrSd)" clip-rule="evenodd" class="lc3ez7bfp"/><path fill="url(#iiduoce)" clip-rule="evenodd" class="e4g-598-g"/><path fill="url(#iDtb5JB)" class="o4msl8bjb"/><g filter="url(#iDPJ4qd)"><path clip-rule="evenodd" class="k-ju00mah"/><path fill="url(#ik8A2zc)" clip-rule="evenodd" class="igbluxbhg"/><path fill="url(#iomweJe)" clip-rule="evenodd" class="igbluxbhg"/></g><g filter="url(#iIW4jhe)"><path fill="url(#iPjN02c)" class="eoc0fgb5c"/></g><path fill="url(#i5DmvYq)" class="lcvj76bae"/><path fill="url(#iS3U99S)" class="ffyzg_nol"/><path fill="url(#iKf3sCe)" class="ffyzg_nol"/><path fill="url(#isWeskx)" class="mpo0zwbic"/><path fill="url(#imRsFew)" class="p8d_bws2x"/><path fill="url(#idrZL1i)" class="p8d_bws2x"/><path fill="url(#is1Yhed)" class="fodmxruzl"/><path fill="url(#iel3Xie)" class="fodmxruzl"/><path fill="url(#iUBOG5b)" class="fodmxruzl"/><g filter="url(#iTYwfie)"><path fill="url(#irNOKvd)" class="f71d18bmm"/></g><g filter="url(#iGDfJbc)"><path fill="url(#i14KNqd)" class="qoalrcbnl"/></g><path fill="url(#ig8yRQC)" class="tqz-m9b5q"/><path fill="url(#iLockUf)" class="tqz-m9b5q"/><path fill="url(#iNV2fnW)" class="ot_s2ab4a"/><path fill="url(#idOennb)" class="ot_s2ab4a"/><path fill="url(#iKbJmuc)" class="zbaxvmghd"/><path fill="url(#iNhw0Yz)" class="zbaxvmghd"/><path fill="url(#iS25d1c)" class="xhmvd3bcy"/><path fill="url(#iHi7C3b)" class="xhmvd3bcy"/><path fill="url(#iXkrzVb)" class="xhmvd3bcy"/><path fill="url(#i9Vg1Ud)" class="xhmvd3bcy"/><path fill="url(#iiHoYVF)" class="xhmvd3bcy"/><path fill="url(#iKxZkuS)" class="xhmvd3bcy"/><path fill="url(#i3oalGe)" class="y48pl-2sa"/><path fill="url(#iroKr5b)" class="y48pl-2sa"/><path fill="url(#iS1pQ5b)" class="y48pl-2sa"/><g filter="url(#ihWKPBb)"><path fill="url(#ik42NfN)" class="b2hap_ioj"/><path fill="url(#isaWgKb)" class="b2hap_ioj"/><path fill="url(#iqByUEc)" class="b2hap_ioj"/></g><path clip-rule="evenodd" class="ur9uw6b9b"/><g filter="url(#i6KRynj)"><path class="nmprvob2h"/></g><g filter="url(#i1RSPke)"><path fill="url(#ivCSKse)" class="gtwhuibhm"/><path fill="url(#iZH0bLd)" class="gtwhuibhm"/></g><path stroke="url(#iITa0cb)" class="r_t0zy9vt"/><path class="kzv2ipo0z"/><path fill="url(#ig3aAxb)" class="p7cow0b7d"/><path class="qk9w2-gwc"/><g filter="url(#iwsuhYc)"><path class="mvrli-bgh"/><path fill="url(#i8W1kIc)" class="l_db2rbuw"/></g><g filter="url(#irAhRcb)"><path fill="url(#ifA0Ktb)" class="wws-k6_xt"/></g><path class="x55o2eq8z"/><path fill="url(#i97UInP)" class="ll5cge3tz"/><path class="quq9pabmg"/><g filter="url(#i01oeHd)"><path fill="url(#iqFEyAd)" class="z5cog-bec"/></g><g filter="url(#iR8dD8W)"><ellipse transform="rotate(-17.442 16.668 11.27)" class="ay91dbc_f"/><ellipse fill="url(#iURvSac)" transform="rotate(-17.442 16.668 11.27)" class="o08d5ab1q"/></g><g filter="url(#i1E3Mnb)"><path fill="url(#iExOIAe)" class="dwd729v_l"/></g><path fill="url(#iOb5McF)" class="xp6kfq0_i"/><path fill="url(#i32K8td)" class="xp6kfq0_i"/><path fill="url(#i30KA7g)" class="xp6kfq0_i"/><path fill="url(#ikib78b)" class="xp6kfq0_i"/><g filter="url(#iC4MZdc)"><path fill="url(#i3Nhu5d)" class="vr46bbbzw"/></g><g filter="url(#i6gd3xb)"><path clip-rule="evenodd" class="skulo7b5p"/></g><g filter="url(#iCYNTTd)"><path class="znpsn40vf"/></g><g filter="url(#iz8dzGd)"><path clip-rule="evenodd" class="aoegllbsc"/></g><g filter="url(#iGrmiFb)"><path class="tcrz9obtu"/></g><defs><radialGradient id="iWQtB3c" cx="0" cy="0" r="1" gradientTransform="rotate(-171.733 7.753 7.403)scale(3.69464 3.85482)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="j8h3dgbhd"/><stop offset="1" class="xq_1inbmx"/></radialGradient><radialGradient id="iJBWyde" cx="0" cy="0" r="1" gradientTransform="matrix(-.55594 1.94881 -1.48215 -.42282 25.159 13.212)" gradientUnits="userSpaceOnUse"><stop class="u44kqtbwx"/><stop offset=".384" class="dmrsrxbbr"/></radialGradient><radialGradient id="iMKZ7sd" cx="0" cy="0" r="1" gradientTransform="matrix(-.51606 1.90495 -1.38608 -.3755 25.791 12.765)" gradientUnits="userSpaceOnUse"><stop class="u44kqtbwx"/><stop offset=".384" class="dmrsrxbbr"/></radialGradient><radialGradient id="icvkWuZ" cx="0" cy="0" r="1" gradientTransform="rotate(113.89 9.242 15.211)scale(1.87125 1.68165)" gradientUnits="userSpaceOnUse"><stop class="dbphouvft"/><stop offset=".467" class="o52n_hqhs"/></radialGradient><radialGradient id="iOByrSd" cx="0" cy="0" r="1" gradientTransform="rotate(113.89 9.242 15.211)scale(1.87125 1.68165)" gradientUnits="userSpaceOnUse"><stop class="c3i1aoblk"/><stop offset=".467" class="pve28abei"/></radialGradient><radialGradient id="iiduoce" cx="0" cy="0" r="1" gradientTransform="matrix(-.67866 1.61156 -1.399 -.58915 27.563 13.715)" gradientUnits="userSpaceOnUse"><stop class="c3i1aoblk"/><stop offset=".467" class="kv0towb6e"/></radialGradient><radialGradient id="iDtb5JB" cx="0" cy="0" r="1" gradientTransform="matrix(-.424 .6523 -1.8923 -1.23 25.203 16.127)" gradientUnits="userSpaceOnUse"><stop class="pt3kuccrj"/><stop offset=".438" class="irk_qbcrg"/></radialGradient><radialGradient id="ik8A2zc" cx="0" cy="0" r="1" gradientTransform="matrix(1.467 -1.9886 6.33088 4.67033 21.233 20.776)" gradientUnits="userSpaceOnUse"><stop class="bgex3sn2v"/><stop offset="1" class="klh3qabex"/></radialGradient><radialGradient id="iomweJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.83537 -1.45884 0 25.568 16.277)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="je851xbvd"/><stop offset="1" class="pkvze_bui"/></radialGradient><radialGradient id="i5DmvYq" cx="0" cy="0" r="1" gradientTransform="matrix(-.90626 2.21874 -3.49772 -1.42868 5.034 4.898)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t1ffwv_yc"/><stop offset="1" class="he60mdbwm"/></radialGradient><radialGradient id="iS3U99S" cx="0" cy="0" r="1" gradientTransform="matrix(-.96014 1.99895 -3.51333 -1.68753 4.88 6.601)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="c6s8j5o0k"/><stop offset="1" class="upn6hw37x"/></radialGradient><radialGradient id="iKf3sCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.51562 1.39063 -3.21171 -1.19085 5.659 7.351)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="w4-c1u12h"/><stop offset="1" class="db6hxbc6j"/></radialGradient><radialGradient id="isWeskx" cx="0" cy="0" r="1" gradientTransform="matrix(.41141 1.3754 -2.82798 .8459 3.883 8.518)" gradientUnits="userSpaceOnUse"><stop offset=".05" class="w3225dbjw"/><stop offset="1" class="rwcn2nbsr"/></radialGradient><radialGradient id="imRsFew" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1467 4.65626 -2.92783 -.72104 8.721 5.992)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="idibcljtc"/><stop offset="1" class="rlocznbrk"/></radialGradient><radialGradient id="is1Yhed" cx="0" cy="0" r="1" gradientTransform="rotate(84.147 1.892 7.922)scale(3.98377 3.9383)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="kkkpn9_8c"/><stop offset="1" class="qsi2djbas"/></radialGradient><radialGradient id="iel3Xie" cx="0" cy="0" r="1" gradientTransform="matrix(.55769 3.79546 -10.478 1.5396 8.721 6.414)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="jbim1r-8q"/><stop offset=".887" class="jx__8ve1w"/></radialGradient><radialGradient id="iUBOG5b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10157 -3.50206 7.04927 -2.21735 10.073 8.734)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="w1-vbdbpq"/><stop offset="1" class="vi9q-fb9u"/></radialGradient><radialGradient id="irNOKvd" cx="0" cy="0" r="1" gradientTransform="matrix(.95313 1.7322 -1.31372 .72286 10.127 5.402)" gradientUnits="userSpaceOnUse"><stop class="pwyc_ob2i"/><stop offset="1" class="x114bxlro"/></radialGradient><radialGradient id="i14KNqd" cx="0" cy="0" r="1" gradientTransform="rotate(-103.141 6.581 -1.11)scale(1.5807 2.46179)" gradientUnits="userSpaceOnUse"><stop class="jh6rb_-if"/><stop offset="1" class="btbmkccji"/></radialGradient><radialGradient id="ig8yRQC" cx="0" cy="0" r="1" gradientTransform="rotate(-100.73 5.749 -1.165)scale(1.84923 2.37953)" gradientUnits="userSpaceOnUse"><stop class="jh6rb_-if"/><stop offset="1" class="btbmkccji"/></radialGradient><radialGradient id="iLockUf" cx="0" cy="0" r="1" gradientTransform="rotate(151.204 3.42 3.438)scale(2.69231 1.10958)" gradientUnits="userSpaceOnUse"><stop offset=".874" class="pv-xo4bei"/><stop offset="1" class="w86h2iq4q"/></radialGradient><radialGradient id="iNV2fnW" cx="0" cy="0" r="1" gradientTransform="matrix(-.9922 -.60156 1.5104 -2.49122 5.807 3.734)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="hgt5uebfs"/><stop offset="1" class="vvex-7byg"/></radialGradient><radialGradient id="idOennb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55468 1.19532 -.2462 -.32022 6.464 3.264)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="oqaibvbqb"/><stop offset="1" class="jj-ghzbrk"/></radialGradient><radialGradient id="iKbJmuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -6.9375 10.4709 -.04717 6.565 10.836)" gradientUnits="userSpaceOnUse"><stop class="x9d7jz1fb"/><stop offset="1" class="nil-nrb9t"/></radialGradient><radialGradient id="iNhw0Yz" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 -2.87499 4.0482 -7.17238 8.846 7.367)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="aljt7ncuz"/><stop offset="1" class="q3hk4_bla"/></radialGradient><radialGradient id="iS25d1c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.68754 8.59373 -8.59905 -3.68982 19.315 18.242)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="rmpzr1bpn"/><stop offset="1" class="eysgdi55n"/></radialGradient><radialGradient id="iXkrzVb" cx="0" cy="0" r="1" gradientTransform="rotate(99.197 .979 13.92)scale(3.32398 6.99637)" gradientUnits="userSpaceOnUse"><stop class="xf6fc56wi"/><stop offset="1" class="oz1prabcs"/></radialGradient><radialGradient id="i9Vg1Ud" cx="0" cy="0" r="1" gradientTransform="rotate(6.921 -126.3 172.916)scale(2.72297 .91041)" gradientUnits="userSpaceOnUse"><stop class="cp11-1gcm"/><stop offset="1" class="srsgrxbbq"/></radialGradient><radialGradient id="iiHoYVF" cx="0" cy="0" r="1" gradientTransform="matrix(.30078 2.59375 -2.78882 .3234 17.659 16.69)" gradientUnits="userSpaceOnUse"><stop offset=".906" class="c9s-hpbqa"/><stop offset="1" class="gkz0xj0po"/></radialGradient><radialGradient id="iKxZkuS" cx="0" cy="0" r="1" gradientTransform="matrix(.29688 2.5625 -2.75522 .3192 17.659 16.69)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="uayuyob5b"/><stop offset=".954" class="uqh6nu2wx"/></radialGradient><radialGradient id="i3oalGe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 4 -6.15337 4.1343 16.002 15.398)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="jx45yjlfo"/><stop offset=".876" class="e3_7pgb3y"/></radialGradient><radialGradient id="iroKr5b" cx="0" cy="0" r="1" gradientTransform="rotate(168.536 8.32 8.628)scale(4.55972 1.90182)" gradientUnits="userSpaceOnUse"><stop offset=".514" class="nw16d5muy"/><stop offset="1" class="d7y73d45o"/></radialGradient><radialGradient id="iS1pQ5b" cx="0" cy="0" r="1" gradientTransform="rotate(157.999 8.551 10.067)scale(1.66837 .64809)" gradientUnits="userSpaceOnUse"><stop class="emput3bhq"/><stop offset="1" class="n_yku1v-w"/></radialGradient><radialGradient id="ik42NfN" cx="0" cy="0" r="1" gradientTransform="rotate(151.705 8.166 8.878)scale(4.5073 3.94979)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="iqirvccxe"/><stop offset="1" class="bqfwc3bya"/></radialGradient><radialGradient id="isaWgKb" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -.84375 .99271 .29414 16.893 11.039)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="pswnefbva"/><stop offset="1" class="ia_bp8w6o"/></radialGradient><radialGradient id="iqByUEc" cx="0" cy="0" r="1" gradientTransform="matrix(.30378 -1.00727 1.1851 .35741 19.785 11.53)" gradientUnits="userSpaceOnUse"><stop class="pswnefbva"/><stop offset="1" class="ia_bp8w6o"/></radialGradient><radialGradient id="ivCSKse" cx="0" cy="0" r="1" gradientTransform="rotate(178.156 9.164 6.528)scale(1.07184 3.25765)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="zepb-5s8y"/><stop offset=".491" class="rglr48bfo"/></radialGradient><radialGradient id="iZH0bLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.32092 1.22102 -1.83089 -.48121 18.252 12.148)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="l2tuc8b4n"/><stop offset=".983" class="j_zhj-bkx"/></radialGradient><radialGradient id="iITa0cb" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 -.32813 1.229 1.17048 16.9 14.19)" gradientUnits="userSpaceOnUse"><stop class="mly26fbqy"/><stop offset="1" class="gdi6d5gtd"/></radialGradient><radialGradient id="ig3aAxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2953 .56697 -.67087 -.34941 19.67 11.815)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="tdiqapb8p"/><stop offset="1" class="mu1lsrbfz"/></radialGradient><radialGradient id="i8W1kIc" cx="0" cy="0" r="1" gradientTransform="rotate(-117.34 13.345 .062)scale(.24737 .34057)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i97UInP" cx="0" cy="0" r="1" gradientTransform="matrix(-.29297 .5625 -.66558 -.34666 16.923 11.26)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="tdiqapb8p"/><stop offset="1" class="mu1lsrbfz"/></radialGradient><radialGradient id="iURvSac" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.978 -2.462)scale(.32222 .38731)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOb5McF" cx="0" cy="0" r="1" gradientTransform="matrix(-4.78124 5.34377 -6.51613 -5.83019 20.94 6.617)" gradientUnits="userSpaceOnUse"><stop class="iz96j8ojk"/><stop offset="1" class="i2-vql0bm"/></radialGradient><radialGradient id="i32K8td" cx="0" cy="0" r="1" gradientTransform="matrix(.30078 -1.59375 3.79885 .71694 18.53 9.71)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="n2b8gu5vw"/><stop offset="1" class="nj1er27qb"/></radialGradient><radialGradient id="i30KA7g" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 1.59375 -3.9358 4.01296 15.377 6.398)" gradientUnits="userSpaceOnUse"><stop class="gmg8hcbdj"/><stop offset="1" class="m2ds08s7w"/></radialGradient><radialGradient id="ikib78b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40626 -2.65624 1.89737 -1.7188 21.909 7.836)" gradientUnits="userSpaceOnUse"><stop class="ht2yfkjwb"/><stop offset="1" class="q_druvruw"/></radialGradient><filter id="iR2tayb" width="28.306" height="11.645" x="2.274" y="18.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.572549 0 0 0 0 0.819608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.619608 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23705" result="effect2_innerShadow_3987_23705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.886275 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_23705" result="effect3_innerShadow_3987_23705"/></filter><filter id="iP0ex0b" width="8.631" height="9.819" x="5.446" y="8.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.243137 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23705"/></filter><filter id="iDPJ4qd" width="9.358" height="9.592" x="19.241" y="14.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.223529 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23705"/></filter><filter id="iIW4jhe" width="5.441" height="5.972" x="20.586" y="16.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23705" stdDeviation=".2"/></filter><filter id="iTYwfie" width="1.134" height="3.026" x="10.046" y="5.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23705"/></filter><filter id="iGDfJbc" width="4.669" height="2.54" x="6.098" y="3.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.768627 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23705"/></filter><filter id="ihWKPBb" width="6.713" height="7.553" x="14.94" y="8.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.188235 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23705"/></filter><filter id="i6KRynj" width="2.2" height="2.754" x="16.711" y="11.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23705" stdDeviation=".25"/></filter><filter id="i1RSPke" width="1.4" height="1.954" x="17.294" y="11.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23705" stdDeviation=".05"/></filter><filter id="iwsuhYc" width=".514" height=".381" x="19.11" y="11.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23705" stdDeviation=".025"/></filter><filter id="irAhRcb" width=".395" height=".425" x="19.711" y="11.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23705" stdDeviation=".025"/></filter><filter id="i01oeHd" width=".45" height=".496" x="16.922" y="11.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23705" stdDeviation=".025"/></filter><filter id="iR8dD8W" width=".591" height=".389" x="16.373" y="11.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23705" stdDeviation=".025"/></filter><filter id="i1E3Mnb" width="28.306" height="6.762" x="2.274" y="23.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.368627 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.458824 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23705" result="effect2_innerShadow_3987_23705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.619608 0 0 0 0 0.988235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_23705" result="effect3_innerShadow_3987_23705"/></filter><filter id="iC4MZdc" width="2.176" height="6.768" x="6.632" y="10.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23705" stdDeviation=".2"/></filter><filter id="i6gd3xb" width="1.725" height=".918" x="16.066" y="9.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0156863 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23705"/></filter><filter id="iCYNTTd" width="1.625" height=".618" x="16.116" y="9.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23705" stdDeviation=".075"/></filter><filter id="iz8dzGd" width="1.608" height="1.292" x="19.386" y="9.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0156863 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23705"/></filter><filter id="iGrmiFb" width="1.508" height=".992" x="19.491" y="10.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23705" stdDeviation=".075"/></filter><linearGradient id="iUOMohd" x1="30.331" x2="7.179" y1="21.961" y2="31.381" gradientUnits="userSpaceOnUse"><stop class="t77dcut_r"/><stop offset=".78" class="qvl3f1svv"/></linearGradient><linearGradient id="iTtD1Je" x1="8.612" x2="9.846" y1="11.008" y2="9.351" gradientUnits="userSpaceOnUse"><stop offset=".174" class="f35kr1b2b"/><stop offset="1" class="g47ni5_fz"/></linearGradient><linearGradient id="ivLQbEd" x1="5.159" x2="6.674" y1="10.117" y2="10.758" gradientUnits="userSpaceOnUse"><stop class="wb6ooab1e"/><stop offset=".917" class="sa851lbem"/></linearGradient><linearGradient id="iPjN02c" x1="25.095" x2="18.33" y1="21.261" y2="14.823" gradientUnits="userSpaceOnUse"><stop offset=".298" class="nwegx7xkg"/><stop offset="1" class="lb8owybif"/></linearGradient><linearGradient id="idrZL1i" x1="7.713" x2="7.924" y1="6.156" y2="6.32" gradientUnits="userSpaceOnUse"><stop offset=".139" class="pdlduxt0m"/><stop offset="1" class="xtrjnaccv"/></linearGradient><linearGradient id="iHi7C3b" x1="11.627" x2="14.346" y1="21.273" y2="21.961" gradientUnits="userSpaceOnUse"><stop class="rzd60jbst"/><stop offset="1" class="w8l-j4b1q"/></linearGradient><linearGradient id="ifA0Ktb" x1="20.073" x2="19.848" y1="12.045" y2="12.132" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqFEyAd" x1="17.302" x2="17.078" y1="11.485" y2="11.572" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iExOIAe" x1="20.471" x2="1.784" y1="29.211" y2="21.586" gradientUnits="userSpaceOnUse"><stop class="l-fqg0bdm"/><stop offset="1" class="wda4yc_iv"/></linearGradient><linearGradient id="i3Nhu5d" x1="7.986" x2="7.845" y1="10.698" y2="19.136" gradientUnits="userSpaceOnUse"><stop class="z8efi882d"/><stop offset="1" class="v81yadizx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-playing-water-polo-medium-dark" /></template>
<style>
.aljt7ncuz {
  stop-color: var(--svg-color--d9d1be, #D9D1BE);
  stop-opacity: 0;
}

.aoegllbsc {
  fill: var(--svg-color--1d0e22, #1D0E22);
  fill-rule: evenodd;
  d: path("M19.386 10.47a.3.3 0 0 0 .29.31a1 1 0 0 1 .518.142c.118.073.198.161.276.249a.3.3 0 1 0 .443-.405c-.08-.088-.207-.233-.402-.354a1.6 1.6 0 0 0-.815-.232a.3.3 0 0 0-.31.29");
}

.ay91dbc_f {
  cx: 16.668px;
  cy: 11.27px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.254px;
  ry: 0.129px;
}

.b2hap_ioj {
  d: path("M15.335 10.066c.148-1.182.828-1.271 1.277-1.23c1.074.097 2.836.48 3.898.789c.999.29.995.8.993 1.11v.042c0 .187-.068.533-.154.956l-.873 2.981a1.9 1.9 0 0 1-2.197 1.33l-1.812-.364a1.9 1.9 0 0 1-1.517-2.049l.232-2.361c.028-.188.057-.42.091-.708z");
}

.bgex3sn2v {
  stop-color: var(--svg-color--6c3139, #6C3139);
}

.bqfwc3bya {
  stop-color: var(--svg-color--6c464a, #6C464A);
}

.btbmkccji {
  stop-color: var(--svg-color--fbcd40, #FBCD40);
}

.c3i1aoblk {
  stop-color: var(--svg-color--9c7c71, #9C7C71);
}

.c6s8j5o0k {
  stop-color: var(--svg-color--daae44, #DAAE44);
}

.c9s-hpbqa {
  stop-color: var(--svg-color--44adff, #44ADFF);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cp11-1gcm {
  stop-color: var(--svg-color--5cc5ff, #5CC5FF);
}

.d7y73d45o {
  stop-color: var(--svg-color--5b3c3c, #5B3C3C);
  stop-opacity: 0;
}

.db6hxbc6j {
  stop-color: var(--svg-color--d39c52, #D39C52);
}

.dbphouvft {
  stop-color: var(--svg-color--685957, #685957);
}

.dmrsrxbbr {
  stop-color: var(--svg-color--693d3d, #693D3D);
}

.dwd729v_l {
  d: path("M30.33 30.414v-6.508c-1.257-.305-2.197.102-2.874.664l-.302.251c-.981.823-1.378 1.155-2.433 1.155c-.818 0-1.343-.467-1.904-.967c-.643-.573-1.334-1.189-2.572-1.189c-1.173 0-1.859.479-2.504.929c-.571.398-1.11.774-1.926.774c-.712 0-1.16-.336-1.657-.71c-.623-.467-1.323-.993-2.714-.993c-1.098 0-1.755.57-2.395 1.123c-.605.523-1.194 1.033-2.125 1.033c-.968 0-1.56-.557-2.194-1.156a20 20 0 0 0-.345-.32c-.625-.563-1.612-.706-1.96-.68v6.594z");
}

.e3_7pgb3y {
  stop-color: var(--svg-color--755050, #755050);
}

.e49-6r6yi {
  fill: var(--svg-color--765145, #765145);
  d: path("m5.449 16.121l.335-6.413l3.093-.375l-.256 5.485a.2.2 0 0 0 .177.208l5.08.572l-.954 2.954l-5.904-.598a1.75 1.75 0 0 1-1.57-1.834");
}

.e4g-598-g {
  fill-rule: evenodd;
  d: path("M26.92 13.63a.5.5 0 0 1 .701.092c.267.346.662 1.257.366 2.406a.5.5 0 1 1-.969-.25c.212-.818-.089-1.416-.189-1.546a.5.5 0 0 1 .091-.701");
}

.emput3bhq {
  stop-color: var(--svg-color--907168, #907168);
}

.eoc0fgb5c {
  d: path("m25.627 21.992l-4.641-4.266l.078-.906l4.14 3.828z");
}

.eysgdi55n {
  stop-color: var(--svg-color--2175c0, #2175C0);
}

.f35kr1b2b {
  stop-color: var(--svg-color--724c4d, #724C4D);
}

.f71d18bmm {
  d: path("M10.937 5.475c-.008-.026-.042-.037-.067-.048a2.5 2.5 0 0 0-.77-.201a.05.05 0 0 0-.05.069c.254.573.64 1.664.546 2.901c-.004.055.069.078.093.028a3.88 3.88 0 0 0 .248-2.75");
}

.ffyzg_nol {
  d: path("M3.539 7.548c.01.021.797 1.243 3.34 1.543a.05.05 0 0 0 .05-.027c.147-.296.227-.6.26-.888a.05.05 0 0 0-.047-.055c-.736-.026-1.715-.182-2.663-.886a3.75 3.75 0 0 1-1.03-1.166c-.025-.042-.088-.03-.094.017a4 4 0 0 0-.024.439c0 .369.028.726.208 1.023");
}

.fodmxruzl {
  d: path("M9.905 9.305c.025-.025.013-.08.022-.114l.001-.004c.588-1.714-.152-3.418-.409-3.929a.05.05 0 0 0-.048-.026a2.4 2.4 0 0 0-.864.275a.05.05 0 0 0-.018.068c.246.43.682 1.366.591 2.517c-.073.872-.356 1.518-.679 1.989c-.028.04.011.093.057.076a3.9 3.9 0 0 0 1.347-.852");
}

.ft5dv1b6b {
  fill: none;
}

.fzu3zcawf {
  d: path("m8.775 8.96l.46.046a.4.4 0 0 1 .18.056c.243.158.339.483.138.895l-.87 2.062l-.892-.84z");
}

.g47ni5_fz {
  stop-color: var(--svg-color--846257, #846257);
}

.gdi6d5gtd {
  stop-color: var(--svg-color--836562, #836562);
  stop-opacity: 0;
}

.gkz0xj0po {
  stop-color: var(--svg-color--44abff, #44ABFF);
  stop-opacity: 0;
}

.gmg8hcbdj {
  stop-color: var(--svg-color--3c7dbf, #3C7DBF);
}

.gtwhuibhm {
  d: path("m17.97 11.805l-.536 1.014c-.11.208.014.46.248.503l.497.093a.348.348 0 0 0 .412-.382l-.138-1.139c-.028-.251-.364-.313-.484-.09");
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

.i2-vql0bm {
  stop-color: var(--svg-color--3385fa, #3385FA);
}

.ia_bp8w6o {
  stop-color: var(--svg-color--6c4249, #6C4249);
  stop-opacity: 0;
}

.idibcljtc {
  stop-color: var(--svg-color--ffe15b, #FFE15B);
}

.igbluxbhg {
  fill-rule: evenodd;
  d: path("M26.526 15.023c.856 0 1.573.425 1.573 1.281v5.858c0 1.69-2.003 2.58-3.257 1.446l-5.09-4.599a1.55 1.55 0 1 1 2.079-2.3l3.008 2.719a.1.1 0 0 0 .167-.071l.098-3.053c0-.856.566-1.28 1.422-1.28");
}

.iqirvccxe {
  stop-color: var(--svg-color--966a5b, #966A5B);
}

.irk_qbcrg {
  stop-color: var(--svg-color--6d3d3f, #6D3D3F);
}

.iz96j8ojk {
  stop-color: var(--svg-color--40bbff, #40BBFF);
}

.j_zhj-bkx {
  stop-color: var(--svg-color--76414c, #76414C);
}

.j7u5_7b5u {
  d: path("M30.33 29.867v-11.39c-1.257-.305-2.197.1-2.874.663l-.302.252c-.981.822-1.378 1.155-2.433 1.155c-.818 0-1.343-.468-1.904-.967c-.643-.574-1.334-1.19-2.572-1.19c-1.173 0-1.859.48-2.504.929c-.571.399-1.11.774-1.926.774c-.712 0-1.16-.336-1.657-.71c-.623-.467-1.323-.993-2.714-.993c-1.098 0-1.755.57-2.395 1.123c-.605.524-1.194 1.034-2.125 1.034c-.968 0-1.56-.558-2.194-1.157a20 20 0 0 0-.345-.32c-.625-.562-1.612-.706-1.96-.68v11.477z");
}

.j8h3dgbhd {
  stop-color: var(--svg-color--604339, #604339);
}

.j8to7olee {
  fill-rule: evenodd;
  d: path("M25.3 12.812a.5.5 0 0 1 .708.143c.188.27.823 1.181.695 2.537a.5.5 0 0 1-.995-.094a2.73 2.73 0 0 0-.534-1.89a.5.5 0 0 1 .125-.696");
}

.jbim1r-8q {
  stop-color: var(--svg-color--dca35e, #DCA35E);
  stop-opacity: 0;
}

.je851xbvd {
  stop-color: var(--svg-color--72433f, #72433F);
}

.jh6rb_-if {
  stop-color: var(--svg-color--fff75e, #FFF75E);
}

.jj-ghzbrk {
  stop-color: var(--svg-color--f8d84f, #F8D84F);
  stop-opacity: 0;
}

.jm45idbtg {
  d: path("m5.449 16.121l.335-6.413l3.093-.375l-.256 5.485a.2.2 0 0 0 .177.208l5.08.572l-.954 2.954l-5.904-.598a1.75 1.75 0 0 1-1.57-1.834");
}

.jx__8ve1w {
  stop-color: var(--svg-color--dca35e, #DCA35E);
}

.jx45yjlfo {
  stop-color: var(--svg-color--895d55, #895D55);
}

.k-ju00mah {
  fill: var(--svg-color--7d594a, #7D594A);
  fill-rule: evenodd;
  d: path("M26.526 15.023c.856 0 1.573.425 1.573 1.281v5.858c0 1.69-2.003 2.58-3.257 1.446l-5.09-4.599a1.55 1.55 0 1 1 2.079-2.3l3.008 2.719a.1.1 0 0 0 .167-.071l.098-3.053c0-.856.566-1.28 1.422-1.28");
}

.kkkpn9_8c {
  stop-color: var(--svg-color--fff96d, #FFF96D);
}

.klh3qabex {
  stop-color: var(--svg-color--835357, #835357);
  stop-opacity: 0;
}

.kv0towb6e {
  stop-color: var(--svg-color--7d584a, #7D584A);
}

.kzv2ipo0z {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.803 11.459a.92.92 0 0 1 .75.847a.18.18 0 0 1-.214.189l-1.444-.267a.15.15 0 0 1-.115-.203a.92.92 0 0 1 1.023-.566");
}

.l_db2rbuw {
  d: path("M19.568 11.725c.03.062-.067.113-.178.168c-.11.054-.192.092-.223.03c-.03-.062.034-.157.145-.212s.225-.048.256.014");
}

.l-fqg0bdm {
  stop-color: var(--svg-color--4087f7, #4087F7);
}

.l2tuc8b4n {
  stop-color: var(--svg-color--76414c, #76414C);
  stop-opacity: 0;
}

.lb8owybif {
  stop-color: var(--svg-color--99756c, #99756C);
  stop-opacity: 0;
}

.lc3ez7bfp {
  fill-rule: evenodd;
  d: path("M26.143 12.833a.5.5 0 0 1 .703.075c.267.332.83 1.208.571 2.568a.5.5 0 0 1-.982-.187c.186-.976-.212-1.56-.367-1.753a.5.5 0 0 1 .075-.703");
}

.lcvj76bae {
  d: path("M3.575 5.167a.04.04 0 0 0-.002.025c.03.13.288 1.023 1.177 1.688c.688.502 1.455.753 2.412.782a.05.05 0 0 0 .05-.053a4.2 4.2 0 0 0-.132-.81a.05.05 0 0 0-.046-.036a3.1 3.1 0 0 1-1.207-.353a3.2 3.2 0 0 1-1.248-1.175a.1.1 0 0 1-.02-.033l-.016-.042l-.004-.009a4 4 0 0 1-.376-.895a.049.049 0 0 0-.087-.016a4 4 0 0 0-.501.927");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll5cge3tz {
  d: path("M16.887 11.057a.583.583 0 0 0-.686.622l1.107.205a.587.587 0 0 0-.421-.827");
}

.m2ds08s7w {
  stop-color: var(--svg-color--2c89f2, #2C89F2);
  stop-opacity: 0;
}

.mly26fbqy {
  stop-color: var(--svg-color--836562, #836562);
}

.mpo0zwbic {
  d: path("M5.756 10.122a.25.25 0 0 0 .139-.004a2.6 2.6 0 0 0 .664-.526a.05.05 0 0 0-.03-.082c-1.132-.172-1.919-.52-2.445-.855c-.046-.03-.1.024-.07.068a3.73 3.73 0 0 0 1.742 1.399");
}

.mu1lsrbfz {
  stop-color: var(--svg-color--6d4c42, #6D4C42);
}

.mvrli-bgh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.568 11.725c.03.062-.067.113-.178.168c-.11.054-.192.092-.223.03c-.03-.062.034-.157.145-.212s.225-.048.256.014");
}

.n_yku1v-w {
  stop-color: var(--svg-color--907168, #907168);
  stop-opacity: 0;
}

.n2b8gu5vw {
  stop-color: var(--svg-color--5472f7, #5472F7);
}

.nil-nrb9t {
  stop-color: var(--svg-color--ffffe9, #FFFFE9);
}

.nj1er27qb {
  stop-color: var(--svg-color--2c8bf2, #2C8BF2);
  stop-opacity: 0;
}

.nmprvob2h {
  fill: var(--svg-color--6f4049, #6F4049);
  d: path("m17.787 11.944l-.535 1.014c-.11.209.014.46.248.504l.497.092a.348.348 0 0 0 .412-.382l-.138-1.138c-.028-.252-.364-.314-.484-.09");
}

.nw16d5muy {
  stop-color: var(--svg-color--55313b, #55313B);
}

.nwegx7xkg {
  stop-color: var(--svg-color--99756c, #99756C);
}

.o08d5ab1q {
  cx: 16.668px;
  cy: 11.27px;
  rx: 0.254px;
  ry: 0.129px;
}

.o4msl8bjb {
  d: path("M24.495 16.617c.287.175.57.5.675.64l.7-1.21c-.192-.113-.67-.394-1.051-.622a.58.58 0 0 0-.906.454c.003.351.222.52.582.738");
}

.o52n_hqhs {
  stop-color: var(--svg-color--412830, #412830);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oqaibvbqb {
  stop-color: var(--svg-color--f8d84f, #F8D84F);
}

.ot_s2ab4a {
  d: path("M4.524 3.727c-.014.013-.011.037-.007.056a4 4 0 0 0 .22.747a.05.05 0 0 0 .086.01a6 6 0 0 1 2.059-1.808c.031-.02.017-.07-.02-.068c-.904.08-1.719.47-2.338 1.063");
}

.oz1prabcs {
  stop-color: var(--svg-color--267dc5, #267DC5);
  stop-opacity: 0;
}

.p7cow0b7d {
  d: path("M19.636 11.61a.587.587 0 0 1 .422.833l-1.116-.206a.59.59 0 0 1 .694-.627");
}

.p8d_bws2x {
  d: path("M7.618 10.378c.031-.004.052-.044.075-.066c.42-.4.922-1.1 1.017-2.252c.08-.989-.289-1.816-.504-2.206a.048.048 0 0 0-.074-.013c-.324.27-.535.568-.631.716a.05.05 0 0 0-.006.042c.076.246.22.846.16 1.524a3.2 3.2 0 0 1-.418 1.322l-.003.008l-.014.024l-.007.01a2.8 2.8 0 0 1-.695.766c-.034.027-.022.082.021.09a4 4 0 0 0 1.079.035");
}

.pdlduxt0m {
  stop-color: var(--svg-color--ffd739, #FFD739);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkvze_bui {
  stop-color: var(--svg-color--72433f, #72433F);
  stop-opacity: 0;
}

.pswnefbva {
  stop-color: var(--svg-color--6c4249, #6C4249);
}

.pt3kuccrj {
  stop-color: var(--svg-color--83625e, #83625E);
}

.pv-xo4bei {
  stop-color: var(--svg-color--fff665, #FFF665);
}

.pve28abei {
  stop-color: var(--svg-color--794d49, #794D49);
}

.pwyc_ob2i {
  stop-color: var(--svg-color--fff662, #FFF662);
}

.q_druvruw {
  stop-color: var(--svg-color--3fb2ff, #3FB2FF);
  stop-opacity: 0;
}

.q3hk4_bla {
  stop-color: var(--svg-color--d9d1be, #D9D1BE);
}

.qk9w2-gwc {
  fill: var(--svg-color--000, #000);
  d: path("M19.198 12.127a.335.335 0 0 1 .392-.27a.335.335 0 0 1 .205.538l-.585-.109a.3.3 0 0 1-.012-.16");
}

.qoalrcbnl {
  d: path("M7.128 6.281c.223-.34.845-1.163 1.906-1.439a3.2 3.2 0 0 1 1.57-.001c.042.01.078-.032.058-.07a3.9 3.9 0 0 0-.674-.943c-.018-.02-.054-.014-.08-.014a4.3 4.3 0 0 0-1.793.38c-1.136.503-1.76 1.374-2.01 1.783a.05.05 0 0 0 .02.07c.4.19.76.243.958.256a.05.05 0 0 0 .045-.022");
}

.qsi2djbas {
  stop-color: var(--svg-color--eaae49, #EAAE49);
}

.quq9pabmg {
  fill: var(--svg-color--000, #000);
  d: path("M17.11 11.69a.33.33 0 0 0-.268-.388a.332.332 0 0 0-.38.425l.58.108a.33.33 0 0 0 .067-.144");
}

.qvl3f1svv {
  stop-color: var(--svg-color--46a4f6, #46A4F6);
}

.r_t0zy9vt {
  fill: var(--svg-color--87014e, #87014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.937 13.593c.22.178.501.311.815.374c.318.064.624.048.897-.031a.15.15 0 0 1 .168.063a.14.14 0 0 1-.02.178m-1.86-.584l1.825.549m-1.825-.55a.15.15 0 0 0-.18-.004a.14.14 0 0 0-.05.17m.23-.165l-.184.146m2.045.438l-.036-.035m.036.035l-.036-.035m.036.035a1.27 1.27 0 0 1-1.158.35a1.27 1.27 0 0 1-.933-.769m2.055.384c-.277.28-.69.42-1.112.335a1.23 1.23 0 0 1-.897-.738m-.046.02l.046-.02m-.046.02v-.001l.046-.019");
}

.rglr48bfo {
  stop-color: var(--svg-color--7c564f, #7C564F);
}

.rlocznbrk {
  stop-color: var(--svg-color--e59a2b, #E59A2B);
}

.rmpzr1bpn {
  stop-color: var(--svg-color--41aaff, #41AAFF);
}

.rwcn2nbsr {
  stop-color: var(--svg-color--d9944a, #D9944A);
}

.rzd60jbst {
  stop-color: var(--svg-color--3569a0, #3569A0);
}

.sa851lbem {
  stop-color: var(--svg-color--765145, #765145);
}

.skulo7b5p {
  fill: var(--svg-color--1d0e22, #1D0E22);
  fill-rule: evenodd;
  d: path("M17.425 10.339c-.468-.106-.809-.012-.94.045a.3.3 0 0 1-.239-.55c.237-.103.708-.217 1.311-.08a.3.3 0 0 1-.133.585");
}

.srsgrxbbq {
  stop-color: var(--svg-color--40b6ff, #40B6FF);
  stop-opacity: 0;
}

.sy7-q781r {
  fill-rule: evenodd;
  d: path("M24.612 13.257a.5.5 0 0 1 .696.125l.04.056c.214.294.92 1.264.797 2.574a.5.5 0 1 1-.996-.095c.087-.915-.402-1.598-.617-1.9l-.046-.064a.5.5 0 0 1 .126-.696");
}

.t1ffwv_yc {
  stop-color: var(--svg-color--e0b93f, #E0B93F);
}

.t77dcut_r {
  stop-color: var(--svg-color--51c9ff, #51C9FF);
}

.tcrz9obtu {
  stroke: var(--svg-color--302f30, #302F30);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M20.749 10.894c-.157-.176-.418-.473-1.008-.493");
}

.tdiqapb8p {
  stop-color: var(--svg-color--795348, #795348);
}

.tqz-m9b5q {
  d: path("M9.344 3.291c.038.026.023.085-.022.091a5 5 0 0 0-1.395.395a4.9 4.9 0 0 0-2.218 1.948a.05.05 0 0 1-.073.014a2.7 2.7 0 0 1-.596-.64a.05.05 0 0 1-.001-.054A5.5 5.5 0 0 1 7.09 3.14a4 4 0 0 1 .95-.343c.36-.085.937.247 1.303.495");
}

.u44kqtbwx {
  stop-color: var(--svg-color--856a63, #856A63);
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

.ur9uw6b9b {
  fill: var(--svg-color--2a71bb, #2A71BB);
  fill-rule: evenodd;
  d: path("m14.352 13.572l.305-3.094l.597.059l-.305 3.094a1.9 1.9 0 0 0 1.518 2.05l1.812.363a1.9 1.9 0 0 0 2.197-1.33l1.082-3.697l.576.169l-1.082 3.697a2.5 2.5 0 0 1-2.89 1.749l-1.813-.363a2.5 2.5 0 0 1-1.997-2.697");
}

.v81yadizx {
  stop-color: var(--svg-color--89655f, #89655F);
  stop-opacity: 0;
}

.vi9q-fb9u {
  stop-color: var(--svg-color--ffcd36, #FFCD36);
}

.vr46bbbzw {
  d: path("M7.096 12.168c.163-1.363.943-1.735 1.313-1.75c-.488.4-.652 1.562-.672 2.094l.171 3.233l-.812.64c.042-.864-.162-2.855 0-4.217");
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

.wb6ooab1e {
  stop-color: var(--svg-color--673b44, #673B44);
}

.wda4yc_iv {
  stop-color: var(--svg-color--3f83e6, #3F83E6);
}

.wws-k6_xt {
  d: path("M20.056 12.205a.55.55 0 0 0-.094-.325l-.2.152l.047.16z");
}

.x114bxlro {
  stop-color: var(--svg-color--f9cd54, #F9CD54);
}

.x55o2eq8z {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.786 10.858a.91.91 0 0 0-.996.52a.18.18 0 0 0 .132.25l1.433.265a.15.15 0 0 0 .178-.148a.915.915 0 0 0-.747-.887");
}

.x9d7jz1fb {
  stop-color: var(--svg-color--d9afcd, #D9AFCD);
}

.xf6fc56wi {
  stop-color: var(--svg-color--3072a5, #3072A5);
}

.xhmvd3bcy {
  d: path("m13.065 16.367l-2.14 7.86l4.609 2.171l4.422-1.953c.583-2.38 1.756-7.16 1.78-7.234c.032-.094.22-.844-.64-.97c-2.61-.358-6.328-.655-7.062-.687c-.588-.025-.89.532-.97.813");
}

.xp6kfq0_i {
  d: path("M15.335 10.066c.148-1.181.828-1.271 1.277-1.23c1.074.097 2.836.48 3.898.789c1.045.303.992.847.992 1.152s-.18 1.035-.328 1.832c-.118.638.081.85.196.875c.117.02.4-.081.593-.656c.336-1.242 1.07-3.672.399-5.016c-.672-1.344-1.719-1.789-2.938-2.023c-1.218-.235-2.617-.25-3.656.656c-1.227.953-1.336 3.406-1.344 4.313s.086 1.343.407 1.242c.32-.102.324-.504.504-1.934");
}

.xq_1inbmx {
  stop-color: var(--svg-color--604339, #604339);
  stop-opacity: 0;
}

.xtrjnaccv {
  stop-color: var(--svg-color--ffd739, #FFD739);
  stop-opacity: 0;
}

.y48pl-2sa {
  d: path("M14.963 16.015c.078-.437.324-.41.363-.418l4.348.38c.17-.016.503.091.484.648c-.117 1.328-1.25 2.617-3.035 2.328c-1.839-.277-2.32-1.895-2.16-2.938");
}

.z5cog-bec {
  d: path("M17.316 11.658c.034-.185-.093-.335-.127-.38l-.217.144l.07.252z");
}

.z8efi882d {
  stop-color: var(--svg-color--89655f, #89655F);
}

.zbaxvmghd {
  d: path("M9.034 4.842c-1.06.276-1.683 1.099-1.907 1.44a.05.05 0 0 1-.044.021a2.7 2.7 0 0 1-.957-.256a.05.05 0 0 1-.02-.07c.25-.41.873-1.28 2.009-1.782a4.3 4.3 0 0 1 1.792-.381c.046 0 .07-.055.037-.087a4 4 0 0 0-.414-.357a.05.05 0 0 0-.034-.01a5.1 5.1 0 0 0-1.57.417A4.9 4.9 0 0 0 5.71 5.725a.05.05 0 0 1-.073.014a2.7 2.7 0 0 1-.596-.64a.05.05 0 0 1-.001-.053a5.5 5.5 0 0 1 2.05-1.907c.318-.167.664-.274.95-.342c.05-.013.052-.084.001-.095a3.8 3.8 0 0 0-.836-.095h-.061l-.023.005c-.08.039-.16.07-.24.12a6 6 0 0 0-2.06 1.807a.05.05 0 0 1-.085-.009a4 4 0 0 1-.22-.747a.05.05 0 0 0-.083-.027c-.105.105-.203.22-.295.336a.05.05 0 0 0-.01.043a4.2 4.2 0 0 0 .414 1.026a.2.2 0 0 0 .044.083a3.2 3.2 0 0 0 1.24 1.166c.488.259.949.337 1.207.353a.05.05 0 0 1 .046.036c.049.175.11.47.133.81a.05.05 0 0 1-.05.053c-.958-.029-1.725-.28-2.412-.782c-.95-.71-1.18-1.682-1.18-1.703c0-.026-.036-.025-.045 0c-.079.215-.134.44-.181.672a.05.05 0 0 0 .004.033c.2.395.543.92 1.131 1.353c.948.704 1.927.86 2.663.886a.05.05 0 0 1 .048.055a2.7 2.7 0 0 1-.261.888a.05.05 0 0 1-.05.027c-2.543-.3-3.33-1.522-3.34-1.543a.2.2 0 0 0-.075-.077c-.031-.019-.061.012-.052.047c.092.334.22.641.383.93l.013.016c.512.387 1.371.841 2.721 1.046a.05.05 0 0 1 .03.082a2.6 2.6 0 0 1-.664.526c-.038.021-.035.078.006.092q.225.082.469.134q.02.004.039-.008q.53-.387.804-.85l.007-.01l.014-.023q.004-.013.01-.025a3.2 3.2 0 0 0 .411-1.305a4.2 4.2 0 0 0-.16-1.524a.05.05 0 0 1 .006-.042c.096-.148.307-.446.631-.716a.048.048 0 0 1 .074.013c.215.39.584 1.217.504 2.206c-.095 1.151-.597 1.852-1.017 2.252c-.036.034-.008.096.04.088q.32-.045.617-.13a.05.05 0 0 0 .025-.018c.373-.48.723-1.176.806-2.16c.09-1.151-.345-2.087-.592-2.517a.05.05 0 0 1 .019-.068a2.4 2.4 0 0 1 .863-.275c.02-.002.04.008.048.026c.257.511.997 2.215.41 3.93c-.018.05.044.091.08.053a4 4 0 0 0 .545-.702l.007-.019c.197-1.369-.236-2.602-.51-3.225a.05.05 0 0 1 .05-.07a2.5 2.5 0 0 1 .77.202c.04.019.085-.02.071-.061a5 5 0 0 0-.175-.461a.05.05 0 0 0-.03-.027a3.2 3.2 0 0 0-1.703-.036");
}

.zepb-5s8y {
  stop-color: var(--svg-color--9d7c72, #9D7C72);
}

.znpsn40vf {
  stroke: var(--svg-color--302f30, #302F30);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.366 10.05c.183-.08.59-.184 1.125-.063");
}

.zvs-cxsdn {
  fill-rule: evenodd;
  d: path("M3.975 8.271a.5.5 0 0 1 .639.302c.08.225.493.986 1.711 1.372a.5.5 0 1 1-.302.953C4.48 10.41 3.847 9.4 3.673 8.91a.5.5 0 0 1 .302-.639");
}

</style>
