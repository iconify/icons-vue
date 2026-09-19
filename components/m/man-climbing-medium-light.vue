<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i0f4ATc)" class="s6i7kxbsp"/><path fill="url(#ienbumd)" class="s6i7kxbsp"/><path fill="url(#i0v7cme)" class="nv_3ww30s"/><path fill="url(#ikBPldd)" class="nv_3ww30s"/><path fill="url(#iNeH5UJ)" class="nv_3ww30s"/><path fill="url(#iOMayze)" class="nv_3ww30s"/><path fill="url(#iZf3pte)" class="nv_3ww30s"/><g filter="url(#idMB6pf)"><path class="xctpj4u6q"/></g><path fill="url(#ipTu1mb)" class="foggvnbji"/><path fill="url(#ivyVoHc)" class="foggvnbji"/><path fill="url(#iIPgPFA)" class="foggvnbji"/><g filter="url(#iU6IGKb)"><path fill="url(#iCv86Yc)" class="atg-_ebrv"/></g><g filter="url(#ig3RZcc)"><path fill="url(#iagmCgS)" clip-rule="evenodd" class="xv468xbcl"/></g><path fill="url(#imj0iWb)" class="sscrhab_a"/><path fill="url(#iYslrsd)" class="sscrhab_a"/><path fill="url(#iUaPnIF)" class="sscrhab_a"/><g filter="url(#icO2hfc)"><path fill="url(#igf9Oyb)" class="qxe3b85cr"/></g><g filter="url(#i1q5gIL)"><path stroke="url(#irqXdRb)" class="kxbrb3y6a"/></g><g filter="url(#i5pQANe)"><path fill="url(#iMAjlee)" class="ytaxympda"/></g><path fill="url(#iyC7bob)" class="gzh61e4uu"/><path fill="url(#iSMW0ee)" class="enju3fb9g"/><path fill="url(#inExGvd)" class="enju3fb9g"/><path fill="url(#iUKZlCd)" class="enju3fb9g"/><path fill="url(#imv7p5d)" transform="rotate(7.73 23.732 10.897)" class="qiz3_1b0n"/><g filter="url(#in4DRbT)"><path fill="url(#iVz4SYd)" class="cqt8lwnsb"/><path fill="url(#ijkee1d)" class="cqt8lwnsb"/></g><path fill="url(#i0Deuic)" clip-rule="evenodd" class="r436xhtkb"/><path fill="url(#iy7MGNd)" clip-rule="evenodd" class="fd6v8abgo"/><path fill="url(#ip4fM6d)" clip-rule="evenodd" class="fd6v8abgo"/><path clip-rule="evenodd" class="lm73sqb7x"/><path class="l5f0vv0gk"/><g filter="url(#iD50P2c)"><path class="vdutjhqub"/><path fill="url(#iK7vgud)" class="kdipkvb6m"/><path fill="url(#iNOq9nd)" class="kdipkvb6m"/></g><path class="uhryg_bvw"/><path fill="url(#imwu7ix)" class="ztjaa1b0c"/><path fill="url(#ixbJJWm)" class="ztjaa1b0c"/><path fill="url(#ixlmvjd)" class="ztjaa1b0c"/><path fill="url(#ijapwab)" class="ztjaa1b0c"/><path fill="url(#iF4z5Ab)" class="b1d4wvlor"/><path class="lqgr1v3ua"/><circle class="ncedebc3w"/><path fill="url(#i3O0Llc)" class="gl37qqljq"/><path fill="url(#iSRItPc)" class="gl37qqljq"/><path fill="url(#i4IEwqd)" class="gl37qqljq"/><path fill="url(#iuiIm1b)" class="gl37qqljq"/><path fill="url(#iyNWVMc)" class="gl37qqljq"/><g filter="url(#iDuWkmd)"><path class="e80_qpb-t"/><path fill="url(#ihABiHb)" class="h7qjpf4qw"/><path fill="url(#iTJDDoe)" class="h7qjpf4qw"/><path fill="url(#ihWaRtk)" class="h7qjpf4qw"/></g><g filter="url(#iotYTFb)"><path class="g29q64i3w"/><path fill="url(#iRPpJ7b)" class="d4hl2gbxa"/></g><g filter="url(#im7IKpd)"><path class="y-44cbcej"/><path fill="url(#ib7M4qb)" class="c44jfsbcl"/><path fill="url(#ifskYjy)" class="c44jfsbcl"/><path fill="url(#irfilVd)" class="c44jfsbcl"/></g><g filter="url(#i3HE2dd)"><path class="yueew9bxe"/><path fill="url(#ib7M4qb)" class="c44jfsbcl"/><path fill="url(#ifskYjy)" class="c44jfsbcl"/><path fill="url(#irfilVd)" class="c44jfsbcl"/></g><g filter="url(#imCPJsS)"><path class="v_z4e5a-y"/><path fill="url(#iYp6Wxe)" class="rz4x8ub3m"/></g><path fill="url(#iq86W0c)" clip-rule="evenodd" class="k6b97hgin"/><path fill="url(#iU9hA3R)" clip-rule="evenodd" class="k6b97hgin"/><path fill="url(#ixviJmF)" clip-rule="evenodd" class="k6b97hgin"/><path class="dalmjr83j"/><path fill="url(#iJIaPId)" class="zvx8bab1g"/><path fill="url(#ikQ4Nia)" class="zvx8bab1g"/><path class="qr3z3bbat"/><path class="onqkikb5s"/><path class="mwnt5qb9g"/><path fill="url(#i3UmpNe)" class="rj672694s"/><path class="lk29dtb_l"/><path fill="url(#ivzJTrw)" class="a99hzmbwx"/><path class="ifw90zbwp"/><path fill="url(#ieVivdc)" class="ippwfacqd"/><g filter="url(#i9KDsld)"><path fill="url(#i1r3KqE)" class="xsx2-_bqq"/></g><circle fill="url(#iEELTNH)" class="p4fxkrs4n"/><path clip-rule="evenodd" class="ic-pg865j"/><path fill="url(#irvcAdr)" clip-rule="evenodd" class="pf-fv0k6b"/><path fill="url(#izTlRPe)" clip-rule="evenodd" class="pf-fv0k6b"/><path fill="url(#iJQfylj)" clip-rule="evenodd" class="pf-fv0k6b"/><g filter="url(#iGs5d7v)"><path fill="url(#iwGoqPd)" class="pt5kwtbum"/></g><g filter="url(#iUmgSMb)"><path fill="url(#iDf9qTd)" class="h_5uwnxae"/></g><path class="up55sb85w"/><path fill="url(#iSyG5rb)" class="uxzfxkh9p"/><g filter="url(#iRS1H8h)"><path clip-rule="evenodd" class="qvgzqwbuq"/></g><path fill="url(#i6zh9db)" class="t0447fais"/><path fill="url(#iiGOerb)" class="t0447fais"/><path fill="url(#iNQ5E7d)" class="t0447fais"/><path fill="url(#iwe6xbe)" class="mvoxdmbia"/><path fill="url(#iY7yfmd)" class="mvoxdmbia"/><path fill="url(#ithtSmc)" class="mvoxdmbia"/><g filter="url(#ipXisUc)"><path class="iay78elet"/></g><defs><radialGradient id="i0f4ATc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.507 28.595)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="iNeH5UJ" cx="0" cy="0" r="1" gradientTransform="rotate(-83.29 17.248 5.23)scale(2.67447 5.21781)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="iOMayze" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 3.143 10.684)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="iZf3pte" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.913 21.47)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="iIPgPFA" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.49 5.308)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="iagmCgS" cx="0" cy="0" r="1" gradientTransform="rotate(66.687 4.626 19.082)scale(6.35158 4.4947)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="f_1v57bhd"/><stop offset="1" class="pl76o5b_i"/></radialGradient><radialGradient id="iYslrsd" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.356 8.632)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="igf9Oyb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 13.163 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="iyC7bob" cx="0" cy="0" r="1" gradientTransform="matrix(-.10714 .67871 -.5326 -.08407 22.982 8.146)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="p62i0qb1k"/><stop offset="1" class="d7aonq0wf"/></radialGradient><radialGradient id="inExGvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.554 21.672)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="iUKZlCd" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.476 19.192)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="imv7p5d" cx="0" cy="0" r="1" gradientTransform="matrix(.00508 -1.12418 .93572 .00423 25.04 11.966)" gradientUnits="userSpaceOnUse"><stop class="nk-mbmbtk"/><stop offset="1" class="db1j3cbeu"/></radialGradient><radialGradient id="iVz4SYd" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 23.163 8.766)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gro4u4t-y"/><stop offset="1" class="x8-nb-ihc"/></radialGradient><radialGradient id="ijkee1d" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.316 12.026)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="wxl7pfshq"/><stop offset="1" class="ghwh3eklg"/></radialGradient><radialGradient id="ip4fM6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 26.011 19.563)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="iNOq9nd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23438 -.90624 .39526 -.97452 21.646 22.042)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="bylttzbhe"/><stop offset="1" class="f7ds2glhm"/></radialGradient><radialGradient id="imwu7ix" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.233 9.943)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="ixbJJWm" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.846 13.282)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="ijapwab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 23.1 28.282)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="iSRItPc" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 10.136 11.777)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="aamjxwftu"/><stop offset="1" class="kbmwaf_hi"/></radialGradient><radialGradient id="i4IEwqd" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.85 11.766)" gradientUnits="userSpaceOnUse"><stop class="xs_2ilnpm"/><stop offset="1" class="p8p5c3bvm"/></radialGradient><radialGradient id="iuiIm1b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06251 1.12498 -.6497 -1.19113 22.929 14.141)" gradientUnits="userSpaceOnUse"><stop class="am3w7_blp"/><stop offset="1" class="couxg3lqo"/></radialGradient><radialGradient id="iyNWVMc" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.507 15.297)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="dq08bkdrq"/><stop offset="1" class="wqel62b_c"/></radialGradient><radialGradient id="ihABiHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.695 21.813)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="iTJDDoe" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 20.241 19.688)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="ihWaRtk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 22.116 19.61)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="ib7M4qb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.6 17.875)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="irfilVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.304 17.22)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="iYp6Wxe" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.538 19.375)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="ixviJmF" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.96 16.172)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="iJIaPId" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.09375 .03207 .24052 19.982 6.776)" gradientUnits="userSpaceOnUse"><stop class="r_5s-tw4v"/><stop offset="1" class="kqp9fdbzy"/></radialGradient><radialGradient id="ikQ4Nia" cx="0" cy="0" r="1" gradientTransform="matrix(.8086 -.23047 .16066 .56368 19.716 7.568)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="czdn7vy6a"/><stop offset="1" class="gk9uazn2k"/></radialGradient><radialGradient id="i1r3KqE" cx="0" cy="0" r="1" gradientTransform="rotate(126.754 10.888 11.724)scale(1.54063 1.00944)" gradientUnits="userSpaceOnUse"><stop class="vayzxccat"/><stop offset="1" class="fgz9pzbnm"/></radialGradient><radialGradient id="iEELTNH" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.516 18.873)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="a0px9dj6c"/><stop offset="1" class="ufi1sccsl"/></radialGradient><radialGradient id="iJQfylj" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.952 9.672)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="iwGoqPd" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.693 9.973)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="iDf9qTd" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45313 1.162 .94162 25.663 8.375)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="i6zh9db" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.543 6.893)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="iiGOerb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15626 -3.3125 9.2644 3.23382 19.74 19.626)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="nuwcoob-p"/><stop offset="1" class="gzdogx1hl"/></radialGradient><radialGradient id="iNQ5E7d" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -2.01 19.91)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="iwe6xbe" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.387 16.233)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="k2smfncym"/><stop offset="1" class="nr_9l6l2k"/></radialGradient><radialGradient id="ithtSmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92187 .21875 -.25309 -1.06657 24.695 13.094)" gradientUnits="userSpaceOnUse"><stop class="vgv_qabik"/><stop offset="1" class="muvudkmkj"/></radialGradient><linearGradient id="ienbumd" x1="11.438" x2="11.438" y1="30.141" y2="28.846" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="i0v7cme" x1="5.32" x2="6.476" y1="17.719" y2="21" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="ikBPldd" x1="5.82" x2="6.163" y1="17.719" y2="18.688" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="ipTu1mb" x1="13.413" x2="11.57" y1="2.032" y2="15.157" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="ivyVoHc" x1="2.601" x2="13.132" y1="17.907" y2="13.751" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="iCv86Yc" x1="14.269" x2="16.87" y1="10.858" y2="15.376" gradientUnits="userSpaceOnUse"><stop offset=".368" class="d6jlrzbaa"/><stop offset="1" class="w5vd7udwg"/></linearGradient><linearGradient id="imj0iWb" x1="4.507" x2="6.882" y1="5.438" y2="13.719" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="iUaPnIF" x1="5.788" x2="5.507" y1="14.329" y2="13.329" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="irqXdRb" x1="19.609" x2="21.582" y1="7.887" y2="10.832" gradientUnits="userSpaceOnUse"><stop class="v8ombmbjb"/><stop offset="1" class="r1g9oggar"/></linearGradient><linearGradient id="iMAjlee" x1="19.576" x2="20.935" y1="11.14" y2="15.8" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="iSMW0ee" x1="25.101" x2="26.507" y1="20.485" y2="20.485" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="i0Deuic" x1="24.875" x2="24.601" y1="18.747" y2="18.747" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="iy7MGNd" x1="26.491" x2="24.475" y1="20.025" y2="19.188" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="iK7vgud" x1="22.739" x2="21.339" y1="25.568" y2="26.203" gradientUnits="userSpaceOnUse"><stop class="ckxh1ljog"/><stop offset="1" class="om1zr9boo"/></linearGradient><linearGradient id="ixlmvjd" x1="23.261" x2="23.155" y1="28.106" y2="28.024" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="iF4z5Ab" x1="23.659" x2="23.905" y1="8.43" y2="7.993" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="i3O0Llc" x1="24.882" x2="22.695" y1="16" y2="12.188" gradientUnits="userSpaceOnUse"><stop class="r1kmajh1r"/><stop offset="1" class="dwwl7kmwu"/></linearGradient><linearGradient id="iRPpJ7b" x1="14.177" x2="14.802" y1="17.042" y2="18.041" gradientUnits="userSpaceOnUse"><stop class="eizi_gdki"/><stop offset="1" class="pbgm9vhci"/></linearGradient><linearGradient id="ifskYjy" x1="20.132" x2="21.101" y1="20.29" y2="17.313" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="iq86W0c" x1="23.103" x2="23.103" y1="16.875" y2="18.313" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="iU9hA3R" x1="24.296" x2="24.527" y1="18.403" y2="17.958" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="i3UmpNe" x1="15.617" x2="15.756" y1="11.899" y2="11.731" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="ivzJTrw" x1="15.825" x2="15.993" y1="11.47" y2="11.268" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="ieVivdc" x1="16.091" x2="16.277" y1="11.074" y2="10.847" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="irvcAdr" x1="24.945" x2="24.624" y1="10.026" y2="9.782" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="izTlRPe" x1="23.491" x2="23.929" y1="10.579" y2="10.868" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="iSyG5rb" x1="16.509" x2="16.699" y1="10.846" y2="10.65" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="iY7yfmd" x1="23.21" x2="23.085" y1="14.907" y2="13.985" gradientUnits="userSpaceOnUse"><stop class="m3e4macxz"/><stop offset="1" class="j6phqvxik"/></linearGradient><filter id="idMB6pf" width="8.743" height="7.346" x="1.956" y="23.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_863" result="effect2_innerShadow_4002_863"/></filter><filter id="iU6IGKb" width="4.276" height="5.599" x="13.345" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_863" stdDeviation=".375"/></filter><filter id="ig3RZcc" width="6.514" height="7.799" x="18.148" y="6.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.721569 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="icO2hfc" width="3.479" height="7.738" x="13.92" y="2.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="i1q5gIL" width="2.679" height="4.12" x="19.144" y="7.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_863" stdDeviation=".15"/></filter><filter id="i5pQANe" width="2.822" height="15.029" x="19.286" y="2.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="in4DRbT" width="4.68" height="4.407" x="21.992" y="7.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.423529 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.670588 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_863" result="effect2_innerShadow_4002_863"/></filter><filter id="iD50P2c" width="5.316" height="9.197" x="18.756" y="20.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.639216 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="iDuWkmd" width="5.527" height="3.544" x="18.964" y="18.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="iotYTFb" width="9.577" height="5.489" x="9.645" y="15.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.47451 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="im7IKpd" width="6.672" height="5.002" x="18.132" y="15.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="i3HE2dd" width="6.922" height="5.002" x="18.132" y="15.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.364706 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="imCPJsS" width="2.568" height="3.646" x="9.622" y="17.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="i9KDsld" width="2.604" height="2.473" x="25.109" y="8.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.623529 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="iGs5d7v" width="4.913" height="4.647" x="23.386" y="5.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="iUmgSMb" width="1.588" height="1.361" x="25.048" y="7.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="iRS1H8h" width="6.514" height="4.796" x="15.609" y="10.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.509804 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_863"/></filter><filter id="ipXisUc" width="3.862" height="3.738" x="16.22" y="10.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_863" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-climbing-medium-light" /></template>
<style>
.a0px9dj6c {
  stop-color: var(--svg-color--c3958d, #C3958D);
}

.a99hzmbwx {
  d: path("M15.04 10.857a.28.28 0 0 1 .368-.42l1.5 1.31l-.368.42z");
}

.aamjxwftu {
  stop-color: var(--svg-color--53bfff, #53BFFF);
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.am3w7_blp {
  stop-color: var(--svg-color--1b7eec, #1B7EEC);
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.atg-_ebrv {
  d: path("m16.87 12.45l-.06.426c-.113.802-.39 1.194-.87 1.488l-.857-1.286l-.946-1.329a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .292-.433l-.024-.033a.28.28 0 1 1 .455-.323l.107.146a.28.28 0 0 1 .5-.223l.499.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345a4 4 0 0 0-.06.6c.001.39.072.613.158.788");
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.b1d4wvlor {
  d: path("m23.83 8.538l.026-.04c.131-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biyiff5mh {
  stop-color: var(--svg-color--333061, #333061);
}

.boi6lnlog {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
}

.bpm5gvbdi {
  stop-color: var(--svg-color--e5e3e5, #E5E3E5);
}

.bylttzbhe {
  stop-color: var(--svg-color--bf7f81, #BF7F81);
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.c44jfsbcl {
  d: path("m21.093 16.57l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.ckxh1ljog {
  stop-color: var(--svg-color--f0bea1, #F0BEA1);
}

.couxg3lqo {
  stop-color: var(--svg-color--1b7eec, #1B7EEC);
  stop-opacity: 0;
}

.cqt8lwnsb {
  d: path("M22.312 9.618c.277-.875.95-1.815 1.21-2.188l2.9 1.867l-.594 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.czdn7vy6a {
  stop-color: var(--svg-color--b9745e, #B9745E);
}

.d4hl2gbxa {
  d: path("m18.425 15.551l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.d6jlrzbaa {
  stop-color: var(--svg-color--908790, #908790);
}

.d7aonq0wf {
  stop-color: var(--svg-color--d4997b, #D4997B);
}

.dalmjr83j {
  fill: var(--svg-color--dfb491, #DFB491);
  d: path("M20.484 7.07c.003.395-.166.71-.25.817l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.db1j3cbeu {
  stop-color: var(--svg-color--cb7a6a, #CB7A6A);
}

.dfv3zlvmf {
  stop-color: var(--svg-color--648431, #648431);
}

.dnpfueb4s {
  stop-color: var(--svg-color--40347f, #40347F);
}

.dq08bkdrq {
  stop-color: var(--svg-color--67a3db, #67A3DB);
}

.dwwl7kmwu {
  stop-color: var(--svg-color--4d94cd, #4D94CD);
}

.e_59tbbed {
  stop-color: var(--svg-color--292557, #292557);
}

.e2k-esbpn {
  stop-color: var(--svg-color--c3c0c6, #C3C0C6);
  stop-opacity: 0;
}

.e80_qpb-t {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.464 20.854l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.eizi_gdki {
  stop-color: var(--svg-color--dca888, #DCA888);
}

.eky141x3a {
  stop-color: var(--svg-color--489778, #489778);
}

.enju3fb9g {
  d: path("m24.6 19.192l1.907.63v.73a.953.953 0 1 1-1.906 0z");
}

.f_1v57bhd {
  stop-color: var(--svg-color--d59b81, #D59B81);
}

.f2xkzabrk {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
  stop-opacity: 0;
}

.f2yuiwowd {
  stop-color: var(--svg-color--948b99, #948B99);
}

.f7ds2glhm {
  stop-color: var(--svg-color--bf7f81, #BF7F81);
  stop-opacity: 0;
}

.fd6v8abgo {
  fill-rule: evenodd;
  d: path("M24.486 19.154a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
}

.fgz9pzbnm {
  stop-color: var(--svg-color--e1bba2, #E1BBA2);
}

.fiw9fyalo {
  stop-color: var(--svg-color--4b4386, #4B4386);
}

.foggvnbji {
  d: path("M14.803 14.876L2.356 19.238V2.196H18.3c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.ft5dv1b6b {
  fill: none;
}

.fwnzc4ctw {
  stop-color: var(--svg-color--5a332d, #5A332D);
}

.fy9sosv6u {
  stop-color: var(--svg-color--417c62, #417C62);
  stop-opacity: 0;
}

.g29q64i3w {
  fill: var(--svg-color--d8a283, #D8A283);
  d: path("m18.425 15.551l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
}

.ghwh3eklg {
  stop-color: var(--svg-color--a46f70, #A46F70);
  stop-opacity: 0;
}

.gk9uazn2k {
  stop-color: var(--svg-color--b9745e, #B9745E);
  stop-opacity: 0;
}

.gl37qqljq {
  d: path("m22.624 13.094l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.102-1.765c-.316-.172-1.025-.28-1.398-.16s-.73.663-.883 1.09");
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.gro4u4t-y {
  stop-color: var(--svg-color--d19f82, #D19F82);
}

.gu1w6obkb {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
  stop-opacity: 0;
}

.gzdogx1hl {
  stop-color: var(--svg-color--7e7776, #7E7776);
}

.gzh61e4uu {
  d: path("M22.452 8.43c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.h_5uwnxae {
  d: path("M25.111 7.584a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.368.479l-.984-.758a.3.3 0 0 1-.055-.423");
}

.h7qjpf4qw {
  d: path("m19.464 20.854l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.iay78elet {
  stroke: var(--svg-color--e9b397, #E9B397);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.87 11.232l2.563 2.437");
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.ic-pg865j {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.714 8.636a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.ifw90zbwp {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M15.192 10.342a.28.28 0 1 1 .368-.421l1.754 1.506l-.368.42z");
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.ippwfacqd {
  d: path("M15.192 10.342a.28.28 0 1 1 .368-.421l1.754 1.506l-.368.42z");
}

.j-c4i6bgu {
  stop-color: var(--svg-color--5e598c, #5E598C);
  stop-opacity: 0;
}

.j6phqvxik {
  stop-color: var(--svg-color--2280e0, #2280E0);
  stop-opacity: 0;
}

.jbbp6_bdq {
  stop-color: var(--svg-color--716170, #716170);
  stop-opacity: 0;
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k2smfncym {
  stop-color: var(--svg-color--34aef0, #34AEF0);
}

.k6b97hgin {
  fill-rule: evenodd;
  d: path("M21.072 15.938a.25.25 0 0 1 .341-.092l3.629 2.09a.25.25 0 1 1-.25.433l-3.628-2.09a.25.25 0 0 1-.092-.34");
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kao1--wwn {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
}

.kbmwaf_hi {
  stop-color: var(--svg-color--53bfff, #53BFFF);
  stop-opacity: 0;
}

.kdipkvb6m {
  d: path("m19.195 21.141l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.127-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203a448 448 0 0 1-2.75-3.945c-.613-.9-.167-1.636.133-1.89");
}

.kqp9fdbzy {
  stop-color: var(--svg-color--e8bb9d, #E8BB9D);
  stop-opacity: 0;
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.kxbrb3y6a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.694 7.99c.07.492.482 1.784 1.58 3.02");
}

.l5f0vv0gk {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.804 7.946c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.lk29dtb_l {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M15.04 10.857a.28.28 0 0 1 .368-.42l1.5 1.31l-.368.42z");
}

.lm73sqb7x {
  fill: var(--svg-color--86004d, #86004D);
  fill-rule: evenodd;
  d: path("M22.677 9.336a.1.1 0 0 1 .139-.029c.085.056.25.103.52.041a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.lqgr1v3ua {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.672 8.434l.053-.07c.073-.12.081-.25.018-.288c-.062-.038-.173.028-.246.148l-.035.071z");
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.m3e4macxz {
  stop-color: var(--svg-color--2280e0, #2280E0);
}

.mmu9u7bsf {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
}

.mn787q_6r {
  stop-color: var(--svg-color--c7c5c9, #C7C5C9);
}

.mr6mdpt1g {
  stop-color: var(--svg-color--716170, #716170);
}

.msti5wbjw {
  stop-color: var(--svg-color--8c7786, #8C7786);
}

.muvudkmkj {
  stop-color: var(--svg-color--56c0ff, #56C0FF);
  stop-opacity: 0;
}

.mvoxdmbia {
  d: path("m21.52 15.18l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
}

.mwbu5sbnw {
  stop-color: var(--svg-color--4a4476, #4A4476);
}

.mwnt5qb9g {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M14.965 11.39a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.mzz_2wq-t {
  stop-color: var(--svg-color--c2bfc5, #C2BFC5);
}

.n_3yhnb8a {
  stop-color: var(--svg-color--958e9b, #958E9B);
  stop-opacity: 0;
}

.n7jws8bws {
  stop-color: var(--svg-color--4b4386, #4B4386);
  stop-opacity: 0;
}

.n7r2-292q {
  stop-color: var(--svg-color--958e9b, #958E9B);
}

.ncedebc3w {
  cx: 23.764px;
  cy: 8.074px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.njdjvcttb {
  stop-color: var(--svg-color--ae9ea8, #AE9EA8);
}

.nk-mbmbtk {
  stop-color: var(--svg-color--e5a08a, #E5A08A);
}

.nkzm4gb5h {
  stop-color: var(--svg-color--a297ad, #A297AD);
}

.nmynr_cvx {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
}

.nr_9l6l2k {
  stop-color: var(--svg-color--3a9cf8, #3A9CF8);
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nuwcoob-p {
  stop-color: var(--svg-color--a49ba8, #A49BA8);
  stop-opacity: 0;
}

.nv_3ww30s {
  d: path("M9.591 17.135a.93.93 0 0 1 .458-.698l-7.693 2.651v2.661c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.nwhi_fa4f {
  stop-color: var(--svg-color--413b69, #413B69);
}

.om1zr9boo {
  stop-color: var(--svg-color--f0bea1, #F0BEA1);
  stop-opacity: 0;
}

.onqkikb5s {
  fill: var(--svg-color--dfa690, #DFA690);
  d: path("m16.78 10.158l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.os32btykc {
  stop-color: var(--svg-color--66619b, #66619B);
}

.p2417ob0x {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
  stop-opacity: 0;
}

.p4fxkrs4n {
  cx: 25.448px;
  cy: 9.487px;
  r: 0.559px;
}

.p62i0qb1k {
  stop-color: var(--svg-color--cc9778, #CC9778);
}

.p8p5c3bvm {
  stop-color: var(--svg-color--4788c0, #4788C0);
  stop-opacity: 0;
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pbgm9vhci {
  stop-color: var(--svg-color--dca888, #DCA888);
  stop-opacity: 0;
}

.pf-fv0k6b {
  fill-rule: evenodd;
  d: path("M25.714 8.636a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.pids_pbns {
  stop-color: var(--svg-color--948f8f, #948F8F);
}

.pktfr7bne {
  stop-color: var(--svg-color--d28f83, #D28F83);
}

.pl76o5b_i {
  stop-color: var(--svg-color--af6c57, #AF6C57);
}

.ps4wek9uf {
  stop-color: var(--svg-color--4a4476, #4A4476);
  stop-opacity: 0;
}

.pt5kwtbum {
  d: path("m27.11 10.202l-3.628-2.696a.22.22 0 0 1-.069-.288a4.8 4.8 0 0 1 .655-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.qiz3_1b0n {
  d: path("M23.732 10.897h1.905v1.844h-1.905z");
}

.qr3z3bbat {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("m16.78 10.158l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.qvgzqwbuq {
  fill: var(--svg-color--dfa68f, #DFA68F);
  fill-rule: evenodd;
  d: path("M18.264 14.385L15.61 11.95l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.423l.433 1.696l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.qxe3b85cr {
  d: path("M13.94 2.152c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
}

.r_5s-tw4v {
  stop-color: var(--svg-color--e8bb9d, #E8BB9D);
}

.r1g9oggar {
  stop-color: var(--svg-color--d9a288, #D9A288);
  stop-opacity: 0;
}

.r1kmajh1r {
  stop-color: var(--svg-color--3aadff, #3AADFF);
}

.r436xhtkb {
  fill-rule: evenodd;
  d: path("M24.675 18.105c.11 0 .2.09.2.2v.883a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
}

.r8uyz9bqp {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
}

.rdr27y14e {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
  stop-opacity: 0;
}

.reex3410h {
  stop-color: var(--svg-color--e2dfe2, #E2DFE2);
}

.rj672694s {
  d: path("M14.965 11.39a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.rz4x8ub3m {
  d: path("m12.14 20.2l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.s6i7kxbsp {
  d: path("M2.356 30.141v-8.953l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.113 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.556l5 4.753z");
}

.sf7z4ybcf {
  stop-color: var(--svg-color--d1cfd2, #D1CFD2);
  stop-opacity: 0;
}

.shmkg3ete {
  stop-color: var(--svg-color--7a7996, #7A7996);
}

.sscrhab_a {
  d: path("M10.22 2.196c.551 1.054 1.37 2.957 1.85 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V2.196z");
}

.t-qeblb7d {
  stop-color: var(--svg-color--e2e0e4, #E2E0E4);
}

.t0447fais {
  d: path("M21.095 16.566c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014c-.906-.21-1.484-.406-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

.t20d06bem {
  stop-color: var(--svg-color--816878, #816878);
  stop-opacity: 0;
}

.t20fa7b7o {
  stop-color: var(--svg-color--9d94a6, #9D94A6);
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tslw4_1qu {
  stop-color: var(--svg-color--63608c, #63608C);
}

.tvjmrrbpc {
  stop-color: var(--svg-color--5e505b, #5E505B);
}

.tylpo8bot {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
  stop-opacity: 0;
}

.ufi1sccsl {
  stop-color: var(--svg-color--bd7475, #BD7475);
}

.uhryg_bvw {
  fill: var(--svg-color--544583, #544583);
  d: path("m23.04 26.345l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.up55sb85w {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M15.765 10.111a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.uubye-mwc {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
}

.uuc-lrj5h {
  stop-color: var(--svg-color--7a7996, #7A7996);
  stop-opacity: 0;
}

.uxzfxkh9p {
  d: path("M15.765 10.111a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.v_z4e5a-y {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m12.14 20.2l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.v5_ahxl8w {
  stop-color: var(--svg-color--554682, #554682);
}

.v8ombmbjb {
  stop-color: var(--svg-color--d9a288, #D9A288);
}

.vayzxccat {
  stop-color: var(--svg-color--f1d2af, #F1D2AF);
}

.vdutjhqub {
  fill: var(--svg-color--ce9087, #CE9087);
  d: path("m19.195 21.141l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.127-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203a448 448 0 0 1-2.75-3.945c-.613-.9-.167-1.636.133-1.89");
}

.vgv_qabik {
  stop-color: var(--svg-color--56c0ff, #56C0FF);
}

.vp6yj4xxl {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
}

.vps27w8pe {
  stop-color: var(--svg-color--413b69, #413B69);
  stop-opacity: 0;
}

.w5vd7udwg {
  stop-color: var(--svg-color--908790, #908790);
  stop-opacity: 0;
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wlyubdb4v {
  stop-color: var(--svg-color--d6d4d7, #D6D4D7);
}

.wqel62b_c {
  stop-color: var(--svg-color--67a3db, #67A3DB);
  stop-opacity: 0;
}

.ws0t5un5c {
  stop-color: var(--svg-color--816878, #816878);
}

.wxl7pfshq {
  stop-color: var(--svg-color--a46f70, #A46F70);
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x8-nb-ihc {
  stop-color: var(--svg-color--cf9388, #CF9388);
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xctpj4u6q {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.356 23.196v6.945H10.7a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.523c-.065-.141-.186-.451-.371-.924l-.285-.725c-.322-.816-.953-1.219-1.437-1.422z");
}

.xgvx5wb1m {
  stop-color: var(--svg-color--d28f83, #D28F83);
  stop-opacity: 0;
}

.xs_2ilnpm {
  stop-color: var(--svg-color--4788c0, #4788C0);
}

.xsx2-_bqq {
  d: path("m25.161 10.431l.488-1.367l1.663 1.17c-.182.277-.795 1.021-1.025 1.104c-.318.113-.785.19-1.035-.118c-.2-.247-.15-.65-.091-.789");
}

.xv468xbcl {
  fill-rule: evenodd;
  d: path("M23.664 13.956c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.341c.33 2.085 1.175 4.09 4.47 5.869z");
}

.xzhs54baa {
  stop-color: var(--svg-color--948f8f, #948F8F);
  stop-opacity: 0;
}

.y-44cbcej {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m21.093 16.57l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.ytaxympda {
  d: path("M19.286 2.196v9.588c0 .132.027.263.079.384l1.706 3.989l.42.137c.05.114.166.978.28.929a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V2.196z");
}

.yueew9bxe {
  fill: var(--svg-color--9f97a9, #9F97A9);
  d: path("m21.093 16.57l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zf7t0yb1u {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
}

.zp0x88wix {
  stop-color: var(--svg-color--aaa6ae, #AAA6AE);
  stop-opacity: 0;
}

.ztjaa1b0c {
  d: path("m23.04 26.345l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.zvx8bab1g {
  d: path("M20.484 7.07c.003.395-.166.71-.25.817l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

</style>
