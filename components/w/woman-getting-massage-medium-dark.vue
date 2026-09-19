<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iYAOztd)"><path fill="url(#iBLebJe)" class="vvxgj6bpi"/><path fill="url(#i6ataMe)" class="vvxgj6bpi"/></g><path fill="url(#iYqpaEd)" class="vvxgj6bpi"/><path fill="url(#ixAyHpb)" class="vvxgj6bpi"/><g filter="url(#ijUPj0a)"><path fill="url(#i7Lqr3b)" class="rot1mr63h"/><path fill="url(#i3kKGod)" class="rot1mr63h"/></g><g filter="url(#iPIEKWc)"><path fill="url(#ivG6lle)" class="blj2xuvve"/><path fill="url(#iMZvxVb)" class="blj2xuvve"/></g><circle fill="url(#isNE04d)" class="nserplb1x"/><g filter="url(#iAh2EGb)" class="mc2zb0bvp"><circle class="sx37nvevz"/></g><circle fill="url(#ieZpuJe)" class="f-z1ozvrb"/><circle fill="url(#icT5FpW)" class="f-z1ozvrb"/><g filter="url(#imjnf4c)"><circle fill="url(#iE1N0le)" class="i4ojxgbvw"/></g><g filter="url(#iAYWiId)"><circle fill="url(#i3y1Erb)" class="m__z0mykh"/></g><path class="gkh8e4-ou"/><path fill="url(#iy7Ttjc)" class="q6gx3quyt"/><path fill="url(#iZnjSre)" class="q6gx3quyt"/><g filter="url(#iNuGg9A)"><rect fill="url(#iSfC4tb)" class="j8z-42s7e"/></g><rect fill="url(#iLQtodd)" class="j8z-42s7e"/><g filter="url(#iEJHgwe)"><path fill="url(#i2Js7Dc)" class="wvp0mabjb"/><path class="ln54gbb5x"/></g><g filter="url(#izzffBe)"><path class="uurfewwpg"/></g><g filter="url(#imUNDge)"><path fill="url(#i5InKZB)" class="q7vyx3bsm"/><path fill="url(#iropwlb)" class="q7vyx3bsm"/><path fill="url(#ic0hzhV)" class="q7vyx3bsm"/><path fill="url(#iXtUkyd)" class="q7vyx3bsm"/></g><g filter="url(#izJZvsh)"><path fill="url(#iVx9FMe)" class="z_1jymb2l"/><path fill="url(#iTJLdve)" class="z_1jymb2l"/></g><g filter="url(#iO5ycgb)"><circle fill="url(#iA0q76c)" class="l_flc0gwk"/></g><g filter="url(#igQvfXb)"><path class="jgch5xaxj"/></g><g filter="url(#iOlZQpj)"><path stroke="url(#ilsqcKe)" class="gti-w2qfb"/></g><g filter="url(#i2vv3Gc)"><path class="mbzj6u4qb"/></g><g filter="url(#iKULete)"><path stroke="url(#iK9iMOe)" class="e2arxx8zo"/></g><path stroke="url(#iLSzUpb)" class="df2hh16wk"/><g filter="url(#iBlpc3d)"><path stroke="url(#ihRusvc)" class="lplgdxbdh"/></g><path stroke="url(#iHV2kbc)" class="q_3fqdbeg"/><g filter="url(#iZooW6b)"><path stroke="url(#iG9hKJb)" class="f1zc5ekne"/></g><g filter="url(#iDbHwjK)"><path class="lyu78b3jt"/></g><path class="th6rwg1-k"/><path fill="url(#i6MN6ae)" class="bnm8uzbww"/><path fill="url(#idzvEKe)" class="bnm8uzbww"/><path fill="url(#ike5XDe)" class="bnm8uzbww"/><g filter="url(#iXd8Tyo)"><path stroke="url(#iSgKaYw)" class="j37u4rb-f"/></g><path class="uj-xnbx6b"/><g filter="url(#iYk15nd)"><path fill="url(#iswkPyc)" class="j9i9zyb7u"/></g><g filter="url(#imiQT6d)"><path class="o-mo64bqj"/><path fill="url(#iq7Gkxe)" class="vod-dschj"/></g><g filter="url(#iGS53Cb)"><path class="v43gb7bwy"/></g><g filter="url(#ihyNY0b)"><path fill="url(#iJiiNdb)" class="ievfp3btw"/></g><g filter="url(#iLX7ppb)"><path fill="url(#iBhzobd)" class="r7917jlmh"/></g><g filter="url(#i7ztQdd)"><path fill="url(#iEBQ1Tb)" class="vf_3ecbae"/><path fill="url(#ifySmJd)" class="vf_3ecbae"/></g><defs><radialGradient id="iBLebJe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.313)" gradientUnits="userSpaceOnUse"><stop class="oof-goujs"/><stop offset=".832" class="y-z81-bua"/></radialGradient><radialGradient id="i6ataMe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.16617 -7.1847 8.98984 -5.2129 23.982 28.248)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="r-5ctobwv"/><stop offset="1" class="b2cgmuy3t"/></radialGradient><radialGradient id="iYqpaEd" cx="0" cy="0" r="1" gradientTransform="rotate(155.64 5.706 11.329)scale(10.8979 4.51152)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="rc0rszb3u"/><stop offset="1" class="k4lo-hb9q"/></radialGradient><radialGradient id="ixAyHpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.5924 15.2389 0 16 30.313)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="xxerewdbl"/><stop offset=".977" class="rjclg2bzq"/></radialGradient><radialGradient id="i7Lqr3b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.56244 7.87504 -7.63171 -5.39056 25.318 13.875)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="g4z-_-bgs"/><stop offset="1" class="pi95o6_xg"/></radialGradient><radialGradient id="i3kKGod" cx="0" cy="0" r="1" gradientTransform="rotate(147.139 10.128 11.737)scale(2.75089 2.7814)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="us-_kefmy"/><stop offset="1" class="o8kgn-caf"/></radialGradient><radialGradient id="ivG6lle" cx="0" cy="0" r="1" gradientTransform="rotate(152.281 3.899 10.46)scale(4.87131 9.06872)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="mdv8kdn7c"/><stop offset="1" class="rbs0vnbur"/></radialGradient><radialGradient id="iMZvxVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82006 6.3586 -4.4708 -1.2797 9.243 10.893)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="ayx0qhcan"/><stop offset="1" class="nx9mshbyu"/></radialGradient><radialGradient id="isNE04d" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.223 17.133)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="p236k5fti"/><stop offset="1" class="g2vlv9bfh"/></radialGradient><radialGradient id="ieZpuJe" cx="0" cy="0" r="1" gradientTransform="rotate(142.158 9.224 11.084)scale(1.19705 1.26073)" gradientUnits="userSpaceOnUse"><stop class="s9x1nlbef"/><stop offset="1" class="xo4w8qb_a"/></radialGradient><radialGradient id="icT5FpW" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.592 21.027)scale(2.34213)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="w08_jhbkt"/><stop offset="1" class="etv5nzb3o"/></radialGradient><radialGradient id="iE1N0le" cx="0" cy="0" r="1" gradientTransform="matrix(.69531 0 0 .82031 21.666 14.584)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="gq6390b8n"/><stop offset="1" class="htw9qedrj"/></radialGradient><radialGradient id="i3y1Erb" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 13.942)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cibck0b0g"/><stop offset=".902" class="ghvr_e1bi"/></radialGradient><radialGradient id="iy7Ttjc" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.189 14.596)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="wzapgli4e"/><stop offset="1" class="vnuk5ibgy"/></radialGradient><radialGradient id="iZnjSre" cx="0" cy="0" r="1" gradientTransform="rotate(65.607 -8.55 21.129)scale(3.12035 6.31255)" gradientUnits="userSpaceOnUse"><stop class="rzvl5tbzx"/><stop offset="1" class="vonrxsbes"/></radialGradient><radialGradient id="iSfC4tb" cx="0" cy="0" r="1" gradientTransform="rotate(174.247 9.378 7.946)scale(6.06562 7.0411)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="xrik-2bjb"/><stop offset="1" class="x6-sayl6h"/></radialGradient><radialGradient id="iLQtodd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.0892 -11.3554 0 16 10.975)" gradientUnits="userSpaceOnUse"><stop offset=".726" class="lbfiabp4p"/><stop offset="1" class="e9t270bgc"/></radialGradient><radialGradient id="i2Js7Dc" cx="0" cy="0" r="1" gradientTransform="matrix(1.05598 2.75833 -1.5163 .5805 11.308 7.168)" gradientUnits="userSpaceOnUse"><stop class="f7m1yfx-m"/><stop offset="1" class="p3lw01bbh"/></radialGradient><radialGradient id="i5InKZB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37502 5.34375 -6.41397 -1.6504 17.88 4.74)" gradientUnits="userSpaceOnUse"><stop class="e9ucyqbno"/><stop offset=".722" class="dg1fw7bjy"/></radialGradient><radialGradient id="iropwlb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06252 -1.68749 2.8938 3.53691 10.819 10.187)" gradientUnits="userSpaceOnUse"><stop class="pd7y1ouls"/><stop offset="1" class="e7x0i9zao"/></radialGradient><radialGradient id="ic0hzhV" cx="0" cy="0" r="1" gradientTransform="rotate(-144.811 12.391 1.866)scale(2.98253 5.11462)" gradientUnits="userSpaceOnUse"><stop class="uchbj6dck"/><stop offset="1" class="cc23txbjg"/></radialGradient><radialGradient id="iXtUkyd" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -1.96875 .58437 .85337 11.224 6.752)" gradientUnits="userSpaceOnUse"><stop class="s6rweorkb"/><stop offset="1" class="dx9qcmbbp"/></radialGradient><radialGradient id="iVx9FMe" cx="0" cy="0" r="1" gradientTransform="rotate(-58.443 17.078 -10.404)scale(4.65751 13.5396)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="p2uy0ugth"/><stop offset=".952" class="sjdbjmbbs"/></radialGradient><radialGradient id="iTJLdve" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36877 -1.375 .63373 -1.09174 18.662 9.522)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="gb_aapvap"/><stop offset="1" class="hb9gybh8f"/></radialGradient><radialGradient id="iA0q76c" cx="0" cy="0" r="1" gradientTransform="rotate(-62.753 18.25 -4.13)scale(1.90544 2.10594)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="q_zq8lcfj"/><stop offset=".902" class="ru61jfres"/></radialGradient><radialGradient id="iLSzUpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.578)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="tf917uigd"/><stop offset="1" class="e974r34pq"/></radialGradient><radialGradient id="iHV2kbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.578)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="tf917uigd"/><stop offset="1" class="e974r34pq"/></radialGradient><radialGradient id="idzvEKe" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 16.758)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="w0_gpw3io"/><stop offset="1" class="kf-afnfjo"/></radialGradient><radialGradient id="ike5XDe" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.542 15.959)" gradientUnits="userSpaceOnUse"><stop class="cbh83mbyh"/><stop offset="1" class="hnph1r6ss"/></radialGradient><radialGradient id="iSgKaYw" cx="0" cy="0" r="1" gradientTransform="rotate(-62.526 22.567 -3.115)scale(.44028 1.97794)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="chi8d6bxi"/><stop offset="1" class="y34pxebel"/></radialGradient><radialGradient id="iq7Gkxe" cx="0" cy="0" r="1" gradientTransform="rotate(-124.468 8.78 2.243)scale(3.17497 1.5867)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="l25dhacin"/><stop offset="1" class="o0smz_bvt"/></radialGradient><radialGradient id="iJiiNdb" cx="0" cy="0" r="1" gradientTransform="matrix(5.87065 -6.2812 5.44456 5.0887 18.354 9.816)" gradientUnits="userSpaceOnUse"><stop class="txpy_zznj"/><stop offset="1" class="vfm0_vraw"/><stop offset="1" class="l5m7qflal"/></radialGradient><radialGradient id="iEBQ1Tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 11.1 6.347)" gradientUnits="userSpaceOnUse"><stop class="l714dnucg"/><stop offset="1" class="mzzxgdkuh"/></radialGradient><radialGradient id="ifySmJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.402 9.826)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="qhhfhnb7p"/><stop offset="1" class="c0ejuub7c"/></radialGradient><filter id="iYAOztd" width="21.451" height="8.965" x="5.649" y="20.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.27451 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24260"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.376471 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24260" result="effect2_innerShadow_3987_24260"/></filter><filter id="ijUPj0a" width="8.434" height="11.989" x="16.543" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.0313726 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24260"/></filter><filter id="iPIEKWc" width="8.784" height="12.039" x="7.173" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.227451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24260"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.0156863 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24260" result="effect2_innerShadow_3987_24260"/></filter><filter id="iAh2EGb" width="2.986" height="2.986" x="9.111" y="12.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".1"/></filter><filter id="imjnf4c" width="2.986" height="2.986" x="19.904" y="12.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".1"/></filter><filter id="iAYWiId" width="3.829" height="3.829" x="11.609" y="11.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".25"/></filter><filter id="iNuGg9A" width="12.021" height="15.258" x="10.24" y="5.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.380392 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24260"/></filter><filter id="iEJHgwe" width="8.186" height="14.251" x="8.271" y="1.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".5"/></filter><filter id="izzffBe" width="8.186" height="10.454" x="15.46" y="5.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".5"/></filter><filter id="imUNDge" width="11.186" height="6.923" x="10.508" y="4.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0470588 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24260"/></filter><filter id="izJZvsh" width="8.715" height="5.797" x="11.935" y="4.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".125"/></filter><filter id="iO5ycgb" width="3.66" height="3.66" x="11.885" y="11.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".25"/></filter><filter id="igQvfXb" width="2.699" height="1.214" x="11.797" y="11.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24260"/></filter><filter id="iOlZQpj" width="2.399" height=".914" x="11.847" y="11.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".075"/></filter><filter id="i2vv3Gc" width="2.699" height="1.214" x="17.703" y="11.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24260"/></filter><filter id="iKULete" width="2.399" height=".914" x="17.753" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".075"/></filter><filter id="iBlpc3d" width="2.618" height=".92" x="12.269" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".075"/></filter><filter id="iZooW6b" width="2.618" height=".92" x="17.16" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".075"/></filter><filter id="iDbHwjK" width="3.122" height="4.211" x="14.162" y="13.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".25"/></filter><filter id="iXd8Tyo" width="4.199" height="1.729" x="13.906" y="17.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".05"/></filter><filter id="iYk15nd" width="2.811" height="6.368" x="8.719" y="8.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".375"/></filter><filter id="imiQT6d" width="6.686" height="12.645" x="8.688" y="2.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.27451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24260"/></filter><filter id="iGS53Cb" width="6.436" height="12.695" x="17.329" y="2.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.227451 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24260"/></filter><filter id="ihyNY0b" width="5.843" height="12.292" x="17.92" y="2.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".25"/></filter><filter id="iLX7ppb" width="2.811" height="6.368" x="8.808" y="8.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".375"/></filter><filter id="i7ztQdd" width="5.14" height="8.355" x="9.763" y="1.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24260" stdDeviation=".25"/></filter><linearGradient id="ilsqcKe" x1="14.021" x2="11.81" y1="12.044" y2="12.508" gradientUnits="userSpaceOnUse"><stop class="c-eczdzuc"/><stop offset="1" class="gwgqzlb4u"/></linearGradient><linearGradient id="iK9iMOe" x1="17.979" x2="20.19" y1="11.989" y2="12.453" gradientUnits="userSpaceOnUse"><stop class="c-eczdzuc"/><stop offset="1" class="gwgqzlb4u"/></linearGradient><linearGradient id="ihRusvc" x1="14.936" x2="12.494" y1="13.984" y2="13.984" gradientUnits="userSpaceOnUse"><stop offset=".045" class="m97csacbr"/><stop offset=".32" class="ppgoehb9j"/><stop offset=".794" class="ppgoehb9j"/><stop offset="1" class="hxk020qex"/></linearGradient><linearGradient id="iG9hKJb" x1="19.826" x2="17.385" y1="13.984" y2="13.984" gradientUnits="userSpaceOnUse"><stop offset=".045" class="m97csacbr"/><stop offset=".32" class="ppgoehb9j"/><stop offset=".794" class="ppgoehb9j"/><stop offset="1" class="hxk020qex"/></linearGradient><linearGradient id="i6MN6ae" x1="16.886" x2="15.849" y1="15.49" y2="15.54" gradientUnits="userSpaceOnUse"><stop offset=".106" class="gt5mw9brj"/><stop offset="1" class="wmgou6bmf"/></linearGradient><linearGradient id="iswkPyc" x1="10.124" x2="10.124" y1="13.097" y2="8.266" gradientUnits="userSpaceOnUse"><stop class="n6_y6k2_m"/><stop offset="1" class="bd1m8wbbp"/></linearGradient><linearGradient id="iBhzobd" x1="10.214" x2="10.214" y1="13.329" y2="8.498" gradientUnits="userSpaceOnUse"><stop class="n7gad4bzu"/><stop offset="1" class="ejsfj0d0t"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-getting-massage-medium-dark" /></template>
<style>
.ayx0qhcan {
  stop-color: var(--svg-color--4c4442, #4C4442);
}

.b2cgmuy3t {
  stop-color: var(--svg-color--9574dd, #9574DD);
  stop-opacity: 0;
}

.bd1m8wbbp {
  stop-color: var(--svg-color--ffcb3b, #FFCB3B);
  stop-opacity: 0;
}

.blj2xuvve {
  d: path("M8.154 11.876c.56-.982.53-1.722.638-2.036l6.665 2.824v8.915h-3.72c-2.443 0-3.523-1.02-4.003-2.22s-.28-2.132-.06-2.795a1.54 1.54 0 0 0-.03-.998c-.452-1.252-.176-2.49.51-3.69");
}

.bnm8uzbww {
  d: path("M16 13.625a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.262");
}

.c-eczdzuc {
  stop-color: var(--svg-color--453a3a, #453A3A);
}

.c0ejuub7c {
  stop-color: var(--svg-color--9a7b72, #9A7B72);
  stop-opacity: 0;
}

.cbh83mbyh {
  stop-color: var(--svg-color--97736e, #97736E);
}

.cc23txbjg {
  stop-color: var(--svg-color--190d13, #190D13);
  stop-opacity: 0;
}

.chi8d6bxi {
  stop-color: var(--svg-color--886667, #886667);
}

.cibck0b0g {
  stop-color: var(--svg-color--ffb129, #FFB129);
}

.df2hh16wk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 13.984c.146.164.536.45 1.024.47c.617.023.949-.306 1.144-.47");
}

.dg1fw7bjy {
  stop-color: var(--svg-color--29151d, #29151D);
}

.dx9qcmbbp {
  stop-color: var(--svg-color--595757, #595757);
  stop-opacity: 0;
}

.e2arxx8zo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.928 12.453c-.258-.207-.883-.578-1.95-.43");
}

.e7x0i9zao {
  stop-color: var(--svg-color--190a1e, #190A1E);
  stop-opacity: 0;
}

.e974r34pq {
  stop-color: var(--svg-color--392c2b, #392C2B);
}

.e9t270bgc {
  stop-color: var(--svg-color--6c394e, #6C394E);
}

.e9ucyqbno {
  stop-color: var(--svg-color--423539, #423539);
}

.ejsfj0d0t {
  stop-color: var(--svg-color--886361, #886361);
  stop-opacity: 0;
}

.etv5nzb3o {
  stop-color: var(--svg-color--7e4950, #7E4950);
}

.f-z1ozvrb {
  cx: 21.396px;
  cy: 14.365px;
  r: 1.979px;
}

.f1zc5ekne {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 13.984c.146.164.536.45 1.023.47c.617.023.95-.306 1.145-.47");
}

.f7m1yfx-m {
  stop-color: var(--svg-color--9b4607, #9B4607);
}

.ft5dv1b6b {
  fill: none;
}

.g2vlv9bfh {
  stop-color: var(--svg-color--653747, #653747);
}

.g4z-_-bgs {
  stop-color: var(--svg-color--3b2f33, #3B2F33);
}

.gb_aapvap {
  stop-color: var(--svg-color--3e2f35, #3E2F35);
}

.ghvr_e1bi {
  stop-color: var(--svg-color--f39423, #F39423);
}

.gkh8e4-ou {
  fill: var(--svg-color--824f50, #824F50);
  d: path("M13.75 20a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.gq6390b8n {
  stop-color: var(--svg-color--815f57, #815F57);
}

.gt5mw9brj {
  stop-color: var(--svg-color--98746c, #98746C);
}

.gti-w2qfb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.508c.258-.207.883-.578 1.95-.43");
}

.gwgqzlb4u {
  stop-color: var(--svg-color--453a3a, #453A3A);
  stop-opacity: 0;
}

.hb9gybh8f {
  stop-color: var(--svg-color--3e2f35, #3E2F35);
  stop-opacity: 0;
}

.hnph1r6ss {
  stop-color: var(--svg-color--97736e, #97736E);
  stop-opacity: 0;
}

.htw9qedrj {
  stop-color: var(--svg-color--7d5047, #7D5047);
}

.hxk020qex {
  stop-color: var(--svg-color--3d3133, #3D3133);
}

.i4ojxgbvw {
  cx: 21.396px;
  cy: 14.365px;
  r: 1.293px;
}

.ievfp3btw {
  d: path("M21.21 8.363L19.187 9.85c-.244.18-.47.42-.676.196c-.22-.238-.007-.337.229-.56a52 52 0 0 1 1.99-1.785c.875-.734.85-2.109.828-2.57V2.554h1.704v10.713a.579.579 0 0 1-1.158 0V9.03c0-.402-.571-.906-.896-.667");
}

.j37u4rb-f {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.333c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.457-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135Z");
}

.j8z-42s7e {
  width: 11.521px;
  height: 15.258px;
  x: 10.24px;
  y: 5.806px;
  rx: 5.76px;
}

.j9i9zyb7u {
  d: path("m9.469 9.011l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.jgch5xaxj {
  stroke: var(--svg-color--322221, #322221);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.072 12.508c.258-.207.883-.578 1.95-.43");
}

.k4lo-hb9q {
  stop-color: var(--svg-color--7c4fa2, #7C4FA2);
  stop-opacity: 0;
}

.kf-afnfjo {
  stop-color: var(--svg-color--7e4757, #7E4757);
  stop-opacity: 0;
}

.l_flc0gwk {
  cx: 13.715px;
  cy: 13.326px;
  r: 1.33px;
}

.l25dhacin {
  stop-color: var(--svg-color--673742, #673742);
}

.l5m7qflal {
  stop-color: var(--svg-color--906f68, #906F68);
  stop-opacity: 0;
}

.l714dnucg {
  stop-color: var(--svg-color--a07e73, #A07E73);
}

.lbfiabp4p {
  stop-color: var(--svg-color--754257, #754257);
  stop-opacity: 0;
}

.ln54gbb5x {
  fill: var(--svg-color--3c1b1c, #3C1B1C);
  d: path("m9.271 2.405l1.516 5.892l1.938-.904c0 .34.199-.381.656 0a78 78 0 0 1 1.727 1.632c.476.46.463 1.207-.027 1.653c-.453.413-1.088.349-1.552-.053l-.98-.713a.54.54 0 0 0-.747.042a.5.5 0 0 0-.132.337V13.5c0 .639-.537 1.156-1.2 1.156s-1.199-.518-1.199-1.156z");
}

.lplgdxbdh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 13.984c.146.164.536.45 1.024.47c.617.023.949-.306 1.144-.47");
}

.lyu78b3jt {
  fill: var(--svg-color--76434f, #76434F);
  d: path("M15.872 13.71c-.163 0-.248.094-.297.255l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.161-.045-.254-.209-.254");
}

.m__z0mykh {
  cx: 13.524px;
  cy: 13.242px;
  r: 1.415px;
}

.m97csacbr {
  stop-color: var(--svg-color--44393a, #44393A);
}

.mbzj6u4qb {
  stroke: var(--svg-color--322221, #322221);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.928 12.508c-.258-.207-.883-.578-1.95-.43");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mdv8kdn7c {
  stop-color: var(--svg-color--1d1519, #1D1519);
}

.mzzxgdkuh {
  stop-color: var(--svg-color--a07e73, #A07E73);
  stop-opacity: 0;
}

.n6_y6k2_m {
  stop-color: var(--svg-color--ffca3e, #FFCA3E);
}

.n7gad4bzu {
  stop-color: var(--svg-color--886361, #886361);
}

.nserplb1x {
  cx: 10.604px;
  cy: 14.365px;
  r: 1.979px;
}

.nx9mshbyu {
  stop-color: var(--svg-color--4c4442, #4C4442);
  stop-opacity: 0;
}

.o-mo64bqj {
  fill: var(--svg-color--845a56, #845A56);
  d: path("M8.688 2.271h3.426v3.484c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.88.393v3.327a1.2 1.2 0 1 1-2.398 0z");
}

.o0smz_bvt {
  stop-color: var(--svg-color--754d4c, #754D4C);
  stop-opacity: 0;
}

.o8kgn-caf {
  stop-color: var(--svg-color--444243, #444243);
  stop-opacity: 0;
}

.oof-goujs {
  stop-color: var(--svg-color--936dd4, #936DD4);
}

.p236k5fti {
  stop-color: var(--svg-color--643e41, #643E41);
}

.p2uy0ugth {
  stop-color: var(--svg-color--4a4445, #4A4445);
  stop-opacity: 0;
}

.p3lw01bbh {
  stop-color: var(--svg-color--d97513, #D97513);
}

.pd7y1ouls {
  stop-color: var(--svg-color--190a1e, #190A1E);
}

.pi95o6_xg {
  stop-color: var(--svg-color--231828, #231828);
}

.ppgoehb9j {
  stop-color: var(--svg-color--3b2e30, #3B2E30);
}

.q_3fqdbeg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 13.984c.146.164.536.45 1.023.47c.617.023.95-.306 1.145-.47");
}

.q_zq8lcfj {
  stop-color: var(--svg-color--724b4a, #724B4A);
}

.q6gx3quyt {
  d: path("M13.75 20a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.q7vyx3bsm {
  d: path("M13.209 8.49c-.782 1.248-2.158 2.114-2.7 2.314V6.655c.265 0 1.576-.141 2.168-.514c.694-.437 1.337-1.637 3.352-1.637c1.071 0 1.808.377 2.923 1.337c.882.652 2.182.697 2.743.652v4.534c-.517-.373-1.428-.41-1.846-.428h-3.375c-1.744 0-2.934-1.39-3.265-2.11");
}

.qhhfhnb7p {
  stop-color: var(--svg-color--9a7b72, #9A7B72);
}

.r-5ctobwv {
  stop-color: var(--svg-color--9574dd, #9574DD);
}

.r7917jlmh {
  d: path("m9.558 9.243l1.311.78v3.433a.655.655 0 1 1-1.31 0z");
}

.rbs0vnbur {
  stop-color: var(--svg-color--1e1424, #1E1424);
}

.rc0rszb3u {
  stop-color: var(--svg-color--6a3874, #6A3874);
}

.rjclg2bzq {
  stop-color: var(--svg-color--402452, #402452);
}

.rot1mr63h {
  d: path("M23.846 11.876c-.56-.982-.53-1.722-.639-2.036l-6.664 2.824v8.915h3.72c2.443 0 3.523-1.02 4.003-2.22s.28-2.132.06-2.795a1.54 1.54 0 0 1 .03-.998c.452-1.252.176-2.49-.51-3.69");
}

.ru61jfres {
  stop-color: var(--svg-color--6c3e49, #6C3E49);
}

.rzvl5tbzx {
  stop-color: var(--svg-color--6e3737, #6E3737);
}

.s6rweorkb {
  stop-color: var(--svg-color--464042, #464042);
}

.s9x1nlbef {
  stop-color: var(--svg-color--93736a, #93736A);
}

.sjdbjmbbs {
  stop-color: var(--svg-color--4a4445, #4A4445);
}

.sx37nvevz {
  cx: 10.604px;
  cy: 14.365px;
  r: 1.293px;
  fill: var(--svg-color--593138, #593138);
}

.tf917uigd {
  stop-color: var(--svg-color--2f182c, #2F182C);
}

.th6rwg1-k {
  fill: var(--svg-color--7e554d, #7E554D);
  d: path("M16 13.625a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.262");
}

.txpy_zznj {
  stop-color: var(--svg-color--906f68, #906F68);
}

.uchbj6dck {
  stop-color: var(--svg-color--190d13, #190D13);
}

.uj-xnbx6b {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M14.357 17.333c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.457-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135");
}

.us-_kefmy {
  stop-color: var(--svg-color--444243, #444243);
}

.uurfewwpg {
  fill: var(--svg-color--512e2f, #512E2F);
  d: path("M22.646 8.25H19.22l-.684-1.812c0 .352.457.528 0 .923a79 79 0 0 0-1.727 1.691a1.195 1.195 0 0 0 .027 1.715c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.v43gb7bwy {
  fill: var(--svg-color--764e49, #764E49);
  d: path("M23.515 2.271h-3.426v3.484c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.714c.454.429 1.09.362 1.555-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.vf_3ecbae {
  d: path("M10.263 5.37V2.472h1.468v3.534a1 1 0 0 0 .28.694l2.263 2.349a.46.46 0 0 1-.636.663l-2.364-2.094a3 3 0 0 1-1.011-2.246");
}

.vfm0_vraw {
  stop-color: var(--svg-color--675553, #675553);
  stop-opacity: 0;
}

.vnuk5ibgy {
  stop-color: var(--svg-color--9a6c63, #9A6C63);
  stop-opacity: 0;
}

.vod-dschj {
  d: path("M8.688 2.271h3.426v3.484c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.88.393v3.327a1.2 1.2 0 1 1-2.398 0z");
}

.vonrxsbes {
  stop-color: var(--svg-color--6e3737, #6E3737);
  stop-opacity: 0;
}

.vvxgj6bpi {
  d: path("M5.65 29.729h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.665");
}

.w0_gpw3io {
  stop-color: var(--svg-color--7e4757, #7E4757);
}

.w08_jhbkt {
  stop-color: var(--svg-color--7e4950, #7E4950);
  stop-opacity: 0;
}

.wmgou6bmf {
  stop-color: var(--svg-color--98746c, #98746C);
  stop-opacity: 0;
}

.wvp0mabjb {
  d: path("m9.271 2.405l1.516 5.892l1.938-.904c0 .34.199-.381.656 0a78 78 0 0 1 1.727 1.632c.476.46.463 1.207-.027 1.653c-.453.413-1.088.349-1.552-.053l-.98-.713a.54.54 0 0 0-.747.042a.5.5 0 0 0-.132.337V13.5c0 .639-.537 1.156-1.2 1.156s-1.199-.518-1.199-1.156z");
}

.wzapgli4e {
  stop-color: var(--svg-color--9a6c63, #9A6C63);
}

.x6-sayl6h {
  stop-color: var(--svg-color--734c49, #734C49);
}

.xo4w8qb_a {
  stop-color: var(--svg-color--815457, #815457);
}

.xrik-2bjb {
  stop-color: var(--svg-color--93655a, #93655A);
}

.xxerewdbl {
  stop-color: var(--svg-color--623e81, #623E81);
  stop-opacity: 0;
}

.y-z81-bua {
  stop-color: var(--svg-color--725698, #725698);
}

.y34pxebel {
  stop-color: var(--svg-color--886667, #886667);
  stop-opacity: 0;
}

.z_1jymb2l {
  d: path("M13.135 6.281c-.313.207-.83.466-.95.438c1.038 3.687 4.893 3.74 6.59 3.437L20.4 8.594V6.719c-1.164-.57-3.218-1.828-4.671-1.742s-2.204 1.046-2.594 1.304");
}

</style>
