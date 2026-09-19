<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#izasRwb)"><path fill="url(#iFqpuyc)" class="y82w82gtu"/><path fill="url(#iXqA5zb)" class="y82w82gtu"/></g><g filter="url(#iBam3db)"><path fill="url(#iuxoJ3d)" class="b__guxb5q"/><path fill="url(#i1y9B7l)" class="b__guxb5q"/></g><path fill="url(#i4TBK6b)" class="bfsmm5jux"/><path fill="url(#iovfRsd)" class="bfsmm5jux"/><path fill="url(#iS9ZDiI)" class="bfsmm5jux"/><path fill="url(#io3hbsd)" class="bfsmm5jux"/><path fill="url(#iCVqgAe)" class="bfsmm5jux"/><path fill="url(#iwb90Fe)" class="bfsmm5jux"/><path fill="url(#iYlbYMc)" class="bfsmm5jux"/><path fill="url(#ihRz4Fc)" class="bfsmm5jux"/><path fill="url(#iX5Gmzd)" class="q-vyvnloj"/><path fill="url(#ielLZkb)" class="q-vyvnloj"/><path fill="url(#iE2SYiX)" class="q-vyvnloj"/><path fill="url(#iS32ave)" class="q-vyvnloj"/><path fill="url(#iLCWise)" class="x3ac2p_-t"/><path fill="url(#iGm40Le)" class="x3ac2p_-t"/><path fill="url(#ibWfH0n)" class="x3ac2p_-t"/><path fill="url(#ibeowCc)" class="x3ac2p_-t"/><path fill="url(#iHmM1Fe)" class="mx-85jb1t"/><path fill="url(#iTXLUYj)" class="rqy_z7taf"/><path fill="url(#iBbC8ab)" class="l2c0efs8e"/><g filter="url(#iwURpJb)"><path fill="url(#iPO6Nic)" class="vv3mrckep"/><path fill="url(#iVMncze)" class="vv3mrckep"/><path fill="url(#ivUDyye)" class="vv3mrckep"/><path fill="url(#ilNBzdF)" class="vv3mrckep"/><path fill="url(#i0CwCve)" class="vv3mrckep"/></g><path class="pbx1a_0-e"/><path fill="url(#inyLdJb)" class="dbez5ccgk"/><path fill="url(#imDWS3c)" class="dbez5ccgk"/><path class="r5lwd_9jp"/><path fill="url(#is5rbYb)" class="uvjko3k9x"/><g filter="url(#icnAZlc)"><path fill="url(#iQmlBWX)" class="z9cekbb2i"/><path fill="url(#irZlZhb)" class="z9cekbb2i"/><path fill="url(#iVaCY7b)" class="z9cekbb2i"/><path fill="url(#iqDO8xd)" class="z9cekbb2i"/><path fill="url(#iPKI3md)" class="z9cekbb2i"/><path fill="url(#iCSSE4c)" class="z9cekbb2i"/></g><g filter="url(#i4UX69c)"><path fill="url(#i4xyObx)" class="wggtpctur"/></g><path fill="url(#iZEwBGb)" class="fw4d8ibbd"/><path fill="url(#ibHJk7b)" class="fw4d8ibbd"/><path fill="url(#iTblmxe)" class="f2s2fz6db"/><path fill="url(#ieKcP5d)" class="j5d124bow"/><path fill="url(#iIvcxxb)" class="j5d124bow"/><path fill="url(#i0HK7fc)" class="uxt_ehm2r"/><path fill="url(#iJx5USM)" class="uxt_ehm2r"/><g filter="url(#irMvtze)"><circle fill="url(#ivk5jac)" class="hl0sk802z"/><circle fill="url(#imJF0Zc)" class="hl0sk802z"/></g><ellipse fill="url(#iJQkzcm)" transform="rotate(-31.445 16.554 23.508)" class="d9pt9np5n"/><g filter="url(#iTvLWae)"><circle fill="url(#iXm651d)" class="spz-82b7z"/></g><g filter="url(#iDml0ve)"><circle fill="url(#ifMSjEe)" class="lo3a_acnh"/></g><g filter="url(#iN7qb0c)"><circle fill="url(#iNCmDKc)" class="xkk8eybzc"/><circle fill="url(#iTeTORc)" class="xkk8eybzc"/></g><g filter="url(#iwUICfb)"><circle class="g-sinpvdo"/><circle fill="url(#ibjc9wd)" class="terk_xbor"/><circle fill="url(#iZjhfec)" class="terk_xbor"/></g><g filter="url(#iGIkhTt)"><path fill="url(#i3zQ2Cb)" class="hcn9qvb5t"/><path fill="url(#idDcSce)" class="hcn9qvb5t"/><path fill="url(#iiFINCb)" class="hcn9qvb5t"/></g><path fill="url(#i95yG3c)" class="p6d2azb8i"/><path fill="url(#ia7yoZK)" class="p6d2azb8i"/><path fill="url(#iqSpmke)" class="p6d2azb8i"/><path fill="url(#ilQr1He)" class="p6d2azb8i"/><g filter="url(#iL0RYJb)"><path fill="url(#iNQi2ac)" class="gsgtixbyq"/></g><g filter="url(#imR30Md)"><path class="bp5vj9b3z"/><path fill="url(#ibhatvb)" class="ux10xmbuk"/><path fill="url(#i9AZE3g)" class="ux10xmbuk"/><path fill="url(#iYudbmc)" class="ux10xmbuk"/><path fill="url(#i69Cunc)" class="ux10xmbuk"/></g><g filter="url(#ivKH3Yb)"><path class="p6-aag9fy"/></g><g filter="url(#iUUPcnd)"><path class="rze2kbbww"/><path fill="url(#iEYA55d)" class="jywmtub7y"/><path fill="url(#iLEzWFd)" class="jywmtub7y"/><path fill="url(#iIXUpUO)" class="jywmtub7y"/><path fill="url(#i9iVIww)" class="jywmtub7y"/></g><path class="k0tipmbrg"/><path fill="url(#iwcSOgb)" class="j05qr1bdn"/><path class="oepmfgb3z"/><g filter="url(#i7qTh1c)"><path class="l6lsh3b7c"/><path fill="url(#i8EkMbe)" class="pq3p2ab2a"/></g><g filter="url(#i9urkRb)"><path fill="url(#iwav3ge)" class="y6ukhtacc"/></g><path class="yey76mb1n"/><path fill="url(#iGeik3d)" class="o2io-ujbo"/><path class="t-qfzd5dc"/><g filter="url(#iQBJWrb)"><path fill="url(#igQreob)" class="mwufvlb3p"/></g><g filter="url(#iEhCNUd)"><ellipse transform="rotate(-27.914 13.59 9.845)" class="t-hldba8v"/><ellipse fill="url(#icIla4b)" transform="rotate(-27.914 13.59 9.845)" class="c4-34w43l"/></g><g filter="url(#itltaOa)"><path stroke="url(#ilZlIzc)" class="luun4pb9o"/></g><g filter="url(#iJ5zjcd)"><path class="ji3hewb6t"/></g><g filter="url(#iM2Pe0d)"><path fill="url(#iOMXoXb)" class="rnkd2acmn"/><path fill="url(#iqwY84c)" class="rnkd2acmn"/><path fill="url(#iTnpuyd)" class="rnkd2acmn"/></g><path fill="url(#ijDj1xL)" class="rnkd2acmn"/><g filter="url(#iL1lBve)"><path class="oamyxgbkc"/></g><g filter="url(#i0spHvb)"><path class="a-71hpg1d"/></g><path class="xywpk0onj"/><defs><radialGradient id="iFqpuyc" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.328 12.649)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iXqA5zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iuxoJ3d" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.26 4.22)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="i1y9B7l" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.119 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="i4TBK6b" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.954)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="iovfRsd" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.4 15.223)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="iS9ZDiI" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.792)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="iCVqgAe" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.338 17.892)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="iwb90Fe" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.267)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="iYlbYMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.642)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iX5Gmzd" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.431 25.423)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="ielLZkb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.252 20.267)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="iE2SYiX" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.704)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="iLCWise" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.11)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="iGm40Le" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.173)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="ibWfH0n" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.861)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="ibeowCc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.454)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="iHmM1Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.07 21.2)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="iTXLUYj" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.845)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iBbC8ab" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.845)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iVMncze" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.897 58.939)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="ivUDyye" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.601)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="ilNBzdF" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.119 15.923)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="i0CwCve" cx="0" cy="0" r="1" gradientTransform="matrix(3.52963 0 0 2.27341 18.523 16.366)" gradientUnits="userSpaceOnUse"><stop class="ge69a97wz"/><stop offset="1" class="jd18rptxw"/></radialGradient><radialGradient id="inyLdJb" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.58)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="imDWS3c" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.837)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="is5rbYb" cx="0" cy="0" r="1" gradientTransform="rotate(13.799 -61.434 36.133)scale(.68782 .87718)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="iVaCY7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.358 16.486)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iqDO8xd" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 12.015 7.42)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="iPKI3md" cx="0" cy="0" r="1" gradientTransform="matrix(-7.31239 0 0 -2.83509 14.65 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="sb_6z1bpd"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="iCSSE4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.917)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="i4xyObx" cx="0" cy="0" r="1" gradientTransform="matrix(-3.3667 .90626 -1.59163 -5.9128 17.338 16.86)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="odam8hbyg"/><stop offset="1" class="du8_b9dvn"/></radialGradient><radialGradient id="iZEwBGb" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.522 11.535)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="ibHJk7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.775 16.97)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="iTblmxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.72)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="ieKcP5d" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.88 20.941)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iIvcxxb" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.48466 .4507 .80322 8.182 17.103)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="i0HK7fc" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.181 16.689)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iJx5USM" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.52344 .50555 .83423 10.26 17.157)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="ivk5jac" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.084 16.965)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="imJF0Zc" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.485)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="iXm651d" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.624 10.624)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iTeTORc" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.19 10.359)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="ibjc9wd" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.776 11.446)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iZjhfec" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.818 10.624)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="idDcSce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.396 9.351)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iiFINCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 13.834 9.485)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iqSpmke" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8549 -12.0201 0 15.746 8.848)" gradientUnits="userSpaceOnUse"><stop offset=".623" class="g5-xgwbca"/><stop offset=".957" class="vtfl3g4nf"/></radialGradient><radialGradient id="ilQr1He" cx="0" cy="0" r="1" gradientTransform="rotate(32.507 -5.77 23.023)scale(4.16897 1.56049)" gradientUnits="userSpaceOnUse"><stop class="fmt8j6yex"/><stop offset="1" class="ty3kddbpd"/></radialGradient><radialGradient id="ibhatvb" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.42495 .3845 20.396 6.513)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="i9AZE3g" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.753 4.752)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iYudbmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 16.048 2.014)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="i69Cunc" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.593 8.839)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="i9iVIww" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.375 12.232)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iwcSOgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.229 9.941)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i8EkMbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18 10.026)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGeik3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.862 9.941)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="icIla4b" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.789 -1.602)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOMXoXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.285)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="c7yfkfb_x"/><stop offset=".878" class="ly-mhyl9x"/></radialGradient><radialGradient id="iqwY84c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 13.042)" gradientUnits="userSpaceOnUse"><stop class="cycj4pb5c"/><stop offset="1" class="xkd2ooi4v"/></radialGradient><radialGradient id="iTnpuyd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25001 4.51317 -4.6352 -5.39197 23.432 6.285)" gradientUnits="userSpaceOnUse"><stop class="mbbg-bcay"/><stop offset="1" class="psls5zbwz"/><stop offset="1" class="vyoyvyblw"/></radialGradient><filter id="izasRwb" width="7.981" height="13.148" x="1.991" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/></filter><filter id="iBam3db" width="7.981" height="13.148" x="22.028" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/></filter><filter id="iwURpJb" width="9.078" height="5.683" x="17.916" y="15.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/></filter><filter id="icnAZlc" width="8.928" height="5.533" x="5.258" y="15.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/></filter><filter id="i4UX69c" width="4.194" height="5.942" x="13.971" y="12.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/></filter><filter id="irMvtze" width="3.465" height="3.465" x="14.33" y="22.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/></filter><filter id="iTvLWae" width="3.542" height="3.342" x="9.624" y="8.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/></filter><filter id="iDml0ve" width="2.992" height="2.992" x="9.8" y="9.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation=".25"/></filter><filter id="iN7qb0c" width="3.592" height="3.592" x="19.147" y="8.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/></filter><filter id="iwUICfb" width="2.992" height="2.992" x="19.322" y="9.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation=".25"/></filter><filter id="iGIkhTt" width="10.383" height="12.189" x="10.885" y="4.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/></filter><filter id="iL0RYJb" width="8.25" height="7.07" x="14.218" y="2.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation="1"/></filter><filter id="imR30Md" width="12.614" height="8.551" x="9.741" y="1.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/></filter><filter id="ivKH3Yb" width="3.262" height="4.184" x="14.178" y="9.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation=".375"/></filter><filter id="iUUPcnd" width="2.379" height="3.184" x="14.858" y="9.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation=".125"/></filter><filter id="i7qTh1c" width=".787" height=".697" x="17.494" y="9.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation=".05"/></filter><filter id="i9urkRb" width=".892" height=".914" x="18.335" y="9.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation=".1"/></filter><filter id="iQBJWrb" width=".987" height="1.041" x="13.889" y="9.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation=".1"/></filter><filter id="iEhCNUd" width=".914" height=".705" x="13.133" y="9.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation=".05"/></filter><filter id="itltaOa" width="1.008" height="2.271" x="10.877" y="5.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation=".125"/></filter><filter id="iJ5zjcd" width="13.891" height="7.06" x="9.087" y="6.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1003" stdDeviation=".375"/></filter><filter id="iM2Pe0d" width="15.159" height="7.107" x="8.403" y="6.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.152941 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.333333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1003" result="effect2_innerShadow_4002_1003"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.215686 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1003" result="effect3_innerShadow_4002_1003"/></filter><filter id="iL1lBve" width="2.192" height="1.627" x="17.223" y="8.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1003" result="effect2_innerShadow_4002_1003"/></filter><filter id="i0spHvb" width="2.192" height="1.627" x="12.726" y="8.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1003"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1003" result="effect2_innerShadow_4002_1003"/></filter><linearGradient id="io3hbsd" x1="23.236" x2="22.978" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="ihRz4Fc" x1="8.857" x2="8.994" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="iS32ave" x1="23.252" x2="23.486" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="iPO6Nic" x1="25.745" x2="20.292" y1="15.923" y2="20.135" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="iQmlBWX" x1="9.772" x2="9.772" y1="15.917" y2="20.704" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="irZlZhb" x1="9.772" x2="9.772" y1="15.548" y2="17.517" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="iJQkzcm" x1="16.985" x2="15.947" y1="23.123" y2="24.026" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="ifMSjEe" x1="11.296" x2="10.654" y1="10.903" y2="10.903" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iNCmDKc" x1="21.905" x2="21.086" y1="9.531" y2="12.07" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="i3zQ2Cb" x1="20.087" x2="12.444" y1="11.014" y2="12.153" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="i95yG3c" x1="10.647" x2="12.53" y1="13.712" y2="13.645" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="ia7yoZK" x1="20.917" x2="19.86" y1="12.874" y2="12.773" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iNQi2ac" x1="15.516" x2="23.668" y1="8.026" y2="5.108" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iEYA55d" x1="15.183" x2="16.122" y1="11.674" y2="11.674" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iLEzWFd" x1="16.987" x2="15.96" y1="11.996" y2="11.982" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iIXUpUO" x1="16.242" x2="16.242" y1="12.739" y2="12.166" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iwav3ge" x1="19.007" x2="18.693" y1="9.995" y2="10.189" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igQreob" x1="14.606" x2="14.292" y1="9.995" y2="10.189" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilZlIzc" x1="11.382" x2="11.382" y1="5.709" y2="7.868" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="ijDj1xL" x1="10.733" x2="10.979" y1="10.114" y2="9.954" gradientUnits="userSpaceOnUse"><stop offset=".102" class="a5a8_w8qp"/><stop offset=".478" class="ydi8a_bcj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-supervillain-medium-dark" /></template>
<style>
.a--e2mwlv {
  stop-color: var(--svg-color--614b90, #614B90);
}

.a-71hpg1d {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m13.077 8.779l1.607.592c.154.057.236.23.147.368c-.22.342-.656.692-1.345.489c-.65-.192-.792-.815-.755-1.257c.014-.167.188-.25.346-.193");
}

.a-lmuhb3j {
  stop-color: var(--svg-color--7560a8, #7560A8);
}

.a5a8_w8qp {
  stop-color: var(--svg-color--5e5158, #5E5158);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.av5bbdb4i {
  stop-color: var(--svg-color--ff499d, #FF499D);
}

.b__guxb5q {
  d: path("M30.01 29.986h-3.532l-4.25-8.75l3.648-4.399c3.414 4.438 4.133 10.383 4.133 13.148");
}

.b5r8fe9sv {
  stop-color: var(--svg-color--735ca8, #735CA8);
}

.bfsmm5jux {
  d: path("M4.588 29.986h22.937c-.205-3.07-.605-5.613-1.406-7.564c-2.444-5.955-7.159-6.953-10.062-6.811c-2.904-.142-7.619.856-10.063 6.811c-.8 1.95-1.2 4.494-1.406 7.563");
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

.bp5vj9b3z {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m20.871 4.14l.43.213c.752.374 1.181 1.228 1.02 2.136l-.59 3.043c-.053.314-.261.525-.573.533h-.018s.053-.907.107-1.44c.044-.434-.032-.567-.43-.962c-.214-.213-.375-.534-.375-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.918.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.748c.054.587.107 1.441.107 1.441l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.213c.268-.16.537-.374.805-.587l.966-1.015c.591-.533 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.053 2.363.534l.805.8c.215.268.483.428.805.588");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c4-34w43l {
  cx: 13.59px;
  cy: 9.845px;
  rx: 0.39px;
  ry: 0.197px;
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

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.ctoai6naw {
  stop-color: var(--svg-color--f93362, #F93362);
}

.cvb6_wfpd {
  stop-color: var(--svg-color--443063, #443063);
}

.cx3r1wb0p {
  stop-color: var(--svg-color--8b74c8, #8B74C8);
}

.cycj4pb5c {
  stop-color: var(--svg-color--322f37, #322F37);
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d-jm4nrou {
  stop-color: var(--svg-color--7757b7, #7757B7);
  stop-opacity: 0;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d9pt9np5n {
  cx: 16.554px;
  cy: 23.508px;
  rx: 0.552px;
  ry: 0.695px;
}

.dbez5ccgk {
  d: path("M9.02 15.957c0 .22.248.315.555.315c.306 0 .555-.119.555-.315a.555.555 0 0 0-1.11 0");
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
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

.e9rx7xb_x {
  stop-color: var(--svg-color--967bc2, #967BC2);
}

.ecn2fkbpq {
  stop-color: var(--svg-color--79659c, #79659C);
  stop-opacity: 0;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f2s2fz6db {
  d: path("M24.115 16.958c0 .211-.237.3-.53.3c-.291 0-.529-.112-.529-.3a.53.53 0 1 1 1.06 0");
}

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f9nu08mzt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
}

.fd6px-b3x {
  stop-color: var(--svg-color--593f75, #593F75);
}

.fdilk9b4n {
  stop-color: var(--svg-color--977fd1, #977FD1);
}

.fmt8j6yex {
  stop-color: var(--svg-color--60443a, #60443A);
}

.ft5dv1b6b {
  fill: none;
}

.fw4d8ibbd {
  d: path("M22.037 16.958c0 .293-.237.367-.53.367c-.292 0-.529-.075-.529-.367a.53.53 0 1 1 1.059 0");
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.fypjwijgc {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
}

.g-sinpvdo {
  cx: 20.818px;
  cy: 10.624px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.g2wrz_okq {
  stop-color: var(--svg-color--bb4566, #BB4566);
}

.g5-xgwbca {
  stop-color: var(--svg-color--804d5d, #804D5D);
  stop-opacity: 0;
}

.ge69a97wz {
  stop-color: var(--svg-color--961241, #961241);
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.gsgtixbyq {
  d: path("m20.015 4.994l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.hcn9qvb5t {
  d: path("m10.943 10.01l.05.002s-.054-.854-.108-1.441c0-.267.107-.587.322-.748l.161-.16c.269-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.054.429.267.429.534v.854c0 .32.16.64.376.854c.502.352.47.546.43.961c-.055.534-.108 1.442-.108 1.442h.018l-.266 3.962c-.16 1.77-1.553 3.005-3.214 3.005h-3.213c-1.714 0-3.053-1.234-3.213-3.005z");
}

.hl0sk802z {
  cx: 16.062px;
  cy: 23.995px;
  r: 1.732px;
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.i3hug6b7s {
  stop-color: var(--svg-color--655586, #655586);
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

.j05qr1bdn {
  d: path("M18.23 9.464a.893.893 0 0 1 .861 1.128h-1.725a.897.897 0 0 1 .865-1.128");
}

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.j5d124bow {
  d: path("M7.987 16.95c0 .211.237.301.529.301s.53-.113.53-.3a.53.53 0 0 0-1.06 0");
}

.jd18rptxw {
  stop-color: var(--svg-color--d31c55, #D31C55);
  stop-opacity: 0;
}

.ji3hewb6t {
  fill: var(--svg-color--67393a, #67393A);
  d: path("m9.897 8.202l3.235 4.806a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.153c.08-.24.253-.576.388-.576c.154 0 .313.337.393.576a.4.4 0 0 0 .085.153l1.45 1.655a.617.617 0 0 0 .975-.06l3.235-4.806c.174-.258-.057-.56-.354-.466l-4.821 1.51a.5.5 0 0 0-.278.25c-.178.342-.476.514-.685.52c-.21-.006-.503-.178-.68-.52a.5.5 0 0 0-.278-.25l-4.821-1.51c-.298-.093-.529.208-.354.466");
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jywmtub7y {
  d: path("m15.665 10.338l-.532 1.702a.54.54 0 0 0 .521.7h.787c.37 0 .63-.356.521-.7l-.532-1.702c-.113-.377-.645-.377-.765 0");
}

.k0tipmbrg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.438 9.192c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
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

.ksp1sznci {
  stop-color: var(--svg-color--6d55a5, #6D55A5);
  stop-opacity: 0;
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l1led_brw {
  stop-color: var(--svg-color--df1d5a, #DF1D5A);
}

.l2c0efs8e {
  d: path("M25.118 15.965c0 .22-.249.315-.555.315s-.556-.119-.556-.316a.555.555 0 0 1 1.11 0");
}

.l6lsh3b7c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.165 9.653c.064.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.16-.359c.15-.113.325-.135.388-.05");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.lo3a_acnh {
  cx: 11.296px;
  cy: 10.624px;
  r: 0.996px;
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.luun4pb9o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.51 5.808v.898c-.007.15-.07.482-.258.623");
}

.ly-mhyl9x {
  stop-color: var(--svg-color--4a474e, #4A474E);
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

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mwufvlb3p {
  d: path("M14.676 10.252c0-.289-.235-.481-.299-.54l-.288.28l.177.361z");
}

.mx-85jb1t {
  d: path("m15.575 21.316l-2.98-4.596h6.946l-2.958 4.594a.6.6 0 0 1-1.008.002");
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

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.o2io-ujbo {
  d: path("M13.86 9.464a.893.893 0 0 0-.861 1.128h1.725a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.oamyxgbkc {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m19.064 8.779l-1.608.592c-.154.057-.235.23-.147.368c.22.342.656.692 1.345.489c.65-.192.792-.815.755-1.257c-.014-.167-.188-.25-.345-.193");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odam8hbyg {
  stop-color: var(--svg-color--835ac7, #835AC7);
}

.oepmfgb3z {
  fill: var(--svg-color--000, #000);
  d: path("M17.72 10.357a.51.51 0 0 1 .51-.512a.51.51 0 0 1 .456.747h-.906a.46.46 0 0 1-.06-.235");
}

.ogttk6b6n {
  stop-color: var(--svg-color--774ca5, #774CA5);
}

.p6-aag9fy {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.772 10.502l-.82 1.7c-.103.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.377-.284-.377-.396 0");
}

.p63xbfaao {
  stop-color: var(--svg-color--85527f, #85527F);
  stop-opacity: 0;
}

.p6d2azb8i {
  d: path("M10.885 8.57c0-.266.107-.586.322-.747l.161-.16c.269-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.054.429.267.429.534v.854c0 .32.16.64.376.854c.502.352.47.546.43.961c-.055.534-.108 1.442-.108 1.442h.018l-.266 3.962c-.16 1.77-1.553 3.005-3.214 3.005h-3.213c-1.714 0-3.053-1.234-3.213-3.005c-.14-1.819-.201-3.642-.367-5.457");
}

.pbx1a_0-e {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.957c0 .22.248.315.555.315c.306 0 .555-.119.555-.315a.555.555 0 0 0-1.11 0");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pq3p2ab2a {
  d: path("M18.165 9.653c.064.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.16-.359c.15-.113.325-.135.388-.05");
}

.psls5zbwz {
  stop-color: var(--svg-color--625570, #625570);
  stop-opacity: 0;
}

.ptuohkesm {
  stop-color: var(--svg-color--cd2172, #CD2172);
  stop-opacity: 0;
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q-vyvnloj {
  d: path("M23.252 18.142v11.843h4.273c-.205-3.069-.605-5.612-1.406-7.563c-.772-1.88-1.77-3.267-2.867-4.28");
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.qaycvn_cp {
  stop-color: var(--svg-color--67416e, #67416E);
}

.qf-zh-bgi {
  stop-color: var(--svg-color--755da2, #755DA2);
  stop-opacity: 0;
}

.qsjdql87s {
  stop-color: var(--svg-color--ae495e, #AE495E);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.r5lwd_9jp {
  fill: var(--svg-color--64417a, #64417A);
  d: path("M6.984 15.957c0 .22.249.315.555.315s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rnkd2acmn {
  d: path("m8.576 6.872l3.932 5.84a.75.75 0 0 0 1.185.074l1.761-2.012a.5.5 0 0 0 .104-.185c.098-.291.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.185l1.761 2.012a.75.75 0 0 0 1.185-.073l3.932-5.84c.212-.314-.069-.68-.43-.567L17.2 8.14a.6.6 0 0 0-.338.304c-.216.415-.578.625-.833.631c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.305L9.006 6.306c-.361-.113-.642.253-.43.566");
}

.rqy_z7taf {
  d: path("M23.083 15.965c0 .22-.249.315-.556.315c-.306 0-.555-.119-.555-.316a.555.555 0 1 1 1.11 0");
}

.rze2kbbww {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.665 10.338l-.532 1.702a.54.54 0 0 0 .521.7h.787c.37 0 .63-.356.521-.7l-.532-1.702c-.113-.377-.645-.377-.765 0");
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sb_6z1bpd {
  stop-color: var(--svg-color--761032, #761032);
}

.slx6fqref {
  stop-color: var(--svg-color--e1658e, #E1658E);
  stop-opacity: 0;
}

.spz-82b7z {
  cx: 11.295px;
  cy: 10.624px;
  r: 1.671px;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t-hldba8v {
  cx: 13.59px;
  cy: 9.845px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.t-qfzd5dc {
  fill: var(--svg-color--000, #000);
  d: path("M14.371 10.357a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.235");
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.terk_xbor {
  cx: 20.818px;
  cy: 10.624px;
  r: 0.996px;
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.ty3kddbpd {
  stop-color: var(--svg-color--60443a, #60443A);
  stop-opacity: 0;
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
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

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
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

.uvjko3k9x {
  d: path("M6.984 15.957c0 .22.249.315.555.315s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.ux10xmbuk {
  d: path("m20.871 4.14l.43.213c.752.374 1.181 1.228 1.02 2.136l-.59 3.043c-.053.314-.261.525-.573.533h-.018s.053-.907.107-1.44c.044-.434-.032-.567-.43-.962c-.214-.213-.375-.534-.375-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.918.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.748c.054.587.107 1.441.107 1.441l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.213c.268-.16.537-.374.805-.587l.966-1.015c.591-.533 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.053 2.363.534l.805.8c.215.268.483.428.805.588");
}

.uxt_ehm2r {
  d: path("M10.065 16.95c0 .293.237.367.53.367c.291 0 .528-.074.528-.367a.53.53 0 0 0-1.058 0");
}

.v_v98qact {
  stop-color: var(--svg-color--230f39, #230F39);
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.vat9yt_ey {
  stop-color: var(--svg-color--614290, #614290);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vtfl3g4nf {
  stop-color: var(--svg-color--6e2d39, #6E2D39);
}

.vv3mrckep {
  d: path("M24.635 19.919c-.75 1.082-1.856 1.976-4.008 1.05c-1.836-.788-2.711-3.268-2.711-5.046l8.203.023c.652 0 .752.442.492.856c-.646 1.03-1.52 2.406-1.976 3.117");
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wggtpctur {
  d: path("M13.971 15.075a2.097 2.097 0 1 1 4.194 0v1.548c0 1.37-.938 2.097-2.097 2.097c-1.158 0-2.097-.695-2.097-2.097z");
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.x3ac2p_-t {
  d: path("M8.861 18.142v11.843H4.588c.205-3.069.605-5.612 1.406-7.563c.772-1.88 1.77-3.267 2.867-4.28");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xkd2ooi4v {
  stop-color: var(--svg-color--322f37, #322F37);
  stop-opacity: 0;
}

.xkk8eybzc {
  cx: 20.818px;
  cy: 10.624px;
  r: 1.671px;
}

.xrr4vbcci {
  stop-color: var(--svg-color--7560a8, #7560A8);
  stop-opacity: 0;
}

.xywpk0onj {
  fill: var(--svg-color--930458, #930458);
  d: path("M17.75 12.648c-.614.807-1.368.893-1.872.925c-.085.005-.12.104-.051.153c.377.27.857.293 1.342.09c.51-.212.733-.703.747-1.123c.003-.091-.11-.118-.165-.045");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y-so25ixd {
  stop-color: var(--svg-color--50387f, #50387F);
}

.y06th9bdt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
  stop-opacity: 0;
}

.y6ukhtacc {
  d: path("M19.026 10.24a.84.84 0 0 0-.231-.464l-.26.286l.117.228z");
}

.y82w82gtu {
  d: path("M1.99 29.986h3.532l4.25-8.75l-3.648-4.399C2.71 21.275 1.99 27.22 1.99 29.985");
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ydi8a_bcj {
  stop-color: var(--svg-color--5e5158, #5E5158);
  stop-opacity: 0;
}

.yey76mb1n {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.653 9.192c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.232a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.yhvjw36xj {
  stop-color: var(--svg-color--563079, #563079);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yog48s40z {
  stop-color: var(--svg-color--ff5292, #FF5292);
}

.yr3p0jbaj {
  stop-color: var(--svg-color--5d3970, #5D3970);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z9cekbb2i {
  d: path("M7.467 19.913c.75 1.083 1.855 1.977 4.008 1.051c1.836-.789 2.71-3.269 2.71-5.047l-8.202.024c-.653 0-.752.442-.492.855c.645 1.03 1.519 2.406 1.976 3.117");
}

.zblf_actk {
  stop-color: var(--svg-color--372543, #372543);
}

.zhe9zhdzx {
  stop-color: var(--svg-color--7a4c9c, #7A4C9C);
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zojxemb8i {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
  stop-opacity: 0;
}

.zxe--8tbm {
  stop-color: var(--svg-color--50387f, #50387F);
  stop-opacity: 0;
}

</style>
