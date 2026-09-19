<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuElUxe)"><path class="gkw4sac_i"/><path fill="url(#iJDjdPr)" class="dcogs8bsh"/></g><path fill="url(#iLpdJie)" class="dcogs8bsh"/><path fill="url(#iitMz0C)" class="dcogs8bsh"/><path fill="url(#ihyYxWc)" class="dcogs8bsh"/><path fill="url(#i4bI9Be)" class="dcogs8bsh"/><g filter="url(#iRM5ajB)"><path class="ydres4b4h"/><path fill="url(#iSxDVke)" class="em-pjfbcg"/></g><path class="eh2k3qbwi"/><path fill="url(#iYkIQJb)" class="lb1zw-b1u"/><path fill="url(#icvlSzb)" class="lb1zw-b1u"/><path fill="url(#iguHF4j)" class="bjo3ledcq"/><path fill="url(#iN96uDc)" class="jytpn83dl"/><path fill="url(#iUS33xe)" class="jytpn83dl"/><g filter="url(#i55qFmo)"><path fill="url(#ivQ5kvQ)" class="b96gakb3t"/><path fill="url(#iIX8Bqc)" class="b96gakb3t"/></g><g filter="url(#iJhheke)"><circle fill="url(#iwKsY6b)" class="yi5ln4bok"/></g><g filter="url(#ijq8RIb)"><circle fill="url(#i2HlaPd)" class="l1gl77bzm"/></g><g filter="url(#i6xajHb)"><circle fill="url(#i5sPa2d)" class="rudb12k0p"/></g><rect fill="url(#io3Rqra)" transform="rotate(26.595 20.662 12.816)" class="rczvpztto"/><g filter="url(#i5qA43c)"><path fill="url(#icDPZUh)" class="fgw68gbhw"/></g><path class="vr3js9b3d"/><path fill="url(#iqoVeFr)" class="ao0db4b4r"/><g filter="url(#ixDB8Cb)"><path class="m0lp5chxg"/><path fill="url(#idY2wib)" class="v-ga10f4f"/><path fill="url(#iGncjRk)" class="v-ga10f4f"/></g><g filter="url(#i2TvZYb)"><path fill="url(#idazM7b)" class="pkq4odbli"/><path fill="url(#iihhPOc)" class="pkq4odbli"/><path fill="url(#iBJhk3c)" class="pkq4odbli"/></g><path fill="url(#iZ5ejEc)" class="nm46fkmyg"/><path fill="url(#i9Z2Ite)" class="nm46fkmyg"/><path clip-rule="evenodd" class="chp33qbnl"/><path fill="url(#ikKOiwb)" clip-rule="evenodd" class="z91enii4f"/><path clip-rule="evenodd" class="l6aht38_w"/><path fill="url(#irUvmQE)" clip-rule="evenodd" class="ob_pqhb0g"/><path clip-rule="evenodd" class="birzucbpr"/><path fill="url(#iR3cl0F)" clip-rule="evenodd" class="s3qfvabch"/><path clip-rule="evenodd" class="i3l5ycb1m"/><path fill="url(#iGGFh8b)" clip-rule="evenodd" class="uajw-acut"/><path class="lsnj8--zq"/><path fill="url(#i7j5mob)" class="ljh96mbpx"/><g filter="url(#iW90QEe)"><path fill="url(#icldLze)" class="mmnxzqoyz"/></g><g filter="url(#iwB3nCe)"><path fill="url(#iUAW8md)" class="lh6x9gb0k"/></g><g filter="url(#iudjRFd)"><path stroke="url(#iOJivJd)" class="e7zo4pl3x"/></g><path fill="url(#iDEsOJe)" class="ofbt04c9m"/><path fill="url(#iDt1UFC)" class="nyjo_g4vj"/><path fill="url(#ipms5me)" class="nyjo_g4vj"/><path fill="url(#iDt1UFC)" class="nyjo_g4vj"/><path fill="url(#ipms5me)" class="nyjo_g4vj"/><g filter="url(#iFfjXHc)"><path fill="url(#iqDkBOc)" class="n0ymxmfvb"/></g><path fill="url(#iBNBNyp)" class="n0ymxmfvb"/><path fill="url(#iSg0lob)" class="n0ymxmfvb"/><path fill="url(#ix7POxe)" class="n0ymxmfvb"/><path fill="url(#ia0uSbc)" class="n0ymxmfvb"/><path fill="url(#ihohlPd)" class="n0ymxmfvb"/><path fill="url(#i2LVcvb)" class="n0ymxmfvb"/><path fill="url(#iKeJDmb)" class="n0ymxmfvb"/><path fill="url(#iwskCec)" class="n0ymxmfvb"/><g filter="url(#i3muxjQ)"><path class="iojdt6qks"/></g><g filter="url(#i0rY60b)"><path fill="url(#ilI0jce)" class="yzhoip_3r"/><path fill="url(#iQrySkb)" class="yzhoip_3r"/><path fill="url(#ikBEFjc)" class="yzhoip_3r"/><path fill="url(#iSdOe5d)" class="yzhoip_3r"/></g><g filter="url(#iAREpwb)"><path stroke="url(#i0GkKZb)" class="iddcbtojx"/></g><path fill="url(#iM8WBQc)" class="v7lye3wjl"/><g filter="url(#ik2Xwdc)"><path fill="url(#iT5tu0c)" class="z75rvmbjd"/><path fill="url(#iLir4Uc)" class="z75rvmbjd"/><path fill="url(#iNwBnTP)" class="z75rvmbjd"/><path fill="url(#i2qqGEb)" class="z75rvmbjd"/><path fill="url(#igx528b)" class="z75rvmbjd"/></g><g filter="url(#i6jQAub)"><path class="iv8495lrh"/></g><g filter="url(#iqC5Jua)"><path class="tqf7hpwrf"/></g><g filter="url(#inXw7Zc)"><path fill="url(#iZj3KLc)" class="t-gjmp61t"/><path fill="url(#i5ZIX4b)" class="t-gjmp61t"/></g><g filter="url(#iAu3Zkb)" class="mc2zb0bvp"><path fill="url(#iLX5EFe)" class="lrmmxmb7j"/><path fill="url(#ix41QPb)" class="lrmmxmb7j"/><path fill="url(#ioCFRse)" class="lrmmxmb7j"/><path fill="url(#iGVV0Ic)" class="lrmmxmb7j"/><path fill="url(#itvrGHd)" class="lrmmxmb7j"/><path fill="url(#ie0sZpH)" class="lrmmxmb7j"/></g><path class="k-mn6laxt"/><path fill="url(#ibJrs0c)" class="rtr9c1byl"/><path class="o-q6xhdsa"/><g filter="url(#iuF2kfw)"><path class="uy0_7abue"/><path fill="url(#iHjVBWb)" class="wepkir8ir"/></g><g filter="url(#iWhrCGd)"><path fill="url(#iykAreb)" class="fmma2ebgi"/></g><path class="g1wqxtb1e"/><path fill="url(#iG4dprc)" class="w55s1l-1v"/><path class="wwh4aabvz"/><g filter="url(#iokmjQb)"><path fill="url(#i0Y4TJb)" class="r6-8k2lby"/></g><g filter="url(#iEfuASb)"><ellipse transform="rotate(-27.914 13.09 5.695)" class="m6-vc-blt"/><ellipse fill="url(#iNhPaiV)" transform="rotate(-27.914 13.09 5.695)" class="izg4nxb9e"/></g><path fill="url(#iPN6Iae)" class="x7h2kpbby"/><path fill="url(#iXmHWbc)" class="x7h2kpbby"/><path fill="url(#itpqUUX)" class="x7h2kpbby"/><path fill="url(#iQs76pT)" class="yo5ghrbuw"/><path fill="url(#ii2vHub)" class="yo5ghrbuw"/><g filter="url(#iIpsFib)"><path class="l1dwd264d"/></g><g filter="url(#iI0sGse)"><path class="ib8ehxbpj"/></g><defs><radialGradient id="iLpdJie" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.984 21.777)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="ihyYxWc" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -6.125 3.8162 2.21963 22.204 21.933)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="i4bI9Be" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.777)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iSxDVke" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.169 25.214)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iYkIQJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.76 25.146)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="xhtyz4bzf"/><stop offset="1" class="wa28pxbrb"/></radialGradient><radialGradient id="iUS33xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.48)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="iIX8Bqc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.744 2.822)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="iwKsY6b" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.214 11.14)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i2HlaPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.563)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i5sPa2d" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.167 9.176)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="io3Rqra" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.115)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="w80grmxvp"/><stop offset="1" class="l5g-5nb-e"/></radialGradient><radialGradient id="icDPZUh" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.198 10.928)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="ae5rwo7_n"/><stop offset="1" class="e8ax3tbne"/></radialGradient><radialGradient id="iqoVeFr" cx="0" cy="0" r="1" gradientTransform="matrix(-.01563 -.84376 1.95707 -.03625 7.865 15.04)" gradientUnits="userSpaceOnUse"><stop class="rc1e7ccwp"/><stop offset="1" class="zv22riybk"/></radialGradient><radialGradient id="idY2wib" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.925 6.72)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="yt5sdf2gy"/><stop offset="1" class="n0_4eow9o"/></radialGradient><radialGradient id="iGncjRk" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.332 10.556)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="nf0740e8o"/><stop offset="1" class="fltjd-k8p"/></radialGradient><radialGradient id="iihhPOc" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.432)" gradientUnits="userSpaceOnUse"><stop class="qfyn005sz"/><stop offset="1" class="inzu6lb7s"/></radialGradient><radialGradient id="iBJhk3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09375 -2.46875 0 13.766 8.245)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="fu31k5bmq"/><stop offset="1" class="zkqd2ycat"/></radialGradient><radialGradient id="i9Z2Ite" cx="0" cy="0" r="1" gradientTransform="rotate(24.436 -15.54 48.352)scale(3.39814 2.30082)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="s41d30h-g"/><stop offset="1" class="woc0miqaj"/></radialGradient><radialGradient id="ikKOiwb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.216 6.135 5.686)scale(1.55003 1.68911)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".69" class="qrfzq6pjd"/></radialGradient><radialGradient id="irUvmQE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24388 -.94214 1.33264 -1.75944 5.77 14.697)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".769" class="qrfzq6pjd"/></radialGradient><radialGradient id="iR3cl0F" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23007 -1.01775 1.46904 -1.7755 5.598 15.262)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".769" class="qrfzq6pjd"/></radialGradient><radialGradient id="iGGFh8b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04688 -.89062 1.29178 -1.51843 5.802 15.495)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="yswqv8bxv"/><stop offset=".769" class="qrfzq6pjd"/></radialGradient><radialGradient id="i7j5mob" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.787)" gradientUnits="userSpaceOnUse"><stop class="vhkp_yb0t"/><stop offset="1" class="bg_l4vb3c"/></radialGradient><radialGradient id="icldLze" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.506 15.406)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iDEsOJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.26998 1.566 -1.8603 -.32072 16.596 6.487)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iDt1UFC" cx="0" cy="0" r="1" gradientTransform="rotate(64.592 .629 12.576)scale(1.31546 .59794)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="ipms5me" cx="0" cy="0" r="1" gradientTransform="matrix(.07944 .52886 -.46392 .06969 12.074 6.522)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iqDkBOc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31629 0 0 -4.0975 15.421 6.143)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iSg0lob" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.85753 -4.85074 0 14.372 3.41)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="dqi7sbofo"/><stop offset="1" class="w2m0zu1wm"/></radialGradient><radialGradient id="ix7POxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59411 .73521 0 15.262 5.647)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ia0uSbc" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 9.243 -3.462)scale(.48956 .53275)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="ihohlPd" cx="0" cy="0" r="1" gradientTransform="matrix(.5347 0 0 2.71777 12.015 6.314)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="i2LVcvb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15851 -1.61897 .3667 .2624 11.584 4.814)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iKeJDmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06939 -4.53833 4.99911 -1.17796 14.109 7.947)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iwskCec" cx="0" cy="0" r="1" gradientTransform="rotate(19.415 -3.464 45.851)scale(.96065 .57629)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="i0GkKZb" cx="0" cy="0" r="1" gradientTransform="matrix(.15382 -.27446 .79868 .44761 13.678 7.6)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="iM8WBQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.31933 1.28477 0 14.177 7.711)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iLir4Uc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.60951 2.85174 0 11.86 5.442)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iNwBnTP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.60951 2.85174 0 16.331 5.442)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="i2qqGEb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44073 -.54955 .29268 -.76729 15.998 2.662)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="igx528b" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 5.14 13.286)scale(.76676 1.77544)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iZj3KLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68673 .60859 -.16938 -.46946 14.29 2.595)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="i5ZIX4b" cx="0" cy="0" r="1" gradientTransform="matrix(1.42587 -2.25763 2.50122 1.57971 11.771 4.704)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iLX5EFe" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -5.435 69.197)scale(1.54153 .86213)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="ix41QPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95198 -1.64099 .91517 -.53091 16.45 5.15)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="ioCFRse" cx="0" cy="0" r="1" gradientTransform="matrix(-.57925 -.97577 .6989 -.4149 16.175 5.016)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iGVV0Ic" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 7.97 2.493)scale(2.18636 2.36354)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="itvrGHd" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 6.743 7.312)scale(.17779 .81282)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="ie0sZpH" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 7.06 6.04)scale(1.88369 4.8575)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="ibJrs0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35947 -.57178 0 15.144 5.737)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iHjVBWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10255 -.13215 .18193 -.14118 15.043 5.774)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iG4dprc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35949 -.5718 0 13.21 5.737)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iNhPaiV" cx="0" cy="0" r="1" gradientTransform="matrix(-.00342 -.21847 .26261 -.00411 13.083 5.834)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXmHWbc" cx="0" cy="0" r="1" gradientTransform="matrix(.27849 .99392 -.94828 .2657 16.224 5.743)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="itpqUUX" cx="0" cy="0" r="1" gradientTransform="matrix(.34904 -.479 .4015 .29257 16.383 5.985)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="ii2vHub" cx="0" cy="0" r="1" gradientTransform="matrix(-.74215 -.10853 .1067 -.7296 12 6.029)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><filter id="iuElUxe" width="23.977" height="13.398" x="6.016" y="16.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/></filter><filter id="iRM5ajB" width="20.681" height="10.082" x="6.11" y="20.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".75"/></filter><filter id="i55qFmo" width="24.344" height="8.644" x="2.007" y="21.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/></filter><filter id="iJhheke" width="2.686" height="2.686" x="24.571" y="13.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/></filter><filter id="ijq8RIb" width="2.186" height="2.186" x="27.821" y="11.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/></filter><filter id="i6xajHb" width="1.928" height="1.928" x="25.946" y="9.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/></filter><filter id="i5qA43c" width="2.857" height="2.898" x="20.532" y="12.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.462745 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/></filter><filter id="ixDB8Cb" width="5.571" height="6.952" x="7.773" y="7.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.305882 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/></filter><filter id="i2TvZYb" width="14.97" height="18.153" x="8.427" y="7.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.521569 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/></filter><filter id="iW90QEe" width="17.737" height="14.8" x="13.579" y="15.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation="1"/></filter><filter id="iwB3nCe" width="6.506" height="14.75" x="14.572" y="7.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".375"/></filter><filter id="iudjRFd" width="5.506" height="5.421" x="17.991" y="7.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".3"/></filter><filter id="iFfjXHc" width="5.278" height="5.668" x="11.934" y="3.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23000" result="effect2_innerShadow_3987_23000"/></filter><filter id="i3muxjQ" width="2.777" height="3.251" x="12.67" y="4.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".5"/></filter><filter id="i0rY60b" width=".932" height="1.385" x="13.711" y="5.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".025"/></filter><filter id="iAREpwb" width="1.926" height=".975" x="13.214" y="7.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".05"/></filter><filter id="ik2Xwdc" width="5.703" height="3.981" x="11.326" y="1.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23000" result="effect2_innerShadow_3987_23000"/></filter><filter id="i6jQAub" width="1.092" height=".639" x="14.882" y="4.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/></filter><filter id="iqC5Jua" width="1.092" height=".632" x="12.553" y="4.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23000"/></filter><filter id="inXw7Zc" width="2.996" height="2.713" x="11.444" y="2.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".075"/></filter><filter id="iAu3Zkb" width="2.725" height="2.482" x="14.19" y="2.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".05"/></filter><filter id="iuF2kfw" width=".459" height=".419" x="14.763" y="5.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".05"/></filter><filter id="iWhrCGd" width=".617" height=".627" x="15.08" y="5.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".1"/></filter><filter id="iokmjQb" width=".659" height=".683" x="13.111" y="5.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".1"/></filter><filter id="iEfuASb" width=".515" height=".423" x="12.832" y="5.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".05"/></filter><filter id="iIpsFib" width=".867" height="1.333" x="11.365" y="5.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".125"/></filter><filter id="iI0sGse" width=".919" height="1.343" x="16.126" y="5.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23000" stdDeviation=".125"/></filter><linearGradient id="iJDjdPr" x1="7.172" x2="16.735" y1="29.37" y2="29.37" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iitMz0C" x1="16.86" x2="16.766" y1="30.277" y2="28.652" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="icvlSzb" x1="7.833" x2="8.372" y1="25.932" y2="26.112" gradientUnits="userSpaceOnUse"><stop offset=".283" class="v4i9n53vy"/><stop offset="1" class="atc_6-nza"/></linearGradient><linearGradient id="iguHF4j" x1="21.172" x2="19.469" y1="21.933" y2="23.019" gradientUnits="userSpaceOnUse"><stop class="ybjx3ubtr"/><stop offset="1" class="zpgy93w4i"/></linearGradient><linearGradient id="iN96uDc" x1="22.095" x2="23.329" y1="24.839" y2="26.12" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="ivQ5kvQ" x1="5.891" x2="25.735" y1="29.245" y2="22.339" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="idazM7b" x1="15.777" x2="15.777" y1="7.613" y2="25.573" gradientUnits="userSpaceOnUse"><stop class="nmvycabwt"/><stop offset=".978" class="xujwu-wlk"/></linearGradient><linearGradient id="iZ5ejEc" x1="22.329" x2="16.517" y1="11.931" y2="8.556" gradientUnits="userSpaceOnUse"><stop class="ku_swbhun"/><stop offset=".888" class="upowizugn"/></linearGradient><linearGradient id="iUAW8md" x1="17.826" x2="20.269" y1="8.167" y2="21.403" gradientUnits="userSpaceOnUse"><stop class="e95gaqibw"/><stop offset="1" class="mtqjbpbdp"/></linearGradient><linearGradient id="iOJivJd" x1="22.438" x2="18.766" y1="11.886" y2="7.995" gradientUnits="userSpaceOnUse"><stop class="yjjppjb0c"/><stop offset="1" class="fvilr_bly"/></linearGradient><linearGradient id="iBNBNyp" x1="16.462" x2="14.534" y1="6.89" y2="6.89" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="ilI0jce" x1="14.177" x2="14.556" y1="6.51" y2="6.51" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iQrySkb" x1="13.702" x2="14.178" y1="6.441" y2="6.468" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ikBEFjc" x1="14.177" x2="14.177" y1="6.687" y2="7.065" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iSdOe5d" x1="14.177" x2="14.177" y1="5.691" y2="5.877" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iT5tu0c" x1="16.554" x2="12.068" y1="3.634" y2="3.634" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iykAreb" x1="15.489" x2="15.35" y1="5.761" y2="5.846" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0Y4TJb" x1="13.54" x2="13.401" y1="5.761" y2="5.846" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPN6Iae" x1="17.029" x2="16.495" y1="5.773" y2="6.737" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iQs76pT" x1="11.585" x2="12.232" y1="6.085" y2="6.029" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-surfing-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.ae5rwo7_n {
  stop-color: var(--svg-color--f9caaa, #F9CAAA);
}

.ao0db4b4r {
  d: path("M7.602 12.783h.594c-.106.668.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.257.977-.3 1.258-.29");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.atc_6-nza {
  stop-color: var(--svg-color--f2b790, #F2B790);
  stop-opacity: 0;
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.b96gakb3t {
  d: path("M24.458 21.269L2.29 28.958a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.1 1.156-.157c5.922-2.015 17.406-5.859 18.176-6.199c.443-.195.511-.378.605-.627v-.002c.094-.25.047-1.03-.5-1.453c-.437-.337-1.105-.185-1.355-.07");
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

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
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

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.dcogs8bsh {
  d: path("M19.75 29.755H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.841 2.937-3.292 4.109-4.976s2.062-2.294 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.326-6.078 1.28");
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
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

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e7zo4pl3x {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.292c1.209-.02 3.782.828 4.104 4");
}

.e8ax3tbne {
  stop-color: var(--svg-color--e2ac93, #E2AC93);
}

.e95gaqibw {
  stop-color: var(--svg-color--ff965a, #FF965A);
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
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

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fgw68gbhw {
  d: path("M20.68 13.856c.256-.588.373-1.22.399-1.462l2.047.023c.046.27-.04.584-.079.704c.088.322.037.686 0 .828c-.054.226-.178.713-.238.86c-.074.184-.183.247-.348.23a.4.4 0 0 1-.148-.042a.3.3 0 0 0-.23-.019a.43.43 0 0 1-.227.019a.43.43 0 0 1-.204-.113a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.005a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.071c-.085.007-.183.003-.235-.04c-.098-.083-.219-.177.031-.747");
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.fltjd-k8p {
  stop-color: var(--svg-color--ff4a2b, #FF4A2B);
  stop-opacity: 0;
}

.fmma2ebgi {
  d: path("M15.497 5.869a.37.37 0 0 0-.102-.205l-.115.126l.052.101z");
}

.ft5dv1b6b {
  fill: none;
}

.fu31k5bmq {
  stop-color: var(--svg-color--ff5714, #FF5714);
}

.fvilr_bly {
  stop-color: var(--svg-color--ff9e61, #FF9E61);
  stop-opacity: 0;
}

.g1wqxtb1e {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.118 5.406a.62.62 0 0 0-.6.469a.12.12 0 0 0 .118.15h.989a.102.102 0 0 0 .1-.12a.62.62 0 0 0-.607-.5");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
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

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
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

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
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

.i3l5ycb1m {
  fill: var(--svg-color--e5b18a, #E5B18A);
  fill-rule: evenodd;
  d: path("M5.611 14.951a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ib8ehxbpj {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("m16.376 6.449l.049-.843a.423.423 0 0 1-.05.843");
}

.iddcbtojx {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m14.879 7.374l.062.041a.136.136 0 0 0-.015-.173a.14.14 0 0 0-.169-.028a1.25 1.25 0 0 1-.58.138c-.213 0-.412-.05-.579-.137a.14.14 0 0 0-.17.028a.136.136 0 0 0-.014.173a.91.91 0 0 0 .763.407c.32 0 .603-.163.765-.408zm0 0a.84.84 0 0 1-.702.374a.84.84 0 0 1-.701-.374c-.038-.055.027-.124.088-.093c.177.093.389.146.613.146c.228 0 .437-.053.614-.146c.061-.03.126.035.088.093Z");
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.inzu6lb7s {
  stop-color: var(--svg-color--ff3e28, #FF3E28);
  stop-opacity: 0;
}

.iojdt6qks {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m13.986 5.994l-.306.734c-.045.167.063.335.215.335h.326c.153 0 .26-.17.216-.335l-.22-.815c-.048-.18-.181-.1-.23.081");
}

.iv8495lrh {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M15.831 4.823a.8.8 0 0 0-.304-.182c-.135-.043-.304-.054-.538-.026a.123.123 0 0 0 .03.244c.213-.026.344-.012.434.016a.6.6 0 0 1 .217.133a.123.123 0 1 0 .161-.185");
}

.izg4nxb9e {
  cx: 13.09px;
  cy: 5.695px;
  rx: 0.172px;
  ry: 0.087px;
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jytpn83dl {
  d: path("m23.469 25.334l-.422-1.143l-2.351.536l2.225 1.099a.396.396 0 0 0 .547-.492");
}

.k-mn6laxt {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.237 5.406c.29 0 .534.199.6.469a.12.12 0 0 1-.118.15h-.99a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .608-.5");
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.ku_swbhun {
  stop-color: var(--svg-color--ff8444, #FF8444);
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l1dwd264d {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M11.945 5.613a.424.424 0 0 0 .037.832a35 35 0 0 1-.037-.832");
}

.l1gl77bzm {
  cx: 28.864px;
  cy: 12.82px;
  r: 1.043px;
}

.l5g-5nb-e {
  stop-color: var(--svg-color--c3735d, #C3735D);
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l6aht38_w {
  fill: var(--svg-color--e5b18a, #E5B18A);
  fill-rule: evenodd;
  d: path("M5.404 14.146c0 .001.02-.027.083-.079a2.1 2.1 0 0 1 1.279-.412a.375.375 0 1 0 .024-.75a2.84 2.84 0 0 0-1.323.296a2.4 2.4 0 0 0-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
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

.lrmmxmb7j {
  d: path("m16.487 5.15l-.013-.28a.65.65 0 0 0-.623-.632h-.62a1.07 1.07 0 0 1-.94-.558s.318-.921.848-.802c.386.087.8.224 1.117.43c.773.505.638 1.413.231 1.841");
}

.lsnj8--zq {
  fill: var(--svg-color--e0ab8d, #E0AB8D);
  d: path("M6.126 14.894c.125-.138.398-.461.52-.606c.23 0 .91-.066 1.198-.097c-.39.714-.84 1.004-1.074 1.195c-.316.21-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.m0lp5chxg {
  fill: var(--svg-color--ff702b, #FF702B);
  d: path("M10.684 11.702c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.031c.3-.027 1.148-.11 2.5-.719c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.386c-.376 1.03-1.005 2.246-2.38 3.261");
}

.m6-vc-blt {
  cx: 13.09px;
  cy: 5.695px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.172px;
  ry: 0.087px;
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mmnxzqoyz {
  d: path("M26.485 24.34c.981-2.28.626-3.888.055-5.014c-.474-.936-.003-1.663 1.018-1.421c.737.174 1.364.694 1.54 1.43c.721 3.026-.313 6.182-3.582 7.817c-2.95 1.475-7.854 1.593-9.937 1.468c3 0 9.804-1.722 10.906-4.28");
}

.mtqjbpbdp {
  stop-color: var(--svg-color--ff8064, #FF8064);
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n0_4eow9o {
  stop-color: var(--svg-color--ff875c, #FF875C);
  stop-opacity: 0;
}

.n0ymxmfvb {
  d: path("M12.04 7.368c.114.865.85 1.51 1.721 1.51h.836c.872 0 1.608-.645 1.722-1.51c.052-.834.105-1.666.143-2.5a.64.64 0 0 0-.61-.634h-.621c-.423 0-.806-.25-.98-.64a.29.29 0 0 0-.273-.185h-.564c-.817 0-1.48.67-1.48 1.497c0 .825.052 1.636.106 2.462");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.nf0740e8o {
  stop-color: var(--svg-color--ff4a2b, #FF4A2B);
}

.nm46fkmyg {
  d: path("M17.568 10.284a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.793-.235-2.546-1.589-3.593c-1.381-1.068-2.68-1.257-4.203-1.257h-.39c-.157 1.285.25 2.192.606 2.671");
}

.nmvycabwt {
  stop-color: var(--svg-color--ff7a3c, #FF7A3C);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nyjo_g4vj {
  d: path("M12.023 6.697a.73.73 0 0 1-.4-.137v.413a.96.96 0 0 0 .594.894a1.8 1.8 0 0 1-.154-.522z");
}

.o-q6xhdsa {
  fill: var(--svg-color--000, #000);
  d: path("M14.919 5.92c0-.125.1-.225.226-.225a.225.225 0 0 1 .2.33h-.4a.2.2 0 0 1-.026-.104");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
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

.ofbt04c9m {
  d: path("M16.331 6.697a.73.73 0 0 0 .401-.137v.413a.96.96 0 0 1-.594.894q.113-.24.153-.522z");
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkq4odbli {
  d: path("M12.759 11.66c-.432-1.716.169-3.162.507-3.485l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.257c1.354 1.047 1.622 2.8 1.589 3.593a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.274-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.512 1.212 3.519c.546 1.484-.11 2.953.375 4.484c.377 1.192 1.203 2.419 1.636 2.921a.04.04 0 0 1-.013.063l-1.834.851a.04.04 0 0 1-.048-.01c-1.848-2.157-2.5-3.825-2.562-3.989s-.23-.531-.574-.531c-.275 0-.59.352-.809.73l-4.667 7.137a.05.05 0 0 1-.056.021l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.164 4.542-9.51 4.773-10.058c.21-.5.181-.916.14-1.086c-.03-.13-.218-.71-.585-2.172");
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qfyn005sz {
  stop-color: var(--svg-color--ff3e28, #FF3E28);
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qrfzq6pjd {
  stop-color: var(--svg-color--ca8b81, #CA8B81);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r6-8k2lby {
  d: path("M13.57 5.874c0-.127-.103-.212-.131-.238l-.128.123l.079.16z");
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

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rtr9c1byl {
  d: path("M15.145 5.526a.395.395 0 0 1 .381.5h-.764a.397.397 0 0 1 .383-.5");
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

.s41d30h-g {
  stop-color: var(--svg-color--fe5346, #FE5346);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.t-gjmp61t {
  d: path("m14.28 3.655l-.029-.06a.29.29 0 0 0-.273-.186h-.564c-.817 0-1.48.67-1.48 1.497v.122c-.15-.114-.34-.356-.34-.748c0-.474.346-.715.567-.868c.063-.043.115-.08.147-.112l.044-.046c.155-.165.43-.457.912-.585q.11-.03.218-.045c.467-.072.808.346.808.819v.206z");
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tqf7hpwrf {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.666 4.775a1.23 1.23 0 0 1 .77-.16a.123.123 0 0 1-.03.244a.98.98 0 0 0-.647.148l-.007.005h-.002a.123.123 0 0 1-.15-.193z");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.uajw-acut {
  fill-rule: evenodd;
  d: path("M5.611 14.951a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.upowizugn {
  stop-color: var(--svg-color--ff783f, #FF783F);
}

.uy0_7abue {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.116 5.61c.028.037-.031.083-.098.133s-.116.085-.145.048s.004-.109.07-.159c.067-.05.144-.06.173-.022");
}

.v-ga10f4f {
  d: path("M10.684 11.702c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.031c.3-.027 1.148-.11 2.5-.719c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.386c-.376 1.03-1.005 2.246-2.38 3.261");
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v4i9n53vy {
  stop-color: var(--svg-color--f2b790, #F2B790);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7lye3wjl {
  d: path("M14.177 7.427c-.224 0-.436-.053-.613-.146c-.061-.03-.126.038-.088.093a.84.84 0 0 0 .701.374c.295 0 .553-.15.702-.374c.038-.058-.027-.124-.088-.093a1.3 1.3 0 0 1-.614.146");
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

.w2m0zu1wm {
  stop-color: var(--svg-color--ca786d, #CA786D);
}

.w55s1l-1v {
  d: path("M13.21 5.526a.395.395 0 0 0-.382.5h.764a.398.398 0 0 0-.383-.5");
}

.w80grmxvp {
  stop-color: var(--svg-color--ce8b73, #CE8B73);
}

.wa28pxbrb {
  stop-color: var(--svg-color--e7b091, #E7B091);
  stop-opacity: 0;
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wepkir8ir {
  d: path("M15.116 5.61c.028.037-.031.083-.098.133s-.116.085-.145.048s.004-.109.07-.159c.067-.05.144-.06.173-.022");
}

.woc0miqaj {
  stop-color: var(--svg-color--fe5346, #FE5346);
  stop-opacity: 0;
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wwh4aabvz {
  fill: var(--svg-color--000, #000);
  d: path("M13.435 5.92c0-.125-.1-.225-.226-.225a.225.225 0 0 0-.2.33h.4a.2.2 0 0 0 .026-.104");
}

.x7h2kpbby {
  d: path("M16.358 6.737q.046-.706.082-1.414a.713.713 0 0 1-.082 1.414");
}

.xhtyz4bzf {
  stop-color: var(--svg-color--e7b091, #E7B091);
}

.xujwu-wlk {
  stop-color: var(--svg-color--ff4d30, #FF4D30);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
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

.yjjppjb0c {
  stop-color: var(--svg-color--ff9e61, #FF9E61);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yo5ghrbuw {
  d: path("M11.938 5.32A.713.713 0 0 0 12 6.737a35 35 0 0 1-.06-1.417");
}

.yswqv8bxv {
  stop-color: var(--svg-color--ca8b81, #CA8B81);
}

.yt5sdf2gy {
  stop-color: var(--svg-color--ff875c, #FF875C);
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.yzhoip_3r {
  d: path("m14.008 5.827l-.236.814c-.048.168.068.335.231.335h.348c.164 0 .28-.17.231-.335l-.235-.814c-.05-.18-.286-.18-.34 0");
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.z75rvmbjd {
  d: path("M16.328 3.2a1.05 1.05 0 0 1 .515 1.585a.7.7 0 0 0-.12.387V5.7a.8.8 0 0 0-.296-.119l.035-.712a.64.64 0 0 0-.61-.634h-.621c-.423 0-.806-.25-.98-.64a.29.29 0 0 0-.273-.185h-.564c-.817 0-1.48.67-1.48 1.497l.014.681a.8.8 0 0 0-.32.117v-.532a.7.7 0 0 0-.12-.387a1.06 1.06 0 0 1-.063-1.084c.13-.244.339-.415.576-.499c.254-.09.47-.261.613-.492a1.03 1.03 0 0 1 1.28-.404a.66.66 0 0 0 .53 0a1.03 1.03 0 0 1 1.285.418c.136.226.35.39.6.476");
}

.z91enii4f {
  fill-rule: evenodd;
  d: path("M7.127 13.55c-.941-.283-1.295.01-1.388.12a.375.375 0 0 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 0 1-.216.718");
}

.zkqd2ycat {
  stop-color: var(--svg-color--ff5714, #FF5714);
  stop-opacity: 0;
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zpgy93w4i {
  stop-color: var(--svg-color--b47c64, #B47C64);
}

.zv22riybk {
  stop-color: var(--svg-color--bc787e, #BC787E);
  stop-opacity: 0;
}

</style>
