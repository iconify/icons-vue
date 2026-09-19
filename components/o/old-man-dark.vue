<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i7MnOae)"><path fill="url(#i1MWiAb)" class="wkt27vamq"/><path fill="url(#i1Hjm6c)" class="wkt27vamq"/></g><g filter="url(#iOmQbvc)"><path class="z1ac9ioef"/><path fill="url(#iKjcVse)" class="wd2gaqb2r"/><path fill="url(#iQoXBWb)" class="wd2gaqb2r"/></g><g filter="url(#iPxVBGc)"><path fill="url(#ii1lB7d)" class="bh4i2qbfz"/></g><g filter="url(#ik6raXd)"><path fill="url(#i10boqc)" class="jt9sfd_8g"/></g><g filter="url(#imNl1ob)"><path fill="url(#ijkFq7c)" class="k7jpzyb2w"/><path fill="url(#iupGute)" class="k7jpzyb2w"/><path fill="url(#ifNCctE)" class="k7jpzyb2w"/><path fill="url(#iP0M9Qc)" class="k7jpzyb2w"/><path fill="url(#iICFKQd)" class="k7jpzyb2w"/><path fill="url(#iXQffCe)" class="k7jpzyb2w"/><path fill="url(#iQxGGbe)" class="k7jpzyb2w"/><path fill="url(#i7vQUKb)" class="k7jpzyb2w"/></g><g filter="url(#i6OA5nk)"><path fill="url(#i6pga1d)" class="feb82lhbu"/></g><g filter="url(#ipkElGj)"><path class="grtw3qb5s"/></g><g filter="url(#iMfjtmc)"><path class="q-99_hbdo"/><path fill="url(#iq6FkBc)" class="ku8peobxx"/><path fill="url(#iwkhH7q)" class="ku8peobxx"/><path fill="url(#i2DonKg)" class="ku8peobxx"/><path fill="url(#is0u9xe)" class="ku8peobxx"/></g><path class="zjp518bgo"/><path fill="url(#iAgcy8d)" class="eja54ndmj"/><path fill="url(#i1qPhDc)" class="eja54ndmj"/><g filter="url(#iYfDvvc)"><path class="p1j5i8b3n"/><path fill="url(#ir5u5xR)" class="a3z0rjbkf"/><path fill="url(#isqJ7pd)" class="a3z0rjbkf"/><path fill="url(#ig2Ogqb)" class="a3z0rjbkf"/></g><path stroke="url(#iX6A5Rd)" class="wanvse71t"/><path class="dxex1chqi"/><path class="kj6bsmvmy"/><rect fill="url(#iUaDMdc)" class="rx61x1b9v"/><rect fill="url(#icdW8eb)" class="zzsbp5bdy"/><path class="fo3bwns7p"/><path fill="url(#i9RvY6b)" class="h86xvuobt"/><path class="xw5vrmbua"/><g filter="url(#itz63Le)"><path fill="url(#idkYwZc)" class="hb068sutp"/></g><g filter="url(#iUpVoxb)"><ellipse transform="rotate(-27.914 11.516 16.78)" class="s-gwt1b5z"/><ellipse fill="url(#iKPWjWb)" transform="rotate(-27.914 11.516 16.78)" class="egw5g_y4s"/></g><path class="vxcq24b1n"/><path fill="url(#ir45hpy)" class="wmtchzb1q"/><path class="iynd1m6ic"/><g filter="url(#iExG0Zc)"><path class="d69huhboq"/><path fill="url(#i33zcNe)" class="lmxrxmb4i"/></g><g filter="url(#iu1Jbtc)"><path fill="url(#iosOvJe)" class="mq-q1xiwv"/></g><g filter="url(#i6Taarc)"><path class="umqdi2bdz"/></g><g filter="url(#ipNYHGD)"><path stroke="url(#i5j43qe)" class="bmkvcoycx"/></g><g filter="url(#iA8t36F)"><path class="dtgynupor"/></g><g filter="url(#iJ2oJte)"><path stroke="url(#ive9RAQ)" class="whrd19cql"/></g><defs><radialGradient id="i1Hjm6c" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 39.804 -30.63)scale(1.93052 2.20343)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iKjcVse" cx="0" cy="0" r="1" gradientTransform="matrix(1.64694 -3.0292 1.773 .96396 24.87 19.709)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iQoXBWb" cx="0" cy="0" r="1" gradientTransform="matrix(.51997 .5147 -.66351 .67031 24.954 18.062)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="ii1lB7d" cx="0" cy="0" r="1" gradientTransform="matrix(3.31277 0 0 5.79738 4.067 18.062)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="ijkFq7c" cx="0" cy="0" r="1" gradientTransform="rotate(152.026 9.337 10.277)scale(17.0552 31.3253)" gradientUnits="userSpaceOnUse"><stop class="zpqiekbmq"/><stop offset="1" class="ay4s1-bcp"/></radialGradient><radialGradient id="iupGute" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.8125 26.0906 0 16.125 29.973)" gradientUnits="userSpaceOnUse"><stop class="ksg_hcc-p"/><stop offset="1" class="xulak8-hu"/></radialGradient><radialGradient id="ifNCctE" cx="0" cy="0" r="1" gradientTransform="rotate(158.66 12.366 6.749)scale(9.9616 12.7935)" gradientUnits="userSpaceOnUse"><stop class="tg7j0e4gw"/><stop offset="1" class="baf2i9bsp"/></radialGradient><radialGradient id="iP0M9Qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.625 3.09375 0 20.935 15.754)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iICFKQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.35329 3.02392 0 12.688 15.982)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="abh2gabji"/><stop offset="1" class="z5_8k6fyg"/></radialGradient><radialGradient id="iXQffCe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35307 -1.63196 1.28997 -1.85996 24.971 10.32)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="kwgrcj4xm"/><stop offset="1" class="rsot6ubhk"/></radialGradient><radialGradient id="iQxGGbe" cx="0" cy="0" r="1" gradientTransform="rotate(132.807 1.262 6.973)scale(2.59831 2.26071)" gradientUnits="userSpaceOnUse"><stop offset=".476" class="rr9ivbbgg"/><stop offset="1" class="f36on8j_k"/></radialGradient><radialGradient id="i7vQUKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.75 -4.63513 0 17.688 4.098)" gradientUnits="userSpaceOnUse"><stop class="dzx4x3b-q"/><stop offset="1" class="ylgm7jlye"/></radialGradient><radialGradient id="is0u9xe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36044 -1.11102 0 16.745 21.053)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iAgcy8d" cx="0" cy="0" r="1" gradientTransform="rotate(139.273 2.458 6.017)scale(4.16691 7.99724)" gradientUnits="userSpaceOnUse"><stop class="rlhs-hbwc"/><stop offset="1" class="xi80kbc0k"/></radialGradient><radialGradient id="i1qPhDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.04688 -.9516 0 7.09 14.816)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="l9fk14bxd"/><stop offset="1" class="uyez41bsl"/></radialGradient><radialGradient id="ir5u5xR" cx="0" cy="0" r="1" gradientTransform="matrix(1.98438 -2.09375 .72837 .69032 24.622 13.254)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="aq7827bba"/><stop offset="1" class="tco_4qs8v"/></radialGradient><radialGradient id="isqJ7pd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 2.625 -2.01353 -1.12662 25.904 9.098)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="wgw2105cx"/><stop offset="1" class="fj_enu3ru"/></radialGradient><radialGradient id="ig2Ogqb" cx="0" cy="0" r="1" gradientTransform="matrix(.32886 -4.54687 .85753 .06202 26.841 16.348)" gradientUnits="userSpaceOnUse"><stop class="bddxqszam"/><stop offset="1" class="bwtw0srgi"/></radialGradient><radialGradient id="i9RvY6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 12.021 17.581)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="zs1u76b3p"/></radialGradient><radialGradient id="iKPWjWb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.293 3.03)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ir45hpy" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.158 17.581)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="zs1u76b3p"/></radialGradient><radialGradient id="i33zcNe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.058 3.726)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i7MnOae" width="6.553" height="6.553" x="21.802" y="14.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20104"/></filter><filter id="iOmQbvc" width="4.991" height="4.991" x="22.459" y="15.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation=".25"/></filter><filter id="iPxVBGc" width="6.503" height="6.303" x="4.067" y="14.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20104"/></filter><filter id="ik6raXd" width="4.991" height="4.991" x="4.723" y="15.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation=".25"/></filter><filter id="imNl1ob" width="20.793" height="25.5" x="6.104" y="4.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20104"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.32549 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_20104" result="effect2_innerShadow_3987_20104"/></filter><filter id="i6OA5nk" width="11.918" height="9.719" x="15.036" y="6.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation="1"/></filter><filter id="ipkElGj" width="4.796" height="6.408" x="13.272" y="16.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation=".375"/></filter><filter id="iMfjtmc" width="3.796" height="5.408" x="14.272" y="16.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation=".125"/></filter><filter id="iYfDvvc" width="4.3" height="9.2" x="23.17" y="7.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.568627 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20104"/></filter><filter id="itz63Le" width="1.493" height="1.594" x="12.245" y="16.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation=".1"/></filter><filter id="iUpVoxb" width="1.529" height="1.141" x="10.751" y="16.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation=".05"/></filter><filter id="iExG0Zc" width="1.294" height="1.125" x="18.875" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation=".05"/></filter><filter id="iu1Jbtc" width="1.316" height="1.357" x="20.528" y="16.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation=".1"/></filter><filter id="i6Taarc" width="5.214" height="3" x="18.514" y="11.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20104"/></filter><filter id="ipNYHGD" width="4.458" height="2.061" x="18.789" y="12.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation=".2"/></filter><filter id="iA8t36F" width="5.214" height="3" x="8.912" y="11.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20104"/></filter><filter id="iJ2oJte" width="4.458" height="2.061" x="9.093" y="12.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20104" stdDeviation=".2"/></filter><linearGradient id="i1MWiAb" x1="27.005" x2="25.459" y1="16.001" y2="20.789" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="i10boqc" x1="7.218" x2="5.934" y1="18.62" y2="18.62" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="i6pga1d" x1="15.727" x2="30.915" y1="14.191" y2="8.754" gradientUnits="userSpaceOnUse"><stop class="p7wwt2b_k"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="iq6FkBc" x1="14.652" x2="16.3" y1="20.032" y2="20.032" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iwkhH7q" x1="17.818" x2="16.017" y1="20.622" y2="20.597" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="i2DonKg" x1="16.512" x2="16.512" y1="21.981" y2="20.932" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iX6A5Rd" x1="14.236" x2="15.047" y1="24.922" y2="23.64" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iUaDMdc" x1="13.17" x2="17.938" y1="8.116" y2="8.116" gradientUnits="userSpaceOnUse"><stop class="ohys34b9r"/><stop offset="1" class="fnb-_ubqy"/></linearGradient><linearGradient id="icdW8eb" x1="13.313" x2="19.844" y1="10.495" y2="10.495" gradientUnits="userSpaceOnUse"><stop class="moydr9c6g"/><stop offset="1" class="gnkeuhb_f"/></linearGradient><linearGradient id="idkYwZc" x1="13.408" x2="12.823" y1="17.06" y2="17.42" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iosOvJe" x1="21.608" x2="21.023" y1="17.06" y2="17.42" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5j43qe" x1="22.646" x2="19.154" y1="13.512" y2="13.512" gradientUnits="userSpaceOnUse"><stop class="kwz2g5lgk"/><stop offset="1" class="mv5v459od"/></linearGradient><linearGradient id="ive9RAQ" x1="13.147" x2="9.693" y1="12.65" y2="13.993" gradientUnits="userSpaceOnUse"><stop class="kwz2g5lgk"/><stop offset="1" class="mv5v459od"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-man-dark" /></template>
<style>
.a3z0rjbkf {
  d: path("M23.904 11.521a2 2 0 1 1 3.246-1.26l-.409 5.714c-.04.562-.508.998-1.071.998v-3.527a1 1 0 0 0-.366-.773l-1.403-1.15z");
}

.abh2gabji {
  stop-color: var(--svg-color--351e26, #351E26);
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.aq7827bba {
  stop-color: var(--svg-color--8f8286, #8F8286);
}

.ay4s1-bcp {
  stop-color: var(--svg-color--40292a, #40292A);
}

.baf2i9bsp {
  stop-color: var(--svg-color--624d4a, #624D4A);
  stop-opacity: 0;
}

.bddxqszam {
  stop-color: var(--svg-color--b1adb0, #B1ADB0);
}

.bh4i2qbfz {
  d: path("M7.218 21.213a3.152 3.152 0 1 0 0-6.303a3.152 3.152 0 0 0 0 6.303");
}

.bmkvcoycx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.389 12.668c.883-.07 2.195.039 3.258.844");
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bwtw0srgi {
  stop-color: var(--svg-color--b1adb0, #B1ADB0);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d69huhboq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.04 16.422c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dtgynupor {
  stroke: var(--svg-color--8a8a8a, #8A8A8A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("M12.951 12.973c-.71-.094-2.086-.079-3.164.812");
}

.dxex1chqi {
  fill: var(--svg-color--452c29, #452C29);
  d: path("M18.11 18.756a.5.5 0 0 1 .706.04c.195.218.377.369.612.473c.24.106.575.18 1.095.18a.5.5 0 0 1 0 1c-.612 0-1.094-.086-1.499-.265c-.409-.181-.701-.44-.954-.722a.5.5 0 0 1 .04-.706");
}

.dzx4x3b-q {
  stop-color: var(--svg-color--5e4c49, #5E4C49);
}

.egw5g_y4s {
  cx: 11.516px;
  cy: 16.781px;
  rx: 0.726px;
  ry: 0.368px;
}

.eja54ndmj {
  d: path("M8.356 11.521a2 2 0 1 0-3.245-1.26l.407 5.714c.04.562.508.99 1.072.99v-3.519a1 1 0 0 1 .366-.773l1.403-1.15z");
}

.f36on8j_k {
  stop-color: var(--svg-color--2e1a1c, #2E1A1C);
  stop-opacity: 0;
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.feb82lhbu {
  d: path("m24.11 8.542l-5.739 1.914a1.953 1.953 0 0 0 .877 3.788l5.706-.764z");
}

.fj_enu3ru {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
  stop-opacity: 0;
}

.fnb-_ubqy {
  stop-color: var(--svg-color--3b2926, #3B2926);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fo3bwns7p {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.632 15.563c-1.218 0-2.246.84-2.526 1.974a.51.51 0 0 0 .499.636h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.103");
}

.ft5dv1b6b {
  fill: none;
}

.gnkeuhb_f {
  stop-color: var(--svg-color--463836, #463836);
}

.grtw3qb5s {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.638 17.857l-1.571 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.9-3.1c-.227-.655-.429-.7-.729 0");
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.h86xvuobt {
  d: path("M12.018 16.07a1.664 1.664 0 0 0-1.604 2.103h3.215c.037-.144.06-.288.06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.hb068sutp {
  d: path("M13.538 17.539c0-.538-.437-.897-.556-1.005l-.537.52l.33.674z");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.iynd1m6ic {
  fill: var(--svg-color--000, #000);
  d: path("M19.209 17.734c0-.53.423-.953.953-.953s.953.424.953.953c0 .159-.038.31-.106.439h-1.687a.86.86 0 0 1-.113-.439");
}

.jt9sfd_8g {
  d: path("M7.218 20.057a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.k7jpzyb2w {
  d: path("M15.27 4.473c-5.2 0-9.2 4.4-8.9 9.5l.8 10.4c.3 3.3 2.8 5.6 6 5.6h6c3.1 0 5.7-2.3 6-5.6l.7-10.4c.4-5.2-3.7-9.5-8.9-9.5z");
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kj6bsmvmy {
  fill: var(--svg-color--362221, #362221);
  d: path("M13.335 18.784a.5.5 0 0 1 .724.69h-.001l-.002.003l-.004.004l-.011.011a2 2 0 0 1-.169.151a3.56 3.56 0 0 1-2.255.806a.5.5 0 1 1 0-1a2.56 2.56 0 0 0 1.718-.665");
}

.ksg_hcc-p {
  stop-color: var(--svg-color--40233b, #40233B);
}

.ku8peobxx {
  d: path("m15.567 17.58l-1 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.956-3.1c-.226-.654-.944-.7-1.244 0");
}

.kwgrcj4xm {
  stop-color: var(--svg-color--341d1c, #341D1C);
}

.kwz2g5lgk {
  stop-color: var(--svg-color--a8a7a9, #A8A7A9);
}

.l9fk14bxd {
  stop-color: var(--svg-color--735551, #735551);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmxrxmb4i {
  d: path("M20.04 16.422c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.moydr9c6g {
  stop-color: var(--svg-color--31201f, #31201F);
}

.mq-q1xiwv {
  d: path("M21.644 17.515a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.425z");
}

.mv5v459od {
  stop-color: var(--svg-color--a8a7a9, #A8A7A9);
  stop-opacity: 0;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohys34b9r {
  stop-color: var(--svg-color--332321, #332321);
}

.p1j5i8b3n {
  fill: var(--svg-color--9f9aa1, #9F9AA1);
  d: path("M23.904 11.521a2 2 0 1 1 3.246-1.26l-.409 5.714c-.04.562-.508.998-1.071.998v-3.527a1 1 0 0 0-.366-.773l-1.403-1.15z");
}

.p7wwt2b_k {
  stop-color: var(--svg-color--685654, #685654);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q-99_hbdo {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.567 17.58l-1 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.956-3.1c-.226-.654-.944-.7-1.244 0");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rlhs-hbwc {
  stop-color: var(--svg-color--bbb6b3, #BBB6B3);
}

.rr9ivbbgg {
  stop-color: var(--svg-color--2e1a1c, #2E1A1C);
}

.rsot6ubhk {
  stop-color: var(--svg-color--341d1c, #341D1C);
  stop-opacity: 0;
}

.rx61x1b9v {
  width: 6px;
  height: 1px;
  x: 13.17px;
  y: 7.116px;
  rx: 0.5px;
}

.s-gwt1b5z {
  cx: 11.516px;
  cy: 16.781px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.tco_4qs8v {
  stop-color: var(--svg-color--8f8286, #8F8286);
  stop-opacity: 0;
}

.tg7j0e4gw {
  stop-color: var(--svg-color--624d4a, #624D4A);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.umqdi2bdz {
  stroke: var(--svg-color--8a8a8a, #8A8A8A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("M19.389 12.973c.71-.094 2.086-.079 3.164.812");
}

.uyez41bsl {
  stop-color: var(--svg-color--735551, #735551);
  stop-opacity: 0;
}

.vxcq24b1n {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.547 15.563c1.218 0 2.247.84 2.526 1.974a.51.51 0 0 1-.499.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.103");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wanvse71t {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.61 23.149a.335.335 0 0 0-.4.069a.305.305 0 0 0-.034.393a3.58 3.58 0 0 0 2.994 1.6a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.397a.34.34 0 0 0-.4-.065a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.221-2.56-.607Z");
}

.wd2gaqb2r {
  d: path("M24.954 20.057a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.wgw2105cx {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
}

.whrd19cql {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.951 12.668c-.883-.07-2.195.039-3.258.844");
}

.wkt27vamq {
  d: path("M24.954 21.213a3.152 3.152 0 1 0 0-6.303a3.152 3.152 0 0 0 0 6.303");
}

.wmtchzb1q {
  d: path("M20.162 16.07a1.664 1.664 0 0 1 1.603 2.103h-3.214a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.67-1.664");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xi80kbc0k {
  stop-color: var(--svg-color--807680, #807680);
  stop-opacity: 0;
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xulak8-hu {
  stop-color: var(--svg-color--482a36, #482A36);
  stop-opacity: 0;
}

.xw5vrmbua {
  fill: var(--svg-color--000, #000);
  d: path("M12.97 17.734a.95.95 0 0 0-.952-.953a.95.95 0 0 0-.953.953c0 .159.037.31.106.439h1.686a.95.95 0 0 0 .114-.439");
}

.ylgm7jlye {
  stop-color: var(--svg-color--5e4c49, #5E4C49);
  stop-opacity: 0;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z1ac9ioef {
  fill: var(--svg-color--463133, #463133);
  d: path("M24.954 20.057a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.z5_8k6fyg {
  stop-color: var(--svg-color--351e26, #351E26);
  stop-opacity: 0;
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zjp518bgo {
  fill: var(--svg-color--7f7680, #7F7680);
  d: path("M8.356 11.521a2 2 0 1 0-3.245-1.26l.407 5.714c.04.562.508.99 1.072.99v-3.519a1 1 0 0 1 .366-.773l1.403-1.15z");
}

.zpqiekbmq {
  stop-color: var(--svg-color--543733, #543733);
}

.zs1u76b3p {
  stop-color: var(--svg-color--5d4139, #5D4139);
}

.zzsbp5bdy {
  width: 10px;
  height: 1px;
  x: 11.126px;
  y: 9.495px;
  rx: 0.5px;
}

</style>
