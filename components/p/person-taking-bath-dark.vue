<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="odofupbzk"/><path fill="url(#ikv6SJc)" class="ch21772fr"/><g filter="url(#iMGVwyd)"><path fill="url(#i69BOyd)" class="iyfew-amo"/><path fill="url(#iTJfTQd)" class="iyfew-amo"/><path fill="url(#iNUAYMW)" class="iyfew-amo"/><path fill="url(#iM54oJb)" class="iyfew-amo"/></g><g filter="url(#iMJY2Me)"><path fill="url(#i1RbfXq)" class="c6hmvtb8u"/><path fill="url(#i7ryksd)" class="c6hmvtb8u"/><path fill="url(#ifg5wXd)" class="c6hmvtb8u"/><path fill="url(#iQdPxqb)" class="c6hmvtb8u"/></g><path fill="url(#iKgri9k)" class="n-9-9xbap"/><path fill="url(#i4tOIWC)" class="n-9-9xbap"/><path clip-rule="evenodd" class="xwb9fibix"/><g filter="url(#iQdzIpE)"><path clip-rule="evenodd" class="vd8-vvzqb"/></g><path class="y2gie2bdd"/><path fill="url(#inqrKvl)" class="b-fe0ebyg"/><path fill="url(#i3sq68d)" class="haj4hhrii"/><ellipse fill="url(#ihScDWc)" transform="scale(-1 1)rotate(74.61 -11.764 -.023)" class="l--rvobkj"/><g filter="url(#i0VAwAe)"><path fill="url(#i24KtOc)" class="ro99wwbpt"/></g><g filter="url(#ivzx1Ab)"><path fill="url(#iGLLFdd)" class="ojcov_btr"/><path fill="url(#iL1pZBd)" class="ojcov_btr"/></g><g filter="url(#i9r3BVc)"><path class="jj9rrl77z"/><path fill="url(#i2lXewj)" class="xqsefibpe"/></g><g filter="url(#inpQzud)"><path class="k-6rydbde"/><path fill="url(#iKccX5c)" class="y6291zrey"/><path fill="url(#im9OVLc)" class="y6291zrey"/></g><g filter="url(#iz6uhCe)"><circle fill="url(#iRexAge)" class="yzi2v60pl"/><circle fill="url(#iBIGF5U)" class="yzi2v60pl"/></g><g filter="url(#iA14F9c)"><path fill="url(#iEVJ3Kd)" clip-rule="evenodd" class="jco-mipgp"/></g><rect fill="url(#i9HZAie)" transform="scale(-1 1)rotate(45 -41.287 -13.074)" class="hrxlqmt6c"/><rect fill="url(#iwL7NEd)" transform="scale(-1 1)rotate(45 -41.287 -13.074)" class="hrxlqmt6c"/><rect fill="url(#i0csxTc)" transform="scale(-1 1)rotate(45 -41.287 -13.074)" class="hrxlqmt6c"/><rect transform="rotate(45 11.782 25.365)" class="c-ms0dq1b"/><rect fill="url(#i9Q7TNg)" transform="rotate(45 11.782 25.365)" class="ds0v_tl4r"/><rect fill="url(#i7kajTw)" transform="rotate(45 11.782 25.365)" class="ds0v_tl4r"/><g filter="url(#iT6fOye)"><path fill="url(#iDU2Kzb)" class="u8oucg9le"/></g><path fill="url(#ibgQKHl)" class="u8oucg9le"/><path fill="url(#ipY2Bqc)" class="u8oucg9le"/><g filter="url(#iqLM3ib)"><rect fill="url(#i3GpgEb)" class="v6ymu42gc"/><rect fill="url(#iIQ7Due)" class="v6ymu42gc"/></g><rect fill="url(#i9Og5Bb)" class="v6ymu42gc"/><g filter="url(#izdSXLb)"><path stroke="url(#iMfo6ub)" class="bckrz6b7j"/></g><g filter="url(#iiIaB3X)"><path stroke="url(#ilUuA7b)" class="k1dzkgluc"/></g><path fill="url(#iYIHqTd)" class="tzkieubpv"/><path fill="url(#iuw6Ucc)" class="tzkieubpv"/><defs><radialGradient id="ikv6SJc" cx="0" cy="0" r="1" gradientTransform="rotate(101.587 .81 9.779)scale(.68063 .96072)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="iTJfTQd" cx="0" cy="0" r="1" gradientTransform="matrix(.63617 -.84977 1.03604 .77562 6.918 13.906)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="iNUAYMW" cx="0" cy="0" r="1" gradientTransform="matrix(-4.99181 -4.18863 1.13547 -1.3532 10.4 12.078)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="iM54oJb" cx="0" cy="0" r="1" gradientTransform="matrix(.37589 .3154 -.49189 .5862 8.634 11.953)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="i1RbfXq" cx="0" cy="0" r="1" gradientTransform="rotate(168.984 2.747 6.482)scale(3.88954 5.91281)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="i7ryksd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81128 .44865 -.7218 -2.914 7.056 8.917)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="ifg5wXd" cx="0" cy="0" r="1" gradientTransform="matrix(.56549 -.38384 .1886 .27785 6.37 16.268)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="iQdPxqb" cx="0" cy="0" r="1" gradientTransform="rotate(143.325 1.065 7.68)scale(1.14972 3.08054)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="iKgri9k" cx="0" cy="0" r="1" gradientTransform="matrix(-.78964 .52884 -.25812 -.38541 6.987 13.595)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="inqrKvl" cx="0" cy="0" r="1" gradientTransform="matrix(-.22079 .26312 -.51121 -.42896 8.898 11.691)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i3sq68d" cx="0" cy="0" r="1" gradientTransform="matrix(-.20186 .24057 -.52061 -.43684 9.055 11.548)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iGLLFdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.09375 .5802 0 20.802 15.15)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="cfzp3sqdk"/><stop offset="1" class="z0pwqv32w"/></radialGradient><radialGradient id="iL1pZBd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49998 -3.09376 1.67378 -.81152 23.521 14.713)" gradientUnits="userSpaceOnUse"><stop class="m4lxhitum"/><stop offset="1" class="d2g3bwbfz"/></radialGradient><radialGradient id="i2lXewj" cx="0" cy="0" r="1" gradientTransform="rotate(-45.372 16.754 -19.196)scale(6.80605 3.84932)" gradientUnits="userSpaceOnUse"><stop class="xy0op_eyz"/><stop offset="1" class="p53pr-blg"/></radialGradient><radialGradient id="iKccX5c" cx="0" cy="0" r="1" gradientTransform="rotate(-150.994 14.7 4.713)scale(3.60894 4.34333)" gradientUnits="userSpaceOnUse"><stop class="v7qdu5boj"/><stop offset="1" class="kdd3vfboh"/></radialGradient><radialGradient id="im9OVLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 2.625 -1.48498 .60106 19.49 13.838)" gradientUnits="userSpaceOnUse"><stop class="xwt5g5sto"/><stop offset="1" class="x484pmbxx"/></radialGradient><radialGradient id="iRexAge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90038 -2.5625 2.1013 -1.55835 20.752 15.874)" gradientUnits="userSpaceOnUse"><stop class="nmlj7qb8u"/><stop offset="1" class="wijlc3r_o"/></radialGradient><radialGradient id="iBIGF5U" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 -2.34375 2.00586 1.12328 16.845 16.405)" gradientUnits="userSpaceOnUse"><stop class="n35yqc9wi"/><stop offset="1" class="e9nymn0gr"/></radialGradient><radialGradient id="iEVJ3Kd" cx="0" cy="0" r="1" gradientTransform="rotate(-138.668 11.431 4.377)scale(4.20282 3.66642)" gradientUnits="userSpaceOnUse"><stop class="fgfvt8_za"/><stop offset="1" class="kb1q69u9p"/></radialGradient><radialGradient id="iwL7NEd" cx="0" cy="0" r="1" gradientTransform="rotate(79.16 -.565 1.44)scale(1.58615 1.72717)" gradientUnits="userSpaceOnUse"><stop class="lkqdv0bwp"/><stop offset="1" class="vou8iltko"/></radialGradient><radialGradient id="i0csxTc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.442 2.4 1.929)scale(1.40065 .72809)" gradientUnits="userSpaceOnUse"><stop class="go679fbfb"/><stop offset="1" class="jo92-ub-i"/></radialGradient><radialGradient id="i7kajTw" cx="0" cy="0" r="1" gradientTransform="rotate(-47.663 40.378 1.499)scale(.6726 1.0441)" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></radialGradient><radialGradient id="iDU2Kzb" cx="0" cy="0" r="1" gradientTransform="matrix(-15.56247 -.06247 .03888 -9.68481 25.99 22.307)" gradientUnits="userSpaceOnUse"><stop class="vn7ncpb8d"/><stop offset="1" class="htcu-gvqd"/></radialGradient><radialGradient id="ibgQKHl" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -39.1562 0 17.115 19.37)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="mh1kw6b0u"/><stop offset="1" class="mg_zulb9j"/></radialGradient><radialGradient id="i3GpgEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.25 -15.4957 0 25.24 16.65)" gradientUnits="userSpaceOnUse"><stop class="ypx_bsb1m"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="iMfo6ub" cx="0" cy="0" r="1" gradientTransform="matrix(-6.71874 10.18756 -7.15636 -4.71965 28.771 3.62)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="ilUuA7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -3.53125 2.69792 1.14602 19.539 6.572)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="iYIHqTd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53418 0 0 -3.55867 20.646 8.611)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="yi5996bix"/><stop offset=".717" class="wvcdyrpfm"/></radialGradient><filter id="iMGVwyd" width="7.79" height="6.597" x="3.983" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.172549 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24056"/></filter><filter id="iMJY2Me" width="5.592" height="8.622" x="2.465" y="8.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24056"/></filter><filter id="iQdzIpE" width=".814" height="1.199" x="7.141" y="10.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24056"/></filter><filter id="i0VAwAe" width="3.831" height="3.046" x="2.457" y="12.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24056" stdDeviation=".25"/></filter><filter id="ivzx1Ab" width="7.367" height="4.959" x="17.412" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.215686 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24056"/></filter><filter id="i9r3BVc" width="9.125" height="15.5" x="17.927" y="1.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.501961 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24056"/></filter><filter id="inpQzud" width="14.805" height="6.438" x="11.177" y="12.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.678431 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24056"/></filter><filter id="iz6uhCe" width="5.582" height="5.582" x="16.06" y="13.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24056" stdDeviation=".25"/></filter><filter id="iA14F9c" width="6.341" height="6.485" x="11.287" y="12.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24056" stdDeviation=".25"/></filter><filter id="iT6fOye" width="28.578" height="11" x="3.771" y="16.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="3" dy="-1"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24056"/></filter><filter id="iqLM3ib" width="28.344" height="2.496" x="2.662" y="15.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.698039 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24056"/></filter><filter id="izdSXLb" width="5.047" height="14.518" x="21.786" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24056" stdDeviation=".25"/></filter><filter id="iiIaB3X" width="2.999" height="4.468" x="17.976" y="2.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24056" stdDeviation=".25"/></filter><linearGradient id="i69BOyd" x1="7.885" x2="10.361" y1="14.204" y2="11.589" gradientUnits="userSpaceOnUse"><stop class="bmcblacal"/><stop offset="1" class="d0kv1cyul"/></linearGradient><linearGradient id="i4tOIWC" x1="7.079" x2="7.003" y1="13.615" y2="13.736" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="ihScDWc" x1="-.009" x2=".225" y1=".062" y2=".139" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="i24KtOc" x1="5.335" x2="2.187" y1="14.574" y2="12.661" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><linearGradient id="i9HZAie" x1="1.641" x2="-.116" y1="2.961" y2="3.171" gradientUnits="userSpaceOnUse"><stop class="t7wbu9b2k"/><stop offset="1" class="t9935ox4b"/></linearGradient><linearGradient id="i9Q7TNg" x1="11.468" x2="13.015" y1="28.867" y2="28.624" gradientUnits="userSpaceOnUse"><stop class="gbuoa-pfp"/><stop offset="1" class="h8mgf7b3a"/></linearGradient><linearGradient id="ipY2Bqc" x1="16.56" x2="16.56" y1="17.807" y2="19.213" gradientUnits="userSpaceOnUse"><stop class="nihdd8-bi"/><stop offset="1" class="x6h_eubpf"/></linearGradient><linearGradient id="iIQ7Due" x1="2.865" x2="12.115" y1="17.244" y2="17.244" gradientUnits="userSpaceOnUse"><stop class="d673tl90q"/><stop offset="1" class="f-q8xrbdi"/></linearGradient><linearGradient id="i9Og5Bb" x1="17.927" x2="17.927" y1="18.154" y2="17.619" gradientUnits="userSpaceOnUse"><stop class="b0b_4h8fx"/><stop offset="1" class="vngbibvro"/></linearGradient><linearGradient id="iuw6Ucc" x1="19.412" x2="19.412" y1="8.611" y2="8.104" gradientUnits="userSpaceOnUse"><stop class="dcrtohb5r"/><stop offset="1" class="k3-gog70w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-taking-bath-dark" /></template>
<style>
.b-fe0ebyg {
  d: path("m8.654 12.025l-.004-.004c-.308-.258-.447-.6-.31-.763c.136-.163.497-.085.805.173l.004.004z");
}

