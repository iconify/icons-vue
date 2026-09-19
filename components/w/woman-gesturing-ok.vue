<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSiHLKb)"><path fill="url(#iR2ZVsd)" clip-rule="evenodd" class="t5xwmodqh"/><path fill="url(#iiiUvfc)" clip-rule="evenodd" class="t5xwmodqh"/><path fill="url(#iY20kkc)" clip-rule="evenodd" class="t5xwmodqh"/><path fill="url(#iKq3CWd)" clip-rule="evenodd" class="t5xwmodqh"/><path fill="url(#ihdZKsn)" clip-rule="evenodd" class="t5xwmodqh"/></g><g filter="url(#iN0CAsb)"><path fill="url(#i2NjRZd)" class="iqnh8pble"/><path fill="url(#ibAbYVc)" class="iqnh8pble"/></g><g filter="url(#irEvtcd)"><path fill="url(#iH2e8zc)" class="cob142b7a"/><path fill="url(#iHpwWFd)" class="cob142b7a"/></g><rect fill="url(#iR54Amd)" class="iuxb-78iw"/><g filter="url(#ih7i0db)"><path fill="url(#igYWDcc)" class="y0zwm33ay"/><path fill="url(#ic3gTqE)" class="y0zwm33ay"/><path fill="url(#ilxYs3d)" class="y0zwm33ay"/><path fill="url(#iGimrKd)" class="y0zwm33ay"/><path fill="url(#ipwdzae)" class="y0zwm33ay"/><path fill="url(#i4G4Ddb)" class="y0zwm33ay"/><path fill="url(#i0sIUkc)" class="y0zwm33ay"/><path fill="url(#irFmGve)" class="y0zwm33ay"/><path fill="url(#ihBSSbc)" class="y0zwm33ay"/><path fill="url(#iUBfMkc)" class="y0zwm33ay"/></g><path fill="url(#iITrjcb)" class="ggskh2bzm"/><path fill="url(#il2uPAe)" class="ggskh2bzm"/><path fill="url(#ifIvNoe)" class="dw85flb0t"/><path fill="url(#i55fYYb)" class="dw85flb0t"/><path fill="url(#i4Wqgqq)" class="r_9_ioa3h"/><path fill="url(#iRneNPQ)" class="r_9_ioa3h"/><path fill="url(#id2DEKf)" class="eim_mrbrv"/><path fill="url(#i1XP0UM)" class="eim_mrbrv"/><g filter="url(#iO1k7oj)"><path fill="url(#ikIICoM)" class="x_mri4gas"/></g><g filter="url(#iz9Tuqc)"><path stroke="url(#iHzhcLb)" class="id0lipbed"/></g><path class="ku49b-vhj"/><path stroke="url(#i51hlve)" class="djebsbcjo"/><path stroke="url(#i1aFbGc)" class="djebsbcjo"/><path stroke="url(#itsaBkb)" class="djebsbcjo"/><path stroke="url(#iHLLHMc)" class="w930jqbym"/><path stroke="url(#iWSDh8d)" class="w930jqbym"/><path stroke="url(#ihu6wOc)" class="w930jqbym"/><path class="qvv7abcya"/><path stroke="url(#iffKTvb)" class="odw-ccxrl"/><path stroke="url(#i40gqKc)" class="odw-ccxrl"/><path stroke="url(#iTHEkfI)" class="odw-ccxrl"/><path stroke="url(#is3o6Ae)" class="lc0lwfbjp"/><path stroke="url(#iNJWaIe)" class="lc0lwfbjp"/><path stroke="url(#iiCywtb)" class="lc0lwfbjp"/><path stroke="url(#iVpEied)" class="zw6cmm23y"/><path class="u8isk7i_t"/><path stroke="url(#iWADMid)" class="zw6cmm23y"/><path stroke="url(#iR1m3gl)" class="zw6cmm23y"/><path stroke="url(#iHxEwAc)" class="zw6cmm23y"/><path stroke="url(#i9rKsIc)" class="abd3-ibar"/><path stroke="url(#ivYPo2q)" class="abd3-ibar"/><path stroke="url(#izkjZie)" class="abd3-ibar"/><path class="ccza6hbch"/><path stroke="url(#ilqQnze)" class="hockzyb4d"/><path stroke="url(#iWDKx4M)" class="hockzyb4d"/><path stroke="url(#iDxJFhb)" class="lgc2wbcpd"/><path stroke="url(#i73gwKd)" class="lgc2wbcpd"/><path stroke="url(#iLwuUHe)" class="lgc2wbcpd"/><path fill="url(#ip6NOWc)" class="eim_mrbrv"/><path fill="url(#idIjZGc)" class="r_9_ioa3h"/><g filter="url(#iN4diEe)"><path fill="url(#ikqYl0d)" class="t_1lg5u6m"/></g><g filter="url(#iHoSQIF)"><path fill="url(#iFsMtEd)" class="mxc3f8vrk"/></g><g filter="url(#ilKXM0d)"><path class="cjapmtbje"/><path fill="url(#ipTATtb)" class="e7l0rab5q"/></g><g filter="url(#ixKUx1d)"><path class="ys44xtaqp"/><path fill="url(#iIloohc)" class="vm5gdfbfi"/></g><g filter="url(#iBXr5Fy)"><path fill="url(#i7eHKJd)" class="i7a7wgkwg"/><path fill="url(#iOGT5xe)" class="i7a7wgkwg"/><path fill="url(#i6Vx7ee)" class="i7a7wgkwg"/><path fill="url(#i2mlrtb)" class="i7a7wgkwg"/><path fill="url(#i40BLib)" class="i7a7wgkwg"/><path fill="url(#iePq76p)" class="i7a7wgkwg"/><path fill="url(#i7UloKd)" class="i7a7wgkwg"/></g><g filter="url(#iTUulGp)"><path class="tdk312-2s"/></g><g filter="url(#i0fTEnd)"><path fill="url(#i7W5mIo)" class="kaliyjbtv"/><path fill="url(#iYBOcHE)" class="kaliyjbtv"/><path fill="url(#ieHL0KO)" class="kaliyjbtv"/><path fill="url(#i3C6Bxe)" class="kaliyjbtv"/></g><path fill="url(#iw3Adxc)" class="kaliyjbtv"/><path fill="url(#ioNF0yd)" class="kaliyjbtv"/><path stroke="url(#iSdux7d)" class="qa4nau83s"/><g filter="url(#i6ZCK3c)"><path class="tdawh5bbz"/></g><g filter="url(#iCMcric)"><path class="z2-1r6b6n"/></g><g filter="url(#inQSoyd)"><path class="kl4b00bzq"/></g><g filter="url(#iGkN73c)"><path clip-rule="evenodd" class="q9fwao-8y"/></g><path class="ionb7nb5v"/><path fill="url(#iCLRTAb)" class="zus0jubvv"/><path class="o0h7dsxoh"/><g filter="url(#i3MfWNE)"><path class="pa_90u-ol"/><path fill="url(#i4tPGTd)" class="u6j6y_csu"/></g><g filter="url(#iAyGiTd)"><path fill="url(#inBxTIb)" class="n5jqcj8fb"/></g><path class="weeqywbny"/><path fill="url(#iODx89y)" class="crdr8dbkn"/><path class="cnlgdqbpj"/><g filter="url(#ic2lQ1c)"><path fill="url(#inQB9vF)" class="czt19889x"/></g><g filter="url(#imLxIXb)"><ellipse transform="rotate(-27.914 13.216 14.821)" class="tb96lttad"/><ellipse fill="url(#itmKfAc)" transform="rotate(-27.914 13.216 14.821)" class="lhvqrgi8y"/></g><g filter="url(#i69I8wR)"><path class="dar6cqm6l"/></g><g filter="url(#iTNQumd)"><path class="p0iwm80fj"/></g><g filter="url(#i5FzLed)"><path stroke="url(#iyu48be)" class="r0__pectf"/></g><defs><radialGradient id="iiiUvfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.78731 -2.53789 0 10.428 16.079)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="sdv7knngl"/><stop offset="1" class="kmgtg_bga"/></radialGradient><radialGradient id="iY20kkc" cx="0" cy="0" r="1" gradientTransform="rotate(59.036 .475 22.544)scale(5.10208 3.85336)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="c8v2xtbbr"/><stop offset="1" class="afp639b_r"/></radialGradient><radialGradient id="iKq3CWd" cx="0" cy="0" r="1" gradientTransform="rotate(104.928 .17 8.995)scale(5.35252 1.69274)" gradientUnits="userSpaceOnUse"><stop class="ge57ngb2v"/><stop offset="1" class="w5-280bhr"/></radialGradient><radialGradient id="ihdZKsn" cx="0" cy="0" r="1" gradientTransform="matrix(-1.42468 0 0 -4.59375 24.424 14.6)" gradientUnits="userSpaceOnUse"><stop class="c_b99kb7k"/><stop offset="1" class="t2fmbzkts"/></radialGradient><radialGradient id="i2NjRZd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0695 2.21877 -1.34677 -1.86315 13.194 8.975)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="x4orl4h6r"/><stop offset="1" class="ly_mbkbuj"/></radialGradient><radialGradient id="ibAbYVc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48437 -1.0625 2.52858 -3.53253 11.53 10.647)" gradientUnits="userSpaceOnUse"><stop offset=".555" class="kfbh47bmm"/><stop offset="1" class="ly5gi8b0b"/></radialGradient><radialGradient id="iH2e8zc" cx="0" cy="0" r="1" gradientTransform="rotate(104.389 5.48 11.616)scale(3.38751 7.06854)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="a1fue4bns"/><stop offset=".796" class="kmslkpbub"/></radialGradient><radialGradient id="iHpwWFd" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -3.41726 4.95339 7.5647 16.125 13.475)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="q4v2oebqx"/><stop offset="1" class="ekpvbsb2t"/></radialGradient><radialGradient id="iR54Amd" cx="0" cy="0" r="1" gradientTransform="rotate(-129.643 14.383 8.104)scale(3.73397 4.5453)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="zkbq2obgs"/><stop offset="1" class="b621vv9ir"/></radialGradient><radialGradient id="ic3gTqE" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71875 -6.83472 0 16 20.756)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="iqhsl1vtz"/><stop offset="1" class="s79xz57ql"/></radialGradient><radialGradient id="ilxYs3d" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.96 8.252)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="c74g9abcg"/><stop offset=".435" class="k33dgh0kx"/></radialGradient><radialGradient id="iGimrKd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.985 14.584)" gradientUnits="userSpaceOnUse"><stop class="kx11me5wz"/><stop offset=".821" class="u1uhvyb0r"/></radialGradient><radialGradient id="ipwdzae" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.173 6.772)" gradientUnits="userSpaceOnUse"><stop class="tcy06xu3j"/><stop offset="1" class="i5zcfd46e"/></radialGradient><radialGradient id="i4G4Ddb" cx="0" cy="0" r="1" gradientTransform="rotate(120.342 2.473 5.772)scale(1.39468 3.26296)" gradientUnits="userSpaceOnUse"><stop class="dpibx-bnx"/><stop offset="1" class="fo8k0-jon"/></radialGradient><radialGradient id="i0sIUkc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88922 1.01511 -2.42427 -4.51178 10.375 18.694)" gradientUnits="userSpaceOnUse"><stop class="lztr6obaf"/><stop offset=".96" class="s0l7a1b5w"/></radialGradient><radialGradient id="irFmGve" cx="0" cy="0" r="1" gradientTransform="rotate(59.077 7.488 25.014)scale(7.31511 1.73016)" gradientUnits="userSpaceOnUse"><stop class="k01my8btw"/><stop offset="1" class="wdetgvldd"/></radialGradient><radialGradient id="ihBSSbc" cx="0" cy="0" r="1" gradientTransform="matrix(.74761 1.13554 -2.7229 1.7927 23.548 6.147)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="lsedqp5nk"/><stop offset="1" class="r_43arenc"/></radialGradient><radialGradient id="iUBfMkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5 -3.84375 0 16.218 21.506)" gradientUnits="userSpaceOnUse"><stop offset=".4" class="hs_dagbsb"/><stop offset="1" class="v4_ps9b4y"/></radialGradient><radialGradient id="iITrjcb" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.835 5.694)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="n4mpkaclr"/><stop offset="1" class="l5smh3bbg"/></radialGradient><radialGradient id="il2uPAe" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.99 5.89)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="cohmtaboh"/><stop offset="1" class="q-4xcsbkb"/></radialGradient><radialGradient id="ifIvNoe" cx="0" cy="0" r="1" gradientTransform="rotate(145.763 11.276 6.464)scale(2.64024 1.85707)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="b1eu2ydha"/><stop offset="1" class="ltc91lylz"/></radialGradient><radialGradient id="i55fYYb" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.402 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="kie_yibqm"/><stop offset="1" class="v0q5d6bwm"/></radialGradient><radialGradient id="i4Wqgqq" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="fhunrr5ci"/><stop offset="1" class="as1blab4r"/></radialGradient><radialGradient id="iRneNPQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.25052 1.35191 -6.0911 5.63427 8.078 2.829)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="kwxb4ppbb"/><stop offset="1" class="hj20s6zvr"/></radialGradient><radialGradient id="id2DEKf" cx="0" cy="0" r="1" gradientTransform="matrix(-2.568 1.57046 -2.49003 -4.07165 24.46 4.389)" gradientUnits="userSpaceOnUse"><stop class="x278nyb7a"/><stop offset=".469" class="bakx-_beg"/></radialGradient><radialGradient id="i1XP0UM" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="nc8kb9b6x"/><stop offset="1" class="xn68z7b1j"/></radialGradient><radialGradient id="ikIICoM" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.18 16.593)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop class="x733f4b8w"/><stop offset="1" class="doo06bbod"/></radialGradient><radialGradient id="i51hlve" cx="0" cy="0" r="1" gradientTransform="rotate(-107.313 7.85 -2.96)scale(1.33912 9.90691)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="itsaBkb" cx="0" cy="0" r="1" gradientTransform="rotate(45.373 5.591 13.928)scale(4.51976 4.41679)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="hsn8dgk7l"/><stop offset=".956" class="bcebw6bhr"/></radialGradient><radialGradient id="ihu6wOc" cx="0" cy="0" r="1" gradientTransform="rotate(96.905 7.712 9.344)scale(.37774 1.72952)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="iffKTvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.20247 -1.22554 7.88755 -1.30309 14.119 4.127)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iTHEkfI" cx="0" cy="0" r="1" gradientTransform="matrix(2.1943 3.64127 -3.57342 2.15341 13.307 1.077)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="hsn8dgk7l"/><stop offset=".956" class="bcebw6bhr"/></radialGradient><radialGradient id="iiCywtb" cx="0" cy="0" r="1" gradientTransform="rotate(90.318 6.676 10.203)scale(.52757 2.91495)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="iVpEied" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 -.90625 8.05091 -1.87395 13.97 4.444)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iWADMid" cx="0" cy="0" r="1" gradientTransform="matrix(-.04687 -.85937 7.6275 -.41603 14.001 4.552)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iHxEwAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.89062 2.59375 -2.74078 1.9978 13.251 2.584)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="hsn8dgk7l"/><stop offset=".956" class="bcebw6bhr"/></radialGradient><radialGradient id="izkjZie" cx="0" cy="0" r="1" gradientTransform="matrix(.03906 .35156 -1.87014 .2078 17.485 4.686)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="ilqQnze" cx="0" cy="0" r="1" gradientTransform="matrix(-.16967 -1.41407 6.69427 -.80322 13.556 6.114)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iLwuUHe" cx="0" cy="0" r="1" gradientTransform="matrix(.03693 .64802 -1.4536 .08285 17.954 6.087)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="ip6NOWc" cx="0" cy="0" r="1" gradientTransform="rotate(104.241 9.588 9.809)scale(4.3577 15.5483)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="bfp_ecc-c"/><stop offset=".936" class="d9wzjmbdf"/></radialGradient><radialGradient id="idIjZGc" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="a7d-k3bmr"/><stop offset="1" class="q3wz7tzyo"/></radialGradient><radialGradient id="iFsMtEd" cx="0" cy="0" r="1" gradientTransform="matrix(2.8005 -1.27296 1.55422 3.41927 20.52 16.095)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="ipTATtb" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 54.895 -51.123)scale(1.46782)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iIloohc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20851 0 0 -1.15601 10.726 15.6)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="i7eHKJd" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.95 9.604)scale(8.05786 10.7853)" gradientUnits="userSpaceOnUse"><stop class="ge894s-3b"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iOGT5xe" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 7.099 10.138)scale(2.68532 2.2783)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="i6Vx7ee" cx="0" cy="0" r="1" gradientTransform="matrix(.94165 -4.55128 5.77473 1.19477 13.523 22.627)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="i2mlrtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.96875 -8.01142 0 15.976 14.725)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="fiwg5tbyl"/><stop offset="1" class="ccl9mdbip"/></radialGradient><radialGradient id="i40BLib" cx="0" cy="0" r="1" gradientTransform="matrix(-6.10105 1.68716 -2.90477 -10.50416 16.682 16.86)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iePq76p" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29476 1.58902 0 18.565 14.525)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="i7UloKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53017 1.75368 0 13.818 14.623)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iYBOcHE" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 14.853 2.144)scale(2.86579 1.63985)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="ioNF0yd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44189 1.02993 -1.37952 -1.9313 16.3 16.614)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iCLRTAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91283 -1.45196 0 18.43 14.929)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i4tPGTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26094 -.33625 .46294 -.35925 18.174 15.023)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iODx89y" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91284 -1.45197 0 13.52 14.929)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="itmKfAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0087 -.55588 .66819 -.01046 13.198 15.175)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iR2ZVsd" x1="21.256" x2="13.629" y1="7.778" y2="22.404" gradientUnits="userSpaceOnUse"><stop class="tahhdxy3z"/><stop offset="1" class="vrw28oiox"/></linearGradient><linearGradient id="igYWDcc" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="p3amiobln"/><stop offset="1" class="bqg_h123s"/></linearGradient><linearGradient id="iHzhcLb" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="pzhuj_59e"/><stop offset="1" class="y4yk8v7tr"/></linearGradient><linearGradient id="i1aFbGc" x1="10.522" x2="12.654" y1="3.629" y2="2.265" gradientUnits="userSpaceOnUse"><stop offset=".249" class="la4rvxbid"/><stop offset="1" class="j0gi-81kw"/></linearGradient><linearGradient id="iHLLHMc" x1="18.298" x2="21.642" y1="2.397" y2="3.186" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="iWSDh8d" x1="17.251" x2="18.704" y1="2.444" y2="2.588" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="i40gqKc" x1="12.267" x2="14.049" y1="3.897" y2="3.055" gradientUnits="userSpaceOnUse"><stop offset=".224" class="xw2qhwj5i"/><stop offset="1" class="qg4fklbdo"/></linearGradient><linearGradient id="is3o6Ae" x1="17.183" x2="20.001" y1="3.104" y2="3.444" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="iNJWaIe" x1="16.173" x2="17.798" y1="3.49" y2="3.297" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="iR1m3gl" x1="12.228" x2="13.705" y1="4.523" y2="3.638" gradientUnits="userSpaceOnUse"><stop offset=".249" class="qc6cxsufz"/><stop offset="1" class="qg4fklbdo"/></linearGradient><linearGradient id="i9rKsIc" x1="17.421" x2="19.358" y1="4.093" y2="4.487" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="ivYPo2q" x1="16.298" x2="17.789" y1="4.834" y2="3.798" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="iWDKx4M" x1="11.892" x2="13.626" y1="5.787" y2="5.254" gradientUnits="userSpaceOnUse"><stop offset=".249" class="la4rvxbid"/><stop offset="1" class="j0gi-81kw"/></linearGradient><linearGradient id="iDxJFhb" x1="17.894" x2="19.781" y1="4.994" y2="5.191" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="i73gwKd" x1="16.831" x2="18.687" y1="6.36" y2="5.699" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="ikqYl0d" x1="8.893" x2="12.223" y1="15.699" y2="15.699" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i7W5mIo" x1="15.976" x2="15.976" y1="17.894" y2="14.876" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ieHL0KO" x1="14.798" x2="15.76" y1="17.036" y2="17.154" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="i3C6Bxe" x1="15.976" x2="15.976" y1="17.997" y2="17.311" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iw3Adxc" x1="16.064" x2="16.064" y1="17.968" y2="17.811" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iSdux7d" x1="15.155" x2="15.665" y1="19.659" y2="18.678" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="inBxTIb" x1="19.306" x2="18.953" y1="14.989" y2="15.207" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inQB9vF" x1="14.357" x2="14.005" y1="14.989" y2="15.207" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyu48be" x1="12.723" x2="13.336" y1="8.627" y2="10.06" gradientUnits="userSpaceOnUse"><stop class="tgfwo6lwf"/><stop offset="1" class="x-1h17b9i"/></linearGradient><filter id="iSiHLKb" width="17.147" height="17.647" x="7.527" y="5.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.454902 0 0 0 0 0.0431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3714"/></filter><filter id="iN0CAsb" width="4.522" height="4.778" x="8.973" y="7.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".15"/></filter><filter id="irEvtcd" width="10.254" height="7.322" x="12.125" y="6.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".2"/></filter><filter id="ih7i0db" width="28.403" height="24.735" x="2.048" y="5.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.278431 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3714"/></filter><filter id="iO1k7oj" width="16.188" height="8.656" x="9.107" y="21.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".5"/></filter><filter id="iz9Tuqc" width="4.094" height="4.656" x="7.923" y="22.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".25"/></filter><filter id="iN4diEe" width="3.771" height="3.871" x="8.893" y="13.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.627451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3714"/></filter><filter id="iHoSQIF" width="3.621" height="3.871" x="19.597" y="13.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3714"/></filter><filter id="ilKXM0d" width="3.417" height="3.417" x="19.698" y="13.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".25"/></filter><filter id="ixKUx1d" width="2.917" height="2.917" x="9.267" y="14.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".125"/></filter><filter id="iBXr5Fy" width="11.466" height="12.638" x="10.243" y="10.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3714"/></filter><filter id="iTUulGp" width="3.112" height="4.017" x="14.237" y="14.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".25"/></filter><filter id="i0fTEnd" width="2.612" height="3.517" x="14.67" y="14.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".125"/></filter><filter id="i6ZCK3c" width="3.352" height="1.446" x="17.061" y="14.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3714"/></filter><filter id="iCMcric" width="3.352" height="1.446" x="11.539" y="14.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3714"/></filter><filter id="inQSoyd" width="2.735" height="1.202" x="11.691" y="12.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.266667 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3714"/></filter><filter id="iGkN73c" width="2.735" height="1.203" x="17.786" y="12.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.266667 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3714"/></filter><filter id="i3MfWNE" width=".86" height=".758" x="17.617" y="14.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".05"/></filter><filter id="iAyGiTd" width=".953" height=".978" x="18.575" y="14.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".1"/></filter><filter id="ic2lQ1c" width="1.06" height="1.12" x="13.576" y="14.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".1"/></filter><filter id="imLxIXb" width="1.002" height=".768" x="12.714" y="14.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".05"/></filter><filter id="i69I8wR" width="2.469" height="1.025" x="17.858" y="12.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".1"/></filter><filter id="iTNQumd" width="2.469" height="1.025" x="11.724" y="12.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".1"/></filter><filter id="i5FzLed" width="1.213" height="2.524" x="12.423" y="7.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3714" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-ok" /></template>
<style>
.a1fue4bns {
  stop-color: var(--svg-color--ffd627, #FFD627);
}

.a7d-k3bmr {
  stop-color: var(--svg-color--f59522, #F59522);
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.afp639b_r {
  stop-color: var(--svg-color--704c2d, #704C2D);
  stop-opacity: 0;
}

.as1blab4r {
  stop-color: var(--svg-color--f4bc2d, #F4BC2D);
}

.b1eu2ydha {
  stop-color: var(--svg-color--8a78bb, #8A78BB);
}

.b621vv9ir {
  stop-color: var(--svg-color--bd6e02, #BD6E02);
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.bakx-_beg {
  stop-color: var(--svg-color--ffc53a, #FFC53A);
}

.bcebw6bhr {
  stop-color: var(--svg-color--eca107, #ECA107);
}

.bf57i6byh {
  stop-color: var(--svg-color--ffd843, #FFD843);
  stop-opacity: 0;
}

.bfp_ecc-c {
  stop-color: var(--svg-color--eb8b05, #EB8B05);
  stop-opacity: 0;
}

.bqg_h123s {
  stop-color: var(--svg-color--7a56bd, #7A56BD);
}

.c_b99kb7k {
  stop-color: var(--svg-color--e4ad37, #E4AD37);
}

.c5ffxnbso {
  stop-color: var(--svg-color--ffdd45, #FFDD45);
}

.c74g9abcg {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
}

.c8v2xtbbr {
  stop-color: var(--svg-color--704c2d, #704C2D);
}

.ccl9mdbip {
  stop-color: var(--svg-color--cf7a16, #CF7A16);
}

.ccza6hbch {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.cjapmtbje {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M21.407 16.809a1.209 1.209 0 1 0 0-2.417a1.209 1.209 0 0 0 0 2.417");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnlgdqbpj {
  fill: var(--svg-color--000, #000);
  d: path("M14.094 15.396a.573.573 0 0 0-.576-.575a.573.573 0 0 0-.51.84h1.017a.6.6 0 0 0 .069-.265");
}

.cob142b7a {
  d: path("M15.297 6.835c-1.274-.281-2.64 1.075-2.772 1.546c1.735 4.074 4.392 3.36 7.522 3.36c2.028 0 1.93 1.078 1.906 1.578c.39-5.328-3.752-5.843-6.656-6.484");
}

.cohmtaboh {
  stop-color: var(--svg-color--8f78bb, #8F78BB);
}

.crdr8dbkn {
  d: path("M13.518 14.392a1.004 1.004 0 0 0-.967 1.269h1.94a1 1 0 0 0 .036-.265a1.01 1.01 0 0 0-1.009-1.004");
}

.czt19889x {
  d: path("M14.436 15.278c0-.324-.264-.54-.335-.606l-.325.314l.2.406z");
}

.d9wzjmbdf {
  stop-color: var(--svg-color--eb8b05, #EB8B05);
}

.dar6cqm6l {
  stroke: var(--svg-color--bc614b, #BC614B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.158 12.931c.363-.088 1.265-.044 1.868.387");
}

.djebsbcjo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.doo06bbod {
  stop-color: var(--svg-color--9179cd, #9179CD);
  stop-opacity: 0;
}

.dpibx-bnx {
  stop-color: var(--svg-color--a07bd3, #A07BD3);
}

.dw85flb0t {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.156-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.e7l0rab5q {
  d: path("M21.407 16.809a1.209 1.209 0 1 0 0-2.417a1.209 1.209 0 0 0 0 2.417");
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.ekpvbsb2t {
  stop-color: var(--svg-color--7d5429, #7D5429);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.fhunrr5ci {
  stop-color: var(--svg-color--ffd234, #FFD234);
}

.fiwg5tbyl {
  stop-color: var(--svg-color--f19a3a, #F19A3A);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fo8k0-jon {
  stop-color: var(--svg-color--a07bd3, #A07BD3);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ge57ngb2v {
  stop-color: var(--svg-color--ae8b45, #AE8B45);
}

.ge894s-3b {
  stop-color: var(--svg-color--ffda08, #FFDA08);
}

.ggskh2bzm {
  d: path("M7.397 4.635L6.97 5.3a.24.24 0 0 0 .01.278c.9 1.156 2.374 1.801 3.283 2.087a.244.244 0 0 0 .281-.107c.15-.248.354-.585.409-.69c.069-.131-.029-.232-.086-.265L7.85 4.775l.125-.273c-.35-.106-.53.044-.578.133");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.hd06z0qdg {
  stop-color: var(--svg-color--d5a136, #D5A136);
  stop-opacity: 0;
}

.hj20s6zvr {
  stop-color: var(--svg-color--d1a345, #D1A345);
  stop-opacity: 0;
}

.hockzyb4d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.hs_dagbsb {
  stop-color: var(--svg-color--3f203a, #3F203A);
}

.hsn8dgk7l {
  stop-color: var(--svg-color--eca107, #ECA107);
  stop-opacity: 0;
}

.i5zcfd46e {
  stop-color: var(--svg-color--8e5dc8, #8E5DC8);
  stop-opacity: 0;
}

.i7a7wgkwg {
  d: path("M10.252 14.18h.014l-.012-.299l-.011-.344c.023-1.068.646-1.48.911-1.619l.058-.023l.058-.023a2.6 2.6 0 0 0 1.338-1.389l.092-.218a.297.297 0 0 1 .52-.057a4.35 4.35 0 0 0 3.588 1.883h3.623c.202 0 1.217.098 1.278 1.499l-.134 3.457c-.139 3.153-2.6 5.27-5.607 5.27c-3.005 0-5.468-2.117-5.606-5.27z");
}

.id0lipbed {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.673 26.678c.48-.448 1.669-1.706 2.594-3.156");
}

.ionb7nb5v {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.666 14.086c.735 0 1.355.507 1.524 1.191c.05.197-.1.384-.3.384h-2.511a.26.26 0 0 1-.256-.306a1.57 1.57 0 0 1 1.543-1.269");
}

.iqhsl1vtz {
  stop-color: var(--svg-color--5c3669, #5C3669);
}

.iqnh8pble {
  d: path("M10.47 8.834c.698-.622 1.706-.629 2.272-.528l.452 1.452c-.289-.044-.547.057-.764.264c-.512 1.418-2.275 2.2-3.092 2.414c-.17-1.678-.076-2.527 1.131-3.602");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.itvn9lbuv {
  stop-color: var(--svg-color--ffc53a, #FFC53A);
  stop-opacity: 0;
}

.iuxb-78iw {
  width: 4.615px;
  height: 6.587px;
  x: 13.668px;
  y: 17.985px;
  rx: 2.307px;
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j0gi-81kw {
  stop-color: var(--svg-color--fbc831, #FBC831);
  stop-opacity: 0;
}

.jh81_obba {
  stop-color: var(--svg-color--d29e3b, #D29E3B);
  stop-opacity: 0;
}

.k01my8btw {
  stop-color: var(--svg-color--a27cda, #A27CDA);
}

.k33dgh0kx {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
  stop-opacity: 0;
}

.kaliyjbtv {
  d: path("m15.546 15.194l-.598 1.913a.607.607 0 0 0 .585.787h.885c.415 0 .708-.4.586-.787l-.598-1.913c-.128-.424-.726-.424-.86 0");
}

.kfbh47bmm {
  stop-color: var(--svg-color--b86c1b, #B86C1B);
  stop-opacity: 0;
}

.kie_yibqm {
  stop-color: var(--svg-color--7860a4, #7860A4);
}

.kl4b00bzq {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.153 13.6l-.005.003a.302.302 0 0 1-.31-.518h.002l.003-.003l.01-.006l.037-.02q.047-.026.13-.066c.111-.053.27-.12.462-.182c.382-.122.917-.225 1.495-.123a.302.302 0 0 1-.105.594c-.45-.079-.88 0-1.207.104a3 3 0 0 0-.512.217");
}

.kmgtg_bga {
  stop-color: var(--svg-color--8a4810, #8A4810);
  stop-opacity: 0;
}

.kmslkpbub {
  stop-color: var(--svg-color--f8a319, #F8A319);
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.ku49b-vhj {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.kwxb4ppbb {
  stop-color: var(--svg-color--d1a345, #D1A345);
}

.kx11me5wz {
  stop-color: var(--svg-color--7a53a4, #7A53A4);
}

.l5smh3bbg {
  stop-color: var(--svg-color--654d88, #654D88);
}

.la4rvxbid {
  stop-color: var(--svg-color--fbc831, #FBC831);
}

.lc0lwfbjp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.608c-.43-.11-2.375-.477-3.255-.266");
}

.lgc2wbcpd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.857 5.381c-.273-.102-1.101-.305-2.171-.242");
}

.lhvqrgi8y {
  cx: 13.216px;
  cy: 14.821px;
  rx: 0.438px;
  ry: 0.222px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lsedqp5nk {
  stop-color: var(--svg-color--7653b2, #7653B2);
}

.ltc91lylz {
  stop-color: var(--svg-color--6e4683, #6E4683);
}

.ly_mbkbuj {
  stop-color: var(--svg-color--cf7d1a, #CF7D1A);
}

.ly5gi8b0b {
  stop-color: var(--svg-color--4e302e, #4E302E);
}

.lztr6obaf {
  stop-color: var(--svg-color--5b325e, #5B325E);
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m5wur4bob {
  stop-color: var(--svg-color--d29e3b, #D29E3B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mxc3f8vrk {
  d: path("M21.407 17.41a1.81 1.81 0 1 0 0-3.62a1.81 1.81 0 0 0 0 3.62");
}

.n4mpkaclr {
  stop-color: var(--svg-color--7d5ab2, #7D5AB2);
}

.n5jqcj8fb {
  d: path("M19.328 15.264a.95.95 0 0 0-.26-.52l-.293.32l.132.257z");
}

.nc8kb9b6x {
  stop-color: var(--svg-color--d4ab3c, #D4AB3C);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o0h7dsxoh {
  fill: var(--svg-color--000, #000);
  d: path("M17.858 15.396c0-.32.256-.575.575-.575a.573.573 0 0 1 .511.84h-1.017a.5.5 0 0 1-.069-.265");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odw-ccxrl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.p0iwm80fj {
  stroke: var(--svg-color--bc614b, #BC614B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.893 12.931c-.363-.088-1.266-.044-1.869.387");
}

.p3amiobln {
  stop-color: var(--svg-color--8261b7, #8261B7);
}

.pa_90u-ol {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.36 14.604c.07.096-.079.213-.249.34s-.296.216-.367.12c-.072-.095.008-.276.178-.403s.366-.152.437-.057");
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pzhuj_59e {
  stop-color: var(--svg-color--987ccd, #987CCD);
}

.q-4xcsbkb {
  stop-color: var(--svg-color--8f78bb, #8F78BB);
  stop-opacity: 0;
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q3wz7tzyo {
  stop-color: var(--svg-color--f59522, #F59522);
  stop-opacity: 0;
}

.q4v2oebqx {
  stop-color: var(--svg-color--f1b31f, #F1B31F);
  stop-opacity: 0;
}

.q9fwao-8y {
  fill: var(--svg-color--b54e29, #B54E29);
  fill-rule: evenodd;
  d: path("m20.174 13.085l-.155.26za.302.302 0 0 1-.31.518l-.005-.003l-.025-.013l-.102-.052a3 3 0 0 0-.386-.152a2.56 2.56 0 0 0-1.206-.104a.302.302 0 1 1-.105-.594c.578-.102 1.113 0 1.495.123a3.7 3.7 0 0 1 .628.268l.011.006l.003.002z");
}

.qa4nau83s {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.4 18.444a.224.224 0 0 0-.271.048a.214.214 0 0 0-.023.27a2.224 2.224 0 0 0 3.74 0a.22.22 0 0 0-.023-.273a.224.224 0 0 0-.27-.045h-.001a3.34 3.34 0 0 1-1.576.382c-.578 0-1.12-.139-1.576-.382Z");
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qc6cxsufz {
  stop-color: var(--svg-color--fdcd33, #FDCD33);
}

.qg4fklbdo {
  stop-color: var(--svg-color--fdcd33, #FDCD33);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qvv7abcya {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r_43arenc {
  stop-color: var(--svg-color--7653b2, #7653B2);
  stop-opacity: 0;
}

.r_9_ioa3h {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.563-.662-.782-.656h-.164c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.r0__pectf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.723 8.24c.026.273.264 1.301.613 1.924");
}

.s0l7a1b5w {
  stop-color: var(--svg-color--5b325e, #5B325E);
  stop-opacity: 0;
}

.s79xz57ql {
  stop-color: var(--svg-color--523961, #523961);
  stop-opacity: 0;
}

.sdv7knngl {
  stop-color: var(--svg-color--8a4810, #8A4810);
}

.t_1lg5u6m {
  d: path("M10.704 17.41a1.81 1.81 0 1 0 0-3.62a1.81 1.81 0 0 0 0 3.62");
}

.t2fmbzkts {
  stop-color: var(--svg-color--e4ad37, #E4AD37);
  stop-opacity: 0;
}

.t5xwmodqh {
  fill-rule: evenodd;
  d: path("M24.06 17.187a3.64 3.64 0 0 0 .364-1.606c0-.526-.108-1.019-.302-1.469h.006a3.6 3.6 0 0 0-.316-.577l-.003-.003a3.65 3.65 0 0 1-.592-1.993v-.011a3.713 3.713 0 0 0-3.711-3.712a.6.6 0 0 1-.513-.262a3.72 3.72 0 0 0-3.017-1.549a3.72 3.72 0 0 0-3.018 1.549a.64.64 0 0 1-.512.262h-.096a3.713 3.713 0 0 0-3.616 3.712v.011c0 .706-.205 1.4-.592 1.993l-.003.004a3.71 3.71 0 0 0-.248 3.65c.08.16.08.354 0 .513a3.7 3.7 0 0 0-.364 1.583a3.615 3.615 0 0 0 3.62 3.62h9.657a3.615 3.615 0 0 0 3.62-3.62c0-.57-.136-1.105-.364-1.583a.58.58 0 0 1 0-.512M10.266 14.18h-.014l1.349 2.65c.138 3.153 1.369 0 4.375 0c3.005 0 4.316 3.51 4.455.357l1.278-3.598c-.06-1.4-1.076-1.498-1.278-1.498h-3.623c-1.43 0-2.78-.7-3.588-1.883a.297.297 0 0 0-.52.057l-.092.218a2.6 2.6 0 0 1-1.454 1.435c-.265.138-.888.551-.911 1.619l.011.344z");
}

.tahhdxy3z {
  stop-color: var(--svg-color--dbae3d, #DBAE3D);
}

.tb96lttad {
  cx: 13.216px;
  cy: 14.821px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.438px;
  ry: 0.222px;
}

.tcy06xu3j {
  stop-color: var(--svg-color--8e5dc8, #8E5DC8);
}

.tdawh5bbz {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.26 14.96c.3-.525.753-.94 1.73-.94c.428 0 .84.119 1.208.415c.302.244.261.557.027.674l-.625.357c-.734-.237-1.545-.269-2.34-.506");
}

.tdk312-2s {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.534 15.35l-.769 1.913a.607.607 0 0 0 .586.786h.884a.608.608 0 0 0 .586-.786l-.598-1.913c-.128-.424-.555-.424-.689 0");
}

.tgfwo6lwf {
  stop-color: var(--svg-color--f3950f, #F3950F);
}

.u1uhvyb0r {
  stop-color: var(--svg-color--7a53a4, #7A53A4);
  stop-opacity: 0;
}

.u6j6y_csu {
  d: path("M18.36 14.604c.07.096-.079.213-.249.34s-.296.216-.367.12c-.072-.095.008-.276.178-.403s.366-.152.437-.057");
}

.u8isk7i_t {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.v0q5d6bwm {
  stop-color: var(--svg-color--7860a4, #7860A4);
  stop-opacity: 0;
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v4_ps9b4y {
  stop-color: var(--svg-color--3f203a, #3F203A);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vm5gdfbfi {
  d: path("M10.726 16.809a1.209 1.209 0 1 0 0-2.417a1.209 1.209 0 0 0 0 2.417");
}

.vrw28oiox {
  stop-color: var(--svg-color--be5b14, #BE5B14);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w5-280bhr {
  stop-color: var(--svg-color--ae8b45, #AE8B45);
  stop-opacity: 0;
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.w9m3_8gbd {
  stop-color: var(--svg-color--d5a136, #D5A136);
}

.wdetgvldd {
  stop-color: var(--svg-color--a27cda, #A27CDA);
  stop-opacity: 0;
}

.weeqywbny {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.286 14.086c-.735 0-1.356.507-1.525 1.191c-.05.197.1.384.301.384h2.51a.26.26 0 0 0 .256-.306a1.576 1.576 0 0 0-1.542-1.269");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x_mri4gas {
  d: path("M23.873 27.147c-1.95-1.2-3.036-3.417-3.36-4.157c-5.174 0-9.28 1.97-10.406 6.657h14.188c0-.9-.156-1.938-.422-2.5");
}

.x-1h17b9i {
  stop-color: var(--svg-color--b77a28, #B77A28);
}

.x278nyb7a {
  stop-color: var(--svg-color--ffe23e, #FFE23E);
}

.x4orl4h6r {
  stop-color: var(--svg-color--ffc423, #FFC423);
}

.x733f4b8w {
  stop-color: var(--svg-color--9179cd, #9179CD);
}

.xn68z7b1j {
  stop-color: var(--svg-color--d4ab3c, #D4AB3C);
  stop-opacity: 0;
}

.xw2qhwj5i {
  stop-color: var(--svg-color--fbca32, #FBCA32);
}

.y0zwm33ay {
  d: path("M6.367 5.28c.269-.07.742.028.945.085L10.5 7.53c.352.415.19.967.055 1.18L8.48 12.221a4.5 4.5 0 0 0-.11 4.382l2.96 5.634a.37.37 0 0 0 .492.152c.203-.101.82-.33 1.323-.515l.524-.195v.586a2.307 2.307 0 1 0 4.614 0v-.684c.672.276 1.662.692 1.894.808a.37.37 0 0 0 .493-.152l2.96-5.634a4.5 4.5 0 0 0-.11-4.382l-2.075-3.512c-.135-.213-.297-.765.055-1.18l3.188-2.164c.203-.057.676-.154.945-.086c.336.086.594.329.812.688c.175.287 1.47 2.48 2.094 3.539c.563.823 1.625 3.088 1.375 5.563c-.1 1.662-.781 3.338-1.11 3.968l-4.132 7.855c-.173.33-.187.719-.08 1.076c.158.529.322 1.28.322 2.022H7.086c0-.743.164-1.493.322-2.022a1.43 1.43 0 0 0-.08-1.076l-4.133-7.855c-.328-.63-1.01-2.306-1.11-3.968c-.25-2.476.813-4.74 1.376-5.563a958 958 0 0 1 2.094-3.54c.218-.358.476-.6.812-.687");
}

.y4yk8v7tr {
  stop-color: var(--svg-color--987ccd, #987CCD);
  stop-opacity: 0;
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.ys44xtaqp {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M10.726 16.809a1.209 1.209 0 1 0 0-2.417a1.209 1.209 0 0 0 0 2.417");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z2-1r6b6n {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.691 14.96c-.299-.525-.753-.94-1.73-.94c-.428 0-.84.119-1.207.415c-.302.244-.262.557-.027.674l.625.357c.733-.237 1.544-.269 2.339-.506");
}

.zkbq2obgs {
  stop-color: var(--svg-color--ffcc3e, #FFCC3E);
}

.zus0jubvv {
  d: path("M18.433 14.392a1.004 1.004 0 0 1 .968 1.269h-1.94a1.008 1.008 0 0 1 .972-1.269");
}

.zw6cmm23y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

</style>
