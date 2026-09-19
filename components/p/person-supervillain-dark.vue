<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuu12Oe)"><path fill="url(#iFqpuyc)" class="fjfdrzb7y"/><path fill="url(#iXqA5zb)" class="fjfdrzb7y"/></g><g filter="url(#i4ZVN4d)"><path fill="url(#iuxoJ3d)" class="fn9llr-4b"/><path fill="url(#i1y9B7l)" class="fn9llr-4b"/></g><path fill="url(#i4TBK6b)" class="th4v7c7lc"/><path fill="url(#iovfRsd)" class="th4v7c7lc"/><path fill="url(#iS9ZDiI)" class="th4v7c7lc"/><path fill="url(#ipb9C6d)" class="th4v7c7lc"/><path fill="url(#iCVqgAe)" class="th4v7c7lc"/><path fill="url(#iwb90Fe)" class="th4v7c7lc"/><path fill="url(#iYlbYMc)" class="th4v7c7lc"/><path fill="url(#ilLMcAb)" class="th4v7c7lc"/><path fill="url(#iX6SMcd)" class="vipjwwaoi"/><path fill="url(#ielLZkb)" class="vipjwwaoi"/><path fill="url(#iE2SYiX)" class="vipjwwaoi"/><path fill="url(#iS32ave)" class="vipjwwaoi"/><path fill="url(#iLCWise)" class="jd2wixbxg"/><path fill="url(#iGm40Le)" class="jd2wixbxg"/><path fill="url(#ibWfH0n)" class="jd2wixbxg"/><path fill="url(#ibeowCc)" class="jd2wixbxg"/><path fill="url(#iHmM1Fe)" class="f_z9dccjp"/><path fill="url(#iTXLUYj)" class="fg2yxxizz"/><path fill="url(#iBbC8ab)" class="t3sh78bml"/><g filter="url(#inFhuic)"><path fill="url(#i5sGDuc)" class="irvd0gopv"/><path fill="url(#iDtXXCY)" class="irvd0gopv"/><path fill="url(#iMieJUd)" class="irvd0gopv"/><path fill="url(#iKEq6hc)" class="irvd0gopv"/><path fill="url(#i0CwCve)" class="irvd0gopv"/></g><path class="pbx1a_0-e"/><path fill="url(#inyLdJb)" class="dbez5ccgk"/><path fill="url(#imDWS3c)" class="dbez5ccgk"/><path class="r5lwd_9jp"/><path fill="url(#is5rbYb)" class="uvjko3k9x"/><g filter="url(#ic1O21E)"><path fill="url(#iQmlBWX)" class="pnrkvto3p"/><path fill="url(#irZlZhb)" class="pnrkvto3p"/><path fill="url(#iVaCY7b)" class="pnrkvto3p"/><path fill="url(#iqDO8xd)" class="pnrkvto3p"/><path fill="url(#iPKI3md)" class="pnrkvto3p"/><path fill="url(#iCSSE4c)" class="pnrkvto3p"/></g><g filter="url(#iXZBWqc)"><path fill="url(#iEk0t0b)" class="ult9otb7c"/></g><path fill="url(#iZEwBGb)" class="gmo59fbsi"/><path fill="url(#iZVAlYc)" class="gmo59fbsi"/><path fill="url(#iTblmxe)" class="hsuj-b9qt"/><path fill="url(#ieKcP5d)" class="t_0girb4l"/><path fill="url(#iAPfeUd)" class="t_0girb4l"/><path fill="url(#iuUNfsy)" class="lmv51mb1h"/><path fill="url(#iJx5USM)" class="lmv51mb1h"/><g filter="url(#iL5ACte)"><circle fill="url(#i1IxFBe)" class="wnzu6gyxf"/><circle fill="url(#imJF0Zc)" class="wnzu6gyxf"/></g><ellipse fill="url(#iJzI5Ge)" transform="rotate(-31.445 16.554 23.508)" class="d9pt9np5n"/><path fill="url(#ipIEUUD)" class="hr2m_vbnp"/><path fill="url(#iXplahe)" class="fbz_tbb1i"/><g filter="url(#i9W49Fc)"><path fill="url(#i2z4fkd)" class="uif5em7ve"/></g><path fill="url(#i3kfZBe)" class="uif5em7ve"/><path fill="url(#iNuzMjb)" class="uif5em7ve"/><path fill="url(#if4knUb)" class="uif5em7ve"/><path fill="url(#iYXzqJc)" class="uif5em7ve"/><path fill="url(#iqDOfne)" class="uif5em7ve"/><path fill="url(#iZKBL4d)" class="uif5em7ve"/><path fill="url(#iKv3Aje)" class="uif5em7ve"/><path fill="url(#iye4zHc)" class="uif5em7ve"/><path fill="url(#iGhYiTc)" class="uif5em7ve"/><path fill="url(#iIzuqVI)" class="uif5em7ve"/><path fill="url(#idRC5KA)" class="uif5em7ve"/><g filter="url(#icFobdd)"><path class="aktbp45oh"/></g><path class="ubi3zzb9f"/><path fill="url(#iqGsWAd)" class="gju63hufz"/><path fill="url(#iDBcKdb)" class="gju63hufz"/><path fill="url(#ivDSEqd)" class="gju63hufz"/><path fill="url(#icWrJDc)" class="gju63hufz"/><path fill="url(#iH5Up6T)" class="gju63hufz"/><g filter="url(#iAPqnge)"><path fill="url(#i666WtV)" class="wphxpcbvw"/><path fill="url(#iXlSnle)" class="wphxpcbvw"/><path fill="url(#ixZQsGc)" class="wphxpcbvw"/><path fill="url(#iEj0jGc)" class="wphxpcbvw"/><path fill="url(#iLH0Zcb)" class="wphxpcbvw"/></g><g filter="url(#iTtzf6b)"><path class="maj0-8bkx"/><path fill="url(#iiL40hb)" class="g1ewtwbgj"/><path fill="url(#idElZne)" class="g1ewtwbgj"/></g><g filter="url(#iP2JMOe)"><path class="u7mpgeuwq"/><path fill="url(#iXGXkdc)" class="f5rntzbon"/></g><path fill="url(#ifTpHAb)" class="bvsrql82x"/><path fill="url(#iEoTxzb)" class="bvsrql82x"/><path fill="url(#iYmcaYc)" class="bvsrql82x"/><path fill="url(#iLmdUub)" class="bvsrql82x"/><path fill="url(#iCRoJTd)" class="jvexho1go"/><path fill="url(#iaqunFd)" class="jvexho1go"/><g filter="url(#iA4Hpec)"><path fill="url(#idgDgAh)" class="oirwh180k"/></g><g filter="url(#i1wI7qe)"><path fill="url(#igwEG7d)" class="g6aitjqsq"/></g><g filter="url(#il5nW8b)"><path class="w9ixvabyl"/></g><g filter="url(#i6whC2d)"><path class="um4v3ch7x"/></g><g filter="url(#i8PBaMd)"><path fill="url(#iOMXoXb)" class="d34lxkbiu"/><path fill="url(#iqwY84c)" class="d34lxkbiu"/><path fill="url(#iTnpuyd)" class="d34lxkbiu"/></g><path fill="url(#ijDj1xL)" class="d34lxkbiu"/><g filter="url(#i4nE1ud)"><path class="l7wu4ybff"/></g><g filter="url(#ixMLDbd)"><path class="tdbpv-bck"/></g><g filter="url(#iaTStFe)"><path stroke="url(#iYEFsAd)" class="zrw7q7-1s"/></g><path class="uu75qbzsz"/><defs><radialGradient id="iFqpuyc" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.328 12.649)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iXqA5zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iuxoJ3d" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.26 4.22)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="i1y9B7l" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.119 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="i4TBK6b" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.954)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="iovfRsd" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.4 15.223)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="iS9ZDiI" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.792)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="iCVqgAe" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.338 17.892)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="iwb90Fe" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.267)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="iYlbYMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.642)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iX6SMcd" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.432 25.423)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="ielLZkb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.252 20.267)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="iE2SYiX" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.704)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="iLCWise" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.11)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="iGm40Le" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.173)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="ibWfH0n" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.861)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="ibeowCc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.454)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="iHmM1Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.07 21.2)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="iTXLUYj" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.845)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iBbC8ab" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.845)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iDtXXCY" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.896 58.94)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="iMieJUd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.6)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="iKEq6hc" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.12 15.923)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="i0CwCve" cx="0" cy="0" r="1" gradientTransform="matrix(3.52963 0 0 2.27341 18.523 16.366)" gradientUnits="userSpaceOnUse"><stop class="ge69a97wz"/><stop offset="1" class="jd18rptxw"/></radialGradient><radialGradient id="inyLdJb" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.58)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="imDWS3c" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.837)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="is5rbYb" cx="0" cy="0" r="1" gradientTransform="rotate(13.799 -61.434 36.133)scale(.68782 .87718)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="iVaCY7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.358 16.486)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iqDO8xd" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 12.015 7.42)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="iPKI3md" cx="0" cy="0" r="1" gradientTransform="matrix(-7.31239 0 0 -2.83509 14.65 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="sb_6z1bpd"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="iCSSE4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.917)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="iEk0t0b" cx="0" cy="0" r="1" gradientTransform="rotate(160.752 7.093 9.794)scale(3.22747 5.66825)" gradientUnits="userSpaceOnUse"><stop class="tip65z0am"/><stop offset="1" class="ek8xgnb4y"/></radialGradient><radialGradient id="iZEwBGb" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.522 11.535)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="iZVAlYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.776 16.97)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="iTblmxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.72)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="ieKcP5d" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.88 20.941)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iAPfeUd" cx="0" cy="0" r="1" gradientTransform="rotate(-29.297 36.806 -7.1)scale(.99044 .92102)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="iuUNfsy" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.182 16.688)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iJx5USM" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.52344 .50555 .83423 10.26 17.157)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="i1IxFBe" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.085 16.965)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="imJF0Zc" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.485)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="ipIEUUD" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.929 20.865)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iXplahe" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 10.012 12.293)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="i2z4fkd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.876 10.862)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iNuzMjb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02223 12.42352 -10.28813 -.84653 17.65 4.949)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="if4knUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.516 9.55)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iYXzqJc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.7 -2.111)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iqDOfne" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.501 11.85)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iZKBL4d" cx="0" cy="0" r="1" gradientTransform="matrix(4.073 -2.6483 .96946 1.491 10.601 6.537)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iKv3Aje" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.19 13.811)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iye4zHc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.589 8.157)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iIzuqVI" cx="0" cy="0" r="1" gradientTransform="matrix(7.87873 .30897 -.67373 17.18 13.628 12.105)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="o1syipbau"/><stop offset=".973" class="p7wwt2b_k"/></radialGradient><radialGradient id="idRC5KA" cx="0" cy="0" r="1" gradientTransform="matrix(3.09745 0 0 .75546 16.115 16.58)" gradientUnits="userSpaceOnUse"><stop class="w9h1cgbuc"/><stop offset="1" class="qj098bbiu"/></radialGradient><radialGradient id="iDBcKdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.535 12.223)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="icWrJDc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.651 11.653)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iXlSnle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.839 7.97)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="ixZQsGc" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.32 -6.31)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iEj0jGc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.175 3.004)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iLH0Zcb" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.163 1.411)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iiL40hb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.322 3.67)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="idElZne" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.225 -5.844)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iXGXkdc" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -42.67 155.95)scale(3.27033 1.36922)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iEoTxzb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.686 9.96)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iYmcaYc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.047 10.504)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iLmdUub" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.16 10.677)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iaqunFd" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.247 9.498)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="idgDgAh" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 11.153 10.604)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="iOMXoXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.285)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="c7yfkfb_x"/><stop offset=".878" class="ly-mhyl9x"/></radialGradient><radialGradient id="iqwY84c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 13.042)" gradientUnits="userSpaceOnUse"><stop class="cycj4pb5c"/><stop offset="1" class="xkd2ooi4v"/></radialGradient><radialGradient id="iTnpuyd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25001 4.51317 -4.6352 -5.39197 23.432 6.285)" gradientUnits="userSpaceOnUse"><stop class="mbbg-bcay"/><stop offset="1" class="psls5zbwz"/><stop offset="1" class="vyoyvyblw"/></radialGradient><radialGradient id="iYEFsAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57932 2.45245 0 16.245 14.017)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></radialGradient><filter id="iuu12Oe" width="7.981" height="13.148" x="1.991" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/></filter><filter id="i4ZVN4d" width="7.981" height="13.148" x="22.028" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/></filter><filter id="inFhuic" width="9.078" height="5.683" x="17.916" y="15.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/></filter><filter id="ic1O21E" width="8.928" height="5.533" x="5.258" y="15.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/></filter><filter id="iXZBWqc" width="4.194" height="5.942" x="13.971" y="12.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/></filter><filter id="iL5ACte" width="3.465" height="3.465" x="14.33" y="22.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/></filter><filter id="i9W49Fc" width="11.22" height="12.542" x="11.005" y="4.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_998" result="effect2_innerShadow_4002_998"/></filter><filter id="icFobdd" width="3.747" height="4.9" x="14.053" y="9.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_998" stdDeviation=".5"/></filter><filter id="iAPqnge" width="12.873" height="8.357" x="9.632" y="1.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_998" result="effect2_innerShadow_4002_998"/></filter><filter id="iTtzf6b" width="6.734" height="5.992" x="9.987" y="2.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/><feGaussianBlur result="effect2_foregroundBlur_4002_998" stdDeviation=".125"/></filter><filter id="iP2JMOe" width="6.362" height="5.736" x="15.909" y="3.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/><feGaussianBlur result="effect2_foregroundBlur_4002_998" stdDeviation=".125"/></filter><filter id="iA4Hpec" width="1.329" height="2.379" x="9.987" y="9.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_998" stdDeviation=".125"/></filter><filter id="i1wI7qe" width="1.947" height="2.903" x="20.511" y="9.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_998" stdDeviation=".25"/></filter><filter id="il5nW8b" width="5.266" height="3.006" x="16.948" y="3.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_998" stdDeviation=".375"/></filter><filter id="i6whC2d" width="13.891" height="7.06" x="9.087" y="6.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_998" stdDeviation=".375"/></filter><filter id="i8PBaMd" width="15.159" height="7.107" x="8.403" y="6.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.152941 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.333333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_998" result="effect2_innerShadow_4002_998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.215686 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_998" result="effect3_innerShadow_4002_998"/></filter><filter id="i4nE1ud" width="2.192" height="1.627" x="17.223" y="8.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_998" result="effect2_innerShadow_4002_998"/></filter><filter id="ixMLDbd" width="2.192" height="1.627" x="12.726" y="8.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_998" result="effect2_innerShadow_4002_998"/></filter><filter id="iaTStFe" width="2.476" height="1.695" x="15.615" y="12.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_998" stdDeviation=".05"/></filter><linearGradient id="ipb9C6d" x1="23.236" x2="22.979" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="ilLMcAb" x1="8.858" x2="8.994" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="iS32ave" x1="23.252" x2="23.486" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="i5sGDuc" x1="25.746" x2="20.292" y1="15.923" y2="20.134" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="iQmlBWX" x1="9.772" x2="9.772" y1="15.917" y2="20.704" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="irZlZhb" x1="9.772" x2="9.772" y1="15.548" y2="17.517" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="iJzI5Ge" x1="16.985" x2="15.947" y1="23.122" y2="24.026" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="i3kfZBe" x1="21.226" x2="16.873" y1="12.547" y2="12.547" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iGhYiTc" x1="16.116" x2="16.116" y1="17.114" y2="16.474" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iqGsWAd" x1="16.698" x2="15.901" y1="11.438" y2="11.501" gradientUnits="userSpaceOnUse"><stop offset=".159" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="ivDSEqd" x1="16.069" x2="16.069" y1="12.676" y2="12.211" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iH5Up6T" x1="16.069" x2="16.069" y1="9.721" y2="10.517" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="i666WtV" x1="22.92" x2="11.308" y1="5.199" y2="5.199" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ifTpHAb" x1="22.505" x2="21.298" y1="10.027" y2="12.203" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iCRoJTd" x1="10.219" x2="11.677" y1="10.73" y2="10.603" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="igwEG7d" x1="21.485" x2="21.485" y1="9.645" y2="11.548" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="ijDj1xL" x1="10.733" x2="10.979" y1="10.114" y2="9.954" gradientUnits="userSpaceOnUse"><stop offset=".102" class="a5a8_w8qp"/><stop offset=".478" class="ydi8a_bcj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-supervillain-dark" /></template>
<style>
.a--e2mwlv {
  stop-color: var(--svg-color--614b90, #614B90);
}

.a-lmuhb3j {
  stop-color: var(--svg-color--7560a8, #7560A8);
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a5a8_w8qp {
  stop-color: var(--svg-color--5e5158, #5E5158);
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.aktbp45oh {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.667 10.343l-.59 1.838c-.102.379.14.757.484.757h.731c.343 0 .586-.384.485-.757l-.495-1.838c-.106-.407-.504-.407-.615 0");
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.av5bbdb4i {
  stop-color: var(--svg-color--ff499d, #FF499D);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b5r8fe9sv {
  stop-color: var(--svg-color--735ca8, #735CA8);
}

.bfw_o9sgk {
  stop-color: var(--svg-color--8977bc, #8977BC);
  stop-opacity: 0;
}

.bkplcs5-b {
  stop-color: var(--svg-color--615181, #615181);
  stop-opacity: 0;
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bozoj1btu {
  stop-color: var(--svg-color--e7547f, #E7547F);
  stop-opacity: 0;
}

.bvsrql82x {
  d: path("M20.99 12.203q.1-1.596.185-3.191a1.61 1.61 0 0 1-.185 3.19");
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c50kycc4s {
  stop-color: var(--svg-color--ff5292, #FF5292);
  stop-opacity: 0;
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c7yfkfb_x {
  stop-color: var(--svg-color--453753, #453753);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbuctgb-f {
  stop-color: var(--svg-color--dd225e, #DD225E);
  stop-opacity: 0;
}

.cgymddbwl {
  stop-color: var(--svg-color--3f2563, #3F2563);
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

.d-jm4nrou {
  stop-color: var(--svg-color--7757b7, #7757B7);
  stop-opacity: 0;
}

.d34lxkbiu {
  d: path("m8.576 6.872l3.932 5.84a.75.75 0 0 0 1.185.074l1.761-2.012a.5.5 0 0 0 .104-.185c.098-.292.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.185l1.761 2.012a.75.75 0 0 0 1.185-.073l3.932-5.84c.212-.314-.069-.68-.43-.567L17.2 8.14a.6.6 0 0 0-.338.304c-.216.415-.578.625-.833.631c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.305L9.006 6.306c-.361-.113-.642.253-.43.566");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
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

.dkr4vta7s {
  stop-color: var(--svg-color--8977bc, #8977BC);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.do8d1irdg {
  stop-color: var(--svg-color--e1658e, #E1658E);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
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

.ek8xgnb4y {
  stop-color: var(--svg-color--453363, #453363);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f_z9dccjp {
  d: path("m15.575 21.315l-2.98-4.595h6.946l-2.958 4.594a.6.6 0 0 1-1.008.001");
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f5rntzbon {
  d: path("m21.281 8.513l-.029-.631c-.01-.764-.642-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.367c-.257-.97.67-1.713 1.655-1.522c.974.189 2.082.517 2.902 1.052c1.745 1.138 1.44 3.188.521 4.154");
}

.f9nu08mzt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
}

.fbz_tbb1i {
  d: path("M11.207 12.112a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fd6px-b3x {
  stop-color: var(--svg-color--593f75, #593F75);
}

.fdilk9b4n {
  stop-color: var(--svg-color--977fd1, #977FD1);
}

.fg2yxxizz {
  d: path("M23.083 15.964c0 .222-.249.316-.556.316c-.306 0-.555-.12-.555-.316a.555.555 0 1 1 1.11 0");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fjfdrzb7y {
  d: path("M1.99 29.985h3.532l4.25-8.75l-3.648-4.398C2.71 21.274 1.99 27.22 1.99 29.985");
}

.fn9llr-4b {
  d: path("M30.01 29.985h-3.532l-4.25-8.75l3.648-4.398c3.414 4.437 4.133 10.383 4.133 13.148");
}

.ft5dv1b6b {
  fill: none;
}

.fypjwijgc {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
}

.g1ewtwbgj {
  d: path("m16.3 5.246l-.065-.137a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.34 1.513-3.34 3.38v.274c-.34-.258-.769-.804-.769-1.687c0-1.072.782-1.614 1.28-1.96c.142-.097.26-.18.332-.253l.1-.105c.349-.37.972-1.031 2.059-1.32a5.5 5.5 0 0 1 1.508-.165c.472.012.806.42.806.893v1.485z");
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g2wrz_okq {
  stop-color: var(--svg-color--bb4566, #BB4566);
}

.g6aitjqsq {
  d: path("M21.011 11.548q.059-.951.111-1.903a.956.956 0 0 1-.11 1.903");
}

.ge69a97wz {
  stop-color: var(--svg-color--961241, #961241);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gju63hufz {
  d: path("m15.686 10.147l-.531 1.839c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.645-.407-.765 0");
}

.gmo59fbsi {
  d: path("M22.037 16.958c0 .292-.237.367-.53.367c-.291 0-.528-.075-.528-.367a.53.53 0 0 1 1.058 0");
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hr2m_vbnp {
  d: path("M20.93 12.112a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.69-1.34 2.02c.17-.363.287-.759.345-1.18z");
}

.hsuj-b9qt {
  d: path("M24.115 16.958c0 .21-.237.3-.529.3s-.53-.113-.53-.3a.53.53 0 1 1 1.06 0");
}

.i3hug6b7s {
  stop-color: var(--svg-color--655586, #655586);
}

.ib49rus2q {
  stop-color: var(--svg-color--72599f, #72599F);
  stop-opacity: 0;
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ie12c-fkv {
  stop-color: var(--svg-color--ee205c, #EE205C);
  stop-opacity: 0;
}

.iek0mvbvg {
  stop-color: var(--svg-color--563680, #563680);
}

.irvd0gopv {
  d: path("M24.635 19.919c-.75 1.082-1.855 1.976-4.008 1.05c-1.836-.788-2.71-3.268-2.71-5.046l8.202.023c.653 0 .752.442.492.856a376 376 0 0 1-1.976 3.117");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.jd18rptxw {
  stop-color: var(--svg-color--d31c55, #D31C55);
  stop-opacity: 0;
}

.jd2wixbxg {
  d: path("M8.861 18.142v11.843H4.588c.205-3.069.605-5.613 1.406-7.563c.772-1.881 1.77-3.268 2.867-4.28");
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jvexho1go {
  d: path("M11.014 9.003a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kejp2n55e {
  stop-color: var(--svg-color--79659c, #79659C);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
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

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1led_brw {
  stop-color: var(--svg-color--df1d5a, #DF1D5A);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l7wu4ybff {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m19.064 8.778l-1.608.593c-.154.057-.235.23-.147.367c.22.343.656.693 1.345.49c.65-.192.792-.815.755-1.257c-.014-.167-.188-.25-.345-.193");
}

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.lmv51mb1h {
  d: path("M10.065 16.95c0 .293.237.367.53.367c.292 0 .529-.075.529-.367a.53.53 0 1 0-1.059 0");
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
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

.maj0-8bkx {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.3 5.246l-.065-.137a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.34 1.513-3.34 3.38v.274c-.34-.258-.769-.804-.769-1.687c0-1.072.782-1.614 1.28-1.96c.142-.097.26-.18.332-.253l.1-.105c.349-.37.972-1.031 2.059-1.32a5.5 5.5 0 0 1 1.508-.165c.472.012.806.42.806.893v1.485z");
}

.mbbg-bcay {
  stop-color: var(--svg-color--625570, #625570);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
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

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.ogttk6b6n {
  stop-color: var(--svg-color--774ca5, #774CA5);
}

.oirwh180k {
  d: path("M10.983 9.663a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p63xbfaao {
  stop-color: var(--svg-color--85527f, #85527F);
  stop-opacity: 0;
}

.p7wwt2b_k {
  stop-color: var(--svg-color--685654, #685654);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pbx1a_0-e {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.957c0 .22.248.315.555.315c.306 0 .555-.119.555-.315a.555.555 0 0 0-1.11 0");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pnrkvto3p {
  d: path("M7.467 19.913c.75 1.082 1.856 1.976 4.008 1.051c1.836-.789 2.711-3.269 2.711-5.047l-8.203.024c-.652 0-.751.442-.492.855c.646 1.03 1.52 2.406 1.976 3.117");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psls5zbwz {
  stop-color: var(--svg-color--625570, #625570);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.ptuohkesm {
  stop-color: var(--svg-color--cd2172, #CD2172);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qaycvn_cp {
  stop-color: var(--svg-color--67416e, #67416E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qf-zh-bgi {
  stop-color: var(--svg-color--755da2, #755DA2);
  stop-opacity: 0;
}

.qj098bbiu {
  stop-color: var(--svg-color--3f3b2c, #3F3B2C);
  stop-opacity: 0;
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qsjdql87s {
  stop-color: var(--svg-color--ae495e, #AE495E);
}

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.r5lwd_9jp {
  fill: var(--svg-color--64417a, #64417A);
  d: path("M6.984 15.957c0 .22.249.315.555.315s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.sb_6z1bpd {
  stop-color: var(--svg-color--761032, #761032);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.slx6fqref {
  stop-color: var(--svg-color--e1658e, #E1658E);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t_0girb4l {
  d: path("M7.987 16.95c0 .211.237.3.53.3c.292 0 .529-.112.529-.3a.53.53 0 1 0-1.06 0");
}

.t3sh78bml {
  d: path("M25.118 15.964c0 .222-.249.316-.555.316s-.556-.12-.556-.316a.555.555 0 0 1 1.11 0");
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.tdbpv-bck {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m13.077 8.778l1.607.593c.154.057.236.23.147.367c-.22.343-.656.693-1.345.49c-.65-.192-.792-.815-.755-1.257c.014-.167.188-.25.346-.193");
}

.th4v7c7lc {
  d: path("M4.588 29.985h22.938c-.206-3.069-.606-5.613-1.406-7.563c-2.445-5.955-7.16-6.953-10.063-6.812c-2.904-.141-7.618.857-10.063 6.812c-.8 1.95-1.2 4.494-1.406 7.563");
}

.tip65z0am {
  stop-color: var(--svg-color--6c53a3, #6C53A3);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.tyoz-v6go {
  stop-color: var(--svg-color--cd2172, #CD2172);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u05m0u9vr {
  stop-color: var(--svg-color--ae495e, #AE495E);
  stop-opacity: 0;
}

.u7mpgeuwq {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.281 8.513l-.029-.631c-.01-.764-.642-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.367c-.257-.97.67-1.713 1.655-1.522c.974.189 2.082.517 2.902 1.052c1.745 1.138 1.44 3.188.521 4.154");
}

.ubi3zzb9f {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.686 10.147l-.531 1.839c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.645-.407-.765 0");
}

.uc4vypayb {
  stop-color: var(--svg-color--8371ae, #8371AE);
}

.uhjz0cbil {
  stop-color: var(--svg-color--e62f68, #E62F68);
  stop-opacity: 0;
}

.uif5em7ve {
  d: path("M11.244 13.627a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.117-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.513-3.342 3.38c0 1.86.116 3.69.238 5.556");
}

.ujur1qtze {
  stop-color: var(--svg-color--db2a69, #DB2A69);
}

.ult9otb7c {
  d: path("M13.971 15.075a2.097 2.097 0 0 1 4.195 0v1.547c0 1.371-.94 2.098-2.097 2.098c-1.159 0-2.098-.696-2.098-2.097z");
}

.um4v3ch7x {
  fill: var(--svg-color--230e12, #230E12);
  d: path("m9.897 8.202l3.235 4.805a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.152c.08-.24.253-.576.388-.576c.154 0 .313.336.393.576a.4.4 0 0 0 .085.152l1.45 1.656a.617.617 0 0 0 .975-.06l3.235-4.806c.174-.258-.057-.56-.354-.466l-4.821 1.51a.5.5 0 0 0-.278.25c-.178.341-.476.514-.685.52c-.21-.006-.503-.179-.68-.52a.5.5 0 0 0-.278-.25l-4.821-1.51c-.298-.093-.529.208-.354.466");
}

.ungg6q-mb {
  stop-color: var(--svg-color--e7547f, #E7547F);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uq-m7pb0g {
  stop-color: var(--svg-color--573a88, #573A88);
}

.uu75qbzsz {
  fill: var(--svg-color--290118, #290118);
  d: path("M17.75 12.648c-.614.807-1.368.893-1.872.924c-.085.006-.12.105-.051.154c.377.27.857.293 1.342.09c.51-.213.733-.703.747-1.123c.003-.091-.11-.118-.165-.045");
}

.uvjko3k9x {
  d: path("M6.984 15.957c0 .22.249.315.555.315s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.v_v98qact {
  stop-color: var(--svg-color--230f39, #230F39);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vat9yt_ey {
  stop-color: var(--svg-color--614290, #614290);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vipjwwaoi {
  d: path("M23.252 18.142v11.843h4.274c-.206-3.069-.606-5.613-1.406-7.563c-.773-1.881-1.771-3.268-2.868-4.28");
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w9h1cgbuc {
  stop-color: var(--svg-color--3f3b2c, #3F3B2C);
}

.w9ixvabyl {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.261 5.264h-2.08a.483.483 0 1 1 .076-.961c.54.086 1.257.205 1.737.325c1.086.269 1.386.797 1.47 1.174a1.51 1.51 0 0 0-1.203-.538");
}

.wnzu6gyxf {
  cx: 16.063px;
  cy: 23.995px;
  r: 1.732px;
}

.wphxpcbvw {
  d: path("M20.923 4.22c.515.176.976.535 1.268 1.05a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.75 1.75 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418h-1.272c-1.846 0-3.342 1.513-3.342 3.38l.03 1.537a1.7 1.7 0 0 0-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.143-2.446a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.193 0a2.4 2.4 0 0 1 .913-.187c.843 0 1.58.456 1.989 1.131c.307.51.79.88 1.352 1.073");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xkd2ooi4v {
  stop-color: var(--svg-color--322f37, #322F37);
  stop-opacity: 0;
}

.xrr4vbcci {
  stop-color: var(--svg-color--7560a8, #7560A8);
  stop-opacity: 0;
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

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zblf_actk {
  stop-color: var(--svg-color--372543, #372543);
}

.zhe9zhdzx {
  stop-color: var(--svg-color--7a4c9c, #7A4C9C);
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zojxemb8i {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
  stop-opacity: 0;
}

.zrw7q7-1s {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.75 12.648c-.614.807-1.368.893-1.872.924c-.085.006-.12.105-.051.154c.377.27.857.293 1.342.09c.51-.213.733-.703.747-1.123c.003-.091-.11-.118-.165-.045Z");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zxe--8tbm {
  stop-color: var(--svg-color--50387f, #50387F);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
