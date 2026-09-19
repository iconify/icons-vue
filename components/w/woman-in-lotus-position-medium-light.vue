<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#ijmsS9c)" class="d2kvgvbvc"><path fill="url(#iz6Sp3c)" class="b8g0fe45x"/><path fill="url(#iBbMSfB)" class="b8g0fe45x"/><path fill="url(#iPXXysd)" class="b8g0fe45x"/><path fill="url(#iSzQK9b)" class="b8g0fe45x"/><path fill="url(#iZdPLoa)" class="b8g0fe45x"/><path fill="url(#irTVZUc)" class="b8g0fe45x"/><path fill="url(#iQqEQee)" class="b8g0fe45x"/><path fill="url(#iNSHxwd)" class="b8g0fe45x"/><path fill="url(#iA9toTd)" class="b8g0fe45x"/><path fill="url(#iKjju5c)" class="b8g0fe45x"/></g><path fill="url(#idZZX5I)" clip-rule="evenodd" class="v-p5omnxm"/><path fill="url(#ir2Gbac)" clip-rule="evenodd" class="bqwscm-5z"/><g filter="url(#itnnorb)"><path fill="url(#imSU0Kd)" class="mxe5l-b8x"/><path fill="url(#iRQN6pc)" class="mxe5l-b8x"/></g><path fill="url(#iJ6HVme)" class="qwmps2bvc"/><path fill="url(#iri4lPe)" class="qwmps2bvc"/><g filter="url(#iNLP2Je)"><path class="v8-ymtd1a"/></g><path fill="url(#iMQI23d)" class="qqq97ebkd"/><path fill="url(#i8GVCXd)" class="qqq97ebkd"/><path fill="url(#ileYPJZ)" class="qqq97ebkd"/><path fill="url(#ijGmsMc)" class="m8zsuwtqz"/><path fill="url(#i1jqf0c)" class="m8zsuwtqz"/><path fill="url(#i0PCseb)" class="m8zsuwtqz"/><path fill="url(#i6dV9Ge)" class="gqrdhsbjl"/><path fill="url(#i8UYDgd)" class="gqrdhsbjl"/><path fill="url(#iWAVhbe)" class="gqrdhsbjl"/><path class="zw0bqzb9t"/><path fill="url(#iIcijtb)" class="ndxr44g2h"/><path fill="url(#iCXimYc)" class="ndxr44g2h"/><path fill="url(#itZ0fRb)" class="ndxr44g2h"/><g filter="url(#inNzyeb)"><path class="hnksfxbro"/><path fill="url(#ijTQx5b)" class="vvb767b_n"/><path fill="url(#iyCfyue)" class="vvb767b_n"/><path fill="url(#iDCoLrd)" class="vvb767b_n"/></g><g filter="url(#ixH3osc)"><path fill="url(#ivci6pe)" class="ha61p4glz"/></g><g filter="url(#itGDllb)"><path fill="url(#i5InDnb)" class="elnrcdbjr"/><path fill="url(#isUHzSd)" class="elnrcdbjr"/></g><path fill="url(#i2yHPVb)" class="d56lu3b4e"/><path fill="url(#iKYViAd)" class="d56lu3b4e"/><path fill="url(#i4Cy5Hn)" class="d56lu3b4e"/><path clip-rule="evenodd" class="auf2_ybvr"/><path fill="url(#iq2BZxb)" clip-rule="evenodd" class="vncbe3bae"/><path clip-rule="evenodd" class="xk0g-_c-a"/><path fill="url(#ixdbthd)" clip-rule="evenodd" class="luuu6sb3x"/><path clip-rule="evenodd" class="tx3o8_15z"/><path fill="url(#iFDyIDj)" clip-rule="evenodd" class="w--l981bs"/><path clip-rule="evenodd" class="a0wxo0yuj"/><path fill="url(#iyc6OsL)" clip-rule="evenodd" class="jch7h-fqu"/><path clip-rule="evenodd" class="zdrx7pbdl"/><path fill="url(#icwCknb)" clip-rule="evenodd" class="oau0_1brx"/><path clip-rule="evenodd" class="vcgmrjd8s"/><path fill="url(#iIXeuoK)" clip-rule="evenodd" class="gfi5steoc"/><path clip-rule="evenodd" class="y9e08hgcp"/><path fill="url(#i9ZWnye)" clip-rule="evenodd" class="op0wkpb0r"/><path fill="url(#iNlmOGO)" clip-rule="evenodd" class="ygz2-cccw"/><path fill="url(#ibUjcnj)" clip-rule="evenodd" class="ygz2-cccw"/><g filter="url(#iH9NqHe)"><path class="ffzgmgbfc"/></g><g filter="url(#i0LwvBd)"><path stroke="url(#iiexQQc)" class="eevmxtb1v"/></g><g filter="url(#i9myVFc)"><path class="gw26_ntap"/></g><g filter="url(#ii35J9d)"><path stroke="url(#iEdOs4b)" class="rmafx6bat"/></g><g filter="url(#i9rUdie)"><path class="xy2spr9ic"/></g><g filter="url(#iPp3mhc)"><path stroke="url(#i2JUGPe)" class="fvsn5ytmb"/></g><g filter="url(#iNws5Me)"><path class="xq52vfsiw"/></g><g filter="url(#i3KkqLk)"><path stroke="url(#iL3XsGd)" class="fj_0iw0tn"/></g><g filter="url(#iitQ92i)"><path fill="url(#ivOr2Zd)" class="q-o2a1b8x"/></g><g filter="url(#iqeq4Ie)"><path fill="url(#il2zbze)" class="zh8if8v_e"/><path fill="url(#iwSbZer)" class="zh8if8v_e"/></g><g filter="url(#ij0zvJe)"><path class="a0ce5r9zl"/><path fill="url(#iB3JbWc)" class="s6w4vh0bu"/></g><g filter="url(#ibh7dfd)"><path class="vgoakxyhw"/><path fill="url(#iwwDhKu)" class="yniglx2of"/></g><g filter="url(#iMit0hc)"><path fill="url(#iDMCrTd)" class="vb_8ixbon"/><path fill="url(#iJrywcd)" class="vb_8ixbon"/><path fill="url(#iDeBo6b)" class="vb_8ixbon"/><path fill="url(#i2QC6Dd)" class="vb_8ixbon"/><path fill="url(#i2MnsBe)" class="vb_8ixbon"/><path fill="url(#iFLX3oG)" class="vb_8ixbon"/><path fill="url(#i7ZAvhc)" class="vb_8ixbon"/></g><path fill="url(#ik2nWGb)" class="yyh74g4vt"/><path fill="url(#isSyDGb)" class="yyh74g4vt"/><path fill="url(#iQ2Rdgd)" class="yyh74g4vt"/><g filter="url(#iRUjp8b)"><path class="viufxqkzv"/></g><g filter="url(#imyCUoe)"><path class="binui-esk"/><path fill="url(#iDXVfBe)" class="i2wn_xbjv"/><path fill="url(#iXiu8fb)" class="i2wn_xbjv"/><path fill="url(#iSMhHvt)" class="i2wn_xbjv"/></g><g filter="url(#i9AGb4c)"><path stroke="url(#iZCtdGd)" class="hpimkt8nn"/></g><path class="o-tn6qjbx"/><g filter="url(#iPaOpHR)"><path class="n6fyop73o"/></g><g filter="url(#iunKbQe)"><path clip-rule="evenodd" class="kelppzbey"/></g><g filter="url(#iMQmRHd)"><path class="jd14lfmtj"/></g><g filter="url(#iQmAeku)"><path class="zwbwv9oku"/></g><g filter="url(#iBkNCLP)"><path fill="url(#i3PhNAb)" class="s52pl8nbr"/><path fill="url(#iEKiMHE)" class="s52pl8nbr"/></g><g filter="url(#i18LhVd)"><path fill="url(#i1tKkAH)" class="vpd8tub0e"/><path fill="url(#iGpdmMZ)" class="vpd8tub0e"/><path fill="url(#ifkhg6b)" class="vpd8tub0e"/></g><g filter="url(#iTiyYmc)"><path stroke="url(#iYavQdb)" class="ncdw1g-ke"/></g><path class="z8ahlcg8v"/><g filter="url(#iJBKMDd)"><path class="n0m4asbit"/></g><path class="w8oa9vb5w"/><g filter="url(#igFwQKw)"><path class="x3almbbjn"/></g><defs><radialGradient id="iBbMSfB" cx="0" cy="0" r="1" gradientTransform="rotate(-64.29 18.485 -9.459)scale(2.54181 5.7955)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iPXXysd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.19456 3.45475 -3.23387 -1.11818 15.595 8.734)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iSzQK9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9933 1.548 -1.9055 -2.45364 14.047 9.37)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iZdPLoa" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 4.46 7.248)scale(1.12661 1.02404)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="irTVZUc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47378 -.32867 .48315 -2.16645 13.295 6.815)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iQqEQee" cx="0" cy="0" r="1" gradientTransform="rotate(55.684 4.119 14.28)scale(2.42621 4.23406)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="iNSHxwd" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 8.872 6.28)scale(1.03559 1.44722)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iA9toTd" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 9.88 5.02)scale(1.21459 2.64279)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iKjju5c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9933 .8482 -1.35144 -3.17594 20.6 8.84)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="idZZX5I" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.354 13.087)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="lic6lbbau"/><stop offset="1" class="gpe3o1c3d"/></radialGradient><radialGradient id="ir2Gbac" cx="0" cy="0" r="1" gradientTransform="rotate(174.454 13.31 11.984)scale(.83202 .3356)" gradientUnits="userSpaceOnUse"><stop class="xdsljxb6l"/><stop offset="1" class="gkxm7k0ja"/></radialGradient><radialGradient id="imSU0Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.187)" gradientUnits="userSpaceOnUse"><stop class="owzxb4bzq"/><stop offset="1" class="vsjc8v9ca"/></radialGradient><radialGradient id="iRQN6pc" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -6.868 31.62)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="z800wxkkv"/><stop offset="1" class="zwg9cab5i"/></radialGradient><radialGradient id="iJ6HVme" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.531)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="wpgg6c2wy"/><stop offset="1" class="boxw_edme"/></radialGradient><radialGradient id="iri4lPe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.172)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="vf-atc5np"/><stop offset="1" class="z2ao1lh1t"/></radialGradient><radialGradient id="iMQI23d" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .21875 -.60896 -2.43587 21.294 25.864)" gradientUnits="userSpaceOnUse"><stop class="dxvi3ib7v"/><stop offset="1" class="ncrbay0xj"/></radialGradient><radialGradient id="i8GVCXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.7705 1.76305 5.29137 5.576 25.74)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="t0tmblryn"/><stop offset="1" class="c16c1ob7o"/></radialGradient><radialGradient id="ileYPJZ" cx="0" cy="0" r="1" gradientTransform="matrix(.67187 .90625 -1.49816 1.1107 7.232 23.874)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="p6zke3bbd"/><stop offset="1" class="bmjjdqblu"/></radialGradient><radialGradient id="ijGmsMc" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.094)" gradientUnits="userSpaceOnUse"><stop class="r40r2-btv"/><stop offset="1" class="w68v077cg"/></radialGradient><radialGradient id="i6dV9Ge" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 22.82)" gradientUnits="userSpaceOnUse"><stop class="oudqrddpb"/><stop offset="1" class="ex-njr0bb"/></radialGradient><radialGradient id="iIcijtb" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.157 23.495)" gradientUnits="userSpaceOnUse"><stop class="nh2d_e3ja"/><stop offset="1" class="s1mkhyyat"/></radialGradient><radialGradient id="itZ0fRb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 20)" gradientUnits="userSpaceOnUse"><stop class="p5dagkb6w"/><stop offset="1" class="d2qw4t-ma"/></radialGradient><radialGradient id="iyCfyue" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.237 7.531)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="be02pvbwh"/><stop offset="1" class="xx2sl9hhj"/></radialGradient><radialGradient id="iDCoLrd" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.094)" gradientUnits="userSpaceOnUse"><stop class="h4omf55qi"/><stop offset="1" class="sqb0hacke"/></radialGradient><radialGradient id="ivci6pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.094)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="i5InDnb" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.068 2.398)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="ye-czfbqo"/><stop offset="1" class="ok-7tsxgn"/></radialGradient><radialGradient id="isUHzSd" cx="0" cy="0" r="1" gradientTransform="rotate(118.757 4.54 9.687)scale(3.02046 3.40652)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="gcnznbcnc"/><stop offset="1" class="s3p5ymzwk"/></radialGradient><radialGradient id="i2yHPVb" cx="0" cy="0" r="1" gradientTransform="matrix(.48635 10.50004 -6.22624 .2884 17.69 13.28)" gradientUnits="userSpaceOnUse"><stop offset=".056" class="q9yk7oosj"/><stop offset="1" class="ddgxe2b5l"/></radialGradient><radialGradient id="iKYViAd" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.577 10.752)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="xz9f7bbos"/><stop offset="1" class="auvxm7b4e"/></radialGradient><radialGradient id="i4Cy5Hn" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 11.812)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="gd3w__bkb"/><stop offset="1" class="gz75fzb0l"/></radialGradient><radialGradient id="iq2BZxb" cx="0" cy="0" r="1" gradientTransform="matrix(.11328 .6422 -3.96388 .69921 4.51 23.047)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="l7q7_gbnx"/><stop offset="1" class="pduv-n6bl"/></radialGradient><radialGradient id="ixdbthd" cx="0" cy="0" r="1" gradientTransform="matrix(-.11328 .6422 -3.96388 -.69922 27.49 23.047)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="wszthn3gy"/><stop offset="1" class="uwzafok6o"/></radialGradient><radialGradient id="iFDyIDj" cx="0" cy="0" r="1" gradientTransform="matrix(.12686 .83746 -4.47454 .67782 4.517 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="l7q7_gbnx"/><stop offset="1" class="pduv-n6bl"/></radialGradient><radialGradient id="iyc6OsL" cx="0" cy="0" r="1" gradientTransform="matrix(-.12686 .83746 -4.47454 -.67782 27.483 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="wszthn3gy"/><stop offset="1" class="uwzafok6o"/></radialGradient><radialGradient id="icwCknb" cx="0" cy="0" r="1" gradientTransform="matrix(.11226 .95131 -3.99486 .47143 5 24.226)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="l7q7_gbnx"/><stop offset="1" class="pduv-n6bl"/></radialGradient><radialGradient id="iIXeuoK" cx="0" cy="0" r="1" gradientTransform="rotate(96.73 2.732 24.113)scale(.95791 4.02259)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="wszthn3gy"/><stop offset="1" class="uwzafok6o"/></radialGradient><radialGradient id="i9ZWnye" cx="0" cy="0" r="1" gradientTransform="matrix(.10014 1.0686 -3.5818 .33567 5.935 24.41)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="l7q7_gbnx"/><stop offset="1" class="pduv-n6bl"/></radialGradient><radialGradient id="ibUjcnj" cx="0" cy="0" r="1" gradientTransform="matrix(-.10014 1.0686 -3.5818 -.33567 26.065 24.411)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="d42ncfbkl"/><stop offset="1" class="fizdybc8y"/></radialGradient><radialGradient id="il2zbze" cx="0" cy="0" r="1" gradientTransform="matrix(1.5745 -.71568 .87381 1.92238 18.575 7.896)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iwSbZer" cx="0" cy="0" r="1" gradientTransform="matrix(.63086 .18024 -.09476 .33167 19.221 6.491)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iB3JbWc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 31.163 -48.976)scale(.82524)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iwwDhKu" cx="0" cy="0" r="1" gradientTransform="matrix(-.76975 0 0 -.73631 13.068 7.618)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iDMCrTd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.11395 1.89708 -2.5392 -5.50645 17.828 7.278)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iJrywcd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33455 .7059 -.5989 -1.13227 17.222 7.72)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iDeBo6b" cx="0" cy="0" r="1" gradientTransform="matrix(.52941 -2.55882 3.24667 .67173 14.64 11.569)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i2QC6Dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.70472 -6.37754 0 16.02 7.097)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="gxm-dc6uw"/></radialGradient><radialGradient id="i2MnsBe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62611 .4877 -.83966 -6.24305 16.422 8.755)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iFLX3oG" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72794 1.0465 0 17.475 7.014)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="i7ZAvhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.8603 .98595 0 14.806 7.069)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="ik2nWGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.85204 0 0 -2.80494 19.243 7.955)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="isSyDGb" cx="0" cy="0" r="1" gradientTransform="matrix(.7314 2.66865 -5.51462 1.51141 14.438 3.795)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iQ2Rdgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.65548 -6.23576 0 16.267 5.229)" gradientUnits="userSpaceOnUse"><stop offset=".729" class="nku1qjb2e"/><stop offset=".957" class="lihjh37-b"/></radialGradient><radialGradient id="iDXVfBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.44119 -1.54963 .88672 -.25245 16.516 8.414)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i3PhNAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.22393 1.69643 -3.3708 2.43196 12.251 3.666)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="iEKiMHE" cx="0" cy="0" r="1" gradientTransform="rotate(127.118 6.203 5.463)scale(1.9679 1.54335)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="i1tKkAH" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.795 6.718)scale(3.08244 4.3831)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iGpdmMZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.54198 2.02878 -3.62143 -.96745 17.483 3.348)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="ifkhg6b" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 10.42 -1.55)scale(4.5611 4.08284)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="ijmsS9c" width="9.75" height="10.25" x="11.27" y="1.474" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/></filter><filter id="itnnorb" width="9.729" height="6.156" x="17.627" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.521569 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.470588 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23995" result="effect2_innerShadow_3987_23995"/></filter><filter id="iNLP2Je" width="17.213" height="7.995" x="5.751" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.584314 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.470588 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23995" result="effect2_innerShadow_3987_23995"/></filter><filter id="inNzyeb" width="7.621" height="12.797" x="19.836" y="11.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.470588 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/></filter><filter id="ixH3osc" width="8.502" height="3.19" x="11.869" y="21.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/></filter><filter id="itGDllb" width="5.834" height="4.108" x="13.158" y="10.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.639216 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/></filter><filter id="iH9NqHe" width="1.684" height="1.255" x="5.351" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".075"/></filter><filter id="i0LwvBd" width="1.684" height="1.255" x="24.965" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".075"/></filter><filter id="i9myVFc" width="2.04" height="1.095" x="4.237" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".075"/></filter><filter id="ii35J9d" width="2.04" height="1.095" x="25.723" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".075"/></filter><filter id="i9rUdie" width="2.223" height=".888" x="3.593" y="23.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".075"/></filter><filter id="iPp3mhc" width="2.223" height=".888" x="26.184" y="23.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".075"/></filter><filter id="iNws5Me" width="2.031" height=".566" x="3.653" y="22.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".075"/></filter><filter id="i3KkqLk" width="2.031" height=".566" x="26.317" y="22.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".075"/></filter><filter id="iitQ92i" width="2.186" height="2.286" x="12.038" y="6.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/></filter><filter id="iqeq4Ie" width="2.036" height="2.286" x="18.055" y="6.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/></filter><filter id="ij0zvJe" width="2.359" height="2.359" x="17.894" y="6.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".25"/></filter><filter id="ibh7dfd" width="2.159" height="2.159" x="11.988" y="6.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".2"/></filter><filter id="iMit0hc" width="6.446" height="7.13" x="12.796" y="4.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/></filter><filter id="iRUjp8b" width="2.188" height="2.696" x="14.823" y="6.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".25"/></filter><filter id="imyCUoe" width="1.387" height="1.896" x="15.326" y="7.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".05"/></filter><filter id="i9AGb4c" width="2.489" height="1.112" x="14.775" y="9.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".05"/></filter><filter id="iPaOpHR" width="1.625" height=".764" x="13.61" y="5.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/></filter><filter id="iunKbQe" width="1.625" height=".764" x="17.038" y="5.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23995"/></filter><filter id="iMQmRHd" width="1.351" height=".539" x="17.097" y="5.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".05"/></filter><filter id="iQmAeku" width="1.351" height=".539" x="13.648" y="5.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".05"/></filter><filter id="iBkNCLP" width="3.079" height="3.688" x="11.877" y="2.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".25"/></filter><filter id="i18LhVd" width="5.723" height="3.74" x="13.879" y="2.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".1"/></filter><filter id="iTiyYmc" width=".945" height="1.681" x="13.89" y="3.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".1"/></filter><filter id="iJBKMDd" width="1.628" height=".644" x="13.82" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".05"/></filter><filter id="igFwQKw" width="1.628" height=".644" x="16.609" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23995" stdDeviation=".05"/></filter><linearGradient id="iz6Sp3c" x1="18.988" x2="14.684" y1="3.22" y2="11.194" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="i1jqf0c" x1="21.525" x2="21.525" y1="21.031" y2="22.187" gradientUnits="userSpaceOnUse"><stop class="u-ogeqbld"/><stop offset="1" class="jiqak5-_m"/></linearGradient><linearGradient id="i0PCseb" x1="18.658" x2="19.892" y1="24.315" y2="24.719" gradientUnits="userSpaceOnUse"><stop offset=".106" class="x0oemnbnc"/><stop offset="1" class="yeoml4btx"/></linearGradient><linearGradient id="i8UYDgd" x1="10.822" x2="10.822" y1="21.031" y2="22.187" gradientUnits="userSpaceOnUse"><stop class="x4_b-2r_f"/><stop offset="1" class="qlojknfdm"/></linearGradient><linearGradient id="iWAVhbe" x1="13.689" x2="12.455" y1="24.315" y2="24.719" gradientUnits="userSpaceOnUse"><stop offset=".106" class="t_z-23bug"/><stop offset="1" class="kkbuv9ocm"/></linearGradient><linearGradient id="iCXimYc" x1="12.24" x2="10.033" y1="20.637" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".184" class="pu7ffqbdj"/><stop offset="1" class="qlidsibqc"/></linearGradient><linearGradient id="ijTQx5b" x1="19.835" x2="22.042" y1="20.637" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".184" class="wuailr9fb"/><stop offset="1" class="hidnebcsy"/></linearGradient><linearGradient id="iNlmOGO" x1="26.466" x2="25.091" y1="25.203" y2="24.046" gradientUnits="userSpaceOnUse"><stop offset=".198" class="kdydwf0xq"/><stop offset=".789" class="e7cxleyvf"/></linearGradient><linearGradient id="iiexQQc" x1="26.516" x2="25.268" y1="25.114" y2="24.986" gradientUnits="userSpaceOnUse"><stop class="us91czbdi"/><stop offset="1" class="eu_n2kn0k"/></linearGradient><linearGradient id="iEdOs4b" x1="27.656" x2="26.075" y1="24.793" y2="24.534" gradientUnits="userSpaceOnUse"><stop class="us91czbdi"/><stop offset="1" class="eu_n2kn0k"/></linearGradient><linearGradient id="i2JUGPe" x1="28.314" x2="26.645" y1="24.047" y2="24.143" gradientUnits="userSpaceOnUse"><stop class="us91czbdi"/><stop offset="1" class="eu_n2kn0k"/></linearGradient><linearGradient id="iL3XsGd" x1="28.24" x2="26.724" y1="23.273" y2="23.211" gradientUnits="userSpaceOnUse"><stop class="us91czbdi"/><stop offset="1" class="eu_n2kn0k"/></linearGradient><linearGradient id="ivOr2Zd" x1="12.038" x2="13.91" y1="7.673" y2="7.673" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iXiu8fb" x1="15.358" x2="15.898" y1="8.425" y2="8.491" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iSMhHvt" x1="16.02" x2="16.02" y1="8.966" y2="8.58" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iZCtdGd" x1="15.558" x2="15.845" y1="9.9" y2="9.349" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="iYavQdb" x1="14.19" x2="14.535" y1="3.697" y2="4.503" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-lotus-position-medium-light" /></template>
<style>
.a0ce5r9zl {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M19.073 8.298a.68.68 0 1 0 0-1.36a.68.68 0 0 0 0 1.36");
}

