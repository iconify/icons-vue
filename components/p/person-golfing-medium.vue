<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4lWzMe)"><path fill="url(#iYGd1he)" clip-rule="evenodd" class="o35pq7t4o"/></g><g filter="url(#iA3Zo6b)"><path class="dx43b-uen"/><path fill="url(#ixskz7c)" class="b3balxjgh"/><path fill="url(#ijRAjme)" class="b3balxjgh"/></g><path fill="url(#i5wwS4d)" class="b3balxjgh"/><path fill="url(#it0JlNd)" class="q_q2mdexk"/><path fill="url(#ikPAQGL)" class="q_q2mdexk"/><path fill="url(#iWTMgBi)" class="q_q2mdexk"/><g filter="url(#ieuMqjb)"><path class="d-flgfb4a"/></g><path class="hjl_vubvu"/><path fill="url(#iP9cu3c)" class="f56k_mb0a"/><path fill="url(#iPnAc3R)" class="f56k_mb0a"/><path fill="url(#i7ppz6b)" class="f56k_mb0a"/><path fill="url(#id0lf6d)" class="f56k_mb0a"/><g filter="url(#izQe0xe)"><path class="yvaq4pxjp"/></g><path fill="url(#iC35oPd)" class="av8-ehspg"/><path fill="url(#iWfnjGc)" class="av8-ehspg"/><path fill="url(#ixGohNb)" class="av8-ehspg"/><path fill="url(#icSznJb)" class="av8-ehspg"/><path fill="url(#i7KF8iq)" class="av8-ehspg"/><path fill="url(#iPeDGZt)" class="av8-ehspg"/><path fill="url(#iPCYrub)" class="av8-ehspg"/><path fill="url(#ihITLue)" class="d7id56bdx"/><path fill="url(#iihu27c)" class="d7id56bdx"/><path fill="url(#iytrcYG)" class="d7id56bdx"/><path fill="url(#ieAyUQd)" class="d7id56bdx"/><path fill="url(#in5evvb)" class="d7id56bdx"/><rect transform="rotate(-26.783 20.65 3.74)" class="i6salnlin"/><rect fill="url(#iezAU2a)" transform="rotate(-26.783 21.084 3.48)" class="t0-pbfrwb"/><rect fill="url(#iaA41Ce)" transform="rotate(-26.783 21.603 3.234)" class="lijeyqbfa"/><rect fill="url(#isveM6Q)" transform="rotate(-26.783 22.173 2.98)" class="olg4dbcpd"/><rect fill="url(#iHNkimd)" transform="rotate(60 21.976 4.011)" class="f15-arbgd"/><g filter="url(#iYfb9wd)"><path class="q_mhte9yh"/><path fill="url(#iUHT6Pe)" class="s7i7c3btj"/></g><g filter="url(#i5Vk4Ae)"><path fill="url(#izOhSwc)" class="rpikfgw0s"/><path fill="url(#iYiKCbb)" class="rpikfgw0s"/><path fill="url(#iwaj5De)" class="rpikfgw0s"/></g><path fill="url(#io0cIjB)" class="t0rt6vb0t"/><path fill="url(#iC9mwJc)" class="ruaexvb-c"/><path class="ojumjsbme"/><path fill="url(#iguQw4d)" class="uxujrsjxl"/><path fill="url(#imen7ve)" class="uxujrsjxl"/><path fill="url(#iC1N7kA)" class="uxujrsjxl"/><path fill="url(#iRWUoRb)" class="uxujrsjxl"/><path fill="url(#iPewCwe)" class="uxujrsjxl"/><g filter="url(#i6WkMQe)"><path class="i0r-hkjxe"/></g><g filter="url(#iMUzB3Y)"><path class="i1maylb9n"/><path fill="url(#iDMpkmb)" class="nciqb6blm"/><path fill="url(#iDvevXc)" class="nciqb6blm"/></g><path class="oyo74lsbl"/><g filter="url(#iFnCKAc)"><path class="ew34cdb8d"/></g><g filter="url(#irFXnld)"><path class="f7_9_wbdl"/></g><path class="fs37d7b0x"/><path fill="url(#iCtZNJe)" class="oykl6nbsu"/><path class="f5hwfh_qp"/><g filter="url(#iKYMKWd)"><path class="i3meegbgh"/><path fill="url(#i3ya5gb)" class="ndoa1s_vo"/></g><g filter="url(#iozey5d)"><path fill="url(#iLKTPSM)" class="a-zm8mmii"/></g><path class="gndrvcqfc"/><path fill="url(#iau8Qte)" class="z5cbgecks"/><path class="jhlegmjip"/><g filter="url(#ibhZE8o)"><path fill="url(#i38MsLb)" class="r387_acpi"/></g><g filter="url(#iftd9qe)"><ellipse transform="rotate(-54.009 13.572 6.105)" class="ks0g04c0s"/><ellipse fill="url(#iev5hwd)" transform="rotate(-54.009 13.572 6.105)" class="hob_weexg"/></g><path fill="url(#iwl4zie)" class="tcbfrl09k"/><path class="cg6r0gbcf"/><g filter="url(#iyhkNsb)"><path class="d5zn5lbsm"/></g><g filter="url(#isb7qQb)"><path fill="url(#izzdqyh)" class="v-xq24nys"/></g><path fill="url(#iMvzFIe)" class="swmrirlin"/><path fill="url(#ibAy9od)" class="swmrirlin"/><path fill="url(#i94xqJc)" class="swmrirlin"/><path fill="url(#iV3WF4r)" class="swmrirlin"/><g filter="url(#ijepCrb)"><path fill="url(#iNNgYxb)" class="d9qjrccow"/><path fill="url(#itfeErb)" class="d9qjrccow"/></g><g filter="url(#iSS136b)"><path class="cyj_-hvmj"/></g><g filter="url(#iff0gTc)"><path stroke="url(#ivaDZRG)" class="huh1sac2a"/></g><g filter="url(#iuhjB4d)"><path fill="url(#iUbjRRb)" class="t4j6y4bmp"/></g><defs><radialGradient id="ixskz7c" cx="0" cy="0" r="1" gradientTransform="rotate(146.915 8.826 5.736)scale(4.92324 2.04943)" gradientUnits="userSpaceOnUse"><stop class="ba1yb3bji"/><stop offset="1" class="kgrhzo17p"/></radialGradient><radialGradient id="i5wwS4d" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -.0625 .23626 5.43402 6.51 13.318)" gradientUnits="userSpaceOnUse"><stop class="wn-t5ndzy"/><stop offset="1" class="ben4f0bqs"/></radialGradient><radialGradient id="iWTMgBi" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .16016 -.21807 -.37232 24.841 2.572)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="i42zc8m6u"/><stop offset="1" class="dsumrvbgt"/></radialGradient><radialGradient id="iPnAc3R" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 -.46876 .24583 -.45888 14.135 29.178)" gradientUnits="userSpaceOnUse"><stop class="ynlfw99ba"/><stop offset="1" class="in-vfpgwh"/></radialGradient><radialGradient id="i7ppz6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .85157 -1.15842 -1.0415 12.743 26.67)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="vkrof_bbk"/><stop offset="1" class="h8hiq33uv"/></radialGradient><radialGradient id="id0lf6d" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 .15625 -.58594 3.04687 11.368 28.068)" gradientUnits="userSpaceOnUse"><stop class="ilg8l_bzj"/><stop offset="1" class="s2j02zbkr"/></radialGradient><radialGradient id="iWfnjGc" cx="0" cy="0" r="1" gradientTransform="matrix(2.71873 -2.53127 .81258 .87276 13.166 27.631)" gradientUnits="userSpaceOnUse"><stop class="pcvpzjboo"/><stop offset="1" class="qe_2d-buv"/></radialGradient><radialGradient id="ixGohNb" cx="0" cy="0" r="1" gradientTransform="matrix(2.54688 -2.64063 .2894 .27913 12.275 25.975)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="kxzgmzb5t"/><stop offset="1" class="xhu8yhbcw"/></radialGradient><radialGradient id="icSznJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 0 0 -5.02098 17.369 21.318)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="keljo6scd"/><stop offset="1" class="ps4m-ab9c"/></radialGradient><radialGradient id="i7KF8iq" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 -.98437 1.15192 .05485 17.619 17.99)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="w5oxhdc5r"/><stop offset="1" class="ebs2-pbbe"/></radialGradient><radialGradient id="iPeDGZt" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 0 0 7.6823 17.978 22.678)" gradientUnits="userSpaceOnUse"><stop class="j_l_30buh"/><stop offset="1" class="xi8fv135v"/></radialGradient><radialGradient id="iPCYrub" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -3.34375 1.20794 1.23052 13.666 27.693)" gradientUnits="userSpaceOnUse"><stop class="ddjhanboc"/><stop offset="1" class="uu7_gub8n"/></radialGradient><radialGradient id="ihITLue" cx="0" cy="0" r="1" gradientTransform="rotate(150.356 8.617 7.45)scale(4.42262 6.15908)" gradientUnits="userSpaceOnUse"><stop class="bcesubcjx"/><stop offset="1" class="vsa1bkbba"/></radialGradient><radialGradient id="iihu27c" cx="0" cy="0" r="1" gradientTransform="matrix(.57404 2.73801 -4.6268 .97003 17.28 6.955)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="cq96abbmk"/><stop offset="1" class="ifjstwbmn"/></radialGradient><radialGradient id="ieAyUQd" cx="0" cy="0" r="1" gradientTransform="matrix(.87501 1.59375 -2.6006 1.4278 15.29 7.661)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="sncm2-ibv"/><stop offset="1" class="tb4k0qb7o"/></radialGradient><radialGradient id="in5evvb" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.01563 .0588 6.46896 13.478 10.068)" gradientUnits="userSpaceOnUse"><stop class="qhy2ocn-y"/><stop offset="1" class="g59b8gbml"/></radialGradient><radialGradient id="iezAU2a" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 21.76 4.148)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="wi0s78byb"/><stop offset="1" class="ek04q5utg"/></radialGradient><radialGradient id="iaA41Ce" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.28 3.902)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="wi0s78byb"/><stop offset="1" class="ek04q5utg"/></radialGradient><radialGradient id="isveM6Q" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.849 3.648)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="wi0s78byb"/><stop offset="1" class="ek04q5utg"/></radialGradient><radialGradient id="iHNkimd" cx="0" cy="0" r="1" gradientTransform="matrix(-.02457 .47352 -.46721 -.02424 22.369 4.163)" gradientUnits="userSpaceOnUse"><stop class="m899xdb7p"/><stop offset="1" class="w2kim8kci"/></radialGradient><radialGradient id="iUHT6Pe" cx="0" cy="0" r="1" gradientTransform="matrix(3.80388 .30087 -.62375 7.88601 17.576 5.303)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="ktyh3bczo"/><stop offset="1" class="oqkg5ybwb"/></radialGradient><radialGradient id="iYiKCbb" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 .21242 -.56203 4.5475 14.04 9.475)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="tcxsyye9l"/><stop offset="1" class="e2fjo6nwd"/></radialGradient><radialGradient id="iwaj5De" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 .51562 -1.9883 .18075 16.181 8.459)" gradientUnits="userSpaceOnUse"><stop class="gq6wqmsky"/><stop offset="1" class="cci816eoj"/></radialGradient><radialGradient id="io0cIjB" cx="0" cy="0" r="1" gradientTransform="rotate(70.692 4.727 14.724)scale(1.06983 .40552)" gradientUnits="userSpaceOnUse"><stop class="gvs-qobyl"/><stop offset="1" class="c-v5xcbcc"/></radialGradient><radialGradient id="iC9mwJc" cx="0" cy="0" r="1" gradientTransform="rotate(57.119 -.57 15.43)scale(1.06983 .40552)" gradientUnits="userSpaceOnUse"><stop class="g9fnh9b8t"/><stop offset="1" class="zc_zi9bsd"/></radialGradient><radialGradient id="iguQw4d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18417 1.2895 -1.2047 -2.04054 15.711 5.524)" gradientUnits="userSpaceOnUse"><stop class="e7a4a2pip"/><stop offset="1" class="qp3_hhk8k"/></radialGradient><radialGradient id="imen7ve" cx="0" cy="0" r="1" gradientTransform="rotate(100.766 5.175 7.9)scale(3.76401 2.46208)" gradientUnits="userSpaceOnUse"><stop class="li-yvmb5b"/><stop offset="1" class="x-4til4cq"/></radialGradient><radialGradient id="iC1N7kA" cx="0" cy="0" r="1" gradientTransform="matrix(1.10749 2.6875 -3.06922 1.2648 14.685 5.761)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="rhkht6bvz"/><stop offset="1" class="lbua0entw"/></radialGradient><radialGradient id="iRWUoRb" cx="0" cy="0" r="1" gradientTransform="rotate(62.738 1.393 12.857)scale(3.4452 1.00393)" gradientUnits="userSpaceOnUse"><stop class="tn8g7itkp"/><stop offset="1" class="hbrr-2qzx"/></radialGradient><radialGradient id="iPewCwe" cx="0" cy="0" r="1" gradientTransform="rotate(69.157 5.165 13.807)scale(2.54705 .99902)" gradientUnits="userSpaceOnUse"><stop class="t0zt74bsq"/><stop offset="1" class="j88pg0b8q"/></radialGradient><radialGradient id="iDMpkmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.35925 .16406 -.0934 -.20454 15.105 6.399)" gradientUnits="userSpaceOnUse"><stop class="rwim96b5d"/><stop offset="1" class="uh3drfs9c"/></radialGradient><radialGradient id="iCtZNJe" cx="0" cy="0" r="1" gradientTransform="matrix(.14768 .30153 -.47962 .2349 15.312 5.297)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i3ya5gb" cx="0" cy="0" r="1" gradientTransform="rotate(-153.907 8.243 .919)scale(.15655 .21553)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iau8Qte" cx="0" cy="0" r="1" gradientTransform="matrix(.1477 .30155 -.47965 .23492 13.69 6.091)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iev5hwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0032 -.20447 .24578 -.00385 13.566 6.235)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwl4zie" cx="0" cy="0" r="1" gradientTransform="matrix(.54297 -.30469 .4255 .75825 16.45 5.09)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="xbwvi596r"/><stop offset="1" class="rvgkuivfc"/></radialGradient><radialGradient id="izzdqyh" cx="0" cy="0" r="1" gradientTransform="matrix(-.24042 .13052 -.1998 -.36806 16.733 4.874)" gradientUnits="userSpaceOnUse"><stop class="qntn7vn0o"/><stop offset="1" class="u0qlugq6d"/></radialGradient><radialGradient id="iMvzFIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.32812 2.10937 -2.73038 -.42473 14.445 2.615)" gradientUnits="userSpaceOnUse"><stop class="rk9ipi4nv"/><stop offset=".816" class="d3ckukbai"/></radialGradient><radialGradient id="ibAy9od" cx="0" cy="0" r="1" gradientTransform="matrix(1.40625 .10938 -.30588 3.93273 11.586 4.74)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="uz50sub2c"/><stop offset="1" class="nk-zfnbce"/></radialGradient><radialGradient id="i94xqJc" cx="0" cy="0" r="1" gradientTransform="rotate(-113.839 8.595 -2.223)scale(1.46908 2.89909)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="e32fiwbxk"/><stop offset="1" class="w8xh_8bpw"/></radialGradient><radialGradient id="iV3WF4r" cx="0" cy="0" r="1" gradientTransform="matrix(.23438 .5625 -2.67897 1.11624 12.96 2.615)" gradientUnits="userSpaceOnUse"><stop class="ttmnipb_u"/><stop offset="1" class="g5vhmeb9a"/></radialGradient><radialGradient id="iNNgYxb" cx="0" cy="0" r="1" gradientTransform="matrix(3.26562 -1.07812 1.92394 5.82757 12.586 5.38)" gradientUnits="userSpaceOnUse"><stop class="ax7c_wbux"/><stop offset="1" class="ofy-zx6wg"/></radialGradient><radialGradient id="itfeErb" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.5 .86462 .09907 15.133 4.162)" gradientUnits="userSpaceOnUse"><stop class="p2usq5blt"/><stop offset="1" class="kxozdy23r"/></radialGradient><filter id="i4lWzMe" width="8.471" height="7.176" x="16.221" y="3.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.45098 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22709" result="effect2_innerShadow_3987_22709"/></filter><filter id="iA3Zo6b" width="18.187" height="14.194" x="6.907" y="1.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22709"/></filter><filter id="ieuMqjb" width="4.793" height="2.27" x="18.177" y="27.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.188235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22709"/></filter><filter id="izQe0xe" width="8.989" height="12.477" x="12.161" y="15.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.635294 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22709"/></filter><filter id="iYfb9wd" width="7.553" height="7.567" x="14.351" y="3.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.392157 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.423529 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22709" result="effect2_innerShadow_3987_22709"/></filter><filter id="i5Vk4Ae" width="3.395" height="2.909" x="14.313" y="8.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.341176 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22709"/></filter><filter id="i6WkMQe" width="1.348" height="1.693" x="14.139" y="5.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".125"/></filter><filter id="iMUzB3Y" width="1.086" height="1.388" x="14.293" y="5.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".05"/></filter><filter id="iFnCKAc" width="1.029" height=".618" x="14.703" y="4.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0509804 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22709"/></filter><filter id="irFXnld" width=".882" height=".886" x="12.823" y="5.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0509804 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22709"/></filter><filter id="iKYMKWd" width=".379" height=".461" x="14.976" y="5.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".05"/></filter><filter id="iozey5d" width=".614" height=".616" x="15.248" y="4.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".1"/></filter><filter id="ibhZE8o" width=".665" height=".658" x="13.584" y="5.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".1"/></filter><filter id="iftd9qe" width=".431" height=".478" x="13.356" y="5.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".05"/></filter><filter id="iyhkNsb" width=".721" height=".904" x="12.33" y="6.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".05"/></filter><filter id="isb7qQb" width=".66" height=".858" x="16.248" y="4.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".05"/></filter><filter id="ijepCrb" width="4.253" height="2.433" x="11.907" y="3.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22709"/></filter><filter id="iSS136b" width="1.789" height="3.497" x="8.087" y="12.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".125"/></filter><filter id="iff0gTc" width="2.601" height="13.601" x="18.427" y="15.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".4"/></filter><filter id="iuhjB4d" width="2.563" height="7.453" x="15.025" y="16.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22709" stdDeviation=".375"/></filter><linearGradient id="iYGd1he" x1="23.013" x2="19.956" y1="4.744" y2="10.749" gradientUnits="userSpaceOnUse"><stop class="lg6xcac6n"/><stop offset=".799" class="hb081ceky"/></linearGradient><linearGradient id="ijRAjme" x1="12.493" x2="12.822" y1="9.174" y2="9.646" gradientUnits="userSpaceOnUse"><stop offset=".349" class="lr97j31fb"/><stop offset="1" class="azn0z--js"/></linearGradient><linearGradient id="it0JlNd" x1="24.916" x2="22.775" y1="2.693" y2="4.006" gradientUnits="userSpaceOnUse"><stop class="ds3hm--8v"/><stop offset="1" class="bq7w62n5j"/></linearGradient><linearGradient id="ikPAQGL" x1="23.884" x2="23.619" y1="3.693" y2="3.162" gradientUnits="userSpaceOnUse"><stop class="seeiowbir"/><stop offset="1" class="tw6dxpb7y"/></linearGradient><linearGradient id="iP9cu3c" x1="12.697" x2="12.697" y1="30.029" y2="29.357" gradientUnits="userSpaceOnUse"><stop class="dhem-xbnm"/><stop offset="1" class="zn47ozbfv"/></linearGradient><linearGradient id="iC35oPd" x1="20.478" x2="19.884" y1="22.568" y2="22.537" gradientUnits="userSpaceOnUse"><stop class="ieaclmdnn"/><stop offset="1" class="p3yd_be1u"/></linearGradient><linearGradient id="iytrcYG" x1="17.279" x2="17.279" y1="15.975" y2="12.787" gradientUnits="userSpaceOnUse"><stop offset=".039" class="ju1sfx7jc"/><stop offset="1" class="yqiyodbty"/></linearGradient><linearGradient id="izOhSwc" x1="16.011" x2="16.011" y1="8.357" y2="10.568" gradientUnits="userSpaceOnUse"><stop class="vsfo3yb3y"/><stop offset="1" class="dos09sbbm"/></linearGradient><linearGradient id="iDvevXc" x1="14.504" x2="14.699" y1="6.589" y2="6.526" gradientUnits="userSpaceOnUse"><stop class="rp7vy4bao"/><stop offset="1" class="j-lca9mxk"/></linearGradient><linearGradient id="iLKTPSM" x1="15.61" x2="15.529" y1="5.175" y2="5.304" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i38MsLb" x1="13.976" x2="13.895" y1="5.976" y2="6.105" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivaDZRG" x1="19.744" x2="19.744" y1="16.6" y2="27.506" gradientUnits="userSpaceOnUse"><stop class="hd06b2knh"/><stop offset="1" class="ggughpb3d"/></linearGradient><linearGradient id="iUbjRRb" x1="16.306" x2="16.306" y1="18.037" y2="24.6" gradientUnits="userSpaceOnUse"><stop class="y6ovumr8k"/><stop offset="1" class="t-eeezbdl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-golfing-medium" /></template>
<style>
.a-zm8mmii {
  d: path("M15.662 5.262a.35.35 0 0 0-.17-.13l-.044.154l.084.063z");
}

.av8-ehspg {
  d: path("M14.522 23.649a1 1 0 0 0 .275-.712l-.167-7.29h6.02l-.312 12.476H18.18l-.259-10.002a.255.255 0 0 0-.509-.005c-.049 1.196-.13 3.455-.13 4.585c0 1.213-.693 2.214-1.04 2.563l-2.472 2.287a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.718-.424c-.252-.225-.439-.553-.547-.795a.36.36 0 0 1 .078-.393z");
}

.ax7c_wbux {
  stop-color: var(--svg-color--ef7849, #EF7849);
}

.azn0z--js {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
  stop-opacity: 0;
}

.b3balxjgh {
  d: path("M8.948 12.591a.35.35 0 0 0-.125.474l.88 1.546a1 1 0 0 1-.373 1.364l-.115.065a1 1 0 0 1-1.364-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.251l.343-.195l16.303-9.709a.4.4 0 0 1 .549.139l.102.172a.4.4 0 0 1-.14.548z");
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

.bq7w62n5j {
  stop-color: var(--svg-color--482a5b, #482A5B);
}

.c-v5xcbcc {
  stop-color: var(--svg-color--2a1e1f, #2A1E1F);
}

.cci816eoj {
  stop-color: var(--svg-color--e36512, #E36512);
  stop-opacity: 0;
}

.cg6r0gbcf {
  fill: var(--svg-color--995f66, #995F66);
  d: path("M12.451 6.264a.666.666 0 0 0 .634 1.164a33 33 0 0 1-.634-1.164");
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

.d-flgfb4a {
  fill: var(--svg-color--4c3765, #4C3765);
  d: path("M18.177 29.88v-1.769h2.16c.164.157.79.551 1.504.782c.494.13.625.488.63.62v.368z");
}

.d3ckukbai {
  stop-color: var(--svg-color--f98841, #F98841);
}

.d5zn5lbsm {
  fill: var(--svg-color--925f5a, #925F5A);
  d: path("M12.578 6.506a.395.395 0 0 0 .373.684a32 32 0 0 1-.373-.684");
}

.d7id56bdx {
  d: path("M13.927 9.537c.176-1.285.703-1.862 1-2.07c.51-.358 1.664-.946 3.336 0c1.758 1.094 2.404 4.057 2.375 5.375v2.804h-6v-3.242c0-.487-.105-.742-.258-.96c-.144-.259-.52-.981-.453-1.907");
}

.d9qjrccow {
  d: path("M13.598 3.97a4.15 4.15 0 0 0-1.691 1.805l.378.134a.42.42 0 0 0 .476-.156c.24-.332.669-.841 1.212-1.118c.53-.271 1.194-.362 1.675-.362a.45.45 0 0 0 .448-.349l.064-.332c-.397-.042-1.629-.172-2.562.379");
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

.dx43b-uen {
  fill: var(--svg-color--afa2b8, #AFA2B8);
  d: path("M8.948 12.591a.35.35 0 0 0-.125.474l.88 1.546a1 1 0 0 1-.373 1.364l-.115.065a1 1 0 0 1-1.364-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.251l.343-.195l16.303-9.709a.4.4 0 0 1 .549.139l.102.172a.4.4 0 0 1-.14.548z");
}

.e2fjo6nwd {
  stop-color: var(--svg-color--f78b4b, #F78B4B);
  stop-opacity: 0;
}

.e32fiwbxk {
  stop-color: var(--svg-color--f47234, #F47234);
}

.e7a4a2pip {
  stop-color: var(--svg-color--bb9076, #BB9076);
}

.ebs2-pbbe {
  stop-color: var(--svg-color--9c8cad, #9C8CAD);
  stop-opacity: 0;
}

.ek04q5utg {
  stop-color: var(--svg-color--9d735f, #9D735F);
}

.ew34cdb8d {
  fill: var(--svg-color--181116, #181116);
  d: path("M15.547 4.435a.8.8 0 0 0-.33-.027c-.13.02-.277.08-.461.2a.115.115 0 0 0 .125.192c.168-.11.283-.152.37-.165a.54.54 0 0 1 .237.022a.115.115 0 0 0 .059-.222");
}

.f15-arbgd {
  width: 0.737px;
  height: 1.252px;
  x: 21.976px;
  y: 4.011px;
  rx: 0.369px;
}

.f56k_mb0a {
  d: path("M11.595 27.49c0-.806.458-1.159.688-1.234l1.367 1.18v1.283a.5.5 0 0 0 .187.39l.203.162c.128.094.297.239.25.415c-.082.171-.25.195-.539.195h-1.506a.65.65 0 0 1-.65-.65z");
}

.f5hwfh_qp {
  fill: var(--svg-color--000, #000);
  d: path("M15.199 5.544a.21.21 0 0 1 .096-.283a.21.21 0 0 1 .305.195l-.336.164a.2.2 0 0 1-.066-.076");
}

.f7_9_wbdl {
  fill: var(--svg-color--181116, #181116);
  d: path("M12.872 5.695q.036-.056.108-.14c.099-.107.252-.233.473-.31a.115.115 0 0 1 .075.217a.92.92 0 0 0-.483.39l-.004.007v.002a.115.115 0 0 1-.206-.102z");
}

.fs37d7b0x {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.254 4.98a.58.58 0 0 1 .696.147a.113.113 0 0 1-.038.176l-.829.406a.095.095 0 0 1-.134-.06a.58.58 0 0 1 .305-.669");
}

.ft5dv1b6b {
  fill: none;
}

.g59b8gbml {
  stop-color: var(--svg-color--fc8f4d, #FC8F4D);
  stop-opacity: 0;
}

.g5vhmeb9a {
  stop-color: var(--svg-color--e28636, #E28636);
  stop-opacity: 0;
}

.g9fnh9b8t {
  stop-color: var(--svg-color--503f40, #503F40);
}

.ggughpb3d {
  stop-color: var(--svg-color--a599b3, #A599B3);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gndrvcqfc {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.476 5.85a.58.58 0 0 0-.31.641c.015.073.095.11.161.078l.83-.406a.095.095 0 0 0 .034-.143a.58.58 0 0 0-.715-.17");
}

.gq6wqmsky {
  stop-color: var(--svg-color--e36512, #E36512);
}

.gvs-qobyl {
  stop-color: var(--svg-color--403433, #403433);
}

.h8hiq33uv {
  stop-color: var(--svg-color--271938, #271938);
  stop-opacity: 0;
}

.hb081ceky {
  stop-color: var(--svg-color--a06f69, #A06F69);
}

.hbrr-2qzx {
  stop-color: var(--svg-color--ba8a7b, #BA8A7B);
  stop-opacity: 0;
}

.hd06b2knh {
  stop-color: var(--svg-color--a89eb3, #A89EB3);
}

.hjl_vubvu {
  fill: var(--svg-color--47385d, #47385D);
  d: path("M11.595 27.49c0-.806.458-1.159.688-1.234l1.367 1.18v1.283a.5.5 0 0 0 .187.39l.203.162c.128.094.297.239.25.415c-.082.171-.25.195-.539.195h-1.506a.65.65 0 0 1-.65-.65z");
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

.i0r-hkjxe {
  fill: var(--svg-color--a06a67, #A06A67);
  d: path("m14.393 5.93l.099.799c.028.16.194.253.33.186l.293-.143c.137-.067.164-.257.056-.376l-.532-.586c-.117-.13-.276-.053-.246.12");
}

.i1maylb9n {
  fill: var(--svg-color--aa7764, #AA7764);
  d: path("m14.396 5.839l.137.78c.028.16.194.253.331.186l.292-.143c.137-.067.164-.258.056-.376l-.532-.587c-.117-.13-.314-.034-.284.14");
}

.i3meegbgh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.236 5.201c.04.02.009.083-.027.152c-.036.07-.063.12-.102.1s-.042-.093-.006-.162c.035-.07.096-.11.135-.09");
}

.i42zc8m6u {
  stop-color: var(--svg-color--615273, #615273);
}

.i6salnlin {
  width: 0.692px;
  height: 1.157px;
  x: 20.651px;
  y: 3.74px;
  fill: var(--svg-color--8c6a54, #8C6A54);
  rx: 0.346px;
}

.ieaclmdnn {
  stop-color: var(--svg-color--a19ca8, #A19CA8);
}

.ifjstwbmn {
  stop-color: var(--svg-color--e27318, #E27318);
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

.j-lca9mxk {
  stop-color: var(--svg-color--af8073, #AF8073);
  stop-opacity: 0;
}

.j88pg0b8q {
  stop-color: var(--svg-color--bf9a7f, #BF9A7F);
  stop-opacity: 0;
}

.jhlegmjip {
  fill: var(--svg-color--000, #000);
  d: path("M13.955 6.153a.21.21 0 0 0-.283-.097a.21.21 0 0 0-.033.36l.336-.165a.2.2 0 0 0-.02-.098");
}

.ju1sfx7jc {
  stop-color: var(--svg-color--ed3623, #ED3623);
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

.ktyh3bczo {
  stop-color: var(--svg-color--bc9581, #BC9581);
  stop-opacity: 0;
}

.kxozdy23r {
  stop-color: var(--svg-color--e96d30, #E96D30);
  stop-opacity: 0;
}

.kxzgmzb5t {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
}

.lbua0entw {
  stop-color: var(--svg-color--8d4c36, #8D4C36);
}

.lg6xcac6n {
  stop-color: var(--svg-color--b18a79, #B18A79);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li-yvmb5b {
  stop-color: var(--svg-color--904f52, #904F52);
}

.lijeyqbfa {
  width: 0.692px;
  height: 1.157px;
  x: 21.603px;
  y: 3.234px;
  rx: 0.346px;
}

.lr97j31fb {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
}

.m899xdb7p {
  stop-color: var(--svg-color--af8c7d, #AF8C7D);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.nciqb6blm {
  d: path("m14.396 5.839l.137.78c.028.16.194.253.331.186l.292-.143c.137-.067.164-.258.056-.376l-.532-.587c-.117-.13-.314-.034-.284.14");
}

.ndoa1s_vo {
  d: path("M15.236 5.201c.04.02.009.083-.027.152c-.036.07-.063.12-.102.1s-.042-.093-.006-.162c.035-.07.096-.11.135-.09");
}

.nk-zfnbce {
  stop-color: var(--svg-color--ff9550, #FF9550);
  stop-opacity: 0;
}

.o35pq7t4o {
  fill-rule: evenodd;
  d: path("M20.961 7.482c.852-1.083.481-2.214.22-2.678l1.915-1.081c.467.828 1.242 3.027-.406 5.12c-.89 1.13-2.33 1.566-3.484 1.752c-1.198.194-2.37.159-2.985.135l.084-2.198c.599.023 1.583.047 2.55-.109c1.012-.163 1.746-.484 2.106-.941");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofy-zx6wg {
  stop-color: var(--svg-color--e0611c, #E0611C);
}

.ojumjsbme {
  fill: var(--svg-color--3a3135, #3A3135);
  d: path("m12.46 6.81l-.538-1.039l.449-.671l.715 1.062zm4.235-2.14l-.539-1.078l-.847.047l.648 1.32z");
}

.olg4dbcpd {
  width: 0.692px;
  height: 1.157px;
  x: 22.173px;
  y: 2.98px;
  rx: 0.346px;
}

.oqkg5ybwb {
  stop-color: var(--svg-color--bc9581, #BC9581);
}

.oykl6nbsu {
  d: path("M15.226 5.12a.37.37 0 0 1 .525.262l-.64.314a.37.37 0 0 1 .116-.576");
}

.oyo74lsbl {
  fill: var(--svg-color--89004e, #89004E);
  d: path("M15.195 7.111a1.24 1.24 0 0 1-.574.13c-.064 0-.09.083-.036.114a.78.78 0 0 0 .743.026a.78.78 0 0 0 .434-.602c.009-.064-.073-.093-.112-.042c-.11.15-.264.28-.455.374");
}

.p2usq5blt {
  stop-color: var(--svg-color--e96d30, #E96D30);
}

.p3yd_be1u {
  stop-color: var(--svg-color--a49faa, #A49FAA);
  stop-opacity: 0;
}

.pcvpzjboo {
  stop-color: var(--svg-color--937da8, #937DA8);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ps4m-ab9c {
  stop-color: var(--svg-color--827a8b, #827A8B);
  stop-opacity: 0;
}

.q_mhte9yh {
  fill: var(--svg-color--a37b6b, #A37B6B);
  d: path("M19.317 5.693a.5.5 0 0 0-.015-.254a5 5 0 0 0-.227-.523c-.02-.089-.025-.29.11-.39a.36.36 0 0 1 .336-.055a.45.45 0 0 1 .207-.286c.134-.071.298-.03.363 0c.018-.066.09-.208.23-.246a.52.52 0 0 1 .356.059c.04-.076.169-.224.36-.215c.238.012.374.262.41.45c.035.187.093.433.152.577c.058.145.117.606-.09 1.2h-.001c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.082a1.1 1.1 0 1 1-.193-2.191c.636-.056 1.522-.243 2.304-.744c.683-.437 1.327-1.135 1.66-2.317");
}

.q_q2mdexk {
  d: path("m21.765 4.959l-.5-.866l3.122-1.859a.4.4 0 0 1 .548.139l.102.172a.4.4 0 0 1-.139.548z");
}

.qe_2d-buv {
  stop-color: var(--svg-color--937da8, #937DA8);
  stop-opacity: 0;
}

.qhy2ocn-y {
  stop-color: var(--svg-color--fc8f4d, #FC8F4D);
}

.qntn7vn0o {
  stop-color: var(--svg-color--a68370, #A68370);
}

.qp3_hhk8k {
  stop-color: var(--svg-color--a87870, #A87870);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r387_acpi {
  d: path("M14.049 6.059c-.053-.108-.175-.136-.209-.146l-.056.156l.131.102z");
}

.rhkht6bvz {
  stop-color: var(--svg-color--a66e68, #A66E68);
  stop-opacity: 0;
}

.rk9ipi4nv {
  stop-color: var(--svg-color--fd9225, #FD9225);
}

.rp7vy4bao {
  stop-color: var(--svg-color--af8073, #AF8073);
}

.rpikfgw0s {
  d: path("M16.001 8.572c.328-.031.652-.125.848-.215l.86 2.196c-.235.12-1.716.593-2.54.43c-.824-.165-1.02-1.196-.73-1.739c.273-.61 1.118-.63 1.562-.672");
}

.ruaexvb-c {
  d: path("M13.089 7.384a.7.7 0 0 1-.392.05l.17.346c.162.332.504.53.865.506a1.7 1.7 0 0 1-.343-.375z");
}

.rvgkuivfc {
  stop-color: var(--svg-color--b08f7c, #B08F7C);
}

.rwim96b5d {
  stop-color: var(--svg-color--b99182, #B99182);
}

.s2j02zbkr {
  stop-color: var(--svg-color--655e6d, #655E6D);
  stop-opacity: 0;
}

.s7i7c3btj {
  d: path("M19.317 5.693a.5.5 0 0 0-.015-.254a5 5 0 0 0-.227-.523c-.02-.089-.025-.29.11-.39a.36.36 0 0 1 .336-.055a.45.45 0 0 1 .207-.286c.134-.071.298-.03.363 0c.018-.066.09-.208.23-.246a.52.52 0 0 1 .356.059c.04-.076.169-.224.36-.215c.238.012.374.262.41.45c.035.187.093.433.152.577c.058.145.117.606-.09 1.2h-.001c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.082a1.1 1.1 0 1 1-.193-2.191c.636-.056 1.522-.243 2.304-.744c.683-.437 1.327-1.135 1.66-2.317");
}

.seeiowbir {
  stop-color: var(--svg-color--482c58, #482C58);
}

.sncm2-ibv {
  stop-color: var(--svg-color--dc5502, #DC5502);
}

.swmrirlin {
  d: path("m11.586 5.15l.324.625c1.34-1.957 3.175-2.312 4.25-2.172l-.293-.503c-.027-.07-.152-.287-.433-.59c-.582-.547-1.315-.403-1.61-.262l-1.601.82c-.127.065-.43.307-.637.754c-.269.569-.145 1.082 0 1.328");
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

.t0zt74bsq {
  stop-color: var(--svg-color--bf9a7f, #BF9A7F);
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

.tn8g7itkp {
  stop-color: var(--svg-color--ba8a7b, #BA8A7B);
}

.ttmnipb_u {
  stop-color: var(--svg-color--e28636, #E28636);
}

.tw6dxpb7y {
  stop-color: var(--svg-color--482c58, #482C58);
  stop-opacity: 0;
}

.u0qlugq6d {
  stop-color: var(--svg-color--9d7660, #9D7660);
}

.uh3drfs9c {
  stop-color: var(--svg-color--b99182, #B99182);
  stop-opacity: 0;
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

.v-xq24nys {
  d: path("m16.617 5.345l-.268-.64a.348.348 0 0 1 .268.64");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vkrof_bbk {
  stop-color: var(--svg-color--271938, #271938);
}

.vsa1bkbba {
  stop-color: var(--svg-color--f55e20, #F55E20);
}

.vsfo3yb3y {
  stop-color: var(--svg-color--f3801f, #F3801F);
}

.w2kim8kci {
  stop-color: var(--svg-color--a78068, #A78068);
}

.w5oxhdc5r {
  stop-color: var(--svg-color--7f5d9d, #7F5D9D);
}

.w8xh_8bpw {
  stop-color: var(--svg-color--f47234, #F47234);
  stop-opacity: 0;
}

.wi0s78byb {
  stop-color: var(--svg-color--b49180, #B49180);
}

.wn-t5ndzy {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
}

.x-4til4cq {
  stop-color: var(--svg-color--9b626a, #9B626A);
  stop-opacity: 0;
}

.xbwvi596r {
  stop-color: var(--svg-color--9c7158, #9C7158);
}

.xhu8yhbcw {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
  stop-opacity: 0;
}

.xi8fv135v {
  stop-color: var(--svg-color--8c7e97, #8C7E97);
  stop-opacity: 0;
}

.y6ovumr8k {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
}

.ynlfw99ba {
  stop-color: var(--svg-color--403451, #403451);
}

.yqiyodbty {
  stop-color: var(--svg-color--ed3623, #ED3623);
  stop-opacity: 0;
}

.yvaq4pxjp {
  fill: var(--svg-color--9785a9, #9785A9);
  d: path("M14.522 23.649a1 1 0 0 0 .275-.712l-.167-7.29h6.02l-.312 12.476H18.18l-.259-10.002a.255.255 0 0 0-.509-.005c-.049 1.196-.13 3.455-.13 4.585c0 1.213-.693 2.214-1.04 2.563l-2.472 2.287a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.718-.424c-.252-.225-.439-.553-.547-.795a.36.36 0 0 1 .078-.393z");
}

.z5cbgecks {
  d: path("M13.603 5.914a.37.37 0 0 0-.115.576l.641-.314a.372.372 0 0 0-.526-.262");
}

.zc_zi9bsd {
  stop-color: var(--svg-color--311b2f, #311B2F);
}

.zn47ozbfv {
  stop-color: var(--svg-color--442563, #442563);
  stop-opacity: 0;
}

</style>
