<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ind4IAb)"><path fill="url(#iMTpAue)" class="t_227-ttg"/></g><path fill="url(#iLnan0m)" class="z8-obfb5z"/><path fill="url(#iPuY4Ee)" class="z8-obfb5z"/><path fill="url(#iFZQm4J)" class="z8-obfb5z"/><g filter="url(#iIrgDRc)"><path stroke="url(#ixjj3CB)" class="mg-49j6uq"/></g><g filter="url(#iCZY78d)"><path fill="url(#iagCdzk)" class="poctzgb6q"/><path fill="url(#it1AhGb)" class="poctzgb6q"/><path fill="url(#i6N0fCe)" class="poctzgb6q"/></g><path fill="url(#inuUcqd)" class="jnda8ue6n"/><path fill="url(#ixv6R3d)" class="jnda8ue6n"/><path fill="url(#iGuIAve)" class="jnda8ue6n"/><path fill="url(#isOnyGm)" class="qc7b67bho"/><path fill="url(#iwOC9CA)" class="qc7b67bho"/><path fill="url(#iAp0Dsc)" class="qc7b67bho"/><path fill="url(#iQh0uDd)" class="wq7u4cbcv"/><path fill="url(#ivFydlc)" class="wq7u4cbcv"/><path fill="url(#iZ7Ezoc)" class="yn3_d1kor"/><g filter="url(#iB4QuUc)"><path fill="url(#idoJNne)" class="vdijrub5w"/><path fill="url(#iiFbLce)" class="vdijrub5w"/><path fill="url(#iU38Rsc)" class="vdijrub5w"/><path fill="url(#ivD1Nvc)" class="vdijrub5w"/></g><g filter="url(#iEmZH9b)"><path fill="url(#iDwoUwg)" class="ymxdkdb7x"/><path fill="url(#ihRtYae)" class="ymxdkdb7x"/><path fill="url(#iI3fdeP)" class="ymxdkdb7x"/><path fill="url(#iSp94yc)" class="ymxdkdb7x"/></g><path fill="url(#i6lBBHN)" class="jj0hsqwwd"/><g filter="url(#iVYO5oN)"><path fill="url(#isW2xDb)" class="tbnk9dbuh"/><path fill="url(#isxz6wd)" class="tbnk9dbuh"/></g><g filter="url(#iaWXIFK)"><path fill="url(#iDQIs3S)" class="ha0cprbfd"/></g><path fill="url(#iFfcr8c)" class="rxedppbdt"/><path clip-rule="evenodd" class="ltxfo2b8y"/><path fill="url(#i29308b)" clip-rule="evenodd" class="pl14swbzk"/><g filter="url(#i2Bflze)"><path fill="url(#iaA0PIb)" class="pc11gtbiw"/><path fill="url(#i73vccd)" class="pc11gtbiw"/><path fill="url(#ii7PHmy)" class="pc11gtbiw"/><path fill="url(#iJGjnGb)" class="pc11gtbiw"/><path fill="url(#int0Ssc)" class="pc11gtbiw"/></g><g filter="url(#ireLElD)"><path fill="url(#inO64Xc)" class="zunmvpbih"/><path fill="url(#i8NIE5d)" class="zunmvpbih"/><path fill="url(#iXxVFVj)" class="zunmvpbih"/><path fill="url(#itYMGVd)" class="zunmvpbih"/><path fill="url(#ia70ICc)" class="zunmvpbih"/></g><path fill="url(#ijWcnxb)" class="erpr8o31c"/><path fill="url(#iZcoCud)" class="ti-ljlb_r"/><g filter="url(#iECEwVb)"><path stroke="url(#iTUotvA)" class="n0hwrab5r"/></g><g filter="url(#i5xVc9c)"><path stroke="url(#iqSrbzc)" class="b57h8db-a"/></g><g filter="url(#iqkViff)"><path stroke="url(#iQcVn3d)" class="m-c6wr06g"/></g><g filter="url(#i2tsqWb)"><path stroke="url(#itVwuNb)" class="cjdo17bjb"/></g><g filter="url(#ib0AuTc)"><path stroke="url(#inF0x9b)" class="dhahslrdx"/></g><g filter="url(#iDEl48k)"><path stroke="url(#iXgQtZb)" class="bdiqbojjb"/></g><path fill="url(#iiQF4pe)" class="yj5fjmbpq"/><path fill="url(#i5gSlMe)" class="c10fbhxdh"/><path fill="url(#iznfz7d)" class="c10fbhxdh"/><path fill="url(#i5gSlMe)" class="c10fbhxdh"/><path fill="url(#iznfz7d)" class="c10fbhxdh"/><g filter="url(#iPHecgd)"><path fill="url(#iszMxrc)" class="er2--pskp"/></g><path fill="url(#ievUoyc)" class="er2--pskp"/><path fill="url(#iaO8Ktc)" class="er2--pskp"/><path fill="url(#iGFXtKc)" class="er2--pskp"/><path fill="url(#ikoGewc)" class="er2--pskp"/><path fill="url(#i64eGmc)" class="er2--pskp"/><path fill="url(#irx1Lje)" class="er2--pskp"/><path fill="url(#iC2MSXb)" class="er2--pskp"/><path fill="url(#iC07wtc)" class="er2--pskp"/><g filter="url(#iniMHob)"><path class="injaeqkfm"/></g><g filter="url(#ibyLlUd)"><path fill="url(#iNkq8Ub)" class="umdq1abts"/><path fill="url(#iHkhPbe)" class="umdq1abts"/><path fill="url(#i5bwdLb)" class="umdq1abts"/><path fill="url(#ik7UBfc)" class="umdq1abts"/></g><path fill="url(#imLmiad)" class="umdq1abts"/><path fill="url(#ieH71Pd)" class="umdq1abts"/><g filter="url(#ibglpZn)"><path stroke="url(#iLhZqlb)" class="jzwmcqb4a"/></g><path fill="url(#i1Sn7wb)" class="d2b2d_b1d"/><g filter="url(#i5MJX4d)"><path fill="url(#ihxtO7d)" class="b1zho21tu"/><path fill="url(#i5infhc)" class="b1zho21tu"/><path fill="url(#iCfp8bd)" class="b1zho21tu"/><path fill="url(#iu5OLYd)" class="b1zho21tu"/><path fill="url(#i1tg0Be)" class="b1zho21tu"/></g><g filter="url(#iyMfMUd)"><path class="l6nfqlbiq"/></g><g filter="url(#iDE67Ud)"><path class="d65kawhah"/></g><g filter="url(#ivAulke)"><path fill="url(#ifBvudc)" class="y70g-pbhj"/><path fill="url(#iFq1nPd)" class="y70g-pbhj"/></g><g filter="url(#isYCIve)"><path fill="url(#iuTTxhe)" class="mw9yznfqi"/><path fill="url(#iZh2Hic)" class="mw9yznfqi"/><path fill="url(#ihTWUPb)" class="mw9yznfqi"/><path fill="url(#ij9M28b)" class="mw9yznfqi"/><path fill="url(#iXnkvVc)" class="mw9yznfqi"/><path fill="url(#iTOthbe)" class="mw9yznfqi"/></g><path class="rjprz9fyp"/><path fill="url(#igIDXZc)" class="e3q65yqob"/><path class="y998tobym"/><g filter="url(#iypd5Ud)"><path class="qr5rq3y1i"/><path fill="url(#iQ4VAyb)" class="sqy6n_49c"/></g><g filter="url(#icpJOKc)"><path fill="url(#iGaTbLb)" class="eos895dgw"/></g><path class="j3hr0z1_g"/><path fill="url(#iduc57d)" class="iz6ustu0g"/><path class="ef3ovc6ol"/><g filter="url(#i2lMIIz)"><path fill="url(#idjD2vb)" class="k65kjk4-j"/></g><g filter="url(#ivukYGc)"><ellipse transform="rotate(-27.914 13.626 10.015)" class="cv86hacux"/><ellipse fill="url(#iy1dWnc)" transform="rotate(-27.914 13.626 10.015)" class="t7h0_fb9b"/></g><path fill="url(#inwmBSc)" class="fb99ugbtd"/><path fill="url(#i595d4d)" class="fb99ugbtd"/><path fill="url(#iM1tgie)" class="fb99ugbtd"/><path fill="url(#iSlwvMc)" class="s6hsucb5n"/><path fill="url(#i89V2fe)" class="s6hsucb5n"/><g filter="url(#iHjDkUc)"><path class="lnt9mxbkj"/></g><g filter="url(#iPjrjTc)"><path class="uksqlhb9p"/></g><g filter="url(#iodTAje)"><path class="ah1hb6-do"/></g><g filter="url(#ipi05Ib)"><path class="rt4rv8j4l"/></g><g filter="url(#iTql91l)"><path fill="url(#iKAZbrC)" class="x4t77tbgl"/><path fill="url(#ivQitPe)" class="x4t77tbgl"/></g><defs><radialGradient id="iPuY4Ee" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.09 6.933)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="iFZQm4J" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.563 25.535)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="i6N0fCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.004 4.37)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="inuUcqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16 16.003)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="ixv6R3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.656 20.535)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iGuIAve" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.719 19.128)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="isOnyGm" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 26.994 28.285)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="ivFydlc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.458 29.833)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="iZ7Ezoc" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.188 20.347)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="iiFbLce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.23 19.494)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="iU38Rsc" cx="0" cy="0" r="1" gradientTransform="rotate(-125.283 15.14 5.162)scale(1.63656 .29806)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="ivD1Nvc" cx="0" cy="0" r="1" gradientTransform="rotate(69.677 -2.883 21.166)scale(.94974 1.77776)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="ihRtYae" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.516 20.41)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="iSp94yc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 1 -1.87182 -.87742 14.031 16.52)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="i6lBBHN" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.81101 -2.05629 0 16.004 17.285)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="gcy2khpyp"/><stop offset="1" class="ns76nm5tj"/></radialGradient><radialGradient id="isW2xDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.637 23.821)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="vh6yi_hgr"/><stop offset="1" class="e4t4y8vlz"/></radialGradient><radialGradient id="isxz6wd" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.779 23.54)" gradientUnits="userSpaceOnUse"><stop class="vvq7hbbzt"/><stop offset="1" class="eb5hv9bjw"/></radialGradient><radialGradient id="iDQIs3S" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.094 24.063)" gradientUnits="userSpaceOnUse"><stop class="x109hm4su"/><stop offset="1" class="va5jmqb6u"/></radialGradient><radialGradient id="i73vccd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.188 25.415)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="ii7PHmy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.203 26.696)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="iJGjnGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.25 27.977)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="int0Ssc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.32 29.337)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="i8NIE5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.25 25.415)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="iXxVFVj" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.188 26.696)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="itYMGVd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.094 27.977)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="ia70ICc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.953 29.337)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="iiQF4pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 21.538 11.803)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="i5gSlMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 10.531 12.086)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iznfz7d" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -1.234 12.522)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iszMxrc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.887 11.027)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iaO8Ktc" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0937 -10.8432 0 16.633 4.53)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="iowqwtb_n"/><stop offset="1" class="n_rj68bxs"/></radialGradient><radialGradient id="iGFXtKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 18.526 9.907)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ikoGewc" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.555 -1.68)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="i64eGmc" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 11.198 11.412)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="irx1Lje" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 10.226 8.026)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iC2MSXb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 15.925 15.1)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iC07wtc" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 18.037 5.646)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="ieH71Pd" cx="0" cy="0" r="1" gradientTransform="rotate(135.131 6.288 9.005)scale(2.59561 1.64977)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="iLhZqlb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.694 -5.602)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="i1Sn7wb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16.08 14.567)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i5infhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 10.85 9.445)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iCfp8bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 20.94 9.445)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iu5OLYd" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 10.385 -.275)scale(3.48023 1.85345)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="i1tg0Be" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.174 1.577)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="ifBvudc" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.902 2.938)scale(4.04714 1.12642)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iFq1nPd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.38 -5.77)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iuTTxhe" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 .80083 -.44788 1.89356 19.7 4.18)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iZh2Hic" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.134 -1.716)scale(4.28182 2.38794)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="ihTWUPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.57741 -.93641 20.588 8.484)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="ij9M28b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.873 4.063)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iXnkvVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.532 3.937)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iTOthbe" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 8.828 7.427)scale(4.25147 10.9633)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="igIDXZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.261 10.111)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iQ4VAyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 18.033 10.195)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iduc57d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.897 10.111)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iy1dWnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.61 10.33)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i595d4d" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.697 10.125)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iM1tgie" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.057 10.67)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i89V2fe" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.973 4.978)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="ivQitPe" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.375 10.05)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><linearGradient id="iMTpAue" x1="11.819" x2="31.261" y1="4.659" y2="22.895" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="iLnan0m" x1="30.063" x2="9.125" y1="13.347" y2="13.347" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="ixjj3CB" x1="13.438" x2="31.25" y1="3.6" y2="24.412" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="iagCdzk" x1="-4.906" x2="28.906" y1="25.691" y2="25.691" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="it1AhGb" x1="3.094" x2="3.094" y1="5.253" y2="23.691" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iwOC9CA" x1="25.174" x2="25.174" y1="30.505" y2="26.688" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="iAp0Dsc" x1="22.406" x2="23.219" y1="29.316" y2="29.3" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iQh0uDd" x1="7.134" x2="9.529" y1="28.198" y2="28.198" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="idoJNne" x1="18.054" x2="20.851" y1="18.425" y2="18.425" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="iDwoUwg" x1="13.944" x2="11.147" y1="18.425" y2="18.425" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iI3fdeP" x1="12.109" x2="12.672" y1="16.988" y2="17.207" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="iFfcr8c" x1="21.844" x2="17.469" y1="24.847" y2="24.847" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="i29308b" x1="10.314" x2="10.742" y1="23.628" y2="23.628" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="iaA0PIb" x1="12.863" x2="8.563" y1="28.066" y2="28.066" gradientUnits="userSpaceOnUse"><stop class="oup8n6dpm"/><stop offset=".716" class="zw2whl-je"/></linearGradient><linearGradient id="inO64Xc" x1="22.469" x2="18.654" y1="27.66" y2="27.66" gradientUnits="userSpaceOnUse"><stop class="d1gud5zvw"/><stop offset=".807" class="bku9lhrph"/></linearGradient><linearGradient id="ijWcnxb" x1="10.781" x2="21.654" y1="22.003" y2="22.003" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="iZcoCud" x1="16.401" x2="16.401" y1="21.066" y2="22.238" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="iTUotvA" x1="19.023" x2="20.852" y1="26.168" y2="26.168" gradientUnits="userSpaceOnUse"><stop class="s9f5xlzkg"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="bi-ijln_l"/></linearGradient><linearGradient id="iqSrbzc" x1="12.932" x2="10.734" y1="26.168" y2="26.168" gradientUnits="userSpaceOnUse"><stop class="g8fj5qv-y"/><stop offset="1" class="n1yz-o_0e"/></linearGradient><linearGradient id="iQcVn3d" x1="19.023" x2="20.852" y1="27.433" y2="27.433" gradientUnits="userSpaceOnUse"><stop class="s9f5xlzkg"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="bi-ijln_l"/></linearGradient><linearGradient id="itVwuNb" x1="12.932" x2="10.734" y1="27.433" y2="27.433" gradientUnits="userSpaceOnUse"><stop class="g8fj5qv-y"/><stop offset="1" class="n1yz-o_0e"/></linearGradient><linearGradient id="inF0x9b" x1="19.023" x2="20.852" y1="28.699" y2="28.699" gradientUnits="userSpaceOnUse"><stop class="s9f5xlzkg"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="bi-ijln_l"/></linearGradient><linearGradient id="iXgQtZb" x1="12.932" x2="10.734" y1="28.699" y2="28.699" gradientUnits="userSpaceOnUse"><stop class="g8fj5qv-y"/><stop offset="1" class="n1yz-o_0e"/></linearGradient><linearGradient id="ievUoyc" x1="21.236" x2="16.884" y1="12.713" y2="12.713" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iNkq8Ub" x1="16.079" x2="16.934" y1="11.856" y2="11.856" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iHkhPbe" x1="15.006" x2="16.081" y1="11.701" y2="11.76" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="i5bwdLb" x1="16.079" x2="16.079" y1="12.255" y2="13.107" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="ik7UBfc" x1="16.079" x2="16.079" y1="10.007" y2="10.427" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="imLmiad" x1="16.21" x2="16.21" y1="12.929" y2="12.87" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="ihxtO7d" x1="21.443" x2="11.319" y1="5.365" y2="5.365" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iGaTbLb" x1="19.039" x2="18.725" y1="10.165" y2="10.358" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idjD2vb" x1="14.641" x2="14.327" y1="10.165" y2="10.358" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inwmBSc" x1="22.515" x2="21.309" y1="10.192" y2="12.368" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iSlwvMc" x1="10.229" x2="11.688" y1="10.896" y2="10.769" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="iKAZbrC" x1="16.08" x2="16.08" y1="8.946" y2="12.727" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient><filter id="ind4IAb" width="27.98" height="21.09" x="2.004" y="4.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/></filter><filter id="iIrgDRc" width="27.413" height="20.785" x="2.669" y="3.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".2"/></filter><filter id="iCZY78d" width="27.91" height="20.96" x="2.004" y="4.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/></filter><filter id="iB4QuUc" width="2.797" height="14.04" x="18.054" y="16.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/></filter><filter id="iEmZH9b" width="2.797" height="14.04" x="11.147" y="16.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/></filter><filter id="iVYO5oN" width="2.1" height="3.39" x="20.948" y="23.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.752941 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/></filter><filter id="iaWXIFK" width="2.1" height="3.29" x="8.951" y="23.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.611765 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/></filter><filter id="i2Bflze" width="4.793" height="5.391" x="8.951" y="24.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.619608 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/></filter><filter id="ireLElD" width="4.793" height="5.591" x="18.454" y="24.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.435294 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.741176 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1664" result="effect2_innerShadow_4002_1664"/></filter><filter id="iECEwVb" width="2.222" height=".3" x="18.873" y="25.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".05"/></filter><filter id="i5xVc9c" width="2.222" height=".3" x="10.861" y="25.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".05"/></filter><filter id="iqkViff" width="2.222" height=".3" x="18.873" y="27.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".05"/></filter><filter id="i2tsqWb" width="2.222" height=".3" x="10.861" y="27.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".05"/></filter><filter id="ib0AuTc" width="2.222" height=".3" x="18.873" y="28.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".05"/></filter><filter id="iDEl48k" width="2.222" height=".3" x="10.861" y="28.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".05"/></filter><filter id="iPHecgd" width="10.97" height="12.542" x="11.016" y="4.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1664" result="effect2_innerShadow_4002_1664"/></filter><filter id="iniMHob" width="3.754" height="4.823" x="13.933" y="9.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".5"/></filter><filter id="ibyLlUd" width="2.077" height="3.1" x="15.04" y="9.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".05"/></filter><filter id="ibglpZn" width="3.718" height="1.573" x="14.22" y="13.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".05"/></filter><filter id="i5MJX4d" width="12.873" height="8.356" x="9.643" y="1.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1664" result="effect2_innerShadow_4002_1664"/></filter><filter id="iyMfMUd" width="2.339" height="1.19" x="17.668" y="7.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/></filter><filter id="iDE67Ud" width="2.339" height="1.176" x="12.412" y="7.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/></filter><filter id="ivAulke" width="6.584" height="5.992" x="9.998" y="2.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".125"/></filter><filter id="isYCIve" width="6.362" height="5.736" x="15.92" y="3.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".125"/></filter><filter id="iypd5Ud" width=".787" height=".696" x="17.527" y="9.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".05"/></filter><filter id="icpJOKc" width=".891" height=".913" x="18.367" y="9.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".1"/></filter><filter id="i2lMIIz" width=".986" height="1.04" x="13.924" y="9.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".1"/></filter><filter id="ivukYGc" width=".913" height=".705" x="13.169" y="9.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".05"/></filter><filter id="iHjDkUc" width="1.329" height="2.379" x="10.046" y="9.58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".125"/></filter><filter id="iPjrjTc" width="1.447" height="2.403" x="20.791" y="9.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".125"/></filter><filter id="iodTAje" width="2.405" height="1.16" x="12.331" y="7.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".125"/></filter><filter id="ipi05Ib" width="2.405" height="1.16" x="17.61" y="7.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1664" stdDeviation=".125"/></filter><filter id="iTql91l" width="10.29" height="4.16" x="10.884" y="8.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1664"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1664" result="effect2_innerShadow_4002_1664"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:teacher-medium-light" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.ah1hb6-do {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.706 8.218c.257-.184.898-.508 1.655-.381");
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avo9uebvh {
  stop-color: var(--svg-color--544b50, #544B50);
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.b1zho21tu {
  d: path("M20.934 4.384c.514.177.976.537 1.268 1.052a2.37 2.37 0 0 1-.107 2.526a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.667-.268l.078-1.606a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.954 0-1.82-.564-2.212-1.443a.66.66 0 0 0-.615-.419h-1.273c-1.845 0-3.341 1.513-3.341 3.38l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2c0-.312-.095-.618-.27-.875a2.39 2.39 0 0 1-.143-2.446a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.383-1.11a2.326 2.326 0 0 1 2.891-.912a1.5 1.5 0 0 0 1.193 0c.282-.118.59-.188.913-.188c.843 0 1.58.456 1.988 1.132c.308.51.79.88 1.353 1.072");
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.b57h8db-a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 26.09h-1.921");
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bdiqbojjb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 28.62h-1.921");
}

.bi-ijln_l {
  stop-color: var(--svg-color--ab685c, #AB685C);
  stop-opacity: 0;
}

.bku9lhrph {
  stop-color: var(--svg-color--b97a6f, #B97A6F);
}

.c10fbhxdh {
  d: path("M11.218 12.277a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.cjdo17bjb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 27.355h-1.921");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cv86hacux {
  cx: 13.626px;
  cy: 10.015px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d1gud5zvw {
  stop-color: var(--svg-color--f0c0a1, #F0C0A1);
}

.d2b2d_b1d {
  d: path("M16.08 13.924c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.918.845 1.583.845s1.249-.338 1.584-.846c.086-.129-.061-.278-.198-.209a3 3 0 0 1-1.386.329");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d65kawhah {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.668 7.939a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.55a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.dhahslrdx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 28.62h1.922");
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e3q65yqob {
  d: path("M18.263 9.634a.892.892 0 0 1 .86 1.128H17.4a.896.896 0 0 1 .864-1.128");
}

.e4t4y8vlz {
  stop-color: var(--svg-color--c8926a, #C8926A);
}

.eb5hv9bjw {
  stop-color: var(--svg-color--edc2a5, #EDC2A5);
  stop-opacity: 0;
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ef3ovc6ol {
  fill: var(--svg-color--000, #000);
  d: path("M14.406 10.527a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.904a.5.5 0 0 0 .061-.236");
}

.eos895dgw {
  d: path("M19.058 10.409a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.er2--pskp {
  d: path("M11.254 13.792a3.916 3.916 0 0 0 3.886 3.406h1.887a3.916 3.916 0 0 0 3.885-3.406c.118-1.883.237-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.419h-1.273c-1.845 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.erpr8o31c {
  d: path("M21.654 23.035v-2.286c0-.388-.36-.699-.81-.699h-8.658c-1.042 0-1.872.73-1.872 1.622c0 .753.61 1.363 1.363 1.363z");
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
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

.fb99ugbtd {
  d: path("M21.001 12.368q.1-1.596.185-3.191A1.61 1.61 0 0 1 21 12.368");
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.ft5dv1b6b {
  fill: none;
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g1nxbnbrj {
  stop-color: var(--svg-color--e4b8a5, #E4B8A5);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g8fj5qv-y {
  stop-color: var(--svg-color--d29c80, #D29C80);
}

.gcy2khpyp {
  stop-color: var(--svg-color--996759, #996759);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gugba3b_v {
  stop-color: var(--svg-color--33141c, #33141C);
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

.ha0cprbfd {
  d: path("M9.95 23.15c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.injaeqkfm {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.649 10.691l-.692 1.656c-.102.378.141.756.486.756h.735c.345 0 .588-.384.486-.756l-.496-1.838c-.107-.408-.408-.225-.52.182");
}

.iowqwtb_n {
  stop-color: var(--svg-color--b67f70, #B67F70);
  stop-opacity: 0;
}

.iz6ustu0g {
  d: path("M13.895 9.634a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j3hr0z1_g {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.688 9.362c-.653 0-1.205.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.128");
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jj0hsqwwd {
  d: path("M16.004 18.72c-1.14 0-2.06-.92-2.06-2.06V14.1c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jnda8ue6n {
  d: path("M16.004 15.55c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jzwmcqb4a {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.728 13.529a.23.23 0 0 0-.271.046a.21.21 0 0 0-.023.271c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.352-.32Z");
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k65kjk4-j {
  d: path("M14.71 10.422c0-.289-.234-.481-.297-.54l-.289.28l.178.361z");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l6nfqlbiq {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M19.812 8.048a1.85 1.85 0 0 0-.687-.412c-.305-.096-.686-.121-1.213-.057a.277.277 0 1 0 .067.55c.482-.058.776-.027.979.036c.198.063.332.164.49.3a.277.277 0 0 0 .364-.417");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.lnt9mxbkj {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M11.042 9.83a.956.956 0 0 0 .083 1.879a78 78 0 0 1-.083-1.88");
}

.ltxfo2b8y {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.408 30.05v-8.406h-2.094v8.406z");
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m-c6wr06g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 27.355h1.922");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg-49j6uq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.219 4.444H29.43a.1.1 0 0 1 .1.1v19.584");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mw9yznfqi {
  d: path("m21.292 8.784l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.367c-.256-.97.671-1.713 1.656-1.522c.973.189 2.082.517 2.902 1.052c1.744 1.138 1.44 3.188.52 4.154");
}

.n_rj68bxs {
  stop-color: var(--svg-color--956055, #956055);
}

.n0hwrab5r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 26.09h1.922");
}

.n1yz-o_0e {
  stop-color: var(--svg-color--d29c80, #D29C80);
  stop-opacity: 0;
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.ns76nm5tj {
  stop-color: var(--svg-color--794933, #794933);
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

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.omd21jb4q {
  stop-color: var(--svg-color--e8b8a6, #E8B8A6);
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.oup8n6dpm {
  stop-color: var(--svg-color--d9a893, #D9A893);
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.pc11gtbiw {
  d: path("M13.344 25.42a.81.81 0 0 1-.303.667a.8.8 0 0 1 .303.637a.77.77 0 0 1-.303.636a.8.8 0 0 1 .303.637a.77.77 0 0 1-.303.636c.187.144.303.39.303.668c-.01.42-.32.75-.685.75H9.724c-.426 0-.773-.401-.773-.894v-3.604c0-.493.347-.893.773-.893h2.842c.475 0 .77.39.778.76");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl14swbzk {
  fill-rule: evenodd;
  d: path("M12.408 30.05v-8.406h-2.094v8.406z");
}

.poctzgb6q {
  d: path("M28.994 24.04H3.004V5.05l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qc7b67bho {
  d: path("M22.674 30.05V17.806a10.98 10.98 0 0 1 4.32 8.744v3.5z");
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qr5rq3y1i {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.198 9.823c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyaeouklz {
  stop-color: var(--svg-color--eebea0, #EEBEA0);
  stop-opacity: 0;
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rjprz9fyp {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.47 9.362c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rt4rv8j4l {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.64 8.172c-.257-.184-.897-.509-1.655-.381");
}

.rxedppbdt {
  d: path("M10.314 21.93v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s6hsucb5n {
  d: path("M11.025 9.169a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.s9f5xlzkg {
  stop-color: var(--svg-color--ab685c, #AB685C);
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.sqy6n_49c {
  d: path("M18.198 9.823c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.t_227-ttg {
  d: path("M29.374 25.04H2.624c-.34 0-.62-.28-.62-.62V4.67c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t7h0_fb9b {
  cx: 13.626px;
  cy: 10.015px;
  rx: 0.39px;
  ry: 0.197px;
}

.tbnk9dbuh {
  d: path("M22.048 23.158c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.ti-ljlb_r {
  d: path("M11.147 21.543c0-.384.312-.696.696-.696h9.811v1.39h-9.811a.695.695 0 0 1-.696-.694");
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.uksqlhb9p {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M21.041 11.717q.059-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umdq1abts {
  d: path("m15.697 10.313l-.532 1.838c-.108.378.152.756.521.756h.786c.37 0 .63-.384.521-.756l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.va5jmqb6u {
  stop-color: var(--svg-color--bc8872, #BC8872);
}

.vdijrub5w {
  d: path("m19.344 16.11l1.36 2.929c.09.19-.05.41-.26.41l-.963-.266c-.422-.105-.437.277-.277.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V16.11z");
}

.vh6yi_hgr {
  stop-color: var(--svg-color--e4b392, #E4B392);
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.vvq7hbbzt {
  stop-color: var(--svg-color--edc2a5, #EDC2A5);
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wq7u4cbcv {
  d: path("M9.294 30.05V17.806a10.98 10.98 0 0 0-4.32 8.744v3.5z");
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x_eyyzgvq {
  stop-color: var(--svg-color--daa594, #DAA594);
  stop-opacity: 0;
}

.x109hm4su {
  stop-color: var(--svg-color--a66d4a, #A66D4A);
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x4t77tbgl {
  d: path("M20.834 8.54h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91V9.48c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y70g-pbhj {
  d: path("m16.312 5.412l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96a2.4 2.4 0 0 0 .331-.252l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.892v1.485z");
}

.y998tobym {
  fill: var(--svg-color--000, #000);
  d: path("M17.752 10.527a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.236");
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.yj5fjmbpq {
  d: path("M20.94 12.277c.336-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.34 2.02q.257-.546.345-1.18z");
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ymxdkdb7x {
  d: path("m12.654 16.11l-1.36 2.929c-.09.19.05.41.26.41l.964-.266c.422-.105.436.277.276.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V16.11z");
}

.yn3_d1kor {
  d: path("M18.054 16.87h-4.11v13.18h4.11z");
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.z8-obfb5z {
  d: path("M3.004 24.04V5.05h25.99v18.99z");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zunmvpbih {
  d: path("M18.655 25.42a.81.81 0 0 0 .302.667a.8.8 0 0 0-.302.637c0 .267.115.503.302.636a.8.8 0 0 0-.302.637c0 .267.115.503.302.636a.84.84 0 0 0-.302.668c.009.42.32.75.684.75h2.935c.427 0 .774-.401.774-.894v-3.604c0-.493-.347-.893-.774-.893h-2.842c-.475 0-.77.39-.777.76");
}

.zw2whl-je {
  stop-color: var(--svg-color--c48b7e, #C48B7E);
}

</style>
