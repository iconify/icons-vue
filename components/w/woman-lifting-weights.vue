<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#icU7eqe)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#i8YqMjD)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#i1xUJud)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#is3gzJe)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#i2XYmZd)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#igK5sqX)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iieTJ2c)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#ivBLUee)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><g filter="url(#inzWose)"><path fill="url(#iVAnGZb)" class="q1wg51bmi"/><path fill="url(#i0AhJLc)" class="q1wg51bmi"/><path fill="url(#i8igjWE)" class="q1wg51bmi"/><path fill="url(#il5AC0d)" class="q1wg51bmi"/></g><g filter="url(#i7DoHKO)"><rect fill="url(#iE3hHec)" class="uywq_y1iv"/><rect fill="url(#i1HNLPr)" class="uywq_y1iv"/></g><g filter="url(#i9SavDc)"><path stroke="url(#ibRzype)" class="ijj045bhz"/></g><path fill="url(#iPLW49h)" class="g4offrb0h"/><path fill="url(#i6H6f0b)" class="nm-q8ebbk"/><path fill="url(#iercRpd)" class="z0ggixb3q"/><path fill="url(#iZ5j9Qc)" class="tzfcre5-h"/><circle fill="url(#iMHIuAb)" class="gknucfb8h"/><path fill="url(#ilRInSd)" class="y0nqeezxq"/><path fill="url(#iSDE3Fb)" class="l2at7otgu"/><path fill="url(#iExIOzc)" class="ufmuzl7ni"/><path fill="url(#izjM9gd)" class="rh3jx3c9i"/><circle fill="url(#i9Hs44c)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><g filter="url(#iQOrmNc)"><path fill="url(#iRuuXqe)" class="em3ofwhyw"/><path fill="url(#ix5upbb)" class="em3ofwhyw"/><path fill="url(#iTnerGc)" class="em3ofwhyw"/></g><g filter="url(#ieHD0Ke)"><path fill="url(#ii9TU6b)" class="qno0gyhtd"/><path fill="url(#iAW9NPa)" class="qno0gyhtd"/><path fill="url(#irsbW7b)" class="qno0gyhtd"/></g><g filter="url(#iINf3tc)"><path fill="url(#iMd3cGY)" class="tphhgybtp"/><path fill="url(#iKoLy8d)" class="tphhgybtp"/></g><g filter="url(#iT3WIxb)"><path fill="url(#ipt2RNb)" class="x9t-2zb_r"/><path fill="url(#ijEmnZt)" class="x9t-2zb_r"/><path fill="url(#iqv6bwe)" class="x9t-2zb_r"/></g><g filter="url(#ifnFiUc)"><path fill="url(#i1fW1XY)" class="g5fg-5cgy"/><path fill="url(#iL5td6D)" class="g5fg-5cgy"/></g><g filter="url(#i0lDWAe)"><path class="naef-0b8m"/></g><g filter="url(#iBe1seb)"><path fill="url(#imrVfMc)" class="u6_y93pge"/><path fill="url(#iID6PAd)" class="u6_y93pge"/></g><g filter="url(#iYiQe5O)"><path fill="url(#iQ3Ldac)" class="qd4tofb7u"/></g><g filter="url(#iHnt1Be)"><path class="f0e_ytb-v"/></g><g filter="url(#iOQs5Zd)"><path fill="url(#ixKrPfb)" class="kv3enpo0a"/><path fill="url(#iIOJZDd)" class="kv3enpo0a"/></g><g filter="url(#iTLLvpe)"><path fill="url(#imGINwe)" class="fzjqedceo"/></g><g filter="url(#iaLyy4d)"><path fill="url(#iGHHxGy)" clip-rule="evenodd" class="dtweq89la"/><path fill="url(#iCaibHe)" clip-rule="evenodd" class="dtweq89la"/><path fill="url(#iMPjfRc)" clip-rule="evenodd" class="dtweq89la"/></g><g filter="url(#ij4XOIc)"><path class="s_9nzobmx"/></g><g filter="url(#i8hWYpe)"><path fill="url(#ikmErcb)" class="omgf1mb7e"/></g><g filter="url(#iuqnWOe)"><path class="gg4fvih9m"/><path fill="url(#iM5a8gx)" class="ygue0q3bo"/></g><g filter="url(#iOXgEue)"><path class="nxg3flbgi"/></g><g filter="url(#iRXRxme)"><path fill="url(#ih5jpFn)" class="ndz_pm_9t"/></g><g filter="url(#i0wxqxb)"><path class="swi22_bsl"/></g><g filter="url(#iFKl5pd)"><path fill="url(#iUFbnhb)" class="p4swes2nq"/><path fill="url(#iYHtHUK)" class="p4swes2nq"/><path fill="url(#i0HedIb)" class="p4swes2nq"/><path fill="url(#iSXHAwd)" class="p4swes2nq"/></g><path class="i0vkgib7y"/><g filter="url(#ik6yFEc)"><path class="fy2ap8zoa"/></g><g filter="url(#iTIPGoe)"><path class="jz1jncb9k"/></g><path class="uef17en4k"/><path fill="url(#iDJgTCe)" class="sf8l-5o7i"/><path class="tm2gy2bqa"/><g filter="url(#iRIbxCe)"><path class="dqzfzb18m"/><path fill="url(#iXgAsCe)" class="ymng13duo"/></g><g filter="url(#iKq2suc)"><path fill="url(#iRccHbe)" class="w8ylb5bcr"/></g><path class="pmnoj4bii"/><path fill="url(#iFzLlwb)" class="cr-sn7bpg"/><path class="cp731-y0v"/><g filter="url(#iqzsH1c)"><path fill="url(#iYTzLLb)" class="i26w_nbze"/></g><g filter="url(#ijsHiQd)"><ellipse transform="rotate(-27.914 14.91 13.045)" class="jbemutu1d"/><ellipse fill="url(#icBWplc)" transform="rotate(-27.914 14.91 13.045)" class="p-zsafbmq"/></g><g filter="url(#iEAubUN)"><path fill="url(#iwFfh7d)" class="z0fjtpbfo"/></g><g filter="url(#iJYlG2d)"><path fill="url(#ixh1RUb)" class="n0-vmbj5m"/><path fill="url(#i2TzcQX)" class="n0-vmbj5m"/><path fill="url(#ilMQY4d)" class="n0-vmbj5m"/></g><path class="h-9r6pjjz"/><g filter="url(#iPcqJ0t)"><path class="xeb59bcce"/></g><path class="ccpiw17it"/><g filter="url(#iWEFGmc)"><path class="ftekvobja"/></g><defs><radialGradient id="icU7eqe" cx="0" cy="0" r="1" gradientTransform="rotate(87.787 -.815 10.418)scale(4.85666 1.64346)" gradientUnits="userSpaceOnUse"><stop class="g77rtfbof"/><stop offset="1" class="x1baucbnz"/></radialGradient><radialGradient id="i1xUJud" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 10.04 7.769)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="tifd2nbhd"/><stop offset="1" class="o4u-l0lno"/></radialGradient><radialGradient id="is3gzJe" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.362 6.832)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="yyejvbcrw"/><stop offset="1" class="i1j-sacds"/></radialGradient><radialGradient id="i2XYmZd" cx="0" cy="0" r="1" gradientTransform="rotate(87.787 -1.122 2.973)scale(4.85666 1.64346)" gradientUnits="userSpaceOnUse"><stop class="g77rtfbof"/><stop offset="1" class="x1baucbnz"/></radialGradient><radialGradient id="iieTJ2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 2.305 .918)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="tifd2nbhd"/><stop offset="1" class="o4u-l0lno"/></radialGradient><radialGradient id="ivBLUee" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="yyejvbcrw"/><stop offset="1" class="i1j-sacds"/></radialGradient><radialGradient id="iVAnGZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.375 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="il5AC0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 17.938 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="iE3hHec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 17.781 5.695)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="i1HNLPr" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 8.96 6.273)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="iPLW49h" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 3.991 3.074)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="i3etvmbtq"/><stop offset="1" class="v3dxsi25s"/></radialGradient><radialGradient id="i6H6f0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 8.863 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="bhv6r6bju"/><stop offset="1" class="zcsf4yb5o"/></radialGradient><radialGradient id="iercRpd" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.03 3.12)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="bhv6r6bju"/><stop offset="1" class="zcsf4yb5o"/></radialGradient><radialGradient id="iZ5j9Qc" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.687 3.116)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="bhv6r6bju"/><stop offset="1" class="zcsf4yb5o"/></radialGradient><radialGradient id="iMHIuAb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39453 .51953 -.51953 -.39453 10.781 6.84)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="m0lqw5bea"/><stop offset=".91" class="rdwyvqbpo"/></radialGradient><radialGradient id="ilRInSd" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 0 0 1.26563 23.836 5.852)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="vjv772cbv"/><stop offset="1" class="f3x0tmb2q"/></radialGradient><radialGradient id="iSDE3Fb" cx="0" cy="0" r="1" gradientTransform="rotate(176.697 11.828 3.28)scale(.90756 1.0035)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xot5t6pkw"/><stop offset="1" class="wjkbrmbdg"/></radialGradient><radialGradient id="iExIOzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8606 .05074 -.05742 -.97387 22.392 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="u521robxh"/><stop offset="1" class="wjkbrmbdg"/></radialGradient><radialGradient id="izjM9gd" cx="0" cy="0" r="1" gradientTransform="matrix(-.90871 .05556 -.06514 -1.06541 23.109 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="u521robxh"/><stop offset="1" class="wjkbrmbdg"/></radialGradient><radialGradient id="i9Hs44c" cx="0" cy="0" r="1" gradientTransform="rotate(37.439 -.33 .432)scale(.62972)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="tydx0uunk"/><stop offset=".91" class="vea9pibbt"/></radialGradient><radialGradient id="iRuuXqe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.313 18.758)" gradientUnits="userSpaceOnUse"><stop class="bhmppoxew"/><stop offset="1" class="kd-ejbc7g"/></radialGradient><radialGradient id="ix5upbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.36701 -3.49725 0 15.501 14.297)" gradientUnits="userSpaceOnUse"><stop offset=".432" class="odylpubas"/><stop offset="1" class="t8d6ru-nk"/></radialGradient><radialGradient id="iTnerGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 19.826 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="yyr7j8rnv"/><stop offset="1" class="ymbigdcyd"/></radialGradient><radialGradient id="ii9TU6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.5 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iMd3cGY" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.294 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ipt2RNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.074 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ijEmnZt" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 2.773 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i1fW1XY" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.438 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iL5td6D" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.188 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iID6PAd" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.145 12.111)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iQ3Ldac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.406 27.992)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iIOJZDd" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.729 15.316)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="imGINwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.719 28.54)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="iGHHxGy" cx="0" cy="0" r="1" gradientTransform="matrix(-2.78618 4.84003 -6.29906 -3.62607 18.343 9.962)" gradientUnits="userSpaceOnUse"><stop class="z0a9xf8ly"/><stop offset="1" class="uk_7vbbxl"/></radialGradient><radialGradient id="iCaibHe" cx="0" cy="0" r="1" gradientTransform="rotate(141.103 4.922 9.847)scale(1.80021 2.52706)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="dz55jtr2d"/><stop offset="1" class="iah51nb6s"/></radialGradient><radialGradient id="iMPjfRc" cx="0" cy="0" r="1" gradientTransform="rotate(68.523 .472 15.506)scale(1.04365 2.1962)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="ichqh9mcv"/><stop offset="1" class="w7iv1ibqs"/></radialGradient><radialGradient id="ikmErcb" cx="0" cy="0" r="1" gradientTransform="rotate(103.552 4.456 13.612)scale(1.29095)" gradientUnits="userSpaceOnUse"><stop class="wz5h02v_q"/><stop offset="1" class="lx3jigcww"/></radialGradient><radialGradient id="iM5a8gx" cx="0" cy="0" r="1" gradientTransform="rotate(-20.297 45.652 -44.096)scale(.59622)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="ih5jpFn" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65882 0 0 -2.57517 17.212 13.624)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="u9zfonkah"/><stop offset="1" class="nzzb8acnf"/></radialGradient><radialGradient id="iYHtHUK" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 13.445 .765)scale(1.16407 .6661)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iDJgTCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37034 -.58907 0 17.03 13.088)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iXgAsCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.10567 -.13617 .18747 -.14547 16.924 13.129)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFzLlwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37034 -.58907 0 15.034 13.088)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="icBWplc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00352 -.2251 .27059 -.00424 14.903 13.188)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwFfh7d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12946 .70166 -.27989 -.45053 14.767 10.16)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="ixh1RUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07935 2.24976 -3.19428 -1.5325 16.943 9.27)" gradientUnits="userSpaceOnUse"><stop offset=".628" class="xzk0urqfv"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="i2TzcQX" cx="0" cy="0" r="1" gradientTransform="matrix(-.46573 1.63397 -3.42429 -.97602 17.297 9.889)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="j_9p5tabl"/><stop offset="1" class="oh_t2j9xj"/></radialGradient><radialGradient id="ilMQY4d" cx="0" cy="0" r="1" gradientTransform="rotate(-117.848 12.13 1.325)scale(3.61268 3.22952)" gradientUnits="userSpaceOnUse"><stop offset=".852" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="inzWose" width="9.5" height="4.284" x="11.172" y="21.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="i7DoHKO" width="27.875" height="1.225" x="2.063" y="5.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="i9SavDc" width="27.781" height=".75" x="2.023" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".125"/></filter><filter id="iQOrmNc" width="10.708" height="10.353" x="10.803" y="11.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.301961 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="ieHD0Ke" width="1.93" height="8.989" x="5.039" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="iINf3tc" width="1.93" height="8.989" x="24.992" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="iT3WIxb" width="1.93" height="5.973" x="3.109" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="ifnFiUc" width="1.93" height="5.973" x="26.922" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="i0lDWAe" width="3.719" height="6.065" x="8.891" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.654902 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.631373 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23306" result="effect2_innerShadow_3987_23306"/></filter><filter id="iBe1seb" width="4.477" height="4.023" x="8.516" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="iYiQe5O" width="4.833" height="2.114" x="7.039" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="iHnt1Be" width="3.719" height="5.564" x="19.922" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.654902 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.576471 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23306" result="effect2_innerShadow_3987_23306"/></filter><filter id="iOQs5Zd" width="4.477" height="4.023" x="19.539" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="iTLLvpe" width="4.833" height="2.114" x="20.159" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="iaLyy4d" width="6.864" height="7.064" x="12.601" y="8.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.376471 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="ij4XOIc" width="1.571" height="1.471" x="13.155" y="12.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.568627 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="i8hWYpe" width="1.471" height="1.571" x="17.503" y="12.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.603922 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="iuqnWOe" width="1.282" height="1.282" x="17.598" y="12.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".075"/></filter><filter id="iOXgEue" width="1.282" height="1.282" x="13.259" y="12.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".075"/></filter><filter id="iRXRxme" width="4.807" height="4.999" x="13.704" y="10.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.45098 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="i0wxqxb" width="1.358" height="1.726" x="15.279" y="12.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".125"/></filter><filter id="iFKl5pd" width="1.058" height="1.426" x="15.503" y="12.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".05"/></filter><filter id="ik6yFEc" width="1.48" height=".587" x="16.354" y="12.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="iTIPGoe" width="1.48" height=".587" x="14.23" y="12.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23306"/></filter><filter id="iRIbxCe" width=".467" height=".426" x="16.64" y="12.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".05"/></filter><filter id="iKq2suc" width=".623" height=".633" x="16.969" y="12.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".1"/></filter><filter id="iqzsH1c" width=".667" height=".692" x="14.939" y="12.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".1"/></filter><filter id="ijsHiQd" width=".525" height=".43" x="14.648" y="12.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".05"/></filter><filter id="iEAubUN" width="2.179" height="2.284" x="13.013" y="9.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".125"/></filter><filter id="iJYlG2d" width="4.546" height="3.437" x="14.293" y="8.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".125"/></filter><filter id="iPcqJ0t" width="1.024" height=".375" x="16.78" y="12.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".025"/></filter><filter id="iWEFGmc" width="1.024" height=".375" x="14.26" y="12.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23306" stdDeviation=".025"/></filter><linearGradient id="i8YqMjD" x1="7.163" x2="8.284" y1="7.95" y2="8.096" gradientUnits="userSpaceOnUse"><stop offset=".136" class="rysyofyzl"/><stop offset="1" class="d85j9ed1i"/></linearGradient><linearGradient id="igK5sqX" x1="-.572" x2=".549" y1="1.099" y2="1.245" gradientUnits="userSpaceOnUse"><stop offset=".136" class="rysyofyzl"/><stop offset="1" class="d85j9ed1i"/></linearGradient><linearGradient id="i0AhJLc" x1="20.313" x2="17.781" y1="25.258" y2="24.82" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="i8igjWE" x1="11.625" x2="14.438" y1="25.352" y2="24.258" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="ibRzype" x1="2.398" x2="29.867" y1="7.406" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="iAW9NPa" x1="5.039" x2="6.531" y1="7.477" y2="7.477" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="irsbW7b" x1="5.039" x2="5.313" y1="7.348" y2="7.348" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iKoLy8d" x1="24.992" x2="26.188" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iqv6bwe" x1="2.958" x2="3.452" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="imrVfMc" x1="12.492" x2="8.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="ixKrPfb" x1="19.539" x2="23.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iUFbnhb" x1="16.032" x2="16.032" y1="14.261" y2="13.035" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="i0HedIb" x1="15.554" x2="15.944" y1="13.913" y2="13.96" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iSXHAwd" x1="16.032" x2="16.032" y1="14.303" y2="14.024" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iRccHbe" x1="17.384" x2="17.241" y1="13.113" y2="13.2" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYTzLLb" x1="15.374" x2="15.231" y1="13.113" y2="13.201" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-lifting-weights" /></template>
<style>
.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.bhmppoxew {
  stop-color: var(--svg-color--9472d9, #9472D9);
}

.bhv6r6bju {
  stop-color: var(--svg-color--ffd83f, #FFD83F);
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.ccpiw17it {
  stroke: var(--svg-color--bf4540, #BF4540);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.184 12.293a1.3 1.3 0 0 0-.824-.167");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cp731-y0v {
  fill: var(--svg-color--000, #000);
  d: path("M15.267 13.278a.23.23 0 0 0-.233-.233a.232.232 0 0 0-.208.34h.413a.23.23 0 0 0 .028-.107");
}

.cr-sn7bpg {
  d: path("M15.034 12.87a.407.407 0 0 0-.393.516h.787a.41.41 0 0 0-.394-.515");
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d85j9ed1i {
  stop-color: var(--svg-color--af7222, #AF7222);
  stop-opacity: 0;
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.dqzfzb18m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17 12.957c.029.04-.032.086-.1.138c-.07.051-.12.087-.15.049c-.029-.039.004-.112.072-.164c.07-.051.149-.061.178-.023");
}

.dtweq89la {
  fill-rule: evenodd;
  d: path("M19.316 13.315a1.5 1.5 0 0 0 .025-1.249h.003a1.5 1.5 0 0 0-.129-.234v-.001a1.5 1.5 0 0 1-.241-.81v-.004c0-.833-.675-1.508-1.508-1.508a.25.25 0 0 1-.208-.107a1.51 1.51 0 0 0-2.451 0a.26.26 0 0 1-.208.107h-.04a1.51 1.51 0 0 0-1.468 1.508v.004c0 .287-.083.57-.24.81l-.002.001a1.51 1.51 0 0 0-.1 1.483a.24.24 0 0 1 0 .208a1.468 1.468 0 0 0 1.323 2.114h3.921a1.47 1.47 0 0 0 1.323-2.114a.24.24 0 0 1 0-.208m-5.603-.886l.542.741c.057 1.281.556 0 1.777 0s1.754 1.426 1.81.145l.52-.937c-.025-.57-.438-.61-.52-.61H16.37c-.58 0-1.13-.284-1.457-.764a.12.12 0 0 0-.211.023l-.038.089c-.256.716-.968.867-.951 1.313");
}

.dz55jtr2d {
  stop-color: var(--svg-color--d97228, #D97228);
}

.e4y-1lbum {
  r: 0.398px;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.em3ofwhyw {
  d: path("m10.948 13.026l2.396-1.12l2.578 3.399l2.469-3.563l2.729 1.318a.25.25 0 0 1 .113.34l-1.194 2.303a1 1 0 0 0-.112.482l.12 5.76h-7.985v-5.788a1 1 0 0 0-.098-.433l-1.136-2.363a.25.25 0 0 1 .12-.335");
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.f0e_ytb-v {
  fill: var(--svg-color--ffdf41, #FFDF41);
  d: path("m22.668 28.448l.473-5.464h-3.22l.479 5.464z");
}

.f3x0tmb2q {
  stop-color: var(--svg-color--ad8518, #AD8518);
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.ft5dv1b6b {
  fill: none;
}

.ftekvobja {
  stroke: var(--svg-color--c25e51, #C25E51);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.184 12.293a1.3 1.3 0 0 0-.824-.167");
}

.fy2ap8zoa {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.554 13.102c.122-.214.306-.382.703-.382c.174 0 .341.048.49.168c.123.1.107.226.011.274l-.254.145c-.298-.096-.627-.11-.95-.205");
}

.fzjqedceo {
  d: path("M24.992 29.53v.376H20.36v-1.914h2.352c.383.377 1.215.73 1.836.941c.398.169.445.442.445.597");
}

.g4offrb0h {
  d: path("M7.5 5.71a.399.399 0 1 1 .797-.034v.46a.38.38 0 0 1-.758.032z");
}

.g5fg-5cgy {
  d: path("M28.852 4.402a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.g77rtfbof {
  stop-color: var(--svg-color--ffdf3f, #FFDF3F);
}

.gg4fvih9m {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M18.239 13.48a.49.49 0 1 0 0-.981a.49.49 0 0 0 0 .982");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gknucfb8h {
  cx: 10.586px;
  cy: 7px;
  r: 0.398px;
}

.h-9r6pjjz {
  stroke: var(--svg-color--bf4540, #BF4540);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.88 12.293c.117-.066.386-.211.824-.167");
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.i0vkgib7y {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.022 14.704c-.238 0-.462-.057-.65-.157c-.064-.034-.133.04-.093.1a.883.883 0 0 0 1.485 0c.04-.062-.028-.134-.093-.1c-.188.1-.409.157-.65.157");
}

.i1j-sacds {
  stop-color: var(--svg-color--efad2e, #EFAD2E);
  stop-opacity: 0;
}

.i26w_nbze {
  d: path("M15.406 13.23c0-.131-.107-.219-.136-.245l-.131.127l.08.164z");
}

.i3etvmbtq {
  stop-color: var(--svg-color--ffc935, #FFC935);
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.iah51nb6s {
  stop-color: var(--svg-color--d97228, #D97228);
  stop-opacity: 0;
}

.ichqh9mcv {
  stop-color: var(--svg-color--e0aa2d, #E0AA2D);
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.ijj045bhz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.398 6.406H29.43");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j_9p5tabl {
  stop-color: var(--svg-color--ffe631, #FFE631);
}

.jbemutu1d {
  cx: 14.91px;
  cy: 13.045px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.178px;
  ry: 0.09px;
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.jz1jncb9k {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.51 13.102c-.12-.214-.305-.382-.702-.382a.76.76 0 0 0-.49.168c-.123.1-.107.226-.012.274l.255.145c.297-.096.627-.11.95-.205");
}

.kd-ejbc7g {
  stop-color: var(--svg-color--7f54b1, #7F54B1);
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kv3enpo0a {
  d: path("M23.516 21.066a1.988 1.988 0 0 0-3.977 0v1.686c0 .193.157.35.35.35h3.277a.35.35 0 0 0 .35-.35z");
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l2at7otgu {
  d: path("M23.823 5.627a.422.422 0 1 0-.843-.033v.584a.4.4 0 0 0 .798.031z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.lx3jigcww {
  stop-color: var(--svg-color--f4b622, #F4B622);
}

.m0lqw5bea {
  stop-color: var(--svg-color--ffd741, #FFD741);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.n0-vmbj5m {
  d: path("M15.684 9.23c-.78 0-1.083.677-1.141.884c.762 1.788 1.763 1.536 3.229 1.536c.781 0 .751.346.817.518c-.215-2.004-1.375-2.938-2.905-2.938");
}

.naef-0b8m {
  fill: var(--svg-color--ffdf41, #FFDF41);
  d: path("m9.404 28.878l-.513-5.894h3.218l-.533 5.966z");
}

.ndz_pm_9t {
  d: path("M13.707 12.62h.006l-.005-.122l-.004-.14c.009-.434.262-.601.37-.657l.023-.01l.024-.01a1.05 1.05 0 0 0 .543-.563l.038-.13a.12.12 0 0 1 .21-.022c.329.48.877.805 1.458.805h1.472c.082 0 .495.04.519.608l-.053 1.243c-.057 1.28-1.057 2.14-2.278 2.14c-1.22 0-2.221-.86-2.277-2.14z");
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nm-q8ebbk {
  d: path("M8.16 5.627a.422.422 0 1 1 .844-.033v.584a.4.4 0 0 1-.798.031z");
}

.nxg3flbgi {
  fill: var(--svg-color--e69418, #E69418);
  d: path("M13.9 13.48a.49.49 0 1 0 0-.981a.49.49 0 0 0 0 .982");
}

.nzzb8acnf {
  stop-color: var(--svg-color--ffb320, #FFB320);
}

.o4u-l0lno {
  stop-color: var(--svg-color--eca42a, #ECA42A);
  stop-opacity: 0;
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odylpubas {
  stop-color: var(--svg-color--613e9f, #613E9F);
}

.oh_t2j9xj {
  stop-color: var(--svg-color--ffe631, #FFE631);
  stop-opacity: 0;
}

.omgf1mb7e {
  d: path("M18.238 13.725a.735.735 0 1 0 0-1.47a.735.735 0 0 0 0 1.47");
}

.p-zsafbmq {
  cx: 14.91px;
  cy: 13.045px;
  rx: 0.178px;
  ry: 0.09px;
}

.p4swes2nq {
  d: path("m15.858 13.165l-.243.776c-.05.16.069.32.238.32h.359a.247.247 0 0 0 .238-.32l-.243-.777c-.052-.172-.295-.172-.35 0");
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmnoj4bii {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.94 12.747a.64.64 0 0 0-.62.483c-.02.08.04.156.123.156h1.02c.064 0 .116-.06.103-.124a.64.64 0 0 0-.627-.515");
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.psru50bbi {
  d: path("M7.735 6.851h2.46v7.269h-2.46z");
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q1wg51bmi {
  d: path("M16 25.93c-2.363 0-4.203-.72-4.828-1.078v-2.907h9.5v3.016c-.573.323-2.31.969-4.672.969");
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.qd4tofb7u {
  d: path("M7.04 29.53v.376h4.632v-1.914H9.32c-.383.377-1.215.73-1.836.941c-.398.169-.445.442-.445.597");
}

.qno0gyhtd {
  d: path("M5.04 2.894a.8.8 0 0 1 .8-.8h.329a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rdwyvqbpo {
  stop-color: var(--svg-color--d69025, #D69025);
}

.rh3jx3c9i {
  d: path("M23.108 5.588a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.015z");
}

.rysyofyzl {
  stop-color: var(--svg-color--825426, #825426);
}

.s_9nzobmx {
  fill: var(--svg-color--f0a321, #F0A321);
  d: path("M13.89 13.725a.735.735 0 1 0 0-1.47a.735.735 0 0 0 0 1.47");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.sf8l-5o7i {
  d: path("M17.03 12.87a.407.407 0 0 1 .393.516h-.787a.41.41 0 0 1 .394-.515");
}

.swi22_bsl {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.853 13.228l-.312.777c-.05.16.069.32.238.32h.359a.247.247 0 0 0 .238-.32l-.243-.777c-.052-.172-.225-.172-.28 0");
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.t8d6ru-nk {
  stop-color: var(--svg-color--6d449a, #6D449A);
  stop-opacity: 0;
}

.tifd2nbhd {
  stop-color: var(--svg-color--ba760f, #BA760F);
}

.tm2gy2bqa {
  fill: var(--svg-color--000, #000);
  d: path("M16.797 13.278c0-.13.103-.233.233-.233a.232.232 0 0 1 .207.34h-.413a.2.2 0 0 1-.027-.107");
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tphhgybtp {
  d: path("M26.922 2.894a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.tydx0uunk {
  stop-color: var(--svg-color--f2b927, #F2B927);
}

.tzfcre5-h {
  d: path("M8.876 5.588a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.823.015z");
}

.u-rrnxf4y {
  stop-color: var(--svg-color--51435f, #51435F);
  stop-opacity: 0;
}

.u521robxh {
  stop-color: var(--svg-color--fdc632, #FDC632);
}

.u6_y93pge {
  d: path("M8.516 21.066a1.988 1.988 0 1 1 3.976 0v1.686a.35.35 0 0 1-.35.35H8.866a.35.35 0 0 1-.35-.35z");
}

.u9zfonkah {
  stop-color: var(--svg-color--ffe430, #FFE430);
}

.uef17en4k {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.125 12.747a.64.64 0 0 1 .62.483a.126.126 0 0 1-.123.156h-1.02a.105.105 0 0 1-.104-.124a.64.64 0 0 1 .627-.515");
}

.ufmuzl7ni {
  d: path("M22.392 5.626a.401.401 0 1 0-.803-.014v.575a.391.391 0 0 0 .783.013z");
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.uk_7vbbxl {
  stop-color: var(--svg-color--fe9724, #FE9724);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
}

.utuf8geyx {
  stop-color: var(--svg-color--cabed2, #CABED2);
  stop-opacity: 0;
}

.uywq_y1iv {
  width: 27.875px;
  height: 1.025px;
  x: 2.063px;
  y: 5.975px;
  rx: 0.2px;
}

.v3dxsi25s {
  stop-color: var(--svg-color--ae7a16, #AE7A16);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vea9pibbt {
  stop-color: var(--svg-color--cc8e21, #CC8E21);
}

.vjv772cbv {
  stop-color: var(--svg-color--e1a82d, #E1A82D);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.w7iv1ibqs {
  stop-color: var(--svg-color--e0aa2d, #E0AA2D);
  stop-opacity: 0;
}

.w8ylb5bcr {
  d: path("M17.392 13.224a.4.4 0 0 0-.105-.21l-.118.129l.053.103z");
}

.wjkbrmbdg {
  stop-color: var(--svg-color--d08d1f, #D08D1F);
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wz5h02v_q {
  stop-color: var(--svg-color--ffd82a, #FFD82A);
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x1baucbnz {
  stop-color: var(--svg-color--eba32a, #EBA32A);
}

.x9t-2zb_r {
  d: path("M3.11 4.402a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.xeb59bcce {
  stroke: var(--svg-color--c25e51, #C25E51);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.88 12.293c.117-.066.386-.211.824-.167");
}

.xot5t6pkw {
  stop-color: var(--svg-color--e9b430, #E9B430);
}

.xzk0urqfv {
  stop-color: var(--svg-color--ffb71f, #FFB71F);
  stop-opacity: 0;
}

.y0nqeezxq {
  d: path("M24.483 5.71a.399.399 0 1 0-.796-.034v.46a.38.38 0 0 0 .758.032z");
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.ygue0q3bo {
  d: path("M18.239 13.48a.49.49 0 1 0 0-.981a.49.49 0 0 0 0 .982");
}

.ymbigdcyd {
  stop-color: var(--svg-color--8263c1, #8263C1);
  stop-opacity: 0;
}

.ymng13duo {
  d: path("M17 12.957c.029.04-.032.086-.1.138c-.07.051-.12.087-.15.049c-.029-.039.004-.112.072-.164c.07-.051.149-.061.178-.023");
}

.yyejvbcrw {
  stop-color: var(--svg-color--d48a23, #D48A23);
}

.yyr7j8rnv {
  stop-color: var(--svg-color--5a3e9b, #5A3E9B);
}

.z0a9xf8ly {
  stop-color: var(--svg-color--ffd42c, #FFD42C);
}

.z0fjtpbfo {
  d: path("M13.835 10.34c.284-.254.694-.256.923-.215l.184.59a.36.36 0 0 0-.31.107c-.208.576-1.02.98-1.352 1.067c-.07-.682.065-1.113.555-1.55");
}

.z0ggixb3q {
  d: path("M9.592 5.626a.401.401 0 1 1 .803-.014v.575a.391.391 0 0 1-.783.013z");
}

.zcsf4yb5o {
  stop-color: var(--svg-color--e0a20c, #E0A20C);
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

</style>
