<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iq8xSUd)"><path class="h973enbaw"/><path fill="url(#ivJ7ZNc)" class="ct5ogkbju"/><path fill="url(#iSgOByc)" class="ct5ogkbju"/></g><path fill="url(#ifSpkXd)" class="ct5ogkbju"/><g filter="url(#in4opBe)"><path class="immvh4whf"/><path fill="url(#iXS2RWc)" class="pgua_xb8h"/><path fill="url(#iulZ1ob)" class="pgua_xb8h"/></g><path class="txq_035kl"/><path fill="url(#iQMnshd)" class="k98kmhbdx"/><path fill="url(#igkyYLe)" class="k98kmhbdx"/><path fill="url(#ivBqBmb)" class="k98kmhbdx"/><path class="gsenwumws"/><path fill="url(#iZFDHHd)" class="izxcq-l4x"/><path fill="url(#iJXV6Ub)" class="izxcq-l4x"/><path fill="url(#iQgUGRd)" class="izxcq-l4x"/><path class="p3zz4kb9j"/><path fill="url(#iwVhmFd)" class="e7_cr3bza"/><path fill="url(#iPOkLCc)" class="e7_cr3bza"/><path fill="url(#imhPERc)" class="e7_cr3bza"/><path fill="url(#iSVv4Vb)" class="kbs6vktjf"/><path fill="url(#izhbSZc)" class="kbs6vktjf"/><path fill="url(#iveVs0A)" class="kbs6vktjf"/><path fill="url(#i3RFzmd)" class="kbs6vktjf"/><path fill="url(#ijDoaLb)" class="kbs6vktjf"/><path fill="url(#iXxNf8b)" class="kbs6vktjf"/><g filter="url(#iFJbxec)"><path fill="url(#iZhDCUz)" class="hznm33ftf"/></g><g filter="url(#iLjywCe)"><path fill="url(#iMi7xEe)" class="oshqjyb1k"/></g><path class="z7q9w9nsq"/><path fill="url(#io2dINc)" class="nmpn19wzd"/><path fill="url(#iItREmH)" class="nmpn19wzd"/><path fill="url(#iCa76SL)" class="nmpn19wzd"/><path fill="url(#i3WYIMe)" class="nmpn19wzd"/><path fill="url(#iEruxub)" class="nmpn19wzd"/><path fill="url(#iIwqxUQ)" class="nmpn19wzd"/><path fill="url(#i5EInCc)" class="nmpn19wzd"/><path fill="url(#icC4Ejd)" class="nmpn19wzd"/><path fill="url(#iF40j6T)" class="v8wnikn7p"/><path fill="url(#i6JEaMb)" class="v8wnikn7p"/><path fill="url(#iCogxxd)" class="v8wnikn7p"/><path fill="url(#iIDulDc)" class="v8wnikn7p"/><g filter="url(#ip2foOb)"><path fill="url(#iKujW4b)" class="drrcjgbmp"/><path fill="url(#iejgeSd)" class="drrcjgbmp"/></g><path fill="url(#iWGzb1d)" class="s1uyvobna"/><path fill="url(#imdVY6l)" class="s1uyvobna"/><g filter="url(#iiMAe3d)"><path fill="url(#iH0QWJc)" class="heqvpu17r"/></g><g filter="url(#iKaDZiS)"><path fill="url(#ij6M1Kb)" class="lcblgbkky"/><path fill="url(#iyDd76b)" class="lcblgbkky"/></g><g filter="url(#iGOtc5b)"><path fill="url(#ic3bQke)" class="ulf-7gbex"/><path fill="url(#icQUsXc)" class="ulf-7gbex"/><path fill="url(#iJGjbCz)" class="ulf-7gbex"/><path fill="url(#iqm7dWa)" class="ulf-7gbex"/></g><path fill="url(#iUMNWKb)" class="guykq4bte"/><path fill="url(#i3AFYWc)" class="guykq4bte"/><path fill="url(#itik7Cb)" class="guykq4bte"/><path fill="url(#igSlHmd)" class="guykq4bte"/><path fill="url(#i1xdHdc)" class="guykq4bte"/><path fill="url(#iuL1bke)" class="guykq4bte"/><path fill="url(#ibmKK5c)" class="guykq4bte"/><g filter="url(#irjMYRd)"><path fill="url(#iNtEife)" class="nbwcfsb-j"/><path fill="url(#ipAiwlb)" class="nbwcfsb-j"/></g><g filter="url(#i9f8Uad)"><path fill="url(#iSaNr0c)" class="kdvyjshue"/><path fill="url(#iB5E05c)" class="kdvyjshue"/><path fill="url(#is8KBib)" class="kdvyjshue"/><path fill="url(#i7WDG9d)" class="kdvyjshue"/></g><path fill="url(#iSWw44C)" class="mnbvi-beq"/><path fill="url(#i4ZQGLb)" class="mnbvi-beq"/><path fill="url(#iZYe5Mb)" class="mnbvi-beq"/><path fill="url(#ipWMnUD)" class="mnbvi-beq"/><path fill="url(#idbYYpe)" class="mnbvi-beq"/><path fill="url(#iNjnfAc)" class="mnbvi-beq"/><path fill="url(#iD1FxLd)" class="w5vn6kb5o"/><path stroke="url(#i87xSac)" class="c4i1tcc7b"/><g filter="url(#iIZQHrd)"><path class="xe060db6l"/></g><path stroke="url(#iG8wtkc)" class="bok5f_uws"/><g filter="url(#iRUouDd)"><path class="cbe2o4bwl"/></g><g filter="url(#i3jhWEV)"><path class="qi2j78bfp"/></g><path fill="url(#ivFDWxc)" class="g1h1v_f7b"/><path fill="url(#iLj1jmI)" class="g1h1v_f7b"/><path fill="url(#i1GStmb)" class="g1h1v_f7b"/><path fill="url(#i4008Uo)" class="b3usjts4l"/><path class="dde1o5bku"/><path fill="url(#i0O8Yfb)" class="r3bbexlfa"/><path class="q6_fzs7-r"/><g filter="url(#ioagcAe)"><path class="xid210bhr"/><path fill="url(#idv22kN)" class="zhcjv5uud"/></g><g filter="url(#i82MABe)"><path fill="url(#i5Q6rbc)" class="bbvz2obwe"/></g><path class="rnooggajo"/><path fill="url(#iVXvR2c)" class="i9vyxwwtv"/><path class="xqyb4dz9z"/><g filter="url(#iogZcud)"><path fill="url(#isi63hb)" class="ql3irgbnp"/></g><g filter="url(#i40Lgcd)"><ellipse transform="rotate(-27.914 13.547 9.778)" class="tp-a8qw8b"/><ellipse fill="url(#iyTjOAc)" transform="rotate(-27.914 13.547 9.778)" class="h6gt32ejx"/></g><g filter="url(#il1YYSb)"><path stroke="url(#iytDscd)" class="jz3fl9fna"/></g><defs><radialGradient id="ivJ7ZNc" cx="0" cy="0" r="1" gradientTransform="rotate(119.999 8.422 12.784)scale(3.50014 9.06684)" gradientUnits="userSpaceOnUse"><stop class="jtnx86cjw"/><stop offset="1" class="ekl-imb0v"/></radialGradient><radialGradient id="iSgOByc" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 -.625 1.0554 3.06064 20.142 14.945)" gradientUnits="userSpaceOnUse"><stop class="yap4pcbws"/><stop offset="1" class="b0havcbgv"/></radialGradient><radialGradient id="ifSpkXd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.289 25.201 -8.557)scale(1.9436 3.02274)" gradientUnits="userSpaceOnUse"><stop class="vbafl_bri"/><stop offset="1" class="y2kfzpo0k"/></radialGradient><radialGradient id="iXS2RWc" cx="0" cy="0" r="1" gradientTransform="rotate(-98.799 12.467 4.558)scale(3.20061 3.97853)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="qt-7gebrh"/><stop offset="1" class="yrqvbcbjq"/></radialGradient><radialGradient id="iulZ1ob" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39063 .57888 -1.52227 -6.28657 12.111 14.413)" gradientUnits="userSpaceOnUse"><stop class="qdirajb4s"/><stop offset="1" class="shrn50bww"/></radialGradient><radialGradient id="igkyYLe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -11.6596 23.142 20.664)" gradientUnits="userSpaceOnUse"><stop class="t2ybzjp2q"/><stop offset="1" class="wodhbzf-c"/></radialGradient><radialGradient id="ivBqBmb" cx="0" cy="0" r="1" gradientTransform="rotate(-110.347 20.47 5.173)scale(3.59496 4.80694)" gradientUnits="userSpaceOnUse"><stop class="i1lv4bpfj"/><stop offset="1" class="mxgskb25j"/></radialGradient><radialGradient id="iZFDHHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.59707 0 0 -12.1778 9.033 29.916)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="t219k_b_a"/><stop offset="1" class="nrfhyjbig"/></radialGradient><radialGradient id="iJXV6Ub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69302 6.8777 -1.92029 -.4727 6.992 23.039)" gradientUnits="userSpaceOnUse"><stop class="a3tgwzvkw"/><stop offset="1" class="zjfb-u0iw"/></radialGradient><radialGradient id="iwVhmFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -10.40629 1.71323 -.26753 25.58 28.351)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="em6jl46va"/><stop offset="1" class="syfl0-b7z"/></radialGradient><radialGradient id="imhPERc" cx="0" cy="0" r="1" gradientTransform="matrix(.49206 0 0 10.875 23.088 26.445)" gradientUnits="userSpaceOnUse"><stop class="yy-0gacyg"/><stop offset="1" class="d07-_rbjf"/></radialGradient><radialGradient id="izhbSZc" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 -2.65624 14.81119 11.32622 15.736 29.758)" gradientUnits="userSpaceOnUse"><stop class="rbi44vm-m"/><stop offset="1" class="qfs6aobhn"/></radialGradient><radialGradient id="iveVs0A" cx="0" cy="0" r="1" gradientTransform="rotate(-132.42 17.243 11.363)scale(18.1601 26.3733)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="pc9y3hbhd"/><stop offset="1" class="vhxxajp3a"/></radialGradient><radialGradient id="i3RFzmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.53125 -8.40625 0 15.986 18.133)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="sb4dv46vs"/><stop offset="1" class="ro5kwtkrd"/></radialGradient><radialGradient id="iZhDCUz" cx="0" cy="0" r="1" gradientTransform="rotate(97.64 -1.617 18.109)scale(3.08805 1.1998)" gradientUnits="userSpaceOnUse"><stop class="xnfwhubut"/><stop offset="1" class="nd_uzdbib"/></radialGradient><radialGradient id="iMi7xEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.63279 -.8125 0 16.517 22.508)" gradientUnits="userSpaceOnUse"><stop class="o5xzi4bgi"/><stop offset="1" class="ui8xaew_b"/></radialGradient><radialGradient id="io2dINc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.82031 -7.8263 0 16 16.289)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="wdde7fbgs"/><stop offset="1" class="qt8zeccfx"/></radialGradient><radialGradient id="iItREmH" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 3.875 -2.05328 1.25846 8.83 16.101)" gradientUnits="userSpaceOnUse"><stop class="fg4eg_4fj"/><stop offset="1" class="eul_yij3i"/></radialGradient><radialGradient id="iCa76SL" cx="0" cy="0" r="1" gradientTransform="rotate(57.322 -7.396 18.171)scale(4.91974 4.45192)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="etr4yvr5e"/><stop offset="1" class="b37sysbpy"/></radialGradient><radialGradient id="i3WYIMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.78127 3.28124 -2.8026 1.52144 12.924 15.133)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="r19r51k_n"/><stop offset="1" class="ah36gjjbi"/></radialGradient><radialGradient id="iEruxub" cx="0" cy="0" r="1" gradientTransform="matrix(1.50686 .88968 -2.07086 3.50742 18.196 16.957)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="ol2rfkycm"/><stop offset="1" class="thpmep7jb"/></radialGradient><radialGradient id="iIwqxUQ" cx="0" cy="0" r="1" gradientTransform="rotate(104.647 4.863 15.397)scale(4.14235 9.13048)" gradientUnits="userSpaceOnUse"><stop class="irx6jyb5l"/><stop offset="1" class="jaugt_k_p"/></radialGradient><radialGradient id="i5EInCc" cx="0" cy="0" r="1" gradientTransform="rotate(36.076 -15.3 37.145)scale(.67663 1.97401)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="yx9tb8yxt"/><stop offset="1" class="gy5_zq-5b"/></radialGradient><radialGradient id="icC4Ejd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.7235 2.96875 -1.22621 -1.12492 22.585 15.976)" gradientUnits="userSpaceOnUse"><stop class="yapr3et_m"/><stop offset="1" class="ht8m2nb0n"/></radialGradient><radialGradient id="iF40j6T" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 -4.22173 3.11001 1.6575 16.142 20.386)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="i7oblybhw"/><stop offset="1" class="rok34m6gz"/></radialGradient><radialGradient id="i6JEaMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.4375 -2.83801 0 15.98 16.476)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="qmv7febfe"/><stop offset="1" class="djyn_9bez"/></radialGradient><radialGradient id="iCogxxd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3573 2.11087 -1.5527 1.73398 12.848 16.164)" gradientUnits="userSpaceOnUse"><stop class="zwki0uz6l"/><stop offset="1" class="zp4ekubcs"/></radialGradient><radialGradient id="iKujW4b" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -1.59462 3.4012 3.06607 8.861 10.165)" gradientUnits="userSpaceOnUse"><stop class="fgp762gdr"/><stop offset="1" class="e4garxz9p"/></radialGradient><radialGradient id="iejgeSd" cx="0" cy="0" r="1" gradientTransform="rotate(72.147 -.353 10.026)scale(5.60612 3.91608)" gradientUnits="userSpaceOnUse"><stop offset=".707" class="i2gy70vof"/><stop offset="1" class="uqzcd-flf"/></radialGradient><radialGradient id="iWGzb1d" cx="0" cy="0" r="1" gradientTransform="rotate(-137.265 7.499 3.484)scale(2.57883 1.75313)" gradientUnits="userSpaceOnUse"><stop class="tdmcedchx"/><stop offset="1" class="sv77bgb6j"/></radialGradient><radialGradient id="imdVY6l" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -1.01563 3.53448 3.04507 9.533 10.788)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="ob_nqzbct"/><stop offset="1" class="ut_l7ccde"/></radialGradient><radialGradient id="ij6M1Kb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6173 -4.10938 2.69336 1.71543 20.9 11.976)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="r7mg8accg"/><stop offset=".774" class="y4t-2eloy"/></radialGradient><radialGradient id="iyDd76b" cx="0" cy="0" r="1" gradientTransform="rotate(-134.182 13.603 .572)scale(1.54695 5.39782)" gradientUnits="userSpaceOnUse"><stop offset=".654" class="khqd-3jrz"/><stop offset="1" class="g38u58vho"/></radialGradient><radialGradient id="ic3bQke" cx="0" cy="0" r="1" gradientTransform="matrix(-7.96875 0 0 -11.4121 19.486 10.982)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="oeidq_bki"/><stop offset=".659" class="syzgjtqxh"/></radialGradient><radialGradient id="icQUsXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.25 17.4712 0 15.952 17.195)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="yzkn1bchk"/><stop offset="1" class="zitiw5rxg"/></radialGradient><radialGradient id="iJGjbCz" cx="0" cy="0" r="1" gradientTransform="rotate(-118.301 9.737 .613)scale(1.3842 1.4285)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="pzudnq9en"/><stop offset="1" class="dt5jht-1m"/></radialGradient><radialGradient id="iqm7dWa" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.375 1.85937 0 18.33 9.351)" gradientUnits="userSpaceOnUse"><stop class="ks6f0dchu"/><stop offset="1" class="h1j9vubqx"/></radialGradient><radialGradient id="iUMNWKb" cx="0" cy="0" r="1" gradientTransform="rotate(120.719 8.287 6.685)scale(5.01638 9.45422)" gradientUnits="userSpaceOnUse"><stop class="ixfcvkblz"/><stop offset="1" class="u2pz5bchd"/></radialGradient><radialGradient id="itik7Cb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 2.03125 -5.2664 2.67372 11.455 2.914)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="une5ndbsc"/><stop offset="1" class="k21m79bgi"/></radialGradient><radialGradient id="igSlHmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.85937 1.53125 -1.07705 -.60446 16.642 1.93)" gradientUnits="userSpaceOnUse"><stop class="fkflu6bxj"/><stop offset="1" class="n-jtbfbli"/></radialGradient><radialGradient id="i1xdHdc" cx="0" cy="0" r="1" gradientTransform="rotate(68.767 6.876 19.687)scale(2.63178 1.51534)" gradientUnits="userSpaceOnUse"><stop class="p3mcnub9l"/><stop offset="1" class="p_ux08e0x"/></radialGradient><radialGradient id="iuL1bke" cx="0" cy="0" r="1" gradientTransform="matrix(.39844 -.7012 2.2432 1.27463 10.384 9.092)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="zs_-_cb2d"/><stop offset="1" class="v-urz5mya"/></radialGradient><radialGradient id="ibmKK5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.05469 -.3809 2.48031 -.35612 21.392 9.092)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="mut2hmbec"/><stop offset="1" class="ilsblivcy"/></radialGradient><radialGradient id="ipAiwlb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 1.12501 -.77584 -2.8878 15.674 3.789)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="z0ws-qb1v"/><stop offset="1" class="am-5v2bda"/></radialGradient><radialGradient id="iSaNr0c" cx="0" cy="0" r="1" gradientTransform="matrix(3.63293 .1875 -.10596 2.05309 18.822 4.664)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="v4w9h7zfb"/><stop offset="1" class="dfxxqjb9s"/></radialGradient><radialGradient id="iB5E05c" cx="0" cy="0" r="1" gradientTransform="matrix(.1961 -1 5.5176 1.08203 18.58 6.633)" gradientUnits="userSpaceOnUse"><stop class="s9sz_kbag"/><stop offset="1" class="v1c42bcjn"/></radialGradient><radialGradient id="is8KBib" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 -1.9375 1.26715 .03066 16.08 4.898)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="l7acxcbhb"/><stop offset="1" class="ewkqpc7px"/></radialGradient><radialGradient id="i7WDG9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.08594 .27344 -2.62427 -.82476 19.47 3.805)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="mlwsi7b0o"/><stop offset="1" class="qpwa8cjbe"/></radialGradient><radialGradient id="ipWMnUD" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 0 0 -.60938 21.767 5.476)" gradientUnits="userSpaceOnUse"><stop class="ekarirbxr"/><stop offset="1" class="n81djoa0z"/></radialGradient><radialGradient id="idbYYpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .54688 -8.71875 0 11.174 4.945)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="b4qr-wvfv"/><stop offset="1" class="yyik5z8lx"/></radialGradient><radialGradient id="iNjnfAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92969 -.45312 0 15.228 5.164)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="h6i96qjvc"/><stop offset="1" class="d31bklhyx"/></radialGradient><radialGradient id="iD1FxLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.90625 2.05457 0 15.978 6.742)" gradientUnits="userSpaceOnUse"><stop class="rkzp1hbvm"/><stop offset="1" class="j5zu11bke"/></radialGradient><radialGradient id="ivFDWxc" cx="0" cy="0" r="1" gradientTransform="rotate(99.52 3.571 12.306)scale(2.55075 1.27331)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="k95c37b9n"/><stop offset="1" class="dktn-eyat"/></radialGradient><radialGradient id="iLj1jmI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17125 -3.82813 2.0415 -.62461 16.939 12.054)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="oazbv9bpw"/><stop offset="1" class="f2qr7p2wj"/></radialGradient><radialGradient id="i1GStmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.69356 2.60937 0 16.08 12.67)" gradientUnits="userSpaceOnUse"><stop class="bzexinb3r"/><stop offset="1" class="xeiq0eb6n"/></radialGradient><radialGradient id="i4008Uo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16 14.33)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i0O8Yfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6777 .87332 -.95908 -.74426 18.43 9.96)" gradientUnits="userSpaceOnUse"><stop class="qxnakxbrg"/><stop offset="1" class="egerxebfb"/></radialGradient><radialGradient id="idv22kN" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.415 .583)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVXvR2c" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 4.594 8.425)scale(1.10548 1.21404)" gradientUnits="userSpaceOnUse"><stop class="qxnakxbrg"/><stop offset="1" class="egerxebfb"/></radialGradient><radialGradient id="iyTjOAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.531 10.093)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iQMnshd" x1="15.049" x2="15.049" y1="29.917" y2="20.508" gradientUnits="userSpaceOnUse"><stop class="zej61lbmf"/><stop offset="1" class="dsw94cbmu"/></linearGradient><linearGradient id="iQgUGRd" x1="8.912" x2="8.912" y1="29.916" y2="21.101" gradientUnits="userSpaceOnUse"><stop class="ce9e8ebsk"/><stop offset="1" class="u4rwp_bwq"/></linearGradient><linearGradient id="iPOkLCc" x1="24.142" x2="26.611" y1="29.289" y2="21.383" gradientUnits="userSpaceOnUse"><stop offset=".116" class="z5lko3bbf"/><stop offset="1" class="r-ruyz2yf"/></linearGradient><linearGradient id="iSVv4Vb" x1="12.517" x2="22.705" y1="21.258" y2="30.914" gradientUnits="userSpaceOnUse"><stop class="l2u0pibnj"/><stop offset="1" class="nkujmsbyn"/></linearGradient><linearGradient id="ijDoaLb" x1="15.015" x2="15.229" y1="28.651" y2="28.447" gradientUnits="userSpaceOnUse"><stop class="p8z5r2h1v"/><stop offset="1" class="nstnghbkd"/></linearGradient><linearGradient id="iXxNf8b" x1="19.002" x2="18.65" y1="21.961" y2="22.32" gradientUnits="userSpaceOnUse"><stop class="i-kbbcb4w"/><stop offset="1" class="k1jzsjbfs"/></linearGradient><linearGradient id="iIDulDc" x1="17.642" x2="17.221" y1="18.57" y2="18.275" gradientUnits="userSpaceOnUse"><stop class="bwecofbbz"/><stop offset="1" class="u7o4p7sth"/></linearGradient><linearGradient id="iH0QWJc" x1="21.861" x2="23.486" y1="9.726" y2="11.57" gradientUnits="userSpaceOnUse"><stop class="gynotgbqh"/><stop offset="1" class="fidc7-bwj"/></linearGradient><linearGradient id="i3AFYWc" x1="13.767" x2="13.767" y1="9.476" y2="4.883" gradientUnits="userSpaceOnUse"><stop class="ki28lybwy"/><stop offset="1" class="oinsejbxo"/></linearGradient><linearGradient id="iNtEife" x1="12.299" x2="12.97" y1="6.508" y2="3.117" gradientUnits="userSpaceOnUse"><stop class="idiu_0eno"/><stop offset="1" class="mnbqkjntq"/></linearGradient><linearGradient id="iSWw44C" x1="15.58" x2="17.299" y1="5.65" y2="5.65" gradientUnits="userSpaceOnUse"><stop class="z5duhrbsp"/><stop offset="1" class="qjga9kbjc"/></linearGradient><linearGradient id="i4ZQGLb" x1="15.644" x2="15.644" y1="6.307" y2="5.65" gradientUnits="userSpaceOnUse"><stop class="i4sxbdchy"/><stop offset="1" class="gpxsxqdnb"/></linearGradient><linearGradient id="iZYe5Mb" x1="15.969" x2="15.969" y1="4.734" y2="5.32" gradientUnits="userSpaceOnUse"><stop class="p59cvi4fc"/><stop offset="1" class="nr_-dacny"/></linearGradient><linearGradient id="i87xSac" x1="14.33" x2="12.142" y1="7.662" y2="8.445" gradientUnits="userSpaceOnUse"><stop class="ew69nzbob"/><stop offset="1" class="bofwuipjx"/></linearGradient><linearGradient id="iG8wtkc" x1="18.111" x2="19.762" y1="7.662" y2="8.445" gradientUnits="userSpaceOnUse"><stop class="vfdhgn9sb"/><stop offset="1" class="v7_873tot"/></linearGradient><linearGradient id="i5Q6rbc" x1="18.96" x2="18.646" y1="9.928" y2="10.121" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isi63hb" x1="14.562" x2="14.248" y1="9.928" y2="10.121" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iytDscd" x1="15.861" x2="14.049" y1="20.476" y2="17.992" gradientUnits="userSpaceOnUse"><stop class="qd6na2-uz"/><stop offset="1" class="syu7jn24l"/></linearGradient><filter id="iq8xSUd" width="7.408" height="7.009" x="17.877" y="11.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.827451 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1360"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.807843 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1360" result="effect2_innerShadow_4002_1360"/></filter><filter id="in4opBe" width="7.258" height="6.609" x="6.975" y="11.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.552941 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1360"/></filter><filter id="iFJbxec" width="2.581" height="5.008" x="14.415" y="20.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".25"/></filter><filter id="iLjywCe" width="1.681" height="4.108" x="15.197" y="20.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1360"/></filter><filter id="ip2foOb" width="3.872" height="5.121" x="7.884" y="7.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.576471 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1360"/></filter><filter id="iiMAe3d" width="3.972" height="5.021" x="20.244" y="7.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.721569 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1360"/></filter><filter id="iKaDZiS" width="2.452" height="3.166" x="20.8" y="8.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.796078 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1360"/></filter><filter id="iGOtc5b" width="11.083" height="12.012" x="10.661" y="4.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.603922 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1360"/></filter><filter id="irjMYRd" width="6.417" height="5.694" x="9.906" y="2.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".125"/></filter><filter id="i9f8Uad" width="6.446" height="5.609" x="15.553" y="2.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".125"/></filter><filter id="iIZQHrd" width="2.169" height=".842" x="12.219" y="7.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".075"/></filter><filter id="iRUouDd" width="2.169" height=".842" x="17.516" y="7.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".075"/></filter><filter id="i3jhWEV" width="3.187" height="4.4" x="14.104" y="9.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".375"/></filter><filter id="ioagcAe" width=".787" height=".696" x="17.448" y="9.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".05"/></filter><filter id="i82MABe" width=".891" height=".913" x="18.287" y="9.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".1"/></filter><filter id="iogZcud" width=".986" height="1.04" x="13.845" y="9.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".1"/></filter><filter id="i40Lgcd" width=".913" height=".705" x="13.09" y="9.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".05"/></filter><filter id="il1YYSb" width="2.916" height="3.003" x="13.723" y="18.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1360" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-elf" /></template>
<style>
.a3tgwzvkw {
  stop-color: var(--svg-color--82bd6c, #82BD6C);
}

.ah36gjjbi {
  stop-color: var(--svg-color--814a40, #814A40);
  stop-opacity: 0;
}

.am-5v2bda {
  stop-color: var(--svg-color--ffa81c, #FFA81C);
  stop-opacity: 0;
}

.b0havcbgv {
  stop-color: var(--svg-color--dc8d16, #DC8D16);
  stop-opacity: 0;
}

.b37sysbpy {
  stop-color: var(--svg-color--77473a, #77473A);
  stop-opacity: 0;
}

.b3usjts4l {
  d: path("M16 13.687c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.13-.06-.279-.198-.209a3 3 0 0 1-1.385.329");
}

.b4qr-wvfv {
  stop-color: var(--svg-color--949393, #949393);
}

.bbvz2obwe {
  d: path("M18.979 10.172a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.bofwuipjx {
  stop-color: var(--svg-color--883f33, #883F33);
}

.bok5f_uws {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.46 8.054c-.195-.136-.84-.472-1.719-.375");
}

.bwecofbbz {
  stop-color: var(--svg-color--c98302, #C98302);
}

.bzexinb3r {
  stop-color: var(--svg-color--f99a36, #F99A36);
}

.c4i1tcc7b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.445 8.054c.195-.136.84-.472 1.718-.375");
}

.cbe2o4bwl {
  stroke: var(--svg-color--b66451, #B66451);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.46 8.054c-.195-.136-.84-.472-1.719-.375");
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

.dfxxqjb9s {
  stop-color: var(--svg-color--ffdf39, #FFDF39);
  stop-opacity: 0;
}

.djyn_9bez {
  stop-color: var(--svg-color--db7c10, #DB7C10);
  stop-opacity: 0;
}

.dktn-eyat {
  stop-color: var(--svg-color--f59a2d, #F59A2D);
}

.drrcjgbmp {
  d: path("M8.763 7.754a6.6 6.6 0 0 1 2.473 1.726l.52 3.024c-.356.052-1.371.609-2.633-1.203a10.7 10.7 0 0 1-1.21-2.751c-.152-.536.332-1.001.85-.796");
}

.dsw94cbmu {
  stop-color: var(--svg-color--659d70, #659D70);
  stop-opacity: 0;
}

.dt5jht-1m {
  stop-color: var(--svg-color--f39528, #F39528);
  stop-opacity: 0;
}

.e4garxz9p {
  stop-color: var(--svg-color--d58521, #D58521);
}

.e7_cr3bza {
  d: path("M23.088 18.28a10.9 10.9 0 0 1 3.84 8.318v3.319h-3.84z");
}

.egerxebfb {
  stop-color: var(--svg-color--694c3f, #694C3F);
}

.ekarirbxr {
  stop-color: var(--svg-color--ede5f4, #EDE5F4);
}

.ekl-imb0v {
  stop-color: var(--svg-color--ffc737, #FFC737);
  stop-opacity: 0;
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

.ew69nzbob {
  stop-color: var(--svg-color--a43e24, #A43E24);
}

.ewkqpc7px {
  stop-color: var(--svg-color--ffad15, #FFAD15);
  stop-opacity: 0;
}

.f2qr7p2wj {
  stop-color: var(--svg-color--ffbb28, #FFBB28);
  stop-opacity: 0;
}

.fg4eg_4fj {
  stop-color: var(--svg-color--9e6c66, #9E6C66);
}

.fgp762gdr {
  stop-color: var(--svg-color--dd9328, #DD9328);
}

.fidc7-bwj {
  stop-color: var(--svg-color--ffd03f, #FFD03F);
}

.fkflu6bxj {
  stop-color: var(--svg-color--e1b53f, #E1B53F);
}

.ft5dv1b6b {
  fill: none;
}

.g1h1v_f7b {
  d: path("m15.618 10.075l-.532 1.839c-.109.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.g38u58vho {
  stop-color: var(--svg-color--ecb624, #ECB624);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.gpxsxqdnb {
  stop-color: var(--svg-color--b688b9, #B688B9);
  stop-opacity: 0;
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

.gynotgbqh {
  stop-color: var(--svg-color--ffd948, #FFD948);
}

.h1j9vubqx {
  stop-color: var(--svg-color--ffbd27, #FFBD27);
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

.h973enbaw {
  fill: var(--svg-color--ffa52a, #FFA52A);
  d: path("M23.879 12.898c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.282l3.313 3.328c2.469-.082 3.322-1.085 3.585-2.024c.36-1.28-.187-2.109-1.296-2.992");
}

.heqvpu17r {
  d: path("M23.237 7.754a6.6 6.6 0 0 0-2.474 1.726l-.52 3.024c.357.052 1.372.609 2.634-1.203a10.7 10.7 0 0 0 1.21-2.751c.152-.536-.332-1.001-.85-.796");
}

.ht8m2nb0n {
  stop-color: var(--svg-color--a86b65, #A86B65);
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

.i2gy70vof {
  stop-color: var(--svg-color--c27b29, #C27B29);
  stop-opacity: 0;
}

.i4sxbdchy {
  stop-color: var(--svg-color--b688b9, #B688B9);
}

.i7oblybhw {
  stop-color: var(--svg-color--ffc026, #FFC026);
}

.i9vyxwwtv {
  d: path("M13.816 9.397a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.idiu_0eno {
  stop-color: var(--svg-color--df7e2b, #DF7E2B);
}

.ilsblivcy {
  stop-color: var(--svg-color--c47a03, #C47A03);
  stop-opacity: 0;
}

.immvh4whf {
  fill: var(--svg-color--e27925, #E27925);
  d: path("M8.381 12.702c.735-.625 1.279-1.255 1.368-1.594h4.234v3.282l-3.313 3.328c-2.469-.082-3.322-1.084-3.586-2.024c-.359-1.28.188-2.109 1.297-2.992");
}

.irx6jyb5l {
  stop-color: var(--svg-color--8e5034, #8E5034);
}

.ixfcvkblz {
  stop-color: var(--svg-color--ffde31, #FFDE31);
}

.izxcq-l4x {
  d: path("M8.912 18.28a10.9 10.9 0 0 0-3.84 8.318v3.319h3.84z");
}

.j5zu11bke {
  stop-color: var(--svg-color--c2ffff, #C2FFFF);
}

.jaugt_k_p {
  stop-color: var(--svg-color--8e5034, #8E5034);
  stop-opacity: 0;
}

.jtnx86cjw {
  stop-color: var(--svg-color--ffc737, #FFC737);
}

.jz3fl9fna {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.049 18.414L15.61 20.6c.12.125.428.3.703 0");
}

.k1jzsjbfs {
  stop-color: var(--svg-color--7f4b4c, #7F4B4C);
  stop-opacity: 0;
}

.k21m79bgi {
  stop-color: var(--svg-color--c69738, #C69738);
  stop-opacity: 0;
}

.k95c37b9n {
  stop-color: var(--svg-color--ffb926, #FFB926);
}

.k98kmhbdx {
  d: path("M5.071 26.599c0-6.036 4.893-10.93 10.929-10.93s10.929 4.894 10.929 10.93v3.318H5.07z");
}

.kbs6vktjf {
  d: path("M16.274 29.917L7.053 20.32a10.95 10.95 0 0 1 5.854-4.207L26.69 29.917z");
}

.kdvyjshue {
  d: path("M21.744 6.625c-.056.825-.357 1.25-.5 1.36c.023-.222-.092-.671-.336-.977a1.01 1.01 0 0 0-.784-.383h-1.247c-.945 0-2.008-.14-2.672-1.086c-.664-.945-.39-1.883 0-2.297a1.174 1.174 0 0 1 1.656-.047c.531.492.961.414 2.094.89s1.86 1.509 1.789 2.54");
}

.khqd-3jrz {
  stop-color: var(--svg-color--ecb624, #ECB624);
  stop-opacity: 0;
}

.ki28lybwy {
  stop-color: var(--svg-color--d37721, #D37721);
}

.ks6f0dchu {
  stop-color: var(--svg-color--ffbd27, #FFBD27);
}

.l2u0pibnj {
  stop-color: var(--svg-color--8a5453, #8A5453);
}

.l7acxcbhb {
  stop-color: var(--svg-color--ffad15, #FFAD15);
}

.lcblgbkky {
  d: path("M20.955 10.633c.7-.994 1.823-1.7 2.297-1.93c-.407 1.25-1.157 2.75-1.618 2.992a.55.55 0 0 1-.734-.18z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mlwsi7b0o {
  stop-color: var(--svg-color--ffd13d, #FFD13D);
}

.mnbqkjntq {
  stop-color: var(--svg-color--ffb91d, #FFB91D);
  stop-opacity: 0;
}

.mnbvi-beq {
  d: path("M8.85 5.65a.53.53 0 0 1 .529-.53h13.18a.53.53 0 0 1 0 1.06H9.378a.53.53 0 0 1-.53-.53");
}

.mut2hmbec {
  stop-color: var(--svg-color--c47a03, #C47A03);
}

.mxgskb25j {
  stop-color: var(--svg-color--79b576, #79B576);
  stop-opacity: 0;
}

.n-jtbfbli {
  stop-color: var(--svg-color--ffc21e, #FFC21E);
  stop-opacity: 0;
}

.n81djoa0z {
  stop-color: var(--svg-color--cfc9e2, #CFC9E2);
  stop-opacity: 0;
}

.nbwcfsb-j {
  d: path("M10.16 6.625c.057.825.292 1.336.435 1.445c-.023-.221.132-.67.375-.976c.244-.307.664-.464.883-.47c.076 0 .44-.023 1.196 0c1.484.048 1.937-.148 2.601-1.093s.44-1.875.05-2.289a1.174 1.174 0 0 0-1.657-.047c-.53.492-.96.414-2.093.89s-1.86 1.509-1.79 2.54");
}

.nd_uzdbib {
  stop-color: var(--svg-color--7f4a45, #7F4A45);
}

.nkujmsbyn {
  stop-color: var(--svg-color--bd7e76, #BD7E76);
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

.o5xzi4bgi {
  stop-color: var(--svg-color--fffcc0, #FFFCC0);
}

.oazbv9bpw {
  stop-color: var(--svg-color--ffde45, #FFDE45);
}

.ob_nqzbct {
  stop-color: var(--svg-color--c9842e, #C9842E);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oeidq_bki {
  stop-color: var(--svg-color--ffdf31, #FFDF31);
}

.oinsejbxo {
  stop-color: var(--svg-color--d37721, #D37721);
  stop-opacity: 0;
}

.ol2rfkycm {
  stop-color: var(--svg-color--7d422e, #7D422E);
}

.oshqjyb1k {
  d: path("M15.988 21.07c.264.221.79.924.79 1.907c0 1.052-.358 1.646-.701 2.06a.115.115 0 0 1-.178 0c-.343-.414-.702-1.008-.702-2.06c0-.983.528-1.686.791-1.907");
}

.p_ux08e0x {
  stop-color: var(--svg-color--f5a922, #F5A922);
  stop-opacity: 0;
}

.p3mcnub9l {
  stop-color: var(--svg-color--ffc930, #FFC930);
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

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pzudnq9en {
  stop-color: var(--svg-color--f39528, #F39528);
}

.q6_fzs7-r {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.29c0-.285.227-.512.51-.512a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.qd6na2-uz {
  stop-color: var(--svg-color--b1736a, #B1736A);
}

.qdirajb4s {
  stop-color: var(--svg-color--b25b0f, #B25B0F);
}

.qfs6aobhn {
  stop-color: var(--svg-color--a85d71, #A85D71);
  stop-opacity: 0;
}

.qi2j78bfp {
  fill: var(--svg-color--f89829, #F89829);
  d: path("m15.447 10.271l-.57 1.838c-.098.379.136.757.467.757h.707c.331 0 .565-.384.468-.757l-.478-1.838c-.102-.407-.487-.407-.594 0");
}

.qjga9kbjc {
  stop-color: var(--svg-color--cdc7e1, #CDC7E1);
}

.ql3irgbnp {
  d: path("M14.631 10.184c0-.288-.234-.48-.298-.538l-.288.278l.177.362z");
}

.qmv7febfe {
  stop-color: var(--svg-color--db7c10, #DB7C10);
}

.qpwa8cjbe {
  stop-color: var(--svg-color--ffd13d, #FFD13D);
  stop-opacity: 0;
}

.qt-7gebrh {
  stop-color: var(--svg-color--95772d, #95772D);
}

.qt8zeccfx {
  stop-color: var(--svg-color--92465c, #92465C);
}

.qxnakxbrg {
  stop-color: var(--svg-color--795646, #795646);
}

.r-ruyz2yf {
  stop-color: var(--svg-color--71ab75, #71AB75);
  stop-opacity: 0;
}

.r19r51k_n {
  stop-color: var(--svg-color--3e190e, #3E190E);
}

.r3bbexlfa {
  d: path("M18.184 9.397a.893.893 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
}

.r7mg8accg {
  stop-color: var(--svg-color--f3c137, #F3C137);
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

.ro5kwtkrd {
  stop-color: var(--svg-color--824d4f, #824D4F);
  stop-opacity: 0;
}

.rok34m6gz {
  stop-color: var(--svg-color--da8610, #DA8610);
}

.s1uyvobna {
  d: path("M11.045 10.633c-.7-.994-1.823-1.7-2.297-1.93c.406 1.25 1.156 2.75 1.617 2.992a.55.55 0 0 0 .735-.18z");
}

.s9sz_kbag {
  stop-color: var(--svg-color--e69029, #E69029);
}

.sb4dv46vs {
  stop-color: var(--svg-color--512429, #512429);
}

.shrn50bww {
  stop-color: var(--svg-color--e37a26, #E37A26);
  stop-opacity: 0;
}

.sv77bgb6j {
  stop-color: var(--svg-color--c4812e, #C4812E);
  stop-opacity: 0;
}

.syfl0-b7z {
  stop-color: var(--svg-color--88c975, #88C975);
  stop-opacity: 0;
}

.syu7jn24l {
  stop-color: var(--svg-color--b1736a, #B1736A);
  stop-opacity: 0;
}

.syzgjtqxh {
  stop-color: var(--svg-color--ffac2d, #FFAC2D);
}

.t219k_b_a {
  stop-color: var(--svg-color--4b8866, #4B8866);
}

.t2ybzjp2q {
  stop-color: var(--svg-color--99da64, #99DA64);
}

.tdmcedchx {
  stop-color: var(--svg-color--c4812e, #C4812E);
}

.thpmep7jb {
  stop-color: var(--svg-color--945740, #945740);
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

.txq_035kl {
  fill: var(--svg-color--7cb04b, #7CB04B);
  d: path("M5.071 26.599c0-6.036 4.893-10.93 10.929-10.93s10.929 4.894 10.929 10.93v3.318H5.07z");
}

.u2pz5bchd {
  stop-color: var(--svg-color--fea41d, #FEA41D);
}

.u4rwp_bwq {
  stop-color: var(--svg-color--639d6c, #639D6C);
  stop-opacity: 0;
}

.u7o4p7sth {
  stop-color: var(--svg-color--eca01b, #ECA01B);
  stop-opacity: 0;
}

.ui8xaew_b {
  stop-color: var(--svg-color--fee9b4, #FEE9B4);
}

.ulf-7gbex {
  d: path("m10.967 12.976l-.306-5.874c.58-.709 2.468-2.126 5.37-2.126s4.674 1.417 5.213 2.126l-.267 5.887c-.005.446-.219 1.552-.86 2.42c-.8 1.087-2.218 1.579-4.165 1.579s-3.34-.508-4.141-1.594c-.64-.869-.839-1.972-.844-2.418");
}

.une5ndbsc {
  stop-color: var(--svg-color--c69738, #C69738);
}

.uqzcd-flf {
  stop-color: var(--svg-color--c27b29, #C27B29);
}

.ut_l7ccde {
  stop-color: var(--svg-color--c9842e, #C9842E);
}

.v-urz5mya {
  stop-color: var(--svg-color--e28620, #E28620);
  stop-opacity: 0;
}

.v1c42bcjn {
  stop-color: var(--svg-color--e69029, #E69029);
  stop-opacity: 0;
}

.v4w9h7zfb {
  stop-color: var(--svg-color--ffdf39, #FFDF39);
}

.v7_873tot {
  stop-color: var(--svg-color--a23a1c, #A23A1C);
}

.v8wnikn7p {
  d: path("m15.719 20.23l-2.871-4.066h6.265L16.25 20.23c-.164.215-.395.2-.531 0");
}

.vbafl_bri {
  stop-color: var(--svg-color--957f2c, #957F2C);
}

.vfdhgn9sb {
  stop-color: var(--svg-color--b14526, #B14526);
}

.vhxxajp3a {
  stop-color: var(--svg-color--6e4641, #6E4641);
}

.w5vn6kb5o {
  d: path("M15.906 3.622a.103.103 0 0 1 .144 0c.269.257.694.871.694 1.702c0 .974-.346 1.524-.679 1.907a.115.115 0 0 1-.174 0c-.332-.383-.678-.933-.678-1.907c0-.83.425-1.445.693-1.702");
}

.wdde7fbgs {
  stop-color: var(--svg-color--a7606b, #A7606B);
  stop-opacity: 0;
}

.wodhbzf-c {
  stop-color: var(--svg-color--82b84c, #82B84C);
  stop-opacity: 0;
}

.xe060db6l {
  stroke: var(--svg-color--a54e3d, #A54E3D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.445 8.054c.195-.136.84-.472 1.718-.375");
}

.xeiq0eb6n {
  stop-color: var(--svg-color--f99a36, #F99A36);
  stop-opacity: 0;
}

.xid210bhr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.585c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.136.389-.05");
}

.xnfwhubut {
  stop-color: var(--svg-color--6f403b, #6F403B);
}

.xqyb4dz9z {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.29a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.y2kfzpo0k {
  stop-color: var(--svg-color--d9971b, #D9971B);
  stop-opacity: 0;
}

.y4t-2eloy {
  stop-color: var(--svg-color--f3c137, #F3C137);
  stop-opacity: 0;
}

.yap4pcbws {
  stop-color: var(--svg-color--dc8d16, #DC8D16);
}

.yapr3et_m {
  stop-color: var(--svg-color--ab756a, #AB756A);
}

.yrqvbcbjq {
  stop-color: var(--svg-color--dd7926, #DD7926);
  stop-opacity: 0;
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

.yzkn1bchk {
  stop-color: var(--svg-color--d87b20, #D87B20);
}

.z0ws-qb1v {
  stop-color: var(--svg-color--ffe033, #FFE033);
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

.zej61lbmf {
  stop-color: var(--svg-color--4d7c7e, #4D7C7E);
}

.zhcjv5uud {
  d: path("M18.118 9.585c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.136.389-.05");
}

.zitiw5rxg {
  stop-color: var(--svg-color--fa9d38, #FA9D38);
  stop-opacity: 0;
}

.zjfb-u0iw {
  stop-color: var(--svg-color--74b04f, #74B04F);
  stop-opacity: 0;
}

.zp4ekubcs {
  stop-color: var(--svg-color--aa5e01, #AA5E01);
  stop-opacity: 0;
}

.zs_-_cb2d {
  stop-color: var(--svg-color--9c4b05, #9C4B05);
}

.zwki0uz6l {
  stop-color: var(--svg-color--793b01, #793B01);
}

</style>