.a0wxo0yuj {
  fill: var(--svg-color--d2a089, #D2A089);
  fill-rule: evenodd;
  d: path("M26.175 23.525a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.auf2_ybvr {
  fill: var(--svg-color--e5ab8a, #E5AB8A);
  fill-rule: evenodd;
  d: path("M5.697 23.047a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136l-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.auvxm7b4e {
  stop-color: var(--svg-color--422d70, #422D70);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b8g0fe45x {
  d: path("M20.565 8.51c.134-.275.204-.583.204-.903c0-.295-.06-.573-.17-.825h.004a2 2 0 0 0-.178-.325l-.001-.002a2.05 2.05 0 0 1-.333-1.12v-.007a2.087 2.087 0 0 0-2.087-2.087a.34.34 0 0 1-.288-.147a2.09 2.09 0 0 0-3.393 0a.36.36 0 0 1-.288.147l-.054.001a2.087 2.087 0 0 0-2.033 2.086v.007c0 .397-.115.787-.333 1.12l-.001.002a2.09 2.09 0 0 0-.14 2.053a.33.33 0 0 1 0 .288a2.033 2.033 0 0 0 1.83 2.926h5.43a2.033 2.033 0 0 0 1.83-2.926a.33.33 0 0 1 0-.288m-7.756-1.69h-.007l.758 1.49c.078 1.772.77 0 2.46 0s2.426 1.973 2.504.2l.719-2.022c-.034-.788-.605-.843-.719-.843h-2.037a2.44 2.44 0 0 1-2.017-1.059a.167.167 0 0 0-.292.033l-.052.122a1.46 1.46 0 0 1-.752.781l-.033.013l-.032.013c-.15.078-.5.31-.513.91l.007.194z");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.be02pvbwh {
  stop-color: var(--svg-color--dfb298, #DFB298);
}

.binui-esk {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.778 7.39l-.337 1.075a.34.34 0 0 0 .33.443h.497a.342.342 0 0 0 .33-.443L16.26 7.39c-.072-.238-.408-.238-.483 0");
}

.bmjjdqblu {
  stop-color: var(--svg-color--dc9a7c, #DC9A7C);
  stop-opacity: 0;
}

.boxw_edme {
  stop-color: var(--svg-color--b97383, #B97383);
}

.bqwscm-5z {
  fill-rule: evenodd;
  d: path("M25.316 22.957a.5.5 0 0 0 .5.5c.632 0 1.257-.193 1.5-.268l.04-.012a.5.5 0 0 0-.292-.957l-.03.01c-.246.075-.743.227-1.218.227a.5.5 0 0 0-.5.5");
}

.c16c1ob7o {
  stop-color: var(--svg-color--e6a790, #E6A790);
  stop-opacity: 0;
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
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

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.ddgxe2b5l {
  stop-color: var(--svg-color--7455b7, #7455B7);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.dxvi3ib7v {
  stop-color: var(--svg-color--ecb99f, #ECB99F);
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e7cxleyvf {
  stop-color: var(--svg-color--c28369, #C28369);
}

.eevmxtb1v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.055a15 15 0 0 1-1.234-.805");
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.elnrcdbjr {
  d: path("M18.892 11.153v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724c.763-.417 1.77-.784 2.914-.784c1.05 0 2.055.375 2.82.786");
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eu_n2kn0k {
  stop-color: var(--svg-color--daaf97, #DAAF97);
  stop-opacity: 0;
}

.ex-njr0bb {
  stop-color: var(--svg-color--ad765c, #AD765C);
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

.ft5dv1b6b {
  fill: none;
}

.fvsn5ytmb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 24.016a3.8 3.8 0 0 1-1.773-.438");
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gcnznbcnc {
  stop-color: var(--svg-color--cc8760, #CC8760);
}

.gd3w__bkb {
  stop-color: var(--svg-color--785684, #785684);
}

.gfi5steoc {
  fill-rule: evenodd;
  d: path("M25.902 23.947a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 1 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
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

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gw26_ntap {
  stroke: var(--svg-color--ebb49a, #EBB49A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.746c.41-.066 1.204-.313 1.59-.645");
}

.gxm-dc6uw {
  stop-color: var(--svg-color--a46e69, #A46E69);
}

.gz75fzb0l {
  stop-color: var(--svg-color--735ea4, #735EA4);
  stop-opacity: 0;
}

.h4omf55qi {
  stop-color: var(--svg-color--f0be9e, #F0BE9E);
}

.ha61p4glz {
  d: path("m13.447 24.312l-1.578-2.99h8.301l-1.551 2.99z");
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.hidnebcsy {
  stop-color: var(--svg-color--e09978, #E09978);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hnksfxbro {
  fill: var(--svg-color--dd9f7b, #DD9F7B);
  d: path("M22.32 16.08c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.hpimkt8nn {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.02 9.46c-.33 0-.64-.08-.9-.218c-.089-.046-.184.056-.128.139a1.222 1.222 0 0 0 2.055 0c.056-.086-.04-.185-.128-.139c-.26.139-.567.218-.9.218Z");
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i2wn_xbjv {
  d: path("m15.778 7.39l-.337 1.075a.34.34 0 0 0 .33.443h.497a.342.342 0 0 0 .33-.443L16.26 7.39c-.072-.238-.408-.238-.483 0");
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jch7h-fqu {
  fill-rule: evenodd;
  d: path("M26.175 23.525a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.jd14lfmtj {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.247 6.117c.204-.05.711-.024 1.05.218");
}

.jiqak5-_m {
  stop-color: var(--svg-color--b57257, #B57257);
  stop-opacity: 0;
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kdydwf0xq {
  stop-color: var(--svg-color--cf9b8d, #CF9B8D);
}

.kelppzbey {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m18.38 6.204l-.087.146za.17.17 0 0 1-.174.291l-.003-.001l-.072-.037a2 2 0 0 0-.216-.086a1.44 1.44 0 0 0-.678-.058a.17.17 0 0 1-.06-.334c.325-.057.626 0 .841.07a2 2 0 0 1 .353.15l.006.004z");
}

.kkbuv9ocm {
  stop-color: var(--svg-color--ba8165, #BA8165);
  stop-opacity: 0;
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.l7q7_gbnx {
  stop-color: var(--svg-color--da978f, #DA978F);
  stop-opacity: 0;
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lic6lbbau {
  stop-color: var(--svg-color--e9ae87, #E9AE87);
}

.lihjh37-b {
  stop-color: var(--svg-color--c78273, #C78273);
}

.luuu6sb3x {
  fill-rule: evenodd;
  d: path("M26.304 23.047a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.m8zsuwtqz {
  d: path("M18.517 21.323h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.mxe5l-b8x {
  d: path("M17.627 27.937h4.244c2.93 0 4.28-1.916 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.11z");
}

.n0m4asbit {
  stroke: var(--svg-color--98643d, #98643D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.303a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.n6fyop73o {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m13.87 6.494l-.003.001a.17.17 0 0 1-.174-.29v-.001l.003-.001l.006-.004a1 1 0 0 1 .094-.048c.062-.03.15-.068.259-.103c.215-.068.516-.126.84-.069a.17.17 0 0 1-.059.334c-.252-.044-.494 0-.678.058a2 2 0 0 0-.274.115z");
}

.ncdw1g-ke {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.19 3.48c.015.154.149.732.345 1.082");
}

.ncrbay0xj {
  stop-color: var(--svg-color--ecb99f, #ECB99F);
  stop-opacity: 0;
}

.ndxr44g2h {
  d: path("M9.755 16.08c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.nh2d_e3ja {
  stop-color: var(--svg-color--f3bea3, #F3BEA3);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nku1qjb2e {
  stop-color: var(--svg-color--d7998d, #D7998D);
  stop-opacity: 0;
}

.o-tn6qjbx {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16.02 9.46c-.33 0-.64-.08-.9-.218c-.089-.046-.184.056-.128.139a1.222 1.222 0 0 0 2.055 0c.056-.086-.04-.185-.128-.139c-.26.139-.567.218-.9.218");
}

.oau0_1brx {
  fill-rule: evenodd;
  d: path("M6.099 23.947a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.ok-7tsxgn {
  stop-color: var(--svg-color--dda688, #DDA688);
}

.op0wkpb0r {
  fill-rule: evenodd;
  d: path("M6.818 24.172c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.oudqrddpb {
  stop-color: var(--svg-color--d9a183, #D9A183);
}

.owzxb4bzq {
  stop-color: var(--svg-color--d2a28b, #D2A28B);
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p5dagkb6w {
  stop-color: var(--svg-color--95472f, #95472F);
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.p6zke3bbd {
  stop-color: var(--svg-color--d9906f, #D9906F);
}

.pduv-n6bl {
  stop-color: var(--svg-color--da978f, #DA978F);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pu7ffqbdj {
  stop-color: var(--svg-color--b56548, #B56548);
}

.q-o2a1b8x {
  d: path("M13.056 8.636a1.018 1.018 0 1 0 0-2.036a1.018 1.018 0 0 0 0 2.036");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.q9yk7oosj {
  stop-color: var(--svg-color--987fd3, #987FD3);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qlidsibqc {
  stop-color: var(--svg-color--d49179, #D49179);
  stop-opacity: 0;
}

.qlojknfdm {
  stop-color: var(--svg-color--9f6048, #9F6048);
  stop-opacity: 0;
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qqq97ebkd {
  d: path("M10.236 27.937c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.qwmps2bvc {
  d: path("M13.22 24.312h-1.429a1 1 0 0 0-.943.67c-.408 1.171-.96 2.765-1.032 3.002c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.871 2.057-1.735l.052-.078h.42z");
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r40r2-btv {
  stop-color: var(--svg-color--bb8c75, #BB8C75);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rmafx6bat {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.538 24.746c-.41-.066-1.204-.313-1.59-.645");
}

.s1mkhyyat {
  stop-color: var(--svg-color--efba94, #EFBA94);
  stop-opacity: 0;
}

.s3p5ymzwk {
  stop-color: var(--svg-color--d69873, #D69873);
  stop-opacity: 0;
}

.s52pl8nbr {
  d: path("M12.924 3.814c.393-.35.96-.353 1.277-.297l.255.817a.5.5 0 0 0-.43.148c-.286 1.06-1.367.901-1.58 1.696c-.095-.943-.2-1.76.478-2.364");
}

.s6w4vh0bu {
  d: path("M19.073 8.298a.68.68 0 1 0 0-1.36a.68.68 0 0 0 0 1.36");
}

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.sqb0hacke {
  stop-color: var(--svg-color--e09576, #E09576);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.t_z-23bug {
  stop-color: var(--svg-color--9b6054, #9B6054);
}

.t0tmblryn {
  stop-color: var(--svg-color--fcbfa4, #FCBFA4);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tx3o8_15z {
  fill: var(--svg-color--e5ab8a, #E5AB8A);
  fill-rule: evenodd;
  d: path("M5.825 23.525a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.u-ogeqbld {
  stop-color: var(--svg-color--a15d45, #A15D45);
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.us91czbdi {
  stop-color: var(--svg-color--daaf97, #DAAF97);
}

.uwzafok6o {
  stop-color: var(--svg-color--bc7f83, #BC7F83);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v-p5omnxm {
  fill-rule: evenodd;
  d: path("M6.76 22.957a.5.5 0 0 1-.5.5c-.632 0-1.257-.193-1.501-.268l-.04-.012a.5.5 0 0 1 .293-.957l.029.01c.246.075.743.227 1.219.227a.5.5 0 0 1 .5.5");
}

.v8-ymtd1a {
  fill: var(--svg-color--e8b38c, #E8B38C);
  d: path("M10.236 27.937c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.vb_8ixbon {
  d: path("m12.803 6.652l-.007-.194c.013-.6.364-.832.513-.91l.032-.013l.033-.013c.337-.155.61-.426.752-.78l.052-.123a.167.167 0 0 1 .292-.033a2.44 2.44 0 0 0 2.017 1.059h2.037c.114 0 .685.055.719.843l-.075 1.944c-.078 1.772-1.463 2.963-3.153 2.963s-3.074-1.19-3.152-2.963z");
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

.vgoakxyhw {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M13.068 8.298a.68.68 0 1 0 0-1.36a.68.68 0 0 0 0 1.36");
}

.viufxqkzv {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.771 7.477l-.432 1.076a.34.34 0 0 0 .33.442h.497a.342.342 0 0 0 .329-.442l-.336-1.076c-.072-.238-.312-.238-.388 0");
}

.vncbe3bae {
  fill-rule: evenodd;
  d: path("M5.697 23.047a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136l-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.vpd8tub0e {
  d: path("M15.638 2.69c-.717-.158-1.485.605-1.559.87c.976 2.29 2.473 2.072 4.135 1.887c.995-.11 1.103.343 1.188.562c-.276-2.566-2.132-2.958-3.764-3.319");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
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

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
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

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
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

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
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

.xy2spr9ic {
  stroke: var(--svg-color--ebb49a, #EBB49A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 24.016c.398 0 1.015-.055 1.773-.438");
}

.xz9f7bbos {
  stop-color: var(--svg-color--644e9f, #644E9F);
  stop-opacity: 0;
}

.y9e08hgcp {
  fill: var(--svg-color--e5ac8d, #E5AC8D);
  fill-rule: evenodd;
  d: path("M6.818 24.172c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
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

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yniglx2of {
  d: path("M13.068 8.298a.68.68 0 1 0 0-1.36a.68.68 0 0 0 0 1.36");
}

.yyh74g4vt {
  d: path("M12.802 6.82h.007l-.006-.168l-.007-.194c.013-.6.364-.832.513-.91l.032-.013l.033-.013c.337-.155.61-.426.752-.78l.052-.123a.167.167 0 0 1 .292-.033a2.44 2.44 0 0 0 2.017 1.059h2.037c.114 0 .685.055.719.843l-.075 1.944c-.078 1.772-1.463 2.963-3.153 2.963s-3.074-1.19-3.152-2.963z");
}

.z2ao1lh1t {
  stop-color: var(--svg-color--e9ae9a, #E9AE9A);
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

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zdrx7pbdl {
  fill: var(--svg-color--e5ab8a, #E5AB8A);
  fill-rule: evenodd;
  d: path("M6.099 23.947a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.zh8if8v_e {
  d: path("M19.073 8.636a1.018 1.018 0 1 0 0-2.036a1.018 1.018 0 0 0 0 2.036");
}

.zw0bqzb9t {
  fill: var(--svg-color--db9d81, #DB9D81);
  d: path("M9.755 16.08c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.zwbwv9oku {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.849 6.117c-.204-.05-.712-.024-1.05.218");
}

.zwg9cab5i {
  stop-color: var(--svg-color--c78d76, #C78D76);
  stop-opacity: 0;
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
