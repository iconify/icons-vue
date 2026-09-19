<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ifEOO7b)" class="n6x53tbfb"/><path fill="url(#iwNae0c)" class="n6x53tbfb"/><path fill="url(#i3lkqxe)" class="n6x53tbfb"/><path class="f9bidsckr"/><path fill="url(#iB9e62B)" class="pumd-vb0g"/><path fill="url(#iB8euwc)" class="pumd-vb0g"/><path class="kcofq3bdr"/><path fill="url(#ixJQrNd)" class="ls6obwb3f"/><path fill="url(#ispwxdb)" class="ls6obwb3f"/><path fill="url(#iBMPYDd)" class="ls6obwb3f"/><path fill="url(#iHTOptc)" class="gp-_mcbiu"/><path fill="url(#imvw8Md)" class="gp-_mcbiu"/><path fill="url(#iRbtMyc)" class="gp-_mcbiu"/><path fill="url(#ito9uue)" class="gp-_mcbiu"/><g filter="url(#idBSake)"><path class="g0uqdobwu"/><path fill="url(#iTsOeAc)" class="lhiym6bfa"/></g><path clip-rule="evenodd" class="kg10zybut"/><path fill="url(#icMw9nC)" clip-rule="evenodd" class="uwfnrgbqt"/><path fill="url(#il6N9hc)" clip-rule="evenodd" class="uwfnrgbqt"/><path fill="url(#ihKyGPb)" clip-rule="evenodd" class="uwfnrgbqt"/><path fill="url(#iBPFFDE)" transform="rotate(-23.31 14.437 8.418)" class="cg6ecbb4c"/><path class="ktfzhlbrc"/><path fill="url(#ibHwj1d)" class="l2g0exbec"/><path fill="url(#iHltdld)" class="l2g0exbec"/><path fill="url(#iniBXib)" class="l2g0exbec"/><path fill="url(#iUEG72b)" class="l2g0exbec"/><path fill="url(#i5ccEOd)" class="l2g0exbec"/><path fill="url(#ikGTEtb)" class="l2g0exbec"/><path fill="url(#idCNt3c)" class="twi_xei0z"/><path fill="url(#iAVXrbg)" class="twi_xei0z"/><path fill="url(#iEyV86c)" class="twi_xei0z"/><path fill="url(#ipL4qSd)" class="twi_xei0z"/><path class="gvbapgpgx"/><path fill="url(#ibBzHee)" class="n76-f1fgy"/><path fill="url(#igFuZkd)" class="n76-f1fgy"/><path fill="url(#iE9GRAc)" class="n76-f1fgy"/><path class="pex0ug43a"/><path fill="url(#iBTkXyd)" class="ibflqacpc"/><path fill="url(#iKOB0te)" class="ibflqacpc"/><path fill="url(#iQL8Zmx)" class="ibflqacpc"/><path fill="url(#iX7gYDd)" class="ibflqacpc"/><path fill="url(#iRCueze)" class="ibflqacpc"/><g filter="url(#iZfxgFd)"><path clip-rule="evenodd" class="p-0i7kbka"/></g><path fill="url(#igF1wBb)" clip-rule="evenodd" class="umlpj3f-g"/><path fill="url(#iP00Kuc)" clip-rule="evenodd" class="umlpj3f-g"/><path class="z0x37nb5u"/><path fill="url(#ixwFtnd)" class="jysduz-gu"/><path fill="url(#iyq6a2c)" class="jysduz-gu"/><path fill="url(#iJ48ZXc)" class="jysduz-gu"/><rect fill="url(#i4m0skY)" transform="rotate(16.21 22.95 5.796)" class="pe307rbdi"/><path fill="url(#ihgFO3b)" class="v34-jfxky"/><path fill="url(#iWn2tgb)" class="ti6aw22pb"/><path fill="url(#i81l0Ld)" class="ti6aw22pb"/><path fill="url(#isSXPCb)" class="cz2beybld"/><path fill="url(#i3tRQcd)" class="cz2beybld"/><path fill="url(#i3gjVHv)" class="d9u19f3ks"/><path fill="url(#iWveXyK)" class="lzvhtxsap"/><path fill="url(#iyBkqmc)" class="lzvhtxsap"/><path fill="url(#i02UTqd)" class="lzvhtxsap"/><path fill="url(#iWFf7id)" class="lzvhtxsap"/><path fill="url(#ibzJDre)" class="lzvhtxsap"/><g filter="url(#iY4apje)"><rect class="s62o9qbvj"/></g><g filter="url(#ikkGDzc)"><rect class="ilu-i2b7q"/></g><path fill="url(#iUUiAod)" class="y7vtfsbnp"/><path fill="url(#iMEx7DT)" class="y7vtfsbnp"/><g filter="url(#il3GIHd)"><path fill="url(#ik76AQM)" class="yw9dngakr"/><path fill="url(#ifAUqVs)" class="yw9dngakr"/><path fill="url(#izP61ud)" class="yw9dngakr"/><path fill="url(#iZCcGIb)" class="yw9dngakr"/></g><g filter="url(#iLvhEMb)"><path fill="url(#iqqiaGc)" class="h63a-4bst"/><path fill="url(#iahMhMd)" class="h63a-4bst"/><path fill="url(#iSFqpud)" class="h63a-4bst"/></g><path fill="url(#iGV17FD)" class="oufsskjbd"/><path fill="url(#ifu8k8d)" class="oufsskjbd"/><path fill="url(#i7maqtK)" class="oufsskjbd"/><path clip-rule="evenodd" class="aw0bosa5n"/><g filter="url(#iQwdUTb)"><path clip-rule="evenodd" class="ws924ibcn"/></g><path class="qs-myabkx"/><path fill="url(#igrfp1d)" class="s5meyqjcv"/><path fill="url(#ixNznsd)" class="a9yy663rk"/><ellipse fill="url(#i9VHVIc)" transform="rotate(24.61 13.274 6.39)" class="ft1g0gbtw"/><g filter="url(#iKf9VIc)"><path fill="url(#imeg1le)" class="t96s0ib1w"/></g><defs><radialGradient id="ixJQrNd" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 1.76562 -1.4243 .35293 19.387 22.2)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="q1pop7b3p"/><stop offset="1" class="hprqurbri"/></radialGradient><radialGradient id="ispwxdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 19.34 22.684)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="yh8khw6sg"/><stop offset="1" class="oatqfqb0v"/></radialGradient><radialGradient id="iBMPYDd" cx="0" cy="0" r="1" gradientTransform="matrix(.60156 2.5625 -1.184 .27795 17.004 22.887)" gradientUnits="userSpaceOnUse"><stop class="k5h4lpbsq"/><stop offset="1" class="rk193sb3z"/></radialGradient><radialGradient id="iHTOptc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 13.286 19.919)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="xyj5utbpv"/><stop offset="1" class="q0o1m355n"/></radialGradient><radialGradient id="imvw8Md" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 11.248 8.325)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wwwuk1sex"/><stop offset="1" class="eigwz2byp"/></radialGradient><radialGradient id="iRbtMyc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.574 22.2)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="omib1tb9q"/><stop offset="1" class="z-vlbvbbc"/></radialGradient><radialGradient id="iTsOeAc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 17.074 20.187)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="icMw9nC" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.838 4.544)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="cw_dmv8-u"/><stop offset="1" class="yo2o8qb-v"/></radialGradient><radialGradient id="il6N9hc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 11.387 12.215)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="j12jqkbuh"/><stop offset=".952" class="ihyx1abhg"/></radialGradient><radialGradient id="ihKyGPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 11.09 12.169)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="a1lnoq-qe"/><stop offset="1" class="v-83r_bol"/></radialGradient><radialGradient id="iBPFFDE" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 15.426 9.747)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="oxw2g-jck"/><stop offset=".75" class="i0vk4ibxw"/></radialGradient><radialGradient id="ibHwj1d" cx="0" cy="0" r="1" gradientTransform="matrix(.0293 -5.32953 3.38376 .0186 15.276 17.876)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ioo6anwhf"/><stop offset="1" class="vly_b_ldb"/></radialGradient><radialGradient id="iHltdld" cx="0" cy="0" r="1" gradientTransform="rotate(102.351 1.8 12.012)scale(5.84509 2.29049)" gradientUnits="userSpaceOnUse"><stop class="d66h0_v2y"/><stop offset="1" class="d3t9wcc9u"/></radialGradient><radialGradient id="iniBXib" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 9.179 7.76)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="yx3aab4wz"/><stop offset="1" class="d2ptywb0c"/></radialGradient><radialGradient id="iUEG72b" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.66 10.542)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="e_wvtt-qm"/><stop offset="1" class="f0_sezbyw"/></radialGradient><radialGradient id="i5ccEOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.68752 -3.28125 6.32584 -1.32545 16.043 17.669)" gradientUnits="userSpaceOnUse"><stop class="c1n-4t3te"/><stop offset="1" class="uol2-ibpf"/></radialGradient><radialGradient id="ikGTEtb" cx="0" cy="0" r="1" gradientTransform="rotate(-27.758 32.235 -29.333)scale(2.0129 1.58718)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="pk-0hnbkq"/><stop offset="1" class="ng31r5btx"/></radialGradient><radialGradient id="iAVXrbg" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 7.135 30.343)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="ipL4qSd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.77 12.263)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iBTkXyd" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.585 17.736)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="iKOB0te" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.895 23.207)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iQL8Zmx" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.633 18.53)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="iRCueze" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 14.164 17.747)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="iP00Kuc" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.919 7.363)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="brfm5ympt"/><stop offset="1" class="tf96tsg_a"/></radialGradient><radialGradient id="iyq6a2c" cx="0" cy="0" r="1" gradientTransform="rotate(22.667 -18.921 43.23)scale(1.2949 2.1866)" gradientUnits="userSpaceOnUse"><stop class="hhyc553gq"/><stop offset="1" class="ss0-anvgm"/></radialGradient><radialGradient id="iJ48ZXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 20.114 10.325)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gtma0og_l"/><stop offset="1" class="yf8z_2acj"/></radialGradient><radialGradient id="ihgFO3b" cx="0" cy="0" r="1" gradientTransform="matrix(3.40685 0 0 1.20429 4.883 11.841)" gradientUnits="userSpaceOnUse"><stop class="gym_2j3rc"/><stop offset=".498" class="qzpft6b_x"/></radialGradient><radialGradient id="i3gjVHv" cx="0" cy="0" r="1" gradientTransform="matrix(1 .46565 -.39135 .84043 8.25 12.802)" gradientUnits="userSpaceOnUse"><stop class="bs8v5pbps"/><stop offset="1" class="cegpmmg6d"/></radialGradient><radialGradient id="iWveXyK" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 12.112 .597)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="iyBkqmc" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 15.188 -9.414)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="i02UTqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 21.027 4.653)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iWFf7id" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.242 4.429)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="ibzJDre" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 13.064 -3.575)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><radialGradient id="iUUiAod" cx="0" cy="0" r="1" gradientTransform="matrix(.51082 .27635 -.39008 .72105 11.993 7.418)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="iMEx7DT" cx="0" cy="0" r="1" gradientTransform="matrix(-.12869 -.31248 .46896 -.19313 12.427 7.758)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="ifAUqVs" cx="0" cy="0" r="1" gradientTransform="matrix(-.9044 -.05025 .06126 -1.10266 15.918 6.664)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="izP61ud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.56045 2.16053 0 12.814 7.937)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="iZCcGIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4187 -.65299 0 13.701 6.715)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="iqqiaGc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5799 -2.08798 3.1741 3.92193 15.012 5.64)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="lbq-lsb6f"/><stop offset="1" class="g-7ivnbav"/></radialGradient><radialGradient id="iahMhMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28675 -.9379 1.50892 2.07013 12.582 4.018)" gradientUnits="userSpaceOnUse"><stop class="tue5drbtp"/><stop offset="1" class="d6crxg3sz"/></radialGradient><radialGradient id="iSFqpud" cx="0" cy="0" r="1" gradientTransform="matrix(-.56107 .1591 -.07817 -.27568 17.763 7.602)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="ja8qkqbty"/><stop offset="1" class="rxuswac8h"/></radialGradient><radialGradient id="iGV17FD" cx="0" cy="0" r="1" gradientTransform="matrix(.7788 -.2261 .11036 .38012 15.678 6.539)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="ifu8k8d" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 4.096 12.611)scale(1.28755 1.34168)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="igrfp1d" cx="0" cy="0" r="1" gradientTransform="matrix(.2931 0 0 .56944 13.385 6.744)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ixNznsd" cx="0" cy="0" r="1" gradientTransform="matrix(.26797 0 0 .57991 13.205 6.767)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="ifEOO7b" x1="11.824" x2="10.137" y1="26.512" y2="26.762" gradientUnits="userSpaceOnUse"><stop class="d3738qb8u"/><stop offset="1" class="ttypkojrk"/></linearGradient><linearGradient id="iwNae0c" x1="9.277" x2="9.996" y1="24.825" y2="24.762" gradientUnits="userSpaceOnUse"><stop class="jha-984sk"/><stop offset="1" class="strkjwbkt"/></linearGradient><linearGradient id="i3lkqxe" x1="11.746" x2="11.316" y1="23.114" y2="23.216" gradientUnits="userSpaceOnUse"><stop class="e4gncgnqd"/><stop offset="1" class="divg9r_of"/></linearGradient><linearGradient id="iB9e62B" x1="23.277" x2="23.219" y1="25.005" y2="23.782" gradientUnits="userSpaceOnUse"><stop class="il9cx6b8o"/><stop offset="1" class="cll88gg-t"/></linearGradient><linearGradient id="iB8euwc" x1="22.656" x2="22.656" y1="22.856" y2="23.766" gradientUnits="userSpaceOnUse"><stop class="cror3zfgh"/><stop offset="1" class="odrq36bum"/></linearGradient><linearGradient id="ito9uue" x1="11.12" x2="11.12" y1="19.036" y2="20.356" gradientUnits="userSpaceOnUse"><stop class="f_4kl0b7z"/><stop offset="1" class="h30nofb2x"/></linearGradient><linearGradient id="idCNt3c" x1="10.324" x2="11.855" y1="29.325" y2="29.325" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iEyV86c" x1="9.887" x2="9.887" y1="30.343" y2="30.02" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="ibBzHee" x1="25.813" x2="26.409" y1="22.473" y2="23.591" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="igFuZkd" x1="26.062" x2="26.756" y1="25.424" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="iE9GRAc" x1="27.776" x2="27.384" y1="24.557" y2="24.732" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="iX7gYDd" x1="13.796" x2="14.246" y1="17.803" y2="18.87" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="igF1wBb" x1="21.824" x2="21.637" y1="11.434" y2="10.497" gradientUnits="userSpaceOnUse"><stop offset=".076" class="t2um5owbu"/><stop offset="1" class="co5izhbpm"/></linearGradient><linearGradient id="ixwFtnd" x1="18.667" x2="17.908" y1="12.582" y2="9.872" gradientUnits="userSpaceOnUse"><stop class="r1i9tc3bx"/><stop offset="1" class="c__hzybex"/></linearGradient><linearGradient id="i4m0skY" x1="25.473" x2="23.476" y1="6.622" y2="6.692" gradientUnits="userSpaceOnUse"><stop offset=".149" class="te-_ckclm"/><stop offset="1" class="h0a2afbtn"/></linearGradient><linearGradient id="iWn2tgb" x1="4.696" x2="7.259" y1="12.281" y2="12.281" gradientUnits="userSpaceOnUse"><stop class="wxhwgwbkv"/><stop offset=".588" class="j8i1teydm"/></linearGradient><linearGradient id="i81l0Ld" x1="5.614" x2="5.614" y1="12.914" y2="12.469" gradientUnits="userSpaceOnUse"><stop class="b46w5gb0s"/><stop offset="1" class="a6qwprbav"/></linearGradient><linearGradient id="isSXPCb" x1="5.105" x2="7.199" y1="12.864" y2="12.864" gradientUnits="userSpaceOnUse"><stop class="wxhwgwbkv"/><stop offset=".588" class="j8i1teydm"/></linearGradient><linearGradient id="i3tRQcd" x1="5.855" x2="5.855" y1="13.497" y2="13.052" gradientUnits="userSpaceOnUse"><stop class="b46w5gb0s"/><stop offset="1" class="a6qwprbav"/></linearGradient><linearGradient id="ik76AQM" x1="15.584" x2="12.515" y1="7.46" y2="7.644" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="i7maqtK" x1="15.619" x2="15.778" y1="6.612" y2="6.625" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="i9VHVIc" x1="13.198" x2="13.398" y1="6.349" y2="6.414" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="imeg1le" x1="17.224" x2="17.7" y1="5.996" y2="2.889" gradientUnits="userSpaceOnUse"><stop offset=".421" class="sj3owrynx"/><stop offset="1" class="i4z7nbbdt"/></linearGradient><filter id="idBSake" width="4.141" height="6.811" x="16.361" y="16.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23779"/></filter><filter id="iZfxgFd" width="9.915" height="8.775" x="15.953" y="3.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.34902 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23779"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.435294 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23779" result="effect2_innerShadow_3987_23779"/></filter><filter id="iY4apje" width="2.065" height=".799" x="5.024" y="12.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23779" stdDeviation=".15"/></filter><filter id="ikkGDzc" width="2.506" height=".866" x="4.54" y="11.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23779" stdDeviation=".15"/></filter><filter id="il3GIHd" width="4.748" height="5.612" x="12.315" y="4.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.345098 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23779"/></filter><filter id="iLvhEMb" width="5.899" height="5.883" x="12.582" y="2.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.14902 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23779"/></filter><filter id="iQwdUTb" width="1.079" height=".601" x="13.124" y="5.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23779"/></filter><filter id="iKf9VIc" width="2.352" height="3.646" x="16.237" y="3.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23779" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-playing-handball-medium" /></template>
<style>
.a1lnoq-qe {
  stop-color: var(--svg-color--906b55, #906B55);
}

.a6qwprbav {
  stop-color: var(--svg-color--a77273, #A77273);
  stop-opacity: 0;
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.a9yy663rk {
  d: path("m13.528 6.767l.004-.078c0-.198-.085-.36-.189-.36s-.188.162-.188.36q0 .04.004.078z");
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.aw0bosa5n {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.887 7.96a.134.134 0 0 1-.002.19c-.255.25-.624.315-.742.327a.134.134 0 1 1-.027-.267c.1-.01.393-.066.582-.251a.134.134 0 0 1 .189.002");
}

.b46w5gb0s {
  stop-color: var(--svg-color--9f6177, #9F6177);
}

.bc_6ftbdd {
  stop-color: var(--svg-color--ddd9e2, #DDD9E2);
}

.brfm5ympt {
  stop-color: var(--svg-color--c09b80, #C09B80);
}

.bs8v5pbps {
  stop-color: var(--svg-color--d0662d, #D0662D);
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

.cg6ecbb4c {
  d: path("M14.437 8.418h2.217v3.3h-2.217z");
}

.cll88gg-t {
  stop-color: var(--svg-color--ac787c, #AC787C);
  stop-opacity: 0;
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.co5izhbpm {
  stop-color: var(--svg-color--a47277, #A47277);
  stop-opacity: 0;
}

.cror3zfgh {
  stop-color: var(--svg-color--a7856e, #A7856E);
}

.cw_dmv8-u {
  stop-color: var(--svg-color--92504d, #92504D);
}

.cz2beybld {
  d: path("M4.955 12.985a.44.44 0 0 1 .44-.44H6.93v.48a.4.4 0 0 1-.4.4H5.395a.44.44 0 0 1-.44-.44");
}

.d2ptywb0c {
  stop-color: var(--svg-color--ff8750, #FF8750);
  stop-opacity: 0;
}

.d3738qb8u {
  stop-color: var(--svg-color--b98b7a, #B98B7A);
}

.d3t9wcc9u {
  stop-color: var(--svg-color--ff9056, #FF9056);
  stop-opacity: 0;
}

.d66h0_v2y {
  stop-color: var(--svg-color--ff9056, #FF9056);
}

.d6crxg3sz {
  stop-color: var(--svg-color--68514d, #68514D);
  stop-opacity: 0;
}

.d9u19f3ks {
  d: path("M8.288 11.992a.197.197 0 0 1 .258-.09c.244.112.694.325.974.496c.084.052.107.16.06.246L8.553 14.55a.186.186 0 0 1-.223.092a4 4 0 0 1-.974-.495a.19.19 0 0 1-.058-.247z");
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.divg9r_of {
  stop-color: var(--svg-color--af8175, #AF8175);
  stop-opacity: 0;
}

.e_wvtt-qm {
  stop-color: var(--svg-color--eb784b, #EB784B);
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.e4gncgnqd {
  stop-color: var(--svg-color--a1736a, #A1736A);
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.eigwz2byp {
  stop-color: var(--svg-color--cf433f, #CF433F);
  stop-opacity: 0;
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.f_4kl0b7z {
  stop-color: var(--svg-color--d76322, #D76322);
}

.f0_sezbyw {
  stop-color: var(--svg-color--eb784b, #EB784B);
  stop-opacity: 0;
}

.f9bidsckr {
  fill: var(--svg-color--b68b7e, #B68B7E);
  d: path("m25.207 24.7l-4.773.703l-.329-2.547l5.215.149z");
}

.ft1g0gbtw {
  cx: 13.274px;
  cy: 6.39px;
  rx: 0.069px;
  ry: 0.094px;
}

.ft5dv1b6b {
  fill: none;
}

.g-7ivnbav {
  stop-color: var(--svg-color--583e3b, #583E3B);
}

.g0uqdobwu {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M17.01 23.15s-.464-1.232-.64-2.275c-.176-1.044 2.337-4.437 2.337-4.437c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.538c-.638.57-2.491.983-3.134 1.161");
}

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gp-_mcbiu {
  d: path("m10.66 19.481l1.016-.445l1.61 2.836l-1.563.469v.421l-2.68.258c-.072-.398-.2-1.251.102-2.015c.335-.849 1.149-1.362 1.516-1.524");
}

.gtma0og_l {
  stop-color: var(--svg-color--ff985a, #FF985A);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gvbapgpgx {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m26.408 22.44l-1.295.557l.035 1.71c.33.29 1.104 1.066 1.808 1.602c.46.35.894.356 1.192.296c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
}

.gym_2j3rc {
  stop-color: var(--svg-color--ba9379, #BA9379);
}

.h0a2afbtn {
  stop-color: var(--svg-color--c86d30, #C86D30);
}

.h30nofb2x {
  stop-color: var(--svg-color--d76322, #D76322);
  stop-opacity: 0;
}

.h63a-4bst {
  d: path("M12.707 3.394a1.1 1.1 0 0 1 1.055-.62c.921.05 1.047.37 1.88.197c.88-.181 1.315-.129 1.692.042l.007.004c.372.168 1.14.518 1.14 2.09c0 1.449-.517 2.213-.766 2.487l.049.018c.248.09.35.353.26.602c-.076.211-.344.333-.682.28c-.386-.06-.67-.113-.891-.157a.266.266 0 0 1-.214-.262V6.882c0-.502-.355-.802-.511-.892c-.017-.519-.176-.758-.436-.883c-.43-.208-.563-.105-1.59-.168c-1.035-.062-1.311-.891-.993-1.545");
}

.hhyc553gq {
  stop-color: var(--svg-color--ff9459, #FF9459);
}

.hprqurbri {
  stop-color: var(--svg-color--ff7839, #FF7839);
  stop-opacity: 0;
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.i0vk4ibxw {
  stop-color: var(--svg-color--a78770, #A78770);
}

.i4z7nbbdt {
  stop-color: var(--svg-color--644a48, #644A48);
  stop-opacity: 0;
}

.ibflqacpc {
  d: path("M18.76 16.018s-4.632 1.786-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.245 1.784-2.567 1.663-3.265c-.105-.604-.491-1.322-.683-1.703");
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.ihyx1abhg {
  stop-color: var(--svg-color--995b7a, #995B7A);
}

.il9cx6b8o {
  stop-color: var(--svg-color--985b84, #985B84);
}

.ilu-i2b7q {
  width: 1.906px;
  height: 0.266px;
  x: 4.84px;
  y: 12.079px;
  fill: var(--svg-color--b08679, #B08679);
  rx: 0.133px;
}

.ioo6anwhf {
  stop-color: var(--svg-color--fb643e, #FB643E);
}

.j12jqkbuh {
  stop-color: var(--svg-color--9d6364, #9D6364);
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

.j8i1teydm {
  stop-color: var(--svg-color--a27368, #A27368);
}

.j96xv6b5h {
  stop-color: var(--svg-color--917ea3, #917EA3);
  stop-opacity: 0;
}

.ja8qkqbty {
  stop-color: var(--svg-color--5f4745, #5F4745);
}

.jha-984sk {
  stop-color: var(--svg-color--c59685, #C59685);
}

.jjj62-byh {
  stop-color: var(--svg-color--66638b, #66638B);
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jysduz-gu {
  d: path("m20.192 12.002l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

.k5h4lpbsq {
  stop-color: var(--svg-color--e76637, #E76637);
}

.kcofq3bdr {
  fill: var(--svg-color--ec5d25, #EC5D25);
  d: path("m17.402 24.38l-.398-1.297L19.91 21.7l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.013-.301.057-.914.125c-1.412.225-2.062-.718-2.21-1.218");
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kg10zybut {
  fill: var(--svg-color--a27368, #A27368);
  fill-rule: evenodd;
  d: path("M6.495 12.08a1.15 1.15 0 0 1 1.607-.246c1.178.864 3.406 1.382 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.376-.47-.93-.095-1.441");
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.ktfzhlbrc {
  fill: var(--svg-color--f76c2c, #F76C2C);
  d: path("m15.953 9.805l.674-.169c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.254l-4.897 2.075c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l2g0exbec {
  d: path("m15.953 9.805l.674-.169c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.254l-4.897 2.075c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.l3_0v7cyw {
  stop-color: var(--svg-color--ab826c, #AB826C);
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lbq-lsb6f {
  stop-color: var(--svg-color--503339, #503339);
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.lhiym6bfa {
  d: path("M17.01 23.15s-.464-1.232-.64-2.275c-.176-1.044 2.337-4.437 2.337-4.437c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.538c-.638.57-2.491.983-3.134 1.161");
}

.ls6obwb3f {
  d: path("m17.402 24.38l-.398-1.297L19.91 21.7l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.013-.301.057-.914.125c-1.412.225-2.062-.718-2.21-1.218");
}

.lzvhtxsap {
  d: path("M25.013 4.53a2.063 2.063 0 1 1-4.125-.001a2.063 2.063 0 0 1 4.125 0");
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
  stop-opacity: 0;
}

.mge9r1s9g {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
  stop-opacity: 0;
}

.n6x53tbfb {
  d: path("m10.074 28.13l-1-5.18l2.57-.477v6.36z");
}

.n76-f1fgy {
  d: path("m26.408 22.44l-1.295.557l.035 1.71c.33.29 1.104 1.066 1.808 1.602c.46.35.894.356 1.192.296c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
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

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.ng31r5btx {
  stop-color: var(--svg-color--eb5f1d, #EB5F1D);
  stop-opacity: 0;
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.oatqfqb0v {
  stop-color: var(--svg-color--d74b53, #D74B53);
}

.odrq36bum {
  stop-color: var(--svg-color--a7856e, #A7856E);
  stop-opacity: 0;
}

.omib1tb9q {
  stop-color: var(--svg-color--fb7640, #FB7640);
  stop-opacity: 0;
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.oufsskjbd {
  d: path("m15.515 7.475l.214-1.543a.779.779 0 0 1-.214 1.543");
}

.oxw2g-jck {
  stop-color: var(--svg-color--7a4e3a, #7A4E3A);
}

.p-0i7kbka {
  fill: var(--svg-color--a8816c, #A8816C);
  fill-rule: evenodd;
  d: path("M24.776 3.878c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.814a1.15 1.15 0 1 1-.435-2.258l4.232-.815a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.pe307rbdi {
  width: 2.533px;
  height: 1.362px;
  x: 22.95px;
  y: 5.796px;
  rx: 0.2px;
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.pex0ug43a {
  fill: var(--svg-color--918996, #918996);
  d: path("M18.76 16.018s-4.632 1.786-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.245 1.784-2.567 1.663-3.265c-.105-.604-.491-1.322-.683-1.703");
}

.pk-0hnbkq {
  stop-color: var(--svg-color--eb5f1d, #EB5F1D);
}

.pumd-vb0g {
  d: path("m25.207 24.7l-4.773.703l-.329-2.547l5.215.149z");
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

.q8c7r9fut {
  stop-color: var(--svg-color--4a4970, #4A4970);
  stop-opacity: 0;
}

.qh9tdvimg {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
}

.qmcjcvbdo {
  stop-color: var(--svg-color--adaaad, #ADAAAD);
  stop-opacity: 0;
}

.qs-myabkx {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.088 6.767h1.06c0-.42-.238-.76-.53-.76s-.53.34-.53.76");
}

.qzpft6b_x {
  stop-color: var(--svg-color--9d7163, #9D7163);
}

.r1i9tc3bx {
  stop-color: var(--svg-color--f05c24, #F05C24);
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.rk193sb3z {
  stop-color: var(--svg-color--e76637, #E76637);
  stop-opacity: 0;
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.rxuswac8h {
  stop-color: var(--svg-color--5f4745, #5F4745);
  stop-opacity: 0;
}

.s-7nhybnh {
  stop-color: var(--svg-color--a5a3a3, #A5A3A3);
}

.s5meyqjcv {
  d: path("M13.737 6.767v-.004c0-.344-.147-.622-.329-.622c-.181 0-.328.278-.328.622v.004z");
}

.s62o9qbvj {
  width: 1.465px;
  height: 0.199px;
  x: 5.324px;
  y: 12.677px;
  fill: var(--svg-color--b08679, #B08679);
  rx: 0.099px;
}

.sew1y7bbn {
  stop-color: var(--svg-color--514d8b, #514D8B);
  stop-opacity: 0;
}

.sj3owrynx {
  stop-color: var(--svg-color--644a48, #644A48);
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.ss0-anvgm {
  stop-color: var(--svg-color--ff9459, #FF9459);
  stop-opacity: 0;
}

.strkjwbkt {
  stop-color: var(--svg-color--af7f77, #AF7F77);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t2um5owbu {
  stop-color: var(--svg-color--935878, #935878);
}

.t54cbcb-z {
  stop-color: var(--svg-color--bab6bd, #BAB6BD);
}

.t96s0ib1w {
  d: path("M16.794 4.76c.167.681.265 1.334.297 1.63c.677-.62.932-1.38.995-2.006c.054-.534-.616-.812-1.07-.526c-.329.207-.314.525-.222.902");
}

.tbe0sc-ij {
  stop-color: var(--svg-color--4a4970, #4A4970);
}

.te-_ckclm {
  stop-color: var(--svg-color--db7c25, #DB7C25);
}

.tf96tsg_a {
  stop-color: var(--svg-color--b48a76, #B48A76);
  stop-opacity: 0;
}

.ti6aw22pb {
  d: path("M4.512 12.402a.44.44 0 0 1 .44-.44H6.93v.88H4.95a.44.44 0 0 1-.44-.44");
}

.ttypkojrk {
  stop-color: var(--svg-color--b07d78, #B07D78);
}

.tue5drbtp {
  stop-color: var(--svg-color--68514d, #68514D);
}

.twi_xei0z {
  d: path("m7.863 29.052l2.215-1.072l1.574.752l-.014 1.34a.253.253 0 0 1-.251.248l-3.855.023c-.221.001-.418-.15-.395-.37c.046-.452.333-.736.726-.921");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.umlpj3f-g {
  fill-rule: evenodd;
  d: path("M24.776 3.878c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.814a1.15 1.15 0 1 1-.435-2.258l4.232-.815a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.uol2-ibpf {
  stop-color: var(--svg-color--f14a2d, #F14A2D);
  stop-opacity: 0;
}

.uwfnrgbqt {
  fill-rule: evenodd;
  d: path("M6.495 12.08a1.15 1.15 0 0 1 1.607-.246c1.178.864 3.406 1.382 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.376-.47-.93-.095-1.441");
}

.v-83r_bol {
  stop-color: var(--svg-color--906b55, #906B55);
  stop-opacity: 0;
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.v34-jfxky {
  d: path("M5.084 11.962a.44.44 0 0 1 .44-.44h1.374c.112 0 .54.008.899.147l.11.34l-.404.393H5.524a.44.44 0 0 1-.44-.44");
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vly_b_ldb {
  stop-color: var(--svg-color--fb643e, #FB643E);
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

.ws924ibcn {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M13.637 5.66a.8.8 0 0 0-.232-.017a.16.16 0 0 1-.04-.319c.076-.01.2-.007.336.02c.136.028.297.082.437.186a.16.16 0 0 1-.191.259a.8.8 0 0 0-.31-.13");
}

.wwwuk1sex {
  stop-color: var(--svg-color--cf433f, #CF433F);
}

.wxhwgwbkv {
  stop-color: var(--svg-color--bf9482, #BF9482);
}

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
}

.xyj5utbpv {
  stop-color: var(--svg-color--ef6923, #EF6923);
}

.y7vtfsbnp {
  d: path("M12.305 6.95c.168-.158.254-.393.277-.49h.192v1.205c-.23.147-.56.124-.657-.096c-.084-.189-.021-.423.188-.62");
}

.ycb1huo4n {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
}

.yf8z_2acj {
  stop-color: var(--svg-color--ff985a, #FF985A);
  stop-opacity: 0;
}

.yh8khw6sg {
  stop-color: var(--svg-color--d74b53, #D74B53);
  stop-opacity: 0;
}

.yo2o8qb-v {
  stop-color: var(--svg-color--92504d, #92504D);
  stop-opacity: 0;
}

.yw9dngakr {
  d: path("M12.545 5.916c.041-.859.32-1.273.45-1.394h4.001l.067 3.391c-.929 2.275-3.764 2.372-4.187 1.55c-.423-.823-.379-2.553-.33-3.547");
}

.yx3aab4wz {
  stop-color: var(--svg-color--ff8750, #FF8750);
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.z-vlbvbbc {
  stop-color: var(--svg-color--fb7640, #FB7640);
}

.z0x37nb5u {
  fill: var(--svg-color--ff832d, #FF832D);
  d: path("m20.192 12.002l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

</style>
