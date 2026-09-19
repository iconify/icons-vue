<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="upydt32_o"/><path fill="url(#i3b9cme)" class="ir5uabcyf"/><path fill="url(#iT6XAqe)" class="ir5uabcyf"/><path fill="url(#iTFqkvb)" class="ir5uabcyf"/><path fill="url(#i6dLLtb)" class="ir5uabcyf"/><g filter="url(#ie7P56d)"><path class="skgxszbhw"/></g><path fill="url(#iVk8ZRb)" class="thtcysb5g"/><path fill="url(#iySxojc)" class="thtcysb5g"/><path fill="url(#iBT0Egc)" class="yvy6tz2sx"/><path fill="url(#iSWq0Oc)" class="yvy6tz2sx"/><g filter="url(#iSGxHLd)"><path fill="url(#iPxdGmJ)" class="gfcus0k-b"/><path fill="url(#icUCMXd)" class="gfcus0k-b"/><path fill="url(#iDtHPwb)" class="gfcus0k-b"/><path fill="url(#ikLUynd)" class="gfcus0k-b"/></g><path fill="url(#iXh9ybH)" class="ckyg--8tq"/><path fill="url(#iaSWI7d)" class="ckyg--8tq"/><path fill="url(#ihSlXYc)" class="ckyg--8tq"/><g filter="url(#i5YkMFe)"><path class="g0x0s6b7k"/><path fill="url(#ie1yCCd)" class="zstiy-bhq"/></g><path fill="url(#iJ1vlub)" class="zstiy-bhq"/><g filter="url(#imE7HCc)"><path class="trkjkfbvt"/><path fill="url(#i4K7vYT)" class="jdcv0xbln"/><path fill="url(#i7KLMve)" class="jdcv0xbln"/></g><path fill="url(#i8sDatb)" class="jdcv0xbln"/><g filter="url(#ixLTgYd)"><path fill="url(#iKdlXfd)" class="frts9nbwi"/><path fill="url(#iCH0HXq)" class="frts9nbwi"/></g><g filter="url(#i6skxqd)"><path fill="url(#iF5yRae)" class="oigr0yrty"/></g><g filter="url(#iylVVJb)"><rect fill="url(#i8yzP5c)" class="f5rlg0klg"/></g><g filter="url(#iucc2dc)"><circle fill="url(#i3Ofu3F)" class="tqj3mfarw"/></g><g filter="url(#idzufbd)"><circle fill="url(#icamWdd)" class="ho6_1fbmc"/></g><g filter="url(#i5zzPge)"><circle fill="url(#iB83Rhc)" class="af47qnbed"/><circle fill="url(#iNEyoIe)" class="af47qnbed"/></g><g filter="url(#io5rfVd)"><circle class="dbvc72ptm"/><circle fill="url(#ijfJPUk)" class="bq6gubb9b"/><circle fill="url(#iAqD6cd)" class="bq6gubb9b"/></g><g filter="url(#iyfuoTx)"><path fill="url(#i2H4eIe)" class="ov-h6ob-c"/><path fill="url(#ivKMwSc)" class="ov-h6ob-c"/></g><path fill="url(#iKcvuud)" class="zjjs7ob2m"/><path fill="url(#i2IVVid)" class="zjjs7ob2m"/><path fill="url(#idQaddH)" class="zjjs7ob2m"/><path fill="url(#it49Lkd)" class="zjjs7ob2m"/><path fill="url(#iJM1X5b)" class="zjjs7ob2m"/><path fill="url(#iWU0rHc)" class="zjjs7ob2m"/><path fill="url(#iv7JTSb)" class="zjjs7ob2m"/><path fill="url(#ixk1LKe)" class="zjjs7ob2m"/><path fill="url(#i26CW0b)" class="zjjs7ob2m"/><path fill="url(#ihLsbPb)" class="zjjs7ob2m"/><g filter="url(#iELf5Gd)"><path class="nb81tigyx"/><path fill="url(#i6Pqvib)" class="g_o2jinne"/><path fill="url(#i126i5b)" class="g_o2jinne"/><path fill="url(#i9nbGub)" class="g_o2jinne"/><path fill="url(#iehZJde)" class="g_o2jinne"/></g><g filter="url(#iFNoajb)"><path class="oa5fw_b_b"/></g><g filter="url(#ixp6SDe)"><path class="su9fzspxv"/><path fill="url(#id9SRpb)" class="vso8dsb3q"/><path fill="url(#iLWDF0d)" class="vso8dsb3q"/><path fill="url(#i3eoxRm)" class="vso8dsb3q"/><path fill="url(#iPqgw3d)" class="vso8dsb3q"/></g><g filter="url(#iY3GzRd)"><path fill="url(#ieRMZ2c)" class="scrwmkq9r"/></g><path stroke="url(#iJwyBIx)" class="c9pwcc-uu"/><path class="rt_stohdk"/><path fill="url(#i1ILhSb)" class="li7kpk4xt"/><path class="qu35x-knk"/><g filter="url(#ivqPlNb)"><path class="gowg66sht"/><path fill="url(#ilKcVde)" class="ynvm6pbtp"/></g><g filter="url(#iDss9xd)"><path fill="url(#ivQtwBb)" class="bk88195vz"/></g><path class="vq_n339mu"/><path fill="url(#iSTq1Td)" class="ttmgj9qdq"/><path class="s77gt1vrd"/><g filter="url(#iDc4vtd)"><path fill="url(#irUHZ3V)" class="ivgddpb3u"/></g><g filter="url(#iYU6kAc)"><ellipse transform="rotate(-27.914 13.138 11.944)" class="e6frhkbcu"/><ellipse fill="url(#iNLO3Cc)" transform="rotate(-27.914 13.138 11.944)" class="lsv-gob5y"/></g><g filter="url(#iPZqXRy)"><path fill="url(#isLM7wb)" class="kotk-bqfm"/><path fill="url(#imyeZ8d)" class="kotk-bqfm"/></g><path fill="url(#iizJfPb)" class="kotk-bqfm"/><g filter="url(#iMv4dGd)"><path class="vbnpoccjx"/></g><g filter="url(#izlscge)"><path fill="url(#iagoo5c)" class="kbhhadb_j"/></g><g filter="url(#iZtybJH)"><path fill="url(#iIgw5Lc)" class="m8dz_mblr"/><path fill="url(#iTf5cKc)" class="m8dz_mblr"/></g><g filter="url(#iohoh6b)"><path clip-rule="evenodd" class="z6a5p4bqu"/></g><g filter="url(#iW5fHHc)"><path fill="url(#igpewSb)" clip-rule="evenodd" class="sw0blobad"/></g><path fill="url(#iiEONhS)" clip-rule="evenodd" class="sw0blobad"/><path fill="url(#i0rO5Pe)" clip-rule="evenodd" class="sw0blobad"/><defs><radialGradient id="i3b9cme" cx="0" cy="0" r="1" gradientTransform="matrix(.59372 6.27271 -11.9943 1.13527 13.662 18.032)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ewagz7_9h"/><stop offset="1" class="a8t42xt1y"/></radialGradient><radialGradient id="iT6XAqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 0 0 14.4101 8.099 29.934)" gradientUnits="userSpaceOnUse"><stop class="vg5w9dbzr"/><stop offset="1" class="r9aql0tfq"/></radialGradient><radialGradient id="iTFqkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -12.1562 24.005 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="bglf8cb8f"/><stop offset="1" class="f1vhuirkb"/></radialGradient><radialGradient id="iVk8ZRb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -6.93362 3.8209 .51663 6.443 29.934)" gradientUnits="userSpaceOnUse"><stop class="ff-z7nbub"/><stop offset="1" class="qt_mg48rg"/></radialGradient><radialGradient id="iySxojc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -13.7094 8.287 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="a2jurmb2n"/><stop offset="1" class="xsu_qdbmh"/></radialGradient><radialGradient id="iBT0Egc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 -8.02737 2.31779 -.47822 26.443 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="f69-7cs4d"/><stop offset="1" class="xf9qqcbnz"/></radialGradient><radialGradient id="iSWq0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36307 0 0 13.6894 23.945 29.71)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="qjgh28b1y"/><stop offset=".8" class="humbo4erb"/></radialGradient><radialGradient id="iPxdGmJ" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 3.525 14.988)scale(2.34396 3.58278)" gradientUnits="userSpaceOnUse"><stop class="ni0htxbur"/><stop offset="1" class="xsp7-kwpz"/></radialGradient><radialGradient id="icUCMXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 -1.10937 1.05865 1.5358 15.474 24.031)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nlnhxpbkx"/><stop offset="1" class="qk56hfspl"/></radialGradient><radialGradient id="iXh9ybH" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71487 -1.3158 0 15.915 25.22)" gradientUnits="userSpaceOnUse"><stop class="e9hbkmbux"/><stop offset="1" class="fqfyucbrl"/></radialGradient><radialGradient id="ie1yCCd" cx="0" cy="0" r="1" gradientTransform="matrix(.6593 -2.21967 2.48774 .73893 14.283 23.669)" gradientUnits="userSpaceOnUse"><stop class="zy2fe0b7g"/><stop offset="1" class="kdz8adazd"/></radialGradient><radialGradient id="iJ1vlub" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.49506 -2.22013 -.51048 14.005 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="cxc4ijbrr"/><stop offset="1" class="sjzaf5e-a"/></radialGradient><radialGradient id="i7KLMve" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .42188 -1.25086 1.38985 17.037 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="bzog60bkg"/><stop offset=".902" class="et8zn2bag"/></radialGradient><radialGradient id="i8sDatb" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 .875 -2.39996 2.31425 17.787 19.906)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="wt_jecb6v"/><stop offset="1" class="tp8jvfpml"/></radialGradient><radialGradient id="iKdlXfd" cx="0" cy="0" r="1" gradientTransform="rotate(148.065 5.885 12.705)scale(2.68809 2.30164)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="q5jcs2bvg"/><stop offset="1" class="vps2f2fmx"/></radialGradient><radialGradient id="iCH0HXq" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42188 .20312 -.04646 -.55397 15.349 20)" gradientUnits="userSpaceOnUse"><stop class="pkofl4buc"/><stop offset="1" class="nikdcj44z"/></radialGradient><radialGradient id="i3Ofu3F" cx="0" cy="0" r="1" gradientTransform="matrix(2.01634 0 0 3.52861 8.585 12.837)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iNEyoIe" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 30.182 -27.316)scale(1.17502 1.34113)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="ijfJPUk" cx="0" cy="0" r="1" gradientTransform="matrix(.94363 -1.7356 1.01585 .55231 21.387 13.78)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iAqD6cd" cx="0" cy="0" r="1" gradientTransform="matrix(.29792 .2949 -.38016 .38406 21.434 12.837)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="i2H4eIe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.09688 0 0 -10.3558 19.212 13.284)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="ivKMwSc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03295 3.22828 -2.71422 -1.70924 18.768 7.71)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="i2IVVid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.54524 11.5612 0 15.916 20.44)" gradientUnits="userSpaceOnUse"><stop offset=".007" class="jpkkobbrw"/><stop offset=".355" class="s77uqpbfc"/><stop offset="1" class="nzv4exikx"/></radialGradient><radialGradient id="idQaddH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.28591 1.65731 0 18.791 11.814)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="it49Lkd" cx="0" cy="0" r="1" gradientTransform="matrix(.00458 -1.22536 1.38878 .0052 13.255 11.867)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iJM1X5b" cx="0" cy="0" r="1" gradientTransform="matrix(-9.90827 .60064 -1.47368 -24.31027 19.94 14.39)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iWU0rHc" cx="0" cy="0" r="1" gradientTransform="matrix(3.94858 -3.26586 .95812 1.15841 8.017 10.224)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iv7JTSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27367 2.7966 -1.16342 -.11385 22.404 10.018)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="ixk1LKe" cx="0" cy="0" r="1" gradientTransform="rotate(-77.34 19.503 2.098)scale(1.59444 3.79644)" gradientUnits="userSpaceOnUse"><stop class="epekmz57g"/><stop offset="1" class="i-h1q0ber"/></radialGradient><radialGradient id="i26CW0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.34946 -1.64719 3.92354 -.8324 18.01 21.033)" gradientUnits="userSpaceOnUse"><stop class="epekmz57g"/><stop offset="1" class="i-h1q0ber"/></radialGradient><radialGradient id="ihLsbPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.22661 -5.38374 0 15.992 11.058)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="wj-baqbis"/><stop offset="1" class="ui6bdrbgt"/></radialGradient><radialGradient id="i6Pqvib" cx="0" cy="0" r="1" gradientTransform="matrix(.9167 -3.39715 1.63572 .44139 20.951 8.12)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="i126i5b" cx="0" cy="0" r="1" gradientTransform="matrix(4.39473 .40444 -.21746 2.36302 19.065 6.097)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="i9nbGub" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92937 -2.98805 0 15.959 2.955)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iehZJde" cx="0" cy="0" r="1" gradientTransform="matrix(3.53197 -2.58831 4.05504 5.53343 8.55 10.789)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iPqgw3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22624 -.72685 0 16.335 14.683)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="i1ILhSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03773 -1.2279 0 18.463 12.437)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="u5b_qpb1y"/><stop offset="1" class="n4wew7txz"/></radialGradient><radialGradient id="ilKcVde" cx="0" cy="0" r="1" gradientTransform="matrix(-.26641 -.3433 .47265 -.36679 18.2 12.15)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSTq1Td" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03778 -1.22796 0 13.45 12.437)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="u5b_qpb1y"/><stop offset="1" class="n4wew7txz"/></radialGradient><radialGradient id="iNLO3Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00889 -.56757 .68225 -.01068 13.12 12.305)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isLM7wb" cx="0" cy="0" r="1" gradientTransform="rotate(153.716 9.95 5.24)scale(8.88768 11.3119)" gradientUnits="userSpaceOnUse"><stop class="b5oikgndb"/><stop offset="1" class="aiodo62qb"/></radialGradient><radialGradient id="iizJfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56249 1.8125 -5.67441 -1.76097 20.88 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="lwjbbq_rp"/><stop offset="1" class="c0fdt7b4z"/></radialGradient><radialGradient id="iIgw5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.454 12.31 1.781)scale(8.75158 12.2726)" gradientUnits="userSpaceOnUse"><stop class="hg7hxmbra"/><stop offset="1" class="i8a3pvbms"/></radialGradient><radialGradient id="iTf5cKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33594 10.5987 0 15.97 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="e3kv8ccww"/><stop offset=".917" class="t9xlhbbtl"/></radialGradient><radialGradient id="iiEONhS" cx="0" cy="0" r="1" gradientTransform="rotate(101.822 7.538 11.83)scale(1.37287 11.6524)" gradientUnits="userSpaceOnUse"><stop class="q-4mmubff"/><stop offset="1" class="z_4nico_h"/></radialGradient><radialGradient id="i0rO5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(137.81 10.052 8.132)scale(2.38738 2.66614)" gradientUnits="userSpaceOnUse"><stop class="q3vx93ufn"/><stop offset="1" class="ojnx9kp9k"/></radialGradient><filter id="ie7P56d" width="7.365" height="6.01" x="12.146" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".25"/></filter><filter id="iSGxHLd" width="4.12" height="2.78" x="13.959" y="21.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/></filter><filter id="i5YkMFe" width="3.58" height="4.539" x="12.543" y="19.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/></filter><filter id="imE7HCc" width="3.6" height="4.539" x="15.879" y="19.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/></filter><filter id="ixLTgYd" width="4.352" height="2.805" x="13.739" y="19.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/></filter><filter id="i6skxqd" width="3.063" height="3.733" x="18.679" y="24.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2682" result="effect2_innerShadow_4002_2682"/></filter><filter id="iylVVJb" width="4.306" height="1.334" x="8.789" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2682" result="effect2_innerShadow_4002_2682"/></filter><filter id="iucc2dc" width="4.036" height="3.836" x="8.585" y="10.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/></filter><filter id="idzufbd" width="3.286" height="3.286" x="8.86" y="11.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".25"/></filter><filter id="i5zzPge" width="4.086" height="4.086" x="19.516" y="10.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/></filter><filter id="io5rfVd" width="3.286" height="3.286" x="19.791" y="11.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".25"/></filter><filter id="iyfuoTx" width="12.919" height="14.02" x="10.033" y="6.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2682" result="effect2_innerShadow_4002_2682"/></filter><filter id="iELf5Gd" width="14.479" height="9.742" x="8.719" y="2.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/></filter><filter id="iFNoajb" width="3.522" height="4.581" x="13.923" y="11.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".375"/></filter><filter id="ixp6SDe" width="2.656" height="3.581" x="14.631" y="11.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".125"/></filter><filter id="iY3GzRd" width="2.656" height="3.581" x="14.631" y="11.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".125"/></filter><filter id="ivqPlNb" width=".874" height=".77" x="17.634" y="11.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".05"/></filter><filter id="iDss9xd" width=".964" height=".99" x="18.614" y="11.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".1"/></filter><filter id="iDc4vtd" width="1.074" height="1.135" x="13.51" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".1"/></filter><filter id="iYU6kAc" width="1.019" height=".78" x="12.628" y="11.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".05"/></filter><filter id="iPZqXRy" width="16.56" height="6.934" x="7.72" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.537255 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/></filter><filter id="iMv4dGd" width="2.674" height="2.948" x="14.589" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".075"/></filter><filter id="izlscge" width="2.624" height="2.748" x="14.643" y="3.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2682" result="effect2_innerShadow_4002_2682"/></filter><filter id="iZtybJH" width="13.155" height="4.088" x="9.342" y="7.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.207843 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2682" result="effect2_innerShadow_4002_2682"/></filter><filter id="iohoh6b" width="13.899" height="3.448" x="9.147" y="5.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2682" stdDeviation=".25"/></filter><filter id="iW5fHHc" width="14.033" height="2.72" x="9.028" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2682"/></filter><linearGradient id="i6dLLtb" x1="7.926" x2="8.205" y1="28.477" y2="28.477" gradientUnits="userSpaceOnUse"><stop offset=".229" class="kdpeaetya"/><stop offset="1" class="rvybbdrcw"/></linearGradient><linearGradient id="iDtHPwb" x1="15.193" x2="15.498" y1="22.422" y2="22.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="ikLUynd" x1="16.404" x2="16.185" y1="22.258" y2="22.555" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="iaSWI7d" x1="17.411" x2="16.474" y1="27.875" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ahgk2rx2r"/><stop offset="1" class="nx2bsjb_t"/></linearGradient><linearGradient id="ihSlXYc" x1="14.677" x2="15.915" y1="27.11" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="yvnwtvbdk"/><stop offset="1" class="gd56libvg"/></linearGradient><linearGradient id="i4K7vYT" x1="18.787" x2="17.247" y1="22.422" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="bxeumjbad"/><stop offset="1" class="c8b-jsd8k"/></linearGradient><linearGradient id="iF5yRae" x1="21.325" x2="18.829" y1="26.246" y2="26.246" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="i8yzP5c" x1="13.095" x2="8.763" y1="26.863" y2="26.863" gradientUnits="userSpaceOnUse"><stop class="gxnbt7b-w"/><stop offset="1" class="vhpcois2a"/></linearGradient><linearGradient id="icamWdd" x1="10.504" x2="9.768" y1="13.157" y2="13.157" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iB83Rhc" x1="22.683" x2="21.742" y1="11.583" y2="14.497" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iKcvuud" x1="21.952" x2="19.003" y1="15.172" y2="15.172" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="id9SRpb" x1="14.966" x2="16.044" y1="14.042" y2="14.042" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iLWDF0d" x1="17.037" x2="15.859" y1="14.413" y2="14.396" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="i3eoxRm" x1="16.183" x2="16.183" y1="15.266" y2="14.607" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="ieRMZ2c" x1="15.959" x2="16.182" y1="12.089" y2="13.748" gradientUnits="userSpaceOnUse"><stop class="fvf8pe3kh"/><stop offset="1" class="ubdb19zve"/></linearGradient><linearGradient id="iJwyBIx" x1="14.767" x2="15.267" y1="17.121" y2="16.331" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="ivQtwBb" x1="19.356" x2="18.996" y1="12.116" y2="12.338" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irUHZ3V" x1="14.304" x2="13.944" y1="12.116" y2="12.338" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imyeZ8d" x1="7.318" x2="13.13" y1="7.656" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="ylhb00l1u"/><stop offset="1" class="r_91d457c"/></linearGradient><linearGradient id="iagoo5c" x1="16.899" x2="14.793" y1="4.541" y2="4.541" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="igpewSb" x1="10.974" x2="21.755" y1="7.7" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="ilj7ybc1n"/><stop offset="1" class="p_hknfval"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-police-officer-medium-dark" /></template>
<style>
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