.b0b_4h8fx {
  stop-color: var(--svg-color--b1a1c2, #B1A1C2);
}

.bckrz6b7j {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M22.302 2.666c1.22-.052 3.657.94 3.657 3.766v9.375");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.brjpzuruh {
  stop-color: var(--svg-color--88828e, #88828E);
}

.c-ms0dq1b {
  width: 1.608px;
  height: 5.132px;
  x: 11.782px;
  y: 25.365px;
  fill: var(--svg-color--735f86, #735F86);
  rx: 0.804px;
}

.c6hmvtb8u {
  d: path("M6.402 8.56a1.29 1.29 0 0 0-1.351.48c-.65.864-.458 1.217-1.24 1.836c-.826.654-1.106 1.083-1.236 1.55l-.003.009c-.128.46-.394 1.413 1.018 2.598c1.3 1.091 2.376 1.204 2.81 1.185l-.021.058c-.107.29.053.58.344.687c.247.091.559-.058.765-.401c.237-.392.403-.686.53-.92a.31.31 0 0 0-.073-.388l-1.07-.899c-.452-.378-.454-.922-.417-1.13c-.453-.406-.548-.729-.465-1.056c.137-.543.33-.586 1.048-1.555c.723-.976.187-1.848-.64-2.055");
}

.cfzp3sqdk {
  stop-color: var(--svg-color--402e31, #402E31);
}

.ch21772fr {
  d: path("M9.896 10.877a1.26 1.26 0 0 1-.648-.121l-.145.173l1.082.908c.305-.096.533-.41.41-.663c-.107-.217-.365-.337-.7-.297");
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.d0kv1cyul {
  stop-color: var(--svg-color--5b4542, #5B4542);
}

.d2g3bwbfz {
  stop-color: var(--svg-color--5e4f4e, #5E4F4E);
  stop-opacity: 0;
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.d673tl90q {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
}

.dcrtohb5r {
  stop-color: var(--svg-color--807f86, #807F86);
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

.e9nymn0gr {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
  stop-opacity: 0;
}

.ea_rhjb1f {
  stop-color: var(--svg-color--88828e, #88828E);
  stop-opacity: 0;
}

.f-q8xrbdi {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
  stop-opacity: 0;
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
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

.h-bh2_bpf {
  stop-color: var(--svg-color--454143, #454143);
}

.h8mgf7b3a {
  stop-color: var(--svg-color--807d83, #807D83);
  stop-opacity: 0;
}

.haj4hhrii {
  d: path("M8.811 11.837a1 1 0 0 1-.073-.055c-.178-.15-.26-.347-.181-.44c.078-.093.287-.048.465.102q.036.03.066.062z");
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.hrxlqmt6c {
  width: 1.608px;
  height: 5.132px;
  rx: 0.804px;
}

.htcu-gvqd {
  stop-color: var(--svg-color--c7bdd3, #C7BDD3);
}

.iyfew-amo {
  d: path("M8.788 10.314c-.803-.61-1.384-.672-1.591-.646L4.183 13.26l2.994 2.614c2.742.88 4.965-1.592 4.545-2.592s-2.006-2.262-2.934-2.968");
}

.jco-mipgp {
  fill-rule: evenodd;
  d: path("M17.128 15.157a2.32 2.32 0 0 0-.631 2.789a2.742 2.742 0 1 1 .631-2.789");
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jj9rrl77z {
  fill: var(--svg-color--adadad, #ADADAD);
  d: path("M24.952 6.182v10.937h1.6V6.182a4.313 4.313 0 0 0-8.625 0v1.03h1.6v-1.03a2.712 2.712 0 1 1 5.425 0");
}

.jo92-ub-i {
  stop-color: var(--svg-color--968da0, #968DA0);
  stop-opacity: 0;
}

.k-6rydbde {
  fill: var(--svg-color--4bd1f1, #4BD1F1);
  d: path("M14.396 19.432a3.22 3.22 0 0 0 2.706-1.475a2.5 2.5 0 0 0 1.657.615c.66 0 1.256-.245 1.687-.64c.511.615 1.402 1.023 2.415 1.023c1.585 0 2.871-.998 2.871-2.23c0-1.051-1.286-2.23-2.871-2.23c-.79 0-1.504.247-2.023.647a.107.107 0 0 1-.15-.019c-.431-.546-1.134-.902-1.929-.902c-.53 0-1.02.159-1.417.428a.107.107 0 0 1-.152-.035a3.219 3.219 0 1 0-2.794 4.818");
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

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
}

.l--rvobkj {
  rx: 0.081px;
  ry: 0.11px;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lkqdv0bwp {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.m4lxhitum {
  stop-color: var(--svg-color--5e4f4e, #5E4F4E);
}

.mg_zulb9j {
  stop-color: var(--svg-color--a887c7, #A887C7);
}

.mh1kw6b0u {
  stop-color: var(--svg-color--bba9cd, #BBA9CD);
  stop-opacity: 0;
}

.n-9-9xbap {
  d: path("m7.95 14.154l-1.546-.97a.913.913 0 0 0 1.546.97");
}

.n35yqc9wi {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nihdd8-bi {
  stop-color: var(--svg-color--a090b0, #A090B0);
}

.nmlj7qb8u {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.odofupbzk {
  fill: var(--svg-color--3e3434, #3E3434);
  d: path("m8.3 15.656l1.423-1.033l1.332 1.832l-1.422 1.033z");
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

.pf-fc7btu {
  stop-color: var(--svg-color--454143, #454143);
  stop-opacity: 0;
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.ro99wwbpt {
  d: path("M4.549 13.257c.486.663.998 1.243 1.24 1.495a3.64 3.64 0 0 1-2.551-.618c-.52-.354-.264-1.165.335-1.357c.433-.14.707.114.976.48");
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
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

.tzkieubpv {
  d: path("M21.092 8.611c.279 0 .508-.23.456-.504c-.25-1.307-1.37-2.293-2.714-2.293c-1.345 0-2.465.986-2.715 2.293c-.052.274.178.504.457.504z");
}

.u8oucg9le {
  d: path("m5.227 22.376l-1.456-4.57H29.35l-1.477 4.59a7.8 7.8 0 0 1-7.425 5.41H12.66a7.8 7.8 0 0 1-7.432-5.43");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uysgu56cq {
  stop-color: var(--svg-color--48302c, #48302C);
}

.v23x_cgsr {
  stop-color: var(--svg-color--482c2e, #482C2E);
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

.vd8-vvzqb {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M7.735 11.102a1 1 0 0 1 .16-.222a.188.188 0 0 0-.257-.276a1.3 1.3 0 0 0-.234.317c-.078.143-.15.328-.163.532a.188.188 0 1 0 .376.024a.9.9 0 0 1 .118-.375");
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
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

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.wijlc3r_o {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
  stop-opacity: 0;
}

.wvcdyrpfm {
  stop-color: var(--svg-color--929192, #929192);
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.x484pmbxx {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
  stop-opacity: 0;
}

.x6h_eubpf {
  stop-color: var(--svg-color--bcb0c8, #BCB0C8);
  stop-opacity: 0;
}

.xktf9pbat {
  stop-color: var(--svg-color--564c49, #564C49);
  stop-opacity: 0;
}

.xqsefibpe {
  d: path("M24.952 6.182v10.937h1.6V6.182a4.313 4.313 0 0 0-8.625 0v1.03h1.6v-1.03a2.712 2.712 0 1 1 5.425 0");
}

.xwb9fibix {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M9.612 13.059c.009.086.086.15.172.14c.417-.04.752-.323.852-.419a.157.157 0 1 0-.219-.225c-.085.082-.355.302-.663.332a.157.157 0 0 0-.142.172");
}

.xwt5g5sto {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
}

.xy0op_eyz {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
}

.y2gie2bdd {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.143 11.442l-.798.95c-.377-.315-.504-.784-.283-1.047c.22-.263.704-.22 1.08.097");
}

.y6291zrey {
  d: path("M14.396 19.432a3.22 3.22 0 0 0 2.706-1.475a2.5 2.5 0 0 0 1.657.615c.66 0 1.256-.245 1.687-.64c.511.615 1.402 1.023 2.415 1.023c1.585 0 2.871-.998 2.871-2.23c0-1.051-1.286-2.23-2.871-2.23c-.79 0-1.504.247-2.023.647a.107.107 0 0 1-.15-.019c-.431-.546-1.134-.902-1.929-.902c-.53 0-1.02.159-1.417.428a.107.107 0 0 1-.152-.035a3.219 3.219 0 1 0-2.794 4.818");
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

.z0pwqv32w {
  stop-color: var(--svg-color--452f2e, #452F2E);
}

</style>
