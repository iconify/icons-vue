<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="dkzqczbuq"/><path fill="url(#i5EmZZc)" class="thurgkbft"/><path fill="url(#i2M4Oqd)" class="yg2xd8kax"/><path fill="url(#ikR3oVc)" class="yg2xd8kax"/><path fill="url(#isQuvFc)" class="ayvwzybky"/><path fill="url(#iMeSsFm)" class="ayvwzybky"/><path fill="url(#iRBpqdb)" class="ayvwzybky"/><path fill="url(#iq7hfBb)" class="ayvwzybky"/><g filter="url(#irzZYOd)"><path fill="url(#iIEDUhM)" class="m8aifg4wo"/><path fill="url(#ik95nEf)" class="m8aifg4wo"/></g><path fill="url(#iQ76pGe)" class="m8aifg4wo"/><path fill="url(#ivkFTge)" class="m8aifg4wo"/><g filter="url(#ihaubXb)"><path fill="url(#i8u1j2b)" class="s73foneqg"/></g><path fill="url(#ipFBGDd)" class="unvh6sz3z"/><path fill="url(#irKBZsY)" class="unvh6sz3z"/><g filter="url(#iU2YfER)"><path class="a21ya3tlm"/></g><g filter="url(#ioljP5c)"><path class="dn-k0krsq"/></g><g filter="url(#i4uXxZq)"><path class="s9j26tbyi"/></g><g filter="url(#ieD6jIO)"><path fill="url(#iImXFme)" class="l313-ytcf"/></g><g filter="url(#ioQrEGv)"><path fill="url(#iCxsawc)" class="rv2yjtb5k"/></g><g filter="url(#itFXXyi)"><path fill="url(#iVqXOVD)" class="l1yq2nfcv"/></g><path fill="url(#iFwUCUd)" class="u3rjmtbdw"/><path fill="url(#i9sxRPb)" class="u3rjmtbdw"/><path fill="url(#iSgPnWb)" class="m4kvjdb5u"/><path fill="url(#iCXnsKc)" class="m4kvjdb5u"/><path fill="url(#i9PN39d)" class="m4kvjdb5u"/><path fill="url(#iVJRemc)" class="sdss79bgs"/><path fill="url(#iB9fFXK)" class="sdss79bgs"/><path fill="url(#iEvZJBi)" class="sdss79bgs"/><path fill="url(#ip9Lbpc)" class="sdss79bgs"/><g filter="url(#iBK02pl)"><path fill="url(#icr5Okc)" class="k3hiscbaj"/></g><g filter="url(#iqmzXDb)"><path class="sd3g6ccoy"/><path fill="url(#iBnmMld)" class="t8z01-bqg"/></g><g filter="url(#iV7r3hN)"><ellipse fill="url(#iaFvkFc)" class="bjvtl8b2l"/></g><g filter="url(#iSAh7Nc)"><path fill="url(#iLAr7ac)" class="bz-p9y0it"/><path fill="url(#impIDyd)" class="bz-p9y0it"/><path fill="url(#iV9IGFv)" class="bz-p9y0it"/><path fill="url(#i13Y8qc)" class="bz-p9y0it"/><path fill="url(#ixP9f9d)" class="bz-p9y0it"/></g><g filter="url(#idv6SKm)"><path stroke="url(#iT9FaLb)" class="ji3l1lbqi"/></g><g filter="url(#ihS0aad)"><path stroke="url(#iY6fsQd)" class="od5_5tboc"/></g><g filter="url(#iiy4dHb)"><path stroke="url(#iCCjOCd)" class="znt3hru3h"/></g><g filter="url(#i1l1Imb)"><circle fill="url(#iKc1ryc)" class="adp_6jbbl"/></g><g filter="url(#itW6e4v)"><circle fill="url(#iwoqmUd)" class="ssgp3qb9g"/></g><g filter="url(#isxQLvd)"><circle fill="url(#irvCBXb)" class="rlr8sp7-e"/><circle fill="url(#iyVMcQc)" class="rlr8sp7-e"/></g><g filter="url(#iYiCcmd)"><circle class="cbmi7h2lo"/><circle fill="url(#iFwJr2c)" class="k8u1scbzc"/><circle fill="url(#i4QHCVc)" class="k8u1scbzc"/></g><g filter="url(#i8sntKc)"><path fill="url(#iMn43od)" class="w502q0ber"/><path fill="url(#i08b2Jc)" class="w502q0ber"/><path fill="url(#iIXDlUc)" class="w502q0ber"/><path fill="url(#iXE4twd)" class="w502q0ber"/><path fill="url(#ix1U0Pd)" class="w502q0ber"/><path fill="url(#irJ8dHd)" class="w502q0ber"/></g><g filter="url(#iyJb6tl)"><path class="p3o58-t8p"/></g><g filter="url(#i53eFwo)"><path class="xyc83j62t"/><path fill="url(#iPDdX2v)" class="vatwq490p"/><path fill="url(#ilvkymb)" class="vatwq490p"/><path fill="url(#imCnEOe)" class="vatwq490p"/></g><path stroke="url(#iU8Aedb)" class="o60hgqn2b"/><path class="cc200ywaf"/><path fill="url(#iM7h1yb)" class="xj-n16x2e"/><path class="le25zm2xh"/><g filter="url(#iYLKx0W)"><path class="kx60ndait"/><path fill="url(#iS5tXMc)" class="ji4gs_b0o"/></g><g filter="url(#i3p769I)"><path fill="url(#iT2uHQc)" class="x1jbyvf7a"/></g><path class="krib4kbbr"/><path fill="url(#iUS4Axe)" class="hks7mmtfu"/><path class="gzp9ip4vw"/><g filter="url(#iVjqRIm)"><path fill="url(#ilxzj5d)" class="ncyz7ynwm"/></g><g filter="url(#icEtjZd)"><ellipse transform="rotate(-27.914 13.166 9.906)" class="drgac6s5t"/><ellipse fill="url(#iYfek4d)" transform="rotate(-27.914 13.166 9.906)" class="a6e-2ipxl"/></g><g filter="url(#ignWzic)"><path clip-rule="evenodd" class="lc3u34-in"/></g><g filter="url(#iPi8nXb)"><path stroke="url(#iDbGiZd)" class="nmbs3ufcy"/></g><g filter="url(#ic27Qte)"><path clip-rule="evenodd" class="s-881obbz"/></g><g filter="url(#ih1xwxb)"><path stroke="url(#iTmUUld)" class="qccgzhfcd"/></g><path fill="url(#iCFScke)" class="yvf9n_m1b"/><path fill="url(#ijGa6me)" class="yvf9n_m1b"/><path fill="url(#icg0MBb)" class="yw4t8ibuk"/><path fill="url(#i3krmce)" class="yw4t8ibuk"/><g filter="url(#icG9jsd)"><path fill="url(#iQ5Re2d)" class="zpq5-ob0a"/><path fill="url(#i60Lhik)" class="zpq5-ob0a"/><path fill="url(#id7oS3c)" class="zpq5-ob0a"/></g><path fill="url(#iAH2wfe)" class="ie60xzbyz"/><path fill="url(#ie6Olhd)" class="ie60xzbyz"/><g filter="url(#i8LtYWd)"><path fill="url(#irfjeud)" class="kr1jnqbzy"/></g><g filter="url(#imzp1nc)"><path fill="url(#izdSbhd)" class="ryu_cxbog"/></g><g filter="url(#ihN0nwe)"><path fill="url(#ibT43Be)" class="bylxlwb0t"/></g><defs><radialGradient id="i5EmZZc" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.474 57.487)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="ikR3oVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 23.694 30.105)" gradientUnits="userSpaceOnUse"><stop class="br4vp4byh"/><stop offset="1" class="fs29nabkl"/></radialGradient><radialGradient id="iRBpqdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.134 30.608)" gradientUnits="userSpaceOnUse"><stop class="gt-1-ac7u"/><stop offset="1" class="yrzv-0byt"/></radialGradient><radialGradient id="iq7hfBb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.94559 0 0 -18.6532 9.222 29.319)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="blny5fbqc"/><stop offset="1" class="ql78zhb7e"/></radialGradient><radialGradient id="iIEDUhM" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 20.735 19.58)" gradientUnits="userSpaceOnUse"><stop class="b3mtuebqr"/><stop offset="1" class="txq537bby"/></radialGradient><radialGradient id="ik95nEf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.4 32.352)" gradientUnits="userSpaceOnUse"><stop class="ygyrfpbde"/><stop offset="1" class="r7svlnonw"/></radialGradient><radialGradient id="iQ76pGe" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.432 15.985)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="ipFBGDd" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 9.007 10.06)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="irKBZsY" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09928 1.3907 -.80165 -2.9394 15.257 15.982)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="arr7-5bxc"/><stop offset="1" class="mejh1wbdq"/></radialGradient><radialGradient id="iFwUCUd" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.343 16.11)scale(2.34093 2.29861)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="i9sxRPb" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 27.395 23.441)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="iSgPnWb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 14.869 19.186)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="iCXnsKc" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.228 18.061)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="i9PN39d" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.339 20.359)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="iVJRemc" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.206 18.477)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="iEvZJBi" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 15.76 18.78)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="ip9Lbpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 18.697 21.186)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="iBnmMld" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.714 11.194)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="j0jku5-3m"/><stop offset="1" class="r37diw65a"/></radialGradient><radialGradient id="iaFvkFc" cx="0" cy="0" r="1" gradientTransform="rotate(96.148 5.207 20.017)scale(2.87591 2.5871)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dsgtjgbbb"/><stop offset=".746" class="ofpn5ibfj"/></radialGradient><radialGradient id="impIDyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.75 25.177)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iV9IGFv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.75 26.472)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i13Y8qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.75 27.722)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ixP9f9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.75 29.073)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iKc1ryc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.2 10.684)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iyVMcQc" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 20.766 10.419)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iFwJr2c" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.352 11.506)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="i4QHCVc" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.394 10.684)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="i08b2Jc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.6803 -10.161 0 16.115 7.339)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="gbmz9tkck"/><stop offset=".952" class="nbba5kb5p"/></radialGradient><radialGradient id="iXE4twd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.60345 0 17.984 9.411)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="ix1U0Pd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.72401 0 13.44 9.378)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iM7h1yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 17.804 10.001)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iS5tXMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.576 10.086)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUS4Axe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.437 10.001)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iYfek4d" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.606 -1.363)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijGa6me" cx="0" cy="0" r="1" gradientTransform="rotate(110.072 2.987 7.623)scale(1.84653 .57019)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="hn1dybclr"/><stop offset="1" class="r0loj7bmn"/></radialGradient><radialGradient id="i3krmce" cx="0" cy="0" r="1" gradientTransform="matrix(.33928 1.30357 -.759 .19755 20.25 7.994)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="sv916ybit"/><stop offset="1" class="j0aqt7wmg"/></radialGradient><radialGradient id="iQ5Re2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.54 5.952)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="zqw5laobm"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="i60Lhik" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.353 2.796)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="id7oS3c" cx="0" cy="0" r="1" gradientTransform="matrix(2.67803 0 0 3.53252 8.317 3.898)" gradientUnits="userSpaceOnUse"><stop class="cxaqe9bxy"/><stop offset="1" class="p0efopw-a"/></radialGradient><radialGradient id="iAH2wfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.46875 8.0624 -.10205 18.79 7.202)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="rfhmcsbwp"/><stop offset="1" class="n6auyzb6w"/></radialGradient><filter id="irzZYOd" width="14.3" height="12.3" x="8.381" y="17.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/></filter><filter id="ihaubXb" width="6.538" height="5.771" x="12.023" y="16.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".325"/></filter><filter id="iU2YfER" width="2.5" height="2.5" x="18.472" y="26.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".25"/></filter><filter id="ioljP5c" width="2.5" height="2.5" x="18.472" y="23.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".25"/></filter><filter id="i4uXxZq" width="2.5" height="2.5" x="18.472" y="19.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".25"/></filter><filter id="ieD6jIO" width="1.7" height="1.7" x="19.141" y="27.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1885" result="effect2_innerShadow_4002_1885"/></filter><filter id="ioQrEGv" width="1.7" height="1.7" x="19.141" y="23.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1885" result="effect2_innerShadow_4002_1885"/></filter><filter id="itFXXyi" width="1.7" height="1.7" x="19.141" y="19.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1885" result="effect2_innerShadow_4002_1885"/></filter><filter id="iBK02pl" width="2.238" height="1.809" x="14.532" y="17.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1885" result="effect2_innerShadow_4002_1885"/></filter><filter id="iqmzXDb" width="5.047" height="11.336" x="23.084" y="14.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.552941 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/></filter><filter id="iV7r3hN" width="3.672" height="4.703" x="23.547" y="15.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.662745 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/><feGaussianBlur result="effect2_foregroundBlur_4002_1885" stdDeviation=".05"/></filter><filter id="iSAh7Nc" width="4.468" height="5.556" x="23.313" y="24.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/></filter><filter id="idv6SKm" width="2.097" height=".3" x="23.683" y="25.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".05"/></filter><filter id="ihS0aad" width="2.097" height=".3" x="23.605" y="27.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".05"/></filter><filter id="iiy4dHb" width="2.097" height=".3" x="23.683" y="28.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".05"/></filter><filter id="i1l1Imb" width="3.542" height="3.342" x="9.2" y="9.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/></filter><filter id="itW6e4v" width="2.992" height="2.992" x="9.375" y="9.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".25"/></filter><filter id="isxQLvd" width="3.592" height="3.592" x="18.722" y="8.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/></filter><filter id="iYiCcmd" width="2.992" height="2.992" x="18.897" y="9.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".25"/></filter><filter id="i8sntKc" width="10.34" height="12.189" x="10.504" y="5.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/></filter><filter id="iyJb6tl" width="3.262" height="4.184" x="13.753" y="9.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".375"/></filter><filter id="i53eFwo" width="2.379" height="3.184" x="14.434" y="9.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".125"/></filter><filter id="iYLKx0W" width=".787" height=".697" x="17.07" y="9.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".05"/></filter><filter id="i3p769I" width=".892" height=".914" x="17.91" y="9.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".1"/></filter><filter id="iVjqRIm" width=".987" height="1.041" x="13.464" y="9.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".1"/></filter><filter id="icEtjZd" width=".914" height=".705" x="12.709" y="9.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".05"/></filter><filter id="ignWzic" width="2.854" height="1.798" x="16.888" y="7.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/></filter><filter id="iPi8nXb" width="2.409" height="1.203" x="16.986" y="7.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".15"/></filter><filter id="ic27Qte" width="2.854" height="1.798" x="11.754" y="7.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/></filter><filter id="ih1xwxb" width="2.409" height="1.203" x="11.852" y="7.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".15"/></filter><filter id="icG9jsd" width="14.779" height="5.543" x="8.317" y="1.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1885"/></filter><filter id="i8LtYWd" width=".674" height="2.047" x="12.564" y="3.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".05"/></filter><filter id="imzp1nc" width=".674" height="2.047" x="18.151" y="3.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".05"/></filter><filter id="ihN0nwe" width=".98" height="2.537" x="15.22" y="3.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1885" stdDeviation=".1"/></filter><linearGradient id="i2M4Oqd" x1="22.839" x2="26.082" y1="25.77" y2="25.77" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="isQuvFc" x1="7.822" x2="7.822" y1="30.89" y2="16.827" gradientUnits="userSpaceOnUse"><stop class="da7b97bvf"/><stop offset="1" class="si_znv48i"/></linearGradient><linearGradient id="iMeSsFm" x1="8.681" x2="8.103" y1="26.515" y2="26.515" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="ivkFTge" x1="8.681" x2="12.618" y1="27.101" y2="27.101" gradientUnits="userSpaceOnUse"><stop class="t81o0ct1j"/><stop offset="1" class="v6vn_tcph"/></linearGradient><linearGradient id="i8u1j2b" x1="16.29" x2="13.329" y1="22.021" y2="18.636" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="iImXFme" x1="20.509" x2="19.241" y1="27.535" y2="28.941" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iCxsawc" x1="20.509" x2="19.241" y1="23.895" y2="25.301" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iVqXOVD" x1="20.509" x2="19.241" y1="20.265" y2="21.671" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iB9fFXK" x1="16.384" x2="17.369" y1="17.89" y2="19.061" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="icr5Okc" x1="15.9" x2="15.9" y1="18.78" y2="17.341" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="iLAr7ac" x1="27.341" x2="23.313" y1="27.935" y2="27.935" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="iT9FaLb" x1="23.833" x2="25.543" y1="25.929" y2="25.929" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iY6fsQd" x1="23.755" x2="25.464" y1="27.233" y2="27.233" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iCCjOCd" x1="23.833" x2="25.543" y1="28.538" y2="28.538" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iwoqmUd" x1="10.871" x2="10.23" y1="10.963" y2="10.963" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="irvCBXb" x1="21.481" x2="20.661" y1="9.591" y2="12.13" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iMn43od" x1="19.668" x2="12.055" y1="11.074" y2="12.204" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iIXDlUc" x1="10.267" x2="12.572" y1="13.772" y2="13.473" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="irJ8dHd" x1="15.674" x2="15.674" y1="6.98" y2="8.262" gradientUnits="userSpaceOnUse"><stop offset=".195" class="g12vaquuw"/><stop offset="1" class="swi-q9bgz"/></linearGradient><linearGradient id="iPDdX2v" x1="14.758" x2="15.697" y1="11.734" y2="11.734" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="ilvkymb" x1="16.563" x2="15.536" y1="12.057" y2="12.042" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="imCnEOe" x1="15.818" x2="15.818" y1="12.8" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iU8Aedb" x1="14.585" x2="15.021" y1="14.416" y2="13.728" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iT2uHQc" x1="18.583" x2="18.269" y1="10.055" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilxzj5d" x1="14.181" x2="13.867" y1="10.055" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDbGiZd" x1="17.843" x2="18.325" y1="7.908" y2="7.067" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iTmUUld" x1="13.404" x2="12.922" y1="7.908" y2="7.067" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iCFScke" x1="10.445" x2="9.8" y1="8.567" y2="8.567" gradientUnits="userSpaceOnUse"><stop class="dcanmj6yg"/><stop offset="1" class="rbn0oiylw"/></linearGradient><linearGradient id="icg0MBb" x1="20.718" x2="20.718" y1="7.545" y2="10.055" gradientUnits="userSpaceOnUse"><stop class="zms6oqb7r"/><stop offset="1" class="mhg1eabqw"/></linearGradient><linearGradient id="ie6Olhd" x1="16.291" x2="16.291" y1="7.671" y2="6.983" gradientUnits="userSpaceOnUse"><stop class="co6smusrg"/><stop offset="1" class="bs-097z7j"/></linearGradient><linearGradient id="irfjeud" x1="13.037" x2="12.459" y1="5.523" y2="5.426" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ka0ki7btw"/><stop offset="1" class="r64vbvf7r"/></linearGradient><linearGradient id="izdSbhd" x1="18.299" x2="18.931" y1="5.332" y2="5.426" gradientUnits="userSpaceOnUse"><stop offset=".246" class="qu7pewj0n"/><stop offset="1" class="g79jbcb8w"/></linearGradient><linearGradient id="ibT43Be" x1="16" x2="16" y1="5.668" y2="3.64" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mzy53gozy"/><stop offset="1" class="zwaih9noa"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-cook-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a21ya3tlm {
  fill: var(--svg-color--bfa9d1, #BFA9D1);
  d: path("M20.472 28.178a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.a6e-2ipxl {
  cx: 13.166px;
  cy: 9.906px;
  rx: 0.39px;
  ry: 0.197px;
}

.adp_6jbbl {
  cx: 10.871px;
  cy: 10.684px;
  r: 1.671px;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.arr7-5bxc {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
}

.ayvwzybky {
  d: path("M8.681 17.876a10.96 10.96 0 0 0-4 8.477v3.55h4z");
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b3mtuebqr {
  stop-color: var(--svg-color--e9dae3, #E9DAE3);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.bjvtl8b2l {
  cx: 25.358px;
  cy: 17.616px;
  rx: 1.711px;
  ry: 2.227px;
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.blny5fbqc {
  stop-color: var(--svg-color--dfc3c4, #DFC3C4);
  stop-opacity: 0;
}

.br4vp4byh {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
}

.bs-097z7j {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
  stop-opacity: 0;
}

.bylxlwb0t {
  d: path("M15.42 3.64H16v2.137h-.58z");
}

.bz-p9y0it {
  d: path("M23.313 25.198c0-.4.326-.731.727-.731h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1H24.04a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.407-.657");
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.cbmi7h2lo {
  cx: 20.393px;
  cy: 10.684px;
  r: 0.996px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.cc200ywaf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.013 9.252c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34H16.87a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co6smusrg {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
}

.cxaqe9bxy {
  stop-color: var(--svg-color--e7d1cd, #E7D1CD);
}

.d8t95rbxw {
  stop-color: var(--svg-color--aa7aa4, #AA7AA4);
}

.d9jlp6fce {
  stop-color: var(--svg-color--b1203d, #B1203D);
}

.da7b97bvf {
  stop-color: var(--svg-color--b59ccc, #B59CCC);
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.dcanmj6yg {
  stop-color: var(--svg-color--dda689, #DDA689);
}

.dkzqczbuq {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M15.661 15.373c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4V26.4c0-3.421-1.554-6.482-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.dn-k0krsq {
  fill: var(--svg-color--bfa9d1, #BFA9D1);
  d: path("M19.722 25.288a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.drgac6s5t {
  cx: 13.166px;
  cy: 9.906px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.dsgtjgbbb {
  stop-color: var(--svg-color--e4976b, #E4976B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.frvthebdh {
  stop-color: var(--svg-color--a498b2, #A498B2);
  stop-opacity: 0;
}

.fs29nabkl {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g12vaquuw {
  stop-color: var(--svg-color--c38475, #C38475);
}

.g79jbcb8w {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
  stop-opacity: 0;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gbmz9tkck {
  stop-color: var(--svg-color--cb8e88, #CB8E88);
  stop-opacity: 0;
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gt-1-ac7u {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.gzp9ip4vw {
  fill: var(--svg-color--000, #000);
  d: path("M13.947 10.417a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.455.746h.906a.5.5 0 0 0 .06-.235");
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hks7mmtfu {
  d: path("M13.435 9.524a.893.893 0 0 0-.86 1.129H14.3a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.hn1dybclr {
  stop-color: var(--svg-color--cd9270, #CD9270);
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.ie60xzbyz {
  d: path("M21.737 5.827H9.683q.027.046.028.102V6.98c0 .249.201.45.45.45H21.26a.45.45 0 0 0 .45-.45V5.925a.2.2 0 0 1 .026-.098");
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.j0aqt7wmg {
  stop-color: var(--svg-color--cf9966, #CF9966);
  stop-opacity: 0;
}

.j0jku5-3m {
  stop-color: var(--svg-color--f4b183, #F4B183);
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.ji3l1lbqi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.833 25.85h1.797");
}

.ji4gs_b0o {
  d: path("M17.74 9.713c.064.085-.069.189-.22.302s-.263.192-.327.107s.007-.245.159-.358c.15-.114.325-.136.389-.051");
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k3hiscbaj {
  d: path("M14.993 17.46c.19-.062.44-.119.707-.119c.268 0 .517.056.708.12a.39.39 0 0 1 .254.45c-.092.486-.27.8-.463.989a.5.5 0 0 1-.268.131a1.5 1.5 0 0 1-.477 0a.43.43 0 0 1-.251-.131c-.195-.189-.372-.503-.464-.99a.39.39 0 0 1 .254-.45");
}

.k8u1scbzc {
  cx: 20.393px;
  cy: 10.684px;
  r: 0.996px;
}

.ka0ki7btw {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
}

.kr1jnqbzy {
  d: path("m13.138 5.778l-.474-1.848v1.848z");
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.krib4kbbr {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.228 9.252c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kx60ndait {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.74 9.713c.064.085-.069.189-.22.302s-.263.192-.327.107s.007-.245.159-.358c.15-.114.325-.136.389-.051");
}

.l1yq2nfcv {
  d: path("M19.991 21.513a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.l313-ytcf {
  d: path("M20.741 28.033a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lc3u34-in {
  fill: var(--svg-color--9a6634, #9A6634);
  fill-rule: evenodd;
  d: path("M17.405 8.365c.72-.067 1.182.214 1.294.318a.473.473 0 1 0 .64-.696c-.306-.282-1.031-.656-2.022-.563a.473.473 0 1 0 .088.941");
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.le25zm2xh {
  fill: var(--svg-color--000, #000);
  d: path("M17.295 10.417a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.061-.235");
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

.m4kvjdb5u {
  d: path("M13.468 18.587c.67-.924 1.704-1.194 2.097-1.246c.205.83.308 2.667-.684 3.564c-.635.574-1.077.722-1.67.787c-.163.017-.269-.165-.221-.322q.047-.149.053-.366c.009-.634-.11-1.68.425-2.418");
}

.m8aifg4wo {
  d: path("M8.681 17.903h10.053c2.176 0 3.947 1.796 3.947 4.003v7.997h-14z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.mejh1wbdq {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
  stop-opacity: 0;
}

.mhg1eabqw {
  stop-color: var(--svg-color--f7c295, #F7C295);
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.mzy53gozy {
  stop-color: var(--svg-color--a990c1, #A990C1);
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n6auyzb6w {
  stop-color: var(--svg-color--b1a3bf, #B1A3BF);
}

.nbba5kb5p {
  stop-color: var(--svg-color--ac6061, #AC6061);
}

.ncyz7ynwm {
  d: path("M14.25 10.312c0-.288-.234-.48-.297-.539l-.289.28l.178.36z");
}

.nmbs3ufcy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.02 8.224c-.21-.193-.804-.52-1.66-.44");
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.o60hgqn2b {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.26 13.444a2.96 2.96 0 0 0 1.363.323c.505 0 .97-.118 1.364-.323a.204.204 0 0 1 .241.04c.058.06.079.155.021.241m-2.99-.281l2.949.253m-2.948-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.221.253m3.21.028l-.041-.028m.041.028l-.041-.028m.041.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.869m3.21-.028c-.335.508-.919.847-1.584.847s-1.25-.339-1.584-.847m-.042.028l.042-.028m-.042.028l.042-.028");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od5_5tboc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.755 27.155h1.797");
}

.ofpn5ibfj {
  stop-color: var(--svg-color--e29457, #E29457);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.p0efopw-a {
  stop-color: var(--svg-color--b8a5ca, #B8A5CA);
  stop-opacity: 0;
}

.p3o58-t8p {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.348 10.562l-.822 1.7c-.101.35.143.7.489.7h.738c.346 0 .59-.354.488-.7l-.498-1.7c-.107-.377-.283-.377-.395 0");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.qccgzhfcd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.227 8.224c.21-.193.803-.52 1.659-.44");
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.ql78zhb7e {
  stop-color: var(--svg-color--dfc3c4, #DFC3C4);
}

.qu7pewj0n {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0loj7bmn {
  stop-color: var(--svg-color--cd9270, #CD9270);
  stop-opacity: 0;
}

.r37diw65a {
  stop-color: var(--svg-color--f4b183, #F4B183);
  stop-opacity: 0;
}

.r64vbvf7r {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
  stop-opacity: 0;
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.r7svlnonw {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
  stop-opacity: 0;
}

.rbn0oiylw {
  stop-color: var(--svg-color--f3c099, #F3C099);
}

.rfhmcsbwp {
  stop-color: var(--svg-color--eee3f8, #EEE3F8);
}

.rlr8sp7-e {
  cx: 20.393px;
  cy: 10.684px;
  r: 1.671px;
}

.rv2yjtb5k {
  d: path("M19.991 25.143a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.ryu_cxbog {
  d: path("m18.252 5.778l.474-1.848v1.848z");
}

.s-881obbz {
  fill: var(--svg-color--9a6634, #9A6634);
  fill-rule: evenodd;
  d: path("M13.842 8.365c-.72-.067-1.183.214-1.295.318a.473.473 0 0 1-.64-.696c.306-.282 1.032-.656 2.023-.563a.473.473 0 1 1-.088.941");
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s73foneqg {
  d: path("M15.394 17.398c-.384.032-1.404.252-2.102 1.143c-.47.599-.498 1.44-.52 2.068q-.005.177-.014.326a1.3 1.3 0 0 1-.07.363c-.054.154.04.342.2.332c.58-.037 1.018-.163 1.665-.706c.492-.413.742-1.062.85-1.716c.044.661.229 1.332.678 1.792c.59.604 1.013.773 1.586.866c.158.026.27-.151.232-.31a1.4 1.4 0 0 1-.034-.368q.006-.15.018-.326c.041-.627.095-1.467-.313-2.11c-.606-.954-1.6-1.274-1.979-1.344a5 5 0 0 0-.127.583a5 5 0 0 0-.07-.593");
}

.s9j26tbyi {
  fill: var(--svg-color--c1a0c0, #C1A0C0);
  d: path("M19.722 21.658a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sd3g6ccoy {
  fill: var(--svg-color--eca779, #ECA779);
  d: path("M26.06 21.076c0-.405.26-.758.569-1.021c.604-.517 1.002-1.392 1.002-2.384c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.567.616.567 1.021v5.056h1.407z");
}

.sdss79bgs {
  d: path("M17.864 18.587c-.67-.924-1.704-1.194-2.096-1.246c-.206.83-.308 2.667.683 3.564c.635.574 1.078.722 1.67.787c.164.017.27-.165.222-.322c-.03-.1-.051-.22-.053-.366c-.01-.634.109-1.68-.426-2.418");
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.ssgp3qb9g {
  cx: 10.871px;
  cy: 10.684px;
  r: 0.996px;
}

.sv916ybit {
  stop-color: var(--svg-color--cf9966, #CF9966);
}

.swi-q9bgz {
  stop-color: var(--svg-color--c38475, #C38475);
  stop-opacity: 0;
}

.t81o0ct1j {
  stop-color: var(--svg-color--9e8fad, #9E8FAD);
}

.t8z01-bqg {
  d: path("M26.06 21.076c0-.405.26-.758.569-1.021c.604-.517 1.002-1.392 1.002-2.384c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.567.616.567 1.021v5.056h1.407z");
}

.thurgkbft {
  d: path("M15.661 15.373c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4V26.4c0-3.421-1.554-6.482-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.txq537bby {
  stop-color: var(--svg-color--d8c4e9, #D8C4E9);
}

.u3rjmtbdw {
  d: path("M26.664 22.96a.97.97 0 0 1 .967.966v2.215h-1.934v-2.214a.976.976 0 0 1 .967-.968");
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.unvh6sz3z {
  d: path("M23.09 18.258H8.243a10.94 10.94 0 0 1 7.42-2.885c3.483 0 5.152.81 7.429 2.885");
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v6vn_tcph {
  stop-color: var(--svg-color--c0b0d1, #C0B0D1);
  stop-opacity: 0;
}

.vatwq490p {
  d: path("m15.24 10.399l-.531 1.7a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.w502q0ber {
  d: path("M10.504 8.49c0-.267.052-.689.267-.849l.056-.434c.268-.213.492-.017.492-.338v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.054.43.267.43.534v.854c0 .32.16.64.375.854c.503.353.471.546.43.961c-.18 1.792-.235 3.607-.356 5.404c-.16 1.771-1.553 3.005-3.213 3.005H14.04c-1.713 0-3.052-1.234-3.213-3.005c-.139-1.812-.323-3.78-.323-5.598");
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x1jbyvf7a {
  d: path("M18.602 10.3a.84.84 0 0 0-.232-.464l-.26.286l.118.228z");
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xj-n16x2e {
  d: path("M17.806 9.524a.893.893 0 0 1 .86 1.129h-1.724a.897.897 0 0 1 .865-1.129");
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

.xyc83j62t {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.24 10.399l-.531 1.7a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yg2xd8kax {
  d: path("M22.681 29.903h4V26.4c0-3.421-1.554-6.482-4-8.498z");
}

.ygyrfpbde {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.yrzv-0byt {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
  stop-opacity: 0;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.yvf9n_m1b {
  d: path("M9.8 8.598V7.161h1.476a2 2 0 0 1-.425.69c-.227.22-.303.596-.303.809v1.395c-.236 0-.331-.114-.549-.53c-.174-.333-.205-.756-.198-.927");
}

.yw4t8ibuk {
  d: path("M21.455 8.598V7.161H19.98c.047.138.198.47.425.69s.303.596.303.809v1.395c.237 0 .331-.114.549-.53c.174-.333.205-.756.198-.927");
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zms6oqb7r {
  stop-color: var(--svg-color--fad0a4, #FAD0A4);
}

.znt3hru3h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.833 28.46h1.797");
}

.zpq5-ob0a {
  d: path("M10.25 1.988a1.933 1.933 0 0 0-.68 3.742a.215.215 0 0 1 .143.198V6.98c0 .249.201.45.45.45H21.26a.45.45 0 0 0 .45-.45V5.926c0-.09.059-.166.141-.198a1.934 1.934 0 0 0-.69-3.74z");
}

.zqw5laobm {
  stop-color: var(--svg-color--aa92c2, #AA92C2);
}

.zwaih9noa {
  stop-color: var(--svg-color--a990c1, #A990C1);
  stop-opacity: 0;
}

</style>