.af47qnbed {
  cx: 21.434px;
  cy: 12.837px;
  r: 1.918px;
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ahgk2rx2r {
  stop-color: var(--svg-color--4a88df, #4A88DF);
}

.aiodo62qb {
  stop-color: var(--svg-color--328fdd, #328FDD);
}

.b5oikgndb {
  stop-color: var(--svg-color--48a8fb, #48A8FB);
}

.bglf8cb8f {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
}

.bk88195vz {
  d: path("M19.378 12.396a.96.96 0 0 0-.266-.532l-.298.328l.134.262z");
}

.bq6gubb9b {
  cx: 21.434px;
  cy: 12.837px;
  r: 1.143px;
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

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c8b-jsd8k {
  stop-color: var(--svg-color--75c1ff, #75C1FF);
  stop-opacity: 0;
}

.c9pwcc-uu {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.39 16.012a.225.225 0 0 0-.269.046a.21.21 0 0 0-.022.266c.393.597 1.08.994 1.86.994s1.467-.398 1.86-.994a.21.21 0 0 0-.023-.268a.23.23 0 0 0-.268-.044a3.4 3.4 0 0 1-1.57.371a3.4 3.4 0 0 1-1.568-.371Z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckyg--8tq {
  d: path("m17.577 29.934l-.927-5.201a.15.15 0 0 0-.147-.124h-1.078a.15.15 0 0 0-.147.12l-1.025 5.205z");
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cxc4ijbrr {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dbvc72ptm {
  cx: 21.434px;
  cy: 12.837px;
  r: 1.143px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.e3kv8ccww {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
  stop-opacity: 0;
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e6frhkbcu {
  cx: 13.138px;
  cy: 11.944px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.448px;
  ry: 0.227px;
}

.e9hbkmbux {
  stop-color: var(--svg-color--3f7cd5, #3F7CD5);
}

.epekmz57g {
  stop-color: var(--svg-color--774f85, #774F85);
}

.et8zn2bag {
  stop-color: var(--svg-color--639be0, #639BE0);
  stop-opacity: 0;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
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

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.ff-z7nbub {
  stop-color: var(--svg-color--3bafff, #3BAFFF);
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

.fvf8pe3kh {
  stop-color: var(--svg-color--6d414a, #6D414A);
}

.g_o2jinne {
  d: path("m21.496 5.394l.493.246c.863.429 1.356 1.41 1.171 2.45l-.678 3.494c-.06.36-.299.603-.657.612h-.02s.06-1.041.122-1.654c.05-.498-.037-.65-.493-1.103c-.246-.245-.431-.613-.431-.98v-.981c0-.306-.247-.552-.493-.613c-.74-.184-2.28-.49-4.5-.49c-2.218 0-3.759.306-4.499.49a.6.6 0 0 0-.492.613v.98c0 .368-.124.736-.432.981l-.185.184c-.246.184-.37.551-.37.858c.062.674.124 1.654.124 1.654q-.03 0-.057-.002a.73.73 0 0 1-.683-.61L8.738 8.03c-.123-.98.37-1.961 1.233-2.39l.493-.246c.308-.183.616-.428.924-.674l1.11-1.164c.678-.613 1.664-.797 2.527-.368a3.4 3.4 0 0 0 1.91 0c.925-.306 1.972-.06 2.712.613l.924.92c.247.306.555.49.925.673");
}

.g0x0s6b7k {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.gd56libvg {
  stop-color: var(--svg-color--3169c8, #3169C8);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gfcus0k-b {
  d: path("M16.749 24.47a.25.25 0 0 1-.224.139h-1.097a.25.25 0 0 1-.223-.139l-1.246-2.491h4.02z");
}

.gowg66sht {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.39 11.723c.073.097-.08.216-.254.346c-.173.13-.302.221-.375.123c-.073-.097.008-.282.182-.411c.174-.13.373-.156.447-.059");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gxnbt7b-w {
  stop-color: var(--svg-color--ffd04c, #FFD04C);
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hg3it7oev {
  stop-color: var(--svg-color--1b54be, #1B54BE);
  stop-opacity: 0;
}

.hg7hxmbra {
  stop-color: var(--svg-color--574a69, #574A69);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.ho6_1fbmc {
  cx: 10.504px;
  cy: 12.837px;
  r: 1.143px;
}

.humbo4erb {
  stop-color: var(--svg-color--189cf0, #189CF0);
  stop-opacity: 0;
}

.i-h1q0ber {
  stop-color: var(--svg-color--774f85, #774F85);
  stop-opacity: 0;
}

.i8a3pvbms {
  stop-color: var(--svg-color--46395b, #46395B);
}

.ilj7ybc1n {
  stop-color: var(--svg-color--73b8f6, #73B8F6);
}

.ir5uabcyf {
  d: path("M3.862 29.934h24.276c-.466-6.297-5.723-11.26-12.138-11.26S4.328 23.638 3.862 29.934");
}

.ivgddpb3u {
  d: path("M14.384 12.41c0-.33-.27-.552-.343-.619l-.33.32l.203.416z");
}

.j3cbwjknw {
  stop-color: var(--svg-color--ffd24b, #FFD24B);
}

.jdcv0xbln {
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.jo3nm0bcx {
  stop-color: var(--svg-color--ffd44c, #FFD44C);
}

.jpkkobbrw {
  stop-color: var(--svg-color--774772, #774772);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
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

.kotk-bqfm {
  d: path("M8.797 4.266c-.625.257-1.356 1.025-.969 2.375s.526 1.802.547 1.859c.04.167.223.5.633.5h.39a.45.45 0 0 0 .301-.133c.142-.135 2.254-1.597 5.827-1.718c3.645.121 6.633 1.583 6.775 1.718a.45.45 0 0 0 .3.133h.391c.41 0 .593-.333.633-.5c.02-.057.16-.51.547-1.86s-.344-2.117-.969-2.374l-5.21-1.853a6 6 0 0 0-4.032.004z");
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li7kpk4xt {
  d: path("M18.465 11.506a1.025 1.025 0 0 1 .988 1.295h-1.98a1.03 1.03 0 0 1 .993-1.295");
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lsv-gob5y {
  cx: 13.138px;
  cy: 11.944px;
  rx: 0.448px;
  ry: 0.227px;
}

.lwjbbq_rp {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m8dz_mblr {
  d: path("M9.442 8.703c.396.844 1.515 2.461 3.97 2.461h5.115c2.454 0 3.573-1.617 3.97-2.46c-2.254-1.05-5.29-1.423-6.528-1.477c-1.237.054-4.274.426-6.527 1.476");
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.n4wew7txz {
  stop-color: var(--svg-color--553830, #553830);
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nb81tigyx {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m21.496 5.394l.493.246c.863.429 1.356 1.41 1.171 2.45l-.678 3.494c-.06.36-.299.603-.657.612h-.02s.06-1.041.122-1.654c.05-.498-.037-.65-.493-1.103c-.246-.245-.431-.613-.431-.98v-.981c0-.306-.247-.552-.493-.613c-.74-.184-2.28-.49-4.5-.49c-2.218 0-3.759.306-4.499.49a.6.6 0 0 0-.492.613v.98c0 .368-.124.736-.432.981l-.185.184c-.246.184-.37.551-.37.858c.062.674.124 1.654.124 1.654q-.03 0-.057-.002a.73.73 0 0 1-.683-.61L8.738 8.03c-.123-.98.37-1.961 1.233-2.39l.493-.246c.308-.183.616-.428.924-.674l1.11-1.164c.678-.613 1.664-.797 2.527-.368a3.4 3.4 0 0 0 1.91 0c.925-.306 1.972-.06 2.712.613l.924.92c.247.306.555.49.925.673");
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.ni0htxbur {
  stop-color: var(--svg-color--407ccf, #407CCF);
}

.nikdcj44z {
  stop-color: var(--svg-color--704061, #704061);
  stop-opacity: 0;
}

.nlnhxpbkx {
  stop-color: var(--svg-color--4681d4, #4681D4);
  stop-opacity: 0;
}

.nx2bsjb_t {
  stop-color: var(--svg-color--4a88df, #4A88DF);
  stop-opacity: 0;
}

.nzv4exikx {
  stop-color: var(--svg-color--7b4a59, #7B4A59);
  stop-opacity: 0;
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.oa5fw_b_b {
  fill: var(--svg-color--71404a, #71404A);
  d: path("M15.643 12.697L14.7 14.65c-.117.402.164.803.56.803h.848c.397 0 .677-.408.56-.803l-.572-1.953c-.123-.433-.325-.433-.453 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oigr0yrty {
  d: path("M18.83 24.93a.5.5 0 0 1 .5-.5h1.812a.5.5 0 0 1 .5.5v1.726a1.406 1.406 0 1 1-2.813 0z");
}

.ojnx9kp9k {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
  stop-opacity: 0;
}

.ov-h6ob-c {
  d: path("m10.1 12.133l.056.002s-.062-.98-.123-1.655c0-.306.123-.674.37-.858l.184-.183c.308-.246.432-.613.432-.98v-.981c0-.307.184-.552.493-.613c.74-.184 2.28-.49 4.499-.49s3.76.306 4.499.49c.246.061.493.306.493.613v.98c0 .368.185.735.431.98c.577.405.541.627.493 1.104c-.061.612-.123 1.654-.123 1.654h.02l-.305 4.548c-.184 2.034-1.782 3.45-3.688 3.45h-3.689c-1.967 0-3.504-1.416-3.689-3.45z");
}

.p_hknfval {
  stop-color: var(--svg-color--81d0ff, #81D0FF);
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkofl4buc {
  stop-color: var(--svg-color--704061, #704061);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q-4mmubff {
  stop-color: var(--svg-color--87ddff, #87DDFF);
}

.q3vx93ufn {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
}

.q5jcs2bvg {
  stop-color: var(--svg-color--714d64, #714D64);
}

.qjgh28b1y {
  stop-color: var(--svg-color--189cf0, #189CF0);
}

.qk56hfspl {
  stop-color: var(--svg-color--4681d4, #4681D4);
}

.qt_mg48rg {
  stop-color: var(--svg-color--409ed2, #409ED2);
}

.qu35x-knk {
  fill: var(--svg-color--000, #000);
  d: path("M17.878 12.531c0-.326.26-.587.587-.587a.585.585 0 0 1 .522.857h-1.04a.53.53 0 0 1-.07-.27");
}

.r_91d457c {
  stop-color: var(--svg-color--4389d1, #4389D1);
  stop-opacity: 0;
}

.r9aql0tfq {
  stop-color: var(--svg-color--30acff, #30ACFF);
  stop-opacity: 0;
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rt_stohdk {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.703 11.193c.75 0 1.384.518 1.556 1.217a.315.315 0 0 1-.308.391h-2.563a.264.264 0 0 1-.26-.312a1.606 1.606 0 0 1 1.575-1.296");
}

.rvybbdrcw {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
  stop-opacity: 0;
}

.s77gt1vrd {
  fill: var(--svg-color--000, #000);
  d: path("M14.034 12.531a.585.585 0 0 0-.587-.587a.585.585 0 0 0-.522.857h1.04a.6.6 0 0 0 .07-.27");
}

.s77uqpbfc {
  stop-color: var(--svg-color--78455f, #78455F);
}

.scrwmkq9r {
  d: path("m15.52 12.413l-.61 1.953a.62.62 0 0 0 .597.804h.904a.62.62 0 0 0 .598-.804l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sjzaf5e-a {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
  stop-opacity: 0;
}

.skgxszbhw {
  fill: var(--svg-color--2389d6, #2389D6);
  d: path("m12.646 19.685l.763 3.8a.41.41 0 0 0 .662.242l.452-.364l.601 1.204c.04.078.12.128.208.128h1.021c.089 0 .17-.05.21-.13l.586-1.187l.437.349a.41.41 0 0 0 .661-.242l.764-3.8z");
}

.su9fzspxv {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.52 12.51l-.61 1.952a.62.62 0 0 0 .597.804h.904a.62.62 0 0 0 .598-.804l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.sw0blobad {
  fill-rule: evenodd;
  d: path("M21.92 8.962c-5.062-1.855-9.999-.764-11.82-.011a.775.775 0 0 1-.592-1.433c2.085-.861 7.432-2.031 12.945-.011a.775.775 0 1 1-.533 1.455");
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

.tqj3mfarw {
  cx: 10.504px;
  cy: 12.837px;
  r: 1.918px;
}

.trkjkfbvt {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.ttmgj9qdq {
  d: path("M13.447 11.505a1.025 1.025 0 0 0-.988 1.296h1.98a1 1 0 0 0 .038-.27a1.03 1.03 0 0 0-1.03-1.026");
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u5b_qpb1y {
  stop-color: var(--svg-color--734d45, #734D45);
}

.ubdb19zve {
  stop-color: var(--svg-color--6d414a, #6D414A);
  stop-opacity: 0;
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ui6bdrbgt {
  stop-color: var(--svg-color--653946, #653946);
  stop-opacity: 0;
}

.upydt32_o {
  fill: var(--svg-color--3fb3ff, #3FB3FF);
  d: path("M3.862 29.934h24.276c-.466-6.297-5.723-11.26-12.138-11.26S4.328 23.638 3.862 29.934");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.vbnpoccjx {
  fill: var(--svg-color--297ecb, #297ECB);
  d: path("M14.74 3.8v.922a1.187 1.187 0 1 0 2.373 0v-.924a.2.2 0 0 0-.307-.168l-.253.16a.1.1 0 0 1-.134-.025l-.294-.402a.25.25 0 0 0-.404 0l-.292.401a.1.1 0 0 1-.135.026l-.247-.159a.2.2 0 0 0-.308.169");
}

.vg5w9dbzr {
  stop-color: var(--svg-color--30acff, #30ACFF);
}

.vhpcois2a {
  stop-color: var(--svg-color--ffcd47, #FFCD47);
}

.vps2f2fmx {
  stop-color: var(--svg-color--653e51, #653E51);
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vq_n339mu {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.21 11.193c-.75 0-1.385.518-1.557 1.217c-.051.2.102.391.307.391h2.564a.263.263 0 0 0 .26-.312a1.61 1.61 0 0 0-1.575-1.296");
}

.vso8dsb3q {
  d: path("m15.52 12.51l-.61 1.952a.62.62 0 0 0 .597.804h.904a.62.62 0 0 0 .598-.804l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wj-baqbis {
  stop-color: var(--svg-color--653946, #653946);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wt_jecb6v {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
}

.xf9qqcbnz {
  stop-color: var(--svg-color--4eb9f4, #4EB9F4);
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xsp7-kwpz {
  stop-color: var(--svg-color--3c73d6, #3C73D6);
}

.xsu_qdbmh {
  stop-color: var(--svg-color--4188d4, #4188D4);
  stop-opacity: 0;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.ylhb00l1u {
  stop-color: var(--svg-color--4389d1, #4389D1);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ynvm6pbtp {
  d: path("M18.39 11.723c.073.097-.08.216-.254.346c-.173.13-.302.221-.375.123c-.073-.097.008-.282.182-.411c.174-.13.373-.156.447-.059");
}

.yvnwtvbdk {
  stop-color: var(--svg-color--3169c8, #3169C8);
}

.yvy6tz2sx {
  d: path("M23.945 29.934h4.193a12.15 12.15 0 0 0-4.193-8.309z");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_4nico_h {
  stop-color: var(--svg-color--7dc8fc, #7DC8FC);
  stop-opacity: 0;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z6a5p4bqu {
  fill: var(--svg-color--247dbd, #247DBD);
  fill-rule: evenodd;
  d: path("M21.582 8.636c-4.687-1.717-9.257-.77-10.943-.072a.717.717 0 1 1-.548-1.326c1.93-.798 6.88-1.82 11.984.05a.717.717 0 1 1-.493 1.348");
}

.zjjs7ob2m {
  d: path("M10.033 10.48c0-.306.123-.674.37-.858l.184-.183c.308-.246.432-.613.432-.98v-.981c0-.307.184-.552.493-.613c.74-.184 2.28-.49 4.499-.49s3.76.306 4.499.49c.246.061.493.306.493.613v.98c0 .368.185.735.431.98c.577.405.541.627.493 1.104c-.061.612-.123 1.654-.123 1.654h.02l-.305 4.548c-.184 2.034-1.782 3.45-3.688 3.45h-3.689c-1.967 0-3.504-1.416-3.689-3.45c-.16-2.087-.23-4.18-.42-6.264");
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zstiy-bhq {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.zy2fe0b7g {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
}

</style>
