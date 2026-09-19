<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#i8tgWOd)" transform="rotate(26.961 19.37 13.476)" class="e2cbcwbro"/><g filter="url(#ixO19Cd)"><path class="dq_1-7o5n"/></g><circle fill="url(#inFRzLc)" class="pid-4m06y"/><circle fill="url(#ikT3wpb)" class="pid-4m06y"/><circle fill="url(#ipd3rHo)" class="pid-4m06y"/><circle fill="url(#ieUwNdb)" class="pid-4m06y"/><g filter="url(#iOu2EIi)"><path fill="url(#iPR2xGd)" class="nngzf3bsk"/></g><path fill="url(#i8QjEsd)" class="n5gdkvxgq"/><path fill="url(#iUeJ2Sb)" class="n5gdkvxgq"/><path fill="url(#i24w7He)" class="kcb6yjbmm"/><path fill="url(#iGYZ1ue)" class="kcb6yjbmm"/><g filter="url(#i9IXPgg)"><path fill="url(#iu5UMge)" class="cur1q0ipi"/><path fill="url(#iNRX4zb)" class="cur1q0ipi"/><path fill="url(#iQpddTg)" class="cur1q0ipi"/></g><g filter="url(#iXXsvCd)"><path fill="url(#iforYlw)" class="sq265sb-l"/><path fill="url(#i0WLFfR)" class="sq265sb-l"/></g><path fill="url(#iVuFPpe)" class="cuqw36btj"/><path fill="url(#iuHFcTc)" class="cuqw36btj"/><path fill="url(#ivkbt6S)" class="i-cfc4c3e"/><path fill="url(#ioiTMCb)" class="i-cfc4c3e"/><path fill="url(#i5wZYne)" class="i-cfc4c3e"/><path fill="url(#igATwqb)" class="i-cfc4c3e"/><path class="efzf2zbap"/><path fill="url(#is0WZfd)" class="wg964l8xn"/><path fill="url(#iHTPxqd)" class="wg964l8xn"/><path fill="url(#iCnPime)" class="wg964l8xn"/><g filter="url(#i1QUBor)"><path class="var-spbti"/><path fill="url(#icubEce)" class="f6rtlablh"/><path fill="url(#iHJmVvb)" class="f6rtlablh"/><path fill="url(#idjB8bc)" class="f6rtlablh"/></g><g filter="url(#iFmojId)"><path fill="url(#iwuX1jb)" class="aaqnz91xn"/><path fill="url(#iAwSFJb)" class="aaqnz91xn"/></g><g filter="url(#ixNhOQb)"><path fill="url(#iLp5Zne)" class="i80p6sbrk"/><path fill="url(#i1VySRd)" class="i80p6sbrk"/></g><g filter="url(#i5Duqle)"><path fill="url(#ihRkukc)" clip-rule="evenodd" class="v7a4roj-a"/></g><path class="gbgug8b6d"/><path fill="url(#iY3Gkce)" class="saa1azb9d"/><path fill="url(#izlY3be)" class="saa1azb9d"/><path clip-rule="evenodd" class="t90z1wkyp"/><path fill="url(#ieRwBBw)" clip-rule="evenodd" class="uqcxmbcfb"/><path clip-rule="evenodd" class="z_1m3ccsq"/><path fill="url(#iiAKlHe)" clip-rule="evenodd" class="yljh9-iht"/><path clip-rule="evenodd" class="s5515db0i"/><path fill="url(#iEW2KXc)" clip-rule="evenodd" class="z0yiw70fd"/><path clip-rule="evenodd" class="odhno-5ym"/><path fill="url(#ieJiSGR)" clip-rule="evenodd" class="yfvcl8bli"/><path fill="url(#iOobPcw)" clip-rule="evenodd" class="usu-mrb7g"/><g filter="url(#i8oh8ic)"><path fill="url(#iHOb1Sc)" class="wxv9r3nmp"/><path fill="url(#ipICnYc)" class="wxv9r3nmp"/></g><path fill="url(#i2a8zYc)" class="wxv9r3nmp"/><path fill="url(#ixtAMxe)" clip-rule="evenodd" class="v7a4roj-a"/><g filter="url(#izHhLre)"><path class="m54s94buf"/></g><g filter="url(#iYuurQa)"><path class="h5ok44qlk"/><path fill="url(#iOJ29Xd)" class="yo6ebkk5b"/></g><g filter="url(#igzl4ac)"><circle fill="url(#icJ6Fbd)" class="afwmdpbtl"/></g><g filter="url(#i6VnbVN)"><circle fill="url(#id3llJe)" class="rch19fi1w"/></g><g filter="url(#iNuAy7b)"><circle fill="url(#i01vLVd)" class="pyuc6d_7f"/><circle fill="url(#iL8GHlb)" class="pyuc6d_7f"/></g><g filter="url(#ixeD6ov)"><circle class="e_wjd0bor"/><circle fill="url(#iBuvpPb)" class="jrg-8z1gq"/><circle fill="url(#ikKrIab)" class="jrg-8z1gq"/></g><g filter="url(#iqxa3wc)"><path fill="url(#is6lStb)" class="bzw267bym"/><path fill="url(#isZ2kwc)" class="bzw267bym"/><path fill="url(#ijbMCzc)" class="bzw267bym"/><path fill="url(#iXsnT8X)" class="bzw267bym"/><path fill="url(#iuBTG6U)" class="bzw267bym"/></g><g filter="url(#irBi0Od)"><path class="atpccsbtm"/><path fill="url(#iTeEFwc)" class="q_nak1h4o"/><path fill="url(#iYlYUFx)" class="q_nak1h4o"/><path fill="url(#iUzVhJe)" class="q_nak1h4o"/><path fill="url(#iXrATOc)" class="q_nak1h4o"/><path fill="url(#iuPPfcb)" class="q_nak1h4o"/></g><path fill="url(#isluHLe)" class="q_nak1h4o"/><path fill="url(#ihNrjyc)" class="q_nak1h4o"/><g filter="url(#ilXxPbe)"><path class="ya6ed1s7r"/></g><g filter="url(#iHyGpne)"><path class="tt3cvqbuk"/><path fill="url(#i4cs5qb)" class="p73626bhv"/><path fill="url(#igmFgcr)" class="p73626bhv"/><path fill="url(#iV2nA4w)" class="p73626bhv"/></g><path stroke="url(#izhztpQ)" class="rpzm12bqg"/><g filter="url(#ieblFws)"><path class="vqjcz4uub"/></g><g filter="url(#iQe0QkA)"><path class="j2_wuxbny"/></g><path class="mq70z9bkg"/><path fill="url(#ihRuR2w)" class="hq7x2mbti"/><path class="h87jn4bfj"/><g filter="url(#i1VzxoF)"><path class="v300w2bja"/><path fill="url(#im1g9we)" class="sw4x5xbtf"/></g><g filter="url(#iZFR2Xb)"><path fill="url(#iBBrnKe)" class="zxhxo6bwd"/></g><path class="r-cw1cber"/><path fill="url(#iA9LOnk)" class="ciy4kid0r"/><path class="p412jwbbq"/><g filter="url(#iJYuTje)"><path fill="url(#iKay8hb)" class="r0fswm2la"/></g><g filter="url(#i9bj43d)"><ellipse transform="rotate(-27.914 11.768 5.647)" class="lklg-abmk"/><ellipse fill="url(#ihbIdRd)" transform="rotate(-27.914 11.768 5.647)" class="nh2ifcqxe"/></g><g filter="url(#iBEJ9sv)"><path stroke="url(#iMXTwBb)" class="gzl__90es"/></g><g filter="url(#i6mzNqr)"><path stroke="url(#i7E0Aeb)" class="zs_q6zreq"/></g><path fill="url(#iVYychc)" class="asa3oabfb"/><path fill="url(#iSzlxac)" class="asa3oabfb"/><path fill="url(#iETV5Bd)" class="asa3oabfb"/><path fill="url(#ibRvbbe)" class="asa3oabfb"/><defs><radialGradient id="i8tgWOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.032)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="jove3dblx"/><stop offset="1" class="azrq8dbhb"/></radialGradient><radialGradient id="ikT3wpb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.336 18.368)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="ipd3rHo" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.547)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ieUwNdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.087)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="iPR2xGd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.845)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="i8QjEsd" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.118)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="caco6ntri"/><stop offset="1" class="dgkitw09n"/></radialGradient><radialGradient id="iUeJ2Sb" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.712)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="t469b3jak"/><stop offset="1" class="qvoq5opiz"/></radialGradient><radialGradient id="iu5UMge" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.607)" gradientUnits="userSpaceOnUse"><stop class="vhhvj2t-s"/><stop offset="1" class="so34edl-m"/></radialGradient><radialGradient id="iNRX4zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.565)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="iQpddTg" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.855 22.55)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="iVuFPpe" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.342 12.627)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="gckwtd8pq"/><stop offset="1" class="sg_-x3gmw"/></radialGradient><radialGradient id="ivkbt6S" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.53 12.33)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="i5wZYne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.171 18.117)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="igATwqb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.878 17.729)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="is0WZfd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.837)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="iHTPxqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.15)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iCnPime" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.759)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="icubEce" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.93)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="iHJmVvb" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.683 2.269)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="idjB8bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.853)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="iwuX1jb" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.544)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="xu1e5_bcz"/><stop offset="1" class="jixz69llq"/></radialGradient><radialGradient id="ihRkukc" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -1.28125 .6632 1.76315 6.712 13.93)" gradientUnits="userSpaceOnUse"><stop class="idtxb7bhf"/><stop offset="1" class="fl8n3u57c"/></radialGradient><radialGradient id="iY3Gkce" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.056)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="krme1767b"/><stop offset="1" class="nkhjpg89n"/></radialGradient><radialGradient id="izlY3be" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.941)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="zxq4xrt3q"/><stop offset="1" class="suc174tfe"/></radialGradient><radialGradient id="ieRwBBw" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.218 7.58)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="iiAKlHe" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .802 7.932)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="iEW2KXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.936)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="ieJiSGR" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.373)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="iOobPcw" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.122 8.926)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="tjlv9x_9r"/><stop offset="1" class="z13dp2ohj"/></radialGradient><radialGradient id="iHOb1Sc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.486)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="uqxno_b8g"/><stop offset=".81" class="d4a71bwtp"/></radialGradient><radialGradient id="ipICnYc" cx="0" cy="0" r="1" gradientTransform="rotate(-104.504 15.36 1.222)scale(8.36833 2.71135)" gradientUnits="userSpaceOnUse"><stop class="g_v4sglua"/><stop offset="1" class="o67susxgp"/></radialGradient><radialGradient id="i2a8zYc" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.27 8.999)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="ip3ktqbqy"/><stop offset="1" class="whspc9bgn"/></radialGradient><radialGradient id="ixtAMxe" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.228)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="k1ssgpxxp"/><stop offset="1" class="dcaablbea"/></radialGradient><radialGradient id="iOJ29Xd" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.25 -14.134)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><radialGradient id="icJ6Fbd" cx="0" cy="0" r="1" gradientTransform="matrix(.79446 0 0 1.39031 9.974 5.999)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iL8GHlb" cx="0" cy="0" r="1" gradientTransform="matrix(.37426 -.27252 .31105 .42717 15.205 5.879)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iBuvpPb" cx="0" cy="0" r="1" gradientTransform="matrix(.3718 -.68384 .40026 .21762 15.018 6.37)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="ikKrIab" cx="0" cy="0" r="1" gradientTransform="matrix(.11738 .1162 -.14979 .15132 15.037 5.999)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="isZ2kwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.83059 -4.61517 0 13.093 4.486)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="vpd4dcexx"/><stop offset="1" class="upbi0xbpg"/></radialGradient><radialGradient id="iXsnT8X" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59174 .7283 0 13.941 5.423)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iuBTG6U" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.62967 .78305 0 11.878 5.408)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iTeEFwc" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 6.661 4.817)scale(2.53802 4.31613)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iUzVhJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.03025 -.84273 .41388 -.01486 10.982 4.435)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iXrATOc" cx="0" cy="0" r="1" gradientTransform="matrix(.38895 -.89026 .72608 .31722 14.793 5.212)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iuPPfcb" cx="0" cy="0" r="1" gradientTransform="matrix(.44945 .55769 -.4924 .39683 12.528 2.105)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="isluHLe" cx="0" cy="0" r="1" gradientTransform="matrix(.08211 .35457 -.58291 .135 13.194 2.105)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="ihNrjyc" cx="0" cy="0" r="1" gradientTransform="matrix(.32845 .40624 -.91022 .73593 10.912 2.887)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="ihRuR2w" cx="0" cy="0" r="1" gradientTransform="matrix(0 .40887 -.4838 0 13.866 5.84)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="im1g9we" cx="0" cy="0" r="1" gradientTransform="matrix(-.10497 -.13527 .18623 -.14452 13.762 5.728)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iA9LOnk" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4089 -.48383 0 11.89 5.84)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ihbIdRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0035 -.22363 .26881 -.0042 11.761 5.789)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVYychc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.438 3.74)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="ibRvbbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.266 3.209)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><filter id="ixO19Cd" width="7.486" height="8.65" x="14.87" y="7.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.447059 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="iOu2EIi" width="5.439" height="5.49" x="2.462" y="16.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="i9IXPgg" width="6.264" height="4.296" x="4.74" y="25.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.505882 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="iXXsvCd" width="5.105" height="3.176" x="4.74" y="26.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="i1QUBor" width="7.339" height="5.547" x="11.424" y="16.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="iFmojId" width="5.437" height="5.553" x="22.676" y="16.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="ixNhOQb" width="2.689" height="5.353" x="25.224" y="16.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="i5Duqle" width="8.098" height="6.294" x="5.657" y="8.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.466667 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.364706 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23234" result="effect2_innerShadow_3987_23234"/></filter><filter id="i8oh8ic" width="7.636" height="9.986" x="11.582" y="7.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.34902 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="izHhLre" width="2.625" height="5.367" x="19.763" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".25"/></filter><filter id="iYuurQa" width="3.404" height="3.248" x="18.396" y="8.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="igzl4ac" width="1.712" height="1.512" x="9.974" y="5.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="i6VnbVN" width="1.901" height="1.901" x="9.779" y="5.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".25"/></filter><filter id="iNuAy7b" width="1.762" height="1.762" x="14.281" y="4.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="ixeD6ov" width="1.901" height="1.901" x="14.086" y="5.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".25"/></filter><filter id="iqxa3wc" width="4.696" height="5.595" x="10.544" y="3.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="irBi0Od" width="5.705" height="3.741" x="10.027" y="2.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="ilXxPbe" width="2.297" height="2.714" x="11.623" y="5.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".375"/></filter><filter id="iHyGpne" width="1.05" height="1.414" x="12.354" y="5.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".05"/></filter><filter id="ieblFws" width="1.486" height="1.067" x="13.414" y="4.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="iQe0QkA" width="1.486" height="1.067" x="11.084" y="4.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23234"/></filter><filter id="i1VzxoF" width=".466" height=".425" x="13.479" y="5.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".05"/></filter><filter id="iZFR2Xb" width=".622" height=".632" x="13.804" y="5.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".1"/></filter><filter id="iJYuTje" width=".665" height=".69" x="11.793" y="5.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".1"/></filter><filter id="i9bj43d" width=".523" height=".428" x="11.506" y="5.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".05"/></filter><filter id="iBEJ9sv" width="1.137" height=".495" x="13.481" y="4.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".05"/></filter><filter id="i6mzNqr" width="1.172" height=".521" x="11.118" y="4.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23234" stdDeviation=".05"/></filter><linearGradient id="inFRzLc" x1="4.743" x2="6.868" y1="18.993" y2="21.118" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="i24w7He" x1="11.118" x2="8.993" y1="26.306" y2="25.556" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="iGYZ1ue" x1="8.915" x2="10.134" y1="25.306" y2="25.77" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="iforYlw" x1="5.181" x2="9.845" y1="27.212" y2="29.743" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="i0WLFfR" x1="7.524" x2="7.466" y1="28.142" y2="28.247" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="iuHFcTc" x1="21.97" x2="21.54" y1="21.134" y2="20.36" gradientUnits="userSpaceOnUse"><stop class="s6dne5bmb"/><stop offset="1" class="mur73_bqp"/></linearGradient><linearGradient id="ioiTMCb" x1="23.368" x2="23.009" y1="20.415" y2="19.681" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="iAwSFJb" x1="26.313" x2="26.114" y1="18.845" y2="18.931" gradientUnits="userSpaceOnUse"><stop offset=".244" class="jylqepbzd"/><stop offset="1" class="v2dwqfdba"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="iLp5Zne" x1="27.532" x2="25.439" y1="21.156" y2="16.279" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="i1VySRd" x1="26.269" x2="26.38" y1="18.974" y2="18.927" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="id3llJe" x1="10.73" x2="10.44" y1="6.125" y2="6.125" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="i01vLVd" x1="15.528" x2="15.158" y1="5.504" y2="6.653" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="is6lStb" x1="14.707" x2="11.249" y1="6.175" y2="6.69" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="ijbMCzc" x1="10.437" x2="11.484" y1="7.395" y2="7.259" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iYlYUFx" x1="10.679" x2="11.992" y1="5.878" y2="3.544" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="i4cs5qb" x1="12.488" x2="12.913" y1="6.473" y2="6.473" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="igmFgcr" x1="13.304" x2="12.84" y1="6.619" y2="6.613" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iV2nA4w" x1="12.967" x2="12.967" y1="6.955" y2="6.696" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="izhztpQ" x1="12.41" x2="12.607" y1="7.687" y2="7.375" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iBBrnKe" x1="14.218" x2="14.076" y1="5.714" y2="5.802" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKay8hb" x1="12.227" x2="12.085" y1="5.714" y2="5.802" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMXTwBb" x1="14.225" x2="14.035" y1="4.746" y2="4.357" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="i7E0Aeb" x1="11.823" x2="11.285" y1="4.688" y2="4.462" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iSzlxac" x1="9.821" x2="13.532" y1="3.927" y2="3.927" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="iETV5Bd" x1="13.594" x2="13.594" y1="4.271" y2="4.154" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-bouncing-ball-medium-light" /></template>
<style>
.aaqnz91xn {
  d: path("M23.563 19.826v-.778a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.247c-.766-1.312-1.607-1.505-2.042-1.52a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.256");
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.afwmdpbtl {
  cx: 10.73px;
  cy: 5.999px;
  r: 0.756px;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.asa3oabfb {
  d: path("M9.82 3.309a.1.1 0 0 1 .1-.1h5.926a.1.1 0 0 1 .1.1v.862a.1.1 0 0 1-.1.1H9.92a.1.1 0 0 1-.1-.1z");
}

.atpccsbtm {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m15.06 3.066l.195.097a.89.89 0 0 1 .461.965l-.267 1.377c-.024.142-.117.237-.259.241h-.008s.024-.41.049-.652c.02-.196-.015-.256-.194-.434a.57.57 0 0 1-.17-.387v-.386a.26.26 0 0 0-.195-.242a7.4 7.4 0 0 0-1.772-.193c-.875 0-1.482.121-1.773.193a.235.235 0 0 0-.194.242v.386a.48.48 0 0 1-.17.387l-.073.072c-.097.072-.146.217-.146.338c.024.266.049.652.049.652h-.023a.29.29 0 0 1-.269-.241l-.267-1.377a.92.92 0 0 1 .486-.941l.194-.097c.121-.072.243-.169.364-.266l.437-.458a.89.89 0 0 1 .996-.145c.243.072.51.072.753 0c.364-.12.777-.024 1.068.241l.365.362c.097.121.218.194.364.266");
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.azrq8dbhb {
  stop-color: var(--svg-color--b86660, #B86660);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bq_62abtc {
  stop-color: var(--svg-color--c9786e, #C9786E);
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.bzw267bym {
  d: path("m10.57 5.721l.023.001s-.024-.386-.049-.652c0-.12.049-.266.146-.338l.073-.072a.48.48 0 0 0 .17-.387v-.386c0-.12.073-.217.194-.242c.291-.072.899-.193 1.773-.193s1.481.121 1.772.193a.26.26 0 0 1 .195.242v.386c0 .145.073.29.17.387c.227.159.213.246.194.434a21 21 0 0 0-.049.652h.009l-.12 1.792c-.073.801-.703 1.36-1.454 1.36h-1.453c-.776 0-1.381-.559-1.454-1.36z");
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.caco6ntri {
  stop-color: var(--svg-color--edb29a, #EDB29A);
}

.ciy4kid0r {
  d: path("M11.89 5.474a.404.404 0 0 0-.39.51h.78a.407.407 0 0 0-.391-.51");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
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

.dcaablbea {
  stop-color: var(--svg-color--ddac86, #DDAC86);
  stop-opacity: 0;
}

.dgkitw09n {
  stop-color: var(--svg-color--c2886c, #C2886C);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.dq_1-7o5n {
  fill: var(--svg-color--edb791, #EDB791);
  d: path("M15.216 10.033q.558-.014 1.474.058c.827.065 1.691.196 2.138.531c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.822.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.e_wjd0bor {
  cx: 15.037px;
  cy: 5.999px;
  r: 0.45px;
  fill: var(--svg-color--d79e81, #D79E81);
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

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.efzf2zbap {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.666c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f6rtlablh {
  d: path("M12.962 17.462c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.239l-3.085 1.898c-.242.149-.512.239-.73.067c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.699 1.148-1.382 1.265-1.726");
}

.fl8n3u57c {
  stop-color: var(--svg-color--c48b6f, #C48B6F);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.ft5dv1b6b {
  fill: none;
}

.g_v4sglua {
  stop-color: var(--svg-color--5290df, #5290DF);
}

.g0kn9gb3f {
  stop-color: var(--svg-color--b391c2, #B391C2);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.gbgug8b6d {
  fill: var(--svg-color--ffc9a7, #FFC9A7);
  d: path("M11.657 11.712c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.805 1.296-.828h2.438c.386.577.634 1.595.744 2.24a4 4 0 0 0 .145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.392c-.423-1.314-.893-3.615-1.107-4.968");
}

.gc9u7lbfl {
  stop-color: var(--svg-color--53adfa, #53ADFA);
  stop-opacity: 0;
}

.gckwtd8pq {
  stop-color: var(--svg-color--e3ab8f, #E3AB8F);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
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

.gzl__90es {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.631 4.702c.195-.034.574-.025.837.18");
}

.h5ok44qlk {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.311a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.225c.418.266.704.577.875.931c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.491-1.734-2.009a4 4 0 0 0-.741-.378");
}

.h87jn4bfj {
  fill: var(--svg-color--000, #000);
  d: path("M13.635 5.878a.23.23 0 0 1 .232-.231a.23.23 0 0 1 .205.337h-.41a.2.2 0 0 1-.027-.106");
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hq7x2mbti {
  d: path("M13.867 5.474a.404.404 0 0 1 .389.51h-.78a.406.406 0 0 1 .391-.51");
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.i-cfc4c3e {
  d: path("m22.282 20.87l.03-.016l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i80p6sbrk {
  d: path("M25.282 16.56a.1.1 0 0 1 .044-.125l.091-.051a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.062a.15.15 0 0 1-.187-.084z");
}

.idtxb7bhf {
  stop-color: var(--svg-color--dfa98a, #DFA98A);
}

.ip3ktqbqy {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j2_wuxbny {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m11.17 4.767l.001-.001l.002-.002l.006-.004l.016-.012l.054-.037a1.28 1.28 0 0 1 .866-.167a.242.242 0 0 1-.076.478a.8.8 0 0 0-.533.099l-.029.02a.242.242 0 0 1-.307-.374");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jixz69llq {
  stop-color: var(--svg-color--3c93f1, #3C93F1);
}

.jove3dblx {
  stop-color: var(--svg-color--c48770, #C48770);
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jrg-8z1gq {
  cx: 15.037px;
  cy: 5.999px;
  r: 0.45px;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jy7vazb8a {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
}

.jylqepbzd {
  stop-color: var(--svg-color--4079dd, #4079DD);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k1ssgpxxp {
  stop-color: var(--svg-color--ddac86, #DDAC86);
}

.kcb6yjbmm {
  d: path("m11.432 25.157l-.853 2.117l-1.977-.968c.176-.463.47-1.251.755-2.041z");
}

.krme1767b {
  stop-color: var(--svg-color--b56e59, #B56E59);
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lklg-abmk {
  cx: 11.768px;
  cy: 5.647px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.176px;
  ry: 0.089px;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.m54s94buf {
  fill: var(--svg-color--fac6a5, #FAC6A5);
  d: path("M20.857 14.176c.475-1.675-.198-3.355-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.617z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mq70z9bkg {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.96 5.35c.296 0 .546.205.614.48a.124.124 0 0 1-.122.154h-1.01a.104.104 0 0 1-.102-.123a.63.63 0 0 1 .62-.51");
}

.mur73_bqp {
  stop-color: var(--svg-color--d89d91, #D89D91);
  stop-opacity: 0;
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.n5gdkvxgq {
  d: path("m11 20.61l.673-.75l2.336 1.86c-.07.047-.328.208-.797.477c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.97c.326-.858 1.06-2.837 1.391-3.874c.331-1.038.81-1.646 1.008-1.82");
}

.nh2ifcqxe {
  cx: 11.768px;
  cy: 5.647px;
  rx: 0.176px;
  ry: 0.089px;
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

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o67susxgp {
  stop-color: var(--svg-color--51b1ff, #51B1FF);
  stop-opacity: 0;
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odhno-5ym {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M6.293 14.785c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.314c.211-.516.904-1.148 2.065-1.025a.415.415 0 1 1-.088.825");
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.p412jwbbq {
  fill: var(--svg-color--000, #000);
  d: path("M12.121 5.878a.23.23 0 0 0-.231-.231a.23.23 0 0 0-.206.337h.41a.23.23 0 0 0 .027-.106");
}

.p73626bhv {
  d: path("m12.706 5.87l-.24.769a.244.244 0 0 0 .235.316h.356c.167 0 .285-.16.236-.316l-.24-.77c-.052-.17-.293-.17-.347 0");
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pid-4m06y {
  cx: 5.18px;
  cy: 19.353px;
  r: 2.721px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.pyuc6d_7f {
  cx: 15.037px;
  cy: 5.999px;
  r: 0.756px;
}

.q_nak1h4o {
  d: path("m15.06 3.066l.195.097a.89.89 0 0 1 .461.965l-.267 1.377c-.024.142-.117.237-.259.241h-.008s.024-.41.049-.652c.02-.196-.015-.256-.194-.434a.57.57 0 0 1-.17-.387v-.386a.26.26 0 0 0-.195-.242a7.4 7.4 0 0 0-1.772-.193c-.875 0-1.482.121-1.773.193a.235.235 0 0 0-.194.242v.386a.48.48 0 0 1-.17.387l-.073.072c-.097.072-.146.217-.146.338c.024.266.049.652.049.652h-.023a.29.29 0 0 1-.269-.241l-.267-1.377a.92.92 0 0 1 .486-.941l.194-.097c.121-.072.243-.169.364-.266l.437-.458a.89.89 0 0 1 .996-.145c.243.072.51.072.753 0c.364-.12.777-.024 1.068.241l.365.362c.097.121.218.194.364.266");
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvoq5opiz {
  stop-color: var(--svg-color--b37381, #B37381);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r-cw1cber {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.796 5.35a.63.63 0 0 0-.613.48c-.02.08.04.154.12.154h1.01a.104.104 0 0 0 .104-.123a.634.634 0 0 0-.621-.51");
}

.r0fswm2la {
  d: path("M12.259 5.83c0-.13-.107-.217-.135-.244l-.13.127l.08.163z");
}

.rch19fi1w {
  cx: 10.73px;
  cy: 5.999px;
  r: 0.45px;
}

.rpzm12bqg {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.638 7.39a.11.11 0 0 0-.013-.144a.12.12 0 0 0-.141-.024c-.175.091-.38.144-.605.144a1.3 1.3 0 0 1-.604-.143a.12.12 0 0 0-.142.024a.11.11 0 0 0-.012.142m1.517 0l-.042-.028zm0 0a.9.9 0 0 1-.759.405a.9.9 0 0 1-.758-.405m0 0v.001l.042-.029m-.042.028l.042-.028m0 0c.151.23.415.383.716.383s.565-.153.717-.383c.039-.058-.028-.126-.09-.094a1.35 1.35 0 0 1-.627.149a1.36 1.36 0 0 1-.627-.15c-.062-.03-.128.04-.09.095Z");
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s5515db0i {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M5.125 14.604c-.293.2-.45.423-.481.5a.415.415 0 0 1-.768-.315c.11-.27.397-.609.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.s6dne5bmb {
  stop-color: var(--svg-color--ba7b8a, #BA7B8A);
}

.saa1azb9d {
  d: path("M11.657 11.712c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.805 1.296-.828h2.438c.386.577.634 1.595.744 2.24a4 4 0 0 0 .145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.392c-.423-1.314-.893-3.615-1.107-4.968");
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.sg_-x3gmw {
  stop-color: var(--svg-color--ce9878, #CE9878);
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

.suc174tfe {
  stop-color: var(--svg-color--ebaf94, #EBAF94);
}

.sw4x5xbtf {
  d: path("M13.837 5.56c.029.038-.031.085-.1.136c-.068.051-.119.087-.148.049c-.028-.039.004-.112.072-.163c.069-.05.147-.061.176-.023");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t469b3jak {
  stop-color: var(--svg-color--b37381, #B37381);
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

.t90z1wkyp {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M6.322 13.692c-.775-.133-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.tjlv9x_9r {
  stop-color: var(--svg-color--f1bda3, #F1BDA3);
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tt3cvqbuk {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m12.706 5.87l-.24.769a.244.244 0 0 0 .235.316h.356c.167 0 .285-.16.236-.316l-.24-.77c-.052-.17-.293-.17-.347 0");
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.upbi0xbpg {
  stop-color: var(--svg-color--9f6e75, #9F6E75);
}

.uqcxmbcfb {
  fill-rule: evenodd;
  d: path("M6.322 13.692c-.775-.133-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
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

.uwcvcu_5g {
  stop-color: var(--svg-color--c9786e, #C9786E);
  stop-opacity: 0;
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v2dwqfdba {
  stop-color: var(--svg-color--4079dd, #4079DD);
  stop-opacity: 0;
}

.v300w2bja {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.837 5.56c.029.038-.031.085-.1.136c-.068.051-.119.087-.148.049c-.028-.039.004-.112.072-.163c.069-.05.147-.061.176-.023");
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
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

.vpd4dcexx {
  stop-color: var(--svg-color--c88d87, #C88D87);
  stop-opacity: 0;
}

.vqjcz4uub {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m14.563 4.767l-.001-.001l-.002-.002l-.006-.004l-.07-.049a1.28 1.28 0 0 0-.866-.167a.242.242 0 1 0 .076.478a.8.8 0 0 1 .534.099l.028.02a.242.242 0 0 0 .307-.374");
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
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

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.wxv9r3nmp {
  d: path("M11.884 8.917c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.273-.238 1.05.25 1.688c.373.486.812.597 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.198.014-2.233.227-2.795");
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xu1e5_bcz {
  stop-color: var(--svg-color--3c92ef, #3C92EF);
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ya6ed1s7r {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m12.755 5.943l-.372.77c-.046.158.065.316.221.316h.334c.156 0 .267-.16.22-.316l-.225-.77c-.048-.17-.128-.17-.178 0");
}

.yfvcl8bli {
  fill-rule: evenodd;
  d: path("M6.293 14.785c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.314c.211-.516.904-1.148 2.065-1.025a.415.415 0 1 1-.088.825");
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yljh9-iht {
  fill-rule: evenodd;
  d: path("M5.23 14.112c-.306.178-.45.37-.473.425a.415.415 0 1 1-.768-.314c.12-.291.436-.603.824-.829a2.86 2.86 0 0 1 1.58-.382a.415.415 0 1 1-.042.83a2.03 2.03 0 0 0-1.12.27");
}

.yo6ebkk5b {
  d: path("M19.324 8.311a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.225c.418.266.704.577.875.931c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.491-1.734-2.009a4 4 0 0 0-.741-.378");
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z_1m3ccsq {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M5.23 14.112c-.306.178-.45.37-.473.425a.415.415 0 1 1-.768-.314c.12-.291.436-.603.824-.829a2.86 2.86 0 0 1 1.58-.382a.415.415 0 1 1-.042.83a2.03 2.03 0 0 0-1.12.27");
}

.z0yiw70fd {
  fill-rule: evenodd;
  d: path("M5.125 14.604c-.293.2-.45.423-.481.5a.415.415 0 0 1-.768-.315c.11-.27.397-.609.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.z13dp2ohj {
  stop-color: var(--svg-color--e1ac8b, #E1AC8B);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zs_q6zreq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.268 4.936c.148-.13.472-.268.873-.204");
}

.zxhxo6bwd {
  d: path("M14.226 5.825a.4.4 0 0 0-.104-.21l-.118.13l.053.103z");
}

.zxq4xrt3q {
  stop-color: var(--svg-color--ebaf94, #EBAF94);
  stop-opacity: 0;
}

</style>
