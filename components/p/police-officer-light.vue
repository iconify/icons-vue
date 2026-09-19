<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="dee3snbxe"/><path fill="url(#i3b9cme)" class="g-3ft7k9f"/><path fill="url(#iT6XAqe)" class="g-3ft7k9f"/><path fill="url(#iTFqkvb)" class="g-3ft7k9f"/><path fill="url(#i6dLLtb)" class="g-3ft7k9f"/><g filter="url(#iZ25p9d)"><path class="w4srnfb7y"/></g><path fill="url(#iVk8ZRb)" class="thtcysb5g"/><path fill="url(#iySxojc)" class="thtcysb5g"/><path fill="url(#iBT0Egc)" class="yvy6tz2sx"/><path fill="url(#iSWq0Oc)" class="yvy6tz2sx"/><g filter="url(#iZGZ7ie)"><path fill="url(#iPxdGmJ)" class="gfcus0k-b"/><path fill="url(#iJSlXzd)" class="gfcus0k-b"/><path fill="url(#iJK0STd)" class="gfcus0k-b"/><path fill="url(#ikLUynd)" class="gfcus0k-b"/></g><path fill="url(#iOoOjsw)" class="coer9ebiy"/><path fill="url(#i4gZH3d)" class="coer9ebiy"/><path fill="url(#ihSlXYc)" class="coer9ebiy"/><g filter="url(#icKyzhe)"><path class="g0x0s6b7k"/><path fill="url(#ie1yCCd)" class="zstiy-bhq"/></g><path fill="url(#iJ1vlub)" class="zstiy-bhq"/><g filter="url(#iwiicpe)"><path class="fu5sdg_kf"/><path fill="url(#iNae8ve)" class="cjztvk1qv"/><path fill="url(#i4SYPYc)" class="cjztvk1qv"/></g><path fill="url(#io6Q47d)" class="cjztvk1qv"/><g filter="url(#i0Fu9Le)"><path fill="url(#ii91opc)" class="vnlonib2h"/><path fill="url(#in3v7nb)" class="vnlonib2h"/></g><path class="wl5mbzbrp"/><path fill="url(#i52pZlb)" class="qhm2dwfxa"/><path fill="url(#iFM7sqb)" class="voanp7bfs"/><path fill="url(#itVMs9w)" class="gw4e2-mlx"/><path fill="url(#irnVshd)" class="iz3s1ejby"/><g filter="url(#iaHg97b)"><path fill="url(#iCaZzRb)" class="hkkessire"/></g><path fill="url(#i4bwWMc)" class="hkkessire"/><path fill="url(#i9p3x8c)" class="hkkessire"/><path fill="url(#ibwYeGd)" class="hkkessire"/><path fill="url(#iNlU9Wd)" class="hkkessire"/><path fill="url(#iFg5rpd)" class="hkkessire"/><path fill="url(#iOcEZse)" class="hkkessire"/><path fill="url(#i3uKGrc)" class="hkkessire"/><path fill="url(#iG5GcUb)" class="hkkessire"/><g filter="url(#iWemuio)"><path class="nt7pcdcpf"/></g><g filter="url(#iWeqatb)"><path class="wf6rhpb2p"/><path fill="url(#iG7AOEN)" class="x9j2v7ggw"/><path fill="url(#ibj9ywb)" class="x9j2v7ggw"/><path fill="url(#i9UJVve)" class="x9j2v7ggw"/><path fill="url(#i4c1ezF)" class="x9j2v7ggw"/></g><g filter="url(#i8tP5Zb)"><path fill="url(#i0B3T5d)" class="iz_fi_baq"/></g><g filter="url(#ij3p2hd)"><path stroke="url(#iWBPLRc)" class="uunc0crwi"/></g><path fill="url(#ieVK02c)" class="ufwuw-btz"/><path class="o01e1_6oi"/><path fill="url(#iFrblpd)" class="drr8mnbiy"/><path class="sg5pofbqj"/><g filter="url(#ihcEVde)"><path class="e6an0wsxl"/><path fill="url(#igfyGOb)" class="zvgm6x-2m"/></g><g filter="url(#iIKnO1c)"><path fill="url(#iNQvNKd)" class="docbq4p7b"/></g><path class="hh5x-tu6v"/><path fill="url(#iMDctIe)" class="uih2t7qid"/><path class="jnzrt9-bi"/><g filter="url(#i7hI8ze)"><path fill="url(#iLCDbcF)" class="t6hykwu8o"/></g><g filter="url(#iHANJyd)"><ellipse transform="rotate(-27.914 13.19 11.966)" class="pm0zl6-bw"/><ellipse fill="url(#i17PzOe)" transform="rotate(-27.914 13.19 11.966)" class="ppv3oyeme"/></g><path fill="url(#iZD31dd)" class="mx2h91fbo"/><path fill="url(#iOqVaRd)" class="mx2h91fbo"/><path fill="url(#ijoOnGr)" class="mx2h91fbo"/><path fill="url(#iIw9Eub)" class="mx2h91fbo"/><path fill="url(#iESeCXc)" class="q52f3-byv"/><path fill="url(#izGFyYc)" class="q52f3-byv"/><g filter="url(#iHejuPe)"><path fill="url(#iI4qYhc)" class="lllow1nim"/></g><g filter="url(#i9D7Zpb)"><path fill="url(#iUvDZLc)" class="zmw0cp6hy"/></g><g filter="url(#iwmSjGc)"><path fill="url(#isLM7wb)" class="j2ao_sb9l"/><path fill="url(#i945GOe)" class="j2ao_sb9l"/></g><path fill="url(#iizJfPb)" class="j2ao_sb9l"/><g filter="url(#izWhaxb)"><path class="trw5-7ral"/></g><g filter="url(#iofZOve)"><path fill="url(#iBrxMjb)" class="hd5r75bzt"/></g><g filter="url(#iDv4JLG)"><path fill="url(#iIgw5Lc)" class="mtkt99emo"/><path fill="url(#i1oZv1c)" class="mtkt99emo"/></g><g filter="url(#iotVRYd)"><path clip-rule="evenodd" class="ts35s1bpk"/></g><g filter="url(#ixTJUJe)"><path fill="url(#igpewSb)" clip-rule="evenodd" class="bk_2u1bog"/></g><path fill="url(#iiEONhS)" clip-rule="evenodd" class="bk_2u1bog"/><path fill="url(#i0rO5Pe)" clip-rule="evenodd" class="bk_2u1bog"/><g filter="url(#iujfV6c)"><path fill="url(#iF5yRae)" class="g3qn2hbkl"/></g><g filter="url(#iFa8i0d)"><rect fill="url(#iySt08c)" class="f5rlg0klg"/></g><defs><radialGradient id="i3b9cme" cx="0" cy="0" r="1" gradientTransform="matrix(.59372 6.27271 -11.9943 1.13527 13.662 18.032)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ewagz7_9h"/><stop offset="1" class="a8t42xt1y"/></radialGradient><radialGradient id="iT6XAqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 0 0 14.4101 8.099 29.934)" gradientUnits="userSpaceOnUse"><stop class="vg5w9dbzr"/><stop offset="1" class="r9aql0tfq"/></radialGradient><radialGradient id="iTFqkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -12.1562 24.005 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="bglf8cb8f"/><stop offset="1" class="f1vhuirkb"/></radialGradient><radialGradient id="iVk8ZRb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -6.93362 3.8209 .51663 6.443 29.934)" gradientUnits="userSpaceOnUse"><stop class="ff-z7nbub"/><stop offset="1" class="qt_mg48rg"/></radialGradient><radialGradient id="iySxojc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -13.7094 8.287 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="a2jurmb2n"/><stop offset="1" class="xsu_qdbmh"/></radialGradient><radialGradient id="iBT0Egc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 -8.02737 2.31779 -.47822 26.443 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="f69-7cs4d"/><stop offset="1" class="xf9qqcbnz"/></radialGradient><radialGradient id="iSWq0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36307 0 0 13.6894 23.945 29.71)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="qjgh28b1y"/><stop offset=".8" class="humbo4erb"/></radialGradient><radialGradient id="iPxdGmJ" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 3.525 14.988)scale(2.34396 3.58278)" gradientUnits="userSpaceOnUse"><stop class="ni0htxbur"/><stop offset="1" class="xsp7-kwpz"/></radialGradient><radialGradient id="iJSlXzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 -1.10937 1.05865 1.5358 15.473 24.032)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nlnhxpbkx"/><stop offset="1" class="qk56hfspl"/></radialGradient><radialGradient id="iOoOjsw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71487 -1.3158 0 15.915 25.219)" gradientUnits="userSpaceOnUse"><stop class="e9hbkmbux"/><stop offset="1" class="fqfyucbrl"/></radialGradient><radialGradient id="ie1yCCd" cx="0" cy="0" r="1" gradientTransform="matrix(.6593 -2.21967 2.48774 .73893 14.283 23.669)" gradientUnits="userSpaceOnUse"><stop class="zy2fe0b7g"/><stop offset="1" class="kdz8adazd"/></radialGradient><radialGradient id="iJ1vlub" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.49506 -2.22013 -.51048 14.005 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="cxc4ijbrr"/><stop offset="1" class="sjzaf5e-a"/></radialGradient><radialGradient id="i4SYPYc" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .42188 -1.25086 1.38985 17.036 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="bzog60bkg"/><stop offset=".902" class="et8zn2bag"/></radialGradient><radialGradient id="io6Q47d" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 .875 -2.39996 2.31425 17.786 19.907)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="wt_jecb6v"/><stop offset="1" class="tp8jvfpml"/></radialGradient><radialGradient id="ii91opc" cx="0" cy="0" r="1" gradientTransform="rotate(148.065 5.885 12.705)scale(2.68809 2.30164)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="yy69dgnjz"/><stop offset="1" class="qxh-jcb9e"/></radialGradient><radialGradient id="in3v7nb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42188 .20312 -.04646 -.55397 15.349 20)" gradientUnits="userSpaceOnUse"><stop class="i39qv0blz"/><stop offset="1" class="xxn25rbwf"/></radialGradient><radialGradient id="i52pZlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2821 .3468 -.8516 -3.14834 10.27 9.781)" gradientUnits="userSpaceOnUse"><stop class="hm53t-bep"/><stop offset=".722" class="f26yiccdf"/></radialGradient><radialGradient id="iFM7sqb" cx="0" cy="0" r="1" gradientTransform="matrix(.8507 .23743 -.95836 3.43383 21.88 9.711)" gradientUnits="userSpaceOnUse"><stop class="yc7--dncc"/><stop offset="1" class="ml32ipbzu"/></radialGradient><radialGradient id="itVMs9w" cx="0" cy="0" r="1" gradientTransform="matrix(.85778 2.31353 -2.7483 1.01898 21.445 14.204)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="irnVshd" cx="0" cy="0" r="1" gradientTransform="matrix(1.6914 .53158 -1.63997 5.21808 9.062 14.766)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iCaZzRb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9889 0 0 -10.5943 19.216 13.126)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="i9p3x8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3023 -11.844 0 16.556 6.402)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="doxrpybdd"/><stop offset=".988" class="g_9wdfbqx"/></radialGradient><radialGradient id="ibwYeGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31552 1.62796 0 18.803 11.622)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iNlU9Wd" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 12.54 -.87)scale(1.25359 1.3642)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iFg5rpd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.741 7.443)scale(9.75217 24.9119)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iOcEZse" cx="0" cy="0" r="1" gradientTransform="matrix(3.54947 -3.75493 1.37457 1.29936 9.737 8.17)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="i3uKGrc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.297 9.006)scale(3.85942 3.18627)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iG5GcUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.9375 -7.375 0 15.465 10.41)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="b4lzsmbqd"/><stop offset="1" class="x3l3c-xdj"/></radialGradient><radialGradient id="ibj9ywb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .27964 -.87886 0 16.534 14.684)" gradientUnits="userSpaceOnUse"><stop class="ws182kb6d"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="i4c1ezF" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.802 8.835)scale(1.91702 3.0808)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="ieVK02c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82566 3.32183 0 16 17.18)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iFrblpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92943 -1.47836 0 18.5 12.076)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="igfyGOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26568 -.34236 .47135 -.36578 18.238 12.172)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMDctIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92948 -1.47843 0 13.5 12.076)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i17PzOe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.654 -.32)scale(.56608 .68045)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOqVaRd" cx="0" cy="0" r="1" gradientTransform="matrix(.72003 2.56985 -2.45183 .68696 21.29 12.092)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="ijoOnGr" cx="0" cy="0" r="1" gradientTransform="matrix(.90246 -1.23848 1.0381 .75645 21.703 12.716)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iIw9Eub" cx="0" cy="0" r="1" gradientTransform="matrix(.67245 -1.77612 2.37315 .89849 21.834 12.913)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="izGFyYc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.848 -.2258 .24238 -1.98375 10.369 12.83)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iI4qYhc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0499 .18022 -.22114 -1.28828 10.37 12.83)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="isLM7wb" cx="0" cy="0" r="1" gradientTransform="rotate(153.716 9.95 5.24)scale(8.88768 11.3119)" gradientUnits="userSpaceOnUse"><stop class="b5oikgndb"/><stop offset="1" class="aiodo62qb"/></radialGradient><radialGradient id="iizJfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56249 1.8125 -5.67441 -1.76097 20.88 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="lwjbbq_rp"/><stop offset="1" class="c0fdt7b4z"/></radialGradient><radialGradient id="iIgw5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.454 12.31 1.781)scale(8.75158 12.2726)" gradientUnits="userSpaceOnUse"><stop class="hg7hxmbra"/><stop offset="1" class="i8a3pvbms"/></radialGradient><radialGradient id="i1oZv1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33594 10.5987 0 15.969 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="e3kv8ccww"/><stop offset=".917" class="t9xlhbbtl"/></radialGradient><radialGradient id="iiEONhS" cx="0" cy="0" r="1" gradientTransform="rotate(101.822 7.538 11.83)scale(1.37287 11.6524)" gradientUnits="userSpaceOnUse"><stop class="q-4mmubff"/><stop offset="1" class="z_4nico_h"/></radialGradient><radialGradient id="i0rO5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(137.81 10.052 8.132)scale(2.38738 2.66614)" gradientUnits="userSpaceOnUse"><stop class="q3vx93ufn"/><stop offset="1" class="ojnx9kp9k"/></radialGradient><filter id="iZ25p9d" width="7.365" height="6.01" x="12.146" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".25"/></filter><filter id="iZGZ7ie" width="4.12" height="2.78" x="13.959" y="21.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/></filter><filter id="icKyzhe" width="3.58" height="4.539" x="12.543" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/></filter><filter id="iwiicpe" width="3.6" height="4.539" x="15.878" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/></filter><filter id="i0Fu9Le" width="4.352" height="2.805" x="13.739" y="19.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.45098 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/></filter><filter id="iaHg97b" width="12.708" height="14.338" x="10.2" y="6.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2689" result="effect2_innerShadow_4002_2689"/></filter><filter id="iWemuio" width="4.001" height="5.322" x="13.837" y="11.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".5"/></filter><filter id="iWeqatb" width="2.551" height="3.722" x="14.725" y="11.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.603922 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/><feGaussianBlur result="effect2_foregroundBlur_4002_2689" stdDeviation=".1"/></filter><filter id="i8tP5Zb" width="2.551" height="3.722" x="14.705" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".1"/></filter><filter id="ij3p2hd" width="4.187" height="1.729" x="13.906" y="15.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".05"/></filter><filter id="ihcEVde" width=".872" height=".769" x="17.673" y="11.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".05"/></filter><filter id="iIKnO1c" width=".963" height=".988" x="18.65" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".1"/></filter><filter id="i7hI8ze" width="1.072" height="1.133" x="13.56" y="11.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".1"/></filter><filter id="iHANJyd" width="1.017" height=".778" x="12.681" y="11.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".05"/></filter><filter id="iHejuPe" width="1.45" height="2.653" x="9.07" y="11.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".125"/></filter><filter id="i9D7Zpb" width="2.084" height="3.18" x="21.235" y="11.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".25"/></filter><filter id="iwmSjGc" width="16.56" height="6.934" x="7.72" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.537255 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/></filter><filter id="izWhaxb" width="2.674" height="2.948" x="14.589" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".075"/></filter><filter id="iofZOve" width="2.624" height="2.748" x="14.643" y="3.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2689" result="effect2_innerShadow_4002_2689"/></filter><filter id="iDv4JLG" width="13.155" height="4.088" x="9.342" y="7.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.207843 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2689" result="effect2_innerShadow_4002_2689"/></filter><filter id="iotVRYd" width="13.899" height="3.448" x="9.147" y="5.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2689" stdDeviation=".25"/></filter><filter id="ixTJUJe" width="14.033" height="2.72" x="9.028" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/></filter><filter id="iujfV6c" width="3.063" height="3.733" x="18.679" y="24.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2689" result="effect2_innerShadow_4002_2689"/></filter><filter id="iFa8i0d" width="4.306" height="1.334" x="8.789" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2689"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2689" result="effect2_innerShadow_4002_2689"/></filter><linearGradient id="i6dLLtb" x1="7.926" x2="8.205" y1="28.477" y2="28.477" gradientUnits="userSpaceOnUse"><stop offset=".229" class="kdpeaetya"/><stop offset="1" class="rvybbdrcw"/></linearGradient><linearGradient id="iJK0STd" x1="15.193" x2="15.497" y1="22.422" y2="22.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="ikLUynd" x1="16.404" x2="16.185" y1="22.258" y2="22.555" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="i4gZH3d" x1="17.412" x2="16.474" y1="27.875" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ahgk2rx2r"/><stop offset="1" class="nx2bsjb_t"/></linearGradient><linearGradient id="ihSlXYc" x1="14.677" x2="15.915" y1="27.11" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="yvnwtvbdk"/><stop offset="1" class="gd56libvg"/></linearGradient><linearGradient id="iNae8ve" x1="18.786" x2="17.247" y1="22.422" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="bxeumjbad"/><stop offset="1" class="c8b-jsd8k"/></linearGradient><linearGradient id="i4bwWMc" x1="21.908" x2="16.922" y1="15.056" y2="15.056" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iG7AOEN" x1="16.96" x2="16" y1="13.898" y2="13.938" gradientUnits="userSpaceOnUse"><stop class="ws182kb6d"/><stop offset="1" class="wrc-_lg0o"/></linearGradient><linearGradient id="i9UJVve" x1="16" x2="16" y1="15.203" y2="14.671" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="i0B3T5d" x1="15.98" x2="16.223" y1="11.887" y2="13.207" gradientUnits="userSpaceOnUse"><stop class="c-c0slf7r"/><stop offset="1" class="wx6_34ico"/></linearGradient><linearGradient id="iWBPLRc" x1="14.623" x2="14.988" y1="17.003" y2="16.047" gradientUnits="userSpaceOnUse"><stop class="gd-fi_kpy"/><stop offset="1" class="u-69jdbpq"/></linearGradient><linearGradient id="iNQvNKd" x1="19.391" x2="19.032" y1="12.138" y2="12.359" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLCDbcF" x1="14.353" x2="13.993" y1="12.138" y2="12.359" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZD31dd" x1="23.373" x2="21.991" y1="12.168" y2="14.662" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iESeCXc" x1="9.299" x2="10.969" y1="12.975" y2="12.829" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iUvDZLc" x1="22.277" x2="22.277" y1="11.743" y2="13.924" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="i945GOe" x1="7.318" x2="13.13" y1="7.657" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="ylhb00l1u"/><stop offset="1" class="r_91d457c"/></linearGradient><linearGradient id="iBrxMjb" x1="16.899" x2="14.793" y1="4.542" y2="4.542" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="igpewSb" x1="10.974" x2="21.755" y1="7.7" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="ilj7ybc1n"/><stop offset="1" class="p_hknfval"/></linearGradient><linearGradient id="iF5yRae" x1="21.325" x2="18.829" y1="26.246" y2="26.246" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="iySt08c" x1="13.095" x2="8.763" y1="26.864" y2="26.864" gradientUnits="userSpaceOnUse"><stop class="gxnbt7b-w"/><stop offset="1" class="vhpcois2a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:police-officer-light" /></template>
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

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.ahgk2rx2r {
  stop-color: var(--svg-color--4a88df, #4A88DF);
}

.aiodo62qb {
  stop-color: var(--svg-color--328fdd, #328FDD);
}

.b4lzsmbqd {
  stop-color: var(--svg-color--b37c7b, #B37C7B);
}

.b5oikgndb {
  stop-color: var(--svg-color--48a8fb, #48A8FB);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bglf8cb8f {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
}

.bk_2u1bog {
  fill-rule: evenodd;
  d: path("M21.92 8.962c-5.062-1.854-10-.764-11.82-.011a.775.775 0 0 1-.593-1.432c2.085-.862 7.433-2.032 12.946-.012a.775.775 0 1 1-.533 1.455");
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.bxeumjbad {
  stop-color: var(--svg-color--8be8ff, #8BE8FF);
}

.bzog60bkg {
  stop-color: var(--svg-color--639be0, #639BE0);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c-c0slf7r {
  stop-color: var(--svg-color--c5918a, #C5918A);
}

.c0fdt7b4z {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
  stop-opacity: 0;
}

.c8b-jsd8k {
  stop-color: var(--svg-color--75c1ff, #75C1FF);
  stop-opacity: 0;
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

.cxc4ijbrr {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
}

.dee3snbxe {
  fill: var(--svg-color--3fb3ff, #3FB3FF);
  d: path("M3.862 29.934h24.276c-.466-6.296-5.723-11.26-12.138-11.26S4.328 23.639 3.862 29.935");
}

.docbq4p7b {
  d: path("M19.413 12.418a.96.96 0 0 0-.265-.53l-.298.326l.134.262z");
}

.doxrpybdd {
  stop-color: var(--svg-color--cd96a0, #CD96A0);
  stop-opacity: 0;
}

.drr8mnbiy {
  d: path("M18.502 11.53a1.022 1.022 0 0 1 .985 1.291h-1.975a1.026 1.026 0 0 1 .99-1.292");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3kv8ccww {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
  stop-opacity: 0;
}

.e6an0wsxl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.427 11.746c.073.097-.08.216-.253.345c-.173.13-.301.22-.374.123s.008-.281.181-.41c.173-.13.373-.156.446-.059");
}

.e9hbkmbux {
  stop-color: var(--svg-color--3f7cd5, #3F7CD5);
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
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

.f26yiccdf {
  stop-color: var(--svg-color--454040, #454040);
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

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
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

.g_9wdfbqx {
  stop-color: var(--svg-color--b888a5, #B888A5);
}

.g-3ft7k9f {
  d: path("M3.862 29.934h24.276c-.466-6.296-5.723-11.26-12.138-11.26S4.328 23.639 3.862 29.935");
}

.g0x0s6b7k {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.g3qn2hbkl {
  d: path("M18.83 24.93a.5.5 0 0 1 .5-.5h1.812a.5.5 0 0 1 .5.5v1.727a1.406 1.406 0 0 1-2.813 0z");
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gd-fi_kpy {
  stop-color: var(--svg-color--f0c2bb, #F0C2BB);
}

.gd56libvg {
  stop-color: var(--svg-color--3169c8, #3169C8);
  stop-opacity: 0;
}

.gfcus0k-b {
  d: path("M16.749 24.47a.25.25 0 0 1-.224.139h-1.097a.25.25 0 0 1-.223-.139l-1.246-2.491h4.02z");
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gw4e2-mlx {
  d: path("M21.569 14.557a1.9 1.9 0 0 0 1.036-.353v1.066c0 1.024-.61 1.935-1.536 2.313a4.7 4.7 0 0 0 .396-1.351z");
}

.gxnbt7b-w {
  stop-color: var(--svg-color--ffd04c, #FFD04C);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hd5r75bzt {
  d: path("M14.793 3.757v.922a1.187 1.187 0 0 0 2.374 0v-.924a.2.2 0 0 0-.308-.168l-.252.16a.1.1 0 0 1-.134-.025l-.295-.402a.25.25 0 0 0-.404 0l-.29.401a.1.1 0 0 1-.136.025l-.247-.158a.2.2 0 0 0-.308.169");
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

.hkkessire {
  d: path("M10.473 16.293a4.486 4.486 0 0 0 4.451 3.902h2.161a4.486 4.486 0 0 0 4.452-3.902c.135-2.158.27-4.307.37-6.464a1.66 1.66 0 0 0-1.579-1.64h-1.604a2.78 2.78 0 0 1-2.533-1.653a.76.76 0 0 0-.705-.48h-1.459c-2.114 0-3.827 1.733-3.827 3.871c0 2.132.133 4.23.273 6.366");
}

.hm53t-bep {
  stop-color: var(--svg-color--0c040a, #0C040A);
}

.humbo4erb {
  stop-color: var(--svg-color--189cf0, #189CF0);
  stop-opacity: 0;
}

.i39qv0blz {
  stop-color: var(--svg-color--b7899d, #B7899D);
}

.i8a3pvbms {
  stop-color: var(--svg-color--46395b, #46395B);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ilj7ybc1n {
  stop-color: var(--svg-color--73b8f6, #73B8F6);
}

.iz_fi_baq {
  d: path("m15.542 12.237l-.609 2.106c-.124.434.174.867.597.867h.9c.423 0 .721-.44.597-.867l-.609-2.106c-.13-.466-.74-.466-.876 0");
}

.iz3s1ejby {
  d: path("M10.431 14.557a1.9 1.9 0 0 1-1.036-.353v1.066c0 1.024.61 1.935 1.536 2.313a4.7 4.7 0 0 1-.396-1.351z");
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j2ao_sb9l {
  d: path("M8.797 4.266c-.625.258-1.356 1.025-.969 2.375s.526 1.802.547 1.86c.04.166.223.5.633.5h.39a.46.46 0 0 0 .301-.134c.142-.134 2.254-1.596 5.827-1.718c3.645.122 6.633 1.584 6.775 1.718a.45.45 0 0 0 .3.133h.391c.41 0 .593-.333.633-.5c.02-.057.16-.51.547-1.86s-.344-2.116-.969-2.374l-5.21-1.853a6 6 0 0 0-4.032.004z");
}

.j3cbwjknw {
  stop-color: var(--svg-color--ffd24b, #FFD24B);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jnzrt9-bi {
  fill: var(--svg-color--000, #000);
  d: path("M14.084 12.552a.583.583 0 0 0-.586-.585a.583.583 0 0 0-.52.855h1.036a.6.6 0 0 0 .07-.27");
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

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lllow1nim {
  d: path("M10.174 11.753a1.095 1.095 0 0 0 .096 2.153a90 90 0 0 1-.096-2.153");
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lwjbbq_rp {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.ml32ipbzu {
  stop-color: var(--svg-color--434042, #434042);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
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

.nt7pcdcpf {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.54 12.525l-.677 2.106c-.115.434.162.867.555.867h.838c.394 0 .671-.44.555-.867l-.566-2.106c-.121-.466-.578-.466-.705 0");
}

.nx2bsjb_t {
  stop-color: var(--svg-color--4a88df, #4A88DF);
  stop-opacity: 0;
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o01e1_6oi {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.74 11.218a1.6 1.6 0 0 1 1.551 1.213c.051.2-.102.39-.306.39h-2.556a.264.264 0 0 1-.26-.311a1.6 1.6 0 0 1 1.57-1.292");
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojnx9kp9k {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
  stop-opacity: 0;
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

.ppv3oyeme {
  cx: 13.19px;
  cy: 11.966px;
  rx: 0.446px;
  ry: 0.226px;
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q-4mmubff {
  stop-color: var(--svg-color--87ddff, #87DDFF);
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q3vx93ufn {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
}

.q52f3-byv {
  d: path("M10.221 10.996a1.854 1.854 0 0 0-1.594 1.826c0 .984.77 1.788 1.742 1.84a90 90 0 0 1-.148-3.666");
}

.qhm2dwfxa {
  d: path("M9.02 9.797c-.153-.45-.262-.89-.31-1.117h1.79v3.273H9.219v-1.195c0-.355-.074-.59-.2-.96");
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

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxh-jcb9e {
  stop-color: var(--svg-color--b98e9a, #B98E9A);
}

.r_91d457c {
  stop-color: var(--svg-color--4389d1, #4389D1);
  stop-opacity: 0;
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.r9aql0tfq {
  stop-color: var(--svg-color--30acff, #30ACFF);
  stop-opacity: 0;
}

.rvybbdrcw {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
  stop-opacity: 0;
}

.sg5pofbqj {
  fill: var(--svg-color--000, #000);
  d: path("M17.917 12.552c0-.325.26-.585.585-.585a.583.583 0 0 1 .52.855h-1.036a.53.53 0 0 1-.07-.27");
}

.sjzaf5e-a {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
  stop-opacity: 0;
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t6hykwu8o {
  d: path("M14.432 12.432c0-.33-.268-.55-.341-.617l-.33.32l.203.413z");
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

.u-69jdbpq {
  stop-color: var(--svg-color--f0c2bb, #F0C2BB);
  stop-opacity: 0;
}

.ufwuw-btz {
  d: path("M16 16.444a3.44 3.44 0 0 1-1.587-.377c-.157-.08-.326.097-.227.24c.384.581 1.052.969 1.814.969s1.43-.388 1.814-.97c.099-.147-.07-.318-.227-.239c-.46.24-1 .377-1.587.377");
}

.uih2t7qid {
  d: path("M13.498 11.53a1.022 1.022 0 0 0-.985 1.292h1.975a1 1 0 0 0 .037-.27a1.03 1.03 0 0 0-1.027-1.022");
}

.uunc0crwi {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.448 16h-.001a.25.25 0 0 0-.298.052a.23.23 0 0 0-.025.297A2.24 2.24 0 0 0 16 17.35c.787 0 1.48-.4 1.876-1.003a.234.234 0 0 0-.026-.298a.25.25 0 0 0-.297-.05A3.35 3.35 0 0 1 16 16.37c-.57 0-1.104-.134-1.553-.368Z");
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.vg5w9dbzr {
  stop-color: var(--svg-color--30acff, #30ACFF);
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vhpcois2a {
  stop-color: var(--svg-color--ffcd47, #FFCD47);
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vnlonib2h {
  d: path("M13.74 19.832c.21.57.812 1.582 2.206 2.223c1.454-.75 1.934-1.652 2.145-2.223l-2.145-.332z");
}

.voanp7bfs {
  d: path("M22.809 9.836c.168-.39.394-.808.48-1.156h-1.945v3.273h1.281v-1.195c-.013-.17.041-.59.184-.922");
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w4srnfb7y {
  fill: var(--svg-color--2389d6, #2389D6);
  d: path("m12.646 19.685l.763 3.8a.41.41 0 0 0 .662.242l.452-.364l.601 1.204c.04.079.12.128.208.128h1.021c.089 0 .17-.05.21-.13l.586-1.187l.437.349a.41.41 0 0 0 .661-.242l.764-3.8z");
}

.wf6rhpb2p {
  fill: var(--svg-color--dda99b, #DDA99B);
  d: path("m15.562 12.307l-.609 2.106c-.124.433.174.866.597.866h.9c.423 0 .721-.44.597-.866l-.609-2.106c-.13-.467-.74-.467-.876 0");
}

.wl5mbzbrp {
  stroke: var(--svg-color--d37034, #D37034);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-627px, 0.627px);
  d: path("M12.08 10.069s.77-.59 1.9-.46m5.94.46s-.77-.59-1.9-.46");
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wrc-_lg0o {
  stop-color: var(--svg-color--facbb7, #FACBB7);
  stop-opacity: 0;
}

.ws182kb6d {
  stop-color: var(--svg-color--facbb7, #FACBB7);
}

.wt_jecb6v {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
}

.wx6_34ico {
  stop-color: var(--svg-color--c5918a, #C5918A);
  stop-opacity: 0;
}

.x3l3c-xdj {
  stop-color: var(--svg-color--b37c7b, #B37C7B);
  stop-opacity: 0;
}

.x9j2v7ggw {
  d: path("m15.562 12.307l-.609 2.106c-.124.433.174.866.597.866h.9c.423 0 .721-.44.597-.866l-.609-2.106c-.13-.467-.74-.467-.876 0");
}

.xf9qqcbnz {
  stop-color: var(--svg-color--4eb9f4, #4EB9F4);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xsp7-kwpz {
  stop-color: var(--svg-color--3c73d6, #3C73D6);
}

.xsu_qdbmh {
  stop-color: var(--svg-color--4188d4, #4188D4);
  stop-opacity: 0;
}

.xxn25rbwf {
  stop-color: var(--svg-color--b7899d, #B7899D);
  stop-opacity: 0;
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yc7--dncc {
  stop-color: var(--svg-color--150f1a, #150F1A);
}

.ylhb00l1u {
  stop-color: var(--svg-color--4389d1, #4389D1);
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yvnwtvbdk {
  stop-color: var(--svg-color--3169c8, #3169C8);
}

.yvy6tz2sx {
  d: path("M23.945 29.934h4.193a12.15 12.15 0 0 0-4.193-8.309z");
}

.yy69dgnjz {
  stop-color: var(--svg-color--c09aa7, #C09AA7);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z_4nico_h {
  stop-color: var(--svg-color--7dc8fc, #7DC8FC);
  stop-opacity: 0;
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.zmw0cp6hy {
  d: path("M21.735 13.924q.066-1.09.126-2.18a1.095 1.095 0 0 1-.127 2.18");
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zstiy-bhq {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.zvgm6x-2m {
  d: path("M18.427 11.746c.073.097-.08.216-.253.345c-.173.13-.301.22-.374.123s.008-.281.181-.41c.173-.13.373-.156.446-.059");
}

.zy2fe0b7g {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
}

</style>
