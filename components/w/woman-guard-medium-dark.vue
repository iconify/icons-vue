<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixIzZps)"><path fill="url(#invM5Tc)" clip-rule="evenodd" class="j8jqlbb0d"/><path fill="url(#icGOEce)" clip-rule="evenodd" class="j8jqlbb0d"/><path fill="url(#icWDPnc)" clip-rule="evenodd" class="j8jqlbb0d"/><path fill="url(#icegWCp)" clip-rule="evenodd" class="j8jqlbb0d"/><path fill="url(#icwcqTd)" clip-rule="evenodd" class="j8jqlbb0d"/><path fill="url(#iPBGrzb)" clip-rule="evenodd" class="j8jqlbb0d"/><path fill="url(#iw1UPpR)" clip-rule="evenodd" class="j8jqlbb0d"/><path fill="url(#i9U7ysd)" clip-rule="evenodd" class="j8jqlbb0d"/><path fill="url(#immBJtd)" clip-rule="evenodd" class="j8jqlbb0d"/><path fill="url(#i0GxRHB)" clip-rule="evenodd" class="j8jqlbb0d"/><path fill="url(#i7Loebc)" clip-rule="evenodd" class="j8jqlbb0d"/></g><path fill="url(#ipxqfNb)" class="c5pyn6kwp"/><path fill="url(#ixtGmqe)" class="c5pyn6kwp"/><path fill="url(#iu4BL0y)" class="c5pyn6kwp"/><path fill="url(#i6kQckA)" class="c5pyn6kwp"/><path fill="url(#ivcbSbu)" class="d42a8nbyx"/><path fill="url(#imxslwc)" class="d42a8nbyx"/><path fill="url(#iCIPAvc)" class="sy7gbya4q"/><path fill="url(#ib2sn4d)" class="sy7gbya4q"/><g filter="url(#ijmi1Td)"><path fill="url(#i6aJFZY)" class="cd8uxyblt"/><path fill="url(#izDA0dI)" class="cd8uxyblt"/></g><g filter="url(#ibL7Ieb)"><path class="v7lobvb0w"/><path fill="url(#i4dkT0d)" class="blsopp2mg"/><path fill="url(#izjH7xz)" class="blsopp2mg"/></g><g filter="url(#iCg3Ndb)"><ellipse transform="rotate(-40.534 9.937 22.244)" class="a_d5m7-5r"/></g><ellipse fill="url(#iuxxmBb)" transform="rotate(-40.534 9.886 22.154)" class="fvifkjh5i"/><g filter="url(#icmUkmc)"><ellipse transform="scale(-1 1)rotate(-35.343 23.849 45.555)" class="n11xmqb_x"/></g><ellipse fill="url(#imtwsXc)" transform="scale(-1 1)rotate(-40.534 18.955 40.983)" class="tto44ccna"/><g filter="url(#irRyMye)"><rect fill="url(#i1U54LR)" class="qyeoy6a8h"/><rect fill="url(#iZgh3lf)" class="qyeoy6a8h"/><rect fill="url(#i7g7vQc)" class="qyeoy6a8h"/></g><rect fill="url(#iJEN6Ld)" class="gx_0zqbtq"/><path fill="url(#iYKVIWb)" class="g4mvl20po"/><path fill="url(#iDWpPDG)" class="g4mvl20po"/><g filter="url(#iOwmJIe)"><circle class="wfn54lnxd"/></g><g filter="url(#ifb7b2m)"><circle class="a1tpsrb8u"/></g><circle fill="url(#iYFehJc)" class="sx6q1cbyi"/><circle fill="url(#iO6rBqd)" class="cad66eb8i"/><path fill="url(#iGfMeIc)" class="if6aw8aev"/><path fill="url(#isLpFne)" class="yk-5cub9i"/><g filter="url(#ivZB75b)"><path fill="url(#iIaq9Kd)" class="r-si_bcfj"/></g><g filter="url(#iq9gC9b)"><path fill="url(#ipuzIbb)" class="by17racky"/><path fill="url(#inCOyBb)" class="by17racky"/></g><g filter="url(#irhnFSd)"><path class="uvchl_awx"/><path fill="url(#iPnEwrc)" class="vpjcd0g0f"/></g><g filter="url(#i7ae5Mb)"><path class="z6iphy9ix"/><path fill="url(#iQephTK)" class="wbznmcc5b"/></g><g filter="url(#ikg3fvd)"><path fill="url(#iWtyUEc)" class="u0x9jkbaj"/><path fill="url(#iiyg4Zf)" class="u0x9jkbaj"/><path fill="url(#ipxJUzd)" class="u0x9jkbaj"/><path fill="url(#iKsX9ie)" class="u0x9jkbaj"/><path fill="url(#iE6Rrpt)" class="u0x9jkbaj"/><path fill="url(#iL0Clzc)" class="u0x9jkbaj"/><path fill="url(#i1bqbec)" class="u0x9jkbaj"/><path fill="url(#ijPA4xb)" class="u0x9jkbaj"/><path fill="url(#idHVFMb)" class="u0x9jkbaj"/><path fill="url(#iVuLExc)" class="u0x9jkbaj"/></g><g filter="url(#iKoCDFd)"><path class="akxip8blo"/></g><g filter="url(#iZaZimb)"><path class="rkgptdbvw"/><path fill="url(#iKg6oud)" class="xsp4el_pm"/><path fill="url(#iBz8EGc)" class="xsp4el_pm"/><path fill="url(#i6fxUQt)" class="xsp4el_pm"/><path fill="url(#ioXCNwe)" class="xsp4el_pm"/></g><g filter="url(#ilORXhO)"><path fill="url(#iHjXQuc)" class="s3k_zbcpk"/></g><g filter="url(#iWmuecE)"><path stroke="url(#iEWhhId)" class="tp3bk41gk"/></g><path class="xot27n23k"/><g filter="url(#iPwb4rd)"><path class="s08-k72_q"/></g><g filter="url(#iUHmRae)"><path class="bdtcw4opv"/></g><path class="gyjyprgdx"/><path fill="url(#iPLkWld)" class="kdpg5wb4q"/><path class="vtqz0ebiy"/><g filter="url(#iGmp6ob)"><path class="oec0hiady"/><path fill="url(#ifv1AZd)" class="islivlshr"/></g><g filter="url(#icAF3Fb)"><path fill="url(#inJpcNb)" class="kyp1p1brp"/></g><path class="lx0z_99ht"/><path fill="url(#iQhsHgc)" class="eri3_1v2e"/><path class="h8p890bck"/><g filter="url(#iCaKSZE)"><path fill="url(#iAR9Hyd)" class="l3sthbi5n"/></g><g filter="url(#iNO7Xwd)"><ellipse transform="rotate(-27.914 13.487 14.869)" class="pbo3-6hfl"/><ellipse fill="url(#iOjwrUG)" transform="rotate(-27.914 13.487 14.869)" class="k6z9s2btf"/></g><g filter="url(#i5plImG)"><path fill="url(#iyKRZUc)" class="vim75kb4b"/><path fill="url(#iC5hH6b)" class="vim75kb4b"/></g><path fill="url(#iWLVOVc)" class="vim75kb4b"/><path fill="url(#i2pBBLt)" class="vim75kb4b"/><path fill="url(#isYcgqc)" class="vim75kb4b"/><g filter="url(#ii9y9zd)"><path fill="url(#iU1wwRb)" class="u17l1bw1n"/><path fill="url(#i7n11Wc)" class="u17l1bw1n"/><path fill="url(#iyBJvOb)" class="u17l1bw1n"/></g><defs><radialGradient id="icGOEce" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.638 18.063)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="icWDPnc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.823 18.331)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="icegWCp" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.648 10.633)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="icwcqTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 1.917 10.116)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iPBGrzb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 0 14.032)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iw1UPpR" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.902 9.3)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="i9U7ysd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.45 14.71)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="immBJtd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.307 10.471)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="i0GxRHB" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.728 -1.256)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i7Loebc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.798 14.675)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ipxqfNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71875 -19.3424 0 16 26.99)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="u2-vnsrzx"/><stop offset="1" class="u25v0cb4e"/></radialGradient><radialGradient id="ixtGmqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 0 0 -8.81836 22.928 27.146)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hztqsacfn"/><stop offset="1" class="g15tcgc_e"/></radialGradient><radialGradient id="ivcbSbu" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -8.07812 2.82155 .68765 6.74 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="y6ictpbdv"/><stop offset="1" class="exer9ybqp"/></radialGradient><radialGradient id="iCIPAvc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.449 24.978 4.727)scale(7.55662 1.96679)" gradientUnits="userSpaceOnUse"><stop class="z2ubpb-up"/><stop offset="1" class="icppbwd3b"/></radialGradient><radialGradient id="ib2sn4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.366 .65507 0 22.942 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="p9dhe0cfb"/><stop offset="1" class="m7r_2tbtp"/></radialGradient><radialGradient id="i6aJFZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -3.29137 2.72714 9.71 21.208)" gradientUnits="userSpaceOnUse"><stop class="tuvqdtb4j"/><stop offset="1" class="mw-6yhbvl"/></radialGradient><radialGradient id="izDA0dI" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.85937 -.47826 .45816 8.381 22.458)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="aok9j0bwd"/><stop offset="1" class="ul3ws4blr"/></radialGradient><radialGradient id="i4dkT0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 .25 -.73637 3.86594 19.569 21.146)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="wcylmi-4x"/><stop offset="1" class="lcybi9bke"/></radialGradient><radialGradient id="izjH7xz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 1.09375 -.16383 -.18256 23.498 22.2)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iuxxmBb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.136 6.388 10.772)scale(1.64141 .91814)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="k5s0mt74t"/><stop offset="1" class="hfobxebps"/></radialGradient><radialGradient id="imtwsXc" cx="0" cy="0" r="1" gradientTransform="matrix(.678 .80592 -1.4278 1.20118 .1 .257)" gradientUnits="userSpaceOnUse"><stop class="w_-x-cc4i"/><stop offset="1" class="xbkp5vbln"/></radialGradient><radialGradient id="i1U54LR" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68749 -3.76563 4.9287 -3.51755 18.1 23.911)" gradientUnits="userSpaceOnUse"><stop class="mg6vw6bqp"/><stop offset="1" class="f_x1tcb5s"/></radialGradient><radialGradient id="iZgh3lf" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 0 0 -.91123 15.538 23.763)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="w_5lucbuv"/><stop offset="1" class="x_olikxjr"/></radialGradient><radialGradient id="i7g7vQc" cx="0" cy="0" r="1" gradientTransform="rotate(74.046 -5.836 21.01)scale(2.11262 4.94248)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="ay981bbmw"/><stop offset="1" class="co8373ibr"/></radialGradient><radialGradient id="iJEN6Ld" cx="0" cy="0" r="1" gradientTransform="rotate(51.989 -14.741 27.087)scale(1.72534 2.83656)" gradientUnits="userSpaceOnUse"><stop class="ysqyevbom"/><stop offset="1" class="kow5dvneo"/></radialGradient><radialGradient id="iYFehJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 25.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iO6rBqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 28.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="ipuzIbb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 19.98 16.001)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="inCOyBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.01 13.88)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iPnEwrc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.332 15.675)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iQephTK" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.572 7.781)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iWtyUEc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.637 14.921)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iiyg4Zf" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.216 9.754)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="ipxJUzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.616 21.429)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iKsX9ie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28468 7.37319 -9.2164 -1.60583 16.801 14.505)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="iE6Rrpt" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.985 9.18)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iL0Clzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.08 14.503)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="i1bqbec" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.702 14.274)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="ijPA4xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.161 12.187)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="idHVFMb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65626 4.28124 -8.65284 -7.3897 16.362 16.435)" gradientUnits="userSpaceOnUse"><stop offset=".749" class="x8fxfrb0v"/><stop offset="1" class="goba2hjxe"/></radialGradient><radialGradient id="iKg6oud" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.724 16.82)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="ioXCNwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.485 17.032)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iPLkWld" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.12773 1.22387 0 18.122 15.616)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="qqi15ibyg"/><stop offset="1" class="p6c0n1b2f"/></radialGradient><radialGradient id="ifv1AZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.894 15.05)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQhsHgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.12774 1.22388 0 13.758 15.616)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="qqi15ibyg"/><stop offset="1" class="p6c0n1b2f"/></radialGradient><radialGradient id="iOjwrUG" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.21 .96)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWLVOVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3535 18.2706 0 15.953 14.155)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="guwslmx9m"/><stop offset="1" class="csva0fh9x"/></radialGradient><radialGradient id="i2pBBLt" cx="0" cy="0" r="1" gradientTransform="rotate(-179.736 10.798 2.33)scale(6.78132 1.9151)" gradientUnits="userSpaceOnUse"><stop class="ak4i8vy1v"/><stop offset="1" class="d0nv29baz"/></radialGradient><radialGradient id="iyBJvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46875 -.51569 0 21.381 16.27)" gradientUnits="userSpaceOnUse"><stop class="qqll8tbvj"/><stop offset="1" class="i1pxvjzop"/></radialGradient><filter id="ixIzZps" width="15.268" height="15.768" x="8.431" y="6.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/></filter><filter id="ijmi1Td" width="4.755" height="3.491" x="8.464" y="20.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/></filter><filter id="ibL7Ieb" width="4.705" height="3.591" x="18.753" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.0666667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2841" result="effect2_innerShadow_4002_2841"/></filter><filter id="iCg3Ndb" width="2.189" height="2.153" x="8.842" y="21.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".25"/></filter><filter id="icmUkmc" width="1.692" height="1.595" x="21.111" y="21.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".125"/></filter><filter id="irRyMye" width="7.744" height="9.694" x="12.072" y="14.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2841" result="effect2_innerShadow_4002_2841"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.172549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2841" result="effect3_innerShadow_4002_2841"/></filter><filter id="iOwmJIe" width="2.09" height="2.09" x="16.395" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".25"/></filter><filter id="ifb7b2m" width="2.09" height="2.09" x="16.395" y="27.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".25"/></filter><filter id="ivZB75b" width="3.368" height="3.218" x="9.45" y="13.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/></filter><filter id="iq9gC9b" width="3.218" height="3.468" x="19.159" y="13.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/></filter><filter id="irhnFSd" width="3.148" height="3.148" x="19.194" y="13.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".25"/></filter><filter id="i7ae5Mb" width="2.648" height="2.648" x="9.755" y="14.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".125"/></filter><filter id="ikg3fvd" width="10.791" height="11.277" x="10.083" y="10.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy="-.15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2841" result="effect2_innerShadow_4002_2841"/></filter><filter id="iKoCDFd" width="2.877" height="3.682" x="14.339" y="14.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".25"/></filter><filter id="iZaZimb" width="2.377" height="3.182" x="14.752" y="14.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".125"/></filter><filter id="ilORXhO" width="2.377" height="3.182" x="14.752" y="14.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".125"/></filter><filter id="iWmuecE" width="3.702" height="1.526" x="14.089" y="17.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".05"/></filter><filter id="iPwb4rd" width="2.901" height="1.285" x="16.983" y="14.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/></filter><filter id="iUHmRae" width="2.901" height="1.285" x="11.997" y="14.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/></filter><filter id="iGmp6ob" width=".787" height=".696" x="17.388" y="14.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".05"/></filter><filter id="icAF3Fb" width=".891" height=".913" x="18.228" y="14.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".1"/></filter><filter id="iCaKSZE" width=".986" height="1.04" x="13.785" y="14.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".1"/></filter><filter id="iNO7Xwd" width=".913" height=".705" x="13.03" y="14.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2841" stdDeviation=".05"/></filter><filter id="i5plImG" width="13.655" height="12.317" x="9.076" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/></filter><filter id="ii9y9zd" width="10.882" height="7.996" x="10.499" y="14.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.635294 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2841"/></filter><linearGradient id="invM5Tc" x1="20.634" x2="13.829" y1="8.61" y2="21.214" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iu4BL0y" x1="9.026" x2="9.233" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="g-00mbcgn"/><stop offset="1" class="tvzw53atw"/></linearGradient><linearGradient id="i6kQckA" x1="22.975" x2="22.827" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yacpd-mqw"/><stop offset="1" class="m2jbcqdpu"/></linearGradient><linearGradient id="imxslwc" x1="9.397" x2="8.084" y1="29.739" y2="29.739" gradientUnits="userSpaceOnUse"><stop class="s2ol_bbam"/><stop offset="1" class="hm-si4p_s"/></linearGradient><linearGradient id="iYKVIWb" x1="15.984" x2="15.984" y1="23.197" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ty59qw5cn"/><stop offset="1" class="jwfvhhlnv"/></linearGradient><linearGradient id="iDWpPDG" x1="16.479" x2="16.147" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="z_332kbzw"/><stop offset="1" class="v6fzn4zbl"/></linearGradient><linearGradient id="iGfMeIc" x1="8.784" x2="23.16" y1="20.372" y2="20.372" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="isLpFne" x1="8.784" x2="23.16" y1="20.341" y2="20.341" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iIaq9Kd" x1="9.501" x2="10.742" y1="15.649" y2="15.649" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iVuLExc" x1="15.778" x2="15.778" y1="13.935" y2="15.623" gradientUnits="userSpaceOnUse"><stop class="vfxe67bao"/><stop offset="1" class="c41x1lbvu"/></linearGradient><linearGradient id="iBz8EGc" x1="15.002" x2="15.94" y1="16.893" y2="16.893" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="i6fxUQt" x1="15.94" x2="15.94" y1="17.692" y2="17.082" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iHjXQuc" x1="15.94" x2="16.151" y1="14.848" y2="16.24" gradientUnits="userSpaceOnUse"><stop class="heiw8ibhs"/><stop offset="1" class="rtr42sbok"/></linearGradient><linearGradient id="iEWhhId" x1="14.876" x2="15.337" y1="19.102" y2="18.39" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="inJpcNb" x1="18.9" x2="18.587" y1="15.019" y2="15.212" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAR9Hyd" x1="14.502" x2="14.188" y1="15.019" y2="15.212" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyKRZUc" x1="19.866" x2="12.585" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="j8rdzr3lb"/><stop offset=".554" class="h5foydtlz"/><stop offset="1" class="roy3-sbpo"/></linearGradient><linearGradient id="iC5hH6b" x1="9.71" x2="12.428" y1="11.989" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="bamb_e30h"/><stop offset="1" class="szoje-bkc"/></linearGradient><linearGradient id="isYcgqc" x1="16.538" x2="16.538" y1="14.155" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="ip1t-iw4f"/><stop offset="1" class="l0ic_xblz"/></linearGradient><linearGradient id="iU1wwRb" x1="21.116" x2="15.022" y1="18.489" y2="18.489" gradientUnits="userSpaceOnUse"><stop class="it4bksbcb"/><stop offset="1" class="twe7w31pl"/></linearGradient><linearGradient id="i7n11Wc" x1="15.94" x2="15.94" y1="13.927" y2="16.029" gradientUnits="userSpaceOnUse"><stop class="x-67tmbrg"/><stop offset="1" class="bkz397hyg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-guard-medium-dark" /></template>
<style>
.a_d5m7-5r {
  cx: 9.937px;
  cy: 22.244px;
  fill: var(--svg-color--321f22, #321F22);
  rx: 0.641px;
  ry: 0.524px;
}

.a1tpsrb8u {
  cx: 17.439px;
  cy: 28.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ak4i8vy1v {
  stop-color: var(--svg-color--686070, #686070);
}

.akxip8blo {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.548 15.34l-.684 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.494-.376-.613 0");
}

.aok9j0bwd {
  stop-color: var(--svg-color--4b4551, #4B4551);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.ay981bbmw {
  stop-color: var(--svg-color--452139, #452139);
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bamb_e30h {
  stop-color: var(--svg-color--4d4c50, #4D4C50);
}

.bdtcw4opv {
  fill: var(--svg-color--5d5c5e, #5D5C5E);
  d: path("M14.799 14.993c-.266-.467-.67-.835-1.538-.835c-.38 0-.747.105-1.073.368c-.269.217-.232.495-.024.6l.556.317c.651-.21 1.372-.24 2.079-.45");
}

.bkz397hyg {
  stop-color: var(--svg-color--c7aed9, #C7AED9);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.blsopp2mg {
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.by17racky {
  d: path("M20.768 17.171a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c41x1lbvu {
  stop-color: var(--svg-color--6c3c43, #6C3C43);
  stop-opacity: 0;
}

.c5pyn6kwp {
  d: path("M5.428 29.911h21.144c-.19-5.356-4.591-9.64-9.994-9.64h-1.156c-5.403 0-9.805 4.284-9.994 9.64");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cad66eb8i {
  cx: 17.494px;
  cy: 28.374px;
  r: 0.545px;
}

.cd8uxyblt {
  d: path("M11.926 20.161c-1.363.418-2.538 1.308-3.179 1.936a.46.46 0 0 0 .011.659l.65.649a.523.523 0 0 0 .705.02a12.3 12.3 0 0 1 3.106-1.857z");
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

.co8373ibr {
  stop-color: var(--svg-color--452139, #452139);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.csva0fh9x {
  stop-color: var(--svg-color--403947, #403947);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d0nv29baz {
  stop-color: var(--svg-color--686070, #686070);
  stop-opacity: 0;
}

.d42a8nbyx {
  d: path("M9.058 29.911h-3.63a9.98 9.98 0 0 1 3.63-7.355z");
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dwh48tz1p {
  stop-color: var(--svg-color--5e5864, #5E5864);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e2y-fbcxj {
  stop-color: var(--svg-color--fca239, #FCA239);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eri3_1v2e {
  d: path("M13.756 14.488a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.exer9ybqp {
  stop-color: var(--svg-color--b13b50, #B13B50);
}

.f_x1tcb5s {
  stop-color: var(--svg-color--482949, #482949);
}

.ft5dv1b6b {
  fill: none;
}

.fvifkjh5i {
  cx: 9.886px;
  cy: 22.154px;
  rx: 0.641px;
  ry: 0.524px;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g-00mbcgn {
  stop-color: var(--svg-color--c2254a, #C2254A);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g15tcgc_e {
  stop-color: var(--svg-color--ff6085, #FF6085);
  stop-opacity: 0;
}

.g4mvl20po {
  d: path("M15.49 23.203v6.708h.989v-6.714a2 2 0 0 1-.409.042h-.203q-.194 0-.377-.036");
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.goba2hjxe {
  stop-color: var(--svg-color--83406e, #83406E);
}

.guwslmx9m {
  stop-color: var(--svg-color--403947, #403947);
  stop-opacity: 0;
}

.gx_0zqbtq {
  width: 4.141px;
  height: 5.141px;
  x: 13.898px;
  y: 18.099px;
  rx: 1.969px;
}

.gyjyprgdx {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.331 14.216c.654 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h5foydtlz {
  stop-color: var(--svg-color--4b3c5b, #4B3C5B);
}

.h8p890bck {
  fill: var(--svg-color--000, #000);
  d: path("M14.267 15.38a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.heiw8ibhs {
  stop-color: var(--svg-color--77494b, #77494B);
}

.hfobxebps {
  stop-color: var(--svg-color--dcb144, #DCB144);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hm-si4p_s {
  stop-color: var(--svg-color--c9345b, #C9345B);
  stop-opacity: 0;
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hztqsacfn {
  stop-color: var(--svg-color--ff6085, #FF6085);
}

.i1pxvjzop {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
  stop-opacity: 0;
}

.icppbwd3b {
  stop-color: var(--svg-color--e34c67, #E34C67);
}

.if6aw8aev {
  d: path("M16.324 20.342c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.ip1t-iw4f {
  stop-color: var(--svg-color--462659, #462659);
}

.islivlshr {
  d: path("M18.059 14.677c.063.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.it4bksbcb {
  stop-color: var(--svg-color--dfc6ed, #DFC6ED);
}

.j8jqlbb0d {
  fill-rule: evenodd;
  d: path("M23.126 16.972a3.25 3.25 0 0 0 .323-1.427a3.3 3.3 0 0 0-.268-1.306h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.003.004a3.3 3.3 0 0 0-.22 3.245a.51.51 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218a3.3 3.3 0 0 0-.323-1.407a.51.51 0 0 1 0-.455m-12.26-2.673h-.013l1.199 2.356c.123 2.802 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.46.051l-.083.194c-.225.561-.656.99-1.19 1.235q-.023.008-.05.02l-.052.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.j8rdzr3lb {
  stop-color: var(--svg-color--5d536a, #5D536A);
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jwfvhhlnv {
  stop-color: var(--svg-color--d8bbeb, #D8BBEB);
}

.k5s0mt74t {
  stop-color: var(--svg-color--cc981a, #CC981A);
}

.k6z9s2btf {
  cx: 13.487px;
  cy: 14.869px;
  rx: 0.39px;
  ry: 0.197px;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kdpg5wb4q {
  d: path("M18.124 14.488a.893.893 0 0 1 .86 1.128H17.26a.896.896 0 0 1 .864-1.128");
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kow5dvneo {
  stop-color: var(--svg-color--86545d, #86545D);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kyp1p1brp {
  d: path("M18.92 15.263a.84.84 0 0 0-.232-.463l-.26.285l.117.228z");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0ic_xblz {
  stop-color: var(--svg-color--462659, #462659);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l3sthbi5n {
  d: path("M14.572 15.275c0-.288-.235-.48-.298-.538l-.289.278l.178.362z");
}

.lcybi9bke {
  stop-color: var(--svg-color--513f4e, #513F4E);
  stop-opacity: 0;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lx0z_99ht {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.55 14.216c-.654 0-1.205.45-1.355 1.059a.273.273 0 0 0 .267.34h2.231a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.m2jbcqdpu {
  stop-color: var(--svg-color--fc356b, #FC356B);
  stop-opacity: 0;
}

.m7r_2tbtp {
  stop-color: var(--svg-color--ee5076, #EE5076);
  stop-opacity: 0;
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mg6vw6bqp {
  stop-color: var(--svg-color--5d4364, #5D4364);
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mw-6yhbvl {
  stop-color: var(--svg-color--382834, #382834);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n11xmqb_x {
  fill: var(--svg-color--3e3138, #3E3138);
  rx: 0.641px;
  ry: 0.494px;
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oec0hiady {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.059 14.677c.063.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
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

.p6c0n1b2f {
  stop-color: var(--svg-color--563a32, #563A32);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.p9dhe0cfb {
  stop-color: var(--svg-color--e11c59, #E11C59);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pbo3-6hfl {
  cx: 13.487px;
  cy: 14.869px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qqi15ibyg {
  stop-color: var(--svg-color--744c48, #744C48);
}

.qqll8tbvj {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qyeoy6a8h {
  width: 7.594px;
  height: 9.594px;
  x: 12.172px;
  y: 14.927px;
  rx: 3.797px;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r-si_bcfj {
  d: path("M11.06 17.171a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rkgptdbvw {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.558 15.2l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.roy3-sbpo {
  stop-color: var(--svg-color--393341, #393341);
}

.rtr42sbok {
  stop-color: var(--svg-color--77494b, #77494B);
  stop-opacity: 0;
}

.s08-k72_q {
  fill: var(--svg-color--4b4a4d, #4B4A4D);
  d: path("M17.083 14.993c.265-.467.668-.835 1.537-.835c.38 0 .747.105 1.073.368c.268.217.232.495.024.6l-.556.317c-.652-.21-1.372-.24-2.079-.45");
}

.s2ol_bbam {
  stop-color: var(--svg-color--ac394e, #AC394E);
}

.s3k_zbcpk {
  d: path("m15.558 15.13l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sx6q1cbyi {
  cx: 17.494px;
  cy: 25.374px;
  r: 0.545px;
}

.sy7gbya4q {
  d: path("M22.942 29.911h3.63a9.98 9.98 0 0 0-3.63-7.355z");
}

.szoje-bkc {
  stop-color: var(--svg-color--393341, #393341);
  stop-opacity: 0;
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tp3bk41gk {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.94 18.473a3 3 0 0 1-1.421-.344c-.14-.073-.292.088-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22c-.411.22-.896.344-1.422.344Z");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tto44ccna {
  rx: 0.641px;
  ry: 0.524px;
}

.tuvqdtb4j {
  stop-color: var(--svg-color--454048, #454048);
}

.tvzw53atw {
  stop-color: var(--svg-color--c2254a, #C2254A);
  stop-opacity: 0;
}

.twe7w31pl {
  stop-color: var(--svg-color--c9b0d8, #C9B0D8);
}

.ty59qw5cn {
  stop-color: var(--svg-color--dbb8dd, #DBB8DD);
}

.u0x9jkbaj {
  d: path("M10.69 14.196h.013l-.01-.265l-.01-.306c.02-.95.574-1.316.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.136 1.332l-.12 3.073c-.123 2.803-2.311 4.685-4.983 4.685c-2.67 0-4.86-1.882-4.983-4.684z");
}

.u17l1bw1n {
  d: path("m10.5 14.156l.12 3.518c.082 2.424 2.07 4.378 4.497 4.378h1.677c2.44 0 4.435-1.976 4.498-4.416l.09-3.48h-.909l-.12 3.48c-.049 1.898-1.662 3.486-3.56 3.486h-1.676c-1.887 0-3.489-1.597-3.553-3.482l-.09-3.485z");
}

.u2-vnsrzx {
  stop-color: var(--svg-color--f73c71, #F73C71);
}

.u25v0cb4e {
  stop-color: var(--svg-color--d6274f, #D6274F);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ul3ws4blr {
  stop-color: var(--svg-color--4b4551, #4B4551);
  stop-opacity: 0;
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uvchl_awx {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.768 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.v6fzn4zbl {
  stop-color: var(--svg-color--eacceb, #EACCEB);
  stop-opacity: 0;
}

.v7lobvb0w {
  fill: var(--svg-color--554b59, #554B59);
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vfxe67bao {
  stop-color: var(--svg-color--6c3c43, #6C3C43);
}

.vim75kb4b {
  d: path("M10.31 14.155c-.278-.016-.842-.08-1.054-.728c-.11-.37.082-.779.143-.91l.024-.049c.062-.12.152-.297-.02-.577c-.193-.313-.374-.615-.045-1.257c.207-.405.093-.652-.032-.875c-.183-.327-.166-.604 0-.938c.071-.143.173-.275.173-.472c0-.198-.07-.335-.141-.474c-.074-.143-.148-.289-.148-.504c0-.23.084-.398.161-.554c.067-.133.128-.257.128-.402c0-.129-.06-.24-.125-.364c-.094-.178-.201-.38-.164-.69c.071-.59.537-.787.756-.879l.02-.008c.21-.089.364-.163.453-.58c.045-.215.131-.502.292-.663a1.06 1.06 0 0 1 .792-.3c.257.007.534-.03.75-.254c.218-.225.46-.413.7-.453s.472.014.725.144c.281.145.567.07.705-.035c.34-.262.718-.32 1.158-.141c.18.072.295.112.394.112s.214-.04.393-.112c.44-.18.819-.12 1.159.141a.68.68 0 0 0 .704.035c.254-.13.485-.184.725-.144c.241.04.483.228.7.453s.494.261.75.253a1.06 1.06 0 0 1 .793.301c.16.161.247.448.292.663c.088.417.243.491.452.58l.02.008c.22.092.685.288.756.878c.038.31-.07.513-.164.69c-.065.124-.125.236-.125.365c0 .145.062.269.128.402c.078.156.161.324.161.554c0 .215-.074.36-.147.504a.94.94 0 0 0-.105.466c0 .528.496.742.176 1.422c-.125.223-.324.455-.116.86c.329.641.192.955 0 1.268c-.172.28-.082.457-.02.577l.02.041l.004.009c.06.13.252.54.142.909c-.212.649-.775.712-1.054.728z");
}

.vpjcd0g0f {
  d: path("M20.768 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.vtqz0ebiy {
  fill: var(--svg-color--000, #000);
  d: path("M17.613 15.38a.51.51 0 0 1 .512-.51a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.236");
}

.w_-x-cc4i {
  stop-color: var(--svg-color--ffff50, #FFFF50);
}

.w_5lucbuv {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
}

.wbznmcc5b {
  d: path("M11.079 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.wcylmi-4x {
  stop-color: var(--svg-color--513f4e, #513F4E);
}

.wfn54lnxd {
  cx: 17.439px;
  cy: 25.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
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

.x_olikxjr {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
  stop-opacity: 0;
}

.x-67tmbrg {
  stop-color: var(--svg-color--b593cf, #B593CF);
}

.x2r0w67qw {
  stop-color: var(--svg-color--fff153, #FFF153);
}

.x8fxfrb0v {
  stop-color: var(--svg-color--83406e, #83406E);
  stop-opacity: 0;
}

.xbkp5vbln {
  stop-color: var(--svg-color--f6cf1c, #F6CF1C);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xot27n23k {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M15.94 18.473a3 3 0 0 1-1.421-.344c-.14-.073-.292.088-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22c-.411.22-.896.344-1.422.344");
}

.xsp4el_pm {
  d: path("m15.558 15.2l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.y6ictpbdv {
  stop-color: var(--svg-color--e43669, #E43669);
}

.yacpd-mqw {
  stop-color: var(--svg-color--fc356b, #FC356B);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.yk-5cub9i {
  d: path("M15.994 20.342h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.ysqyevbom {
  stop-color: var(--svg-color--75394e, #75394E);
}

.z_332kbzw {
  stop-color: var(--svg-color--eacceb, #EACCEB);
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

.z6iphy9ix {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.079 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

</style>
