<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iVfAbrI)" class="n5l6-vbop"/><g filter="url(#iNh4sqb)"><circle fill="url(#iHB4Oad)" class="dc3qs961x"/></g><g filter="url(#i467Jvc)"><circle fill="url(#iiMAUpV)" class="epd-gjm1d"/><circle fill="url(#iHcNoKd)" class="epd-gjm1d"/></g><g filter="url(#izAcsYE)"><circle class="q3q-kla0x"/><circle fill="url(#iEhTeWP)" class="t6k9jjfux"/><circle fill="url(#imdOJTi)" class="t6k9jjfux"/></g><g filter="url(#iHwvbWb)"><path class="qvcm7nbab"/><path fill="url(#iIYFhQc)" class="x9uu-xb7k"/><path fill="url(#iTaMgvb)" class="x9uu-xb7k"/><path fill="url(#ixegX7d)" class="x9uu-xb7k"/><path fill="url(#iDi45rc)" class="x9uu-xb7k"/><path fill="url(#iF6dsBb)" class="x9uu-xb7k"/><path fill="url(#ijiPuyb)" class="x9uu-xb7k"/></g><g filter="url(#ieYJXvd)"><path stroke="url(#iXdxkyY)" class="zh2q_cx1x"/></g><path fill="url(#iqIli4b)" class="sunk1qcbw"/><path fill="url(#in5FHsd)" class="sunk1qcbw"/><path fill="url(#iBwFELc)" class="sunk1qcbw"/><path fill="url(#i2lT3Qd)" class="sunk1qcbw"/><path fill="url(#iLEjspc)" class="sunk1qcbw"/><path fill="url(#iEtCT1c)" class="sunk1qcbw"/><path fill="url(#i5EmH2c)" class="sunk1qcbw"/><path fill="url(#ibKQ63d)" class="sunk1qcbw"/><path fill="url(#iBJazie)" class="sunk1qcbw"/><g filter="url(#ilqjU0c)"><path fill="url(#ivqHuIn)" class="od7didcnk"/></g><rect fill="url(#iKLj8me)" class="olnlzjb7t"/><g filter="url(#iajCXHI)"><circle fill="url(#ixorroc)" class="n5l6-vbop"/></g><g filter="url(#iUoum3S)"><path fill="url(#iEoKicc)" class="fl6v4jbox"/><path fill="url(#iEujL4d)" class="fl6v4jbox"/><path fill="url(#ibNieNc)" class="fl6v4jbox"/></g><path fill="url(#iPSuhQb)" class="c0ahgbbyv"/><path fill="url(#iZaiIvd)" class="c0ahgbbyv"/><path fill="url(#iNzGvfc)" class="c0ahgbbyv"/><g filter="url(#iyfG7Ee)"><path fill="url(#i8tUpEo)" class="zqtfuubox"/></g><g filter="url(#iROMsvb)"><path class="nzsr-mvum"/></g><g filter="url(#iGhpDYd)"><path class="mll8ux0_y"/><path fill="url(#iQvU1ac)" class="fd4-7hbff"/><path fill="url(#iMmtktu)" class="fd4-7hbff"/><path fill="url(#iVCwQwd)" class="fd4-7hbff"/><path fill="url(#iNsbfEb)" class="fd4-7hbff"/></g><path fill="url(#iwB954b)" class="fd4-7hbff"/><path stroke="url(#iZpKYhb)" class="gozepcuux"/><g filter="url(#iZANdBu)"><path class="isdzejbfm"/><path fill="url(#ikJwAqb)" class="b5ulksbek"/></g><g filter="url(#iMJIptc)"><path class="b2mce-bxa"/><path fill="url(#iXd56Dv)" class="ndi_upboi"/></g><path class="t-k-ah6xr"/><path fill="url(#irpEA7b)" class="xfusavblz"/><path class="zt6oz3b6p"/><g filter="url(#iTKBhXP)"><path class="vaohs3kzm"/><path fill="url(#iVHuXZd)" class="qjq6rh-_p"/></g><g filter="url(#ikfnfNf)"><path fill="url(#iqjCZSd)" class="gvzi1o5te"/></g><path class="rhzf9746k"/><path fill="url(#iWZ9xad)" class="lk-7fkbne"/><path class="i1zge7bxq"/><g filter="url(#isQY5yc)"><path fill="url(#iWY1FUS)" class="z7i4q1b9v"/></g><g filter="url(#iyr3ZAe)"><ellipse transform="rotate(-27.914 13.3 14.528)" class="e2-y19b3b"/><ellipse fill="url(#iAhQniR)" transform="rotate(-27.914 13.3 14.528)" class="w3y10-85o"/></g><g filter="url(#iLcO1qK)"><path stroke="url(#itgIctb)" class="vgx7mccjp"/></g><g filter="url(#iBoaCtb)"><path stroke="url(#irPTE6d)" class="wr1p58bbk"/></g><path fill="url(#iVE7ioc)" class="b708fac5x"/><path fill="url(#irH7ZXc)" class="b708fac5x"/><path fill="url(#iBEAeMb)" class="glwi1stvd"/><path fill="url(#iuFoaMe)" class="glwi1stvd"/><path fill="url(#irO76xd)" class="sm8pdvbmw"/><path fill="url(#i54kkAe)" class="sm8pdvbmw"/><path fill="url(#iHaSJUd)" class="wjv5_vbkk"/><path fill="url(#i3q9S5S)" class="wjv5_vbkk"/><path stroke="url(#iWidVJc)" class="u3uvgsmzz"/><path stroke="url(#iUbxzJe)" class="u3uvgsmzz"/><path stroke="url(#iLfMX0L)" class="u3uvgsmzz"/><g filter="url(#imZfS5d)"><path stroke="url(#iGpUrFb)" class="q36pexb2h"/></g><path stroke="url(#iBR6SLb)" class="x5fl8bb9z"/><path stroke="url(#igWXlyb)" class="x5fl8bb9z"/><path stroke="url(#iOMwP7b)" class="x5fl8bb9z"/><path stroke="url(#i8yi0qX)" class="x5fl8bb9z"/><path stroke="url(#i13mTbd)" class="z1am7_ptr"/><path stroke="url(#iFw79ge)" class="z1am7_ptr"/><path stroke="url(#iN2CP8b)" class="z1am7_ptr"/><g filter="url(#iZFpg2b)"><path stroke="url(#ilrieDR)" class="fcfdz5b0a"/></g><path stroke="url(#i7xgBhc)" class="uooqxacug"/><path stroke="url(#iBHq0Oc)" class="uooqxacug"/><path stroke="url(#iBfM4kX)" class="uooqxacug"/><path stroke="url(#iDu478c)" class="uooqxacug"/><path stroke="url(#i1CI4jE)" class="xmee_ibwz"/><path stroke="url(#igFMOZz)" class="xmee_ibwz"/><path stroke="url(#iI57S8b)" class="xmee_ibwz"/><path stroke="url(#iyBfcgb)" class="bte4c_-ez"/><path stroke="url(#iaetrBe)" class="bte4c_-ez"/><path stroke="url(#iADDUJe)" class="bte4c_-ez"/><path stroke="url(#ia3PIfu)" class="bte4c_-ez"/><path stroke="url(#ik0FHQd)" class="ygt1ak-zz"/><path stroke="url(#i3N8C0d)" class="ygt1ak-zz"/><g filter="url(#iiFrEkb)"><path stroke="url(#iTzZulb)" class="g4ut9_b3d"/></g><g filter="url(#iVucBPd)"><path stroke="url(#iDdXIne)" class="xuc0fbcps"/></g><path stroke="url(#iyPJYZp)" class="ml3y86b5r"/><path stroke="url(#ieB68Sb)" class="ml3y86b5r"/><path stroke="url(#izKvVmb)" class="ml3y86b5r"/><path stroke="url(#iU1MVbc)" class="ml3y86b5r"/><path fill="url(#idOOQfc)" class="wjv5_vbkk"/><path fill="url(#iW4Kiic)" class="sm8pdvbmw"/><path fill="url(#iKQSnke)" class="sm8pdvbmw"/><g filter="url(#iLw4yEe)"><path fill="url(#ikHG3Sp)" class="o08tmvbnv"/></g><g filter="url(#iDShRjV)"><path stroke="url(#iVsNqkc)" class="bznr9j1-f"/></g><defs><radialGradient id="iVfAbrI" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 9.876 5.795)scale(1.81492)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iHcNoKd" cx="0" cy="0" r="1" gradientTransform="matrix(.90563 -.65944 .75267 1.03366 21.618 15.09)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iEhTeWP" cx="0" cy="0" r="1" gradientTransform="matrix(.89967 -1.65475 .96853 .52658 21.166 16.28)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="imdOJTi" cx="0" cy="0" r="1" gradientTransform="matrix(.28405 .28117 -.36245 .36617 21.211 15.38)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iIYFhQc" cx="0" cy="0" r="1" gradientTransform="matrix(.87399 -3.2389 1.20109 .3241 20.75 10.882)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iTaMgvb" cx="0" cy="0" r="1" gradientTransform="matrix(4.19 .38558 -.20733 2.25294 18.951 8.954)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="ixegX7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.83949 -2.84885 0 15.99 5.957)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iDi45rc" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 24.981 -6.927)scale(4.17484 6.5406)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iF6dsBb" cx="0" cy="0" r="1" gradientTransform="rotate(137.984 9.767 8.323)scale(4.66882 10.7065)" gradientUnits="userSpaceOnUse"><stop class="i1j5fqthb"/><stop offset=".76" class="aei3zobdj"/></radialGradient><radialGradient id="ijiPuyb" cx="0" cy="0" r="1" gradientTransform="matrix(5.09374 2.25 -5.15972 11.68097 8.562 8.625)" gradientUnits="userSpaceOnUse"><stop class="i1j5fqthb"/><stop offset=".76" class="aei3zobdj"/></radialGradient><radialGradient id="in5FHsd" cx="0" cy="0" r="1" gradientTransform="matrix(8.8125 0 0 9.43494 11 29.98)" gradientUnits="userSpaceOnUse"><stop class="q920b5bgt"/><stop offset="1" class="hmv6xsb8e"/></radialGradient><radialGradient id="iBwFELc" cx="0" cy="0" r="1" gradientTransform="matrix(5.25 -8.62501 6.82131 4.1521 23.375 24.34)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="bawjzlb6r"/><stop offset="1" class="ati7d-krq"/></radialGradient><radialGradient id="i2lT3Qd" cx="0" cy="0" r="1" gradientTransform="matrix(3 0 0 4.4849 7.5 29.98)" gradientUnits="userSpaceOnUse"><stop class="qe_-3ab1e"/><stop offset="1" class="chsdmobsg"/></radialGradient><radialGradient id="iLEjspc" cx="0" cy="0" r="1" gradientTransform="matrix(.87505 5.5 -7.00176 1.11398 15.125 19.528)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gwwxrtb_v"/><stop offset="1" class="ssq48xbfd"/></radialGradient><radialGradient id="iEtCT1c" cx="0" cy="0" r="1" gradientTransform="rotate(118.413 2.338 6.06)scale(1.08366 3.24985)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="zpk636z_v"/><stop offset="1" class="mtfxop-pk"/></radialGradient><radialGradient id="i5EmH2c" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 0 0 28.1734 1.625 13.778)" gradientUnits="userSpaceOnUse"><stop class="sg9fyvxai"/><stop offset="1" class="r0adxvbzx"/></radialGradient><radialGradient id="ibKQ63d" cx="0" cy="0" r="1" gradientTransform="matrix(7.00002 10.68753 -3.8615 2.52917 25.625 5.903)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="t4nmlm7ht"/><stop offset="1" class="q4q53m76f"/></radialGradient><radialGradient id="iBJazie" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 .84375 -2.45037 1.58819 23.657 6.466)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="ubeq2y34d"/><stop offset="1" class="r7flkhbpm"/></radialGradient><radialGradient id="ivqHuIn" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.18 16.588)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="xli568bjl"/><stop offset="1" class="dvyuy-plf"/></radialGradient><radialGradient id="iKLj8me" cx="0" cy="0" r="1" gradientTransform="rotate(-125.466 14.933 7.707)scale(3.02812 2.80781)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="wteo2abtt"/><stop offset="1" class="tvzc_9zoc"/></radialGradient><radialGradient id="ixorroc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92241 0 0 3.36423 8.96 15.38)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iEujL4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.43187 1.7623 0 18.56 13.987)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="ibNieNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.5053 1.87198 0 13.567 14.134)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iNzGvfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.95838 -12.1605 0 15.66 13.436)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="rspweobvb"/><stop offset="1" class="nb88f8l_e"/></radialGradient><radialGradient id="iNsbfEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2157 -.69299 0 16.349 17.14)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="ikJwAqb" cx="0" cy="0" r="1" gradientTransform="matrix(.11414 -.66086 1.95511 .33768 18.666 13.097)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iXd56Dv" cx="0" cy="0" r="1" gradientTransform="matrix(.11415 -.66086 1.95522 .33772 13.027 13.097)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="irpEA7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88857 -1.41338 0 18.377 14.633)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVHuXZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.254 -.32731 .45063 -.3497 18.127 14.725)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWZ9xad" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88862 -1.41345 0 13.598 14.633)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iAhQniR" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.963 .898)scale(.5412 .65054)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVE7ioc" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.838 5.69)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dp3nzmbzl"/><stop offset="1" class="wkrt2mblo"/></radialGradient><radialGradient id="irH7ZXc" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.993 5.884)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="i0f64nbug"/><stop offset="1" class="ucmtgi-2a"/></radialGradient><radialGradient id="iBEAeMb" cx="0" cy="0" r="1" gradientTransform="rotate(145.763 11.278 6.459)scale(2.64024 1.85707)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="xr5reebcs"/><stop offset="1" class="z9wcvylbn"/></radialGradient><radialGradient id="iuFoaMe" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.382 -43.869)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="zi5l5kj0o"/><stop offset="1" class="mcuv6-nuk"/></radialGradient><radialGradient id="irO76xd" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.856)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="b9m3k9r2b"/><stop offset="1" class="mkc39zb9h"/></radialGradient><radialGradient id="i54kkAe" cx="0" cy="0" r="1" gradientTransform="matrix(.59766 .66937 -3.1595 2.82105 8.73 3.502)" gradientUnits="userSpaceOnUse"><stop class="wyik6iche"/><stop offset="1" class="g2x2jxbfq"/></radialGradient><radialGradient id="iHaSJUd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57172 2.16536 -4.16467 -4.94623 24.46 5.247)" gradientUnits="userSpaceOnUse"><stop class="c2k9t5bpp"/><stop offset="1" class="y1r1v2b6d"/></radialGradient><radialGradient id="i3q9S5S" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.84)" gradientUnits="userSpaceOnUse"><stop class="h4ehjy6dd"/><stop offset="1" class="bj832jb3d"/></radialGradient><radialGradient id="iUbxzJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.1251 -1.2359 5.3348 -.54 12.864 3.2)" gradientUnits="userSpaceOnUse"><stop offset=".747" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="iLfMX0L" cx="0" cy="0" r="1" gradientTransform="matrix(-.94657 -.97706 .81368 -.7883 14.891 3.829)" gradientUnits="userSpaceOnUse"><stop class="k84rzffkc"/><stop offset="1" class="f63cqv7mt"/></radialGradient><radialGradient id="iOMwP7b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.56426 2.0201 -2.31983 -4.09312 20.913 1.34)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="i8yi0qX" cx="0" cy="0" r="1" gradientTransform="rotate(-80.888 11.73 -9.671)scale(1.42374 5.9709)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="ow_pc7b8u"/><stop offset=".979" class="d9x2ylwjm"/></radialGradient><radialGradient id="iFw79ge" cx="0" cy="0" r="1" gradientTransform="matrix(.01226 -1.01716 4.43025 .05338 14.082 3.665)" gradientUnits="userSpaceOnUse"><stop offset=".747" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="iN2CP8b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.878 8.91 -1.654)scale(1.11775 .93295)" gradientUnits="userSpaceOnUse"><stop class="k84rzffkc"/><stop offset="1" class="f63cqv7mt"/></radialGradient><radialGradient id="iBfM4kX" cx="0" cy="0" r="1" gradientTransform="rotate(130.332 9.717 4.866)scale(5.09325 5.91748)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="iDu478c" cx="0" cy="0" r="1" gradientTransform="matrix(.09206 -1.68795 4.97536 .27136 18.499 4.228)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="dk1glybfm"/><stop offset=".979" class="a0yyvkbzn"/></radialGradient><radialGradient id="igFMOZz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21324 6.39051 0 13.808 4.608)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="iI57S8b" cx="0" cy="0" r="1" gradientTransform="rotate(-130.37 8.836 -.999)scale(1.0406 .9935)" gradientUnits="userSpaceOnUse"><stop class="k84rzffkc"/><stop offset="1" class="f63cqv7mt"/></radialGradient><radialGradient id="iADDUJe" cx="0" cy="0" r="1" gradientTransform="rotate(146.114 9.14 4.448)scale(3.02405 3.27841)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="ia3PIfu" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13777 3.28035 0 18.35 4.557)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="dk1glybfm"/><stop offset=".979" class="a0yyvkbzn"/></radialGradient><radialGradient id="i3N8C0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.01775 -1.34298 3.63064 -.04798 13.474 5.755)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="izKvVmb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23453 3.00551 -3.33751 -2.48137 19.584 3.07)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="iU1MVbc" cx="0" cy="0" r="1" gradientTransform="matrix(.10954 -1.26306 4.00443 .3473 18.771 5.622)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="dk1glybfm"/><stop offset=".829" class="a0yyvkbzn"/></radialGradient><radialGradient id="idOOQfc" cx="0" cy="0" r="1" gradientTransform="rotate(99.386 9.326 10.139)scale(4.22369 15.0701)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="e9zt1qbrs"/><stop offset="1" class="tenu6ccuh"/></radialGradient><radialGradient id="iW4Kiic" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 8.997 -1.343)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="n-vzpx_le"/><stop offset="1" class="g15wokvee"/></radialGradient><radialGradient id="iKQSnke" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.564 6.54)" gradientUnits="userSpaceOnUse"><stop class="ui8aeifuz"/><stop offset="1" class="xok7o2bsm"/></radialGradient><radialGradient id="ikHG3Sp" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53124 -8.125 5.12798 -2.85982 9.094 24.872)" gradientUnits="userSpaceOnUse"><stop class="x034jqb5d"/><stop offset="1" class="rpjijqwhi"/></radialGradient><linearGradient id="iHB4Oad" x1="10.789" x2="10.088" y1="15.685" y2="15.685" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iiMAUpV" x1="22.401" x2="21.504" y1="14.184" y2="16.963" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iXdxkyY" x1="10.883" x2="10.883" y1="10.001" y2="12.364" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="iqIli4b" x1="22.825" x2=".452" y1="30.767" y2="8.819" gradientUnits="userSpaceOnUse"><stop class="b9v5e-b3e"/><stop offset="1" class="t_qwphcjx"/></linearGradient><linearGradient id="iEoKicc" x1="20.412" x2="12.046" y1="15.807" y2="17.053" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iPSuhQb" x1="10.079" x2="12.14" y1="18.76" y2="18.687" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iZaiIvd" x1="21.381" x2="20.163" y1="17.838" y2="17.732" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="i8tUpEo" x1="15.408" x2="24.33" y1="12.537" y2="9.343" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iQvU1ac" x1="15.044" x2="16.072" y1="16.529" y2="16.529" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iMmtktu" x1="17.018" x2="15.895" y1="16.882" y2="16.866" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iVCwQwd" x1="16.203" x2="16.203" y1="17.695" y2="17.067" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iwB954b" x1="16.128" x2="16.128" y1="17.741" y2="17.558" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="iZpKYhb" x1="14.854" x2="15.331" y1="19.465" y2="18.711" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iqjCZSd" x1="19.229" x2="18.886" y1="14.692" y2="14.904" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWY1FUS" x1="14.412" x2="14.069" y1="14.692" y2="14.903" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itgIctb" x1="19.247" x2="18.786" y1="12.348" y2="11.407" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="irPTE6d" x1="13.435" x2="12.133" y1="12.208" y2="11.662" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iWidVJc" x1="14.261" x2="10.736" y1="2.578" y2="4.339" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="iGpUrFb" x1="14.299" x2="11.472" y1="2.485" y2="4.322" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><linearGradient id="iBR6SLb" x1="19.032" x2="21.102" y1="2.578" y2="3.024" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="igWXlyb" x1="16.583" x2="21.672" y1="3.136" y2="3.68" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="i13mTbd" x1="15.286" x2="12.235" y1="3.287" y2="4.413" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="ilrieDR" x1="15.432" x2="12.281" y1="3.175" y2="4.558" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><linearGradient id="i7xgBhc" x1="18.499" x2="20.126" y1="3.268" y2="3.598" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="iBHq0Oc" x1="15.618" x2="20.781" y1="4.249" y2="4.225" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="i1CI4jE" x1="14.956" x2="12.465" y1="4.156" y2="5.267" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="iyBfcgb" x1="18.35" x2="19.914" y1="4.156" y2="4.224" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="iaetrBe" x1="16.317" x2="19.96" y1="4.565" y2="4.537" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="ik0FHQd" x1="14.472" x2="11.788" y1="5.117" y2="5.732" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="iTzZulb" x1="14.505" x2="12.194" y1="5.192" y2="5.914" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><linearGradient id="iDdXIne" x1="15.088" x2="11.938" y1="4.035" y2="5.417" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><linearGradient id="iyPJYZp" x1="19.589" x2="20.216" y1="5.244" y2="5.371" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="ieB68Sb" x1="16.849" x2="20.295" y1="5.872" y2="5.859" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="iVsNqkc" x1="11.267" x2="7.298" y1="23.512" y2="27.637" gradientUnits="userSpaceOnUse"><stop class="tuzqszfby"/><stop offset="1" class="ljv2-xbix"/></linearGradient><filter id="iNh4sqb" width="3.18" height="3.18" x="9.199" y="13.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".25"/></filter><filter id="i467Jvc" width="3.908" height="3.908" x="19.382" y="13.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3724"/></filter><filter id="izAcsYE" width="3.18" height="3.18" x="19.621" y="13.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".25"/></filter><filter id="iHwvbWb" width="13.805" height="9.311" x="9.088" y="5.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3724"/></filter><filter id="ieYJXvd" width="1.033" height="2.414" x="10.367" y="9.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".125"/></filter><filter id="ilqjU0c" width="15.688" height="8.156" x="9.357" y="22.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".375"/></filter><filter id="iajCXHI" width="3.858" height="3.658" x="8.96" y="13.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3724"/></filter><filter id="iUoum3S" width="11.364" height="13.426" x="10.34" y="9.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3724"/></filter><filter id="iyfG7Ee" width="8.651" height="7.359" x="14.177" y="7.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation="1"/></filter><filter id="iROMsvb" width="3.428" height="4.437" x="14.015" y="14.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".375"/></filter><filter id="iGhpDYd" width="2.556" height="3.437" x="14.712" y="14.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".125"/></filter><filter id="iZANdBu" width="3.24" height="2.014" x="17.285" y="11.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3724"/></filter><filter id="iMJIptc" width="3.24" height="2.014" x="11.646" y="11.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3724"/></filter><filter id="iTKBhXP" width=".843" height=".744" x="17.583" y="14.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".05"/></filter><filter id="ikfnfNf" width=".938" height=".962" x="18.512" y="14.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".1"/></filter><filter id="isQY5yc" width="1.042" height="1.101" x="13.646" y="14.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".1"/></filter><filter id="iyr3ZAe" width=".981" height=".753" x="12.81" y="14.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".05"/></filter><filter id="iLcO1qK" width="3.526" height="1.972" x="17.06" y="11.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".25"/></filter><filter id="iBoaCtb" width="3.611" height="2.035" x="11.342" y="11.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".25"/></filter><filter id="imZfS5d" width="3.938" height="1.28" x="10.688" y="2.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".125"/></filter><filter id="iZFpg2b" width="3.966" height="1.018" x="11.791" y="2.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".125"/></filter><filter id="iiFrEkb" width="2.922" height="1.004" x="11.925" y="4.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".125"/></filter><filter id="iVucBPd" width="3.966" height="1.018" x="11.448" y="3.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".125"/></filter><filter id="iLw4yEe" width="9.632" height="11.909" x="1.844" y="15.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".25"/></filter><filter id="iDShRjV" width="4.094" height="4.656" x="7.923" y="22.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3724" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-gesturing-ok-medium" /></template>
<style>
.a0yyvkbzn {
  stop-color: var(--svg-color--a48369, #A48369);
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.aei3zobdj {
  stop-color: var(--svg-color--1f1d24, #1F1D24);
  stop-opacity: 0;
}

.ati7d-krq {
  stop-color: var(--svg-color--298dff, #298DFF);
  stop-opacity: 0;
}

.b2mce-bxa {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m11.857 12.4l.002-.002l.005-.005l.013-.01l.04-.03q.048-.035.13-.088c.11-.068.264-.153.46-.23a3.1 3.1 0 0 1 1.635-.174a.585.585 0 1 1-.182 1.155a1.93 1.93 0 0 0-1.023.106a1.7 1.7 0 0 0-.33.175l-.008.006a.585.585 0 0 1-.743-.902");
}

.b5ulksbek {
  d: path("M20.065 12.4h-.001l-.002-.002l-.005-.005l-.013-.01l-.04-.03a2.8 2.8 0 0 0-.59-.319a3.1 3.1 0 0 0-1.635-.173a.585.585 0 1 0 .182 1.155c.436-.069.785.012 1.023.106a1.7 1.7 0 0 1 .33.175l.008.006a.585.585 0 0 0 .743-.903");
}

.b708fac5x {
  d: path("m7.397 4.625l-.428.666a.24.24 0 0 0 .01.279c.9 1.155 2.374 1.8 3.283 2.087a.244.244 0 0 0 .281-.108c.15-.247.354-.584.409-.69c.069-.13-.029-.231-.086-.265L7.85 4.766l.125-.274c-.35-.106-.53.045-.578.133");
}

.b9m3k9r2b {
  stop-color: var(--svg-color--ae8671, #AE8671);
}

.b9v5e-b3e {
  stop-color: var(--svg-color--3ca8ff, #3CA8FF);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bawjzlb6r {
  stop-color: var(--svg-color--298dff, #298DFF);
}

.bj832jb3d {
  stop-color: var(--svg-color--9a7d65, #9A7D65);
  stop-opacity: 0;
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bte4c_-ez {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.293c-.43-.11-1.281-.203-2.297-.078");
}

.bznr9j1-f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.673 26.668c.48-.448 1.669-1.706 2.594-3.156");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c0ahgbbyv {
  d: path("M10.34 13.133c0-.292.117-.643.352-.818l.177-.175c.293-.234.411-.585.411-.935v-.935a.57.57 0 0 1 .47-.584c.705-.175 2.174-.468 4.29-.468s3.584.293 4.29.468c.234.058.47.292.47.584v.935c0 .35.175.701.41.935c.55.385.516.597.47 1.051a51 51 0 0 0-.117 1.578h.02l-.291 4.336c-.176 1.939-1.7 3.29-3.517 3.29h-3.517c-1.876 0-3.341-1.351-3.517-3.29c-.153-1.99-.22-3.985-.401-5.972");
}

.c2k9t5bpp {
  stop-color: var(--svg-color--c9a083, #C9A083);
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.chsdmobsg {
  stop-color: var(--svg-color--499efa, #499EFA);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d9x2ylwjm {
  stop-color: var(--svg-color--b99477, #B99477);
}

.dc3qs961x {
  cx: 10.789px;
  cy: 15.38px;
  r: 1.09px;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dk1glybfm {
  stop-color: var(--svg-color--a48369, #A48369);
  stop-opacity: 0;
}

.dp3nzmbzl {
  stop-color: var(--svg-color--2d99fd, #2D99FD);
}

.dvyrp5bps {
  stop-color: var(--svg-color--916855, #916855);
}

.dvyuy-plf {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
  stop-opacity: 0;
}

.dz3ns1n_g {
  stop-color: var(--svg-color--c39d8a, #C39D8A);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2-y19b3b {
  cx: 13.301px;
  cy: 14.528px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.427px;
  ry: 0.216px;
}

.e4s700vze {
  stop-color: var(--svg-color--764b4b, #764B4B);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e9zt1qbrs {
  stop-color: var(--svg-color--9e6d71, #9E6D71);
  stop-opacity: 0;
}

.epd-gjm1d {
  cx: 21.211px;
  cy: 15.38px;
  r: 1.829px;
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f63cqv7mt {
  stop-color: var(--svg-color--82594c, #82594C);
  stop-opacity: 0;
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fcfdz5b0a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.167 3.365c.43-.11 2.2-.359 3.216-.234");
}

.fd4-7hbff {
  d: path("m15.572 15.067l-.582 1.862a.59.59 0 0 0 .57.766h.861a.592.592 0 0 0 .57-.766l-.582-1.862c-.125-.412-.707-.412-.837 0");
}

.fjos8cb-d {
  stop-color: var(--svg-color--764b4b, #764B4B);
  stop-opacity: 0;
}

.fl6v4jbox {
  d: path("m10.404 14.709l.053.002s-.058-.935-.117-1.578c0-.292.117-.643.352-.818l.177-.175c.293-.234.411-.585.411-.935v-.935a.57.57 0 0 1 .47-.584c.705-.175 2.174-.468 4.29-.468s3.584.293 4.29.468c.234.058.47.292.47.584v.935c0 .35.175.701.41.935c.55.385.516.597.47 1.051a51 51 0 0 0-.117 1.578h.02l-.291 4.336c-.176 1.939-1.7 3.29-3.517 3.29h-3.517c-1.876 0-3.341-1.351-3.517-3.29z");
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g15wokvee {
  stop-color: var(--svg-color--925a61, #925A61);
  stop-opacity: 0;
}

.g2x2jxbfq {
  stop-color: var(--svg-color--907664, #907664);
  stop-opacity: 0;
}

.g4ut9_b3d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.3 5.371c.274-.101 1.102-.304 2.172-.242");
}

.glwi1stvd {
  d: path("m24.76 4.625l.428.666a.24.24 0 0 1-.01.279c-.899 1.155-2.373 1.8-3.283 2.087a.244.244 0 0 1-.28-.108a22 22 0 0 1-.41-.69c-.068-.13.03-.231.087-.265l3.015-1.828l-.125-.274c.35-.106.531.045.578.133");
}

.gozepcuux {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.496 18.405a.22.22 0 0 0-.26.044a.2.2 0 0 0-.021.257c.376.57 1.03.948 1.776.948c.745 0 1.4-.379 1.775-.948a.2.2 0 0 0-.022-.259a.22.22 0 0 0-.259-.043a3.2 3.2 0 0 1-1.494.355a3.24 3.24 0 0 1-1.495-.354Z");
}

.gvzi1o5te {
  d: path("M19.25 14.96a.92.92 0 0 0-.253-.508l-.285.313l.129.25z");
}

.gwwxrtb_v {
  stop-color: var(--svg-color--1d5894, #1D5894);
}

.h-qwb4b2p {
  stop-color: var(--svg-color--947061, #947061);
  stop-opacity: 0;
}

.h4ehjy6dd {
  stop-color: var(--svg-color--9a7d65, #9A7D65);
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hmv6xsb8e {
  stop-color: var(--svg-color--2691ff, #2691FF);
  stop-opacity: 0;
}

.i-v4lm-fq {
  stop-color: var(--svg-color--99755e, #99755E);
  stop-opacity: 0;
}

.i0f64nbug {
  stop-color: var(--svg-color--49abff, #49ABFF);
}

.i1j5fqthb {
  stop-color: var(--svg-color--1f1d24, #1F1D24);
}

.i1zge7bxq {
  fill: var(--svg-color--000, #000);
  d: path("M14.155 15.088a.557.557 0 0 0-.56-.56a.558.558 0 0 0-.497.817h.99a.56.56 0 0 0 .067-.257");
}

.i4aahzyol {
  stop-color: var(--svg-color--99755e, #99755E);
}

.isdzejbfm {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M20.065 12.4h-.001l-.002-.002l-.005-.005l-.013-.01l-.04-.03a2.8 2.8 0 0 0-.59-.319a3.1 3.1 0 0 0-1.635-.173a.585.585 0 1 0 .182 1.155c.436-.069.785.012 1.023.106a1.7 1.7 0 0 1 .33.175l.008.006a.585.585 0 0 0 .743-.903");
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jjmtttbid {
  stop-color: var(--svg-color--916b60, #916B60);
}

.k84rzffkc {
  stop-color: var(--svg-color--82594c, #82594C);
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljv2-xbix {
  stop-color: var(--svg-color--3b95f9, #3B95F9);
  stop-opacity: 0;
}

.lk-7fkbne {
  d: path("M13.596 14.11a.978.978 0 0 0-.942 1.236h1.888q.034-.127.035-.258a.984.984 0 0 0-.982-.978");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcuv6-nuk {
  stop-color: var(--svg-color--4298d4, #4298D4);
  stop-opacity: 0;
}

.mgz6y4bsd {
  stop-color: var(--svg-color--ab8570, #AB8570);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mkc39zb9h {
  stop-color: var(--svg-color--a58268, #A58268);
}

.ml3y86b5r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.857 5.371c-.273-.101-1.101-.304-2.171-.242");
}

.mll8ux0_y {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.572 15.067l-.582 1.862a.59.59 0 0 0 .57.766h.861a.592.592 0 0 0 .57-.766l-.582-1.862c-.125-.412-.707-.412-.837 0");
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mtfxop-pk {
  stop-color: var(--svg-color--43bbff, #43BBFF);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n-vzpx_le {
  stop-color: var(--svg-color--925a61, #925A61);
}

.n5l6-vbop {
  cx: 10.789px;
  cy: 15.38px;
  r: 1.829px;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nb88f8l_e {
  stop-color: var(--svg-color--83556d, #83556D);
}

.ndi_upboi {
  d: path("m11.857 12.4l.002-.002l.005-.005l.013-.01l.04-.03q.048-.035.13-.088c.11-.068.264-.153.46-.23a3.1 3.1 0 0 1 1.635-.174a.585.585 0 1 1-.182 1.155a1.93 1.93 0 0 0-1.023.106a1.7 1.7 0 0 0-.33.175l-.008.006a.585.585 0 0 1-.743-.902");
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.nzsr-mvum {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.689 15.246l-.899 1.862c-.111.383.156.766.535.766h.807c.38 0 .646-.389.535-.766l-.546-1.862c-.117-.412-.31-.412-.432 0");
}

.o08tmvbnv {
  d: path("M7.788 26.781L2.344 16.684l4.594-.812l4.038 7.878c-1.35 2.025-2.688 2.864-3.188 3.031");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od7didcnk {
  d: path("M23.873 27.137c-1.95-1.2-3.036-3.417-3.36-4.156c-5.174 0-9.28 1.968-10.406 6.656h14.188c0-.9-.156-1.937-.422-2.5");
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.olnlzjb7t {
  width: 4.615px;
  height: 6.587px;
  x: 13.668px;
  y: 17.976px;
  rx: 2.307px;
}

.ow_pc7b8u {
  stop-color: var(--svg-color--b99477, #B99477);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q36pexb2h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.064 3.02c.68-.344 2.468-.57 3.187-.524");
}

.q3q-kla0x {
  cx: 21.211px;
  cy: 15.38px;
  r: 1.09px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.q4q53m76f {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
  stop-opacity: 0;
}

.q920b5bgt {
  stop-color: var(--svg-color--2691ff, #2691FF);
}

.qe_-3ab1e {
  stop-color: var(--svg-color--499efa, #499EFA);
}

.qjq6rh-_p {
  d: path("M18.308 14.317c.07.093-.076.207-.242.33s-.288.211-.358.118s.008-.269.174-.393c.165-.123.356-.148.426-.055");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvcm7nbab {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m21.27 8.284l.47.233c.822.41 1.292 1.344 1.116 2.337l-.647 3.33c-.057.345-.285.576-.626.585h-.02s.059-.993.118-1.578c.047-.474-.035-.619-.47-1.051c-.235-.234-.412-.585-.412-.935v-.935c0-.292-.235-.526-.47-.584c-.705-.175-2.174-.468-4.29-.468s-3.584.293-4.289.468a.57.57 0 0 0-.47.584v.935c0 .35-.117.701-.411.935l-.177.175c-.235.175-.352.526-.352.818c.059.643.117 1.578.117 1.578l-.053-.002a.694.694 0 0 1-.652-.583l-.646-3.33c-.118-.935.352-1.87 1.175-2.279l.47-.233c.294-.176.588-.41.882-.643l1.057-1.11c.647-.584 1.587-.76 2.41-.35a3.2 3.2 0 0 0 1.821 0c.881-.293 1.88-.06 2.585.584l.882.876c.235.292.529.467.881.643");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r0adxvbzx {
  stop-color: var(--svg-color--54acf3, #54ACF3);
  stop-opacity: 0;
}

.r7flkhbpm {
  stop-color: var(--svg-color--419ae2, #419AE2);
  stop-opacity: 0;
}

.re3qjtb0n {
  stop-color: var(--svg-color--916855, #916855);
  stop-opacity: 0;
}

.rhzf9746k {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.369 13.813a1.53 1.53 0 0 0-1.484 1.16a.3.3 0 0 0 .293.372h2.444c.155 0 .28-.142.249-.297a1.534 1.534 0 0 0-1.502-1.235");
}

.rpjijqwhi {
  stop-color: var(--svg-color--2882ff, #2882FF);
  stop-opacity: 0;
}

.rspweobvb {
  stop-color: var(--svg-color--996276, #996276);
  stop-opacity: 0;
}

.sg9fyvxai {
  stop-color: var(--svg-color--54acf3, #54ACF3);
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.sm8pdvbmw {
  d: path("M9.515 3.075a61 61 0 0 0-1.79 1.61a.08.08 0 0 0-.027.054c-.033.574 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.004 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.218.695-.414c.064-.132.065-.316-.029-.523a.63.63 0 0 0 .442-.281a.64.64 0 0 0 .056-.625c.156-.063.337-.304.313-.649c-.038-.537-.563-.661-.782-.656h-.164c.013-.55-.585-.6-.814-.574l-1.717.097a.98.98 0 0 0-.766-.132c-.432.122-1.263.338-2.093 1.047");
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.ssq48xbfd {
  stop-color: var(--svg-color--1d5894, #1D5894);
  stop-opacity: 0;
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.sunk1qcbw {
  d: path("M7.312 5.356c-.203-.057-.676-.155-.945-.086c-.336.086-.594.328-.812.687c-.175.288-1.47 2.48-2.094 3.54c-.563.822-1.625 3.087-1.375 5.562c.1 1.662.781 3.339 1.11 3.969l4.132 7.854c.173.33.187.719.08 1.076c-.158.529-.322 1.28-.322 2.023h17.828c0-.743-.164-1.494-.322-2.023a1.43 1.43 0 0 1 .08-1.076l4.133-7.854c.328-.63 1.01-2.307 1.11-3.97c.25-2.474-.813-4.739-1.376-5.562a915 915 0 0 0-2.094-3.539c-.218-.359-.476-.601-.812-.687c-.269-.069-.742.029-.945.086L21.5 7.52c-.352.414-.19.966-.055 1.18l2.075 3.511a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a50 50 0 0 0-1.343-.59c-.295.138-.22.126-.551.176v.29a2.307 2.307 0 0 1-4.615 0v-.385c-.298-.05-.329.076-.593-.043c-.418.156-1.092.472-1.252.552a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382L10.555 8.7c.135-.214.297-.766-.055-1.18z");
}

.t_qwphcjx {
  stop-color: var(--svg-color--2a99ff, #2A99FF);
}

.t-k-ah6xr {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.606 13.813c.715 0 1.32.493 1.484 1.16a.3.3 0 0 1-.293.372h-2.444a.252.252 0 0 1-.249-.297a1.53 1.53 0 0 1 1.502-1.235");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t4nmlm7ht {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
}

.t6k9jjfux {
  cx: 21.211px;
  cy: 15.38px;
  r: 1.09px;
}

.tenu6ccuh {
  stop-color: var(--svg-color--6a4046, #6A4046);
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tuzqszfby {
  stop-color: var(--svg-color--3a95fa, #3A95FA);
}

.tvzc_9zoc {
  stop-color: var(--svg-color--7f5365, #7F5365);
}

.u3uvgsmzz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.176c.68-.344 2.469-.57 3.188-.523");
}

.ubeq2y34d {
  stop-color: var(--svg-color--419ae2, #419AE2);
}

.ucmtgi-2a {
  stop-color: var(--svg-color--49abff, #49ABFF);
  stop-opacity: 0;
}

.ui8aeifuz {
  stop-color: var(--svg-color--b48376, #B48376);
}

.uooqxacug {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.598c-.43-.11-2.375-.477-3.255-.266");
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.vaohs3kzm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.308 14.317c.07.093-.076.207-.242.33s-.288.211-.358.118s.008-.269.174-.393c.165-.123.356-.148.426-.055");
}

.vgx7mccjp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.81 12.242c.47-.083 1.39-.059 2.026.436");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w3y10-85o {
  cx: 13.301px;
  cy: 14.528px;
  rx: 0.427px;
  ry: 0.216px;
}

.wjf3cr6ec {
  stop-color: var(--svg-color--c39d8a, #C39D8A);
}

.wjv5_vbkk {
  d: path("M22.643 3.075a61 61 0 0 1 1.79 1.61a.08.08 0 0 1 .026.054c.033.574-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.004-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.218-.696-.414c-.064-.132-.064-.316.03-.523a.63.63 0 0 1-.442-.281a.64.64 0 0 1-.057-.625c-.156-.063-.336-.304-.312-.649c.037-.537.562-.661.781-.656h.164c-.012-.55.585-.6.815-.574l1.717.097a.98.98 0 0 1 .765-.132c.432.122 1.263.338 2.094 1.047");
}

.wkrt2mblo {
  stop-color: var(--svg-color--1284d5, #1284D5);
}

.wr1p58bbk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.092 12.81c.358-.317 1.14-.65 2.11-.496");
}

.wteo2abtt {
  stop-color: var(--svg-color--b88d82, #B88D82);
}

.wyik6iche {
  stop-color: var(--svg-color--907664, #907664);
}

.x034jqb5d {
  stop-color: var(--svg-color--2882ff, #2882FF);
}

.x5fl8bb9z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.176c-.68-.344-2.47-.57-3.188-.523");
}

.x9uu-xb7k {
  d: path("m21.27 8.284l.47.233c.822.41 1.292 1.344 1.116 2.337l-.647 3.33c-.057.345-.285.576-.626.585h-.02s.059-.993.118-1.578c.047-.474-.035-.619-.47-1.051c-.235-.234-.412-.585-.412-.935v-.935c0-.292-.235-.526-.47-.584c-.705-.175-2.174-.468-4.29-.468s-3.584.293-4.289.468a.57.57 0 0 0-.47.584v.935c0 .35-.117.701-.411.935l-.177.175c-.235.175-.352.526-.352.818c.059.643.117 1.578.117 1.578l-.053-.002a.694.694 0 0 1-.652-.583l-.646-3.33c-.118-.935.352-1.87 1.175-2.279l.47-.233c.294-.176.588-.41.882-.643l1.057-1.11c.647-.584 1.587-.76 2.41-.35a3.2 3.2 0 0 0 1.821 0c.881-.293 1.88-.06 2.585.584l.882.876c.235.292.529.467.881.643");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xfusavblz {
  d: path("M18.38 14.11a.977.977 0 0 1 .942 1.236h-1.889a.98.98 0 0 1 .946-1.235");
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xli568bjl {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
}

.xmee_ibwz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.293c.43-.11 1.28-.203 2.296-.078");
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xok7o2bsm {
  stop-color: var(--svg-color--b48376, #B48376);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xr5reebcs {
  stop-color: var(--svg-color--4bb4ff, #4BB4FF);
}

.xuc0fbcps {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.823 4.224c.43-.109 2.2-.358 3.216-.233");
}

.y1r1v2b6d {
  stop-color: var(--svg-color--97735c, #97735C);
}

.ygt1ak-zz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.371c.274-.101 1.102-.304 2.172-.242");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z1am7_ptr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.62 3.48c.43-.109 1.65-.273 2.666-.148");
}

.z7i4q1b9v {
  d: path("M14.489 14.973c0-.316-.257-.527-.327-.59l-.316.305l.195.396z");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.z9wcvylbn {
  stop-color: var(--svg-color--347bc6, #347BC6);
}

.zh2q_cx1x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.025 10.11v.982c-.009.163-.077.527-.283.682");
}

.zi5l5kj0o {
  stop-color: var(--svg-color--4298d4, #4298D4);
}

.zpfboqufv {
  stop-color: var(--svg-color--ab8570, #AB8570);
  stop-opacity: 0;
}

.zpk636z_v {
  stop-color: var(--svg-color--43bbff, #43BBFF);
}

.zqtfuubox {
  d: path("m20.332 9.218l-3.37 1.124a1.147 1.147 0 0 0 .514 2.226l3.352-.45z");
}

.zt6oz3b6p {
  fill: var(--svg-color--000, #000);
  d: path("M17.82 15.088c0-.311.249-.56.56-.56a.557.557 0 0 1 .497.817h-.99a.5.5 0 0 1-.067-.257");
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
