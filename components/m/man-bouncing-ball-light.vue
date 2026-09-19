<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#i5n8p8J)" transform="rotate(26.961 19.37 13.476)" class="e2cbcwbro"/><g filter="url(#it4jkgc)"><path class="ib089svvj"/></g><circle fill="url(#inFRzLc)" class="pid-4m06y"/><circle fill="url(#ikT3wpb)" class="pid-4m06y"/><circle fill="url(#ipd3rHo)" class="pid-4m06y"/><circle fill="url(#ieUwNdb)" class="pid-4m06y"/><g filter="url(#i6pNaHe)"><path fill="url(#iPR2xGd)" class="nngzf3bsk"/></g><path fill="url(#ioRLLAb)" class="n5gdkvxgq"/><path fill="url(#ioQp9VT)" class="n5gdkvxgq"/><path fill="url(#i24w7He)" class="pb1u5rwut"/><path fill="url(#iGYZ1ue)" class="pb1u5rwut"/><g filter="url(#iKPtwJe)"><path fill="url(#iu5UMge)" class="cur1q0ipi"/><path fill="url(#iNRX4zb)" class="cur1q0ipi"/><path fill="url(#iQpddTg)" class="cur1q0ipi"/></g><g filter="url(#iRD5PVp)"><path fill="url(#iforYlw)" class="sq265sb-l"/><path fill="url(#i0WLFfR)" class="sq265sb-l"/></g><path fill="url(#i6cVORc)" class="cuqw36btj"/><path fill="url(#iR1A0Be)" class="cuqw36btj"/><path fill="url(#ivkbt6S)" class="i-cfc4c3e"/><path fill="url(#ioiTMCb)" class="i-cfc4c3e"/><path fill="url(#i5wZYne)" class="i-cfc4c3e"/><path fill="url(#igATwqb)" class="i-cfc4c3e"/><path class="efzf2zbap"/><path fill="url(#is0WZfd)" class="wg964l8xn"/><path fill="url(#iHTPxqd)" class="wg964l8xn"/><path fill="url(#iCnPime)" class="wg964l8xn"/><g filter="url(#ihcCnjd)"><path class="var-spbti"/><path fill="url(#icubEce)" class="f6rtlablh"/><path fill="url(#iHJmVvb)" class="f6rtlablh"/><path fill="url(#idjB8bc)" class="f6rtlablh"/></g><g filter="url(#iP9Ksmd)"><path fill="url(#iwuX1jb)" class="aaqnz91xn"/><path fill="url(#iAwSFJb)" class="aaqnz91xn"/></g><g filter="url(#ioPsaae)"><path fill="url(#iLp5Zne)" class="i80p6sbrk"/><path fill="url(#i1VySRd)" class="i80p6sbrk"/></g><g filter="url(#iEkFMqc)"><path fill="url(#ihcs1zb)" clip-rule="evenodd" class="v7a4roj-a"/></g><path class="oneud5b_v"/><path fill="url(#iL9XrIb)" class="saa1azb9d"/><path fill="url(#i9AfEjt)" class="saa1azb9d"/><path clip-rule="evenodd" class="s2_ykvr2e"/><path fill="url(#iM2hWad)" clip-rule="evenodd" class="mt922xxhp"/><path clip-rule="evenodd" class="t0aiwbcnw"/><path fill="url(#ih9IXdD)" clip-rule="evenodd" class="yljh9-iht"/><path clip-rule="evenodd" class="grt6kh0of"/><path fill="url(#i9wrtrc)" clip-rule="evenodd" class="z0yiw70fd"/><path clip-rule="evenodd" class="ymdcy-b7v"/><path fill="url(#ijZJgsc)" clip-rule="evenodd" class="aci9pts-i"/><path fill="url(#ibBTzqe)" clip-rule="evenodd" class="usu-mrb7g"/><g filter="url(#iOclphE)"><path fill="url(#iHOb1Sc)" class="wxv9r3nmp"/><path fill="url(#ipICnYc)" class="wxv9r3nmp"/></g><path fill="url(#i2a8zYc)" class="wxv9r3nmp"/><path fill="url(#izZMPMe)" clip-rule="evenodd" class="v7a4roj-a"/><g filter="url(#ifoEoPc)"><path class="ixfgd0bde"/></g><g filter="url(#iTtLMwq)"><path class="h5ok44qlk"/><path fill="url(#iOJ29Xd)" class="yo6ebkk5b"/></g><g filter="url(#ih4PhNc)"><circle fill="url(#i7hukJd)" class="mqtnlr-ha"/></g><g filter="url(#ifWnwob)"><circle fill="url(#ilLha3d)" class="m11d91bcs"/></g><g filter="url(#iYwVnZd)"><circle fill="url(#i6RlQbb)" class="cdh5ssw-h"/><circle fill="url(#i8q1mbd)" class="cdh5ssw-h"/></g><g filter="url(#iDHuZqP)"><circle class="dbltg25wr"/><circle fill="url(#ihlzLCb)" class="g5wehopug"/><circle fill="url(#ilAE14d)" class="g5wehopug"/></g><g filter="url(#inhUGQc)"><path fill="url(#io70Uoc)" class="o1x-hzk1z"/><path fill="url(#i8sjuDp)" class="o1x-hzk1z"/><path fill="url(#itrB6Jb)" class="o1x-hzk1z"/><path fill="url(#iJbClTd)" class="o1x-hzk1z"/><path fill="url(#iNuTfzc)" class="o1x-hzk1z"/><path fill="url(#iTpa3ld)" class="o1x-hzk1z"/></g><g filter="url(#ilALKJe)"><path fill="url(#iU5De8b)" class="r_uc2dbaa"/></g><g filter="url(#iQNUIDb)"><path class="al24rqb9g"/><path fill="url(#iFT8RNc)" class="leycomb-d"/><path fill="url(#iBDE5te)" class="leycomb-d"/><path fill="url(#ij4XRwd)" class="leycomb-d"/><path fill="url(#iFdwTfD)" class="leycomb-d"/></g><g filter="url(#iKOqz0n)"><path class="xvghccb-o"/></g><g filter="url(#iHVOFhe)"><path class="zpviw0bxc"/><path fill="url(#iC8dEQe)" class="weh1a1nwn"/><path fill="url(#iZuQd9c)" class="weh1a1nwn"/><path fill="url(#itV9u4d)" class="weh1a1nwn"/><path fill="url(#i7FU60K)" class="weh1a1nwn"/></g><path class="rrixx5x3p"/><g filter="url(#i1voEGb)"><path class="edqwx8bzo"/></g><g filter="url(#ihNE1Me)"><path class="qm_7gab-x"/></g><path class="z2pel1nsk"/><path fill="url(#imzRC7d)" class="r7sr9ubrw"/><path class="o0a60dbfj"/><g filter="url(#iBGJQBb)"><path class="e7237gbfo"/><path fill="url(#imfHVzd)" class="qhfjj5brh"/></g><g filter="url(#iGuIaad)"><path fill="url(#isv0eId)" class="jrm_lvjlx"/></g><path class="rlozrqb1t"/><path fill="url(#i9q6Yrd)" class="skv92hlmk"/><path class="e5ld9oxky"/><g filter="url(#iny7Hcb)"><path fill="url(#i8pf0Sd)" class="r-25bbbgc"/></g><g filter="url(#iUq9iJB)"><ellipse transform="rotate(-27.914 11.68 5.647)" class="v-vzhociv"/><ellipse fill="url(#iO95fMe)" transform="rotate(-27.914 11.68 5.647)" class="y_h4prb7b"/></g><g filter="url(#iaLB7qe)"><path stroke="url(#iXIiBkh)" class="o4zeo-ufr"/></g><g filter="url(#iNsKLSc)"><path stroke="url(#ivNknSb)" class="qum-1-bur"/></g><g filter="url(#iTL1eyd)"><path stroke="url(#iwFA7ve)" class="eq8t8ccrw"/></g><path fill="url(#ixnwXBb)" class="muc5wjuki"/><path fill="url(#iPM3I2b)" class="muc5wjuki"/><path fill="url(#iRjriHc)" class="muc5wjuki"/><path fill="url(#iABZ5Ej)" class="muc5wjuki"/><defs><radialGradient id="i5n8p8J" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.032)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="of6eoebwa"/><stop offset="1" class="hhvxh5bcs"/></radialGradient><radialGradient id="ikT3wpb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.336 18.368)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="ipd3rHo" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.547)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ieUwNdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.087)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="iPR2xGd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.845)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="ioRLLAb" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.118)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="btsp6rbtk"/><stop offset="1" class="qk70xkspj"/></radialGradient><radialGradient id="ioQp9VT" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.712)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="s515o6bjz"/><stop offset="1" class="mid6c9bnp"/></radialGradient><radialGradient id="iu5UMge" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.607)" gradientUnits="userSpaceOnUse"><stop class="vhhvj2t-s"/><stop offset="1" class="so34edl-m"/></radialGradient><radialGradient id="iNRX4zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.565)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="iQpddTg" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.855 22.55)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="i6cVORc" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.342 12.627)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="e085m5ymq"/><stop offset="1" class="c_xsycbdz"/></radialGradient><radialGradient id="ivkbt6S" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.53 12.33)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="i5wZYne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.171 18.117)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="igATwqb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.878 17.729)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="is0WZfd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.837)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="iHTPxqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.15)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iCnPime" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.759)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="icubEce" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.93)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="iHJmVvb" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.683 2.269)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="idjB8bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.853)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="iwuX1jb" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.544)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="xu1e5_bcz"/><stop offset="1" class="jixz69llq"/></radialGradient><radialGradient id="ihcs1zb" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -1.28125 .6632 1.76315 6.712 13.93)" gradientUnits="userSpaceOnUse"><stop class="lk1-k5bve"/><stop offset="1" class="biy3jzpmj"/></radialGradient><radialGradient id="iL9XrIb" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.056)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="w_rrm9a7q"/><stop offset="1" class="nkhjpg89n"/><stop offset="1" class="d7rccub7n"/></radialGradient><radialGradient id="i9AfEjt" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.941)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="oxnqswb1g"/><stop offset="1" class="ycl44mqxw"/></radialGradient><radialGradient id="iM2hWad" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.219 7.58)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="ih9IXdD" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .802 7.932)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="i9wrtrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.936)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="ijZJgsc" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.373)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="ibBTzqe" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.122 8.926)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="k_ltadprl"/><stop offset="1" class="tsvq44-rv"/></radialGradient><radialGradient id="iHOb1Sc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.486)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="uqxno_b8g"/><stop offset=".81" class="d4a71bwtp"/></radialGradient><radialGradient id="ipICnYc" cx="0" cy="0" r="1" gradientTransform="rotate(-104.504 15.36 1.222)scale(8.36833 2.71135)" gradientUnits="userSpaceOnUse"><stop class="g_v4sglua"/><stop offset="1" class="o67susxgp"/></radialGradient><radialGradient id="i2a8zYc" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.27 8.999)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="ip3ktqbqy"/><stop offset="1" class="whspc9bgn"/></radialGradient><radialGradient id="izZMPMe" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.228)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="yvgme-ued"/><stop offset="1" class="t405zhbew"/></radialGradient><radialGradient id="iOJ29Xd" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.25 -14.134)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><radialGradient id="i7hukJd" cx="0" cy="0" r="1" gradientTransform="matrix(.79446 0 0 1.39031 9.887 5.999)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="i8q1mbd" cx="0" cy="0" r="1" gradientTransform="matrix(.37426 -.27252 .31105 .42717 15.118 5.879)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="ihlzLCb" cx="0" cy="0" r="1" gradientTransform="matrix(.3718 -.68384 .40026 .21762 14.93 6.37)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="ilAE14d" cx="0" cy="0" r="1" gradientTransform="matrix(.11738 .1162 -.14979 .15132 14.95 5.999)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="i8sjuDp" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27152 -5.79836 0 12.805 5.127)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="p7jmmxb2h"/><stop offset="1" class="uzkpn5btf"/></radialGradient><radialGradient id="iNuTfzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59174 .7283 0 13.854 5.423)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iTpa3ld" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.62967 .78305 0 11.79 5.408)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iFT8RNc" cx="0" cy="0" r="1" gradientTransform="matrix(.36119 -1.33851 .49636 .13394 14.759 4.14)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iBDE5te" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -29.395 154.293)scale(1.73889 .93499)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ij4XRwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7602 -1.17732 0 12.792 2.105)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iFdwTfD" cx="0" cy="0" r="1" gradientTransform="matrix(1.39163 -1.01982 1.59772 2.18022 9.872 5.191)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="i7FU60K" cx="0" cy="0" r="1" gradientTransform="matrix(0 .08914 -.28639 0 12.94 6.726)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="imzRC7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36721 -.5841 0 13.778 5.69)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="imfHVzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10497 -.13527 .18623 -.14452 13.675 5.728)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9q6Yrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36723 -.58412 0 11.803 5.69)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iO95fMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.0035 -.22363 .26881 -.0042 11.673 5.789)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixnwXBb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.415 3.74)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="iABZ5Ej" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.243 3.209)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><filter id="it4jkgc" width="7.486" height="8.65" x="14.87" y="7.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.552941 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="i6pNaHe" width="5.439" height="5.49" x="2.462" y="16.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="iKPtwJe" width="6.264" height="4.296" x="4.74" y="25.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.505882 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="iRD5PVp" width="5.105" height="3.176" x="4.74" y="26.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="ihcCnjd" width="7.339" height="5.547" x="11.424" y="16.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="iP9Ksmd" width="5.437" height="5.553" x="22.676" y="16.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="ioPsaae" width="2.689" height="5.353" x="25.224" y="16.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="iEkFMqc" width="8.098" height="6.294" x="5.657" y="8.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.603922 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.45098 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23237" result="effect2_innerShadow_3987_23237"/></filter><filter id="iOclphE" width="7.636" height="9.986" x="11.582" y="7.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.34902 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="ifoEoPc" width="2.625" height="5.367" x="19.763" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".25"/></filter><filter id="iTtLMwq" width="3.404" height="3.248" x="18.396" y="8.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="ih4PhNc" width="1.712" height="1.512" x="9.887" y="5.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="ifWnwob" width="1.901" height="1.901" x="9.692" y="5.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".25"/></filter><filter id="iYwVnZd" width="1.762" height="1.762" x="14.194" y="4.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="iDHuZqP" width="1.901" height="1.901" x="13.999" y="5.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".25"/></filter><filter id="inhUGQc" width="4.696" height="5.695" x="10.457" y="3.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="ilALKJe" width="3.922" height="3.388" x="11.869" y="2.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".5"/></filter><filter id="iQNUIDb" width="5.705" height="3.741" x="9.939" y="2.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="iKOqz0n" width="2.297" height="2.714" x="11.535" y="5.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".375"/></filter><filter id="iHVOFhe" width="1.05" height="1.414" x="12.267" y="5.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".05"/></filter><filter id="i1voEGb" width="1.486" height="1.067" x="13.327" y="4.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="ihNE1Me" width="1.486" height="1.067" x="10.996" y="4.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23237"/></filter><filter id="iBGJQBb" width=".466" height=".425" x="13.391" y="5.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".05"/></filter><filter id="iGuIaad" width=".622" height=".632" x="13.717" y="5.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".1"/></filter><filter id="iny7Hcb" width=".665" height=".69" x="11.706" y="5.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".1"/></filter><filter id="iUq9iJB" width=".523" height=".428" x="11.419" y="5.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".05"/></filter><filter id="iaLB7qe" width="1.337" height=".695" x="13.294" y="4.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".1"/></filter><filter id="iNsKLSc" width="1.372" height=".721" x="10.931" y="4.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".1"/></filter><filter id="iTL1eyd" width=".867" height="1.438" x="10.248" y="3.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23237" stdDeviation=".125"/></filter><linearGradient id="inFRzLc" x1="4.743" x2="6.868" y1="18.993" y2="21.118" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="i24w7He" x1="11.118" x2="8.993" y1="26.306" y2="25.556" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="iGYZ1ue" x1="8.915" x2="10.134" y1="25.306" y2="25.77" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="iforYlw" x1="5.181" x2="9.845" y1="27.212" y2="29.743" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="i0WLFfR" x1="7.524" x2="7.466" y1="28.142" y2="28.247" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="iR1A0Be" x1="21.97" x2="21.54" y1="21.134" y2="20.36" gradientUnits="userSpaceOnUse"><stop class="q2zf-acki"/><stop offset="1" class="wrgoaxbaa"/></linearGradient><linearGradient id="ioiTMCb" x1="23.368" x2="23.009" y1="20.415" y2="19.681" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="iAwSFJb" x1="26.313" x2="26.114" y1="18.845" y2="18.931" gradientUnits="userSpaceOnUse"><stop offset=".244" class="jylqepbzd"/><stop offset="1" class="v2dwqfdba"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="iLp5Zne" x1="27.532" x2="25.439" y1="21.156" y2="16.279" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="i1VySRd" x1="26.269" x2="26.38" y1="18.974" y2="18.927" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="ilLha3d" x1="10.643" x2="10.352" y1="6.125" y2="6.125" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="i6RlQbb" x1="15.441" x2="15.07" y1="5.504" y2="6.653" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="io70Uoc" x1="14.619" x2="11.162" y1="6.175" y2="6.69" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="itrB6Jb" x1="10.237" x2="11.758" y1="6.866" y2="6.918" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iJbClTd" x1="10.349" x2="11.201" y1="7.395" y2="7.365" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iU5De8b" x1="12.551" x2="16.238" y1="4.824" y2="3.504" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iC8dEQe" x1="12.401" x2="12.825" y1="6.473" y2="6.473" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iZuQd9c" x1="13.217" x2="12.752" y1="6.619" y2="6.613" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="itV9u4d" x1="12.88" x2="12.88" y1="6.955" y2="6.696" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="isv0eId" x1="14.13" x2="13.988" y1="5.714" y2="5.802" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8pf0Sd" x1="12.14" x2="11.998" y1="5.714" y2="5.802" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXIiBkh" x1="14.137" x2="13.947" y1="4.746" y2="4.357" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ivNknSb" x1="11.736" x2="11.197" y1="4.688" y2="4.462" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iwFA7ve" x1="10.681" x2="10.681" y1="3.776" y2="4.752" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="iPM3I2b" x1="9.797" x2="13.508" y1="3.927" y2="3.927" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="iRjriHc" x1="13.571" x2="13.571" y1="4.271" y2="4.154" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-bouncing-ball-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.aaqnz91xn {
  d: path("M23.563 19.826v-.778a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.247c-.766-1.312-1.607-1.505-2.042-1.52a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.256");
}

