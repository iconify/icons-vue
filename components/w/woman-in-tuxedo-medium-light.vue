<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#io5Lq9l)"><path fill="url(#iC4Tsjb)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#iEURp7c)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#irDnH2d)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#iUo8rpe)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#idHXI7c)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#iDwZsid)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#iyBNeic)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#iXzb5fI)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#i13tYPb)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#i0LMsOd)" clip-rule="evenodd" class="ene-v8epk"/></g><path fill="url(#iM2PU2d)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#iysTndg)" clip-rule="evenodd" class="ene-v8epk"/><path fill="url(#iOTSjsd)" class="iwijhb8cc"/><path fill="url(#iVt7Kmd)" class="iwijhb8cc"/><path fill="url(#ijJWFGd)" class="iwijhb8cc"/><path fill="url(#iuyr1tn)" class="iwijhb8cc"/><path fill="url(#iwTkvTT)" class="iwijhb8cc"/><path fill="url(#iGY3pLe)" class="z77pc-39f"/><path fill="url(#iOmSTFf)" class="z77pc-39f"/><g filter="url(#isTXeUd)"><path fill="url(#iHafYHb)" class="uoh3u9bsv"/><path fill="url(#irRAuOe)" class="uoh3u9bsv"/></g><path fill="url(#iosNevc)" class="bv7-wxb3q"/><g filter="url(#iPqH9Ce)"><path fill="url(#i0qUINb)" class="wsuqc2bol"/><path fill="url(#iDSTCFe)" class="wsuqc2bol"/></g><g filter="url(#i90Ka1c)"><path clip-rule="evenodd" class="nzd5pi4db"/></g><path fill="url(#iQD9ace)" class="pwzf73bct"/><path fill="url(#iulJYbe)" class="pwzf73bct"/><path fill="url(#i4qDnic)" class="pwzf73bct"/><path fill="url(#ig0Fqhd)" class="pwzf73bct"/><path fill="url(#i3hbZ4w)" class="d0ocvmu4d"/><path fill="url(#ivP7kqb)" class="d0ocvmu4d"/><path fill="url(#iwDR1wV)" class="d0ocvmu4d"/><path fill="url(#i1L7Mpd)" class="d0ocvmu4d"/><g filter="url(#iOrZ4Jb)"><path fill="url(#i6XAUBd)" class="d60lbkuym"/></g><g filter="url(#iQAsShe)"><path fill="url(#iLOUAXd)" class="dj5l2yqzg"/></g><path fill="url(#iHd26xe)" class="dj5l2yqzg"/><path fill="url(#iZCJqXd)" class="dj5l2yqzg"/><path fill="url(#ixvOk5d)" class="dj5l2yqzg"/><g filter="url(#isiuRlc)"><path class="wga2pr3ix"/></g><g filter="url(#i1RQaRb)"><circle class="mvlg1lb-a"/></g><g filter="url(#i6kIEBc)"><circle class="tao08pzef"/></g><g filter="url(#iEKQUFb)"><circle fill="url(#iGv238b)" class="qsy44ybab"/></g><g filter="url(#ivlgvsd)"><circle fill="url(#iUdTZPc)" class="zgcak206m"/></g><rect fill="url(#ilOIclb)" class="epgmjx2er"/><rect fill="url(#iheKdde)" class="epgmjx2er"/><rect fill="url(#irEUGGc)" class="epgmjx2er"/><rect fill="url(#iiIRg2d)" class="epgmjx2er"/><g filter="url(#ivtaNjc)"><path fill="url(#i7lfzIe)" class="o-ok2ibcd"/></g><path fill="url(#iBWIq2c)" class="o-ok2ibcd"/><g filter="url(#i94jDge)"><path class="ku2lh6uuy"/><path fill="url(#isKdouB)" class="pbpjm1bhy"/><path fill="url(#iXYh5ub)" class="pbpjm1bhy"/><path fill="url(#ipN7wmd)" class="pbpjm1bhy"/></g><g filter="url(#inaWq4d)"><circle fill="url(#icPlPbd)" class="wui8nqfgb"/><circle fill="url(#iAsT4et)" class="wui8nqfgb"/></g><path fill="url(#if4vDlY)" class="lmkyvq38o"/><path fill="url(#iZ5HQbe)" class="dc_z0_bxw"/><g filter="url(#iT0OLae)"><path fill="url(#iaxIJrb)" class="jeah4dbrk"/></g><g filter="url(#iZripdd)"><path fill="url(#iWecT3c)" class="uqyvgzkbv"/><path fill="url(#iFPBe6c)" class="uqyvgzkbv"/></g><g filter="url(#iTq0Y1c)"><path class="dohjyt8kz"/><path fill="url(#iaUkQTd)" class="f76qgd9qn"/></g><g filter="url(#inYFshb)"><path class="pifmjgb7d"/><path fill="url(#iurQo4d)" class="c047y6t2e"/></g><g filter="url(#i2EOKWd)"><path fill="url(#ibq5Q1b)" class="dkhaswb9x"/><path fill="url(#i1dp0ld)" class="dkhaswb9x"/><path fill="url(#iRlqPab)" class="dkhaswb9x"/><path fill="url(#iDjouFc)" class="dkhaswb9x"/><path fill="url(#iCUklOd)" class="dkhaswb9x"/><path fill="url(#iLd31Ce)" class="dkhaswb9x"/><path fill="url(#ifIwoYb)" class="dkhaswb9x"/></g><path fill="url(#iCIyckb)" class="mmwou_i8u"/><path fill="url(#ioHjRPb)" class="mmwou_i8u"/><g filter="url(#i3w4aiV)"><path class="rpm4ycxof"/></g><g filter="url(#i4Rvmyb)"><path class="mbqyinbph"/><path fill="url(#iIehpkF)" class="omj93bweh"/><path fill="url(#iAtxlPe)" class="omj93bweh"/><path fill="url(#i25jbue)" class="omj93bweh"/></g><g filter="url(#itATmQb)"><path stroke="url(#i2PyylL)" class="pn527rb9i"/></g><path class="hlpsh0pka"/><g filter="url(#imAvk9U)"><path class="axutl7beo"/></g><g filter="url(#iGMCOac)"><path class="rr_xtkbqp"/></g><g filter="url(#iVe6LCc)"><path class="n0hytgbgy"/></g><g filter="url(#iQeF9Jb)"><path clip-rule="evenodd" class="lcsuusbll"/></g><path class="bchzmi1so"/><path fill="url(#inxyNOc)" class="l6bu9wb8i"/><path class="dnyi2nbwd"/><g filter="url(#ibz83zd)"><path class="a6wyg-bez"/><path fill="url(#iLwyvNe)" class="ikym1vb8z"/></g><g filter="url(#iNhJGXc)"><path fill="url(#i5hXDwe)" class="qeue4_bux"/></g><path class="prstl2fga"/><path fill="url(#iecUIAb)" class="qjruynb1t"/><path class="hmh19xb-g"/><g filter="url(#iVciPfe)"><path fill="url(#iFGHLod)" class="l24ppp87r"/></g><g filter="url(#ibg7BHe)"><ellipse transform="rotate(-27.914 13.54 9.862)" class="ud62v449c"/><ellipse fill="url(#iHIFKte)" transform="rotate(-27.914 13.54 9.862)" class="hyrjkgb1x"/></g><g filter="url(#iBY6FNG)"><path class="ecnu8434e"/></g><g filter="url(#iCoHh0c)"><path class="ir2ky6n1g"/></g><g filter="url(#i1daZhb)"><path fill="url(#iDSyN4c)" class="t071f0bxb"/><path fill="url(#irL4e7z)" class="t071f0bxb"/></g><g filter="url(#imUSSAc)"><path fill="url(#iTHKFLe)" class="be6j1sb0b"/><path fill="url(#i3qje5c)" class="be6j1sb0b"/><path fill="url(#ir6i3fe)" class="be6j1sb0b"/></g><g filter="url(#iDpGoqd)"><path stroke="url(#iLn3WkG)" class="x69bombgk"/></g><defs><radialGradient id="iEURp7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 20.686 16.375)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="irDnH2d" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 3.274 11.617)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iUo8rpe" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 4.155 8.868)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="idHXI7c" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.772 8.288)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iDwZsid" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.354 3.999)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iyBNeic" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 12.155 2.983)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="iXzb5fI" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.688 7.132)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="i13tYPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.502 9.704)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="i0LMsOd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 23.234 12.486)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iM2PU2d" cx="0" cy="0" r="1" gradientTransform="rotate(4.928 -166.904 220.333)scale(5.21139)" gradientUnits="userSpaceOnUse"><stop class="ku5k7n3yy"/><stop offset="1" class="of-5eykok"/></radialGradient><radialGradient id="iysTndg" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.2151 -13.5901 0 15.993 7.99)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="cqetd1bxd"/><stop offset="1" class="t3_bfrc1u"/></radialGradient><radialGradient id="iOTSjsd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.376)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="iVt7Kmd" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.756 10.843)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="ijJWFGd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.287)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iGY3pLe" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.271 2.64)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iOmSTFf" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.187)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="iHafYHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.443)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="iosNevc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.599)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="i0qUINb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.568)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iDSTCFe" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.33 13.055)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="iulJYbe" cx="0" cy="0" r="1" gradientTransform="rotate(-148.052 10.537 8.072)scale(1.21384 4.09383)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="i4qDnic" cx="0" cy="0" r="1" gradientTransform="matrix(.7959 -.2721 .77398 2.26394 13.24 18.359)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="ivP7kqb" cx="0" cy="0" r="1" gradientTransform="rotate(16.487 -55.161 68.502)scale(1.44847 6.30545)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iwDR1wV" cx="0" cy="0" r="1" gradientTransform="matrix(-.2731 .4204 -1.76025 -1.14347 17.274 19.237)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="iLOUAXd" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.073 11.886)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="iHd26xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91837 1.77673 -4.30254 -2.22394 13.135 16.373)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="iZCJqXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.92462 -.4885 0 11.747 16.431)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="ixvOk5d" cx="0" cy="0" r="1" gradientTransform="rotate(86.901 -5.602 15.98)scale(1.69986 .36274)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iGv238b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.862 16.074)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iUdTZPc" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.48 14.57)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iheKdde" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.54688 1.51805 2.0819 14.294 18.047)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="w6batdbtw"/><stop offset="1" class="o8km552wm"/></radialGradient><radialGradient id="irEUGGc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.74927 .5625 -.2661 -1.30057 16.012 15.917)" gradientUnits="userSpaceOnUse"><stop offset=".389" class="f7xereb4t"/><stop offset="1" class="ki1lu3bjf"/></radialGradient><radialGradient id="iiIRg2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.82813 .3069 -.49372 4.54966 15.497 17.266)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="vnj0svbtx"/><stop offset="1" class="g0235lowf"/></radialGradient><radialGradient id="i7lfzIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.79)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iBWIq2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.166)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="iXYh5ub" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.448 6.885)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="ipN7wmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 19.021)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="icPlPbd" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.362 12.614)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iAsT4et" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.38)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="iWecT3c" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.033 10.994)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iFPBe6c" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 21.055 8.773)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iaUkQTd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.44 -52.104)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iurQo4d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 11.327 10.555)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="ibq5Q1b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.853 10.018)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="i1dp0ld" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.894 10.715)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iRlqPab" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.814 16.8)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iDjouFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.4375 -10.082 0 15.993 9.73)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="gxm-dc6uw"/></radialGradient><radialGradient id="iCUklOd" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.902 6.733)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iLd31Ce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 18.295 9.6)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="ifIwoYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.075 9.686)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iCIyckb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.089 11.087)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="ioHjRPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 13.493 4.512)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iIehpkF" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.778 11.813)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="inxyNOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.175 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iLwyvNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.947 10.042)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iecUIAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.811 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iHIFKte" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.772 -1.569)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDSyN4c" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 10.036 4.307)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="irL4e7z" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 13.278 4.541)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iTHKFLe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 17.904 2.63)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="i3qje5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 18.306 3.804)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="ir6i3fe" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.368 -.45)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="io5Lq9l" width="15.268" height="15.768" x="8.484" y="1.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="isTXeUd" width="4.081" height="11.683" x="5.07" y="18.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="iPqH9Ce" width="5.909" height="14.117" x="12.858" y="15.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="i90Ka1c" width="7.13" height="5.229" x="12.285" y="16.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".3"/></filter><filter id="iOrZ4Jb" width="7.239" height="14.645" x="9.195" y="15.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".5"/></filter><filter id="iQAsShe" width="5.917" height="14.259" x="10.326" y="15.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3333" result="effect2_innerShadow_4002_3333"/></filter><filter id="isiuRlc" width="6.567" height="14.209" x="15.297" y="15.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3333" result="effect2_innerShadow_4002_3333"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3333" result="effect3_innerShadow_4002_3333"/></filter><filter id="i1RQaRb" width="2" height="2" x="14.731" y="24.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".25"/></filter><filter id="i6kIEBc" width="2" height="2" x="14.731" y="21.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".25"/></filter><filter id="iEKQUFb" width="1.05" height="1.05" x="15.504" y="25.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="ivlgvsd" width="1.05" height="1.05" x="15.504" y="22.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="ivtaNjc" width="2.465" height="2.95" x="16.029" y="17.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3333" result="effect2_innerShadow_4002_3333"/></filter><filter id="i94jDge" width="2.365" height="2.9" x="13.731" y="17.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="inaWq4d" width="1.717" height="1.717" x="15.204" y="17.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="iT0OLae" width="3.368" height="3.468" x="9.699" y="8.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="iZripdd" width="3.218" height="3.468" x="19.212" y="8.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="iTq0Y1c" width="3.148" height="3.148" x="19.247" y="8.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".25"/></filter><filter id="inYFshb" width="2.948" height="2.948" x="9.853" y="9.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".2"/></filter><filter id="i2EOKWd" width="10.191" height="11.127" x="10.898" y="5.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="i3w4aiV" width="2.877" height="3.682" x="14.393" y="9.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".25"/></filter><filter id="i4Rvmyb" width="2.377" height="3.182" x="14.805" y="9.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".125"/></filter><filter id="itATmQb" width="3.702" height="1.526" x="14.142" y="12.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".05"/></filter><filter id="imAvk9U" width="3.001" height="1.285" x="16.936" y="9.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="iGMCOac" width="3.001" height="1.285" x="12.05" y="9.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="iVe6LCc" width="2.453" height="1.091" x="12.185" y="7.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="iQeF9Jb" width="2.453" height="1.091" x="17.602" y="7.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3333"/></filter><filter id="ibz83zd" width=".787" height=".696" x="17.441" y="9.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".05"/></filter><filter id="iNhJGXc" width=".891" height=".913" x="18.281" y="9.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".1"/></filter><filter id="iVciPfe" width=".986" height="1.04" x="13.838" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".1"/></filter><filter id="ibg7BHe" width=".913" height=".705" x="13.083" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".05"/></filter><filter id="iBY6FNG" width="2.261" height=".978" x="17.633" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".1"/></filter><filter id="iCoHh0c" width="2.261" height=".978" x="12.181" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".1"/></filter><filter id="i1daZhb" width="4.287" height="5.25" x="9.734" y="3.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".25"/></filter><filter id="imUSSAc" width="8.914" height="5.78" x="12.676" y="2.481" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".125"/></filter><filter id="iDpGoqd" width="1.145" height="2.31" x="12.802" y="3.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3333" stdDeviation=".1"/></filter><linearGradient id="iC4Tsjb" x1="20.687" x2="13.882" y1="3.603" y2="16.207" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iuyr1tn" x1="23.131" x2="22.971" y1="29.966" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iwTkvTT" x1="8.858" x2="9.061" y1="29.966" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="irRAuOe" x1="9.19" x2="7.596" y1="29.973" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="iQD9ace" x1="14.707" x2="12.794" y1="19.947" y2="16.473" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="ig0Fqhd" x1="15.518" x2="15.198" y1="20.04" y2="19.939" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="i3hbZ4w" x1="16.798" x2="18.955" y1="19.966" y2="16.867" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="i1L7Mpd" x1="16.486" x2="16.722" y1="19.727" y2="19.649" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="i6XAUBd" x1="12.815" x2="12.815" y1="16.834" y2="29.479" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="ilOIclb" x1="17.576" x2="14.433" y1="18.506" y2="18.124" gradientUnits="userSpaceOnUse"><stop class="wiue_0f-j"/><stop offset="1" class="s9a27_beb"/></linearGradient><linearGradient id="isKdouB" x1="15.205" x2="14.838" y1="19.49" y2="19.037" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="if4vDlY" x1="8.894" x2="23.27" y1="15.42" y2="15.42" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iZ5HQbe" x1="8.894" x2="23.27" y1="15.39" y2="15.39" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iaxIJrb" x1="9.699" x2="12.658" y1="10.642" y2="10.642" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iAtxlPe" x1="14.947" x2="15.801" y1="11.831" y2="11.935" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="i25jbue" x1="15.993" x2="15.993" y1="12.685" y2="12.075" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="i2PyylL" x1="15.264" x2="15.717" y1="14.162" y2="13.29" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="i5hXDwe" x1="18.953" x2="18.64" y1="10.012" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFGHLod" x1="14.555" x2="14.241" y1="10.012" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLn3WkG" x1="13.102" x2="13.647" y1="4.357" y2="5.631" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-tuxedo-medium-light" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.a6wyg-bez {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.112 9.67c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.axutl7beo {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.136 9.986c.265-.467.668-.835 1.537-.835c.38 0 .747.105 1.073.368c.269.218.233.495.024.6l-.556.317c-.652-.21-1.372-.24-2.078-.45");
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bchzmi1so {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.384 9.21c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.34H17.24a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.be6j1sb0b {
  d: path("M15.39 2.765c-1.133-.25-2.347.955-2.464 1.374c1.542 3.62 3.91 3.275 6.537 2.983c1.573-.174 1.743.542 1.877.889c-.436-4.056-3.369-4.677-5.95-5.246");
}

.bv7-wxb3q {
  d: path("M8.901 18.29a10.68 10.68 0 0 0-3.831 8.18v3.496H8.9z");
}

.c047y6t2e {
  d: path("M11.327 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.cqetd1bxd {
  stop-color: var(--svg-color--cb9187, #CB9187);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d0ocvmu4d {
  d: path("M17.598 20.338c1.186-1.235 1.368-4.254 1.368-4.254c-.681-.36-1.548-.406-1.548-.406l-1.421.789l-.036 2.222l.774 1.52c.148.308.608.394.863.129");
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d60lbkuym {
  d: path("M11.242 18.4c-.03-1.01.55-1.42.819-1.501l.617-.065v5.372c0 3.575.239 4.663 2.733 7.12l.011.016c.047.082-.05.176-.132.12c-2.75-1.881-4.776-3.355-5.094-8.18a.19.19 0 0 1 .174-.198c.297-.02.56-.044.747-.061a.19.19 0 0 0 .171-.191c-.01-.531-.02-1.533-.046-2.431");
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.dc_z0_bxw {
  d: path("M16.104 15.39h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dj5l2yqzg {
  d: path("M11.709 17.604c0-1.278.933-1.774 1.554-1.618v5.737c0 3.873 1.453 6.262 2.712 8.087c.063.091-.047.201-.138.139c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.048.808-.066c.107-.01.188-.1.186-.207c-.011-.574-.023-1.658-.05-2.631");
}

.dkhaswb9x {
  d: path("m10.908 9.027l-.01-.306c.02-.949.574-1.316.81-1.439q.025-.008.051-.02l.052-.02A2.3 2.3 0 0 0 13 6.007l.081-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.081.088 1.135 1.333l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.dnyi2nbwd {
  fill: var(--svg-color--000, #000);
  d: path("M17.666 10.374a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.dohjyt8kz {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.82 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
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

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.ecnu8434e {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.933 8.183c.323-.079 1.125-.04 1.66.344");
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.ene-v8epk {
  fill-rule: evenodd;
  d: path("M23.179 11.965a3.25 3.25 0 0 0 .323-1.427a3.3 3.3 0 0 0-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.004a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.003.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.895-4.625a.52.52 0 0 1 0-.455m-12.26-2.672h-.013l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.46.051L13 6.007a2.3 2.3 0 0 1-1.24 1.255l-.052.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.epgmjx2er {
  width: 3.875px;
  height: 6.133px;
  x: 14.075px;
  y: 12.709px;
  rx: 1.938px;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.f76qgd9qn {
  d: path("M20.82 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.f7xereb4t {
  stop-color: var(--svg-color--b57376, #B57376);
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g0235lowf {
  stop-color: var(--svg-color--d4a694, #D4A694);
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gxm-dc6uw {
  stop-color: var(--svg-color--a46e69, #A46E69);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hlpsh0pka {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M15.994 13.467c-.521 0-1.01-.126-1.422-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345");
}

.hmh19xb-g {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 10.374a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hyrjkgb1x {
  cx: 13.54px;
  cy: 9.862px;
  rx: 0.39px;
  ry: 0.197px;
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.ikym1vb8z {
  d: path("M18.112 9.67c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.ir2ky6n1g {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.142 8.183c-.323-.079-1.125-.04-1.66.344");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iwijhb8cc {
  d: path("M5.07 26.47c0-5.796 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.824 10.5 10.62v3.496H5.07z");
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jeah4dbrk {
  d: path("M11.308 12.164a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.ki1lu3bjf {
  stop-color: var(--svg-color--b57376, #B57376);
  stop-opacity: 0;
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
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

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ku2lh6uuy {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.535l1.813 1.252l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.ku5k7n3yy {
  stop-color: var(--svg-color--dfa496, #DFA496);
}

.l24ppp87r {
  d: path("M14.625 10.269c0-.289-.235-.481-.298-.54l-.289.28l.178.36z");
}

.l6bu9wb8i {
  d: path("M18.177 9.481a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lcsuusbll {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m19.725 8.32l-.138.23za.268.268 0 0 1-.276.46l-.004-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .559.238l.01.005l.002.002z");
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmkyvq38o {
  d: path("M16.434 15.39c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbqyinbph {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.611 10.194l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mmwou_i8u {
  d: path("M10.906 9.292h.013l-.01-.265l-.01-.306c.02-.949.573-1.316.81-1.439q.024-.008.05-.02l.052-.02A2.3 2.3 0 0 0 13 6.007l.081-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.081.088 1.135 1.333l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvlg1lb-a {
  cx: 15.731px;
  cy: 25.909px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.n0hytgbgy {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.596 8.777l-.005.003a.268.268 0 0 1-.275-.46l.001-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.11a.268.268 0 1 1-.093.53a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.455.193");
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.nzd5pi4db {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.741c-.037.825.18 2.636 1.367 3.871c.255.266.715.18.863-.129l.73-1.435l.731 1.435c.149.309.608.395.863.13c1.186-1.236 1.404-3.047 1.368-3.872z");
}

.o-ok2ibcd {
  d: path("m17.892 17.535l-1.813 1.252l1.795 1.258a.246.246 0 0 0 .388-.187c.041-.791.041-1.57.008-2.144a.239.239 0 0 0-.378-.179");
}

.o8km552wm {
  stop-color: var(--svg-color--bd8478, #BD8478);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of-5eykok {
  stop-color: var(--svg-color--dfa496, #DFA496);
  stop-opacity: 0;
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.omj93bweh {
  d: path("m15.611 10.194l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pbpjm1bhy {
  d: path("m14.133 17.535l1.813 1.252l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.pifmjgb7d {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.327 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn527rb9i {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.994 13.467c-.521 0-1.01-.126-1.422-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345Z");
}

.prstl2fga {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.602 9.21c-.653 0-1.204.45-1.354 1.058a.273.273 0 0 0 .267.34h2.231a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pwzf73bct {
  d: path("M14.41 20.338c-1.185-1.235-1.367-4.254-1.367-4.254c.681-.36 1.548-.406 1.548-.406l1.421.789l.035 2.222l-.773 1.52c-.148.308-.608.394-.863.129");
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qeue4_bux {
  d: path("M18.972 10.256a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qjruynb1t {
  d: path("M13.81 9.481a.892.892 0 0 0-.86 1.128h1.723a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qsy44ybab {
  cx: 16.004px;
  cy: 25.636px;
  r: 0.5px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.rpm4ycxof {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.6 10.333l-.683 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.494-.376-.613 0");
}

.rr_xtkbqp {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.852 9.986c-.266-.467-.67-.835-1.538-.835c-.38 0-.747.105-1.073.368c-.268.218-.232.495-.024.6l.556.317c.652-.21 1.372-.24 2.079-.45");
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.s9a27_beb {
  stop-color: var(--svg-color--b87972, #B87972);
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.t071f0bxb {
  d: path("M11.1 4.541c.62-.553 1.516-.559 2.019-.47l.402 1.291c-.257-.039-.486.05-.679.235c-.452 1.676-2.162 1.425-2.497 2.682c-.151-1.492-.319-2.782.754-3.738");
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.t3_bfrc1u {
  stop-color: var(--svg-color--b97c86, #B97C86);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tao08pzef {
  cx: 15.731px;
  cy: 22.761px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.ud62v449c {
  cx: 13.54px;
  cy: 9.862px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.uoh3u9bsv {
  d: path("M8.901 18.29a10.69 10.69 0 0 0-3.831 8.185v3.498H8.9z");
}

.uqyvgzkbv {
  d: path("M20.82 12.164a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vnj0svbtx {
  stop-color: var(--svg-color--d4a694, #D4A694);
  stop-opacity: 0;
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w6batdbtw {
  stop-color: var(--svg-color--bd8478, #BD8478);
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wga2pr3ix {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.332 17.604c0-1.278-.933-1.774-1.555-1.618v5.737c0 3.873-1.452 6.262-2.711 8.087c-.063.091.047.201.138.139c2.976-2.036 4.915-4.003 5.26-9.226a.203.203 0 0 0-.188-.215c-.321-.02-.606-.048-.809-.066a.204.204 0 0 1-.185-.207c.011-.574.023-1.658.05-2.631");
}

.wiue_0f-j {
  stop-color: var(--svg-color--c58d85, #C58D85);
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wsuqc2bol {
  d: path("M18.767 16.117a10.3 10.3 0 0 0-2.337-.267h-.86a10.3 10.3 0 0 0-2.312.261v5.423c0 4.175 1.065 5.971 2.654 8.432h.285c1.59-2.46 2.57-4.257 2.57-8.432z");
}

.wui8nqfgb {
  cx: 16.012px;
  cy: 18.756px;
  r: 0.809px;
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x69bombgk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.102 4.013c.024.243.235 1.157.545 1.71");
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z77pc-39f {
  d: path("M23.099 18.29a10.68 10.68 0 0 1 3.831 8.18v3.496H23.1z");
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zgcak206m {
  cx: 16.004px;
  cy: 22.628px;
  r: 0.5px;
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
