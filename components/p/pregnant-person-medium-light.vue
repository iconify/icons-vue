<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imuQOGc)"><path class="m6ls9bb0r"/><path fill="url(#iJsIz3p)" class="lfatth4fq"/><path fill="url(#ifxyeUd)" class="lfatth4fq"/><path fill="url(#iiVkhbb)" class="lfatth4fq"/><path fill="url(#iNeSoxb)" class="lfatth4fq"/></g><g filter="url(#iBrfX1d)"><path class="q_hhljmyz"/></g><g filter="url(#iZmU7se)"><path fill="url(#iSVhALe)" class="als6l0h8g"/><path fill="url(#ielqNEb)" class="als6l0h8g"/><path fill="url(#iDBKl8c)" class="als6l0h8g"/></g><g filter="url(#iYTbrDe)"><path fill="url(#izSprNc)" class="k5tnkb85n"/><path fill="url(#ipZwoGe)" class="k5tnkb85n"/></g><g filter="url(#iDb4u7T)"><path stroke="url(#igx5tnW)" class="miptak6ux"/></g><g filter="url(#iCrhrec)"><path stroke="url(#ixNmq6d)" class="ffy646bhn"/></g><g filter="url(#i5QPimd)"><path stroke="url(#i6cRdCb)" class="e6cjplsbl"/></g><g filter="url(#isDucvK)"><path stroke="url(#ixqjUge)" class="x0j_d8-hg"/></g><path fill="url(#iz8g6vd)" class="i4da6sbcw"/><path fill="url(#i4bKSod)" class="ynjjhfq9h"/><path fill="url(#i9ZVmNc)" class="ynjjhfq9h"/><path fill="url(#i4bKSod)" class="ynjjhfq9h"/><path fill="url(#i9ZVmNc)" class="ynjjhfq9h"/><g filter="url(#iQunG0c)"><path fill="url(#iP7Ohcd)" class="yskxmxb0h"/></g><path fill="url(#io89IMe)" class="yskxmxb0h"/><path fill="url(#i3PS95d)" class="yskxmxb0h"/><path fill="url(#iH3c6Zc)" class="yskxmxb0h"/><path fill="url(#iJqfKac)" class="yskxmxb0h"/><path fill="url(#i5tI4kb)" class="yskxmxb0h"/><path fill="url(#iiiKGNe)" class="yskxmxb0h"/><path fill="url(#im9Sa4b)" class="yskxmxb0h"/><path fill="url(#iiaiKwU)" class="yskxmxb0h"/><g filter="url(#i0W4sJR)"><path class="ui_r9kbra"/></g><g filter="url(#idsQmfe)"><path fill="url(#iMSswQc)" class="ib-2neb9d"/><path fill="url(#iGRHVLd)" class="ib-2neb9d"/><path fill="url(#ilHMZsc)" class="ib-2neb9d"/><path fill="url(#iILjZHb)" class="ib-2neb9d"/></g><path fill="url(#ioGtayc)" class="ib-2neb9d"/><path fill="url(#iPn7OWb)" class="ib-2neb9d"/><g filter="url(#iuUPUmb)"><path stroke="url(#inlD8Yd)" class="cmjox28je"/></g><path fill="url(#iBUJ7sc)" class="l0fhg4bxa"/><g filter="url(#iuKzPxc)"><path fill="url(#irTboEe)" class="cxd0i1h7m"/><path fill="url(#iOZnyqb)" class="cxd0i1h7m"/><path fill="url(#iagmfYb)" class="cxd0i1h7m"/><path fill="url(#iToHBtb)" class="cxd0i1h7m"/><path fill="url(#iQuEQUh)" class="cxd0i1h7m"/></g><g filter="url(#i2tdhge)"><path class="gyfqgqbrq"/></g><g filter="url(#i4wzINb)"><path class="n_fx2q4az"/></g><g filter="url(#is9hgKc)"><path fill="url(#i3lCFud)" class="g-vw-vb1q"/><path fill="url(#i5qpuRo)" class="g-vw-vb1q"/></g><g filter="url(#i7ERCMb)"><path fill="url(#ibv2sxb)" class="oa-j_rb_h"/><path fill="url(#iWP1Ffc)" class="oa-j_rb_h"/><path fill="url(#igbIumc)" class="oa-j_rb_h"/><path fill="url(#ixtnCtd)" class="oa-j_rb_h"/><path fill="url(#i3vS1ab)" class="oa-j_rb_h"/><path fill="url(#iWwRLde)" class="oa-j_rb_h"/></g><path class="voj8pzbmh"/><path fill="url(#i4XXhXd)" class="ripslkbfd"/><path class="ed7er_byz"/><g filter="url(#iUOJDne)"><path class="vld2qbc-v"/><path fill="url(#iAZtVyc)" class="i6yzwnb2d"/></g><g filter="url(#iP4Ppyb)"><path fill="url(#ipwybWb)" class="xkl1e8bfa"/></g><path class="n3cs3bbyz"/><path fill="url(#iKDYI1N)" class="zk2x07bba"/><path class="kkrf5ybfd"/><g filter="url(#ir32elY)"><path fill="url(#ixTeePc)" class="p4chvnbhy"/></g><g filter="url(#iFHWLlc)"><ellipse transform="rotate(-27.914 15.836 8.78)" class="oxbi4bbci"/><ellipse fill="url(#i8nW2Yc)" transform="rotate(-27.914 15.836 8.78)" class="a3dhlcbvp"/></g><path fill="url(#iFbrppO)" class="pa2senhml"/><path fill="url(#ibIwXcc)" class="pa2senhml"/><path fill="url(#iYxmyge)" class="pa2senhml"/><path fill="url(#iuBAmKc)" class="y2fgc9qrp"/><path fill="url(#iuQJshe)" class="y2fgc9qrp"/><g filter="url(#iA4ia4n)"><path class="f1quscbia"/></g><g filter="url(#iX2GQmb)"><path class="hu6h7qbra"/></g><g filter="url(#ihNV4yy)"><path class="ceysw33rj"/></g><g filter="url(#iC1DMlb)"><path class="tzztfna-i"/></g><defs><radialGradient id="iJsIz3p" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.2441 14.467 0 15.057 29.814)" gradientUnits="userSpaceOnUse"><stop class="i0nsp7bni"/><stop offset="1" class="j9mdirbao"/></radialGradient><radialGradient id="ifxyeUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.36327 -1.99342 2.97247 -.54169 21.084 15.876)" gradientUnits="userSpaceOnUse"><stop class="y8skcxtgz"/><stop offset="1" class="j0n9-bc_s"/></radialGradient><radialGradient id="iiVkhbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.0625 -2.6875 0 20.72 21.851)" gradientUnits="userSpaceOnUse"><stop class="le_3nbbjw"/><stop offset="1" class="imi34--zw"/></radialGradient><radialGradient id="iNeSoxb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.39747 2.14876 -.75252 -2.24047 18.9 13.702)" gradientUnits="userSpaceOnUse"><stop offset=".449" class="vp7op3b3o"/><stop offset="1" class="akwhn1mys"/></radialGradient><radialGradient id="izSprNc" cx="0" cy="0" r="1" gradientTransform="rotate(115.321 5.941 15.552)scale(4.28183 3.28478)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="l863e7bwo"/><stop offset="1" class="h-d21x52g"/></radialGradient><radialGradient id="ipZwoGe" cx="0" cy="0" r="1" gradientTransform="rotate(118.72 6.293 14.862)scale(2.6272 1.65249)" gradientUnits="userSpaceOnUse"><stop class="xhl3qijdh"/><stop offset="1" class="phlxv6bym"/></radialGradient><radialGradient id="iz8g6vd" cx="0" cy="0" r="1" gradientTransform="matrix(-.54478 3.15995 -3.75378 -.64716 22.91 10.379)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="i4bKSod" cx="0" cy="0" r="1" gradientTransform="matrix(1.13888 2.39764 -1.08984 .51767 13.07 10.632)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="i9ZVmNc" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 .825 13.23)scale(1.07912 .94662)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iP7Ohcd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.67391 0 0 -8.26809 20.54 9.685)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="i3PS95d" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.3554 -9.40364 0 18.422 4.632)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="kxbun9b-a"/><stop offset=".96" class="s4gd3jb7x"/></radialGradient><radialGradient id="iH3c6Zc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.19882 1.48354 0 20.218 8.683)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iJqfKac" cx="0" cy="0" r="1" gradientTransform="matrix(-.05191 -.98648 1.07352 -.0565 16.029 8.56)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="i5tI4kb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07894 0 0 5.48401 13.666 10.029)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iiiKGNe" cx="0" cy="0" r="1" gradientTransform="matrix(2.3377 -3.26679 .73993 .5295 12.797 7.002)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="im9Sa4b" cx="0" cy="0" r="1" gradientTransform="rotate(-103.259 14.221 -.42)scale(9.4084 10.3637)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iiaiKwU" cx="0" cy="0" r="1" gradientTransform="rotate(19.415 -4.355 60.25)scale(1.93844 1.16285)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iPn7OWb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64464 1.63713 -1.04057 -1.04534 18.94 9.617)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="inlD8Yd" cx="0" cy="0" r="1" gradientTransform="matrix(.31038 -.5538 1.6116 .9032 17.022 12.626)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="iBUJ7sc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.64437 2.59245 0 18.03 12.85)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iOZnyqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.24774 5.75435 0 13.354 8.27)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iagmfYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.24774 5.75435 0 22.375 8.27)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iToHBtb" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 11.096 -.67)scale(3.11146 1.65706)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="iQuEQUh" cx="0" cy="0" r="1" gradientTransform="matrix(.8092 1.3187 -3.0535 1.87374 17.22 1.236)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="i3lCFud" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 8.907 2.86)scale(3.6183 1.00706)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="i5qpuRo" cx="0" cy="0" r="1" gradientTransform="matrix(2.8772 -4.55551 5.04703 3.18764 13.174 6.78)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="ibv2sxb" cx="0" cy="0" r="1" gradientTransform="matrix(3.02703 .71595 -.4004 1.69292 21.266 3.563)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iWP1Ffc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92094 -3.31126 1.84667 -1.0713 22.615 7.68)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="igbIumc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16884 -1.96894 1.41027 -.83719 22.06 7.411)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="ixtnCtd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28999 1.02922 -1.11263 -4.63764 22.316 3.459)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="i3vS1ab" cx="0" cy="0" r="1" gradientTransform="matrix(-.1049 .34307 -1.56847 -.47959 21.117 3.347)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iWwRLde" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78322 3.35672 -8.65603 -4.59842 21.114 2.612)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="i4XXhXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .72535 -1.15375 0 19.98 8.866)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iAZtVyc" cx="0" cy="0" r="1" gradientTransform="matrix(-.20735 -.26718 .36786 -.28547 19.777 8.942)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKDYI1N" cx="0" cy="0" r="1" gradientTransform="matrix(0 .72539 -1.15381 0 16.079 8.866)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i8nW2Yc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.372 -3.257)scale(.44179 .53104)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibIwXcc" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 5.225 19.05)scale(2.08282 1.98717)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iYxmyge" cx="0" cy="0" r="1" gradientTransform="matrix(.70431 -.96655 .81016 .59035 22.48 9.366)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iuQJshe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49753 -.219 .2153 -1.47221 13.635 9.454)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><filter id="imuQOGc" width="16.1" height="17.295" x="7.632" y="12.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737772 0 0 0 0 0.308243 0 0 0 0 0.219096 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4532"/></filter><filter id="iBrfX1d" width="15.69" height="15.109" x="7.314" y="14.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".5"/></filter><filter id="iZmU7se" width="16.543" height="14.071" x="6.244" y="15.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.466667 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4532"/></filter><filter id="iYTbrDe" width="4.451" height="5.283" x="18.533" y="15.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.262745 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4532"/></filter><filter id="iDb4u7T" width="1.542" height=".3" x="6.883" y="26.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".05"/></filter><filter id="iCrhrec" width="1.542" height=".3" x="6.516" y="27.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".05"/></filter><filter id="i5QPimd" width="1.542" height=".3" x="6.703" y="28.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".05"/></filter><filter id="isDucvK" width="12.538" height="9.787" x="8.412" y="19.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".4"/></filter><filter id="iQunG0c" width="9.887" height="11.234" x="13.503" y="4.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4532"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_4532" result="effect2_innerShadow_13929_4532"/></filter><filter id="i0W4sJR" width="3.568" height="4.524" x="16.005" y="8.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".5"/></filter><filter id="idsQmfe" width="1.878" height="2.793" x="17.091" y="8.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".05"/></filter><filter id="iuUPUmb" width="3.377" height="1.459" x="16.341" y="11.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".05"/></filter><filter id="iuKzPxc" width="11.509" height="7.524" x="12.275" y="1.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4532"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_4532" result="effect2_innerShadow_13929_4532"/></filter><filter id="i2tdhge" width="2.102" height="1.085" x="19.45" y="6.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4532"/></filter><filter id="i4wzINb" width="2.102" height="1.072" x="14.751" y="6.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4532"/></filter><filter id="is9hgKc" width="5.94" height="5.41" x="12.567" y="2.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".125"/></filter><filter id="i7ERCMb" width="5.71" height="5.152" x="17.891" y="2.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".125"/></filter><filter id="iUOJDne" width=".725" height=".643" x="19.314" y="8.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".05"/></filter><filter id="iP4Ppyb" width=".839" height=".859" x="20.054" y="8.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".1"/></filter><filter id="ir32elY" width=".924" height=".972" x="16.082" y="8.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".1"/></filter><filter id="iFHWLlc" width=".838" height=".651" x="15.418" y="8.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".05"/></filter><filter id="iA4ia4n" width="1.241" height="2.18" x="12.61" y="8.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".125"/></filter><filter id="iX2GQmb" width="1.346" height="2.202" x="22.216" y="8.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".125"/></filter><filter id="ihNV4yy" width="2.23" height="1.117" x="14.639" y="6.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".125"/></filter><filter id="iC1DMlb" width="2.23" height="1.117" x="19.358" y="6.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4532" stdDeviation=".125"/></filter><linearGradient id="iSVhALe" x1="20.158" x2="7.502" y1="20.914" y2="30.695" gradientUnits="userSpaceOnUse"><stop class="w2lmjc7rb"/><stop offset="1" class="lto3m1jpj"/></linearGradient><linearGradient id="ielqNEb" x1="6.502" x2="9.127" y1="27.789" y2="27.601" gradientUnits="userSpaceOnUse"><stop class="g6_qmy6ut"/><stop offset="1" class="iq_e-hgds"/></linearGradient><linearGradient id="iDBKl8c" x1="19.814" x2="18.877" y1="18.82" y2="20.633" gradientUnits="userSpaceOnUse"><stop class="azzi5mbzv"/><stop offset="1" class="gdrfnlhwr"/></linearGradient><linearGradient id="igx5tnW" x1="7.033" x2="8.486" y1="26.679" y2="26.679" gradientUnits="userSpaceOnUse"><stop class="gad6u7bha"/><stop offset="1" class="dpx-tpb3y"/><stop offset="1" class="fb9lq7rid"/></linearGradient><linearGradient id="ixNmq6d" x1="6.666" x2="8.119" y1="27.617" y2="27.617" gradientUnits="userSpaceOnUse"><stop class="gad6u7bha"/><stop offset="1" class="dpx-tpb3y"/><stop offset="1" class="fb9lq7rid"/></linearGradient><linearGradient id="i6cRdCb" x1="6.853" x2="8.306" y1="28.515" y2="28.515" gradientUnits="userSpaceOnUse"><stop class="gad6u7bha"/><stop offset="1" class="dpx-tpb3y"/><stop offset="1" class="fb9lq7rid"/></linearGradient><linearGradient id="ixqjUge" x1="20.055" x2="6.868" y1="20.733" y2="29.265" gradientUnits="userSpaceOnUse"><stop class="rmfe762wy"/><stop offset="1" class="ed7pcqjnp"/></linearGradient><linearGradient id="io89IMe" x1="22.64" x2="18.749" y1="11.192" y2="11.192" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iMSswQc" x1="18.03" x2="18.794" y1="10.426" y2="10.426" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iGRHVLd" x1="17.071" x2="18.031" y1="10.287" y2="10.34" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ilHMZsc" x1="18.03" x2="18.03" y1="10.783" y2="11.544" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iILjZHb" x1="18.03" x2="18.03" y1="8.773" y2="9.148" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="ioGtayc" x1="18.147" x2="18.147" y1="11.386" y2="11.333" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="irTboEe" x1="22.825" x2="13.774" y1="4.623" y2="4.623" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="ipwybWb" x1="20.676" x2="20.395" y1="8.914" y2="9.087" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixTeePc" x1="16.744" x2="16.463" y1="8.914" y2="9.087" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFbrppO" x1="23.784" x2="22.705" y1="8.939" y2="10.884" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iuBAmKc" x1="12.8" x2="14.104" y1="9.568" y2="9.454" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pregnant-person-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a3dhlcbvp {
  cx: 15.836px;
  cy: 8.781px;
  rx: 0.348px;
  ry: 0.176px;
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.akwhn1mys {
  stop-color: var(--svg-color--ee3404, #EE3404);
  stop-opacity: 0;
}

.als6l0h8g {
  d: path("M21.776 15.658a1.674 1.674 0 0 1 .872 2.202c-.383.886-1.065 2.411-1.96 3.979c-.88 1.537-2.043 3.259-3.434 4.433c-2.342 1.976-4.765 2.698-6.745 2.923c-.93.129-2.17.232-3.109.184c-.457-.024-.735-.232-.785-.477a.5.5 0 0 1 .062-.366a.526.526 0 0 1-.177-.9a.525.525 0 0 1 .27-.976h.18a.504.504 0 0 1 .243-.945H8.29a1.6 1.6 0 0 1-.257-.431c-.1-.236.024-.506.253-.622c.236-.12.522-.04.692.164c.597.713 1.248 1.043 1.79.947c1.352-.24 2.917-.805 4.35-2.015c.935-.79 1.84-2.145 2.661-3.581c.804-1.407 1.428-2.799 1.795-3.647a1.675 1.675 0 0 1 2.202-.873");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.azzi5mbzv {
  stop-color: var(--svg-color--bd8d7b, #BD8D7B);
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ceysw33rj {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.014 7.174c.23-.165.802-.455 1.48-.341");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmjox28je {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.826 11.915a2.6 2.6 0 0 0 1.204.285c.446 0 .856-.104 1.204-.285a.21.21 0 0 1 .252.041a.2.2 0 0 1 .022.254m-2.682-.295l2.62.254m-2.62-.254a.21.21 0 0 0-.253.043a.2.2 0 0 0-.02.252m.273-.295l-.212.254m2.894.041l-.063-.042m.063.042l-.063-.042m.063.042c-.313.474-.858.79-1.478.79s-1.165-.316-1.478-.79m2.893-.042a1.69 1.69 0 0 1-1.415.757a1.7 1.7 0 0 1-1.416-.757m-.062.043l.062-.043m-.062.043v-.001l.062-.042");
}

.cxd0i1h7m {
  d: path("M22.37 3.746c.46.159.873.48 1.133.94a2.12 2.12 0 0 1-.094 2.259c-.157.23-.242.503-.242.781V8.79a1.6 1.6 0 0 0-.597-.24l.07-1.436a1.296 1.296 0 0 0-1.233-1.28h-1.251a2.17 2.17 0 0 1-1.978-1.29a.59.59 0 0 0-.55-.375H16.49c-1.65 0-2.987 1.353-2.987 3.021l.027 1.375a1.5 1.5 0 0 0-.643.235V7.726c0-.278-.086-.551-.242-.781a2.14 2.14 0 0 1-.128-2.187c.26-.494.683-.84 1.161-1.007a2.4 2.4 0 0 0 1.238-.993a2.08 2.08 0 0 1 2.584-.815a1.33 1.33 0 0 0 1.067 0c.252-.105.526-.168.816-.168a2.08 2.08 0 0 1 1.778 1.012c.275.456.706.787 1.21.96");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dpx-tpb3y {
  stop-color: var(--svg-color--85624e, #85624E);
  stop-opacity: 0;
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e6cjplsbl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M6.853 28.515h1.242");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ed7er_byz {
  fill: var(--svg-color--000, #000);
  d: path("M19.525 9.237c0-.254.203-.457.457-.457a.455.455 0 0 1 .407.668h-.81a.4.4 0 0 1-.054-.21");
}

.ed7pcqjnp {
  stop-color: var(--svg-color--edb49c, #EDB49C);
  stop-opacity: 0;
}

.f1quscbia {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M13.526 8.614a.854.854 0 0 0 .075 1.68q-.047-.84-.075-1.68");
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

.fb9lq7rid {
  stop-color: var(--svg-color--c48b67, #C48B67);
  stop-opacity: 0;
}

.ffy646bhn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M6.666 27.617h1.242");
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-vw-vb1q {
  d: path("M18.237 4.665a2 2 0 0 1-.059-.123a.59.59 0 0 0-.55-.374H16.49c-1.65 0-2.987 1.353-2.987 3.021v.246c-.304-.231-.686-.719-.686-1.509c0-.958.698-1.442 1.144-1.751c.126-.088.232-.16.296-.227l.09-.093c.312-.332.868-.922 1.84-1.18a4.8 4.8 0 0 1 1.263-.15c.473.005.806.413.806.886v1.242z");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g6_qmy6ut {
  stop-color: var(--svg-color--dfa78d, #DFA78D);
}

.gad6u7bha {
  stop-color: var(--svg-color--c48b67, #C48B67);
}

.gdrfnlhwr {
  stop-color: var(--svg-color--bd8d7b, #BD8D7B);
  stop-opacity: 0;
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

.gyfqgqbrq {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M21.367 7.021a1.7 1.7 0 0 0-.615-.367c-.272-.086-.612-.11-1.084-.051a.248.248 0 1 0 .06.492c.43-.053.694-.025.875.032c.178.055.297.146.438.268a.248.248 0 1 0 .326-.374");
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h-d21x52g {
  stop-color: var(--svg-color--ec541d, #EC541D);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hu6h7qbra {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M22.466 10.302q.052-.85.099-1.701a.854.854 0 0 1-.099 1.701");
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

.i0nsp7bni {
  stop-color: var(--svg-color--d7454a, #D7454A);
}

.i4da6sbcw {
  d: path("M22.376 10.803c.3-.01.58-.112.809-.276v.832a1.94 1.94 0 0 1-1.2 1.805q.23-.487.31-1.055z");
}

.i6yzwnb2d {
  d: path("M19.924 8.608c.056.076-.062.169-.197.27c-.136.101-.236.172-.293.096s.007-.22.142-.32c.135-.101.29-.122.348-.046");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ib-2neb9d {
  d: path("m17.688 9.047l-.475 1.643c-.097.338.136.676.465.676h.703c.33 0 .563-.343.466-.676l-.475-1.643c-.102-.365-.577-.365-.684 0");
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.imi34--zw {
  stop-color: var(--svg-color--ff7634, #FF7634);
  stop-opacity: 0;
}

.iq_e-hgds {
  stop-color: var(--svg-color--d9a487, #D9A487);
  stop-opacity: 0;
}

.j0n9-bc_s {
  stop-color: var(--svg-color--ff7a45, #FF7A45);
  stop-opacity: 0;
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j9mdirbao {
  stop-color: var(--svg-color--fc5428, #FC5428);
  stop-opacity: 0;
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.k5tnkb85n {
  d: path("M22.752 18.191c.39-1.09-.127-2.166-.976-2.533a1.675 1.675 0 0 0-2.202.872c-.267.616-.533 1.241-1.041 2.227l3.047 1.946c.566-1.099.924-1.82 1.172-2.512");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kkrf5ybfd {
  fill: var(--svg-color--000, #000);
  d: path("M16.534 9.237a.455.455 0 0 0-.457-.457a.455.455 0 0 0-.406.668h.809a.45.45 0 0 0 .054-.21");
}

.kxbun9b-a {
  stop-color: var(--svg-color--ca8882, #CA8882);
  stop-opacity: 0;
}

.l0fhg4bxa {
  d: path("M18.03 12.275a2.7 2.7 0 0 1-1.239-.293c-.122-.063-.254.075-.177.187c.3.453.822.756 1.416.756s1.116-.303 1.415-.757c.078-.115-.054-.249-.177-.186c-.358.187-.78.293-1.238.293");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l863e7bwo {
  stop-color: var(--svg-color--ff6420, #FF6420);
}

.le_3nbbjw {
  stop-color: var(--svg-color--ff7634, #FF7634);
}

.lfatth4fq {
  d: path("M16.942 12.61c-2.204.675-3.886 3.246-3.886 5.608v.717a.526.526 0 0 1-.406.504c-2.87.705-5.018 3.106-5.018 6.148v1.215c0 1.657 1.345 3 3.004 3l10.163.012c.968 0 1.683-.783 1.683-1.75V15.83c0-1.296-.845-2.238-2.037-2.487q-.232-.046-.462-.099a3.5 3.5 0 0 1-.764-.256l-.058-.03c-.695-.346-1.477-.577-2.219-.35");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lto3m1jpj {
  stop-color: var(--svg-color--e4ab91, #E4AB91);
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m6ls9bb0r {
  fill: var(--svg-color--ff6428, #FF6428);
  d: path("M16.942 12.61c-2.204.675-3.886 3.246-3.886 5.608v.717a.526.526 0 0 1-.406.504c-2.87.705-5.018 3.106-5.018 6.148v1.215c0 1.657 1.345 3 3.004 3l10.163.012c.968 0 1.683-.783 1.683-1.75V15.83c0-1.296-.845-2.238-2.037-2.487q-.232-.046-.462-.099a3.5 3.5 0 0 1-.764-.256l-.058-.03c-.695-.346-1.477-.577-2.219-.35");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.miptak6ux {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.033 26.68h1.242");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n_fx2q4az {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M14.98 6.924a2.48 2.48 0 0 1 1.555-.321a.248.248 0 1 1-.06.492a2 2 0 0 0-1.24.254l-.082.054l-.003.002a.248.248 0 0 1-.303-.392z");
}

.n3cs3bbyz {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.892 8.197c-.584 0-1.077.402-1.211.946c-.04.156.08.305.24.305h1.994a.206.206 0 0 0 .203-.243a1.25 1.25 0 0 0-1.226-1.008");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oa-j_rb_h {
  d: path("m22.69 7.68l-.026-.565c-.01-.682-.574-1.245-1.256-1.274h-1.252c-.795 0-1.52-.435-1.9-1.126c0 0-.022-.054-.054-.151c-.311-.954.628-1.708 1.61-1.502c.824.174 1.73.459 2.412.904c1.56 1.017 1.287 2.85.466 3.714");
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

.oxbi4bbci {
  cx: 15.836px;
  cy: 8.781px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.348px;
  ry: 0.176px;
}

.p4chvnbhy {
  d: path("M16.806 9.144c0-.258-.21-.43-.266-.482l-.258.25l.159.322z");
}

.pa2senhml {
  d: path("M22.43 10.884q.09-1.426.165-2.853a1.439 1.439 0 0 1-.165 2.853");
}

.phlxv6bym {
  stop-color: var(--svg-color--ff5d1d, #FF5D1D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q_hhljmyz {
  fill: var(--svg-color--e23405, #E23405);
  d: path("M10.556 28.848q.229-.03.44-.06c1.886-.224 3.508-.32 5.739-2.297c1.325-1.174 2.433-2.896 3.27-4.433c.854-1.568 1.503-3.093 1.868-3.98c.35-.849-.022-1.834-.831-2.202s-1.748.024-2.098.873c-.35.848-.944 2.24-1.71 3.646c-.782 1.437-1.643 2.792-2.533 3.581a8.56 8.56 0 0 1-4.145 2.016c-.516.096-1.136-.235-1.705-.948a.56.56 0 0 0-.494-.215a7 7 0 0 0-.043.758v1.215c0 1.164 1.318 1.548 2.242 2.046");
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

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.ripslkbfd {
  d: path("M19.982 8.44a.798.798 0 0 1 .77 1.008H19.21a.8.8 0 0 1 .772-1.008");
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rmfe762wy {
  stop-color: var(--svg-color--edb49c, #EDB49C);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.s4gd3jb7x {
  stop-color: var(--svg-color--c66159, #C66159);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
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

.tzztfna-i {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.213 7.133c-.23-.165-.802-.455-1.48-.341");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
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

.ui_r9kbra {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m17.645 9.385l-.619 1.48c-.09.338.127.676.435.676h.657c.308 0 .526-.343.435-.676l-.444-1.644c-.095-.364-.365-.2-.464.164");
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vld2qbc-v {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.924 8.608c.056.076-.062.169-.197.27c-.136.101-.236.172-.293.096s.007-.22.142-.32c.135-.101.29-.122.348-.046");
}

.voj8pzbmh {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.167 8.197c.584 0 1.078.402 1.212.946a.245.245 0 0 1-.24.305h-1.994a.206.206 0 0 1-.203-.243a1.25 1.25 0 0 1 1.225-1.008");
}

.vp7op3b3o {
  stop-color: var(--svg-color--ee3404, #EE3404);
}

.w2lmjc7rb {
  stop-color: var(--svg-color--e3ae99, #E3AE99);
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x0j_d8-hg {
  stroke-linecap: round;
  d: path("M19.65 20.483c-1.043 2.063-4.488 6.388-9.938 7.188");
}

.xhl3qijdh {
  stop-color: var(--svg-color--ff8147, #FF8147);
}

.xkl1e8bfa {
  d: path("M20.693 9.132a.75.75 0 0 0-.207-.413l-.232.255l.105.204z");
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y2fgc9qrp {
  d: path("M13.511 8.023a1.439 1.439 0 0 0 .124 2.861a70 70 0 0 1-.124-2.86");
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y8skcxtgz {
  stop-color: var(--svg-color--ff7a45, #FF7A45);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ynjjhfq9h {
  d: path("M13.684 10.803c-.3-.01-.58-.112-.81-.276v.832c0 .799.477 1.51 1.2 1.805a3.7 3.7 0 0 1-.31-1.055z");
}

.yskxmxb0h {
  d: path("M13.716 12.157a3.5 3.5 0 0 0 3.474 3.045h1.687c1.758 0 3.244-1.3 3.474-3.045c.105-1.684.211-3.362.29-5.045a1.296 1.296 0 0 0-1.233-1.28h-1.252a2.17 2.17 0 0 1-1.977-1.29a.59.59 0 0 0-.55-.374H16.49c-1.65 0-2.987 1.352-2.987 3.021c0 1.664.104 3.3.213 4.968");
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

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zk2x07bba {
  d: path("M16.077 8.44a.798.798 0 0 0-.769 1.008h1.542a.803.803 0 0 0-.772-1.008");
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

</style>
