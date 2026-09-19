<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iAPJuib)" class="p--846bez"/><path fill="url(#iQoovgc)" class="p--846bez"/><g filter="url(#i4tnmIt)"><path class="ng78d8b0l"/></g><g filter="url(#i3NB76c)"><path fill="url(#iPMqLGb)" class="uk8e6_3gk"/><path fill="url(#i8SWfye)" class="uk8e6_3gk"/><path fill="url(#itOLHpd)" class="uk8e6_3gk"/><path fill="url(#i4qJjyd)" class="uk8e6_3gk"/></g><path fill="url(#i6RsiYd)" class="ddwhu7b-p"/><path fill="url(#iZUr6qd)" class="ddwhu7b-p"/><path fill="url(#izjVH7N)" class="ddwhu7b-p"/><path fill="url(#ivIebid)" class="qywkn-bic"/><path fill="url(#iw5ELoc)" class="ddwhu7b-p"/><path fill="url(#iozxVHF)" class="ddwhu7b-p"/><path fill="url(#iepqwFe)" class="ddwhu7b-p"/><path fill="url(#iDHzzbb)" class="ddwhu7b-p"/><path fill="url(#iIoSrIe)" class="ddwhu7b-p"/><path fill="url(#iMHMrAe)" class="ddwhu7b-p"/><path fill="url(#i3Edbyb)" class="ddwhu7b-p"/><path fill="url(#iMkOKsA)" class="ddwhu7b-p"/><path fill="url(#iZBtdyl)" class="ddwhu7b-p"/><g filter="url(#icNw1VL)"><path fill="url(#iF94Dme)" class="cgv8vu4qe"/></g><g filter="url(#ifYh5ob)"><path class="toi7uyb2z"/></g><path fill="url(#i4zF69V)" class="k0wnik7ze"/><path fill="url(#is5lyPb)" class="k0wnik7ze"/><path fill="url(#i4uqVhc)" class="k0wnik7ze"/><path fill="url(#ikipgLc)" class="k0wnik7ze"/><path fill="url(#ijIq7Ed)" class="k0wnik7ze"/><path fill="url(#iylPfGe)" class="k0wnik7ze"/><path fill="url(#iFEUYCe)" class="k0wnik7ze"/><path fill="url(#iKg7VYc)" class="isdmovbnh"/><path fill="url(#ipeKAmd)" class="isdmovbnh"/><path fill="url(#irONztb)" stroke="url(#iUp4Xrc)" class="y7e1cwbmv"/><g filter="url(#iyCvkEc)"><path class="s7lwiybiw"/></g><path class="nhjr2lbyk"/><path fill="url(#ikjksCe)" class="n4hhv9xop"/><path fill="url(#ifC8Fcc)" class="n4hhv9xop"/><path fill="url(#iOs08Tc)" class="n4hhv9xop"/><path fill="url(#i23Nkud)" class="n4hhv9xop"/><path fill="url(#iRDkzre)" class="xx53xtndd"/><path fill="url(#iJwM8Oe)" class="xx53xtndd"/><g filter="url(#ifii0lc)"><path class="xe4hqjy-h"/></g><rect fill="url(#i1nbyze)" class="r24325gxz"/><rect fill="url(#iuYsqHb)" class="r24325gxz"/><rect fill="url(#iTK6nsb)" class="r24325gxz"/><g filter="url(#iXGkz7b)"><path stroke="url(#i7Bebjc)" class="v8guylbxz"/></g><g filter="url(#i68gnAb)"><path class="tcjdwzbtn"/></g><g filter="url(#iJ9Udrc)"><ellipse fill="url(#igS7kMc)" transform="rotate(26.272 14.643 2.903)" class="u3xpg_brt"/></g><g filter="url(#i0J0wqc)"><ellipse fill="url(#iaGHked)" transform="rotate(-21.931 18.375 10.884)" class="wjjqjbb2e"/></g><g filter="url(#iEjWaKc)"><ellipse fill="url(#i5JfFZd)" transform="rotate(43.388 27 13.494)" class="l68-aabjg"/></g><g filter="url(#iaZ0AXd)"><path fill="url(#ijzjfSd)" class="ufw2dxdyu"/></g><path fill="url(#iHMO2Hd)" class="rz-o0gb0n"/><g filter="url(#ibJdSAd)"><path fill="url(#iF790Rd)" class="hfsflacau"/></g><g filter="url(#i2vmv3c)"><path class="qw0rvvbpm"/></g><g filter="url(#iA8SUCm)"><path stroke="url(#iYmbncc)" class="o-qbxsx4h"/></g><path fill="url(#iPTL9jb)" class="i61mq2bem"/><path fill="url(#ipr9STd)" class="i61mq2bem"/><path fill="url(#iQMcLQC)" class="i61mq2bem"/><g filter="url(#i3dEvOd)"><path class="gus3ddb7k"/></g></g><defs><radialGradient id="ivIebid" cx="0" cy="0" r="1" gradientTransform="rotate(101.464 3.008 5.744)scale(4.55972 3.14895)" gradientUnits="userSpaceOnUse"><stop class="u7wyl1bgq"/><stop offset="1" class="ufh11wxjx"/></radialGradient><radialGradient id="iepqwFe" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -2.8125 1.95807 -1.3924 14.484 27.563)" gradientUnits="userSpaceOnUse"><stop class="q_1a4cbsy"/><stop offset="1" class="ffnkmvbeq"/></radialGradient><radialGradient id="iDHzzbb" cx="0" cy="0" r="1" gradientTransform="matrix(3.78125 -2.8125 1.49585 2.01109 8.484 23.531)" gradientUnits="userSpaceOnUse"><stop class="q_1a4cbsy"/><stop offset="1" class="ffnkmvbeq"/></radialGradient><radialGradient id="iIoSrIe" cx="0" cy="0" r="1" gradientTransform="rotate(-129.992 15.447 8.3)scale(8.60652 5.01512)" gradientUnits="userSpaceOnUse"><stop class="q_1a4cbsy"/><stop offset="1" class="ffnkmvbeq"/></radialGradient><radialGradient id="iMHMrAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.51562 -2.54688 1.82958 1.08877 21.688 23.766)" gradientUnits="userSpaceOnUse"><stop class="ml2xohbvj"/><stop offset=".801" class="vlw5zvbdy"/></radialGradient><radialGradient id="i3Edbyb" cx="0" cy="0" r="1" gradientTransform="matrix(.375 -4.60937 1.5766 .12826 29.078 22.156)" gradientUnits="userSpaceOnUse"><stop class="ml2xohbvj"/><stop offset="1" class="vlw5zvbdy"/></radialGradient><radialGradient id="iMkOKsA" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 -3.90625 2.10786 1.4502 20.516 25.125)" gradientUnits="userSpaceOnUse"><stop class="q_1a4cbsy"/><stop offset="1" class="ffnkmvbeq"/></radialGradient><radialGradient id="iZBtdyl" cx="0" cy="0" r="1" gradientTransform="matrix(3.29687 -3.57812 1.93686 1.78462 4.922 13.906)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="q_1a4cbsy"/><stop offset="1" class="ffnkmvbeq"/></radialGradient><radialGradient id="i4zF69V" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 1.82812 -3.12353 -3.04345 12.984 8.516)" gradientUnits="userSpaceOnUse"><stop class="ju9zw6uwt"/><stop offset="0" class="rygjaacdk"/><stop offset="1" class="ysj-jjprv"/></radialGradient><radialGradient id="is5lyPb" cx="0" cy="0" r="1" gradientTransform="rotate(130.462 4.31 7.333)scale(2.09475 2.88998)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="qqw30xbps"/><stop offset="1" class="d5jph2bba"/></radialGradient><radialGradient id="i4uqVhc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.674 8.015 3.53)scale(3.02508 4.64294)" gradientUnits="userSpaceOnUse"><stop class="d5jph2bba"/><stop offset="1" class="qqw30xbps"/></radialGradient><radialGradient id="ikipgLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.71875 -2.23438 -1.99062 12.594 8.781)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="l5y0tgbvf"/><stop offset="1" class="l_anbhj4s"/></radialGradient><radialGradient id="ijIq7Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-.6406 2.75 -3.57651 -.83314 12.86 8.406)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="l5y0tgbvf"/><stop offset="1" class="scgziacmf"/></radialGradient><radialGradient id="iylPfGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.67969 -.1875 .10787 -.39103 14.094 10.531)" gradientUnits="userSpaceOnUse"><stop class="hx0crul8a"/><stop offset="1" class="qrcn-h7ih"/></radialGradient><radialGradient id="iFEUYCe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6875 -1.35936 .9392 -1.16591 14.047 11.781)" gradientUnits="userSpaceOnUse"><stop class="scgziacmf"/><stop offset="1" class="l5y0tgbvf"/></radialGradient><radialGradient id="iKg7VYc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09373 3.06251 -3.80232 -2.5995 5.953 9.031)" gradientUnits="userSpaceOnUse"><stop class="g4y6vmb0y"/><stop offset="1" class="cfc2o6ykq"/></radialGradient><radialGradient id="ipeKAmd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31247 -3.28126 5.27362 -2.1094 5.36 13.313)" gradientUnits="userSpaceOnUse"><stop class="ot21yub5t"/><stop offset="1" class="s0-vsbmaz"/></radialGradient><radialGradient id="irONztb" cx="0" cy="0" r="1" gradientTransform="matrix(.5 0 0 .82047 4.242 10.516)" gradientUnits="userSpaceOnUse"><stop class="kjtbkhboi"/><stop offset="1" class="ifr39_c6p"/></radialGradient><radialGradient id="iUp4Xrc" cx="0" cy="0" r="1" gradientTransform="matrix(.82812 -.92968 2.39657 2.13476 3.75 11.094)" gradientUnits="userSpaceOnUse"><stop class="hq2ex9t-i"/><stop offset="1" class="r5_kkacnr"/></radialGradient><radialGradient id="ikjksCe" cx="0" cy="0" r="1" gradientTransform="matrix(.10938 3.53125 -5.53245 .17136 11.078 3.453)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="w15oarbsc"/><stop offset="1" class="c4sgc_d1i"/></radialGradient><radialGradient id="ifC8Fcc" cx="0" cy="0" r="1" gradientTransform="rotate(48.531 2.202 15.71)scale(.82583 1.88093)" gradientUnits="userSpaceOnUse"><stop class="bpczcib6q"/><stop offset="1" class="fmfohus3x"/></radialGradient><radialGradient id="i23Nkud" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 2 -3.58073 4.41996 11.844 3.89)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="fmfohus3x"/><stop offset="1" class="bpczcib6q"/></radialGradient><radialGradient id="igS7kMc" cx="0" cy="0" r="1" gradientTransform="matrix(.02118 .9575 -.4931 .0109 14.621 2.543)" gradientUnits="userSpaceOnUse"><stop class="tiswix-cf"/><stop offset="1" class="mh358hkmc"/></radialGradient><radialGradient id="iaGHked" cx="0" cy="0" r="1" gradientTransform="matrix(-.55715 5.39986 -3.70835 -.38262 18.898 7.785)" gradientUnits="userSpaceOnUse"><stop class="w9vlxqcee"/><stop offset="1" class="ekfn5qdre"/></radialGradient><radialGradient id="i5JfFZd" cx="0" cy="0" r="1" gradientTransform="matrix(.05846 5.38441 -2.84925 .03093 27.021 10.537)" gradientUnits="userSpaceOnUse"><stop class="w9vlxqcee"/><stop offset="1" class="ekfn5qdre"/></radialGradient><radialGradient id="iHMO2Hd" cx="0" cy="0" r="1" gradientTransform="rotate(105.051 4.553 20.968)scale(3.85086 5.73688)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="ffnkmvbeq"/><stop offset="1" class="q_1a4cbsy"/></radialGradient><radialGradient id="iPTL9jb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59376 -1.49998 5.22527 -9.03549 30.953 25.016)" gradientUnits="userSpaceOnUse"><stop class="wh15k1f1p"/><stop offset="1" class="m7w36h2-e"/></radialGradient><radialGradient id="ipr9STd" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 4.32812 -2.65488 -.11501 30.078 22.61)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="ipyiufb3y"/><stop offset="1" class="re5_w0l0v"/></radialGradient><radialGradient id="iQMcLQC" cx="0" cy="0" r="1" gradientTransform="rotate(111.682 7.634 21.656)scale(1.39562 .95286)" gradientUnits="userSpaceOnUse"><stop class="txof9obun"/><stop offset="1" class="d_tbkrmtt"/></radialGradient><linearGradient id="iAPJuib" x1="21.609" x2="21.609" y1="22.593" y2="29.458" gradientUnits="userSpaceOnUse"><stop offset=".079" class="oa4h-kjhx"/><stop offset="1" class="n2_pl8bde"/></linearGradient><linearGradient id="iQoovgc" x1="22.334" x2="22.359" y1="27.612" y2="29.922" gradientUnits="userSpaceOnUse"><stop offset=".644" class="ffnkmvbeq"/><stop offset=".949" class="l9f1yjecv"/></linearGradient><linearGradient id="iPMqLGb" x1="16.274" x2="16.274" y1="17.063" y2="27.5" gradientUnits="userSpaceOnUse"><stop class="oa4h-kjhx"/><stop offset="1" class="n2_pl8bde"/></linearGradient><linearGradient id="i8SWfye" x1="16.916" x2="16.953" y1="27.331" y2="29.941" gradientUnits="userSpaceOnUse"><stop offset=".644" class="ffnkmvbeq"/><stop offset=".949" class="l9f1yjecv"/></linearGradient><linearGradient id="itOLHpd" x1="15.922" x2="16.953" y1="20.625" y2="24.188" gradientUnits="userSpaceOnUse"><stop class="oa4h-kjhx"/><stop offset="1" class="lec4fib8m"/></linearGradient><linearGradient id="i4qJjyd" x1="18.239" x2="16.969" y1="23.688" y2="24.203" gradientUnits="userSpaceOnUse"><stop class="oa4h-kjhx"/><stop offset="1" class="lec4fib8m"/></linearGradient><linearGradient id="i6RsiYd" x1="22.672" x2="22.672" y1="10.25" y2="25.938" gradientUnits="userSpaceOnUse"><stop class="imk7mq3mp"/><stop offset="1" class="mi5ik13rn"/></linearGradient><linearGradient id="iZUr6qd" x1="7.141" x2="12.266" y1="4.125" y2="10.188" gradientUnits="userSpaceOnUse"><stop class="vjjtu4byf"/><stop offset="1" class="ed2ei3b-h"/></linearGradient><linearGradient id="izjVH7N" x1="5.922" x2="11.609" y1="16.125" y2="15.188" gradientUnits="userSpaceOnUse"><stop class="vjjtu4byf"/><stop offset="1" class="ed2ei3b-h"/></linearGradient><linearGradient id="iw5ELoc" x1="22.609" x2="19.984" y1="3.625" y2="13.25" gradientUnits="userSpaceOnUse"><stop class="xvoltzroz"/><stop offset=".988" class="w99jj4byi"/></linearGradient><linearGradient id="iozxVHF" x1="20.93" x2="20.93" y1="23.688" y2="30.469" gradientUnits="userSpaceOnUse"><stop offset=".788" class="ffnkmvbeq"/><stop offset=".919" class="l9f1yjecv"/></linearGradient><linearGradient id="iF94Dme" x1="14.688" x2="11.996" y1="7.406" y2="9.173" gradientUnits="userSpaceOnUse"><stop class="w9vlxqcee"/><stop offset="1" class="ekfn5qdre"/></linearGradient><linearGradient id="iOs08Tc" x1="7.828" x2="12.126" y1="5.281" y2="4.59" gradientUnits="userSpaceOnUse"><stop class="bpczcib6q"/><stop offset="1" class="fmfohus3x"/></linearGradient><linearGradient id="iRDkzre" x1="12.072" x2="12.047" y1="1.375" y2="2.992" gradientUnits="userSpaceOnUse"><stop offset=".575" class="w15oarbsc"/><stop offset="1" class="k1zzcdcpk"/></linearGradient><linearGradient id="iJwM8Oe" x1="11.063" x2="12.438" y1="2.641" y2="2.641" gradientUnits="userSpaceOnUse"><stop class="bpczcib6q"/><stop offset="1" class="fmfohus3x"/></linearGradient><linearGradient id="i1nbyze" x1="8.172" x2="7.578" y1="8.755" y2="8.755" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset=".855" class="co-foyhmg"/></linearGradient><linearGradient id="iuYsqHb" x1="8.479" x2="8.479" y1="9.955" y2="9.244" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iTK6nsb" x1="7.156" x2="7.594" y1="8.875" y2="8.875" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset="1" class="c_lfom8in"/></linearGradient><linearGradient id="i7Bebjc" x1="11.063" x2="13.266" y1="7.734" y2="9.969" gradientUnits="userSpaceOnUse"><stop class="zrldq4zmc"/><stop offset="1" class="tr3-oac9m"/></linearGradient><linearGradient id="ijzjfSd" x1="27.859" x2="27.859" y1="24.031" y2="11.031" gradientUnits="userSpaceOnUse"><stop class="tfduksbhn"/><stop offset="1" class="rh6_d6v2o"/></linearGradient><linearGradient id="iF790Rd" x1="14.219" x2="14.219" y1="24.044" y2="19.128" gradientUnits="userSpaceOnUse"><stop class="lumgacevc"/><stop offset="1" class="vvys2pb-n"/></linearGradient><linearGradient id="iYmbncc" x1="31.494" x2="31.494" y1="23.188" y2="15.807" gradientUnits="userSpaceOnUse"><stop class="yerb6abbg"/><stop offset="1" class="c8-n_-b5m"/></linearGradient><filter id="i4tnmIt" width="3.472" height="8.191" x="19.772" y="21.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".325"/></filter><filter id="i3NB76c" width="4.08" height="10.05" x="14.309" y="19.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.133333 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_2889"/></filter><filter id="icNw1VL" width="5.813" height="6.516" x="10.016" y="4.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".5"/></filter><filter id="ifYh5ob" width="4.18" height="4.38" x="9.618" y="7.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".25"/></filter><filter id="iyCvkEc" width="4.851" height="3.212" x="8.448" y="4.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".325"/></filter><filter id="ifii0lc" width="1.969" height="2.96" x="6.611" y="7.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".25"/></filter><filter id="iXGkz7b" width="3.528" height="3.573" x="10.518" y="7.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".2"/></filter><filter id="i68gnAb" width="6.623" height="5.254" x="9.172" y="1.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".5"/></filter><filter id="iJ9Udrc" width="1.962" height="2.143" x="13.661" y="1.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".25"/></filter><filter id="i0J0wqc" width="6.085" height="6.904" x="15.332" y="7.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".5"/></filter><filter id="iEjWaKc" width="8.282" height="8.207" x="22.859" y="9.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".625"/></filter><filter id="iaZ0AXd" width="3.938" height="11.156" x="24.922" y="18.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".5"/></filter><filter id="ibJdSAd" width="3.653" height="5.962" x="11.566" y="21.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".5"/></filter><filter id="i2vmv3c" width="2.318" height="7.188" x="15.937" y="22.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".25"/></filter><filter id="iA8SUCm" width=".75" height="6.969" x="29.688" y="16.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".125"/></filter><filter id="i3dEvOd" width=".95" height="3.622" x="29.47" y="22.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2889" stdDeviation=".2"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:water-buffalo" /></template>
<style>
.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.bpczcib6q {
  stop-color: var(--svg-color--808089, #808089);
}

.c_lfom8in {
  stop-color: var(--svg-color--574d50, #574D50);
  stop-opacity: 0;
}

.c4sgc_d1i {
  stop-color: var(--svg-color--82729a, #82729A);
}

.c8-n_-b5m {
  stop-color: var(--svg-color--797481, #797481);
  stop-opacity: 0;
}

.cfc2o6ykq {
  stop-color: var(--svg-color--3b393e, #3B393E);
}

.cgv8vu4qe {
  d: path("m14.828 8l-1.281-2.094l-2.531.188l.906 4.328z");
}

.co-foyhmg {
  stop-color: var(--svg-color--31232c, #31232C);
}

.d_tbkrmtt {
  stop-color: var(--svg-color--9e9d9f, #9E9D9F);
  stop-opacity: 0;
}

.d5jph2bba {
  stop-color: var(--svg-color--46434c, #46434C);
}

.ddwhu7b-p {
  d: path("M25.67 9.775h-3.76c-.62 0-1.2-.27-1.63-.72a3.93 3.93 0 0 0-2.92-1.28h-2c-.16 0-.31-.08-.39-.22l-.56-.96a3.63 3.63 0 0 0-3.15-1.82h-.89c-.78 0-1.55.23-2.2.67l-5.1 3.4c-.44.29-.71.79-.71 1.32c0 1.43 1.13 2.61 2.56 2.61h2.022a.5.5 0 0 1 .492.41l.655 3.62l.68 3.9c.17.947.842 1.694 1.718 1.978a.45.45 0 0 1 .322.415v6.457c0 .14.11.25.25.25h1.5c.14 0 .25-.11.25-.25v-2.504a.4.4 0 0 1 .22-.357l.65-.329c.69-.35 1.13-1.05 1.13-1.82v-1.342a.4.4 0 0 1 .398-.4l5.542-.028a2.6 2.6 0 0 0 1.36-.381a.177.177 0 0 1 .264.132a3.26 3.26 0 0 0 2.466 2.87l1.142.284a.5.5 0 0 1 .378.485v3.36c0 .14.11.25.25.25h1.5c.14 0 .25-.11.25-.25V20.47a.83.83 0 0 1 .328-.641q.049-.038.096-.08c.214-.178.576-.038.576.241v3.786h1v-9.31c0-2.59-2.1-4.69-4.69-4.69");
}

.ed2ei3b-h {
  stop-color: var(--svg-color--5e5f62, #5E5F62);
  stop-opacity: 0;
}

.ekfn5qdre {
  stop-color: var(--svg-color--808085, #808085);
  stop-opacity: 0;
}

.ffnkmvbeq {
  stop-color: var(--svg-color--5b3e76, #5B3E76);
  stop-opacity: 0;
}

.fmfohus3x {
  stop-color: var(--svg-color--808089, #808089);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g4y6vmb0y {
  stop-color: var(--svg-color--4c4d4f, #4C4D4F);
}

.gus3ddb7k {
  stroke: var(--svg-color--7f7b85, #7F7B85);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M29.945 23.405v2.672");
}

.hfsflacau {
  d: path("M12.566 22.472h1.653v2.994l-1.653.968z");
}

.hq2ex9t-i {
  stop-color: var(--svg-color--57555c, #57555C);
}

.hx0crul8a {
  stop-color: var(--svg-color--6b6b6d, #6B6B6D);
}

.i61mq2bem {
  d: path("M29.865 26.713c.267.068.494-.162.494-.438v-3.5c-1.1 0-2 .9-2 2c0 .93.643 1.716 1.505 1.938");
}

.ifr39_c6p {
  stop-color: var(--svg-color--1d1d20, #1D1D20);
}

.imk7mq3mp {
  stop-color: var(--svg-color--6d6975, #6D6975);
}

.ipyiufb3y {
  stop-color: var(--svg-color--5d4875, #5D4875);
  stop-opacity: 0;
}

.isdmovbnh {
  d: path("M2.36 10.165c0 1.43 1.13 2.61 2.56 2.61h1.39v-2.36c0-1.17-.75-2.17-1.8-2.53l-1.44.96c-.44.29-.71.79-.71 1.32");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.ju9zw6uwt {
  stop-color: var(--svg-color--7d5953, #7D5953);
}

.k0wnik7ze {
  d: path("M11.21 7.397c-.226-.227-.607-.184-.71.12a2.601 2.601 0 0 0 3.307 3.299c.3-.105.34-.483.116-.707z");
}

.k1zzcdcpk {
  stop-color: var(--svg-color--766392, #766392);
}

.kfeabacio {
  stop-color: var(--svg-color--574d50, #574D50);
}

.kjtbkhboi {
  stop-color: var(--svg-color--3e3d40, #3E3D40);
}

.l_anbhj4s {
  stop-color: var(--svg-color--49375b, #49375B);
}

.l5y0tgbvf {
  stop-color: var(--svg-color--281c33, #281C33);
  stop-opacity: 0;
}

.l68-aabjg {
  cx: 27px;
  cy: 13.494px;
  rx: 3.184px;
  ry: 2.523px;
}

.l9f1yjecv {
  stop-color: var(--svg-color--5b3e76, #5B3E76);
}

.lec4fib8m {
  stop-color: var(--svg-color--2c2238, #2C2238);
  stop-opacity: 0;
}

.lumgacevc {
  stop-color: var(--svg-color--7a7682, #7A7682);
}

.m7w36h2-e {
  stop-color: var(--svg-color--4e4c53, #4E4C53);
}

.mh358hkmc {
  stop-color: var(--svg-color--c4c4c4, #C4C4C4);
  stop-opacity: 0;
}

.mi5ik13rn {
  stop-color: var(--svg-color--676073, #676073);
}

.ml2xohbvj {
  stop-color: var(--svg-color--483e56, #483E56);
}

.n2_pl8bde {
  stop-color: var(--svg-color--5d5768, #5D5768);
}

.n4hhv9xop {
  d: path("M14.14 1.775h-2.26c-.27 0-.5.2-.52.47c-.02.29.21.53.5.53h1.31c.09 0 .16.1.12.18c-.43.99-1.51 1.8-2.63 1.82h-.3c-.55 0-1 .45-1 1s.45 1 1 1h1c2-.09 4-1.78 4-3.78c0-.68-.54-1.22-1.22-1.22");
}

.ng78d8b0l {
  stroke: var(--svg-color--6e6877, #6E6877);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m22.469 22.516l-1.922 6.64");
}

.nhjr2lbyk {
  fill: var(--svg-color--9c9ba4, #9C9BA4);
  d: path("M14.14 1.775h-2.26c-.27 0-.5.2-.52.47c-.02.29.21.53.5.53h1.31c.09 0 .16.1.12.18c-.43.99-1.51 1.8-2.63 1.82h-.3c-.55 0-1 .45-1 1s.45 1 1 1h1c2-.09 4-1.78 4-3.78c0-.68-.54-1.22-1.22-1.22");
}

.o-qbxsx4h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M30.063 23.188v-6.22");
}

.oa4h-kjhx {
  stop-color: var(--svg-color--2c2238, #2C2238);
}

.ot21yub5t {
  stop-color: var(--svg-color--4b3560, #4B3560);
}

.p--846bez {
  d: path("M21.12 29.775h-1.48c-.17 0-.29-.16-.24-.32l2.43-8.53h2l-2.47 8.67c-.03.11-.13.18-.24.18");
}

.q_1a4cbsy {
  stop-color: var(--svg-color--492e63, #492E63);
}

.qqw30xbps {
  stop-color: var(--svg-color--46434c, #46434C);
  stop-opacity: 0;
}

.qrcn-h7ih {
  stop-color: var(--svg-color--6b6b6d, #6B6B6D);
  stop-opacity: 0;
}

.qw0rvvbpm {
  stroke: var(--svg-color--6e6877, #6E6877);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m16.563 23.344l1.062 3.39l-.75 2.547");
}

.qywkn-bic {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M25.67 9.775h-3.76c-.62 0-1.2-.27-1.63-.72a3.93 3.93 0 0 0-2.92-1.28h-2c-.16 0-.31-.08-.39-.22l-.56-.96a3.63 3.63 0 0 0-3.15-1.82h-.89c-.78 0-1.55.23-2.2.67l-5.1 3.4c-.44.29-.71.79-.71 1.32c0 1.43 1.13 2.61 2.56 2.61h2.022a.5.5 0 0 1 .492.41l.655 3.62l.68 3.9c.17.947.842 1.694 1.718 1.978a.45.45 0 0 1 .322.415v6.457c0 .14.11.25.25.25h1.5c.14 0 .25-.11.25-.25v-2.504a.4.4 0 0 1 .22-.357l.65-.329c.69-.35 1.13-1.05 1.13-1.82v-1.342a.4.4 0 0 1 .398-.4l5.542-.028a2.6 2.6 0 0 0 1.36-.381a.177.177 0 0 1 .264.132a3.26 3.26 0 0 0 2.466 2.87l1.142.284a.5.5 0 0 1 .378.485v3.36c0 .14.11.25.25.25h1.5c.14 0 .25-.11.25-.25V20.47a.83.83 0 0 1 .328-.641q.049-.038.096-.08c.214-.178.576-.038.576.241v3.786h1v-9.31c0-2.59-2.1-4.69-4.69-4.69");
}

.r24325gxz {
  width: 0.969px;
  height: 1.96px;
  x: 7.359px;
  y: 7.775px;
  rx: 0.484px;
}

.r5_kkacnr {
  stop-color: var(--svg-color--4a375c, #4A375C);
  stop-opacity: 0;
}

.re5_w0l0v {
  stop-color: var(--svg-color--5d4875, #5D4875);
}

.rh6_d6v2o {
  stop-color: var(--svg-color--7b7882, #7B7882);
  stop-opacity: 0;
}

.rygjaacdk {
  stop-color: var(--svg-color--545456, #545456);
}

.rz-o0gb0n {
  d: path("M26.352 19.531h-2.149l-1.911 2.867a.17.17 0 0 1 .081.128a3.26 3.26 0 0 0 2.466 2.87l1.142.284a.5.5 0 0 1 .37.397z");
}

.s0-vsbmaz {
  stop-color: var(--svg-color--4b3560, #4B3560);
  stop-opacity: 0;
}

.s7lwiybiw {
  fill: var(--svg-color--44414a, #44414A);
  d: path("M9.098 6.099c0-.528.428-.956.956-.956h2.594v.912a1 1 0 0 1-1 1h-1.594a.956.956 0 0 1-.956-.956");
}

.scgziacmf {
  stop-color: var(--svg-color--483060, #483060);
}

.tcjdwzbtn {
  stroke: var(--svg-color--c0c0c7, #C0C0C7);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.672 2.734c-.188 1.157-1.575 3.11-4.5 3.11");
}

.tfduksbhn {
  stop-color: var(--svg-color--7b7882, #7B7882);
}

.tiswix-cf {
  stop-color: var(--svg-color--c4c4c4, #C4C4C4);
}

.toi7uyb2z {
  fill: var(--svg-color--4c4656, #4C4656);
  d: path("M11.594 8.098c-.507-.564-1.432-.481-1.472.276a2.6 2.6 0 0 0 2.456 2.736c.761.04.94-.868.432-1.435z");
}

.tr3-oac9m {
  stop-color: var(--svg-color--727076, #727076);
  stop-opacity: 0;
}

.txof9obun {
  stop-color: var(--svg-color--9e9d9f, #9E9D9F);
}

.u3xpg_brt {
  cx: 14.643px;
  cy: 2.903px;
  rx: 0.448px;
  ry: 0.598px;
}

.u7wyl1bgq {
  stop-color: var(--svg-color--44414a, #44414A);
}

.ufh11wxjx {
  stop-color: var(--svg-color--44414a, #44414A);
  stop-opacity: 0;
}

.ufw2dxdyu {
  d: path("M27.86 19.875v9.156l-1.938-9.156z");
}

.uk8e6_3gk {
  d: path("M16.31 19.775h-2l1.98 6.91c.02.06.02.12 0 .17l-.76 2.59c-.05.17.07.33.23.33h1.48c.11 0 .21-.07.24-.18l.7-2.39c.08-.28.08-.58 0-.87z");
}

.v8guylbxz {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m10.953 7.64l2.656 2.704");
}

.vjjtu4byf {
  stop-color: var(--svg-color--5e5f62, #5E5F62);
}

.vlw5zvbdy {
  stop-color: var(--svg-color--483e56, #483E56);
  stop-opacity: 0;
}

.vvys2pb-n {
  stop-color: var(--svg-color--7a7682, #7A7682);
  stop-opacity: 0;
}

.w15oarbsc {
  stop-color: var(--svg-color--82729a, #82729A);
  stop-opacity: 0;
}

.w99jj4byi {
  stop-color: var(--svg-color--57585b, #57585B);
  stop-opacity: 0;
}

.w9vlxqcee {
  stop-color: var(--svg-color--808085, #808085);
}

.wh15k1f1p {
  stop-color: var(--svg-color--6e6977, #6E6977);
}

.wjjqjbb2e {
  cx: 18.375px;
  cy: 10.884px;
  rx: 1.953px;
  ry: 2.523px;
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xe4hqjy-h {
  fill: var(--svg-color--4c4656, #4C4656);
  d: path("M7.111 8.326a.484.484 0 1 1 .969 0v.991a.484.484 0 1 1-.969 0z");
}

.xvoltzroz {
  stop-color: var(--svg-color--57585b, #57585B);
}

.xx53xtndd {
  d: path("M13.7 1.775c-.19.702-.433 1.295-.598 1.537q.107-.173.187-.357c.04-.08-.03-.18-.12-.18h-1.31c-.29 0-.52-.24-.5-.53c.02-.27.25-.47.52-.47z");
}

.y7e1cwbmv {
  stroke-width: var(--svg-stroke-width--0-12px, 0.12px);
  d: path("M3.9 10.685c0 .313.246.56.56.56c.312 0 .56-.247.56-.56v-.55a.555.555 0 0 0-.56-.56a.555.555 0 0 0-.56.56z");
}

.yerb6abbg {
  stop-color: var(--svg-color--797481, #797481);
}

.ysj-jjprv {
  stop-color: var(--svg-color--46424c, #46424C);
}

.zrldq4zmc {
  stop-color: var(--svg-color--7e7b82, #7E7B82);
}

</style>
