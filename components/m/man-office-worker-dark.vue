<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iOfv8Fb)" class="fpc-w8unn"/><path fill="url(#ibfv0gb)" class="fpc-w8unn"/><g filter="url(#irbRx6d)"><path class="t0sec-baz"/></g><g filter="url(#iwKYBMe)"><path class="umngd4zaj"/></g><path fill="url(#itSRADc)" class="exvucxbiq"/><path fill="url(#iSbbKnb)" class="exvucxbiq"/><path fill="url(#i1fHkvc)" class="exvucxbiq"/><path fill="url(#iE5g3gb)" class="xc6znrbjq"/><path fill="url(#i0lVWpe)" class="xc6znrbjq"/><g filter="url(#i5KZV3b)"><path fill="url(#iCo4Qkc)" class="vlp0azbmu"/><path fill="url(#iYqEHNc)" class="vlp0azbmu"/><path fill="url(#itqYW8b)" class="vlp0azbmu"/></g><path fill="url(#iL6RgQb)" class="vlp0azbmu"/><path fill="url(#ilmGz8c)" class="vlp0azbmu"/><path fill="url(#iSnmIFb)" class="vlp0azbmu"/><g filter="url(#i9Ga2ld)"><path fill="url(#iPDHuEm)" class="c6b1s1b5b"/></g><g filter="url(#iddOKff)"><path class="ge-l1eb2k"/><path fill="url(#ixVJ9ed)" class="yi0b9jgtv"/></g><path fill="url(#i07ZYOk)" class="dem1xwbda"/><path fill="url(#iVfj0Bc)" class="dem1xwbda"/><path fill="url(#iNeTQVf)" class="wqstn2bfu"/><path fill="url(#iSHNXae)" class="l3diyl3ks"/><path fill="url(#i8IKsne)" class="l3diyl3ks"/><path fill="url(#iY6QOvc)" class="l3diyl3ks"/><path fill="url(#i3KtIsd)" class="risho-b5r"/><g filter="url(#iqrKoGd)"><circle fill="url(#iv49TFd)" class="vsbmcyiza"/></g><g filter="url(#iRhb87c)"><circle fill="url(#itDhK8c)" class="b8fa5ebrd"/></g><g filter="url(#iB4JEci)"><circle fill="url(#iyMEVsd)" class="hk7pmurmp"/><circle fill="url(#iETbNxw)" class="hk7pmurmp"/></g><g filter="url(#i8ylVvC)"><circle class="njtos9b-j"/><circle fill="url(#iC6vxHb)" class="ff7a03w8s"/><circle fill="url(#isks3md)" class="ff7a03w8s"/></g><g filter="url(#iyODxKe)"><path fill="url(#isZw9sc)" class="yzxpeeb5d"/><path fill="url(#igoY3dd)" class="yzxpeeb5d"/><path fill="url(#iftyFwN)" class="yzxpeeb5d"/><path fill="url(#igso2BE)" class="yzxpeeb5d"/><path fill="url(#igp3z5d)" class="yzxpeeb5d"/><path fill="url(#iD295fe)" class="yzxpeeb5d"/></g><g filter="url(#ickQ2qd)"><path fill="url(#iZHcZBc)" class="zqt-f00lw"/></g><g filter="url(#iDtkvTc)"><path class="d6soithkm"/><path fill="url(#iIMh77s)" class="m0hcd9zwz"/><path fill="url(#iyHqjfe)" class="m0hcd9zwz"/><path fill="url(#ihGebrb)" class="m0hcd9zwz"/><path fill="url(#iVJmlGe)" class="m0hcd9zwz"/></g><g filter="url(#iB3vYJb)"><path class="m9p1_ks0w"/></g><g filter="url(#i0w0dCe)"><path class="rrvl_cb-a"/><path fill="url(#i5LciVK)" class="h5n4xbbpw"/><path fill="url(#iBSvEze)" class="h5n4xbbpw"/><path fill="url(#iNsO3Yc)" class="h5n4xbbpw"/><path fill="url(#ie4npde)" class="h5n4xbbpw"/></g><path fill="url(#iwFxCnc)" class="h5n4xbbpw"/><path stroke="url(#i5gEWBc)" class="ckgriyb0h"/><g filter="url(#izXfexb)"><path class="zj8xfjdfq"/></g><g filter="url(#iEIK8lb)"><path class="ha2pa-0kq"/></g><path class="vu3ym3l2n"/><path fill="url(#i2aAsGc)" class="g1n8c5b7p"/><path class="xp08z-shx"/><g filter="url(#ireTZPe)"><path class="hy6z68b_i"/><path fill="url(#ijCEJKe)" class="brc13vbsg"/></g><g filter="url(#i1Q6tLd)"><path fill="url(#idzn0td)" class="kp1j46bam"/></g><path class="humn_d7jk"/><path fill="url(#iptnxsw)" class="g6gt9ebiy"/><path class="f66f-hdec"/><g filter="url(#iseRnxb)"><path fill="url(#iZs02sl)" class="g2188xbhn"/></g><g filter="url(#iH1jdZZ)"><ellipse transform="rotate(-27.914 13.518 9.854)" class="zojqmrb-a"/><ellipse fill="url(#i1yQDZc)" transform="rotate(-27.914 13.518 9.854)" class="i22og5bvl"/></g><g filter="url(#ibkevHd)"><path stroke="url(#iWAgL5d)" class="hrs0ghorb"/></g><g filter="url(#iPE52se)"><path stroke="url(#iZnMUWY)" class="bixeycc4v"/></g><g filter="url(#idu6aZb)"><path stroke="url(#ipsNOdH)" class="j3koz1ble"/></g><defs><linearGradient id="iOfv8Fb" x1="16" x2="16" y1="16.279" y2="31.216" gradientUnits="userSpaceOnUse"><stop class="aj_3f3bsc"/><stop offset="1" class="wnr_hxb1w"/></linearGradient><linearGradient id="iSbbKnb" x1="18.903" x2="17.059" y1="25.279" y2="25.279" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="i1fHkvc" x1="15.591" x2="15.669" y1="17.826" y2="21.716" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="i0lVWpe" x1="23" x2="23.744" y1="29.454" y2="29.43" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="iCo4Qkc" x1="11.902" x2="11.902" y1="16.057" y2="29.957" gradientUnits="userSpaceOnUse"><stop class="f3sse8oum"/><stop offset=".524" class="u_3z34bhk"/></linearGradient><linearGradient id="iYqEHNc" x1="13.671" x2="13.05" y1="22.516" y2="22.516" gradientUnits="userSpaceOnUse"><stop class="ihv8a_ggy"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="iL6RgQb" x1="11.902" x2="12.839" y1="25.933" y2="25.532" gradientUnits="userSpaceOnUse"><stop offset=".196" class="k61ntrncu"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="iSnmIFb" x1="12.223" x2="12.434" y1="16.057" y2="16.458" gradientUnits="userSpaceOnUse"><stop class="po-lo7b_p"/><stop offset="1" class="un5vu3b4v"/></linearGradient><linearGradient id="iPDHuEm" x1="15.988" x2="15.988" y1="18.95" y2="20.935" gradientUnits="userSpaceOnUse"><stop offset=".006" class="cv8mglbzi"/><stop offset="1" class="s7ujjhbeb"/></linearGradient><linearGradient id="ixVJ9ed" x1="18.71" x2="20.111" y1="21.564" y2="21.564" gradientUnits="userSpaceOnUse"><stop offset=".093" class="d4aenlb5d"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="iNeTQVf" x1="9.452" x2="7.02" y1="23.974" y2="23.974" gradientUnits="userSpaceOnUse"><stop class="qv0c6ccxx"/><stop offset="1" class="ox2qw0bwk"/></linearGradient><linearGradient id="i8IKsne" x1="14.606" x2="14.899" y1="24.837" y2="24.876" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="iY6QOvc" x1="17.411" x2="17.012" y1="24.654" y2="24.701" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="itDhK8c" x1="11.224" x2="10.583" y1="10.911" y2="10.911" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iyMEVsd" x1="21.834" x2="21.014" y1="9.54" y2="12.079" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="isZw9sc" x1="20.016" x2="12.372" y1="11.022" y2="12.161" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="igoY3dd" x1="10.575" x2="12.842" y1="13.721" y2="13.579" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iZHcZBc" x1="16.936" x2="25.561" y1="7.641" y2="4.673" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="i5LciVK" x1="15.111" x2="16.05" y1="11.682" y2="11.682" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iBSvEze" x1="16.916" x2="15.889" y1="12.005" y2="11.99" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iNsO3Yc" x1="16.171" x2="16.171" y1="12.748" y2="12.174" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iwFxCnc" x1="16.102" x2="16.102" y1="12.79" y2="12.622" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="i5gEWBc" x1="14.938" x2="15.374" y1="14.364" y2="13.676" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="idzn0td" x1="18.936" x2="18.622" y1="10.004" y2="10.197" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZs02sl" x1="14.534" x2="14.22" y1="10.004" y2="10.197" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWAgL5d" x1="18.951" x2="18.531" y1="7.862" y2="7.003" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iZnMUWY" x1="13.642" x2="12.451" y1="7.734" y2="7.235" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ipsNOdH" x1="11.31" x2="11.31" y1="5.718" y2="7.877" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><radialGradient id="ibfv0gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.46)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="itSRADc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 23.032)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="iE5g3gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.967)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="itqYW8b" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.71 11.651)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="i1uneh2yx"/><stop offset="1" class="iw5474bga"/></radialGradient><radialGradient id="ilmGz8c" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15357 .53751 11.395 19.724)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="i07ZYOk" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.482)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="zr8leoe3h"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="iVfj0Bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.979)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="po0u5abxc"/><stop offset=".876" class="s80u955fl"/></radialGradient><radialGradient id="iSHNXae" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.982 21.38)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="ium-0_blv"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="i3KtIsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.48828 -3.72875 0 16.03 17.228)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="spf0krb0n"/><stop offset="1" class="u-xq04bhh"/></radialGradient><radialGradient id="iv49TFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.553 10.633)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iETbNxw" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.119 10.367)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iC6vxHb" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.705 11.454)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="isks3md" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.747 10.632)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iftyFwN" cx="0" cy="0" r="1" gradientTransform="scale(9.36564 6.89945)rotate(90 .08 1.593)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="ahl1t5bdh"/><stop offset="1" class="p4hakjc7i"/></radialGradient><radialGradient id="igso2BE" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.325 9.36)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="igp3z5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.762 9.326)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iD295fe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25341 -.93173 .54745 -1.9116 20.658 17.042)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iIMh77s" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 20.325 6.522)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iyHqjfe" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.681 4.76)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ihGebrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.976 2.023)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iVJmlGe" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.521 8.847)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="ie4npde" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.304 12.24)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="i2aAsGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.157 9.95)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ijCEJKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.93 10.035)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iptnxsw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.79 9.95)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1yQDZc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.757 -1.562)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="irbRx6d" width="6.556" height="14.595" x="9.212" y="15.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".5"/></filter><filter id="iwKYBMe" width="3.95" height="13.362" x="17.96" y="16.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".375"/></filter><filter id="i5KZV3b" width="2.897" height="14" x="10.503" y="16.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2095"/></filter><filter id="i9Ga2ld" width="2.965" height="2.883" x="14.509" y="18.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2095"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2095" result="effect2_innerShadow_4002_2095"/></filter><filter id="iddOKff" width="2.902" height="14.05" x="18.61" y="16.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2095"/></filter><filter id="iqrKoGd" width="3.542" height="3.342" x="9.553" y="8.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2095"/></filter><filter id="iRhb87c" width="2.992" height="2.992" x="9.728" y="9.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".25"/></filter><filter id="iB4JEci" width="3.592" height="3.592" x="19.075" y="8.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2095"/></filter><filter id="i8ylVvC" width="2.992" height="2.992" x="19.25" y="9.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".25"/></filter><filter id="iyODxKe" width="10.383" height="12.189" x="10.813" y="5.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2095"/></filter><filter id="ickQ2qd" width="6.25" height="5.07" x="15.146" y="4.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".5"/></filter><filter id="iDtkvTc" width="12.614" height="8.551" x="9.669" y="1.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2095"/></filter><filter id="iB3vYJb" width="3.262" height="4.184" x="14.106" y="9.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".375"/></filter><filter id="i0w0dCe" width="2.379" height="3.184" x="14.787" y="9.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".125"/></filter><filter id="izXfexb" width="2.982" height="1.874" x="17.16" y="6.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2095"/></filter><filter id="iEIK8lb" width="2.982" height="1.874" x="12.007" y="6.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2095"/></filter><filter id="ireTZPe" width=".787" height=".697" x="17.422" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".05"/></filter><filter id="i1Q6tLd" width=".892" height=".914" x="18.263" y="9.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".1"/></filter><filter id="iseRnxb" width=".987" height="1.041" x="13.817" y="9.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".1"/></filter><filter id="iH1jdZZ" width=".914" height=".705" x="13.062" y="9.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".05"/></filter><filter id="ibkevHd" width="2.701" height="1.281" x="17.213" y="7.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".15"/></filter><filter id="iPE52se" width="2.779" height="1.339" x="11.989" y="7.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".15"/></filter><filter id="idu6aZb" width="1.008" height="2.271" x="10.806" y="5.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2095" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-office-worker-dark" /></template>
<style>
.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ahl1t5bdh {
  stop-color: var(--svg-color--3c1d32, #3C1D32);
  stop-opacity: 0;
}

.aj_3f3bsc {
  stop-color: var(--svg-color--594e72, #594E72);
}

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b8fa5ebrd {
  cx: 11.224px;
  cy: 10.632px;
  r: 0.996px;
}

.bixeycc4v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.414 8.284c.328-.29 1.043-.594 1.929-.453");
}

.brc13vbsg {
  d: path("M18.094 9.661c.063.085-.07.189-.221.302s-.264.193-.327.108c-.064-.086.007-.246.159-.36c.15-.112.325-.135.389-.05");
}

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c6b1s1b5b {
  d: path("m16.013 18.294l-1.357 1.275a.15.15 0 0 0-.031.177l.596 1.193a.25.25 0 0 0 .224.138h1.09a.25.25 0 0 0 .224-.14l.6-1.212a.15.15 0 0 0-.032-.175z");
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
  stop-opacity: 0;
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.ckgriyb0h {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.613 13.392a2.96 2.96 0 0 0 1.363.323c.505 0 .97-.118 1.364-.323a.204.204 0 0 1 .241.04a.19.19 0 0 1 .021.241m-2.99-.28l2.949.253m-2.948-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.21.027l-.041-.027m.041.027l-.041-.027m.041.027a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.027a1.89 1.89 0 0 1-1.584.846c-.665 0-1.25-.338-1.584-.846m-.042.028l.042-.028m-.042.028l.042-.028");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cv8mglbzi {
  stop-color: var(--svg-color--5a3859, #5A3859);
}

.d4aenlb5d {
  stop-color: var(--svg-color--5a4c74, #5A4C74);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d6soithkm {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.8 4.148l.43.214c.75.374 1.18 1.228 1.02 2.135l-.591 3.043c-.053.315-.26.526-.573.534h-.018s.054-.907.107-1.441c.044-.434-.032-.566-.429-.961c-.215-.214-.376-.534-.376-.854v-.855c0-.266-.215-.48-.43-.533c-.644-.16-1.986-.427-3.919-.427s-3.275.266-3.92.427a.52.52 0 0 0-.429.533v.855c0 .32-.107.64-.376.854l-.16.16c-.215.16-.323.48-.323.747c.054.588.108 1.442.108 1.442l-.05-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.074-2.082l.43-.214a8 8 0 0 0 .804-.587l.967-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.267 1.718-.054 2.362.533l.805.801c.215.267.483.427.806.587");
}

.dem1xwbda {
  d: path("M16 15.024h-2.71v4.74c0 .31.36.49.61.29L16 18.66l2.1 1.393c.25.2.61.02.61-.29v-4.74z");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.exvucxbiq {
  d: path("M18.71 16.087h-5.42v13.89h5.42z");
}

.f3sse8oum {
  stop-color: var(--svg-color--594b78, #594B78);
}

.f66f-hdec {
  fill: var(--svg-color--000, #000);
  d: path("M14.3 10.366a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.ff7a03w8s {
  cx: 20.746px;
  cy: 10.632px;
  r: 0.996px;
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fpc-w8unn {
  d: path("M16 15.467c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

.ft2atdbel {
  stop-color: var(--svg-color--877f93, #877F93);
}

.ft5dv1b6b {
  fill: none;
}

.g1k32m_rh {
  stop-color: var(--svg-color--6d6193, #6D6193);
}

.g1n8c5b7p {
  d: path("M18.16 9.472a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.g2188xbhn {
  d: path("M14.604 10.26c0-.288-.235-.48-.298-.539l-.289.28l.178.361z");
}

.g6gt9ebiy {
  d: path("M13.788 9.472a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.ge-l1eb2k {
  fill: var(--svg-color--615990, #615990);
  d: path("m21.22 21.087l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.h5n4xbbpw {
  d: path("m15.594 10.347l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.ha2pa-0kq {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.2 7.91v-.001l.003-.002l.004-.003l.012-.01a2 2 0 0 1 .155-.108c.1-.062.241-.14.42-.21c.36-.143.873-.257 1.494-.159a.534.534 0 1 1-.166 1.055a1.77 1.77 0 0 0-.935.097a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.68-.825");
}

.hk7pmurmp {
  cx: 20.746px;
  cy: 10.633px;
  r: 1.671px;
}

.hrs0ghorb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.638 7.765c.43-.075 1.27-.054 1.852.398");
}

.humn_d7jk {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.58 9.2c-.653 0-1.205.45-1.355 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271A1.4 1.4 0 0 0 13.581 9.2");
}

.hy6z68b_i {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.094 9.661c.063.085-.07.189-.221.302s-.264.193-.327.108c-.064-.086.007-.246.159-.36c.15-.112.325-.135.389-.05");
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.i1uneh2yx {
  stop-color: var(--svg-color--4e3360, #4E3360);
}

.i22og5bvl {
  cx: 13.518px;
  cy: 9.854px;
  rx: 0.39px;
  ry: 0.197px;
}

.ihv8a_ggy {
  stop-color: var(--svg-color--553a63, #553A63);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.ium-0_blv {
  stop-color: var(--svg-color--59416d, #59416D);
}

.iw5474bga {
  stop-color: var(--svg-color--4e3360, #4E3360);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j3koz1ble {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.439 5.816v.899c-.008.149-.07.481-.258.622");
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.k61ntrncu {
  stop-color: var(--svg-color--594c7d, #594C7D);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
  stop-opacity: 0;
}

.kp1j46bam {
  d: path("M18.955 10.248a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.l3diyl3ks {
  d: path("M15.505 21.077a.25.25 0 0 0-.248.212l-1.327 8.668h4.11l-1.318-8.667a.25.25 0 0 0-.247-.213z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m0hcd9zwz {
  d: path("m20.8 4.148l.43.214c.75.374 1.18 1.228 1.02 2.135l-.591 3.043c-.053.315-.26.526-.573.534h-.018s.054-.907.107-1.441c.044-.434-.032-.566-.429-.961c-.215-.214-.376-.534-.376-.854v-.855c0-.266-.215-.48-.43-.533c-.644-.16-1.986-.427-3.919-.427s-3.275.266-3.92.427a.52.52 0 0 0-.429.533v.855c0 .32-.107.64-.376.854l-.16.16c-.215.16-.323.48-.323.747c.054.588.108 1.442.108 1.442l-.05-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.074-2.082l.43-.214a8 8 0 0 0 .804-.587l.967-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.267 1.718-.054 2.362.533l.805.801c.215.267.483.427.806.587");
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.m9p1_ks0w {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.7 10.51l-.82 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.701c-.107-.377-.283-.377-.395 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.njtos9b-j {
  cx: 20.746px;
  cy: 10.632px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
}

.ox2qw0bwk {
  stop-color: var(--svg-color--43395f, #43395F);
  stop-opacity: 0;
}

.p4hakjc7i {
  stop-color: var(--svg-color--3f1843, #3F1843);
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po-lo7b_p {
  stop-color: var(--svg-color--584360, #584360);
}

.po0u5abxc {
  stop-color: var(--svg-color--9d8392, #9D8392);
  stop-opacity: 0;
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qv0c6ccxx {
  stop-color: var(--svg-color--43395f, #43395F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r8-nbsf4i {
  stop-color: var(--svg-color--504176, #504176);
  stop-opacity: 0;
}

.r8964-bmu {
  stop-color: var(--svg-color--877f93, #877F93);
  stop-opacity: 0;
}

.risho-b5r {
  d: path("M14.045 16.857c.02.213.205.69.746 1.054c.213.144 1.213.629 1.193.62c.156-.079.807-.3 1.284-.62c.54-.363.725-.84.746-1.054l-1.985-.953z");
}

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.rrvl_cb-a {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.594 10.347l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.s7ujjhbeb {
  stop-color: var(--svg-color--463952, #463952);
}

.s80u955fl {
  stop-color: var(--svg-color--815a72, #815A72);
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.spf0krb0n {
  stop-color: var(--svg-color--331b22, #331B22);
}

.t0sec-baz {
  fill: var(--svg-color--46375f, #46375F);
  d: path("M13.419 16.816c-.513 0-1.296-.03-1.77.166l-1.38 2.724c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.343c-.26.26-.36.65-.23 1l2.912 6.5l1.587-1.116l-1.34-11.477z");
}

.u_3z34bhk {
  stop-color: var(--svg-color--5d5087, #5D5087);
}

.u-xq04bhh {
  stop-color: var(--svg-color--352121, #352121);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.umngd4zaj {
  fill: var(--svg-color--493e6a, #493E6A);
  d: path("m20.905 21.148l-1.19-.828a.23.23 0 0 1 .166-.393h.919a.252.252 0 0 0 .227-.358l-1.076-2.291a8 8 0 0 0-.646-.236h-.595v11.862l2.404-6.873a.85.85 0 0 0-.21-.883");
}

.un5vu3b4v {
  stop-color: var(--svg-color--584360, #584360);
  stop-opacity: 0;
}

.vlp0azbmu {
  d: path("M13.29 16.057h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vsbmcyiza {
  cx: 11.224px;
  cy: 10.633px;
  r: 1.671px;
}

.vu3ym3l2n {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.366 9.2c.654 0 1.206.451 1.356 1.06a.274.274 0 0 1-.268.341h-2.233a.23.23 0 0 1-.227-.272A1.4 1.4 0 0 1 18.366 9.2");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wnr_hxb1w {
  stop-color: var(--svg-color--594984, #594984);
}

.wqstn2bfu {
  d: path("M7.032 29.967H8.97V18.003a11 11 0 0 0-3.656 5.843a11 11 0 0 0-.304 2.631l.02 3.49z");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xc6znrbjq {
  d: path("M23 17.985v11.982h4v-3.5a10.98 10.98 0 0 0-4-8.482");
}

.xp08z-shx {
  fill: var(--svg-color--000, #000);
  d: path("M17.648 10.366a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.236");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yi0b9jgtv {
  d: path("m21.22 21.087l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.yzxpeeb5d {
  d: path("m10.872 10.019l.049.002s-.054-.855-.108-1.442c0-.267.108-.587.322-.747l.162-.16c.268-.214.375-.534.375-.854v-.855a.52.52 0 0 1 .43-.533c.644-.16 1.986-.428 3.92-.428c1.932 0 3.274.267 3.919.428c.215.053.43.266.43.533v.855c0 .32.16.64.375.854c.503.352.471.546.43.96c-.054.534-.108 1.442-.108 1.442h.018l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.713 0-3.052-1.235-3.213-3.006z");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zj8xfjdfq {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.7 7.91l-.002-.001l-.002-.002l-.004-.003l-.012-.01a1.4 1.4 0 0 0-.155-.108c-.1-.062-.241-.14-.42-.21a2.84 2.84 0 0 0-1.495-.159a.534.534 0 1 0 .167 1.055c.398-.062.717.01.935.097a1.5 1.5 0 0 1 .308.166a.534.534 0 0 0 .68-.825");
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zojqmrb-a {
  cx: 13.518px;
  cy: 9.854px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zqt-f00lw {
  d: path("m19.944 5.002l-3.08 1.027a1.048 1.048 0 0 0 .47 2.034l3.062-.41z");
}

.zr8leoe3h {
  stop-color: var(--svg-color--cdbed0, #CDBED0);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
