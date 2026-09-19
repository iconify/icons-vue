<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iK4bcxb)"><path fill="url(#iaZzGBd)" class="a-zqzeldx"/><path fill="url(#iDLf1Wb)" class="a-zqzeldx"/><path fill="url(#i7OIbkd)" class="a-zqzeldx"/></g><path fill="url(#i4Wc1Fe)" class="uwqjkbvol"/><path fill="url(#imd4NIb)" class="uwqjkbvol"/><path fill="url(#i1Vpllf)" class="uwqjkbvol"/><g filter="url(#iDB4oBA)"><path class="nltqiob6t"/></g><g filter="url(#io6W1Hf)"><path class="u8l8bnbbx"/></g><path fill="url(#iqvF0Pe)" class="ifk4wkbgx"/><path fill="url(#iMI3nDd)" class="ifk4wkbgx"/><path fill="url(#i1ynvbt)" class="a2ysf6bzt"/><g filter="url(#icsv90b)"><path class="dt3zjybqz"/><path fill="url(#i9TkeRb)" class="o5cnyqbgj"/><path fill="url(#iGhXFFb)" class="o5cnyqbgj"/></g><g filter="url(#ipoPZ2Q)"><path fill="url(#iLuyZJb)" class="e648o_baz"/><path fill="url(#ikP0P5c)" class="e648o_baz"/><path fill="url(#iLMCzNd)" class="e648o_baz"/><path fill="url(#i8uPQSc)" class="e648o_baz"/><path fill="url(#i4DOhAc)" class="e648o_baz"/></g><g filter="url(#icIDq3c)"><path fill="url(#i9huZKN)" class="d49vq-b3b"/><path fill="url(#i60rmed)" class="d49vq-b3b"/><path fill="url(#i3wkpUc)" class="d49vq-b3b"/></g><path fill="url(#iW7Dhmc)" class="d49vq-b3b"/><path fill="url(#iLbqbCd)" class="d49vq-b3b"/><g filter="url(#iBdk3zc)"><path class="ne-a_f2xh"/></g><g filter="url(#ix9el3b)"><path class="huirbzbri"/><path fill="url(#iPJ4W0o)" class="bds0mc2jk"/></g><path fill="url(#iH2ZIwj)" class="ws5-tkbbq"/><path fill="url(#iBTREUc)" class="ws5-tkbbq"/><g filter="url(#ik2xtRb)"><path fill="url(#iMff82c)" class="f-1fthf3z"/></g><path fill="url(#iWsG4Wd)" class="e7x_umu1z"/><g filter="url(#iXe7Urb)"><path fill="url(#iI05f6d)" class="bgcikgb_z"/></g><g filter="url(#iHDcTvd)"><path fill="url(#i2iuHyd)" class="f4zah8e_v"/></g><g filter="url(#iRWqrvd)"><path fill="url(#imGIHBd)" class="z2dc11bst"/></g><path fill="url(#iO5rmJc)" class="z2dc11bst"/><path fill="url(#ilyFfke)" class="z2dc11bst"/><path fill="url(#iA1g0Ed)" class="z2dc11bst"/><path fill="url(#imriNte)" class="z2dc11bst"/><path fill="url(#iyeLfIe)" class="z2dc11bst"/><path fill="url(#iCEwqKe)" class="z2dc11bst"/><g filter="url(#iCWrfpe)"><path class="f3-rogtvj"/></g><path class="o0iamdbbq"/><path fill="url(#ioTe4Nc)" class="c-r7lac-e"/><path fill="url(#iflFvje)" class="c-r7lac-e"/><path fill="url(#i3rHAhd)" class="c-r7lac-e"/><path fill="url(#idi6wQb)" class="c-r7lac-e"/><path fill="url(#iSak1Kd)" class="c-r7lac-e"/><g filter="url(#iTMh4lc)"><path stroke="url(#i1e49nd)" class="p5-kffbwq"/></g><path class="p1qx546bt"/><g filter="url(#iD4KtVd)"><path class="i6ome3bjp"/></g><g filter="url(#ibpcLXc)"><path class="wfyw6s3ky"/></g><g filter="url(#iyVcPxb)"><path fill="url(#imOjsTd)" class="m085vbczi"/></g><g filter="url(#iWD8cqc)"><path fill="url(#ibpwENS)" clip-rule="evenodd" class="akd-kjb0w"/></g><path class="aaxdscbsl"/><path fill="url(#iEgq0rd)" class="i_adio88s"/><path class="ze51d9bhu"/><g filter="url(#iXmxQ8d)"><path class="vhfg2eqad"/><path fill="url(#i9W19jb)" class="ah72kqf4l"/></g><g filter="url(#ijaAUie)"><path fill="url(#iq5qcpc)" class="k1teuu2jt"/></g><path class="eibw3jify"/><path fill="url(#iXdBk2d)" class="njr-tqk5i"/><path class="veytm7xja"/><g filter="url(#izGOFTb)"><path fill="url(#iVMn0de)" class="lc-98cbqi"/></g><g filter="url(#iUJG3Dt)"><ellipse transform="rotate(-27.914 11.197 5.792)" class="e_534j-zv"/><ellipse fill="url(#iVUe7bd)" transform="rotate(-27.914 11.197 5.792)" class="rhhoifucn"/></g><g filter="url(#iY4q6QZ)"><path class="ccjl1vw5m"/></g><g filter="url(#incT0wb)"><path class="mh5-x1bhk"/></g><g filter="url(#isNBw4b)"><path fill="url(#iFaq6vd)" class="zm8v8_boj"/></g><g filter="url(#imRxire)"><path fill="url(#iDFwJ8u)" class="rttxvnbop"/></g><g filter="url(#iU8e5yc)"><path fill="url(#iHy0Bue)" class="rttxvnbop"/><path fill="url(#iVsD1De)" class="rttxvnbop"/><path fill="url(#ig0hvyd)" class="rttxvnbop"/><path fill="url(#iSf6YYm)" class="rttxvnbop"/><path fill="url(#izRXtYd)" class="rttxvnbop"/></g><g filter="url(#iMuxlBd)"><path fill="url(#iaPypic)" clip-rule="evenodd" class="kkds9sbif"/></g><g filter="url(#isgoIkh)"><path fill="url(#iJGx8Rc)" clip-rule="evenodd" class="ga74agm1p"/></g><defs><radialGradient id="iaZzGBd" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 6.594 5.448)scale(8.70848 16.566)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="x0zlvzb_b"/><stop offset="1" class="jhou7tlnj"/></radialGradient><radialGradient id="iDLf1Wb" cx="0" cy="0" r="1" gradientTransform="matrix(2.86052 -4.80863 5.49651 3.26972 13.703 8.715)" gradientUnits="userSpaceOnUse"><stop class="i2h38kz1u"/><stop offset="1" class="ftmryjblq"/></radialGradient><radialGradient id="i7OIbkd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06036 2.34267 -2.56131 -1.15933 10.399 4.868)" gradientUnits="userSpaceOnUse"><stop class="x7utjgb1r"/><stop offset="1" class="ke5ghyvxy"/><stop offset="1" class="ke5ghyvxy"/></radialGradient><radialGradient id="i1Vpllf" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72861 4.02946 -1.91414 -.82115 8.63 27.856)" gradientUnits="userSpaceOnUse"><stop class="rxdm1gb4b"/><stop offset="1" class="en9rkbb0o"/></radialGradient><radialGradient id="i1ynvbt" cx="0" cy="0" r="1" gradientTransform="rotate(117.071 -3.416 17.085)scale(2.08793 1.98277)" gradientUnits="userSpaceOnUse"><stop class="u6ezkbbkd"/><stop offset="1" class="cpmw12bkg"/></radialGradient><radialGradient id="i9TkeRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.61426 -1.61513 0 20.377 7.221)" gradientUnits="userSpaceOnUse"><stop class="nqd2cobbz"/><stop offset="1" class="kp02gcw6w"/></radialGradient><radialGradient id="iGhXFFb" cx="0" cy="0" r="1" gradientTransform="rotate(146.31 9.82 4.868)scale(.67604 .47453)" gradientUnits="userSpaceOnUse"><stop class="dwgr7twqc"/><stop offset="1" class="k0x-nnb5u"/></radialGradient><radialGradient id="iLuyZJb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.18747 -5.71878 5.09832 -4.62466 15.278 14.836)" gradientUnits="userSpaceOnUse"><stop class="zstr-2b3h"/><stop offset="1" class="r38-lhbhs"/></radialGradient><radialGradient id="ikP0P5c" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 -.45703 .8012 5.4783 9.84 12.324)" gradientUnits="userSpaceOnUse"><stop offset=".481" class="dz8dqqbnh"/><stop offset="1" class="hv09-7aho"/></radialGradient><radialGradient id="iLMCzNd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 0 0 -4.28125 16.153 9.867)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="d1nygi1_s"/><stop offset="1" class="bzjd0s3dz"/></radialGradient><radialGradient id="i8uPQSc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14245 .25001 -.22815 -1.9551 15.952 12.71)" gradientUnits="userSpaceOnUse"><stop class="etzb8g0rx"/><stop offset="1" class="q_d1lub6r"/></radialGradient><radialGradient id="i4DOhAc" cx="0" cy="0" r="1" gradientTransform="rotate(91.112 2.088 9.266)scale(2.8878 5.12554)" gradientUnits="userSpaceOnUse"><stop class="ed0bwz-2w"/><stop offset="1" class="h1j4vebkc"/></radialGradient><radialGradient id="i9huZKN" cx="0" cy="0" r="1" gradientTransform="rotate(45.496 -14.752 21.43)scale(10.2092 15.8767)" gradientUnits="userSpaceOnUse"><stop class="h84ffkb2i"/><stop offset="1" class="emq3pu1ym"/></radialGradient><radialGradient id="i3wkpUc" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -4.4375 3.8181 .75287 27.06 16.648)" gradientUnits="userSpaceOnUse"><stop offset=".37" class="c4hclxboa"/><stop offset="1" class="mz51gmfzq"/></radialGradient><radialGradient id="iW7Dhmc" cx="0" cy="0" r="1" gradientTransform="matrix(4.72488 -2.8426 6.67598 11.09657 4.788 29.252)" gradientUnits="userSpaceOnUse"><stop class="ket8l8b0j"/><stop offset="1" class="lze6x5b3f"/></radialGradient><radialGradient id="iLbqbCd" cx="0" cy="0" r="1" gradientTransform="matrix(.81156 -4.64805 2.43505 .42516 28.216 17.497)" gradientUnits="userSpaceOnUse"><stop class="m8u-j2bfh"/><stop offset="1" class="xbj9zzvwg"/></radialGradient><radialGradient id="iPJ4W0o" cx="0" cy="0" r="1" gradientTransform="matrix(-3.31249 1.60939 -.35465 -.72996 11.236 9.283)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="y7jpxbbhu"/><stop offset="1" class="rquix_ngw"/></radialGradient><radialGradient id="iH2ZIwj" cx="0" cy="0" r="1" gradientTransform="matrix(-.80887 -1.87683 2.42187 -1.04377 13.58 10.361)" gradientUnits="userSpaceOnUse"><stop class="cz3brismi"/><stop offset="1" class="cgagdkbfp"/></radialGradient><radialGradient id="iBTREUc" cx="0" cy="0" r="1" gradientTransform="rotate(47.291 -3.816 17.657)scale(1.79682 5.00055)" gradientUnits="userSpaceOnUse"><stop class="y9u9iibtz"/><stop offset="1" class="ebrwadt3p"/></radialGradient><radialGradient id="iWsG4Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.52402 .51786 -.35536 -.3596 15.152 5.788)" gradientUnits="userSpaceOnUse"><stop class="ha79ukbar"/><stop offset="1" class="tyid2cb9a"/></radialGradient><radialGradient id="iI05f6d" cx="0" cy="0" r="1" gradientTransform="rotate(90 4.239 10.354)scale(.50089)" gradientUnits="userSpaceOnUse"><stop class="t1wmkubur"/><stop offset="1" class="hy3u76v1i"/></radialGradient><radialGradient id="i2iuHyd" cx="0" cy="0" r="1" gradientTransform="rotate(106.949 2.778 6.694)scale(.67671)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="yem0kqbom"/><stop offset="1" class="icbl5ibjw"/></radialGradient><radialGradient id="imGIHBd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.392 1.36061 -2.32925 -4.09489 13.26 6.363)" gradientUnits="userSpaceOnUse"><stop class="x0z57ccyo"/><stop offset="1" class="nj83g3bmu"/></radialGradient><radialGradient id="iO5rmJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.54276 -4.67289 0 12.342 5.356)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="jtmo9zbne"/><stop offset="1" class="x5vi3qbzz"/></radialGradient><radialGradient id="ilyFfke" cx="0" cy="0" r="1" gradientTransform="matrix(-.93706 .6165 -.98106 -1.49119 14.418 4.493)" gradientUnits="userSpaceOnUse"><stop class="y77jxgbee"/><stop offset="1" class="juawl1gfq"/></radialGradient><radialGradient id="iA1g0Ed" cx="0" cy="0" r="1" gradientTransform="rotate(47.721 .968 14.26)scale(.62314 2.38307)" gradientUnits="userSpaceOnUse"><stop class="u27eaq1ke"/><stop offset="1" class="zwlqziglb"/></radialGradient><radialGradient id="imriNte" cx="0" cy="0" r="1" gradientTransform="rotate(134.662 5.878 5.101)scale(1.94071 1.24456)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="nxpnkb1eb"/><stop offset="1" class="djrdya1sy"/></radialGradient><radialGradient id="iyeLfIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.55176 .86925 0 13.42 5.595)" gradientUnits="userSpaceOnUse"><stop class="j055wdbud"/><stop offset="1" class="jyqj6pdqa"/></radialGradient><radialGradient id="iCEwqKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.71513 .72746 0 11.237 5.558)" gradientUnits="userSpaceOnUse"><stop class="vmpvo2iof"/><stop offset="1" class="k39_6wapl"/></radialGradient><radialGradient id="iflFvje" cx="0" cy="0" r="1" gradientTransform="matrix(-.37606 0 0 -.11752 12.538 6.818)" gradientUnits="userSpaceOnUse"><stop class="k5p37d2fo"/><stop offset="1" class="yiekaulvh"/></radialGradient><radialGradient id="i3rHAhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.30983 .82485 0 12.342 7.066)" gradientUnits="userSpaceOnUse"><stop class="iwj441a3a"/><stop offset="1" class="nxis-vb-u"/></radialGradient><radialGradient id="iEgq0rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.24811 .35977 -.57071 -.39359 13.607 5.78)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="i9W19jb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 8.065 -.307)scale(.17566 .24183)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXdBk2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.24812 .35977 -.57072 -.3936 11.573 5.78)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="iVUe7bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0036 -.22942 .27577 -.00432 11.19 5.938)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFaq6vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56588 1.26997 -.49095 -.60535 10.905 3.643)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="h0xizc-pq"/><stop offset=".77" class="lnzo7tbfa"/></radialGradient><radialGradient id="iDFwJ8u" cx="0" cy="0" r="1" gradientTransform="rotate(178.548 7.075 1.931)scale(2.7381 1.32767)" gradientUnits="userSpaceOnUse"><stop class="g2qbx_b_v"/><stop offset="1" class="cn6gyybop"/></radialGradient><radialGradient id="iHy0Bue" cx="0" cy="0" r="1" gradientTransform="rotate(-169.129 7.392 1.433)scale(1.89583 .54016)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="n4ybtv3-a"/><stop offset="1" class="k1mq2-9zz"/></radialGradient><radialGradient id="iVsD1De" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37965 .25893 -.21946 -2.01686 13.087 3.327)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="kd1pu_b5e"/><stop offset="1" class="dacedmb2p"/></radialGradient><radialGradient id="ig0hvyd" cx="0" cy="0" r="1" gradientTransform="matrix(.3329 -2.30567 5.0715 .73225 11.62 4.629)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="bh0i_3bdf"/><stop offset=".942" class="bd2iczr0j"/></radialGradient><radialGradient id="iSf6YYm" cx="0" cy="0" r="1" gradientTransform="matrix(.48087 .46236 -.32645 .33952 14.09 4.535)" gradientUnits="userSpaceOnUse"><stop class="mbrovup5s"/><stop offset="1" class="xpjl1tbpw"/></radialGradient><radialGradient id="izRXtYd" cx="0" cy="0" r="1" gradientTransform="matrix(-.51168 -.67814 .38057 -.28715 14.548 4.187)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="rfs9njbxq"/><stop offset="1" class="ymbtox6zc"/></radialGradient><filter id="iK4bcxb" width="11.621" height="12.177" x="4.756" y="1.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.184314 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="iDB4oBA" width="6.401" height="8.773" x="16.966" y="21.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.364706 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="io6W1Hf" width="4.034" height="2.448" x="19.082" y="27.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.219608 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="icsv90b" width="8.253" height="7.777" x="14.731" y="2.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.301961 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_615" result="effect2_innerShadow_4002_615"/></filter><filter id="ipoPZ2Q" width="7.93" height="8.273" x="9.022" y="7.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.207843 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="icIDq3c" width="24.323" height="17.206" x="4.092" y="13.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.27451 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.2 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_615" result="effect2_innerShadow_4002_615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.141176 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_615" result="effect3_innerShadow_4002_615"/></filter><filter id="iBdk3zc" width="2.218" height="2.723" x="4.396" y="15.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.223529 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="ix9el3b" width="7.274" height="8.998" x="3.684" y="8.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.403922 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.368627 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_615" result="effect2_innerShadow_4002_615"/></filter><filter id="ik2xtRb" width="1.601" height="1.501" x="9.407" y="5.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.462745 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="iXe7Urb" width="1.402" height="1.402" x="13.892" y="5.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".1"/></filter><filter id="iHDcTvd" width="1.202" height="1.202" x="9.565" y="5.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".05"/></filter><filter id="iRWqrvd" width="5.152" height="5.072" x="9.966" y="3.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.466667 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="iCWrfpe" width="1.375" height="1.751" x="11.579" y="5.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".125"/></filter><filter id="iTMh4lc" width="1.74" height=".725" x="11.472" y="7.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".025"/></filter><filter id="iD4KtVd" width="1.506" height=".599" x="12.675" y="5.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="ibpcLXc" width="1.506" height=".599" x="10.503" y="5.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="iyVcPxb" width="1.251" height=".615" x="10.566" y="4.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.160784 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="iWD8cqc" width="1.251" height=".616" x="13.092" y="4.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.160784 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/></filter><filter id="iXmxQ8d" width=".472" height=".43" x="12.964" y="5.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".05"/></filter><filter id="ijaAUie" width=".628" height=".638" x="13.302" y="5.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".1"/></filter><filter id="izGOFTb" width=".672" height=".697" x="11.23" y="5.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".1"/></filter><filter id="iUJG3Dt" width=".531" height=".434" x="10.932" y="5.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".05"/></filter><filter id="iY4q6QZ" width="1.024" height=".426" x="13.122" y="4.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".05"/></filter><filter id="incT0wb" width="1.024" height=".426" x="10.579" y="4.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".05"/></filter><filter id="isNBw4b" width="1.749" height="2.018" x="9.539" y="2.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".05"/></filter><filter id="imRxire" width="4.106" height="2.95" x="10.672" y="2.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.14902 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/><feGaussianBlur result="effect2_foregroundBlur_4002_615" stdDeviation=".05"/></filter><filter id="iU8e5yc" width="4.106" height="2.8" x="10.672" y="2.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_615" stdDeviation=".05"/></filter><filter id="iMuxlBd" width="2.957" height="3.037" x="12.949" y="2.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.341176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_615" result="effect2_innerShadow_4002_615"/></filter><filter id="isgoIkh" width="1.893" height="1.933" x="13.445" y="3.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.0627451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_615" result="effect2_innerShadow_4002_615"/></filter><linearGradient id="i4Wc1Fe" x1="21.631" x2="12.192" y1="20.756" y2="31.059" gradientUnits="userSpaceOnUse"><stop class="x_atgxb_v"/><stop offset="1" class="ppa6_abwh"/></linearGradient><linearGradient id="imd4NIb" x1="9.974" x2="19.537" y1="24.594" y2="28.553" gradientUnits="userSpaceOnUse"><stop class="yung1xdgy"/><stop offset="1" class="i-td5rxsk"/></linearGradient><linearGradient id="iqvF0Pe" x1="11.126" x2="8.785" y1="27.476" y2="26.934" gradientUnits="userSpaceOnUse"><stop class="dfbgiuber"/><stop offset="1" class="cfavdtb4y"/></linearGradient><linearGradient id="iMI3nDd" x1="8.408" x2="8.908" y1="27.377" y2="27.659" gradientUnits="userSpaceOnUse"><stop offset=".221" class="aslu99bfy"/><stop offset="1" class="g_36o6z6u"/></linearGradient><linearGradient id="i60rmed" x1="28.216" x2="16.204" y1="17.367" y2="17.367" gradientUnits="userSpaceOnUse"><stop offset=".219" class="k2sx12b0p"/><stop offset="1" class="yu3j8mbni"/></linearGradient><linearGradient id="iMff82c" x1="9.69" x2="10.157" y1="5.899" y2="6.866" gradientUnits="userSpaceOnUse"><stop class="vypt9ybrl"/><stop offset="1" class="u1lo-0nty"/></linearGradient><linearGradient id="ioTe4Nc" x1="12.68" x2="12.31" y1="6.546" y2="6.565" gradientUnits="userSpaceOnUse"><stop class="qy_lu4bmh"/><stop offset="1" class="no2vo2b5r"/></linearGradient><linearGradient id="idi6wQb" x1="12.375" x2="12.375" y1="7.089" y2="6.947" gradientUnits="userSpaceOnUse"><stop class="l_2gubcru"/><stop offset="1" class="cic6athgq"/></linearGradient><linearGradient id="iSak1Kd" x1="12.342" x2="12.342" y1="5.815" y2="6.553" gradientUnits="userSpaceOnUse"><stop class="r0kaalb9z"/><stop offset=".824" class="aau54zb2u"/></linearGradient><linearGradient id="i1e49nd" x1="12.002" x2="12.213" y1="7.797" y2="7.391" gradientUnits="userSpaceOnUse"><stop class="rp4tm-b1w"/><stop offset="1" class="wj_ij8b3z"/></linearGradient><linearGradient id="imOjsTd" x1="11.535" x2="10.566" y1="5.184" y2="5.184" gradientUnits="userSpaceOnUse"><stop class="t_opl6b5d"/><stop offset="1" class="r1b4l6vhf"/></linearGradient><linearGradient id="ibpwENS" x1="14.061" x2="13.092" y1="5.184" y2="5.184" gradientUnits="userSpaceOnUse"><stop class="t_opl6b5d"/><stop offset="1" class="r1b4l6vhf"/></linearGradient><linearGradient id="iq5qcpc" x1="13.722" x2="13.576" y1="5.862" y2="5.951" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVMn0de" x1="11.67" x2="11.525" y1="5.861" y2="5.951" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaPypic" x1="15.412" x2="14.05" y1="2.932" y2="5.276" gradientUnits="userSpaceOnUse"><stop class="y_ccjxb5k"/><stop offset="1" class="w39yz6l0u"/></linearGradient><linearGradient id="iJGx8Rc" x1="15.339" x2="13.856" y1="3.43" y2="4.383" gradientUnits="userSpaceOnUse"><stop class="wzt3udgik"/><stop offset="1" class="gn591vgmd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-dancing-medium" /></template>
<style>
.a-zqzeldx {
  d: path("M6.386 12.84c1.43 1.244 3.316.958 4.08.691v-3.65h5.71c.407-1.046.122-1.935-.187-2.42a.22.22 0 0 1-.023-.19c.065-.185.152-.485.163-.722c.025-.52-.136-.558-.15-1.273c-.016-.715-.243-.979-.617-1.59c-.303-.493-1.082-.814-1.557-1.002c-.521-.207-.706-.598-1.492-.598c-.607 0-1.007.308-1.283.575a.67.67 0 0 1-.378.182c-.966.129-1.789.58-2.244 1.422c-.267.494-.291 1.27-.288 1.8a.42.42 0 0 1-.332.406c-1.206.272-2.09.97-2.51 1.761c-.455.863-.68 3.055 1.108 4.609");
}

.a2ysf6bzt {
  d: path("m8.196 27.901l-.004.008a1.6 1.6 0 0 0-.18.883c.043.36.309.727.784 1.04c.257.17.594.062.751-.201l1.034-1.73z");
}

.aau54zb2u {
  stop-color: var(--svg-color--a87e70, #A87E70);
  stop-opacity: 0;
}

.aaxdscbsl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.457 5.488c.305 0 .562.21.632.493a.128.128 0 0 1-.125.16h-1.04a.107.107 0 0 1-.106-.128a.65.65 0 0 1 .64-.525");
}

.ah72kqf4l {
  d: path("M13.329 5.703c.03.04-.032.087-.103.14c-.07.052-.122.09-.151.05c-.03-.04.003-.114.073-.167c.07-.052.151-.063.18-.023");
}

.akd-kjb0w {
  fill-rule: evenodd;
  d: path("m14.082 5.073l-.064.107za.125.125 0 0 1-.128.214h-.002l-.01-.006l-.043-.022a1 1 0 0 0-.16-.063a1.06 1.06 0 0 0-.5-.043a.125.125 0 1 1-.043-.246c.24-.042.46 0 .62.05a1.5 1.5 0 0 1 .26.112l.004.003z");
}

.aslu99bfy {
  stop-color: var(--svg-color--8b544d, #8B544D);
}

.bd2iczr0j {
  stop-color: var(--svg-color--634b48, #634B48);
}

.bds0mc2jk {
  d: path("M10.83 9.487c.288.55.075 1.23-.476 1.518l-3.072 1.57c-.257.133-.449.238-.543.613l-.332 1.27a1 1 0 0 0-.032.276l.04 1.756a.486.486 0 1 1-.973 0v-.807l-.568.408a.25.25 0 0 0-.103.218l.056.956a.486.486 0 1 1-.971.057l-.07-1.2c-.007-.126 0-.349.137-.528l.541-.869l.184-1.733a3.13 3.13 0 0 1 1.657-2.41l3.007-1.571a1.125 1.125 0 0 1 1.518.476");
}

.bgcikgb_z {
  d: path("M14.593 6.616a.5.5 0 1 0 0-1.002a.5.5 0 0 0 0 1.002");
}

.bh0i_3bdf {
  stop-color: var(--svg-color--634b48, #634B48);
  stop-opacity: 0;
}

.bzjd0s3dz {
  stop-color: var(--svg-color--ff4660, #FF4660);
  stop-opacity: 0;
}

.c-r7lac-e {
  d: path("m12.164 5.947l-.248.793c-.05.163.07.326.243.326h.366a.252.252 0 0 0 .243-.326l-.248-.793c-.053-.176-.3-.176-.356 0");
}

.c4hclxboa {
  stop-color: var(--svg-color--e73e59, #E73E59);
}

.ccjl1vw5m {
  stroke: var(--svg-color--493236, #493236);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M13.247 5.009c.15-.037.524-.019.774.16");
}

.cfavdtb4y {
  stop-color: var(--svg-color--844548, #844548);
}

.cgagdkbfp {
  stop-color: var(--svg-color--6d4f42, #6D4F42);
}

.chm_zob8h {
  stop-color: var(--svg-color--7a5449, #7A5449);
}

.cic6athgq {
  stop-color: var(--svg-color--a2786d, #A2786D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn6gyybop {
  stop-color: var(--svg-color--56363a, #56363A);
}

.cpmw12bkg {
  stop-color: var(--svg-color--cc2e32, #CC2E32);
}

.cz3brismi {
  stop-color: var(--svg-color--926d61, #926D61);
}

.d1nygi1_s {
  stop-color: var(--svg-color--ff4660, #FF4660);
}

.d49vq-b3b {
  d: path("M26.74 13.508q-.222 0-.424.062c-.318.077-.621.221-.994.399h-.001c-.292.139-.626.298-1.043.46c-1.5.587-3.218.587-4.062.587H11.59c-1.933 0-3.534 1.566-3.559 3.499c-.007.536-.011 1.23-.011 1.79c0 1.797-1.662 3.73-2.672 4.687c-.7.664-.868 1.063-.967 1.297l-.014.034l-.02.044l.011.008a2.617 2.617 0 0 0 2.45 3.539h.965c-.499-.101-1.097-.246-1.566-.422c-1.04-.39-1.14-1.27-1.113-1.613c.02-.265.226-1.332 1.636-1.332c.95 0 2.031.064 3.022.123c.632.037 1.227.073 1.728.088c1.048.032 2.12-.065 2.57-1.215c.47-1.43.848-1.91 1.907-1.91c.493.03.872.049 1.124.062l.306.016c.7.047 1.452-.089 1.64-1.36c.211-1.421 1.067-1.552 1.672-1.53c.664.023 1.594.023 2.016-.29c.422-.312.468-.883.468-1.304s.147-1.164 1.172-1.266c1.149-.115 1.375-.36 1.532-.578c.226-.317.239-.694.187-1.266c-.07-.777.115-1.26.582-1.558c.617-.395 1.073.047 1.168.84c.023.19.052.446.085.736c.09.803.21 1.862.306 2.467v-3.618c0-.786-.615-1.43-1.39-1.474v-.002z");
}

.dacedmb2p {
  stop-color: var(--svg-color--5e4341, #5E4341);
}

.dfbgiuber {
  stop-color: var(--svg-color--a46d76, #A46D76);
}

.djrdya1sy {
  stop-color: var(--svg-color--a07b73, #A07B73);
  stop-opacity: 0;
}

.dt3zjybqz {
  fill: var(--svg-color--9b7162, #9B7162);
  d: path("M18.847 8.508h-4.116l.555 2.203h3.508c1.486 0 2.375-1.063 2.297-2.656l-.076-2.34a.1.1 0 0 1 .077-.102c.205-.053.56-.155.784-.215a1 1 0 0 0 .508-.343l.506-.744a.546.546 0 1 0-.907-.609l-.294.443a.17.17 0 0 1-.074.063c-.395.167-.904.173-1.137.163l.28-.268a.533.533 0 0 0-.705-.798l-.4.328c-.133.12-.417.448-.492.804a2.8 2.8 0 0 0-.028.758c.013.151.024.303.015.455l-.15 2.716a.15.15 0 0 1-.15.142");
}

.dwgr7twqc {
  stop-color: var(--svg-color--bb9982, #BB9982);
}

.dz8dqqbnh {
  stop-color: var(--svg-color--d62645, #D62645);
}

.e_534j-zv {
  cx: 11.197px;
  cy: 5.792px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.181px;
  ry: 0.092px;
}

.e648o_baz {
  d: path("M9.95 14.54v1.67l5.735-.155c-.375-1.555-.368-3.258-.211-3.64c.156-.384.453-.774.476-1.29c.024-.516-.172-1-.476-1.484a3.5 3.5 0 0 1-.344-.805a.55.55 0 0 0-.513-.399h-.768c-.068 0-.109.09-.169.122l-.956.496l-1.204-.617c-.906.039-2.078.257-2.304.562c-.227.305-.25 1.008-.094 1.883s.43 1.812.648 2.36c.175.437.193 1.046.18 1.296");
}

.e7x_umu1z {
  d: path("M14.593 6.866a.75.75 0 1 0 0-1.501a.75.75 0 0 0 0 1.5");
}

.ebrwadt3p {
  stop-color: var(--svg-color--562d26, #562D26);
  stop-opacity: 0;
}

.ed0bwz-2w {
  stop-color: var(--svg-color--921c39, #921C39);
}

.eibw3jify {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.227 5.488a.65.65 0 0 0-.632.493a.128.128 0 0 0 .125.16h1.04c.067 0 .12-.061.107-.128a.65.65 0 0 0-.64-.525");
}

.emq3pu1ym {
  stop-color: var(--svg-color--da2e3d, #DA2E3D);
}

.en9rkbb0o {
  stop-color: var(--svg-color--6c1118, #6C1118);
  stop-opacity: 0;
}

.etzb8g0rx {
  stop-color: var(--svg-color--f22b4e, #F22B4E);
}

.f-1fthf3z {
  d: path("M10.157 6.866a.75.75 0 1 0 0-1.501a.75.75 0 0 0 0 1.5");
}

.f3-rogtvj {
  fill: var(--svg-color--96606a, #96606A);
  d: path("m12.16 6.011l-.32.793a.252.252 0 0 0 .243.326h.367a.252.252 0 0 0 .243-.326l-.248-.793c-.053-.175-.23-.175-.286 0");
}

.f4zah8e_v {
  d: path("M10.166 6.616a.5.5 0 1 0 0-1.002a.5.5 0 0 0 0 1.002");
}

.ft5dv1b6b {
  fill: none;
}

.ftmryjblq {
  stop-color: var(--svg-color--1c1414, #1C1414);
  stop-opacity: 0;
}

.g_36o6z6u {
  stop-color: var(--svg-color--8b544d, #8B544D);
  stop-opacity: 0;
}

.g2qbx_b_v {
  stop-color: var(--svg-color--694a46, #694A46);
}

.ga74agm1p {
  fill-rule: evenodd;
  d: path("m14.718 4.488l-.004.015c-.072.222-.282.352-.47.292c-.187-.061-.28-.29-.209-.512l.008-.02h-.039c-.226 0-.409-.159-.409-.356s.183-.356.409-.356h.007L14 3.506c-.043-.221.088-.433.293-.473c.194-.037.385.094.44.296l.004-.002c.181-.134.423-.113.54.045c.116.159.064.396-.118.53l-.016.01q.03.023.056.05c.162.168.178.415.036.551c-.133.128-.356.114-.517-.025");
}

.gn591vgmd {
  stop-color: var(--svg-color--c32e4e, #C32E4E);
}

.h0xizc-pq {
  stop-color: var(--svg-color--5e3e40, #5E3E40);
}

.h1j4vebkc {
  stop-color: var(--svg-color--921c39, #921C39);
  stop-opacity: 0;
}

.h84ffkb2i {
  stop-color: var(--svg-color--d42f4e, #D42F4E);
}

.ha79ukbar {
  stop-color: var(--svg-color--b29483, #B29483);
}

.huirbzbri {
  fill: var(--svg-color--a7806d, #A7806D);
  d: path("M10.83 9.487c.288.55.075 1.23-.476 1.518l-3.072 1.57c-.257.133-.449.238-.543.613l-.332 1.27a1 1 0 0 0-.032.276l.04 1.756a.486.486 0 1 1-.973 0v-.807l-.568.408a.25.25 0 0 0-.103.218l.056.956a.486.486 0 1 1-.971.057l-.07-1.2c-.007-.126 0-.349.137-.528l.541-.869l.184-1.733a3.13 3.13 0 0 1 1.657-2.41l3.007-1.571a1.125 1.125 0 0 1 1.518.476");
}

.hv09-7aho {
  stop-color: var(--svg-color--d62645, #D62645);
  stop-opacity: 0;
}

.hy3u76v1i {
  stop-color: var(--svg-color--926760, #926760);
}

.i_adio88s {
  d: path("M13.36 5.614a.416.416 0 0 1 .402.526h-.804a.418.418 0 0 1 .403-.526");
}

.i-td5rxsk {
  stop-color: var(--svg-color--851e29, #851E29);
  stop-opacity: 0;
}

.i2h38kz1u {
  stop-color: var(--svg-color--1c1414, #1C1414);
}

.i6ome3bjp {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M12.875 5.85c.124-.218.312-.39.717-.39c.177 0 .348.05.5.172c.125.101.109.231.011.28l-.259.148c-.304-.099-.64-.112-.97-.21");
}

.icbl5ibjw {
  stop-color: var(--svg-color--7e554c, #7E554C);
}

.ifk4wkbgx {
  d: path("m8.192 27.91l.719-1.45l2.555-.038l-1.919 3.209c-.157.263-.494.371-.751.202c-.475-.313-.741-.682-.784-1.04a1.6 1.6 0 0 1 .18-.884");
}

.iwj441a3a {
  stop-color: var(--svg-color--98636e, #98636E);
}

.j055wdbud {
  stop-color: var(--svg-color--9b6c69, #9B6C69);
}

.jhou7tlnj {
  stop-color: var(--svg-color--201422, #201422);
}

.jtmo9zbne {
  stop-color: var(--svg-color--9c6873, #9C6873);
  stop-opacity: 0;
}

.juawl1gfq {
  stop-color: var(--svg-color--886863, #886863);
  stop-opacity: 0;
}

.jyqj6pdqa {
  stop-color: var(--svg-color--9b6c69, #9B6C69);
  stop-opacity: 0;
}

.k0x-nnb5u {
  stop-color: var(--svg-color--bb9982, #BB9982);
  stop-opacity: 0;
}

.k1mq2-9zz {
  stop-color: var(--svg-color--6c4c4c, #6C4C4C);
  stop-opacity: 0;
}

.k1teuu2jt {
  d: path("M13.73 5.975a.4.4 0 0 0-.107-.215l-.12.132l.054.106z");
}

.k2sx12b0p {
  stop-color: var(--svg-color--db2f4a, #DB2F4A);
}

.k39_6wapl {
  stop-color: var(--svg-color--98676b, #98676B);
  stop-opacity: 0;
}

.k5p37d2fo {
  stop-color: var(--svg-color--b48f7f, #B48F7F);
}

.kd1pu_b5e {
  stop-color: var(--svg-color--543737, #543737);
  stop-opacity: 0;
}

.ke5ghyvxy {
  stop-color: var(--svg-color--5c4040, #5C4040);
  stop-opacity: 0;
}

.ket8l8b0j {
  stop-color: var(--svg-color--d32659, #D32659);
}

.kkds9sbif {
  fill-rule: evenodd;
  d: path("M14.85 4.965c.013-.04.067-.057.1-.032a.599.599 0 1 0 .711-.963a.067.067 0 0 1 0-.104a.598.598 0 0 0-.705-.967c-.035.025-.09.007-.102-.034a.6.6 0 1 0-1.14.368c.014.04-.02.087-.062.087h-.004a.599.599 0 0 0 0 1.197c.04 0 .073.044.061.083a.599.599 0 0 0 1.14.365");
}

.kp02gcw6w {
  stop-color: var(--svg-color--9f7165, #9F7165);
  stop-opacity: 0;
}

.l_2gubcru {
  stop-color: var(--svg-color--8f5864, #8F5864);
}

.lc-98cbqi {
  d: path("M11.703 5.98c0-.133-.11-.223-.139-.25l-.134.13l.083.168z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnzo7tbfa {
  stop-color: var(--svg-color--542e3f, #542E3F);
  stop-opacity: 0;
}

.lze6x5b3f {
  stop-color: var(--svg-color--d32659, #D32659);
  stop-opacity: 0;
}

.m085vbczi {
  d: path("m10.758 5.286l-.002.001a.125.125 0 0 1-.129-.214l.002-.001l.005-.003l.015-.008q.018-.011.054-.028c.046-.022.111-.05.19-.075c.16-.05.381-.093.62-.051a.125.125 0 1 1-.043.246c-.186-.033-.365 0-.5.043a1.3 1.3 0 0 0-.202.085z");
}

.m8u-j2bfh {
  stop-color: var(--svg-color--b01b4b, #B01B4B);
}

.mbrovup5s {
  stop-color: var(--svg-color--3a1e36, #3A1E36);
}

.mh5-x1bhk {
  stroke: var(--svg-color--493236, #493236);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M11.479 5.009c-.15-.037-.525-.019-.775.16");
}

.mz51gmfzq {
  stop-color: var(--svg-color--e73e59, #E73E59);
  stop-opacity: 0;
}

.n4ybtv3-a {
  stop-color: var(--svg-color--6c4c4c, #6C4C4C);
}

.ne-a_f2xh {
  fill: var(--svg-color--9d6c70, #9D6C70);
  d: path("m5.324 17.383l-.35-.457l-.578-1.078l1.378-.516l.047 1.254l.2.26a.44.44 0 1 1-.697.537");
}

.nj83g3bmu {
  stop-color: var(--svg-color--99696c, #99696C);
}

.njr-tqk5i {
  d: path("M11.324 5.614a.416.416 0 0 0-.401.526h.804a.42.42 0 0 0-.403-.526");
}

.nltqiob6t {
  fill: var(--svg-color--c39687, #C39687);
  d: path("m19.653 28.71l-2.687-5.53l1.851-1.57l3.541 8.133a.1.1 0 0 1-.092.14h-.769c-1.012 0-1.594-.586-1.844-1.172");
}

.no2vo2b5r {
  stop-color: var(--svg-color--b69180, #B69180);
  stop-opacity: 0;
}

.nqd2cobbz {
  stop-color: var(--svg-color--bb917f, #BB917F);
}

.nxis-vb-u {
  stop-color: var(--svg-color--a0736f, #A0736F);
  stop-opacity: 0;
}

.nxpnkb1eb {
  stop-color: var(--svg-color--a07b73, #A07B73);
}

.o0iamdbbq {
  fill: var(--svg-color--a37c6a, #A37C6A);
  d: path("m12.164 5.947l-.248.793c-.05.163.07.326.243.326h.366a.252.252 0 0 0 .243-.326l-.248-.793c-.053-.176-.3-.176-.356 0");
}

.o5cnyqbgj {
  d: path("M18.847 8.508h-4.116l.555 2.203h3.508c1.486 0 2.375-1.063 2.297-2.656l-.076-2.34a.1.1 0 0 1 .077-.102c.205-.053.56-.155.784-.215a1 1 0 0 0 .508-.343l.506-.744a.546.546 0 1 0-.907-.609l-.294.443a.17.17 0 0 1-.074.063c-.395.167-.904.173-1.137.163l.28-.268a.533.533 0 0 0-.705-.798l-.4.328c-.133.12-.417.448-.492.804a2.8 2.8 0 0 0-.028.758c.013.151.024.303.015.455l-.15 2.716a.15.15 0 0 1-.15.142");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p1qx546bt {
  fill: var(--svg-color--87014e, #87014E);
  d: path("M12.342 7.473a1.4 1.4 0 0 1-.663-.16c-.065-.035-.136.04-.094.101a.9.9 0 0 0 1.515 0c.041-.063-.03-.136-.095-.102a1.4 1.4 0 0 1-.663.16");
}

.p5-kffbwq {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.342 7.473a1.4 1.4 0 0 1-.663-.16c-.065-.035-.136.04-.094.101a.9.9 0 0 0 1.515 0c.041-.063-.03-.136-.095-.102a1.4 1.4 0 0 1-.663.16Z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppa6_abwh {
  stop-color: var(--svg-color--9a3037, #9A3037);
}

.q_d1lub6r {
  stop-color: var(--svg-color--f22b4e, #F22B4E);
  stop-opacity: 0;
}

.qy_lu4bmh {
  stop-color: var(--svg-color--b69180, #B69180);
}

.r0kaalb9z {
  stop-color: var(--svg-color--a87e70, #A87E70);
}

.r1b4l6vhf {
  stop-color: var(--svg-color--3f2232, #3F2232);
}

.r38-lhbhs {
  stop-color: var(--svg-color--e9283f, #E9283F);
}

.rfs9njbxq {
  stop-color: var(--svg-color--4e373b, #4E373B);
}

.rhhoifucn {
  cx: 11.197px;
  cy: 5.792px;
  rx: 0.181px;
  ry: 0.092px;
}

.rp4tm-b1w {
  stop-color: var(--svg-color--a07674, #A07674);
}

.rquix_ngw {
  stop-color: var(--svg-color--a98170, #A98170);
  stop-opacity: 0;
}

.rttxvnbop {
  d: path("M12.06 2.467c-.527-.117-1.233.462-1.288.658c.72 1.688 1.69 1.579 3.032 1.528c.745-.028.805.237.867.399c.124-2.122-1.406-2.32-2.61-2.585");
}

.rxdm1gb4b {
  stop-color: var(--svg-color--6c1118, #6C1118);
}

.t_opl6b5d {
  stop-color: var(--svg-color--412332, #412332);
}

.t1wmkubur {
  stop-color: var(--svg-color--9a736a, #9A736A);
}

.tyid2cb9a {
  stop-color: var(--svg-color--9e7470, #9E7470);
}

.u1lo-0nty {
  stop-color: var(--svg-color--865a63, #865A63);
}

.u27eaq1ke {
  stop-color: var(--svg-color--5b3333, #5B3333);
}

.u6ezkbbkd {
  stop-color: var(--svg-color--ee3148, #EE3148);
}

.u8l8bnbbx {
  fill: var(--svg-color--ff444f, #FF444F);
  d: path("m19.082 27.535l.571 1.176c.25.586.832 1.172 1.844 1.172h.77a.1.1 0 0 0 .091-.14l-.628-1.444z");
}

.uwqjkbvol {
  d: path("M15.782 29.914h-8.58c-.823-.182-2.47-.85-2.47-2.06c0-1.514 1.345-2.514 1.25-2.576c-.074-.05 3.025-2.425 4.583-3.606l13.045-5.58c.87-.697 2.796-2.081 3.535-2.037c.738.043 1.021 1.007 1.07 1.483v5.533c0 .921-.304 1.951-.985 2.404c-.68.453-1.212.343-2.26.343c-1.173 0-1.454.336-1.908 1.749c-.363 1.13-.985 1.381-1.9 1.381h-1.189c-.805 0-1.345.172-1.798 1.67c-.4 1.08-1.408 1.296-2.393 1.296");
}

.veytm7xja {
  fill: var(--svg-color--000, #000);
  d: path("M11.562 6.03a.237.237 0 0 0-.238-.238a.237.237 0 0 0-.212.348h.422a.24.24 0 0 0 .028-.11");
}

.vhfg2eqad {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.329 5.703c.03.04-.032.087-.103.14c-.07.052-.122.09-.151.05c-.03-.04.003-.114.073-.167c.07-.052.151-.063.18-.023");
}

.vmpvo2iof {
  stop-color: var(--svg-color--98676b, #98676B);
}

.vypt9ybrl {
  stop-color: var(--svg-color--806058, #806058);
}

.w_bi9zfnz {
  stop-color: var(--svg-color--724c46, #724C46);
}

.w39yz6l0u {
  stop-color: var(--svg-color--dc2d68, #DC2D68);
}

.wfyw6s3ky {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M11.81 5.85c-.124-.218-.312-.39-.717-.39a.77.77 0 0 0-.5.172c-.126.101-.109.231-.012.28l.26.148c.303-.099.64-.112.969-.21");
}

.wj_ij8b3z {
  stop-color: var(--svg-color--a07674, #A07674);
  stop-opacity: 0;
}

.ws5-tkbbq {
  d: path("m13.116 10.256l-1.752-1.6l.383-.172h2.04V9.96a.4.4 0 0 1-.67.296");
}

.wzt3udgik {
  stop-color: var(--svg-color--c9334f, #C9334F);
}

.x_atgxb_v {
  stop-color: var(--svg-color--911c39, #911C39);
}

.x0z57ccyo {
  stop-color: var(--svg-color--b08770, #B08770);
}

.x0zlvzb_b {
  stop-color: var(--svg-color--694c47, #694C47);
}

.x5vi3qbzz {
  stop-color: var(--svg-color--8b5560, #8B5560);
}

.x7utjgb1r {
  stop-color: var(--svg-color--5c4040, #5C4040);
}

.xbj9zzvwg {
  stop-color: var(--svg-color--b01b4b, #B01B4B);
  stop-opacity: 0;
}

.xpjl1tbpw {
  stop-color: var(--svg-color--3a1e36, #3A1E36);
  stop-opacity: 0;
}

.y_ccjxb5k {
  stop-color: var(--svg-color--e73950, #E73950);
}

.y77jxgbee {
  stop-color: var(--svg-color--967669, #967669);
}

.y7jpxbbhu {
  stop-color: var(--svg-color--ba937e, #BA937E);
}

.y9u9iibtz {
  stop-color: var(--svg-color--562d26, #562D26);
}

.yem0kqbom {
  stop-color: var(--svg-color--7b5554, #7B5554);
}

.yiekaulvh {
  stop-color: var(--svg-color--b48f7f, #B48F7F);
  stop-opacity: 0;
}

.ymbtox6zc {
  stop-color: var(--svg-color--4e373b, #4E373B);
  stop-opacity: 0;
}

.yu3j8mbni {
  stop-color: var(--svg-color--db2f4a, #DB2F4A);
  stop-opacity: 0;
}

.yung1xdgy {
  stop-color: var(--svg-color--851e29, #851E29);
}

.z2dc11bst {
  d: path("M9.97 5.526h.006l-.005-.123l-.005-.143c.01-.443.268-.614.378-.671l.024-.01l.024-.01c.248-.113.45-.313.554-.575l.039-.09a.123.123 0 0 1 .215-.024c.335.49.894.78 1.487.78h1.502c.084 0 .504.041.53.622l-.056 1.433c-.058 1.306-1.078 2.184-2.324 2.184s-2.266-.878-2.324-2.184z");
}

.ze51d9bhu {
  fill: var(--svg-color--000, #000);
  d: path("M13.122 6.03c0-.132.106-.238.239-.238a.237.237 0 0 1 .211.348h-.421a.2.2 0 0 1-.029-.11");
}

.zm8v8_boj {
  d: path("M10.93 4.013c-.174.445-.932.811-1.27.9c-.113-.903.237-1.992 1.342-1.795l.186.722c-.186-.053-.226.087-.259.173");
}

.zstr-2b3h {
  stop-color: var(--svg-color--ff3b57, #FF3B57);
}

.zwlqziglb {
  stop-color: var(--svg-color--825a51, #825A51);
  stop-opacity: 0;
}

</style>
