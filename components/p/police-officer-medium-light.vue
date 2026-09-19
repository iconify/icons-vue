<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="upydt32_o"/><path fill="url(#i3b9cme)" class="ir5uabcyf"/><path fill="url(#iT6XAqe)" class="ir5uabcyf"/><path fill="url(#iTFqkvb)" class="ir5uabcyf"/><path fill="url(#i6dLLtb)" class="ir5uabcyf"/><g filter="url(#ibTmhNb)"><path class="skgxszbhw"/></g><path fill="url(#iVk8ZRb)" class="thtcysb5g"/><path fill="url(#iySxojc)" class="thtcysb5g"/><path fill="url(#iBT0Egc)" class="yvy6tz2sx"/><path fill="url(#iSWq0Oc)" class="yvy6tz2sx"/><g filter="url(#iKKBYqb)"><path fill="url(#iPxdGmJ)" class="gfcus0k-b"/><path fill="url(#iJSlXzd)" class="gfcus0k-b"/><path fill="url(#iJK0STd)" class="gfcus0k-b"/><path fill="url(#ikLUynd)" class="gfcus0k-b"/></g><path fill="url(#iXh9ybH)" class="ldh_5l31c"/><path fill="url(#i4gZH3d)" class="ldh_5l31c"/><path fill="url(#ihSlXYc)" class="ldh_5l31c"/><g filter="url(#iYqEyab)"><path class="g0x0s6b7k"/><path fill="url(#ie1yCCd)" class="zstiy-bhq"/></g><path fill="url(#iJ1vlub)" class="zstiy-bhq"/><g filter="url(#izLylbe)"><path class="fu5sdg_kf"/><path fill="url(#iNae8ve)" class="cjztvk1qv"/><path fill="url(#i4SYPYc)" class="cjztvk1qv"/></g><path fill="url(#iHY0HKb)" class="cjztvk1qv"/><g filter="url(#iDcBEhd)"><path fill="url(#iI6PXQi)" class="frts9nbwi"/><path fill="url(#iIGWG6j)" class="frts9nbwi"/></g><path class="wl5mbzbrp"/><path fill="url(#icfJeMc)" class="veo4_4wkp"/><path fill="url(#iHUlAWc)" class="vzjo7ybfn"/><path fill="url(#i797Jyq)" class="uvtwfy9zz"/><path fill="url(#idBxlgG)" class="sfneccb9i"/><path fill="url(#i0weWJc)" class="sfneccb9i"/><path fill="url(#idBxlgG)" class="sfneccb9i"/><path fill="url(#i0weWJc)" class="sfneccb9i"/><g filter="url(#iQB4R4R)"><path fill="url(#iZUxt2c)" class="q-bntt46s"/></g><path fill="url(#ibWoyzd)" class="q-bntt46s"/><path fill="url(#insuRKe)" class="q-bntt46s"/><path fill="url(#iT4rJRc)" class="q-bntt46s"/><path fill="url(#ivxEBCd)" class="q-bntt46s"/><path fill="url(#iCgfTud)" class="q-bntt46s"/><path fill="url(#iqBEYie)" class="q-bntt46s"/><path fill="url(#ioKbzwb)" class="q-bntt46s"/><path fill="url(#ivHR9Sc)" class="q-bntt46s"/><path fill="url(#i16X9Nd)" class="q-bntt46s"/><g filter="url(#iSAYTVC)"><path class="izdx-_k7u"/></g><g filter="url(#ioo4HOc)"><path fill="url(#ifofZDe)" class="x9j2v7ggw"/><path fill="url(#itiqRrW)" class="x9j2v7ggw"/><path fill="url(#ilvCPrb)" class="x9j2v7ggw"/><path fill="url(#iHtkdBd)" class="x9j2v7ggw"/></g><g filter="url(#iTM1oob)"><path fill="url(#iwF80bn)" class="dz89mb5_b"/></g><g filter="url(#iEDSKkf)"><path stroke="url(#i7L2YTb)" class="auh9h8cwq"/></g><path fill="url(#iWY3Dtb)" class="x8c121t2i"/><path class="u82v-g98u"/><path fill="url(#iuwqWzd)" class="drr8mnbiy"/><path class="mfb2epbjy"/><g filter="url(#ibF8Ede)"><path class="s61wqzbqn"/><path fill="url(#iHNn0se)" class="tsk7gib4f"/></g><g filter="url(#inITygb)"><path fill="url(#iNQvNKd)" class="pvp-tubaw"/></g><path class="hh5x-tu6v"/><path fill="url(#ijpPAzb)" class="zs271jbpx"/><path class="d66o4d3ge"/><g filter="url(#iz7rgwe)"><path fill="url(#iYQ1ykb)" class="ohy-4pb9x"/></g><g filter="url(#iMgTTYN)"><ellipse transform="rotate(-27.914 13.19 11.966)" class="pm0zl6-bw"/><ellipse fill="url(#iJwQlUn)" transform="rotate(-27.914 13.19 11.966)" class="ppv3oyeme"/></g><path fill="url(#i25xWMe)" class="mx2h91fbo"/><path fill="url(#im6Ytqd)" class="mx2h91fbo"/><path fill="url(#inFSh9d)" class="mx2h91fbo"/><path fill="url(#iXbg48b)" class="b-0nwd3vz"/><path fill="url(#iIrr6Qb)" class="b-0nwd3vz"/><g filter="url(#imUVZHc)"><path class="r5omuxwjo"/></g><g filter="url(#ipEodfc)"><path class="z7u0vobrp"/></g><g filter="url(#inrBshc)"><path fill="url(#isLM7wb)" class="kotk-bqfm"/><path fill="url(#imyeZ8d)" class="kotk-bqfm"/></g><path fill="url(#iizJfPb)" class="kotk-bqfm"/><g filter="url(#ixsnsVb)"><path class="vbnpoccjx"/></g><g filter="url(#i1c9uIc)"><path fill="url(#iagoo5c)" class="b-vc95bkj"/></g><g filter="url(#i3rIE1c)"><path fill="url(#iIgw5Lc)" class="mtkt99emo"/><path fill="url(#i1oZv1c)" class="mtkt99emo"/></g><g filter="url(#iAJMUzI)"><path clip-rule="evenodd" class="z6a5p4bqu"/></g><g filter="url(#iCXgoJd)"><path fill="url(#igpewSb)" clip-rule="evenodd" class="qr96pbbth"/></g><path fill="url(#iiEONhS)" clip-rule="evenodd" class="qr96pbbth"/><path fill="url(#i0rO5Pe)" clip-rule="evenodd" class="qr96pbbth"/><g filter="url(#iGapEqH)"><path fill="url(#iF5yRae)" class="oigr0yrty"/></g><g filter="url(#iPMwSPc)"><rect fill="url(#i8yzP5c)" class="f5rlg0klg"/></g><defs><radialGradient id="i3b9cme" cx="0" cy="0" r="1" gradientTransform="matrix(.59372 6.27271 -11.9943 1.13527 13.662 18.032)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ewagz7_9h"/><stop offset="1" class="a8t42xt1y"/></radialGradient><radialGradient id="iT6XAqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 0 0 14.4101 8.099 29.934)" gradientUnits="userSpaceOnUse"><stop class="vg5w9dbzr"/><stop offset="1" class="r9aql0tfq"/></radialGradient><radialGradient id="iTFqkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -12.1562 24.005 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="bglf8cb8f"/><stop offset="1" class="f1vhuirkb"/></radialGradient><radialGradient id="iVk8ZRb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -6.93362 3.8209 .51663 6.443 29.934)" gradientUnits="userSpaceOnUse"><stop class="ff-z7nbub"/><stop offset="1" class="qt_mg48rg"/></radialGradient><radialGradient id="iySxojc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -13.7094 8.287 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="a2jurmb2n"/><stop offset="1" class="xsu_qdbmh"/></radialGradient><radialGradient id="iBT0Egc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 -8.02737 2.31779 -.47822 26.443 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="f69-7cs4d"/><stop offset="1" class="xf9qqcbnz"/></radialGradient><radialGradient id="iSWq0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36307 0 0 13.6894 23.945 29.71)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="qjgh28b1y"/><stop offset=".8" class="humbo4erb"/></radialGradient><radialGradient id="iPxdGmJ" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 3.525 14.988)scale(2.34396 3.58278)" gradientUnits="userSpaceOnUse"><stop class="ni0htxbur"/><stop offset="1" class="xsp7-kwpz"/></radialGradient><radialGradient id="iJSlXzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 -1.10937 1.05865 1.5358 15.473 24.032)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nlnhxpbkx"/><stop offset="1" class="qk56hfspl"/></radialGradient><radialGradient id="iXh9ybH" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71487 -1.3158 0 15.915 25.22)" gradientUnits="userSpaceOnUse"><stop class="e9hbkmbux"/><stop offset="1" class="fqfyucbrl"/></radialGradient><radialGradient id="ie1yCCd" cx="0" cy="0" r="1" gradientTransform="matrix(.6593 -2.21967 2.48774 .73893 14.283 23.669)" gradientUnits="userSpaceOnUse"><stop class="zy2fe0b7g"/><stop offset="1" class="kdz8adazd"/></radialGradient><radialGradient id="iJ1vlub" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.49506 -2.22013 -.51048 14.005 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="cxc4ijbrr"/><stop offset="1" class="sjzaf5e-a"/></radialGradient><radialGradient id="i4SYPYc" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .42188 -1.25086 1.38985 17.036 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="bzog60bkg"/><stop offset=".902" class="et8zn2bag"/></radialGradient><radialGradient id="iHY0HKb" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 .875 -2.39996 2.31425 17.786 19.906)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="wt_jecb6v"/><stop offset="1" class="tp8jvfpml"/></radialGradient><radialGradient id="iI6PXQi" cx="0" cy="0" r="1" gradientTransform="rotate(148.065 5.885 12.705)scale(2.68809 2.30164)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="xmkjq1brc"/><stop offset="1" class="qooaqh4_d"/></radialGradient><radialGradient id="iIGWG6j" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42188 .20312 -.04646 -.55397 15.349 20)" gradientUnits="userSpaceOnUse"><stop class="of_6980ch"/><stop offset="1" class="ad6u3u09p"/></radialGradient><radialGradient id="icfJeMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.18023 -1.0785 3.46644 3.79344 9.068 10.914)" gradientUnits="userSpaceOnUse"><stop class="z_i15q2zj"/><stop offset=".794" class="tc6a80wmm"/></radialGradient><radialGradient id="iHUlAWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3201 -1.41424 2.39503 -2.23559 23.29 10.914)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="ejmeisu5i"/><stop offset="1" class="py-05368u"/></radialGradient><radialGradient id="i797Jyq" cx="0" cy="0" r="1" gradientTransform="matrix(-.69806 4.04904 -4.80994 -.82924 22.254 14.014)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="idBxlgG" cx="0" cy="0" r="1" gradientTransform="matrix(1.45932 3.07225 -1.39648 .66333 9.644 14.338)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="i0weWJc" cx="0" cy="0" r="1" gradientTransform="matrix(.2054 1.3674 -1.1995 .18018 10.562 14.104)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iZUxt2c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.98895 0 0 -10.5944 19.216 13.125)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="insuRKe" cx="0" cy="0" r="1" gradientTransform="scale(16.0612 14.473)rotate(90 .29 .709)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="a9torj7vm"/><stop offset=".988" class="rwuy40buq"/></radialGradient><radialGradient id="iT4rJRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53612 1.90095 0 18.803 11.842)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ivxEBCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.06651 -1.26404 1.37557 -.07238 13.436 11.685)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iCgfTud" cx="0" cy="0" r="1" gradientTransform="matrix(1.38251 0 0 7.02699 10.409 13.566)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iqBEYie" cx="0" cy="0" r="1" gradientTransform="matrix(2.99544 -4.18593 .94812 .67847 9.295 9.687)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="ioKbzwb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.259 14.955 2.631)scale(12.0555 13.2796)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="ivHR9Sc" cx="0" cy="0" r="1" gradientTransform="matrix(2.34258 .82567 -.49531 1.4053 18.243 6.96)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="i16X9Nd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.0625 -6.15103 0 16.054 10.464)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="pmx6s8bth"/><stop offset="1" class="c9az5fbdm"/></radialGradient><radialGradient id="i7L2YTb" cx="0" cy="0" r="1" gradientTransform="matrix(.3977 -.70962 2.06505 1.15734 14.71 16.893)" gradientUnits="userSpaceOnUse"><stop class="cd9sm8kim"/><stop offset="1" class="ysf-mvunt"/></radialGradient><radialGradient id="iWY3Dtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82566 3.32186 0 16 17.18)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iuwqWzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92944 -1.47837 0 18.5 12.076)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iHNn0se" cx="0" cy="0" r="1" gradientTransform="matrix(-.26568 -.34237 .47136 -.36578 18.238 12.172)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijpPAzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92948 -1.47845 0 13.5 12.076)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iJwQlUn" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.654 -.32)scale(.56608 .68046)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="im6Ytqd" cx="0" cy="0" r="1" gradientTransform="matrix(.72006 2.56987 -2.45185 .687 21.29 12.092)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="inFSh9d" cx="0" cy="0" r="1" gradientTransform="matrix(.90247 -1.2385 1.0381 .75645 21.703 12.716)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iIrr6Qb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.91887 -.28062 .27587 -1.88642 10.369 12.829)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="isLM7wb" cx="0" cy="0" r="1" gradientTransform="rotate(153.716 9.95 5.24)scale(8.88768 11.3119)" gradientUnits="userSpaceOnUse"><stop class="b5oikgndb"/><stop offset="1" class="aiodo62qb"/></radialGradient><radialGradient id="iizJfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56249 1.8125 -5.67441 -1.76097 20.88 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="lwjbbq_rp"/><stop offset="1" class="c0fdt7b4z"/></radialGradient><radialGradient id="iIgw5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.454 12.31 1.781)scale(8.75158 12.2726)" gradientUnits="userSpaceOnUse"><stop class="hg7hxmbra"/><stop offset="1" class="i8a3pvbms"/></radialGradient><radialGradient id="i1oZv1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33594 10.5987 0 15.969 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="e3kv8ccww"/><stop offset=".917" class="t9xlhbbtl"/></radialGradient><radialGradient id="iiEONhS" cx="0" cy="0" r="1" gradientTransform="rotate(101.822 7.538 11.83)scale(1.37287 11.6524)" gradientUnits="userSpaceOnUse"><stop class="q-4mmubff"/><stop offset="1" class="z_4nico_h"/></radialGradient><radialGradient id="i0rO5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(137.81 10.052 8.132)scale(2.38738 2.66614)" gradientUnits="userSpaceOnUse"><stop class="q3vx93ufn"/><stop offset="1" class="ojnx9kp9k"/></radialGradient><filter id="ibTmhNb" width="7.365" height="6.01" x="12.146" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".25"/></filter><filter id="iKKBYqb" width="4.12" height="2.78" x="13.959" y="21.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/></filter><filter id="iYqEyab" width="3.58" height="4.539" x="12.543" y="19.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/></filter><filter id="izLylbe" width="3.6" height="4.539" x="15.878" y="19.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/></filter><filter id="iDcBEhd" width="4.352" height="2.805" x="13.739" y="19.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.431373 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/></filter><filter id="iQB4R4R" width="12.458" height="14.338" x="10.2" y="6.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2686" result="effect2_innerShadow_4002_2686"/></filter><filter id="iSAYTVC" width="4.01" height="5.235" x="13.687" y="11.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".5"/></filter><filter id="ioo4HOc" width="2.351" height="3.522" x="14.825" y="11.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.537255 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/><feGaussianBlur result="effect2_foregroundBlur_4002_2686" stdDeviation=".05"/></filter><filter id="iTM1oob" width="2.351" height="3.522" x="14.825" y="11.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".05"/></filter><filter id="iEDSKkf" width="4.187" height="1.729" x="13.906" y="15.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".05"/></filter><filter id="ibF8Ede" width=".872" height=".769" x="17.673" y="11.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".05"/></filter><filter id="inITygb" width=".963" height=".988" x="18.65" y="11.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".1"/></filter><filter id="iz7rgwe" width="1.072" height="1.133" x="13.56" y="11.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".1"/></filter><filter id="iMgTTYN" width="1.017" height=".778" x="12.681" y="11.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".05"/></filter><filter id="imUVZHc" width="1.45" height="2.653" x="9.125" y="11.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".125"/></filter><filter id="ipEodfc" width="1.584" height="2.68" x="21.434" y="11.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".125"/></filter><filter id="inrBshc" width="16.56" height="6.934" x="7.72" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.537255 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/></filter><filter id="ixsnsVb" width="2.674" height="2.948" x="14.589" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".075"/></filter><filter id="i1c9uIc" width="2.624" height="2.748" x="14.643" y="3.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2686" result="effect2_innerShadow_4002_2686"/></filter><filter id="i3rIE1c" width="13.155" height="4.088" x="9.342" y="7.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.207843 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2686" result="effect2_innerShadow_4002_2686"/></filter><filter id="iAJMUzI" width="13.899" height="3.448" x="9.147" y="5.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2686" stdDeviation=".25"/></filter><filter id="iCXgoJd" width="14.033" height="2.72" x="9.028" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/></filter><filter id="iGapEqH" width="3.063" height="3.733" x="18.679" y="24.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2686" result="effect2_innerShadow_4002_2686"/></filter><filter id="iPMwSPc" width="4.306" height="1.334" x="8.789" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2686"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2686" result="effect2_innerShadow_4002_2686"/></filter><linearGradient id="i6dLLtb" x1="7.926" x2="8.205" y1="28.477" y2="28.477" gradientUnits="userSpaceOnUse"><stop offset=".229" class="kdpeaetya"/><stop offset="1" class="rvybbdrcw"/></linearGradient><linearGradient id="iJK0STd" x1="15.193" x2="15.497" y1="22.422" y2="22.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="ikLUynd" x1="16.404" x2="16.185" y1="22.258" y2="22.555" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="i4gZH3d" x1="17.412" x2="16.474" y1="27.875" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ahgk2rx2r"/><stop offset="1" class="nx2bsjb_t"/></linearGradient><linearGradient id="ihSlXYc" x1="14.677" x2="15.915" y1="27.11" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="yvnwtvbdk"/><stop offset="1" class="gd56libvg"/></linearGradient><linearGradient id="iNae8ve" x1="18.786" x2="17.247" y1="22.422" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="bxeumjbad"/><stop offset="1" class="c8b-jsd8k"/></linearGradient><linearGradient id="ibWoyzd" x1="21.908" x2="16.922" y1="15.056" y2="15.056" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="ifofZDe" x1="16" x2="16.979" y1="14.075" y2="14.075" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="itiqRrW" x1="14.771" x2="16.002" y1="13.897" y2="13.965" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ilvCPrb" x1="16" x2="16" y1="14.532" y2="15.508" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iHtkdBd" x1="16" x2="16" y1="11.957" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iwF80bn" x1="15.887" x2="16.106" y1="11.887" y2="13.23" gradientUnits="userSpaceOnUse"><stop class="fnob3ccdo"/><stop offset="1" class="jcvvgynwi"/></linearGradient><linearGradient id="iNQvNKd" x1="19.391" x2="19.032" y1="12.138" y2="12.359" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYQ1ykb" x1="14.352" x2="13.993" y1="12.138" y2="12.359" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i25xWMe" x1="23.373" x2="21.991" y1="12.169" y2="14.662" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iXbg48b" x1="9.299" x2="10.969" y1="12.975" y2="12.829" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="imyeZ8d" x1="7.318" x2="13.13" y1="7.656" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="ylhb00l1u"/><stop offset="1" class="r_91d457c"/></linearGradient><linearGradient id="iagoo5c" x1="16.899" x2="14.793" y1="4.541" y2="4.541" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="igpewSb" x1="10.974" x2="21.755" y1="7.7" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="ilj7ybc1n"/><stop offset="1" class="p_hknfval"/></linearGradient><linearGradient id="iF5yRae" x1="21.325" x2="18.829" y1="26.246" y2="26.246" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="i8yzP5c" x1="13.095" x2="8.763" y1="26.863" y2="26.863" gradientUnits="userSpaceOnUse"><stop class="gxnbt7b-w"/><stop offset="1" class="vhpcois2a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:police-officer-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a2jurmb2n {
  stop-color: var(--svg-color--3183ce, #3183CE);
}

.a565onb9e {
  stop-color: var(--svg-color--33488b, #33488B);
}

.a8t42xt1y {
  stop-color: var(--svg-color--36a5fc, #36A5FC);
  stop-opacity: 0;
}

.a9torj7vm {
  stop-color: var(--svg-color--c7898e, #C7898E);
  stop-opacity: 0;
}

.ad6u3u09p {
  stop-color: var(--svg-color--af798d, #AF798D);
  stop-opacity: 0;
}

.ahgk2rx2r {
  stop-color: var(--svg-color--4a88df, #4A88DF);
}

.aiodo62qb {
  stop-color: var(--svg-color--328fdd, #328FDD);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.auh9h8cwq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.448 16.001h-.001a.25.25 0 0 0-.298.051a.23.23 0 0 0-.025.297A2.24 2.24 0 0 0 16 17.351c.787 0 1.48-.4 1.876-1.002a.234.234 0 0 0-.026-.3a.25.25 0 0 0-.297-.048A3.35 3.35 0 0 1 16 16.37c-.57 0-1.104-.134-1.553-.368Z");
}

.b-0nwd3vz {
  d: path("M10.21 10.996a1.844 1.844 0 0 0 .159 3.666a89 89 0 0 1-.159-3.666");
}

.b-vc95bkj {
  d: path("M14.793 3.756v.922a1.187 1.187 0 0 0 2.374 0v-.923a.2.2 0 0 0-.308-.169l-.252.16a.1.1 0 0 1-.134-.025l-.295-.401a.25.25 0 0 0-.404 0l-.29.4a.1.1 0 0 1-.136.026l-.247-.158a.2.2 0 0 0-.308.168");
}

.b5oikgndb {
  stop-color: var(--svg-color--48a8fb, #48A8FB);
}

.bglf8cb8f {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
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

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.c9az5fbdm {
  stop-color: var(--svg-color--a56c6a, #A56C6A);
  stop-opacity: 0;
}

.cd9sm8kim {
  stop-color: var(--svg-color--e3aba2, #E3ABA2);
}

.cjztvk1qv {
  d: path("M15.878 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cxc4ijbrr {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
}

.d66o4d3ge {
  fill: var(--svg-color--000, #000);
  d: path("M14.084 12.552a.583.583 0 0 0-.586-.586a.583.583 0 0 0-.52.855h1.036a.6.6 0 0 0 .07-.27");
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.drr8mnbiy {
  d: path("M18.502 11.53a1.022 1.022 0 0 1 .985 1.291h-1.975a1.026 1.026 0 0 1 .99-1.292");
}

.dz89mb5_b {
  d: path("m15.562 12.237l-.609 2.106c-.124.433.174.867.597.867h.9c.423 0 .721-.44.597-.867l-.609-2.106c-.13-.466-.74-.466-.876 0");
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e3kv8ccww {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
  stop-opacity: 0;
}

.e9hbkmbux {
  stop-color: var(--svg-color--3f7cd5, #3F7CD5);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ejmeisu5i {
  stop-color: var(--svg-color--f9d7a5, #F9D7A5);
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

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.ff-z7nbub {
  stop-color: var(--svg-color--3bafff, #3BAFFF);
}

.fnob3ccdo {
  stop-color: var(--svg-color--bc8477, #BC8477);
}

.fqfyucbrl {
  stop-color: var(--svg-color--3872d8, #3872D8);
}

.frts9nbwi {
  d: path("M13.74 19.832c.21.57.812 1.582 2.206 2.223c1.454-.75 1.934-1.653 2.145-2.223l-2.145-.332z");
}

.ft5dv1b6b {
  fill: none;
}

.fu5sdg_kf {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M15.878 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.g0x0s6b7k {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gd56libvg {
  stop-color: var(--svg-color--3169c8, #3169C8);
  stop-opacity: 0;
}

.gfcus0k-b {
  d: path("M16.749 24.47a.25.25 0 0 1-.224.139h-1.097a.25.25 0 0 1-.223-.139l-1.246-2.491h4.02z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxnbt7b-w {
  stop-color: var(--svg-color--ffd04c, #FFD04C);
}

.hg3it7oev {
  stop-color: var(--svg-color--1b54be, #1B54BE);
  stop-opacity: 0;
}

.hg7hxmbra {
  stop-color: var(--svg-color--574a69, #574A69);
}

.hh5x-tu6v {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.261 11.218a1.6 1.6 0 0 0-1.552 1.213c-.051.2.102.39.306.39h2.557a.264.264 0 0 0 .26-.311a1.605 1.605 0 0 0-1.571-1.292");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.humbo4erb {
  stop-color: var(--svg-color--189cf0, #189CF0);
  stop-opacity: 0;
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i8a3pvbms {
  stop-color: var(--svg-color--46395b, #46395B);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.ilj7ybc1n {
  stop-color: var(--svg-color--73b8f6, #73B8F6);
}

.ir5uabcyf {
  d: path("M3.862 29.934h24.276c-.466-6.297-5.723-11.26-12.138-11.26S4.328 23.638 3.862 29.934");
}

.izdx-_k7u {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.507 12.74l-.793 1.897c-.116.433.162.867.557.867h.842c.395 0 .674-.44.557-.867l-.569-2.106c-.121-.466-.467-.257-.594.21");
}

.j3cbwjknw {
  stop-color: var(--svg-color--ffd24b, #FFD24B);
}

.jcvvgynwi {
  stop-color: var(--svg-color--bc8477, #BC8477);
  stop-opacity: 0;
}

.jo3nm0bcx {
  stop-color: var(--svg-color--ffd44c, #FFD44C);
}

.kdpeaetya {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
}

.kdz8adazd {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
  stop-opacity: 0;
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kotk-bqfm {
  d: path("M8.797 4.266c-.625.257-1.356 1.025-.969 2.375s.526 1.802.547 1.859c.04.167.223.5.633.5h.39a.45.45 0 0 0 .301-.133c.142-.135 2.254-1.597 5.827-1.718c3.645.121 6.633 1.583 6.775 1.718a.45.45 0 0 0 .3.133h.391c.41 0 .593-.333.633-.5c.02-.057.16-.51.547-1.86s-.344-2.117-.969-2.374l-5.21-1.853a6 6 0 0 0-4.032.004z");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.ldh_5l31c {
  d: path("m17.577 29.934l-.926-5.201a.15.15 0 0 0-.148-.124h-1.078a.15.15 0 0 0-.147.12l-1.025 5.205z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwjbbq_rp {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfb2epbjy {
  fill: var(--svg-color--000, #000);
  d: path("M17.917 12.552c0-.325.26-.586.585-.586a.583.583 0 0 1 .52.855h-1.036a.53.53 0 0 1-.07-.27");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mtkt99emo {
  d: path("M9.442 8.703c.396.844 1.515 2.461 3.97 2.461h5.115c2.454 0 3.573-1.617 3.97-2.46c-2.254-1.05-5.291-1.423-6.528-1.477c-1.237.054-4.274.426-6.527 1.476");
}

.mx2h91fbo {
  d: path("M21.638 14.662q.115-1.829.212-3.656a1.844 1.844 0 0 1-.212 3.656");
}

.ni0htxbur {
  stop-color: var(--svg-color--407ccf, #407CCF);
}

.nlnhxpbkx {
  stop-color: var(--svg-color--4681d4, #4681D4);
  stop-opacity: 0;
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nx2bsjb_t {
  stop-color: var(--svg-color--4a88df, #4A88DF);
  stop-opacity: 0;
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_6980ch {
  stop-color: var(--svg-color--af798d, #AF798D);
}

.ohy-4pb9x {
  d: path("M14.432 12.432c0-.33-.269-.551-.341-.617l-.33.319l.203.414z");
}

.oigr0yrty {
  d: path("M18.83 24.93a.5.5 0 0 1 .5-.5h1.812a.5.5 0 0 1 .5.5v1.726a1.406 1.406 0 1 1-2.813 0z");
}

.ojnx9kp9k {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
  stop-opacity: 0;
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.p_hknfval {
  stop-color: var(--svg-color--81d0ff, #81D0FF);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm0zl6-bw {
  cx: 13.19px;
  cy: 11.966px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.446px;
  ry: 0.226px;
}

.pmx6s8bth {
  stop-color: var(--svg-color--a56c6a, #A56C6A);
}

.ppv3oyeme {
  cx: 13.19px;
  cy: 11.966px;
  rx: 0.446px;
  ry: 0.226px;
}

.pvp-tubaw {
  d: path("M19.413 12.417a.96.96 0 0 0-.265-.53l-.298.327l.134.261z");
}

.py-05368u {
  stop-color: var(--svg-color--dfb698, #DFB698);
}

.q-4mmubff {
  stop-color: var(--svg-color--87ddff, #87DDFF);
}

.q-bntt46s {
  d: path("M10.473 16.293a4.486 4.486 0 0 0 4.451 3.902h2.161a4.486 4.486 0 0 0 4.452-3.902c.135-2.158.27-4.307.371-6.464a1.66 1.66 0 0 0-1.58-1.64h-1.604a2.78 2.78 0 0 1-2.533-1.654a.76.76 0 0 0-.705-.479h-1.459c-2.114 0-3.827 1.733-3.827 3.871c0 2.132.133 4.229.273 6.366");
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q3vx93ufn {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qjgh28b1y {
  stop-color: var(--svg-color--189cf0, #189CF0);
}

.qk56hfspl {
  stop-color: var(--svg-color--4681d4, #4681D4);
}

.qooaqh4_d {
  stop-color: var(--svg-color--a97980, #A97980);
}

.qr96pbbth {
  fill-rule: evenodd;
  d: path("M21.92 8.962c-5.062-1.855-10-.764-11.82-.011a.775.775 0 0 1-.593-1.433c2.085-.861 7.433-2.031 12.946-.011a.775.775 0 1 1-.533 1.455");
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

.r5omuxwjo {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.23 11.753a1.095 1.095 0 0 0 .095 2.153a89 89 0 0 1-.096-2.153");
}

.r9aql0tfq {
  stop-color: var(--svg-color--30acff, #30ACFF);
  stop-opacity: 0;
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rvybbdrcw {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
  stop-opacity: 0;
}

.rwuy40buq {
  stop-color: var(--svg-color--b37a98, #B37A98);
}

.s61wqzbqn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.427 11.746c.073.097-.08.216-.253.345c-.173.13-.301.22-.374.123s.008-.28.181-.41c.174-.13.373-.156.446-.058");
}

.sfneccb9i {
  d: path("M10.43 14.557a1.9 1.9 0 0 1-1.035-.353v1.066a2.49 2.49 0 0 0 1.536 2.313a4.7 4.7 0 0 1-.396-1.352z");
}

.sjzaf5e-a {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
  stop-opacity: 0;
}

.skgxszbhw {
  fill: var(--svg-color--2389d6, #2389D6);
  d: path("m12.646 19.685l.763 3.8a.41.41 0 0 0 .662.242l.452-.364l.601 1.204c.04.078.12.128.208.128h1.021c.089 0 .17-.05.21-.13l.586-1.187l.437.349a.41.41 0 0 0 .661-.242l.764-3.8z");
}

.t9xlhbbtl {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
}

.tc6a80wmm {
  stop-color: var(--svg-color--d2a08c, #D2A08C);
}

.thtcysb5g {
  d: path("M8.055 29.934H3.862a12.15 12.15 0 0 1 4.193-8.309z");
}

.tp8jvfpml {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tsk7gib4f {
  d: path("M18.427 11.746c.073.097-.08.216-.253.345c-.173.13-.301.22-.374.123s.008-.28.181-.41c.174-.13.373-.156.446-.058");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u82v-g98u {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.74 11.218a1.6 1.6 0 0 1 1.551 1.213c.051.2-.102.39-.306.39h-2.556a.264.264 0 0 1-.26-.31a1.6 1.6 0 0 1 1.57-1.293");
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.upydt32_o {
  fill: var(--svg-color--3fb3ff, #3FB3FF);
  d: path("M3.862 29.934h24.276c-.466-6.297-5.723-11.26-12.138-11.26S4.328 23.638 3.862 29.934");
}

.uvtwfy9zz {
  d: path("M21.57 14.557a1.9 1.9 0 0 0 1.035-.353v1.066a2.49 2.49 0 0 1-1.536 2.313a4.7 4.7 0 0 0 .396-1.352z");
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vbnpoccjx {
  fill: var(--svg-color--297ecb, #297ECB);
  d: path("M14.74 3.8v.922a1.187 1.187 0 1 0 2.373 0v-.924a.2.2 0 0 0-.307-.168l-.253.16a.1.1 0 0 1-.134-.025l-.294-.402a.25.25 0 0 0-.404 0l-.292.401a.1.1 0 0 1-.135.026l-.247-.159a.2.2 0 0 0-.308.169");
}

.veo4_4wkp {
  d: path("M9.02 9.797c-.153-.45-.262-.89-.31-1.117h1.79v3.273H9.219v-1.195c0-.356-.074-.59-.2-.961");
}

.vg5w9dbzr {
  stop-color: var(--svg-color--30acff, #30ACFF);
}

.vhpcois2a {
  stop-color: var(--svg-color--ffcd47, #FFCD47);
}

.vzjo7ybfn {
  d: path("M22.809 9.836c.168-.39.394-.809.48-1.156h-1.945v3.273h1.281v-1.195c-.013-.17.041-.59.184-.922");
}

.wl5mbzbrp {
  stroke: var(--svg-color--d37034, #D37034);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-627px, 0.627px);
  d: path("M12.08 10.069s.77-.59 1.9-.46m5.94.46s-.77-.59-1.9-.46");
}

.wt_jecb6v {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x8c121t2i {
  d: path("M16 16.444a3.44 3.44 0 0 1-1.587-.376c-.157-.08-.326.097-.227.24a2.17 2.17 0 0 0 1.814.968c.762 0 1.43-.387 1.814-.969c.099-.148-.07-.32-.227-.24c-.46.24-1 .377-1.587.377");
}

.x9j2v7ggw {
  d: path("m15.562 12.307l-.609 2.106c-.124.433.174.866.597.866h.9c.423 0 .721-.44.597-.866l-.609-2.106c-.13-.467-.74-.467-.876 0");
}

.xf9qqcbnz {
  stop-color: var(--svg-color--4eb9f4, #4EB9F4);
}

.xmkjq1brc {
  stop-color: var(--svg-color--b58893, #B58893);
}

.xsp7-kwpz {
  stop-color: var(--svg-color--3c73d6, #3C73D6);
}

.xsu_qdbmh {
  stop-color: var(--svg-color--4188d4, #4188D4);
  stop-opacity: 0;
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ylhb00l1u {
  stop-color: var(--svg-color--4389d1, #4389D1);
}

.ysf-mvunt {
  stop-color: var(--svg-color--e3aba2, #E3ABA2);
  stop-opacity: 0;
}

.yvnwtvbdk {
  stop-color: var(--svg-color--3169c8, #3169C8);
}

.yvy6tz2sx {
  d: path("M23.945 29.934h4.193a12.15 12.15 0 0 0-4.193-8.309z");
}

.z_4nico_h {
  stop-color: var(--svg-color--7dc8fc, #7DC8FC);
  stop-opacity: 0;
}

.z_i15q2zj {
  stop-color: var(--svg-color--f6c498, #F6C498);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z6a5p4bqu {
  fill: var(--svg-color--247dbd, #247DBD);
  fill-rule: evenodd;
  d: path("M21.582 8.636c-4.687-1.717-9.257-.77-10.943-.072a.717.717 0 1 1-.548-1.326c1.93-.798 6.88-1.82 11.984.05a.717.717 0 1 1-.493 1.348");
}

.z7u0vobrp {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M21.684 13.916q.067-1.09.127-2.18a1.095 1.095 0 0 1-.127 2.18");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zs271jbpx {
  d: path("M13.498 11.53a1.022 1.022 0 0 0-.985 1.291h1.975q.036-.13.037-.27a1.03 1.03 0 0 0-1.027-1.022");
}

.zstiy-bhq {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.zy2fe0b7g {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
}

</style>
