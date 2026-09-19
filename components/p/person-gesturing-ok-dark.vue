<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVtC2jd)" class="smk8hf09v"/><path fill="url(#iF0eS2d)" class="z68hxd5ya"/><rect fill="url(#i1jzmsM)" class="o89p0ub4o"/><rect fill="url(#iwu9PIc)" class="o89p0ub4o"/><g filter="url(#iSeI3fd)"><path fill="url(#iP6oNNe)" class="ipqv18bkn"/><path fill="url(#iCukgPc)" class="ipqv18bkn"/><path fill="url(#iWrJLbc)" class="ipqv18bkn"/><path fill="url(#iJ7abwb)" class="ipqv18bkn"/><path fill="url(#iCGvhAc)" class="ipqv18bkn"/></g><path fill="url(#iHiuzzd)" class="ipqv18bkn"/><path fill="url(#iRQwQtd)" class="ipqv18bkn"/><path fill="url(#iohlyyd)" class="ipqv18bkn"/><g filter="url(#iBu43db)"><path class="e0_s-ccjj"/></g><g filter="url(#iZJP0oc)"><path class="hafi0jbga"/><path fill="url(#ik8RsHe)" class="swsuc2b-u"/><path fill="url(#iF11bWd)" class="swsuc2b-u"/><path fill="url(#iENzRlb)" class="swsuc2b-u"/></g><g filter="url(#io3jmzc)"><path fill="url(#igbcIcd)" class="xzfyhsbwz"/><path fill="url(#itgNZYc)" class="xzfyhsbwz"/><path fill="url(#iPGMudd)" class="xzfyhsbwz"/></g><path fill="url(#i5VEzRc)" class="xzfyhsbwz"/><path fill="url(#igMWE0r)" class="xzfyhsbwz"/><g filter="url(#i5B8CKc)"><path class="kbxalxbaa"/><path fill="url(#i1Mauob)" class="p0abytb-y"/><path fill="url(#itorHDe)" class="p0abytb-y"/></g><g filter="url(#iTbQdQe)"><path class="j0tyu7ber"/><path fill="url(#iHLwV1o)" class="nmo6e1i6c"/></g><path class="j85ao0bcf"/><path fill="url(#iLWrcCb)" class="bqw3z_b7a"/><path class="gu6tecb8a"/><g filter="url(#iZeA55b)"><path class="cyxut_buu"/><path fill="url(#i67Cj7c)" class="a9v7zjbuf"/></g><g filter="url(#i0So2NJ)"><path fill="url(#ifA08sb)" class="gw18cjbfi"/></g><path class="auv2jxbee"/><path fill="url(#ih7Knsc)" class="sy43x-b1n"/><path class="z3h-89ams"/><g filter="url(#iyp0drv)"><path fill="url(#iBeM4Pe)" class="mnttfobfp"/></g><g filter="url(#idHITLe)"><ellipse transform="rotate(-27.914 13.302 15.052)" class="t9jirh49o"/><ellipse fill="url(#iwRokhb)" transform="rotate(-27.914 13.302 15.052)" class="s-bvk7j1g"/></g><path fill="url(#iVZS5Fd)" class="t66rxj2ac"/><path fill="url(#i4e9m3b)" class="ho3l0pbty"/><g filter="url(#i6hqbZp)"><path fill="url(#iXolmsU)" class="hbiy7rsgs"/></g><g filter="url(#ibpZX0c)"><path fill="url(#i7VVl2d)" class="rv6kkhbrx"/></g><g filter="url(#iNM6o6g)"><path clip-rule="evenodd" class="imyribcnz"/></g><g filter="url(#iZCISid)"><path stroke="url(#iZE6qYb)" class="vfgu2wb9r"/></g><g filter="url(#izeekue)"><path clip-rule="evenodd" class="sfldthbut"/></g><g filter="url(#iX9R87d)"><path stroke="url(#iyOjS2d)" class="vnfc80b-n"/></g><path stroke="url(#iRoo0ad)" class="mn62upa0i"/><path fill="url(#iMALT6d)" class="ouq4o0bxk"/><path fill="url(#i9KQLOd)" class="ouq4o0bxk"/><path fill="url(#i7tuKPe)" class="ouq4o0bxk"/><path fill="url(#iyxuDgv)" class="ouq4o0bxk"/><path fill="url(#iFzTXbb)" class="ouq4o0bxk"/><path fill="url(#i9wjCNc)" class="ouq4o0bxk"/><path fill="url(#ibnGgSW)" class="ouq4o0bxk"/><path fill="url(#igqVBzb)" class="ouq4o0bxk"/><path fill="url(#iOgytic)" class="ouq4o0bxk"/><path fill="url(#i8dB7mY)" class="ouq4o0bxk"/><path fill="url(#iIAmwnc)" class="ouq4o0bxk"/><path fill="url(#i5Tleib)" class="ouq4o0bxk"/><path fill="url(#iOFv1Kd)" class="nnw551blu"/><path fill="url(#iunZmrd)" class="nnw551blu"/><path fill="url(#iiCAqce)" class="q5kz07b1g"/><path fill="url(#iMnJMKe)" class="q5kz07b1g"/><path fill="url(#ijMXlRd)" class="q5kz07b1g"/><path fill="url(#iTmP2Oc)" class="rljmqdbdm"/><path fill="url(#ijwBDuc)" class="rljmqdbdm"/><path fill="url(#i8OfS4c)" class="tlhnu4bgl"/><path fill="url(#iTPpSQd)" class="tlhnu4bgl"/><g filter="url(#iyOX5dc)"><path fill="url(#iqZdUGc)" class="objo5mqkg"/></g><g filter="url(#itNMMfc)"><path stroke="url(#iYtwOec)" class="d1wh27gbc"/></g><path class="f6dcakbta"/><path stroke="url(#ihUKuxc)" class="g2pfm6b2q"/><path stroke="url(#iHxwskb)" class="g2pfm6b2q"/><path stroke="url(#izBpvyb)" class="p5o93zbvk"/><path stroke="url(#iXn8XNi)" class="p5o93zbvk"/><path stroke="url(#iVKkzHc)" class="p5o93zbvk"/><path stroke="url(#iwusE6d)" class="p5o93zbvk"/><path class="tgg33wray"/><path stroke="url(#i7zGTRd)" class="sulmr2p6z"/><path stroke="url(#i00ry6d)" class="sulmr2p6z"/><path stroke="url(#iw8pEuW)" class="st7zu_bkr"/><path stroke="url(#ix9gD3d)" class="st7zu_bkr"/><path stroke="url(#iKoqpAe)" class="st7zu_bkr"/><path stroke="url(#iwT5Fsb)" class="st7zu_bkr"/><path stroke="url(#iiJHjob)" class="o8eh185ql"/><path class="mwx1nwbkc"/><path stroke="url(#iJMSYzw)" class="o8eh185ql"/><path stroke="url(#iqtdSxd)" class="o8eh185ql"/><path stroke="url(#iOdjE2c)" class="g2nuuigok"/><path stroke="url(#i0ILzFb)" class="g2nuuigok"/><path stroke="url(#iArX0Vc)" class="g2nuuigok"/><path stroke="url(#i8hTXfb)" class="g2nuuigok"/><path class="t9_b9cb9w"/><path stroke="url(#itAc4fe)" class="kktc6hgtz"/><path stroke="url(#isbCP7c)" class="jbemdffol"/><path stroke="url(#icdiSne)" class="jbemdffol"/><path fill="url(#izutHLi)" class="p6n3jab6e"/><path fill="url(#iqPWwyV)" class="p6n3jab6e"/><path fill="url(#i2Y1Iic)" class="sdpofnlol"/><path fill="url(#i4eEaUa)" class="sdpofnlol"/><g filter="url(#ir7dSGc)"><path stroke="url(#i7LgK4A)" class="dngnupbnt"/></g><g filter="url(#iKe3PrF)"><path stroke="url(#iv2Xryd)" class="p6gd-c5_t"/></g><g filter="url(#isNSM3b)"><path stroke="url(#iub8gAb)" class="y5yvssumf"/></g><g filter="url(#iBRYNbc)"><path stroke="url(#ivFL98b)" class="mf8lxmbde"/></g><defs><radialGradient id="iVtC2jd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83944 3.44902 -4.09716 -.99719 22.013 17.025)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="ezh02gbvd"/><stop offset=".837" class="gavknk-rw"/></radialGradient><radialGradient id="iF0eS2d" cx="0" cy="0" r="1" gradientTransform="matrix(1.12646 -.03884 .11746 3.40643 9.637 18.326)" gradientUnits="userSpaceOnUse"><stop class="okxecjbze"/><stop offset=".944" class="khto69bzj"/></radialGradient><radialGradient id="i1jzmsM" cx="0" cy="0" r="1" gradientTransform="matrix(2.4546 2.4656 -3.03258 3.01906 15.09 22.282)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="zu__wcbib"/><stop offset="1" class="v1cdxsyyg"/></radialGradient><radialGradient id="iwu9PIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.83127 1.3003 0 17.007 25.573)" gradientUnits="userSpaceOnUse"><stop class="qdqqfixaa"/><stop offset="1" class="yvt-nqbiu"/></radialGradient><radialGradient id="iP6oNNe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.3125 0 0 -6.42697 16.188 18.125)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="u_pi4nbrf"/><stop offset="1" class="zn3xi9bpn"/></radialGradient><radialGradient id="iCukgPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49619 4.52484 -2.91505 -.9639 18.094 10.188)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="dccrmw9im"/><stop offset="1" class="a_b1i5frv"/></radialGradient><radialGradient id="iJ7abwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.5 1.64835 0 13.516 14.531)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iCGvhAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71875 1.6875 0 18.594 14.813)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="qhgr5vbwq"/><stop offset="1" class="vzcz7obpn"/></radialGradient><radialGradient id="iohlyyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.25755 11.3761 0 16.024 22.718)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="sfdgrznqv"/><stop offset=".369" class="ugplhqxsv"/><stop offset="1" class="w808r0nmy"/></radialGradient><radialGradient id="iENzRlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .1875 -.73438 0 16.414 17.492)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="lwf47ccyr"/><stop offset="1" class="zmkruk91v"/></radialGradient><radialGradient id="itgNZYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.69214 5.50698 0 16.135 10.651)" gradientUnits="userSpaceOnUse"><stop offset=".78" class="wgttxsdys"/><stop offset="1" class="rotm0lbjl"/></radialGradient><radialGradient id="iPGMudd" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 1.22339 -2.53932 3.50266 9.635 9.421)" gradientUnits="userSpaceOnUse"><stop class="elwg_hb8v"/><stop offset="1" class="x-kyklb-a"/></radialGradient><radialGradient id="i5VEzRc" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -2.34375 3.84014 .40961 9.875 14.375)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="kg5wfpbcx"/><stop offset="1" class="lfjjhubys"/></radialGradient><radialGradient id="igMWE0r" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18953 1.36893 -2.21408 -1.92393 20.829 8.51)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="qy05b9bsw"/><stop offset="1" class="aqwz8eb5i"/></radialGradient><radialGradient id="i1Mauob" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70756 0 0 -.70728 16.57 8.075)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="wx87iwb8j"/><stop offset="1" class="ew05122nr"/></radialGradient><radialGradient id="itorHDe" cx="0" cy="0" r="1" gradientTransform="matrix(3.50375 -5.54762 8.14343 5.14321 10.06 12.463)" gradientUnits="userSpaceOnUse"><stop class="bo9ofmw9k"/><stop offset=".288" class="tpx6wbcio"/></radialGradient><radialGradient id="iHLwV1o" cx="0" cy="0" r="1" gradientTransform="matrix(3.21875 .9375 -.3993 1.3709 18.875 8.938)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="oju6c_bmm"/><stop offset="1" class="t39rzsbyn"/></radialGradient><radialGradient id="iLWrcCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88332 -1.40502 0 18.349 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="au361rb0r"/></radialGradient><radialGradient id="i67Cj7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.2525 -.32538 .44797 -.34763 18.1 15.248)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ih7Knsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88336 -1.40509 0 13.597 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="au361rb0r"/></radialGradient><radialGradient id="iwRokhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00842 -.53793 .64661 -.01012 13.286 15.395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVZS5Fd" cx="0" cy="0" r="1" gradientTransform="matrix(1.42879 0 0 1.59032 21.446 15.61)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="dq9t1f2dd"/><stop offset="1" class="glnh1qovj"/></radialGradient><radialGradient id="i4e9m3b" cx="0" cy="0" r="1" gradientTransform="rotate(-175.776 5.531 7.748)scale(1.29257 2.20938)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="ba38z0-_a"/><stop offset="1" class="gb_6b_bzf"/></radialGradient><radialGradient id="iXolmsU" cx="0" cy="0" r="1" gradientTransform="matrix(-.65365 0 0 -1.07747 10.521 15.773)" gradientUnits="userSpaceOnUse"><stop class="px0bqddnx"/><stop offset="1" class="ae7hq_o7r"/></radialGradient><radialGradient id="i7VVl2d" cx="0" cy="0" r="1" gradientTransform="matrix(.96094 .04287 -.03776 .84633 21.358 15.723)" gradientUnits="userSpaceOnUse"><stop class="xlxfzcbzl"/><stop offset="1" class="l-xm7ybzq"/></radialGradient><radialGradient id="i9KQLOd" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 -1.195 15.65)scale(7.05349 6.17563)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="m_2922ixt"/><stop offset="1" class="a-2r3fbgq"/></radialGradient><radialGradient id="i7tuKPe" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.936 8.392)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="h9fb5bbiv"/><stop offset="1" class="j1090kf1c"/></radialGradient><radialGradient id="iyxuDgv" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 9.01 14.858)" gradientUnits="userSpaceOnUse"><stop class="hiycpfc4f"/><stop offset="1" class="mqq2pckgy"/></radialGradient><radialGradient id="iFzTXbb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.197 7.046)" gradientUnits="userSpaceOnUse"><stop class="ew56wjbup"/><stop offset="1" class="qd38sjb7e"/></radialGradient><radialGradient id="i9wjCNc" cx="0" cy="0" r="1" gradientTransform="rotate(123.092 2.514 5.779)scale(1.65986 2.90522)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="jbd_cz55y"/><stop offset="1" class="by6guy4wy"/></radialGradient><radialGradient id="ibnGgSW" cx="0" cy="0" r="1" gradientTransform="rotate(158.664 4.69 10.15)scale(5.43502 6.37816)" gradientUnits="userSpaceOnUse"><stop class="bps78hksv"/><stop offset="1" class="fh1_5ac_k"/></radialGradient><radialGradient id="igqVBzb" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 .71875 -2.2725 1.03746 23.572 6.42)" gradientUnits="userSpaceOnUse"><stop class="ze5ugdbxr"/><stop offset="1" class="pr8brkb_h"/></radialGradient><radialGradient id="iOgytic" cx="0" cy="0" r="1" gradientTransform="matrix(5.0625 -2.5 8.03057 16.26191 2.563 22.25)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="aeh-ojcyt"/><stop offset="1" class="eg11r1-xe"/></radialGradient><radialGradient id="i8dB7mY" cx="0" cy="0" r="1" gradientTransform="rotate(19.44 -33.045 68.006)scale(5.63367 5.31661)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="g1bdywbbk"/><stop offset="1" class="woz3hacrx"/></radialGradient><radialGradient id="iIAmwnc" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 -1.5 3.12608 5.73115 20.875 10.625)" gradientUnits="userSpaceOnUse"><stop class="g1bdywbbk"/><stop offset="1" class="woz3hacrx"/></radialGradient><radialGradient id="i5Tleib" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 1.625 -3.01778 6.26772 20.813 17.25)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="g1bdywbbk"/><stop offset="1" class="woz3hacrx"/></radialGradient><radialGradient id="iOFv1Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 1 -2.31305 -1.3011 9.088 6.546)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="iunZmrd" cx="0" cy="0" r="1" gradientTransform="rotate(123.118 3.058 5.774)scale(.58626 1.5796)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="qso4uy3-n"/><stop offset="1" class="b_rfybbbi"/></radialGradient><radialGradient id="iiCAqce" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1 -2.31306 1.3011 23.118 6.546)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="iMnJMKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.2431 1.58204 -3.03843 2.38745 24.061 5.233)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="j26seachc"/><stop offset=".74" class="rsdjdrd8e"/></radialGradient><radialGradient id="ijMXlRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.64397 -.80986 .45783 .92938 23.255 5.44)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="vj5muxz_t"/><stop offset="1" class="tdhijwbfm"/></radialGradient><radialGradient id="iTmP2Oc" cx="0" cy="0" r="1" gradientTransform="matrix(8.00195 -4.49003 1.23522 2.20137 9.26 6.14)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="sjcrub2lh"/><stop offset="1" class="wgkuwteff"/></radialGradient><radialGradient id="ijwBDuc" cx="0" cy="0" r="1" gradientTransform="matrix(1.25052 1.35191 -6.0911 5.63427 8.103 3.103)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="wfxtb3qbv"/><stop offset="1" class="eax729dsn"/></radialGradient><radialGradient id="i8OfS4c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.568 1.57046 -2.49003 -4.07165 24.484 4.663)" gradientUnits="userSpaceOnUse"><stop class="v99wjxblu"/><stop offset=".469" class="fve8fmbgh"/></radialGradient><radialGradient id="iTPpSQd" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.135 2.124)" gradientUnits="userSpaceOnUse"><stop class="pa_nigs1j"/><stop offset="1" class="igdnfmbpz"/></radialGradient><radialGradient id="iqZdUGc" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.182 16.744)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop class="y1z543b6m"/><stop offset="1" class="qetg81_po"/></radialGradient><radialGradient id="ihUKuxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2142 -2.07063 5.3651 -.555 12.79 4.195)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="snh9c8fxs"/><stop offset="1" class="y-9i83_gz"/></radialGradient><radialGradient id="iHxwskb" cx="0" cy="0" r="1" gradientTransform="matrix(2.11795 2.22809 -3.41166 3.24302 12.528 1.681)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="s9v__5azz"/><stop offset="1" class="bcjkesbyj"/></radialGradient><radialGradient id="iVKkzHc" cx="0" cy="0" r="1" gradientTransform="rotate(96.911 7.838 9.68)scale(.2597 1.09361)" gradientUnits="userSpaceOnUse"><stop class="bbijeebsz"/><stop offset="1" class="aypdg85ht"/></radialGradient><radialGradient id="iwusE6d" cx="0" cy="0" r="1" gradientTransform="matrix(.14465 -1.10153 3.9101 .51345 19.627 3.529)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="gabhccily"/><stop offset="1" class="jia0zn94s"/></radialGradient><radialGradient id="i7zGTRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.91565 5.00841 0 13.978 4.431)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="snh9c8fxs"/><stop offset=".951" class="y-9i83_gz"/></radialGradient><radialGradient id="i00ry6d" cx="0" cy="0" r="1" gradientTransform="matrix(1.57086 2.47251 -3.5045 2.22651 13.977 2.449)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="s9v__5azz"/><stop offset="1" class="bcjkesbyj"/></radialGradient><radialGradient id="iKoqpAe" cx="0" cy="0" r="1" gradientTransform="matrix(.03363 .53517 -1.63373 .10266 17.797 4.148)" gradientUnits="userSpaceOnUse"><stop class="bbijeebsz"/><stop offset="1" class="aypdg85ht"/></radialGradient><radialGradient id="iwT5Fsb" cx="0" cy="0" r="1" gradientTransform="matrix(.05835 -1.56885 4.81421 .17906 18.523 4.363)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gabhccily"/><stop offset="1" class="jia0zn94s"/></radialGradient><radialGradient id="iiJHjob" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 -.90625 8.05091 -1.87395 13.994 4.718)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iJMSYzw" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36455 4.31533 0 13.832 5.052)" gradientUnits="userSpaceOnUse"><stop offset=".729" class="snh9c8fxs"/><stop offset="1" class="y-9i83_gz"/></radialGradient><radialGradient id="iqtdSxd" cx="0" cy="0" r="1" gradientTransform="rotate(52.458 3.222 15.857)scale(2.22121 3.36062)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="s9v__5azz"/><stop offset="1" class="bcjkesbyj"/></radialGradient><radialGradient id="iArX0Vc" cx="0" cy="0" r="1" gradientTransform="matrix(-.008 .32792 -1.41492 -.03451 17.99 4.888)" gradientUnits="userSpaceOnUse"><stop class="bbijeebsz"/><stop offset="1" class="aypdg85ht"/></radialGradient><radialGradient id="i8hTXfb" cx="0" cy="0" r="1" gradientTransform="rotate(-87.754 11.742 -7.16)scale(1.13578 5.8741)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gabhccily"/><stop offset="1" class="jia0zn94s"/></radialGradient><radialGradient id="itAc4fe" cx="0" cy="0" r="1" gradientTransform="matrix(-.06965 -1.61842 4.37527 -.1883 13.48 6.337)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="snh9c8fxs"/><stop offset="1" class="y-9i83_gz"/></radialGradient><radialGradient id="izutHLi" cx="0" cy="0" r="1" gradientTransform="rotate(108.623 9.59 9.315)scale(4.23839 15.1226)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nnha85vdf"/><stop offset="1" class="ttw1-g7zn"/></radialGradient><radialGradient id="iqPWwyV" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.50682 -3.31996 -1.79016 22.844 3.156)" gradientUnits="userSpaceOnUse"><stop class="h6orixb7r"/><stop offset="1" class="s3qs9xb1s"/></radialGradient><radialGradient id="i2Y1Iic" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9.114 -1.21)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="c2b4j9bss"/><stop offset="1" class="rjn5j4bgi"/></radialGradient><radialGradient id="i4eEaUa" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.589 6.825)" gradientUnits="userSpaceOnUse"><stop class="f_gowxnlh"/><stop offset="1" class="bx7a6gbyw"/></radialGradient><linearGradient id="iWrJLbc" x1="10.649" x2="12.407" y1="17.518" y2="17.822" gradientUnits="userSpaceOnUse"><stop class="beto58x7m"/><stop offset="1" class="zaudeyb6s"/></linearGradient><linearGradient id="iHiuzzd" x1="21.588" x2="21.129" y1="16.819" y2="16.794" gradientUnits="userSpaceOnUse"><stop class="l-kfx0bvm"/><stop offset="1" class="f7ed1l_pp"/></linearGradient><linearGradient id="iRQwQtd" x1="10.461" x2="11.091" y1="16.794" y2="16.794" gradientUnits="userSpaceOnUse"><stop class="y9-mgy3gl"/><stop offset="1" class="q68dcacvn"/></linearGradient><linearGradient id="ik8RsHe" x1="16.637" x2="15.973" y1="16.579" y2="16.579" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iF11bWd" x1="16.125" x2="16.125" y1="18.047" y2="17.43" gradientUnits="userSpaceOnUse"><stop offset=".101" class="aqgn8ntqj"/><stop offset="1" class="lra14bugm"/></linearGradient><linearGradient id="igbcIcd" x1="16.635" x2="16.635" y1="5.84" y2="14.077" gradientUnits="userSpaceOnUse"><stop class="rxy3d1mqt"/><stop offset=".622" class="ovy025hqy"/></linearGradient><linearGradient id="ifA08sb" x1="19.196" x2="18.854" y1="15.215" y2="15.425" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBeM4Pe" x1="14.407" x2="14.066" y1="15.215" y2="15.425" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZE6qYb" x1="14.101" x2="11.524" y1="12.595" y2="12.595" gradientUnits="userSpaceOnUse"><stop offset=".333" class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="iyOjS2d" x1="17.844" x2="20.422" y1="12.595" y2="12.595" gradientUnits="userSpaceOnUse"><stop offset=".333" class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="iRoo0ad" x1="15" x2="15.488" y1="19.769" y2="18.887" gradientUnits="userSpaceOnUse"><stop class="u2tqccrku"/><stop offset=".537" class="neizwibai"/></linearGradient><linearGradient id="iMALT6d" x1="24.552" x2="10.086" y1="13.017" y2="32.866" gradientUnits="userSpaceOnUse"><stop class="eod5jnblz"/><stop offset="1" class="afa9xwbaj"/></linearGradient><linearGradient id="iYtwOec" x1="11.291" x2="7.322" y1="23.796" y2="27.921" gradientUnits="userSpaceOnUse"><stop class="j2t7368de"/><stop offset=".582" class="x05lq4b2v"/></linearGradient><linearGradient id="izBpvyb" x1="18.242" x2="20.93" y1="2.774" y2="3.541" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="iXn8XNi" x1="16.431" x2="18.671" y1="2.931" y2="3.622" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset="1" class="h2thr5bul"/></linearGradient><linearGradient id="iw8pEuW" x1="17.208" x2="20.026" y1="3.398" y2="3.738" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="ix9gD3d" x1="15.411" x2="17.773" y1="3.901" y2="4.223" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset="1" class="h2thr5bul"/></linearGradient><linearGradient id="iOdjE2c" x1="17.446" x2="19.383" y1="4.367" y2="4.762" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="i0ILzFb" x1="16.031" x2="18.196" y1="5.408" y2="5.357" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset="1" class="h2thr5bul"/></linearGradient><linearGradient id="isbCP7c" x1="17.918" x2="19.805" y1="5.268" y2="5.465" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="icdiSne" x1="16.575" x2="18.473" y1="6.16" y2="5.994" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset=".84" class="h2thr5bul"/></linearGradient><linearGradient id="i7LgK4A" x1="14.675" x2="11.623" y1="5.534" y2="6.255" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="iv2Xryd" x1="15.03" x2="11.516" y1="4.438" y2="5.413" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="iub8gAb" x1="15.164" x2="11.65" y1="3.452" y2="4.427" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="ivFL98b" x1="14.162" x2="10.788" y1="2.646" y2="4.045" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><filter id="iSeI3fd" width="11.877" height="13.637" x="10.461" y="9.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.223529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3716"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0745098 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3716" result="effect2_innerShadow_4002_3716"/></filter><filter id="iBu43db" width="4.044" height="5.157" x="13.726" y="14.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".5"/></filter><filter id="iZJP0oc" width="2.244" height="3.357" x="14.851" y="14.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".05"/></filter><filter id="io3jmzc" width="14.015" height="9.054" x="8.965" y="5.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0196078 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3716"/></filter><filter id="i5B8CKc" width="7.25" height="6.272" x="9.325" y="6.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341667 0 0 0 0 0.324583 0 0 0 0 0.324583 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3716"/><feGaussianBlur result="effect2_foregroundBlur_4002_3716" stdDeviation=".15"/></filter><filter id="iTbQdQe" width="6.919" height="6.381" x="15.808" y="7.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3716"/><feGaussianBlur result="effect2_foregroundBlur_4002_3716" stdDeviation=".15"/></filter><filter id="iZeA55b" width=".839" height=".74" x="17.558" y="14.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".05"/></filter><filter id="i0So2NJ" width=".935" height=".959" x="18.482" y="14.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".1"/></filter><filter id="iyp0drv" width="1.038" height="1.097" x="13.645" y="14.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".1"/></filter><filter id="idHITLe" width=".976" height=".749" x="12.814" y="14.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".05"/></filter><filter id="i6hqbZp" width="1.402" height="2.546" x="9.427" y="14.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".125"/></filter><filter id="ibpZX0c" width="1.531" height="2.572" x="21.147" y="14.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".125"/></filter><filter id="iNM6o6g" width="2.544" height="1.086" x="11.868" y="12.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3716"/></filter><filter id="iZCISid" width="2.594" height="1.136" x="11.793" y="12.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".125"/></filter><filter id="izeekue" width="2.544" height="1.086" x="17.634" y="12.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3716"/></filter><filter id="iX9R87d" width="2.594" height="1.136" x="17.559" y="12.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".125"/></filter><filter id="iyOX5dc" width="16.188" height="8.656" x="9.197" y="22.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".5"/></filter><filter id="itNMMfc" width="4.094" height="4.656" x="7.947" y="23.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".25"/></filter><filter id="ir7dSGc" width="3.508" height="1.177" x="11.5" y="5.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".125"/></filter><filter id="iKe3PrF" width="4.104" height="1.115" x="11.366" y="3.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".125"/></filter><filter id="isNSM3b" width="4.104" height="1.115" x="11.5" y="3.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".125"/></filter><filter id="iBRYNbc" width="4.288" height="1.471" x="10.486" y="2.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3716" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-ok-dark" /></template>
<style>
.a_b1i5frv {
  stop-color: var(--svg-color--574646, #574646);
  stop-opacity: 0;
}

.a-2r3fbgq {
  stop-color: var(--svg-color--9d4635, #9D4635);
  stop-opacity: 0;
}

.a9v7zjbuf {
  d: path("M18.28 14.842c.069.093-.076.205-.24.329c-.165.123-.287.21-.356.117c-.07-.093.008-.268.172-.39c.165-.124.354-.149.423-.056");
}

.ae7hq_o7r {
  stop-color: var(--svg-color--281215, #281215);
}

.aeh-ojcyt {
  stop-color: var(--svg-color--c7482a, #C7482A);
}

.afa9xwbaj {
  stop-color: var(--svg-color--db4f17, #DB4F17);
}

.aqgn8ntqj {
  stop-color: var(--svg-color--3e1f2a, #3E1F2A);
}

.aqwz8eb5i {
  stop-color: var(--svg-color--494748, #494748);
  stop-opacity: 0;
}

.au361rb0r {
  stop-color: var(--svg-color--5f443e, #5F443E);
}

.auv2jxbee {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.37 14.34a1.52 1.52 0 0 0-1.475 1.153a.3.3 0 0 0 .291.371h2.43a.25.25 0 0 0 .247-.296a1.525 1.525 0 0 0-1.493-1.227");
}

.aypdg85ht {
  stop-color: var(--svg-color--261111, #261111);
  stop-opacity: 0;
}

.b_rfybbbi {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
  stop-opacity: 0;
}

.ba38z0-_a {
  stop-color: var(--svg-color--3d201d, #3D201D);
}

.bbijeebsz {
  stop-color: var(--svg-color--261111, #261111);
}

.bcjkesbyj {
  stop-color: var(--svg-color--2d1717, #2D1717);
}

.beto58x7m {
  stop-color: var(--svg-color--431c17, #431C17);
}

.bf57i6byh {
  stop-color: var(--svg-color--ffd843, #FFD843);
  stop-opacity: 0;
}

.bo9ofmw9k {
  stop-color: var(--svg-color--251421, #251421);
}

.bps78hksv {
  stop-color: var(--svg-color--942d01, #942D01);
}

.bqw3z_b7a {
  d: path("M18.35 14.637a.972.972 0 0 1 .937 1.227H17.41a.975.975 0 0 1 .94-1.228");
}

.bx7a6gbyw {
  stop-color: var(--svg-color--533d3d, #533D3D);
  stop-opacity: 0;
}

.by6guy4wy {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
  stop-opacity: 0;
}

.c2b4j9bss {
  stop-color: var(--svg-color--30171b, #30171B);
}

.c5ffxnbso {
  stop-color: var(--svg-color--ffdd45, #FFDD45);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cyxut_buu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.28 14.842c.069.093-.076.205-.24.329c-.165.123-.287.21-.356.117c-.07-.093.008-.268.172-.39c.165-.124.354-.149.423-.056");
}

.d1wh27gbc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.697 26.952c.48-.448 1.669-1.706 2.594-3.156");
}

.dccrmw9im {
  stop-color: var(--svg-color--574646, #574646);
}

.dngnupbnt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.875 5.835c.391-.173 1.476-.503 2.758-.41");
}

.dq9t1f2dd {
  stop-color: var(--svg-color--584041, #584041);
}

.dwxodwo3m {
  stop-color: var(--svg-color--343434, #343434);
}

.e0_s-ccjj {
  fill: var(--svg-color--341824, #341824);
  d: path("m15.444 15.435l-.692 2.002c-.118.411.166.823.567.823h.856c.402 0 .685-.418.567-.823l-.578-2.002c-.124-.443-.59-.443-.72 0");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eax729dsn {
  stop-color: var(--svg-color--4e4240, #4E4240);
  stop-opacity: 0;
}

.eg11r1-xe {
  stop-color: var(--svg-color--c7482a, #C7482A);
  stop-opacity: 0;
}

.elwg_hb8v {
  stop-color: var(--svg-color--383636, #383636);
}

.eod5jnblz {
  stop-color: var(--svg-color--ff5918, #FF5918);
}

.ew05122nr {
  stop-color: var(--svg-color--3f383b, #3F383B);
  stop-opacity: 0;
}

.ew56wjbup {
  stop-color: var(--svg-color--ff7532, #FF7532);
}

.ezh02gbvd {
  stop-color: var(--svg-color--323030, #323030);
}

.f_gowxnlh {
  stop-color: var(--svg-color--533d3d, #533D3D);
}

.f-iegb-dq {
  stop-color: var(--svg-color--ff5930, #FF5930);
}

.f6dcakbta {
  stroke: var(--svg-color--4c3332, #4C3332);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.106 3.46c.68-.344 2.47-.57 3.188-.523");
}

.f7ed1l_pp {
  stop-color: var(--svg-color--594c4b, #594C4B);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fh1_5ac_k {
  stop-color: var(--svg-color--942d01, #942D01);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fve8fmbgh {
  stop-color: var(--svg-color--4f3733, #4F3733);
}

.fwajr3bwa {
  stop-color: var(--svg-color--503833, #503833);
  stop-opacity: 0;
}

.g1bdywbbk {
  stop-color: var(--svg-color--ad4002, #AD4002);
}

.g2nuuigok {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.522 4.577c-.43-.11-1.28-.203-2.296-.078");
}

.g2pfm6b2q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.106 3.46c.68-.344 2.47-.57 3.188-.523");
}

.gabhccily {
  stop-color: var(--svg-color--544442, #544442);
  stop-opacity: 0;
}

.gavknk-rw {
  stop-color: var(--svg-color--25171d, #25171D);
}

.gb_6b_bzf {
  stop-color: var(--svg-color--342127, #342127);
}

.glnh1qovj {
  stop-color: var(--svg-color--321715, #321715);
}

.gu6tecb8a {
  fill: var(--svg-color--000, #000);
  d: path("M17.794 15.608c0-.309.248-.556.557-.556a.554.554 0 0 1 .495.812h-.985a.5.5 0 0 1-.067-.256");
}

.gw18cjbfi {
  d: path("M19.216 15.48a.9.9 0 0 0-.252-.503l-.282.31l.127.248z");
}

.h2thr5bul {
  stop-color: var(--svg-color--281414, #281414);
  stop-opacity: 0;
}

.h6orixb7r {
  stop-color: var(--svg-color--5a4745, #5A4745);
}

.h9fb5bbiv {
  stop-color: var(--svg-color--ffa143, #FFA143);
}

.hafi0jbga {
  fill: var(--svg-color--462e2c, #462E2C);
  d: path("m15.557 15.222l-.579 2.001c-.118.412.165.824.567.824h.856c.402 0 .685-.418.567-.824l-.579-2.001c-.124-.444-.702-.444-.832 0");
}

.hbiy7rsgs {
  d: path("M10.489 14.696a1.04 1.04 0 0 0 .09 2.046a84 84 0 0 1-.09-2.046");
}

.hiycpfc4f {
  stop-color: var(--svg-color--ff711c, #FF711C);
}

.ho3l0pbty {
  d: path("M10.48 13.988a1.75 1.75 0 0 0-1.515 1.723c0 .935.733 1.7 1.656 1.75a84 84 0 0 1-.14-3.473");
}

.igdnfmbpz {
  stop-color: var(--svg-color--5a4947, #5A4947);
  stop-opacity: 0;
}

.imyribcnz {
  fill: var(--svg-color--0b090a, #0B090A);
  fill-rule: evenodd;
  d: path("M13.994 12.899c-.79-.127-1.468.194-1.69.354a.275.275 0 1 1-.323-.444c.31-.226 1.134-.608 2.1-.453a.275.275 0 0 1-.087.543");
}

.ipqv18bkn {
  d: path("M10.72 19.01a4.26 4.26 0 0 0 4.23 3.708h2.055a4.26 4.26 0 0 0 4.23-3.708c.128-2.05.258-4.093.353-6.143a1.58 1.58 0 0 0-1.501-1.56h-1.525c-1.04 0-1.98-.612-2.408-1.57a.72.72 0 0 0-.67-.455h-1.386c-2.009 0-3.637 1.646-3.637 3.678c0 2.026.126 4.02.259 6.05");
}

.j0tyu7ber {
  fill: var(--svg-color--20171a, #20171A);
  d: path("m21.648 13.26l-.032-.687c-.011-.831-.698-1.517-1.53-1.552h-1.524c-1.498 0-2.207-1.316-2.44-2.628c-.1-.56.381-1.008.939-.898c1.189.236 2.82.758 3.964 1.504c1.9 1.239 1.623 3.21.623 4.261");
}

.j1090kf1c {
  stop-color: var(--svg-color--ff6428, #FF6428);
  stop-opacity: 0;
}

.j26seachc {
  stop-color: var(--svg-color--ff8547, #FF8547);
}

.j2t7368de {
  stop-color: var(--svg-color--ef6736, #EF6736);
}

.j85ao0bcf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.576 14.34c.711 0 1.312.491 1.475 1.153a.298.298 0 0 1-.291.371h-2.43a.25.25 0 0 1-.247-.296a1.52 1.52 0 0 1 1.493-1.227");
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jbemdffol {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.882 5.655c-.274-.101-1.102-.304-2.172-.242");
}

.jia0zn94s {
  stop-color: var(--svg-color--544442, #544442);
}

.k35cj8b6j {
  stop-color: var(--svg-color--685755, #685755);
}

.kbxalxbaa {
  fill: var(--svg-color--211419, #211419);
  d: path("M16.252 9.58a3 3 0 0 1-.072-.15a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.823 1.646-3.823 3.679v.3c-.37-.283-.676-.57-.676-1.532c0-1.608 2.705-3.588 4.105-3.96a6 6 0 0 1 1.723-.177c.468.017.8.42.805.888l.016 1.391z");
}

.kg5wfpbcx {
  stop-color: var(--svg-color--413735, #413735);
}

.khto69bzj {
  stop-color: var(--svg-color--130402, #130402);
}

.kktc6hgtz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.325 5.655c.273-.101 1.101-.304 2.171-.242");
}

.l-kfx0bvm {
  stop-color: var(--svg-color--594c4b, #594C4B);
}

.l-xm7ybzq {
  stop-color: var(--svg-color--2a1418, #2A1418);
}

.lfjjhubys {
  stop-color: var(--svg-color--413735, #413735);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lq2g98b5s {
  stop-color: var(--svg-color--281414, #281414);
}

.lra14bugm {
  stop-color: var(--svg-color--3e1f2a, #3E1F2A);
  stop-opacity: 0;
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m_2922ixt {
  stop-color: var(--svg-color--9d4635, #9D4635);
}

.m16jdvb1f {
  stop-color: var(--svg-color--685755, #685755);
  stop-opacity: 0;
}

.mf8lxmbde {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.86 3.354c.434-.235 2.032-.622 3.539-.721");
}

.mn62upa0i {
  fill: var(--svg-color--290017, #290017);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.476 18.606c.44.23.965.361 1.524.361c.565 0 1.084-.131 1.524-.36v-.001a.22.22 0 0 1 .263.043a.205.205 0 0 1 .023.263m-3.334-.306l3.292.278m-3.292-.278a.22.22 0 0 0-.263.045a.2.2 0 0 0-.023.26m.286-.305l-.244.278m3.578.028l-.042-.028m.042.028l-.042-.028m.042.028c-.383.58-1.05.967-1.81.967s-1.427-.387-1.81-.967m3.578-.028a2.11 2.11 0 0 1-1.768.945a2.11 2.11 0 0 1-1.768-.945m-.042.028l.042-.028m-.042.028l.042-.028");
}

.mnttfobfp {
  d: path("M14.483 15.494c0-.314-.255-.523-.324-.586l-.314.303l.193.393z");
}

.mqq2pckgy {
  stop-color: var(--svg-color--ff711c, #FF711C);
  stop-opacity: 0;
}

.mwx1nwbkc {
  stroke: var(--svg-color--4c3332, #4C3332);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.684 4.577c.43-.11 1.281-.203 2.297-.078");
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.neizwibai {
  stop-color: var(--svg-color--564747, #564747);
  stop-opacity: 0;
}

.nmo6e1i6c {
  d: path("m21.648 13.26l-.032-.687c-.011-.831-.698-1.517-1.53-1.552h-1.524c-1.498 0-2.207-1.316-2.44-2.628c-.1-.56.381-1.008.939-.898c1.189.236 2.82.758 3.964 1.504c1.9 1.239 1.623 3.21.623 4.261");
}

.nnha85vdf {
  stop-color: var(--svg-color--251014, #251014);
  stop-opacity: 0;
}

.nnw551blu {
  d: path("m7.422 4.91l-.428.665a.24.24 0 0 0 .01.279c.898 1.155 2.373 1.8 3.283 2.087a.244.244 0 0 0 .28-.108c.151-.247.354-.584.41-.69c.068-.13-.03-.231-.087-.265L7.875 5.05L8 4.776c-.35-.106-.531.045-.578.133");
}

.ns3cxsbdp {
  stop-color: var(--svg-color--343434, #343434);
  stop-opacity: 0;
}

.o89p0ub4o {
  width: 4.615px;
  height: 6.587px;
  x: 13.693px;
  y: 18.26px;
  rx: 2.307px;
}

.o8eh185ql {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.684 4.577c.43-.11 1.281-.203 2.297-.078");
}

.objo5mqkg {
  d: path("M23.963 27.421c-1.95-1.2-3.037-3.417-3.36-4.156c-5.175 0-9.28 1.969-10.406 6.656h14.188c0-.9-.157-1.937-.422-2.5");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oju6c_bmm {
  stop-color: var(--svg-color--4d4749, #4D4749);
}

.okxecjbze {
  stop-color: var(--svg-color--433a37, #433A37);
}

.ouq4o0bxk {
  d: path("M7.337 5.64c-.203-.058-.677-.155-.946-.086c-.335.086-.593.328-.812.687a958 958 0 0 0-2.094 3.54c-.562.822-1.625 3.087-1.375 5.562c.1 1.662.781 3.339 1.11 3.969l4.132 7.854c.173.33.187.719.08 1.076c-.158.529-.322 1.28-.322 2.023h17.828c0-.743-.164-1.494-.322-2.023a1.43 1.43 0 0 1 .08-1.076l4.133-7.854c.328-.63 1.01-2.307 1.11-3.97c.25-2.474-.813-4.739-1.376-5.562a915 915 0 0 0-2.093-3.539c-.22-.359-.477-.601-.813-.687c-.269-.069-.742.028-.945.086l-3.188 2.164c-.351.414-.19.966-.054 1.18l2.075 3.511a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a14 14 0 0 0-1.12-.483a4.3 4.3 0 0 1-.775.336v.023a2.307 2.307 0 0 1-4.614 0v-.009a4.3 4.3 0 0 1-.782-.329c-.395.155-.762.312-1.064.462a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382l2.075-3.511c.135-.214.297-.766-.055-1.18z");
}

.ovy025hqy {
  stop-color: var(--svg-color--2e2a30, #2E2A30);
}

.p0abytb-y {
  d: path("M16.252 9.58a3 3 0 0 1-.072-.15a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.823 1.646-3.823 3.679v.3c-.37-.283-.676-.57-.676-1.532c0-1.608 2.705-3.588 4.105-3.96a6 6 0 0 1 1.723-.177c.468.017.8.42.805.888l.016 1.391z");
}

.p5o93zbvk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.1 3.46c-.68-.344-2.47-.57-3.188-.523");
}

.p6gd-c5_t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.741 4.74c.46-.173 1.847-.439 3.353-.347");
}

.p6n3jab6e {
  d: path("M22.667 3.359a61 61 0 0 1 1.79 1.61a.08.08 0 0 1 .027.054c.032.574-1.969 1.625-3.04 2.013a.1.1 0 0 1-.033.006c-.941-.004-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309s-.602-.218-.696-.414c-.063-.132-.064-.316.03-.523a.63.63 0 0 1-.442-.281a.64.64 0 0 1-.056-.625c-.157-.063-.337-.304-.313-.649c.038-.537.563-.661.781-.656h.165c-.013-.55.585-.6.814-.574l1.717.097a.98.98 0 0 1 .765-.132c.433.122 1.264.338 2.094 1.047");
}

.pa_nigs1j {
  stop-color: var(--svg-color--5a4947, #5A4947);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr8brkb_h {
  stop-color: var(--svg-color--ff7840, #FF7840);
  stop-opacity: 0;
}

.px0bqddnx {
  stop-color: var(--svg-color--2d191c, #2D191C);
}

.q5kz07b1g {
  d: path("m24.785 4.91l.427.665a.24.24 0 0 1-.01.279c-.898 1.155-2.373 1.8-3.283 2.087a.244.244 0 0 1-.28-.108a22 22 0 0 1-.41-.69c-.068-.13.03-.231.087-.265L24.33 5.05l-.125-.274c.35-.106.532.045.579.133");
}

.q68dcacvn {
  stop-color: var(--svg-color--50403e, #50403E);
  stop-opacity: 0;
}

.qd38sjb7e {
  stop-color: var(--svg-color--ff7532, #FF7532);
  stop-opacity: 0;
}

.qdqqfixaa {
  stop-color: var(--svg-color--543e3e, #543E3E);
}

.qetg81_po {
  stop-color: var(--svg-color--ff8543, #FF8543);
  stop-opacity: 0;
}

.qg9x9catg {
  stop-color: var(--svg-color--503833, #503833);
}

.qhgr5vbwq {
  stop-color: var(--svg-color--412527, #412527);
}

.qso4uy3-n {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
}

.qy05b9bsw {
  stop-color: var(--svg-color--494748, #494748);
}

.rjn5j4bgi {
  stop-color: var(--svg-color--30171b, #30171B);
  stop-opacity: 0;
}

.rljmqdbdm {
  d: path("M9.54 3.359a61 61 0 0 0-1.79 1.61a.08.08 0 0 0-.027.054c-.033.574 1.968 1.625 3.038 2.013q.017.006.034.006c.941-.004 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.218.696-.414c.063-.132.064-.316-.03-.523a.63.63 0 0 0 .442-.281a.64.64 0 0 0 .056-.625c.157-.063.337-.304.313-.649c-.037-.537-.494-.37-.713-.366l-.232-.29c.012-.55-.586-.6-.815-.574l-1.717.097a.98.98 0 0 0-.765-.132c-.432.122-1.263.338-2.094 1.047");
}

.rotm0lbjl {
  stop-color: var(--svg-color--3a3233, #3A3233);
}

.rsdjdrd8e {
  stop-color: var(--svg-color--ff8547, #FF8547);
  stop-opacity: 0;
}

.rv6kkhbrx {
  d: path("M21.397 16.759q.064-1.037.12-2.072a1.04 1.04 0 0 1-.12 2.072");
}

.rxy3d1mqt {
  stop-color: var(--svg-color--383435, #383435);
}

.s-bvk7j1g {
  cx: 13.302px;
  cy: 15.052px;
  rx: 0.424px;
  ry: 0.215px;
}

.s3qs9xb1s {
  stop-color: var(--svg-color--5a4745, #5A4745);
  stop-opacity: 0;
}

.s9v__5azz {
  stop-color: var(--svg-color--2d1717, #2D1717);
  stop-opacity: 0;
}

.sdpofnlol {
  d: path("M9.54 3.359a61 61 0 0 0-1.79 1.61a.08.08 0 0 0-.027.054c-.033.574 1.968 1.625 3.038 2.013q.017.006.034.006c.941-.004 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.218.696-.414c.063-.132.064-.316-.03-.523a.63.63 0 0 0 .442-.281a.64.64 0 0 0 .056-.625c.157-.063.337-.304.313-.649c-.037-.537-.562-.661-.781-.656h-.164c.012-.55-.586-.6-.815-.574l-1.717.097a.98.98 0 0 0-.765-.132c-.432.122-1.263.338-2.094 1.047");
}

.sfdgrznqv {
  stop-color: var(--svg-color--36141a, #36141A);
}

.sfldthbut {
  fill: var(--svg-color--0b090a, #0B090A);
  fill-rule: evenodd;
  d: path("M17.952 12.899c.79-.127 1.468.194 1.689.354a.275.275 0 1 0 .324-.444c-.31-.226-1.134-.608-2.1-.453a.275.275 0 0 0 .087.543");
}

.sjcrub2lh {
  stop-color: var(--svg-color--4c3232, #4C3232);
}

.smk8hf09v {
  d: path("M21.266 17.36c.365-.011.706-.135.985-.335v1.014c0 .972-.58 1.838-1.46 2.198q.279-.594.376-1.285z");
}

.snh9c8fxs {
  stop-color: var(--svg-color--2d1716, #2D1716);
  stop-opacity: 0;
}

.st7zu_bkr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.15 3.901c-.43-.11-2.375-.476-3.254-.265");
}

.sulmr2p6z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.645 3.765c.43-.11 1.65-.274 2.665-.149");
}

.swsuc2b-u {
  d: path("m15.557 15.222l-.579 2.001c-.118.412.165.824.567.824h.856c.402 0 .685-.418.567-.824l-.579-2.001c-.124-.444-.702-.444-.832 0");
}

.sy43x-b1n {
  d: path("M13.595 14.637a.972.972 0 0 0-.936 1.227h1.877a1 1 0 0 0 .035-.256a.98.98 0 0 0-.976-.971");
}

.t39rzsbyn {
  stop-color: var(--svg-color--4d4749, #4D4749);
  stop-opacity: 0;
}

.t66rxj2ac {
  d: path("M21.332 17.46q.108-1.737.2-3.475a1.752 1.752 0 0 1-.2 3.475");
}

.t9_b9cb9w {
  stroke: var(--svg-color--4c3332, #4C3332);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.325 5.655c.273-.101 1.101-.304 2.171-.242");
}

.t9jirh49o {
  cx: 13.302px;
  cy: 15.052px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.424px;
  ry: 0.215px;
}

.tdhijwbfm {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
  stop-opacity: 0;
}

.tgg33wray {
  stroke: var(--svg-color--4c3332, #4C3332);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.645 3.765c.43-.11 1.65-.274 2.665-.149");
}

.tlhnu4bgl {
  d: path("M22.667 3.359a61 61 0 0 1 1.79 1.61a.08.08 0 0 1 .027.054c.032.574-1.969 1.625-3.04 2.013a.1.1 0 0 1-.033.006c-.941-.004-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309s-.602-.218-.696-.414c-.063-.132-.064-.316.03-.523a.63.63 0 0 1-.442-.281a.64.64 0 0 1-.056-.625c-.157-.063-.337-.304-.313-.649c.038-.537.592-.465.81-.46l.136-.196c-.013-.55.585-.6.814-.574l1.717.097a.98.98 0 0 1 .765-.132c.433.122 1.264.338 2.094 1.047");
}

.tpx6wbcio {
  stop-color: var(--svg-color--251421, #251421);
  stop-opacity: 0;
}

.ttw1-g7zn {
  stop-color: var(--svg-color--251014, #251014);
}

.u_pi4nbrf {
  stop-color: var(--svg-color--462f2d, #462F2D);
}

.u2tqccrku {
  stop-color: var(--svg-color--564747, #564747);
}

.ugplhqxsv {
  stop-color: var(--svg-color--4a1e1f, #4A1E1F);
}

.v1cdxsyyg {
  stop-color: var(--svg-color--502a26, #502A26);
}

.v99wjxblu {
  stop-color: var(--svg-color--63504e, #63504E);
}

.vfgu2wb9r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.143 13.03c.266-.192 1.016-.543 1.894-.403");
}

.vj5muxz_t {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
}

.vnfc80b-n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.803 13.03c-.266-.192-1.017-.543-1.894-.403");
}

.vzcz7obpn {
  stop-color: var(--svg-color--412527, #412527);
  stop-opacity: 0;
}

.w808r0nmy {
  stop-color: var(--svg-color--42222d, #42222D);
  stop-opacity: 0;
}

.wfxtb3qbv {
  stop-color: var(--svg-color--4e4240, #4E4240);
}

.wgkuwteff {
  stop-color: var(--svg-color--4b3330, #4B3330);
}

.wgttxsdys {
  stop-color: var(--svg-color--3a3233, #3A3233);
  stop-opacity: 0;
}

.woz3hacrx {
  stop-color: var(--svg-color--ad4002, #AD4002);
  stop-opacity: 0;
}

.wx87iwb8j {
  stop-color: var(--svg-color--3f383b, #3F383B);
}

.x-kyklb-a {
  stop-color: var(--svg-color--383636, #383636);
  stop-opacity: 0;
}

.x05lq4b2v {
  stop-color: var(--svg-color--ef6736, #EF6736);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xlxfzcbzl {
  stop-color: var(--svg-color--392c2d, #392C2D);
}

.xzfyhsbwz {
  d: path("M21.259 8.768c.56.192 1.062.584 1.38 1.144a2.58 2.58 0 0 1-.116 2.75c-.19.281-.294.614-.294.952v1.294a1.9 1.9 0 0 0-.727-.292l.086-1.749a1.58 1.58 0 0 0-1.502-1.56h-1.524c-1.04 0-1.98-.612-2.408-1.57a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.638 1.646-3.638 3.678l.034 1.674c-.277.04-.566.133-.784.287v-1.306c0-.34-.104-.672-.295-.952A2.6 2.6 0 0 1 9.26 10a2.55 2.55 0 0 1 1.415-1.227c.624-.221 1.026-.607 1.378-1.173c.45-.719 1.37-1.232 2.277-1.232c.352 0 .687.045.999.173c.415.181.883.181 1.299 0c.306-.128.641-.173.994-.173c.918 0 1.72.496 2.165 1.232c.335.554.86.957 1.473 1.168");
}

.y-9i83_gz {
  stop-color: var(--svg-color--2d1716, #2D1716);
}

.y1z543b6m {
  stop-color: var(--svg-color--ff8543, #FF8543);
}

.y5yvssumf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.875 3.754c.46-.173 1.847-.439 3.353-.346");
}

.y9-mgy3gl {
  stop-color: var(--svg-color--50403e, #50403E);
}

.ym0brebyc {
  stop-color: var(--svg-color--ff6a31, #FF6A31);
}

.yvt-nqbiu {
  stop-color: var(--svg-color--543e3e, #543E3E);
  stop-opacity: 0;
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z3h-89ams {
  fill: var(--svg-color--000, #000);
  d: path("M14.152 15.608a.554.554 0 0 0-.557-.556a.554.554 0 0 0-.495.813h.986a.55.55 0 0 0 .066-.257");
}

.z68hxd5ya {
  d: path("M10.68 17.36a1.8 1.8 0 0 1-.985-.335v1.014c0 .972.58 1.838 1.46 2.198a4.5 4.5 0 0 1-.376-1.285z");
}

.zaudeyb6s {
  stop-color: var(--svg-color--431c17, #431C17);
  stop-opacity: 0;
}

.ze5ugdbxr {
  stop-color: var(--svg-color--ff7840, #FF7840);
}

.zmkruk91v {
  stop-color: var(--svg-color--62504f, #62504F);
  stop-opacity: 0;
}

.zn3xi9bpn {
  stop-color: var(--svg-color--3f2422, #3F2422);
}

.zu__wcbib {
  stop-color: var(--svg-color--2c1214, #2C1214);
}

</style>