.aci9pts-i {
  fill-rule: evenodd;
  d: path("M6.293 14.785c-.79-.084-1.136.337-1.209.514a.415.415 0 0 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.al24rqb9g {
  fill: var(--svg-color--242324, #242324);
  d: path("m14.973 3.066l.195.097a.89.89 0 0 1 .461.965l-.267 1.377c-.024.142-.118.237-.259.241h-.008s.024-.41.048-.652c.02-.196-.014-.256-.194-.434a.57.57 0 0 1-.17-.387v-.386a.26.26 0 0 0-.194-.242c-.292-.072-.899-.193-1.773-.193s-1.481.121-1.772.193a.235.235 0 0 0-.195.242v.386a.48.48 0 0 1-.17.387l-.073.072c-.097.072-.145.217-.145.338c.024.266.048.652.048.652h-.022a.29.29 0 0 1-.27-.241l-.266-1.377a.92.92 0 0 1 .485-.941l.195-.097c.121-.072.242-.169.364-.266l.437-.458a.89.89 0 0 1 .996-.145c.242.072.51.072.752 0c.365-.12.777-.024 1.069.241l.364.362c.097.121.219.194.364.266");
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.biy3jzpmj {
  stop-color: var(--svg-color--daa490, #DAA490);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.btsp6rbtk {
  stop-color: var(--svg-color--fec8b8, #FEC8B8);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.c_xsycbdz {
  stop-color: var(--svg-color--e2ac91, #E2AC91);
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.cdh5ssw-h {
  cx: 14.949px;
  cy: 5.999px;
  r: 0.756px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cuqw36btj {
  d: path("M19.267 22.462c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.804-4.561 2.437-4.773 2.527");
}

.cur1q0ipi {
  d: path("m9.12 25.796l.482.611a.27.27 0 0 0 .399.059c.12-.108.433-.271.71-.059c.279.213.195.578.118.735l-1.032 2.505a.4.4 0 0 1-.564.198l-4.34-2.418a.3.3 0 0 1-.105-.425l.326-.506a.53.53 0 0 1 .643-.193c1.414.555 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.d4a71bwtp {
  stop-color: var(--svg-color--3b8be5, #3B8BE5);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d7rccub7n {
  stop-color: var(--svg-color--d08776, #D08776);
  stop-opacity: 0;
}

.dbltg25wr {
  cx: 14.949px;
  cy: 5.999px;
  r: 0.45px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e085m5ymq {
  stop-color: var(--svg-color--f3beac, #F3BEAC);
}

.e2cbcwbro {
  width: 0.659px;
  height: 1.111px;
  x: 19.37px;
  y: 13.476px;
  rx: 0.33px;
}

.e3m1knbgu {
  stop-color: var(--svg-color--e7dff1, #E7DFF1);
}

.e5ld9oxky {
  fill: var(--svg-color--000, #000);
  d: path("M12.034 5.878a.23.23 0 0 0-.232-.232a.23.23 0 0 0-.205.338h.41a.23.23 0 0 0 .027-.106");
}

.e7237gbfo {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.75 5.56c.028.038-.032.085-.1.136c-.069.05-.12.087-.148.048c-.029-.038.003-.11.072-.162c.068-.051.147-.061.176-.023");
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.edqwx8bzo {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m14.476 4.767l-.002-.001l-.002-.002l-.005-.004l-.07-.049a1.28 1.28 0 0 0-.866-.167a.242.242 0 1 0 .075.478a.8.8 0 0 1 .534.099l.029.02a.242.242 0 0 0 .307-.374");
}

.efzf2zbap {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.666c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.eq8t8ccrw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.74 3.82v.407c-.004.067-.032.217-.117.281");
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f6rtlablh {
  d: path("M12.962 17.462c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.239l-3.085 1.898c-.242.149-.512.239-.73.067c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.699 1.148-1.382 1.265-1.726");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g_v4sglua {
  stop-color: var(--svg-color--5290df, #5290DF);
}

.g0kn9gb3f {
  stop-color: var(--svg-color--b391c2, #B391C2);
}

.g5wehopug {
  cx: 14.949px;
  cy: 5.999px;
  r: 0.45px;
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.gc9u7lbfl {
  stop-color: var(--svg-color--53adfa, #53ADFA);
  stop-opacity: 0;
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.grt6kh0of {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M5.125 14.604c-.293.2-.45.423-.481.5a.415.415 0 0 1-.768-.315c.11-.27.397-.609.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h5ok44qlk {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.311a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.225c.418.266.704.577.875.931c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.491-1.734-2.009a4 4 0 0 0-.741-.378");
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hhvxh5bcs {
  stop-color: var(--svg-color--cb766a, #CB766A);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.i-cfc4c3e {
  d: path("m22.282 20.87l.03-.016l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.i1mrv7bgu {
  stop-color: var(--svg-color--df968d, #DF968D);
  stop-opacity: 0;
}

.i80p6sbrk {
  d: path("M25.282 16.56a.1.1 0 0 1 .044-.125l.091-.051a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.062a.15.15 0 0 1-.187-.084z");
}

.ib089svvj {
  fill: var(--svg-color--ffcaaf, #FFCAAF);
  d: path("M15.216 10.033q.558-.015 1.474.058c.827.065 1.691.196 2.138.531c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.016.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.145a.45.45 0 0 0 .244-.016a.2.2 0 0 1 .172.02a.6.6 0 0 0 .205.086c.14.02.305-.039.367-.234c.035-.109.08-.298.121-.476c.098-.417.25-.822.25-1.255a4.95 4.95 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.ip3ktqbqy {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
}

.ixfgd0bde {
  fill: var(--svg-color--ffdec5, #FFDEC5);
  d: path("M20.857 14.176c.475-1.675-.198-3.355-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.617z");
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.jixz69llq {
  stop-color: var(--svg-color--3c93f1, #3C93F1);
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jrm_lvjlx {
  d: path("M14.139 5.825a.4.4 0 0 0-.105-.21l-.117.13l.053.103z");
}

.jy7vazb8a {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
}

.jylqepbzd {
  stop-color: var(--svg-color--4079dd, #4079DD);
}

.k_ltadprl {
  stop-color: var(--svg-color--ffcebb, #FFCEBB);
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.leycomb-d {
  d: path("m14.973 3.066l.195.097a.89.89 0 0 1 .461.965l-.267 1.377c-.024.142-.118.237-.259.241h-.008s.024-.41.048-.652c.02-.196-.014-.256-.194-.434a.57.57 0 0 1-.17-.387v-.386a.26.26 0 0 0-.194-.242c-.292-.072-.899-.193-1.773-.193s-1.481.121-1.772.193a.235.235 0 0 0-.195.242v.386a.48.48 0 0 1-.17.387l-.073.072c-.097.072-.145.217-.145.338c.024.266.048.652.048.652h-.022a.29.29 0 0 1-.27-.241l-.266-1.377a.92.92 0 0 1 .485-.941l.195-.097c.121-.072.242-.169.364-.266l.437-.458a.89.89 0 0 1 .996-.145c.242.072.51.072.752 0c.365-.12.777-.024 1.069.241l.364.362c.097.121.219.194.364.266");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk1-k5bve {
  stop-color: var(--svg-color--f3bda8, #F3BDA8);
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m11d91bcs {
  cx: 10.643px;
  cy: 5.999px;
  r: 0.45px;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mid6c9bnp {
  stop-color: var(--svg-color--bc818e, #BC818E);
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mqtnlr-ha {
  cx: 10.642px;
  cy: 5.999px;
  r: 0.756px;
}

.mt922xxhp {
  fill-rule: evenodd;
  d: path("M6.322 13.691c-.775-.132-1.17.09-1.3.29a.415.415 0 0 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.818");
}

.muc5wjuki {
  d: path("M9.797 3.309a.1.1 0 0 1 .1-.1h5.926a.1.1 0 0 1 .1.1v.862a.1.1 0 0 1-.1.1H9.897a.1.1 0 0 1-.1-.1z");
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.n5gdkvxgq {
  d: path("m11 20.61l.673-.75l2.336 1.86c-.07.047-.328.208-.797.477c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.97c.326-.858 1.06-2.837 1.391-3.874c.331-1.038.81-1.646 1.008-1.82");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nkhjpg89n {
  stop-color: var(--svg-color--cd8f76, #CD8F76);
  stop-opacity: 0;
}

.nngzf3bsk {
  d: path("M5.527 16.654a2.52 2.52 0 0 0 .598 1.588l.897-.892q.093.085.176.177l-.9.896a2.23 2.23 0 0 0 1.586.621q.014.123.017.25h-.065A2.48 2.48 0 0 1 6.12 18.6l-.777.773l1.754 1.913q-.088.088-.185.168l-1.746-1.905l-.77.765c.422.46.689 1.08.714 1.76a3 3 0 0 1-.25-.017a2.5 2.5 0 0 0-.64-1.567l-.877.871a3 3 0 0 1-.177-.177l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.002c.638 0 1.22.246 1.666.65l.778-.773l-1.758-1.917q.088-.09.184-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.nqhicrryp {
  stop-color: var(--svg-color--b391c2, #B391C2);
  stop-opacity: 0;
}

.o-iz-vbwp {
  stop-color: var(--svg-color--b7a8c2, #B7A8C2);
}

.o0a60dbfj {
  fill: var(--svg-color--000, #000);
  d: path("M13.548 5.878a.23.23 0 0 1 .231-.231a.23.23 0 0 1 .206.337h-.41a.2.2 0 0 1-.027-.106");
}

.o1x-hzk1z {
  d: path("M10.457 5.07c0-.12.048-.266.145-.338l.073-.072a.48.48 0 0 0 .17-.387v-.386c0-.12.073-.217.194-.242c.292-.072.899-.193 1.773-.193s1.482.121 1.773.193a.26.26 0 0 1 .194.242v.386c0 .145.073.29.17.387c.227.159.213.246.194.434c-.024.242-.048.652-.048.652h.008l-.12 1.792c-.073.801-.703 1.36-1.454 1.36h-1.453c-.775 0-1.38-.559-1.453-1.36c-.064-.822-.091-1.647-.166-2.468");
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o4zeo-ufr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.544 4.702c.194-.034.574-.025.837.18");
}

.o67susxgp {
  stop-color: var(--svg-color--51b1ff, #51B1FF);
  stop-opacity: 0;
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of6eoebwa {
  stop-color: var(--svg-color--da9885, #DA9885);
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.oneud5b_v {
  fill: var(--svg-color--ffddc4, #FFDDC4);
  d: path("M11.657 11.712c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.805 1.296-.828h2.438c.386.577.634 1.595.744 2.24a4 4 0 0 0 .145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.392c-.423-1.314-.893-3.615-1.107-4.968");
}

.oxnqswb1g {
  stop-color: var(--svg-color--f6b7a5, #F6B7A5);
  stop-opacity: 0;
}

.p7jmmxb2h {
  stop-color: var(--svg-color--d7a09d, #D7A09D);
  stop-opacity: 0;
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pb1u5rwut {
  d: path("m11.432 25.157l-.853 2.118l-1.977-.97c.176-.462.47-1.25.755-2.04z");
}

.pid-4m06y {
  cx: 5.18px;
  cy: 19.353px;
  r: 2.721px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q2zf-acki {
  stop-color: var(--svg-color--c28895, #C28895);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qhfjj5brh {
  d: path("M13.75 5.56c.028.038-.032.085-.1.136c-.069.05-.12.087-.148.048c-.029-.038.003-.11.072-.162c.068-.051.147-.061.176-.023");
}

.qk70xkspj {
  stop-color: var(--svg-color--e4ab95, #E4AB95);
}

.qm_7gab-x {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.083 4.767l.001-.001l.002-.002l.005-.004l.017-.012l.053-.037a1.28 1.28 0 0 1 .866-.167a.242.242 0 0 1-.075.478a.8.8 0 0 0-.534.099l-.028.02a.242.242 0 0 1-.308-.374");
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qum-1-bur {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.18 4.936c.149-.13.472-.268.873-.204");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_uc2dbaa {
  d: path("m14.586 3.452l-1.393.465a.474.474 0 0 0 .213.92l1.385-.186z");
}

.r-25bbbgc {
  d: path("M12.171 5.83c0-.13-.106-.217-.135-.244l-.13.127l.08.163z");
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r7sr9ubrw {
  d: path("M13.78 5.474a.404.404 0 0 1 .388.51h-.78a.406.406 0 0 1 .391-.51");
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rlozrqb1t {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.709 5.35a.63.63 0 0 0-.614.48c-.02.08.04.154.121.154h1.01a.104.104 0 0 0 .103-.123a.634.634 0 0 0-.62-.51");
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rrixx5x3p {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M12.792 7.416a1.36 1.36 0 0 1-.627-.15c-.062-.03-.129.04-.09.095c.152.23.416.383.717.383c.3 0 .565-.153.716-.383c.04-.058-.027-.126-.089-.094a1.35 1.35 0 0 1-.627.149");
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s2_ykvr2e {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M6.322 13.691c-.775-.132-1.17.09-1.3.29a.415.415 0 0 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.818");
}

.s515o6bjz {
  stop-color: var(--svg-color--bc818e, #BC818E);
  stop-opacity: 0;
}

.saa1azb9d {
  d: path("M11.657 11.712c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.805 1.296-.828h2.438c.386.577.634 1.595.744 2.24a4 4 0 0 0 .145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.392c-.423-1.314-.893-3.615-1.107-4.968");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.skv92hlmk {
  d: path("M11.802 5.474a.404.404 0 0 0-.39.51h.781a.407.407 0 0 0-.391-.51");
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.so34edl-m {
  stop-color: var(--svg-color--3d94fa, #3D94FA);
}

.sq265sb-l {
  d: path("M9.794 29.425a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.t0aiwbcnw {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M5.23 14.112c-.306.178-.45.37-.473.425a.415.415 0 1 1-.768-.314c.12-.291.436-.603.824-.829a2.86 2.86 0 0 1 1.58-.382a.415.415 0 1 1-.042.83a2.03 2.03 0 0 0-1.12.27");
}

.t405zhbew {
  stop-color: var(--svg-color--f3c2a5, #F3C2A5);
  stop-opacity: 0;
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tsvq44-rv {
  stop-color: var(--svg-color--fdc9b0, #FDC9B0);
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uqxno_b8g {
  stop-color: var(--svg-color--3da9fd, #3DA9FD);
}

.usu-mrb7g {
  fill-rule: evenodd;
  d: path("M7.132 13.94a.415.415 0 0 1 .118.575c-.364.55-.738.946-.905 1.123l-.008.008a.415.415 0 0 1-.602-.57l.005-.006c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.uul9_ttvm {
  stop-color: var(--svg-color--98919c, #98919C);
}

.uzkpn5btf {
  stop-color: var(--svg-color--b07f87, #B07F87);
}

.v-vzhociv {
  cx: 11.68px;
  cy: 5.647px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.176px;
  ry: 0.089px;
}

.v2dwqfdba {
  stop-color: var(--svg-color--4079dd, #4079DD);
  stop-opacity: 0;
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.v7a4roj-a {
  fill-rule: evenodd;
  d: path("m11.974 9.003l.053-.092l1.728 1.008l-.074.126c-.712 1.225-1.57 2.699-3.676 3.892c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.099 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.var-spbti {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.462c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.239l-3.085 1.898c-.242.149-.512.239-.73.067c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.699 1.148-1.382 1.265-1.726");
}

.vhhvj2t-s {
  stop-color: var(--svg-color--3e98f5, #3E98F5);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.w_rrm9a7q {
  stop-color: var(--svg-color--d08776, #D08776);
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.weh1a1nwn {
  d: path("m12.619 5.87l-.24.769a.244.244 0 0 0 .235.316h.356c.167 0 .285-.16.236-.316l-.241-.77c-.052-.17-.292-.17-.346 0");
}

.wg6epmg7n {
  stop-color: var(--svg-color--53adfa, #53ADFA);
}

.wg964l8xn {
  d: path("M18.292 22.666c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.whspc9bgn {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
  stop-opacity: 0;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wrgoaxbaa {
  stop-color: var(--svg-color--f2bdaa, #F2BDAA);
  stop-opacity: 0;
}

.wxv9r3nmp {
  d: path("M11.884 8.917c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.273-.238 1.05.25 1.688c.373.486.812.597 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.198.014-2.233.227-2.795");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xu1e5_bcz {
  stop-color: var(--svg-color--3c92ef, #3C92EF);
}

.xvghccb-o {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m12.667 5.943l-.371.77c-.046.158.064.316.22.316h.335c.156 0 .266-.16.22-.316l-.225-.77c-.048-.17-.128-.17-.179 0");
}

.y_h4prb7b {
  cx: 11.68px;
  cy: 5.647px;
  rx: 0.176px;
  ry: 0.089px;
}

.ycl44mqxw {
  stop-color: var(--svg-color--f6b7a5, #F6B7A5);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yljh9-iht {
  fill-rule: evenodd;
  d: path("M5.23 14.112c-.306.178-.45.37-.473.425a.415.415 0 1 1-.768-.314c.12-.291.436-.603.824-.829a2.86 2.86 0 0 1 1.58-.382a.415.415 0 1 1-.042.83a2.03 2.03 0 0 0-1.12.27");
}

.ymdcy-b7v {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M6.293 14.785c-.79-.084-1.136.337-1.209.514a.415.415 0 0 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.yo6ebkk5b {
  d: path("M19.324 8.311a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.225c.418.266.704.577.875.931c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.491-1.734-2.009a4 4 0 0 0-.741-.378");
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.yvgme-ued {
  stop-color: var(--svg-color--f3c2a5, #F3C2A5);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z0yiw70fd {
  fill-rule: evenodd;
  d: path("M5.125 14.604c-.293.2-.45.423-.481.5a.415.415 0 0 1-.768-.315c.11-.27.397-.609.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.z2pel1nsk {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.873 5.35c.296 0 .545.205.613.48a.124.124 0 0 1-.121.154h-1.01a.104.104 0 0 1-.103-.123a.63.63 0 0 1 .62-.51");
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zpviw0bxc {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m12.619 5.87l-.24.769a.244.244 0 0 0 .235.316h.356c.167 0 .285-.16.236-.316l-.241-.77c-.052-.17-.292-.17-.346 0");
}

.zvhlj4t4z {
  stop-color: var(--svg-color--df968d, #DF968D);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
