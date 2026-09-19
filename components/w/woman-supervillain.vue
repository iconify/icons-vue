<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i1p3fAb)"><path fill="url(#iEx1x5d)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#ii6R7RG)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#iNukVvf)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#iuaUtBd)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#iv1MiLc)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#i5YQ0iB)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#i68UB0c)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#iiTiNDY)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#iKFvptb)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#iz3BsCe)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#iIJhphB)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#iRcqcve)" clip-rule="evenodd" class="kj7e60h2q"/><path fill="url(#iDdWBbK)" clip-rule="evenodd" class="kj7e60h2q"/></g><g filter="url(#iMeLAue)"><path fill="url(#icQ93yd)" class="rogbl960m"/><path fill="url(#iViecEe)" class="rogbl960m"/></g><g filter="url(#iARyZud)"><path fill="url(#iuhQLbe)" class="kb_-_jbav"/><path fill="url(#iCBdd2r)" class="kb_-_jbav"/></g><path fill="url(#i4ZC7AD)" class="palvvabur"/><path fill="url(#iIZwoXd)" class="palvvabur"/><path fill="url(#i2bcbpT)" class="palvvabur"/><path fill="url(#iSLEYkc)" class="palvvabur"/><path fill="url(#iwiC3Rb)" class="palvvabur"/><path fill="url(#ivTuwAc)" class="palvvabur"/><path fill="url(#iznByOd)" class="palvvabur"/><path fill="url(#i6UFgvb)" class="palvvabur"/><path fill="url(#iqmInAc)" class="glmadebyq"/><path fill="url(#iggAQLd)" class="glmadebyq"/><path fill="url(#iMFFrKc)" class="glmadebyq"/><path fill="url(#iqdJ1qe)" class="glmadebyq"/><path fill="url(#iOR8MCd)" class="hszcn43qv"/><path fill="url(#iYk1gPc)" class="hszcn43qv"/><path fill="url(#i4r5cFb)" class="hszcn43qv"/><path fill="url(#i6kNpTb)" class="hszcn43qv"/><path fill="url(#i647Wqb)" class="q25wohb5n"/><path fill="url(#idjiMmb)" class="r3tvax9mc"/><path fill="url(#ijuf4Bc)" class="iitbw26oy"/><g filter="url(#iP6MElb)"><path fill="url(#ivxRBQb)" class="ti1znzbde"/><path fill="url(#iHqKkcE)" class="ti1znzbde"/><path fill="url(#ilqqeDe)" class="ti1znzbde"/><path fill="url(#iOlUHde)" class="ti1znzbde"/></g><path class="ljssbab8s"/><path fill="url(#inwurSa)" class="cpk5dlpmi"/><path fill="url(#i54JjGd)" class="cpk5dlpmi"/><path class="a0e13gbyz"/><path fill="url(#iQTKuMl)" class="nmjycpfuo"/><g filter="url(#i5B3qIc)"><path fill="url(#iz6CZrQ)" class="wx32uubmd"/><path fill="url(#iq4saGc)" class="wx32uubmd"/><path fill="url(#iBosmBc)" class="wx32uubmd"/><path fill="url(#iOB8XHb)" class="wx32uubmd"/><path fill="url(#iuLoaiz)" class="wx32uubmd"/><path fill="url(#iNoYEGc)" class="wx32uubmd"/></g><g filter="url(#i9nUr8b)"><path fill="url(#isNpXEc)" class="o46ofwfzc"/><path fill="url(#it2RaIc)" class="o46ofwfzc"/></g><path fill="url(#i2IkSDc)" class="yl99ywbbx"/><path fill="url(#iIDccEc)" class="yl99ywbbx"/><path fill="url(#i6p2Yrb)" class="d5ey51fhz"/><path fill="url(#iR4LLzc)" class="r1xawcb_b"/><path fill="url(#il82uvb)" class="r1xawcb_b"/><path fill="url(#icbJSMd)" class="mqugyu6md"/><path fill="url(#iccDLdJ)" class="mqugyu6md"/><g filter="url(#iB48edc)"><circle fill="url(#iQk5IOe)" class="yv8ct19nr"/><circle fill="url(#ioxEsGl)" class="yv8ct19nr"/></g><ellipse fill="url(#iCrkxFc)" transform="rotate(-31.445 16.554 23.399)" class="kqiql03qa"/><g filter="url(#icidEta)"><path fill="url(#i0vI1hb)" class="nacflcrwo"/></g><g filter="url(#iGxUA3c)"><path fill="url(#iYQKa7b)" class="u-k0accsj"/></g><g filter="url(#izDczcC)"><path class="v45hli7wg"/><path fill="url(#iQWlaOb)" class="di9ldgb2l"/></g><g filter="url(#iTMuiQe)"><path class="xyxikm4if"/><path fill="url(#ijl8DFe)" class="vel2nbvep"/></g><g filter="url(#iZD1pOc)"><path fill="url(#i4waqDb)" class="f-6fsm1jb"/><path fill="url(#iIwkXhc)" class="f-6fsm1jb"/><path fill="url(#il6NN1c)" class="f-6fsm1jb"/><path fill="url(#iOIb6Sd)" class="f-6fsm1jb"/><path fill="url(#iXOIJ1c)" class="f-6fsm1jb"/><path fill="url(#iE2CNab)" class="f-6fsm1jb"/><path fill="url(#izSgehc)" class="f-6fsm1jb"/></g><path fill="url(#iFNgQNe)" class="f-6fsm1jb"/><g filter="url(#iapeoIc)"><path class="wkw4j3mcv"/></g><g filter="url(#ioqLrEy)"><path fill="url(#i4yBNQe)" class="olef95bjy"/><path fill="url(#iXxqECe)" class="olef95bjy"/><path fill="url(#is8iCfw)" class="olef95bjy"/><path fill="url(#iQ3Ad0R)" class="olef95bjy"/></g><g filter="url(#iBKW8rc)"><path fill="url(#iWN9ZAb)" class="wnt8m5adu"/><path fill="url(#iOsrB1c)" class="wnt8m5adu"/></g><g filter="url(#iFNGlqc)"><path fill="url(#igjxdob)" class="uzbm8fbih"/><path fill="url(#iK2lSuc)" class="uzbm8fbih"/><path fill="url(#i7obUMd)" class="uzbm8fbih"/></g><g filter="url(#iT6qJVd)"><path stroke="url(#iHAqpFc)" class="uyr3pgb_u"/></g><g filter="url(#iLunWDb)"><path class="oxuqfhtpn"/></g><g filter="url(#ikL66ee)"><path fill="url(#iv7pADc)" class="lx6pr3bfo"/><path fill="url(#ieEhxqd)" class="lx6pr3bfo"/><path fill="url(#i2lx1mX)" class="lx6pr3bfo"/></g><g filter="url(#i3Kn07b)"><path fill="url(#ixe1VBb)" class="nbtsubb7v"/></g><g filter="url(#ipepipy)"><path fill="url(#iJ3NeLb)" class="g069mbodf"/></g><path class="ttza0znfm"/><defs><radialGradient id="ii6R7RG" cx="0" cy="0" r="1" gradientTransform="rotate(28.301 -17.74 46.353)scale(3.18955 4.51784)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="iNukVvf" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 11.461 12.685)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iuaUtBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.57099 -5.8032 0 16.032 12.778)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iv1MiLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 11.122 10.973)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="i5YQ0iB" cx="0" cy="0" r="1" gradientTransform="matrix(-.46758 2.51377 -2.61762 -.4869 11.713 8.536)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="i68UB0c" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 3.479 12.184)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iiTiNDY" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.686 7.189)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iKFvptb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.542 9.8)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iz3BsCe" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 14.625 4.112)scale(4.66215 6.69539)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iIJhphB" cx="0" cy="0" r="1" gradientTransform="matrix(-.00843 -1.37436 .45061 -.00276 13.328 5.984)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iRcqcve" cx="0" cy="0" r="1" gradientTransform="rotate(-148.106 9.152 6.2)scale(6.03297 7.34671)" gradientUnits="userSpaceOnUse"><stop class="z29mgbg9e"/><stop offset="1" class="txubum6tf"/></radialGradient><radialGradient id="iDdWBbK" cx="0" cy="0" r="1" gradientTransform="matrix(6.1875 -2.5 2.5 6.1875 18.52 16.363)" gradientUnits="userSpaceOnUse"><stop class="ijh-4jgzd"/><stop offset="1" class="iupt-xb7z"/></radialGradient><radialGradient id="icQ93yd" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.26 12.594)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iViecEe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.533)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iuhQLbe" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.22 4.165)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iCBdd2r" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.118 24.533)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="i4ZC7AD" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.845)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="iIZwoXd" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.43 15.168)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="i2bcbpT" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.683)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="iwiC3Rb" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.34 17.783)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="ivTuwAc" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.157)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="iznByOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.532)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iqmInAc" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.432 25.314)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="iggAQLd" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.252 20.158)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="iMFFrKc" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.595)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="iOR8MCd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.001)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="iYk1gPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.064)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="i4r5cFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.752)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="i6kNpTb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.345)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="i647Wqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.068 21.095)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="idjiMmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.735)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="ijuf4Bc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.735)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iHqKkcE" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.589 58.885)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="ilqqeDe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.492)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="iOlUHde" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.12 15.814)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="inwurSa" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.47)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="i54JjGd" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.728)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="iQTKuMl" cx="0" cy="0" r="1" gradientTransform="rotate(13.799 -60.983 36.079)scale(.68782 .87718)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="iBosmBc" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.358 16.377)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iOB8XHb" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 11.987 7.366)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="iuLoaiz" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 0 0 -4.84375 14.65 16.189)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="c5ehj6bcm"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="iNoYEGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.808)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="isNpXEc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.3667 .90626 -1.59163 -5.9128 17.338 16.751)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="odam8hbyg"/><stop offset="1" class="du8_b9dvn"/></radialGradient><radialGradient id="it2RaIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.28125 -2.36037 0 16.068 16.376)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="kyuudab7x"/><stop offset="1" class="tmqa42b1z"/></radialGradient><radialGradient id="i2IkSDc" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.538 11.48)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="iIDccEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.775 16.86)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="i6p2Yrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.61)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="iR4LLzc" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.71 20.887)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="il82uvb" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.48466 .4507 .80322 8.182 16.994)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="icbJSMd" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.182 16.58)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iccDLdJ" cx="0" cy="0" r="1" gradientTransform="rotate(-31.216 35.643 -9.84)scale(1.00998 .97546)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="iQk5IOe" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.12 16.91)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="ioxEsGl" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.376)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="iYQKa7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.072 11.091)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iQWlaOb" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.73 -52.165)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="ijl8DFe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.366 10.652)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="i4waqDb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.336 7.13)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iIwkXhc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.933 10.812)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="il6NN1c" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.853 16.897)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iOIb6Sd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.44059 -11.8177 0 15.77 9.63)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="iXOIJ1c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.66 11.77)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iE2CNab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.334 9.696)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="izSgehc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.114 9.783)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iFNgQNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.128 11.184)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iXxqECe" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.817 11.91)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iWN9ZAb" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.787 4.986)scale(5.36951 2.34181)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iOsrB1c" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 5.908 4.235)scale(3.81321 1.88454)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="igjxdob" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.824 2.527)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iK2lSuc" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.844 8.887)scale(3.44004 7.20923)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="i7obUMd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46744 5.78149 -3.05443 17.182 9.411)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="iv7pADc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.443)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="d345q5kvq"/><stop offset=".878" class="q3r2vvb2e"/></radialGradient><radialGradient id="ieEhxqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 13.2)" gradientUnits="userSpaceOnUse"><stop class="icl8iab1q"/><stop offset="1" class="d-uipgb7e"/></radialGradient><radialGradient id="i2lx1mX" cx="0" cy="0" r="1" gradientTransform="rotate(147.848 11.116 6.692)scale(6.34862 12.6391)" gradientUnits="userSpaceOnUse"><stop class="x_gul429t"/><stop offset="1" class="vyoyvyblw"/></radialGradient><radialGradient id="ixe1VBb" cx="0" cy="0" r="1" gradientTransform="matrix(.46094 1.04688 -1.8385 .80948 18.291 9.323)" gradientUnits="userSpaceOnUse"><stop class="f21c62brn"/><stop offset="1" class="femkqfbis"/></radialGradient><radialGradient id="iJ3NeLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 1.04688 -1.83849 -.8095 13.85 9.323)" gradientUnits="userSpaceOnUse"><stop class="f21c62brn"/><stop offset="1" class="femkqfbis"/></radialGradient><filter id="i1p3fAb" width="15.268" height="15.268" x="8.523" y="1.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="iMeLAue" width="7.981" height="13.148" x="1.991" y="16.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="iARyZud" width="7.981" height="13.148" x="22.028" y="16.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="iP6MElb" width="9.078" height="5.683" x="17.916" y="15.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="i5B3qIc" width="8.928" height="5.533" x="5.258" y="15.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="i9nUr8b" width="4.194" height="5.942" x="13.971" y="12.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="iB48edc" width="3.465" height="3.465" x="14.33" y="22.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="icidEta" width="3.318" height="3.218" x="9.738" y="9.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="iGxUA3c" width="3.218" height="3.468" x="19.25" y="8.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="izDczcC" width="3.148" height="3.148" x="19.286" y="9.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_996" stdDeviation=".25"/></filter><filter id="iTMuiQe" width="2.648" height="2.648" x="10.042" y="9.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_996" stdDeviation=".125"/></filter><filter id="iZD1pOc" width="10.191" height="11.277" x="10.937" y="5.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="iapeoIc" width="2.877" height="3.682" x="14.431" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_996" stdDeviation=".25"/></filter><filter id="ioqLrEy" width="2.377" height="3.182" x="14.844" y="9.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_996" stdDeviation=".125"/></filter><filter id="iBKW8rc" width="4.985" height="5.214" x="9.325" y="3.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_996" stdDeviation=".375"/></filter><filter id="iFNGlqc" width="8.914" height="5.78" x="12.715" y="2.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_996" stdDeviation=".125"/></filter><filter id="iT6qJVd" width="1.145" height="2.31" x="12.841" y="3.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_996" stdDeviation=".125"/></filter><filter id="iLunWDb" width="13.891" height="7.06" x="9.087" y="7.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_996" stdDeviation=".375"/></filter><filter id="ikL66ee" width="15.059" height="7.157" x="8.503" y="6.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.141176 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.301961 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_996" result="effect2_innerShadow_4002_996"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.246463 0 0 0 0 0.17575 0 0 0 0 0.249183 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_996" result="effect3_innerShadow_4002_996"/></filter><filter id="i3Kn07b" width="2.142" height="1.527" x="17.273" y="8.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.721569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><filter id="ipepipy" width="2.142" height="1.527" x="12.726" y="8.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.721569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_996"/></filter><linearGradient id="iEx1x5d" x1="20.726" x2="13.484" y1="3.699" y2="17.142" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iSLEYkc" x1="23.236" x2="22.979" y1="29.876" y2="29.876" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="i6UFgvb" x1="8.857" x2="8.994" y1="29.876" y2="29.876" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="iqdJ1qe" x1="23.252" x2="23.486" y1="29.876" y2="29.876" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="ivxRBQb" x1="25.746" x2="20.292" y1="15.814" y2="20.025" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="iz6CZrQ" x1="9.772" x2="9.772" y1="15.808" y2="20.595" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="iq4saGc" x1="9.772" x2="9.772" y1="15.439" y2="17.407" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="iCrkxFc" x1="16.985" x2="15.947" y1="23.013" y2="23.917" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="i0vI1hb" x1="9.738" x2="12.697" y1="10.739" y2="10.739" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i4yBNQe" x1="16.032" x2="16.032" y1="12.69" y2="10.008" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="is8iCfw" x1="14.986" x2="15.84" y1="11.928" y2="12.032" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iQ3Ad0R" x1="16.032" x2="16.032" y1="12.782" y2="12.172" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iHAqpFc" x1="13.141" x2="13.686" y1="4.454" y2="5.727" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-supervillain" /></template>
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

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.av5bbdb4i {
  stop-color: var(--svg-color--ff499d, #FF499D);
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

.bozoj1btu {
  stop-color: var(--svg-color--e7547f, #E7547F);
  stop-opacity: 0;
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.c50kycc4s {
  stop-color: var(--svg-color--ff5292, #FF5292);
  stop-opacity: 0;
}

.c5ehj6bcm {
  stop-color: var(--svg-color--a61e39, #A61E39);
}

.cbuctgb-f {
  stop-color: var(--svg-color--dd225e, #DD225E);
  stop-opacity: 0;
}

.cgymddbwl {
  stop-color: var(--svg-color--3f2563, #3F2563);
}

.cpk5dlpmi {
  d: path("M9.02 15.847c0 .222.248.316.555.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
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

.d-jm4nrou {
  stop-color: var(--svg-color--7757b7, #7757B7);
  stop-opacity: 0;
}

.d-uipgb7e {
  stop-color: var(--svg-color--48323e, #48323E);
  stop-opacity: 0;
}

.d345q5kvq {
  stop-color: var(--svg-color--603d60, #603D60);
}

.d5ey51fhz {
  d: path("M24.115 16.849c0 .21-.237.3-.53.3c-.291 0-.528-.113-.528-.3a.53.53 0 0 1 1.058 0");
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.di9ldgb2l {
  d: path("M20.86 11.726a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.dkr4vta7s {
  stop-color: var(--svg-color--8977bc, #8977BC);
}

.do8d1irdg {
  stop-color: var(--svg-color--e1658e, #E1658E);
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.du8_b9dvn {
  stop-color: var(--svg-color--643b89, #643B89);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e1q0bl71g {
  stop-color: var(--svg-color--5f4d85, #5F4D85);
  stop-opacity: 0;
}

.e33ikws-z {
  stop-color: var(--svg-color--ff4574, #FF4574);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e9rx7xb_x {
  stop-color: var(--svg-color--967bc2, #967BC2);
}

.ecn2fkbpq {
  stop-color: var(--svg-color--79659c, #79659C);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f-6fsm1jb {
  d: path("M10.945 9.39h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.439l.051-.02q.027-.012.052-.02a2.3 2.3 0 0 0 1.19-1.235l.081-.194a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.088 1.136 1.333l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.f21c62brn {
  stop-color: var(--svg-color--ccfe8c, #CCFE8C);
}

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
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

.femkqfbis {
  stop-color: var(--svg-color--c6f58b, #C6F58B);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.ft5dv1b6b {
  fill: none;
}

.fypjwijgc {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
}

.g069mbodf {
  d: path("m13.077 8.937l1.607.592c.155.057.236.23.147.368c-.22.342-.656.692-1.345.489c-.65-.192-.792-.814-.755-1.257c.014-.167.188-.25.346-.192");
}

.g2wrz_okq {
  stop-color: var(--svg-color--bb4566, #BB4566);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.glmadebyq {
  d: path("M23.252 18.033v11.843h4.273c-.205-3.069-.605-5.613-1.406-7.563c-.772-1.881-1.77-3.268-2.867-4.28");
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hszcn43qv {
  d: path("M8.861 18.033v11.843H4.588c.205-3.069.605-5.613 1.406-7.563c.772-1.881 1.77-3.268 2.867-4.28");
}

.i3hug6b7s {
  stop-color: var(--svg-color--655586, #655586);
}

.ib49rus2q {
  stop-color: var(--svg-color--72599f, #72599F);
  stop-opacity: 0;
}

.icl8iab1q {
  stop-color: var(--svg-color--48323e, #48323E);
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

.ijh-4jgzd {
  stop-color: var(--svg-color--df5b05, #DF5B05);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iupt-xb7z {
  stop-color: var(--svg-color--df5b05, #DF5B05);
  stop-opacity: 0;
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
}

.kb_-_jbav {
  d: path("M30.01 29.876h-3.532l-4.25-8.75l3.648-4.398c3.415 4.437 4.133 10.383 4.133 13.148");
}

.kejp2n55e {
  stop-color: var(--svg-color--79659c, #79659C);
}

.kj7e60h2q {
  fill-rule: evenodd;
  d: path("M23.218 12.062a3.25 3.25 0 0 0 .324-1.427c0-.468-.097-.906-.269-1.306h.005a3 3 0 0 0-.28-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.77v-.011a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376A3.3 3.3 0 0 0 13.351 3.5a.56.56 0 0 1-.456.233h-.085a3.3 3.3 0 0 0-3.214 3.299v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.581a3.213 3.213 0 0 0 2.895-4.625a.52.52 0 0 1 0-.455m-12.26-2.673h-.013l1.199 2.356c.123 2.802 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.198c-.054-1.244-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.46.051l-.083.194a2.3 2.3 0 0 1-1.24 1.255l-.052.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.klsvjl5ds {
  stop-color: var(--svg-color--7056ae, #7056AE);
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
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

.kyuudab7x {
  stop-color: var(--svg-color--7042ad, #7042AD);
}

.l1led_brw {
  stop-color: var(--svg-color--df1d5a, #DF1D5A);
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.ljssbab8s {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.847c0 .222.248.316.555.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.lx6pr3bfo {
  d: path("m8.576 7.03l3.932 5.84a.75.75 0 0 0 1.185.074l1.76-2.012a.5.5 0 0 0 .105-.185c.098-.291.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.185l1.761 2.012a.75.75 0 0 0 1.185-.073l3.932-5.84c.212-.314-.069-.68-.43-.567L17.2 8.299a.6.6 0 0 0-.338.305c-.216.414-.578.624-.833.63c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.304l-5.86-1.836c-.36-.113-.641.253-.429.566");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m48igd19d {
  stop-color: var(--svg-color--735aa1, #735AA1);
}

.m9hq76bya {
  stop-color: var(--svg-color--64468e, #64468E);
}

.mqugyu6md {
  d: path("M10.065 16.841c0 .292.237.367.53.367c.292 0 .528-.075.528-.367a.53.53 0 1 0-1.058 0");
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

.nacflcrwo {
  d: path("M11.347 12.261a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.nbtsubb7v {
  d: path("m19.064 8.937l-1.608.592c-.154.057-.235.23-.146.368c.22.342.656.692 1.344.489c.65-.192.792-.814.755-1.257c-.014-.167-.188-.25-.345-.192");
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nmjycpfuo {
  d: path("M6.984 15.847c0 .222.249.316.556.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o46ofwfzc {
  d: path("M13.971 14.966a2.097 2.097 0 0 1 4.195 0v1.547c0 1.371-.94 2.098-2.098 2.098s-2.097-.696-2.097-2.098z");
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.odam8hbyg {
  stop-color: var(--svg-color--835ac7, #835AC7);
}

.ogttk6b6n {
  stop-color: var(--svg-color--774ca5, #774CA5);
}

.olef95bjy {
  d: path("m15.65 10.29l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.oxuqfhtpn {
  fill: var(--svg-color--d57e27, #D57E27);
  d: path("m9.897 8.36l3.235 4.806a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.152c.08-.24.253-.577.388-.577c.154 0 .313.337.393.576a.4.4 0 0 0 .086.153l1.449 1.655a.617.617 0 0 0 .975-.06l3.235-4.806c.175-.258-.057-.559-.354-.466l-4.82 1.51a.5.5 0 0 0-.279.25c-.177.342-.475.515-.685.52c-.21-.005-.503-.178-.68-.52a.5.5 0 0 0-.278-.25l-4.821-1.51c-.297-.093-.528.208-.354.466");
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p63xbfaao {
  stop-color: var(--svg-color--85527f, #85527F);
  stop-opacity: 0;
}

.palvvabur {
  d: path("M4.588 29.876h22.937c-.205-3.069-.605-5.613-1.406-7.563c-2.444-5.955-7.159-6.625-10.062-6.484c-2.904-.141-7.618.529-10.063 6.484c-.8 1.95-1.2 4.494-1.406 7.563");
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.ptuohkesm {
  stop-color: var(--svg-color--cd2172, #CD2172);
  stop-opacity: 0;
}

.q25wohb5n {
  d: path("m15.575 21.206l-2.98-4.595h6.946l-2.958 4.594a.6.6 0 0 1-1.008.001");
}

.q3r2vvb2e {
  stop-color: var(--svg-color--514853, #514853);
}

.qaycvn_cp {
  stop-color: var(--svg-color--67416e, #67416E);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qf-zh-bgi {
  stop-color: var(--svg-color--755da2, #755DA2);
  stop-opacity: 0;
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qsjdql87s {
  stop-color: var(--svg-color--ae495e, #AE495E);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.r1xawcb_b {
  d: path("M7.987 16.841c0 .211.237.3.53.3c.291 0 .528-.112.528-.3a.53.53 0 0 0-1.058 0");
}

.r3tvax9mc {
  d: path("M23.083 15.855c0 .221-.25.316-.556.316s-.555-.12-.555-.316a.555.555 0 1 1 1.11 0");
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rogbl960m {
  d: path("M1.99 29.876h3.532l4.25-8.75l-3.648-4.398C2.709 21.165 1.99 27.11 1.99 29.876");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
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

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.ti1znzbde {
  d: path("M24.635 19.81c-.75 1.082-1.856 1.976-4.008 1.05c-1.836-.788-2.711-3.268-2.711-5.046l8.203.023c.652 0 .752.442.492.856a424 424 0 0 1-1.976 3.117");
}

.tmqa42b1z {
  stop-color: var(--svg-color--7042ad, #7042AD);
  stop-opacity: 0;
}

.ttza0znfm {
  fill: var(--svg-color--88004d, #88004D);
  d: path("M17.75 12.806c-.614.807-1.368.893-1.872.925c-.085.005-.12.104-.051.154c.377.269.857.292 1.342.09c.51-.213.733-.703.747-1.123c.003-.092-.11-.119-.165-.046");
}

.txubum6tf {
  stop-color: var(--svg-color--bf500c, #BF500C);
  stop-opacity: 0;
}

.tyoz-v6go {
  stop-color: var(--svg-color--cd2172, #CD2172);
}

.u-k0accsj {
  d: path("M20.86 12.261a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u05m0u9vr {
  stop-color: var(--svg-color--ae495e, #AE495E);
  stop-opacity: 0;
}

.uc4vypayb {
  stop-color: var(--svg-color--8371ae, #8371AE);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.uhjz0cbil {
  stop-color: var(--svg-color--e62f68, #E62F68);
  stop-opacity: 0;
}

.ujur1qtze {
  stop-color: var(--svg-color--db2a69, #DB2A69);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.ungg6q-mb {
  stop-color: var(--svg-color--e7547f, #E7547F);
}

.uq-m7pb0g {
  stop-color: var(--svg-color--573a88, #573A88);
}

.uyr3pgb_u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.141 4.11c.023.243.235 1.156.545 1.71");
}

.uzbm8fbih {
  d: path("M15.429 2.861c-1.133-.25-2.347.956-2.464 1.375c1.542 3.62 3.91 3.275 6.537 2.983c1.573-.175 1.743.542 1.877.889c-.436-4.057-3.369-4.677-5.95-5.247");
}

.v_v98qact {
  stop-color: var(--svg-color--230f39, #230F39);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v45hli7wg {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.86 11.726a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vat9yt_ey {
  stop-color: var(--svg-color--614290, #614290);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vel2nbvep {
  d: path("M11.366 11.726a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wkw4j3mcv {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.64 10.43l-.684 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.494-.376-.613 0");
}

.wnt8m5adu {
  d: path("M11.138 4.638c.621-.553 1.517-.559 2.02-.47l.402 1.291c-.257-.039-.486.05-.678.235c-.456 1.26-2.023 1.955-2.75 2.145c-.15-1.491-.066-2.246 1.006-3.201");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wx32uubmd {
  d: path("M7.467 19.804c.75 1.082 1.856 1.976 4.008 1.051c1.836-.789 2.711-3.269 2.711-5.047l-8.203.024c-.652 0-.752.441-.492.855c.646 1.03 1.519 2.406 1.976 3.117");
}

.x_gul429t {
  stop-color: var(--svg-color--6c587a, #6C587A);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xrr4vbcci {
  stop-color: var(--svg-color--7560a8, #7560A8);
  stop-opacity: 0;
}

.xyxikm4if {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.366 11.726a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.y-so25ixd {
  stop-color: var(--svg-color--50387f, #50387F);
}

.y06th9bdt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
  stop-opacity: 0;
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
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

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yqk-2gbyp {
  stop-color: var(--svg-color--cb6325, #CB6325);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yr3p0jbaj {
  stop-color: var(--svg-color--5d3970, #5D3970);
  stop-opacity: 0;
}

.yv8ct19nr {
  cx: 16.063px;
  cy: 23.886px;
  r: 1.732px;
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z29mgbg9e {
  stop-color: var(--svg-color--ad3902, #AD3902);
}

.zblf_actk {
  stop-color: var(--svg-color--372543, #372543);
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

</style>
