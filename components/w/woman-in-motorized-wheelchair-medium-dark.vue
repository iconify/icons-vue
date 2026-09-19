<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3jfkvf)" class="n68u5luyx"/><path fill="url(#i21iV8d)" class="n68u5luyx"/><path class="xy0warxtb"/><path fill="url(#izOYdMc)" class="wfgkivb4m"/><path fill="url(#i11S1ic)" class="wfgkivb4m"/><path fill="url(#ifG8Jkc)" class="wfgkivb4m"/><path fill="url(#iHpj0ze)" class="wfgkivb4m"/><g filter="url(#iREepCc)"><path fill="url(#i2L03NG)" class="opuqn1hcz"/><path fill="url(#iG895Qd)" class="opuqn1hcz"/><path fill="url(#i6ZgNIb)" class="opuqn1hcz"/><path fill="url(#imkIxSc)" class="opuqn1hcz"/></g><path class="rjbedibdc"/><path fill="url(#iQp8VDb)" class="xix9lmpxe"/><path fill="url(#itwQAob)" class="xix9lmpxe"/><path fill="url(#iz4ydhe)" class="xix9lmpxe"/><path fill="url(#iBMFUtd)" class="eiyzwdbvn"/><path fill="url(#iE52mHd)" class="zz5qicf0f"/><path fill="url(#ieLCPkc)" class="tq5ps4b3l"/><g filter="url(#ieGyQCc)"><path clip-rule="evenodd" class="ac72u6bzq"/><path fill="url(#iwWVxZb)" clip-rule="evenodd" class="wtnucq2vy"/></g><g filter="url(#i2z82qQ)"><path stroke="url(#iTm2GNt)" class="c0w9skb7x"/></g><circle fill="url(#ictfY7b)" class="dvsjoj0vs"/><circle fill="url(#iE1cxDc)" class="dvsjoj0vs"/><circle fill="url(#i7rF0Ub)" class="dvsjoj0vs"/><circle class="gruyj9uct"/><circle fill="url(#i94QvBv)" class="tkes6b_0a"/><circle fill="url(#i6yJGLe)" class="tkes6b_0a"/><g filter="url(#ieYjjlv)"><path fill="url(#ij0EDle)" class="fqlyqbbmu"/><path fill="url(#iTWJYMc)" class="fqlyqbbmu"/><path fill="url(#i7rvU4b)" class="fqlyqbbmu"/></g><g filter="url(#ivelpgc)"><path class="rc1jpzb3f"/><path fill="url(#igQ3goc)" class="xhqab6xhy"/></g><path class="gfg94vbiy"/><path fill="url(#i6x3Myb)" class="c-vkptb2l"/><path fill="url(#ighlmjb)" class="c-vkptb2l"/><path fill="url(#iupeVHe)" class="c-vkptb2l"/><path fill="url(#i4bdPze)" class="c-vkptb2l"/><path fill="url(#ilUajzd)" class="c-vkptb2l"/><rect fill="url(#iM60PRd)" transform="rotate(9.205 23.614 6.624)" class="mzi2avtdm"/><rect fill="url(#iuoZMjc)" transform="rotate(9.205 23.614 6.624)" class="mzi2avtdm"/><path fill="url(#iShpo0d)" class="pxendyjut"/><path fill="url(#ifY3bjd)" class="pxendyjut"/><path fill="url(#iRSbRob)" class="bdzq53b4f"/><g filter="url(#iWa3r9c)"><path fill="url(#iZM0VGd)" class="r62w_lejb"/><path fill="url(#ihuw2zi)" class="r62w_lejb"/><path fill="url(#ivtXAgc)" class="r62w_lejb"/><path fill="url(#iAakM9d)" class="r62w_lejb"/></g><g filter="url(#iq9Ybbb)"><path class="d_35etgbw"/><path fill="url(#iybETdd)" class="gc1c4bbqk"/></g><path fill="url(#i6SlOBc)" class="gc1c4bbqk"/><path fill="url(#iBoGa2d)" class="c10_-52hz"/><path fill="url(#infnPpc)" class="c10_-52hz"/><path fill="url(#iqU6S4b)" class="c10_-52hz"/><path clip-rule="evenodd" class="mdia87ptp"/><g filter="url(#i7i48we)"><path clip-rule="evenodd" class="on-6a1tha"/></g><path class="j0o3mob8g"/><path class="jifg9fbqa"/><path fill="url(#iXYyjeb)" class="w24n_ub5p"/><path fill="url(#in67lwb)" class="hqbc8kbno"/><ellipse fill="url(#ibNW15b)" transform="rotate(30.848 18.315 5.145)" class="svvwe7bhc"/><g filter="url(#iTSTKwe)"><path class="gh1dv7p4f"/><path fill="url(#igERG6d)" class="vtqj02myp"/><path fill="url(#iOHeogx)" class="vtqj02myp"/></g><path fill="url(#iYn5tXc)" class="vtqj02myp"/><g filter="url(#irY4BYc)"><rect class="k7-xlwbtv"/><rect fill="url(#i2YgYqc)" class="r7q-w8bhi"/><rect fill="url(#iSjR8uc)" class="r7q-w8bhi"/></g><rect fill="url(#ihiu4ob)" class="r7q-w8bhi"/><g filter="url(#itvdo5d)"><path fill="url(#iYxH4Zd)" class="axy0hcb7a"/></g><path fill="url(#iYwf10c)" class="axy0hcb7a"/><circle class="cmnvd12ya"/><g filter="url(#ilRZ12c)"><circle class="riz6vyb_j"/></g><circle fill="url(#icukdlb)" class="z3g8mdthr"/><circle fill="url(#iUpHD1b)" class="bsb9ukbke"/><circle fill="url(#ixg6Tqb)" class="p29rc0b5o"/><g filter="url(#ix7sxgR)"><path clip-rule="evenodd" class="kk9p30bku"/></g><path fill="url(#ihapdFd)" clip-rule="evenodd" class="yo3u-ub4s"/><g filter="url(#iorH88b)"><circle class="q-5444bwf"/></g><g filter="url(#icfLBPd)"><circle class="fon7meb-r"/></g><g filter="url(#iDitM5d)"><path fill="url(#iS4LLpF)" class="zcevvihat"/></g><path fill="url(#iTTORye)" class="zcevvihat"/><path fill="url(#ifVQJZd)" class="zcevvihat"/><circle fill="url(#ikKVuDd)" class="d5xoocd9m"/><g filter="url(#irNAwCd)"><path clip-rule="evenodd" class="i_2-mnb6b"/></g><g filter="url(#iEORZdb)"><path stroke="url(#iwpMF3d)" clip-rule="evenodd" class="r8d-hgb6b"/></g><g filter="url(#i4kkxhD)"><path stroke="url(#iITRRib)" clip-rule="evenodd" class="mzqppqgkg"/></g><g filter="url(#iBJIKAd)"><path class="zrt30_2yc"/></g><g filter="url(#ikqBzgb)"><path stroke="url(#isShNQd)" clip-rule="evenodd" class="zcp15fbad"/></g><g filter="url(#iFVC4Nc)"><circle class="tsh4uysfx"/></g><g filter="url(#ioCKqJb)"><path class="eu9d2ynfb"/></g><g filter="url(#i7kbG1c)"><path class="xdztpacdw"/><path fill="url(#im0wsMe)" class="jp6shsbzj"/></g><g filter="url(#iHQxJBe)"><path class="t2wsg-6mb"/></g><g filter="url(#iqIckAb)"><path class="rf3kejb9c"/></g><path class="u4sz8cc_m"/><path fill="url(#iQVeewc)" class="lsbd06pgn"/><path fill="url(#ipH9Z3h)" class="lsbd06pgn"/><path fill="url(#i6ApPrd)" class="lsbd06pgn"/><path fill="url(#iLpoUpb)" class="lsbd06pgn"/><path fill="url(#isVxtJe)" class="lsbd06pgn"/><g filter="url(#iYheabb)"><path fill="url(#iztAShe)" class="vbsma9b6v"/></g><g filter="url(#idWs3ed)"><path class="eohpzzbti"/><path fill="url(#iUKitBR)" class="w_hnjyb9a"/><path fill="url(#iMsuF2c)" class="w_hnjyb9a"/></g><g filter="url(#iJnPt3d)"><path stroke="url(#iGmuN4c)" class="ppzv89b4g"/></g><defs><radialGradient id="i3jfkvf" cx="0" cy="0" r="1" gradientTransform="rotate(-35.373 24.929 -25.018)scale(2.11331 2.161)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="c5y0hmb-o"/><stop offset="1" class="fkvlxj0pp"/></radialGradient><radialGradient id="izOYdMc" cx="0" cy="0" r="1" gradientTransform="matrix(.86682 -4.84514 8.4494 1.51164 19.346 13.3)" gradientUnits="userSpaceOnUse"><stop offset=".829" class="a-iuprblf"/><stop offset="1" class="o_3_trjap"/></radialGradient><radialGradient id="i11S1ic" cx="0" cy="0" r="1" gradientTransform="matrix(4.625 4.75001 -5.30938 5.16964 16.085 9.489)" gradientUnits="userSpaceOnUse"><stop offset=".367" class="tgn2_cbqk"/><stop offset="1" class="d5v58yb6h"/></radialGradient><radialGradient id="iHpj0ze" cx="0" cy="0" r="1" gradientTransform="rotate(169.951 10.617 5.916)scale(1.29942 2.83119)" gradientUnits="userSpaceOnUse"><stop class="r9oq2bbva"/><stop offset="1" class="obuzyxb5s"/></radialGradient><radialGradient id="iG895Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 -1 2.95172 -6.27244 12.147 21.801)" gradientUnits="userSpaceOnUse"><stop class="jzl720bvd"/><stop offset="1" class="zdh48sb9s"/></radialGradient><radialGradient id="i6ZgNIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40625 6.4375 0 18.647 18.082)" gradientUnits="userSpaceOnUse"><stop class="d9q4mwzxt"/><stop offset="1" class="kegmapbvr"/></radialGradient><radialGradient id="imkIxSc" cx="0" cy="0" r="1" gradientTransform="rotate(11.535 -92.723 56.205)scale(1.56281 6.59576)" gradientUnits="userSpaceOnUse"><stop class="d0phtb81o"/><stop class="d0phtb81o"/><stop offset="1" class="hwvatcc-y"/></radialGradient><radialGradient id="iQp8VDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11941 -1.8243 6.0381 -.39524 8.366 24.801)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="ie8_agh2b"/><stop offset="1" class="gzc_qccoq"/></radialGradient><radialGradient id="iz4ydhe" cx="0" cy="0" r="1" gradientTransform="matrix(1.64063 -.01563 .00576 .60488 6.07 23.723)" gradientUnits="userSpaceOnUse"><stop class="u9mcm6llv"/><stop offset="1" class="b-3vnvcpj"/></radialGradient><radialGradient id="iwWVxZb" cx="0" cy="0" r="1" gradientTransform="matrix(1.01563 .01563 -.03485 2.26557 5.557 23.957)" gradientUnits="userSpaceOnUse"><stop class="ihz8r9bpq"/><stop offset="1" class="cabiwub4i"/></radialGradient><radialGradient id="ictfY7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.80087 -.53995 .5353 -.79397 15.588 16.714)" gradientUnits="userSpaceOnUse"><stop class="id6hb3b7i"/><stop offset="1" class="nbyzmw_ck"/></radialGradient><radialGradient id="iE1cxDc" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 -.33594 .30415 .24757 15.494 16.418)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="z1-difb5b"/><stop offset="1" class="yxnjz7r7g"/></radialGradient><radialGradient id="i7rF0Ub" cx="0" cy="0" r="1" gradientTransform="matrix(.18962 -.81468 .57531 .1339 14.418 16.865)" gradientUnits="userSpaceOnUse"><stop class="mcd03_b4y"/><stop offset="1" class="e14bc-vgp"/></radialGradient><radialGradient id="i94QvBv" cx="0" cy="0" r="1" gradientTransform="rotate(65.376 -3.83 19.27)scale(.41251)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="ipohnfkvg"/><stop offset="1" class="aur13kbnc"/></radialGradient><radialGradient id="i6yJGLe" cx="0" cy="0" r="1" gradientTransform="matrix(.41406 -.125 .14254 .47215 14.744 15.09)" gradientUnits="userSpaceOnUse"><stop class="clzavdftr"/><stop offset="1" class="w07b1tb5i"/></radialGradient><radialGradient id="iTWJYMc" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.28126 .36059 .90144 10.98 25.958)" gradientUnits="userSpaceOnUse"><stop class="b9iguid0k"/><stop offset="1" class="rfxr5lvvz"/></radialGradient><radialGradient id="iuoZMjc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.544 16.182 -7.89)scale(1.19329 .67738)" gradientUnits="userSpaceOnUse"><stop class="bcaxkqjfb"/><stop offset="1" class="kh4so6bgt"/></radialGradient><radialGradient id="iShpo0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.16406 -2.98016 0 18.6 20.863)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="yu1mih4mu"/><stop offset="1" class="eu5aevb0y"/></radialGradient><radialGradient id="ifY3bjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.36328 -3.72499 0 18.6 21.39)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="cvn34-xwu"/><stop offset=".771" class="i8rkxoa5u"/></radialGradient><radialGradient id="iRSbRob" cx="0" cy="0" r="1" gradientTransform="matrix(.41534 .29189 -.41616 .59218 17.125 5.869)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="n304-r4kd"/><stop offset=".684" class="uk3jx7nau"/></radialGradient><radialGradient id="ihuw2zi" cx="0" cy="0" r="1" gradientTransform="matrix(-.7585 -.12581 .15339 -.92475 20.52 5.62)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="jijo4-b9s"/><stop offset="1" class="ni_rkbnps"/></radialGradient><radialGradient id="ivtXAgc" cx="0" cy="0" r="1" gradientTransform="matrix(.51286 -4.69181 1.27187 .13903 17.783 6.408)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="dd9hd6bwg"/><stop offset="1" class="aw2d6h33n"/></radialGradient><radialGradient id="iAakM9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.03862 .3533 -.55098 -.06023 18.645 5.458)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="jynvl5b3k"/><stop offset="1" class="b-jom1b0d"/></radialGradient><radialGradient id="iybETdd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4309 -.2387 .51151 3.06639 17.916 3.29)" gradientUnits="userSpaceOnUse"><stop class="y_bf1qbke"/><stop offset="1" class="e8kph3xgf"/></radialGradient><radialGradient id="i6SlOBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59374 -.12501 .27543 -3.51148 23.025 5.684)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="xo67nobiw"/><stop offset="1" class="or7cc4f6p"/></radialGradient><radialGradient id="iBoGa2d" cx="0" cy="0" r="1" gradientTransform="matrix(.67799 -.11895 .05806 .33092 20.24 5.483)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="infnPpc" cx="0" cy="0" r="1" gradientTransform="rotate(85.395 7.324 13.606)scale(1.09288 1.13883)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="iXYyjeb" cx="0" cy="0" r="1" gradientTransform="matrix(.24702 .02704 -.05253 .47991 18.402 5.46)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="in67lwb" cx="0" cy="0" r="1" gradientTransform="matrix(.22611 .02472 -.05349 .48932 18.222 5.457)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iOHeogx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10465 .77326 -.66363 -.94804 24.785 9.077)" gradientUnits="userSpaceOnUse"><stop class="t_w7gbbck"/><stop offset="1" class="pbwt4gb4m"/></radialGradient><radialGradient id="iYn5tXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0138 .77326 -2.388 -.04264 22.147 16.326)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="seor_02fd"/><stop offset="1" class="cfhwg-9zy"/></radialGradient><radialGradient id="iYwf10c" cx="0" cy="0" r="1" gradientTransform="matrix(.64844 -.00781 .01612 1.33804 17.065 15.582)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="etx6bbf-f"/><stop offset="1" class="xbtn5acgm"/></radialGradient><radialGradient id="icukdlb" cx="0" cy="0" r="1" gradientTransform="matrix(1.71874 -1.8125 1.7735 1.68175 12.167 29.285)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="bu0v-9rgl"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iUpHD1b" cx="0" cy="0" r="1" gradientTransform="rotate(-49.87 37.33 .962)scale(1.46152 1.87048)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="ixg6Tqb" cx="0" cy="0" r="1" gradientTransform="rotate(-49.87 43.158 -11.573)scale(1.46152 1.87048)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="ihapdFd" cx="0" cy="0" r="1" gradientTransform="rotate(-133.238 18.903 9.263)scale(2.87398 2.81213)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="bu0v-9rgl"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="ifVQJZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.625 3.92187 -.8118 -.12937 22.744 22.832)" gradientUnits="userSpaceOnUse"><stop class="th1brvxrz"/><stop offset="1" class="ux0of3-jj"/></radialGradient><radialGradient id="ikKVuDd" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 -1.89062 2.41965 2.03971 18.198 28.098)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="im0wsMe" cx="0" cy="0" r="1" gradientTransform="matrix(.13544 1.98754 -.87055 .05932 21.16 12.522)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="a3cmd2asj"/><stop offset="1" class="y3ztz7b1k"/></radialGradient><radialGradient id="iQVeewc" cx="0" cy="0" r="1" gradientTransform="matrix(.61593 -3.1794 1.00389 .19448 22.564 5.95)" gradientUnits="userSpaceOnUse"><stop class="fndizab4b"/><stop offset="1" class="hw8l16bxs"/></radialGradient><radialGradient id="iLpoUpb" cx="0" cy="0" r="1" gradientTransform="rotate(142.883 12.242 6.12)scale(1.45001 1.69112)" gradientUnits="userSpaceOnUse"><stop class="v4yb5cu8i"/><stop offset="1" class="ewip82vxi"/></radialGradient><radialGradient id="isVxtJe" cx="0" cy="0" r="1" gradientTransform="matrix(.14062 1.03125 -3.76156 .51293 23.823 2.754)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="i00c46bgu"/><stop offset="1" class="gb6cd3sju"/></radialGradient><radialGradient id="iMsuF2c" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 -3.43171 .7295 .06643 21.025 12.423)" gradientUnits="userSpaceOnUse"><stop class="w8fowerpf"/><stop offset="1" class="t0hm9_sih"/></radialGradient><radialGradient id="iGmuN4c" cx="0" cy="0" r="1" gradientTransform="rotate(-165.811 10.998 5.553)scale(3.50585 10.7045)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="f37qg-byx"/><stop offset="1" class="awbnnxqjj"/></radialGradient><linearGradient id="i21iV8d" x1="19.111" x2="20.079" y1="9.228" y2="9.263" gradientUnits="userSpaceOnUse"><stop class="dleg5vxtn"/><stop offset="1" class="o-5paobui"/><stop offset="1" class="yt_hl7yft"/></linearGradient><linearGradient id="ifG8Jkc" x1="21.07" x2="20.324" y1="16.945" y2="16.831" gradientUnits="userSpaceOnUse"><stop class="vdj-q1-ni"/><stop offset="1" class="rq851lrid"/></linearGradient><linearGradient id="i2L03NG" x1="17.96" x2="9.835" y1="16.832" y2="24.145" gradientUnits="userSpaceOnUse"><stop class="scqcqwblc"/><stop offset="1" class="j5-6p70xh"/></linearGradient><linearGradient id="itwQAob" x1="10.311" x2="9.132" y1="25.309" y2="24.692" gradientUnits="userSpaceOnUse"><stop class="wjw662jrg"/><stop offset="1" class="xkzs54_ul"/></linearGradient><linearGradient id="iBMFUtd" x1="14.823" x2="15.423" y1="15.636" y2="15.636" gradientUnits="userSpaceOnUse"><stop class="p8hc-w2ji"/><stop offset=".573" class="c76owwbvh"/></linearGradient><linearGradient id="iE52mHd" x1="24.659" x2="24.187" y1="27.004" y2="26.66" gradientUnits="userSpaceOnUse"><stop offset=".323" class="lzxtmdbfr"/><stop offset="1" class="ajt-21bdu"/></linearGradient><linearGradient id="ieLCPkc" x1="12.588" x2="13.049" y1="26.996" y2="26.746" gradientUnits="userSpaceOnUse"><stop offset=".385" class="lzxtmdbfr"/><stop offset="1" class="ajt-21bdu"/></linearGradient><linearGradient id="iTm2GNt" x1="6.252" x2="11.604" y1="24.176" y2="26.449" gradientUnits="userSpaceOnUse"><stop class="bq9mpqbzy"/><stop offset="1" class="ka6kobc6f"/></linearGradient><linearGradient id="ij0EDle" x1="11.495" x2="14.151" y1="26.582" y2="24.676" gradientUnits="userSpaceOnUse"><stop class="f6z4yi_ag"/><stop offset="1" class="cu9n-vbgf"/></linearGradient><linearGradient id="i7rvU4b" x1="12.791" x2="12.963" y1="24.207" y2="24.676" gradientUnits="userSpaceOnUse"><stop class="ybejupycn"/><stop offset="1" class="o7v7nujms"/></linearGradient><linearGradient id="igQ3goc" x1="24.776" x2="24.276" y1="24.176" y2="25.076" gradientUnits="userSpaceOnUse"><stop class="hlkhhwb3q"/><stop offset="1" class="b37qgpujw"/></linearGradient><linearGradient id="i6x3Myb" x1="15.219" x2="15.219" y1="16.783" y2="17.443" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05dlfbsr"/><stop offset="1" class="uevlegbhj"/></linearGradient><linearGradient id="ighlmjb" x1="13.944" x2="15.024" y1="17.896" y2="17.896" gradientUnits="userSpaceOnUse"><stop offset=".326" class="mykl6fbtk"/><stop offset="1" class="uevlegbhj"/></linearGradient><linearGradient id="iupeVHe" x1="16.493" x2="15.675" y1="18.103" y2="18.103" gradientUnits="userSpaceOnUse"><stop class="jsdt5e8xl"/><stop offset="1" class="erpm-ebho"/></linearGradient><linearGradient id="i4bdPze" x1="16.493" x2="16.206" y1="18.103" y2="18.103" gradientUnits="userSpaceOnUse"><stop class="gxhbeh9zc"/><stop offset="1" class="t07ov5bcy"/></linearGradient><linearGradient id="ilUajzd" x1="13.944" x2="14.236" y1="17.845" y2="17.845" gradientUnits="userSpaceOnUse"><stop class="xs80ogben"/><stop offset="1" class="snka5sm3m"/></linearGradient><linearGradient id="iM60PRd" x1="23.911" x2="23.901" y1="7.056" y2="8.261" gradientUnits="userSpaceOnUse"><stop class="ronnvab4v"/><stop offset="1" class="dt2-hrbth"/></linearGradient><linearGradient id="iZM0VGd" x1="20.164" x2="17.559" y1="6.261" y2="6.133" gradientUnits="userSpaceOnUse"><stop class="vloggvbag"/><stop offset="1" class="bvwuwdbuv"/></linearGradient><linearGradient id="iqU6S4b" x1="20.145" x2="20.392" y1="5.504" y2="5.603" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="ibNW15b" x1="18.25" x2="18.419" y1="5.11" y2="5.165" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="igERG6d" x1="23.928" x2="22.216" y1="17.334" y2="17.169" gradientUnits="userSpaceOnUse"><stop offset=".357" class="ejmms-frd"/><stop offset="1" class="bd5h7cqqn"/></linearGradient><linearGradient id="i2YgYqc" x1="18.651" x2="18.651" y1="18.332" y2="19.332" gradientUnits="userSpaceOnUse"><stop offset=".219" class="jqu95-b8t"/><stop offset="1" class="vt606lu7d"/></linearGradient><linearGradient id="iSjR8uc" x1="24.573" x2="23.276" y1="19.522" y2="19.522" gradientUnits="userSpaceOnUse"><stop class="e9_lu_tkl"/><stop offset="1" class="ms0rob30e"/></linearGradient><linearGradient id="ihiu4ob" x1="12.729" x2="13.245" y1="19.652" y2="19.652" gradientUnits="userSpaceOnUse"><stop offset=".255" class="aafld1b5m"/><stop offset="1" class="t9qy5zbtq"/></linearGradient><linearGradient id="iYxH4Zd" x1="20.565" x2="20.565" y1="15.022" y2="16.49" gradientUnits="userSpaceOnUse"><stop offset=".116" class="k8klmcqbt"/><stop offset="1" class="t8rqipb-o"/></linearGradient><linearGradient id="iS4LLpF" x1="18.588" x2="18.588" y1="21.91" y2="27.707" gradientUnits="userSpaceOnUse"><stop class="ebki_vbdj"/><stop offset=".752" class="w_fjow9gn"/></linearGradient><linearGradient id="iTTORye" x1="14.244" x2="15.244" y1="25.551" y2="25.457" gradientUnits="userSpaceOnUse"><stop class="golah4bmm"/><stop offset="1" class="nhtvs4bus"/></linearGradient><linearGradient id="iwpMF3d" x1="20.205" x2="17.023" y1="25.716" y2="28.852" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset=".37" class="hxfvufi0i"/><stop offset=".778" class="hxfvufi0i"/><stop offset="1" class="bqaby2bzq"/></linearGradient><linearGradient id="iITRRib" x1="25.351" x2="23.553" y1="27.526" y2="29.298" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset=".37" class="hxfvufi0i"/><stop offset=".778" class="hxfvufi0i"/><stop offset="1" class="bqaby2bzq"/></linearGradient><linearGradient id="isShNQd" x1="11.501" x2="12.985" y1="28.91" y2="27.473" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset="1" class="hxfvufi0i"/></linearGradient><linearGradient id="ipH9Z3h" x1="25.573" x2="24.369" y1="6.02" y2="5.785" gradientUnits="userSpaceOnUse"><stop class="sputfhdoz"/><stop offset="1" class="x91xhsboa"/></linearGradient><linearGradient id="i6ApPrd" x1="23.807" x2="23.994" y1="7.107" y2="5.832" gradientUnits="userSpaceOnUse"><stop class="zeqefbvfd"/><stop offset="1" class="aetcf802l"/></linearGradient><linearGradient id="iztAShe" x1="10.022" x2="14.772" y1="23.051" y2="14.645" gradientUnits="userSpaceOnUse"><stop offset=".047" class="x9-imyafb"/><stop offset="1" class="uu4nvia_s"/></linearGradient><linearGradient id="iUKitBR" x1="19.403" x2="20.166" y1="11.439" y2="11.517" gradientUnits="userSpaceOnUse"><stop offset=".184" class="ph_duzi0t"/><stop offset="1" class="scmywnb8q"/></linearGradient><filter id="iREepCc" width="15.582" height="10.819" x="5.713" y="14.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.223529 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="ieGyQCc" width="6.441" height="2.956" x="5.508" y="23.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.133333 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.14902 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_393" result="effect2_innerShadow_4002_393"/></filter><filter id="i2z82qQ" width="5.567" height="2.356" x="5.933" y="23.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_393" stdDeviation=".075"/></filter><filter id="ieYjjlv" width="4.441" height="3.418" x="10.858" y="23.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.109804 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="ivelpgc" width="4.535" height="3.468" x="21.807" y="23.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.145098 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="iWa3r9c" width="4.276" height="4.88" x="17.352" y="3.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="iq9Ybbb" width="5.818" height="7.141" x="17.335" y="1.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0588235 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_393" result="effect2_innerShadow_4002_393"/></filter><filter id="i7i48we" width=".91" height=".581" x="18.256" y="4.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="iTSTKwe" width="4.718" height="10.273" x="20.506" y="8.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="irY4BYc" width="11.844" height="3.289" x="12.729" y="17.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.133333 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.184314 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_393" result="effect2_innerShadow_4002_393"/></filter><filter id="itvdo5d" width="7.15" height="1.822" x="17.065" y="14.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.137255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="ilRZ12c" width="3.042" height="3.242" x="11.275" y="26.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_393" result="effect2_innerShadow_4002_393"/></filter><filter id="ix7sxgR" width="3.042" height="3.242" x="22.932" y="26.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_393" result="effect2_innerShadow_4002_393"/></filter><filter id="iorH88b" width=".953" height=".953" x="12.295" y="28.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_393" result="effect2_innerShadow_4002_393"/></filter><filter id="icfLBPd" width=".953" height=".953" x="23.951" y="28.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_393" result="effect2_innerShadow_4002_393"/></filter><filter id="iDitM5d" width="9.072" height="5.925" x="14.052" y="21.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.0392157 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="irNAwCd" width="5.213" height="5.612" x="16.068" y="24.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_393" result="effect2_innerShadow_4002_393"/></filter><filter id="iEORZdb" width="4.858" height="4.858" x="16.271" y="24.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_393" stdDeviation=".125"/></filter><filter id="i4kkxhD" width="2.743" height="2.743" x="23.129" y="27.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_393" stdDeviation=".075"/></filter><filter id="iBJIKAd" width="4.351" height="5.782" x="18.123" y="8.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_393" stdDeviation=".5"/></filter><filter id="ikqBzgb" width="2.743" height="2.743" x="11.4" y="27.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_393" stdDeviation=".075"/></filter><filter id="iFVC4Nc" width="1.474" height="1.474" x="17.863" y="26.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_393" result="effect2_innerShadow_4002_393"/></filter><filter id="ioCKqJb" width="7.234" height="2.726" x="14.177" y="12.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.423529 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="i7kbG1c" width="7.434" height="2.926" x="14.177" y="12.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.219608 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_393" result="effect2_innerShadow_4002_393"/></filter><filter id="iHQxJBe" width="1.884" height="1.437" x="13.714" y="13.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.290196 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="iqIckAb" width="1.948" height="1.321" x="14.102" y="13.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.290196 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="iYheabb" width="5.063" height="8.469" x="9.179" y="15.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_393" stdDeviation=".25"/></filter><filter id="idWs3ed" width="2.651" height="3.782" x="19.103" y="8.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.192157 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_393"/></filter><filter id="iJnPt3d" width="4.206" height="1.8" x="16.491" y="12.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_393" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-motorized-wheelchair-medium-dark" /></template>
<style>
.a-iuprblf {
  stop-color: var(--svg-color--4e3870, #4E3870);
  stop-opacity: 0;
}

.a3cmd2asj {
  stop-color: var(--svg-color--906964, #906964);
}

.aafld1b5m {
  stop-color: var(--svg-color--64576e, #64576E);
}

.ac72u6bzq {
  fill: var(--svg-color--3b3349, #3B3349);
  fill-rule: evenodd;
  d: path("M5.697 23.862a.375.375 0 0 1 .502-.17l3.788 1.864l.01.003h1.427a.375.375 0 0 1 0 .75H9.998a.8.8 0 0 1-.343-.08l-3.787-1.865a.375.375 0 0 1-.171-.502");
}

.aetcf802l {
  stop-color: var(--svg-color--492f60, #492F60);
  stop-opacity: 0;
}

.ajt-21bdu {
  stop-color: var(--svg-color--3a183a, #3A183A);
}

.aur13kbnc {
  stop-color: var(--svg-color--5a4a71, #5A4A71);
  stop-opacity: 0;
}

.aw2d6h33n {
  stop-color: var(--svg-color--9a7468, #9A7468);
  stop-opacity: 0;
}

.awbnnxqjj {
  stop-color: var(--svg-color--7c5b5b, #7C5B5B);
  stop-opacity: 0;
}

.axy0hcb7a {
  d: path("M17.065 15.519a.7.7 0 0 1 .7-.7h6.3l-.274 1.671h-6.026a.7.7 0 0 1-.7-.7z");
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b-3vnvcpj {
  stop-color: var(--svg-color--565476, #565476);
  stop-opacity: 0;
}

.b-jom1b0d {
  stop-color: var(--svg-color--845a4e, #845A4E);
  stop-opacity: 0;
}

.b37qgpujw {
  stop-color: var(--svg-color--f24147, #F24147);
  stop-opacity: 0;
}

.b3dj2bied {
  stop-color: var(--svg-color--c7b9d7, #C7B9D7);
}

.b9iguid0k {
  stop-color: var(--svg-color--cc3437, #CC3437);
}

.bcaxkqjfb {
  stop-color: var(--svg-color--404047, #404047);
}

.bd5h7cqqn {
  stop-color: var(--svg-color--5a4a6a, #5A4A6A);
  stop-opacity: 0;
}

.bdzq53b4f {
  d: path("M17.436 5.502c.156-.117.247-.344.275-.424l.175.08l-.111 1.017c-.208.102-.496.02-.558-.175c-.053-.167.024-.351.219-.498");
}

.bq9mpqbzy {
  stop-color: var(--svg-color--474652, #474652);
}

.bqaby2bzq {
  stop-color: var(--svg-color--a09aa7, #A09AA7);
}

.bsb9ukbke {
  cx: 12.771px;
  cy: 28.524px;
  r: 0.894px;
}

.bu0v-9rgl {
  stop-color: var(--svg-color--776287, #776287);
  stop-opacity: 0;
}

.bvwuwdbuv {
  stop-color: var(--svg-color--7d5751, #7D5751);
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c-vkptb2l {
  d: path("M13.945 17.283a.5.5 0 0 1 .5-.5h1.548a.5.5 0 0 1 .5.5v.82h-2.548z");
}

.c0w9skb7x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m6.158 24.028l3.89 1.906h1.227");
}

.c10_-52hz {
  d: path("m20.017 6.257l.323-1.282a.661.661 0 0 1-.323 1.282");
}

.c5y0hmb-o {
  stop-color: var(--svg-color--694548, #694548);
}

.c76owwbvh {
  stop-color: var(--svg-color--393640, #393640);
}

.cabiwub4i {
  stop-color: var(--svg-color--535154, #535154);
  stop-opacity: 0;
}

.cfhwg-9zy {
  stop-color: var(--svg-color--422d5a, #422D5A);
  stop-opacity: 0;
}

.clzavdftr {
  stop-color: var(--svg-color--5e4e70, #5E4E70);
}

.cmnvd12ya {
  cx: 22.508px;
  cy: 15.698px;
  r: 0.475px;
  fill: var(--svg-color--3e3a4a, #3E3A4A);
}

.cu9n-vbgf {
  stop-color: var(--svg-color--c7262d, #C7262D);
}

.cvn34-xwu {
  stop-color: var(--svg-color--832538, #832538);
  stop-opacity: 0;
}

.d_35etgbw {
  fill: var(--svg-color--2e1928, #2E1928);
  d: path("M17.768 3.448c-.115-.388.099-.762.2-.886c.399-.572 1.092-.536 1.47-.319c.443.256.57.38 1.349.248c.78-.133 1.701.068 2.093.997c.392.93-.246 1.858-.184 2.408c.06.55.398.64.457 1.276c.012.874-.583 1.377-1.07 1.453c-.488.075-1.449-.159-1.68-.985c-.38-1.352.042-1.926 0-2.588s-.411-.889-1.133-.825c-.85.075-1.349-.263-1.502-.78");
}

.d0phtb81o {
  stop-color: var(--svg-color--9d969d, #9D969D);
}

.d5v58yb6h {
  stop-color: var(--svg-color--3d2d64, #3D2D64);
}

.d5xoocd9m {
  cx: 18.599px;
  cy: 27.488px;
  r: 1.512px;
}

.d9q4mwzxt {
  stop-color: var(--svg-color--5c5166, #5C5166);
}

.dd9hd6bwg {
  stop-color: var(--svg-color--9d726c, #9D726C);
}

.dleg5vxtn {
  stop-color: var(--svg-color--815f5c, #815F5C);
}

.dt2-hrbth {
  stop-color: var(--svg-color--2b2731, #2B2731);
}

.dvsjoj0vs {
  cx: 15.212px;
  cy: 16.715px;
  r: 0.794px;
}

.e14bc-vgp {
  stop-color: var(--svg-color--ab556a, #AB556A);
  stop-opacity: 0;
}

.e8kph3xgf {
  stop-color: var(--svg-color--4b3e3e, #4B3E3E);
  stop-opacity: 0;
}

.e9_lu_tkl {
  stop-color: var(--svg-color--685977, #685977);
}

.ebki_vbdj {
  stop-color: var(--svg-color--e4355d, #E4355D);
}

.eiyzwdbvn {
  d: path("M14.924 15.129h.578v1.285h-.578z");
}

.ejmms-frd {
  stop-color: var(--svg-color--5a4a6a, #5A4A6A);
}

.eohpzzbti {
  fill: var(--svg-color--7d5fba, #7D5FBA);
  d: path("m19.666 10.076l-.263 2.526c.688 0 1.692.101 2.07.172c.074-.523.233-1.725.274-2.355c.052-.789-.17-1.099-.424-1.268a1 1 0 0 0-1.083 0c-.39.24-.546.716-.574.925");
}

.erpm-ebho {
  stop-color: var(--svg-color--64597c, #64597C);
  stop-opacity: 0;
}

.etx6bbf-f {
  stop-color: var(--svg-color--6c5d7f, #6C5D7F);
}

.eu5aevb0y {
  stop-color: var(--svg-color--bb3143, #BB3143);
}

.eu9d2ynfb {
  fill: var(--svg-color--ffc136, #FFC136);
  d: path("m19.466 12.942l.062-.5a5.2 5.2 0 0 1 1.883.265a10 10 0 0 1-.125 1.016c-.094.523-.367 1.183-1.633 1.23c-1.265.047-3.469-.152-3.726-.222a2 2 0 0 0-.532-.063l-.968-.554c-.196.07-.375-.188-.133-.391c.325-.281.979-.326 1.265-.313c1.126-.387 3.073-.474 3.907-.468");
}

.ewip82vxi {
  stop-color: var(--svg-color--56426b, #56426B);
  stop-opacity: 0;
}

.f37qg-byx {
  stop-color: var(--svg-color--7c5b5b, #7C5B5B);
}

.f6z4yi_ag {
  stop-color: var(--svg-color--dd2f40, #DD2F40);
}

.fkvlxj0pp {
  stop-color: var(--svg-color--562b29, #562B29);
}

.fndizab4b {
  stop-color: var(--svg-color--5e4a5e, #5E4A5E);
}

.fon7meb-r {
  cx: 24.428px;
  cy: 28.524px;
  r: 0.377px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.fqlyqbbmu {
  d: path("m11.28 25.161l3.058-1.72l.961 3.269h-3.62a.827.827 0 0 1-.4-1.549");
}

.ft5dv1b6b {
  fill: none;
}

.gb6cd3sju {
  stop-color: var(--svg-color--4b3c57, #4B3C57);
  stop-opacity: 0;
}

.gc1c4bbqk {
  d: path("M17.768 3.448c-.115-.388.099-.762.2-.886c.399-.572 1.092-.536 1.47-.319c.443.256.57.38 1.349.248c.78-.133 1.701.068 2.093.997c.392.93-.246 1.858-.184 2.408c.06.55.398.64.457 1.276c.012.874-.583 1.377-1.07 1.453c-.488.075-1.449-.159-1.68-.985c-.38-1.352.042-1.926 0-2.588s-.411-.889-1.133-.825c-.85.075-1.349-.263-1.502-.78");
}

.gfg94vbiy {
  fill: var(--svg-color--5e4f7f, #5E4F7F);
  d: path("M13.945 17.283a.5.5 0 0 1 .5-.5h1.548a.5.5 0 0 1 .5.5v.82h-2.548z");
}

.gh1dv7p4f {
  fill: var(--svg-color--55416a, #55416A);
  d: path("M21.961 9.3a1.4 1.4 0 0 1 1.381-1.171h.182a1.4 1.4 0 0 1 1.381 1.628l-1.38 8.346h-3.019z");
}

.golah4bmm {
  stop-color: var(--svg-color--db4459, #DB4459);
}

.gruyj9uct {
  cx: 15.212px;
  cy: 14.819px;
  r: 0.518px;
  fill: var(--svg-color--4a2a60, #4A2A60);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gxhbeh9zc {
  stop-color: var(--svg-color--483962, #483962);
}

.gzc_qccoq {
  stop-color: var(--svg-color--3e3e6c, #3E3E6C);
}

.hlkhhwb3q {
  stop-color: var(--svg-color--f24147, #F24147);
}

.hqbc8kbno {
  d: path("m18.494 5.487l.01-.065c.019-.168-.038-.312-.125-.322c-.088-.01-.174.119-.193.287l-.003.066z");
}

.hw8l16bxs {
  stop-color: var(--svg-color--5e4a5e, #5E4A5E);
  stop-opacity: 0;
}

.hwvatcc-y {
  stop-color: var(--svg-color--9d969d, #9D969D);
  stop-opacity: 0;
}

.hxfvufi0i {
  stop-color: var(--svg-color--a09aa7, #A09AA7);
  stop-opacity: 0;
}

.i_2-mnb6b {
  fill: var(--svg-color--857d8e, #857D8E);
  fill-rule: evenodd;
  d: path("M18.6 30.02a2.531 2.531 0 1 0 0-5.063a2.531 2.531 0 0 0 0 5.063m0-1.02a1.512 1.512 0 1 0 0-3.023a1.512 1.512 0 0 0 0 3.023");
}

.i00c46bgu {
  stop-color: var(--svg-color--4b3c57, #4B3C57);
}

.i8rkxoa5u {
  stop-color: var(--svg-color--832538, #832538);
}

.id6hb3b7i {
  stop-color: var(--svg-color--b11943, #B11943);
}

.ie8_agh2b {
  stop-color: var(--svg-color--3e3e6c, #3E3E6C);
  stop-opacity: 0;
}

.ihz8r9bpq {
  stop-color: var(--svg-color--535154, #535154);
}

.ipohnfkvg {
  stop-color: var(--svg-color--5a4a71, #5A4A71);
}

.j0o3mob8g {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M19.1 5.085c-.105-.131-.3-.18-.383-.188l.228.452c.133.006.287-.1.155-.264");
}

.j5-6p70xh {
  stop-color: var(--svg-color--908893, #908893);
}

.jifg9fbqa {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.123 5.446l.893.098c.04-.354-.13-.663-.376-.69c-.247-.027-.479.238-.517.592");
}

.jijo4-b9s {
  stop-color: var(--svg-color--794b40, #794B40);
}

.jp6shsbzj {
  d: path("m19.466 12.942l.062-.5a5.2 5.2 0 0 1 1.883.265a10 10 0 0 1-.125 1.016c-.094.523-.367 1.183-1.633 1.23c-1.265.047-3.469-.152-3.726-.222a2 2 0 0 0-.532-.063l-.968-.554c-.196.07-.375-.188-.133-.391c.325-.281.979-.326 1.265-.313c1.126-.387 3.073-.474 3.907-.468");
}

.jqu95-b8t {
  stop-color: var(--svg-color--574568, #574568);
}

.jsdt5e8xl {
  stop-color: var(--svg-color--64597c, #64597C);
}

.jynvl5b3k {
  stop-color: var(--svg-color--845a4e, #845A4E);
}

.jzl720bvd {
  stop-color: var(--svg-color--816d8d, #816D8D);
}

.k7-xlwbtv {
  width: 11.844px;
  height: 2.839px;
  x: 12.729px;
  y: 18.102px;
  fill: var(--svg-color--58426f, #58426F);
  rx: 0.5px;
}

.k8klmcqbt {
  stop-color: var(--svg-color--645381, #645381);
}

.ka6kobc6f {
  stop-color: var(--svg-color--474652, #474652);
  stop-opacity: 0;
}

.kegmapbvr {
  stop-color: var(--svg-color--5c5166, #5C5166);
  stop-opacity: 0;
}

.kh4so6bgt {
  stop-color: var(--svg-color--404047, #404047);
  stop-opacity: 0;
}

.kk9p30bku {
  fill: var(--svg-color--857d8e, #857D8E);
  fill-rule: evenodd;
  d: path("M24.428 30.02a1.496 1.496 0 1 0 0-2.993a1.496 1.496 0 0 0 0 2.993m0-.603a.894.894 0 1 0 0-1.787a.894.894 0 0 0 0 1.787");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lsbd06pgn {
  d: path("M22.883 3.902a1.2 1.2 0 0 1 1.39-.972l.565.1a1.2 1.2 0 0 1 .972 1.39l-.3 1.696a1.2 1.2 0 0 1-1.39.972l-.566-.1a1.2 1.2 0 0 1-.972-1.39z");
}

.lzxtmdbfr {
  stop-color: var(--svg-color--4a3a4c, #4A3A4C);
}

.ma5b9zegf {
  stop-color: var(--svg-color--9c83b4, #9C83B4);
}

.mcd03_b4y {
  stop-color: var(--svg-color--ab556a, #AB556A);
}

.mdia87ptp {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M18.686 6.527c.039.05.03.12-.019.16c-.238.187-.555.207-.655.206a.114.114 0 0 1 .001-.227c.086 0 .337-.02.513-.158a.114.114 0 0 1 .16.019");
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.ms0rob30e {
  stop-color: var(--svg-color--58426e, #58426E);
  stop-opacity: 0;
}

.mykl6fbtk {
  stop-color: var(--svg-color--564778, #564778);
}

.mzi2avtdm {
  width: 0.619px;
  height: 2.008px;
  x: 23.614px;
  y: 6.624px;
  rx: 0.31px;
}

.mzqppqgkg {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.5 29.617a1.146 1.146 0 1 0 0-2.292a1.146 1.146 0 0 0 0 2.292Z");
}

.n304-r4kd {
  stop-color: var(--svg-color--9e746b, #9E746B);
}

.n68u5luyx {
  d: path("M19.123 6.964h1.914v2.752h-1.914z");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nbyzmw_ck {
  stop-color: var(--svg-color--b52f5e, #B52F5E);
}

.nhtvs4bus {
  stop-color: var(--svg-color--db4459, #DB4459);
  stop-opacity: 0;
}

.ni_rkbnps {
  stop-color: var(--svg-color--794b40, #794B40);
  stop-opacity: 0;
}

.o_3_trjap {
  stop-color: var(--svg-color--4e3870, #4E3870);
}

.o-5paobui {
  stop-color: var(--svg-color--544341, #544341);
  stop-opacity: 0;
}

.o7v7nujms {
  stop-color: var(--svg-color--b92c31, #B92C31);
  stop-opacity: 0;
}

.obuzyxb5s {
  stop-color: var(--svg-color--25163e, #25163E);
  stop-opacity: 0;
}

.on-6a1tha {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M18.688 4.562a.7.7 0 0 0-.194-.035a.136.136 0 0 1-.004-.273a1 1 0 0 1 .28.048a.9.9 0 0 1 .352.197a.136.136 0 1 1-.185.2a.7.7 0 0 0-.249-.137");
}

.opuqn1hcz {
  d: path("m12.85 15.532l3.914-.48l4.53 3.426h-8.582s-1.636 4.634-2.75 7.144c-1.096-.411-4-1.833-4-1.833c.02-.163.218-.526.849-.677c.63-.15 2.033-.131 2.655-.103c.117-.825.438-2.956.788-4.882s1.876-2.532 2.595-2.595");
}

.or7cc4f6p {
  stop-color: var(--svg-color--0a0208, #0A0208);
  stop-opacity: 0;
}

.p29rc0b5o {
  cx: 24.428px;
  cy: 28.524px;
  r: 0.894px;
}

.p8hc-w2ji {
  stop-color: var(--svg-color--746e6d, #746E6D);
}

.pbwt4gb4m {
  stop-color: var(--svg-color--675876, #675876);
  stop-opacity: 0;
}

.ph_duzi0t {
  stop-color: var(--svg-color--846eaf, #846EAF);
}

.ppzv89b4g {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.721 13.946c.52-.078 1.94-.256 3.453-.344l.125-.828");
}

.pxendyjut {
  d: path("M16.181 20.754h4.836v1.273h-4.836z");
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.q-5444bwf {
  cx: 12.771px;
  cy: 28.524px;
  r: 0.377px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.r62w_lejb {
  d: path("M17.743 4.678c.114-.72.387-1.044.509-1.135l3.375.37l-.256 2.867c-.993 1.833-3.394 1.654-3.676.92c-.281-.732-.084-2.188.048-3.022");
}

.r7q-w8bhi {
  width: 11.844px;
  height: 2.839px;
  x: 12.729px;
  y: 18.102px;
  rx: 0.5px;
}

.r8d-hgb6b {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M18.7 29.417a2.029 2.029 0 1 0 0-4.058a2.029 2.029 0 0 0 0 4.058Z");
}

.r9oq2bbva {
  stop-color: var(--svg-color--25163e, #25163E);
}

.rc1jpzb3f {
  fill: var(--svg-color--f0303e, #F0303E);
  d: path("m25.92 25.161l-3.059-1.72l-1.054 3.269h3.714a.827.827 0 0 0 .399-1.549");
}

.rf3kejb9c {
  fill: var(--svg-color--785451, #785451);
  d: path("M14.164 14.781c.417-.495.921-.668 1.13-.707c.223-.062.651-.075.726.121a.43.43 0 0 1-.062.418a1.95 1.95 0 0 0-1.32.55a.32.32 0 0 1-.442.005a.283.283 0 0 1-.032-.387");
}

.rfxr5lvvz {
  stop-color: var(--svg-color--cc3437, #CC3437);
  stop-opacity: 0;
}

.riz6vyb_j {
  cx: 12.771px;
  cy: 28.524px;
  r: 1.496px;
  fill: var(--svg-color--857d8e, #857D8E);
}

.rjbedibdc {
  fill: var(--svg-color--4c477e, #4C477E);
  d: path("M10.53 24.276c-.196.485-.388.943-.567 1.346c-1.097-.411-4-1.833-4-1.833c.02-.163.217-.526.848-.677c.63-.15 2.033-.131 2.655-.103c0-.006.48.55 1.065 1.267");
}

.ronnvab4v {
  stop-color: var(--svg-color--211b2c, #211B2C);
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.rq851lrid {
  stop-color: var(--svg-color--312058, #312058);
  stop-opacity: 0;
}

.scmywnb8q {
  stop-color: var(--svg-color--846eaf, #846EAF);
  stop-opacity: 0;
}

.scqcqwblc {
  stop-color: var(--svg-color--7d7172, #7D7172);
}

.seor_02fd {
  stop-color: var(--svg-color--422d5a, #422D5A);
}

.snka5sm3m {
  stop-color: var(--svg-color--6b6080, #6B6080);
  stop-opacity: 0;
}

.sputfhdoz {
  stop-color: var(--svg-color--6a5c77, #6A5C77);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.svvwe7bhc {
  cx: 18.315px;
  cy: 5.145px;
  rx: 0.059px;
  ry: 0.08px;
}

.t_w7gbbck {
  stop-color: var(--svg-color--675876, #675876);
}

.t07ov5bcy {
  stop-color: var(--svg-color--483962, #483962);
  stop-opacity: 0;
}

.t0hm9_sih {
  stop-color: var(--svg-color--8c73c0, #8C73C0);
  stop-opacity: 0;
}

.t2wsg-6mb {
  fill: var(--svg-color--785451, #785451);
  d: path("M13.761 14.59c.367-.533.853-.754 1.057-.812c.215-.083.641-.137.735.051a.43.43 0 0 1-.023.422a1.95 1.95 0 0 0-1.261.675a.32.32 0 0 1-.44.047a.284.284 0 0 1-.068-.383");
}

.t8rqipb-o {
  stop-color: var(--svg-color--523579, #523579);
}

.t9qy5zbtq {
  stop-color: var(--svg-color--64576e, #64576E);
  stop-opacity: 0;
}

.tgn2_cbqk {
  stop-color: var(--svg-color--664a85, #664A85);
  stop-opacity: 0;
}

.th1brvxrz {
  stop-color: var(--svg-color--ed516c, #ED516C);
}

.tkes6b_0a {
  cx: 15.212px;
  cy: 14.819px;
  r: 0.518px;
}

.tq5ps4b3l {
  d: path("M12.536 26.32h.471v1.492h-.471z");
}

.tsh4uysfx {
  cx: 18.599px;
  cy: 27.488px;
  r: 0.637px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.u4sz8cc_m {
  fill: var(--svg-color--55426a, #55426A);
  d: path("M22.883 3.902a1.2 1.2 0 0 1 1.39-.972l.565.1a1.2 1.2 0 0 1 .972 1.39l-.3 1.696a1.2 1.2 0 0 1-1.39.972l-.566-.1a1.2 1.2 0 0 1-.972-1.39z");
}

.u9mcm6llv {
  stop-color: var(--svg-color--565476, #565476);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uevlegbhj {
  stop-color: var(--svg-color--5b4874, #5B4874);
  stop-opacity: 0;
}

.uk3jx7nau {
  stop-color: var(--svg-color--8a5752, #8A5752);
}

.uu4nvia_s {
  stop-color: var(--svg-color--958d9a, #958D9A);
  stop-opacity: 0;
}

.ux0of3-jj {
  stop-color: var(--svg-color--e2305a, #E2305A);
  stop-opacity: 0;
}

.v4yb5cu8i {
  stop-color: var(--svg-color--695b77, #695B77);
}

.vbsma9b6v {
  d: path("m10.71 17.988l-1.031 5.079l.343.328l1.72-5.875h2v-1.594l-1.282.156c-1.125.125-1.636 1.323-1.75 1.906");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vdj-q1-ni {
  stop-color: var(--svg-color--312058, #312058);
}

.vloggvbag {
  stop-color: var(--svg-color--7b5257, #7B5257);
}

.vt606lu7d {
  stop-color: var(--svg-color--574568, #574568);
  stop-opacity: 0;
}

.vtqj02myp {
  d: path("M21.961 9.3a1.4 1.4 0 0 1 1.381-1.171h.182a1.4 1.4 0 0 1 1.381 1.628l-1.38 8.346h-3.019z");
}

.w_fjow9gn {
  stop-color: var(--svg-color--d61f4c, #D61F4C);
}

.w_hnjyb9a {
  d: path("m19.666 10.076l-.263 2.526c.688 0 1.692.101 2.07.172c.074-.523.233-1.725.274-2.355c.052-.789-.17-1.099-.424-1.268a1 1 0 0 0-1.083 0c-.39.24-.546.716-.574.925");
}

.w07b1tb5i {
  stop-color: var(--svg-color--5e4e70, #5E4E70);
  stop-opacity: 0;
}

.w24n_ub5p {
  d: path("M18.67 5.505v-.003c.032-.29-.067-.538-.22-.555c-.153-.016-.302.205-.334.494v.004z");
}

.w8fowerpf {
  stop-color: var(--svg-color--8c73c0, #8C73C0);
}

.wfgkivb4m {
  d: path("m16.73 15.027l3.793 3.118l1.44-8.172c-.197-1.362-1.876-1.576-2.518-1.507c-.643.068-1.37.437-1.876 1.978c-.404 1.234-.728 3.57-.84 4.583");
}

.wjw662jrg {
  stop-color: var(--svg-color--321d4a, #321D4A);
}

.wtnucq2vy {
  fill-rule: evenodd;
  d: path("M5.697 23.862a.375.375 0 0 1 .502-.17l3.788 1.864l.01.003h1.427a.375.375 0 0 1 0 .75H9.998a.8.8 0 0 1-.343-.08l-3.787-1.865a.375.375 0 0 1-.171-.502");
}

.x9-imyafb {
  stop-color: var(--svg-color--958d9a, #958D9A);
}

.x91xhsboa {
  stop-color: var(--svg-color--55426a, #55426A);
  stop-opacity: 0;
}

.xbtn5acgm {
  stop-color: var(--svg-color--6c5d7f, #6C5D7F);
  stop-opacity: 0;
}

.xdztpacdw {
  fill: var(--svg-color--835c5a, #835C5A);
  d: path("m19.466 12.942l.062-.5a5.2 5.2 0 0 1 1.883.265a10 10 0 0 1-.125 1.016c-.094.523-.367 1.183-1.633 1.23c-1.265.047-3.469-.152-3.726-.222a2 2 0 0 0-.532-.063l-.968-.554c-.196.07-.375-.188-.133-.391c.325-.281.979-.326 1.265-.313c1.126-.387 3.073-.474 3.907-.468");
}

.xhqab6xhy {
  d: path("m25.92 25.161l-3.059-1.72l-1.054 3.269h3.714a.827.827 0 0 0 .399-1.549");
}

.xix9lmpxe {
  d: path("M10.53 24.276c-.196.485-.388.943-.567 1.346c-1.097-.411-4-1.833-4-1.833c.02-.163.217-.526.848-.677c.63-.15 2.033-.131 2.655-.103c0-.006.48.55 1.065 1.267");
}

.xkzs54_ul {
  stop-color: var(--svg-color--4d487f, #4D487F);
  stop-opacity: 0;
}

.xo67nobiw {
  stop-color: var(--svg-color--0a0208, #0A0208);
}

.xs80ogben {
  stop-color: var(--svg-color--6b6080, #6B6080);
}

.xy0warxtb {
  fill: var(--svg-color--826bad, #826BAD);
  d: path("m16.73 15.027l3.793 3.118l1.44-8.172c-.197-1.362-1.876-1.576-2.518-1.507c-.643.068-1.37.437-1.876 1.978c-.404 1.234-.728 3.57-.84 4.583");
}

.y_bf1qbke {
  stop-color: var(--svg-color--4b3e3e, #4B3E3E);
}

.y05dlfbsr {
  stop-color: var(--svg-color--5b4874, #5B4874);
}

.y3ztz7b1k {
  stop-color: var(--svg-color--906964, #906964);
  stop-opacity: 0;
}

.ybejupycn {
  stop-color: var(--svg-color--b92c31, #B92C31);
}

.yo3u-ub4s {
  fill-rule: evenodd;
  d: path("M24.428 30.02a1.496 1.496 0 1 0 0-2.993a1.496 1.496 0 0 0 0 2.993m0-.603a.894.894 0 1 0 0-1.787a.894.894 0 0 0 0 1.787");
}

.yt_hl7yft {
  stop-color: var(--svg-color--815f5c, #815F5C);
  stop-opacity: 0;
}

.yu1mih4mu {
  stop-color: var(--svg-color--9c1a55, #9C1A55);
}

.yxnjz7r7g {
  stop-color: var(--svg-color--c54169, #C54169);
  stop-opacity: 0;
}

.z1-difb5b {
  stop-color: var(--svg-color--c54169, #C54169);
}

.z3g8mdthr {
  cx: 12.771px;
  cy: 28.524px;
  r: 1.496px;
}

.zcevvihat {
  d: path("m14.486 26.66l-.425-3.4a1.2 1.2 0 0 1 1.191-1.35h6.672a1.2 1.2 0 0 1 1.191 1.343l-.406 3.4a1 1 0 0 1-.993.882h-6.237a1 1 0 0 1-.993-.876");
}

.zcp15fbad {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.771 29.617a1.146 1.146 0 1 0 0-2.292a1.146 1.146 0 0 0 0 2.292Z");
}

.zdh48sb9s {
  stop-color: var(--svg-color--816d8d, #816D8D);
  stop-opacity: 0;
}

.zeqefbvfd {
  stop-color: var(--svg-color--321c43, #321C43);
}

.zrt30_2yc {
  fill: var(--svg-color--624499, #624499);
  d: path("m19.386 10.314l-.263 2.526c.688 0 1.692.101 2.07.172c.075-.522.233-1.725.274-2.355c.052-.788-.17-1.099-.423-1.268a1 1 0 0 0-1.084 0c-.39.24-.545.717-.574.925");
}

.zz5qicf0f {
  d: path("M24.187 26.32h.471v1.492h-.471z");
}

</style>
