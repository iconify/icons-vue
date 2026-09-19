<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ijOCl2c)" class="ck3t74vmm"/><path fill="url(#iIhM5NH)" class="ck3t74vmm"/><path fill="url(#iDvfgad)" class="ck3t74vmm"/><g filter="url(#iei4FRm)"><path class="h3ojjx9ln"/></g><g filter="url(#iP38xgd)"><path fill="url(#iMvUvfU)" class="cdzsq9ijv"/><path fill="url(#iOSyZGb)" class="cdzsq9ijv"/><path fill="url(#iXYAihb)" class="cdzsq9ijv"/></g><path fill="url(#ikFsWzc)" class="cdzsq9ijv"/><path fill="url(#iaYkCFb)" class="u3wudo3aw"/><path fill="url(#ij9wnTc)" class="u3wudo3aw"/><path fill="url(#iheFcNb)" class="u3wudo3aw"/><path fill="url(#ijkMNDe)" class="u3wudo3aw"/><path fill="url(#iPElSkc)" class="u3wudo3aw"/><g filter="url(#iDshvMc)"><path fill="url(#irAKJGd)" class="ud1y3fb8c"/><path fill="url(#ivJg1Kb)" class="ud1y3fb8c"/><path fill="url(#i4dF0Ed)" class="ud1y3fb8c"/><path fill="url(#ifgbISb)" class="ud1y3fb8c"/><path fill="url(#ipPGxAb)" class="ud1y3fb8c"/><path fill="url(#inyMCJY)" class="ud1y3fb8c"/><path fill="url(#iriNjhc)" class="ud1y3fb8c"/><path fill="url(#inUhkdd)" class="ud1y3fb8c"/><path fill="url(#iN1iaHd)" class="ud1y3fb8c"/></g><g filter="url(#iuRo6xc)"><path class="p40_-bbkh"/></g><g filter="url(#ipKKchb)"><path class="f9j9f-beh"/><path fill="url(#iQsKAqd)" class="me9_ukbyy"/><path fill="url(#ix44nzd)" class="me9_ukbyy"/><path fill="url(#i3FvKbe)" class="me9_ukbyy"/><path fill="url(#iRJu7Nd)" class="me9_ukbyy"/></g><g filter="url(#iFncnde)"><path stroke="url(#iiLulKd)" class="t22so4e-i"/></g><path class="wosmnub9c"/><g filter="url(#i7xYSfb)"><path class="ncle-i6gw"/></g><g filter="url(#iSPhFme)"><path class="c0intva2d"/></g><g filter="url(#iGZT1Rc)"><path class="mm1mlmbrr"/></g><g filter="url(#i138q3U)"><path clip-rule="evenodd" class="i-m8c8bpf"/></g><path class="wlwkhobtb"/><path fill="url(#i69Thde)" class="y4c3mbb7q"/><path class="d1pgleb_c"/><g filter="url(#iZmK3Bc)"><path class="n-rhjzb7i"/><path fill="url(#ipF5gnd)" class="im0qnzw9i"/></g><g filter="url(#imbbhad)"><path fill="url(#i9qhC2d)" class="w8swczbws"/></g><path class="mhvjalq4x"/><path fill="url(#ify7HVj)" class="i464sabgc"/><path class="w05epcjbm"/><g filter="url(#iMnKqed)"><path fill="url(#iXMTdqd)" class="rd99adqso"/></g><g filter="url(#iIzbm8c)"><ellipse transform="rotate(-27.914 13.465 10.565)" class="iezg297eb"/><ellipse fill="url(#iK2qNsb)" transform="rotate(-27.914 13.465 10.565)" class="oiyjo0bvt"/></g><g filter="url(#iZ3tgFd)"><path class="fadzbbbmm"/></g><g filter="url(#i26wFHe)"><path class="ue2oxlben"/></g><g filter="url(#iDUpA4d)"><path fill="url(#iA1S3Oe)" clip-rule="evenodd" class="t66wd7hki"/></g><path fill="url(#isRo9iX)" clip-rule="evenodd" class="t66wd7hki"/><path fill="url(#iT6Zd0b)" clip-rule="evenodd" class="t66wd7hki"/><path fill="url(#iFRyUYd)" clip-rule="evenodd" class="t66wd7hki"/><path fill="url(#iXavMEb)" clip-rule="evenodd" class="t66wd7hki"/><path fill="url(#ig7cTOb)" clip-rule="evenodd" class="t66wd7hki"/><defs><radialGradient id="ijOCl2c" cx="0" cy="0" r="1" gradientTransform="matrix(-15.56254 13.4375 -17.37186 -20.1191 23.88 18.239)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="c-m2-db1r"/><stop offset="1" class="lpw_68bsr"/></radialGradient><radialGradient id="iIhM5NH" cx="0" cy="0" r="1" gradientTransform="rotate(136.874 7.068 16.588)scale(6.07995 6.11994)" gradientUnits="userSpaceOnUse"><stop class="wdm8my4jl"/><stop offset="1" class="au_4blbid"/></radialGradient><radialGradient id="iMvUvfU" cx="0" cy="0" r="1" gradientTransform="matrix(-8.48286 0 0 -9.81298 19.285 23.52)" gradientUnits="userSpaceOnUse"><stop class="prklqobcj"/><stop offset="1" class="ym6mqqctl"/></radialGradient><radialGradient id="iOSyZGb" cx="0" cy="0" r="1" gradientTransform="matrix(-12.58516 -5.40493 4.87536 -11.35207 18.377 28.833)" gradientUnits="userSpaceOnUse"><stop offset=".79" class="zl0gbcrkw"/><stop offset="1" class="rqdnlobox"/></radialGradient><radialGradient id="iXYAihb" cx="0" cy="0" r="1" gradientTransform="matrix(-.96657 6.43064 -6.40563 -.96281 15.181 16.702)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="zhscqlbpv"/><stop offset="1" class="hr18vydyp"/></radialGradient><radialGradient id="ikFsWzc" cx="0" cy="0" r="1" gradientTransform="matrix(10.03122 6.84374 -7.53953 11.05108 9.88 16.707)" gradientUnits="userSpaceOnUse"><stop offset=".972" class="j3anwzjna"/><stop offset=".991" class="y61txublo"/></radialGradient><radialGradient id="ij9wnTc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.99999 3.96877 -1.22204 -1.53957 20.535 16.989)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="n1775ub4r"/><stop offset="1" class="yh-1r4-sb"/></radialGradient><radialGradient id="iheFcNb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.3178 2.71017 -3.76393 -8.7743 17.228 16.591)" gradientUnits="userSpaceOnUse"><stop offset=".694" class="ln5rrnnhq"/><stop offset=".928" class="zvy0gs06n"/></radialGradient><radialGradient id="ijkMNDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.81395 -5.55482 0 15.109 17.713)" gradientUnits="userSpaceOnUse"><stop offset=".498" class="g2b227i-s"/><stop offset="1" class="ul9foxw2y"/></radialGradient><radialGradient id="iPElSkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.86218 -8.36853 0 16.004 15.8)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="ryrd9sb2y"/><stop offset="1" class="lesk0hb6s"/></radialGradient><radialGradient id="irAKJGd" cx="0" cy="0" r="1" gradientTransform="rotate(155.462 8.304 7.422)scale(7.4735 9.938)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="ivJg1Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1288 1.00465 -.6952 -1.4731 17.861 11.597)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="i4dF0Ed" cx="0" cy="0" r="1" gradientTransform="matrix(1.12216 -3.5975 4.6024 1.43562 13.673 17.745)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="ifgbISb" cx="0" cy="0" r="1" gradientTransform="rotate(96.794 3.424 12.776)scale(7.08729 7.19499)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="ipPGxAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.79628 -6.90148 0 15.678 11.129)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="inyMCJY" cx="0" cy="0" r="1" gradientTransform="rotate(169.005 8.32 7.117)scale(7.35382 12.544)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iriNjhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.19097 1.47636 0 18.357 10.292)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="inUhkdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.35836 1.57245 0 13.78 10.056)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iN1iaHd" cx="0" cy="0" r="1" gradientTransform="rotate(123.986 7.361 8.094)scale(3.35425 3.08102)" gradientUnits="userSpaceOnUse"><stop class="kte15q61f"/><stop offset="1" class="mltae6b_k"/></radialGradient><radialGradient id="iQsKAqd" cx="0" cy="0" r="1" gradientTransform="rotate(-105.014 13.235 -.158)scale(2.78915 .85959)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iRJu7Nd" cx="0" cy="0" r="1" gradientTransform="matrix(-.80663 0 0 -.2255 16.568 12.803)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="i69Thde" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83965 -1.33556 0 18.263 10.663)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ipF5gnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.24002 -.3093 .42582 -.33045 18.026 10.75)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ify7HVj" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83966 -1.33557 0 13.746 10.663)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iK2qNsb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.086 -1.175)scale(.51138 .6147)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iA1S3Oe" cx="0" cy="0" r="1" gradientTransform="rotate(121.679 8.075 8.491)scale(12.0506 10.0996)" gradientUnits="userSpaceOnUse"><stop class="qgb64vbcc"/><stop offset="1" class="qifif4biz"/></radialGradient><radialGradient id="iT6Zd0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.7879 -8.79851 0 15.98 8.638)" gradientUnits="userSpaceOnUse"><stop class="al4q6ffpx"/><stop offset=".866" class="thcs-obed"/><stop offset="1" class="x8eb2zbkq"/></radialGradient><radialGradient id="iFRyUYd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.65397 -9.37048 9.62948 -5.81025 17.124 12.45)" gradientUnits="userSpaceOnUse"><stop offset=".758" class="xhimsmknu"/><stop offset=".994" class="fuwrw2b5h"/></radialGradient><radialGradient id="iXavMEb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.79524 3.2082 -9.93816 -8.65893 21.761 3.27)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="p40y9dbky"/><stop offset="1" class="msi-dpmal"/></radialGradient><filter id="iei4FRm" width="16.584" height="15.121" x="5.243" y="13.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3296" stdDeviation=".125"/></filter><filter id="iP38xgd" width="16.502" height="15.01" x="5.145" y="13.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.317647 0 0 0 0 0.745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3296"/></filter><filter id="iDshvMc" width="10.328" height="11.96" x="10.808" y="5.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3296"/></filter><filter id="iuRo6xc" width="2.943" height="3.775" x="14.365" y="10.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3296" stdDeviation=".25"/></filter><filter id="ipKKchb" width="2.443" height="3.275" x="14.783" y="10.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3296" stdDeviation=".125"/></filter><filter id="iFncnde" width="3.818" height="1.565" x="14.095" y="13.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3296" stdDeviation=".05"/></filter><filter id="i7xYSfb" width="3.099" height="1.33" x="16.986" y="9.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3296"/></filter><filter id="iSPhFme" width="3.099" height="1.33" x="11.923" y="9.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3296"/></filter><filter id="iGZT1Rc" width="2.531" height="1.122" x="12.063" y="8.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3296"/></filter><filter id="i138q3U" width="2.531" height="1.122" x="17.67" y="8.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3296"/></filter><filter id="iZmK3Bc" width=".807" height=".714" x="17.506" y="10.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3296" stdDeviation=".05"/></filter><filter id="imbbhad" width=".908" height=".931" x="18.379" y="10.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3296" stdDeviation=".1"/></filter><filter id="iMnKqed" width="1.006" height="1.062" x="13.781" y="10.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3296" stdDeviation=".1"/></filter><filter id="iIzbm8c" width=".938" height=".722" x="12.996" y="10.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3296" stdDeviation=".05"/></filter><filter id="iZ3tgFd" width="2.519" height="1.191" x="17.611" y="8.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3296" stdDeviation=".1"/></filter><filter id="i26wFHe" width="2.519" height="1.191" x="11.97" y="8.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3296" stdDeviation=".1"/></filter><filter id="iDUpA4d" width="15.212" height="17.812" x="8.549" y="1.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.258824 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3296"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.196078 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3296" result="effect2_innerShadow_4002_3296"/></filter><linearGradient id="iDvfgad" x1="5.561" x2="7.848" y1="29.986" y2="29.986" gradientUnits="userSpaceOnUse"><stop class="fozhrdxgd"/><stop offset="1" class="fnmmfsrpm"/></linearGradient><linearGradient id="iaYkCFb" x1="20.567" x2="12.504" y1="17.52" y2="20.926" gradientUnits="userSpaceOnUse"><stop class="vow0ojb4t"/><stop offset="1" class="lem83lbgo"/></linearGradient><linearGradient id="ix44nzd" x1="15.033" x2="16.004" y1="12.659" y2="12.659" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="i3FvKbe" x1="16.004" x2="16.004" y1="13.486" y2="12.855" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iiLulKd" x1="14.903" x2="15.38" y1="14.945" y2="14.208" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="i9qhC2d" x1="19.067" x2="18.743" y1="10.719" y2="10.919" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXMTdqd" x1="14.515" x2="14.191" y1="10.719" y2="10.919" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isRo9iX" x1="23.261" x2="21.888" y1="12.609" y2="12.609" gradientUnits="userSpaceOnUse"><stop class="g7b7vvs6b"/><stop offset="1" class="tcqkmtb2a"/></linearGradient><linearGradient id="ig7cTOb" x1="8.699" x2="10.294" y1="11.656" y2="11.592" gradientUnits="userSpaceOnUse"><stop class="wqzdbcbqv"/><stop offset="1" class="ikg8w-bhe"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-headscarf-dark" /></template>
<style>
.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.al4q6ffpx {
  stop-color: var(--svg-color--573199, #573199);
  stop-opacity: 0;
}

.au_4blbid {
  stop-color: var(--svg-color--7866a7, #7866A7);
  stop-opacity: 0;
}

.c-m2-db1r {
  stop-color: var(--svg-color--6e5d9b, #6E5D9B);
}

.c0intva2d {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.823 10.693c-.275-.483-.693-.865-1.591-.865c-.394 0-.773.109-1.11.382c-.279.224-.242.512-.026.62l.575.328c.675-.218 1.42-.247 2.152-.465");
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.cdzsq9ijv {
  d: path("M5.246 27.237a.1.1 0 0 0 .053.105c1.552.777 3.232 1.154 5.086 1.154c5.455 0 10.083-3.927 11.26-9.023a.1.1 0 0 0-.047-.107c-.9-.536-1.833-1.022-2.88-1.276c-.32-.08-.663-.134-.663-.464v-1.98c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v1.98c0 .33-.21.451-.53.531c-4.28 1.131-7.373 4.149-8.16 9.08");
}

.ck3t74vmm {
  d: path("M18.552 18.093a.715.715 0 0 1-.531-.703v-2.016c0-1.16-.905-2.097-2.026-2.097s-2.025.936-2.025 2.097v2.016a.715.715 0 0 1-.531.703c-4.73 1.191-8.24 5.61-8.24 10.875v1.018H26.8v-1.018c0-5.264-3.51-9.684-8.25-10.875");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d1pgleb_c {
  fill: var(--svg-color--000, #000);
  d: path("M17.736 11.094c0-.294.235-.53.529-.53a.527.527 0 0 1 .47.773h-.936a.5.5 0 0 1-.063-.243");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.f9j9f-beh {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.609 10.908l-.55 1.76a.558.558 0 0 0 .538.723h.814a.56.56 0 0 0 .539-.724l-.55-1.76c-.118-.389-.668-.389-.791 0");
}

.fadzbbbmm {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.012 8.826c.333-.081 1.163-.04 1.718.356");
}

.fnmmfsrpm {
  stop-color: var(--svg-color--655b83, #655B83);
  stop-opacity: 0;
}

.fozhrdxgd {
  stop-color: var(--svg-color--655b83, #655B83);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.fuwrw2b5h {
  stop-color: var(--svg-color--7358a4, #7358A4);
}

.g2b227i-s {
  stop-color: var(--svg-color--452686, #452686);
}

.g7b7vvs6b {
  stop-color: var(--svg-color--906ccf, #906CCF);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.h3ojjx9ln {
  fill: var(--svg-color--514575, #514575);
  d: path("M5.494 27.245a.1.1 0 0 0 .053.104c1.522.763 3.168 1.132 4.986 1.132c5.349 0 9.887-3.85 11.04-8.847a.1.1 0 0 0-.045-.107c-.883-.525-1.797-1.001-2.822-1.25c-.314-.079-.652-.132-.652-.455V15.88c0-1.118-.902-2.02-2.02-2.02s-2.02.902-2.02 2.02v1.942c0 .323-.205.442-.519.52c-4.197 1.11-7.23 4.068-8 8.903");
}

.hr18vydyp {
  stop-color: var(--svg-color--4f2e93, #4F2E93);
  stop-opacity: 0;
}

.i-m8c8bpf {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.866 8.968l-.142.238za.278.278 0 0 1-.285.476l-.005-.003a2 2 0 0 0-.117-.06a3 3 0 0 0-.354-.14a2.35 2.35 0 0 0-1.11-.095a.277.277 0 1 1-.096-.547a2.9 2.9 0 0 1 1.375.113a3.4 3.4 0 0 1 .578.247l.01.006l.003.002z");
}

.i464sabgc {
  d: path("M13.744 10.17a.924.924 0 0 0-.89 1.167h1.784a1 1 0 0 0 .034-.244a.93.93 0 0 0-.928-.923");
}

.iezg297eb {
  cx: 13.465px;
  cy: 10.565px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.403px;
  ry: 0.204px;
}

.ikg8w-bhe {
  stop-color: var(--svg-color--755da5, #755DA5);
  stop-opacity: 0;
}

.im0qnzw9i {
  d: path("M18.197 10.365c.066.088-.072.195-.228.312s-.273.2-.339.112c-.065-.088.008-.255.165-.372c.156-.117.336-.14.402-.052");
}

.j3anwzjna {
  stop-color: var(--svg-color--9c7ada, #9C7ADA);
  stop-opacity: 0;
}

.kte15q61f {
  stop-color: var(--svg-color--625352, #625352);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lem83lbgo {
  stop-color: var(--svg-color--60429a, #60429A);
}

.lesk0hb6s {
  stop-color: var(--svg-color--5c35a2, #5C35A2);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln5rrnnhq {
  stop-color: var(--svg-color--755fa4, #755FA4);
  stop-opacity: 0;
}

.lpw_68bsr {
  stop-color: var(--svg-color--534082, #534082);
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me9_ukbyy {
  d: path("m15.609 10.908l-.55 1.76a.558.558 0 0 0 .538.723h.814a.56.56 0 0 0 .539-.724l-.55-1.76c-.118-.389-.668-.389-.791 0");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mhvjalq4x {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.53 9.888c-.676 0-1.247.466-1.402 1.096a.284.284 0 0 0 .277.353h2.309a.238.238 0 0 0 .235-.281a1.45 1.45 0 0 0-1.42-1.168");
}

.mltae6b_k {
  stop-color: var(--svg-color--625352, #625352);
  stop-opacity: 0;
}

.mm1mlmbrr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.488 9.441l-.005.003a.278.278 0 0 1-.285-.476l.002-.001l.003-.002l.01-.006a2 2 0 0 1 .153-.08a4 4 0 0 1 .425-.167a2.9 2.9 0 0 1 1.374-.113a.278.278 0 0 1-.096.547a2.35 2.35 0 0 0-1.11.095a3 3 0 0 0-.47.2");
}

.msi-dpmal {
  stop-color: var(--svg-color--a27ce3, #A27CE3);
  stop-opacity: 0;
}

.n-rhjzb7i {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.197 10.365c.066.088-.072.195-.228.312s-.273.2-.339.112c-.065-.088.008-.255.165-.372c.156-.117.336-.14.402-.052");
}

.n1775ub4r {
  stop-color: var(--svg-color--9376cc, #9376CC);
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.ncle-i6gw {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.186 10.693c.275-.483.692-.865 1.591-.865c.394 0 .773.109 1.11.382c.279.224.241.512.026.62l-.576.328c-.674-.218-1.42-.247-2.15-.465");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oiyjo0bvt {
  cx: 13.465px;
  cy: 10.565px;
  rx: 0.403px;
  ry: 0.204px;
}

.p40_-bbkh {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.598 11.05l-.708 1.76a.558.558 0 0 0 .54.724h.813a.56.56 0 0 0 .539-.724l-.55-1.76c-.118-.389-.51-.389-.634 0");
}

.p40y9dbky {
  stop-color: var(--svg-color--a27ce3, #A27CE3);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prklqobcj {
  stop-color: var(--svg-color--8e6bd1, #8E6BD1);
}

.qgb64vbcc {
  stop-color: var(--svg-color--9670d7, #9670D7);
}

.qifif4biz {
  stop-color: var(--svg-color--7454ac, #7454AC);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rd99adqso {
  d: path("M14.587 10.984c0-.298-.242-.496-.308-.556l-.298.288l.183.373z");
}

.rqdnlobox {
  stop-color: var(--svg-color--7a65a5, #7A65A5);
}

.ryrd9sb2y {
  stop-color: var(--svg-color--5c35a2, #5C35A2);
  stop-opacity: 0;
}

.t22so4e-i {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.004 14.295c-.539 0-1.045-.13-1.47-.357c-.146-.076-.303.092-.211.227a2 2 0 0 0 3.363 0c.091-.14-.065-.303-.21-.227a3.1 3.1 0 0 1-1.472.357Z");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t66wd7hki {
  fill-rule: evenodd;
  d: path("M10.114 4.208c2.911-2.928 8.816-2.925 11.732.007c1.235 1.39 1.415 2.897 1.415 4.125c0 .836-.055 2.784-.086 3.68c-.086 3.713-2.68 7.25-7.195 7.406c-5.39 0-7.137-4.914-7.195-7.414c-.032-.896-.086-2.844-.086-3.68c0-1.227.18-2.734 1.415-4.124m4.678 1.909a2 2 0 0 1 2.36 0l3.164 2.312a2 2 0 0 1 .82 1.614v2.235a5.164 5.164 0 1 1-10.328 0v-2.235a2 2 0 0 1 .82-1.614z");
}

.tcqkmtb2a {
  stop-color: var(--svg-color--906ccf, #906CCF);
  stop-opacity: 0;
}

.thcs-obed {
  stop-color: var(--svg-color--573199, #573199);
  stop-opacity: 0.024;
}

.u3wudo3aw {
  d: path("M16.004 22.441a5.85 5.85 0 1 0 0-11.7a5.85 5.85 0 0 0 0 11.7");
}

.ud1y3fb8c {
  d: path("M17.152 6.116a2 2 0 0 0-2.36 0l-3.164 2.312a2 2 0 0 0-.82 1.615v2.235a5.164 5.164 0 0 0 10.328 0v-2.235a2 2 0 0 0-.82-1.615z");
}

.ue2oxlben {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.088 8.826c-.333-.081-1.164-.04-1.718.356");
}

.ul9foxw2y {
  stop-color: var(--svg-color--452686, #452686);
  stop-opacity: 0;
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vow0ojb4t {
  stop-color: var(--svg-color--8966c9, #8966C9);
}

.w05epcjbm {
  fill: var(--svg-color--000, #000);
  d: path("M14.273 11.094a.527.527 0 0 0-.53-.53a.527.527 0 0 0-.47.773h.937a.5.5 0 0 0 .063-.243");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w8swczbws {
  d: path("M19.087 10.971a.87.87 0 0 0-.24-.478l-.268.295l.121.236z");
}

.wdm8my4jl {
  stop-color: var(--svg-color--8570b8, #8570B8);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wlwkhobtb {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.479 9.888c.676 0 1.247.466 1.402 1.096a.284.284 0 0 1-.277.353h-2.31a.238.238 0 0 1-.234-.281a1.45 1.45 0 0 1 1.419-1.168");
}

.wosmnub9c {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M16.004 14.295c-.539 0-1.045-.13-1.47-.357c-.146-.076-.303.092-.211.227a2 2 0 0 0 3.363 0c.091-.14-.065-.303-.21-.227a3.1 3.1 0 0 1-1.472.357");
}

.wqzdbcbqv {
  stop-color: var(--svg-color--755da5, #755DA5);
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.x8eb2zbkq {
  stop-color: var(--svg-color--573199, #573199);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xhimsmknu {
  stop-color: var(--svg-color--7358a4, #7358A4);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.y4c3mbb7q {
  d: path("M18.265 10.17a.924.924 0 0 1 .89 1.167H17.37a.927.927 0 0 1 .894-1.167");
}

.y61txublo {
  stop-color: var(--svg-color--9c7ada, #9C7ADA);
}

.yh-1r4-sb {
  stop-color: var(--svg-color--9376cc, #9376CC);
  stop-opacity: 0;
}

.ym6mqqctl {
  stop-color: var(--svg-color--7050ad, #7050AD);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zhscqlbpv {
  stop-color: var(--svg-color--4f2e93, #4F2E93);
}

.zl0gbcrkw {
  stop-color: var(--svg-color--7a65a5, #7A65A5);
  stop-opacity: 0;
}

.zvy0gs06n {
  stop-color: var(--svg-color--755fa4, #755FA4);
}

</style>
