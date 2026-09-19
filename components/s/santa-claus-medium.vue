<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iivjzXd)"><path fill="url(#ifvKxOb)" class="e-rjpbc3s"/><path fill="url(#iX3Iv6c)" class="e-rjpbc3s"/></g><g filter="url(#iHTzivO)"><circle fill="url(#iqg8yTG)" class="y8d4eh7kx"/></g><circle fill="url(#iQVIwOe)" class="y8d4eh7kx"/><g filter="url(#ifpy1je)"><circle fill="url(#iBCGBlb)" class="iheo8cbur"/><circle fill="url(#iNx91oc)" class="iheo8cbur"/></g><circle fill="url(#iwcMIMb)" class="l2ceykibm"/><circle fill="url(#int0hCb)" class="l2ceykibm"/><g filter="url(#iS99sDd)"><circle fill="url(#iOJzmnb)" class="smvwoqxye"/></g><g filter="url(#ixOh2pb)"><circle fill="url(#ioFwvbU)" class="whn9jdb7h"/></g><path fill="url(#i4326ql)" class="hrltht9-f"/><path fill="url(#iH4bnTp)" class="hrltht9-f"/><path fill="url(#iXulCSl)" class="hrltht9-f"/><path fill="url(#iitsMVY)" class="hrltht9-f"/><path fill="url(#iyw4nQd)" class="hrltht9-f"/><path fill="url(#iXrdrmb)" class="hrltht9-f"/><path fill="url(#iXdOXmd)" class="hrltht9-f"/><g filter="url(#iqS3hfd)"><path clip-rule="evenodd" class="t53q3e-6a"/></g><g filter="url(#i1PoU1d)"><path clip-rule="evenodd" class="uj5j0zbkb"/></g><path clip-rule="evenodd" class="d2upmobvt"/><path clip-rule="evenodd" class="btdo69biz"/><path fill="url(#ifBFQ6b)" class="j6cn8wbef"/><path fill="url(#isMN36b)" class="j6cn8wbef"/><path fill="url(#imAtemb)" class="j6cn8wbef"/><path fill="url(#iioYoMe)" class="j6cn8wbef"/><path fill="url(#i59wwwc)" class="j6cn8wbef"/><path fill="url(#ibW8JUb)" class="j6cn8wbef"/><path fill="url(#iBUj17b)" class="j6cn8wbef"/><path fill="url(#ikdvQvX)" class="j6cn8wbef"/><path fill="url(#ilTRRvb)" class="j6cn8wbef"/><g filter="url(#i0zYdue)"><path class="k3smf8bjh"/></g><g filter="url(#iQNXcQy)"><path class="y680a7f1p"/></g><path fill="url(#iEdVn1d)" class="lstyhqihv"/><path fill="url(#iPqFw2T)" class="lstyhqihv"/><path fill="url(#iDKbwdb)" class="lstyhqihv"/><path class="q8nrffr1s"/><path class="ts2a3n5mb"/><g filter="url(#iiP4ihd)"><path fill="url(#iPyXFVb)" class="nodyl9b9g"/><path fill="url(#i99Ax8d)" class="nodyl9b9g"/><path fill="url(#inMchle)" class="nodyl9b9g"/><path fill="url(#iHSQ87b)" class="nodyl9b9g"/></g><path fill="url(#iies8Db)" class="nodyl9b9g"/><path fill="url(#isbHXkb)" class="nodyl9b9g"/><g filter="url(#i4Y9b1c)"><path class="aj_v2r-qr"/><path fill="url(#i2gwzxe)" class="m8hu2gblp"/><path fill="url(#i5Z3ade)" class="m8hu2gblp"/></g><g filter="url(#i8l180c)"><path fill="url(#iKvTZ5c)" class="tjxtjhwhc"/></g><path class="cgicp7b7j"/><path fill="url(#ioWFvoe)" class="qqa14yb1w"/><path fill="url(#iTxokPc)" class="sz6vfjbcc"/><path class="rcor55bjd"/><g filter="url(#i9fekMe)"><path class="wy8ankowc"/><path fill="url(#iwsDU8b)" class="mjvesmb5g"/></g><g filter="url(#ioaMgJe)"><path fill="url(#iv8aVjO)" class="tpam-ccyr"/></g><g filter="url(#iN0CWte)"><path fill="url(#idhSZMe)" class="fkmfzvbee"/></g><g filter="url(#icAWNOb)"><ellipse transform="rotate(-27.914 10.363 14.634)" class="y6i7p6lez"/><ellipse fill="url(#itIyl1c)" transform="rotate(-27.914 10.363 14.634)" class="ad1bj3btk"/></g><g filter="url(#iEklcZc)"><path stroke="url(#if7a8Nb)" class="u02_orb3o"/></g><g filter="url(#i4Ohhob)"><path stroke="url(#iifGnrd)" class="e7gkk5buy"/></g><g filter="url(#ijFcJme)"><circle fill="url(#i9juxjd)" class="o4lyf_5ag"/></g><g filter="url(#ibkZHAb)"><ellipse fill="url(#iqNN9kF)" class="rr3_lob0y"/></g><g filter="url(#iZvfv6d)"><ellipse fill="url(#iLujVNc)" class="msi-m1byb"/></g><g filter="url(#iLlWLOb)"><ellipse fill="url(#iheEDje)" class="bjt_hxbfh"/></g><g filter="url(#ia9BlMk)"><ellipse fill="url(#isZgRCc)" class="pp1fzcbiu"/></g><g filter="url(#iqHcqJD)"><ellipse fill="url(#i4LDEre)" class="svaglzbrc"/></g><defs><radialGradient id="iqg8yTG" cx="0" cy="0" r="1" gradientTransform="rotate(123.555 7.897 19.273)scale(3.6749 2.81742)" gradientUnits="userSpaceOnUse"><stop class="bo8yv-bcc"/><stop offset="1" class="qdylhtb9e"/></radialGradient><radialGradient id="iQVIwOe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.79688 1.78126 -1.89788 -2.98 29.152 23.595)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="vc--wpv5i"/><stop offset="1" class="xtx5iybhh"/></radialGradient><radialGradient id="iBCGBlb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.833 .75502 -.86782 -3.25623 5.23 15.783)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="i-t-pic6y"/><stop offset="1" class="bmkf76lfa"/></radialGradient><radialGradient id="iNx91oc" cx="0" cy="0" r="1" gradientTransform="rotate(-125.77 7.684 8.277)scale(3.58191 3.48949)" gradientUnits="userSpaceOnUse"><stop class="s6zfi5w0u"/><stop offset="1" class="vh2as1b-g"/></radialGradient><radialGradient id="iwcMIMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 4.82422 -6.44806 2.0049 24.387 14.283)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="o4_dd7bbg"/><stop offset=".907" class="ygkfiab9p"/></radialGradient><radialGradient id="int0hCb" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 -1.82812 1.40115 1.6287 24.116 15.856)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="ripo1ol5m"/><stop offset="1" class="gexi46btr"/></radialGradient><radialGradient id="iOJzmnb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51561 -2.50001 1.91885 -1.16329 6.152 16.657)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="dv112bb7v"/><stop offset="1" class="vcl8jlb9a"/></radialGradient><radialGradient id="ioFwvbU" cx="0" cy="0" r="1" gradientTransform="matrix(1.4144 -1.86368 1.70568 1.29449 23.946 16.302)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="vdsme1g2o"/><stop offset=".857" class="a7po69bqb"/></radialGradient><radialGradient id="i4326ql" cx="0" cy="0" r="1" gradientTransform="rotate(-142.148 15.037 5.674)scale(13.852 14.8537)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="yd15m2foq"/><stop offset=".826" class="mry6a4z4f"/></radialGradient><radialGradient id="iH4bnTp" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 16.09377 -3.4413 .54794 6.2 12.47)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="i051rv_lz"/><stop offset="1" class="pytrs5o3w"/></radialGradient><radialGradient id="iXulCSl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.71875 3.65625 0 10.523 13.85)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="cgegkgb5x"/><stop offset="1" class="ob7qo1brk"/></radialGradient><radialGradient id="iitsMVY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.02625 2.66699 0 19.48 13.809)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="blytpxb0y"/><stop offset="1" class="yqckwab_k"/></radialGradient><radialGradient id="iyw4nQd" cx="0" cy="0" r="1" gradientTransform="matrix(2.64062 -1.59375 1.26033 2.08819 17.507 10.262)" gradientUnits="userSpaceOnUse"><stop class="ghhmefbck"/><stop offset="1" class="xq45_ub8l"/></radialGradient><radialGradient id="iXrdrmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62498 -3.28126 4.56897 -2.26269 12.335 22.038)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="f9e_rybzl"/><stop offset="1" class="szao4j3dd"/></radialGradient><radialGradient id="iXdOXmd" cx="0" cy="0" r="1" gradientTransform="matrix(12.125 0 0 31.579 11.304 15.888)" gradientUnits="userSpaceOnUse"><stop offset=".966" class="pqyo8lb9u"/><stop offset=".992" class="xns6qxbzc"/></radialGradient><radialGradient id="ifBFQ6b" cx="0" cy="0" r="1" gradientTransform="matrix(-12.00007 11.56246 -10.46048 -10.85639 23.887 16.814)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="oijij4boh"/><stop offset="1" class="xo4b6qb3v"/></radialGradient><radialGradient id="isMN36b" cx="0" cy="0" r="1" gradientTransform="rotate(176.86 8.6 10.463)scale(12.5501 32.3756)" gradientUnits="userSpaceOnUse"><stop offset=".784" class="vchip2bvs"/><stop offset="1" class="urqzme3oh"/></radialGradient><radialGradient id="imAtemb" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.6562 -17.2158 0 14.84 14.372)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="qjyawonpb"/><stop offset="1" class="zrfuj9hzf"/></radialGradient><radialGradient id="iioYoMe" cx="0" cy="0" r="1" gradientTransform="rotate(91.647 -3.612 10.76)scale(5.69174 .80306)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="bks0ld69z"/><stop offset="1" class="if-nn2b7l"/></radialGradient><radialGradient id="i59wwwc" cx="0" cy="0" r="1" gradientTransform="matrix(.40632 10.62503 -.9433 .03607 22.48 9.002)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="ux_yq0b9s"/><stop offset="1" class="npyrhozum"/></radialGradient><radialGradient id="ibW8JUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.52885 7.9644 -1.22174 -.08113 24.67 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".551" class="qo6gcmbfr"/><stop offset="1" class="gax15acsl"/></radialGradient><radialGradient id="iBUj17b" cx="0" cy="0" r="1" gradientTransform="rotate(31.749 -29.738 42.82)scale(3.40312 2.63829)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="qyhe1g75t"/><stop offset="1" class="dbhb7obko"/></radialGradient><radialGradient id="ikdvQvX" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1658 1.36131 -1.1976 -2.78508 9.4 22.078)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="jt6hy6lan"/><stop offset="1" class="myb7nmbsf"/></radialGradient><radialGradient id="ilTRRvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.6929 -3.30064 0 14.852 23.154)" gradientUnits="userSpaceOnUse"><stop class="g2jr1acbg"/><stop offset="1" class="dw544eozv"/></radialGradient><radialGradient id="iEdVn1d" cx="0" cy="0" r="1" gradientTransform="rotate(156.024 12.066 5.894)scale(3.4607 1.9527)" gradientUnits="userSpaceOnUse"><stop offset=".291" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iPqFw2T" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -2 4.24558 1.39308 6.043 9.907)" gradientUnits="userSpaceOnUse"><stop class="aoo0obp8f"/><stop offset="1" class="xn_9mrb9a"/></radialGradient><radialGradient id="iDKbwdb" cx="0" cy="0" r="1" gradientTransform="rotate(151.208 3.18 3.6)scale(2.06818 1.32908)" gradientUnits="userSpaceOnUse"><stop class="cy3fw4bfy"/><stop offset="1" class="cw63m1bfl"/></radialGradient><radialGradient id="i99Ax8d" cx="0" cy="0" r="1" gradientTransform="rotate(146.262 4.265 11.38)scale(6.87582 11.899)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="uuz5kdbdb"/><stop offset="1" class="qh2sebchq"/></radialGradient><radialGradient id="inMchle" cx="0" cy="0" r="1" gradientTransform="matrix(.82428 .4278 -.38205 .73613 19.861 20.864)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="mzlqetbfg"/><stop offset="1" class="v9111y7za"/></radialGradient><radialGradient id="iHSQ87b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04688 -2.69196 0 14.543 19.314)" gradientUnits="userSpaceOnUse"><stop offset=".478" class="tk12yhu0n"/><stop offset="1" class="fykpid82j"/></radialGradient><radialGradient id="iies8Db" cx="0" cy="0" r="1" gradientTransform="matrix(-1 .73438 -.7444 -1.01363 21.574 21.064)" gradientUnits="userSpaceOnUse"><stop class="jk3dy6bqz"/><stop offset=".677" class="qesf29b5z"/></radialGradient><radialGradient id="isbHXkb" cx="0" cy="0" r="1" gradientTransform="rotate(118.511 -1.3 13.58)scale(.72015 .94161)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="zvx0v3k-f"/><stop offset="1" class="e3sjunb7v"/></radialGradient><radialGradient id="i5Z3ade" cx="0" cy="0" r="1" gradientTransform="matrix(-.87024 0 0 -.5 15.741 18.84)" gradientUnits="userSpaceOnUse"><stop class="g02nitb7a"/><stop offset="1" class="xx32jkb4r"/></radialGradient><radialGradient id="ioWFvoe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 2.04688 -1.65328 -1.50184 19.757 14.543)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="e0-rnofaa"/><stop offset=".949" class="azqdyxbky"/></radialGradient><radialGradient id="iTxokPc" cx="0" cy="0" r="1" gradientTransform="rotate(132.252 2.645 9.872)scale(2.74867 2.22012)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="e0-rnofaa"/><stop offset=".949" class="azqdyxbky"/></radialGradient><radialGradient id="iwsDU8b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.895 2.96)scale(.70572 .9716)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="itIyl1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.01434 -.91615 1.10125 -.01724 10.335 15.218)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9juxjd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59013 0 0 -5.13281 7.453 7.384)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="tlnk369mx"/><stop offset="1" class="jccegnx7f"/></radialGradient><radialGradient id="iqNN9kF" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70655 0 0 -4.25781 10.367 7.384)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="hkvpugxoe"/><stop offset="1" class="ty3_ks7kr"/></radialGradient><radialGradient id="iLujVNc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88325 0 0 -4.05381 14.241 7.384)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="ypx_bsb1m"/><stop offset=".911" class="frsmpkb3r"/></radialGradient><radialGradient id="iheEDje" cx="0" cy="0" r="1" gradientTransform="matrix(-2.64284 0 0 -3.60682 24.464 7.384)" gradientUnits="userSpaceOnUse"><stop offset=".159" class="vc--wpv5i"/><stop offset="1" class="jccegnx7f"/></radialGradient><radialGradient id="isZgRCc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96513 0 0 -4.04668 21.615 7.384)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="vc--wpv5i"/><stop offset=".699" class="hngzuob8m"/></radialGradient><radialGradient id="i4LDEre" cx="0" cy="0" r="1" gradientTransform="matrix(-2.83795 0 0 -2.70327 17.982 7.384)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="vc--wpv5i"/><stop offset=".912" class="k03m-pbsr"/></radialGradient><filter id="iivjzXd" width="23" height="22.065" x="5.512" y="1.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.0901961 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24231"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.384314 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24231" result="effect2_innerShadow_3987_24231"/></filter><filter id="iHTzivO" width="4.573" height="4.473" x="24.879" y="22.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.47451 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24231"/></filter><filter id="ifpy1je" width="6.366" height="6.266" x="2.848" y="12.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.454902 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24231"/></filter><filter id="iS99sDd" width="5.172" height="5.172" x="3.395" y="13.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".25"/></filter><filter id="ixOh2pb" width="5.443" height="5.443" x="20.923" y="13.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".25"/></filter><filter id="iqS3hfd" width="5.126" height="3.313" x="7.413" y="9.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.380392 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24231"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.360784 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24231" result="effect2_innerShadow_3987_24231"/></filter><filter id="i1PoU1d" width="5.176" height="3.213" x="17.253" y="9.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.392157 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24231"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.345098 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24231" result="effect2_innerShadow_3987_24231"/></filter><filter id="i0zYdue" width="17.957" height="5.249" x="5.899" y="5.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".5"/></filter><filter id="iQNXcQy" width="21.719" height="5.32" x="4.268" y="4.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.615686 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24231"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.564706 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24231" result="effect2_innerShadow_3987_24231"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.839216 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_24231" result="effect3_innerShadow_3987_24231"/></filter><filter id="iiP4ihd" width="13.71" height="3.92" x="7.998" y="19.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.576471 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24231"/></filter><filter id="i4Y9b1c" width="3.627" height="5.953" x="13.158" y="13.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.396078 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24231"/></filter><filter id="i8l180c" width="3.917" height="5.653" x="12.894" y="14.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".05"/></filter><filter id="i9fekMe" width="1.295" height="1.126" x="17.605" y="14.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".05"/></filter><filter id="ioaMgJe" width="1.316" height="1.358" x="19.259" y="14.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".1"/></filter><filter id="iN0CWte" width="1.487" height="1.587" x="11.088" y="14.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".1"/></filter><filter id="icAWNOb" width="1.522" height="1.136" x="9.602" y="14.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".05"/></filter><filter id="iEklcZc" width="4.836" height="2.588" x="7.659" y="10.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".3"/></filter><filter id="i4Ohhob" width="4.75" height="2.479" x="17.434" y="10.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".25"/></filter><filter id="ijFcJme" width="4.203" height="4.203" x="4.363" y="5.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".25"/></filter><filter id="ibkZHAb" width="5.18" height="5.281" x="6.642" y="4.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".375"/></filter><filter id="iZvfv6d" width="5.42" height="5.1" x="10.321" y="4.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".375"/></filter><filter id="iLlWLOb" width="5.093" height="4.703" x="20.809" y="5.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".375"/></filter><filter id="ia9BlMk" width="5.531" height="5.094" x="17.605" y="4.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".375"/></filter><filter id="iqHcqJD" width="5.246" height="5.019" x="14.12" y="4.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24231" stdDeviation=".375"/></filter><linearGradient id="ifvKxOb" x1="17.34" x2="25.949" y1="1.968" y2="24.814" gradientUnits="userSpaceOnUse"><stop class="qt739_5fv"/><stop offset="1" class="qp19kfbuy"/></linearGradient><linearGradient id="iX3Iv6c" x1="16.512" x2="16.512" y1="1.968" y2="4.814" gradientUnits="userSpaceOnUse"><stop class="om0t3ze-i"/><stop offset="1" class="c56mphbsh"/></linearGradient><linearGradient id="iPyXFVb" x1="19.911" x2="11.047" y1="22.173" y2="22.173" gradientUnits="userSpaceOnUse"><stop class="ms1kw7o6c"/><stop offset="1" class="ljeo-0znr"/></linearGradient><linearGradient id="i2gwzxe" x1="16.194" x2="14.21" y1="16.195" y2="16.773" gradientUnits="userSpaceOnUse"><stop offset=".248" class="dg3we74bv"/><stop offset="1" class="osoedmn0g"/></linearGradient><linearGradient id="iKvTZ5c" x1="14.852" x2="14.852" y1="14.388" y2="16.748" gradientUnits="userSpaceOnUse"><stop offset=".172" class="e_pwhebtm"/><stop offset="1" class="o12opibni"/></linearGradient><linearGradient id="iv8aVjO" x1="20.34" x2="19.755" y1="14.905" y2="15.266" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idhSZMe" x1="12.246" x2="11.665" y1="14.911" y2="15.27" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="if7a8Nb" x1="11.686" x2="8.459" y1="10.965" y2="12.115" gradientUnits="userSpaceOnUse"><stop class="h_eag5bdx"/><stop offset="1" class="mqh-33bsa"/></linearGradient><linearGradient id="iifGnrd" x1="21.824" x2="17.465" y1="11.954" y2="10.892" gradientUnits="userSpaceOnUse"><stop class="er0tgp7sq"/><stop offset="1" class="jj3uc_bgu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:santa-claus-medium" /></template>
<style>
.a7po69bqb {
  stop-color: var(--svg-color--ab7b70, #AB7B70);
}

.ad1bj3btk {
  cx: 10.363px;
  cy: 14.634px;
  rx: 0.722px;
  ry: 0.366px;
}

.aj_v2r-qr {
  fill: var(--svg-color--a67e6c, #A67E6C);
  d: path("M14.871 14.439a.5.5 0 0 0-.472.341l-1.137 3.456c-.063.177-.182.643-.032 1.03c.186.48.688.623 1.625.626h.032c.936-.003 1.44-.146 1.625-.625c.15-.388.03-.854-.032-1.031l-1.137-3.456a.5.5 0 0 0-.472-.341");
}

.aoo0obp8f {
  stop-color: var(--svg-color--a58fa6, #A58FA6);
}

.azqdyxbky {
  stop-color: var(--svg-color--644843, #644843);
}

.bjt_hxbfh {
  cx: 23.355px;
  cy: 7.384px;
  rx: 1.797px;
  ry: 1.602px;
}

.bks0ld69z {
  stop-color: var(--svg-color--d5c8d1, #D5C8D1);
}

.blytpxb0y {
  stop-color: var(--svg-color--ab7771, #AB7771);
}

.bmkf76lfa {
  stop-color: var(--svg-color--7f604f, #7F604F);
}

.bo8yv-bcc {
  stop-color: var(--svg-color--f8eff8, #F8EFF8);
}

.btdo69biz {
  fill: var(--svg-color--916853, #916853);
  fill-rule: evenodd;
  d: path("M17.371 17.113a.425.425 0 0 0 .013.601a3.3 3.3 0 0 0 2.341.923a.425.425 0 1 0-.017-.85a2.45 2.45 0 0 1-1.736-.686a.425.425 0 0 0-.6.012");
}

.c56mphbsh {
  stop-color: var(--svg-color--fe404f, #FE404F);
  stop-opacity: 0;
}

.cgegkgb5x {
  stop-color: var(--svg-color--8c5d62, #8C5D62);
}

.cgicp7b7j {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.279 13.525c1.219 0 2.249.723 2.529 1.859a.512.512 0 0 1-.5.636h-4.165a.43.43 0 0 1-.424-.508c.235-1.196 1.287-1.987 2.56-1.987m-8.818 0c-1.212 0-2.285.734-2.564 1.863a.51.51 0 0 0 .497.632h4.19a.427.427 0 0 0 .421-.504c-.233-1.19-1.287-1.991-2.544-1.991");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cw63m1bfl {
  stop-color: var(--svg-color--e5e1e2, #E5E1E2);
  stop-opacity: 0;
}

.cy3fw4bfy {
  stop-color: var(--svg-color--e5e1e2, #E5E1E2);
}

.d2upmobvt {
  fill: var(--svg-color--7f5b49, #7F5B49);
  fill-rule: evenodd;
  d: path("M12.299 17.113a.425.425 0 0 1-.013.601a3.3 3.3 0 0 1-2.341.923a.425.425 0 1 1 .016-.85a2.45 2.45 0 0 0 1.737-.686a.425.425 0 0 1 .6.012");
}

.dbhb7obko {
  stop-color: var(--svg-color--c4bccd, #C4BCCD);
  stop-opacity: 0;
}

.dg3we74bv {
  stop-color: var(--svg-color--cfa58d, #CFA58D);
}

.dv112bb7v {
  stop-color: var(--svg-color--825a5b, #825A5B);
}

.dw544eozv {
  stop-color: var(--svg-color--dbd4e1, #DBD4E1);
  stop-opacity: 0;
}

.e_pwhebtm {
  stop-color: var(--svg-color--a57d6a, #A57D6A);
}

.e-rjpbc3s {
  d: path("M12.246 2.282c-3.656.32-5.094 2.594-5.578 3.68l-.656 2.352l17.297-1V16l2.78 7.531h1.923c-.25-3.375 0-9.125 0-12.656c-.063-3.047-.209-5.567-3.149-7.492C21.56 1.22 13.34 2.142 12.246 2.282");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3sjunb7v {
  stop-color: var(--svg-color--f4e9e6, #F4E9E6);
  stop-opacity: 0;
}

.e7gkk5buy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.184 11.001c.63-.083 2.162-.01 3.25.953");
}

.er0tgp7sq {
  stop-color: var(--svg-color--a29da9, #A29DA9);
}

.f9e_rybzl {
  stop-color: var(--svg-color--8b5b5e, #8B5B5E);
}

.fkmfzvbee {
  d: path("M12.375 15.387c0-.534-.435-.891-.552-.999l-.535.518l.33.67z");
}

.frsmpkb3r {
  stop-color: var(--svg-color--bdbcbf, #BDBCBF);
}

.ft5dv1b6b {
  fill: none;
}

.fykpid82j {
  stop-color: var(--svg-color--d5c5c2, #D5C5C2);
  stop-opacity: 0;
}

.g02nitb7a {
  stop-color: var(--svg-color--caa18d, #CAA18D);
}

.g2jr1acbg {
  stop-color: var(--svg-color--cac2d3, #CAC2D3);
}

.gax15acsl {
  stop-color: var(--svg-color--e7e3e6, #E7E3E6);
  stop-opacity: 0;
}

.gexi46btr {
  stop-color: var(--svg-color--c59a87, #C59A87);
  stop-opacity: 0;
}

.ghhmefbck {
  stop-color: var(--svg-color--a88179, #A88179);
}

.h_eag5bdx {
  stop-color: var(--svg-color--91889b, #91889B);
}

.hkvpugxoe {
  stop-color: var(--svg-color--e5e1e9, #E5E1E9);
}

.hngzuob8m {
  stop-color: var(--svg-color--e2e1e3, #E2E1E3);
}

.hrltht9-f {
  d: path("M6.324 19.564c-.65-2.9-.396-8.646-.187-11.157h17.5c.156 1.813.375 6.438 0 10.438s-5.907 4.667-8.625 4.5c-2.625-.052-8.038-.881-8.688-3.781");
}

.i-t-pic6y {
  stop-color: var(--svg-color--906864, #906864);
}

.i051rv_lz {
  stop-color: var(--svg-color--9a7167, #9A7167);
}

.if-nn2b7l {
  stop-color: var(--svg-color--d5c8d1, #D5C8D1);
  stop-opacity: 0;
}

.iheo8cbur {
  cx: 5.98px;
  cy: 15.97px;
  r: 3.133px;
}

.j6cn8wbef {
  d: path("M6.809 9.072c-.125 1.64-.416 5.66-.141 9.46c.272 3.768 5.503 3.67 8.15 3.14v-.015l.034.007l.035-.007v.014c2.647.53 7.878.629 8.15-3.139c.275-3.8-.015-7.82-.14-9.46l1.773-.743c0 2.055-.163 4.963-.238 6.11c-.076 1.146-.254 4.71-.02 6.968c.277 2.665.055 5.47-2.36 7.032c-2.379 1.54-5.578 1.592-7.165 1.593h-.069c-1.587 0-4.786-.053-7.166-1.593c-2.414-1.563-2.636-4.367-2.36-7.032c.235-2.257.057-5.822-.019-6.968c-.075-1.147-.238-4.055-.238-6.11z");
}

.jccegnx7f {
  stop-color: var(--svg-color--a8a4ad, #A8A4AD);
}

.jj3uc_bgu {
  stop-color: var(--svg-color--8a8391, #8A8391);
}

.jk3dy6bqz {
  stop-color: var(--svg-color--faf7fa, #FAF7FA);
}

.jt6hy6lan {
  stop-color: var(--svg-color--a399ad, #A399AD);
}

.k03m-pbsr {
  stop-color: var(--svg-color--d4d3d5, #D4D3D5);
}

.k3smf8bjh {
  fill: var(--svg-color--5d333f, #5D333F);
  d: path("M9.897 9.786a.55.55 0 0 0-.553 0a1.624 1.624 0 1 1 0-2.805a.55.55 0 0 0 .553 0a1.62 1.62 0 0 1 1.546-.05c.36.18.892.18 1.251 0a1.62 1.62 0 0 1 1.427-.013c.392.188 1.026.188 1.419 0a1.62 1.62 0 0 1 1.424.011c.364.182.911.182 1.276 0a1.62 1.62 0 0 1 1.569.067a.56.56 0 0 0 .577 0a1.624 1.624 0 1 1 0 2.775a.56.56 0 0 0-.578 0a1.62 1.62 0 0 1-1.568.068a1.56 1.56 0 0 0-1.276 0a1.62 1.62 0 0 1-1.424.011c-.393-.188-1.027-.188-1.42 0a1.62 1.62 0 0 1-1.426-.012c-.36-.18-.891-.18-1.25 0a1.62 1.62 0 0 1-1.547-.052");
}

.l2ceykibm {
  cx: 23.744px;
  cy: 15.974px;
  r: 3.133px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljeo-0znr {
  stop-color: var(--svg-color--e2dde8, #E2DDE8);
}

.lstyhqihv {
  d: path("M8.255 9.249a.74.74 0 0 0-.736 0a2.16 2.16 0 1 1 0-3.73a.74.74 0 0 0 .736 0a2.15 2.15 0 0 1 1.09-.295c.348 0 .675.082.966.227c.478.239 1.185.239 1.663 0c.29-.145.618-.227.966-.227c.333 0 .649.075.93.21c.523.25 1.366.25 1.888 0a2.16 2.16 0 0 1 1.894.015c.484.242 1.212.242 1.696 0a2.16 2.16 0 0 1 2.086.09a.75.75 0 0 0 .768 0a2.16 2.16 0 1 1 0 3.69a.75.75 0 0 0-.768 0a2.15 2.15 0 0 1-1.123.315a2.16 2.16 0 0 1-.963-.225c-.484-.242-1.212-.242-1.696 0a2.16 2.16 0 0 1-1.894.015c-.522-.25-1.365-.25-1.887 0a2.16 2.16 0 0 1-1.897-.017c-.478-.239-1.185-.239-1.663 0c-.29.145-.618.227-.965.227a2.15 2.15 0 0 1-1.091-.295");
}

.m8hu2gblp {
  d: path("M14.871 14.439a.5.5 0 0 0-.472.341l-1.137 3.456c-.063.177-.182.643-.032 1.03c.186.48.688.623 1.625.626h.032c.936-.003 1.44-.146 1.625-.625c.15-.388.03-.854-.032-1.031l-1.137-3.456a.5.5 0 0 0-.472-.341");
}

.mjvesmb5g {
  d: path("M18.77 14.267c.118.159-.13.352-.412.563s-.49.36-.61.2c-.118-.158.014-.458.296-.668s.607-.254.725-.095");
}

.mqh-33bsa {
  stop-color: var(--svg-color--857a91, #857A91);
}

.mry6a4z4f {
  stop-color: var(--svg-color--9a7462, #9A7462);
}

.ms1kw7o6c {
  stop-color: var(--svg-color--e8e3eb, #E8E3EB);
}

.msi-m1byb {
  cx: 13.031px;
  cy: 7.384px;
  rx: 1.96px;
  ry: 1.8px;
}

.myb7nmbsf {
  stop-color: var(--svg-color--b2aab9, #B2AAB9);
  stop-opacity: 0;
}

.mzlqetbfg {
  stop-color: var(--svg-color--d4c5bd, #D4C5BD);
}

.nodyl9b9g {
  d: path("M13.235 19.678h3.235c1.094 0 1.883.719 2.313 1.11l.005.005l.139.127c.184.17.309.284.433.373c.09.065.275.117.358-.05a1.05 1.05 0 0 1 1.888.919c-.62 1.31-2.526 1.592-3.65.78a5 5 0 0 1-.582-.518c-.406-.402-.793-.786-1.438-.786H13.77c-.646 0-1.033.384-1.438.786c-.182.18-.368.364-.582.519c-1.125.81-3.03.528-3.651-.781a1.05 1.05 0 0 1 1.888-.919c.083.167.269.115.358.05c.124-.09.249-.204.434-.373l.138-.127l.005-.005c.43-.391 1.22-1.11 2.313-1.11");
}

.npyrhozum {
  stop-color: var(--svg-color--bc9c89, #BC9C89);
  stop-opacity: 0;
}

.o12opibni {
  stop-color: var(--svg-color--a57d6a, #A57D6A);
  stop-opacity: 0;
}

.o4_dd7bbg {
  stop-color: var(--svg-color--bc8d7f, #BC8D7F);
}

.o4lyf_5ag {
  cx: 6.465px;
  cy: 7.384px;
  r: 1.602px;
}

.ob7qo1brk {
  stop-color: var(--svg-color--8c5d62, #8C5D62);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oijij4boh {
  stop-color: var(--svg-color--eceaee, #ECEAEE);
}

.om0t3ze-i {
  stop-color: var(--svg-color--e15157, #E15157);
}

.osoedmn0g {
  stop-color: var(--svg-color--b38976, #B38976);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp1fzcbiu {
  cx: 20.371px;
  cy: 7.384px;
  rx: 2.016px;
  ry: 1.797px;
}

.pqyo8lb9u {
  stop-color: var(--svg-color--82554c, #82554C);
  stop-opacity: 0;
}

.pytrs5o3w {
  stop-color: var(--svg-color--9a7167, #9A7167);
  stop-opacity: 0;
}

.q8nrffr1s {
  fill: var(--svg-color--dfdbe4, #DFDBE4);
  d: path("m11.87 21.69l.923-1.052h3.89l1.2.948c-.43.98-1.625 1.685-3.03 1.685c-1.356 0-2.515-.655-2.983-1.58");
}

.qdylhtb9e {
  stop-color: var(--svg-color--cbbdcc, #CBBDCC);
}

.qesf29b5z {
  stop-color: var(--svg-color--faf7fa, #FAF7FA);
  stop-opacity: 0;
}

.qh2sebchq {
  stop-color: var(--svg-color--bdb9c0, #BDB9C0);
}

.qjyawonpb {
  stop-color: var(--svg-color--c1b5cd, #C1B5CD);
  stop-opacity: 0;
}

.qo6gcmbfr {
  stop-color: var(--svg-color--e5dede, #E5DEDE);
}

.qp19kfbuy {
  stop-color: var(--svg-color--e72d5f, #E72D5F);
}

.qqa14yb1w {
  d: path("M18.892 13.915a1.666 1.666 0 0 1 1.606 2.105h-3.219a1.7 1.7 0 0 1-.06-.44c0-.916.75-1.665 1.673-1.665");
}

.qt739_5fv {
  stop-color: var(--svg-color--ff414b, #FF414B);
}

.qyhe1g75t {
  stop-color: var(--svg-color--9c90aa, #9C90AA);
}

.rcor55bjd {
  fill: var(--svg-color--000, #000);
  d: path("M17.939 15.58a.95.95 0 0 1 .954-.953a.95.95 0 0 1 .954.954a.94.94 0 0 1-.106.439h-1.689a.86.86 0 0 1-.113-.44m-6.127.003a.944.944 0 0 0-.948-.949a.944.944 0 0 0-.948.948c0 .159.037.31.105.437h1.678a.94.94 0 0 0 .113-.436");
}

.ripo1ol5m {
  stop-color: var(--svg-color--c59a87, #C59A87);
}

.rr3_lob0y {
  cx: 9.231px;
  cy: 7.384px;
  rx: 1.84px;
  ry: 1.891px;
}

.s6zfi5w0u {
  stop-color: var(--svg-color--895667, #895667);
}

.smvwoqxye {
  cx: 5.98px;
  cy: 15.97px;
  r: 2.086px;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.svaglzbrc {
  cx: 16.743px;
  cy: 7.384px;
  rx: 1.873px;
  ry: 1.759px;
}

.sz6vfjbcc {
  d: path("M10.863 13.927a1.656 1.656 0 0 0-1.596 2.093h3.2c.037-.143.06-.287.06-.437a1.667 1.667 0 0 0-1.664-1.656");
}

.szao4j3dd {
  stop-color: var(--svg-color--8b5b5e, #8B5B5E);
  stop-opacity: 0;
}

.t53q3e-6a {
  fill: var(--svg-color--7b7481, #7B7481);
  fill-rule: evenodd;
  d: path("M11.582 12.17c-1.378-.13-2.28.43-2.538.643a.875.875 0 1 1-1.112-1.35c.533-.44 1.88-1.219 3.814-1.036a.875.875 0 1 1-.164 1.742");
}

.tjxtjhwhc {
  d: path("M14.852 14.388a.54.54 0 0 0-.511.342l-1.234 3.455c-.068.177-.197.644-.034 1.031c.2.48.746.622 1.762.625h.034c1.017-.003 1.562-.146 1.763-.625c.163-.387.034-.854-.034-1.03l-1.234-3.456a.54.54 0 0 0-.512-.342");
}

.tk12yhu0n {
  stop-color: var(--svg-color--b78b81, #B78B81);
}

.tlnk369mx {
  stop-color: var(--svg-color--cdc9d1, #CDC9D1);
}

.tpam-ccyr {
  d: path("M20.376 15.36a1.57 1.57 0 0 0-.432-.862l-.485.532l.22.425z");
}

.ts2a3n5mb {
  fill: var(--svg-color--87004d, #87004D);
  d: path("m11.87 21.663l.923-1.052h3.89l1.2.948c-.43.98-1.625 1.685-3.03 1.685c-1.356 0-2.515-.655-2.983-1.581");
}

.ty3_ks7kr {
  stop-color: var(--svg-color--a8a6aa, #A8A6AA);
}

.u02_orb3o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.46 12.115c.382-.369 1.565-1.08 3.235-.978");
}

.uj5j0zbkb {
  fill: var(--svg-color--969398, #969398);
  fill-rule: evenodd;
  d: path("M18.21 12.17c1.377-.13 2.28.43 2.537.643a.875.875 0 1 0 1.113-1.35c-.533-.44-1.88-1.219-3.814-1.036a.875.875 0 0 0 .164 1.742");
}

.urqzme3oh {
  stop-color: var(--svg-color--b1afb3, #B1AFB3);
}

.uuz5kdbdb {
  stop-color: var(--svg-color--e4dfea, #E4DFEA);
  stop-opacity: 0;
}

.ux_yq0b9s {
  stop-color: var(--svg-color--bc9c89, #BC9C89);
}

.v9111y7za {
  stop-color: var(--svg-color--d4c5bd, #D4C5BD);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vchip2bvs {
  stop-color: var(--svg-color--b1afb3, #B1AFB3);
  stop-opacity: 0;
}

.vcl8jlb9a {
  stop-color: var(--svg-color--82595e, #82595E);
}

.vdsme1g2o {
  stop-color: var(--svg-color--bb8f7e, #BB8F7E);
}

.vh2as1b-g {
  stop-color: var(--svg-color--895667, #895667);
  stop-opacity: 0;
}

.whn9jdb7h {
  cx: 23.645px;
  cy: 15.974px;
  r: 2.221px;
}

.wy8ankowc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.77 14.267c.118.159-.13.352-.412.563s-.49.36-.61.2c-.118-.158.014-.458.296-.668s.607-.254.725-.095");
}

.xn_9mrb9a {
  stop-color: var(--svg-color--a58fa6, #A58FA6);
  stop-opacity: 0;
}

.xns6qxbzc {
  stop-color: var(--svg-color--82554c, #82554C);
}

.xo4b6qb3v {
  stop-color: var(--svg-color--cac2d2, #CAC2D2);
}

.xq45_ub8l {
  stop-color: var(--svg-color--a88179, #A88179);
  stop-opacity: 0;
}

.xtx5iybhh {
  stop-color: var(--svg-color--ebdee4, #EBDEE4);
  stop-opacity: 0;
}

.xx32jkb4r {
  stop-color: var(--svg-color--caa18d, #CAA18D);
  stop-opacity: 0;
}

.y680a7f1p {
  fill: var(--svg-color--cdcccd, #CDCCCD);
  d: path("M8.255 9.249a.74.74 0 0 0-.736 0a2.16 2.16 0 1 1 0-3.73a.74.74 0 0 0 .736 0a2.15 2.15 0 0 1 1.09-.295c.348 0 .675.082.966.227c.478.239 1.185.239 1.663 0c.29-.145.618-.227.966-.227c.333 0 .649.075.93.21c.523.25 1.366.25 1.888 0a2.16 2.16 0 0 1 1.894.015c.484.242 1.212.242 1.696 0a2.16 2.16 0 0 1 2.086.09a.75.75 0 0 0 .768 0a2.16 2.16 0 1 1 0 3.69a.75.75 0 0 0-.768 0a2.15 2.15 0 0 1-1.123.315a2.16 2.16 0 0 1-.963-.225c-.484-.242-1.212-.242-1.696 0a2.16 2.16 0 0 1-1.894.015c-.522-.25-1.365-.25-1.887 0a2.16 2.16 0 0 1-1.897-.017c-.478-.239-1.185-.239-1.663 0c-.29.145-.618.227-.965.227a2.15 2.15 0 0 1-1.091-.295");
}

.y6i7p6lez {
  cx: 10.363px;
  cy: 14.634px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.722px;
  ry: 0.366px;
}

.y8d4eh7kx {
  cx: 27.016px;
  cy: 24.782px;
  r: 2.137px;
}

.yd15m2foq {
  stop-color: var(--svg-color--c99a82, #C99A82);
}

.ygkfiab9p {
  stop-color: var(--svg-color--a37178, #A37178);
}

.ypx_bsb1m {
  stop-color: var(--svg-color--fefcff, #FEFCFF);
}

.yqckwab_k {
  stop-color: var(--svg-color--ab7771, #AB7771);
  stop-opacity: 0;
}

.zrfuj9hzf {
  stop-color: var(--svg-color--9783ab, #9783AB);
}

.zvx0v3k-f {
  stop-color: var(--svg-color--f4e9e6, #F4E9E6);
}

</style>
