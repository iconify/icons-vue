<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iyXHNEd)" class="fa7y8bbtb"/><path fill="url(#iygOAZc)" class="fa7y8bbtb"/><path fill="url(#is9VHhc)" class="fa7y8bbtb"/><path fill="url(#iZTDFpe)" class="fa7y8bbtb"/><path fill="url(#iq7VUDb)" class="fa7y8bbtb"/><path fill="url(#ijMRNKd)" class="fa7y8bbtb"/><path fill="url(#iKe3pRb)" class="fa7y8bbtb"/><path fill="url(#iIzGOjd)" class="fa7y8bbtb"/><path fill="url(#i4N2xue)" class="fa7y8bbtb"/><path fill="url(#iohmUGg)" class="fa7y8bbtb"/><path fill="url(#i49Dg7C)" class="fa7y8bbtb"/><g filter="url(#iozjNBc)"><path stroke="url(#i28CHXc)" class="qi4cc019n"/></g><g filter="url(#iXhsCne)"><path stroke="url(#ilb82Cc)" class="i1dntjbtt"/></g><g filter="url(#ikwQXtc)"><path stroke="url(#ib6Hryc)" class="zo-k1gbuz"/></g><g filter="url(#iitxyHj)"><path stroke="url(#i0AkAFb)" class="wo5fx1zwo"/></g><g filter="url(#iIurJed)"><path stroke="url(#ieOqhNd)" class="weys5srlk"/></g><g filter="url(#icYMljb)"><path stroke="url(#ishNMXb)" class="ozsjjimhh"/></g><g filter="url(#iXJWDKc)"><path stroke="url(#ishNMXb)" class="z87dxl5ss"/></g><g filter="url(#iiTZ8sZ)"><path stroke="url(#iVqZISd)" class="nzozvnuhf"/></g><g filter="url(#iJdH3ab)"><path stroke="url(#iHzUUes)" class="nd70fsisg"/></g><g filter="url(#iq22UAn)"><path stroke="url(#iJxjppc)" class="ev1imzbvf"/></g><path fill="url(#iieNy9b)" class="q_9bhzbsg"/><path fill="url(#iDoLxOh)" class="q_9bhzbsg"/><path fill="url(#iAG4qhd)" class="q_9bhzbsg"/><g filter="url(#ibUjymc)"><path fill="url(#iDi0nlc)" clip-rule="evenodd" class="o730nehak"/><path fill="url(#iduyUHe)" clip-rule="evenodd" class="o730nehak"/><path fill="url(#iBAZZqb)" clip-rule="evenodd" class="o730nehak"/><path fill="url(#ipJMBId)" clip-rule="evenodd" class="o730nehak"/><path fill="url(#izH03me)" clip-rule="evenodd" class="o730nehak"/><path fill="url(#i1TTXRd)" clip-rule="evenodd" class="o730nehak"/><path fill="url(#i4S1yZZ)" clip-rule="evenodd" class="o730nehak"/><path fill="url(#itqliic)" clip-rule="evenodd" class="o730nehak"/><path fill="url(#ighFCHt)" clip-rule="evenodd" class="o730nehak"/><path fill="url(#iDN1vzI)" clip-rule="evenodd" class="o730nehak"/><path fill="url(#iWXoAOe)" clip-rule="evenodd" class="o730nehak"/></g><path fill="url(#iwaUIad)" class="g2d-77b2l"/><path fill="url(#iH2ELyc)" class="g2d-77b2l"/><path fill="url(#iU1KkEc)" class="g2d-77b2l"/><path fill="url(#iEwSPOc)" class="o-fxcn62m"/><path fill="url(#iVltdic)" class="o-fxcn62m"/><path fill="url(#iT1IlFc)" class="o-fxcn62m"/><path fill="url(#iufulbF)" class="o-fxcn62m"/><path fill="url(#isFYOHc)" class="o-fxcn62m"/><path fill="url(#iBzJLrX)" class="o-fxcn62m"/><path fill="url(#igW2D7b)" class="sd0d3bc6s"/><g filter="url(#iLx4rcb)"><path stroke="url(#iEvDKsb)" class="ieqfxmbvc"/></g><g filter="url(#izxIpld)"><path fill="url(#iCJJYpe)" class="vqat9mbls"/></g><g filter="url(#iv09Osd)"><path fill="url(#ieRSRCh)" class="uqcqe_03s"/><path fill="url(#izaVjcc)" class="uqcqe_03s"/></g><g filter="url(#i8gvpHb)"><path class="jtnrz7b8j"/><path fill="url(#idsIc3b)" class="zsj8kyflc"/></g><g filter="url(#iGnfYrc)"><path class="mi4alfbsr"/><path fill="url(#iglzXir)" class="cwcjt9bjx"/></g><g filter="url(#iVPTeJb)"><path fill="url(#iiSLPJd)" class="vlyb9zb4j"/><path fill="url(#i8MU5ye)" class="vlyb9zb4j"/><path fill="url(#iA04uqY)" class="vlyb9zb4j"/><path fill="url(#iH6BCHe)" class="vlyb9zb4j"/><path fill="url(#i1hWmuc)" class="vlyb9zb4j"/><path fill="url(#iSGgWad)" class="vlyb9zb4j"/><path fill="url(#iKV8dUc)" class="vlyb9zb4j"/><path fill="url(#ipX48ee)" class="vlyb9zb4j"/></g><path fill="url(#iuEx5pb)" class="vlyb9zb4j"/><g filter="url(#iR7Csre)"><path class="v78boebky"/></g><g filter="url(#iMexqid)"><path class="fjem-ccyp"/><path fill="url(#itABq0c)" class="xdltxabbm"/><path fill="url(#i0qw1dc)" class="xdltxabbm"/><path fill="url(#i1CfNed)" class="xdltxabbm"/><path fill="url(#ikZaGbc)" class="xdltxabbm"/></g><path fill="url(#id0XiKd)" class="xdltxabbm"/><path fill="url(#ihxOVyb)" class="xdltxabbm"/><path stroke="url(#ieZTeJc)" class="i115qhbyb"/><g filter="url(#iBkXQcb)"><path class="r_xs8s3mj"/></g><g filter="url(#iERnfKo)"><path class="s5lllhbzl"/></g><g filter="url(#iNE5Wce)"><path class="pigemablk"/></g><g filter="url(#iaJkAMb)"><path clip-rule="evenodd" class="vb3l5frdw"/></g><path class="djv3vvrki"/><path fill="url(#i9o7DWd)" class="t4_u-s8fw"/><path class="izgp51f1m"/><g filter="url(#iDN3Xwb)"><path class="nxupihbjj"/><path fill="url(#iZ1xwTd)" class="p6ezwlbne"/></g><g filter="url(#i5EhqNb)"><path fill="url(#iySOknf)" class="a49uuisdp"/></g><path class="c5d3fneuy"/><path fill="url(#i3yiVCB)" class="gr4-zfbbq"/><path class="jo4oxwb-t"/><g filter="url(#iNTvBPd)"><path fill="url(#iQt4CJc)" class="xngtjnj_b"/></g><g filter="url(#i5O4WFb)"><ellipse transform="rotate(-27.914 15.727 13.055)" class="amc-qkb8g"/><ellipse fill="url(#iGpgb7d)" transform="rotate(-27.914 15.727 13.055)" class="kvyy2mb3b"/></g><g filter="url(#iEhBRmc)"><path class="q3nbhz2zy"/></g><g filter="url(#is1X99d)"><path class="fpb97garr"/></g><g filter="url(#iOvbwme)"><path class="pde8a6kpd"/><path fill="url(#iFgQ5pe)" class="xzx42o2np"/><path fill="url(#i2NL7Qd)" class="xzx42o2np"/></g><g filter="url(#iItX2Xc)"><path class="fyna7jbmf"/><path fill="url(#igd72ve)" class="dy1qktvqg"/><path fill="url(#iSn8fYc)" class="dy1qktvqg"/></g><g filter="url(#iuan9zd)"><path stroke="url(#irzisVc)" class="al80r3voi"/></g><g filter="url(#itJBv0d)"><path class="vfqs0qbuy"/></g><defs><radialGradient id="iyXHNEd" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 5.57 11.342)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="ous3tjbxu"/><stop offset="1" class="vqxmos31w"/></radialGradient><radialGradient id="iygOAZc" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 2.75 6.98)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="nb3h23xzn"/><stop offset="1" class="av_vhzb0x"/></radialGradient><radialGradient id="iZTDFpe" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.295 4.528)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="shvpuacoj"/><stop offset="1" class="h5rrjb2yq"/></radialGradient><radialGradient id="iq7VUDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 5.943 3.365)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="shvpuacoj"/><stop offset="1" class="h5rrjb2yq"/></radialGradient><radialGradient id="ijMRNKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 3.96875 -.56716 -.09602 7.912 2.599)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="shvpuacoj"/><stop offset="1" class="h5rrjb2yq"/></radialGradient><radialGradient id="iKe3pRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 9.412 2.96)" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></radialGradient><radialGradient id="iIzGOjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 7.484 1.931)" gradientUnits="userSpaceOnUse"><stop class="cmb_6ubbj"/><stop offset=".994" class="h1hyg9g1x"/></radialGradient><radialGradient id="i4N2xue" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.65 3.542)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="sl7huzb4s"/><stop offset="1" class="akhb020hk"/></radialGradient><radialGradient id="iohmUGg" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 3.67 3.747)" gradientUnits="userSpaceOnUse"><stop class="q_yfvabjb"/><stop offset="1" class="vtax1pite"/></radialGradient><radialGradient id="i49Dg7C" cx="0" cy="0" r="1" gradientTransform="matrix(-.88951 .77545 -.60682 -.69608 11.451 6.599)" gradientUnits="userSpaceOnUse"><stop class="l-2lm0_-n"/><stop offset="1" class="e9-zjobdb"/></radialGradient><radialGradient id="iDoLxOh" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -1.15625 0 6.835 11.9)" gradientUnits="userSpaceOnUse"><stop class="vm40c2rnb"/><stop offset="1" class="in_wled_m"/></radialGradient><radialGradient id="iduyUHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73555 5.55753 -6.94248 -.91885 18.35 16.948)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iBAZZqb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5144 2.37014 -3.11418 -4.61765 14.918 17.275)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ipJMBId" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.906 10.25)scale(2.62359 2.01456)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="izH03me" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.402 9.596)scale(3.0171 2.12528)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i1TTXRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.67543 3.1874 -4.4246 2.32575 14.427 4.076)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i4S1yZZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75705 1.75717 -2.45561 -2.45544 25.828 6.61)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="itqliic" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24742 .65383 -1.36352 -4.68684 27.872 12.862)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ighFCHt" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43248 .85817 -1.09318 -4.37248 27.136 17.03)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iDN1vzI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10252 -3.23067 2.55528 -.87203 24.487 9.895)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iWXoAOe" cx="0" cy="0" r="1" gradientTransform="matrix(1.83328 .1923 -.31158 2.97044 11.231 12.818)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iH2ELyc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.05789 2.36576 -2.0517 -6.98818 25.18 27.081)" gradientUnits="userSpaceOnUse"><stop class="cedqx2rkm"/><stop offset="1" class="xi0shyhbu"/></radialGradient><radialGradient id="iU1KkEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.62502 2.65624 0 10.595 29.447)" gradientUnits="userSpaceOnUse"><stop class="fp2gw167u"/><stop offset="1" class="rnij5z0qd"/></radialGradient><radialGradient id="iVltdic" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.65451 -5.4375 0 2.685 12.447)" gradientUnits="userSpaceOnUse"><stop class="rz1t4jbgv"/><stop offset="1" class="xkxmx1bvv"/></radialGradient><radialGradient id="iT1IlFc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.10928 -2.13275 .90224 -4.27661 17.408 19.72)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="m2mta8b_j"/><stop offset="1" class="tx_pqhb7h"/></radialGradient><radialGradient id="iufulbF" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69115 0 0 -5.6259 11.455 15.307)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m2mta8b_j"/><stop offset="1" class="tx_pqhb7h"/></radialGradient><radialGradient id="igW2D7b" cx="0" cy="0" r="1" gradientTransform="rotate(45.616 -14.902 29.777)scale(4.20588 5.16626)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="cnwmb7ycc"/><stop offset="1" class="r9i5gck8b"/></radialGradient><radialGradient id="ieRSRCh" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 45.141 -47.356)scale(3.3329 4.06932)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="izaVjcc" cx="0" cy="0" r="1" gradientTransform="matrix(1.60392 .89901 -.25417 .45346 24.898 11.85)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="idsIc3b" cx="0" cy="0" r="1" gradientTransform="matrix(1.84056 -.13691 .10703 1.4388 24.071 14.037)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iglzXir" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47111 0 0 -1.16052 13.11 13.9)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iiSLPJd" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 9.648 9.059)scale(8.73018 11.6852)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="i8MU5ye" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 8.859 9.504)scale(2.75006 1.9151)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iA04uqY" cx="0" cy="0" r="1" gradientTransform="matrix(1.30857 -4.23734 5.3764 1.66034 16.06 21.512)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iH6BCHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.9777 8.28922 -8.33361 -.98294 19.377 13.436)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="i1hWmuc" cx="0" cy="0" r="1" gradientTransform="scale(8.04794 8.00507)rotate(90 .286 2)" gradientUnits="userSpaceOnUse"><stop offset=".858" class="l-0cbacrb"/><stop offset="1" class="tetwumyrr"/></radialGradient><radialGradient id="iSGgWad" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 9.716 8.694)scale(8.57858 14.7697)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iKV8dUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40279 1.72161 0 21.523 12.734)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="ipX48ee" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.59996 1.83366 0 16.187 12.456)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iuEx5pb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56676 0 0 -7.85716 24.93 14.548)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="itABq0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.5553 -2.49165 .7679 -.17114 19.674 15.434)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="ikZaGbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9501 0 0 -.26562 19.382 15.691)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="ihxOVyb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6715 1.14755 -1.37918 -2.0089 19.178 14.966)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="i9o7DWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .989 -1.57311 0 21.378 13.172)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZ1xwTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2827 -.3643 .50156 -.38922 21.1 13.274)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3yiVCB" cx="0" cy="0" r="1" gradientTransform="matrix(0 .989 -1.57312 0 16.058 13.172)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iGpgb7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.00943 -.60226 .72394 -.01133 15.71 13.44)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFgQ5pe" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 14.157 -3.914)scale(3.69442 1.88997)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="i2NL7Qd" cx="0" cy="0" r="1" gradientTransform="rotate(-110.547 10.818 -.211)scale(4.18484 6.84693)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="t7u3qkefj"/><stop offset=".93" class="w4h8bubsi"/></radialGradient><radialGradient id="igd72ve" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57447 5.35319 -8.75215 -4.20911 21.047 4.24)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iSn8fYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2564 1.66661 -3.58564 -.55163 18.974 4.69)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iozjNBc" width=".423" height="2.22" x="4.15" y="4.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".05"/></filter><filter id="iXhsCne" width=".345" height="2.572" x="5.704" y="4.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".05"/></filter><filter id="ikwQXtc" width=".509" height="1.681" x="7.181" y="4.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".05"/></filter><filter id="iitxyHj" width="1.556" height="3.487" x="3.015" y="3.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".2"/></filter><filter id="iIurJed" width="1.2" height="3.889" x="4.701" y="2.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".2"/></filter><filter id="icYMljb" width="1.488" height="4.773" x="6.248" y="2.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".2"/></filter><filter id="iXJWDKc" width="2.002" height="4.299" x="7.652" y="3.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".2"/></filter><filter id="iiTZ8sZ" width="1.412" height="1.358" x="3.305" y="6.423" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".1"/></filter><filter id="iJdH3ab" width="1.118" height=".999" x="4.954" y="6.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".1"/></filter><filter id="iq22UAn" width="1.312" height="1.023" x="6.22" y="6.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".1"/></filter><filter id="ibUjymc" width="18.557" height="19.057" x="9.564" y="2.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3863"/></filter><filter id="iLx4rcb" width="9.217" height="11.911" x="5.06" y="11.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".75"/></filter><filter id="izxIpld" width="4.073" height="3.923" x="11.045" y="11.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3863"/></filter><filter id="iv09Osd" width="3.923" height="4.173" x="22.641" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3863"/></filter><filter id="i8gvpHb" width="3.619" height="3.619" x="22.793" y="12.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".25"/></filter><filter id="iGnfYrc" width="3.119" height="3.119" x="11.47" y="12.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".125"/></filter><filter id="iVPTeJb" width="12.423" height="13.659" x="12.507" y="7.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3863"/></filter><filter id="iR7Csre" width="3.288" height="4.269" x="16.876" y="12.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".25"/></filter><filter id="iMexqid" width="2.788" height="3.769" x="17.324" y="12.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".125"/></filter><filter id="iBkXQcb" width="3.615" height="1.567" x="19.91" y="12.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3863"/></filter><filter id="iERnfKo" width="3.615" height="1.567" x="13.911" y="12.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3863"/></filter><filter id="iNE5Wce" width="2.946" height="1.286" x="14.076" y="10.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3863"/></filter><filter id="iaJkAMb" width="2.946" height="1.286" x="20.679" y="10.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3863"/></filter><filter id="iDN3Xwb" width=".915" height=".805" x="20.505" y="12.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".05"/></filter><filter id="i5EhqNb" width=".999" height="1.026" x="21.551" y="12.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".1"/></filter><filter id="iNTvBPd" width="1.115" height="1.18" x="16.135" y="12.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".1"/></filter><filter id="i5O4WFb" width="1.069" height=".815" x="15.193" y="12.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".05"/></filter><filter id="iEhBRmc" width="2.624" height="1.06" x="20.782" y="10.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".1"/></filter><filter id="is1X99d" width="2.624" height="1.06" x="14.137" y="10.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".1"/></filter><filter id="iOvbwme" width="4.959" height="5.327" x="11.059" y="5.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".2"/></filter><filter id="iItX2Xc" width="10.567" height="6.939" x="14.919" y="4.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3863"/><feGaussianBlur result="effect2_foregroundBlur_4002_3863" stdDeviation=".125"/></filter><filter id="iuan9zd" width="1.264" height="2.684" x="14.893" y="5.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".1"/></filter><filter id="itJBv0d" width="8.006" height="4.282" x="17.923" y="6.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3863" stdDeviation=".5"/></filter><linearGradient id="is9VHhc" x1="6.053" x2="6.053" y1="12.002" y2="10.299" gradientUnits="userSpaceOnUse"><stop class="vym-t7ebt"/><stop offset="1" class="jb51pmjgw"/></linearGradient><linearGradient id="i28CHXc" x1="4.543" x2="4.552" y1="4.696" y2="6.698" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="ilb82Cc" x1="5.963" x2="5.99" y1="4.267" y2="6.63" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="ib6Hryc" x1="7.722" x2="7.725" y1="4.867" y2="6.314" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="i0AkAFb" x1="3.309" x2="3.728" y1="4.808" y2="7.416" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="ieOqhNd" x1="5.371" x2="5.079" y1="3.376" y2="7.372" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="ishNMXb" x1="6.918" x2="6.626" y1="3.32" y2="7.316" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="iVqZISd" x1="4.445" x2="3.59" y1="6.777" y2="6.644" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="iHzUUes" x1="5.875" x2="5.311" y1="6.504" y2="6.363" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="iJxjppc" x1="7.334" x2="6.77" y1="6.312" y2="6.171" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="iieNy9b" x1="3.904" x2="8.279" y1="12.01" y2="12.01" gradientUnits="userSpaceOnUse"><stop class="u-9w58unm"/><stop offset=".743" class="gv7qteejy"/></linearGradient><linearGradient id="iAG4qhd" x1="6.174" x2="6.174" y1="11.424" y2="11.682" gradientUnits="userSpaceOnUse"><stop class="s68njbc8b"/><stop offset="1" class="ha46_3b_b"/></linearGradient><linearGradient id="iDi0nlc" x1="24.439" x2="16.144" y1="5.424" y2="20.789" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iwaUIad" x1="18.688" x2="5.165" y1="28.625" y2="12.447" gradientUnits="userSpaceOnUse"><stop class="dkttnh3ka"/><stop offset=".751" class="j0qmv8b6d"/></linearGradient><linearGradient id="iEwSPOc" x1="9.17" x2="11.063" y1="25.87" y2="19.679" gradientUnits="userSpaceOnUse"><stop offset=".1" class="nrxnoi8to"/><stop offset="1" class="o8-s5pjlc"/></linearGradient><linearGradient id="isFYOHc" x1="13.509" x2="12.724" y1="24.181" y2="22.548" gradientUnits="userSpaceOnUse"><stop class="hzm5vwgac"/><stop offset=".732" class="yy_71ub6o"/></linearGradient><linearGradient id="iBzJLrX" x1="6.7" x2="6.7" y1="12.447" y2="13.469" gradientUnits="userSpaceOnUse"><stop class="ignlpnblb"/><stop offset="1" class="a8kog2b_j"/></linearGradient><linearGradient id="iEvDKsb" x1="6.717" x2="12.467" y1="14.155" y2="22.436" gradientUnits="userSpaceOnUse"><stop class="ius0mclhc"/><stop offset="1" class="f3d24-ppq"/></linearGradient><linearGradient id="iCJJYpe" x1="11.045" x2="14.652" y1="14.006" y2="14.006" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="i0qw1dc" x1="17.574" x2="18.718" y1="15.522" y2="15.522" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="i1CfNed" x1="18.718" x2="18.718" y1="16.496" y2="15.752" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="id0XiKd" x1="18.813" x2="18.813" y1="16.464" y2="16.294" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="ieZTeJc" x1="17.421" x2="17.982" y1="18.215" y2="17.346" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iySOknf" x1="22.326" x2="21.944" y1="13.238" y2="13.473" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQt4CJc" x1="16.965" x2="16.582" y1="13.237" y2="13.473" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irzisVc" x1="15.194" x2="15.857" y1="6.344" y2="7.897" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-raising-hand-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a49uuisdp {
  d: path("M22.35 13.535a1.02 1.02 0 0 0-.283-.564l-.316.348l.143.278z");
}

