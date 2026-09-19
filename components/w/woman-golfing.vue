<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="d2smg-bvf"/><path fill="url(#i8wZgEc)" clip-rule="evenodd" class="p4yinsbqr"/><path fill="url(#i1Ydgpd)" clip-rule="evenodd" class="p4yinsbqr"/><path fill="url(#iSxK1xd)" clip-rule="evenodd" class="p4yinsbqr"/><g filter="url(#iYtd1Pb)"><path fill="url(#i8tqcYr)" clip-rule="evenodd" class="xjxnzbcno"/></g><g filter="url(#iwlkZ6c)"><path class="yocnddcqz"/><path fill="url(#iRdq9jc)" class="sr1ckfb_s"/><path fill="url(#iGCEezc)" class="sr1ckfb_s"/></g><path fill="url(#isKmUcb)" class="i_ikeur-m"/><path fill="url(#ipd2Usb)" class="i_ikeur-m"/><path fill="url(#ivJANhb)" class="i_ikeur-m"/><g filter="url(#iQsAGNb)"><path class="ro68m4b1o"/></g><path class="w6_gecbjt"/><path fill="url(#iKQElOe)" class="bk0-xsbnt"/><path fill="url(#iejncvd)" class="bk0-xsbnt"/><path fill="url(#iGhBrZr)" class="bk0-xsbnt"/><path fill="url(#ih8ORqN)" class="bk0-xsbnt"/><g filter="url(#ickmAlc)"><path class="j5m1n_04i"/></g><path fill="url(#iAFS1Wx)" class="r_8igzxod"/><path fill="url(#i4cvBOc)" class="r_8igzxod"/><path fill="url(#ibwhNFd)" class="r_8igzxod"/><path fill="url(#ivFnzgc)" class="r_8igzxod"/><path fill="url(#igSQBxd)" class="r_8igzxod"/><path fill="url(#iBcydWL)" class="r_8igzxod"/><path fill="url(#iOfdqqc)" class="r_8igzxod"/><path fill="url(#iLcWRgd)" class="b1q481j-e"/><path fill="url(#iFmP0vc)" class="b1q481j-e"/><path fill="url(#iwV61gb)" class="b1q481j-e"/><path fill="url(#iAUHR2b)" class="b1q481j-e"/><path fill="url(#ioMvQCT)" class="b1q481j-e"/><rect fill="url(#inDeJbe)" transform="rotate(-26.783 20.65 4.151)" class="yuypg-bpl"/><rect fill="url(#ibrn6lG)" transform="rotate(-26.783 21.084 3.892)" class="bnk9occqx"/><rect fill="url(#i1cmN5d)" transform="rotate(-26.783 21.603 3.646)" class="qc-9lgb7u"/><rect fill="url(#i6K5nzt)" transform="rotate(-26.783 22.173 3.392)" class="e4n1ffbms"/><rect fill="url(#ixdailc)" transform="rotate(60 21.976 4.423)" class="u1g4dxbrg"/><g filter="url(#i0zhq1b)"><path class="g1axk00gm"/><path fill="url(#ixktAzw)" class="h3-hcc6xo"/></g><g filter="url(#ihveJPe)"><path fill="url(#iusfD2b)" class="zom_kry4o"/><path fill="url(#iI49Jwe)" class="zom_kry4o"/><path fill="url(#iCb2fQc)" class="zom_kry4o"/></g><g filter="url(#iFTDeny)"><path class="dhd6km3rx"/></g><g filter="url(#iNQaBob)"><path stroke="url(#ipPN1jb)" class="uw-_4rbwh"/></g><g filter="url(#if9BMwe)"><path fill="url(#iVy1Gyd)" class="e9z7ehngf"/></g><g filter="url(#izvqIme)"><path class="h4h5rsbrw"/></g><g filter="url(#iwKtNwd)"><path fill="url(#i9sUVGg)" class="diny9tbav"/></g><g filter="url(#iUxKgue)"><path class="dyid5_bjz"/><path fill="url(#i7xWIUb)" class="z1jkahbiz"/></g><g filter="url(#i5DCSzc)"><path class="z-tc3nh5j"/></g><path fill="url(#ixxWLjc)" class="nakpuljwd"/><path fill="url(#igvuXid)" class="nakpuljwd"/><path fill="url(#iaZrdGe)" class="nakpuljwd"/><g filter="url(#iUmcMRD)"><path class="mhnq3mo3j"/></g><g filter="url(#iK4rtee)"><path fill="url(#iRLxQyL)" class="b_b3xwxoo"/></g><g filter="url(#iuCuazc)"><path stroke="url(#iRGT2ac)" class="ynn_1cvkj"/></g><path class="nddod5b3z"/><g filter="url(#iRTEBgb)"><path class="yffvx8b_t"/></g><g filter="url(#iDqmjJd)"><path class="pd8kwccwo"/></g><g filter="url(#iOjH5jc)"><path class="g05smc5_v"/></g><g filter="url(#ilyx7He)"><path clip-rule="evenodd" class="rr3z7eg2t"/></g><path class="p2hc_mblf"/><path fill="url(#iszT7gd)" class="d-_ztzc9a"/><path class="a6h6mobhd"/><g filter="url(#igWZtme)"><path class="hw4b9obcq"/><path fill="url(#il6PV5d)" class="pdy5l7eay"/></g><g filter="url(#ilIs8Rb)"><path fill="url(#iflGiMc)" class="q8jh71bsc"/></g><path class="ybyttdvmz"/><path fill="url(#i4DRDoT)" class="ajs9ss72k"/><path class="k3wt0u04d"/><g filter="url(#imRIGLc)"><path fill="url(#iH2fNWT)" class="u1nv9tz7s"/></g><g filter="url(#iXdQvwb)"><ellipse transform="rotate(-53.05 13.61 6.442)" class="mw4zxhc4b"/><ellipse fill="url(#iUHba1b)" transform="rotate(-53.05 13.61 6.442)" class="k0h2lnbak"/></g><path fill="url(#ildX7je)" class="hznysmbpr"/><path fill="url(#ihjFFFv)" class="hznysmbpr"/><path fill="url(#iCA2uvc)" class="hznysmbpr"/><path fill="url(#iwhY6YQ)" class="hznysmbpr"/><g filter="url(#i2gp4ne)"><path fill="url(#i9Vrpjb)" class="qkq015b1v"/><path fill="url(#ilZwajd)" class="qkq015b1v"/></g><defs><radialGradient id="i8wZgEc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.275 11.99 -4.788)scale(2.46895 5.31465)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="ftqy6sbhb"/><stop offset="1" class="uy0edsrfa"/></radialGradient><radialGradient id="i1Ydgpd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.20313 -1.09374 1.2485 -3.65638 14.345 8.48)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="kld0av5cc"/><stop offset="1" class="cax3-9bdu"/></radialGradient><radialGradient id="iSxK1xd" cx="0" cy="0" r="1" gradientTransform="rotate(-110.339 9.3 -2.09)scale(2.26738)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="b4pae_ykk"/><stop offset="1" class="qqp8wrblx"/></radialGradient><radialGradient id="iRdq9jc" cx="0" cy="0" r="1" gradientTransform="rotate(146.915 8.765 5.942)scale(4.92324 2.04943)" gradientUnits="userSpaceOnUse"><stop class="ba1yb3bji"/><stop offset="1" class="kgrhzo17p"/></radialGradient><radialGradient id="ivJANhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .16016 -.21807 -.37232 24.841 2.984)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="i42zc8m6u"/><stop offset="1" class="dsumrvbgt"/></radialGradient><radialGradient id="iejncvd" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 -.46876 .24583 -.45888 14.133 29.59)" gradientUnits="userSpaceOnUse"><stop class="ynlfw99ba"/><stop offset="1" class="in-vfpgwh"/></radialGradient><radialGradient id="iGhBrZr" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .85157 -1.15842 -1.0415 12.743 27.082)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="vkrof_bbk"/><stop offset="1" class="h8hiq33uv"/></radialGradient><radialGradient id="ih8ORqN" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 .15625 -.58594 3.04687 11.368 28.48)" gradientUnits="userSpaceOnUse"><stop class="ilg8l_bzj"/><stop offset="1" class="s2j02zbkr"/></radialGradient><radialGradient id="i4cvBOc" cx="0" cy="0" r="1" gradientTransform="matrix(2.71873 -2.53127 .81258 .87276 13.166 28.043)" gradientUnits="userSpaceOnUse"><stop class="pcvpzjboo"/><stop offset="1" class="qe_2d-buv"/></radialGradient><radialGradient id="ibwhNFd" cx="0" cy="0" r="1" gradientTransform="matrix(2.54688 -2.64063 .2894 .27913 12.275 26.387)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="kxzgmzb5t"/><stop offset="1" class="xhu8yhbcw"/></radialGradient><radialGradient id="ivFnzgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 0 0 -5.02098 17.369 21.73)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="keljo6scd"/><stop offset="1" class="ps4m-ab9c"/></radialGradient><radialGradient id="igSQBxd" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 -.98437 1.15192 .05485 17.619 18.402)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="w5oxhdc5r"/><stop offset="1" class="ebs2-pbbe"/></radialGradient><radialGradient id="iBcydWL" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 0 0 7.6823 17.978 23.09)" gradientUnits="userSpaceOnUse"><stop class="j_l_30buh"/><stop offset="1" class="xi8fv135v"/></radialGradient><radialGradient id="iOfdqqc" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -3.34375 1.20794 1.23052 13.666 28.105)" gradientUnits="userSpaceOnUse"><stop class="ddjhanboc"/><stop offset="1" class="uu7_gub8n"/></radialGradient><radialGradient id="iLcWRgd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40533 1.69034 -2.35402 -6.13499 20.352 10.571)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="e05l2cs0p"/><stop offset="1" class="vokmvabvz"/></radialGradient><radialGradient id="iFmP0vc" cx="0" cy="0" r="1" gradientTransform="matrix(.57404 2.73801 -4.6268 .97003 17.28 7.367)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="xdvfs5b6o"/><stop offset="1" class="lpm73-wsn"/></radialGradient><radialGradient id="iAUHR2b" cx="0" cy="0" r="1" gradientTransform="matrix(.87501 1.59375 -2.6006 1.4278 15.29 8.073)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="lzqv--boa"/><stop offset="1" class="qgyv_0bxz"/></radialGradient><radialGradient id="ioMvQCT" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.01563 .0588 6.46896 13.478 10.48)" gradientUnits="userSpaceOnUse"><stop class="jwirzncnv"/><stop offset="1" class="td20orbdz"/></radialGradient><radialGradient id="inDeJbe" cx="0" cy="0" r="1" gradientTransform="matrix(.09624 .94236 -.56384 .05758 20.9 4.366)" gradientUnits="userSpaceOnUse"><stop class="hcmpzwvfn"/><stop offset="1" class="tzgzt3b1l"/></radialGradient><radialGradient id="ibrn6lG" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 21.76 4.56)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="euzbypbyq"/><stop offset="1" class="ob4ztkbap"/></radialGradient><radialGradient id="i1cmN5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.28 4.314)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="euzbypbyq"/><stop offset="1" class="ob4ztkbap"/></radialGradient><radialGradient id="i6K5nzt" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.849 4.06)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="euzbypbyq"/><stop offset="1" class="ob4ztkbap"/></radialGradient><radialGradient id="ixdailc" cx="0" cy="0" r="1" gradientTransform="matrix(-.02457 .47352 -.46721 -.02424 22.37 4.575)" gradientUnits="userSpaceOnUse"><stop class="usai76iql"/><stop offset=".931" class="muua73y8y"/></radialGradient><radialGradient id="ixktAzw" cx="0" cy="0" r="1" gradientTransform="matrix(3.80388 .30087 -.62375 7.88601 17.576 5.714)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="t_a14bpou"/><stop offset="1" class="ojy1jndng"/></radialGradient><radialGradient id="iI49Jwe" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 .21242 -.56203 4.5475 14.04 9.886)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="aidzwlkvm"/><stop offset="1" class="v3r5uzuwd"/></radialGradient><radialGradient id="iCb2fQc" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 .51562 -1.9883 .18075 16.181 8.87)" gradientUnits="userSpaceOnUse"><stop class="avihppb8x"/><stop offset="1" class="t3o1xnbhr"/></radialGradient><radialGradient id="i9sUVGg" cx="0" cy="0" r="1" gradientTransform="matrix(.74473 -.87445 1.06766 .90928 16.28 5.714)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="i7xWIUb" cx="0" cy="0" r="1" gradientTransform="rotate(-45.434 14.843 -16.883)scale(.54806)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="ixxWLjc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18751 1.98436 -1.85922 -2.9865 16.595 5.496)" gradientUnits="userSpaceOnUse"><stop class="dblh6zb0b"/><stop offset=".766" class="sedutetcs"/></radialGradient><radialGradient id="igvuXid" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 2.60937 -3.8815 1.81292 14.626 6.09)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="x16wh0r6i"/><stop offset=".969" class="n8b-cjbii"/></radialGradient><radialGradient id="iaZrdGe" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.59375 -1.70658 .87002 13.751 5.136)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="cqn7i9qhy"/><stop offset="1" class="q_w9u85di"/></radialGradient><radialGradient id="iszT7gd" cx="0" cy="0" r="1" gradientTransform="matrix(.14462 .3082 -.49024 .23003 15.389 5.652)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="il6PV5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.1414 -.0722 .0994 -.19466 15.317 5.724)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4DRDoT" cx="0" cy="0" r="1" gradientTransform="matrix(.14462 .30821 -.49024 .23003 13.729 6.43)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iUHba1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00326 -.20792 .24993 -.00391 13.603 6.575)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ildX7je" cx="0" cy="0" r="1" gradientTransform="rotate(106.89 5.816 7.311)scale(1.32268 1.71208)" gradientUnits="userSpaceOnUse"><stop class="ie8u9uubp"/><stop offset=".816" class="wg59hevzp"/></radialGradient><radialGradient id="ihjFFFv" cx="0" cy="0" r="1" gradientTransform="rotate(-83.991 9.391 -3.613)scale(2.68664 2.56641)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="ecxt7ybnv"/><stop offset="1" class="e8jaecbhx"/></radialGradient><radialGradient id="iCA2uvc" cx="0" cy="0" r="1" gradientTransform="rotate(-113.479 8.74 -2.048)scale(1.19248 2.52362)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="xtgg-5mjh"/><stop offset="1" class="cgn2r-bvw"/></radialGradient><radialGradient id="iwhY6YQ" cx="0" cy="0" r="1" gradientTransform="matrix(.30322 .55469 -2.64176 1.44413 12.892 3.035)" gradientUnits="userSpaceOnUse"><stop class="sgjix6b2q"/><stop offset="1" class="v-z7nrvme"/></radialGradient><radialGradient id="i9Vrpjb" cx="0" cy="0" r="1" gradientTransform="matrix(3.26562 -1.07812 1.92394 5.82757 12.586 5.793)" gradientUnits="userSpaceOnUse"><stop class="mtesmbwby"/><stop offset="1" class="m7l7lfb0p"/></radialGradient><radialGradient id="ilZwajd" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.5 .86462 .09907 15.133 4.574)" gradientUnits="userSpaceOnUse"><stop class="tva982odh"/><stop offset="1" class="jsz_uluep"/></radialGradient><filter id="iYtd1Pb" width="8.471" height="7.176" x="16.221" y="3.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.580392 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.545098 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22922" result="effect2_innerShadow_3987_22922"/></filter><filter id="iwlkZ6c" width="18.187" height="14.194" x="6.907" y="2.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><filter id="iQsAGNb" width="4.793" height="2.27" x="18.177" y="28.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.188235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><filter id="ickmAlc" width="8.989" height="12.477" x="12.161" y="16.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.635294 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><filter id="i0zhq1b" width="7.553" height="7.567" x="14.351" y="3.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.658824 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.537255 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22922" result="effect2_innerShadow_3987_22922"/></filter><filter id="ihveJPe" width="3.395" height="2.909" x="14.313" y="8.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.239216 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><filter id="iFTDeny" width="1.789" height="3.497" x="8.087" y="12.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".125"/></filter><filter id="iNQaBob" width="2.601" height="13.601" x="18.427" y="15.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".4"/></filter><filter id="if9BMwe" width="2.563" height="7.453" x="15.025" y="16.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".375"/></filter><filter id="izvqIme" width="1.402" height="1.352" x="12.208" y="6.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><filter id="iwKtNwd" width="1.352" height="1.602" x="15.826" y="4.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><filter id="iUxKgue" width="1.303" height="1.303" x="15.85" y="4.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".1"/></filter><filter id="i5DCSzc" width="1.303" height="1.303" x="12.24" y="6.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".1"/></filter><filter id="iUmcMRD" width="1.8" height="2.136" x="13.975" y="5.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".25"/></filter><filter id="iK4rtee" width="1.057" height="1.329" x="14.354" y="5.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".05"/></filter><filter id="iuCuazc" width="1.667" height="1.178" x="14.315" y="6.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".05"/></filter><filter id="iRTEBgb" width="1.254" height=".664" x="14.799" y="5.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><filter id="iDqmjJd" width="1.302" height=".675" x="13.029" y="6.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><filter id="iOjH5jc" width="1.021" height=".854" x="12.849" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><filter id="ilyx7He" width="1.136" height=".612" x="14.852" y="4.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><filter id="igWZtme" width=".384" height=".464" x="15.048" y="5.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".05"/></filter><filter id="ilIs8Rb" width=".618" height=".62" x="15.327" y="5.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".1"/></filter><filter id="imRIGLc" width=".669" height=".663" x="13.625" y="6.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".1"/></filter><filter id="iXdQvwb" width=".438" height=".481" x="13.391" y="6.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22922" stdDeviation=".05"/></filter><filter id="i2gp4ne" width="4.253" height="2.433" x="11.907" y="3.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.34902 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22922"/></filter><linearGradient id="i8tqcYr" x1="23.013" x2="19.956" y1="5.156" y2="11.161" gradientUnits="userSpaceOnUse"><stop class="ksevddbvl"/><stop offset=".799" class="d30rw76zq"/></linearGradient><linearGradient id="iGCEezc" x1="12.493" x2="12.822" y1="9.586" y2="10.058" gradientUnits="userSpaceOnUse"><stop offset=".349" class="lr97j31fb"/><stop offset="1" class="azn0z--js"/></linearGradient><linearGradient id="isKmUcb" x1="24.916" x2="22.775" y1="3.105" y2="4.418" gradientUnits="userSpaceOnUse"><stop class="ds3hm--8v"/><stop offset="1" class="bq7w62n5j"/></linearGradient><linearGradient id="ipd2Usb" x1="23.884" x2="23.619" y1="4.105" y2="3.574" gradientUnits="userSpaceOnUse"><stop class="seeiowbir"/><stop offset="1" class="tw6dxpb7y"/></linearGradient><linearGradient id="iKQElOe" x1="12.697" x2="12.697" y1="30.441" y2="29.769" gradientUnits="userSpaceOnUse"><stop class="dhem-xbnm"/><stop offset="1" class="zn47ozbfv"/></linearGradient><linearGradient id="iAFS1Wx" x1="20.478" x2="19.884" y1="22.98" y2="22.949" gradientUnits="userSpaceOnUse"><stop class="ieaclmdnn"/><stop offset="1" class="p3yd_be1u"/></linearGradient><linearGradient id="iwV61gb" x1="17.279" x2="17.279" y1="16.387" y2="14.86" gradientUnits="userSpaceOnUse"><stop class="tpolxqb5t"/><stop offset="1" class="kuwu5yf2m"/></linearGradient><linearGradient id="iusfD2b" x1="16.011" x2="16.011" y1="8.769" y2="10.98" gradientUnits="userSpaceOnUse"><stop class="eo95k2lyk"/><stop offset="1" class="fijq563tp"/></linearGradient><linearGradient id="ipPN1jb" x1="19.744" x2="19.744" y1="17.012" y2="27.918" gradientUnits="userSpaceOnUse"><stop class="hd06b2knh"/><stop offset="1" class="ggughpb3d"/></linearGradient><linearGradient id="iVy1Gyd" x1="16.306" x2="16.306" y1="18.449" y2="25.012" gradientUnits="userSpaceOnUse"><stop class="y6ovumr8k"/><stop offset="1" class="t-eeezbdl"/></linearGradient><linearGradient id="iRLxQyL" x1="15.173" x2="14.736" y1="6.433" y2="6.64" gradientUnits="userSpaceOnUse"><stop offset=".259" class="nmm8urb4e"/><stop offset="1" class="tpckrzjou"/></linearGradient><linearGradient id="iRGT2ac" x1="15.032" x2="15.049" y1="7.77" y2="7.358" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iflGiMc" x1="15.694" x2="15.61" y1="5.533" y2="5.663" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iH2fNWT" x1="14.022" x2="13.937" y1="6.318" y2="6.447" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-golfing" /></template>
<style>
.a6h6mobhd {
  fill: var(--svg-color--000, #000);
  d: path("M15.27 5.9a.213.213 0 0 1 .103-.285a.213.213 0 0 1 .305.202l-.343.161a.2.2 0 0 1-.065-.078");
}

.aidzwlkvm {
  stop-color: var(--svg-color--846ab1, #846AB1);
}

.ajs9ss72k {
  d: path("M13.643 6.25a.374.374 0 0 0-.126.581l.655-.307a.377.377 0 0 0-.53-.274");
}

.avihppb8x {
  stop-color: var(--svg-color--7a5998, #7A5998);
}

.azn0z--js {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
  stop-opacity: 0;
}

.b_b3xwxoo {
  d: path("m14.456 6.199l.101.741a.226.226 0 0 0 .323.173l.299-.14a.227.227 0 0 0 .073-.359l-.505-.552c-.11-.123-.313-.028-.291.137");
}

.b1q481j-e {
  d: path("M13.927 9.949c.176-1.285.703-1.862 1-2.07c.51-.358 1.664-.946 3.336 0c1.758 1.093 2.404 4.057 2.375 5.375v2.804h-6v-3.242c0-.487-.105-.742-.258-.96c-.144-.259-.52-.981-.453-1.907");
}

.b4pae_ykk {
  stop-color: var(--svg-color--da7926, #DA7926);
}

.ba1yb3bji {
  stop-color: var(--svg-color--a99797, #A99797);
}

.bk0-xsbnt {
  d: path("M11.595 27.902c0-.806.458-1.159.688-1.234l1.367 1.18v1.283a.5.5 0 0 0 .187.39l.203.162c.128.094.297.239.25.414c-.082.172-.25.196-.539.196h-1.506a.65.65 0 0 1-.65-.65z");
}

.bnk9occqx {
  width: 0.692px;
  height: 1.157px;
  x: 21.084px;
  y: 3.892px;
  rx: 0.346px;
}

.bq7w62n5j {
  stop-color: var(--svg-color--482a5b, #482A5B);
}

.cax3-9bdu {
  stop-color: var(--svg-color--cc6d18, #CC6D18);
  stop-opacity: 0;
}

.cgn2r-bvw {
  stop-color: var(--svg-color--68489a, #68489A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqn7i9qhy {
  stop-color: var(--svg-color--f19c30, #F19C30);
}

.d-_ztzc9a {
  d: path("M15.305 5.47a.375.375 0 0 1 .527.275l-.655.307a.376.376 0 0 1 .127-.582");
}

.d2smg-bvf {
  fill: var(--svg-color--ffcb37, #FFCB37);
  fill-rule: evenodd;
  d: path("M17.602 5.524c-.235-.734-.449-.822-.449-.822c-.348-.302-.86-.454-1.125-.85c-.325-.692-.702-1.078-1.395-.753a.23.23 0 0 1-.215-.007a1.39 1.39 0 0 0-2.04.957a.24.24 0 0 1-.132.17l-.032.016c-.67.335-.719.936-.399 1.618c.123.342.128.576.065 1.023c-.065.676-.105.883.313 1.233a.22.22 0 0 1 .082.173A1.35 1.35 0 0 0 14.2 9.524l3.263-1.53a1.35 1.35 0 0 0 .276-2.276a.35.35 0 0 1-.138-.194M12.52 6.716l-.005.002l.877.682c.547 1.044.462-.217 1.478-.694c1.016-.476 2.016.502 1.563-.586l-.139-1.418c-.242-.464-.6-.337-.67-.304l-1.2.649c-.483.226-1.075.13-1.536-.142a.11.11 0 0 0-.166.102l.003.088a.97.97 0 0 1-.248.699l-.015.017c-.068.088-.213.327-.052.691l.059.115z");
}

.d30rw76zq {
  stop-color: var(--svg-color--f5aa27, #F5AA27);
}

.dblh6zb0b {
  stop-color: var(--svg-color--ffd731, #FFD731);
}

.ddjhanboc {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
}

.dhd6km3rx {
  stroke: var(--svg-color--c3b8c3, #C3B8C3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.51 13.027a.53.53 0 0 0 0 .54c.13.237.718 1.277.96 1.714c.05.103.111.355-.039.543");
}

.dhem-xbnm {
  stop-color: var(--svg-color--442563, #442563);
}

.diny9tbav {
  d: path("M16.79 6.019a.676.676 0 1 0-.575-1.224a.676.676 0 0 0 .574 1.224");
}

.ds3hm--8v {
  stop-color: var(--svg-color--533d66, #533D66);
}

.dsumrvbgt {
  stop-color: var(--svg-color--615273, #615273);
  stop-opacity: 0;
}

.dyid5_bjz {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M16.693 5.815a.451.451 0 1 0-.383-.817a.451.451 0 0 0 .383.817");
}

.e05l2cs0p {
  stop-color: var(--svg-color--9175c2, #9175C2);
}

.e4n1ffbms {
  width: 0.692px;
  height: 1.157px;
  x: 22.173px;
  y: 3.392px;
  rx: 0.346px;
}

.e8jaecbhx {
  stop-color: var(--svg-color--7a5eaf, #7A5EAF);
  stop-opacity: 0;
}

.e9z7ehngf {
  d: path("m16.15 23.668l-.375-5.953l1.062.5v5.453z");
}

.ebs2-pbbe {
  stop-color: var(--svg-color--9c8cad, #9C8CAD);
  stop-opacity: 0;
}

.ecxt7ybnv {
  stop-color: var(--svg-color--8469b5, #8469B5);
}

.eo95k2lyk {
  stop-color: var(--svg-color--7c5dab, #7C5DAB);
}

.euzbypbyq {
  stop-color: var(--svg-color--fdc83c, #FDC83C);
}

.fijq563tp {
  stop-color: var(--svg-color--7652b9, #7652B9);
}

.ft5dv1b6b {
  fill: none;
}

.ftqy6sbhb {
  stop-color: var(--svg-color--bd6f1e, #BD6F1E);
}

.g05smc5_v {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m13.057 6.198l-.001.002a.113.113 0 0 1-.187-.126v-.002l.003-.003l.01-.013l.033-.043a1.4 1.4 0 0 1 .127-.135a1.2 1.2 0 0 1 .486-.278a.113.113 0 0 1 .059.217a.95.95 0 0 0-.392.226a1 1 0 0 0-.132.147z");
}

.g1axk00gm {
  fill: var(--svg-color--ffc131, #FFC131);
  d: path("M19.317 6.105a.5.5 0 0 0-.015-.254a5 5 0 0 0-.227-.523c-.02-.089-.025-.29.11-.39a.36.36 0 0 1 .336-.055a.45.45 0 0 1 .207-.286c.134-.072.298-.03.363 0c.018-.066.09-.208.23-.246a.52.52 0 0 1 .356.059c.04-.076.169-.224.36-.215c.238.012.374.262.41.45c.035.187.093.433.152.577c.058.145.117.606-.09 1.2h-.001c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.082a1.1 1.1 0 0 1-.193-2.191c.636-.056 1.522-.244 2.304-.744c.683-.437 1.327-1.135 1.66-2.317");
}

.ggughpb3d {
  stop-color: var(--svg-color--a599b3, #A599B3);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.h3-hcc6xo {
  d: path("M19.317 6.105a.5.5 0 0 0-.015-.254a5 5 0 0 0-.227-.523c-.02-.089-.025-.29.11-.39a.36.36 0 0 1 .336-.055a.45.45 0 0 1 .207-.286c.134-.072.298-.03.363 0c.018-.066.09-.208.23-.246a.52.52 0 0 1 .356.059c.04-.076.169-.224.36-.215c.238.012.374.262.41.45c.035.187.093.433.152.577c.058.145.117.606-.09 1.2h-.001c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.082a1.1 1.1 0 0 1-.193-2.191c.636-.056 1.522-.244 2.304-.744c.683-.437 1.327-1.135 1.66-2.317");
}

.h4h5rsbrw {
  fill: var(--svg-color--faa830, #FAA830);
  d: path("M13.171 7.716a.676.676 0 1 0-.574-1.224a.676.676 0 0 0 .574 1.224");
}

.h8hiq33uv {
  stop-color: var(--svg-color--271938, #271938);
  stop-opacity: 0;
}

.hcmpzwvfn {
  stop-color: var(--svg-color--e0a524, #E0A524);
}

.hd06b2knh {
  stop-color: var(--svg-color--a89eb3, #A89EB3);
}

.hw4b9obcq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.313 5.553c.04.021.007.084-.03.154s-.065.12-.105.1c-.04-.022-.04-.095-.004-.165c.038-.07.1-.11.14-.089");
}

.hznysmbpr {
  d: path("m11.586 5.562l.324.625c1.34-1.957 3.175-2.312 4.25-2.172l-.293-.504c-.027-.07-.152-.286-.433-.59c-.582-.546-1.315-.402-1.61-.261l-1.601.82c-.127.065-.43.307-.637.754c-.269.569-.145 1.082 0 1.328");
}

.i_ikeur-m {
  d: path("m21.765 5.37l-.5-.865l3.122-1.86a.4.4 0 0 1 .548.14l.102.172a.4.4 0 0 1-.139.548z");
}

.i42zc8m6u {
  stop-color: var(--svg-color--615273, #615273);
}

.ie8u9uubp {
  stop-color: var(--svg-color--8a74b9, #8A74B9);
}

.ieaclmdnn {
  stop-color: var(--svg-color--a19ca8, #A19CA8);
}

.ilg8l_bzj {
  stop-color: var(--svg-color--655e6d, #655E6D);
}

.in-vfpgwh {
  stop-color: var(--svg-color--403451, #403451);
  stop-opacity: 0;
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j_l_30buh {
  stop-color: var(--svg-color--5d5467, #5D5467);
}

.j5m1n_04i {
  fill: var(--svg-color--9785a9, #9785A9);
  d: path("M14.522 24.06a1 1 0 0 0 .275-.711l-.167-7.29h6.02l-.312 12.476H18.18l-.259-10.002a.255.255 0 0 0-.509-.005c-.049 1.196-.13 3.455-.13 4.585c0 1.213-.693 2.214-1.04 2.563l-2.472 2.287a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.718-.424c-.252-.225-.439-.553-.547-.795a.36.36 0 0 1 .078-.393z");
}

.jsz_uluep {
  stop-color: var(--svg-color--7765a4, #7765A4);
  stop-opacity: 0;
}

.jwirzncnv {
  stop-color: var(--svg-color--8773ae, #8773AE);
}

.k0h2lnbak {
  cx: 13.61px;
  cy: 6.442px;
  rx: 0.164px;
  ry: 0.083px;
}

.k3wt0u04d {
  fill: var(--svg-color--000, #000);
  d: path("M13.996 6.497a.213.213 0 0 0-.285-.103a.213.213 0 0 0-.04.365l.344-.161a.2.2 0 0 0-.02-.1");
}

.keljo6scd {
  stop-color: var(--svg-color--827a8b, #827A8B);
}

.kgrhzo17p {
  stop-color: var(--svg-color--a99797, #A99797);
  stop-opacity: 0;
}

.kld0av5cc {
  stop-color: var(--svg-color--cc6d18, #CC6D18);
}

.ksevddbvl {
  stop-color: var(--svg-color--fdc631, #FDC631);
}

.kuwu5yf2m {
  stop-color: var(--svg-color--6a4fad, #6A4FAD);
  stop-opacity: 0;
}

.kxzgmzb5t {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lpm73-wsn {
  stop-color: var(--svg-color--765594, #765594);
  stop-opacity: 0;
}

.lr97j31fb {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
}

.lzqv--boa {
  stop-color: var(--svg-color--5b3f80, #5B3F80);
}

.m7l7lfb0p {
  stop-color: var(--svg-color--6a5696, #6A5696);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mhnq3mo3j {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m14.477 6.253l.043.769a.227.227 0 0 0 .323.173l.3-.14a.227.227 0 0 0 .072-.36l-.505-.551c-.11-.123-.255-.055-.233.11");
}

.mtesmbwby {
  stop-color: var(--svg-color--77649c, #77649C);
}

.muua73y8y {
  stop-color: var(--svg-color--f3ae21, #F3AE21);
}

.mw4zxhc4b {
  cx: 13.61px;
  cy: 6.442px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.164px;
  ry: 0.083px;
}

.n8b-cjbii {
  stop-color: var(--svg-color--a5701f, #A5701F);
}

.nakpuljwd {
  d: path("m12.506 6.696l.005-.003l-.052-.099l-.058-.114c-.162-.365-.017-.603.051-.692l.016-.017l.016-.017a.97.97 0 0 0 .232-.682l-.003-.088a.11.11 0 0 1 .166-.102c.46.272 1.065.364 1.548.137l1.188-.644c.069-.032.427-.16.67.304l.503 1.19c.453 1.088-.043 2.194-1.06 2.67c-1.015.477-2.183.152-2.73-.892z");
}

.nddod5b3z {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.185 7.375a1.3 1.3 0 0 1-.602.123c-.066-.003-.095.086-.038.12a.812.812 0 0 0 1.236-.58c.01-.068-.076-.1-.117-.048a1.26 1.26 0 0 1-.479.385");
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nmm8urb4e {
  stop-color: var(--svg-color--ffcc35, #FFCC35);
}

.ob4ztkbap {
  stop-color: var(--svg-color--eaa22a, #EAA22A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojy1jndng {
  stop-color: var(--svg-color--ffd540, #FFD540);
}

.p2hc_mblf {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.335 5.33a.59.59 0 0 1 .704.16a.115.115 0 0 1-.04.178l-.85.398a.097.097 0 0 1-.134-.063a.59.59 0 0 1 .32-.673");
}

.p3yd_be1u {
  stop-color: var(--svg-color--a49faa, #A49FAA);
  stop-opacity: 0;
}

.p4yinsbqr {
  fill-rule: evenodd;
  d: path("M17.602 5.524c-.235-.734-.449-.822-.449-.822c-.348-.302-.86-.454-1.125-.85c-.325-.692-.702-1.078-1.395-.753a.23.23 0 0 1-.215-.007a1.39 1.39 0 0 0-2.04.957a.24.24 0 0 1-.132.17l-.032.016c-.67.335-.719.936-.399 1.618c.123.342.128.576.065 1.023c-.065.676-.105.883.313 1.233a.22.22 0 0 1 .082.173A1.35 1.35 0 0 0 14.2 9.524l3.263-1.53a1.35 1.35 0 0 0 .276-2.276a.35.35 0 0 1-.138-.194M12.52 6.716l-.005.002l.877.682c.547 1.044.462-.217 1.478-.694c1.016-.476 2.016.502 1.563-.586l-.139-1.418c-.242-.464-.6-.337-.67-.304l-1.2.649c-.483.226-1.075.13-1.536-.142a.11.11 0 0 0-.166.102l.003.088a.97.97 0 0 1-.248.699l-.015.017c-.068.088-.213.327-.052.691l.059.115z");
}

.pcvpzjboo {
  stop-color: var(--svg-color--937da8, #937DA8);
}

.pd8kwccwo {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.13 6.255c-.184-.13-.403-.198-.734-.043a.7.7 0 0 0-.342.332c-.063.13 0 .23.098.232l.268.021c.21-.196.48-.336.71-.542");
}

.pdy5l7eay {
  d: path("M15.313 5.553c.04.021.007.084-.03.154s-.065.12-.105.1c-.04-.022-.04-.095-.004-.165c.038-.07.1-.11.14-.089");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ps4m-ab9c {
  stop-color: var(--svg-color--827a8b, #827A8B);
  stop-opacity: 0;
}

.q_w9u85di {
  stop-color: var(--svg-color--f19c30, #F19C30);
  stop-opacity: 0;
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q8jh71bsc {
  d: path("M15.745 5.622a.35.35 0 0 0-.17-.134l-.048.155l.085.065z");
}

.qc-9lgb7u {
  width: 0.692px;
  height: 1.157px;
  x: 21.603px;
  y: 3.646px;
  rx: 0.346px;
}

.qe_2d-buv {
  stop-color: var(--svg-color--937da8, #937DA8);
  stop-opacity: 0;
}

.qgyv_0bxz {
  stop-color: var(--svg-color--5b3f80, #5B3F80);
  stop-opacity: 0;
}

.qkq015b1v {
  d: path("M13.598 4.383a4.15 4.15 0 0 0-1.691 1.804l.378.134a.42.42 0 0 0 .476-.156c.24-.332.669-.841 1.212-1.118c.53-.271 1.194-.362 1.675-.362a.45.45 0 0 0 .448-.349l.064-.332c-.397-.042-1.629-.172-2.562.379");
}

.qqp8wrblx {
  stop-color: var(--svg-color--da7926, #DA7926);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_8igzxod {
  d: path("M14.522 24.06a1 1 0 0 0 .275-.711l-.167-7.29h6.02l-.312 12.476H18.18l-.259-10.002a.255.255 0 0 0-.509-.005c-.049 1.196-.13 3.455-.13 4.585c0 1.213-.693 2.214-1.04 2.563l-2.472 2.287a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.718-.424c-.252-.225-.439-.553-.547-.795a.36.36 0 0 1 .078-.393z");
}

.ro68m4b1o {
  fill: var(--svg-color--4c3765, #4C3765);
  d: path("M18.177 30.293v-1.77h2.16c.164.156.79.551 1.504.781c.494.132.625.489.63.622v.367z");
}

.rr3z7eg2t {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m15.686 4.752l-.011.112za.113.113 0 0 1-.022.224h-.003l-.053-.002a1 1 0 0 0-.154.01a.95.95 0 0 0-.425.156a.113.113 0 1 1-.13-.184c.18-.126.377-.176.526-.196a1.4 1.4 0 0 1 .255-.009h.006z");
}

.s2j02zbkr {
  stop-color: var(--svg-color--655e6d, #655E6D);
  stop-opacity: 0;
}

.sedutetcs {
  stop-color: var(--svg-color--ffb536, #FFB536);
}

.seeiowbir {
  stop-color: var(--svg-color--482c58, #482C58);
}

.sgjix6b2q {
  stop-color: var(--svg-color--7660a4, #7660A4);
}

.sr1ckfb_s {
  d: path("M8.948 13.003a.35.35 0 0 0-.125.474l.88 1.546a1 1 0 0 1-.373 1.363l-.115.066a1 1 0 0 1-1.364-.374L7.123 14.8a1.65 1.65 0 0 1 .617-2.25l.343-.195l16.303-9.71a.4.4 0 0 1 .549.14l.102.172a.4.4 0 0 1-.14.548z");
}

.t_a14bpou {
  stop-color: var(--svg-color--ffd540, #FFD540);
  stop-opacity: 0;
}

.t-eeezbdl {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
  stop-opacity: 0;
}

.t3o1xnbhr {
  stop-color: var(--svg-color--7a5998, #7A5998);
  stop-opacity: 0;
}

.td20orbdz {
  stop-color: var(--svg-color--8773ae, #8773AE);
  stop-opacity: 0;
}

.tpckrzjou {
  stop-color: var(--svg-color--ffb533, #FFB533);
}

.tpolxqb5t {
  stop-color: var(--svg-color--6a4fad, #6A4FAD);
}

.tva982odh {
  stop-color: var(--svg-color--7765a4, #7765A4);
}

.tw6dxpb7y {
  stop-color: var(--svg-color--482c58, #482C58);
  stop-opacity: 0;
}

.tzgzt3b1l {
  stop-color: var(--svg-color--bb7701, #BB7701);
}

.u1g4dxbrg {
  width: 0.737px;
  height: 1.252px;
  x: 21.976px;
  y: 4.423px;
  rx: 0.369px;
}

.u1nv9tz7s {
  d: path("M14.094 6.403c-.052-.11-.175-.14-.21-.151l-.06.157l.133.106z");
}

.usai76iql {
  stop-color: var(--svg-color--fcc540, #FCC540);
}

.uu7_gub8n {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
  stop-opacity: 0;
}

.uw-_4rbwh {
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("m19.822 16.73l-.188 11.188");
}

.uy0edsrfa {
  stop-color: var(--svg-color--e6961b, #E6961B);
  stop-opacity: 0;
}

.v-z7nrvme {
  stop-color: var(--svg-color--7660a4, #7660A4);
  stop-opacity: 0;
}

.v3r5uzuwd {
  stop-color: var(--svg-color--7a5cb5, #7A5CB5);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vkrof_bbk {
  stop-color: var(--svg-color--271938, #271938);
}

.vokmvabvz {
  stop-color: var(--svg-color--755ab4, #755AB4);
}

.w5oxhdc5r {
  stop-color: var(--svg-color--7f5d9d, #7F5D9D);
}

.w6_gecbjt {
  fill: var(--svg-color--47385d, #47385D);
  d: path("M11.595 27.902c0-.806.458-1.159.688-1.234l1.367 1.18v1.283a.5.5 0 0 0 .187.39l.203.162c.128.094.297.239.25.414c-.082.172-.25.196-.539.196h-1.506a.65.65 0 0 1-.65-.65z");
}

.wg59hevzp {
  stop-color: var(--svg-color--7a5eae, #7A5EAE);
}

.x16wh0r6i {
  stop-color: var(--svg-color--f3a335, #F3A335);
  stop-opacity: 0;
}

.xdvfs5b6o {
  stop-color: var(--svg-color--765594, #765594);
}

.xhu8yhbcw {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
  stop-opacity: 0;
}

.xi8fv135v {
  stop-color: var(--svg-color--8c7e97, #8C7E97);
  stop-opacity: 0;
}

.xjxnzbcno {
  fill-rule: evenodd;
  d: path("M20.961 7.893c.852-1.082.481-2.213.22-2.677l1.915-1.081c.467.827 1.242 3.027-.406 5.12c-.89 1.13-2.33 1.566-3.484 1.752c-1.198.193-2.37.159-2.985.135l.084-2.198c.599.023 1.583.047 2.55-.109c1.012-.163 1.746-.484 2.106-.942");
}

.xtgg-5mjh {
  stop-color: var(--svg-color--68489a, #68489A);
}

.y6ovumr8k {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
}

.ybyttdvmz {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.517 6.183a.59.59 0 0 0-.327.644a.115.115 0 0 0 .163.082l.848-.398a.097.097 0 0 0 .038-.144a.59.59 0 0 0-.723-.184");
}

.yffvx8b_t {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.999 5.848c.018-.225.105-.437.435-.592a.7.7 0 0 1 .474-.052c.141.035.177.147.117.224l-.155.22c-.286.036-.565.154-.871.2");
}

.ynlfw99ba {
  stop-color: var(--svg-color--403451, #403451);
}

.ynn_1cvkj {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.185 7.375a1.3 1.3 0 0 1-.602.123c-.066-.003-.095.086-.038.12a.812.812 0 0 0 1.236-.58c.01-.068-.076-.1-.117-.048a1.26 1.26 0 0 1-.479.385Z");
}

.yocnddcqz {
  fill: var(--svg-color--afa2b8, #AFA2B8);
  d: path("M8.948 13.003a.35.35 0 0 0-.125.474l.88 1.546a1 1 0 0 1-.373 1.363l-.115.066a1 1 0 0 1-1.364-.374L7.123 14.8a1.65 1.65 0 0 1 .617-2.25l.343-.195l16.303-9.71a.4.4 0 0 1 .549.14l.102.172a.4.4 0 0 1-.14.548z");
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yuypg-bpl {
  width: 0.692px;
  height: 1.157px;
  x: 20.651px;
  y: 4.151px;
  rx: 0.346px;
}

.z-tc3nh5j {
  fill: var(--svg-color--f69e19, #F69E19);
  d: path("M13.083 7.51a.451.451 0 1 0-.383-.818a.451.451 0 0 0 .383.817");
}

.z1jkahbiz {
  d: path("M16.693 5.815a.451.451 0 1 0-.383-.817a.451.451 0 0 0 .383.817");
}

.zn47ozbfv {
  stop-color: var(--svg-color--442563, #442563);
  stop-opacity: 0;
}

.zom_kry4o {
  d: path("M16.001 8.984c.328-.031.652-.125.848-.215l.86 2.196c-.235.12-1.716.593-2.54.43c-.824-.165-1.02-1.196-.73-1.739c.273-.61 1.118-.63 1.562-.672");
}

</style>
