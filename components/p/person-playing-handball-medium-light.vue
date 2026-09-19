<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iHD14fb)" class="zeg5sabaz"/><path fill="url(#ifonCIg)" class="zeg5sabaz"/><path fill="url(#iUnrjuT)" class="zeg5sabaz"/><path class="vd52uabtv"/><path fill="url(#iO3e62b)" class="omznjsb0g"/><path fill="url(#iiRK8od)" class="omznjsb0g"/><path class="tmxi2_bfl"/><path fill="url(#iQBE8ve)" class="fjfm5pj-o"/><path fill="url(#iQkpWAc)" class="fjfm5pj-o"/><path fill="url(#i33Bgmc)" class="fjfm5pj-o"/><path fill="url(#iIYnCqe)" class="z_22iv9bb"/><path fill="url(#iwA7ufb)" class="z_22iv9bb"/><path fill="url(#iAlJh1c)" class="z_22iv9bb"/><path fill="url(#iV93hMe)" class="z_22iv9bb"/><g filter="url(#i3F25Qd)"><path class="o1aiahbfk"/><path fill="url(#iTAPAqc)" class="aqa5c3brz"/></g><path clip-rule="evenodd" class="t03tk9lor"/><path fill="url(#iMjZrPd)" clip-rule="evenodd" class="joon06atp"/><path fill="url(#iTxUinc)" clip-rule="evenodd" class="joon06atp"/><path fill="url(#iA1awRc)" clip-rule="evenodd" class="joon06atp"/><path fill="url(#iXIvnJc)" transform="rotate(-23.31 14.437 7.98)" class="ue_9ai6eb"/><path class="cpody5b_d"/><path fill="url(#iRY4q5c)" class="p0-un4b3x"/><path fill="url(#icx1oWu)" class="p0-un4b3x"/><path fill="url(#izRGg5g)" class="p0-un4b3x"/><path fill="url(#ivR1Rje)" class="p0-un4b3x"/><path fill="url(#iulsJgb)" class="p0-un4b3x"/><path fill="url(#iIqgHCZ)" class="p0-un4b3x"/><path fill="url(#iCtUvmT)" class="ucl2tybze"/><path fill="url(#ii7tcLc)" class="ucl2tybze"/><path fill="url(#i2crHgc)" class="ucl2tybze"/><path fill="url(#idK6ile)" class="ucl2tybze"/><path class="zmr2254cb"/><path fill="url(#iv8w8sQ)" class="rmfo6z_hn"/><path fill="url(#iOOGHGb)" class="rmfo6z_hn"/><path fill="url(#i1hfn1d)" class="rmfo6z_hn"/><path class="n1mxv41iz"/><path fill="url(#ibmgCqi)" class="s4ig8b3bw"/><path fill="url(#iw58Cvc)" class="s4ig8b3bw"/><path fill="url(#iHguBbc)" class="s4ig8b3bw"/><path fill="url(#i4dgO0c)" class="s4ig8b3bw"/><path fill="url(#itVRJ0c)" class="s4ig8b3bw"/><g filter="url(#iMR2aWb)"><path clip-rule="evenodd" class="ut2una94e"/></g><path fill="url(#i1Q6ZZZ)" clip-rule="evenodd" class="i7xbcsyur"/><path fill="url(#i2u1ETc)" clip-rule="evenodd" class="i7xbcsyur"/><path class="px5c21brg"/><path fill="url(#iJSb4He)" class="k1q0ufiag"/><path fill="url(#iqMHZtd)" class="k1q0ufiag"/><path fill="url(#iGtG6Pe)" class="k1q0ufiag"/><rect fill="url(#ikLHGac)" transform="rotate(16.21 22.95 5.358)" class="s_0d-zx_y"/><path fill="url(#ivL2WOc)" class="lupv7v83w"/><path fill="url(#izSrgVb)" class="ebl-bfb0u"/><path fill="url(#inWqQcb)" class="ebl-bfb0u"/><path fill="url(#i9THuZd)" class="lxlfkhbxj"/><path fill="url(#iiO6JDd)" class="lxlfkhbxj"/><path fill="url(#iHkNrhd)" class="jj_bpovaw"/><path fill="url(#iReDsIe)" class="i7rt9jb_v"/><path fill="url(#ixnUssd)" class="i7rt9jb_v"/><path fill="url(#il1l8yb)" class="i7rt9jb_v"/><path fill="url(#iIhWSQc)" class="i7rt9jb_v"/><path fill="url(#iw75h3d)" class="i7rt9jb_v"/><g filter="url(#i7mKC1V)"><rect class="rqnxvnxny"/></g><path fill="url(#i5LGvvd)" class="wypfi4brd"/><path fill="url(#iWYyqbb)" class="wypfi4brd"/><g filter="url(#ikbDx7c)"><path fill="url(#ihfLcYd)" class="fs8-01b_x"/><path fill="url(#iN6Iylc)" class="fs8-01b_x"/><path fill="url(#iEv8sdc)" class="fs8-01b_x"/><path fill="url(#iMtwfla)" class="fs8-01b_x"/></g><g filter="url(#ibjVlFb)"><path fill="url(#i35cW7c)" class="t37tphbdk"/><path fill="url(#iEuH7Dd)" class="t37tphbdk"/><path fill="url(#iozeqBb)" class="t37tphbdk"/></g><path fill="url(#iSJHaSb)" class="d7wsnjbbs"/><path fill="url(#iLexC6c)" class="d7wsnjbbs"/><path fill="url(#iUNXfzb)" class="d7wsnjbbs"/><path clip-rule="evenodd" class="z6ek77bcu"/><g filter="url(#istpwhb)"><path clip-rule="evenodd" class="v678cdbes"/></g><path class="sleni0bge"/><path fill="url(#iaFfXEb)" class="zm3m1tbbe"/><path fill="url(#ifWFiyb)" class="hqp3pz_0r"/><ellipse fill="url(#imhxlue)" transform="rotate(24.61 13.274 5.952)" class="nxpms02wt"/><g filter="url(#iTbrN0d)"><path fill="url(#inRkKfd)" class="ytkho7eel"/></g><defs><radialGradient id="iQBE8ve" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 1.76562 -1.4243 .35293 19.387 21.763)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="q1pop7b3p"/><stop offset="1" class="hprqurbri"/></radialGradient><radialGradient id="iQkpWAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 19.34 22.246)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="yh8khw6sg"/><stop offset="1" class="oatqfqb0v"/></radialGradient><radialGradient id="i33Bgmc" cx="0" cy="0" r="1" gradientTransform="matrix(.60156 2.5625 -1.184 .27795 17.004 22.45)" gradientUnits="userSpaceOnUse"><stop class="k5h4lpbsq"/><stop offset="1" class="rk193sb3z"/></radialGradient><radialGradient id="iIYnCqe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 13.286 19.48)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="xyj5utbpv"/><stop offset="1" class="q0o1m355n"/></radialGradient><radialGradient id="iwA7ufb" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 11.157 8.106)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wwwuk1sex"/><stop offset="1" class="eigwz2byp"/></radialGradient><radialGradient id="iAlJh1c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.574 21.762)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="omib1tb9q"/><stop offset="1" class="z-vlbvbbc"/></radialGradient><radialGradient id="iTAPAqc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 17.074 19.75)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iMjZrPd" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.752 4.325)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="swgsx6bpm"/><stop offset="1" class="wcx06_c5w"/></radialGradient><radialGradient id="iTxUinc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 11.387 11.777)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="so5pusb0b"/><stop offset=".952" class="ifv48cbic"/></radialGradient><radialGradient id="iA1awRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 11.09 11.73)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="apa7qrbhd"/><stop offset="1" class="g7rslpl_w"/></radialGradient><radialGradient id="iXIvnJc" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 15.426 9.309)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="qik8kac6n"/><stop offset=".75" class="d8jx6bckt"/></radialGradient><radialGradient id="iRY4q5c" cx="0" cy="0" r="1" gradientTransform="matrix(.0293 -5.32953 3.38376 .0186 15.275 17.439)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ioo6anwhf"/><stop offset="1" class="vly_b_ldb"/></radialGradient><radialGradient id="icx1oWu" cx="0" cy="0" r="1" gradientTransform="rotate(102.351 1.977 11.793)scale(5.84509 2.29049)" gradientUnits="userSpaceOnUse"><stop class="d66h0_v2y"/><stop offset="1" class="d3t9wcc9u"/></radialGradient><radialGradient id="izRGg5g" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 9.185 7.541)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="yx3aab4wz"/><stop offset="1" class="d2ptywb0c"/></radialGradient><radialGradient id="ivR1Rje" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.766 10.323)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="e_wvtt-qm"/><stop offset="1" class="f0_sezbyw"/></radialGradient><radialGradient id="iulsJgb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68752 -3.28125 6.32584 -1.32545 16.043 17.23)" gradientUnits="userSpaceOnUse"><stop class="c1n-4t3te"/><stop offset="1" class="uol2-ibpf"/></radialGradient><radialGradient id="iIqgHCZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 17.371 11.2)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="pk-0hnbkq"/><stop offset="1" class="ng31r5btx"/></radialGradient><radialGradient id="ii7tcLc" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 7.135 29.905)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="idK6ile" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.644 12.044)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="ibmgCqi" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.584 17.298)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="iw58Cvc" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.895 22.769)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iHguBbc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.633 18.093)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="itVRJ0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 14.164 17.309)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="i2u1ETc" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 12.007 7.144)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="bg8bjl54k"/><stop offset="1" class="mdp6qlbos"/></radialGradient><radialGradient id="iqMHZtd" cx="0" cy="0" r="1" gradientTransform="rotate(22.667 -17.828 43.011)scale(1.2949 2.1866)" gradientUnits="userSpaceOnUse"><stop class="hhyc553gq"/><stop offset="1" class="ss0-anvgm"/></radialGradient><radialGradient id="iGtG6Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 20.115 9.887)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gtma0og_l"/><stop offset="1" class="yf8z_2acj"/></radialGradient><radialGradient id="iHkNrhd" cx="0" cy="0" r="1" gradientTransform="matrix(1 .46565 -.39135 .84043 8.25 12.364)" gradientUnits="userSpaceOnUse"><stop class="bs8v5pbps"/><stop offset="1" class="cegpmmg6d"/></radialGradient><radialGradient id="iReDsIe" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 12.088 .378)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ixnUssd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.938 -9.633)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="il1l8yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 21.027 4.215)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iIhWSQc" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.282 4.21)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iw75h3d" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.948 -3.794)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><radialGradient id="i5LGvvd" cx="0" cy="0" r="1" gradientTransform="matrix(.51083 .27635 -.39008 .72105 11.993 6.98)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="rcpmccbyc"/><stop offset=".684" class="wdglv_bwm"/></radialGradient><radialGradient id="iWYyqbb" cx="0" cy="0" r="1" gradientTransform="rotate(-112.383 8.665 -.501)scale(.33794 .50718)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iN6Iylc" cx="0" cy="0" r="1" gradientTransform="matrix(-.90442 -.05025 .06126 -1.10267 15.918 6.226)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="iEv8sdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.5605 2.16056 0 12.814 7.5)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="nkfrpdbdq"/><stop offset="1" class="eqwiy2pxg"/></radialGradient><radialGradient id="iMtwfla" cx="0" cy="0" r="1" gradientTransform="matrix(0 .41871 -.653 0 13.701 6.277)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="i35cW7c" cx="0" cy="0" r="1" gradientTransform="matrix(2.57994 -2.088 3.17413 3.92197 15.012 5.202)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="te4zz7dbn"/><stop offset="1" class="otf1z2b9l"/></radialGradient><radialGradient id="iEuH7Dd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28676 -.9379 1.50892 2.07015 12.582 3.58)" gradientUnits="userSpaceOnUse"><stop class="r-95cxbic"/><stop offset="1" class="efo8wovhu"/></radialGradient><radialGradient id="iozeqBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56108 .1591 -.07818 -.27568 17.762 7.164)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="cl2mrcsll"/><stop offset="1" class="hms2sfnpk"/></radialGradient><radialGradient id="iSJHaSb" cx="0" cy="0" r="1" gradientTransform="matrix(.7788 -.2261 .11036 .38012 15.678 6.1)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="iLexC6c" cx="0" cy="0" r="1" gradientTransform="matrix(.24221 1.26457 -1.31774 .2524 15.71 5.779)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="iaFfXEb" cx="0" cy="0" r="1" gradientTransform="matrix(.2931 0 0 .56945 13.385 6.306)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ifWFiyb" cx="0" cy="0" r="1" gradientTransform="matrix(.26798 0 0 .57992 13.205 6.329)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iHD14fb" x1="11.824" x2="10.137" y1="26.075" y2="26.325" gradientUnits="userSpaceOnUse"><stop class="s0d_o1h9v"/><stop offset="1" class="q1-w0b0qt"/></linearGradient><linearGradient id="ifonCIg" x1="9.391" x2="10.125" y1="24.384" y2="24.244" gradientUnits="userSpaceOnUse"><stop offset=".237" class="l2quysbsq"/><stop offset="1" class="qibnn1bya"/></linearGradient><linearGradient id="iUnrjuT" x1="11.746" x2="11.316" y1="22.676" y2="22.778" gradientUnits="userSpaceOnUse"><stop class="lyz1uln4w"/><stop offset="1" class="pvjw0ujzi"/></linearGradient><linearGradient id="iO3e62b" x1="23.277" x2="23.219" y1="24.567" y2="23.344" gradientUnits="userSpaceOnUse"><stop class="afqpej-7d"/><stop offset="1" class="aft-xhbkd"/><stop offset="1" class="cll88gg-t"/></linearGradient><linearGradient id="iiRK8od" x1="22.656" x2="22.656" y1="22.418" y2="23.328" gradientUnits="userSpaceOnUse"><stop class="okh6_pbqf"/><stop offset="1" class="u1j_tu46h"/></linearGradient><linearGradient id="iV93hMe" x1="11.12" x2="11.12" y1="18.598" y2="19.918" gradientUnits="userSpaceOnUse"><stop class="f_4kl0b7z"/><stop offset="1" class="h30nofb2x"/></linearGradient><linearGradient id="iCtUvmT" x1="10.324" x2="11.855" y1="28.887" y2="28.887" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="i2crHgc" x1="9.887" x2="9.887" y1="29.905" y2="29.582" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iv8w8sQ" x1="25.813" x2="26.409" y1="22.035" y2="23.153" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="iOOGHGb" x1="26.062" x2="26.756" y1="24.985" y2="24.119" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="i1hfn1d" x1="27.776" x2="27.384" y1="24.119" y2="24.294" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="i4dgO0c" x1="13.796" x2="14.246" y1="17.365" y2="18.432" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="i1Q6ZZZ" x1="21.824" x2="21.637" y1="10.996" y2="10.059" gradientUnits="userSpaceOnUse"><stop offset=".076" class="bf4ns_o8j"/><stop offset="1" class="oi5imboky"/></linearGradient><linearGradient id="iJSb4He" x1="18.667" x2="17.908" y1="12.144" y2="9.434" gradientUnits="userSpaceOnUse"><stop class="r1i9tc3bx"/><stop offset="1" class="c__hzybex"/></linearGradient><linearGradient id="ikLHGac" x1="25.473" x2="23.476" y1="6.184" y2="6.254" gradientUnits="userSpaceOnUse"><stop class="dks6vbcwf"/><stop offset="1" class="jl_acuvtz"/></linearGradient><linearGradient id="ivL2WOc" x1="4.75" x2="8.29" y1="11.403" y2="11.403" gradientUnits="userSpaceOnUse"><stop class="dosa6sbas"/><stop offset=".588" class="gd67z4bal"/></linearGradient><linearGradient id="izSrgVb" x1="4.696" x2="7.259" y1="11.843" y2="11.843" gradientUnits="userSpaceOnUse"><stop class="dosa6sbas"/><stop offset=".588" class="gd67z4bal"/></linearGradient><linearGradient id="inWqQcb" x1="5.614" x2="5.614" y1="12.476" y2="12.03" gradientUnits="userSpaceOnUse"><stop class="x9uaycblj"/><stop offset="1" class="pnjqveb_u"/></linearGradient><linearGradient id="i9THuZd" x1="5.105" x2="7.199" y1="12.426" y2="12.426" gradientUnits="userSpaceOnUse"><stop class="lpv-lnbtt"/><stop offset=".588" class="gex5jb8qh"/></linearGradient><linearGradient id="iiO6JDd" x1="5.855" x2="5.855" y1="13.059" y2="12.614" gradientUnits="userSpaceOnUse"><stop class="x3uyqiwdn"/><stop offset="1" class="l_u_tcbng"/></linearGradient><linearGradient id="ihfLcYd" x1="15.584" x2="12.515" y1="7.022" y2="7.206" gradientUnits="userSpaceOnUse"><stop class="w6b0chbuk"/><stop offset="1" class="n3dqqoxxk"/></linearGradient><linearGradient id="iUNXfzb" x1="15.619" x2="15.778" y1="6.174" y2="6.187" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="imhxlue" x1="13.198" x2="13.398" y1="5.911" y2="5.976" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="inRkKfd" x1="16.99" x2="17.467" y1="5.672" y2="2.565" gradientUnits="userSpaceOnUse"><stop offset=".421" class="esqjgpxir"/><stop offset="1" class="lj6qdgbam"/></linearGradient><filter id="i3F25Qd" width="4.141" height="6.811" x="16.361" y="15.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23782"/></filter><filter id="iMR2aWb" width="9.915" height="8.775" x="15.953" y="2.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.466667 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23782"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.603922 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23782" result="effect2_innerShadow_3987_23782"/></filter><filter id="i7mKC1V" width="2.065" height=".799" x="5.024" y="11.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23782" stdDeviation=".15"/></filter><filter id="ikbDx7c" width="4.748" height="5.612" x="12.315" y="3.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.462745 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23782"/></filter><filter id="ibjVlFb" width="5.899" height="5.883" x="12.582" y="2.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.682353 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23782"/></filter><filter id="istpwhb" width="1.079" height=".601" x="13.124" y="4.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23782"/></filter><filter id="iTbrN0d" width="2.352" height="3.646" x="16.004" y="2.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23782" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-playing-handball-medium-light" /></template>
<style>
.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.afqpej-7d {
  stop-color: var(--svg-color--bb778c, #BB778C);
}

.aft-xhbkd {
  stop-color: var(--svg-color--ce918e, #CE918E);
  stop-opacity: 0;
}

.apa7qrbhd {
  stop-color: var(--svg-color--c8926f, #C8926F);
}

.aqa5c3brz {
  d: path("M17.01 22.711s-.464-1.23-.64-2.274S18.707 16 18.707 16c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.538c-.638.57-2.491.983-3.134 1.161");
}

.bc_6ftbdd {
  stop-color: var(--svg-color--ddd9e2, #DDD9E2);
}

.bf4ns_o8j {
  stop-color: var(--svg-color--b97782, #B97782);
}

.bg8bjl54k {
  stop-color: var(--svg-color--e1b898, #E1B898);
}

.bs8v5pbps {
  stop-color: var(--svg-color--d0662d, #D0662D);
}

.c__hzybex {
  stop-color: var(--svg-color--ff813d, #FF813D);
  stop-opacity: 0;
}

.c-xbvquvy {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
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

.ccv6f1brb {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
  stop-opacity: 0;
}

.cegpmmg6d {
  stop-color: var(--svg-color--ca502d, #CA502D);
}

.cl2mrcsll {
  stop-color: var(--svg-color--ffdda9, #FFDDA9);
}

.cll88gg-t {
  stop-color: var(--svg-color--ac787c, #AC787C);
  stop-opacity: 0;
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.cpody5b_d {
  fill: var(--svg-color--f76c2c, #F76C2C);
  d: path("m15.953 9.367l.674-.169c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.255l-4.897 2.074c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.d2ptywb0c {
  stop-color: var(--svg-color--ff8750, #FF8750);
  stop-opacity: 0;
}

.d3t9wcc9u {
  stop-color: var(--svg-color--ff9056, #FF9056);
  stop-opacity: 0;
}

.d66h0_v2y {
  stop-color: var(--svg-color--ff9056, #FF9056);
}

.d7wsnjbbs {
  d: path("m15.515 7.037l.214-1.543a.779.779 0 0 1-.214 1.543");
}

.d8jx6bckt {
  stop-color: var(--svg-color--cb9b80, #CB9B80);
}

.dks6vbcwf {
  stop-color: var(--svg-color--ea8521, #EA8521);
}

.dosa6sbas {
  stop-color: var(--svg-color--f9be9f, #F9BE9F);
}

.e_wvtt-qm {
  stop-color: var(--svg-color--eb784b, #EB784B);
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.ebl-bfb0u {
  d: path("M4.512 11.964a.44.44 0 0 1 .44-.44H6.93v.88H4.95a.44.44 0 0 1-.44-.44");
}

.efo8wovhu {
  stop-color: var(--svg-color--ffeeb8, #FFEEB8);
  stop-opacity: 0;
}

.eigwz2byp {
  stop-color: var(--svg-color--cf433f, #CF433F);
  stop-opacity: 0;
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.eqwiy2pxg {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
  stop-opacity: 0;
}

.esqjgpxir {
  stop-color: var(--svg-color--fff9bd, #FFF9BD);
}

.f_4kl0b7z {
  stop-color: var(--svg-color--d76322, #D76322);
}

.f0_sezbyw {
  stop-color: var(--svg-color--eb784b, #EB784B);
  stop-opacity: 0;
}

.fjfm5pj-o {
  d: path("m17.402 23.942l-.398-1.297l2.906-1.383l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.013-.301.057-.914.125c-1.412.225-2.062-.718-2.21-1.218");
}

.fs8-01b_x {
  d: path("M12.545 5.478c.041-.859.32-1.273.45-1.394h4.001l.067 3.391c-.928 2.275-3.764 2.372-4.187 1.55c-.423-.823-.379-2.553-.33-3.547");
}

.ft5dv1b6b {
  fill: none;
}

.g7rslpl_w {
  stop-color: var(--svg-color--c8926f, #C8926F);
  stop-opacity: 0;
}

.gd67z4bal {
  stop-color: var(--svg-color--d0937d, #D0937D);
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gex5jb8qh {
  stop-color: var(--svg-color--cf927e, #CF927E);
}

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.gtma0og_l {
  stop-color: var(--svg-color--ff985a, #FF985A);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h30nofb2x {
  stop-color: var(--svg-color--d76322, #D76322);
  stop-opacity: 0;
}

.hhyc553gq {
  stop-color: var(--svg-color--ff9459, #FF9459);
}

.hms2sfnpk {
  stop-color: var(--svg-color--ffdda9, #FFDDA9);
  stop-opacity: 0;
}

.hprqurbri {
  stop-color: var(--svg-color--ff7839, #FF7839);
  stop-opacity: 0;
}

.hqp3pz_0r {
  d: path("m13.528 6.329l.004-.078c0-.198-.085-.36-.189-.36s-.188.162-.188.36q0 .04.004.078z");
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.i7rt9jb_v {
  d: path("M25.013 4.091a2.063 2.063 0 1 1-4.125 0a2.063 2.063 0 0 1 4.125 0");
}

.i7xbcsyur {
  fill-rule: evenodd;
  d: path("M24.776 3.44c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.815a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.ifv48cbic {
  stop-color: var(--svg-color--be7782, #BE7782);
}

.ioo6anwhf {
  stop-color: var(--svg-color--fb643e, #FB643E);
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
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

.jj_bpovaw {
  d: path("M8.288 11.554a.197.197 0 0 1 .258-.09c.244.112.694.325.974.496c.084.052.107.16.06.246l-1.028 1.907a.186.186 0 0 1-.223.09a4 4 0 0 1-.974-.494a.19.19 0 0 1-.058-.247z");
}

.jjj62-byh {
  stop-color: var(--svg-color--66638b, #66638B);
}

.jl_acuvtz {
  stop-color: var(--svg-color--d97031, #D97031);
}

.joon06atp {
  fill-rule: evenodd;
  d: path("M6.495 11.643a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.406 1.381 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.375-.47-.93-.095-1.441");
}

.k1q0ufiag {
  d: path("m20.192 11.564l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

.k5h4lpbsq {
  stop-color: var(--svg-color--e76637, #E76637);
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.ksl77bchk {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
  stop-opacity: 0;
}

.l_u_tcbng {
  stop-color: var(--svg-color--d38f87, #D38F87);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l2quysbsq {
  stop-color: var(--svg-color--ffc3a5, #FFC3A5);
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lj6qdgbam {
  stop-color: var(--svg-color--fff9bd, #FFF9BD);
  stop-opacity: 0;
}

.lpv-lnbtt {
  stop-color: var(--svg-color--f8bea1, #F8BEA1);
}

.lupv7v83w {
  d: path("M5.084 11.524a.44.44 0 0 1 .44-.44h1.374c.112 0 .54.008.899.147l.11.34l-.404.393H5.524a.44.44 0 0 1-.44-.44");
}

.lxlfkhbxj {
  d: path("M4.955 12.547a.44.44 0 0 1 .44-.44H6.93v.48a.4.4 0 0 1-.4.4H5.395a.44.44 0 0 1-.44-.44");
}

.lyz1uln4w {
  stop-color: var(--svg-color--ca907f, #CA907F);
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
  stop-opacity: 0;
}

.mdp6qlbos {
  stop-color: var(--svg-color--d3a387, #D3A387);
  stop-opacity: 0;
}

.mge9r1s9g {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
  stop-opacity: 0;
}

.n1mxv41iz {
  fill: var(--svg-color--918996, #918996);
  d: path("M18.76 15.58s-4.632 1.786-7.165 3.045a17.6 17.6 0 0 0 1.804 3.371a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.245 1.784-2.567 1.663-3.264c-.105-.604-.491-1.323-.683-1.704");
}

.n3dqqoxxk {
  stop-color: var(--svg-color--f2b592, #F2B592);
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

.ng31r5btx {
  stop-color: var(--svg-color--eb5f1d, #EB5F1D);
  stop-opacity: 0;
}

.nkfrpdbdq {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
}

.nxpms02wt {
  cx: 13.274px;
  cy: 5.952px;
  rx: 0.069px;
  ry: 0.094px;
}

.o1aiahbfk {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M17.01 22.711s-.464-1.23-.64-2.274S18.707 16 18.707 16c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.538c-.638.57-2.491.983-3.134 1.161");
}

.oatqfqb0v {
  stop-color: var(--svg-color--d74b53, #D74B53);
}

.oi5imboky {
  stop-color: var(--svg-color--cb9089, #CB9089);
  stop-opacity: 0;
}

.okh6_pbqf {
  stop-color: var(--svg-color--d5a887, #D5A887);
}

.omib1tb9q {
  stop-color: var(--svg-color--fb7640, #FB7640);
  stop-opacity: 0;
}

.omznjsb0g {
  d: path("m25.207 24.262l-4.773.703l-.329-2.547l5.215.149z");
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.otf1z2b9l {
  stop-color: var(--svg-color--ffedae, #FFEDAE);
}

.p0-un4b3x {
  d: path("m15.953 9.367l.674-.169c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.255l-4.897 2.074c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.pfu46_y1s {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
}

.pk-0hnbkq {
  stop-color: var(--svg-color--eb5f1d, #EB5F1D);
}

.pnjqveb_u {
  stop-color: var(--svg-color--de9d8a, #DE9D8A);
  stop-opacity: 0;
}

.pvjw0ujzi {
  stop-color: var(--svg-color--dba390, #DBA390);
  stop-opacity: 0;
}

.px5c21brg {
  fill: var(--svg-color--ff832d, #FF832D);
  d: path("m20.192 11.564l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

.q0o1m355n {
  stop-color: var(--svg-color--fc672b, #FC672B);
}

.q1-w0b0qt {
  stop-color: var(--svg-color--e9ae95, #E9AE95);
}

.q1pop7b3p {
  stop-color: var(--svg-color--ff7839, #FF7839);
}

.q1yj_xkrc {
  stop-color: var(--svg-color--504b8a, #504B8A);
}

.q8c7r9fut {
  stop-color: var(--svg-color--4a4970, #4A4970);
  stop-opacity: 0;
}

.qdq-erb7u {
  stop-color: var(--svg-color--e5a88d, #E5A88D);
}

.qh9tdvimg {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
}

.qibnn1bya {
  stop-color: var(--svg-color--eeb096, #EEB096);
  stop-opacity: 0;
}

.qik8kac6n {
  stop-color: var(--svg-color--bb754f, #BB754F);
}

.qmcjcvbdo {
  stop-color: var(--svg-color--adaaad, #ADAAAD);
  stop-opacity: 0;
}

.r-95cxbic {
  stop-color: var(--svg-color--ffeeb8, #FFEEB8);
}

.r1i9tc3bx {
  stop-color: var(--svg-color--f05c24, #F05C24);
}

.rcpmccbyc {
  stop-color: var(--svg-color--fec19d, #FEC19D);
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.rk193sb3z {
  stop-color: var(--svg-color--e76637, #E76637);
  stop-opacity: 0;
}

.rmfo6z_hn {
  d: path("m26.408 22.001l-1.295.558l.035 1.71c.33.29 1.104 1.066 1.808 1.603c.46.35.894.355 1.192.295c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rqnxvnxny {
  width: 1.465px;
  height: 0.199px;
  x: 5.324px;
  y: 12.239px;
  fill: var(--svg-color--e1a78f, #E1A78F);
  rx: 0.099px;
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.s_0d-zx_y {
  width: 2.533px;
  height: 1.362px;
  x: 22.95px;
  y: 5.358px;
  rx: 0.2px;
}

.s-7nhybnh {
  stop-color: var(--svg-color--a5a3a3, #A5A3A3);
}

.s0d_o1h9v {
  stop-color: var(--svg-color--e2ac95, #E2AC95);
}

.s4ig8b3bw {
  d: path("M18.76 15.58s-4.632 1.786-7.165 3.045a17.6 17.6 0 0 0 1.804 3.371a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.245 1.784-2.567 1.663-3.264c-.105-.604-.491-1.323-.683-1.704");
}

.sew1y7bbn {
  stop-color: var(--svg-color--514d8b, #514D8B);
  stop-opacity: 0;
}

.sleni0bge {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.088 6.329h1.06c0-.42-.238-.76-.53-.76s-.53.34-.53.76");
}

.so5pusb0b {
  stop-color: var(--svg-color--be7782, #BE7782);
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

.swgsx6bpm {
  stop-color: var(--svg-color--c17560, #C17560);
}

.t03tk9lor {
  fill: var(--svg-color--d0937d, #D0937D);
  fill-rule: evenodd;
  d: path("M6.495 11.643a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.406 1.381 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.375-.47-.93-.095-1.441");
}

.t37tphbdk {
  d: path("M12.707 2.956a1.1 1.1 0 0 1 1.055-.62c.921.05 1.047.37 1.88.197c.88-.181 1.315-.129 1.692.042l.007.004c.372.168 1.14.518 1.14 2.09c0 1.449-.516 2.213-.766 2.487l.049.018c.248.09.35.353.26.602c-.076.211-.344.333-.682.28c-.386-.06-.67-.113-.891-.157a.266.266 0 0 1-.214-.262V6.444c0-.502-.355-.802-.511-.892c-.017-.519-.176-.757-.435-.883c-.43-.208-.564-.105-1.592-.168c-1.034-.062-1.31-.891-.992-1.545");
}

.t54cbcb-z {
  stop-color: var(--svg-color--bab6bd, #BAB6BD);
}

.tbe0sc-ij {
  stop-color: var(--svg-color--4a4970, #4A4970);
}

.te4zz7dbn {
  stop-color: var(--svg-color--ffe2ad, #FFE2AD);
}

.tmxi2_bfl {
  fill: var(--svg-color--ec5d25, #EC5D25);
  d: path("m17.402 23.942l-.398-1.297l2.906-1.383l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.013-.301.057-.914.125c-1.412.225-2.062-.718-2.21-1.218");
}

.u1j_tu46h {
  stop-color: var(--svg-color--d5a887, #D5A887);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ucl2tybze {
  d: path("m7.863 28.614l2.215-1.072l1.574.752l-.014 1.34a.253.253 0 0 1-.251.248l-3.855.023c-.221.001-.418-.15-.395-.37c.046-.452.333-.736.726-.921");
}

.ue_9ai6eb {
  d: path("M14.437 7.98h2.217v3.3h-2.217z");
}

.uol2-ibpf {
  stop-color: var(--svg-color--f14a2d, #F14A2D);
  stop-opacity: 0;
}

.ut2una94e {
  fill: var(--svg-color--d9a68f, #D9A68F);
  fill-rule: evenodd;
  d: path("M24.776 3.44c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.815a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.v678cdbes {
  fill: var(--svg-color--915d37, #915D37);
  fill-rule: evenodd;
  d: path("M13.638 5.222a.8.8 0 0 0-.233-.017a.16.16 0 0 1-.04-.319c.076-.01.2-.007.336.02c.136.028.297.082.437.186a.16.16 0 0 1-.191.259a.8.8 0 0 0-.31-.13");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vd52uabtv {
  fill: var(--svg-color--e1ac97, #E1AC97);
  d: path("m25.207 24.262l-4.773.703l-.329-2.547l5.215.149z");
}

.vly_b_ldb {
  stop-color: var(--svg-color--fb643e, #FB643E);
  stop-opacity: 0;
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vuvc8_ujh {
  stop-color: var(--svg-color--444367, #444367);
  stop-opacity: 0;
}

.vx88q5bse {
  stop-color: var(--svg-color--484083, #484083);
  stop-opacity: 0;
}

.w6b0chbuk {
  stop-color: var(--svg-color--dfa289, #DFA289);
}

.wcx06_c5w {
  stop-color: var(--svg-color--ca8571, #CA8571);
  stop-opacity: 0;
}

.wdglv_bwm {
  stop-color: var(--svg-color--f2b08a, #F2B08A);
}

.wwwuk1sex {
  stop-color: var(--svg-color--cf433f, #CF433F);
}

.wypfi4brd {
  d: path("M12.305 6.511c.168-.157.254-.392.277-.49h.192v1.206c-.23.147-.56.124-.657-.096c-.084-.189-.021-.423.188-.62");
}

.x3uyqiwdn {
  stop-color: var(--svg-color--d38f87, #D38F87);
}

.x9uaycblj {
  stop-color: var(--svg-color--de9d8a, #DE9D8A);
}

.xyj5utbpv {
  stop-color: var(--svg-color--ef6923, #EF6923);
}

.ycb1huo4n {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
}

.yf8z_2acj {
  stop-color: var(--svg-color--ff985a, #FF985A);
  stop-opacity: 0;
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
}

.yh8khw6sg {
  stop-color: var(--svg-color--d74b53, #D74B53);
  stop-opacity: 0;
}

.ytkho7eel {
  d: path("M16.56 4.436c.168.682.265 1.334.298 1.63c.676-.619.932-1.38.995-2.006c.053-.534-.617-.811-1.071-.525c-.328.206-.314.524-.221.901");
}

.yx3aab4wz {
  stop-color: var(--svg-color--ff8750, #FF8750);
}

.z_22iv9bb {
  d: path("m10.66 19.043l1.016-.445l1.61 2.836l-1.563.469v.422l-2.68.257c-.072-.398-.2-1.251.102-2.015c.335-.849 1.149-1.362 1.516-1.524");
}

.z-vlbvbbc {
  stop-color: var(--svg-color--fb7640, #FB7640);
}

.z6ek77bcu {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.887 7.523a.134.134 0 0 1-.002.19c-.255.25-.624.314-.742.326a.134.134 0 1 1-.027-.267c.1-.01.393-.066.582-.251a.134.134 0 0 1 .19.002");
}

.zeg5sabaz {
  d: path("m10.074 27.692l-1-5.18l2.57-.477v6.36z");
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.zm3m1tbbe {
  d: path("M13.737 6.33v-.005c0-.343-.147-.622-.329-.622c-.181 0-.328.279-.328.622v.004z");
}

.zmr2254cb {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m26.408 22.001l-1.295.558l.035 1.71c.33.29 1.104 1.066 1.808 1.603c.46.35.894.355 1.192.295c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
}

</style>
