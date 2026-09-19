<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ieu9mia)" class="ul8yzzy5p"/><path fill="url(#i9Pkuzb)" class="ul8yzzy5p"/><path fill="url(#ilHe0je)" class="ul8yzzy5p"/><path fill="url(#iW2aO1d)" class="ul8yzzy5p"/><path fill="url(#iO9wWrc)" class="ul8yzzy5p"/><path fill="url(#iWlVjCe)" class="ul8yzzy5p"/><path fill="url(#i4C6idc)" class="n8khjlbdo"/><path fill="url(#iQLLrqc)" class="n8khjlbdo"/><path fill="url(#iNdG3pd)" class="n8khjlbdo"/><path fill="url(#i2ZIBcd)" class="dy84ygb3l"/><g filter="url(#iTEe5yb)"><path fill="url(#icGkw2c)" class="sxxddhjsf"/><path fill="url(#imVONQe)" class="sxxddhjsf"/></g><path fill="url(#iSSJLie)" class="keu943bph"/><path fill="url(#iVVWgNZ)" class="keu943bph"/><path fill="url(#iK9bZDd)" class="keu943bph"/><path fill="url(#itoQg6b)" class="szk9545gm"/><path fill="url(#ihJBaCe)" class="szk9545gm"/><path fill="url(#iaLPX5c)" class="szk9545gm"/><path fill="url(#i4bjaEi)" class="s8lgxzbhp"/><path fill="url(#iRfgk9d)" class="s8lgxzbhp"/><path fill="url(#ionLtJb)" class="s8lgxzbhp"/><path fill="url(#iON7EjQ)" class="s8lgxzbhp"/><path fill="url(#iP7PWPb)" class="s8lgxzbhp"/><path fill="url(#isclF0d)" class="s8lgxzbhp"/><path fill="url(#iDRXN4c)" class="s8lgxzbhp"/><g filter="url(#i1Kvood)"><path fill="url(#iS9Ev6d)" class="pg2upnb0g"/><path fill="url(#ilM9P2b)" class="pg2upnb0g"/><path fill="url(#i04SaQd)" class="pg2upnb0g"/><path fill="url(#iTvoGjb)" class="pg2upnb0g"/><path fill="url(#i94wRLj)" class="pg2upnb0g"/><path stroke="url(#itYBDkS)" class="winht877z"/></g><path fill="url(#iq5grxc)" class="k6ft4_b3l"/><g filter="url(#iLoFYPd)"><path class="ut5qt-u_y"/></g><path fill="url(#iwAayAd)" class="iq1u3k1wa"/><path fill="url(#i7iIApe)" class="iq1u3k1wa"/><g filter="url(#i4cYwIe)"><path class="no9fnjgey"/></g><g filter="url(#iqyIVhc)"><path fill="url(#iSFZpOe)" class="gemps2knm"/><path fill="url(#idvaCco)" class="gemps2knm"/><path fill="url(#iDwP91d)" class="gemps2knm"/><path fill="url(#ihZrSNc)" class="gemps2knm"/></g><g filter="url(#iA3UMyR)"><path class="psfq9ybev"/></g><g filter="url(#iH4RX4d)"><path class="ry34eabsg"/></g><path fill="url(#iMqLKNi)" class="hw09ab0hr"/><path fill="url(#iTaoqmb)" class="hw09ab0hr"/><path fill="url(#iw1jnOc)" class="hw09ab0hr"/><path fill="url(#iVCvCWd)" class="hw09ab0hr"/><path clip-rule="evenodd" class="uhjhn9b3f"/><path clip-rule="evenodd" class="akjkhoqir"/><g filter="url(#ifJDoBA)"><path fill="url(#i92Wl0b)" clip-rule="evenodd" class="uw344gogm"/></g><path class="hyyp17b7p"/><path fill="url(#ipeSu8w)" class="kj9xuub5a"/><path class="gkfgd-bym"/><g filter="url(#ikacAJb)"><path class="uxgwypbgl"/><path fill="url(#iB8NdPb)" class="bcd-hkbhh"/></g><g filter="url(#iGLnWHc)"><path fill="url(#ijrqUJx)" class="vx2arccxn"/></g><path fill="url(#iFF7vHd)" class="k5i1obbcc"/><path fill="url(#iR34W2c)" class="k5i1obbcc"/><path class="xus5pkr-r"/><path fill="url(#i9HBkgc)" class="fwd3q-uyq"/><path class="lrepv5bkn"/><g filter="url(#ici4HQe)"><path fill="url(#iovA8Pd)" class="c2cwddcfn"/></g><g filter="url(#iiyVM3c)"><ellipse transform="rotate(-27.914 13.258 14.375)" class="uaw_s5rgf"/><ellipse fill="url(#iJHhAQb)" transform="rotate(-27.914 13.258 14.375)" class="bj_c06brs"/></g><g filter="url(#iDRbQne)"><path fill="url(#iGIpk4H)" class="mvc25evki"/><path fill="url(#iWGPb8d)" class="mvc25evki"/><path fill="url(#iGWAD2d)" class="mvc25evki"/><path fill="url(#igTqeBd)" class="mvc25evki"/></g><path fill="url(#i8p1Rze)" class="u9gp0acpk"/><path fill="url(#ighTuLd)" class="u9gp0acpk"/><path fill="url(#ikiAMVQ)" class="sn5zqwaoh"/><g filter="url(#iuJZ6Vf)"><path stroke="url(#ikyJE0b)" class="cb13voduh"/></g><path class="q9eu_1urh"/><g filter="url(#i5JNXdc)"><path fill="url(#iusn0Be)" clip-rule="evenodd" class="e-eqv1h-i"/><path fill="url(#ijEiKbA)" clip-rule="evenodd" class="e-eqv1h-i"/><path fill="url(#iqZStCK)" clip-rule="evenodd" class="e-eqv1h-i"/></g><path fill="url(#ierK1Be)" clip-rule="evenodd" class="e-eqv1h-i"/><g filter="url(#iH6kqLc)"><path clip-rule="evenodd" class="zvz_j9byp"/></g><path class="nv3141b3h"/><path fill="url(#ifRwArc)" class="b5djzgbgl"/><path fill="url(#ioJqUBc)" class="b5djzgbgl"/><path fill="url(#iiIKKOb)" class="b5djzgbgl"/><path fill="url(#inytbpY)" class="b5djzgbgl"/><path fill="url(#ivsZ1re)" class="b5djzgbgl"/><g filter="url(#i51zgki)"><path fill="url(#iuq2Xrd)" class="hoa8-tbfc"/><path fill="url(#iQuYeGb)" class="hoa8-tbfc"/><path fill="url(#igZuAnd)" class="hoa8-tbfc"/><path fill="url(#ifTjdid)" class="hoa8-tbfc"/><path fill="url(#imOHbge)" class="hoa8-tbfc"/></g><g filter="url(#izpZVte)"><path stroke="url(#i0y7jKK)" class="h7wfmk73a"/></g><g filter="url(#icmYWQc)"><path stroke="url(#ihqE12b)" class="qbutz3c9r"/></g><g filter="url(#i4RW9Dc)"><path stroke="url(#ipRK7de)" class="gkr7_8biz"/></g><defs><radialGradient id="ieu9mia" cx="0" cy="0" r="1" gradientTransform="rotate(123.947 4.952 16.492)scale(10.1334 22.4724)" gradientUnits="userSpaceOnUse"><stop class="ul10cac5y"/><stop offset="1" class="ionth7brd"/></radialGradient><radialGradient id="i9Pkuzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.25 -2.59375 0 11.679 23.469)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="xa-9it8ui"/><stop offset="1" class="nvrzpdhpt"/></radialGradient><radialGradient id="ilHe0je" cx="0" cy="0" r="1" gradientTransform="matrix(.875 0 0 11.2188 8.616 30)" gradientUnits="userSpaceOnUse"><stop class="p09j7tbqs"/><stop offset="1" class="w08nqeb6o"/></radialGradient><radialGradient id="iW2aO1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16162 -2.40625 0 19.773 25.12)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="r-f_l1b-y"/><stop offset="1" class="l8yphmoyw"/></radialGradient><radialGradient id="iO9wWrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 0 0 -10.5 23.085 25.344)" gradientUnits="userSpaceOnUse"><stop class="rhfs4jg4m"/><stop offset="1" class="vji5arydn"/></radialGradient><radialGradient id="iWlVjCe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.06247 -8.71874 18.10537 -8.43613 14.554 30)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="zquyghcdt"/><stop offset="1" class="hb0k2h_0q"/></radialGradient><radialGradient id="i4C6idc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7196 0 0 -11.0312 8.636 30)" gradientUnits="userSpaceOnUse"><stop offset=".291" class="xc-1yb-kl"/><stop offset="1" class="zrfo1hnzb"/></radialGradient><radialGradient id="iQLLrqc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.32545 -.78123 1.83121 -10.13886 9.241 30.469)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="z6vkgyynh"/><stop offset="1" class="hidyelbxs"/></radialGradient><radialGradient id="iNdG3pd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.74003 .48334 0 8.636 25.303)" gradientUnits="userSpaceOnUse"><stop class="li354g47q"/><stop offset="1" class="lmtqybbtc"/></radialGradient><radialGradient id="i2ZIBcd" cx="0" cy="0" r="1" gradientTransform="matrix(.68645 6.66194 -2.21693 .22843 23.108 23.338)" gradientUnits="userSpaceOnUse"><stop class="cdhdhx4uq"/><stop offset="1" class="b8c389gzb"/></radialGradient><radialGradient id="icGkw2c" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 .96875 -.2841 1.50295 17.07 3.156)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="s_1mw_rhq"/><stop offset="1" class="pql562bff"/></radialGradient><radialGradient id="iSSJLie" cx="0" cy="0" r="1" gradientTransform="matrix(-4.62501 2.59374 -3.8683 -6.89775 17.977 3.813)" gradientUnits="userSpaceOnUse"><stop offset=".063" class="uhl03ccti"/><stop offset="1" class="uuh3gfbsu"/></radialGradient><radialGradient id="iK9bZDd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 -1.30125 2.428 -12.47818 18.758 7.531)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="tsk-k9bvn"/><stop offset="1" class="phlvo2b_b"/></radialGradient><radialGradient id="i4bjaEi" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15156 -24.7184 0 15.739 9.328)" gradientUnits="userSpaceOnUse"><stop class="r-yilwbra"/><stop offset=".652" class="vxkgnhd4n"/></radialGradient><radialGradient id="iRfgk9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.64742 -17.2274 0 13.01 8.976)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="huu-ickwn"/><stop offset="1" class="t4ibp7bdp"/></radialGradient><radialGradient id="ionLtJb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68356 0 0 -2.80263 25.965 10.705)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="p5_1r5b0y"/><stop offset="1" class="bkffn87la"/></radialGradient><radialGradient id="iON7EjQ" cx="0" cy="0" r="1" gradientTransform="matrix(-10.1661 0 0 -1.56292 25.083 9.55)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="zdk8j6bjz"/><stop offset="1" class="lmlq_xbrl"/></radialGradient><radialGradient id="iP7PWPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.15365 1.28841 0 24.907 11.905)" gradientUnits="userSpaceOnUse"><stop offset=".051" class="o8p2_blib"/><stop offset="1" class="szwxs1ffj"/></radialGradient><radialGradient id="isclF0d" cx="0" cy="0" r="1" gradientTransform="rotate(-119.268 10.572 6.105)scale(3.2599 6.67388)" gradientUnits="userSpaceOnUse"><stop class="vmjr7rbhn"/><stop offset="1" class="zxip0bczk"/></radialGradient><radialGradient id="iDRXN4c" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 0 0 1.78125 21.32 18.188)" gradientUnits="userSpaceOnUse"><stop class="iusprebiv"/><stop offset="1" class="n4ma-nbis"/></radialGradient><radialGradient id="iS9Ev6d" cx="0" cy="0" r="1" gradientTransform="matrix(-8.43067 -6.22495 7.88718 -10.6819 24.297 17.752)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="qxprq_b_n"/><stop offset="1" class="id0y_n31u"/></radialGradient><radialGradient id="ilM9P2b" cx="0" cy="0" r="1" gradientTransform="matrix(1.19531 0 0 .58033 20.985 13.22)" gradientUnits="userSpaceOnUse"><stop class="azeqcu15x"/><stop offset="1" class="sda7dac5x"/></radialGradient><radialGradient id="i04SaQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60937 0 0 -.8125 11.047 13.408)" gradientUnits="userSpaceOnUse"><stop class="x9q-1ua-h"/><stop offset="1" class="d_y83zkbz"/></radialGradient><radialGradient id="iTvoGjb" cx="0" cy="0" r="1" gradientTransform="rotate(-177.049 5.48 8.506)scale(3.03527 4.59892)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="ftdzlkbpm"/><stop offset="1" class="iu-l6acky"/></radialGradient><radialGradient id="i94wRLj" cx="0" cy="0" r="1" gradientTransform="rotate(-50.886 21.054 2.907)scale(3.51696 3.66873)" gradientUnits="userSpaceOnUse"><stop class="ap_fa_bgx"/><stop offset="1" class="wnm2vg-zq"/></radialGradient><radialGradient id="iq5grxc" cx="0" cy="0" r="1" gradientTransform="rotate(18.583 -40.458 35.618)scale(1.9122)" gradientUnits="userSpaceOnUse"><stop class="piog5dbbq"/><stop offset="1" class="scj14cc8n"/></radialGradient><radialGradient id="iwAayAd" cx="0" cy="0" r="1" gradientTransform="rotate(58.191 -2.461 25.115)scale(2.90507)" gradientUnits="userSpaceOnUse"><stop class="l6_drsttt"/><stop offset=".818" class="y8ko8lbwt"/></radialGradient><radialGradient id="i7iIApe" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .21093 -.3117 -.93518 21.468 14.756)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="scdbh9z2a"/><stop offset="1" class="a_-lrxb-j"/></radialGradient><radialGradient id="iSFZpOe" cx="0" cy="0" r="1" gradientTransform="rotate(175.38 9.081 8.247)scale(6.92401 7.3565)" gradientUnits="userSpaceOnUse"><stop offset=".099" class="q53kgabbx"/><stop offset="1" class="bnjlidcqw"/></radialGradient><radialGradient id="idvaCco" cx="0" cy="0" r="1" gradientTransform="rotate(-135.278 9.615 4.176)scale(1.80274 1.46677)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="lcdmwxb3o"/><stop offset="1" class="zulp-7bpr"/></radialGradient><radialGradient id="iDwP91d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.25 1.59519 0 18.308 14)" gradientUnits="userSpaceOnUse"><stop class="un5p1-92b"/><stop offset="1" class="dwi3bmkhd"/></radialGradient><radialGradient id="ihZrSNc" cx="0" cy="0" r="1" gradientTransform="rotate(-39.991 25.263 -17.106)scale(2.09745 1.53563)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="grnmvqnpc"/><stop offset="1" class="cx7g7ubph"/></radialGradient><radialGradient id="iTaoqmb" cx="0" cy="0" r="1" gradientTransform="rotate(108.857 5.716 14.547)scale(5.92181 6.00374)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="cgxt7tbhv"/><stop offset="1" class="anlei4e5k"/></radialGradient><radialGradient id="iw1jnOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.983 -5.15649 0 15.788 14.706)" gradientUnits="userSpaceOnUse"><stop offset=".849" class="z6iy9bq0d"/><stop offset=".937" class="ep8tcxbhd"/></radialGradient><radialGradient id="iVCvCWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.52691 -7.4935 3.6233 -.25478 20.872 30.27)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="t-11r3bnw"/><stop offset="1" class="czclolbcn"/></radialGradient><radialGradient id="ipeSu8w" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.893 14.47)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iB8NdPb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.397 2.952)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFF7vHd" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.535 16.216)scale(2.34093 2.29861)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="ga9rerbuy"/><stop offset="1" class="nzebcsqxz"/></radialGradient><radialGradient id="iR34W2c" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 27.806 23.525)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="xd1qixbwn"/><stop offset="1" class="xp3m0tmzy"/></radialGradient><radialGradient id="i9HBkgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.53 14.47)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iJHhAQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.243 14.69)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWGPb8d" cx="0" cy="0" r="1" gradientTransform="rotate(50.631 4.135 27.613)scale(4.77012 4.93363)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="vas9tjbit"/><stop offset="1" class="ny-1wemya"/></radialGradient><radialGradient id="iGWAD2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.08699 -2.67056 0 25.694 7.038)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="viuzncbxq"/><stop offset="1" class="ej1v0hbca"/></radialGradient><radialGradient id="igTqeBd" cx="0" cy="0" r="1" gradientTransform="rotate(145.359 13.475 8.328)scale(4.03204 2.70487)" gradientUnits="userSpaceOnUse"><stop class="uvv0p6btj"/><stop offset="1" class="elep40b9c"/></radialGradient><radialGradient id="i8p1Rze" cx="0" cy="0" r="1" gradientTransform="rotate(144.673 12.833 7.06)scale(4.10848 4.60794)" gradientUnits="userSpaceOnUse"><stop class="a-lhjfbpa"/><stop offset="1" class="begh2ub5w"/></radialGradient><radialGradient id="ighTuLd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18338 -3.37245 3.40485 -3.21396 26.736 7.19)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="po1nyh2al"/><stop offset=".913" class="cjnv6q4jy"/></radialGradient><radialGradient id="ikiAMVQ" cx="0" cy="0" r="1" gradientTransform="rotate(-111.272 15.624 -6.078)scale(2.21539 2.9282)" gradientUnits="userSpaceOnUse"><stop offset=".052" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="iusn0Be" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 5.11733 0 15.687 19.438)" gradientUnits="userSpaceOnUse"><stop offset=".514" class="qjhnpgb8v"/><stop offset="1" class="s8ee2e-gk"/></radialGradient><radialGradient id="ijEiKbA" cx="0" cy="0" r="1" gradientTransform="rotate(-30.121 43.438 -14.014)scale(3.48638 1.33201)" gradientUnits="userSpaceOnUse"><stop class="pplnvv__n"/><stop offset="1" class="xk-by4b4y"/></radialGradient><radialGradient id="iqZStCK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -1 1.44386 -2.12067 19.429 19.625)" gradientUnits="userSpaceOnUse"><stop class="jcpsiebxx"/><stop offset="1" class="k7rvojiiu"/></radialGradient><radialGradient id="inytbpY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .1959 -.60167 0 16.016 16.706)" gradientUnits="userSpaceOnUse"><stop class="thz14rm3n"/><stop offset="1" class="v_m0mg0xo"/></radialGradient><radialGradient id="iQuYeGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 25.996 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="igZuAnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 25.996 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ifTjdid" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 25.996 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="imOHbge" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 25.996 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><linearGradient id="imVONQe" x1="19.133" x2="19.461" y1="5.203" y2="3.844" gradientUnits="userSpaceOnUse"><stop class="guc8z7bij"/><stop offset="1" class="iov6rh-pq"/></linearGradient><linearGradient id="iVVWgNZ" x1="17.352" x2="17.352" y1="8.5" y2="7.313" gradientUnits="userSpaceOnUse"><stop class="u3wf8s8gl"/><stop offset="1" class="pt6842k6d"/></linearGradient><linearGradient id="itoQg6b" x1="14.165" x2="20.227" y1="9.906" y2="9.75" gradientUnits="userSpaceOnUse"><stop class="p-go_8bpa"/><stop offset="1" class="tp_ivrbui"/></linearGradient><linearGradient id="ihJBaCe" x1="21.852" x2="19.258" y1="9.281" y2="9.281" gradientUnits="userSpaceOnUse"><stop class="xrhcfrbuk"/><stop offset="1" class="psjmui2lw"/></linearGradient><linearGradient id="iaLPX5c" x1="9.727" x2="11.946" y1="9.515" y2="10.53" gradientUnits="userSpaceOnUse"><stop class="cvjhjoe1h"/><stop offset="1" class="wmajqfcti"/></linearGradient><linearGradient id="itYBDkS" x1="15.867" x2="15.867" y1="11.3" y2="16.752" gradientUnits="userSpaceOnUse"><stop class="flda2eefx"/><stop offset="1" class="leei8_8-z"/></linearGradient><linearGradient id="iMqLKNi" x1="9.991" x2="21.329" y1="25.138" y2="25.138" gradientUnits="userSpaceOnUse"><stop class="qrvn3qqfw"/><stop offset=".232" class="g5fe5iufq"/><stop offset=".416" class="kprmyi-ro"/><stop offset=".64" class="p_dqhfwyw"/><stop offset="1" class="r5d9x5b3n"/></linearGradient><linearGradient id="i92Wl0b" x1="17.206" x2="13.402" y1="19.345" y2="19.345" gradientUnits="userSpaceOnUse"><stop class="q_ql_xbdw"/><stop offset="1" class="gvw--y2hy"/></linearGradient><linearGradient id="ijrqUJx" x1="18.671" x2="18.358" y1="14.525" y2="14.718" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iovA8Pd" x1="14.273" x2="13.96" y1="14.525" y2="14.718" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGIpk4H" x1="24.349" x2="28.321" y1="10.144" y2="10.144" gradientUnits="userSpaceOnUse"><stop class="kytdhlviv"/><stop offset="1" class="bf9jtobby"/></linearGradient><linearGradient id="ikyJE0b" x1="26.594" x2="26.594" y1="10.041" y2="25.783" gradientUnits="userSpaceOnUse"><stop class="pafpa8b3r"/><stop offset="1" class="irkpemyfq"/></linearGradient><linearGradient id="ierK1Be" x1="17.991" x2="17.335" y1="17.313" y2="18.5" gradientUnits="userSpaceOnUse"><stop offset=".182" class="dnj3c6bdc"/><stop offset="1" class="aqvxwkutl"/></linearGradient><linearGradient id="ifRwArc" x1="16.477" x2="15.43" y1="16.3" y2="16.426" gradientUnits="userSpaceOnUse"><stop offset=".175" class="lbea_6bqh"/><stop offset="1" class="chqodfbvj"/></linearGradient><linearGradient id="ioJqUBc" x1="15.89" x2="15.89" y1="17.21" y2="16.331" gradientUnits="userSpaceOnUse"><stop offset=".147" class="uq1c5gbgz"/><stop offset="1" class="m-jwf-jyg"/></linearGradient><linearGradient id="iiIKKOb" x1="14.813" x2="15.805" y1="16.19" y2="16.268" gradientUnits="userSpaceOnUse"><stop class="jgljp9bab"/><stop offset="1" class="m-jwf-jyg"/></linearGradient><linearGradient id="ivsZ1re" x1="15.705" x2="15.705" y1="14.543" y2="17.21" gradientUnits="userSpaceOnUse"><stop offset=".026" class="uue9nwz4j"/><stop offset=".208" class="xqma8_b2l"/></linearGradient><linearGradient id="iuq2Xrd" x1="27.727" x2="23.346" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="a87gyab7w"/></linearGradient><linearGradient id="i0y7jKK" x1="23.866" x2="25.575" y1="26.056" y2="26.056" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ihqE12b" x1="23.788" x2="25.497" y1="27.361" y2="27.361" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ipRK7de" x1="23.866" x2="25.575" y1="28.665" y2="28.665" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><filter id="iTEe5yb" width="6.328" height="3.25" x="15.649" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.521569 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1079"/></filter><filter id="i1Kvood" width="23.09" height="7.66" x="4.322" y="10.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".125"/></filter><filter id="iLoFYPd" width="2.6" height="2.6" x="9.499" y="13.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".1"/></filter><filter id="i4cYwIe" width="2.6" height="2.6" x="19.199" y="13.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".1"/></filter><filter id="iqyIVhc" width="11.125" height="10.616" x="10.468" y="11.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.317647 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1079"/></filter><filter id="iA3UMyR" width="2.873" height="1.77" x="11.802" y="11.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.396078 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1079"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.443137 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1079" result="effect2_innerShadow_4002_1079"/></filter><filter id="iH4RX4d" width="2.857" height="1.77" x="17.116" y="11.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.396078 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1079"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.443137 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1079" result="effect2_innerShadow_4002_1079"/></filter><filter id="ifJDoBA" width="7.703" height="4.796" x="11.834" y="16.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".375"/></filter><filter id="ikacAJb" width=".787" height=".696" x="17.159" y="14.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".05"/></filter><filter id="iGLnWHc" width=".891" height=".913" x="17.999" y="14.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".1"/></filter><filter id="ici4HQe" width=".986" height="1.04" x="13.556" y="14.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".1"/></filter><filter id="iiyVM3c" width=".913" height=".705" x="12.802" y="14.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".05"/></filter><filter id="iDRbQne" width="5.505" height="22.045" x="23.066" y="4.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.45098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1079"/></filter><filter id="iuJZ6Vf" width="1.8" height="17.542" x="25.194" y="9.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".325"/></filter><filter id="i5JNXdc" width="7.999" height="3.446" x="11.687" y="16.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.647059 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1079"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.552941 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1079" result="effect2_innerShadow_4002_1079"/></filter><filter id="iH6kqLc" width="1.801" height=".85" x="14.806" y="16.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".05"/></filter><filter id="i51zgki" width="4.846" height="5.556" x="23.346" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.352941 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1079"/></filter><filter id="izpZVte" width="2.097" height=".3" x="23.716" y="25.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".05"/></filter><filter id="icmYWQc" width="2.097" height=".3" x="23.637" y="27.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".05"/></filter><filter id="i4RW9Dc" width="2.097" height=".3" x="23.716" y="28.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1079" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-mage-medium" /></template>
<style>
.a_-lrxb-j {
  stop-color: var(--svg-color--876b6a, #876B6A);
  stop-opacity: 0;
}

.a-lhjfbpa {
  stop-color: var(--svg-color--4ddcff, #4DDCFF);
}

.a87gyab7w {
  stop-color: var(--svg-color--a57c6f, #A57C6F);
}

.akjkhoqir {
  fill: var(--svg-color--a37467, #A37467);
  fill-rule: evenodd;
  d: path("M17.633 15.546a.3.3 0 0 0-.417.432l.208-.216l-.207.216l.001.001l.003.003l.007.007a1 1 0 0 0 .115.095c.077.059.187.135.327.21c.277.149.681.298 1.168.28a.3.3 0 0 0-.023-.6a1.7 1.7 0 0 1-.862-.209a2 2 0 0 1-.306-.207zm0 0l-.001-.001");
}

.anlei4e5k {
  stop-color: var(--svg-color--d0cfe4, #D0CFE4);
  stop-opacity: 0;
}

.ap_fa_bgx {
  stop-color: var(--svg-color--3171db, #3171DB);
}

.aqvxwkutl {
  stop-color: var(--svg-color--d7d4da, #D7D4DA);
  stop-opacity: 0;
}

.azeqcu15x {
  stop-color: var(--svg-color--215a98, #215A98);
}

.b5djzgbgl {
  d: path("m15.334 14.82l-.497 1.69c-.105.35.143.7.497.7h.746c.344 0 .593-.35.497-.7l-.497-1.69c-.124-.37-.631-.37-.746 0");
}

.b8c389gzb {
  stop-color: var(--svg-color--2e8ced, #2E8CED);
}

.bcd-hkbhh {
  d: path("M17.83 14.183c.064.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.136.389-.05");
}

.begh2ub5w {
  stop-color: var(--svg-color--2f85fe, #2F85FE);
}

.bf9jtobby {
  stop-color: var(--svg-color--e4a771, #E4A771);
}

.bj_c06brs {
  cx: 13.258px;
  cy: 14.375px;
  rx: 0.39px;
  ry: 0.197px;
}

.bkffn87la {
  stop-color: var(--svg-color--3da9f9, #3DA9F9);
  stop-opacity: 0;
}

.bnjlidcqw {
  stop-color: var(--svg-color--8b6760, #8B6760);
}

.c2cwddcfn {
  d: path("M14.343 14.782c0-.289-.235-.481-.298-.54l-.288.28l.177.36z");
}

.cb13voduh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M26.094 10.041v15.742");
}

.cdhdhx4uq {
  stop-color: var(--svg-color--4abfff, #4ABFFF);
}

.cgxt7tbhv {
  stop-color: var(--svg-color--d0cfe4, #D0CFE4);
}

.chqodfbvj {
  stop-color: var(--svg-color--a27c6e, #A27C6E);
  stop-opacity: 0;
}

.cjnv6q4jy {
  stop-color: var(--svg-color--4093be, #4093BE);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cvjhjoe1h {
  stop-color: var(--svg-color--57515f, #57515F);
}

.cx7g7ubph {
  stop-color: var(--svg-color--a87d77, #A87D77);
  stop-opacity: 0;
}

.czclolbcn {
  stop-color: var(--svg-color--e9dfec, #E9DFEC);
  stop-opacity: 0;
}

.d_y83zkbz {
  stop-color: var(--svg-color--14488d, #14488D);
  stop-opacity: 0;
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.dnj3c6bdc {
  stop-color: var(--svg-color--d7d4da, #D7D4DA);
}

.dwi3bmkhd {
  stop-color: var(--svg-color--a16f6b, #A16F6B);
  stop-opacity: 0;
}

.dy84ygb3l {
  d: path("M22.881 22.763C25.357 24.925 26.42 28 26.561 30h-3.68z");
}

.e-eqv1h-i {
  fill-rule: evenodd;
  d: path("M15.35 16.71a.75.75 0 0 1 .75 0l3.211 1.795a.75.75 0 1 1-.752 1.3l-2.74-1.525a.2.2 0 0 0-.193 0l-2.815 1.525a.75.75 0 1 1-.747-1.303z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ej1v0hbca {
  stop-color: var(--svg-color--ba795b, #BA795B);
  stop-opacity: 0;
}

.elep40b9c {
  stop-color: var(--svg-color--cc8c6f, #CC8C6F);
  stop-opacity: 0;
}

.ep8tcxbhd {
  stop-color: var(--svg-color--e3dee6, #E3DEE6);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.flda2eefx {
  stop-color: var(--svg-color--4478e6, #4478E6);
}

.ft5dv1b6b {
  fill: none;
}

.ftdzlkbpm {
  stop-color: var(--svg-color--1956ae, #1956AE);
}

.fwd3q-uyq {
  d: path("M13.527 13.994a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.892");
}

.g5fe5iufq {
  stop-color: var(--svg-color--c9c1d3, #C9C1D3);
}

.ga9rerbuy {
  stop-color: var(--svg-color--bc9479, #BC9479);
}

.gemps2knm {
  d: path("M20.83 13.532q0-.015 0 0l.01-.106c.04-1.044-.263-1.763-2.042-1.924c-1.78-.161-4.49-.215-6.324 0c-1.833.214-2.088.899-1.987 1.982l.302 4.456c.262 1.885 1.936 3.286 3.922 3.286h1.905c1.986 0 3.659-1.41 3.921-3.286z");
}

.gkfgd-bym {
  fill: var(--svg-color--000, #000);
  d: path("M17.384 14.886a.51.51 0 0 1 .511-.51a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.236");
}

.gkr7_8biz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.866 28.587h1.797");
}

.grnmvqnpc {
  stop-color: var(--svg-color--a87d77, #A87D77);
}

.guc8z7bij {
  stop-color: var(--svg-color--2caafc, #2CAAFC);
}

.gvw--y2hy {
  stop-color: var(--svg-color--b0a3bd, #B0A3BD);
}

.h7wfmk73a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.866 25.978h1.797");
}

.hb0k2h_0q {
  stop-color: var(--svg-color--458cd0, #458CD0);
}

.hidyelbxs {
  stop-color: var(--svg-color--4e85b1, #4E85B1);
}

.hoa8-tbfc {
  d: path("M23.346 25.326a.73.73 0 0 1 .726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.huu-ickwn {
  stop-color: var(--svg-color--2fb4f5, #2FB4F5);
}

.hw09ab0hr {
  d: path("M19.824 30c.443-.705 1.363-2.623 1.437-4.654c.094-2.554.141-8.822-.453-11.737c-.17 2.12-1.97 5.016-5.16 5.278c-3.189-.262-4.989-3.158-5.159-5.278c-.593 2.915-.546 9.183-.453 11.737c.075 2.031.995 3.949 1.438 4.654z");
}

.hyyp17b7p {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.102 13.722c.654 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.id0y_n31u {
  stop-color: var(--svg-color--2e65d4, #2E65D4);
}

.ionth7brd {
  stop-color: var(--svg-color--2a87f2, #2A87F2);
}

.iov6rh-pq {
  stop-color: var(--svg-color--2caafc, #2CAAFC);
  stop-opacity: 0;
}

.iq1u3k1wa {
  d: path("M20.499 16.75a1.65 1.65 0 1 0 0-3.3a1.65 1.65 0 0 0 0 3.3");
}

.irkpemyfq {
  stop-color: var(--svg-color--e3a984, #E3A984);
  stop-opacity: 0;
}

.iu-l6acky {
  stop-color: var(--svg-color--1956ae, #1956AE);
  stop-opacity: 0;
}

.iusprebiv {
  stop-color: var(--svg-color--1868c3, #1868C3);
}

.jcpsiebxx {
  stop-color: var(--svg-color--dddae3, #DDDAE3);
}

.jgljp9bab {
  stop-color: var(--svg-color--805b52, #805B52);
}

.k5i1obbcc {
  d: path("M27.075 23.044a.97.97 0 0 1 .967.967v2.214h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.k6ft4_b3l {
  d: path("M10.799 16.75a1.65 1.65 0 1 0 0-3.3a1.65 1.65 0 0 0 0 3.3");
}

.k7rvojiiu {
  stop-color: var(--svg-color--dddae3, #DDDAE3);
  stop-opacity: 0;
}

.keu943bph {
  d: path("M21.599 10.46h-11.9l.18-.35c1.12-2.16 3.34-8.11 5.77-8.11c2.44 0 4.67 5.96 5.78 8.13z");
}

.kj9xuub5a {
  d: path("M17.895 13.994a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.kprmyi-ro {
  stop-color: var(--svg-color--e8e0f3, #E8E0F3);
}

.kytdhlviv {
  stop-color: var(--svg-color--d98350, #D98350);
}

.l6_drsttt {
  stop-color: var(--svg-color--6a5058, #6A5058);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l8yphmoyw {
  stop-color: var(--svg-color--3084eb, #3084EB);
  stop-opacity: 0;
}

.lbea_6bqh {
  stop-color: var(--svg-color--bb9481, #BB9481);
}

.lcdmwxb3o {
  stop-color: var(--svg-color--8b5c63, #8B5C63);
}

.leei8_8-z {
  stop-color: var(--svg-color--4478e6, #4478E6);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li354g47q {
  stop-color: var(--svg-color--278ce6, #278CE6);
}

.lmlq_xbrl {
  stop-color: var(--svg-color--2fa3f0, #2FA3F0);
  stop-opacity: 0;
}

.lmtqybbtc {
  stop-color: var(--svg-color--278ce6, #278CE6);
  stop-opacity: 0;
}

.lrepv5bkn {
  fill: var(--svg-color--000, #000);
  d: path("M14.039 14.886a.51.51 0 0 0-.512-.51a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.236");
}

.m-jwf-jyg {
  stop-color: var(--svg-color--a17b6d, #A17B6D);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mvc25evki {
  d: path("M26.94 4.871a.31.31 0 0 0-.455.272v1.634a.803.803 0 0 1-.806.807a.79.79 0 0 1-.777-.786V5.143a.31.31 0 0 0-.454-.272a2.63 2.63 0 0 0-1.382 2.29c-.01 1.018.585 1.916 1.443 2.36c.1.05.161.151.161.262V25.83c0 .575.474 1.049 1.049 1.049s1.049-.475 1.049-1.05V9.764a.29.29 0 0 1 .161-.262a2.627 2.627 0 0 0 .01-4.63");
}

.n4ma-nbis {
  stop-color: var(--svg-color--1868c3, #1868C3);
  stop-opacity: 0;
}

.n8khjlbdo {
  d: path("M8.636 22.756C6.02 25.02 4.916 28.247 4.916 30h3.72z");
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.no9fnjgey {
  fill: var(--svg-color--79544d, #79544D);
  d: path("M20.499 16.2a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.nv3141b3h {
  fill: var(--svg-color--a07a6c, #A07A6C);
  d: path("m15.334 14.82l-.497 1.69c-.105.35.143.7.497.7h.746c.344 0 .593-.35.497-.7l-.497-1.69c-.124-.37-.631-.37-.746 0");
}

.nvrzpdhpt {
  stop-color: var(--svg-color--226bd5, #226BD5);
  stop-opacity: 0;
}

.ny-1wemya {
  stop-color: var(--svg-color--ba756c, #BA756C);
  stop-opacity: 0;
}

.nzebcsqxz {
  stop-color: var(--svg-color--aa7756, #AA7756);
}

.o8p2_blib {
  stop-color: var(--svg-color--2e74cb, #2E74CB);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p_dqhfwyw {
  stop-color: var(--svg-color--f4ecfc, #F4ECFC);
}

.p-go_8bpa {
  stop-color: var(--svg-color--423851, #423851);
}

.p09j7tbqs {
  stop-color: var(--svg-color--2088ea, #2088EA);
}

.p5_1r5b0y {
  stop-color: var(--svg-color--3da9f9, #3DA9F9);
}

.pafpa8b3r {
  stop-color: var(--svg-color--e3a984, #E3A984);
}

.pg2upnb0g {
  d: path("M22.862 18.06H8.872c-2.27 0-4.1-1.51-4.1-3.38s1.84-3.38 4.1-3.38l13.99.01c2.27 0 4.1 1.51 4.1 3.38c0 1.86-1.84 3.37-4.1 3.37");
}

.phlvo2b_b {
  stop-color: var(--svg-color--4991bb, #4991BB);
}

.piog5dbbq {
  stop-color: var(--svg-color--624757, #624757);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po1nyh2al {
  stop-color: var(--svg-color--39a1ff, #39A1FF);
  stop-opacity: 0;
}

.pplnvv__n {
  stop-color: var(--svg-color--dbd5e2, #DBD5E2);
}

.pql562bff {
  stop-color: var(--svg-color--2bbbff, #2BBBFF);
}

.psfq9ybev {
  stroke: var(--svg-color--a1a3ad, #A1A3AD);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M12.278 12.805S13 12.232 14 12.352");
}

.psjmui2lw {
  stop-color: var(--svg-color--665d70, #665D70);
  stop-opacity: 0;
}

.pt6842k6d {
  stop-color: var(--svg-color--50b2e2, #50B2E2);
  stop-opacity: 0;
}

.q_ql_xbdw {
  stop-color: var(--svg-color--a899b6, #A899B6);
}

.q53kgabbx {
  stop-color: var(--svg-color--b78a77, #B78A77);
}

.q9eu_1urh {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M16.947 18.68c-1.118.418-2.122.174-2.484 0l1.234-1.008z");
}

.qbutz3c9r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.788 27.283h1.796");
}

.qjhnpgb8v {
  stop-color: var(--svg-color--d4d0db, #D4D0DB);
}

.qrvn3qqfw {
  stop-color: var(--svg-color--bfb9ca, #BFB9CA);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxprq_b_n {
  stop-color: var(--svg-color--257bd2, #257BD2);
}

.r-f_l1b-y {
  stop-color: var(--svg-color--3084eb, #3084EB);
}

.r-yilwbra {
  stop-color: var(--svg-color--35acfa, #35ACFA);
}

.r5d9x5b3n {
  stop-color: var(--svg-color--e0d5e0, #E0D5E0);
}

.rhfs4jg4m {
  stop-color: var(--svg-color--49bcff, #49BCFF);
}

.ry34eabsg {
  stroke: var(--svg-color--a1a3ad, #A1A3AD);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M19.298 12.805s-.707-.573-1.707-.453");
}

.s_1mw_rhq {
  stop-color: var(--svg-color--4cdbff, #4CDBFF);
}

.s8ee2e-gk {
  stop-color: var(--svg-color--c7c2cd, #C7C2CD);
}

.s8lgxzbhp {
  d: path("m23.329 18.48l-15.2-.01c-2.45 0-4.45-2-4.45-4.46s2-4.46 4.46-4.46l15.2.01c2.46 0 4.46 2 4.46 4.46a4.48 4.48 0 0 1-4.47 4.46");
}

.scdbh9z2a {
  stop-color: var(--svg-color--876b6a, #876B6A);
}

.scj14cc8n {
  stop-color: var(--svg-color--714c57, #714C57);
}

.sda7dac5x {
  stop-color: var(--svg-color--215a98, #215A98);
  stop-opacity: 0;
}

.sn5zqwaoh {
  d: path("M25.63 5.538a.883.883 0 1 1 1.588-.766l.124.3a.864.864 0 0 1-1.554.75z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sxxddhjsf {
  d: path("M15.649 2c2.84 0 4.71.95 5.81 1.77c.52.39.23 1.22-.42 1.22l-5.31.01z");
}

.szk9545gm {
  d: path("m9.469 10.15l-.19.38h12.74l-.18-.36a7.1 7.1 0 0 0-1.19-1.67h-10c-.46.49-.86 1.04-1.18 1.65");
}

.szwxs1ffj {
  stop-color: var(--svg-color--2e74cb, #2E74CB);
  stop-opacity: 0;
}

.t-11r3bnw {
  stop-color: var(--svg-color--ccc0d0, #CCC0D0);
}

.t4ibp7bdp {
  stop-color: var(--svg-color--359cf2, #359CF2);
  stop-opacity: 0;
}

.thz14rm3n {
  stop-color: var(--svg-color--b88f82, #B88F82);
}

.tp_ivrbui {
  stop-color: var(--svg-color--584d65, #584D65);
}

.tsk-k9bvn {
  stop-color: var(--svg-color--2fa9e7, #2FA9E7);
  stop-opacity: 0;
}

.u3wf8s8gl {
  stop-color: var(--svg-color--50b2e2, #50B2E2);
}

.u9gp0acpk {
  d: path("M25.699 8.78a2.622 2.622 0 1 0 0-5.245a2.622 2.622 0 0 0 0 5.245");
}

.uaw_s5rgf {
  cx: 13.258px;
  cy: 14.375px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uhjhn9b3f {
  fill: var(--svg-color--8a605a, #8A605A);
  fill-rule: evenodd;
  d: path("M13.845 15.546a.3.3 0 0 1 .416.432l-.208-.216l.208.216l-.001.001l-.003.003l-.008.007a1 1 0 0 1-.115.095a2.4 2.4 0 0 1-.326.21a2.3 2.3 0 0 1-1.168.28a.3.3 0 0 1 .022-.6c.351.013.649-.094.862-.209a2 2 0 0 0 .307-.207zm0 0");
}

.uhl03ccti {
  stop-color: var(--svg-color--4bdaff, #4BDAFF);
}

.ul10cac5y {
  stop-color: var(--svg-color--42b8fe, #42B8FE);
}

.ul8yzzy5p {
  d: path("M4.916 30c0-2.883 2.987-9.76 10.778-9.76c7.79 0 10.627 6.396 10.868 9.76z");
}

.un5p1-92b {
  stop-color: var(--svg-color--a16f6b, #A16F6B);
}

.uq1c5gbgz {
  stop-color: var(--svg-color--96676d, #96676D);
}

.ut5qt-u_y {
  fill: var(--svg-color--613f46, #613F46);
  d: path("M10.799 16.2a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.uue9nwz4j {
  stop-color: var(--svg-color--a57c6e, #A57C6E);
}

.uuh3gfbsu {
  stop-color: var(--svg-color--2cb1f7, #2CB1F7);
}

.uvv0p6btj {
  stop-color: var(--svg-color--cc8c6f, #CC8C6F);
}

.uw344gogm {
  fill-rule: evenodd;
  d: path("M15.425 17.094a.47.47 0 0 1 .581.001l2.49 1.795c.279.207.374.666.213 1.025c-.161.36-.517.482-.796.274l-2.084-1.495a.2.2 0 0 0-.232-.002l-2.14 1.497c-.28.206-.636.082-.796-.277s-.063-.819.216-1.025z");
}

.uxgwypbgl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.83 14.183c.064.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.136.389-.05");
}

.v_m0mg0xo {
  stop-color: var(--svg-color--b88f82, #B88F82);
  stop-opacity: 0;
}

.vas9tjbit {
  stop-color: var(--svg-color--ba756c, #BA756C);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.viuzncbxq {
  stop-color: var(--svg-color--ba795b, #BA795B);
}

.vji5arydn {
  stop-color: var(--svg-color--49bcff, #49BCFF);
  stop-opacity: 0;
}

.vmjr7rbhn {
  stop-color: var(--svg-color--104e9b, #104E9B);
}

.vx2arccxn {
  d: path("M18.69 14.769a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.vxkgnhd4n {
  stop-color: var(--svg-color--3171da, #3171DA);
}

.w08nqeb6o {
  stop-color: var(--svg-color--2088ea, #2088EA);
  stop-opacity: 0;
}

.winht877z {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m8.872 11.2l13.99.01m-13.99-.01v.1c-2.26 0-4.1 1.51-4.1 3.38s1.83 3.38 4.1 3.38h13.99c2.26 0 4.1-1.51 4.1-3.37c0-1.87-1.83-3.38-4.1-3.38v-.1m-13.99-.01c-2.297 0-4.2 1.537-4.2 3.48c0 1.942 1.893 3.48 4.2 3.48h13.99c2.296 0 4.2-1.538 4.2-3.47c0-1.943-1.894-3.48-4.2-3.48m-13.99-.01l13.99.01");
}

.wmajqfcti {
  stop-color: var(--svg-color--423952, #423952);
  stop-opacity: 0;
}

.wnm2vg-zq {
  stop-color: var(--svg-color--3171db, #3171DB);
  stop-opacity: 0;
}

.x9q-1ua-h {
  stop-color: var(--svg-color--14488d, #14488D);
}

.xa-9it8ui {
  stop-color: var(--svg-color--226bd5, #226BD5);
}

.xc-1yb-kl {
  stop-color: var(--svg-color--3596f4, #3596F4);
}

.xd1qixbwn {
  stop-color: var(--svg-color--cfa78e, #CFA78E);
}

.xk-by4b4y {
  stop-color: var(--svg-color--dbd5e2, #DBD5E2);
  stop-opacity: 0;
}

.xp3m0tmzy {
  stop-color: var(--svg-color--cfa78e, #CFA78E);
  stop-opacity: 0;
}

.xqma8_b2l {
  stop-color: var(--svg-color--a57c6e, #A57C6E);
  stop-opacity: 0;
}

.xrhcfrbuk {
  stop-color: var(--svg-color--665d70, #665D70);
}

.xus5pkr-r {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.32 13.722c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.231a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.y8ko8lbwt {
  stop-color: var(--svg-color--926f6a, #926F6A);
}

.z6iy9bq0d {
  stop-color: var(--svg-color--eeeaf3, #EEEAF3);
}

.z6vkgyynh {
  stop-color: var(--svg-color--5b8fc2, #5B8FC2);
  stop-opacity: 0;
}

.zdk8j6bjz {
  stop-color: var(--svg-color--2d6ba6, #2D6BA6);
}

.zquyghcdt {
  stop-color: var(--svg-color--3c79ae, #3C79AE);
  stop-opacity: 0;
}

.zrfo1hnzb {
  stop-color: var(--svg-color--2b84e7, #2B84E7);
}

.zulp-7bpr {
  stop-color: var(--svg-color--8b5c63, #8B5C63);
  stop-opacity: 0;
}

.zvz_j9byp {
  fill: var(--svg-color--77615d, #77615D);
  fill-rule: evenodd;
  d: path("m16.507 16.93l-.43-.24a.71.71 0 0 0-.706-.001l-.465.254a.49.49 0 0 0 .45.302h.702a.49.49 0 0 0 .449-.315");
}

.zxip0bczk {
  stop-color: var(--svg-color--104e9b, #104E9B);
  stop-opacity: 0;
}

</style>
