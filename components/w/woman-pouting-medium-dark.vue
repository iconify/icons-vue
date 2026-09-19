<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9Dq4eB)"><path fill="url(#iRc8Tbc)" clip-rule="evenodd" class="py15ldbnv"/><path fill="url(#iTVJwTb)" clip-rule="evenodd" class="py15ldbnv"/><path fill="url(#i67Tqmd)" clip-rule="evenodd" class="py15ldbnv"/><path fill="url(#i43QYjc)" clip-rule="evenodd" class="py15ldbnv"/><path fill="url(#iWvztMe)" clip-rule="evenodd" class="py15ldbnv"/><path fill="url(#iTAemQe)" clip-rule="evenodd" class="py15ldbnv"/><path fill="url(#ifnXwzd)" clip-rule="evenodd" class="py15ldbnv"/><path fill="url(#ii8yvfu)" clip-rule="evenodd" class="py15ldbnv"/><path fill="url(#iCrglDe)" clip-rule="evenodd" class="py15ldbnv"/><path fill="url(#iJiu9jb)" clip-rule="evenodd" class="py15ldbnv"/><path fill="url(#ih7cP9c)" clip-rule="evenodd" class="py15ldbnv"/></g><path fill="url(#iqkbJ5b)" class="nbb4y2b5h"/><path fill="url(#iFkR15T)" class="nbb4y2b5h"/><path fill="url(#iXXCYgd)" class="nbb4y2b5h"/><path fill="url(#i7oXz9d)" class="nbb4y2b5h"/><path fill="url(#idyVLJc)" class="xxbt6zn9m"/><path fill="url(#i1h68Ic)" class="xxbt6zn9m"/><path fill="url(#i9dtpAb)" class="ldghddv0u"/><path fill="url(#iWw9U4c)" class="ldghddv0u"/><path fill="url(#iBODEdK)" class="ldghddv0u"/><g filter="url(#iN9F03c)"><path fill="url(#iHwdUwc)" class="en7s-n43f"/></g><path fill="url(#iINGXoq)" class="en7s-n43f"/><path fill="url(#i8CUwUc)" class="en7s-n43f"/><path fill="url(#iHate7j)" class="en7s-n43f"/><g filter="url(#iurRoyW)"><path fill="url(#infT91c)" class="drrtrhbzn"/><path fill="url(#iDymYhc)" class="drrtrhbzn"/></g><rect fill="url(#iHxomfb)" class="dn4d3682r"/><g filter="url(#ipDqNKb)"><path class="e74zqub-p"/></g><g filter="url(#iYwGXGd)"><path class="j6fa55bil"/></g><path class="b0msec53k"/><path fill="url(#iQTKKUc)" class="x7nq7wgaa"/><path class="idv6xgweg"/><g filter="url(#iqxR2rL)"><path class="kp6ra-bju"/><path fill="url(#ihrF5oc)" class="zmeko4bdj"/></g><g filter="url(#iChqHRc)"><path fill="url(#iYmP1ub)" class="h3_blnb5o"/></g><path class="s9oq5du9i"/><path fill="url(#i1GDFmd)" class="v3iun_bxh"/><path class="xc_yqnbyx"/><g filter="url(#iOqHg1r)"><path fill="url(#i3Fi8bd)" class="y571vjp9q"/></g><g filter="url(#i3TeYGb)"><ellipse transform="rotate(-27.914 13.597 10.133)" class="h0umdsb9u"/><ellipse fill="url(#i7ojsdr)" transform="rotate(-27.914 13.597 10.133)" class="bkxrzxfaf"/></g><g filter="url(#iJHFcgr)"><path fill="url(#i4XEsNb)" class="yf0fl-bni"/></g><g filter="url(#ipEpsXc)"><path fill="url(#i28tbQb)" class="lalr9_kvp"/><path fill="url(#iwYLIxz)" class="lalr9_kvp"/></g><g filter="url(#ikFS46d)"><path class="tpi6ydnsr"/><path fill="url(#iacaMMb)" class="r5br3ebku"/></g><g filter="url(#i9IHQpi)"><path class="ebs_accnm"/><path fill="url(#iJps0KB)" class="l_mwys05q"/></g><g filter="url(#igMlKjd)"><path fill="url(#iT2aIWc)" class="kwtc84bmu"/><path fill="url(#iFcx0eb)" class="kwtc84bmu"/><path fill="url(#iOdRtPc)" class="kwtc84bmu"/><path fill="url(#iFKkdZb)" class="kwtc84bmu"/><path fill="url(#iF08fAd)" class="kwtc84bmu"/><path fill="url(#ix0OGry)" class="kwtc84bmu"/><path fill="url(#imkVY6c)" class="kwtc84bmu"/><path fill="url(#iyJpkKb)" class="kwtc84bmu"/><path fill="url(#iRQ2BJV)" class="kwtc84bmu"/></g><path fill="url(#iNUgBrc)" class="kwtc84bmu"/><g filter="url(#i4Msa0c)"><path class="xecohubck"/></g><g filter="url(#iQR5G9I)"><path class="airdl4z1g"/><path fill="url(#iCmj7Eb)" class="jtonf3boi"/><path fill="url(#iAvy8oi)" class="jtonf3boi"/><path fill="url(#iQD2vDd)" class="jtonf3boi"/><path fill="url(#ilLeDZb)" class="jtonf3boi"/></g><path fill="url(#iTMuvlc)" class="jtonf3boi"/><path fill="url(#iT93lab)" class="jtonf3boi"/><g filter="url(#i01b1Fe)"><path class="myr6auabb"/></g><g filter="url(#ium4U5N)"><path class="jg_lshlhu"/></g><path class="v0772nbeb"/><path fill="url(#ihtvHSc)" class="bocvfoi6o"/><path class="tr9mabeqm"/><g filter="url(#iAL8IZd)"><path class="gp8xz73ko"/><path fill="url(#iAFfskd)" class="hu-l1vbkt"/></g><g filter="url(#iavTPFb)"><path fill="url(#iR86Woc)" class="w--u_ccvp"/></g><path class="mbnl93g5j"/><path fill="url(#iz6axPb)" class="rxdmped-p"/><path class="aa9o5j61v"/><g filter="url(#iWm8x0d)"><path fill="url(#iSkMM0d)" class="p1-fwmb0q"/></g><g filter="url(#izHC78x)"><ellipse transform="rotate(-27.914 13.49 10.093)" class="v-pddxvjj"/><ellipse fill="url(#irTLWgb)" transform="rotate(-27.914 13.49 10.093)" class="zzy93iskp"/></g><g filter="url(#intHOob)"><path class="fxg8xkzgd"/><path fill="url(#i7nvmle)" class="aeu3emddr"/></g><g filter="url(#i7IEs1c)"><path class="xqp4ueb7y"/><path fill="url(#iQXy3pd)" class="rmyjb5beg"/><path fill="url(#iWEvYCc)" class="rmyjb5beg"/></g><g filter="url(#iGFE6db)"><path stroke="url(#iJ0fNeM)" class="hy__gx5fz"/></g><g filter="url(#iio1RDc)"><path class="o8aw9gbne"/></g><g filter="url(#iqexSQd)"><path stroke="url(#iU4R05d)" clip-rule="evenodd" class="b_-gfdczs"/><path stroke="url(#ilhkKpe)" clip-rule="evenodd" class="b_-gfdczs"/></g><path clip-rule="evenodd" class="y2ky7ab4a"/><g filter="url(#i3iXfcc)"><path fill="url(#irgvV0b)" class="kexj4gomu"/></g><g filter="url(#iRtIPdd)"><rect class="vrouchppf"/></g><g filter="url(#i1WUZvx)"><rect class="l7gdx3ceq"/></g><g filter="url(#ivgMW9b)"><path class="zy0rhmb_c"/></g><g filter="url(#iZO611b)"><path class="a7f1s9b5d"/></g><defs><radialGradient id="iTVJwTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.61436 4.64187 -5.79864 -.76746 15.68 13.344)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="i67Tqmd" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.325 8.767)scale(3.54054 4.65199)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i43QYjc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.804 8.243)scale(2.19133 1.68264)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iWvztMe" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.246 7.708)scale(2.52001 1.77513)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iTAemQe" cx="0" cy="0" r="1" gradientTransform="matrix(1.39937 2.66225 -3.69562 1.94255 12.403 2.592)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ifnXwzd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46756 1.46766 -2.05103 -2.0509 21.926 4.709)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ii8yvfu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87715 .5461 -1.13886 -3.91463 23.632 9.931)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iCrglDe" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.683 8.123)scale(2.9552 3.76448)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iJiu9jb" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.069 -3.715)scale(2.8512 2.25513)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ih7cP9c" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -89.718 97.995)scale(1.53963 2.49465)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iqkbJ5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.625 -11.8762 0 16.002 15.958)" gradientUnits="userSpaceOnUse"><stop class="l4nwu-c5t"/><stop offset="1" class="c0giurt9j"/></radialGradient><radialGradient id="iFkR15T" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.06339 5.05408 0 22.943 23.27)" gradientUnits="userSpaceOnUse"><stop class="kropdjn8m"/><stop offset="1" class="jl9qoxtbg"/></radialGradient><radialGradient id="i7oXz9d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.65625 0 0 -3.18983 15.005 15.49)" gradientUnits="userSpaceOnUse"><stop offset=".225" class="vpya669ti"/><stop offset="1" class="sh_b6m3le"/></radialGradient><radialGradient id="idyVLJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4266 -.1154 .41566 5.13875 24.387 23.762)" gradientUnits="userSpaceOnUse"><stop class="cp-d4w76k"/><stop offset="1" class="kbv5awe4z"/></radialGradient><radialGradient id="i9dtpAb" cx="0" cy="0" r="1" gradientTransform="matrix(3.29142 1.0992 -1.85676 5.55982 5.897 21.547)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="czk58ibbt"/><stop offset=".965" class="j_bmu-wtk"/></radialGradient><radialGradient id="iBODEdK" cx="0" cy="0" r="1" gradientTransform="matrix(.17189 -4.40625 .36187 .01412 8.552 24.58)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="jw1a1w0ab"/><stop offset="1" class="b462b5bvz"/></radialGradient><radialGradient id="iHwdUwc" cx="0" cy="0" r="1" gradientTransform="matrix(14.39625 1.34665 -.34444 3.6822 16.667 24.736)" gradientUnits="userSpaceOnUse"><stop class="p0lftvbvg"/><stop offset="1" class="ef7cjeq0h"/></radialGradient><radialGradient id="iINGXoq" cx="0" cy="0" r="1" gradientTransform="matrix(.70684 1.42914 -5.7496 2.8437 17.493 26.513)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="jyw_alb4y"/><stop offset="1" class="ti5s1ob3c"/></radialGradient><radialGradient id="i8CUwUc" cx="0" cy="0" r="1" gradientTransform="rotate(163.022 11.216 13.965)scale(5.74064 1.49909)" gradientUnits="userSpaceOnUse"><stop class="tlp_hijwf"/><stop offset="1" class="ix_m7ebzb"/></radialGradient><radialGradient id="iHate7j" cx="0" cy="0" r="1" gradientTransform="rotate(-134.178 11.952 9.583)scale(4.61877 12.7797)" gradientUnits="userSpaceOnUse"><stop class="p5-nbbcqi"/><stop offset="1" class="o229e6cph"/></radialGradient><radialGradient id="infT91c" cx="0" cy="0" r="1" gradientTransform="matrix(.54681 2.7031 -23.81541 4.8176 16.266 25.067)" gradientUnits="userSpaceOnUse"><stop offset=".044" class="z1jqhlm_c"/><stop offset=".498" class="vq5hracyt"/></radialGradient><radialGradient id="iHxomfb" cx="0" cy="0" r="1" gradientTransform="matrix(2.42726 2.33472 -2.87161 2.98543 15.163 16.276)" gradientUnits="userSpaceOnUse"><stop offset=".357" class="v-sa347qt"/><stop offset=".962" class="b9hne165d"/></radialGradient><radialGradient id="iQTKKUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82156 -1.30678 0 18.29 10.23)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ihrF5oc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.556 .735)scale(.38306 .52738)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1GDFmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82156 -1.30678 0 13.871 10.23)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i7ojsdr" cx="0" cy="0" r="1" gradientTransform="matrix(-.00783 -.5003 .60137 -.00942 13.581 10.451)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i28tbQb" cx="0" cy="0" r="1" gradientTransform="matrix(2.53426 -1.15194 1.40646 3.0942 20.1 11.245)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iwYLIxz" cx="0" cy="0" r="1" gradientTransform="matrix(1.33966 .7509 -.21229 .37874 21.15 9.086)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iacaMMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53731 -.11435 .0894 1.20175 20.458 10.912)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iJps0KB" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.651 5.399)scale(1.07514)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iT2aIWc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.62169 3.05348 -4.08703 -8.86301 18.898 10.25)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iFcx0eb" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.828 7.452)scale(2.42529 1.68893)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iOdRtPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.31256 -3.9997 5.07488 1.6654 13.786 16.876)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iFKkdZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.125 -8.90616 0 15.987 9.896)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="kpfusfbhk"/><stop offset="1" class="zown6ueue"/></radialGradient><radialGradient id="iF08fAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38256 -6.41674 0 15.721 10.659)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="fv84zpbqk"/><stop offset="1" class="kc83dxbna"/></radialGradient><radialGradient id="ix0OGry" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.331 6.873)scale(7.16519 12.3363)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="imkVY6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17167 1.43796 0 18.33 9.825)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iyJpkKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.33635 1.53155 0 13.873 9.592)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iRQ2BJV" cx="0" cy="0" r="1" gradientTransform="matrix(-.88596 3.28535 -2.62882 -.70892 17.395 7.467)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iNUgBrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30862 0 0 -6.56263 21.175 11.34)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iCmj7Eb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46382 -2.08113 .64138 -.14294 16.787 12.08)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="ilLeDZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79356 0 0 -.22185 16.542 12.295)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iT93lab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39611 .95848 -1.15195 -1.67791 16.37 11.689)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="ihtvHSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82605 -1.31393 0 18.209 10.19)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iAFfskd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23613 -.30428 .41893 -.3251 17.976 10.276)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iz6axPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82605 -1.31393 0 13.765 10.19)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="irTLWgb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00788 -.50303 .60467 -.00947 13.475 10.413)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i7nvmle" cx="0" cy="0" r="1" gradientTransform="matrix(1.28495 -2.80547 1.4352 .65735 10.226 8.031)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iQXy3pd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1503 4.4712 -7.31016 -3.51563 17.933 2.73)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iWEvYCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21415 1.39202 -2.99487 -.46074 16.2 3.105)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iU4R05d" cx="0" cy="0" r="1" gradientTransform="rotate(116.896 4.003 12.163)scale(.30222 .93391)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="dm3q2i2vr"/><stop offset="1" class="l-6i7o8sk"/></radialGradient><radialGradient id="ilhkKpe" cx="0" cy="0" r="1" gradientTransform="matrix(.16016 -.09766 .11816 .19379 14.927 14.22)" gradientUnits="userSpaceOnUse"><stop class="dm3q2i2vr"/><stop offset="1" class="l-6i7o8sk"/></radialGradient><radialGradient id="irgvV0b" cx="0" cy="0" r="1" gradientTransform="matrix(.54688 -.23828 .10932 .2509 15.697 14.869)" gradientUnits="userSpaceOnUse"><stop class="t13ylcbqs"/><stop offset="1" class="aa9wsyy5l"/></radialGradient><filter id="i9Dq4eB" width="15.541" height="16.041" x="8.342" y="1.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="iN9F03c" width="19.161" height="7.244" x="8.163" y="22.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.219608 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="iurRoyW" width="19.009" height="7.177" x="5.176" y="22.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.266667 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="ipDqNKb" width="3.037" height="1.302" x="17.037" y="9.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="iYwGXGd" width="3.037" height="1.302" x="12.088" y="9.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="iqxR2rL" width=".794" height=".703" x="17.548" y="9.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".05"/></filter><filter id="iChqHRc" width=".897" height=".92" x="18.4" y="9.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".1"/></filter><filter id="iOqHg1r" width=".994" height="1.048" x="13.901" y="9.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".1"/></filter><filter id="i3TeYGb" width=".922" height=".711" x="13.136" y="9.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".05"/></filter><filter id="iJHFcgr" width="3.427" height="3.277" x="9.578" y="9.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="ipEpsXc" width="3.277" height="3.527" x="19.264" y="8.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="ikFS46d" width="3.187" height="3.187" x="19.308" y="9.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".25"/></filter><filter id="i9IHQpi" width="2.687" height="2.687" x="9.892" y="9.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".125"/></filter><filter id="igMlKjd" width="10.376" height="11.274" x="10.799" y="5.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="i4Msa0c" width="2.911" height="3.731" x="14.366" y="9.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".25"/></filter><filter id="iQR5G9I" width="2.411" height="3.231" x="14.781" y="9.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".125"/></filter><filter id="i01b1Fe" width="3.052" height="1.309" x="16.95" y="9.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="ium4U5N" width="3.052" height="1.309" x="11.972" y="9.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="iAL8IZd" width=".797" height=".705" x="17.463" y="9.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".05"/></filter><filter id="iavTPFb" width=".9" height=".923" x="18.32" y="9.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".1"/></filter><filter id="iWm8x0d" width=".997" height="1.052" x="13.796" y="9.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".1"/></filter><filter id="izHC78x" width=".926" height=".714" x="13.026" y="9.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".05"/></filter><filter id="intHOob" width="4.474" height="4.781" x="9.425" y="3.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/><feGaussianBlur result="effect2_foregroundBlur_13036_4634" stdDeviation=".25"/></filter><filter id="i7IEs1c" width="8.917" height="5.878" x="12.764" y="2.58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/><feGaussianBlur result="effect2_foregroundBlur_13036_4634" stdDeviation=".125"/></filter><filter id="iGFE6db" width="1.155" height="2.341" x="12.743" y="3.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".1"/></filter><filter id="iio1RDc" width="7.017" height="3.906" x="15.158" y="4.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".5"/></filter><filter id="iqexSQd" width="2.698" height="1.082" x="14.766" y="13.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".05"/></filter><filter id="i3iXfcc" width="1.224" height=".712" x="15.456" y="14.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".05"/></filter><filter id="iRtIPdd" width="2.848" height=".741" x="12.531" y="8.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="i1WUZvx" width="2.848" height=".741" x="17.05" y="8.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4634"/></filter><filter id="ivgMW9b" width="2.62" height=".55" x="17.123" y="8.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".075"/></filter><filter id="iZO611b" width="2.62" height=".55" x="12.628" y="8.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4634" stdDeviation=".075"/></filter><linearGradient id="iRc8Tbc" x1="20.765" x2="13.837" y1="3.719" y2="16.553" gradientUnits="userSpaceOnUse"><stop class="e2npcradg"/><stop offset="1" class="e87hw8bgw"/></linearGradient><linearGradient id="iXXCYgd" x1="16.505" x2="16.505" y1="30.331" y2="26.581" gradientUnits="userSpaceOnUse"><stop class="waift8brn"/><stop offset="1" class="qeur-ccno"/></linearGradient><linearGradient id="i1h68Ic" x1="22.8" x2="23.56" y1="22.828" y2="22.774" gradientUnits="userSpaceOnUse"><stop class="cyj659bzg"/><stop offset="1" class="jmgn8ibxu"/></linearGradient><linearGradient id="iWw9U4c" x1="9.63" x2="8.474" y1="23.831" y2="23.737" gradientUnits="userSpaceOnUse"><stop class="g27c6tbna"/><stop offset="1" class="jvn9nabmr"/></linearGradient><linearGradient id="iDymYhc" x1="16.658" x2="16.189" y1="28.302" y2="24.865" gradientUnits="userSpaceOnUse"><stop class="c267h0b4y"/><stop offset="1" class="c6oid1bon"/></linearGradient><linearGradient id="iYmP1ub" x1="19.078" x2="18.761" y1="10.284" y2="10.48" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3Fi8bd" x1="14.625" x2="14.307" y1="10.284" y2="10.48" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4XEsNb" x1="9.63" x2="10.893" y1="10.887" y2="10.887" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iAvy8oi" x1="15.031" x2="15.987" y1="12.153" y2="12.153" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iQD2vDd" x1="15.987" x2="15.987" y1="12.967" y2="12.346" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iTMuvlc" x1="16.067" x2="16.067" y1="12.94" y2="12.798" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="iR86Woc" x1="19.001" x2="18.681" y1="10.245" y2="10.442" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSkMM0d" x1="14.523" x2="14.203" y1="10.245" y2="10.442" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJ0fNeM" x1="13.043" x2="13.598" y1="4.487" y2="5.784" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-pouting-medium-dark" /></template>
<style>
.a7f1s9b5d {
  stroke: var(--svg-color--453b3b, #453B3B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.903 8.604h2.07");
}

.aa9o5j61v {
  fill: var(--svg-color--000, #000);
  d: path("M14.284 10.613c0-.29-.232-.52-.52-.52a.518.518 0 0 0-.463.76h.92a.5.5 0 0 0 .063-.24");
}

.aa9wsyy5l {
  stop-color: var(--svg-color--724040, #724040);
}

.aeu3emddr {
  d: path("M10.826 4.701c.576-.61 1.666-.611 2.17-.52l.402 1.314c-.257-.04-.486.051-.68.239c-.456 1.283-2.025 1.99-2.752 2.184c-.151-1.519.11-2.423.86-3.217");
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.airdl4z1g {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.598 10.43l-.542 1.731a.55.55 0 0 0 .53.712h.801a.55.55 0 0 0 .53-.712l-.54-1.73c-.117-.384-.658-.384-.78 0");
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b_-gfdczs {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.952 14.261c-.485-.33-1.193-.33-1.673 0a.2.2 0 1 1-.226-.33c.616-.423 1.504-.423 2.124 0a.2.2 0 1 1-.225.33");
}

.b0msec53k {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.502 9.471c.661 0 1.22.456 1.372 1.072a.278.278 0 0 1-.271.345h-2.26a.233.233 0 0 1-.23-.275a1.415 1.415 0 0 1 1.389-1.142");
}

.b462b5bvz {
  stop-color: var(--svg-color--685390, #685390);
  stop-opacity: 0;
}

.b9hne165d {
  stop-color: var(--svg-color--855e5f, #855E5F);
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bkxrzxfaf {
  cx: 13.597px;
  cy: 10.133px;
  rx: 0.395px;
  ry: 0.2px;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bocvfoi6o {
  d: path("M18.21 9.704a.91.91 0 0 1 .877 1.149H17.33a.912.912 0 0 1 .88-1.148");
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.c0giurt9j {
  stop-color: var(--svg-color--7c60b2, #7C60B2);
}

.c267h0b4y {
  stop-color: var(--svg-color--814c62, #814C62);
}

.c6oid1bon {
  stop-color: var(--svg-color--7c594c, #7C594C);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
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

.cp-d4w76k {
  stop-color: var(--svg-color--a285de, #A285DE);
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyj659bzg {
  stop-color: var(--svg-color--7555ae, #7555AE);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.czk58ibbt {
  stop-color: var(--svg-color--81649d, #81649D);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dm3q2i2vr {
  stop-color: var(--svg-color--8a6667, #8A6667);
}

.dn4d3682r {
  width: 4.223px;
  height: 6.028px;
  x: 13.876px;
  y: 12.584px;
  rx: 2.111px;
}

.drrtrhbzn {
  d: path("M5.626 28.427c-.6-1.05-.454-2.813-.375-3.598l3.937-.168c.413.213 1.526.089 2.031 0l9.672-1.562c.617-.118 1.448-.177 2.125.187c.728.392.7.965.642 1.352a.1.1 0 0 1-.063.078c-4.286 1.54-12.404 4.813-13.524 5.062c-1.82.313-3.695-.039-4.445-1.351");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2npcradg {
  stop-color: var(--svg-color--46383b, #46383B);
}

.e74zqub-p {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.238 10.258c.268-.473.677-.846 1.556-.846c.385 0 .757.106 1.087.373c.272.22.235.502.024.607l-.562.321c-.66-.213-1.39-.242-2.105-.455");
}

.e87hw8bgw {
  stop-color: var(--svg-color--1d0d22, #1D0D22);
}

.ebs_accnm {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.236 11.892a1.094 1.094 0 1 0 0-2.188a1.094 1.094 0 0 0 0 2.188");
}

.ef7cjeq0h {
  stop-color: var(--svg-color--906060, #906060);
}

.en7s-n43f {
  d: path("M26.374 28.427c.6-1.05.454-2.813.375-3.598l-3.937-.168c-.413.213-1.526.089-2.031 0l-8.898-1.406c-.617-.117-2.096-.232-2.773.133c-.766.412-1 1.192-.938 1.578c4.271 1.531 12.632 4.562 13.757 4.812c1.82.313 3.695-.039 4.445-1.351");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.ft5dv1b6b {
  fill: none;
}

.fv84zpbqk {
  stop-color: var(--svg-color--65384c, #65384C);
  stop-opacity: 0;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fxg8xkzgd {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M10.826 4.701c.576-.61 1.666-.611 2.17-.52l.402 1.314c-.257-.04-.486.051-.68.239c-.456 1.283-2.025 1.99-2.752 2.184c-.151-1.519.11-2.423.86-3.217");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g27c6tbna {
  stop-color: var(--svg-color--5f488a, #5F488A);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gp8xz73ko {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.144 9.897c.065.086-.07.192-.225.307c-.153.115-.268.196-.332.11c-.065-.088.007-.25.161-.366s.331-.138.396-.051");
}

.h0umdsb9u {
  cx: 13.597px;
  cy: 10.133px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.h3_blnb5o {
  d: path("M19.098 10.531a.85.85 0 0 0-.235-.469l-.263.29l.119.23z");
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hu-l1vbkt {
  d: path("M18.144 9.897c.065.086-.07.192-.225.307c-.153.115-.268.196-.332.11c-.065-.088.007-.25.161-.366s.331-.138.396-.051");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hy__gx5fz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.043 4.137c.024.248.24 1.178.555 1.741");
}

.idv6xgweg {
  fill: var(--svg-color--000, #000);
  d: path("M17.775 10.65c0-.287.23-.518.518-.518a.515.515 0 0 1 .46.756h-.916a.47.47 0 0 1-.062-.238");
}

.ix_m7ebzb {
  stop-color: var(--svg-color--856156, #856156);
  stop-opacity: 0;
}

.j_bmu-wtk {
  stop-color: var(--svg-color--604885, #604885);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6fa55bil {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.925 10.258c-.27-.473-.678-.846-1.557-.846a1.68 1.68 0 0 0-1.087.373c-.272.22-.235.502-.024.607l.563.321c.66-.213 1.39-.242 2.105-.455");
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jg_lshlhu {
  fill: var(--svg-color--58575a, #58575A);
  d: path("M14.824 10.219c-.27-.476-.68-.851-1.565-.851c-.387 0-.76.107-1.092.375c-.274.222-.237.505-.025.61l.566.324c.664-.215 1.397-.244 2.116-.458");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jl9qoxtbg {
  stop-color: var(--svg-color--9d80d7, #9D80D7);
  stop-opacity: 0;
}

.jmgn8ibxu {
  stop-color: var(--svg-color--7555ae, #7555AE);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jtonf3boi {
  d: path("m15.598 10.43l-.542 1.731a.55.55 0 0 0 .53.712h.801a.55.55 0 0 0 .53-.712l-.54-1.73c-.117-.384-.658-.384-.78 0");
}

.jvn9nabmr {
  stop-color: var(--svg-color--5f488a, #5F488A);
  stop-opacity: 0;
}

.jw1a1w0ab {
  stop-color: var(--svg-color--685390, #685390);
}

.jyw_alb4y {
  stop-color: var(--svg-color--65344d, #65344D);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kbv5awe4z {
  stop-color: var(--svg-color--8f74c8, #8F74C8);
}

.kc83dxbna {
  stop-color: var(--svg-color--65384c, #65384C);
}

.kexj4gomu {
  d: path("M16.58 14.931a.512.512 0 1 0-1.024 0z");
}

.kp6ra-bju {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.226 9.937c.065.087-.07.192-.223.306s-.267.195-.331.109s.008-.249.16-.363c.153-.115.33-.138.394-.052");
}

.kpfusfbhk {
  stop-color: var(--svg-color--66394d, #66394D);
  stop-opacity: 0;
}

.kropdjn8m {
  stop-color: var(--svg-color--9d80d7, #9D80D7);
}

.kwtc84bmu {
  d: path("M10.807 9.512h.013l-.01-.27l-.01-.311c.02-.966.584-1.34.824-1.465q.025-.008.052-.02q.028-.013.052-.022a2.35 2.35 0 0 0 1.212-1.257l.083-.197a.269.269 0 0 1 .47-.052a3.93 3.93 0 0 0 3.247 1.704h3.279c.183 0 1.101.089 1.156 1.356l-.12 3.129c-.126 2.853-2.355 4.77-5.075 4.77s-4.948-1.917-5.073-4.77z");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l_mwys05q {
  d: path("M11.236 11.892a1.094 1.094 0 1 0 0-2.188a1.094 1.094 0 0 0 0 2.188");
}

.l-6i7o8sk {
  stop-color: var(--svg-color--8a6667, #8A6667);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l4nwu-c5t {
  stop-color: var(--svg-color--7d5bb9, #7D5BB9);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7gdx3ceq {
  width: 2.648px;
  height: 0.541px;
  x: 17.05px;
  y: 8.38px;
  fill: var(--svg-color--2c1d1c, #2C1D1C);
  rx: 0.271px;
}

.lalr9_kvp {
  d: path("M20.902 12.436a1.638 1.638 0 1 0 0-3.276a1.638 1.638 0 0 0 0 3.276");
}

.ldghddv0u {
  d: path("m5.251 24.829l3.847-.16l.059.182h.031v-7.108a10.5 10.5 0 0 0-3.937 7.086");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbnl93g5j {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.553 9.428c-.665 0-1.227.458-1.38 1.078a.28.28 0 0 0 .273.347h2.271c.145 0 .26-.133.232-.277a1.43 1.43 0 0 0-1.396-1.148");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.myr6auabb {
  fill: var(--svg-color--505051, #505051);
  d: path("M17.15 10.219c.27-.476.681-.851 1.565-.851c.387 0 .76.107 1.093.375c.273.222.237.505.025.61l-.566.324c-.664-.215-1.398-.244-2.117-.458");
}

.nbb4y2b5h {
  d: path("m9.157 24.646l-3.906.183c.578-5.253 5.03-9.34 10.437-9.34h.625c5.415 0 9.872 4.098 10.44 9.362l-4.378-.206v5.188H9.157z");
}

.o229e6cph {
  stop-color: var(--svg-color--6c4b40, #6C4B40);
  stop-opacity: 0;
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o8aw9gbne {
  fill: var(--svg-color--45363c, #45363C);
  d: path("m18.437 6.541l-1.451.267a.7.7 0 1 1-.127-1.39h2.383c1.41 0 1.876 1.421 1.933 1.906a3.2 3.2 0 0 0-2.738-.783");
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

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p0lftvbvg {
  stop-color: var(--svg-color--8e6861, #8E6861);
}

.p1-fwmb0q {
  d: path("M14.593 10.506c0-.293-.239-.49-.303-.548l-.294.284l.181.368z");
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p5-nbbcqi {
  stop-color: var(--svg-color--6c4b40, #6C4B40);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.py15ldbnv {
  fill-rule: evenodd;
  d: path("M23.303 12.233a3.3 3.3 0 0 0 .33-1.453c0-.475-.098-.922-.274-1.329h.005a3.3 3.3 0 0 0-.286-.522l-.002-.003a3.3 3.3 0 0 1-.536-1.803v-.01a3.36 3.36 0 0 0-3.359-3.36a.55.55 0 0 1-.463-.237a3.37 3.37 0 0 0-2.731-1.401a3.37 3.37 0 0 0-2.73 1.401a.58.58 0 0 1-.464.237l-.087.001a3.36 3.36 0 0 0-3.272 3.358v.01c0 .64-.186 1.268-.536 1.804l-.002.004a3.36 3.36 0 0 0-.225 3.303a.52.52 0 0 1 0 .464a3.272 3.272 0 0 0 2.947 4.709h8.738a3.27 3.27 0 0 0 3.276-3.277c0-.515-.123-1-.33-1.432a.52.52 0 0 1 0-.464M10.82 9.513h-.013l1.22 2.398c.126 2.853 1.24 0 3.96 0s3.906 3.176 4.031.322l1.157-3.255c-.055-1.267-.973-1.356-1.157-1.356H16.74a3.93 3.93 0 0 1-3.247-1.704a.268.268 0 0 0-.47.052l-.084.197a2.35 2.35 0 0 1-1.263 1.278q-.028.013-.052.02c-.24.126-.804.5-.825 1.466l.01.311z");
}

.qeur-ccno {
  stop-color: var(--svg-color--7150b0, #7150B0);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r5br3ebku {
  d: path("M20.902 11.892a1.094 1.094 0 1 0 0-2.188a1.094 1.094 0 0 0 0 2.188");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rmyjb5beg {
  d: path("M15.373 2.866c-1.154-.255-2.19.896-2.308 1.323c1.07 3.609 3.78 3.411 6.455 3.114c1.6-.178 1.774.552 1.911.904c0-4.004-3.405-4.755-6.03-5.335z");
}

.rxdmped-p {
  d: path("M13.763 9.704a.91.91 0 0 0-.875 1.149h1.755a1 1 0 0 0 .033-.24a.915.915 0 0 0-.913-.909");
}

.s9oq5du9i {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.66 9.471c-.662 0-1.22.456-1.372 1.072a.278.278 0 0 0 .27.345h2.26a.233.233 0 0 0 .23-.275a1.42 1.42 0 0 0-1.388-1.142");
}

.sh_b6m3le {
  stop-color: var(--svg-color--482e57, #482E57);
  stop-opacity: 0;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t13ylcbqs {
  stop-color: var(--svg-color--7c5857, #7C5857);
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.ti5s1ob3c {
  stop-color: var(--svg-color--65344d, #65344D);
  stop-opacity: 0;
}

.tlp_hijwf {
  stop-color: var(--svg-color--856156, #856156);
}

.tpi6ydnsr {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.902 11.892a1.094 1.094 0 1 0 0-2.188a1.094 1.094 0 0 0 0 2.188");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tr9mabeqm {
  fill: var(--svg-color--000, #000);
  d: path("M17.69 10.613c0-.289.232-.52.52-.52a.518.518 0 0 1 .463.76h-.92a.47.47 0 0 1-.063-.24");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.v-pddxvjj {
  cx: 13.489px;
  cy: 10.093px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.397px;
  ry: 0.201px;
}

.v-sa347qt {
  stop-color: var(--svg-color--643b46, #643B46);
}

.v0772nbeb {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.422 9.428c.665 0 1.226.458 1.379 1.078a.28.28 0 0 1-.273.347h-2.271a.234.234 0 0 1-.232-.277a1.42 1.42 0 0 1 1.397-1.148");
}

.v3iun_bxh {
  d: path("M13.87 9.746a.904.904 0 0 0-.872 1.142h1.746a1 1 0 0 0 .033-.238a.91.91 0 0 0-.908-.904");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vpya669ti {
  stop-color: var(--svg-color--482e57, #482E57);
}

.vq5hracyt {
  stop-color: var(--svg-color--855f50, #855F50);
}

.vrouchppf {
  width: 2.648px;
  height: 0.541px;
  x: 12.531px;
  y: 8.38px;
  fill: var(--svg-color--2c1d1c, #2C1D1C);
  rx: 0.271px;
}

.w--u_ccvp {
  d: path("M19.02 10.493a.86.86 0 0 0-.235-.47l-.265.29l.12.232z");
}

.waift8brn {
  stop-color: var(--svg-color--7150b0, #7150B0);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x7nq7wgaa {
  d: path("M18.293 9.746a.904.904 0 0 1 .87 1.142h-1.745a.907.907 0 0 1 .875-1.142");
}

.xc_yqnbyx {
  fill: var(--svg-color--000, #000);
  d: path("M14.387 10.65a.516.516 0 0 0-.518-.518a.515.515 0 0 0-.46.756h.916a.5.5 0 0 0 .062-.238");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xecohubck {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.588 10.571l-.696 1.731a.55.55 0 0 0 .53.712h.8a.55.55 0 0 0 .53-.712l-.54-1.73c-.117-.384-.503-.384-.624 0");
}

.xqp4ueb7y {
  fill: var(--svg-color--39262c, #39262C);
  d: path("M15.373 2.866c-1.154-.255-2.19.896-2.308 1.323c1.07 3.609 3.78 3.411 6.455 3.114c1.6-.178 1.774.552 1.911.904c0-4.004-3.405-4.755-6.03-5.335z");
}

.xxbt6zn9m {
  d: path("M22.925 17.832a10.48 10.48 0 0 1 3.827 7.02l-3.827-.18z");
}

.y2ky7ab4a {
  fill: var(--svg-color--86004d, #86004D);
  fill-rule: evenodd;
  d: path("M16.952 14.261c-.485-.33-1.193-.33-1.673 0a.2.2 0 1 1-.226-.33c.616-.423 1.504-.423 2.124 0a.2.2 0 1 1-.225.33");
}

.y571vjp9q {
  d: path("M14.695 10.544c0-.292-.238-.487-.302-.546l-.292.283l.18.366z");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yf0fl-bni {
  d: path("M11.216 12.436a1.638 1.638 0 1 0 0-3.276a1.638 1.638 0 0 0 0 3.276");
}

.z1jqhlm_c {
  stop-color: var(--svg-color--9b7369, #9B7369);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zmeko4bdj {
  d: path("M18.226 9.937c.065.087-.07.192-.223.306s-.267.195-.331.109s.008-.249.16-.363c.153-.115.33-.138.394-.052");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zown6ueue {
  stop-color: var(--svg-color--66394d, #66394D);
}

.zy0rhmb_c {
  stroke: var(--svg-color--453b3b, #453B3B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.398 8.604h2.07");
}

.zzy93iskp {
  cx: 13.489px;
  cy: 10.093px;
  rx: 0.397px;
  ry: 0.201px;
}

</style>
