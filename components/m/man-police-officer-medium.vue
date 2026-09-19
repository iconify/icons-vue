<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="dee3snbxe"/><path fill="url(#i3b9cme)" class="g-3ft7k9f"/><path fill="url(#iT6XAqe)" class="g-3ft7k9f"/><path fill="url(#iTFqkvb)" class="g-3ft7k9f"/><path fill="url(#i6dLLtb)" class="g-3ft7k9f"/><g filter="url(#iaPqK6b)"><path class="w4srnfb7y"/></g><path fill="url(#iVk8ZRb)" class="thtcysb5g"/><path fill="url(#iySxojc)" class="thtcysb5g"/><path fill="url(#iBT0Egc)" class="yvy6tz2sx"/><path fill="url(#iSWq0Oc)" class="yvy6tz2sx"/><g filter="url(#iiKxoXb)"><path fill="url(#iPxdGmJ)" class="gfcus0k-b"/><path fill="url(#iJSlXzd)" class="gfcus0k-b"/><path fill="url(#iDtHPwb)" class="gfcus0k-b"/><path fill="url(#ikLUynd)" class="gfcus0k-b"/></g><path fill="url(#iOoOjsw)" class="htxp2lohr"/><path fill="url(#iaSWI7d)" class="htxp2lohr"/><path fill="url(#ihSlXYc)" class="htxp2lohr"/><g filter="url(#i5eARGl)"><path class="g0x0s6b7k"/><path fill="url(#ie1yCCd)" class="zstiy-bhq"/></g><path fill="url(#iJ1vlub)" class="zstiy-bhq"/><g filter="url(#iqBKCFb)"><path class="trkjkfbvt"/><path fill="url(#i4K7vYT)" class="jdcv0xbln"/><path fill="url(#i7KLMve)" class="jdcv0xbln"/></g><path fill="url(#ix6vz4b)" class="jdcv0xbln"/><g filter="url(#i6nRSub)"><path fill="url(#iCAKTMe)" class="vnlonib2h"/><path fill="url(#iRh2DQe)" class="vnlonib2h"/></g><g filter="url(#iQl2ANd)"><path fill="url(#iF5yRae)" class="g3qn2hbkl"/></g><g filter="url(#ide8xSc)"><rect fill="url(#iySt08c)" class="f5rlg0klg"/></g><g filter="url(#itE4x7b)"><circle fill="url(#ivkPIEd)" class="etvc25zce"/></g><circle fill="url(#icVX3qf)" class="etvc25zce"/><g filter="url(#iEztiWb)"><circle fill="url(#ib7qiqb)" class="y_n28597o"/></g><g filter="url(#iBymR0c)"><circle fill="url(#ipFVJud)" class="hkek06bnn"/><circle fill="url(#ihw7szX)" class="hkek06bnn"/></g><g filter="url(#iaFvYxc)"><circle class="x9phhgbra"/><circle fill="url(#i49uFld)" class="mrrnlab-m"/><circle fill="url(#i2guKtc)" class="mrrnlab-m"/></g><g filter="url(#iMWRhmb)"><path fill="url(#iDIj8Sd)" class="magncybxl"/><path fill="url(#iixg4FG)" class="magncybxl"/></g><path fill="url(#iQ7U1Fd)" class="meixgrb4k"/><path fill="url(#iWqo50c)" class="meixgrb4k"/><path fill="url(#i7kqKNd)" class="meixgrb4k"/><path fill="url(#iP1Vsue)" class="meixgrb4k"/><path fill="url(#iZH76pb)" class="meixgrb4k"/><path fill="url(#iexApNe)" class="meixgrb4k"/><path fill="url(#i7sw1ae)" class="meixgrb4k"/><path fill="url(#isumTVb)" class="meixgrb4k"/><path fill="url(#ikertxd)" class="meixgrb4k"/><g filter="url(#ihCzJic)"><path class="hvd61e78c"/><path fill="url(#ikqi9hV)" class="iimpokbga"/><path fill="url(#iVO6Iwc)" class="iimpokbga"/><path fill="url(#inBLIzd)" class="iimpokbga"/><path fill="url(#ip4la0c)" class="iimpokbga"/></g><g filter="url(#iEC1Shw)"><path class="n1x1y9b1p"/></g><g filter="url(#i8FWhjb)"><path class="zh5wbhzns"/><path fill="url(#iMF6pid)" class="cse72pbcy"/><path fill="url(#ikOvyJe)" class="cse72pbcy"/><path fill="url(#iPfG0jb)" class="cse72pbcy"/><path fill="url(#iE2MyWc)" class="cse72pbcy"/></g><g filter="url(#iE6d9kw)"><path fill="url(#iIKoPOb)" class="gytvam_id"/></g><path stroke="url(#ihLDAdd)" class="bqqn4kb-w"/><path class="cq3w4r4ov"/><path fill="url(#imk3Swe)" class="ju6dckb-b"/><path class="g13pasyql"/><g filter="url(#iolG1Rx)"><path class="b7nyl9bqo"/><path fill="url(#iqoe4vb)" class="jrhkttjal"/></g><g filter="url(#idWjyrd)"><path fill="url(#ijKognd)" class="k-my16b7i"/></g><path class="fagndgtuo"/><path fill="url(#iIVL9ud)" class="tvq6re52s"/><path class="nh6zrzb2s"/><g filter="url(#i48EHJe)"><path fill="url(#iSb3qTd)" class="zp2_bjbgn"/></g><g filter="url(#iMpYGFd)"><ellipse transform="rotate(-27.914 13.138 11.96)" class="x0d9392gq"/><ellipse fill="url(#ic9geNe)" transform="rotate(-27.914 13.138 11.96)" class="piqrmm5sr"/></g><g filter="url(#iAx9kOb)"><path fill="url(#isLM7wb)" class="j2ao_sb9l"/><path fill="url(#i945GOe)" class="j2ao_sb9l"/></g><path fill="url(#iizJfPb)" class="j2ao_sb9l"/><g filter="url(#ijs5Afn)"><path class="trw5-7ral"/></g><g filter="url(#iGWkeVb)"><path fill="url(#iBrxMjb)" class="nta8ypj0m"/></g><g filter="url(#i65nuZc)"><path fill="url(#iIgw5Lc)" class="m8dz_mblr"/><path fill="url(#iTf5cKc)" class="m8dz_mblr"/></g><g filter="url(#irnVhwt)"><path clip-rule="evenodd" class="ts35s1bpk"/></g><g filter="url(#iHDgqMc)"><path fill="url(#igpewSb)" clip-rule="evenodd" class="qfni0kjsa"/></g><path fill="url(#iiEONhS)" clip-rule="evenodd" class="qfni0kjsa"/><path fill="url(#i0rO5Pe)" clip-rule="evenodd" class="qfni0kjsa"/><defs><radialGradient id="i3b9cme" cx="0" cy="0" r="1" gradientTransform="matrix(.59372 6.27271 -11.9943 1.13527 13.662 18.032)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ewagz7_9h"/><stop offset="1" class="a8t42xt1y"/></radialGradient><radialGradient id="iT6XAqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 0 0 14.4101 8.099 29.934)" gradientUnits="userSpaceOnUse"><stop class="vg5w9dbzr"/><stop offset="1" class="r9aql0tfq"/></radialGradient><radialGradient id="iTFqkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -12.1562 24.005 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="bglf8cb8f"/><stop offset="1" class="f1vhuirkb"/></radialGradient><radialGradient id="iVk8ZRb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -6.93362 3.8209 .51663 6.443 29.934)" gradientUnits="userSpaceOnUse"><stop class="ff-z7nbub"/><stop offset="1" class="qt_mg48rg"/></radialGradient><radialGradient id="iySxojc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -13.7094 8.287 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="a2jurmb2n"/><stop offset="1" class="xsu_qdbmh"/></radialGradient><radialGradient id="iBT0Egc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 -8.02737 2.31779 -.47822 26.443 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="f69-7cs4d"/><stop offset="1" class="xf9qqcbnz"/></radialGradient><radialGradient id="iSWq0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36307 0 0 13.6894 23.945 29.71)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="qjgh28b1y"/><stop offset=".8" class="humbo4erb"/></radialGradient><radialGradient id="iPxdGmJ" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 3.525 14.988)scale(2.34396 3.58278)" gradientUnits="userSpaceOnUse"><stop class="ni0htxbur"/><stop offset="1" class="xsp7-kwpz"/></radialGradient><radialGradient id="iJSlXzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 -1.10937 1.05865 1.5358 15.473 24.032)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nlnhxpbkx"/><stop offset="1" class="qk56hfspl"/></radialGradient><radialGradient id="iOoOjsw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71487 -1.3158 0 15.915 25.219)" gradientUnits="userSpaceOnUse"><stop class="e9hbkmbux"/><stop offset="1" class="fqfyucbrl"/></radialGradient><radialGradient id="ie1yCCd" cx="0" cy="0" r="1" gradientTransform="matrix(.6593 -2.21967 2.48774 .73893 14.283 23.669)" gradientUnits="userSpaceOnUse"><stop class="zy2fe0b7g"/><stop offset="1" class="kdz8adazd"/></radialGradient><radialGradient id="iJ1vlub" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.49506 -2.22013 -.51048 14.005 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="cxc4ijbrr"/><stop offset="1" class="sjzaf5e-a"/></radialGradient><radialGradient id="i7KLMve" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .42188 -1.25086 1.38985 17.037 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="bzog60bkg"/><stop offset=".902" class="et8zn2bag"/></radialGradient><radialGradient id="ix6vz4b" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 .875 -2.39996 2.31425 17.787 19.907)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="wt_jecb6v"/><stop offset="1" class="tp8jvfpml"/></radialGradient><radialGradient id="iCAKTMe" cx="0" cy="0" r="1" gradientTransform="rotate(148.065 5.885 12.705)scale(2.68809 2.30164)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="t8aw4mbyz"/><stop offset="1" class="a991r1brt"/></radialGradient><radialGradient id="iRh2DQe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42188 .20312 -.04646 -.55397 15.349 20)" gradientUnits="userSpaceOnUse"><stop class="c8ock4brc"/><stop offset="1" class="edm992bfq"/></radialGradient><radialGradient id="ivkPIEd" cx="0" cy="0" r="1" gradientTransform="matrix(2.01634 0 0 3.52861 8.585 12.853)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="icVX3qf" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 9.098 4.65)scale(1.9036)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="ihw7szX" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 30.207 -27.308)scale(1.17502 1.34113)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="i49uFld" cx="0" cy="0" r="1" gradientTransform="matrix(.94363 -1.7356 1.01585 .55231 21.387 13.797)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="i2guKtc" cx="0" cy="0" r="1" gradientTransform="matrix(.29792 .2949 -.38016 .38406 21.434 12.853)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iDIj8Sd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.48715 0 0 -9.32016 19.212 13.3)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iixg4FG" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03295 3.22828 -2.71422 -1.70923 18.768 7.725)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iWqo50c" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.8524 -11.9472 0 16.59 6.738)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="u3zrqkbyl"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="i7kqKNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.28591 1.65731 0 18.791 11.83)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iP1Vsue" cx="0" cy="0" r="1" gradientTransform="matrix(.00458 -1.22536 1.38878 .0052 13.255 11.882)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iZH76pb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.90826 .60063 -1.47368 -24.31027 19.94 14.407)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iexApNe" cx="0" cy="0" r="1" gradientTransform="matrix(3.94858 -3.26586 .95812 1.15841 8.016 10.24)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="i7sw1ae" cx="0" cy="0" r="1" gradientTransform="matrix(-.27367 2.7966 -1.16342 -.11385 22.404 10.034)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="isumTVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .976 -1.95134 0 13.353 12.746)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="ikertxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.17191 -6.87163 0 15.125 10.129)" gradientUnits="userSpaceOnUse"><stop offset=".404" class="re303qbql"/><stop offset="1" class="x0r_jb-wm"/></radialGradient><radialGradient id="ikqi9hV" cx="0" cy="0" r="1" gradientTransform="matrix(.9167 -3.39715 1.25977 .33994 20.951 8.135)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iVO6Iwc" cx="0" cy="0" r="1" gradientTransform="matrix(4.39473 .40444 -.21746 2.36302 19.065 6.113)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="inBLIzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92937 -2.98805 0 15.959 2.97)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="ip4la0c" cx="0" cy="0" r="1" gradientTransform="matrix(3.53197 -2.58831 4.05504 5.53343 8.55 10.804)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iE2MyWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22624 -.72685 0 16.335 14.7)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="imk3Swe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03773 -1.2279 0 18.463 12.453)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="u5b_qpb1y"/><stop offset="1" class="n4wew7txz"/></radialGradient><radialGradient id="iqoe4vb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26641 -.3433 .47265 -.36679 18.2 12.166)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIVL9ud" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03778 -1.22796 0 13.45 12.453)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="u5b_qpb1y"/><stop offset="1" class="n4wew7txz"/></radialGradient><radialGradient id="ic9geNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00889 -.56757 .68224 -.01068 13.12 12.32)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isLM7wb" cx="0" cy="0" r="1" gradientTransform="rotate(153.716 9.95 5.24)scale(8.88768 11.3119)" gradientUnits="userSpaceOnUse"><stop class="b5oikgndb"/><stop offset="1" class="aiodo62qb"/></radialGradient><radialGradient id="iizJfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56249 1.8125 -5.67441 -1.76097 20.88 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="lwjbbq_rp"/><stop offset="1" class="c0fdt7b4z"/></radialGradient><radialGradient id="iIgw5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.454 12.31 1.781)scale(8.75158 12.2726)" gradientUnits="userSpaceOnUse"><stop class="hg7hxmbra"/><stop offset="1" class="i8a3pvbms"/></radialGradient><radialGradient id="iTf5cKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33594 10.5987 0 15.97 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="e3kv8ccww"/><stop offset=".917" class="t9xlhbbtl"/></radialGradient><radialGradient id="iiEONhS" cx="0" cy="0" r="1" gradientTransform="rotate(101.822 7.538 11.83)scale(1.37287 11.6524)" gradientUnits="userSpaceOnUse"><stop class="q-4mmubff"/><stop offset="1" class="z_4nico_h"/></radialGradient><radialGradient id="i0rO5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(137.81 10.052 8.132)scale(2.38738 2.66614)" gradientUnits="userSpaceOnUse"><stop class="q3vx93ufn"/><stop offset="1" class="ojnx9kp9k"/></radialGradient><filter id="iaPqK6b" width="7.365" height="6.01" x="12.146" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".25"/></filter><filter id="iiKxoXb" width="4.12" height="2.78" x="13.959" y="21.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/></filter><filter id="i5eARGl" width="3.58" height="4.539" x="12.543" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/></filter><filter id="iqBKCFb" width="3.6" height="4.539" x="15.879" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/></filter><filter id="i6nRSub" width="4.352" height="2.805" x="13.739" y="19.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.278431 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/></filter><filter id="iQl2ANd" width="3.063" height="3.733" x="18.679" y="24.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2685" result="effect2_innerShadow_4002_2685"/></filter><filter id="ide8xSc" width="4.306" height="1.334" x="8.789" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2685" result="effect2_innerShadow_4002_2685"/></filter><filter id="itE4x7b" width="4.036" height="3.836" x="8.585" y="10.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/></filter><filter id="iEztiWb" width="3.286" height="3.286" x="8.86" y="11.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".25"/></filter><filter id="iBymR0c" width="4.086" height="4.086" x="19.516" y="10.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/></filter><filter id="iaFvYxc" width="3.286" height="3.286" x="19.791" y="11.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".25"/></filter><filter id="iMWRhmb" width="12.919" height="13.92" x="10.032" y="6.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2685" result="effect2_innerShadow_4002_2685"/></filter><filter id="ihCzJic" width="14.479" height="9.742" x="8.719" y="2.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/></filter><filter id="iEC1Shw" width="3.522" height="4.581" x="13.923" y="11.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".375"/></filter><filter id="i8FWhjb" width="2.656" height="3.581" x="14.631" y="11.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".125"/></filter><filter id="iE6d9kw" width="2.656" height="3.581" x="14.631" y="11.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".125"/></filter><filter id="iolG1Rx" width=".874" height=".77" x="17.634" y="11.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".05"/></filter><filter id="idWjyrd" width=".964" height=".99" x="18.614" y="11.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".1"/></filter><filter id="i48EHJe" width="1.074" height="1.135" x="13.51" y="11.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".1"/></filter><filter id="iMpYGFd" width="1.019" height=".78" x="12.628" y="11.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".05"/></filter><filter id="iAx9kOb" width="16.56" height="6.934" x="7.72" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.537255 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/></filter><filter id="ijs5Afn" width="2.674" height="2.948" x="14.589" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".075"/></filter><filter id="iGWkeVb" width="2.624" height="2.748" x="14.643" y="3.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2685" result="effect2_innerShadow_4002_2685"/></filter><filter id="i65nuZc" width="13.155" height="4.088" x="9.342" y="7.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.207843 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2685" result="effect2_innerShadow_4002_2685"/></filter><filter id="irnVhwt" width="13.899" height="3.448" x="9.147" y="5.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2685" stdDeviation=".25"/></filter><filter id="iHDgqMc" width="14.033" height="2.72" x="9.028" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2685"/></filter><linearGradient id="i6dLLtb" x1="7.926" x2="8.205" y1="28.477" y2="28.477" gradientUnits="userSpaceOnUse"><stop offset=".229" class="kdpeaetya"/><stop offset="1" class="rvybbdrcw"/></linearGradient><linearGradient id="iDtHPwb" x1="15.193" x2="15.498" y1="22.422" y2="22.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="ikLUynd" x1="16.404" x2="16.185" y1="22.258" y2="22.555" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="iaSWI7d" x1="17.411" x2="16.474" y1="27.875" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ahgk2rx2r"/><stop offset="1" class="nx2bsjb_t"/></linearGradient><linearGradient id="ihSlXYc" x1="14.677" x2="15.915" y1="27.11" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="yvnwtvbdk"/><stop offset="1" class="gd56libvg"/></linearGradient><linearGradient id="i4K7vYT" x1="18.787" x2="17.247" y1="22.422" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="bxeumjbad"/><stop offset="1" class="c8b-jsd8k"/></linearGradient><linearGradient id="iF5yRae" x1="21.325" x2="18.829" y1="26.246" y2="26.246" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="iySt08c" x1="13.095" x2="8.763" y1="26.864" y2="26.864" gradientUnits="userSpaceOnUse"><stop class="gxnbt7b-w"/><stop offset="1" class="vhpcois2a"/></linearGradient><linearGradient id="ib7qiqb" x1="10.504" x2="9.768" y1="13.173" y2="13.173" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="ipFVJud" x1="22.683" x2="21.742" y1="11.599" y2="14.513" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iQ7U1Fd" x1="21.952" x2="19.002" y1="15.188" y2="15.188" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iMF6pid" x1="14.966" x2="16.044" y1="14.058" y2="14.058" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="ikOvyJe" x1="17.037" x2="15.859" y1="14.429" y2="14.412" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iPfG0jb" x1="16.183" x2="16.183" y1="15.282" y2="14.623" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iIKoPOb" x1="15.959" x2="16.089" y1="12.068" y2="13.412" gradientUnits="userSpaceOnUse"><stop class="lo1rr9b0y"/><stop offset="1" class="yz7s41bfz"/></linearGradient><linearGradient id="ihLDAdd" x1="14.768" x2="15.267" y1="17.137" y2="16.347" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ijKognd" x1="19.356" x2="18.996" y1="12.131" y2="12.353" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSb3qTd" x1="14.304" x2="13.943" y1="12.131" y2="12.354" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i945GOe" x1="7.318" x2="13.13" y1="7.657" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="ylhb00l1u"/><stop offset="1" class="r_91d457c"/></linearGradient><linearGradient id="iBrxMjb" x1="16.899" x2="14.793" y1="4.542" y2="4.542" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="igpewSb" x1="10.974" x2="21.755" y1="7.7" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="ilj7ybc1n"/><stop offset="1" class="p_hknfval"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-police-officer-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
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

