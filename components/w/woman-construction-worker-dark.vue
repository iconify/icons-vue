<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHOn6rc)"><path fill="url(#iCd195b)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#iW8RNqe)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#iBDhsge)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#iNe4LWb)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#iGdKHwb)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#ipITAJe)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#iyb9LEJ)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#iRfqrVb)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#i5Cdlxc)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#iS4aSiu)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#i9PMsAd)" clip-rule="evenodd" class="xschf7bon"/><path fill="url(#irKe4cs)" clip-rule="evenodd" class="xschf7bon"/></g><path fill="url(#i08HAYo)" class="rihmkq8le"/><path fill="url(#ixLFgme)" class="rihmkq8le"/><path fill="url(#iRNOrCe)" class="f3ael5nnj"/><path fill="url(#izlspBK)" class="f3ael5nnj"/><path fill="url(#i3kJV0d)" class="f3ael5nnj"/><path fill="url(#iFGqZ7b)" class="aja9ggbky"/><path fill="url(#intQq8b)" class="aja9ggbky"/><path fill="url(#iTFP0od)" class="pkk1wtbcw"/><path fill="url(#i0QFqKc)" class="pkk1wtbcw"/><path fill="url(#i1aP5Bc)" class="pkk1wtbcw"/><path fill="url(#i8sZbpU)" class="xj4nx8s9d"/><path fill="url(#ilGfS8d)" class="xj4nx8s9d"/><path class="cwhvcxb2p"/><path fill="url(#in3x4bd)" class="julhe_bku"/><path fill="url(#igUtr8b)" class="bkw3kzb2o"/><path fill="url(#iwPt3uy)" class="bkw3kzb2o"/><path fill="url(#iVqbwQd)" class="m1bnqqb6k"/><path fill="url(#ikFV3wd)" class="m1bnqqb6k"/><path fill="url(#iwAoUzb)" class="wgxfwnb9g"/><path fill="url(#ijxSbtZ)" class="wgxfwnb9g"/><path fill="url(#iZIOXsd)" class="ms87elb-e"/><path fill="url(#i5fhg2d)" class="ms87elb-e"/><path fill="url(#iVFu95T)" class="ms87elb-e"/><path fill="url(#ishXBXd)" class="laua0zbfl"/><path fill="url(#iMgCrRb)" class="e8alx3boy"/><g filter="url(#iM6w3pd)"><path fill="url(#iPRV0Sd)" class="ekmwwp6he"/></g><g filter="url(#iuRGHRc)"><path fill="url(#i4ZgvFd)" class="e9n9v48re"/><path fill="url(#iFL7fLc)" class="e9n9v48re"/></g><g filter="url(#iTsgLve)"><path class="wz6gk8b7h"/><path fill="url(#i5uEsIe)" class="xj3cpeb0l"/></g><g filter="url(#iKTYTDe)"><path class="mizhc4mmy"/><path fill="url(#i6Q0HFd)" class="x3e0ybbex"/></g><g filter="url(#i5Uprqb)"><path fill="url(#iNyJxpd)" class="wqsfuxbua"/><path fill="url(#iyRjVJr)" class="wqsfuxbua"/><path fill="url(#icEAW7c)" class="wqsfuxbua"/><path fill="url(#iw22fQc)" class="wqsfuxbua"/><path fill="url(#ipqp7Or)" class="wqsfuxbua"/><path fill="url(#iH5Rtbb)" class="wqsfuxbua"/><path fill="url(#i2WwwZd)" class="wqsfuxbua"/><path fill="url(#iffHi7b)" class="wqsfuxbua"/></g><path fill="url(#i7flRMb)" class="wqsfuxbua"/><path fill="url(#iGKb0Nm)" class="wqsfuxbua"/><path fill="url(#i4hI92o)" class="wqsfuxbua"/><g filter="url(#iNoUtIm)"><path class="abbollbxc"/></g><g filter="url(#ikvNnrp)"><path class="ar_b6nudx"/><path fill="url(#ivlzwdb)" class="qze94y9ya"/><path fill="url(#i0VjvhG)" class="qze94y9ya"/><path fill="url(#ikvWood)" class="qze94y9ya"/><path fill="url(#iGkuMte)" class="qze94y9ya"/></g><path fill="url(#ikuUqob)" class="qze94y9ya"/><path fill="url(#iVQmbPc)" class="qze94y9ya"/><g filter="url(#ieGrtMb)"><path stroke="url(#ikhSAzd)" class="sxjvr5bbd"/></g><path class="jdvrr4bki"/><g filter="url(#iq7Jz4b)"><path class="x0j5kq9cy"/></g><g filter="url(#i1smYae)"><path class="oerer4b3m"/></g><path class="u2ixadbmf"/><path fill="url(#iTR3Odb)" class="rmkfl0bjv"/><path class="lxwhz9cyk"/><g filter="url(#iRDujsb)"><path class="ggkjncceg"/><path fill="url(#i49uRjc)" class="py2dd4baz"/></g><g filter="url(#iZuRbhd)"><path fill="url(#iNblyfd)" class="qbnr5ccfc"/></g><path class="oj-r7qbzh"/><path fill="url(#iv7RIWb)" class="xf-1bnbrd"/><path class="nnsygdchs"/><g filter="url(#ivSosbe)"><path fill="url(#iRNGv8b)" class="k7hp83jwi"/></g><g filter="url(#iVw8fge)"><ellipse transform="rotate(-27.914 13.269 13.3)" class="bng3e90hp"/><ellipse fill="url(#irODOrb)" transform="rotate(-27.914 13.269 13.3)" class="q923i4b7z"/></g><path fill="url(#i2Wef1d)" class="yacjacccz"/><path fill="url(#iAvECrc)" class="yacjacccz"/><path fill="url(#iPHUYFd)" class="yacjacccz"/><path fill="url(#iXMTIBb)" class="yacjacccz"/><path fill="url(#iajAx2b)" class="yacjacccz"/><path fill="url(#iXqASBd)" class="yacjacccz"/><path fill="url(#iMLgQTb)" class="yacjacccz"/><path fill="url(#i3tCWcc)" class="yacjacccz"/><g filter="url(#immF9Xc)"><path fill="url(#i0JBewd)" class="f-z5vk62h"/><path fill="url(#iA7KXld)" class="f-z5vk62h"/><path fill="url(#iszGV9b)" class="f-z5vk62h"/><path fill="url(#i351hfc)" class="f-z5vk62h"/></g><path fill="url(#iDJTnsb)" class="fe6f5np8m"/><path fill="url(#iLaLawe)" class="fe6f5np8m"/><path fill="url(#iu2HU3b)" class="fe6f5np8m"/><path fill="url(#iRrXLNd)" class="fe6f5np8m"/><g filter="url(#iFRkHce)"><ellipse class="nt-_wr80m"/></g><defs><radialGradient id="iW8RNqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.67685 5.11426 -6.38874 -.84552 15.683 16.884)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iBDhsge" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.635 10.506)scale(3.90083 5.12539)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iNe4LWb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.754 9.78)scale(2.41433 1.85387)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iGdKHwb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.168 9.137)scale(2.77646 1.95577)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ipITAJe" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 1.866 12.511)scale(3.3137 4.59993)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iyb9LEJ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6169 1.61702 -2.25975 -2.2596 22.564 7.37)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iRfqrVb" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.287 8.303)scale(2.15391 4.49182)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i5Cdlxc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.84 9.942)scale(3.25593 4.14757)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iS4aSiu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01458 -2.973 2.35146 -.80247 21.33 10.393)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i9PMsAd" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -120.499 93.832)scale(1.69631 2.74851)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="irKe4cs" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 1.318 8.374)scale(3.27527 3.01918)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="i08HAYo" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.59375 -5.6138 0 16.011 20.61)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="cr7yd6bcj"/><stop offset="1" class="mv_v0947c"/></radialGradient><radialGradient id="ixLFgme" cx="0" cy="0" r="1" gradientTransform="matrix(-.96875 0 0 -5.28125 18.483 26.172)" gradientUnits="userSpaceOnUse"><stop class="ke__lf9po"/><stop offset="1" class="i5rrmccaf"/></radialGradient><radialGradient id="iRNOrCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.721 24.564)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="izlspBK" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.721 26.231)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="i3kJV0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.037)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="iFGqZ7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.042 20.266)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="intQq8b" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.279 27.384)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="i0QFqKc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.885)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="i1aP5Bc" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.341 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="i8sZbpU" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.659 22.544)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="ilGfS8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.659 27.938)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="in3x4bd" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.473 10.12)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="iwPt3uy" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.36)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="iVqbwQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.891)" gradientUnits="userSpaceOnUse"><stop class="ecitxobgm"/><stop offset="1" class="rk8_jsb0a"/></radialGradient><radialGradient id="iwAoUzb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2124 -8.20544 2.09119 -.30899 25.529 29.93)" gradientUnits="userSpaceOnUse"><stop class="wqe5m4buq"/><stop offset="1" class="zykt_9b7s"/></radialGradient><radialGradient id="ijxSbtZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .46978 0 23.659 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="cs69zqbom"/><stop offset="1" class="u77xpkbsk"/></radialGradient><radialGradient id="iZIOXsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09685 -3.968 0 16.021 20.59)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="xaehtwbwd"/><stop offset=".88" class="qj2c_jctc"/></radialGradient><radialGradient id="i5fhg2d" cx="0" cy="0" r="1" gradientTransform="rotate(124.232 3.699 15.26)scale(3.11083 1.51803)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="brq334vht"/><stop offset="1" class="ukqopzb2x"/></radialGradient><radialGradient id="iVFu95T" cx="0" cy="0" r="1" gradientTransform="rotate(150.285 5.654 12.362)scale(3.04044 5.42348)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="gpeilhbya"/><stop offset="1" class="hei205inv"/></radialGradient><radialGradient id="i4ZgvFd" cx="0" cy="0" r="1" gradientTransform="matrix(2.79215 -1.26916 1.54959 3.40908 20.7 14.57)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iFL7fLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.47598 .8273 -.2339 .41728 21.856 12.193)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="i5uEsIe" cx="0" cy="0" r="1" gradientTransform="matrix(1.69376 -.126 .09849 1.32404 21.094 14.204)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="i6Q0HFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35377 0 0 -1.06796 10.597 14.078)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iNyJxpd" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.136 8.848)scale(8.03385 10.7532)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="iyRjVJr" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28443 1.08898 -.75835 -1.59083 18.07 14.42)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="icEAW7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.2042 -3.89936 4.94757 1.5279 13.576 21.084)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iw22fQc" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 2.246 14.216)scale(7.68094 7.72207)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="ipqp7Or" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.36657 -7.40602 0 15.727 13.913)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="iH5Rtbb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.74658 1.52024 -2.61738 -13.3372 18.052 15.417)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="i2WwwZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2909 1.58429 0 18.603 13.006)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iffHi7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.47234 1.6874 0 13.692 12.75)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="i7flRMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44179 0 0 -7.23046 21.737 14.674)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iGKb0Nm" cx="0" cy="0" r="1" gradientTransform="rotate(139.279 6.645 13.396)scale(2.70712 1.81438)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="i4hI92o" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -8.61997 0 16.021 12.202)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="b5aje4-6n"/><stop offset="1" class="fdt-r-b0a"/></radialGradient><radialGradient id="ivlzwdb" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 14.66 .97)scale(2.34917 .72399)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iGkuMte" cx="0" cy="0" r="1" gradientTransform="matrix(-.87431 0 0 -.24443 16.632 15.727)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iVQmbPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53819 1.05602 -1.26917 -1.84866 16.444 15.06)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="iTR3Odb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91011 -1.44764 0 18.469 13.409)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i49uRjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26016 -.33525 .46156 -.35817 18.213 13.503)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iv7RIWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91012 -1.44764 0 13.573 13.409)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="irODOrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00868 -.55422 .6662 -.01043 13.252 13.654)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2Wef1d" cx="0" cy="0" r="1" gradientTransform="rotate(89.9 6.196 13.391)scale(4.18751 2.64389)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="iAvECrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 11.834 9.86)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="iPHUYFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.24 10.297)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iXMTIBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.177 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="iajAx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.302 2.703)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iXqASBd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.74 9.703)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="i3tCWcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 10.959 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iszGV9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.459 9.86)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="i351hfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.334 9.922)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="iRrXLNd" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.697 8.935)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="iCd195b" x1="21.286" x2="13.652" y1="6.279" y2="20.419" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iTFP0od" x1="9.158" x2="9.158" y1="21.199" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="igUtr8b" x1="21.034" x2="21.034" y1="19.735" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="ikFV3wd" x1="8.468" x2="6.8" y1="29.93" y2="29.77" gradientUnits="userSpaceOnUse"><stop offset=".333" class="x43wds7fi"/><stop offset="1" class="xjs932baa"/></linearGradient><linearGradient id="ishXBXd" x1="7.961" x2="24.088" y1="19.662" y2="19.662" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iMgCrRb" x1="7.961" x2="24.088" y1="19.628" y2="19.628" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iPRV0Sd" x1="8.697" x2="12.017" y1="14.176" y2="14.176" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="i0VjvhG" x1="14.968" x2="16.021" y1="15.572" y2="15.572" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="ikvWood" x1="16.021" x2="16.021" y1="16.468" y2="15.784" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="ikuUqob" x1="16.109" x2="16.109" y1="16.439" y2="16.282" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="ikhSAzd" x1="14.827" x2="15.344" y1="18.05" y2="17.25" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iNblyfd" x1="19.341" x2="18.989" y1="13.469" y2="13.686" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRNGv8b" x1="14.408" x2="14.056" y1="13.469" y2="13.686" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMLgQTb" x1="9.771" x2="10.584" y1="9.234" y2="9.234" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="i0JBewd" x1="15.81" x2="15.81" y1="2.07" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="iA7KXld" x1="15.81" x2="15.81" y1="2.07" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="iDJTnsb" x1="21.786" x2="5.158" y1="11.243" y2="11.243" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="iLaLawe" x1="15.587" x2="15.587" y1="9.842" y2="10.156" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iu2HU3b" x1="16.505" x2="16.505" y1="12.149" y2="10.896" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="iHOn6rc" width="17.097" height="17.597" x="7.598" y="3.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2949"/></filter><filter id="iM6w3pd" width="3.76" height="3.61" x="8.697" y="12.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2949"/></filter><filter id="iuRGHRc" width="3.61" height="3.86" x="19.778" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2949"/></filter><filter id="iTsgLve" width="3.41" height="3.41" x="19.878" y="12.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2949" stdDeviation=".25"/></filter><filter id="iKTYTDe" width="2.91" height="2.91" x="9.069" y="12.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2949" stdDeviation=".125"/></filter><filter id="i5Uprqb" width="11.432" height="12.451" x="10.305" y="8.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2949"/></filter><filter id="iNoUtIm" width="3.106" height="4.008" x="14.286" y="13.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2949" stdDeviation=".25"/></filter><filter id="ikvNnrp" width="2.606" height="3.508" x="14.718" y="13.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2949" stdDeviation=".125"/></filter><filter id="ieGrtMb" width="4.104" height="1.663" x="13.969" y="16.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2949" stdDeviation=".05"/></filter><filter id="iq7Jz4b" width="3.343" height="1.442" x="17.102" y="12.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2949"/></filter><filter id="i1smYae" width="3.343" height="1.442" x="11.598" y="12.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2949"/></filter><filter id="iRDujsb" width=".858" height=".757" x="17.657" y="12.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2949" stdDeviation=".05"/></filter><filter id="iZuRbhd" width=".951" height=".976" x="18.612" y="13.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2949" stdDeviation=".1"/></filter><filter id="ivSosbe" width="1.058" height="1.118" x="13.628" y="12.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2949" stdDeviation=".1"/></filter><filter id="iVw8fge" width="1" height=".766" x="12.769" y="12.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2949" stdDeviation=".05"/></filter><filter id="immF9Xc" width="5.791" height="8.428" x="12.915" y="2.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2949"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2949" result="effect2_innerShadow_4002_2949"/></filter><filter id="iFRkHce" width="7.654" height="2.528" x="15.502" y="9.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2949" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-construction-worker-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.abbollbxc {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.58 13.829l-.766 1.907a.605.605 0 0 0 .584.784h.882a.607.607 0 0 0 .584-.784l-.596-1.908c-.128-.422-.554-.422-.687 0");
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.aja9ggbky {
  d: path("M18.279 19.198c.608.134 1.195.31 1.763.537V29.93H18.28z");
}

.ar_b6nudx {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.592 13.673l-.596 1.907a.605.605 0 0 0 .584.785h.882a.607.607 0 0 0 .584-.785l-.596-1.907c-.128-.422-.724-.422-.858 0");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.b5aje4-6n {
  stop-color: var(--svg-color--381e24, #381E24);
}

.bkw3kzb2o {
  d: path("M22.025 20.77v9.16h-1.983V19.735c.698.28 1.355.62 1.983 1.034");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bng3e90hp {
  cx: 13.269px;
  cy: 13.301px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.437px;
  ry: 0.221px;
}

.brq334vht {
  stop-color: var(--svg-color--492a29, #492A29);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
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

.cr7yd6bcj {
  stop-color: var(--svg-color--9d67e1, #9D67E1);
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cs69zqbom {
  stop-color: var(--svg-color--8356c7, #8356C7);
}

.cwhvcxb2p {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.e8alx3boy {
  d: path("M16.05 19.629h-.046c.112 0 .213 0 .325.011c-.09-.011-.19-.011-.28-.011");
}

.e9n9v48re {
  d: path("M21.583 15.884a1.805 1.805 0 1 0 0-3.61a1.805 1.805 0 0 0 0 3.61");
}

.ecitxobgm {
  stop-color: var(--svg-color--966ce3, #966CE3);
}

.ekmwwp6he {
  d: path("M10.503 15.884a1.805 1.805 0 1 0 0-3.61a1.805 1.805 0 0 0 0 3.61");
}

.ex-0zhc5k {
  stop-color: var(--svg-color--e1926f, #E1926F);
}

.ez-c7ubrp {
  stop-color: var(--svg-color--da4708, #DA4708);
}

.f-z5vk62h {
  d: path("M14.615 2.07h2.39c.829 0 1.5.603 1.5 1.633v6.795h-5.39V3.703c0-1.03.671-1.633 1.5-1.633");
}

.f2js-baog {
  stop-color: var(--svg-color--cd963a, #CD963A);
}

.f3ael5nnj {
  d: path("M13.721 19.198c-.608.134-1.196.31-1.763.537V29.93h1.763z");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fdt-r-b0a {
  stop-color: var(--svg-color--381e24, #381E24);
  stop-opacity: 0;
}

.fe6f5np8m {
  d: path("M22.266 9.842H9.672a1.153 1.153 0 1 0 0 2.307h12.594c.642 0 1.153-.521 1.153-1.153a1.147 1.147 0 0 0-1.153-1.154");
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.ggkjncceg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.397 13.085c.072.095-.077.211-.247.338s-.295.216-.366.12c-.072-.095.008-.275.177-.401c.17-.127.365-.152.436-.057");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gpeilhbya {
  stop-color: var(--svg-color--422652, #422652);
  stop-opacity: 0;
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hb0fg9dnu {
  stop-color: var(--svg-color--c3a852, #C3A852);
}

.hei205inv {
  stop-color: var(--svg-color--422652, #422652);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.htellnhxv {
  stop-color: var(--svg-color--ffcf4c, #FFCF4C);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i5rrmccaf {
  stop-color: var(--svg-color--a271ef, #A271EF);
  stop-opacity: 0;
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.jdvrr4bki {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M16.021 17.345a3.4 3.4 0 0 1-1.595-.387c-.157-.082-.327.1-.228.246a2.167 2.167 0 0 0 3.646 0c.099-.152-.07-.328-.228-.246a3.4 3.4 0 0 1-1.595.387");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.julhe_bku {
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.k7hp83jwi {
  d: path("M14.486 13.757c0-.324-.264-.54-.335-.605l-.323.313l.199.406z");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.ke__lf9po {
  stop-color: var(--svg-color--a271ef, #A271EF);
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.laua0zbfl {
  d: path("M16.42 19.629c.28.011.571.034.863.056c-.292-.022-.572-.045-.864-.056");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmg939n4j {
  stop-color: var(--svg-color--e3b438, #E3B438);
}

.lsejgobiz {
  stop-color: var(--svg-color--e9b840, #E9B840);
}

.lxwhz9cyk {
  fill: var(--svg-color--000, #000);
  d: path("M17.898 13.875a.57.57 0 0 1 .573-.574a.57.57 0 0 1 .51.838h-1.015a.5.5 0 0 1-.068-.264");
}

.m1bnqqb6k {
  d: path("M4.601 29.93c.14-.946.34-1.882.62-2.786a11.56 11.56 0 0 1 3.12-5.019v7.805z");
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

.mgd_z41tu {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
  stop-opacity: 0;
}

.mizhc4mmy {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M10.524 15.283a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.ms43e0vsz {
  stop-color: var(--svg-color--cdac54, #CDAC54);
}

.ms87elb-e {
  d: path("M13.81 20.296c.06.797.585 2.392 2.211 2.392s2.151-1.595 2.211-2.392z");
}

.ms9ao5bgb {
  stop-color: var(--svg-color--d7a439, #D7A439);
}

.mv_v0947c {
  stop-color: var(--svg-color--a473f8, #A473F8);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mzrwpxbna {
  stop-color: var(--svg-color--dc5314, #DC5314);
  stop-opacity: 0;
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nnsygdchs {
  fill: var(--svg-color--000, #000);
  d: path("M14.144 13.875a.57.57 0 0 0-.573-.574a.57.57 0 0 0-.51.838h1.015a.6.6 0 0 0 .068-.264");
}

.npjjoacns {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
  stop-opacity: 0;
}

.nrsb-h28d {
  stop-color: var(--svg-color--c4a966, #C4A966);
}

.nt-_wr80m {
  cx: 19.329px;
  cy: 10.856px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 2.827px;
  ry: 0.264px;
}

.o043sbvrw {
  stop-color: var(--svg-color--fd4, #FD4);
}

.o2jd-jggt {
  stop-color: var(--svg-color--ffce64, #FFCE64);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o5ewjjbtz {
  stop-color: var(--svg-color--f9b14d, #F9B14D);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oerer4b3m {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.74 13.44c-.298-.524-.75-.938-1.724-.938a1.86 1.86 0 0 0-1.204.414c-.301.244-.261.556-.027.672l.623.356c.731-.236 1.54-.268 2.332-.504");
}

.oj-r7qbzh {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.339 12.568c-.733 0-1.352.505-1.52 1.188c-.05.196.1.382.3.382h2.503c.16 0 .287-.145.255-.305a1.57 1.57 0 0 0-1.538-1.265");
}

.omeu62b7c {
  stop-color: var(--svg-color--ff6f4e, #FF6F4E);
}

.oobbay99s {
  stop-color: var(--svg-color--c3a852, #C3A852);
  stop-opacity: 0;
}

.ououd5b1f {
  stop-color: var(--svg-color--f9cd2e, #F9CD2E);
}

.p-n74xx1h {
  stop-color: var(--svg-color--fb684a, #FB684A);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkk1wtbcw {
  d: path("M8.389 22.018a.15.15 0 0 0-.048.109v7.803h1.634v-9.16c-.56.37-1.092.79-1.586 1.248");
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.py2dd4baz {
  d: path("M18.397 13.085c.072.095-.077.211-.247.338s-.295.216-.366.12c-.072-.095.008-.275.177-.401c.17-.127.365-.152.436-.057");
}

.q923i4b7z {
  cx: 13.269px;
  cy: 13.301px;
  rx: 0.437px;
  ry: 0.221px;
}

.qbnr5ccfc {
  d: path("M19.363 13.743a.94.94 0 0 0-.26-.52l-.291.32l.131.257z");
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qf92jxbjd {
  stop-color: var(--svg-color--fe713a, #FE713A);
  stop-opacity: 0;
}

.qj2c_jctc {
  stop-color: var(--svg-color--3e212b, #3E212B);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qo0y3qb-y {
  stop-color: var(--svg-color--f46d40, #F46D40);
}

.qq6id-bgn {
  stop-color: var(--svg-color--ffee61, #FFEE61);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qze94y9ya {
  d: path("m15.592 13.673l-.596 1.907a.605.605 0 0 0 .584.785h.882a.607.607 0 0 0 .584-.785l-.596-1.907c-.128-.422-.724-.422-.858 0");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.rihmkq8le {
  d: path("M16.021 19.32c-.78 0-1.55.08-2.3.23v10.38h4.58V19.55c-.74-.15-1.5-.23-2.28-.23");
}

.rk8_jsb0a {
  stop-color: var(--svg-color--8d6fbf, #8D6FBF);
}

.rmkfl0bjv {
  d: path("M18.471 12.874a1 1 0 0 1 .965 1.265h-1.934a1.005 1.005 0 0 1 .97-1.265");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
}

.sxjvr5bbd {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.021 17.345a3.4 3.4 0 0 1-1.595-.387c-.157-.082-.327.1-.228.246a2.167 2.167 0 0 0 3.646 0c.099-.152-.07-.328-.228-.246a3.4 3.4 0 0 1-1.595.387Z");
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.thq31dj-g {
  stop-color: var(--svg-color--fe713a, #FE713A);
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.u2ixadbmf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.703 12.568c.733 0 1.352.505 1.52 1.188c.05.196-.1.382-.3.382H17.42a.258.258 0 0 1-.255-.305a1.57 1.57 0 0 1 1.538-1.265");
}

.u77xpkbsk {
  stop-color: var(--svg-color--8356c7, #8356C7);
  stop-opacity: 0;
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.ukqopzb2x {
  stop-color: var(--svg-color--492a29, #492A29);
  stop-opacity: 0;
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wgxfwnb9g {
  d: path("M27.399 29.93c-.14-.946-.34-1.882-.62-2.786a11.56 11.56 0 0 0-3.12-5.019v7.805z");
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.wqe5m4buq {
  stop-color: var(--svg-color--b087fd, #B087FD);
}

.wqsfuxbua {
  d: path("M10.314 12.662h.014l-.011-.298l-.012-.343c.023-1.065.644-1.477.909-1.614l.057-.023q.03-.014.058-.023a2.6 2.6 0 0 0 1.335-1.385l.091-.217a.296.296 0 0 1 .518-.057a4.33 4.33 0 0 0 3.578 1.877h3.612c.202 0 1.214.098 1.274 1.494l-.133 3.447c-.138 3.144-2.593 5.255-5.59 5.255s-5.452-2.111-5.59-5.255z");
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.wz6gk8b7h {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M21.583 15.283a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x0j5kq9cy {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.302 13.44c.298-.524.75-.938 1.725-.938c.426 0 .838.119 1.203.414c.302.244.261.556.028.672l-.624.356c-.731-.236-1.54-.268-2.332-.504");
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x3e0ybbex {
  d: path("M10.524 15.283a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.x43wds7fi {
  stop-color: var(--svg-color--735992, #735992);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.xaehtwbwd {
  stop-color: var(--svg-color--381b28, #381B28);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xf-1bnbrd {
  d: path("M13.571 12.874a1 1 0 0 0-.965 1.265h1.934q.036-.129.037-.264a1.01 1.01 0 0 0-1.006-1.001");
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xj3cpeb0l {
  d: path("M21.583 15.283a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.xj4nx8s9d {
  d: path("M23.627 22.032a.1.1 0 0 1 .032.073v7.825h-1.634v-9.16a12.5 12.5 0 0 1 1.602 1.262");
}

.xjs932baa {
  stop-color: var(--svg-color--735992, #735992);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xmtd48u_j {
  stop-color: var(--svg-color--ff7955, #FF7955);
}

.xnbb4159v {
  stop-color: var(--svg-color--cc6e42, #CC6E42);
}

.xr07nxbnn {
  stop-color: var(--svg-color--ffe550, #FFE550);
  stop-opacity: 0;
}

.xschf7bon {
  fill-rule: evenodd;
  d: path("M24.081 15.66a3.64 3.64 0 0 0 .364-1.6c0-.525-.108-1.017-.302-1.465h.006a3.6 3.6 0 0 0-.315-.576l-.003-.003c-.386-.59-.79-.733-.79-1.437l-1.765.483c0-2.044.308-4.745-1.736-4.745a.6.6 0 0 1-.51-.261a3.7 3.7 0 0 0-3.01-1.544a3.7 3.7 0 0 0-3.007 1.544a.63.63 0 0 1-.511.26l-.096.002c-2 .05-2.333 2.607-2.333 4.619l-1.078-.53c0 .704-.399 1.018-.784 1.609l-.003.004a3.7 3.7 0 0 0-.247 3.64c.08.159.08.352 0 .51a3.7 3.7 0 0 0-.363 1.579a3.605 3.605 0 0 0 3.61 3.61h9.626a3.605 3.605 0 0 0 3.61-3.61a3.66 3.66 0 0 0-.363-1.578a.58.58 0 0 1 0-.511m-13.753-2.998h-.014l1.345 2.642c.138 3.144 1.365 0 4.362 0s4.304 3.5 4.442.356l1.274-3.587c-.06-1.396-1.072-1.494-1.274-1.494H16.85a4.33 4.33 0 0 1-3.578-1.877a.296.296 0 0 0-.518.057l-.092.217a2.6 2.6 0 0 1-1.334 1.385l-.058.023q-.03.015-.057.023c-.265.137-.886.55-.909 1.614l.012.343z");
}

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.yacjacccz {
  d: path("M9.771 7.178a4.1 4.1 0 0 1 4.1-4.1h3.988a4.1 4.1 0 0 1 4.1 4.1V9.86H9.77z");
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yrdgovb8a {
  stop-color: var(--svg-color--fdbf28, #FDBF28);
  stop-opacity: 0;
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zykt_9b7s {
  stop-color: var(--svg-color--9879c9, #9879C9);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
