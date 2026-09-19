<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLsCL1b)"><path fill="url(#iinPw8D)" class="cwwuu-zus"/><path fill="url(#iaBBtbd)" class="cwwuu-zus"/></g><g filter="url(#itCp8Ge)"><path fill="url(#iiEqr2b)" class="ql_s_gb7e"/><path fill="url(#ioUcBAb)" class="ql_s_gb7e"/></g><path fill="url(#iBiQeDA)" class="cza2qst-y"/><path fill="url(#izpz5ze)" class="cza2qst-y"/><path fill="url(#iKePr8Z)" class="cza2qst-y"/><path fill="url(#i4CpmUc)" class="cza2qst-y"/><path fill="url(#ivSi3bb)" class="cza2qst-y"/><path fill="url(#ircrQDd)" class="cza2qst-y"/><path fill="url(#ifryBne)" class="cza2qst-y"/><path fill="url(#ifGMGfc)" class="cza2qst-y"/><path fill="url(#iPXZfwe)" class="cqqhj6b5l"/><path fill="url(#iBvVYyd)" class="cqqhj6b5l"/><path fill="url(#ihP5YId)" class="cqqhj6b5l"/><path fill="url(#iMs4HDc)" class="cqqhj6b5l"/><path fill="url(#iuiz98k)" class="b8g9wj85t"/><path fill="url(#i9sXN2b)" class="b8g9wj85t"/><path fill="url(#i4RB5Kb)" class="b8g9wj85t"/><path fill="url(#i2tM7DX)" class="b8g9wj85t"/><path fill="url(#i5XrZRD)" class="enuodcxjx"/><path fill="url(#i6bBXnb)" class="xshejgbiq"/><path fill="url(#i4yYkKm)" class="ffppavbjz"/><g filter="url(#i5SUM6R)"><path fill="url(#iz1Zitd)" class="fmw11ojyd"/><path fill="url(#iI76g3c)" class="fmw11ojyd"/><path fill="url(#imd9wXd)" class="fmw11ojyd"/><path fill="url(#iBdek7b)" class="fmw11ojyd"/><path fill="url(#iKtwjae)" class="fmw11ojyd"/></g><path class="zo3xzub3m"/><path fill="url(#iNkC37b)" class="cs3_qu-mq"/><path fill="url(#iPmcduc)" class="cs3_qu-mq"/><path class="ayordobqc"/><path fill="url(#iyRy83b)" class="q2xn-obga"/><g filter="url(#iVZRIKc)"><path fill="url(#iivArnd)" class="aeh8j5ukx"/><path fill="url(#iPBza4d)" class="aeh8j5ukx"/><path fill="url(#imxH5Bd)" class="aeh8j5ukx"/><path fill="url(#iARVvgc)" class="aeh8j5ukx"/><path fill="url(#iaiWMGd)" class="aeh8j5ukx"/><path fill="url(#ivMOxZb)" class="aeh8j5ukx"/></g><g filter="url(#i0YPRKd)"><path fill="url(#iibhYfc)" class="cr8fy0bhj"/></g><path fill="url(#iHKY1Dd)" class="krb7dqh8m"/><path fill="url(#iihvgBd)" class="krb7dqh8m"/><path fill="url(#ibrytKP)" class="uehfnrv2s"/><path fill="url(#i2nPSae)" class="qzls3vb2f"/><path fill="url(#i7cIkAd)" class="qzls3vb2f"/><path fill="url(#ip2g45b)" class="d3177plvc"/><path fill="url(#i6yAJSZ)" class="d3177plvc"/><g filter="url(#iy2ynsc)"><circle fill="url(#izX1t2t)" class="ex3jgac_b"/><circle fill="url(#ihtMJRc)" class="ex3jgac_b"/></g><ellipse fill="url(#iYq9qZb)" transform="rotate(-31.445 16.554 23.452)" class="qt64ghhxa"/><g filter="url(#ifoAkOc)"><circle fill="url(#igOufUc)" class="vid03obgg"/></g><circle fill="url(#iy9C3gd)" class="vid03obgg"/><g filter="url(#ijlQHBb)"><circle fill="url(#iTLhxzV)" class="qki2lm4wo"/></g><g filter="url(#i13rBZB)"><circle fill="url(#iQVRhFd)" class="hen17tbvu"/><circle fill="url(#iWnsrbb)" class="hen17tbvu"/></g><g filter="url(#ihWDT4c)"><circle class="hie7ol4or"/><circle fill="url(#iUzRgXc)" class="swwyfhppg"/><circle fill="url(#ihOqUoc)" class="swwyfhppg"/></g><g filter="url(#irh8l2c)"><path fill="url(#iNsVnKP)" class="ffy61ybxl"/><path fill="url(#iG2b8Db)" class="ffy61ybxl"/><path fill="url(#irkKOxd)" class="ffy61ybxl"/></g><path fill="url(#i70HJcb)" class="q50ar7-tx"/><path fill="url(#iJ6Quoe)" class="q50ar7-tx"/><path fill="url(#iYVkJne)" class="q50ar7-tx"/><path fill="url(#ihxMIpd)" class="q50ar7-tx"/><g filter="url(#iZs1eHb)"><path fill="url(#iWthnpv)" class="np9tgiero"/></g><g filter="url(#i1ujdkC)"><path class="nrytt9b5q"/><path fill="url(#iUhHHfb)" class="oit1kgbnv"/><path fill="url(#iqD2zee)" class="oit1kgbnv"/><path fill="url(#iGyOQoc)" class="oit1kgbnv"/><path fill="url(#i9x8miN)" class="oit1kgbnv"/></g><g filter="url(#iMquAWb)"><path class="vxg30mb5o"/></g><g filter="url(#iSZGDrd)"><path class="au_kqr7xq"/><path fill="url(#ixdHeTc)" class="audnus_bk"/><path fill="url(#isigA3b)" class="audnus_bk"/><path fill="url(#iWCorgA)" class="audnus_bk"/><path fill="url(#iGfDkfc)" class="audnus_bk"/></g><g filter="url(#iWhtwNd)"><path stroke="url(#i6gHIMb)" class="yjzk6_bwe"/></g><path class="yrqfnf2oy"/><path fill="url(#iuJNh4B)" class="x7un6yb_h"/><path class="k561k8ppe"/><g filter="url(#iEPAk0c)"><path class="fb_f0ab6x"/><path fill="url(#iBQYNib)" class="tdxsvibvu"/></g><g filter="url(#iv7t1Mc)"><path fill="url(#ixtN8xd)" class="i9uiobbul"/></g><path class="oh3-d7lzf"/><path fill="url(#i3OTepe)" class="kaoo1uz8s"/><path class="o646v6buz"/><g filter="url(#ipiGoxi)"><path fill="url(#izq1vvd)" class="fd4z9cb9c"/></g><g filter="url(#iWTtnnd)"><ellipse transform="rotate(-27.914 13.59 9.79)" class="g9_sxsbrd"/><ellipse fill="url(#iLImnyc)" transform="rotate(-27.914 13.59 9.79)" class="xnqc2smdc"/></g><g filter="url(#ipE2h5c)"><path class="wp9t5rg1b"/></g><g filter="url(#iLpKHad)"><path fill="url(#iWBVdAc)" class="ygkfonyaf"/><path fill="url(#inhZTwb)" class="ygkfonyaf"/><path fill="url(#icnKn3b)" class="ygkfonyaf"/></g><path fill="url(#iAJt6SQ)" class="ygkfonyaf"/><g filter="url(#iKRlBud)"><path class="c0eecvb8p"/></g><g filter="url(#inInocb)"><path class="hmuq4s6pt"/></g><path class="mcrjo7bzf"/><defs><radialGradient id="iinPw8D" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.293 12.621)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iaBBtbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.586)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iiEqr2b" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.24 4.191)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="ioUcBAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.118 24.587)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iBiQeDA" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.898)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="izpz5ze" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.415 15.195)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="iKePr8Z" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.736)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="ivSi3bb" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.338 17.837)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="ircrQDd" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.21)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="ifryBne" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.586)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iPXZfwe" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.431 25.367)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="iBvVYyd" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.252 20.211)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="ihP5YId" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.648)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="iuiz98k" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.055)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="i9sXN2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.117)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="i4RB5Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.805)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="i2tM7DX" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.398)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="i5XrZRD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.068 21.148)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="i6bBXnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.789)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="i4yYkKm" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.789)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iI76g3c" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.74 58.911)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="imd9wXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.545)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="iBdek7b" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.119 15.867)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="iKtwjae" cx="0" cy="0" r="1" gradientTransform="matrix(3.52963 0 0 2.27341 18.523 16.31)" gradientUnits="userSpaceOnUse"><stop class="ge69a97wz"/><stop offset="1" class="jd18rptxw"/></radialGradient><radialGradient id="iNkC37b" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.523)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="iPmcduc" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.781)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="iyRy83b" cx="0" cy="0" r="1" gradientTransform="matrix(.66797 .16406 -.20923 .85186 6.846 15.64)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="imxH5Bd" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.358 16.43)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iARVvgc" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 12 7.393)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="iaiWMGd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.31239 0 0 -2.83509 14.65 16.242)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="sb_6z1bpd"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="ivMOxZb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.861)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="iibhYfc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.3667 .90626 -1.59163 -5.9128 17.338 16.805)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="odam8hbyg"/><stop offset="1" class="du8_b9dvn"/></radialGradient><radialGradient id="iHKY1Dd" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.53 11.507)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="iihvgBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.775 16.914)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="ibrytKP" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.664)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="i2nPSae" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.793 20.913)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="i7cIkAd" cx="0" cy="0" r="1" gradientTransform="rotate(-29.297 36.7 -7.127)scale(.99044 .92102)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="ip2g45b" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.181 16.633)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="i6yAJSZ" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.52344 .50555 .83423 10.26 17.102)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="izX1t2t" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.102 16.937)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="ihtMJRc" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.43)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="igOufUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 9.607 10.67)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iy9C3gd" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.851 3.234)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iWnsrbb" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.16 10.406)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iUzRgXc" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.747 11.492)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="ihOqUoc" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.58 30.612)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iG2b8Db" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.37 9.4)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="irkKOxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 13.812 9.534)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iYVkJne" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.32774 -10.3217 0 15.896 9.137)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="lw_54jmvs"/><stop offset=".988" class="jkkarfbaa"/></radialGradient><radialGradient id="ihxMIpd" cx="0" cy="0" r="1" gradientTransform="rotate(-128.779 8.884 1.037)scale(5.17314 2.21233)" gradientUnits="userSpaceOnUse"><stop class="vqnicvviz"/><stop offset="1" class="xcrsoe6-m"/></radialGradient><radialGradient id="iUhHHfb" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.47 -10.014)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iqD2zee" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -42.964 206.323)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iGyOQoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 16.024 2.07)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="i9x8miN" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.576 8.888)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iGfDkfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.35 12.277)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iuJNh4B" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.229 9.885)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iBQYNib" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3OTepe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.862 9.885)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iLImnyc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.761 -1.63)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWBVdAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.229)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="c7yfkfb_x"/><stop offset=".878" class="ly-mhyl9x"/></radialGradient><radialGradient id="inhZTwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 12.986)" gradientUnits="userSpaceOnUse"><stop class="cycj4pb5c"/><stop offset="1" class="xkd2ooi4v"/></radialGradient><radialGradient id="icnKn3b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25001 4.51317 -4.6352 -5.39197 23.432 6.229)" gradientUnits="userSpaceOnUse"><stop class="mbbg-bcay"/><stop offset="1" class="psls5zbwz"/><stop offset="1" class="vyoyvyblw"/></radialGradient><filter id="iLsCL1b" width="7.981" height="13.148" x="1.991" y="16.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/></filter><filter id="itCp8Ge" width="7.981" height="13.148" x="22.028" y="16.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/></filter><filter id="i5SUM6R" width="9.078" height="5.683" x="17.916" y="15.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/></filter><filter id="iVZRIKc" width="8.928" height="5.533" x="5.258" y="15.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/></filter><filter id="i0YPRKd" width="4.194" height="5.942" x="13.971" y="12.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/></filter><filter id="iy2ynsc" width="3.465" height="3.465" x="14.33" y="22.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/></filter><filter id="ifoAkOc" width="3.539" height="3.339" x="9.607" y="9.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/></filter><filter id="ijlQHBb" width="2.99" height="2.99" x="9.781" y="9.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation=".25"/></filter><filter id="i13rBZB" width="3.589" height="3.589" x="19.119" y="8.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/></filter><filter id="ihWDT4c" width="2.99" height="2.99" x="19.294" y="9.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation=".25"/></filter><filter id="irh8l2c" width="10.373" height="12.177" x="10.866" y="5.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/></filter><filter id="iZs1eHb" width="8.246" height="7.066" x="14.194" y="3.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation="1"/></filter><filter id="i1ujdkC" width="12.601" height="8.543" x="9.724" y="1.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/></filter><filter id="iMquAWb" width="3.26" height="4.181" x="14.155" y="9.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation=".375"/></filter><filter id="iSZGDrd" width="2.377" height="3.181" x="14.835" y="9.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation=".125"/></filter><filter id="iWhtwNd" width="1.008" height="2.269" x="10.858" y="5.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation=".125"/></filter><filter id="iEPAk0c" width=".787" height=".697" x="17.494" y="9.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation=".05"/></filter><filter id="iv7t1Mc" width=".892" height=".914" x="18.335" y="9.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation=".1"/></filter><filter id="ipiGoxi" width=".987" height="1.041" x="13.889" y="9.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation=".1"/></filter><filter id="iWTtnnd" width=".914" height=".705" x="13.133" y="9.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation=".05"/></filter><filter id="ipE2h5c" width="13.891" height="7.06" x="9.087" y="6.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1006" stdDeviation=".375"/></filter><filter id="iLpKHad" width="15.159" height="7.107" x="8.403" y="6.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.152941 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.333333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1006" result="effect2_innerShadow_4002_1006"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.215686 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1006" result="effect3_innerShadow_4002_1006"/></filter><filter id="iKRlBud" width="2.192" height="1.627" x="17.223" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1006" result="effect2_innerShadow_4002_1006"/></filter><filter id="inInocb" width="2.192" height="1.627" x="12.726" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1006"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1006" result="effect2_innerShadow_4002_1006"/></filter><linearGradient id="i4CpmUc" x1="23.236" x2="22.978" y1="29.93" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="ifGMGfc" x1="8.857" x2="8.994" y1="29.93" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="iMs4HDc" x1="23.252" x2="23.486" y1="29.93" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="iz1Zitd" x1="25.745" x2="20.292" y1="15.867" y2="20.079" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="iivArnd" x1="9.772" x2="9.772" y1="15.861" y2="20.648" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="iPBza4d" x1="9.772" x2="9.772" y1="15.492" y2="17.461" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="iYq9qZb" x1="16.985" x2="15.947" y1="23.067" y2="23.971" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="iTLhxzV" x1="11.276" x2="10.636" y1="10.95" y2="10.95" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iQVRhFd" x1="21.875" x2="21.056" y1="9.579" y2="12.116" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iNsVnKP" x1="20.059" x2="12.423" y1="11.06" y2="12.198" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="i70HJcb" x1="10.628" x2="12.51" y1="13.756" y2="13.689" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iJ6Quoe" x1="20.944" x2="19.832" y1="12.915" y2="12.818" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iWthnpv" x1="15.492" x2="23.635" y1="8.076" y2="5.16" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="ixdHeTc" x1="15.159" x2="16.098" y1="11.72" y2="11.72" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="isigA3b" x1="16.962" x2="15.936" y1="12.042" y2="12.027" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iWCorgA" x1="16.218" x2="16.218" y1="12.784" y2="12.211" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="i6gHIMb" x1="11.362" x2="11.362" y1="5.761" y2="7.918" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="ixtN8xd" x1="19.007" x2="18.693" y1="9.939" y2="10.133" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izq1vvd" x1="14.606" x2="14.292" y1="9.939" y2="10.133" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAJt6SQ" x1="10.733" x2="10.979" y1="10.059" y2="9.898" gradientUnits="userSpaceOnUse"><stop offset=".102" class="a5a8_w8qp"/><stop offset=".478" class="ydi8a_bcj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-supervillain-medium" /></template>
<style>
.a--e2mwlv {
  stop-color: var(--svg-color--614b90, #614B90);
}

.a-lmuhb3j {
  stop-color: var(--svg-color--7560a8, #7560A8);
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a5a8_w8qp {
  stop-color: var(--svg-color--5e5158, #5E5158);
}

.aeh8j5ukx {
  d: path("M7.467 19.857c.75 1.083 1.855 1.977 4.008 1.051c1.836-.789 2.71-3.269 2.71-5.047l-8.202.024c-.653 0-.752.442-.492.855c.645 1.03 1.519 2.406 1.976 3.117");
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.au_kqr7xq {
  fill: var(--svg-color--a17b69, #A17B69);
  d: path("m15.641 10.386l-.53 1.7a.54.54 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.audnus_bk {
  d: path("m15.641 10.386l-.53 1.7a.54.54 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.av5bbdb4i {
  stop-color: var(--svg-color--ff499d, #FF499D);
}

.ayordobqc {
  fill: var(--svg-color--64417a, #64417A);
  d: path("M6.984 15.9c0 .222.249.316.555.316s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.b5r8fe9sv {
  stop-color: var(--svg-color--735ca8, #735CA8);
}

.b8g9wj85t {
  d: path("M8.861 18.087V29.93H4.588c.205-3.07.605-5.613 1.406-7.564c.772-1.88 1.77-3.267 2.867-4.28");
}

.bfw_o9sgk {
  stop-color: var(--svg-color--8977bc, #8977BC);
  stop-opacity: 0;
}

.bkplcs5-b {
  stop-color: var(--svg-color--615181, #615181);
  stop-opacity: 0;
}

.bozoj1btu {
  stop-color: var(--svg-color--e7547f, #E7547F);
  stop-opacity: 0;
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c0eecvb8p {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m19.064 8.723l-1.608.592c-.154.057-.235.23-.147.368c.22.342.656.692 1.345.489c.65-.192.792-.814.755-1.257c-.014-.167-.188-.25-.345-.192");
}

.c50kycc4s {
  stop-color: var(--svg-color--ff5292, #FF5292);
  stop-opacity: 0;
}

.c7yfkfb_x {
  stop-color: var(--svg-color--453753, #453753);
}

.cbuctgb-f {
  stop-color: var(--svg-color--dd225e, #DD225E);
  stop-opacity: 0;
}

.cgymddbwl {
  stop-color: var(--svg-color--3f2563, #3F2563);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqqhj6b5l {
  d: path("M23.252 18.087V29.93h4.273c-.205-3.07-.605-5.613-1.406-7.564c-.772-1.88-1.77-3.267-2.867-4.28");
}

.cr8fy0bhj {
  d: path("M13.971 15.019a2.097 2.097 0 0 1 4.194 0v1.548c0 1.37-.938 2.097-2.097 2.097c-1.158 0-2.097-.695-2.097-2.097z");
}

.cs3_qu-mq {
  d: path("M9.02 15.9c0 .222.248.316.555.316c.306 0 .555-.119.555-.315a.555.555 0 0 0-1.11 0");
}

.ctoai6naw {
  stop-color: var(--svg-color--f93362, #F93362);
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cvb6_wfpd {
  stop-color: var(--svg-color--443063, #443063);
}

.cwwuu-zus {
  d: path("M1.99 29.93h3.532l4.25-8.75l-3.648-4.399C2.71 21.22 1.99 27.164 1.99 29.93");
}

.cx3r1wb0p {
  stop-color: var(--svg-color--8b74c8, #8B74C8);
}

.cycj4pb5c {
  stop-color: var(--svg-color--322f37, #322F37);
}

.cza2qst-y {
  d: path("M4.588 29.93h22.937c-.205-3.07-.605-5.613-1.406-7.564c-2.444-5.955-7.159-6.953-10.062-6.811c-2.904-.142-7.619.856-10.063 6.811c-.8 1.95-1.2 4.494-1.406 7.564");
}

.d-jm4nrou {
  stop-color: var(--svg-color--7757b7, #7757B7);
  stop-opacity: 0;
}

.d3177plvc {
  d: path("M10.065 16.895c0 .292.237.367.53.367c.291 0 .528-.075.528-.367a.53.53 0 0 0-1.058 0");
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dkr4vta7s {
  stop-color: var(--svg-color--8977bc, #8977BC);
}

.do8d1irdg {
  stop-color: var(--svg-color--e1658e, #E1658E);
}

.du8_b9dvn {
  stop-color: var(--svg-color--643b89, #643B89);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1q0bl71g {
  stop-color: var(--svg-color--5f4d85, #5F4D85);
  stop-opacity: 0;
}

.e33ikws-z {
  stop-color: var(--svg-color--ff4574, #FF4574);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e9rx7xb_x {
  stop-color: var(--svg-color--967bc2, #967BC2);
}

.ecn2fkbpq {
  stop-color: var(--svg-color--79659c, #79659C);
  stop-opacity: 0;
}

.enuodcxjx {
  d: path("m15.575 21.26l-2.98-4.596h6.946l-2.958 4.594a.6.6 0 0 1-1.008.002");
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.ex3jgac_b {
  cx: 16.062px;
  cy: 23.939px;
  r: 1.732px;
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f9nu08mzt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
}

.fb_f0ab6x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.165 9.597c.064.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.16-.359c.15-.113.325-.135.388-.05");
}

.fd4z9cb9c {
  d: path("M14.676 10.196c0-.288-.235-.48-.299-.539l-.288.28l.177.36z");
}

.fd6px-b3x {
  stop-color: var(--svg-color--593f75, #593F75);
}

.fdilk9b4n {
  stop-color: var(--svg-color--977fd1, #977FD1);
}

.ffppavbjz {
  d: path("M25.118 15.909c0 .22-.249.315-.555.315s-.556-.119-.556-.315a.555.555 0 0 1 1.11 0");
}

.ffy61ybxl {
  d: path("m10.924 10.058l.05.002s-.054-.853-.108-1.44c0-.267.107-.587.322-.747l.16-.16c.269-.213.376-.533.376-.853v-.853a.52.52 0 0 1 .43-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.271.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.108 1.44-.108 1.44h.018l-.265 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.713 0-3.05-1.234-3.21-3.003z");
}

.fmw11ojyd {
  d: path("M24.635 19.863c-.75 1.082-1.856 1.976-4.008 1.051c-1.836-.789-2.711-3.269-2.711-5.047l8.203.024c.652 0 .752.441.492.855c-.646 1.03-1.52 2.406-1.976 3.117");
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fypjwijgc {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
}

.g2wrz_okq {
  stop-color: var(--svg-color--bb4566, #BB4566);
}

.g9_sxsbrd {
  cx: 13.59px;
  cy: 9.79px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ge69a97wz {
  stop-color: var(--svg-color--961241, #961241);
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hen17tbvu {
  cx: 20.789px;
  cy: 10.671px;
  r: 1.669px;
}

.hie7ol4or {
  cx: 20.789px;
  cy: 10.671px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.hmuq4s6pt {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m13.077 8.723l1.607.592c.154.057.236.23.147.368c-.22.342-.656.692-1.345.489c-.65-.192-.792-.814-.755-1.257c.014-.167.188-.25.346-.192");
}

.i3hug6b7s {
  stop-color: var(--svg-color--655586, #655586);
}

.i9uiobbul {
  d: path("M19.026 10.184a.84.84 0 0 0-.231-.464l-.26.286l.117.228z");
}

.ib49rus2q {
  stop-color: var(--svg-color--72599f, #72599F);
  stop-opacity: 0;
}

.ie12c-fkv {
  stop-color: var(--svg-color--ee205c, #EE205C);
  stop-opacity: 0;
}

.iek0mvbvg {
  stop-color: var(--svg-color--563680, #563680);
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.jd18rptxw {
  stop-color: var(--svg-color--d31c55, #D31C55);
  stop-opacity: 0;
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.jkkarfbaa {
  stop-color: var(--svg-color--944a5a, #944A5A);
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
}

.k561k8ppe {
  fill: var(--svg-color--000, #000);
  d: path("M17.72 10.301a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .456.747h-.906a.46.46 0 0 1-.06-.236");
}

.kaoo1uz8s {
  d: path("M13.86 9.408a.893.893 0 0 0-.861 1.129h1.725a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.893");
}

.kejp2n55e {
  stop-color: var(--svg-color--79659c, #79659C);
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.klsvjl5ds {
  stop-color: var(--svg-color--7056ae, #7056AE);
}

.kr4wgsbgo {
  stop-color: var(--svg-color--533179, #533179);
}

.krb7dqh8m {
  d: path("M22.037 16.902c0 .293-.237.367-.53.367c-.292 0-.529-.074-.529-.367a.53.53 0 0 1 1.059 0");
}

.ksp1sznci {
  stop-color: var(--svg-color--6d55a5, #6D55A5);
  stop-opacity: 0;
}

.l1led_brw {
  stop-color: var(--svg-color--df1d5a, #DF1D5A);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.lw_54jmvs {
  stop-color: var(--svg-color--a16e73, #A16E73);
  stop-opacity: 0;
}

.ly-mhyl9x {
  stop-color: var(--svg-color--4a474e, #4A474E);
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m48igd19d {
  stop-color: var(--svg-color--735aa1, #735AA1);
}

.m9hq76bya {
  stop-color: var(--svg-color--64468e, #64468E);
}

.mbbg-bcay {
  stop-color: var(--svg-color--625570, #625570);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcrjo7bzf {
  fill: var(--svg-color--930458, #930458);
  d: path("M17.75 12.592c-.614.807-1.368.893-1.872.925c-.085.005-.12.104-.051.154c.377.269.857.292 1.342.09c.51-.213.733-.703.747-1.123c.003-.092-.11-.119-.165-.046");
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.mxm28cb7d {
  stop-color: var(--svg-color--735784, #735784);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n1_6kac4r {
  stop-color: var(--svg-color--745b84, #745B84);
}

.n5x1trblw {
  stop-color: var(--svg-color--73629d, #73629D);
}

.n6ixpp1jb {
  stop-color: var(--svg-color--7da646, #7DA646);
}

.n7j357b5a {
  stop-color: var(--svg-color--230f39, #230F39);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.np9tgiero {
  d: path("M19.987 5.047L16.91 6.073a1.047 1.047 0 0 0 .47 2.031l3.06-.41z");
}

.nrytt9b5q {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m20.842 4.194l.43.213c.75.373 1.18 1.227 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.906.108-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.533c-.644-.16-1.984-.427-3.915-.427s-3.272.267-3.916.427a.52.52 0 0 0-.429.533v.853c0 .32-.107.64-.375.853l-.161.16c-.215.16-.322.48-.322.747c.054.587.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.072-2.08l.43-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.054 2.36.533l.805.8c.214.267.482.427.804.587");
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o646v6buz {
  fill: var(--svg-color--000, #000);
  d: path("M14.371 10.301a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.236");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odam8hbyg {
  stop-color: var(--svg-color--835ac7, #835AC7);
}

.ogttk6b6n {
  stop-color: var(--svg-color--774ca5, #774CA5);
}

.oh3-d7lzf {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.653 9.136c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.232a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.oit1kgbnv {
  d: path("m20.842 4.194l.43.213c.75.373 1.18 1.227 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.906.108-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.533c-.644-.16-1.984-.427-3.915-.427s-3.272.267-3.916.427a.52.52 0 0 0-.429.533v.853c0 .32-.107.64-.375.853l-.161.16c-.215.16-.322.48-.322.747c.054.587.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.072-2.08l.43-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.054 2.36.533l.805.8c.214.267.482.427.804.587");
}

.p63xbfaao {
  stop-color: var(--svg-color--85527f, #85527F);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psls5zbwz {
  stop-color: var(--svg-color--625570, #625570);
  stop-opacity: 0;
}

.ptuohkesm {
  stop-color: var(--svg-color--cd2172, #CD2172);
  stop-opacity: 0;
}

.q2xn-obga {
  d: path("M6.984 15.9c0 .222.249.316.555.316s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.q50ar7-tx {
  d: path("M10.866 8.62c0-.267.107-.587.322-.747l.16-.16c.269-.213.376-.533.376-.853v-.853a.52.52 0 0 1 .43-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.271.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.108 1.44-.108 1.44h.018l-.265 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.713 0-3.05-1.234-3.21-3.003c-.14-1.816-.201-3.638-.367-5.451");
}

.qaycvn_cp {
  stop-color: var(--svg-color--67416e, #67416E);
}

.qf-zh-bgi {
  stop-color: var(--svg-color--755da2, #755DA2);
  stop-opacity: 0;
}

.qki2lm4wo {
  cx: 11.276px;
  cy: 10.671px;
  r: 0.995px;
}

.ql_s_gb7e {
  d: path("M30.01 29.93h-3.532l-4.25-8.75l3.648-4.399C29.29 21.22 30.01 27.164 30.01 29.93");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qsjdql87s {
  stop-color: var(--svg-color--ae495e, #AE495E);
}

.qt64ghhxa {
  cx: 16.554px;
  cy: 23.452px;
  rx: 0.552px;
  ry: 0.695px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.qzls3vb2f {
  d: path("M7.987 16.895c0 .21.237.3.529.3s.53-.113.53-.3a.53.53 0 0 0-1.06 0");
}

.sb_6z1bpd {
  stop-color: var(--svg-color--761032, #761032);
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.slx6fqref {
  stop-color: var(--svg-color--e1658e, #E1658E);
  stop-opacity: 0;
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.swwyfhppg {
  cx: 20.789px;
  cy: 10.671px;
  r: 0.995px;
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.tdxsvibvu {
  d: path("M18.165 9.597c.064.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.16-.359c.15-.113.325-.135.388-.05");
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tyoz-v6go {
  stop-color: var(--svg-color--cd2172, #CD2172);
}

.u05m0u9vr {
  stop-color: var(--svg-color--ae495e, #AE495E);
  stop-opacity: 0;
}

.uc4vypayb {
  stop-color: var(--svg-color--8371ae, #8371AE);
}

.uehfnrv2s {
  d: path("M24.115 16.902c0 .211-.237.301-.53.301c-.291 0-.529-.113-.529-.3a.53.53 0 0 1 1.06 0");
}

.uhjz0cbil {
  stop-color: var(--svg-color--e62f68, #E62F68);
  stop-opacity: 0;
}

.ujur1qtze {
  stop-color: var(--svg-color--db2a69, #DB2A69);
}

.ungg6q-mb {
  stop-color: var(--svg-color--e7547f, #E7547F);
}

.uq-m7pb0g {
  stop-color: var(--svg-color--573a88, #573A88);
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v_v98qact {
  stop-color: var(--svg-color--230f39, #230F39);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.vat9yt_ey {
  stop-color: var(--svg-color--614290, #614290);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vid03obgg {
  cx: 11.276px;
  cy: 10.671px;
  r: 1.669px;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vqnicvviz {
  stop-color: var(--svg-color--7a5f4b, #7A5F4B);
}

.vxg30mb5o {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.748 10.549l-.82 1.7c-.102.349.142.698.488.698h.737c.346 0 .59-.355.488-.699l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.wp9t5rg1b {
  fill: var(--svg-color--6a4440, #6A4440);
  d: path("m9.897 8.146l3.235 4.806a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.153c.08-.24.253-.576.388-.576c.154 0 .313.337.393.576a.4.4 0 0 0 .085.153l1.45 1.655a.617.617 0 0 0 .975-.06l3.235-4.806c.174-.258-.057-.559-.354-.466l-4.821 1.51a.5.5 0 0 0-.278.25c-.178.342-.476-.255-.685-.25c-.21-.005-.503.592-.68.25a.5.5 0 0 0-.278-.25L10.25 7.68c-.298-.093-.529.208-.354.466");
}

.x7un6yb_h {
  d: path("M18.23 9.408a.893.893 0 0 1 .861 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xcrsoe6-m {
  stop-color: var(--svg-color--7a5f4b, #7A5F4B);
  stop-opacity: 0;
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xkd2ooi4v {
  stop-color: var(--svg-color--322f37, #322F37);
  stop-opacity: 0;
}

.xnqc2smdc {
  cx: 13.59px;
  cy: 9.79px;
  rx: 0.39px;
  ry: 0.197px;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xrr4vbcci {
  stop-color: var(--svg-color--7560a8, #7560A8);
  stop-opacity: 0;
}

.xshejgbiq {
  d: path("M23.083 15.909c0 .22-.249.315-.556.315c-.306 0-.555-.119-.555-.315a.555.555 0 1 1 1.11 0");
}

.y-so25ixd {
  stop-color: var(--svg-color--50387f, #50387F);
}

.y06th9bdt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
  stop-opacity: 0;
}

.ydi8a_bcj {
  stop-color: var(--svg-color--5e5158, #5E5158);
  stop-opacity: 0;
}

.ygkfonyaf {
  d: path("m8.576 6.816l3.932 5.84a.75.75 0 0 0 1.185.074l1.761-2.012a.5.5 0 0 0 .104-.185c.098-.291.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.185l1.761 2.012a.75.75 0 0 0 1.185-.073l3.932-5.84c.212-.314-.069-.68-.43-.567L17.2 8.085a.6.6 0 0 0-.338.305c-.216.414-.578.624-.833.63c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.305L9.006 6.25c-.361-.113-.642.253-.43.566");
}

.yhvjw36xj {
  stop-color: var(--svg-color--563079, #563079);
}

.yjzk6_bwe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.491 5.86v.897c-.008.15-.07.481-.258.622");
}

.yog48s40z {
  stop-color: var(--svg-color--ff5292, #FF5292);
}

.yr3p0jbaj {
  stop-color: var(--svg-color--5d3970, #5D3970);
  stop-opacity: 0;
}

.yrqfnf2oy {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.438 9.136c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zblf_actk {
  stop-color: var(--svg-color--372543, #372543);
}

.zhe9zhdzx {
  stop-color: var(--svg-color--7a4c9c, #7A4C9C);
}

.zo3xzub3m {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.9c0 .222.248.316.555.316c.306 0 .555-.119.555-.315a.555.555 0 0 0-1.11 0");
}

.zojxemb8i {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
  stop-opacity: 0;
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

.zxe--8tbm {
  stop-color: var(--svg-color--50387f, #50387F);
  stop-opacity: 0;
}

</style>
