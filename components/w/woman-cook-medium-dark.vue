<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJsF2TS)"><path fill="url(#iuBhwWc)" class="h6w1uhbwe"/><path fill="url(#iDTqytO)" class="h6w1uhbwe"/><path fill="url(#iJkgDBs)" class="h6w1uhbwe"/><path fill="url(#iMHOcKc)" class="h6w1uhbwe"/><path fill="url(#iaxvSud)" class="h6w1uhbwe"/></g><g filter="url(#isReUbM)"><path fill="url(#ifvIVJc)" class="u64zgjugq"/><path fill="url(#iPllTjb)" class="u64zgjugq"/></g><g filter="url(#ilLJwQd)"><path fill="url(#ijMm2pe)" class="tvwcg7bpl"/></g><g filter="url(#ibZfd9b)"><path class="j5m1qfbno"/><path fill="url(#iUxQ2Yh)" class="ry8eqongf"/></g><g filter="url(#iJfpgge)"><path class="z3i0j3ehy"/><path fill="url(#iErkxAd)" class="oc0ut1bfs"/></g><path class="lh7e2tbbn"/><path fill="url(#idFQcsd)" class="stu8oqovd"/><path fill="url(#iKqkAVc)" class="blpzdydjz"/><path fill="url(#iPRwR9c)" class="blpzdydjz"/><path fill="url(#irMuQ6d)" class="sqyc0-b_e"/><path fill="url(#icjGs9d)" class="sqyc0-b_e"/><path fill="url(#i3mAT7d)" class="sqyc0-b_e"/><g filter="url(#iEUwoIV)"><path fill="url(#ihb1r6c)" class="uufzy531h"/><path fill="url(#irFR3xL)" class="uufzy531h"/></g><path fill="url(#imMvuLZ)" class="uufzy531h"/><path fill="url(#iZpsOyc)" class="uufzy531h"/><g filter="url(#iOIuQAd)"><path fill="url(#iNgCPkc)" class="haclwf56c"/></g><path fill="url(#imL1N2q)" class="t0as5lb7o"/><path fill="url(#ixCkBMb)" class="t0as5lb7o"/><g filter="url(#iao2E0b)"><path class="nu-9clneb"/></g><g filter="url(#iM9PlmI)"><path class="qd3hihlro"/></g><g filter="url(#iDbYe3d)"><path class="nlbb52brb"/></g><g filter="url(#iSV7cKb)"><path fill="url(#iWCexBb)" class="fthjn8bln"/></g><g filter="url(#imo2CEc)"><path fill="url(#i73IVve)" class="csktmfbaf"/></g><g filter="url(#isyGLGb)"><path fill="url(#i3iejEe)" class="vudh53y-u"/></g><path fill="url(#i7i2Otc)" class="aqag9bbfy"/><path fill="url(#i1J4uSd)" class="aqag9bbfy"/><path fill="url(#iM8PZed)" class="blmox6b7u"/><path fill="url(#iGfoYpd)" class="blmox6b7u"/><path fill="url(#i02A4Wc)" class="blmox6b7u"/><path fill="url(#ioxtCmd)" class="s7tiqhntw"/><path fill="url(#iP4l8Qc)" class="s7tiqhntw"/><path fill="url(#iINeLPb)" class="s7tiqhntw"/><path fill="url(#iEoZCxd)" class="s7tiqhntw"/><g filter="url(#iX6Ljjb)"><path fill="url(#iepJAGc)" class="ov8nwcc1h"/></g><g filter="url(#i0ACrqb)"><path class="bajhcsb4i"/><path fill="url(#iMLVAvc)" class="nc2j6-b2o"/></g><g filter="url(#iGvOpQd)"><ellipse fill="url(#inzN4gd)" class="t-lva2_9g"/></g><g filter="url(#iTqqnZp)"><path fill="url(#iJjI9JF)" class="tv-vosbrb"/><path fill="url(#iS1qtcb)" class="tv-vosbrb"/><path fill="url(#ir8igpe)" class="tv-vosbrb"/><path fill="url(#iR7MRub)" class="tv-vosbrb"/><path fill="url(#iXu0Wxb)" class="tv-vosbrb"/></g><g filter="url(#iZgnLrd)"><path stroke="url(#ioxQemd)" class="tpemzel9y"/></g><g filter="url(#izvT2Kc)"><path stroke="url(#i4OdCld)" class="tfi36jbmt"/></g><g filter="url(#iDXRFDm)"><path stroke="url(#iSXySbe)" class="gn619t_vi"/></g><g filter="url(#iktqkpc)"><path fill="url(#iST65kd)" class="hkvk8zdkh"/><path fill="url(#iLooIYb)" class="hkvk8zdkh"/><path fill="url(#izWiSwd)" class="hkvk8zdkh"/><path fill="url(#iUoU9ib)" class="hkvk8zdkh"/><path fill="url(#i3gZrqe)" class="hkvk8zdkh"/><path fill="url(#ic6LeOc)" class="hkvk8zdkh"/><path fill="url(#iUMauBJ)" class="hkvk8zdkh"/><path fill="url(#ibrrQ8i)" class="hkvk8zdkh"/></g><path fill="url(#i1mu8zc)" class="hkvk8zdkh"/><path fill="url(#i97AzHd)" class="hkvk8zdkh"/><path fill="url(#i7VvWhb)" class="hkvk8zdkh"/><g filter="url(#i4Cjfab)"><path class="nqgof3b1h"/></g><g filter="url(#iAUQgvb)"><path class="n3y1qib6g"/><path fill="url(#ietZLRc)" class="rl4hre_lo"/><path fill="url(#i9Nyh9b)" class="rl4hre_lo"/><path fill="url(#iIwL4tx)" class="rl4hre_lo"/><path fill="url(#iUaWQTb)" class="rl4hre_lo"/></g><g filter="url(#i4Ky3tc)"><path stroke="url(#iOVuupe)" class="zn0rir-7v"/></g><path class="l-ziskbjl"/><g filter="url(#iHsCSwL)"><path class="tt5-atb3j"/></g><g filter="url(#i3AWOye)"><path class="zh54njbod"/></g><g filter="url(#ibpBfJT)"><path class="bm-xshxey"/></g><g filter="url(#ivaDSGc)"><path class="ukz0qjd3l"/></g><g filter="url(#imaSoWc)"><path fill="url(#icOAvzd)" class="ihpkfdcnk"/><path fill="url(#idoHOEj)" class="ihpkfdcnk"/></g><path fill="url(#iKCD6Ad)" class="z11yhk6pj"/><path fill="url(#iRTBnII)" class="z11yhk6pj"/><g filter="url(#igsyh8c)"><path fill="url(#iZc8rWz)" class="qvq9jhbdp"/></g><g filter="url(#izZghUd)"><path fill="url(#is2qOze)" class="r_v6tbb6q"/></g><g filter="url(#ilIY7mZ)"><path fill="url(#iiSmylb)" class="sxaj7eb4j"/></g><g filter="url(#iNF6HFe)"><path class="cjijn7bun"/></g><g filter="url(#i8UzSHv)"><path class="zbqcvi4ox"/></g><path class="zvux2nk2r"/><path fill="url(#iKbI1jc)" class="ve4373bce"/><path class="iwi8kqb9g"/><g filter="url(#iyTroQd)"><path class="tr51m_pir"/><path fill="url(#iK7B9lb)" class="zk_np5dyn"/></g><g filter="url(#idOdGYc)"><path fill="url(#ilzfKrb)" class="iw0vqhxgc"/></g><path class="l9ncprb-z"/><path fill="url(#iZNZfvc)" class="lpg0uuzhu"/><path class="ujfm1kb7u"/><g filter="url(#irZ0Sre)"><path fill="url(#itRGKMd)" class="mjtp6eb5c"/></g><g filter="url(#ijNz4sb)"><ellipse transform="rotate(-27.914 13.651 9.893)" class="i76pxf3mh"/><ellipse fill="url(#iRQ4I2c)" transform="rotate(-27.914 13.651 9.893)" class="unehog9sx"/></g><defs><radialGradient id="iDTqytO" cx="0" cy="0" r="1" gradientTransform="rotate(140.889 3.89 5.296)scale(4.24611 1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="yd_laccri"/><stop offset="1" class="dmf0acl5m"/></radialGradient><radialGradient id="iJkgDBs" cx="0" cy="0" r="1" gradientTransform="matrix(2.11985 0 0 3.47579 20.286 7.627)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="w9txrw6kc"/><stop offset="1" class="h-4ghpb7u"/></radialGradient><radialGradient id="iMHOcKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90841 -5.85233 0 14.832 12.584)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="dc6jrkblm"/><stop offset="1" class="oy6n6fbyn"/></radialGradient><radialGradient id="iaxvSud" cx="0" cy="0" r="1" gradientTransform="rotate(117.05 7.926 13.534)scale(2.23819 1.04512)" gradientUnits="userSpaceOnUse"><stop class="jsa0_reur"/><stop offset="1" class="j1xr6ccfb"/></radialGradient><radialGradient id="ifvIVJc" cx="0" cy="0" r="1" gradientTransform="rotate(-43.767 24.363 -21.17)scale(1.62195 2.626)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iPllTjb" cx="0" cy="0" r="1" gradientTransform="matrix(.61918 .73134 -.23906 .2024 21.898 8.868)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iUxQ2Yh" cx="0" cy="0" r="1" gradientTransform="matrix(-.40745 0 0 -.9238 10.761 10.532)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iErkxAd" cx="0" cy="0" r="1" gradientTransform="matrix(.66527 -.09951 .15385 1.02855 21.347 10.628)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="idFQcsd" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.27 58.616)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="iPRwR9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 24.142 30.113)" gradientUnits="userSpaceOnUse"><stop class="br4vp4byh"/><stop offset="1" class="fs29nabkl"/></radialGradient><radialGradient id="i3mAT7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.583 30.616)" gradientUnits="userSpaceOnUse"><stop class="gt-1-ac7u"/><stop offset="1" class="yrzv-0byt"/></radialGradient><radialGradient id="ihb1r6c" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 21.184 19.588)" gradientUnits="userSpaceOnUse"><stop class="b3mtuebqr"/><stop offset="1" class="txq537bby"/></radialGradient><radialGradient id="irFR3xL" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.848 32.36)" gradientUnits="userSpaceOnUse"><stop class="ygyrfpbde"/><stop offset="1" class="r7svlnonw"/></radialGradient><radialGradient id="imMvuLZ" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.213 16.28)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="imL1N2q" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 9.23 10.099)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="ixCkBMb" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.837 8.602)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="arr7-5bxc"/><stop offset="1" class="mejh1wbdq"/></radialGradient><radialGradient id="i7i2Otc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59797 1.31329 -1.29023 -1.56991 28.08 23.601)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="i1J4uSd" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 27.844 23.449)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="iM8PZed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 15.317 19.194)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="iGfoYpd" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.677 18.07)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="i02A4Wc" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.788 20.366)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="ioxtCmd" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.654 18.485)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="iINeLPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 16.207 18.789)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="iEoZCxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 19.145 21.194)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="iMLVAvc" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.937 11.251)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="via-_dbpm"/><stop offset="1" class="bt1_2zb2r"/></radialGradient><radialGradient id="inzN4gd" cx="0" cy="0" r="1" gradientTransform="matrix(2.27907 0 0 3.27907 24.876 17.803)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="uelaalb7d"/><stop offset=".746" class="i5m4wsx9z"/></radialGradient><radialGradient id="iS1qtcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.199 25.185)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ir8igpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.199 26.48)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iR7MRub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.199 27.73)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iXu0Wxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.199 29.081)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iST65kd" cx="0" cy="0" r="1" gradientTransform="rotate(155.407 8.473 7.032)scale(7.36936 9.81575)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iLooIYb" cx="0" cy="0" r="1" gradientTransform="rotate(156.406 7.97 7.286)scale(2.45132 1.69842)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="izWiSwd" cx="0" cy="0" r="1" gradientTransform="matrix(1.32825 -4.01732 5.12803 1.69549 13.93 16.554)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iUoU9ib" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3237 7.54015 -9.49173 -1.6663 17.213 9.473)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="i3gZrqe" cx="0" cy="0" r="1" gradientTransform="rotate(168.978 8.449 6.704)scale(7.24885 12.394)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="ic6LeOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17683 1.45515 0 18.53 9.471)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iUMauBJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34224 1.54986 0 14.02 9.237)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="ibrrQ8i" cx="0" cy="0" r="1" gradientTransform="rotate(105.2 6.077 10.273)scale(3.41944 2.75387)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="i1mu8zc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32427 0 0 -6.59153 21.409 10.992)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="i97AzHd" cx="0" cy="0" r="1" gradientTransform="matrix(1.80308 -1.59788 1.89562 2.13905 12 15.758)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="i7VvWhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.21571 -8.33155 .00001 16.159 7.17)" gradientUnits="userSpaceOnUse"><stop class="qnytp7vps"/><stop offset="1" class="bg5c9ebkp"/></radialGradient><radialGradient id="ietZLRc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.645 13.263 -.968)scale(2.25681 .64762)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iUaWQTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.23563 16.65 12.055)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="icOAvzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.989 5.96)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="zqw5laobm"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="idoHOEj" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.801 2.804)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="iKCD6Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.46875 8.0624 -.10205 19.239 7.21)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="rfhmcsbwp"/><stop offset="1" class="n6auyzb6w"/></radialGradient><radialGradient id="iKbI1jc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.286 9.989)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iK7B9lb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.496 .614)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZNZfvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.922 9.989)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRQ4I2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.636 10.208)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iJsF2TS" width="15.95" height="13.5" x="7.784" y="4.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.101961 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.337255 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1878" result="effect2_innerShadow_4002_1878"/></filter><filter id="isReUbM" width="1.514" height="3.441" x="21.026" y="8.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="ilLJwQd" width="1.671" height="3.2" x="9.668" y="8.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="ibZfd9b" width="1.329" height="2.379" x="10.072" y="9.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".125"/></filter><filter id="iJfpgge" width="1.947" height="2.903" x="20.566" y="9.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".25"/></filter><filter id="iEUwoIV" width="14.3" height="12.3" x="8.829" y="17.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="iOIuQAd" width="6.538" height="5.771" x="12.472" y="16.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".325"/></filter><filter id="iao2E0b" width="2.5" height="2.5" x="18.92" y="26.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".25"/></filter><filter id="iM9PlmI" width="2.5" height="2.5" x="18.92" y="23.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".25"/></filter><filter id="iDbYe3d" width="2.5" height="2.5" x="18.92" y="19.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".25"/></filter><filter id="iSV7cKb" width="1.7" height="1.7" x="19.59" y="27.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1878" result="effect2_innerShadow_4002_1878"/></filter><filter id="imo2CEc" width="1.7" height="1.7" x="19.59" y="23.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1878" result="effect2_innerShadow_4002_1878"/></filter><filter id="isyGLGb" width="1.7" height="1.7" x="19.59" y="19.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1878" result="effect2_innerShadow_4002_1878"/></filter><filter id="iX6Ljjb" width="2.238" height="1.809" x="14.98" y="17.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1878" result="effect2_innerShadow_4002_1878"/></filter><filter id="i0ACrqb" width="5.047" height="11.336" x="23.532" y="14.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.521569 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="iGvOpQd" width="3.672" height="4.703" x="23.995" y="15.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.647059 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/><feGaussianBlur result="effect2_foregroundBlur_4002_1878" stdDeviation=".05"/></filter><filter id="iTqqnZp" width="4.468" height="5.556" x="23.762" y="24.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="iZgnLrd" width="2.097" height=".3" x="24.132" y="25.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".05"/></filter><filter id="izvT2Kc" width="2.097" height=".3" x="24.053" y="27.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".05"/></filter><filter id="iDXRFDm" width="2.097" height=".3" x="24.132" y="28.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".05"/></filter><filter id="iktqkpc" width="10.5" height="11.373" x="10.909" y="5.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="i4Cjfab" width="2.877" height="3.9" x="14.459" y="9.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".25"/></filter><filter id="iAUQgvb" width="2.377" height="3.4" x="14.916" y="9.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".125"/></filter><filter id="i4Ky3tc" width="3.518" height="1.373" x="14.345" y="13.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".05"/></filter><filter id="iHsCSwL" width="2.439" height="1.19" x="17.694" y="7.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="i3AWOye" width="2.439" height="1.176" x="12.437" y="7.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="ibpBfJT" width="2.655" height="1.379" x="12.231" y="7.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".2"/></filter><filter id="ivaDSGc" width="2.655" height="1.387" x="17.51" y="7.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".2"/></filter><filter id="imaSoWc" width="14.779" height="5.543" x="8.765" y="1.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="igsyh8c" width=".675" height="2.047" x="13.012" y="3.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".05"/></filter><filter id="izZghUd" width=".675" height="2.047" x="18.6" y="3.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".05"/></filter><filter id="ilIY7mZ" width=".98" height="2.537" x="15.669" y="3.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".1"/></filter><filter id="iNF6HFe" width="2.611" height="1.227" x="17.394" y="9.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="i8UzSHv" width="2.611" height="1.227" x="12.206" y="9.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1878"/></filter><filter id="iyTroQd" width=".787" height=".696" x="17.552" y="9.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".05"/></filter><filter id="idOdGYc" width=".891" height=".913" x="18.392" y="9.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".1"/></filter><filter id="irZ0Sre" width=".986" height="1.04" x="13.949" y="9.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".1"/></filter><filter id="ijNz4sb" width=".913" height=".705" x="13.194" y="9.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1878" stdDeviation=".05"/></filter><linearGradient id="iuBhwWc" x1="22.488" x2="15.005" y1="6.399" y2="18.597" gradientUnits="userSpaceOnUse"><stop class="cd2w3_-kd"/><stop offset=".862" class="cl0gv76ti"/></linearGradient><linearGradient id="ijMm2pe" x1="9.692" x2="10.278" y1="10.618" y2="10.618" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iKqkAVc" x1="23.287" x2="26.53" y1="25.779" y2="25.779" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="irMuQ6d" x1="8.27" x2="8.27" y1="30.898" y2="16.835" gradientUnits="userSpaceOnUse"><stop class="da7b97bvf"/><stop offset="1" class="si_znv48i"/></linearGradient><linearGradient id="icjGs9d" x1="9.129" x2="8.551" y1="26.523" y2="26.523" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="iZpsOyc" x1="9.129" x2="13.066" y1="27.109" y2="27.109" gradientUnits="userSpaceOnUse"><stop class="t81o0ct1j"/><stop offset="1" class="v6vn_tcph"/></linearGradient><linearGradient id="iNgCPkc" x1="16.738" x2="13.777" y1="22.029" y2="18.644" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="iWCexBb" x1="20.958" x2="19.689" y1="27.543" y2="28.949" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="i73IVve" x1="20.958" x2="19.689" y1="23.902" y2="25.309" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="i3iejEe" x1="20.958" x2="19.689" y1="20.273" y2="21.679" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iP4l8Qc" x1="16.833" x2="17.817" y1="17.898" y2="19.069" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="iepJAGc" x1="16.348" x2="16.348" y1="18.788" y2="17.349" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="iJjI9JF" x1="27.79" x2="23.762" y1="27.943" y2="27.943" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="ioxQemd" x1="24.282" x2="25.991" y1="25.937" y2="25.937" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i4OdCld" x1="24.203" x2="25.913" y1="27.241" y2="27.241" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iSXySbe" x1="24.282" x2="25.991" y1="28.546" y2="28.546" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i9Nyh9b" x1="15.166" x2="16.104" y1="11.905" y2="11.905" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iIwL4tx" x1="16.104" x2="16.104" y1="12.769" y2="12.109" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iOVuupe" x1="15.172" x2="15.438" y1="14.175" y2="13.675" gradientUnits="userSpaceOnUse"><stop class="nvlbbobzu"/><stop offset="1" class="ixkv46_0d"/></linearGradient><linearGradient id="iRTBnII" x1="16.739" x2="16.739" y1="7.679" y2="6.991" gradientUnits="userSpaceOnUse"><stop class="co6smusrg"/><stop offset="1" class="bs-097z7j"/></linearGradient><linearGradient id="iZc8rWz" x1="13.485" x2="12.907" y1="5.531" y2="5.434" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ka0ki7btw"/><stop offset="1" class="r64vbvf7r"/></linearGradient><linearGradient id="is2qOze" x1="19.127" x2="18.494" y1="5.34" y2="5.434" gradientUnits="userSpaceOnUse"><stop offset=".246" class="qu7pewj0n"/><stop offset="1" class="g79jbcb8w"/></linearGradient><linearGradient id="iiSmylb" x1="16.448" x2="16.448" y1="5.676" y2="3.648" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mzy53gozy"/><stop offset="1" class="zwaih9noa"/></linearGradient><linearGradient id="ilzfKrb" x1="19.064" x2="18.751" y1="10.043" y2="10.236" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itRGKMd" x1="14.666" x2="14.352" y1="10.043" y2="10.236" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-cook-medium-dark" /></template>
<style>
.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.aqag9bbfy {
  d: path("M27.112 22.968a.97.97 0 0 1 .967.967v2.214h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.arr7-5bxc {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b3mtuebqr {
  stop-color: var(--svg-color--e9dae3, #E9DAE3);
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bajhcsb4i {
  fill: var(--svg-color--e1a474, #E1A474);
  d: path("M26.509 21.084c0-.405.26-.758.568-1.021c.605-.517 1.002-1.392 1.002-2.384c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.568.616.568 1.021v5.056h1.406z");
}

.bg5c9ebkp {
  stop-color: var(--svg-color--703f48, #703F48);
  stop-opacity: 0;
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.blmox6b7u {
  d: path("M13.917 18.594c.67-.923 1.704-1.194 2.096-1.245c.206.83.308 2.667-.683 3.564c-.635.574-1.078.722-1.67.786c-.164.018-.27-.164-.222-.321c.03-.1.051-.22.053-.366c.01-.634-.109-1.68.426-2.418");
}

.blpzdydjz {
  d: path("M23.13 29.91h4v-3.5c0-3.421-1.554-6.482-4-8.498z");
}

.bm-xshxey {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.731 8.238c.257-.17.898-.47 1.655-.352");
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.br4vp4byh {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
}

.bs-097z7j {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
  stop-opacity: 0;
}

.bt1_2zb2r {
  stop-color: var(--svg-color--eaae7e, #EAAE7E);
  stop-opacity: 0;
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.cd2w3_-kd {
  stop-color: var(--svg-color--2f1d25, #2F1D25);
}

.cjijn7bun {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M18.613 9.175c-.766.04-1.099.422-1.219.613l2.012.461c.14.008.484-.086.563-.246a.31.31 0 0 0-.051-.363c-.176-.203-.674-.497-1.305-.465");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl0gv76ti {
  stop-color: var(--svg-color--1a0e1c, #1A0E1C);
}

.co6smusrg {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.csktmfbaf {
  d: path("M20.44 25.15a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
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

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.dc6jrkblm {
  stop-color: var(--svg-color--160c19, #160C19);
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dmf0acl5m {
  stop-color: var(--svg-color--565252, #565252);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
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

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fthjn8bln {
  d: path("M21.19 28.04a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g79jbcb8w {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
  stop-opacity: 0;
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gn619t_vi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.282 28.468h1.796");
}

.gt-1-ac7u {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
}

.h-4ghpb7u {
  stop-color: var(--svg-color--150a0d, #150A0D);
  stop-opacity: 0;
}

.h6w1uhbwe {
  d: path("M23.584 10.657c0-.71-.207-1.361-.562-1.912c-.545-.846-1.488-1.2-1.488-1.861v-.01c0-.92-.138-1.761-.493-2.382H10.724c-.305.62-.394 1.461-.394 2.382v.01c0 .66-1.203 1.127-1.685 1.861a3.5 3.5 0 0 0-.561 1.912c0 .54.118 1.04.335 1.501c.069.15.069.33 0 .48c-.217.45-.335.951-.335 1.482c0 1.861 1.488 3.372 3.32 3.372h8.859c1.833 0 3.32-1.511 3.32-3.372c0-.53-.118-1.031-.334-1.481a.58.58 0 0 1 0-.48c.216-.461.335-.972.335-1.502");
}

.haclwf56c {
  d: path("M15.843 17.406c-.385.033-1.405.253-2.103 1.143c-.469.599-.498 1.44-.52 2.068q-.004.177-.013.326a1.4 1.4 0 0 1-.07.363c-.054.154.04.342.2.332c.58-.037 1.018-.163 1.664-.706c.492-.413.742-1.062.85-1.716c.044.662.23 1.332.678 1.792c.59.604 1.013.773 1.587.866c.158.026.27-.151.231-.31a1.4 1.4 0 0 1-.034-.368q.007-.15.019-.326c.04-.627.095-1.467-.313-2.11c-.607-.954-1.6-1.274-1.98-1.344a5 5 0 0 0-.127.583a5 5 0 0 0-.07-.593");
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hkvk8zdkh {
  d: path("M20.194 7.208H16.88c-1.314 0-2.508-.595-3.244-1.657a.272.272 0 0 0-.478.048l-.08.195a2.34 2.34 0 0 1-1.234 1.238a.4.4 0 0 1-.11.049c-.248.117-.816.487-.825 1.452l.139 3.236c.12 2.865 2.379 4.785 5.115 4.785c2.738 0 4.997-1.92 5.116-4.785l.13-3.08c-.02-1.355-1.026-1.481-1.215-1.481");
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.i5m4wsx9z {
  stop-color: var(--svg-color--d68e4a, #D68E4A);
}

.i76pxf3mh {
  cx: 13.651px;
  cy: 9.893px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.ihpkfdcnk {
  d: path("M10.699 1.996a1.933 1.933 0 0 0-.682 3.743a.215.215 0 0 1 .143.198v1.051c0 .249.201.45.45.45h11.099a.45.45 0 0 0 .45-.45V5.933c0-.088.059-.165.142-.197a1.934 1.934 0 0 0-.69-3.74z");
}

.iw0vqhxgc {
  d: path("M19.083 10.287a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.iwi8kqb9g {
  fill: var(--svg-color--000, #000);
  d: path("M17.777 10.404c0-.284.227-.51.511-.51a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.236");
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.ixkv46_0d {
  stop-color: var(--svg-color--845c60, #845C60);
  stop-opacity: 0;
}

.j1xr6ccfb {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
  stop-opacity: 0;
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.j5m1qfbno {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.067 9.592a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jsa0_reur {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
}

.ka0ki7btw {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l-ziskbjl {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16.104 13.687c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.279-.198-.209a3 3 0 0 1-1.386.329");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9ncprb-z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.714 9.24c-.654 0-1.205.45-1.356 1.06c-.044.173.09.34.268.34h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lh7e2tbbn {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M16.11 15.38c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.5c0-3.421-1.554-6.482-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lpg0uuzhu {
  d: path("M13.92 9.512a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
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

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mjtp6eb5c {
  d: path("M14.736 10.3c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mzy53gozy {
  stop-color: var(--svg-color--a990c1, #A990C1);
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n3y1qib6g {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.722 10.075l-.531 1.839c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.n6auyzb6w {
  stop-color: var(--svg-color--b1a3bf, #B1A3BF);
}

.nc2j6-b2o {
  d: path("M26.509 21.084c0-.405.26-.758.568-1.021c.605-.517 1.002-1.392 1.002-2.384c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.568.616.568 1.021v5.056h1.406z");
}

.nlbb52brb {
  fill: var(--svg-color--c1a0c0, #C1A0C0);
  d: path("M20.17 21.666a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.nqgof3b1h {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.618 10.271l-.635 1.838c-.108.379.152.757.52.757h.787c.37 0 .63-.384.52-.757l-.53-1.838c-.114-.407-.542-.407-.662 0");
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.nu-9clneb {
  fill: var(--svg-color--c4abda, #C4ABDA);
  d: path("M20.92 28.186a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.nvlbbobzu {
  stop-color: var(--svg-color--845c60, #845C60);
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.oc0ut1bfs {
  d: path("M21.066 11.48q.059-.952.11-1.904a.956.956 0 0 1-.11 1.904");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ov8nwcc1h {
  d: path("M15.442 17.468c.19-.063.44-.119.707-.119s.517.056.707.12a.39.39 0 0 1 .254.45c-.092.486-.269.8-.463.989a.5.5 0 0 1-.268.13c-.109.02-.337.032-.476 0a.43.43 0 0 1-.252-.13c-.194-.189-.371-.503-.464-.99a.39.39 0 0 1 .255-.45");
}

.oy6n6fbyn {
  stop-color: var(--svg-color--160c19, #160C19);
  stop-opacity: 0;
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.qd3hihlro {
  fill: var(--svg-color--bfa9d1, #BFA9D1);
  d: path("M20.17 25.296a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qnytp7vps {
  stop-color: var(--svg-color--703f48, #703F48);
}

.qu7pewj0n {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
}

.qvq9jhbdp {
  d: path("m13.587 5.786l-.475-1.848v1.848z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_v6tbb6q {
  d: path("m18.7 5.786l.474-1.848v1.848z");
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
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

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rfhmcsbwp {
  stop-color: var(--svg-color--eee3f8, #EEE3F8);
}

.rl4hre_lo {
  d: path("m15.722 10.075l-.531 1.839c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.ry8eqongf {
  d: path("M11.067 9.592a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.s7tiqhntw {
  d: path("M18.312 18.594c-.67-.923-1.704-1.194-2.096-1.245c-.205.83-.308 2.667.684 3.564c.635.574 1.077.722 1.67.786c.163.018.268-.164.221-.321c-.03-.1-.051-.22-.053-.366c-.01-.634.109-1.68-.426-2.418");
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.sqyc0-b_e {
  d: path("M9.13 17.884a10.96 10.96 0 0 0-4 8.477v3.55h4z");
}

.stu8oqovd {
  d: path("M16.11 15.38c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.5c0-3.421-1.554-6.482-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.sxaj7eb4j {
  d: path("M15.869 3.648h.58v2.137h-.58z");
}

.t-lva2_9g {
  cx: 25.806px;
  cy: 17.624px;
  rx: 1.711px;
  ry: 2.227px;
}

.t0as5lb7o {
  d: path("M23.539 18.266H8.69a10.94 10.94 0 0 1 7.42-2.885c3.483 0 5.152.81 7.429 2.885");
}

.t81o0ct1j {
  stop-color: var(--svg-color--9e8fad, #9E8FAD);
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tfi36jbmt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.204 27.163H26");
}

.tpemzel9y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.282 25.859h1.796");
}

.tr51m_pir {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.223 9.7c.064.086-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.tt5-atb3j {
  fill: var(--svg-color--352827, #352827);
  d: path("M19.837 8.075a1.85 1.85 0 0 0-.687-.412c-.304-.096-.685-.121-1.213-.057a.277.277 0 0 0 .068.55c.48-.058.776-.028.978.036c.198.063.333.164.49.3a.277.277 0 0 0 .364-.417");
}

.tv-vosbrb {
  d: path("M23.762 25.206c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.tvwcg7bpl {
  d: path("M11.05 8.931a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.txq537bby {
  stop-color: var(--svg-color--d8c4e9, #D8C4E9);
}

.u64zgjugq {
  d: path("M21.026 12.13q.1-1.594.185-3.19a1.61 1.61 0 0 1-.185 3.19");
}

.uelaalb7d {
  stop-color: var(--svg-color--da9766, #DA9766);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ujfm1kb7u {
  fill: var(--svg-color--000, #000);
  d: path("M14.432 10.405a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.236");
}

.ukz0qjd3l {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.665 8.202c-.282-.274-.897-.47-1.655-.352");
}

.unehog9sx {
  cx: 13.651px;
  cy: 9.893px;
  rx: 0.39px;
  ry: 0.197px;
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uufzy531h {
  d: path("M9.13 17.91h10.052c2.176 0 3.947 1.797 3.947 4.004v7.997h-14z");
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.v6vn_tcph {
  stop-color: var(--svg-color--c0b0d1, #C0B0D1);
  stop-opacity: 0;
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.ve4373bce {
  d: path("M18.289 9.512a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.via-_dbpm {
  stop-color: var(--svg-color--eaae7e, #EAAE7E);
}

.vudh53y-u {
  d: path("M20.44 21.52a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.w9txrw6kc {
  stop-color: var(--svg-color--150a0d, #150A0D);
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yd_laccri {
  stop-color: var(--svg-color--565252, #565252);
}

.ygyrfpbde {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
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

.z11yhk6pj {
  d: path("M22.185 5.835H10.132a.2.2 0 0 1 .028.102v1.051c0 .249.201.45.45.45h11.099a.45.45 0 0 0 .45-.45V5.933a.2.2 0 0 1 .026-.098");
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z3i0j3ehy {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M21.066 11.48q.059-.952.11-1.904a.956.956 0 0 1-.11 1.904");
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zbqcvi4ox {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M13.598 9.175c.766.04 1.1.422 1.219.613l-2.012.461c-.14.008-.484-.086-.562-.246a.31.31 0 0 1 .05-.363c.176-.203.675-.497 1.305-.465");
}

.zh54njbod {
  fill: var(--svg-color--352827, #352827);
  d: path("M12.694 7.958a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.zk_np5dyn {
  d: path("M18.223 9.7c.064.086-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.zn0rir-7v {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.104 13.687c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.279-.198-.209a3 3 0 0 1-1.386.329Z");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zqw5laobm {
  stop-color: var(--svg-color--aa92c2, #AA92C2);
}

.zvux2nk2r {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.496 9.24c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.231a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.zwaih9noa {
  stop-color: var(--svg-color--a990c1, #A990C1);
  stop-opacity: 0;
}

</style>
