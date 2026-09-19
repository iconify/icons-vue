<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iqjVhfb" class="xzdbzvp2x"/></defs><g class="ft5dv1b6b"><path fill="url(#iEGGwpd)" class="kkb_itbhc"/><path fill="url(#iO2O1lb)" class="kkb_itbhc"/><path fill="url(#iNwD0hb)" class="dixgp5b2c"/><path fill="url(#iTMT5Fe)" class="dixgp5b2c"/><path fill="url(#iOdxqAd)" class="dixgp5b2c"/><path fill="url(#iHPSSTc)" class="zv2tyvbtc"/><path fill="url(#iqIvJAb)" class="zv2tyvbtc"/><path fill="url(#i59HMpb)" class="ui5t8ob3c"/><path fill="url(#iwKqotb)" class="ui5t8ob3c"/><path fill="url(#iPeOANc)" class="ui5t8ob3c"/><path fill="url(#iDPM1Fd)" class="c17i9lxwo"/><path fill="url(#idGrQzb)" class="c17i9lxwo"/><path class="motck9eja"/><path fill="url(#i1KV55d)" class="atn5mf2cn"/><path fill="url(#is4Tk2d)" class="cvb_k8b2c"/><path fill="url(#i72FXBc)" class="cvb_k8b2c"/><path fill="url(#iOhUSec)" class="s1kv5tupz"/><path fill="url(#iJRY4fb)" class="s1kv5tupz"/><path fill="url(#iO7EKec)" class="p9p0yqoca"/><path fill="url(#iGoycPc)" class="p9p0yqoca"/><path fill="url(#iuCT98v)" class="w4mmokmfn"/><path fill="url(#iE3aupd)" class="w4mmokmfn"/><path fill="url(#ihGCdLc)" class="w4mmokmfn"/><g filter="url(#iVCcwYk)"><ellipse class="as8s4rb-o"/></g><g filter="url(#iCUwyee)"><circle fill="url(#iE9c13n)" class="fhr5unbce"/></g><g filter="url(#iuaLQ5y)"><circle fill="url(#ilMsSZB)" class="dordgpbqi"/></g><g filter="url(#iTvg3Jb)"><circle fill="url(#iyuuUAc)" class="hhuw-tbsg"/><circle fill="url(#iJ3nC5b)" class="hhuw-tbsg"/></g><g filter="url(#iyP341E)"><circle class="r0z-pxb6h"/><circle fill="url(#iGEXoKe)" class="d2-11ueaa"/></g><path fill="url(#iFhMFOb)" class="s0rf8sb0g"/><path fill="url(#idG6KPc)" class="s0rf8sb0g"/><path fill="url(#ipESDAe)" class="s0rf8sb0g"/><path fill="url(#iMJbooc)" class="s0rf8sb0g"/><path fill="url(#iaDWMNd)" class="s0rf8sb0g"/><path fill="url(#iL67wEd)" class="s0rf8sb0g"/><path fill="url(#iHDKzAd)" class="s0rf8sb0g"/><path fill="url(#iJumAKd)" class="s0rf8sb0g"/><g filter="url(#iKYrKOb)"><path class="abmxgxbkf"/></g><g filter="url(#iCQ1ide)"><path class="sq4_kzbfq"/><path fill="url(#iRe3sxc)" class="f0kdrlbaf"/><path fill="url(#iV51k0b)" class="f0kdrlbaf"/><path fill="url(#ibWs9Yb)" class="f0kdrlbaf"/><path fill="url(#iDhC7uc)" class="f0kdrlbaf"/></g><g filter="url(#ixWnXUd)"><path fill="url(#irO6vVc)" class="clkxb77sn"/></g><g filter="url(#iJ1oB8c)"><use href="#iqjVhfb"/><path stroke="url(#iYjQb5d)" class="zk6gaob1c"/></g><use href="#iqjVhfb"/><path class="gnrqf4m8q"/><path fill="url(#iUS6ggT)" class="bs97mqxgs"/><path class="su8uv8bru"/><g filter="url(#iYN1F1z)"><path class="pxgxjc71a"/><path fill="url(#i3Etv6d)" class="h2w-d-bol"/></g><g filter="url(#iLFc8ld)"><path fill="url(#i3OZued)" class="f8ilswb3i"/></g><path class="njjnczw1i"/><path fill="url(#iU6I9Ld)" class="lyty50l8w"/><path class="t58kq9r-h"/><g filter="url(#ildcJud)"><path fill="url(#iZBwr6c)" class="q8o5fdbzr"/></g><g filter="url(#ixS1tye)"><ellipse transform="rotate(-27.914 13.35 13.035)" class="z1zvcfbsl"/><ellipse fill="url(#iUkFibd)" transform="rotate(-27.914 13.35 13.035)" class="xgcgu4bql"/></g><path fill="url(#iwvsKLc)" class="k7mbfsf3j"/><path fill="url(#iT8EgXc)" class="b4kb8vsrp"/><path fill="url(#icYCTvd)" class="v737-kb8e"/><path fill="url(#i1gk2NX)" class="v737-kb8e"/><path fill="url(#i33Kzde)" class="v737-kb8e"/><path fill="url(#iOYFGrc)" class="v737-kb8e"/><path fill="url(#ii0WgBc)" class="v737-kb8e"/><path fill="url(#iY6OXhc)" class="v737-kb8e"/><path fill="url(#iw8tett)" class="v737-kb8e"/><path fill="url(#iwqMSGd)" class="v737-kb8e"/><g filter="url(#iXANhkc)"><path fill="url(#i73cVJb)" class="qj9ym25-d"/><path fill="url(#iIVGT8b)" class="qj9ym25-d"/><path fill="url(#iHRIIYb)" class="qj9ym25-d"/><path fill="url(#ixGweCe)" class="qj9ym25-d"/></g><path fill="url(#ib2lrXd)" class="g2i6l-0tu"/><path fill="url(#iHJ6XLr)" class="g2i6l-0tu"/><path fill="url(#iuJLUJe)" class="g2i6l-0tu"/><path fill="url(#im5cwBe)" class="g2i6l-0tu"/><g filter="url(#ix5dYHT)"><ellipse class="jq7ez9q1u"/></g><defs><radialGradient id="iEGGwpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.25 -8.82215 0 16.011 16.61)" gradientUnits="userSpaceOnUse"><stop class="l9-nibb6i"/><stop offset="1" class="yfct4t52m"/></radialGradient><radialGradient id="iO2O1lb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9049 0 0 -8.83091 18.677 26.142)" gradientUnits="userSpaceOnUse"><stop class="b601vwbxd"/><stop offset="1" class="g__icmf-v"/></radialGradient><radialGradient id="iNwD0hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.721 24.534)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="iTMT5Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.721 26.201)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="iOdxqAd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.007)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="iHPSSTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.042 20.236)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="iqIvJAb" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.279 27.354)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="iwKqotb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.854)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="iPeOANc" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.341 29.9)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="iDPM1Fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.659 22.513)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="idGrQzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.659 27.907)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="i1KV55d" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.462 10.106)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="i72FXBc" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.33)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="iOhUSec" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.86)" gradientUnits="userSpaceOnUse"><stop class="fanogvbyi"/><stop offset="1" class="a0y7_lb_e"/></radialGradient><radialGradient id="iJRY4fb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28125 0 0 -15.3733 9.022 29.673)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="mhpw6_ebm"/><stop offset="1" class="nh1zhnb8g"/></radialGradient><radialGradient id="iO7EKec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -8.13268 2.48004 -.42883 25.677 29.9)" gradientUnits="userSpaceOnUse"><stop class="jlteq3ywp"/><stop offset="1" class="ud4d3yb8t"/></radialGradient><radialGradient id="iGoycPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .62514 0 23.659 29.9)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="kqqjbhbza"/><stop offset="1" class="g8lpdoqap"/></radialGradient><radialGradient id="iuCT98v" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.968 0 16.021 20.657)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="uek015btq"/><stop offset=".88" class="d894rgb9r"/></radialGradient><radialGradient id="iE3aupd" cx="0" cy="0" r="1" gradientTransform="rotate(125.503 3.83 15.16)scale(3.01336 1.49475)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="uv7-zdjnc"/><stop offset="1" class="wdl5xvb6m"/></radialGradient><radialGradient id="ihGCdLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.89063 -2.32678 0 16.021 20.126)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="ipt6eibjd"/><stop offset="1" class="o_k4jmbty"/></radialGradient><radialGradient id="iE9c13n" cx="0" cy="0" r="1" gradientTransform="matrix(1.90138 0 0 3.32744 9.058 13.877)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iyuuUAc" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 43.318 -39.648)scale(3.07356 3.75267)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iJ3nC5b" cx="0" cy="0" r="1" gradientTransform="matrix(1.4791 .82906 -.23439 .41817 21.448 11.988)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iGEXoKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.51542 -.11273 .08812 1.18464 20.738 13.99)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iFhMFOb" cx="0" cy="0" r="1" gradientTransform="rotate(-178.453 10.026 7.737)scale(7.73146 8.86531)" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="ipESDAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.29403 -17.4254 0 15.685 13.662)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="g58tvbcgs"/></radialGradient><radialGradient id="iMJbooc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41621 1.74303 0 18.553 12.5)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iaDWMNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.507 1.87408 0 13.615 12.464)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iHDKzAd" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 11.543 9.046)scale(3.16695 1.86079)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iJumAKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.15857 -8.11005 0 16.043 12.141)" gradientUnits="userSpaceOnUse"><stop class="ny5z_tl8m"/><stop offset="1" class="fr8ts7bxr"/></radialGradient><radialGradient id="iDhC7uc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21334 -.68541 0 16.366 15.618)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iUS6ggT" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87886 -1.39792 0 18.372 13.139)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i3Etv6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.25103 -.3235 .44537 -.3456 18.124 13.23)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iU6I9Ld" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8789 -1.39799 0 13.645 13.139)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iUkFibd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00837 -.5348 .64286 -.01007 13.334 13.375)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwvsKLc" cx="0" cy="0" r="1" gradientTransform="matrix(.16294 1.43904 -.60098 .06805 10.379 12.14)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="l455clhzf"/><stop offset="1" class="o_6cpw3af"/></radialGradient><radialGradient id="iT8EgXc" cx="0" cy="0" r="1" gradientTransform="matrix(.68394 .16058 -.54394 2.31675 21.48 12.575)" gradientUnits="userSpaceOnUse"><stop class="b0rle0boe"/><stop offset=".933" class="ofjcs8bae"/></radialGradient><radialGradient id="icYCTvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5625 -2.88065 0 19.794 6.827)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="i1gk2NX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 12.044 9.89)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="i33Kzde" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.45 10.327)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iOYFGrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.388 6.499)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="ii0WgBc" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.513 2.733)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iY6OXhc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.95 9.733)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="iwqMSGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 11.17 10.124)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iHRIIYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.67 9.89)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="ixGweCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.544 9.952)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="im5cwBe" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.909 8.966)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="i59HMpb" x1="9.158" x2="9.158" y1="21.169" y2="29.899" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="is4Tk2d" x1="21.034" x2="21.034" y1="19.705" y2="29.899" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="ilMsSZB" x1="10.867" x2="10.173" y1="14.18" y2="14.18" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="idG6KPc" x1="10.165" x2="12.619" y1="17.221" y2="17.067" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iL67wEd" x1="16.043" x2="16.043" y1="-3.333" y2="21.034" gradientUnits="userSpaceOnUse"><stop offset=".979" class="wvw1ebchz"/><stop offset="1" class="y2xm7ibwq"/></linearGradient><linearGradient id="iRe3sxc" x1="15.075" x2="16.092" y1="15.014" y2="15.014" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iV51k0b" x1="17.028" x2="15.917" y1="15.363" y2="15.347" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="ibWs9Yb" x1="16.222" x2="16.222" y1="16.168" y2="15.547" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="irO6vVc" x1="16.012" x2="16.012" y1="13.147" y2="14.65" gradientUnits="userSpaceOnUse"><stop class="l9a-b4blu"/><stop offset="1" class="wjwfebcns"/></linearGradient><linearGradient id="iYjQb5d" x1="14.888" x2="15.359" y1="17.917" y2="17.172" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="i3OZued" x1="19.215" x2="18.875" y1="13.197" y2="13.406" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZBwr6c" x1="14.45" x2="14.111" y1="13.197" y2="13.406" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iw8tett" x1="9.982" x2="10.794" y1="9.264" y2="9.264" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="i73cVJb" x1="16.021" x2="16.021" y1="2.1" y2="10.528" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="iIVGT8b" x1="16.021" x2="16.021" y1="2.1" y2="4.702" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="ib2lrXd" x1="21.997" x2="5.369" y1="11.273" y2="11.273" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="iHJ6XLr" x1="15.798" x2="15.798" y1="9.872" y2="10.186" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iuJLUJe" x1="16.716" x2="16.716" y1="12.179" y2="10.926" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="iVCcwYk" width="8.369" height="2.215" x="15.115" y="9.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".375"/></filter><filter id="iCUwyee" width="3.818" height="3.618" x="9.058" y="12.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2950"/></filter><filter id="iuaLQ5y" width="3.156" height="3.156" x="9.289" y="12.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".25"/></filter><filter id="iTvg3Jb" width="3.618" height="3.868" x="19.366" y="11.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2950"/></filter><filter id="iyP341E" width="3.156" height="3.156" x="19.597" y="12.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".25"/></filter><filter id="iKYrKOb" width="3.407" height="4.405" x="14.049" y="12.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".375"/></filter><filter id="iCQ1ide" width="2.534" height="3.405" x="14.745" y="13.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".125"/></filter><filter id="ixWnXUd" width="2.534" height="3.405" x="14.745" y="12.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".125"/></filter><filter id="iJ1oB8c" width="3.886" height="1.562" x="14.069" y="16.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".05"/></filter><filter id="iYN1F1z" width=".835" height=".737" x="17.585" y="12.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".05"/></filter><filter id="iLFc8ld" width=".932" height=".956" x="18.504" y="12.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".1"/></filter><filter id="ildcJud" width="1.035" height="1.093" x="13.691" y="12.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".1"/></filter><filter id="ixS1tye" width=".972" height=".746" x="12.865" y="12.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".05"/></filter><filter id="iXANhkc" width="5.791" height="8.428" x="13.126" y="2.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2950"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2950" result="effect2_innerShadow_4002_2950"/></filter><filter id="ix5dYHT" width="7.654" height="2.528" x="15.713" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2950" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-construction-worker-dark" /></template>
<style>
.a0y7_lb_e {
  stop-color: var(--svg-color--469bc8, #469BC8);
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.abmxgxbkf {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.713 13.745l-.888 1.842c-.11.379.154.757.528.757h.8c.374 0 .638-.384.528-.757l-.54-1.842c-.116-.408-.306-.408-.428 0");
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.as8s4rb-o {
  cx: 19.299px;
  cy: 10.826px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 3.435px;
  ry: 0.358px;
}

.atn5mf2cn {
  d: path("M9.975 20.74v9.16h1.983V19.705c-.698.28-1.355.62-1.983 1.034");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.b0rle0boe {
  stop-color: var(--svg-color--190a1c, #190A1C);
}

.b4kb8vsrp {
  d: path("m21.48 13.357l.043-1.309l.844-.117c-.026.085-.117.368-.27.824s-.475.591-.617.602");
}

.b601vwbxd {
  stop-color: var(--svg-color--3fb7ff, #3FB7FF);
}

.bs97mqxgs {
  d: path("M18.375 12.622a.967.967 0 0 1 .931 1.221H17.44a.97.97 0 0 1 .936-1.222");
}

.c17i9lxwo {
  d: path("M23.659 22.031V29.9h-1.634v-9.16c.578.383 1.126.817 1.634 1.292");
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clkxb77sn {
  d: path("m15.597 13.453l-.575 1.842a.584.584 0 0 0 .564.757h.851c.4 0 .682-.384.564-.757l-.575-1.842c-.124-.408-.7-.408-.829 0");
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cvb_k8b2c {
  d: path("M22.025 20.74v9.16h-1.983V19.705c.698.28 1.355.62 1.983 1.034");
}

.d2-11ueaa {
  cx: 21.175px;
  cy: 13.878px;
  r: 1.078px;
}

.d894rgb9r {
  stop-color: var(--svg-color--3b2029, #3B2029);
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.dixgp5b2c {
  d: path("M13.721 19.168c-.608.134-1.196.31-1.763.537V29.9h1.763z");
}

.dordgpbqi {
  cx: 10.867px;
  cy: 13.878px;
  r: 1.078px;
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ex-0zhc5k {
  stop-color: var(--svg-color--e1926f, #E1926F);
}

.ez-c7ubrp {
  stop-color: var(--svg-color--da4708, #DA4708);
}

.f0kdrlbaf {
  d: path("m15.597 13.568l-.575 1.842a.584.584 0 0 0 .564.758h.851c.4 0 .682-.385.564-.758l-.575-1.842c-.124-.407-.7-.407-.829 0");
}

.f2js-baog {
  stop-color: var(--svg-color--cd963a, #CD963A);
}

.f8ilswb3i {
  d: path("M19.235 13.461a.9.9 0 0 0-.25-.5l-.281.308l.127.247z");
}

.fanogvbyi {
  stop-color: var(--svg-color--3baeff, #3BAEFF);
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fhr5unbce {
  cx: 10.867px;
  cy: 13.877px;
  r: 1.809px;
}

.fr8ts7bxr {
  stop-color: var(--svg-color--371d20, #371D20);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g__icmf-v {
  stop-color: var(--svg-color--3fb7ff, #3FB7FF);
  stop-opacity: 0;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g2i6l-0tu {
  d: path("M22.477 9.872H9.883a1.153 1.153 0 1 0 0 2.307h12.594c.642 0 1.153-.521 1.153-1.154a1.147 1.147 0 0 0-1.153-1.153");
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.g58tvbcgs {
  stop-color: var(--svg-color--3b1937, #3B1937);
}

.g8lpdoqap {
  stop-color: var(--svg-color--199dea, #199DEA);
  stop-opacity: 0;
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.gnrqf4m8q {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.599 12.327c.707 0 1.305.488 1.467 1.147a.297.297 0 0 1-.29.37H17.36a.25.25 0 0 1-.247-.295a1.514 1.514 0 0 1 1.486-1.222");
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.h2w-d-bol {
  d: path("M18.303 12.827c.069.092-.075.204-.239.326s-.285.208-.353.117c-.07-.093.008-.266.171-.389c.164-.122.352-.146.42-.054");
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hb0fg9dnu {
  stop-color: var(--svg-color--c3a852, #C3A852);
}

.hhuw-tbsg {
  cx: 21.175px;
  cy: 13.877px;
  r: 1.809px;
}

.htellnhxv {
  stop-color: var(--svg-color--ffcf4c, #FFCF4C);
}

.ipt6eibjd {
  stop-color: var(--svg-color--28243f, #28243F);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.jlteq3ywp {
  stop-color: var(--svg-color--58d2ff, #58D2FF);
}

.jq7ez9q1u {
  cx: 19.54px;
  cy: 10.886px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 2.827px;
  ry: 0.264px;
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.k7mbfsf3j {
  d: path("m10.558 13.38l-.078-1.332l-.844-.117c.026.085.117.368.27.824s.51.615.652.626");
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kkb_itbhc {
  d: path("M16.021 19.29c-.78 0-1.55.08-2.3.23V29.9h4.58V19.52c-.74-.15-1.5-.23-2.28-.23");
}

.kqqjbhbza {
  stop-color: var(--svg-color--199dea, #199DEA);
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l455clhzf {
  stop-color: var(--svg-color--130718, #130718);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9-nibb6i {
  stop-color: var(--svg-color--3086e2, #3086E2);
}

.l9a-b4blu {
  stop-color: var(--svg-color--3d2426, #3D2426);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
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

.lyty50l8w {
  d: path("M13.643 12.622a.967.967 0 0 0-.932 1.222h1.868a1 1 0 0 0 .035-.255a.973.973 0 0 0-.971-.967");
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

.mhpw6_ebm {
  stop-color: var(--svg-color--4188d0, #4188D0);
}

.motck9eja {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.74v9.16h1.983V19.705c-.698.28-1.355.62-1.983 1.034");
}

.ms43e0vsz {
  stop-color: var(--svg-color--cdac54, #CDAC54);
}

.ms9ao5bgb {
  stop-color: var(--svg-color--d7a439, #D7A439);
}

.mzrwpxbna {
  stop-color: var(--svg-color--dc5314, #DC5314);
  stop-opacity: 0;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.nh1zhnb8g {
  stop-color: var(--svg-color--4188d0, #4188D0);
  stop-opacity: 0;
}

.njjnczw1i {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.419 12.327c-.708 0-1.305.488-1.468 1.147a.297.297 0 0 0 .29.37h2.417a.25.25 0 0 0 .246-.295a1.52 1.52 0 0 0-1.485-1.222");
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.npjjoacns {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
  stop-opacity: 0;
}

.nrsb-h28d {
  stop-color: var(--svg-color--c4a966, #C4A966);
}

.ny5z_tl8m {
  stop-color: var(--svg-color--371d20, #371D20);
}

.o_6cpw3af {
  stop-color: var(--svg-color--474241, #474241);
}

.o_k4jmbty {
  stop-color: var(--svg-color--28243f, #28243F);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o043sbvrw {
  stop-color: var(--svg-color--fd4, #FD4);
}

.o2jd-jggt {
  stop-color: var(--svg-color--ffce64, #FFCE64);
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

.ofjcs8bae {
  stop-color: var(--svg-color--4d4b4c, #4D4B4C);
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

.p9p0yqoca {
  d: path("M27.399 29.9c-.14-.947-.34-1.882-.62-2.787a11.56 11.56 0 0 0-3.12-5.018v7.804z");
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.pxgxjc71a {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.303 12.827c.069.092-.075.204-.239.326s-.285.208-.353.117c-.07-.093.008-.266.171-.389c.164-.122.352-.146.42-.054");
}

.q8o5fdbzr {
  d: path("M14.526 13.475c0-.313-.254-.52-.323-.584l-.312.302l.192.391z");
}

.qf92jxbjd {
  stop-color: var(--svg-color--fe713a, #FE713A);
  stop-opacity: 0;
}

.qj9ym25-d {
  d: path("M14.826 2.1h2.39c.829 0 1.5.603 1.5 1.633v6.795h-5.39V3.733c0-1.03.671-1.633 1.5-1.633");
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

.r0z-pxb6h {
  cx: 21.175px;
  cy: 13.878px;
  r: 1.078px;
  fill: var(--svg-color--4c3637, #4C3637);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.s0rf8sb0g {
  d: path("M10.423 11.655c0-.289.116-.635.349-.809l.174-.173c.29-.231.407-.578.407-.925v-.924c0-.29.174-.52.465-.578c.697-.174 2.15-.463 4.242-.463s3.546.29 4.243.463c.232.058.465.289.465.578v.924c0 .347.174.694.407.925c.544.381.51.59.465 1.04c-.058.578-.117 1.56-.117 1.56h.02l-.288 4.289c-.174 1.917-1.681 3.254-3.478 3.254h-3.479c-1.855 0-3.304-1.337-3.478-3.254c-.152-1.977-.218-3.944-.397-5.907");
}

.s1kv5tupz {
  d: path("M4.601 29.9c.14-.947.34-1.882.62-2.787a11.56 11.56 0 0 1 3.12-5.018v7.804z");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sq4_kzbfq {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.597 13.568l-.575 1.842a.584.584 0 0 0 .564.758h.851c.4 0 .682-.385.564-.758l-.575-1.842c-.124-.407-.7-.407-.829 0");
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
}

.su8uv8bru {
  fill: var(--svg-color--000, #000);
  d: path("M17.821 13.588c0-.307.246-.553.553-.553a.55.55 0 0 1 .492.808h-.98a.5.5 0 0 1-.065-.255");
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.t58kq9r-h {
  fill: var(--svg-color--000, #000);
  d: path("M14.196 13.588a.55.55 0 0 0-.553-.553a.55.55 0 0 0-.492.808h.979a.55.55 0 0 0 .066-.255");
}

.thq31dj-g {
  stop-color: var(--svg-color--fe713a, #FE713A);
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ud4d3yb8t {
  stop-color: var(--svg-color--54b9f0, #54B9F0);
}

.uek015btq {
  stop-color: var(--svg-color--351c27, #351C27);
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.ui5t8ob3c {
  d: path("M8.389 21.987a.15.15 0 0 0-.048.11v7.802h1.634v-9.16c-.56.37-1.092.79-1.586 1.248");
}

.uv7-zdjnc {
  stop-color: var(--svg-color--40252a, #40252A);
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v737-kb8e {
  d: path("M9.982 7.208a4.1 4.1 0 0 1 4.1-4.1h3.988a4.1 4.1 0 0 1 4.1 4.1V9.89H9.981z");
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w4mmokmfn {
  d: path("M13.81 20.376c.06.76.585 2.281 2.211 2.281s2.151-1.52 2.211-2.28z");
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wdl5xvb6m {
  stop-color: var(--svg-color--40252a, #40252A);
  stop-opacity: 0;
}

.wjwfebcns {
  stop-color: var(--svg-color--3d2426, #3D2426);
  stop-opacity: 0;
}

.wvw1ebchz {
  stop-color: var(--svg-color--624d68, #624D68);
  stop-opacity: 0;
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.xgcgu4bql {
  cx: 13.351px;
  cy: 13.035px;
  rx: 0.422px;
  ry: 0.213px;
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

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xzdbzvp2x {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M16.012 17.269a3.26 3.26 0 0 1-1.501-.356c-.148-.076-.308.092-.214.226c.362.55.994.917 1.715.917a2.05 2.05 0 0 0 1.715-.917c.093-.14-.066-.302-.215-.226a3.24 3.24 0 0 1-1.5.356");
}

.y2xm7ibwq {
  stop-color: var(--svg-color--624d68, #624D68);
}

.yfct4t52m {
  stop-color: var(--svg-color--41baff, #41BAFF);
}

.yrdgovb8a {
  stop-color: var(--svg-color--fdbf28, #FDBF28);
  stop-opacity: 0;
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z1zvcfbsl {
  cx: 13.351px;
  cy: 13.035px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.422px;
  ry: 0.213px;
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zk6gaob1c {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.012 17.269a3.26 3.26 0 0 1-1.501-.356c-.148-.076-.308.092-.214.226c.362.55.994.917 1.715.917a2.05 2.05 0 0 0 1.715-.917c.093-.14-.066-.302-.215-.226a3.24 3.24 0 0 1-1.5.356Z");
}

.zv2tyvbtc {
  d: path("M18.279 19.168c.608.134 1.195.31 1.763.537V29.9H18.28z");
}

</style>
