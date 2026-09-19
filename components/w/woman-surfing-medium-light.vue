<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iWNdR6b)"><path fill="url(#itHHpyd)" clip-rule="evenodd" class="pv0wmib5g"/><path fill="url(#i28b6ob)" clip-rule="evenodd" class="pv0wmib5g"/><path fill="url(#iAmg6Xi)" clip-rule="evenodd" class="pv0wmib5g"/><path fill="url(#iVrK9hc)" clip-rule="evenodd" class="pv0wmib5g"/><path fill="url(#iGEyMle)" clip-rule="evenodd" class="pv0wmib5g"/><path fill="url(#i0HWzxo)" clip-rule="evenodd" class="pv0wmib5g"/><path fill="url(#iNkxzKe)" clip-rule="evenodd" class="pv0wmib5g"/><path fill="url(#idZ9abe)" clip-rule="evenodd" class="pv0wmib5g"/><path fill="url(#iJx4Aqd)" clip-rule="evenodd" class="pv0wmib5g"/><path fill="url(#i8biKqd)" clip-rule="evenodd" class="pv0wmib5g"/></g><g filter="url(#iguUSQd)"><path class="gkw4sac_i"/><path fill="url(#iJDjdPr)" class="dcogs8bsh"/></g><path fill="url(#iLpdJie)" class="dcogs8bsh"/><path fill="url(#iitMz0C)" class="dcogs8bsh"/><path fill="url(#ihyYxWc)" class="dcogs8bsh"/><path fill="url(#i4bI9Be)" class="dcogs8bsh"/><g filter="url(#iHLfF5t)"><path class="ydres4b4h"/><path fill="url(#iSxDVke)" class="em-pjfbcg"/></g><path class="eh2k3qbwi"/><path fill="url(#iYkIQJb)" class="lb1zw-b1u"/><path fill="url(#icvlSzb)" class="lb1zw-b1u"/><path fill="url(#iguHF4j)" class="bjo3ledcq"/><path fill="url(#iN96uDc)" class="jytpn83dl"/><path fill="url(#iUS33xe)" class="jytpn83dl"/><g filter="url(#in1Eoub)"><path fill="url(#ivQ5kvQ)" class="b96gakb3t"/><path fill="url(#iIX8Bqc)" class="b96gakb3t"/></g><g filter="url(#icq5fJy)"><circle fill="url(#iwKsY6b)" class="yi5ln4bok"/></g><g filter="url(#iCnyqDe)"><circle fill="url(#i2HlaPd)" class="l1gl77bzm"/></g><g filter="url(#iylUvcb)"><circle fill="url(#i5sPa2d)" class="rudb12k0p"/></g><rect fill="url(#io3Rqra)" transform="rotate(26.595 20.662 12.816)" class="rczvpztto"/><g filter="url(#iselLzd)"><path fill="url(#icDPZUh)" class="fgw68gbhw"/></g><path class="vr3js9b3d"/><path fill="url(#iqoVeFr)" class="ao0db4b4r"/><g filter="url(#i0FfXJB)"><path class="ds30cn8jn"/><path fill="url(#i92Wmde)" class="v-ga10f4f"/><path fill="url(#i2F9C6c)" class="v-ga10f4f"/></g><g filter="url(#i7qVqwe)"><path fill="url(#ituQYvc)" class="pkq4odbli"/><path fill="url(#izlTtkb)" class="pkq4odbli"/><path fill="url(#iDMr6bd)" class="pkq4odbli"/></g><path fill="url(#i9OSjNb)" class="pkq4odbli"/><path fill="url(#igiT9oe)" class="nm46fkmyg"/><path fill="url(#ihTa3yb)" class="nm46fkmyg"/><path clip-rule="evenodd" class="chp33qbnl"/><path fill="url(#ikKOiwb)" clip-rule="evenodd" class="z91enii4f"/><path clip-rule="evenodd" class="l6aht38_w"/><path fill="url(#irUvmQE)" clip-rule="evenodd" class="ob_pqhb0g"/><path clip-rule="evenodd" class="birzucbpr"/><path fill="url(#iR3cl0F)" clip-rule="evenodd" class="s3qfvabch"/><path clip-rule="evenodd" class="i3l5ycb1m"/><path fill="url(#iGGFh8b)" clip-rule="evenodd" class="uajw-acut"/><path class="lsnj8--zq"/><path fill="url(#i7j5mob)" class="ljh96mbpx"/><g filter="url(#iivX9tb)"><path fill="url(#icldLze)" class="mmnxzqoyz"/></g><g filter="url(#iZRCqcb)"><path fill="url(#iBnAUfc)" class="lh6x9gb0k"/></g><g filter="url(#iBBiU2d)"><path stroke="url(#i88b1oc)" class="e7zo4pl3x"/></g><g filter="url(#icxqaWt)"><path fill="url(#iaSCEWc)" class="fhwg6t2pp"/></g><g filter="url(#iPoGybp)"><path fill="url(#iHBciNc)" class="qi2kcsf3p"/><path fill="url(#i5a5wad)" class="qi2kcsf3p"/></g><g filter="url(#iIwKqsd)"><path class="sarw-6e3w"/><path fill="url(#iwbXqve)" class="hz431rbti"/></g><g filter="url(#iEpEm7d)"><path class="avn0nybnh"/><path fill="url(#iPxSiVc)" class="w920tibzd"/></g><g filter="url(#iYd9KJd)"><path fill="url(#ijUfy2A)" class="e1gb3ud4q"/><path fill="url(#ibT71cY)" class="e1gb3ud4q"/><path fill="url(#inu5c8G)" class="e1gb3ud4q"/><path fill="url(#i84T7we)" class="e1gb3ud4q"/><path fill="url(#iUtuTDb)" class="e1gb3ud4q"/><path fill="url(#ij0Bkrd)" class="e1gb3ud4q"/><path fill="url(#iG3p9hj)" class="e1gb3ud4q"/></g><path fill="url(#i0vCvrb)" class="uut2tzvfk"/><path fill="url(#iKpKv8c)" class="uut2tzvfk"/><g filter="url(#iAY0MOb)"><path class="ux8s3tb1k"/></g><g filter="url(#iUJ2X2d)"><path class="yyyd5xbmh"/><path fill="url(#ie28tQd)" class="czo3l-bis"/><path fill="url(#iUeV3Cc)" class="czo3l-bis"/><path fill="url(#i0Fdiuc)" class="czo3l-bis"/></g><g filter="url(#i0ZJ5PA)"><path stroke="url(#iWG6xte)" class="ti806hbyi"/></g><path class="an4cvzbvp"/><g filter="url(#itbpoUb)"><path class="lyvafw1qq"/></g><g filter="url(#i385Gme)"><path class="mh5_oyb-o"/></g><g filter="url(#igen7Cb)"><path class="qd44cykic"/></g><g filter="url(#iU1XpBe)"><path clip-rule="evenodd" class="qb-wrebmf"/></g><path class="doyz57bke"/><path fill="url(#iOaPwXd)" class="cvlq0tbfa"/><path class="bwfunibcz"/><g filter="url(#idSsnve)"><path class="r-tcg49me"/><path fill="url(#iN40fFG)" class="yigls-4cm"/></g><g filter="url(#ieaRJjY)"><path fill="url(#iTL5Fhe)" class="jvm8jpbje"/></g><path class="v3yl7qbiq"/><path fill="url(#i20M5qd)" class="cv-9qybkk"/><path class="g9ef_2jps"/><g filter="url(#i00fRGe)"><path fill="url(#isdMUzb)" class="jhqk5abft"/></g><g filter="url(#iOdYIKC)"><ellipse transform="rotate(-27.914 12.934 5.733)" class="hau9snbkd"/><ellipse fill="url(#iEfoeNA)" transform="rotate(-27.914 12.934 5.733)" class="czqv10bab"/></g><g filter="url(#iBj2lIc)"><path fill="url(#ie4oJid)" class="tz9lvlbes"/><path fill="url(#i0sdvse)" class="tz9lvlbes"/><path fill="url(#iArnKBe)" class="tz9lvlbes"/></g><defs><radialGradient id="i28b6ob" cx="0" cy="0" r="1" gradientTransform="matrix(.7809 -1.62186 3.69796 1.7805 16.136 8.65)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iAmg6Xi" cx="0" cy="0" r="1" gradientTransform="matrix(-.84597 2.4466 -2.29017 -.79188 13.733 6.834)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iVrK9hc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41161 1.09626 -1.34944 -1.73762 12.637 7.284)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iGEyMle" cx="0" cy="0" r="1" gradientTransform="matrix(-.45806 .65325 -.59378 -.41635 11.863 6.143)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="i0HWzxo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0437 -.23276 .34216 -1.53425 12.104 5.475)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iNkxzKe" cx="0" cy="0" r="1" gradientTransform="matrix(.96865 1.41913 -2.47658 1.69042 12.313 2.651)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="idZ9abe" cx="0" cy="0" r="1" gradientTransform="matrix(-.49557 .54063 -.75551 -.69254 16.496 3.47)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iJx4Aqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.82591 .24028 -.52281 -1.79707 17.397 5.662)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="i8biKqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41162 .60068 -.95707 -2.24915 17.277 6.909)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iLpdJie" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.984 21.777)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="ihyYxWc" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -6.125 3.8162 2.21963 22.204 21.933)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="i4bI9Be" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.777)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iSxDVke" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.169 25.214)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iYkIQJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.76 25.146)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="xhtyz4bzf"/><stop offset="1" class="wa28pxbrb"/></radialGradient><radialGradient id="iUS33xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.48)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="iIX8Bqc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.744 2.822)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="iwKsY6b" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.214 11.14)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i2HlaPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.563)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i5sPa2d" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.167 9.176)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="io3Rqra" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.115)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="w80grmxvp"/><stop offset="1" class="l5g-5nb-e"/></radialGradient><radialGradient id="icDPZUh" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.198 10.928)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="ae5rwo7_n"/><stop offset="1" class="e8ax3tbne"/></radialGradient><radialGradient id="iqoVeFr" cx="0" cy="0" r="1" gradientTransform="matrix(-.01563 -.84376 1.95707 -.03625 7.865 15.04)" gradientUnits="userSpaceOnUse"><stop class="rc1e7ccwp"/><stop offset="1" class="zv22riybk"/></radialGradient><radialGradient id="i92Wmde" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.925 6.72)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="hiph0yb8z"/><stop offset="1" class="nng6piu-d"/></radialGradient><radialGradient id="i2F9C6c" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.332 10.556)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="rjhj4ebho"/><stop offset="1" class="m0m5thktx"/></radialGradient><radialGradient id="izlTtkb" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.432)" gradientUnits="userSpaceOnUse"><stop class="zhpuq6bwb"/><stop offset="1" class="lrsiznbuc"/></radialGradient><radialGradient id="iDMr6bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49191 -2.04898 0 13.776 7.613)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="sz7_smkrr"/><stop offset="1" class="rqh0k2bpm"/></radialGradient><radialGradient id="i9OSjNb" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 -.625 2.3294 4.19292 17.339 21.245)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tn---htwd"/><stop offset="1" class="accyaboul"/></radialGradient><radialGradient id="ihTa3yb" cx="0" cy="0" r="1" gradientTransform="matrix(3.55689 1.62587 -1.10084 2.4083 18.61 10.76)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ns_rnx4db"/><stop offset="1" class="airol1bay"/><stop offset="1" class="cfcr9ub1k"/></radialGradient><radialGradient id="ikKOiwb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.216 6.135 5.686)scale(1.55003 1.68911)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".69" class="qrfzq6pjd"/></radialGradient><radialGradient id="irUvmQE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24388 -.94214 1.33264 -1.75944 5.77 14.697)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".769" class="qrfzq6pjd"/></radialGradient><radialGradient id="iR3cl0F" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23007 -1.01775 1.46904 -1.7755 5.598 15.262)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".769" class="qrfzq6pjd"/></radialGradient><radialGradient id="iGGFh8b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04688 -.89062 1.29178 -1.51843 5.802 15.495)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".769" class="qrfzq6pjd"/></radialGradient><radialGradient id="i7j5mob" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.787)" gradientUnits="userSpaceOnUse"><stop class="vhkp_yb0t"/><stop offset="1" class="bg_l4vb3c"/></radialGradient><radialGradient id="icldLze" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.506 15.406)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iHBciNc" cx="0" cy="0" r="1" gradientTransform="matrix(1.11503 -.50683 .61882 1.3614 15.843 6.24)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="i5a5wad" cx="0" cy="0" r="1" gradientTransform="matrix(.44676 .12765 -.0671 .23488 16.3 5.246)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iwbXqve" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 25.224 -41.868)scale(.58442)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iPxSiVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.54512 0 0 -.52144 11.943 6.044)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="ijUfy2A" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91343 1.34348 -1.79823 -3.89958 15.314 5.803)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="ibT71cY" cx="0" cy="0" r="1" gradientTransform="matrix(-.9451 .4999 -.42413 -.80185 14.884 6.115)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="inu5c8G" cx="0" cy="0" r="1" gradientTransform="matrix(.37492 -1.81211 2.29923 .4757 13.056 8.841)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i84T7we" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3318 -4.51646 0 14.033 5.674)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="gxm-dc6uw"/></radialGradient><radialGradient id="iUtuTDb" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 6.93 3.904)scale(2.59107 4.46103)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="ij0Bkrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51551 .74111 0 15.064 5.615)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iG3p9hj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60924 .69824 0 13.174 5.655)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="i0vCvrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 0 0 -1.98641 16.316 6.282)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iKpKv8c" cx="0" cy="0" r="1" gradientTransform="matrix(.51797 1.88988 -3.90536 1.07036 12.913 3.336)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="ie28tQd" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 9.687 -2.127)scale(1.14103 .65291)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iOaPwXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36345 -.5781 0 15.01 5.776)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iN40fFG" cx="0" cy="0" r="1" gradientTransform="matrix(-.10365 -.13357 .18389 -.1427 14.909 5.814)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i20M5qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36345 -.5781 0 13.056 5.776)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iEfoeNA" cx="0" cy="0" r="1" gradientTransform="matrix(-.00346 -.22081 .26542 -.00416 12.927 5.874)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ie4oJid" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.66 5.927)scale(2.18293 3.10404)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="i0sdvse" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 6.375 7.296)scale(1.48713 2.65458)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iArnKBe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56933 -2.82324 2.52721 -1.40478 14.611 5.467)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="iWNdR6b" width="6.978" height="7.478" x="10.669" y="1.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="iguUSQd" width="23.977" height="13.398" x="6.016" y="16.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="iHLfF5t" width="20.681" height="10.082" x="6.11" y="20.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".75"/></filter><filter id="in1Eoub" width="24.344" height="8.644" x="2.007" y="21.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="icq5fJy" width="2.686" height="2.686" x="24.571" y="13.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="iCnyqDe" width="2.186" height="2.186" x="27.821" y="11.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="iylUvcb" width="1.928" height="1.928" x="25.946" y="9.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="iselLzd" width="2.857" height="2.898" x="20.532" y="12.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.462745 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="i0FfXJB" width="5.571" height="6.952" x="7.773" y="7.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.219608 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="i7qVqwe" width="14.97" height="18.153" x="8.427" y="7.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.470588 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="iivX9tb" width="17.737" height="14.8" x="13.579" y="15.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation="1"/></filter><filter id="iZRCqcb" width="6.506" height="14.75" x="14.572" y="7.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".375"/></filter><filter id="iBBiU2d" width="5.506" height="5.421" x="17.991" y="7.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".3"/></filter><filter id="icxqaWt" width="1.592" height="1.692" x="11.213" y="5.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="iPoGybp" width="1.442" height="1.692" x="15.475" y="5.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="iIwKqsd" width="1.962" height="1.962" x="15.214" y="5.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".25"/></filter><filter id="iEpEm7d" width="1.762" height="1.762" x="11.062" y="5.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".2"/></filter><filter id="iYd9KJd" width="4.565" height="5.122" x="11.75" y="3.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="iAY0MOb" width="1.841" height="2.201" x="13.04" y="5.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".25"/></filter><filter id="iUJ2X2d" width="1.041" height="1.401" x="13.513" y="5.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".05"/></filter><filter id="i0ZJ5PA" width="1.879" height=".904" x="13.094" y="6.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".05"/></filter><filter id="itbpoUb" width="1.455" height=".576" x="14.345" y="5.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="i385Gme" width="1.455" height=".576" x="12.267" y="5.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="igen7Cb" width="1.209" height=".599" x="12.327" y="4.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="iU1XpBe" width="1.209" height=".599" x="14.754" y="4.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23001"/></filter><filter id="idSsnve" width=".462" height=".422" x="14.627" y="5.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".05"/></filter><filter id="ieaRJjY" width=".62" height=".629" x="14.948" y="5.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".1"/></filter><filter id="i00fRGe" width=".662" height=".686" x="12.957" y="5.474" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".1"/></filter><filter id="iOdYIKC" width=".519" height=".425" x="12.674" y="5.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".05"/></filter><filter id="iBj2lIc" width="4.069" height="2.665" x="12.509" y="2.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23001" stdDeviation=".075"/></filter><linearGradient id="itHHpyd" x1="16.136" x2="13.087" y1="2.929" y2="8.576" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iJDjdPr" x1="7.172" x2="16.735" y1="29.37" y2="29.37" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iitMz0C" x1="16.86" x2="16.766" y1="30.277" y2="28.652" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="icvlSzb" x1="7.833" x2="8.372" y1="25.932" y2="26.112" gradientUnits="userSpaceOnUse"><stop offset=".283" class="v4i9n53vy"/><stop offset="1" class="atc_6-nza"/></linearGradient><linearGradient id="iguHF4j" x1="21.172" x2="19.469" y1="21.933" y2="23.019" gradientUnits="userSpaceOnUse"><stop class="ybjx3ubtr"/><stop offset="1" class="zpgy93w4i"/></linearGradient><linearGradient id="iN96uDc" x1="22.095" x2="23.329" y1="24.839" y2="26.12" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="ivQ5kvQ" x1="5.891" x2="25.735" y1="29.245" y2="22.339" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="ituQYvc" x1="15.777" x2="15.777" y1="7.613" y2="25.573" gradientUnits="userSpaceOnUse"><stop class="t_t1uhgaw"/><stop offset="1" class="wlohty-lv"/></linearGradient><linearGradient id="igiT9oe" x1="23.651" x2="16.517" y1="12.509" y2="8.555" gradientUnits="userSpaceOnUse"><stop class="g55u5uboh"/><stop offset=".91" class="hq3x-3bjw"/></linearGradient><linearGradient id="iBnAUfc" x1="17.826" x2="20.269" y1="8.167" y2="21.403" gradientUnits="userSpaceOnUse"><stop class="xf-olmy6i"/><stop offset="1" class="nb49g6u5x"/></linearGradient><linearGradient id="i88b1oc" x1="22.438" x2="18.766" y1="11.886" y2="7.995" gradientUnits="userSpaceOnUse"><stop class="o-7v_hpgv"/><stop offset="1" class="qosi95ahb"/></linearGradient><linearGradient id="iaSCEWc" x1="11.213" x2="12.539" y1="6.083" y2="6.083" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iUeV3Cc" x1="13.564" x2="13.947" y1="6.615" y2="6.662" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="i0Fdiuc" x1="14.033" x2="14.033" y1="6.998" y2="6.725" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iWG6xte" x1="13.707" x2="13.909" y1="7.66" y2="7.269" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="iTL5Fhe" x1="15.359" x2="15.218" y1="5.8" y2="5.887" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isdMUzb" x1="13.388" x2="13.248" y1="5.8" y2="5.886" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-surfing-medium-light" /></template>
<style>
.accyaboul {
  stop-color: var(--svg-color--593b9d, #593B9D);
  stop-opacity: 0;
}

.ae5rwo7_n {
  stop-color: var(--svg-color--f9caaa, #F9CAAA);
}

.airol1bay {
  stop-color: var(--svg-color--815ecd, #815ECD);
  stop-opacity: 0;
}

.an4cvzbvp {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M14.033 7.348c-.233 0-.452-.056-.637-.154c-.063-.033-.13.04-.09.098a.865.865 0 0 0 1.455 0c.04-.061-.028-.131-.09-.098a1.35 1.35 0 0 1-.638.154");
}

.ao0db4b4r {
  d: path("M7.602 12.783h.594c-.106.668.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.257.977-.3 1.258-.29");
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atc_6-nza {
  stop-color: var(--svg-color--f2b790, #F2B790);
  stop-opacity: 0;
}

.avn0nybnh {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.943 6.525a.481.481 0 1 0 0-.962a.481.481 0 0 0 0 .962");
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b96gakb3t {
  d: path("M24.458 21.269L2.29 28.958a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.1 1.156-.157c5.922-2.015 17.406-5.859 18.176-6.199c.443-.195.511-.378.605-.627v-.002c.094-.25.047-1.03-.5-1.453c-.437-.337-1.105-.185-1.355-.07");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
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

.bwfunibcz {
  fill: var(--svg-color--000, #000);
  d: path("M14.783 5.962c0-.127.101-.229.229-.229a.228.228 0 0 1 .203.335h-.405a.2.2 0 0 1-.027-.106");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.cfcr9ub1k {
  stop-color: var(--svg-color--6845b9, #6845B9);
  stop-opacity: 0;
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

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cv-9qybkk {
  d: path("M13.055 5.563a.4.4 0 0 0-.386.505h.773a.403.403 0 0 0-.387-.505");
}

.cvlq0tbfa {
  d: path("M15.012 5.563a.4.4 0 0 1 .385.505h-.773a.4.4 0 0 1 .387-.505");
}

.czo3l-bis {
  d: path("m13.862 5.882l-.238.761a.242.242 0 0 0 .233.314h.352c.165 0 .282-.16.234-.314l-.239-.761c-.05-.169-.289-.169-.342 0");
}

.czqv10bab {
  cx: 12.934px;
  cy: 5.733px;
  rx: 0.174px;
  ry: 0.088px;
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

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.doyz57bke {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.104 5.44c.293 0 .54.202.607.475a.123.123 0 0 1-.12.153h-1a.103.103 0 0 1-.101-.122a.626.626 0 0 1 .614-.505");
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.ds30cn8jn {
  fill: var(--svg-color--7a5cb9, #7A5CB9);
  d: path("M10.684 11.702c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.031c.3-.027 1.148-.11 2.5-.719c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.386c-.376 1.03-1.005 2.246-2.38 3.261");
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e1gb3ud4q {
  d: path("m11.755 5.36l-.005-.138c.01-.425.258-.59.363-.644l.023-.01l.023-.009c.24-.11.432-.301.533-.553l.037-.087a.118.118 0 0 1 .207-.022c.321.47.859.75 1.428.75h1.443c.08 0 .484.038.509.596l-.054 1.377c-.055 1.255-1.035 2.098-2.232 2.098s-2.177-.843-2.232-2.098z");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
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

.eh2k3qbwi {
  fill: var(--svg-color--e3aa86, #E3AA86);
  d: path("m7.305 27.355l1.172-2.39l1.766.304v1.039z");
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.em-pjfbcg {
  d: path("M21.985 27.34L7.61 28.84c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.335 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fgw68gbhw {
  d: path("M20.68 13.856c.256-.588.373-1.22.399-1.462l2.047.023c.046.27-.04.584-.079.704c.088.322.037.686 0 .828c-.054.226-.178.713-.238.86c-.074.184-.183.247-.348.23a.4.4 0 0 1-.148-.042a.3.3 0 0 0-.23-.019a.43.43 0 0 1-.227.019a.43.43 0 0 1-.204-.113a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.005a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.071c-.085.007-.183.003-.235-.04c-.098-.083-.219-.177.031-.747");
}

.fhwg6t2pp {
  d: path("M11.934 6.765a.72.72 0 1 0 0-1.442a.72.72 0 0 0 0 1.442");
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g55u5uboh {
  stop-color: var(--svg-color--896ad2, #896AD2);
}

.g9ef_2jps {
  fill: var(--svg-color--000, #000);
  d: path("M13.284 5.962a.23.23 0 0 0-.23-.229a.228.228 0 0 0-.203.335h.405a.2.2 0 0 0 .027-.106");
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

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gxm-dc6uw {
  stop-color: var(--svg-color--a46e69, #A46E69);
}

.hau9snbkd {
  cx: 12.934px;
  cy: 5.733px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.174px;
  ry: 0.088px;
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hiph0yb8z {
  stop-color: var(--svg-color--8069a8, #8069A8);
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hq3x-3bjw {
  stop-color: var(--svg-color--8c6dd3, #8C6DD3);
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hz431rbti {
  d: path("M16.195 6.525a.481.481 0 1 0 0-.962a.481.481 0 0 0 0 .962");
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i3l5ycb1m {
  fill: var(--svg-color--e5b18a, #E5B18A);
  fill-rule: evenodd;
  d: path("M5.611 14.951a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jhqk5abft {
  d: path("M13.42 5.915c0-.13-.105-.215-.134-.241l-.129.125l.08.161z");
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jvm8jpbje {
  d: path("M15.367 5.91a.4.4 0 0 0-.103-.208l-.116.128l.052.102z");
}

.jytpn83dl {
  d: path("m23.469 25.334l-.422-1.143l-2.351.536l2.225 1.099a.396.396 0 0 0 .547-.492");
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
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

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lb1zw-b1u {
  d: path("m7.305 27.355l1.172-2.39l1.766.304v1.039z");
}

.lh6x9gb0k {
  d: path("M16.782 13.457c-.65-1.28-1.166-3.185-1.443-4.424a.714.714 0 0 1 .588-.856c.447-.074.855.272.91.723c.205 1.698.95 3.373 1.445 4.682c.578 1.53.312 1.062.234 3.515c-.057 1.781 1.266 3.25 1.813 4.11l-.407.21c-.609-.828-2.203-2.945-2.203-4.851c0-1.791.063-1.14-.937-3.11");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljh96mbpx {
  d: path("M6.126 14.894c.125-.138.398-.461.52-.606c.23 0 .91-.066 1.198-.097c-.39.714-.84 1.004-1.074 1.195c-.316.21-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.lrsiznbuc {
  stop-color: var(--svg-color--623f8d, #623F8D);
  stop-opacity: 0;
}

.lsnj8--zq {
  fill: var(--svg-color--e0ab8d, #E0AB8D);
  d: path("M6.126 14.894c.125-.138.398-.461.52-.606c.23 0 .91-.066 1.198-.097c-.39.714-.84 1.004-1.074 1.195c-.316.21-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lyvafw1qq {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.545 5.789c.119-.21.3-.375.688-.375c.17 0 .335.048.481.166c.12.097.104.221.011.268l-.249.142c-.292-.094-.615-.107-.931-.201");
}

.m0m5thktx {
  stop-color: var(--svg-color--572cad, #572CAD);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mh5_oyb-o {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.521 5.789c-.119-.21-.3-.375-.688-.375a.74.74 0 0 0-.48.166c-.121.097-.105.221-.012.268l.25.142c.291-.094.614-.107.93-.201");
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mmnxzqoyz {
  d: path("M26.485 24.34c.981-2.28.626-3.888.055-5.014c-.474-.936-.003-1.663 1.018-1.421c.737.174 1.364.694 1.54 1.43c.721 3.026-.313 6.182-3.582 7.817c-2.95 1.475-7.854 1.593-9.937 1.468c3 0 9.804-1.722 10.906-4.28");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.nb49g6u5x {
  stop-color: var(--svg-color--8b79ca, #8B79CA);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nm46fkmyg {
  d: path("M17.568 10.284a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.793-.235-2.546-1.589-3.593c-1.381-1.068-2.68-1.257-4.203-1.257h-.39c-.157 1.285.25 2.192.606 2.671");
}

.nng6piu-d {
  stop-color: var(--svg-color--8069a8, #8069A8);
  stop-opacity: 0;
}

.ns_rnx4db {
  stop-color: var(--svg-color--6845b9, #6845B9);
}

.o-7v_hpgv {
  stop-color: var(--svg-color--9577dc, #9577DC);
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

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkq4odbli {
  d: path("M12.759 11.66c-.432-1.716.169-3.162.507-3.485l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.257c1.354 1.047 1.622 2.8 1.589 3.593a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.274-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.512 1.212 3.519c.546 1.484-.11 2.953.375 4.484c.377 1.192 1.203 2.419 1.636 2.921a.04.04 0 0 1-.013.063l-1.834.851a.04.04 0 0 1-.048-.01c-1.848-2.157-2.5-3.825-2.562-3.989s-.23-.531-.574-.531c-.275 0-.59.352-.809.73l-4.667 7.137a.05.05 0 0 1-.056.021l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.164 4.542-9.51 4.773-10.058c.21-.5.181-.916.14-1.086c-.03-.13-.218-.71-.585-2.172");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pv0wmib5g {
  fill-rule: evenodd;
  d: path("M17.252 6.675a1.47 1.47 0 0 0 .025-1.224h.002a1.4 1.4 0 0 0-.126-.23V5.22a1.45 1.45 0 0 1-.236-.793v-.005c0-.816-.662-1.478-1.478-1.478a.24.24 0 0 1-.204-.104a1.48 1.48 0 0 0-2.403 0a.25.25 0 0 1-.204.104h-.038c-.799.02-1.44.675-1.44 1.478v.005c0 .28-.082.557-.236.793l-.001.002a1.48 1.48 0 0 0-.099 1.453a.23.23 0 0 1 0 .204a1.44 1.44 0 0 0 1.297 2.072h3.844a1.44 1.44 0 0 0 1.297-2.072a.23.23 0 0 1 0-.204M11.76 5.478h-.006l.537 1.055c.055 1.256.545 0 1.742 0s1.719 1.398 1.774.142l.509-1.432c-.024-.558-.428-.597-.509-.597h-1.443a1.73 1.73 0 0 1-1.428-.75a.118.118 0 0 0-.207.023l-.037.087a1.03 1.03 0 0 1-.533.553l-.023.01l-.022.009c-.106.054-.354.219-.363.644l.004.137z");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qb-wrebmf {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m15.705 5.042l-.062.103za.12.12 0 0 1-.124.207l-.002-.002l-.01-.005l-.04-.02a1 1 0 0 0-.154-.061a1 1 0 0 0-.48-.042a.12.12 0 0 1-.042-.236c.23-.04.443 0 .595.049a1.5 1.5 0 0 1 .25.107l.005.002z");
}

.qd44cykic {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.51 5.247l-.001.001a.12.12 0 0 1-.124-.206h.003l.004-.003l.014-.008l.052-.027c.044-.02.107-.048.184-.072c.152-.049.365-.09.595-.05a.12.12 0 1 1-.042.237c-.178-.031-.35 0-.48.042a1 1 0 0 0-.194.08z");
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qi2kcsf3p {
  d: path("M16.196 6.765a.72.72 0 1 0 0-1.442a.72.72 0 0 0 0 1.442");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qosi95ahb {
  stop-color: var(--svg-color--9577dc, #9577DC);
  stop-opacity: 0;
}

.qrfzq6pjd {
  stop-color: var(--svg-color--ca8b81, #CA8B81);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r-tcg49me {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M14.982 5.647c.028.038-.031.085-.1.135c-.067.05-.117.086-.145.048s.003-.11.07-.16c.068-.05.146-.06.175-.023");
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

.rjhj4ebho {
  stop-color: var(--svg-color--572cad, #572CAD);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rqh0k2bpm {
  stop-color: var(--svg-color--6f43ac, #6F43AC);
  stop-opacity: 0;
}

.rudb12k0p {
  cx: 26.86px;
  cy: 10.734px;
  r: 0.914px;
}

.s3qfvabch {
  fill-rule: evenodd;
  d: path("M5.25 14.674q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.sarw-6e3w {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M16.195 6.525a.481.481 0 1 0 0-.962a.481.481 0 0 0 0 .962");
}

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.sz7_smkrr {
  stop-color: var(--svg-color--6f43ac, #6F43AC);
}

.t_t1uhgaw {
  stop-color: var(--svg-color--8463ce, #8463CE);
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.ti806hbyi {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.033 7.348c-.233 0-.452-.056-.637-.154c-.063-.033-.13.04-.09.098a.865.865 0 0 0 1.455 0c.04-.061-.028-.131-.09-.098a1.35 1.35 0 0 1-.638.154Z");
}

.tn---htwd {
  stop-color: var(--svg-color--593b9d, #593B9D);
}

.tz9lvlbes {
  d: path("M13.763 2.554c-.508-.112-1.051.428-1.104.615c.69 1.622 1.752 1.468 2.928 1.337c.705-.078.781.243.841.398c-.195-1.817-1.509-2.095-2.665-2.35");
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.uajw-acut {
  fill-rule: evenodd;
  d: path("M5.611 14.951a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uut2tzvfk {
  d: path("M11.754 5.478h.006l-.005-.119l-.005-.137c.01-.425.258-.59.363-.644l.023-.01l.023-.009c.24-.11.432-.301.533-.553l.037-.087a.118.118 0 0 1 .207-.022c.321.47.859.75 1.428.75h1.443c.08 0 .484.038.509.596l-.054 1.377c-.055 1.255-1.035 2.098-2.232 2.098s-2.177-.843-2.232-2.098z");
}

.ux8s3tb1k {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m13.857 5.944l-.306.761a.242.242 0 0 0 .233.314h.352c.166 0 .282-.16.234-.314l-.238-.761c-.051-.169-.221-.169-.275 0");
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v-ga10f4f {
  d: path("M10.684 11.702c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.031c.3-.027 1.148-.11 2.5-.719c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.386c-.376 1.03-1.005 2.246-2.38 3.261");
}

.v3yl7qbiq {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.962 5.44a.626.626 0 0 0-.607.475c-.02.078.04.153.12.153h1a.103.103 0 0 0 .101-.122a.63.63 0 0 0-.614-.505");
}

.v4i9n53vy {
  stop-color: var(--svg-color--f2b790, #F2B790);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vhkp_yb0t {
  stop-color: var(--svg-color--efba9f, #EFBA9F);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vr3js9b3d {
  fill: var(--svg-color--e5b18a, #E5B18A);
  d: path("M7.602 12.783h.594c-.106.668.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.257.977-.3 1.258-.29");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w80grmxvp {
  stop-color: var(--svg-color--ce8b73, #CE8B73);
}

.w920tibzd {
  d: path("M11.943 6.525a.481.481 0 1 0 0-.962a.481.481 0 0 0 0 .962");
}

.wa28pxbrb {
  stop-color: var(--svg-color--e7b091, #E7B091);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wlohty-lv {
  stop-color: var(--svg-color--6247a5, #6247A5);
}

.xf-olmy6i {
  stop-color: var(--svg-color--9a7ce0, #9A7CE0);
}

.xhtyz4bzf {
  stop-color: var(--svg-color--e7b091, #E7B091);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.ybjx3ubtr {
  stop-color: var(--svg-color--f4c7a5, #F4C7A5);
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.ydres4b4h {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("M21.985 27.34L7.61 28.84c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.335 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yi5ln4bok {
  cx: 25.864px;
  cy: 14.769px;
  r: 1.293px;
}

.yigls-4cm {
  d: path("M14.982 5.647c.028.038-.031.085-.1.135c-.067.05-.117.086-.145.048s.003-.11.07-.16c.068-.05.146-.06.175-.023");
}

.yswqv8bxv {
  stop-color: var(--svg-color--ca8b81, #CA8B81);
}

.yyyd5xbmh {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m13.862 5.882l-.238.761a.242.242 0 0 0 .233.314h.352c.165 0 .282-.16.234-.314l-.239-.761c-.05-.169-.289-.169-.342 0");
}

.z91enii4f {
  fill-rule: evenodd;
  d: path("M7.127 13.55c-.941-.283-1.295.01-1.388.12a.375.375 0 0 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 0 1-.216.718");
}

.zhpuq6bwb {
  stop-color: var(--svg-color--623f8d, #623F8D);
}

.zpgy93w4i {
  stop-color: var(--svg-color--b47c64, #B47C64);
}

.zv22riybk {
  stop-color: var(--svg-color--bc787e, #BC787E);
  stop-opacity: 0;
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
