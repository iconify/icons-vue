<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#itAPcmd)"><path fill="url(#i1emUUM)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#ij7ryMc)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#iIFjyxU)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#ixmTZnc)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#iK5sA1c)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#i86KBAb)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#iHeqdgb)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#i2l56rd)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#iqaYIAm)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#iOsERSO)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#iOuhSwd)" clip-rule="evenodd" class="xlifj_bsk"/><path fill="url(#idFbHzA)" clip-rule="evenodd" class="xlifj_bsk"/></g><g filter="url(#iBWLiEo)"><path class="pk84u7jjf"/><path fill="url(#iYUPgCn)" class="pn5jbtt9h"/></g><path fill="url(#ibC1qLe)" class="pn5jbtt9h"/><path fill="url(#iIAQn6c)" class="pn5jbtt9h"/><path fill="url(#i1wcfOb)" class="pn5jbtt9h"/><path fill="url(#id94ewd)" class="pn5jbtt9h"/><g filter="url(#iI69HYd)"><path class="y79whbcii"/><path fill="url(#iTH78cb)" class="z0pxpnkbw"/></g><path class="fugdzyb1o"/><path fill="url(#iTIjaLd)" class="hr107sbjg"/><path fill="url(#ioDmBkd)" class="sgu32ab0w"/><path fill="url(#ijic07z)" class="sf2boes3b"/><path fill="url(#isyGmte)" class="sf2boes3b"/><g filter="url(#iTq1uKW)"><path fill="url(#icOIhCe)" class="lbpgcfbob"/><path fill="url(#i0RjV5w)" class="lbpgcfbob"/></g><g filter="url(#iI2ruFc)"><circle fill="url(#ilkWDkd)" class="dkktn1hof"/></g><g filter="url(#iHY7shb)"><circle fill="url(#iR7ViFc)" class="uh8iu31tc"/></g><g filter="url(#it2CT5c)"><circle fill="url(#iVwnzxc)" class="a5a4koq8x"/></g><rect fill="url(#iWebikb)" transform="rotate(26.595 20.662 12.81)" class="toe447tsm"/><g filter="url(#iLYaGib)"><path fill="url(#icaasDe)" class="qd_9svrfx"/></g><path class="dldw44uej"/><g filter="url(#iCCk4JW)"><path class="cxr4nnflu"/><path fill="url(#if0YLEc)" class="xzkoa2bwe"/><path fill="url(#ildRqmd)" class="xzkoa2bwe"/></g><g filter="url(#iQ9iEUb)"><path fill="url(#iZr6Sle)" class="cjqtkw6wk"/><path fill="url(#iKQJHyJ)" class="cjqtkw6wk"/><path fill="url(#itDDjWb)" class="cjqtkw6wk"/></g><path fill="url(#ivw1T6b)" class="cjqtkw6wk"/><path fill="url(#iQjL6ye)" class="llo96eq-p"/><path fill="url(#iRaF0Fb)" class="llo96eq-p"/><path clip-rule="evenodd" class="n-63dkbfe"/><path fill="url(#ibw8yfe)" clip-rule="evenodd" class="y-2lu0bml"/><path clip-rule="evenodd" class="qe-ha1b7i"/><path fill="url(#i7JGUkc)" clip-rule="evenodd" class="xy8jbrbcm"/><path clip-rule="evenodd" class="iwur3y2uz"/><path fill="url(#iyLPjHb)" clip-rule="evenodd" class="ngpy26t4k"/><path clip-rule="evenodd" class="vurnokzna"/><path fill="url(#iyiSuIb)" clip-rule="evenodd" class="wvwy8egxn"/><path class="ekge1hb-m"/><path fill="url(#iCdksNe)" class="lalq_3f3j"/><g filter="url(#is8rXce)"><path fill="url(#iR6HFdd)" class="r8fjj8bcd"/></g><g filter="url(#iFPaaDb)"><path fill="url(#iS8Pj9w)" class="siwrhab8g"/></g><g filter="url(#iiCzioe)"><path stroke="url(#i3UNp3d)" class="j6zxuhbzj"/></g><g filter="url(#iDIlF7d)"><path fill="url(#iwCEIlk)" class="v0zmloa0d"/></g><path fill="url(#iW6NARd)" class="v0zmloa0d"/><g filter="url(#isW4Kud)"><path fill="url(#itjvJYc)" class="fb_y6pmdf"/><path fill="url(#ilw0zUb)" class="fb_y6pmdf"/></g><g filter="url(#iD6UNuc)"><path class="zsn7xn-yh"/><path fill="url(#ihK15Uq)" class="tuwn6jbrs"/></g><g filter="url(#ihPTHHl)"><path class="jv4zpicrd"/><path fill="url(#i78zP1c)" class="nqqcbvb7z"/></g><path fill="url(#ik9ovuc)" class="mt1ylgber"/><path fill="url(#iMTupod)" class="mt1ylgber"/><path fill="url(#iXIPFjb)" class="mt1ylgber"/><path fill="url(#it51bXl)" class="mt1ylgber"/><path fill="url(#iOBKaxe)" class="mt1ylgber"/><path fill="url(#iGmrgHc)" class="mt1ylgber"/><path fill="url(#ivGmr9d)" class="mt1ylgber"/><path fill="url(#iLuG6UW)" class="mt1ylgber"/><path fill="url(#ilMyNGd)" class="mt1ylgber"/><g filter="url(#i7ZtXVb)"><path class="c0do_cc_q"/></g><g filter="url(#iR4VtAd)"><path class="hp6uesvdn"/><path fill="url(#i0DPQxN)" class="v74acaceo"/><path fill="url(#i6T8mnN)" class="v74acaceo"/><path fill="url(#idxaB4b)" class="v74acaceo"/><path fill="url(#iAFU2Lc)" class="v74acaceo"/></g><g filter="url(#iY82nYb)"><path stroke="url(#i23Xg3d)" class="unss9nbst"/></g><path class="bd-bwb4vx"/><g filter="url(#ixnBvYb)"><path class="cybrf_xbn"/></g><g filter="url(#iN78C6c)"><path class="l67vgwenw"/></g><g filter="url(#izvrpgb)"><path class="vqsxzubiu"/></g><g filter="url(#iHDt9Db)"><path clip-rule="evenodd" class="oda0xdbdw"/></g><path class="qtb8wgbxo"/><path fill="url(#ihf3DBe)" class="sk9mj8t1w"/><path class="uu7g49bxq"/><g filter="url(#i2nioIc)"><path class="o8igjrb5x"/><path fill="url(#ij4QENc)" class="n73g--bav"/></g><g filter="url(#iMFLcXb)"><path fill="url(#ichuhId)" class="aukhclb3a"/></g><path class="h0orq2bcv"/><path fill="url(#iYwqACd)" class="f21lz6tah"/><path class="zc5clpb8v"/><g filter="url(#i5YIvtv)"><path fill="url(#iSnlqbe)" class="oz-ci00mm"/></g><g filter="url(#icf4Kvb)"><ellipse transform="rotate(-27.914 12.947 5.729)" class="etwbqtb1r"/><ellipse fill="url(#iVNYFxe)" transform="rotate(-27.914 12.947 5.729)" class="rrk9g0i-o"/></g><g filter="url(#iLHcCxb)"><path class="o2028dbfw"/><path fill="url(#i6dX2cG)" class="qocy9nbod"/><path fill="url(#itjExsb)" class="qocy9nbod"/></g><g filter="url(#itOJSTc)"><path class="meew3122p"/></g><defs><radialGradient id="ij7ryMc" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 3.819 9.671)scale(2.05339 2.5651)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iIFjyxU" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 5.213 5.57)scale(1.55266 2.04007)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="ixmTZnc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 4.423 6.004)scale(.96098 .73791)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iK5sA1c" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 4.574 6.003)scale(1.10512 .77846)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="i86KBAb" cx="0" cy="0" r="1" gradientTransform="matrix(.61368 1.1675 -1.62066 .85189 12.47 2.44)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="iHeqdgb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 7.626 5.132)scale(.91019 1.27198)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="i2l56rd" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 8.294 4.068)scale(.85733 1.78789)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iqaYIAm" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 8.12 4.646)scale(1.29597 1.65087)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iOsERSO" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 9.713 -3.493)scale(1.25036 .98896)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iOuhSwd" cx="0" cy="0" r="1" gradientTransform="matrix(.6715 .07044 -.11413 1.08803 11.3 5.641)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="idFbHzA" cx="0" cy="0" r="1" gradientTransform="matrix(-.3742 -1.65396 .59694 -.13505 16.325 5.35)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="ibC1qLe" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.985 21.77)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="i1wcfOb" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -6.125 3.8162 2.21963 22.204 21.926)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="id94ewd" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.77)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iTH78cb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.17 25.208)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iTIjaLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.76 25.141)" gradientUnits="userSpaceOnUse"><stop class="gsejooqnz"/><stop offset="1" class="of4__9yml"/></radialGradient><radialGradient id="isyGmte" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.473)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="i0RjV5w" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.742 2.818)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="ilkWDkd" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.215 11.138)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iR7ViFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.556)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iVwnzxc" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.168 9.172)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iWebikb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.108)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="eb_ebqvii"/><stop offset="1" class="wqensyb5w"/></radialGradient><radialGradient id="icaasDe" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.2 10.925)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="xtqzqnbwf"/><stop offset="1" class="god345nqf"/></radialGradient><radialGradient id="if0YLEc" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.926 6.717)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="hiph0yb8z"/><stop offset="1" class="nng6piu-d"/></radialGradient><radialGradient id="ildRqmd" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.335 10.553)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="rjhj4ebho"/><stop offset="1" class="m0m5thktx"/></radialGradient><radialGradient id="iKQJHyJ" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.426)" gradientUnits="userSpaceOnUse"><stop class="zhpuq6bwb"/><stop offset="1" class="lrsiznbuc"/></radialGradient><radialGradient id="itDDjWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49191 -2.04898 0 13.776 7.606)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="sz7_smkrr"/><stop offset="1" class="rqh0k2bpm"/></radialGradient><radialGradient id="ivw1T6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 -.625 2.3294 4.19292 17.339 21.238)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tn---htwd"/><stop offset="1" class="accyaboul"/></radialGradient><radialGradient id="iRaF0Fb" cx="0" cy="0" r="1" gradientTransform="matrix(3.55689 1.62587 -1.10084 2.4083 18.61 10.753)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ns_rnx4db"/><stop offset="1" class="airol1bay"/><stop offset="1" class="cfcr9ub1k"/></radialGradient><radialGradient id="ibw8yfe" cx="0" cy="0" r="1" gradientTransform="rotate(-139.897 5.2 5.918)scale(1.34825 1.69882)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="i7JGUkc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24388 -.94214 1.33264 -1.75944 5.77 14.69)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="iyLPjHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23007 -1.01775 1.46904 -1.7755 5.598 15.256)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="iyiSuIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04688 -.89062 1.29178 -1.51843 5.802 15.488)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="iCdksNe" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.78)" gradientUnits="userSpaceOnUse"><stop class="pzzto25mw"/><stop offset="1" class="pfxo1bxwi"/></radialGradient><radialGradient id="iR6HFdd" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.508 15.402)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iW6NARd" cx="0" cy="0" r="1" gradientTransform="rotate(-118.51 7.897 -.124)scale(.6115 .69292)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="itjvJYc" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 22.313 -33.46)scale(1.22079 1.49053)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="ilw0zUb" cx="0" cy="0" r="1" gradientTransform="matrix(.53885 0 0 .232 16.25 5.276)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="ihK15Uq" cx="0" cy="0" r="1" gradientTransform="matrix(.67417 -.05015 .0392 .52701 16.003 6.088)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="i78zP1c" cx="0" cy="0" r="1" gradientTransform="rotate(-180 5.994 3.019)scale(.47149)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="ik9ovuc" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.023 4.58)scale(3.19774 4.28012)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iMTupod" cx="0" cy="0" r="1" gradientTransform="matrix(-.9735 .42837 -.29831 -.67793 14.922 6.18)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iXIPFjb" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 12.547 -4.676)scale(1.84606 2.3423)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="it51bXl" cx="0" cy="0" r="1" gradientTransform="matrix(-.57361 3.29215 -4.11514 -.717 14.5 5.612)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="iOBKaxe" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.106 4.007)scale(3.14221 5.40992)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iGmrgHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51382 .6306 0 15.07 5.611)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="ivGmr9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58604 .67164 0 13.115 5.509)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iLuG6UW" cx="0" cy="0" r="1" gradientTransform="matrix(-.38853 1.44075 -1.15284 -.31089 14.66 4.577)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="ilMyNGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57388 0 0 -2.87796 16.317 6.275)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="i0DPQxN" cx="0" cy="0" r="1" gradientTransform="matrix(-.2034 -.91266 .28127 -.06269 14.393 6.6)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iAFU2Lc" cx="0" cy="0" r="1" gradientTransform="matrix(-.348 0 0 -.0973 14.286 6.694)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="ihf3DBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36225 -.5762 0 15.017 5.771)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ij4QENc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10355 -.13344 .18372 -.14257 14.915 5.809)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYwqACd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36226 -.57621 0 13.068 5.771)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVNYFxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00345 -.2206 .26517 -.00415 12.94 5.87)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6dX2cG" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.662 5.932)scale(2.17576 3.55725)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="itjExsb" cx="0" cy="0" r="1" gradientTransform="matrix(-.09392 .61046 -1.31337 -.20206 14.136 2.664)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="itAPcmd" width="6.956" height="7.456" x="10.69" y="1.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="iBWLiEo" width="23.977" height="13.398" x="6.016" y="16.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="iI69HYd" width="20.681" height="10.082" x="6.11" y="20.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".75"/></filter><filter id="iTq1uKW" width="24.344" height="8.644" x="2.007" y="21.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="iI2ruFc" width="2.686" height="2.686" x="24.571" y="13.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="iHY7shb" width="2.186" height="2.186" x="27.821" y="11.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="it2CT5c" width="1.928" height="1.928" x="25.946" y="9.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="iLYaGib" width="2.857" height="2.898" x="20.532" y="12.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.34902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="iCCk4JW" width="5.571" height="6.952" x="7.773" y="7.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.219608 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="iQ9iEUb" width="14.97" height="18.153" x="8.427" y="7.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.470588 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="is8rXce" width="17.737" height="14.8" x="13.579" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation="1"/></filter><filter id="iFPaaDb" width="6.506" height="14.75" x="14.572" y="7.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".375"/></filter><filter id="iiCzioe" width="5.506" height="5.421" x="17.991" y="7.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".3"/></filter><filter id="iDIlF7d" width="1.587" height="1.437" x="11.232" y="5.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="isW4Kud" width="1.437" height="1.687" x="15.479" y="5.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="iD6UNuc" width="1.959" height="1.959" x="15.218" y="5.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".25"/></filter><filter id="ihPTHHl" width="1.659" height="1.659" x="11.129" y="5.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".175"/></filter><filter id="i7ZtXVb" width="1.838" height="2.197" x="13.051" y="5.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".25"/></filter><filter id="iR4VtAd" width="1.038" height="1.397" x="13.523" y="5.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".05"/></filter><filter id="iY82nYb" width="1.875" height=".903" x="13.105" y="6.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".05"/></filter><filter id="ixnBvYb" width="1.451" height=".574" x="14.352" y="5.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="iN78C6c" width="1.451" height=".574" x="12.282" y="5.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="izvrpgb" width="1.206" height=".598" x="12.342" y="4.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="iHDt9Db" width="1.206" height=".598" x="14.761" y="4.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/></filter><filter id="i2nioIc" width=".462" height=".422" x="14.633" y="5.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".05"/></filter><filter id="iMFLcXb" width=".619" height=".629" x="14.953" y="5.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".1"/></filter><filter id="i5YIvtv" width=".662" height=".686" x="12.969" y="5.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".1"/></filter><filter id="icf4Kvb" width=".518" height=".425" x="12.688" y="5.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".05"/></filter><filter id="iLHcCxb" width="4.119" height="2.708" x="12.461" y="2.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22998"/><feGaussianBlur result="effect2_foregroundBlur_3987_22998" stdDeviation=".075"/></filter><filter id="itOJSTc" width="3.7" height="2.336" x="13.368" y="2.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22998" stdDeviation=".375"/></filter><linearGradient id="i1emUUM" x1="16.138" x2="13.399" y1="2.933" y2="7.738" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iYUPgCn" x1="7.172" x2="16.735" y1="29.364" y2="29.364" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iIAQn6c" x1="16.86" x2="16.766" y1="30.27" y2="28.645" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="ioDmBkd" x1="21.172" x2="19.469" y1="21.926" y2="23.012" gradientUnits="userSpaceOnUse"><stop class="szw4sibdg"/><stop offset="1" class="k794rrb7o"/></linearGradient><linearGradient id="ijic07z" x1="22.095" x2="23.329" y1="24.832" y2="26.114" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="icOIhCe" x1="5.891" x2="25.735" y1="29.239" y2="22.332" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="iZr6Sle" x1="15.777" x2="15.777" y1="7.606" y2="25.567" gradientUnits="userSpaceOnUse"><stop class="t_t1uhgaw"/><stop offset="1" class="wlohty-lv"/></linearGradient><linearGradient id="iQjL6ye" x1="23.651" x2="16.517" y1="12.502" y2="8.549" gradientUnits="userSpaceOnUse"><stop class="g55u5uboh"/><stop offset=".91" class="hq3x-3bjw"/></linearGradient><linearGradient id="iS8Pj9w" x1="17.826" x2="20.269" y1="8.16" y2="21.397" gradientUnits="userSpaceOnUse"><stop class="xf-olmy6i"/><stop offset="1" class="nb49g6u5x"/></linearGradient><linearGradient id="i3UNp3d" x1="22.438" x2="18.766" y1="11.879" y2="7.989" gradientUnits="userSpaceOnUse"><stop class="o-7v_hpgv"/><stop offset="1" class="qosi95ahb"/></linearGradient><linearGradient id="iwCEIlk" x1="11.232" x2="12.061" y1="6.077" y2="6.077" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="i6T8mnN" x1="13.623" x2="14.042" y1="6.632" y2="6.632" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="idxaB4b" x1="14.042" x2="14.042" y1="6.948" y2="6.668" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="i23Xg3d" x1="13.567" x2="13.773" y1="7.618" y2="7.3" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ichuhId" x1="15.364" x2="15.224" y1="5.795" y2="5.882" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSnlqbe" x1="13.4" x2="13.26" y1="5.795" y2="5.882" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-surfing-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a5a4koq8x {
  cx: 26.86px;
  cy: 10.727px;
  r: 0.914px;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.accyaboul {
  stop-color: var(--svg-color--593b9d, #593B9D);
  stop-opacity: 0;
}

.airol1bay {
  stop-color: var(--svg-color--815ecd, #815ECD);
  stop-opacity: 0;
}

.ajhe7ybyb {
  stop-color: var(--svg-color--9b686d, #9B686D);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.aukhclb3a {
  d: path("M15.373 5.904a.4.4 0 0 0-.104-.206l-.116.127l.053.102z");
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.bd-bwb4vx {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M14.042 7.338a1.35 1.35 0 0 1-.634-.154c-.063-.033-.13.04-.091.098a.863.863 0 0 0 1.45 0c.04-.06-.027-.13-.09-.098c-.184.098-.4.154-.635.154");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.c0do_cc_q {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m13.867 5.938l-.305.76a.24.24 0 0 0 .232.312h.352c.164 0 .28-.159.232-.313l-.237-.759c-.051-.168-.22-.168-.274 0");
}

.cfcr9ub1k {
  stop-color: var(--svg-color--6845b9, #6845B9);
  stop-opacity: 0;
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.cjqtkw6wk {
  d: path("M12.759 11.653c-.432-1.716.169-3.162.507-3.485l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.258c1.354 1.047 1.622 2.799 1.589 3.592a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.273-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.513 1.212 3.52c.546 1.484-.11 2.952.375 4.484c.377 1.191 1.203 2.418 1.636 2.92a.04.04 0 0 1-.013.063l-1.834.852a.04.04 0 0 1-.048-.01c-1.848-2.158-2.5-3.826-2.562-3.99s-.23-.53-.574-.53c-.275 0-.59.35-.809.73l-4.667 7.137a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.164 4.542-9.51 4.773-10.057c.21-.5.181-.917.14-1.086c-.03-.13-.218-.711-.585-2.172");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cxr4nnflu {
  fill: var(--svg-color--7a5cb9, #7A5CB9);
  d: path("M10.684 11.696c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.032c.3-.028 1.148-.11 2.5-.72c1.679-.756 2.458-1.803 2.64-2.245l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.cybrf_xbn {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M14.552 5.784c.119-.209.299-.373.687-.373a.74.74 0 0 1 .479.164c.12.097.104.221.01.268l-.248.142c-.29-.094-.612-.107-.928-.201");
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.dkktn1hof {
  cx: 25.864px;
  cy: 14.762px;
  r: 1.293px;
}

.dldw44uej {
  fill: var(--svg-color--aa846a, #AA846A);
  d: path("M7.602 12.776h.594c-.106.669.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.256.977-.3 1.258-.29");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eb_ebqvii {
  stop-color: var(--svg-color--94625a, #94625A);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.ekge1hb-m {
  fill: var(--svg-color--aa846a, #AA846A);
  d: path("M6.126 14.887c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.etwbqtb1r {
  cx: 12.947px;
  cy: 5.729px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.174px;
  ry: 0.088px;
}

.f21lz6tah {
  d: path("M13.067 5.558a.398.398 0 0 0-.384.504h.77a.4.4 0 0 0-.386-.504");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fb_y6pmdf {
  d: path("M16.198 6.756a.718.718 0 1 0 0-1.437a.718.718 0 0 0 0 1.437");
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.ft5dv1b6b {
  fill: none;
}

.fugdzyb1o {
  fill: var(--svg-color--ab7f67, #AB7F67);
  d: path("m7.305 27.348l1.172-2.39l1.766.304v1.04z");
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

.g55u5uboh {
  stop-color: var(--svg-color--896ad2, #896AD2);
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.god345nqf {
  stop-color: var(--svg-color--a1706f, #A1706F);
}

.gsejooqnz {
  stop-color: var(--svg-color--ba917f, #BA917F);
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h0orq2bcv {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.975 5.437a.624.624 0 0 0-.605.473c-.02.078.04.152.12.152h.996a.103.103 0 0 0 .101-.122a.626.626 0 0 0-.612-.503");
}

.hiph0yb8z {
  stop-color: var(--svg-color--8069a8, #8069A8);
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

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hp6uesvdn {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m13.872 5.877l-.238.759a.24.24 0 0 0 .233.312h.35a.24.24 0 0 0 .233-.312l-.237-.76c-.05-.168-.288-.168-.341 0");
}

.hq3x-3bjw {
  stop-color: var(--svg-color--8c6dd3, #8C6DD3);
}

.hr107sbjg {
  d: path("m7.305 27.348l1.172-2.39l1.766.304v1.04z");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iwur3y2uz {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M5.25 14.667q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.129.165-.253.27-.354a2.5 2.5 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.37a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.263a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
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

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j6zxuhbzj {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.286c1.209-.021 3.782.828 4.104 4");
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jv4zpicrd {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.959 6.517a.48.48 0 1 0 0-.959a.48.48 0 0 0 0 .96");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k794rrb7o {
  stop-color: var(--svg-color--82574c, #82574C);
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
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

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l67vgwenw {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M13.532 5.784c-.118-.209-.298-.373-.686-.373a.74.74 0 0 0-.479.164c-.12.097-.104.221-.011.268l.248.142c.291-.094.613-.107.928-.201");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lalq_3f3j {
  d: path("M6.126 14.887c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.lbpgcfbob {
  d: path("M24.458 21.262L2.29 28.951a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.099 1.156-.156c5.922-2.016 17.406-5.86 18.176-6.2c.443-.195.511-.378.605-.627v-.001c.094-.25.047-1.032-.5-1.454c-.437-.337-1.105-.184-1.355-.07");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llo96eq-p {
  d: path("M17.568 10.277a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.793-.235-2.545-1.589-3.592c-1.381-1.07-2.68-1.258-4.203-1.258h-.39c-.157 1.285.25 2.193.606 2.671");
}

.lrsiznbuc {
  stop-color: var(--svg-color--623f8d, #623F8D);
  stop-opacity: 0;
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.m0m5thktx {
  stop-color: var(--svg-color--572cad, #572CAD);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meew3122p {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m15.117 4.171l-.637.117a.307.307 0 1 1-.055-.61h1.045c.618 0 .822.624.847.836a1.4 1.4 0 0 0-1.2-.343");
}

.mt1ylgber {
  d: path("M11.77 5.474h.006l-.004-.118l-.005-.137c.01-.424.257-.588.362-.642l.023-.01l.023-.009c.238-.109.43-.3.53-.55l.037-.087a.118.118 0 0 1 .206-.023c.321.469.857.747 1.425.747h1.437c.08 0 .484.039.507.595l-.053 1.372c-.055 1.251-1.032 2.091-2.225 2.091c-1.192 0-2.17-.84-2.225-2.091z");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.n-63dkbfe {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M7.127 13.544c-.941-.284-1.295.01-1.388.119a.375.375 0 1 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n73g--bav {
  d: path("M14.988 5.642c.029.038-.03.085-.098.135s-.118.086-.146.048s.003-.11.07-.16c.068-.05.146-.06.174-.023");
}

.nb49g6u5x {
  stop-color: var(--svg-color--8b79ca, #8B79CA);
}

.ngpy26t4k {
  fill-rule: evenodd;
  d: path("M5.25 14.667q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.129.165-.253.27-.354a2.5 2.5 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.37a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.263a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.nng6piu-d {
  stop-color: var(--svg-color--8069a8, #8069A8);
  stop-opacity: 0;
}

.nqqcbvb7z {
  d: path("M11.959 6.517a.48.48 0 1 0 0-.959a.48.48 0 0 0 0 .96");
}

.ns_rnx4db {
  stop-color: var(--svg-color--6845b9, #6845B9);
}

.o-7v_hpgv {
  stop-color: var(--svg-color--9577dc, #9577DC);
}

.o2028dbfw {
  fill: var(--svg-color--553836, #553836);
  d: path("M13.773 2.56c-.506-.112-.96.392-1.012.58c.47 1.582 1.658 1.495 2.83 1.365c.703-.078.779.242.839.397c0-1.756-1.493-2.086-2.644-2.34z");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o8igjrb5x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M14.988 5.642c.029.038-.03.085-.098.135s-.118.086-.146.048s.003-.11.07-.16c.068-.05.146-.06.174-.023");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oda0xdbdw {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m15.709 5.04l-.062.102za.12.12 0 0 1-.123.205l-.003-.001l-.01-.005l-.04-.021a1 1 0 0 0-.153-.06a1 1 0 0 0-.479-.041a.12.12 0 0 1-.041-.236c.229-.04.441 0 .593.049a1.5 1.5 0 0 1 .25.106l.004.003z");
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.of4__9yml {
  stop-color: var(--svg-color--ba917f, #BA917F);
  stop-opacity: 0;
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.omf6kkb4j {
  stop-color: var(--svg-color--9b686d, #9B686D);
  stop-opacity: 0;
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.oz-ci00mm {
  d: path("M13.431 5.91c0-.129-.105-.215-.133-.24l-.129.124l.08.161z");
}

.pfxo1bxwi {
  stop-color: var(--svg-color--bd9484, #BD9484);
  stop-opacity: 0;
}

.pk84u7jjf {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.748H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976s2.062-2.293 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn5jbtt9h {
  d: path("M19.75 29.748H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976s2.062-2.293 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.pzzto25mw {
  stop-color: var(--svg-color--bd9484, #BD9484);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qd_9svrfx {
  d: path("M20.68 13.849c.256-.588.373-1.22.399-1.462l2.047.024c.046.268-.04.583-.079.703c.088.322.037.687 0 .829c-.054.225-.178.713-.238.86c-.074.183-.183.246-.348.23a.4.4 0 0 1-.148-.043a.3.3 0 0 0-.23-.018a.43.43 0 0 1-.227.018a.43.43 0 0 1-.204-.112a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.004a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.07c-.085.007-.183.002-.235-.042c-.098-.082-.219-.175.031-.746");
}

.qe-ha1b7i {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M5.404 14.139s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284c-.11.089-.234.211-.296.355a.375.375 0 0 0 .685.306");
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qocy9nbod {
  d: path("M13.773 2.56c-.506-.112-.96.392-1.012.58c.47 1.582 1.658 1.495 2.83 1.365c.703-.078.779.242.839.397c0-1.756-1.493-2.086-2.644-2.34z");
}

.qosi95ahb {
  stop-color: var(--svg-color--9577dc, #9577DC);
  stop-opacity: 0;
}

.qtb8wgbxo {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.11 5.437c.292 0 .538.2.605.473a.122.122 0 0 1-.12.152H14.6a.103.103 0 0 1-.101-.122a.624.624 0 0 1 .612-.503");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r8fjj8bcd {
  d: path("M26.485 24.332c.981-2.278.626-3.886.055-5.013c-.474-.936-.003-1.662 1.018-1.421c.737.174 1.364.694 1.54 1.431c.721 3.025-.313 6.182-3.582 7.816c-2.95 1.475-7.854 1.594-9.937 1.469c3 0 9.804-1.723 10.906-4.282");
}

.rjhj4ebho {
  stop-color: var(--svg-color--572cad, #572CAD);
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rqh0k2bpm {
  stop-color: var(--svg-color--6f43ac, #6F43AC);
  stop-opacity: 0;
}

.rrk9g0i-o {
  cx: 12.947px;
  cy: 5.729px;
  rx: 0.174px;
  ry: 0.088px;
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.sf2boes3b {
  d: path("m23.469 25.327l-.422-1.143l-2.351.536l2.225 1.1a.396.396 0 0 0 .547-.493");
}

.sgu32ab0w {
  d: path("M19.837 23.012a29 29 0 0 1-.907-.867l1.867-.883c.075.131.51.8.72 1.117z");
}

.siwrhab8g {
  d: path("M16.782 13.45c-.65-1.28-1.166-3.185-1.443-4.423a.714.714 0 0 1 .588-.856c.447-.075.855.271.91.722c.205 1.698.95 3.373 1.445 4.682c.578 1.531.312 1.062.234 3.515c-.057 1.782 1.266 3.25 1.813 4.11l-.407.21c-.609-.827-2.203-2.945-2.203-4.85c0-1.792.063-1.141-.937-3.11");
}

.sk9mj8t1w {
  d: path("M15.018 5.558a.398.398 0 0 1 .384.504h-.77a.4.4 0 0 1 .386-.504");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.sz7_smkrr {
  stop-color: var(--svg-color--6f43ac, #6F43AC);
}

.szw4sibdg {
  stop-color: var(--svg-color--c5a18a, #C5A18A);
}

.t_t1uhgaw {
  stop-color: var(--svg-color--8463ce, #8463CE);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tn---htwd {
  stop-color: var(--svg-color--593b9d, #593B9D);
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.toe447tsm {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.809px;
  rx: 0.299px;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.tuwn6jbrs {
  d: path("M16.198 6.517a.48.48 0 1 0 0-.959a.48.48 0 0 0 0 .96");
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.uh8iu31tc {
  cx: 28.864px;
  cy: 12.813px;
  r: 1.043px;
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.unss9nbst {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.042 7.338a1.35 1.35 0 0 1-.634-.154c-.063-.033-.13.04-.091.098a.863.863 0 0 0 1.45 0c.04-.06-.027-.13-.09-.098c-.184.098-.4.154-.635.154Z");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.uu7g49bxq {
  fill: var(--svg-color--000, #000);
  d: path("M14.79 5.957c0-.127.1-.228.228-.228a.227.227 0 0 1 .202.333h-.403a.2.2 0 0 1-.028-.105");
}

.v0zmloa0d {
  d: path("M11.95 6.756a.718.718 0 1 0 0-1.437a.718.718 0 0 0 0 1.437");
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v74acaceo {
  d: path("m13.872 5.877l-.238.759a.24.24 0 0 0 .233.312h.35a.24.24 0 0 0 .233-.312l-.237-.76c-.05-.168-.288-.168-.341 0");
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vqsxzubiu {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.526 5.244l-.002.001a.12.12 0 0 1-.124-.205h.001l.001-.001l.005-.003l.014-.008l.052-.026c.044-.021.107-.048.183-.072a1.25 1.25 0 0 1 .593-.05a.12.12 0 0 1-.042.237c-.178-.032-.349 0-.478.04a1 1 0 0 0-.194.082z");
}

.vurnokzna {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M5.611 14.945a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14c-.09.053-.163.111-.215.164a.5.5 0 0 0-.074.089");
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
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

.wlohty-lv {
  stop-color: var(--svg-color--6247a5, #6247A5);
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wqensyb5w {
  stop-color: var(--svg-color--8d5050, #8D5050);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wvwy8egxn {
  fill-rule: evenodd;
  d: path("M5.611 14.945a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14c-.09.053-.163.111-.215.164a.5.5 0 0 0-.074.089");
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xf-olmy6i {
  stop-color: var(--svg-color--9a7ce0, #9A7CE0);
}

.xlifj_bsk {
  fill-rule: evenodd;
  d: path("M17.25 6.667a1.46 1.46 0 0 0 .025-1.22h.003a1.4 1.4 0 0 0-.126-.229v-.001a1.45 1.45 0 0 1-.236-.791v-.004c0-.814-.66-1.474-1.473-1.474a.24.24 0 0 1-.203-.103a1.476 1.476 0 0 0-2.395 0a.25.25 0 0 1-.203.103h-.038a1.473 1.473 0 0 0-1.435 1.474v.004c0 .28-.082.556-.236.79v.002a1.47 1.47 0 0 0-.099 1.45a.23.23 0 0 1 0 .203a1.435 1.435 0 0 0 1.292 2.065h3.832a1.435 1.435 0 0 0 1.293-2.065a.23.23 0 0 1 0-.204m-5.474-1.193h-.005l.535 1.052c.055 1.251.544 0 1.736 0c1.193 0 1.713 1.393 1.768.141l.507-1.427c-.023-.556-.426-.595-.507-.595h-1.437a1.73 1.73 0 0 1-1.424-.747a.118.118 0 0 0-.206.023l-.037.086a1.03 1.03 0 0 1-.577.57c-.105.054-.353.218-.362.642l.005.137z");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xtqzqnbwf {
  stop-color: var(--svg-color--c9a38e, #C9A38E);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xy8jbrbcm {
  fill-rule: evenodd;
  d: path("M5.404 14.139s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284c-.11.089-.234.211-.296.355a.375.375 0 0 0 .685.306");
}

.xzkoa2bwe {
  d: path("M10.684 11.696c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.032c.3-.028 1.148-.11 2.5-.72c1.679-.756 2.458-1.803 2.64-2.245l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.y-2lu0bml {
  fill-rule: evenodd;
  d: path("M7.127 13.544c-.941-.284-1.295.01-1.388.119a.375.375 0 1 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y79whbcii {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("m21.985 27.333l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.z0pxpnkbw {
  d: path("m21.985 27.333l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.zc5clpb8v {
  fill: var(--svg-color--000, #000);
  d: path("M13.295 5.957a.227.227 0 0 0-.228-.228a.227.227 0 0 0-.203.333h.404a.2.2 0 0 0 .027-.105");
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zhpuq6bwb {
  stop-color: var(--svg-color--623f8d, #623F8D);
}

.zsn7xn-yh {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M16.198 6.517a.48.48 0 1 0 0-.959a.48.48 0 0 0 0 .96");
}

</style>
