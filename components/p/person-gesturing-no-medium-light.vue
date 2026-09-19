<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#imK7ZTc)" class="e5ucantjx"/><path fill="url(#iRXStQc)" class="e5ucantjx"/><path fill="url(#ieyDjZd)" class="a6yq75bbi"/><path fill="url(#iSPe7hb)" class="a6yq75bbi"/><g filter="url(#iG8p1Eb)"><path fill="url(#icredyc)" class="omftgvbac"/></g><path fill="url(#iM8Crxc)" class="omftgvbac"/><path fill="url(#iSxXk3c)" class="omftgvbac"/><path fill="url(#i3g6Nib)" class="omftgvbac"/><path fill="url(#iAfb2Yb)" class="omftgvbac"/><path fill="url(#iZ0Vn7b)" class="omftgvbac"/><path fill="url(#ijtF0pb)" class="omftgvbac"/><path fill="url(#iIMji1Z)" class="omftgvbac"/><path fill="url(#i0vcxoP)" class="omftgvbac"/><g filter="url(#iWqcZee)"><path class="o606u1sth"/></g><g filter="url(#ivev2be)"><path fill="url(#i2JDRbe)" class="e-zb_sb0t"/><path fill="url(#i6NYcxc)" class="e-zb_sb0t"/><path fill="url(#iIlz7pe)" class="e-zb_sb0t"/><path fill="url(#iaXyHeb)" class="e-zb_sb0t"/></g><g filter="url(#iYhS28c)"><path fill="url(#iVKAe1d)" class="bnbr98b0b"/><path fill="url(#izACv4c)" class="bnbr98b0b"/><path fill="url(#irFra1b)" class="bnbr98b0b"/><path fill="url(#idg5H9b)" class="bnbr98b0b"/><path fill="url(#ieSdkDb)" class="bnbr98b0b"/></g><g filter="url(#iqiINVh)"><path fill="url(#i2r0Ise)" class="rbbulnz3l"/><path fill="url(#iRuxGte)" class="rbbulnz3l"/></g><g filter="url(#iEAZLue)"><path fill="url(#ioRRHEc)" class="t-faq4izi"/><path fill="url(#ilCAiDb)" class="t-faq4izi"/><path fill="url(#iccOKmd)" class="t-faq4izi"/><path fill="url(#iMFDkcc)" class="t-faq4izi"/><path fill="url(#i421Ijb)" class="t-faq4izi"/><path fill="url(#i99LYoD)" class="t-faq4izi"/></g><path class="utrmehb1k"/><path fill="url(#iPjnENe)" class="cswzjcx6u"/><path class="iitgd8bac"/><g filter="url(#iBW8vcb)"><path class="dodqfog5q"/><path fill="url(#i9QUMfK)" class="nsn8oes0z"/></g><g filter="url(#ih0FObb)"><path fill="url(#iKnUjve)" class="t0_upib5g"/></g><path class="ub8ckabiz"/><path fill="url(#iOPziAb)" class="fqu12ubrd"/><path class="ebo5c_0lf"/><g filter="url(#i9RedKe)"><path fill="url(#i7aVE8b)" class="q5hvggldb"/></g><g filter="url(#iJQwKAc)"><ellipse transform="rotate(-27.914 12.844 12.236)" class="z-qcyfbze"/><ellipse fill="url(#i8Ldsle)" transform="rotate(-27.914 12.844 12.236)" class="a3xscqbym"/></g><path fill="url(#iM9KVjd)" class="nl8aomm7e"/><path fill="url(#iE2Yr1d)" class="nl8aomm7e"/><path fill="url(#iGmqald)" class="nl8aomm7e"/><path fill="url(#iUYUrkb)" class="l3e-mtbcj"/><path fill="url(#i5MqYhe)" class="l3e-mtbcj"/><g filter="url(#ia2W4Ce)"><path class="bn9h6fb9e"/></g><g filter="url(#i9oVlFd)"><path class="qa6kmbxxy"/></g><g filter="url(#iBY7QGK)"><path class="f-wt1y5yx"/></g><g filter="url(#iKUqz1c)"><path class="abx797buj"/></g><g filter="url(#iGq1ize)"><path stroke="url(#iu0VbQc)" class="gspwrdz1o"/></g><g filter="url(#ijOw5Eb)"><path stroke="url(#ib7pKWd)" class="wq0eljlkx"/></g><path class="fq1gvacsb"/><path class="w73iq3bud"/><path fill="url(#iY2ScGe)" class="akki1obxr"/><path fill="url(#inirSwb)" class="akki1obxr"/><path fill="url(#ikeLGbe)" class="u4cp3820t"/><path fill="url(#ihqOLGc)" class="cuomu7bqz"/><path fill="url(#iRbdh4d)" class="cuomu7bqz"/><path fill="url(#i16tupc)" class="cuomu7bqz"/><path fill="url(#isBeo5c)" class="cuomu7bqz"/><path fill="url(#izAvOPb)" class="cuomu7bqz"/><path fill="url(#igdf08b)" class="cuomu7bqz"/><path fill="url(#iiwVwQd)" class="twmiqpbxq"/><path fill="url(#iDDcgbe)" class="v3eonib4h"/><path fill="url(#iwGAPQd)" class="v3eonib4h"/><path fill="url(#ixh7Cge)" class="v3eonib4h"/><path fill="url(#iIC8WJd)" class="e3jco7qba"/><path fill="url(#iPziSyb)" class="e3jco7qba"/><path fill="url(#itpf4Od)" class="e3jco7qba"/><path fill="url(#iUk9wee)" class="i4fzwzbpd"/><path fill="url(#i5quqyh)" class="i4fzwzbpd"/><path fill="url(#iVFkqsd)" class="vzu9-mfnh"/><path fill="url(#iISaF1c)" class="vzu9-mfnh"/><path fill="url(#iB3tmAb)" class="vzu9-mfnh"/><path fill="url(#iZ0Eaad)" class="vzu9-mfnh"/><g filter="url(#iP62Lxb)"><path fill="url(#i5eHVJb)" class="cw3sn1brq"/><path fill="url(#iJlijyt)" class="cw3sn1brq"/></g><path fill="url(#iq5d0OS)" class="cw3sn1brq"/><g filter="url(#ilpz9hb)"><path fill="url(#isTi4te)" class="j_0xl5h8m"/></g><defs><radialGradient id="imK7ZTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.99022 4.06854 -4.83311 -1.1763 23.12 14.564)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="g_go8-i7v"/><stop offset="1" class="t6hj3nbht"/></radialGradient><radialGradient id="iRXStQc" cx="0" cy="0" r="1" gradientTransform="rotate(40.237 -9.47 37.906)scale(.54988 .70819)" gradientUnits="userSpaceOnUse"><stop class="ic7m27p6x"/><stop offset="1" class="a8f8wslpf"/></radialGradient><radialGradient id="ieyDjZd" cx="0" cy="0" r="1" gradientTransform="matrix(1.63603 3.44427 -1.56558 .74365 8.87 14.714)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iSPe7hb" cx="0" cy="0" r="1" gradientTransform="matrix(.23028 1.533 -1.34475 .202 9.899 14.452)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="icredyc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.71417 0 0 -11.8773 19.601 13.355)" gradientUnits="userSpaceOnUse"><stop class="c19sz__ej"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iSxXk3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46795 16.6485 -13.78691 -1.21563 18.026 5.76)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="zgchiqbcj"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="i3g6Nib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.72213 2.13114 0 19.138 11.916)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iAfb2Yb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07457 -1.4171 1.54215 -.08115 13.12 11.74)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iZ0Vn7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.54992 0 0 7.8779 9.727 13.849)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="ijtF0pb" cx="0" cy="0" r="1" gradientTransform="matrix(3.35817 -4.69282 1.06293 .76063 8.478 9.5)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iIMji1Z" cx="0" cy="0" r="1" gradientTransform="rotate(-103.259 15.256 3.039)scale(13.5154 14.8876)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="i0vcxoP" cx="0" cy="0" r="1" gradientTransform="matrix(2.62626 .92565 -.5553 1.57547 18.51 6.444)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="izACv4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.66544 8.26625 0 9.279 11.323)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="irFra1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.66544 8.26625 0 22.238 11.323)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="idg5H9b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.17618 -1.59297 .84836 -2.2241 21.269 3.262)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="ieSdkDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.16245 1.89434 -4.3864 2.69168 14.832 1.217)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="i2r0Ise" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.892 2.962)scale(5.19777 1.44666)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iRuxGte" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.84 -3.592)scale(7.74003 8.57516)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="ioRRHEc" cx="0" cy="0" r="1" gradientTransform="matrix(4.34839 1.0285 -.57521 2.43192 20.645 4.56)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="ilCAiDb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 14.307 -1.266)scale(5.49916 3.06684)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="iccOKmd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67906 -2.82842 2.02587 -1.20264 21.786 10.088)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iMFDkcc" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 10.815 3.515)scale(6.33753 6.85111)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="i421Ijb" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 8.643 9.683)scale(.51535 2.35612)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="i99LYoD" cx="0" cy="0" r="1" gradientTransform="matrix(-2.56164 4.822 -12.43459 -6.60574 20.425 3.193)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iPjnENe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04198 -1.65739 0 18.798 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i9QUMfK" cx="0" cy="0" r="1" gradientTransform="matrix(-.29785 -.38382 .52843 -.41007 18.504 12.467)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOPziAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04204 -1.65748 0 13.193 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8Ldsle" cx="0" cy="0" r="1" gradientTransform="matrix(-.00994 -.63455 .76277 -.01194 12.825 12.642)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iE2Yr1d" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 2.921 20.555)scale(2.99201 2.85461)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iGmqald" cx="0" cy="0" r="1" gradientTransform="matrix(1.01175 -1.38847 1.16382 .84805 22.388 12.895)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i5MqYhe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15123 -.31506 .31015 -2.11775 9.682 13.019)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="iY2ScGe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.445)" gradientUnits="userSpaceOnUse"><stop class="prd44wbso"/><stop offset="1" class="c5khawelw"/></radialGradient><radialGradient id="inirSwb" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.227)" gradientUnits="userSpaceOnUse"><stop class="u1hhhxbfd"/><stop offset="1" class="cl_cdxbgs"/></radialGradient><radialGradient id="ikeLGbe" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 1.25 -2.6929 5.58776 8.406 17.32)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="sy-f5ccgl"/><stop offset="1" class="i26rr_0fw"/></radialGradient><radialGradient id="ihqOLGc" cx="0" cy="0" r="1" gradientTransform="matrix(17.51082 8.75543 -2.15289 4.30577 13.551 19.209)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="v3bwo4btz"/><stop offset="1" class="kd1_xhb_o"/></radialGradient><radialGradient id="iRbdh4d" cx="0" cy="0" r="1" gradientTransform="rotate(159.944 11.543 15.187)scale(2.90693 2.17455)" gradientUnits="userSpaceOnUse"><stop class="cq9p23brg"/><stop offset="1" class="cwmsguygo"/></radialGradient><radialGradient id="i16tupc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11963 5.31578 -8.32746 -1.75396 14.245 17.692)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="w58mn6r_g"/><stop offset="1" class="xrn2z6b6u"/></radialGradient><radialGradient id="izAvOPb" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.455 -3.07)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="mq0gl8bsz"/><stop offset="1" class="w-vsz3bnm"/></radialGradient><radialGradient id="iiwVwQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 .6475 -1.4343 -3.32276 24.094 18.195)" gradientUnits="userSpaceOnUse"><stop class="qxiqgebpn"/><stop offset="1" class="m_8hwoksz"/></radialGradient><radialGradient id="iDDcgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.883)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="jbd_cz55y"/><stop offset="1" class="m7o64xbbx"/></radialGradient><radialGradient id="iIC8WJd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.469)" gradientUnits="userSpaceOnUse"><stop class="aa7vwbb4q"/><stop offset=".615" class="b51u270in"/></radialGradient><radialGradient id="iUk9wee" cx="0" cy="0" r="1" gradientTransform="matrix(1.74664 .85478 -1.17534 2.40165 3.176 17.648)" gradientUnits="userSpaceOnUse"><stop class="s6hgzbzaq"/><stop offset=".697" class="tqvfhbbxd"/></radialGradient><radialGradient id="i5quqyh" cx="0" cy="0" r="1" gradientTransform="rotate(162.607 1.083 8.97)scale(.89785 1.70016)" gradientUnits="userSpaceOnUse"><stop class="luld7ndnd"/><stop offset="1" class="dsgye7-db"/></radialGradient><radialGradient id="iVFkqsd" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.294 6.356)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ps47ry3bo"/><stop offset="1" class="y_wsbk4sp"/></radialGradient><radialGradient id="iISaF1c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 .59376 -.2045 -.35517 30.161 13.225)" gradientUnits="userSpaceOnUse"><stop class="l94zn1bjc"/><stop offset="1" class="wncwu8b0a"/></radialGradient><radialGradient id="iZ0Eaad" cx="0" cy="0" r="1" gradientTransform="matrix(2.96386 -2.56198 2.74355 3.17391 24.182 21.076)" gradientUnits="userSpaceOnUse"><stop class="idon908fh"/><stop offset="1" class="f2po-obrk"/></radialGradient><radialGradient id="iJlijyt" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.288)" gradientUnits="userSpaceOnUse"><stop class="f5tmiabas"/><stop offset="1" class="uo2he_6_t"/></radialGradient><radialGradient id="iq5d0OS" cx="0" cy="0" r="1" gradientTransform="matrix(1.00475 -.26214 .85754 3.28688 4.382 18.192)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="x5w5cvbwy"/><stop offset="1" class="ug66v3bff"/></radialGradient><linearGradient id="iM8Crxc" x1="22.619" x2="20.288" y1="15.52" y2="15.376" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="i2JDRbe" x1="15.995" x2="17.093" y1="14.441" y2="14.441" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="i6NYcxc" x1="14.617" x2="15.997" y1="14.241" y2="14.317" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iIlz7pe" x1="15.995" x2="15.995" y1="14.953" y2="16.047" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iaXyHeb" x1="15.995" x2="15.995" y1="12.066" y2="12.605" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iVKAe1d" x1="22.884" x2="9.881" y1="6.082" y2="6.082" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iKnUjve" x1="19.798" x2="19.394" y1="12.429" y2="12.678" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7aVE8b" x1="14.148" x2="13.745" y1="12.428" y2="12.677" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iM9KVjd" x1="24.261" x2="22.711" y1="12.282" y2="15.077" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iUYUrkb" x1="8.482" x2="10.355" y1="13.182" y2="13.019" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="iu0VbQc" x1="13.921" x2="11.175" y1="9.208" y2="9.928" gradientUnits="userSpaceOnUse"><stop offset=".333" class="t-ltb0bxu"/><stop offset="1" class="mycwy9ulq"/></linearGradient><linearGradient id="ib7pKWd" x1="18.178" x2="20.924" y1="9.208" y2="9.928" gradientUnits="userSpaceOnUse"><stop offset=".333" class="t-ltb0bxu"/><stop offset="1" class="mycwy9ulq"/></linearGradient><linearGradient id="isBeo5c" x1="9.156" x2="10.344" y1="18.508" y2="18.883" gradientUnits="userSpaceOnUse"><stop class="psrrqcksv"/><stop offset="1" class="rbkr51v-c"/></linearGradient><linearGradient id="igdf08b" x1="17.406" x2="17.906" y1="26.977" y2="25.758" gradientUnits="userSpaceOnUse"><stop class="gd1of5hxe"/><stop offset="1" class="v1z821b6o"/></linearGradient><linearGradient id="iwGAPQd" x1="14.83" x2="14.461" y1="26.816" y2="25.927" gradientUnits="userSpaceOnUse"><stop class="q9mg64b4e"/><stop offset="1" class="vzmhuwavr"/></linearGradient><linearGradient id="ixh7Cge" x1="22.827" x2="21.613" y1="18.819" y2="19.382" gradientUnits="userSpaceOnUse"><stop class="smo9u60ba"/><stop offset="1" class="ktas3sbvn"/></linearGradient><linearGradient id="iPziSyb" x1="27.52" x2="26.84" y1="19.664" y2="18.102" gradientUnits="userSpaceOnUse"><stop class="wvesq7bsq"/><stop offset="1" class="rgj_ccorv"/></linearGradient><linearGradient id="itpf4Od" x1="26.75" x2="27.494" y1="17.398" y2="18.158" gradientUnits="userSpaceOnUse"><stop offset=".353" class="s1zw3qoay"/><stop offset="1" class="sg0r51lje"/></linearGradient><linearGradient id="iB3tmAb" x1="25.489" x2="25.997" y1="14.289" y2="15.189" gradientUnits="userSpaceOnUse"><stop class="v9kdkd3dw"/><stop offset="1" class="izl0csmmw"/></linearGradient><linearGradient id="i5eHVJb" x1="8" x2="5.5" y1="15.758" y2="19.524" gradientUnits="userSpaceOnUse"><stop offset=".206" class="wm1rnnuue"/><stop offset="1" class="zcorn7o9q"/></linearGradient><linearGradient id="isTi4te" x1="29.179" x2="24.036" y1="14.953" y2="17.82" gradientUnits="userSpaceOnUse"><stop class="wyj2c0peu"/><stop offset="1" class="tx-xnn8qh"/></linearGradient><filter id="iG8p1Eb" width="13.876" height="16.05" x="9.492" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24803"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24803" result="effect2_innerShadow_3987_24803"/></filter><filter id="iWqcZee" width="4.411" height="5.725" x="13.524" y="11.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".5"/></filter><filter id="ivev2be" width="2.611" height="3.925" x="14.69" y="11.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".05"/></filter><filter id="iYhS28c" width="16.532" height="10.59" x="7.729" y="1.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24803"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24803" result="effect2_innerShadow_3987_24803"/></filter><filter id="iqiINVh" width="8.814" height="8.053" x="8.006" y="2.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".25"/></filter><filter id="iEAZLue" width="8.596" height="7.796" x="15.543" y="3.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".25"/></filter><filter id="iBW8vcb" width=".954" height=".837" x="17.883" y="11.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".05"/></filter><filter id="ih0FObb" width="1.033" height="1.061" x="18.99" y="11.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".1"/></filter><filter id="i9RedKe" width="1.153" height="1.222" x="13.284" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".1"/></filter><filter id="iJQwKAc" width="1.116" height=".848" x="12.286" y="11.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".05"/></filter><filter id="ia2W4Ce" width="1.565" height="2.914" x="8.318" y="11.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".125"/></filter><filter id="i9oVlFd" width="1.716" height="2.944" x="22.117" y="11.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".125"/></filter><filter id="iBY7QGK" width="2.884" height="1.34" x="11.376" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.282353 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24803"/></filter><filter id="iKUqz1c" width="2.884" height="1.34" x="17.939" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.282353 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24803"/></filter><filter id="iGq1ize" width="2.717" height="1.234" x="11.486" y="8.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".125"/></filter><filter id="ijOw5Eb" width="2.717" height="1.234" x="17.896" y="8.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".125"/></filter><filter id="iP62Lxb" width="7.3" height="8.016" x="2" y="12.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24803"/></filter><filter id="ilpz9hb" width="5.538" height="5.423" x="24.159" y="13.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24803" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-no-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a3xscqbym {
  cx: 12.844px;
  cy: 12.236px;
  rx: 0.5px;
  ry: 0.253px;
}

