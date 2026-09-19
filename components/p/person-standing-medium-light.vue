<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="gc_nsb79v"/><path fill="url(#iiI6jgb)" class="dhem5bbqc"/><g filter="url(#icqheYc)"><path class="l538fmchy"/><path fill="url(#iZufaLc)" class="a2zxjbcyy"/></g><path class="treq1gbey"/><path fill="url(#isg6Gpb)" class="u78464b_o"/><path fill="url(#iP1SOOe)" class="u78464b_o"/><path class="ta7i6wbki"/><path fill="url(#iSH97bP)" class="gh48jbbhn"/><path fill="url(#i0hUVic)" class="gh48jbbhn"/><path fill="url(#ivKrMAb)" class="gh48jbbhn"/><g filter="url(#iS7GBCe)"><path class="k98skybyf"/></g><path class="er818xpbc"/><path fill="url(#iXI2pNc)" class="bsrto12qr"/><path fill="url(#i7f2jHN)" class="bsrto12qr"/><g filter="url(#iP31Vlb)"><path class="ir-g6pm8n"/></g><path fill="url(#iKWj31d)" class="z9wedib1s"/><path fill="url(#i02Gsmn)" class="z9wedib1s"/><path fill="url(#ilCBvjH)" class="z9wedib1s"/><path fill="url(#iaPOC8b)" class="z9wedib1s"/><g filter="url(#imdKUrC)"><path fill="url(#iEmngAd)" class="h5gec01yx"/><path fill="url(#iopGuPc)" class="h5gec01yx"/></g><path fill="url(#i4SyW8b)" class="ja04_0anf"/><g filter="url(#ixuMawd)"><path class="q7l7dqb4y"/></g><path fill="url(#iaDrApd)" class="kbtpxgecb"/><path fill="url(#ieH8Tse)" class="kbtpxgecb"/><g filter="url(#iJmZRUc)"><path class="sx-yjgb9f"/></g><path fill="url(#itsz0oc)" class="a03mykf9s"/><path fill="url(#iG7njCe)" class="drhu1ybzd"/><path fill="url(#i548PoY)" class="drhu1ybzd"/><path fill="url(#iG7njCe)" class="drhu1ybzd"/><path fill="url(#i548PoY)" class="drhu1ybzd"/><g filter="url(#iQuMqfb)"><path fill="url(#ia8EKad)" class="yhl3rwbtd"/></g><path fill="url(#iN3yr4n)" class="yhl3rwbtd"/><path fill="url(#iudxcRC)" class="yhl3rwbtd"/><path fill="url(#iGkpGtb)" class="yhl3rwbtd"/><path fill="url(#iU1ipLJ)" class="yhl3rwbtd"/><path fill="url(#iErPA1c)" class="yhl3rwbtd"/><path fill="url(#ismqKoc)" class="yhl3rwbtd"/><path fill="url(#iJ5S7jb)" class="yhl3rwbtd"/><path fill="url(#ih0ILOe)" class="yhl3rwbtd"/><g filter="url(#iz8nc1d)"><path class="j0gqqp9fe"/></g><g filter="url(#itl03vd)"><path fill="url(#i2ZbmRc)" class="v1ass0bqn"/><path fill="url(#iloOcyc)" class="v1ass0bqn"/><path fill="url(#ibOJ67b)" class="v1ass0bqn"/><path fill="url(#i7uJwOb)" class="v1ass0bqn"/></g><g filter="url(#i7I9efe)"><path stroke="url(#i7b4m5r)" class="nb3czznun"/></g><path fill="url(#in6ud0c)" class="as_wp7bxb"/><g filter="url(#i21Ized)"><path fill="url(#i5jnvEd)" class="lpu_bb7zv"/><path fill="url(#iafxXrd)" class="lpu_bb7zv"/><path fill="url(#igYuoYw)" class="lpu_bb7zv"/><path fill="url(#iykRiye)" class="lpu_bb7zv"/><path fill="url(#iDlCqEb)" class="lpu_bb7zv"/></g><g filter="url(#i0Jj4jb)"><path class="nc8x04b8h"/></g><g filter="url(#ibhK8ac)"><path class="flylnfw7h"/></g><g filter="url(#iTmJNKy)"><path fill="url(#iBCspEe)" class="l4sfebcir"/><path fill="url(#iTuTYfc)" class="l4sfebcir"/></g><g filter="url(#iCw4Cqd)"><path fill="url(#iBjoiud)" class="fxlb6obqg"/><path fill="url(#ilO4Qtd)" class="fxlb6obqg"/><path fill="url(#ifpXFzc)" class="fxlb6obqg"/><path fill="url(#iFG4IFs)" class="fxlb6obqg"/><path fill="url(#irlQnnd)" class="fxlb6obqg"/><path fill="url(#iwbzMwb)" class="fxlb6obqg"/></g><path class="fxkhv7z2g"/><path fill="url(#iu6NYAc)" class="u__fffk1x"/><path class="bqsds0gft"/><g filter="url(#iPHvD3c)"><path class="qeja3fbkn"/><path fill="url(#ib798Pe)" class="hjh-z6vly"/></g><g filter="url(#iyajdgC)"><path fill="url(#idNkDye)" class="l5ljb8kaq"/></g><path class="tf9iwot5v"/><path fill="url(#i6iN8Mb)" class="wgp31zbmt"/><path class="cd-jzicse"/><g filter="url(#iUnWVQb)"><path fill="url(#imyaIkc)" class="cktzfgb9f"/></g><g filter="url(#ishLFnb)"><ellipse transform="rotate(-27.914 14.93 5.455)" class="ozv9gm3ep"/><ellipse fill="url(#iHtZkLc)" transform="rotate(-27.914 14.93 5.455)" class="f6hrwsbeg"/></g><path fill="url(#iRz91Zc)" class="rufovacfb"/><path fill="url(#ig1e86d)" class="rufovacfb"/><path fill="url(#iRFj5Nd)" class="rufovacfb"/><path fill="url(#izr4dEb)" class="z837j6bda"/><path fill="url(#iSES2kv)" class="z837j6bda"/><g filter="url(#iLEVwPW)"><path class="u_xo5widk"/></g><g filter="url(#i4HerZc)"><path class="yerb4zbge"/></g><g filter="url(#iIv94Xc)"><path class="o7rzgwbcd"/></g><g filter="url(#iKcwuEd)"><path class="pzup_vbrq"/></g><defs><radialGradient id="iiI6jgb" cx="0" cy="0" r="1" gradientTransform="matrix(.3711 -.3086 .27428 .32982 18.99 19.906)" gradientUnits="userSpaceOnUse"><stop class="icg_3vvcd"/><stop offset="1" class="uewaaqbzx"/></radialGradient><radialGradient id="iZufaLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.326 16.63)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="epjl3v-ou"/><stop offset="1" class="zn2dcd5yl"/></radialGradient><radialGradient id="isg6Gpb" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.903 16.63)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="dz8ufbuwb"/><stop offset="1" class="mysctvbqw"/></radialGradient><radialGradient id="iP1SOOe" cx="0" cy="0" r="1" gradientTransform="matrix(.1836 -.5625 .3991 .13026 19.35 19.025)" gradientUnits="userSpaceOnUse"><stop class="r7zi6ccbx"/><stop offset="1" class="n8x_xkbtc"/></radialGradient><radialGradient id="iSH97bP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98267 0 0 -3.09375 13.544 12.523)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="cn77rwbmc"/><stop offset="1" class="y2mxoh-zc"/></radialGradient><radialGradient id="i0hUVic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.593 8.832)" gradientUnits="userSpaceOnUse"><stop class="y4_ytjb3b"/><stop offset="1" class="wysngjbll"/></radialGradient><radialGradient id="iXI2pNc" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.3125 1.2963 3.62963 18.825 11.976)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="l7g1kibqg"/><stop offset="1" class="d_gvw4b_b"/></radialGradient><radialGradient id="i02Gsmn" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16.031 18.101)" gradientUnits="userSpaceOnUse"><stop class="kcjik5o6k"/><stop offset="1" class="j6ndfp4vo"/></radialGradient><radialGradient id="ilCBvjH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.107 28.465)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iaPOC8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.825 28.554)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iopGuPc" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.442 8.232)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="mdbsecb0y"/><stop offset="1" class="y-nukfwnq"/></radialGradient><radialGradient id="i4SyW8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.42712 .66406 -.8419 1.8093 15.475 8.873)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="x6ry26biy"/><stop offset="1" class="v_htu4bru"/></radialGradient><radialGradient id="ieH8Tse" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.598 29.414)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="itsz0oc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27353 1.58656 -1.88471 -.32494 18.482 6.258)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iG7njCe" cx="0" cy="0" r="1" gradientTransform="matrix(.57182 1.20382 -.54719 .25992 13.54 6.384)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="i548PoY" cx="0" cy="0" r="1" gradientTransform="matrix(.08049 .5358 -.47 .0706 13.9 6.293)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="ia8EKad" cx="0" cy="0" r="1" gradientTransform="matrix(-2.3467 0 0 -4.15128 17.291 5.91)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iudxcRC" cx="0" cy="0" r="1" gradientTransform="matrix(-.51307 5.81888 -4.81873 -.42488 16.74 3.255)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="dqi7sbofo"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="iGkpGtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60191 .74486 0 17.13 5.406)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iU1ipLJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.02606 -.4953 .539 -.02836 15.026 5.345)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iErPA1c" cx="0" cy="0" r="1" gradientTransform="matrix(.54172 0 0 2.75344 13.84 6.082)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="ismqKoc" cx="0" cy="0" r="1" gradientTransform="matrix(1.17373 -1.6402 .3715 .26585 13.404 4.562)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iJ5S7jb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.259 11.044 -2.45)scale(4.72382 5.20343)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="ih0ILOe" cx="0" cy="0" r="1" gradientTransform="matrix(.91792 .32352 -.19408 .55065 16.91 3.493)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="i7b4m5r" cx="0" cy="0" r="1" gradientTransform="matrix(.15584 -.27806 .80916 .45348 15.525 7.386)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="in6ud0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32353 1.30163 0 16.031 7.498)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iafxXrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.63064 2.88917 0 13.684 5.2)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="igYuoYw" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.63064 2.88917 0 18.213 5.2)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iykRiye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45964 -.55677 .29651 -.77735 17.875 2.381)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="iDlCqEb" cx="0" cy="0" r="1" gradientTransform="matrix(.40629 .6621 -1.53312 .94078 15.625 1.667)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iBCspEe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.70886 .61657 -.1716 -.47562 16.145 2.314)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iTuTYfc" cx="0" cy="0" r="1" gradientTransform="matrix(1.44458 -2.28726 2.53405 1.60045 13.593 4.45)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iBjoiud" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -3.324 77.095)scale(1.56176 .87344)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="ilO4Qtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.96448 -1.66254 .92718 -.53788 18.333 4.902)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="ifpXFzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.58685 -.98857 .70807 -.42034 18.055 4.767)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iFG4IFs" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 8.927 2.467)scale(2.21506 2.39456)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="irlQnnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05267 .17225 -.78752 -.2408 17.582 2.727)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iwbzMwb" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 8.081 6.462)scale(1.90841 4.92126)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iu6NYAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36419 -.57928 0 17.01 5.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ib798Pe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 9.81 -1.373)scale(.16981 .23378)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6iN8Mb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3642 -.57931 0 15.052 5.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iHtZkLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00347 -.22179 .2666 -.00417 14.923 5.596)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ig1e86d" cx="0" cy="0" r="1" gradientTransform="matrix(.28214 1.00697 -.96073 .26918 18.104 5.504)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iRFj5Nd" cx="0" cy="0" r="1" gradientTransform="matrix(.35362 -.48529 .40677 .2964 18.266 5.749)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iSES2kv" cx="0" cy="0" r="1" gradientTransform="rotate(-171.677 7.123 2.394)scale(.75989 .74703)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><filter id="icqheYc" width="2.311" height="8.028" x="11.372" y="12.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.682353 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_179"/></filter><filter id="iS7GBCe" width="1.464" height="6.913" x="19.195" y="11.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".25"/></filter><filter id="iP31Vlb" width="6.169" height="12.453" x="13.047" y="16.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.462745 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_179"/></filter><filter id="imdKUrC" width="6.417" height="7.594" x="12.973" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.415686 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_179"/></filter><filter id="ixuMawd" width="3.316" height="1.848" x="12.465" y="28.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_179"/></filter><filter id="iJmZRUc" width="6.594" height="13.766" x="12.872" y="15.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".5"/></filter><filter id="iQuMqfb" width="5.338" height="5.74" x="13.758" y="3.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_179"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_179" result="effect2_innerShadow_4002_179"/></filter><filter id="iz8nc1d" width="2.788" height="3.267" x="14.517" y="4.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".5"/></filter><filter id="itl03vd" width="1.043" height="1.502" x="15.51" y="5.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".05"/></filter><filter id="i7I9efe" width="1.945" height=".982" x="15.059" y="6.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".05"/></filter><filter id="i21Ized" width="5.778" height="4.027" x="13.142" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_179"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_179" result="effect2_innerShadow_4002_179"/></filter><filter id="i0Jj4jb" width="1.105" height=".645" x="16.744" y="4.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_179"/></filter><filter id="ibhK8ac" width="1.105" height=".638" x="14.385" y="4.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_179"/></filter><filter id="iTmJNKy" width="2.931" height="2.645" x="13.313" y="2.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".05"/></filter><filter id="iCw4Cqd" width="2.758" height="2.512" x="16.045" y="2.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".05"/></filter><filter id="iPHvD3c" width=".463" height=".423" x="16.626" y="5.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".05"/></filter><filter id="iyajdgC" width=".62" height=".63" x="16.948" y="5.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".1"/></filter><filter id="iUnWVQb" width=".663" height=".687" x="14.953" y="5.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".1"/></filter><filter id="ishLFnb" width=".52" height=".427" x="14.67" y="5.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".05"/></filter><filter id="iLEVwPW" width=".872" height="1.344" x="13.185" y="5.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".125"/></filter><filter id="i4HerZc" width=".925" height="1.354" x="18.008" y="5.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".125"/></filter><filter id="iIv94Xc" width="1.043" height=".484" x="14.367" y="4.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".05"/></filter><filter id="iKcwuEd" width="1.043" height=".484" x="16.736" y="4.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_179" stdDeviation=".05"/></filter><linearGradient id="ivKrMAb" x1="12.497" x2="12.497" y1="12.781" y2="12.304" gradientUnits="userSpaceOnUse"><stop class="mea8vgbzb"/><stop offset="1" class="x8_6e5b0q"/></linearGradient><linearGradient id="i7f2jHN" x1="19.778" x2="19.778" y1="12.867" y2="12.164" gradientUnits="userSpaceOnUse"><stop class="kidhsabwy"/><stop offset="1" class="i08i0qbub"/></linearGradient><linearGradient id="iKWj31d" x1="16.031" x2="16.031" y1="16.011" y2="16.445" gradientUnits="userSpaceOnUse"><stop class="sb3cb-bog"/><stop offset="1" class="hpe4_756h"/></linearGradient><linearGradient id="iEmngAd" x1="16.031" x2="16.031" y1="9.101" y2="16.062" gradientUnits="userSpaceOnUse"><stop class="hrtvttbtf"/><stop offset="1" class="nua72fb5w"/></linearGradient><linearGradient id="iaDrApd" x1="18.278" x2="16.531" y1="29.726" y2="29.523" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="iN3yr4n" x1="18.346" x2="16.392" y1="6.666" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="i2ZbmRc" x1="16.031" x2="16.415" y1="6.281" y2="6.281" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iloOcyc" x1="15.55" x2="16.032" y1="6.211" y2="6.238" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ibOJ67b" x1="16.031" x2="16.031" y1="6.46" y2="6.843" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="i7uJwOb" x1="16.031" x2="16.031" y1="5.451" y2="5.64" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="i5jnvEd" x1="18.439" x2="13.894" y1="3.367" y2="3.367" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="idNkDye" x1="17.36" x2="17.219" y1="5.522" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imyaIkc" x1="15.385" x2="15.245" y1="5.522" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRz91Zc" x1="18.92" x2="18.378" y1="5.534" y2="6.511" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="izr4dEb" x1="13.405" x2="14.06" y1="5.85" y2="5.793" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-standing-medium-light" /></template>
<style>
.a03mykf9s {
  d: path("M18.213 6.47a.74.74 0 0 0 .406-.138v.418c0 .4-.239.758-.602.906q.116-.245.155-.53z");
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a2zxjbcyy {
  d: path("M12.08 20.44c-.937-1.981-.768-6.258-.486-7.823h1.672c-.072 2.425.039 5.243.177 6.511c.012.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.062.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.as_wp7bxb {
  d: path("M16.031 7.21c-.228 0-.442-.054-.622-.148c-.061-.031-.128.038-.089.094a.85.85 0 0 0 .711.38a.85.85 0 0 0 .71-.38c.04-.058-.027-.125-.088-.094a1.34 1.34 0 0 1-.622.148");
}

.bqsds0gft {
  fill: var(--svg-color--000, #000);
  d: path("M16.782 5.685c0-.128.102-.23.23-.23a.23.23 0 0 1 .203.335h-.406a.2.2 0 0 1-.027-.105");
}

.bsrto12qr {
  d: path("M20.499 12.66c-.487-2.253-1.629-3.333-3.03-3.828v3.949h2.932a.1.1 0 0 0 .098-.12");
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cd-jzicse {
  fill: var(--svg-color--000, #000);
  d: path("M15.28 5.685a.23.23 0 0 0-.23-.23a.228.228 0 0 0-.203.335h.406a.2.2 0 0 0 .027-.105");
}

.cktzfgb9f {
  d: path("M15.417 5.637c0-.13-.106-.215-.134-.241l-.13.125l.08.162z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn77rwbmc {
  stop-color: var(--svg-color--f16440, #F16440);
  stop-opacity: 0;
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.d_gvw4b_b {
  stop-color: var(--svg-color--ff391e, #FF391E);
  stop-opacity: 0;
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.dhem5bbqc {
  d: path("M19.364 19.16a.22.22 0 0 0 .043-.238h.437l-.32.996c-.262.078-.54.05-.59-.114a.32.32 0 0 1 .074-.3a9 9 0 0 0 .356-.344");
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

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.drhu1ybzd {
  d: path("M13.849 6.47a.74.74 0 0 1-.406-.138v.418c0 .4.239.758.602.906a1.8 1.8 0 0 1-.156-.53z");
}

.dz8ufbuwb {
  stop-color: var(--svg-color--d27e6a, #D27E6A);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.epjl3v-ou {
  stop-color: var(--svg-color--9c5f5c, #9C5F5C);
}

.er818xpbc {
  fill: var(--svg-color--ff7a43, #FF7A43);
  d: path("M20.499 12.66c-.487-2.253-1.629-3.333-3.03-3.828v3.949h2.932a.1.1 0 0 0 .098-.12");
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6hrwsbeg {
  cx: 14.93px;
  cy: 5.455px;
  rx: 0.175px;
  ry: 0.089px;
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.flylnfw7h {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M14.5 4.523a1.25 1.25 0 0 1 .78-.161a.124.124 0 0 1-.03.247a1 1 0 0 0-.656.149l-.007.005l-.002.001a.125.125 0 0 1-.152-.197z");
}

.ft5dv1b6b {
  fill: none;
}

.fxkhv7z2g {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.104 5.162c.293 0 .541.202.608.475a.123.123 0 0 1-.12.153h-1.001a.103.103 0 0 1-.102-.122a.63.63 0 0 1 .615-.506");
}

.fxlb6obqg {
  d: path("m18.37 4.902l-.012-.283a.66.66 0 0 0-.631-.64h-.628c-.4 0-.763-.218-.954-.565c0 0 .323-.934.86-.813c.392.088.811.227 1.132.436c.783.511.646 1.432.234 1.865");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gc_nsb79v {
  fill: var(--svg-color--aa6e62, #AA6E62);
  d: path("M12.699 19.16a.22.22 0 0 1-.043-.238h-.438l.32.996c.262.078.54.05.59-.114a.32.32 0 0 0-.074-.3a9 9 0 0 1-.355-.344");
}

.gh48jbbhn {
  d: path("M11.564 12.66c.486-2.253 1.628-3.333 3.03-3.828v3.949H11.66a.1.1 0 0 1-.097-.12");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
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

.h5gec01yx {
  d: path("M12.973 11.527a3.059 3.059 0 1 1 6.117 0v4.441a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
}

.hjh-z6vly {
  d: path("M16.982 5.369c.028.038-.031.084-.1.135c-.067.05-.117.086-.146.048s.003-.11.071-.16s.146-.062.175-.023");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hpe4_756h {
  stop-color: var(--svg-color--856988, #856988);
  stop-opacity: 0;
}

.hrtvttbtf {
  stop-color: var(--svg-color--ff7325, #FF7325);
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

.i08i0qbub {
  stop-color: var(--svg-color--ff381e, #FF381E);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.icg_3vvcd {
  stop-color: var(--svg-color--c2807d, #C2807D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.ir-g6pm8n {
  fill: var(--svg-color--827a8a, #827A8A);
  d: path("m13.047 16.011l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.j0gqqp9fe {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.838 5.758l-.311.744c-.046.17.064.34.218.34h.33c.155 0 .264-.173.219-.34l-.223-.826c-.048-.182-.184-.1-.234.082");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j6ndfp4vo {
  stop-color: var(--svg-color--6a597b, #6A597B);
  stop-opacity: 0;
}

.ja04_0anf {
  d: path("M15.16 7.375h1.742v1.351a.871.871 0 0 1-1.742 0z");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.k98skybyf {
  stroke: var(--svg-color--f2ae96, #F2AE96);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.844 12.498c.125 1 .3 3.575 0 5.875");
}

.kbtpxgecb {
  d: path("M19.598 29.82v.242H16.53v-1.598h1.992c.102.368.575.754.817.915c.186.123.258.3.258.44");
}

.kcjik5o6k {
  stop-color: var(--svg-color--6a597b, #6A597B);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kidhsabwy {
  stop-color: var(--svg-color--ff381e, #FF381E);
}

.l4sfebcir {
  d: path("m16.135 3.389l-.03-.062a.3.3 0 0 0-.276-.188h-.571c-.829 0-1.5.68-1.5 1.517v.124c-.153-.117-.344-.362-.344-.758c0-.481.35-.724.574-.88c.063-.043.117-.08.149-.113l.044-.047c.157-.167.437-.463.925-.593q.116-.03.231-.047c.468-.07.808.348.808.821v.22z");
}

.l538fmchy {
  fill: var(--svg-color--d19881, #D19881);
  d: path("M12.08 20.44c-.937-1.981-.768-6.258-.486-7.823h1.672c-.072 2.425.039 5.243.177 6.511c.012.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.062.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.l5ljb8kaq {
  d: path("M17.368 5.632a.4.4 0 0 0-.103-.208l-.117.128l.053.103z");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l7g1kibqg {
  stop-color: var(--svg-color--ff391e, #FF391E);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lpu_bb7zv {
  d: path("M18.21 2.927a1.064 1.064 0 0 1 .521 1.606a.7.7 0 0 0-.12.393v.533a.8.8 0 0 0-.3-.12l.035-.721a.65.65 0 0 0-.619-.643H17.1c-.429 0-.817-.253-.993-.648a.3.3 0 0 0-.276-.188h-.572c-.828 0-1.5.68-1.5 1.517l.014.69a.8.8 0 0 0-.323.119v-.54a.7.7 0 0 0-.122-.392a1.07 1.07 0 0 1-.064-1.098c.131-.248.343-.42.583-.505c.258-.092.477-.265.622-.499a1.044 1.044 0 0 1 1.297-.409a.67.67 0 0 0 .536 0a1.044 1.044 0 0 1 1.302.424c.138.229.355.395.607.481");
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdbsecb0y {
  stop-color: var(--svg-color--ff863c, #FF863C);
}

.mea8vgbzb {
  stop-color: var(--svg-color--fb2d18, #FB2D18);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mysctvbqw {
  stop-color: var(--svg-color--d27e6a, #D27E6A);
  stop-opacity: 0;
}

.n8x_xkbtc {
  stop-color: var(--svg-color--c07874, #C07874);
  stop-opacity: 0;
}

.nb3czznun {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m16.742 7.156l.062.042a.14.14 0 0 0-.015-.174a.144.144 0 0 0-.17-.029a1.3 1.3 0 0 1-.588.14c-.216 0-.418-.051-.587-.14a.144.144 0 0 0-.171.03a.136.136 0 0 0-.015.173a.93.93 0 0 0 .773.413c.324 0 .61-.165.773-.414zm0 0a.85.85 0 0 1-.711.38a.85.85 0 0 1-.71-.38c-.04-.056.027-.125.088-.094c.18.094.394.148.622.148c.23 0 .442-.054.622-.148c.061-.031.128.036.089.094Z");
}

.nc8x04b8h {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M17.707 4.572a.8.8 0 0 0-.309-.185c-.136-.043-.308-.055-.544-.026a.125.125 0 1 0 .03.248c.216-.027.348-.013.44.015a.6.6 0 0 1 .22.135a.125.125 0 0 0 .163-.187");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nua72fb5w {
  stop-color: var(--svg-color--ff4c2e, #FF4C2E);
}

.o7rzgwbcd {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.517 4.648a1.04 1.04 0 0 1 .743-.17");
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

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.ozv9gm3ep {
  cx: 14.93px;
  cy: 5.455px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.175px;
  ry: 0.089px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pzup_vbrq {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.63 4.628a1.04 1.04 0 0 0-.744-.171");
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q7l7dqb4y {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.465 29.82v.242h3.066v-1.598H13.54c-.102.368-.574.754-.816.915a.54.54 0 0 0-.258.44");
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qeja3fbkn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.982 5.369c.028.038-.031.084-.1.135c-.067.05-.117.086-.146.048s.003-.11.071-.16s.146-.062.175-.023");
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r7zi6ccbx {
  stop-color: var(--svg-color--c07874, #C07874);
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rufovacfb {
  d: path("M18.24 6.511q.045-.717.083-1.432a.723.723 0 0 1-.083 1.432");
}

.sb3cb-bog {
  stop-color: var(--svg-color--856988, #856988);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.sx-yjgb9f {
  fill: var(--svg-color--9d98a2, #9D98A2);
  d: path("m13.872 16.382l.469 11.766h.812v-10.61h2.203v10.61h.672l.438-11.766z");
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.ta7i6wbki {
  fill: var(--svg-color--ff4326, #FF4326);
  d: path("M11.564 12.66c.486-2.253 1.628-3.333 3.03-3.828v3.949H11.66a.1.1 0 0 1-.097-.12");
}

.tf9iwot5v {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.958 5.162a.63.63 0 0 0-.608.475c-.02.078.04.153.12.153h1.001a.103.103 0 0 0 .102-.122a.63.63 0 0 0-.615-.506");
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.treq1gbey {
  fill: var(--svg-color--e3b495, #E3B495);
  d: path("M19.92 20.44c.937-1.981.768-6.258.486-7.823h-1.671c.071 2.425-.156 5.253-.294 6.522a.29.29 0 0 0 .554.15l.117-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.062.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.u__fffk1x {
  d: path("M17.011 5.284a.4.4 0 0 1 .387.506h-.774a.402.402 0 0 1 .388-.506");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u_xo5widk {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M13.77 5.372a.429.429 0 0 0 .037.843a35 35 0 0 1-.037-.843");
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u78464b_o {
  d: path("M19.92 20.44c.937-1.981.768-6.258.486-7.823h-1.671c.071 2.425-.156 5.253-.294 6.522a.29.29 0 0 0 .554.15l.117-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.062.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.uewaaqbzx {
  stop-color: var(--svg-color--c6856b, #C6856B);
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

.v_htu4bru {
  stop-color: var(--svg-color--eca484, #ECA484);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v1ass0bqn {
  d: path("m15.86 5.589l-.24.825c-.048.17.069.34.235.34h.353c.165 0 .282-.173.233-.34l-.238-.825c-.051-.183-.29-.183-.343 0");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wgp31zbmt {
  d: path("M15.05 5.284a.4.4 0 0 0-.385.506h.774a.403.403 0 0 0-.388-.506");
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.wysngjbll {
  stop-color: var(--svg-color--de5d25, #DE5D25);
  stop-opacity: 0;
}

.x6ry26biy {
  stop-color: var(--svg-color--cf8785, #CF8785);
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.x8_6e5b0q {
  stop-color: var(--svg-color--fb2d18, #FB2D18);
  stop-opacity: 0;
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y-nukfwnq {
  stop-color: var(--svg-color--ff863c, #FF863C);
  stop-opacity: 0;
}

.y2mxoh-zc {
  stop-color: var(--svg-color--f16440, #F16440);
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y4_ytjb3b {
  stop-color: var(--svg-color--de5d25, #DE5D25);
}

.yerb4zbge {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("m18.258 6.219l.05-.855a.429.429 0 0 1-.05.855");
}

.yhl3rwbtd {
  d: path("M13.865 7.15a1.76 1.76 0 0 0 1.744 1.53h.847c.883 0 1.629-.653 1.744-1.53c.053-.845.107-1.687.146-2.532a.65.65 0 0 0-.62-.643h-.628c-.428 0-.816-.253-.992-.648a.3.3 0 0 0-.277-.188h-.57c-.83 0-1.5.68-1.5 1.517c0 .835.051 1.657.106 2.494");
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

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.z837j6bda {
  d: path("M13.763 5.075a.722.722 0 0 0 .062 1.436q-.047-.718-.062-1.436");
}

.z9wedib1s {
  d: path("m13.047 16.011l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.zn2dcd5yl {
  stop-color: var(--svg-color--9c5f5c, #9C5F5C);
  stop-opacity: 0;
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

</style>
