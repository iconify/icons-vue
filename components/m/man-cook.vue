<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="jz524ub8q"/><path fill="url(#ihCks5c)" class="vf29eozqp"/><path fill="url(#iirod2b)" class="nvjmqub3o"/><path fill="url(#ivPPUVb)" class="nvjmqub3o"/><path fill="url(#iFnTFTb)" class="i26zq3bfi"/><path fill="url(#iteh88c)" class="i26zq3bfi"/><path fill="url(#iHRwpvc)" class="i26zq3bfi"/><g filter="url(#iebEyBb)"><path fill="url(#ilACw6c)" class="b4arxk18h"/><path fill="url(#ikZukoc)" class="b4arxk18h"/></g><path fill="url(#iSKuFve)" class="b4arxk18h"/><path fill="url(#iCge4Hc)" class="b4arxk18h"/><g filter="url(#iRNkWjb)"><path fill="url(#iYQnNFc)" class="yi80usmmo"/></g><path fill="url(#iBsIO7c)" class="q2jbj30-x"/><path fill="url(#ir6reNe)" class="q2jbj30-x"/><g filter="url(#i2SAYVd)"><path class="e2iag5blt"/></g><g filter="url(#iMfcyhb)"><path class="e4tn_kbzn"/></g><g filter="url(#iNrMqge)"><path class="qqj6z8bjg"/></g><g filter="url(#iW1pdfs)"><path fill="url(#iOKQVYZ)" class="qpufwi9gx"/></g><g filter="url(#iP2nrje)"><path fill="url(#iyR4ftd)" class="kd6dp8bun"/></g><g filter="url(#iJreLle)"><path fill="url(#iRtxbvD)" class="bb31kfb8z"/></g><g filter="url(#iLmhqSA)"><path fill="url(#ii0Ps7d)" class="ooqp6liqz"/></g><path fill="url(#iSdSqLb)" class="u0d81yb0e"/><path fill="url(#i7U2rya)" class="u0d81yb0e"/><path fill="url(#i3q4CNb)" class="u0d81yb0e"/><path fill="url(#iiV86he)" class="mt9itobwb"/><path fill="url(#iQHuKre)" class="mt9itobwb"/><path fill="url(#i1qE2Kd)" class="mt9itobwb"/><path fill="url(#im9Xqmd)" class="mt9itobwb"/><g filter="url(#iG2WHFe)"><path fill="url(#ifiYPrs)" class="wu3us02re"/></g><g filter="url(#inkprte)"><path class="gx2kzlz2c"/><path fill="url(#iKj4Gpd)" class="d87p9sbbt"/></g><g filter="url(#iXmNUKb)"><ellipse fill="url(#iVmDMYb)" class="nr7g6retl"/></g><g filter="url(#iBMyKse)"><path fill="url(#iFkPUGe)" class="qkd4mebsu"/><path fill="url(#i2P0V9c)" class="qkd4mebsu"/><path fill="url(#it7nxqd)" class="qkd4mebsu"/><path fill="url(#ipN27Rb)" class="qkd4mebsu"/><path fill="url(#iGkt9vb)" class="qkd4mebsu"/></g><g filter="url(#iMDW6fc)"><path stroke="url(#ixvIhhb)" class="d18eg08ir"/></g><g filter="url(#ijoqYkS)"><path stroke="url(#iFVIEQd)" class="m-shsob7k"/></g><g filter="url(#iVocGFd)"><path stroke="url(#iMcfXDL)" class="q2yybukwq"/></g><circle fill="url(#i1bdv9d)" class="n02uu-b6x"/><g filter="url(#iQBfLie)"><circle fill="url(#icPCopb)" class="n_k97i32u"/></g><g filter="url(#iaHpYlc)"><circle fill="url(#iWcbioA)" class="apuzrtb6t"/><circle fill="url(#iLLcghd)" class="apuzrtb6t"/></g><g filter="url(#inTSjZc)"><circle class="ubprwdbiq"/><circle fill="url(#iDOEb0b)" class="k2xku0-dm"/><circle fill="url(#iVtihYd)" class="k2xku0-dm"/></g><path fill="url(#iUQbioe)" class="f3dc8hy9a"/><path fill="url(#iQsXxSm)" class="f3dc8hy9a"/><path fill="url(#iA05PMd)" class="f3dc8hy9a"/><path fill="url(#isL7Rld)" class="f3dc8hy9a"/><path fill="url(#iqdjr3b)" class="f3dc8hy9a"/><path fill="url(#ijh6zke)" class="f3dc8hy9a"/><g filter="url(#i0VzMNd)"><path class="lln708bdo"/></g><g filter="url(#iuKgnBb)"><path class="v8p1s8bjz"/><path fill="url(#itQpExY)" class="pw-x-zfsr"/><path fill="url(#imlvExc)" class="pw-x-zfsr"/><path fill="url(#iYcABvb)" class="pw-x-zfsr"/></g><path fill="url(#ivNsMCY)" class="pw-x-zfsr"/><g filter="url(#iOndPqe)"><path stroke="url(#iSDkYic)" class="pg6lbop7x"/></g><path class="wbvw1-bqp"/><path class="g1lvx6b-m"/><path fill="url(#ivt5hFq)" class="sw632_b-v"/><path class="lyvyy0brv"/><g filter="url(#ipNFJOv)"><path class="qs7g0nbma"/><path fill="url(#ierqDib)" class="xrol__bnb"/></g><g filter="url(#imrreBn)"><path fill="url(#iA9XDrb)" class="m244p3pbi"/></g><path class="hs8rglbgr"/><path fill="url(#ifYVlfb)" class="xjn5h7bct"/><path class="f8af11lci"/><g filter="url(#i6hTYTZ)"><path fill="url(#ivvDywd)" class="pmc-e_bfd"/></g><g filter="url(#iSTtSDd)"><ellipse transform="rotate(-27.914 13.165 10.003)" class="zb_39rbvg"/><ellipse fill="url(#iYGcJvb)" transform="rotate(-27.914 13.165 10.003)" class="yy9gddfua"/></g><g filter="url(#i78ihjd)"><path clip-rule="evenodd" class="vriol9bmo"/></g><g filter="url(#ixfqnSd)"><path class="naru7epwh"/></g><g filter="url(#ioVUjpe)"><path clip-rule="evenodd" class="fev3nkbqf"/></g><g filter="url(#iiE3d1d)"><path class="wowbj5avh"/></g><path fill="url(#iFXfCYb)" class="vr9cal3xr"/><path fill="url(#iCTD3pb)" class="vr9cal3xr"/><path fill="url(#iTOy4Wd)" class="n8gff6b-r"/><path fill="url(#iciTVJb)" class="n8gff6b-r"/><g filter="url(#igvZ1xc)"><path fill="url(#i5zXa9b)" class="z6r-ksbnm"/><path fill="url(#iZljIsc)" class="z6r-ksbnm"/></g><path fill="url(#iZ7MGCo)" class="gw6gj7bum"/><path fill="url(#irnsZbd)" class="gw6gj7bum"/><g filter="url(#imDTEWz)"><path fill="url(#indKf4d)" class="dli80jljk"/></g><g filter="url(#iSMS4yc)"><path fill="url(#i2cL8sr)" class="hs4qt_t_d"/></g><g filter="url(#i8V3VZb)"><path fill="url(#i50x7hd)" class="my5p8ss_g"/></g><defs><radialGradient id="ihCks5c" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.719 57.536)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="ivPPUVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 23.694 30.202)" gradientUnits="userSpaceOnUse"><stop class="br4vp4byh"/><stop offset="1" class="fs29nabkl"/></radialGradient><radialGradient id="iHRwpvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.134 30.706)" gradientUnits="userSpaceOnUse"><stop class="gt-1-ac7u"/><stop offset="1" class="yrzv-0byt"/></radialGradient><radialGradient id="ilACw6c" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 20.735 19.677)" gradientUnits="userSpaceOnUse"><stop class="b3mtuebqr"/><stop offset="1" class="txq537bby"/></radialGradient><radialGradient id="ikZukoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.4 32.45)" gradientUnits="userSpaceOnUse"><stop class="ygyrfpbde"/><stop offset="1" class="r7svlnonw"/></radialGradient><radialGradient id="iSKuFve" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.495 16.033)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="iBsIO7c" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 8.999 10.108)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="ir6reNe" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.607 8.618)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="arr7-5bxc"/><stop offset="1" class="mejh1wbdq"/></radialGradient><radialGradient id="ii0Ps7d" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 6.605 19.91)scale(1.88642 1.51516)" gradientUnits="userSpaceOnUse"><stop class="phvlv-hdf"/><stop offset=".828" class="ty_drcd_b"/></radialGradient><radialGradient id="iSdSqLb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 14.869 19.284)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="i7U2rya" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.228 18.159)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="i3q4CNb" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.34 20.456)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="iiV86he" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.205 18.574)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="i1qE2Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 15.76 18.877)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="im9Xqmd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 18.697 21.284)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="iKj4Gpd" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.702 11.243)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="j0jku5-3m"/><stop offset="1" class="r37diw65a"/></radialGradient><radialGradient id="iVmDMYb" cx="0" cy="0" r="1" gradientTransform="rotate(96.148 5.163 20.065)scale(2.87591 2.5871)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dsgtjgbbb"/><stop offset=".746" class="ofpn5ibfj"/></radialGradient><radialGradient id="i2P0V9c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.631 24.564)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="it7nxqd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 23.5 25.94)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="ipN27Rb" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 23.313 27.267)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iGkt9vb" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 23.218 28.534)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="i1bdv9d" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.2 10.781)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iLLcghd" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 26.537 -26.64)scale(1.02361 1.16832)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iDOEb0b" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.352 11.603)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iVtihYd" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.393 10.781)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iA05PMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.59375 -9.8125 0 16.114 9.189)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="isL7Rld" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 17.971 9.509)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iqdjr3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.41 9.475)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iSDkYic" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 15.539 14.797)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="ivt5hFq" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90401 -1.06968 0 17.804 10.433)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ierqDib" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.577 10.183)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifYVlfb" cx="0" cy="0" r="1" gradientTransform="scale(1.06973 .90406)rotate(90 .51 12.05)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iYGcJvb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.654 -1.314)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCTD3pb" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -1.3125 .7375 .32485 10.969 8.328)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="ge1jwqb7d"/><stop offset="1" class="wifa6l5re"/></radialGradient><radialGradient id="iciTVJb" cx="0" cy="0" r="1" gradientTransform="rotate(69.616 4.45 18.342)scale(1.79189 .94568)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="wjcsvfbtk"/><stop offset="1" class="wmfnh5i_q"/></radialGradient><radialGradient id="i5zXa9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.54 6.05)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="zqw5laobm"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="iZljIsc" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.353 2.893)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="iZ7MGCo" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.46875 8.0624 -.10205 18.79 7.3)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="rfhmcsbwp"/><stop offset="1" class="n6auyzb6w"/></radialGradient><filter id="iebEyBb" width="14.3" height="12.3" x="8.381" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/></filter><filter id="iRNkWjb" width="6.538" height="5.771" x="12.023" y="16.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".325"/></filter><filter id="i2SAYVd" width="2.5" height="2.5" x="18.472" y="27.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".25"/></filter><filter id="iMfcyhb" width="2.5" height="2.5" x="18.472" y="23.385" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".25"/></filter><filter id="iNrMqge" width="2.5" height="2.5" x="18.472" y="19.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".25"/></filter><filter id="iW1pdfs" width="1.7" height="1.7" x="19.141" y="27.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1873" result="effect2_innerShadow_4002_1873"/></filter><filter id="iP2nrje" width="1.7" height="1.7" x="19.141" y="23.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1873" result="effect2_innerShadow_4002_1873"/></filter><filter id="iJreLle" width="1.7" height="1.7" x="19.141" y="20.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1873" result="effect2_innerShadow_4002_1873"/></filter><filter id="iLmhqSA" width="2.584" height="3.682" x="25.697" y="22.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/></filter><filter id="iG2WHFe" width="2.238" height="1.809" x="14.532" y="17.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1873" result="effect2_innerShadow_4002_1873"/></filter><filter id="inkprte" width="5.047" height="11.336" x="23.084" y="14.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.552941 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/></filter><filter id="iXmNUKb" width="3.672" height="4.703" x="23.547" y="15.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.662745 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/><feGaussianBlur result="effect2_foregroundBlur_4002_1873" stdDeviation=".05"/></filter><filter id="iBMyKse" width="4.618" height="5.556" x="23.313" y="24.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/></filter><filter id="iMDW6fc" width="2.047" height=".25" x="23.708" y="25.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".05"/></filter><filter id="ijoqYkS" width="2.047" height=".25" x="23.63" y="27.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".05"/></filter><filter id="iVocGFd" width="2.047" height=".25" x="23.708" y="28.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".05"/></filter><filter id="iQBfLie" width="2.992" height="2.992" x="9.375" y="9.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".25"/></filter><filter id="iaHpYlc" width="3.592" height="3.592" x="18.722" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/></filter><filter id="inTSjZc" width="2.992" height="2.992" x="18.897" y="9.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".25"/></filter><filter id="i0VzMNd" width="3.262" height="4.184" x="13.753" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".375"/></filter><filter id="iuKgnBb" width="2.379" height="3.184" x="14.434" y="9.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".125"/></filter><filter id="iOndPqe" width="3.621" height="1.474" x="13.813" y="13.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".05"/></filter><filter id="ipNFJOv" width=".787" height=".697" x="17.07" y="9.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".05"/></filter><filter id="imrreBn" width=".892" height=".914" x="17.91" y="9.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".1"/></filter><filter id="i6hTYTZ" width=".987" height="1.041" x="13.464" y="9.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".1"/></filter><filter id="iSTtSDd" width=".914" height=".705" x="12.709" y="9.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".05"/></filter><filter id="i78ihjd" width="2.604" height="1.648" x="16.888" y="7.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.247059 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/></filter><filter id="ixfqnSd" width="2.709" height="1.502" x="16.836" y="7.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".2"/></filter><filter id="ioVUjpe" width="2.604" height="1.648" x="11.754" y="7.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.247059 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/></filter><filter id="iiE3d1d" width="2.709" height="1.502" x="11.702" y="7.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".2"/></filter><filter id="igvZ1xc" width="14.779" height="5.543" x="8.317" y="2.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1873"/></filter><filter id="imDTEWz" width=".674" height="2.047" x="12.564" y="3.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".05"/></filter><filter id="iSMS4yc" width=".674" height="2.047" x="18.151" y="3.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".05"/></filter><filter id="i8V3VZb" width=".98" height="2.537" x="15.22" y="3.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1873" stdDeviation=".1"/></filter><linearGradient id="iirod2b" x1="22.839" x2="26.082" y1="25.868" y2="25.868" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="iFnTFTb" x1="7.822" x2="7.822" y1="30.987" y2="16.924" gradientUnits="userSpaceOnUse"><stop class="da7b97bvf"/><stop offset="1" class="si_znv48i"/></linearGradient><linearGradient id="iteh88c" x1="8.681" x2="8.103" y1="26.612" y2="26.612" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="iCge4Hc" x1="8.681" x2="12.618" y1="27.198" y2="27.198" gradientUnits="userSpaceOnUse"><stop class="t81o0ct1j"/><stop offset="1" class="v6vn_tcph"/></linearGradient><linearGradient id="iYQnNFc" x1="16.29" x2="13.329" y1="22.118" y2="18.733" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="iOKQVYZ" x1="20.509" x2="19.241" y1="27.632" y2="29.038" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iyR4ftd" x1="20.509" x2="19.241" y1="23.992" y2="25.398" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iRtxbvD" x1="20.509" x2="19.241" y1="20.362" y2="21.768" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iQHuKre" x1="16.384" x2="17.369" y1="17.987" y2="19.159" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="ifiYPrs" x1="15.9" x2="15.9" y1="18.877" y2="17.439" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="iFkPUGe" x1="27.341" x2="23.313" y1="28.032" y2="28.032" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="ixvIhhb" x1="25.514" x2="23.678" y1="25.948" y2="25.948" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iFVIEQd" x1="25.436" x2="23.6" y1="27.252" y2="27.252" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iMcfXDL" x1="25.514" x2="23.678" y1="28.557" y2="28.557" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="icPCopb" x1="10.871" x2="10.23" y1="11.06" y2="11.06" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iWcbioA" x1="21.481" x2="20.661" y1="9.689" y2="12.227" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iUQbioe" x1="19.663" x2="12.019" y1="11.171" y2="12.31" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iQsXxSm" x1="10.222" x2="12.537" y1="13.87" y2="13.568" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="ijh6zke" x1="15.674" x2="15.674" y1="7.313" y2="10.469" gradientUnits="userSpaceOnUse"><stop offset=".04" class="vrr3882ov"/><stop offset=".386" class="q5f78nb8s"/></linearGradient><linearGradient id="itQpExY" x1="14.758" x2="15.697" y1="11.831" y2="11.831" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="imlvExc" x1="16.563" x2="15.536" y1="12.154" y2="12.139" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iYcABvb" x1="15.818" x2="15.818" y1="12.897" y2="12.323" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="ivNsMCY" x1="15.749" x2="15.749" y1="12.939" y2="12.771" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="iA9XDrb" x1="18.583" x2="18.269" y1="10.153" y2="10.346" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivvDywd" x1="14.181" x2="13.867" y1="10.153" y2="10.346" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFXfCYb" x1="10.445" x2="9.8" y1="8.664" y2="8.664" gradientUnits="userSpaceOnUse"><stop class="yjke6abjv"/><stop offset="1" class="nm0swhbin"/></linearGradient><linearGradient id="iTOy4Wd" x1="20.718" x2="20.718" y1="7.258" y2="10.152" gradientUnits="userSpaceOnUse"><stop class="wka6e7qhl"/><stop offset="1" class="bpqz-nbwm"/></linearGradient><linearGradient id="irnsZbd" x1="16.291" x2="16.291" y1="7.768" y2="7.081" gradientUnits="userSpaceOnUse"><stop class="co6smusrg"/><stop offset="1" class="bs-097z7j"/></linearGradient><linearGradient id="indKf4d" x1="13.037" x2="12.459" y1="5.621" y2="5.523" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ka0ki7btw"/><stop offset="1" class="r64vbvf7r"/></linearGradient><linearGradient id="i2cL8sr" x1="18.299" x2="18.931" y1="5.429" y2="5.523" gradientUnits="userSpaceOnUse"><stop offset=".246" class="qu7pewj0n"/><stop offset="1" class="g79jbcb8w"/></linearGradient><linearGradient id="i50x7hd" x1="16" x2="16" y1="5.765" y2="3.738" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mzy53gozy"/><stop offset="1" class="zwaih9noa"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-cook" /></template>
<style>
.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.apuzrtb6t {
  cx: 20.393px;
  cy: 10.781px;
  r: 1.671px;
}

