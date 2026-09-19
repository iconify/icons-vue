<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i7lSAde)"><path fill="url(#iL2AdmL)" clip-rule="evenodd" class="ifjou58sj"/></g><path fill="url(#igVuEle)" clip-rule="evenodd" class="ifjou58sj"/><path fill="url(#i25FO9d)" clip-rule="evenodd" class="ifjou58sj"/><path fill="url(#iLU2iZb)" clip-rule="evenodd" class="ifjou58sj"/><path fill="url(#i2C7Ued)" clip-rule="evenodd" class="ifjou58sj"/><path fill="url(#iMQTq7d)" clip-rule="evenodd" class="ifjou58sj"/><path fill="url(#iuOXjLe)" clip-rule="evenodd" class="ifjou58sj"/><path fill="url(#iFp6pre)" clip-rule="evenodd" class="ifjou58sj"/><path class="upydt32_o"/><path fill="url(#i3b9cme)" class="ir5uabcyf"/><path fill="url(#iT6XAqe)" class="ir5uabcyf"/><path fill="url(#iTFqkvb)" class="ir5uabcyf"/><path fill="url(#i6dLLtb)" class="ir5uabcyf"/><g filter="url(#iXi2cvb)"><path class="e8jg72bqi"/></g><path fill="url(#iVk8ZRb)" class="thtcysb5g"/><path fill="url(#iySxojc)" class="thtcysb5g"/><path fill="url(#iBT0Egc)" class="yvy6tz2sx"/><path fill="url(#iSWq0Oc)" class="yvy6tz2sx"/><g filter="url(#i0yUEoc)"><path fill="url(#iPxdGmJ)" class="gfcus0k-b"/><path fill="url(#icUCMXd)" class="gfcus0k-b"/><path fill="url(#iDtHPwb)" class="gfcus0k-b"/><path fill="url(#ikLUynd)" class="gfcus0k-b"/></g><path fill="url(#iXh9ybH)" class="ldh_5l31c"/><path fill="url(#i4gZH3d)" class="ldh_5l31c"/><path fill="url(#ihSlXYc)" class="ldh_5l31c"/><g filter="url(#ioOKiDz)"><path class="dcs92d2ir"/><path fill="url(#ihxZmMc)" class="dxf81xgxc"/></g><path fill="url(#iYNmYPb)" class="qgn4spb6l"/><g filter="url(#iERSM5b)"><path class="llwl8xbbe"/><path fill="url(#i4K7vYT)" class="nbobwxzih"/><path fill="url(#i7KLMve)" class="nbobwxzih"/></g><path fill="url(#i1oXDfd)" class="nbobwxzih"/><g filter="url(#iAnmxqd)"><path fill="url(#iF5yRae)" class="oigr0yrty"/></g><g filter="url(#ifWIzZb)"><rect fill="url(#i8yzP5c)" class="f5rlg0klg"/></g><path fill="url(#iKA5pgd)" class="t2siy786u"/><path fill="url(#idy4REe)" class="n-i72ubxb"/><g filter="url(#iemmfcd)"><path fill="url(#iXVk2lb)" class="hn-n7-b5k"/><path fill="url(#iylihld)" class="hn-n7-b5k"/></g><g filter="url(#iU6nZ9d)"><path fill="url(#iAjkq0y)" class="h_h_4t2dc"/></g><g filter="url(#iqI6NOA)"><path fill="url(#ipJENqs)" class="cfiz3abhu"/><path fill="url(#ijmLFNe)" class="cfiz3abhu"/></g><g filter="url(#iVjshxb)"><path class="qrocdccto"/><path fill="url(#ijofa2b)" class="a67f08-nh"/></g><g filter="url(#iAts1Ce)"><path class="xdpsjccue"/><path fill="url(#iiaKGob)" class="m5kfvc0eh"/></g><g filter="url(#iBRMEgb)"><path fill="url(#iBdsi5b)" class="m3xkgmb-t"/><path fill="url(#iskfKte)" class="m3xkgmb-t"/><path fill="url(#iUQ9I5c)" class="m3xkgmb-t"/><path fill="url(#idqjMnd)" class="m3xkgmb-t"/><path fill="url(#i0D63bc)" class="m3xkgmb-t"/><path fill="url(#ixpBFAc)" class="m3xkgmb-t"/><path fill="url(#iZaXqKb)" class="m3xkgmb-t"/></g><path fill="url(#ilAGJ5d)" class="ayftu5j9l"/><path fill="url(#iMLzNZC)" class="ayftu5j9l"/><path fill="url(#itqNkib)" class="ayftu5j9l"/><g filter="url(#iHY6aQe)"><path class="lbq2vhbhw"/></g><g filter="url(#i1sH4oE)"><path class="fxxpwxt5r"/><path fill="url(#ihq6hLe)" class="ls327tu-e"/><path fill="url(#iAJqled)" class="ls327tu-e"/><path fill="url(#iFvFwIe)" class="ls327tu-e"/></g><g filter="url(#iw68Pbe)"><path fill="url(#in3bZBd)" class="yvpnuvb4w"/></g><g filter="url(#iplTabb)"><path stroke="url(#i056k2O)" class="wm9obhbbe"/></g><path class="ae0dqwb3b"/><g filter="url(#iV74IeE)"><path class="xpcksdqyw"/></g><g filter="url(#iLRGjub)"><path class="bpf45zbql"/></g><path class="n3gabqbgv"/><path fill="url(#iyb4T9d)" class="x04v_w04n"/><path class="jouaxabjh"/><g filter="url(#iwWK6Wc)"><path class="itout2brt"/><path fill="url(#i8ETVgc)" class="e09dj5ofg"/></g><g filter="url(#io2qWWc)"><path fill="url(#iW2wUib)" class="s8arww3_h"/></g><path class="uik0qxugc"/><path fill="url(#iJjSdQe)" class="g4avr0whh"/><path class="z0ryd6fmh"/><g filter="url(#iEocN2d)"><path fill="url(#iDye89c)" class="y0fag01yz"/></g><g filter="url(#i6ep3Ie)"><ellipse transform="rotate(-27.914 13.02 11.893)" class="ci945ccog"/><ellipse fill="url(#iiS1JAc)" transform="rotate(-27.914 13.02 11.893)" class="ouv-nzxqj"/></g><g filter="url(#iQTdgyH)"><path fill="url(#isLM7wb)" class="kotk-bqfm"/><path fill="url(#imyeZ8d)" class="kotk-bqfm"/></g><path fill="url(#iizJfPb)" class="kotk-bqfm"/><g filter="url(#iZrnSYc)"><path class="y2ilnmbem"/></g><g filter="url(#ieeAQhO)"><path fill="url(#iagoo5c)" class="kbhhadb_j"/></g><g filter="url(#i3rf7Ee)"><path fill="url(#iIgw5Lc)" class="m8dz_mblr"/><path fill="url(#iTf5cKc)" class="m8dz_mblr"/></g><g filter="url(#iSCAIzd)"><path clip-rule="evenodd" class="z6a5p4bqu"/></g><g filter="url(#ikxdUTG)"><path fill="url(#igpewSb)" clip-rule="evenodd" class="sw0blobad"/></g><path fill="url(#iiEONhS)" clip-rule="evenodd" class="sw0blobad"/><path fill="url(#i0rO5Pe)" clip-rule="evenodd" class="sw0blobad"/><defs><radialGradient id="igVuEle" cx="0" cy="0" r="1" gradientTransform="matrix(3 2.0625 -2.33786 3.40053 19.807 16.027)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="iqybgbc9n"/><stop offset="1" class="xyqpj-b-m"/></radialGradient><radialGradient id="i25FO9d" cx="0" cy="0" r="1" gradientTransform="rotate(-136.652 15.45 4.785)scale(4.59811)" gradientUnits="userSpaceOnUse"><stop class="z3n4zq94h"/><stop offset="1" class="s6yishbmu"/></radialGradient><radialGradient id="iLU2iZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50633 -16.5092 0 15.816 11.498)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="mtuo14bcx"/><stop offset=".904" class="bno831b-g"/><stop offset=".966" class="df5tgf52l"/></radialGradient><radialGradient id="i2C7Ued" cx="0" cy="0" r="1" gradientTransform="matrix(-4.56252 -2.49997 3.24575 -5.92357 12.432 18.808)" gradientUnits="userSpaceOnUse"><stop class="gegx_wy3n"/><stop offset="1" class="mfcet0q3v"/></radialGradient><radialGradient id="iMQTq7d" cx="0" cy="0" r="1" gradientTransform="rotate(104.153 1.18 9.164)scale(5.55938 1.53877)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="x1bufs-rn"/><stop offset="1" class="nyhx0mbls"/></radialGradient><radialGradient id="iuOXjLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 -3.15625 1.22442 -.21821 21.057 11.12)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="bwx80zbad"/><stop offset="1" class="b6idfybdv"/></radialGradient><radialGradient id="iFp6pre" cx="0" cy="0" r="1" gradientTransform="matrix(3.84375 1.46875 -1.5987 4.18383 17.807 17.652)" gradientUnits="userSpaceOnUse"><stop class="ko_hncw6z"/><stop offset="1" class="kn4vqfbmv"/></radialGradient><radialGradient id="i3b9cme" cx="0" cy="0" r="1" gradientTransform="matrix(.59372 6.27271 -11.9943 1.13527 13.662 18.032)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ewagz7_9h"/><stop offset="1" class="a8t42xt1y"/></radialGradient><radialGradient id="iT6XAqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 0 0 14.4101 8.099 29.934)" gradientUnits="userSpaceOnUse"><stop class="vg5w9dbzr"/><stop offset="1" class="r9aql0tfq"/></radialGradient><radialGradient id="iTFqkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -12.1562 24.005 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="bglf8cb8f"/><stop offset="1" class="f1vhuirkb"/></radialGradient><radialGradient id="iVk8ZRb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -6.93362 3.8209 .51663 6.443 29.934)" gradientUnits="userSpaceOnUse"><stop class="ff-z7nbub"/><stop offset="1" class="qt_mg48rg"/></radialGradient><radialGradient id="iySxojc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -13.7094 8.287 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="a2jurmb2n"/><stop offset="1" class="xsu_qdbmh"/></radialGradient><radialGradient id="iBT0Egc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 -8.02737 2.31779 -.47822 26.443 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="f69-7cs4d"/><stop offset="1" class="xf9qqcbnz"/></radialGradient><radialGradient id="iSWq0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36307 0 0 13.6894 23.945 29.71)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="qjgh28b1y"/><stop offset=".8" class="humbo4erb"/></radialGradient><radialGradient id="iPxdGmJ" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 3.525 14.988)scale(2.34396 3.58278)" gradientUnits="userSpaceOnUse"><stop class="ni0htxbur"/><stop offset="1" class="xsp7-kwpz"/></radialGradient><radialGradient id="icUCMXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 -1.10937 1.05865 1.5358 15.474 24.031)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nlnhxpbkx"/><stop offset="1" class="qk56hfspl"/></radialGradient><radialGradient id="iXh9ybH" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71487 -1.3158 0 15.915 25.22)" gradientUnits="userSpaceOnUse"><stop class="e9hbkmbux"/><stop offset="1" class="fqfyucbrl"/></radialGradient><radialGradient id="ihxZmMc" cx="0" cy="0" r="1" gradientTransform="matrix(.6593 -2.21966 2.48774 .73892 14.284 23.668)" gradientUnits="userSpaceOnUse"><stop class="zy2fe0b7g"/><stop offset="1" class="kdz8adazd"/></radialGradient><radialGradient id="iYNmYPb" cx="0" cy="0" r="1" gradientTransform="rotate(101.829 -.949 15.464)scale(1.68811 2.30315)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="cxc4ijbrr"/><stop offset="1" class="sjzaf5e-a"/></radialGradient><radialGradient id="i7KLMve" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .42188 -1.25086 1.38985 17.037 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="bzog60bkg"/><stop offset=".902" class="et8zn2bag"/></radialGradient><radialGradient id="i1oXDfd" cx="0" cy="0" r="1" gradientTransform="matrix(.90561 .5 -1.37227 2.48548 17.634 19.75)" gradientUnits="userSpaceOnUse"><stop class="wt_jecb6v"/><stop offset="1" class="tp8jvfpml"/></radialGradient><radialGradient id="iXVk2lb" cx="0" cy="0" r="1" gradientTransform="rotate(142.994 5.61 12.939)scale(2.81109 2.40696)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="fvnf29blq"/><stop offset="1" class="llr-3tqju"/></radialGradient><radialGradient id="iylihld" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 0 0 -1.10937 15.696 19.188)" gradientUnits="userSpaceOnUse"><stop class="bfw8jn5la"/><stop offset="1" class="vweyc3b2b"/></radialGradient><radialGradient id="ipJENqs" cx="0" cy="0" r="1" gradientTransform="matrix(2.83681 -1.28946 1.57437 3.46362 20.42 13.183)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="ijmLFNe" cx="0" cy="0" r="1" gradientTransform="matrix(1.13664 .32475 -.17074 .59757 21.585 10.652)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="ijofa2b" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 46.708 -52.322)scale(1.48685)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iiaKGob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38687 0 0 -1.32663 10.498 12.683)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iBdsi5b" cx="0" cy="0" r="1" gradientTransform="matrix(-7.95027 2.19957 -2.09123 -7.55865 19.613 13.289)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset=".716" class="gvh2bspmv"/></radialGradient><radialGradient id="iskfKte" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 7.395 8.664)scale(2.72013 2.30784)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iUQ9I5c" cx="0" cy="0" r="1" gradientTransform="matrix(.95386 -4.61029 5.8496 1.21027 13.332 19.8)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="idqjMnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.74402 -10.4975 0 15.816 11.743)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="zanrk7_8f"/><stop offset="1" class="mh0_pg5pw"/></radialGradient><radialGradient id="i0D63bc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.53327 .87869 -1.51282 -11.24822 16.542 14.73)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="ixpBFAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31155 1.8855 0 18.439 11.593)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iZaXqKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.55001 1.77642 0 13.63 11.693)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="ilAGJ5d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53514 0 0 -5.05373 21.623 13.289)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iMLzNZC" cx="0" cy="0" r="1" gradientTransform="matrix(1.3178 4.80816 -9.93578 2.72316 12.967 5.795)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="itqNkib" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.91496 -5.66087 0 15.37 10.374)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="gpq5pfbkf"/><stop offset="1" class="p32hh8bag"/></radialGradient><radialGradient id="ihq6hLe" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 13.684 .75)scale(2.90295 1.66111)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iyb4T9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92467 -1.47079 0 18.303 12.002)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i8ETVgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26432 -.34061 .46894 -.3639 18.043 12.098)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJjSdQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92467 -1.4708 0 13.33 12.002)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iiS1JAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00882 -.56308 .67686 -.0106 13.002 12.252)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isLM7wb" cx="0" cy="0" r="1" gradientTransform="rotate(153.716 9.95 5.24)scale(8.88768 11.3119)" gradientUnits="userSpaceOnUse"><stop class="b5oikgndb"/><stop offset="1" class="aiodo62qb"/></radialGradient><radialGradient id="iizJfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56249 1.8125 -5.67441 -1.76097 20.88 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="lwjbbq_rp"/><stop offset="1" class="c0fdt7b4z"/></radialGradient><radialGradient id="iIgw5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.454 12.31 1.781)scale(8.75158 12.2726)" gradientUnits="userSpaceOnUse"><stop class="hg7hxmbra"/><stop offset="1" class="i8a3pvbms"/></radialGradient><radialGradient id="iTf5cKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33594 10.5987 0 15.97 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="e3kv8ccww"/><stop offset=".917" class="t9xlhbbtl"/></radialGradient><radialGradient id="iiEONhS" cx="0" cy="0" r="1" gradientTransform="rotate(101.822 7.538 11.83)scale(1.37287 11.6524)" gradientUnits="userSpaceOnUse"><stop class="q-4mmubff"/><stop offset="1" class="z_4nico_h"/></radialGradient><radialGradient id="i0rO5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(137.81 10.052 8.132)scale(2.38738 2.66614)" gradientUnits="userSpaceOnUse"><stop class="q3vx93ufn"/><stop offset="1" class="ojnx9kp9k"/></radialGradient><filter id="i7lSAde" width="18.144" height="17.144" x="6.244" y="2.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.956863 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="iXi2cvb" width="7.365" height="6.01" x="12.146" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".25"/></filter><filter id="i0yUEoc" width="4.12" height="2.78" x="13.959" y="21.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="ioOKiDz" width="3.587" height="5.006" x="12.537" y="18.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="iERSM5b" width="3.611" height="5.002" x="15.879" y="18.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="iAnmxqd" width="3.063" height="3.733" x="18.679" y="24.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2687" result="effect2_innerShadow_4002_2687"/></filter><filter id="ifWIzZb" width="4.306" height="1.334" x="8.789" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2687" result="effect2_innerShadow_4002_2687"/></filter><filter id="iemmfcd" width="4.487" height="3.547" x="13.683" y="18.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.45098 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="iU6nZ9d" width="3.818" height="3.918" x="8.642" y="10.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="iqI6NOA" width="3.668" height="3.918" x="19.484" y="10.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="iVjshxb" width="3.448" height="3.448" x="19.594" y="10.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".25"/></filter><filter id="iAts1Ce" width="3.248" height="3.248" x="8.874" y="11.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".2"/></filter><filter id="iBRMEgb" width="11.615" height="12.646" x="10.009" y="7.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="iHY6aQe" width="3.14" height="4.057" x="14.061" y="11.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".25"/></filter><filter id="i1sH4oE" width="2.64" height="3.557" x="14.496" y="11.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".125"/></filter><filter id="iw68Pbe" width="2.64" height="3.557" x="14.496" y="11.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".125"/></filter><filter id="iplTabb" width="4.164" height="1.683" x="13.734" y="15.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".05"/></filter><filter id="iV74IeE" width="3.393" height="1.465" x="16.918" y="11.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="iLRGjub" width="3.393" height="1.465" x="11.322" y="11.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="iwWK6Wc" width=".869" height=".766" x="17.48" y="11.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".05"/></filter><filter id="io2qWWc" width=".96" height=".985" x="18.452" y="11.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".1"/></filter><filter id="iEocN2d" width="1.068" height="1.13" x="13.388" y="11.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".1"/></filter><filter id="i6ep3Ie" width="1.013" height=".775" x="12.514" y="11.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".05"/></filter><filter id="iQTdgyH" width="16.56" height="6.934" x="7.72" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.537255 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><filter id="iZrnSYc" width="2.674" height="2.948" x="14.589" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".075"/></filter><filter id="ieeAQhO" width="2.624" height="2.748" x="14.643" y="3.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2687" result="effect2_innerShadow_4002_2687"/></filter><filter id="i3rf7Ee" width="13.155" height="4.088" x="9.342" y="7.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.207843 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2687" result="effect2_innerShadow_4002_2687"/></filter><filter id="iSCAIzd" width="13.899" height="3.448" x="9.147" y="5.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2687" stdDeviation=".25"/></filter><filter id="ikxdUTG" width="14.033" height="2.72" x="9.028" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2687"/></filter><linearGradient id="iL2AdmL" x1="21.481" x2="15.324" y1="10.222" y2="20.847" gradientUnits="userSpaceOnUse"><stop class="u9bpp-1oj"/><stop offset="1" class="rxaby506o"/></linearGradient><linearGradient id="i6dLLtb" x1="7.926" x2="8.205" y1="28.477" y2="28.477" gradientUnits="userSpaceOnUse"><stop offset=".229" class="kdpeaetya"/><stop offset="1" class="rvybbdrcw"/></linearGradient><linearGradient id="iDtHPwb" x1="15.193" x2="15.498" y1="22.422" y2="22.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="ikLUynd" x1="16.404" x2="16.185" y1="22.258" y2="22.555" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="i4gZH3d" x1="17.412" x2="16.474" y1="27.875" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ahgk2rx2r"/><stop offset="1" class="nx2bsjb_t"/></linearGradient><linearGradient id="ihSlXYc" x1="14.677" x2="15.915" y1="27.11" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="yvnwtvbdk"/><stop offset="1" class="gd56libvg"/></linearGradient><linearGradient id="i4K7vYT" x1="18.787" x2="17.247" y1="22.422" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="bxeumjbad"/><stop offset="1" class="c8b-jsd8k"/></linearGradient><linearGradient id="iF5yRae" x1="21.325" x2="18.829" y1="26.246" y2="26.246" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="i8yzP5c" x1="13.095" x2="8.763" y1="26.863" y2="26.863" gradientUnits="userSpaceOnUse"><stop class="gxnbt7b-w"/><stop offset="1" class="vhpcois2a"/></linearGradient><linearGradient id="iKA5pgd" x1="7.628" x2="24.012" y1="18.164" y2="18.164" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="idy4REe" x1="7.628" x2="24.012" y1="18.13" y2="18.13" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iAjkq0y" x1="8.642" x2="12.015" y1="12.782" y2="12.782" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iAJqled" x1="14.624" x2="15.597" y1="14.136" y2="14.256" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iFvFwIe" x1="15.816" x2="15.816" y1="15.11" y2="14.415" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="in3bZBd" x1="15.816" x2="16.067" y1="11.815" y2="13.157" gradientUnits="userSpaceOnUse"><stop class="fvll0swav"/><stop offset="1" class="ojlr4zbcq"/></linearGradient><linearGradient id="i056k2O" x1="14.985" x2="15.501" y1="16.794" y2="15.8" gradientUnits="userSpaceOnUse"><stop class="nffjv6p6j"/><stop offset="1" class="pctc2_emz"/></linearGradient><linearGradient id="iW2wUib" x1="19.19" x2="18.832" y1="12.063" y2="12.284" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDye89c" x1="14.177" x2="13.819" y1="12.064" y2="12.284" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imyeZ8d" x1="7.318" x2="13.13" y1="7.656" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="ylhb00l1u"/><stop offset="1" class="r_91d457c"/></linearGradient><linearGradient id="iagoo5c" x1="16.899" x2="14.793" y1="4.541" y2="4.541" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="igpewSb" x1="10.974" x2="21.755" y1="7.7" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="ilj7ybc1n"/><stop offset="1" class="p_hknfval"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-police-officer-medium-light" /></template>
<style>
.a2jurmb2n {
  stop-color: var(--svg-color--3183ce, #3183CE);
}

.a565onb9e {
  stop-color: var(--svg-color--33488b, #33488B);
}

.a67f08-nh {
  d: path("M21.318 13.907a1.224 1.224 0 1 0 0-2.449a1.224 1.224 0 0 0 0 2.449");
}

.a8t42xt1y {
  stop-color: var(--svg-color--36a5fc, #36A5FC);
  stop-opacity: 0;
}

.ae0dqwb3b {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M15.816 16.001a3.45 3.45 0 0 1-1.62-.393c-.16-.083-.332.101-.232.25a2.202 2.202 0 0 0 3.704 0c.1-.155-.071-.333-.232-.25c-.468.25-1.02.393-1.62.393");
}

.ahgk2rx2r {
  stop-color: var(--svg-color--4a88df, #4A88DF);
}

.aiodo62qb {
  stop-color: var(--svg-color--328fdd, #328FDD);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.ayftu5j9l {
  d: path("M10.018 11.244h.014l-.011-.303l-.012-.349c.023-1.081.654-1.5.923-1.64l.059-.022l.058-.024A2.63 2.63 0 0 0 12.405 7.5l.093-.22a.3.3 0 0 1 .526-.059a4.4 4.4 0 0 0 3.635 1.907h3.67c.205 0 1.233.1 1.294 1.519l-.135 3.502c-.14 3.194-2.635 5.339-5.68 5.339s-5.538-2.145-5.679-5.339z");
}

.b5oikgndb {
  stop-color: var(--svg-color--48a8fb, #48A8FB);
}

.b6idfybdv {
  stop-color: var(--svg-color--d9aa70, #D9AA70);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bfw8jn5la {
  stop-color: var(--svg-color--b47f87, #B47F87);
}

.bglf8cb8f {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
}

.bno831b-g {
  stop-color: var(--svg-color--cca6a1, #CCA6A1);
}

.bpf45zbql {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.515 12.034c-.303-.532-.763-.953-1.753-.953c-.433 0-.85.12-1.222.42c-.306.248-.265.565-.028.684l.633.362c.743-.24 1.565-.273 2.37-.513");
}

.bwx80zbad {
  stop-color: var(--svg-color--d9aa70, #D9AA70);
}

.bxeumjbad {
  stop-color: var(--svg-color--8be8ff, #8BE8FF);
}

.bzog60bkg {
  stop-color: var(--svg-color--639be0, #639BE0);
}

.c0fdt7b4z {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
  stop-opacity: 0;
}

.c8b-jsd8k {
  stop-color: var(--svg-color--75c1ff, #75C1FF);
  stop-opacity: 0;
}

.cfiz3abhu {
  d: path("M21.318 14.516a1.834 1.834 0 1 0 0-3.667a1.834 1.834 0 0 0 0 3.667");
}

.ci945ccog {
  cx: 13.02px;
  cy: 11.893px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.444px;
  ry: 0.225px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cxc4ijbrr {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
}

.dcs92d2ir {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.824-4.062a.1.1 0 0 1 .07-.116l1.298-.37z");
}

.df5tgf52l {
  stop-color: var(--svg-color--b78890, #B78890);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dxf81xgxc {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.824-4.062a.1.1 0 0 1 .07-.116l1.298-.37z");
}

.e09dj5ofg {
  d: path("M18.23 11.674c.073.097-.078.215-.25.343c-.173.13-.3.22-.373.123c-.072-.097.008-.28.18-.409c.173-.129.371-.154.444-.057");
}

.e3kv8ccww {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
  stop-opacity: 0;
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e8jg72bqi {
  fill: var(--svg-color--2389d6, #2389D6);
  d: path("m12.646 19.685l.764 3.8a.41.41 0 0 0 .66.242l.453-.364l.601 1.204c.04.078.12.128.208.128h1.021c.09 0 .17-.05.21-.13l.586-1.187l.437.349a.41.41 0 0 0 .662-.242l.763-3.8z");
}

.e9hbkmbux {
  stop-color: var(--svg-color--3f7cd5, #3F7CD5);
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.et8zn2bag {
  stop-color: var(--svg-color--639be0, #639BE0);
  stop-opacity: 0;
}

.ewagz7_9h {
  stop-color: var(--svg-color--3a84b9, #3A84B9);
}

.f1vhuirkb {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
  stop-opacity: 0;
}

.f5rlg0klg {
  width: 4.156px;
  height: 1.234px;
  x: 8.939px;
  y: 25.977px;
  rx: 0.15px;
}

.f69-7cs4d {
  stop-color: var(--svg-color--55d2ff, #55D2FF);
}

.ff-z7nbub {
  stop-color: var(--svg-color--3bafff, #3BAFFF);
}

.fqfyucbrl {
  stop-color: var(--svg-color--3872d8, #3872D8);
}

.ft5dv1b6b {
  fill: none;
}

.fvll0swav {
  stop-color: var(--svg-color--ba8178, #BA8178);
}

.fvnf29blq {
  stop-color: var(--svg-color--c59e97, #C59E97);
}

.fxxpwxt5r {
  fill: var(--svg-color--d79f8a, #D79F8A);
  d: path("m15.38 12.27l-.605 1.938a.614.614 0 0 0 .593.797h.896c.42 0 .717-.404.594-.797l-.606-1.937c-.13-.43-.735-.43-.871 0");
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g4avr0whh {
  d: path("M13.327 11.459a1.017 1.017 0 0 0-.98 1.285h1.965q.036-.131.037-.268a1.024 1.024 0 0 0-1.022-1.018");
}

.gd56libvg {
  stop-color: var(--svg-color--3169c8, #3169C8);
  stop-opacity: 0;
}

.gegx_wy3n {
  stop-color: var(--svg-color--b28082, #B28082);
}

.gfcus0k-b {
  d: path("M16.749 24.47a.25.25 0 0 1-.224.139h-1.097a.25.25 0 0 1-.223-.139l-1.246-2.491h4.02z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gpq5pfbkf {
  stop-color: var(--svg-color--a46c6b, #A46C6B);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gxnbt7b-w {
  stop-color: var(--svg-color--ffd04c, #FFD04C);
}

.h_h_4t2dc {
  d: path("M10.476 14.516a1.834 1.834 0 1 0 0-3.667a1.834 1.834 0 0 0 0 3.667");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hg3it7oev {
  stop-color: var(--svg-color--1b54be, #1B54BE);
  stop-opacity: 0;
}

.hg7hxmbra {
  stop-color: var(--svg-color--574a69, #574A69);
}

.hn-n7-b5k {
  d: path("M13.685 18.758c-.055 1.344.883 2.656 2.277 3.297c1.453-.75 2.207-2.086 2.207-3.297z");
}

.humbo4erb {
  stop-color: var(--svg-color--189cf0, #189CF0);
  stop-opacity: 0;
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i8a3pvbms {
  stop-color: var(--svg-color--46395b, #46395B);
}

.ifjou58sj {
  fill-rule: evenodd;
  d: path("M24.019 14.27c.242-.496.37-1.05.37-1.628a3.7 3.7 0 0 0-.307-1.49h.006a3.6 3.6 0 0 0-.321-.586l-.002-.004a3.7 3.7 0 0 1-.601-2.022v-.01a3.767 3.767 0 0 0-3.767-3.766a.62.62 0 0 1-.52-.266a3.77 3.77 0 0 0-3.061-1.571c-1.26 0-2.38.624-3.061 1.571a.65.65 0 0 1-.52.266h-.097a3.767 3.767 0 0 0-3.67 3.766v.011c0 .717-.207 1.421-.6 2.022l-.003.004a3.77 3.77 0 0 0-.251 3.705c.08.161.08.358 0 .52a3.7 3.7 0 0 0-.37 1.605a3.67 3.67 0 0 0 3.674 3.674h9.797a3.67 3.67 0 0 0 3.673-3.674c0-.577-.138-1.12-.37-1.606a.59.59 0 0 1 0-.52");
}

.ilj7ybc1n {
  stop-color: var(--svg-color--73b8f6, #73B8F6);
}

.iqybgbc9n {
  stop-color: var(--svg-color--f2c4a4, #F2C4A4);
}

.ir5uabcyf {
  d: path("M3.862 29.934h24.276c-.466-6.297-5.723-11.26-12.138-11.26S4.328 23.638 3.862 29.934");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.itout2brt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.23 11.674c.073.097-.078.215-.25.343c-.173.13-.3.22-.373.123c-.072-.097.008-.28.18-.409c.173-.129.371-.154.444-.057");
}

.j3cbwjknw {
  stop-color: var(--svg-color--ffd24b, #FFD24B);
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jo3nm0bcx {
  stop-color: var(--svg-color--ffd44c, #FFD44C);
}

.jouaxabjh {
  fill: var(--svg-color--000, #000);
  d: path("M17.723 12.476a.58.58 0 0 1 .582-.583a.58.58 0 0 1 .518.85h-1.03a.53.53 0 0 1-.07-.267");
}

.kbhhadb_j {
  d: path("M14.793 3.756v.922a1.187 1.187 0 0 0 2.374 0v-.923a.2.2 0 0 0-.308-.169l-.252.16a.1.1 0 0 1-.134-.025l-.295-.401a.25.25 0 0 0-.403 0l-.292.4a.1.1 0 0 1-.135.026l-.247-.158a.2.2 0 0 0-.308.168");
}

.kdpeaetya {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
}

.kdz8adazd {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
  stop-opacity: 0;
}

.kn4vqfbmv {
  stop-color: var(--svg-color--c29b94, #C29B94);
  stop-opacity: 0;
}

.ko_hncw6z {
  stop-color: var(--svg-color--c29b94, #C29B94);
}

.kotk-bqfm {
  d: path("M8.797 4.266c-.625.257-1.356 1.025-.969 2.375s.526 1.802.547 1.859c.04.167.223.5.633.5h.39a.45.45 0 0 0 .301-.133c.142-.135 2.254-1.597 5.827-1.718c3.645.121 6.633 1.583 6.775 1.718a.45.45 0 0 0 .3.133h.391c.41 0 .593-.333.633-.5c.02-.057.16-.51.547-1.86s-.344-2.117-.969-2.374l-5.21-1.853a6 6 0 0 0-4.032.004z");
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lbq2vhbhw {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.369 12.429l-.78 1.937a.615.615 0 0 0 .594.797h.896c.42 0 .717-.404.594-.797l-.606-1.937c-.13-.43-.562-.43-.698 0");
}

.ldh_5l31c {
  d: path("m17.577 29.934l-.926-5.201a.15.15 0 0 0-.148-.124h-1.078a.15.15 0 0 0-.147.12l-1.025 5.205z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llr-3tqju {
  stop-color: var(--svg-color--b4888a, #B4888A);
}

.llwl8xbbe {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.829-4.12a.1.1 0 0 0-.076-.117l-1.316-.306z");
}

.ls327tu-e {
  d: path("m15.38 12.27l-.605 1.938a.614.614 0 0 0 .593.797h.896c.42 0 .717-.404.594-.797l-.606-1.937c-.13-.43-.735-.43-.871 0");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lwjbbq_rp {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
}

.m3xkgmb-t {
  d: path("m10.02 10.941l-.011-.349c.023-1.081.654-1.5.923-1.64l.059-.022l.058-.024A2.63 2.63 0 0 0 12.405 7.5l.093-.22a.3.3 0 0 1 .526-.059a4.4 4.4 0 0 0 3.635 1.907h3.67c.205 0 1.233.1 1.294 1.519l-.135 3.502c-.14 3.194-2.635 5.339-5.68 5.339s-5.538-2.145-5.679-5.339z");
}

.m5kfvc0eh {
  d: path("M10.498 13.907a1.224 1.224 0 1 0 0-2.448a1.224 1.224 0 0 0 0 2.448");
}

.m8dz_mblr {
  d: path("M9.442 8.703c.396.844 1.515 2.461 3.97 2.461h5.115c2.454 0 3.573-1.617 3.97-2.46c-2.254-1.05-5.29-1.423-6.528-1.477c-1.237.054-4.274.426-6.527 1.476");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfcet0q3v {
  stop-color: var(--svg-color--b28082, #B28082);
  stop-opacity: 0;
}

.mh0_pg5pw {
  stop-color: var(--svg-color--b37c95, #B37C95);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mtuo14bcx {
  stop-color: var(--svg-color--eabfac, #EABFAC);
  stop-opacity: 0;
}

.n-i72ubxb {
  d: path("M15.845 18.13h-.046c.114 0 .217 0 .33.012c-.09-.012-.193-.012-.284-.012");
}

.n3gabqbgv {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.541 11.148c.744 0 1.373.514 1.544 1.207a.312.312 0 0 1-.305.388h-2.543a.262.262 0 0 1-.258-.31a1.59 1.59 0 0 1 1.562-1.285");
}

.nbobwxzih {
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.829-4.12a.1.1 0 0 0-.076-.117l-1.316-.306z");
}

.nffjv6p6j {
  stop-color: var(--svg-color--daaaa2, #DAAAA2);
}

.ni0htxbur {
  stop-color: var(--svg-color--407ccf, #407CCF);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nlnhxpbkx {
  stop-color: var(--svg-color--4681d4, #4681D4);
  stop-opacity: 0;
}

.nx2bsjb_t {
  stop-color: var(--svg-color--4a88df, #4A88DF);
  stop-opacity: 0;
}

.nyhx0mbls {
  stop-color: var(--svg-color--c49371, #C49371);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oigr0yrty {
  d: path("M18.83 24.93a.5.5 0 0 1 .5-.5h1.812a.5.5 0 0 1 .5.5v1.726a1.406 1.406 0 1 1-2.813 0z");
}

.ojlr4zbcq {
  stop-color: var(--svg-color--ba8178, #BA8178);
  stop-opacity: 0;
}

.ojnx9kp9k {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
  stop-opacity: 0;
}

.ouv-nzxqj {
  cx: 13.02px;
  cy: 11.893px;
  rx: 0.444px;
  ry: 0.225px;
}

.p_hknfval {
  stop-color: var(--svg-color--81d0ff, #81D0FF);
}

.p32hh8bag {
  stop-color: var(--svg-color--a46c6b, #A46C6B);
  stop-opacity: 0;
}

.pctc2_emz {
  stop-color: var(--svg-color--daaaa2, #DAAAA2);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.q-4mmubff {
  stop-color: var(--svg-color--87ddff, #87DDFF);
}

.q3vx93ufn {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
}

.qgn4spb6l {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.843-4.153l1.387-.394z");
}

.qjgh28b1y {
  stop-color: var(--svg-color--189cf0, #189CF0);
}

.qk56hfspl {
  stop-color: var(--svg-color--4681d4, #4681D4);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qrocdccto {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M21.318 13.907a1.224 1.224 0 1 0 0-2.449a1.224 1.224 0 0 0 0 2.449");
}

.qt_mg48rg {
  stop-color: var(--svg-color--409ed2, #409ED2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_91d457c {
  stop-color: var(--svg-color--4389d1, #4389D1);
  stop-opacity: 0;
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r9aql0tfq {
  stop-color: var(--svg-color--30acff, #30ACFF);
  stop-opacity: 0;
}

.rvybbdrcw {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
  stop-opacity: 0;
}

.rxaby506o {
  stop-color: var(--svg-color--f2bf95, #F2BF95);
}

.s6yishbmu {
  stop-color: var(--svg-color--ebbfa8, #EBBFA8);
  stop-opacity: 0;
}

.s8arww3_h {
  d: path("M19.212 12.341a.96.96 0 0 0-.264-.527l-.296.325l.133.26z");
}

.sjzaf5e-a {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
  stop-opacity: 0;
}

.sw0blobad {
  fill-rule: evenodd;
  d: path("M21.92 8.962c-5.062-1.855-9.999-.764-11.82-.011a.775.775 0 0 1-.592-1.433c2.085-.861 7.432-2.031 12.945-.011a.775.775 0 1 1-.533 1.455");
}

.t2siy786u {
  d: path("M16.22 18.13c.286.012.582.035.878.057c-.296-.022-.58-.045-.877-.057");
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.t9xlhbbtl {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
}

.thtcysb5g {
  d: path("M8.055 29.934H3.862a12.15 12.15 0 0 1 4.193-8.309z");
}

.tp8jvfpml {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
  stop-opacity: 0;
}

.u9bpp-1oj {
  stop-color: var(--svg-color--f3d2a9, #F3D2A9);
}

.uik0qxugc {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.091 11.148c-.744 0-1.373.514-1.544 1.207a.312.312 0 0 0 .305.388h2.543a.262.262 0 0 0 .259-.31a1.6 1.6 0 0 0-1.563-1.285");
}

.upydt32_o {
  fill: var(--svg-color--3fb3ff, #3FB3FF);
  d: path("M3.862 29.934h24.276c-.466-6.297-5.723-11.26-12.138-11.26S4.328 23.638 3.862 29.934");
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vg5w9dbzr {
  stop-color: var(--svg-color--30acff, #30ACFF);
}

.vhpcois2a {
  stop-color: var(--svg-color--ffcd47, #FFCD47);
}

.vweyc3b2b {
  stop-color: var(--svg-color--b47f87, #B47F87);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wm9obhbbe {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.816 16.001a3.45 3.45 0 0 1-1.62-.393c-.16-.083-.332.101-.232.25a2.202 2.202 0 0 0 3.704 0c.1-.155-.071-.333-.232-.25c-.468.25-1.02.393-1.62.393Z");
}

.wt_jecb6v {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
}

.x04v_w04n {
  d: path("M18.305 11.459a1.017 1.017 0 0 1 .98 1.285h-1.964a1.02 1.02 0 0 1 .985-1.285");
}

.x1bufs-rn {
  stop-color: var(--svg-color--c49371, #C49371);
}

.xdpsjccue {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M10.498 13.907a1.224 1.224 0 1 0 0-2.448a1.224 1.224 0 0 0 0 2.448");
}

.xf9qqcbnz {
  stop-color: var(--svg-color--4eb9f4, #4EB9F4);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xpcksdqyw {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.118 12.034c.302-.532.762-.953 1.752-.953c.433 0 .851.12 1.223.42c.306.248.265.565.028.684l-.634.362c-.743-.24-1.564-.273-2.37-.513");
}

.xsp7-kwpz {
  stop-color: var(--svg-color--3c73d6, #3C73D6);
}

.xsu_qdbmh {
  stop-color: var(--svg-color--4188d4, #4188D4);
  stop-opacity: 0;
}

.xyqpj-b-m {
  stop-color: var(--svg-color--f2c4a4, #F2C4A4);
  stop-opacity: 0;
}

.y0fag01yz {
  d: path("M14.256 12.356c0-.328-.267-.548-.34-.614l-.328.318l.202.412z");
}

.y2ilnmbem {
  fill: var(--svg-color--297ecb, #297ECB);
  d: path("M14.74 3.8v.922a1.187 1.187 0 1 0 2.373 0v-.924a.2.2 0 0 0-.307-.168l-.253.16a.1.1 0 0 1-.134-.025l-.294-.402a.25.25 0 0 0-.404 0l-.292.401a.1.1 0 0 1-.134.026l-.248-.159a.2.2 0 0 0-.308.169");
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.ylhb00l1u {
  stop-color: var(--svg-color--4389d1, #4389D1);
}

.yvnwtvbdk {
  stop-color: var(--svg-color--3169c8, #3169C8);
}

.yvpnuvb4w {
  d: path("m15.38 12.136l-.605 1.938a.614.614 0 0 0 .593.797h.896c.42 0 .717-.405.594-.797l-.606-1.938c-.13-.429-.735-.429-.871 0");
}

.yvy6tz2sx {
  d: path("M23.945 29.934h4.193a12.15 12.15 0 0 0-4.193-8.309z");
}

.z_4nico_h {
  stop-color: var(--svg-color--7dc8fc, #7DC8FC);
  stop-opacity: 0;
}

.z0ryd6fmh {
  fill: var(--svg-color--000, #000);
  d: path("M13.91 12.476a.58.58 0 0 0-.583-.583a.58.58 0 0 0-.518.85h1.031a.6.6 0 0 0 .07-.267");
}

.z3n4zq94h {
  stop-color: var(--svg-color--ebbfa8, #EBBFA8);
}

.z6a5p4bqu {
  fill: var(--svg-color--247dbd, #247DBD);
  fill-rule: evenodd;
  d: path("M21.582 8.636c-4.687-1.717-9.257-.77-10.943-.072a.717.717 0 1 1-.548-1.326c1.93-.798 6.88-1.82 11.984.05a.717.717 0 1 1-.493 1.348");
}

.zanrk7_8f {
  stop-color: var(--svg-color--c2848d, #C2848D);
  stop-opacity: 0;
}

.zy2fe0b7g {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
