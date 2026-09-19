<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPH7xVd)"><path fill="url(#ixVUzle)" clip-rule="evenodd" class="enbg2f5yw"/></g><g filter="url(#iaTlkgc)"><path class="mt3agfeyc"/><path fill="url(#ixskz7c)" class="pl049mlvn"/><path fill="url(#iheoHVd)" class="pl049mlvn"/></g><path fill="url(#i5wwS4d)" class="pl049mlvn"/><path fill="url(#it0JlNd)" class="omms1hbxq"/><path fill="url(#ikPAQGL)" class="omms1hbxq"/><path fill="url(#iWTMgBi)" class="omms1hbxq"/><g filter="url(#iPSV5nd)"><path class="h6114zkcs"/></g><path class="ebr-2mmqh"/><path fill="url(#iP9cu3c)" class="k78a0jbvv"/><path fill="url(#iPnAc3R)" class="k78a0jbvv"/><path fill="url(#iru8Xud)" class="k78a0jbvv"/><path fill="url(#ixjnVZc)" class="k78a0jbvv"/><g filter="url(#i2rpmME)"><path class="q4joo645p"/></g><path fill="url(#iC35oPd)" class="s_3zwkbhw"/><path fill="url(#iWfnjGc)" class="s_3zwkbhw"/><path fill="url(#ixGohNb)" class="s_3zwkbhw"/><path fill="url(#icSznJb)" class="s_3zwkbhw"/><path fill="url(#i7KF8iq)" class="s_3zwkbhw"/><path fill="url(#iPeDGZt)" class="s_3zwkbhw"/><path fill="url(#iLj3KWg)" class="s_3zwkbhw"/><path fill="url(#ihITLue)" class="xnk2l2bya"/><path fill="url(#idfE8gc)" class="xnk2l2bya"/><path fill="url(#iytrcYG)" class="xnk2l2bya"/><path fill="url(#ifOjrne)" class="xnk2l2bya"/><path fill="url(#in5evvb)" class="xnk2l2bya"/><rect fill="url(#i2cs0dv)" transform="rotate(-26.783 20.65 3.74)" class="exno9xb6e"/><rect fill="url(#iBkVbmb)" transform="rotate(-26.783 21.084 3.48)" class="t0-pbfrwb"/><rect fill="url(#iUCUCib)" transform="rotate(-26.783 21.603 3.234)" class="lijeyqbfa"/><rect fill="url(#ifPWOfe)" transform="rotate(-26.783 22.173 2.98)" class="olg4dbcpd"/><rect fill="url(#iuJXXQc)" transform="rotate(60 21.976 4.011)" class="f15-arbgd"/><g filter="url(#i4LWZ8c)"><path class="wb27l4bhs"/><path fill="url(#iSIcsJe)" class="xkamdub3z"/></g><g filter="url(#iJ8Iibe)"><path fill="url(#iBJprxq)" class="xipy-p0qb"/><path fill="url(#iYiKCbb)" class="xipy-p0qb"/><path fill="url(#iwaj5De)" class="xipy-p0qb"/></g><path fill="url(#iSVU3uc)" class="t0rt6vb0t"/><path fill="url(#i8GGVzd)" class="t0rt6vb0t"/><path fill="url(#iohP9pc)" class="ptgqu1bav"/><path fill="url(#inCEd4d)" class="ptgqu1bav"/><path fill="url(#i3kPFEe)" class="egq0gdkgq"/><path fill="url(#i42j7Ld)" class="qc_gmpkqt"/><g filter="url(#ivtGYsb)"><path fill="url(#i5kmHsb)" class="uxujrsjxl"/></g><path fill="url(#iAV4lwe)" class="uxujrsjxl"/><path fill="url(#iBB1P9d)" class="uxujrsjxl"/><path fill="url(#iRu3ofN)" class="uxujrsjxl"/><path fill="url(#iNGNsae)" class="uxujrsjxl"/><path fill="url(#ifzgjlb)" class="uxujrsjxl"/><g filter="url(#iTpf2Cb)"><path class="dzp61fbni"/></g><g filter="url(#iQ7C1me)"><path fill="url(#iEgpEDd)" class="zwaguzbxa"/><path fill="url(#ipoRgvb)" class="zwaguzbxa"/><path fill="url(#i8sPPuV)" class="zwaguzbxa"/><path fill="url(#iPg73Bc)" class="zwaguzbxa"/></g><path fill="url(#iiYQNhd)" class="szwyz5b7x"/><g filter="url(#ioIb5Uc)"><path class="x3vluzbgl"/></g><g filter="url(#iwmoDxb)"><path class="ntf44obau"/></g><path class="c-9pe2dhf"/><path fill="url(#iCtZNJe)" class="oykl6nbsu"/><path class="j-_odrnuk"/><g filter="url(#iyJRp6d)"><path class="oy2bmg2hk"/><path fill="url(#i3ya5gb)" class="to2qzr-xo"/></g><g filter="url(#i4kEakc)"><path fill="url(#i1xcXcd)" class="r46ixy0tk"/></g><path class="fvoebdchu"/><path fill="url(#iau8Qte)" class="z5cbgecks"/><path class="jhlegmjip"/><g filter="url(#irdSxlb)"><path fill="url(#i38MsLb)" class="r387_acpi"/></g><g filter="url(#ilyO5oe)"><ellipse transform="rotate(-54.009 13.572 6.105)" class="ks0g04c0s"/><ellipse fill="url(#iev5hwd)" transform="rotate(-54.009 13.572 6.105)" class="hob_weexg"/></g><path fill="url(#iTLFcub)" class="tcbfrl09k"/><path fill="url(#ikWUNob)" class="tcbfrl09k"/><path fill="url(#ibcSQNq)" class="tcbfrl09k"/><path fill="url(#iIJlvsd)" class="oyg3rwtgg"/><path fill="url(#iosuPje)" class="oyg3rwtgg"/><g filter="url(#iiaAeJC)"><path class="xzviogqak"/></g><g filter="url(#i6TLrkc)"><path class="u7tbj0bap"/></g><path fill="url(#iMvzFIe)" class="qq2dxfbei"/><path fill="url(#ibAy9od)" class="qq2dxfbei"/><path fill="url(#i94xqJc)" class="qq2dxfbei"/><path fill="url(#iV3WF4r)" class="qq2dxfbei"/><g filter="url(#id0gR3d)"><path fill="url(#iNNgYxb)" class="p8_7hsp1q"/><path fill="url(#itfeErb)" class="p8_7hsp1q"/></g><g filter="url(#iKS3S9d)"><path class="cyj_-hvmj"/></g><g filter="url(#i6jLUsA)"><path stroke="url(#ivaDZRG)" class="huh1sac2a"/></g><g filter="url(#ieKJi5c)"><path fill="url(#iUbjRRb)" class="t4j6y4bmp"/></g><defs><radialGradient id="ixskz7c" cx="0" cy="0" r="1" gradientTransform="rotate(146.915 8.826 5.736)scale(4.92324 2.04943)" gradientUnits="userSpaceOnUse"><stop class="ba1yb3bji"/><stop offset="1" class="kgrhzo17p"/></radialGradient><radialGradient id="i5wwS4d" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -.0625 .23626 5.43402 6.51 13.318)" gradientUnits="userSpaceOnUse"><stop class="wn-t5ndzy"/><stop offset="1" class="ben4f0bqs"/></radialGradient><radialGradient id="iWTMgBi" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .16016 -.21807 -.37232 24.841 2.572)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="i42zc8m6u"/><stop offset="1" class="dsumrvbgt"/></radialGradient><radialGradient id="iPnAc3R" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 -.46876 .24583 -.45888 14.135 29.178)" gradientUnits="userSpaceOnUse"><stop class="ynlfw99ba"/><stop offset="1" class="in-vfpgwh"/></radialGradient><radialGradient id="iru8Xud" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .85157 -1.15842 -1.0415 12.744 26.67)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="vkrof_bbk"/><stop offset="1" class="h8hiq33uv"/></radialGradient><radialGradient id="ixjnVZc" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 .15625 -.58594 3.04687 11.369 28.068)" gradientUnits="userSpaceOnUse"><stop class="ilg8l_bzj"/><stop offset="1" class="s2j02zbkr"/></radialGradient><radialGradient id="iWfnjGc" cx="0" cy="0" r="1" gradientTransform="matrix(2.71873 -2.53127 .81258 .87276 13.166 27.631)" gradientUnits="userSpaceOnUse"><stop class="pcvpzjboo"/><stop offset="1" class="qe_2d-buv"/></radialGradient><radialGradient id="ixGohNb" cx="0" cy="0" r="1" gradientTransform="matrix(2.54688 -2.64063 .2894 .27913 12.275 25.975)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="kxzgmzb5t"/><stop offset="1" class="xhu8yhbcw"/></radialGradient><radialGradient id="icSznJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 0 0 -5.02098 17.369 21.318)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="keljo6scd"/><stop offset="1" class="ps4m-ab9c"/></radialGradient><radialGradient id="i7KF8iq" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 -.98437 1.15192 .05485 17.619 17.99)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="w5oxhdc5r"/><stop offset="1" class="ebs2-pbbe"/></radialGradient><radialGradient id="iPeDGZt" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 0 0 7.6823 17.978 22.678)" gradientUnits="userSpaceOnUse"><stop class="j_l_30buh"/><stop offset="1" class="xi8fv135v"/></radialGradient><radialGradient id="iLj3KWg" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -3.34375 1.20794 1.23052 13.665 27.693)" gradientUnits="userSpaceOnUse"><stop class="ddjhanboc"/><stop offset="1" class="uu7_gub8n"/></radialGradient><radialGradient id="ihITLue" cx="0" cy="0" r="1" gradientTransform="rotate(150.356 8.617 7.45)scale(4.42262 6.15908)" gradientUnits="userSpaceOnUse"><stop class="bcesubcjx"/><stop offset="1" class="vsa1bkbba"/></radialGradient><radialGradient id="idfE8gc" cx="0" cy="0" r="1" gradientTransform="matrix(.57404 2.73801 -4.6268 .97003 17.279 6.955)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="cq96abbmk"/><stop offset="1" class="ifjstwbmn"/></radialGradient><radialGradient id="ifOjrne" cx="0" cy="0" r="1" gradientTransform="matrix(.87501 1.59375 -2.6006 1.4278 15.29 7.662)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="sncm2-ibv"/><stop offset="1" class="tb4k0qb7o"/></radialGradient><radialGradient id="in5evvb" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.01563 .0588 6.46896 13.478 10.068)" gradientUnits="userSpaceOnUse"><stop class="qhy2ocn-y"/><stop offset="1" class="g59b8gbml"/></radialGradient><radialGradient id="i2cs0dv" cx="0" cy="0" r="1" gradientTransform="matrix(.09624 .94236 -.56384 .05758 20.9 3.954)" gradientUnits="userSpaceOnUse"><stop class="hcmpzwvfn"/><stop offset="1" class="tzgzt3b1l"/></radialGradient><radialGradient id="iBkVbmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 21.76 4.148)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="euzbypbyq"/><stop offset="1" class="ob4ztkbap"/></radialGradient><radialGradient id="iUCUCib" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.28 3.902)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="euzbypbyq"/><stop offset="1" class="ob4ztkbap"/></radialGradient><radialGradient id="ifPWOfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.85 3.648)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="euzbypbyq"/><stop offset="1" class="ob4ztkbap"/></radialGradient><radialGradient id="iuJXXQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.02457 .47352 -.46721 -.02424 22.369 4.163)" gradientUnits="userSpaceOnUse"><stop class="usai76iql"/><stop offset=".931" class="muua73y8y"/></radialGradient><radialGradient id="iSIcsJe" cx="0" cy="0" r="1" gradientTransform="matrix(3.80388 .30087 -.62375 7.88601 17.576 5.303)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="t_a14bpou"/><stop offset="1" class="ojy1jndng"/></radialGradient><radialGradient id="iYiKCbb" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 .21242 -.56203 4.5475 14.04 9.475)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="tcxsyye9l"/><stop offset="1" class="e2fjo6nwd"/></radialGradient><radialGradient id="iwaj5De" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 .51562 -1.9883 .18075 16.181 8.459)" gradientUnits="userSpaceOnUse"><stop class="gq6wqmsky"/><stop offset="1" class="cci816eoj"/></radialGradient><radialGradient id="iSVU3uc" cx="0" cy="0" r="1" gradientTransform="rotate(77.074 5.077 13.297)scale(1.58458 1.88236)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="i8GGVzd" cx="0" cy="0" r="1" gradientTransform="matrix(.18224 .0961 -.08165 .15482 16.672 5.61)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iohP9pc" cx="0" cy="0" r="1" gradientTransform="matrix(1.20963 1.21552 -.5525 .54983 12.799 7.438)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="inCEd4d" cx="0" cy="0" r="1" gradientTransform="matrix(.2999 .31268 -.27429 .26307 13.043 7.314)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="i3kPFEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.44922 .26953 -.35294 -.58823 12.504 5.955)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="hiiftkbcp"/><stop offset="1" class="la-4pc5er"/></radialGradient><radialGradient id="i42j7Ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.53514 .21538 -.22142 -.55016 16.002 4.275)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="hiiftkbcp"/><stop offset="1" class="la-4pc5er"/></radialGradient><radialGradient id="i5kmHsb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.94296 .95163 -1.68344 -3.43708 15.712 5.524)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iAV4lwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.61633 -1.25836 4.89516 -2.39758 15.75 8.424)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="iBB1P9d" cx="0" cy="0" r="1" gradientTransform="matrix(.96112 2.3411 -.86068 .35335 16.543 5.01)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iRu3ofN" cx="0" cy="0" r="1" gradientTransform="matrix(-.25737 -.52547 .63264 -.30986 13.676 5.977)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iNGNsae" cx="0" cy="0" r="1" gradientTransform="matrix(-.27946 -.57058 .74006 -.36247 15.303 4.99)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="ifzgjlb" cx="0" cy="0" r="1" gradientTransform="rotate(57.933 2.922 14.451)scale(1.53037 4.18978)" gradientUnits="userSpaceOnUse"><stop offset=".159" class="rehb2ofun"/><stop offset="1" class="s8vaxcyqu"/></radialGradient><radialGradient id="iiYQNhd" cx="0" cy="0" r="1" gradientTransform="rotate(-116.095 9.948 -1.1)scale(.29827 1.20002)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iCtZNJe" cx="0" cy="0" r="1" gradientTransform="matrix(.14768 .30153 -.47962 .2349 15.312 5.297)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i3ya5gb" cx="0" cy="0" r="1" gradientTransform="rotate(-153.907 8.243 .919)scale(.15655 .21553)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iau8Qte" cx="0" cy="0" r="1" gradientTransform="matrix(.1477 .30155 -.47965 .23492 13.69 6.091)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iev5hwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0032 -.20447 .24578 -.00385 13.566 6.235)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikWUNob" cx="0" cy="0" r="1" gradientTransform="matrix(.64195 .71931 -.68628 .61247 16.22 4.859)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="ibcSQNq" cx="0" cy="0" r="1" gradientTransform="matrix(.09599 -.5452 .45699 .08046 16.453 4.995)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iosuPje" cx="0" cy="0" r="1" gradientTransform="matrix(.22446 .84672 -.8324 .22066 12.578 6.72)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iMvzFIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.32812 2.10937 -2.73038 -.42473 14.445 2.615)" gradientUnits="userSpaceOnUse"><stop class="rk9ipi4nv"/><stop offset=".816" class="d3ckukbai"/></radialGradient><radialGradient id="ibAy9od" cx="0" cy="0" r="1" gradientTransform="matrix(1.40625 .10938 -.30588 3.93273 11.586 4.74)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="uz50sub2c"/><stop offset="1" class="nk-zfnbce"/></radialGradient><radialGradient id="i94xqJc" cx="0" cy="0" r="1" gradientTransform="rotate(-113.839 8.595 -2.223)scale(1.46908 2.89909)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="e32fiwbxk"/><stop offset="1" class="w8xh_8bpw"/></radialGradient><radialGradient id="iV3WF4r" cx="0" cy="0" r="1" gradientTransform="matrix(.23438 .5625 -2.67897 1.11624 12.96 2.615)" gradientUnits="userSpaceOnUse"><stop class="ttmnipb_u"/><stop offset="1" class="g5vhmeb9a"/></radialGradient><radialGradient id="iNNgYxb" cx="0" cy="0" r="1" gradientTransform="matrix(3.26562 -1.07812 1.92394 5.82757 12.586 5.38)" gradientUnits="userSpaceOnUse"><stop class="ax7c_wbux"/><stop offset="1" class="ofy-zx6wg"/></radialGradient><radialGradient id="itfeErb" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.5 .86462 .09907 15.133 4.162)" gradientUnits="userSpaceOnUse"><stop class="p2usq5blt"/><stop offset="1" class="kxozdy23r"/></radialGradient><filter id="iPH7xVd" width="8.471" height="7.176" x="16.221" y="3.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.580392 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.545098 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22706" result="effect2_innerShadow_3987_22706"/></filter><filter id="iaTlkgc" width="18.187" height="14.194" x="6.907" y="1.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22706"/></filter><filter id="iPSV5nd" width="4.793" height="2.27" x="18.177" y="27.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.188235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22706"/></filter><filter id="i2rpmME" width="8.989" height="12.477" x="12.16" y="15.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.635294 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22706"/></filter><filter id="i4LWZ8c" width="7.553" height="7.567" x="14.35" y="3.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.658824 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.537255 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22706" result="effect2_innerShadow_3987_22706"/></filter><filter id="iJ8Iibe" width="3.395" height="2.909" x="14.313" y="8.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.341176 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22706"/></filter><filter id="ivtGYsb" width="5.419" height="5.169" x="12.134" y="3.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22706" result="effect2_innerShadow_3987_22706"/></filter><filter id="iTpf2Cb" width="2.848" height="3.193" x="13.389" y="4.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".5"/></filter><filter id="iQ7C1me" width="1.086" height="1.388" x="14.293" y="5.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".05"/></filter><filter id="ioIb5Uc" width="1.029" height=".618" x="14.703" y="4.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22706"/></filter><filter id="iwmoDxb" width=".882" height=".886" x="12.823" y="5.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22706"/></filter><filter id="iyJRp6d" width=".379" height=".461" x="14.976" y="5.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".05"/></filter><filter id="i4kEakc" width=".614" height=".616" x="15.248" y="4.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".1"/></filter><filter id="irdSxlb" width=".665" height=".658" x="13.584" y="5.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".1"/></filter><filter id="ilyO5oe" width=".431" height=".478" x="13.356" y="5.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".05"/></filter><filter id="iiaAeJC" width="1.021" height="1.204" x="12.18" y="6.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".125"/></filter><filter id="i6TLrkc" width="1.024" height="1.249" x="16.083" y="4.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".125"/></filter><filter id="id0gR3d" width="4.253" height="2.433" x="11.906" y="3.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22706"/></filter><filter id="iKS3S9d" width="1.789" height="3.497" x="8.087" y="12.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".125"/></filter><filter id="i6jLUsA" width="2.601" height="13.601" x="18.428" y="15.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".4"/></filter><filter id="ieKJi5c" width="2.563" height="7.453" x="15.025" y="16.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22706" stdDeviation=".375"/></filter><linearGradient id="ixVUzle" x1="23.013" x2="19.956" y1="4.744" y2="10.749" gradientUnits="userSpaceOnUse"><stop class="ksevddbvl"/><stop offset=".799" class="d30rw76zq"/></linearGradient><linearGradient id="iheoHVd" x1="12.494" x2="12.822" y1="9.174" y2="9.646" gradientUnits="userSpaceOnUse"><stop offset=".349" class="lr97j31fb"/><stop offset="1" class="azn0z--js"/></linearGradient><linearGradient id="it0JlNd" x1="24.916" x2="22.775" y1="2.693" y2="4.006" gradientUnits="userSpaceOnUse"><stop class="ds3hm--8v"/><stop offset="1" class="bq7w62n5j"/></linearGradient><linearGradient id="ikPAQGL" x1="23.884" x2="23.619" y1="3.693" y2="3.162" gradientUnits="userSpaceOnUse"><stop class="seeiowbir"/><stop offset="1" class="tw6dxpb7y"/></linearGradient><linearGradient id="iP9cu3c" x1="12.697" x2="12.697" y1="30.029" y2="29.357" gradientUnits="userSpaceOnUse"><stop class="dhem-xbnm"/><stop offset="1" class="zn47ozbfv"/></linearGradient><linearGradient id="iC35oPd" x1="20.478" x2="19.884" y1="22.568" y2="22.537" gradientUnits="userSpaceOnUse"><stop class="ieaclmdnn"/><stop offset="1" class="p3yd_be1u"/></linearGradient><linearGradient id="iytrcYG" x1="17.279" x2="17.279" y1="15.975" y2="12.787" gradientUnits="userSpaceOnUse"><stop offset=".039" class="ju1sfx7jc"/><stop offset="1" class="yqiyodbty"/></linearGradient><linearGradient id="iBJprxq" x1="16.01" x2="16.01" y1="8.357" y2="10.568" gradientUnits="userSpaceOnUse"><stop class="vsfo3yb3y"/><stop offset="1" class="dos09sbbm"/></linearGradient><linearGradient id="iEgpEDd" x1="14.819" x2="15.136" y1="6.343" y2="6.187" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="ipoRgvb" x1="14.392" x2="14.802" y1="6.48" y2="6.307" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="i8sPPuV" x1="14.891" x2="15.046" y1="6.491" y2="6.807" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iPg73Bc" x1="14.482" x2="14.559" y1="5.655" y2="5.811" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="i1xcXcd" x1="15.611" x2="15.529" y1="5.175" y2="5.304" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i38MsLb" x1="13.976" x2="13.895" y1="5.976" y2="6.105" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTLFcub" x1="16.908" x2="16.856" y1="4.553" y2="5.581" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iIJlvsd" x1="12.47" x2="12.989" y1="7.051" y2="6.738" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="ivaDZRG" x1="19.744" x2="19.744" y1="16.6" y2="27.506" gradientUnits="userSpaceOnUse"><stop class="hd06b2knh"/><stop offset="1" class="ggughpb3d"/></linearGradient><linearGradient id="iUbjRRb" x1="16.306" x2="16.306" y1="18.037" y2="24.6" gradientUnits="userSpaceOnUse"><stop class="y6ovumr8k"/><stop offset="1" class="t-eeezbdl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-golfing" /></template>
<style>
.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ax7c_wbux {
  stop-color: var(--svg-color--ef7849, #EF7849);
}

.azn0z--js {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
  stop-opacity: 0;
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.ba1yb3bji {
  stop-color: var(--svg-color--a99797, #A99797);
}

.bcesubcjx {
  stop-color: var(--svg-color--ff8f43, #FF8F43);
}

.ben4f0bqs {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
  stop-opacity: 0;
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bkz_cdc-o {
  stop-color: var(--svg-color--e27426, #E27426);
}

.bq7w62n5j {
  stop-color: var(--svg-color--482a5b, #482A5B);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c-9pe2dhf {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.253 4.98a.58.58 0 0 1 .697.147a.113.113 0 0 1-.038.176l-.829.406a.095.095 0 0 1-.134-.06a.58.58 0 0 1 .304-.668");
}

.cci816eoj {
  stop-color: var(--svg-color--e36512, #E36512);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cq96abbmk {
  stop-color: var(--svg-color--e27318, #E27318);
}

.cyj_-hvmj {
  stroke: var(--svg-color--c3b8c3, #C3B8C3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.51 12.615a.53.53 0 0 0 0 .54c.13.237.718 1.277.96 1.714c.05.103.111.356-.039.543");
}

.d30rw76zq {
  stop-color: var(--svg-color--f5aa27, #F5AA27);
}

.d3ckukbai {
  stop-color: var(--svg-color--f98841, #F98841);
}

.ddjhanboc {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
}

.dhem-xbnm {
  stop-color: var(--svg-color--442563, #442563);
}

.dos09sbbm {
  stop-color: var(--svg-color--ed732b, #ED732B);
}

.ds3hm--8v {
  stop-color: var(--svg-color--533d66, #533D66);
}

.dsumrvbgt {
  stop-color: var(--svg-color--615273, #615273);
  stop-opacity: 0;
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.dzp61fbni {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m14.393 5.93l.098.799c.029.16.195.253.332.186l.292-.143c.137-.067.164-.257.056-.376l-.532-.586c-.117-.13-.276-.053-.246.12");
}

.e2fjo6nwd {
  stop-color: var(--svg-color--f78b4b, #F78B4B);
  stop-opacity: 0;
}

.e32fiwbxk {
  stop-color: var(--svg-color--f47234, #F47234);
}

.ebr-2mmqh {
  fill: var(--svg-color--47385d, #47385D);
  d: path("M11.595 27.49c0-.806.458-1.159.688-1.234l1.367 1.18v1.283a.5.5 0 0 0 .188.39l.203.162c.127.094.296.239.25.415c-.082.171-.25.195-.54.195h-1.506a.65.65 0 0 1-.65-.65z");
}

.ebs2-pbbe {
  stop-color: var(--svg-color--9c8cad, #9C8CAD);
  stop-opacity: 0;
}

.egq0gdkgq {
  d: path("m12.46 6.81l-.538-1.039l.45-.671l.714 1.062z");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.enbg2f5yw {
  fill-rule: evenodd;
  d: path("M20.961 7.482c.852-1.083.48-2.214.219-2.678l1.916-1.081c.467.828 1.242 3.027-.406 5.12c-.89 1.13-2.33 1.566-3.484 1.752c-1.199.194-2.37.159-2.985.135l.084-2.198c.599.023 1.583.047 2.55-.109c1.012-.163 1.746-.484 2.106-.941");
}

.euzbypbyq {
  stop-color: var(--svg-color--fdc83c, #FDC83C);
}

.exno9xb6e {
  width: 0.692px;
  height: 1.157px;
  x: 20.651px;
  y: 3.74px;
  rx: 0.346px;
}

.f15-arbgd {
  width: 0.737px;
  height: 1.252px;
  x: 21.976px;
  y: 4.011px;
  rx: 0.369px;
}

.ft5dv1b6b {
  fill: none;
}

.fvoebdchu {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.477 5.851a.58.58 0 0 0-.311.64c.015.073.095.11.161.078l.83-.406a.095.095 0 0 0 .034-.142a.58.58 0 0 0-.715-.17");
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g59b8gbml {
  stop-color: var(--svg-color--fc8f4d, #FC8F4D);
  stop-opacity: 0;
}

.g5vhmeb9a {
  stop-color: var(--svg-color--e28636, #E28636);
  stop-opacity: 0;
}

.ggughpb3d {
  stop-color: var(--svg-color--a599b3, #A599B3);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gq6wqmsky {
  stop-color: var(--svg-color--e36512, #E36512);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h6114zkcs {
  fill: var(--svg-color--4c3765, #4C3765);
  d: path("M18.177 29.88v-1.769h2.16c.165.157.79.551 1.504.782c.494.13.625.488.63.62v.368z");
}

.h8hiq33uv {
  stop-color: var(--svg-color--271938, #271938);
  stop-opacity: 0;
}

.hcmpzwvfn {
  stop-color: var(--svg-color--e0a524, #E0A524);
}

.hd06b2knh {
  stop-color: var(--svg-color--a89eb3, #A89EB3);
}

.hiiftkbcp {
  stop-color: var(--svg-color--f49b37, #F49B37);
}

.hob_weexg {
  cx: 13.572px;
  cy: 6.105px;
  rx: 0.161px;
  ry: 0.082px;
}

.huh1sac2a {
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("m19.822 16.318l-.188 11.188");
}

.i42zc8m6u {
  stop-color: var(--svg-color--615273, #615273);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ieaclmdnn {
  stop-color: var(--svg-color--a19ca8, #A19CA8);
}

.ifjstwbmn {
  stop-color: var(--svg-color--e27318, #E27318);
  stop-opacity: 0;
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ilg8l_bzj {
  stop-color: var(--svg-color--655e6d, #655E6D);
}

.in-vfpgwh {
  stop-color: var(--svg-color--403451, #403451);
  stop-opacity: 0;
}

.j_l_30buh {
  stop-color: var(--svg-color--5d5467, #5D5467);
}

.j-_odrnuk {
  fill: var(--svg-color--000, #000);
  d: path("M15.198 5.544a.21.21 0 0 1 .097-.283a.21.21 0 0 1 .305.195l-.336.164a.2.2 0 0 1-.066-.076");
}

.jhlegmjip {
  fill: var(--svg-color--000, #000);
  d: path("M13.955 6.153a.21.21 0 0 0-.283-.097a.21.21 0 0 0-.033.36l.336-.165a.2.2 0 0 0-.02-.098");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.ju1sfx7jc {
  stop-color: var(--svg-color--ed3623, #ED3623);
}

.k78a0jbvv {
  d: path("M11.595 27.49c0-.806.458-1.159.688-1.234l1.367 1.18v1.283a.5.5 0 0 0 .188.39l.203.162c.127.094.296.239.25.415c-.082.171-.25.195-.54.195h-1.506a.65.65 0 0 1-.65-.65z");
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.keljo6scd {
  stop-color: var(--svg-color--827a8b, #827A8B);
}

.kgrhzo17p {
  stop-color: var(--svg-color--a99797, #A99797);
  stop-opacity: 0;
}

.ks0g04c0s {
  cx: 13.572px;
  cy: 6.105px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.161px;
  ry: 0.082px;
}

.ksevddbvl {
  stop-color: var(--svg-color--fdc631, #FDC631);
}

.kxozdy23r {
  stop-color: var(--svg-color--e96d30, #E96D30);
  stop-opacity: 0;
}

.kxzgmzb5t {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.la-4pc5er {
  stop-color: var(--svg-color--fbad41, #FBAD41);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lijeyqbfa {
  width: 0.692px;
  height: 1.157px;
  x: 21.603px;
  y: 3.234px;
  rx: 0.346px;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lr97j31fb {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mt3agfeyc {
  fill: var(--svg-color--afa2b8, #AFA2B8);
  d: path("M8.948 12.591a.35.35 0 0 0-.125.474l.88 1.546a1 1 0 0 1-.373 1.364l-.115.065a1 1 0 0 1-1.364-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.251l.343-.195l16.303-9.709a.4.4 0 0 1 .549.139l.102.172a.4.4 0 0 1-.139.548z");
}

.muua73y8y {
  stop-color: var(--svg-color--f3ae21, #F3AE21);
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nk-zfnbce {
  stop-color: var(--svg-color--ff9550, #FF9550);
  stop-opacity: 0;
}

.ntf44obau {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.872 5.695q.036-.056.108-.14c.099-.107.252-.233.473-.31a.115.115 0 0 1 .075.217a.92.92 0 0 0-.483.39l-.004.007v.002a.115.115 0 0 1-.206-.102z");
}

.ob4ztkbap {
  stop-color: var(--svg-color--eaa22a, #EAA22A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofy-zx6wg {
  stop-color: var(--svg-color--e0611c, #E0611C);
}

.ojy1jndng {
  stop-color: var(--svg-color--ffd540, #FFD540);
}

.olg4dbcpd {
  width: 0.692px;
  height: 1.157px;
  x: 22.173px;
  y: 2.98px;
  rx: 0.346px;
}

.omms1hbxq {
  d: path("m21.765 4.959l-.5-.866l3.121-1.859a.4.4 0 0 1 .549.139l.102.172a.4.4 0 0 1-.14.548z");
}

.oy2bmg2hk {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.236 5.201c.039.02.008.083-.027.153s-.063.119-.102.099c-.04-.02-.042-.093-.006-.162c.035-.07.096-.11.135-.09");
}

.oyg3rwtgg {
  d: path("M12.451 6.264a.666.666 0 0 0 .634 1.164a33 33 0 0 1-.634-1.164");
}

.oykl6nbsu {
  d: path("M15.226 5.12a.37.37 0 0 1 .525.262l-.64.314a.37.37 0 0 1 .116-.576");
}

.p2usq5blt {
  stop-color: var(--svg-color--e96d30, #E96D30);
}

.p3yd_be1u {
  stop-color: var(--svg-color--a49faa, #A49FAA);
  stop-opacity: 0;
}

.p8_7hsp1q {
  d: path("M13.598 3.97a4.15 4.15 0 0 0-1.692 1.805l.379.134a.42.42 0 0 0 .475-.156c.242-.332.67-.841 1.213-1.118c.53-.271 1.194-.362 1.675-.362a.45.45 0 0 0 .448-.349l.064-.332c-.397-.042-1.63-.172-2.562.379");
}

.pcvpzjboo {
  stop-color: var(--svg-color--937da8, #937DA8);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl049mlvn {
  d: path("M8.948 12.591a.35.35 0 0 0-.125.474l.88 1.546a1 1 0 0 1-.373 1.364l-.115.065a1 1 0 0 1-1.364-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.251l.343-.195l16.303-9.709a.4.4 0 0 1 .549.139l.102.172a.4.4 0 0 1-.139.548z");
}

.ps4m-ab9c {
  stop-color: var(--svg-color--827a8b, #827A8B);
  stop-opacity: 0;
}

.ptgqu1bav {
  d: path("M13.089 7.384a.7.7 0 0 1-.393.05l.17.346a.9.9 0 0 0 .866.506a1.7 1.7 0 0 1-.343-.375z");
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q4joo645p {
  fill: var(--svg-color--9785a9, #9785A9);
  d: path("M14.522 23.649a1 1 0 0 0 .275-.712l-.167-7.29h6.02l-.313 12.476h-2.156l-.259-10.002a.255.255 0 0 0-.509-.005c-.049 1.196-.13 3.455-.13 4.585c0 1.213-.693 2.214-1.04 2.563l-2.472 2.287a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.718-.424c-.252-.225-.439-.553-.547-.795a.36.36 0 0 1 .078-.393z");
}

.qc_gmpkqt {
  d: path("m16.695 4.67l-.539-1.078l-.847.047l.648 1.32z");
}

.qe_2d-buv {
  stop-color: var(--svg-color--937da8, #937DA8);
  stop-opacity: 0;
}

.qhy2ocn-y {
  stop-color: var(--svg-color--fc8f4d, #FC8F4D);
}

.qq2dxfbei {
  d: path("m11.586 5.15l.324.625c1.34-1.957 3.175-2.312 4.25-2.172l-.293-.503c-.027-.07-.152-.287-.433-.59c-.581-.547-1.315-.403-1.61-.262l-1.601.82c-.126.065-.43.307-.637.754c-.269.569-.145 1.082 0 1.328");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r387_acpi {
  d: path("M14.049 6.059c-.053-.108-.175-.136-.209-.146l-.056.156l.131.102z");
}

.r46ixy0tk {
  d: path("M15.662 5.262a.35.35 0 0 0-.17-.13l-.044.154l.085.063z");
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rehb2ofun {
  stop-color: var(--svg-color--db7d23, #DB7D23);
}

.rk9ipi4nv {
  stop-color: var(--svg-color--fd9225, #FD9225);
}

.s_3zwkbhw {
  d: path("M14.522 23.649a1 1 0 0 0 .275-.712l-.167-7.29h6.02l-.313 12.476h-2.156l-.259-10.002a.255.255 0 0 0-.509-.005c-.049 1.196-.13 3.455-.13 4.585c0 1.213-.693 2.214-1.04 2.563l-2.472 2.287a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.718-.424c-.252-.225-.439-.553-.547-.795a.36.36 0 0 1 .078-.393z");
}

.s2j02zbkr {
  stop-color: var(--svg-color--655e6d, #655E6D);
  stop-opacity: 0;
}

.s8vaxcyqu {
  stop-color: var(--svg-color--db7d23, #DB7D23);
  stop-opacity: 0;
}

.seeiowbir {
  stop-color: var(--svg-color--482c58, #482C58);
}

.sncm2-ibv {
  stop-color: var(--svg-color--dc5502, #DC5502);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.szwyz5b7x {
  d: path("M15.195 7.111a1.24 1.24 0 0 1-.575.13c-.063 0-.09.083-.035.114a.78.78 0 0 0 .742.026a.78.78 0 0 0 .435-.602c.008-.064-.073-.093-.112-.042c-.11.15-.264.28-.455.374");
}

.t_a14bpou {
  stop-color: var(--svg-color--ffd540, #FFD540);
  stop-opacity: 0;
}

.t-eeezbdl {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
  stop-opacity: 0;
}

.t0-pbfrwb {
  width: 0.692px;
  height: 1.157px;
  x: 21.084px;
  y: 3.48px;
  rx: 0.346px;
}

.t0rt6vb0t {
  d: path("M16.702 5.614a.7.7 0 0 0 .28-.28l.17.347a.9.9 0 0 1-.131.994a1.7 1.7 0 0 0-.086-.501z");
}

.t4j6y4bmp {
  d: path("m16.15 23.256l-.375-5.953l1.062.5v5.453z");
}

.tb4k0qb7o {
  stop-color: var(--svg-color--dc5502, #DC5502);
  stop-opacity: 0;
}

.tcbfrl09k {
  d: path("M16.741 5.637q-.253-.61-.512-1.22a.666.666 0 0 1 .512 1.22");
}

.tcxsyye9l {
  stop-color: var(--svg-color--f78b4b, #F78B4B);
}

.to2qzr-xo {
  d: path("M15.236 5.201c.039.02.008.083-.027.153s-.063.119-.102.099c-.04-.02-.042-.093-.006-.162c.035-.07.096-.11.135-.09");
}

.ttmnipb_u {
  stop-color: var(--svg-color--e28636, #E28636);
}

.tw6dxpb7y {
  stop-color: var(--svg-color--482c58, #482C58);
  stop-opacity: 0;
}

.tzgzt3b1l {
  stop-color: var(--svg-color--bb7701, #BB7701);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.u7tbj0bap {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("m16.638 5.388l-.305-.728a.396.396 0 0 1 .305.728");
}

.usai76iql {
  stop-color: var(--svg-color--fcc540, #FCC540);
}

.uu7_gub8n {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
  stop-opacity: 0;
}

.uxujrsjxl {
  d: path("M13.378 7.94a1.62 1.62 0 0 0 2.064.559l.701-.343a1.62 1.62 0 0 0 .825-1.974c-.3-.721-.597-1.44-.907-2.156a.6.6 0 0 0-.773-.28l-.52.254a1 1 0 0 1-1.085-.134a.275.275 0 0 0-.305-.043l-.473.232a1.39 1.39 0 0 0-.627 1.864c.339.691.715 1.35 1.1 2.022");
}

.uz50sub2c {
  stop-color: var(--svg-color--ff9550, #FF9550);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vkrof_bbk {
  stop-color: var(--svg-color--271938, #271938);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vsa1bkbba {
  stop-color: var(--svg-color--f55e20, #F55E20);
}

.vsfo3yb3y {
  stop-color: var(--svg-color--f3801f, #F3801F);
}

.w5oxhdc5r {
  stop-color: var(--svg-color--7f5d9d, #7F5D9D);
}

.w8xh_8bpw {
  stop-color: var(--svg-color--f47234, #F47234);
  stop-opacity: 0;
}

.wb27l4bhs {
  fill: var(--svg-color--ffc131, #FFC131);
  d: path("M19.317 5.693a.5.5 0 0 0-.015-.254a5 5 0 0 0-.227-.523c-.02-.089-.025-.29.11-.39a.36.36 0 0 1 .336-.055a.45.45 0 0 1 .207-.286c.134-.071.298-.03.363 0c.018-.066.09-.208.23-.246a.52.52 0 0 1 .356.059c.04-.076.169-.224.36-.215c.238.012.374.262.41.45c.035.187.093.433.152.577c.058.145.117.606-.09 1.2h-.001c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.082a1.1 1.1 0 1 1-.193-2.191c.636-.056 1.522-.243 2.304-.744c.682-.437 1.327-1.135 1.66-2.317");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wn-t5ndzy {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.x3vluzbgl {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M15.547 4.435a.8.8 0 0 0-.33-.027c-.131.02-.277.08-.462.2a.115.115 0 1 0 .126.192c.168-.11.283-.152.37-.165a.54.54 0 0 1 .237.022a.115.115 0 1 0 .059-.222");
}

.xhu8yhbcw {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
  stop-opacity: 0;
}

.xi8fv135v {
  stop-color: var(--svg-color--8c7e97, #8C7E97);
  stop-opacity: 0;
}

.xipy-p0qb {
  d: path("M16.001 8.572a2.8 2.8 0 0 0 .848-.215l.859 2.196c-.234.12-1.715.593-2.54.43c-.823-.165-1.018-1.196-.73-1.739c.274-.61 1.119-.63 1.563-.672");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xkamdub3z {
  d: path("M19.317 5.693a.5.5 0 0 0-.015-.254a5 5 0 0 0-.227-.523c-.02-.089-.025-.29.11-.39a.36.36 0 0 1 .336-.055a.45.45 0 0 1 .207-.286c.134-.071.298-.03.363 0c.018-.066.09-.208.23-.246a.52.52 0 0 1 .356.059c.04-.076.169-.224.36-.215c.238.012.374.262.41.45c.035.187.093.433.152.577c.058.145.117.606-.09 1.2h-.001c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.082a1.1 1.1 0 1 1-.193-2.191c.636-.056 1.522-.243 2.304-.744c.682-.437 1.327-1.135 1.66-2.317");
}

.xnk2l2bya {
  d: path("M13.927 9.537c.176-1.285.703-1.862 1-2.07c.51-.358 1.664-.946 3.336 0c1.758 1.094 2.404 4.057 2.375 5.375v2.804h-6v-3.242c0-.487-.106-.742-.258-.96c-.144-.259-.52-.981-.453-1.907");
}

.xzviogqak {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M12.578 6.506a.396.396 0 0 0 .373.684a33 33 0 0 1-.373-.684");
}

.y6ovumr8k {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.ynlfw99ba {
  stop-color: var(--svg-color--403451, #403451);
}

.yqiyodbty {
  stop-color: var(--svg-color--ed3623, #ED3623);
  stop-opacity: 0;
}

.z5cbgecks {
  d: path("M13.603 5.914a.37.37 0 0 0-.115.576l.641-.314a.372.372 0 0 0-.526-.262");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zn47ozbfv {
  stop-color: var(--svg-color--442563, #442563);
  stop-opacity: 0;
}

.zwaguzbxa {
  d: path("m14.396 5.839l.137.78c.028.16.194.253.33.186l.293-.143c.137-.067.164-.258.056-.376l-.532-.587c-.117-.13-.314-.034-.284.14");
}

</style>
