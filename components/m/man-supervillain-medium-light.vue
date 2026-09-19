<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibcm99G)"><path fill="url(#iinPw8D)" class="cwwuu-zus"/><path fill="url(#iaBBtbd)" class="cwwuu-zus"/></g><g filter="url(#i0aFard)"><path fill="url(#iiEqr2b)" class="ql_s_gb7e"/><path fill="url(#ioUcBAb)" class="ql_s_gb7e"/></g><path fill="url(#iBiQeDA)" class="okhuii28v"/><path fill="url(#izpz5ze)" class="okhuii28v"/><path fill="url(#iKePr8Z)" class="okhuii28v"/><path fill="url(#insqWwt)" class="okhuii28v"/><path fill="url(#ivSi3bb)" class="okhuii28v"/><path fill="url(#ircrQDd)" class="okhuii28v"/><path fill="url(#ifryBne)" class="okhuii28v"/><path fill="url(#ikIiN1c)" class="okhuii28v"/><path fill="url(#iOuvhDb)" class="yeod45b3y"/><path fill="url(#iBvVYyd)" class="yeod45b3y"/><path fill="url(#ihP5YId)" class="yeod45b3y"/><path fill="url(#iMs4HDc)" class="yeod45b3y"/><path fill="url(#iuiz98k)" class="b8g9wj85t"/><path fill="url(#i9sXN2b)" class="b8g9wj85t"/><path fill="url(#i4RB5Kb)" class="b8g9wj85t"/><path fill="url(#i2tM7DX)" class="b8g9wj85t"/><path fill="url(#iHtsFid)" class="enuodcxjx"/><path fill="url(#i6bBXnb)" class="xshejgbiq"/><path fill="url(#i4yYkKm)" class="ffppavbjz"/><g filter="url(#iYFf4vc)"><path fill="url(#i6Mny8c)" class="rbw28e91g"/><path fill="url(#ikEiTHe)" class="rbw28e91g"/><path fill="url(#imd9wXd)" class="rbw28e91g"/><path fill="url(#iFyR8He)" class="rbw28e91g"/><path fill="url(#iKtwjae)" class="rbw28e91g"/></g><path class="zo3xzub3m"/><path fill="url(#iNkC37b)" class="cs3_qu-mq"/><path fill="url(#iPmcduc)" class="cs3_qu-mq"/><path class="ayordobqc"/><path fill="url(#iyRy83b)" class="q2xn-obga"/><g filter="url(#ispEA4L)"><path fill="url(#imeN56b)" class="m0vavhoqr"/><path fill="url(#iPBza4d)" class="m0vavhoqr"/><path fill="url(#imbb6gd)" class="m0vavhoqr"/><path fill="url(#iARVvgc)" class="m0vavhoqr"/><path fill="url(#iaiWMGd)" class="m0vavhoqr"/><path fill="url(#ixRS5jk)" class="m0vavhoqr"/></g><g filter="url(#i3HeDmc)"><path fill="url(#iibhYfc)" class="q2nu1kw1c"/></g><path fill="url(#iHKY1Dd)" class="f-34xcbsr"/><path fill="url(#idNKkhd)" class="f-34xcbsr"/><path fill="url(#ibrytKP)" class="zti9x05ov"/><path fill="url(#i2nPSae)" class="frrfa_xnp"/><path fill="url(#i7cIkAd)" class="frrfa_xnp"/><path fill="url(#iXTbrde)" class="ksm2e4q4f"/><path fill="url(#i6yAJSZ)" class="ksm2e4q4f"/><g filter="url(#ivuZRHc)"><circle fill="url(#iAXPard)" class="rlk2u7-bv"/><circle fill="url(#ihtMJRc)" class="rlk2u7-bv"/></g><ellipse fill="url(#iYq9qZb)" transform="rotate(-31.445 16.554 23.452)" class="qt64ghhxa"/><g filter="url(#iDpfrne)"><circle fill="url(#i5HcTAC)" class="rj24mkbpb"/></g><g filter="url(#i57DRhs)"><circle fill="url(#ixaI9Td)" class="u-8ja_bsp"/></g><g filter="url(#iGzZclc)"><circle fill="url(#iwgGMqi)" class="rv0ek2bxr"/><circle fill="url(#iQhImre)" class="rv0ek2bxr"/></g><g filter="url(#i20gr6a)"><circle class="r77uiubpn"/><circle fill="url(#iheimBc)" class="l_ux29bmr"/><circle fill="url(#i9Ibjcc)" class="l_ux29bmr"/></g><g filter="url(#idrUt8d)"><path fill="url(#iZps0ue)" class="gfr543eqx"/><path fill="url(#irXgZMd)" class="gfr543eqx"/><path fill="url(#iNrh1eg)" class="gfr543eqx"/><path fill="url(#infrgPc)" class="gfr543eqx"/><path fill="url(#izrgV7d)" class="gfr543eqx"/><path fill="url(#i09vWKd)" class="gfr543eqx"/></g><g filter="url(#i6SaRdd)"><path class="atv0vxbqr"/><path fill="url(#iKQLrJk)" class="t708mfdzi"/><path fill="url(#ir12nRe)" class="t708mfdzi"/><path fill="url(#inLusuc)" class="t708mfdzi"/><path fill="url(#iA6pHuc)" class="t708mfdzi"/><path fill="url(#i8y2XBd)" class="t708mfdzi"/></g><path fill="url(#ifui5nb)" class="t708mfdzi"/><path fill="url(#iKa2HHd)" class="t708mfdzi"/><g filter="url(#iIG7IId)"><path class="rvdc7_btv"/></g><g filter="url(#iIe7oTb)"><path class="l2rlpbc4o"/><path fill="url(#iOQ7nOd)" class="sm3vg3bhe"/><path fill="url(#insn6sc)" class="sm3vg3bhe"/><path fill="url(#iARTP9b)" class="sm3vg3bhe"/></g><path class="yrqfnf2oy"/><path fill="url(#iuJNh4B)" class="d8fmmnoud"/><path class="k561k8ppe"/><g filter="url(#iWQkw3d)"><path class="q6tdpc27r"/><path fill="url(#iBQYNib)" class="bi_zkmxzr"/></g><g filter="url(#iznzBXb)"><path fill="url(#ixtN8xd)" class="i9uiobbul"/></g><path class="oh3-d7lzf"/><path fill="url(#i3OTepe)" class="gveelkgks"/><path class="o646v6buz"/><g filter="url(#igdeECe)"><path fill="url(#izq1vvd)" class="fd4z9cb9c"/></g><g filter="url(#iw63Ggd)"><ellipse transform="rotate(-27.914 13.59 9.79)" class="g9_sxsbrd"/><ellipse fill="url(#iLImnyc)" transform="rotate(-27.914 13.59 9.79)" class="xnqc2smdc"/></g><g filter="url(#ifMNfAZ)"><path class="ob7cplbpf"/></g><g filter="url(#iYqAwwc)"><path fill="url(#iWBVdAc)" class="ygkfonyaf"/><path fill="url(#inhZTwb)" class="ygkfonyaf"/><path fill="url(#icnKn3b)" class="ygkfonyaf"/></g><path fill="url(#iAJt6SQ)" class="ygkfonyaf"/><g filter="url(#ixb7Dge)"><path class="c0eecvb8p"/></g><g filter="url(#iT3xf6c)"><path class="hmuq4s6pt"/></g><path class="ca0fkqb1x"/><defs><radialGradient id="iinPw8D" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.293 12.621)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iaBBtbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.586)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iiEqr2b" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.24 4.191)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="ioUcBAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.118 24.587)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iBiQeDA" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.898)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="izpz5ze" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.415 15.195)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="iKePr8Z" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.736)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="ivSi3bb" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.338 17.837)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="ircrQDd" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.21)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="ifryBne" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.586)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iOuvhDb" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.432 25.367)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="iBvVYyd" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.252 20.211)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="ihP5YId" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.648)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="iuiz98k" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.055)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="i9sXN2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.117)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="i4RB5Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.805)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="i2tM7DX" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.398)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="iHtsFid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.069 21.148)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="i6bBXnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.789)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="i4yYkKm" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.789)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="ikEiTHe" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.74 58.912)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="imd9wXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.545)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="iFyR8He" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.12 15.867)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="iKtwjae" cx="0" cy="0" r="1" gradientTransform="matrix(3.52963 0 0 2.27341 18.523 16.31)" gradientUnits="userSpaceOnUse"><stop class="ge69a97wz"/><stop offset="1" class="jd18rptxw"/></radialGradient><radialGradient id="iNkC37b" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.523)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="iPmcduc" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.781)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="iyRy83b" cx="0" cy="0" r="1" gradientTransform="matrix(.66797 .16406 -.20923 .85186 6.846 15.64)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="imbb6gd" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.359 16.43)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iARVvgc" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 12 7.393)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="iaiWMGd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.31239 0 0 -2.83509 14.65 16.242)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="sb_6z1bpd"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="ixRS5jk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.862)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="iibhYfc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.3667 .90626 -1.59163 -5.9128 17.338 16.805)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="odam8hbyg"/><stop offset="1" class="du8_b9dvn"/></radialGradient><radialGradient id="iHKY1Dd" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.53 11.507)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="idNKkhd" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.776 16.914)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="ibrytKP" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.664)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="i2nPSae" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.793 20.913)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="i7cIkAd" cx="0" cy="0" r="1" gradientTransform="rotate(-29.297 36.7 -7.127)scale(.99044 .92102)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="iXTbrde" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.182 16.633)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="i6yAJSZ" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.52344 .50555 .83423 10.26 17.102)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="iAXPard" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.103 16.937)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="ihtMJRc" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.43)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="i5HcTAC" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 9.672 10.67)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iQhImre" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.226 10.406)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iheimBc" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.813 11.492)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="i9Ibjcc" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 20.855 10.671)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="irXgZMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.6693 -10.1935 0 16.56 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="j31ej4b2t"/><stop offset=".937" class="cm_yz06fm"/></radialGradient><radialGradient id="infrgPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 18.435 9.4)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="izrgV7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.878 9.366)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="i09vWKd" cx="0" cy="0" r="1" gradientTransform="rotate(-128.577 9.313 .95)scale(4.30904 1.19555)" gradientUnits="userSpaceOnUse"><stop class="vl6c6-35a"/><stop offset="1" class="f9bc6128v"/></radialGradient><radialGradient id="iKQLrJk" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.166 6.324)scale(5.6057 9.53299)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="inLusuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.06682 -1.86131 .91413 -.03282 11.896 7.217)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iA6pHuc" cx="0" cy="0" r="1" gradientTransform="matrix(.85907 -1.96631 1.60368 .70064 20.316 8.934)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="i8y2XBd" cx="0" cy="0" r="1" gradientTransform="matrix(.9927 1.23176 -1.08755 .87648 15.314 2.07)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="ifui5nb" cx="0" cy="0" r="1" gradientTransform="matrix(.18136 .78313 -1.28748 .29815 16.784 2.07)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iKa2HHd" cx="0" cy="0" r="1" gradientTransform="matrix(.72544 .89725 -2.0104 1.62544 11.744 3.798)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="iuJNh4B" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.229 9.885)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iBQYNib" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3OTepe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.862 9.885)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iLImnyc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.761 -1.63)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWBVdAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.229)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="c7yfkfb_x"/><stop offset=".878" class="ly-mhyl9x"/></radialGradient><radialGradient id="inhZTwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 12.986)" gradientUnits="userSpaceOnUse"><stop class="cycj4pb5c"/><stop offset="1" class="xkd2ooi4v"/></radialGradient><radialGradient id="icnKn3b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25001 4.51317 -4.6352 -5.39197 23.432 6.229)" gradientUnits="userSpaceOnUse"><stop class="mbbg-bcay"/><stop offset="1" class="psls5zbwz"/><stop offset="1" class="vyoyvyblw"/></radialGradient><filter id="ibcm99G" width="7.981" height="13.148" x="1.991" y="16.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/></filter><filter id="i0aFard" width="7.981" height="13.148" x="22.028" y="16.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/></filter><filter id="iYFf4vc" width="9.078" height="5.683" x="17.916" y="15.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/></filter><filter id="ispEA4L" width="8.928" height="5.533" x="5.258" y="15.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/></filter><filter id="i3HeDmc" width="4.194" height="5.942" x="13.971" y="12.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/></filter><filter id="ivuZRHc" width="3.465" height="3.465" x="14.33" y="22.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/></filter><filter id="iDpfrne" width="3.539" height="3.339" x="9.672" y="9.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/></filter><filter id="i57DRhs" width="2.99" height="2.99" x="9.847" y="9.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1009" stdDeviation=".25"/></filter><filter id="iGzZclc" width="3.589" height="3.589" x="19.185" y="8.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/></filter><filter id="i20gr6a" width="2.99" height="2.99" x="19.36" y="9.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1009" stdDeviation=".25"/></filter><filter id="idrUt8d" width="10.373" height="12.177" x="10.932" y="5.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/></filter><filter id="i6SaRdd" width="12.601" height="8.543" x="9.789" y="1.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/></filter><filter id="iIG7IId" width="3.26" height="4.181" x="14.22" y="9.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1009" stdDeviation=".375"/></filter><filter id="iIe7oTb" width="2.377" height="3.181" x="14.901" y="9.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1009" stdDeviation=".125"/></filter><filter id="iWQkw3d" width=".787" height=".697" x="17.494" y="9.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1009" stdDeviation=".05"/></filter><filter id="iznzBXb" width=".892" height=".914" x="18.335" y="9.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1009" stdDeviation=".1"/></filter><filter id="igdeECe" width=".987" height="1.041" x="13.889" y="9.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1009" stdDeviation=".1"/></filter><filter id="iw63Ggd" width=".914" height=".705" x="13.133" y="9.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1009" stdDeviation=".05"/></filter><filter id="ifMNfAZ" width="13.891" height="7.06" x="9.087" y="6.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1009" stdDeviation=".375"/></filter><filter id="iYqAwwc" width="15.159" height="7.107" x="8.403" y="6.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.152941 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.333333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1009" result="effect2_innerShadow_4002_1009"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.215686 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1009" result="effect3_innerShadow_4002_1009"/></filter><filter id="ixb7Dge" width="2.192" height="1.627" x="17.223" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1009" result="effect2_innerShadow_4002_1009"/></filter><filter id="iT3xf6c" width="2.192" height="1.627" x="12.726" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1009"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1009" result="effect2_innerShadow_4002_1009"/></filter><linearGradient id="insqWwt" x1="23.236" x2="22.979" y1="29.93" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="ikIiN1c" x1="8.858" x2="8.994" y1="29.93" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="iMs4HDc" x1="23.252" x2="23.486" y1="29.93" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="i6Mny8c" x1="25.746" x2="20.292" y1="15.867" y2="20.079" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="imeN56b" x1="9.772" x2="9.772" y1="15.862" y2="20.648" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="iPBza4d" x1="9.772" x2="9.772" y1="15.492" y2="17.461" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="iYq9qZb" x1="16.985" x2="15.947" y1="23.067" y2="23.971" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="ixaI9Td" x1="11.342" x2="10.701" y1="10.95" y2="10.95" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iwgGMqi" x1="21.941" x2="21.122" y1="9.579" y2="12.116" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iZps0ue" x1="20.125" x2="12.489" y1="11.06" y2="12.198" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iNrh1eg" x1="10.694" x2="13.006" y1="13.756" y2="13.454" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="ir12nRe" x1="11.229" x2="14.13" y1="10.404" y2="5.249" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iOQ7nOd" x1="15.225" x2="16.163" y1="11.72" y2="11.72" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="insn6sc" x1="17.028" x2="16.002" y1="12.042" y2="12.027" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iARTP9b" x1="16.284" x2="16.284" y1="12.784" y2="12.211" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="ixtN8xd" x1="19.007" x2="18.693" y1="9.939" y2="10.133" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izq1vvd" x1="14.606" x2="14.292" y1="9.939" y2="10.133" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAJt6SQ" x1="10.733" x2="10.979" y1="10.059" y2="9.898" gradientUnits="userSpaceOnUse"><stop offset=".102" class="a5a8_w8qp"/><stop offset=".478" class="ydi8a_bcj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-supervillain-medium-light" /></template>
<style>
.a--e2mwlv {
  stop-color: var(--svg-color--614b90, #614B90);
}

.a-lmuhb3j {
  stop-color: var(--svg-color--7560a8, #7560A8);
}

.a5a8_w8qp {
  stop-color: var(--svg-color--5e5158, #5E5158);
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.atv0vxbqr {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m20.908 4.194l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.267-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.429-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.587");
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

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bfw_o9sgk {
  stop-color: var(--svg-color--8977bc, #8977BC);
  stop-opacity: 0;
}

.bi_zkmxzr {
  d: path("M18.165 9.597c.064.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.16-.359c.15-.113.325-.135.388-.05");
}

.bkplcs5-b {
  stop-color: var(--svg-color--615181, #615181);
  stop-opacity: 0;
}

.bozoj1btu {
  stop-color: var(--svg-color--e7547f, #E7547F);
  stop-opacity: 0;
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

.ca0fkqb1x {
  fill: var(--svg-color--930257, #930257);
  d: path("M17.75 12.592c-.614.807-1.368.893-1.872.925c-.085.005-.12.104-.051.154c.377.269.857.292 1.342.09c.51-.213.733-.703.747-1.123c.003-.092-.11-.119-.165-.046");
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

.cm_yz06fm {
  stop-color: var(--svg-color--b9686b, #B9686B);
}

.cs3_qu-mq {
  d: path("M9.02 15.9c0 .222.248.316.555.316c.306 0 .555-.119.555-.315a.555.555 0 0 0-1.11 0");
}

.ctoai6naw {
  stop-color: var(--svg-color--f93362, #F93362);
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

.d-jm4nrou {
  stop-color: var(--svg-color--7757b7, #7757B7);
  stop-opacity: 0;
}

.d8fmmnoud {
  d: path("M18.231 9.408a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.dkr4vta7s {
  stop-color: var(--svg-color--8977bc, #8977BC);
}

.do8d1irdg {
  stop-color: var(--svg-color--e1658e, #E1658E);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
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

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f-34xcbsr {
  d: path("M22.037 16.902c0 .293-.237.367-.53.367c-.291 0-.528-.074-.528-.367a.53.53 0 0 1 1.058 0");
}

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f9bc6128v {
  stop-color: var(--svg-color--daa288, #DAA288);
  stop-opacity: 0;
}

.f9nu08mzt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
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

.frrfa_xnp {
  d: path("M7.987 16.895c0 .21.237.3.53.3c.292 0 .529-.113.529-.3a.53.53 0 0 0-1.06 0");
}

.ft5dv1b6b {
  fill: none;
}

.fypjwijgc {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
}

.g2wrz_okq {
  stop-color: var(--svg-color--bb4566, #BB4566);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
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

.gfr543eqx {
  d: path("m10.99 10.058l.049.002s-.054-.853-.107-1.44c0-.267.107-.587.322-.747l.16-.16c.269-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.533c.644-.16 1.985-.427 3.915-.427c1.931 0 3.272.267 3.916.427c.214.053.429.266.429.533v.853c0 .32.16.64.375.853c.502.352.471.546.43.96c-.054.534-.108 1.44-.108 1.44h.018l-.266 3.958c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.234-3.21-3.003z");
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gveelkgks {
  d: path("M13.86 9.408a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.hmuq4s6pt {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m13.077 8.723l1.607.592c.154.057.236.23.147.368c-.22.342-.656.692-1.345.489c-.65-.192-.792-.814-.755-1.257c.014-.167.188-.25.346-.192");
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.i3hug6b7s {
  stop-color: var(--svg-color--655586, #655586);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
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

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.j31ej4b2t {
  stop-color: var(--svg-color--d19889, #D19889);
  stop-opacity: 0;
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jd18rptxw {
  stop-color: var(--svg-color--d31c55, #D31C55);
  stop-opacity: 0;
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
}

.k561k8ppe {
  fill: var(--svg-color--000, #000);
  d: path("M17.72 10.301a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .456.747h-.906a.46.46 0 0 1-.06-.236");
}

.kejp2n55e {
  stop-color: var(--svg-color--79659c, #79659C);
}

.klsvjl5ds {
  stop-color: var(--svg-color--7056ae, #7056AE);
}

.kr4wgsbgo {
  stop-color: var(--svg-color--533179, #533179);
}

.ksm2e4q4f {
  d: path("M10.065 16.895c0 .292.237.367.53.367c.292 0 .529-.075.529-.367a.53.53 0 0 0-1.059 0");
}

.ksp1sznci {
  stop-color: var(--svg-color--6d55a5, #6D55A5);
  stop-opacity: 0;
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l_ux29bmr {
  cx: 20.854px;
  cy: 10.671px;
  r: 0.995px;
}

.l1led_brw {
  stop-color: var(--svg-color--df1d5a, #DF1D5A);
}

.l2rlpbc4o {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.707 10.386l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.ly-mhyl9x {
  stop-color: var(--svg-color--4a474e, #4A474E);
}

.m0vavhoqr {
  d: path("M7.467 19.858c.75 1.082 1.856 1.976 4.008 1.05c1.836-.789 2.711-3.268 2.711-5.046l-8.203.023c-.652 0-.751.442-.492.856c.646 1.03 1.52 2.405 1.976 3.117");
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

.mxm28cb7d {
  stop-color: var(--svg-color--735784, #735784);
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

.o646v6buz {
  fill: var(--svg-color--000, #000);
  d: path("M14.371 10.301a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.236");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.ob7cplbpf {
  fill: var(--svg-color--ad7455, #AD7455);
  d: path("m9.897 8.146l3.235 4.806a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.152c.08-.24.253-.577.388-.577c.154 0 .313.337.393.576a.4.4 0 0 0 .085.153l1.45 1.655a.617.617 0 0 0 .975-.06l3.235-4.806c.174-.258-.057-.559-.354-.466l-4.821 1.51a.5.5 0 0 0-.278.25c-.178.342-.476-.255-.685-.25c-.21-.005-.503.592-.68.25a.5.5 0 0 0-.278-.25L10.25 7.68c-.298-.093-.529.208-.354.466");
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

.okhuii28v {
  d: path("M4.588 29.93h22.938c-.206-3.07-.606-5.613-1.406-7.564c-2.445-5.955-7.16-6.953-10.063-6.811c-2.904-.142-7.618.856-10.063 6.811c-.8 1.95-1.2 4.494-1.406 7.564");
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
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

.q2nu1kw1c {
  d: path("M13.971 15.02a2.097 2.097 0 0 1 4.195 0v1.547c0 1.37-.94 2.097-2.097 2.097c-1.159 0-2.098-.695-2.098-2.097z");
}

.q2xn-obga {
  d: path("M6.984 15.9c0 .222.249.316.555.316s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.q6tdpc27r {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.165 9.597c.064.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.16-.359c.15-.113.325-.135.388-.05");
}

.qaycvn_cp {
  stop-color: var(--svg-color--67416e, #67416E);
}

.qf-zh-bgi {
  stop-color: var(--svg-color--755da2, #755DA2);
  stop-opacity: 0;
}

.ql_s_gb7e {
  d: path("M30.01 29.93h-3.532l-4.25-8.75l3.648-4.399C29.29 21.22 30.01 27.164 30.01 29.93");
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

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r77uiubpn {
  cx: 20.854px;
  cy: 10.671px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.rbw28e91g {
  d: path("M24.635 19.863c-.75 1.082-1.855 1.976-4.008 1.051c-1.836-.789-2.71-3.269-2.71-5.047l8.202.024c.653 0 .752.441.492.855a376 376 0 0 1-1.976 3.117");
}

.rj24mkbpb {
  cx: 11.342px;
  cy: 10.671px;
  r: 1.669px;
}

.rlk2u7-bv {
  cx: 16.063px;
  cy: 23.939px;
  r: 1.732px;
}

.rv0ek2bxr {
  cx: 20.854px;
  cy: 10.671px;
  r: 1.669px;
}

.rvdc7_btv {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.814 10.549l-.82 1.7c-.102.349.142.698.488.698h.737c.345 0 .59-.355.488-.699l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.sb_6z1bpd {
  stop-color: var(--svg-color--761032, #761032);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.slx6fqref {
  stop-color: var(--svg-color--e1658e, #E1658E);
  stop-opacity: 0;
}

.sm3vg3bhe {
  d: path("m15.707 10.386l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.t708mfdzi {
  d: path("m20.908 4.194l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.267-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.429-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.587");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tyoz-v6go {
  stop-color: var(--svg-color--cd2172, #CD2172);
}

.u-8ja_bsp {
  cx: 11.342px;
  cy: 10.671px;
  r: 0.995px;
}

.u05m0u9vr {
  stop-color: var(--svg-color--ae495e, #AE495E);
  stop-opacity: 0;
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.uc4vypayb {
  stop-color: var(--svg-color--8371ae, #8371AE);
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

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v_v98qact {
  stop-color: var(--svg-color--230f39, #230F39);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.vat9yt_ey {
  stop-color: var(--svg-color--614290, #614290);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vl6c6-35a {
  stop-color: var(--svg-color--b58360, #B58360);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
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

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
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

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ydi8a_bcj {
  stop-color: var(--svg-color--5e5158, #5E5158);
  stop-opacity: 0;
}

.yeod45b3y {
  d: path("M23.252 18.087V29.93h4.274c-.206-3.07-.606-5.613-1.406-7.564c-.773-1.88-1.771-3.267-2.868-4.28");
}

.ygkfonyaf {
  d: path("m8.576 6.816l3.932 5.84a.75.75 0 0 0 1.185.074l1.761-2.012a.5.5 0 0 0 .104-.185c.098-.291.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.185l1.761 2.012a.75.75 0 0 0 1.185-.073l3.932-5.84c.212-.314-.069-.68-.43-.567L17.2 8.085a.6.6 0 0 0-.338.305c-.216.414-.578.624-.833.63c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.305L9.006 6.25c-.361-.113-.642.253-.43.566");
}

.yhvjw36xj {
  stop-color: var(--svg-color--563079, #563079);
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

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.zblf_actk {
  stop-color: var(--svg-color--372543, #372543);
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zhe9zhdzx {
  stop-color: var(--svg-color--7a4c9c, #7A4C9C);
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zo3xzub3m {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.9c0 .222.248.316.555.316c.306 0 .555-.119.555-.315a.555.555 0 0 0-1.11 0");
}

.zojxemb8i {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
  stop-opacity: 0;
}

.zti9x05ov {
  d: path("M24.115 16.902c0 .211-.237.301-.529.301s-.53-.113-.53-.3a.53.53 0 1 1 1.06 0");
}

.zxe--8tbm {
  stop-color: var(--svg-color--50387f, #50387F);
  stop-opacity: 0;
}

</style>
