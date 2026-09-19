<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuMZfRc)"><path fill="url(#iE3txCb)" clip-rule="evenodd" class="rknqf7fgs"/><path fill="url(#igUcBmb)" clip-rule="evenodd" class="rknqf7fgs"/><path fill="url(#imwAjCe)" clip-rule="evenodd" class="rknqf7fgs"/></g><g filter="url(#irmXOzc)"><path fill="url(#i1Pd52d)" class="e5n7-cbky"/><path fill="url(#iM6rPqd)" class="e5n7-cbky"/></g><g filter="url(#itoRxxb)"><path class="ii_vcdblz"/></g><g filter="url(#iKZdCxv)"><path class="x9-b3hbfy"/></g><g filter="url(#ieWSf3g)"><path class="a424ylq9x"/><path fill="url(#i7bctJc)" class="m3dxw5b4u"/><path fill="url(#izNqDsc)" class="m3dxw5b4u"/><path fill="url(#it3vqkc)" class="m3dxw5b4u"/></g><path class="a1i_j40xh"/><path fill="url(#igSiocc)" class="rq76sybla"/><path fill="url(#iQD9PdN)" class="rq76sybla"/><path fill="url(#ifkmApd)" class="rq76sybla"/><path fill="url(#iUzRGHc)" class="rq76sybla"/><path fill="url(#iFGxoeb)" class="lt_b3wboz"/><path fill="url(#i5m29vW)" class="lt_b3wboz"/><path class="vbc9nqbss"/><path fill="url(#iPRoNnL)" class="pi6c47yng"/><path class="javsik_yi"/><path fill="url(#iOgo57h)" class="u-q3e7b8s"/><path fill="url(#ixTCUsb)" class="wallrjjxc"/><path fill="url(#ibY3Hwd)" class="wallrjjxc"/><path fill="url(#ilUJdLc)" class="wallrjjxc"/><path fill="url(#iEUdCfb)" class="fbjx3y-qb"/><path fill="url(#iYx2EHb)" class="fbjx3y-qb"/><g filter="url(#iC4FfXb)"><path class="kc9q3mbff"/><path fill="url(#ifFH9Wc)" class="qv8wc6zla"/></g><path fill="url(#iUEJUid)" class="ue1gv6enh"/><path fill="url(#i294t4w)" class="ue1gv6enh"/><g filter="url(#iCtTklb)"><path fill="url(#ipsyrne)" class="na59ribzw"/></g><path class="vczswwwcd"/><g filter="url(#i0SMake)"><path fill="url(#iRrCpFd)" class="qtzewq2gr"/><path fill="url(#irXsggA)" class="qtzewq2gr"/><path fill="url(#iGAXcHe)" class="qtzewq2gr"/><path fill="url(#i16MIqd)" class="qtzewq2gr"/><path fill="url(#iwHUrfZ)" class="qtzewq2gr"/></g><g filter="url(#iXlJbPb)"><path stroke="url(#il7Uzxb)" class="bzs2-ddka"/></g><g filter="url(#iZ5kF2c)"><path stroke="url(#iClF6kr)" class="pjsi77bhr"/></g><g filter="url(#ipONudc)"><path stroke="url(#iNjvqRd)" class="oool1tdti"/></g><g filter="url(#iD74O2c)"><path fill="url(#iJRVmSd)" class="eh59-c2og"/></g><path fill="url(#iR2iq9a)" class="dw3xeubwh"/><path fill="url(#iS6Ohib)" class="dw3xeubwh"/><g filter="url(#i539Zmb)"><path fill="url(#iVnS8Wd)" class="wg_w1vbgj"/></g><g filter="url(#i8Nehhb)"><path fill="url(#iVFif9b)" class="v9wc5kdsn"/></g><g filter="url(#i6uBh3d)"><path fill="url(#iOjV5pd)" class="g8y5_ueit"/></g><path fill="url(#ilm5E1U)" class="g8y5_ueit"/><path fill="url(#i4qyZjd)" class="g8y5_ueit"/><path fill="url(#iSDjEKq)" class="g8y5_ueit"/><path fill="url(#iI9tjLd)" class="g8y5_ueit"/><path fill="url(#iN8Tvbb)" class="g8y5_ueit"/><path fill="url(#iG7Blxd)" class="g8y5_ueit"/><g filter="url(#im8RPXc)"><path class="zadlptbzn"/></g><g filter="url(#iG6yQje)"><path fill="url(#iPso2cj)" class="vxca8ab-k"/></g><g filter="url(#iQs4B3c)"><path stroke="url(#iXUmSdd)" class="jt6x1fb4w"/></g><path fill="url(#izbRTfH)" class="l8qslmb5u"/><g filter="url(#iQE1OCd)"><path class="d8j-r9bsb"/></g><g filter="url(#iLv1W6d)"><path class="pmikb6mtj"/></g><g filter="url(#iJaJqUb)"><path class="pmh75mbyu"/></g><g filter="url(#ik2Lxkd)"><path clip-rule="evenodd" class="xl-8m7bem"/></g><path class="knosl_37y"/><path fill="url(#ipdtO8d)" class="s3p5lff5x"/><path class="ngwa02-tu"/><g filter="url(#i5aj5Yb)"><path class="b9xd2sfxu"/><path fill="url(#illsOim)" class="lkgfrvbcs"/></g><g filter="url(#iRSMkPd)"><path fill="url(#iz27EMc)" class="pdra6ipeg"/></g><path class="y9d5neb6h"/><path fill="url(#ia1chte)" class="jv7e0m1bl"/><path class="qjc1qgb0d"/><g filter="url(#iyYfcde)"><path fill="url(#iMcjOzc)" class="rxmjvacge"/></g><g filter="url(#i4G1beu)"><ellipse transform="rotate(-27.914 12.28 9.93)" class="v6_fcq9so"/><ellipse fill="url(#i7Oj7Cc)" transform="rotate(-27.914 12.28 9.93)" class="v-p3thbyp"/></g><g filter="url(#iuaciRd)"><path class="rin7jfzij"/></g><g filter="url(#itWFTsd)"><path class="memsme0ni"/></g><path fill="url(#icBL91d)" class="iycy_sbnz"/><path fill="url(#ibvcPeT)" class="g9arp8b8o"/><path fill="url(#ic8iSPb)" class="g9arp8b8o"/><path fill="url(#iLeaTZU)" class="sb1phf9zd"/><path fill="url(#iE9kqQd)" class="sb1phf9zd"/><path fill="url(#ijzTWdd)" class="ltwsa8bld"/><path fill="url(#iT74aTv)" class="ltwsa8bld"/><path fill="url(#ivqY3ab)" class="ltwsa8bld"/><g filter="url(#iWc4GJc)"><path fill="url(#iCmdwmN)" class="o12zmvuzn"/></g><g filter="url(#iCG6NGb)"><path class="ojb-ttbmo"/></g><g filter="url(#iEZYiAe)"><path class="ac3zfwb5z"/></g><g filter="url(#ijSWnmd)"><path fill="url(#iQ1Swud)" class="ah-0903bl"/></g><defs><radialGradient id="igUcBmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52301 0 0 -1.79688 22.36 12.616)" gradientUnits="userSpaceOnUse"><stop class="jg7a3hcoh"/><stop offset="1" class="ppjvl5bbu"/></radialGradient><radialGradient id="imwAjCe" cx="0" cy="0" r="1" gradientTransform="rotate(102.551 .208 7.835)scale(2.59322)" gradientUnits="userSpaceOnUse"><stop class="ymyjruwrb"/><stop offset="1" class="y8uqe7b6k"/><stop offset="1" class="zexrct42f"/></radialGradient><radialGradient id="iM6rPqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.5 5.875 0 20.418 30)" gradientUnits="userSpaceOnUse"><stop class="bbqwceq4e"/><stop offset="1" class="s5pm96b_v"/></radialGradient><radialGradient id="i7bctJc" cx="0" cy="0" r="1" gradientTransform="rotate(137.578 3.33 12.372)scale(3.51039 2.85287)" gradientUnits="userSpaceOnUse"><stop class="ypv_kpaja"/><stop offset="1" class="iv7bj_baj"/></radialGradient><radialGradient id="izNqDsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 1.72406 -2.87775 -1.46054 13.106 16.844)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="d7sh3eboe"/><stop offset="1" class="tizux9w7p"/></radialGradient><radialGradient id="ifkmApd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94352 -1.86047 0 16.66 16.037)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="rtj8_6bqg"/><stop offset="1" class="m8_l30tsr"/></radialGradient><radialGradient id="iUzRGHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.94683 2.47509 -1.65865 -.6345 15.664 17.448)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="s1rw4px-b"/><stop offset="1" class="p3_97vb4n"/></radialGradient><radialGradient id="iFGxoeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.9375 0 6.668 30)" gradientUnits="userSpaceOnUse"><stop class="mx797o4di"/><stop offset="1" class="m1_q07_me"/></radialGradient><radialGradient id="iPRoNnL" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -3.70312 0 24.043 20.063)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="p7prpqhjw"/><stop offset="1" class="m4mhe8bqv"/></radialGradient><radialGradient id="iOgo57h" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.76563 6.85285 0 14.734 21.438)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="ee8yo8bto"/><stop offset="1" class="dn7nvsb1v"/></radialGradient><radialGradient id="ixTCUsb" cx="0" cy="0" r="1" gradientTransform="scale(1.82355 1.69641)rotate(90 -.8 8.88)" gradientUnits="userSpaceOnUse"><stop class="dp83cpbjl"/><stop offset="1" class="d7z3r5b0e"/></radialGradient><radialGradient id="iEUdCfb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 26.796 23.749)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="x9sp0lxpb"/><stop offset="1" class="fzpj5-hyz"/></radialGradient><radialGradient id="iYx2EHb" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 26.205 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="ifFH9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 32.088 -22.467)scale(.99437 .32275)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="ky_dg6bhp"/><stop offset="1" class="qwfi8obtf"/></radialGradient><radialGradient id="i294t4w" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45773 0 0 -.25781 25.259 22.922)" gradientUnits="userSpaceOnUse"><stop class="wp6rq3sqk"/><stop offset="1" class="hnxygroex"/></radialGradient><radialGradient id="irXsggA" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 24.568 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iGAXcHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 24.568 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i16MIqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 24.568 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iwHUrfZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 24.568 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iR2iq9a" cx="0" cy="0" r="1" gradientTransform="matrix(-.41657 3.3751 -4.1856 -.5166 20.301 8.858)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="g20ie9-kx"/><stop offset=".811" class="ix5prrbkm"/></radialGradient><radialGradient id="iS6Ohib" cx="0" cy="0" r="1" gradientTransform="matrix(1.27242 -.46819 .30286 .8231 19.9 12.234)" gradientUnits="userSpaceOnUse"><stop class="wry8bcbts"/><stop offset="1" class="j3aw0eb-i"/></radialGradient><radialGradient id="iVFif9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.66406 -.0616 .11497 -1.2396 9.736 10.624)" gradientUnits="userSpaceOnUse"><stop class="umogei_uo"/><stop offset="1" class="kzrzyfs2s"/></radialGradient><radialGradient id="iOjV5pd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.85065 3.01535 -4.036 -7.831 17.594 10.086)" gradientUnits="userSpaceOnUse"><stop class="l831-vdhm"/><stop offset=".792" class="uk1rllu7c"/></radialGradient><radialGradient id="ilm5E1U" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5625 -2.23353 0 15.931 7.24)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="o8qsov-gv"/><stop offset="1" class="xy1hnebch"/></radialGradient><radialGradient id="iSDjEKq" cx="0" cy="0" r="1" gradientTransform="matrix(1.60937 3.9464 -3.64909 1.48813 19.822 7.21)" gradientUnits="userSpaceOnUse"><stop offset=".068" class="bugteub2d"/><stop offset="1" class="pxy3tzb7j"/></radialGradient><radialGradient id="iI9tjLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.05615 -8.39787 0 14.719 9.74)" gradientUnits="userSpaceOnUse"><stop offset=".601" class="k8g_t3bck"/><stop offset="1" class="g-rb_3bjy"/></radialGradient><radialGradient id="iN8Tvbb" cx="0" cy="0" r="1" gradientTransform="rotate(-139.611 8.044 2.515)scale(1.37447 .89292)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="x6pc4sbye"/><stop offset="1" class="a_--kffsi"/></radialGradient><radialGradient id="iG7Blxd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.125 2.85938 -1.45866 -2.1043 11.572 6.61)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="hddvf2b6l"/><stop offset="1" class="chus_4bcf"/><stop offset="1" class="n0q_375iv"/></radialGradient><radialGradient id="izbRTfH" cx="0" cy="0" r="1" gradientTransform="matrix(2.23981 -1.1263 4.59356 9.13498 14.23 14.3)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ipdtO8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81164 -1.291 0 16.917 10.027)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="illsOim" cx="0" cy="0" r="1" gradientTransform="matrix(-.23182 -.29873 .41128 -.31916 16.688 10.111)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ia1chte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81164 -1.29101 0 12.55 10.027)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i7Oj7Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49386 .59363 -.0093 12.264 10.246)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ic8iSPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3125 -.47665 0 23.309 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="y66dh_b5l"/><stop offset="1" class="nzjwoybta"/></radialGradient><radialGradient id="iLeaTZU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40034 6.13 0 14.849 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="ixw-oi7aq"/><stop offset="1" class="mguibccfx"/></radialGradient><radialGradient id="ijzTWdd" cx="0" cy="0" r="1" gradientTransform="rotate(129.472 9.359 6.843)scale(6.19389 12.2026)" gradientUnits="userSpaceOnUse"><stop class="qyg3b1b6n"/><stop offset="1" class="p64oiyb7x"/></radialGradient><radialGradient id="iT74aTv" cx="0" cy="0" r="1" gradientTransform="rotate(146.725 7.907 4.576)scale(9.56883 10.9225)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="yytwt1d8s"/><stop offset="1" class="s1a8ycb7r"/></radialGradient><radialGradient id="iCmdwmN" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71875 -10.576 0 14.791 6.156)" gradientUnits="userSpaceOnUse"><stop class="z2rllvutr"/><stop offset="1" class="t8ye-ilvp"/></radialGradient><filter id="iuMZfRc" width="15.024" height="15.274" x="7.337" y="2.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.211765 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="irmXOzc" width="22.99" height="15" x="3.739" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.431373 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="itoRxxb" width="5.492" height="8.119" x="9.76" y="14.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".5"/></filter><filter id="iKZdCxv" width="5.492" height="8.113" x="13.872" y="15.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".5"/></filter><filter id="ieWSf3g" width="3.592" height="6.219" x="10.712" y="15.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.337255 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="iC4FfXb" width="3.02" height="8.58" x="23.729" y="14.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.501961 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="iCtTklb" width="3.675" height="3.685" x="24.636" y="12.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.870588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="i0SMake" width="4.468" height="5.556" x="22.131" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="iXlJbPb" width="2.097" height=".3" x="22.598" y="25.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".05"/></filter><filter id="iZ5kF2c" width="2.097" height=".3" x="22.52" y="27.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".05"/></filter><filter id="ipONudc" width="2.097" height=".3" x="22.598" y="28.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".05"/></filter><filter id="iD74O2c" width="3.319" height="3.219" x="8.436" y="9.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.423529 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="i539Zmb" width="3.149" height="3.149" x="17.988" y="9.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".25"/></filter><filter id="i8Nehhb" width="2.649" height="2.649" x="8.741" y="9.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".125"/></filter><filter id="i6uBh3d" width="10.706" height="10.881" x="9.616" y="5.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.427451 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="im8RPXc" width="2.878" height="3.683" x="13.132" y="9.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".25"/></filter><filter id="iG6yQje" width="2.078" height="2.883" x="13.695" y="9.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.32549 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/><feGaussianBlur result="effect2_foregroundBlur_4002_2027" stdDeviation=".05"/></filter><filter id="iQs4B3c" width="3.704" height="1.526" x="12.882" y="12.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".05"/></filter><filter id="iQE1OCd" width="3.002" height="1.286" x="15.676" y="9.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="iLv1W6d" width="3.002" height="1.286" x="10.789" y="9.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="iJaJqUb" width="2.354" height="1.091" x="10.924" y="7.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="ik2Lxkd" width="2.354" height="1.091" x="16.343" y="7.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="i5aj5Yb" width=".787" height=".696" x="16.182" y="9.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".05"/></filter><filter id="iRSMkPd" width=".891" height=".913" x="17.022" y="9.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".1"/></filter><filter id="iyYfcde" width=".986" height="1.04" x="12.578" y="9.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".1"/></filter><filter id="i4G1beu" width=".913" height=".704" x="11.823" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".05"/></filter><filter id="iuaciRd" width="2.211" height=".928" x="16.399" y="7.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".1"/></filter><filter id="itWFTsd" width="2.211" height=".928" x="10.945" y="7.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".1"/></filter><filter id="iWc4GJc" width="15.17" height="4.76" x="7.155" y="5.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.47451 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.329412 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2027" result="effect2_innerShadow_4002_2027"/></filter><filter id="iCG6NGb" width="9.99" height="2.47" x="9.739" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.843137 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="iEZYiAe" width="6.31" height="2.47" x="13.419" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.890196 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2027"/></filter><filter id="ijSWnmd" width="1.556" height="3.181" x="14.141" y="9.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2027" stdDeviation=".15"/></filter><linearGradient id="iE3txCb" x1="21.65" x2="12.3" y1="12.584" y2="17.31" gradientUnits="userSpaceOnUse"><stop class="x0fpu16bk"/><stop offset="1" class="ucknu6wzv"/></linearGradient><linearGradient id="i1Pd52d" x1="14.735" x2="14.735" y1="16.438" y2="30.563" gradientUnits="userSpaceOnUse"><stop class="troaenb0e"/><stop offset="1" class="jsbk_hbmd"/></linearGradient><linearGradient id="it3vqkc" x1="10.637" x2="11.379" y1="18.219" y2="18.242" gradientUnits="userSpaceOnUse"><stop offset=".344" class="u9ri-jbkw"/><stop offset="1" class="j0xtzac4y"/></linearGradient><linearGradient id="igSiocc" x1="18.805" x2="18.012" y1="18.937" y2="18.937" gradientUnits="userSpaceOnUse"><stop class="ph46gxbvy"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iQD9PdN" x1="16.746" x2="17.254" y1="20.766" y2="19.984" gradientUnits="userSpaceOnUse"><stop class="sq-bwm1qa"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="i5m29vW" x1="7.769" x2="5.387" y1="27.844" y2="27.844" gradientUnits="userSpaceOnUse"><stop class="r5fk93cur"/><stop offset="1" class="bl3c3b0wv"/></linearGradient><linearGradient id="ibY3Hwd" x1="12.584" x2="13.536" y1="16.298" y2="16.298" gradientUnits="userSpaceOnUse"><stop class="rjt1bgbei"/><stop offset="1" class="su429docc"/></linearGradient><linearGradient id="ilUJdLc" x1="17.009" x2="16.009" y1="16.64" y2="16.64" gradientUnits="userSpaceOnUse"><stop offset=".125" class="nxvboccsw"/><stop offset="1" class="wakofwbmw"/></linearGradient><linearGradient id="iUEJUid" x1="25.259" x2="23.652" y1="24.265" y2="24.265" gradientUnits="userSpaceOnUse"><stop class="ec1jnjbjz"/><stop offset="1" class="yd41utmlw"/></linearGradient><linearGradient id="ipsyrne" x1="25.442" x2="26.863" y1="15.852" y2="14.43" gradientUnits="userSpaceOnUse"><stop class="tgqsm4b7j"/><stop offset="1" class="k1-983bet"/></linearGradient><linearGradient id="iRrCpFd" x1="26.159" x2="22.131" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="il7Uzxb" x1="22.748" x2="24.458" y1="26.08" y2="26.08" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iClF6kr" x1="22.67" x2="24.38" y1="27.385" y2="27.385" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iNjvqRd" x1="22.748" x2="24.458" y1="28.689" y2="28.689" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iJRVmSd" x1="9.291" x2="10.046" y1="9.109" y2="12.094" gradientUnits="userSpaceOnUse"><stop class="az85o9bon"/><stop offset="1" class="f1zkfi02k"/></linearGradient><linearGradient id="iVnS8Wd" x1="20.236" x2="19.563" y1="10.015" y2="11.698" gradientUnits="userSpaceOnUse"><stop offset=".355" class="frptkoqkb"/><stop offset=".873" class="bmiekbbkf"/></linearGradient><linearGradient id="i4qyZjd" x1="14.719" x2="14.719" y1="6.999" y2="7.656" gradientUnits="userSpaceOnUse"><stop offset=".399" class="b6706bc6q"/><stop offset="1" class="l971y_bpv"/></linearGradient><linearGradient id="iPso2cj" x1="15.111" x2="15.111" y1="10.185" y2="12.518" gradientUnits="userSpaceOnUse"><stop offset=".729" class="utxzoibhw"/><stop offset="1" class="e4bnjhbpq"/></linearGradient><linearGradient id="iXUmSdd" x1="13.5" x2="13.84" y1="14.05" y2="13.178" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iz27EMc" x1="17.694" x2="17.381" y1="10.08" y2="10.274" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMcjOzc" x1="13.294" x2="12.981" y1="10.08" y2="10.274" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icBL91d" x1="6.356" x2="7.059" y1="7.633" y2="6.703" gradientUnits="userSpaceOnUse"><stop class="qo28zhh9b"/><stop offset="1" class="yhrc8s1zu"/></linearGradient><linearGradient id="ibvcPeT" x1="22.462" x2="22.462" y1="6" y2="8.01" gradientUnits="userSpaceOnUse"><stop class="ott3_jqut"/><stop offset="1" class="l8p6brbrs"/></linearGradient><linearGradient id="iE9kqQd" x1="15.051" x2="15.051" y1="7.33" y2="7.174" gradientUnits="userSpaceOnUse"><stop class="j3h4o1d7b"/><stop offset="1" class="lo1ogpbbw"/></linearGradient><linearGradient id="ivqY3ab" x1="6.787" x2="7.841" y1="7.125" y2="7.125" gradientUnits="userSpaceOnUse"><stop class="it1_ig0bc"/><stop offset="1" class="qgmif2bih"/></linearGradient><linearGradient id="iQ1Swud" x1="14.919" x2="14.919" y1="9.584" y2="12.165" gradientUnits="userSpaceOnUse"><stop offset=".128" class="y9fhw5bke"/><stop offset="1" class="yrfobccjy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-factory-worker-medium" /></template>
<style>
.a_--kffsi {
  stop-color: var(--svg-color--8b5a63, #8B5A63);
  stop-opacity: 0;
}

.a1i_j40xh {
  fill: var(--svg-color--3c77cf, #3C77CF);
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.a424ylq9x {
  fill: var(--svg-color--3674c9, #3674C9);
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.ac3zfwb5z {
  fill: var(--svg-color--8cf5ff, #8CF5FF);
  d: path("m16.169 2l-2.45 2.37h5.45c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19z");
}

.ah-0903bl {
  d: path("m14.748 11.804l.02-2.22l.476 2.297h.01a.142.142 0 0 1 0 .284h-.67a.142.142 0 0 1 0-.284h.088a.077.077 0 0 0 .076-.077");
}

.az85o9bon {
  stop-color: var(--svg-color--5b383b, #5B383B);
}

.b6706bc6q {
  stop-color: var(--svg-color--774552, #774552);
}

.b9xd2sfxu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.852 9.738c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.bbqwceq4e {
  stop-color: var(--svg-color--3878e5, #3878E5);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bl3c3b0wv {
  stop-color: var(--svg-color--3e6fc6, #3E6FC6);
  stop-opacity: 0;
}

.bmiekbbkf {
  stop-color: var(--svg-color--865d54, #865D54);
}

.bugteub2d {
  stop-color: var(--svg-color--4f2c3a, #4F2C3A);
}

.bzs2-ddka {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 26.002h1.797");
}

.chus_4bcf {
  stop-color: var(--svg-color--592e3d, #592E3D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d7sh3eboe {
  stop-color: var(--svg-color--26386d, #26386D);
}

.d7z3r5b0e {
  stop-color: var(--svg-color--986b69, #986B69);
}

.d8j-r9bsb {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.876 10.055c.266-.467.67-.836 1.538-.836c.38 0 .747.105 1.073.369c.27.217.233.495.025.6l-.556.317c-.652-.211-1.373-.24-2.08-.45");
}

.dn7nvsb1v {
  stop-color: var(--svg-color--806879, #806879);
}

.dp83cpbjl {
  stop-color: var(--svg-color--a36b7b, #A36B7B);
}

.dw3xeubwh {
  d: path("M19.563 12.234a1.61 1.61 0 1 0 0-3.22a1.61 1.61 0 0 0 0 3.22");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4bnjhbpq {
  stop-color: var(--svg-color--90586e, #90586E);
}

.e5n7-cbky {
  d: path("M14.739 15.5c-6.07 0-11 4.92-11 11V30h20.99a1 1 0 0 0 1-1v-2.5c0-6.08-4.92-11-10.99-11");
}

.ec1jnjbjz {
  stop-color: var(--svg-color--675479, #675479);
}

.ee8yo8bto {
  stop-color: var(--svg-color--806879, #806879);
  stop-opacity: 0;
}

.eh59-c2og {
  d: path("M10.046 12.234a1.61 1.61 0 1 0 0-3.22a1.61 1.61 0 0 0 0 3.22");
}

.f1zkfi02k {
  stop-color: var(--svg-color--804f60, #804F60);
}

.fbjx3y-qb {
  d: path("M25.449 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.frptkoqkb {
  stop-color: var(--svg-color--69414a, #69414A);
}

.ft5dv1b6b {
  fill: none;
}

.fzpj5-hyz {
  stop-color: var(--svg-color--754d41, #754D41);
}

.g-rb_3bjy {
  stop-color: var(--svg-color--955485, #955485);
}

.g20ie9-kx {
  stop-color: var(--svg-color--503034, #503034);
}

.g8y5_ueit {
  d: path("M9.616 8.631c.02-.949.574-1.316.81-1.439q.024-.008.052-.02l.05-.02c.534-.246.986-.516 1.211-1.078l.082-.194a.264.264 0 0 1 .462-.05c.718 1.05 1.878.147 3.15.147h3.221c.18 0 1.114.102 1.168 1.347l-.11 4.586c-.123 2.804-2.312 4.686-4.985 4.686c-2.672 0-4.862-1.882-4.985-4.686z");
}

.g9arp8b8o {
  d: path("M22.819 8.01h-.713a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.713c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.hddvf2b6l {
  stop-color: var(--svg-color--744351, #744351);
}

.hnxygroex {
  stop-color: var(--svg-color--624b78, #624B78);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ii_vcdblz {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M10.76 16.494v4.63c-.002.26.024.579.25.72c.234.144.581-.02.743-.142l2.5-1.765V15.78a11 11 0 0 0-3.492.713");
}

.it1_ig0bc {
  stop-color: var(--svg-color--57525e, #57525E);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iv7bj_baj {
  stop-color: var(--svg-color--4680db, #4680DB);
  stop-opacity: 0;
}

.ix5prrbkm {
  stop-color: var(--svg-color--a67f76, #A67F76);
}

.ixw-oi7aq {
  stop-color: var(--svg-color--3d3248, #3D3248);
}

.iycy_sbnz {
  d: path("M7.366 8.01h-.707a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.707c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.j0xtzac4y {
  stop-color: var(--svg-color--4d79b0, #4D79B0);
  stop-opacity: 0;
}

.j3aw0eb-i {
  stop-color: var(--svg-color--93616c, #93616C);
  stop-opacity: 0;
}

.j3h4o1d7b {
  stop-color: var(--svg-color--391f48, #391F48);
}

.javsik_yi {
  fill: var(--svg-color--f3d8ed, #F3D8ED);
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.jg7a3hcoh {
  stop-color: var(--svg-color--372f32, #372F32);
}

.jsbk_hbmd {
  stop-color: var(--svg-color--3e80ff, #3E80FF);
}

.jt6x1fb4w {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.335 13.148a.205.205 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.983 1.983 0 0 0 3.334 0a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.247-.041a3 3 0 0 1-1.4.339c-.512 0-.994-.124-1.398-.34Z");
}

.jv7e0m1bl {
  d: path("M12.549 9.55a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.k1-983bet {
  stop-color: var(--svg-color--8cffff, #8CFFFF);
}

.k8g_t3bck {
  stop-color: var(--svg-color--986077, #986077);
  stop-opacity: 0;
}

.kc9q3mbff {
  fill: var(--svg-color--c6c6c6, #C6C6C6);
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.knosl_37y {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.126 9.278c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.ky_dg6bhp {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
}

.kzrzyfs2s {
  stop-color: var(--svg-color--69424a, #69424A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l831-vdhm {
  stop-color: var(--svg-color--b18771, #B18771);
}

.l8p6brbrs {
  stop-color: var(--svg-color--38234f, #38234F);
}

.l8qslmb5u {
  d: path("M14.734 13.537a3 3 0 0 1-1.422-.345c-.141-.073-.292.089-.204.22a1.933 1.933 0 0 0 3.251 0c.089-.136-.062-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.l971y_bpv {
  stop-color: var(--svg-color--774552, #774552);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkgfrvbcs {
  d: path("M16.852 9.738c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.lo1ogpbbw {
  stop-color: var(--svg-color--391f48, #391F48);
  stop-opacity: 0;
}

.lt_b3wboz {
  d: path("m3.769 30l4-.02l-.06-11.94a11 11 0 0 0-3.563 5.482c-.262.948-.4 1.947-.397 2.978z");
}

.ltwsa8bld {
  d: path("M7.757 10.031c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.47c.27 0 .48-.22.48-.48v-3.24c0-2.36-1.91-4.27-4.27-4.27h-7.45a4.253 4.253 0 0 0-4.27 4.26v3.24c0 .27.21.49.48.49z");
}

.m1_q07_me {
  stop-color: var(--svg-color--6899f0, #6899F0);
}

.m3dxw5b4u {
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.m4mhe8bqv {
  stop-color: var(--svg-color--4f94d3, #4F94D3);
  stop-opacity: 0;
}

.m8_l30tsr {
  stop-color: var(--svg-color--2a3765, #2A3765);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.memsme0ni {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.882 8.25c-.323-.078-1.125-.039-1.662.345");
}

.mguibccfx {
  stop-color: var(--svg-color--2a193d, #2A193D);
}

.mx797o4di {
  stop-color: var(--svg-color--4086f6, #4086F6);
}

.n0q_375iv {
  stop-color: var(--svg-color--744351, #744351);
  stop-opacity: 0;
}

.na59ribzw {
  d: path("M28.245 13.16c.081-.326-.151-.554-.478-.472c-.878.18-2.296.406-2.714.954c-.571.613-.55 1.582.03 2.184a1.577 1.577 0 0 0 2.256.01c.503-.512.733-1.836.906-2.676");
}

.ngwa02-tu {
  fill: var(--svg-color--000, #000);
  d: path("M16.407 10.442a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.236");
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nxvboccsw {
  stop-color: var(--svg-color--482a2c, #482A2C);
}

.nzjwoybta {
  stop-color: var(--svg-color--675878, #675878);
  stop-opacity: 0;
}

.o12zmvuzn {
  d: path("M20.756 7.641a7.5 7.5 0 0 0-2.31-1.49c-1.09-.45-2.32-.68-3.66-.68c-1.22 0-2.36.2-3.38.6c-.84.33-1.61.79-2.28 1.38c-1.16 1-1.69 2.07-1.83 2.37c-.03.07-.04.14-.04.21h.5c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.5c0-.06-.01-.11-.03-.17c-.01-.05-.41-1.14-1.54-2.22");
}

.o8qsov-gv {
  stop-color: var(--svg-color--a98077, #A98077);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojb-ttbmo {
  fill: var(--svg-color--c4ffff, #C4FFFF);
  d: path("M10.299 4.37h8.87c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19h-7.45c-.44 0-.87.07-1.27.19v1.62c0 .31.25.56.56.56");
}

.oool1tdti {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 28.611h1.797");
}

.ott3_jqut {
  stop-color: var(--svg-color--534065, #534065);
}

.p3_97vb4n {
  stop-color: var(--svg-color--465e8a, #465E8A);
  stop-opacity: 0;
}

.p64oiyb7x {
  stop-color: var(--svg-color--55406a, #55406A);
}

.p7prpqhjw {
  stop-color: var(--svg-color--5da7f2, #5DA7F2);
}

.pdra6ipeg {
  d: path("M17.713 10.324a.84.84 0 0 0-.23-.462l-.26.285l.117.228z");
}

.ph46gxbvy {
  stop-color: var(--svg-color--4f8dd8, #4F8DD8);
}

.pi6c47yng {
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.pjsi77bhr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.67 27.307h1.797");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmh75mbyu {
  fill: var(--svg-color--202020, #202020);
  d: path("m11.335 8.845l-.005.003a.268.268 0 0 1-.275-.46l.001-.001l.003-.002l.01-.006l.032-.018q.041-.023.116-.058a3 3 0 0 1 .41-.162c.34-.109.816-.2 1.329-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.073.092a3 3 0 0 0-.455.193");
}

.pmikb6mtj {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.591 10.055c-.265-.467-.669-.836-1.538-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.024.6l.556.317c.652-.211 1.373-.24 2.08-.45");
}

.ppjvl5bbu {
  stop-color: var(--svg-color--372f32, #372F32);
  stop-opacity: 0;
}

.pxy3tzb7j {
  stop-color: var(--svg-color--61384a, #61384A);
  stop-opacity: 0;
}

.qgmif2bih {
  stop-color: var(--svg-color--57525e, #57525E);
  stop-opacity: 0;
}

.qjc1qgb0d {
  fill: var(--svg-color--000, #000);
  d: path("M13.06 10.442a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747H13a.5.5 0 0 0 .061-.236");
}

.qo28zhh9b {
  stop-color: var(--svg-color--3a2252, #3A2252);
}

.qtzewq2gr {
  d: path("M22.13 25.326c0-.402.326-.732.727-.732h2.392a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.qv8wc6zla {
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwfi8obtf {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
  stop-opacity: 0;
}

.qyg3b1b6n {
  stop-color: var(--svg-color--6f5b84, #6F5B84);
}

.r5fk93cur {
  stop-color: var(--svg-color--2869c1, #2869C1);
}

.rin7jfzij {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.674 8.25c.323-.078 1.125-.039 1.661.345");
}

.rjt1bgbei {
  stop-color: var(--svg-color--402527, #402527);
}

.rknqf7fgs {
  fill-rule: evenodd;
  d: path("M22.037 12.228a3.25 3.25 0 0 0 .324-1.427a3.3 3.3 0 0 0-.269-1.306h.005a3 3 0 0 0-.28-.514l-.003-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.456-.234a3.3 3.3 0 0 0-2.683-1.377a3.3 3.3 0 0 0-2.683 1.377a.56.56 0 0 1-.456.233l-.085.001a3.3 3.3 0 0 0-3.215 3.3v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.246c.07.142.07.314 0 .456a3.215 3.215 0 0 0 2.895 4.627h8.585a3.215 3.215 0 0 0 3.22-3.22c0-.506-.122-.982-.324-1.407a.52.52 0 0 1 0-.456M10.979 9.555h-.012l-.008 2.356c.123 2.804 1.217 0 3.89 0s3.837 3.12 3.96.317l-.481-3.245c-.054-1.245.662-1.286.482-1.286h-3.221a3.86 3.86 0 0 1-3.191-1.674a.264.264 0 0 0-.462.051l-.082.194c-.225.561.551.99.018 1.235l-.052.02q-.028.013-.05.02c-.237.123-.79.49-.811 1.44l.01.306z");
}

.rq76sybla {
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.rtj8_6bqg {
  stop-color: var(--svg-color--2a3765, #2A3765);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.rxmjvacge {
  d: path("M13.364 10.337c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.s1a8ycb7r {
  stop-color: var(--svg-color--362d41, #362D41);
}

.s1rw4px-b {
  stop-color: var(--svg-color--465e8a, #465E8A);
}

.s21zh4b3w {
  stop-color: var(--svg-color--3d78d0, #3D78D0);
  stop-opacity: 0;
}

.s3p5lff5x {
  d: path("M16.919 9.55a.893.893 0 0 1 .86 1.127h-1.725a.896.896 0 0 1 .864-1.128");
}

.s5pm96b_v {
  stop-color: var(--svg-color--3578e5, #3578E5);
  stop-opacity: 0;
}

.sb1phf9zd {
  d: path("M20.979 4.68H8.719v2.65h12.26z");
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sq-bwm1qa {
  stop-color: var(--svg-color--1f54c5, #1F54C5);
}

.su429docc {
  stop-color: var(--svg-color--5d383e, #5D383E);
  stop-opacity: 0;
}

.t8ye-ilvp {
  stop-color: var(--svg-color--7b51c6, #7B51C6);
}

.tgqsm4b7j {
  stop-color: var(--svg-color--5cd3e2, #5CD3E2);
}

.tizux9w7p {
  stop-color: var(--svg-color--3877cc, #3877CC);
  stop-opacity: 0;
}

.troaenb0e {
  stop-color: var(--svg-color--428ef7, #428EF7);
}

.u-q3e7b8s {
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.u9ri-jbkw {
  stop-color: var(--svg-color--547eb3, #547EB3);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.ucknu6wzv {
  stop-color: var(--svg-color--1b1121, #1B1121);
}

.ue1gv6enh {
  d: path("M25.259 25.94h-2.05v-3c0-.19.16-.35.35-.35h1.35c.19 0 .35.16.35.35z");
}

.uk1rllu7c {
  stop-color: var(--svg-color--8f6461, #8F6461);
}

.umogei_uo {
  stop-color: var(--svg-color--6f4345, #6F4345);
}

.utxzoibhw {
  stop-color: var(--svg-color--9e7667, #9E7667);
}

.v-p3thbyp {
  cx: 12.279px;
  cy: 9.931px;
  rx: 0.389px;
  ry: 0.197px;
}

.v6_fcq9so {
  cx: 12.279px;
  cy: 9.931px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.v9wc5kdsn {
  d: path("M10.066 11.698a1.075 1.075 0 1 0 0-2.149a1.075 1.075 0 0 0 0 2.15");
}

.vbc9nqbss {
  fill: var(--svg-color--1e64bd, #1E64BD);
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.vczswwwcd {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.151 15.597a.85.85 0 1 0 0-1.7a.85.85 0 0 0 0 1.7");
}

.vxca8ab-k {
  d: path("m14.351 10.263l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.766 0");
}

.wakofwbmw {
  stop-color: var(--svg-color--6a4844, #6A4844);
  stop-opacity: 0;
}

.wallrjjxc {
  d: path("M14.734 18.117c-.865 0-2.01-.576-2.01-1.729v-3.02c0-1.143.897-2.074 2.01-2.074s2.01.93 2.01 2.083v3.021c-.01 1.143-1.146 1.719-2.01 1.719");
}

.wg_w1vbgj {
  d: path("M19.563 11.698a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.15");
}

.wp6rq3sqk {
  stop-color: var(--svg-color--6e5981, #6E5981);
}

.wry8bcbts {
  stop-color: var(--svg-color--93616c, #93616C);
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.x0fpu16bk {
  stop-color: var(--svg-color--271b26, #271B26);
}

.x6pc4sbye {
  stop-color: var(--svg-color--8b5a63, #8B5A63);
}

.x9-b3hbfy {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M18.365 16.768v4.575c.002.26-.024.578-.25.719c-.234.145-.581-.018-.743-.14l-2.5-1.766v-4.15c1.229.064 2.403.328 3.492.762");
}

.x9sp0lxpb {
  stop-color: var(--svg-color--b48974, #B48974);
}

.xl-8m7bem {
  fill: var(--svg-color--202020, #202020);
  fill-rule: evenodd;
  d: path("m18.467 8.388l-.138.23za.268.268 0 0 1-.276.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.073-.092a.268.268 0 0 1-.093-.528c.513-.091.989 0 1.329.109a3.3 3.3 0 0 1 .559.238l.01.006l.002.002z");
}

.xy1hnebch {
  stop-color: var(--svg-color--a98077, #A98077);
  stop-opacity: 0;
}

.y66dh_b5l {
  stop-color: var(--svg-color--675878, #675878);
}

.y8uqe7b6k {
  stop-color: var(--svg-color--3f3531, #3F3531);
  stop-opacity: 0;
}

.y9d5neb6h {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.342 9.278c-.654 0-1.206.45-1.356 1.059c-.044.174.09.34.268.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.y9fhw5bke {
  stop-color: var(--svg-color--bf9887, #BF9887);
  stop-opacity: 0;
}

.yd41utmlw {
  stop-color: var(--svg-color--32263f, #32263F);
}

.yhrc8s1zu {
  stop-color: var(--svg-color--31263f, #31263F);
}

.ymyjruwrb {
  stop-color: var(--svg-color--3a2d2b, #3A2D2B);
}

.ypv_kpaja {
  stop-color: var(--svg-color--4680db, #4680DB);
}

.yrfobccjy {
  stop-color: var(--svg-color--bf9887, #BF9887);
}

.yytwt1d8s {
  stop-color: var(--svg-color--362d41, #362D41);
  stop-opacity: 0;
}

.z2rllvutr {
  stop-color: var(--svg-color--8c68d5, #8C68D5);
}

.zadlptbzn {
  fill: var(--svg-color--875659, #875659);
  d: path("m14.341 10.401l-.684 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.494-.377-.613 0");
}

.zexrct42f {
  stop-color: var(--svg-color--3a2d2b, #3A2D2B);
  stop-opacity: 0;
}

</style>