.a6yq75bbi {
  d: path("M9.752 14.96a2.1 2.1 0 0 1-1.162-.396v1.195a2.79 2.79 0 0 0 1.722 2.593a5.3 5.3 0 0 1-.444-1.515z");
}

.a8f8wslpf {
  stop-color: var(--svg-color--e6b489, #E6B489);
  stop-opacity: 0;
}

.aa7vwbb4q {
  stop-color: var(--svg-color--edbfa2, #EDBFA2);
}

.abx797buj {
  fill: var(--svg-color--935d2c, #935D2C);
  d: path("M20.711 9.94a.35.35 0 0 0-.25-.426l-2.086-.542a.349.349 0 1 0-.175.675l2.086.542a.35.35 0 0 0 .425-.249");
}

.akki1obxr {
  d: path("M25.5 30.008h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.b51u270in {
  stop-color: var(--svg-color--dead8c, #DEAD8C);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bn9h6fb9e {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M9.526 11.817a1.228 1.228 0 0 0 .107 2.413q-.069-1.206-.107-2.413");
}

.bnbr98b0b {
  d: path("M22.23 4.823c.66.228 1.253.69 1.628 1.35a3.04 3.04 0 0 1-.136 3.245a2 2 0 0 0-.348 1.123v1.526a2.2 2.2 0 0 0-.856-.345l.1-2.063a1.86 1.86 0 0 0-1.77-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34l.028 1.976c-.326.048-.655.155-.913.336v-1.541c0-.4-.123-.792-.348-1.123a3.07 3.07 0 0 1-.184-3.141a3 3 0 0 1 1.67-1.447a3.44 3.44 0 0 0 1.777-1.426a2.99 2.99 0 0 1 2.534-1.412c.416 0 .81.09 1.179.241c.49.214 1.042.214 1.532 0a3 3 0 0 1 1.172-.24c1.083 0 2.03.585 2.554 1.453a3.24 3.24 0 0 0 1.737 1.377");
}

.c19sz__ej {
  stop-color: var(--svg-color--ffc195, #FFC195);
}

.c5khawelw {
  stop-color: var(--svg-color--ff9540, #FF9540);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl_cdxbgs {
  stop-color: var(--svg-color--e2632d, #E2632D);
  stop-opacity: 0;
}

.cq9p23brg {
  stop-color: var(--svg-color--ff7d48, #FF7D48);
}

.cswzjcx6u {
  d: path("M18.8 11.747a1.146 1.146 0 0 1 1.105 1.448H17.69a1.15 1.15 0 0 1 1.11-1.448");
}

.cuomu7bqz {
  d: path("m11.56 16.106l15.407 7.178a3.53 3.53 0 0 1 1.7 4.687a3.52 3.52 0 0 1-4.679 1.704L8.581 22.487a1 1 0 0 1-.483-1.34l2.123-4.567a1.004 1.004 0 0 1 1.339-.474");
}

.cw3sn1brq {
  d: path("m9 16.078l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.cwmsguygo {
  stop-color: var(--svg-color--ff7d48, #FF7D48);
  stop-opacity: 0;
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dodqfog5q {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dsgye7-db {
  stop-color: var(--svg-color--bb7753, #BB7753);
  stop-opacity: 0;
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e-zb_sb0t {
  d: path("m15.504 12.458l-.683 2.361c-.139.486.196.972.67.972H16.5c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.829-.524-.982 0");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3jco7qba {
  d: path("M24.75 19.811a.885.885 0 0 1 .35-1.203l2.609-1.428a.899.899 0 1 1 .856 1.581l-2.621 1.404a.885.885 0 0 1-1.194-.354");
}

.e5ucantjx {
  d: path("M22.239 14.96c.43-.014.833-.16 1.161-.396v1.195a2.79 2.79 0 0 1-1.722 2.593c.219-.465.37-.973.444-1.515z");
}

.ebo5c_0lf {
  fill: var(--svg-color--000, #000);
  d: path("M13.847 12.893a.654.654 0 0 0-.657-.657a.654.654 0 0 0-.583.959h1.162a.65.65 0 0 0 .078-.302");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.f-wt1y5yx {
  fill: var(--svg-color--935d2c, #935D2C);
  d: path("M11.388 9.94a.35.35 0 0 1 .25-.426l2.086-.542a.349.349 0 1 1 .175.675l-2.086.542a.35.35 0 0 1-.425-.249");
}

.f2po-obrk {
  stop-color: var(--svg-color--cb7c77, #CB7C77);
  stop-opacity: 0;
}

.f5tmiabas {
  stop-color: var(--svg-color--eebca0, #EEBCA0);
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fq1gvacsb {
  fill: var(--svg-color--88004c, #88004C);
  d: path("M15.989 19.458c.791 0 1.433-.688 1.433-1.537c0-.85-.642-1.538-1.433-1.538s-1.433.688-1.433 1.538c0 .849.642 1.537 1.433 1.537");
}

.fqu12ubrd {
  d: path("M13.19 11.747a1.146 1.146 0 0 0-1.104 1.448H14.3q.04-.147.041-.302a1.154 1.154 0 0 0-1.15-1.147");
}

.ft5dv1b6b {
  fill: none;
}

.g_go8-i7v {
  stop-color: var(--svg-color--ffdcaf, #FFDCAF);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gd1of5hxe {
  stop-color: var(--svg-color--eb4e66, #EB4E66);
}

.gspwrdz1o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.836 9.76l2.017-.534");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i26rr_0fw {
  stop-color: var(--svg-color--b9321e, #B9321E);
}

.i4fzwzbpd {
  d: path("M7.152 19.747c.236-.43.228-.904-.201-1.14L4.342 17.18a.899.899 0 1 0-.856 1.581l2.622 1.404c.427.229.81.007 1.044-.418");
}

.ic7m27p6x {
  stop-color: var(--svg-color--e6b489, #E6B489);
}

.idon908fh {
  stop-color: var(--svg-color--cb7c77, #CB7C77);
}

.iitgd8bac {
  fill: var(--svg-color--000, #000);
  d: path("M18.144 12.893c0-.365.291-.657.656-.657a.654.654 0 0 1 .584.959h-1.162a.6.6 0 0 1-.078-.302");
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.izl0csmmw {
  stop-color: var(--svg-color--c6916f, #C6916F);
  stop-opacity: 0;
}

.j_0xl5h8m {
  d: path("M26.653 15.73c.527-.847 1.795-1.665 2.462-1.988a.13.13 0 0 1 .152.034a.132.132 0 0 1-.033.196c-2.06 1.273-1.875 1.785-2.645 3.097c-.355.604-1.177 1.112-1.556 1.284l-.474-.899c.53-.28 1.462-.711 2.094-1.725");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.kd1_xhb_o {
  stop-color: var(--svg-color--ff4c31, #FF4C31);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.ktas3sbvn {
  stop-color: var(--svg-color--ffa842, #FFA842);
  stop-opacity: 0;
}

.l3e-mtbcj {
  d: path("M9.513 10.96a2.08 2.08 0 0 0-1.784 2.053c0 1.103.864 2.005 1.953 2.063a101 101 0 0 1-.17-4.115");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l94zn1bjc {
  stop-color: var(--svg-color--f2c4a6, #F2C4A6);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.luld7ndnd {
  stop-color: var(--svg-color--bb7753, #BB7753);
}

.m_8hwoksz {
  stop-color: var(--svg-color--f54617, #F54617);
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.m7o64xbbx {
  stop-color: var(--svg-color--ff4923, #FF4923);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mq0gl8bsz {
  stop-color: var(--svg-color--e4764e, #E4764E);
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mycwy9ulq {
  stop-color: var(--svg-color--a26e44, #A26E44);
  stop-opacity: 0;
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.nl8aomm7e {
  d: path("M22.316 15.077q.129-2.05.237-4.099a2.067 2.067 0 0 1-.237 4.099");
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nsn8oes0z {
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.o606u1sth {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.37 12.689l-.815 2.36c-.139.486.196.972.67.972h1.009c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.696-.524-.85 0");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.omftgvbac {
  d: path("M9.798 16.906a5.03 5.03 0 0 0 4.99 4.374h2.424a5.03 5.03 0 0 0 4.99-4.374c.152-2.42.304-4.829.417-7.247a1.86 1.86 0 0 0-1.771-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34c0 2.39.15 4.74.306 7.136");
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prd44wbso {
  stop-color: var(--svg-color--ff9540, #FF9540);
}

.ps47ry3bo {
  stop-color: var(--svg-color--e6b396, #E6B396);
}

.psrrqcksv {
  stop-color: var(--svg-color--ff730a, #FF730A);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q5hvggldb {
  d: path("M14.237 12.758c0-.37-.3-.617-.382-.692l-.37.358l.227.464z");
}

.q9mg64b4e {
  stop-color: var(--svg-color--f35e74, #F35E74);
}

.qa6kmbxxy {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M22.367 14.24q.076-1.221.142-2.444a1.227 1.227 0 0 1-.142 2.445");
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxiqgebpn {
  stop-color: var(--svg-color--ff6732, #FF6732);
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.rbbulnz3l {
  d: path("M16.294 6.143a3 3 0 0 1-.085-.176a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34v.353c-.436-.333-.986-1.033-.986-2.168c0-1.376 1.004-2.072 1.645-2.516c.18-.125.332-.23.425-.325l.128-.135c.448-.476 1.248-1.324 2.645-1.695a7.2 7.2 0 0 1 2.167-.203c.472.026.805.434.805.907v2.137z");
}

.rbkr51v-c {
  stop-color: var(--svg-color--ff730a, #FF730A);
  stop-opacity: 0;
}

.rgj_ccorv {
  stop-color: var(--svg-color--ca8684, #CA8684);
  stop-opacity: 0;
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.s1zw3qoay {
  stop-color: var(--svg-color--d0976d, #D0976D);
}

.s6hgzbzaq {
  stop-color: var(--svg-color--c68c71, #C68C71);
}

.sg0r51lje {
  stop-color: var(--svg-color--d0976d, #D0976D);
  stop-opacity: 0;
}

.smo9u60ba {
  stop-color: var(--svg-color--ffa842, #FFA842);
}

.sy-f5ccgl {
  stop-color: var(--svg-color--e76b2f, #E76B2F);
}

.t-faq4izi {
  d: path("m22.69 10.474l-.038-.811c-.014-.98-.824-1.79-1.805-1.83H19.05a3.11 3.11 0 0 1-2.728-1.619s-.16-.372-.258-.96c-.165-.989.75-1.717 1.74-1.554c1.354.222 3.024.66 4.218 1.438c2.24 1.462 1.848 4.095.669 5.336");
}

.t-ltb0bxu {
  stop-color: var(--svg-color--a26e44, #A26E44);
}

.t0_upib5g {
  d: path("M19.823 12.744a1.1 1.1 0 0 0-.298-.596l-.335.367l.151.294z");
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t6hj3nbht {
  stop-color: var(--svg-color--d89e98, #D89E98);
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tqvfhbbxd {
  stop-color: var(--svg-color--bd756f, #BD756F);
}

.twmiqpbxq {
  d: path("m25.19 20.578l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.tx-xnn8qh {
  stop-color: var(--svg-color--f1c2a5, #F1C2A5);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u1hhhxbfd {
  stop-color: var(--svg-color--e2632d, #E2632D);
}

.u4cp3820t {
  d: path("m6.81 20.578l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.ub8ckabiz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.924 11.398c-.838 0-1.547.578-1.74 1.36a.352.352 0 0 0 .344.437h2.866a.296.296 0 0 0 .291-.35a1.8 1.8 0 0 0-1.76-1.447");
}

.ug66v3bff {
  stop-color: var(--svg-color--d59883, #D59883);
  stop-opacity: 0;
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uo2he_6_t {
  stop-color: var(--svg-color--eebca0, #EEBCA0);
  stop-opacity: 0;
}

.utrmehb1k {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.066 11.398c.839 0 1.547.578 1.74 1.36a.352.352 0 0 1-.344.437h-2.865a.296.296 0 0 1-.292-.35a1.795 1.795 0 0 1 1.76-1.447");
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v1z821b6o {
  stop-color: var(--svg-color--eb4e66, #EB4E66);
  stop-opacity: 0;
}

.v3bwo4btz {
  stop-color: var(--svg-color--ff7132, #FF7132);
}

.v3eonib4h {
  d: path("M20.44 16.106L5.033 23.28a3.53 3.53 0 0 0-1.7 4.69a3.516 3.516 0 0 0 4.679 1.705l15.407-7.182c.503-.232.724-.837.483-1.342l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.v9kdkd3dw {
  stop-color: var(--svg-color--c6916f, #C6916F);
}

.vzmhuwavr {
  stop-color: var(--svg-color--f35e74, #F35E74);
  stop-opacity: 0;
}

.vzu9-mfnh {
  d: path("m23 16.078l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.w-vsz3bnm {
  stop-color: var(--svg-color--e4764e, #E4764E);
  stop-opacity: 0;
}

.w58mn6r_g {
  stop-color: var(--svg-color--ff9a32, #FF9A32);
}

.w73iq3bud {
  fill: var(--svg-color--f53b19, #F53B19);
  d: path("M25.5 30.008h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wm1rnnuue {
  stop-color: var(--svg-color--f1bf99, #F1BF99);
}

.wncwu8b0a {
  stop-color: var(--svg-color--f2c4a6, #F2C4A6);
  stop-opacity: 0;
}

.wq0eljlkx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.263 9.76l-2.017-.534");
}

.wvesq7bsq {
  stop-color: var(--svg-color--ca8684, #CA8684);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wyj2c0peu {
  stop-color: var(--svg-color--f1c2a5, #F1C2A5);
}

.x5w5cvbwy {
  stop-color: var(--svg-color--d59883, #D59883);
}

.xrn2z6b6u {
  stop-color: var(--svg-color--ff8c11, #FF8C11);
  stop-opacity: 0;
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y_wsbk4sp {
  stop-color: var(--svg-color--daa884, #DAA884);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z-qcyfbze {
  cx: 12.844px;
  cy: 12.236px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.5px;
  ry: 0.253px;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zcorn7o9q {
  stop-color: var(--svg-color--d1927f, #D1927F);
}

.zgchiqbcj {
  stop-color: var(--svg-color--b36e91, #B36E91);
  stop-opacity: 0;
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

</style>
