<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i7Mc5be)"><path class="gkw4sac_i"/><path fill="url(#iJDjdPr)" class="dcogs8bsh"/></g><path fill="url(#iLpdJie)" class="dcogs8bsh"/><path fill="url(#iitMz0C)" class="dcogs8bsh"/><path fill="url(#ihyYxWc)" class="dcogs8bsh"/><path fill="url(#i4bI9Be)" class="dcogs8bsh"/><g filter="url(#iL2zckb)"><path class="ydres4b4h"/><path fill="url(#iSxDVke)" class="em-pjfbcg"/></g><path class="eh2k3qbwi"/><path fill="url(#iYkIQJb)" class="lb1zw-b1u"/><path fill="url(#icvlSzb)" class="lb1zw-b1u"/><path fill="url(#iguHF4j)" class="bjo3ledcq"/><path fill="url(#iN96uDc)" class="jytpn83dl"/><path fill="url(#iUS33xe)" class="jytpn83dl"/><g filter="url(#iadwChn)"><path fill="url(#ivQ5kvQ)" class="b96gakb3t"/><path fill="url(#iIX8Bqc)" class="b96gakb3t"/></g><g filter="url(#ih2gkNA)"><circle fill="url(#iwKsY6b)" class="yi5ln4bok"/></g><g filter="url(#i8QcDnR)"><circle fill="url(#i2HlaPd)" class="l1gl77bzm"/></g><g filter="url(#icXE69d)"><circle fill="url(#i5sPa2d)" class="rudb12k0p"/></g><rect fill="url(#io3Rqra)" transform="rotate(26.595 20.662 12.816)" class="rczvpztto"/><g filter="url(#ib5HEze)"><path fill="url(#icDPZUh)" class="fgw68gbhw"/></g><path class="vr3js9b3d"/><path fill="url(#iqoVeFr)" class="ao0db4b4r"/><g filter="url(#iX8u1RK)"><path class="rp7oudbsr"/><path fill="url(#iRECIzb)" class="v-ga10f4f"/><path fill="url(#iPpqrPd)" class="v-ga10f4f"/></g><g filter="url(#ikm5Nhb)"><path fill="url(#isMHdAd)" class="pkq4odbli"/><path fill="url(#i3g2fcO)" class="pkq4odbli"/><path fill="url(#iw6jNCd)" class="pkq4odbli"/></g><path fill="url(#iN6KJMd)" class="pkq4odbli"/><path fill="url(#i2W9LUc)" class="nm46fkmyg"/><path fill="url(#iQhotvd)" class="nm46fkmyg"/><path clip-rule="evenodd" class="chp33qbnl"/><path fill="url(#ikKOiwb)" clip-rule="evenodd" class="z91enii4f"/><path clip-rule="evenodd" class="l6aht38_w"/><path fill="url(#irUvmQE)" clip-rule="evenodd" class="ob_pqhb0g"/><path clip-rule="evenodd" class="birzucbpr"/><path fill="url(#iR3cl0F)" clip-rule="evenodd" class="s3qfvabch"/><path clip-rule="evenodd" class="i3l5ycb1m"/><path fill="url(#iGGFh8b)" clip-rule="evenodd" class="uajw-acut"/><path class="lsnj8--zq"/><path fill="url(#i7j5mob)" class="ljh96mbpx"/><g filter="url(#it3qRwe)"><path fill="url(#icldLze)" class="mmnxzqoyz"/></g><g filter="url(#irB77ue)"><path fill="url(#inTSD3b)" class="lh6x9gb0k"/></g><g filter="url(#iasNhld)"><path stroke="url(#iqyR7Md)" class="e7zo4pl3x"/></g><g filter="url(#i2eEJ8m)"><circle fill="url(#iaAWDvc)" class="hlkj9uvrc"/></g><g filter="url(#i0EReEb)"><circle fill="url(#i7MBJDc)" class="tvn1pe_ym"/></g><g filter="url(#iN4mCEd)"><circle fill="url(#iB30CRd)" class="keb1ysbtm"/><circle fill="url(#i5H5Xmd)" class="keb1ysbtm"/></g><g filter="url(#iBrglJe)"><circle class="mvelyh28d"/><circle fill="url(#iE9ldsj)" class="ni4ip04et"/><circle fill="url(#iRyGOxl)" class="ni4ip04et"/></g><g filter="url(#iQsP7Ub)"><path fill="url(#iYODNKY)" class="w9cb85b5x"/><path fill="url(#iUWkaEe)" class="w9cb85b5x"/><path fill="url(#ipDMTNg)" class="w9cb85b5x"/><path fill="url(#i0mvgCb)" class="w9cb85b5x"/><path fill="url(#iDnoQDd)" class="w9cb85b5x"/></g><g filter="url(#iWSEvCb)"><path class="v9a_2379o"/><path fill="url(#iGW6D9d)" class="e6f6l9bqz"/><path fill="url(#ihN9IMe)" class="e6f6l9bqz"/><path fill="url(#it2oRcb)" class="e6f6l9bqz"/><path fill="url(#il8cEYd)" class="e6f6l9bqz"/><path fill="url(#i7DadTd)" class="e6f6l9bqz"/></g><path fill="url(#imF173F)" class="fjpeh0q8d"/><path fill="url(#iXwW1YS)" class="fjpeh0q8d"/><g filter="url(#iQw3Ebe)"><path class="efvigvlwx"/></g><g filter="url(#izPCEBb)"><path class="hsgktvbnq"/><path fill="url(#ij5RlCd)" class="p70sstpth"/><path fill="url(#irOA8Vd)" class="p70sstpth"/><path fill="url(#iaBwrDb)" class="p70sstpth"/></g><path stroke="url(#i8Ci7Gq)" class="mf22u5b0t"/><g filter="url(#i2ceGBd)"><path class="hv5ov_b9j"/></g><g filter="url(#ivQ1pdd)"><path class="qhb9xl9dj"/></g><path class="yykgsohgs"/><path fill="url(#iDi7XDd)" class="qbgflqb2s"/><path class="gbiibgnkx"/><g filter="url(#i2NO3xb)"><path class="h1n_uss9t"/><path fill="url(#iotQvpd)" class="v0khcu8ni"/></g><g filter="url(#idba3ub)"><path fill="url(#iK9dVld)" class="h79f4xbxx"/></g><path class="wlm6gibod"/><path fill="url(#iMKT64c)" class="q_tlouv3l"/><path class="zh1fb4b2d"/><g filter="url(#iIwCiCc)"><path fill="url(#i5B9Xrc)" class="ow034zbkg"/></g><g filter="url(#iLtBbEc)"><ellipse transform="rotate(-27.914 13.085 5.693)" class="a5s36obsl"/><ellipse fill="url(#iWqw54d)" transform="rotate(-27.914 13.085 5.693)" class="szaxszpjh"/></g><g filter="url(#iLLqvwO)"><path stroke="url(#iOUO6cb)" class="o-_kuhk7b"/></g><g filter="url(#iepKwie)"><path stroke="url(#iSiUErb)" class="srov_gb6c"/></g><defs><radialGradient id="iLpdJie" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.984 21.777)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="ihyYxWc" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -6.125 3.8162 2.21963 22.204 21.933)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="i4bI9Be" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.777)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iSxDVke" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.169 25.214)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iYkIQJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.76 25.146)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="xhtyz4bzf"/><stop offset="1" class="wa28pxbrb"/></radialGradient><radialGradient id="iUS33xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.48)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="iIX8Bqc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.744 2.822)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="iwKsY6b" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.214 11.14)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i2HlaPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.563)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i5sPa2d" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.167 9.176)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="io3Rqra" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.115)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="w80grmxvp"/><stop offset="1" class="l5g-5nb-e"/></radialGradient><radialGradient id="icDPZUh" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.198 10.928)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="ae5rwo7_n"/><stop offset="1" class="e8ax3tbne"/></radialGradient><radialGradient id="iqoVeFr" cx="0" cy="0" r="1" gradientTransform="matrix(-.01563 -.84376 1.95707 -.03625 7.865 15.04)" gradientUnits="userSpaceOnUse"><stop class="rc1e7ccwp"/><stop offset="1" class="zv22riybk"/></radialGradient><radialGradient id="iRECIzb" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.925 6.72)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="jioe1_9gu"/><stop offset="1" class="t5lf5ccyt"/></radialGradient><radialGradient id="iPpqrPd" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.332 10.556)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="fqeviqb2e"/><stop offset="1" class="to9zfdmjz"/></radialGradient><radialGradient id="i3g2fcO" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.432)" gradientUnits="userSpaceOnUse"><stop class="lj0l7tb9r"/><stop offset="1" class="zrzxj2epv"/></radialGradient><radialGradient id="iw6jNCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49191 -2.04898 0 13.776 7.613)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="vgauzicqp"/><stop offset="1" class="r0iiaeguw"/></radialGradient><radialGradient id="iN6KJMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.38038 -.82813 3.08645 5.14471 17.339 21.245)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="t502ec3cr"/><stop offset="1" class="oipf0m4co"/></radialGradient><radialGradient id="iQhotvd" cx="0" cy="0" r="1" gradientTransform="matrix(3.55689 1.62587 -.93464 2.0447 18.61 10.76)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="g99cn0bet"/><stop offset="1" class="gq1i90b_a"/><stop offset="1" class="airol1bay"/></radialGradient><radialGradient id="ikKOiwb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.216 6.135 5.686)scale(1.55003 1.68911)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".69" class="qrfzq6pjd"/></radialGradient><radialGradient id="irUvmQE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24388 -.94214 1.33264 -1.75944 5.77 14.697)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".769" class="qrfzq6pjd"/></radialGradient><radialGradient id="iR3cl0F" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23007 -1.01775 1.46904 -1.7755 5.598 15.262)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".769" class="qrfzq6pjd"/></radialGradient><radialGradient id="iGGFh8b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04688 -.89062 1.29178 -1.51843 5.802 15.495)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".769" class="qrfzq6pjd"/></radialGradient><radialGradient id="i7j5mob" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.787)" gradientUnits="userSpaceOnUse"><stop class="vhkp_yb0t"/><stop offset="1" class="bg_l4vb3c"/></radialGradient><radialGradient id="icldLze" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.506 15.406)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iaAWDvc" cx="0" cy="0" r="1" gradientTransform="matrix(.77822 0 0 1.36189 11.328 6.038)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="i5H5Xmd" cx="0" cy="0" r="1" gradientTransform="matrix(.36661 -.26695 .3047 .41844 16.452 5.92)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iE9ldsj" cx="0" cy="0" r="1" gradientTransform="matrix(.3642 -.66987 .39208 .21317 16.268 6.402)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iRyGOxl" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 .802 22.821)scale(.16179 .20857)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iUWkaEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.73186 -4.52084 0 14.382 4.556)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="vpd4dcexx"/><stop offset="1" class="upbi0xbpg"/></radialGradient><radialGradient id="i0mvgCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57964 .7134 0 15.214 5.474)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iDnoQDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6168 .76705 0 13.193 5.459)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iGW6D9d" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 7.264 5.18)scale(2.48614 4.22791)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="it2oRcb" cx="0" cy="0" r="1" gradientTransform="rotate(-92.056 8.33 -3.687)scale(.82603 .40568)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="il8cEYd" cx="0" cy="0" r="1" gradientTransform="matrix(.381 -.87207 .71124 .31073 16.048 5.267)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="i7DadTd" cx="0" cy="0" r="1" gradientTransform="matrix(.44027 .54629 -.48233 .38872 13.83 2.223)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="imF173F" cx="0" cy="0" r="1" gradientTransform="matrix(.08043 .34732 -.571 .13224 14.376 2.222)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iXwW1YS" cx="0" cy="0" r="1" gradientTransform="matrix(.32173 .39793 -.89162 .72089 12.14 2.99)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="iDi7XDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .40052 -.47392 0 15.14 5.883)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iotQvpd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 8.933 -.796)scale(.16772 .23091)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMKT64c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .40054 -.47394 0 13.205 5.883)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iWqw54d" cx="0" cy="0" r="1" gradientTransform="matrix(-.00343 -.21906 .26332 -.00412 13.078 5.832)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i7Mc5be" width="23.977" height="13.398" x="6.016" y="16.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="iL2zckb" width="20.681" height="10.082" x="6.11" y="20.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".75"/></filter><filter id="iadwChn" width="24.344" height="8.644" x="2.007" y="21.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="ih2gkNA" width="2.686" height="2.686" x="24.571" y="13.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="i8QcDnR" width="2.186" height="2.186" x="27.821" y="11.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="icXE69d" width="1.928" height="1.928" x="25.946" y="9.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="ib5HEze" width="2.857" height="2.898" x="20.532" y="12.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.462745 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="iX8u1RK" width="5.571" height="6.952" x="7.773" y="7.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.396078 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="ikm5Nhb" width="14.97" height="18.153" x="8.427" y="7.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.537255 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="it3qRwe" width="17.737" height="14.8" x="13.579" y="15.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation="1"/></filter><filter id="irB77ue" width="6.506" height="14.75" x="14.572" y="7.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".375"/></filter><filter id="iasNhld" width="5.506" height="5.421" x="17.991" y="7.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".3"/></filter><filter id="i2eEJ8m" width="1.681" height="1.481" x="11.328" y="5.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="i0EReEb" width="1.282" height="1.282" x="11.427" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".1"/></filter><filter id="iN4mCEd" width="1.731" height="1.731" x="15.546" y="5.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="iBrglJe" width="1.282" height="1.282" x="15.646" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".1"/></filter><filter id="iQsP7Ub" width="4.6" height="5.484" x="11.886" y="3.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="iWSEvCb" width="5.588" height="3.667" x="11.379" y="2.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="iQw3Ebe" width="2.28" height="2.689" x="12.927" y="5.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".375"/></filter><filter id="izPCEBb" width="1.032" height="1.389" x="13.657" y="5.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".05"/></filter><filter id="i2ceGBd" width="1.461" height="1.053" x="14.698" y="4.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="ivQ1pdd" width="1.461" height="1.053" x="12.415" y="4.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23002"/></filter><filter id="i2NO3xb" width=".46" height=".42" x="14.758" y="5.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".05"/></filter><filter id="idba3ub" width=".618" height=".628" x="15.075" y="5.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".1"/></filter><filter id="iIwCiCc" width=".66" height=".684" x="13.105" y="5.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".1"/></filter><filter id="iLtBbEc" width=".516" height=".424" x="12.826" y="5.481" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".05"/></filter><filter id="iLLqvwO" width="1.22" height=".591" x="14.71" y="4.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".075"/></filter><filter id="iepKwie" width="1.255" height=".616" x="12.395" y="4.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23002" stdDeviation=".075"/></filter><linearGradient id="iJDjdPr" x1="7.172" x2="16.735" y1="29.37" y2="29.37" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iitMz0C" x1="16.86" x2="16.766" y1="30.277" y2="28.652" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="icvlSzb" x1="7.833" x2="8.372" y1="25.932" y2="26.112" gradientUnits="userSpaceOnUse"><stop offset=".283" class="v4i9n53vy"/><stop offset="1" class="atc_6-nza"/></linearGradient><linearGradient id="iguHF4j" x1="21.172" x2="19.469" y1="21.933" y2="23.019" gradientUnits="userSpaceOnUse"><stop class="ybjx3ubtr"/><stop offset="1" class="zpgy93w4i"/></linearGradient><linearGradient id="iN96uDc" x1="22.095" x2="23.329" y1="24.839" y2="26.12" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="ivQ5kvQ" x1="5.891" x2="25.735" y1="29.245" y2="22.339" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="isMHdAd" x1="15.777" x2="15.777" y1="7.613" y2="25.573" gradientUnits="userSpaceOnUse"><stop class="nxcp0hivj"/><stop offset="1" class="p79aa0p9z"/></linearGradient><linearGradient id="i2W9LUc" x1="23.651" x2="16.517" y1="12.509" y2="8.555" gradientUnits="userSpaceOnUse"><stop class="y60usm6nn"/><stop offset=".91" class="u6gia-bos"/></linearGradient><linearGradient id="inTSD3b" x1="17.826" x2="20.269" y1="8.167" y2="21.403" gradientUnits="userSpaceOnUse"><stop class="yrtrc6n_d"/><stop offset="1" class="kkuk5w_fi"/></linearGradient><linearGradient id="iqyR7Md" x1="22.438" x2="18.766" y1="11.886" y2="7.995" gradientUnits="userSpaceOnUse"><stop class="tgz_9qxcq"/><stop offset="1" class="zvqcq9hxr"/></linearGradient><linearGradient id="i7MBJDc" x1="12.068" x2="11.784" y1="6.161" y2="6.161" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iB30CRd" x1="16.768" x2="16.405" y1="5.554" y2="6.678" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iYODNKY" x1="15.963" x2="12.577" y1="6.21" y2="6.715" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="ipDMTNg" x1="11.781" x2="12.806" y1="7.406" y2="7.272" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="ihN9IMe" x1="12.018" x2="13.305" y1="5.919" y2="3.633" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="ij5RlCd" x1="13.79" x2="14.206" y1="6.503" y2="6.503" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="irOA8Vd" x1="14.589" x2="14.135" y1="6.646" y2="6.639" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iaBwrDb" x1="14.26" x2="14.26" y1="6.975" y2="6.721" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="i8Ci7Gq" x1="13.714" x2="13.906" y1="7.691" y2="7.386" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iK9dVld" x1="15.485" x2="15.345" y1="5.759" y2="5.845" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5B9Xrc" x1="13.534" x2="13.395" y1="5.759" y2="5.845" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iOUO6cb" x1="15.492" x2="15.305" y1="4.81" y2="4.429" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iSiUErb" x1="13.139" x2="12.612" y1="4.754" y2="4.532" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-surfing-medium-light" /></template>
<style>
.a5s36obsl {
  cx: 13.085px;
  cy: 5.693px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.173px;
  ry: 0.087px;
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.ae5rwo7_n {
  stop-color: var(--svg-color--f9caaa, #F9CAAA);
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.airol1bay {
  stop-color: var(--svg-color--815ecd, #815ECD);
  stop-opacity: 0;
}

.ao0db4b4r {
  d: path("M7.602 12.783h.594c-.106.668.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.257.977-.3 1.258-.29");
}

.atc_6-nza {
  stop-color: var(--svg-color--f2b790, #F2B790);
  stop-opacity: 0;
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.b96gakb3t {
  d: path("M24.458 21.269L2.29 28.958a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.1 1.156-.157c5.922-2.015 17.406-5.859 18.176-6.199c.443-.195.511-.378.605-.627v-.002c.094-.25.047-1.03-.5-1.453c-.437-.337-1.105-.185-1.355-.07");
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bg_l4vb3c {
  stop-color: var(--svg-color--efba9f, #EFBA9F);
  stop-opacity: 0;
}

.birzucbpr {
  fill: var(--svg-color--e5b18a, #E5B18A);
  fill-rule: evenodd;
  d: path("M5.25 14.674q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.bjo3ledcq {
  d: path("M19.837 23.019a29 29 0 0 1-.907-.867l1.867-.883c.075.131.51.8.72 1.117z");
}

.chp33qbnl {
  fill: var(--svg-color--e5b18a, #E5B18A);
  fill-rule: evenodd;
  d: path("M7.127 13.55c-.941-.283-1.295.01-1.388.12a.375.375 0 0 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 0 1-.216.718");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.dcogs8bsh {
  d: path("M19.75 29.755H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.841 2.937-3.292 4.109-4.976s2.062-2.294 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.326-6.078 1.28");
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e6f6l9bqz {
  d: path("m16.31 3.165l.19.095a.87.87 0 0 1 .453.946l-.262 1.348c-.023.139-.115.233-.254.236h-.008s.024-.402.048-.638c.02-.192-.014-.251-.19-.426a.56.56 0 0 1-.167-.378v-.379a.255.255 0 0 0-.19-.236a7.3 7.3 0 0 0-1.737-.19c-.856 0-1.45.119-1.736.19a.23.23 0 0 0-.19.236v.379a.47.47 0 0 1-.167.378l-.071.07c-.095.072-.143.214-.143.332c.024.26.048.639.048.639l-.022-.001a.28.28 0 0 1-.264-.236l-.261-1.348a.905.905 0 0 1 .475-.922l.19-.095c.12-.071.238-.166.357-.26l.428-.45a.87.87 0 0 1 .976-.142c.238.071.5.071.737 0a1.07 1.07 0 0 1 1.047.237l.357.355a1 1 0 0 0 .357.26");
}

.e7zo4pl3x {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.292c1.209-.02 3.782.828 4.104 4");
}

.e8ax3tbne {
  stop-color: var(--svg-color--e2ac93, #E2AC93);
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.efvigvlwx {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m14.051 5.984l-.364.753c-.045.155.064.31.217.31h.327c.153 0 .261-.157.216-.31l-.22-.753c-.048-.167-.126-.167-.176 0");
}

.eh2k3qbwi {
  fill: var(--svg-color--e3aa86, #E3AA86);
  d: path("m7.305 27.355l1.172-2.39l1.766.304v1.039z");
}

.em-pjfbcg {
  d: path("M21.985 27.34L7.61 28.84c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.335 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fgw68gbhw {
  d: path("M20.68 13.856c.256-.588.373-1.22.399-1.462l2.047.023c.046.27-.04.584-.079.704c.088.322.037.686 0 .828c-.054.226-.178.713-.238.86c-.074.184-.183.247-.348.23a.4.4 0 0 1-.148-.042a.3.3 0 0 0-.23-.019a.43.43 0 0 1-.227.019a.43.43 0 0 1-.204-.113a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.005a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.071c-.085.007-.183.003-.235-.04c-.098-.083-.219-.177.031-.747");
}

.fjpeh0q8d {
  d: path("m16.205 3.165l.19.095a.87.87 0 0 1 .452.946l-.262 1.348c-.023.139-.115.233-.254.236h-.008s.024-.402.048-.638c.02-.192-.014-.251-.19-.426a.56.56 0 0 1-.167-.378v-.379a.255.255 0 0 0-.19-.236a7.3 7.3 0 0 0-1.737-.19c-.856 0-1.45.119-1.736.19a.23.23 0 0 0-.19.236v.379a.47.47 0 0 1-.167.378l-.071.07c-.095.072-.143.214-.143.332c.024.26.048.639.048.639l-.022-.001a.28.28 0 0 1-.264-.236l-.261-1.348a.91.91 0 0 1 .475-.922l.19-.095c.12-.071.239-.166.357-.26l.429-.45a.87.87 0 0 1 .975-.142c.238.071.5.071.737 0a1.07 1.07 0 0 1 1.047.237l.357.355a1 1 0 0 0 .356.26");
}

.fqeviqb2e {
  stop-color: var(--svg-color--1154b9, #1154B9);
}

.ft5dv1b6b {
  fill: none;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.g99cn0bet {
  stop-color: var(--svg-color--2965ce, #2965CE);
}

.gbiibgnkx {
  fill: var(--svg-color--000, #000);
  d: path("M14.914 5.92c0-.127.1-.227.227-.227a.226.226 0 0 1 .201.33h-.401a.2.2 0 0 1-.027-.104");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.gkw4sac_i {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.755H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.841 2.937-3.292 4.109-4.976s2.062-2.294 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.326-6.078 1.28");
}

.gq1i90b_a {
  stop-color: var(--svg-color--2965ce, #2965CE);
  stop-opacity: 0;
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.h1n_uss9t {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.111 5.607c.029.038-.03.084-.097.134s-.117.085-.145.048s.003-.11.07-.16s.144-.06.172-.022");
}

.h79f4xbxx {
  d: path("M15.493 5.867a.37.37 0 0 0-.103-.205l-.115.127l.052.1z");
}

.hlkj9uvrc {
  cx: 12.068px;
  cy: 6.038px;
  r: 0.74px;
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hsgktvbnq {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m14.004 5.911l-.236.754a.24.24 0 0 0 .231.31h.349a.24.24 0 0 0 .23-.31l-.235-.754c-.05-.167-.286-.167-.34 0");
}

.hv5ov_b9j {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M15.823 4.831h-.002l-.002-.002l-.005-.005l-.069-.047a1.26 1.26 0 0 0-.848-.164a.237.237 0 1 0 .074.468a.78.78 0 0 1 .523.097l.024.016l.004.003a.237.237 0 0 0 .3-.366");
}

.i3l5ycb1m {
  fill: var(--svg-color--e5b18a, #E5B18A);
  fill-rule: evenodd;
  d: path("M5.611 14.951a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jioe1_9gu {
  stop-color: var(--svg-color--5391be, #5391BE);
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jytpn83dl {
  d: path("m23.469 25.334l-.422-1.143l-2.351.536l2.225 1.099a.396.396 0 0 0 .547-.492");
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.keb1ysbtm {
  cx: 16.287px;
  cy: 6.038px;
  r: 0.74px;
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.kkuk5w_fi {
  stop-color: var(--svg-color--6096e0, #6096E0);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l1gl77bzm {
  cx: 28.864px;
  cy: 12.82px;
  r: 1.043px;
}

.l5g-5nb-e {
  stop-color: var(--svg-color--c3735d, #C3735D);
}

.l6aht38_w {
  fill: var(--svg-color--e5b18a, #E5B18A);
  fill-rule: evenodd;
  d: path("M5.404 14.146c0 .001.02-.027.083-.079a2.1 2.1 0 0 1 1.279-.412a.375.375 0 1 0 .024-.75a2.84 2.84 0 0 0-1.323.296a2.4 2.4 0 0 0-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.lb1zw-b1u {
  d: path("m7.305 27.355l1.172-2.39l1.766.304v1.039z");
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lh6x9gb0k {
  d: path("M16.782 13.457c-.65-1.28-1.166-3.185-1.443-4.424a.714.714 0 0 1 .588-.856c.447-.074.855.272.91.723c.205 1.698.95 3.373 1.445 4.682c.578 1.53.312 1.062.234 3.515c-.057 1.781 1.266 3.25 1.813 4.11l-.407.21c-.609-.828-2.203-2.945-2.203-4.851c0-1.791.063-1.14-.937-3.11");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0l7tb9r {
  stop-color: var(--svg-color--2b68b8, #2B68B8);
}

.ljh96mbpx {
  d: path("M6.126 14.894c.125-.138.398-.461.52-.606c.23 0 .91-.066 1.198-.097c-.39.714-.84 1.004-1.074 1.195c-.316.21-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lsnj8--zq {
  fill: var(--svg-color--e0ab8d, #E0AB8D);
  d: path("M6.126 14.894c.125-.138.398-.461.52-.606c.23 0 .91-.066 1.198-.097c-.39.714-.84 1.004-1.074 1.195c-.316.21-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf22u5b0t {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.917 7.4a.11.11 0 0 0-.012-.141a.12.12 0 0 0-.14-.024c-.17.09-.372.14-.591.14s-.421-.05-.592-.14a.12.12 0 0 0-.14.025a.11.11 0 0 0-.012.14m1.487 0l-.041-.027zm0 0a.89.89 0 0 1-.743.398a.89.89 0 0 1-.744-.397m0 0l.042-.028m-.042.028l.042-.028m0 0a.84.84 0 0 0 .702.375a.84.84 0 0 0 .702-.375c.038-.058-.027-.124-.088-.093a1.3 1.3 0 0 1-.614.146a1.3 1.3 0 0 1-.615-.146c-.06-.03-.126.037-.087.093Z");
}

.mmnxzqoyz {
  d: path("M26.485 24.34c.981-2.28.626-3.888.055-5.014c-.474-.936-.003-1.663 1.018-1.421c.737.174 1.364.694 1.54 1.43c.721 3.026-.313 6.182-3.582 7.817c-2.95 1.475-7.854 1.593-9.937 1.468c3 0 9.804-1.722 10.906-4.28");
}

.mvelyh28d {
  cx: 16.287px;
  cy: 6.038px;
  r: 0.441px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.ni4ip04et {
  cx: 16.287px;
  cy: 6.038px;
  r: 0.441px;
}

.nm46fkmyg {
  d: path("M17.568 10.284a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.793-.235-2.546-1.589-3.593c-1.381-1.068-2.68-1.257-4.203-1.257h-.39c-.157 1.285.25 2.192.606 2.671");
}

.nxcp0hivj {
  stop-color: var(--svg-color--3794e2, #3794E2);
}

.o-_kuhk7b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.91 4.767c.19-.033.562-.024.82.177");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.ob_pqhb0g {
  fill-rule: evenodd;
  d: path("M5.404 14.146c0 .001.02-.027.083-.079a2.1 2.1 0 0 1 1.279-.412a.375.375 0 1 0 .024-.75a2.84 2.84 0 0 0-1.323.296a2.4 2.4 0 0 0-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.oipf0m4co {
  stop-color: var(--svg-color--4861ab, #4861AB);
  stop-opacity: 0;
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.ow034zbkg {
  d: path("M13.565 5.873c0-.128-.104-.213-.132-.239l-.128.124l.079.16z");
}

.p70sstpth {
  d: path("m14.004 5.911l-.236.754a.24.24 0 0 0 .231.31h.349a.24.24 0 0 0 .23-.31l-.235-.754c-.05-.167-.286-.167-.34 0");
}

.p79aa0p9z {
  stop-color: var(--svg-color--3066bf, #3066BF);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkq4odbli {
  d: path("M12.759 11.66c-.432-1.716.169-3.162.507-3.485l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.257c1.354 1.047 1.622 2.8 1.589 3.593a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.274-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.512 1.212 3.519c.546 1.484-.11 2.953.375 4.484c.377 1.192 1.203 2.419 1.636 2.921a.04.04 0 0 1-.013.063l-1.834.851a.04.04 0 0 1-.048-.01c-1.848-2.157-2.5-3.825-2.562-3.989s-.23-.531-.574-.531c-.275 0-.59.352-.809.73l-4.667 7.137a.05.05 0 0 1-.056.021l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.164 4.542-9.51 4.773-10.058c.21-.5.181-.916.14-1.086c-.03-.13-.218-.71-.585-2.172");
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.q_tlouv3l {
  d: path("M13.204 5.524a.396.396 0 0 0-.381.5h.764a.398.398 0 0 0-.383-.5");
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qbgflqb2s {
  d: path("M15.14 5.524a.396.396 0 0 1 .382.5h-.765a.397.397 0 0 1 .383-.5");
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qhb9xl9dj {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m12.5 4.832l.002-.002l.006-.005l.068-.047a1.26 1.26 0 0 1 .848-.164a.237.237 0 1 1-.073.468a.78.78 0 0 0-.523.097l-.025.016l-.003.003a.237.237 0 0 1-.301-.365");
}

.qrfzq6pjd {
  stop-color: var(--svg-color--ca8b81, #CA8B81);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r0iiaeguw {
  stop-color: var(--svg-color--3168c8, #3168C8);
  stop-opacity: 0;
}

.rc1e7ccwp {
  stop-color: var(--svg-color--bc787e, #BC787E);
}

.rczvpztto {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.816px;
  rx: 0.299px;
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rp7oudbsr {
  fill: var(--svg-color--3086d6, #3086D6);
  d: path("M10.684 11.702c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.031c.3-.027 1.148-.11 2.5-.719c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.386c-.376 1.03-1.005 2.246-2.38 3.261");
}

.rudb12k0p {
  cx: 26.86px;
  cy: 10.734px;
  r: 0.914px;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s3qfvabch {
  fill-rule: evenodd;
  d: path("M5.25 14.674q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.srov_gb6c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.595 4.997c.145-.128.462-.263.855-.2");
}

.szaxszpjh {
  cx: 13.085px;
  cy: 5.693px;
  rx: 0.173px;
  ry: 0.087px;
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
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

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tvn1pe_ym {
  cx: 12.068px;
  cy: 6.038px;
  r: 0.441px;
}

.u6gia-bos {
  stop-color: var(--svg-color--418dd5, #418DD5);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.uajw-acut {
  fill-rule: evenodd;
  d: path("M5.611 14.951a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.upbi0xbpg {
  stop-color: var(--svg-color--9f6e75, #9F6E75);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v-ga10f4f {
  d: path("M10.684 11.702c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.031c.3-.027 1.148-.11 2.5-.719c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.386c-.376 1.03-1.005 2.246-2.38 3.261");
}

.v0khcu8ni {
  d: path("M15.111 5.607c.029.038-.03.084-.097.134s-.117.085-.145.048s.003-.11.07-.16s.144-.06.172-.022");
}

.v4i9n53vy {
  stop-color: var(--svg-color--f2b790, #F2B790);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9a_2379o {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m16.31 3.165l.19.095a.87.87 0 0 1 .453.946l-.262 1.348c-.023.139-.115.233-.254.236h-.008s.024-.402.048-.638c.02-.192-.014-.251-.19-.426a.56.56 0 0 1-.167-.378v-.379a.255.255 0 0 0-.19-.236a7.3 7.3 0 0 0-1.737-.19c-.856 0-1.45.119-1.736.19a.23.23 0 0 0-.19.236v.379a.47.47 0 0 1-.167.378l-.071.07c-.095.072-.143.214-.143.332c.024.26.048.639.048.639l-.022-.001a.28.28 0 0 1-.264-.236l-.261-1.348a.905.905 0 0 1 .475-.922l.19-.095c.12-.071.238-.166.357-.26l.428-.45a.87.87 0 0 1 .976-.142c.238.071.5.071.737 0a1.07 1.07 0 0 1 1.047.237l.357.355a1 1 0 0 0 .357.26");
}

.vgauzicqp {
  stop-color: var(--svg-color--3168c8, #3168C8);
}

.vhkp_yb0t {
  stop-color: var(--svg-color--efba9f, #EFBA9F);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vpd4dcexx {
  stop-color: var(--svg-color--c88d87, #C88D87);
  stop-opacity: 0;
}

.vr3js9b3d {
  fill: var(--svg-color--e5b18a, #E5B18A);
  d: path("M7.602 12.783h.594c-.106.668.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.257.977-.3 1.258-.29");
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w80grmxvp {
  stop-color: var(--svg-color--ce8b73, #CE8B73);
}

.w9cb85b5x {
  d: path("M11.912 5.766h.022s-.024-.378-.048-.638c0-.118.048-.26.143-.331l.071-.071a.47.47 0 0 0 .167-.379V3.97a.23.23 0 0 1 .19-.236c.285-.071.88-.19 1.736-.19c.857 0 1.452.119 1.737.19c.095.023.19.118.19.236v.378a.56.56 0 0 0 .167.379c.222.156.209.242.19.426c-.024.236-.047.638-.047.638h.008l-.118 1.756c-.072.784-.688 1.331-1.424 1.331h-1.424c-.76 0-1.352-.547-1.423-1.331z");
}

.wa28pxbrb {
  stop-color: var(--svg-color--e7b091, #E7B091);
  stop-opacity: 0;
}

.wlm6gibod {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.112 5.403a.62.62 0 0 0-.6.47a.12.12 0 0 0 .118.15h.99a.102.102 0 0 0 .1-.12a.62.62 0 0 0-.608-.5");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.xhtyz4bzf {
  stop-color: var(--svg-color--e7b091, #E7B091);
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y60usm6nn {
  stop-color: var(--svg-color--46a5ef, #46A5EF);
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ybjx3ubtr {
  stop-color: var(--svg-color--f4c7a5, #F4C7A5);
}

.ydres4b4h {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("M21.985 27.34L7.61 28.84c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.335 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.yi5ln4bok {
  cx: 25.864px;
  cy: 14.769px;
  r: 1.293px;
}

.yrtrc6n_d {
  stop-color: var(--svg-color--54acfa, #54ACFA);
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.yswqv8bxv {
  stop-color: var(--svg-color--ca8b81, #CA8B81);
}

.yykgsohgs {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.232 5.403c.29 0 .535.2.601.47a.122.122 0 0 1-.119.15h-.989a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .607-.5");
}

.z91enii4f {
  fill-rule: evenodd;
  d: path("M7.127 13.55c-.941-.283-1.295.01-1.388.12a.375.375 0 0 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 0 1-.216.718");
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zh1fb4b2d {
  fill: var(--svg-color--000, #000);
  d: path("M13.43 5.92c0-.127-.1-.227-.226-.227a.226.226 0 0 0-.201.33h.4a.2.2 0 0 0 .028-.104");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zpgy93w4i {
  stop-color: var(--svg-color--b47c64, #B47C64);
}

.zrzxj2epv {
  stop-color: var(--svg-color--2b68b8, #2B68B8);
  stop-opacity: 0;
}

.zv22riybk {
  stop-color: var(--svg-color--bc787e, #BC787E);
  stop-opacity: 0;
}

.zvqcq9hxr {
  stop-color: var(--svg-color--57b4fd, #57B4FD);
  stop-opacity: 0;
}

</style>