.a8kog2b_j {
  stop-color: var(--svg-color--6a51a2, #6A51A2);
  stop-opacity: 0;
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.akhb020hk {
  stop-color: var(--svg-color--685856, #685856);
  stop-opacity: 0;
}

.al80r3voi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.194 5.925c.028.296.285 1.41.663 2.084");
}

.amc-qkb8g {
  cx: 15.727px;
  cy: 13.055px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.475px;
  ry: 0.24px;
}

.av_vhzb0x {
  stop-color: var(--svg-color--362024, #362024);
  stop-opacity: 0;
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.c5d3fneuy {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.803 12.259c-.796 0-1.468.549-1.651 1.29a.334.334 0 0 0 .326.416h2.72a.28.28 0 0 0 .277-.331a1.71 1.71 0 0 0-1.672-1.375");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.cedqx2rkm {
  stop-color: var(--svg-color--9e7fdf, #9E7FDF);
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

.cmb_6ubbj {
  stop-color: var(--svg-color--695755, #695755);
}

.cnwmb7ycc {
  stop-color: var(--svg-color--351f21, #351F21);
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cwcjt9bjx {
  d: path("M13.03 15.209a1.31 1.31 0 1 0 0-2.619a1.31 1.31 0 0 0 0 2.619");
}

.djv3vvrki {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.633 12.259c.796 0 1.468.549 1.651 1.29a.334.334 0 0 1-.326.416h-2.72a.28.28 0 0 1-.277-.331a1.704 1.704 0 0 1 1.672-1.375");
}

.dkttnh3ka {
  stop-color: var(--svg-color--8663c9, #8663C9);
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dwl3kxbcz {
  stop-color: var(--svg-color--645352, #645352);
  stop-opacity: 0;
}

.dy1qktvqg {
  d: path("M17.983 4.403c-1.381-.305-2.621 1.072-2.764 1.583c1.282 4.322 4.526 4.085 7.729 3.73c1.916-.214 2.125.66 2.288 1.082c0-4.794-4.077-5.694-7.219-6.387z");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9-zjobdb {
  stop-color: var(--svg-color--584947, #584947);
  stop-opacity: 0;
}

.ev1imzbvf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.232 6.323c-.13.165-.501.36-.712.423");
}

.f3d24-ppq {
  stop-color: var(--svg-color--9478ce, #9478CE);
  stop-opacity: 0;
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fa7y8bbtb {
  d: path("M2.99 8.705c-.125-1.921-.28-2.958-.328-3.64c-.035-.512.024-1.067.711-1.192c.598-.074.883.452.907.66c-.003-.2 0-.679 0-.804c0-.211.007-.977.859-.977c.601 0 .816.588.8.864c.011-.102.023-.414.036-.707c.018-.434.251-.99.945-.977c.598.039.793.613.766.977l-.117 1.867c.023-.188.102-.665.277-1.34s.702-.72.957-.684c.326.046.88.361.648 1.274c-.275 1.156-.462 2.644-.527 3.285c.324-.133.642-.413 1.002-.788s.886-.383 1.183-.16c.34.293.522.967.12 1.37c-.463.425-2.13 2.405-2.957 3.394c-.23.292-.997.875-2.235.875c-2.203-.094-2.941-1.676-3.047-3.297");
}

.fjem-ccyp {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m18.252 13.46l-.648 2.072a.657.657 0 0 0 .635.852h.958a.66.66 0 0 0 .635-.852l-.648-2.073c-.139-.459-.787-.459-.932 0");
}

.fp2gw167u {
  stop-color: var(--svg-color--8969ba, #8969BA);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.fpb97garr {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.461 11.007c-.393-.095-1.37-.047-2.024.42");
}

.ft5dv1b6b {
  fill: none;
}

.fyna7jbmf {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M17.983 4.403c-1.381-.305-2.621 1.072-2.764 1.583c1.282 4.322 4.526 4.085 7.729 3.73c1.916-.214 2.125.66 2.288 1.082c0-4.794-4.077-5.694-7.219-6.387z");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g2d-77b2l {
  d: path("M19.683 20.447h.97c2.49 0 7.472 3.5 7.472 9H10.192v-3.5a.67.67 0 0 0-.414-.625l-3.073-1.375c-2.49-1-3.487-3.5-3.487-5.198v-5.287c0-.564.423-1.015.932-1.015h4.114c.517 0 .932.461.932 1.015v3.985c0 1.302.996 1.5.996 1.5l5.977 1.5z");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gr4-zfbbq {
  d: path("M16.056 12.59a1.088 1.088 0 0 0-1.049 1.375h2.102q.039-.14.04-.287a1.095 1.095 0 0 0-1.093-1.088");
}

.gv7qteejy {
  stop-color: var(--svg-color--463168, #463168);
}

.h1hyg9g1x {
  stop-color: var(--svg-color--695755, #695755);
  stop-opacity: 0;
}

.h5rrjb2yq {
  stop-color: var(--svg-color--301715, #301715);
  stop-opacity: 0;
}

.ha46_3b_b {
  stop-color: var(--svg-color--4f396f, #4F396F);
  stop-opacity: 0;
}

.hj-mkimsp {
  stop-color: var(--svg-color--645352, #645352);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hzm5vwgac {
  stop-color: var(--svg-color--8967cb, #8967CB);
}

.i115qhbyb {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.009 16.984a3.64 3.64 0 0 0 1.709.415c.633 0 1.215-.151 1.71-.415a.24.24 0 0 1 .288.048a.23.23 0 0 1 .024.291l-.041-.027a2.355 2.355 0 0 1-3.962 0zm0 0a.24.24 0 0 0-.29.051a.23.23 0 0 0-.023.288z");
}

.i1dntjbtt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m5.912 4.263l-.07 2.297");
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.ieqfxmbvc {
  d: path("M7.06 13.375v5.172a2 2 0 0 0 1.38 1.901l4.183 1.363");
}

.ignlpnblb {
  stop-color: var(--svg-color--6a51a2, #6A51A2);
}

.in_wled_m {
  stop-color: var(--svg-color--655188, #655188);
  stop-opacity: 0;
}

.ius0mclhc {
  stop-color: var(--svg-color--9478ce, #9478CE);
}

.izgp51f1m {
  fill: var(--svg-color--000, #000);
  d: path("M20.757 13.678a.62.62 0 0 1 .623-.623a.62.62 0 0 1 .554.91h-1.103a.56.56 0 0 1-.074-.287");
}

.j0qmv8b6d {
  stop-color: var(--svg-color--7a5fb3, #7A5FB3);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jb51pmjgw {
  stop-color: var(--svg-color--3d1a14, #3D1A14);
  stop-opacity: 0;
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jo4oxwb-t {
  fill: var(--svg-color--000, #000);
  d: path("M16.679 13.678a.62.62 0 0 0-.624-.623a.62.62 0 0 0-.553.91h1.102a.6.6 0 0 0 .075-.287");
}

.jtnrz7b8j {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M24.602 15.209a1.31 1.31 0 1 0 0-2.619a1.31 1.31 0 0 0 0 2.619");
}

.k35cj8b6j {
  stop-color: var(--svg-color--685755, #685755);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.kvyy2mb3b {
  cx: 15.727px;
  cy: 13.055px;
  rx: 0.475px;
  ry: 0.24px;
}

.l-0cbacrb {
  stop-color: var(--svg-color--5c4761, #5C4761);
  stop-opacity: 0;
}

.l-2lm0_-n {
  stop-color: var(--svg-color--584947, #584947);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7n7uk6bh {
  stop-color: var(--svg-color--331c1a, #331C1A);
  stop-opacity: 0;
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

.m16jdvb1f {
  stop-color: var(--svg-color--685755, #685755);
  stop-opacity: 0;
}

.m2mta8b_j {
  stop-color: var(--svg-color--362659, #362659);
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mi4alfbsr {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M13.03 15.209a1.31 1.31 0 1 0 0-2.619a1.31 1.31 0 0 0 0 2.619");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.nb3h23xzn {
  stop-color: var(--svg-color--362024, #362024);
}

.nd70fsisg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M5.773 6.515c-.13.164-.333.3-.519.399");
}

.nrxnoi8to {
  stop-color: var(--svg-color--6b45ad, #6B45AD);
}

.nxupihbjj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.3 12.82c.078.104-.084.23-.268.368c-.185.138-.321.235-.399.131c-.077-.104.01-.3.194-.437c.184-.138.396-.165.473-.062");
}

.nzozvnuhf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M3.605 7.48c.11-.062.618-.379.813-.757");
}

.o-fxcn62m {
  d: path("m18.076 20.411l-7.874 5.151a.65.65 0 0 0-.4-.47L6.718 23.74c-2.5-.982-3.5-3.437-3.5-5.105v-5.192c0-.554.425-.997.935-.997h4.13c.52 0 .935.453.935.997v3.914c0 1.278 1 1.473 1 1.473l6 1.473z");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o730nehak {
  fill-rule: evenodd;
  d: path("M27.477 15.618c.259-.53.395-1.123.395-1.74c0-.57-.118-1.104-.328-1.59h.007a4 4 0 0 0-.343-.626l-.003-.004a3.95 3.95 0 0 1-.641-2.159v-.012a4.02 4.02 0 0 0-4.022-4.022a.66.66 0 0 1-.555-.284a4.03 4.03 0 0 0-3.27-1.677A4.03 4.03 0 0 0 15.45 5.18a.69.69 0 0 1-.555.284q-.053 0-.104.002a4.02 4.02 0 0 0-3.918 4.02v.012a3.95 3.95 0 0 1-.642 2.159l-.002.005a4.02 4.02 0 0 0-.269 3.955a.63.63 0 0 1 0 .555a4 4 0 0 0-.395 1.715a3.917 3.917 0 0 0 3.923 3.923H23.95a3.917 3.917 0 0 0 3.923-3.923a4 4 0 0 0-.395-1.715a.63.63 0 0 1 0-.555M12.532 12.36h-.015l1.46 2.872c.151 3.416 1.484 0 4.74 0s4.677 3.802 4.828.386l1.384-3.897c-.065-1.518-1.165-1.624-1.384-1.624h-3.926a4.71 4.71 0 0 1-3.887-2.04a.321.321 0 0 0-.563.062l-.1.236a2.8 2.8 0 0 1-1.512 1.53l-.063.025c-.287.15-.962.597-.987 1.754l.012.373z");
}

.o8-s5pjlc {
  stop-color: var(--svg-color--6b45ad, #6B45AD);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ous3tjbxu {
  stop-color: var(--svg-color--482f30, #482F30);
}

.ozsjjimhh {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.137 2.465l-.29 3.944");
}

.p6ezwlbne {
  d: path("M21.3 12.82c.078.104-.084.23-.268.368c-.185.138-.321.235-.399.131c-.077-.104.01-.3.194-.437c.184-.138.396-.165.473-.062");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pde8a6kpd {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M12.539 6.6c.69-.73 1.994-.732 2.597-.623l.482 1.573c-.308-.047-.582.062-.813.286c-.547 1.537-2.425 2.384-3.296 2.616c-.181-1.819.132-2.902 1.03-3.852");
}

.pigemablk {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m14.576 11.732l-.005.003a.327.327 0 0 1-.336-.56l.002-.002l.003-.002l.012-.006a3 3 0 0 1 .18-.094c.12-.057.292-.13.5-.197c.415-.132.994-.244 1.62-.133a.327.327 0 1 1-.114.644c-.486-.086-.953-.001-1.307.112a3.4 3.4 0 0 0-.555.235");
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q_9bhzbsg {
  d: path("M4.068 11.624c0-.11.09-.2.2-.2H8.08c.11 0 .2.09.2.2v1.714H4.07z");
}

.q_yfvabjb {
  stop-color: var(--svg-color--685756, #685756);
}

.q3nbhz2zy {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.082 11.007c.393-.095 1.371-.047 2.025.42");
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qi4cc019n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.287 4.693l.149 1.945");
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
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

.r_xs8s3mj {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M20.11 13.206c.324-.57.816-1.019 1.874-1.019c.464 0 .91.129 1.308.45c.328.265.284.604.03.73l-.678.387c-.794-.256-1.673-.291-2.534-.548");
}

.r9i5gck8b {
  stop-color: var(--svg-color--503536, #503536);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rnij5z0qd {
  stop-color: var(--svg-color--8969ba, #8969BA);
  stop-opacity: 0;
}

.rz1t4jbgv {
  stop-color: var(--svg-color--8b6ebc, #8B6EBC);
}

.s5lllhbzl {
  fill: var(--svg-color--272528, #272528);
  d: path("M17.326 13.206c-.323-.57-.815-1.019-1.874-1.019c-.463 0-.91.129-1.308.45c-.328.265-.284.604-.03.73l.678.387c.795-.256 1.673-.291 2.534-.548");
}

.s68njbc8b {
  stop-color: var(--svg-color--4f396f, #4F396F);
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sd0d3bc6s {
  d: path("M18.718 23.553c-1.268 0-2.296-.986-2.296-2.2v-2.6c0-1.215 1.028-2.2 2.296-2.2s2.296.985 2.296 2.2v2.6c0 1.214-1.028 2.2-2.296 2.2");
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.shvpuacoj {
  stop-color: var(--svg-color--301715, #301715);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sl7huzb4s {
  stop-color: var(--svg-color--685856, #685856);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t4_u-s8fw {
  d: path("M21.38 12.59a1.088 1.088 0 0 1 1.049 1.375h-2.102a1.092 1.092 0 0 1 1.053-1.375");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t7u3qkefj {
  stop-color: var(--svg-color--545253, #545253);
  stop-opacity: 0;
}

.tetwumyrr {
  stop-color: var(--svg-color--5c4761, #5C4761);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tx_pqhb7h {
  stop-color: var(--svg-color--5e4490, #5E4490);
  stop-opacity: 0;
}

.u-9w58unm {
  stop-color: var(--svg-color--745c92, #745C92);
}

.uqcqe_03s {
  d: path("M24.602 15.861a1.962 1.962 0 1 0 0-3.923a1.962 1.962 0 0 0 0 3.923");
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v78boebky {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m18.24 13.628l-.834 2.072a.657.657 0 0 0 .635.853H19a.66.66 0 0 0 .634-.853l-.648-2.072c-.139-.459-.601-.459-.747 0");
}

.vb3l5frdw {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m23.267 11.175l-.168.28za.327.327 0 0 1-.336.56l-.006-.003a2 2 0 0 0-.138-.07a3 3 0 0 0-.417-.165c-.354-.113-.82-.198-1.307-.112a.327.327 0 0 1-.113-.644c.625-.11 1.204 0 1.619.133a4 4 0 0 1 .68.29l.012.007l.004.003z");
}

.vfqs0qbuy {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m21.651 8.803l-1.737.32a.839.839 0 1 1-.153-1.664h2.854c1.687 0 2.246 1.7 2.314 2.282a3.84 3.84 0 0 0-3.278-.938");
}

.vlyb9zb4j {
  d: path("M12.517 12.36h.015l-.013-.323l-.012-.373c.025-1.157.7-1.604.987-1.754l.063-.025l.062-.025a2.8 2.8 0 0 0 1.45-1.504l.1-.237a.322.322 0 0 1 .563-.062a4.71 4.71 0 0 0 3.887 2.04h3.926c.22 0 1.319.106 1.384 1.624l-.144 3.746c-.15 3.416-2.819 5.71-6.075 5.71s-5.924-2.294-6.075-5.71z");
}

.vm40c2rnb {
  stop-color: var(--svg-color--655188, #655188);
}

.vqat9mbls {
  d: path("M13.006 15.861a1.961 1.961 0 1 0 0-3.923a1.961 1.961 0 0 0 0 3.923");
}

.vqxmos31w {
  stop-color: var(--svg-color--432927, #432927);
}

.vtax1pite {
  stop-color: var(--svg-color--685756, #685756);
  stop-opacity: 0;
}

.vym-t7ebt {
  stop-color: var(--svg-color--3d1a14, #3D1A14);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w4h8bubsi {
  stop-color: var(--svg-color--545253, #545253);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.weys5srlk {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.3 3.376v3.089");
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wo5fx1zwo {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m3.613 4.332l.36 2.633");
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xdltxabbm {
  d: path("m18.252 13.46l-.648 2.072a.657.657 0 0 0 .635.852h.958a.66.66 0 0 0 .635-.852l-.648-2.073c-.139-.459-.787-.459-.932 0");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xi0shyhbu {
  stop-color: var(--svg-color--9e7fdf, #9E7FDF);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xkxmx1bvv {
  stop-color: var(--svg-color--8b6ebc, #8B6EBC);
  stop-opacity: 0;
}

.xngtjnj_b {
  d: path("M17.05 13.55c0-.351-.287-.586-.364-.656l-.351.34l.216.44z");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xzx42o2np {
  d: path("M12.539 6.6c.69-.73 1.994-.732 2.597-.623l.482 1.573c-.308-.047-.582.062-.813.286c-.547 1.537-2.425 2.384-3.296 2.616c-.181-1.819.132-2.902 1.03-3.852");
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yy_71ub6o {
  stop-color: var(--svg-color--8967cb, #8967CB);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z0iyhs38d {
  stop-color: var(--svg-color--331c1a, #331C1A);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z87dxl5ss {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.059 3.512l-.813 3.406");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zo-k1gbuz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m7.553 4.864l-.235 1.407");
}

.zsj8kyflc {
  d: path("M24.602 15.209a1.31 1.31 0 1 0 0-2.619a1.31 1.31 0 0 0 0 2.619");
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
