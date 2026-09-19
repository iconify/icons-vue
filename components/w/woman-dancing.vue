<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGDZuTc)"><path fill="url(#iN7wsjb)" class="jvy1spb5y"/><path fill="url(#ioyQg4d)" class="jvy1spb5y"/><path fill="url(#igslFFe)" class="jvy1spb5y"/><path fill="url(#i0zbg9c)" class="jvy1spb5y"/><path fill="url(#iJKSwPb)" class="jvy1spb5y"/></g><path fill="url(#ih58lPd)" class="jvy1spb5y"/><path fill="url(#i4Wc1Fe)" class="uwqjkbvol"/><path fill="url(#imd4NIb)" class="uwqjkbvol"/><path fill="url(#i1Vpllf)" class="uwqjkbvol"/><g filter="url(#iJrPonb)"><path class="gi2arrbdt"/></g><g filter="url(#ihiwQ4a)"><path class="u8l8bnbbx"/></g><path fill="url(#iZGm6wc)" class="ifk4wkbgx"/><path fill="url(#i1ynvbt)" class="a2ysf6bzt"/><g filter="url(#ibSSQPc)"><path class="sxfolecfg"/></g><path fill="url(#iOokYOb)" class="qeacnbbth"/><path fill="url(#ioOnTne)" class="qeacnbbth"/><path fill="url(#iWgOAVc)" class="qeacnbbth"/><path fill="url(#ixv0uOb)" class="qeacnbbth"/><g filter="url(#izVSgZb)"><path fill="url(#iLuyZJb)" class="e648o_baz"/><path fill="url(#ikP0P5c)" class="e648o_baz"/><path fill="url(#iLMCzNd)" class="e648o_baz"/><path fill="url(#i8uPQSc)" class="e648o_baz"/></g><g filter="url(#i6u1DsY)"><path fill="url(#i9huZKN)" class="d49vq-b3b"/><path fill="url(#i60rmed)" class="d49vq-b3b"/><path fill="url(#i3wkpUc)" class="d49vq-b3b"/></g><path fill="url(#iW7Dhmc)" class="d49vq-b3b"/><path fill="url(#iLbqbCd)" class="d49vq-b3b"/><g filter="url(#iufenld)"><path class="d15flxx9h"/></g><g filter="url(#iY4aotc)"><path class="ip7sig10h"/><path fill="url(#iTVOijQ)" class="bds0mc2jk"/></g><path fill="url(#isqEP0d)" class="ws5-tkbbq"/><path fill="url(#ifg9yvc)" class="ws5-tkbbq"/><g filter="url(#i6U9ndc)"><path fill="url(#in9pDQc)" class="c1q2hvb_u"/></g><g filter="url(#iA9I6HD)"><path fill="url(#iyhUPVb)" class="a4iyzzbbh"/></g><g filter="url(#i1HFHfc)"><path class="p9buofj5o"/><path fill="url(#iuU0bkc)" class="ry2u4ettk"/></g><g filter="url(#izCTXRc)"><path class="tokl5obpo"/><path fill="url(#ixemKEe)" class="ga4l9mfxp"/></g><path fill="url(#iYiFJsS)" class="dq9tr21aa"/><path fill="url(#i6UgCFe)" class="dq9tr21aa"/><path fill="url(#iyO5U3d)" class="dq9tr21aa"/><path fill="url(#i7tDwyL)" class="dq9tr21aa"/><path fill="url(#iA5GEdd)" class="dq9tr21aa"/><g filter="url(#i9tE0ue)"><path class="s0t3b5bsy"/></g><g filter="url(#ifo8yqY)"><path fill="url(#i8LCzDk)" class="wekyuhbgq"/><path fill="url(#ilYdewn)" class="wekyuhbgq"/><path fill="url(#icwhgVb)" class="wekyuhbgq"/><path fill="url(#ie6NkdT)" class="wekyuhbgq"/></g><path class="qwi8yijyk"/><g filter="url(#iMZEA0G)"><path class="o8ttlvbbv"/></g><g filter="url(#iafeW7A)"><path class="d9icb2zol"/></g><g filter="url(#ijwKwec)"><path class="bpimejb0o"/></g><g filter="url(#ie0vXFp)"><path clip-rule="evenodd" class="e-8-lqb6c"/></g><path class="vxxn0wvyn"/><path fill="url(#iZXEwsd)" class="qrshpjbyu"/><path class="tftcpfbts"/><g filter="url(#idI4nAc)"><path class="kblmseblg"/><path fill="url(#igbmEve)" class="xrcay_bay"/></g><g filter="url(#iqPBXTi)"><path fill="url(#iCtITVb)" class="pfx98bcnv"/></g><path class="szh_6ccyb"/><path fill="url(#iJ5RRcu)" class="cuc6i6ptf"/><path class="qx37jk62h"/><g filter="url(#iakiOIy)"><path fill="url(#i3XYbQe)" class="z1kl9cbka"/></g><g filter="url(#ii2hfbe)"><ellipse transform="rotate(-27.914 11.116 5.718)" class="p5rbushok"/><ellipse fill="url(#ikGW1hc)" transform="rotate(-27.914 11.116 5.718)" class="za0h8_bfn"/></g><g filter="url(#ioCTQCe)"><path class="dt832ccha"/><path fill="url(#iVI9vnQ)" class="a1n06i0zb"/><path fill="url(#iFOzyec)" class="a1n06i0zb"/><path fill="url(#iV9kXqc)" class="a1n06i0zb"/></g><g filter="url(#igzHUWb)"><path fill="url(#iaPypic)" clip-rule="evenodd" class="kkds9sbif"/></g><g filter="url(#iBEUIMb)"><path fill="url(#iJGx8Rc)" clip-rule="evenodd" class="ga74agm1p"/></g><defs><radialGradient id="iN7wsjb" cx="0" cy="0" r="1" gradientTransform="rotate(78.857 5.16 9.481)scale(6.30639 6.26922)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ac74pxb4g"/><stop offset="1" class="n-pg25r_f"/></radialGradient><radialGradient id="ioyQg4d" cx="0" cy="0" r="1" gradientTransform="rotate(-118.32 8.761 3.708)scale(6.38977 11.6013)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="bo3m2cq3s"/><stop offset="1" class="jxb9upbaz"/></radialGradient><radialGradient id="igslFFe" cx="0" cy="0" r="1" gradientTransform="matrix(2.8125 .98437 -1.3538 3.868 13.185 7.46)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ruuksdskt"/><stop offset="1" class="xs-pbrfux"/></radialGradient><radialGradient id="i0zbg9c" cx="0" cy="0" r="1" gradientTransform="rotate(148.061 4.365 5.536)scale(4.67675 4.03986)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="hpsx2qbbm"/><stop offset="1" class="i7fuhyp3t"/></radialGradient><radialGradient id="iJKSwPb" cx="0" cy="0" r="1" gradientTransform="rotate(128.928 3.58 5.606)scale(1.15199 1.13106)" gradientUnits="userSpaceOnUse"><stop offset=".262" class="lz2kt3bcs"/><stop offset="1" class="mvps8dl8q"/></radialGradient><radialGradient id="ih58lPd" cx="0" cy="0" r="1" gradientTransform="rotate(59.146 3.463 10.989)scale(1.54581 3.33775)" gradientUnits="userSpaceOnUse"><stop class="dl0pwpa4e"/><stop offset="1" class="l2sdh-27q"/></radialGradient><radialGradient id="i1Vpllf" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72861 4.02946 -1.91414 -.82115 8.63 27.856)" gradientUnits="userSpaceOnUse"><stop class="rxdm1gb4b"/><stop offset="1" class="en9rkbb0o"/></radialGradient><radialGradient id="i1ynvbt" cx="0" cy="0" r="1" gradientTransform="rotate(117.071 -3.416 17.085)scale(2.08793 1.98277)" gradientUnits="userSpaceOnUse"><stop class="u6ezkbbkd"/><stop offset="1" class="cpmw12bkg"/></radialGradient><radialGradient id="iOokYOb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.214 1.125 -1.1662 -1.25845 22.774 3.711)" gradientUnits="userSpaceOnUse"><stop class="bgozq8y0t"/><stop offset="1" class="kvfe0w2um"/></radialGradient><radialGradient id="ioOnTne" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 .75 -.5221 -.47859 20.685 3.399)" gradientUnits="userSpaceOnUse"><stop class="ell555b-a"/><stop offset="1" class="gx806ib7y"/></radialGradient><radialGradient id="iWgOAVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.125 -1.17925 0 20.872 7.586)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="cyd9f573s"/><stop offset="1" class="fua9u6bte"/></radialGradient><radialGradient id="ixv0uOb" cx="0" cy="0" r="1" gradientTransform="matrix(3.28125 0 0 .75 15.185 9.742)" gradientUnits="userSpaceOnUse"><stop class="z0ce-5bzk"/><stop offset="1" class="c1krl9btc"/></radialGradient><radialGradient id="iLuyZJb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.18747 -5.71878 5.09832 -4.62466 15.278 14.836)" gradientUnits="userSpaceOnUse"><stop class="zstr-2b3h"/><stop offset="1" class="r38-lhbhs"/></radialGradient><radialGradient id="ikP0P5c" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 -.45703 .8012 5.4783 9.84 12.324)" gradientUnits="userSpaceOnUse"><stop offset=".481" class="dz8dqqbnh"/><stop offset="1" class="hv09-7aho"/></radialGradient><radialGradient id="iLMCzNd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 0 0 -4.28125 16.153 9.867)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="d1nygi1_s"/><stop offset="1" class="bzjd0s3dz"/></radialGradient><radialGradient id="i8uPQSc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14245 .25001 -.22815 -1.9551 15.952 12.71)" gradientUnits="userSpaceOnUse"><stop class="etzb8g0rx"/><stop offset="1" class="q_d1lub6r"/></radialGradient><radialGradient id="i9huZKN" cx="0" cy="0" r="1" gradientTransform="rotate(45.496 -14.752 21.43)scale(10.2092 15.8767)" gradientUnits="userSpaceOnUse"><stop class="h84ffkb2i"/><stop offset="1" class="emq3pu1ym"/></radialGradient><radialGradient id="i3wkpUc" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -4.4375 3.8181 .75287 27.06 16.648)" gradientUnits="userSpaceOnUse"><stop offset=".37" class="c4hclxboa"/><stop offset="1" class="mz51gmfzq"/></radialGradient><radialGradient id="iW7Dhmc" cx="0" cy="0" r="1" gradientTransform="matrix(4.72488 -2.8426 6.67598 11.09657 4.788 29.252)" gradientUnits="userSpaceOnUse"><stop class="ket8l8b0j"/><stop offset="1" class="lze6x5b3f"/></radialGradient><radialGradient id="iLbqbCd" cx="0" cy="0" r="1" gradientTransform="matrix(.81156 -4.64805 2.43505 .42516 28.216 17.497)" gradientUnits="userSpaceOnUse"><stop class="m8u-j2bfh"/><stop offset="1" class="xbj9zzvwg"/></radialGradient><radialGradient id="iTVOijQ" cx="0" cy="0" r="1" gradientTransform="rotate(146.197 4.07 6.302)scale(2.1345 2.96029)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="iustk2bzv"/><stop offset="1" class="aa7zv3brh"/></radialGradient><radialGradient id="isqEP0d" cx="0" cy="0" r="1" gradientTransform="rotate(-56.976 15.736 -6.59)scale(1.86357 2.40477)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="zxijwrkla"/><stop offset="1" class="bo4fo6bbz"/></radialGradient><radialGradient id="ifg9yvc" cx="0" cy="0" r="1" gradientTransform="rotate(47.291 -3.816 17.657)scale(1.79682 5.00055)" gradientUnits="userSpaceOnUse"><stop class="r4hgb6bsu"/><stop offset="1" class="azf933b1h"/></radialGradient><radialGradient id="iyhUPVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.18223 -.53738 .65611 1.44344 14.2 6.256)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iuU0bkc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 24.438 -37.318)scale(.61964)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="ixemKEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.51017 0 0 -.48801 10.065 6.047)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iYiFJsS" cx="0" cy="0" r="1" gradientTransform="rotate(141.306 6.056 5.14)scale(5.29858 4.93449)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="h_1qpybxa"/></radialGradient><radialGradient id="i6UgCFe" cx="0" cy="0" r="1" gradientTransform="matrix(.39752 -1.92132 2.43779 .50437 11.246 9.013)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iyO5U3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.54658 .6708 0 13.375 5.593)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="i7tDwyL" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.64596 .74031 0 11.37 5.634)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iA5GEdd" cx="0" cy="0" r="1" gradientTransform="rotate(137.064 6.277 5.296)scale(2.70714 3.12769)" gradientUnits="userSpaceOnUse"><stop class="fvfwd9b2i"/><stop offset="1" class="sr_-7-5tk"/></radialGradient><radialGradient id="ilYdewn" cx="0" cy="0" r="1" gradientTransform="matrix(-.33127 -1.16355 .6658 -.18956 12.655 6.645)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iZXEwsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38577 -.61361 0 13.319 5.764)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="igbmEve" cx="0" cy="0" r="1" gradientTransform="matrix(-.11006 -.14182 .19525 -.15152 13.21 5.803)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJ5RRcu" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38577 -.61362 0 11.246 5.764)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ikGW1hc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 8.443 -2.535)scale(.23448 .28186)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVI9vnQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.8358 1.27533 -1.8234 -1.19497 13.17 3.242)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="t7mz97-qi"/><stop offset="1" class="t_ovd3gtv"/></radialGradient><radialGradient id="iFOzyec" cx="0" cy="0" r="1" gradientTransform="rotate(142.413 5.737 3.52)scale(3.30578 3.33435)" gradientUnits="userSpaceOnUse"><stop offset=".842" class="vurgnx4vo"/><stop offset="1" class="uh31b8bkh"/></radialGradient><radialGradient id="iV9kXqc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41321 0 0 -1.02779 13.912 4.224)" gradientUnits="userSpaceOnUse"><stop class="t68nuubkx"/><stop offset="1" class="y6mwbuj6k"/></radialGradient><filter id="iGDZuTc" width="11.865" height="12.477" x="4.894" y="1.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.658824 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.396078 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_606" result="effect2_innerShadow_4002_606"/></filter><filter id="iJrPonb" width="5.901" height="8.773" x="16.966" y="21.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.517647 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/></filter><filter id="ihiwQ4a" width="4.034" height="2.448" x="19.082" y="27.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.219608 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/></filter><filter id="ibSSQPc" width="8.253" height="7.777" x="14.521" y="2.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.639216 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.490196 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_606" result="effect2_innerShadow_4002_606"/></filter><filter id="izVSgZb" width="7.93" height="8.273" x="9.022" y="7.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.207843 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/></filter><filter id="i6u1DsY" width="24.323" height="17.206" x="4.092" y="13.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.27451 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.2 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_606" result="effect2_innerShadow_4002_606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.141176 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_606" result="effect3_innerShadow_4002_606"/></filter><filter id="iufenld" width="2.218" height="2.723" x="4.114" y="15.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.494118 0 0 0 0 0.0431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/></filter><filter id="iY4aotc" width="7.274" height="8.998" x="3.684" y="8.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.65098 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.607843 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_606" result="effect2_innerShadow_4002_606"/></filter><filter id="i6U9ndc" width="1.629" height="1.529" x="9.292" y="5.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/></filter><filter id="iA9I6HD" width="1.529" height="1.779" x="13.81" y="5.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/></filter><filter id="i1HFHfc" width="1.22" height="1.22" x="13.964" y="5.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_606" stdDeviation=".05"/></filter><filter id="izCTXRc" width="1.22" height="1.22" x="9.455" y="5.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_606" stdDeviation=".05"/></filter><filter id="i9tE0ue" width="1.892" height="2.274" x="11.259" y="5.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_606" stdDeviation=".25"/></filter><filter id="ifo8yqY" width=".992" height="1.374" x="11.786" y="5.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_606" stdDeviation=".025"/></filter><filter id="iMZEA0G" width="1.531" height=".611" x="12.624" y="5.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/></filter><filter id="iafeW7A" width="1.531" height=".611" x="10.409" y="5.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/></filter><filter id="ijwKwec" width="1.27" height=".623" x="10.473" y="4.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/></filter><filter id="ie0vXFp" width="1.27" height=".623" x="13.046" y="4.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/></filter><filter id="idI4nAc" width=".478" height=".436" x="12.917" y="5.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_606" stdDeviation=".05"/></filter><filter id="iqPBXTi" width=".632" height=".643" x="13.263" y="5.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_606" stdDeviation=".1"/></filter><filter id="iakiOIy" width=".677" height=".703" x="11.153" y="5.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_606" stdDeviation=".1"/></filter><filter id="ii2hfbe" width=".538" height=".439" x="10.847" y="5.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_606" stdDeviation=".05"/></filter><filter id="ioCTQCe" width="5.555" height="2.932" x="9.558" y="2.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_606" stdDeviation=".05"/></filter><filter id="igzHUWb" width="2.957" height="3.037" x="12.949" y="2.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.341176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_606" result="effect2_innerShadow_4002_606"/></filter><filter id="iBEUIMb" width="1.893" height="1.933" x="13.445" y="3.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.0627451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_606" result="effect2_innerShadow_4002_606"/></filter><linearGradient id="i4Wc1Fe" x1="21.631" x2="12.192" y1="20.756" y2="31.059" gradientUnits="userSpaceOnUse"><stop class="x_atgxb_v"/><stop offset="1" class="ppa6_abwh"/></linearGradient><linearGradient id="imd4NIb" x1="9.974" x2="19.537" y1="24.594" y2="28.553" gradientUnits="userSpaceOnUse"><stop class="yung1xdgy"/><stop offset="1" class="i-td5rxsk"/></linearGradient><linearGradient id="iZGm6wc" x1="11.126" x2="8.785" y1="27.476" y2="26.934" gradientUnits="userSpaceOnUse"><stop class="lw92mcbvd"/><stop offset="1" class="rz89_uzdo"/></linearGradient><linearGradient id="i60rmed" x1="28.216" x2="16.204" y1="17.367" y2="17.367" gradientUnits="userSpaceOnUse"><stop offset=".219" class="k2sx12b0p"/><stop offset="1" class="yu3j8mbni"/></linearGradient><linearGradient id="in9pDQc" x1="9.292" x2="10.698" y1="6.088" y2="6.088" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i8LCzDk" x1="12.282" x2="12.282" y1="7.015" y2="5.741" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="icwhgVb" x1="11.785" x2="12.191" y1="6.653" y2="6.703" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="ie6NkdT" x1="12.282" x2="12.282" y1="7.059" y2="6.769" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iCtITVb" x1="13.687" x2="13.538" y1="5.788" y2="5.88" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3XYbQe" x1="11.598" x2="11.449" y1="5.788" y2="5.88" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaPypic" x1="15.412" x2="14.05" y1="2.932" y2="5.276" gradientUnits="userSpaceOnUse"><stop class="y_ccjxb5k"/><stop offset="1" class="w39yz6l0u"/></linearGradient><linearGradient id="iJGx8Rc" x1="15.339" x2="13.856" y1="3.43" y2="4.383" gradientUnits="userSpaceOnUse"><stop class="wzt3udgik"/><stop offset="1" class="gn591vgmd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-dancing" /></template>
<style>
.a1n06i0zb {
  d: path("M10.2 4.574a.8.8 0 0 0-.367.434c-.356-.82-.117-1.38.25-1.647s.484-.158.992-.654c.508-.497 1.156-.678 2.523.079c1.094.605 1.399 1.444 1.414 1.788h-2.5a1.7 1.7 0 0 1-1.372-.648c-.056-.072-.192-.062-.235.019c-.182.337-.46.486-.705.63");
}

.a2ysf6bzt {
  d: path("m8.196 27.901l-.004.008a1.6 1.6 0 0 0-.18.883c.043.36.309.727.784 1.04c.257.17.594.062.751-.201l1.034-1.73z");
}

.a4iyzzbbh {
  d: path("M14.574 6.811a.764.764 0 1 0 0-1.528a.764.764 0 0 0 0 1.528");
}

.aa7zv3brh {
  stop-color: var(--svg-color--ffce35, #FFCE35);
  stop-opacity: 0;
}

.ac74pxb4g {
  stop-color: var(--svg-color--f0c537, #F0C537);
}

.azf933b1h {
  stop-color: var(--svg-color--fcad16, #FCAD16);
  stop-opacity: 0;
}

.bds0mc2jk {
  d: path("M10.83 9.487c.288.55.075 1.23-.476 1.518l-3.072 1.57c-.257.133-.449.238-.543.613l-.332 1.27a1 1 0 0 0-.032.276l.04 1.756a.486.486 0 1 1-.973 0v-.807l-.568.408a.25.25 0 0 0-.103.218l.056.956a.486.486 0 1 1-.971.057l-.07-1.2c-.007-.126 0-.349.137-.528l.541-.869l.184-1.733a3.13 3.13 0 0 1 1.657-2.41l3.007-1.571a1.125 1.125 0 0 1 1.518.476");
}

.bgozq8y0t {
  stop-color: var(--svg-color--fdc938, #FDC938);
}

.bo3m2cq3s {
  stop-color: var(--svg-color--e1691f, #E1691F);
}

.bo4fo6bbz {
  stop-color: var(--svg-color--eba410, #EBA410);
}

.bpimejb0o {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("M10.668 5.203h-.002v.001a.127.127 0 0 1-.13-.219h.001l.005-.003l.015-.009l.055-.028q.072-.035.195-.077c.161-.051.387-.095.63-.052a.127.127 0 1 1-.043.251c-.19-.033-.372 0-.51.044a1.3 1.3 0 0 0-.206.086z");
}

.bzjd0s3dz {
  stop-color: var(--svg-color--ff4660, #FF4660);
  stop-opacity: 0;
}

.c1krl9btc {
  stop-color: var(--svg-color--ffb92f, #FFB92F);
  stop-opacity: 0;
}

.c1q2hvb_u {
  d: path("M10.056 6.811a.764.764 0 1 0 0-1.528a.764.764 0 0 0 0 1.528");
}

.c4hclxboa {
  stop-color: var(--svg-color--e73e59, #E73E59);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpmw12bkg {
  stop-color: var(--svg-color--cc2e32, #CC2E32);
}

.cuc6i6ptf {
  d: path("M11.245 5.537a.424.424 0 0 0-.41.536h.82a.427.427 0 0 0-.41-.536");
}

.cyd9f573s {
  stop-color: var(--svg-color--ffd03e, #FFD03E);
}

.d15flxx9h {
  fill: var(--svg-color--e1912d, #E1912D);
  d: path("m5.042 17.508l-.35-.457l-.578-1.078l1.38-.516l.046 1.254l.2.26a.44.44 0 1 1-.698.537");
}

.d1nygi1_s {
  stop-color: var(--svg-color--ff4660, #FF4660);
}

.d49vq-b3b {
  d: path("M26.74 13.508q-.222 0-.424.062c-.318.077-.621.221-.994.399h-.001c-.292.139-.626.298-1.043.46c-1.5.587-3.218.587-4.062.587H11.59c-1.933 0-3.534 1.566-3.559 3.499c-.007.536-.011 1.23-.011 1.79c0 1.797-1.662 3.73-2.672 4.687c-.7.664-.868 1.063-.967 1.297l-.014.034l-.02.044l.011.008a2.617 2.617 0 0 0 2.45 3.539h.965c-.499-.101-1.097-.246-1.566-.422c-1.04-.39-1.14-1.27-1.113-1.613c.02-.265.226-1.332 1.636-1.332c.95 0 2.031.064 3.022.123c.632.037 1.227.073 1.728.088c1.048.032 2.12-.065 2.57-1.215c.47-1.43.848-1.91 1.907-1.91c.493.03.872.049 1.124.062l.306.016c.7.047 1.452-.089 1.64-1.36c.211-1.421 1.067-1.552 1.672-1.53c.664.023 1.594.023 2.016-.29c.422-.312.468-.883.468-1.304s.147-1.164 1.172-1.266c1.149-.115 1.375-.36 1.532-.578c.226-.317.239-.694.187-1.266c-.07-.777.115-1.26.582-1.558c.617-.395 1.073.047 1.168.84c.023.19.052.446.085.736c.09.803.21 1.862.306 2.467v-3.618c0-.786-.615-1.43-1.39-1.474v-.002z");
}

.d9icb2zol {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M11.74 5.777c-.127-.222-.318-.397-.73-.397a.8.8 0 0 0-.51.175c-.128.103-.111.235-.012.285l.264.15c.31-.1.652-.113.987-.213");
}

.dl0pwpa4e {
  stop-color: var(--svg-color--cea741, #CEA741);
}

.dq9tr21aa {
  d: path("M9.95 4.792a.9.9 0 0 1 .25-.218l.038-.022c.286-.166.605-.352.764-.835h.007c.139.291.625.857 1.503.857h1.737c.154.03.432.151.453.624l-.057 1.46c-.058 1.33-1.098 2.225-2.367 2.225S9.97 7.989 9.911 6.658l-.046-1.21h.006l-.005-.127l-.005-.145a.9.9 0 0 1 .089-.384");
}

.dt832ccha {
  fill: var(--svg-color--f7a427, #F7A427);
  d: path("M10.2 4.574a.8.8 0 0 0-.367.434c-.356-.82-.117-1.38.25-1.647s.484-.158.992-.654c.508-.497 1.156-.678 2.523.079c1.094.605 1.399 1.444 1.414 1.788h-2.5a1.7 1.7 0 0 1-1.372-.648c-.056-.072-.192-.062-.235.019c-.182.337-.46.486-.705.63");
}

.dz8dqqbnh {
  stop-color: var(--svg-color--d62645, #D62645);
}

.e-8-lqb6c {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m14.054 4.985l-.066.11za.127.127 0 0 1-.13.219h-.001l-.002-.001l-.054-.028a1 1 0 0 0-.162-.064a1.1 1.1 0 0 0-.51-.044a.127.127 0 0 1-.044-.25c.244-.044.47 0 .631.051a1.6 1.6 0 0 1 .265.114l.005.002z");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e648o_baz {
  d: path("M9.95 14.54v1.67l5.735-.155c-.375-1.555-.368-3.258-.211-3.64c.156-.384.453-.774.476-1.29c.024-.516-.172-1-.476-1.484a3.5 3.5 0 0 1-.344-.805a.55.55 0 0 0-.513-.399h-.768c-.068 0-.109.09-.169.122l-.956.496l-1.204-.617c-.906.039-2.078.257-2.304.562c-.227.305-.25 1.008-.094 1.883s.43 1.812.648 2.36c.175.437.193 1.046.18 1.296");
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ell555b-a {
  stop-color: var(--svg-color--ffca3f, #FFCA3F);
}

.emq3pu1ym {
  stop-color: var(--svg-color--da2e3d, #DA2E3D);
}

.en9rkbb0o {
  stop-color: var(--svg-color--6c1118, #6C1118);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.etzb8g0rx {
  stop-color: var(--svg-color--f22b4e, #F22B4E);
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.ft5dv1b6b {
  fill: none;
}

.fua9u6bte {
  stop-color: var(--svg-color--ffd03e, #FFD03E);
  stop-opacity: 0;
}

.fvfwd9b2i {
  stop-color: var(--svg-color--ef9025, #EF9025);
}

.ga4l9mfxp {
  d: path("M10.065 6.557a.51.51 0 1 0 0-1.02a.51.51 0 0 0 0 1.02");
}

.ga74agm1p {
  fill-rule: evenodd;
  d: path("m14.718 4.488l-.004.015c-.072.222-.282.352-.47.292c-.187-.061-.28-.29-.209-.512l.008-.02h-.039c-.226 0-.409-.159-.409-.356s.183-.356.409-.356h.007L14 3.506c-.043-.221.088-.433.293-.473c.194-.037.385.094.44.296l.004-.002c.181-.134.423-.113.54.045c.116.159.064.396-.118.53l-.016.01q.03.023.056.05c.162.168.178.415.036.551c-.133.128-.356.114-.517-.025");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gi2arrbdt {
  fill: var(--svg-color--ffc63e, #FFC63E);
  d: path("m19.653 28.71l-2.687-5.53l1.851-1.57l3.541 8.133a.1.1 0 0 1-.092.14h-.769c-1.012 0-1.594-.586-1.844-1.172");
}

.gn591vgmd {
  stop-color: var(--svg-color--c32e4e, #C32E4E);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gx806ib7y {
  stop-color: var(--svg-color--ffca3f, #FFCA3F);
  stop-opacity: 0;
}

.h_1qpybxa {
  stop-color: var(--svg-color--ee8620, #EE8620);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h84ffkb2i {
  stop-color: var(--svg-color--d42f4e, #D42F4E);
}

.hpsx2qbbm {
  stop-color: var(--svg-color--af4103, #AF4103);
}

.hv09-7aho {
  stop-color: var(--svg-color--d62645, #D62645);
  stop-opacity: 0;
}

.i-td5rxsk {
  stop-color: var(--svg-color--851e29, #851E29);
  stop-opacity: 0;
}

.i7fuhyp3t {
  stop-color: var(--svg-color--e7740e, #E7740E);
  stop-opacity: 0;
}

.ifk4wkbgx {
  d: path("m8.192 27.91l.719-1.45l2.555-.038l-1.919 3.209c-.157.263-.494.371-.751.202c-.475-.313-.741-.682-.784-1.04a1.6 1.6 0 0 1 .18-.884");
}

.ip7sig10h {
  fill: var(--svg-color--ffc237, #FFC237);
  d: path("M10.83 9.487c.288.55.075 1.23-.476 1.518l-3.072 1.57c-.257.133-.449.238-.543.613l-.332 1.27a1 1 0 0 0-.032.276l.04 1.756a.486.486 0 1 1-.973 0v-.807l-.568.408a.25.25 0 0 0-.103.218l.056.956a.486.486 0 1 1-.971.057l-.07-1.2c-.007-.126 0-.349.137-.528l.541-.869l.184-1.733a3.13 3.13 0 0 1 1.657-2.41l3.007-1.571a1.125 1.125 0 0 1 1.518.476");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iustk2bzv {
  stop-color: var(--svg-color--ffce35, #FFCE35);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.jvy1spb5y {
  d: path("M9.247 3.367a3 3 0 0 1 1.484-.558a.3.3 0 0 0 .203-.103c.397-.476.853-.62 1.227-.62c.564 0 .932.2 1.07.289c.29.188.485.313.915.43s1.335 1.351 1.601 1.75c.266.398.14.78.14 1.015s.157.313.204.75c.034.316-.09.706-.177.91a.11.11 0 0 0 .016.11c.624.78.433 2.055.255 2.605h-3.641v2.344c-.646.583-2.375 1.688-4.125 1.438c-2.188-.313-4.016-2.532-3.406-4.813c.446-1.67 1.998-2.368 2.905-2.554a.27.27 0 0 0 .22-.279c-.062-1.253.212-2.067 1.11-2.714");
}

.jxb9upbaz {
  stop-color: var(--svg-color--e1691f, #E1691F);
  stop-opacity: 0;
}

.k2sx12b0p {
  stop-color: var(--svg-color--db2f4a, #DB2F4A);
}

.kblmseblg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.288 5.626c.03.04-.033.09-.105.144c-.071.053-.125.091-.155.05s.004-.116.075-.17c.072-.053.155-.064.185-.024");
}

.ket8l8b0j {
  stop-color: var(--svg-color--d32659, #D32659);
}

.kkds9sbif {
  fill-rule: evenodd;
  d: path("M14.85 4.965c.013-.04.067-.057.1-.032a.599.599 0 1 0 .711-.963a.067.067 0 0 1 0-.104a.598.598 0 0 0-.705-.967c-.035.025-.09.007-.102-.034a.6.6 0 1 0-1.14.368c.014.04-.02.087-.062.087h-.004a.599.599 0 0 0 0 1.197c.04 0 .073.044.061.083a.599.599 0 0 0 1.14.365");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kvfe0w2um {
  stop-color: var(--svg-color--fdc938, #FDC938);
  stop-opacity: 0;
}

.l2sdh-27q {
  stop-color: var(--svg-color--cea741, #CEA741);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lw92mcbvd {
  stop-color: var(--svg-color--e69934, #E69934);
}

.lz2kt3bcs {
  stop-color: var(--svg-color--c0500a, #C0500A);
}

.lze6x5b3f {
  stop-color: var(--svg-color--d32659, #D32659);
  stop-opacity: 0;
}

.m8u-j2bfh {
  stop-color: var(--svg-color--b01b4b, #B01B4B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mvps8dl8q {
  stop-color: var(--svg-color--c0500a, #C0500A);
  stop-opacity: 0;
}

.mz51gmfzq {
  stop-color: var(--svg-color--e73e59, #E73E59);
  stop-opacity: 0;
}

.n-pg25r_f {
  stop-color: var(--svg-color--ff971f, #FF971F);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o8ttlvbbv {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M12.824 5.777c.126-.222.318-.397.73-.397c.181 0 .355.05.51.175c.128.103.11.235.012.285l-.264.15c-.31-.1-.652-.113-.988-.213");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p5rbushok {
  cx: 11.116px;
  cy: 5.718px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.185px;
  ry: 0.094px;
}

.p9buofj5o {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M14.575 6.557a.51.51 0 1 0 0-1.02a.51.51 0 0 0 0 1.02");
}

.pfx98bcnv {
  d: path("M13.696 5.904a.4.4 0 0 0-.11-.219l-.123.135l.056.108z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppa6_abwh {
  stop-color: var(--svg-color--9a3037, #9A3037);
}

.q_d1lub6r {
  stop-color: var(--svg-color--f22b4e, #F22B4E);
  stop-opacity: 0;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qeacnbbth {
  d: path("M18.636 8.508h-4.115l.554 2.203h3.508c1.486 0 2.375-1.062 2.297-2.656l-.076-2.34a.1.1 0 0 1 .077-.102c.205-.053.56-.154.784-.214a1 1 0 0 0 .508-.344l.506-.744a.546.546 0 1 0-.907-.609l-.294.443a.17.17 0 0 1-.074.063c-.395.168-.904.173-1.137.163l.28-.268a.533.533 0 0 0-.705-.798l-.4.328c-.132.12-.417.448-.492.805a2.8 2.8 0 0 0-.028.757c.013.152.024.304.015.455l-.15 2.716a.15.15 0 0 1-.15.142");
}

.qrshpjbyu {
  d: path("M13.32 5.537a.424.424 0 0 1 .409.536h-.82a.426.426 0 0 1 .41-.536");
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwi8yijyk {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M12.282 7.43c-.248 0-.48-.06-.675-.164c-.067-.035-.139.042-.097.104a.918.918 0 0 0 1.543 0c.042-.064-.03-.139-.096-.104a1.4 1.4 0 0 1-.675.164");
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.qx37jk62h {
  fill: var(--svg-color--000, #000);
  d: path("M11.488 5.961a.24.24 0 0 0-.243-.243a.242.242 0 0 0-.216.355h.43a.24.24 0 0 0 .029-.112");
}

.r38-lhbhs {
  stop-color: var(--svg-color--e9283f, #E9283F);
}

.r4hgb6bsu {
  stop-color: var(--svg-color--c97000, #C97000);
}

.ruuksdskt {
  stop-color: var(--svg-color--e06b0e, #E06B0E);
}

.rxdm1gb4b {
  stop-color: var(--svg-color--6c1118, #6C1118);
}

.ry2u4ettk {
  d: path("M14.575 6.557a.51.51 0 1 0 0-1.02a.51.51 0 0 0 0 1.02");
}

.rz89_uzdo {
  stop-color: var(--svg-color--db7c1a, #DB7C1A);
}

.s0t3b5bsy {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m12.095 5.941l-.324.808a.256.256 0 0 0 .247.332h.373a.257.257 0 0 0 .248-.332l-.253-.808c-.054-.179-.234-.179-.29 0");
}

.sr_-7-5tk {
  stop-color: var(--svg-color--ef9025, #EF9025);
  stop-opacity: 0;
}

.sxfolecfg {
  fill: var(--svg-color--ffbc30, #FFBC30);
  d: path("M18.636 8.508h-4.115l.554 2.203h3.508c1.486 0 2.375-1.062 2.297-2.656l-.076-2.34a.1.1 0 0 1 .077-.102c.205-.053.56-.154.784-.214a1 1 0 0 0 .508-.344l.506-.744a.546.546 0 1 0-.907-.609l-.294.443a.17.17 0 0 1-.074.063c-.395.168-.904.173-1.137.163l.28-.268a.533.533 0 0 0-.705-.798l-.4.328c-.132.12-.417.448-.492.805a2.8 2.8 0 0 0-.028.757c.013.152.024.304.015.455l-.15 2.716a.15.15 0 0 1-.15.142");
}

.szh_6ccyb {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.146 5.408a.664.664 0 0 0-.643.503a.13.13 0 0 0 .127.161h1.06a.11.11 0 0 0 .107-.129a.665.665 0 0 0-.65-.535");
}

.t_ovd3gtv {
  stop-color: var(--svg-color--ffc426, #FFC426);
  stop-opacity: 0;
}

.t68nuubkx {
  stop-color: var(--svg-color--e16f21, #E16F21);
}

.t7mz97-qi {
  stop-color: var(--svg-color--ffc426, #FFC426);
}

.tftcpfbts {
  fill: var(--svg-color--000, #000);
  d: path("M13.076 5.961c0-.135.108-.243.243-.243a.242.242 0 0 1 .216.355h-.43a.2.2 0 0 1-.029-.112");
}

.tokl5obpo {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M10.065 6.557a.51.51 0 1 0 0-1.02a.51.51 0 0 0 0 1.02");
}

.u6ezkbbkd {
  stop-color: var(--svg-color--ee3148, #EE3148);
}

.u8l8bnbbx {
  fill: var(--svg-color--ff444f, #FF444F);
  d: path("m19.082 27.535l.571 1.176c.25.586.832 1.172 1.844 1.172h.77a.1.1 0 0 0 .091-.14l-.628-1.444z");
}

.uh31b8bkh {
  stop-color: var(--svg-color--f29d23, #F29D23);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uwqjkbvol {
  d: path("M15.782 29.914h-8.58c-.823-.182-2.47-.85-2.47-2.06c0-1.514 1.345-2.514 1.25-2.576c-.074-.05 3.025-2.425 4.583-3.606l13.045-5.58c.87-.697 2.796-2.081 3.535-2.037c.738.043 1.021 1.007 1.07 1.483v5.533c0 .921-.304 1.951-.985 2.404c-.68.453-1.212.343-2.26.343c-1.173 0-1.454.336-1.908 1.749c-.363 1.13-.985 1.381-1.9 1.381h-1.189c-.805 0-1.345.172-1.798 1.67c-.4 1.08-1.408 1.296-2.393 1.296");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vurgnx4vo {
  stop-color: var(--svg-color--f29d23, #F29D23);
  stop-opacity: 0;
}

.vxxn0wvyn {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.418 5.408c.31 0 .572.214.643.503a.13.13 0 0 1-.127.161h-1.06a.11.11 0 0 1-.108-.129a.664.664 0 0 1 .652-.535");
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w39yz6l0u {
  stop-color: var(--svg-color--dc2d68, #DC2D68);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wekyuhbgq {
  d: path("m12.1 5.875l-.252.808a.256.256 0 0 0 .247.332h.373a.257.257 0 0 0 .248-.332l-.253-.808c-.054-.179-.306-.179-.363 0");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.ws5-tkbbq {
  d: path("m13.116 10.256l-1.752-1.6l.383-.172h2.04V9.96a.4.4 0 0 1-.67.296");
}

.wzt3udgik {
  stop-color: var(--svg-color--c9334f, #C9334F);
}

.x_atgxb_v {
  stop-color: var(--svg-color--911c39, #911C39);
}

.xbj9zzvwg {
  stop-color: var(--svg-color--b01b4b, #B01B4B);
  stop-opacity: 0;
}

.xrcay_bay {
  d: path("M13.288 5.626c.03.04-.033.09-.105.144c-.071.053-.125.091-.155.05s.004-.116.075-.17c.072-.053.155-.064.185-.024");
}

.xs-pbrfux {
  stop-color: var(--svg-color--ff8610, #FF8610);
  stop-opacity: 0;
}

.y_ccjxb5k {
  stop-color: var(--svg-color--e73950, #E73950);
}

.y6mwbuj6k {
  stop-color: var(--svg-color--e16f21, #E16F21);
  stop-opacity: 0;
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yu3j8mbni {
  stop-color: var(--svg-color--db2f4a, #DB2F4A);
  stop-opacity: 0;
}

.yung1xdgy {
  stop-color: var(--svg-color--851e29, #851E29);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z0ce-5bzk {
  stop-color: var(--svg-color--ffb92f, #FFB92F);
}

.z1kl9cbka {
  d: path("M11.63 5.91c0-.137-.11-.227-.14-.255l-.137.132l.084.17z");
}

.za0h8_bfn {
  cx: 11.116px;
  cy: 5.718px;
  rx: 0.185px;
  ry: 0.094px;
}

.zstr-2b3h {
  stop-color: var(--svg-color--ff3b57, #FF3B57);
}

.zxijwrkla {
  stop-color: var(--svg-color--ffd23b, #FFD23B);
}

</style>
