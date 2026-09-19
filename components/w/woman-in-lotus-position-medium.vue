<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#i0SDRFb)" class="d2kvgvbvc"><path fill="url(#iFQoxUb)" class="fj48qebga"/><path fill="url(#iY7ooEd)" class="fj48qebga"/><path fill="url(#iJe8RZj)" class="fj48qebga"/><path fill="url(#iuuPXtd)" class="fj48qebga"/><path fill="url(#iitL9lb)" class="fj48qebga"/><path fill="url(#ix8eEPd)" class="fj48qebga"/><path fill="url(#il5aZic)" class="fj48qebga"/><path fill="url(#iCAdhjd)" class="fj48qebga"/><path fill="url(#ikwiCAb)" class="fj48qebga"/><path fill="url(#i1RZCjE)" class="fj48qebga"/><path fill="url(#iuxczed)" class="fj48qebga"/><path fill="url(#i4LWpFe)" class="fj48qebga"/></g><path fill="url(#ieTKKyb)" clip-rule="evenodd" class="v-p5omnxm"/><path fill="url(#ix6Vdgc)" clip-rule="evenodd" class="bqwscm-5z"/><g filter="url(#iDHbnvd)"><path fill="url(#iyo2Nte)" class="mxe5l-b8x"/><path fill="url(#i8SL0bb)" class="mxe5l-b8x"/></g><path fill="url(#imh6k8d)" class="qwmps2bvc"/><path fill="url(#ivkLTrd)" class="qwmps2bvc"/><g filter="url(#i42Mrdm)"><path class="s9hud2bil"/></g><path fill="url(#iRHRrrd)" class="qqq97ebkd"/><path fill="url(#i4r1ieb)" class="qqq97ebkd"/><path fill="url(#i5EgdJb)" class="qqq97ebkd"/><path fill="url(#iXY8vte)" class="m8zsuwtqz"/><path fill="url(#iVX833c)" class="m8zsuwtqz"/><path fill="url(#iagd0tc)" class="m8zsuwtqz"/><path fill="url(#iLtCeJd)" class="gqrdhsbjl"/><path fill="url(#iXawENb)" class="gqrdhsbjl"/><path fill="url(#igaeHWd)" class="gqrdhsbjl"/><path class="h5ql4kb6g"/><path fill="url(#iVh47be)" class="ndxr44g2h"/><path fill="url(#i1szBMb)" class="ndxr44g2h"/><path fill="url(#iovxGFb)" class="ndxr44g2h"/><g filter="url(#i147itb)"><path class="mbv-embne"/><path fill="url(#iyUX1Jd)" class="vvb767b_n"/><path fill="url(#iOLZ0cW)" class="vvb767b_n"/><path fill="url(#iOzeqFe)" class="vvb767b_n"/></g><g filter="url(#iEDHG3c)"><path fill="url(#ivci6pe)" class="ha61p4glz"/></g><g filter="url(#i2wKKqd)"><path fill="url(#i01NKmc)" class="xm_vkhc8e"/><path fill="url(#iKUFnmb)" class="xm_vkhc8e"/></g><path fill="url(#i2yHPVb)" class="d56lu3b4e"/><path fill="url(#iKYViAd)" class="d56lu3b4e"/><path fill="url(#i4Cy5Hn)" class="d56lu3b4e"/><path clip-rule="evenodd" class="i19nx45cf"/><path fill="url(#itYWULc)" clip-rule="evenodd" class="y-yhajzcm"/><path clip-rule="evenodd" class="ob_jzvllb"/><path fill="url(#i06IHtd)" clip-rule="evenodd" class="md5c6jb0j"/><path clip-rule="evenodd" class="plwjkgbcu"/><path fill="url(#ikm6jCe)" clip-rule="evenodd" class="w--l981bs"/><path clip-rule="evenodd" class="oyxgmhbah"/><path fill="url(#isRiwAI)" clip-rule="evenodd" class="jch7h-fqu"/><path clip-rule="evenodd" class="j51x2pblc"/><path fill="url(#iBuXhqd)" clip-rule="evenodd" class="mriigjb_g"/><path clip-rule="evenodd" class="obgxu4wfp"/><path fill="url(#i13XCdb)" clip-rule="evenodd" class="fdw6rbsah"/><path clip-rule="evenodd" class="zhncmkv5o"/><path fill="url(#i4Pdzdb)" clip-rule="evenodd" class="op0wkpb0r"/><path fill="url(#i7ixhhM)" clip-rule="evenodd" class="g3wgqm9be"/><path fill="url(#iQqVLLb)" clip-rule="evenodd" class="g3wgqm9be"/><g filter="url(#iQqbCLb)"><path class="o4k-cfqdc"/></g><g filter="url(#iAYLcOT)"><path stroke="url(#i6vmdXd)" class="eevmxtb1v"/></g><g filter="url(#ibobsNc)"><path class="fd18zdsfu"/></g><g filter="url(#i4CQAje)"><path stroke="url(#ijCJzkR)" class="rmafx6bat"/></g><g filter="url(#iIdUG6b)"><path class="pdh31bxtz"/></g><g filter="url(#iKzyOqc)"><path stroke="url(#iJifgBd)" class="fvsn5ytmb"/></g><g filter="url(#ibl7zbd)"><path class="a77vmgktr"/></g><g filter="url(#iexqDqc)"><path stroke="url(#iFR0lWc)" class="fj_0iw0tn"/></g><g filter="url(#iU4f21c)"><path fill="url(#iOwD2ne)" class="xm54pacit"/></g><path fill="url(#inJwQ5d)" class="xm54pacit"/><g filter="url(#iY12ADe)"><path fill="url(#izxp8ge)" class="ecuhe014s"/><path fill="url(#io5FIBb)" class="ecuhe014s"/></g><g filter="url(#i661txe)"><path class="snggjva1s"/><path fill="url(#itRZNsb)" class="gadlax3pj"/></g><g filter="url(#i4XiyHb)"><path class="hmr_dubmk"/><path fill="url(#iMPGzYa)" class="blra1bckb"/></g><g filter="url(#iTtl8ac)"><path fill="url(#iCBDSUc)" class="p4x3aecbj"/><path fill="url(#iLttw6d)" class="p4x3aecbj"/><path fill="url(#iRMV5Xd)" class="p4x3aecbj"/><path fill="url(#iOQyade)" class="p4x3aecbj"/><path fill="url(#iE3IOeo)" class="p4x3aecbj"/><path fill="url(#iK6oE9n)" class="p4x3aecbj"/><path fill="url(#iGamdOc)" class="p4x3aecbj"/><path fill="url(#iA3tWsc)" class="p4x3aecbj"/></g><path fill="url(#ix0VmfS)" class="p4x3aecbj"/><g filter="url(#iVILLQs)"><path class="oj6hd_b8p"/></g><g filter="url(#idAZjOb)"><path class="detells5d"/><path fill="url(#iYGkylb)" class="tc6oczbku"/><path fill="url(#irVZEbe)" class="tc6oczbku"/><path fill="url(#i6KbO8c)" class="tc6oczbku"/><path fill="url(#iBdEe6c)" class="tc6oczbku"/></g><g filter="url(#i6mGuwE)"><path stroke="url(#imYcU2c)" class="owjc3wely"/></g><path class="u3fpl9xlw"/><g filter="url(#ijJOkug)"><path class="r7ync1b_p"/></g><g filter="url(#iVjFW6c)"><path clip-rule="evenodd" class="ghblo_xfz"/></g><g filter="url(#iR27Qwc)"><path class="w2ozrw1jg"/></g><g filter="url(#ikFXHNF)"><path class="tfaodt5uq"/></g><g filter="url(#iR2IyVb)"><path class="fff98tjgn"/><path fill="url(#in8KAAc)" class="qtt-ft6el"/><path fill="url(#iFJI40d)" class="qtt-ft6el"/></g><g filter="url(#iFjPWpc)"><path class="rvb7_lzrr"/></g><path class="db5ke1b9h"/><g filter="url(#iFwLASc)"><path class="qdrbxzb6i"/></g><path class="fimwz6btm"/><g filter="url(#iyypGob)"><path class="vkakb-b8o"/></g><defs><radialGradient id="iY7ooEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3817 2.88392 -3.6026 -.47681 15.842 9.2)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iJe8RZj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8237 1.22992 -1.61602 -2.3962 14.06 9.37)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iuuPXtd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 4.567 7.083)scale(1.36144 1.0454)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iitL9lb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 4.812 6.954)scale(1.56564 1.10286)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="ix8eEPd" cx="0" cy="0" r="1" gradientTransform="matrix(.86941 1.65402 -2.29603 1.20688 13.806 2.52)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="il5aZic" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.067 6.002)scale(1.28948 1.80203)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iCAdhjd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16624 .33929 -.70756 -2.4321 20.783 7.08)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="ikwiCAb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7812 .44532 -.56727 -2.26897 20.401 9.243)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="i1RZCjE" cx="0" cy="0" r="1" gradientTransform="matrix(-.57212 -1.67647 1.326 -.45252 19.026 5.54)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iuxczed" cx="0" cy="0" r="1" gradientTransform="matrix(.95133 .0998 -.16171 1.54143 12.15 7.058)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="i4LWpFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.53012 -2.3432 .8457 -.19133 19.267 6.645)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="ieTKKyb" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.354 13.087)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="ws2mhob-h"/><stop offset="1" class="cp-r2vxwo"/></radialGradient><radialGradient id="ix6Vdgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.60937 .20323 -.41021 -1.22999 27.717 22.624)" gradientUnits="userSpaceOnUse"><stop class="kd9kwmb5m"/><stop offset="1" class="r-5q5hb6k"/></radialGradient><radialGradient id="iyo2Nte" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.187)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="sg1foi1wu"/><stop offset="1" class="p1klu8b2k"/></radialGradient><radialGradient id="i8SL0bb" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -6.868 31.62)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="kx-uu3bcv"/><stop offset="1" class="koh73ykov"/></radialGradient><radialGradient id="imh6k8d" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.531)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="oij_789sb"/><stop offset="1" class="fgo10-bfl"/></radialGradient><radialGradient id="ivkLTrd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.172)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="jmmx0hb4k"/><stop offset="1" class="or-gk9zdk"/></radialGradient><radialGradient id="iRHRrrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .21875 -.60896 -2.43587 21.294 25.864)" gradientUnits="userSpaceOnUse"><stop class="l7-d3obpj"/><stop offset="1" class="awfuupnpj"/></radialGradient><radialGradient id="i4r1ieb" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.7705 1.76305 5.29137 5.576 25.74)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="n3riwubet"/><stop offset="1" class="v-3y1-x4r"/></radialGradient><radialGradient id="i5EgdJb" cx="0" cy="0" r="1" gradientTransform="matrix(.67187 .90625 -1.49816 1.1107 7.232 23.874)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="psz9wvbgc"/><stop offset="1" class="kjhv6n3zi"/></radialGradient><radialGradient id="iXY8vte" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.094)" gradientUnits="userSpaceOnUse"><stop class="mjvnc1bex"/><stop offset="1" class="qlzah1wzj"/></radialGradient><radialGradient id="iLtCeJd" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 22.82)" gradientUnits="userSpaceOnUse"><stop class="e11ubwgsj"/><stop offset="1" class="blyd8fb6w"/></radialGradient><radialGradient id="i1szBMb" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.157 23.495)" gradientUnits="userSpaceOnUse"><stop class="fr7vzibnl"/><stop offset="1" class="ql13ux9_l"/></radialGradient><radialGradient id="iovxGFb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 20)" gradientUnits="userSpaceOnUse"><stop class="d-4gskbey"/><stop offset="1" class="w_0c54bla"/></radialGradient><radialGradient id="iOLZ0cW" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.237 7.531)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="idtmk0bzs"/><stop offset="1" class="n_iu3kb_q"/></radialGradient><radialGradient id="iOzeqFe" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.094)" gradientUnits="userSpaceOnUse"><stop class="g43k_w9lo"/><stop offset="1" class="b1hmbi0gc"/><stop offset="1" class="zsh0_03kt"/></radialGradient><radialGradient id="ivci6pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.094)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="i01NKmc" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.068 2.398)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="bcjyfrafl"/><stop offset="1" class="ly19gqbcr"/></radialGradient><radialGradient id="iKUFnmb" cx="0" cy="0" r="1" gradientTransform="rotate(124.947 4.907 9.149)scale(2.44474 2.75721)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="ytty6sbwb"/><stop offset="1" class="louj_4_he"/></radialGradient><radialGradient id="i2yHPVb" cx="0" cy="0" r="1" gradientTransform="matrix(.48635 10.50004 -6.22624 .2884 17.69 13.28)" gradientUnits="userSpaceOnUse"><stop offset=".056" class="q9yk7oosj"/><stop offset="1" class="ddgxe2b5l"/></radialGradient><radialGradient id="iKYViAd" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.577 10.752)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="xz9f7bbos"/><stop offset="1" class="auvxm7b4e"/></radialGradient><radialGradient id="i4Cy5Hn" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 11.812)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="gd3w__bkb"/><stop offset="1" class="gz75fzb0l"/></radialGradient><radialGradient id="itYWULc" cx="0" cy="0" r="1" gradientTransform="matrix(.11328 .6422 -3.96388 .69921 4.51 23.047)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="t2t46ho0j"/><stop offset="1" class="v5op15mpp"/></radialGradient><radialGradient id="i06IHtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.11328 .6422 -3.96388 -.69922 27.49 23.047)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="h9o--2dhj"/><stop offset="1" class="dranwgbob"/></radialGradient><radialGradient id="ikm6jCe" cx="0" cy="0" r="1" gradientTransform="matrix(.12686 .83746 -4.47454 .67782 4.517 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="t2t46ho0j"/><stop offset="1" class="v5op15mpp"/></radialGradient><radialGradient id="isRiwAI" cx="0" cy="0" r="1" gradientTransform="matrix(-.12686 .83746 -4.47454 -.67782 27.483 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="h9o--2dhj"/><stop offset="1" class="dranwgbob"/></radialGradient><radialGradient id="iBuXhqd" cx="0" cy="0" r="1" gradientTransform="matrix(.11226 .95131 -3.99486 .47143 5 24.226)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="t2t46ho0j"/><stop offset="1" class="v5op15mpp"/></radialGradient><radialGradient id="i13XCdb" cx="0" cy="0" r="1" gradientTransform="rotate(96.73 2.732 24.113)scale(.95791 4.02259)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="h9o--2dhj"/><stop offset="1" class="dranwgbob"/></radialGradient><radialGradient id="i4Pdzdb" cx="0" cy="0" r="1" gradientTransform="matrix(.10014 1.0686 -3.5818 .33567 5.935 24.411)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="t2t46ho0j"/><stop offset="1" class="v5op15mpp"/></radialGradient><radialGradient id="iQqVLLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10014 1.0686 -3.5818 -.33567 26.065 24.411)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="h9o--2dhj"/><stop offset="1" class="dranwgbob"/></radialGradient><radialGradient id="inJwQ5d" cx="0" cy="0" r="1" gradientTransform="rotate(-118.51 8.978 .505)scale(.86633 .98166)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="izxp8ge" cx="0" cy="0" r="1" gradientTransform="matrix(1.5745 -.71568 .87381 1.92238 18.587 7.896)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="io5FIBb" cx="0" cy="0" r="1" gradientTransform="matrix(.7634 0 0 .32868 19.16 6.539)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="itRZNsb" cx="0" cy="0" r="1" gradientTransform="matrix(.9551 -.07105 .05554 .74663 18.81 7.69)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iMPGzYa" cx="0" cy="0" r="1" gradientTransform="rotate(-179.86 6.56 3.81)scale(.66797)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iCBDSUc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.11395 1.89708 -2.5392 -5.50645 17.841 7.278)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iLttw6d" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.817 5.726)scale(1.50679 1.04931)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iRMV5Xd" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 15.198 -4.426)scale(2.61534 3.31838)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iOQyade" cx="0" cy="0" r="1" gradientTransform="rotate(99.884 5.39 10.52)scale(4.73431 5.91783)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="iE3IOeo" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.182 5.021)scale(4.45162 7.66432)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iK6oE9n" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72794 .89338 0 17.488 7.014)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iGamdOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.83025 .95153 0 14.719 6.869)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iA3tWsc" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 6.328 9.25)scale(2.11405 1.69159)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="ix0VmfS" cx="0" cy="0" r="1" gradientTransform="matrix(-.81303 0 0 -4.07726 19.256 7.955)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iYGkylb" cx="0" cy="0" r="1" gradientTransform="matrix(-.28816 -1.29298 .39848 -.0888 16.529 8.414)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iBdEe6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.49302 0 0 -.13784 16.377 8.548)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="in8KAAc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33595 2.77789 -4.54169 -2.1842 17.24 2.605)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iFJI40d" cx="0" cy="0" r="1" gradientTransform="matrix(-.13305 .86484 -1.86067 -.28625 16.165 2.839)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="i0SDRFb" width="9.75" height="10.25" x="11.283" y="1.474" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/></filter><filter id="iDHbnvd" width="9.729" height="6.156" x="17.627" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.407843 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.337255 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23992" result="effect2_innerShadow_3987_23992"/></filter><filter id="i42Mrdm" width="17.213" height="7.995" x="5.751" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.447059 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.360784 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23992" result="effect2_innerShadow_3987_23992"/></filter><filter id="i147itb" width="7.621" height="12.797" x="19.836" y="11.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.294118 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/></filter><filter id="iEDHG3c" width="8.502" height="3.19" x="11.869" y="21.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/></filter><filter id="i2wKKqd" width="5.834" height="4.108" x="13.158" y="10.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.447059 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/></filter><filter id="iQqbCLb" width="1.684" height="1.255" x="5.351" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".075"/></filter><filter id="iAYLcOT" width="1.684" height="1.255" x="24.965" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".075"/></filter><filter id="ibobsNc" width="2.04" height="1.095" x="4.237" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".075"/></filter><filter id="i4CQAje" width="2.04" height="1.095" x="25.723" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".075"/></filter><filter id="iIdUG6b" width="2.223" height=".888" x="3.593" y="23.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".075"/></filter><filter id="iKzyOqc" width="2.223" height=".888" x="26.184" y="23.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".075"/></filter><filter id="ibl7zbd" width="2.031" height=".566" x="3.653" y="22.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".075"/></filter><filter id="iexqDqc" width="2.031" height=".566" x="26.317" y="22.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".075"/></filter><filter id="iU4f21c" width="2.186" height="2.036" x="12.05" y="6.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/></filter><filter id="iY12ADe" width="2.036" height="2.286" x="18.068" y="6.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/></filter><filter id="i661txe" width="2.359" height="2.359" x="17.907" y="6.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".25"/></filter><filter id="i4XiyHb" width="2.059" height="2.059" x="12.051" y="6.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".175"/></filter><filter id="iTtl8ac" width="6.446" height="7.13" x="12.809" y="4.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/></filter><filter id="iVILLQs" width="2.188" height="2.696" x="14.836" y="6.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".25"/></filter><filter id="idAZjOb" width="1.488" height="1.996" x="15.289" y="7.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".075"/></filter><filter id="i6mGuwE" width="2.489" height="1.112" x="14.788" y="9.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".05"/></filter><filter id="ijJOkug" width="1.625" height=".764" x="13.623" y="5.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/></filter><filter id="iVjFW6c" width="1.625" height=".764" x="17.05" y="5.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/></filter><filter id="iR27Qwc" width="1.351" height=".539" x="17.109" y="5.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".05"/></filter><filter id="ikFXHNF" width="1.351" height=".539" x="13.661" y="5.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".05"/></filter><filter id="iR2IyVb" width="5.698" height="3.741" x="13.916" y="2.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23992"/><feGaussianBlur result="effect2_foregroundBlur_3987_23992" stdDeviation=".1"/></filter><filter id="iFjPWpc" width="3.917" height="1.984" x="15.739" y="3.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".2"/></filter><filter id="iFwLASc" width="1.628" height=".644" x="13.82" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".05"/></filter><filter id="iyypGob" width="1.628" height=".644" x="16.609" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23992" stdDeviation=".05"/></filter><linearGradient id="iFQoxUb" x1="19.002" x2="15.121" y1="3.22" y2="10.027" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iVX833c" x1="21.525" x2="21.525" y1="21.031" y2="22.187" gradientUnits="userSpaceOnUse"><stop class="aop12fbwl"/><stop offset="1" class="vjrb8p1-v"/></linearGradient><linearGradient id="iagd0tc" x1="18.658" x2="19.892" y1="24.315" y2="24.719" gradientUnits="userSpaceOnUse"><stop offset=".106" class="omwhmkb4w"/><stop offset="1" class="k0b-y7b8g"/></linearGradient><linearGradient id="iXawENb" x1="10.822" x2="10.822" y1="21.031" y2="22.187" gradientUnits="userSpaceOnUse"><stop class="x54l16cbw"/><stop offset="1" class="f1jial7kz"/></linearGradient><linearGradient id="igaeHWd" x1="13.689" x2="12.455" y1="24.315" y2="24.719" gradientUnits="userSpaceOnUse"><stop offset=".106" class="irp1--mlr"/><stop offset="1" class="nq1cvobrk"/></linearGradient><linearGradient id="iVh47be" x1="12.24" x2="10.033" y1="20.637" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".184" class="ickdwm8yu"/><stop offset="1" class="m4mios-ri"/></linearGradient><linearGradient id="iyUX1Jd" x1="19.835" x2="22.042" y1="20.637" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".184" class="rgd-j9bsm"/><stop offset="1" class="r2m9e8bad"/></linearGradient><linearGradient id="i7ixhhM" x1="26.466" x2="25.091" y1="25.203" y2="24.046" gradientUnits="userSpaceOnUse"><stop class="q91o75bcf"/><stop offset=".789" class="m-asxm1xk"/></linearGradient><linearGradient id="i6vmdXd" x1="26.516" x2="25.268" y1="25.114" y2="24.986" gradientUnits="userSpaceOnUse"><stop class="u95ub1zpg"/><stop offset="1" class="sgshpgb8b"/></linearGradient><linearGradient id="ijCJzkR" x1="27.656" x2="26.075" y1="24.793" y2="24.534" gradientUnits="userSpaceOnUse"><stop class="u95ub1zpg"/><stop offset="1" class="sgshpgb8b"/></linearGradient><linearGradient id="iJifgBd" x1="28.314" x2="26.645" y1="24.047" y2="24.143" gradientUnits="userSpaceOnUse"><stop class="u95ub1zpg"/><stop offset="1" class="sgshpgb8b"/></linearGradient><linearGradient id="iFR0lWc" x1="28.24" x2="26.724" y1="23.273" y2="23.211" gradientUnits="userSpaceOnUse"><stop class="u95ub1zpg"/><stop offset="1" class="sgshpgb8b"/></linearGradient><linearGradient id="iOwD2ne" x1="12.05" x2="13.225" y1="7.673" y2="7.673" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="irVZEbe" x1="15.439" x2="16.033" y1="8.46" y2="8.46" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="i6KbO8c" x1="16.033" x2="16.033" y1="8.908" y2="8.511" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="imYcU2c" x1="15.359" x2="15.65" y1="9.858" y2="9.407" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-lotus-position-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a77vmgktr {
  stroke: var(--svg-color--c0998a, #C0998A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.878 23.265c.398 0 .893.047 1.58-.109");
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aop12fbwl {
  stop-color: var(--svg-color--613226, #613226);
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.auvxm7b4e {
  stop-color: var(--svg-color--422d70, #422D70);
}

.awfuupnpj {
  stop-color: var(--svg-color--bf9785, #BF9785);
  stop-opacity: 0;
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b1hmbi0gc {
  stop-color: var(--svg-color--9a766b, #9A766B);
  stop-opacity: 0;
}

.bcjyfrafl {
  stop-color: var(--svg-color--bf9885, #BF9885);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.blra1bckb {
  d: path("M13.08 8.298a.68.68 0 1 0 0-1.36a.68.68 0 0 0 0 1.36");
}

.blyd8fb6w {
  stop-color: var(--svg-color--875f4f, #875F4F);
}

.bqwscm-5z {
  fill-rule: evenodd;
  d: path("M25.316 22.957a.5.5 0 0 0 .5.5c.632 0 1.257-.193 1.5-.268l.04-.012a.5.5 0 0 0-.292-.957l-.03.01c-.246.075-.743.227-1.218.227a.5.5 0 0 0-.5.5");
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.cp-r2vxwo {
  stop-color: var(--svg-color--a47b5f, #A47B5F);
}

.d-4gskbey {
  stop-color: var(--svg-color--5b221f, #5B221F);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d56lu3b4e {
  d: path("M18.892 11.153v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724a6.5 6.5 0 0 0-1.27.896v9.276h8.289v-9.276c-.198-.2-.662-.559-1.285-.894");
}

.db5ke1b9h {
  stroke: var(--svg-color--432534, #432534);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.97 7.303a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.ddgxe2b5l {
  stop-color: var(--svg-color--7455b7, #7455B7);
}

.detells5d {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.79 7.39l-.335 1.075a.34.34 0 0 0 .329.443h.497a.342.342 0 0 0 .33-.443l-.336-1.075c-.072-.238-.409-.238-.484 0");
}

.dranwgbob {
  stop-color: var(--svg-color--88594b, #88594B);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e11ubwgsj {
  stop-color: var(--svg-color--a5826e, #A5826E);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.ecuhe014s {
  d: path("M19.086 8.636a1.018 1.018 0 1 0 0-2.036a1.018 1.018 0 0 0 0 2.036");
}

.eevmxtb1v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.055a15 15 0 0 1-1.234-.805");
}

.f1jial7kz {
  stop-color: var(--svg-color--845c4a, #845C4A);
  stop-opacity: 0;
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fd18zdsfu {
  stroke: var(--svg-color--c0998a, #C0998A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.746c.41-.066 1.204-.313 1.59-.645");
}

.fdw6rbsah {
  fill-rule: evenodd;
  d: path("M25.902 23.947a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 0 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.fff98tjgn {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.65 2.69c-.716-.158-1.36.557-1.434.822c.666 2.242 2.349 2.12 4.01 1.935c.996-.11 1.104.343 1.188.562c0-2.488-2.115-2.955-3.746-3.315z");
}

.fgo10-bfl {
  stop-color: var(--svg-color--935a7c, #935A7C);
}

.fimwz6btm {
  stroke: var(--svg-color--432534, #432534);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.76 7.303a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.fj_0iw0tn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.265c-.398 0-.893.047-1.58-.109");
}

.fj48qebga {
  d: path("M20.578 8.51a2.05 2.05 0 0 0 .205-.903a2.1 2.1 0 0 0-.17-.825h.003a2 2 0 0 0-.178-.325l-.001-.002a2.05 2.05 0 0 1-.333-1.12v-.007a2.087 2.087 0 0 0-2.087-2.087a.34.34 0 0 1-.288-.147a2.09 2.09 0 0 0-3.393 0a.36.36 0 0 1-.288.147l-.054.001a2.087 2.087 0 0 0-2.033 2.086v.007c0 .397-.115.787-.333 1.12l-.001.002a2.09 2.09 0 0 0-.14 2.053a.33.33 0 0 1 0 .288a2.033 2.033 0 0 0 1.83 2.926h5.43a2.033 2.033 0 0 0 1.83-2.926a.33.33 0 0 1 0-.288m-7.755-1.69h-.008l.758 1.49c.078 1.772.77 0 2.46 0s2.426 1.973 2.504.2l.719-2.022c-.034-.788-.605-.843-.719-.843H16.5a2.44 2.44 0 0 1-2.017-1.059a.167.167 0 0 0-.292.033l-.052.122a1.46 1.46 0 0 1-.785.794l-.032.013c-.15.077-.5.31-.512.91l.006.194z");
}

.fr7vzibnl {
  stop-color: var(--svg-color--c79d88, #C79D88);
}

.ft5dv1b6b {
  fill: none;
}

.fvsn5ytmb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 24.016a3.8 3.8 0 0 1-1.773-.438");
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g3wgqm9be {
  fill-rule: evenodd;
  d: path("M25.182 24.172c-.14.17-.272.303-.101.443a5.8 5.8 0 0 0 1.193.783l.072.037a.4.4 0 0 0 .367-.711l-.074-.038a5 5 0 0 1-1.051-.69c-.17-.14-.266.005-.406.176");
}

.g43k_w9lo {
  stop-color: var(--svg-color--c59b85, #C59B85);
}

.gadlax3pj {
  d: path("M19.086 8.298a.68.68 0 1 0 0-1.36a.68.68 0 0 0 0 1.36");
}

.gd3w__bkb {
  stop-color: var(--svg-color--785684, #785684);
}

.ghblo_xfz {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m18.393 6.204l-.087.146za.17.17 0 0 1-.175.291l-.002-.001l-.072-.037a2 2 0 0 0-.216-.086a1.44 1.44 0 0 0-.679-.058a.17.17 0 0 1-.058-.334c.324-.057.625 0 .84.07a2 2 0 0 1 .353.15l.006.004z");
}

.gqrdhsbjl {
  d: path("M13.83 21.323H7.814v2.692c2.531.352 6.016.297 6.016.297z");
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gz75fzb0l {
  stop-color: var(--svg-color--735ea4, #735EA4);
  stop-opacity: 0;
}

.h5ql4kb6g {
  fill: var(--svg-color--a97e62, #A97E62);
  d: path("M9.755 16.08c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.h9o--2dhj {
  stop-color: var(--svg-color--88594b, #88594B);
  stop-opacity: 0;
}

.ha61p4glz {
  d: path("m13.447 24.312l-1.578-2.99h8.301l-1.551 2.99z");
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hmr_dubmk {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M13.08 8.298a.68.68 0 1 0 0-1.36a.68.68 0 0 0 0 1.36");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i19nx45cf {
  fill: var(--svg-color--b18970, #B18970);
  fill-rule: evenodd;
  d: path("M5.697 23.047a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136q-.082-.003-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.ickdwm8yu {
  stop-color: var(--svg-color--87463e, #87463E);
}

.idtmk0bzs {
  stop-color: var(--svg-color--ba9783, #BA9783);
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.irp1--mlr {
  stop-color: var(--svg-color--68413d, #68413D);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j51x2pblc {
  fill: var(--svg-color--b18970, #B18970);
  fill-rule: evenodd;
  d: path("M6.099 23.947a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 0 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jch7h-fqu {
  fill-rule: evenodd;
  d: path("M26.175 23.525a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.jmmx0hb4k {
  stop-color: var(--svg-color--bc8f81, #BC8F81);
  stop-opacity: 0;
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.k0b-y7b8g {
  stop-color: var(--svg-color--7a544e, #7A544E);
  stop-opacity: 0;
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kd9kwmb5m {
  stop-color: var(--svg-color--b99880, #B99880);
}

.kjhv6n3zi {
  stop-color: var(--svg-color--8b5c4d, #8B5C4D);
  stop-opacity: 0;
}

.koh73ykov {
  stop-color: var(--svg-color--855c4f, #855C4F);
  stop-opacity: 0;
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kx-uu3bcv {
  stop-color: var(--svg-color--694137, #694137);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7-d3obpj {
  stop-color: var(--svg-color--bf9785, #BF9785);
}

.louj_4_he {
  stop-color: var(--svg-color--8d6d58, #8D6D58);
  stop-opacity: 0;
}

.ly19gqbcr {
  stop-color: var(--svg-color--a17c62, #A17C62);
}

.m-asxm1xk {
  stop-color: var(--svg-color--a15f4d, #A15F4D);
}

.m4mios-ri {
  stop-color: var(--svg-color--ac8270, #AC8270);
  stop-opacity: 0;
}

.m8zsuwtqz {
  d: path("M18.517 21.323h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.mbv-embne {
  fill: var(--svg-color--a7785f, #A7785F);
  d: path("M22.32 16.08c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.md5c6jb0j {
  fill-rule: evenodd;
  d: path("M26.304 23.047a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136q.082-.003.124-.002a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.mjvnc1bex {
  stop-color: var(--svg-color--916e5e, #916E5E);
}

.mriigjb_g {
  fill-rule: evenodd;
  d: path("M6.099 23.947a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 0 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mxe5l-b8x {
  d: path("M17.627 27.937h4.244c2.93 0 4.28-1.916 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.11z");
}

.n_iu3kb_q {
  stop-color: var(--svg-color--b38b73, #B38B73);
  stop-opacity: 0;
}

.n3riwubet {
  stop-color: var(--svg-color--c39684, #C39684);
}

.ndxr44g2h {
  d: path("M9.755 16.08c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.nq1cvobrk {
  stop-color: var(--svg-color--7e5b4b, #7E5B4B);
  stop-opacity: 0;
}

.o4k-cfqdc {
  stroke: var(--svg-color--c0998a, #C0998A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.576 25.055a15 15 0 0 0 1.234-.805");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.ob_jzvllb {
  fill: var(--svg-color--a97760, #A97760);
  fill-rule: evenodd;
  d: path("M26.304 23.047a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136q.082-.003.124-.002a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.obgxu4wfp {
  fill: var(--svg-color--a97760, #A97760);
  fill-rule: evenodd;
  d: path("M25.902 23.947a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 0 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.oij_789sb {
  stop-color: var(--svg-color--a66d7a, #A66D7A);
}

.oj6hd_b8p {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.785 7.477l-.433 1.076a.34.34 0 0 0 .33.442h.497a.342.342 0 0 0 .33-.442l-.337-1.076c-.072-.238-.312-.238-.388 0");
}

.omwhmkb4w {
  stop-color: var(--svg-color--7a544e, #7A544E);
}

.op0wkpb0r {
  fill-rule: evenodd;
  d: path("M6.818 24.172c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.or-gk9zdk {
  stop-color: var(--svg-color--bc8f81, #BC8F81);
}

.owjc3wely {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.032 9.46c-.33 0-.639-.08-.899-.218c-.089-.046-.184.056-.128.139a1.222 1.222 0 0 0 2.055 0c.056-.086-.04-.185-.128-.139c-.26.139-.567.218-.9.218Z");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.oyxgmhbah {
  fill: var(--svg-color--a97760, #A97760);
  fill-rule: evenodd;
  d: path("M26.175 23.525a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.p1klu8b2k {
  stop-color: var(--svg-color--a6786a, #A6786A);
}

.p4x3aecbj {
  d: path("M12.814 6.82h.008l-.006-.168l-.007-.194c.013-.6.363-.832.513-.91l.032-.013l.032-.013c.338-.155.61-.426.753-.78l.052-.123a.167.167 0 0 1 .292-.033A2.44 2.44 0 0 0 16.5 5.645h2.037c.114 0 .684.055.719.843l-.076 1.944c-.078 1.772-1.462 2.963-3.152 2.963s-3.074-1.19-3.152-2.963z");
}

.pdh31bxtz {
  stroke: var(--svg-color--c0998a, #C0998A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 24.016c.398 0 1.015-.055 1.773-.438");
}

.plwjkgbcu {
  fill: var(--svg-color--b18970, #B18970);
  fill-rule: evenodd;
  d: path("M5.825 23.525a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.psz9wvbgc {
  stop-color: var(--svg-color--8b5c4d, #8B5C4D);
}

.q91o75bcf {
  stop-color: var(--svg-color--a97760, #A97760);
}

.q9yk7oosj {
  stop-color: var(--svg-color--987fd3, #987FD3);
}

.qdrbxzb6i {
  stroke: var(--svg-color--523b3e, #523B3E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.303a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.ql13ux9_l {
  stop-color: var(--svg-color--b58b6f, #B58B6F);
  stop-opacity: 0;
}

.qlzah1wzj {
  stop-color: var(--svg-color--754b41, #754B41);
}

.qqq97ebkd {
  d: path("M10.236 27.937c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.qtt-ft6el {
  d: path("M15.65 2.69c-.716-.158-1.36.557-1.434.822c.666 2.242 2.349 2.12 4.01 1.935c.996-.11 1.104.343 1.188.562c0-2.488-2.115-2.955-3.746-3.315z");
}

.qwmps2bvc {
  d: path("M13.22 24.312h-1.429a1 1 0 0 0-.943.67c-.408 1.171-.96 2.765-1.032 3.002c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.871 2.057-1.735l.052-.078h.42z");
}

.r-5q5hb6k {
  stop-color: var(--svg-color--a68064, #A68064);
}

.r2m9e8bad {
  stop-color: var(--svg-color--b57f6f, #B57F6F);
  stop-opacity: 0;
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r7ync1b_p {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m13.883 6.494l-.002.001a.17.17 0 0 1-.175-.29v-.001h.001l.002-.001l.006-.004l.094-.048a2 2 0 0 1 .26-.103c.214-.068.515-.126.84-.069a.17.17 0 0 1-.06.334c-.252-.044-.494 0-.678.058a2 2 0 0 0-.274.115z");
}

.rgd-j9bsm {
  stop-color: var(--svg-color--8a3e31, #8A3E31);
}

.rmafx6bat {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.538 24.746c-.41-.066-1.204-.313-1.59-.645");
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rvb7_lzrr {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m17.555 4.974l-.902.165a.435.435 0 1 1-.079-.863h1.48c.877 0 1.167.883 1.202 1.184a1.99 1.99 0 0 0-1.701-.486");
}

.s9hud2bil {
  fill: var(--svg-color--b2886c, #B2886C);
  d: path("M10.236 27.937c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.sg1foi1wu {
  stop-color: var(--svg-color--ae8574, #AE8574);
}

.sgshpgb8b {
  stop-color: var(--svg-color--b99884, #B99884);
  stop-opacity: 0;
}

.snggjva1s {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M19.086 8.298a.68.68 0 1 0 0-1.36a.68.68 0 0 0 0 1.36");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t2t46ho0j {
  stop-color: var(--svg-color--a46680, #A46680);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tc6oczbku {
  d: path("m15.79 7.39l-.335 1.075a.34.34 0 0 0 .329.443h.497a.342.342 0 0 0 .33-.443l-.336-1.075c-.072-.238-.409-.238-.484 0");
}

.tfaodt5uq {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.862 6.117c-.204-.05-.712-.024-1.05.218");
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u3fpl9xlw {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.032 9.46c-.33 0-.639-.08-.899-.218c-.089-.046-.184.056-.128.139a1.222 1.222 0 0 0 2.055 0c.056-.086-.04-.185-.128-.139c-.26.139-.567.218-.9.218");
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.u95ub1zpg {
  stop-color: var(--svg-color--b99884, #B99884);
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v-3y1-x4r {
  stop-color: var(--svg-color--ab7d71, #AB7D71);
  stop-opacity: 0;
}

.v-p5omnxm {
  fill-rule: evenodd;
  d: path("M6.76 22.957a.5.5 0 0 1-.5.5c-.632 0-1.257-.193-1.501-.268l-.04-.012a.5.5 0 0 1 .293-.957l.029.01c.246.075.743.227 1.219.227a.5.5 0 0 1 .5.5");
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v5op15mpp {
  stop-color: var(--svg-color--a46680, #A46680);
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vjrb8p1-v {
  stop-color: var(--svg-color--754437, #754437);
  stop-opacity: 0;
}

.vkakb-b8o {
  stroke: var(--svg-color--523b3e, #523B3E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.76 7.303a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.vvb767b_n {
  d: path("M22.32 16.08c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w_0c54bla {
  stop-color: var(--svg-color--965b4a, #965B4A);
  stop-opacity: 0;
}

.w--l981bs {
  fill-rule: evenodd;
  d: path("M5.825 23.525a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w2ozrw1jg {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.26 6.117c.203-.05.71-.024 1.05.218");
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.ws2mhob-h {
  stop-color: var(--svg-color--af896e, #AF896E);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.x54l16cbw {
  stop-color: var(--svg-color--613c31, #613C31);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xm_vkhc8e {
  d: path("M18.892 11.153v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724c.763-.416 1.77-.784 2.914-.784c1.05 0 2.055.375 2.82.786");
}

.xm54pacit {
  d: path("M13.068 8.636a1.018 1.018 0 1 0 0-2.036a1.018 1.018 0 0 0 0 2.036");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xz9f7bbos {
  stop-color: var(--svg-color--644e9f, #644E9F);
  stop-opacity: 0;
}

.y-yhajzcm {
  fill-rule: evenodd;
  d: path("M5.697 23.047a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136q-.082-.003-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.ytty6sbwb {
  stop-color: var(--svg-color--7d5644, #7D5644);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zhncmkv5o {
  fill: var(--svg-color--b18970, #B18970);
  fill-rule: evenodd;
  d: path("M6.818 24.172c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.zsh0_03kt {
  stop-color: var(--svg-color--c59b85, #C59B85);
  stop-opacity: 0;
}

</style>
