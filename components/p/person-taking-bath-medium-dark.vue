<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="f6t-uxb_c"/><path fill="url(#iMdm93b)" class="pryz6mbzp"/><g filter="url(#iArHwac)"><path fill="url(#iiDBOoc)" class="bh47gjbhh"/><path fill="url(#iQd4uud)" class="bh47gjbhh"/><path fill="url(#i7YfCbe)" class="bh47gjbhh"/><path fill="url(#iWvgkIO)" class="bh47gjbhh"/></g><g filter="url(#iCRuLfc)"><path fill="url(#iDGc1Xa)" class="lix5yybsf"/><path fill="url(#iwUi2id)" class="lix5yybsf"/><path fill="url(#iVWgjsc)" class="lix5yybsf"/><path fill="url(#i0JCkkx)" class="lix5yybsf"/></g><path fill="url(#iJ31End)" class="pwd5dvbsq"/><path fill="url(#iJU3TUb)" class="pwd5dvbsq"/><path fill="url(#ix9BQnc)" class="pwd5dvbsq"/><path clip-rule="evenodd" class="dkap42b6k"/><g filter="url(#iVk0Jge)"><path clip-rule="evenodd" class="kuki7z_nz"/></g><path class="r705rkbnv"/><path fill="url(#igLcKKc)" class="sflxmoz4d"/><path fill="url(#icJhVBc)" class="mq57ysmcs"/><ellipse fill="url(#ihScDWc)" transform="scale(-1 1)rotate(74.61 -11.764 -.022)" class="l--rvobkj"/><g filter="url(#i6c6vmd)"><path fill="url(#itczuDR)" class="ufejb-byd"/></g><g filter="url(#iox4RGe)"><path fill="url(#i6rIl5d)" class="ojcov_btr"/><path fill="url(#ivdhPAc)" class="ojcov_btr"/></g><g filter="url(#iRHEpUX)"><path class="n7_r_obfk"/><path fill="url(#i2lXewj)" class="y_3eji5af"/></g><g filter="url(#iISBAwd)"><path class="xnb0a4bnu"/><path fill="url(#iKccX5c)" class="jv7q47bif"/><path fill="url(#im9OVLc)" class="jv7q47bif"/></g><g filter="url(#i2IhBZd)"><circle fill="url(#iRexAge)" class="yzi2v60pl"/><circle fill="url(#iBIGF5U)" class="yzi2v60pl"/></g><g filter="url(#i5dRkIe)"><path fill="url(#iMvfgbc)" clip-rule="evenodd" class="o0-on2bdg"/></g><rect fill="url(#i9HZAie)" transform="scale(-1 1)rotate(45 -41.287 -13.074)" class="hrxlqmt6c"/><rect fill="url(#iwL7NEd)" transform="scale(-1 1)rotate(45 -41.287 -13.074)" class="hrxlqmt6c"/><rect fill="url(#i0csxTc)" transform="scale(-1 1)rotate(45 -41.287 -13.074)" class="hrxlqmt6c"/><rect transform="rotate(45 11.782 25.365)" class="c-ms0dq1b"/><rect fill="url(#i9Q7TNg)" transform="rotate(45 11.782 25.365)" class="ds0v_tl4r"/><rect fill="url(#i7kajTw)" transform="rotate(45 11.782 25.365)" class="ds0v_tl4r"/><g filter="url(#ia4Ebnc)"><path fill="url(#iDU2Kzb)" class="r2ntrrblt"/></g><path fill="url(#ibgQKHl)" class="r2ntrrblt"/><path fill="url(#ipY2Bqc)" class="r2ntrrblt"/><g filter="url(#ibyi4sb)"><rect fill="url(#i3GpgEb)" class="v6ymu42gc"/><rect fill="url(#iIQ7Due)" class="v6ymu42gc"/></g><rect fill="url(#i9Og5Bb)" class="v6ymu42gc"/><g filter="url(#iilqA5d)"><path stroke="url(#iMfo6ub)" class="xcd1inbkf"/></g><g filter="url(#is3JHrP)"><path stroke="url(#ilUuA7b)" class="k1dzkgluc"/></g><path fill="url(#iYIHqTd)" class="i_tqe2j8y"/><path fill="url(#iuw6Ucc)" class="i_tqe2j8y"/><defs><radialGradient id="iMdm93b" cx="0" cy="0" r="1" gradientTransform="rotate(101.587 .81 9.779)scale(.68061 .9607)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="n304-r4kd"/><stop offset=".684" class="uk3jx7nau"/></radialGradient><radialGradient id="iQd4uud" cx="0" cy="0" r="1" gradientTransform="matrix(.63615 -.84975 1.03601 .7756 6.918 13.906)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="jijo4-b9s"/><stop offset="1" class="ni_rkbnps"/></radialGradient><radialGradient id="i7YfCbe" cx="0" cy="0" r="1" gradientTransform="rotate(-140 7.398 4.146)scale(6.51616 1.76643)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="dd9hd6bwg"/><stop offset="1" class="aw2d6h33n"/></radialGradient><radialGradient id="iWvgkIO" cx="0" cy="0" r="1" gradientTransform="matrix(.37588 .3154 -.49187 .5862 8.633 11.953)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="jynvl5b3k"/><stop offset="1" class="b-jom1b0d"/></radialGradient><radialGradient id="iDGc1Xa" cx="0" cy="0" r="1" gradientTransform="rotate(168.984 2.747 6.482)scale(3.88943 5.91263)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="my1ob8bzv"/><stop offset="1" class="eys4t1u9r"/></radialGradient><radialGradient id="iwUi2id" cx="0" cy="0" r="1" gradientTransform="rotate(166.088 2.984 4.889)scale(1.86596 3.00198)" gradientUnits="userSpaceOnUse"><stop class="bd_cirbzn"/><stop offset="1" class="u8iayhb4j"/></radialGradient><radialGradient id="iVWgjsc" cx="0" cy="0" r="1" gradientTransform="matrix(.56547 -.38383 .18859 .27784 6.37 16.268)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="e4cf86x4h"/><stop offset="1" class="dar5wrbvj"/></radialGradient><radialGradient id="i0JCkkx" cx="0" cy="0" r="1" gradientTransform="matrix(-.9221 .68668 -1.83988 -2.47063 6.507 13.205)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="iJ31End" cx="0" cy="0" r="1" gradientTransform="matrix(-.78962 .52882 -.25811 -.3854 6.986 13.597)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="iJU3TUb" cx="0" cy="0" r="1" gradientTransform="rotate(50.843 -10.742 13.71)scale(1.50885 1.57229)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="igLcKKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.22078 .26311 -.5112 -.42894 8.898 11.691)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="icJhVBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.20186 .24056 -.5206 -.43683 9.054 11.547)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="i6rIl5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.09375 .5802 0 20.802 15.15)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="uz40eif1s"/><stop offset="1" class="nn8i0jfly"/></radialGradient><radialGradient id="ivdhPAc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49998 -3.09376 1.67378 -.81152 23.521 14.713)" gradientUnits="userSpaceOnUse"><stop class="w0sb0vrwy"/><stop offset="1" class="p7g900bdp"/></radialGradient><radialGradient id="i2lXewj" cx="0" cy="0" r="1" gradientTransform="rotate(-45.372 16.754 -19.196)scale(6.80605 3.84932)" gradientUnits="userSpaceOnUse"><stop class="xy0op_eyz"/><stop offset="1" class="p53pr-blg"/></radialGradient><radialGradient id="iKccX5c" cx="0" cy="0" r="1" gradientTransform="rotate(-150.994 14.7 4.713)scale(3.60894 4.34333)" gradientUnits="userSpaceOnUse"><stop class="v7qdu5boj"/><stop offset="1" class="kdd3vfboh"/></radialGradient><radialGradient id="im9OVLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 2.625 -1.48498 .60106 19.49 13.838)" gradientUnits="userSpaceOnUse"><stop class="xwt5g5sto"/><stop offset="1" class="x484pmbxx"/></radialGradient><radialGradient id="iRexAge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90038 -2.5625 2.1013 -1.55835 20.752 15.874)" gradientUnits="userSpaceOnUse"><stop class="nmlj7qb8u"/><stop offset="1" class="wijlc3r_o"/></radialGradient><radialGradient id="iBIGF5U" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 -2.34375 2.00586 1.12328 16.845 16.405)" gradientUnits="userSpaceOnUse"><stop class="n35yqc9wi"/><stop offset="1" class="e9nymn0gr"/></radialGradient><radialGradient id="iMvfgbc" cx="0" cy="0" r="1" gradientTransform="rotate(-138.668 11.43 4.377)scale(4.20282 3.66642)" gradientUnits="userSpaceOnUse"><stop class="fgfvt8_za"/><stop offset="1" class="kb1q69u9p"/></radialGradient><radialGradient id="iwL7NEd" cx="0" cy="0" r="1" gradientTransform="rotate(79.16 -.565 1.44)scale(1.58615 1.72717)" gradientUnits="userSpaceOnUse"><stop class="lkqdv0bwp"/><stop offset="1" class="vou8iltko"/></radialGradient><radialGradient id="i0csxTc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.442 2.4 1.929)scale(1.40065 .72809)" gradientUnits="userSpaceOnUse"><stop class="go679fbfb"/><stop offset="1" class="jo92-ub-i"/></radialGradient><radialGradient id="i7kajTw" cx="0" cy="0" r="1" gradientTransform="rotate(-47.663 40.378 1.499)scale(.6726 1.0441)" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></radialGradient><radialGradient id="iDU2Kzb" cx="0" cy="0" r="1" gradientTransform="matrix(-15.56247 -.06247 .03888 -9.68481 25.99 22.307)" gradientUnits="userSpaceOnUse"><stop class="vn7ncpb8d"/><stop offset="1" class="htcu-gvqd"/></radialGradient><radialGradient id="ibgQKHl" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -39.1562 0 17.115 19.37)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="mh1kw6b0u"/><stop offset="1" class="mg_zulb9j"/></radialGradient><radialGradient id="i3GpgEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.25 -15.4957 0 25.24 16.65)" gradientUnits="userSpaceOnUse"><stop class="ypx_bsb1m"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="iMfo6ub" cx="0" cy="0" r="1" gradientTransform="matrix(-6.71874 10.18756 -7.15636 -4.71965 28.771 3.62)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="ilUuA7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -3.53125 2.69792 1.14602 19.539 6.572)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="iYIHqTd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53418 0 0 -3.55867 20.646 8.611)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="yi5996bix"/><stop offset=".717" class="wvcdyrpfm"/></radialGradient><filter id="iArHwac" width="7.79" height="6.597" x="3.983" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.25098 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24057"/></filter><filter id="iCRuLfc" width="5.592" height="8.621" x="2.464" y="8.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0509804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24057"/></filter><filter id="iVk0Jge" width=".814" height="1.199" x="7.141" y="10.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24057"/></filter><filter id="i6c6vmd" width="3.831" height="3.046" x="2.457" y="12.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24057" stdDeviation=".25"/></filter><filter id="iox4RGe" width="7.367" height="4.959" x="17.412" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.321569 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24057"/></filter><filter id="iRHEpUX" width="9.125" height="15.5" x="17.927" y="1.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.501961 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24057"/></filter><filter id="iISBAwd" width="14.805" height="6.438" x="11.177" y="12.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.678431 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24057"/></filter><filter id="i2IhBZd" width="5.582" height="5.582" x="16.06" y="13.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24057" stdDeviation=".25"/></filter><filter id="i5dRkIe" width="6.341" height="6.485" x="11.287" y="12.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24057" stdDeviation=".25"/></filter><filter id="ia4Ebnc" width="28.578" height="11" x="3.771" y="16.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="3" dy="-1"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24057"/></filter><filter id="ibyi4sb" width="28.344" height="2.496" x="2.662" y="15.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.698039 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24057"/></filter><filter id="iilqA5d" width="5.047" height="14.518" x="21.786" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24057" stdDeviation=".25"/></filter><filter id="is3JHrP" width="2.999" height="4.468" x="17.976" y="2.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24057" stdDeviation=".25"/></filter><linearGradient id="iiDBOoc" x1="7.885" x2="10.361" y1="14.204" y2="11.589" gradientUnits="userSpaceOnUse"><stop class="co18c5bwy"/><stop offset="1" class="kj_uw-bok"/></linearGradient><linearGradient id="ix9BQnc" x1="7.103" x2="6.951" y1="13.525" y2="13.859" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="ihScDWc" x1="-.009" x2=".225" y1=".062" y2=".139" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="itczuDR" x1="5.335" x2="2.186" y1="14.574" y2="12.661" gradientUnits="userSpaceOnUse"><stop offset=".421" class="zsttjmk2m"/><stop offset="1" class="vu17sxeyk"/></linearGradient><linearGradient id="i9HZAie" x1="1.641" x2="-.116" y1="2.961" y2="3.171" gradientUnits="userSpaceOnUse"><stop class="t7wbu9b2k"/><stop offset="1" class="t9935ox4b"/></linearGradient><linearGradient id="i9Q7TNg" x1="11.468" x2="13.015" y1="28.867" y2="28.624" gradientUnits="userSpaceOnUse"><stop class="gbuoa-pfp"/><stop offset="1" class="h8mgf7b3a"/></linearGradient><linearGradient id="ipY2Bqc" x1="16.56" x2="16.56" y1="17.807" y2="19.213" gradientUnits="userSpaceOnUse"><stop class="nihdd8-bi"/><stop offset="1" class="x6h_eubpf"/></linearGradient><linearGradient id="iIQ7Due" x1="2.865" x2="12.115" y1="17.244" y2="17.244" gradientUnits="userSpaceOnUse"><stop class="d673tl90q"/><stop offset="1" class="f-q8xrbdi"/></linearGradient><linearGradient id="i9Og5Bb" x1="17.927" x2="17.927" y1="18.154" y2="17.619" gradientUnits="userSpaceOnUse"><stop class="b0b_4h8fx"/><stop offset="1" class="vngbibvro"/></linearGradient><linearGradient id="iuw6Ucc" x1="19.412" x2="19.412" y1="8.611" y2="8.104" gradientUnits="userSpaceOnUse"><stop class="dcrtohb5r"/><stop offset="1" class="k3-gog70w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-taking-bath-medium-dark" /></template>
<style>
.aw2d6h33n {
  stop-color: var(--svg-color--9a7468, #9A7468);
  stop-opacity: 0;
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b-jom1b0d {
  stop-color: var(--svg-color--845a4e, #845A4E);
  stop-opacity: 0;
}

.b0b_4h8fx {
  stop-color: var(--svg-color--b1a1c2, #B1A1C2);
}

.bd_cirbzn {
  stop-color: var(--svg-color--514342, #514342);
}

.bh47gjbhh {
  d: path("M8.787 10.314c-.802-.61-1.383-.672-1.59-.646L4.183 13.26l2.994 2.614c2.741.88 4.964-1.592 4.545-2.592s-2.006-2.262-2.935-2.968");
}

.brjpzuruh {
  stop-color: var(--svg-color--88828e, #88828E);
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.c-ms0dq1b {
  width: 1.608px;
  height: 5.132px;
  x: 11.782px;
  y: 25.365px;
  fill: var(--svg-color--735f86, #735F86);
  rx: 0.804px;
}

.co18c5bwy {
  stop-color: var(--svg-color--825756, #825756);
}

.d673tl90q {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
}

.dar5wrbvj {
  stop-color: var(--svg-color--3f3438, #3F3438);
  stop-opacity: 0;
}

.dcrtohb5r {
  stop-color: var(--svg-color--807f86, #807F86);
}

.dd9hd6bwg {
  stop-color: var(--svg-color--9d726c, #9D726C);
}

.dkap42b6k {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M9.612 13.059c.008.086.085.15.171.14c.417-.04.753-.323.852-.42a.157.157 0 1 0-.219-.224c-.084.082-.355.302-.663.332a.157.157 0 0 0-.141.172");
}

.ds0v_tl4r {
  width: 1.608px;
  height: 5.132px;
  x: 11.782px;
  y: 25.365px;
  rx: 0.804px;
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e4cf86x4h {
  stop-color: var(--svg-color--3f3438, #3F3438);
}

.e9nymn0gr {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
  stop-opacity: 0;
}

.ea_rhjb1f {
  stop-color: var(--svg-color--88828e, #88828E);
  stop-opacity: 0;
}

.eys4t1u9r {
  stop-color: var(--svg-color--3d2d32, #3D2D32);
}

.f-q8xrbdi {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
  stop-opacity: 0;
}

.f6t-uxb_c {
  fill: var(--svg-color--6a4f4d, #6A4F4D);
  d: path("m8.3 15.656l1.423-1.033l1.332 1.832l-1.422 1.033z");
}

.fgfvt8_za {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
}

.ft5dv1b6b {
  fill: none;
}

.gbuoa-pfp {
  stop-color: var(--svg-color--807d83, #807D83);
}

.go679fbfb {
  stop-color: var(--svg-color--bebac2, #BEBAC2);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h8mgf7b3a {
  stop-color: var(--svg-color--807d83, #807D83);
  stop-opacity: 0;
}

.hrxlqmt6c {
  width: 1.608px;
  height: 5.132px;
  rx: 0.804px;
}

.htcu-gvqd {
  stop-color: var(--svg-color--c7bdd3, #C7BDD3);
}

.i_tqe2j8y {
  d: path("M21.091 8.611c.28 0 .509-.23.457-.504c-.25-1.307-1.37-2.293-2.714-2.293c-1.345 0-2.465.986-2.715 2.293c-.052.274.177.504.457.504z");
}

.jijo4-b9s {
  stop-color: var(--svg-color--794b40, #794B40);
}

.jo92-ub-i {
  stop-color: var(--svg-color--968da0, #968DA0);
  stop-opacity: 0;
}

.jv7q47bif {
  d: path("M14.396 19.432a3.22 3.22 0 0 0 2.706-1.475a2.5 2.5 0 0 0 1.657.615c.66 0 1.256-.245 1.687-.64c.511.615 1.402 1.023 2.415 1.023c1.585 0 2.87-.998 2.87-2.23c0-1.051-1.285-2.23-2.87-2.23c-.79 0-1.504.247-2.023.647a.107.107 0 0 1-.15-.019c-.431-.546-1.134-.902-1.929-.902a2.5 2.5 0 0 0-1.417.428a.107.107 0 0 1-.152-.035a3.219 3.219 0 1 0-2.794 4.818");
}

.jynvl5b3k {
  stop-color: var(--svg-color--845a4e, #845A4E);
}

.k1dzkgluc {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.226 3.385c-.458.406-1.375 1.612-1.375 3.187");
}

.k3-gog70w {
  stop-color: var(--svg-color--8f9198, #8F9198);
  stop-opacity: 0;
}

.kb1q69u9p {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
  stop-opacity: 0;
}

.kdd3vfboh {
  stop-color: var(--svg-color--66ebff, #66EBFF);
  stop-opacity: 0;
}

.kj_uw-bok {
  stop-color: var(--svg-color--875d51, #875D51);
}

.kuki7z_nz {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M7.734 11.102a1 1 0 0 1 .16-.222a.188.188 0 1 0-.256-.276a1.3 1.3 0 0 0-.234.317c-.078.143-.15.328-.163.532a.188.188 0 0 0 .376.024a.9.9 0 0 1 .117-.376");
}

.l--rvobkj {
  rx: 0.081px;
  ry: 0.11px;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lix5yybsf {
  d: path("M6.402 8.56a1.285 1.285 0 0 0-1.351.48c-.65.864-.458 1.217-1.24 1.836c-.826.654-1.106 1.083-1.237 1.55l-.002.009c-.128.46-.394 1.413 1.018 2.598c1.3 1.09 2.376 1.203 2.81 1.185l-.021.057c-.107.29.053.582.343.688c.248.091.56-.058.766-.401c.237-.393.403-.687.53-.92a.31.31 0 0 0-.073-.388l-1.071-.899c-.451-.378-.454-.923-.416-1.13c-.453-.406-.548-.729-.465-1.057c.137-.542.33-.585 1.048-1.554c.723-.976.187-1.848-.64-2.055");
}

.lkqdv0bwp {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
}

.mg_zulb9j {
  stop-color: var(--svg-color--a887c7, #A887C7);
}

.mh1kw6b0u {
  stop-color: var(--svg-color--bba9cd, #BBA9CD);
  stop-opacity: 0;
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.mq57ysmcs {
  d: path("M8.811 11.837a1 1 0 0 1-.073-.055c-.178-.15-.26-.347-.181-.44c.078-.094.286-.048.465.102q.036.03.066.062z");
}

.my1ob8bzv {
  stop-color: var(--svg-color--301f27, #301F27);
}

.n304-r4kd {
  stop-color: var(--svg-color--9e746b, #9E746B);
}

.n35yqc9wi {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
}

.n7_r_obfk {
  fill: var(--svg-color--adadad, #ADADAD);
  d: path("M24.952 6.182v10.937h1.6V6.182a4.312 4.312 0 1 0-8.625 0v1.03h1.6v-1.03a2.713 2.713 0 0 1 5.425 0");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ni_rkbnps {
  stop-color: var(--svg-color--794b40, #794B40);
  stop-opacity: 0;
}

.nihdd8-bi {
  stop-color: var(--svg-color--a090b0, #A090B0);
}

.nmlj7qb8u {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
}

.nn8i0jfly {
  stop-color: var(--svg-color--7c5a50, #7C5A50);
}

.o0-on2bdg {
  fill-rule: evenodd;
  d: path("M17.128 15.157a2.32 2.32 0 0 0-.632 2.79a2.742 2.742 0 1 1 .631-2.789");
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.ojcov_btr {
  d: path("M18.502 13.578a2.288 2.288 0 0 1 4.215-.309l1.812 3.6h-7.117z");
}

.p_197nrym {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
  stop-opacity: 0;
}

.p53pr-blg {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
  stop-opacity: 0;
}

.p7g900bdp {
  stop-color: var(--svg-color--8e706a, #8E706A);
  stop-opacity: 0;
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.pryz6mbzp {
  d: path("M9.896 10.877a1.26 1.26 0 0 1-.648-.121l-.145.173l1.082.908c.305-.096.533-.41.409-.663c-.106-.217-.364-.337-.698-.297");
}

.pwd5dvbsq {
  d: path("m7.95 14.154l-1.547-.97a.913.913 0 0 0 1.547.97");
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.r2ntrrblt {
  d: path("m5.227 22.376l-1.456-4.57h25.578l-1.477 4.59a7.8 7.8 0 0 1-7.425 5.41h-7.788a7.8 7.8 0 0 1-7.432-5.43");
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.r705rkbnv {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.143 11.442l-.798.95c-.377-.315-.504-.784-.284-1.047s.705-.22 1.082.097");
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.sflxmoz4d {
  d: path("m8.654 12.025l-.004-.004c-.308-.258-.447-.6-.31-.763c.136-.163.497-.085.805.173l.004.003z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t7wbu9b2k {
  stop-color: var(--svg-color--887a96, #887A96);
}

.t9935ox4b {
  stop-color: var(--svg-color--a9a6ac, #A9A6AC);
}

.u8iayhb4j {
  stop-color: var(--svg-color--514342, #514342);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ufejb-byd {
  d: path("M4.548 13.257a17 17 0 0 0 1.24 1.495a3.64 3.64 0 0 1-2.55-.618c-.52-.354-.264-1.165.335-1.358c.432-.139.707.114.975.481");
}

.uk3jx7nau {
  stop-color: var(--svg-color--8a5752, #8A5752);
}

.uz40eif1s {
  stop-color: var(--svg-color--76515a, #76515A);
}

.v6ymu42gc {
  width: 27.844px;
  height: 2.246px;
  x: 2.662px;
  y: 15.908px;
  rx: 1.123px;
}

.v7qdu5boj {
  stop-color: var(--svg-color--66ebff, #66EBFF);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vn7ncpb8d {
  stop-color: var(--svg-color--e1daea, #E1DAEA);
}

.vngbibvro {
  stop-color: var(--svg-color--bbb2c3, #BBB2C3);
  stop-opacity: 0;
}

.vou8iltko {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
  stop-opacity: 0;
}

.vu17sxeyk {
  stop-color: var(--svg-color--403337, #403337);
  stop-opacity: 0;
}

.w0sb0vrwy {
  stop-color: var(--svg-color--8e706a, #8E706A);
}

.wijlc3r_o {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
  stop-opacity: 0;
}

.wvcdyrpfm {
  stop-color: var(--svg-color--929192, #929192);
}

.x484pmbxx {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
  stop-opacity: 0;
}

.x6h_eubpf {
  stop-color: var(--svg-color--bcb0c8, #BCB0C8);
  stop-opacity: 0;
}

.xcd1inbkf {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M22.302 2.666c1.219-.052 3.657.94 3.657 3.766v9.375");
}

.xnb0a4bnu {
  fill: var(--svg-color--4bd1f1, #4BD1F1);
  d: path("M14.396 19.432a3.22 3.22 0 0 0 2.706-1.475a2.5 2.5 0 0 0 1.657.615c.66 0 1.256-.245 1.687-.64c.511.615 1.402 1.023 2.415 1.023c1.585 0 2.87-.998 2.87-2.23c0-1.051-1.285-2.23-2.87-2.23c-.79 0-1.504.247-2.023.647a.107.107 0 0 1-.15-.019c-.431-.546-1.134-.902-1.929-.902a2.5 2.5 0 0 0-1.417.428a.107.107 0 0 1-.152-.035a3.219 3.219 0 1 0-2.794 4.818");
}

.xwt5g5sto {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
}

.xy0op_eyz {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
}

.y_3eji5af {
  d: path("M24.952 6.182v10.937h1.6V6.182a4.312 4.312 0 1 0-8.625 0v1.03h1.6v-1.03a2.713 2.713 0 0 1 5.425 0");
}

.yi5996bix {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
}

.ypx_bsb1m {
  stop-color: var(--svg-color--fefcff, #FEFCFF);
}

.yzi2v60pl {
  cx: 18.851px;
  cy: 16.73px;
  r: 2.291px;
}

.zsttjmk2m {
  stop-color: var(--svg-color--403337, #403337);
}

</style>