.a991r1brt {
  stop-color: var(--svg-color--8b5d71, #8B5D71);
}

.ahgk2rx2r {
  stop-color: var(--svg-color--4a88df, #4A88DF);
}

.aiodo62qb {
  stop-color: var(--svg-color--328fdd, #328FDD);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b5oikgndb {
  stop-color: var(--svg-color--48a8fb, #48A8FB);
}

.b7nyl9bqo {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.39 11.738c.072.098-.08.217-.254.347c-.173.13-.302.22-.375.123c-.073-.098.008-.282.182-.412c.173-.13.373-.156.446-.058");
}

.bglf8cb8f {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
}

.bqqn4kb-w {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.39 16.028a.23.23 0 0 0-.269.046a.21.21 0 0 0-.022.266c.393.596 1.08.994 1.86.994s1.467-.398 1.86-.994a.21.21 0 0 0-.023-.268a.23.23 0 0 0-.268-.045a3.4 3.4 0 0 1-1.569.372a3.4 3.4 0 0 1-1.568-.371Z");
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bxeumjbad {
  stop-color: var(--svg-color--8be8ff, #8BE8FF);
}

.bzog60bkg {
  stop-color: var(--svg-color--639be0, #639BE0);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c0fdt7b4z {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
  stop-opacity: 0;
}

.c8b-jsd8k {
  stop-color: var(--svg-color--75c1ff, #75C1FF);
  stop-opacity: 0;
}

.c8ock4brc {
  stop-color: var(--svg-color--8e5879, #8E5879);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cq3w4r4ov {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.703 11.21c.75 0 1.384.516 1.556 1.215a.315.315 0 0 1-.308.392h-2.563a.264.264 0 0 1-.26-.312a1.606 1.606 0 0 1 1.575-1.296");
}

.cse72pbcy {
  d: path("m15.52 12.525l-.61 1.953a.62.62 0 0 0 .597.804h.904a.62.62 0 0 0 .598-.804l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cxc4ijbrr {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dee3snbxe {
  fill: var(--svg-color--3fb3ff, #3FB3FF);
  d: path("M3.862 29.934h24.276c-.466-6.296-5.723-11.26-12.138-11.26S4.328 23.639 3.862 29.935");
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.e3kv8ccww {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
  stop-opacity: 0;
}

.e9hbkmbux {
  stop-color: var(--svg-color--3f7cd5, #3F7CD5);
}

.edm992bfq {
  stop-color: var(--svg-color--8e5879, #8E5879);
  stop-opacity: 0;
}

.et8zn2bag {
  stop-color: var(--svg-color--639be0, #639BE0);
  stop-opacity: 0;
}

.etvc25zce {
  cx: 10.504px;
  cy: 12.853px;
  r: 1.918px;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
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

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fagndgtuo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.21 11.21c-.75 0-1.385.516-1.557 1.215c-.051.2.102.392.307.392h2.564c.163 0 .293-.15.26-.312a1.61 1.61 0 0 0-1.575-1.296");
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

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g-3ft7k9f {
  d: path("M3.862 29.934h24.276c-.466-6.296-5.723-11.26-12.138-11.26S4.328 23.639 3.862 29.935");
}

.g0x0s6b7k {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g13pasyql {
  fill: var(--svg-color--000, #000);
  d: path("M17.878 12.546c0-.326.26-.587.587-.587a.585.585 0 0 1 .522.858h-1.04a.53.53 0 0 1-.07-.27");
}

.g3qn2hbkl {
  d: path("M18.83 24.93a.5.5 0 0 1 .5-.5h1.812a.5.5 0 0 1 .5.5v1.727a1.406 1.406 0 0 1-2.813 0z");
}

.gd56libvg {
  stop-color: var(--svg-color--3169c8, #3169C8);
  stop-opacity: 0;
}

.gfcus0k-b {
  d: path("M16.749 24.47a.25.25 0 0 1-.224.139h-1.097a.25.25 0 0 1-.223-.139l-1.246-2.491h4.02z");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gxnbt7b-w {
  stop-color: var(--svg-color--ffd04c, #FFD04C);
}

.gytvam_id {
  d: path("m15.52 12.392l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hg3it7oev {
  stop-color: var(--svg-color--1b54be, #1B54BE);
  stop-opacity: 0;
}

.hg7hxmbra {
  stop-color: var(--svg-color--574a69, #574A69);
}

.hkek06bnn {
  cx: 21.434px;
  cy: 12.853px;
  r: 1.918px;
}

.htxp2lohr {
  d: path("m17.577 29.934l-.927-5.202a.15.15 0 0 0-.147-.123h-1.078a.15.15 0 0 0-.147.12l-1.025 5.205z");
}

.humbo4erb {
  stop-color: var(--svg-color--189cf0, #189CF0);
  stop-opacity: 0;
}

.hvd61e78c {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m21.496 5.41l.493.245c.863.429 1.356 1.41 1.17 2.451l-.677 3.493c-.06.361-.299.604-.657.613h-.021s.062-1.042.123-1.655c.05-.497-.037-.649-.493-1.103c-.246-.245-.431-.612-.431-.98v-.98c0-.307-.247-.552-.493-.613c-.74-.184-2.28-.49-4.5-.49c-2.218 0-3.759.306-4.499.49a.6.6 0 0 0-.492.612v.98c0 .369-.124.736-.432.981l-.185.184c-.246.184-.37.552-.37.858c.062.674.124 1.655.124 1.655q-.03 0-.057-.002a.73.73 0 0 1-.683-.611l-.678-3.493c-.123-.98.37-1.961 1.233-2.39l.493-.245c.308-.184.616-.43.924-.674l1.11-1.165c.678-.612 1.664-.796 2.527-.367a3.4 3.4 0 0 0 1.91 0c.925-.307 1.972-.062 2.712.613l.924.919c.247.306.555.49.925.674");
}

.i8a3pvbms {
  stop-color: var(--svg-color--46395b, #46395B);
}

.iimpokbga {
  d: path("m21.496 5.41l.493.245c.863.429 1.356 1.41 1.17 2.451l-.677 3.493c-.06.361-.299.604-.657.613h-.021s.062-1.042.123-1.655c.05-.497-.037-.649-.493-1.103c-.246-.245-.431-.612-.431-.98v-.98c0-.307-.247-.552-.493-.613c-.74-.184-2.28-.49-4.5-.49c-2.218 0-3.759.306-4.499.49a.6.6 0 0 0-.492.612v.98c0 .369-.124.736-.432.981l-.185.184c-.246.184-.37.552-.37.858c.062.674.124 1.655.124 1.655q-.03 0-.057-.002a.73.73 0 0 1-.683-.611l-.678-3.493c-.123-.98.37-1.961 1.233-2.39l.493-.245c.308-.184.616-.43.924-.674l1.11-1.165c.678-.612 1.664-.796 2.527-.367a3.4 3.4 0 0 0 1.91 0c.925-.307 1.972-.062 2.712.613l.924.919c.247.306.555.49.925.674");
}

.ilj7ybc1n {
  stop-color: var(--svg-color--73b8f6, #73B8F6);
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j2ao_sb9l {
  d: path("M8.797 4.266c-.625.258-1.356 1.025-.969 2.375s.526 1.802.547 1.86c.04.166.223.5.633.5h.39a.46.46 0 0 0 .301-.134c.142-.134 2.254-1.596 5.827-1.718c3.645.122 6.633 1.584 6.775 1.718a.45.45 0 0 0 .3.133h.391c.41 0 .593-.333.633-.5c.02-.057.16-.51.547-1.86s-.344-2.116-.969-2.374l-5.21-1.853a6 6 0 0 0-4.032.004z");
}

.j3cbwjknw {
  stop-color: var(--svg-color--ffd24b, #FFD24B);
}

.jdcv0xbln {
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jo3nm0bcx {
  stop-color: var(--svg-color--ffd44c, #FFD44C);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jrhkttjal {
  d: path("M18.39 11.738c.072.098-.08.217-.254.347c-.173.13-.302.22-.375.123c-.073-.098.008-.282.182-.412c.173-.13.373-.156.446-.058");
}

.ju6dckb-b {
  d: path("M18.465 11.521a1.025 1.025 0 0 1 .988 1.296h-1.98a1.03 1.03 0 0 1 .993-1.296");
}

.k-my16b7i {
  d: path("M19.378 12.412a.97.97 0 0 0-.266-.532l-.298.328l.134.262z");
}

.kdpeaetya {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
}

.kdz8adazd {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
  stop-opacity: 0;
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo1rr9b0y {
  stop-color: var(--svg-color--8a5d62, #8A5D62);
}

.lwjbbq_rp {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
}

.m8dz_mblr {
  d: path("M9.442 8.703c.396.844 1.515 2.461 3.97 2.461h5.115c2.454 0 3.573-1.617 3.97-2.46c-2.254-1.05-5.29-1.423-6.528-1.477c-1.237.054-4.274.426-6.527 1.476");
}

.magncybxl {
  d: path("m10.1 12.149l.056.002s-.062-.98-.124-1.655c0-.306.124-.674.37-.858l.185-.184c.308-.245.431-.612.431-.98v-.98c0-.307.185-.552.493-.613c.74-.184 2.28-.49 4.5-.49c2.218 0 3.76.306 4.499.49c.246.06.493.306.493.612v.98c0 .369.185.736.431.981c.577.405.541.627.493 1.103c-.061.613-.123 1.655-.123 1.655h.02l-.305 4.548c-.184 2.033-1.782 3.45-3.688 3.45h-3.69c-1.966 0-3.503-1.417-3.688-3.45z");
}

.meixgrb4k {
  d: path("M10.032 10.496c0-.306.124-.674.37-.858l.185-.184c.308-.245.431-.612.431-.98v-.98c0-.307.185-.552.493-.613c.74-.184 2.28-.49 4.5-.49c2.218 0 3.76.306 4.499.49c.246.06.493.306.493.612v.98c0 .369.185.736.431.981c.577.405.541.627.493 1.103c-.061.613-.123 1.655-.123 1.655h.02l-.305 4.548c-.184 2.033-1.782 3.45-3.688 3.45h-3.69c-1.966 0-3.503-1.417-3.688-3.45c-.16-2.087-.23-4.18-.42-6.264");
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mrrnlab-m {
  cx: 21.434px;
  cy: 12.853px;
  r: 1.143px;
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n1x1y9b1p {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.643 12.712l-.943 1.953c-.117.402.164.804.56.804h.848c.397 0 .678-.408.56-.804l-.572-1.953c-.122-.432-.325-.432-.453 0");
}

.n4wew7txz {
  stop-color: var(--svg-color--553830, #553830);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nh6zrzb2s {
  fill: var(--svg-color--000, #000);
  d: path("M14.034 12.546a.585.585 0 0 0-.587-.587a.585.585 0 0 0-.522.858h1.04a.6.6 0 0 0 .07-.27");
}

.ni0htxbur {
  stop-color: var(--svg-color--407ccf, #407CCF);
}

.nlnhxpbkx {
  stop-color: var(--svg-color--4681d4, #4681D4);
  stop-opacity: 0;
}

.nta8ypj0m {
  d: path("M14.793 3.757v.922a1.187 1.187 0 0 0 2.374 0v-.924a.2.2 0 0 0-.308-.168l-.252.16a.1.1 0 0 1-.134-.025l-.295-.402a.25.25 0 0 0-.403 0l-.292.401a.1.1 0 0 1-.135.025l-.247-.158a.2.2 0 0 0-.308.169");
}

.nx2bsjb_t {
  stop-color: var(--svg-color--4a88df, #4A88DF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ojnx9kp9k {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
  stop-opacity: 0;
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.p_hknfval {
  stop-color: var(--svg-color--81d0ff, #81D0FF);
}

.piqrmm5sr {
  cx: 13.138px;
  cy: 11.959px;
  rx: 0.448px;
  ry: 0.227px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q-4mmubff {
  stop-color: var(--svg-color--87ddff, #87DDFF);
}

.q3vx93ufn {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.qfni0kjsa {
  fill-rule: evenodd;
  d: path("M21.92 8.962c-5.062-1.854-9.999-.764-11.82-.011a.775.775 0 0 1-.592-1.432c2.085-.862 7.432-2.032 12.945-.012a.775.775 0 1 1-.533 1.455");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qjgh28b1y {
  stop-color: var(--svg-color--189cf0, #189CF0);
}

.qk56hfspl {
  stop-color: var(--svg-color--4681d4, #4681D4);
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qt_mg48rg {
  stop-color: var(--svg-color--409ed2, #409ED2);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r_91d457c {
  stop-color: var(--svg-color--4389d1, #4389D1);
  stop-opacity: 0;
}

.r9aql0tfq {
  stop-color: var(--svg-color--30acff, #30ACFF);
  stop-opacity: 0;
}

.re303qbql {
  stop-color: var(--svg-color--7c4e5c, #7C4E5C);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rvybbdrcw {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
  stop-opacity: 0;
}

.sjzaf5e-a {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
  stop-opacity: 0;
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t8aw4mbyz {
  stop-color: var(--svg-color--9b7282, #9B7282);
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

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.trkjkfbvt {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.trw5-7ral {
  fill: var(--svg-color--297ecb, #297ECB);
  d: path("M14.74 3.8v.922a1.187 1.187 0 1 0 2.373 0v-.924a.2.2 0 0 0-.307-.169l-.253.161a.1.1 0 0 1-.134-.025l-.294-.402a.25.25 0 0 0-.404 0l-.292.401a.1.1 0 0 1-.135.025l-.247-.158a.2.2 0 0 0-.308.169");
}

.ts35s1bpk {
  fill: var(--svg-color--247dbd, #247DBD);
  fill-rule: evenodd;
  d: path("M21.582 8.636c-4.687-1.717-9.257-.769-10.943-.072a.717.717 0 1 1-.548-1.326c1.93-.798 6.88-1.82 11.984.05a.717.717 0 1 1-.493 1.348");
}

.tvq6re52s {
  d: path("M13.447 11.521a1.025 1.025 0 0 0-.988 1.296h1.98q.037-.132.038-.27a1.03 1.03 0 0 0-1.03-1.026");
}

.u3zrqkbyl {
  stop-color: var(--svg-color--956868, #956868);
  stop-opacity: 0;
}

.u5b_qpb1y {
  stop-color: var(--svg-color--734d45, #734D45);
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vg5w9dbzr {
  stop-color: var(--svg-color--30acff, #30ACFF);
}

.vhpcois2a {
  stop-color: var(--svg-color--ffcd47, #FFCD47);
}

.vnlonib2h {
  d: path("M13.74 19.832c.21.57.812 1.582 2.206 2.223c1.454-.75 1.934-1.652 2.145-2.223l-2.145-.332z");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w4srnfb7y {
  fill: var(--svg-color--2389d6, #2389D6);
  d: path("m12.646 19.685l.763 3.8a.41.41 0 0 0 .662.242l.452-.364l.601 1.204c.04.079.12.128.208.128h1.021c.089 0 .17-.05.21-.13l.586-1.187l.437.349a.41.41 0 0 0 .661-.242l.764-3.8z");
}

.wt_jecb6v {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
}

.x0d9392gq {
  cx: 13.138px;
  cy: 11.959px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.448px;
  ry: 0.227px;
}

.x0r_jb-wm {
  stop-color: var(--svg-color--7c4e5c, #7C4E5C);
  stop-opacity: 0;
}

.x9phhgbra {
  cx: 21.434px;
  cy: 12.853px;
  r: 1.143px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.xf9qqcbnz {
  stop-color: var(--svg-color--4eb9f4, #4EB9F4);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xsp7-kwpz {
  stop-color: var(--svg-color--3c73d6, #3C73D6);
}

.xsu_qdbmh {
  stop-color: var(--svg-color--4188d4, #4188D4);
  stop-opacity: 0;
}

.y_n28597o {
  cx: 10.504px;
  cy: 12.853px;
  r: 1.143px;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.ylhb00l1u {
  stop-color: var(--svg-color--4389d1, #4389D1);
}

.yvnwtvbdk {
  stop-color: var(--svg-color--3169c8, #3169C8);
}

.yvy6tz2sx {
  d: path("M23.945 29.934h4.193a12.15 12.15 0 0 0-4.193-8.309z");
}

.yz7s41bfz {
  stop-color: var(--svg-color--8a5d62, #8A5D62);
  stop-opacity: 0;
}

.z_4nico_h {
  stop-color: var(--svg-color--7dc8fc, #7DC8FC);
  stop-opacity: 0;
}

.zh5wbhzns {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.52 12.525l-.61 1.953a.62.62 0 0 0 .597.804h.904a.62.62 0 0 0 .598-.804l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.zp2_bjbgn {
  d: path("M14.384 12.426c0-.331-.27-.552-.343-.619l-.33.32l.203.416z");
}

.zstiy-bhq {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zy2fe0b7g {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
}

</style>
