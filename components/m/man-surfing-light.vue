<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#inVSczb)"><path class="gkw4sac_i"/><path fill="url(#iJDjdPr)" class="dcogs8bsh"/></g><path fill="url(#iLpdJie)" class="dcogs8bsh"/><path fill="url(#iitMz0C)" class="dcogs8bsh"/><path fill="url(#ihyYxWc)" class="dcogs8bsh"/><path fill="url(#i4bI9Be)" class="dcogs8bsh"/><g filter="url(#iNeySTg)"><path class="ydres4b4h"/><path fill="url(#iSxDVke)" class="em-pjfbcg"/></g><path class="vu5of3bdl"/><path fill="url(#iN6QTPD)" class="lb1zw-b1u"/><path fill="url(#iAJyj9b)" class="lb1zw-b1u"/><path fill="url(#iQU1gjX)" class="bjo3ledcq"/><path fill="url(#iN96uDc)" class="jytpn83dl"/><path fill="url(#iUS33xe)" class="jytpn83dl"/><g filter="url(#iiM7ead)"><path fill="url(#ivQ5kvQ)" class="b96gakb3t"/><path fill="url(#iIX8Bqc)" class="b96gakb3t"/></g><g filter="url(#iNjkFJb)"><circle fill="url(#iwKsY6b)" class="yi5ln4bok"/></g><g filter="url(#iSXbAlQ)"><circle fill="url(#i2HlaPd)" class="l1gl77bzm"/></g><g filter="url(#iYnNykM)"><circle fill="url(#i5sPa2d)" class="rudb12k0p"/></g><rect fill="url(#irAWhYd)" transform="rotate(26.595 20.662 12.816)" class="rczvpztto"/><g filter="url(#icYeU8b)"><path fill="url(#iGqyHde)" class="fgw68gbhw"/></g><path class="vcpm8vbvg"/><path fill="url(#iPAEW7J)" class="ao0db4b4r"/><g filter="url(#iNSfxQc)"><path class="rp7oudbsr"/><path fill="url(#iRECIzb)" class="v-ga10f4f"/><path fill="url(#iPpqrPd)" class="v-ga10f4f"/></g><g filter="url(#iRZuwMc)"><path fill="url(#isMHdAd)" class="pkq4odbli"/><path fill="url(#i3g2fcO)" class="pkq4odbli"/><path fill="url(#iw6jNCd)" class="pkq4odbli"/></g><path fill="url(#iN6KJMd)" class="pkq4odbli"/><path fill="url(#i2W9LUc)" class="nm46fkmyg"/><path fill="url(#iQhotvd)" class="nm46fkmyg"/><path clip-rule="evenodd" class="r82a8ebvo"/><path fill="url(#ifkTDwd)" clip-rule="evenodd" class="z91enii4f"/><path clip-rule="evenodd" class="tcon8-qkz"/><path fill="url(#ieUi1be)" clip-rule="evenodd" class="ob_pqhb0g"/><path clip-rule="evenodd" class="h400q-4fl"/><path fill="url(#iQ4ESUd)" clip-rule="evenodd" class="s3qfvabch"/><path clip-rule="evenodd" class="i8-ofx0jr"/><path fill="url(#iCR8Ztd)" clip-rule="evenodd" class="uajw-acut"/><path class="zebje2bvd"/><path fill="url(#igWvqcd)" class="ljh96mbpx"/><g filter="url(#iIDBJPd)"><path fill="url(#icldLze)" class="mmnxzqoyz"/></g><g filter="url(#i8JWyAe)"><path fill="url(#inTSD3b)" class="lh6x9gb0k"/></g><g filter="url(#i3Rk17c)"><path stroke="url(#iqyR7Md)" class="e7zo4pl3x"/></g><g filter="url(#i1ndRNc)"><circle fill="url(#iwIKagb)" class="vkxqb2bnp"/></g><g filter="url(#iv97o4u)"><circle fill="url(#igKPToc)" class="h0qaawcfj"/></g><g filter="url(#iTVpKBz)"><circle fill="url(#iCZBvGJ)" class="prg3zrz8k"/><circle fill="url(#iKW3Oec)" class="prg3zrz8k"/></g><g filter="url(#ivG5Dke)"><circle class="o855rib8r"/><circle fill="url(#i3Np0hb)" class="s6fw_r1qg"/><circle fill="url(#iniLkYb)" class="s6fw_r1qg"/></g><g filter="url(#iNuuw5J)"><path fill="url(#ivcqxOe)" class="n06rbc_sp"/><path fill="url(#i1Vmxsb)" class="n06rbc_sp"/><path fill="url(#i4cGMRc)" class="n06rbc_sp"/><path fill="url(#i5OfPle)" class="n06rbc_sp"/><path fill="url(#i3mr5Vb)" class="n06rbc_sp"/><path fill="url(#itcM3we)" class="n06rbc_sp"/></g><g filter="url(#iVZBped)"><path fill="url(#ii9I4ky)" class="vovys4b_g"/></g><g filter="url(#i9syPmb)"><path class="r4b1-ibwp"/><path fill="url(#ipbmrnd)" class="mqkuen7rv"/><path fill="url(#iMJCyBe)" class="mqkuen7rv"/><path fill="url(#ihgxfnb)" class="mqkuen7rv"/><path fill="url(#i9ER91c)" class="mqkuen7rv"/></g><g filter="url(#i0wQLJb)"><path class="eakiiobyh"/></g><g filter="url(#iEj8vPh)"><path class="vnopehb9h"/><path fill="url(#iBemmJb)" class="b5iesbbmr"/><path fill="url(#ipZMrob)" class="b5iesbbmr"/><path fill="url(#iMMdted)" class="b5iesbbmr"/><path fill="url(#iXBIF3Z)" class="b5iesbbmr"/></g><path stroke="url(#iwDYsMe)" class="q8yoq8bts"/><g filter="url(#iKEndNb)"><path class="tggvabbvc"/></g><g filter="url(#iW8e5Ld)"><path class="efctcxbso"/></g><path class="txef72d1h"/><path fill="url(#i9o5dJe)" class="h3xvb7b2q"/><path class="agcr1zvqr"/><g filter="url(#ijkjqYb)"><path class="bv0rmnbrl"/><path fill="url(#ii1AJfZ)" class="i75s2ibjf"/></g><g filter="url(#i5O0Kmd)"><path fill="url(#ivPfn5d)" class="jrricjbwu"/></g><path class="ynrp46ydd"/><path fill="url(#iPxTZqe)" class="g3p53qx1q"/><path class="b54sc6tsh"/><g filter="url(#i7LUoOs)"><path fill="url(#iEjE9pb)" class="kych8tj7f"/></g><g filter="url(#i9QYfyc)"><ellipse transform="rotate(-27.914 13.083 5.693)" class="nyf_ntbrg"/><ellipse fill="url(#iRqB6Yc)" transform="rotate(-27.914 13.083 5.693)" class="wab8z-b3m"/></g><g filter="url(#isXttqd)"><path stroke="url(#i2LzEtb)" class="lsxdl_bbw"/></g><g filter="url(#ibfnkDb)"><path stroke="url(#i338qkc)" class="ki97a6qmk"/></g><g filter="url(#igwZPoS)"><path stroke="url(#iRLfEee)" class="auiuthgla"/></g><defs><radialGradient id="iLpdJie" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.984 21.777)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="ihyYxWc" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -6.125 3.8162 2.21963 22.204 21.933)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="i4bI9Be" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.777)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iSxDVke" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.169 25.214)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iN6QTPD" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.76 25.146)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="vxxc7i85i"/><stop offset="1" class="tu701m2xi"/></radialGradient><radialGradient id="iUS33xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.48)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="iIX8Bqc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.744 2.822)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="iwKsY6b" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.214 11.14)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i2HlaPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.563)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i5sPa2d" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.167 9.176)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="irAWhYd" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.115)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="jalmfobon"/><stop offset="1" class="fhgc0ib0i"/></radialGradient><radialGradient id="iGqyHde" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.198 10.928)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="gttado_ri"/><stop offset="1" class="s1_qcx0nn"/></radialGradient><radialGradient id="iPAEW7J" cx="0" cy="0" r="1" gradientTransform="matrix(-.01563 -.84376 1.95707 -.03625 7.865 15.04)" gradientUnits="userSpaceOnUse"><stop class="vevwxpb8j"/><stop offset="1" class="w9ndm1bxw"/></radialGradient><radialGradient id="iRECIzb" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.925 6.72)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="jioe1_9gu"/><stop offset="1" class="t5lf5ccyt"/></radialGradient><radialGradient id="iPpqrPd" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.332 10.556)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="fqeviqb2e"/><stop offset="1" class="to9zfdmjz"/></radialGradient><radialGradient id="i3g2fcO" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.432)" gradientUnits="userSpaceOnUse"><stop class="lj0l7tb9r"/><stop offset="1" class="zrzxj2epv"/></radialGradient><radialGradient id="iw6jNCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49191 -2.04898 0 13.776 7.613)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="vgauzicqp"/><stop offset="1" class="r0iiaeguw"/></radialGradient><radialGradient id="iN6KJMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.38038 -.82813 3.08645 5.14471 17.339 21.245)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="t502ec3cr"/><stop offset="1" class="oipf0m4co"/></radialGradient><radialGradient id="iQhotvd" cx="0" cy="0" r="1" gradientTransform="matrix(3.55689 1.62587 -.93464 2.0447 18.61 10.76)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="g99cn0bet"/><stop offset="1" class="gq1i90b_a"/><stop offset="1" class="airol1bay"/></radialGradient><radialGradient id="ifkTDwd" cx="0" cy="0" r="1" gradientTransform="rotate(-138.814 5.307 5.976)scale(1.66096 2.09285)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="s1mjb1beh"/><stop offset=".769" class="cd88em0te"/></radialGradient><radialGradient id="ieUi1be" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24388 -.94214 1.33264 -1.75944 5.77 14.697)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="s1mjb1beh"/><stop offset=".769" class="cd88em0te"/></radialGradient><radialGradient id="iQ4ESUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23007 -1.01775 1.46904 -1.7755 5.598 15.262)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="s1mjb1beh"/><stop offset=".769" class="cd88em0te"/></radialGradient><radialGradient id="iCR8Ztd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04688 -.89062 1.29178 -1.51843 5.802 15.495)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="s1mjb1beh"/><stop offset=".769" class="cd88em0te"/></radialGradient><radialGradient id="igWvqcd" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.787)" gradientUnits="userSpaceOnUse"><stop class="cl_02q7-e"/><stop offset="1" class="uzhwu5bek"/></radialGradient><radialGradient id="icldLze" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.506 15.406)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iwIKagb" cx="0" cy="0" r="1" gradientTransform="matrix(.77822 0 0 1.36189 11.326 6.038)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iKW3Oec" cx="0" cy="0" r="1" gradientTransform="matrix(.36661 -.26695 .3047 .41844 16.45 5.92)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="i3Np0hb" cx="0" cy="0" r="1" gradientTransform="matrix(.3642 -.66987 .39208 .21317 16.267 6.402)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iniLkYb" cx="0" cy="0" r="1" gradientTransform="matrix(.11498 .11382 -.14673 .14823 16.285 6.038)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="i1Vmxsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.18421 -5.67985 0 14.185 5.184)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="p7jmmxb2h"/><stop offset="1" class="uzkpn5btf"/></radialGradient><radialGradient id="i3mr5Vb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57964 .7134 0 15.212 5.474)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="itcM3we" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6168 .76705 0 13.19 5.459)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="ipbmrnd" cx="0" cy="0" r="1" gradientTransform="matrix(.3538 -1.31115 .48622 .1312 16.099 4.217)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iMJCyBe" cx="0" cy="0" r="1" gradientTransform="matrix(1.69618 .15609 -.08393 .91202 15.37 3.436)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ihgxfnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .74465 -1.15326 0 14.172 2.223)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="i9ER91c" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 13.674 -14.663)scale(1.69004 2.64774)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iXBIF3Z" cx="0" cy="0" r="1" gradientTransform="matrix(0 .08732 -.28053 0 14.317 6.75)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="i9o5dJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3597 -.57216 0 15.138 5.735)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ii1AJfZ" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 8.932 -.796)scale(.16772 .23091)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPxTZqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35973 -.57219 0 13.203 5.735)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRqB6Yc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00343 -.21906 .26332 -.00412 13.076 5.832)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="inVSczb" width="23.977" height="13.398" x="6.016" y="16.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="iNeySTg" width="20.681" height="10.082" x="6.11" y="20.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".75"/></filter><filter id="iiM7ead" width="24.344" height="8.644" x="2.007" y="21.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="iNjkFJb" width="2.686" height="2.686" x="24.571" y="13.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="iSXbAlQ" width="2.186" height="2.186" x="27.821" y="11.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="iYnNykM" width="1.928" height="1.928" x="25.946" y="9.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="icYeU8b" width="2.857" height="2.898" x="20.532" y="12.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.572549 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="iNSfxQc" width="5.571" height="6.952" x="7.773" y="7.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.396078 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="iRZuwMc" width="14.97" height="18.153" x="8.427" y="7.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.537255 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="iIDBJPd" width="17.737" height="14.8" x="13.579" y="15.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation="1"/></filter><filter id="i8JWyAe" width="6.506" height="14.75" x="14.572" y="7.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".375"/></filter><filter id="i3Rk17c" width="5.506" height="5.421" x="17.991" y="7.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".3"/></filter><filter id="i1ndRNc" width="1.681" height="1.481" x="11.326" y="5.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="iv97o4u" width="1.882" height="1.882" x="11.125" y="5.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".25"/></filter><filter id="iTVpKBz" width="1.731" height="1.731" x="15.545" y="5.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="ivG5Dke" width="1.882" height="1.882" x="15.344" y="5.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".25"/></filter><filter id="iNuuw5J" width="4.6" height="5.584" x="11.884" y="3.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="iVZBped" width="5.883" height="5.36" x="12.247" y="1.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation="1"/></filter><filter id="i9syPmb" width="5.588" height="3.667" x="11.378" y="2.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="i0wQLJb" width="2.28" height="2.689" x="12.925" y="5.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".375"/></filter><filter id="iEj8vPh" width=".932" height="1.289" x="13.706" y="5.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".025"/></filter><filter id="iKEndNb" width="1.461" height="1.053" x="14.696" y="4.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="iW8e5Ld" width="1.461" height="1.053" x="12.413" y="4.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23005"/></filter><filter id="ijkjqYb" width=".46" height=".42" x="14.757" y="5.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".05"/></filter><filter id="i5O0Kmd" width=".618" height=".628" x="15.074" y="5.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".1"/></filter><filter id="i7LUoOs" width=".66" height=".684" x="13.104" y="5.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".1"/></filter><filter id="i9QYfyc" width=".516" height=".424" x="12.825" y="5.481" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".05"/></filter><filter id="isXttqd" width="1.32" height=".691" x="14.658" y="4.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".1"/></filter><filter id="ibfnkDb" width="1.355" height=".716" x="12.344" y="4.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".1"/></filter><filter id="igwZPoS" width=".864" height="1.424" x="11.672" y="3.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23005" stdDeviation=".125"/></filter><linearGradient id="iJDjdPr" x1="7.172" x2="16.735" y1="29.37" y2="29.37" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iitMz0C" x1="16.86" x2="16.766" y1="30.277" y2="28.652" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="iAJyj9b" x1="7.833" x2="8.372" y1="25.932" y2="26.112" gradientUnits="userSpaceOnUse"><stop offset=".283" class="q2kjmzqur"/><stop offset="1" class="atc_6-nza"/><stop offset="1" class="h31kj0t6r"/></linearGradient><linearGradient id="iQU1gjX" x1="21.172" x2="19.469" y1="21.933" y2="23.019" gradientUnits="userSpaceOnUse"><stop class="ion1yqb0q"/><stop offset="1" class="r9287rbao"/></linearGradient><linearGradient id="iN96uDc" x1="22.095" x2="23.329" y1="24.839" y2="26.12" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="ivQ5kvQ" x1="5.891" x2="25.735" y1="29.245" y2="22.339" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="isMHdAd" x1="15.777" x2="15.777" y1="7.613" y2="25.573" gradientUnits="userSpaceOnUse"><stop class="nxcp0hivj"/><stop offset="1" class="p79aa0p9z"/></linearGradient><linearGradient id="i2W9LUc" x1="23.651" x2="16.517" y1="12.509" y2="8.555" gradientUnits="userSpaceOnUse"><stop class="y60usm6nn"/><stop offset=".91" class="u6gia-bos"/></linearGradient><linearGradient id="inTSD3b" x1="17.826" x2="20.269" y1="8.167" y2="21.403" gradientUnits="userSpaceOnUse"><stop class="yrtrc6n_d"/><stop offset="1" class="kkuk5w_fi"/></linearGradient><linearGradient id="iqyR7Md" x1="22.438" x2="18.766" y1="11.886" y2="7.995" gradientUnits="userSpaceOnUse"><stop class="tgz_9qxcq"/><stop offset="1" class="zvqcq9hxr"/></linearGradient><linearGradient id="igKPToc" x1="12.066" x2="11.782" y1="6.161" y2="6.161" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iCZBvGJ" x1="16.767" x2="16.404" y1="5.554" y2="6.678" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="ivcqxOe" x1="15.962" x2="12.575" y1="6.21" y2="6.715" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="i4cGMRc" x1="11.67" x2="13.159" y1="6.888" y2="6.938" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="i5OfPle" x1="11.779" x2="12.613" y1="7.406" y2="7.376" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="ii9I4ky" x1="13.936" x2="17.548" y1="4.887" y2="3.594" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iBemmJb" x1="13.788" x2="14.204" y1="6.503" y2="6.503" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="ipZMrob" x1="14.588" x2="14.133" y1="6.646" y2="6.639" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iMMdted" x1="14.258" x2="14.258" y1="6.975" y2="6.721" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iwDYsMe" x1="13.712" x2="13.905" y1="7.691" y2="7.386" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="ivPfn5d" x1="15.483" x2="15.344" y1="5.759" y2="5.845" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEjE9pb" x1="13.533" x2="13.394" y1="5.759" y2="5.845" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2LzEtb" x1="15.49" x2="15.303" y1="4.81" y2="4.429" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="i338qkc" x1="13.137" x2="12.61" y1="4.754" y2="4.532" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iRLfEee" x1="12.104" x2="12.104" y1="3.86" y2="4.817" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-surfing-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.agcr1zvqr {
  fill: var(--svg-color--000, #000);
  d: path("M14.912 5.92c0-.127.101-.227.227-.227a.226.226 0 0 1 .201.33h-.4a.2.2 0 0 1-.028-.104");
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

.auiuthgla {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.162 3.904v.398c-.004.066-.032.213-.115.276");
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.b54sc6tsh {
  fill: var(--svg-color--000, #000);
  d: path("M13.429 5.92c0-.127-.1-.227-.227-.227a.226.226 0 0 0-.201.33h.401a.2.2 0 0 0 .027-.104");
}

.b5iesbbmr {
  d: path("m14.002 5.911l-.236.754a.24.24 0 0 0 .231.31h.349a.24.24 0 0 0 .23-.31l-.235-.754c-.05-.167-.286-.167-.339 0");
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.b96gakb3t {
  d: path("M24.458 21.269L2.29 28.958a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.1 1.156-.157c5.922-2.015 17.406-5.859 18.176-6.199c.443-.195.511-.378.605-.627v-.002c.094-.25.047-1.03-.5-1.453c-.437-.337-1.105-.185-1.355-.07");
}

.bjo3ledcq {
  d: path("M19.837 23.019a29 29 0 0 1-.907-.867l1.867-.883c.075.131.51.8.72 1.117z");
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bv0rmnbrl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.11 5.607c.028.038-.031.084-.098.134s-.117.085-.145.048s.003-.11.07-.16s.145-.06.173-.022");
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.cd88em0te {
  stop-color: var(--svg-color--d89c92, #D89C92);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl_02q7-e {
  stop-color: var(--svg-color--f6c1b0, #F6C1B0);
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.dcogs8bsh {
  d: path("M19.75 29.755H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.841 2.937-3.292 4.109-4.976s2.062-2.294 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.326-6.078 1.28");
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7zo4pl3x {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.292c1.209-.02 3.782.828 4.104 4");
}

.eakiiobyh {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m14.05 5.984l-.364.753c-.045.155.063.31.216.31h.327c.153 0 .262-.157.217-.31l-.221-.753c-.048-.167-.126-.167-.175 0");
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.efctcxbso {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.498 4.832h.002l.002-.002l.005-.005l.069-.047a1.26 1.26 0 0 1 .848-.164a.237.237 0 1 1-.074.468a.78.78 0 0 0-.523.097l-.028.019a.237.237 0 0 1-.3-.365");
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

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fgw68gbhw {
  d: path("M20.68 13.856c.256-.588.373-1.22.399-1.462l2.047.023c.046.27-.04.584-.079.704c.088.322.037.686 0 .828c-.054.226-.178.713-.238.86c-.074.184-.183.247-.348.23a.4.4 0 0 1-.148-.042a.3.3 0 0 0-.23-.019a.43.43 0 0 1-.227.019a.43.43 0 0 1-.204-.113a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.005a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.071c-.085.007-.183.003-.235-.04c-.098-.083-.219-.177.031-.747");
}

.fhgc0ib0i {
  stop-color: var(--svg-color--dd937e, #DD937E);
}

.fqeviqb2e {
  stop-color: var(--svg-color--1154b9, #1154B9);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g3p53qx1q {
  d: path("M13.202 5.524a.396.396 0 0 0-.381.5h.764a.398.398 0 0 0-.383-.5");
}

.g99cn0bet {
  stop-color: var(--svg-color--2965ce, #2965CE);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
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

.gttado_ri {
  stop-color: var(--svg-color--faccbd, #FACCBD);
}

.h0qaawcfj {
  cx: 12.066px;
  cy: 6.038px;
  r: 0.441px;
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h31kj0t6r {
  stop-color: var(--svg-color--fac2a5, #FAC2A5);
  stop-opacity: 0;
}

.h3xvb7b2q {
  d: path("M15.139 5.524a.396.396 0 0 1 .381.5h-.764a.397.397 0 0 1 .383-.5");
}

.h400q-4fl {
  fill: var(--svg-color--f3bea7, #F3BEA7);
  fill-rule: evenodd;
  d: path("M5.25 14.674q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i75s2ibjf {
  d: path("M15.11 5.607c.028.038-.031.084-.098.134s-.117.085-.145.048s.003-.11.07-.16s.145-.06.173-.022");
}

.i8-ofx0jr {
  fill: var(--svg-color--f3bea7, #F3BEA7);
  fill-rule: evenodd;
  d: path("M5.611 14.951a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.ion1yqb0q {
  stop-color: var(--svg-color--f6cbb9, #F6CBB9);
}

.jalmfobon {
  stop-color: var(--svg-color--e19b84, #E19B84);
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jioe1_9gu {
  stop-color: var(--svg-color--5391be, #5391BE);
}

.jrricjbwu {
  d: path("M15.491 5.867a.37.37 0 0 0-.102-.205l-.115.127l.052.1z");
}

.jytpn83dl {
  d: path("m23.469 25.334l-.422-1.143l-2.351.536l2.225 1.099a.396.396 0 0 0 .547-.492");
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.ki97a6qmk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.594 4.997c.145-.128.461-.263.854-.2");
}

.kkuk5w_fi {
  stop-color: var(--svg-color--6096e0, #6096E0);
}

.kych8tj7f {
  d: path("M13.564 5.873c0-.128-.104-.213-.133-.239l-.127.124l.078.16z");
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l1gl77bzm {
  cx: 28.864px;
  cy: 12.82px;
  r: 1.043px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
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

.lj0l7tb9r {
  stop-color: var(--svg-color--2b68b8, #2B68B8);
}

.ljh96mbpx {
  d: path("M6.126 14.894c.125-.138.398-.461.52-.606c.23 0 .91-.066 1.198-.097c-.39.714-.84 1.004-1.074 1.195c-.316.21-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.lsxdl_bbw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.908 4.767c.19-.033.563-.024.82.177");
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mmnxzqoyz {
  d: path("M26.485 24.34c.981-2.28.626-3.888.055-5.014c-.474-.936-.003-1.663 1.018-1.421c.737.174 1.364.694 1.54 1.43c.721 3.026-.313 6.182-3.582 7.817c-2.95 1.475-7.854 1.593-9.937 1.468c3 0 9.804-1.722 10.906-4.28");
}

.mqkuen7rv {
  d: path("m16.309 3.165l.19.095a.87.87 0 0 1 .452.946l-.262 1.348c-.023.139-.115.233-.253.236h-.008s.023-.402.047-.638c.02-.192-.014-.251-.19-.426a.56.56 0 0 1-.166-.378v-.379a.255.255 0 0 0-.19-.236a7.3 7.3 0 0 0-1.737-.19c-.857 0-1.451.119-1.737.19a.23.23 0 0 0-.19.236v.379a.47.47 0 0 1-.167.378l-.07.07c-.096.072-.144.214-.144.332c.024.26.048.639.048.639l-.022-.001a.28.28 0 0 1-.264-.236l-.261-1.348a.905.905 0 0 1 .476-.922l.19-.095c.119-.071.238-.166.357-.26l.428-.45a.87.87 0 0 1 .975-.142c.238.071.5.071.738 0a1.07 1.07 0 0 1 1.046.237l.357.355a1 1 0 0 0 .357.26");
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n06rbc_sp {
  d: path("M11.884 5.128c0-.118.048-.26.143-.331l.072-.071a.47.47 0 0 0 .166-.379V3.97a.23.23 0 0 1 .19-.236c.286-.071.88-.19 1.737-.19c.856 0 1.45.119 1.736.19c.095.023.19.118.19.236v.378a.56.56 0 0 0 .167.379c.223.156.209.242.19.426c-.024.236-.047.638-.047.638h.008l-.118 1.756c-.071.784-.688 1.331-1.424 1.331H13.47c-.759 0-1.352-.547-1.423-1.331c-.062-.806-.09-1.614-.163-2.418");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nm46fkmyg {
  d: path("M17.568 10.284a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.793-.235-2.546-1.589-3.593c-1.381-1.068-2.68-1.257-4.203-1.257h-.39c-.157 1.285.25 2.192.606 2.671");
}

.nxcp0hivj {
  stop-color: var(--svg-color--3794e2, #3794E2);
}

.nyf_ntbrg {
  cx: 13.083px;
  cy: 5.693px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.173px;
  ry: 0.087px;
}

.o855rib8r {
  cx: 16.285px;
  cy: 6.038px;
  r: 0.441px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
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

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.p79aa0p9z {
  stop-color: var(--svg-color--3066bf, #3066BF);
}

.p7jmmxb2h {
  stop-color: var(--svg-color--d7a09d, #D7A09D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkq4odbli {
  d: path("M12.759 11.66c-.432-1.716.169-3.162.507-3.485l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.257c1.354 1.047 1.622 2.8 1.589 3.593a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.274-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.512 1.212 3.519c.546 1.484-.11 2.953.375 4.484c.377 1.192 1.203 2.419 1.636 2.921a.04.04 0 0 1-.013.063l-1.834.851a.04.04 0 0 1-.048-.01c-1.848-2.157-2.5-3.825-2.562-3.989s-.23-.531-.574-.531c-.275 0-.59.352-.809.73l-4.667 7.137a.05.05 0 0 1-.056.021l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.164 4.542-9.51 4.773-10.058c.21-.5.181-.916.14-1.086c-.03-.13-.218-.71-.585-2.172");
}

.prg3zrz8k {
  cx: 16.285px;
  cy: 6.038px;
  r: 0.74px;
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q2kjmzqur {
  stop-color: var(--svg-color--fac2a5, #FAC2A5);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.q8yoq8bts {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.915 7.4a.11.11 0 0 0-.012-.141a.12.12 0 0 0-.14-.024c-.17.09-.372.14-.591.14s-.421-.05-.591-.14a.12.12 0 0 0-.14.025a.11.11 0 0 0-.013.14m1.487 0l-.041-.027zm0 0a.89.89 0 0 1-.743.398a.89.89 0 0 1-.744-.397m0 0l.042-.028m-.042.028l.042-.028m0 0a.84.84 0 0 0 .702.375a.84.84 0 0 0 .702-.375c.038-.058-.027-.124-.088-.093a1.3 1.3 0 0 1-.614.146c-.225 0-.437-.053-.615-.146c-.06-.03-.126.037-.087.093Z");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0iiaeguw {
  stop-color: var(--svg-color--3168c8, #3168C8);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r4b1-ibwp {
  fill: var(--svg-color--242324, #242324);
  d: path("m16.309 3.165l.19.095a.87.87 0 0 1 .452.946l-.262 1.348c-.023.139-.115.233-.253.236h-.008s.023-.402.047-.638c.02-.192-.014-.251-.19-.426a.56.56 0 0 1-.166-.378v-.379a.255.255 0 0 0-.19-.236a7.3 7.3 0 0 0-1.737-.19c-.857 0-1.451.119-1.737.19a.23.23 0 0 0-.19.236v.379a.47.47 0 0 1-.167.378l-.07.07c-.096.072-.144.214-.144.332c.024.26.048.639.048.639l-.022-.001a.28.28 0 0 1-.264-.236l-.261-1.348a.905.905 0 0 1 .476-.922l.19-.095c.119-.071.238-.166.357-.26l.428-.45a.87.87 0 0 1 .975-.142c.238.071.5.071.738 0a1.07 1.07 0 0 1 1.046.237l.357.355a1 1 0 0 0 .357.26");
}

.r82a8ebvo {
  fill: var(--svg-color--f3bea7, #F3BEA7);
  fill-rule: evenodd;
  d: path("M7.127 13.55c-.941-.283-1.295.01-1.388.12a.375.375 0 0 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 0 1-.216.718");
}

.r9287rbao {
  stop-color: var(--svg-color--d29a85, #D29A85);
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rczvpztto {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.816px;
  rx: 0.299px;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
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

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s1_qcx0nn {
  stop-color: var(--svg-color--e2a89d, #E2A89D);
}

.s1mjb1beh {
  stop-color: var(--svg-color--d89c92, #D89C92);
}

.s3qfvabch {
  fill-rule: evenodd;
  d: path("M5.25 14.674q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.s6fw_r1qg {
  cx: 16.285px;
  cy: 6.038px;
  r: 0.441px;
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
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

.tcon8-qkz {
  fill: var(--svg-color--f3bea7, #F3BEA7);
  fill-rule: evenodd;
  d: path("M5.404 14.146c0 .001.02-.027.083-.079a2.1 2.1 0 0 1 1.279-.412a.375.375 0 1 0 .024-.75a2.84 2.84 0 0 0-1.323.296a2.4 2.4 0 0 0-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.tggvabbvc {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m15.821 4.831l-.002-.002l-.005-.005l-.07-.047a1.26 1.26 0 0 0-.848-.164a.237.237 0 0 0 .075.468a.78.78 0 0 1 .522.097l.025.016l.003.003a.237.237 0 0 0 .301-.366");
}

.tgz_9qxcq {
  stop-color: var(--svg-color--57b4fd, #57B4FD);
}

.to9zfdmjz {
  stop-color: var(--svg-color--1154b9, #1154B9);
  stop-opacity: 0;
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tu701m2xi {
  stop-color: var(--svg-color--f4baa6, #F4BAA6);
  stop-opacity: 0;
}

.txef72d1h {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.23 5.403c.29 0 .535.2.601.47a.122.122 0 0 1-.118.15h-.99a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .608-.5");
}

.u6gia-bos {
  stop-color: var(--svg-color--418dd5, #418DD5);
}

.uajw-acut {
  fill-rule: evenodd;
  d: path("M5.611 14.951a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uzhwu5bek {
  stop-color: var(--svg-color--f6c1b0, #F6C1B0);
  stop-opacity: 0;
}

.uzkpn5btf {
  stop-color: var(--svg-color--b07f87, #B07F87);
}

.v-ga10f4f {
  d: path("M10.684 11.702c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.031c.3-.027 1.148-.11 2.5-.719c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.386c-.376 1.03-1.005 2.246-2.38 3.261");
}

.vcpm8vbvg {
  fill: var(--svg-color--f0bca4, #F0BCA4);
  d: path("M7.602 12.783h.594c-.106.668.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.257.977-.3 1.258-.29");
}

.vevwxpb8j {
  stop-color: var(--svg-color--da9893, #DA9893);
}

.vgauzicqp {
  stop-color: var(--svg-color--3168c8, #3168C8);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vkxqb2bnp {
  cx: 12.066px;
  cy: 6.038px;
  r: 0.74px;
}

.vnopehb9h {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m14.002 5.911l-.236.754a.24.24 0 0 0 .231.31h.349a.24.24 0 0 0 .23-.31l-.235-.754c-.05-.167-.286-.167-.339 0");
}

.vovys4b_g {
  d: path("m15.93 3.543l-1.365.455a.464.464 0 0 0 .208.901l1.357-.182z");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vu5of3bdl {
  fill: var(--svg-color--f0b8a0, #F0B8A0);
  d: path("m7.305 27.355l1.172-2.39l1.766.304v1.039z");
}

.vxxc7i85i {
  stop-color: var(--svg-color--f4baa6, #F4BAA6);
}

.w9ndm1bxw {
  stop-color: var(--svg-color--da9893, #DA9893);
  stop-opacity: 0;
}

.wab8z-b3m {
  cx: 13.083px;
  cy: 5.693px;
  rx: 0.173px;
  ry: 0.087px;
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y60usm6nn {
  stop-color: var(--svg-color--46a5ef, #46A5EF);
}

.ydres4b4h {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("M21.985 27.34L7.61 28.84c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.335 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yi5ln4bok {
  cx: 25.864px;
  cy: 14.769px;
  r: 1.293px;
}

.ynrp46ydd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.11 5.403a.62.62 0 0 0-.6.47c-.02.077.04.15.119.15h.989a.102.102 0 0 0 .1-.12a.62.62 0 0 0-.607-.5");
}

.yrtrc6n_d {
  stop-color: var(--svg-color--54acfa, #54ACFA);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.z91enii4f {
  fill-rule: evenodd;
  d: path("M7.127 13.55c-.941-.283-1.295.01-1.388.12a.375.375 0 0 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 0 1-.216.718");
}

.zebje2bvd {
  fill: var(--svg-color--f0bca4, #F0BCA4);
  d: path("M6.126 14.894c.125-.138.398-.461.52-.606c.23 0 .91-.066 1.198-.097c-.39.714-.84 1.004-1.074 1.195c-.316.21-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zrzxj2epv {
  stop-color: var(--svg-color--2b68b8, #2B68B8);
  stop-opacity: 0;
}

.zvqcq9hxr {
  stop-color: var(--svg-color--57b4fd, #57B4FD);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
