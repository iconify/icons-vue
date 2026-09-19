<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iqnuVDe)"><path fill="url(#iC90rcx)" clip-rule="evenodd" class="fv9d0fb4m"/><path fill="url(#iOWciBe)" clip-rule="evenodd" class="fv9d0fb4m"/><path fill="url(#i6E1mFe)" clip-rule="evenodd" class="fv9d0fb4m"/></g><path fill="url(#iDFcmwc)" clip-rule="evenodd" class="fv9d0fb4m"/><path class="godrk_bmy"/><path class="fn710pb-f"/><path class="sfel_0bwf"/><path fill="url(#itAv7mc)" class="kt3lmyn-z"/><path fill="url(#iPx204b)" class="kt3lmyn-z"/><path fill="url(#iF2nVcd)" class="kt3lmyn-z"/><path class="lzdxjachy"/><path fill="url(#ivcdg1b)" class="xls38_2mk"/><path fill="url(#irFvdDd)" class="xls38_2mk"/><path fill="url(#iwsXT7b)" class="xls38_2mk"/><path class="tv19b1bat"/><path fill="url(#iqqfBIO)" class="z-i44bwbr"/><path fill="url(#ilFN9zc)" class="z-i44bwbr"/><path fill="url(#iyZgaOd)" class="z-i44bwbr"/><path class="a475j9bqy"/><path fill="url(#inJCiKd)" class="wluhrxbrv"/><path fill="url(#iv6sspe)" class="wluhrxbrv"/><g filter="url(#iFpCD6B)"><path class="c6h0wqbcg"/></g><path fill="url(#itcTqpH)" class="zs29d05ot"/><path fill="url(#iaAzUMc)" class="zs29d05ot"/><path fill="url(#ih6M9If)" class="zs29d05ot"/><path fill="url(#i4ryrYb)" class="zs29d05ot"/><path fill="url(#iwOnWVd)" class="zs29d05ot"/><g filter="url(#iLBSIjc)"><path fill="url(#iKvUG8d)" class="pzhfo7gff"/><path fill="url(#iFT9Mjd)" class="pzhfo7gff"/></g><path fill="url(#iXrCLBb)" class="pzhfo7gff"/><path fill="url(#i4gNiIc)" class="pzhfo7gff"/><path fill="url(#i7d7wXb)" class="l8l04acls"/><g filter="url(#irMufoe)"><path class="n_d3k6bij"/></g><path fill="url(#iAaybve)" class="of2wd6_hn"/><path fill="url(#iS8Yx0d)" class="of2wd6_hn"/><g filter="url(#iX3sQxc)"><path class="otkoo8bst"/></g><path fill="url(#i7pTYXa)" class="bhcwzdbgh"/><g filter="url(#iRZx60d)"><path fill="url(#iNFd1ub)" class="wpp3rccyx"/></g><g filter="url(#imcpk5c)"><path class="bf8uc_bgm"/><path fill="url(#iC6hNub)" class="hpdr4hbsc"/></g><g filter="url(#idM6Sdb)"><path class="de5qrkb4o"/><path fill="url(#iIRltoc)" class="tys7vacrh"/></g><g filter="url(#iWmjOwb)"><path fill="url(#iEuMRGc)" class="sd-zocbbe"/><path fill="url(#ib2USph)" class="sd-zocbbe"/><path fill="url(#irp6IZc)" class="sd-zocbbe"/><path fill="url(#i24bH5d)" class="sd-zocbbe"/><path fill="url(#iCAYfad)" class="sd-zocbbe"/><path fill="url(#i6ppe6c)" class="sd-zocbbe"/><path fill="url(#ikK0cBb)" class="sd-zocbbe"/></g><path fill="url(#ip17qee)" class="sd-zocbbe"/><g filter="url(#ijzvBcd)"><path class="t-5rj7bku"/></g><g filter="url(#ixLHFLd)"><path fill="url(#iLOkfVr)" class="z2ay7bcdw"/><path fill="url(#iAprIzd)" class="z2ay7bcdw"/><path fill="url(#iBqVSGe)" class="z2ay7bcdw"/><path fill="url(#iCRVfRd)" class="z2ay7bcdw"/></g><g filter="url(#iGrqHzb)"><path stroke="url(#iPAlolb)" class="rrmnl8a6d"/></g><path class="u--jko-la"/><g filter="url(#ixoOMyd)"><path class="z23jy_b6r"/></g><g filter="url(#ioS6wec)"><path class="y2jzj52xi"/></g><g filter="url(#ipeDsBo)"><path class="deoyg1bko"/></g><g filter="url(#iMm6pMb)"><path clip-rule="evenodd" class="gjbt50r5i"/></g><path class="s9q3aubtg"/><path fill="url(#iOAcVie)" class="xfmiyfbup"/><path class="gv4ki33ax"/><g filter="url(#inHBH1b)"><path class="uccst6b8z"/><path fill="url(#iM24jqc)" class="pny907xds"/></g><g filter="url(#i7UD6Cb)"><path fill="url(#ifY88Wb)" class="bp147lcsz"/></g><path class="u9lz71bmu"/><path fill="url(#i4H2vne)" class="fkoi38byl"/><path class="wwxifibwx"/><g filter="url(#iTF1HMk)"><path fill="url(#i1qd6Yb)" class="nwew1lnuw"/></g><g filter="url(#iSLd6Ae)"><ellipse transform="rotate(-27.914 14.93 5.462)" class="s0mfety7t"/><ellipse fill="url(#i6FI4jd)" transform="rotate(-27.914 14.93 5.462)" class="i0b1bhbaw"/></g><g filter="url(#iCMqdNV)"><path class="mng8bxtzz"/></g><g filter="url(#iPrQrfc)"><path class="c5_yd6bmo"/></g><g filter="url(#i0W9voc)"><path fill="url(#iKQN4Wd)" class="u6spyceik"/><path fill="url(#iR2ikRd)" class="u6spyceik"/></g><g filter="url(#i1cMNuc)"><path fill="url(#ii9dORd)" class="goynr98wh"/><path fill="url(#iJSumBe)" class="goynr98wh"/><path fill="url(#i3b579t)" class="goynr98wh"/></g><g filter="url(#iKNffKd)"><path stroke="url(#iYvf3yd)" class="ec51tcbeh"/></g><defs><radialGradient id="iC90rcx" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31245 6.43752 -6.1387 -2.2051 18.08 3.089)" gradientUnits="userSpaceOnUse"><stop offset=".497" class="ohh9pqskr"/><stop offset=".8" class="r46shilgf"/></radialGradient><radialGradient id="iOWciBe" cx="0" cy="0" r="1" gradientTransform="rotate(-63.435 11 -8.593)scale(1.17044 .76865)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="sireaor_n"/><stop offset="1" class="f5t9rhp5t"/></radialGradient><radialGradient id="i6E1mFe" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 .89063 -2.0899 1.4299 14.736 2.557)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="bn0n3qbkc"/><stop offset="1" class="eqppp8b3o"/></radialGradient><radialGradient id="itAv7mc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.357 16.525)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="hv_q7gbew"/><stop offset="1" class="o5yx0rbao"/></radialGradient><radialGradient id="iPx204b" cx="0" cy="0" r="1" gradientTransform="matrix(.125 3.21875 -.73141 .0284 13.279 16.792)" gradientUnits="userSpaceOnUse"><stop offset=".022" class="se31mfapw"/><stop offset="1" class="j7o0jsb0d"/></radialGradient><radialGradient id="iF2nVcd" cx="0" cy="0" r="1" gradientTransform="rotate(-104.351 14.384 5.144)scale(2.04829 1.02534)" gradientUnits="userSpaceOnUse"><stop class="ef54lsb2t"/><stop offset="1" class="ekf73n8ha"/></radialGradient><radialGradient id="ivcdg1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.872 16.525)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="zs8fg1bme"/><stop offset="1" class="slh_g2biw"/></radialGradient><radialGradient id="irFvdDd" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 0 0 4.57812 18.67 17.042)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="vkmdc3sjj"/><stop offset="1" class="cw7ntv66c"/></radialGradient><radialGradient id="iwsXT7b" cx="0" cy="0" r="1" gradientTransform="rotate(-71.25 23.752 -3.058)scale(1.79857 .49047)" gradientUnits="userSpaceOnUse"><stop class="yn315pfzg"/><stop offset="1" class="le_psun2r"/></radialGradient><radialGradient id="iqqfBIO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98267 0 0 -3.69141 13.513 12.417)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="lr6ezac3g"/><stop offset="1" class="qb-zcep5b"/></radialGradient><radialGradient id="ilFN9zc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.562 8.725)" gradientUnits="userSpaceOnUse"><stop class="oyvuzabcb"/><stop offset="1" class="n3qwnccvd"/></radialGradient><radialGradient id="inJCiKd" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.3125 1.2963 3.62963 18.794 11.87)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="j-lpq16bn"/><stop offset="1" class="a6e6h5zrw"/></radialGradient><radialGradient id="ih6M9If" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16 17.995)" gradientUnits="userSpaceOnUse"><stop class="rwlxembxd"/><stop offset="1" class="oig4whb0o"/></radialGradient><radialGradient id="i4ryrYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.075 28.358)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iwOnWVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.794 28.448)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iFT9Mjd" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.446 8.174)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="gr1u6n3xs"/><stop offset="1" class="p5rei_uzm"/></radialGradient><radialGradient id="i4gNiIc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23437 -7.85938 10.48665 -1.647 16.423 15.839)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="y9klw1bbn"/><stop offset=".967" class="q1_kb-bpc"/></radialGradient><radialGradient id="i7d7wXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.11133 -1.40894 0 16 8.38)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="w4burac2j"/><stop offset="1" class="tpyprqb_v"/></radialGradient><radialGradient id="iS8Yx0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.566 29.308)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="iNFd1ub" cx="0" cy="0" r="1" gradientTransform="matrix(1.08587 -.49358 .60263 1.3258 17.762 5.956)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iC6hNub" cx="0" cy="0" r="1" gradientTransform="rotate(-20.297 25.393 -47.356)scale(.56914)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iIRltoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46859 0 0 -.44823 13.964 5.764)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iEuMRGc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.83723 1.30834 -1.7512 -3.79758 17.247 5.53)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="rznujpbxa"/></radialGradient><radialGradient id="ib2USph" cx="0" cy="0" r="1" gradientTransform="matrix(-.92039 .48683 -.41304 -.78088 16.829 5.834)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="irp6IZc" cx="0" cy="0" r="1" gradientTransform="matrix(.36511 -1.76472 2.2391 .46326 15.05 8.489)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="i24bH5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.24601 -5.15554 0 15.886 5.319)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="ajxs5ri3z"/><stop offset="1" class="b97fdsb_t"/></radialGradient><radialGradient id="iCAYfad" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36562 .65418 -1.1263 -4.07288 16.274 6.253)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="i6ppe6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50203 .61613 0 17.004 5.347)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="ikK0cBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59331 .67997 0 15.163 5.386)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="ip17qee" cx="0" cy="0" r="1" gradientTransform="matrix(-.58762 0 0 -1.93445 18.223 5.996)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iAprIzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30427 -1.06872 .61154 -.1741 16.343 6.314)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iOAcVie" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35354 -.56234 0 16.951 5.504)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iM24jqc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 9.783 -1.356)scale(.1649 .22702)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4H2vne" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35354 -.56235 0 15.048 5.504)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i6FI4jd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00337 -.21536 .25888 -.00405 14.923 5.6)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKQN4Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4917 1.80611 -.7877 -.65058 14.815 2.731)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iR2ikRd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3536 .96702 -.47791 -.66897 14.754 2.971)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="ii9dORd" cx="0" cy="0" r="1" gradientTransform="rotate(115.63 7.692 6.39)scale(2.20403 3.12936)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iJSumBe" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.503 7.835)scale(1.50074 3.14507)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="i3b579t" cx="0" cy="0" r="1" gradientTransform="rotate(-117.848 9.825 -2.36)scale(3.19101 2.85257)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="iqnuVDe" width="6.802" height="6.802" x="12.724" y="1.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_168"/></filter><filter id="iFpCD6B" width="6.169" height="12.453" x="13.016" y="15.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.360784 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_168"/></filter><filter id="iLBSIjc" width="6.417" height="7.694" x="12.941" y="8.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.470588 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_168"/></filter><filter id="irMufoe" width="3.316" height="1.848" x="12.434" y="28.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_168"/></filter><filter id="iX3sQxc" width="6.594" height="13.766" x="12.841" y="15.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".5"/></filter><filter id="iRZx60d" width="1.404" height="1.654" x="17.404" y="4.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_168"/></filter><filter id="imcpk5c" width="1.937" height="1.937" x="17.137" y="4.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".25"/></filter><filter id="idM6Sdb" width="1.437" height="1.437" x="13.246" y="5.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".125"/></filter><filter id="iWmjOwb" width="4.446" height="4.845" x="13.777" y="3.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_168"/></filter><filter id="ijzvBcd" width="1.819" height="2.17" x="15.02" y="5.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".25"/></filter><filter id="ixLHFLd" width=".919" height="1.27" x="15.541" y="5.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".025"/></filter><filter id="iGrqHzb" width="1.841" height=".891" x="15.08" y="6.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".05"/></filter><filter id="ixoOMyd" width="1.422" height=".561" x="16.298" y="5.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_168"/></filter><filter id="ioS6wec" width="1.422" height=".561" x="14.28" y="5.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_168"/></filter><filter id="ipeDsBo" width="1.183" height=".589" x="14.339" y="4.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_168"/></filter><filter id="iMm6pMb" width="1.183" height=".589" x="16.702" y="4.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_168"/></filter><filter id="inHBH1b" width=".456" height=".416" x="16.575" y="5.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".05"/></filter><filter id="i7UD6Cb" width=".613" height=".623" x="16.885" y="5.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".1"/></filter><filter id="iTF1HMk" width=".655" height=".678" x="14.947" y="5.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".1"/></filter><filter id="iSLd6Ae" width=".511" height=".42" x="14.674" y="5.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".05"/></filter><filter id="iCMqdNV" width="1.024" height=".465" x="16.696" y="4.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".05"/></filter><filter id="iPrQrfc" width="1.024" height=".465" x="14.319" y="4.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".05"/></filter><filter id="i0W9voc" width="2.021" height="2.12" x="13.151" y="2.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".125"/></filter><filter id="i1cMNuc" width="3.971" height="2.603" x="14.512" y="2.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".075"/></filter><filter id="iKNffKd" width=".837" height="1.345" x="14.439" y="2.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_168" stdDeviation=".125"/></filter><linearGradient id="iDFcmwc" x1="16" x2="16" y1="8.932" y2="8.057" gradientUnits="userSpaceOnUse"><stop class="pt-vh3uhx"/><stop offset="1" class="qh1nfob4r"/></linearGradient><linearGradient id="iyZgaOd" x1="12.466" x2="12.466" y1="12.675" y2="12.198" gradientUnits="userSpaceOnUse"><stop class="iohq-acuq"/><stop offset="1" class="nja5v6b8m"/></linearGradient><linearGradient id="iv6sspe" x1="19.747" x2="19.747" y1="12.675" y2="12.436" gradientUnits="userSpaceOnUse"><stop class="vmu71vpaa"/><stop offset="1" class="j7e_afboq"/></linearGradient><linearGradient id="itcTqpH" x1="13.341" x2="13.568" y1="24.12" y2="24.112" gradientUnits="userSpaceOnUse"><stop class="yaaat27jw"/><stop offset="1" class="jursh_bcv"/></linearGradient><linearGradient id="iaAzUMc" x1="16" x2="16" y1="15.905" y2="16.339" gradientUnits="userSpaceOnUse"><stop class="j3c7jv70r"/><stop offset="1" class="y3uayvb5s"/></linearGradient><linearGradient id="iKvUG8d" x1="16" x2="16" y1="8.995" y2="15.956" gradientUnits="userSpaceOnUse"><stop class="ydvpfnbad"/><stop offset="1" class="puz0v9hbo"/></linearGradient><linearGradient id="iXrCLBb" x1="17.173" x2="17.173" y1="15.956" y2="15.62" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lq6trp79k"/><stop offset="1" class="xy-lxi48h"/></linearGradient><linearGradient id="iAaybve" x1="18.247" x2="16.5" y1="29.62" y2="29.417" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="i7pTYXa" x1="13.254" x2="14.545" y1="5.803" y2="5.803" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iLOkfVr" x1="16" x2="16" y1="6.654" y2="5.484" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iBqVSGe" x1="15.544" x2="15.916" y1="6.321" y2="6.367" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iCRVfRd" x1="16" x2="16" y1="6.694" y2="6.428" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iPAlolb" x1="15.682" x2="15.88" y1="7.338" y2="6.958" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ifY88Wb" x1="17.291" x2="17.154" y1="5.527" y2="5.611" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1qd6Yb" x1="15.371" x2="15.235" y1="5.527" y2="5.611" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYvf3yd" x1="14.739" x2="14.976" y1="3.06" y2="3.615" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-standing" /></template>
<style>
.a475j9bqy {
  fill: var(--svg-color--957fc5, #957FC5);
  d: path("M20.468 12.554c-.487-2.254-1.629-3.333-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.12");
}

.a6e6h5zrw {
  stop-color: var(--svg-color--8065b2, #8065B2);
  stop-opacity: 0;
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.b97fdsb_t {
  stop-color: var(--svg-color--d58820, #D58820);
}

.bf8uc_bgm {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M18.106 6.233a.469.469 0 1 0 0-.937a.469.469 0 0 0 0 .937");
}

.bhcwzdbgh {
  d: path("M13.956 6.467a.702.702 0 1 0 0-1.404a.702.702 0 0 0 0 1.404");
}

.bn0n3qbkc {
  stop-color: var(--svg-color--cc9f38, #CC9F38);
}

.bp147lcsz {
  d: path("M17.299 5.633a.36.36 0 0 0-.1-.2l-.114.123l.051.1z");
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.c5_yd6bmo {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.192 4.73a1.04 1.04 0 0 0-.723.15");
}

.c6h0wqbcg {
  fill: var(--svg-color--a2859a, #A2859A);
  d: path("m13.016 15.905l.484 12.453h2l.238-9.523c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.cw7ntv66c {
  stop-color: var(--svg-color--d0910c, #D0910C);
  stop-opacity: 0;
}

.de5qrkb4o {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M13.964 6.233a.469.469 0 1 0 0-.937a.469.469 0 0 0 0 .937");
}

.deoyg1bko {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m14.518 4.989l-.002.001a.117.117 0 0 1-.12-.2v-.001h.002l.004-.003l.014-.008l.05-.026c.044-.02.105-.046.18-.07c.148-.048.355-.087.579-.048a.117.117 0 0 1-.04.23a1 1 0 0 0-.468.04a1 1 0 0 0-.19.08z");
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.ec51tcbeh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.739 2.91c.01.107.102.505.237.746");
}

.ef54lsb2t {
  stop-color: var(--svg-color--c2821c, #C2821C);
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.ekf73n8ha {
  stop-color: var(--svg-color--eda82d, #EDA82D);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eqppp8b3o {
  stop-color: var(--svg-color--cc9f38, #CC9F38);
  stop-opacity: 0;
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.f5t9rhp5t {
  stop-color: var(--svg-color--df7916, #DF7916);
  stop-opacity: 0;
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fkoi38byl {
  d: path("M15.047 5.296a.39.39 0 0 0-.375.491h.751a.392.392 0 0 0-.377-.491");
}

.fn710pb-f {
  fill: var(--svg-color--c78e18, #C78E18);
  d: path("M19.333 19.054a.22.22 0 0 0 .043-.239h.437l-.32.996c-.262.079-.54.051-.59-.113a.32.32 0 0 1 .074-.3a9 9 0 0 0 .355-.344");
}

.ft5dv1b6b {
  fill: none;
}

.fv9d0fb4m {
  fill-rule: evenodd;
  d: path("M19.135 6.38c.092-.19.14-.402.14-.623a1.4 1.4 0 0 0-.116-.57h.002a1.4 1.4 0 0 0-.123-.223v-.002c-.15-.23-.23-.499-.23-.772v-.005a1.44 1.44 0 0 0-1.44-1.439a.24.24 0 0 1-.198-.102a1.442 1.442 0 0 0-2.34 0a.25.25 0 0 1-.199.102h-.037a1.44 1.44 0 0 0-1.402 1.44v.004c0 .273-.08.543-.23.772v.002a1.44 1.44 0 0 0-.097 1.416a.22.22 0 0 1 0 .198a1.402 1.402 0 0 0 1.263 2.018h3.744a1.402 1.402 0 0 0 1.263-2.018a.22.22 0 0 1 0-.198m-5.349-1.166h-.005l.523 1.027c.053 1.223.53 0 1.696 0s1.674 1.361 1.727.139l.496-1.395c-.023-.543-.417-.581-.496-.581h-1.404a1.69 1.69 0 0 1-1.392-.73a.115.115 0 0 0-.201.022l-.036.084a1 1 0 0 1-.541.548l-.023.009c-.102.053-.344.213-.353.627l.005.134z");
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbt50r5i {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m17.628 4.79l-.06.1za.117.117 0 0 1-.12.2l-.002-.001l-.01-.005l-.04-.02a1 1 0 0 0-.149-.06a1 1 0 0 0-.467-.04a.117.117 0 0 1-.041-.23c.224-.04.431 0 .58.048a1.4 1.4 0 0 1 .243.104l.004.002l.001.001z");
}

.godrk_bmy {
  fill: var(--svg-color--bf8011, #BF8011);
  d: path("M12.668 19.054a.22.22 0 0 1-.043-.239h-.438l.32.996c.262.079.54.051.59-.113a.32.32 0 0 0-.074-.3a9 9 0 0 1-.355-.344");
}

.goynr98wh {
  d: path("M15.737 2.366c-.494-.11-1.024.417-1.075.6c.673 1.579 1.706 1.428 2.852 1.301c.686-.076.76.236.819.388c-.19-1.77-1.47-2.04-2.596-2.29");
}

.gr1u6n3xs {
  stop-color: var(--svg-color--a282d2, #A282D2);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gv4ki33ax {
  fill: var(--svg-color--000, #000);
  d: path("M16.73 5.685c0-.124.099-.223.223-.223a.222.222 0 0 1 .198.326h-.395a.2.2 0 0 1-.026-.103");
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.hpdr4hbsc {
  d: path("M18.106 6.233a.469.469 0 1 0 0-.937a.469.469 0 0 0 0 .937");
}

.hv_q7gbew {
  stop-color: var(--svg-color--e97a06, #E97A06);
}

.i0b1bhbaw {
  cx: 14.93px;
  cy: 5.462px;
  rx: 0.17px;
  ry: 0.086px;
}

.iohq-acuq {
  stop-color: var(--svg-color--684082, #684082);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j-lpq16bn {
  stop-color: var(--svg-color--674ea1, #674EA1);
}

.j3c7jv70r {
  stop-color: var(--svg-color--966d92, #966D92);
}

.j7e_afboq {
  stop-color: var(--svg-color--7055a4, #7055A4);
  stop-opacity: 0;
}

.j7o0jsb0d {
  stop-color: var(--svg-color--d58816, #D58816);
  stop-opacity: 0;
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jursh_bcv {
  stop-color: var(--svg-color--a5949b, #A5949B);
  stop-opacity: 0;
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kt3lmyn-z {
  d: path("M12.112 20.334c-.938-1.982-.769-6.258-.488-7.823h1.672c-.071 2.425.04 5.243.178 6.511c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.061.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.l8l04acls {
  d: path("M15.129 7.268h1.742V8.62a.871.871 0 0 1-1.742 0z");
}

.le_psun2r {
  stop-color: var(--svg-color--cc952b, #CC952B);
  stop-opacity: 0;
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lq6trp79k {
  stop-color: var(--svg-color--6c4a9f, #6C4A9F);
}

.lr6ezac3g {
  stop-color: var(--svg-color--84749d, #84749D);
  stop-opacity: 0;
}

.lzdxjachy {
  fill: var(--svg-color--ffcc2d, #FFCC2D);
  d: path("M19.888 20.334c.938-1.982.769-6.258.487-7.823h-1.671c.071 2.425-.156 5.253-.294 6.522a.29.29 0 0 0 .555.15l.116-.262a.183.183 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.061.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mng8bxtzz {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.846 4.73c.14-.035.49-.018.724.15");
}

.n_d3k6bij {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.434 29.714v.242H15.5v-1.598h-1.992c-.102.367-.574.754-.817.914a.54.54 0 0 0-.257.442");
}

.n3qwnccvd {
  stop-color: var(--svg-color--765887, #765887);
  stop-opacity: 0;
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nja5v6b8m {
  stop-color: var(--svg-color--6e498e, #6E498E);
  stop-opacity: 0;
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nwew1lnuw {
  d: path("M15.402 5.639c0-.126-.102-.21-.13-.234l-.125.12l.077.158z");
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o5yx0rbao {
  stop-color: var(--svg-color--f2a31f, #F2A31F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of2wd6_hn {
  d: path("M19.566 29.714v.242H16.5v-1.598h1.992c.102.367.574.754.817.914a.54.54 0 0 1 .257.442");
}

.ohh9pqskr {
  stop-color: var(--svg-color--ffd13c, #FFD13C);
}

.oig4whb0o {
  stop-color: var(--svg-color--867081, #867081);
  stop-opacity: 0;
}

.otkoo8bst {
  fill: var(--svg-color--ac99aa, #AC99AA);
  d: path("m13.841 16.276l.469 11.766h.812v-10.61h2.203v10.61h.672l.438-11.766z");
}

.oyvuzabcb {
  stop-color: var(--svg-color--765887, #765887);
}

.p5rei_uzm {
  stop-color: var(--svg-color--a282d2, #A282D2);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pny907xds {
  d: path("M16.924 5.378c.028.037-.03.083-.096.132c-.066.05-.115.084-.143.047s.004-.107.07-.157c.065-.049.141-.059.169-.022");
}

.pt-vh3uhx {
  stop-color: var(--svg-color--9d4a0e, #9D4A0E);
}

.puz0v9hbo {
  stop-color: var(--svg-color--825ab8, #825AB8);
}

.pzhfo7gff {
  d: path("M12.941 11.42a3.059 3.059 0 1 1 6.118 0v4.442a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q1_kb-bpc {
  stop-color: var(--svg-color--4f2646, #4F2646);
}

.qb-zcep5b {
  stop-color: var(--svg-color--84749d, #84749D);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qh1nfob4r {
  stop-color: var(--svg-color--e37123, #E37123);
  stop-opacity: 0;
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r46shilgf {
  stop-color: var(--svg-color--f79929, #F79929);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rrmnl8a6d {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16 7.035a1.3 1.3 0 0 1-.62-.15c-.061-.033-.127.038-.089.095a.843.843 0 0 0 1.418 0c.038-.06-.027-.128-.089-.096c-.18.096-.39.15-.62.15Z");
}

.rwlxembxd {
  stop-color: var(--svg-color--8560a3, #8560A3);
}

.rznujpbxa {
  stop-color: var(--svg-color--f0a024, #F0A024);
}

.s0mfety7t {
  cx: 14.93px;
  cy: 5.462px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.17px;
  ry: 0.086px;
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s9q3aubtg {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.043 5.177a.61.61 0 0 1 .591.462a.12.12 0 0 1-.117.149h-.973a.1.1 0 0 1-.099-.119a.61.61 0 0 1 .598-.492");
}

.sd-zocbbe {
  d: path("M13.78 5.214h.006l-.004-.116l-.005-.134c.009-.414.25-.574.354-.627l.022-.01l.022-.008c.233-.107.42-.294.52-.539l.035-.084a.115.115 0 0 1 .201-.022c.314.458.837.73 1.392.73h1.404c.079 0 .473.038.496.58l-.052 1.341c-.054 1.223-1.008 2.044-2.174 2.044s-2.12-.821-2.174-2.044z");
}

.se31mfapw {
  stop-color: var(--svg-color--ad6605, #AD6605);
}

.sfel_0bwf {
  fill: var(--svg-color--eaae34, #EAAE34);
  d: path("M12.112 20.334c-.938-1.982-.769-6.258-.488-7.823h1.672c-.071 2.425.04 5.243.178 6.511c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.061.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.sireaor_n {
  stop-color: var(--svg-color--df7916, #DF7916);
}

.slh_g2biw {
  stop-color: var(--svg-color--fcb726, #FCB726);
  stop-opacity: 0;
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t-5rj7bku {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.829 5.667l-.298.742a.235.235 0 0 0 .227.305h.343c.16 0 .274-.155.227-.305l-.232-.742c-.05-.164-.215-.164-.267 0");
}

.tpyprqb_v {
  stop-color: var(--svg-color--ffb614, #FFB614);
}

.tv19b1bat {
  fill: var(--svg-color--7c5897, #7C5897);
  d: path("M11.533 12.554c.486-2.254 1.628-3.333 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.12");
}

.tys7vacrh {
  d: path("M13.964 6.233a.469.469 0 1 0 0-.937a.469.469 0 0 0 0 .937");
}

.u--jko-la {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16 7.035a1.3 1.3 0 0 1-.62-.15c-.061-.033-.127.038-.089.095a.843.843 0 0 0 1.418 0c.038-.06-.027-.128-.089-.096c-.18.096-.39.15-.62.15");
}

.u6spyceik {
  d: path("M13.865 3.14c.27-.24.662-.243.88-.204l.176.563a.34.34 0 0 0-.296.103c-.199.55-.882.853-1.199.936c-.066-.651-.03-.98.439-1.397");
}

.u9lz71bmu {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.957 5.177a.61.61 0 0 0-.591.462a.12.12 0 0 0 .117.149h.973a.1.1 0 0 0 .1-.119a.61.61 0 0 0-.6-.492");
}

.uccst6b8z {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.924 5.378c.028.037-.03.083-.096.132c-.066.05-.115.084-.143.047s.004-.107.07-.157c.065-.049.141-.059.169-.022");
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vkmdc3sjj {
  stop-color: var(--svg-color--bc7a0b, #BC7A0B);
}

.vmu71vpaa {
  stop-color: var(--svg-color--6d4ca1, #6D4CA1);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w4burac2j {
  stop-color: var(--svg-color--fa9e1e, #FA9E1E);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wluhrxbrv {
  d: path("M20.468 12.554c-.487-2.254-1.629-3.333-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.12");
}

.wpp3rccyx {
  d: path("M18.106 6.467a.702.702 0 1 0 0-1.404a.702.702 0 0 0 0 1.404");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.wwxifibwx {
  fill: var(--svg-color--000, #000);
  d: path("M15.27 5.685a.22.22 0 0 0-.223-.223a.222.222 0 0 0-.198.326h.394a.2.2 0 0 0 .027-.103");
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.xfmiyfbup {
  d: path("M16.952 5.296a.39.39 0 0 1 .375.491h-.751a.39.39 0 0 1 .377-.491");
}

.xls38_2mk {
  d: path("M19.888 20.334c.938-1.982.769-6.258.487-7.823h-1.671c.071 2.425-.156 5.253-.294 6.522a.29.29 0 0 0 .555.15l.116-.262a.183.183 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.061.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.xy-lxi48h {
  stop-color: var(--svg-color--8761b9, #8761B9);
  stop-opacity: 0;
}

.y2jzj52xi {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.502 5.516c-.116-.203-.292-.364-.67-.364a.72.72 0 0 0-.469.16c-.117.095-.101.217-.01.262l.242.139c.284-.092.599-.105.907-.197");
}

.y3uayvb5s {
  stop-color: var(--svg-color--966d92, #966D92);
  stop-opacity: 0;
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.y9klw1bbn {
  stop-color: var(--svg-color--733b64, #733B64);
  stop-opacity: 0;
}

.yaaat27jw {
  stop-color: var(--svg-color--a5949b, #A5949B);
}

.ydvpfnbad {
  stop-color: var(--svg-color--9d6ec3, #9D6EC3);
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yn315pfzg {
  stop-color: var(--svg-color--cc952b, #CC952B);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z-i44bwbr {
  d: path("M11.533 12.554c.486-2.254 1.628-3.333 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.12");
}

.z23jy_b6r {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.498 5.516c.116-.203.292-.364.67-.364c.167 0 .327.046.469.16c.117.095.101.217.01.262l-.242.139c-.284-.092-.599-.105-.907-.197");
}

.z2ay7bcdw {
  d: path("m15.833 5.607l-.232.742a.235.235 0 0 0 .227.305h.344c.16 0 .274-.155.227-.305l-.232-.742c-.05-.164-.282-.164-.334 0");
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.zs29d05ot {
  d: path("m13.016 15.905l.484 12.453h2l.238-9.523c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
}

.zs8fg1bme {
  stop-color: var(--svg-color--f88e01, #F88E01);
}

</style>
