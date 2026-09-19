<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iapxzBe)"><path fill="url(#iBLebJe)" class="vvxgj6bpi"/><path fill="url(#i6ataMe)" class="vvxgj6bpi"/></g><path fill="url(#iYqpaEd)" class="vvxgj6bpi"/><path fill="url(#ixAyHpb)" class="vvxgj6bpi"/><g filter="url(#iNL57Hb)"><path fill="url(#iW0Dq3C)" class="rot1mr63h"/><path fill="url(#i3kKGod)" class="rot1mr63h"/></g><g filter="url(#iFpKGNb)"><path fill="url(#i0lIjbj)" class="blj2xuvve"/><path fill="url(#iMZvxVb)" class="blj2xuvve"/></g><circle fill="url(#iDLrVVc)" class="nserplb1x"/><g filter="url(#iZxpHFd)" class="mc2zb0bvp"><circle class="qnvlgqbda"/></g><circle fill="url(#iwJMpYt)" class="f-z1ozvrb"/><circle fill="url(#iKAxnLc)" class="f-z1ozvrb"/><g filter="url(#iBnXzDb)"><circle fill="url(#imMGhDe)" class="i4ojxgbvw"/></g><g filter="url(#i0FILLd)"><circle fill="url(#i3y1Erb)" class="m__z0mykh"/></g><path class="h_keknbwg"/><path fill="url(#izeskPb)" class="q6gx3quyt"/><path fill="url(#izNLWVM)" class="q6gx3quyt"/><g filter="url(#izRGeLb)"><rect fill="url(#iJzNXgc)" class="j8z-42s7e"/></g><rect fill="url(#iZcGDod)" class="j8z-42s7e"/><g filter="url(#i2pqQrb)"><path fill="url(#i2Js7Dc)" class="wvp0mabjb"/><path class="tg833uend"/></g><g filter="url(#iTu4ebe)"><path class="xgr1jvbtp"/></g><g filter="url(#i1RV9kC)"><path fill="url(#iRZrOke)" class="q7vyx3bsm"/><path fill="url(#iropwlb)" class="q7vyx3bsm"/><path fill="url(#ic0hzhV)" class="q7vyx3bsm"/><path fill="url(#iQaos1c)" class="q7vyx3bsm"/></g><g filter="url(#iv4PjEd)"><path fill="url(#iWod57h)" class="z_1jymb2l"/><path fill="url(#iRuDcfc)" class="z_1jymb2l"/></g><g filter="url(#iqMQYqb)"><circle fill="url(#iI5DzYc)" class="l_flc0gwk"/></g><g filter="url(#izaXdWc)"><path class="j8s-5d-gn"/></g><g filter="url(#i0tkW8b)"><path stroke="url(#ivQFLnd)" class="gti-w2qfb"/></g><g filter="url(#icxQ0Ac)"><path class="kpblyoq0s"/></g><g filter="url(#ilcoEGe)"><path stroke="url(#i1sfzDd)" class="e2arxx8zo"/></g><path stroke="url(#iIvHfdd)" class="df2hh16wk"/><g filter="url(#iS2sfEb)"><path stroke="url(#iInIrkd)" class="lplgdxbdh"/></g><path stroke="url(#iPuFOOa)" class="q_3fqdbeg"/><g filter="url(#itQ33Gq)"><path stroke="url(#ik17Yfm)" class="f1zc5ekne"/></g><g filter="url(#i9hBJdb)"><path class="amg2zcclb"/></g><path class="avvho9bsk"/><path fill="url(#i8vZlSc)" class="bnm8uzbww"/><path fill="url(#iLfUAcU)" class="bnm8uzbww"/><path fill="url(#iYoZ6Id)" class="bnm8uzbww"/><g filter="url(#iuLrVFb)"><path stroke="url(#iCLJbje)" class="j37u4rb-f"/></g><path class="fya8so0hw"/><g filter="url(#iYrCnZd)"><path fill="url(#iswkPyc)" class="j9i9zyb7u"/></g><g filter="url(#iTfWSsc)"><path class="q_571zmbj"/><path fill="url(#ig8QwAe)" class="vod-dschj"/></g><g filter="url(#izEMApt)"><path class="az3nu1b6w"/></g><g filter="url(#iVUAT9y)"><path fill="url(#iFG06fd)" class="ievfp3btw"/></g><g filter="url(#iJUwi9c)"><path fill="url(#iHz1Hcb)" class="r7917jlmh"/></g><g filter="url(#i1Ts9pc)"><path fill="url(#ixdcOtd)" class="vf_3ecbae"/><path fill="url(#ifhtiNd)" class="vf_3ecbae"/></g><defs><radialGradient id="iBLebJe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.313)" gradientUnits="userSpaceOnUse"><stop class="oof-goujs"/><stop offset=".832" class="y-z81-bua"/></radialGradient><radialGradient id="i6ataMe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.16617 -7.1847 8.98984 -5.2129 23.982 28.248)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="r-5ctobwv"/><stop offset="1" class="b2cgmuy3t"/></radialGradient><radialGradient id="iYqpaEd" cx="0" cy="0" r="1" gradientTransform="rotate(155.64 5.706 11.329)scale(10.8979 4.51152)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="rc0rszb3u"/><stop offset="1" class="k4lo-hb9q"/></radialGradient><radialGradient id="ixAyHpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.5924 15.2389 0 16 30.313)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="xxerewdbl"/><stop offset=".977" class="rjclg2bzq"/></radialGradient><radialGradient id="iW0Dq3C" cx="0" cy="0" r="1" gradientTransform="matrix(-5.56244 7.87504 -7.63171 -5.39056 25.318 13.875)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="jywaqhbli"/><stop offset="1" class="rh917jb8x"/></radialGradient><radialGradient id="i3kKGod" cx="0" cy="0" r="1" gradientTransform="rotate(147.139 10.128 11.737)scale(2.75089 2.7814)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="us-_kefmy"/><stop offset="1" class="o8kgn-caf"/></radialGradient><radialGradient id="i0lIjbj" cx="0" cy="0" r="1" gradientTransform="rotate(152.281 3.899 10.46)scale(4.87131 9.06872)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="ywdwogbzt"/><stop offset="1" class="u0kksrmqh"/></radialGradient><radialGradient id="iMZvxVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82006 6.3586 -4.4708 -1.2797 9.243 10.893)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="ayx0qhcan"/><stop offset="1" class="nx9mshbyu"/></radialGradient><radialGradient id="iDLrVVc" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.223 17.133)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="phs3tubib"/><stop offset="1" class="grwnnnb5d"/></radialGradient><radialGradient id="iwJMpYt" cx="0" cy="0" r="1" gradientTransform="rotate(142.158 9.224 11.084)scale(1.19705 1.26073)" gradientUnits="userSpaceOnUse"><stop class="my0c8s4fp"/><stop offset="1" class="y581ksbre"/></radialGradient><radialGradient id="iKAxnLc" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.592 21.027)scale(2.34213)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="qtf9d8byq"/><stop offset="1" class="j9ig536pv"/></radialGradient><radialGradient id="imMGhDe" cx="0" cy="0" r="1" gradientTransform="matrix(.69531 0 0 .82031 21.666 14.584)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="gh1umgbbt"/><stop offset="1" class="lefbu6b0u"/></radialGradient><radialGradient id="i3y1Erb" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 13.942)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cibck0b0g"/><stop offset=".902" class="ghvr_e1bi"/></radialGradient><radialGradient id="izeskPb" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.189 14.596)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="ydm9ddced"/><stop offset="1" class="n_nhnibbq"/></radialGradient><radialGradient id="izNLWVM" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.8125 -5.89395 3.25184 14.513 21.219)" gradientUnits="userSpaceOnUse"><stop class="pj2xknbvf"/><stop offset="1" class="dit5vub-g"/></radialGradient><radialGradient id="iJzNXgc" cx="0" cy="0" r="1" gradientTransform="rotate(174.247 9.378 7.946)scale(6.06562 7.0411)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="b1hc77b2b"/><stop offset="1" class="b94-l-y5w"/></radialGradient><radialGradient id="iZcGDod" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.0892 -18.4627 0 16 10.975)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="zjwmqlbwo"/><stop offset=".953" class="spxm__abu"/></radialGradient><radialGradient id="i2Js7Dc" cx="0" cy="0" r="1" gradientTransform="matrix(1.05598 2.75833 -1.5163 .5805 11.308 7.168)" gradientUnits="userSpaceOnUse"><stop class="f7m1yfx-m"/><stop offset="1" class="p3lw01bbh"/></radialGradient><radialGradient id="iRZrOke" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37502 5.34375 -6.41397 -1.6504 17.88 4.74)" gradientUnits="userSpaceOnUse"><stop class="yo4_wwpln"/><stop offset=".722" class="boy1db52w"/></radialGradient><radialGradient id="iropwlb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06252 -1.68749 2.8938 3.53691 10.819 10.187)" gradientUnits="userSpaceOnUse"><stop class="pd7y1ouls"/><stop offset="1" class="e7x0i9zao"/></radialGradient><radialGradient id="ic0hzhV" cx="0" cy="0" r="1" gradientTransform="rotate(-144.811 12.391 1.866)scale(2.98253 5.11462)" gradientUnits="userSpaceOnUse"><stop class="uchbj6dck"/><stop offset="1" class="cc23txbjg"/></radialGradient><radialGradient id="iQaos1c" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 -2.5625 .76061 .94612 12.13 6.656)" gradientUnits="userSpaceOnUse"><stop class="spvl3-bel"/><stop offset="1" class="dx9qcmbbp"/></radialGradient><radialGradient id="iWod57h" cx="0" cy="0" r="1" gradientTransform="rotate(-58.443 17.078 -10.404)scale(4.65751 13.5396)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="tjm0n2v5h"/><stop offset=".952" class="vlw8-dbis"/></radialGradient><radialGradient id="iRuDcfc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36877 -1.375 .63373 -1.09174 18.662 9.522)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="inwx22uty"/><stop offset="1" class="q-trqsbdf"/></radialGradient><radialGradient id="iI5DzYc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.753 18.25 -4.13)scale(1.90544 2.10594)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="bo6sve4_m"/><stop offset=".902" class="aud44laqb"/></radialGradient><radialGradient id="iIvHfdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.578)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="vk3h5kjsq"/><stop offset="1" class="dsheu9oxu"/></radialGradient><radialGradient id="iPuFOOa" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.578)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="vk3h5kjsq"/><stop offset="1" class="dsheu9oxu"/></radialGradient><radialGradient id="iLfUAcU" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 16.758)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="q_3bb9b3h"/><stop offset="1" class="h65c54lsi"/></radialGradient><radialGradient id="iYoZ6Id" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.542 15.959)" gradientUnits="userSpaceOnUse"><stop class="x_31h1mma"/><stop offset="1" class="c7c54u04z"/></radialGradient><radialGradient id="iCLJbje" cx="0" cy="0" r="1" gradientTransform="rotate(-62.526 22.567 -3.115)scale(.44028 1.97794)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="j2uqjm0oz"/><stop offset="1" class="qf8pq8giw"/></radialGradient><radialGradient id="ig8QwAe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.9 10.67)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="e45b6kbci"/><stop offset="1" class="s4dmvvdkq"/></radialGradient><radialGradient id="iFG06fd" cx="0" cy="0" r="1" gradientTransform="matrix(5.87065 -6.2812 5.44456 5.0887 18.354 9.816)" gradientUnits="userSpaceOnUse"><stop class="cbx5-fbbx"/><stop offset="1" class="vfm0_vraw"/></radialGradient><radialGradient id="ixdcOtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 11.1 6.347)" gradientUnits="userSpaceOnUse"><stop class="p7wwt2b_k"/><stop offset="1" class="o1syipbau"/></radialGradient><radialGradient id="ifhtiNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.402 9.826)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="s4ff5rbng"/><stop offset="1" class="mqv57bcbp"/></radialGradient><filter id="iapxzBe" width="21.451" height="8.965" x="5.649" y="20.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.27451 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24257"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.376471 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24257" result="effect2_innerShadow_3987_24257"/></filter><filter id="iNL57Hb" width="8.434" height="11.989" x="16.543" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.0313726 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24257"/></filter><filter id="iFpKGNb" width="8.784" height="12.039" x="7.173" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.227451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24257"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.0156863 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24257" result="effect2_innerShadow_3987_24257"/></filter><filter id="iZxpHFd" width="2.986" height="2.986" x="9.111" y="12.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".1"/></filter><filter id="iBnXzDb" width="2.986" height="2.986" x="19.904" y="12.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".1"/></filter><filter id="i0FILLd" width="3.829" height="3.829" x="11.609" y="11.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".25"/></filter><filter id="izRGeLb" width="12.021" height="15.258" x="10.24" y="5.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.40335 0 0 0 0 0.308846 0 0 0 0 0.287845 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24257"/></filter><filter id="i2pqQrb" width="8.186" height="14.251" x="8.271" y="1.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".5"/></filter><filter id="iTu4ebe" width="8.186" height="10.454" x="15.46" y="5.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".5"/></filter><filter id="i1RV9kC" width="11.186" height="6.923" x="10.508" y="4.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.0470588 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24257"/></filter><filter id="iv4PjEd" width="8.715" height="5.797" x="11.935" y="4.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".125"/></filter><filter id="iqMQYqb" width="3.66" height="3.66" x="11.885" y="11.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".25"/></filter><filter id="izaXdWc" width="2.699" height="1.214" x="11.797" y="11.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24257"/></filter><filter id="i0tkW8b" width="2.399" height=".914" x="11.847" y="11.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".075"/></filter><filter id="icxQ0Ac" width="2.699" height="1.214" x="17.703" y="11.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24257"/></filter><filter id="ilcoEGe" width="2.399" height=".914" x="17.753" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".075"/></filter><filter id="iS2sfEb" width="2.618" height=".92" x="12.269" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".075"/></filter><filter id="itQ33Gq" width="2.618" height=".92" x="17.16" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".075"/></filter><filter id="i9hBJdb" width="3.122" height="4.211" x="14.162" y="13.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".25"/></filter><filter id="iuLrVFb" width="4.199" height="1.729" x="13.906" y="17.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".05"/></filter><filter id="iYrCnZd" width="2.811" height="6.368" x="8.719" y="8.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".375"/></filter><filter id="iTfWSsc" width="6.686" height="12.645" x="8.688" y="2.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24257"/></filter><filter id="izEMApt" width="6.436" height="12.695" x="17.329" y="2.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.137255 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24257"/></filter><filter id="iVUAT9y" width="5.843" height="12.292" x="17.92" y="2.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".25"/></filter><filter id="iJUwi9c" width="2.811" height="6.368" x="8.808" y="8.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".375"/></filter><filter id="i1Ts9pc" width="5.14" height="8.355" x="9.763" y="1.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24257" stdDeviation=".25"/></filter><linearGradient id="ivQFLnd" x1="14.021" x2="11.81" y1="12.044" y2="12.508" gradientUnits="userSpaceOnUse"><stop class="du3_mqevj"/><stop offset="1" class="hpzn95b1x"/></linearGradient><linearGradient id="i1sfzDd" x1="17.979" x2="20.19" y1="11.989" y2="12.453" gradientUnits="userSpaceOnUse"><stop class="du3_mqevj"/><stop offset="1" class="hpzn95b1x"/></linearGradient><linearGradient id="iInIrkd" x1="14.936" x2="12.494" y1="13.984" y2="13.984" gradientUnits="userSpaceOnUse"><stop offset=".045" class="d3bth9bgz"/><stop offset=".32" class="rulb4ox_k"/><stop offset=".794" class="rulb4ox_k"/><stop offset="1" class="omc-6wb_b"/></linearGradient><linearGradient id="ik17Yfm" x1="19.826" x2="17.385" y1="13.984" y2="13.984" gradientUnits="userSpaceOnUse"><stop offset=".045" class="d3bth9bgz"/><stop offset=".32" class="rulb4ox_k"/><stop offset=".794" class="rulb4ox_k"/><stop offset="1" class="omc-6wb_b"/></linearGradient><linearGradient id="i8vZlSc" x1="16.886" x2="15.849" y1="15.49" y2="15.54" gradientUnits="userSpaceOnUse"><stop offset=".106" class="cbx5-fbbx"/><stop offset="1" class="vfm0_vraw"/></linearGradient><linearGradient id="iswkPyc" x1="10.124" x2="10.124" y1="13.097" y2="8.266" gradientUnits="userSpaceOnUse"><stop class="n6_y6k2_m"/><stop offset="1" class="bd1m8wbbp"/></linearGradient><linearGradient id="iHz1Hcb" x1="10.214" x2="10.214" y1="13.329" y2="8.498" gradientUnits="userSpaceOnUse"><stop class="p-tc_9j4a"/><stop offset="1" class="a4q8d6dqq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-getting-massage-dark" /></template>
<style>
.a4q8d6dqq {
  stop-color: var(--svg-color--523c3c, #523C3C);
  stop-opacity: 0;
}

.amg2zcclb {
  fill: var(--svg-color--361b29, #361B29);
  d: path("M15.872 13.71c-.163 0-.248.094-.297.255l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.161-.045-.254-.209-.254");
}

.aud44laqb {
  stop-color: var(--svg-color--362325, #362325);
}

.avvho9bsk {
  fill: var(--svg-color--452e2c, #452E2C);
  d: path("M16 13.625a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.262");
}

.ayx0qhcan {
  stop-color: var(--svg-color--4c4442, #4C4442);
}

.az3nu1b6w {
  fill: var(--svg-color--3f2929, #3F2929);
  d: path("M23.515 2.271h-3.426v3.484c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.714c.454.429 1.09.362 1.555-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.b1hc77b2b {
  stop-color: var(--svg-color--4d302c, #4D302C);
}

.b2cgmuy3t {
  stop-color: var(--svg-color--9574dd, #9574DD);
  stop-opacity: 0;
}

.b94-l-y5w {
  stop-color: var(--svg-color--3c2728, #3C2728);
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

.bo6sve4_m {
  stop-color: var(--svg-color--3f292a, #3F292A);
}

.boy1db52w {
  stop-color: var(--svg-color--21181e, #21181E);
}

.c7c54u04z {
  stop-color: var(--svg-color--635150, #635150);
  stop-opacity: 0;
}

.cbx5-fbbx {
  stop-color: var(--svg-color--675553, #675553);
}

.cc23txbjg {
  stop-color: var(--svg-color--190d13, #190D13);
  stop-opacity: 0;
}

.cibck0b0g {
  stop-color: var(--svg-color--ffb129, #FFB129);
}

.d3bth9bgz {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
}

.df2hh16wk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 13.984c.146.164.536.45 1.024.47c.617.023.949-.306 1.144-.47");
}

.dit5vub-g {
  stop-color: var(--svg-color--311617, #311617);
  stop-opacity: 0;
}

.dsheu9oxu {
  stop-color: var(--svg-color--0c0b0b, #0C0B0B);
}

.du3_mqevj {
  stop-color: var(--svg-color--2c2c2d, #2C2C2D);
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

.e45b6kbci {
  stop-color: var(--svg-color--2d151b, #2D151B);
}

.e7x0i9zao {
  stop-color: var(--svg-color--190a1e, #190A1E);
  stop-opacity: 0;
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

.fya8so0hw {
  fill: var(--svg-color--290118, #290118);
  d: path("M14.357 17.333c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.457-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135");
}

.gh1umgbbt {
  stop-color: var(--svg-color--4c3938, #4C3938);
}

.ghvr_e1bi {
  stop-color: var(--svg-color--f39423, #F39423);
}

.grwnnnb5d {
  stop-color: var(--svg-color--301c27, #301C27);
}

.gti-w2qfb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.508c.258-.207.883-.578 1.95-.43");
}

.h_keknbwg {
  fill: var(--svg-color--482c2f, #482C2F);
  d: path("M13.75 20a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.h65c54lsi {
  stop-color: var(--svg-color--3f222e, #3F222E);
  stop-opacity: 0;
}

.hpzn95b1x {
  stop-color: var(--svg-color--2c2c2d, #2C2C2D);
  stop-opacity: 0;
}

.i4ojxgbvw {
  cx: 21.396px;
  cy: 14.365px;
  r: 1.293px;
}

.ievfp3btw {
  d: path("M21.21 8.363L19.187 9.85c-.244.18-.47.42-.676.196c-.22-.238-.007-.337.229-.56a52 52 0 0 1 1.99-1.785c.875-.734.85-2.109.828-2.57V2.554h1.704v10.713a.579.579 0 0 1-1.158 0V9.03c0-.402-.571-.906-.896-.667");
}

.inwx22uty {
  stop-color: var(--svg-color--433e40, #433E40);
}

.j2uqjm0oz {
  stop-color: var(--svg-color--58494a, #58494A);
}

.j37u4rb-f {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.333c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.457-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135Z");
}

.j8s-5d-gn {
  stroke: var(--svg-color--0c0808, #0C0808);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.072 12.508c.258-.207.883-.578 1.95-.43");
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

.j9ig536pv {
  stop-color: var(--svg-color--47232a, #47232A);
}

.jywaqhbli {
  stop-color: var(--svg-color--342f31, #342F31);
}

.k4lo-hb9q {
  stop-color: var(--svg-color--7c4fa2, #7C4FA2);
  stop-opacity: 0;
}

.kpblyoq0s {
  stroke: var(--svg-color--0c0808, #0C0808);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.928 12.508c-.258-.207-.883-.578-1.95-.43");
}

.l_flc0gwk {
  cx: 13.715px;
  cy: 13.326px;
  r: 1.33px;
}

.lefbu6b0u {
  stop-color: var(--svg-color--3c2221, #3C2221);
}

.lplgdxbdh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 13.984c.146.164.536.45 1.024.47c.617.023.949-.306 1.144-.47");
}

.m__z0mykh {
  cx: 13.524px;
  cy: 13.242px;
  r: 1.415px;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqv57bcbp {
  stop-color: var(--svg-color--6a5856, #6A5856);
  stop-opacity: 0;
}

.my0c8s4fp {
  stop-color: var(--svg-color--5b4645, #5B4645);
}

.n_nhnibbq {
  stop-color: var(--svg-color--59403f, #59403F);
  stop-opacity: 0;
}

.n6_y6k2_m {
  stop-color: var(--svg-color--ffca3e, #FFCA3E);
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

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o8kgn-caf {
  stop-color: var(--svg-color--444243, #444243);
  stop-opacity: 0;
}

.omc-6wb_b {
  stop-color: var(--svg-color--2e2e2e, #2E2E2E);
}

.oof-goujs {
  stop-color: var(--svg-color--936dd4, #936DD4);
}

.p-tc_9j4a {
  stop-color: var(--svg-color--523c3c, #523C3C);
}

.p3lw01bbh {
  stop-color: var(--svg-color--d97513, #D97513);
}

.p7wwt2b_k {
  stop-color: var(--svg-color--685654, #685654);
}

.pd7y1ouls {
  stop-color: var(--svg-color--190a1e, #190A1E);
}

.phs3tubib {
  stop-color: var(--svg-color--332122, #332122);
}

.pj2xknbvf {
  stop-color: var(--svg-color--311617, #311617);
}

.q_3bb9b3h {
  stop-color: var(--svg-color--3f222e, #3F222E);
}

.q_3fqdbeg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 13.984c.146.164.536.45 1.023.47c.617.023.95-.306 1.145-.47");
}

.q_571zmbj {
  fill: var(--svg-color--563c39, #563C39);
  d: path("M8.688 2.271h3.426v3.484c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.88.393v3.327a1.2 1.2 0 1 1-2.398 0z");
}

.q-trqsbdf {
  stop-color: var(--svg-color--433e40, #433E40);
  stop-opacity: 0;
}

.q6gx3quyt {
  d: path("M13.75 20a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.q7vyx3bsm {
  d: path("M13.209 8.49c-.782 1.248-2.158 2.114-2.7 2.314V6.655c.265 0 1.576-.141 2.168-.514c.694-.437 1.337-1.637 3.352-1.637c1.071 0 1.808.377 2.923 1.337c.882.652 2.182.697 2.743.652v4.534c-.517-.373-1.428-.41-1.846-.428h-3.375c-1.744 0-2.934-1.39-3.265-2.11");
}

.qf8pq8giw {
  stop-color: var(--svg-color--58494a, #58494A);
  stop-opacity: 0;
}

.qnvlgqbda {
  cx: 10.604px;
  cy: 14.365px;
  r: 1.293px;
  fill: var(--svg-color--261417, #261417);
}

.qtf9d8byq {
  stop-color: var(--svg-color--47232a, #47232A);
  stop-opacity: 0;
}

.r-5ctobwv {
  stop-color: var(--svg-color--9574dd, #9574DD);
}

.r7917jlmh {
  d: path("m9.558 9.243l1.311.78v3.433a.655.655 0 1 1-1.31 0z");
}

.rc0rszb3u {
  stop-color: var(--svg-color--6a3874, #6A3874);
}

.rh917jb8x {
  stop-color: var(--svg-color--180f21, #180F21);
}

.rjclg2bzq {
  stop-color: var(--svg-color--402452, #402452);
}

.rot1mr63h {
  d: path("M23.846 11.876c-.56-.982-.53-1.722-.639-2.036l-6.664 2.824v8.915h3.72c2.443 0 3.523-1.02 4.003-2.22s.28-2.132.06-2.795a1.54 1.54 0 0 1 .03-.998c.452-1.252.176-2.49-.51-3.69");
}

.rulb4ox_k {
  stop-color: var(--svg-color--242425, #242425);
}

.s4dmvvdkq {
  stop-color: var(--svg-color--58403c, #58403C);
  stop-opacity: 0;
}

.s4ff5rbng {
  stop-color: var(--svg-color--6a5856, #6A5856);
}

.spvl3-bel {
  stop-color: var(--svg-color--595757, #595757);
}

.spxm__abu {
  stop-color: var(--svg-color--371c2e, #371C2E);
}

.tg833uend {
  fill: var(--svg-color--1a0a0d, #1A0A0D);
  d: path("m9.271 2.405l1.516 5.892l1.938-.904c0 .34.199-.381.656 0a78 78 0 0 1 1.727 1.632c.476.46.463 1.207-.027 1.653c-.453.413-1.088.349-1.552-.053l-.98-.713a.54.54 0 0 0-.747.042a.5.5 0 0 0-.132.337V13.5c0 .639-.537 1.156-1.2 1.156s-1.199-.518-1.199-1.156z");
}

.tjm0n2v5h {
  stop-color: var(--svg-color--3e393a, #3E393A);
  stop-opacity: 0;
}

.u0kksrmqh {
  stop-color: var(--svg-color--191717, #191717);
}

.uchbj6dck {
  stop-color: var(--svg-color--190d13, #190D13);
}

.us-_kefmy {
  stop-color: var(--svg-color--444243, #444243);
}

.vf_3ecbae {
  d: path("M10.263 5.37V2.472h1.468v3.534a1 1 0 0 0 .28.694l2.263 2.349a.46.46 0 0 1-.636.663l-2.364-2.094a3 3 0 0 1-1.011-2.246");
}

.vfm0_vraw {
  stop-color: var(--svg-color--675553, #675553);
  stop-opacity: 0;
}

.vk3h5kjsq {
  stop-color: var(--svg-color--140a18, #140A18);
}

.vlw8-dbis {
  stop-color: var(--svg-color--5a5858, #5A5858);
}

.vod-dschj {
  d: path("M8.688 2.271h3.426v3.484c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.88.393v3.327a1.2 1.2 0 1 1-2.398 0z");
}

.vvxgj6bpi {
  d: path("M5.65 29.729h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.665");
}

.wvp0mabjb {
  d: path("m9.271 2.405l1.516 5.892l1.938-.904c0 .34.199-.381.656 0a78 78 0 0 1 1.727 1.632c.476.46.463 1.207-.027 1.653c-.453.413-1.088.349-1.552-.053l-.98-.713a.54.54 0 0 0-.747.042a.5.5 0 0 0-.132.337V13.5c0 .639-.537 1.156-1.2 1.156s-1.199-.518-1.199-1.156z");
}

.x_31h1mma {
  stop-color: var(--svg-color--635150, #635150);
}

.xgr1jvbtp {
  fill: var(--svg-color--211314, #211314);
  d: path("M22.646 8.25H19.22l-.684-1.812c0 .352.457.528 0 .923a79 79 0 0 0-1.727 1.691a1.195 1.195 0 0 0 .027 1.715c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.xxerewdbl {
  stop-color: var(--svg-color--623e81, #623E81);
  stop-opacity: 0;
}

.y-z81-bua {
  stop-color: var(--svg-color--725698, #725698);
}

.y581ksbre {
  stop-color: var(--svg-color--462b30, #462B30);
}

.ydm9ddced {
  stop-color: var(--svg-color--59403f, #59403F);
}

.yo4_wwpln {
  stop-color: var(--svg-color--494446, #494446);
}

.ywdwogbzt {
  stop-color: var(--svg-color--181419, #181419);
}

.z_1jymb2l {
  d: path("M13.135 6.281c-.313.207-.83.466-.95.438c1.038 3.687 4.893 3.74 6.59 3.437L20.4 8.594V6.719c-1.164-.57-3.218-1.828-4.671-1.742s-2.204 1.046-2.594 1.304");
}

.zjwmqlbwo {
  stop-color: var(--svg-color--3c212e, #3C212E);
  stop-opacity: 0;
}

</style>
