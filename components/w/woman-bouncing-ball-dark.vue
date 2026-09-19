<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imz3bsE)"><path fill="url(#ixC4Dge)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#iDUMSId)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#iUuntZf)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#iej9xoc)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#irjtGnc)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#ip67rHH)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#ifhNbqe)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#i12K5cc)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#iAPcicb)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#ifhx2Ib)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#i3EoiQt)" clip-rule="evenodd" class="x-8du9i_e"/><path fill="url(#ia0D9Tc)" clip-rule="evenodd" class="x-8du9i_e"/></g><rect fill="url(#i6P2OZc)" transform="rotate(26.961 19.37 13.47)" class="b1ysgbbus"/><g filter="url(#iROU83c)"><path class="j2kgqe7zp"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#iyd6kOb)"><path fill="url(#i0yZFVd)" class="sepv3nkwr"/></g><path fill="url(#iw8t0bd)" class="b1yazzwzl"/><path fill="url(#iRYs9qX)" class="b1yazzwzl"/><path fill="url(#iCUMoEc)" class="of70meq1k"/><path fill="url(#idv3syc)" class="of70meq1k"/><g filter="url(#izJBjfb)"><path fill="url(#ikclHuc)" class="cyh5i_zar"/><path fill="url(#iqSctJd)" class="cyh5i_zar"/><path fill="url(#iZVep2c)" class="cyh5i_zar"/></g><g filter="url(#i2CVDdX)"><path fill="url(#ihTfWPe)" class="vuejbwbij"/><path fill="url(#ieA83vb)" class="vuejbwbij"/></g><path fill="url(#iulRx3d)" class="qexsyge6i"/><path fill="url(#iijTlmb)" class="qexsyge6i"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="thhwo06ax"/><path fill="url(#iB3O36Y)" class="ginv3dbis"/><path fill="url(#i2oUhlc)" class="ginv3dbis"/><path fill="url(#iLGf6rd)" class="ginv3dbis"/><g filter="url(#iLcL4vb)"><path class="sa73rem9k"/><path fill="url(#ipRtVxG)" class="j88k0lalk"/><path fill="url(#ix89MNd)" class="j88k0lalk"/><path fill="url(#iXt88Ec)" class="j88k0lalk"/></g><g filter="url(#iH9Xssb)"><path fill="url(#i55AUOe)" class="yxagr-bug"/><path fill="url(#i136FHe)" class="yxagr-bug"/></g><g filter="url(#iS3gV8d)"><path fill="url(#i4iFAyd)" class="xcwnd6bms"/><path fill="url(#iOQGJ1x)" class="xcwnd6bms"/></g><g filter="url(#ijuKfrd)"><path fill="url(#iS9PGLc)" clip-rule="evenodd" class="y_4pajl7d"/></g><path class="h6shqem9k"/><path fill="url(#iKtWyZd)" class="eikeckbha"/><path fill="url(#iiW7y2d)" class="eikeckbha"/><path clip-rule="evenodd" class="t7a49cbok"/><path fill="url(#iVjgVld)" clip-rule="evenodd" class="x99s9tbej"/><path clip-rule="evenodd" class="mepwz8bxb"/><path fill="url(#i8wS5zc)" clip-rule="evenodd" class="y8eztfbsi"/><path clip-rule="evenodd" class="wp4l-0bam"/><path fill="url(#i31cEkC)" clip-rule="evenodd" class="t7cma5ywk"/><path clip-rule="evenodd" class="j2zqil73b"/><path fill="url(#iwN68qM)" clip-rule="evenodd" class="viuz5dbki"/><path fill="url(#iWychmd)" clip-rule="evenodd" class="s4af_bb4s"/><g filter="url(#i0I9vEb)"><path class="tmtee3wvy"/><path fill="url(#iQBvayU)" class="p3ru7q3ze"/></g><path fill="url(#i3EK4rb)" class="p3ru7q3ze"/><path fill="url(#iwpw8cd)" clip-rule="evenodd" class="y_4pajl7d"/><g filter="url(#iThBLSb)"><path class="v8osb-7cp"/></g><g filter="url(#in9c1Ab)"><path class="j9f4fjdso"/><path fill="url(#ikDRoLc)" class="hpxf53bap"/></g><path fill="url(#iC4Yg4c)" class="jc3m6gbpr"/><path fill="url(#iseQn1c)" class="jvlxkhb5g"/><g filter="url(#iF99njc)"><path fill="url(#imytxuP)" class="n3-uornug"/></g><g filter="url(#iAQezid)"><path fill="url(#iO7iT6c)" class="mv8pcdc3x"/><path fill="url(#ipQVFmd)" class="mv8pcdc3x"/></g><g filter="url(#iQr8sSc)"><path class="h5vly2tkj"/><path fill="url(#ifFhFpe)" class="yev--gbbt"/></g><g filter="url(#i2HsCGA)"><path class="c7vodpkje"/><path fill="url(#iTPdp1t)" class="ozkpdrb2z"/></g><g filter="url(#iPSiZHe)"><path fill="url(#iqvWXqc)" class="d6e8vbetd"/><path fill="url(#iAsN80b)" class="d6e8vbetd"/><path fill="url(#i0ichMN)" class="d6e8vbetd"/><path fill="url(#i3f3grc)" class="d6e8vbetd"/><path fill="url(#iwEnn5d)" class="d6e8vbetd"/><path fill="url(#imH9w1b)" class="d6e8vbetd"/><path fill="url(#iXaqS9b)" class="d6e8vbetd"/><path fill="url(#iRnu0ib)" class="d6e8vbetd"/></g><path fill="url(#ii8xfdc)" class="d6e8vbetd"/><path fill="url(#iW7Pbye)" class="d6e8vbetd"/><g filter="url(#ipy76fe)"><path class="jq7ua48xq"/></g><g filter="url(#iak9eIN)"><path class="umukxkbqw"/><path fill="url(#irdwDVc)" class="ma0rq8byp"/><path fill="url(#iyfFjwc)" class="ma0rq8byp"/><path fill="url(#iv4eUed)" class="ma0rq8byp"/><path fill="url(#imYUzPc)" class="ma0rq8byp"/></g><g filter="url(#iwNryze)"><path stroke="url(#ih1S4Yc)" class="smsfwib5a"/></g><path class="r0gvrtb7u"/><g filter="url(#ia2czxe)"><path class="vhjtasbtw"/></g><g filter="url(#izHiwjk)"><path class="vduidpbnw"/></g><g filter="url(#ikW5uRd)"><path class="qxzmp5tlk"/></g><g filter="url(#ikpZp3O)"><path clip-rule="evenodd" class="gv_m0rfny"/></g><path class="hqgdd5p4z"/><path fill="url(#i6LtWne)" class="esz20tjtq"/><path class="pmpc-jbtg"/><g filter="url(#iGVafNp)"><path class="aasv0ac6h"/><path fill="url(#iVFR0be)" class="fm6__4s-a"/></g><g filter="url(#ioOKfte)"><path fill="url(#il22yOd)" class="szw5yccab"/></g><path class="noepf8b0z"/><path fill="url(#i3LYUrY)" class="zp7l0n1bm"/><path class="ngrbimqoq"/><g filter="url(#ioIUwxe)"><path fill="url(#i1twDFc)" class="yzw9_cswp"/></g><g filter="url(#i2eUwwd)"><ellipse transform="rotate(-27.914 11.775 5.705)" class="bf2wnwb9u"/><ellipse fill="url(#ioaa8bw)" transform="rotate(-27.914 11.775 5.705)" class="sa2jimbnx"/></g><g filter="url(#iiYxE2b)"><path class="ihqt4yopx"/></g><g filter="url(#iomUjqb)"><path class="ir658hbtp"/></g><g filter="url(#iUlHvWd)"><path class="h3gz0cbrh"/><path fill="url(#iDSRmNb)" class="edezdccbu"/><path fill="url(#iZmL0Fd)" class="edezdccbu"/></g><g filter="url(#iTdBZsc)"><path class="rw-156b3q"/></g><g filter="url(#ifhrmRZ)"><path clip-rule="evenodd" class="tsc4hfq3g"/></g><defs><radialGradient id="iDUMSId" cx="0" cy="0" r="1" gradientTransform="matrix(-.2767 2.0907 -2.6117 -.34565 12.763 7.169)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iUuntZf" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.62 5.4)scale(1.59466 2.09525)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iej9xoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59953 .78402 -.60202 -.46036 10.68 6.124)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="irjtGnc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.987 5.65)scale(1.13501 .79952)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ip67rHH" cx="0" cy="0" r="1" gradientTransform="matrix(.63028 1.19908 -1.66451 .87493 11.286 2.327)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ifhNbqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.66099 .66103 -.92378 -.92372 15.575 3.28)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="i12K5cc" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 7.77 3.98)scale(.88052 1.83625)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iAPcicb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29127 .32284 -.41125 -1.6449 16.067 7.2)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ifhx2Ib" cx="0" cy="0" r="1" gradientTransform="matrix(-.41476 -1.21536 .96128 -.32805 15.07 4.516)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i3EoiQt" cx="0" cy="0" r="1" gradientTransform="rotate(5.989 -48.636 99.206)scale(.69345 1.12359)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ia0D9Tc" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 3.616 5.89)scale(1.33893 1.23424)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="i6P2OZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="e8oc6bywr"/><stop offset="1" class="wzf1pcvjw"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="iw8t0bd" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="erkbt9b7m"/><stop offset="1" class="zb0z-k-8t"/></radialGradient><radialGradient id="iRYs9qX" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ne1zjtblh"/><stop offset="1" class="y1q425b6v"/></radialGradient><radialGradient id="ikclHuc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="b1kvifv3j"/><stop offset="1" class="w__bqyylv"/></radialGradient><radialGradient id="iqSctJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="jfk78yx3r"/><stop offset="1" class="v_thlccbr"/></radialGradient><radialGradient id="iZVep2c" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="jfk78yx3r"/><stop offset="1" class="v_thlccbr"/></radialGradient><radialGradient id="iulRx3d" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="vmzfl5bmw"/><stop offset="1" class="kf-rak19e"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="i55AUOe" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="uwn_p0-dn"/><stop offset="1" class="sa6pubcic"/></radialGradient><radialGradient id="iS9PGLc" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="euv_c6bft"/><stop offset="1" class="zkdorr-qw"/></radialGradient><radialGradient id="iKtWyZd" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="oaslx4bco"/><stop offset="1" class="y1haz_b5t"/></radialGradient><radialGradient id="iiW7y2d" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="zx3oawgbb"/><stop offset=".945" class="xc4yriomg"/></radialGradient><radialGradient id="iVjgVld" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="yssh7b0_e"/><stop offset="1" class="nwlgi0bip"/></radialGradient><radialGradient id="i8wS5zc" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="yssh7b0_e"/><stop offset="1" class="nwlgi0bip"/></radialGradient><radialGradient id="i31cEkC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="yssh7b0_e"/><stop offset="1" class="nwlgi0bip"/></radialGradient><radialGradient id="iwN68qM" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="yssh7b0_e"/><stop offset="1" class="nwlgi0bip"/></radialGradient><radialGradient id="iWychmd" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.12 8.922)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="nn8u2ibbq"/><stop offset="1" class="rq9thmbis"/></radialGradient><radialGradient id="i3EK4rb" cx="0" cy="0" r="1" gradientTransform="rotate(106.912 4.941 9.22)scale(3.20093 4.86981)" gradientUnits="userSpaceOnUse"><stop class="env4r_bwx"/><stop offset="1" class="spg8_pgop"/></radialGradient><radialGradient id="iwpw8cd" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="w_a146b3e"/><stop offset="1" class="w8yk26t7j"/></radialGradient><radialGradient id="ikDRoLc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><radialGradient id="iO7iT6c" cx="0" cy="0" r="1" gradientTransform="matrix(1.14143 -.51883 .63347 1.39363 14.753 6.224)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="ipQVFmd" cx="0" cy="0" r="1" gradientTransform="rotate(29.271 -2.442 31.778)scale(.6917 .19555)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="ifFhFpe" cx="0" cy="0" r="1" gradientTransform="matrix(.6924 -.0515 .04026 .54127 14.914 6.074)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iTPdp1t" cx="0" cy="0" r="1" gradientTransform="matrix(-.55342 0 0 -.43658 10.79 6.022)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iqvWXqc" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 6.472 4.447)scale(3.28423 4.39589)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="iAsN80b" cx="0" cy="0" r="1" gradientTransform="matrix(-.93387 .44517 -.31001 -.65033 13.738 6.162)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="i0ichMN" cx="0" cy="0" r="1" gradientTransform="matrix(.49228 -1.59406 2.02256 .6246 11.9 8.886)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="i3f3grc" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 3.975 8.768)scale(3.13996 3.15678)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iwEnn5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.01145 -3.02758 0 12.78 5.955)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="imH9w1b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1668 .62147 -1.06999 -5.45225 13.73 6.57)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iXaqS9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.52772 .64766 0 13.956 5.584)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iRnu0ib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6019 .6898 0 11.948 5.48)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="ii8xfdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.5894 0 0 -2.95581 15.237 6.266)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iW7Pbye" cx="0" cy="0" r="1" gradientTransform="matrix(-.83874 .72197 -.48388 -.56215 14.699 8.122)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="irdwDVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2089 -.93734 .28888 -.06438 13.26 6.6)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="imYUzPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.35742 0 0 -.09992 13.15 6.696)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="i6LtWne" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37205 -.5918 0 13.901 5.748)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVFR0be" cx="0" cy="0" r="1" gradientTransform="matrix(-.1061 -.13673 .18825 -.14608 13.796 5.787)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3LYUrY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37206 -.5918 0 11.9 5.748)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ioaa8bw" cx="0" cy="0" r="1" gradientTransform="matrix(-.00354 -.22604 .27171 -.00425 11.768 5.849)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDSRmNb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.138 5.525)scale(2.23461 3.65346)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iZmL0Fd" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 5.401 6.854)scale(.63435 1.36475)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="imz3bsE" width="7.137" height="7.637" x="9.457" y="1.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="iROU83c" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.113725 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="iyd6kOb" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="izJBjfb" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.341176 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="i2CVDdX" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="iLcL4vb" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="iH9Xssb" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="iS3gV8d" width="2.689" height="5.353" x="25.224" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="ijuKfrd" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.129412 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.14902 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23224" result="effect2_innerShadow_3987_23224"/></filter><filter id="i0I9vEb" width="8.236" height="9.786" x="11.582" y="7.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.262745 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23224" result="effect2_innerShadow_3987_23224"/></filter><filter id="iThBLSb" width="2.625" height="5.367" x="19.763" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".25"/></filter><filter id="in9c1Ab" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="iF99njc" width="1.626" height="1.476" x="10.014" y="5.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="iAQezid" width="1.476" height="1.726" x="14.376" y="5.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="iQr8sSc" width="1.985" height="1.985" x="14.122" y="5.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".25"/></filter><filter id="i2HsCGA" width="1.485" height="1.485" x="10.018" y="5.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".125"/></filter><filter id="iPSiZHe" width="4.673" height="5.238" x="10.564" y="3.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="ipy76fe" width="1.861" height="2.23" x="11.896" y="5.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".25"/></filter><filter id="iak9eIN" width="1.061" height="1.43" x="12.37" y="5.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".05"/></filter><filter id="iwNryze" width="1.914" height=".916" x="11.943" y="6.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".05"/></filter><filter id="ia2czxe" width="1.485" height=".589" x="13.224" y="5.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="izHiwjk" width="1.485" height=".589" x="11.092" y="5.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="ikW5uRd" width="1.233" height=".609" x="11.154" y="4.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="ikpZp3O" width="1.233" height=".609" x="13.639" y="4.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><filter id="iGVafNp" width=".468" height=".427" x="13.51" y="5.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".05"/></filter><filter id="ioOKfte" width=".625" height=".635" x="13.841" y="5.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".1"/></filter><filter id="ioIUwxe" width=".668" height=".693" x="11.804" y="5.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".1"/></filter><filter id="i2eUwwd" width=".526" height=".431" x="11.512" y="5.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".05"/></filter><filter id="iiYxE2b" width="1.062" height=".473" x="13.64" y="4.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".05"/></filter><filter id="iomUjqb" width="1.062" height=".473" x="11.14" y="4.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".05"/></filter><filter id="iUlHvWd" width="4.218" height="2.772" x="11.284" y="2.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/><feGaussianBlur result="effect2_foregroundBlur_3987_23224" stdDeviation=".075"/></filter><filter id="iTdBZsc" width="2.859" height="1.458" x="12.678" y="3.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23224" stdDeviation=".15"/></filter><filter id="ifhrmRZ" width="1.518" height=".691" x="11.092" y="3.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.345098 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23224"/></filter><linearGradient id="ixC4Dge" x1="15.053" x2="11.932" y1="2.834" y2="8.614" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="iijTlmb" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="z-3d4acgs"/><stop offset="1" class="h60oztn5g"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="i136FHe" x1="26.313" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ivbdbpjuw"/><stop offset="1" class="zovioqy4e"/></linearGradient><linearGradient id="i4iFAyd" x1="27.532" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="iQBvayU" x1="18.384" x2="14.604" y1="15.165" y2="16.372" gradientUnits="userSpaceOnUse"><stop offset=".207" class="uov-5vb3w"/><stop offset="1" class="mzo6olgul"/></linearGradient><linearGradient id="iC4Yg4c" x1="9.614" x2="16.191" y1="8.228" y2="8.228" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iseQn1c" x1="9.597" x2="16.208" y1="8.214" y2="8.214" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="imytxuP" x1="10.014" x2="11.371" y1="6.062" y2="6.062" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iyfFjwc" x1="12.47" x2="12.9" y1="6.633" y2="6.633" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iv4eUed" x1="12.9" x2="12.9" y1="6.999" y2="6.719" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="ih1S4Yc" x1="12.412" x2="12.624" y1="7.646" y2="7.319" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="il22yOd" x1="14.258" x2="14.114" y1="5.773" y2="5.862" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1twDFc" x1="12.241" x2="12.097" y1="5.773" y2="5.861" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-bouncing-ball-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.aasv0ac6h {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.871 5.617c.03.038-.031.086-.1.138c-.07.051-.121.088-.15.049c-.03-.04.003-.113.072-.164c.07-.052.15-.062.178-.023");
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b1kvifv3j {
  stop-color: var(--svg-color--8668c7, #8668C7);
}

.b1yazzwzl {
  d: path("m11 20.604l.673-.75l2.336 1.86c-.07.046-.328.207-.797.476c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.969c.326-.86 1.06-2.837 1.391-3.875s.81-1.646 1.008-1.82");
}

.b1ysgbbus {
  width: 0.659px;
  height: 1.111px;
  x: 19.37px;
  y: 13.469px;
  rx: 0.33px;
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bf2wnwb9u {
  cx: 11.775px;
  cy: 5.705px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.178px;
  ry: 0.09px;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c7vodpkje {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M10.76 6.515a.493.493 0 1 0 0-.985a.493.493 0 0 0 0 .985");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.cyh5i_zar {
  d: path("m9.12 25.79l.482.61a.27.27 0 0 0 .399.059c.12-.108.433-.271.71-.059c.279.213.195.579.118.735L9.797 29.64a.4.4 0 0 1-.564.198l-4.34-2.419a.3.3 0 0 1-.105-.424l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d6e8vbetd {
  d: path("M10.568 5.443h.005l-.005-.121l-.004-.14c.01-.436.263-.604.371-.66l.024-.01l.023-.01c.245-.111.442-.308.546-.565l.037-.09a.12.12 0 0 1 .212-.023c.33.482.88.768 1.463.768h1.476c.083 0 .497.04.521.61l-.054 1.41c-.057 1.285-1.06 2.148-2.285 2.148s-2.23-.863-2.286-2.148z");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e8oc6bywr {
  stop-color: var(--svg-color--382525, #382525);
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.edezdccbu {
  d: path("M12.624 2.45c-.52-.115-.986.403-1.04.595c.483 1.626 1.703 1.537 2.908 1.403c.72-.08.8.249.86.408c0-1.804-1.533-2.142-2.715-2.403z");
}

.eikeckbha {
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.env4r_bwx {
  stop-color: var(--svg-color--966bb1, #966BB1);
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.erkbt9b7m {
  stop-color: var(--svg-color--4d3235, #4D3235);
}

.esz20tjtq {
  d: path("M13.902 5.53a.41.41 0 0 1 .395.517h-.791a.41.41 0 0 1 .396-.517");
}

.euv_c6bft {
  stop-color: var(--svg-color--442c2d, #442C2D);
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fm6__4s-a {
  d: path("M13.871 5.617c.03.038-.031.086-.1.138c-.07.051-.121.088-.15.049c-.03-.04.003-.113.072-.164c.07-.052.15-.062.178-.023");
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.ft5dv1b6b {
  fill: none;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.ginv3dbis {
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gv_m0rfny {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m14.612 4.997l-.063.106za.123.123 0 0 1-.126.211l-.003-.001l-.01-.006l-.042-.02a1 1 0 0 0-.156-.063a1.04 1.04 0 0 0-.492-.042a.123.123 0 1 1-.043-.242c.236-.042.453 0 .61.05a1.5 1.5 0 0 1 .255.11l.005.002z");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h3gz0cbrh {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M12.624 2.45c-.52-.115-.986.403-1.04.595c.483 1.626 1.703 1.537 2.908 1.403c.72-.08.8.249.86.408c0-1.804-1.533-2.142-2.715-2.403z");
}

.h5vly2tkj {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M15.114 6.515a.493.493 0 1 0 0-.985a.493.493 0 0 0 0 .985");
}

.h60oztn5g {
  stop-color: var(--svg-color--432836, #432836);
  stop-opacity: 0;
}

.h6shqem9k {
  fill: var(--svg-color--6a5856, #6A5856);
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpxf53bap {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.hqgdd5p4z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.997 5.405c.3 0 .553.207.621.486c.02.08-.04.156-.122.156h-1.024a.106.106 0 0 1-.104-.125a.64.64 0 0 1 .63-.517");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.ihqt4yopx {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.79 4.934c.148-.036.516-.018.762.158");
}

.ir658hbtp {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.051 4.934a1.1 1.1 0 0 0-.761.158");
}

.ivbdbpjuw {
  stop-color: var(--svg-color--614a93, #614A93);
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j2kgqe7zp {
  fill: var(--svg-color--4b3230, #4B3230);
  d: path("M15.216 10.026q.558-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.821.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j2zqil73b {
  fill: var(--svg-color--483230, #483230);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.j88k0lalk {
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.j9f4fjdso {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.jc3m6gbpr {
  d: path("M13.063 8.214q.174.008.353.023c-.12-.009-.234-.018-.353-.023");
}

.jfk78yx3r {
  stop-color: var(--svg-color--9a82d0, #9A82D0);
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jq7ua48xq {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m12.72 5.92l-.313.78c-.05.16.07.32.239.32h.36c.17 0 .289-.162.24-.32L13 5.92c-.052-.172-.226-.172-.28 0");
}

.jvlxkhb5g {
  d: path("M12.912 8.214h-.018c.046 0 .087 0 .133.005c-.036-.005-.078-.005-.115-.005");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kf-rak19e {
  stop-color: var(--svg-color--402531, #402531);
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.ma0rq8byp {
  d: path("m12.725 5.857l-.243.78c-.05.16.07.32.238.32h.36c.17 0 .29-.163.24-.32l-.244-.78c-.052-.173-.296-.173-.35 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mepwz8bxb {
  fill: var(--svg-color--483230, #483230);
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mv8pcdc3x {
  d: path("M15.114 6.76a.738.738 0 1 0 0-1.476a.738.738 0 0 0 0 1.476");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mzo6olgul {
  stop-color: var(--svg-color--8568c5, #8568C5);
  stop-opacity: 0;
}

.n3-uornug {
  d: path("M10.752 6.76a.738.738 0 1 0 0-1.476a.738.738 0 0 0 0 1.476");
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.ne1zjtblh {
  stop-color: var(--svg-color--3d2231, #3D2231);
  stop-opacity: 0;
}

.ngrbimqoq {
  fill: var(--svg-color--000, #000);
  d: path("M12.134 5.939a.233.233 0 0 0-.235-.234a.233.233 0 0 0-.208.342h.415a.23.23 0 0 0 .027-.108");
}

.nn8u2ibbq {
  stop-color: var(--svg-color--655453, #655453);
}

.noepf8b0z {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.804 5.405a.64.64 0 0 0-.621.486c-.02.08.04.156.123.156h1.023c.065 0 .117-.06.104-.125a.64.64 0 0 0-.629-.517");
}

.nwlgi0bip {
  stop-color: var(--svg-color--3b2425, #3B2425);
  stop-opacity: 0;
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.oaslx4bco {
  stop-color: var(--svg-color--311c1c, #311C1C);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of70meq1k {
  d: path("m11.432 25.15l-.853 2.118l-1.977-.969c.176-.463.47-1.25.755-2.041z");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ozkpdrb2z {
  d: path("M10.76 6.515a.493.493 0 1 0 0-.985a.493.493 0 0 0 0 .985");
}

.p3ru7q3ze {
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmpc-jbtg {
  fill: var(--svg-color--000, #000);
  d: path("M13.668 5.939c0-.13.104-.234.234-.234a.233.233 0 0 1 .209.342h-.415a.2.2 0 0 1-.028-.108");
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qexsyge6i {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qxzmp5tlk {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.343 5.207l-.002.001a.123.123 0 0 1-.127-.21v-.001l.002-.001l.005-.003l.014-.008l.054-.027c.045-.021.11-.049.188-.074c.156-.05.374-.092.609-.05a.123.123 0 0 1-.043.242c-.183-.032-.358 0-.491.042a1.3 1.3 0 0 0-.2.083z");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r0gvrtb7u {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M12.9 7.357a1.4 1.4 0 0 1-.651-.158c-.065-.033-.134.041-.094.101a.886.886 0 0 0 1.49 0c.041-.062-.028-.134-.092-.1c-.19.1-.411.157-.652.157");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rq9thmbis {
  stop-color: var(--svg-color--482c2f, #482C2F);
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rw-156b3q {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m14.004 4.105l-.654.12a.316.316 0 1 1-.057-.626h1.073c.635 0 .845.64.871.859a1.44 1.44 0 0 0-1.233-.353");
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s4af_bb4s {
  fill-rule: evenodd;
  d: path("M7.132 13.933a.415.415 0 0 1 .118.575a8 8 0 0 1-.913 1.13a.415.415 0 1 1-.602-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sa2jimbnx {
  cx: 11.775px;
  cy: 5.705px;
  rx: 0.178px;
  ry: 0.09px;
}

.sa6pubcic {
  stop-color: var(--svg-color--8466c4, #8466C4);
}

.sa73rem9k {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.sepv3nkwr {
  d: path("M5.527 16.647c.013.613.238 1.167.598 1.588l.897-.892q.093.085.176.178l-.9.895a2.23 2.23 0 0 0 1.586.621q.014.123.017.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.773l1.754 1.913q-.088.089-.185.168l-1.746-1.905l-.77.765c.422.461.689 1.08.714 1.761a3 3 0 0 1-.25-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.178l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.666.65l.778-.773l-1.758-1.918q.088-.09.184-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.smsfwib5a {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.9 7.357a1.4 1.4 0 0 1-.651-.158c-.065-.033-.134.041-.094.101a.886.886 0 0 0 1.49 0c.041-.062-.028-.134-.092-.1c-.19.1-.411.157-.652.157Z");
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.spg8_pgop {
  stop-color: var(--svg-color--966bb1, #966BB1);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.szw5yccab {
  d: path("M14.267 5.885a.4.4 0 0 0-.106-.212l-.12.13l.054.105z");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.t7a49cbok {
  fill: var(--svg-color--483230, #483230);
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.t7cma5ywk {
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.thhwo06ax {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.tmtee3wvy {
  fill: var(--svg-color--876cc6, #876CC6);
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tsc4hfq3g {
  fill: var(--svg-color--9f97a6, #9F97A6);
  fill-rule: evenodd;
  d: path("M12.61 4.473h-1.518a1.05 1.05 0 0 0 .47-.527l.037-.089a.12.12 0 0 1 .211-.023c.2.292.48.512.8.64");
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u072kwb9c {
  d: path("m22.282 20.864l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.umukxkbqw {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m12.725 5.857l-.243.78c-.05.16.07.32.238.32h.36c.17 0 .29-.163.24-.32l-.244-.78c-.052-.173-.296-.173-.35 0");
}

.uov-5vb3w {
  stop-color: var(--svg-color--9782d0, #9782D0);
}

.uwn_p0-dn {
  stop-color: var(--svg-color--8366c4, #8366C4);
}

.v_thlccbr {
  stop-color: var(--svg-color--9a82d0, #9A82D0);
  stop-opacity: 0;
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.v8osb-7cp {
  fill: var(--svg-color--614e4d, #614E4D);
  d: path("M20.857 14.169c.475-1.675-.198-3.354-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.618z");
}

.vduidpbnw {
  fill: var(--svg-color--272528, #272528);
  d: path("M12.377 5.761c-.122-.214-.307-.383-.705-.383a.76.76 0 0 0-.492.17c-.123.099-.107.226-.011.274l.255.146c.299-.097.629-.11.953-.207");
}

.vhjtasbtw {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M13.424 5.761c.122-.214.307-.383.705-.383a.76.76 0 0 1 .492.17c.123.099.107.226.011.274l-.255.146c-.298-.097-.629-.11-.953-.207");
}

.viuz5dbki {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.vmzfl5bmw {
  stop-color: var(--svg-color--462928, #462928);
}

.vuejbwbij {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.w__bqyylv {
  stop-color: var(--svg-color--8768cb, #8768CB);
}

.w_a146b3e {
  stop-color: var(--svg-color--4b3532, #4B3532);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.w8yk26t7j {
  stop-color: var(--svg-color--4b3532, #4B3532);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.wp4l-0bam {
  fill: var(--svg-color--483230, #483230);
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.wzf1pcvjw {
  stop-color: var(--svg-color--33151d, #33151D);
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x-8du9i_e {
  fill-rule: evenodd;
  d: path("M16.195 6.669a1.5 1.5 0 0 0 .025-1.253h.003a1.5 1.5 0 0 0-.129-.235v-.002a1.5 1.5 0 0 1-.242-.812v-.005c0-.835-.678-1.513-1.513-1.513a.25.25 0 0 1-.209-.106a1.516 1.516 0 0 0-2.46 0a.26.26 0 0 1-.208.106h-.04a1.514 1.514 0 0 0-1.473 1.513v.005c0 .288-.084.57-.242.812v.002a1.51 1.51 0 0 0-.102 1.488a.24.24 0 0 1 0 .209a1.474 1.474 0 0 0 1.327 2.12h3.936a1.474 1.474 0 0 0 1.327-2.12a.24.24 0 0 1 0-.21m-5.622-1.226h-.005l.55 1.08c.056 1.286.557 0 1.782 0s1.76 1.431 1.816.146l.521-1.466c-.025-.571-.438-.611-.52-.611H13.24a1.77 1.77 0 0 1-1.463-.768a.12.12 0 0 0-.212.024l-.037.089a1.06 1.06 0 0 1-.546.566l-.023.01l-.024.009c-.108.056-.362.224-.371.66l.005.14z");
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.x99s9tbej {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.xc4yriomg {
  stop-color: var(--svg-color--533938, #533938);
}

.xcwnd6bms {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.187-.085z");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y_4pajl7d {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.y1haz_b5t {
  stop-color: var(--svg-color--311c1c, #311C1C);
  stop-opacity: 0;
}

.y1q425b6v {
  stop-color: var(--svg-color--3d2231, #3D2231);
}

.y8eztfbsi {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yev--gbbt {
  d: path("M15.114 6.515a.493.493 0 1 0 0-.985a.493.493 0 0 0 0 .985");
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.yssh7b0_e {
  stop-color: var(--svg-color--3b2425, #3B2425);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxagr-bug {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.313-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.256");
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.yzw9_cswp {
  d: path("M12.272 5.89c0-.132-.107-.22-.136-.246l-.132.127l.081.166z");
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z-3d4acgs {
  stop-color: var(--svg-color--432836, #432836);
}

.zb0z-k-8t {
  stop-color: var(--svg-color--3f2522, #3F2522);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zkdorr-qw {
  stop-color: var(--svg-color--442229, #442229);
}

.zovioqy4e {
  stop-color: var(--svg-color--614a93, #614A93);
  stop-opacity: 0;
}

.zp7l0n1bm {
  d: path("M11.899 5.53a.41.41 0 0 0-.394.517h.79a.412.412 0 0 0-.396-.517");
}

.zx3oawgbb {
  stop-color: var(--svg-color--533938, #533938);
  stop-opacity: 0;
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
