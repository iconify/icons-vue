<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyMfqXb)"><path class="dpxhxrnfz"/><path fill="url(#isoHuke)" class="ejq-m9lis"/></g><path fill="url(#iPqW3Sd)" class="ejq-m9lis"/><path fill="url(#ifpVvYd)" class="ejq-m9lis"/><path fill="url(#iuAkgNd)" class="ejq-m9lis"/><path fill="url(#iE2odcb)" class="ejq-m9lis"/><g filter="url(#iZJXZae)"><path class="cdkho4bzl"/><path fill="url(#iTtDOsg)" class="yy8dgg-sf"/></g><path fill="url(#i0F59iE)" class="un_ukdoyr"/><path fill="url(#i0027lc)" class="un_ukdoyr"/><path fill="url(#i0faaDd)" class="dkirjjblf"/><path fill="url(#iXtfGle)" class="o7xzxjeog"/><path fill="url(#iO2Ygtb)" class="o7xzxjeog"/><g filter="url(#ix4OKyS)"><path fill="url(#iA62u2b)" class="rw2hv3b3j"/><path fill="url(#iQe5OKe)" class="rw2hv3b3j"/></g><g filter="url(#izmns5n)"><circle fill="url(#iKauWab)" class="rgxydrbdo"/></g><g filter="url(#intEi0c)"><circle fill="url(#i1dqqdb)" class="i1i4-ybdv"/></g><g filter="url(#iyIPR1d)"><circle fill="url(#imOfnhd)" class="zn6vq8_5x"/></g><rect fill="url(#i4eVNRd)" transform="rotate(26.595 20.662 12.657)" class="gsp1_cbyb"/><g filter="url(#i9a4Mod)"><path fill="url(#ifyDJfb)" class="ypt34m9md"/></g><path class="my_np7pnq"/><g filter="url(#iuBMe2d)"><path class="oi31bnzvs"/><path fill="url(#i0sPYpb)" class="p3pobob2w"/><path fill="url(#iThrUAc)" class="p3pobob2w"/></g><g filter="url(#iTlBcMK)"><path fill="url(#i1lCYkb)" class="d_h7vwb5y"/><path fill="url(#iNgoxtd)" class="d_h7vwb5y"/><path fill="url(#iP90ZBd)" class="d_h7vwb5y"/></g><path fill="url(#iXcaQFM)" class="d_h7vwb5y"/><path fill="url(#iO6MSyd)" class="qm6d4zl7k"/><path fill="url(#ihi3Fye)" class="qm6d4zl7k"/><path clip-rule="evenodd" class="pzos0ebxn"/><path fill="url(#iqbxFyb)" clip-rule="evenodd" class="dt0ulhsox"/><path clip-rule="evenodd" class="i2-j8r05r"/><path fill="url(#iGZgsvy)" clip-rule="evenodd" class="rvk092zcg"/><path clip-rule="evenodd" class="l6lc_1mea"/><path fill="url(#i4Ci3Ed)" clip-rule="evenodd" class="ga0zoe4ka"/><path clip-rule="evenodd" class="ry7h8ubvo"/><path fill="url(#i1cULAb)" clip-rule="evenodd" class="jtf97bc6c"/><path class="wr_om0nho"/><path fill="url(#iLudbrL)" class="w7mkidbxg"/><g filter="url(#iM63qfe)"><path fill="url(#iXWxVfc)" class="e_iyf8bcq"/></g><g filter="url(#iKoVDCb)"><path fill="url(#ii4iQSd)" class="isd49kjbn"/></g><g filter="url(#izJRihd)"><path stroke="url(#iCB6LEN)" class="vcu7f7bip"/></g><circle fill="url(#iHnnnne)" class="wj9xfsbot"/><g filter="url(#iekiJrj)"><circle fill="url(#iZ4ZUHe)" class="b-x1qr_ov"/></g><g filter="url(#i1IuAZU)"><circle fill="url(#is4wAye)" class="sqzx0mbth"/><circle fill="url(#ixis0bc)" class="sqzx0mbth"/></g><g filter="url(#iW20BsU)"><circle class="estigtb-d"/><circle fill="url(#i51biuv)" class="w-kcyrvzt"/><circle fill="url(#iq9nTiC)" class="w-kcyrvzt"/></g><path fill="url(#ihXY0Ne)" class="x30hr5izj"/><path fill="url(#iBmityp)" class="x30hr5izj"/><path fill="url(#ifGjEUc)" class="x30hr5izj"/><path fill="url(#i7iMnUm)" class="x30hr5izj"/><path fill="url(#i5a6IHd)" class="x30hr5izj"/><g filter="url(#iyuJQgd)"><path class="g9ee7jwuh"/><path fill="url(#ijugUAd)" class="x-g1vtjtj"/><path fill="url(#ihZIb5b)" class="x-g1vtjtj"/><path fill="url(#isgKcpd)" class="x-g1vtjtj"/><path fill="url(#iptmKpe)" class="x-g1vtjtj"/><path fill="url(#iVbbObc)" class="x-g1vtjtj"/><path fill="url(#i5xjtie)" class="x-g1vtjtj"/></g><path fill="url(#isrbB2b)" class="x-g1vtjtj"/><path fill="url(#iurqkGd)" class="x-g1vtjtj"/><path fill="url(#ibipgbe)" class="x-g1vtjtj"/><g filter="url(#ie3rUub)"><path class="n4mu-rrxw"/></g><g filter="url(#iWU22ib)"><path class="wt5zlcbim"/><path fill="url(#idVkThd)" class="uft06xbgm"/><path fill="url(#ipwfp4l)" class="uft06xbgm"/><path fill="url(#iBI6rhc)" class="uft06xbgm"/></g><g filter="url(#innmNad)"><path stroke="url(#ijk3JVb)" class="aq7_qp7np"/></g><path class="y8xbx2bgs"/><path class="ntgqrnb5k"/><path fill="url(#i2ih5rb)" class="g1gdzbclh"/><path class="nnq7diqka"/><g filter="url(#iYmsaye)"><path class="zuu8q1pyu"/><path fill="url(#i3XZEsy)" class="hsurblbrz"/></g><g filter="url(#iTXNOWb)"><path fill="url(#iCLhpXw)" class="xm16noihw"/></g><path class="b416-eb9q"/><path fill="url(#iUsRCNu)" class="lby2z07uq"/><path class="mt54hdcxh"/><g filter="url(#ipgkFUd)"><path fill="url(#iRIrQLe)" class="c09cwob2u"/></g><g filter="url(#ipY6w6b)"><ellipse transform="rotate(-27.914 12.854 5.796)" class="pul53bbta"/><ellipse fill="url(#i09BT5w)" transform="rotate(-27.914 12.854 5.796)" class="x_57qtbhm"/></g><g filter="url(#i9gAuge)"><path fill="url(#ihPgLue)" clip-rule="evenodd" class="ofrhzw7xm"/></g><g filter="url(#isCuSRc)"><path class="s34zpdb_t"/></g><g filter="url(#iAzNm8N)"><path fill="url(#iy3iu9b)" clip-rule="evenodd" class="xdc35tb2f"/></g><g filter="url(#iYikwdU)"><path class="h5_84-b9g"/></g><defs><radialGradient id="iPqW3Sd" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.986 21.617)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="iuAkgNd" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -6.125 3.8162 2.21963 22.204 21.773)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="iE2odcb" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.617)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iTtDOsg" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.169 25.054)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="i0F59iE" cx="0" cy="0" r="1" gradientTransform="rotate(-82.266 19.83 7.653)scale(1.27724 1.67272)" gradientUnits="userSpaceOnUse"><stop class="jobbcdb5u"/><stop offset="1" class="ztrk-1hpr"/></radialGradient><radialGradient id="iO2Ygtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.32)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="iQe5OKe" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.689 2.742)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="iKauWab" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.238 11.061)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i1dqqdb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.403)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="imOfnhd" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.19 9.096)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i4eVNRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 12.955)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="l0ervjwrq"/><stop offset="1" class="h8-lgt47k"/></radialGradient><radialGradient id="ifyDJfb" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.227 10.849)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="q-9x-2bzr"/><stop offset="1" class="doutuqf7h"/></radialGradient><radialGradient id="i0sPYpb" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.952 6.641)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="jioe1_9gu"/><stop offset="1" class="t5lf5ccyt"/></radialGradient><radialGradient id="iThrUAc" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.395 10.476)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="fqeviqb2e"/><stop offset="1" class="to9zfdmjz"/></radialGradient><radialGradient id="iNgoxtd" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.274)" gradientUnits="userSpaceOnUse"><stop class="lj0l7tb9r"/><stop offset="1" class="zrzxj2epv"/></radialGradient><radialGradient id="iP90ZBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49191 -2.04898 0 13.776 7.453)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="vgauzicqp"/><stop offset="1" class="r0iiaeguw"/></radialGradient><radialGradient id="iXcaQFM" cx="0" cy="0" r="1" gradientTransform="matrix(1.38038 -.82813 3.08645 5.14471 17.339 21.086)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="t502ec3cr"/><stop offset="1" class="oipf0m4co"/></radialGradient><radialGradient id="ihi3Fye" cx="0" cy="0" r="1" gradientTransform="matrix(3.55689 1.62587 -.93464 2.0447 18.61 10.6)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="g99cn0bet"/><stop offset="1" class="gq1i90b_a"/><stop offset="1" class="airol1bay"/></radialGradient><radialGradient id="iqbxFyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.32031 -.9626 1.21082 -.4029 5.665 13.485)" gradientUnits="userSpaceOnUse"><stop offset=".081" class="bohes4bvb"/><stop offset="1" class="b8-5lhb5p"/></radialGradient><radialGradient id="iGZgsvy" cx="0" cy="0" r="1" gradientTransform="matrix(-.25782 -.71094 1.29265 -.46878 5.649 13.899)" gradientUnits="userSpaceOnUse"><stop offset=".081" class="bohes4bvb"/><stop offset="1" class="b8-5lhb5p"/></radialGradient><radialGradient id="i4Ci3Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-.25403 -1.03125 1.96272 -.48347 5.747 14.68)" gradientUnits="userSpaceOnUse"><stop offset=".081" class="bohes4bvb"/><stop offset="1" class="b8-5lhb5p"/></radialGradient><radialGradient id="i1cULAb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 -.59147 1.24454 -.57535 6.047 14.922)" gradientUnits="userSpaceOnUse"><stop offset=".081" class="bohes4bvb"/><stop offset="1" class="b8-5lhb5p"/></radialGradient><radialGradient id="iLudbrL" cx="0" cy="0" r="1" gradientTransform="matrix(.42822 .95084 -2.90206 1.30698 6.516 14.367)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="b8-5lhb5p"/><stop offset="1" class="bohes4bvb"/></radialGradient><radialGradient id="iXWxVfc" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.54 15.326)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iHnnnne" cx="0" cy="0" r="1" gradientTransform="matrix(.76552 0 0 1.33967 11.125 6.135)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ixis0bc" cx="0" cy="0" r="1" gradientTransform="matrix(.36063 -.2626 .29972 .41161 16.166 6.02)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="i51biuv" cx="0" cy="0" r="1" gradientTransform="rotate(-61.467 13.453 -10.197)scale(.75003 .439)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iq9nTiC" cx="0" cy="0" r="1" gradientTransform="matrix(.1131 .11196 -.14433 .14581 16.003 6.135)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="ifGjEUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.74529 -4.27645 0 14.139 5.44)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="i7iMnUm" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57019 .70177 0 14.948 5.58)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="i5a6IHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60674 .75453 0 12.96 5.566)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="ijugUAd" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 7.09 5.19)scale(2.44557 4.15892)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="isgKcpd" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 8.133 -3.251)scale(.87291 .4287)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iptmKpe" cx="0" cy="0" r="1" gradientTransform="matrix(.37478 -.85784 .69963 .30566 15.769 5.377)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iVbbObc" cx="0" cy="0" r="1" gradientTransform="matrix(.43308 .53737 -.47446 .38238 13.586 2.383)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="i5xjtie" cx="0" cy="0" r="1" gradientTransform="matrix(.63297 -1.32423 .45754 .2187 15.752 4.294)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="isrbB2b" cx="0" cy="0" r="1" gradientTransform="rotate(75.569 5.577 10.368)scale(.45716 .75157)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iurqkGd" cx="0" cy="0" r="1" gradientTransform="matrix(.48288 .6975 -1.45148 1.00487 12.013 2.933)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="ibipgbe" cx="0" cy="0" r="1" gradientTransform="rotate(155.748 6.76 3.666)scale(3.44844 4.31498)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="ijk3JVb" cx="0" cy="0" r="1" gradientTransform="matrix(.01073 -.27363 .8209 .0322 13.888 7.885)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="i2ih5rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39398 -.46618 0 14.875 5.983)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i3XZEsy" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 8.826 -.681)scale(.16498 .22714)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUsRCNu" cx="0" cy="0" r="1" gradientTransform="matrix(0 .394 -.4662 0 12.972 5.983)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i09BT5w" cx="0" cy="0" r="1" gradientTransform="matrix(-.00337 -.21548 .25902 -.00406 12.847 5.933)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihPgLue" cx="0" cy="0" r="1" gradientTransform="matrix(.08585 -.35411 .77687 .18833 14.994 5.175)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iy3iu9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.08585 -.35411 .77687 -.18833 12.856 5.175)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><filter id="iyMfqXb" width="23.977" height="13.398" x="6.016" y="16.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="iZJXZae" width="20.681" height="10.082" x="6.11" y="20.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".75"/></filter><filter id="ix4OKyS" width="24.344" height="8.644" x="2.007" y="20.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="izmns5n" width="2.686" height="2.686" x="24.571" y="13.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="intEi0c" width="2.186" height="2.186" x="27.821" y="11.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="iyIPR1d" width="1.928" height="1.928" x="25.946" y="9.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="i9a4Mod" width="2.857" height="2.898" x="20.532" y="11.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.556863 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="iuBMe2d" width="5.571" height="6.952" x="7.773" y="7.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.396078 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="iTlBcMK" width="14.97" height="18.152" x="8.427" y="7.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.537255 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="iM63qfe" width="17.737" height="14.8" x="13.579" y="15.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation="1"/></filter><filter id="iKoVDCb" width="6.506" height="14.75" x="14.572" y="7.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".375"/></filter><filter id="izJRihd" width="5.506" height="5.421" x="17.991" y="7.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".3"/></filter><filter id="iekiJrj" width="1.868" height="1.868" x="10.92" y="5.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".25"/></filter><filter id="i1IuAZU" width="1.707" height="1.707" x="15.275" y="5.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="iW20BsU" width="1.868" height="1.868" x="15.069" y="5.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".25"/></filter><filter id="iyuJQgd" width="5.497" height="3.659" x="11.176" y="2.233" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_5147_19680" result="effect2_innerShadow_5147_19680"/></filter><filter id="ie3rUub" width="2.268" height="2.67" x="12.687" y="5.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".375"/></filter><filter id="iWU22ib" width="1.019" height="1.37" x="13.415" y="5.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".05"/></filter><filter id="innmNad" width="1.804" height=".868" x="13.023" y="7.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".05"/></filter><filter id="iYmsaye" width=".456" height=".417" x="14.499" y="5.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".05"/></filter><filter id="iTXNOWb" width=".614" height=".624" x="14.809" y="5.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".1"/></filter><filter id="ipgkFUd" width=".656" height=".679" x="12.871" y="5.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".1"/></filter><filter id="ipY6w6b" width=".511" height=".42" x="12.598" y="5.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".05"/></filter><filter id="i9gAuge" width="1.135" height=".859" x="14.476" y="4.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="isCuSRc" width="1.173" height=".647" x="14.457" y="4.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".075"/></filter><filter id="iAzNm8N" width="1.135" height=".859" x="12.239" y="4.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19680"/></filter><filter id="iYikwdU" width="1.173" height=".647" x="12.22" y="4.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19680" stdDeviation=".075"/></filter><linearGradient id="isoHuke" x1="7.172" x2="16.735" y1="29.211" y2="29.211" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="ifpVvYd" x1="16.86" x2="16.766" y1="30.117" y2="28.492" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="i0027lc" x1="10.344" x2="9.579" y1="25.82" y2="25.883" gradientUnits="userSpaceOnUse"><stop class="vt7w43b0h"/><stop offset="1" class="z7xjq9sfn"/></linearGradient><linearGradient id="i0faaDd" x1="21.172" x2="19.469" y1="21.774" y2="22.86" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="j4yrk8b8m"/></linearGradient><linearGradient id="iXtfGle" x1="22.095" x2="23.329" y1="24.68" y2="25.961" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="iA62u2b" x1="5.891" x2="25.735" y1="29.086" y2="22.18" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="i1lCYkb" x1="15.777" x2="15.777" y1="7.453" y2="25.414" gradientUnits="userSpaceOnUse"><stop class="nxcp0hivj"/><stop offset="1" class="p79aa0p9z"/></linearGradient><linearGradient id="iO6MSyd" x1="23.651" x2="16.517" y1="12.35" y2="8.396" gradientUnits="userSpaceOnUse"><stop class="y60usm6nn"/><stop offset=".91" class="u6gia-bos"/></linearGradient><linearGradient id="ii4iQSd" x1="17.826" x2="20.269" y1="8.008" y2="21.244" gradientUnits="userSpaceOnUse"><stop class="yrtrc6n_d"/><stop offset="1" class="kkuk5w_fi"/></linearGradient><linearGradient id="iCB6LEN" x1="22.438" x2="18.766" y1="11.727" y2="7.836" gradientUnits="userSpaceOnUse"><stop class="tgz_9qxcq"/><stop offset="1" class="zvqcq9hxr"/></linearGradient><linearGradient id="iZ4ZUHe" x1="11.854" x2="11.574" y1="6.256" y2="6.256" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="is4wAye" x1="16.477" x2="16.12" y1="5.659" y2="6.765" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="ihXY0Ne" x1="15.685" x2="12.354" y1="6.305" y2="6.801" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iBmityp" x1="11.571" x2="12.58" y1="7.481" y2="7.349" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="ihZIb5b" x1="11.804" x2="13.07" y1="6.018" y2="3.77" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="idVkThd" x1="13.548" x2="13.957" y1="6.592" y2="6.592" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="ipwfp4l" x1="14.334" x2="13.887" y1="6.733" y2="6.727" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iBI6rhc" x1="14.01" x2="14.01" y1="7.057" y2="6.807" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iCLhpXw" x1="15.215" x2="15.078" y1="5.861" y2="5.945" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRIrQLe" x1="13.296" x2="13.159" y1="5.861" y2="5.945" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-surfing" /></template>
<style>
.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.airol1bay {
  stop-color: var(--svg-color--815ecd, #815ECD);
  stop-opacity: 0;
}

.aq7_qp7np {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.925 7.5a1.3 1.3 0 0 1-.604-.143c-.06-.03-.124.037-.087.091c.146.221.4.369.69.369s.545-.148.691-.369c.038-.056-.026-.122-.086-.091c-.175.091-.38.143-.604.143Z");
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.b-x1qr_ov {
  cx: 11.854px;
  cy: 6.135px;
  r: 0.434px;
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.b416-eb9q {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.88 5.51a.61.61 0 0 0-.59.462a.12.12 0 0 0 .117.149h.973a.1.1 0 0 0 .099-.119a.61.61 0 0 0-.598-.491");
}

.b8-5lhb5p {
  stop-color: var(--svg-color--e39647, #E39647);
  stop-opacity: 0;
}

.bohes4bvb {
  stop-color: var(--svg-color--e39647, #E39647);
}

.c09cwob2u {
  d: path("M13.327 5.973c0-.126-.103-.21-.13-.235l-.126.121l.077.158z");
}

.cdkho4bzl {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("M21.985 27.18L7.61 28.68c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.199 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d_h7vwb5y {
  d: path("M12.759 11.5c-.432-1.715.169-3.161.507-3.484l2.344-.563h1.742c1.524 0 2.822.19 4.203 1.258c1.354 1.047 1.622 2.8 1.589 3.593a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.372-.066-1.274-1-2.015c-.606-.48-1.519-.531-2.146-.494a.373.373 0 0 0-.323.498c.316.956.84 2.513 1.212 3.52c.546 1.484-.11 2.953.375 4.484c.377 1.192 1.203 2.419 1.636 2.92a.04.04 0 0 1-.013.064l-1.834.851a.04.04 0 0 1-.048-.01c-1.848-2.157-2.5-3.826-2.562-3.989c-.062-.164-.23-.531-.574-.531c-.275 0-.59.351-.809.73l-4.667 7.137a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.067c1.499-3.164 4.542-9.51 4.773-10.058c.21-.5.181-.917.14-1.086c-.03-.13-.218-.71-.585-2.172");
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.dkirjjblf {
  d: path("M19.837 22.86a29 29 0 0 1-.907-.868l1.867-.883c.075.132.51.8.72 1.118z");
}

.doutuqf7h {
  stop-color: var(--svg-color--ffb834, #FFB834);
}

.dpxhxrnfz {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.595H6.017c3.433-1.326 10.769-4.345 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976c1.172-1.684 2.062-2.293 3.922-2.035c1.691.234 3.164 1.574 3.289 4.039c0 4.593-2.74 6.555-4.164 7.511c-1.907 1.28-4.625 1.326-6.078 1.28");
}

.dt0ulhsox {
  fill-rule: evenodd;
  d: path("M7.127 13.39c-.941-.283-1.295.01-1.388.12a.375.375 0 1 1-.57-.488c.328-.382 1.014-.699 2.174-.35a.375.375 0 1 1-.216.719");
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e_iyf8bcq {
  d: path("M26.485 24.18c.981-2.279.626-3.887.055-5.014c-.474-.935-.003-1.662 1.018-1.42c.737.174 1.364.694 1.54 1.43c.721 3.025-.313 6.182-3.582 7.816c-2.95 1.475-7.854 1.594-9.937 1.47c3 0 9.804-1.723 10.906-4.282");
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.ejq-m9lis {
  d: path("M19.75 29.595H6.017c3.433-1.326 10.769-4.345 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976c1.172-1.684 2.062-2.293 3.922-2.035c1.691.234 3.164 1.574 3.289 4.039c0 4.593-2.74 6.555-4.164 7.511c-1.907 1.28-4.625 1.326-6.078 1.28");
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.estigtb-d {
  cx: 16.003px;
  cy: 6.135px;
  r: 0.434px;
  fill: var(--svg-color--ffbf34, #FFBF34);
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

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fqeviqb2e {
  stop-color: var(--svg-color--1154b9, #1154B9);
}

.ft5dv1b6b {
  fill: none;
}

.g1gdzbclh {
  d: path("M14.876 5.63a.39.39 0 0 1 .375.491H14.5a.39.39 0 0 1 .377-.492");
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g99cn0bet {
  stop-color: var(--svg-color--2965ce, #2965CE);
}

.g9ee7jwuh {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m16.027 3.309l.187.093a.86.86 0 0 1 .445.93L16.4 5.66c-.023.137-.113.229-.25.232c.016-.22.03-.574.036-.63c.02-.189-.01-.244-.184-.416a.55.55 0 0 1-.163-.373V4.1a.25.25 0 0 0-.187-.233a7.2 7.2 0 0 0-1.709-.186c-.842 0-1.427.117-1.708.186a.23.23 0 0 0-.187.233v.372c0 .14-.047.28-.164.373l-.07.07c-.094.07-.14.215-.14.331c.005.068.015.459.025.622a.276.276 0 0 1-.26-.232l-.257-1.327a.89.89 0 0 1 .468-.907c.443-.194.604-.488.96-.791a.86.86 0 0 1 .959-.14c.234.07.491.07.725 0a1.05 1.05 0 0 1 1.03.233l.35.35c.095.115.211.185.352.255");
}

.ga0zoe4ka {
  fill-rule: evenodd;
  d: path("M5.25 14.514q-.005.007-.002.001a.375.375 0 0 1-.69-.296c.056-.128.165-.253.27-.354a2.6 2.6 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.369a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.262a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gq1i90b_a {
  stop-color: var(--svg-color--2965ce, #2965CE);
  stop-opacity: 0;
}

.gsp1_cbyb {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.657px;
  rx: 0.299px;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.h5_84-b9g {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.445 5.111c.09-.084.35-.227.723-.192");
}

.h8-lgt47k {
  stop-color: var(--svg-color--de8137, #DE8137);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hsurblbrz {
  d: path("M14.848 5.711c.027.038-.03.083-.097.132c-.066.05-.114.084-.142.047s.003-.107.069-.156c.066-.05.142-.06.17-.023");
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i1i4-ybdv {
  cx: 28.864px;
  cy: 12.66px;
  r: 1.043px;
}

.i2-j8r05r {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  fill-rule: evenodd;
  d: path("M5.404 13.986c0 .001.02-.027.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.isd49kjbn {
  d: path("M16.782 13.297c-.65-1.28-1.166-3.185-1.443-4.423a.714.714 0 0 1 .588-.856c.447-.075.855.272.91.722c.205 1.698.95 3.373 1.445 4.682c.578 1.531.312 1.063.234 3.516c-.057 1.781 1.266 3.25 1.813 4.11l-.407.21c-.609-.828-2.203-2.945-2.203-4.851c0-1.791.063-1.141-.937-3.11");
}

.j4yrk8b8m {
  stop-color: var(--svg-color--e28e5b, #E28E5B);
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jioe1_9gu {
  stop-color: var(--svg-color--5391be, #5391BE);
}

.jobbcdb5u {
  stop-color: var(--svg-color--ffc73f, #FFC73F);
}

.jtf97bc6c {
  fill-rule: evenodd;
  d: path("M5.611 14.792a.375.375 0 0 1-.69-.295c.093-.216.328-.445.6-.605a1.76 1.76 0 0 1 1.119-.236a.375.375 0 1 1-.099.743a1 1 0 0 0-.641.14a1 1 0 0 0-.215.165a.5.5 0 0 0-.074.088");
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.kkuk5w_fi {
  stop-color: var(--svg-color--6096e0, #6096E0);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l0ervjwrq {
  stop-color: var(--svg-color--ef972b, #EF972B);
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l6lc_1mea {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  fill-rule: evenodd;
  d: path("M5.25 14.514q-.005.007-.002.001a.375.375 0 0 1-.69-.296c.056-.128.165-.253.27-.354a2.6 2.6 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.369a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.262a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lby2z07uq {
  d: path("M12.971 5.63a.39.39 0 0 0-.375.491h.752a.392.392 0 0 0-.377-.492");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0l7tb9r {
  stop-color: var(--svg-color--2b68b8, #2B68B8);
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
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

.mt54hdcxh {
  fill: var(--svg-color--000, #000);
  d: path("M13.194 6.018c0-.123-.1-.222-.223-.222a.222.222 0 0 0-.198.325h.395a.2.2 0 0 0 .026-.103");
}

.my_np7pnq {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  d: path("M7.563 12.625h.594c-.106.669.07 1.612.172 2c-1.007.131-1.696-.112-1.914-.25l-.11-1.46c.332-.257.977-.3 1.258-.29");
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n4mu-rrxw {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m13.805 6.081l-.358.742c-.044.152.062.305.213.305h.322c.15 0 .257-.155.213-.305l-.218-.742c-.046-.164-.123-.164-.172 0");
}

.nnq7diqka {
  fill: var(--svg-color--000, #000);
  d: path("M14.653 6.018c0-.123.1-.222.223-.222a.222.222 0 0 1 .198.325h-.394a.2.2 0 0 1-.027-.103");
}

.ntgqrnb5k {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.967 5.51a.61.61 0 0 1 .59.463a.12.12 0 0 1-.116.148h-.973a.1.1 0 0 1-.1-.118a.61.61 0 0 1 .598-.492");
}

.nxcp0hivj {
  stop-color: var(--svg-color--3794e2, #3794E2);
}

.o7xzxjeog {
  d: path("m23.469 25.174l-.422-1.143l-2.351.537l2.225 1.098a.396.396 0 0 0 .547-.492");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.ofrhzw7xm {
  fill-rule: evenodd;
  d: path("M14.701 5.173c.314-.03.515.093.564.138a.206.206 0 0 0 .28-.303c-.134-.123-.45-.286-.882-.246a.206.206 0 0 0 .038.41");
}

.oi31bnzvs {
  fill: var(--svg-color--3086d6, #3086D6);
  d: path("M10.684 11.543c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.03c.3-.026 1.148-.108 2.5-.718c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.387c-.376 1.032-1.005 2.246-2.38 3.262");
}

.oipf0m4co {
  stop-color: var(--svg-color--4861ab, #4861AB);
  stop-opacity: 0;
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p3pobob2w {
  d: path("M10.684 11.543c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.03c.3-.026 1.148-.108 2.5-.718c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.387c-.376 1.032-1.005 2.246-2.38 3.262");
}

.p79aa0p9z {
  stop-color: var(--svg-color--3066bf, #3066BF);
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pul53bbta {
  cx: 12.854px;
  cy: 5.796px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.17px;
  ry: 0.086px;
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.pzos0ebxn {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  fill-rule: evenodd;
  d: path("M7.127 13.39c-.941-.283-1.295.01-1.388.12a.375.375 0 1 1-.57-.488c.328-.382 1.014-.699 2.174-.35a.375.375 0 1 1-.216.719");
}

.q-9x-2bzr {
  stop-color: var(--svg-color--ffd441, #FFD441);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qm6d4zl7k {
  d: path("M17.568 10.125a.37.37 0 0 1 .34-.416c.628-.037 1.541.013 2.147.494c.934.741 1.038 1.643 1 2.015c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.794-.235-2.546-1.589-3.593c-1.381-1.069-2.68-1.258-4.203-1.258h-.39c-.157 1.285.25 2.193.606 2.672");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0iiaeguw {
  stop-color: var(--svg-color--3168c8, #3168C8);
  stop-opacity: 0;
}

.rgxydrbdo {
  cx: 25.864px;
  cy: 14.61px;
  r: 1.293px;
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rvk092zcg {
  fill-rule: evenodd;
  d: path("M5.404 13.986c0 .001.02-.027.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.rw2hv3b3j {
  d: path("M24.458 21.11L2.29 28.798a.421.421 0 0 0 .138.82h3.948c.487 0 .968-.1 1.156-.157c5.922-2.016 17.406-5.86 18.176-6.2c.443-.195.511-.377.605-.627v-.001c.094-.25.047-1.031-.5-1.453c-.437-.338-1.105-.185-1.355-.07");
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.ry7h8ubvo {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  fill-rule: evenodd;
  d: path("M5.611 14.792a.375.375 0 0 1-.69-.295c.093-.216.328-.445.6-.605a1.76 1.76 0 0 1 1.119-.236a.375.375 0 1 1-.099.743a1 1 0 0 0-.641.14a1 1 0 0 0-.215.165a.5.5 0 0 0-.074.088");
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s34zpdb_t {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.405 5.111c-.091-.084-.35-.227-.723-.192");
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sqzx0mbth {
  cx: 16.003px;
  cy: 6.135px;
  r: 0.728px;
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t502ec3cr {
  stop-color: var(--svg-color--4861ab, #4861AB);
}

.t5lf5ccyt {
  stop-color: var(--svg-color--5391be, #5391BE);
  stop-opacity: 0;
}

.tgz_9qxcq {
  stop-color: var(--svg-color--57b4fd, #57B4FD);
}

.to9zfdmjz {
  stop-color: var(--svg-color--1154b9, #1154B9);
  stop-opacity: 0;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.u6gia-bos {
  stop-color: var(--svg-color--418dd5, #418DD5);
}

.uft06xbgm {
  d: path("m13.758 6.01l-.232.742a.235.235 0 0 0 .227.305h.343a.236.236 0 0 0 .227-.305l-.231-.742c-.05-.164-.282-.164-.334 0");
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.un_ukdoyr {
  d: path("m7.305 27.195l1.172-2.39l1.766.305v1.039z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vcu7f7bip {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.133c1.209-.02 3.782.828 4.104 4");
}

.vgauzicqp {
  stop-color: var(--svg-color--3168c8, #3168C8);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vt7w43b0h {
  stop-color: var(--svg-color--ffaf2e, #FFAF2E);
}

.w-kcyrvzt {
  cx: 16.003px;
  cy: 6.135px;
  r: 0.434px;
}

.w7mkidbxg {
  d: path("M6.126 14.735c.125-.138.398-.461.52-.606c.23 0 .91-.066 1.198-.098c-.39.715-.84 1.004-1.074 1.196c-.316.21-.605 0-.644-.067c-.047-.047-.157-.254 0-.425");
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wj9xfsbot {
  cx: 11.854px;
  cy: 6.135px;
  r: 0.728px;
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wr_om0nho {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  d: path("M6.126 14.735c.125-.138.398-.461.52-.606c.23 0 .91-.066 1.198-.098c-.39.715-.84 1.004-1.074 1.196c-.316.21-.605 0-.644-.067c-.047-.047-.157-.254 0-.425");
}

.wt5zlcbim {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m13.758 6.01l-.232.742a.235.235 0 0 0 .227.305h.343a.236.236 0 0 0 .227-.305l-.231-.742c-.05-.164-.282-.164-.334 0");
}

.x_57qtbhm {
  cx: 12.854px;
  cy: 5.796px;
  rx: 0.17px;
  ry: 0.086px;
}

.x-g1vtjtj {
  d: path("m16.027 3.309l.187.093a.86.86 0 0 1 .445.93L16.4 5.66c-.023.137-.113.229-.25.232c.016-.22.03-.574.036-.63c.02-.189-.01-.244-.184-.416a.55.55 0 0 1-.163-.373V4.1a.25.25 0 0 0-.187-.233a7.2 7.2 0 0 0-1.709-.186c-.842 0-1.427.117-1.708.186a.23.23 0 0 0-.187.233v.372c0 .14-.047.28-.164.373l-.07.07c-.094.07-.14.215-.14.331c.005.068.015.459.025.622a.276.276 0 0 1-.26-.232l-.257-1.327a.89.89 0 0 1 .468-.907c.443-.194.604-.488.96-.791a.86.86 0 0 1 .959-.14c.234.07.491.07.725 0a1.05 1.05 0 0 1 1.03.233l.35.35c.095.115.211.185.352.255");
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x30hr5izj {
  d: path("M11.7 5.868a13 13 0 0 1-.025-.628c0-.116.046-.256.14-.326l.07-.07a.46.46 0 0 0 .164-.372V4.1c0-.116.07-.21.187-.233c.281-.07.866-.186 1.708-.186c.843 0 1.428.117 1.708.186a.25.25 0 0 1 .188.233v.372c0 .14.07.28.163.373c.22.153.206.237.188.418c-.006.056-.024.521-.04.628l-.115 1.727c-.07.772-.677 1.31-1.4 1.31h-1.401c-.747 0-1.33-.538-1.4-1.31z");
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xdc35tb2f {
  fill-rule: evenodd;
  d: path("M13.149 5.173c-.314-.03-.516.093-.565.138a.206.206 0 1 1-.279-.303c.134-.123.45-.286.882-.246a.206.206 0 0 1-.038.41");
}

.xm16noihw {
  d: path("M15.223 5.967a.37.37 0 0 0-.101-.202l-.113.125l.05.1z");
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y60usm6nn {
  stop-color: var(--svg-color--46a5ef, #46A5EF);
}

.y8xbx2bgs {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M13.925 7.5a1.3 1.3 0 0 1-.604-.143c-.06-.03-.124.037-.087.091c.146.221.4.369.69.369s.545-.148.691-.369c.038-.056-.026-.122-.086-.091c-.175.091-.38.143-.604.143");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ypt34m9md {
  d: path("M20.68 13.696c.256-.588.373-1.22.399-1.461l2.047.023c.046.269-.04.584-.079.704c.088.322.037.686 0 .828c-.054.226-.178.713-.238.86c-.074.184-.183.246-.348.23a.4.4 0 0 1-.148-.042a.3.3 0 0 0-.23-.02a.43.43 0 0 1-.227.02a.43.43 0 0 1-.204-.113a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.005a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.071c-.085.007-.183.002-.235-.041c-.098-.082-.219-.176.031-.747");
}

.yrtrc6n_d {
  stop-color: var(--svg-color--54acfa, #54ACFA);
}

.yy8dgg-sf {
  d: path("M21.985 27.18L7.61 28.68c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.199 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.z7xjq9sfn {
  stop-color: var(--svg-color--ffaf2e, #FFAF2E);
  stop-opacity: 0;
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zn6vq8_5x {
  cx: 26.86px;
  cy: 10.574px;
  r: 0.914px;
}

.zrzxj2epv {
  stop-color: var(--svg-color--2b68b8, #2B68B8);
  stop-opacity: 0;
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.ztrk-1hpr {
  stop-color: var(--svg-color--ffbe42, #FFBE42);
}

.zuu8q1pyu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M14.848 5.711c.027.038-.03.083-.097.132c-.066.05-.114.084-.142.047s.003-.107.069-.156c.066-.05.142-.06.17-.023");
}

.zvqcq9hxr {
  stop-color: var(--svg-color--57b4fd, #57B4FD);
  stop-opacity: 0;
}

</style>
