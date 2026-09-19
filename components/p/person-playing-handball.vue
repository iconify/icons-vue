<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ikGEqzG)" class="zeg5sabaz"/><path fill="url(#iye4z5d)" class="zeg5sabaz"/><path fill="url(#idQa6lp)" class="zeg5sabaz"/><path class="g5rwapbxe"/><path fill="url(#iu4Mrab)" class="omznjsb0g"/><path fill="url(#iClNTte)" class="omznjsb0g"/><path class="is6016qki"/><path fill="url(#iQBE8ve)" class="ixpr6yotb"/><path fill="url(#iQWd7gb)" class="ixpr6yotb"/><path fill="url(#i33Bgmc)" class="ixpr6yotb"/><path fill="url(#iIYnCqe)" class="bykg3lbwp"/><path fill="url(#iwA7ufb)" class="bykg3lbwp"/><path fill="url(#iAlJh1c)" class="bykg3lbwp"/><path fill="url(#iV93hMe)" class="bykg3lbwp"/><g filter="url(#icetxHc)"><path class="o1aiahbfk"/><path fill="url(#iTAPAqc)" class="aqa5c3brz"/></g><path clip-rule="evenodd" class="i19mesu9x"/><path fill="url(#idGuQFd)" clip-rule="evenodd" class="uh23xt8gj"/><path fill="url(#iwOy7JO)" clip-rule="evenodd" class="uh23xt8gj"/><path fill="url(#iLBPHZb)" clip-rule="evenodd" class="uh23xt8gj"/><path fill="url(#ijX5G5b)" class="zkt38gbae"/><path fill="url(#iCCj7gb)" transform="rotate(-23.31 14.437 7.98)" class="ue_9ai6eb"/><g filter="url(#ikKLfzd)"><path fill="url(#iqDWCLf)" class="o4ss3bbpg"/><path fill="url(#io7zYbb)" class="o4ss3bbpg"/></g><g filter="url(#i55czKv)"><path class="o1w-6957s"/><path fill="url(#iY2MhRb)" class="hy-avb8mw"/><path fill="url(#iwF0Rfd)" class="hy-avb8mw"/><path fill="url(#iX7SShc)" class="hy-avb8mw"/><path fill="url(#i5dsvxc)" class="hy-avb8mw"/><path fill="url(#i4SvJ1b)" class="hy-avb8mw"/></g><path fill="url(#iDTKD0c)" class="op8kv6r0e"/><path clip-rule="evenodd" class="rrt-ffb3w"/><g filter="url(#ihJAyWb)"><path clip-rule="evenodd" class="jtbpmtbyn"/></g><path class="cho59lbel"/><path fill="url(#ikgDNCb)" class="cpziutftp"/><path fill="url(#i6YoOeb)" class="zci16_b_s"/><ellipse fill="url(#iHjAsmb)" transform="rotate(24.583 -7.032 33.44)skewX(-.054)" class="z4icciaal"/><path class="cpody5b_d"/><path fill="url(#iRY4q5c)" class="p0-un4b3x"/><path fill="url(#icx1oWu)" class="p0-un4b3x"/><path fill="url(#izRGg5g)" class="p0-un4b3x"/><path fill="url(#ivR1Rje)" class="p0-un4b3x"/><path fill="url(#iulsJgb)" class="p0-un4b3x"/><path fill="url(#iIqgHCZ)" class="p0-un4b3x"/><path fill="url(#iCtUvmT)" class="ucl2tybze"/><path fill="url(#ii7tcLc)" class="ucl2tybze"/><path fill="url(#i2crHgc)" class="ucl2tybze"/><path fill="url(#idK6ile)" class="ucl2tybze"/><path class="zmr2254cb"/><path fill="url(#iv8w8sQ)" class="rmfo6z_hn"/><path fill="url(#iOOGHGb)" class="rmfo6z_hn"/><path fill="url(#i1hfn1d)" class="rmfo6z_hn"/><path class="webzhi31t"/><path fill="url(#ibmgCqi)" class="im3j77blb"/><path fill="url(#iw58Cvc)" class="im3j77blb"/><path fill="url(#iHguBbc)" class="im3j77blb"/><path fill="url(#i4dgO0c)" class="im3j77blb"/><path fill="url(#itVRJ0c)" class="im3j77blb"/><g filter="url(#i6RXqwb)"><path clip-rule="evenodd" class="o3-t4o2un"/></g><path fill="url(#iGTZgZc)" clip-rule="evenodd" class="i7xbcsyur"/><path fill="url(#ivVA9Kd)" clip-rule="evenodd" class="i7xbcsyur"/><path class="px5c21brg"/><path fill="url(#iJSb4He)" class="k1q0ufiag"/><path fill="url(#iqMHZtd)" class="k1q0ufiag"/><path fill="url(#iGtG6Pe)" class="k1q0ufiag"/><rect fill="url(#igETNMw)" transform="rotate(16.21 22.95 5.358)" class="s_0d-zx_y"/><path fill="url(#ijsfepb)" class="lupv7v83w"/><path fill="url(#iQ7ZJsd)" class="ebl-bfb0u"/><path fill="url(#i6FHOkc)" class="ebl-bfb0u"/><path fill="url(#iB7Cure)" class="lxlfkhbxj"/><path fill="url(#iYr2qch)" class="lxlfkhbxj"/><path class="xqggd3_1c"/><path fill="url(#iReDsIe)" class="i7rt9jb_v"/><path fill="url(#ixnUssd)" class="i7rt9jb_v"/><path fill="url(#il1l8yb)" class="i7rt9jb_v"/><path fill="url(#iIhWSQc)" class="i7rt9jb_v"/><path fill="url(#iw75h3d)" class="i7rt9jb_v"/><g filter="url(#ihOWqZb)"><rect class="u1l9q5icd"/></g><g filter="url(#iYz0Qdb)"><rect class="veki17gcj"/></g><defs><radialGradient id="iQBE8ve" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 1.76562 -1.4243 .35293 19.387 21.763)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="q1pop7b3p"/><stop offset="1" class="hprqurbri"/></radialGradient><radialGradient id="iQWd7gb" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 19.34 22.247)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="yh8khw6sg"/><stop offset="1" class="oatqfqb0v"/></radialGradient><radialGradient id="i33Bgmc" cx="0" cy="0" r="1" gradientTransform="matrix(.60156 2.5625 -1.184 .27795 17.004 22.45)" gradientUnits="userSpaceOnUse"><stop class="k5h4lpbsq"/><stop offset="1" class="rk193sb3z"/></radialGradient><radialGradient id="iIYnCqe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 13.286 19.48)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="xyj5utbpv"/><stop offset="1" class="q0o1m355n"/></radialGradient><radialGradient id="iwA7ufb" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 11.157 8.106)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wwwuk1sex"/><stop offset="1" class="eigwz2byp"/></radialGradient><radialGradient id="iAlJh1c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.574 21.762)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="omib1tb9q"/><stop offset="1" class="z-vlbvbbc"/></radialGradient><radialGradient id="iTAPAqc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 17.074 19.75)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="idGuQFd" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.752 4.325)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="rs48o2blf"/><stop offset="1" class="kt4kpbc4c"/></radialGradient><radialGradient id="iwOy7JO" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 11.387 11.777)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="l7uszybpq"/><stop offset=".614" class="tga8kggao"/><stop offset=".952" class="ujog_hb2e"/></radialGradient><radialGradient id="iLBPHZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 11.09 11.73)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="p01fglb1l"/><stop offset="1" class="l_kbrikva"/></radialGradient><radialGradient id="ijX5G5b" cx="0" cy="0" r="1" gradientTransform="rotate(62.714 .586 13.286)scale(.72975 .92938)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="iCCj7gb" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 15.426 9.309)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bc35jgf1e"/><stop offset=".75" class="r1nhybycb"/></radialGradient><radialGradient id="io7zYbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.90438 -.05018 .0611 -1.10126 15.918 6.23)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iY2MhRb" cx="0" cy="0" r="1" gradientTransform="rotate(-45.461 17.487 -15.733)scale(2.91586 4.26131)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="iwF0Rfd" cx="0" cy="0" r="1" gradientTransform="rotate(157.286 8.586 3.726)scale(2.4692 3.46337)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iX7SShc" cx="0" cy="0" r="1" gradientTransform="matrix(-.87088 -.2509 .11655 -.40454 17.895 7.276)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="g6je8pe2z"/></radialGradient><radialGradient id="i5dsvxc" cx="0" cy="0" r="1" gradientTransform="rotate(169.664 7.99 1.928)scale(1.95776 .90288)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="t5jak8x3h"/><stop offset="1" class="hze7fms1a"/></radialGradient><radialGradient id="i4SvJ1b" cx="0" cy="0" r="1" gradientTransform="matrix(.5443 .51017 -.73674 .78603 13.071 2.3)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="an20q5kfx"/><stop offset="1" class="xh4g4qbuv"/></radialGradient><radialGradient id="iDTKD0c" cx="0" cy="0" r="1" gradientTransform="rotate(115.731 6.226 8.121)scale(1.11872 1.81928)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="ikgDNCb" cx="0" cy="0" r="1" gradientTransform="matrix(.29272 0 0 .56871 13.385 6.31)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i6YoOeb" cx="0" cy="0" r="1" gradientTransform="matrix(.26763 0 0 .57917 13.205 6.333)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iRY4q5c" cx="0" cy="0" r="1" gradientTransform="matrix(.0293 -5.32953 3.38376 .0186 15.275 17.439)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ioo6anwhf"/><stop offset="1" class="vly_b_ldb"/></radialGradient><radialGradient id="icx1oWu" cx="0" cy="0" r="1" gradientTransform="rotate(102.351 1.977 11.793)scale(5.84509 2.29049)" gradientUnits="userSpaceOnUse"><stop class="d66h0_v2y"/><stop offset="1" class="d3t9wcc9u"/></radialGradient><radialGradient id="izRGg5g" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 9.185 7.541)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="yx3aab4wz"/><stop offset="1" class="d2ptywb0c"/></radialGradient><radialGradient id="ivR1Rje" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.766 10.323)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="e_wvtt-qm"/><stop offset="1" class="f0_sezbyw"/></radialGradient><radialGradient id="iulsJgb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68752 -3.28125 6.32584 -1.32545 16.043 17.23)" gradientUnits="userSpaceOnUse"><stop class="c1n-4t3te"/><stop offset="1" class="uol2-ibpf"/></radialGradient><radialGradient id="iIqgHCZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 17.371 11.2)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="pk-0hnbkq"/><stop offset="1" class="ng31r5btx"/></radialGradient><radialGradient id="ii7tcLc" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 7.135 29.905)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="idK6ile" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.644 12.044)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="ibmgCqi" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.584 17.298)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="iw58Cvc" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.895 22.769)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iHguBbc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.633 18.093)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="itVRJ0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 14.164 17.309)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="ivVA9Kd" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 12.007 7.144)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="m3380hbjq"/><stop offset="1" class="wzizgcbzx"/></radialGradient><radialGradient id="iqMHZtd" cx="0" cy="0" r="1" gradientTransform="rotate(22.667 -17.828 43.011)scale(1.2949 2.1866)" gradientUnits="userSpaceOnUse"><stop class="hhyc553gq"/><stop offset="1" class="ss0-anvgm"/></radialGradient><radialGradient id="iGtG6Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 20.115 9.887)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gtma0og_l"/><stop offset="1" class="yf8z_2acj"/></radialGradient><radialGradient id="iReDsIe" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 12.088 .378)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ixnUssd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.938 -9.633)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="il1l8yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 21.027 4.215)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iIhWSQc" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.282 4.21)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iw75h3d" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.948 -3.794)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><linearGradient id="ikGEqzG" x1="11.824" x2="10.137" y1="26.075" y2="26.325" gradientUnits="userSpaceOnUse"><stop class="mlwsi7b0o"/><stop offset="1" class="a_09dwbav"/></linearGradient><linearGradient id="iye4z5d" x1="9.277" x2="9.996" y1="24.387" y2="24.325" gradientUnits="userSpaceOnUse"><stop class="bb6w2-xac"/><stop offset="1" class="tr-unjbvn"/></linearGradient><linearGradient id="idQa6lp" x1="11.746" x2="11.316" y1="22.676" y2="22.778" gradientUnits="userSpaceOnUse"><stop class="cqxnxcb8s"/><stop offset="1" class="w8-xerjiz"/></linearGradient><linearGradient id="iu4Mrab" x1="23.277" x2="23.16" y1="24.567" y2="23.59" gradientUnits="userSpaceOnUse"><stop class="lp2i-cd1a"/><stop offset="1" class="mtvp7bo5z"/></linearGradient><linearGradient id="iClNTte" x1="22.656" x2="22.656" y1="22.418" y2="22.801" gradientUnits="userSpaceOnUse"><stop class="qjijibc8w"/><stop offset="1" class="er4fe2jqk"/><stop offset="1" class="y6so9rbtm"/></linearGradient><linearGradient id="iV93hMe" x1="11.12" x2="11.12" y1="18.598" y2="19.918" gradientUnits="userSpaceOnUse"><stop class="f_4kl0b7z"/><stop offset="1" class="h30nofb2x"/></linearGradient><linearGradient id="iqDWCLf" x1="15.583" x2="12.515" y1="7.025" y2="7.209" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="iHjAsmb" x1="-.007" x2=".192" y1=".053" y2=".118" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iCtUvmT" x1="10.324" x2="11.855" y1="28.887" y2="28.887" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="i2crHgc" x1="9.887" x2="9.887" y1="29.905" y2="29.582" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iv8w8sQ" x1="25.813" x2="26.409" y1="22.035" y2="23.153" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="iOOGHGb" x1="26.062" x2="26.756" y1="24.985" y2="24.119" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="i1hfn1d" x1="27.776" x2="27.384" y1="24.119" y2="24.294" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="i4dgO0c" x1="13.796" x2="14.246" y1="17.365" y2="18.432" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="iGTZgZc" x1="21.824" x2="21.637" y1="10.996" y2="10.059" gradientUnits="userSpaceOnUse"><stop offset=".076" class="b-mglds6n"/><stop offset="1" class="pdikdebak"/></linearGradient><linearGradient id="iJSb4He" x1="18.667" x2="17.908" y1="12.144" y2="9.434" gradientUnits="userSpaceOnUse"><stop class="r1i9tc3bx"/><stop offset="1" class="c__hzybex"/></linearGradient><linearGradient id="igETNMw" x1="25.473" x2="23.476" y1="6.184" y2="6.254" gradientUnits="userSpaceOnUse"><stop offset=".149" class="vlsl7vjfu"/><stop offset="1" class="a6imr-icp"/></linearGradient><linearGradient id="ijsfepb" x1="5.402" x2="7.906" y1="11.387" y2="11.387" gradientUnits="userSpaceOnUse"><stop class="c3ji72h7e"/><stop offset=".78" class="f8z2jhb-c"/></linearGradient><linearGradient id="iQ7ZJsd" x1="4.785" x2="6.931" y1="11.827" y2="11.827" gradientUnits="userSpaceOnUse"><stop class="c3ji72h7e"/><stop offset=".78" class="i4zqqwbcb"/></linearGradient><linearGradient id="i6FHOkc" x1="5.614" x2="5.614" y1="12.476" y2="12.03" gradientUnits="userSpaceOnUse"><stop class="tjo7m0eif"/><stop offset="1" class="rn6fgc7ks"/></linearGradient><linearGradient id="iB7Cure" x1="5.105" x2="7.199" y1="12.426" y2="12.426" gradientUnits="userSpaceOnUse"><stop class="c3ji72h7e"/><stop offset=".78" class="qtd36y-1r"/></linearGradient><linearGradient id="iYr2qch" x1="5.855" x2="5.855" y1="13.059" y2="12.614" gradientUnits="userSpaceOnUse"><stop class="tjo7m0eif"/><stop offset="1" class="rn6fgc7ks"/></linearGradient><filter id="icetxHc" width="4.141" height="6.811" x="16.361" y="15.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23770"/></filter><filter id="ikKLfzd" width="4.748" height="5.605" x="12.315" y="3.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.533333 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23770"/></filter><filter id="i55czKv" width="5.899" height="5.876" x="12.582" y="2.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23770"/></filter><filter id="ihJAyWb" width="1.079" height=".6" x="13.124" y="4.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23770"/></filter><filter id="i6RXqwb" width="9.915" height="8.775" x="15.953" y="2.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.635294 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23770"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23770" result="effect2_innerShadow_3987_23770"/></filter><filter id="ihOWqZb" width="2.065" height=".866" x="5.024" y="11.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23770" stdDeviation=".15"/></filter><filter id="iYz0Qdb" width="2.506" height=".866" x="4.54" y="11.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23770" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-playing-handball" /></template>
<style>
.a_09dwbav {
  stop-color: var(--svg-color--ffbe38, #FFBE38);
}

.a6imr-icp {
  stop-color: var(--svg-color--ef712f, #EF712F);
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.an20q5kfx {
  stop-color: var(--svg-color--e0a531, #E0A531);
}

.aqa5c3brz {
  d: path("M17.01 22.711s-.464-1.23-.64-2.274S18.707 16 18.707 16c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.538c-.638.57-2.491.983-3.134 1.161");
}

.b-mglds6n {
  stop-color: var(--svg-color--ca7743, #CA7743);
}

.bb6w2-xac {
  stop-color: var(--svg-color--ffcd54, #FFCD54);
}

.bc_6ftbdd {
  stop-color: var(--svg-color--ddd9e2, #DDD9E2);
}

.bc35jgf1e {
  stop-color: var(--svg-color--d0801b, #D0801B);
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bykg3lbwp {
  d: path("m10.66 19.043l1.016-.445l1.61 2.836l-1.563.469v.422l-2.68.257c-.072-.398-.2-1.25.102-2.015c.335-.849 1.149-1.362 1.516-1.524");
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

.c3ji72h7e {
  stop-color: var(--svg-color--ffc52a, #FFC52A);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.cho59lbel {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.088 6.333h1.06c0-.42-.238-.759-.53-.759s-.53.34-.53.759");
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.cpody5b_d {
  fill: var(--svg-color--f76c2c, #F76C2C);
  d: path("m15.953 9.367l.674-.169c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.255l-4.897 2.074c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.cpziutftp {
  d: path("M13.736 6.333v-.004c0-.343-.147-.621-.328-.621s-.328.278-.328.62v.005z");
}

.cqxnxcb8s {
  stop-color: var(--svg-color--d39b39, #D39B39);
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

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
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

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.eigwz2byp {
  stop-color: var(--svg-color--cf433f, #CF433F);
  stop-opacity: 0;
}

.er4fe2jqk {
  stop-color: var(--svg-color--eab93e, #EAB93E);
  stop-opacity: 0;
}

.f_4kl0b7z {
  stop-color: var(--svg-color--d76322, #D76322);
}

.f0_sezbyw {
  stop-color: var(--svg-color--eb784b, #EB784B);
  stop-opacity: 0;
}

.f8z2jhb-c {
  stop-color: var(--svg-color--fbac30, #FBAC30);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.g5rwapbxe {
  fill: var(--svg-color--ffc93b, #FFC93B);
  d: path("m25.207 24.262l-4.773.703l-.329-2.547l5.215.149z");
}

.g6je8pe2z {
  stop-color: var(--svg-color--ffd237, #FFD237);
  stop-opacity: 0;
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
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

.hprqurbri {
  stop-color: var(--svg-color--ff7839, #FF7839);
  stop-opacity: 0;
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.hy-avb8mw {
  d: path("M12.707 2.965a1.1 1.1 0 0 1 1.055-.62c.921.05 1.047.369 1.88.197c.88-.181 1.315-.129 1.692.042l.007.003c.371.169 1.14.518 1.14 2.088c0 1.447-.517 2.21-.767 2.484l.05.018c.248.09.35.353.26.6c-.076.212-.344.334-.682.28c-.386-.06-.67-.112-.892-.156a.266.266 0 0 1-.213-.262V6.448c0-.502-.355-.802-.511-.89c-.017-.52-.176-.758-.436-.883c-.43-.208-.563-.105-1.59-.167c-1.035-.063-1.311-.891-.993-1.543");
}

.hze7fms1a {
  stop-color: var(--svg-color--ffbf27, #FFBF27);
  stop-opacity: 0;
}

.i19mesu9x {
  fill: var(--svg-color--ffad2f, #FFAD2F);
  fill-rule: evenodd;
  d: path("M6.495 11.643a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.406 1.382 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.375-.47-.93-.095-1.441");
}

.i4zqqwbcb {
  stop-color: var(--svg-color--ffad2f, #FFAD2F);
}

.i7rt9jb_v {
  d: path("M25.013 4.091a2.063 2.063 0 1 1-4.125 0a2.063 2.063 0 0 1 4.125 0");
}

.i7xbcsyur {
  fill-rule: evenodd;
  d: path("M24.776 3.44c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.815a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.im3j77blb {
  d: path("M18.76 15.58s-4.632 1.786-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.491-1.323-.683-1.704");
}

.ioo6anwhf {
  stop-color: var(--svg-color--fb643e, #FB643E);
}

.is6016qki {
  fill: var(--svg-color--ec5d25, #EC5D25);
  d: path("m17.402 23.942l-.398-1.297l2.906-1.383l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.014-.301.057-.914.125c-1.412.226-2.062-.718-2.21-1.218");
}

.ixpr6yotb {
  d: path("m17.402 23.942l-.398-1.297l2.906-1.383l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.014-.301.057-.914.125c-1.412.226-2.062-.718-2.21-1.218");
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

.jjj62-byh {
  stop-color: var(--svg-color--66638b, #66638B);
}

.jkk-xsb9b {
  stop-color: var(--svg-color--ffd237, #FFD237);
}

.jtbpmtbyn {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M13.637 5.227a.8.8 0 0 0-.232-.016a.16.16 0 1 1-.04-.319c.076-.01.2-.007.336.02c.136.028.297.082.437.186a.16.16 0 1 1-.191.258a.8.8 0 0 0-.31-.129");
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

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
}

.kt4kpbc4c {
  stop-color: var(--svg-color--f58d21, #F58D21);
  stop-opacity: 0;
}

.l_kbrikva {
  stop-color: var(--svg-color--dfa634, #DFA634);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l7uszybpq {
  stop-color: var(--svg-color--f99f2d, #F99F2D);
  stop-opacity: 0;
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lp2i-cd1a {
  stop-color: var(--svg-color--c67656, #C67656);
}

.lupv7v83w {
  d: path("M5.084 11.524a.44.44 0 0 1 .44-.44h1.374c.112 0 .54.008.899.147l.11.34l-.404.393H5.524a.44.44 0 0 1-.44-.44");
}

.lxlfkhbxj {
  d: path("M4.955 12.547a.44.44 0 0 1 .44-.44H6.93v.48a.4.4 0 0 1-.4.4H5.395a.44.44 0 0 1-.44-.44");
}

.m3380hbjq {
  stop-color: var(--svg-color--ffda3f, #FFDA3F);
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
  stop-opacity: 0;
}

.mge9r1s9g {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
  stop-opacity: 0;
}

.mlwsi7b0o {
  stop-color: var(--svg-color--ffd13d, #FFD13D);
}

.mtvp7bo5z {
  stop-color: var(--svg-color--f3a935, #F3A935);
  stop-opacity: 0;
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

.o1aiahbfk {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M17.01 22.711s-.464-1.23-.64-2.274S18.707 16 18.707 16c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.538c-.638.57-2.491.983-3.134 1.161");
}

.o1w-6957s {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M12.707 2.965a1.1 1.1 0 0 1 1.055-.62c.921.05 1.047.369 1.88.197c.88-.181 1.315-.129 1.692.042l.007.003c.371.169 1.14.518 1.14 2.088c0 1.447-.517 2.21-.767 2.484l.05.018c.248.09.35.353.26.6c-.076.212-.344.334-.682.28c-.386-.06-.67-.112-.892-.156a.266.266 0 0 1-.213-.262V6.448c0-.502-.355-.802-.511-.89c-.017-.52-.176-.758-.436-.883c-.43-.208-.563-.105-1.59-.167c-1.035-.063-1.311-.891-.993-1.543");
}

.o3-t4o2un {
  fill: var(--svg-color--ffc632, #FFC632);
  fill-rule: evenodd;
  d: path("M24.776 3.44c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.815a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.o4ss3bbpg {
  d: path("M12.545 5.483c.041-.858.32-1.271.45-1.392h4.001l.067 3.387c-.929 2.271-3.764 2.369-4.187 1.547s-.379-2.549-.33-3.542");
}

.oatqfqb0v {
  stop-color: var(--svg-color--d74b53, #D74B53);
}

.omib1tb9q {
  stop-color: var(--svg-color--fb7640, #FB7640);
  stop-opacity: 0;
}

.omznjsb0g {
  d: path("m25.207 24.262l-4.773.703l-.329-2.547l5.215.149z");
}

.op8kv6r0e {
  d: path("m15.515 7.04l.214-1.541a.778.778 0 0 1-.214 1.54");
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.p0-un4b3x {
  d: path("m15.953 9.367l.674-.169c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.255l-4.897 2.074c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.p01fglb1l {
  stop-color: var(--svg-color--dfa634, #DFA634);
}

.pdikdebak {
  stop-color: var(--svg-color--f8a733, #F8A733);
  stop-opacity: 0;
}

.pk-0hnbkq {
  stop-color: var(--svg-color--eb5f1d, #EB5F1D);
}

.px5c21brg {
  fill: var(--svg-color--ff832d, #FF832D);
  d: path("m20.192 11.564l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
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

.qjijibc8w {
  stop-color: var(--svg-color--eab93e, #EAB93E);
}

.qmcjcvbdo {
  stop-color: var(--svg-color--adaaad, #ADAAAD);
  stop-opacity: 0;
}

.qtd36y-1r {
  stop-color: var(--svg-color--feac30, #FEAC30);
}

.r1i9tc3bx {
  stop-color: var(--svg-color--f05c24, #F05C24);
}

.r1nhybycb {
  stop-color: var(--svg-color--fabd40, #FABD40);
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
}

.rk193sb3z {
  stop-color: var(--svg-color--e76637, #E76637);
  stop-opacity: 0;
}

.rmfo6z_hn {
  d: path("m26.408 22.001l-1.295.558l.035 1.71c.33.29 1.104 1.066 1.808 1.603c.46.35.894.355 1.192.295c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
}

.rn6fgc7ks {
  stop-color: var(--svg-color--f0a135, #F0A135);
  stop-opacity: 0;
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rrt-ffb3w {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M13.887 7.525a.134.134 0 0 1-.002.19c-.255.25-.624.313-.742.325a.134.134 0 1 1-.027-.266c.1-.01.393-.066.582-.25a.134.134 0 0 1 .189.001");
}

.rs48o2blf {
  stop-color: var(--svg-color--f58d21, #F58D21);
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

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t54cbcb-z {
  stop-color: var(--svg-color--bab6bd, #BAB6BD);
}

.t5jak8x3h {
  stop-color: var(--svg-color--e4af34, #E4AF34);
}

.tbe0sc-ij {
  stop-color: var(--svg-color--4a4970, #4A4970);
}

.tga8kggao {
  stop-color: var(--svg-color--ed9635, #ED9635);
  stop-opacity: 0.236;
}

.tjo7m0eif {
  stop-color: var(--svg-color--d88642, #D88642);
}

.tr-unjbvn {
  stop-color: var(--svg-color--ffcd54, #FFCD54);
  stop-opacity: 0;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u1l9q5icd {
  width: 1.465px;
  height: 0.266px;
  x: 5.324px;
  y: 12.239px;
  fill: var(--svg-color--ffc635, #FFC635);
  rx: 0.133px;
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

.uh23xt8gj {
  fill-rule: evenodd;
  d: path("M6.495 11.643a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.406 1.382 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.375-.47-.93-.095-1.441");
}

.ujog_hb2e {
  stop-color: var(--svg-color--c87a51, #C87A51);
}

.uol2-ibpf {
  stop-color: var(--svg-color--f14a2d, #F14A2D);
  stop-opacity: 0;
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.veki17gcj {
  width: 1.906px;
  height: 0.266px;
  x: 4.84px;
  y: 11.641px;
  fill: var(--svg-color--ffc635, #FFC635);
  rx: 0.133px;
}

.vlsl7vjfu {
  stop-color: var(--svg-color--f18021, #F18021);
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

.w8-xerjiz {
  stop-color: var(--svg-color--ffd23e, #FFD23E);
  stop-opacity: 0;
}

.webzhi31t {
  fill: var(--svg-color--918996, #918996);
  d: path("M18.76 15.58s-4.632 1.786-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.491-1.323-.683-1.704");
}

.wwwuk1sex {
  stop-color: var(--svg-color--cf433f, #CF433F);
}

.wzizgcbzx {
  stop-color: var(--svg-color--ffda3f, #FFDA3F);
  stop-opacity: 0;
}

.xh4g4qbuv {
  stop-color: var(--svg-color--e0a531, #E0A531);
  stop-opacity: 0;
}

.xqggd3_1c {
  fill: var(--svg-color--ef7c28, #EF7C28);
  d: path("M8.288 11.554a.197.197 0 0 1 .258-.09c.244.112.694.325.974.496c.084.052.107.16.06.246l-1.028 1.906a.186.186 0 0 1-.223.092a4 4 0 0 1-.974-.495a.19.19 0 0 1-.058-.247z");
}

.xyj5utbpv {
  stop-color: var(--svg-color--ef6923, #EF6923);
}

.y6so9rbtm {
  stop-color: var(--svg-color--ffc93b, #FFC93B);
  stop-opacity: 0;
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

.yx3aab4wz {
  stop-color: var(--svg-color--ff8750, #FF8750);
}

.z-vlbvbbc {
  stop-color: var(--svg-color--fb7640, #FB7640);
}

.z4icciaal {
  rx: 0.069px;
  ry: 0.094px;
}

.zci16_b_s {
  d: path("m13.527 6.333l.004-.077c0-.199-.084-.36-.188-.36s-.188.161-.188.36q0 .04.004.077z");
}

.zeg5sabaz {
  d: path("m10.074 27.692l-1-5.18l2.57-.477v6.36z");
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zkt38gbae {
  d: path("M12.305 6.515c.167-.157.254-.392.276-.49h.192V7.23c-.23.146-.559.123-.656-.096c-.084-.188-.021-.423.188-.62");
}

.zmr2254cb {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m26.408 22.001l-1.295.558l.035 1.71c.33.29 1.104 1.066 1.808 1.603c.46.35.894.355 1.192.295c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
}

</style>
