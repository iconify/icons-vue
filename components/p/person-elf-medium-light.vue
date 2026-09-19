<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLGLUie)"><path class="tdz80xyrh"/><path fill="url(#iIzFe7b)" class="ct5ogkbju"/><path fill="url(#iFfiHwd)" class="ct5ogkbju"/></g><path fill="url(#i4181Eb)" class="ct5ogkbju"/><path fill="url(#iwKURmd)" class="ct5ogkbju"/><g filter="url(#i2nprBb)"><path class="p3j2vhgti"/><path fill="url(#iYAEuQx)" class="pgua_xb8h"/><path fill="url(#idMup7i)" class="pgua_xb8h"/></g><path class="txq_035kl"/><path fill="url(#iQMnshd)" class="k98kmhbdx"/><path fill="url(#igkyYLe)" class="k98kmhbdx"/><path fill="url(#ivBqBmb)" class="k98kmhbdx"/><path class="gsenwumws"/><path fill="url(#iZFDHHd)" class="izxcq-l4x"/><path fill="url(#iJXV6Ub)" class="izxcq-l4x"/><path fill="url(#iQgUGRd)" class="izxcq-l4x"/><path class="p3zz4kb9j"/><path fill="url(#iwVhmFd)" class="e7_cr3bza"/><path fill="url(#iPOkLCc)" class="e7_cr3bza"/><path fill="url(#imhPERc)" class="e7_cr3bza"/><path fill="url(#iSVv4Vb)" class="kbs6vktjf"/><path fill="url(#izhbSZc)" class="kbs6vktjf"/><path fill="url(#iveVs0A)" class="kbs6vktjf"/><path fill="url(#i3RFzmd)" class="kbs6vktjf"/><path fill="url(#ijDoaLb)" class="kbs6vktjf"/><path fill="url(#iXxNf8b)" class="kbs6vktjf"/><g filter="url(#ikjrcIe)"><path fill="url(#iZhDCUz)" class="hznm33ftf"/></g><g filter="url(#iYdi9vd)"><path fill="url(#iMi7xEe)" class="oshqjyb1k"/></g><path class="z7q9w9nsq"/><path fill="url(#io2dINc)" class="nmpn19wzd"/><path fill="url(#iItREmH)" class="nmpn19wzd"/><path fill="url(#iCa76SL)" class="nmpn19wzd"/><path fill="url(#i3WYIMe)" class="nmpn19wzd"/><path fill="url(#iEruxub)" class="nmpn19wzd"/><path fill="url(#iIwqxUQ)" class="nmpn19wzd"/><path fill="url(#i5EInCc)" class="nmpn19wzd"/><path fill="url(#icC4Ejd)" class="nmpn19wzd"/><path fill="url(#i1RPp3b)" class="v8wnikn7p"/><path fill="url(#iB8bj2Q)" class="v8wnikn7p"/><path fill="url(#ihmh9pe)" class="v8wnikn7p"/><path fill="url(#iEQT5Bw)" class="v8wnikn7p"/><path fill="url(#igGUIPe)" class="v8wnikn7p"/><g filter="url(#iYKtxib)"><path fill="url(#iw9uSuM)" class="drrcjgbmp"/><path fill="url(#i2Hk7Oe)" class="drrcjgbmp"/></g><path fill="url(#ixzRBzd)" class="s1uyvobna"/><path fill="url(#i680xYa)" class="s1uyvobna"/><g filter="url(#iC2NqMQ)"><path class="cc9dkzbch"/></g><g filter="url(#i176Dte)"><path class="o72-b5bhn"/></g><g filter="url(#irxU5Fc)"><path class="t6oix3hhn"/></g><g filter="url(#i2bFFfd)"><path fill="url(#iZWBa3b)" class="wj_0ttb5q"/></g><g filter="url(#ijMjRbe)"><path fill="url(#iouAFxb)" class="lcblgbkky"/><path fill="url(#iLhrOqe)" class="lcblgbkky"/></g><g filter="url(#i3of8Hb)"><path fill="url(#ia0aZmb)" class="ulf-7gbex"/><path fill="url(#iCL3kIb)" class="ulf-7gbex"/><path fill="url(#igPfPJb)" class="ulf-7gbex"/><path fill="url(#i4xzxLe)" class="ulf-7gbex"/><path fill="url(#i3G2ZPb)" class="ulf-7gbex"/><path fill="url(#ipSP41D)" class="ulf-7gbex"/></g><path fill="url(#iYzJU8c)" class="ulf-7gbex"/><path fill="url(#i6d4Bse)" class="guykq4bte"/><path fill="url(#iclLlKc)" class="guykq4bte"/><path fill="url(#iLRAJ3d)" class="guykq4bte"/><path fill="url(#ib0LyCe)" class="guykq4bte"/><path fill="url(#iEtnrFb)" class="guykq4bte"/><path fill="url(#ilBmCbd)" class="guykq4bte"/><path fill="url(#inBbkOc)" class="guykq4bte"/><g filter="url(#ih0XyAd)"><path fill="url(#iiEcmAe)" class="hl55lzb8b"/><path fill="url(#itztxSc)" class="hl55lzb8b"/></g><g filter="url(#i6WRggc)"><path fill="url(#iNqvhjb)" class="qtvun2a2x"/><path fill="url(#ix65EIc)" class="qtvun2a2x"/><path fill="url(#ia3EWHo)" class="qtvun2a2x"/><path fill="url(#i3fffGd)" class="qtvun2a2x"/></g><path fill="url(#iSWw44C)" class="mnbvi-beq"/><path fill="url(#iyRbZUb)" class="mnbvi-beq"/><path fill="url(#iZYe5Mb)" class="mnbvi-beq"/><path fill="url(#ipWMnUD)" class="mnbvi-beq"/><path fill="url(#idbYYpe)" class="mnbvi-beq"/><path fill="url(#iNjnfAc)" class="mnbvi-beq"/><path fill="url(#iD1FxLd)" class="w5vn6kb5o"/><path stroke="url(#iGNVdnb)" class="c4i1tcc7b"/><g filter="url(#i7zKzFd)"><path class="iuymwvcbo"/></g><path stroke="url(#iYVgKWb)" class="bok5f_uws"/><g filter="url(#iiCM8nc)"><path class="p1udt06bx"/></g><g filter="url(#iCQsMmR)"><path class="jbwbdrjdn"/></g><path class="ne81pbb8b"/><path fill="url(#i262hxd)" class="g1h1v_f7b"/><path fill="url(#iMRu0wd)" class="g1h1v_f7b"/><path fill="url(#iSYnkHR)" class="g1h1v_f7b"/><g filter="url(#ig1UI8u)"><path stroke="url(#iSgF9hA)" class="f5g35n02h"/></g><path class="kry1ddb0t"/><path class="dde1o5bku"/><path fill="url(#i0O8Yfb)" class="r3bbexlfa"/><path class="q6_fzs7-r"/><g filter="url(#iU72OPg)"><path class="xid210bhr"/><path fill="url(#idv22kN)" class="zhcjv5uud"/></g><g filter="url(#invK5cd)"><path fill="url(#i5Q6rbc)" class="bbvz2obwe"/></g><path class="rnooggajo"/><path fill="url(#iVXvR2c)" class="pkb7vsbwf"/><path class="ucz1v1bss"/><g filter="url(#iywOu3c)"><path fill="url(#isi63hb)" class="ql3irgbnp"/></g><g filter="url(#iNmLyGR)"><ellipse transform="rotate(-27.914 13.547 9.778)" class="tp-a8qw8b"/><ellipse fill="url(#iyTjOAc)" transform="rotate(-27.914 13.547 9.778)" class="h6gt32ejx"/></g><g filter="url(#i5K6uSd)"><path stroke="url(#iytDscd)" class="jz3fl9fna"/></g><defs><radialGradient id="iIzFe7b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59143 1.98438 -5.14037 -4.12248 23.705 11.883)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="g34co-bjj"/><stop offset="1" class="j0iym8bez"/></radialGradient><radialGradient id="iFfiHwd" cx="0" cy="0" r="1" gradientTransform="matrix(1.6383 .29074 -.8262 4.65558 20.317 14.03)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="r-p883bfh"/><stop offset="1" class="jnmw52bvm"/></radialGradient><radialGradient id="i4181Eb" cx="0" cy="0" r="1" gradientTransform="matrix(.73438 3.71875 -3.59965 .71086 22.41 14.107)" gradientUnits="userSpaceOnUse"><stop offset=".881" class="ly3r7ebiq"/><stop offset="1" class="ja41yub3g"/></radialGradient><radialGradient id="iwKURmd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.289 25.201 -8.557)scale(1.9436 3.02274)" gradientUnits="userSpaceOnUse"><stop class="m2zebkb3b"/><stop offset="1" class="lj7znd7rs"/></radialGradient><radialGradient id="iYAEuQx" cx="0" cy="0" r="1" gradientTransform="matrix(-.76854 -2.3752 2.9525 -.95534 9.87 17.576)" gradientUnits="userSpaceOnUse"><stop class="sl7vf6bvq"/><stop offset="1" class="k7vxnrb9w"/></radialGradient><radialGradient id="idMup7i" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39063 .57888 -1.52227 -6.28657 12.111 14.413)" gradientUnits="userSpaceOnUse"><stop class="smbbml-bd"/><stop offset="1" class="vgv3oz8qv"/></radialGradient><radialGradient id="igkyYLe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -11.6596 23.142 20.664)" gradientUnits="userSpaceOnUse"><stop class="t2ybzjp2q"/><stop offset="1" class="wodhbzf-c"/></radialGradient><radialGradient id="ivBqBmb" cx="0" cy="0" r="1" gradientTransform="rotate(-110.347 20.47 5.173)scale(3.59496 4.80694)" gradientUnits="userSpaceOnUse"><stop class="i1lv4bpfj"/><stop offset="1" class="mxgskb25j"/></radialGradient><radialGradient id="iZFDHHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.59707 0 0 -12.1778 9.033 29.916)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="t219k_b_a"/><stop offset="1" class="nrfhyjbig"/></radialGradient><radialGradient id="iJXV6Ub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69302 6.8777 -1.92029 -.4727 6.992 23.039)" gradientUnits="userSpaceOnUse"><stop class="a3tgwzvkw"/><stop offset="1" class="zjfb-u0iw"/></radialGradient><radialGradient id="iwVhmFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -10.40629 1.71323 -.26753 25.58 28.351)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="em6jl46va"/><stop offset="1" class="syfl0-b7z"/></radialGradient><radialGradient id="imhPERc" cx="0" cy="0" r="1" gradientTransform="matrix(.49206 0 0 10.875 23.088 26.445)" gradientUnits="userSpaceOnUse"><stop class="yy-0gacyg"/><stop offset="1" class="d07-_rbjf"/></radialGradient><radialGradient id="izhbSZc" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 -2.65624 14.81119 11.32622 15.736 29.758)" gradientUnits="userSpaceOnUse"><stop class="rbi44vm-m"/><stop offset="1" class="qfs6aobhn"/></radialGradient><radialGradient id="iveVs0A" cx="0" cy="0" r="1" gradientTransform="rotate(-132.42 17.243 11.363)scale(18.1601 26.3733)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="pc9y3hbhd"/><stop offset="1" class="vhxxajp3a"/></radialGradient><radialGradient id="i3RFzmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.53125 -8.40625 0 15.986 18.133)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="sb4dv46vs"/><stop offset="1" class="ro5kwtkrd"/></radialGradient><radialGradient id="iZhDCUz" cx="0" cy="0" r="1" gradientTransform="rotate(97.64 -1.617 18.109)scale(3.08805 1.1998)" gradientUnits="userSpaceOnUse"><stop class="xnfwhubut"/><stop offset="1" class="nd_uzdbib"/></radialGradient><radialGradient id="iMi7xEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.63279 -.8125 0 16.517 22.508)" gradientUnits="userSpaceOnUse"><stop class="o5xzi4bgi"/><stop offset="1" class="ui8xaew_b"/></radialGradient><radialGradient id="io2dINc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.82031 -7.8263 0 16 16.289)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="wdde7fbgs"/><stop offset="1" class="qt8zeccfx"/></radialGradient><radialGradient id="iItREmH" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 3.875 -2.05328 1.25846 8.83 16.101)" gradientUnits="userSpaceOnUse"><stop class="fg4eg_4fj"/><stop offset="1" class="eul_yij3i"/></radialGradient><radialGradient id="iCa76SL" cx="0" cy="0" r="1" gradientTransform="rotate(57.322 -7.396 18.171)scale(4.91974 4.45192)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="etr4yvr5e"/><stop offset="1" class="b37sysbpy"/></radialGradient><radialGradient id="i3WYIMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.78127 3.28124 -2.8026 1.52144 12.924 15.133)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="r19r51k_n"/><stop offset="1" class="ah36gjjbi"/></radialGradient><radialGradient id="iEruxub" cx="0" cy="0" r="1" gradientTransform="matrix(1.50686 .88968 -2.07086 3.50742 18.196 16.957)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="ol2rfkycm"/><stop offset="1" class="thpmep7jb"/></radialGradient><radialGradient id="iIwqxUQ" cx="0" cy="0" r="1" gradientTransform="rotate(104.647 4.863 15.397)scale(4.14235 9.13048)" gradientUnits="userSpaceOnUse"><stop class="irx6jyb5l"/><stop offset="1" class="jaugt_k_p"/></radialGradient><radialGradient id="i5EInCc" cx="0" cy="0" r="1" gradientTransform="rotate(36.076 -15.3 37.145)scale(.67663 1.97401)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="yx9tb8yxt"/><stop offset="1" class="gy5_zq-5b"/></radialGradient><radialGradient id="icC4Ejd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.7235 2.96875 -1.22621 -1.12492 22.585 15.976)" gradientUnits="userSpaceOnUse"><stop class="yapr3et_m"/><stop offset="1" class="ht8m2nb0n"/></radialGradient><radialGradient id="i1RPp3b" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 -4.22173 2.03479 1.08445 16.142 20.386)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="q52fr3noq"/><stop offset="1" class="w_rnmcxom"/></radialGradient><radialGradient id="ihmh9pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.4375 -4.25757 0 15.98 16.476)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="px6vm6bxx"/><stop offset="1" class="nuy6hm44h"/></radialGradient><radialGradient id="iEQT5Bw" cx="0" cy="0" r="1" gradientTransform="rotate(42.523 -14.346 24.59)scale(3.58325 2.63576)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="nt3ohmb5v"/><stop offset="1" class="hd78y1x_x"/></radialGradient><radialGradient id="iw9uSuM" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -1.59462 3.4012 3.06607 8.861 10.165)" gradientUnits="userSpaceOnUse"><stop class="asqw3jbui"/><stop offset="1" class="q8p3q3bqx"/></radialGradient><radialGradient id="i2Hk7Oe" cx="0" cy="0" r="1" gradientTransform="rotate(72.147 -.353 10.026)scale(5.60612 3.91608)" gradientUnits="userSpaceOnUse"><stop offset=".707" class="tvz40gbou"/><stop offset="1" class="si20u1b5q"/></radialGradient><radialGradient id="ixzRBzd" cx="0" cy="0" r="1" gradientTransform="rotate(-137.265 7.499 3.484)scale(2.57883 1.75313)" gradientUnits="userSpaceOnUse"><stop class="t60ntu-wj"/><stop offset="1" class="nld201kgm"/></radialGradient><radialGradient id="i680xYa" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -1.01563 3.53448 3.04507 9.533 10.788)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="o20k0cbhd"/><stop offset="1" class="fp865pypd"/></radialGradient><radialGradient id="iouAFxb" cx="0" cy="0" r="1" gradientTransform="rotate(-54.058 22.006 -15.2)scale(3.85988 2.29361)" gradientUnits="userSpaceOnUse"><stop class="sx3rjlbzk"/><stop offset="1" class="dkch0db-r"/></radialGradient><radialGradient id="iLhrOqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11719 -1.04687 3.854 -4.11286 22.707 10.851)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="dye_m7bch"/><stop offset="1" class="sd49k712l"/></radialGradient><radialGradient id="ia0aZmb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.96875 0 0 -10.1138 19.486 10.982)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="ro__zqilq"/><stop offset=".659" class="s0u10ejgs"/></radialGradient><radialGradient id="iCL3kIb" cx="0" cy="0" r="1" gradientTransform="rotate(-113.782 9.778 .247)scale(1.59313 1.68253)" gradientUnits="userSpaceOnUse"><stop class="c7ols3oue"/><stop offset="1" class="vs6qzmbeh"/></radialGradient><radialGradient id="igPfPJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.05826 -1.54029 1.70531 -.0645 18.389 9.516)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="fdx7kfdrk"/><stop offset="1" class="itpb-mb4j"/></radialGradient><radialGradient id="i4xzxLe" cx="0" cy="0" r="1" gradientTransform="rotate(118.989 7.107 8.539)scale(2.64372 1.90605)" gradientUnits="userSpaceOnUse"><stop class="q439j4sbs"/><stop offset="1" class="ddoxxtboo"/></radialGradient><radialGradient id="i3G2ZPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.62025 3.72489 -7.3403 3.19287 14.332 4.977)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="vtamvdyqj"/><stop offset="1" class="uvyahya6g"/></radialGradient><radialGradient id="iYzJU8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.30859 -10.2999 0 15.952 9.68)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="jm6-jkb_l"/><stop offset="1" class="ecc-79p_w"/></radialGradient><radialGradient id="i6d4Bse" cx="0" cy="0" r="1" gradientTransform="rotate(120.719 8.287 6.685)scale(5.01638 9.45422)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset=".592" class="nvp34342a"/></radialGradient><radialGradient id="iclLlKc" cx="0" cy="0" r="1" gradientTransform="matrix(.25 2.3655 -2.25832 .23867 20.3 3.773)" gradientUnits="userSpaceOnUse"><stop class="r0z1khbsa"/><stop offset="1" class="luxz9w7iu"/></radialGradient><radialGradient id="iLRAJ3d" cx="0" cy="0" r="1" gradientTransform="matrix(2.8125 -.197 .38327 5.47201 9.176 7.023)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="wyqd5ab8k"/><stop offset="1" class="l3hsrn8ob"/></radialGradient><radialGradient id="ib0LyCe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43752 3.49999 -1.48595 -.61031 11.707 3.554)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="lgj7dyo1j"/><stop offset="1" class="wjq_rgywi"/></radialGradient><radialGradient id="iEtnrFb" cx="0" cy="0" r="1" gradientTransform="matrix(.40625 -1.07813 6.40833 2.41474 10.504 9.186)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="k8f_-10rg"/><stop offset="1" class="l1kqit9sq"/></radialGradient><radialGradient id="ilBmCbd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.6 19.114 -14.61)scale(1.9246 3.63447)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="a4sfhobbt"/><stop offset="1" class="zeavlp0uo"/></radialGradient><radialGradient id="inBbkOc" cx="0" cy="0" r="1" gradientTransform="rotate(-103.109 9.618 -1.766)scale(2.34229 5.71314)" gradientUnits="userSpaceOnUse"><stop class="cu84zd6ok"/><stop offset="1" class="k_huevcxk"/></radialGradient><radialGradient id="itztxSc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4597 1.15626 -.59734 -1.78734 16.073 3.92)" gradientUnits="userSpaceOnUse"><stop class="qfx4f-mat"/><stop offset="1" class="wy3jcw9jp"/></radialGradient><radialGradient id="iNqvhjb" cx="0" cy="0" r="1" gradientTransform="matrix(3.63293 .1875 -.04917 .95273 18.822 4.664)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="vsbibr_ed"/><stop offset="1" class="zmahyob7y"/></radialGradient><radialGradient id="ix65EIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.40836 -2.2346 7.9682 5.02198 18.638 5.786)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="t0ficfbbx"/><stop offset="1" class="w1ahfsiui"/></radialGradient><radialGradient id="i3fffGd" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -.6875 1.03347 1.90252 16.488 4.951)" gradientUnits="userSpaceOnUse"><stop class="qhrgfk8ap"/><stop offset="1" class="eiyn6rq_o"/></radialGradient><radialGradient id="ipWMnUD" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 0 0 -.60938 21.767 5.476)" gradientUnits="userSpaceOnUse"><stop class="ekarirbxr"/><stop offset="1" class="n81djoa0z"/></radialGradient><radialGradient id="idbYYpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .54688 -8.71875 0 11.174 4.945)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="b4qr-wvfv"/><stop offset="1" class="yyik5z8lx"/></radialGradient><radialGradient id="iNjnfAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92969 -.45312 0 15.228 5.164)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="h6i96qjvc"/><stop offset="1" class="d31bklhyx"/></radialGradient><radialGradient id="iD1FxLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.90625 2.05457 0 15.978 6.742)" gradientUnits="userSpaceOnUse"><stop class="rkzp1hbvm"/><stop offset="1" class="j5zu11bke"/></radialGradient><radialGradient id="iSgF9hA" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 -.625 1.875 .98437 14.614 14.133)" gradientUnits="userSpaceOnUse"><stop class="w42gypbga"/><stop offset="1" class="n8iweabrd"/></radialGradient><radialGradient id="i0O8Yfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6777 .87332 -.95908 -.74426 18.43 9.96)" gradientUnits="userSpaceOnUse"><stop class="qxnakxbrg"/><stop offset="1" class="egerxebfb"/></radialGradient><radialGradient id="idv22kN" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.415 .583)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVXvR2c" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 4.594 8.425)scale(1.10548 1.21404)" gradientUnits="userSpaceOnUse"><stop class="qxnakxbrg"/><stop offset="1" class="egerxebfb"/></radialGradient><radialGradient id="iyTjOAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.531 10.093)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iQMnshd" x1="15.049" x2="15.049" y1="29.917" y2="20.508" gradientUnits="userSpaceOnUse"><stop class="zej61lbmf"/><stop offset="1" class="dsw94cbmu"/></linearGradient><linearGradient id="iQgUGRd" x1="8.912" x2="8.912" y1="29.916" y2="21.101" gradientUnits="userSpaceOnUse"><stop class="ce9e8ebsk"/><stop offset="1" class="u4rwp_bwq"/></linearGradient><linearGradient id="iPOkLCc" x1="24.142" x2="26.611" y1="29.289" y2="21.383" gradientUnits="userSpaceOnUse"><stop offset=".116" class="z5lko3bbf"/><stop offset="1" class="r-ruyz2yf"/></linearGradient><linearGradient id="iSVv4Vb" x1="12.517" x2="22.705" y1="21.258" y2="30.914" gradientUnits="userSpaceOnUse"><stop class="l2u0pibnj"/><stop offset="1" class="nkujmsbyn"/></linearGradient><linearGradient id="ijDoaLb" x1="15.015" x2="15.229" y1="28.651" y2="28.447" gradientUnits="userSpaceOnUse"><stop class="p8z5r2h1v"/><stop offset="1" class="nstnghbkd"/></linearGradient><linearGradient id="iXxNf8b" x1="19.002" x2="18.65" y1="21.961" y2="22.32" gradientUnits="userSpaceOnUse"><stop class="i-kbbcb4w"/><stop offset="1" class="k1jzsjbfs"/></linearGradient><linearGradient id="iB8bj2Q" x1="15.098" x2="15.695" y1="19.67" y2="19.268" gradientUnits="userSpaceOnUse"><stop offset=".184" class="e8x8t6m4c"/><stop offset="1" class="sfwupzbpl"/></linearGradient><linearGradient id="igGUIPe" x1="17.642" x2="16.895" y1="18.57" y2="18.195" gradientUnits="userSpaceOnUse"><stop class="ytmccib4c"/><stop offset="1" class="zsyl6jyid"/></linearGradient><linearGradient id="iZWBa3b" x1="21.832" x2="23.715" y1="11.617" y2="8.648" gradientUnits="userSpaceOnUse"><stop offset=".667" class="yr_fudj4r"/><stop offset="1" class="ler-mrb8r"/></linearGradient><linearGradient id="ipSP41D" x1="21.426" x2="19.801" y1="11.367" y2="11.304" gradientUnits="userSpaceOnUse"><stop offset=".267" class="b-7ftg6nf"/><stop offset="1" class="cd8hmxqwr"/></linearGradient><linearGradient id="iiEcmAe" x1="12.082" x2="12.426" y1="7.451" y2="4.076" gradientUnits="userSpaceOnUse"><stop class="q96xbxbcl"/><stop offset="1" class="ffiwsc2ql"/></linearGradient><linearGradient id="ia3EWHo" x1="18.457" x2="18.488" y1="7.607" y2="5.264" gradientUnits="userSpaceOnUse"><stop class="abrviqbym"/><stop offset="1" class="mntu2074k"/></linearGradient><linearGradient id="iSWw44C" x1="15.58" x2="17.299" y1="5.65" y2="5.65" gradientUnits="userSpaceOnUse"><stop class="z5duhrbsp"/><stop offset="1" class="qjga9kbjc"/></linearGradient><linearGradient id="iyRbZUb" x1="15.644" x2="15.644" y1="6.307" y2="5.65" gradientUnits="userSpaceOnUse"><stop class="i817agb_c"/><stop offset="1" class="tp-3hccxn"/></linearGradient><linearGradient id="iZYe5Mb" x1="15.969" x2="15.969" y1="4.734" y2="5.32" gradientUnits="userSpaceOnUse"><stop class="p59cvi4fc"/><stop offset="1" class="nr_-dacny"/></linearGradient><linearGradient id="iGNVdnb" x1="13.088" x2="12.791" y1="8.248" y2="7.482" gradientUnits="userSpaceOnUse"><stop offset=".3" class="izc32rvpj"/><stop offset="1" class="iyykd5bnv"/></linearGradient><linearGradient id="iYVgKWb" x1="18.816" x2="19.113" y1="8.248" y2="7.482" gradientUnits="userSpaceOnUse"><stop offset=".3" class="izc32rvpj"/><stop offset="1" class="a_-twrhmu"/></linearGradient><linearGradient id="i262hxd" x1="16.938" x2="15.238" y1="11.498" y2="11.639" gradientUnits="userSpaceOnUse"><stop offset=".117" class="ebnkoj8rz"/><stop offset=".685" class="yr_s1wb-e"/></linearGradient><linearGradient id="iMRu0wd" x1="15.832" x2="15.832" y1="12.67" y2="11.842" gradientUnits="userSpaceOnUse"><stop offset=".072" class="qvn0k1bbh"/><stop offset="1" class="l5lubve6n"/></linearGradient><linearGradient id="iSYnkHR" x1="16" x2="16" y1="9.77" y2="10.414" gradientUnits="userSpaceOnUse"><stop class="xogtr7m2h"/><stop offset="1" class="hzipojmca"/></linearGradient><linearGradient id="i5Q6rbc" x1="18.96" x2="18.646" y1="9.928" y2="10.121" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isi63hb" x1="14.562" x2="14.248" y1="9.928" y2="10.121" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iytDscd" x1="15.861" x2="14.049" y1="20.476" y2="17.992" gradientUnits="userSpaceOnUse"><stop class="qd6na2-uz"/><stop offset="1" class="syu7jn24l"/></linearGradient><filter id="iLGLUie" width="7.408" height="7.009" x="17.877" y="11.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.94902 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1372"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1372" result="effect2_innerShadow_4002_1372"/></filter><filter id="i2nprBb" width="7.258" height="6.609" x="6.975" y="11.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.764706 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1372"/></filter><filter id="ikjrcIe" width="2.581" height="5.008" x="14.415" y="20.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".25"/></filter><filter id="iYdi9vd" width="1.681" height="4.108" x="15.197" y="20.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1372"/></filter><filter id="iYKtxib" width="3.872" height="5.121" x="7.884" y="7.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.462745 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1372"/></filter><filter id="iC2NqMQ" width="2.764" height="2.303" x="8.462" y="8.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".05"/></filter><filter id="i176Dte" width="3.972" height="5.021" x="20.244" y="7.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.596078 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1372"/></filter><filter id="irxU5Fc" width="3.402" height="2.55" x="20.573" y="7.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".1"/></filter><filter id="i2bFFfd" width="3.267" height="4.113" x="20.648" y="8.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".1"/></filter><filter id="ijMjRbe" width="2.552" height="3.266" x="20.8" y="8.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".05"/></filter><filter id="i3of8Hb" width="11.183" height="12.012" x="10.661" y="4.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.627451 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1372"/></filter><filter id="ih0XyAd" width="6.417" height="5.694" x="9.906" y="2.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".125"/></filter><filter id="i6WRggc" width="6.446" height="5.609" x="15.553" y="2.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".125"/></filter><filter id="i7zKzFd" width="2.169" height=".842" x="12.219" y="7.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".075"/></filter><filter id="iiCM8nc" width="2.169" height=".842" x="17.516" y="7.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".075"/></filter><filter id="iCQsMmR" width="3.187" height="4.4" x="14.104" y="9.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".375"/></filter><filter id="ig1UI8u" width="3.668" height="1.523" x="14.166" y="13.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".075"/></filter><filter id="iU72OPg" width=".787" height=".696" x="17.448" y="9.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".05"/></filter><filter id="invK5cd" width=".891" height=".913" x="18.287" y="9.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".1"/></filter><filter id="iywOu3c" width=".986" height="1.04" x="13.845" y="9.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".1"/></filter><filter id="iNmLyGR" width=".913" height=".705" x="13.09" y="9.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".05"/></filter><filter id="i5K6uSd" width="2.916" height="3.003" x="13.723" y="18.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1372" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-elf-medium-light" /></template>
<style>
.a_-twrhmu {
  stop-color: var(--svg-color--9b6638, #9B6638);
}

.a3tgwzvkw {
  stop-color: var(--svg-color--82bd6c, #82BD6C);
}

.a4sfhobbt {
  stop-color: var(--svg-color--d0a56a, #D0A56A);
}

.abrviqbym {
  stop-color: var(--svg-color--e9c090, #E9C090);
}

.ah36gjjbi {
  stop-color: var(--svg-color--814a40, #814A40);
  stop-opacity: 0;
}

.asqw3jbui {
  stop-color: var(--svg-color--b77c64, #B77C64);
}

.b-7ftg6nf {
  stop-color: var(--svg-color--f0bf99, #F0BF99);
}

.b37sysbpy {
  stop-color: var(--svg-color--77473a, #77473A);
  stop-opacity: 0;
}

.b4qr-wvfv {
  stop-color: var(--svg-color--949393, #949393);
}

.bbvz2obwe {
  d: path("M18.979 10.172a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.bok5f_uws {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.46 8.054c-.195-.136-.84-.472-1.719-.375");
}

.c4i1tcc7b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.445 8.054c.195-.136.84-.472 1.718-.375");
}

.c7ols3oue {
  stop-color: var(--svg-color--c5887b, #C5887B);
}

.cc9dkzbch {
  stroke: var(--svg-color--c68d7a, #C68D7A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M8.637 8.498c.476.164 1.672.953 2.414 1.953");
}

.cd8hmxqwr {
  stop-color: var(--svg-color--fcc49f, #FCC49F);
  stop-opacity: 0;
}

.ce9e8ebsk {
  stop-color: var(--svg-color--4f7e79, #4F7E79);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ct5ogkbju {
  d: path("M23.879 12.898c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.282l3.313 3.328c2.469-.082 3.322-1.085 3.585-2.024c.36-1.28-.187-2.109-1.296-2.992");
}

.cu84zd6ok {
  stop-color: var(--svg-color--cfa286, #CFA286);
}

.d07-_rbjf {
  stop-color: var(--svg-color--67a16e, #67A16E);
  stop-opacity: 0;
}

.d31bklhyx {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
  stop-opacity: 0;
}

.dde1o5bku {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.39 9.125c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ddoxxtboo {
  stop-color: var(--svg-color--dea692, #DEA692);
  stop-opacity: 0;
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dkch0db-r {
  stop-color: var(--svg-color--d8a487, #D8A487);
}

.drrcjgbmp {
  d: path("M8.763 7.754a6.6 6.6 0 0 1 2.473 1.726l.52 3.024c-.356.052-1.371.609-2.633-1.203a10.7 10.7 0 0 1-1.21-2.751c-.152-.536.332-1.001.85-.796");
}

.dsw94cbmu {
  stop-color: var(--svg-color--659d70, #659D70);
  stop-opacity: 0;
}

.dye_m7bch {
  stop-color: var(--svg-color--d5a184, #D5A184);
  stop-opacity: 0;
}

.e7_cr3bza {
  d: path("M23.088 18.28a10.9 10.9 0 0 1 3.84 8.318v3.319h-3.84z");
}

.e8x8t6m4c {
  stop-color: var(--svg-color--c88d69, #C88D69);
}

.ebnkoj8rz {
  stop-color: var(--svg-color--f5c2a6, #F5C2A6);
}

.ecc-79p_w {
  stop-color: var(--svg-color--ae6b6c, #AE6B6C);
}

.egerxebfb {
  stop-color: var(--svg-color--694c3f, #694C3F);
}

.eiyn6rq_o {
  stop-color: var(--svg-color--e6ca98, #E6CA98);
  stop-opacity: 0;
}

.ekarirbxr {
  stop-color: var(--svg-color--ede5f4, #EDE5F4);
}

.em6jl46va {
  stop-color: var(--svg-color--88c975, #88C975);
}

.etr4yvr5e {
  stop-color: var(--svg-color--77473a, #77473A);
}

.eul_yij3i {
  stop-color: var(--svg-color--9e6c66, #9E6C66);
  stop-opacity: 0;
}

.f5g35n02h {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16 13.687c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.13-.06-.279-.198-.209a3 3 0 0 1-1.385.329Z");
}

.fdx7kfdrk {
  stop-color: var(--svg-color--e6a78d, #E6A78D);
}

.ffiwsc2ql {
  stop-color: var(--svg-color--e8c994, #E8C994);
  stop-opacity: 0;
}

.fg4eg_4fj {
  stop-color: var(--svg-color--9e6c66, #9E6C66);
}

.fp865pypd {
  stop-color: var(--svg-color--b87f6a, #B87F6A);
}

.ft5dv1b6b {
  fill: none;
}

.g1h1v_f7b {
  d: path("m15.618 10.075l-.532 1.839c-.109.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.g34co-bjj {
  stop-color: var(--svg-color--fff1bb, #FFF1BB);
}

.gsenwumws {
  fill: var(--svg-color--74af4b, #74AF4B);
  d: path("M8.912 18.28a10.9 10.9 0 0 0-3.84 8.318v3.319h3.84z");
}

.guykq4bte {
  d: path("m10.722 8.104l.042.9a6.7 6.7 0 0 0-.925-.703c-.579-1.153-.547-1.839-.238-2.569c.285-.672.978-1.072 1.422-1.329q.083-.046.153-.089q.116-.069.218-.124c.31-.174.544-.305.996-.856c1.008-1.367 2-1.328 2.72-1.18l.185.039c.335.07.48.1.654.1c.186 0 .315-.027.61-.088l.243-.05c.73-.15 1.738-.188 2.761 1.179c.459.551.696.682 1.012.856q.103.055.222.124l.154.09c.452.256 1.155.656 1.444 1.328c.314.732.347 1.418-.245 2.575c-.413.262-.75.54-1.008.785l.045-.988c.03-.428-.357-1.368-1.269-1.368c-.8 0-1.167.01-1.364.016l-.165.004c-.785 0-1.58-.184-2.126-.984h-.623c-.537.8-1.32.984-2.093.984l-.175-.004a49 49 0 0 0-1.4-.016c-.898 0-1.278.94-1.25 1.368");
}

.gy5_zq-5b {
  stop-color: var(--svg-color--6a3a22, #6A3A22);
  stop-opacity: 0;
}

.h6gt32ejx {
  cx: 13.547px;
  cy: 9.778px;
  rx: 0.39px;
  ry: 0.197px;
}

.h6i96qjvc {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
}

.hd78y1x_x {
  stop-color: var(--svg-color--9e634a, #9E634A);
  stop-opacity: 0;
}

.hl55lzb8b {
  d: path("M10.16 6.625c.057.825.292 1.336.435 1.445c-.023-.221.132-.67.375-.977c.244-.306.664-.463.883-.468c.076 0 .44-.024 1.196 0c1.484.046 1.937-.149 2.601-1.094s.44-1.875.05-2.29a1.174 1.174 0 0 0-1.657-.046c-.53.492-.96.414-2.093.89s-1.86 1.508-1.79 2.54");
}

.ht8m2nb0n {
  stop-color: var(--svg-color--a86b65, #A86B65);
  stop-opacity: 0;
}

.hzipojmca {
  stop-color: var(--svg-color--dea68b, #DEA68B);
  stop-opacity: 0;
}

.hznm33ftf {
  d: path("M15.706 21.11c.263.22.79.923.79 1.906c0 1.053-.358 1.646-.702 2.06a.115.115 0 0 1-.177 0c-.343-.414-.702-1.007-.702-2.06c0-.983.527-1.686.79-1.907");
}

.i-kbbcb4w {
  stop-color: var(--svg-color--906550, #906550);
}

.i1lv4bpfj {
  stop-color: var(--svg-color--79b576, #79B576);
}

.i817agb_c {
  stop-color: var(--svg-color--9777b8, #9777B8);
}

.irx6jyb5l {
  stop-color: var(--svg-color--8e5034, #8E5034);
}

.itpb-mb4j {
  stop-color: var(--svg-color--e8af96, #E8AF96);
  stop-opacity: 0;
}

.iuymwvcbo {
  stroke: var(--svg-color--7b532f, #7B532F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.445 8.054c.195-.136.84-.472 1.718-.375");
}

.iyykd5bnv {
  stop-color: var(--svg-color--784b26, #784B26);
}

.izc32rvpj {
  stop-color: var(--svg-color--69431f, #69431F);
}

.izxcq-l4x {
  d: path("M8.912 18.28a10.9 10.9 0 0 0-3.84 8.318v3.319h3.84z");
}

.j0iym8bez {
  stop-color: var(--svg-color--ffdbac, #FFDBAC);
  stop-opacity: 0;
}

.j5zu11bke {
  stop-color: var(--svg-color--c2ffff, #C2FFFF);
}

.ja41yub3g {
  stop-color: var(--svg-color--d5b08a, #D5B08A);
}

.jaugt_k_p {
  stop-color: var(--svg-color--8e5034, #8E5034);
  stop-opacity: 0;
}

.jbwbdrjdn {
  fill: var(--svg-color--cd907e, #CD907E);
  d: path("m15.447 10.271l-.57 1.838c-.098.379.136.757.467.757h.707c.331 0 .565-.384.468-.757l-.478-1.838c-.102-.407-.487-.407-.594 0");
}

.jm6-jkb_l {
  stop-color: var(--svg-color--c08183, #C08183);
  stop-opacity: 0;
}

.jnmw52bvm {
  stop-color: var(--svg-color--f2c192, #F2C192);
  stop-opacity: 0;
}

.jz3fl9fna {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.049 18.414L15.61 20.6c.12.125.428.3.703 0");
}

.k_huevcxk {
  stop-color: var(--svg-color--cfa286, #CFA286);
  stop-opacity: 0;
}

.k1jzsjbfs {
  stop-color: var(--svg-color--7f4b4c, #7F4B4C);
  stop-opacity: 0;
}

.k7vxnrb9w {
  stop-color: var(--svg-color--d8a584, #D8A584);
  stop-opacity: 0;
}

.k8f_-10rg {
  stop-color: var(--svg-color--a97e4c, #A97E4C);
}

.k98kmhbdx {
  d: path("M5.071 26.599c0-6.036 4.893-10.93 10.929-10.93s10.929 4.894 10.929 10.93v3.318H5.07z");
}

.kbs6vktjf {
  d: path("M16.274 29.917L7.053 20.32a10.95 10.95 0 0 1 5.854-4.207L26.69 29.917z");
}

.kry1ddb0t {
  fill: var(--svg-color--87014d, #87014D);
  d: path("M16 13.687c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.13-.06-.279-.198-.209a3 3 0 0 1-1.385.329");
}

.l1kqit9sq {
  stop-color: var(--svg-color--f1c299, #F1C299);
  stop-opacity: 0;
}

.l2u0pibnj {
  stop-color: var(--svg-color--8a5453, #8A5453);
}

.l3hsrn8ob {
  stop-color: var(--svg-color--efc097, #EFC097);
  stop-opacity: 0;
}

.l5lubve6n {
  stop-color: var(--svg-color--e1a991, #E1A991);
  stop-opacity: 0;
}

.lcblgbkky {
  d: path("M20.955 10.633c.7-.994 1.823-1.7 2.297-1.93c-.407 1.25-1.157 2.75-1.618 2.992a.55.55 0 0 1-.734-.18z");
}

.ler-mrb8r {
  stop-color: var(--svg-color--e3b59c, #E3B59C);
  stop-opacity: 0;
}

.lgj7dyo1j {
  stop-color: var(--svg-color--dec492, #DEC492);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj7znd7rs {
  stop-color: var(--svg-color--e2bb85, #E2BB85);
  stop-opacity: 0;
}

.luxz9w7iu {
  stop-color: var(--svg-color--fffec0, #FFFEC0);
  stop-opacity: 0;
}

.ly3r7ebiq {
  stop-color: var(--svg-color--f6d09d, #F6D09D);
  stop-opacity: 0;
}

.m2zebkb3b {
  stop-color: var(--svg-color--bda75e, #BDA75E);
}

.mnbvi-beq {
  d: path("M8.85 5.65a.53.53 0 0 1 .529-.53h13.18a.53.53 0 0 1 0 1.06H9.378a.53.53 0 0 1-.53-.53");
}

.mntu2074k {
  stop-color: var(--svg-color--e9c090, #E9C090);
  stop-opacity: 0;
}

.mxgskb25j {
  stop-color: var(--svg-color--79b576, #79B576);
  stop-opacity: 0;
}

.n81djoa0z {
  stop-color: var(--svg-color--cfc9e2, #CFC9E2);
  stop-opacity: 0;
}

.n8iweabrd {
  stop-color: var(--svg-color--d39d90, #D39D90);
  stop-opacity: 0;
}

.nd_uzdbib {
  stop-color: var(--svg-color--7f4a45, #7F4A45);
}

.ne81pbb8b {
  fill: var(--svg-color--dca588, #DCA588);
  d: path("m15.618 10.075l-.532 1.839c-.109.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.nkujmsbyn {
  stop-color: var(--svg-color--bd7e76, #BD7E76);
}

.nld201kgm {
  stop-color: var(--svg-color--bd856f, #BD856F);
}

.nmpn19wzd {
  d: path("M12.12 14.601c-.82-.07-1.718.055-2.327 1.11c-.61.96-.793 3.255 1.914 4.5c1.443.663 3.695.898 4.293.898c.633 0 2.85-.235 4.293-.898c2.707-1.245 2.523-3.54 1.914-4.5c-.61-1.055-1.508-1.18-2.328-1.11l-3.88.14z");
}

.nr_-dacny {
  stop-color: var(--svg-color--a29b98, #A29B98);
  stop-opacity: 0;
}

.nrfhyjbig {
  stop-color: var(--svg-color--4b8866, #4B8866);
  stop-opacity: 0;
}

.nstnghbkd {
  stop-color: var(--svg-color--975a60, #975A60);
  stop-opacity: 0;
}

.nt3ohmb5v {
  stop-color: var(--svg-color--7f452e, #7F452E);
}

.nuy6hm44h {
  stop-color: var(--svg-color--ca9480, #CA9480);
  stop-opacity: 0;
}

.nvp34342a {
  stop-color: var(--svg-color--ebd396, #EBD396);
}

.o20k0cbhd {
  stop-color: var(--svg-color--b87f6a, #B87F6A);
  stop-opacity: 0;
}

.o5xzi4bgi {
  stop-color: var(--svg-color--fffcc0, #FFFCC0);
}

.o72-b5bhn {
  fill: var(--svg-color--e3b293, #E3B293);
  d: path("M23.237 7.754a6.6 6.6 0 0 0-2.474 1.726l-.52 3.024c.357.052 1.372.609 2.634-1.203a10.7 10.7 0 0 0 1.21-2.751c.152-.536-.332-1.001-.85-.796");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ol2rfkycm {
  stop-color: var(--svg-color--7d422e, #7D422E);
}

.oshqjyb1k {
  d: path("M15.988 21.07c.264.221.79.924.79 1.907c0 1.052-.358 1.646-.701 2.06a.115.115 0 0 1-.178 0c-.343-.414-.702-1.008-.702-2.06c0-.983.528-1.686.791-1.907");
}

.p1udt06bx {
  stroke: var(--svg-color--8c6037, #8C6037);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.46 8.054c-.195-.136-.84-.472-1.719-.375");
}

.p3j2vhgti {
  fill: var(--svg-color--d8a585, #D8A585);
  d: path("M8.381 12.702c.735-.625 1.279-1.255 1.368-1.594h4.234v3.282l-3.313 3.328c-2.469-.082-3.322-1.084-3.586-2.024c-.359-1.28.188-2.109 1.297-2.992");
}

.p3zz4kb9j {
  fill: var(--svg-color--93d756, #93D756);
  d: path("M23.088 18.28a10.9 10.9 0 0 1 3.84 8.318v3.319h-3.84z");
}

.p59cvi4fc {
  stop-color: var(--svg-color--a29b98, #A29B98);
}

.p8z5r2h1v {
  stop-color: var(--svg-color--8a575a, #8A575A);
}

.pc9y3hbhd {
  stop-color: var(--svg-color--6e4641, #6E4641);
  stop-opacity: 0;
}

.pgua_xb8h {
  d: path("M8.381 12.702c.735-.625 1.279-1.255 1.368-1.594h4.234v3.282l-3.313 3.328c-2.469-.082-3.322-1.084-3.586-2.024c-.359-1.28.188-2.109 1.297-2.992");
}

.pkb7vsbwf {
  d: path("M13.816 9.396a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px6vm6bxx {
  stop-color: var(--svg-color--b17160, #B17160);
}

.q439j4sbs {
  stop-color: var(--svg-color--dea692, #DEA692);
}

.q52fr3noq {
  stop-color: var(--svg-color--d59f87, #D59F87);
}

.q6_fzs7-r {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.29c0-.285.227-.512.51-.512a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.q8p3q3bqx {
  stop-color: var(--svg-color--be856f, #BE856F);
}

.q96xbxbcl {
  stop-color: var(--svg-color--deaf94, #DEAF94);
}

.qd6na2-uz {
  stop-color: var(--svg-color--b1736a, #B1736A);
}

.qfs6aobhn {
  stop-color: var(--svg-color--a85d71, #A85D71);
  stop-opacity: 0;
}

.qfx4f-mat {
  stop-color: var(--svg-color--fff9be, #FFF9BE);
}

.qhrgfk8ap {
  stop-color: var(--svg-color--e6ca98, #E6CA98);
}

.qjga9kbjc {
  stop-color: var(--svg-color--cdc7e1, #CDC7E1);
}

.ql3irgbnp {
  d: path("M14.631 10.184c0-.288-.234-.48-.298-.538l-.288.278l.177.362z");
}

.qt8zeccfx {
  stop-color: var(--svg-color--92465c, #92465C);
}

.qtvun2a2x {
  d: path("M21.744 6.625c-.056.825-.357 1.25-.5 1.359c.023-.221-.092-.67-.336-.977a1.01 1.01 0 0 0-.784-.382h-1.247c-.945 0-2.008-.141-2.672-1.086s-.39-1.883 0-2.297a1.174 1.174 0 0 1 1.656-.047c.531.492.961.414 2.094.89s1.86 1.508 1.789 2.54");
}

.qvn0k1bbh {
  stop-color: var(--svg-color--cf8e80, #CF8E80);
}

.qxnakxbrg {
  stop-color: var(--svg-color--795646, #795646);
}

.r-p883bfh {
  stop-color: var(--svg-color--e3b482, #E3B482);
}

.r-ruyz2yf {
  stop-color: var(--svg-color--71ab75, #71AB75);
  stop-opacity: 0;
}

.r0z1khbsa {
  stop-color: var(--svg-color--fffec0, #FFFEC0);
}

.r19r51k_n {
  stop-color: var(--svg-color--3e190e, #3E190E);
}

.r3bbexlfa {
  d: path("M18.184 9.397a.893.893 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
}

.rbi44vm-m {
  stop-color: var(--svg-color--a85d71, #A85D71);
}

.rkzp1hbvm {
  stop-color: var(--svg-color--6fe9ff, #6FE9FF);
}

.rnooggajo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 9.125c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.ro__zqilq {
  stop-color: var(--svg-color--fdc49d, #FDC49D);
}

.ro5kwtkrd {
  stop-color: var(--svg-color--824d4f, #824D4F);
  stop-opacity: 0;
}

.s0u10ejgs {
  stop-color: var(--svg-color--d09a83, #D09A83);
}

.s1uyvobna {
  d: path("M11.045 10.633c-.7-.994-1.823-1.7-2.297-1.93c.406 1.25 1.156 2.75 1.617 2.992a.55.55 0 0 0 .735-.18z");
}

.sb4dv46vs {
  stop-color: var(--svg-color--512429, #512429);
}

.sd49k712l {
  stop-color: var(--svg-color--d5a184, #D5A184);
}

.sfwupzbpl {
  stop-color: var(--svg-color--ce9578, #CE9578);
  stop-opacity: 0;
}

.si20u1b5q {
  stop-color: var(--svg-color--b67760, #B67760);
}

.sl7vf6bvq {
  stop-color: var(--svg-color--b99c5f, #B99C5F);
}

.smbbml-bd {
  stop-color: var(--svg-color--bd8d6a, #BD8D6A);
}

.sx3rjlbzk {
  stop-color: var(--svg-color--d4a287, #D4A287);
}

.syfl0-b7z {
  stop-color: var(--svg-color--88c975, #88C975);
  stop-opacity: 0;
}

.syu7jn24l {
  stop-color: var(--svg-color--b1736a, #B1736A);
  stop-opacity: 0;
}

.t0ficfbbx {
  stop-color: var(--svg-color--ffedb6, #FFEDB6);
  stop-opacity: 0;
}

.t219k_b_a {
  stop-color: var(--svg-color--4b8866, #4B8866);
}

.t2ybzjp2q {
  stop-color: var(--svg-color--99da64, #99DA64);
}

.t60ntu-wj {
  stop-color: var(--svg-color--b47d69, #B47D69);
}

.t6oix3hhn {
  stroke: var(--svg-color--eab99c, #EAB99C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M20.848 9.992c.383-.547 1.589-1.45 2.851-2");
}

.tdz80xyrh {
  fill: var(--svg-color--ffcfa1, #FFCFA1);
  d: path("M23.879 12.898c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.282l3.313 3.328c2.469-.082 3.322-1.085 3.585-2.024c.36-1.28-.187-2.109-1.296-2.992");
}

.thpmep7jb {
  stop-color: var(--svg-color--945740, #945740);
  stop-opacity: 0;
}

.tp-3hccxn {
  stop-color: var(--svg-color--9777b8, #9777B8);
  stop-opacity: 0;
}

.tp-a8qw8b {
  cx: 13.547px;
  cy: 9.778px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.tvz40gbou {
  stop-color: var(--svg-color--be8471, #BE8471);
  stop-opacity: 0;
}

.txq_035kl {
  fill: var(--svg-color--7cb04b, #7CB04B);
  d: path("M5.071 26.599c0-6.036 4.893-10.93 10.929-10.93s10.929 4.894 10.929 10.93v3.318H5.07z");
}

.u4rwp_bwq {
  stop-color: var(--svg-color--639d6c, #639D6C);
  stop-opacity: 0;
}

.ucz1v1bss {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.289a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.ui8xaew_b {
  stop-color: var(--svg-color--fee9b4, #FEE9B4);
}

.ulf-7gbex {
  d: path("m10.967 12.976l-.306-5.874c.58-.709 2.468-2.126 5.37-2.126s4.674 1.417 5.213 2.126l-.267 5.887c-.005.446-.219 1.552-.86 2.42c-.8 1.087-2.218 1.579-4.165 1.579s-3.34-.508-4.141-1.594c-.64-.869-.839-1.972-.844-2.418");
}

.uvyahya6g {
  stop-color: var(--svg-color--c28475, #C28475);
  stop-opacity: 0;
}

.v8wnikn7p {
  d: path("m15.719 20.23l-2.871-4.066h6.265L16.25 20.23c-.164.215-.395.2-.531 0");
}

.vgv3oz8qv {
  stop-color: var(--svg-color--cb997a, #CB997A);
  stop-opacity: 0;
}

.vhxxajp3a {
  stop-color: var(--svg-color--6e4641, #6E4641);
}

.vs6qzmbeh {
  stop-color: var(--svg-color--c4897d, #C4897D);
  stop-opacity: 0;
}

.vsbibr_ed {
  stop-color: var(--svg-color--ffffc5, #FFFFC5);
}

.vtamvdyqj {
  stop-color: var(--svg-color--c28475, #C28475);
}

.w_rnmcxom {
  stop-color: var(--svg-color--c6907d, #C6907D);
}

.w1ahfsiui {
  stop-color: var(--svg-color--ffedb6, #FFEDB6);
}

.w42gypbga {
  stop-color: var(--svg-color--d39d90, #D39D90);
}

.w5vn6kb5o {
  d: path("M15.906 3.622a.103.103 0 0 1 .144 0c.269.257.694.871.694 1.702c0 .974-.346 1.524-.679 1.907a.115.115 0 0 1-.174 0c-.332-.383-.678-.933-.678-1.907c0-.83.425-1.445.693-1.702");
}

.wdde7fbgs {
  stop-color: var(--svg-color--a7606b, #A7606B);
  stop-opacity: 0;
}

.wj_0ttb5q {
  d: path("M20.914 10.767c.849-1.205 2.226-1.99 2.801-2.267c-.25 1.656-1.219 3.117-1.992 3.617c-.424.274-.765-.11-.875-.28z");
}

.wjq_rgywi {
  stop-color: var(--svg-color--dec492, #DEC492);
  stop-opacity: 0;
}

.wodhbzf-c {
  stop-color: var(--svg-color--82b84c, #82B84C);
  stop-opacity: 0;
}

.wy3jcw9jp {
  stop-color: var(--svg-color--fff9be, #FFF9BE);
  stop-opacity: 0;
}

.wyqd5ab8k {
  stop-color: var(--svg-color--efc097, #EFC097);
}

.xid210bhr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.585c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.136.389-.05");
}

.xnfwhubut {
  stop-color: var(--svg-color--6f403b, #6F403B);
}

.xogtr7m2h {
  stop-color: var(--svg-color--dea68b, #DEA68B);
}

.yapr3et_m {
  stop-color: var(--svg-color--ab756a, #AB756A);
}

.yr_fudj4r {
  stop-color: var(--svg-color--e3b59c, #E3B59C);
}

.yr_s1wb-e {
  stop-color: var(--svg-color--f5c2a6, #F5C2A6);
  stop-opacity: 0;
}

.ytmccib4c {
  stop-color: var(--svg-color--b17859, #B17859);
}

.yx9tb8yxt {
  stop-color: var(--svg-color--6a3a22, #6A3A22);
}

.yy-0gacyg {
  stop-color: var(--svg-color--509652, #509652);
}

.yyik5z8lx {
  stop-color: var(--svg-color--949393, #949393);
  stop-opacity: 0;
}

.z5duhrbsp {
  stop-color: var(--svg-color--aba5ae, #ABA5AE);
}

.z5lko3bbf {
  stop-color: var(--svg-color--5a8d7c, #5A8D7C);
}

.z7q9w9nsq {
  fill: var(--svg-color--a16260, #A16260);
  d: path("M12.12 14.601c-.82-.07-1.718.055-2.327 1.11c-.61.96-.793 3.255 1.914 4.5c1.443.663 3.695.898 4.293.898c.633 0 2.85-.235 4.293-.898c2.707-1.245 2.523-3.54 1.914-4.5c-.61-1.055-1.508-1.18-2.328-1.11l-3.88.14z");
}

.zeavlp0uo {
  stop-color: var(--svg-color--edc595, #EDC595);
  stop-opacity: 0;
}

.zej61lbmf {
  stop-color: var(--svg-color--4d7c7e, #4D7C7E);
}

.zhcjv5uud {
  d: path("M18.118 9.585c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.136.389-.05");
}

.zjfb-u0iw {
  stop-color: var(--svg-color--74b04f, #74B04F);
  stop-opacity: 0;
}

.zmahyob7y {
  stop-color: var(--svg-color--ffffc5, #FFFFC5);
  stop-opacity: 0;
}

.zsyl6jyid {
  stop-color: var(--svg-color--c38e78, #C38E78);
  stop-opacity: 0;
}

</style>
