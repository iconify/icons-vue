<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4j4Zhb)"><path fill="url(#iFOMDte)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#ifnvh2d)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#ioKxIBe)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iier0mc)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iu54eYM)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#ibpjXtm)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#inG62Ub)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iAPVCor)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iC2p3Uc)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iz0Kere)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#ioxVpxK)" clip-rule="evenodd" class="g-fa2m3lw"/></g><g filter="url(#iSF4wAc)"><path fill="url(#ifiAdUi)" class="ylwpyxpit"/></g><g filter="url(#idAZsIe)"><path fill="url(#i1PyAwb)" class="f11-aub0q"/><path fill="url(#ivh8aLe)" class="f11-aub0q"/></g><g filter="url(#iuQ0Wwv)"><path class="tvljpdb8m"/><path fill="url(#itAEHHc)" class="p6zaajppg"/></g><g filter="url(#iSAQKJn)"><path class="su1mnhj-w"/><path fill="url(#ikG0yZd)" class="f007bp1ul"/></g><g filter="url(#iiI4yQd)"><path fill="url(#iRxkhSb)" class="irmntbcmp"/><path fill="url(#i9RKZns)" class="irmntbcmp"/><path fill="url(#iW6OsCc)" class="irmntbcmp"/><path fill="url(#ii3xfEK)" class="irmntbcmp"/><path fill="url(#ipwT0bb)" class="irmntbcmp"/><path fill="url(#i0eZxTc)" class="irmntbcmp"/><path fill="url(#iPjjfJj)" class="irmntbcmp"/><path fill="url(#iBNF5ne)" class="irmntbcmp"/><path fill="url(#iDakcgd)" class="irmntbcmp"/></g><path fill="url(#iQzXmvd)" class="irmntbcmp"/><path fill="url(#ieM8Yze)" class="irmntbcmp"/><g filter="url(#iK00OMl)"><path class="senk-zbyq"/></g><g filter="url(#i8Lqoue)"><path class="k82wc4bih"/><path fill="url(#i4JHueB)" class="g65p4x7tf"/><path fill="url(#izh6uGe)" class="g65p4x7tf"/><path fill="url(#i13W77c)" class="g65p4x7tf"/><path fill="url(#iqt3dKb)" class="g65p4x7tf"/></g><path fill="url(#iCHyP4f)" class="g65p4x7tf"/><path fill="url(#iWZpq4d)" class="g65p4x7tf"/><g filter="url(#it5A8md)"><path class="uvor8nbbc"/></g><g filter="url(#iDhGT7b)"><path class="it6nhblbi"/></g><path class="iwsk8qbgx"/><path fill="url(#i7QDFVd)" class="y123fuz1j"/><path class="uefdqc9nj"/><g filter="url(#ix19plo)"><path class="h1g0vw0qt"/><path fill="url(#iLUUCoI)" class="crtuyac6r"/></g><g filter="url(#iRTi4zt)"><path fill="url(#iUu6Eue)" class="va-go5bwh"/></g><path class="o0ok5qkkx"/><path fill="url(#i4D75Gb)" class="sr0h1d87b"/><path class="rh8zr1bra"/><g filter="url(#ixhCMOe)"><path fill="url(#iBXPAcU)" class="kx0iqc05r"/></g><g filter="url(#ixWmBpe)"><ellipse transform="rotate(-27.914 12.899 11.9)" class="g_9po2pxb"/><ellipse fill="url(#is6fTtb)" transform="rotate(-27.914 12.899 11.9)" class="cyaokcc9k"/></g><g filter="url(#ipyqotb)"><path class="pbyooeb-t"/><path fill="url(#iNXif1d)" class="joi5rjocn"/></g><g filter="url(#i93oNob)"><path class="zz2w-l5db"/><path fill="url(#iTrYVsm)" class="mvim7ccql"/><path fill="url(#ilRem7c)" class="mvim7ccql"/></g><g filter="url(#igNnzVo)"><path stroke="url(#idDbnre)" class="kog8wrbvt"/></g><g filter="url(#i4B6Uqw)"><path class="jcjzpbbaz"/></g><g filter="url(#iYkqjlA)"><path class="a6pcdgmkm"/></g><g filter="url(#iR1QWkd)"><path class="pz33-rohp"/></g><g filter="url(#ieKw2Bb)"><path class="o4dsycb9t"/></g><g filter="url(#i59skwc)"><path class="lxo6-yb9g"/></g><path class="perb44bls"/><path fill="url(#imX5tuc)" class="blkufcbkz"/><path fill="url(#iklKFhd)" class="blkufcbkz"/><path fill="url(#iF26lYJ)" class="blkufcbkz"/><path fill="url(#ibkOc1D)" class="m_uqd5bep"/><path fill="url(#iMTbu0a)" class="f15z0sb-m"/><path fill="url(#iuFoQfc)" class="f15z0sb-m"/><path fill="url(#iNJVqsc)" class="f15z0sb-m"/><path fill="url(#iZQduEe)" class="f15z0sb-m"/><path fill="url(#iitk95b)" class="f15z0sb-m"/><path fill="url(#iV4RBve)" class="f15z0sb-m"/><path fill="url(#ikX8Wzd)" class="f15z0sb-m"/><path fill="url(#iWHd6np)" class="mxno9qm9q"/><path fill="url(#iMRBetc)" class="mxno9qm9q"/><path fill="url(#i7tVwed)" class="yk_uyhgen"/><path fill="url(#ifcYKSc)" class="yk_uyhgen"/><path fill="url(#iNr6HFe)" class="yk_uyhgen"/><path fill="url(#i0mjutc)" class="yk_uyhgen"/><path fill="url(#ilW9mac)" class="d074i_boa"/><path fill="url(#iyklWTb)" class="d074i_boa"/><path fill="url(#iQeClcd)" class="d074i_boa"/><path fill="url(#izwZFPq)" class="grxl85bvp"/><path fill="url(#idEGNEC)" class="grxl85bvp"/><path fill="url(#io10Yge)" class="pmce5gb2r"/><path fill="url(#iOWN36d)" class="pmce5gb2r"/><path fill="url(#iKjZevk)" class="pmce5gb2r"/><path fill="url(#idkl72b)" class="pmce5gb2r"/><g filter="url(#ieB4xiD)"><path fill="url(#ijgIBde)" class="thixcfbik"/><path fill="url(#iPfGK8b)" class="thixcfbik"/></g><path fill="url(#i7Y9EUb)" class="thixcfbik"/><g filter="url(#i73LLfc)"><path fill="url(#iEZreGd)" class="kv5z55b-o"/></g><defs><radialGradient id="ifnvh2d" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 .828 14.8)scale(5.79283 7.23642)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ioKxIBe" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.546 9.974)scale(4.38021 5.75526)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iier0mc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.719 8.969)scale(2.71103 2.0817)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iu54eYM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62572 2.66023 -1.8739 -1.14518 10.457 10.496)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ibpjXtm" cx="0" cy="0" r="1" gradientTransform="matrix(1.73125 3.29364 -4.57208 2.40325 11.555 2.621)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="inG62Ub" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 10.583 7.453)scale(2.56774 3.58838)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iAPVCor" cx="0" cy="0" r="1" gradientTransform="matrix(-2.32233 .67562 -1.40896 -4.84304 25.448 11.7)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iC2p3Uc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 11.358 9.523)scale(3.65605 4.65727)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iz0Kere" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.063 -3.534)scale(3.52739 2.78996)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ioxVpxK" cx="0" cy="0" r="1" gradientTransform="matrix(1.89438 .1987 -.32196 3.06944 8.252 11.654)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i1PyAwb" cx="0" cy="0" r="1" gradientTransform="matrix(3.13528 -1.42513 1.74002 3.82804 21.077 13.325)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="ivh8aLe" cx="0" cy="0" r="1" gradientTransform="matrix(1.65737 .92898 -.26264 .46856 22.376 10.655)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="itAEHHc" cx="0" cy="0" r="1" gradientTransform="matrix(1.9019 -.14147 .1106 1.48676 21.52 12.914)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="ikG0yZd" cx="0" cy="0" r="1" gradientTransform="rotate(-180 5.097 6.386)scale(1.33012)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iRxkhSb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.468 8.197)scale(9.02114 12.0746)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="i9RKZns" cx="0" cy="0" r="1" gradientTransform="matrix(-2.74634 1.20848 -.84156 -1.91251 18.471 13.17)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iW6OsCc" cx="0" cy="0" r="1" gradientTransform="matrix(1.62385 -4.94828 6.27844 2.06036 13.266 20.292)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="ii3xfEK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61822 9.28749 -11.6092 -2.02275 17.277 11.57)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ermiffb8a"/><stop offset="1" class="d5lrpr21j"/></radialGradient><radialGradient id="ipwT0bb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.89626 -7.93854 0 15.66 12.586)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="plx9t1yez"/><stop offset="1" class="tcn1mccqj"/></radialGradient><radialGradient id="i0eZxTc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.44 8.026)scale(8.86449 15.2619)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iPjjfJj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44954 1.77899 0 18.888 11.568)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iBNF5ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.65328 1.89477 0 13.373 11.28)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iDakcgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09608 4.0645 -3.25227 -.87704 17.731 8.65)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iQzXmvd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61898 0 0 -8.11903 22.407 13.442)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="ieM8Yze" cx="0" cy="0" r="1" gradientTransform="rotate(-84.552 17.45 2.339)scale(6.07309 10.454)" gradientUnits="userSpaceOnUse"><stop class="h20fabc7c"/><stop offset="1" class="e8xzy9rwp"/></radialGradient><radialGradient id="i4JHueB" cx="0" cy="0" r="1" gradientTransform="matrix(-.57381 -2.5747 .7935 -.17684 16.977 14.357)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iqt3dKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.98176 0 0 -.27447 16.675 14.624)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iWZpq4d" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.08 9.491)scale(2.09509 2.51797)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="i7QDFVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02196 -1.62554 0 18.738 12.02)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iLUUCoI" cx="0" cy="0" r="1" gradientTransform="matrix(-.29213 -.37645 .51828 -.4022 18.45 12.127)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4D75Gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02196 -1.62555 0 13.24 12.02)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="is6fTtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00974 -.62233 .74807 -.01171 12.88 12.296)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNXif1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.58969 -3.47082 1.77558 .81324 8.862 9.35)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iTrYVsm" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.32 7.178)scale(6.13805 10.0354)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ilRem7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.26494 1.72216 -3.70514 -.57001 16.253 3.256)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="imX5tuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.8125 10.4384 0 16.562 30.373)" gradientUnits="userSpaceOnUse"><stop class="gfj1348zm"/><stop offset=".714" class="vqiy7zq_f"/></radialGradient><radialGradient id="iklKFhd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.407)" gradientUnits="userSpaceOnUse"><stop class="uatqp3rks"/><stop offset="1" class="oln0s8bds"/></radialGradient><radialGradient id="iF26lYJ" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.189)" gradientUnits="userSpaceOnUse"><stop class="leds28lfi"/><stop offset="1" class="x0hvtbbrr"/></radialGradient><radialGradient id="ibkOc1D" cx="0" cy="0" r="1" gradientTransform="matrix(2.6551 1.32154 -2.0509 4.12044 8.345 17.211)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="xjoxl1baz"/><stop offset="1" class="xm7oxtb8r"/></radialGradient><radialGradient id="iMTbu0a" cx="0" cy="0" r="1" gradientTransform="matrix(16.5217 8.52358 -2.95327 5.72447 14.913 18.627)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="fupnc-bzv"/><stop offset="1" class="h4nid6imp"/></radialGradient><radialGradient id="iuFoQfc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.125 2.06252 -1.29855 -3.22666 31 24.171)" gradientUnits="userSpaceOnUse"><stop class="qomb6ec0x"/><stop offset="1" class="ha79_8bui"/></radialGradient><radialGradient id="iNJVqsc" cx="0" cy="0" r="1" gradientTransform="rotate(116.107 1.618 13.268)scale(4.96085 7.77144)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="vxxihotpt"/><stop offset="1" class="amuq4_bzy"/></radialGradient><radialGradient id="iitk95b" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.39 -3.09)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="fjifp0bsg"/><stop offset="1" class="wn5ytjbyn"/></radialGradient><radialGradient id="ikX8Wzd" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -3 .29081 .6725 18.155 24.451)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="zlawngbku"/><stop offset="1" class="oc_o5xbok"/></radialGradient><radialGradient id="iWHd6np" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 .59375 -1.31526 -3.21892 23.405 17.78)" gradientUnits="userSpaceOnUse"><stop class="y0cud7bhd"/><stop offset="1" class="irfgqiu-v"/></radialGradient><radialGradient id="i7tVwed" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.845)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y0d2ypbdf"/><stop offset="1" class="tmdmcl4vt"/></radialGradient><radialGradient id="ilW9mac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.43)" gradientUnits="userSpaceOnUse"><stop class="qyctpef7w"/><stop offset=".615" class="cskv_pboi"/></radialGradient><radialGradient id="izwZFPq" cx="0" cy="0" r="1" gradientTransform="rotate(25.705 -36.997 15.768)scale(1.9602 2.66792)" gradientUnits="userSpaceOnUse"><stop class="t0phas2np"/><stop offset=".697" class="f1gbiwx_q"/></radialGradient><radialGradient id="idEGNEC" cx="0" cy="0" r="1" gradientTransform="matrix(-.8664 .26697 -.4987 -1.61843 4.82 17.168)" gradientUnits="userSpaceOnUse"><stop class="w_6w3opsv"/><stop offset="1" class="u9mvxzbci"/></radialGradient><radialGradient id="io10Yge" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.291 6.337)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="g4wyz37uu"/><stop offset="1" class="xjh-ixbfp"/></radialGradient><radialGradient id="iOWN36d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 .59376 -.2045 -.35517 30.162 13.19)" gradientUnits="userSpaceOnUse"><stop class="d-by8cbiw"/><stop offset="1" class="hqjfx29jv"/></radialGradient><radialGradient id="idkl72b" cx="0" cy="0" r="1" gradientTransform="rotate(-25.641 56.237 -44.01)scale(2.59977 2.78402)" gradientUnits="userSpaceOnUse"><stop class="ma1u1iuqv"/><stop offset="1" class="rizivib-o"/></radialGradient><radialGradient id="iPfGK8b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.25)" gradientUnits="userSpaceOnUse"><stop class="whmlezbbn"/><stop offset="1" class="r8d20-6qp"/></radialGradient><radialGradient id="i7Y9EUb" cx="0" cy="0" r="1" gradientTransform="matrix(1.00475 -.26214 .85754 3.28688 4.382 18.154)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="bwst52bsk"/><stop offset="1" class="br5e4xb7k"/></radialGradient><filter id="i4j4Zhb" width="19.167" height="19.667" x="6.53" y="1.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/></filter><filter id="iSF4wAc" width="4.204" height="4.054" x="8.06" y="10.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/></filter><filter id="idAZsIe" width="4.054" height="4.304" x="20.043" y="10.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/></filter><filter id="iuQ0Wwv" width="3.706" height="3.706" x="20.217" y="10.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".25"/></filter><filter id="iSAQKJn" width="3.206" height="3.206" x="8.508" y="11.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".125"/></filter><filter id="iiI4yQd" width="12.837" height="13.901" x="9.571" y="6.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/></filter><filter id="iK00OMl" width="3.365" height="4.378" x="14.102" y="11.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".25"/></filter><filter id="i8Lqoue" width="2.865" height="3.878" x="14.557" y="11.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".125"/></filter><filter id="it5A8md" width="3.729" height="1.619" x="17.228" y="11.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/></filter><filter id="iDhGT7b" width="3.729" height="1.619" x="11.022" y="11.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/></filter><filter id="ix19plo" width=".939" height=".825" x="17.839" y="11.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".05"/></filter><filter id="iRTi4zt" width="1.019" height="1.047" x="18.923" y="11.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".1"/></filter><filter id="ixhCMOe" width="1.139" height="1.206" x="13.326" y="11.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".1"/></filter><filter id="ixWmBpe" width="1.098" height=".835" x="12.35" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".05"/></filter><filter id="ipyqotb" width="5.298" height="5.678" x="7.989" y="4.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/><feGaussianBlur result="effect2_foregroundBlur_3987_24798" stdDeviation=".25"/></filter><filter id="i93oNob" width="10.901" height="7.153" x="12.073" y="2.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/><feGaussianBlur result="effect2_foregroundBlur_3987_24798" stdDeviation=".125"/></filter><filter id="igNnzVo" width="1.286" height="2.754" x="12.047" y="4.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".1"/></filter><filter id="i4B6Uqw" width="8.206" height="4.358" x="15.201" y="5.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".5"/></filter><filter id="iYkqjlA" width="2.884" height="1.34" x="11.376" y="9.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/></filter><filter id="iR1QWkd" width="2.884" height="1.34" x="17.939" y="9.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/></filter><filter id="ieKw2Bb" width="2.617" height="1.134" x="11.536" y="9.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".1"/></filter><filter id="i59skwc" width="2.617" height="1.134" x="17.946" y="9.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".1"/></filter><filter id="ieB4xiD" width="7.3" height="8.016" x="2" y="12.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.290196 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24798"/></filter><filter id="i73LLfc" width="5.538" height="5.423" x="24.197" y="13.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24798" stdDeviation=".2"/></filter><linearGradient id="iFOMDte" x1="21.901" x2="13.329" y1="4.015" y2="19.892" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="ifiAdUi" x1="8.124" x2="9.687" y1="12.882" y2="12.882" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="izh6uGe" x1="14.807" x2="15.989" y1="14.449" y2="14.449" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="i13W77c" x1="15.989" x2="15.989" y1="15.456" y2="14.687" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iCHyP4f" x1="16.087" x2="16.087" y1="15.423" y2="15.247" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="iUu6Eue" x1="19.718" x2="19.322" y1="12.088" y2="12.332" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBXPAcU" x1="14.177" x2="13.782" y1="12.088" y2="12.332" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idDbnre" x1="12.347" x2="13.033" y1="4.965" y2="6.569" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iZQduEe" x1="9.156" x2="10.486" y1="18.47" y2="19.093" gradientUnits="userSpaceOnUse"><stop class="x0-05wb5o"/><stop offset="1" class="b_wdx7bxu"/></linearGradient><linearGradient id="iV4RBve" x1="17.482" x2="17.906" y1="26.675" y2="25.72" gradientUnits="userSpaceOnUse"><stop class="jbvrfolcv"/><stop offset=".46" class="byl3sfbil"/></linearGradient><linearGradient id="iMRBetc" x1="24.108" x2="23.968" y1="18.281" y2="18.347" gradientUnits="userSpaceOnUse"><stop class="zb0hqnb-l"/><stop offset="1" class="sqzs4ozft"/></linearGradient><linearGradient id="ifcYKSc" x1="14.945" x2="14.231" y1="27.114" y2="25.507" gradientUnits="userSpaceOnUse"><stop class="na3bqccxs"/><stop offset="1" class="tndlebqua"/></linearGradient><linearGradient id="iNr6HFe" x1="22.968" x2="21.812" y1="18.64" y2="19.203" gradientUnits="userSpaceOnUse"><stop class="fp2c12bya"/><stop offset="1" class="xyqac8gqa"/></linearGradient><linearGradient id="i0mjutc" x1="3.231" x2="6.517" y1="28.257" y2="26.65" gradientUnits="userSpaceOnUse"><stop class="m_3r9vbdq"/><stop offset="1" class="iioqnhb4d"/></linearGradient><linearGradient id="iyklWTb" x1="28.085" x2="27.547" y1="19.477" y2="18.645" gradientUnits="userSpaceOnUse"><stop offset=".198" class="y5l4vob7e"/><stop offset="1" class="yemvrmxbd"/></linearGradient><linearGradient id="iQeClcd" x1="26.75" x2="27.494" y1="17.361" y2="18.12" gradientUnits="userSpaceOnUse"><stop offset=".353" class="vhav-abny"/><stop offset="1" class="m754bqf9r"/></linearGradient><linearGradient id="iKjZevk" x1="25.489" x2="25.997" y1="14.252" y2="15.151" gradientUnits="userSpaceOnUse"><stop class="sghkjcc6n"/><stop offset="1" class="n39i5izax"/></linearGradient><linearGradient id="ijgIBde" x1="8" x2="5.5" y1="15.72" y2="19.486" gradientUnits="userSpaceOnUse"><stop offset=".206" class="inmwvkbzn"/><stop offset="1" class="myckyxb_u"/></linearGradient><linearGradient id="iEZreGd" x1="29.217" x2="24.074" y1="14.816" y2="17.683" gradientUnits="userSpaceOnUse"><stop class="hdh7eybjd"/><stop offset="1" class="d3plm5x9f"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-no-medium-dark" /></template>
<style>
.a6pcdgmkm {
  fill: var(--svg-color--352827, #352827);
  d: path("M11.388 10.154a.35.35 0 0 1 .25-.426l2.086-.543a.349.349 0 0 1 .175.675l-2.086.543a.35.35 0 0 1-.425-.25");
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.amuq4_bzy {
  stop-color: var(--svg-color--9771d7, #9771D7);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b_wdx7bxu {
  stop-color: var(--svg-color--62429a, #62429A);
  stop-opacity: 0;
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.blkufcbkz {
  d: path("M25.5 29.97h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.br5e4xb7k {
  stop-color: var(--svg-color--805c58, #805C58);
  stop-opacity: 0;
}

.bwst52bsk {
  stop-color: var(--svg-color--805c58, #805C58);
}

.byl3sfbil {
  stop-color: var(--svg-color--684c9e, #684C9E);
  stop-opacity: 0;
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
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

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.crtuyac6r {
  d: path("M18.657 11.657c.08.107-.087.238-.277.38s-.332.242-.412.135s.01-.309.2-.451s.41-.171.49-.064");
}

.cskv_pboi {
  stop-color: var(--svg-color--794f40, #794F40);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyaokcc9k {
  cx: 12.899px;
  cy: 11.9px;
  rx: 0.491px;
  ry: 0.248px;
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d-by8cbiw {
  stop-color: var(--svg-color--9d7d73, #9D7D73);
}

.d074i_boa {
  d: path("M24.75 19.773a.885.885 0 0 1 .35-1.203l2.609-1.428a.899.899 0 1 1 .856 1.581l-2.621 1.404a.885.885 0 0 1-1.194-.354");
}

.d3plm5x9f {
  stop-color: var(--svg-color--9c7b72, #9C7B72);
  stop-opacity: 0;
}

.d5lrpr21j {
  stop-color: var(--svg-color--793e68, #793E68);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e8xzy9rwp {
  stop-color: var(--svg-color--5a3839, #5A3839);
  stop-opacity: 0;
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.ermiffb8a {
  stop-color: var(--svg-color--793e68, #793E68);
  stop-opacity: 0;
}

.f007bp1ul {
  d: path("M10.111 14.125a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.f11-aub0q {
  d: path("M22.07 14.8a2.027 2.027 0 1 0 0-4.054a2.027 2.027 0 0 0 0 4.053");
}

.f15z0sb-m {
  d: path("m11.56 16.068l15.407 7.178a3.53 3.53 0 0 1 1.7 4.687a3.52 3.52 0 0 1-4.679 1.704L8.581 22.45a1.003 1.003 0 0 1-.483-1.341l2.123-4.567a1.004 1.004 0 0 1 1.339-.474");
}

.f1gbiwx_q {
  stop-color: var(--svg-color--6a3849, #6A3849);
}

.fjifp0bsg {
  stop-color: var(--svg-color--745b8c, #745B8C);
}

.fp2c12bya {
  stop-color: var(--svg-color--a680df, #A680DF);
}

.ft5dv1b6b {
  fill: none;
}

.fupnc-bzv {
  stop-color: var(--svg-color--8066bd, #8066BD);
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g_9po2pxb {
  cx: 12.899px;
  cy: 11.9px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.491px;
  ry: 0.248px;
}

.g-fa2m3lw {
  fill-rule: evenodd;
  d: path("M25.04 14.548a4.1 4.1 0 0 0 .408-1.797c0-.589-.121-1.141-.339-1.645h.007a4 4 0 0 0-.354-.646l-.003-.004a4.1 4.1 0 0 1-.663-2.23v-.013a4.156 4.156 0 0 0-4.155-4.156a.68.68 0 0 1-.574-.293A4.16 4.16 0 0 0 15.99 2.03c-1.39 0-2.626.688-3.378 1.734a.71.71 0 0 1-.574.293l-.107.001a4.156 4.156 0 0 0-4.048 4.155v.012c0 .79-.23 1.568-.663 2.231l-.003.005a4.16 4.16 0 0 0-.278 4.087c.09.178.09.395 0 .574a4.1 4.1 0 0 0-.408 1.772a4.05 4.05 0 0 0 4.054 4.053h10.81a4.05 4.05 0 0 0 4.054-4.053c0-.638-.153-1.237-.408-1.772a.65.65 0 0 1 0-.574M9.597 11.182H9.58l1.51 2.967c.155 3.53 1.533 0 4.898 0s4.832 3.93 4.988.399l1.43-4.027c-.067-1.568-1.204-1.678-1.43-1.678H16.92a4.87 4.87 0 0 1-4.018-2.108a.332.332 0 0 0-.58.064l-.104.244A2.9 2.9 0 0 1 10.72 8.6q-.03.01-.064.025l-.065.026c-.297.154-.994.617-1.02 1.812l.013.386z");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g4wyz37uu {
  stop-color: var(--svg-color--8f655e, #8F655E);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g65p4x7tf {
  d: path("m15.507 12.317l-.67 2.142a.68.68 0 0 0 .657.88h.99a.68.68 0 0 0 .656-.88l-.67-2.142c-.143-.474-.812-.474-.963 0");
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gfj1348zm {
  stop-color: var(--svg-color--6547af, #6547AF);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.grxl85bvp {
  d: path("M7.246 19.743a.885.885 0 0 0-.351-1.203l-2.553-1.398a.899.899 0 1 0-.855 1.581l2.565 1.374a.885.885 0 0 0 1.194-.354");
}

.h1g0vw0qt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.657 11.657c.08.107-.087.238-.277.38s-.332.242-.412.135s.01-.309.2-.451s.41-.171.49-.064");
}

.h20fabc7c {
  stop-color: var(--svg-color--5a3839, #5A3839);
}

.h4nid6imp {
  stop-color: var(--svg-color--593b97, #593B97);
}

.ha79_8bui {
  stop-color: var(--svg-color--8e7cc9, #8E7CC9);
  stop-opacity: 0;
}

.hdh7eybjd {
  stop-color: var(--svg-color--9c7b72, #9C7B72);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hqjfx29jv {
  stop-color: var(--svg-color--9d7d73, #9D7D73);
  stop-opacity: 0;
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.iioqnhb4d {
  stop-color: var(--svg-color--604c85, #604C85);
  stop-opacity: 0;
}

.inmwvkbzn {
  stop-color: var(--svg-color--916a5a, #916A5A);
}

.irfgqiu-v {
  stop-color: var(--svg-color--58448e, #58448E);
}

.irmntbcmp {
  d: path("M9.581 11.182h.016l-.013-.334l-.013-.386c.026-1.195.723-1.658 1.02-1.812l.065-.026l.064-.025a2.9 2.9 0 0 0 1.499-1.556l.103-.244a.332.332 0 0 1 .581-.064a4.87 4.87 0 0 0 4.018 2.108h4.056c.226 0 1.363.11 1.43 1.678l-.15 3.87c-.155 3.53-2.911 5.901-6.276 5.901s-6.122-2.37-6.277-5.9z");
}

.it6nhblbi {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.55 12.056c-.334-.588-.842-1.053-1.936-1.053c-.479 0-.94.133-1.351.464c-.339.274-.293.624-.031.755l.7.4c.821-.265 1.73-.301 2.619-.566");
}

.iwsk8qbgx {
  fill: var(--svg-color--fff, #fff);
  d: path("M19 11.077a1.76 1.76 0 0 1 1.707 1.334a.345.345 0 0 1-.337.429h-2.81a.29.29 0 0 1-.286-.342A1.76 1.76 0 0 1 19 11.077");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jbvrfolcv {
  stop-color: var(--svg-color--684c9e, #684C9E);
}

.jcjzpbbaz {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m19.02 7.506l-1.795.33a.867.867 0 1 1-.158-1.72h2.949c1.744 0 2.32 1.758 2.391 2.359a3.96 3.96 0 0 0-3.387-.97");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.joi5rjocn {
  d: path("M9.604 5.23c.712-.756 2.06-.757 2.684-.644l.498 1.626c-.318-.05-.602.063-.84.295C11.38 8.095 9.438 8.97 8.538 9.21c-.187-1.88.137-2.998 1.065-3.98");
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.k82wc4bih {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.507 12.317l-.67 2.142a.68.68 0 0 0 .657.88h.99a.68.68 0 0 0 .656-.88l-.67-2.142c-.143-.474-.812-.474-.963 0");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kog8wrbvt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.347 4.532c.03.306.296 1.457.686 2.153");
}

.kv5z55b-o {
  d: path("M26.691 15.593c.527-.847 1.795-1.665 2.462-1.988a.13.13 0 0 1 .153.034a.132.132 0 0 1-.034.196c-2.06 1.273-1.875 1.785-2.645 3.097c-.354.605-1.176 1.113-1.556 1.284l-.474-.899c.53-.28 1.463-.711 2.094-1.724");
}

.kx0iqc05r {
  d: path("M14.265 12.411c0-.363-.296-.605-.375-.678l-.364.351l.224.455z");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.leds28lfi {
  stop-color: var(--svg-color--785e96, #785E96);
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

.lxo6-yb9g {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.263 9.973l-2.017-.533");
}

.m_3r9vbdq {
  stop-color: var(--svg-color--604c85, #604C85);
  stop-opacity: 0.939;
}

.m_uqd5bep {
  d: path("m6.81 20.54l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.m754bqf9r {
  stop-color: var(--svg-color--734a39, #734A39);
  stop-opacity: 0;
}

.ma1u1iuqv {
  stop-color: var(--svg-color--7e4a51, #7E4A51);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mvim7ccql {
  d: path("M15.23 2.959c-1.428-.315-2.709 1.108-2.857 1.636c1.325 4.466 4.677 4.221 7.987 3.853c1.98-.22 2.195.683 2.364 1.12c0-4.954-4.212-5.884-7.459-6.601z");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mxno9qm9q {
  d: path("m25.19 20.54l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.myckyxb_u {
  stop-color: var(--svg-color--713e45, #713E45);
}

.n39i5izax {
  stop-color: var(--svg-color--704b3d, #704B3D);
  stop-opacity: 0;
}

.na3bqccxs {
  stop-color: var(--svg-color--6a44b0, #6A44B0);
}

.o0ok5qkkx {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.977 11.077a1.76 1.76 0 0 0-1.706 1.334a.344.344 0 0 0 .337.429h2.81a.29.29 0 0 0 .287-.342a1.765 1.765 0 0 0-1.728-1.421");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o4dsycb9t {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.836 9.973l2.017-.533");
}

.oc_o5xbok {
  stop-color: var(--svg-color--5d3ca0, #5D3CA0);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.oln0s8bds {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
  stop-opacity: 0;
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

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p6zaajppg {
  d: path("M22.07 14.125a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pbyooeb-t {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M9.604 5.23c.712-.756 2.06-.757 2.684-.644l.498 1.626c-.318-.05-.602.063-.84.295C11.38 8.095 9.438 8.97 8.538 9.21c-.187-1.88.137-2.998 1.065-3.98");
}

.perb44bls {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M15.989 19.42c.791 0 1.433-.688 1.433-1.537c0-.85-.642-1.538-1.433-1.538s-1.433.689-1.433 1.538s.642 1.537 1.433 1.537");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plx9t1yez {
  stop-color: var(--svg-color--885485, #885485);
  stop-opacity: 0;
}

.pmce5gb2r {
  d: path("m23 16.04l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.pz33-rohp {
  fill: var(--svg-color--352827, #352827);
  d: path("M20.711 10.154a.35.35 0 0 0-.25-.426l-2.086-.543a.349.349 0 0 0-.175.675l2.086.543a.35.35 0 0 0 .425-.25");
}

.qomb6ec0x {
  stop-color: var(--svg-color--8e7cc9, #8E7CC9);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qyctpef7w {
  stop-color: var(--svg-color--9a7b71, #9A7B71);
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r8d20-6qp {
  stop-color: var(--svg-color--8d6d68, #8D6D68);
  stop-opacity: 0;
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rh8zr1bra {
  fill: var(--svg-color--000, #000);
  d: path("M13.882 12.544a.64.64 0 0 0-.644-.644a.64.64 0 0 0-.572.94h1.139a.64.64 0 0 0 .077-.296");
}

.rizivib-o {
  stop-color: var(--svg-color--7e4a51, #7E4A51);
  stop-opacity: 0;
}

.senk-zbyq {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.495 12.492l-.861 2.141a.68.68 0 0 0 .655.881h.99a.68.68 0 0 0 .657-.88l-.67-2.142c-.143-.475-.621-.475-.771 0");
}

.sghkjcc6n {
  stop-color: var(--svg-color--704b3d, #704B3D);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sqzs4ozft {
  stop-color: var(--svg-color--8071aa, #8071AA);
  stop-opacity: 0;
}

.sr0h1d87b {
  d: path("M13.238 11.42a1.124 1.124 0 0 0-1.083 1.42h2.171a1.2 1.2 0 0 0 .041-.296a1.13 1.13 0 0 0-1.13-1.125");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.su1mnhj-w {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M10.111 14.125a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.t0phas2np {
  stop-color: var(--svg-color--694641, #694641);
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tcn1mccqj {
  stop-color: var(--svg-color--885485, #885485);
}

.thixcfbik {
  d: path("m9 16.04l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.tmdmcl4vt {
  stop-color: var(--svg-color--69569a, #69569A);
}

.tndlebqua {
  stop-color: var(--svg-color--6a44b0, #6A44B0);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tvljpdb8m {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M22.07 14.125a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.u9mvxzbci {
  stop-color: var(--svg-color--592f28, #592F28);
  stop-opacity: 0;
}

.uatqp3rks {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
}

.uefdqc9nj {
  fill: var(--svg-color--000, #000);
  d: path("M18.096 12.544c0-.358.287-.644.644-.644a.64.64 0 0 1 .572.94h-1.139a.6.6 0 0 1-.077-.296");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uvor8nbbc {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.428 12.056c.334-.588.842-1.053 1.936-1.053c.48 0 .941.133 1.352.464c.338.274.293.624.03.755l-.7.4c-.82-.265-1.729-.301-2.618-.566");
}

.va-go5bwh {
  d: path("M19.741 12.396a1.06 1.06 0 0 0-.291-.583l-.327.359l.147.287z");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vhav-abny {
  stop-color: var(--svg-color--734a39, #734A39);
}

.vqiy7zq_f {
  stop-color: var(--svg-color--53329c, #53329C);
}

.vxxihotpt {
  stop-color: var(--svg-color--9771d7, #9771D7);
}

.w_6w3opsv {
  stop-color: var(--svg-color--592f28, #592F28);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.whmlezbbn {
  stop-color: var(--svg-color--8d6d68, #8D6D68);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wn5ytjbyn {
  stop-color: var(--svg-color--745b8c, #745B8C);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x0-05wb5o {
  stop-color: var(--svg-color--62429a, #62429A);
}

.x0hvtbbrr {
  stop-color: var(--svg-color--785e96, #785E96);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xjoxl1baz {
  stop-color: var(--svg-color--76679f, #76679F);
}

.xm7oxtb8r {
  stop-color: var(--svg-color--433169, #433169);
}

.xyqac8gqa {
  stop-color: var(--svg-color--a680df, #A680DF);
  stop-opacity: 0;
}

.y0cud7bhd {
  stop-color: var(--svg-color--705f9f, #705F9F);
}

.y0d2ypbdf {
  stop-color: var(--svg-color--8b64ce, #8B64CE);
}

.y123fuz1j {
  d: path("M18.74 11.42a1.124 1.124 0 0 1 1.083 1.42h-2.171a1.13 1.13 0 0 1 1.088-1.42");
}

.y5l4vob7e {
  stop-color: var(--svg-color--7e4a52, #7E4A52);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yemvrmxbd {
  stop-color: var(--svg-color--7e4a52, #7E4A52);
  stop-opacity: 0;
}

.yk_uyhgen {
  d: path("M20.44 16.069L5.033 23.24a3.53 3.53 0 0 0-1.7 4.69a3.516 3.516 0 0 0 4.679 1.706l15.407-7.183c.503-.232.724-.837.483-1.342l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.ylwpyxpit {
  d: path("M10.087 14.8a2.027 2.027 0 1 0 0-4.055a2.027 2.027 0 0 0 0 4.054");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zb0hqnb-l {
  stop-color: var(--svg-color--8071aa, #8071AA);
}

.zlawngbku {
  stop-color: var(--svg-color--5d3ca0, #5D3CA0);
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zz2w-l5db {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.23 2.959c-1.428-.315-2.709 1.108-2.857 1.636c1.325 4.466 4.677 4.221 7.987 3.853c1.98-.22 2.195.683 2.364 1.12c0-4.954-4.212-5.884-7.459-6.601z");
}

</style>
