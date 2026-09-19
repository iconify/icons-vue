<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipxqfNb)" class="c5pyn6kwp"/><path fill="url(#ixtGmqe)" class="c5pyn6kwp"/><path fill="url(#iu4BL0y)" class="c5pyn6kwp"/><path fill="url(#i6kQckA)" class="c5pyn6kwp"/><path fill="url(#ivcbSbu)" class="d42a8nbyx"/><path fill="url(#imxslwc)" class="d42a8nbyx"/><path fill="url(#iCIPAvc)" class="sy7gbya4q"/><path fill="url(#ib2sn4d)" class="sy7gbya4q"/><g filter="url(#iUDnd8b)"><path fill="url(#i6aJFZY)" class="cd8uxyblt"/><path fill="url(#izDA0dI)" class="cd8uxyblt"/></g><g filter="url(#ib6gjPd)"><path class="v7lobvb0w"/><path fill="url(#i4dkT0d)" class="blsopp2mg"/><path fill="url(#izjH7xz)" class="blsopp2mg"/></g><g filter="url(#idwC1cc)"><ellipse transform="rotate(-40.534 9.937 22.244)" class="a_d5m7-5r"/></g><ellipse fill="url(#iuxxmBb)" transform="rotate(-40.534 9.886 22.154)" class="fvifkjh5i"/><g filter="url(#iINuB2c)"><ellipse transform="scale(-1 1)rotate(-35.343 23.849 45.555)" class="n11xmqb_x"/></g><ellipse fill="url(#imtwsXc)" transform="scale(-1 1)rotate(-40.534 18.955 40.983)" class="tto44ccna"/><g filter="url(#ireG8Vc)"><rect fill="url(#i1U54LR)" class="qyeoy6a8h"/><rect fill="url(#iZgh3lf)" class="qyeoy6a8h"/><rect fill="url(#izJ86Ne)" class="qyeoy6a8h"/></g><rect fill="url(#ie86Gud)" class="gx_0zqbtq"/><path fill="url(#iYKVIWb)" class="g4mvl20po"/><path fill="url(#iDWpPDG)" class="g4mvl20po"/><g filter="url(#iN6SfKe)"><circle class="wfn54lnxd"/></g><g filter="url(#iYgggpc)"><circle class="a1tpsrb8u"/></g><circle fill="url(#iYFehJc)" class="sx6q1cbyi"/><circle fill="url(#iO6rBqd)" class="cad66eb8i"/><circle fill="url(#i5EHinb)" class="c-82tbczp"/><g filter="url(#i4eB5Ld)"><circle fill="url(#iUpbFEG)" class="y07a6kbzi"/></g><g filter="url(#ivuCQ6c)"><circle fill="url(#iHM4vUv)" class="vhkjfhb6j"/><circle fill="url(#iTlPjme)" class="vhkjfhb6j"/></g><g filter="url(#iBg4Apb)"><circle class="l3pckibxq"/><circle fill="url(#idj20ie)" class="z7nk_dj9j"/><circle fill="url(#iBmY0Ne)" class="z7nk_dj9j"/></g><g filter="url(#iDOVFUc)"><path fill="url(#izyaG6b)" class="vgc7sxbfz"/><path fill="url(#iZHJsxd)" class="vgc7sxbfz"/><path fill="url(#iRgtACc)" class="vgc7sxbfz"/><path fill="url(#ihkNXFc)" class="vgc7sxbfz"/><path fill="url(#i9EmNXd)" class="vgc7sxbfz"/><path fill="url(#ipNOwfd)" class="vgc7sxbfz"/></g><path class="jjwzsgbte"/><g filter="url(#iLDCzym)"><path class="etvg7sgev"/></g><g filter="url(#i1y5aYb)"><path class="ghx8gcraz"/><path fill="url(#iTC9KPb)" class="ccvft17ek"/><path fill="url(#iTYnhpc)" class="ccvft17ek"/><path fill="url(#inUimQD)" class="ccvft17ek"/></g><g filter="url(#iL6CoFd)"><path fill="url(#ix30ZVb)" class="et8i_jb5i"/></g><g filter="url(#iRr1Lic)"><path stroke="url(#insmshe)" class="h1toaudvx"/></g><path class="oo_rztnfc"/><path class="d-nm079ju"/><path fill="url(#iJlbyHd)" class="zezksebju"/><path class="rv_p3h2st"/><g filter="url(#iqqrldb)"><path class="ig0-p4pru"/><path fill="url(#iB7OBPJ)" class="t3qq63bln"/></g><g filter="url(#iTRb78d)"><path fill="url(#imW8oPb)" class="f2j1c12os"/></g><path class="rhwowbbqa"/><path fill="url(#iGfA2RZ)" class="dytuwhbeb"/><path class="dt7hl8b9e"/><g filter="url(#izbvVAb)"><path fill="url(#iEl94sO)" class="n95juusso"/></g><g filter="url(#i10bJhe)"><ellipse transform="rotate(-27.914 13.534 14.477)" class="qqmjsks8f"/><ellipse fill="url(#ibQFhDc)" transform="rotate(-27.914 13.534 14.477)" class="a6f2rbbfa"/></g><g filter="url(#ihT4hmc)"><path fill="url(#il1AcPe)" class="gw4u-ub3u"/><path fill="url(#is0vYcc)" class="gw4u-ub3u"/></g><path fill="url(#iWLVOVc)" class="gw4u-ub3u"/><path fill="url(#i2pBBLt)" class="gw4u-ub3u"/><path fill="url(#isYcgqc)" class="gw4u-ub3u"/><g filter="url(#ioH2hqW)"><path fill="url(#iEi7LFc)" class="sfe148-0e"/><path fill="url(#iB21tpe)" class="sfe148-0e"/><path fill="url(#iyBJvOb)" class="sfe148-0e"/></g><defs><radialGradient id="ipxqfNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71875 -19.3424 0 16 26.99)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="u2-vnsrzx"/><stop offset="1" class="u25v0cb4e"/></radialGradient><radialGradient id="ixtGmqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 0 0 -8.81836 22.928 27.146)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hztqsacfn"/><stop offset="1" class="g15tcgc_e"/></radialGradient><radialGradient id="ivcbSbu" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -8.07812 2.82155 .68765 6.74 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="y6ictpbdv"/><stop offset="1" class="exer9ybqp"/></radialGradient><radialGradient id="iCIPAvc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.449 24.978 4.727)scale(7.55662 1.96679)" gradientUnits="userSpaceOnUse"><stop class="z2ubpb-up"/><stop offset="1" class="icppbwd3b"/></radialGradient><radialGradient id="ib2sn4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.366 .65507 0 22.942 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="p9dhe0cfb"/><stop offset="1" class="m7r_2tbtp"/></radialGradient><radialGradient id="i6aJFZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -3.29137 2.72714 9.71 21.208)" gradientUnits="userSpaceOnUse"><stop class="tuvqdtb4j"/><stop offset="1" class="mw-6yhbvl"/></radialGradient><radialGradient id="izDA0dI" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.85937 -.47826 .45816 8.381 22.458)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="aok9j0bwd"/><stop offset="1" class="ul3ws4blr"/></radialGradient><radialGradient id="i4dkT0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 .25 -.73637 3.86594 19.569 21.146)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="wcylmi-4x"/><stop offset="1" class="lcybi9bke"/></radialGradient><radialGradient id="izjH7xz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 1.09375 -.16383 -.18256 23.498 22.2)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iuxxmBb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.136 6.388 10.772)scale(1.64141 .91814)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="k5s0mt74t"/><stop offset="1" class="hfobxebps"/></radialGradient><radialGradient id="imtwsXc" cx="0" cy="0" r="1" gradientTransform="matrix(.678 .80592 -1.4278 1.20118 .1 .257)" gradientUnits="userSpaceOnUse"><stop class="w_-x-cc4i"/><stop offset="1" class="xbkp5vbln"/></radialGradient><radialGradient id="i1U54LR" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68749 -3.76563 4.9287 -3.51755 18.1 23.911)" gradientUnits="userSpaceOnUse"><stop class="mg6vw6bqp"/><stop offset="1" class="f_x1tcb5s"/></radialGradient><radialGradient id="iZgh3lf" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 0 0 -.91123 15.538 23.763)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="w_5lucbuv"/><stop offset="1" class="x_olikxjr"/></radialGradient><radialGradient id="izJ86Ne" cx="0" cy="0" r="1" gradientTransform="rotate(112.38 -.17 15.586)scale(1.14905 2.6882)" gradientUnits="userSpaceOnUse"><stop class="ay981bbmw"/><stop offset="1" class="co8373ibr"/></radialGradient><radialGradient id="ie86Gud" cx="0" cy="0" r="1" gradientTransform="rotate(51.989 -14.741 27.087)scale(1.72534 2.83656)" gradientUnits="userSpaceOnUse"><stop class="fmz42zp1p"/><stop offset="1" class="gumxcfc4t"/></radialGradient><radialGradient id="iYFehJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 25.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iO6rBqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 28.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="i5EHinb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.568 15.255)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iTlPjme" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.134 14.99)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="idj20ie" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.72 16.078)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iBmY0Ne" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.76 15.255)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="izyaG6b" cx="0" cy="0" r="1" gradientTransform="rotate(-172.91 10.46 8.334)scale(6.32965 9.56112)" gradientUnits="userSpaceOnUse"><stop class="x5ozldbku"/><stop offset="1" class="as9qb1byz"/></radialGradient><radialGradient id="iRgtACc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.59375 -9.8125 0 16.483 13.663)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="ihkNXFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.34 13.983)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="i9EmNXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.777 13.95)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="insmshe" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 15.906 19.271)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iJlbyHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15625 1.36814 0 18.172 15.318)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="nl-zfpbdy"/><stop offset="1" class="xd8uf9-7v"/></radialGradient><radialGradient id="iB7OBPJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.943 14.658)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGfA2RZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15631 1.36821 0 13.805 15.318)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="nl-zfpbdy"/><stop offset="1" class="xd8uf9-7v"/></radialGradient><radialGradient id="ibQFhDc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.04 .742)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWLVOVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3535 18.2706 0 15.953 14.155)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="guwslmx9m"/><stop offset="1" class="csva0fh9x"/></radialGradient><radialGradient id="i2pBBLt" cx="0" cy="0" r="1" gradientTransform="rotate(-179.736 10.798 2.33)scale(6.78132 1.9151)" gradientUnits="userSpaceOnUse"><stop class="ak4i8vy1v"/><stop offset="1" class="d0nv29baz"/></radialGradient><radialGradient id="iyBJvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46875 -.51569 0 21.381 16.27)" gradientUnits="userSpaceOnUse"><stop class="qqll8tbvj"/><stop offset="1" class="i1pxvjzop"/></radialGradient><filter id="iUDnd8b" width="4.755" height="3.491" x="8.464" y="20.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2836"/></filter><filter id="ib6gjPd" width="4.705" height="3.591" x="18.753" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2836"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.0666667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2836" result="effect2_innerShadow_4002_2836"/></filter><filter id="idwC1cc" width="2.189" height="2.153" x="8.842" y="21.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".25"/></filter><filter id="iINuB2c" width="1.692" height="1.595" x="21.111" y="21.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".125"/></filter><filter id="ireG8Vc" width="7.744" height="9.694" x="12.072" y="14.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2836"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2836" result="effect2_innerShadow_4002_2836"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.172549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2836" result="effect3_innerShadow_4002_2836"/></filter><filter id="iN6SfKe" width="2.09" height="2.09" x="16.395" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".25"/></filter><filter id="iYgggpc" width="2.09" height="2.09" x="16.395" y="27.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".25"/></filter><filter id="i4eB5Ld" width="2.992" height="2.992" x="9.743" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".25"/></filter><filter id="ivuCQ6c" width="3.592" height="3.592" x="19.09" y="13.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2836"/></filter><filter id="iBg4Apb" width="2.992" height="2.992" x="19.265" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".25"/></filter><filter id="iDOVFUc" width="11.034" height="12.689" x="10.178" y="8.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.65" dy="-.65"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.458824 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2836"/></filter><filter id="iLDCzym" width="3.262" height="4.184" x="14.121" y="14.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".375"/></filter><filter id="i1y5aYb" width="2.379" height="3.184" x="14.802" y="14.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".125"/></filter><filter id="iL6CoFd" width="2.379" height="3.184" x="14.802" y="14.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".125"/></filter><filter id="iRr1Lic" width="3.621" height="1.474" x="14.181" y="17.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".05"/></filter><filter id="iqqrldb" width=".787" height=".697" x="17.438" y="14.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".05"/></filter><filter id="iTRb78d" width=".892" height=".914" x="18.278" y="14.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".1"/></filter><filter id="izbvVAb" width=".987" height="1.041" x="13.832" y="14.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".1"/></filter><filter id="i10bJhe" width=".914" height=".705" x="13.077" y="14.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2836" stdDeviation=".05"/></filter><filter id="ihT4hmc" width="13.655" height="12.317" x="9.076" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2836"/></filter><filter id="ioH2hqW" width="10.882" height="7.996" x="10.499" y="14.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.635294 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2836"/></filter><linearGradient id="iu4BL0y" x1="9.026" x2="9.233" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="g-00mbcgn"/><stop offset="1" class="tvzw53atw"/></linearGradient><linearGradient id="i6kQckA" x1="22.975" x2="22.827" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yacpd-mqw"/><stop offset="1" class="m2jbcqdpu"/></linearGradient><linearGradient id="imxslwc" x1="9.397" x2="8.084" y1="29.739" y2="29.739" gradientUnits="userSpaceOnUse"><stop class="s2ol_bbam"/><stop offset="1" class="hm-si4p_s"/></linearGradient><linearGradient id="iYKVIWb" x1="15.984" x2="15.984" y1="23.197" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ty59qw5cn"/><stop offset="1" class="jwfvhhlnv"/></linearGradient><linearGradient id="iDWpPDG" x1="16.479" x2="16.147" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="z_332kbzw"/><stop offset="1" class="v6fzn4zbl"/></linearGradient><linearGradient id="iUpbFEG" x1="11.239" x2="10.598" y1="15.534" y2="15.534" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iHM4vUv" x1="21.849" x2="21.029" y1="14.163" y2="16.701" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iZHJsxd" x1="10.59" x2="12.905" y1="18.344" y2="18.042" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="ipNOwfd" x1="16.02" x2="16.02" y1="13.989" y2="15.443" gradientUnits="userSpaceOnUse"><stop offset=".097" class="hotayftkc"/><stop offset="1" class="w_ikrdbrc"/></linearGradient><linearGradient id="iTC9KPb" x1="15.126" x2="16.065" y1="16.305" y2="16.305" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iTYnhpc" x1="17.251" x2="15.751" y1="16.458" y2="16.443" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="inUimQD" x1="16.186" x2="16.186" y1="17.371" y2="16.797" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="ix30ZVb" x1="15.991" x2="16.282" y1="14.524" y2="15.982" gradientUnits="userSpaceOnUse"><stop class="wn31yqbtg"/><stop offset="1" class="lp7iiz5ue"/></linearGradient><linearGradient id="imW8oPb" x1="18.951" x2="18.637" y1="14.627" y2="14.82" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEl94sO" x1="14.549" x2="14.235" y1="14.627" y2="14.82" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="il1AcPe" x1="19.866" x2="12.584" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="j8rdzr3lb"/><stop offset=".554" class="h5foydtlz"/><stop offset="1" class="roy3-sbpo"/></linearGradient><linearGradient id="is0vYcc" x1="9.709" x2="12.428" y1="11.989" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="bamb_e30h"/><stop offset="1" class="szoje-bkc"/></linearGradient><linearGradient id="isYcgqc" x1="16.538" x2="16.538" y1="14.155" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="ip1t-iw4f"/><stop offset="1" class="l0ic_xblz"/></linearGradient><linearGradient id="iEi7LFc" x1="21.116" x2="15.022" y1="18.489" y2="18.489" gradientUnits="userSpaceOnUse"><stop class="haq-yyb5a"/><stop offset="1" class="fnv2cqusr"/></linearGradient><linearGradient id="iB21tpe" x1="15.941" x2="15.941" y1="13.927" y2="15.458" gradientUnits="userSpaceOnUse"><stop class="aa_k4sbxt"/><stop offset="1" class="t9tvqlbrf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-guard" /></template>
<style>
.a_d5m7-5r {
  cx: 9.937px;
  cy: 22.244px;
  fill: var(--svg-color--321f22, #321F22);
  rx: 0.641px;
  ry: 0.524px;
}

.a1tpsrb8u {
  cx: 17.439px;
  cy: 28.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.a6f2rbbfa {
  cx: 13.534px;
  cy: 14.477px;
  rx: 0.39px;
  ry: 0.197px;
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.aa_k4sbxt {
  stop-color: var(--svg-color--cc9bd2, #CC9BD2);
}

.ak4i8vy1v {
  stop-color: var(--svg-color--686070, #686070);
}

.aok9j0bwd {
  stop-color: var(--svg-color--4b4551, #4B4551);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.ay981bbmw {
  stop-color: var(--svg-color--452139, #452139);
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.bamb_e30h {
  stop-color: var(--svg-color--4d4c50, #4D4C50);
}

.blsopp2mg {
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.c-82tbczp {
  cx: 11.239px;
  cy: 15.255px;
  r: 1.671px;
}

.c5pyn6kwp {
  d: path("M5.428 29.911h21.144c-.19-5.356-4.591-9.64-9.994-9.64h-1.156c-5.403 0-9.805 4.284-9.994 9.64");
}

.cad66eb8i {
  cx: 17.494px;
  cy: 28.374px;
  r: 0.545px;
}

.ccvft17ek {
  d: path("m15.609 14.97l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.cd8uxyblt {
  d: path("M11.926 20.161c-1.363.418-2.538 1.308-3.179 1.936a.46.46 0 0 0 .011.659l.65.649a.523.523 0 0 0 .705.02a12.3 12.3 0 0 1 3.106-1.857z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co8373ibr {
  stop-color: var(--svg-color--452139, #452139);
  stop-opacity: 0;
}

.csva0fh9x {
  stop-color: var(--svg-color--403947, #403947);
}

.d-nm079ju {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.381 13.824c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.341h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.129");
}

.d0nv29baz {
  stop-color: var(--svg-color--686070, #686070);
  stop-opacity: 0;
}

.d42a8nbyx {
  d: path("M9.058 29.911h-3.63a9.98 9.98 0 0 1 3.63-7.355z");
}

.dt7hl8b9e {
  fill: var(--svg-color--000, #000);
  d: path("M14.315 14.988a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
}

.dwh48tz1p {
  stop-color: var(--svg-color--5e5864, #5E5864);
}

.dytuwhbeb {
  d: path("M13.803 14.096a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.894");
}

.e2y-fbcxj {
  stop-color: var(--svg-color--fca239, #FCA239);
}

.et8i_jb5i {
  d: path("m15.609 14.806l-.532 1.702a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.702c-.114-.376-.646-.376-.765 0");
}

.etvg7sgev {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.716 15.133l-.821 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.489-.7l-.5-1.701c-.106-.377-.282-.377-.394 0");
}

.exer9ybqp {
  stop-color: var(--svg-color--b13b50, #B13B50);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f_x1tcb5s {
  stop-color: var(--svg-color--482949, #482949);
}

.f2j1c12os {
  d: path("M18.97 14.871a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.fmz42zp1p {
  stop-color: var(--svg-color--f28235, #F28235);
}

.fnv2cqusr {
  stop-color: var(--svg-color--e3bbe0, #E3BBE0);
}

.ft5dv1b6b {
  fill: none;
}

.fvifkjh5i {
  cx: 9.886px;
  cy: 22.154px;
  rx: 0.641px;
  ry: 0.524px;
}

.g-00mbcgn {
  stop-color: var(--svg-color--c2254a, #C2254A);
}

.g15tcgc_e {
  stop-color: var(--svg-color--ff6085, #FF6085);
  stop-opacity: 0;
}

.g4mvl20po {
  d: path("M15.49 23.203v6.708h.989v-6.714a2 2 0 0 1-.409.042h-.203q-.194 0-.377-.036");
}

.ghx8gcraz {
  fill: var(--svg-color--ffab1e, #FFAB1E);
  d: path("m15.609 14.97l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.gumxcfc4t {
  stop-color: var(--svg-color--fdac39, #FDAC39);
}

.guwslmx9m {
  stop-color: var(--svg-color--403947, #403947);
  stop-opacity: 0;
}

.gw4u-ub3u {
  d: path("M10.31 14.155c-.278-.016-.842-.08-1.054-.728c-.11-.37.082-.779.143-.91l.004-.008l.02-.04c.061-.121.152-.298-.02-.578c-.193-.313-.375-.615-.045-1.257c.207-.405.093-.652-.032-.875c-.183-.327-.166-.604 0-.938c.07-.143.173-.275.173-.472c0-.198-.07-.335-.141-.474c-.074-.143-.148-.289-.148-.504c0-.23.084-.398.161-.554c.066-.133.128-.257.128-.402c0-.129-.06-.24-.125-.364c-.094-.178-.201-.38-.164-.69c.071-.59.537-.787.756-.879l.02-.008c.21-.089.364-.163.452-.58c.046-.215.132-.502.293-.663a1.06 1.06 0 0 1 .791-.3c.257.007.535-.03.752-.254c.217-.225.458-.413.699-.453s.471.014.725.144c.281.145.567.07.705-.035c.34-.262.718-.32 1.158-.141c.18.072.295.112.394.112c.098 0 .214-.04.393-.112c.44-.18.819-.12 1.159.141a.68.68 0 0 0 .704.035c.254-.13.484-.184.725-.144s.483.228.7.453s.494.261.75.253a1.06 1.06 0 0 1 .793.301c.16.161.246.448.292.663c.088.417.243.491.452.58l.02.008c.219.092.685.288.756.878c.038.31-.07.513-.164.69c-.065.124-.125.236-.125.365c0 .145.062.269.128.402c.078.156.161.324.161.554c0 .215-.074.36-.147.504a.94.94 0 0 0-.105.466c0 .528.496.742.176 1.422c-.125.223-.324.455-.117.86c.33.641.193.955 0 1.268c-.171.28-.081.457-.02.577l.02.041l.005.009c.06.13.252.54.142.909c-.212.649-.775.712-1.054.728z");
}

.gx_0zqbtq {
  width: 4.141px;
  height: 5.141px;
  x: 13.898px;
  y: 18.099px;
  rx: 1.969px;
}

.h1toaudvx {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.991 18.388c-.508 0-.985-.12-1.386-.329c-.137-.07-.285.085-.198.21c.335.508.919.846 1.584.846c.666 0 1.25-.338 1.585-.846c.086-.13-.061-.28-.198-.21c-.402.21-.874.33-1.387.33Z");
}

.h5foydtlz {
  stop-color: var(--svg-color--4b3c5b, #4B3C5B);
}

.haq-yyb5a {
  stop-color: var(--svg-color--f6d3f9, #F6D3F9);
}

.hfobxebps {
  stop-color: var(--svg-color--dcb144, #DCB144);
}

.hm-si4p_s {
  stop-color: var(--svg-color--c9345b, #C9345B);
  stop-opacity: 0;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hotayftkc {
  stop-color: var(--svg-color--cd7c20, #CD7C20);
}

.hztqsacfn {
  stop-color: var(--svg-color--ff6085, #FF6085);
}

.i1pxvjzop {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
  stop-opacity: 0;
}

.icppbwd3b {
  stop-color: var(--svg-color--e34c67, #E34C67);
}

.ig0-p4pru {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.109 14.284c.063.085-.07.19-.221.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.359c.15-.113.325-.136.389-.05");
}

.ip1t-iw4f {
  stop-color: var(--svg-color--462659, #462659);
}

.j8rdzr3lb {
  stop-color: var(--svg-color--5d536a, #5D536A);
}

.jjwzsgbte {
  fill: var(--svg-color--d47615, #D47615);
  d: path("m20.815 8.772l.43.213c.75.374 1.18 1.228 1.02 2.136l-.591 3.043c-.053.314-.26.525-.573.533c.036-.504.07-1.317.082-1.446c.044-.433-.025-.56-.422-.956c-.215-.213-.376-.534-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.375.854l-.162.16c-.214.16-.323.495-.323.762c.014.156.036 1.052.06 1.425a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.854.322-1.708 1.074-2.082c1.014-.445 1.384-1.12 2.2-1.815c.591-.534 1.45-.694 2.202-.32c.537.16 1.128.16 1.665 0c.805-.267 1.718-.053 2.362.534l.805.8c.215.267.483.428.806.588");
}

.jwfvhhlnv {
  stop-color: var(--svg-color--d8bbeb, #D8BBEB);
}

.k5s0mt74t {
  stop-color: var(--svg-color--cc981a, #CC981A);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l0ic_xblz {
  stop-color: var(--svg-color--462659, #462659);
  stop-opacity: 0;
}

.l3pckibxq {
  cx: 20.761px;
  cy: 15.255px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lcybi9bke {
  stop-color: var(--svg-color--513f4e, #513F4E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lp7iiz5ue {
  stop-color: var(--svg-color--e79827, #E79827);
  stop-opacity: 0;
}

.m2jbcqdpu {
  stop-color: var(--svg-color--fc356b, #FC356B);
  stop-opacity: 0;
}

.m7r_2tbtp {
  stop-color: var(--svg-color--ee5076, #EE5076);
  stop-opacity: 0;
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mg6vw6bqp {
  stop-color: var(--svg-color--5d4364, #5D4364);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mw-6yhbvl {
  stop-color: var(--svg-color--382834, #382834);
}

.n11xmqb_x {
  fill: var(--svg-color--3e3138, #3E3138);
  rx: 0.641px;
  ry: 0.494px;
}

.n95juusso {
  d: path("M14.619 14.884c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.nl-zfpbdy {
  stop-color: var(--svg-color--764b4c, #764B4C);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oo_rztnfc {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.991 18.388c-.508 0-.985-.12-1.386-.329c-.137-.07-.285.085-.198.21c.335.508.919.846 1.584.846c.666 0 1.25-.338 1.585-.846c.086-.13-.061-.28-.198-.21c-.402.21-.874.33-1.387.33");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.p9dhe0cfb {
  stop-color: var(--svg-color--e11c59, #E11C59);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qqll8tbvj {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
}

.qqmjsks8f {
  cx: 13.534px;
  cy: 14.477px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qyeoy6a8h {
  width: 7.594px;
  height: 9.594px;
  x: 12.172px;
  y: 14.927px;
  rx: 3.797px;
}

.rhwowbbqa {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.596 13.824c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.129");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.roy3-sbpo {
  stop-color: var(--svg-color--393341, #393341);
}

.rv_p3h2st {
  fill: var(--svg-color--000, #000);
  d: path("M17.663 14.989a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s2ol_bbam {
  stop-color: var(--svg-color--ac394e, #AC394E);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sfe148-0e {
  d: path("m10.5 14.156l.12 3.518c.082 2.424 2.07 4.378 4.497 4.378h1.677c2.44 0 4.436-1.976 4.498-4.416l.09-3.48h-.909l-.12 3.48c-.049 1.898-1.661 3.486-3.56 3.486h-1.676c-1.887 0-3.489-1.597-3.553-3.482l-.09-3.485z");
}

.sx6q1cbyi {
  cx: 17.494px;
  cy: 25.374px;
  r: 0.545px;
}

.sy7gbya4q {
  d: path("M22.942 29.911h3.63a9.98 9.98 0 0 0-3.63-7.355z");
}

.szoje-bkc {
  stop-color: var(--svg-color--393341, #393341);
  stop-opacity: 0;
}

.t3qq63bln {
  d: path("M18.109 14.284c.063.085-.07.19-.221.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.359c.15-.113.325-.136.389-.05");
}

.t9tvqlbrf {
  stop-color: var(--svg-color--e5bde2, #E5BDE2);
  stop-opacity: 0;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tto44ccna {
  rx: 0.641px;
  ry: 0.524px;
}

.tuvqdtb4j {
  stop-color: var(--svg-color--454048, #454048);
}

.tvzw53atw {
  stop-color: var(--svg-color--c2254a, #C2254A);
  stop-opacity: 0;
}

.ty59qw5cn {
  stop-color: var(--svg-color--dbb8dd, #DBB8DD);
}

.u2-vnsrzx {
  stop-color: var(--svg-color--f73c71, #F73C71);
}

.u25v0cb4e {
  stop-color: var(--svg-color--d6274f, #D6274F);
}

.ul3ws4blr {
  stop-color: var(--svg-color--4b4551, #4B4551);
  stop-opacity: 0;
}

.v6fzn4zbl {
  stop-color: var(--svg-color--eacceb, #EACCEB);
  stop-opacity: 0;
}

.v7lobvb0w {
  fill: var(--svg-color--554b59, #554B59);
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.vgc7sxbfz {
  d: path("M10.887 14.642a30 30 0 0 1-.059-1.44c0-.266.108-.587.322-.747l.162-.16c.268-.214.375-.534.375-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.215.053.43.267.43.534v.854c0 .32.16.64.375.854c.503.352.471.546.43.96c-.013.13-.054 1.196-.09 1.442l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.713 0-3.052-1.235-3.213-3.006z");
}

.vhkjfhb6j {
  cx: 20.761px;
  cy: 15.255px;
  r: 1.671px;
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.w_-x-cc4i {
  stop-color: var(--svg-color--ffff50, #FFFF50);
}

.w_5lucbuv {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
}

.w_ikrdbrc {
  stop-color: var(--svg-color--fba629, #FBA629);
  stop-opacity: 0;
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wcylmi-4x {
  stop-color: var(--svg-color--513f4e, #513F4E);
}

.wfn54lnxd {
  cx: 17.439px;
  cy: 25.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.wn31yqbtg {
  stop-color: var(--svg-color--e79827, #E79827);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x_olikxjr {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
  stop-opacity: 0;
}

.x2r0w67qw {
  stop-color: var(--svg-color--fff153, #FFF153);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x5ozldbku {
  stop-color: var(--svg-color--ffdd32, #FFDD32);
}

.xbkp5vbln {
  stop-color: var(--svg-color--f6cf1c, #F6CF1C);
}

.xd8uf9-7v {
  stop-color: var(--svg-color--563237, #563237);
}

.y07a6kbzi {
  cx: 11.239px;
  cy: 15.255px;
  r: 0.996px;
}

.y6ictpbdv {
  stop-color: var(--svg-color--e43669, #E43669);
}

.yacpd-mqw {
  stop-color: var(--svg-color--fc356b, #FC356B);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.z_332kbzw {
  stop-color: var(--svg-color--eacceb, #EACCEB);
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

.z7nk_dj9j {
  cx: 20.761px;
  cy: 15.255px;
  r: 0.996px;
}

.zezksebju {
  d: path("M18.174 14.096a.893.893 0 0 1 .86 1.128H17.31a.896.896 0 0 1 .865-1.129");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

</style>
