<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i7CEWxc)" class="zbu6axbaw"/><g filter="url(#iiNq7Me)"><path fill="url(#iG0LFJc)" class="jym7wkbau"/><path fill="url(#i5O75je)" class="jym7wkbau"/></g><path fill="url(#i7Xt5pb)" class="r0j763b4n"/><g filter="url(#iD8XcqB)"><path fill="url(#i0F9odi)" class="fpvu-0bdf"/></g><path fill="url(#izESdue)" class="ditqpozrw"/><path fill="url(#ia5pCpe)" class="ditqpozrw"/><path fill="url(#iOG36An)" class="ditqpozrw"/><path fill="url(#iA55OUb)" class="ditqpozrw"/><path fill="url(#i0rKHCb)" class="ditqpozrw"/><path fill="url(#iT6C8Wb)" class="ditqpozrw"/><path fill="url(#iJpKRtd)" class="ditqpozrw"/><path fill="url(#ikoijAe)" class="ditqpozrw"/><path fill="url(#iTngBAY)" class="cjushcbdo"/><path fill="url(#iCLZE9t)" class="cjushcbdo"/><path fill="url(#iA7EGcd)" class="pogxiw08n"/><path fill="url(#iu5o3Ec)" class="pogxiw08n"/><path fill="url(#iH21wAd)" class="pogxiw08n"/><path fill="url(#ibpF4pc)" class="xo0xxmoup"/><path fill="url(#i7vLzOc)" class="xo0xxmoup"/><path fill="url(#i0DeLEe)" class="xo0xxmoup"/><g filter="url(#ifNc8db)"><path class="kck72bb7a"/></g><g filter="url(#iDIgsOS)"><path class="bhqibir3b"/></g><path class="qz8mrpbia"/><g filter="url(#iuAV54d)"><path class="quxm6bems"/></g><g filter="url(#iqaQOVb)"><path fill="url(#in7t1cc)" class="ev3jkwgwv"/><path fill="url(#ignwU0c)" class="ev3jkwgwv"/><path fill="url(#ijhys4b)" class="ev3jkwgwv"/></g><g filter="url(#imalsbd)"><path fill="url(#i3ewByb)" class="yrzxb9b5h"/></g><g filter="url(#i5Ma7pU)"><path fill="url(#iqqEJxe)" class="roo9_2b8i"/></g><path fill="url(#iIQBeIb)" class="roo9_2b8i"/><path fill="url(#iWMMXke)" class="roo9_2b8i"/><path fill="url(#iJM9zdb)" class="roo9_2b8i"/><path fill="url(#iUZoBie)" class="roo9_2b8i"/><path fill="url(#iYnQaud)" class="roo9_2b8i"/><path fill="url(#iVPDeBe)" class="roo9_2b8i"/><path class="o9bbdk3je"/><path fill="url(#i3uXAWd)" class="vswxs9bpn"/><path fill="url(#itCkCVU)" class="vswxs9bpn"/><path fill="url(#iolaAqe)" class="vswxs9bpn"/><path fill="url(#iVtk4qe)" class="mmdfzdm0x"/><path fill="url(#iNyO5Zb)" class="mmdfzdm0x"/><path fill="url(#ipZ9T9d)" class="mmdfzdm0x"/><path fill="url(#iVVzW5c)" class="xc8nhibmz"/><path fill="url(#iLmvcUc)" class="xc8nhibmz"/><g filter="url(#iGMzFoT)"><path stroke="url(#igoaSqd)" class="ee2oaqb4r"/></g><path class="x25i7gb0d"/><path fill="url(#iKeTB2W)" class="wuihzi_9f"/><path fill="url(#iqRluYn)" class="zdoa0yq9l"/><g filter="url(#iPGoOvd)"><path fill="url(#iYz2ucd)" class="tzvl-yazp"/><path fill="url(#iFud50b)" class="tzvl-yazp"/></g><g filter="url(#iSG1P6N)"><path fill="url(#iazHyBb)" class="el6sdrb2c"/><path fill="url(#iPjgnPc)" class="el6sdrb2c"/></g><path clip-rule="evenodd" class="al3hsxb7i"/><path fill="url(#isQUMsb)" clip-rule="evenodd" class="fxbsjml4i"/><path clip-rule="evenodd" class="vkj9-gbgg"/><path fill="url(#iv2iGXc)" clip-rule="evenodd" class="oxgh8sb0d"/><path fill="url(#iG9SZHd)" clip-rule="evenodd" class="oh_kewb0f"/><path clip-rule="evenodd" class="up3z98m5n"/><path fill="url(#iAHFyRm)" clip-rule="evenodd" class="m2dsk_bhk"/><g filter="url(#iXLNMCe)"><path class="bt_wr5bpp"/></g><path fill="url(#iMOj39c)" class="c1mh3mgls"/><path fill="url(#i5Kog1r)" class="c1mh3mgls"/><path fill="url(#ikKCdmc)" class="c1mh3mgls"/><path fill="url(#iCttNEd)" class="c1mh3mgls"/><g filter="url(#iH1pt6b)"><path stroke="url(#iqe5GYc)" class="t3ctwsx-f"/></g><g filter="url(#i4VhNqb)"><path stroke="url(#il1IJwe)" class="fzg1bwbxm"/></g><g filter="url(#iAaSEKd)"><path stroke="url(#iHpLoPe)" class="wa6qzac-e"/></g><g filter="url(#iWzOese)"><path class="gyjispkmu"/></g><g filter="url(#itqpojc)"><path class="mdkt7kbno"/><path fill="url(#iaJAwve)" class="yg9akk17m"/><path fill="url(#i8yBOfX)" class="yg9akk17m"/><path fill="url(#iUIMDmc)" class="yg9akk17m"/><path fill="url(#iA8J6qe)" class="yg9akk17m"/><path fill="url(#iXm5X1X)" class="yg9akk17m"/></g><path class="mi551g4xt"/><path fill="url(#iSoxgbC)" class="bf9linbqu"/><path class="s90difbur"/><g filter="url(#ipH0vRq)"><path class="wuxtngbmf"/><path fill="url(#iI09Pie)" class="a_z7xslor"/></g><g filter="url(#it51pJe)"><path fill="url(#ifG3quc)" class="gzag6vibp"/></g><path class="lsa_f9bow"/><path fill="url(#iR6r5Ec)" class="g4nd-rv6p"/><path class="pa4puzbvc"/><g filter="url(#iif9p7b)"><path fill="url(#i9nNcWc)" class="qv-_izbdm"/></g><g filter="url(#i1hzJTB)"><ellipse transform="rotate(-27.914 13.508 9.074)" class="lup0rknnc"/><ellipse fill="url(#iurvIzd)" transform="rotate(-27.914 13.508 9.074)" class="jh5w8ibpn"/></g><defs><radialGradient id="i7CEWxc" cx="0" cy="0" r="1" gradientTransform="matrix(3.93792 -7.29125 14.315 7.73138 20.554 15.864)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="1" class="gdsiwyiyr"/></radialGradient><radialGradient id="iG0LFJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.92122 7.06151 -2.22108 -.91882 27.573 11.34)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="jpxim8b1x"/><stop offset="1" class="n52c8qgao"/></radialGradient><radialGradient id="i5O75je" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 4.15626 -.42744 -.1607 27.323 11.808)" gradientUnits="userSpaceOnUse"><stop class="fg6i_oqme"/><stop offset="1" class="ih2ibv29b"/></radialGradient><radialGradient id="i7Xt5pb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.58397 -6.61442 12.98618 -8.99977 12.493 16.141)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="0" class="pxp9rxlhv"/><stop offset="1" class="e06hnni3m"/></radialGradient><radialGradient id="ia5pCpe" cx="0" cy="0" r="1" gradientTransform="rotate(-118.874 16.258 8.035)scale(12.4902 33.343)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="f6lcb9bkn"/><stop offset="1" class="jtbt9y0gz"/></radialGradient><radialGradient id="iOG36An" cx="0" cy="0" r="1" gradientTransform="rotate(-65.133 28.53 1.162)scale(12.2618 28.8332)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="r21k1wzrc"/><stop offset="1" class="b2cn2_uce"/></radialGradient><radialGradient id="iA55OUb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.71875 0 0 -14.5625 23.292 22.433)" gradientUnits="userSpaceOnUse"><stop class="odfe47amh"/><stop offset="1" class="carxtabzu"/></radialGradient><radialGradient id="i0rKHCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.6875 -.22656 0 19.206 15.84)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="z8m-hreok"/><stop offset="1" class="ehu1o5vid"/></radialGradient><radialGradient id="iT6C8Wb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15623 3.5 -5.72433 -1.89104 12.667 15.465)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="a75cnrb-k"/><stop offset="1" class="ri_i1lblj"/></radialGradient><radialGradient id="iTngBAY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.6045 2.48458 0 23.855 29.058)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="vbb18ixfb"/><stop offset="1" class="p5bq_2b9f"/></radialGradient><radialGradient id="iCLZE9t" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.5781 .52466 0 23.11 29.058)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="l0d7sccpf"/><stop offset="1" class="r3f5xvbmj"/></radialGradient><radialGradient id="iA7EGcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.2188 2.95614 0 7.292 29.058)" gradientUnits="userSpaceOnUse"><stop class="oj4dw6cda"/><stop offset="1" class="jsbpdr4yj"/></radialGradient><radialGradient id="iu5o3Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-4.21875 0 0 -14.5625 8.542 28.59)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="ihp7x-bon"/><stop offset="1" class="g_z46f3jl"/></radialGradient><radialGradient id="in7t1cc" cx="0" cy="0" r="1" gradientTransform="rotate(57.496 -6.472 21.392)scale(4.18715 6.17567)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="xksrntfob"/><stop offset="1" class="pu1_ubb-e"/></radialGradient><radialGradient id="ignwU0c" cx="0" cy="0" r="1" gradientTransform="matrix(.37499 3.375 -7.05108 .78343 14.729 13.464)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="jzwike70j"/><stop offset="1" class="gbck5ebgo"/></radialGradient><radialGradient id="ijhys4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87568 -2.6343 0 15.948 15.496)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="uxwciubxp"/><stop offset="1" class="kqp3z9b3n"/></radialGradient><radialGradient id="iqqEJxe" cx="0" cy="0" r="1" gradientTransform="rotate(153.796 8.668 6.669)scale(6.65243 6.56876)" gradientUnits="userSpaceOnUse"><stop class="g-7ivnbav"/><stop offset="1" class="b94-l-y5w"/></radialGradient><radialGradient id="iIQBeIb" cx="0" cy="0" r="1" gradientTransform="matrix(5.26564 -5.10936 1.36318 1.40487 11.313 5.246)" gradientUnits="userSpaceOnUse"><stop class="u971fdczb"/><stop offset="1" class="hjlrz39ai"/></radialGradient><radialGradient id="iWMMXke" cx="0" cy="0" r="1" gradientTransform="matrix(2.99475 -2.09375 1.42285 2.03514 18.172 4.855)" gradientUnits="userSpaceOnUse"><stop class="s4ff5rbng"/><stop offset="1" class="mqv57bcbp"/></radialGradient><radialGradient id="iJM9zdb" cx="0" cy="0" r="1" gradientTransform="matrix(4.28125 -6.34375 6.55435 4.42338 15.328 10.387)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="oipnm6glf"/><stop offset=".946" class="e7f-98b7z"/></radialGradient><radialGradient id="iUZoBie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.10937 6.74738 0 15.944 16.183)" gradientUnits="userSpaceOnUse"><stop class="uwsxe-bjv"/><stop offset="1" class="coremvbkz"/></radialGradient><radialGradient id="iYnQaud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40625 1.52344 0 18.484 8.605)" gradientUnits="userSpaceOnUse"><stop class="ky2i9gfwu"/><stop offset=".994" class="rjxs4hg5m"/></radialGradient><radialGradient id="iVPDeBe" cx="0" cy="0" r="1" gradientTransform="rotate(-119.055 9.502 .312)scale(1.52826 1.68465)" gradientUnits="userSpaceOnUse"><stop class="zdwvyrbqc"/><stop offset=".996" class="x8ix_1b_c"/></radialGradient><radialGradient id="i3uXAWd" cx="0" cy="0" r="1" gradientTransform="rotate(135.269 9.83 5.832)scale(4.70673 6.16305)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="glx9rn1kk"/><stop offset="1" class="st-pambja"/></radialGradient><radialGradient id="itCkCVU" cx="0" cy="0" r="1" gradientTransform="rotate(-139.028 6.434 .62)scale(3.14556 5.45202)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="n_d3gr2_k"/><stop offset="1" class="st-pambja"/></radialGradient><radialGradient id="iolaAqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.24277 -3.79959 0 15.935 1.16)" gradientUnits="userSpaceOnUse"><stop class="y465w_bjd"/><stop offset="1" class="d6o1i3elf"/></radialGradient><radialGradient id="iNyO5Zb" cx="0" cy="0" r="1" gradientTransform="rotate(132.451 10.277 8.563)scale(2.50015 .55787)" gradientUnits="userSpaceOnUse"><stop class="ko44f1ecp"/><stop offset="1" class="i1u0xeg2c"/></radialGradient><radialGradient id="iLmvcUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29688 .47656 -2.49611 -1.55496 10.48 7.488)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="vx8dsgrfz"/><stop offset="1" class="sfkkzgbur"/></radialGradient><radialGradient id="iYz2ucd" cx="0" cy="0" r="1" gradientTransform="matrix(1.59772 -1.40625 .5978 .67918 20.98 9.433)" gradientUnits="userSpaceOnUse"><stop class="tt0m3dw5o"/><stop offset="1" class="iwate57pq"/></radialGradient><radialGradient id="iFud50b" cx="0" cy="0" r="1" gradientTransform="matrix(.771 .03125 -.09929 2.44952 20.839 9.433)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="lymk7up5q"/><stop offset="1" class="udqi13bwa"/></radialGradient><radialGradient id="iazHyBb" cx="0" cy="0" r="1" gradientTransform="rotate(-132.082 7.543 2.277)scale(2.41247 2.17677)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="rlrkc3tlk"/><stop offset="1" class="hy1_v56-b"/></radialGradient><radialGradient id="iPjgnPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18123 .63382 -1.16713 -2.17513 11.01 8.89)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="nnv6oabuq"/><stop offset="1" class="ih2vhqbgt"/></radialGradient><radialGradient id="iMOj39c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1 -6.0416 0 15.99 1.933)" gradientUnits="userSpaceOnUse"><stop class="p9pt_iv8l"/><stop offset="1" class="i30ki7brg"/></radialGradient><radialGradient id="i5Kog1r" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45508 3.06778 0 15.99 4.795)" gradientUnits="userSpaceOnUse"><stop class="d__zvs94x"/><stop offset="1" class="exhvt3bml"/></radialGradient><radialGradient id="ikKCdmc" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -2.6875 1.35972 .82215 12.266 5.746)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="ii6mzr5ev"/><stop offset="1" class="wolfrvf5u"/></radialGradient><radialGradient id="iCttNEd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18749 -3.4375 1.7319 -1.1021 20.125 6.762)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="ii6mzr5ev"/><stop offset="1" class="wolfrvf5u"/></radialGradient><radialGradient id="i8yBOfX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2259 -.76773 0 16.433 11.487)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iA8J6qe" cx="0" cy="0" r="1" gradientTransform="rotate(157.024 7.16 7.162)scale(1.6534 2.5206)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iSoxgbC" cx="0" cy="0" r="1" gradientTransform="rotate(-117.266 11.958 -.826)scale(.57126 .90459)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iI09Pie" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.918 9.254)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="iR6r5Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.26172 -.50781 .80412 -.41444 13.804 9.425)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iurvIzd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.368 -1.947)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><linearGradient id="i0F9odi" x1="5.54" x2="8.863" y1="11.096" y2="17.464" gradientUnits="userSpaceOnUse"><stop class="imlbmc2sy"/><stop offset="1" class="h7wwwp44w"/></linearGradient><linearGradient id="izESdue" x1="15.935" x2="15.935" y1="14.683" y2="29.058" gradientUnits="userSpaceOnUse"><stop class="plsegxa8t"/><stop offset="1" class="dbg8b7bda"/></linearGradient><linearGradient id="iJpKRtd" x1="8.661" x2="8.938" y1="29.058" y2="29.058" gradientUnits="userSpaceOnUse"><stop class="rq6u1obxj"/><stop offset="1" class="yomd27bxe"/></linearGradient><linearGradient id="ikoijAe" x1="23.206" x2="22.776" y1="29.058" y2="29.058" gradientUnits="userSpaceOnUse"><stop offset=".136" class="i0lopbdha"/><stop offset="1" class="w11i7m31i"/></linearGradient><linearGradient id="iH21wAd" x1="8.759" x2="7.51" y1="27.871" y2="27.871" gradientUnits="userSpaceOnUse"><stop class="k6ta6mb-r"/><stop offset="1" class="drixk4bdm"/></linearGradient><linearGradient id="ibpF4pc" x1="15.939" x2="15.939" y1="20.027" y2="29.058" gradientUnits="userSpaceOnUse"><stop class="zajm34fcf"/><stop offset="1" class="puh_1hb6q"/></linearGradient><linearGradient id="i7vLzOc" x1="15.939" x2="15.939" y1="29.058" y2="26.402" gradientUnits="userSpaceOnUse"><stop class="ou_12nqfl"/><stop offset="1" class="ypzxpcc2j"/></linearGradient><linearGradient id="i0DeLEe" x1="19.542" x2="17.698" y1="27.871" y2="27.871" gradientUnits="userSpaceOnUse"><stop offset=".119" class="zxxizob4i"/><stop offset="1" class="u7u0nyv_w"/></linearGradient><linearGradient id="i3ewByb" x1="15.935" x2="15.935" y1="16.949" y2="24.977" gradientUnits="userSpaceOnUse"><stop class="gmn9ea1yo"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="iVtk4qe" x1="21.542" x2="22.417" y1="7.527" y2="10.215" gradientUnits="userSpaceOnUse"><stop class="nn6-fgbyw"/><stop offset="1" class="kgk9-3b8f"/></linearGradient><linearGradient id="ipZ9T9d" x1="21.862" x2="22.131" y1="7.269" y2="7.691" gradientUnits="userSpaceOnUse"><stop class="b-jo-_osr"/><stop offset="1" class="bmy67tbbi"/></linearGradient><linearGradient id="iVVzW5c" x1="8.979" x2="11.385" y1="9.621" y2="8.621" gradientUnits="userSpaceOnUse"><stop class="fhqxyfhau"/><stop offset="1" class="thtu3qbtz"/></linearGradient><linearGradient id="igoaSqd" x1="15.948" x2="15.948" y1="13.801" y2="13.379" gradientUnits="userSpaceOnUse"><stop class="hln8tw04j"/><stop offset="1" class="muom63bbu"/></linearGradient><linearGradient id="iKeTB2W" x1="17.479" x2="16.94" y1="12.988" y2="13.23" gradientUnits="userSpaceOnUse"><stop class="h4n1x2_nx"/><stop offset="1" class="kbidwf4gr"/></linearGradient><linearGradient id="iqRluYn" x1="14.969" x2="14.516" y1="13.23" y2="13.157" gradientUnits="userSpaceOnUse"><stop class="ftqk6c0fk"/><stop offset="1" class="seh9j6z3x"/></linearGradient><linearGradient id="isQUMsb" x1="16.351" x2="16.479" y1="18.207" y2="18.816" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="iv2iGXc" x1="15.546" x2="15.417" y1="18.207" y2="18.816" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="iG9SZHd" x1="12.448" x2="14.433" y1="7.57" y2="6.871" gradientUnits="userSpaceOnUse"><stop class="bq_0jebkw"/><stop offset="1" class="kjjvcb6je"/><stop offset="1" class="wasds5b8d"/></linearGradient><linearGradient id="iAHFyRm" x1="19.43" x2="17.445" y1="7.57" y2="6.871" gradientUnits="userSpaceOnUse"><stop class="bq_0jebkw"/><stop offset="1" class="kjjvcb6je"/><stop offset="1" class="wasds5b8d"/></linearGradient><linearGradient id="iqe5GYc" x1="16.042" x2="20.276" y1="4.48" y2="3.246" gradientUnits="userSpaceOnUse"><stop offset=".164" class="a0m3qtb0g"/><stop offset=".481" class="y8ovvibws"/><stop offset=".742" class="aplh-7tkj"/></linearGradient><linearGradient id="il1IJwe" x1="14.057" x2="12.174" y1="6.898" y2="7.269" gradientUnits="userSpaceOnUse"><stop class="map3_rs3n"/><stop offset="1" class="ymkmd4kjm"/></linearGradient><linearGradient id="iHpLoPe" x1="19.439" x2="16.973" y1="7.258" y2="7.049" gradientUnits="userSpaceOnUse"><stop class="map3_rs3n"/><stop offset="1" class="ymkmd4kjm"/></linearGradient><linearGradient id="iaJAwve" x1="16.805" x2="15.966" y1="10.852" y2="10.89" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iUIMDmc" x1="15.966" x2="15.966" y1="11.906" y2="11.476" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iXm5X1X" x1="15.966" x2="15.966" y1="9.172" y2="9.909" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="ifG3quc" x1="18.887" x2="18.63" y1="9.231" y2="9.396" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="i9nNcWc" x1="14.524" x2="14.21" y1="9.223" y2="9.417" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><filter id="iiNq7Me" width="4.702" height="8.2" x="22.301" y="10.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1217"/></filter><filter id="iD8XcqB" width="4.902" height="8.4" x="5.146" y="10.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.321569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1217"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.32549 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1217" result="effect2_innerShadow_4002_1217"/></filter><filter id="ifNc8db" width="6.968" height="4.815" x="12.464" y="14.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".25"/></filter><filter id="iDIgsOS" width="1.583" height="3.273" x="10.143" y="10.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.258824 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1217"/></filter><filter id="iuAV54d" width="6.431" height="9.028" x="12.527" y="16.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".25"/></filter><filter id="iqaQOVb" width="6.43" height="4.46" x="12.733" y="14.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.835294 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1217"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.733333 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1217" result="effect2_innerShadow_4002_1217"/></filter><filter id="imalsbd" width="5.531" height="8.006" x="13.219" y="17.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.705882 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1217"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.670588 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1217" result="effect2_innerShadow_4002_1217"/></filter><filter id="i5Ma7pU" width="11.195" height="12.422" x="10.721" y="3.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.254902 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1217"/></filter><filter id="iGMzFoT" width="3.566" height="1.546" x="14.165" y="12.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".05"/></filter><filter id="iPGoOvd" width="1.798" height="3.38" x="20.88" y="7.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".05"/></filter><filter id="iSG1P6N" width="2.017" height="3.595" x="9.092" y="7.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".1"/></filter><filter id="iXLNMCe" width="12.683" height="5.723" x="9.648" y="1.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1217"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1217" result="effect2_innerShadow_4002_1217"/></filter><filter id="iH1pt6b" width="6.906" height="3.493" x="15.313" y="2.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".25"/></filter><filter id="i4VhNqb" width="2.177" height=".868" x="12.199" y="6.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".075"/></filter><filter id="iAaSEKd" width="2.177" height=".868" x="17.488" y="6.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".075"/></filter><filter id="iWzOese" width="3.262" height="4.184" x="14.096" y="8.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".375"/></filter><filter id="itqpojc" width="2.279" height="3.084" x="14.827" y="9.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".1"/></filter><filter id="ipH0vRq" width=".787" height=".697" x="17.412" y="8.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".05"/></filter><filter id="it51pJe" width=".892" height=".914" x="18.253" y="8.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".1"/></filter><filter id="iif9p7b" width=".987" height="1.041" x="13.807" y="8.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".1"/></filter><filter id="i1hzJTB" width=".914" height=".705" x="13.052" y="8.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1217" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-vampire-dark" /></template>
<style>
.a_z7xslor {
  d: path("M18.083 8.88c.064.086-.069.19-.22.303s-.264.192-.327.107c-.064-.085.007-.245.158-.359c.152-.113.326-.135.39-.05");
}

.a0m3qtb0g {
  stop-color: var(--svg-color--505050, #505050);
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a75cnrb-k {
  stop-color: var(--svg-color--47374c, #47374C);
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.al3hsxb7i {
  fill: var(--svg-color--decee7, #DECEE7);
  fill-rule: evenodd;
  d: path("M16.458 18.208a.125.125 0 0 1 .141.107l.649 4.672a.125.125 0 1 1-.248.034l-.648-4.672a.125.125 0 0 1 .106-.14");
}

.aplh-7tkj {
  stop-color: var(--svg-color--616161, #616161);
}

.b-jo-_osr {
  stop-color: var(--svg-color--2f1c19, #2F1C19);
}

.b2cn2_uce {
  stop-color: var(--svg-color--60506b, #60506B);
}

.b94-l-y5w {
  stop-color: var(--svg-color--3c2728, #3C2728);
}

.bf9linbqu {
  d: path("M18.15 8.692a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.bhqibir3b {
  fill: var(--svg-color--302838, #302838);
  d: path("m10.174 11.836l-.03-1.145h1.382v3.274c-1.125-.524-1.354-1.603-1.352-2.13");
}

.bmy67tbbi {
  stop-color: var(--svg-color--2f1c19, #2F1C19);
  stop-opacity: 0;
}

.bq_0jebkw {
  stop-color: var(--svg-color--281c22, #281C22);
}

.bt_wr5bpp {
  fill: var(--svg-color--1f1e1d, #1F1E1D);
  d: path("M21.153 7.656c-.01-2.238-1.441-3.282-2.21-3.54c-.872-.29-1.484-.263-1.917-.074c-.418.182-.565.53-.695.836l-.014.035c-.14.326-.614.301-.742 0l-.014-.035c-.13-.307-.277-.654-.695-.836c-.434-.19-1.067-.217-1.938.075c-.763.255-2.14 1.27-2.186 3.48c-.276-.21-.66-.662-.764-1.382c-.139-.975.218-1.366.728-1.926q.095-.103.194-.215l.032-.036c.62-.7 1.864-2.105 3.937-2.105h2.241c2.073 0 3.317 1.404 3.937 2.105l.032.036l.194.215c.51.56.867.951.728 1.926c-.114.797-.574 1.266-.848 1.441");
}

.c1mh3mgls {
  d: path("M21.153 7.656c-.01-2.238-1.441-3.282-2.21-3.54c-.872-.29-1.484-.263-1.917-.074c-.418.182-.565.53-.695.836l-.014.035c-.14.326-.614.301-.742 0l-.014-.035c-.13-.307-.277-.654-.695-.836c-.434-.19-1.067-.217-1.938.075c-.763.255-2.14 1.27-2.186 3.48c-.276-.21-.66-.662-.764-1.382c-.139-.975.218-1.366.728-1.926q.095-.103.194-.215l.032-.036c.62-.7 1.864-2.105 3.937-2.105h2.241c2.073 0 3.317 1.404 3.937 2.105l.032.036l.194.215c.51.56.867.951.728 1.926c-.114.797-.574 1.266-.848 1.441");
}

.carxtabzu {
  stop-color: var(--svg-color--604f70, #604F70);
  stop-opacity: 0;
}

.cjushcbdo {
  d: path("M23.11 17.454v11.604h3.762v-3.234c0-3.295-1.456-6.31-3.761-8.37");
}

.coremvbkz {
  stop-color: var(--svg-color--5b4161, #5B4161);
  stop-opacity: 0;
}

.d__zvs94x {
  stop-color: var(--svg-color--21132a, #21132A);
}

.d6o1i3elf {
  stop-color: var(--svg-color--404040, #404040);
  stop-opacity: 0;
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dbg8b7bda {
  stop-color: var(--svg-color--553d71, #553D71);
}

.ditqpozrw {
  d: path("M15.935 14.683c-6.04 0-10.938 5.1-10.938 11.141v3.234h21.875v-3.234c0-6.04-4.896-11.14-10.937-11.14");
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.e06hnni3m {
  stop-color: var(--svg-color--e73665, #E73665);
}

.e7f-98b7z {
  stop-color: var(--svg-color--402825, #402825);
}

.ee2oaqb4r {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.513 12.559a2.94 2.94 0 0 0 2.87 0c.077-.042.17.022.143.106c-.26.85-.993 1.026-1.578 1.026s-1.317-.176-1.578-1.026c-.026-.084.066-.148.143-.106Z");
}

.ehu1o5vid {
  stop-color: var(--svg-color--47304f, #47304F);
  stop-opacity: 0;
}

.el6sdrb2c {
  d: path("m10.778 8.433l.062 1.134l.069 1.24C9.833 9.942 9.41 8.685 9.294 7.86c-.028-.2.19-.318.355-.204z");
}

.ev3jkwgwv {
  d: path("M12.733 18.797v-3.754h6.43v3.649c0 .403-.233.603-.777.347c-.739-.347-2.453-1.617-2.453-1.617S14 18.81 13.53 19.019s-.797.182-.797-.222");
}

.exhvt3bml {
  stop-color: var(--svg-color--21132a, #21132A);
  stop-opacity: 0;
}

.f1lm8sbjk {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
}

.f6lcb9bkn {
  stop-color: var(--svg-color--56475f, #56475F);
  stop-opacity: 0;
}

.fg6i_oqme {
  stop-color: var(--svg-color--574b64, #574B64);
}

.fhqxyfhau {
  stop-color: var(--svg-color--382326, #382326);
}

.fpvu-0bdf {
  d: path("M6.27 10.202q-.254.22-.5.454a1.68 1.68 0 0 0-.48 1.602c.462 1.964 1.584 4.649 3.62 6.143l1.038-.694c-2.588-1.72-3.696-4.97-3.678-7.506");
}

.ft5dv1b6b {
  fill: none;
}

.ftqk6c0fk {
  stop-color: var(--svg-color--d1c8d8, #D1C8D8);
}

.fxbsjml4i {
  fill-rule: evenodd;
  d: path("M16.458 18.208a.125.125 0 0 1 .141.107l.649 4.672a.125.125 0 1 1-.248.034l-.648-4.672a.125.125 0 0 1 .106-.14");
}

.fzg1bwbxm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.424 7.316c.224-.18.93-.5 1.727-.398");
}

.g_z46f3jl {
  stop-color: var(--svg-color--655578, #655578);
}

.g-7ivnbav {
  stop-color: var(--svg-color--583e3b, #583E3B);
}

.g4nd-rv6p {
  d: path("M13.778 8.692a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.gbck5ebgo {
  stop-color: var(--svg-color--a99494, #A99494);
  stop-opacity: 0;
}

.gdsiwyiyr {
  stop-color: var(--svg-color--e82e5c, #E82E5C);
}

.glx9rn1kk {
  stop-color: var(--svg-color--494949, #494949);
}

.gmn9ea1yo {
  stop-color: var(--svg-color--f4dff7, #F4DFF7);
}

.gyjispkmu {
  fill: var(--svg-color--3e262d, #3E262D);
  d: path("m15.69 9.73l-.82 1.7c-.102.35.142.7.488.7h.738c.346 0 .59-.355.489-.7l-.5-1.7c-.106-.377-.282-.377-.394 0");
}

.gzag6vibp {
  d: path("M18.945 9.467a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.h1sgipbfm {
  stop-color: var(--svg-color--d82535, #D82535);
}

.h4n1x2_nx {
  stop-color: var(--svg-color--e6deec, #E6DEEC);
}

.h7wwwp44w {
  stop-color: var(--svg-color--302736, #302736);
}

.hjlrz39ai {
  stop-color: var(--svg-color--200f10, #200F10);
  stop-opacity: 0;
}

.hl4dixbko {
  stop-color: var(--svg-color--ff6d74, #FF6D74);
}

.hln8tw04j {
  stop-color: var(--svg-color--4d3c3c, #4D3C3C);
}

.hy1_v56-b {
  stop-color: var(--svg-color--38212d, #38212D);
}

.i0lopbdha {
  stop-color: var(--svg-color--4a2f65, #4A2F65);
}

.i1u0xeg2c {
  stop-color: var(--svg-color--665654, #665654);
  stop-opacity: 0;
}

.i30ki7brg {
  stop-color: var(--svg-color--202020, #202020);
  stop-opacity: 0;
}

.ih2ibv29b {
  stop-color: var(--svg-color--574b64, #574B64);
  stop-opacity: 0;
}

.ih2vhqbgt {
  stop-color: var(--svg-color--443738, #443738);
}

.ihp7x-bon {
  stop-color: var(--svg-color--655578, #655578);
  stop-opacity: 0;
}

.ii6mzr5ev {
  stop-color: var(--svg-color--060303, #060303);
}

.imlbmc2sy {
  stop-color: var(--svg-color--554961, #554961);
}

.iwate57pq {
  stop-color: var(--svg-color--3e2322, #3E2322);
}

.jh5w8ibpn {
  cx: 13.508px;
  cy: 9.074px;
  rx: 0.39px;
  ry: 0.197px;
}

.jpxim8b1x {
  stop-color: var(--svg-color--534263, #534263);
}

.jsbpdr4yj {
  stop-color: var(--svg-color--483859, #483859);
}

.jtbt9y0gz {
  stop-color: var(--svg-color--56475f, #56475F);
}

.jym7wkbau {
  d: path("M25.979 10.202q.254.22.5.454c.431.413.616 1.02.48 1.602c-.462 1.964-1.584 4.649-3.62 6.143l-1.038-.694c2.587-1.72 3.696-4.97 3.678-7.506");
}

.jzwike70j {
  stop-color: var(--svg-color--a99494, #A99494);
}

.k6ta6mb-r {
  stop-color: var(--svg-color--423153, #423153);
}

.kbidwf4gr {
  stop-color: var(--svg-color--d3cadb, #D3CADB);
}

.kck72bb7a {
  fill: var(--svg-color--bb172a, #BB172A);
  d: path("M12.964 18.94v-3.484h5.968v3.387c0 .374-.216.56-.721.322c-.685-.322-2.277-1.5-2.277-1.5s-1.793 1.288-2.23 1.482c-.438.195-.74.168-.74-.206");
}

.kgk9-3b8f {
  stop-color: var(--svg-color--4c3332, #4C3332);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kjjvcb6je {
  stop-color: var(--svg-color--301d1b, #301D1B);
}

.ko44f1ecp {
  stop-color: var(--svg-color--665654, #665654);
}

.kqp3z9b3n {
  stop-color: var(--svg-color--9c8ea7, #9C8EA7);
  stop-opacity: 0;
}

.ky2i9gfwu {
  stop-color: var(--svg-color--422628, #422628);
}

.l0d7sccpf {
  stop-color: var(--svg-color--48335e, #48335E);
}

.lft-zacfy {
  stop-color: var(--svg-color--ff242f, #FF242F);
}

.lsa_f9bow {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.57 8.42c-.653 0-1.205.45-1.355 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.lup0rknnc {
  cx: 13.508px;
  cy: 9.074px;
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.39px;
  ry: 0.197px;
}

.lymk7up5q {
  stop-color: var(--svg-color--594948, #594948);
}

.m2dsk_bhk {
  fill-rule: evenodd;
  d: path("M17.74 7.18c.717-.134 1.346.18 1.57.342a.25.25 0 1 0 .294-.404c-.292-.212-1.059-.597-1.955-.43a.25.25 0 0 0 .092.491");
}

.map3_rs3n {
  stop-color: var(--svg-color--4e4649, #4E4649);
}

.mdkt7kbno {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.584 9.567l-.532 1.7a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.mi551g4xt {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.356 8.42c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.mmdfzdm0x {
  d: path("M20.945 11.405c.03-.514.065-1.152.103-1.838l.098-1.8a16 16 0 0 1 1.708-.97c.214-.102.456.02.461.258c.014.64-.118 1.503-.656 2.527c-.62 1.215-1.21 1.655-1.714 1.823");
}

.mqv57bcbp {
  stop-color: var(--svg-color--6a5856, #6A5856);
  stop-opacity: 0;
}

.muom63bbu {
  stop-color: var(--svg-color--4d3c3c, #4D3C3C);
  stop-opacity: 0;
}

.n_d3gr2_k {
  stop-color: var(--svg-color--4a4a4a, #4A4A4A);
}

.n52c8qgao {
  stop-color: var(--svg-color--3d3743, #3D3743);
}

.nn6-fgbyw {
  stop-color: var(--svg-color--463032, #463032);
}

.nnv6oabuq {
  stop-color: var(--svg-color--443738, #443738);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o9bbdk3je {
  fill: var(--svg-color--1e1d1d, #1E1D1D);
  d: path("M10.047 7.711c-.01-.09-.088-.45-.315-1.182c-.284-.915-.348-1.17-.142-1.75c.238-.67.713-.979 1.214-1.304l.24-.158c.583-.394.772-.572 1.292-1.108s1.38-1.225 2.55-1.009c.484.109.861.12 1.049.126a5.3 5.3 0 0 0 1.048-.126c1.17-.216 2.03.473 2.55 1.01c.52.535.71.713 1.293 1.107l.24.158c.5.325.976.634 1.214 1.304c.206.58.142.835-.142 1.75c-.227.731-.305 1.093-.315 1.182l-.68.3c.149-2.484-1.392-3.623-2.201-3.894c-.871-.292-1.483-.264-1.916-.075c-.418.182-.565.53-.695.836l-.014.035c-.14.326-.614.301-.742 0l-.014-.035c-.13-.307-.277-.654-.695-.836c-.434-.19-1.067-.217-1.938.075c-.81.27-2.308 1.395-2.18 3.894z");
}

.odfe47amh {
  stop-color: var(--svg-color--746784, #746784);
}

.oh_kewb0f {
  fill-rule: evenodd;
  d: path("M14.138 7.18c-.717-.134-1.345.18-1.57.342a.25.25 0 0 1-.293-.404c.291-.212 1.058-.597 1.954-.43a.25.25 0 1 1-.091.491");
}

.oipnm6glf {
  stop-color: var(--svg-color--442c29, #442C29);
  stop-opacity: 0;
}

.oj4dw6cda {
  stop-color: var(--svg-color--543e6e, #543E6E);
}

.ou_12nqfl {
  stop-color: var(--svg-color--f73397, #F73397);
}

.oxgh8sb0d {
  fill-rule: evenodd;
  d: path("M15.438 18.208a.125.125 0 0 0-.141.107l-.649 4.672a.125.125 0 0 0 .248.034l.649-4.672a.125.125 0 0 0-.107-.14");
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.ozza9wbzj {
  stop-color: var(--svg-color--ff136b, #FF136B);
}

.p5bq_2b9f {
  stop-color: var(--svg-color--605075, #605075);
}

.p71wtvbay {
  stop-color: var(--svg-color--f3e0ff, #F3E0FF);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.p9pt_iv8l {
  stop-color: var(--svg-color--202020, #202020);
}

.pa4puzbvc {
  fill: var(--svg-color--000, #000);
  d: path("M14.29 9.585a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
}

.plsegxa8t {
  stop-color: var(--svg-color--503d5d, #503D5D);
}

.pogxiw08n {
  d: path("M8.76 17.454v11.604H4.996v-3.234c0-3.295 1.457-6.31 3.762-8.37");
}

.pu1_ubb-e {
  stop-color: var(--svg-color--eae1f3, #EAE1F3);
}

.puh_1hb6q {
  stop-color: var(--svg-color--ff3779, #FF3779);
}

.pxp9rxlhv {
  stop-color: var(--svg-color--e33e4b, #E33E4B);
}

.qhxuaybfw {
  stop-color: var(--svg-color--dfcfe8, #DFCFE8);
  stop-opacity: 0;
}

.quxm6bems {
  fill: var(--svg-color--c91a3b, #C91A3B);
  d: path("m14.177 17.012l-1.144 6.985a.402.402 0 0 0 .602.41l.201-.119a.51.51 0 0 1 .554.028l.706.513a1.1 1.1 0 0 0 1.294 0l.706-.513a.51.51 0 0 1 .553-.028l.202.118a.402.402 0 0 0 .602-.409l-1.145-6.985z");
}

.qv-_izbdm {
  d: path("M14.594 9.48c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.qz8mrpbia {
  fill: var(--svg-color--1e1c21, #1E1C21);
  d: path("m21.722 11.836l.03-1.145H20.37v3.274c1.125-.524 1.354-1.603 1.352-2.13");
}

.r0j763b4n {
  d: path("M5.77 10.656c2.244-2.143 5.052-3.376 6.334-3.816l4.063 12.312h-5.89c-2.916-1.118-4.431-4.528-4.987-6.894a1.68 1.68 0 0 1 .48-1.602");
}

.r21k1wzrc {
  stop-color: var(--svg-color--60506b, #60506B);
  stop-opacity: 0;
}

.r3f5xvbmj {
  stop-color: var(--svg-color--48335e, #48335E);
  stop-opacity: 0;
}

.ri_i1lblj {
  stop-color: var(--svg-color--47374c, #47374C);
  stop-opacity: 0;
}

.rjxs4hg5m {
  stop-color: var(--svg-color--422628, #422628);
  stop-opacity: 0;
}

.rlrkc3tlk {
  stop-color: var(--svg-color--301f25, #301F25);
}

.roo9_2b8i {
  d: path("M13.237 3.996c-1.172.219-2.635 1.68-2.508 3.922c.032.555.062 1.116.091 1.649c.064 1.157.12 2.177.16 2.695c.04.453.252 1.55.765 2.312c.64.953 1.89 1.61 2.969 1.61h2.46c1.079 0 2.329-.657 2.97-1.61c.512-.762.723-1.86.765-2.312c.04-.518.095-1.537.158-2.695l.092-1.65c.127-2.241-1.336-3.702-2.508-3.921c-1.677-.313-3.737-.313-5.414 0");
}

.rq6u1obxj {
  stop-color: var(--svg-color--453455, #453455);
}

.s4ff5rbng {
  stop-color: var(--svg-color--6a5856, #6A5856);
}

.s90difbur {
  fill: var(--svg-color--000, #000);
  d: path("M17.638 9.585a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.236");
}

.seh9j6z3x {
  stop-color: var(--svg-color--c7becf, #C7BECF);
}

.sfkkzgbur {
  stop-color: var(--svg-color--281717, #281717);
  stop-opacity: 0;
}

.st-pambja {
  stop-color: var(--svg-color--494949, #494949);
  stop-opacity: 0;
}

.t3ctwsx-f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M15.964 4.527c.182-.536.734-1.453 1.953-1.61c1.394-.178 3.043 1.114 3.652 2.177");
}

.thtu3qbtz {
  stop-color: var(--svg-color--221210, #221210);
}

.tt0m3dw5o {
  stop-color: var(--svg-color--473031, #473031);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.tzvl-yazp {
  d: path("m20.98 10.792l.131-2.372l1.11-.764c.165-.114.383.004.355.204c-.117.82-.534 2.067-1.596 2.932");
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u7u0nyv_w {
  stop-color: var(--svg-color--dd2864, #DD2864);
  stop-opacity: 0;
}

.u971fdczb {
  stop-color: var(--svg-color--200f10, #200F10);
}

.udqi13bwa {
  stop-color: var(--svg-color--594948, #594948);
  stop-opacity: 0;
}

.up3z98m5n {
  fill: var(--svg-color--393939, #393939);
  fill-rule: evenodd;
  d: path("M17.74 7.18c.717-.134 1.346.18 1.57.342a.25.25 0 1 0 .294-.404c-.292-.212-1.059-.597-1.955-.43a.25.25 0 0 0 .092.491");
}

.uw1qucxdm {
  stop-color: var(--svg-color--d2bdd8, #D2BDD8);
}

.uwsxe-bjv {
  stop-color: var(--svg-color--5b4161, #5B4161);
}

.uxwciubxp {
  stop-color: var(--svg-color--776484, #776484);
}

.vbb18ixfb {
  stop-color: var(--svg-color--6b5a80, #6B5A80);
}

.vkj9-gbgg {
  fill: var(--svg-color--decee8, #DECEE8);
  fill-rule: evenodd;
  d: path("M15.438 18.208a.125.125 0 0 0-.141.107l-.649 4.672a.125.125 0 0 0 .248.034l.649-4.672a.125.125 0 0 0-.107-.14");
}

.vo8nxhb-a {
  stop-color: var(--svg-color--e5e5e5, #E5E5E5);
  stop-opacity: 0;
}

.vswxs9bpn {
  d: path("M10.047 7.711c-.01-.09-.088-.45-.315-1.182c-.284-.915-.348-1.17-.142-1.75c.238-.67.713-.979 1.214-1.304l.24-.158c.583-.394.772-.572 1.292-1.108s1.38-1.225 2.55-1.009c.484.109.861.12 1.049.126a5.3 5.3 0 0 0 1.048-.126c1.17-.216 2.03.473 2.55 1.01c.52.535.71.713 1.293 1.107l.24.158c.5.325.976.634 1.214 1.304c.206.58.142.835-.142 1.75c-.227.731-.305 1.093-.315 1.182l-.68.3c.149-2.484-1.392-3.623-2.201-3.894c-.871-.292-1.483-.264-1.916-.075c-.418.182-.565.53-.695.836l-.014.035c-.14.326-.614.301-.742 0l-.014-.035c-.13-.307-.277-.654-.695-.836c-.434-.19-1.067-.217-1.938.075c-.81.27-2.308 1.395-2.18 3.894z");
}

.vx8dsgrfz {
  stop-color: var(--svg-color--281717, #281717);
}

.w11i7m31i {
  stop-color: var(--svg-color--665579, #665579);
  stop-opacity: 0;
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.wa6qzac-e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.44 7.258c-.225-.18-.93-.5-1.728-.399");
}

.wasds5b8d {
  stop-color: var(--svg-color--1f1216, #1F1216);
}

.wolfrvf5u {
  stop-color: var(--svg-color--060303, #060303);
  stop-opacity: 0;
}

.wuihzi_9f {
  d: path("m17.153 13.715l-.396-.895c.257-.078.466-.175.624-.263c.102-.057.248.043.218.156l-.258.987a.1.1 0 0 1-.188.015");
}

.wuxtngbmf {
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M18.083 8.88c.064.086-.069.19-.22.303s-.264.192-.327.107c-.064-.085.007-.245.158-.359c.152-.113.326-.135.39-.05");
}

.x25i7gb0d {
  fill: var(--svg-color--290118, #290118);
  d: path("M14.513 12.559a2.94 2.94 0 0 0 2.87 0c.077-.042.17.022.143.106c-.26.85-.993 1.026-1.578 1.026s-1.317-.176-1.578-1.026c-.026-.084.066-.148.143-.106");
}

.x8ix_1b_c {
  stop-color: var(--svg-color--361e26, #361E26);
  stop-opacity: 0;
}

.xc8nhibmz {
  d: path("m10.743 7.78l.006.138l.091 1.649c.038.689.073 1.33.104 1.844c-.508-.163-1.105-.599-1.733-1.83c-.538-1.023-.67-1.886-.656-2.526c.005-.237.247-.36.46-.258c.61.291 1.235.658 1.728.982");
}

.xksrntfob {
  stop-color: var(--svg-color--b3a9bc, #B3A9BC);
}

.xn_fidfol {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
  stop-opacity: 0;
}

.xo0xxmoup {
  d: path("M12.733 29.058V15.166a10.7 10.7 0 0 1 3.183-.483a10.7 10.7 0 0 1 3.23.497v13.878z");
}

.y465w_bjd {
  stop-color: var(--svg-color--404040, #404040);
}

.y8ovvibws {
  stop-color: var(--svg-color--484848, #484848);
  stop-opacity: 0;
}

.yg9akk17m {
  d: path("m15.584 9.567l-.532 1.7a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.ymkmd4kjm {
  stop-color: var(--svg-color--4e4649, #4E4649);
  stop-opacity: 0;
}

.yomd27bxe {
  stop-color: var(--svg-color--453455, #453455);
  stop-opacity: 0;
}

.ypzxpcc2j {
  stop-color: var(--svg-color--f73397, #F73397);
  stop-opacity: 0;
}

.yrzxb9b5h {
  d: path("m14.083 18.695l-.858 5.24a.402.402 0 0 0 .602.409l.201-.118a.51.51 0 0 1 .554.027l.705.514a1.1 1.1 0 0 0 1.295 0l.706-.514a.51.51 0 0 1 .553-.027l.202.118a.402.402 0 0 0 .602-.41l-.858-5.233c-.81-.505-1.855-1.28-1.855-1.28s-1.107.796-1.849 1.274");
}

.z8m-hreok {
  stop-color: var(--svg-color--47304f, #47304F);
}

.zajm34fcf {
  stop-color: var(--svg-color--e32d3d, #E32D3D);
}

.zbu6axbaw {
  d: path("M26.478 10.656c-2.243-2.143-5.051-3.376-6.334-3.816l-4.062 12.312h5.89c2.916-1.118 4.431-4.528 4.986-6.894a1.68 1.68 0 0 0-.48-1.602");
}

.zdoa0yq9l {
  d: path("m14.735 13.715l.396-.895a3.2 3.2 0 0 1-.624-.263c-.102-.057-.248.043-.218.156l.257.987a.1.1 0 0 0 .189.015");
}

.zdwvyrbqc {
  stop-color: var(--svg-color--361e26, #361E26);
}

.zxxizob4i {
  stop-color: var(--svg-color--c52133, #C52133);
}

</style>
