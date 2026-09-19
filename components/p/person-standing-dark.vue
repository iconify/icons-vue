<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="vtc-e9n-d"/><path class="at4q51bux"/><g filter="url(#iWs5wZc)"><path class="h5gektbgw"/><path fill="url(#i04lsCd)" class="z23533p_d"/></g><path class="ec6e809pj"/><path fill="url(#i37b3eb)" class="bg_y89dup"/><path class="re73b6xet"/><path fill="url(#iSKzZDe)" class="zzl9q_jda"/><path fill="url(#iYGcJKd)" class="zzl9q_jda"/><path fill="url(#i2bDogb)" class="zzl9q_jda"/><g filter="url(#ikmmoqc)"><path class="imqxb70jo"/></g><path class="qes_hkbxf"/><path fill="url(#iwpA6bd)" class="osx_cvdvg"/><path fill="url(#izQrBVc)" class="osx_cvdvg"/><g filter="url(#ik2qf7c)"><path class="vjpr3ob1d"/></g><path fill="url(#ibWngWb)" class="dq46or42q"/><path fill="url(#iVrANId)" class="dq46or42q"/><path fill="url(#in1TjYd)" class="dq46or42q"/><path fill="url(#i36tcdc)" class="dq46or42q"/><g filter="url(#icRpvTb)"><path fill="url(#iglQ6Fe)" class="io8qqi52v"/><path fill="url(#iotG6Zb)" class="io8qqi52v"/></g><path fill="url(#ix4DtMb)" class="ck6qoaboh"/><g filter="url(#iSYM0ab)"><path class="utjcgnnio"/></g><path fill="url(#iB6Yhfe)" class="tfe_aug3p"/><path fill="url(#iVcvQqc)" class="tfe_aug3p"/><g filter="url(#iCzlyub)"><path class="jxrw3o5te"/></g><path fill="url(#ifCDAVQ)" class="b8lr97w5y"/><path fill="url(#iiXQdzb)" class="zmoflnhgm"/><g filter="url(#iWY8jzd)"><path fill="url(#ivZgMze)" class="rr9h-xcpt"/></g><path fill="url(#iDfusCm)" class="rr9h-xcpt"/><path fill="url(#iknPwob)" class="rr9h-xcpt"/><path fill="url(#i0ecymd)" class="rr9h-xcpt"/><path fill="url(#iP8w4Tb)" class="rr9h-xcpt"/><path fill="url(#i756ReQ)" class="rr9h-xcpt"/><path fill="url(#iOZp5Xk)" class="rr9h-xcpt"/><path fill="url(#iF4Ojld)" class="rr9h-xcpt"/><path fill="url(#iHeR4ob)" class="rr9h-xcpt"/><path fill="url(#ifCyWdb)" class="rr9h-xcpt"/><g filter="url(#iQqsWtm)"><path class="z24qw8r9d"/></g><path class="bk6kzacrv"/><path fill="url(#iavkyGd)" class="gnkev6mug"/><path fill="url(#iqoMSwb)" class="gnkev6mug"/><path fill="url(#iIMiBSd)" class="gnkev6mug"/><path fill="url(#iPAwVNH)" class="gnkev6mug"/><path fill="url(#iSIGOTb)" class="gnkev6mug"/><g filter="url(#iGnSB5P)"><path stroke="url(#ir1NLhc)" class="xb3grpq8z"/></g><path fill="url(#i1OEple)" class="zmwvj69un"/><g filter="url(#iSAqUCb)"><path fill="url(#iTri6ye)" class="ochsfqbqa"/><path fill="url(#i9XCcWd)" class="ochsfqbqa"/><path fill="url(#ieHJOdc)" class="ochsfqbqa"/><path fill="url(#izoCjEe)" class="ochsfqbqa"/><path fill="url(#ikUEzle)" class="ochsfqbqa"/></g><g filter="url(#ienF3qH)"><path class="tt1-v_bmp"/></g><g filter="url(#iqQuCne)"><path class="knghs1bqd"/></g><g filter="url(#iLsFSPv)"><path class="yna4gi_mg"/><path fill="url(#iqsgUBd)" class="qn28_pozx"/><path fill="url(#iuBpQie)" class="qn28_pozx"/></g><g filter="url(#iSZFm1c)"><path class="gkf-77iza"/><path fill="url(#idfTYqb)" class="mqap58bft"/></g><path class="bca6h3crt"/><path fill="url(#iHF4nOe)" class="ltpbs0btu"/><path class="eqcl63bwm"/><g filter="url(#iKa0YlT)"><path class="mt6kztu9a"/><path fill="url(#iVC6TMd)" class="lgf7m9lol"/></g><g filter="url(#iIn3jUc)"><path fill="url(#i0YieUc)" class="fiqf-vbvi"/></g><path class="uffn9sb4e"/><path fill="url(#iQ2hVkd)" class="gz9jp_byg"/><path class="hb9auub6r"/><g filter="url(#i70uEmd)"><path fill="url(#iBX24Jb)" class="opik0i52p"/></g><g filter="url(#iEnNQhd)"><ellipse transform="rotate(-27.914 14.899 5.455)" class="tqgsrbmpz"/><ellipse fill="url(#inVuysb)" transform="rotate(-27.914 14.899 5.455)" class="s2118m3wh"/></g><path fill="url(#iLUrhTc)" class="hgrr3mz7l"/><path fill="url(#iw6J1le)" class="hgrr3mz7l"/><path fill="url(#i7j9MGV)" class="hgrr3mz7l"/><path fill="url(#iSccoSd)" class="hgrr3mz7l"/><path fill="url(#ir9mH8c)" class="kooo24bxd"/><path fill="url(#iICUp5c)" class="kooo24bxd"/><g filter="url(#iH5pfGd)"><path fill="url(#iWCuMvc)" class="urz-1qguo"/></g><g filter="url(#igsP5cc)"><path fill="url(#izPuc0T)" class="i1f5ne5hf"/></g><g filter="url(#iOGcodc)"><path class="tffnktbqq"/></g><g filter="url(#iRgjvMU)"><path class="ntxocsg7q"/></g><g filter="url(#iuYINKb)"><path class="rvxbr74wk"/></g><defs><radialGradient id="i04lsCd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.357 16.63)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="axxfosbfa"/><stop offset="1" class="kwh_vkbqv"/></radialGradient><radialGradient id="i37b3eb" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.872 16.63)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="e2dz_dw5r"/><stop offset="1" class="ei1q8ubqv"/></radialGradient><radialGradient id="iSKzZDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98267 0 0 -3.09375 13.513 12.523)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="cn77rwbmc"/><stop offset="1" class="y2mxoh-zc"/></radialGradient><radialGradient id="iYGcJKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.562 8.832)" gradientUnits="userSpaceOnUse"><stop class="y4_ytjb3b"/><stop offset="1" class="wysngjbll"/></radialGradient><radialGradient id="iwpA6bd" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.3125 1.2963 3.62963 18.794 11.976)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="l7g1kibqg"/><stop offset="1" class="d_gvw4b_b"/></radialGradient><radialGradient id="iVrANId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16 18.101)" gradientUnits="userSpaceOnUse"><stop class="kcjik5o6k"/><stop offset="1" class="j6ndfp4vo"/></radialGradient><radialGradient id="in1TjYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.076 28.465)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="i36tcdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.794 28.554)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iotG6Zb" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.427 8.227)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="mdbsecb0y"/><stop offset="1" class="y-nukfwnq"/></radialGradient><radialGradient id="ix4DtMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.42712 .66406 -.8419 1.8093 15.444 8.873)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="w-40tz9fc"/><stop offset="1" class="wz2zkpbpl"/></radialGradient><radialGradient id="iVcvQqc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.566 29.414)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="ifCDAVQ" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 4.517 16.198)scale(.96684 1.14853)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iiXQdzb" cx="0" cy="0" r="1" gradientTransform="matrix(.66276 .2083 -.6426 2.04466 13.281 6.552)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="ivZgMze" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34669 0 0 -4.15128 17.26 5.91)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iknPwob" cx="0" cy="0" r="1" gradientTransform="matrix(-.45886 5.5767 -4.61817 -.38 16.71 3.255)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="i0ecymd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51548 .6379 0 17.099 5.32)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iP8w4Tb" cx="0" cy="0" r="1" gradientTransform="matrix(.00176 -.4912 .53454 .00192 14.967 5.34)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="i756ReQ" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8137 .24074 -.61497 -9.7421 17.54 6.353)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iOZp5Xk" cx="0" cy="0" r="1" gradientTransform="matrix(1.8283 -1.18877 .43517 .66929 13.546 3.968)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iF4Ojld" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.15 10.716)scale(1.12599 .45011)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iHeR4ob" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.509 6.656)scale(1.51228 1.24851)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iqoMSwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10957 -.34437 0 16.21 6.52)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iPAwVNH" cx="0" cy="0" r="1" gradientTransform="matrix(-.68282 .31307 -.50312 -1.09734 16.262 6.264)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i1OEple" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32353 1.30163 0 16 7.498)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="i9XCcWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.57169 3.97461 0 13.652 4.611)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="ieHJOdc" cx="0" cy="0" r="1" gradientTransform="matrix(.0512 -1.12784 1.9983 .0907 18.182 5.2)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="izoCjEe" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 9.278 -1.48)scale(1.26733 .93028)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="ikUEzle" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.307 14.766)scale(.77682 1.79875)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iqsgUBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.98805 0 0 -.3667 16.114 2.681)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iuBpQie" cx="0" cy="0" r="1" gradientTransform="matrix(1.44458 -2.28726 2.53405 1.60045 13.562 4.45)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="idfTYqb" cx="0" cy="0" r="1" gradientTransform="matrix(1.45807 .17042 -.07135 .61047 16.785 3.73)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iHF4nOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36419 -.57928 0 16.98 5.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iVC6TMd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 9.794 -1.365)scale(.16981 .23378)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQ2hVkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3642 -.57931 0 15.02 5.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="inVuysb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00347 -.22179 .2666 -.00417 14.892 5.596)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iw6J1le" cx="0" cy="0" r="1" gradientTransform="matrix(.28214 1.00697 -.96073 .26918 18.072 5.504)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="i7j9MGV" cx="0" cy="0" r="1" gradientTransform="rotate(-53.92 14.768 -15.05)scale(.60046 .50331)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iSccoSd" cx="0" cy="0" r="1" gradientTransform="matrix(.2635 -.69596 .9299 .35206 18.286 5.826)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iICUp5c" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 4.53 8.386)scale(.95014 .93408)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iWCuMvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4114 .07062 -.03115 -.18145 13.794 5.793)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><filter id="iWs5wZc" width="2.311" height="8.028" x="11.403" y="12.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.278431 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_170"/></filter><filter id="ikmmoqc" width="1.064" height="6.513" x="19.364" y="12.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".15"/></filter><filter id="ik2qf7c" width="6.169" height="12.453" x="13.016" y="16.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.462745 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_170"/></filter><filter id="icRpvTb" width="6.417" height="7.594" x="12.941" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.415686 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_170"/></filter><filter id="iSYM0ab" width="3.316" height="1.848" x="12.434" y="28.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_170"/></filter><filter id="iCzlyub" width="6.594" height="13.766" x="12.841" y="15.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".5"/></filter><filter id="iWY8jzd" width="5.588" height="5.74" x="13.727" y="3.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_170"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_170" result="effect2_innerShadow_4002_170"/></filter><filter id="iQqsWtm" width="2.784" height="3.302" x="14.544" y="4.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".5"/></filter><filter id="iGnSB5P" width="1.745" height=".782" x="15.128" y="6.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".05"/></filter><filter id="iSAqUCb" width="5.778" height="4.027" x="13.111" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_170"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_170" result="effect2_innerShadow_4002_170"/></filter><filter id="ienF3qH" width="1.105" height=".645" x="16.713" y="4.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_170"/></filter><filter id="iqQuCne" width="1.105" height=".638" x="14.354" y="4.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_170"/></filter><filter id="iLsFSPv" width="3.231" height="2.745" x="13.283" y="2.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_170"/><feGaussianBlur result="effect2_foregroundBlur_4002_170" stdDeviation=".05"/></filter><filter id="iSZFm1c" width="2.958" height="2.712" x="15.914" y="2.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_170"/><feGaussianBlur result="effect2_foregroundBlur_4002_170" stdDeviation=".1"/></filter><filter id="iKa0YlT" width=".463" height=".423" x="16.595" y="5.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".05"/></filter><filter id="iIn3jUc" width=".62" height=".63" x="16.917" y="5.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".1"/></filter><filter id="i70uEmd" width=".663" height=".687" x="14.922" y="5.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".1"/></filter><filter id="iEnNQhd" width=".52" height=".427" x="14.639" y="5.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".05"/></filter><filter id="iH5pfGd" width=".872" height="1.344" x="13.133" y="5.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".125"/></filter><filter id="igsP5cc" width="1.425" height="1.854" x="17.719" y="4.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".25"/></filter><filter id="iOGcodc" width="1.043" height=".484" x="14.336" y="4.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".05"/></filter><filter id="iRgjvMU" width="1.043" height=".484" x="16.706" y="4.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".05"/></filter><filter id="iuYINKb" width="2.19" height="1.176" x="16.481" y="2.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_170" stdDeviation=".125"/></filter><linearGradient id="i2bDogb" x1="12.466" x2="12.466" y1="12.781" y2="12.304" gradientUnits="userSpaceOnUse"><stop class="mea8vgbzb"/><stop offset="1" class="x8_6e5b0q"/></linearGradient><linearGradient id="izQrBVc" x1="19.747" x2="19.747" y1="12.867" y2="12.164" gradientUnits="userSpaceOnUse"><stop class="kidhsabwy"/><stop offset="1" class="i08i0qbub"/></linearGradient><linearGradient id="ibWngWb" x1="16" x2="16" y1="16.011" y2="16.445" gradientUnits="userSpaceOnUse"><stop class="sb3cb-bog"/><stop offset="1" class="hpe4_756h"/></linearGradient><linearGradient id="iglQ6Fe" x1="16" x2="16" y1="9.101" y2="16.062" gradientUnits="userSpaceOnUse"><stop class="hrtvttbtf"/><stop offset="1" class="nua72fb5w"/></linearGradient><linearGradient id="iB6Yhfe" x1="18.247" x2="16.5" y1="29.726" y2="29.523" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="iDfusCm" x1="18.315" x2="16.361" y1="6.666" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="ifCyWdb" x1="16.021" x2="16.021" y1="8.716" y2="8.428" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iavkyGd" x1="16.376" x2="16" y1="6.212" y2="6.228" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iIMiBSd" x1="16" x2="16" y1="6.724" y2="6.515" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iSIGOTb" x1="16" x2="16" y1="5.397" y2="5.755" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="ir1NLhc" x1="15.461" x2="15.604" y1="7.429" y2="7.054" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iTri6ye" x1="19.076" x2="13.863" y1="3.367" y2="3.367" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="i0YieUc" x1="17.329" x2="17.188" y1="5.522" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBX24Jb" x1="15.354" x2="15.214" y1="5.522" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLUrhTc" x1="18.889" x2="18.347" y1="5.534" y2="6.511" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="ir9mH8c" x1="13.374" x2="14.029" y1="5.85" y2="5.793" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="izPuc0T" x1="18.431" x2="18.431" y1="5.363" y2="6.217" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-standing-dark" /></template>
<style>
.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.at4q51bux {
  fill: var(--svg-color--3b2828, #3B2828);
  d: path("M19.333 19.16a.22.22 0 0 0 .043-.238h.437l-.32.996c-.262.078-.54.05-.59-.114a.32.32 0 0 1 .074-.3a9 9 0 0 0 .356-.344");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.axxfosbfa {
  stop-color: var(--svg-color--2a1318, #2A1318);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b8lr97w5y {
  d: path("M18.182 6.47a.74.74 0 0 0 .406-.138v.418c0 .4-.239.758-.602.906q.116-.245.156-.53z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bca6h3crt {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.073 5.162c.293 0 .541.202.609.475a.123.123 0 0 1-.12.153H16.56a.103.103 0 0 1-.102-.122a.63.63 0 0 1 .615-.506");
}

.bg_y89dup {
  d: path("M19.888 20.44c.938-1.981.769-6.258.487-7.823h-1.672c.072 2.425-.155 5.253-.293 6.522a.29.29 0 0 0 .554.15l.117-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.062.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.bk6kzacrv {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.828 5.589l-.238.825c-.049.17.068.34.234.34h.353c.165 0 .282-.173.233-.34l-.238-.825c-.051-.183-.29-.183-.344 0");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ck6qoaboh {
  d: path("M15.129 7.375h1.742v1.351a.871.871 0 0 1-1.742 0z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn77rwbmc {
  stop-color: var(--svg-color--f16440, #F16440);
  stop-opacity: 0;
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.d_gvw4b_b {
  stop-color: var(--svg-color--ff391e, #FF391E);
  stop-opacity: 0;
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dq46or42q {
  d: path("m13.016 16.011l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2dz_dw5r {
  stop-color: var(--svg-color--341c1e, #341C1E);
}

.ec6e809pj {
  fill: var(--svg-color--502626, #502626);
  d: path("M19.888 20.44c.938-1.981.769-6.258.487-7.823h-1.672c.072 2.425-.155 5.253-.293 6.522a.29.29 0 0 0 .554.15l.117-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.062.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.ei1q8ubqv {
  stop-color: var(--svg-color--4e2525, #4E2525);
  stop-opacity: 0;
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.eqcl63bwm {
  fill: var(--svg-color--000, #000);
  d: path("M16.75 5.685a.23.23 0 0 1 .23-.23a.228.228 0 0 1 .204.335h-.406a.2.2 0 0 1-.027-.105");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fiqf-vbvi {
  d: path("M17.337 5.632a.4.4 0 0 0-.104-.208l-.116.128l.052.103z");
}

.ft5dv1b6b {
  fill: none;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gkf-77iza {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m18.34 4.855l-.013-.283a.66.66 0 0 0-.631-.64h-.629c-.398 0-.762-.218-.953-.566c0 0 .323-.933.86-.812c.392.088.811.227 1.132.436c.783.511.646 1.431.234 1.865");
}

.gnkev6mug {
  d: path("m15.828 5.589l-.238.825c-.049.17.068.34.234.34h.353c.165 0 .282-.173.233-.34l-.238-.825c-.051-.183-.29-.183-.344 0");
}

.gz9jp_byg {
  d: path("M15.02 5.284a.4.4 0 0 0-.386.506h.774a.403.403 0 0 0-.388-.506");
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h5gektbgw {
  fill: var(--svg-color--412d2d, #412D2D);
  d: path("M12.112 20.44c-.938-1.981-.769-6.258-.487-7.823h1.672c-.072 2.425.039 5.243.177 6.511c.012.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.062.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.hb9auub6r {
  fill: var(--svg-color--000, #000);
  d: path("M15.25 5.685a.23.23 0 0 0-.23-.23a.228.228 0 0 0-.204.335h.406a.2.2 0 0 0 .027-.105");
}

.hgrr3mz7l {
  d: path("M18.21 6.511q.044-.717.082-1.432a.723.723 0 0 1-.083 1.432");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hpe4_756h {
  stop-color: var(--svg-color--856988, #856988);
  stop-opacity: 0;
}

.hrtvttbtf {
  stop-color: var(--svg-color--ff7325, #FF7325);
}

.i08i0qbub {
  stop-color: var(--svg-color--ff381e, #FF381E);
  stop-opacity: 0;
}

.i1f5ne5hf {
  d: path("m18.219 6.217l.05-.854a.429.429 0 0 1-.05.854");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.imqxb70jo {
  stroke: var(--svg-color--583f3f, #583F3F);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.813 12.498c.125 1 .3 3.575 0 5.875");
}

.io8qqi52v {
  d: path("M12.942 11.527a3.059 3.059 0 1 1 6.117 0v4.441a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j6ndfp4vo {
  stop-color: var(--svg-color--6a597b, #6A597B);
  stop-opacity: 0;
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jxrw3o5te {
  fill: var(--svg-color--9d98a2, #9D98A2);
  d: path("m13.84 16.382l.47 11.766h.812v-10.61h2.203v10.61h.672l.438-11.766z");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kcjik5o6k {
  stop-color: var(--svg-color--6a597b, #6A597B);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kidhsabwy {
  stop-color: var(--svg-color--ff381e, #FF381E);
}

.knghs1bqd {
  fill: var(--svg-color--202020, #202020);
  d: path("M14.469 4.523a1.25 1.25 0 0 1 .78-.161a.124.124 0 0 1-.03.247a1 1 0 0 0-.656.149l-.007.005l-.002.001a.125.125 0 0 1-.152-.197z");
}

.kooo24bxd {
  d: path("M13.731 5.075a.722.722 0 0 0 .062 1.436q-.045-.718-.062-1.436");
}

.kwh_vkbqv {
  stop-color: var(--svg-color--2a1318, #2A1318);
  stop-opacity: 0;
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l7g1kibqg {
  stop-color: var(--svg-color--ff391e, #FF391E);
}

.lgf7m9lol {
  d: path("M16.951 5.369c.029.038-.031.084-.099.135c-.068.05-.118.086-.147.048s.004-.11.072-.16s.145-.062.174-.023");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ltpbs0btu {
  d: path("M16.98 5.284a.4.4 0 0 1 .386.506h-.773a.402.402 0 0 1 .388-.506");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdbsecb0y {
  stop-color: var(--svg-color--ff863c, #FF863C);
}

.mea8vgbzb {
  stop-color: var(--svg-color--fb2d18, #FB2D18);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mqap58bft {
  d: path("m18.34 4.855l-.013-.283a.66.66 0 0 0-.631-.64h-.629c-.398 0-.762-.218-.953-.566c0 0 .323-.933.86-.812c.392.088.811.227 1.132.436c.783.511.646 1.431.234 1.865");
}

.mt6kztu9a {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.951 5.369c.029.038-.031.084-.099.135c-.068.05-.118.086-.147.048s.004-.11.072-.16s.145-.062.174-.023");
}

.ntxocsg7q {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.599 4.628a1.04 1.04 0 0 0-.744-.171");
}

.nua72fb5w {
  stop-color: var(--svg-color--ff4c2e, #FF4C2E);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.ochsfqbqa {
  d: path("M18.18 2.927a1.064 1.064 0 0 1 .521 1.606a.7.7 0 0 0-.122.393v.533a.8.8 0 0 0-.3-.12l.036-.721a.65.65 0 0 0-.62-.643h-.628c-.428 0-.816-.253-.992-.648a.3.3 0 0 0-.277-.188h-.571c-.828 0-1.5.68-1.5 1.517l.014.69a.8.8 0 0 0-.323.119v-.54a.7.7 0 0 0-.122-.392a1.07 1.07 0 0 1-.064-1.098c.13-.248.343-.42.583-.505a1.2 1.2 0 0 0 .622-.499a1.044 1.044 0 0 1 1.297-.409a.67.67 0 0 0 .536 0a1.044 1.044 0 0 1 1.302.424c.138.229.355.395.607.481");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.opik0i52p {
  d: path("M15.386 5.637c0-.129-.106-.215-.134-.241l-.13.125l.08.162z");
}

.osx_cvdvg {
  d: path("M20.468 12.66c-.487-2.253-1.629-3.333-3.03-3.828v3.949h2.933a.1.1 0 0 0 .097-.12");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qes_hkbxf {
  fill: var(--svg-color--ff7a43, #FF7A43);
  d: path("M20.468 12.66c-.487-2.253-1.629-3.333-3.03-3.828v3.949h2.933a.1.1 0 0 0 .097-.12");
}

.qn28_pozx {
  d: path("m16.104 3.389l-.03-.062a.3.3 0 0 0-.276-.188h-.57c-.83 0-1.5.68-1.5 1.517v.124c-.153-.117-.345-.362-.345-.758c0-.481.35-.724.574-.88c.064-.043.117-.08.149-.113l.045-.047c.156-.167.436-.463.924-.593q.116-.03.231-.047c.468-.07.808.348.808.821v.22z");
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.re73b6xet {
  fill: var(--svg-color--ff4326, #FF4326);
  d: path("M11.533 12.66c.486-2.253 1.628-3.333 3.03-3.828v3.949H11.63a.1.1 0 0 1-.097-.12");
}

.rr9h-xcpt {
  d: path("M13.834 7.15a1.76 1.76 0 0 0 1.744 1.53h.847c.883 0 1.629-.653 1.744-1.53c.053-.845.107-1.687.146-2.532a.65.65 0 0 0-.62-.643h-.628c-.428 0-.816-.253-.992-.648a.3.3 0 0 0-.276-.188h-.572c-.828 0-1.5.68-1.5 1.517c0 .835.052 1.657.107 2.494");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rvxbr74wk {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M17.882 3.396h-.934a.217.217 0 1 1 .035-.431c.242.039.564.092.78.146c.487.12.621.358.659.527a.68.68 0 0 0-.54-.242");
}

.s2118m3wh {
  cx: 14.899px;
  cy: 5.455px;
  rx: 0.175px;
  ry: 0.089px;
}

.sb3cb-bog {
  stop-color: var(--svg-color--856988, #856988);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.tfe_aug3p {
  d: path("M19.567 29.82v.242H16.5v-1.598h1.992c.102.368.575.754.817.915c.186.123.258.3.258.44");
}

.tffnktbqq {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.486 4.648a1.04 1.04 0 0 1 .743-.17");
}

.tqgsrbmpz {
  cx: 14.899px;
  cy: 5.455px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.175px;
  ry: 0.089px;
}

.tt1-v_bmp {
  fill: var(--svg-color--202020, #202020);
  d: path("M17.676 4.572a.8.8 0 0 0-.31-.185c-.136-.043-.307-.054-.543-.025a.124.124 0 1 0 .03.247c.216-.027.348-.013.44.016a.6.6 0 0 1 .219.135a.124.124 0 1 0 .163-.188");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.uffn9sb4e {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.927 5.162a.63.63 0 0 0-.608.475c-.02.078.04.153.12.153h1.002a.103.103 0 0 0 .101-.122a.63.63 0 0 0-.615-.506");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.urz-1qguo {
  d: path("M13.717 5.371a.429.429 0 0 0 .038.844a35 35 0 0 1-.038-.844");
}

.utjcgnnio {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.434 29.82v.242H15.5v-1.598h-1.992c-.102.368-.574.754-.816.915a.54.54 0 0 0-.258.44");
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vjpr3ob1d {
  fill: var(--svg-color--827a8a, #827A8A);
  d: path("m13.016 16.011l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.vtc-e9n-d {
  fill: var(--svg-color--2b151c, #2B151C);
  d: path("M12.668 19.16a.22.22 0 0 1-.043-.238h-.438l.32.996c.262.078.54.05.59-.114a.32.32 0 0 0-.074-.3a9 9 0 0 1-.355-.344");
}

.w-40tz9fc {
  stop-color: var(--svg-color--3b1f1f, #3B1F1F);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.wysngjbll {
  stop-color: var(--svg-color--de5d25, #DE5D25);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.wz2zkpbpl {
  stop-color: var(--svg-color--5e332c, #5E332C);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.x8_6e5b0q {
  stop-color: var(--svg-color--fb2d18, #FB2D18);
  stop-opacity: 0;
}

.xb3grpq8z {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16 7.21c-.228 0-.442-.054-.622-.148c-.061-.031-.127.038-.089.094a.85.85 0 0 0 .711.38a.85.85 0 0 0 .71-.38c.04-.058-.027-.125-.088-.094A1.34 1.34 0 0 1 16 7.21Z");
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.y-nukfwnq {
  stop-color: var(--svg-color--ff863c, #FF863C);
  stop-opacity: 0;
}

.y2mxoh-zc {
  stop-color: var(--svg-color--f16440, #F16440);
}

.y4_ytjb3b {
  stop-color: var(--svg-color--de5d25, #DE5D25);
}

.yna4gi_mg {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.104 3.389l-.03-.062a.3.3 0 0 0-.276-.188h-.57c-.83 0-1.5.68-1.5 1.517v.124c-.153-.117-.345-.362-.345-.758c0-.481.35-.724.574-.88c.064-.043.117-.08.149-.113l.045-.047c.156-.167.436-.463.924-.593q.116-.03.231-.047c.468-.07.808.348.808.821v.22z");
}

.z23533p_d {
  d: path("M12.112 20.44c-.938-1.981-.769-6.258-.487-7.823h1.672c-.072 2.425.039 5.243.177 6.511c.012.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.062.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.z24qw8r9d {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.82 5.676l-.265.826c-.046.17.063.34.217.34h.329c.154 0 .262-.173.217-.34l-.222-.826c-.047-.182-.226-.182-.276 0");
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zmoflnhgm {
  d: path("M13.818 6.47a.74.74 0 0 1-.406-.138v.418c0 .4.239.758.602.906a1.8 1.8 0 0 1-.156-.53z");
}

.zmwvj69un {
  d: path("M16 7.21c-.228 0-.442-.054-.622-.148c-.061-.031-.127.038-.089.094a.85.85 0 0 0 .711.38a.85.85 0 0 0 .71-.38c.04-.058-.027-.125-.088-.094A1.34 1.34 0 0 1 16 7.21");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

.zzl9q_jda {
  d: path("M11.533 12.66c.486-2.253 1.628-3.333 3.03-3.828v3.949H11.63a.1.1 0 0 1-.097-.12");
}

</style>
