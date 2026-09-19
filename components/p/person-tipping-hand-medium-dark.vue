<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ig0Khfo)" class="yrge1zfdi"/><path fill="url(#if1EhSd)" class="yrge1zfdi"/><path fill="url(#iOWGGLe)" class="yrge1zfdi"/><path fill="url(#iT8WEgb)" class="yrge1zfdi"/><rect fill="url(#i78rdVb)" class="k4wmpi0gu"/><rect fill="url(#izPS4ib)" class="k4wmpi0gu"/><path class="p1wg40bfi"/><path fill="url(#iO5YgVb)" class="qs25ae_rv"/><path fill="url(#isbdT0d)" class="qs25ae_rv"/><path fill="url(#iGlpArc)" class="qs25ae_rv"/><path clip-rule="evenodd" class="k3r_l1bdh"/><path fill="url(#i2qfD5T)" clip-rule="evenodd" class="er41dmlxr"/><path fill="url(#i5iGtse)" clip-rule="evenodd" class="er41dmlxr"/><path fill="url(#iOhYqse)" clip-rule="evenodd" class="er41dmlxr"/><path clip-rule="evenodd" class="pveniccms"/><path fill="url(#iqF5Aid)" clip-rule="evenodd" class="vo5goibhn"/><path fill="url(#iCntL5c)" clip-rule="evenodd" class="vo5goibhn"/><path fill="url(#im1MjxW)" clip-rule="evenodd" class="vo5goibhn"/><path clip-rule="evenodd" class="sssve8b6c"/><path fill="url(#igTwbhc)" clip-rule="evenodd" class="gdv0dxbqa"/><path fill="url(#iI7Je4c)" clip-rule="evenodd" class="gdv0dxbqa"/><path fill="url(#iP00pyW)" clip-rule="evenodd" class="gdv0dxbqa"/><g filter="url(#iqQZyFd)"><path class="gk9i0cwvh"/><path fill="url(#iGrhlhb)" class="um075_w0b"/><path fill="url(#iI5Nvce)" class="um075_w0b"/><path fill="url(#iLUrQ1b)" class="um075_w0b"/></g><path fill="url(#iD9sTee)" class="da_5dbbwr"/><path fill="url(#iM7ARBc)" class="da_5dbbwr"/><path fill="url(#itXylRc)" class="c5vvkgb5a"/><path fill="url(#iYqZ5kd)" class="c5vvkgb5a"/><path fill="url(#inwniNc)" class="c5vvkgb5a"/><g filter="url(#i0UYcid)"><path stroke="url(#iAsvfsd)" class="b3edk4bxu"/></g><path fill="url(#iQZwind)" class="ir36d_ouf"/><path fill="url(#iyLaCdd)" class="shg0r6liy"/><g filter="url(#iLze6Il)"><path fill="url(#iiZAGXM)" class="y3v42mvza"/><path fill="url(#i56Ltwl)" class="y3v42mvza"/></g><path fill="url(#iPjNLje)" class="y3v42mvza"/><path fill="url(#ihWz1Gd)" class="y3v42mvza"/><path fill="url(#i0iUBWb)" class="y3v42mvza"/><path fill="url(#iX3UaJk)" class="y3v42mvza"/><path fill="url(#izx57ad)" class="y3v42mvza"/><path fill="url(#ibqPooc)" class="y3v42mvza"/><path fill="url(#iFfjqLG)" class="y3v42mvza"/><g filter="url(#i84Xpyb)"><path class="bvsgufbbr"/></g><g filter="url(#iv1vNAb)"><path class="jh7ht6b9o"/><path fill="url(#iO5kirc)" class="vrpuehbbs"/><path fill="url(#i7bMpre)" class="vrpuehbbs"/><path fill="url(#in99Knd)" class="vrpuehbbs"/><path fill="url(#i8VvJHb)" class="vrpuehbbs"/><path fill="url(#im2O9ye)" class="vrpuehbbs"/></g><path fill="url(#izhPzJb)" class="vrpuehbbs"/><path fill="url(#i2IHahp)" class="vrpuehbbs"/><g filter="url(#iiVXtnd)"><path stroke="url(#im7P17e)" class="ctu2ctb1i"/></g><path fill="url(#i0KmWYd)" class="wimljq6wl"/><g filter="url(#i2aLDEc)"><path fill="url(#iB43j8n)" class="p1gb5yj8d"/><path fill="url(#idsHFBc)" class="p1gb5yj8d"/><path fill="url(#iPnfIac)" class="p1gb5yj8d"/><path fill="url(#i0Yjmmc)" class="p1gb5yj8d"/><path fill="url(#iBqx4ku)" class="p1gb5yj8d"/></g><g filter="url(#iiDU8Bd)"><path class="tyl3vccpr"/></g><g filter="url(#iw80ggb)"><path class="qmirnmbrv"/></g><g filter="url(#iKk9Wne)"><path class="azkay71ji"/><path fill="url(#iBvcOwd)" class="u11inbb9i"/><path fill="url(#iyCGQJv)" class="u11inbb9i"/></g><g filter="url(#i8vBa2B)"><path class="ig0l3rqdb"/><path fill="url(#iDYfp5d)" class="iaigq7fdd"/><path fill="url(#iZaAsse)" class="iaigq7fdd"/></g><path class="rc8u4jbpc"/><path fill="url(#ivvMiCc)" class="yf3f4niht"/><path class="eiir0cbjo"/><g filter="url(#iv3PnLc)"><path class="xo9z6lb1s"/><path fill="url(#iaZsT2b)" class="uyphap2rl"/></g><g filter="url(#iWBqYIb)"><path fill="url(#iBWVgeb)" class="ng9tk7v0v"/></g><path class="lqmi1bcsp"/><path fill="url(#ibXnotb)" class="gyszg9b3n"/><path class="bvkxpuvxj"/><g filter="url(#i4i0zDI)"><path fill="url(#iP9RZ6m)" class="ry9kx509t"/></g><g filter="url(#iGAU0od)"><ellipse transform="rotate(-27.914 9.814 11.931)" class="fbv1iabyv"/><ellipse fill="url(#iRsmpGd)" transform="rotate(-27.914 9.814 11.931)" class="miikeq9vc"/></g><path fill="url(#ipGUYjc)" class="heng61bvn"/><path fill="url(#iCPaq0P)" class="heng61bvn"/><path fill="url(#iZOy4Ub)" class="heng61bvn"/><path fill="url(#idyAjxb)" class="heng61bvn"/><path fill="url(#iGnwVOd)" class="hj_ltqb_k"/><path fill="url(#i0iR5yc)" class="hj_ltqb_k"/><g filter="url(#iV8nAOe)"><path fill="url(#ieDjCBX)" class="sje6kx_br"/></g><g filter="url(#ifXIZKb)"><path fill="url(#iWYHyCw)" class="cm8rqkbpd"/></g><g filter="url(#iLe6JNb)"><path class="eyz3uwbas"/></g><g filter="url(#iK7njXb)"><path class="yn7ys7lym"/></g><g filter="url(#iz4SRVd)"><path class="t1tfgbb7n"/></g><defs><radialGradient id="if1EhSd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.43883 -5.70657 4.58851 -5.98138 20.001 29.347)" gradientUnits="userSpaceOnUse"><stop class="ivi3fdawu"/><stop offset="1" class="xxzm8qbti"/></radialGradient><radialGradient id="iOWGGLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.33798 -7.92939 0 12.555 18.39)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="yitnujsmh"/><stop offset="1" class="p9u6z5b-m"/></radialGradient><radialGradient id="iT8WEgb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.60995 -7.279 2.80725 -1.7779 22.375 29.936)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="jc9tt1bnq"/><stop offset="1" class="vq1hgac7r"/></radialGradient><radialGradient id="i78rdVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.97059 3.60967 -4.23023 2.30936 12.625 20.197)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="qfq-4njfa"/><stop offset=".826" class="iwwy4nazl"/></radialGradient><radialGradient id="iO5YgVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14487 1.17029 -.21646 -.21176 24.458 12.948)" gradientUnits="userSpaceOnUse"><stop class="o3zst353r"/><stop offset="1" class="yk_3_lmdp"/></radialGradient><radialGradient id="isbdT0d" cx="0" cy="0" r="1" gradientTransform="rotate(-70.927 22.48 -9.019)scale(3.10812 1.58159)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="ax61zhbvm"/><stop offset="1" class="tw5b7-bqr"/></radialGradient><radialGradient id="iGlpArc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10937 .79688 -1.21512 -.16677 24.357 14.506)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="ns2xpk6fj"/><stop offset="1" class="y_oq21bme"/></radialGradient><radialGradient id="i2qfD5T" cx="0" cy="0" r="1" gradientTransform="matrix(-.69262 .16923 -.21445 -.87773 30.16 14.012)" gradientUnits="userSpaceOnUse"><stop class="r-1zse6uu"/><stop offset="1" class="ib8qs4a_l"/></radialGradient><radialGradient id="iOhYqse" cx="0" cy="0" r="1" gradientTransform="rotate(82.145 6.174 22.591)scale(.37067 3.64537)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="hcgd5kb7l"/><stop offset="1" class="cf_38xbde"/></radialGradient><radialGradient id="iqF5Aid" cx="0" cy="0" r="1" gradientTransform="matrix(-.68924 .16508 -.20552 -.85808 30.738 14.323)" gradientUnits="userSpaceOnUse"><stop class="r-1zse6uu"/><stop offset="1" class="ib8qs4a_l"/></radialGradient><radialGradient id="im1MjxW" cx="0" cy="0" r="1" gradientTransform="matrix(.05214 .36215 -3.63059 .52268 28.297 13.656)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="hcgd5kb7l"/><stop offset="1" class="cf_38xbde"/></radialGradient><radialGradient id="igTwbhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.69149 .15913 -.19118 -.83072 30.457 14.785)" gradientUnits="userSpaceOnUse"><stop class="r-1zse6uu"/><stop offset="1" class="ib8qs4a_l"/></radialGradient><radialGradient id="iP00pyW" cx="0" cy="0" r="1" gradientTransform="matrix(.0523 .34914 -3.63628 .54474 28.007 14.14)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="hcgd5kb7l"/><stop offset="1" class="cf_38xbde"/></radialGradient><radialGradient id="iGrhlhb" cx="0" cy="0" r="1" gradientTransform="rotate(173.822 14.448 8.597)scale(.96972 .53174)" gradientUnits="userSpaceOnUse"><stop class="k8893l_5s"/><stop offset="1" class="dagxnpbxc"/></radialGradient><radialGradient id="iI5Nvce" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 5.188 23.664)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="tc83oubxb"/><stop offset="1" class="jc2cbvyjw"/></radialGradient><radialGradient id="iLUrQ1b" cx="0" cy="0" r="1" gradientTransform="matrix(.92109 -.74564 1.75363 2.16625 22.325 16.747)" gradientUnits="userSpaceOnUse"><stop class="mcx49tb9t"/><stop offset="1" class="evh57dbtz"/></radialGradient><radialGradient id="iD9sTee" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.17059 -4.07047 0 24.626 17.236)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="fs0lcjope"/><stop offset="1" class="tlllf-zgd"/><stop offset="1" class="omr_ktb6b"/></radialGradient><radialGradient id="iYqZ5kd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.75 -3.6875 0 26.189 17.564)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="tu7zelskj"/><stop offset="1" class="h4j2h-grr"/></radialGradient><radialGradient id="iQZwind" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -.897 20.77)scale(2.71243 3.22216)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iyLaCdd" cx="0" cy="0" r="1" gradientTransform="matrix(1.85934 .58437 -1.8028 5.7362 5.277 15.009)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iiZAGXM" cx="0" cy="0" r="1" gradientTransform="matrix(-6.58356 0 0 -11.6463 16.44 13.206)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="i56Ltwl" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1952 3.63057 -2.99734 -1.81232 15.96 6.936)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="ihWz1Gd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.8624 9.28021 0 12.881 21.253)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="i0iUBWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44615 1.78961 0 15.986 11.552)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iX3UaJk" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 10.83 .784)scale(1.37806 1.49965)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="izx57ad" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.386 7.497)scale(10.7205 27.3855)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="ibqPooc" cx="0" cy="0" r="1" gradientTransform="rotate(-40.741 15.323 -.977)scale(5.62755 1.66228)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iFfjqLG" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 5.604 13.819)scale(3.15894 1.26276)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="i7bMpre" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3074 -.96613 0 13.491 14.92)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="i8VvJHb" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 5.268 8.59)scale(2.10736 3.3867)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="i2IHahp" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61475 1.54088 -2.22387 -2.33048 13.448 13.838)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="i0KmWYd" cx="0" cy="0" r="1" gradientTransform="rotate(-26.18 44.35 -17.533)scale(3.06194 12.319)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="idsHFBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.4093 11.1506 0 6.318 9.563)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iPnfIac" cx="0" cy="0" r="1" gradientTransform="matrix(.14362 -3.16411 5.60618 .25446 19.025 11.213)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i0Yjmmc" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 9.533 -1.051)scale(3.55544 2.60987)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iBqx4ku" cx="0" cy="0" r="1" gradientTransform="matrix(.84587 1.50895 -3.49401 1.95863 11.764 1.304)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iBvcOwd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.77193 0 0 -1.02877 13.223 4.15)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iyCGQJv" cx="0" cy="0" r="1" gradientTransform="matrix(4.05272 -6.41682 7.10917 4.49 6.065 9.114)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iDYfp5d" cx="0" cy="0" r="1" gradientTransform="matrix(3.37338 -3.214 5.88404 6.1758 16.22 8.952)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iZaAsse" cx="0" cy="0" r="1" gradientTransform="matrix(4.09056 .47814 -.20019 1.71264 15.106 7.094)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ivvMiCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02171 -1.62515 0 15.652 12.052)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iaZsT2b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.66 2.316)scale(.47639 .65587)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibXnotb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02177 -1.62523 0 10.156 12.052)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iRsmpGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00974 -.62221 .74792 -.01171 9.795 12.328)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCPaq0P" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.402 18.377)scale(2.93381 2.79908)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iZOy4Ub" cx="0" cy="0" r="1" gradientTransform="matrix(.99207 -1.36146 1.14118 .83156 19.173 12.755)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="idyAjxb" cx="0" cy="0" r="1" gradientTransform="matrix(.73922 -1.95249 2.60878 .9877 19.317 12.973)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="i0iR5yc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08828 0 0 -2.33186 6.714 12.877)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="ieDjCBX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15414 .19811 -.20313 -1.18336 6.715 12.88)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><linearGradient id="ig0Khfo" x1="12.904" x2="12.904" y1="29.936" y2="24.417" gradientUnits="userSpaceOnUse"><stop class="qg8x1vbhh"/><stop offset="1" class="ijvl3aczp"/><stop offset="1" class="ijvl3aczp"/></linearGradient><linearGradient id="izPS4ib" x1="12.873" x2="12.873" y1="20.49" y2="21.724" gradientUnits="userSpaceOnUse"><stop class="bcwl5-b2w"/><stop offset="1" class="epu517bvh"/></linearGradient><linearGradient id="i5iGtse" x1="28.163" x2="28.03" y1="15.559" y2="14.303" gradientUnits="userSpaceOnUse"><stop offset=".217" class="rnkxh8b0f"/><stop offset="1" class="vsq2kybkm"/></linearGradient><linearGradient id="iCntL5c" x1="28.75" x2="28.624" y1="15.833" y2="14.607" gradientUnits="userSpaceOnUse"><stop offset=".217" class="rnkxh8b0f"/><stop offset="1" class="vsq2kybkm"/></linearGradient><linearGradient id="iI7Je4c" x1="28.463" x2="28.345" y1="16.239" y2="15.056" gradientUnits="userSpaceOnUse"><stop offset=".217" class="rnkxh8b0f"/><stop offset="1" class="vsq2kybkm"/></linearGradient><linearGradient id="iM7ARBc" x1="24.005" x2="24.005" y1="18.552" y2="17.928" gradientUnits="userSpaceOnUse"><stop offset=".316" class="f3g2sacre"/><stop offset="1" class="wyf_7nbxp"/></linearGradient><linearGradient id="itXylRc" x1="24.876" x2="24.876" y1="19.252" y2="38.564" gradientUnits="userSpaceOnUse"><stop class="xx_iqybrp"/><stop offset=".621" class="t57nv_-5z"/></linearGradient><linearGradient id="inwniNc" x1="23.834" x2="23.834" y1="18.092" y2="19.127" gradientUnits="userSpaceOnUse"><stop offset=".366" class="tu7zelskj"/><stop offset="1" class="h4j2h-grr"/></linearGradient><linearGradient id="iAsvfsd" x1="28.757" x2="23.936" y1="15.649" y2="16.156" gradientUnits="userSpaceOnUse"><stop class="qrm8h702x"/><stop offset="1" class="g7kay-2kl"/></linearGradient><linearGradient id="iPjNLje" x1="19.398" x2="16.214" y1="15.328" y2="15.328" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iO5kirc" x1="13.96" x2="12.904" y1="14.056" y2="14.099" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="in99Knd" x1="12.904" x2="12.904" y1="15.49" y2="14.905" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="im2O9ye" x1="12.904" x2="12.904" y1="12.084" y2="12.772" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="izhPzJb" x1="13.427" x2="13.427" y1="15.664" y2="15.421" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="im7P17e" x1="11.39" x2="11.791" y1="17.468" y2="16.418" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iB43j8n" x1="21.533" x2="6.909" y1="6.075" y2="6.075" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iBWVgeb" x1="16.631" x2="16.236" y1="12.12" y2="12.363" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iP9RZ6m" x1="11.093" x2="10.698" y1="12.12" y2="12.363" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipGUYjc" x1="21.009" x2="19.49" y1="12.154" y2="14.894" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iGnwVOd" x1="5.537" x2="7.374" y1="13.04" y2="12.88" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iWYHyCw" x1="19.725" x2="19.725" y1="11.673" y2="14.07" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><filter id="iqQZyFd" width="7.879" height="3.847" x="21.78" y="13.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.286275 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3792"/></filter><filter id="i0UYcid" width="5.722" height="1.374" x="23.756" y="15.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".125"/></filter><filter id="iLze6Il" width="13.871" height="15.742" x="6.528" y="5.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3792"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3792" result="effect2_innerShadow_4002_3792"/></filter><filter id="i84Xpyb" width="4.2" height="5.652" x="10.625" y="11.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".5"/></filter><filter id="iv1vNAb" width="2.764" height="4.052" x="11.522" y="11.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".1"/></filter><filter id="iiVXtnd" width="4.553" height="1.851" x="10.627" y="16.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".05"/></filter><filter id="i2aLDEc" width="16.211" height="10.394" x="4.798" y="1.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3792"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3792" result="effect2_innerShadow_4002_3792"/></filter><filter id="iiDU8Bd" width="2.919" height="1.447" x="14.905" y="8.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3792"/></filter><filter id="iw80ggb" width="2.919" height="1.429" x="8.286" y="8.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3792"/></filter><filter id="iKk9Wne" width="8.662" height="7.916" x="5.061" y="2.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3792"/><feGaussianBlur result="effect2_foregroundBlur_4002_3792" stdDeviation=".25"/></filter><filter id="i8vBa2B" width="8.392" height="7.637" x="12.455" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".25"/></filter><filter id="iv3PnLc" width=".939" height=".825" x="14.753" y="11.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".05"/></filter><filter id="iWBqYIb" width="1.019" height="1.047" x="15.837" y="11.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".1"/></filter><filter id="i4i0zDI" width="1.138" height="1.206" x="10.242" y="11.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".1"/></filter><filter id="iGAU0od" width="1.098" height=".835" x="9.265" y="11.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".05"/></filter><filter id="iV8nAOe" width="1.544" height="2.867" x="5.311" y="11.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".125"/></filter><filter id="ifXIZKb" width="2.192" height="3.397" x="18.629" y="11.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".25"/></filter><filter id="iLe6JNb" width="2.834" height="1.267" x="8.281" y="8.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".125"/></filter><filter id="iK7njXb" width="2.834" height="1.267" x="14.929" y="8.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".125"/></filter><filter id="iz4SRVd" width="6.742" height="3.896" x="13.956" y="3.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3792" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-tipping-hand-medium-dark" /></template>
<style>
.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ax61zhbvm {
  stop-color: var(--svg-color--6c4a3e, #6C4A3E);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.azkay71ji {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("M13.197 6.134a3 3 0 0 1-.084-.173a.84.84 0 0 0-.774-.526h-1.604c-2.324 0-4.207 1.904-4.207 4.255v.347C6.099 9.71 5.56 9.023 5.56 7.91c0-1.35.984-2.032 1.612-2.467c.178-.123.326-.226.417-.32l.125-.131c.44-.467 1.225-1.299 2.594-1.662a7 7 0 0 1 2.11-.2c.471.024.804.432.804.905v2.08z");
}

.b3edk4bxu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M24.13 16.273c.85-.058 3.032-.264 4.973-.624");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bcwl5-b2w {
  stop-color: var(--svg-color--713542, #713542);
}

.bvkxpuvxj {
  fill: var(--svg-color--000, #000);
  d: path("M10.797 12.575a.64.64 0 0 0-.644-.644a.64.64 0 0 0-.572.94h1.14a.64.64 0 0 0 .076-.296");
}

.bvsgufbbr {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m12.398 12.552l-.744 2.315c-.127.476.178.953.61.953h.922c.432 0 .737-.484.61-.953l-.623-2.315c-.133-.513-.635-.513-.775 0");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c5vvkgb5a {
  d: path("M20.638 18.892a.8.8 0 0 1 .8-.8h4.79a.8.8 0 0 1 .8.8v11.044h-6.39z");
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cf_38xbde {
  stop-color: var(--svg-color--8e6f62, #8E6F62);
  stop-opacity: 0;
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm8rqkbpd {
  d: path("M19.129 14.07q.073-1.2.139-2.397a1.203 1.203 0 0 1-.14 2.397");
}

.ctu2ctb1i {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M11.194 16.373a3.7 3.7 0 0 0 1.71.405c.634 0 1.216-.147 1.71-.405a.27.27 0 0 1 .319.052a.25.25 0 0 1 .027.32l-.062-.042a2.38 2.38 0 0 1-1.994 1.065a2.38 2.38 0 0 1-1.994-1.065zm0 0a.27.27 0 0 0-.32.055a.25.25 0 0 0-.026.317z");
}

.da_5dbbwr {
  d: path("M21.537 17.397a.25.25 0 0 1 .25-.25h4.094a.25.25 0 0 1 .25.25v1.64h-4.594z");
}

.dagxnpbxc {
  stop-color: var(--svg-color--99786f, #99786F);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.eiir0cbjo {
  fill: var(--svg-color--000, #000);
  d: path("M15.01 12.575c0-.358.287-.644.644-.644a.64.64 0 0 1 .573.94h-1.14a.6.6 0 0 1-.076-.296");
}

.epu517bvh {
  stop-color: var(--svg-color--713542, #713542);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.er41dmlxr {
  fill-rule: evenodd;
  d: path("M30.147 14.03a.85.85 0 0 1-.69.985c-.147.026-.337.066-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 1 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.083.715-.142a.85.85 0 0 1 .985.69");
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.evh57dbtz {
  stop-color: var(--svg-color--825b55, #825B55);
  stop-opacity: 0;
}

.eyz3uwbas {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.656 9.668c.324-.232 1.13-.64 2.084-.48");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f3g2sacre {
  stop-color: var(--svg-color--b33f0e, #B33F0E);
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fbv1iabyv {
  cx: 9.814px;
  cy: 11.931px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.491px;
  ry: 0.248px;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fs0lcjope {
  stop-color: var(--svg-color--f26f40, #F26F40);
}

.ft5dv1b6b {
  fill: none;
}

.g7kay-2kl {
  stop-color: var(--svg-color--9b7b71, #9B7B71);
  stop-opacity: 0;
}

.gdv0dxbqa {
  fill-rule: evenodd;
  d: path("M30.454 14.916a.85.85 0 0 1-.773.921a28 28 0 0 0-1.26.162l-.03.004c-.525.075-1.133.16-1.787.231a.85.85 0 0 1-.182-1.69c.622-.067 1.205-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.gk9i0cwvh {
  fill: var(--svg-color--7d5447, #7D5447);
  d: path("M26.092 13.866a53 53 0 0 1-1.827.173c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.857-.099 1.166-.196c.242-.076.516-.215.975-.302c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.gyszg9b3n {
  d: path("M10.154 11.451a1.124 1.124 0 0 0-1.084 1.42h2.172q.039-.144.04-.296a1.13 1.13 0 0 0-1.129-1.124");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h4j2h-grr {
  stop-color: var(--svg-color--fa9319, #FA9319);
  stop-opacity: 0;
}

.hcgd5kb7l {
  stop-color: var(--svg-color--8e6f62, #8E6F62);
}

.heng61bvn {
  d: path("M19.102 14.894q.126-2.009.233-4.019a2.027 2.027 0 0 1-.233 4.02");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj_ltqb_k {
  d: path("M6.552 10.859a2.044 2.044 0 0 0-1.754 2.012c0 1.082.848 1.966 1.916 2.024a99 99 0 0 1-.162-4.036");
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iaigq7fdd {
  d: path("m19.468 10.248l-.037-.795c-.013-.962-.807-1.755-1.77-1.795h-1.763a3.05 3.05 0 0 1-2.674-1.587s-.152-.35-.248-.907c-.171-.989.745-1.713 1.73-1.523c1.282.247 2.838.71 3.99 1.462c2.197 1.433 1.929 3.928.772 5.145");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ib8qs4a_l {
  stop-color: var(--svg-color--9b7b70, #9B7B70);
  stop-opacity: 0;
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ig0l3rqdb {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m19.468 10.248l-.037-.795c-.013-.962-.807-1.755-1.77-1.795h-1.763a3.05 3.05 0 0 1-2.674-1.587s-.152-.35-.248-.907c-.171-.989.745-1.713 1.73-1.523c1.282.247 2.838.71 3.99 1.462c2.197 1.433 1.929 3.928.772 5.145");
}

.ijvl3aczp {
  stop-color: var(--svg-color--df6b20, #DF6B20);
}

.ir36d_ouf {
  d: path("M19.026 14.78a2.07 2.07 0 0 0 1.139-.389v1.173c0 1.124-.67 2.126-1.689 2.542q.324-.687.436-1.486z");
}

.ivi3fdawu {
  stop-color: var(--svg-color--f17040, #F17040);
}

.iwwy4nazl {
  stop-color: var(--svg-color--824f44, #824F44);
}

.jc2cbvyjw {
  stop-color: var(--svg-color--886658, #886658);
  stop-opacity: 0;
}

.jc9tt1bnq {
  stop-color: var(--svg-color--a62807, #A62807);
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jh7ht6b9o {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m12.422 12.306l-.669 2.315c-.136.476.191.952.656.952h.99c.464 0 .792-.483.656-.952l-.67-2.315c-.143-.513-.812-.513-.963 0");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k3r_l1bdh {
  fill: var(--svg-color--7d5447, #7D5447);
  fill-rule: evenodd;
  d: path("M30.147 14.03a.85.85 0 0 1-.69.985c-.147.026-.337.066-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 1 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.083.715-.142a.85.85 0 0 1 .985.69");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k4wmpi0gu {
  width: 4.898px;
  height: 6.68px;
  x: 10.466px;
  y: 16.858px;
  rx: 2.449px;
}

.k8893l_5s {
  stop-color: var(--svg-color--99786f, #99786F);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lqmi1bcsp {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.893 11.109c-.823 0-1.517.567-1.706 1.333c-.057.22.112.43.337.43h2.81a.29.29 0 0 0 .286-.343a1.764 1.764 0 0 0-1.727-1.42");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcx49tb9t {
  stop-color: var(--svg-color--825b55, #825B55);
}

.miikeq9vc {
  cx: 9.814px;
  cy: 11.931px;
  rx: 0.491px;
  ry: 0.248px;
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.ng9tk7v0v {
  d: path("M16.655 12.427a1.06 1.06 0 0 0-.291-.583l-.327.36l.147.287z");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.ns2xpk6fj {
  stop-color: var(--svg-color--917568, #917568);
}

.o3zst353r {
  stop-color: var(--svg-color--927568, #927568);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omr_ktb6b {
  stop-color: var(--svg-color--bf4617, #BF4617);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p1gb5yj8d {
  d: path("M19.018 4.84a2.92 2.92 0 0 1 1.596 1.324a2.98 2.98 0 0 1-.134 3.181c-.22.325-.34.71-.34 1.101v1.497a2.2 2.2 0 0 0-.84-.338l.098-2.023a1.825 1.825 0 0 0-1.736-1.804h-1.763a3.05 3.05 0 0 1-2.786-1.817a.84.84 0 0 0-.774-.526h-1.603c-2.325 0-4.208 1.904-4.208 4.255l.038 1.936c-.32.047-.654.154-.907.332v-1.511c0-.392-.12-.777-.34-1.102a3.01 3.01 0 0 1-.18-3.08a2.95 2.95 0 0 1 1.636-1.418a3.38 3.38 0 0 0 1.743-1.398a2.93 2.93 0 0 1 3.64-1.148a1.88 1.88 0 0 0 1.503 0a3 3 0 0 1 1.149-.237a2.93 2.93 0 0 1 2.505 1.425a3.18 3.18 0 0 0 1.703 1.351");
}

.p1wg40bfi {
  fill: var(--svg-color--814f54, #814F54);
  d: path("M21.78 15.638h4.015v2.016H21.78z");
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p9u6z5b-m {
  stop-color: var(--svg-color--a25018, #A25018);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pveniccms {
  fill: var(--svg-color--7d5447, #7D5447);
  fill-rule: evenodd;
  d: path("M30.725 14.359a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.125-1.626.305-2.733.41a.85.85 0 1 1-.16-1.692a27 27 0 0 0 2.552-.384l.459-.084a.85.85 0 0 1 .984.69");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.qfq-4njfa {
  stop-color: var(--svg-color--71384a, #71384A);
}

.qg8x1vbhh {
  stop-color: var(--svg-color--e4532d, #E4532D);
}

.qmirnmbrv {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M8.608 9.316a3.5 3.5 0 0 1 2.19-.453a.35.35 0 1 1-.085.694a2.8 2.8 0 0 0-1.746.358a2 2 0 0 0-.115.076l-.004.002a.35.35 0 0 1-.428-.552z");
}

.qrm8h702x {
  stop-color: var(--svg-color--9b7b71, #9B7B71);
}

.qs25ae_rv {
  d: path("M22.552 13.725c-.554.649-.74 1.417-.761 1.758l1.847-.102l.887-1.183c.29-.383.54-1.02-.035-1.442c-.466-.342-.945-.066-1.102.106c-.062.057-.248.244-.836.863");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r-1zse6uu {
  stop-color: var(--svg-color--9b7b70, #9B7B70);
}

.rc8u4jbpc {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.915 11.109a1.76 1.76 0 0 1 1.706 1.333a.345.345 0 0 1-.337.43h-2.81a.29.29 0 0 1-.286-.343a1.76 1.76 0 0 1 1.727-1.42");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rnkxh8b0f {
  stop-color: var(--svg-color--7d4b55, #7D4B55);
}

.ry9kx509t {
  d: path("M11.18 12.443c0-.363-.295-.605-.375-.679l-.363.352l.223.455z");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.shg0r6liy {
  d: path("M6.782 14.78a2.07 2.07 0 0 1-1.14-.389v1.173c0 1.124.67 2.126 1.69 2.542a5.2 5.2 0 0 1-.436-1.486z");
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sje6kx_br {
  d: path("M6.5 11.696a1.204 1.204 0 0 0 .105 2.367q-.067-1.184-.105-2.367");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.sssve8b6c {
  fill: var(--svg-color--7d5447, #7D5447);
  fill-rule: evenodd;
  d: path("M30.454 14.916a.85.85 0 0 1-.773.921a28 28 0 0 0-1.26.162l-.03.004c-.525.075-1.133.16-1.787.231a.85.85 0 0 1-.182-1.69c.622-.067 1.205-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t1tfgbb7n {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M18.184 6.078h-2.62a.61.61 0 1 1 .097-1.21c.68.108 1.583.259 2.187.409c1.367.338 1.745 1.004 1.85 1.479a1.9 1.9 0 0 0-1.514-.678");
}

.t57nv_-5z {
  stop-color: var(--svg-color--d36028, #D36028);
}

.tc83oubxb {
  stop-color: var(--svg-color--886658, #886658);
}

.tlllf-zgd {
  stop-color: var(--svg-color--bb5028, #BB5028);
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tu7zelskj {
  stop-color: var(--svg-color--fa9319, #FA9319);
}

.tw5b7-bqr {
  stop-color: var(--svg-color--6c4a3e, #6C4A3E);
}

.tyl3vccpr {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M17.605 9.453c-.22-.192-.477-.395-.866-.518c-.383-.12-.863-.153-1.527-.072a.35.35 0 1 0 .085.694c.606-.074.977-.036 1.232.044c.25.079.419.206.617.379a.35.35 0 1 0 .459-.527");
}

.u11inbb9i {
  d: path("M13.197 6.134a3 3 0 0 1-.084-.173a.84.84 0 0 0-.774-.526h-1.604c-2.324 0-4.207 1.904-4.207 4.255v.347C6.099 9.71 5.56 9.023 5.56 7.91c0-1.35.984-2.032 1.612-2.467c.178-.123.326-.226.417-.32l.125-.131c.44-.467 1.225-1.299 2.594-1.662a7 7 0 0 1 2.11-.2c.471.024.804.432.804.905v2.08z");
}

.um075_w0b {
  d: path("M26.092 13.866a53 53 0 0 1-1.827.173c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.857-.099 1.166-.196c.242-.076.516-.215.975-.302c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uyphap2rl {
  d: path("M15.572 11.689c.08.107-.087.237-.278.38c-.19.142-.331.242-.411.135s.009-.31.2-.452c.19-.142.409-.17.489-.063");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vo5goibhn {
  fill-rule: evenodd;
  d: path("M30.725 14.359a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.125-1.626.305-2.733.41a.85.85 0 1 1-.16-1.692a27 27 0 0 0 2.552-.384l.459-.084a.85.85 0 0 1 .984.69");
}

.vq1hgac7r {
  stop-color: var(--svg-color--a62807, #A62807);
  stop-opacity: 0;
}

.vrpuehbbs {
  d: path("m12.422 12.306l-.669 2.315c-.136.476.191.952.656.952h.99c.464 0 .792-.483.656-.952l-.67-2.315c-.143-.513-.812-.513-.963 0");
}

.vsq2kybkm {
  stop-color: var(--svg-color--7d4b55, #7D4B55);
  stop-opacity: 0;
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wimljq6wl {
  d: path("M12.904 16.853c-.64 0-1.24-.15-1.745-.413c-.173-.088-.358.106-.25.263a2.38 2.38 0 0 0 1.995 1.065c.837 0 1.572-.426 1.994-1.065c.108-.163-.077-.35-.25-.263a3.76 3.76 0 0 1-1.744.413");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wyf_7nbxp {
  stop-color: var(--svg-color--b33f0e, #B33F0E);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xo9z6lb1s {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.572 11.689c.08.107-.087.237-.278.38c-.19.142-.331.242-.411.135s.009-.31.2-.452c.19-.142.409-.17.489-.063");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xx_iqybrp {
  stop-color: var(--svg-color--e88222, #E88222);
}

.xxzm8qbti {
  stop-color: var(--svg-color--f17040, #F17040);
  stop-opacity: 0;
}

.y_oq21bme {
  stop-color: var(--svg-color--917568, #917568);
  stop-opacity: 0;
}

.y3v42mvza {
  d: path("M6.828 16.688a4.93 4.93 0 0 0 4.893 4.289h2.376a4.93 4.93 0 0 0 4.893-4.29c.149-2.372.298-4.734.408-7.105a1.825 1.825 0 0 0-1.736-1.804h-1.763a3.05 3.05 0 0 1-2.786-1.817a.84.84 0 0 0-.774-.526h-1.604c-2.324 0-4.207 1.904-4.207 4.255c0 2.343.146 4.649.3 6.998");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.yf3f4niht {
  d: path("M15.654 11.451a1.124 1.124 0 0 1 1.083 1.42h-2.17a1.128 1.128 0 0 1 1.088-1.42");
}

.yitnujsmh {
  stop-color: var(--svg-color--a25018, #A25018);
}

.yk_3_lmdp {
  stop-color: var(--svg-color--7c5a4c, #7C5A4C);
}

.yn7ys7lym {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.388 9.61c-.323-.232-1.13-.64-2.084-.48");
}

.yrge1zfdi {
  d: path("M12.904 19.885c-5.523 0-10 4.477-10 10v.05h20v-.05c0-5.523-4.477-10-10-10");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
