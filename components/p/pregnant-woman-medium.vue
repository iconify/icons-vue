<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLRWYSc)"><path fill="url(#icPtlQb)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#icJMwok)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#iEVxrBF)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#idWjidd)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#iIernJc)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#i9eul5c)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#iVDyJbE)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#itHYe8d)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#i3zqYFe)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#iODVQ6W)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#idUbiGb)" clip-rule="evenodd" class="pggmpvqyk"/><path fill="url(#iHFWtGb)" clip-rule="evenodd" class="pggmpvqyk"/></g><g filter="url(#ihAFI4b)"><path fill="url(#ieEbhAc)" class="yht16jo-c"/><path fill="url(#inZFKMl)" class="yht16jo-c"/><path fill="url(#iOSrnkY)" class="yht16jo-c"/><path fill="url(#iYNNY9c)" class="yht16jo-c"/><path fill="url(#ibLRCSK)" class="yht16jo-c"/><path fill="url(#iAL5jlb)" class="yht16jo-c"/><path fill="url(#i9IjANd)" class="yht16jo-c"/><path fill="url(#iqKS0ie)" class="yht16jo-c"/></g><g filter="url(#iSGzekb)"><path fill="url(#iBDHwbb)" class="ht1v0vbjk"/></g><g filter="url(#i9iZPQc)"><path class="yy81w7bkk"/><path fill="url(#i5s6Nwc)" class="ngijsmbxi"/></g><path fill="url(#i1QxTic)" class="ewplotbza"/><path fill="url(#ivvdizc)" class="ewplotbza"/><g filter="url(#ilgente)"><path fill="url(#icGEpKc)" class="hg6-zww1t"/></g><g filter="url(#iZgGBke)"><path fill="url(#iD6ZtAe)" class="x8eeg0e4g"/></g><g filter="url(#iy05GjX)"><path stroke="url(#i3khfDc)" class="hey6xvbxk"/></g><g filter="url(#ia8Cncx)"><path stroke="url(#iB6rnKc)" class="riwlwftfe"/></g><g filter="url(#idC75zg)"><path stroke="url(#iFbmgfB)" class="cu3zhpboq"/></g><path fill="url(#i20QYMe)" class="nzn-gsbyu"/><g filter="url(#iUFzw2G)"><path fill="url(#iZUaPsd)" class="vs9u-ubkt"/></g><g filter="url(#iLwCgbc)"><path fill="url(#idTQwac)" class="ke26ytyyy"/></g><path fill="url(#iIqZROb)" class="ke26ytyyy"/><g filter="url(#iEhwWtc)"><path fill="url(#i1VHT2b)" class="h_uq2jx_h"/><path fill="url(#iksVwab)" class="h_uq2jx_h"/></g><g filter="url(#iuDB9cc)"><path class="gmh16pbhc"/><path fill="url(#i8NXUSb)" class="qb7w4p61e"/></g><g filter="url(#i5aYIkH)"><path class="fxwdy7i7i"/><path fill="url(#iPtSttd)" class="nbuhz2g3f"/></g><g filter="url(#iZHuQ5d)"><path fill="url(#iJnGEGV)" class="ora_he4ri"/><path fill="url(#ic7sHxe)" class="ora_he4ri"/><path fill="url(#iAVHvhU)" class="ora_he4ri"/><path fill="url(#ifDPmie)" class="ora_he4ri"/><path fill="url(#ipUYlkz)" class="ora_he4ri"/><path fill="url(#iA39Wee)" class="ora_he4ri"/><path fill="url(#iUk6AKb)" class="ora_he4ri"/><path fill="url(#i7C27ke)" class="ora_he4ri"/></g><path fill="url(#iWgQhCe)" class="ora_he4ri"/><g filter="url(#ierQ8Hd)"><path class="xwfpkj1bn"/></g><g filter="url(#iRjY4Ge)"><path class="lrovjac-q"/><path fill="url(#i3q7OVb)" class="ijikxmizn"/><path fill="url(#i7Jl0Jc)" class="ijikxmizn"/><path fill="url(#it7iQqk)" class="ijikxmizn"/><path fill="url(#iXKXmic)" class="ijikxmizn"/></g><g filter="url(#i2i84zb)"><path stroke="url(#ivHP1Zd)" class="e_g_cccep"/></g><path class="jnwmjy2bp"/><g filter="url(#iB57gGb)"><path class="l7pu18bsn"/></g><g filter="url(#i0y7VGb)"><path class="g44vfgbgq"/></g><g filter="url(#ijsvZkd)"><path class="mn2b71b2y"/></g><g filter="url(#iZGMPge)"><path clip-rule="evenodd" class="ig-docbkp"/></g><path class="horj7rb9v"/><path fill="url(#if4r3Je)" class="f13chd4ap"/><path class="sukvsybor"/><g filter="url(#iv6Mfnc)"><path class="lnmxcbkwy"/><path fill="url(#iWU1kCK)" class="oh9if-eab"/></g><g filter="url(#if3j9we)"><path fill="url(#ijVGPle)" class="h7_vdpbse"/></g><path class="wc-_eg4hk"/><path fill="url(#i2sfqyc)" class="kfbtlfbjz"/><path class="qxokb5y-b"/><g filter="url(#iq6UFle)"><path fill="url(#iXpw1Pe)" class="a-arde3nj"/></g><g filter="url(#in3J6RU)"><ellipse transform="rotate(-27.914 16.07 8.885)" class="glt2dbbul"/><ellipse fill="url(#ief7qle)" transform="rotate(-27.914 16.07 8.885)" class="ovn7qnelk"/></g><g filter="url(#id88EYc)"><path class="v8uncjb6h"/></g><g filter="url(#iMAVACe)"><path class="nxnmnd66v"/></g><g filter="url(#iIghgxe)"><path class="rvlczfr5q"/><path fill="url(#iNnDz5b)" class="x1kh70p8c"/><path fill="url(#ijB1J2d)" class="x1kh70p8c"/></g><g filter="url(#iHNzmDb)"><path class="vu_ajf3du"/><path fill="url(#iZ5Q2td)" class="x3_i6-21h"/><path fill="url(#i5Sdhxc)" class="x3_i6-21h"/></g><g filter="url(#i5vLmbe)"><path stroke="url(#ikRkake)" class="vfx_igb5k"/></g><g filter="url(#iD683ne)"><path class="m5vo_2b3c"/></g><defs><radialGradient id="icJMwok" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 3.859 13.707)scale(4.02466 5.02762)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iEVxrBF" cx="0" cy="0" r="1" gradientTransform="matrix(-2.52307 1.70158 -2.23573 -3.31511 15.49 11.915)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="idWjidd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 4.596 8.297)scale(1.88354 1.44629)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iIernJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1295 1.84824 -1.30192 -.79563 14.374 7.91)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="i9eul5c" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 5.55 13.748)scale(2.58518 3.58862)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="iVDyJbE" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 10.78 6.96)scale(1.78398 2.49309)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="itHYe8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61348 .4694 -.9789 -3.36478 24.789 8.747)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="i3zqYFe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46426 .6161 -.78482 -3.1391 24.26 11.739)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iODVQ6W" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.546 -4.69)scale(2.45072 1.93837)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="idUbiGb" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -76.89 127.124)scale(1.32337 2.14425)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iHFWtGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73342 -3.24177 1.17002 -.2647 22.691 8.145)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iOSrnkY" cx="0" cy="0" r="1" gradientTransform="rotate(143.412 5.633 14.177)scale(5.96846 3.36558)" gradientUnits="userSpaceOnUse"><stop class="s2ayxoxhu"/><stop offset="1" class="j6izx0btu"/></radialGradient><radialGradient id="iYNNY9c" cx="0" cy="0" r="1" gradientTransform="rotate(117.506 5.306 14.346)scale(10.2174 6.6572)" gradientUnits="userSpaceOnUse"><stop class="c9qnqxb4v"/><stop offset="1" class="f6lyc94ec"/></radialGradient><radialGradient id="ibLRCSK" cx="0" cy="0" r="1" gradientTransform="rotate(133.238 6.284 9.66)scale(4.31097 4.07134)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="abn8efjgi"/><stop offset="1" class="v46c2zbrf"/></radialGradient><radialGradient id="iAL5jlb" cx="0" cy="0" r="1" gradientTransform="rotate(-144.77 15.757 10.466)scale(4.37936 1.86088)" gradientUnits="userSpaceOnUse"><stop class="jhjy8fbuk"/><stop offset="1" class="eb_-_cbgw"/></radialGradient><radialGradient id="i9IjANd" cx="0" cy="0" r="1" gradientTransform="rotate(-140.774 9.442 11.603)scale(.98834 .87647)" gradientUnits="userSpaceOnUse"><stop class="ui2onhbah"/><stop offset="1" class="r9xs6qbkj"/></radialGradient><radialGradient id="iqKS0ie" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 .23438 -.1603 .3847 13.126 19.476)" gradientUnits="userSpaceOnUse"><stop class="i5_a4vbjv"/><stop offset="1" class="qromo9b3v"/></radialGradient><radialGradient id="i5s6Nwc" cx="0" cy="0" r="1" gradientTransform="rotate(-111.297 16.98 9.9)scale(2.70865 13.4771)" gradientUnits="userSpaceOnUse"><stop class="ob062_bwk"/><stop offset="1" class="sqkvlv6cj"/></radialGradient><radialGradient id="i1QxTic" cx="0" cy="0" r="1" gradientTransform="rotate(172.312 10.093 13.635)scale(15.1472 14.3188)" gradientUnits="userSpaceOnUse"><stop offset=".843" class="koh162bjq"/><stop offset="1" class="m-np0bilz"/></radialGradient><radialGradient id="ivvdizc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4464 7.74936 -17.0124 3.17533 11.454 22.442)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="euq4gbh-v"/><stop offset=".947" class="hfg02r6gm"/></radialGradient><radialGradient id="iIqZROb" cx="0" cy="0" r="1" gradientTransform="rotate(-118.51 10.128 1.354)scale(1.19855 1.35812)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="i1VHT2b" cx="0" cy="0" r="1" gradientTransform="matrix(2.1783 -.99014 1.20891 2.6596 21.753 9.877)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iksVwab" cx="0" cy="0" r="1" gradientTransform="matrix(1.05614 0 0 .45473 22.545 7.999)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="i8NXUSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.32138 -.0983 .07684 1.03296 22.06 9.59)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iPtSttd" cx="0" cy="0" r="1" gradientTransform="rotate(180 7.095 4.746)scale(.92412)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iJnGEGV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.6916 2.62459 -3.51296 -7.6181 20.72 9.022)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="ic7sHxe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90807 .83961 -.5847 -1.32875 19.942 9.77)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iAVHvhU" cx="0" cy="0" r="1" gradientTransform="matrix(1.1282 -3.4379 4.36206 1.43147 16.325 14.717)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="ifDPmie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12429 6.45264 -8.06571 -1.40534 19.113 8.658)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="ipUYlkz" cx="0" cy="0" r="1" gradientTransform="matrix(-6.04348 1.18601 -2.04195 -10.40503 19.802 10.537)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iA39Wee" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.0071 1.23598 0 20.231 8.656)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iUk6AKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14864 1.31642 0 16.4 8.456)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="i7C27ke" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 7.175 10.756)scale(2.92476 2.34029)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iWgQhCe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12481 0 0 -5.64083 22.677 9.958)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="i3q7OVb" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 13.698 -2.28)scale(1.8327 .56482)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iXKXmic" cx="0" cy="0" r="1" gradientTransform="matrix(-.6821 0 0 -.1907 18.694 10.778)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="if4r3Je" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71002 -1.12937 0 20.127 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iWU1kCK" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 12.178 -.358)scale(.33106 .45578)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2sfqyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71003 -1.12938 0 16.308 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ief7qle" cx="0" cy="0" r="1" gradientTransform="matrix(-.00677 -.43238 .51973 -.00814 16.057 9.161)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNnDz5b" cx="0" cy="0" r="1" gradientTransform="matrix(1.10448 -2.4114 1.2336 .56502 13.266 7.113)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="ijB1J2d" cx="0" cy="0" r="1" gradientTransform="matrix(1.006 -1.72863 .92803 .54009 14.76 6.255)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="iZ5Q2td" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 9.141 7.53)scale(4.26452 6.97223)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="i5Sdhxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.18408 1.1965 -2.5742 -.39603 18.401 2.88)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="iLRWYSc" width="13.393" height="13.893" x="11.646" y="1.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/></filter><filter id="ihAFI4b" width="15.898" height="17.05" x="7.691" y="13.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.345098 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.396078 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3482" result="effect2_innerShadow_4002_3482"/></filter><filter id="iSGzekb" width="15.258" height="14.494" x="7.177" y="15.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".25"/></filter><filter id="i9iZPQc" width="14.977" height="12.277" x="7.211" y="17.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.345098 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/></filter><filter id="ilgente" width="4.354" height="4.526" x="18.588" y="15.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.27451 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/></filter><filter id="iZgGBke" width="3.759" height="5.328" x="19.419" y="15.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".5"/></filter><filter id="iy05GjX" width="1.206" height=".37" x="7.762" y="26.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".05"/></filter><filter id="ia8Cncx" width="1.261" height=".3" x="7.527" y="27.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".05"/></filter><filter id="idC75zg" width="1.206" height=".3" x="7.937" y="28.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".05"/></filter><filter id="iUFzw2G" width="4.908" height="6.063" x="16.814" y="19.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".25"/></filter><filter id="iLwCgbc" width="2.966" height="2.816" x="12.709" y="8.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/></filter><filter id="iEhwWtc" width="2.816" height="3.066" x="21.034" y="7.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/></filter><filter id="iuDB9cc" width="2.88" height="2.88" x="21.002" y="8.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".25"/></filter><filter id="i5aYIkH" width="2.58" height="2.58" x="12.844" y="8.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".175"/></filter><filter id="iZHuQ5d" width="8.919" height="9.769" x="13.758" y="5.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/></filter><filter id="ierQ8Hd" width="2.643" height="3.347" x="16.754" y="8.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".25"/></filter><filter id="iRjY4Ge" width="2.143" height="2.847" x="17.146" y="8.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".125"/></filter><filter id="i2i84zb" width="3.29" height="1.386" x="16.572" y="11.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".05"/></filter><filter id="iB57gGb" width="2.652" height="1.125" x="19.017" y="8.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/></filter><filter id="i0y7VGb" width="2.652" height="1.125" x="14.766" y="8.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/></filter><filter id="ijsvZkd" width="2.171" height=".98" x="14.885" y="6.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/></filter><filter id="iZGMPge" width="2.171" height=".98" x="19.625" y="6.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/></filter><filter id="iv6Mfnc" width=".714" height=".635" x="19.472" y="8.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".05"/></filter><filter id="if3j9we" width=".83" height=".849" x="20.195" y="8.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".1"/></filter><filter id="iq6UFle" width=".913" height=".96" x="16.306" y="8.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".1"/></filter><filter id="in3J6RU" width=".824" height=".641" x="15.658" y="8.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".05"/></filter><filter id="id88EYc" width="2.053" height=".931" x="19.615" y="7.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".1"/></filter><filter id="iMAVACe" width="2.053" height=".931" x="14.844" y="7.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".1"/></filter><filter id="iIghgxe" width="3.886" height="4.15" x="12.606" y="3.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/><feGaussianBlur result="effect2_foregroundBlur_4002_3482" stdDeviation=".2"/></filter><filter id="iHNzmDb" width="7.741" height="5.123" x="15.405" y="2.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3482"/><feGaussianBlur result="effect2_foregroundBlur_4002_3482" stdDeviation=".125"/></filter><filter id="i5vLmbe" width="1.077" height="2.096" x="15.387" y="3.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".1"/></filter><filter id="iD683ne" width="5.812" height="3.138" x="17.615" y="4.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3482" stdDeviation=".375"/></filter><linearGradient id="icPtlQb" x1="22.325" x2="16.956" y1="3.407" y2="12.824" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="ieEbhAc" x1="20.106" x2="12.387" y1="27.891" y2="19.391" gradientUnits="userSpaceOnUse"><stop class="pokolfbgc"/><stop offset="1" class="b3y8h4ksz"/></linearGradient><linearGradient id="inZFKMl" x1="16.512" x2="16.512" y1="29.971" y2="27.261" gradientUnits="userSpaceOnUse"><stop class="ckcj4hbsb"/><stop offset="1" class="q93oiybtq"/></linearGradient><linearGradient id="iBDHwbb" x1="19.157" x2="11.439" y1="17.604" y2="26.104" gradientUnits="userSpaceOnUse"><stop class="tts0ot_3n"/><stop offset="1" class="luw3gnblf"/></linearGradient><linearGradient id="icGEpKc" x1="21.84" x2="18.965" y1="18.203" y2="18.047" gradientUnits="userSpaceOnUse"><stop class="a_ut7cc2e"/><stop offset="1" class="cyj659bzg"/></linearGradient><linearGradient id="iD6ZtAe" x1="21.309" x2="20.606" y1="16.453" y2="20.953" gradientUnits="userSpaceOnUse"><stop class="gla1f_2eg"/><stop offset="1" class="fx7b7_wnc"/></linearGradient><linearGradient id="i3khfDc" x1="7.912" x2="9.067" y1="27.133" y2="27.203" gradientUnits="userSpaceOnUse"><stop class="ugg-_qbln"/><stop offset="1" class="de57ux5iu"/></linearGradient><linearGradient id="iB6rnKc" x1="7.677" x2="8.907" y1="28.117" y2="28.123" gradientUnits="userSpaceOnUse"><stop class="ugg-_qbln"/><stop offset="1" class="de57ux5iu"/></linearGradient><linearGradient id="iFbmgfB" x1="8.087" x2="9.247" y1="29.031" y2="29.036" gradientUnits="userSpaceOnUse"><stop class="ugg-_qbln"/><stop offset="1" class="de57ux5iu"/></linearGradient><linearGradient id="i20QYMe" x1="11.923" x2="24.514" y1="13.673" y2="13.673" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iZUaPsd" x1="20.439" x2="16.048" y1="20.167" y2="26.245" gradientUnits="userSpaceOnUse"><stop class="f82cxkbtx"/><stop offset="1" class="ot1id8hky"/></linearGradient><linearGradient id="idTQwac" x1="12.709" x2="14.334" y1="9.568" y2="9.568" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="i7Jl0Jc" x1="17.396" x2="18.217" y1="10.657" y2="10.657" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="it7iQqk" x1="18.217" x2="18.217" y1="11.276" y2="10.727" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="ivHP1Zd" x1="17.286" x2="17.689" y1="12.59" y2="11.966" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ijVGPle" x1="20.808" x2="20.533" y1="9.017" y2="9.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXpw1Pe" x1="16.959" x2="16.684" y1="9.016" y2="9.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikRkake" x1="15.497" x2="15.925" y1="3.407" y2="4.515" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pregnant-woman-medium" /></template>
<style>
.a_ut7cc2e {
  stop-color: var(--svg-color--8e6acb, #8E6ACB);
}

.a-arde3nj {
  d: path("M17.02 9.241c0-.252-.206-.42-.261-.471l-.253.244l.156.316z");
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.abn8efjgi {
  stop-color: var(--svg-color--513091, #513091);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b3y8h4ksz {
  stop-color: var(--svg-color--7657b1, #7657B1);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.c9qnqxb4v {
  stop-color: var(--svg-color--9c7cd3, #9C7CD3);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckcj4hbsb {
  stop-color: var(--svg-color--5d4097, #5D4097);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu3zhpboq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M8.087 29.031h.907");
}

.cyj659bzg {
  stop-color: var(--svg-color--7555ae, #7555AE);
}

.de57ux5iu {
  stop-color: var(--svg-color--7d5a46, #7D5A46);
  stop-opacity: 0;
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e_g_cccep {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.218 12.04a2.65 2.65 0 0 1-1.245-.302c-.123-.064-.255.078-.177.192a1.69 1.69 0 0 0 2.843 0c.078-.119-.054-.256-.177-.192c-.36.192-.784.302-1.244.302Z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eb_-_cbgw {
  stop-color: var(--svg-color--6f56b0, #6F56B0);
  stop-opacity: 0;
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.euq4gbh-v {
  stop-color: var(--svg-color--9c5e7b, #9C5E7B);
  stop-opacity: 0;
}

.ewplotbza {
  d: path("M11.884 26.236c4.56-1.156 6.421-4.828 6.85-6.558l3.454.302c-.663 2.752-2.038 5.192-4.976 7.466c-3.972 2.752-8.54 2.498-8.75 2.498c-.209 0-.575-.105-.63-.432a.45.45 0 0 1 .182-.46c-.127 0-.47-.02-.576-.406a.49.49 0 0 1 .161-.512a.48.48 0 0 1-.385-.547c.037-.424.426-.483.639-.473c-.259-.097-.282-.37-.254-.532c.023-.131.195-.512.761-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.271-.317a.55.55 0 0 1 .051-.742a.55.55 0 0 1 .792.026c.113.126.24.27.369.42c.42.488.703.702 1.513.556");
}

.f13chd4ap {
  d: path("M20.129 8.552a.78.78 0 0 1 .752.987h-1.508a.784.784 0 0 1 .756-.987");
}

.f6lyc94ec {
  stop-color: var(--svg-color--8563c2, #8563C2);
  stop-opacity: 0;
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.f82cxkbtx {
  stop-color: var(--svg-color--c39d8c, #C39D8C);
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx7b7_wnc {
  stop-color: var(--svg-color--a281e0, #A281E0);
  stop-opacity: 0;
}

.fxwdy7i7i {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M14.134 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g44vfgbgq {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M17.218 8.994c-.232-.409-.585-.731-1.345-.731a1.45 1.45 0 0 0-.94.322c-.235.19-.203.434-.02.525l.486.278c.57-.185 1.201-.21 1.82-.394");
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gla1f_2eg {
  stop-color: var(--svg-color--a281e0, #A281E0);
}

.glt2dbbul {
  cx: 16.07px;
  cy: 8.885px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.341px;
  ry: 0.173px;
}

.gmh16pbhc {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M22.442 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h_uq2jx_h {
  d: path("M22.442 10.9a1.408 1.408 0 1 0 0-2.816a1.408 1.408 0 0 0 0 2.816");
}

.h7_vdpbse {
  d: path("M20.825 9.23a.74.74 0 0 0-.203-.405l-.227.25l.102.2z");
}

.hey6xvbxk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.912 27.133c.174.013.6.045.906.07");
}

.hfg02r6gm {
  stop-color: var(--svg-color--9c5e7b, #9C5E7B);
}

.hg6-zww1t {
  d: path("M19.037 17.512c0-1.562 1.204-1.887 1.805-1.855c.8 0 1.747.576 1.698 1.962a10.4 10.4 0 0 1-.35 2.362h-3.602c.15-.492.449-1.673.449-2.47");
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.horj7rb9v {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.31 8.314c.571 0 1.054.395 1.186.927a.24.24 0 0 1-.235.298H19.31a.2.2 0 0 1-.2-.238c.11-.56.604-.987 1.2-.987");
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.ht1v0vbjk {
  d: path("M20.331 16.168c-.568-.03-1.704.276-1.704 1.75c0 .752-.282 1.867-.424 2.33h.06c-.528 1.723-2.32 4.875-6.388 5.905c-.764.138-1.031-.064-1.428-.525a27 27 0 0 0-.348-.396a.52.52 0 0 0-.747-.024a.52.52 0 0 0-.048.7c.093.115.187.227.256.299a5.6 5.6 0 0 1-1.01-.1c-.534-.11-.697.249-.719.373c-.026.153 1.516.324 1.76.416c-.201-.009-.568.046-.603.447a.455.455 0 0 0 .364.516c-.07.054-1.742.317-1.673.57c.1.363.424.382.544.382a.43.43 0 0 0-.171.434c.05.31.396.409.594.409h.048c.52.015 4.622.128 8.21-2.358c2.773-2.147 4.072-4.422 4.698-7.02l-.287-.027h.287a9.8 9.8 0 0 0 .332-2.23c.046-1.307-.848-1.851-1.603-1.851");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i5_a4vbjv {
  stop-color: var(--svg-color--725e92, #725E92);
}

.ig-docbkp {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m21.483 7.536l-.12.201za.235.235 0 0 1-.24.402h-.001l-.004-.003a1 1 0 0 0-.1-.05a2.4 2.4 0 0 0-.299-.119a2 2 0 0 0-.938-.08a.235.235 0 1 1-.081-.462c.448-.08.864 0 1.162.095a3 3 0 0 1 .489.209l.008.005l.003.001z");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.ijikxmizn {
  d: path("m17.883 9.176l-.465 1.488a.472.472 0 0 0 .455.612h.688a.474.474 0 0 0 .456-.612l-.465-1.488c-.1-.33-.565-.33-.67 0");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6izx0btu {
  stop-color: var(--svg-color--755fa5, #755FA5);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jhjy8fbuk {
  stop-color: var(--svg-color--7a63b9, #7A63B9);
}

.jnwmjy2bp {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M18.218 12.04a2.65 2.65 0 0 1-1.245-.302c-.123-.064-.255.078-.177.192a1.69 1.69 0 0 0 2.843 0c.078-.119-.054-.256-.177-.192c-.36.192-.784.302-1.244.302");
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.ke26ytyyy {
  d: path("M14.117 10.9a1.408 1.408 0 1 0 0-2.816a1.408 1.408 0 0 0 0 2.816");
}

.kfbtlfbjz {
  d: path("M16.306 8.552a.78.78 0 0 0-.753.987h1.509a.786.786 0 0 0-.756-.987");
}

.koh162bjq {
  stop-color: var(--svg-color--997565, #997565);
  stop-opacity: 0;
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7pu18bsn {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M19.217 8.994c.232-.409.585-.731 1.345-.731c.333 0 .654.092.939.322c.235.19.204.434.022.525l-.487.278c-.57-.185-1.201-.21-1.82-.394");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnmxcbkwy {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.071 8.717c.056.075-.06.165-.193.264c-.132.099-.23.169-.286.094c-.055-.074.007-.215.14-.314c.131-.098.284-.118.34-.044");
}

.lrovjac-q {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m17.883 9.176l-.465 1.488a.472.472 0 0 0 .455.612h.688a.474.474 0 0 0 .456-.612l-.465-1.488c-.1-.33-.565-.33-.67 0");
}

.luw3gnblf {
  stop-color: var(--svg-color--584487, #584487);
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.m-np0bilz {
  stop-color: var(--svg-color--997565, #997565);
}

.m5vo_2b3c {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m20.323 5.833l-1.247.23a.602.602 0 1 1-.11-1.195h2.049c1.211 0 1.613 1.221 1.662 1.638a2.75 2.75 0 0 0-2.354-.673");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mn2b71b2y {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m15.244 7.937l-.004.002a.235.235 0 0 1-.241-.403H15l.003-.002l.008-.005a2 2 0 0 1 .13-.067a3 3 0 0 1 .359-.142a2.46 2.46 0 0 1 1.162-.095a.235.235 0 0 1-.081.462c-.35-.062-.684 0-.938.08a2.4 2.4 0 0 0-.399.17");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.nbuhz2g3f {
  d: path("M14.134 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.ngijsmbxi {
  d: path("M11.884 26.236c4.56-1.156 6.421-4.828 6.85-6.558l2.703-2.005l.751 2.307c-.663 2.752-2.038 5.192-4.976 7.466c-3.972 2.752-8.54 2.498-8.75 2.498c-.209 0-.575-.105-.63-.432a.45.45 0 0 1 .182-.46c-.127 0-.47-.021-.576-.406a.49.49 0 0 1 .161-.512a.48.48 0 0 1-.385-.547c.037-.425.426-.483.639-.473c-.259-.098-.282-.37-.254-.532c.023-.131.195-.512.761-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.271-.317a.55.55 0 0 1 .051-.742a.55.55 0 0 1 .792.026c.113.125.24.27.369.42c.42.488.703.702 1.513.556");
}

.nxnmnd66v {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.597 7.416c-.282-.069-.984-.034-1.453.301");
}

.nzn-gsbyu {
  d: path("M18.238 13.674h-.035c.087 0 .166 0 .253.009c-.07-.01-.148-.01-.218-.01");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.ob062_bwk {
  stop-color: var(--svg-color--b68083, #B68083);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh9if-eab {
  d: path("M20.071 8.717c.056.075-.06.165-.193.264c-.132.099-.23.169-.286.094c-.055-.074.007-.215.14-.314c.131-.098.284-.118.34-.044");
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.ora_he4ri {
  d: path("M13.765 8.387h.01l-.008-.232l-.009-.268c.018-.83.503-1.151.709-1.259q.021-.006.045-.017t.045-.018a2.02 2.02 0 0 0 1.04-1.08l.073-.17a.23.23 0 0 1 .403-.045a3.38 3.38 0 0 0 2.791 1.464h2.819c.157 0 .947.077.994 1.166l-.104 2.69c-.108 2.452-2.024 4.1-4.361 4.1c-2.338 0-4.254-1.648-4.362-4.1z");
}

.ot1id8hky {
  stop-color: var(--svg-color--c39d8c, #C39D8C);
  stop-opacity: 0;
}

.ovn7qnelk {
  cx: 16.07px;
  cy: 8.885px;
  rx: 0.341px;
  ry: 0.173px;
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.pggmpvqyk {
  fill-rule: evenodd;
  d: path("M24.506 10.725c.186-.38.283-.806.283-1.248c0-.41-.084-.793-.235-1.143h.005a3 3 0 0 0-.247-.449l-.001-.003c-.302-.46-.46-1-.46-1.55v-.008a2.89 2.89 0 0 0-2.888-2.887a.47.47 0 0 1-.399-.204a2.9 2.9 0 0 0-2.347-1.205c-.965 0-1.824.479-2.347 1.205a.5.5 0 0 1-.398.204h-.075a2.89 2.89 0 0 0-2.812 2.887v.009c0 .549-.16 1.089-.461 1.55l-.002.003a2.89 2.89 0 0 0-.193 2.84a.45.45 0 0 1 0 .398a2.812 2.812 0 0 0 2.533 4.047h7.51a2.812 2.812 0 0 0 2.534-4.047a.45.45 0 0 1 0-.399m-10.73-2.338h-.01l1.048 2.061c.108 2.453 1.065 0 3.403 0s3.358 2.73 3.466.277l.994-2.798c-.047-1.089-.837-1.165-.994-1.165h-2.818a3.38 3.38 0 0 1-2.791-1.465a.23.23 0 0 0-.404.045l-.072.17a2.02 2.02 0 0 1-1.13 1.116c-.207.107-.692.428-.71 1.259l.01.268z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pokolfbgc {
  stop-color: var(--svg-color--7a61b9, #7A61B9);
}

.q93oiybtq {
  stop-color: var(--svg-color--5d4097, #5D4097);
  stop-opacity: 0;
}

.qb7w4p61e {
  d: path("M22.442 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qromo9b3v {
  stop-color: var(--svg-color--725e92, #725E92);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxokb5y-b {
  fill: var(--svg-color--000, #000);
  d: path("M16.753 9.333a.445.445 0 0 0-.447-.447a.445.445 0 0 0-.398.653h.792a.44.44 0 0 0 .053-.206");
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r9xs6qbkj {
  stop-color: var(--svg-color--423363, #423363);
  stop-opacity: 0;
}

.riwlwftfe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.677 28.117h.961");
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rvlczfr5q {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M13.781 4.251c.495-.524 1.432-.525 1.865-.447l.346 1.13c-.221-.035-.258-.002-.424.16c-.12.956-1.205 1.537-2.526 1.922c-.13-1.305.095-2.083.74-2.765");
}

.s2ayxoxhu {
  stop-color: var(--svg-color--755fa5, #755FA5);
}

.sqkvlv6cj {
  stop-color: var(--svg-color--b68083, #B68083);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.sukvsybor {
  fill: var(--svg-color--000, #000);
  d: path("M19.682 9.333c0-.248.198-.447.447-.447a.445.445 0 0 1 .397.653h-.791a.4.4 0 0 1-.053-.206");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tts0ot_3n {
  stop-color: var(--svg-color--553697, #553697);
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ugg-_qbln {
  stop-color: var(--svg-color--7d5a46, #7D5A46);
}

.ui2onhbah {
  stop-color: var(--svg-color--423363, #423363);
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v46c2zbrf {
  stop-color: var(--svg-color--785cad, #785CAD);
  stop-opacity: 0;
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v8uncjb6h {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.915 7.416c.282-.069.984-.034 1.453.301");
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vfx_igb5k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.687 3.767c.02.212.205 1.012.477 1.496");
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vs9u-ubkt {
  d: path("M20.347 20.167c-.463 2.15-2.257 4.286-3.033 5.063c2.637-1.776 3.747-4.13 3.908-5.063z");
}

.vu_ajf3du {
  fill: var(--svg-color--553836, #553836);
  d: path("M17.69 2.674c-.992-.219-1.882.77-1.985 1.137c.92 3.102 3.25 2.932 5.549 2.677c1.376-.153 1.525.474 1.643.777c0-3.442-2.927-4.088-5.183-4.586z");
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wc-_eg4hk {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.125 8.314c-.572 0-1.054.395-1.186.927a.24.24 0 0 0 .235.298h1.952a.2.2 0 0 0 .199-.238a1.226 1.226 0 0 0-1.2-.987");
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.x1kh70p8c {
  d: path("M13.781 4.251c.495-.524 1.432-.525 1.865-.447l.346 1.13c-.221-.035-.258-.002-.424.16c-.12.956-1.205 1.537-2.526 1.922c-.13-1.305.095-2.083.74-2.765");
}

.x3_i6-21h {
  d: path("M17.69 2.674c-.992-.219-1.882.77-1.985 1.137c.92 3.102 3.25 2.932 5.549 2.677c1.376-.153 1.525.474 1.643.777c0-3.442-2.927-4.088-5.183-4.586z");
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x8eeg0e4g {
  d: path("M20.696 17.172a35 35 0 0 1-.277 2.61h1.5a23 23 0 0 0 .258-2.58a.72.72 0 0 0-.726-.749a.764.764 0 0 0-.755.72");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xwfpkj1bn {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m17.874 9.297l-.598 1.488a.472.472 0 0 0 .455.612h.688c.323 0 .55-.31.456-.612l-.465-1.488c-.1-.33-.432-.33-.536 0");
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yht16jo-c {
  d: path("M13.48 16.188c.688-.875 2.474-2.375 3.282-3.016h3.265c2.15.587 2.563 2.625 2.563 3.625v11.328c0 1.563-1.209 1.88-1.813 1.844h-9.89c-2.282 0-4.093-3.188-2.719-6.61c1.264-2.63 3.502-3.447 4.787-3.74a.16.16 0 0 0 .093-.243c-.98-1.43-.39-2.141.432-3.189");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yy81w7bkk {
  fill: var(--svg-color--ad8373, #AD8373);
  d: path("M11.884 26.236c4.56-1.156 6.421-4.828 6.85-6.558l2.703-2.005l.751 2.307c-.663 2.752-2.038 5.192-4.976 7.466c-3.972 2.752-8.54 2.498-8.75 2.498c-.209 0-.575-.105-.63-.432a.45.45 0 0 1 .182-.46c-.127 0-.47-.021-.576-.406a.49.49 0 0 1 .161-.512a.48.48 0 0 1-.385-.547c.037-.425.426-.483.639-.473c-.259-.098-.282-.37-.254-.532c.023-.131.195-.512.761-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.271-.317a.55.55 0 0 1 .051-.742a.55.55 0 0 1 .792.026c.113.125.24.27.369.42c.42.488.703.702 1.513.556");
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

</style>
