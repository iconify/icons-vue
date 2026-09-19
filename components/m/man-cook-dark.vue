<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sc_sq1rcf"/><path fill="url(#iVG2Kzb)" class="xl-_vsb8m"/><path fill="url(#iGt906c)" class="hli13obbz"/><path fill="url(#ibgx4Eb)" class="hli13obbz"/><path fill="url(#iDyriqd)" class="s1n30k-8i"/><path fill="url(#iI9WHze)" class="s1n30k-8i"/><path fill="url(#iI1z6Yi)" class="s1n30k-8i"/><g filter="url(#ir9VOqc)"><path fill="url(#ilAZ05w)" class="rqng-o75v"/><path fill="url(#i1XaLWb)" class="rqng-o75v"/></g><path fill="url(#iEBiUge)" class="rqng-o75v"/><path fill="url(#ij05RCc)" class="rqng-o75v"/><g filter="url(#iisAzbd)"><path fill="url(#isCM1Jz)" class="k5mj7db2t"/></g><path fill="url(#i3Fnj7c)" class="hwa7c8b2i"/><path fill="url(#ilvxZJd)" class="hwa7c8b2i"/><g filter="url(#iXmYLWb)"><path class="xkvuqmb_j"/></g><g filter="url(#irsfL0t)"><path class="qdxhbpb0p"/></g><g filter="url(#iObgLtb)"><path class="vzy_pqbvx"/></g><g filter="url(#iqyOKTO)"><path class="r_hj_bbby"/></g><g filter="url(#ikYDkud)"><path class="dxnpahbpe"/></g><g filter="url(#i2lmJod)"><path class="r77l3mbhz"/></g><path fill="url(#inR3YGc)" class="trde_l8na"/><path fill="url(#iNyMyVk)" class="trde_l8na"/><path fill="url(#iaNFcbi)" class="w3fh2kkny"/><path fill="url(#irP0nFd)" class="w3fh2kkny"/><path fill="url(#iXXsxov)" class="w3fh2kkny"/><path fill="url(#iK08eMe)" class="dktrxccqv"/><path fill="url(#iIpaR4b)" class="dktrxccqv"/><path fill="url(#i1qE2Kd)" class="dktrxccqv"/><path fill="url(#icSnlNb)" class="dktrxccqv"/><g filter="url(#iKPvTOe)"><path fill="url(#iqwYuQe)" class="hwy0od_ma"/></g><g filter="url(#iLUFlVU)"><path class="a1s5upm6n"/><path fill="url(#iSMgaNd)" class="cx821ccni"/></g><g filter="url(#ibuMvme)"><ellipse fill="url(#inXmfOd)" class="drrhxsbec"/></g><g filter="url(#i74ex2c)"><path fill="url(#iMZx74b)" class="lhr-ibb6r"/><path fill="url(#ihLzYSd)" class="lhr-ibb6r"/><path fill="url(#iG3IOeE)" class="lhr-ibb6r"/><path fill="url(#iivqzjk)" class="lhr-ibb6r"/><path fill="url(#icaGoTJ)" class="lhr-ibb6r"/></g><g filter="url(#i5k3lNc)"><path stroke="url(#iyP9wNe)" class="qdng1m96y"/></g><g filter="url(#ijmPg0b)"><path stroke="url(#ilPUqld)" class="qeyngbb0g"/></g><g filter="url(#i51dkdb)"><path stroke="url(#iKIh9gI)" class="m7jeiwb9a"/></g><g filter="url(#iSSpmVd)"><circle fill="url(#iIJGnMe)" class="fxdbj_b2r"/></g><g filter="url(#iRn7Ove)"><circle fill="url(#iqEvUOe)" class="zvqnwo5qe"/></g><g filter="url(#iTi38Bd)"><circle fill="url(#iO047Gc)" class="a2_yhqbjx"/><circle fill="url(#ixelgwi)" class="a2_yhqbjx"/></g><g filter="url(#iNlfWme)"><circle class="xhfcb3qnc"/><circle fill="url(#i1jb0me)" class="gkcah5tub"/><circle fill="url(#iD6uVhd)" class="gkcah5tub"/></g><g filter="url(#iBJFlZd)"><path fill="url(#i1eONwr)" class="cfv0f-ztv"/><path fill="url(#iHpX5Wb)" class="cfv0f-ztv"/><path fill="url(#iXaaaJc)" class="cfv0f-ztv"/><path fill="url(#iU9SNJc)" class="cfv0f-ztv"/><path fill="url(#iFzDbhd)" class="cfv0f-ztv"/><path fill="url(#isCGmJg)" class="cfv0f-ztv"/><path fill="url(#iEW2Kmd)" class="cfv0f-ztv"/><path fill="url(#iGQbl7d)" class="cfv0f-ztv"/></g><g filter="url(#iuPc3ge)"><path class="cu0bqebzk"/></g><g filter="url(#isMuOne)"><path class="obss6-bml"/><path fill="url(#iaz57ad)" class="r9jwp9ffy"/><path fill="url(#i9aNtfN)" class="r9jwp9ffy"/><path fill="url(#ixmwmrb)" class="r9jwp9ffy"/><path fill="url(#iA8mzke)" class="r9jwp9ffy"/></g><path stroke="url(#iY0nj8d)" class="xt4dnx1tg"/><path class="rrna_jb6d"/><path fill="url(#ivRUaSd)" class="q6fjdp0or"/><path class="lkv_7obls"/><g filter="url(#iC5Nsdc)"><path class="lb-r4td4r"/><path fill="url(#ialGAgc)" class="ba-4xbbao"/></g><g filter="url(#iiGtJcc)"><path fill="url(#iJAK21z)" class="x6fwodqnd"/></g><path class="jnc25qbpn"/><path fill="url(#iFOeChd)" class="q2b_s4bxz"/><path class="t0vu2z0fa"/><g filter="url(#izwAwfc)"><path fill="url(#iZBZohd)" class="hrzs9pb6k"/></g><g filter="url(#icPNByd)"><ellipse transform="rotate(-27.914 13.166 10)" class="h0bxc2bks"/><ellipse fill="url(#iHTEXJi)" transform="rotate(-27.914 13.166 10)" class="ha712abim"/></g><g filter="url(#iQM2e9t)"><path clip-rule="evenodd" class="d426gga4g"/></g><g filter="url(#iKjNvXb)"><path stroke="url(#i1lKr9E)" class="hkt82hb-w"/></g><g filter="url(#i4DMhhc)"><path clip-rule="evenodd" class="nujrjcctj"/></g><g filter="url(#ivwrK1U)"><path stroke="url(#iPPX4ke)" class="wd7-xxbdp"/></g><path fill="url(#iIuvJUd)" class="ci23tqjrh"/><path fill="url(#ih1gMAb)" class="ci23tqjrh"/><path fill="url(#i9jH9Tb)" class="yv8ms4m5l"/><path fill="url(#iZ8ymjd)" class="yv8ms4m5l"/><g filter="url(#ihLhc8T)"><path fill="url(#irGEYUF)" class="oc59d5-1h"/><path fill="url(#iR5Y8Me)" class="oc59d5-1h"/></g><path fill="url(#iYkFO8b)" class="egkd9knrb"/><path fill="url(#iXcgTqb)" class="egkd9knrb"/><g filter="url(#iYHU77k)"><path fill="url(#iydasdc)" class="gbr77eb4u"/></g><g filter="url(#i4XXMWd)"><path fill="url(#iNUznHO)" class="bkw929b6n"/></g><g filter="url(#insUPZc)"><path fill="url(#iIwhIxe)" class="cisjizbch"/></g><defs><radialGradient id="iVG2Kzb" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.712 57.535)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="ibgx4Eb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 23.694 30.2)" gradientUnits="userSpaceOnUse"><stop class="q2rhgqb4s"/><stop offset="1" class="fs29nabkl"/><stop offset="1" class="sli_wqbvh"/></radialGradient><radialGradient id="iI1z6Yi" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.134 30.703)" gradientUnits="userSpaceOnUse"><stop class="g2ynuf2dq"/><stop offset="1" class="ef22fkbzm"/></radialGradient><radialGradient id="ilAZ05w" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 20.735 19.675)" gradientUnits="userSpaceOnUse"><stop class="m6lhrcc1m"/><stop offset="1" class="hm5-ozbqx"/></radialGradient><radialGradient id="i1XaLWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.4 32.447)" gradientUnits="userSpaceOnUse"><stop class="fg0e2bc1h"/><stop offset="1" class="qk3h5tshn"/></radialGradient><radialGradient id="iEBiUge" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.493 16.032)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="i3Fnj7c" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 9 10.106)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="ilvxZJd" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.608 8.617)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="arr7-5bxc"/><stop offset="1" class="mejh1wbdq"/></radialGradient><radialGradient id="inR3YGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68781 1.6831 -2.07966 -2.08548 27.72 23.318)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iNyMyVk" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 27.395 23.535)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="iaNFcbi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 14.869 19.281)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="irP0nFd" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.228 18.156)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="iXXsxov" cx="0" cy="0" r="1" gradientTransform="matrix(.6856 -1.32813 .78813 .40685 14.34 20.453)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="iK08eMe" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.206 18.572)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="i1qE2Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 15.76 18.877)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="icSnlNb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 18.697 21.281)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="iSMgaNd" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.703 11.241)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="j0jku5-3m"/><stop offset="1" class="r37diw65a"/></radialGradient><radialGradient id="inXmfOd" cx="0" cy="0" r="1" gradientTransform="rotate(96.148 5.164 20.064)scale(2.87591 2.5871)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dsgtjgbbb"/><stop offset=".746" class="ofpn5ibfj"/></radialGradient><radialGradient id="ihLzYSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.75 25.272)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iG3IOeE" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.75 26.566)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iivqzjk" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.75 27.816)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="icaGoTJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.75 29.168)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iIJGnMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.2 10.779)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="ixelgwi" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 20.766 10.514)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="i1jb0me" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.352 11.6)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iD6uVhd" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.393 10.779)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iXaaaJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.6133 0 15.345 10.58)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="iU9SNJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.60345 0 17.984 9.506)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iFzDbhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.72401 0 13.44 9.473)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="isCGmJg" cx="0" cy="0" r="1" gradientTransform="matrix(-2.83176 -.68748 .40546 -1.6701 19.9 16.944)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iEW2Kmd" cx="0" cy="0" r="1" gradientTransform="rotate(132.936 8.673 8.042)scale(4.90874 6.54919)" gradientUnits="userSpaceOnUse"><stop class="zx2qd4bhl"/><stop offset="1" class="y7qcqib5l"/></radialGradient><radialGradient id="iA8mzke" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 15.95 12.387)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="ivRUaSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 17.804 10.096)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ialGAgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.576 10.18)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFOeChd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.437 10.096)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iHTEXJi" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.653 -1.315)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ih1gMAb" cx="0" cy="0" r="1" gradientTransform="matrix(-.19063 -1.34375 .41494 -.05886 9.8 9.655)" gradientUnits="userSpaceOnUse"><stop class="bt8p5ibtm"/><stop offset="1" class="lzg318lcd"/></radialGradient><radialGradient id="iZ8ymjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 -.03125 .1499 -3.6732 21.64 9.42)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="cu8te_b2r"/><stop offset="1" class="ibppm52cb"/></radialGradient><radialGradient id="irGEYUF" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.54 6.047)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ysetj63ow"/><stop offset="1" class="e1v2e-byl"/></radialGradient><radialGradient id="iR5Y8Me" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.353 2.89)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="iYkFO8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.75 8.9809 -.10205 18.822 7.101)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="ox62rwbrf"/><stop offset="1" class="g4wbwbcoe"/></radialGradient><filter id="ir9VOqc" width="14.3" height="12.3" x="8.381" y="17.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/></filter><filter id="iisAzbd" width="6.538" height="5.771" x="12.023" y="16.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".325"/></filter><filter id="iXmYLWb" width="2.5" height="2.5" x="18.472" y="27.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".25"/></filter><filter id="irsfL0t" width="2.5" height="2.5" x="18.472" y="23.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".25"/></filter><filter id="iObgLtb" width="2.5" height="2.5" x="18.472" y="19.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".25"/></filter><filter id="iqyOKTO" width="1.7" height="1.7" x="19.141" y="27.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.533333 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.647059 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1876" result="effect2_innerShadow_4002_1876"/></filter><filter id="ikYDkud" width="1.7" height="1.7" x="19.141" y="23.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.533333 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.647059 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1876" result="effect2_innerShadow_4002_1876"/></filter><filter id="i2lmJod" width="1.7" height="1.7" x="19.141" y="20.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.533333 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.647059 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1876" result="effect2_innerShadow_4002_1876"/></filter><filter id="iKPvTOe" width="2.238" height="1.809" x="14.532" y="17.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1876" result="effect2_innerShadow_4002_1876"/></filter><filter id="iLUFlVU" width="5.047" height="11.336" x="23.084" y="14.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.552941 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/></filter><filter id="ibuMvme" width="3.672" height="4.703" x="23.547" y="15.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.662745 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/><feGaussianBlur result="effect2_foregroundBlur_4002_1876" stdDeviation=".05"/></filter><filter id="i74ex2c" width="4.468" height="5.556" x="23.313" y="24.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/></filter><filter id="i5k3lNc" width="2.097" height=".3" x="23.683" y="25.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".05"/></filter><filter id="ijmPg0b" width="2.097" height=".3" x="23.605" y="27.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".05"/></filter><filter id="i51dkdb" width="2.097" height=".3" x="23.683" y="28.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".05"/></filter><filter id="iSSpmVd" width="3.542" height="3.342" x="9.2" y="9.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/></filter><filter id="iRn7Ove" width="2.992" height="2.992" x="9.375" y="9.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".25"/></filter><filter id="iTi38Bd" width="3.592" height="3.592" x="18.722" y="8.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/></filter><filter id="iNlfWme" width="2.992" height="2.992" x="18.897" y="9.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".25"/></filter><filter id="iBJFlZd" width="10.34" height="12.189" x="10.504" y="5.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/></filter><filter id="iuPc3ge" width="3.262" height="4.184" x="13.753" y="9.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".375"/></filter><filter id="isMuOne" width="2.379" height="3.184" x="14.434" y="9.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".125"/></filter><filter id="iC5Nsdc" width=".787" height=".697" x="17.07" y="9.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".05"/></filter><filter id="iiGtJcc" width=".892" height=".914" x="17.91" y="9.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".1"/></filter><filter id="izwAwfc" width=".987" height="1.041" x="13.464" y="9.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".1"/></filter><filter id="icPNByd" width=".914" height=".705" x="12.709" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".05"/></filter><filter id="iQM2e9t" width="2.854" height="1.798" x="16.888" y="7.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/></filter><filter id="iKjNvXb" width="2.409" height="1.203" x="16.986" y="7.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".15"/></filter><filter id="i4DMhhc" width="2.854" height="1.798" x="11.754" y="7.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/></filter><filter id="ivwrK1U" width="2.409" height="1.203" x="11.852" y="7.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".15"/></filter><filter id="ihLhc8T" width="14.779" height="5.543" x="8.317" y="2.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1876"/></filter><filter id="iYHU77k" width=".674" height="2.047" x="12.564" y="3.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".05"/></filter><filter id="i4XXMWd" width=".674" height="2.047" x="18.151" y="3.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".05"/></filter><filter id="insUPZc" width=".98" height="2.537" x="15.22" y="3.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1876" stdDeviation=".1"/></filter><linearGradient id="iGt906c" x1="22.839" x2="26.082" y1="25.866" y2="25.866" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="iDyriqd" x1="7.822" x2="7.822" y1="30.984" y2="16.922" gradientUnits="userSpaceOnUse"><stop offset=".06" class="rvini-b1k"/><stop offset="1" class="si_znv48i"/><stop offset="1" class="akw2ge0vx"/></linearGradient><linearGradient id="iI9WHze" x1="8.681" x2="8.103" y1="26.609" y2="26.609" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="ij05RCc" x1="8.681" x2="12.618" y1="27.196" y2="27.196" gradientUnits="userSpaceOnUse"><stop class="fj7z_vbcj"/><stop offset="1" class="zab3c9ypw"/></linearGradient><linearGradient id="isCM1Jz" x1="16.29" x2="13.329" y1="22.115" y2="18.731" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="iIpaR4b" x1="16.384" x2="17.369" y1="17.984" y2="19.156" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="iqwYuQe" x1="15.9" x2="15.9" y1="18.875" y2="17.436" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="iMZx74b" x1="27.341" x2="23.313" y1="28.03" y2="28.03" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iyP9wNe" x1="23.833" x2="25.543" y1="26.023" y2="26.023" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="ilPUqld" x1="23.755" x2="25.464" y1="27.328" y2="27.328" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iKIh9gI" x1="23.833" x2="25.543" y1="28.633" y2="28.633" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iqEvUOe" x1="10.871" x2="10.23" y1="11.057" y2="11.057" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iO047Gc" x1="21.481" x2="20.661" y1="9.686" y2="12.225" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="i1eONwr" x1="19.668" x2="12.055" y1="11.169" y2="12.298" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iHpX5Wb" x1="10.267" x2="12.525" y1="13.867" y2="13.726" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iGQbl7d" x1="15.674" x2="15.674" y1="7.248" y2="8.03" gradientUnits="userSpaceOnUse"><stop class="wu63rebjw"/><stop offset="1" class="mbqqxmbsg"/></linearGradient><linearGradient id="iaz57ad" x1="14.758" x2="15.697" y1="11.828" y2="11.828" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="i9aNtfN" x1="16.563" x2="15.536" y1="12.151" y2="12.136" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="ixmwmrb" x1="15.818" x2="15.818" y1="12.894" y2="12.321" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iY0nj8d" x1="14.585" x2="15.021" y1="14.511" y2="13.823" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iJAK21z" x1="18.583" x2="18.269" y1="10.15" y2="10.343" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZBZohd" x1="14.181" x2="13.867" y1="10.15" y2="10.343" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1lKr9E" x1="17.843" x2="18.325" y1="8.003" y2="7.162" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iPPX4ke" x1="13.404" x2="12.922" y1="8.003" y2="7.162" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iIuvJUd" x1="10.445" x2="9.8" y1="8.662" y2="8.662" gradientUnits="userSpaceOnUse"><stop class="dqogn5h-s"/><stop offset="1" class="sf_e44b2v"/></linearGradient><linearGradient id="i9jH9Tb" x1="20.718" x2="20.718" y1="7.639" y2="10.15" gradientUnits="userSpaceOnUse"><stop class="fdcpxvbay"/><stop offset="1" class="hf4w3nbyi"/></linearGradient><linearGradient id="iXcgTqb" x1="16.291" x2="16.291" y1="7.766" y2="7.078" gradientUnits="userSpaceOnUse"><stop class="gjkvqmbnm"/><stop offset="1" class="f1s8bobxq"/></linearGradient><linearGradient id="iydasdc" x1="13.037" x2="12.459" y1="5.618" y2="5.52" gradientUnits="userSpaceOnUse"><stop offset=".297" class="u7axe2baw"/><stop offset="1" class="dv8o3t25w"/></linearGradient><linearGradient id="iNUznHO" x1="18.679" x2="18.046" y1="5.427" y2="5.52" gradientUnits="userSpaceOnUse"><stop offset=".246" class="ahul9kboj"/><stop offset="1" class="ongktybvd"/></linearGradient><linearGradient id="iIwhIxe" x1="16" x2="16" y1="5.763" y2="3.735" gradientUnits="userSpaceOnUse"><stop offset=".1" class="ztvu2mbem"/><stop offset="1" class="bm3jemb-u"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-cook-dark" /></template>
<style>
.a1s5upm6n {
  fill: var(--svg-color--eca779, #ECA779);
  d: path("M26.06 21.17c0-.405.26-.757.569-1.02c.604-.517 1.002-1.392 1.002-2.384c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.567.615.567 1.02v5.057h1.407z");
}

.a2_yhqbjx {
  cx: 20.393px;
  cy: 10.779px;
  r: 1.671px;
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ahul9kboj {
  stop-color: var(--svg-color--a499b2, #A499B2);
}

.akw2ge0vx {
  stop-color: var(--svg-color--9b9598, #9B9598);
}

.arr7-5bxc {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.ba-4xbbao {
  d: path("M17.74 9.808c.064.085-.069.188-.22.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.135.389-.05");
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.bkw929b6n {
  d: path("m18.252 5.872l.474-1.847v1.847z");
}

.bm3jemb-u {
  stop-color: var(--svg-color--9c8fab, #9C8FAB);
  stop-opacity: 0;
}

.bt8p5ibtm {
  stop-color: var(--svg-color--4f4c4b, #4F4C4B);
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cfv0f-ztv {
  d: path("M10.504 8.584c0-.267.052-.688.267-.848l.056-.434c.268-.213.492-.018.492-.338V6.11a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.053.43.267.43.534v.854c0 .32.16.64.375.854c.503.352.471.546.43.961c-.18 1.792-.235 3.607-.356 5.403c-.16 1.772-1.553 3.006-3.213 3.006H14.04c-1.713 0-3.052-1.234-3.213-3.006c-.139-1.81-.323-3.779-.323-5.598");
}

.ci23tqjrh {
  d: path("M9.8 8.693V7.255h1.476a2 2 0 0 1-.425.69c-.227.22-.303.597-.303.81v1.395c-.236 0-.331-.114-.549-.53c-.174-.333-.205-.757-.198-.927");
}

.cisjizbch {
  d: path("M15.42 3.735H16v2.137h-.58z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu0bqebzk {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.348 10.656l-.822 1.702c-.101.35.143.7.489.7h.738c.346 0 .59-.356.488-.7l-.498-1.702c-.107-.376-.283-.376-.395 0");
}

.cu8te_b2r {
  stop-color: var(--svg-color--575757, #575757);
}

.cx821ccni {
  d: path("M26.06 21.17c0-.405.26-.757.569-1.02c.604-.517 1.002-1.392 1.002-2.384c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.567.615.567 1.02v5.057h1.407z");
}

.d426gga4g {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M17.405 8.46c.72-.067 1.182.214 1.294.317a.473.473 0 1 0 .64-.695c-.306-.282-1.031-.656-2.022-.563a.473.473 0 1 0 .088.941");
}

.d8t95rbxw {
  stop-color: var(--svg-color--aa7aa4, #AA7AA4);
}

.d9jlp6fce {
  stop-color: var(--svg-color--b1203d, #B1203D);
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.dktrxccqv {
  d: path("M17.864 18.681c-.67-.924-1.704-1.194-2.096-1.245c-.206.83-.308 2.667.683 3.564c.635.574 1.078.722 1.67.786c.164.018.27-.164.222-.321a1.3 1.3 0 0 1-.053-.366c-.01-.634.109-1.68-.426-2.418");
}

.dqogn5h-s {
  stop-color: var(--svg-color--1c111f, #1C111F);
}

.drrhxsbec {
  cx: 25.358px;
  cy: 17.711px;
  rx: 1.711px;
  ry: 2.227px;
}

.dsgtjgbbb {
  stop-color: var(--svg-color--e4976b, #E4976B);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dv8o3t25w {
  stop-color: var(--svg-color--9183a0, #9183A0);
  stop-opacity: 0;
}

.dxnpahbpe {
  fill: var(--svg-color--9c95a4, #9C95A4);
  d: path("M19.991 25.237a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1v2e-byl {
  stop-color: var(--svg-color--cac5ce, #CAC5CE);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ef22fkbzm {
  stop-color: var(--svg-color--ac9fb8, #AC9FB8);
  stop-opacity: 0;
}

.egkd9knrb {
  d: path("M21.737 5.922H9.683q.027.046.028.102v1.051c0 .249.201.45.45.45H21.26a.45.45 0 0 0 .45-.45V6.02a.2.2 0 0 1 .026-.098");
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f1s8bobxq {
  stop-color: var(--svg-color--9482a1, #9482A1);
  stop-opacity: 0;
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fdcpxvbay {
  stop-color: var(--svg-color--21131d, #21131D);
}

.fg0e2bc1h {
  stop-color: var(--svg-color--beb0cc, #BEB0CC);
}

.fj7z_vbcj {
  stop-color: var(--svg-color--958d9d, #958D9D);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
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

.fxdbj_b2r {
  cx: 10.871px;
  cy: 10.779px;
  r: 1.671px;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g2ynuf2dq {
  stop-color: var(--svg-color--ac9fb8, #AC9FB8);
}

.g4wbwbcoe {
  stop-color: var(--svg-color--a79da9, #A79DA9);
}

.gbr77eb4u {
  d: path("m13.138 5.872l-.474-1.847v1.847z");
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gjkvqmbnm {
  stop-color: var(--svg-color--9482a1, #9482A1);
}

.gkcah5tub {
  cx: 20.393px;
  cy: 10.779px;
  r: 0.996px;
}

.h0bxc2bks {
  cx: 13.166px;
  cy: 10px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.ha712abim {
  cx: 13.166px;
  cy: 10px;
  rx: 0.39px;
  ry: 0.197px;
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hf4w3nbyi {
  stop-color: var(--svg-color--282627, #282627);
}

.hkt82hb-w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.02 8.319c-.21-.193-.804-.52-1.66-.44");
}

.hli13obbz {
  d: path("M22.681 29.998h4v-3.502c0-3.421-1.554-6.482-4-8.498z");
}

.hm5-ozbqx {
  stop-color: var(--svg-color--cfc5da, #CFC5DA);
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.hrzs9pb6k {
  d: path("M14.25 10.407c0-.289-.234-.481-.297-.54l-.289.28l.178.361z");
}

.hwa7c8b2i {
  d: path("M23.09 18.352H8.243a10.94 10.94 0 0 1 7.42-2.885c3.483 0 5.152.812 7.429 2.885");
}

.hwy0od_ma {
  d: path("M14.993 17.555c.19-.063.44-.119.707-.119c.268 0 .517.056.708.12a.39.39 0 0 1 .254.45c-.092.486-.27.8-.463.989a.5.5 0 0 1-.268.13c-.11.02-.338.032-.477 0a.43.43 0 0 1-.251-.13c-.195-.189-.372-.503-.464-.99a.39.39 0 0 1 .254-.45");
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.ibppm52cb {
  stop-color: var(--svg-color--575757, #575757);
  stop-opacity: 0;
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j0jku5-3m {
  stop-color: var(--svg-color--f4b183, #F4B183);
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jnc25qbpn {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.228 9.347c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.k5mj7db2t {
  d: path("M15.394 17.493c-.384.032-1.404.252-2.102 1.143c-.47.598-.498 1.44-.52 2.068q-.005.176-.014.326q-.016.216-.07.362c-.054.155.04.342.2.332c.58-.036 1.018-.162 1.665-.705c.492-.413.742-1.062.85-1.716c.044.661.229 1.332.678 1.792c.59.604 1.013.773 1.586.866c.158.026.27-.151.232-.31a1.4 1.4 0 0 1-.034-.368q.006-.151.018-.326c.041-.628.095-1.468-.313-2.11c-.606-.955-1.6-1.274-1.979-1.344c-.047.16-.092.359-.127.582a5 5 0 0 0-.07-.592");
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lb-r4td4r {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.74 9.808c.064.085-.069.188-.22.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.135.389-.05");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhr-ibb6r {
  d: path("M23.313 25.293c0-.401.326-.732.727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1H24.04a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkv_7obls {
  fill: var(--svg-color--000, #000);
  d: path("M17.295 10.512a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.061-.235");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lzg318lcd {
  stop-color: var(--svg-color--4f4c4b, #4F4C4B);
  stop-opacity: 0;
}

.m6lhrcc1m {
  stop-color: var(--svg-color--e1d7df, #E1D7DF);
}

.m7jeiwb9a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.833 28.555h1.797");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbqqxmbsg {
  stop-color: var(--svg-color--361e25, #361E25);
  stop-opacity: 0;
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.mejh1wbdq {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
  stop-opacity: 0;
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.nujrjcctj {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M13.842 8.46c-.72-.067-1.183.214-1.295.317a.473.473 0 0 1-.64-.695c.306-.282 1.032-.656 2.023-.563a.473.473 0 1 1-.088.941");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.obss6-bml {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.24 10.493l-.531 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.765 0");
}

.oc59d5-1h {
  d: path("M10.25 2.083a1.933 1.933 0 0 0-.681 3.743a.215.215 0 0 1 .143.198v1.051c0 .249.201.45.45.45H21.26a.45.45 0 0 0 .45-.45V6.02c0-.088.059-.166.141-.197a1.934 1.934 0 0 0-.69-3.74z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpn5ibfj {
  stop-color: var(--svg-color--e29457, #E29457);
}

.ongktybvd {
  stop-color: var(--svg-color--a499b2, #A499B2);
  stop-opacity: 0;
}

.ox62rwbrf {
  stop-color: var(--svg-color--e1dbe8, #E1DBE8);
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q2b_s4bxz {
  d: path("M13.435 9.619a.893.893 0 0 0-.86 1.128H14.3a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.q2rhgqb4s {
  stop-color: var(--svg-color--998ba1, #998BA1);
}

.q6fjdp0or {
  d: path("M17.806 9.619a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .865-1.129");
}

.qdng1m96y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.833 25.945h1.797");
}

.qdxhbpb0p {
  fill: var(--svg-color--b2a5bc, #B2A5BC);
  d: path("M19.722 25.382a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.qeyngbb0g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.755 27.25h1.797");
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qk3h5tshn {
  stop-color: var(--svg-color--beb0cc, #BEB0CC);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r_hj_bbby {
  fill: var(--svg-color--9c95a4, #9C95A4);
  d: path("M20.741 28.127a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.r37diw65a {
  stop-color: var(--svg-color--f4b183, #F4B183);
  stop-opacity: 0;
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.r77l3mbhz {
  fill: var(--svg-color--9c95a4, #9C95A4);
  d: path("M19.991 21.607a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.r9jwp9ffy {
  d: path("m15.24 10.493l-.531 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.765 0");
}

.rqng-o75v {
  d: path("M8.681 17.998h10.053c2.176 0 3.947 1.796 3.947 4.003v7.997h-14z");
}

.rrna_jb6d {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.013 9.347c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34H16.87a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.rvini-b1k {
  stop-color: var(--svg-color--aa99ac, #AA99AC);
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.s1n30k-8i {
  d: path("M8.681 17.97a10.96 10.96 0 0 0-4 8.477v3.55h4z");
}

.sc_sq1rcf {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M15.661 15.467c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.501c0-3.422-1.554-6.482-4-8.499v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.sf_e44b2v {
  stop-color: var(--svg-color--443b39, #443B39);
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.sli_wqbvh {
  stop-color: var(--svg-color--998ba1, #998BA1);
  stop-opacity: 0;
}

.t0vu2z0fa {
  fill: var(--svg-color--000, #000);
  d: path("M13.947 10.512a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.235");
}

.trde_l8na {
  d: path("M26.664 23.054a.97.97 0 0 1 .967.967v2.215h-1.934V24.02a.976.976 0 0 1 .967-.967");
}

.u7axe2baw {
  stop-color: var(--svg-color--9183a0, #9183A0);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.vzy_pqbvx {
  fill: var(--svg-color--af99ad, #AF99AD);
  d: path("M19.722 21.752a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w3fh2kkny {
  d: path("M13.468 18.681c.67-.924 1.704-1.194 2.097-1.245c.205.83.308 2.667-.684 3.564c-.635.574-1.077.722-1.67.786c-.163.018-.269-.164-.221-.321c.03-.101.05-.22.053-.366c.009-.634-.11-1.68.425-2.418");
}

.wd7-xxbdp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.227 8.319c.21-.193.803-.52 1.659-.44");
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wu63rebjw {
  stop-color: var(--svg-color--361e25, #361E25);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x6fwodqnd {
  d: path("M18.602 10.394a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xhfcb3qnc {
  cx: 20.393px;
  cy: 10.779px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.xkvuqmb_j {
  fill: var(--svg-color--b5a5c5, #B5A5C5);
  d: path("M20.472 28.272a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.xl-_vsb8m {
  d: path("M15.661 15.467c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.501c0-3.422-1.554-6.482-4-8.499v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.xt4dnx1tg {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.26 13.539a2.96 2.96 0 0 0 1.363.323c.505 0 .97-.118 1.364-.323a.204.204 0 0 1 .241.04a.186.186 0 0 1 .021.24m-2.99-.28l2.949.253m-2.948-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.221.253m3.21.028l-.041-.028m.041.028l-.041-.028m.041.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.869m3.21-.028c-.335.508-.919.847-1.584.847s-1.25-.339-1.584-.847m-.042.028l.042-.028m-.042.028l.042-.028");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y7qcqib5l {
  stop-color: var(--svg-color--5a4340, #5A4340);
  stop-opacity: 0;
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.ysetj63ow {
  stop-color: var(--svg-color--9785a0, #9785A0);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yv8ms4m5l {
  d: path("M21.455 8.693V7.255H19.98c.047.14.198.471.425.69c.227.22.303.597.303.81v1.395c.237 0 .331-.114.549-.53c.174-.333.205-.757.198-.927");
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zab3c9ypw {
  stop-color: var(--svg-color--a8a0af, #A8A0AF);
  stop-opacity: 0;
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.ztvu2mbem {
  stop-color: var(--svg-color--9c8fab, #9C8FAB);
}

.zvqnwo5qe {
  cx: 10.871px;
  cy: 10.779px;
  r: 0.996px;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zx2qd4bhl {
  stop-color: var(--svg-color--5a4340, #5A4340);
}

</style>
