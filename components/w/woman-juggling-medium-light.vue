<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#itJVrNc)"><path fill="url(#it9qbSc)" clip-rule="evenodd" class="v4l9b7bfk"/><path fill="url(#i4ZJblb)" clip-rule="evenodd" class="v4l9b7bfk"/><path fill="url(#ijoFjTc)" clip-rule="evenodd" class="v4l9b7bfk"/><path fill="url(#i4ZENHF)" clip-rule="evenodd" class="v4l9b7bfk"/><path fill="url(#i3FO55b)" clip-rule="evenodd" class="v4l9b7bfk"/><path fill="url(#i0hGBKc)" clip-rule="evenodd" class="v4l9b7bfk"/><path fill="url(#i8BpOLb)" clip-rule="evenodd" class="v4l9b7bfk"/><path fill="url(#ib5I73c)" clip-rule="evenodd" class="v4l9b7bfk"/><path fill="url(#iL6jUxg)" clip-rule="evenodd" class="v4l9b7bfk"/><path fill="url(#iKUgrIe)" clip-rule="evenodd" class="v4l9b7bfk"/></g><g filter="url(#iskt11R)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#iR6S3NZ)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#iGUfUFX)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#ipPlaYd)"><path fill="url(#ih8Nxde)" class="icuni4bra"/><path fill="url(#iQpTAtb)" class="icuni4bra"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#i6xnS7d)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#ipSUDMd)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#iFAKQmb)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#iCjCujc)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iiYllUd)"><path class="t5ih6_hjp"/></g><g filter="url(#iJ1sCae)"><path class="mdzzfhz-x"/></g><g filter="url(#ixcUtDc)"><path class="znvzi0b9x"/></g><g filter="url(#ihYy1sb)"><path class="z9b4pwbpg"/></g><g filter="url(#iD9bt1c)"><path class="sty1w-bnq"/></g><path fill="url(#i9aB4nd)" class="hw860-bkw"/><path fill="url(#i1P2OKg)" class="hw860-bkw"/><path fill="url(#iQvGmfb)" class="hw860-bkw"/><g filter="url(#itJXEyc)"><path fill="url(#iH4w94w)" class="k-ikuabgd"/></g><path fill="url(#icc9pKv)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iWgnezd)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#ivI3iyH)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#inrNF9c)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#iBFjJkb)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iGp04ob)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#i64UBtb)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ioxxPTd)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ixRckpe)" class="twba206ho"/><path fill="url(#i7tW1rc)" class="twba206ho"/><path fill="url(#iU8PPyb)" class="wp2dqucie"/><g filter="url(#iBvok2d)"><path class="dukixxuqk"/></g><g filter="url(#iLviNIb)"><path class="rwc5yskns"/></g><g filter="url(#ieTjwWd)"><path class="u5j75vbts"/></g><g filter="url(#itS1Brb)"><path class="u47ww4b8k"/></g><g filter="url(#iIh9xDd)"><path stroke="url(#iPWzvjj)" class="bdk4dmb5b"/></g><g filter="url(#iZDLtwe)"><path stroke="url(#i0gZ48c)" class="gwm_2mjil"/></g><g filter="url(#iCB8Pmb)"><path stroke="url(#iF8fKMd)" class="y2ly1lryk"/></g><g filter="url(#izlTJ0b)"><path stroke="url(#impiaed)" class="am6k_ubte"/></g><g filter="url(#iIutUpM)"><path stroke="url(#iVWluoc)" class="c549xi8ae"/></g><g filter="url(#iP1zUIb)"><path fill="url(#iGr0I7d)" class="kcghdwhrn"/></g><g filter="url(#icbOnGd)"><path fill="url(#ijMVszd)" class="e62ny4r5a"/><path fill="url(#i1XmTid)" class="e62ny4r5a"/></g><g filter="url(#ijPcFWc)"><path class="w8nounoll"/><path fill="url(#i0qBnra)" class="r98c7zpub"/></g><g filter="url(#imKyP4c)"><path class="wh3c_kh0o"/><path fill="url(#i2y5EQd)" class="omcg-jx5s"/></g><g filter="url(#iPzQ9vR)"><path fill="url(#iZ8WsLb)" class="vpgapnbls"/><path fill="url(#iggr8Mb)" class="vpgapnbls"/><path fill="url(#i040fmb)" class="vpgapnbls"/><path fill="url(#i2A2gHe)" class="vpgapnbls"/><path fill="url(#iqw0Lnb)" class="vpgapnbls"/><path fill="url(#i5MaS6d)" class="vpgapnbls"/><path fill="url(#ibrmhcm)" class="vpgapnbls"/></g><path fill="url(#iJs8BAM)" class="vpgapnbls"/><path fill="url(#i1dfTNE)" class="vpgapnbls"/><path fill="url(#ivCGs2d)" class="vpgapnbls"/><g filter="url(#iQsKjKb)"><path class="n0q868z5u"/></g><g filter="url(#iMeCPFc)"><path class="vdquivcge"/><path fill="url(#ipYwtBd)" class="t4v4yv0jq"/><path fill="url(#ikraUDb)" class="t4v4yv0jq"/><path fill="url(#irMqvpb)" class="t4v4yv0jq"/></g><g filter="url(#ilbdrxc)"><path stroke="url(#i63yqBR)" class="qiv0sy4ti"/></g><path class="o-78pgbmu"/><g filter="url(#i3n6kbc)"><path class="gg8w35byp"/></g><g filter="url(#ipTBiFd)"><path class="i0g-r-b4q"/></g><g filter="url(#idm9s1d)"><path class="xsrv17hzl"/></g><g filter="url(#i2oNetb)"><path clip-rule="evenodd" class="ocu5vabbc"/></g><path class="gpuqoab5b"/><path fill="url(#ilfNkFd)" class="iim9_1bun"/><path class="akouact0v"/><g filter="url(#iKszqvp)"><path class="d0z_a_s9o"/><path fill="url(#ixg2NKz)" class="x47nvg59z"/></g><g filter="url(#iVxdTAd)"><path fill="url(#iGIFZme)" class="jgr1hwbqg"/></g><path class="dlr0qpi_a"/><path fill="url(#isXjuMc)" class="mp-v6wxxc"/><path class="wd3l9ackr"/><g filter="url(#i5t8oge)"><path fill="url(#iVPXSWd)" class="dj0tr0jfc"/></g><g filter="url(#iAb2yBb)"><ellipse transform="rotate(-27.914 14.209 13.575)" class="w6b1k4b2n"/><ellipse fill="url(#iQlCGEG)" transform="rotate(-27.914 14.209 13.575)" class="ya6u6gbcz"/></g><g filter="url(#iNLIind)"><path class="sycxk1b0o"/></g><g filter="url(#ijhLbvd)"><path class="urv0ax6ew"/></g><g filter="url(#i2Z095b)"><path fill="url(#iiezAhb)" class="x92nk4bxu"/><path fill="url(#i07AaXb)" class="x92nk4bxu"/></g><g filter="url(#ic5aCzJ)"><path fill="url(#i9iq31d)" class="fgq5x6brk"/><path fill="url(#iDEsQAx)" class="fgq5x6brk"/><path fill="url(#iSiqkxc)" class="fgq5x6brk"/></g><g filter="url(#idj1Vte)"><path stroke="url(#iQVfLQd)" class="vlrm142vf"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#ixSAAAe)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="i4ZJblb" cx="0" cy="0" r="1" gradientTransform="matrix(1.82232 -3.78482 8.62965 4.155 21.68 20.383)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="ijoFjTc" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 2.287 13.796)scale(6.0411 5.65486)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="i4ZENHF" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 3.81 10.913)scale(4.1709 5.13415)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="i3FO55b" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.076 10.31)scale(1.86187 1.69236)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="i0hGBKc" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.85 5.81)scale(2.49544 3.66831)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="i8BpOLb" cx="0" cy="0" r="1" gradientTransform="rotate(55.684 .338 15.271)scale(4.00963 6.99736)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="ib5I73c" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.436 9.1)scale(1.71146 2.39173)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iL6jUxg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92737 .56072 -1.22005 -4.1937 24.623 13.41)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iKUgrIe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.2942 1.40177 -2.23345 -5.24867 24.343 16.318)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="ih8Nxde" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.265 20.795)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iQpTAtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.188 22.482)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="i9aB4nd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="sqw7shfwy"/><stop offset="1" class="t-r3m-b0n"/></radialGradient><radialGradient id="i1P2OKg" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="fxbge344d"/><stop offset="1" class="i9u4tf5-i"/></radialGradient><radialGradient id="iQvGmfb" cx="0" cy="0" r="1" gradientTransform="rotate(77.963 .104 26.074)scale(1.04894 5.75403)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="te2y3cbdr"/><stop offset="1" class="pdm4p_b5q"/><stop offset="1" class="kmrvduh9f"/></radialGradient><radialGradient id="iH4w94w" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="vxe5hyz_v"/><stop offset="1" class="k9e4-bb7j"/></radialGradient><radialGradient id="icc9pKv" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="iWgnezd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="ivI3iyH" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="inrNF9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="iBFjJkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="iGp04ob" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="i64UBtb" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="ioxxPTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="ixRckpe" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="w3oseebkq"/><stop offset=".644" class="cy8y9p-pn"/></radialGradient><radialGradient id="i7tW1rc" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="axsenyy_b"/><stop offset="1" class="j471ep9dt"/></radialGradient><radialGradient id="iU8PPyb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 2.24809 -2.56376 1.92445 16.099 20.289)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="s0pz40q7h"/><stop offset="1" class="lvd5l1bfv"/></radialGradient><radialGradient id="ijMVszd" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 44.565 -41.087)scale(2.85826 3.4898)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="i1XmTid" cx="0" cy="0" r="1" gradientTransform="matrix(1.04258 .29788 -.1566 .54812 22.065 12.437)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="i0qBnra" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 51.424 -52.989)scale(1.36382)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="i2y5EQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27211 0 0 -1.21685 11.895 14.3)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iZ8WsLb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.79886 3.13518 -4.19638 -9.10015 19.762 13.738)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iggr8Mb" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 7.585 9.561)scale(2.49505 2.11687)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="i040fmb" cx="0" cy="0" r="1" gradientTransform="rotate(-78.311 20.036 1.514)scale(4.31835 5.47919)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i2A2gHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.77519 -10.5397 0 16.773 13.437)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="hc6nasj2l"/><stop offset=".91" class="jvratdb7m"/></radialGradient><radialGradient id="iqw0Lnb" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 8.178 8.673)scale(6.0466 10.4104)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="i5MaS6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20302 1.72948 0 19.179 13.3)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="ibrmhcm" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.42175 1.62942 0 14.768 13.391)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iJs8BAM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40811 0 0 -4.63553 22.1 14.855)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="i1dfTNE" cx="0" cy="0" r="1" gradientTransform="matrix(1.20875 4.4103 -9.11365 2.49781 14.16 7.982)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="ipYwtBd" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 14.691 1.166)scale(2.66274 1.52365)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="ilfNkFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84815 -1.34908 0 19.054 13.676)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ixg2NKz" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.778 2.274)scale(.39546 .54446)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isXjuMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84816 -1.34909 0 14.492 13.675)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iQlCGEG" cx="0" cy="0" r="1" gradientTransform="matrix(-.00809 -.51649 .62084 -.00972 14.192 13.904)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iiezAhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02273 2.80356 -5.57067 4.01918 10.546 7.767)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="i07AaXb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96259 2.59331 -2.03383 -1.53918 13.935 8.012)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="i9iq31d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20784 4.59084 -6.52798 -3.13946 18.77 6.015)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iDEsQAx" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 6.815 10.99)scale(3.47042 6.19479)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iSiqkxc" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 12.871 1.147)scale(7.53784 6.74744)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="ixSAAAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.269 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="itJVrNc" width="15.95" height="16.45" x="8.923" y="4.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="iskt11R" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="iR6S3NZ" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23856"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23856" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23856"/></filter><filter id="iGUfUFX" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23856"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23856" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23856"/></filter><filter id="ipPlaYd" width="6.565" height="3.702" x="13.395" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="i6xnS7d" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".5"/></filter><filter id="ipSUDMd" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="iFAKQmb" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="iCjCujc" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="iiYllUd" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.592157 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="iJ1sCae" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="ixcUtDc" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="ihYy1sb" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="iD9bt1c" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="itJXEyc" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.607843 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="iBvok2d" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="iLviNIb" width="1.286" height="2.978" x="23.933" y="18.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="ieTjwWd" width="1.444" height="3.775" x="24.963" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="itS1Brb" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="iIh9xDd" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="iZDLtwe" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="iCB8Pmb" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="izlTJ0b" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="iIutUpM" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="iP1zUIb" width="3.514" height="3.614" x="10.193" y="12.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="icbOnGd" width="3.364" height="3.614" x="20.138" y="12.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="ijPcFWc" width="3.246" height="3.246" x="20.197" y="12.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".25"/></filter><filter id="imKyP4c" width="3.046" height="3.046" x="10.372" y="12.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".2"/></filter><filter id="iPzQ9vR" width="10.654" height="11.621" x="11.446" y="9.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="iQsKjKb" width="2.962" height="3.803" x="15.122" y="13.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".25"/></filter><filter id="iMeCPFc" width="2.462" height="3.303" x="15.542" y="13.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="ilbdrxc" width="3.852" height="1.577" x="14.847" y="16.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".05"/></filter><filter id="i3n6kbc" width="3.129" height="1.344" x="17.767" y="12.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="ipTBiFd" width="3.129" height="1.344" x="12.651" y="12.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="idm9s1d" width="2.555" height="1.131" x="12.792" y="11.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="i2oNetb" width="2.555" height="1.132" x="18.455" y="11.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23856"/></filter><filter id="iKszqvp" width=".813" height=".719" x="18.291" y="13.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".05"/></filter><filter id="iVxdTAd" width=".914" height=".937" x="19.174" y="13.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".1"/></filter><filter id="i5t8oge" width="1.013" height="1.069" x="14.529" y="13.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".1"/></filter><filter id="iAb2yBb" width=".945" height=".727" x="13.736" y="13.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".05"/></filter><filter id="iNLIind" width="2.336" height=".995" x="18.501" y="11.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".1"/></filter><filter id="ijhLbvd" width="2.336" height=".995" x="12.802" y="11.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".1"/></filter><filter id="i2Z095b" width="4.436" height="5.443" x="10.252" y="6.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".25"/></filter><filter id="ic5aCzJ" width="9.296" height="6.02" x="13.317" y="5.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".125"/></filter><filter id="idj1Vte" width="1.169" height="2.387" x="13.451" y="7.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23856" stdDeviation=".1"/></filter><linearGradient id="it9qbSc" x1="21.68" x2="14.566" y1="7.031" y2="20.208" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="iPWzvjj" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="nisiqibvr"/><stop offset="1" class="nntb9stew"/></linearGradient><linearGradient id="i0gZ48c" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="iF8fKMd" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="impiaed" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="iVWluoc" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="iGr0I7d" x1="10.193" x2="13.286" y1="14.39" y2="14.39" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="ivCGs2d" x1="16.773" x2="16.773" y1="10.685" y2="11.881" gradientUnits="userSpaceOnUse"><stop class="myg-xrbkb"/><stop offset="1" class="zjigynbqy"/></linearGradient><linearGradient id="ikraUDb" x1="15.679" x2="16.572" y1="15.633" y2="15.742" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="irMqvpb" x1="16.773" x2="16.773" y1="16.526" y2="15.888" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="i63yqBR" x1="16.011" x2="16.484" y1="18.07" y2="17.159" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="iGIFZme" x1="19.868" x2="19.54" y1="13.732" y2="13.934" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVPXSWd" x1="15.27" x2="14.942" y1="13.731" y2="13.934" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQVfLQd" x1="13.751" x2="14.32" y1="8.028" y2="9.359" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-juggling-medium-light" /></template>
<style>
.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.akouact0v {
  fill: var(--svg-color--000, #000);
  d: path("M18.522 14.11c0-.297.237-.535.534-.535a.532.532 0 0 1 .475.78h-.945a.5.5 0 0 1-.064-.245");
}

.am6k_ubte {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.981 17.139c.11.172.625 1.078 1.282 1.273");
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aqzyd8bsb {
  stop-color: var(--svg-color--896bb4, #896BB4);
  stop-opacity: 0;
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.auvn9fbbk {
  stop-color: var(--svg-color--e9387a, #E9387A);
}

.axsenyy_b {
  stop-color: var(--svg-color--c28d66, #C28D66);
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bd09vtb_c {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bdk4dmb5b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m28.692 20.295l-.937 1.75");
}

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.bq5dgsbba {
  stop-color: var(--svg-color--dcc8ec, #DCC8EC);
}

.btor07b8q {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
}

.byn6wubog {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.899 24.871a.35.35 0 0 1-.266.244c-.25.048-.467.048-.717 0a.35.35 0 0 1-.262-.23c-.18.2-.49.432-1.009.607c-.31.106-.668.058-.833-.23a1.86 1.86 0 0 1-.245-.948c0-.431.124-.74.245-.95c.165-.287.523-.334.833-.23c.503.171.81.418.993.63a.35.35 0 0 1 .278-.293c.25-.048.467-.048.717 0a.35.35 0 0 1 .28.31c.18-.215.49-.47 1.008-.646c.31-.105.668-.058.834.23c.12.208.244.513.244.949s-.124.74-.244.949c-.166.287-.524.335-.834.23c-.531-.18-.844-.42-1.022-.622");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c549xi8ae {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.77 17.467c.177.245.618 1.078 1.72 1.594");
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c60cvac3k {
  stop-color: var(--svg-color--e5ddee, #E5DDEE);
  stop-opacity: 0;
}

.c6833cb9x {
  stop-color: var(--svg-color--372f3c, #372F3C);
}

.ci3gi1b_k {
  stop-color: var(--svg-color--784b89, #784B89);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.ctsppjbax {
  d: path("M14.866 22.463c.91.308 1.268.83 1.389 1.082l.028.29l-.028.359c-.12.25-.48.706-1.389 1.014c-.36.123-.777.068-.97-.267a2.17 2.17 0 0 1-.285-1.105c0-.502.144-.862.285-1.106c.193-.335.61-.39.97-.267");
}

.ctupw6b3d {
  fill-rule: evenodd;
  d: path("M3.113 18.184a.75.75 0 0 1 1.042.196c.312.455.974 1.204 1.85 1.204a.75.75 0 1 1 0 1.5c-1.702 0-2.759-1.376-3.088-1.858a.75.75 0 0 1 .196-1.042");
}

.cy8y9p-pn {
  stop-color: var(--svg-color--daa781, #DAA781);
}

.d0z_a_s9o {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.988 13.374c.066.089-.073.197-.23.315c-.159.118-.276.201-.342.113c-.067-.09.007-.257.165-.375s.34-.142.407-.053");
}

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d7caiobkz {
  stop-color: var(--svg-color--e4cc30, #E4CC30);
  stop-opacity: 0;
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.demkpcl0k {
  stop-color: var(--svg-color--b1a0b8, #B1A0B8);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dj0tr0jfc {
  d: path("M15.342 14c0-.302-.245-.503-.311-.563l-.302.291l.186.378z");
}

.dlr0qpi_a {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.274 12.893c-.683 0-1.26.47-1.416 1.106a.286.286 0 0 0 .28.357h2.332a.24.24 0 0 0 .237-.284a1.465 1.465 0 0 0-1.433-1.18");
}

.don2wdpjw {
  cx: 16.761px;
  cy: 26.282px;
  r: 0.739px;
}

.dpmuo-biy {
  stop-color: var(--svg-color--6f5ea2, #6F5EA2);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dukixxuqk {
  stroke: var(--svg-color--ddac99, #DDAC99);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m23.333 19.615l.414 1.64");
}

.duyhuibwk {
  cx: 9.246px;
  cy: 3.857px;
  r: 1.684px;
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e62ny4r5a {
  d: path("M21.82 15.982a1.682 1.682 0 1 0 0-3.365a1.682 1.682 0 0 0 0 3.364");
}

.efwa18n2a {
  stop-color: var(--svg-color--efbea6, #EFBEA6);
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fgq5x6brk {
  d: path("M16.143 6.155c-1.184-.261-2.454.999-2.576 1.437c1.612 3.785 4.087 3.424 6.834 3.119c1.643-.183 1.822.566 1.962.928c-.456-4.24-3.522-4.888-6.22-5.484");
}

.fr__qmhjc {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
}

.ft5dv1b6b {
  fill: none;
}

.fxbge344d {
  stop-color: var(--svg-color--cb8d82, #CB8D82);
  stop-opacity: 0;
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.gg8w35byp {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.967 13.705c.277-.489.7-.874 1.607-.874c.397 0 .78.11 1.121.386c.282.227.244.517.026.626l-.581.332c-.681-.22-1.435-.25-2.173-.47");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gpuqoab5b {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.273 12.893c.683 0 1.26.47 1.416 1.106a.287.287 0 0 1-.28.357h-2.332a.24.24 0 0 1-.238-.284c.132-.67.721-1.18 1.434-1.18");
}

.gr0wzobbs {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
  stop-opacity: 0;
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gwm_2mjil {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.177 19.865c.177.245.832.742 1.472.84");
}

.gypp10kih {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
  stop-opacity: 0;
}

.gzsz7evmk {
  stop-color: var(--svg-color--eb3782, #EB3782);
}

.h2li0wblg {
  stop-color: var(--svg-color--d02759, #D02759);
}

.h4mko5b9o {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
  stop-opacity: 0;
}

.hc6nasj2l {
  stop-color: var(--svg-color--c58780, #C58780);
  stop-opacity: 0;
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hjrsfpbzk {
  stop-color: var(--svg-color--e7b594, #E7B594);
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hw860-bkw {
  d: path("M22.993 22.213c.119.463.586 1.456.805 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i0g-r-b4q {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.58 13.705c-.278-.489-.7-.874-1.608-.874c-.397 0-.78.11-1.121.386c-.281.227-.244.517-.026.626l.581.332c.682-.22 1.435-.25 2.173-.47");
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i7zyuv8vr {
  stop-color: var(--svg-color--ede7f3, #EDE7F3);
}

.i8j0jyb4u {
  stop-color: var(--svg-color--b8a734, #B8A734);
}

.i8skpb2jz {
  stop-color: var(--svg-color--5d5565, #5D5565);
}

.i9u4tf5-i {
  stop-color: var(--svg-color--cb8d82, #CB8D82);
}

.icuni4bra {
  d: path("M16.796 19.623h-.343a10.2 10.2 0 0 0-3.058.466l.597 3.136h4.945l.823-3.22c-.93-.279-1.942-.382-2.964-.382");
}

.iim9_1bun {
  d: path("M19.056 13.177a.933.933 0 0 1 .9 1.179h-1.803a.937.937 0 0 1 .903-1.179");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j471ep9dt {
  stop-color: var(--svg-color--d5a186, #D5A186);
  stop-opacity: 0;
}

.j70rp9pis {
  d: path("M22.222 29.826h-1.578v-9.568q.826.307 1.578.746z");
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.j8k1fac_p {
  stop-color: var(--svg-color--5b5a5d, #5B5A5D);
}

.jgr1hwbqg {
  d: path("M19.887 13.987a.9.9 0 0 0-.241-.484l-.272.298l.123.239z");
}

.jhlen960d {
  stop-color: var(--svg-color--745ba5, #745BA5);
}

.jjf293xlz {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
  stop-opacity: 0;
}

.jm40s5baz {
  stop-color: var(--svg-color--968f9c, #968F9C);
  stop-opacity: 0;
}

.jvratdb7m {
  stop-color: var(--svg-color--b8707a, #B8707A);
}

.k-ikuabgd {
  d: path("M6.803 17.694a.782.782 0 0 1 1.249-.94l.93 1.213c.337.438.519.975.519 1.527l-1.5-.18z");
}

.k9e4-bb7j {
  stop-color: var(--svg-color--d49a78, #D49A78);
}

.kcghdwhrn {
  d: path("M11.875 15.982a1.682 1.682 0 1 0 0-3.365a1.682 1.682 0 0 0 0 3.364");
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.kmrvduh9f {
  stop-color: var(--svg-color--ce9487, #CE9487);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.ku63lg_wt {
  stop-color: var(--svg-color--e8e2ec, #E8E2EC);
}

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.ld_83jb7a {
  d: path("M16.018 23.224a.41.41 0 0 1 .328-.37a2.1 2.1 0 0 1 .834 0a.41.41 0 0 1 .328.37c.042.395.042.778 0 1.174a.41.41 0 0 1-.328.37c-.29.056-.544.056-.834 0a.41.41 0 0 1-.328-.37a5.5 5.5 0 0 1 0-1.174");
}

.lelj2r8dg {
  stop-color: var(--svg-color--9ae453, #9AE453);
}

.lgi0lwbjz {
  stop-color: var(--svg-color--775184, #775184);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvd5l1bfv {
  stop-color: var(--svg-color--d29a87, #D29A87);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.lxw2rgt3i {
  stop-color: var(--svg-color--c7877f, #C7877F);
  stop-opacity: 0;
}

.m-1-e5bla {
  stop-color: var(--svg-color--fbf2f7, #FBF2F7);
}

.m5avsc_ef {
  stop-color: var(--svg-color--784b89, #784B89);
}

.m9gf32bwp {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdzzfhz-x {
  fill: var(--svg-color--d59f8d, #D59F8D);
  d: path("M25.92 18.247a.668.668 0 1 1 1.316-.232l.34 2.222q.012.082.005.164l-.015.163c-.005.055-.002.11 0 .165c.016.295-.146.515-.454.557a.61.61 0 0 1-.68-.483z");
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mp-v6wxxc {
  d: path("M14.49 13.177a.933.933 0 0 0-.9 1.179h1.803a1 1 0 0 0 .034-.246a.94.94 0 0 0-.937-.933");
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
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

.myg-xrbkb {
  stop-color: var(--svg-color--b1756a, #B1756A);
}

.n0q868z5u {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m16.363 14.067l-.715 1.777a.564.564 0 0 0 .544.731h.822a.566.566 0 0 0 .544-.731l-.555-1.777c-.12-.394-.516-.394-.64 0");
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.nisiqibvr {
  stop-color: var(--svg-color--efc0a4, #EFC0A4);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nke1727fd {
  stop-color: var(--svg-color--c7877f, #C7877F);
}

.nl0wbpawx {
  stop-color: var(--svg-color--968f9c, #968F9C);
}

.nntb9stew {
  stop-color: var(--svg-color--efc0a4, #EFC0A4);
  stop-opacity: 0;
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o-78pgbmu {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16.773 17.343a3.16 3.16 0 0 1-1.486-.36c-.147-.077-.305.093-.212.23a2.02 2.02 0 0 0 3.397 0c.092-.143-.066-.307-.213-.23c-.43.23-.936.36-1.486.36");
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.ocu5vabbc {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m20.674 11.962l-.144.24za.28.28 0 0 1-.288.482l-.005-.003a2 2 0 0 0-.118-.061a3 3 0 0 0-.358-.141a2.4 2.4 0 0 0-1.12-.097a.28.28 0 1 1-.098-.552a2.95 2.95 0 0 1 1.389.114a3.4 3.4 0 0 1 .584.25l.01.006l.002.001z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ok2r3obil {
  stop-color: var(--svg-color--634d93, #634D93);
}

.okwd93kys {
  width: 15.516px;
  height: 1.742px;
  x: 9.003px;
  y: 9.238px;
  rx: 0.871px;
}

.omcg-jx5s {
  d: path("M11.895 15.423a1.123 1.123 0 1 0 0-2.246a1.123 1.123 0 0 0 0 2.246");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.pdm4p_b5q {
  stop-color: var(--svg-color--e6b298, #E6B298);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppr920emc {
  stop-color: var(--svg-color--61a150, #61A150);
  stop-opacity: 0;
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qiv0sy4ti {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.773 17.343a3.16 3.16 0 0 1-1.486-.36c-.147-.077-.305.093-.212.23a2.02 2.02 0 0 0 3.397 0c.092-.143-.066-.307-.213-.23c-.43.23-.936.36-1.486.36Z");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qsu4qbckq {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qy4rrcb8b {
  d: path("M12.857 29.826h-1.578v-8.795a10 10 0 0 1 1.578-.756z");
}

.qzd219blo {
  d: path("M11 8.662a5.773 5.773 0 1 1 11.547 0v1.648H11z");
}

.qzhltkbuo {
  stop-color: var(--svg-color--b9aac8, #B9AAC8);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r98c7zpub {
  d: path("M21.82 15.423a1.123 1.123 0 1 0 0-2.246a1.123 1.123 0 0 0 0 2.246");
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rwc5yskns {
  stroke: var(--svg-color--ddac99, #DDAC99);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.358 18.55l.436 2.128");
}

.s0pz40q7h {
  stop-color: var(--svg-color--b76d71, #B76D71);
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.sawf8hb2n {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
  stop-opacity: 0;
}

.sb-ednb_a {
  stop-color: var(--svg-color--ece4f4, #ECE4F4);
}

.scbqttb8d {
  stop-color: var(--svg-color--ec4182, #EC4182);
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.sqw7shfwy {
  stop-color: var(--svg-color--f1bea0, #F1BEA0);
}

.sty1w-bnq {
  fill: var(--svg-color--d59f8d, #D59F8D);
  d: path("M22.414 19.881a.681.681 0 1 1 1.33-.294l.36 1.794a.645.645 0 0 1-1.26.279z");
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.sycxk1b0o {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.8 11.82c.338-.083 1.176-.042 1.737.36");
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.t-r3m-b0n {
  stop-color: var(--svg-color--d69f8b, #D69F8B);
}

.t4v4yv0jq {
  d: path("m16.373 13.922l-.555 1.777a.564.564 0 0 0 .544.731h.822a.565.565 0 0 0 .544-.731l-.555-1.777c-.12-.394-.675-.394-.8 0");
}

.t5ih6_hjp {
  fill: var(--svg-color--f2bfa1, #F2BFA1);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.te2y3cbdr {
  stop-color: var(--svg-color--ce9487, #CE9487);
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tsmwdfbse {
  stop-color: var(--svg-color--efbea6, #EFBEA6);
  stop-opacity: 0;
}

.tub8lbbfx {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
}

.tvoyviyhj {
  stop-color: var(--svg-color--775184, #775184);
}

.twba206ho {
  d: path("M5.963 18.892a.88.88 0 0 0-.37.74v2.108l.618.04h3.302v-2.33c0-.836-.805-1.25-1.97-1.148c-.655.057-1.208.34-1.58.589");
}

.u1gl_1zha {
  stop-color: var(--svg-color--ec4182, #EC4182);
  stop-opacity: 0;
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.u47ww4b8k {
  stroke: var(--svg-color--ddac99, #DDAC99);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m26.849 18.13l.32 2.165");
}

.u5j75vbts {
  stroke: var(--svg-color--ddac99, #DDAC99);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m25.388 17.651l.594 2.925");
}

.u6lph46no {
  stop-color: var(--svg-color--f0dff0, #F0DFF0);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.urv0ax6ew {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.838 11.82c-.337-.083-1.176-.042-1.736.36");
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v4l9b7bfk {
  fill-rule: evenodd;
  d: path("M24.285 15.773c.222-.455.338-.962.338-1.491c0-.489-.1-.947-.28-1.365h.005a3.3 3.3 0 0 0-.294-.536l-.002-.004a3.4 3.4 0 0 1-.55-1.851v-.01c0-.729-1.513-.617-1.898-1.174c-.623-.9-.375-2.276-1.551-2.276a.56.56 0 0 1-.476-.243a3.46 3.46 0 0 0-2.804-1.439c-1.153 0-2.18.572-2.803 1.44a.59.59 0 0 1-.477.242q-.045 0-.088.002c-1.098.027-1.033 1.654-1.645 2.477c-.427.574-1.716.2-1.716.97v.01c0 .657-.19 1.302-.55 1.852l-.002.004a3.45 3.45 0 0 0-.23 3.392a.54.54 0 0 1 0 .476a3.4 3.4 0 0 0-.339 1.471a3.36 3.36 0 0 0 3.364 3.364h8.972a3.36 3.36 0 0 0 3.364-3.364c0-.529-.127-1.026-.338-1.47a.54.54 0 0 1 0-.477M11.468 12.98h-.013l1.253 2.462c.129 2.93 1.272 0 4.065 0s4.01 3.261 4.14.331l1.187-3.342c-.056-1.301-1-1.393-1.187-1.393h-3.367a4.04 4.04 0 0 1-3.334-1.749a.276.276 0 0 0-.482.053l-.086.203a2.4 2.4 0 0 1-1.243 1.29l-.054.022q-.03.013-.054.021c-.246.128-.825.512-.847 1.504l.011.32z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.vdquivcge {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m16.373 13.922l-.555 1.777a.564.564 0 0 0 .544.731h.822a.565.565 0 0 0 .544-.731l-.555-1.777c-.12-.394-.675-.394-.8 0");
}

.vfp25y1ae {
  stop-color: var(--svg-color--cf9080, #CF9080);
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vlrm142vf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.75 7.668c.025.255.246 1.21.57 1.788");
}

.vpgapnbls {
  d: path("m11.457 12.702l-.01-.32c.02-.992.6-1.376.846-1.504q.025-.008.054-.021l.053-.021a2.4 2.4 0 0 0 1.244-1.291l.086-.203a.276.276 0 0 1 .482-.053c.75 1.099 2.005 1.214 3.334 1.214h3.366c.567 0 1.132.627 1.188 1.928l-.124 3.213c-.13 2.93-2.417 4.897-5.21 4.897s-5.08-1.968-5.21-4.898z");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.vxe5hyz_v {
  stop-color: var(--svg-color--dfad8b, #DFAD8B);
}

.w3oseebkq {
  stop-color: var(--svg-color--f5c5a6, #F5C5A6);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w63qn2bkh {
  stop-color: var(--svg-color--605966, #605966);
}

.w6b1k4b2n {
  cx: 14.209px;
  cy: 13.575px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.407px;
  ry: 0.206px;
}

.w8nounoll {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M21.82 15.423a1.123 1.123 0 1 0 0-2.246a1.123 1.123 0 0 0 0 2.246");
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wd3l9ackr {
  fill: var(--svg-color--000, #000);
  d: path("M15.025 14.11a.53.53 0 0 0-.535-.535a.532.532 0 0 0-.475.78h.946a.5.5 0 0 0 .064-.245");
}

.wfgw5ub6b {
  fill-rule: evenodd;
  d: path("M4.273 16.754a.75.75 0 0 1 1.042.196q.091.134.166.258c.141.228.267.432.519.637c.292.238.794.485 1.747.42a.75.75 0 1 1 .102 1.497c-1.29.088-2.178-.25-2.796-.754c-.478-.389-.78-.89-.917-1.116l-.059-.096a.75.75 0 0 1 .196-1.042");
}

.wh3c_kh0o {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.895 15.423a1.123 1.123 0 1 0 0-2.246a1.123 1.123 0 0 0 0 2.246");
}

.wjchuwb6a {
  stop-color: var(--svg-color--745ba5, #745BA5);
  stop-opacity: 0;
}

.wozepxbaa {
  d: path("M11.048 7.912a6 6 0 0 0-.048.75v1.648h11.547V8.663q0-.381-.049-.75z");
}

.wp2dqucie {
  d: path("M14.545 18.417c0-.99.901-1.794 2.012-1.794s2.012.803 2.012 1.794v2.326c0 .99-.901 1.794-2.012 1.794s-2.012-.803-2.012-1.794z");
}

.wp2p6dbcv {
  d: path("M23.777 24.107h4.094v5.719h-4.094z");
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.x47nvg59z {
  d: path("M18.988 13.374c.066.089-.073.197-.23.315c-.159.118-.276.201-.342.113c-.067-.09.007-.257.165-.375s.34-.142.407-.053");
}

.x92nk4bxu {
  d: path("M11.657 8.012c.649-.578 1.585-.584 2.111-.49l.42 1.349c-.268-.04-.508.053-.709.245c-.473 1.753-2.26 1.49-2.61 2.804c-.159-1.56-.334-2.909.788-3.908");
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.xsrv17hzl {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m13.222 12.44l-.005.003a.28.28 0 0 1-.288-.48v-.001h.001l.003-.002l.01-.006a2 2 0 0 1 .155-.08c.103-.05.25-.112.43-.17a2.9 2.9 0 0 1 1.388-.114a.28.28 0 1 1-.098.553a2.36 2.36 0 0 0-1.12.096a3 3 0 0 0-.454.189z");
}

.y_auwli2s {
  stop-color: var(--svg-color--415e58, #415E58);
}

.y-1rsmdul {
  stop-color: var(--svg-color--3a7ab4, #3A7AB4);
  stop-opacity: 0;
}

.y05rrkbkk {
  stop-color: var(--svg-color--ffff54, #FFFF54);
}

.y2ly1lryk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.716 18.576c.177.245.672.953 1.492 1.172");
}

.ya6u6gbcz {
  cx: 14.209px;
  cy: 13.575px;
  rx: 0.407px;
  ry: 0.206px;
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.z9b4pwbpg {
  fill: var(--svg-color--d59f8d, #D59F8D);
  d: path("M23.407 18.803a.679.679 0 1 1 1.323-.298l.555 2.766a.613.613 0 0 1-1.195.27z");
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zjigynbqy {
  stop-color: var(--svg-color--b1756a, #B1756A);
  stop-opacity: 0;
}

.znvzi0b9x {
  fill: var(--svg-color--d59f8d, #D59F8D);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