.arr7-5bxc {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b3mtuebqr {
  stop-color: var(--svg-color--e9dae3, #E9DAE3);
}

.b4arxk18h {
  d: path("M8.681 18h10.052c2.177 0 3.948 1.796 3.948 4.003V30h-14z");
}

.bb31kfb8z {
  d: path("M19.991 21.61a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.bpqz-nbwm {
  stop-color: var(--svg-color--f89e26, #F89E26);
}

.br4vp4byh {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
}

.bs-097z7j {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
  stop-opacity: 0;
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co6smusrg {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.d18eg08ir {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.833 25.948h1.797");
}

.d87p9sbbt {
  d: path("M26.06 21.173c0-.405.26-.757.569-1.02c.604-.517 1.002-1.392 1.002-2.385c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.264.567.616.567 1.021v5.056h1.407z");
}

.d8t95rbxw {
  stop-color: var(--svg-color--aa7aa4, #AA7AA4);
}

.d9jlp6fce {
  stop-color: var(--svg-color--b1203d, #B1203D);
}

.da7b97bvf {
  stop-color: var(--svg-color--b59ccc, #B59CCC);
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dli80jljk {
  d: path("m13.138 5.875l-.474-1.847v1.847z");
}

.dsgtjgbbb {
  stop-color: var(--svg-color--e4976b, #E4976B);
}

.e2iag5blt {
  fill: var(--svg-color--bfa9d1, #BFA9D1);
  d: path("M20.472 28.275a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.e4tn_kbzn {
  fill: var(--svg-color--bfa9d1, #BFA9D1);
  d: path("M19.722 25.385a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f3dc8hy9a {
  d: path("M10.504 8.587c0-.267.052-.688.267-.848l.056-.434c.268-.214.492-.018.492-.338v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.053.43.267.43.534v.854c0 .32.16.64.375.854c.503.352.471.546.43.96c-.18 1.792-.235 3.608-.356 5.404c-.16 1.771-1.553 3.006-3.213 3.006H14.04c-1.713 0-3.052-1.235-3.213-3.006c-.139-1.811-.323-3.78-.323-5.598");
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.f8af11lci {
  fill: var(--svg-color--000, #000);
  d: path("M13.947 10.515a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
}

.fev3nkbqf {
  fill: var(--svg-color--ae503e, #AE503E);
  fill-rule: evenodd;
  d: path("M13.842 8.463c-.72-.067-1.183.214-1.295.317a.473.473 0 1 1-.64-.695c.306-.283 1.032-.656 2.023-.564a.473.473 0 0 1-.088.942");
}

.frvthebdh {
  stop-color: var(--svg-color--a498b2, #A498B2);
  stop-opacity: 0;
}

.fs29nabkl {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1lvx6b-m {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.013 9.35c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.34H16.87a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.g79jbcb8w {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
  stop-opacity: 0;
}

.ge1jwqb7d {
  stop-color: var(--svg-color--c66008, #C66008);
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gt-1-ac7u {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
}

.gw6gj7bum {
  d: path("M21.737 5.925H9.683q.027.046.028.101v1.052c0 .248.201.45.45.45H21.26a.45.45 0 0 0 .45-.45V6.023a.2.2 0 0 1 .026-.098");
}

.gx2kzlz2c {
  fill: var(--svg-color--eca779, #ECA779);
  d: path("M26.06 21.173c0-.405.26-.757.569-1.02c.604-.517 1.002-1.392 1.002-2.385c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.264.567.616.567 1.021v5.056h1.407z");
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.hs4qt_t_d {
  d: path("m18.252 5.875l.474-1.847v1.847z");
}

.hs8rglbgr {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.228 9.35c-.654 0-1.206.45-1.356 1.059a.274.274 0 0 0 .268.341h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.129");
}

.i26zq3bfi {
  d: path("M8.681 17.973a10.96 10.96 0 0 0-4 8.477V30h4z");
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.j0jku5-3m {
  stop-color: var(--svg-color--f4b183, #F4B183);
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.jz524ub8q {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M15.661 15.47c-6.07 0-10.98 4.92-10.98 10.98V30h4v-.06h14V30h4v-3.502c0-3.421-1.554-6.481-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.k2xku0-dm {
  cx: 20.393px;
  cy: 10.781px;
  r: 0.996px;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.ka0ki7btw {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.kd6dp8bun {
  d: path("M19.991 25.24a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lln708bdo {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.348 10.66l-.822 1.7c-.101.35.143.7.49.7h.737c.346 0 .59-.355.489-.7l-.5-1.7c-.106-.378-.282-.378-.394 0");
}

.lyvyy0brv {
  fill: var(--svg-color--000, #000);
  d: path("M17.295 10.514a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.236");
}

.m-shsob7k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.755 27.252h1.797");
}

.m244p3pbi {
  d: path("M18.602 10.397a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
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

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.mejh1wbdq {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
  stop-opacity: 0;
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mt9itobwb {
  d: path("M17.864 18.684c-.67-.924-1.704-1.194-2.097-1.245c-.205.83-.307 2.666.684 3.563c.635.574 1.078.722 1.67.787c.164.018.27-.165.222-.322c-.03-.1-.051-.22-.053-.365c-.01-.634.109-1.681-.426-2.418");
}

.my5p8ss_g {
  d: path("M15.42 3.738H16v2.137h-.58z");
}

.mzy53gozy {
  stop-color: var(--svg-color--a990c1, #A990C1);
}

.n_k97i32u {
  cx: 10.871px;
  cy: 10.781px;
  r: 0.996px;
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n02uu-b6x {
  cx: 10.871px;
  cy: 10.781px;
  r: 1.671px;
}

.n6auyzb6w {
  stop-color: var(--svg-color--b1a3bf, #B1A3BF);
}

.n8gff6b-r {
  d: path("M21.455 8.695V7.258H19.98c.047.139.198.47.425.69s.303.596.303.809v1.395c.237 0 .331-.113.549-.53c.174-.333.205-.756.198-.927");
}

.naru7epwh {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.02 8.321c-.21-.192-.804-.52-1.66-.44");
}

.nm0swhbin {
  stop-color: var(--svg-color--ce883e, #CE883E);
}

.nr7g6retl {
  cx: 25.358px;
  cy: 17.713px;
  rx: 1.711px;
  ry: 2.227px;
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.nvjmqub3o {
  d: path("M22.681 30h4v-3.502c0-3.421-1.554-6.481-4-8.498z");
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpn5ibfj {
  stop-color: var(--svg-color--e29457, #E29457);
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.ooqp6liqz {
  d: path("M26.664 23.057a.97.97 0 0 1 .967.967v2.214h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pg6lbop7x {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.623 13.914c-.508 0-.985-.12-1.386-.328c-.137-.07-.285.084-.198.209c.335.508.919.846 1.584.846s1.25-.338 1.585-.846c.086-.13-.061-.28-.198-.21c-.402.21-.874.33-1.387.33Z");
}

.phvlv-hdf {
  stop-color: var(--svg-color--ffdf46, #FFDF46);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmc-e_bfd {
  d: path("M14.25 10.41c0-.29-.234-.481-.297-.54l-.289.28l.178.361z");
}

.pw-x-zfsr {
  d: path("m15.24 10.496l-.531 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q2jbj30-x {
  d: path("M23.09 18.355H8.243a10.94 10.94 0 0 1 7.42-2.885c3.483 0 5.152.811 7.429 2.885");
}

.q2yybukwq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.833 28.557h1.797");
}

.q5f78nb8s {
  stop-color: var(--svg-color--e39328, #E39328);
  stop-opacity: 0;
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qkd4mebsu {
  d: path("M23.313 25.296c0-.402.326-.732.727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1H24.04a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.qpufwi9gx {
  d: path("M20.741 28.13a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.qqj6z8bjg {
  fill: var(--svg-color--c1a0c0, #C1A0C0);
  d: path("M19.722 21.755a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.qs7g0nbma {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.74 9.81c.064.085-.069.189-.22.302s-.264.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.389-.05");
}

.qu7pewj0n {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r37diw65a {
  stop-color: var(--svg-color--f4b183, #F4B183);
  stop-opacity: 0;
}

.r64vbvf7r {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
  stop-opacity: 0;
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.r7svlnonw {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
  stop-opacity: 0;
}

.rfhmcsbwp {
  stop-color: var(--svg-color--eee3f8, #EEE3F8);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.sw632_b-v {
  d: path("M17.806 9.621a.893.893 0 0 1 .86 1.129h-1.724a.896.896 0 0 1 .865-1.129");
}

.t81o0ct1j {
  stop-color: var(--svg-color--9e8fad, #9E8FAD);
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.txq537bby {
  stop-color: var(--svg-color--d8c4e9, #D8C4E9);
}

.ty_drcd_b {
  stop-color: var(--svg-color--f9c116, #F9C116);
}

.u0d81yb0e {
  d: path("M13.469 18.684c.67-.924 1.704-1.194 2.096-1.245c.205.83.308 2.666-.684 3.563c-.635.574-1.077.722-1.67.787c-.163.018-.269-.165-.221-.322q.047-.149.053-.365c.009-.634-.11-1.681.426-2.418");
}

.ubprwdbiq {
  cx: 20.393px;
  cy: 10.781px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6vn_tcph {
  stop-color: var(--svg-color--c0b0d1, #C0B0D1);
  stop-opacity: 0;
}

.v8p1s8bjz {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.24 10.496l-.531 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.vf29eozqp {
  d: path("M15.661 15.47c-6.07 0-10.98 4.92-10.98 10.98V30h4v-.06h14V30h4v-3.502c0-3.421-1.554-6.481-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.vr9cal3xr {
  d: path("M9.8 8.695V7.258h1.476a2 2 0 0 1-.425.69c-.227.22-.303.596-.303.809v1.395c-.236 0-.331-.113-.549-.53c-.174-.333-.205-.756-.198-.927");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vriol9bmo {
  fill: var(--svg-color--ae503e, #AE503E);
  fill-rule: evenodd;
  d: path("M17.405 8.463c.72-.067 1.182.214 1.294.317a.473.473 0 1 0 .64-.695c-.306-.283-1.031-.656-2.022-.564a.473.473 0 1 0 .088.942");
}

.vrr3882ov {
  stop-color: var(--svg-color--e39328, #E39328);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wbvw1-bqp {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.623 13.914c-.508 0-.985-.12-1.386-.328c-.137-.07-.285.084-.198.209c.335.508.919.846 1.584.846s1.25-.338 1.585-.846c.086-.13-.061-.28-.198-.21c-.402.21-.874.33-1.387.33");
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wifa6l5re {
  stop-color: var(--svg-color--c66008, #C66008);
  stop-opacity: 0;
}

.wjcsvfbtk {
  stop-color: var(--svg-color--dc7a0f, #DC7A0F);
}

.wka6e7qhl {
  stop-color: var(--svg-color--ffbc2c, #FFBC2C);
}

.wmfnh5i_q {
  stop-color: var(--svg-color--dc7a0f, #DC7A0F);
  stop-opacity: 0;
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wowbj5avh {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.227 8.321c.21-.192.803-.52 1.659-.44");
}

.wu3us02re {
  d: path("M14.993 17.558c.19-.063.44-.12.707-.12c.268 0 .517.057.708.12a.39.39 0 0 1 .254.45c-.092.486-.27.8-.463.99a.5.5 0 0 1-.268.13a1.5 1.5 0 0 1-.477 0a.43.43 0 0 1-.251-.13c-.195-.19-.372-.504-.464-.99a.39.39 0 0 1 .254-.45");
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xjn5h7bct {
  d: path("M13.435 9.621a.893.893 0 0 0-.86 1.129H14.3a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.xrol__bnb {
  d: path("M17.74 9.81c.064.085-.069.189-.22.302s-.264.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.389-.05");
}

.ygyrfpbde {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
}

.yi80usmmo {
  d: path("M15.394 17.496c-.384.032-1.404.252-2.102 1.142c-.47.599-.498 1.44-.52 2.068q-.005.177-.014.327q-.016.216-.07.362c-.054.155.04.342.2.332c.58-.036 1.018-.163 1.665-.705c.492-.414.742-1.063.85-1.717c.044.662.229 1.332.678 1.792c.59.604 1.013.773 1.587.867c.157.025.27-.152.23-.31a1.4 1.4 0 0 1-.033-.369q.006-.15.018-.326c.041-.627.096-1.467-.312-2.11c-.607-.954-1.6-1.274-1.98-1.344a5 5 0 0 0-.127.583a5 5 0 0 0-.07-.593");
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.yjke6abjv {
  stop-color: var(--svg-color--d8822e, #D8822E);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.yrzv-0byt {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
  stop-opacity: 0;
}

.yy9gddfua {
  cx: 13.165px;
  cy: 10.003px;
  rx: 0.39px;
  ry: 0.197px;
}

.z6r-ksbnm {
  d: path("M10.25 2.085a1.933 1.933 0 0 0-.681 3.743a.215.215 0 0 1 .143.198v1.052c0 .248.201.45.45.45H21.26a.45.45 0 0 0 .45-.45V6.023c0-.089.059-.166.141-.198a1.934 1.934 0 0 0-.69-3.74z");
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zb_39rbvg {
  cx: 13.165px;
  cy: 10.003px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zqw5laobm {
  stop-color: var(--svg-color--aa92c2, #AA92C2);
}

.zwaih9noa {
  stop-color: var(--svg-color--a990c1, #A990C1);
  stop-opacity: 0;
}

</style>
