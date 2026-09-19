<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igtPXve)" class="m1i1rlbvk"/><g filter="url(#i29ammb)"><path class="xk18tyb3e"/></g><path class="duc38e2qw"/><path fill="url(#iCoINWb)" class="zqss5obsp"/><path fill="url(#i6jO4ud)" class="zqss5obsp"/><path fill="url(#iwtLm3r)" class="zqss5obsp"/><path fill="url(#iRlvw5c)" class="zqss5obsp"/><path class="fgv70eb9t"/><path fill="url(#iw5yIye)" class="om0oq7b1v"/><path fill="url(#ivP9Jjb)" class="om0oq7b1v"/><path fill="url(#i8g26lb)" class="om0oq7b1v"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#iTdOGsd)" class="vqc4qgzhu"/><path fill="url(#iJIw8ya)" class="vqc4qgzhu"/><g filter="url(#iLzlREZ)"><path fill="url(#iblgbvb)" class="dvr2s59yl"/></g><path fill="url(#idlbkMe)" class="rom2yrbwh"/><path fill="url(#iIvEVud)" class="rom2yrbwh"/><path fill="url(#iXRw9pd)" class="rom2yrbwh"/><path fill="url(#iz9xh1o)" class="rom2yrbwh"/><path fill="url(#i6G3R0c)" class="rom2yrbwh"/><g filter="url(#iCDgvbb)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#iv50Obe)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#isaMVKc)"><path class="crx1i3bfy"/></g><g filter="url(#iOJs2Eb)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#ixaGDYd)" class="u1e8ikbzb"/></g><g filter="url(#i5OpvYM)"><path class="z5g21op2e"/></g><g filter="url(#ipr9EAb)"><path fill="url(#iEYHwqd)" class="pv8cx5b7o"/><path fill="url(#ibrdWNd)" class="pv8cx5b7o"/><path fill="url(#i024Txd)" class="pv8cx5b7o"/><path fill="url(#ieWdNxd)" class="pv8cx5b7o"/><path fill="url(#iqGuoib)" class="pv8cx5b7o"/></g><g filter="url(#imDsqRc)"><path stroke="url(#izTUB2b)" class="waqwqw1tk"/></g><g filter="url(#iQFMOie)"><path stroke="url(#igbgkNe)" class="phyw90buy"/></g><g filter="url(#i0Epsyc)"><path stroke="url(#iA5CJKp)" class="vz0qjzgsj"/></g><circle fill="url(#ioCFKhc)" class="d0cy2bcgv"/><g filter="url(#iQj4yXc)"><circle fill="url(#iqzRlSu)" class="yua6h8bjf"/></g><g filter="url(#ijUzOls)"><circle fill="url(#iExIa1c)" class="l2vt3sbxe"/><circle fill="url(#iof0Hwc)" class="l2vt3sbxe"/></g><g filter="url(#ivKv9Fs)"><circle class="v3toh_t4d"/><circle fill="url(#igrjBlc)" class="jwo4tsbei"/><circle fill="url(#iL4UJSb)" class="jwo4tsbei"/></g><path fill="url(#iTLbRve)" class="t3si6zqed"/><path fill="url(#izDBYgb)" class="t3si6zqed"/><path fill="url(#iWXtmtc)" class="t3si6zqed"/><path fill="url(#ii4NVye)" class="t3si6zqed"/><path fill="url(#iMW6Vle)" class="t3si6zqed"/><path fill="url(#iytTOub)" class="t3si6zqed"/><g filter="url(#iiWnWNF)"><path class="yog9y-cyc"/></g><g filter="url(#iJ3TYJe)"><path class="m7n0u5bjb"/><path fill="url(#iU4Nrjb)" class="iojvtzgha"/><path fill="url(#iZ3CIJd)" class="iojvtzgha"/><path fill="url(#i6UIEue)" class="iojvtzgha"/><path fill="url(#i968ZWb)" class="iojvtzgha"/></g><g filter="url(#iIWY2QC)"><path stroke="url(#iZkd7Sd)" class="iw-xlacms"/></g><path class="yxy_9dzmc"/><path class="nt7sn0kyf"/><path fill="url(#i5iyA2d)" class="pji7vab_z"/><path class="kzs5jvb0q"/><g filter="url(#iVPGobc)"><path class="f0ea7el6t"/><path fill="url(#ikKi4JF)" class="a9lydnbnh"/></g><g filter="url(#iBpVBfb)"><path fill="url(#i3JsZtb)" class="aeebpybre"/></g><path class="j3ivezbmc"/><path fill="url(#is2nubX)" class="nu3gtu0dv"/><path class="n59raacqh"/><g filter="url(#iXoItAc)"><path fill="url(#i6bDUkc)" class="lxu_qmqlm"/></g><g filter="url(#i0wKOol)"><ellipse transform="rotate(-27.914 13.242 10.005)" class="tlddw5lso"/><ellipse fill="url(#iLr7sOd)" transform="rotate(-27.914 13.242 10.005)" class="m30uidvsw"/></g><g filter="url(#iulm0Jd)"><path clip-rule="evenodd" class="ya--wfdcu"/></g><g filter="url(#iK9s7od)"><path clip-rule="evenodd" class="qpumadcjo"/></g><path fill="url(#iBeSVwd)" class="xamwdicaf"/><path fill="url(#iZ3IHpe)" class="ne_--y7gl"/><path fill="url(#io9H1ve)" class="ne_--y7gl"/><g filter="url(#itewJGe)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#iCKhEPe)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="iwtLm3r" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.998 12.054)scale(1.81196 3.24827)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="wnf6rgd_w"/><stop offset="1" class="r3cifybsp"/></radialGradient><radialGradient id="iRlvw5c" cx="0" cy="0" r="1" gradientTransform="rotate(147.269 4.65 10.005)scale(2.65864 2.62008)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="f-d4mvczx"/><stop offset="1" class="bwphqzbzj"/></radialGradient><radialGradient id="i8g26lb" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="cdn41be_i"/><stop offset="1" class="tziry6b6t"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="iblgbvb" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 6.39 19.816)scale(1.95067 1.56677)" gradientUnits="userSpaceOnUse"><stop class="phvlv-hdf"/><stop offset=".828" class="ty_drcd_b"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="i6G3R0c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.553 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="ixaGDYd" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.839)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="ibrdWNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.245 24.594)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="i024Txd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 23.113 25.97)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="ieWdNxd" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 22.927 27.297)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iqGuoib" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 22.832 28.564)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="ioCFKhc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75356 0 0 3.06874 9.283 10.782)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iof0Hwc" cx="0" cy="0" r="1" gradientTransform="matrix(.82608 -.60152 .68656 .94287 20.83 10.517)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="igrjBlc" cx="0" cy="0" r="1" gradientTransform="matrix(.82065 -1.5094 .88347 .48033 20.417 11.602)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iL4UJSb" cx="0" cy="0" r="1" gradientTransform="matrix(.2591 .25647 -.33062 .334 20.458 10.782)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iWXtmtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.65625 -11.0257 0 16.186 9.031)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="v71hqib9z"/><stop offset=".916" class="snzqtmgtz"/><stop offset="1" class="p40p06bts"/></radialGradient><radialGradient id="ii4NVye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30611 1.60752 0 18.04 9.511)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iMW6Vle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.38983 1.72838 0 13.486 9.478)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iytTOub" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.26495 -6.73687 0 15.747 6.906)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="q4ajq1t1d"/><stop offset="1" class="zjm96qmni"/></radialGradient><radialGradient id="iZkd7Sd" cx="0" cy="0" r="1" gradientTransform="matrix(.02458 -.6268 1.8804 .07375 15.611 14.791)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="i5iyA2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90248 -1.06787 0 17.873 10.434)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ikKi4JF" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.316 .771)scale(.37757 .51982)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="is2nubX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90253 -1.06793 0 13.514 10.434)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iLr7sOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00772 -.49315 .59278 -.00928 13.227 10.32)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="io9H1ve" cx="0" cy="0" r="1" gradientTransform="matrix(-.57714 -1.31028 .73625 -.3243 20.433 8.333)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="r24hnpb7d"/><stop offset="1" class="eo8gvvf_z"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><linearGradient id="igtPXve" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="hzctbo64o"/><stop offset="1" class="ncpoyrbpw"/></linearGradient><linearGradient id="iCoINWb" x1="14.633" x2="13.72" y1="19.957" y2="18.965" gradientUnits="userSpaceOnUse"><stop class="aq4-jj3gx"/><stop offset="1" class="f5q4vk1vk"/></linearGradient><linearGradient id="i6jO4ud" x1="11.535" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="ovaf-b7lk"/></linearGradient><linearGradient id="iw5yIye" x1="19.937" x2="18.312" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="k3d1ulbgd"/></linearGradient><linearGradient id="ivP9Jjb" x1="17" x2="17.937" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="iTdOGsd" x1="23.473" x2="23.473" y1="29.781" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="iEYHwqd" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="izTUB2b" x1="25.183" x2="23.348" y1="25.992" y2="25.992" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="igbgkNe" x1="25.105" x2="23.269" y1="27.297" y2="27.297" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iA5CJKp" x1="25.183" x2="23.348" y1="28.602" y2="28.602" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iqzRlSu" x1="10.952" x2="10.312" y1="11.06" y2="11.06" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iExIa1c" x1="21.544" x2="20.725" y1="9.691" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iTLbRve" x1="19.729" x2="12.098" y1="11.171" y2="12.308" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="izDBYgb" x1="10.304" x2="12.615" y1="13.865" y2="13.564" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iU4Nrjb" x1="14.833" x2="15.77" y1="11.83" y2="11.83" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iZ3CIJd" x1="16.634" x2="15.609" y1="12.152" y2="12.138" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="i6UIEue" x1="15.89" x2="15.89" y1="12.894" y2="12.321" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="i968ZWb" x1="15.696" x2="15.696" y1="10.215" y2="11.554" gradientUnits="userSpaceOnUse"><stop offset=".236" class="wl9qt_poz"/><stop offset="1" class="g6359dcyj"/></linearGradient><linearGradient id="i3JsZtb" x1="18.65" x2="18.337" y1="10.154" y2="10.347" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6bDUkc" x1="14.256" x2="13.943" y1="10.154" y2="10.347" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBeSVwd" x1="10.65" x2="10.057" y1="8.668" y2="8.668" gradientUnits="userSpaceOnUse"><stop class="nhc87rgbt"/><stop offset="1" class="h1q2j_bib"/></linearGradient><linearGradient id="iZ3IHpe" x1="21.111" x2="21.385" y1="8.668" y2="8.668" gradientUnits="userSpaceOnUse"><stop class="pw4-s-b5m"/><stop offset="1" class="rfipqcbwy"/></linearGradient><filter id="i29ammb" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".5"/></filter><filter id="iLzlREZ" width="2.65" height="3.79" x="25.245" y="22.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1946"/></filter><filter id="iCDgvbb" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1946"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1946" result="shape"/></filter><filter id="iv50Obe" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1946"/></filter><filter id="isaMVKc" width="3.922" height="2.04" x="13.799" y="16.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.54902 0 0 0 0 0.00392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1946"/></filter><filter id="iOJs2Eb" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1946"/></filter><filter id="i5OpvYM" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".325"/></filter><filter id="ipr9EAb" width="4.618" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1946"/></filter><filter id="imDsqRc" width="2.047" height=".25" x="23.378" y="25.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".05"/></filter><filter id="iQFMOie" width="2.047" height=".25" x="23.3" y="27.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".05"/></filter><filter id="i0Epsyc" width="2.047" height=".25" x="23.378" y="28.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".05"/></filter><filter id="iQj4yXc" width="2.988" height="2.989" x="9.458" y="9.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".25"/></filter><filter id="ijUzOls" width="3.586" height="3.586" x="18.79" y="8.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1946"/></filter><filter id="ivKv9Fs" width="2.988" height="2.989" x="18.964" y="9.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".25"/></filter><filter id="iiWnWNF" width="3.259" height="4.179" x="13.828" y="9.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".375"/></filter><filter id="iJ3TYJe" width="2.375" height="3.179" x="14.508" y="9.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".125"/></filter><filter id="iIWY2QC" width="3.615" height="1.472" x="13.888" y="13.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".05"/></filter><filter id="iVPGobc" width=".786" height=".695" x="17.14" y="9.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".05"/></filter><filter id="iBpVBfb" width=".89" height=".912" x="17.979" y="9.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".1"/></filter><filter id="iXoItAc" width=".985" height="1.039" x="13.54" y="9.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".1"/></filter><filter id="i0wKOol" width=".912" height=".704" x="12.786" y="9.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1946" stdDeviation=".05"/></filter><filter id="iulm0Jd" width="2.8" height="1.646" x="16.759" y="7.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.156863 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1946"/></filter><filter id="iK9s7od" width="2.8" height="1.646" x="11.634" y="7.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.156863 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1946"/></filter><filter id="itewJGe" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1946"/></filter><filter id="iCKhEPe" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1946"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-mechanic" /></template>
<style>
.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.a9lydnbnh {
  d: path("M17.81 9.813c.063.085-.07.188-.22.3c-.152.114-.264.193-.327.108c-.064-.085.007-.245.158-.358s.325-.135.388-.05");
}

.aeebpybre {
  d: path("M18.669 10.397a.84.84 0 0 0-.231-.461l-.26.284l.118.228z");
}

.aq4-jj3gx {
  stop-color: var(--svg-color--f1d5ff, #F1D5FF);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.bwphqzbzj {
  stop-color: var(--svg-color--e298b3, #E298B3);
  stop-opacity: 0;
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cdn41be_i {
  stop-color: var(--svg-color--e49da8, #E49DA8);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crx1i3bfy {
  fill: var(--svg-color--f0a32b, #F0A32B);
  d: path("M15.71 18.676c-1.524-.508-1.825-1.445-1.91-1.84h3.92c-.355 1.237-1.492 1.738-2.01 1.84");
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.d0cy2bcgv {
  cx: 10.952px;
  cy: 10.782px;
  r: 1.668px;
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.duc38e2qw {
  fill: var(--svg-color--ffe9ff, #FFE9FF);
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.eo8gvvf_z {
  stop-color: var(--svg-color--ef8a2f, #EF8A2F);
  stop-opacity: 0;
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f-d4mvczx {
  stop-color: var(--svg-color--e298b3, #E298B3);
}

.f0ea7el6t {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.81 9.813c.063.085-.07.188-.22.3c-.152.114-.264.193-.327.108c-.064-.085.007-.245.158-.358s.325-.135.388-.05");
}

.f5q4vk1vk {
  stop-color: var(--svg-color--f1d5ff, #F1D5FF);
  stop-opacity: 0;
}

.fgv70eb9t {
  fill: var(--svg-color--ffe3f6, #FFE3F6);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.ft5dv1b6b {
  fill: none;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.g6359dcyj {
  stop-color: var(--svg-color--efab2f, #EFAB2F);
  stop-opacity: 0;
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.h1q2j_bib {
  stop-color: var(--svg-color--d28d46, #D28D46);
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.hzctbo64o {
  stop-color: var(--svg-color--d6c6ed, #D6C6ED);
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.iojvtzgha {
  d: path("m15.314 10.497l-.53 1.698a.54.54 0 0 0 .52.699h.785a.54.54 0 0 0 .52-.699l-.53-1.698c-.115-.376-.646-.376-.765 0");
}

.iw-xlacms {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.696 13.91a3 3 0 0 1-1.384-.329c-.137-.07-.284.085-.198.21c.335.506.918.844 1.582.844s1.247-.338 1.582-.845c.086-.129-.061-.278-.198-.209c-.4.21-.872.329-1.384.329Z");
}

.j3ivezbmc {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.305 9.353c-.653 0-1.204.45-1.354 1.057c-.044.175.09.34.268.34h2.229a.23.23 0 0 0 .227-.27a1.4 1.4 0 0 0-1.37-1.127");
}

.jwo4tsbei {
  cx: 20.458px;
  cy: 10.782px;
  r: 0.994px;
}

.k3d1ulbgd {
  stop-color: var(--svg-color--fee6ff, #FEE6FF);
  stop-opacity: 0;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.kzs5jvb0q {
  fill: var(--svg-color--000, #000);
  d: path("M17.365 10.515c0-.283.227-.51.51-.51a.508.508 0 0 1 .453.745h-.902a.46.46 0 0 1-.061-.235");
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l2vt3sbxe {
  cx: 20.458px;
  cy: 10.782px;
  r: 1.668px;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.lxu_qmqlm {
  d: path("M14.326 10.41c0-.287-.235-.48-.298-.537l-.288.278l.178.36z");
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m30uidvsw {
  cx: 13.242px;
  cy: 10.005px;
  rx: 0.389px;
  ry: 0.197px;
}

.m7n0u5bjb {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.314 10.497l-.53 1.698a.54.54 0 0 0 .52.699h.785a.54.54 0 0 0 .52-.699l-.53-1.698c-.115-.376-.646-.376-.765 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.n59raacqh {
  fill: var(--svg-color--000, #000);
  d: path("M14.021 10.515a.51.51 0 0 0-.51-.51a.508.508 0 0 0-.453.745h.902a.5.5 0 0 0 .061-.235");
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.ncpoyrbpw {
  stop-color: var(--svg-color--cdb2d2, #CDB2D2);
}

.ne_--y7gl {
  d: path("M21.323 8.7V7.265h-1.197c.047.138.198.47.425.689s.302.595.302.807l-.081 1.393c.076 0 .224 0 .353-.199c.204-.314.204-1.085.198-1.255");
}

.nhc87rgbt {
  stop-color: var(--svg-color--e47729, #E47729);
}

.nt7sn0kyf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.082 9.353c.652 0 1.204.45 1.354 1.057a.274.274 0 0 1-.268.34H16.94a.23.23 0 0 1-.227-.27a1.396 1.396 0 0 1 1.37-1.127");
}

.nu3gtu0dv {
  d: path("M13.512 9.624a.892.892 0 0 0-.86 1.127h1.723a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.om0oq7b1v {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.ovaf-b7lk {
  stop-color: var(--svg-color--ffeaff, #FFEAFF);
  stop-opacity: 0;
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p40p06bts {
  stop-color: var(--svg-color--f18a66, #F18A66);
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.phvlv-hdf {
  stop-color: var(--svg-color--ffdf46, #FFDF46);
}

.phyw90buy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.425 27.297h1.797");
}

.pji7vab_z {
  d: path("M17.875 9.624a.892.892 0 0 1 .86 1.127h-1.723a.895.895 0 0 1 .863-1.127");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.pv8cx5b7o {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.pw4-s-b5m {
  stop-color: var(--svg-color--ffa829, #FFA829);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q4ajq1t1d {
  stop-color: var(--svg-color--d47e31, #D47E31);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qpumadcjo {
  fill: var(--svg-color--a0354c, #A0354C);
  fill-rule: evenodd;
  d: path("M13.918 8.467c-.72-.067-1.18.214-1.293.317a.472.472 0 0 1-.64-.694c.307-.282 1.032-.655 2.02-.562a.472.472 0 0 1-.087.94");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.r24hnpb7d {
  stop-color: var(--svg-color--ef8a2f, #EF8A2F);
}

.r3cifybsp {
  stop-color: var(--svg-color--edc3c1, #EDC3C1);
  stop-opacity: 0;
}

.rfipqcbwy {
  stop-color: var(--svg-color--ffbb3c, #FFBB3C);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rom2yrbwh {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.101-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.snzqtmgtz {
  stop-color: var(--svg-color--ee8952, #EE8952);
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t3si6zqed {
  d: path("M10.586 8.591c0-.266.051-.687.265-.847l.057-.433c.268-.213.492-.018.492-.337V6.12c0-.267.16-.48.428-.533c.644-.16 1.984-.426 3.913-.426c1.93 0 3.27.266 3.913.426c.214.053.429.266.429.533v.853c0 .32.16.64.375.852c.502.352.47.545.429.96c-.18 1.788-.235 3.6-.355 5.394c-.16 1.768-1.55 3-3.208 3h-3.208c-1.711 0-3.048-1.232-3.208-3c-.139-1.808-.323-3.773-.322-5.589");
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tlddw5lso {
  cx: 13.242px;
  cy: 10.005px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.ty_drcd_b {
  stop-color: var(--svg-color--f9c116, #F9C116);
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.tziry6b6t {
  stop-color: var(--svg-color--e49da8, #E49DA8);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v3toh_t4d {
  cx: 20.458px;
  cy: 10.782px;
  r: 0.994px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v71hqib9z {
  stop-color: var(--svg-color--ee8952, #EE8952);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.vqc4qgzhu {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.402-1.54-6.44-3.96-8.457");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vz0qjzgsj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.503 28.602H25.3");
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.waqwqw1tk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.503 25.992H25.3");
}

.wl9qt_poz {
  stop-color: var(--svg-color--efab2f, #EFAB2F);
}

.wnf6rgd_w {
  stop-color: var(--svg-color--edc3c1, #EDC3C1);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xamwdicaf {
  d: path("M10.16 8.7V7.265h1.196c-.047.138-.198.47-.425.689s-.302.595-.302.807v1.392h-.001c-.076 0-.143 0-.27-.198c-.205-.314-.205-1.085-.199-1.255");
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xk18tyb3e {
  fill: var(--svg-color--caadc8, #CAADC8);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.ya--wfdcu {
  fill: var(--svg-color--a2374b, #A2374B);
  fill-rule: evenodd;
  d: path("M17.475 8.467c.719-.067 1.18.214 1.292.317a.472.472 0 0 0 .64-.694c-.306-.282-1.031-.655-2.02-.562a.472.472 0 0 0 .087.94");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yog9y-cyc {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.421 10.66l-.82 1.698c-.101.35.142.7.488.7h.737c.345 0 .589-.356.487-.7l-.497-1.698c-.107-.376-.283-.376-.395 0");
}

.yua6h8bjf {
  cx: 10.952px;
  cy: 10.782px;
  r: 0.994px;
}

.yxy_9dzmc {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.696 13.91a3 3 0 0 1-1.384-.329c-.137-.07-.284.085-.198.21c.335.506.918.844 1.582.844s1.247-.338 1.582-.845c.086-.129-.061-.278-.198-.209c-.4.21-.872.329-1.384.329");
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.zjm96qmni {
  stop-color: var(--svg-color--d47e31, #D47E31);
  stop-opacity: 0;
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zqss5obsp {
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

</style>
