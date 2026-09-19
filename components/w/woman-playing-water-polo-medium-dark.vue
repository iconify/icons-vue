<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iAm0anb)" class="v3vfkabey"/><path fill="url(#ipJe8Bb)" class="npzdus8rc"/><g filter="url(#iN7JAfc)"><path fill="url(#i2314BO)" class="vuc-e-qgu"/></g><path fill="url(#iMU0Brd)" class="eavzsrtdt"/><g filter="url(#iCMjZPb)"><path class="nx5i0kb9s"/><path fill="url(#ijSD02j)" class="hjpjmzbhg"/></g><path fill="url(#in1fcIc)" clip-rule="evenodd" class="u2vsikbqs"/><path fill="url(#iRSWcpc)" clip-rule="evenodd" class="mc69qbcuz"/><path fill="url(#iPV5Yoe)" clip-rule="evenodd" class="qq8mdzsuu"/><path fill="url(#iAiZgre)" clip-rule="evenodd" class="h97wn5p7r"/><path fill="url(#iWPAHKb)" clip-rule="evenodd" class="h97wn5p7r"/><path fill="url(#i8sVhLe)" clip-rule="evenodd" class="g1pman8wa"/><path fill="url(#iU04wXb)" class="ed41k8brv"/><g filter="url(#iIsfVbb)"><path clip-rule="evenodd" class="p3zpjlb6d"/><path fill="url(#iHBF1Je)" clip-rule="evenodd" class="oxae2u2rt"/><path fill="url(#iUXIsYb)" clip-rule="evenodd" class="oxae2u2rt"/></g><g filter="url(#ihc7Fmb)"><path fill="url(#izlwVkj)" class="mko_diovh"/></g><path fill="url(#iitbohe)" class="nxxr3abyt"/><path fill="url(#iC4i3be)" class="te623bspc"/><path fill="url(#ikRoW9b)" class="te623bspc"/><path fill="url(#iLDnEib)" class="e76p4vkrs"/><path fill="url(#iEgSPqc)" class="xdiwrunqp"/><path fill="url(#iJQcp3e)" class="xdiwrunqp"/><path fill="url(#iCwH9bB)" class="wao9xvbcz"/><path fill="url(#iXquTzb)" class="wao9xvbcz"/><path fill="url(#ipFIozb)" class="wao9xvbcz"/><g filter="url(#irMdqhe)"><path fill="url(#ibikxIb)" class="mn-wyqbqw"/></g><g filter="url(#iQcnibb)"><path fill="url(#iuO00Wb)" class="zfso0abuk"/></g><path fill="url(#itUYLsS)" class="a268dfber"/><path fill="url(#iPa2R1c)" class="a268dfber"/><path fill="url(#izPPrPc)" class="sb91vbc8w"/><path fill="url(#irqbO7d)" class="sb91vbc8w"/><path fill="url(#igSa0ic)" class="hxow8bcae"/><path fill="url(#iBnexte)" class="hxow8bcae"/><path fill="url(#iEkpLqe)" class="h4st6nerq"/><path fill="url(#ijOtMDd)" class="h4st6nerq"/><path fill="url(#inHKbfe)" class="h4st6nerq"/><path fill="url(#idT7u6d)" class="h4st6nerq"/><path fill="url(#ilPPkOc)" class="h4st6nerq"/><path fill="url(#iDoy6dQ)" class="h4st6nerq"/><path fill="url(#iEkpLqe)" class="h4st6nerq"/><path fill="url(#ijOtMDd)" class="h4st6nerq"/><path fill="url(#inHKbfe)" class="h4st6nerq"/><path fill="url(#idT7u6d)" class="h4st6nerq"/><path fill="url(#ilPPkOc)" class="h4st6nerq"/><path fill="url(#iDoy6dQ)" class="h4st6nerq"/><path fill="url(#iWbcF4d)" class="qqvhld2kx"/><path fill="url(#iwtT9eO)" class="qqvhld2kx"/><path fill="url(#ih5IbAd)" class="qqvhld2kx"/><g filter="url(#io6A2De)"><path fill="url(#iyInytb)" class="mfaqlgbhq"/></g><g filter="url(#iJNCdZd)"><path fill="url(#iYRyQhc)" class="rt0q9-bwa"/></g><g filter="url(#i3xRGje)"><path fill="url(#iqNKv9d)" class="b_au_d83j"/><path fill="url(#iKIS4Yd)" class="b_au_d83j"/><path fill="url(#i7bkuie)" class="b_au_d83j"/><path fill="url(#i8EaC0k)" class="b_au_d83j"/></g><g filter="url(#ihYt3RE)"><path clip-rule="evenodd" class="jmde6ezpz"/></g><g filter="url(#imAzrbc)"><path clip-rule="evenodd" class="rbdca_23i"/></g><g filter="url(#iXSdfge)"><path class="ubqrvr0_n"/></g><g filter="url(#iQGsEkb)"><path fill="url(#ibu51Ke)" class="fdr21fpoo"/><path fill="url(#iPZDbIb)" class="fdr21fpoo"/></g><path stroke="url(#idTG76c)" class="xerb7tdfi"/><g filter="url(#iRQl23d)"><path class="ih0g4nbfz"/></g><g filter="url(#iHN1eeb)"><path class="w6k2ut5zu"/></g><path class="wwjt5lyhp"/><path fill="url(#ivKb5me)" class="jesbzuboj"/><path class="addndubun"/><g filter="url(#iUBhbdc)"><path class="ypqigjezu"/><path fill="url(#iAQuDvb)" class="vb1011phq"/></g><g filter="url(#iRtYTNd)"><path fill="url(#ihrDOle)" class="xsaxc8btc"/></g><path class="p_apwyb8c"/><path fill="url(#ia0SP3d)" class="j13l2ir_z"/><path class="m4rwtdbrs"/><g filter="url(#i9wHd0c)"><path fill="url(#iDB0xek)" class="epp7qxb0e"/></g><g filter="url(#iuUwsub)"><ellipse transform="rotate(-17.442 16.52 11.27)" class="x7sdhebzt"/><ellipse fill="url(#ideNBjd)" transform="rotate(-17.442 16.52 11.27)" class="jw23vabrn"/></g><g filter="url(#iTJMMfQ)"><path class="ge48w0b5j"/></g><g filter="url(#iLDFgUd)"><path class="hxha0gmrz"/></g><g filter="url(#iQpRJFd)"><path clip-rule="evenodd" class="ekn6pnbcj"/></g><g filter="url(#iu9tOee)"><path class="mvtd0pbef"/></g><path fill="url(#iGD0DKc)" class="uua34abnm"/><path fill="url(#i5rrBPd)" class="uua34abnm"/><path fill="url(#ijPxLkd)" class="uua34abnm"/><path fill="url(#i3kTRpb)" class="uua34abnm"/><defs><radialGradient id="iAm0anb" cx="0" cy="0" r="1" gradientTransform="matrix(.60816 5.60938 -4.2048 .45587 14.94 10.262)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="jd2_gubse"/><stop offset="1" class="hvr6robrc"/></radialGradient><radialGradient id="ipJe8Bb" cx="0" cy="0" r="1" gradientTransform="rotate(124.509 8.069 12.271)scale(4.74983 4.09958)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="fe1ixid0a"/><stop offset="1" class="e-ywdabyy"/></radialGradient><radialGradient id="ijSD02j" cx="0" cy="0" r="1" gradientTransform="rotate(-171.733 7.678 7.408)scale(3.69464 3.85482)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="j8h3dgbhd"/><stop offset="1" class="xq_1inbmx"/></radialGradient><radialGradient id="in1fcIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.55594 1.94881 -1.48215 -.42282 25.008 13.212)" gradientUnits="userSpaceOnUse"><stop class="u44kqtbwx"/><stop offset=".384" class="dmrsrxbbr"/></radialGradient><radialGradient id="iPV5Yoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.51606 1.90495 -1.38608 -.3755 25.64 12.765)" gradientUnits="userSpaceOnUse"><stop class="u44kqtbwx"/><stop offset=".384" class="dmrsrxbbr"/></radialGradient><radialGradient id="iAiZgre" cx="0" cy="0" r="1" gradientTransform="rotate(113.89 9.167 15.162)scale(1.87125 1.68165)" gradientUnits="userSpaceOnUse"><stop class="dbphouvft"/><stop offset=".467" class="o52n_hqhs"/></radialGradient><radialGradient id="iWPAHKb" cx="0" cy="0" r="1" gradientTransform="rotate(113.89 9.167 15.162)scale(1.87125 1.68165)" gradientUnits="userSpaceOnUse"><stop class="c3i1aoblk"/><stop offset=".467" class="pve28abei"/></radialGradient><radialGradient id="i8sVhLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.67866 1.61156 -1.399 -.58915 27.413 13.715)" gradientUnits="userSpaceOnUse"><stop class="c3i1aoblk"/><stop offset=".467" class="kv0towb6e"/></radialGradient><radialGradient id="iU04wXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.424 .6523 -1.8923 -1.23 25.052 16.127)" gradientUnits="userSpaceOnUse"><stop class="pt3kuccrj"/><stop offset=".438" class="irk_qbcrg"/></radialGradient><radialGradient id="iHBF1Je" cx="0" cy="0" r="1" gradientTransform="matrix(1.467 -1.9886 6.33088 4.67033 21.082 20.776)" gradientUnits="userSpaceOnUse"><stop class="bgex3sn2v"/><stop offset="1" class="klh3qabex"/></radialGradient><radialGradient id="iUXIsYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.83537 -1.45884 0 25.417 16.277)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="je851xbvd"/><stop offset="1" class="pkvze_bui"/></radialGradient><radialGradient id="iitbohe" cx="0" cy="0" r="1" gradientTransform="matrix(-.90626 2.21874 -3.49772 -1.42868 4.883 4.898)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t1ffwv_yc"/><stop offset="1" class="he60mdbwm"/></radialGradient><radialGradient id="iC4i3be" cx="0" cy="0" r="1" gradientTransform="matrix(-.96014 1.99895 -3.51333 -1.68753 4.73 6.601)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="c6s8j5o0k"/><stop offset="1" class="upn6hw37x"/></radialGradient><radialGradient id="ikRoW9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.51562 1.39063 -3.21171 -1.19085 5.508 7.351)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="w4-c1u12h"/><stop offset="1" class="db6hxbc6j"/></radialGradient><radialGradient id="iLDnEib" cx="0" cy="0" r="1" gradientTransform="matrix(.41141 1.3754 -2.82798 .8459 3.732 8.519)" gradientUnits="userSpaceOnUse"><stop offset=".05" class="w3225dbjw"/><stop offset="1" class="rwcn2nbsr"/></radialGradient><radialGradient id="iEgSPqc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1467 4.65626 -2.92783 -.72104 8.57 5.992)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="idibcljtc"/><stop offset="1" class="rlocznbrk"/></radialGradient><radialGradient id="iCwH9bB" cx="0" cy="0" r="1" gradientTransform="rotate(84.147 1.817 7.839)scale(3.98377 3.9383)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="kkkpn9_8c"/><stop offset="1" class="qsi2djbas"/></radialGradient><radialGradient id="iXquTzb" cx="0" cy="0" r="1" gradientTransform="matrix(.55769 3.79546 -10.478 1.5396 8.57 6.414)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="jbim1r-8q"/><stop offset=".887" class="jx__8ve1w"/></radialGradient><radialGradient id="ipFIozb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10157 -3.50206 7.04927 -2.21735 9.922 8.734)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="w1-vbdbpq"/><stop offset="1" class="vi9q-fb9u"/></radialGradient><radialGradient id="ibikxIb" cx="0" cy="0" r="1" gradientTransform="matrix(.95313 1.7322 -1.31372 .72286 9.977 5.402)" gradientUnits="userSpaceOnUse"><stop class="pwyc_ob2i"/><stop offset="1" class="x114bxlro"/></radialGradient><radialGradient id="iuO00Wb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.141 6.506 -1.05)scale(1.5807 2.46179)" gradientUnits="userSpaceOnUse"><stop class="jh6rb_-if"/><stop offset="1" class="btbmkccji"/></radialGradient><radialGradient id="itUYLsS" cx="0" cy="0" r="1" gradientTransform="rotate(-100.73 5.673 -1.103)scale(1.84923 2.37953)" gradientUnits="userSpaceOnUse"><stop class="jh6rb_-if"/><stop offset="1" class="btbmkccji"/></radialGradient><radialGradient id="iPa2R1c" cx="0" cy="0" r="1" gradientTransform="rotate(151.204 3.344 3.419)scale(2.69231 1.10958)" gradientUnits="userSpaceOnUse"><stop offset=".874" class="pv-xo4bei"/><stop offset="1" class="w86h2iq4q"/></radialGradient><radialGradient id="izPPrPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9922 -.60156 1.5104 -2.49122 5.656 3.734)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="hgt5uebfs"/><stop offset="1" class="vvex-7byg"/></radialGradient><radialGradient id="irqbO7d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55468 1.19532 -.2462 -.32022 6.312 3.266)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="oqaibvbqb"/><stop offset="1" class="jj-ghzbrk"/></radialGradient><radialGradient id="igSa0ic" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -6.9375 10.4709 -.04717 6.414 10.836)" gradientUnits="userSpaceOnUse"><stop class="x9d7jz1fb"/><stop offset="1" class="nil-nrb9t"/></radialGradient><radialGradient id="iBnexte" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 -2.87499 4.0482 -7.17238 8.695 7.367)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="aljt7ncuz"/><stop offset="1" class="q3hk4_bla"/></radialGradient><radialGradient id="iEkpLqe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.68754 8.59373 -8.59905 -3.68982 19.164 18.242)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="ajceiybox"/><stop offset="1" class="kyri3g7rc"/></radialGradient><radialGradient id="inHKbfe" cx="0" cy="0" r="1" gradientTransform="rotate(99.197 .904 13.857)scale(3.32398 6.99637)" gradientUnits="userSpaceOnUse"><stop class="cgvg0acnd"/><stop offset="1" class="t_ucbwbbk"/></radialGradient><radialGradient id="idT7u6d" cx="0" cy="0" r="1" gradientTransform="matrix(2.70313 .32813 -.1097 .90377 19.766 16.48)" gradientUnits="userSpaceOnUse"><stop class="y0tde_bcy"/><stop offset="1" class="v679tzbuc"/></radialGradient><radialGradient id="ilPPkOc" cx="0" cy="0" r="1" gradientTransform="matrix(.30078 2.59375 -2.78882 .3234 17.508 16.69)" gradientUnits="userSpaceOnUse"><stop offset=".906" class="zdfpz2b9v"/><stop offset="1" class="yy8y3t7sm"/></radialGradient><radialGradient id="iDoy6dQ" cx="0" cy="0" r="1" gradientTransform="matrix(.29688 2.5625 -2.75522 .3192 17.508 16.69)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="nvypefbww"/><stop offset=".954" class="bblzlobak"/></radialGradient><radialGradient id="iWbcF4d" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 4 -6.15337 4.1343 15.852 15.398)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="jx45yjlfo"/><stop offset=".876" class="e3_7pgb3y"/></radialGradient><radialGradient id="iwtT9eO" cx="0" cy="0" r="1" gradientTransform="rotate(168.536 8.245 8.62)scale(4.55972 1.90182)" gradientUnits="userSpaceOnUse"><stop offset=".514" class="nw16d5muy"/><stop offset="1" class="d7y73d45o"/></radialGradient><radialGradient id="ih5IbAd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.54687 .625 -.24279 -.6009 20.1 16.199)" gradientUnits="userSpaceOnUse"><stop class="emput3bhq"/><stop offset="1" class="n_yku1v-w"/></radialGradient><radialGradient id="iqNKv9d" cx="0" cy="0" r="1" gradientTransform="rotate(153.547 8.528 8.197)scale(5.06763 4.24341)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="iqirvccxe"/><stop offset="1" class="bqfwc3bya"/></radialGradient><radialGradient id="iKIS4Yd" cx="0" cy="0" r="1" gradientTransform="matrix(.1875 -.9375 1.1772 .23544 16.563 11.094)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="n967l8b-u"/><stop offset="1" class="ia_bp8w6o"/></radialGradient><radialGradient id="i7bkuie" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 -.9235 1.15909 .43144 19.781 11.736)" gradientUnits="userSpaceOnUse"><stop class="rrljybbjf"/><stop offset="1" class="tfkxk5q_t"/></radialGradient><radialGradient id="i8EaC0k" cx="0" cy="0" r="1" gradientTransform="rotate(133.112 7.961 8.91)scale(2.01193 1.78921)" gradientUnits="userSpaceOnUse"><stop class="t1a7crb1v"/><stop offset="1" class="po79w8bfx"/></radialGradient><radialGradient id="ibu51Ke" cx="0" cy="0" r="1" gradientTransform="rotate(178.156 9.09 6.527)scale(1.07184 3.25765)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="zepb-5s8y"/><stop offset=".491" class="rglr48bfo"/></radialGradient><radialGradient id="iPZDbIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.32092 1.22102 -1.83089 -.48121 18.103 12.148)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="l2tuc8b4n"/><stop offset=".983" class="j_zhj-bkx"/></radialGradient><radialGradient id="idTG76c" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 -.32813 1.229 1.17048 16.751 14.191)" gradientUnits="userSpaceOnUse"><stop class="mly26fbqy"/><stop offset="1" class="gdi6d5gtd"/></radialGradient><radialGradient id="ivKb5me" cx="0" cy="0" r="1" gradientTransform="matrix(-.2953 .56697 -.67087 -.34941 19.522 11.816)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="tdiqapb8p"/><stop offset="1" class="mu1lsrbfz"/></radialGradient><radialGradient id="iAQuDvb" cx="0" cy="0" r="1" gradientTransform="rotate(-117.34 13.27 .108)scale(.24737 .34057)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ia0SP3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.29297 .5625 -.66558 -.34666 16.775 11.262)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="tdiqapb8p"/><stop offset="1" class="mu1lsrbfz"/></radialGradient><radialGradient id="ideNBjd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.904 -2.389)scale(.32222 .38731)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGD0DKc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.78124 5.34377 -6.51613 -5.83019 20.791 6.618)" gradientUnits="userSpaceOnUse"><stop class="iz96j8ojk"/><stop offset="1" class="i2-vql0bm"/></radialGradient><radialGradient id="i5rrBPd" cx="0" cy="0" r="1" gradientTransform="matrix(.30077 -1.59375 3.79886 .7169 18.381 9.71)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="n2b8gu5vw"/><stop offset="1" class="nj1er27qb"/></radialGradient><radialGradient id="ijPxLkd" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 1.59375 -3.9358 4.01296 15.229 6.399)" gradientUnits="userSpaceOnUse"><stop class="gmg8hcbdj"/><stop offset="1" class="m2ds08s7w"/></radialGradient><radialGradient id="i3kTRpb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40626 -2.65624 1.89737 -1.7188 21.76 7.836)" gradientUnits="userSpaceOnUse"><stop class="ht2yfkjwb"/><stop offset="1" class="q_druvruw"/></radialGradient><filter id="iN7JAfc" width="28.306" height="11.645" x="2.123" y="18.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.572549 0 0 0 0 0.819608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.619608 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23704" result="effect2_innerShadow_3987_23704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.886275 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_23704" result="effect3_innerShadow_3987_23704"/></filter><filter id="iCMjZPb" width="8.631" height="9.819" x="5.295" y="8.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.243137 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/></filter><filter id="iIsfVbb" width="9.358" height="9.592" x="19.091" y="14.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.223529 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/></filter><filter id="ihc7Fmb" width="5.441" height="5.972" x="20.435" y="16.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".2"/></filter><filter id="irMdqhe" width="1.134" height="3.026" x="9.895" y="5.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/></filter><filter id="iQcnibb" width="4.669" height="2.54" x="5.947" y="3.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.768627 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/></filter><filter id="io6A2De" width="28.306" height="6.762" x="2.123" y="23.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.368627 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.458824 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23704" result="effect2_innerShadow_3987_23704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.619608 0 0 0 0 0.988235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_23704" result="effect3_innerShadow_3987_23704"/></filter><filter id="iJNCdZd" width="2.176" height="6.768" x="6.481" y="10.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".2"/></filter><filter id="i3xRGje" width="7.659" height="8.744" x="14.521" y="7.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.188235 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/></filter><filter id="ihYt3RE" width="1.456" height=".646" x="15.916" y="9.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0156863 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/></filter><filter id="imAzrbc" width="1.358" height="1.007" x="19.311" y="10.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0156863 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/></filter><filter id="iXSdfge" width="2.2" height="2.754" x="16.563" y="11.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".25"/></filter><filter id="iQGsEkb" width="1.4" height="1.954" x="17.145" y="11.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".05"/></filter><filter id="iRQl23d" width="1.76" height=".627" x="15.544" y="10.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.129412 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/></filter><filter id="iHN1eeb" width="1.749" height=".829" x="18.98" y="11.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.129412 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/></filter><filter id="iUBhbdc" width=".514" height=".381" x="18.961" y="11.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".025"/></filter><filter id="iRtYTNd" width=".395" height=".425" x="19.563" y="11.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".025"/></filter><filter id="i9wHd0c" width=".45" height=".496" x="16.773" y="11.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".025"/></filter><filter id="iuUwsub" width=".591" height=".389" x="16.224" y="11.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".025"/></filter><filter id="iTJMMfQ" width="1.409" height=".403" x="15.942" y="9.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".05"/></filter><filter id="iLDFgUd" width="1.343" height=".722" x="19.317" y="10.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".05"/></filter><filter id="iQpRJFd" width="7.779" height="5.716" x="14.246" y="10.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.482353 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23704"/></filter><filter id="iu9tOee" width="7.733" height="5.823" x="14.221" y="10.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23704" stdDeviation=".1"/></filter><linearGradient id="i2314BO" x1="30.18" x2="7.028" y1="21.961" y2="31.381" gradientUnits="userSpaceOnUse"><stop class="t77dcut_r"/><stop offset=".78" class="qvl3f1svv"/></linearGradient><linearGradient id="iMU0Brd" x1="8.461" x2="9.695" y1="11.008" y2="9.351" gradientUnits="userSpaceOnUse"><stop offset=".174" class="f35kr1b2b"/><stop offset="1" class="g47ni5_fz"/></linearGradient><linearGradient id="iRSWcpc" x1="5.008" x2="6.523" y1="10.117" y2="10.758" gradientUnits="userSpaceOnUse"><stop class="wb6ooab1e"/><stop offset=".917" class="sa851lbem"/></linearGradient><linearGradient id="izlwVkj" x1="24.944" x2="18.179" y1="21.261" y2="14.823" gradientUnits="userSpaceOnUse"><stop offset=".298" class="nwegx7xkg"/><stop offset="1" class="lb8owybif"/></linearGradient><linearGradient id="iJQcp3e" x1="7.563" x2="7.773" y1="6.156" y2="6.32" gradientUnits="userSpaceOnUse"><stop offset=".139" class="pdlduxt0m"/><stop offset="1" class="xtrjnaccv"/></linearGradient><linearGradient id="ijOtMDd" x1="11.477" x2="14.195" y1="21.273" y2="21.961" gradientUnits="userSpaceOnUse"><stop class="ge6p9hb8t"/><stop offset="1" class="o2b36j3xt"/></linearGradient><linearGradient id="iyInytb" x1="20.32" x2="1.633" y1="29.211" y2="21.586" gradientUnits="userSpaceOnUse"><stop class="l-fqg0bdm"/><stop offset="1" class="wda4yc_iv"/></linearGradient><linearGradient id="iYRyQhc" x1="7.835" x2="7.694" y1="10.698" y2="19.136" gradientUnits="userSpaceOnUse"><stop class="z8efi882d"/><stop offset="1" class="v81yadizx"/></linearGradient><linearGradient id="ihrDOle" x1="19.924" x2="19.699" y1="12.046" y2="12.133" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDB0xek" x1="17.153" x2="16.93" y1="11.486" y2="11.573" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-playing-water-polo-medium-dark" /></template>
<style>
.a268dfber {
  d: path("M9.193 3.291c.038.026.023.085-.022.091a5 5 0 0 0-1.395.395a4.9 4.9 0 0 0-2.218 1.948a.05.05 0 0 1-.073.014a2.7 2.7 0 0 1-.596-.64a.05.05 0 0 1-.001-.054A5.5 5.5 0 0 1 6.94 3.14a4 4 0 0 1 .95-.343c.361-.085.938.247 1.303.495");
}

.addndubun {
  fill: var(--svg-color--000, #000);
  d: path("M19.05 12.128a.335.335 0 0 1 .392-.27a.335.335 0 0 1 .204.537l-.585-.108a.3.3 0 0 1-.011-.16");
}

.ajceiybox {
  stop-color: var(--svg-color--856ad3, #856AD3);
}

.aljt7ncuz {
  stop-color: var(--svg-color--d9d1be, #D9D1BE);
  stop-opacity: 0;
}

.b_au_d83j {
  d: path("m14.532 12.59l.187-1.946c.449-2.856 1.355-3.257 1.752-3.101c1 0 3.331.15 4.656.75s.905 2.338.53 3.133c-.131.578-.418 2.142-.696 2.789c-.337.78-1.723 2.22-4.015 1.586c-2.132-.59-2.5-2.313-2.414-3.211");
}

.bblzlobak {
  stop-color: var(--svg-color--7856c9, #7856C9);
  stop-opacity: 0;
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

.cgvg0acnd {
  stop-color: var(--svg-color--654986, #654986);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
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

.e-ywdabyy {
  stop-color: var(--svg-color--181320, #181320);
}

.e3_7pgb3y {
  stop-color: var(--svg-color--755050, #755050);
}

.e76p4vkrs {
  d: path("M5.605 10.122a.25.25 0 0 0 .14-.004a2.6 2.6 0 0 0 .663-.526a.05.05 0 0 0-.03-.082c-1.132-.172-1.919-.52-2.445-.855c-.046-.03-.1.024-.07.068a3.73 3.73 0 0 0 1.742 1.399");
}

.eavzsrtdt {
  d: path("m8.625 8.96l.458.046c.064.006.128.02.182.056c.242.158.338.483.137.895l-.87 2.062l-.892-.84z");
}

.ed41k8brv {
  d: path("M24.344 16.617c.287.175.57.5.676.64l.699-1.21c-.192-.113-.67-.394-1.051-.622a.58.58 0 0 0-.906.454c.004.351.222.52.582.738");
}

.ekn6pnbcj {
  fill: var(--svg-color--2f6dbd, #2F6DBD);
  fill-rule: evenodd;
  d: path("m14.259 12.563l.186-1.945l.548.053l-.187 1.945c-.039.402.025 1 .34 1.56c.312.551.877 1.084 1.873 1.36c2.131.59 3.394-.746 3.69-1.43c.127-.296.264-.824.387-1.372c.06-.27.117-.538.167-.776l.023-.111c.04-.19.074-.358.102-.482l.537.121a31 31 0 0 0-.124.584c-.05.239-.106.51-.168.785c-.122.54-.268 1.118-.42 1.468c-.378.878-1.887 2.422-4.34 1.743c-1.136-.315-1.82-.939-2.205-1.62a3.3 3.3 0 0 1-.41-1.883");
}

.emput3bhq {
  stop-color: var(--svg-color--907168, #907168);
}

.epp7qxb0e {
  d: path("M17.167 11.659c.034-.185-.093-.335-.127-.38l-.217.144l.07.252z");
}

.f35kr1b2b {
  stop-color: var(--svg-color--724c4d, #724C4D);
}

.fdr21fpoo {
  d: path("m17.82 11.806l-.535 1.014c-.11.208.014.46.248.503l.498.092a.348.348 0 0 0 .411-.382l-.137-1.138c-.028-.252-.365-.314-.484-.09");
}

.fe1ixid0a {
  stop-color: var(--svg-color--373536, #373536);
}

.ft5dv1b6b {
  fill: none;
}

.g1pman8wa {
  fill-rule: evenodd;
  d: path("M26.77 13.63a.5.5 0 0 1 .7.092c.267.346.662 1.257.366 2.406a.5.5 0 1 1-.969-.25c.212-.818-.089-1.416-.189-1.546a.5.5 0 0 1 .091-.701");
}

.g47ni5_fz {
  stop-color: var(--svg-color--846257, #846257);
}

.gdi6d5gtd {
  stop-color: var(--svg-color--836562, #836562);
  stop-opacity: 0;
}

.ge48w0b5j {
  stroke: var(--svg-color--201f22, #201F22);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.092 10.063a2 2 0 0 1 1.11-.043");
}

.ge6p9hb8t {
  stop-color: var(--svg-color--534285, #534285);
}

.gmg8hcbdj {
  stop-color: var(--svg-color--3c7dbf, #3C7DBF);
}

.h4st6nerq {
  d: path("m12.914 16.367l-2.14 7.86l4.609 2.171l4.422-1.953c.583-2.38 1.756-7.16 1.78-7.234c.032-.094.22-.844-.64-.97c-2.61-.358-6.328-.655-7.062-.687c-.588-.025-.89.532-.969.813");
}

.h97wn5p7r {
  fill-rule: evenodd;
  d: path("M25.992 12.833a.5.5 0 0 1 .703.075c.268.332.83 1.208.571 2.568a.5.5 0 1 1-.982-.187c.186-.976-.212-1.56-.367-1.753a.5.5 0 0 1 .075-.703");
}

.he60mdbwm {
  stop-color: var(--svg-color--f1bd46, #F1BD46);
}

.hgt5uebfs {
  stop-color: var(--svg-color--ddbe40, #DDBE40);
}

.hjpjmzbhg {
  d: path("m5.298 16.121l.335-6.413l3.094-.375l-.257 5.485a.2.2 0 0 0 .177.208l5.08.572l-.954 2.954l-5.904-.598a1.75 1.75 0 0 1-1.571-1.833");
}

.ht2yfkjwb {
  stop-color: var(--svg-color--5dd2ff, #5DD2FF);
}

.hvr6robrc {
  stop-color: var(--svg-color--05030d, #05030D);
}

.hxha0gmrz {
  stroke: var(--svg-color--201f22, #201F22);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.467 10.485c.316 0 .734.113 1.043.422");
}

.hxow8bcae {
  d: path("M8.883 4.842c-1.06.276-1.683 1.099-1.906 1.44a.05.05 0 0 1-.045.021a2.7 2.7 0 0 1-.957-.256a.05.05 0 0 1-.02-.07c.25-.41.873-1.28 2.009-1.782a4.3 4.3 0 0 1 1.792-.381c.046 0 .07-.055.038-.087a4 4 0 0 0-.415-.357a.05.05 0 0 0-.034-.01a5.1 5.1 0 0 0-1.57.417a4.9 4.9 0 0 0-2.217 1.948a.05.05 0 0 1-.073.014a2.7 2.7 0 0 1-.596-.64a.05.05 0 0 1-.001-.053A5.5 5.5 0 0 1 6.94 3.139c.319-.167.664-.274.95-.342c.05-.013.053-.084.002-.095a3.8 3.8 0 0 0-.837-.095h-.061l-.023.005c-.08.039-.16.07-.24.12a6 6 0 0 0-2.06 1.807a.05.05 0 0 1-.085-.009a4 4 0 0 1-.22-.747a.05.05 0 0 0-.083-.027c-.105.105-.203.22-.295.336a.05.05 0 0 0-.009.043a4.2 4.2 0 0 0 .413 1.026a.2.2 0 0 0 .044.083a3.2 3.2 0 0 0 1.24 1.166a3.1 3.1 0 0 0 1.208.353a.05.05 0 0 1 .045.036c.049.175.11.47.133.81a.05.05 0 0 1-.05.053c-.957-.029-1.725-.28-2.412-.782c-.951-.71-1.18-1.682-1.18-1.703c0-.026-.037-.025-.045 0c-.08.215-.135.44-.182.672a.05.05 0 0 0 .004.033c.2.395.543.92 1.131 1.353c.949.704 1.927.86 2.663.886a.05.05 0 0 1 .048.055a2.7 2.7 0 0 1-.26.888a.05.05 0 0 1-.051.027c-2.543-.3-3.33-1.522-3.34-1.543a.2.2 0 0 0-.075-.077c-.03-.019-.061.012-.052.047c.092.334.22.641.383.93l.013.016c.512.387 1.371.841 2.722 1.046a.05.05 0 0 1 .03.082a2.6 2.6 0 0 1-.665.526c-.038.021-.035.078.006.092q.225.082.469.134q.02.004.039-.008q.53-.387.804-.85l.008-.01l.013-.023q.004-.013.01-.025a3.2 3.2 0 0 0 .411-1.305a4.2 4.2 0 0 0-.16-1.524a.05.05 0 0 1 .006-.042a3.3 3.3 0 0 1 .631-.716a.048.048 0 0 1 .074.013c.215.39.584 1.217.505 2.206c-.096 1.151-.598 1.852-1.018 2.252c-.036.034-.008.096.04.088q.32-.045.617-.13a.05.05 0 0 0 .026-.018c.372-.48.722-1.176.805-2.16c.09-1.151-.345-2.087-.592-2.517a.05.05 0 0 1 .019-.068a2.4 2.4 0 0 1 .863-.275c.02-.002.04.008.048.026c.257.511.997 2.215.41 3.93c-.018.05.044.091.081.053q.307-.318.544-.702l.007-.019c.197-1.369-.236-2.602-.51-3.225a.05.05 0 0 1 .05-.07c.33.034.593.123.77.202c.04.019.085-.02.071-.061a5 5 0 0 0-.175-.461a.05.05 0 0 0-.03-.027a3.2 3.2 0 0 0-1.703-.036");
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

.ih0g4nbfz {
  fill: var(--svg-color--232226, #232226);
  d: path("M15.544 11.03c0 .149.117.193.168.23l1.492.032c-.034-.154-.27-.474-.77-.555c-.625-.101-.89.175-.89.293");
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

.j13l2ir_z {
  d: path("M16.738 11.058a.583.583 0 0 0-.686.622l1.107.205a.587.587 0 0 0-.421-.827");
}

.j8h3dgbhd {
  stop-color: var(--svg-color--604339, #604339);
}

.jbim1r-8q {
  stop-color: var(--svg-color--dca35e, #DCA35E);
  stop-opacity: 0;
}

.jd2_gubse {
  stop-color: var(--svg-color--28201c, #28201C);
}

.je851xbvd {
  stop-color: var(--svg-color--72433f, #72433F);
}

.jesbzuboj {
  d: path("M19.488 11.61a.587.587 0 0 1 .421.834l-1.116-.206a.59.59 0 0 1 .694-.627");
}

.jh6rb_-if {
  stop-color: var(--svg-color--fff75e, #FFF75E);
}

.jj-ghzbrk {
  stop-color: var(--svg-color--f8d84f, #F8D84F);
  stop-opacity: 0;
}

.jmde6ezpz {
  fill: var(--svg-color--1d0e22, #1D0E22);
  fill-rule: evenodd;
  d: path("M17.141 10.198c-.38-.127-.778-.037-1.003.026a.175.175 0 0 1-.094-.337c.233-.065.721-.184 1.208-.021a.175.175 0 1 1-.11.332");
}

.jw23vabrn {
  cx: 16.52px;
  cy: 11.271px;
  rx: 0.254px;
  ry: 0.129px;
}

.jx__8ve1w {
  stop-color: var(--svg-color--dca35e, #DCA35E);
}

.jx45yjlfo {
  stop-color: var(--svg-color--895d55, #895D55);
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

.kyri3g7rc {
  stop-color: var(--svg-color--6249ac, #6249AC);
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

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m2ds08s7w {
  stop-color: var(--svg-color--2c89f2, #2C89F2);
  stop-opacity: 0;
}

.m4rwtdbrs {
  fill: var(--svg-color--000, #000);
  d: path("M16.96 11.692a.33.33 0 0 0-.267-.39a.332.332 0 0 0-.38.426l.58.108a.33.33 0 0 0 .068-.144");
}

.mc69qbcuz {
  fill-rule: evenodd;
  d: path("M3.824 8.271a.5.5 0 0 1 .639.302c.08.225.493.986 1.711 1.372a.5.5 0 1 1-.302.953C4.328 10.41 3.696 9.4 3.522 8.91a.5.5 0 0 1 .302-.639");
}

.mfaqlgbhq {
  d: path("M30.18 30.414v-6.508c-1.258-.305-2.198.102-2.875.664l-.301.251c-.982.823-1.379 1.155-2.434 1.155c-.818 0-1.343-.467-1.903-.967c-.644-.573-1.335-1.189-2.573-1.189c-1.172 0-1.859.479-2.504.929c-.571.398-1.11.774-1.926.774c-.712 0-1.16-.336-1.657-.71c-.623-.467-1.323-.993-2.714-.993c-1.098 0-1.755.57-2.395 1.123c-.605.523-1.194 1.033-2.125 1.033c-.968 0-1.56-.557-2.194-1.156a20 20 0 0 0-.345-.32c-.625-.563-1.612-.706-1.96-.68v6.594z");
}

.mko_diovh {
  d: path("m25.476 21.992l-4.641-4.266l.078-.906l4.14 3.828z");
}

.mly26fbqy {
  stop-color: var(--svg-color--836562, #836562);
}

.mn-wyqbqw {
  d: path("M10.786 5.475c-.008-.026-.042-.037-.067-.048a2.5 2.5 0 0 0-.77-.201a.05.05 0 0 0-.05.069c.254.573.64 1.664.547 2.901c-.005.055.068.078.092.028a3.88 3.88 0 0 0 .248-2.75");
}

.mu1lsrbfz {
  stop-color: var(--svg-color--6d4c42, #6D4C42);
}

.mvtd0pbef {
  stroke: var(--svg-color--4178be, #4178BE);
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m14.72 10.644l-.188 1.946c-.086.898.282 2.62 2.413 3.21c2.293.636 3.68-.804 4.016-1.585c.279-.647.565-2.211.695-2.79");
}

.n_yku1v-w {
  stop-color: var(--svg-color--907168, #907168);
  stop-opacity: 0;
}

.n2b8gu5vw {
  stop-color: var(--svg-color--5472f7, #5472F7);
}

.n967l8b-u {
  stop-color: var(--svg-color--704549, #704549);
}

.nil-nrb9t {
  stop-color: var(--svg-color--ffffe9, #FFFFE9);
}

.nj1er27qb {
  stop-color: var(--svg-color--2c8bf2, #2C8BF2);
  stop-opacity: 0;
}

.npzdus8rc {
  d: path("M22.368 11.527a1.7 1.7 0 0 1-.086-.617c.063 0-.75-.104-1.164-.156l-3.531 5.43l3.336.304c1.289-.742 1.148-1.906 1.148-2.14v-.44c0-.1.032-.199.085-.284c.623-1.009.317-1.797.212-2.097");
}

.nvypefbww {
  stop-color: var(--svg-color--7856c9, #7856C9);
}

.nw16d5muy {
  stop-color: var(--svg-color--55313b, #55313B);
}

.nwegx7xkg {
  stop-color: var(--svg-color--99756c, #99756C);
}

.nx5i0kb9s {
  fill: var(--svg-color--765145, #765145);
  d: path("m5.298 16.121l.335-6.413l3.094-.375l-.257 5.485a.2.2 0 0 0 .177.208l5.08.572l-.954 2.954l-5.904-.598a1.75 1.75 0 0 1-1.571-1.833");
}

.nxxr3abyt {
  d: path("M3.424 5.167a.04.04 0 0 0-.002.025c.03.13.288 1.023 1.178 1.688c.687.502 1.454.753 2.411.782a.05.05 0 0 0 .051-.053a4.2 4.2 0 0 0-.133-.81a.05.05 0 0 0-.045-.036a3.1 3.1 0 0 1-1.208-.353a3.2 3.2 0 0 1-1.248-1.175a.1.1 0 0 1-.02-.033l-.016-.042l-.004-.009a4 4 0 0 1-.375-.895c-.012-.04-.064-.05-.088-.016a4 4 0 0 0-.5.927");
}

.o2b36j3xt {
  stop-color: var(--svg-color--6048a5, #6048A5);
  stop-opacity: 0;
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

.oxae2u2rt {
  fill-rule: evenodd;
  d: path("M26.375 15.023c.856 0 1.573.425 1.573 1.281v5.858c0 1.69-2.003 2.58-3.257 1.446l-5.09-4.599a1.55 1.55 0 1 1 2.079-2.3l3.008 2.719a.1.1 0 0 0 .167-.071l.098-3.053c0-.856.566-1.28 1.422-1.28");
}

.p_apwyb8c {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.638 10.859a.91.91 0 0 0-.996.519a.18.18 0 0 0 .131.25l1.433.265a.15.15 0 0 0 .178-.147a.915.915 0 0 0-.746-.887");
}

.p3zpjlb6d {
  fill: var(--svg-color--7d594a, #7D594A);
  fill-rule: evenodd;
  d: path("M26.375 15.023c.856 0 1.573.425 1.573 1.281v5.858c0 1.69-2.003 2.58-3.257 1.446l-5.09-4.599a1.55 1.55 0 1 1 2.079-2.3l3.008 2.719a.1.1 0 0 0 .167-.071l.098-3.053c0-.856.566-1.28 1.422-1.28");
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

.po79w8bfx {
  stop-color: var(--svg-color--9c786e, #9C786E);
  stop-opacity: 0;
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

.qq8mdzsuu {
  fill-rule: evenodd;
  d: path("M25.148 12.812a.5.5 0 0 1 .696.125l.013.018c.188.27.824 1.181.695 2.537a.5.5 0 0 1-.995-.094a2.73 2.73 0 0 0-.534-1.89a.5.5 0 0 1 .125-.696");
}

.qqvhld2kx {
  d: path("M14.812 16.015c.078-.437.324-.41.363-.418l4.348.38c.17-.016.503.091.484.648c-.117 1.328-1.25 2.617-3.034 2.328c-1.84-.277-2.321-1.895-2.161-2.938");
}

.qsi2djbas {
  stop-color: var(--svg-color--eaae49, #EAAE49);
}

.qvl3f1svv {
  stop-color: var(--svg-color--46a4f6, #46A4F6);
}

.rbdca_23i {
  fill: var(--svg-color--1d0e22, #1D0E22);
  fill-rule: evenodd;
  d: path("M19.311 10.463a.175.175 0 0 0 .161.189c.413.032.746.21.883.388a.175.175 0 0 0 .278-.212c-.215-.282-.656-.488-1.133-.525a.175.175 0 0 0-.189.16");
}

.rglr48bfo {
  stop-color: var(--svg-color--7c564f, #7C564F);
}

.rlocznbrk {
  stop-color: var(--svg-color--e59a2b, #E59A2B);
}

.rrljybbjf {
  stop-color: var(--svg-color--865350, #865350);
}

.rt0q9-bwa {
  d: path("M6.945 12.168c.163-1.363.943-1.735 1.313-1.75c-.488.4-.651 1.562-.672 2.094l.172 3.233l-.813.64c.042-.864-.162-2.855 0-4.217");
}

.rwcn2nbsr {
  stop-color: var(--svg-color--d9944a, #D9944A);
}

.sa851lbem {
  stop-color: var(--svg-color--765145, #765145);
}

.sb91vbc8w {
  d: path("M4.373 3.727c-.014.013-.01.037-.007.056a4 4 0 0 0 .22.747a.05.05 0 0 0 .086.01A6 6 0 0 1 6.73 2.731c.031-.02.018-.07-.02-.068c-.904.08-1.719.47-2.338 1.063");
}

.t_ucbwbbk {
  stop-color: var(--svg-color--654986, #654986);
  stop-opacity: 0;
}

.t1a7crb1v {
  stop-color: var(--svg-color--9c786e, #9C786E);
}

.t1ffwv_yc {
  stop-color: var(--svg-color--e0b93f, #E0B93F);
}

.t77dcut_r {
  stop-color: var(--svg-color--51c9ff, #51C9FF);
}

.tdiqapb8p {
  stop-color: var(--svg-color--795348, #795348);
}

.te623bspc {
  d: path("M3.388 7.548c.01.021.797 1.243 3.34 1.543a.05.05 0 0 0 .05-.027c.148-.296.227-.6.26-.888a.05.05 0 0 0-.047-.055c-.736-.026-1.714-.182-2.663-.886a3.75 3.75 0 0 1-1.03-1.166c-.024-.042-.088-.03-.094.017a4 4 0 0 0-.024.439c0 .369.028.726.208 1.023");
}

.tfkxk5q_t {
  stop-color: var(--svg-color--865350, #865350);
  stop-opacity: 0;
}

.u2vsikbqs {
  fill-rule: evenodd;
  d: path("M24.46 13.257a.5.5 0 0 1 .697.125l.04.056c.214.294.92 1.264.797 2.574a.5.5 0 1 1-.996-.095c.087-.915-.401-1.598-.617-1.9l-.046-.064a.5.5 0 0 1 .126-.696");
}

.u44kqtbwx {
  stop-color: var(--svg-color--856a63, #856A63);
}

.ubqrvr0_n {
  fill: var(--svg-color--6f4049, #6F4049);
  d: path("m17.638 11.945l-.535 1.014c-.11.209.014.46.248.504l.498.092a.348.348 0 0 0 .411-.382l-.138-1.139c-.027-.251-.364-.313-.484-.089");
}

.upn6hw37x {
  stop-color: var(--svg-color--e2a548, #E2A548);
}

.uua34abnm {
  d: path("M15.186 10.067c.148-1.182.828-1.271 1.277-1.23c1.074.097 2.836.48 3.899.788c1.044.304.992.848.992 1.153c0 .304-.18 1.035-.328 1.832c-.12.637.08.849.195.875c.117.02.4-.081.594-.656c.336-1.243 1.07-3.672.398-5.016s-1.719-1.79-2.937-2.023c-1.22-.235-2.618-.25-3.657.656c-1.226.953-1.336 3.406-1.343 4.312c-.008.907.085 1.344.406 1.243c.32-.102.324-.504.504-1.934");
}

.v3vfkabey {
  d: path("M13.805 10.73c.163-.45.503-.877.672-1.007l3.375 2.43l-.742 3.718c-.094 0-.552-.031-1.633-.156c-1.351-.156-1.992-.656-2.195-1.711c-.134-.697.11-1.325.32-1.672a.64.64 0 0 0 .097-.397c-.035-.314-.051-.769.106-1.205");
}

.v679tzbuc {
  stop-color: var(--svg-color--8d6bd3, #8D6BD3);
  stop-opacity: 0;
}

.v81yadizx {
  stop-color: var(--svg-color--89655f, #89655F);
  stop-opacity: 0;
}

.vb1011phq {
  d: path("M19.42 11.726c.03.062-.068.113-.178.168c-.11.054-.192.092-.223.03c-.03-.062.034-.157.144-.212c.111-.055.226-.048.256.014");
}

.vi9q-fb9u {
  stop-color: var(--svg-color--ffcd36, #FFCD36);
}

.vuc-e-qgu {
  d: path("M30.18 29.867v-11.39c-1.258-.305-2.198.1-2.875.663l-.301.252c-.982.822-1.379 1.155-2.434 1.155c-.818 0-1.343-.468-1.903-.967c-.644-.574-1.335-1.19-2.573-1.19c-1.172 0-1.859.48-2.504.929c-.571.399-1.11.774-1.926.774c-.712 0-1.16-.336-1.657-.71c-.623-.467-1.323-.993-2.714-.993c-1.098 0-1.755.57-2.395 1.123c-.605.524-1.194 1.034-2.125 1.034c-.968 0-1.56-.558-2.194-1.157a20 20 0 0 0-.345-.32c-.625-.562-1.612-.706-1.96-.68v11.477z");
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

.w6k2ut5zu {
  fill: var(--svg-color--232226, #232226);
  d: path("M20.622 12.048c-.054.139-.18.137-.24.154l-1.402-.512c.087-.131.423-.344.918-.238c.62.132.767.486.724.596");
}

.w86h2iq4q {
  stop-color: var(--svg-color--ffe451, #FFE451);
  stop-opacity: 0;
}

.wao9xvbcz {
  d: path("M9.754 9.305c.025-.025.013-.08.022-.114l.001-.004c.588-1.714-.152-3.418-.409-3.929a.05.05 0 0 0-.048-.026a2.4 2.4 0 0 0-.863.275a.05.05 0 0 0-.019.068c.247.43.682 1.366.592 2.517c-.074.872-.357 1.518-.68 1.989c-.028.04.012.093.057.076a3.9 3.9 0 0 0 1.347-.852");
}

.wb6ooab1e {
  stop-color: var(--svg-color--673b44, #673B44);
}

.wda4yc_iv {
  stop-color: var(--svg-color--3f83e6, #3F83E6);
}

.wwjt5lyhp {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.654 11.46a.92.92 0 0 1 .75.847a.18.18 0 0 1-.214.189l-1.444-.267a.152.152 0 0 1-.115-.203a.92.92 0 0 1 1.023-.566");
}

.x114bxlro {
  stop-color: var(--svg-color--f9cd54, #F9CD54);
}

.x7sdhebzt {
  cx: 16.52px;
  cy: 11.271px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.254px;
  ry: 0.129px;
}

.x9d7jz1fb {
  stop-color: var(--svg-color--d9afcd, #D9AFCD);
}

.xdiwrunqp {
  d: path("M7.467 10.378c.031-.004.052-.044.075-.066c.42-.4.922-1.1 1.017-2.252c.08-.989-.289-1.816-.504-2.206a.048.048 0 0 0-.074-.013c-.324.27-.535.568-.631.716a.05.05 0 0 0-.006.042c.076.246.22.846.16 1.524a3.2 3.2 0 0 1-.418 1.322l-.003.008l-.013.024l-.008.01a2.8 2.8 0 0 1-.695.766c-.034.027-.022.082.021.09a4 4 0 0 0 1.079.035");
}

.xerb7tdfi {
  fill: var(--svg-color--87014e, #87014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.788 13.594c.221.178.501.311.816.374c.317.064.624.048.897-.031a.15.15 0 0 1 .168.063a.14.14 0 0 1-.02.178m-1.861-.585l1.826.55m-1.826-.55a.15.15 0 0 0-.18-.005a.14.14 0 0 0-.05.171m.23-.165l-.184.146m2.045.438l-.035-.036m.035.036l-.035-.036m.035.036a1.27 1.27 0 0 1-1.157.349a1.27 1.27 0 0 1-.934-.768m2.056.383c-.277.28-.69.42-1.113.336a1.23 1.23 0 0 1-.897-.738m-.046.02l.046-.02m-.046.02v-.001l.046-.02");
}

.xq_1inbmx {
  stop-color: var(--svg-color--604339, #604339);
  stop-opacity: 0;
}

.xsaxc8btc {
  d: path("M19.907 12.205a.55.55 0 0 0-.093-.325l-.201.153l.048.16z");
}

.xtrjnaccv {
  stop-color: var(--svg-color--ffd739, #FFD739);
  stop-opacity: 0;
}

.y0tde_bcy {
  stop-color: var(--svg-color--a186df, #A186DF);
}

.ypqigjezu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.42 11.726c.03.062-.068.113-.178.168c-.11.054-.192.092-.223.03c-.03-.062.034-.157.144-.212c.111-.055.226-.048.256.014");
}

.yy8y3t7sm {
  stop-color: var(--svg-color--866bd4, #866BD4);
  stop-opacity: 0;
}

.z8efi882d {
  stop-color: var(--svg-color--89655f, #89655F);
}

.zdfpz2b9v {
  stop-color: var(--svg-color--9e83e0, #9E83E0);
}

.zepb-5s8y {
  stop-color: var(--svg-color--9d7c72, #9D7C72);
}

.zfso0abuk {
  d: path("M6.977 6.281c.223-.34.846-1.163 1.906-1.439a3.2 3.2 0 0 1 1.57-.001c.042.01.078-.032.058-.07a3.9 3.9 0 0 0-.674-.943c-.018-.02-.054-.014-.08-.014a4.3 4.3 0 0 0-1.793.38c-1.136.503-1.76 1.374-2.01 1.783a.05.05 0 0 0 .02.07c.4.19.76.243.958.256a.05.05 0 0 0 .045-.022");
}

</style>
