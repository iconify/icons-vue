<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iGVDYLb)" class="qgn4m6b9b"/><path fill="url(#iljnsBd)" class="qgn4m6b9b"/><path fill="url(#iUDkVFb)" class="qgn4m6b9b"/><path class="g3qags9cz"/><path fill="url(#i42B9Kr)" class="ma89g7ocx"/><path fill="url(#ifN9Pfe)" class="ma89g7ocx"/><path class="ngwzjcb-d"/><path fill="url(#iwbJP0d)" class="byelksj-j"/><path fill="url(#iucuvHe)" class="byelksj-j"/><path fill="url(#idT8hkc)" class="byelksj-j"/><path fill="url(#iI1FgSc)" class="ma3j-6bml"/><path fill="url(#iI0gPAe)" class="ma3j-6bml"/><path fill="url(#iuAWNRc)" class="ma3j-6bml"/><path fill="url(#iZuQ9gd)" class="ma3j-6bml"/><g filter="url(#ijYndXd)"><path class="gr6uhbu3u"/><path fill="url(#ids0HxU)" class="u99e5yb0f"/></g><path clip-rule="evenodd" class="lqbrsk59g"/><path fill="url(#iv60Sto)" clip-rule="evenodd" class="wh_ctabfh"/><path fill="url(#ikVe87A)" clip-rule="evenodd" class="wh_ctabfh"/><path fill="url(#ir7A61b)" clip-rule="evenodd" class="wh_ctabfh"/><path fill="url(#i2ClvCb)" transform="rotate(-23.31 14.437 8.272)" class="d5xfz_brd"/><path class="w8oltxzpk"/><path fill="url(#iar3Fkc)" class="o56gmwxbe"/><path fill="url(#i5T6x6G)" class="o56gmwxbe"/><path fill="url(#iPJyiTG)" class="o56gmwxbe"/><path fill="url(#ir45IAb)" class="o56gmwxbe"/><path fill="url(#inMRrdA)" class="o56gmwxbe"/><path fill="url(#i3BIdqD)" class="o56gmwxbe"/><path fill="url(#i5yW9ye)" class="yd5q5qbwr"/><path fill="url(#itB4HEc)" class="yd5q5qbwr"/><path fill="url(#iwM2Y8c)" class="yd5q5qbwr"/><path fill="url(#iFJceSb)" class="yd5q5qbwr"/><path class="dyi39t1rc"/><path fill="url(#ity8Ssd)" class="nek2k8yoi"/><path fill="url(#iJRN48b)" class="nek2k8yoi"/><path fill="url(#iECYh7d)" class="nek2k8yoi"/><path class="ae-91abjh"/><path fill="url(#i5RQe9q)" class="b8krgz6uy"/><path fill="url(#iguSJ8b)" class="b8krgz6uy"/><path fill="url(#iITYMFd)" class="b8krgz6uy"/><path fill="url(#iZgcOAe)" class="b8krgz6uy"/><path fill="url(#iKsAvLc)" class="b8krgz6uy"/><g filter="url(#ieg0Djb)"><path clip-rule="evenodd" class="i0y0r_lhq"/></g><path fill="url(#iryOXab)" clip-rule="evenodd" class="pwe40rb4w"/><path fill="url(#ix1idOb)" clip-rule="evenodd" class="pwe40rb4w"/><path class="jj9-e_b6v"/><path fill="url(#ioaUNnd)" class="qxaomdbby"/><path fill="url(#ikuNnbd)" class="qxaomdbby"/><path fill="url(#ii2TMyd)" class="qxaomdbby"/><rect fill="url(#iyVYPbE)" transform="rotate(16.21 22.95 5.65)" class="wr3c_pbqs"/><path fill="url(#igWFLyb)" class="xpgm6sw_l"/><path fill="url(#iz053Pb)" class="wc2h7abfk"/><path fill="url(#idwzUIC)" class="wc2h7abfk"/><path fill="url(#i2DJxGU)" class="w7fnd4bab"/><path fill="url(#iFl6WIb)" class="w7fnd4bab"/><path fill="url(#itcgC9b)" class="ywbescb6v"/><path fill="url(#ilh9zce)" class="v-sia8bsk"/><path fill="url(#iX0eeTc)" class="v-sia8bsk"/><path fill="url(#iKLYroS)" class="v-sia8bsk"/><path fill="url(#iiiXxqd)" class="v-sia8bsk"/><path fill="url(#iyXTYcb)" class="v-sia8bsk"/><g filter="url(#iFMeSec)"><rect class="h6p_qrbmq"/></g><g filter="url(#iuZykDd)"><rect class="f_bxme79n"/></g><path fill="url(#i4RC0Ac)" class="inetyprch"/><g filter="url(#iYqmyHe)"><path fill="url(#iey8Kgi)" class="p7heynbsd"/><path fill="url(#iktuQQb)" class="p7heynbsd"/><path fill="url(#ivwIrLb)" class="p7heynbsd"/><path fill="url(#ihwDd8b)" class="p7heynbsd"/></g><g filter="url(#iuHQTCe)"><path fill="url(#imqahLd)" class="apbr4tbmi"/><path fill="url(#iAt0OEc)" class="apbr4tbmi"/><path fill="url(#ixx32cc)" class="apbr4tbmi"/><path fill="url(#iwlof3b)" class="apbr4tbmi"/></g><path fill="url(#iDhuqac)" class="rm8scpdcl"/><path fill="url(#iAp5EAb)" class="rm8scpdcl"/><path fill="url(#iKCs4oe)" class="rm8scpdcl"/><path clip-rule="evenodd" class="w5i27ibyi"/><g filter="url(#igEIuAe)"><path clip-rule="evenodd" class="a786dacbh"/></g><path class="nkgf4sbfo"/><path fill="url(#iXVvl7c)" class="ozl8fsbzh"/><path fill="url(#ieu6bod)" class="xmkqexbkb"/><ellipse fill="url(#iBIBJdd)" transform="rotate(24.61 13.274 6.244)" class="h_qkkkbpv"/><g filter="url(#i8aHXHI)"><path fill="url(#ip01o2d)" class="p40cr-unf"/></g><defs><radialGradient id="iwbJP0d" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 1.76562 -1.4243 .35293 19.386 22.054)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="q1pop7b3p"/><stop offset="1" class="hprqurbri"/></radialGradient><radialGradient id="iucuvHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 19.34 22.538)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="yh8khw6sg"/><stop offset="1" class="oatqfqb0v"/></radialGradient><radialGradient id="idT8hkc" cx="0" cy="0" r="1" gradientTransform="matrix(.60156 2.5625 -1.184 .27795 17.004 22.741)" gradientUnits="userSpaceOnUse"><stop class="k5h4lpbsq"/><stop offset="1" class="rk193sb3z"/></radialGradient><radialGradient id="iI1FgSc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 13.286 19.773)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="xyj5utbpv"/><stop offset="1" class="q0o1m355n"/></radialGradient><radialGradient id="iI0gPAe" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 11.217 8.252)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wwwuk1sex"/><stop offset="1" class="eigwz2byp"/></radialGradient><radialGradient id="iuAWNRc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.574 22.054)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="omib1tb9q"/><stop offset="1" class="z-vlbvbbc"/></radialGradient><radialGradient id="ids0HxU" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 17.074 20.041)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iv60Sto" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.81 4.47)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="hllbrjbqi"/><stop offset="1" class="y8lqf67-a"/></radialGradient><radialGradient id="ikVe87A" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 11.387 12.07)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="mdfnq_gtj"/><stop offset=".952" class="bw4ryrbal"/></radialGradient><radialGradient id="ir7A61b" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 11.09 12.023)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="l011be-du"/><stop offset="1" class="widna0pfy"/></radialGradient><radialGradient id="i2ClvCb" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 15.426 9.601)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="o89cy-q7m"/><stop offset=".75" class="kw93z0bba"/></radialGradient><radialGradient id="iar3Fkc" cx="0" cy="0" r="1" gradientTransform="matrix(.0293 -5.32953 3.38376 .0186 15.276 17.73)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ioo6anwhf"/><stop offset="1" class="vly_b_ldb"/></radialGradient><radialGradient id="i5T6x6G" cx="0" cy="0" r="1" gradientTransform="rotate(102.351 1.86 11.94)scale(5.84509 2.29049)" gradientUnits="userSpaceOnUse"><stop class="d66h0_v2y"/><stop offset="1" class="d3t9wcc9u"/></radialGradient><radialGradient id="iPJyiTG" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 9.18 7.687)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="yx3aab4wz"/><stop offset="1" class="d2ptywb0c"/></radialGradient><radialGradient id="ir45IAb" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.695 10.47)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="e_wvtt-qm"/><stop offset="1" class="f0_sezbyw"/></radialGradient><radialGradient id="inMRrdA" cx="0" cy="0" r="1" gradientTransform="matrix(-.68752 -3.28125 6.32584 -1.32545 16.043 17.523)" gradientUnits="userSpaceOnUse"><stop class="c1n-4t3te"/><stop offset="1" class="uol2-ibpf"/></radialGradient><radialGradient id="i3BIdqD" cx="0" cy="0" r="1" gradientTransform="rotate(-27.758 31.94 -29.406)scale(2.0129 1.58718)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="pk-0hnbkq"/><stop offset="1" class="ng31r5btx"/></radialGradient><radialGradient id="itB4HEc" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 7.135 30.197)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iFJceSb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.727 12.19)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="i5RQe9q" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.585 17.59)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="iguSJ8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.895 23.06)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iITYMFd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.633 18.385)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="iKsAvLc" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 14.164 17.6)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="ix1idOb" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.948 7.29)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="use5i75_z"/><stop offset="1" class="fl3j6mbvj"/></radialGradient><radialGradient id="ikuNnbd" cx="0" cy="0" r="1" gradientTransform="rotate(22.667 -18.557 43.157)scale(1.2949 2.1866)" gradientUnits="userSpaceOnUse"><stop class="hhyc553gq"/><stop offset="1" class="ss0-anvgm"/></radialGradient><radialGradient id="ii2TMyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 20.116 10.179)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gtma0og_l"/><stop offset="1" class="yf8z_2acj"/></radialGradient><radialGradient id="igWFLyb" cx="0" cy="0" r="1" gradientTransform="matrix(3.40685 0 0 1.20429 4.883 11.695)" gradientUnits="userSpaceOnUse"><stop class="rghujac2y"/><stop offset=".498" class="rsj257spn"/></radialGradient><radialGradient id="iz053Pb" cx="0" cy="0" r="1" gradientTransform="matrix(2.92344 0 0 10.9376 4.336 12.135)" gradientUnits="userSpaceOnUse"><stop class="rghujac2y"/><stop offset=".671" class="qrwwtp3cf"/></radialGradient><radialGradient id="itcgC9b" cx="0" cy="0" r="1" gradientTransform="matrix(1 .46565 -.39135 .84043 8.25 12.656)" gradientUnits="userSpaceOnUse"><stop class="bs8v5pbps"/><stop offset="1" class="cegpmmg6d"/></radialGradient><radialGradient id="ilh9zce" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 12.104 .524)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="iX0eeTc" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 15.105 -9.487)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iKLYroS" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 21.027 4.507)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iiiXxqd" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.255 4.356)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iyXTYcb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 13.026 -3.648)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><radialGradient id="i4RC0Ac" cx="0" cy="0" r="1" gradientTransform="matrix(.51082 .27635 -.39007 .72103 11.993 7.272)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="n304-r4kd"/><stop offset=".684" class="uk3jx7nau"/></radialGradient><radialGradient id="iktuQQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9044 -.05025 .06126 -1.10265 15.918 6.518)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="jijo4-b9s"/><stop offset="1" class="ni_rkbnps"/></radialGradient><radialGradient id="ivwIrLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.56039 1.50733 0 12.814 7.791)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="dd9hd6bwg"/><stop offset="1" class="aw2d6h33n"/></radialGradient><radialGradient id="ihwDd8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4187 -.65298 0 13.701 6.569)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="jynvl5b3k"/><stop offset="1" class="b-jom1b0d"/></radialGradient><radialGradient id="imqahLd" cx="0" cy="0" r="1" gradientTransform="rotate(-38.984 15.267 -18.459)scale(3.31894 5.04539)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="my1ob8bzv"/><stop offset="1" class="eys4t1u9r"/></radialGradient><radialGradient id="iAt0OEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28673 -.9379 1.5089 2.0701 12.582 3.872)" gradientUnits="userSpaceOnUse"><stop class="bd_cirbzn"/><stop offset="1" class="u8iayhb4j"/></radialGradient><radialGradient id="ixx32cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56106 .1591 -.07817 -.27567 17.763 7.456)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="e4cf86x4h"/><stop offset="1" class="dar5wrbvj"/></radialGradient><radialGradient id="iwlof3b" cx="0" cy="0" r="1" gradientTransform="matrix(.95465 -.2261 .6058 2.55786 15.686 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="iDhuqac" cx="0" cy="0" r="1" gradientTransform="matrix(.77879 -.2261 .11036 .38012 15.678 6.393)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="iAp5EAb" cx="0" cy="0" r="1" gradientTransform="matrix(.2422 1.26454 -1.31772 .25239 15.711 6.07)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="iXVvl7c" cx="0" cy="0" r="1" gradientTransform="matrix(.2931 0 0 .56944 13.385 6.598)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ieu6bod" cx="0" cy="0" r="1" gradientTransform="matrix(.26797 0 0 .5799 13.205 6.62)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iGVDYLb" x1="11.824" x2="10.137" y1="26.366" y2="26.616" gradientUnits="userSpaceOnUse"><stop class="q4_mrj_zj"/><stop offset="1" class="afmf_bb8r"/></linearGradient><linearGradient id="iljnsBd" x1="9.277" x2="9.996" y1="24.679" y2="24.616" gradientUnits="userSpaceOnUse"><stop class="u3lolvdoh"/><stop offset="1" class="daujsygaa"/></linearGradient><linearGradient id="iUDkVFb" x1="11.746" x2="11.316" y1="22.968" y2="23.07" gradientUnits="userSpaceOnUse"><stop class="x3ycg2l0r"/><stop offset="1" class="bgzosm0kb"/></linearGradient><linearGradient id="i42B9Kr" x1="23.277" x2="23.219" y1="24.859" y2="23.636" gradientUnits="userSpaceOnUse"><stop class="qrr4uxb4z"/><stop offset="1" class="s8mikn8pw"/></linearGradient><linearGradient id="ifN9Pfe" x1="22.656" x2="22.656" y1="22.71" y2="23.62" gradientUnits="userSpaceOnUse"><stop class="pwx7w1tsv"/><stop offset="1" class="usmw8dbrh"/></linearGradient><linearGradient id="iZuQ9gd" x1="11.12" x2="11.12" y1="18.89" y2="20.21" gradientUnits="userSpaceOnUse"><stop class="f_4kl0b7z"/><stop offset="1" class="h30nofb2x"/></linearGradient><linearGradient id="i5yW9ye" x1="10.324" x2="11.855" y1="29.179" y2="29.179" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iwM2Y8c" x1="9.887" x2="9.887" y1="30.197" y2="29.875" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="ity8Ssd" x1="25.813" x2="26.409" y1="22.327" y2="23.445" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="iJRN48b" x1="26.062" x2="26.756" y1="25.277" y2="24.411" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="iECYh7d" x1="27.776" x2="27.384" y1="24.411" y2="24.585" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="iZgcOAe" x1="13.796" x2="14.246" y1="17.657" y2="18.724" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="iryOXab" x1="21.824" x2="21.637" y1="11.288" y2="10.351" gradientUnits="userSpaceOnUse"><stop offset=".076" class="u-andmsxm"/><stop offset="1" class="zo4dljfdh"/></linearGradient><linearGradient id="ioaUNnd" x1="18.667" x2="17.908" y1="12.436" y2="9.726" gradientUnits="userSpaceOnUse"><stop class="r1i9tc3bx"/><stop offset="1" class="c__hzybex"/></linearGradient><linearGradient id="iyVYPbE" x1="25.473" x2="23.476" y1="6.476" y2="6.546" gradientUnits="userSpaceOnUse"><stop offset=".149" class="te-_ckclm"/><stop offset="1" class="h0a2afbtn"/></linearGradient><linearGradient id="idwzUIC" x1="5.614" x2="5.614" y1="12.768" y2="12.322" gradientUnits="userSpaceOnUse"><stop class="ks316abal"/><stop offset="1" class="yc0zi2bvg"/></linearGradient><linearGradient id="i2DJxGU" x1="5.105" x2="7.199" y1="12.718" y2="12.718" gradientUnits="userSpaceOnUse"><stop class="rghujac2y"/><stop offset=".588" class="b49rzbb9k"/></linearGradient><linearGradient id="iFl6WIb" x1="5.855" x2="5.855" y1="13.351" y2="12.906" gradientUnits="userSpaceOnUse"><stop class="ks316abal"/><stop offset="1" class="yc0zi2bvg"/></linearGradient><linearGradient id="iey8Kgi" x1="15.583" x2="12.515" y1="7.314" y2="7.498" gradientUnits="userSpaceOnUse"><stop class="co18c5bwy"/><stop offset="1" class="kj_uw-bok"/></linearGradient><linearGradient id="iKCs4oe" x1="15.569" x2="15.87" y1="6.43" y2="6.514" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="iBIBJdd" x1="13.198" x2="13.398" y1="6.203" y2="6.268" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ip01o2d" x1="17.224" x2="17.7" y1="5.85" y2="2.743" gradientUnits="userSpaceOnUse"><stop offset=".421" class="zsttjmk2m"/><stop offset="1" class="vu17sxeyk"/></linearGradient><filter id="ijYndXd" width="4.141" height="6.811" x="16.361" y="16.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23776"/></filter><filter id="ieg0Djb" width="9.915" height="8.775" x="15.953" y="3.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.266667 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23776"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.313726 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23776" result="effect2_innerShadow_3987_23776"/></filter><filter id="iFMeSec" width="2.065" height=".799" x="5.024" y="12.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23776" stdDeviation=".15"/></filter><filter id="iuZykDd" width="2.506" height=".866" x="4.54" y="11.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23776" stdDeviation=".15"/></filter><filter id="iYqmyHe" width="4.748" height="5.612" x="12.315" y="4.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.25098 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23776"/></filter><filter id="iuHQTCe" width="5.899" height="5.883" x="12.582" y="2.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0509804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23776"/></filter><filter id="igEIuAe" width="1.079" height=".601" x="13.124" y="5.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23776"/></filter><filter id="i8aHXHI" width="2.352" height="3.646" x="16.237" y="3.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23776" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-playing-handball-medium-dark" /></template>
<style>
.a786dacbh {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M13.637 5.514a.8.8 0 0 0-.232-.017a.16.16 0 0 1-.04-.319c.076-.01.2-.007.336.02c.136.028.297.082.437.186a.16.16 0 0 1-.191.259a.8.8 0 0 0-.31-.13");
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.ae-91abjh {
  fill: var(--svg-color--918996, #918996);
  d: path("M18.76 15.872s-4.632 1.786-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.245 1.784-2.567 1.663-3.264c-.105-.605-.491-1.323-.683-1.704");
}

.afmf_bb8r {
  stop-color: var(--svg-color--8a5a5a, #8A5A5A);
}

.apbr4tbmi {
  d: path("M12.707 3.248a1.1 1.1 0 0 1 1.055-.62c.921.05 1.047.37 1.88.197c.88-.181 1.315-.129 1.692.042l.007.004c.372.168 1.14.518 1.14 2.09c0 1.449-.517 2.213-.766 2.487l.049.018c.248.09.35.353.26.602c-.076.211-.344.333-.682.28a22 22 0 0 1-.891-.157a.266.266 0 0 1-.214-.262V6.736c0-.502-.355-.802-.511-.892c-.017-.519-.176-.758-.436-.883c-.43-.208-.563-.105-1.59-.168c-1.035-.062-1.311-.891-.993-1.545");
}

.aw2d6h33n {
  stop-color: var(--svg-color--9a7468, #9A7468);
  stop-opacity: 0;
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b-jom1b0d {
  stop-color: var(--svg-color--845a4e, #845A4E);
  stop-opacity: 0;
}

.b49rzbb9k {
  stop-color: var(--svg-color--795050, #795050);
}

.b8krgz6uy {
  d: path("M18.76 15.872s-4.632 1.786-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.245 1.784-2.567 1.663-3.264c-.105-.605-.491-1.323-.683-1.704");
}

.bc_6ftbdd {
  stop-color: var(--svg-color--ddd9e2, #DDD9E2);
}

.bd_cirbzn {
  stop-color: var(--svg-color--514342, #514342);
}

.bgzosm0kb {
  stop-color: var(--svg-color--8b615e, #8B615E);
  stop-opacity: 0;
}

.bs8v5pbps {
  stop-color: var(--svg-color--d0662d, #D0662D);
}

.bw4ryrbal {
  stop-color: var(--svg-color--7e4765, #7E4765);
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.byelksj-j {
  d: path("m17.402 24.234l-.398-1.297l2.906-1.383l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.013-.301.057-.914.125c-1.412.225-2.062-.718-2.21-1.218");
}

.c__hzybex {
  stop-color: var(--svg-color--ff813d, #FF813D);
  stop-opacity: 0;
}

.c1n-4t3te {
  stop-color: var(--svg-color--f14a2d, #F14A2D);
}

.c2ukjabcr {
  stop-color: var(--svg-color--4d318d, #4D318D);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.cegpmmg6d {
  stop-color: var(--svg-color--ca502d, #CA502D);
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.co18c5bwy {
  stop-color: var(--svg-color--825756, #825756);
}

.d2ptywb0c {
  stop-color: var(--svg-color--ff8750, #FF8750);
  stop-opacity: 0;
}

.d3t9wcc9u {
  stop-color: var(--svg-color--ff9056, #FF9056);
  stop-opacity: 0;
}

.d5xfz_brd {
  d: path("M14.437 8.272h2.217v3.3h-2.217z");
}

.d66h0_v2y {
  stop-color: var(--svg-color--ff9056, #FF9056);
}

.dar5wrbvj {
  stop-color: var(--svg-color--3f3438, #3F3438);
  stop-opacity: 0;
}

.daujsygaa {
  stop-color: var(--svg-color--936762, #936762);
  stop-opacity: 0;
}

.dd9hd6bwg {
  stop-color: var(--svg-color--9d726c, #9D726C);
}

.dyi39t1rc {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m26.408 22.293l-1.295.558l.035 1.71c.33.29 1.104 1.066 1.808 1.602c.46.35.894.356 1.192.296c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e_wvtt-qm {
  stop-color: var(--svg-color--eb784b, #EB784B);
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.e4cf86x4h {
  stop-color: var(--svg-color--3f3438, #3F3438);
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.eigwz2byp {
  stop-color: var(--svg-color--cf433f, #CF433F);
  stop-opacity: 0;
}

.eys4t1u9r {
  stop-color: var(--svg-color--3d2d32, #3D2D32);
}

.f_4kl0b7z {
  stop-color: var(--svg-color--d76322, #D76322);
}

.f_bxme79n {
  width: 1.906px;
  height: 0.266px;
  x: 4.84px;
  y: 11.933px;
  fill: var(--svg-color--89635e, #89635E);
  rx: 0.133px;
}

.f0_sezbyw {
  stop-color: var(--svg-color--eb784b, #EB784B);
  stop-opacity: 0;
}

.fl3j6mbvj {
  stop-color: var(--svg-color--825d52, #825D52);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3qags9cz {
  fill: var(--svg-color--8e6863, #8E6863);
  d: path("m25.207 24.554l-4.773.703l-.329-2.547l5.215.149z");
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gr6uhbu3u {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M17.01 23.003s-.464-1.23-.64-2.274s2.337-4.437 2.337-4.437c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.539c-.638.568-2.491.982-3.134 1.16");
}

.gtma0og_l {
  stop-color: var(--svg-color--ff985a, #FF985A);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h_qkkkbpv {
  cx: 13.274px;
  cy: 6.244px;
  rx: 0.069px;
  ry: 0.094px;
}

.h0a2afbtn {
  stop-color: var(--svg-color--c86d30, #C86D30);
}

.h30nofb2x {
  stop-color: var(--svg-color--d76322, #D76322);
  stop-opacity: 0;
}

.h6p_qrbmq {
  width: 1.465px;
  height: 0.199px;
  x: 5.324px;
  y: 12.53px;
  fill: var(--svg-color--89635e, #89635E);
  rx: 0.099px;
}

.hhyc553gq {
  stop-color: var(--svg-color--ff9459, #FF9459);
}

.hllbrjbqi {
  stop-color: var(--svg-color--713839, #713839);
}

.hprqurbri {
  stop-color: var(--svg-color--ff7839, #FF7839);
  stop-opacity: 0;
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.i0y0r_lhq {
  fill: var(--svg-color--825c55, #825C55);
  fill-rule: evenodd;
  d: path("M24.776 3.732c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.815a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.inetyprch {
  d: path("M12.305 6.803c.168-.157.254-.392.277-.49h.192V7.52c-.23.147-.56.124-.657-.096c-.084-.189-.021-.423.188-.62");
}

.ioo6anwhf {
  stop-color: var(--svg-color--fb643e, #FB643E);
}

.j23k_cb2p {
  stop-color: var(--svg-color--9c959a, #9C959A);
  stop-opacity: 0;
}

.j2u_3dtev {
  stop-color: var(--svg-color--908582, #908582);
  stop-opacity: 0;
}

.j96xv6b5h {
  stop-color: var(--svg-color--917ea3, #917EA3);
  stop-opacity: 0;
}

.jijo4-b9s {
  stop-color: var(--svg-color--794b40, #794B40);
}

.jj9-e_b6v {
  fill: var(--svg-color--ff832d, #FF832D);
  d: path("m20.192 11.856l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

.jjj62-byh {
  stop-color: var(--svg-color--66638b, #66638B);
}

.jynvl5b3k {
  stop-color: var(--svg-color--845a4e, #845A4E);
}

.k5h4lpbsq {
  stop-color: var(--svg-color--e76637, #E76637);
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kj_uw-bok {
  stop-color: var(--svg-color--875d51, #875D51);
}

.ks316abal {
  stop-color: var(--svg-color--824c5c, #824C5C);
}

.kw93z0bba {
  stop-color: var(--svg-color--7c645a, #7C645A);
}

.l011be-du {
  stop-color: var(--svg-color--704b3e, #704B3E);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lqbrsk59g {
  fill: var(--svg-color--79504f, #79504F);
  fill-rule: evenodd;
  d: path("M6.495 11.935a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.406 1.381 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.375-.47-.93-.095-1.441");
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
  stop-opacity: 0;
}

.ma3j-6bml {
  d: path("m10.66 19.335l1.016-.445l1.61 2.836l-1.563.469v.421l-2.68.258c-.072-.398-.2-1.251.102-2.015c.335-.849 1.149-1.362 1.516-1.524");
}

.ma89g7ocx {
  d: path("m25.207 24.554l-4.773.703l-.329-2.547l5.215.149z");
}

.mdfnq_gtj {
  stop-color: var(--svg-color--7b4850, #7B4850);
  stop-opacity: 0;
}

.mge9r1s9g {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
  stop-opacity: 0;
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.my1ob8bzv {
  stop-color: var(--svg-color--301f27, #301F27);
}

.n304-r4kd {
  stop-color: var(--svg-color--9e746b, #9E746B);
}

.n8gqlhnrc {
  stop-color: var(--svg-color--9583a6, #9583A6);
  stop-opacity: 0;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ne985-vqe {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
  stop-opacity: 0;
}

.nek2k8yoi {
  d: path("m26.408 22.293l-1.295.558l.035 1.71c.33.29 1.104 1.066 1.808 1.602c.46.35.894.356 1.192.296c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
}

.ng31r5btx {
  stop-color: var(--svg-color--eb5f1d, #EB5F1D);
  stop-opacity: 0;
}

.ngwzjcb-d {
  fill: var(--svg-color--ec5d25, #EC5D25);
  d: path("m17.402 24.234l-.398-1.297l2.906-1.383l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.013-.301.057-.914.125c-1.412.225-2.062-.718-2.21-1.218");
}

.ni_rkbnps {
  stop-color: var(--svg-color--794b40, #794B40);
  stop-opacity: 0;
}

.nkgf4sbfo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.088 6.621h1.06c0-.42-.238-.76-.53-.76s-.53.34-.53.76");
}

.o56gmwxbe {
  d: path("m15.953 9.66l.674-.17c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.255l-4.897 2.074c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.o89cy-q7m {
  stop-color: var(--svg-color--60372d, #60372D);
}

.oatqfqb0v {
  stop-color: var(--svg-color--d74b53, #D74B53);
}

.omib1tb9q {
  stop-color: var(--svg-color--fb7640, #FB7640);
  stop-opacity: 0;
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.ozl8fsbzh {
  d: path("M13.737 6.62v-.003c0-.344-.147-.622-.329-.622c-.181 0-.328.278-.328.622v.004z");
}

.p40cr-unf {
  d: path("M16.794 4.614c.167.681.265 1.334.297 1.63c.677-.62.932-1.38.995-2.006c.054-.534-.616-.812-1.07-.526c-.329.207-.314.525-.222.902");
}

.p7heynbsd {
  d: path("M12.545 5.77c.041-.859.32-1.273.45-1.394h4.001l.067 3.391c-.929 2.274-3.764 2.372-4.187 1.55c-.423-.823-.379-2.553-.33-3.547");
}

.pk-0hnbkq {
  stop-color: var(--svg-color--eb5f1d, #EB5F1D);
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.pwe40rb4w {
  fill-rule: evenodd;
  d: path("M24.776 3.732c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.815a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.pwx7w1tsv {
  stop-color: var(--svg-color--865f52, #865F52);
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.q0o1m355n {
  stop-color: var(--svg-color--fc672b, #FC672B);
}

.q1pop7b3p {
  stop-color: var(--svg-color--ff7839, #FF7839);
}

.q1yj_xkrc {
  stop-color: var(--svg-color--504b8a, #504B8A);
}

.q4_mrj_zj {
  stop-color: var(--svg-color--8e635c, #8E635C);
}

.q8c7r9fut {
  stop-color: var(--svg-color--4a4970, #4A4970);
  stop-opacity: 0;
}

.qgn4m6b9b {
  d: path("m10.074 27.984l-1-5.18l2.57-.477v6.36z");
}

.qh9tdvimg {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
}

.qmcjcvbdo {
  stop-color: var(--svg-color--adaaad, #ADAAAD);
  stop-opacity: 0;
}

.qrr4uxb4z {
  stop-color: var(--svg-color--7e446d, #7E446D);
}

.qrwwtp3cf {
  stop-color: var(--svg-color--78504c, #78504C);
}

.qxaomdbby {
  d: path("m20.192 11.856l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

.r1i9tc3bx {
  stop-color: var(--svg-color--f05c24, #F05C24);
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.rghujac2y {
  stop-color: var(--svg-color--977269, #977269);
}

.rk193sb3z {
  stop-color: var(--svg-color--e76637, #E76637);
  stop-opacity: 0;
}

.rm8scpdcl {
  d: path("m15.515 7.329l.214-1.543a.78.78 0 0 1-.214 1.543");
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.rsj257spn {
  stop-color: var(--svg-color--774f4b, #774F4B);
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.s-7nhybnh {
  stop-color: var(--svg-color--a5a3a3, #A5A3A3);
}

.s8mikn8pw {
  stop-color: var(--svg-color--85575e, #85575E);
  stop-opacity: 0;
}

.sew1y7bbn {
  stop-color: var(--svg-color--514d8b, #514D8B);
  stop-opacity: 0;
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.ss0-anvgm {
  stop-color: var(--svg-color--ff9459, #FF9459);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t54cbcb-z {
  stop-color: var(--svg-color--bab6bd, #BAB6BD);
}

.tbe0sc-ij {
  stop-color: var(--svg-color--4a4970, #4A4970);
}

.te-_ckclm {
  stop-color: var(--svg-color--db7c25, #DB7C25);
}

.u-andmsxm {
  stop-color: var(--svg-color--7b4565, #7B4565);
}

.u3lolvdoh {
  stop-color: var(--svg-color--a37970, #A37970);
}

.u8iayhb4j {
  stop-color: var(--svg-color--514342, #514342);
  stop-opacity: 0;
}

.u99e5yb0f {
  d: path("M17.01 23.003s-.464-1.23-.64-2.274s2.337-4.437 2.337-4.437c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.539c-.638.568-2.491.982-3.134 1.16");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uk3jx7nau {
  stop-color: var(--svg-color--8a5752, #8A5752);
}

.uol2-ibpf {
  stop-color: var(--svg-color--f14a2d, #F14A2D);
  stop-opacity: 0;
}

.use5i75_z {
  stop-color: var(--svg-color--917063, #917063);
}

.usmw8dbrh {
  stop-color: var(--svg-color--865f52, #865F52);
  stop-opacity: 0;
}

.v-sia8bsk {
  d: path("M25.013 4.383a2.063 2.063 0 1 1-4.125 0a2.063 2.063 0 0 1 4.125 0");
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vly_b_ldb {
  stop-color: var(--svg-color--fb643e, #FB643E);
  stop-opacity: 0;
}

.vu17sxeyk {
  stop-color: var(--svg-color--403337, #403337);
  stop-opacity: 0;
}

.vuvc8_ujh {
  stop-color: var(--svg-color--444367, #444367);
  stop-opacity: 0;
}

.vx88q5bse {
  stop-color: var(--svg-color--484083, #484083);
  stop-opacity: 0;
}

.w5i27ibyi {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.887 7.815a.134.134 0 0 1-.002.189c-.255.25-.624.315-.742.327a.134.134 0 1 1-.027-.267c.1-.01.393-.066.582-.251a.134.134 0 0 1 .189.002");
}

.w7fnd4bab {
  d: path("M4.955 12.84a.44.44 0 0 1 .44-.44H6.93v.48a.4.4 0 0 1-.4.4H5.395a.44.44 0 0 1-.44-.44");
}

.w8oltxzpk {
  fill: var(--svg-color--f76c2c, #F76C2C);
  d: path("m15.953 9.66l.674-.17c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.255l-4.897 2.074c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.wc2h7abfk {
  d: path("M4.512 12.256a.44.44 0 0 1 .44-.44H6.93v.88H4.95a.44.44 0 0 1-.44-.44");
}

.wh_ctabfh {
  fill-rule: evenodd;
  d: path("M6.495 11.935a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.406 1.381 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.375-.47-.93-.095-1.441");
}

.widna0pfy {
  stop-color: var(--svg-color--704b3e, #704B3E);
  stop-opacity: 0;
}

.wr3c_pbqs {
  width: 2.533px;
  height: 1.362px;
  x: 22.95px;
  y: 5.65px;
  rx: 0.2px;
}

.wwwuk1sex {
  stop-color: var(--svg-color--cf433f, #CF433F);
}

.x3ycg2l0r {
  stop-color: var(--svg-color--815350, #815350);
}

.xmkqexbkb {
  d: path("m13.528 6.62l.004-.077c0-.198-.085-.36-.189-.36s-.188.162-.188.36q0 .04.004.078z");
}

.xpgm6sw_l {
  d: path("M5.084 11.816a.44.44 0 0 1 .44-.44h1.374c.112 0 .54.008.899.147l.11.34l-.404.393H5.524a.44.44 0 0 1-.44-.44");
}

.xyj5utbpv {
  stop-color: var(--svg-color--ef6923, #EF6923);
}

.y8lqf67-a {
  stop-color: var(--svg-color--713839, #713839);
  stop-opacity: 0;
}

.yc0zi2bvg {
  stop-color: var(--svg-color--824c5c, #824C5C);
  stop-opacity: 0;
}

.ycb1huo4n {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
}

.yd5q5qbwr {
  d: path("m7.863 28.906l2.215-1.072l1.574.752l-.014 1.34a.253.253 0 0 1-.251.248l-3.855.023c-.221.001-.418-.15-.395-.37c.046-.452.333-.736.726-.921");
}

.yf8z_2acj {
  stop-color: var(--svg-color--ff985a, #FF985A);
  stop-opacity: 0;
}

.yh8khw6sg {
  stop-color: var(--svg-color--d74b53, #D74B53);
  stop-opacity: 0;
}

.ywbescb6v {
  d: path("M8.288 11.846a.197.197 0 0 1 .258-.09c.244.112.694.325.974.496c.084.052.107.16.06.246l-1.028 1.907a.186.186 0 0 1-.223.09a4 4 0 0 1-.974-.494a.19.19 0 0 1-.058-.247z");
}

.yx3aab4wz {
  stop-color: var(--svg-color--ff8750, #FF8750);
}

.z-vlbvbbc {
  stop-color: var(--svg-color--fb7640, #FB7640);
}

.zo4dljfdh {
  stop-color: var(--svg-color--7b4565, #7B4565);
  stop-opacity: 0;
}

.zsttjmk2m {
  stop-color: var(--svg-color--403337, #403337);
}

</style>
