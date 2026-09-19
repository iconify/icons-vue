<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLQ70zd)"><path fill="url(#iBLebJe)" class="vvxgj6bpi"/><path fill="url(#i6ataMe)" class="vvxgj6bpi"/></g><path fill="url(#iYqpaEd)" class="vvxgj6bpi"/><path fill="url(#ixAyHpb)" class="vvxgj6bpi"/><g filter="url(#igitkNc)"><path fill="url(#iuQw5uc)" class="ig-n-yctu"/><path fill="url(#i0tnQAd)" class="ig-n-yctu"/></g><g filter="url(#iI8hGxe)"><path fill="url(#iXr7Rnx)" class="d3j_vxdji"/><path fill="url(#iNTJx8N)" class="d3j_vxdji"/></g><circle fill="url(#iIieboc)" class="nserplb1x"/><g filter="url(#i2jiHwd)" class="mc2zb0bvp"><circle class="ave42jpej"/></g><circle fill="url(#ixzpRCc)" class="tu_6z7zsi"/><circle fill="url(#ihWqA8b)" class="tu_6z7zsi"/><g filter="url(#i6SU69b)"><circle fill="url(#iBDjCbd)" class="i4ojxgbvw"/></g><g filter="url(#iNokoNe)"><circle fill="url(#i3y1Erb)" class="m__z0mykh"/></g><path class="k8fo80b1l"/><path fill="url(#iXStOEd)" class="q6gx3quyt"/><path fill="url(#iFoRg4U)" class="q6gx3quyt"/><g filter="url(#iTdl7gJ)"><rect fill="url(#iwTYy3c)" class="j8z-42s7e"/></g><rect fill="url(#i4xNvad)" class="j8z-42s7e"/><g filter="url(#ipnnGUh)"><path fill="url(#iNNWYAe)" class="wvp0mabjb"/></g><g filter="url(#iVEVnzd)"><path fill="url(#iyEInfe)" class="xnnyhy2ap"/></g><g filter="url(#ic3kEqv)"><path fill="url(#iZYhWCb)" class="q7vyx3bsm"/><path fill="url(#ip9T1sd)" class="q7vyx3bsm"/><path fill="url(#iGGwJad)" class="q7vyx3bsm"/><path fill="url(#iuDa5Ob)" class="q7vyx3bsm"/></g><g filter="url(#iUzrkib)"><path fill="url(#iKjZOtc)" class="z_1jymb2l"/><path fill="url(#iB6TAhb)" class="z_1jymb2l"/><path fill="url(#ix7vDjc)" class="z_1jymb2l"/></g><g filter="url(#iCGaOpd)"><circle fill="url(#indJj4K)" class="l_flc0gwk"/></g><g filter="url(#irtS3yb)"><path class="llgl-_cwc"/></g><g filter="url(#iefzzGc)"><path stroke="url(#ia2x8xe)" class="gti-w2qfb"/></g><g filter="url(#iiYjDis)"><path class="dzkex-d4f"/></g><g filter="url(#ime5Nyc)"><path stroke="url(#iGCgdmC)" class="e2arxx8zo"/></g><path stroke="url(#i2LxIPO)" class="df2hh16wk"/><g filter="url(#ivTJGFd)"><path stroke="url(#i35Wavd)" class="lplgdxbdh"/></g><path stroke="url(#iTTEWeL)" class="q_3fqdbeg"/><g filter="url(#i3WzTwb)"><path stroke="url(#ivelIBC)" class="f1zc5ekne"/></g><g filter="url(#iSX87Jb)"><path class="h3_2_jkqk"/></g><path class="wjkb-kbpv"/><path fill="url(#iPkXrqb)" class="bnm8uzbww"/><path fill="url(#i3zJXOb)" class="bnm8uzbww"/><path fill="url(#isqoPkc)" class="bnm8uzbww"/><g filter="url(#ijgioje)"><path stroke="url(#it6NuMb)" class="sr4z9jbkj"/></g><path class="y_i3q3xjv"/><g filter="url(#iYxh6jd)"><path fill="url(#iswkPyc)" class="j9i9zyb7u"/></g><g filter="url(#iJa42Nd)"><path class="k35a_9nht"/><path fill="url(#iVCXwKc)" class="vod-dschj"/></g><g filter="url(#izcwIid)"><path class="n0rp3ccbd"/></g><g filter="url(#iOpRosM)"><path fill="url(#ilIjwPx)" class="ievfp3btw"/></g><g filter="url(#it2MAdb)"><path fill="url(#iShsSgb)" class="xz3qu32ga"/></g><g filter="url(#igJQv4b)"><path fill="url(#ioaiNHc)" class="wwb0izbyi"/><path fill="url(#i9355rn)" class="wwb0izbyi"/></g><defs><radialGradient id="iBLebJe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.313)" gradientUnits="userSpaceOnUse"><stop class="oof-goujs"/><stop offset=".832" class="y-z81-bua"/></radialGradient><radialGradient id="i6ataMe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.16617 -7.1847 8.98984 -5.2129 23.982 28.248)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="r-5ctobwv"/><stop offset="1" class="b2cgmuy3t"/></radialGradient><radialGradient id="iYqpaEd" cx="0" cy="0" r="1" gradientTransform="rotate(155.64 5.706 11.329)scale(10.8979 4.51152)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="rc0rszb3u"/><stop offset="1" class="k4lo-hb9q"/></radialGradient><radialGradient id="ixAyHpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.5924 15.2389 0 16 30.313)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="xxerewdbl"/><stop offset=".977" class="rjclg2bzq"/></radialGradient><radialGradient id="iuQw5uc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.56244 7.87504 -7.63171 -5.39056 25.318 13.875)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uc0tkdwba"/><stop offset="1" class="jkq8hibuy"/></radialGradient><radialGradient id="i0tnQAd" cx="0" cy="0" r="1" gradientTransform="rotate(147.139 10.128 11.737)scale(2.75089 2.7814)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="rq4errj1n"/><stop offset="1" class="jbk3ro_7f"/></radialGradient><radialGradient id="iXr7Rnx" cx="0" cy="0" r="1" gradientTransform="rotate(152.281 3.899 10.46)scale(4.87131 9.06872)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="djz2u_f1j"/><stop offset="1" class="u3571bcrc"/></radialGradient><radialGradient id="iNTJx8N" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82006 6.3586 -4.4708 -1.2797 9.243 10.892)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="xuj_d5bpu"/><stop offset="1" class="pbp-bsbxj"/></radialGradient><radialGradient id="iIieboc" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.223 17.133)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="eusqnibct"/><stop offset="1" class="hkkpz-bpt"/></radialGradient><radialGradient id="ixzpRCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7615 .75741 -.7977 -.802 23.196 14.244)" gradientUnits="userSpaceOnUse"><stop class="kew95vbbt"/><stop offset="1" class="qmajx1z3l"/></radialGradient><radialGradient id="ihWqA8b" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.493 20.988)scale(2.34213)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="bitta5b4f"/><stop offset="1" class="qfofjhlvk"/></radialGradient><radialGradient id="iBDjCbd" cx="0" cy="0" r="1" gradientTransform="matrix(.69531 0 0 .82031 21.666 14.584)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="eevz_mbba"/><stop offset="1" class="xtumd7buv"/></radialGradient><radialGradient id="i3y1Erb" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 13.942)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cibck0b0g"/><stop offset=".902" class="ghvr_e1bi"/></radialGradient><radialGradient id="iXStOEd" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.189 14.596)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="ecblxkmju"/><stop offset="1" class="l7ooslboc"/></radialGradient><radialGradient id="iFoRg4U" cx="0" cy="0" r="1" gradientTransform="matrix(1.4742 2.59113 -8.42594 4.79384 14.039 20.44)" gradientUnits="userSpaceOnUse"><stop class="kt536ebly"/><stop offset="1" class="ks_06bc0r"/></radialGradient><radialGradient id="iwTYy3c" cx="0" cy="0" r="1" gradientTransform="rotate(174.247 9.378 7.946)scale(6.06562 7.0411)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="k12aqibrq"/><stop offset="1" class="dfqtmwbvu"/></radialGradient><radialGradient id="i4xNvad" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.0892 -11.3554 0 16 10.975)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="jr1vabh8w"/><stop offset="1" class="tn944ra6k"/></radialGradient><radialGradient id="iNNWYAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.03943 7.79525 -3.98358 .53118 11.325 6.861)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="ac4xzzbrr"/><stop offset="1" class="cpmy9wdkn"/></radialGradient><radialGradient id="iyEInfe" cx="0" cy="0" r="1" gradientTransform="rotate(107.245 7.044 12.702)scale(3.64237 3.54945)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="top4m_b9w"/><stop offset="1" class="gd06x8-mu"/></radialGradient><radialGradient id="iZYhWCb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37502 5.34375 -6.41397 -1.6504 17.88 4.74)" gradientUnits="userSpaceOnUse"><stop class="l44rzebdx"/><stop offset=".722" class="psovanbtx"/></radialGradient><radialGradient id="ip9T1sd" cx="0" cy="0" r="1" gradientTransform="matrix(2.06252 -1.68749 2.8938 3.53691 10.819 10.187)" gradientUnits="userSpaceOnUse"><stop class="peu1-t5lu"/><stop offset="1" class="z-8krbb_n"/></radialGradient><radialGradient id="iGGwJad" cx="0" cy="0" r="1" gradientTransform="rotate(-144.811 12.391 1.866)scale(2.98253 5.11462)" gradientUnits="userSpaceOnUse"><stop class="h3m92abdo"/><stop offset="1" class="mf2rwenym"/></radialGradient><radialGradient id="iuDa5Ob" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -1.96875 .58437 .85337 11.224 6.752)" gradientUnits="userSpaceOnUse"><stop class="z0omcdrve"/><stop offset="1" class="rn_0m_9es"/></radialGradient><radialGradient id="iKjZOtc" cx="0" cy="0" r="1" gradientTransform="rotate(-58.443 17.078 -10.404)scale(4.65751 13.5396)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="i8k1wbclk"/><stop offset="1" class="uabjmjbgv"/></radialGradient><radialGradient id="iB6TAhb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.91443 -2.2661 1.04442 -2.265 19.427 8.515)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="vskr0tb6x"/><stop offset="1" class="r5yplmm8z"/></radialGradient><radialGradient id="ix7vDjc" cx="0" cy="0" r="1" gradientTransform="rotate(-149.958 11.068 .496)scale(3.49028 1.92611)" gradientUnits="userSpaceOnUse"><stop class="lnnm4cfzy"/><stop offset="1" class="q2k3-h57j"/></radialGradient><radialGradient id="indJj4K" cx="0" cy="0" r="1" gradientTransform="rotate(-62.753 18.25 -4.13)scale(1.90544 2.10594)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="n_pf1oy7u"/><stop offset=".902" class="e0nbxjblq"/></radialGradient><radialGradient id="i2LxIPO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.578)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="i6h5s3y2e"/><stop offset="1" class="r-0_iwkut"/></radialGradient><radialGradient id="iTTEWeL" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.578)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="i6h5s3y2e"/><stop offset="1" class="r-0_iwkut"/></radialGradient><radialGradient id="i3zJXOb" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 16.758)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="csb315wui"/><stop offset="1" class="c2okx_q2g"/></radialGradient><radialGradient id="isqoPkc" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.542 15.959)" gradientUnits="userSpaceOnUse"><stop class="yp6fmsbhu"/><stop offset="1" class="ea054pq6c"/></radialGradient><radialGradient id="it6NuMb" cx="0" cy="0" r="1" gradientTransform="rotate(-62.526 22.567 -3.115)scale(.44028 1.97794)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="gl9j5ld5z"/><stop offset="1" class="b3ziilbku"/></radialGradient><radialGradient id="iVCXwKc" cx="0" cy="0" r="1" gradientTransform="rotate(-124.468 8.78 2.243)scale(3.17497 1.5867)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="xk4wwk53d"/><stop offset="1" class="b0gopucow"/></radialGradient><radialGradient id="ilIjwPx" cx="0" cy="0" r="1" gradientTransform="matrix(5.87065 -6.2812 5.44456 5.0887 18.354 9.816)" gradientUnits="userSpaceOnUse"><stop class="zpoasobui"/><stop offset="1" class="ss3psybpi"/></radialGradient><radialGradient id="ioaiNHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 11.1 6.347)" gradientUnits="userSpaceOnUse"><stop class="xms_-vb8m"/><stop offset="1" class="wj0_vcbzm"/><stop offset="1" class="dpgj0fl2i"/></radialGradient><radialGradient id="i9355rn" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.402 9.827)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="cbcg1h21f"/><stop offset="1" class="ecsgmuy6m"/></radialGradient><filter id="iLQ70zd" width="21.451" height="8.965" x="5.649" y="20.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.27451 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24266"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.376471 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24266" result="effect2_innerShadow_3987_24266"/></filter><filter id="igitkNc" width="8.434" height="11.989" x="16.543" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.533333 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24266"/></filter><filter id="iI8hGxe" width="8.784" height="12.039" x="7.173" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24266"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.454902 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24266" result="effect2_innerShadow_3987_24266"/></filter><filter id="i2jiHwd" width="2.986" height="2.986" x="9.111" y="12.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".1"/></filter><filter id="i6SU69b" width="2.986" height="2.986" x="19.904" y="12.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".1"/></filter><filter id="iNokoNe" width="3.829" height="3.829" x="11.609" y="11.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".25"/></filter><filter id="iTdl7gJ" width="12.021" height="15.258" x="10.24" y="5.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24266"/></filter><filter id="ipnnGUh" width="8.186" height="14.251" x="8.271" y="1.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".5"/></filter><filter id="iVEVnzd" width="8.186" height="10.454" x="15.46" y="5.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".5"/></filter><filter id="ic3kEqv" width="11.186" height="6.923" x="10.508" y="4.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.698039 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24266"/></filter><filter id="iUzrkib" width="8.715" height="5.797" x="11.935" y="4.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".125"/></filter><filter id="iCGaOpd" width="3.66" height="3.66" x="11.885" y="11.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".25"/></filter><filter id="irtS3yb" width="2.699" height="1.214" x="11.797" y="11.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24266"/></filter><filter id="iefzzGc" width="2.399" height=".914" x="11.847" y="11.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".075"/></filter><filter id="iiYjDis" width="2.699" height="1.214" x="17.703" y="11.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24266"/></filter><filter id="ime5Nyc" width="2.399" height=".914" x="17.753" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".075"/></filter><filter id="ivTJGFd" width="2.618" height=".92" x="12.269" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".075"/></filter><filter id="i3WzTwb" width="2.618" height=".92" x="17.16" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".075"/></filter><filter id="iSX87Jb" width="3.122" height="4.211" x="14.162" y="13.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".25"/></filter><filter id="ijgioje" width="4.199" height="1.729" x="13.906" y="17.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".05"/></filter><filter id="iYxh6jd" width="2.811" height="6.368" x="8.719" y="8.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".375"/></filter><filter id="iJa42Nd" width="6.686" height="12.645" x="8.688" y="2.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.592157 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24266"/></filter><filter id="izcwIid" width="6.436" height="12.695" x="17.329" y="2.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.447059 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24266"/></filter><filter id="iOpRosM" width="5.843" height="12.292" x="17.92" y="2.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".25"/></filter><filter id="it2MAdb" width="2.811" height="6.368" x="8.808" y="8.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".375"/></filter><filter id="igJQv4b" width="5.14" height="8.355" x="9.763" y="1.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24266" stdDeviation=".25"/></filter><linearGradient id="ia2x8xe" x1="11.796" x2="14.021" y1="12.967" y2="12.044" gradientUnits="userSpaceOnUse"><stop class="tanu-rbxd"/><stop offset="1" class="sykku8w3p"/></linearGradient><linearGradient id="iGCgdmC" x1="20.204" x2="17.979" y1="12.912" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="tanu-rbxd"/><stop offset="1" class="sykku8w3p"/></linearGradient><linearGradient id="i35Wavd" x1="14.936" x2="12.494" y1="13.984" y2="13.984" gradientUnits="userSpaceOnUse"><stop offset=".045" class="vmf5ti4hh"/><stop offset=".32" class="niae35b7q"/><stop offset=".794" class="lphhh6b5o"/><stop offset="1" class="ojzo1eq0m"/></linearGradient><linearGradient id="ivelIBC" x1="19.826" x2="17.385" y1="13.984" y2="13.984" gradientUnits="userSpaceOnUse"><stop offset=".045" class="vmf5ti4hh"/><stop offset=".32" class="niae35b7q"/><stop offset=".794" class="lphhh6b5o"/><stop offset="1" class="ojzo1eq0m"/></linearGradient><linearGradient id="iPkXrqb" x1="16.886" x2="15.849" y1="15.49" y2="15.54" gradientUnits="userSpaceOnUse"><stop offset=".106" class="y_s895zcx"/><stop offset="1" class="gd4v4obak"/></linearGradient><linearGradient id="iswkPyc" x1="10.124" x2="10.124" y1="13.097" y2="8.266" gradientUnits="userSpaceOnUse"><stop class="n6_y6k2_m"/><stop offset="1" class="bd1m8wbbp"/></linearGradient><linearGradient id="iShsSgb" x1="10.214" x2="10.214" y1="13.329" y2="8.498" gradientUnits="userSpaceOnUse"><stop class="ow5lwmmzq"/><stop offset="1" class="t4_yy204v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-getting-massage-medium-light" /></template>
<style>
.ac4xzzbrr {
  stop-color: var(--svg-color--97523e, #97523E);
}

.ave42jpej {
  cx: 10.604px;
  cy: 14.365px;
  r: 1.293px;
  fill: var(--svg-color--ba765f, #BA765F);
}

.b0gopucow {
  stop-color: var(--svg-color--d39c86, #D39C86);
  stop-opacity: 0;
}

.b2cgmuy3t {
  stop-color: var(--svg-color--9574dd, #9574DD);
  stop-opacity: 0;
}

.b3ziilbku {
  stop-color: var(--svg-color--d49d8f, #D49D8F);
  stop-opacity: 0;
}

.bd1m8wbbp {
  stop-color: var(--svg-color--ffcb3b, #FFCB3B);
  stop-opacity: 0;
}

.bitta5b4f {
  stop-color: var(--svg-color--da9779, #DA9779);
  stop-opacity: 0;
}

.bnm8uzbww {
  d: path("M16 13.625a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.262");
}

.c2okx_q2g {
  stop-color: var(--svg-color--d39186, #D39186);
  stop-opacity: 0;
}

.cbcg1h21f {
  stop-color: var(--svg-color--edbfa5, #EDBFA5);
}

.cibck0b0g {
  stop-color: var(--svg-color--ffb129, #FFB129);
}

.cpmy9wdkn {
  stop-color: var(--svg-color--ab6a5f, #AB6A5F);
}

.csb315wui {
  stop-color: var(--svg-color--d39186, #D39186);
}

.d3j_vxdji {
  d: path("M8.154 11.876c.56-.982.53-1.722.638-2.036l6.665 2.824v8.915h-3.72c-2.443 0-3.523-1.02-4.003-2.22s-.28-2.133-.06-2.795a1.54 1.54 0 0 0-.03-.998c-.452-1.252-.176-2.49.51-3.69");
}

.df2hh16wk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 13.984c.146.164.536.45 1.024.47c.617.023.949-.306 1.144-.47");
}

.dfqtmwbvu {
  stop-color: var(--svg-color--c9907d, #C9907D);
}

.djz2u_f1j {
  stop-color: var(--svg-color--d29b7c, #D29B7C);
}

.dpgj0fl2i {
  stop-color: var(--svg-color--fbc8a8, #FBC8A8);
  stop-opacity: 0;
}

.dzkex-d4f {
  stroke: var(--svg-color--945c2e, #945C2E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.928 12.508c-.258-.207-.883-.578-1.95-.43");
}

.e0nbxjblq {
  stop-color: var(--svg-color--c6867c, #C6867C);
}

.e2arxx8zo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.928 12.453c-.258-.207-.883-.578-1.95-.43");
}

.ea054pq6c {
  stop-color: var(--svg-color--f2bea5, #F2BEA5);
  stop-opacity: 0;
}

.ecblxkmju {
  stop-color: var(--svg-color--f1b99b, #F1B99B);
}

.ecsgmuy6m {
  stop-color: var(--svg-color--edbfa5, #EDBFA5);
  stop-opacity: 0;
}

.eevz_mbba {
  stop-color: var(--svg-color--e2a786, #E2A786);
}

.eusqnibct {
  stop-color: var(--svg-color--c4836f, #C4836F);
}

.f1zc5ekne {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 13.984c.146.164.536.45 1.023.47c.617.023.95-.306 1.145-.47");
}

.ft5dv1b6b {
  fill: none;
}

.gd06x8-mu {
  stop-color: var(--svg-color--c5836c, #C5836C);
}

.gd4v4obak {
  stop-color: var(--svg-color--f3c0a4, #F3C0A4);
  stop-opacity: 0;
}

.ghvr_e1bi {
  stop-color: var(--svg-color--f39423, #F39423);
}

.gl9j5ld5z {
  stop-color: var(--svg-color--d49d8f, #D49D8F);
}

.gti-w2qfb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.508c.258-.207.883-.578 1.95-.43");
}

.h3_2_jkqk {
  fill: var(--svg-color--cb8a7c, #CB8A7C);
  d: path("M15.872 13.71c-.163 0-.248.094-.297.255l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.161-.045-.254-.209-.254");
}

.h3m92abdo {
  stop-color: var(--svg-color--d4a685, #D4A685);
}

.hkkpz-bpt {
  stop-color: var(--svg-color--c37a6b, #C37A6B);
}

.i4ojxgbvw {
  cx: 21.396px;
  cy: 14.365px;
  r: 1.293px;
}

.i6h5s3y2e {
  stop-color: var(--svg-color--7e4630, #7E4630);
}

.i8k1wbclk {
  stop-color: var(--svg-color--e5d39c, #E5D39C);
  stop-opacity: 0;
}

.ievfp3btw {
  d: path("M21.21 8.363L19.187 9.85c-.244.18-.47.42-.676.196c-.22-.238-.007-.337.229-.56a52 52 0 0 1 1.99-1.785c.875-.734.85-2.109.828-2.57V2.554h1.704v10.713a.579.579 0 0 1-1.158 0V9.03c0-.402-.571-.906-.896-.667");
}

.ig-n-yctu {
  d: path("M23.846 11.876c-.56-.982-.53-1.722-.639-2.036l-6.664 2.824v8.915h3.72c2.443 0 3.523-1.02 4.003-2.22s.28-2.133.06-2.795a1.54 1.54 0 0 1 .03-.998c.452-1.252.176-2.49-.51-3.69");
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

.jbk3ro_7f {
  stop-color: var(--svg-color--ffebb7, #FFEBB7);
  stop-opacity: 0;
}

.jkq8hibuy {
  stop-color: var(--svg-color--f2bc9f, #F2BC9F);
}

.jr1vabh8w {
  stop-color: var(--svg-color--c28682, #C28682);
  stop-opacity: 0;
}

.k12aqibrq {
  stop-color: var(--svg-color--f4bc97, #F4BC97);
}

.k35a_9nht {
  fill: var(--svg-color--e1aa8e, #E1AA8E);
  d: path("M8.688 2.271h3.426v3.484c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.88.393v3.327a1.2 1.2 0 1 1-2.398 0z");
}

.k4lo-hb9q {
  stop-color: var(--svg-color--7c4fa2, #7C4FA2);
  stop-opacity: 0;
}

.k8fo80b1l {
  fill: var(--svg-color--d89985, #D89985);
  d: path("M13.75 20a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.kew95vbbt {
  stop-color: var(--svg-color--ecb99c, #ECB99C);
}

.ks_06bc0r {
  stop-color: var(--svg-color--b4756a, #B4756A);
  stop-opacity: 0;
}

.kt536ebly {
  stop-color: var(--svg-color--b4756a, #B4756A);
}

.l_flc0gwk {
  cx: 13.715px;
  cy: 13.326px;
  r: 1.33px;
}

.l44rzebdx {
  stop-color: var(--svg-color--fbeaae, #FBEAAE);
}

.l7ooslboc {
  stop-color: var(--svg-color--f1b99b, #F1B99B);
  stop-opacity: 0;
}

.llgl-_cwc {
  stroke: var(--svg-color--945c2e, #945C2E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.072 12.508c.258-.207.883-.578 1.95-.43");
}

.lnnm4cfzy {
  stop-color: var(--svg-color--ceb887, #CEB887);
}

.lphhh6b5o {
  stop-color: var(--svg-color--925d35, #925D35);
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

.mf2rwenym {
  stop-color: var(--svg-color--d4a685, #D4A685);
  stop-opacity: 0;
}

.n_pf1oy7u {
  stop-color: var(--svg-color--d09580, #D09580);
}

.n0rp3ccbd {
  fill: var(--svg-color--d2997d, #D2997D);
  d: path("M23.515 2.271h-3.426v3.484c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.714c.454.429 1.09.362 1.555-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.n6_y6k2_m {
  stop-color: var(--svg-color--ffca3e, #FFCA3E);
}

.niae35b7q {
  stop-color: var(--svg-color--98623a, #98623A);
}

.nserplb1x {
  cx: 10.604px;
  cy: 14.365px;
  r: 1.979px;
}

.ojzo1eq0m {
  stop-color: var(--svg-color--a06b42, #A06B42);
}

.oof-goujs {
  stop-color: var(--svg-color--936dd4, #936DD4);
}

.ow5lwmmzq {
  stop-color: var(--svg-color--e1ad98, #E1AD98);
}

.pbp-bsbxj {
  stop-color: var(--svg-color--f6c998, #F6C998);
  stop-opacity: 0;
}

.peu1-t5lu {
  stop-color: var(--svg-color--cb9983, #CB9983);
}

.psovanbtx {
  stop-color: var(--svg-color--ffe3a6, #FFE3A6);
}

.q_3fqdbeg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 13.984c.146.164.536.45 1.023.47c.617.023.95-.306 1.145-.47");
}

.q2k3-h57j {
  stop-color: var(--svg-color--ceb887, #CEB887);
  stop-opacity: 0;
}

.q6gx3quyt {
  d: path("M13.75 20a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.q7vyx3bsm {
  d: path("M13.209 8.49c-.782 1.248-2.158 2.114-2.7 2.314V6.655c.265 0 1.576-.141 2.168-.514c.694-.437 1.337-1.637 3.352-1.637c1.071 0 1.808.377 2.923 1.337c.882.652 2.182.697 2.743.652v4.534c-.517-.373-1.428-.41-1.846-.428h-3.375c-1.744 0-2.934-1.39-3.265-2.11");
}

.qfofjhlvk {
  stop-color: var(--svg-color--da9779, #DA9779);
}

.qmajx1z3l {
  stop-color: var(--svg-color--de9f87, #DE9F87);
}

.r-0_iwkut {
  stop-color: var(--svg-color--834f26, #834F26);
}

.r-5ctobwv {
  stop-color: var(--svg-color--9574dd, #9574DD);
}

.r5yplmm8z {
  stop-color: var(--svg-color--ffefb7, #FFEFB7);
  stop-opacity: 0;
}

.rc0rszb3u {
  stop-color: var(--svg-color--6a3874, #6A3874);
}

.rjclg2bzq {
  stop-color: var(--svg-color--402452, #402452);
}

.rn_0m_9es {
  stop-color: var(--svg-color--dbc591, #DBC591);
  stop-opacity: 0;
}

.rq4errj1n {
  stop-color: var(--svg-color--ffebb7, #FFEBB7);
}

.sr4z9jbkj {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.333c.344.18.879.383 1.649.384c.77 0 1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135Z");
}

.ss3psybpi {
  stop-color: var(--svg-color--e7b79d, #E7B79D);
  stop-opacity: 0;
}

.sykku8w3p {
  stop-color: var(--svg-color--9f6a40, #9F6A40);
}

.t4_yy204v {
  stop-color: var(--svg-color--e1ad98, #E1AD98);
  stop-opacity: 0;
}

.tanu-rbxd {
  stop-color: var(--svg-color--9f6a40, #9F6A40);
  stop-opacity: 0;
}

.tn944ra6k {
  stop-color: var(--svg-color--ae6d76, #AE6D76);
}

.top4m_b9w {
  stop-color: var(--svg-color--a66046, #A66046);
}

.tu_6z7zsi {
  cx: 21.285px;
  cy: 14.432px;
  r: 1.979px;
}

.u3571bcrc {
  stop-color: var(--svg-color--eab990, #EAB990);
}

.uabjmjbgv {
  stop-color: var(--svg-color--e5d39c, #E5D39C);
}

.uc0tkdwba {
  stop-color: var(--svg-color--fff0b9, #FFF0B9);
}

.vmf5ti4hh {
  stop-color: var(--svg-color--9d683d, #9D683D);
}

.vod-dschj {
  d: path("M8.688 2.271h3.426v3.484c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.88.393v3.327a1.2 1.2 0 1 1-2.398 0z");
}

.vskr0tb6x {
  stop-color: var(--svg-color--ffefb7, #FFEFB7);
}

.vvxgj6bpi {
  d: path("M5.65 29.729h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.665");
}

.wj0_vcbzm {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
  stop-opacity: 0;
}

.wjkb-kbpv {
  fill: var(--svg-color--dfa789, #DFA789);
  d: path("M16 13.625a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.262");
}

.wvp0mabjb {
  d: path("m9.271 2.405l1.516 5.892l1.938-.904c0 .34.199-.381.656 0a78 78 0 0 1 1.727 1.632c.476.46.463 1.207-.027 1.653c-.453.413-1.088.349-1.552-.053l-.98-.713a.54.54 0 0 0-.747.042a.5.5 0 0 0-.132.337V13.5c0 .639-.537 1.156-1.2 1.156s-1.199-.518-1.199-1.156z");
}

.wwb0izbyi {
  d: path("M10.263 5.371v-2.9h1.468v3.535a1 1 0 0 0 .28.693l2.263 2.349a.46.46 0 0 1-.636.663l-2.364-2.094a3 3 0 0 1-1.011-2.246");
}

.xk4wwk53d {
  stop-color: var(--svg-color--be7d75, #BE7D75);
}

.xms_-vb8m {
  stop-color: var(--svg-color--fbc8a8, #FBC8A8);
}

.xnnyhy2ap {
  d: path("M22.646 8.25H19.22l-.684-1.812c0 .352.457.528 0 .923a79 79 0 0 0-1.727 1.691a1.195 1.195 0 0 0 .027 1.715c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.xtumd7buv {
  stop-color: var(--svg-color--e2a481, #E2A481);
}

.xuj_d5bpu {
  stop-color: var(--svg-color--f6c998, #F6C998);
}

.xxerewdbl {
  stop-color: var(--svg-color--623e81, #623E81);
  stop-opacity: 0;
}

.xz3qu32ga {
  d: path("m9.558 9.243l1.311.78v3.433a.656.656 0 0 1-1.31 0z");
}

.y_i3q3xjv {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M14.357 17.333c.344.18.879.383 1.649.384c.77 0 1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135");
}

.y_s895zcx {
  stop-color: var(--svg-color--f3c0a4, #F3C0A4);
}

.y-z81-bua {
  stop-color: var(--svg-color--725698, #725698);
}

.yp6fmsbhu {
  stop-color: var(--svg-color--f2bea5, #F2BEA5);
}

.z_1jymb2l {
  d: path("M13.135 6.281c-.313.207-.83.466-.95.438c1.038 3.687 4.893 3.74 6.59 3.437L20.4 8.594V6.719c-1.164-.57-3.218-1.828-4.671-1.742s-2.204 1.046-2.594 1.304");
}

.z-8krbb_n {
  stop-color: var(--svg-color--cb9983, #CB9983);
  stop-opacity: 0;
}

.z0omcdrve {
  stop-color: var(--svg-color--dbc591, #DBC591);
}

.zpoasobui {
  stop-color: var(--svg-color--e7b79d, #E7B79D);
}

</style>
