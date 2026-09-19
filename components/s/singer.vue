<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ieDERxb)"><path class="ao-rt-uhf"/></g><g filter="url(#iBaxQ3b)"><path class="wf31j_m3i"/><path fill="url(#iwT8Yhb)" class="ma7bgbcul"/></g><path fill="url(#iaymqjc)" class="z3tmracpy"/><path fill="url(#i48vhyb)" class="z3tmracpy"/><path fill="url(#iOGzMed)" class="alpke6bgr"/><path fill="url(#iRt9GPQ)" class="alpke6bgr"/><path fill="url(#iH9O5Pd)" class="p93e4gk6d"/><path fill="url(#iFLNIZd)" class="p93e4gk6d"/><path fill="url(#imwwx5T)" class="p93e4gk6d"/><path fill="url(#iPuTYtc)" class="p93e4gk6d"/><path fill="url(#iQJtd8b)" class="fcs7flbwg"/><path fill="url(#iC7Fble)" class="fcs7flbwg"/><path fill="url(#i4bwE3b)" class="fcs7flbwg"/><path fill="url(#iWJpn9d)" class="fcs7flbwg"/><path fill="url(#inHqRab)" class="fcs7flbwg"/><path fill="url(#iFGyd5M)" class="yr-wd3bdy"/><path fill="url(#i0h8Fjc)" class="b9sj__brp"/><path fill="url(#iIAd31b)" class="tbefs5d0d"/><path fill="url(#ip0KKfe)" class="nkmjyccuf"/><path fill="url(#igS3Cie)" class="nkmjyccuf"/><path fill="url(#iYBqpTd)" class="nkmjyccuf"/><path fill="url(#iiRNY4A)" class="kn6rpk-yp"/><path fill="url(#iz6zgjd)" class="kn6rpk-yp"/><path fill="url(#iW5mQYc)" class="w5bhpkbss"/><path fill="url(#iPxsfwb)" class="w5bhpkbss"/><path fill="url(#iqGB4qd)" class="w5bhpkbss"/><path fill="url(#iCQupBH)" class="w5bhpkbss"/><g filter="url(#i7n4blN)"><path fill="url(#i5zDRrc)" class="agjxsvb1m"/><path fill="url(#i0ew3bK)" class="agjxsvb1m"/><path fill="url(#ifOWZ6b)" class="agjxsvb1m"/></g><path fill="url(#iVO4H0A)" class="go0ufubgn"/><path fill="url(#ii9vjSc)" class="go0ufubgn"/><path fill="url(#iUD0Edi)" class="go0ufubgn"/><g filter="url(#if5V3De)"><path fill="url(#iGQfR7b)" class="hf_dmgbtw"/></g><g filter="url(#i4k36Td)"><circle fill="url(#i9oaRQd)" class="y_ok4rf-q"/></g><path fill="url(#i9W3Nte)" class="fnu1q5x6k"/><path fill="url(#iGuRmPn)" class="fnu1q5x6k"/><path fill="url(#iYdDMgT)" class="uwfkylv_u"/><path fill="url(#iRgX2DL)" class="uwfkylv_u"/><g filter="url(#inEMMUP)"><path fill="url(#i1OI3Vc)" class="guwvw8byr"/></g><path fill="url(#imfRcQc)" class="guwvw8byr"/><path fill="url(#iNPAAAe)" class="guwvw8byr"/><path fill="url(#i6UTk0c)" class="guwvw8byr"/><path fill="url(#inoCnsb)" class="guwvw8byr"/><g filter="url(#iAddkcb)"><path class="v7wp60bcw"/></g><g filter="url(#i6qtPod)"><path fill="url(#iDP99hb)" class="py8_5dbcb"/><path fill="url(#iLFDcMd)" class="py8_5dbcb"/><path fill="url(#ibgKE4b)" class="py8_5dbcb"/><path fill="url(#iotmj1b)" class="py8_5dbcb"/></g><path fill="url(#iKHk0zb)" class="cxf3v0baf"/><path fill="url(#itQ8sLe)" class="cxf3v0baf"/><g filter="url(#iavKo9b)"><path stroke="url(#iII0KEm)" class="txh8aq1mn"/></g><path fill="url(#i93miie)" class="ugmo_530l"/><g filter="url(#i2pdaOM)"><path fill="url(#iFsrUSb)" class="ovjkybbnn"/><path fill="url(#idGeJrb)" class="ovjkybbnn"/><path fill="url(#iBEhvZb)" class="ovjkybbnn"/><path fill="url(#i7aK7gd)" class="ovjkybbnn"/><path fill="url(#ixaJMGb)" class="ovjkybbnn"/></g><g filter="url(#iVRypYd)"><path class="wc4slvbug"/></g><g filter="url(#iNp2Vvb)"><path class="dpjgnpdex"/></g><g filter="url(#iZ1rc7b)"><path fill="url(#iMnWgeb)" class="ldm_1v-5j"/><path fill="url(#iO9Vhhc)" class="ldm_1v-5j"/></g><g filter="url(#iD7xbAc)"><path fill="url(#iHq1usB)" class="f71l5lp1h"/><path fill="url(#i9V2Lsd)" class="f71l5lp1h"/><path fill="url(#ijtqUEg)" class="f71l5lp1h"/><path fill="url(#iz8hOQQ)" class="f71l5lp1h"/><path fill="url(#iEI7bGe)" class="f71l5lp1h"/></g><path class="hy1lvcb8j"/><path fill="url(#iGzCfld)" class="bh30q1gbu"/><path class="wtoaknbgg"/><g filter="url(#i6RiTNd)"><path class="d0i7vecxv"/><path fill="url(#izlRnne)" class="omm106fle"/></g><g filter="url(#iRaMOsW)"><path fill="url(#isAwFYG)" class="h__y94wtt"/></g><path class="jiu__0bgd"/><path fill="url(#iyptItb)" class="gjjsvbmnk"/><path class="qovgumx7t"/><g filter="url(#idborLj)"><path fill="url(#i7eAYpD)" class="l2pb7sqlg"/></g><g filter="url(#iq1onPc)"><ellipse transform="rotate(-27.914 12.715 11.305)" class="nig06wb4n"/><ellipse fill="url(#i4AZBjb)" transform="rotate(-27.914 12.715 11.305)" class="tn13etb4r"/></g><path fill="url(#i4Mh3hd)" class="p_4flkbnx"/><path fill="url(#iuxCpPb)" class="p_4flkbnx"/><path fill="url(#iZacOIe)" class="p_4flkbnx"/><path fill="url(#iwEj75d)" class="mt218kbbr"/><path fill="url(#iBKut1b)" class="mt218kbbr"/><g filter="url(#imR9u3d)"><path class="nj1s36brp"/></g><g filter="url(#iBLcZQc)"><path class="d5urlbh-c"/></g><g filter="url(#in3SMUb)"><path class="a_myqv72g"/></g><g filter="url(#id29SRd)"><path fill="url(#iA5bnhc)" class="j3k160fag"/><path fill="url(#i1ycqOb)" class="j3k160fag"/><path fill="url(#iUtZFbb)" class="j3k160fag"/><path fill="url(#iTYvWFb)" class="j3k160fag"/><path fill="url(#iCLXone)" class="j3k160fag"/></g><g filter="url(#itMDeBd)"><path stroke="url(#iIxoX2d)" class="m788-7e4w"/></g><g filter="url(#ijAVRAd)"><path stroke="url(#iFrfVhp)" class="tb-kvacyi"/></g><g filter="url(#iMXXAfd)"><path stroke="url(#ipW8UAc)" class="vh1l4rmrx"/></g><defs><radialGradient id="iaymqjc" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.773 25.505)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="iOGzMed" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.738 19.514)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="imwwx5T" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.304 17.786)" gradientUnits="userSpaceOnUse"><stop class="mnp72frot"/><stop offset="1" class="l4rg4-bid"/></radialGradient><radialGradient id="iC7Fble" cx="0" cy="0" r="1" gradientTransform="rotate(-101.597 18.15 8.849)scale(6.81742 .9881)" gradientUnits="userSpaceOnUse"><stop class="rzqjthgas"/><stop offset="1" class="ejynn6b3w"/></radialGradient><radialGradient id="iWJpn9d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80897 .6578 -1.95135 -5.36624 12.253 17.671)" gradientUnits="userSpaceOnUse"><stop class="i03-jcbks"/><stop offset="1" class="m27qtcbgg"/></radialGradient><radialGradient id="ip0KKfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.171 20.152)" gradientUnits="userSpaceOnUse"><stop class="gwxe3pb8f"/><stop offset=".766" class="t0h--bk_d"/></radialGradient><radialGradient id="igS3Cie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.171 24.096)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="sbrbvfbik"/><stop offset=".937" class="omgy1jbfi"/></radialGradient><radialGradient id="iiRNY4A" cx="0" cy="0" r="1" gradientTransform="matrix(1.25267 -.93725 1.10777 1.48058 26.87 22.53)" gradientUnits="userSpaceOnUse"><stop class="xcnvxobld"/><stop offset="1" class="k7fvrbbpb"/></radialGradient><radialGradient id="iz6zgjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.81108 .73899 -.74364 -.8162 28.086 21.115)" gradientUnits="userSpaceOnUse"><stop class="u7id6gble"/><stop offset="1" class="ydn9dmb6d"/></radialGradient><radialGradient id="iPxsfwb" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.347 12.035)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="iqGB4qd" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.907 15.101)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="iCQupBH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.977 16.459)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="i0ew3bK" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.572 16.85)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iGQfR7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 26.046 20.721)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="i9oaRQd" cx="0" cy="0" r="1" gradientTransform="rotate(43.152 -15.607 26.584)scale(2.9724 3.56688)" gradientUnits="userSpaceOnUse"><stop class="ijcmcsb6h"/><stop offset=".865" class="p354_vbhd"/></radialGradient><radialGradient id="i9W3Nte" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 5.1 14.844)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iGuRmPn" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -3.317 26.402)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iYdDMgT" cx="0" cy="0" r="1" gradientTransform="matrix(1.33305 3.92345 -1.7834 .60594 9.62 13.376)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="iRgX2DL" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -4.01 13.722)scale(1.04691 .91836)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="i1OI3Vc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 17.976 12.317)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="imfRcQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40256 6.10192 -2.24332 -.148 20.325 12.086)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iNPAAAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 13.077 11.137)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="i6UTk0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 17.657 10.725)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="inoCnsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.4134 -8.62355 0 15.215 8.375)" gradientUnits="userSpaceOnUse"><stop offset=".791" class="o9h92gs3b"/><stop offset=".994" class="e3hrlgbfx"/></radialGradient><radialGradient id="iKHk0zb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15622 3.87502 -2.80434 -2.28415 14.996 9.346)" gradientUnits="userSpaceOnUse"><stop class="mon_o44bn"/><stop offset="1" class="k27wcn7av"/></radialGradient><radialGradient id="iII0KEm" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 20.339 -4.18)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="i93miie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.168 15.857)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="idGeJrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.71897 10.1329 0 9.939 10.736)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iBEhvZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63265 6.43634 0 20.029 10.736)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="i7aK7gd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10651 -1.44082 .76733 -2.187 19.275 4.46)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="ixaJMGb" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 14.263 2.867)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iMnWgeb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80692 1.37358 -.3823 -1.05955 15.422 4.31)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iO9Vhhc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 13.095 -4.3)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iHq1usB" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -14.048 83.266)scale(3.4792 1.94581)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="i9V2Lsd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.05 -.808)scale(4.28181 2.38793)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="ijtqUEg" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 12.62 -.714)scale(2.56111 1.83441)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iz8hOQQ" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 19.962 5.353)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="iEI7bGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 18.621 5.227)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iGzCfld" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.35 11.401)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="izlRnne" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.374 1.55)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iyptItb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.986 11.401)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i4AZBjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.7 11.62)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuxCpPb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 19.786 11.415)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iZacOIe" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.146 11.96)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iBKut1b" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 .2 9.856)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="i1ycqOb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62488 2.62025 -2.19236 -1.35953 28.412 22.48)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="iUtZFbb" cx="0" cy="0" r="1" gradientTransform="matrix(2.59834 0 0 .51085 23.77 23.989)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="pzho1txaw"/><stop offset="1" class="r-w7u-p-k"/></radialGradient><radialGradient id="iTYvWFb" cx="0" cy="0" r="1" gradientTransform="matrix(2.91284 0 0 .57269 23.56 25.443)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="pzho1txaw"/><stop offset="1" class="r-w7u-p-k"/></radialGradient><radialGradient id="iCLXone" cx="0" cy="0" r="1" gradientTransform="matrix(3.0548 0 0 .35964 23.453 26.832)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="pzho1txaw"/><stop offset="1" class="r-w7u-p-k"/></radialGradient><linearGradient id="iwT8Yhb" x1="16.967" x2="15.57" y1="26.026" y2="25.723" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="i48vhyb" x1="7.264" x2="6.093" y1="25.825" y2="25.825" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iRt9GPQ" x1="23.193" x2="23.836" y1="25.911" y2="25.88" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iH9O5Pd" x1="22.836" x2="18.461" y1="15.896" y2="28.406" gradientUnits="userSpaceOnUse"><stop class="qm8srpk6b"/><stop offset="1" class="knnk86b5x"/></linearGradient><linearGradient id="iFLNIZd" x1="16.889" x2="17.497" y1="26.396" y2="26.46" gradientUnits="userSpaceOnUse"><stop class="o_frn_b6l"/><stop offset="1" class="ohgvqyqas"/></linearGradient><linearGradient id="iPuTYtc" x1="20.852" x2="20.852" y1="15.896" y2="16.718" gradientUnits="userSpaceOnUse"><stop offset=".165" class="oy7fe6bjb"/><stop offset="1" class="ivc982b0q"/></linearGradient><linearGradient id="iQJtd8b" x1="7.961" x2="11.961" y1="17.536" y2="28.786" gradientUnits="userSpaceOnUse"><stop class="e55i1-bjj"/><stop offset="1" class="rqyrdfbps"/></linearGradient><linearGradient id="i4bwE3b" x1="8.416" x2="9.128" y1="15.15" y2="19.206" gradientUnits="userSpaceOnUse"><stop class="agyv0c9kf"/><stop offset="1" class="vxg8xmb_d"/></linearGradient><linearGradient id="inHqRab" x1="7.961" x2="8.375" y1="22.473" y2="22.27" gradientUnits="userSpaceOnUse"><stop class="maqiohbml"/><stop offset="1" class="qndc1xila"/></linearGradient><linearGradient id="iFGyd5M" x1="23.461" x2="21.679" y1="25.942" y2="25.942" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="i0h8Fjc" x1="8.179" x2="10.461" y1="27.755" y2="26.598" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="iIAd31b" x1="15.177" x2="15.177" y1="17.296" y2="28.4" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iYBqpTd" x1="17.982" x2="16.381" y1="21.953" y2="21.71" gradientUnits="userSpaceOnUse"><stop offset=".061" class="ko-tlzp-g"/><stop offset="1" class="hk3yvnfuu"/></linearGradient><linearGradient id="iW5mQYc" x1="25.804" x2="25.804" y1="15.592" y2="19.649" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="i5zDRrc" x1="25.999" x2="25.857" y1="16.528" y2="17.732" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="ifOWZ6b" x1="23.301" x2="23.428" y1="16.465" y2="16.901" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="iVO4H0A" x1="27.002" x2="24.714" y1="21.035" y2="21.035" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="ii9vjSc" x1="24.531" x2="24.912" y1="20.878" y2="20.85" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="iUD0Edi" x1="27.149" x2="26.887" y1="20.749" y2="20.725" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="iDP99hb" x1="15.168" x2="16.023" y1="13.146" y2="13.146" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iLFDcMd" x1="14.095" x2="15.169" y1="12.991" y2="13.05" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="ibgKE4b" x1="15.168" x2="15.168" y1="13.545" y2="14.397" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iotmj1b" x1="15.168" x2="15.168" y1="11.297" y2="11.717" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="itQ8sLe" x1="14.074" x2="13.559" y1="6.144" y2="8.221" gradientUnits="userSpaceOnUse"><stop class="dc395nbfa"/><stop offset="1" class="q2sj4_bau"/></linearGradient><linearGradient id="iFsrUSb" x1="20.532" x2="10.408" y1="6.655" y2="6.655" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="isAwFYG" x1="18.128" x2="17.814" y1="11.455" y2="11.648" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7eAYpD" x1="13.73" x2="13.416" y1="11.455" y2="11.648" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4Mh3hd" x1="21.604" x2="20.398" y1="11.482" y2="13.658" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iwEj75d" x1="9.318" x2="10.777" y1="12.186" y2="12.059" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iA5bnhc" x1="28.086" x2="23.56" y1="26.282" y2="26.282" gradientUnits="userSpaceOnUse"><stop class="kwbcosrfm"/><stop offset=".861" class="rfqu9yc3v"/></linearGradient><linearGradient id="iIxoX2d" x1="25.696" x2="23.633" y1="24.002" y2="24.002" gradientUnits="userSpaceOnUse"><stop class="qebm4hycr"/><stop offset="1" class="b9b7yqeyc"/></linearGradient><linearGradient id="iFrfVhp" x1="25.696" x2="23.633" y1="25.443" y2="25.443" gradientUnits="userSpaceOnUse"><stop class="qebm4hycr"/><stop offset="1" class="b9b7yqeyc"/></linearGradient><linearGradient id="ipW8UAc" x1="25.696" x2="23.633" y1="26.873" y2="26.873" gradientUnits="userSpaceOnUse"><stop class="qebm4hycr"/><stop offset="1" class="b9b7yqeyc"/></linearGradient><filter id="ieDERxb" width="1.447" height="2.403" x="19.88" y="10.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".125"/></filter><filter id="iBaxQ3b" width="5.513" height="4.74" x="12.913" y="23.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3665"/></filter><filter id="i7n4blN" width="6.102" height="1.228" x="22.856" y="16.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3665"/></filter><filter id="if5V3De" width="1.075" height="1.075" x="25.264" y="20.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3665"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13949_3665" result="effect2_innerShadow_13949_3665"/></filter><filter id="i4k36Td" width="5.813" height="5.813" x="12.309" y="14.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".25"/></filter><filter id="inEMMUP" width="10.72" height="12.542" x="10.105" y="6.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3665"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13949_3665" result="effect2_innerShadow_13949_3665"/></filter><filter id="iAddkcb" width="3.877" height="4.9" x="13.022" y="10.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".5"/></filter><filter id="i6qtPod" width="2.077" height="3.1" x="14.13" y="11.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".05"/></filter><filter id="iavKo9b" width="3.718" height="1.573" x="13.309" y="14.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".05"/></filter><filter id="i2pdaOM" width="12.873" height="8.357" x="8.732" y="2.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3665"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13949_3665" result="effect2_innerShadow_13949_3665"/></filter><filter id="iVRypYd" width="2.339" height="1.19" x="16.757" y="8.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.231373 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3665"/></filter><filter id="iNp2Vvb" width="2.339" height="1.176" x="11.501" y="8.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.231373 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3665"/></filter><filter id="iZ1rc7b" width="6.584" height="5.992" x="9.087" y="4.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".125"/></filter><filter id="iD7xbAc" width="6.362" height="5.736" x="15.009" y="4.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".125"/></filter><filter id="i6RiTNd" width=".787" height=".696" x="16.616" y="10.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".05"/></filter><filter id="iRaMOsW" width=".891" height=".913" x="17.456" y="11.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".1"/></filter><filter id="idborLj" width=".986" height="1.04" x="13.013" y="10.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".1"/></filter><filter id="iq1onPc" width=".913" height=".705" x="12.258" y="10.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".05"/></filter><filter id="imR9u3d" width="1.329" height="2.379" x="9.136" y="10.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".125"/></filter><filter id="iBLcZQc" width="2.205" height=".96" x="11.52" y="8.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".075"/></filter><filter id="in3SMUb" width="2.105" height=".86" x="16.849" y="8.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".075"/></filter><filter id="id29SRd" width="5.519" height="6.076" x="23.193" y="22.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3665"/></filter><filter id="itMDeBd" width="2.269" height=".25" x="23.683" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".05"/></filter><filter id="ijAVRAd" width="2.269" height=".25" x="23.683" y="25.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".05"/></filter><filter id="iMXXAfd" width="2.269" height=".25" x="23.683" y="26.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3665" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:singer" /></template>
<style>
.a_myqv72g {
  stroke: var(--svg-color--ce6c59, #CE6C59);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M18.73 9.462c-.258-.184-.898-.508-1.656-.381");
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

.agjxsvb1m {
  d: path("m28.28 16.436l-4.845-.02a.57.57 0 0 0-.579.579c0 .325.254.579.58.579l4.843.02a.57.57 0 0 0 .579-.579a.585.585 0 0 0-.579-.579");
}

.agyv0c9kf {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
}

.alpke6bgr {
  d: path("M27.083 28.396c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.ao-rt-uhf {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.13 13.007q.058-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.b9b7yqeyc {
  stop-color: var(--svg-color--d58628, #D58628);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.b9sj__brp {
  d: path("M7.143 28.396h3.87L7.143 20.8z");
}

.bh30q1gbu {
  d: path("M17.352 10.924a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
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

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
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

.cxf3v0baf {
  d: path("M15.188 6.281a.66.66 0 0 0-.402-.137h-1.273a3.3 3.3 0 0 0-.541.044l-2.248 6.619h1.809l-.508 2.687l3.688-5.132H13.83z");
}

.d0i7vecxv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.287 11.113c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.114.325-.136.389-.051");
}

.d5urlbh-c {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.795 9.508c.257-.184.898-.508 1.655-.38");
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.dc395nbfa {
  stop-color: var(--svg-color--ff165e, #FF165E);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.dpjgnpdex {
  fill: var(--svg-color--bf4c2d, #BF4C2D);
  d: path("M11.757 9.229a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.55a2.22 2.22 0 0 0-1.387.286a1 1 0 0 0-.092.06l-.002.001a.277.277 0 0 1-.34-.438z");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e3hrlgbfx {
  stop-color: var(--svg-color--e88027, #E88027);
}

.e55i1-bjj {
  stop-color: var(--svg-color--e86b1f, #E86B1F);
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ejynn6b3w {
  stop-color: var(--svg-color--ef5945, #EF5945);
  stop-opacity: 0;
}

.f71l5lp1h {
  d: path("m20.38 10.074l-.028-.631c-.011-.764-.642-1.394-1.406-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.367c-.256-.97.671-1.713 1.656-1.522c.973.189 2.082.517 2.902 1.052c1.745 1.138 1.439 3.188.52 4.154");
}

.fcs7flbwg {
  d: path("M5.47 16.417h6.086l2.248 11.989h-2.79l-5.88-11.529c-.085-.125-.07-.46.336-.46");
}

.fnu1q5x6k {
  d: path("M20.03 13.567c.335-.01.648-.124.904-.308v.93c0 .894-.532 1.69-1.34 2.02a4.1 4.1 0 0 0 .345-1.18z");
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
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

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjjsvbmnk {
  d: path("M12.984 10.924a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.go0ufubgn {
  d: path("M25.791 26.236a.784.784 0 0 1-.782-.71l-.67-6.429l2.976.01l-.732 6.428a.8.8 0 0 1-.792.7");
}

.guwvw8byr {
  d: path("M10.343 15.082a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.237-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.556");
}

.gwxe3pb8f {
  stop-color: var(--svg-color--ffc033, #FFC033);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h__y94wtt {
  d: path("M18.147 11.7a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.hf_dmgbtw {
  d: path("M25.801 21.524a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hk3yvnfuu {
  stop-color: var(--svg-color--fbb231, #FBB231);
  stop-opacity: 0;
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hy1lvcb8j {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.56 10.653c.652 0 1.204.45 1.354 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.i03-jcbks {
  stop-color: var(--svg-color--d14708, #D14708);
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

.ijcmcsb6h {
  stop-color: var(--svg-color--e58421, #E58421);
}

.ivc982b0q {
  stop-color: var(--svg-color--e48043, #E48043);
  stop-opacity: 0;
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j3k160fag {
  d: path("M23.193 23.283c0-.44.366-.803.816-.803h3.055c.745 0 1.348.59 1.348 1.316v3.514c0 .605-.503 1.096-1.123 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.314.187-.59.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.72a.8.8 0 0 1-.458-.721c0-.314.187-.589.458-.72a.8.8 0 0 1-.458-.72");
}

.jiu__0bgd {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.777 10.652c-.653 0-1.205.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.128");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k27wcn7av {
  stop-color: var(--svg-color--ec375e, #EC375E);
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k7fvrbbpb {
  stop-color: var(--svg-color--ffd033, #FFD033);
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

.kn6rpk-yp {
  d: path("M27.342 20.72c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.knnk86b5x {
  stop-color: var(--svg-color--d53939, #D53939);
}

.ko-tlzp-g {
  stop-color: var(--svg-color--ce6f07, #CE6F07);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.kwbcosrfm {
  stop-color: var(--svg-color--ffe432, #FFE432);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l2pb7sqlg {
  d: path("M13.8 11.712c0-.289-.235-.48-.299-.539l-.288.279l.178.361z");
}

.l4rg4-bid {
  stop-color: var(--svg-color--f6874a, #F6874A);
  stop-opacity: 0;
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.ldm_1v-5j {
  d: path("m15.4 6.702l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379V9.8c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96a2.4 2.4 0 0 0 .331-.252l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.892v1.485z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m27qtcbgg {
  stop-color: var(--svg-color--d14708, #D14708);
  stop-opacity: 0;
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.m788-7e4w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.808 24.002h2.019");
}

.ma7bgbcul {
  d: path("M12.913 23.656v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.maqiohbml {
  stop-color: var(--svg-color--ec7046, #EC7046);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mnp72frot {
  stop-color: var(--svg-color--f6874a, #F6874A);
}

.mon_o44bn {
  stop-color: var(--svg-color--ff2d8d, #FF2D8D);
}

.mt218kbbr {
  d: path("M10.114 10.459a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nig06wb4n {
  cx: 12.715px;
  cy: 11.305px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nj1s36brp {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.131 11.12a.956.956 0 0 0 .083 1.879a78 78 0 0 1-.083-1.88");
}

.nkmjyccuf {
  d: path("M15.183 16.209c-1.16 0-2.486.209-3.566.58l1.29 6.873c.72.325 1.496.434 2.316.434c.77 0 1.511-.074 2.191-.352l1.312-6.955c-1.05-.383-2.383-.58-3.543-.58");
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.o_frn_b6l {
  stop-color: var(--svg-color--cc2820, #CC2820);
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o9h92gs3b {
  stop-color: var(--svg-color--e88027, #E88027);
  stop-opacity: 0;
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.ohgvqyqas {
  stop-color: var(--svg-color--cc2820, #CC2820);
  stop-opacity: 0;
}

.omgy1jbfi {
  stop-color: var(--svg-color--cf731b, #CF731B);
}

.omm106fle {
  d: path("M17.287 11.113c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.114.325-.136.389-.051");
}

.ovjkybbnn {
  d: path("M20.023 5.675c.515.177.976.536 1.268 1.05a2.37 2.37 0 0 1-.107 2.527a1.56 1.56 0 0 0-.27.874v1.189a1.7 1.7 0 0 0-.667-.269l.078-1.606a1.45 1.45 0 0 0-1.379-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.446a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.383-1.11a2.325 2.325 0 0 1 2.891-.912a1.5 1.5 0 0 0 1.193 0c.281-.118.59-.188.913-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.oy7fe6bjb {
  stop-color: var(--svg-color--e48043, #E48043);
}

.p_4flkbnx {
  d: path("M20.09 13.658q.101-1.596.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.p354_vbhd {
  stop-color: var(--svg-color--f29719, #F29719);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.p93e4gk6d {
  d: path("M24.379 16.41h-5.58l-2.274 11.996h3.148l5.326-11.017a.685.685 0 0 0-.62-.98");
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

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.py8_5dbcb {
  d: path("m14.786 11.603l-.532 1.838c-.108.378.152.756.52.756h.787c.37 0 .63-.383.52-.756l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.pzho1txaw {
  stop-color: var(--svg-color--ee9829, #EE9829);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q2sj4_bau {
  stop-color: var(--svg-color--ff165e, #FF165E);
  stop-opacity: 0;
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qebm4hycr {
  stop-color: var(--svg-color--d58628, #D58628);
  stop-opacity: 0;
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qm8srpk6b {
  stop-color: var(--svg-color--f98026, #F98026);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qndc1xila {
  stop-color: var(--svg-color--ec7046, #EC7046);
  stop-opacity: 0;
}

.qovgumx7t {
  fill: var(--svg-color--000, #000);
  d: path("M13.495 11.817a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-w7u-p-k {
  stop-color: var(--svg-color--ee9829, #EE9829);
  stop-opacity: 0;
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rfqu9yc3v {
  stop-color: var(--svg-color--f5a32b, #F5A32B);
}

.rqyrdfbps {
  stop-color: var(--svg-color--e22f38, #E22F38);
}

.rzqjthgas {
  stop-color: var(--svg-color--ef5945, #EF5945);
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.sbrbvfbik {
  stop-color: var(--svg-color--cf731b, #CF731B);
  stop-opacity: 0;
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t0h--bk_d {
  stop-color: var(--svg-color--f0972b, #F0972B);
}

.tb-kvacyi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.808 25.443h2.019");
}

.tbefs5d0d {
  d: path("M15.183 17.296c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.tn13etb4r {
  cx: 12.715px;
  cy: 11.305px;
  rx: 0.39px;
  ry: 0.197px;
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.txh8aq1mn {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.817 14.819c.39.203.855.32 1.351.32c.5 0 .96-.117 1.35-.32h.002a.23.23 0 0 1 .27.044a.214.214 0 0 1 .024.273m-2.997-.317l2.934.275m-2.934-.275a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27m.294-.317l-.232.275m3.229.042l-.063-.041m.063.041l-.063-.041m.063.041a1.97 1.97 0 0 1-1.646.88c-.69 0-1.297-.352-1.645-.88m3.228-.041a1.9 1.9 0 0 1-1.583.845a1.9 1.9 0 0 1-1.583-.845m-.062.041v.001l.062-.043m-.062.043v-.001l.062-.041");
}

.u7id6gble {
  stop-color: var(--svg-color--ffe945, #FFE945);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ugmo_530l {
  d: path("M15.168 15.214c-.507 0-.984-.12-1.385-.328c-.137-.07-.285.084-.198.209c.335.507.918.845 1.583.845s1.249-.338 1.583-.845c.087-.13-.06-.28-.198-.21a3 3 0 0 1-1.385.329");
}

.uwfkylv_u {
  d: path("M10.307 13.567a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7wp60bcw {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m14.682 11.799l-.635 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.408-.543-.408-.662 0");
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vh1l4rmrx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.808 26.873h2.019");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vxg8xmb_d {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
  stop-opacity: 0;
}

.w5bhpkbss {
  d: path("M25.832 19.595a2.498 2.498 0 1 0 0-4.997a2.498 2.498 0 0 0 0 4.997");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wc4slvbug {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M18.901 9.338a1.85 1.85 0 0 0-.687-.412c-.305-.095-.686-.121-1.213-.057a.277.277 0 1 0 .067.55c.481-.058.776-.027.979.036c.198.063.332.164.49.301a.277.277 0 0 0 .364-.418");
}

.wf31j_m3i {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.913 23.656v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wtoaknbgg {
  fill: var(--svg-color--000, #000);
  d: path("M16.841 11.817c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.235");
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.xcnvxobld {
  stop-color: var(--svg-color--f5a511, #F5A511);
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.y_ok4rf-q {
  cx: 15.215px;
  cy: 17.655px;
  r: 2.406px;
}

.ydn9dmb6d {
  stop-color: var(--svg-color--ffe945, #FFE945);
  stop-opacity: 0;
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yr-wd3bdy {
  d: path("M23.193 28.396v-7.268l-3.52 7.268z");
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z3tmracpy {
  d: path("M7.143 28.396v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
