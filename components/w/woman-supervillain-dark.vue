<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVaeJic)"><path fill="url(#ixgle3Z)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#iHr0NPe)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#id409pc)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#iVJBMpe)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#iUo6sAb)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#i1dG9jd)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#ip31LzE)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#iSjM0kc)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#iI5gFpX)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#iEeAgQe)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#iwcqehc)" clip-rule="evenodd" class="iql2qqbdo"/><path fill="url(#iDEqmqX)" clip-rule="evenodd" class="iql2qqbdo"/></g><g filter="url(#i5jYz6c)"><path fill="url(#icQ93yd)" class="rogbl960m"/><path fill="url(#iViecEe)" class="rogbl960m"/></g><g filter="url(#isAPRYc)"><path fill="url(#iuhQLbe)" class="kb_-_jbav"/><path fill="url(#iCBdd2r)" class="kb_-_jbav"/></g><path fill="url(#i4ZC7AD)" class="palvvabur"/><path fill="url(#iIZwoXd)" class="palvvabur"/><path fill="url(#i2bcbpT)" class="palvvabur"/><path fill="url(#iSLEYkc)" class="palvvabur"/><path fill="url(#iwiC3Rb)" class="palvvabur"/><path fill="url(#ivTuwAc)" class="palvvabur"/><path fill="url(#iznByOd)" class="palvvabur"/><path fill="url(#i6UFgvb)" class="palvvabur"/><path fill="url(#iqmInAc)" class="glmadebyq"/><path fill="url(#iggAQLd)" class="glmadebyq"/><path fill="url(#iMFFrKc)" class="glmadebyq"/><path fill="url(#iqdJ1qe)" class="glmadebyq"/><path fill="url(#iOR8MCd)" class="hszcn43qv"/><path fill="url(#iYk1gPc)" class="hszcn43qv"/><path fill="url(#i4r5cFb)" class="hszcn43qv"/><path fill="url(#i6kNpTb)" class="hszcn43qv"/><path fill="url(#i647Wqb)" class="q25wohb5n"/><path fill="url(#idjiMmb)" class="r3tvax9mc"/><path fill="url(#ijuf4Bc)" class="iitbw26oy"/><g filter="url(#i2YKI6b)"><path fill="url(#ivxRBQb)" class="ti1znzbde"/><path fill="url(#iHqKkcE)" class="ti1znzbde"/><path fill="url(#ilqqeDe)" class="ti1znzbde"/><path fill="url(#iOlUHde)" class="ti1znzbde"/><path fill="url(#iIizEnb)" class="ti1znzbde"/></g><path class="ljssbab8s"/><path fill="url(#inwurSa)" class="cpk5dlpmi"/><path fill="url(#i54JjGd)" class="cpk5dlpmi"/><path class="a0e13gbyz"/><path fill="url(#iQTKuMl)" class="nmjycpfuo"/><g filter="url(#ieJ99Md)"><path fill="url(#iz6CZrQ)" class="wx32uubmd"/><path fill="url(#iq4saGc)" class="wx32uubmd"/><path fill="url(#iBosmBc)" class="wx32uubmd"/><path fill="url(#iOB8XHb)" class="wx32uubmd"/><path fill="url(#id99MGz)" class="wx32uubmd"/><path fill="url(#iNoYEGc)" class="wx32uubmd"/></g><g filter="url(#iM70Lte)"><path fill="url(#iNpj7Rb)" class="o46ofwfzc"/></g><path fill="url(#i2IkSDc)" class="yl99ywbbx"/><path fill="url(#iIDccEc)" class="yl99ywbbx"/><path fill="url(#i6p2Yrb)" class="d5ey51fhz"/><path fill="url(#iR4LLzc)" class="r1xawcb_b"/><path fill="url(#il82uvb)" class="r1xawcb_b"/><path fill="url(#icbJSMd)" class="mqugyu6md"/><path fill="url(#iccDLdJ)" class="mqugyu6md"/><g filter="url(#ib8bbPe)"><circle fill="url(#iQk5IOe)" class="yv8ct19nr"/><circle fill="url(#ioxEsGl)" class="yv8ct19nr"/></g><ellipse fill="url(#iCrkxFc)" transform="rotate(-31.445 16.554 23.399)" class="kqiql03qa"/><path fill="url(#iZtp0Fd)" class="tf1435bsz"/><path fill="url(#iqpaHsy)" class="izabd-jnr"/><g filter="url(#iWvbBfd)"><path fill="url(#ihooV6d)" class="dby6-8bqy"/></g><g filter="url(#igV9itb)"><path fill="url(#izQCCbm)" class="k1n3c-oqn"/><path fill="url(#ikbqxly)" class="k1n3c-oqn"/></g><g filter="url(#iVWc2tc)"><path class="dfioa_bfd"/><path fill="url(#i4SHcVb)" class="djqzmac-h"/></g><g filter="url(#i7RCkkb)"><path class="iy0-_vhtm"/><path fill="url(#i1m69wb)" class="k4g_5mrud"/></g><g filter="url(#i3AqO3i)"><path fill="url(#ikwnRJb)" class="v8pyzobsk"/><path fill="url(#i9DMzRc)" class="v8pyzobsk"/><path fill="url(#ibreWVg)" class="v8pyzobsk"/><path fill="url(#iaeQprc)" class="v8pyzobsk"/><path fill="url(#ij3UGZL)" class="v8pyzobsk"/><path fill="url(#iRkrx1u)" class="v8pyzobsk"/><path fill="url(#iaGIBvc)" class="v8pyzobsk"/><path fill="url(#iY8Xx1b)" class="v8pyzobsk"/></g><path fill="url(#i4BvZ6c)" class="v8pyzobsk"/><path fill="url(#iU5DT2d)" class="v8pyzobsk"/><path fill="url(#ipS6iEd)" class="v8pyzobsk"/><g filter="url(#iG8R8md)"><path class="u3652hbvq"/></g><g filter="url(#ickeaAc)"><path class="wk6ysu79b"/><path fill="url(#iNFoXxo)" class="n4rlg11-l"/><path fill="url(#ia0iJ6d)" class="n4rlg11-l"/><path fill="url(#isfVQoc)" class="n4rlg11-l"/><path fill="url(#iUJL3Me)" class="n4rlg11-l"/></g><g filter="url(#iv3N8uc)"><path class="y14ghbckx"/><path fill="url(#iDgpw1c)" class="pxavwbbxf"/></g><g filter="url(#i7BUyEe)"><path class="zy1h1z55x"/><path fill="url(#ilDq7Es)" class="ze40wjbsc"/><path fill="url(#iNrNqub)" class="ze40wjbsc"/></g><g filter="url(#ihIQN3c)"><path stroke="url(#iFMRaJe)" class="f5gf9hbul"/></g><g filter="url(#i1Mz3oe)"><path class="y44urlb5i"/></g><g filter="url(#iaNY1Ic)"><path class="gqyesjbxh"/></g><g filter="url(#iZNGKhc)"><path fill="url(#iprvUUd)" class="lx6pr3bfo"/><path fill="url(#iR1zTSd)" class="lx6pr3bfo"/><path fill="url(#izYMnbb)" class="lx6pr3bfo"/></g><path fill="url(#iUiBBtb)" class="lx6pr3bfo"/><g filter="url(#ivvk91m)"><path class="m30qzccnf"/></g><g filter="url(#iNCSkqc)"><path class="dldloji7j"/></g><g filter="url(#i19fhhd)"><path stroke="url(#i9mtVkb)" class="n3pzo91gp"/></g><path class="wq_6-jqcy"/><defs><radialGradient id="iHr0NPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.796 13.152)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="id409pc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.98 13.42)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iVJBMpe" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.94 8.217)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iUo6sAb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.373 7.705)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i1dG9jd" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.143 11.707)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ip31LzE" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.998 6.878)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iSjM0kc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.607 9.8)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iI5gFpX" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.688 8.026)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iEeAgQe" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.05 -3.767)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iwcqehc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.956 9.764)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iDEqmqX" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 2.78 7.183)scale(2.91973 2.69143)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="icQ93yd" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.26 12.594)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iViecEe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.533)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iuhQLbe" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.22 4.165)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iCBdd2r" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.118 24.533)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="i4ZC7AD" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.845)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="iIZwoXd" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.43 15.168)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="i2bcbpT" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.683)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="iwiC3Rb" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.34 17.783)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="ivTuwAc" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.157)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="iznByOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.532)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iqmInAc" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.432 25.314)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="iggAQLd" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.252 20.158)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="iMFFrKc" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.595)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="iOR8MCd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.001)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="iYk1gPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.064)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="i4r5cFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.752)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="i6kNpTb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.345)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="i647Wqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.068 21.095)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="idjiMmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.735)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="ijuf4Bc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.735)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iHqKkcE" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.589 58.885)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="ilqqeDe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.492)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="iOlUHde" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.12 15.814)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="iIizEnb" cx="0" cy="0" r="1" gradientTransform="matrix(3.52963 0 0 2.27341 18.523 16.257)" gradientUnits="userSpaceOnUse"><stop class="ge69a97wz"/><stop offset="1" class="jd18rptxw"/></radialGradient><radialGradient id="inwurSa" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.47)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="i54JjGd" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.728)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="iQTKuMl" cx="0" cy="0" r="1" gradientTransform="rotate(13.799 -60.983 36.079)scale(.68782 .87718)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="iBosmBc" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.358 16.377)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iOB8XHb" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 11.987 7.366)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="id99MGz" cx="0" cy="0" r="1" gradientTransform="matrix(-7.31239 0 0 -2.83509 14.65 16.189)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="sb_6z1bpd"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="iNoYEGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.808)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="iNpj7Rb" cx="0" cy="0" r="1" gradientTransform="rotate(160.752 7.102 9.74)scale(3.22747 5.66825)" gradientUnits="userSpaceOnUse"><stop class="tip65z0am"/><stop offset="1" class="ek8xgnb4y"/></radialGradient><radialGradient id="i2IkSDc" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.538 11.48)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="iIDccEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.775 16.86)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="i6p2Yrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.61)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="iR4LLzc" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.71 20.887)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="il82uvb" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.48466 .4507 .80322 8.182 16.994)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="icbJSMd" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.182 16.58)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iccDLdJ" cx="0" cy="0" r="1" gradientTransform="rotate(-31.216 35.643 -9.84)scale(1.00998 .97546)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="iQk5IOe" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.12 16.91)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="ioxEsGl" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.376)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="izQCCbm" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.137 11.091)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="ikbqxly" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.168 8.97)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="i4SHcVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.49 10.764)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="i1m69wb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.497 10.652)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="ikwnRJb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.957 10.114)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="i9DMzRc" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.724 7.505)scale(2.25599 1.57104)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="ibreWVg" cx="0" cy="0" r="1" gradientTransform="matrix(1.0735 -3.47607 4.41049 1.36207 13.918 16.897)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iaeQprc" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 3.754 12.531)scale(6.84714 6.88381)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="ij3UGZL" cx="0" cy="0" r="1" gradientTransform="scale(6.60207 6.56691)rotate(90 .4 2)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="iRkrx1u" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.378 6.793)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iaGIBvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.4 9.696)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iY8Xx1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 14.022 9.467)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="i4BvZ6c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.194 11.183)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iU5DT2d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8113 2.02102 -1.67661 -2.33222 20.02 15.23)" gradientUnits="userSpaceOnUse"><stop class="vx1k0bbnw"/><stop offset="1" class="pshyf94fk"/></radialGradient><radialGradient id="ipS6iEd" cx="0" cy="0" r="1" gradientTransform="matrix(5.53125 3.625 -5.23935 7.99453 15.02 10.876)" gradientUnits="userSpaceOnUse"><stop offset=".917" class="e7v24h5mq"/><stop offset=".98" class="hgqs6y9yl"/></radialGradient><radialGradient id="iNFoXxo" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.882 11.91)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iUJL3Me" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.643 12.122)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iDgpw1c" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.4 -4.165)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ilDq7Es" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.147 7.025)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iNrNqub" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.309 3.097)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iprvUUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.443)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="c7yfkfb_x"/><stop offset=".878" class="ly-mhyl9x"/></radialGradient><radialGradient id="iR1zTSd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 13.2)" gradientUnits="userSpaceOnUse"><stop class="cycj4pb5c"/><stop offset="1" class="xkd2ooi4v"/></radialGradient><radialGradient id="izYMnbb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25001 4.51317 -4.6352 -5.39197 23.432 6.443)" gradientUnits="userSpaceOnUse"><stop class="mbbg-bcay"/><stop offset="1" class="psls5zbwz"/><stop offset="1" class="vyoyvyblw"/></radialGradient><radialGradient id="i9mtVkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57932 2.45245 0 16.245 14.176)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></radialGradient><filter id="iVaeJic" width="15.268" height="15.768" x="8.589" y="1.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/></filter><filter id="i5jYz6c" width="7.981" height="13.148" x="1.991" y="16.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/></filter><filter id="isAPRYc" width="7.981" height="13.148" x="22.028" y="16.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/></filter><filter id="i2YKI6b" width="9.078" height="5.683" x="17.916" y="15.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/></filter><filter id="ieJ99Md" width="8.928" height="5.533" x="5.258" y="15.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/></filter><filter id="iM70Lte" width="4.194" height="5.942" x="13.971" y="12.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/></filter><filter id="ib8bbPe" width="3.465" height="3.465" x="14.33" y="22.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/></filter><filter id="iWvbBfd" width="3.368" height="3.218" x="9.803" y="9.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/></filter><filter id="igV9itb" width="3.218" height="3.468" x="19.316" y="8.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/></filter><filter id="iVWc2tc" width="3.148" height="3.148" x="19.351" y="9.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_999" stdDeviation=".25"/></filter><filter id="i7RCkkb" width="2.648" height="2.648" x="10.107" y="9.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_999" stdDeviation=".125"/></filter><filter id="i3AqO3i" width="10.191" height="11.127" x="11.003" y="5.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/></filter><filter id="iG8R8md" width="2.877" height="3.682" x="14.497" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_999" stdDeviation=".25"/></filter><filter id="ickeaAc" width="2.377" height="3.182" x="14.909" y="9.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_999" stdDeviation=".125"/></filter><filter id="iv3N8uc" width="4.412" height="4.713" x="9.644" y="3.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/><feGaussianBlur result="effect2_foregroundBlur_4002_999" stdDeviation=".25"/></filter><filter id="i7BUyEe" width="8.767" height="5.782" x="12.928" y="2.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/><feGaussianBlur result="effect2_foregroundBlur_4002_999" stdDeviation=".125"/></filter><filter id="ihIQN3c" width="1.145" height="2.31" x="12.907" y="3.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_999" stdDeviation=".1"/></filter><filter id="i1Mz3oe" width="6.427" height="3.372" x="15.516" y="4.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_999" stdDeviation=".375"/></filter><filter id="iaNY1Ic" width="13.891" height="7.06" x="9.087" y="7.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_999" stdDeviation=".375"/></filter><filter id="iZNGKhc" width="15.159" height="7.107" x="8.403" y="6.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.152941 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.333333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_999" result="effect2_innerShadow_4002_999"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.215686 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_999" result="effect3_innerShadow_4002_999"/></filter><filter id="ivvk91m" width="2.192" height="1.627" x="17.223" y="8.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_999" result="effect2_innerShadow_4002_999"/></filter><filter id="iNCSkqc" width="2.192" height="1.627" x="12.726" y="8.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_999"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_999" result="effect2_innerShadow_4002_999"/></filter><filter id="i19fhhd" width="2.476" height="1.695" x="15.615" y="12.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_999" stdDeviation=".05"/></filter><linearGradient id="ixgle3Z" x1="20.791" x2="13.986" y1="3.699" y2="16.304" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iSLEYkc" x1="23.236" x2="22.979" y1="29.876" y2="29.876" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="i6UFgvb" x1="8.857" x2="8.994" y1="29.876" y2="29.876" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="iqdJ1qe" x1="23.252" x2="23.486" y1="29.876" y2="29.876" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="ivxRBQb" x1="25.746" x2="20.292" y1="15.814" y2="20.025" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="iz6CZrQ" x1="9.772" x2="9.772" y1="15.808" y2="20.595" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="iq4saGc" x1="9.772" x2="9.772" y1="15.439" y2="17.407" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="iCrkxFc" x1="16.985" x2="15.947" y1="23.013" y2="23.917" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="iZtp0Fd" x1="8.913" x2="23.289" y1="15.461" y2="15.461" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iqpaHsy" x1="8.913" x2="23.289" y1="15.431" y2="15.431" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ihooV6d" x1="9.803" x2="12.762" y1="10.739" y2="10.739" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="ia0iJ6d" x1="15.159" x2="16.098" y1="11.983" y2="11.983" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="isfVQoc" x1="16.098" x2="16.098" y1="12.782" y2="12.172" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iFMRaJe" x1="13.207" x2="13.752" y1="4.454" y2="5.727" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iUiBBtb" x1="10.732" x2="10.979" y1="10.273" y2="10.113" gradientUnits="userSpaceOnUse"><stop offset=".102" class="a5a8_w8qp"/><stop offset=".478" class="ydi8a_bcj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-supervillain-dark" /></template>
<style>
.a--e2mwlv {
  stop-color: var(--svg-color--614b90, #614B90);
}

.a-lmuhb3j {
  stop-color: var(--svg-color--7560a8, #7560A8);
}

.a0e13gbyz {
  fill: var(--svg-color--64417a, #64417A);
  d: path("M6.984 15.847c0 .222.249.316.556.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a5a8_w8qp {
  stop-color: var(--svg-color--5e5158, #5E5158);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.av5bbdb4i {
  stop-color: var(--svg-color--ff499d, #FF499D);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
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

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bozoj1btu {
  stop-color: var(--svg-color--e7547f, #E7547F);
  stop-opacity: 0;
}

.c50kycc4s {
  stop-color: var(--svg-color--ff5292, #FF5292);
  stop-opacity: 0;
}

.c7yfkfb_x {
  stop-color: var(--svg-color--453753, #453753);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cbuctgb-f {
  stop-color: var(--svg-color--dd225e, #DD225E);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.cgymddbwl {
  stop-color: var(--svg-color--3f2563, #3F2563);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.cpk5dlpmi {
  d: path("M9.02 15.847c0 .222.248.316.555.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.ctoai6naw {
  stop-color: var(--svg-color--f93362, #F93362);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
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

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d5ey51fhz {
  d: path("M24.115 16.849c0 .21-.237.3-.53.3c-.291 0-.528-.113-.528-.3a.53.53 0 0 1 1.058 0");
}

.dby6-8bqy {
  d: path("M11.412 12.261a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.dfioa_bfd {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.925 11.726a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.djqzmac-h {
  d: path("M20.925 11.726a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.dkr4vta7s {
  stop-color: var(--svg-color--8977bc, #8977BC);
}

.dldloji7j {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m13.077 8.937l1.607.592c.155.057.236.23.147.368c-.22.342-.656.692-1.345.489c-.65-.192-.792-.814-.755-1.257c.014-.167.188-.25.346-.192");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.do8d1irdg {
  stop-color: var(--svg-color--e1658e, #E1658E);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e1q0bl71g {
  stop-color: var(--svg-color--5f4d85, #5F4D85);
  stop-opacity: 0;
}

.e33ikws-z {
  stop-color: var(--svg-color--ff4574, #FF4574);
}

.e7v24h5mq {
  stop-color: var(--svg-color--5b4543, #5B4543);
  stop-opacity: 0;
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

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f5gf9hbul {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.207 4.11c.023.243.234 1.156.544 1.71");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
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

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.fypjwijgc {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g2wrz_okq {
  stop-color: var(--svg-color--bb4566, #BB4566);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.ge69a97wz {
  stop-color: var(--svg-color--961241, #961241);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glmadebyq {
  d: path("M23.252 18.033v11.843h4.273c-.205-3.069-.605-5.613-1.406-7.563c-.772-1.881-1.77-3.268-2.867-4.28");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.gqyesjbxh {
  fill: var(--svg-color--230e12, #230E12);
  d: path("m9.897 8.36l3.235 4.806a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.152c.08-.24.253-.577.388-.577c.154 0 .313.337.393.576a.4.4 0 0 0 .086.153l1.449 1.655a.617.617 0 0 0 .975-.06l3.235-4.806c.175-.258-.057-.559-.354-.466l-4.82 1.51a.5.5 0 0 0-.279.25c-.177.342-.475.515-.685.52c-.21-.005-.503-.178-.68-.52a.5.5 0 0 0-.278-.25l-4.821-1.51c-.297-.093-.528.208-.354.466");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hgqs6y9yl {
  stop-color: var(--svg-color--5b4543, #5B4543);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hszcn43qv {
  d: path("M8.861 18.033v11.843H4.588c.205-3.069.605-5.613 1.406-7.563c.772-1.881 1.77-3.268 2.867-4.28");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
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

.iitbw26oy {
  d: path("M25.118 15.855c0 .221-.249.316-.555.316s-.556-.12-.556-.316a.555.555 0 0 1 1.11 0");
}

.iql2qqbdo {
  fill-rule: evenodd;
  d: path("M23.283 12.062c.213-.435.324-.921.324-1.427a3.3 3.3 0 0 0-.269-1.306h.006a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.77v-.011a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376A3.3 3.3 0 0 0 13.416 3.5a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.216 3.3v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.51.51 0 0 1 0-.455M11.022 9.39h-.012l1.198 2.356c.124 2.802 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.198c-.053-1.244-.955-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.292 1.275c-.236.123-.79.49-.81 1.439l.01.306z");
}

.iy0-_vhtm {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.432 11.726a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.izabd-jnr {
  d: path("M16.123 15.432h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jd18rptxw {
  stop-color: var(--svg-color--d31c55, #D31C55);
  stop-opacity: 0;
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.k1n3c-oqn {
  d: path("M20.925 12.261a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
}

.k4g_5mrud {
  d: path("M11.432 11.726a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.kb_-_jbav {
  d: path("M30.01 29.876h-3.532l-4.25-8.75l3.648-4.398c3.415 4.437 4.133 10.383 4.133 13.148");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kejp2n55e {
  stop-color: var(--svg-color--79659c, #79659C);
}

.klsvjl5ds {
  stop-color: var(--svg-color--7056ae, #7056AE);
}

.kqiql03qa {
  cx: 16.554px;
  cy: 23.399px;
  rx: 0.552px;
  ry: 0.695px;
}

.kr4wgsbgo {
  stop-color: var(--svg-color--533179, #533179);
}

.ksp1sznci {
  stop-color: var(--svg-color--6d55a5, #6D55A5);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l1led_brw {
  stop-color: var(--svg-color--df1d5a, #DF1D5A);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.ljssbab8s {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.847c0 .222.248.316.555.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.lx6pr3bfo {
  d: path("m8.576 7.03l3.932 5.84a.75.75 0 0 0 1.185.074l1.76-2.012a.5.5 0 0 0 .105-.185c.098-.291.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.185l1.761 2.012a.75.75 0 0 0 1.185-.073l3.932-5.84c.212-.314-.069-.68-.43-.567L17.2 8.299a.6.6 0 0 0-.338.305c-.216.414-.578.624-.833.63c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.304l-5.86-1.836c-.36-.113-.641.253-.429.566");
}

.ly-mhyl9x {
  stop-color: var(--svg-color--4a474e, #4A474E);
}

.m30qzccnf {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m19.064 8.937l-1.608.592c-.154.057-.235.23-.146.368c.22.342.656.692 1.344.489c.65-.192.792-.814.755-1.257c-.014-.167-.188-.25-.345-.192");
}

.m48igd19d {
  stop-color: var(--svg-color--735aa1, #735AA1);
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m9hq76bya {
  stop-color: var(--svg-color--64468e, #64468E);
}

.mbbg-bcay {
  stop-color: var(--svg-color--625570, #625570);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mqugyu6md {
  d: path("M10.065 16.841c0 .292.237.367.53.367c.292 0 .528-.075.528-.367a.53.53 0 1 0-1.058 0");
}

.mxm28cb7d {
  stop-color: var(--svg-color--735784, #735784);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1_6kac4r {
  stop-color: var(--svg-color--745b84, #745B84);
}

.n3pzo91gp {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.75 12.806c-.614.807-1.368.893-1.872.925c-.085.005-.12.104-.051.154c.377.269.857.292 1.342.09c.51-.213.733-.703.747-1.123c.003-.092-.11-.119-.165-.046Z");
}

.n4rlg11-l {
  d: path("m15.716 10.29l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
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

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nmjycpfuo {
  d: path("M6.984 15.847c0 .222.249.316.556.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o46ofwfzc {
  d: path("M13.971 14.966a2.097 2.097 0 0 1 4.195 0v1.547c0 1.371-.94 2.098-2.098 2.098s-2.097-.696-2.097-2.098z");
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.ogttk6b6n {
  stop-color: var(--svg-color--774ca5, #774CA5);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p63xbfaao {
  stop-color: var(--svg-color--85527f, #85527F);
  stop-opacity: 0;
}

.palvvabur {
  d: path("M4.588 29.876h22.937c-.205-3.069-.605-5.613-1.406-7.563c-2.444-5.955-7.159-6.625-10.062-6.484c-2.904-.141-7.618.529-10.063 6.484c-.8 1.95-1.2 4.494-1.406 7.563");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pshyf94fk {
  stop-color: var(--svg-color--4f2c2f, #4F2C2F);
  stop-opacity: 0;
}

.psls5zbwz {
  stop-color: var(--svg-color--625570, #625570);
  stop-opacity: 0;
}

.ptuohkesm {
  stop-color: var(--svg-color--cd2172, #CD2172);
  stop-opacity: 0;
}

.pxavwbbxf {
  d: path("M11.029 4.664c.566-.6 1.636-.6 2.13-.511l.396 1.29c-.252-.039-.478.05-.667.235c-.449 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.q25wohb5n {
  d: path("m15.575 21.206l-2.98-4.595h6.946l-2.958 4.594a.6.6 0 0 1-1.008.001");
}

.qaycvn_cp {
  stop-color: var(--svg-color--67416e, #67416E);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qf-zh-bgi {
  stop-color: var(--svg-color--755da2, #755DA2);
  stop-opacity: 0;
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qsjdql87s {
  stop-color: var(--svg-color--ae495e, #AE495E);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r1xawcb_b {
  d: path("M7.987 16.841c0 .211.237.3.53.3c.291 0 .528-.112.528-.3a.53.53 0 0 0-1.058 0");
}

.r3tvax9mc {
  d: path("M23.083 15.855c0 .221-.25.316-.556.316s-.555-.12-.555-.316a.555.555 0 1 1 1.11 0");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rogbl960m {
  d: path("M1.99 29.876h3.532l4.25-8.75l-3.648-4.398C2.709 21.165 1.99 27.11 1.99 29.876");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sb_6z1bpd {
  stop-color: var(--svg-color--761032, #761032);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.slx6fqref {
  stop-color: var(--svg-color--e1658e, #E1658E);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tf1435bsz {
  d: path("M16.453 15.432c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.ti1znzbde {
  d: path("M24.635 19.81c-.75 1.082-1.856 1.976-4.008 1.05c-1.836-.788-2.711-3.268-2.711-5.046l8.203.023c.652 0 .752.442.492.856a424 424 0 0 1-1.976 3.117");
}

.tip65z0am {
  stop-color: var(--svg-color--6c53a3, #6C53A3);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tyoz-v6go {
  stop-color: var(--svg-color--cd2172, #CD2172);
}

.u05m0u9vr {
  stop-color: var(--svg-color--ae495e, #AE495E);
  stop-opacity: 0;
}

.u3652hbvq {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.706 10.43l-.684 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
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

.v_v98qact {
  stop-color: var(--svg-color--230f39, #230F39);
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v8pyzobsk {
  d: path("M11.01 9.39h.013l-.01-.266l-.01-.306c.02-.95.574-1.316.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.136 1.332l-.12 3.073c-.123 2.803-2.311 4.685-4.982 4.685s-4.86-1.882-4.984-4.684z");
}

.vat9yt_ey {
  stop-color: var(--svg-color--614290, #614290);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vx1k0bbnw {
  stop-color: var(--svg-color--5c2330, #5C2330);
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wk6ysu79b {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.716 10.29l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.wq_6-jqcy {
  fill: var(--svg-color--290018, #290018);
  d: path("M17.75 12.806c-.614.807-1.368.893-1.872.925c-.085.005-.12.104-.051.154c.377.269.857.292 1.342.09c.51-.213.733-.703.747-1.123c.003-.092-.11-.119-.165-.046");
}

.wx32uubmd {
  d: path("M7.467 19.804c.75 1.082 1.856 1.976 4.008 1.051c1.836-.789 2.711-3.269 2.711-5.047l-8.203.024c-.652 0-.752.441-.492.855c.646 1.03 1.519 2.406 1.976 3.117");
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xkd2ooi4v {
  stop-color: var(--svg-color--322f37, #322F37);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xrr4vbcci {
  stop-color: var(--svg-color--7560a8, #7560A8);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y-so25ixd {
  stop-color: var(--svg-color--50387f, #50387F);
}

.y06th9bdt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
  stop-opacity: 0;
}

.y14ghbckx {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M11.029 4.664c.566-.6 1.636-.6 2.13-.511l.396 1.29c-.252-.039-.478.05-.667.235c-.449 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.y44urlb5i {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.504 6.47l-1.425.263a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.ydi8a_bcj {
  stop-color: var(--svg-color--5e5158, #5E5158);
  stop-opacity: 0;
}

.yhvjw36xj {
  stop-color: var(--svg-color--563079, #563079);
}

.yl99ywbbx {
  d: path("M22.037 16.849c0 .292-.237.367-.53.367c-.292 0-.529-.075-.529-.367a.53.53 0 0 1 1.06 0");
}

.yog48s40z {
  stop-color: var(--svg-color--ff5292, #FF5292);
}

.yr3p0jbaj {
  stop-color: var(--svg-color--5d3970, #5D3970);
  stop-opacity: 0;
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yv8ct19nr {
  cx: 16.063px;
  cy: 23.886px;
  r: 1.732px;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zblf_actk {
  stop-color: var(--svg-color--372543, #372543);
}

.ze40wjbsc {
  d: path("M15.495 2.861c-1.133-.25-2.15.88-2.267 1.3c1.052 3.544 3.713 3.35 6.34 3.058c1.572-.175 1.743.542 1.877.889c0-3.933-3.344-4.671-5.921-5.24z");
}

.zhe9zhdzx {
  stop-color: var(--svg-color--7a4c9c, #7A4C9C);
}

.zojxemb8i {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
  stop-opacity: 0;
}

.zxe--8tbm {
  stop-color: var(--svg-color--50387f, #50387F);
  stop-opacity: 0;
}

.zy1h1z55x {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.495 2.861c-1.133-.25-2.15.88-2.267 1.3c1.052 3.544 3.713 3.35 6.34 3.058c1.572-.175 1.743.542 1.877.889c0-3.933-3.344-4.671-5.921-5.24z");
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
