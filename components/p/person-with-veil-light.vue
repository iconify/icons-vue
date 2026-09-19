<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iirqIYH)"><path fill="url(#iGbkieW)" class="d-spvtb4l"/><path fill="url(#iXR4Reb)" class="d-spvtb4l"/><path fill="url(#ik2liTd)" class="d-spvtb4l"/></g><g filter="url(#ihfluzc)"><path fill="url(#iEcCtRd)" class="rw21-0q9v"/></g><path fill="url(#i8vJPJR)" class="cujr0sbrc"/><path fill="url(#iIV2KVJ)" class="cujr0sbrc"/><path fill="url(#ickTg7I)" class="cujr0sbrc"/><path fill="url(#i1okksJ)" class="cujr0sbrc"/><g filter="url(#ibjL62c)"><path class="i6ihwdjck"/></g><g filter="url(#i1hntSd)"><path class="ya17bcw5b"/></g><g filter="url(#iGZ5Fmb)"><path fill="url(#i9hkzQc)" class="ablqfeb3v"/><path fill="url(#ileyhld)" class="ablqfeb3v"/><path fill="url(#i3szJUd)" class="ablqfeb3v"/></g><g filter="url(#iMLl1oc)"><path fill="url(#imwcmYb)" class="ayk-bvndi"/><path fill="url(#iOoZOvc)" class="ayk-bvndi"/><path fill="url(#iSgKhye)" class="ayk-bvndi"/></g><g filter="url(#iQdwOlb)"><path fill="url(#inv0Uwd)" class="yiubpvbej"/><path fill="url(#iUyFYlb)" class="yiubpvbej"/><path fill="url(#iRA3xTc)" class="yiubpvbej"/><path fill="url(#iozwt1c)" class="yiubpvbej"/><path fill="url(#iR3OlUb)" class="yiubpvbej"/></g><path fill="url(#iaVvAYD)" class="ypl5194yo"/><path fill="url(#i8SRwGd)" class="ypl5194yo"/><g filter="url(#i1sJbuv)"><path class="h_s96xi5w"/></g><g filter="url(#iqlDpgc)"><path fill="url(#iUzOOzc)" class="n-_v94bpq"/><path fill="url(#iIDlZAb)" class="n-_v94bpq"/></g><g filter="url(#i5dLozd)"><path fill="url(#ifCbFdV)" class="sxixn7bkv"/><path fill="url(#i9SyZGk)" class="sxixn7bkv"/></g><circle fill="url(#iYjn4Bl)" class="d1hy5_7ji"/><circle fill="url(#iQ8x29b)" class="d1hy5_7ji"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.302)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.302)" class="movji7bnz"/><circle fill="url(#iUAdRbd)" class="mnl6j-bsb"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.36)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.36)" class="movji7bnz"/><path fill="url(#iv49KXs)" class="x-uo0zbag"/><g filter="url(#iltIqyd)"><path class="c00rrsbjk"/><path fill="url(#izVgAOd)" class="in-cf_bxb"/><path fill="url(#i2YXaTd)" class="in-cf_bxb"/><path fill="url(#ixyTOdc)" class="in-cf_bxb"/><path fill="url(#iJDkswb)" class="in-cf_bxb"/><path fill="url(#iKCdyfd)" class="in-cf_bxb"/></g><path fill="url(#iM3SyZb)" class="xqpun5kuz"/><g filter="url(#i3kjXae)"><path class="aqqlzundh"/><path fill="url(#i3gMsKe)" class="rfljnn3cw"/><path fill="url(#iI24l8d)" class="rfljnn3cw"/></g><g filter="url(#iXi7yUd)"><path class="ruxo04blp"/><path fill="url(#iUn2hcd)" class="pcv4-9l7i"/><path fill="url(#i1pXntM)" class="pcv4-9l7i"/><path fill="url(#ijpgsKd)" class="pcv4-9l7i"/><path fill="url(#iYqUD8b)" class="pcv4-9l7i"/><path fill="url(#i34eg8b)" class="pcv4-9l7i"/></g><g filter="url(#il3KaGc)"><path fill="url(#iajBQDO)" clip-rule="evenodd" class="b-8danbqt"/></g><g filter="url(#iQ70u3b)"><path class="x2zcceb4i"/></g><g filter="url(#iW4nYqe)"><path fill="url(#iXnn0Zb)" class="k2cf33bae"/><path fill="url(#iWkSbDd)" class="k2cf33bae"/></g><g filter="url(#ia0Orrd)"><path stroke="url(#iqHzsbe)" class="c_x-a9uxs"/></g><g filter="url(#iaMuRkb)"><path stroke="url(#izO0RmF)" class="rdwxb6bhu"/></g><g filter="url(#ikiuqqb)"><path stroke="url(#iVB6wGe)" class="f69b65b_h"/></g><g filter="url(#itj6rJd)"><path stroke="url(#iIMpfcU)" class="zji4bqm-z"/></g><path fill="url(#iCzkvzd)" class="x3hrjzb3d"/><path fill="url(#iJ8liob)" class="xuk244bgc"/><g filter="url(#i6oLGxc)"><path fill="url(#iqac2bc)" class="ofmdqub2l"/></g><path fill="url(#iTiLF1c)" class="ofmdqub2l"/><path fill="url(#iJIdS7d)" class="ofmdqub2l"/><path fill="url(#ishqXGe)" class="ofmdqub2l"/><path fill="url(#iwCDMHd)" class="ofmdqub2l"/><path fill="url(#iwHIpze)" class="ofmdqub2l"/><path fill="url(#iHz2hHc)" class="ofmdqub2l"/><path fill="url(#ioa4dqc)" class="ofmdqub2l"/><g filter="url(#i8rXT3b)"><path class="nut600bmt"/></g><g filter="url(#iHjr1lm)"><path class="cs0eoq8od"/><path fill="url(#iYzZSvc)" class="q2gg96pcn"/><path fill="url(#iO8HtPb)" class="q2gg96pcn"/><path fill="url(#iodnF0b)" class="q2gg96pcn"/><path fill="url(#i4ruWue)" class="q2gg96pcn"/></g><g filter="url(#iEgCaqe)"><path fill="url(#isHL1hc)" class="wdv_n9bkr"/></g><g filter="url(#iLru2Ic)"><path stroke="url(#iD8Ylqc)" class="y_jkek1zy"/></g><path fill="url(#iarX5LM)" class="qglaym30m"/><g filter="url(#iKKsswe)"><path fill="url(#iHBJ9cc)" class="r5vo0kbfr"/><path fill="url(#ivebl0x)" class="r5vo0kbfr"/><path fill="url(#ipaE3re)" class="r5vo0kbfr"/><path fill="url(#ixicu0b)" class="r5vo0kbfr"/><path fill="url(#iB3YGRp)" class="r5vo0kbfr"/></g><g filter="url(#iZPCRRb)"><path class="w8_cgvdqm"/></g><g filter="url(#iPOJJZb)"><path class="du9lm-46v"/></g><g filter="url(#iim1nmb)"><path class="s3kmhfnih"/><path fill="url(#iuLgone)" class="erlkjr5sa"/><path fill="url(#idGwReb)" class="erlkjr5sa"/></g><g filter="url(#iOcgx4b)"><path class="zqhrzdlkb"/><path fill="url(#i3JzemC)" class="z7btlk2or"/><path fill="url(#iUoapnd)" class="z7btlk2or"/><path fill="url(#iqxtide)" class="z7btlk2or"/></g><path class="zdt7j3bwy"/><path fill="url(#ibno6ne)" class="rfl_fn8on"/><path class="c6b3ts1qn"/><g filter="url(#idBALOe)"><path class="nq5w1nb_l"/><path fill="url(#iKN7mab)" class="plvl9topq"/></g><g filter="url(#iWm5XGb)"><path fill="url(#iCixzSc)" class="ci4b-fbaa"/></g><path class="dpugscc0h"/><path fill="url(#iKcx1pg)" class="w7ub773oj"/><path class="o9o2rpb7q"/><g filter="url(#ia3NwVc)"><path fill="url(#ig3wKYQ)" class="u_fm1ybae"/></g><g filter="url(#ioPODec)"><ellipse transform="rotate(-27.914 13.467 9.999)" class="vj9ki-bgq"/><ellipse fill="url(#iIGwmVb)" transform="rotate(-27.914 13.467 9.999)" class="oo5a1_dee"/></g><path fill="url(#iA34hRd)" class="y0ui976-o"/><path fill="url(#ijAnuHd)" class="y0ui976-o"/><path fill="url(#ikHvxIc)" class="y0ui976-o"/><path fill="url(#iMgnlQb)" class="y0ui976-o"/><path fill="url(#inZQEdc)" class="upsminbrl"/><path fill="url(#iB2a5GC)" class="upsminbrl"/><g filter="url(#i25E3rc)"><path fill="url(#i4JniBe)" class="racr4kz8s"/></g><g filter="url(#i928FCc)"><path fill="url(#iyhUQnC)" class="yqtvzp8fc"/></g><g filter="url(#iW12L6b)"><path class="v62n-db7t"/></g><g filter="url(#ig3d25b)"><path class="h224et-kr"/></g><g filter="url(#iYX6Hwc)"><path fill="url(#ik1wZAd)" clip-rule="evenodd" class="d28eaq2-z"/><path fill="url(#ifJ6gre)" clip-rule="evenodd" class="d28eaq2-z"/></g><defs><radialGradient id="iXR4Reb" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.806 6.967)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="ik2liTd" cx="0" cy="0" r="1" gradientTransform="matrix(6.93747 -5.37505 4.67308 6.03145 5.7 25.525)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="i8vJPJR" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.164 15.68)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="ickTg7I" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 27.9)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i1okksJ" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.056)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="ileyhld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.694)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="i3szJUd" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.65 14.576)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iOoZOvc" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.762 27.195)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="iSgKhye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.759)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="inv0Uwd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.95206 -2.46677 3.46444 -9.76378 21.531 21.477)" gradientUnits="userSpaceOnUse"><stop class="mt5e72-yt"/><stop offset="1" class="i_w-uabpc"/></radialGradient><radialGradient id="iUyFYlb" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.729 16.526)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="l3byadclu"/><stop offset="1" class="u-l7gqbnl"/></radialGradient><radialGradient id="iRA3xTc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.10937 .98438 -.41833 -1.3214 16.117 16.551)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="nhvn8xbgd"/><stop offset="1" class="vt544m69k"/></radialGradient><radialGradient id="iozwt1c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07223 -.6455 .5202 -.8641 22.585 20.7)" gradientUnits="userSpaceOnUse"><stop class="cyqt__gil"/><stop offset="1" class="yvysc04cm"/></radialGradient><radialGradient id="iR3OlUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.96875 -.73075 0 14.117 16.543)" gradientUnits="userSpaceOnUse"><stop class="rb6miyacc"/><stop offset="1" class="onrup1btv"/></radialGradient><radialGradient id="iaVvAYD" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.538 35.831)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="iIDlZAb" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.072 4.857)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="i9SyZGk" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.196)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="iYjn4Bl" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.334 11.746)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="iQ8x29b" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.374 14.541)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="iUAdRbd" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.371 12.602)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="iv49KXs" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.289 19.312)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="izVgAOd" cx="0" cy="0" r="1" gradientTransform="matrix(1.56458 3.75 -.74545 .31102 12.95 20.9)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="i2YXaTd" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21875 -.15017 .24383 9.481 22.9)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="ixyTOdc" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.142 9.168)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iJDkswb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.279 24.697)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="iKCdyfd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.477)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="iM3SyZb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.696)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="i3gMsKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.602)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="iI24l8d" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.616)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iUn2hcd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.18)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="i1pXntM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.868)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iajBQDO" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.344 16.58)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iXnn0Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.388 23.743)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iWkSbDd" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.13)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="iCzkvzd" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.748 20.833)scale(2.15387 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iJ8liob" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43156 4.55498 9.864 12.443)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iqac2bc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.46368 0 0 -7.8962 18.729 11.01)" gradientUnits="userSpaceOnUse"><stop class="mzl_h2r6k"/><stop offset="1" class="kvx_ci1ar"/></radialGradient><radialGradient id="iJIdS7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.8501 -10.6414 0 16.421 4.84)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="pizj1wbfb"/><stop offset=".961" class="s5bqomtsm"/></radialGradient><radialGradient id="ishqXGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.368 9.698)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iwCDMHd" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09427 1.19083 .00428 13.62 9.744)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iwHIpze" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49597 .5363 -1.37 -21.7029 19.354 11.999)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iHz2hHc" cx="0" cy="0" r="1" gradientTransform="matrix(5 -4.4375 1.62444 1.83035 8.359 7.534)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="ioa4dqc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74316 2.88295 -2.3801 -1.43912 18.348 6.032)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iO8HtPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.387 12.371)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="i4ruWue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.503 11.801)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iarX5LM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.8997 0 15.92 14.55)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="ivebl0x" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50132 8.85443 0 10.691 8.118)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="ipaE3re" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.324 -6.159)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="ixicu0b" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.485 -1.422)scale(2.82328 2.07243)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iB3YGRp" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09581 15.016 1.56)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iuLgone" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20112 0 0 -.81692 16.174 3.819)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="idGwReb" cx="0" cy="0" r="1" gradientTransform="matrix(3.21816 -5.09543 5.64521 3.5654 10.49 7.761)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="i3JzemC" cx="0" cy="0" r="1" gradientTransform="matrix(3.05838 0 0 1.19577 19.335 4.596)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iUoapnd" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90405 18.555 7.633)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iqxtide" cx="0" cy="0" r="1" gradientTransform="matrix(3.2482 .37966 -.15896 1.35996 17.669 6.156)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ibno6ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.103 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iKN7mab" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.43 .712)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKcx1pg" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.739 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iIGwmVb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.453 10.314)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijAnuHd" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24327 -2.14025 .59968 20.539 10.108)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="ikHvxIc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.899 10.653)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iMgnlQb" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.013 10.825)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iB2a5GC" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.83 5.041)scale(1.62516 1.74453)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="i4JniBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15731 -.19303 -1.12456 11.006 10.752)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="ifJ6gre" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.699 8.535)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="iirqIYH" width="21.944" height="26.818" x="4.962" y="3.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><filter id="ihfluzc" width="12.631" height="14.916" x="9.484" y="8.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/><feGaussianBlur result="effect2_foregroundBlur_4002_3421" stdDeviation=".05"/></filter><filter id="ibjL62c" width="5.874" height="5.537" x="6.993" y="23.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".5"/></filter><filter id="i1hntSd" width="4.98" height="4.054" x="18.51" y="24.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".5"/></filter><filter id="iGZ5Fmb" width="2.973" height="2.006" x="21.47" y="23.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><filter id="iMLl1oc" width="3.281" height="2" x="20.468" y="25.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><filter id="iQdwOlb" width="13.965" height="11.381" x="9.149" y="12.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.623529 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><filter id="i1sJbuv" width="10.996" height="6.432" x="11.932" y="21.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".5"/></filter><filter id="iqlDpgc" width="2.973" height="2.006" x="7.658" y="23.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><filter id="i5dLozd" width="3.266" height="2" x="8.366" y="25.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><filter id="iltIqyd" width="6.218" height="6.789" x="8.343" y="19.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3421" result="effect2_innerShadow_4002_3421"/></filter><filter id="i3kjXae" width="6.218" height="6.639" x="17.574" y="19.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3421" result="effect2_innerShadow_4002_3421"/></filter><filter id="iXi7yUd" width="6.702" height="6.417" x="12.683" y="20.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><filter id="il3KaGc" width="6.703" height="6.517" x="12.633" y="20.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".15"/></filter><filter id="iQ70u3b" width="3.2" height="3.2" x="14.271" y="22.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".25"/></filter><filter id="iW4nYqe" width="2.35" height="2.35" x="14.893" y="22.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><filter id="ia0Orrd" width="1.458" height="2.505" x="15.848" y="20.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".125"/></filter><filter id="iaMuRkb" width="1.723" height="1.924" x="16.94" y="24.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".125"/></filter><filter id="ikiuqqb" width="1.368" height="2.217" x="18.104" y="22.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".125"/></filter><filter id="itj6rJd" width="3.55" height="1.942" x="15.171" y="17.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".25"/></filter><filter id="i6oLGxc" width="11.22" height="12.542" x="10.858" y="4.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3421" result="effect2_innerShadow_4002_3421"/></filter><filter id="i8rXT3b" width="3.747" height="4.9" x="13.905" y="9.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".5"/></filter><filter id="iHjr1lm" width="2.277" height="3.3" x="14.782" y="9.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".1"/></filter><filter id="iEgCaqe" width="2.277" height="3.3" x="14.782" y="9.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".1"/></filter><filter id="iLru2Ic" width="3.718" height="1.573" x="14.062" y="13.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".05"/></filter><filter id="iKKsswe" width="12.873" height="8.356" x="9.484" y="1.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3421" result="effect2_innerShadow_4002_3421"/></filter><filter id="iZPCRRb" width="2.339" height="1.19" x="17.51" y="7.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><filter id="iPOJJZb" width="2.339" height="1.176" x="12.254" y="7.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><filter id="iim1nmb" width="6.734" height="5.992" x="9.84" y="2.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/><feGaussianBlur result="effect2_foregroundBlur_4002_3421" stdDeviation=".125"/></filter><filter id="iOcgx4b" width="6.361" height="5.736" x="15.762" y="3.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".125"/></filter><filter id="idBALOe" width=".787" height=".696" x="17.369" y="9.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".05"/></filter><filter id="iWm5XGb" width=".891" height=".913" x="18.209" y="9.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".1"/></filter><filter id="ia3NwVc" width=".986" height="1.04" x="13.766" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".1"/></filter><filter id="ioPODec" width=".913" height=".704" x="13.011" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".05"/></filter><filter id="i25E3rc" width="1.329" height="2.379" x="9.84" y="9.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".125"/></filter><filter id="i928FCc" width="1.947" height="2.903" x="20.427" y="9.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".25"/></filter><filter id="iW12L6b" width="2.205" height=".961" x="12.273" y="7.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".1"/></filter><filter id="ig3d25b" width="2.205" height=".961" x="17.552" y="7.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3421" stdDeviation=".1"/></filter><filter id="iYX6Hwc" width="15.448" height="4.54" x="8.283" y="2.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3421"/></filter><linearGradient id="iGbkieW" x1="26.906" x2="11.7" y1="11.399" y2="21.399" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="iEcCtRd" x1="20.7" x2="10.387" y1="17.305" y2="17.305" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iIV2KVJ" x1="14.887" x2="14.887" y1="30.775" y2="29.493" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="i9hkzQc" x1="23.649" x2="21.867" y1="25.697" y2="24.286" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="imwcmYb" x1="22.95" x2="21.169" y1="27.281" y2="25.587" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="i8SRwGd" x1="12.653" x2="13.255" y1="29.165" y2="28.821" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="iUzOOzc" x1="7.856" x2="9.361" y1="24.18" y2="26" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="ifCbFdV" x1="9.062" x2="10.843" y1="27.28" y2="25.595" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="ijpgsKd" x1="14.919" x2="16.7" y1="27.044" y2="22.775" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iYqUD8b" x1="13.356" x2="16.981" y1="22.806" y2="23.493" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="i34eg8b" x1="17.231" x2="16.325" y1="26.806" y2="25.056" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iqHzsbe" x1="16.477" x2="16.477" y1="20.727" y2="22.735" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="izO0RmF" x1="17.286" x2="18.153" y1="24.782" y2="25.985" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="iVB6wGe" x1="18.728" x2="18.728" y1="22.314" y2="23.931" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iIMpfcU" x1="16.132" x2="20.117" y1="18.926" y2="17.754" gradientUnits="userSpaceOnUse"><stop class="s_ql7obry"/><stop offset="1" class="zpmzd2b_c"/></linearGradient><linearGradient id="iTiLF1c" x1="21.078" x2="16.725" y1="12.696" y2="12.696" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iYzZSvc" x1="16.759" x2="15.921" y1="11.685" y2="11.72" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iodnF0b" x1="15.921" x2="15.921" y1="12.824" y2="12.359" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="isHL1hc" x1="15.921" x2="15.921" y1="9.804" y2="11.254" gradientUnits="userSpaceOnUse"><stop class="r3uzy6bze"/><stop offset="1" class="xkgsg_3yf"/></linearGradient><linearGradient id="iD8Ylqc" x1="14.719" x2="15.037" y1="14.395" y2="13.56" gradientUnits="userSpaceOnUse"><stop class="lnp00kbuv"/><stop offset="1" class="km3-rt7bh"/></linearGradient><linearGradient id="iHBJ9cc" x1="22.773" x2="11.161" y1="5.348" y2="5.348" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iCixzSc" x1="18.881" x2="18.567" y1="10.148" y2="10.342" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ig3wKYQ" x1="14.483" x2="14.169" y1="10.148" y2="10.342" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iA34hRd" x1="22.357" x2="21.15" y1="10.175" y2="12.351" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="inZQEdc" x1="10.071" x2="11.529" y1="10.879" y2="10.752" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iyhUQnC" x1="21.4" x2="21.4" y1="9.804" y2="11.707" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="ik1wZAd" x1="20.481" x2="8.544" y1="3.555" y2="7.243" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-veil-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.ablqfeb3v {
  d: path("M21.48 25.199c.063-.898.843-1.586 1.721-1.535l.99.06c.121 0 .162.157.149.206c-.176.967-.961 1.703-2 1.633l-.768-.097a.11.11 0 0 1-.102-.118z");
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.aqqlzundh {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.665c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.183l-.754 1.63c-.044.108-.088.205-.132.312c-.111.292-.303.839-.336 1.135c-.152 1.231.46 2.09 1.43 2.537c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ayk-bvndi {
  d: path("M20.61 25.712c.678-.6 1.716-.535 2.297.112l.69.734c.063.068.083.205-.023.271c-.91.563-1.996.492-2.66-.27l-.42-.584a.11.11 0 0 1 .009-.15z");
}

.b-8danbqt {
  fill-rule: evenodd;
  d: path("M13.709 24.24a.913.913 0 0 1-.753-1.107a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.303l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.561a.3.3 0 0 0 .396.284l.551-.187l.007-.003c.516-.193 1.023.047 1.16.56c.14.531-.183 1.092-.687 1.183l-.466.102a.3.3 0 0 0-.178.47l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.384l-.005.008a.91.91 0 0 1-1.294.33l-.001-.002a.92.92 0 0 1-.227-1.335l.005-.007l.362-.533a.3.3 0 0 0-.196-.464l-.369-.066z");
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c_x-a9uxs {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 20.93c.324 0 .758.377.758.86v.945");
}

.c00rrsbjk {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.665c-.076-.155-.018-.354.098-.418c.854-.404 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.183l.753 1.63l.133.312c.111.292.303.839.336 1.135c.152 1.231-.46 2.09-1.43 2.537c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.c6b3ts1qn {
  fill: var(--svg-color--000, #000);
  d: path("M17.594 10.51c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ci4b-fbaa {
  d: path("M18.9 10.392a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.cs0eoq8od {
  fill: var(--svg-color--f5c0a8, #F5C0A8);
  d: path("m15.539 10.296l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.765 0");
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cujr0sbrc {
  d: path("M27 29.837v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.462 5 23.637 5 28.837v1z");
}

.cyqt__gil {
  stop-color: var(--svg-color--f3ba97, #F3BA97);
}

.d-spvtb4l {
  d: path("M5.062 16.337c0-8.813 4.89-13.219 10.922-13.219s10.922 4.219 10.922 13.219v13.5H5.062z");
}

.d1hy5_7ji {
  cx: 9.168px;
  cy: 20.404px;
  r: 0.762px;
}

.d28eaq2-z {
  fill-rule: evenodd;
  d: path("M15.972 4.268c-3.812 0-5.694 1.656-6.334 2.379a.775.775 0 0 1-1.16-1.027c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.915 7.54 2.876A.775.775 0 1 1 22.4 6.673c-.735-.757-2.556-2.405-6.428-2.405");
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dpugscc0h {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.53 9.346c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.du9lm-46v {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.51 7.922a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.068.551a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.erlkjr5sa {
  d: path("m16.153 5.395l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.179.33-.253q.047-.046.1-.104c.35-.371.973-1.032 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892v1.485z");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f69b65b_h {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.478c.307.135.83.615.461 1.453");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.h_s96xi5w {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.313c.096.053.144.219.081.348l-.668 1.39c-.181.388-.526.926-.809 1.177c-.687.638-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.325-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.003l-.201.312a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.415l.298-.438a.042.042 0 0 0-.027-.064l-.308-.056a.97.97 0 0 1-.799-1.173a.97.97 0 0 1 1.248-.708l.516.176a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.664.81-1.062v.467c0 .028.028.048.055.04l.458-.157q.112-.041.223-.057l.036-.085l1.043.854c.063-.13.19-.198.295-.152c.711.327.494-.417.288.728c-.022.122.015.129.098.029c.74-.9 1.97-1.695 2.682-1.36");
}

.h224et-kr {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.482 8.155c-.257-.184-.898-.508-1.655-.381");
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.i_w-uabpc {
  stop-color: var(--svg-color--efb59b, #EFB59B);
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i6ihwdjck {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.049c.879-.052 1.658.636 1.72 1.534l.009.116c.31.043.61.174.862.397l.107.113a.11.11 0 0 1 .01.15l-.42.583c-.665.762-1.75.833-2.66.27c-.064-.05-.086-.202-.024-.27l.69-.734q.136-.152.302-.26c-.906-.06-1.574-.75-1.735-1.634c-.013-.049.028-.207.15-.207z");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.in-cf_bxb {
  d: path("M8.528 22.665c-.076-.155-.018-.354.098-.418c.854-.404 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.183l.753 1.63l.133.312c.111.292.303.839.336 1.135c.152 1.231-.46 2.09-1.43 2.537c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.k2cf33bae {
  d: path("M15.993 25.13a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.km3-rt7bh {
  stop-color: var(--svg-color--eebbb1, #EEBBB1);
  stop-opacity: 0;
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.kvx_ci1ar {
  stop-color: var(--svg-color--e1ac9b, #E1AC9B);
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l3byadclu {
  stop-color: var(--svg-color--eaa28f, #EAA28F);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnp00kbuv {
  stop-color: var(--svg-color--eebbb1, #EEBBB1);
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mnl6j-bsb {
  cx: 10.18px;
  cy: 21.482px;
  r: 0.762px;
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mt5e72-yt {
  stop-color: var(--svg-color--ffd4b8, #FFD4B8);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.mzl_h2r6k {
  stop-color: var(--svg-color--ffddbf, #FFDDBF);
}

.n-_v94bpq {
  d: path("M10.52 25.199c-.063-.898-.843-1.586-1.721-1.535l-.99.06c-.121 0-.162.157-.149.206c.176.967.961 1.703 2 1.633l.768-.097a.11.11 0 0 0 .102-.118z");
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nhvn8xbgd {
  stop-color: var(--svg-color--e19584, #E19584);
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.nq5w1nb_l {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.04 9.806c.063.085-.07.19-.221.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.05");
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.nut600bmt {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.52 10.487l-.591 1.838c-.101.379.14.757.484.757h.732c.343 0 .585-.384.484-.757l-.494-1.838c-.106-.407-.505-.407-.616 0");
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.o9o2rpb7q {
  fill: var(--svg-color--000, #000);
  d: path("M14.248 10.51a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofmdqub2l {
  d: path("M11.096 13.776a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.onrup1btv {
  stop-color: var(--svg-color--eea990, #EEA990);
  stop-opacity: 0;
}

.oo5a1_dee {
  cx: 13.467px;
  cy: 9.999px;
  rx: 0.39px;
  ry: 0.197px;
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcv4-9l7i {
  d: path("M12.712 23.077c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pizj1wbfb {
  stop-color: var(--svg-color--e1a39f, #E1A39F);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plvl9topq {
  d: path("M18.04 9.806c.063.085-.07.19-.221.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.05");
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q2gg96pcn {
  d: path("m15.539 10.296l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.765 0");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qglaym30m {
  d: path("M15.92 13.907c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.086-.13-.06-.278-.198-.209a3 3 0 0 1-1.385.329");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r3uzy6bze {
  stop-color: var(--svg-color--ebbca6, #EBBCA6);
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.r5vo0kbfr {
  d: path("M20.776 4.368c.514.177.976.536 1.267 1.05a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.079-1.606a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379l.03 1.537c-.254.037-.52.122-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875A2.39 2.39 0 0 1 9.754 5.5a2.35 2.35 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.843 0 1.58.456 1.99 1.132c.307.51.79.88 1.352 1.073");
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.racr4kz8s {
  d: path("M10.835 9.813a.956.956 0 0 0 .084 1.879a78 78 0 0 1-.084-1.88");
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rb6miyacc {
  stop-color: var(--svg-color--eea990, #EEA990);
}

.rdwxb6bhu {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.696l.907 1.18");
}

.rfl_fn8on {
  d: path("M18.105 9.617a.892.892 0 0 1 .86 1.128H17.24a.896.896 0 0 1 .864-1.128");
}

.rfljnn3cw {
  d: path("M23.457 22.665c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.183l-.754 1.63c-.044.108-.088.205-.132.312c-.111.292-.303.839-.336 1.135c-.152 1.231.46 2.09 1.43 2.537c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruxo04blp {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.077c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.rw21-0q9v {
  d: path("M9.984 15.76c0-4.855 2.694-7.281 6.016-7.281s6.016 2.323 6.016 7.28v7.436H9.984z");
}

.s_ql7obry {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
}

.s3kmhfnih {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.153 5.395l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.179.33-.253q.047-.046.1-.104c.35-.371.973-1.032 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892v1.485z");
}

.s5bqomtsm {
  stop-color: var(--svg-color--dc9082, #DC9082);
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxixn7bkv {
  d: path("M11.39 25.712c-.678-.6-1.716-.535-2.298.112l-.69.734c-.062.068-.04.22.024.27c.91.563 1.996.493 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u_fm1ybae {
  d: path("M14.552 10.405c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.u-l7gqbnl {
  stop-color: var(--svg-color--eaa28f, #EAA28F);
  stop-opacity: 0;
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.upsminbrl {
  d: path("M10.876 9.151a1.62 1.62 0 0 0-1.392 1.594c0 .86.674 1.561 1.521 1.607a78 78 0 0 1-.129-3.2");
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v62n-db7t {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.548 8.201c.257-.184.897-.508 1.655-.381");
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vj9ki-bgq {
  cx: 13.467px;
  cy: 9.999px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vt544m69k {
  stop-color: var(--svg-color--e19584, #E19584);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w7ub773oj {
  d: path("M13.737 9.617a.893.893 0 0 0-.86 1.128H14.6a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.w8_cgvdqm {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.654 8.031a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.058.776-.028.978.036c.199.062.333.164.49.3a.277.277 0 1 0 .365-.418");
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wdv_n9bkr {
  d: path("m15.539 10.11l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x-uo0zbag {
  d: path("m11.186 26.206l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.191-.717.058-.797.238c-.3.82-.081 2.137.085 3.002z");
}

.x2zcceb4i {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.262a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.x3hrjzb3d {
  d: path("M20.782 12.26c.335-.01.65-.124.905-.308v.931c0 .893-.533 1.689-1.341 2.02q.256-.547.346-1.18z");
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xkgsg_3yf {
  stop-color: var(--svg-color--ebbca6, #EBBCA6);
  stop-opacity: 0;
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xqpun5kuz {
  d: path("m20.799 26.206l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.191.718.058.798.238c.3.82.081 2.137-.085 3.002z");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xuk244bgc {
  d: path("M11.06 12.26a1.64 1.64 0 0 1-.905-.308v.931c0 .893.532 1.689 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.y_jkek1zy {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.57 13.512a.23.23 0 0 0-.272.046a.21.21 0 0 0-.023.271c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.045h-.002c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.351-.32Z");
}

.y0ui976-o {
  d: path("M20.843 12.351q.1-1.596.184-3.19a1.61 1.61 0 0 1-.184 3.19");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.ya17bcw5b {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.878c.78-.46 1.787-.2 2.235.545l.538.852c.048.078.043.217-.074.261c-1 .38-2.053.105-2.561-.77l-.302-.652a.11.11 0 0 1 .037-.145z");
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yiubpvbej {
  d: path("M9.15 20.37a11.2 11.2 0 0 1 4.31-2.048c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.ypl5194yo {
  d: path("M13.196 29.836L10.649 26l5.25-3.476l5.828 2.91l-2.922 4.402z");
}

.yqtvzp8fc {
  d: path("M20.927 11.707q.057-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.yvysc04cm {
  stop-color: var(--svg-color--f3ba97, #F3BA97);
  stop-opacity: 0;
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z7btlk2or {
  d: path("m21.134 8.661l-.03-.63c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.059-.136-.12-.368c-.256-.97.67-1.712 1.656-1.521c.973.188 2.082.517 2.902 1.051c1.744 1.138 1.439 3.189.52 4.154");
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zdt7j3bwy {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.312 9.346c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.127 1.37-1.127");
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zji4bqm-z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.75c.395.01 1.357-.063 2.05-.441");
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zpmzd2b_c {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
  stop-opacity: 0;
}

.zqhrzdlkb {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.134 8.661l-.03-.63c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.059-.136-.12-.368c-.256-.97.67-1.712 1.656-1.521c.973.188 2.082.517 2.902 1.051c1.744 1.138 1.439 3.189.52 4.154");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
