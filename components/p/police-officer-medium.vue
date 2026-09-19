<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="dee3snbxe"/><path fill="url(#i3b9cme)" class="g-3ft7k9f"/><path fill="url(#iT6XAqe)" class="g-3ft7k9f"/><path fill="url(#iTFqkvb)" class="g-3ft7k9f"/><path fill="url(#i6dLLtb)" class="g-3ft7k9f"/><g filter="url(#izuWpJb)"><path class="w4srnfb7y"/></g><path fill="url(#iVk8ZRb)" class="thtcysb5g"/><path fill="url(#iySxojc)" class="thtcysb5g"/><path fill="url(#iBT0Egc)" class="yvy6tz2sx"/><path fill="url(#iSWq0Oc)" class="yvy6tz2sx"/><g filter="url(#iDCKOMH)"><path fill="url(#iPxdGmJ)" class="gfcus0k-b"/><path fill="url(#iJSlXzd)" class="gfcus0k-b"/><path fill="url(#iJK0STd)" class="gfcus0k-b"/><path fill="url(#ikLUynd)" class="gfcus0k-b"/></g><path fill="url(#iOoOjsw)" class="coer9ebiy"/><path fill="url(#i4gZH3d)" class="coer9ebiy"/><path fill="url(#ihSlXYc)" class="coer9ebiy"/><g filter="url(#ih6Qtfb)"><path class="g0x0s6b7k"/><path fill="url(#ie1yCCd)" class="zstiy-bhq"/></g><path fill="url(#iJ1vlub)" class="zstiy-bhq"/><g filter="url(#i5oWd4b)"><path class="fu5sdg_kf"/><path fill="url(#iNae8ve)" class="cjztvk1qv"/><path fill="url(#i4SYPYc)" class="cjztvk1qv"/></g><path fill="url(#io6Q47d)" class="cjztvk1qv"/><g filter="url(#idrXeib)"><path fill="url(#iCAKTMe)" class="vnlonib2h"/><path fill="url(#iRh2DQe)" class="vnlonib2h"/></g><path class="wl5mbzbrp"/><path fill="url(#iCAZktd)" class="qhm2dwfxa"/><path fill="url(#id9szCE)" class="voanp7bfs"/><path fill="url(#iiuNA5d)" class="d4ciczbmk"/><path fill="url(#iSfAU7c)" class="y7qu51ufm"/><g filter="url(#iVppf1d)"><path fill="url(#iqeazkc)" class="u0qirtb1z"/><path fill="url(#iMrplPq)" class="u0qirtb1z"/></g><path fill="url(#ijx9lIe)" class="u0qirtb1z"/><path fill="url(#iRuUIkb)" class="u0qirtb1z"/><path fill="url(#i8VWwoe)" class="u0qirtb1z"/><path fill="url(#iY8GeSb)" class="u0qirtb1z"/><path fill="url(#iQQNayd)" class="u0qirtb1z"/><path fill="url(#iZe8g4b)" class="u0qirtb1z"/><path fill="url(#ioz43vR)" class="u0qirtb1z"/><path fill="url(#i4A3dJd)" class="u0qirtb1z"/><path fill="url(#in8sKXG)" class="u0qirtb1z"/><g filter="url(#ig62L6b)"><path class="miuwk7bwm"/></g><g filter="url(#isDDY2d)"><path class="ar23nzpht"/><path fill="url(#iFdAfDc)" class="qs5wm801v"/><path fill="url(#iFif3id)" class="qs5wm801v"/><path fill="url(#iAs8wpb)" class="qs5wm801v"/><path fill="url(#iVqmGsb)" class="qs5wm801v"/></g><g filter="url(#i7IDmVd)"><path fill="url(#i9QGRjb)" class="qs5wm801v"/></g><g filter="url(#iRM8iXc)"><path stroke="url(#iY7MbBb)" class="ib_4zcc7n"/></g><path fill="url(#imdrHHe)" class="cvumfw47y"/><path class="p76qd6b4y"/><path fill="url(#i72pdtd)" class="lastglwui"/><path class="rbhkdchdt"/><g filter="url(#itIhbme)"><path class="bpyjwvbyf"/><path fill="url(#imE6cge)" class="hw5sr9bfk"/></g><g filter="url(#iXihTbc)"><path fill="url(#iw26wTc)" class="vpfkknbue"/></g><path class="lazm-rb0q"/><path fill="url(#iuYTAqb)" class="pfkuhzbwv"/><path class="nf93_wb4f"/><g filter="url(#irsi84c)"><path fill="url(#ilbueLe)" class="r37r56bat"/></g><g filter="url(#iIZT2Ub)"><ellipse transform="rotate(-27.914 13.203 11.966)" class="et7xlcb-w"/><ellipse fill="url(#iQHFG2d)" transform="rotate(-27.914 13.203 11.966)" class="rkreho0mf"/></g><path fill="url(#iahp91b)" class="qhj-eqb8q"/><path fill="url(#igWuBsc)" class="qhj-eqb8q"/><path fill="url(#iCGT4Cl)" class="qhj-eqb8q"/><path fill="url(#i8lZu6b)" class="qhj-eqb8q"/><path fill="url(#izYERdc)" class="hfw44hboy"/><path fill="url(#itkh0Oe)" class="hfw44hboy"/><g filter="url(#idAbxhe)"><path fill="url(#inWcoBc)" class="rr6b_e_fs"/></g><g filter="url(#iuCb4Lb)"><path fill="url(#i8ELZPd)" class="kzgimbbrm"/></g><g filter="url(#iAl2GIb)"><path fill="url(#isLM7wb)" class="j2ao_sb9l"/><path fill="url(#i945GOe)" class="j2ao_sb9l"/></g><path fill="url(#iizJfPb)" class="j2ao_sb9l"/><g filter="url(#ilFlIJc)"><path class="trw5-7ral"/></g><g filter="url(#ioOwqqA)"><path fill="url(#iBrxMjb)" class="hd5r75bzt"/></g><g filter="url(#isWyyCl)"><path fill="url(#iIgw5Lc)" class="mtkt99emo"/><path fill="url(#i1oZv1c)" class="mtkt99emo"/></g><g filter="url(#i86u8lb)"><path clip-rule="evenodd" class="ts35s1bpk"/></g><g filter="url(#iA1tbJc)"><path fill="url(#igpewSb)" clip-rule="evenodd" class="bk_2u1bog"/></g><path fill="url(#iiEONhS)" clip-rule="evenodd" class="bk_2u1bog"/><path fill="url(#i0rO5Pe)" clip-rule="evenodd" class="bk_2u1bog"/><g filter="url(#iT5LJAd)"><path fill="url(#iF5yRae)" class="g3qn2hbkl"/></g><g filter="url(#ihrh48b)"><rect fill="url(#iySt08c)" class="f5rlg0klg"/></g><defs><radialGradient id="i3b9cme" cx="0" cy="0" r="1" gradientTransform="matrix(.59372 6.27271 -11.9943 1.13527 13.662 18.032)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ewagz7_9h"/><stop offset="1" class="a8t42xt1y"/></radialGradient><radialGradient id="iT6XAqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 0 0 14.4101 8.099 29.934)" gradientUnits="userSpaceOnUse"><stop class="vg5w9dbzr"/><stop offset="1" class="r9aql0tfq"/></radialGradient><radialGradient id="iTFqkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -12.1562 24.005 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="bglf8cb8f"/><stop offset="1" class="f1vhuirkb"/></radialGradient><radialGradient id="iVk8ZRb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -6.93362 3.8209 .51663 6.443 29.934)" gradientUnits="userSpaceOnUse"><stop class="ff-z7nbub"/><stop offset="1" class="qt_mg48rg"/></radialGradient><radialGradient id="iySxojc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -13.7094 8.287 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="a2jurmb2n"/><stop offset="1" class="xsu_qdbmh"/></radialGradient><radialGradient id="iBT0Egc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 -8.02737 2.31779 -.47822 26.443 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="f69-7cs4d"/><stop offset="1" class="xf9qqcbnz"/></radialGradient><radialGradient id="iSWq0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36307 0 0 13.6894 23.945 29.71)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="qjgh28b1y"/><stop offset=".8" class="humbo4erb"/></radialGradient><radialGradient id="iPxdGmJ" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 3.525 14.988)scale(2.34396 3.58278)" gradientUnits="userSpaceOnUse"><stop class="ni0htxbur"/><stop offset="1" class="xsp7-kwpz"/></radialGradient><radialGradient id="iJSlXzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 -1.10937 1.05865 1.5358 15.473 24.032)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nlnhxpbkx"/><stop offset="1" class="qk56hfspl"/></radialGradient><radialGradient id="iOoOjsw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71487 -1.3158 0 15.915 25.219)" gradientUnits="userSpaceOnUse"><stop class="e9hbkmbux"/><stop offset="1" class="fqfyucbrl"/></radialGradient><radialGradient id="ie1yCCd" cx="0" cy="0" r="1" gradientTransform="matrix(.6593 -2.21967 2.48774 .73893 14.283 23.669)" gradientUnits="userSpaceOnUse"><stop class="zy2fe0b7g"/><stop offset="1" class="kdz8adazd"/></radialGradient><radialGradient id="iJ1vlub" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.49506 -2.22013 -.51048 14.005 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="cxc4ijbrr"/><stop offset="1" class="sjzaf5e-a"/></radialGradient><radialGradient id="i4SYPYc" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .42188 -1.25086 1.38985 17.036 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="bzog60bkg"/><stop offset=".902" class="et8zn2bag"/></radialGradient><radialGradient id="io6Q47d" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 .875 -2.39996 2.31425 17.786 19.907)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="wt_jecb6v"/><stop offset="1" class="tp8jvfpml"/></radialGradient><radialGradient id="iCAKTMe" cx="0" cy="0" r="1" gradientTransform="rotate(148.065 5.885 12.705)scale(2.68809 2.30164)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="t8aw4mbyz"/><stop offset="1" class="a991r1brt"/></radialGradient><radialGradient id="iRh2DQe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42188 .20312 -.04646 -.55397 15.349 20)" gradientUnits="userSpaceOnUse"><stop class="c8ock4brc"/><stop offset="1" class="edm992bfq"/></radialGradient><radialGradient id="iCAZktd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2821 .3468 -.8516 -3.14834 10.27 9.781)" gradientUnits="userSpaceOnUse"><stop class="ni3kwpbbb"/><stop offset=".722" class="ev83w7b-f"/></radialGradient><radialGradient id="id9szCE" cx="0" cy="0" r="1" gradientTransform="matrix(.8507 .23743 -.95836 3.43383 21.88 9.711)" gradientUnits="userSpaceOnUse"><stop class="okrus5wdl"/><stop offset="1" class="eoxgmkk3z"/></radialGradient><radialGradient id="iiuNA5d" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 .522 22.523)scale(2.46745 2.93114)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iSfAU7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.69141 .53159 -1.63998 5.21813 9.075 14.766)" gradientUnits="userSpaceOnUse"><stop class="t1hu-8bzb"/><stop offset=".746" class="rjnu1bd2y"/></radialGradient><radialGradient id="iqeazkc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.39002 0 0 -9.5349 19.23 13.126)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iMrplPq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99694 3.30267 -2.72663 -1.64864 18.794 7.422)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iRuUIkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.1716 -11.7357 0 16.654 6.412)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="u3zrqkbyl"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="i8VWwoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31554 1.62797 0 18.817 11.622)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iY8GeSb" cx="0" cy="0" r="1" gradientTransform="matrix(.0045 -1.2536 1.3642 .0049 13.378 11.675)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iQQNayd" cx="0" cy="0" r="1" gradientTransform="matrix(-9.73289 .61439 -1.56945 -24.86261 19.946 14.258)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iZe8g4b" cx="0" cy="0" r="1" gradientTransform="matrix(3.8787 -3.34107 .9869 1.1457 8.233 9.995)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="ioz43vR" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.729 15.073)scale(2.87363 1.14871)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="i4A3dJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .99848 -1.9168 0 13.475 12.558)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="in8sKXG" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.24499 -6.75 0 15.215 9.88)" gradientUnits="userSpaceOnUse"><stop offset=".404" class="re303qbql"/><stop offset="1" class="x0r_jb-wm"/></radialGradient><radialGradient id="iFif3id" cx="0" cy="0" r="1" gradientTransform="matrix(0 .27964 -.87887 0 16.547 14.684)" gradientUnits="userSpaceOnUse"><stop class="o5qf-ej6a"/><stop offset="1" class="ilt16x1zy"/></radialGradient><radialGradient id="iVqmGsb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9384 .8593 -1.38097 -3.11516 16.68 14.032)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="imdrHHe" cx="0" cy="0" r="1" gradientTransform="matrix(2.49965 -1.2289 4.94418 10.05676 15.45 17.276)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i72pdtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92944 -1.47837 0 18.513 12.076)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="imE6cge" cx="0" cy="0" r="1" gradientTransform="matrix(-.26568 -.34237 .47136 -.36578 18.252 12.173)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuYTAqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92948 -1.47845 0 13.514 12.076)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iQHFG2d" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.66 -.327)scale(.56608 .68046)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igWuBsc" cx="0" cy="0" r="1" gradientTransform="matrix(.72006 2.56987 -2.45185 .687 21.303 12.092)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iCGT4Cl" cx="0" cy="0" r="1" gradientTransform="matrix(.90247 -1.2385 1.0381 .75645 21.716 12.716)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i8lZu6b" cx="0" cy="0" r="1" gradientTransform="matrix(.67246 -1.77614 2.37318 .8985 21.847 12.913)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="itkh0Oe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.89967 0 0 -2.12126 10.382 12.827)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="inWcoBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0499 .18022 -.18478 -1.07649 10.383 12.83)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="isLM7wb" cx="0" cy="0" r="1" gradientTransform="rotate(153.716 9.95 5.24)scale(8.88768 11.3119)" gradientUnits="userSpaceOnUse"><stop class="b5oikgndb"/><stop offset="1" class="aiodo62qb"/></radialGradient><radialGradient id="iizJfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56249 1.8125 -5.67441 -1.76097 20.88 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="lwjbbq_rp"/><stop offset="1" class="c0fdt7b4z"/></radialGradient><radialGradient id="iIgw5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.454 12.31 1.781)scale(8.75158 12.2726)" gradientUnits="userSpaceOnUse"><stop class="hg7hxmbra"/><stop offset="1" class="i8a3pvbms"/></radialGradient><radialGradient id="i1oZv1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33594 10.5987 0 15.969 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="e3kv8ccww"/><stop offset=".917" class="t9xlhbbtl"/></radialGradient><radialGradient id="iiEONhS" cx="0" cy="0" r="1" gradientTransform="rotate(101.822 7.538 11.83)scale(1.37287 11.6524)" gradientUnits="userSpaceOnUse"><stop class="q-4mmubff"/><stop offset="1" class="z_4nico_h"/></radialGradient><radialGradient id="i0rO5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(137.81 10.052 8.132)scale(2.38738 2.66614)" gradientUnits="userSpaceOnUse"><stop class="q3vx93ufn"/><stop offset="1" class="ojnx9kp9k"/></radialGradient><filter id="izuWpJb" width="7.365" height="6.01" x="12.146" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".25"/></filter><filter id="iDCKOMH" width="4.12" height="2.78" x="13.959" y="21.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/></filter><filter id="ih6Qtfb" width="3.58" height="4.539" x="12.543" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/></filter><filter id="i5oWd4b" width="3.6" height="4.539" x="15.878" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/></filter><filter id="idrXeib" width="4.352" height="2.805" x="13.739" y="19.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.278431 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/></filter><filter id="iVppf1d" width="12.708" height="14.239" x="10.213" y="6.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2683" result="effect2_innerShadow_4002_2683"/></filter><filter id="ig62L6b" width="4.001" height="5.322" x="13.85" y="11.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".5"/></filter><filter id="isDDY2d" width="2.551" height="3.722" x="14.738" y="11.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.360784 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/><feGaussianBlur result="effect2_foregroundBlur_4002_2683" stdDeviation=".1"/></filter><filter id="i7IDmVd" width="2.551" height="3.722" x="14.738" y="11.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".1"/></filter><filter id="iRM8iXc" width="4.187" height="1.729" x="13.92" y="15.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".05"/></filter><filter id="itIhbme" width=".872" height=".769" x="17.687" y="11.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".05"/></filter><filter id="iXihTbc" width=".963" height=".988" x="18.663" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".1"/></filter><filter id="irsi84c" width="1.072" height="1.133" x="13.574" y="11.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".1"/></filter><filter id="iIZT2Ub" width="1.017" height=".778" x="12.694" y="11.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".05"/></filter><filter id="idAbxhe" width="1.45" height="2.653" x="9.084" y="11.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".125"/></filter><filter id="iuCb4Lb" width="1.923" height="3.014" x="21.299" y="11.315" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".25"/></filter><filter id="iAl2GIb" width="16.56" height="6.934" x="7.72" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.537255 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/></filter><filter id="ilFlIJc" width="2.674" height="2.948" x="14.589" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".075"/></filter><filter id="ioOwqqA" width="2.624" height="2.748" x="14.643" y="3.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2683" result="effect2_innerShadow_4002_2683"/></filter><filter id="isWyyCl" width="13.155" height="4.088" x="9.342" y="7.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.207843 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2683" result="effect2_innerShadow_4002_2683"/></filter><filter id="i86u8lb" width="13.899" height="3.448" x="9.147" y="5.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2683" stdDeviation=".25"/></filter><filter id="iA1tbJc" width="14.033" height="2.72" x="9.028" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/></filter><filter id="iT5LJAd" width="3.063" height="3.733" x="18.679" y="24.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2683" result="effect2_innerShadow_4002_2683"/></filter><filter id="ihrh48b" width="4.306" height="1.334" x="8.789" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2683"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2683" result="effect2_innerShadow_4002_2683"/></filter><linearGradient id="i6dLLtb" x1="7.926" x2="8.205" y1="28.477" y2="28.477" gradientUnits="userSpaceOnUse"><stop offset=".229" class="kdpeaetya"/><stop offset="1" class="rvybbdrcw"/></linearGradient><linearGradient id="iJK0STd" x1="15.193" x2="15.497" y1="22.422" y2="22.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="ikLUynd" x1="16.404" x2="16.185" y1="22.258" y2="22.555" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="i4gZH3d" x1="17.412" x2="16.474" y1="27.875" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ahgk2rx2r"/><stop offset="1" class="nx2bsjb_t"/></linearGradient><linearGradient id="ihSlXYc" x1="14.677" x2="15.915" y1="27.11" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="yvnwtvbdk"/><stop offset="1" class="gd56libvg"/></linearGradient><linearGradient id="iNae8ve" x1="18.786" x2="17.247" y1="22.422" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="bxeumjbad"/><stop offset="1" class="c8b-jsd8k"/></linearGradient><linearGradient id="ijx9lIe" x1="21.921" x2="19.024" y1="15.056" y2="15.056" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iFdAfDc" x1="16.974" x2="16.013" y1="13.899" y2="13.938" gradientUnits="userSpaceOnUse"><stop class="b0x3oac_z"/><stop offset="1" class="fo1xyl03w"/></linearGradient><linearGradient id="iAs8wpb" x1="16.013" x2="16.013" y1="15.204" y2="14.671" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="i9QGRjb" x1="16.013" x2="16.059" y1="11.957" y2="13.123" gradientUnits="userSpaceOnUse"><stop class="cfp4fxb-k"/><stop offset="1" class="etuosdj9z"/></linearGradient><linearGradient id="iY7MbBb" x1="14.637" x2="15.001" y1="17.003" y2="16.047" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iw26wTc" x1="19.404" x2="19.045" y1="12.138" y2="12.359" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilbueLe" x1="14.366" x2="14.006" y1="12.138" y2="12.359" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iahp91b" x1="23.387" x2="22.004" y1="12.168" y2="14.662" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="izYERdc" x1="9.312" x2="10.982" y1="12.975" y2="12.829" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="i8ELZPd" x1="22.26" x2="22.26" y1="11.815" y2="13.829" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="i945GOe" x1="7.318" x2="13.13" y1="7.657" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="ylhb00l1u"/><stop offset="1" class="r_91d457c"/></linearGradient><linearGradient id="iBrxMjb" x1="16.899" x2="14.793" y1="4.542" y2="4.542" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="igpewSb" x1="10.974" x2="21.755" y1="7.7" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="ilj7ybc1n"/><stop offset="1" class="p_hknfval"/></linearGradient><linearGradient id="iF5yRae" x1="21.325" x2="18.829" y1="26.246" y2="26.246" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="iySt08c" x1="13.095" x2="8.763" y1="26.864" y2="26.864" gradientUnits="userSpaceOnUse"><stop class="gxnbt7b-w"/><stop offset="1" class="vhpcois2a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:police-officer-medium" /></template>
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

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
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

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.ar23nzpht {
  fill: var(--svg-color--936763, #936763);
  d: path("m15.575 12.307l-.609 2.106c-.124.433.174.866.597.866h.9c.423 0 .721-.44.597-.866l-.609-2.106c-.13-.467-.739-.467-.876 0");
}

.b0x3oac_z {
  stop-color: var(--svg-color--c29c84, #C29C84);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b5oikgndb {
  stop-color: var(--svg-color--48a8fb, #48A8FB);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bglf8cb8f {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bk_2u1bog {
  fill-rule: evenodd;
  d: path("M21.92 8.962c-5.062-1.854-10-.764-11.82-.011a.775.775 0 0 1-.593-1.432c2.085-.862 7.433-2.032 12.946-.012a.775.775 0 1 1-.533 1.455");
}

.bpyjwvbyf {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.44 11.746c.073.097-.08.216-.252.345c-.173.13-.302.22-.375.123s.009-.281.182-.41c.173-.13.372-.156.445-.059");
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

.cfp4fxb-k {
  stop-color: var(--svg-color--875a60, #875A60);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cjztvk1qv {
  d: path("M15.878 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.coer9ebiy {
  d: path("m17.577 29.934l-.926-5.202a.15.15 0 0 0-.148-.123h-1.078a.15.15 0 0 0-.147.12l-1.025 5.205z");
}

.cvumfw47y {
  d: path("M16.013 16.444a3.44 3.44 0 0 1-1.587-.377c-.157-.08-.325.097-.227.24c.384.581 1.053.969 1.814.969s1.43-.388 1.814-.97c.099-.147-.07-.318-.227-.239c-.459.24-1 .377-1.587.377");
}

.cxc4ijbrr {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
}

.d4ciczbmk {
  d: path("M21.582 14.557a1.9 1.9 0 0 0 1.037-.353v1.066c0 1.024-.61 1.935-1.537 2.313q.295-.624.397-1.351z");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dee3snbxe {
  fill: var(--svg-color--3fb3ff, #3FB3FF);
  d: path("M3.862 29.934h24.276c-.466-6.296-5.723-11.26-12.138-11.26S4.328 23.639 3.862 29.935");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
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

.eoxgmkk3z {
  stop-color: var(--svg-color--4e383c, #4E383C);
}

.et7xlcb-w {
  cx: 13.203px;
  cy: 11.966px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.446px;
  ry: 0.226px;
}

.et8zn2bag {
  stop-color: var(--svg-color--639be0, #639BE0);
  stop-opacity: 0;
}

.etuosdj9z {
  stop-color: var(--svg-color--875a60, #875A60);
  stop-opacity: 0;
}

.ev83w7b-f {
  stop-color: var(--svg-color--564242, #564242);
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

.fo1xyl03w {
  stop-color: var(--svg-color--c29c84, #C29C84);
  stop-opacity: 0;
}

.fqfyucbrl {
  stop-color: var(--svg-color--3872d8, #3872D8);
}

.ft5dv1b6b {
  fill: none;
}

.fu5sdg_kf {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M15.878 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
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

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gxnbt7b-w {
  stop-color: var(--svg-color--ffd04c, #FFD04C);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hd5r75bzt {
  d: path("M14.793 3.757v.922a1.187 1.187 0 0 0 2.374 0v-.924a.2.2 0 0 0-.308-.168l-.252.16a.1.1 0 0 1-.134-.025l-.295-.402a.25.25 0 0 0-.404 0l-.29.401a.1.1 0 0 1-.136.025l-.247-.158a.2.2 0 0 0-.308.169");
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hfw44hboy {
  d: path("M10.235 10.991c-.895.126-1.595.9-1.595 1.83c0 .985.771 1.789 1.742 1.841a90 90 0 0 1-.147-3.671");
}

.hg3it7oev {
  stop-color: var(--svg-color--1b54be, #1B54BE);
  stop-opacity: 0;
}

.hg7hxmbra {
  stop-color: var(--svg-color--574a69, #574A69);
}

.humbo4erb {
  stop-color: var(--svg-color--189cf0, #189CF0);
  stop-opacity: 0;
}

.hw5sr9bfk {
  d: path("M18.44 11.746c.073.097-.08.216-.252.345c-.173.13-.302.22-.375.123s.009-.281.182-.41c.173-.13.372-.156.445-.059");
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i8a3pvbms {
  stop-color: var(--svg-color--46395b, #46395B);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ib_4zcc7n {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.46 16c.449.235.983.369 1.553.369c.576 0 1.104-.134 1.553-.368a.25.25 0 0 1 .298.049c.07.073.097.191.026.298l-.063-.041a2.17 2.17 0 0 1-1.814.969a2.17 2.17 0 0 1-1.814-.97zm0 0a.25.25 0 0 0-.298.052a.23.23 0 0 0-.025.297z");
}

.ilj7ybc1n {
  stop-color: var(--svg-color--73b8f6, #73B8F6);
}

.ilt16x1zy {
  stop-color: var(--svg-color--be9586, #BE9586);
  stop-opacity: 0;
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
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

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jo3nm0bcx {
  stop-color: var(--svg-color--ffd44c, #FFD44C);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.kdpeaetya {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
}

.kdz8adazd {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kzgimbbrm {
  d: path("M21.799 13.829q.056-1.008.108-2.014c.46.062.815.487.815 1.003c0 .555-.413 1.005-.923 1.01");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lastglwui {
  d: path("M18.515 11.53a1.022 1.022 0 0 1 .985 1.292h-1.974a1.026 1.026 0 0 1 .99-1.292");
}

.lazm-rb0q {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.274 11.218a1.6 1.6 0 0 0-1.552 1.213c-.051.2.102.39.307.39h2.556a.264.264 0 0 0 .26-.311a1.605 1.605 0 0 0-1.57-1.292");
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

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.miuwk7bwm {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.553 12.531l-.676 2.106c-.116.433.161.867.554.867h.839c.393 0 .67-.44.555-.867l-.567-2.106c-.121-.466-.577-.466-.705 0");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mtkt99emo {
  d: path("M9.442 8.703c.396.844 1.515 2.461 3.97 2.461h5.115c2.454 0 3.573-1.617 3.97-2.46c-2.254-1.05-5.291-1.423-6.528-1.477c-1.237.054-4.274.426-6.527 1.476");
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nf93_wb4f {
  fill: var(--svg-color--000, #000);
  d: path("M14.097 12.552a.583.583 0 0 0-.586-.585a.583.583 0 0 0-.52.855h1.036a.6.6 0 0 0 .07-.27");
}

.ni0htxbur {
  stop-color: var(--svg-color--407ccf, #407CCF);
}

.ni3kwpbbb {
  stop-color: var(--svg-color--2d1522, #2D1522);
}

.nlnhxpbkx {
  stop-color: var(--svg-color--4681d4, #4681D4);
  stop-opacity: 0;
}

.nx2bsjb_t {
  stop-color: var(--svg-color--4a88df, #4A88DF);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o5qf-ej6a {
  stop-color: var(--svg-color--be9586, #BE9586);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
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

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.okrus5wdl {
  stop-color: var(--svg-color--3f2433, #3F2433);
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.p_hknfval {
  stop-color: var(--svg-color--81d0ff, #81D0FF);
}

.p76qd6b4y {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.752 11.218a1.6 1.6 0 0 1 1.552 1.213c.052.2-.102.39-.306.39h-2.556a.264.264 0 0 1-.26-.311a1.6 1.6 0 0 1 1.57-1.292");
}

.pfkuhzbwv {
  d: path("M13.511 11.53a1.022 1.022 0 0 0-.985 1.292H14.5a1 1 0 0 0 .037-.27a1.03 1.03 0 0 0-1.027-1.022");
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

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qhj-eqb8q {
  d: path("M21.652 14.662q.114-1.829.211-3.656a1.844 1.844 0 0 1-.211 3.656");
}

.qhm2dwfxa {
  d: path("M9.02 9.797c-.153-.45-.262-.89-.31-1.117h1.79v3.273H9.219v-1.195c0-.355-.074-.59-.2-.96");
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

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qs5wm801v {
  d: path("m15.575 12.307l-.609 2.106c-.124.433.174.866.597.866h.9c.423 0 .721-.44.597-.866l-.609-2.106c-.13-.467-.739-.467-.876 0");
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

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r37r56bat {
  d: path("M14.445 12.432c0-.33-.268-.55-.34-.617l-.331.32l.203.413z");
}

.r9aql0tfq {
  stop-color: var(--svg-color--30acff, #30ACFF);
  stop-opacity: 0;
}

.rbhkdchdt {
  fill: var(--svg-color--000, #000);
  d: path("M17.93 12.552c0-.325.26-.585.585-.585a.583.583 0 0 1 .52.855H18a.53.53 0 0 1-.07-.27");
}

.re303qbql {
  stop-color: var(--svg-color--7c4e5c, #7C4E5C);
}

.rjnu1bd2y {
  stop-color: var(--svg-color--2a1e21, #2A1E21);
}

.rkreho0mf {
  cx: 13.203px;
  cy: 11.966px;
  rx: 0.446px;
  ry: 0.226px;
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rr6b_e_fs {
  d: path("M10.188 11.753a1.095 1.095 0 0 0 .095 2.153a90 90 0 0 1-.095-2.153");
}

.rvybbdrcw {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
  stop-opacity: 0;
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sjzaf5e-a {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
  stop-opacity: 0;
}

.t1hu-8bzb {
  stop-color: var(--svg-color--4c3d3a, #4C3D3A);
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

.trw5-7ral {
  fill: var(--svg-color--297ecb, #297ECB);
  d: path("M14.74 3.8v.922a1.187 1.187 0 1 0 2.373 0v-.924a.2.2 0 0 0-.307-.169l-.253.161a.1.1 0 0 1-.134-.025l-.294-.402a.25.25 0 0 0-.404 0l-.292.401a.1.1 0 0 1-.135.025l-.247-.158a.2.2 0 0 0-.308.169");
}

.ts35s1bpk {
  fill: var(--svg-color--247dbd, #247DBD);
  fill-rule: evenodd;
  d: path("M21.582 8.636c-4.687-1.717-9.257-.769-10.943-.072a.717.717 0 1 1-.548-1.326c1.93-.798 6.88-1.82 11.984.05a.717.717 0 1 1-.493 1.348");
}

.u0qirtb1z {
  d: path("M10.486 16.293a4.486 4.486 0 0 0 4.451 3.902H17.1a4.486 4.486 0 0 0 4.45-3.902c.136-2.158.272-4.307.372-6.464a1.66 1.66 0 0 0-1.58-1.64h-1.604a2.78 2.78 0 0 1-2.533-1.653a.76.76 0 0 0-.705-.48h-1.458c-2.115 0-3.828 1.733-3.828 3.871c0 2.132.133 4.23.273 6.366");
}

.u3zrqkbyl {
  stop-color: var(--svg-color--956868, #956868);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
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

.voanp7bfs {
  d: path("M22.809 9.836c.168-.39.394-.808.48-1.156h-1.945v3.273h1.281v-1.195c-.013-.17.041-.59.184-.922");
}

.vpfkknbue {
  d: path("M19.426 12.418a.96.96 0 0 0-.265-.53l-.298.326l.135.262z");
}

.w4srnfb7y {
  fill: var(--svg-color--2389d6, #2389D6);
  d: path("m12.646 19.685l.763 3.8a.41.41 0 0 0 .662.242l.452-.364l.601 1.204c.04.079.12.128.208.128h1.021c.089 0 .17-.05.21-.13l.586-1.187l.437.349a.41.41 0 0 0 .661-.242l.764-3.8z");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
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

.x0r_jb-wm {
  stop-color: var(--svg-color--7c4e5c, #7C4E5C);
  stop-opacity: 0;
}

.xf9qqcbnz {
  stop-color: var(--svg-color--4eb9f4, #4EB9F4);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xsp7-kwpz {
  stop-color: var(--svg-color--3c73d6, #3C73D6);
}

.xsu_qdbmh {
  stop-color: var(--svg-color--4188d4, #4188D4);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y7qu51ufm {
  d: path("M10.444 14.557a1.9 1.9 0 0 1-1.036-.353v1.066c0 1.024.61 1.935 1.536 2.313a4.7 4.7 0 0 1-.396-1.351z");
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

.z_4nico_h {
  stop-color: var(--svg-color--7dc8fc, #7DC8FC);
  stop-opacity: 0;
}

.zstiy-bhq {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zy2fe0b7g {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
}

</style>
