<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPdZ9hd)"><path class="n2ljw7bum"/></g><path fill="url(#iT4BEec)" class="yjs_1lmgw"/><g filter="url(#i6id4qU)"><path fill="url(#ilFKzlc)" class="wrjncmbvl"/></g><g filter="url(#iueMkdd)"><path stroke="url(#i77yBdc)" class="j27_zub1v"/></g><g filter="url(#iqBHoub)"><path stroke="url(#ibZ2sCe)" class="wqoser8ru"/></g><g filter="url(#i0eAOPe)"><path stroke="url(#iMq826c)" class="r_n1v7r5p"/></g><g filter="url(#i4Sx3yb)"><path fill="url(#iS9uZ5d)" class="m275xhwfx"/><path fill="url(#iWwRv5I)" class="m275xhwfx"/><path fill="url(#iAd8VBd)" class="m275xhwfx"/></g><path fill="url(#iyHOuOc)" class="vgjfbsb7l"/><path fill="url(#i7VBsyx)" class="vgjfbsb7l"/><path fill="url(#iH2NTle)" class="vgjfbsb7l"/><path fill="url(#iE3xHuc)" class="vgjfbsb7l"/><g filter="url(#iBic00b)"><rect class="txp88d1_z"/><rect fill="url(#iNKFmde)" class="uc68slbrm"/></g><g filter="url(#iq619Hd)"><path fill="url(#imyDoTc)" class="i9c-eob6c"/><path fill="url(#ieCLF6d)" class="i9c-eob6c"/><path fill="url(#i6UTi5W)" class="i9c-eob6c"/></g><g filter="url(#i22LJfe)"><path fill="url(#iNj1Vtc)" class="cv_2u2b1j"/><path fill="url(#iCFtYsx)" class="cv_2u2b1j"/><path fill="url(#iHR30zc)" class="cv_2u2b1j"/><path fill="url(#ixhglsb)" class="cv_2u2b1j"/><path fill="url(#iNMwGWb)" class="cv_2u2b1j"/></g><path fill="url(#i0PhYgb)" class="nid47tbzi"/><path fill="url(#iatuWTb)" class="nid47tbzi"/><path fill="url(#iUgxfUd)" class="nid47tbzi"/><path fill="url(#iWzWLLb)" class="nid47tbzi"/><path fill="url(#iPaWPYd)" class="dxbw9fmxo"/><path fill="url(#iyrl8qd)" class="dxbw9fmxo"/><g filter="url(#ifXPbLd)"><path fill="url(#iZBmsmd)" class="t06-rzbwx"/><path fill="url(#ioWLCLe)" class="t06-rzbwx"/><path fill="url(#iGiOxee)" class="t06-rzbwx"/></g><path fill="url(#iBSWCxe)" class="jqtbx6bdj"/><path fill="url(#inW3s3b)" class="jqtbx6bdj"/><path fill="url(#i8viBkc)" class="jqtbx6bdj"/><path fill="url(#iRNtjEb)" class="jqtbx6bdj"/><g filter="url(#iPTImQe)"><path stroke="url(#iv0YjMe)" class="doky60syc"/></g><g filter="url(#ilbUkHb)"><path stroke="url(#iekjRMb)" class="t1qofdbri"/></g><g filter="url(#i9avDUd)"><path fill="url(#iuS78cd)" class="uxmx_b5qt"/></g><g filter="url(#i1jfjJc)"><path stroke="url(#icAMA8b)" class="h8f39p-0t"/></g><g filter="url(#iCNVHSb)"><path stroke="url(#iTqnyxe)" class="ilhx4zbpd"/></g><g filter="url(#ivvJDHe)"><path stroke="url(#iK6wiUb)" class="jt0iaf2nr"/></g><g filter="url(#iuwMGKb)"><circle fill="url(#idc1wjd)" class="k8f-b6tly"/></g><g filter="url(#iBDSxWd)"><circle fill="url(#itlD5gc)" class="df0eo_byv"/></g><g filter="url(#iYtonte)"><circle fill="url(#ifnByve)" class="rq16spb6n"/><circle fill="url(#i8sMhac)" class="rq16spb6n"/></g><g filter="url(#ivRdvmc)"><circle class="dmf7ibb4u"/><circle fill="url(#iuKh38L)" class="bh6f89byw"/><circle fill="url(#i3k4bId)" class="bh6f89byw"/></g><g filter="url(#iPC9WSS)"><path fill="url(#iPJ0CZd)" class="vwqo82iho"/><path fill="url(#i8LaUec)" class="vwqo82iho"/><path fill="url(#iVKmSdb)" class="vwqo82iho"/><path fill="url(#iDybnYd)" class="vwqo82iho"/><path fill="url(#iqPME2k)" class="vwqo82iho"/></g><g filter="url(#ip7CBhZ)"><path class="m8te_ab5w"/><path fill="url(#iRFfb9b)" class="kw6ccvhnj"/><path fill="url(#iJ0VoQd)" class="kw6ccvhnj"/><path fill="url(#iBFvk9d)" class="kw6ccvhnj"/><path fill="url(#iHF9aFd)" class="kw6ccvhnj"/><path fill="url(#i8pVhjc)" class="kw6ccvhnj"/></g><path fill="url(#iPavsvb)" class="kw6ccvhnj"/><path fill="url(#ikFS0Jd)" class="kw6ccvhnj"/><g filter="url(#iOn9FIt)"><path class="px8lptbkt"/></g><g filter="url(#iRUnjPb)"><path class="w68lhtwwn"/><path fill="url(#inycxMd)" class="uotkb3-yl"/><path fill="url(#iFDoKnc)" class="uotkb3-yl"/><path fill="url(#ixEDoIe)" class="uotkb3-yl"/></g><path stroke="url(#iC378lc)" class="l0mey06vx"/><g filter="url(#iAAPVse)"><path class="gmg9qbkwd"/></g><g filter="url(#izU48ae)"><path class="q0dmax7dd"/></g><path class="vw0r--b4a"/><path fill="url(#i6EyeCd)" class="y_66wxvct"/><path class="kwq24xrzi"/><g filter="url(#imtHvae)"><path class="vacnm89zp"/><path fill="url(#iYHVHUc)" class="ga1jnhb0w"/></g><g filter="url(#i8Qdoii)"><path fill="url(#iOiTNHc)" class="unhp_hi6j"/></g><path class="kihb0lb2k"/><path fill="url(#i5TlN9c)" class="acx3wxb5i"/><path class="kwkhc9bqp"/><g filter="url(#i2LDLZb)"><path fill="url(#iwI1iwc)" class="gnxfttbkz"/></g><g filter="url(#ijVe7Je)"><ellipse transform="rotate(-27.914 13.431 6.532)" class="zx29jrbqo"/><ellipse fill="url(#i2onmee)" transform="rotate(-27.914 13.431 6.532)" class="npl8uhbaw"/></g><g filter="url(#i4zmcNd)"><path stroke="url(#iS7Viob)" class="xrch4ccua"/></g><g filter="url(#i6ra8mc)"><path stroke="url(#iaX62qb)" class="acvm8_bqb"/></g><defs><radialGradient id="iT4BEec" cx="0" cy="0" r="1" gradientTransform="matrix(12.502 -3.897 4.76721 15.29373 8.201 25.12)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="ilFKzlc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 20.046 20.648)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="iS9uZ5d" cx="0" cy="0" r="1" gradientTransform="matrix(7.75852 4.4892 -3.11118 5.37693 16.862 11.13)" gradientUnits="userSpaceOnUse"><stop class="eufzeuc-t"/><stop offset="1" class="mj415ib8l"/></radialGradient><radialGradient id="iWwRv5I" cx="0" cy="0" r="1" gradientTransform="matrix(2.09374 2.54688 -.87207 .71691 17.692 13.742)" gradientUnits="userSpaceOnUse"><stop class="tkq_smxzd"/><stop offset="1" class="hyal6rbtf"/></radialGradient><radialGradient id="iAd8VBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92188 -.83495 0 24.395 14.851)" gradientUnits="userSpaceOnUse"><stop class="nqvhaxa_c"/><stop offset="1" class="zq-itunnh"/></radialGradient><radialGradient id="iyHOuOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.5273 1.08984 0 24.823 29.968)" gradientUnits="userSpaceOnUse"><stop class="vj07kubhl"/><stop offset="1" class="keqz-8g7v"/></radialGradient><radialGradient id="i7VBsyx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -17.8945 2.43359 0 24.823 28.336)" gradientUnits="userSpaceOnUse"><stop offset=".906" class="sy7qt-bzl"/><stop offset="1" class="i8gxpdlwn"/></radialGradient><radialGradient id="iH2NTle" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.3125 -1.10912 0 24.823 15.836)" gradientUnits="userSpaceOnUse"><stop class="ti8dkw8jh"/><stop offset="1" class="uw8wenb6w"/></radialGradient><radialGradient id="iNKFmde" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31815 0 0 -1.07813 26.163 9.882)" gradientUnits="userSpaceOnUse"><stop class="jk8wwdkvh"/><stop offset="1" class="kt1qsbbol"/></radialGradient><radialGradient id="imyDoTc" cx="0" cy="0" r="1" gradientTransform="rotate(108.771 12.726 11.781)scale(5.04985 5.80366)" gradientUnits="userSpaceOnUse"><stop class="l1mhifosa"/><stop offset="1" class="nwr0ulaka"/></radialGradient><radialGradient id="ieCLF6d" cx="0" cy="0" r="1" gradientTransform="matrix(2 8.14203 -5.28875 1.29912 23.35 2.1)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="tfpize5dt"/><stop offset="1" class="udxjy24sj"/></radialGradient><radialGradient id="i6UTi5W" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 1 -.64044 -.57039 23.148 2.398)" gradientUnits="userSpaceOnUse"><stop offset=".048" class="ozaj1r-nb"/><stop offset="1" class="pkl3f-q-p"/></radialGradient><radialGradient id="iCFtYsx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25757 0 0 -.32031 26.255 15.52)" gradientUnits="userSpaceOnUse"><stop class="y5jeombpr"/><stop offset="1" class="b2j1evbtw"/></radialGradient><radialGradient id="iHR30zc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06226 0 0 -.27056 26.255 14.718)" gradientUnits="userSpaceOnUse"><stop class="k3_t617jt"/><stop offset="1" class="uz9ryib2u"/></radialGradient><radialGradient id="ixhglsb" cx="0" cy="0" r="1" gradientTransform="matrix(-.97632 0 0 -.27344 26.255 13.992)" gradientUnits="userSpaceOnUse"><stop class="o_t5--bfj"/><stop offset="1" class="iqdmaebug"/></radialGradient><radialGradient id="iNMwGWb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17944 0 0 -.28906 26.255 13.218)" gradientUnits="userSpaceOnUse"><stop class="cyqpwvbyi"/><stop offset="1" class="c6xnsdb_f"/></radialGradient><radialGradient id="iatuWTb" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.28098 -1.58159 .34725 23.942 12.67)" gradientUnits="userSpaceOnUse"><stop class="gjnphvbix"/><stop offset="1" class="arqho5b7s"/></radialGradient><radialGradient id="iUgxfUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 0 0 -1 25.63 13.843)" gradientUnits="userSpaceOnUse"><stop class="hpf5aobnc"/><stop offset="1" class="n8pdz0bgw"/></radialGradient><radialGradient id="iWzWLLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -.9375 .74865 -.02496 24.27 14.492)" gradientUnits="userSpaceOnUse"><stop class="yuxw77bqf"/><stop offset="1" class="u2hnt4brx"/></radialGradient><radialGradient id="iPaWPYd" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -.26562 .64937 1.60434 4.241 16.757)" gradientUnits="userSpaceOnUse"><stop class="v-gkzt3yo"/><stop offset="1" class="lu2kygb1n"/></radialGradient><radialGradient id="iZBmsmd" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -3.1875 1.21246 2.63887 4.726 16.21)" gradientUnits="userSpaceOnUse"><stop class="glt2xqbag"/><stop offset="1" class="qxzcgzblc"/></radialGradient><radialGradient id="ioWLCLe" cx="0" cy="0" r="1" gradientTransform="rotate(138.102 3.516 9.17)scale(4.49229 1.70257)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="distoibkm"/><stop offset="1" class="ba0e5yj0i"/></radialGradient><radialGradient id="iGiOxee" cx="0" cy="0" r="1" gradientTransform="rotate(-179.561 6.573 5.161)scale(2.03912 1.41902)" gradientUnits="userSpaceOnUse"><stop class="wlil1mrmm"/><stop offset="1" class="natgddb0b"/></radialGradient><radialGradient id="iBSWCxe" cx="0" cy="0" r="1" gradientTransform="matrix(.78907 8.61887 -5.42589 .49675 18.155 11.748)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="dimvtpb4a"/><stop offset="1" class="r32eg3b6m"/></radialGradient><radialGradient id="inW3s3b" cx="0" cy="0" r="1" gradientTransform="matrix(.3615 4.948 -2.46163 .17985 11.008 14.73)" gradientUnits="userSpaceOnUse"><stop class="pou80-bzh"/><stop offset="1" class="a6np3140v"/></radialGradient><radialGradient id="i8viBkc" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -1.8125 4.2981 10.67113 13.52 14.539)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="rd-kp2hok"/><stop offset="1" class="i_n63cflx"/></radialGradient><radialGradient id="iRNtjEb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.34375 1.37499 -.66249 -1.61107 15.255 9.685)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="l4moz2bvy"/><stop offset="1" class="qevosta-x"/></radialGradient><radialGradient id="iuS78cd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 .23438 -.46507 -.83711 25.304 2.828)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="nvk-74bwn"/><stop offset="1" class="f1ri06bus"/></radialGradient><radialGradient id="iK6wiUb" cx="0" cy="0" r="1" gradientTransform="matrix(4.84376 2.56248 -.9379 1.77288 19.114 12.82)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="e3cpuodcm"/><stop offset="1" class="wu046_gyv"/></radialGradient><radialGradient id="idc1wjd" cx="0" cy="0" r="1" gradientTransform="matrix(1.00956 0 0 1.76674 11.152 6.98)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="i8sMhac" cx="0" cy="0" r="1" gradientTransform="matrix(.4756 -.3463 .39527 .54283 17.8 6.827)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iuKh38L" cx="0" cy="0" r="1" gradientTransform="matrix(.47247 -.869 .50863 .27654 17.562 7.452)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="i3k4bId" cx="0" cy="0" r="1" gradientTransform="matrix(.14917 .14765 -.19034 .1923 17.585 6.98)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="i8LaUec" cx="0" cy="0" r="1" gradientTransform="scale(5.86475 6.1385)rotate(90 .877 1.7)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="a-1obqbcp"/><stop offset=".936" class="niqz7n5ws"/></radialGradient><radialGradient id="iDybnYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.75196 .92548 0 16.194 6.248)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iqPME2k" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.80016 .99507 0 13.571 6.229)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iRFfb9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97706 2.54817 -4.33338 -3.36217 16.968 2.543)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iBFvk9d" cx="0" cy="0" r="1" gradientTransform="rotate(-92.056 8.624 -3.5)scale(1.07159 .52628)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iHF9aFd" cx="0" cy="0" r="1" gradientTransform="matrix(.49426 -1.1313 .92267 .4031 17.276 5.98)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="i8pVhjc" cx="0" cy="0" r="1" gradientTransform="matrix(.57114 .70868 -.62572 .50428 14.398 2.032)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iPavsvb" cx="0" cy="0" r="1" gradientTransform="rotate(76.961 6.344 10.604)scale(.46249 .76035)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="ikFS0Jd" cx="0" cy="0" r="1" gradientTransform="matrix(.41738 .51623 -1.15666 .93518 12.344 3.026)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i6EyeCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .51958 -.6148 0 16.098 6.78)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iYHVHUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13339 -.1719 .23665 -.18365 15.966 6.636)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5TlN9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .5196 -.61483 0 13.588 6.78)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i2onmee" cx="0" cy="0" r="1" gradientTransform="matrix(-.00445 -.28418 .3416 -.00535 13.422 6.714)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iPdZ9hd" width="16.97" height="13.626" x="4.983" y="16.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1301" result="effect2_innerShadow_4002_1301"/></filter><filter id="i6id4qU" width="8.803" height="12.453" x="12.427" y="15.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".5"/></filter><filter id="iueMkdd" width="11.112" height="3.615" x="8.173" y="25.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".2"/></filter><filter id="iqBHoub" width="3.297" height="3.17" x="5.589" y="23.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".2"/></filter><filter id="i0eAOPe" width="3.085" height="3.032" x="8.851" y="23.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".2"/></filter><filter id="i4Sx3yb" width="8.453" height="6.378" x="16.55" y="9.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.8"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.505882 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.454902 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1301" result="effect2_innerShadow_4002_1301"/></filter><filter id="iBic00b" width="2.963" height="1.158" x="23.363" y="9.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.541176 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/></filter><filter id="iq619Hd" width="8.438" height="7.533" x="20.669" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.517647 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/></filter><filter id="i22LJfe" width="1.765" height="3.013" x="24.69" y="13.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.501961 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/></filter><filter id="ifXPbLd" width="10.053" height="7.208" x="2.993" y="10.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.458824 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/></filter><filter id="iPTImQe" width="2.209" height="5.708" x="26.777" y="3.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".1"/></filter><filter id="ilbUkHb" width="1.759" height="1.3" x="26.569" y="2.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".1"/></filter><filter id="i9avDUd" width="1.189" height="1.345" x="24.572" y="2.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".1"/></filter><filter id="i1jfjJc" width="2.586" height="5.952" x="24.656" y="3.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".1"/></filter><filter id="iCNVHSb" width="2.948" height="6.859" x="20.962" y="2.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".1"/></filter><filter id="ivvJDHe" width="7.3" height="3.894" x="17.558" y="11.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".3"/></filter><filter id="iuwMGKb" width="2.121" height="1.921" x="11.152" y="6.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/></filter><filter id="iBDSxWd" width="2.145" height="2.145" x="11.04" y="5.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".25"/></filter><filter id="iYtonte" width="2.171" height="2.171" x="16.625" y="5.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/></filter><filter id="ivRdvmc" width="2.145" height="2.145" x="16.513" y="5.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".25"/></filter><filter id="iPC9WSS" width="5.968" height="7.02" x="11.877" y="3.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/></filter><filter id="ip7CBhZ" width="7.25" height="5.127" x="11.219" y="1.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/></filter><filter id="iOn9FIt" width="2.513" height="3.042" x="13.45" y="5.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".375"/></filter><filter id="iRUnjPb" width="1.28" height="1.742" x="14.204" y="6.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".05"/></filter><filter id="iAAPVse" width="1.82" height="1.247" x="15.524" y="4.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/></filter><filter id="izU48ae" width="1.82" height="1.247" x="12.563" y="4.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1301"/></filter><filter id="imtHvae" width=".538" height=".486" x="15.633" y="6.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".05"/></filter><filter id="i8Qdoii" width=".683" height=".695" x="16.073" y="6.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".1"/></filter><filter id="i2LDLZb" width=".737" height=".768" x="13.518" y="6.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".1"/></filter><filter id="ijVe7Je" width=".61" height=".49" x="13.126" y="6.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".05"/></filter><filter id="i4zmcNd" width="1.464" height=".648" x="15.599" y="5.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".075"/></filter><filter id="i6ra8mc" width="1.509" height=".681" x="12.597" y="5.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1301" stdDeviation=".075"/></filter><linearGradient id="i77yBdc" x1="9.112" x2="18.219" y1="27.046" y2="28.889" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="ibZ2sCe" x1="7.862" x2="5.547" y1="25.839" y2="25.467" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iMq826c" x1="11.357" x2="10.826" y1="24.177" y2="26.286" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iE3xHuc" x1="25.417" x2="25.113" y1="20.679" y2="20.679" gradientUnits="userSpaceOnUse"><stop class="y_8gxtivd"/><stop offset="1" class="rtj1uebvi"/></linearGradient><linearGradient id="iNj1Vtc" x1="25.472" x2="25.472" y1="13.218" y2="16.031" gradientUnits="userSpaceOnUse"><stop class="y_4kejkfw"/><stop offset="1" class="s0u10ejgs"/></linearGradient><linearGradient id="i0PhYgb" x1="24.195" x2="25.702" y1="13.951" y2="13.951" gradientUnits="userSpaceOnUse"><stop offset=".342" class="bm2z22sdd"/><stop offset="1" class="zzph65bql"/></linearGradient><linearGradient id="iyrl8qd" x1="4.021" x2="4.289" y1="16.859" y2="16.835" gradientUnits="userSpaceOnUse"><stop class="nytyklb8p"/><stop offset="1" class="ujmbb4brk"/></linearGradient><linearGradient id="iv0YjMe" x1="27.226" x2="28.976" y1="3.679" y2="9.414" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset="1" class="msr886b7s"/></linearGradient><linearGradient id="iekjRMb" x1="27.437" x2="27.067" y1="2.812" y2="3.028" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset="1" class="msr886b7s"/></linearGradient><linearGradient id="icAMA8b" x1="25.17" x2="27.718" y1="3.765" y2="13.135" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset=".765" class="msr886b7s"/></linearGradient><linearGradient id="iTqnyxe" x1="21.517" x2="24.201" y1="3.146" y2="13.697" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset=".765" class="msr886b7s"/></linearGradient><linearGradient id="itlD5gc" x1="12.112" x2="11.744" y1="7.14" y2="7.14" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="ifnByve" x1="18.21" x2="17.739" y1="6.352" y2="7.811" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iPJ0CZd" x1="17.166" x2="12.772" y1="7.204" y2="7.859" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iVKmSdb" x1="11.74" x2="13.07" y1="8.755" y2="8.581" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iJ0VoQd" x1="12.047" x2="13.717" y1="6.826" y2="3.861" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="inycxMd" x1="14.347" x2="14.886" y1="7.583" y2="7.583" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iFDoKnc" x1="15.384" x2="14.794" y1="7.769" y2="7.76" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="ixEDoIe" x1="14.956" x2="14.956" y1="8.196" y2="7.866" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iC378lc" x1="14.247" x2="14.498" y1="9.125" y2="8.729" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iOiTNHc" x1="16.545" x2="16.364" y1="6.619" y2="6.73" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwI1iwc" x1="14.015" x2="13.835" y1="6.618" y2="6.73" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iS7Viob" x1="16.554" x2="16.312" y1="5.387" y2="4.893" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iaX62qb" x1="13.502" x2="12.818" y1="5.314" y2="5.027" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-merpeople-medium-light" /></template>
<style>
.a-1obqbcp {
  stop-color: var(--svg-color--cd9486, #CD9486);
  stop-opacity: 0;
}

.a6np3140v {
  stop-color: var(--svg-color--cf9982, #CF9982);
  stop-opacity: 0;
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.acvm8_bqb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.797 5.63c.188-.166.599-.341 1.108-.26");
}

.acx3wxb5i {
  d: path("M13.586 6.313a.513.513 0 0 0-.494.649h.991a.517.517 0 0 0-.497-.649");
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.arqho5b7s {
  stop-color: var(--svg-color--c79373, #C79373);
  stop-opacity: 0;
}

.b2j1evbtw {
  stop-color: var(--svg-color--e7bb9b, #E7BB9B);
  stop-opacity: 0;
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.ba0e5yj0i {
  stop-color: var(--svg-color--d79d8a, #D79D8A);
  stop-opacity: 0;
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bh6f89byw {
  cx: 17.585px;
  cy: 6.98px;
  r: 0.572px;
}

.bm2z22sdd {
  stop-color: var(--svg-color--e3ae8b, #E3AE8B);
}

.c6xnsdb_f {
  stop-color: var(--svg-color--eabd9a, #EABD9A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cv_2u2b1j {
  d: path("M25.256 13.218a.34.34 0 0 0-.338.338v.019c0 .128.072.24.178.297c.017.01.017.04 0 .049a.34.34 0 0 0-.178.297v.019c0 .13.073.242.18.298c.007.004.005.015-.003.015a.405.405 0 0 0-.143.785c.019.007.022.04.005.052a.349.349 0 0 0 .186.644h.762a.35.35 0 0 0 .2-.636c-.035-.024-.041-.109-.01-.136a.404.404 0 0 0-.036-.634c-.026-.019-.022-.081.005-.097a.34.34 0 0 0 .166-.291v-.019a.34.34 0 0 0-.168-.292c-.026-.015-.029-.065-.005-.082a.34.34 0 0 0 .133-.27v-.018a.34.34 0 0 0-.338-.338z");
}

.cyqpwvbyi {
  stop-color: var(--svg-color--eabd9a, #EABD9A);
}

.df0eo_byv {
  cx: 12.112px;
  cy: 6.98px;
  r: 0.572px;
}

.dimvtpb4a {
  stop-color: var(--svg-color--f0b796, #F0B796);
}

.distoibkm {
  stop-color: var(--svg-color--ba796c, #BA796C);
}

.dmf7ibb4u {
  cx: 17.585px;
  cy: 6.98px;
  r: 0.572px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.doky60syc {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M27.077 3.43c0 .382.117.882.602 1.452c.669.788 1.008 1.22 1.008 1.844c0 .399-.118 1.305-1.008 1.93");
}

.dxbw9fmxo {
  d: path("M4.022 16.009a.517.517 0 0 1 1.033-.063l.052.87a.517.517 0 0 1-1.033.062z");
}

.e3cpuodcm {
  stop-color: var(--svg-color--eeb999, #EEB999);
}

.eufzeuc-t {
  stop-color: var(--svg-color--eeb493, #EEB493);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f1ri06bus {
  stop-color: var(--svg-color--f2be56, #F2BE56);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.ga1jnhb0w {
  d: path("M16.06 6.422c.038.049-.039.108-.126.173s-.151.111-.188.062c-.036-.049.004-.141.091-.206s.187-.078.224-.03");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjnphvbix {
  stop-color: var(--svg-color--c79373, #C79373);
}

.glt2xqbag {
  stop-color: var(--svg-color--daa48b, #DAA48B);
}

.gmg9qbkwd {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M16.984 5.415h-.001l-.001-.001l-.003-.003l-.007-.005a1 1 0 0 0-.089-.062a1.63 1.63 0 0 0-1.1-.212a.307.307 0 0 0 .096.606a1.02 1.02 0 0 1 .678.126l.032.022l.004.003a.307.307 0 0 0 .39-.474");
}

.gnxfttbkz {
  d: path("M14.055 6.766c0-.166-.135-.276-.171-.31l-.166.16l.102.208z");
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

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.h8f39p-0t {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M24.96 3.507v4.22c-.026.213.05.798.625 1.085c.575.288 1.211.078 1.422 0");
}

.hpf5aobnc {
  stop-color: var(--svg-color--ecbd9e, #ECBD9E);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hyal6rbtf {
  stop-color: var(--svg-color--ce9584, #CE9584);
  stop-opacity: 0;
}

.i_n63cflx {
  stop-color: var(--svg-color--ecb290, #ECB290);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i8gxpdlwn {
  stop-color: var(--svg-color--d6803e, #D6803E);
}

.i9c-eob6c {
  d: path("m24.646 2.201l-.753 1.02a.2.2 0 0 0 .163.318l.21-.002a.15.15 0 0 1 .152.15v3.856a1 1 0 0 1-1 1h-.032c-.902 0-1.538-.625-1.71-1.228c-.105-.37-.112-.645-.033-.906c.082-.27.275-.58.67-.983c.862-.882.866-1.887.87-3.02v-.04a.15.15 0 0 0-.243-.117l-1.3 1.025a.15.15 0 0 0 .092.268h.37c.085 0 .153.071.137.155a2.13 2.13 0 0 1-.584 1.086c-.446.456-.75.889-.892 1.358c-.146.48-.109.944.028 1.425a2.76 2.76 0 0 0 2.661 1.967h2.772a2.76 2.76 0 0 0 2.661-1.967c.137-.481.175-.945.029-1.425c-.143-.469-.447-.902-.892-1.358a2.14 2.14 0 0 1-.585-1.086c-.015-.084.053-.155.138-.155h.37a.15.15 0 0 0 .092-.268l-1.3-1.025a.15.15 0 0 0-.243.118v.04c.004 1.132.008 2.137.87 3.019c.395.404.587.713.67.983c.079.261.072.536-.034.906c-.171.603-.798 1.228-1.776 1.228a.95.95 0 0 1-.951-.952V3.678a.15.15 0 0 1 .148-.15l.213-.002a.2.2 0 0 0 .159-.32l-.745-1.005a.25.25 0 0 0-.402 0");
}

.ilhx4zbpd {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.953 2.586c0 .984-.058 1.818-.946 2.718c-1.11 1.125-.686 2.145-.562 2.422c.226.508.812 1.219 2.265 1.219");
}

.iqdmaebug {
  stop-color: var(--svg-color--e7bb99, #E7BB99);
  stop-opacity: 0;
}

.j27_zub1v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.773 26.94c-.007.65.436 1.949 2.266 1.949h3.177c1.01-.014 3.317-.517 4.469-2.415");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jk8wwdkvh {
  stop-color: var(--svg-color--ebaf51, #EBAF51);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jqtbx6bdj {
  d: path("M12.966 10.445c-.475.528-1.424 2.02-1.424 3.764v3.051c0 .359.291.65.65.65h5.314a.65.65 0 0 0 .65-.65v-3.051c0-1.744-.95-3.236-1.424-3.764z");
}

.jt0iaf2nr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m18.458 12.445l1.884 1.942a.5.5 0 0 0 .359.152h3.257");
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k3_t617jt {
  stop-color: var(--svg-color--e8bc9b, #E8BC9B);
}

.k8f-b6tly {
  cx: 12.113px;
  cy: 6.98px;
  r: 0.96px;
}

.keqz-8g7v {
  stop-color: var(--svg-color--e49c45, #E49C45);
}

.kihb0lb2k {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.467 6.157a.804.804 0 0 0-.78.609c-.025.1.052.196.155.196h1.283a.132.132 0 0 0 .13-.156a.806.806 0 0 0-.788-.65");
}

.kt1qsbbol {
  stop-color: var(--svg-color--ebaf51, #EBAF51);
  stop-opacity: 0;
}

.kw6ccvhnj {
  d: path("m17.616 3.253l.247.123c.432.215.679.706.586 1.227l-.34 1.75c-.03.18-.149.301-.328.306h-.01s.03-.522.061-.828c.025-.25-.018-.326-.247-.553a.72.72 0 0 1-.216-.49v-.492a.33.33 0 0 0-.247-.306c-.37-.092-1.141-.246-2.252-.246s-1.883.154-2.253.246a.3.3 0 0 0-.247.306v.491a.61.61 0 0 1-.216.491l-.092.092c-.124.092-.186.276-.186.43c.031.337.062.828.062.828h-.028a.364.364 0 0 1-.342-.306l-.34-1.75c-.061-.49.186-.981.617-1.196l.247-.123c.155-.092.309-.215.463-.337l.556-.583c.34-.307.833-.4 1.265-.184c.309.092.648.092.957 0a1.39 1.39 0 0 1 1.357.306l.463.46c.124.154.278.246.463.338");
}

.kwkhc9bqp {
  fill: var(--svg-color--000, #000);
  d: path("M13.88 6.826a.293.293 0 0 0-.294-.294a.293.293 0 0 0-.261.43h.52a.3.3 0 0 0 .035-.136");
}

.kwq24xrzi {
  fill: var(--svg-color--000, #000);
  d: path("M15.805 6.826c0-.163.13-.294.294-.294a.293.293 0 0 1 .261.43h-.52a.3.3 0 0 1-.035-.136");
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l0mey06vx {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.07 8.547c.223.117.49.184.774.184c.287 0 .55-.067.774-.184a.14.14 0 0 1 .164.027a.13.13 0 0 1 .014.165m-1.726-.192l1.685.165m-1.685-.165a.14.14 0 0 0-.164.028a.13.13 0 0 0-.014.165m.178-.193l-.137.165m1.863.027l-.041-.027m.041.027l-.041-.027m.041.027a1.14 1.14 0 0 1-.952.51c-.4 0-.75-.204-.952-.51m1.863-.027a1.09 1.09 0 0 1-.911.486c-.382 0-.718-.194-.91-.486m-.042.028l.041-.028m-.041.028l.041-.028");
}

.l1mhifosa {
  stop-color: var(--svg-color--f0b438, #F0B438);
}

.l4moz2bvy {
  stop-color: var(--svg-color--94543c, #94543C);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lu2kygb1n {
  stop-color: var(--svg-color--ab674a, #AB674A);
}

.luqq4ccam {
  stop-color: var(--svg-color--f6c059, #F6C059);
}

.m275xhwfx {
  d: path("m20.646 13.364l-2.182-2.114c-.68-.61-1.46-.703-1.914-.836l.946 3.59c.218.184.953.847 1.585 1.453c.579.488 1.254.535 1.61.535h4.312v-2.125c-.426-.06-2.951-.279-4.12-.393a.4.4 0 0 1-.237-.11");
}

.m8te_ab5w {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m17.616 3.253l.247.123c.432.215.679.706.586 1.227l-.34 1.75c-.03.18-.149.301-.328.306h-.01s.03-.522.061-.828c.025-.25-.018-.326-.247-.553a.72.72 0 0 1-.216-.49v-.492a.33.33 0 0 0-.247-.306c-.37-.092-1.141-.246-2.252-.246s-1.883.154-2.253.246a.3.3 0 0 0-.247.306v.491a.61.61 0 0 1-.216.491l-.092.092c-.124.092-.186.276-.186.43c.031.337.062.828.062.828h-.028a.364.364 0 0 1-.342-.306l-.34-1.75c-.061-.49.186-.981.617-1.196l.247-.123c.155-.092.309-.215.463-.337l.556-.583c.34-.307.833-.4 1.265-.184c.309.092.648.092.957 0a1.39 1.39 0 0 1 1.357.306l.463.46c.124.154.278.246.463.338");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mj415ib8l {
  stop-color: var(--svg-color--e0ac88, #E0AC88);
}

.msr886b7s {
  stop-color: var(--svg-color--f6c059, #F6C059);
  stop-opacity: 0;
}

.n2ljw7bum {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M10.7 19.168c0-1.425.76-2.102 1.16-2.243l5.66-.34c1.61.72 2.954 2.782 3.141 5.282c.188 2.5-.203 4.953-2.265 6.562c-1.65 1.288-3.959 1.552-4.938 1.532h-2.472c-2.625 0-3.246-1.891-3.356-2.297a11 11 0 0 0-.184-.599a.43.43 0 0 0-.221-.26c-.528-.243-1.52-.486-1.946-1.387a3.1 3.1 0 0 1-.28-1.63c.021-.214.231-.344.44-.297c.52.12.95.253 1.57.567a3.4 3.4 0 0 1 1.237 1.227c.065.11.238.111.304.002c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.766-.747 2.275-1.198 2.513c-.288.132-.62.278-.865.388c-.14.063-.209.224-.141.36c.474.957 1.468.87 2.858.87c1.851 0 2.96-1.325 2.844-2.723c-.063-1.813-1.563-2.516-2.57-3.149c-.524-.328-2.055-1.144-2.055-2.925");
}

.n8pdz0bgw {
  stop-color: var(--svg-color--ecbd9e, #ECBD9E);
  stop-opacity: 0;
}

.natgddb0b {
  stop-color: var(--svg-color--be8462, #BE8462);
  stop-opacity: 0;
}

.nid47tbzi {
  d: path("M24.808 13.027h-.5c-.53 0-.779.382-.887.863l.848.266l.042-.177a.1.1 0 0 1 .11-.076l.2.027c.078.01.136.078.136.156v.316a.473.473 0 0 0 .945 0v-.453c0-.258-.027-.461-.304-.692a1 1 0 0 0-.59-.23");
}

.niqz7n5ws {
  stop-color: var(--svg-color--be817f, #BE817F);
}

.npl8uhbaw {
  cx: 13.431px;
  cy: 6.532px;
  rx: 0.224px;
  ry: 0.113px;
}

.nqvhaxa_c {
  stop-color: var(--svg-color--b46b5d, #B46B5D);
}

.nvk-74bwn {
  stop-color: var(--svg-color--f2be56, #F2BE56);
}

.nwr0ulaka {
  stop-color: var(--svg-color--f0a23f, #F0A23F);
}

.nytyklb8p {
  stop-color: var(--svg-color--db9d84, #DB9D84);
}

.o_t5--bfj {
  stop-color: var(--svg-color--e7bb99, #E7BB99);
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.ozaj1r-nb {
  stop-color: var(--svg-color--f1c057, #F1C057);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkl3f-q-p {
  stop-color: var(--svg-color--f1c057, #F1C057);
  stop-opacity: 0;
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pou80-bzh {
  stop-color: var(--svg-color--bc816b, #BC816B);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.px8lptbkt {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m14.686 6.91l-.472.977c-.059.201.082.402.28.402h.425c.198 0 .339-.204.28-.402l-.286-.978c-.062-.216-.163-.216-.228 0");
}

.q0dmax7dd {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m12.673 5.415l.002-.001l.003-.003l.006-.005a1 1 0 0 1 .09-.062a1.63 1.63 0 0 1 1.1-.212a.307.307 0 0 1-.096.606a1.02 1.02 0 0 0-.678.126l-.032.022l-.005.003a.307.307 0 0 1-.39-.474");
}

.qevosta-x {
  stop-color: var(--svg-color--b17254, #B17254);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxzcgzblc {
  stop-color: var(--svg-color--d59e86, #D59E86);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r_n1v7r5p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.336 23.986c-.308.353-1.133 1.101-1.885 1.832");
}

.r32eg3b6m {
  stop-color: var(--svg-color--d59e87, #D59E87);
}

.rd-kp2hok {
  stop-color: var(--svg-color--ecb290, #ECB290);
  stop-opacity: 0;
}

.rq16spb6n {
  cx: 17.585px;
  cy: 6.98px;
  r: 0.96px;
}

.rtj1uebvi {
  stop-color: var(--svg-color--e69440, #E69440);
  stop-opacity: 0;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s0u10ejgs {
  stop-color: var(--svg-color--d09a83, #D09A83);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sy7qt-bzl {
  stop-color: var(--svg-color--d6803e, #D6803E);
  stop-opacity: 0;
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t06-rzbwx {
  d: path("M10.933 11.367c.775-.75 1.746-.925 2.113-.914v4.054h-1.422c-.112-.13-.218-.09-.258-.054c-.502.424-1.62 1.372-2.07 1.765c-.45.394-1.208.498-1.531.5H6.13a.4.4 0 0 0-.273.108l-.472.44a.537.537 0 0 1-.748-.769l.358-.363a.102.102 0 0 0-.022-.161l-.068-.038a.32.32 0 0 0-.391.058l-.65.68a.506.506 0 0 1-.754-.674l.788-.944a.8.8 0 0 1 .518-.28l3.203-.37a.3.3 0 0 0 .172-.08c.758-.72 2.284-2.198 3.142-2.958");
}

.t1qofdbri {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m26.827 2.593l.993.72h-.72");
}

.tfpize5dt {
  stop-color: var(--svg-color--ebad2f, #EBAD2F);
}

.ti8dkw8jh {
  stop-color: var(--svg-color--d77735, #D77735);
}

.tkq_smxzd {
  stop-color: var(--svg-color--c58272, #C58272);
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.txp88d1_z {
  width: 2.963px;
  height: 0.908px;
  x: 23.363px;
  y: 9.533px;
  fill: var(--svg-color--eca63f, #ECA63F);
  rx: 0.454px;
}

.u2hnt4brx {
  stop-color: var(--svg-color--b9746f, #B9746F);
  stop-opacity: 0;
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.uc68slbrm {
  width: 2.963px;
  height: 0.908px;
  x: 23.363px;
  y: 9.533px;
  rx: 0.454px;
}

.udxjy24sj {
  stop-color: var(--svg-color--ebad2f, #EBAD2F);
  stop-opacity: 0;
}

.ujmbb4brk {
  stop-color: var(--svg-color--c2826e, #C2826E);
  stop-opacity: 0;
}

.unhp_hi6j {
  d: path("M16.556 6.759a.5.5 0 0 0-.133-.266l-.15.164l.068.131z");
}

.uotkb3-yl {
  d: path("m14.624 6.816l-.306.977a.31.31 0 0 0 .3.403h.452a.31.31 0 0 0 .3-.403l-.306-.977c-.066-.217-.371-.217-.44 0");
}

.uw8wenb6w {
  stop-color: var(--svg-color--d77735, #D77735);
  stop-opacity: 0;
}

.uxmx_b5qt {
  d: path("m25.562 3.234l-.617-.945l-.173.945z");
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.uz9ryib2u {
  stop-color: var(--svg-color--e8bc9b, #E8BC9B);
  stop-opacity: 0;
}

.v-gkzt3yo {
  stop-color: var(--svg-color--c48572, #C48572);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vacnm89zp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.06 6.422c.038.049-.039.108-.126.173s-.151.111-.188.062c-.036-.049.004-.141.091-.206s.187-.078.224-.03");
}

.vgjfbsb7l {
  d: path("M24.359 10.441h.93v19.377a.15.15 0 0 1-.15.15h-.63a.15.15 0 0 1-.15-.15z");
}

.vj07kubhl {
  stop-color: var(--svg-color--f8a33e, #F8A33E);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vw0r--b4a {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.218 6.157c.375 0 .693.259.779.609a.158.158 0 0 1-.154.196H15.56a.132.132 0 0 1-.131-.157a.804.804 0 0 1 .789-.648");
}

.vwqo82iho {
  d: path("m11.91 6.627l.028.001s-.03-.49-.062-.828c0-.154.062-.338.186-.43l.092-.092a.61.61 0 0 0 .216-.49v-.492a.3.3 0 0 1 .247-.307c.37-.092 1.142-.245 2.253-.245c1.11 0 1.882.153 2.252.245a.33.33 0 0 1 .247.307v.491c0 .184.093.368.216.491c.29.203.271.314.247.552c-.03.307-.062.829-.062.829h.01l-.152 2.277c-.092 1.018-.893 1.728-1.847 1.728h-1.847c-.985 0-1.754-.71-1.847-1.728z");
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w68lhtwwn {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m14.624 6.816l-.306.977a.31.31 0 0 0 .3.403h.452a.31.31 0 0 0 .3-.403l-.306-.977c-.066-.217-.371-.217-.44 0");
}

.wlil1mrmm {
  stop-color: var(--svg-color--be8462, #BE8462);
}

.wqoser8ru {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.189 24.505c.41.162 1.402.783 2.097 1.97");
}

.wrjncmbvl {
  d: path("M18.661 26.742c0-5.344-3.922-7.969-5.234-9l3.25-1.453c1.125.52 3.035 2.357 3.453 5.11c.485 3.187-.927 4.926-1.469 5.343");
}

.wu046_gyv {
  stop-color: var(--svg-color--eeb999, #EEB999);
  stop-opacity: 0;
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrch4ccua {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.8 5.332c.247-.044.73-.031 1.063.229");
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y_4kejkfw {
  stop-color: var(--svg-color--e3b48e, #E3B48E);
}

.y_66wxvct {
  d: path("M16.099 6.313a.513.513 0 0 1 .494.649h-.991a.515.515 0 0 1 .497-.649");
}

.y_8gxtivd {
  stop-color: var(--svg-color--cc802a, #CC802A);
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y5jeombpr {
  stop-color: var(--svg-color--e7bb9b, #E7BB9B);
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yjs_1lmgw {
  d: path("M10.7 19.168c0-1.425.76-2.102 1.16-2.243l5.66-.34c1.61.72 2.954 2.782 3.141 5.282c.188 2.5-.203 4.953-2.265 6.562c-1.65 1.288-3.959 1.552-4.938 1.532h-2.472c-2.625 0-3.246-1.891-3.356-2.297a11 11 0 0 0-.184-.599a.43.43 0 0 0-.221-.26c-.528-.243-1.52-.486-1.946-1.387a3.1 3.1 0 0 1-.28-1.63c.021-.214.231-.344.44-.297c.52.12.95.253 1.57.567a3.4 3.4 0 0 1 1.237 1.227c.065.11.238.111.304.002c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.766-.747 2.275-1.198 2.513c-.288.132-.62.278-.865.388c-.14.063-.209.224-.141.36c.474.957 1.468.87 2.858.87c1.851 0 2.96-1.325 2.844-2.723c-.063-1.813-1.563-2.516-2.57-3.149c-.524-.328-2.055-1.144-2.055-2.925");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.yuxw77bqf {
  stop-color: var(--svg-color--b9746f, #B9746F);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zq-itunnh {
  stop-color: var(--svg-color--c28177, #C28177);
  stop-opacity: 0;
}

.zx29jrbqo {
  cx: 13.431px;
  cy: 6.532px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.224px;
  ry: 0.113px;
}

.zzph65bql {
  stop-color: var(--svg-color--e4b28c, #E4B28C);
}

</style>
