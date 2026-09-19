<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#idZZX5I)" clip-rule="evenodd" class="v-p5omnxm"/><path fill="url(#ir2Gbac)" clip-rule="evenodd" class="bqwscm-5z"/><g filter="url(#i1DR2Mb)"><path fill="url(#imSU0Kd)" class="mxe5l-b8x"/><path fill="url(#iRQN6pc)" class="mxe5l-b8x"/></g><path fill="url(#iJ6HVme)" class="qwmps2bvc"/><path fill="url(#iri4lPe)" class="qwmps2bvc"/><g filter="url(#i11FLDc)"><path class="v8-ymtd1a"/></g><path fill="url(#iMQI23d)" class="qqq97ebkd"/><path fill="url(#i8GVCXd)" class="qqq97ebkd"/><path fill="url(#ileYPJZ)" class="qqq97ebkd"/><path fill="url(#ijGmsMc)" class="m8zsuwtqz"/><path fill="url(#i1jqf0c)" class="m8zsuwtqz"/><path fill="url(#i0PCseb)" class="m8zsuwtqz"/><path fill="url(#i6dV9Ge)" class="gqrdhsbjl"/><path fill="url(#i8UYDgd)" class="gqrdhsbjl"/><path fill="url(#iWAVhbe)" class="gqrdhsbjl"/><path class="zw0bqzb9t"/><path fill="url(#iIcijtb)" class="ndxr44g2h"/><path fill="url(#iCXimYc)" class="ndxr44g2h"/><path fill="url(#itZ0fRb)" class="ndxr44g2h"/><g filter="url(#iJrqWue)"><path class="hnksfxbro"/><path fill="url(#ijTQx5b)" class="vvb767b_n"/><path fill="url(#iyCfyue)" class="vvb767b_n"/><path fill="url(#iDCoLrd)" class="vvb767b_n"/></g><g filter="url(#iQGsCmP)"><path fill="url(#ivci6pe)" class="ha61p4glz"/></g><g filter="url(#isdvbdY)"><path fill="url(#i5InDnb)" class="elnrcdbjr"/><path fill="url(#isUHzSd)" class="elnrcdbjr"/></g><g filter="url(#iPStlxH)"><path fill="url(#iFbbife)" class="d56lu3b4e"/><path fill="url(#iNNdesb)" class="d56lu3b4e"/></g><path fill="url(#i0wzcic)" class="d56lu3b4e"/><path clip-rule="evenodd" class="auf2_ybvr"/><path fill="url(#iq2BZxb)" clip-rule="evenodd" class="vncbe3bae"/><path clip-rule="evenodd" class="xk0g-_c-a"/><path fill="url(#ixdbthd)" clip-rule="evenodd" class="luuu6sb3x"/><path clip-rule="evenodd" class="tx3o8_15z"/><path fill="url(#iFDyIDj)" clip-rule="evenodd" class="w--l981bs"/><path clip-rule="evenodd" class="a0wxo0yuj"/><path fill="url(#iyc6OsL)" clip-rule="evenodd" class="jch7h-fqu"/><path clip-rule="evenodd" class="zdrx7pbdl"/><path fill="url(#icwCknb)" clip-rule="evenodd" class="oau0_1brx"/><path clip-rule="evenodd" class="vcgmrjd8s"/><path fill="url(#iIXeuoK)" clip-rule="evenodd" class="gfi5steoc"/><path clip-rule="evenodd" class="y9e08hgcp"/><path fill="url(#i9ZWnye)" clip-rule="evenodd" class="op0wkpb0r"/><path fill="url(#iNlmOGO)" clip-rule="evenodd" class="ygz2-cccw"/><path fill="url(#ibUjcnj)" clip-rule="evenodd" class="ygz2-cccw"/><g filter="url(#iIko4je)"><path class="ffzgmgbfc"/></g><g filter="url(#iDH7Yec)"><path stroke="url(#iiexQQc)" class="eevmxtb1v"/></g><g filter="url(#iZQGBpe)"><path class="gw26_ntap"/></g><g filter="url(#iBRL1sb)"><path stroke="url(#iEdOs4b)" class="rmafx6bat"/></g><g filter="url(#iWhJ0wc)"><path class="xy2spr9ic"/></g><g filter="url(#iEgX4fp)"><path stroke="url(#i2JUGPe)" class="fvsn5ytmb"/></g><g filter="url(#iFJTzic)"><path class="xq52vfsiw"/></g><g filter="url(#ilVisNd)"><path stroke="url(#iL3XsGd)" class="fj_0iw0tn"/></g><path fill="url(#imiPwrd)" class="hkx_asbot"/><path fill="url(#iaR7bud)" class="ov85j1_vd"/><path fill="url(#iUKtTCd)" class="ov85j1_vd"/><path fill="url(#iaR7bud)" class="ov85j1_vd"/><path fill="url(#iUKtTCd)" class="ov85j1_vd"/><g filter="url(#i0Wb8xd)"><path fill="url(#i8Dzo8d)" class="bun-84bgj"/></g><path fill="url(#iXcJzYb)" class="bun-84bgj"/><path fill="url(#iKMm4Md)" class="bun-84bgj"/><path fill="url(#izoDQ7b)" class="bun-84bgj"/><path fill="url(#itQ8fvJ)" class="bun-84bgj"/><path fill="url(#io0Dodd)" class="bun-84bgj"/><path fill="url(#ituHBae)" class="bun-84bgj"/><path fill="url(#ivEW65c)" class="bun-84bgj"/><path fill="url(#iOO6ITd)" class="bun-84bgj"/><g filter="url(#idjzwtd)"><path class="zhiua4b9h"/></g><g filter="url(#ig1nuTd)"><path fill="url(#ilGb93b)" class="vfp6t-bnj"/><path fill="url(#i0d1tky)" class="vfp6t-bnj"/><path fill="url(#iydew5L)" class="vfp6t-bnj"/><path fill="url(#iUv60Wc)" class="vfp6t-bnj"/></g><g filter="url(#iTqQBpe)"><path stroke="url(#ioTnKbN)" class="wcudicc8v"/></g><path fill="url(#isYFlXD)" class="d81s04x-l"/><g filter="url(#iLsAo6b)"><path fill="url(#iDxP17d)" class="lahppm_hl"/><path fill="url(#iBZvLOe)" class="lahppm_hl"/><path fill="url(#ieQ7Udb)" class="lahppm_hl"/><path fill="url(#ifAlTSd)" class="lahppm_hl"/><path fill="url(#izSBQwl)" class="lahppm_hl"/></g><g filter="url(#ilqgiId)"><path class="uu8flgbet"/></g><g filter="url(#ihReX4d)"><path class="uo7na2b1f"/></g><g filter="url(#iVs5WWp)"><path fill="url(#izX9aGe)" class="ydii2-bnu"/><path fill="url(#iBMbCuf)" class="ydii2-bnu"/></g><g filter="url(#iniVS0b)"><path fill="url(#iSCJb7c)" class="au275sqwj"/><path fill="url(#iSa4yRb)" class="au275sqwj"/><path fill="url(#i0jFHGG)" class="au275sqwj"/><path fill="url(#i6WIt3d)" class="au275sqwj"/><path fill="url(#iHp9Njc)" class="au275sqwj"/><path fill="url(#iQJYPxb)" class="au275sqwj"/></g><path fill="url(#i2j6h9c)" class="boim9zblr"/><path fill="url(#i37HiGc)" class="boim9zblr"/><path fill="url(#ioP0WAI)" class="boim9zblr"/><path fill="url(#if0Btab)" class="n0licc55p"/><path fill="url(#i2xONtb)" class="n0licc55p"/><g filter="url(#iaUeZBc)"><path class="tyc9ftetr"/></g><g filter="url(#iapjaFL)"><path class="o3qutogak"/></g><g filter="url(#iJM8pWb)"><path class="i5776abmf"/></g><g filter="url(#iy0Cjie)"><path class="m_9-jubdu"/></g><path class="z8ahlcg8v"/><g filter="url(#iqXIN8c)"><path class="n0m4asbit"/></g><path class="w8oa9vb5w"/><g filter="url(#iykfXAP)"><path class="x3almbbjn"/></g><defs><radialGradient id="idZZX5I" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.354 13.087)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="lic6lbbau"/><stop offset="1" class="gpe3o1c3d"/></radialGradient><radialGradient id="ir2Gbac" cx="0" cy="0" r="1" gradientTransform="rotate(174.454 13.31 11.984)scale(.83202 .3356)" gradientUnits="userSpaceOnUse"><stop class="xdsljxb6l"/><stop offset="1" class="gkxm7k0ja"/></radialGradient><radialGradient id="imSU0Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.187)" gradientUnits="userSpaceOnUse"><stop class="owzxb4bzq"/><stop offset="1" class="vsjc8v9ca"/></radialGradient><radialGradient id="iRQN6pc" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -6.868 31.62)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="z800wxkkv"/><stop offset="1" class="zwg9cab5i"/></radialGradient><radialGradient id="iJ6HVme" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.531)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="wpgg6c2wy"/><stop offset="1" class="boxw_edme"/></radialGradient><radialGradient id="iri4lPe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.172)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="vf-atc5np"/><stop offset="1" class="z2ao1lh1t"/></radialGradient><radialGradient id="iMQI23d" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .21875 -.60896 -2.43587 21.294 25.864)" gradientUnits="userSpaceOnUse"><stop class="dxvi3ib7v"/><stop offset="1" class="ncrbay0xj"/></radialGradient><radialGradient id="i8GVCXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.7705 1.76305 5.29137 5.576 25.74)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="t0tmblryn"/><stop offset="1" class="c16c1ob7o"/></radialGradient><radialGradient id="ileYPJZ" cx="0" cy="0" r="1" gradientTransform="matrix(.67187 .90625 -1.49816 1.1107 7.232 23.874)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="p6zke3bbd"/><stop offset="1" class="bmjjdqblu"/></radialGradient><radialGradient id="ijGmsMc" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.094)" gradientUnits="userSpaceOnUse"><stop class="r40r2-btv"/><stop offset="1" class="w68v077cg"/></radialGradient><radialGradient id="i6dV9Ge" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 22.82)" gradientUnits="userSpaceOnUse"><stop class="oudqrddpb"/><stop offset="1" class="ex-njr0bb"/></radialGradient><radialGradient id="iIcijtb" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.157 23.495)" gradientUnits="userSpaceOnUse"><stop class="nh2d_e3ja"/><stop offset="1" class="s1mkhyyat"/></radialGradient><radialGradient id="itZ0fRb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 20)" gradientUnits="userSpaceOnUse"><stop class="p5dagkb6w"/><stop offset="1" class="d2qw4t-ma"/></radialGradient><radialGradient id="iyCfyue" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.237 7.531)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="be02pvbwh"/><stop offset="1" class="xx2sl9hhj"/></radialGradient><radialGradient id="iDCoLrd" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.094)" gradientUnits="userSpaceOnUse"><stop class="h4omf55qi"/><stop offset="1" class="sqb0hacke"/></radialGradient><radialGradient id="ivci6pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.094)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="i5InDnb" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.068 2.398)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="ye-czfbqo"/><stop offset="1" class="ok-7tsxgn"/></radialGradient><radialGradient id="isUHzSd" cx="0" cy="0" r="1" gradientTransform="rotate(118.757 4.54 9.687)scale(3.02046 3.40652)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="gcnznbcnc"/><stop offset="1" class="s3p5ymzwk"/></radialGradient><radialGradient id="iFbbife" cx="0" cy="0" r="1" gradientTransform="matrix(.5 8.04173 -7.73502 .48093 17.689 13.281)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="ydcxvabaw"/><stop offset="1" class="hekp_gbnf"/></radialGradient><radialGradient id="iNNdesb" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.577 10.752)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="ksocwfbza"/><stop offset="1" class="ecaf6kbqo"/></radialGradient><radialGradient id="i0wzcic" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 11.812)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="bmu4g5dxl"/><stop offset="1" class="z321yabtz"/></radialGradient><radialGradient id="iq2BZxb" cx="0" cy="0" r="1" gradientTransform="matrix(.11328 .6422 -3.96388 .69921 4.51 23.047)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="l7q7_gbnx"/><stop offset="1" class="pduv-n6bl"/></radialGradient><radialGradient id="ixdbthd" cx="0" cy="0" r="1" gradientTransform="matrix(-.11328 .6422 -3.96388 -.69922 27.49 23.047)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="wszthn3gy"/><stop offset="1" class="uwzafok6o"/></radialGradient><radialGradient id="iFDyIDj" cx="0" cy="0" r="1" gradientTransform="matrix(.12686 .83746 -4.47454 .67782 4.517 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="l7q7_gbnx"/><stop offset="1" class="pduv-n6bl"/></radialGradient><radialGradient id="iyc6OsL" cx="0" cy="0" r="1" gradientTransform="matrix(-.12686 .83746 -4.47454 -.67782 27.483 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="wszthn3gy"/><stop offset="1" class="uwzafok6o"/></radialGradient><radialGradient id="icwCknb" cx="0" cy="0" r="1" gradientTransform="matrix(.11226 .95131 -3.99486 .47143 5 24.226)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="l7q7_gbnx"/><stop offset="1" class="pduv-n6bl"/></radialGradient><radialGradient id="iIXeuoK" cx="0" cy="0" r="1" gradientTransform="rotate(96.73 2.732 24.113)scale(.95791 4.02259)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="wszthn3gy"/><stop offset="1" class="uwzafok6o"/></radialGradient><radialGradient id="i9ZWnye" cx="0" cy="0" r="1" gradientTransform="matrix(.10014 1.0686 -3.5818 .33567 5.935 24.41)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="l7q7_gbnx"/><stop offset="1" class="pduv-n6bl"/></radialGradient><radialGradient id="ibUjcnj" cx="0" cy="0" r="1" gradientTransform="matrix(-.10014 1.0686 -3.5818 -.33567 26.065 24.411)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="d42ncfbkl"/><stop offset="1" class="fizdybc8y"/></radialGradient><radialGradient id="imiPwrd" cx="0" cy="0" r="1" gradientTransform="rotate(99.782 6.247 12.335)scale(2.25518 2.67898)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iaR7bud" cx="0" cy="0" r="1" gradientTransform="matrix(.80098 1.68626 -.76648 .36408 12.544 8.452)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iUKtTCd" cx="0" cy="0" r="1" gradientTransform="matrix(.11274 .75053 -.65837 .0989 13.047 8.324)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="i8Dzo8d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.28716 0 0 -5.81496 17.798 7.787)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iKMm4Md" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.50661 -6.21637 0 16.308 4.713)" gradientUnits="userSpaceOnUse"><stop offset=".729" class="nku1qjb2e"/><stop offset=".957" class="lihjh37-b"/></radialGradient><radialGradient id="izoDQ7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.84313 1.04338 0 17.571 7.082)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="itQ8fvJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.0365 -.69379 .75502 -.03973 14.625 6.996)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="io0Dodd" cx="0" cy="0" r="1" gradientTransform="matrix(.75882 0 0 3.85691 12.963 8.028)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="ituHBae" cx="0" cy="0" r="1" gradientTransform="matrix(1.6441 -2.29753 .5204 .3724 12.352 5.9)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="ivEW65c" cx="0" cy="0" r="1" gradientTransform="rotate(-103.259 12.064 -1.135)scale(6.61694 7.28876)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iOO6ITd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28578 .45317 -.27186 .77133 17.263 4.403)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="ioTnKbN" cx="0" cy="0" r="1" gradientTransform="matrix(.21829 -.3895 1.13344 .63523 15.324 9.855)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="isYFlXD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.45318 1.82327 0 16.032 10.012)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iBZvLOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.28413 4.04704 0 12.744 6.792)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="ieQ7Udb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.28414 4.04704 0 19.089 6.792)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="ifAlTSd" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 9.57 -.292)scale(2.18829 1.16541)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="izSBQwl" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.084 14.738)scale(1.08814 2.51962)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="izX9aGe" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.855 2.791)scale(2.54475 .70827)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iBMbCuf" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 11.52 -8.575)scale(3.78941 4.19828)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iSCJb7c" cx="0" cy="0" r="1" gradientTransform="matrix(2.12891 .50354 -.28162 1.19063 18.309 3.48)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iSa4yRb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.351 -2.3288 1.29876 -.75344 19.257 6.376)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="i0jFHGG" cx="0" cy="0" r="1" gradientTransform="matrix(-.82204 -1.38475 .99184 -.5888 18.867 6.187)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="i6WIt3d" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 9.322 2.83)scale(3.10276 3.35421)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iHp9Njc" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 7.87 8.399)scale(.25231 1.15351)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iQJYPxb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25414 2.36078 -6.0878 -3.23408 18.201 2.812)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="i37HiGc" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 4.708 16.095)scale(1.46485 1.39758)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="ioP0WAI" cx="0" cy="0" r="1" gradientTransform="matrix(.49534 -.67978 .56979 .4152 19.163 7.562)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i2xONtb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05322 -.15402 .15142 -1.0354 12.942 7.624)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><filter id="i1DR2Mb" width="9.729" height="6.156" x="17.627" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.521569 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23994"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.470588 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23994" result="effect2_innerShadow_3987_23994"/></filter><filter id="i11FLDc" width="17.213" height="7.995" x="5.751" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.584314 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23994"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.470588 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23994" result="effect2_innerShadow_3987_23994"/></filter><filter id="iJrqWue" width="7.621" height="12.797" x="19.836" y="11.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.470588 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23994"/></filter><filter id="iQGsCmP" width="8.502" height="3.19" x="11.869" y="21.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23994"/></filter><filter id="isdvbdY" width="5.834" height="4.108" x="13.158" y="10.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.639216 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23994"/></filter><filter id="iPStlxH" width="8.289" height="10.271" x="11.888" y="11.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.423529 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23994"/></filter><filter id="iIko4je" width="1.684" height="1.255" x="5.351" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".075"/></filter><filter id="iDH7Yec" width="1.684" height="1.255" x="24.965" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".075"/></filter><filter id="iZQGBpe" width="2.04" height="1.095" x="4.237" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".075"/></filter><filter id="iBRL1sb" width="2.04" height="1.095" x="25.723" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".075"/></filter><filter id="iWhJ0wc" width="2.223" height=".888" x="3.593" y="23.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".075"/></filter><filter id="iEgX4fp" width="2.223" height=".888" x="26.184" y="23.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".075"/></filter><filter id="iFJTzic" width="2.031" height=".566" x="3.653" y="22.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".075"/></filter><filter id="ilVisNd" width="2.031" height=".566" x="26.317" y="22.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".075"/></filter><filter id="i0Wb8xd" width="7.176" height="7.96" x="12.849" y="3.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23994"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23994" result="effect2_innerShadow_3987_23994"/></filter><filter id="idjzwtd" width="3.103" height="3.775" x="14.312" y="6.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".5"/></filter><filter id="ig1nuTd" width="1.38" height="2.023" x="15.342" y="7.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".05"/></filter><filter id="iTqQBpe" width="2.524" height="1.175" x="14.77" y="9.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".05"/></filter><filter id="iLsAo6b" width="8.094" height="5.44" x="11.985" y="1.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23994"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23994" result="effect2_innerShadow_3987_23994"/></filter><filter id="ilqgiId" width="1.508" height=".823" x="17.032" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23994"/></filter><filter id="ihReX4d" width="1.508" height=".813" x="13.727" y="5.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23994"/></filter><filter id="iVs5WWp" width="4.026" height="3.649" x="12.266" y="2.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".05"/></filter><filter id="iniVS0b" width="3.883" height="3.538" x="16.042" y="2.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".075"/></filter><filter id="iaUeZBc" width="1.021" height="1.682" x="12.146" y="6.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".125"/></filter><filter id="iapjaFL" width="1.095" height="1.697" x="18.902" y="6.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".125"/></filter><filter id="iJM8pWb" width="1.341" height=".558" x="13.761" y="5.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".05"/></filter><filter id="iy0Cjie" width="1.341" height=".558" x="17.081" y="5.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".05"/></filter><filter id="iqXIN8c" width="1.628" height=".644" x="13.82" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".05"/></filter><filter id="iykfXAP" width="1.628" height=".644" x="16.609" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23994" stdDeviation=".05"/></filter><linearGradient id="i1jqf0c" x1="21.525" x2="21.525" y1="21.031" y2="22.187" gradientUnits="userSpaceOnUse"><stop class="u-ogeqbld"/><stop offset="1" class="jiqak5-_m"/></linearGradient><linearGradient id="i0PCseb" x1="18.658" x2="19.892" y1="24.315" y2="24.719" gradientUnits="userSpaceOnUse"><stop offset=".106" class="x0oemnbnc"/><stop offset="1" class="yeoml4btx"/></linearGradient><linearGradient id="i8UYDgd" x1="10.822" x2="10.822" y1="21.031" y2="22.187" gradientUnits="userSpaceOnUse"><stop class="x4_b-2r_f"/><stop offset="1" class="qlojknfdm"/></linearGradient><linearGradient id="iWAVhbe" x1="13.689" x2="12.455" y1="24.315" y2="24.719" gradientUnits="userSpaceOnUse"><stop offset=".106" class="t_z-23bug"/><stop offset="1" class="kkbuv9ocm"/></linearGradient><linearGradient id="iCXimYc" x1="12.24" x2="10.033" y1="20.637" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".184" class="pu7ffqbdj"/><stop offset="1" class="qlidsibqc"/></linearGradient><linearGradient id="ijTQx5b" x1="19.835" x2="22.042" y1="20.637" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".184" class="wuailr9fb"/><stop offset="1" class="hidnebcsy"/></linearGradient><linearGradient id="iNlmOGO" x1="26.466" x2="25.091" y1="25.203" y2="24.046" gradientUnits="userSpaceOnUse"><stop offset=".198" class="kdydwf0xq"/><stop offset=".789" class="e7cxleyvf"/></linearGradient><linearGradient id="iiexQQc" x1="26.516" x2="25.268" y1="25.114" y2="24.986" gradientUnits="userSpaceOnUse"><stop class="us91czbdi"/><stop offset="1" class="eu_n2kn0k"/></linearGradient><linearGradient id="iEdOs4b" x1="27.656" x2="26.075" y1="24.793" y2="24.534" gradientUnits="userSpaceOnUse"><stop class="us91czbdi"/><stop offset="1" class="eu_n2kn0k"/></linearGradient><linearGradient id="i2JUGPe" x1="28.314" x2="26.645" y1="24.047" y2="24.143" gradientUnits="userSpaceOnUse"><stop class="us91czbdi"/><stop offset="1" class="eu_n2kn0k"/></linearGradient><linearGradient id="iL3XsGd" x1="28.24" x2="26.724" y1="23.273" y2="23.211" gradientUnits="userSpaceOnUse"><stop class="us91czbdi"/><stop offset="1" class="eu_n2kn0k"/></linearGradient><linearGradient id="iXcJzYb" x1="19.275" x2="16.538" y1="8.846" y2="8.846" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="ilGb93b" x1="16.032" x2="16.57" y1="8.308" y2="8.308" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="i0d1tky" x1="15.358" x2="16.033" y1="8.21" y2="8.247" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iydew5L" x1="16.032" x2="16.032" y1="8.558" y2="9.094" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iUv60Wc" x1="16.032" x2="16.032" y1="7.145" y2="7.409" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iDxP17d" x1="19.405" x2="13.039" y1="4.226" y2="4.226" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="i2j6h9c" x1="20.08" x2="19.321" y1="7.261" y2="8.63" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="if0Btab" x1="12.354" x2="13.271" y1="7.704" y2="7.624" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-lotus-position-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a0wxo0yuj {
  fill: var(--svg-color--d2a089, #D2A089);
  fill-rule: evenodd;
  d: path("M26.175 23.525a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.au275sqwj {
  d: path("m19.31 6.376l-.018-.397a.924.924 0 0 0-.884-.896h-.88a1.52 1.52 0 0 1-1.336-.792s.453-1.308 1.204-1.138c.55.123 1.137.318 1.586.61c1.097.716.905 2.006.328 2.613");
}

.auf2_ybvr {
  fill: var(--svg-color--e5ab8a, #E5AB8A);
  fill-rule: evenodd;
  d: path("M5.697 23.047a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136l-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.be02pvbwh {
  stop-color: var(--svg-color--dfb298, #DFB298);
}

.bmjjdqblu {
  stop-color: var(--svg-color--dc9a7c, #DC9A7C);
  stop-opacity: 0;
}

.bmu4g5dxl {
  stop-color: var(--svg-color--c56d32, #C56D32);
}

.boim9zblr {
  d: path("M19.127 8.63q.064-1.004.117-2.007a1.012 1.012 0 0 1-.117 2.007");
}

.boxw_edme {
  stop-color: var(--svg-color--b97383, #B97383);
}

.bqwscm-5z {
  fill-rule: evenodd;
  d: path("M25.316 22.957a.5.5 0 0 0 .5.5c.632 0 1.257-.193 1.5-.268l.04-.012a.5.5 0 0 0-.292-.957l-.03.01c-.246.075-.743.227-1.218.227a.5.5 0 0 0-.5.5");
}

.bun-84bgj {
  d: path("M12.999 9.525a2.46 2.46 0 0 0 2.443 2.142h1.186a2.46 2.46 0 0 0 2.443-2.142c.074-1.184.149-2.364.204-3.548a.91.91 0 0 0-.867-.9h-.88c-.6 0-1.144-.354-1.391-.907a.42.42 0 0 0-.387-.263h-.8c-1.16 0-2.101.95-2.101 2.124c0 1.17.073 2.321.15 3.494");
}

.c16c1ob7o {
  stop-color: var(--svg-color--e6a790, #E6A790);
  stop-opacity: 0;
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d2qw4t-ma {
  stop-color: var(--svg-color--bc7156, #BC7156);
  stop-opacity: 0;
}

.d42ncfbkl {
  stop-color: var(--svg-color--c18489, #C18489);
  stop-opacity: 0;
}

.d56lu3b4e {
  d: path("M18.892 11.153v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724a6.5 6.5 0 0 0-1.27.896v9.276h8.289v-9.276c-.198-.2-.662-.559-1.285-.894");
}

.d81s04x-l {
  d: path("M16.032 9.608c-.319 0-.619-.075-.87-.207c-.087-.043-.18.054-.125.132c.21.319.577.532.995.532s.785-.213.996-.532c.054-.082-.038-.175-.125-.132a1.9 1.9 0 0 1-.87.207");
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dxvi3ib7v {
  stop-color: var(--svg-color--ecb99f, #ECB99F);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e7cxleyvf {
  stop-color: var(--svg-color--c28369, #C28369);
}

.ecaf6kbqo {
  stop-color: var(--svg-color--cc3a05, #CC3A05);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.eevmxtb1v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.055a15 15 0 0 1-1.234-.805");
}

.elnrcdbjr {
  d: path("M18.892 11.153v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724c.763-.417 1.77-.784 2.914-.784c1.05 0 2.055.375 2.82.786");
}

.eu_n2kn0k {
  stop-color: var(--svg-color--daaf97, #DAAF97);
  stop-opacity: 0;
}

.ex-njr0bb {
  stop-color: var(--svg-color--ad765c, #AD765C);
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

.ffzgmgbfc {
  stroke: var(--svg-color--ebb49a, #EBB49A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.576 25.055a15 15 0 0 0 1.234-.805");
}

.fizdybc8y {
  stop-color: var(--svg-color--c18489, #C18489);
}

.fj_0iw0tn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.265c-.398 0-.893.047-1.58-.109");
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvsn5ytmb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 24.016a3.8 3.8 0 0 1-1.773-.438");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcnznbcnc {
  stop-color: var(--svg-color--cc8760, #CC8760);
}

.gfi5steoc {
  fill-rule: evenodd;
  d: path("M25.902 23.947a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 1 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.gkxm7k0ja {
  stop-color: var(--svg-color--d4a47e, #D4A47E);
}

.gpe3o1c3d {
  stop-color: var(--svg-color--e9ac86, #E9AC86);
}

.gqrdhsbjl {
  d: path("M13.83 21.323H7.814v2.692c2.531.352 6.016.297 6.016.297z");
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gw26_ntap {
  stroke: var(--svg-color--ebb49a, #EBB49A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.746c.41-.066 1.204-.313 1.59-.645");
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

.h4omf55qi {
  stop-color: var(--svg-color--f0be9e, #F0BE9E);
}

.ha61p4glz {
  d: path("m13.447 24.312l-1.578-2.99h8.301l-1.551 2.99z");
}

.hekp_gbnf {
  stop-color: var(--svg-color--f74d05, #F74D05);
}

.hidnebcsy {
  stop-color: var(--svg-color--e09978, #E09978);
  stop-opacity: 0;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hkx_asbot {
  d: path("M19.089 8.572c.21-.006.408-.078.569-.194v.586c0 .561-.335 1.062-.843 1.27q.161-.344.217-.743z");
}

.hnksfxbro {
  fill: var(--svg-color--dd9f7b, #DD9F7B);
  d: path("M22.32 16.08c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
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

.i5776abmf {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.911 6.02c.162-.116.565-.32 1.04-.24");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.jch7h-fqu {
  fill-rule: evenodd;
  d: path("M26.175 23.525a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.jiqak5-_m {
  stop-color: var(--svg-color--b57257, #B57257);
  stop-opacity: 0;
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.kdydwf0xq {
  stop-color: var(--svg-color--cf9b8d, #CF9B8D);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kkbuv9ocm {
  stop-color: var(--svg-color--ba8165, #BA8165);
  stop-opacity: 0;
}

.ksocwfbza {
  stop-color: var(--svg-color--ee5422, #EE5422);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l7q7_gbnx {
  stop-color: var(--svg-color--da978f, #DA978F);
  stop-opacity: 0;
}

.lahppm_hl {
  d: path("M19.085 3.61c.323.111.614.337.797.66a1.49 1.49 0 0 1-.067 1.59a1 1 0 0 0-.17.549v.747a1.1 1.1 0 0 0-.42-.169l.05-1.01a.91.91 0 0 0-.867-.9h-.88c-.6 0-1.144-.354-1.391-.907a.42.42 0 0 0-.387-.263h-.8c-1.16 0-2.101.95-2.101 2.124l.019.967c-.16.023-.327.077-.453.166v-.755a1 1 0 0 0-.17-.55a1.5 1.5 0 0 1-.09-1.538c.184-.347.48-.59.817-.708c.36-.128.667-.37.87-.698a1.46 1.46 0 0 1 1.818-.573a.94.94 0 0 0 .75 0a1.46 1.46 0 0 1 1.824.594c.194.32.497.552.851.674");
}

.lic6lbbau {
  stop-color: var(--svg-color--e9ae87, #E9AE87);
}

.lihjh37-b {
  stop-color: var(--svg-color--c78273, #C78273);
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.luuu6sb3x {
  fill-rule: evenodd;
  d: path("M26.304 23.047a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.m_9-jubdu {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.272 5.991a1.46 1.46 0 0 0-1.041-.24");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.m8zsuwtqz {
  d: path("M18.517 21.323h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mxe5l-b8x {
  d: path("M17.627 27.937h4.244c2.93 0 4.28-1.916 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.11z");
}

.n0licc55p {
  d: path("M12.855 6.618a1.012 1.012 0 0 0 .087 2.012a48 48 0 0 1-.087-2.012");
}

.n0m4asbit {
  stroke: var(--svg-color--98643d, #98643D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.303a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.ncrbay0xj {
  stop-color: var(--svg-color--ecb99f, #ECB99F);
  stop-opacity: 0;
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.ndxr44g2h {
  d: path("M9.755 16.08c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.nh2d_e3ja {
  stop-color: var(--svg-color--f3bea3, #F3BEA3);
}

.nku1qjb2e {
  stop-color: var(--svg-color--d7998d, #D7998D);
  stop-opacity: 0;
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.o3qutogak {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M19.152 8.22q.037-.598.07-1.196a.6.6 0 0 1-.07 1.196");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.oau0_1brx {
  fill-rule: evenodd;
  d: path("M6.099 23.947a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.ok-7tsxgn {
  stop-color: var(--svg-color--dda688, #DDA688);
}

.op0wkpb0r {
  fill-rule: evenodd;
  d: path("M6.818 24.172c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.oudqrddpb {
  stop-color: var(--svg-color--d9a183, #D9A183);
}

.ov85j1_vd {
  d: path("M12.976 8.572a1.03 1.03 0 0 1-.57-.194v.586c0 .561.335 1.062.844 1.27a2.6 2.6 0 0 1-.218-.743z");
}

.owzxb4bzq {
  stop-color: var(--svg-color--d2a28b, #D2A28B);
}

.p5dagkb6w {
  stop-color: var(--svg-color--95472f, #95472F);
}

.p6zke3bbd {
  stop-color: var(--svg-color--d9906f, #D9906F);
}

.pduv-n6bl {
  stop-color: var(--svg-color--da978f, #DA978F);
}

.pu7ffqbdj {
  stop-color: var(--svg-color--b56548, #B56548);
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

.qlidsibqc {
  stop-color: var(--svg-color--d49179, #D49179);
  stop-opacity: 0;
}

.qlojknfdm {
  stop-color: var(--svg-color--9f6048, #9F6048);
  stop-opacity: 0;
}

.qqq97ebkd {
  d: path("M10.236 27.937c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.qwmps2bvc {
  d: path("M13.22 24.312h-1.429a1 1 0 0 0-.943.67c-.408 1.171-.96 2.765-1.032 3.002c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.871 2.057-1.735l.052-.078h.42z");
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r40r2-btv {
  stop-color: var(--svg-color--bb8c75, #BB8C75);
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rmafx6bat {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.538 24.746c-.41-.066-1.204-.313-1.59-.645");
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.s1mkhyyat {
  stop-color: var(--svg-color--efba94, #EFBA94);
  stop-opacity: 0;
}

.s3p5ymzwk {
  stop-color: var(--svg-color--d69873, #D69873);
  stop-opacity: 0;
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.sqb0hacke {
  stop-color: var(--svg-color--e09576, #E09576);
  stop-opacity: 0;
}

.t_z-23bug {
  stop-color: var(--svg-color--9b6054, #9B6054);
}

.t0tmblryn {
  stop-color: var(--svg-color--fcbfa4, #FCBFA4);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tx3o8_15z {
  fill: var(--svg-color--e5ab8a, #E5AB8A);
  fill-rule: evenodd;
  d: path("M5.825 23.525a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.tyc9ftetr {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M12.865 7.033a.6.6 0 0 0 .053 1.182q-.033-.59-.053-1.182");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u-ogeqbld {
  stop-color: var(--svg-color--a15d45, #A15D45);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uo7na2b1f {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M13.888 5.844a1.74 1.74 0 0 1 1.093-.226a.174.174 0 1 1-.042.347a1.4 1.4 0 0 0-.92.209l-.01.007l-.002.002a.174.174 0 0 1-.213-.276z");
}

.us91czbdi {
  stop-color: var(--svg-color--daaf97, #DAAF97);
}

.uu8flgbet {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M18.38 5.913a1.2 1.2 0 0 0-.433-.259c-.191-.06-.43-.076-.762-.035a.174.174 0 0 0 .042.346c.303-.037.488-.018.616.022c.124.04.209.103.308.189a.174.174 0 1 0 .229-.263");
}

.uwzafok6o {
  stop-color: var(--svg-color--bc7f83, #BC7F83);
}

.v-p5omnxm {
  fill-rule: evenodd;
  d: path("M6.76 22.957a.5.5 0 0 1-.5.5c-.632 0-1.257-.193-1.501-.268l-.04-.012a.5.5 0 0 1 .293-.957l.029.01c.246.075.743.227 1.219.227a.5.5 0 0 1 .5.5");
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v8-ymtd1a {
  fill: var(--svg-color--e8b38c, #E8B38C);
  d: path("M10.236 27.937c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.vcgmrjd8s {
  fill: var(--svg-color--d2a089, #D2A089);
  fill-rule: evenodd;
  d: path("M25.902 23.947a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 1 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.vf-atc5np {
  stop-color: var(--svg-color--e9ae9a, #E9AE9A);
  stop-opacity: 0;
}

.vfp6t-bnj {
  d: path("m15.792 7.337l-.335 1.156c-.068.238.096.476.328.476h.494c.232 0 .396-.242.328-.476l-.334-1.156c-.072-.256-.406-.256-.481 0");
}

.vncbe3bae {
  fill-rule: evenodd;
  d: path("M5.697 23.047a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136l-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.vsjc8v9ca {
  stop-color: var(--svg-color--d99f83, #D99F83);
}

.vvb767b_n {
  d: path("M22.32 16.08c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.w--l981bs {
  fill-rule: evenodd;
  d: path("M5.825 23.525a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.w68v077cg {
  stop-color: var(--svg-color--b27360, #B27360);
}

.w8oa9vb5w {
  stroke: var(--svg-color--7f492d, #7F492D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.76 7.303a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wcudicc8v {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.196 9.335c.24.126.529.198.836.198c.31 0 .596-.072.837-.198a.17.17 0 0 1 .203.033c.049.05.067.133.018.206m-1.894-.24l1.832.199m-1.832-.198a.17.17 0 0 0-.204.035a.16.16 0 0 0-.018.205m.222-.24l-.16.198m2.054.041l-.062-.041m.062.041l-.062-.041m.062.041c-.224.34-.614.566-1.058.566c-.443 0-.833-.226-1.057-.565m2.053-.042a1.19 1.19 0 0 1-.996.532a1.19 1.19 0 0 1-.995-.532m-.062.042l.062-.042m-.062.042l.062-.042");
}

.wpgg6c2wy {
  stop-color: var(--svg-color--d69791, #D69791);
}

.wszthn3gy {
  stop-color: var(--svg-color--bc7f83, #BC7F83);
  stop-opacity: 0;
}

.wuailr9fb {
  stop-color: var(--svg-color--bf6a4c, #BF6A4C);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x0oemnbnc {
  stop-color: var(--svg-color--a06e60, #A06E60);
}

.x3almbbjn {
  stroke: var(--svg-color--98643d, #98643D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.76 7.303a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.x4_b-2r_f {
  stop-color: var(--svg-color--9f6048, #9F6048);
}

.xdsljxb6l {
  stop-color: var(--svg-color--dcb195, #DCB195);
}

.xk0g-_c-a {
  fill: var(--svg-color--d2a089, #D2A089);
  fill-rule: evenodd;
  d: path("M26.304 23.047a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.xq52vfsiw {
  stroke: var(--svg-color--ebb49a, #EBB49A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.878 23.265c.398 0 .893.047 1.58-.109");
}

.xx2sl9hhj {
  stop-color: var(--svg-color--dfb08f, #DFB08F);
  stop-opacity: 0;
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.xy2spr9ic {
  stroke: var(--svg-color--ebb49a, #EBB49A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 24.016c.398 0 1.015-.055 1.773-.438");
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y9e08hgcp {
  fill: var(--svg-color--e5ac8d, #E5AC8D);
  fill-rule: evenodd;
  d: path("M6.818 24.172c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.ydcxvabaw {
  stop-color: var(--svg-color--ff7d3c, #FF7D3C);
}

.ydii2-bnu {
  d: path("m16.179 4.256l-.042-.086a.42.42 0 0 0-.387-.263h-.8c-1.16 0-2.101.95-2.101 2.124v.173c-.214-.162-.483-.506-.483-1.061c0-.674.492-1.015.805-1.232a1.4 1.4 0 0 0 .208-.16q.03-.029.063-.065c.22-.233.611-.648 1.295-.83c.22-.058.442-.088.647-.1c.472-.025.808.386.808.859v.632z");
}

.ye-czfbqo {
  stop-color: var(--svg-color--efba9d, #EFBA9D);
}

.yeoml4btx {
  stop-color: var(--svg-color--a06e60, #A06E60);
  stop-opacity: 0;
}

.ygz2-cccw {
  fill-rule: evenodd;
  d: path("M25.267 24.195c-.14.17-.272.303-.101.443c.565.464.85.628 1.108.76l.072.037a.4.4 0 0 0 .367-.711l-.074-.038c-.243-.123-.38-.123-.88-.532c-.17-.14-.352-.13-.492.04");
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

.z2ao1lh1t {
  stop-color: var(--svg-color--e9ae9a, #E9AE9A);
}

.z321yabtz {
  stop-color: var(--svg-color--d3612e, #D3612E);
  stop-opacity: 0;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.z800wxkkv {
  stop-color: var(--svg-color--b57253, #B57253);
}

.z8ahlcg8v {
  stroke: var(--svg-color--7f492d, #7F492D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.97 7.303a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.zdrx7pbdl {
  fill: var(--svg-color--e5ab8a, #E5AB8A);
  fill-rule: evenodd;
  d: path("M6.099 23.947a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.zhiua4b9h {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.762 7.575l-.435 1.041c-.064.238.089.476.306.476h.462c.216 0 .37-.242.306-.476l-.313-1.156c-.067-.256-.256-.14-.326.115");
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

.zw0bqzb9t {
  fill: var(--svg-color--db9d81, #DB9D81);
  d: path("M9.755 16.08c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.zwg9cab5i {
  stop-color: var(--svg-color--c78d76, #C78D76);
  stop-opacity: 0;
}

</style>
