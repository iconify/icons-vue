<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ilrfONd)"><path fill="url(#iKhXjzM)" class="udeghrbqj"/><path fill="url(#iDKV0tc)" class="udeghrbqj"/><path fill="url(#iSc9Wvd)" class="udeghrbqj"/><path fill="url(#i01fBxe)" class="udeghrbqj"/></g><path fill="url(#iicL1gc)" class="xxsefzpdq"/><path fill="url(#iMvTABe)" class="xxsefzpdq"/><path fill="url(#iKkwVod)" class="nczmykb2q"/><path fill="url(#iqdGPbc)" class="nczmykb2q"/><path fill="url(#iYnd6Rc)" class="c-tja9bpr"/><path fill="url(#il3aafd)" class="c-tja9bpr"/><path fill="url(#iZQubKe)" class="c-tja9bpr"/><path fill="url(#ir2HP9d)" class="mspkabc6v"/><path fill="url(#ipOd9Xc)" class="mspkabc6v"/><path fill="url(#iVWGzDb)" class="mspkabc6v"/><path fill="url(#i6l3kGc)" class="mspkabc6v"/><g filter="url(#ijd0zpe)"><path class="fs1ufx2tc"/></g><path fill="url(#iLaes2w)" class="q9zrzf44o"/><g filter="url(#inkvUle)"><path class="ouoob-ulp"/></g><g filter="url(#igZnAqd)"><path fill="url(#iMm4Ddd)" class="d8vxffbru"/><path fill="url(#ideVytc)" class="d8vxffbru"/><path fill="url(#iNjTTxJ)" class="d8vxffbru"/></g><path fill="url(#iXFEZTd)" class="d8vxffbru"/><g filter="url(#iKwfMyF)"><path class="n7k0g1b5l"/></g><g filter="url(#iFsarXb)"><path fill="url(#itFU7Nd)" class="wd-dmob4h"/><path fill="url(#iXl3B5d)" class="wd-dmob4h"/></g><path fill="url(#iq5GnHe)" class="gael-ox4b"/><path fill="url(#iCZ4BTb)" class="gael-ox4b"/><path fill="url(#i03SEAe)" class="gael-ox4b"/><path fill="url(#iQwoj1d)" class="gael-ox4b"/><g filter="url(#i5nL3gb)"><path fill="url(#iMNODVc)" class="v6z_k_d_d"/></g><path fill="url(#iZ5PEfe)" class="zpz9k1skg"/><path fill="url(#ievyAtd)" class="zpz9k1skg"/><path fill="url(#ivb6Vbe)" class="zpz9k1skg"/><g filter="url(#itpZOKk)"><path fill="url(#ihQDfDb)" class="j15x05bur"/></g><g filter="url(#iHboF9c)"><path fill="url(#ijdUBqd)" class="r_vl-sbqf"/><path fill="url(#iDyZD6L)" class="r_vl-sbqf"/></g><g filter="url(#iatrIyg)"><path class="usxrj1w_z"/><path fill="url(#i9r5zAb)" class="sgyrsnb3c"/></g><g filter="url(#iTlkE1c)"><path class="rsg8qabkz"/><path fill="url(#i4FMR6c)" class="yscn_8bxn"/></g><g filter="url(#iGveyhy)"><path fill="url(#iuDyjLe)" class="n2kpppk1r"/><path fill="url(#idjY2Ub)" class="n2kpppk1r"/><path fill="url(#imLNSae)" class="n2kpppk1r"/><path fill="url(#iAbaFhe)" class="n2kpppk1r"/><path fill="url(#i0qkdNn)" class="n2kpppk1r"/><path fill="url(#i6mOwDb)" class="n2kpppk1r"/><path fill="url(#i37PRQc)" class="n2kpppk1r"/><path fill="url(#iS33sXd)" class="n2kpppk1r"/></g><path fill="url(#iTTvq3b)" class="n2kpppk1r"/><path fill="url(#iCDWZ6c)" class="n2kpppk1r"/><path fill="url(#iYR0Oib)" class="n2kpppk1r"/><g filter="url(#iHZqTkd)"><path class="id2zpx19p"/></g><g filter="url(#iqyvfvd)"><path class="ybthuqb6r"/><path fill="url(#iemCgYc)" class="hu9j2x_qi"/><path fill="url(#ivN9ltK)" class="hu9j2x_qi"/><path fill="url(#if1wYQb)" class="hu9j2x_qi"/><path fill="url(#i4gJGMd)" class="hu9j2x_qi"/><path fill="url(#iOjsmld)" class="hu9j2x_qi"/></g><path fill="url(#iGikXgb)" class="hu9j2x_qi"/><path fill="url(#iDRgcUd)" class="hu9j2x_qi"/><g filter="url(#iYV2u8K)"><path stroke="url(#iHLuuPd)" class="eg0g29bhv"/></g><path class="m_k8h2avt"/><g filter="url(#isUczUl)"><path class="i3phgrb_b"/></g><g filter="url(#is3HuzD)"><path class="jr4ysllwf"/></g><path class="gtshlzbwr"/><path fill="url(#ilN2oxe)" class="pu7ea5b-x"/><path class="t599r2wjp"/><g filter="url(#iXIoYdc)"><path class="f1s638bht"/><path fill="url(#iHyOJXb)" class="suka19rxv"/></g><g filter="url(#i0ZJ8Oq)"><path fill="url(#iNCZTad)" class="zigb4bbmt"/></g><path class="qu3o196cc"/><path fill="url(#i8V5sNc)" class="xh7uoab0h"/><path class="pqh2clb7j"/><g filter="url(#iZAWsTd)"><path fill="url(#id3jxAb)" class="eywgl9j9f"/></g><g filter="url(#iYhCiLc)"><ellipse transform="rotate(-27.914 13.452 9.975)" class="mp_eyyvlr"/><ellipse fill="url(#iNwNlDc)" transform="rotate(-27.914 13.452 9.975)" class="ekql31b4w"/></g><path fill="url(#iuF1cdb)" class="pc5nu3b6v"/><path fill="url(#ioXfSpM)" class="pb6u00bdc"/><g filter="url(#iGXwHhd)"><path class="kflbiccup"/></g><g filter="url(#iOTt0dc)"><path fill="url(#iyNkKHc)" class="te18_qled"/></g><path fill="url(#im41Hle)" class="wb9snib6m"/><path fill="url(#iik2bBb)" class="wb9snib6m"/><path fill="url(#iNQcnJd)" class="wb9snib6m"/><g filter="url(#i43iFob)"><path fill="url(#iorGERc)" class="ywpgx-8qy"/></g><path fill="url(#iRzB4mc)" class="d43ioubeg"/><path fill="url(#iUbYlyc)" class="d43ioubeg"/><path fill="url(#iEHuhpd)" class="d43ioubeg"/><g filter="url(#iTObx8m)"><path class="d-rslkbmf"/></g><g filter="url(#ifestGd)"><path fill="url(#iNlblBe)" class="wes-0ybwy"/><path fill="url(#i18Wkwz)" class="wes-0ybwy"/></g><g filter="url(#ilxjhFc)"><path fill="url(#iYqfV7X)" class="hdde0uvpo"/></g><g filter="url(#i3p0Lwb)"><path fill="url(#iRal8Sb)" class="yi-thdc0w"/></g><path fill="url(#izWDMkb)" class="yi-thdc0w"/><defs><radialGradient id="iDKV0tc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49222 1.63809 -.7506 -.68376 10.563 7.261)" gradientUnits="userSpaceOnUse"><stop class="byjccxdtl"/><stop offset="1" class="eav29bbfi"/></radialGradient><radialGradient id="iSc9Wvd" cx="0" cy="0" r="1" gradientTransform="matrix(2.00833 2.54688 -.66707 .52602 21.693 7.115)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="i6xvtdb8e"/><stop offset="1" class="stq0hsb2e"/></radialGradient><radialGradient id="i01fBxe" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.6875 -.86793 .24109 23.656 13.233)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="d42me8v-p"/><stop offset="1" class="kd3kb9bpm"/></radialGradient><radialGradient id="iMvTABe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.224 24.403)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="iKkwVod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.063 30)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iqdGPbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.13 30)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="iYnd6Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.615 30)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="iZQubKe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.708 29.637)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="ir2HP9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 16 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="i6l3kGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.255 30.216)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="iLaes2w" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 15.991 21.044)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="ideVytc" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.494 11.9)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="iNjTTxJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.295 23.22)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="iXl3B5d" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.036 15.867)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="iq5GnHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 16.005 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="adgho6gps"/><stop offset="1" class="p81iumb5r"/></radialGradient><radialGradient id="iCZ4BTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.24 19.685)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="iQwoj1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 1.60937 -.56235 .41494 19.375 17.468)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="p96-cobfo"/><stop offset="1" class="t_e0v9wgf"/></radialGradient><radialGradient id="iZ5PEfe" cx="0" cy="0" r="1" gradientTransform="rotate(89.999 -.228 16.205)scale(1.6196 2.56357)" gradientUnits="userSpaceOnUse"><stop class="v9dka4b0m"/><stop offset=".65" class="ao7qeo4nr"/></radialGradient><radialGradient id="ievyAtd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.87842 1.04823 -1.9814 -5.44089 16.935 16.296)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="nd0by9azb"/><stop offset="1" class="p9wj8bbrf"/></radialGradient><radialGradient id="ivb6Vbe" cx="0" cy="0" r="1" gradientTransform="rotate(125.991 4.866 12.57)scale(1.73802 1.29242)" gradientUnits="userSpaceOnUse"><stop class="robk3p81h"/><stop offset="1" class="fsheh0bba"/></radialGradient><radialGradient id="ijdUBqd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 19.945 11.107)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iDyZD6L" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 20.976 8.987)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="i9r5zAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.297 10.78)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="i4FMR6c" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.652 5.334)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iuDyjLe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.765 10.13)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="idjY2Ub" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.783 7.372)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="imLNSae" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.743 16.638)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iAbaFhe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.95312 -8.69132 0 15.905 9.818)" gradientUnits="userSpaceOnUse"><stop offset=".726" class="ld78_r53j"/><stop offset=".973" class="gcp0wezsc"/></radialGradient><radialGradient id="i0qkdNn" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.281 6.792)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="i6mOwDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.207 9.712)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="i37PRQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.829 9.483)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iS33sXd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.289 7.396)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iTTvq3b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21 11.2)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iCDWZ6c" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -1.5625 1.85526 2.0779 11.87 15.86)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="iYR0Oib" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.90625 -4.97773 0 15.375 7.896)" gradientUnits="userSpaceOnUse"><stop offset=".404" class="lpuoumypx"/><stop offset="1" class="h-gecbzwd"/></radialGradient><radialGradient id="iemCgYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.69 11.926)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i4gJGMd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.45 12.138)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iDRgcUd" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.35 8.297)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="ilN2oxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.088 10.07)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iHyOJXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.86 10.155)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8V5sNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.723 10.07)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iNwNlDc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.784 -1.47)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="im41Hle" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.485 2)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="iik2bBb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.798 4.31)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="iNQcnJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.38 4.747)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="iorGERc" cx="0" cy="0" r="1" gradientTransform="rotate(-96.626 13.263 -3.831)scale(3.52078 14.6419)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="iUbYlyc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.099 6.06)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iEHuhpd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.099 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="i18Wkwz" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.675 -1.206)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="iRal8Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.583 4.044)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="izWDMkb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 15.88 4.544)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><filter id="ilrfONd" width="15.646" height="10.422" x="8.153" y="6.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.219608 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.219608 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2462" result="effect2_innerShadow_4002_2462"/></filter><filter id="ijd0zpe" width="7.031" height="7.114" x="12.489" y="14.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".5"/></filter><filter id="inkvUle" width="4.951" height="14.36" x="9.117" y="15.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".5"/></filter><filter id="igZnAqd" width="3.097" height="14.304" x="10.348" y="15.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2462" result="effect2_innerShadow_4002_2462"/></filter><filter id="iKwfMyF" width="4.081" height="12.629" x="18.162" y="15.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".5"/></filter><filter id="iFsarXb" width="3.042" height="14.156" x="18.465" y="15.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2462" result="effect2_innerShadow_4002_2462"/></filter><filter id="i5nL3gb" width="2.735" height="2.58" x="14.632" y="18.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2462" result="effect2_innerShadow_4002_2462"/></filter><filter id="itpZOKk" width="3.368" height="3.218" x="9.611" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/></filter><filter id="iHboF9c" width="3.218" height="3.468" x="19.124" y="8.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/></filter><filter id="iatrIyg" width="3.148" height="3.148" x="19.159" y="9.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".25"/></filter><filter id="iTlkE1c" width="2.648" height="2.648" x="9.915" y="9.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".125"/></filter><filter id="iGveyhy" width="10.191" height="11.127" x="10.81" y="5.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/></filter><filter id="iHZqTkd" width="2.877" height="3.682" x="14.305" y="9.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".25"/></filter><filter id="iqyvfvd" width="2.377" height="3.182" x="14.717" y="9.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".125"/></filter><filter id="iYV2u8K" width="3.702" height="1.526" x="14.054" y="13.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".05"/></filter><filter id="isUczUl" width="3.001" height="1.285" x="16.848" y="9.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/></filter><filter id="is3HuzD" width="3.001" height="1.285" x="11.962" y="9.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/></filter><filter id="iXIoYdc" width=".787" height=".696" x="17.354" y="9.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".05"/></filter><filter id="i0ZJ8Oq" width=".891" height=".913" x="18.193" y="9.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".1"/></filter><filter id="iZAWsTd" width=".986" height="1.04" x="13.75" y="9.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".1"/></filter><filter id="iYhCiLc" width=".913" height=".704" x="12.996" y="9.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".05"/></filter><filter id="iGXwHhd" width="3.151" height="1.346" x="20.534" y="19.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".1"/></filter><filter id="iOTt0dc" width="2.881" height="1.03" x="20.734" y="19.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2462" result="effect2_innerShadow_4002_2462"/></filter><filter id="i43iFob" width="10.9" height="2.77" x="10.555" y="6.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/></filter><filter id="iTObx8m" width="4.831" height="2.64" x="13.59" y="2.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2462" stdDeviation=".125"/></filter><filter id="ifestGd" width="2.293" height="1.21" x="13.861" y="3.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/></filter><filter id="ilxjhFc" width="2.298" height="1.22" x="15.943" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/></filter><filter id="i3p0Lwb" width="1.63" height="1.63" x="15.295" y="3.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2462"/></filter><linearGradient id="iKhXjzM" x1="21.133" x2="15.976" y1="7.219" y2="17.128" gradientUnits="userSpaceOnUse"><stop class="trxz_2bws"/><stop offset="1" class="o-iy24ajy"/></linearGradient><linearGradient id="iicL1gc" x1="16" x2="16" y1="15.501" y2="30.001" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="il3aafd" x1="9.135" x2="6.943" y1="27.817" y2="27.817" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="ipOd9Xc" x1="16.505" x2="16.505" y1="30.466" y2="28.997" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="iVWGzDb" x1="19.067" x2="17.161" y1="26.56" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="iMm4Ddd" x1="13.295" x2="13.295" y1="29.372" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="iXFEZTd" x1="13.295" x2="13.295" y1="29.69" y2="23.356" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="itFU7Nd" x1="18.715" x2="19.724" y1="20.747" y2="20.747" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="i03SEAe" x1="13.583" x2="15.177" y1="16.56" y2="18.607" gradientUnits="userSpaceOnUse"><stop class="ovo1ps97q"/><stop offset="1" class="k5-d0pb7l"/><stop offset="1" class="mrezdm8zl"/></linearGradient><linearGradient id="iMNODVc" x1="15.991" x2="15.991" y1="19.225" y2="20.922" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="ihQDfDb" x1="9.662" x2="10.902" y1="10.755" y2="10.755" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="ivN9ltK" x1="14.967" x2="15.906" y1="11.999" y2="11.999" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="if1wYQb" x1="15.906" x2="15.906" y1="12.798" y2="12.188" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iOjsmld" x1="15.906" x2="15.906" y1="10.024" y2="10.724" gradientUnits="userSpaceOnUse"><stop class="gkndtibbl"/><stop offset="1" class="h5gbr7b1j"/></linearGradient><linearGradient id="iGikXgb" x1="15.984" x2="15.984" y1="12.772" y2="12.632" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="iHLuuPd" x1="14.841" x2="15.302" y1="14.208" y2="13.495" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iNCZTad" x1="18.866" x2="18.552" y1="10.125" y2="10.318" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="id3jxAb" x1="14.467" x2="14.153" y1="10.124" y2="10.318" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuF1cdb" x1="8.721" x2="23.097" y1="15.477" y2="15.477" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ioXfSpM" x1="8.721" x2="23.097" y1="15.447" y2="15.447" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iyNkKHc" x1="21.084" x2="22.88" y1="20.076" y2="20.711" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="iRzB4mc" x1="17.349" x2="11.13" y1="6.841" y2="6.841" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset=".875" class="ayzgumbov"/></linearGradient><linearGradient id="iNlblBe" x1="16.091" x2="14.513" y1="4.161" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="iYqfV7X" x1="18.083" x2="16.597" y1="3.169" y2="4.16" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-pilot-medium-dark" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.adgho6gps {
  stop-color: var(--svg-color--c9c0d4, #C9C0D4);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ao7qeo4nr {
  stop-color: var(--svg-color--713e51, #713E51);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.byjccxdtl {
  stop-color: var(--svg-color--4e4745, #4E4745);
}

.c-tja9bpr {
  d: path("M8.88 30V18.12a10.97 10.97 0 0 0-3.875 8.38V30z");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cit_-lbel {
  stop-color: var(--svg-color--e09037, #E09037);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cuwamcc7w {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.d-rslkbmf {
  fill: var(--svg-color--382534, #382534);
  d: path("M16.793 4.351h.633a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.275.475a.8.8 0 0 0-.415.006l-.272-.47a.2.2 0 0 0-.18-.11h-1.4c-.08 0-.13.09-.09.16l.54.94c.04.07.1.11.18.11h.66a.79.79 0 1 0 1.559 0");
}

.d42me8v-p {
  stop-color: var(--svg-color--3d3a3b, #3D3A3B);
}

.d43ioubeg {
  d: path("M15.955 5.52h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.d8vxffbru {
  d: path("M13.295 15.837q-.691.176-1.345.435l-.035.019l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.eav29bbfi {
  stop-color: var(--svg-color--4e4745, #4E4745);
  stop-opacity: 0;
}

.eg0g29bhv {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.906 13.58c-.521 0-1.01-.126-1.422-.345c-.14-.074-.292.088-.203.219a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345Z");
}

.ekql31b4w {
  cx: 13.452px;
  cy: 9.975px;
  rx: 0.39px;
  ry: 0.197px;
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eywgl9j9f {
  d: path("M14.537 10.381c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.f1s638bht {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.024 9.782c.064.085-.07.189-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.158-.358s.325-.136.39-.05");
}

.fs1ufx2tc {
  fill: var(--svg-color--8f809c, #8F809C);
  d: path("M16.005 15.348H13.49v4.74c0 .31.334.49.566.29l1.95-1.67l1.948 1.67c.232.2.567.02.567-.29v-4.74z");
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.fsheh0bba {
  stop-color: var(--svg-color--764e56, #764E56);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fxe3zh8pp {
  stop-color: var(--svg-color--3b3541, #3B3541);
}

.g-uemq__p {
  stop-color: var(--svg-color--59416c, #59416C);
}

.gael-ox4b {
  d: path("M16.005 15.284h-2.71v4.74c0 .31.36.49.61.29l2.1-1.67l2.1 1.67c.25.2.61.02.61-.29v-4.74z");
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gcp0wezsc {
  stop-color: var(--svg-color--79386b, #79386B);
}

.gkndtibbl {
  stop-color: var(--svg-color--7a4f52, #7A4F52);
}

.gtshlzbwr {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.297 9.322c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.231a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-gecbzwd {
  stop-color: var(--svg-color--63374a, #63374A);
  stop-opacity: 0;
}

.h5gbr7b1j {
  stop-color: var(--svg-color--7a4f52, #7A4F52);
  stop-opacity: 0;
}

.hdde0uvpo {
  d: path("M16.098 4.24h1.4a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.55.95c-.04.07.01.16.09.16");
}

.hi4tb8d4g {
  stop-color: var(--svg-color--80728b, #80728B);
}

.hm8qkhptt {
  stop-color: var(--svg-color--c47c25, #C47C25);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hqfmlmg6f {
  stop-color: var(--svg-color--483555, #483555);
}

.hu9j2x_qi {
  d: path("m15.523 10.307l-.531 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i3phgrb_b {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.048 10.099c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.269.217.233.495.024.599l-.556.318c-.652-.211-1.372-.24-2.078-.45");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.id2zpx19p {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.513 10.445l-.684 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.377-.493-.377-.612 0");
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_s_0lsgx {
  stop-color: var(--svg-color--524a68, #524A68);
}

.j15x05bur {
  d: path("M11.22 12.277a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jr4ysllwf {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.764 10.099c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.105-1.073.369c-.268.217-.232.495-.024.599l.556.318c.652-.211 1.372-.24 2.079-.45");
}

.jsljpd_vj {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
  stop-opacity: 0;
}

.k3jqbac6c {
  stop-color: var(--svg-color--eba026, #EBA026);
  stop-opacity: 0;
}

.k5-d0pb7l {
  stop-color: var(--svg-color--987a8d, #987A8D);
  stop-opacity: 0;
}

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.kd3kb9bpm {
  stop-color: var(--svg-color--3d3a3b, #3D3A3B);
  stop-opacity: 0;
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.kflbiccup {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.247 19.836h-.611c-.22 0-.42.13-.516.329c-.01.02-.038.02-.038 0a.57.57 0 0 0-.516-.33h-.592c-.124 0-.23.09-.239.22c-.01.13.096.25.22.25h.152c.18 0 .18.079.213.149c.057.12.172.2.306.2h.238l.54.128c.133 0 .46-.099.518-.219l.086-.199c.02-.04.057-.06.096-.06h.143c.124 0 .229-.09.238-.219c-.01-.14-.114-.25-.238-.25");
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l6siijbzt {
  stop-color: var(--svg-color--80728b, #80728B);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ld78_r53j {
  stop-color: var(--svg-color--7b4260, #7B4260);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln2o6octk {
  stop-color: var(--svg-color--3a3340, #3A3340);
  stop-opacity: 0;
}

.lpuoumypx {
  stop-color: var(--svg-color--63374a, #63374A);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m_k8h2avt {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M15.906 13.58c-.521 0-1.01-.126-1.422-.345c-.14-.074-.292.088-.203.219a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345");
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mp_eyyvlr {
  cx: 13.452px;
  cy: 9.975px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.mrezdm8zl {
  stop-color: var(--svg-color--4e4852, #4E4852);
  stop-opacity: 0;
}

.mspkabc6v {
  d: path("M18.705 16.11h-5.41V30h5.41z");
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.n-1p2p9pr {
  stop-color: var(--svg-color--615589, #615589);
}

.n2kpppk1r {
  d: path("M10.818 9.405h.013l-.01-.265l-.01-.306c.02-.95.573-1.317.81-1.439l.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.081-.194a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.081.087 1.135 1.332l-.119 3.073c-.123 2.803-2.312 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.n7k0g1b5l {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.055 20.479l.444 1.05c.202.26.272.65.178 1.01l-1.295 4.645l-.22-10.445l.09-.183q.507.173.989.423l.98 2.64c.07.19-.04.41-.202.41h-.816c-.187 0-.28.28-.148.45");
}

.nczmykb2q {
  d: path("M23.13 18.123V30h3.865v-3.5c0-3.356-1.5-6.36-3.865-8.377");
}

.nd0by9azb {
  stop-color: var(--svg-color--593439, #593439);
  stop-opacity: 0;
}

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-iy24ajy {
  stop-color: var(--svg-color--190326, #190326);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odfguq8mk {
  stop-color: var(--svg-color--5a4b85, #5A4B85);
}

.olptj6tus {
  stop-color: var(--svg-color--56466e, #56466E);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ouoob-ulp {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.795 16.462c-.46.117-.364.098-.8.27c-.54.784-1.546 2.2-1.85 2.874c-.09.19.05.41.26.41l1.18-.174c.24 0 .35.29.19.45l-1.37 1.196c-.26.26-.36.65-.23 1l2.893 6.334z");
}

.ovo1ps97q {
  stop-color: var(--svg-color--4e4852, #4E4852);
}

.oyco1db5g {
  stop-color: var(--svg-color--483555, #483555);
  stop-opacity: 0;
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p81iumb5r {
  stop-color: var(--svg-color--6d6675, #6D6675);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.p96-cobfo {
  stop-color: var(--svg-color--69646e, #69646E);
}

.p9wj8bbrf {
  stop-color: var(--svg-color--593439, #593439);
}

.pb6u00bdc {
  d: path("M15.93 15.448h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.pc5nu3b6v {
  d: path("M16.26 15.448c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.pj095ubna {
  stop-color: var(--svg-color--635870, #635870);
  stop-opacity: 0;
}

.pk_fxjb0k {
  stop-color: var(--svg-color--6e658c, #6E658C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp0fzgbhc {
  stop-color: var(--svg-color--ce8634, #CE8634);
}

.pqh2clb7j {
  fill: var(--svg-color--000, #000);
  d: path("M14.233 10.486a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.pu7ea5b-x {
  d: path("M18.09 9.594a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.q6gdl1i5d {
  stop-color: var(--svg-color--695978, #695978);
}

.q9zrzf44o {
  d: path("M15.517 21.044a.25.25 0 0 0-.247.212l-1.335 8.745h4.12l-1.33-8.745a.25.25 0 0 0-.247-.212z");
}

.qg2z49_rr {
  stop-color: var(--svg-color--564973, #564973);
}

.qga7xqb8q {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
}

.qk2jzhbua {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
}

.qu3o196cc {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.515 9.322c-.654 0-1.205.45-1.355 1.059a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_vl-sbqf {
  d: path("M20.733 12.277a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rgck1cbbg {
  stop-color: var(--svg-color--eba026, #EBA026);
}

.rndoiibli {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
  stop-opacity: 0;
}

.robk3p81h {
  stop-color: var(--svg-color--764e56, #764E56);
}

.rsg8qabkz {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.24 11.742a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.s59tlt20i {
  stop-color: var(--svg-color--7d77a7, #7D77A7);
}

.sgyrsnb3c {
  d: path("M20.733 11.742a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.suka19rxv {
  d: path("M18.024 9.782c.064.085-.07.189-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.158-.358s.325-.136.39-.05");
}

.t_e0v9wgf {
  stop-color: var(--svg-color--69646e, #69646E);
  stop-opacity: 0;
}

.t599r2wjp {
  fill: var(--svg-color--000, #000);
  d: path("M17.579 10.486c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.te18_qled {
  d: path("M23.365 19.78h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.trxz_2bws {
  stop-color: var(--svg-color--211622, #211622);
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.udeghrbqj {
  d: path("M10.636 6.706h10.68c.092.577.528.993.98 1.425c.285.273.577.552.792.882c.625.958.461 1.953.176 2.937c-.076.264-.072.494 0 .637c.133.32.285.785.285 1.295a3.24 3.24 0 0 1-3.246 3.246H11.65a3.24 3.24 0 0 1-3.246-3.246c0-.51.153-.975.286-1.295c.071-.143.055-.445 0-.637c-.286-.984-.45-1.979.176-2.937c.214-.33.506-.609.792-.882c.452-.432.888-.848.98-1.425");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.usxrj1w_z {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.733 11.742a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v6z_k_d_d {
  d: path("m14.732 19.661l1.267-1.097l1.268 1.074l-.546 1.265a.24.24 0 0 1-.216.141h-1.022a.24.24 0 0 1-.216-.141z");
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.v9dka4b0m {
  stop-color: var(--svg-color--753a5c, #753A5C);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.w4yfy3zsx {
  stop-color: var(--svg-color--c7bbd0, #C7BBD0);
}

.w784rnm9d {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
  stop-opacity: 0;
}

.wb9snib6m {
  d: path("M21.747 3.55c-2.66-1.66-5.7-1.55-5.74-1.55s-3.14-.01-5.74 1.54c-1 .6-1.19 1.96-.39 2.8l.68.72h10.9l.68-.72c.8-.83.6-2.18-.39-2.79");
}

.wd-dmob4h {
  d: path("m19.865 19.79l1.36 1.33c.26.26.35.65.23 1.01l-2.74 7.86V15.836l.117.032q.653.174 1.272.424l1.261 2.64c.09.19-.05.41-.26.41h-1.05c-.24 0-.36.28-.19.45");
}

.wes-0ybwy {
  d: path("M16.045 4.24h-1.4a.2.2 0 0 1-.18-.11l-.54-.94c-.04-.07.01-.16.09-.16h1.4a.2.2 0 0 1 .18.11l.55.95c.03.06-.02.15-.1.15");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xh7uoab0h {
  d: path("M13.721 9.594a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.xxsefzpdq {
  d: path("M16.005 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ybthuqb6r {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.523 10.307l-.531 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.ydmi_gbdg {
  stop-color: var(--svg-color--5a4b81, #5A4B81);
}

.yfv60kbve {
  stop-color: var(--svg-color--514476, #514476);
  stop-opacity: 0;
}

.yi-thdc0w {
  d: path("M16.085 5.16a.79.79 0 1 0 0-1.58a.79.79 0 0 0 0 1.58");
}

.yscn_8bxn {
  d: path("M11.24 11.742a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ywpgx-8qy {
  d: path("M16.005 6.33s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.zigb4bbmt {
  d: path("M18.885 10.369a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zpz9k1skg {
  d: path("M15.976 18.503c1.79-.788 1.932-1.316 1.92-1.7v-.99h-3.839v.99c-.013.384.224.97 1.92 1.7");
}

</style>
