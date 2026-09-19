<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iQ4en7d)" class="zeg5sabaz"/><path fill="url(#igjydlc)" class="zeg5sabaz"/><path fill="url(#ioIGVUd)" class="zeg5sabaz"/><path class="nj5v6sb8o"/><path fill="url(#iHMBW1c)" class="omznjsb0g"/><path fill="url(#iza040b)" class="omznjsb0g"/><path class="tmxi2_bfl"/><path fill="url(#iQBE8ve)" class="fjfm5pj-o"/><path fill="url(#iQkpWAc)" class="fjfm5pj-o"/><path fill="url(#i33Bgmc)" class="fjfm5pj-o"/><path fill="url(#iIYnCqe)" class="z_22iv9bb"/><path fill="url(#iwA7ufb)" class="z_22iv9bb"/><path fill="url(#iAlJh1c)" class="z_22iv9bb"/><path fill="url(#iV93hMe)" class="z_22iv9bb"/><g filter="url(#ijc1HJU)"><path class="o1aiahbfk"/><path fill="url(#iTAPAqc)" class="aqa5c3brz"/></g><path clip-rule="evenodd" class="af2fymbrh"/><path fill="url(#iZJttdb)" clip-rule="evenodd" class="joon06atp"/><path fill="url(#iFM2Eid)" clip-rule="evenodd" class="joon06atp"/><path fill="url(#imMCmBc)" clip-rule="evenodd" class="joon06atp"/><path fill="url(#iO67GJd)" transform="rotate(-23.31 14.437 7.98)" class="ue_9ai6eb"/><path class="cpody5b_d"/><path fill="url(#iRY4q5c)" class="p0-un4b3x"/><path fill="url(#icx1oWu)" class="p0-un4b3x"/><path fill="url(#izRGg5g)" class="p0-un4b3x"/><path fill="url(#ivR1Rje)" class="p0-un4b3x"/><path fill="url(#iulsJgb)" class="p0-un4b3x"/><path fill="url(#iIqgHCZ)" class="p0-un4b3x"/><path fill="url(#iCtUvmT)" class="ucl2tybze"/><path fill="url(#ii7tcLc)" class="ucl2tybze"/><path fill="url(#i2crHgc)" class="ucl2tybze"/><path fill="url(#idK6ile)" class="ucl2tybze"/><path class="zmr2254cb"/><path fill="url(#iv8w8sQ)" class="rmfo6z_hn"/><path fill="url(#iOOGHGb)" class="rmfo6z_hn"/><path fill="url(#i1hfn1d)" class="rmfo6z_hn"/><path class="n1mxv41iz"/><path fill="url(#ibmgCqi)" class="s4ig8b3bw"/><path fill="url(#iw58Cvc)" class="s4ig8b3bw"/><path fill="url(#iHguBbc)" class="s4ig8b3bw"/><path fill="url(#i4dgO0c)" class="s4ig8b3bw"/><path fill="url(#itVRJ0c)" class="s4ig8b3bw"/><g filter="url(#iBqLomc)"><path clip-rule="evenodd" class="wpyy_5b-y"/></g><path fill="url(#iv6603b)" clip-rule="evenodd" class="i7xbcsyur"/><path fill="url(#iie2jje)" clip-rule="evenodd" class="i7xbcsyur"/><path class="px5c21brg"/><path fill="url(#iJSb4He)" class="k1q0ufiag"/><path fill="url(#iqMHZtd)" class="k1q0ufiag"/><path fill="url(#iGtG6Pe)" class="k1q0ufiag"/><rect fill="url(#i4z4qHb)" transform="rotate(16.21 22.95 5.358)" class="s_0d-zx_y"/><path fill="url(#iuVVO1c)" class="lupv7v83w"/><path fill="url(#iC7h1ue)" class="lupv7v83w"/><path fill="url(#iYvSwKc)" class="ebl-bfb0u"/><path fill="url(#iKFMYkc)" class="ebl-bfb0u"/><path fill="url(#iEDrVob)" class="lxlfkhbxj"/><path fill="url(#iw3UYXc)" class="lxlfkhbxj"/><path class="lnrju2sjx"/><path fill="url(#iReDsIe)" class="i7rt9jb_v"/><path fill="url(#ixnUssd)" class="i7rt9jb_v"/><path fill="url(#il1l8yb)" class="i7rt9jb_v"/><path fill="url(#iIhWSQc)" class="i7rt9jb_v"/><path fill="url(#iw75h3d)" class="i7rt9jb_v"/><g filter="url(#iAHGiEe)"><rect class="fpshecjqd"/></g><g filter="url(#iTzQAoe)"><rect class="xj19xpaxa"/></g><path fill="url(#iiXkRJc)" class="wypfi4brd"/><g filter="url(#ijRA8Ce)"><path fill="url(#idt2zkY)" class="zilfvl16i"/><path fill="url(#iRW0CYc)" class="zilfvl16i"/><path fill="url(#iJ4Ljoe)" class="zilfvl16i"/><path fill="url(#iqDXmNb)" class="zilfvl16i"/></g><g filter="url(#iKdErKb)"><path fill="url(#ingcIec)" class="xvvfm57dh"/><path fill="url(#ibKoxNe)" class="xvvfm57dh"/><path fill="url(#iPBmKsc)" class="xvvfm57dh"/><path fill="url(#iXaoo5b)" class="xvvfm57dh"/></g><path fill="url(#ic9Cyae)" class="d7wsnjbbs"/><path fill="url(#iHEf36b)" class="d7wsnjbbs"/><path clip-rule="evenodd" class="f2ckmgsoo"/><g filter="url(#isHFnLb)"><path clip-rule="evenodd" class="mfx4nv_uu"/></g><path class="sleni0bge"/><path fill="url(#iP7G3mb)" class="k0inlobah"/><path fill="url(#izmMCSc)" class="hqp3pz_0r"/><ellipse fill="url(#imhxlue)" transform="rotate(24.61 13.274 5.952)" class="nxpms02wt"/><g filter="url(#i45WI7b)"><path fill="url(#iRqDoSb)" class="tcg2t54au"/></g><defs><radialGradient id="iQBE8ve" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 1.76562 -1.4243 .35293 19.387 21.763)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="q1pop7b3p"/><stop offset="1" class="hprqurbri"/></radialGradient><radialGradient id="iQkpWAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 19.34 22.246)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="yh8khw6sg"/><stop offset="1" class="oatqfqb0v"/></radialGradient><radialGradient id="i33Bgmc" cx="0" cy="0" r="1" gradientTransform="matrix(.60156 2.5625 -1.184 .27795 17.004 22.45)" gradientUnits="userSpaceOnUse"><stop class="k5h4lpbsq"/><stop offset="1" class="rk193sb3z"/></radialGradient><radialGradient id="iIYnCqe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 13.286 19.48)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="xyj5utbpv"/><stop offset="1" class="q0o1m355n"/></radialGradient><radialGradient id="iwA7ufb" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 11.157 8.106)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wwwuk1sex"/><stop offset="1" class="eigwz2byp"/></radialGradient><radialGradient id="iAlJh1c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.574 21.762)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="omib1tb9q"/><stop offset="1" class="z-vlbvbbc"/></radialGradient><radialGradient id="iTAPAqc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 17.074 19.75)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iZJttdb" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.752 4.325)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="v27sfw_5y"/><stop offset="1" class="ob57ysbap"/></radialGradient><radialGradient id="iFM2Eid" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 11.387 11.777)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="a5v-ibbyp"/><stop offset=".952" class="dhzphmhhv"/></radialGradient><radialGradient id="imMCmBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 11.09 11.73)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="gioczw4ny"/><stop offset="1" class="vg-1agb5d"/></radialGradient><radialGradient id="iO67GJd" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 15.426 9.309)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="lbh256w_i"/><stop offset=".75" class="ao5r4vunm"/></radialGradient><radialGradient id="iRY4q5c" cx="0" cy="0" r="1" gradientTransform="matrix(.0293 -5.32953 3.38376 .0186 15.275 17.439)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ioo6anwhf"/><stop offset="1" class="vly_b_ldb"/></radialGradient><radialGradient id="icx1oWu" cx="0" cy="0" r="1" gradientTransform="rotate(102.351 1.977 11.793)scale(5.84509 2.29049)" gradientUnits="userSpaceOnUse"><stop class="d66h0_v2y"/><stop offset="1" class="d3t9wcc9u"/></radialGradient><radialGradient id="izRGg5g" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 9.185 7.541)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="yx3aab4wz"/><stop offset="1" class="d2ptywb0c"/></radialGradient><radialGradient id="ivR1Rje" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.766 10.323)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="e_wvtt-qm"/><stop offset="1" class="f0_sezbyw"/></radialGradient><radialGradient id="iulsJgb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68752 -3.28125 6.32584 -1.32545 16.043 17.23)" gradientUnits="userSpaceOnUse"><stop class="c1n-4t3te"/><stop offset="1" class="uol2-ibpf"/></radialGradient><radialGradient id="iIqgHCZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 17.371 11.2)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="pk-0hnbkq"/><stop offset="1" class="ng31r5btx"/></radialGradient><radialGradient id="ii7tcLc" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 7.135 29.905)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="idK6ile" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.644 12.044)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="ibmgCqi" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.584 17.298)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="iw58Cvc" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.895 22.769)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iHguBbc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.633 18.093)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="itVRJ0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 14.164 17.309)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="iie2jje" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 12.007 7.144)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="dbxn0ya4l"/><stop offset="1" class="u8e_1ft3u"/></radialGradient><radialGradient id="iqMHZtd" cx="0" cy="0" r="1" gradientTransform="rotate(22.667 -17.828 43.011)scale(1.2949 2.1866)" gradientUnits="userSpaceOnUse"><stop class="hhyc553gq"/><stop offset="1" class="ss0-anvgm"/></radialGradient><radialGradient id="iGtG6Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 20.115 9.887)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gtma0og_l"/><stop offset="1" class="yf8z_2acj"/></radialGradient><radialGradient id="iReDsIe" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 12.088 .378)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ixnUssd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.938 -9.633)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="il1l8yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 21.027 4.215)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iIhWSQc" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.282 4.21)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iw75h3d" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.948 -3.794)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><radialGradient id="iiXkRJc" cx="0" cy="0" r="1" gradientTransform="matrix(.51081 .27634 -.39007 .72103 11.993 6.98)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="iRW0CYc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.814 8.046 2.892)scale(.90579 1.10432)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="iJ4Ljoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.56032 1.50732 0 12.814 7.5)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="iqDXmNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4187 -.65297 0 13.701 6.277)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="ingcIec" cx="0" cy="0" r="1" gradientTransform="rotate(-38.984 14.854 -18.604)scale(3.3189 5.04533)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="ibKoxNe" cx="0" cy="0" r="1" gradientTransform="matrix(1.28671 -.93789 1.50888 2.07008 12.582 3.58)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="iPBmKsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56106 .1591 -.07817 -.27567 17.762 7.164)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="iXaoo5b" cx="0" cy="0" r="1" gradientTransform="matrix(.95463 -.2261 .6058 2.55783 15.686 5.573)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="ic9Cyae" cx="0" cy="0" r="1" gradientTransform="matrix(.77878 -.2261 .11035 .38011 15.678 6.1)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="iP7G3mb" cx="0" cy="0" r="1" gradientTransform="matrix(.29309 0 0 .56943 13.385 6.306)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="izmMCSc" cx="0" cy="0" r="1" gradientTransform="matrix(.26797 0 0 .5799 13.205 6.329)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iQ4en7d" x1="11.824" x2="10.137" y1="26.075" y2="26.325" gradientUnits="userSpaceOnUse"><stop class="zsdj_cc5a"/><stop offset="1" class="cu51yf-7r"/></linearGradient><linearGradient id="igjydlc" x1="9.277" x2="9.996" y1="24.387" y2="24.325" gradientUnits="userSpaceOnUse"><stop class="ibzaseb-i"/><stop offset="1" class="xojzxxboq"/></linearGradient><linearGradient id="ioIGVUd" x1="11.746" x2="11.316" y1="22.676" y2="22.778" gradientUnits="userSpaceOnUse"><stop class="ljsluudhz"/><stop offset="1" class="b7qlthb7k"/></linearGradient><linearGradient id="iHMBW1c" x1="23.277" x2="23.219" y1="24.567" y2="23.344" gradientUnits="userSpaceOnUse"><stop class="n-awbpg6m"/><stop offset="1" class="usr-62t-w"/></linearGradient><linearGradient id="iza040b" x1="22.656" x2="22.656" y1="22.418" y2="23.328" gradientUnits="userSpaceOnUse"><stop class="ebb6qj3ko"/><stop offset="1" class="jw3sj5zvz"/></linearGradient><linearGradient id="iV93hMe" x1="11.12" x2="11.12" y1="18.598" y2="19.918" gradientUnits="userSpaceOnUse"><stop class="f_4kl0b7z"/><stop offset="1" class="h30nofb2x"/></linearGradient><linearGradient id="iCtUvmT" x1="10.324" x2="11.855" y1="28.887" y2="28.887" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="i2crHgc" x1="9.887" x2="9.887" y1="29.905" y2="29.582" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iv8w8sQ" x1="25.813" x2="26.409" y1="22.035" y2="23.153" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="iOOGHGb" x1="26.062" x2="26.756" y1="24.985" y2="24.119" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="i1hfn1d" x1="27.776" x2="27.384" y1="24.119" y2="24.294" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="i4dgO0c" x1="13.796" x2="14.246" y1="17.365" y2="18.432" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="iv6603b" x1="21.824" x2="21.637" y1="10.996" y2="10.059" gradientUnits="userSpaceOnUse"><stop offset=".076" class="t12v1gxuw"/><stop offset="1" class="r0caqn-8d"/></linearGradient><linearGradient id="iJSb4He" x1="18.667" x2="17.908" y1="12.144" y2="9.434" gradientUnits="userSpaceOnUse"><stop class="r1i9tc3bx"/><stop offset="1" class="c__hzybex"/></linearGradient><linearGradient id="i4z4qHb" x1="25.473" x2="23.476" y1="6.184" y2="6.254" gradientUnits="userSpaceOnUse"><stop offset=".149" class="te-_ckclm"/><stop offset="1" class="h0a2afbtn"/></linearGradient><linearGradient id="iuVVO1c" x1="5.299" x2="8.29" y1="11.403" y2="11.403" gradientUnits="userSpaceOnUse"><stop class="oj5k1ib6q"/><stop offset=".588" class="lvlod4-sl"/></linearGradient><linearGradient id="iC7h1ue" x1="6.371" x2="6.371" y1="12.036" y2="11.591" gradientUnits="userSpaceOnUse"><stop class="li_6k3bgy"/><stop offset="1" class="dradh66ej"/></linearGradient><linearGradient id="iYvSwKc" x1="4.696" x2="7.259" y1="11.843" y2="11.843" gradientUnits="userSpaceOnUse"><stop class="oj5k1ib6q"/><stop offset=".588" class="lvlod4-sl"/></linearGradient><linearGradient id="iKFMYkc" x1="5.614" x2="5.614" y1="12.476" y2="12.03" gradientUnits="userSpaceOnUse"><stop class="li_6k3bgy"/><stop offset="1" class="dradh66ej"/></linearGradient><linearGradient id="iEDrVob" x1="5.105" x2="7.199" y1="12.426" y2="12.426" gradientUnits="userSpaceOnUse"><stop class="oj5k1ib6q"/><stop offset=".588" class="lvlod4-sl"/></linearGradient><linearGradient id="iw3UYXc" x1="5.855" x2="5.855" y1="13.059" y2="12.614" gradientUnits="userSpaceOnUse"><stop class="li_6k3bgy"/><stop offset="1" class="dradh66ej"/></linearGradient><linearGradient id="idt2zkY" x1="15.583" x2="12.515" y1="7.022" y2="7.206" gradientUnits="userSpaceOnUse"><stop class="bmcblacal"/><stop offset="1" class="d0kv1cyul"/></linearGradient><linearGradient id="iHEf36b" x1="15.64" x2="15.761" y1="6.172" y2="6.189" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="imhxlue" x1="13.198" x2="13.398" y1="5.911" y2="5.976" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iRqDoSb" x1="17.224" x2="17.7" y1="5.558" y2="2.451" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><filter id="ijc1HJU" width="4.141" height="6.811" x="16.361" y="15.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23773"/></filter><filter id="iBqLomc" width="9.915" height="8.775" x="15.953" y="2.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.121569 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23773"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.176471 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23773" result="effect2_innerShadow_3987_23773"/></filter><filter id="iAHGiEe" width="2.065" height=".799" x="5.024" y="11.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23773" stdDeviation=".15"/></filter><filter id="iTzQAoe" width="2.506" height=".866" x="4.54" y="11.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23773" stdDeviation=".15"/></filter><filter id="ijRA8Ce" width="4.748" height="5.612" x="12.315" y="3.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.172549 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23773"/></filter><filter id="iKdErKb" width="5.899" height="5.883" x="12.582" y="2.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23773"/></filter><filter id="isHFnLb" width="1.079" height=".601" x="13.124" y="4.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23773"/></filter><filter id="i45WI7b" width="2.352" height="3.646" x="16.237" y="2.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23773" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-playing-handball-dark" /></template>
<style>
.a5v-ibbyp {
  stop-color: var(--svg-color--422229, #422229);
  stop-opacity: 0;
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.af2fymbrh {
  fill: var(--svg-color--42292d, #42292D);
  fill-rule: evenodd;
  d: path("M6.495 11.643a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.406 1.381 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.375-.47-.93-.095-1.441");
}

.ao5r4vunm {
  stop-color: var(--svg-color--584a48, #584A48);
}

.aqa5c3brz {
  d: path("M17.01 22.711s-.464-1.23-.64-2.274S18.707 16 18.707 16c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.538c-.638.57-2.491.983-3.134 1.161");
}

.b7qlthb7k {
  stop-color: var(--svg-color--4c2e2e, #4C2E2E);
  stop-opacity: 0;
}

.bc_6ftbdd {
  stop-color: var(--svg-color--ddd9e2, #DDD9E2);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
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

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.cpody5b_d {
  fill: var(--svg-color--f76c2c, #F76C2C);
  d: path("m15.953 9.367l.674-.169c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.255l-4.897 2.074c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.cu51yf-7r {
  stop-color: var(--svg-color--4f3838, #4F3838);
}

.d0kv1cyul {
  stop-color: var(--svg-color--5b4542, #5B4542);
}

.d2ptywb0c {
  stop-color: var(--svg-color--ff8750, #FF8750);
  stop-opacity: 0;
}

.d3t9wcc9u {
  stop-color: var(--svg-color--ff9056, #FF9056);
  stop-opacity: 0;
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.d66h0_v2y {
  stop-color: var(--svg-color--ff9056, #FF9056);
}

.d7wsnjbbs {
  d: path("m15.515 7.037l.214-1.543a.779.779 0 0 1-.214 1.543");
}

.dbxn0ya4l {
  stop-color: var(--svg-color--5d4846, #5D4846);
}

.dhzphmhhv {
  stop-color: var(--svg-color--44263d, #44263D);
}

.dradh66ej {
  stop-color: var(--svg-color--412232, #412232);
  stop-opacity: 0;
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

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.ebb6qj3ko {
  stop-color: var(--svg-color--4c3431, #4C3431);
}

.ebl-bfb0u {
  d: path("M4.512 11.964a.44.44 0 0 1 .44-.44H6.93v.88H4.95a.44.44 0 0 1-.44-.44");
}

.eigwz2byp {
  stop-color: var(--svg-color--cf433f, #CF433F);
  stop-opacity: 0;
}

.f_4kl0b7z {
  stop-color: var(--svg-color--d76322, #D76322);
}

.f0_sezbyw {
  stop-color: var(--svg-color--eb784b, #EB784B);
  stop-opacity: 0;
}

.f2ckmgsoo {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M13.887 7.523a.134.134 0 0 1-.002.189c-.255.25-.624.315-.742.327a.134.134 0 1 1-.027-.267c.1-.01.393-.066.582-.251a.134.134 0 0 1 .189.002");
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
}

.fjfm5pj-o {
  d: path("m17.402 23.942l-.398-1.297l2.906-1.383l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.013-.301.057-.914.125c-1.412.225-2.062-.718-2.21-1.218");
}

.fpshecjqd {
  width: 1.465px;
  height: 0.199px;
  x: 5.324px;
  y: 12.239px;
  fill: var(--svg-color--574545, #574545);
  rx: 0.099px;
}

.ft5dv1b6b {
  fill: none;
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gioczw4ny {
  stop-color: var(--svg-color--3f2b28, #3F2B28);
}

.gtma0og_l {
  stop-color: var(--svg-color--ff985a, #FF985A);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h-bh2_bpf {
  stop-color: var(--svg-color--454143, #454143);
}

.h0a2afbtn {
  stop-color: var(--svg-color--c86d30, #C86D30);
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

.hqp3pz_0r {
  d: path("m13.528 6.329l.004-.078c0-.198-.085-.36-.189-.36s-.188.162-.188.36q0 .04.004.078z");
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
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

.ibzaseb-i {
  stop-color: var(--svg-color--6c5551, #6C5551);
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

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jjj62-byh {
  stop-color: var(--svg-color--66638b, #66638B);
}

.joon06atp {
  fill-rule: evenodd;
  d: path("M6.495 11.643a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.406 1.381 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.375-.47-.93-.095-1.441");
}

.jw3sj5zvz {
  stop-color: var(--svg-color--4c3431, #4C3431);
  stop-opacity: 0;
}

.k0inlobah {
  d: path("M13.737 6.33v-.005c0-.344-.147-.622-.329-.622c-.181 0-.328.278-.328.622v.004z");
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

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lbh256w_i {
  stop-color: var(--svg-color--301d1c, #301D1C);
}

.li_6k3bgy {
  stop-color: var(--svg-color--412232, #412232);
}

.ljsluudhz {
  stop-color: var(--svg-color--4c2e2e, #4C2E2E);
}

.lnrju2sjx {
  fill: var(--svg-color--c8621d, #C8621D);
  d: path("M8.288 11.554a.197.197 0 0 1 .258-.09c.244.112.694.325.974.496c.084.052.107.16.06.246l-1.028 1.907a.186.186 0 0 1-.223.09a4 4 0 0 1-.974-.494a.19.19 0 0 1-.058-.247z");
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.lupv7v83w {
  d: path("M5.084 11.524a.44.44 0 0 1 .44-.44h1.374c.112 0 .54.008.899.147l.11.34l-.404.393H5.524a.44.44 0 0 1-.44-.44");
}

.lvlod4-sl {
  stop-color: var(--svg-color--42292d, #42292D);
}

.lxlfkhbxj {
  d: path("M4.955 12.547a.44.44 0 0 1 .44-.44H6.93v.48a.4.4 0 0 1-.4.4H5.395a.44.44 0 0 1-.44-.44");
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
  stop-opacity: 0;
}

.mfx4nv_uu {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M13.637 5.222a.8.8 0 0 0-.232-.017a.16.16 0 0 1-.04-.319c.076-.01.2-.006.336.02c.136.028.297.083.437.186a.16.16 0 0 1-.191.259a.8.8 0 0 0-.31-.129");
}

.mge9r1s9g {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
  stop-opacity: 0;
}

.n-awbpg6m {
  stop-color: var(--svg-color--42273f, #42273F);
}

.n1mxv41iz {
  fill: var(--svg-color--918996, #918996);
  d: path("M18.76 15.58s-4.632 1.786-7.165 3.045a17.6 17.6 0 0 0 1.804 3.371a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.245 1.784-2.567 1.663-3.264c-.105-.604-.491-1.323-.683-1.704");
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

.nj5v6sb8o {
  fill: var(--svg-color--584444, #584444);
  d: path("m25.207 24.262l-4.773.703l-.329-2.547l5.215.149z");
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
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

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.oatqfqb0v {
  stop-color: var(--svg-color--d74b53, #D74B53);
}

.ob57ysbap {
  stop-color: var(--svg-color--443331, #443331);
  stop-opacity: 0;
}

.oj5k1ib6q {
  stop-color: var(--svg-color--594441, #594441);
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

.p0-un4b3x {
  d: path("m15.953 9.367l.674-.169c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.255l-4.897 2.074c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.pf-fc7btu {
  stop-color: var(--svg-color--454143, #454143);
  stop-opacity: 0;
}

.pk-0hnbkq {
  stop-color: var(--svg-color--eb5f1d, #EB5F1D);
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
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

.qmcjcvbdo {
  stop-color: var(--svg-color--adaaad, #ADAAAD);
  stop-opacity: 0;
}

.r0caqn-8d {
  stop-color: var(--svg-color--452931, #452931);
  stop-opacity: 0;
}

.r1i9tc3bx {
  stop-color: var(--svg-color--f05c24, #F05C24);
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

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.ss0-anvgm {
  stop-color: var(--svg-color--ff9459, #FF9459);
  stop-opacity: 0;
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t12v1gxuw {
  stop-color: var(--svg-color--3c2031, #3C2031);
}

.t54cbcb-z {
  stop-color: var(--svg-color--bab6bd, #BAB6BD);
}

.tbe0sc-ij {
  stop-color: var(--svg-color--4a4970, #4A4970);
}

.tcg2t54au {
  d: path("M16.794 4.322c.167.681.265 1.334.297 1.63c.677-.62.932-1.38.995-2.006c.054-.534-.616-.812-1.07-.526c-.329.207-.314.525-.222.902");
}

.te-_ckclm {
  stop-color: var(--svg-color--db7c25, #DB7C25);
}

.tmxi2_bfl {
  fill: var(--svg-color--ec5d25, #EC5D25);
  d: path("m17.402 23.942l-.398-1.297l2.906-1.383l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.013-.301.057-.914.125c-1.412.225-2.062-.718-2.21-1.218");
}

.u8e_1ft3u {
  stop-color: var(--svg-color--4d3432, #4D3432);
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

.usr-62t-w {
  stop-color: var(--svg-color--472b33, #472B33);
  stop-opacity: 0;
}

.uysgu56cq {
  stop-color: var(--svg-color--48302c, #48302C);
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.v23x_cgsr {
  stop-color: var(--svg-color--482c2e, #482C2E);
}

.v27sfw_5y {
  stop-color: var(--svg-color--443331, #443331);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.vg-1agb5d {
  stop-color: var(--svg-color--3f2b28, #3F2B28);
  stop-opacity: 0;
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

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.wpyy_5b-y {
  fill: var(--svg-color--493030, #493030);
  fill-rule: evenodd;
  d: path("M24.776 3.44c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.815a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.wwwuk1sex {
  stop-color: var(--svg-color--cf433f, #CF433F);
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.wypfi4brd {
  d: path("M12.305 6.511c.168-.157.254-.392.277-.49h.192v1.206c-.23.147-.56.124-.657-.096c-.084-.189-.021-.423.188-.62");
}

.xj19xpaxa {
  width: 1.906px;
  height: 0.266px;
  x: 4.84px;
  y: 11.641px;
  fill: var(--svg-color--574545, #574545);
  rx: 0.133px;
}

.xktf9pbat {
  stop-color: var(--svg-color--564c49, #564C49);
  stop-opacity: 0;
}

.xojzxxboq {
  stop-color: var(--svg-color--574241, #574241);
  stop-opacity: 0;
}

.xvvfm57dh {
  d: path("M12.707 2.956a1.1 1.1 0 0 1 1.055-.62c.921.05 1.047.37 1.88.197c.88-.181 1.315-.129 1.692.042l.007.004c.372.168 1.14.517 1.14 2.09c0 1.449-.517 2.213-.766 2.487l.049.018c.248.09.35.353.26.602c-.076.211-.344.333-.682.28c-.386-.06-.67-.113-.891-.157a.266.266 0 0 1-.214-.262V6.444c0-.502-.355-.802-.511-.892c-.017-.519-.176-.758-.436-.883c-.43-.208-.563-.105-1.59-.168c-1.035-.062-1.311-.891-.993-1.545");
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

.yh8khw6sg {
  stop-color: var(--svg-color--d74b53, #D74B53);
  stop-opacity: 0;
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

.zeg5sabaz {
  d: path("m10.074 27.692l-1-5.18l2.57-.477v6.36z");
}

.zilfvl16i {
  d: path("M12.545 5.478c.041-.859.32-1.273.45-1.394h4.001l.067 3.391c-.929 2.274-3.764 2.372-4.187 1.55c-.423-.823-.379-2.553-.33-3.547");
}

.zmr2254cb {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m26.408 22.001l-1.295.558l.035 1.71c.33.29 1.104 1.066 1.808 1.603c.46.35.894.355 1.192.295c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
}

.zsdj_cc5a {
  stop-color: var(--svg-color--523939, #523939);
}

</style>
