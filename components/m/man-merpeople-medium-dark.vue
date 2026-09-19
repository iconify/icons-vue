<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#irkL6dE)"><path class="akxi8m76s"/></g><path fill="url(#igX65Dc)" class="c643mffnw"/><g filter="url(#i2wQ8qe)"><path fill="url(#iTOCd4d)" class="xxpmw9bmk"/></g><g filter="url(#iqDpoFb)"><path stroke="url(#ieE0Yhd)" class="r4iderb0y"/></g><g filter="url(#iSizitb)"><path stroke="url(#iRHdtfb)" class="ny9sszb6m"/></g><g filter="url(#inSQYjb)"><path stroke="url(#ieanqtr)" class="tfrolbc-z"/></g><g filter="url(#iin9kEb)"><path class="c371ppbal"/><path fill="url(#i6585gc)" class="r-gax6bvb"/><path fill="url(#izWpCok)" class="r-gax6bvb"/></g><path fill="url(#iiMzX4d)" class="ehl3r9-ue"/><path fill="url(#iIF5Vwd)" class="ehl3r9-ue"/><path fill="url(#ios9MOa)" class="ehl3r9-ue"/><path fill="url(#iFRANrb)" class="ehl3r9-ue"/><g filter="url(#iKsGEKd)"><rect class="b3-b84bgv"/><rect fill="url(#iO0H3lc)" class="cjh0fgb4e"/></g><g filter="url(#i9wSnId)"><path fill="url(#iXfqq3j)" class="lvdaoyblx"/><path fill="url(#iMBqliN)" class="lvdaoyblx"/><path fill="url(#ikHIUre)" class="lvdaoyblx"/></g><g filter="url(#iVJ6bqb)"><path fill="url(#ivPc5hd)" class="ltzv29bsf"/><path fill="url(#iji78QN)" class="ltzv29bsf"/><path fill="url(#iOYDUJe)" class="ltzv29bsf"/><path fill="url(#iKOIV4c)" class="ltzv29bsf"/><path fill="url(#ilHv6va)" class="ltzv29bsf"/></g><path fill="url(#ilFtXie)" class="bv_sh6uhi"/><path fill="url(#i5f0bRX)" class="bv_sh6uhi"/><path fill="url(#iHHdShd)" class="bv_sh6uhi"/><path fill="url(#ipJ71Fc)" class="a94pfab2a"/><path fill="url(#iIZ9OKf)" class="a94pfab2a"/><g filter="url(#igefS8S)"><path fill="url(#ifbyPyb)" class="hzfyqre6p"/><path fill="url(#iZhPaFb)" class="hzfyqre6p"/></g><path fill="url(#i98XLfb)" class="wyojejvbl"/><path fill="url(#i7vozCe)" class="wyojejvbl"/><path fill="url(#iyMqRre)" class="wyojejvbl"/><path fill="url(#ioMIqWd)" class="wyojejvbl"/><g filter="url(#idctdWb)"><path stroke="url(#iKLlMZb)" class="isx036d_i"/></g><g filter="url(#iZ8Xc3d)"><path stroke="url(#iojTvld)" class="d_rf9vbee"/></g><g filter="url(#iaBxaMf)"><path fill="url(#iCybRry)" class="c2k06z0us"/></g><g filter="url(#iSfq7tc)"><path stroke="url(#iW5WXXs)" class="ph7r7fb0a"/></g><g filter="url(#iedJTVc)"><path stroke="url(#iSxRyoe)" class="effrlx4na"/></g><g filter="url(#iEa4FAb)"><path stroke="url(#i9YcDMc)" class="g-ne0bc-o"/></g><g filter="url(#iwRWXGe)"><circle fill="url(#ijo5fZd)" class="wc9zh7c1h"/></g><g filter="url(#ifJ9nYc)"><circle fill="url(#i8mp5Bd)" class="a0-6u3e5y"/></g><g filter="url(#iI9C5xd)"><circle fill="url(#ioPsgid)" class="mtgo0ubdn"/><circle fill="url(#iSYxnub)" class="mtgo0ubdn"/></g><g filter="url(#icRwZIe)"><circle class="nsfj97bgf"/><circle fill="url(#iKSLzte)" class="acig8mj4m"/><circle fill="url(#ijVgcab)" class="acig8mj4m"/></g><g filter="url(#iOU2gqe)"><path fill="url(#iCwYOIe)" class="l7mq-8b5v"/><path fill="url(#iSIQFNe)" class="l7mq-8b5v"/><path fill="url(#iSf1pHe)" class="l7mq-8b5v"/></g><path fill="url(#i6lIdLm)" class="ztklvab2u"/><path fill="url(#isXaobd)" class="ztklvab2u"/><path fill="url(#i2R3aOn)" class="ztklvab2u"/><g filter="url(#iNMlzNe)"><path fill="url(#i43HjDb)" class="k_h8jt__y"/></g><g filter="url(#iSL6Iqc)"><path class="l50mvkdpw"/><path fill="url(#iOvm8Db)" class="est74jqyf"/><path fill="url(#iUooAyd)" class="est74jqyf"/><path fill="url(#iKsOxFb)" class="est74jqyf"/><path fill="url(#i49Li7c)" class="est74jqyf"/></g><g filter="url(#iWOpbAb)"><path class="j1jnmrbau"/></g><g filter="url(#iTzsgQT)"><path class="mb_u8gbtd"/><path fill="url(#iSawKAm)" class="dx70v779w"/><path fill="url(#imjmxXb)" class="dx70v779w"/><path fill="url(#is4pXUd)" class="dx70v779w"/><path fill="url(#iecbZbd)" class="dx70v779w"/></g><path stroke="url(#iSY52fb)" class="dfh5jib8x"/><g filter="url(#idZEw5c)"><path class="a2al628fd"/><path fill="url(#ivU4LIb)" class="cg9ww2bak"/></g><g filter="url(#iX2WDSb)"><path class="idi1sy6zn"/><path fill="url(#iS0tUab)" class="ik8rbzbeu"/></g><path class="a9e6g3bep"/><path fill="url(#i9MuLWD)" class="ds5elicqx"/><path class="qtupvmeij"/><g filter="url(#iP87Pbd)"><path class="ehygodg_r"/><path fill="url(#iqP31yc)" class="ht4ed36iq"/></g><g filter="url(#io9eFLb)"><path fill="url(#iUVetDd)" class="h6fiem_lc"/></g><path class="kf4vpey8i"/><path fill="url(#ixKg9wU)" class="xk6vuvbsk"/><path class="q6u_azx6h"/><g filter="url(#iPFl77w)"><path fill="url(#iOyNDme)" class="md63exb4n"/></g><g filter="url(#ic0vYNe)"><ellipse transform="rotate(-27.914 13.435 6.532)" class="rt84dmblg"/><ellipse fill="url(#isuaYhe)" transform="rotate(-27.914 13.435 6.532)" class="nnvmiz6zt"/></g><g filter="url(#ibLKNKe)"><path stroke="url(#i1gYneb)" class="w5k93kblc"/></g><g filter="url(#iXUT6xd)"><path stroke="url(#iJNIJeb)" class="e645vzbmc"/></g><g filter="url(#iJsRMKp)"><path stroke="url(#i0ZNu1d)" class="m3e9qlrif"/></g><defs><radialGradient id="igX65Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 86.56 -14.38)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="iTOCd4d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 20.046 20.637)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="i6585gc" cx="0" cy="0" r="1" gradientTransform="matrix(2.09374 2.54688 -.87207 .71691 17.692 13.73)" gradientUnits="userSpaceOnUse"><stop class="wufs5mmvw"/><stop offset="1" class="idtkbybie"/></radialGradient><radialGradient id="izWpCok" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92188 -.83495 0 24.395 14.84)" gradientUnits="userSpaceOnUse"><stop class="puzayy21j"/><stop offset="1" class="y6s2lqb2q"/></radialGradient><radialGradient id="iiMzX4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.5273 1.08984 0 24.823 29.957)" gradientUnits="userSpaceOnUse"><stop class="vj07kubhl"/><stop offset="1" class="keqz-8g7v"/></radialGradient><radialGradient id="iIF5Vwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -17.8945 2.43359 0 24.823 28.324)" gradientUnits="userSpaceOnUse"><stop offset=".906" class="sy7qt-bzl"/><stop offset="1" class="i8gxpdlwn"/></radialGradient><radialGradient id="ios9MOa" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.3125 -1.10912 0 24.823 15.824)" gradientUnits="userSpaceOnUse"><stop class="ti8dkw8jh"/><stop offset="1" class="uw8wenb6w"/></radialGradient><radialGradient id="iO0H3lc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31815 0 0 -1.07813 26.163 9.871)" gradientUnits="userSpaceOnUse"><stop class="jk8wwdkvh"/><stop offset="1" class="kt1qsbbol"/></radialGradient><radialGradient id="iXfqq3j" cx="0" cy="0" r="1" gradientTransform="rotate(108.771 12.73 11.776)scale(5.04985 5.80366)" gradientUnits="userSpaceOnUse"><stop class="l1mhifosa"/><stop offset="1" class="nwr0ulaka"/></radialGradient><radialGradient id="iMBqliN" cx="0" cy="0" r="1" gradientTransform="matrix(2 8.14203 -5.28875 1.29912 23.35 2.088)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="tfpize5dt"/><stop offset="1" class="udxjy24sj"/></radialGradient><radialGradient id="ikHIUre" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 1 -.64044 -.57039 23.148 2.387)" gradientUnits="userSpaceOnUse"><stop offset=".048" class="ozaj1r-nb"/><stop offset="1" class="pkl3f-q-p"/></radialGradient><radialGradient id="iji78QN" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25757 0 0 -.32031 26.255 15.508)" gradientUnits="userSpaceOnUse"><stop class="vujuhsl8y"/><stop offset="1" class="mq0387tuz"/></radialGradient><radialGradient id="iOYDUJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06226 0 0 -.27056 26.255 14.707)" gradientUnits="userSpaceOnUse"><stop class="vujuhsl8y"/><stop offset="1" class="mq0387tuz"/></radialGradient><radialGradient id="iKOIV4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.97632 0 0 -.27344 26.255 13.98)" gradientUnits="userSpaceOnUse"><stop class="vujuhsl8y"/><stop offset="1" class="mq0387tuz"/></radialGradient><radialGradient id="ilHv6va" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17944 0 0 -.28906 26.255 13.207)" gradientUnits="userSpaceOnUse"><stop class="vujuhsl8y"/><stop offset="1" class="mq0387tuz"/></radialGradient><radialGradient id="i5f0bRX" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 0 0 -1 25.63 13.832)" gradientUnits="userSpaceOnUse"><stop class="tz8c4ccqc"/><stop offset="1" class="t8oj2cj7p"/></radialGradient><radialGradient id="iHHdShd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -.9375 .74865 -.02496 24.27 14.48)" gradientUnits="userSpaceOnUse"><stop class="puzayy21j"/><stop offset="1" class="y6s2lqb2q"/></radialGradient><radialGradient id="ipJ71Fc" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -.26562 .64937 1.60434 4.241 16.746)" gradientUnits="userSpaceOnUse"><stop class="xhiu3e_7t"/><stop offset="1" class="b8bskobqr"/></radialGradient><radialGradient id="ifbyPyb" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -3.1875 1.21246 2.63887 4.726 16.2)" gradientUnits="userSpaceOnUse"><stop class="io-9ceb3b"/><stop offset="1" class="f7ghh-b7f"/></radialGradient><radialGradient id="iZhPaFb" cx="0" cy="0" r="1" gradientTransform="rotate(138.102 3.518 9.165)scale(4.49229 1.70257)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="fhkyt6b1e"/><stop offset="1" class="ue5c2h_jl"/></radialGradient><radialGradient id="i98XLfb" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 8.28125 -6.68817 1.3124 17.32 12.074)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="ho90xacyk"/><stop offset="1" class="i87klgbfp"/></radialGradient><radialGradient id="i7vozCe" cx="0" cy="0" r="1" gradientTransform="matrix(.36153 4.94799 -2.46163 .17986 11.008 14.719)" gradientUnits="userSpaceOnUse"><stop class="gjxswab1e"/><stop offset="1" class="fsqmitk4x"/></radialGradient><radialGradient id="iyMqRre" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -1.8125 4.2981 10.67113 13.52 14.527)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="ezxr85bmy"/><stop offset="1" class="lx7u95xxl"/></radialGradient><radialGradient id="ioMIqWd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49805 1.0781 -.58371 -1.3525 14.849 10.121)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="btcqthbni"/><stop offset="1" class="v9ivl9bbn"/></radialGradient><radialGradient id="iCybRry" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 .23438 -.46507 -.83711 25.304 2.816)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="nvk-74bwn"/><stop offset="1" class="f1ri06bus"/></radialGradient><radialGradient id="i9YcDMc" cx="0" cy="0" r="1" gradientTransform="matrix(4.84376 2.56248 -.9379 1.77288 19.114 12.808)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="pmht_lb4e"/><stop offset=".93" class="y63dx6x-v"/></radialGradient><radialGradient id="ijo5fZd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0069 0 0 1.76209 11.162 6.978)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iSYxnub" cx="0" cy="0" r="1" gradientTransform="matrix(.47434 -.3454 .39422 .5414 17.792 6.826)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iKSLzte" cx="0" cy="0" r="1" gradientTransform="matrix(.47122 -.86671 .50729 .2758 17.555 7.45)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="ijVgcab" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 .304 24.862)scale(.20933 .26986)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iSIQFNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.74997 .92304 0 16.19 6.249)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iSf1pHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.78843 .98049 0 13.575 6.326)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="i2R3aOn" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.07595 -6.89033 0 14.671 5.96)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="l9l4bwbun"/><stop offset=".949" class="e_um2wu8p"/></radialGradient><radialGradient id="iOvm8Db" cx="0" cy="0" r="1" gradientTransform="matrix(.45777 -1.69644 .81683 .22041 17.338 4.622)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iUooAyd" cx="0" cy="0" r="1" gradientTransform="matrix(2.1946 .20196 -.1086 1.18002 16.395 3.612)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iKsOxFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96347 -1.49215 0 14.844 2.043)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="i49Li7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.76376 -1.29253 2.02497 2.76324 11.144 5.955)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iecbZbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .11298 -.36297 0 15.032 7.9)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="ivU4LIb" cx="0" cy="0" r="1" gradientTransform="matrix(.05978 -.34614 1.02403 .17687 16.245 5.782)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iS0tUab" cx="0" cy="0" r="1" gradientTransform="matrix(.05979 -.34614 1.02409 .17689 13.292 5.782)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="i9MuLWD" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46541 -.74029 0 16.094 6.587)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iqP31yc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 9.606 -.592)scale(.217 .29877)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixKg9wU" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46543 -.74032 0 13.59 6.587)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="isuaYhe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00444 -.28343 .3407 -.00533 13.426 6.713)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="irkL6dE" width="16.97" height="13.626" x="4.983" y="16.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1295" result="effect2_innerShadow_4002_1295"/></filter><filter id="i2wQ8qe" width="8.803" height="12.453" x="12.427" y="15.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".5"/></filter><filter id="iqDpoFb" width="11.112" height="3.615" x="8.173" y="25.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".2"/></filter><filter id="iSizitb" width="3.297" height="3.17" x="5.589" y="23.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".2"/></filter><filter id="inSQYjb" width="3.085" height="3.032" x="8.851" y="23.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".2"/></filter><filter id="iin9kEb" width="8.453" height="6.378" x="16.55" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.8"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.305882 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.313726 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1295" result="effect2_innerShadow_4002_1295"/></filter><filter id="iKsGEKd" width="2.963" height="1.158" x="23.363" y="9.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.541176 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/></filter><filter id="i9wSnId" width="8.438" height="7.533" x="20.669" y="1.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.517647 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/></filter><filter id="iVJ6bqb" width="1.765" height="3.013" x="24.69" y="13.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.254902 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/></filter><filter id="igefS8S" width="10.053" height="7.208" x="2.993" y="10.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.266667 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/></filter><filter id="idctdWb" width="2.209" height="5.708" x="26.777" y="3.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".1"/></filter><filter id="iZ8Xc3d" width="1.759" height="1.3" x="26.569" y="2.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".1"/></filter><filter id="iaBxaMf" width="1.189" height="1.345" x="24.572" y="2.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".1"/></filter><filter id="iSfq7tc" width="2.586" height="5.952" x="24.656" y="3.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".1"/></filter><filter id="iedJTVc" width="2.948" height="6.859" x="20.962" y="2.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".1"/></filter><filter id="iEa4FAb" width="7.3" height="3.894" x="17.558" y="11.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".3"/></filter><filter id="iwRWXGe" width="2.116" height="1.916" x="11.162" y="6.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/></filter><filter id="ifJ9nYc" width="2.142" height="2.142" x="11.049" y="5.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".25"/></filter><filter id="iI9C5xd" width="2.166" height="2.166" x="16.62" y="5.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/></filter><filter id="icRwZIe" width="2.142" height="2.142" x="16.507" y="5.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".25"/></filter><filter id="iOU2gqe" width="5.952" height="7.001" x="11.884" y="3.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.235294 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/></filter><filter id="iNMlzNe" width="6.436" height="5.76" x="12.941" y="1.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation="1"/></filter><filter id="iSL6Iqc" width="7.231" height="5.115" x="11.229" y="1.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/></filter><filter id="iWOpbAb" width="2.51" height="3.038" x="13.452" y="5.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".375"/></filter><filter id="iTzsgQT" width="1.277" height="1.738" x="14.205" y="6.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".05"/></filter><filter id="idZEw5c" width="1.816" height="1.245" x="15.522" y="4.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/></filter><filter id="iX2WDSb" width="1.816" height="1.245" x="12.569" y="4.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1295"/></filter><filter id="iP87Pbd" width=".537" height=".485" x="15.63" y="6.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".05"/></filter><filter id="io9eFLb" width=".682" height=".695" x="16.07" y="6.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".1"/></filter><filter id="iPFl77w" width=".736" height=".767" x="13.521" y="6.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".1"/></filter><filter id="ic0vYNe" width=".609" height=".489" x="13.13" y="6.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".05"/></filter><filter id="ibLKNKe" width="1.511" height=".697" x="15.572" y="5.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".075"/></filter><filter id="iXUT6xd" width="1.556" height=".73" x="12.577" y="5.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".075"/></filter><filter id="iJsRMKp" width=".898" height="1.622" x="11.72" y="3.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1295" stdDeviation=".125"/></filter><linearGradient id="ieE0Yhd" x1="9.112" x2="18.219" y1="27.035" y2="28.878" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iRHdtfb" x1="7.862" x2="5.547" y1="25.828" y2="25.456" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="ieanqtr" x1="11.357" x2="10.826" y1="24.165" y2="26.275" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iFRANrb" x1="25.417" x2="25.113" y1="20.668" y2="20.668" gradientUnits="userSpaceOnUse"><stop class="y_8gxtivd"/><stop offset="1" class="rtj1uebvi"/></linearGradient><linearGradient id="ivPc5hd" x1="25.472" x2="25.472" y1="13.207" y2="16.02" gradientUnits="userSpaceOnUse"><stop class="yuhnzydjs"/><stop offset="1" class="gbozhs6vn"/></linearGradient><linearGradient id="ilFtXie" x1="24.195" x2="25.702" y1="13.94" y2="13.94" gradientUnits="userSpaceOnUse"><stop offset=".342" class="jgx-fwbww"/><stop offset="1" class="ypw3s-8il"/></linearGradient><linearGradient id="iIZ9OKf" x1="4.021" x2="4.289" y1="16.848" y2="16.824" gradientUnits="userSpaceOnUse"><stop class="u562etbcn"/><stop offset="1" class="kpx3m6bah"/></linearGradient><linearGradient id="iKLlMZb" x1="27.226" x2="28.976" y1="3.668" y2="9.402" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset="1" class="msr886b7s"/></linearGradient><linearGradient id="iojTvld" x1="27.437" x2="27.067" y1="2.801" y2="3.017" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset="1" class="msr886b7s"/></linearGradient><linearGradient id="iW5WXXs" x1="25.17" x2="27.718" y1="3.753" y2="13.123" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset=".765" class="msr886b7s"/></linearGradient><linearGradient id="iSxRyoe" x1="21.517" x2="24.201" y1="3.135" y2="13.686" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset=".765" class="msr886b7s"/></linearGradient><linearGradient id="i8mp5Bd" x1="12.12" x2="11.752" y1="7.138" y2="7.138" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="ioPsgid" x1="18.202" x2="17.732" y1="6.352" y2="7.807" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iCwYOIe" x1="17.16" x2="12.778" y1="7.202" y2="7.855" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="i6lIdLm" x1="11.748" x2="12.828" y1="8.749" y2="8.71" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="isXaobd" x1="17.635" x2="17.029" y1="8.268" y2="8.21" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="i43HjDb" x1="14.539" x2="19.212" y1="5.489" y2="3.816" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iSawKAm" x1="14.348" x2="14.886" y1="7.58" y2="7.58" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="imjmxXb" x1="15.382" x2="14.794" y1="7.765" y2="7.757" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="is4pXUd" x1="14.956" x2="14.956" y1="8.191" y2="7.862" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iSY52fb" x1="14.249" x2="14.498" y1="9.118" y2="8.723" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iUVetDd" x1="16.54" x2="16.36" y1="6.618" y2="6.729" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iOyNDme" x1="14.017" x2="13.837" y1="6.618" y2="6.729" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1gYneb" x1="16.549" x2="16.308" y1="5.39" y2="4.897" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iJNIJeb" x1="13.506" x2="12.823" y1="5.317" y2="5.031" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="i0ZNu1d" x1="12.169" x2="12.169" y1="4.161" y2="5.399" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-merpeople-medium-dark" /></template>
<style>
.a0-6u3e5y {
  cx: 12.12px;
  cy: 6.978px;
  r: 0.571px;
}

.a2al628fd {
  fill: var(--svg-color--352827, #352827);
  d: path("m16.978 5.417l-.002-.001l-.002-.002l-.007-.006a1 1 0 0 0-.089-.061a1.63 1.63 0 0 0-1.097-.212a.306.306 0 0 0 .095.605a1 1 0 0 1 .677.126l.036.024a.306.306 0 0 0 .39-.473");
}

.a94pfab2a {
  d: path("M4.022 15.997a.517.517 0 0 1 1.033-.062l.052.87a.517.517 0 0 1-1.033.062z");
}

.a9e6g3bep {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.214 6.157c.375 0 .691.259.777.608a.157.157 0 0 1-.153.195h-1.28a.132.132 0 0 1-.13-.156a.8.8 0 0 1 .786-.647");
}

.acig8mj4m {
  cx: 17.578px;
  cy: 6.978px;
  r: 0.571px;
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.akxi8m76s {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M10.7 19.156c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.288-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.246-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.946-1.388a3.1 3.1 0 0 1-.28-1.63c.021-.213.231-.344.44-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.747 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.209.223-.141.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.844-2.724c-.063-1.812-1.563-2.515-2.57-3.148c-.524-.329-2.055-1.145-2.055-2.926");
}

.b3-b84bgv {
  width: 2.963px;
  height: 0.908px;
  x: 23.363px;
  y: 9.522px;
  fill: var(--svg-color--eca63f, #ECA63F);
  rx: 0.454px;
}

.b8bskobqr {
  stop-color: var(--svg-color--542926, #542926);
}

.btcqthbni {
  stop-color: var(--svg-color--3f1f1b, #3F1F1B);
}

.bv_sh6uhi {
  d: path("M24.808 13.016h-.5c-.53 0-.779.382-.887.863l.848.266l.042-.178a.1.1 0 0 1 .11-.076l.2.028c.078.01.136.077.136.156v.316a.473.473 0 1 0 .945 0v-.453c0-.258-.027-.461-.304-.692a1 1 0 0 0-.59-.23");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c2k06z0us {
  d: path("m25.562 3.223l-.617-.946l-.173.946z");
}

.c371ppbal {
  fill: var(--svg-color--855c4c, #855C4C);
  d: path("m20.646 13.352l-2.182-2.114c-.68-.61-1.46-.703-1.914-.836l.946 3.59c.218.185.953.848 1.585 1.453c.579.489 1.254.535 1.61.535h4.312v-2.125c-.426-.06-2.951-.278-4.12-.392a.4.4 0 0 1-.237-.11");
}

.c643mffnw {
  d: path("M10.7 19.156c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.288-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.246-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.946-1.388a3.1 3.1 0 0 1-.28-1.63c.021-.213.231-.344.44-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.747 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.209.223-.141.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.844-2.724c-.063-1.812-1.563-2.515-2.57-3.148c-.524-.329-2.055-1.145-2.055-2.926");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cg9ww2bak {
  d: path("m16.978 5.417l-.002-.001l-.002-.002l-.007-.006a1 1 0 0 0-.089-.061a1.63 1.63 0 0 0-1.097-.212a.306.306 0 0 0 .095.605a1 1 0 0 1 .677.126l.036.024a.306.306 0 0 0 .39-.473");
}

.cjh0fgb4e {
  width: 2.963px;
  height: 0.908px;
  x: 23.363px;
  y: 9.522px;
  rx: 0.454px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d_rf9vbee {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m26.827 2.582l.993.719h-.72");
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfh5jib8x {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.072 8.541c.223.116.489.183.772.183c.286 0 .549-.067.772-.183a.14.14 0 0 1 .164.027a.13.13 0 0 1 .014.165m-1.722-.192l1.68.165m-1.68-.165a.14.14 0 0 0-.164.028a.13.13 0 0 0-.014.164m.178-.192l-.136.165m1.858.027l-.042-.027m.042.027l-.042-.027m.042.027a1.14 1.14 0 0 1-.95.508c-.399 0-.749-.203-.95-.508m1.858-.027a1.09 1.09 0 0 1-.908.485c-.381 0-.716-.194-.908-.485m-.042.027v.001l.042-.028m-.042.027l.042-.027");
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.ds5elicqx {
  d: path("M16.095 6.313a.512.512 0 0 1 .494.647h-.99a.514.514 0 0 1 .496-.647");
}

.dx70v779w {
  d: path("m14.625 6.815l-.305.975a.31.31 0 0 0 .298.401h.451a.31.31 0 0 0 .3-.401l-.306-.975c-.065-.216-.37-.216-.439 0");
}

.e_um2wu8p {
  stop-color: var(--svg-color--6c3d47, #6C3D47);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e645vzbmc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.802 5.632c.188-.166.598-.34 1.106-.26");
}

.effrlx4na {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.953 2.574c0 .985-.058 1.819-.946 2.719c-1.11 1.125-.686 2.144-.562 2.422c.226.508.812 1.219 2.265 1.219");
}

.ehl3r9-ue {
  d: path("M24.359 10.43h.93v19.377a.15.15 0 0 1-.15.15h-.63a.15.15 0 0 1-.15-.15z");
}

.ehygodg_r {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.058 6.421c.036.05-.04.109-.127.174c-.086.064-.15.11-.187.061s.004-.14.09-.205c.087-.065.187-.078.224-.03");
}

.est74jqyf {
  d: path("m17.609 3.261l.246.123c.431.214.677.704.585 1.224l-.339 1.744c-.03.18-.149.302-.328.306h-.01s.03-.52.061-.826c.025-.249-.018-.324-.246-.55a.72.72 0 0 1-.215-.49v-.49a.33.33 0 0 0-.246-.306c-.37-.092-1.14-.245-2.247-.245c-1.108 0-1.878.153-2.247.245a.3.3 0 0 0-.246.306v.49a.6.6 0 0 1-.216.49l-.092.09c-.123.093-.185.276-.185.43c.031.336.062.826.062.826l-.028-.001a.36.36 0 0 1-.341-.305l-.339-1.745c-.061-.49.185-.979.616-1.193l.246-.123a4 4 0 0 0 .462-.336l.554-.582a1.125 1.125 0 0 1 1.261-.183c.308.092.647.092.954 0c.462-.153.985-.03 1.355.306l.461.459c.123.153.277.245.462.336");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.ezxr85bmy {
  stop-color: var(--svg-color--845b4d, #845B4D);
  stop-opacity: 0;
}

.f1ri06bus {
  stop-color: var(--svg-color--f2be56, #F2BE56);
  stop-opacity: 0;
}

.f7ghh-b7f {
  stop-color: var(--svg-color--835953, #835953);
}

.fhkyt6b1e {
  stop-color: var(--svg-color--6b4045, #6B4045);
}

.fsqmitk4x {
  stop-color: var(--svg-color--815753, #815753);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g-ne0bc-o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m18.458 12.434l1.884 1.942a.5.5 0 0 0 .359.151h3.257");
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.gbozhs6vn {
  stop-color: var(--svg-color--7f545a, #7F545A);
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gjxswab1e {
  stop-color: var(--svg-color--643d3b, #643D3B);
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.h6fiem_lc {
  d: path("M16.551 6.758a.5.5 0 0 0-.132-.266l-.15.164l.068.131z");
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.ho90xacyk {
  stop-color: var(--svg-color--8e6157, #8E6157);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.ht4ed36iq {
  d: path("M16.058 6.421c.036.05-.04.109-.127.174c-.086.064-.15.11-.187.061s.004-.14.09-.205c.087-.065.187-.078.224-.03");
}

.hzfyqre6p {
  d: path("M10.933 11.355c.775-.75 1.746-.924 2.113-.914v4.055h-1.422c-.112-.131-.218-.091-.258-.055c-.502.425-1.62 1.372-2.07 1.766s-1.208.497-1.531.5H6.13a.4.4 0 0 0-.273.108l-.472.44a.537.537 0 0 1-.748-.77l.358-.362a.102.102 0 0 0-.022-.161l-.068-.038a.32.32 0 0 0-.391.058l-.65.68a.506.506 0 0 1-.754-.674l.788-.944a.8.8 0 0 1 .518-.28l3.203-.37a.3.3 0 0 0 .172-.08c.758-.72 2.284-2.198 3.142-2.959");
}

.i87klgbfp {
  stop-color: var(--svg-color--7e5452, #7E5452);
}

.i8gxpdlwn {
  stop-color: var(--svg-color--d6803e, #D6803E);
}

.idi1sy6zn {
  fill: var(--svg-color--352827, #352827);
  d: path("M12.679 5.418v-.001l.002-.001l.002-.002l.007-.006a1 1 0 0 1 .09-.061a1.63 1.63 0 0 1 1.097-.212a.306.306 0 1 1-.096.605a1 1 0 0 0-.677.126l-.036.024a.306.306 0 0 1-.39-.472");
}

.idtkbybie {
  stop-color: var(--svg-color--5f313b, #5F313B);
  stop-opacity: 0;
}

.ik8rbzbeu {
  d: path("M12.679 5.418v-.001l.002-.001l.002-.002l.007-.006a1 1 0 0 1 .09-.061a1.63 1.63 0 0 1 1.097-.212a.306.306 0 1 1-.096.605a1 1 0 0 0-.677.126l-.036.024a.306.306 0 0 1-.39-.472");
}

.io-9ceb3b {
  stop-color: var(--svg-color--815852, #815852);
}

.isx036d_i {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M27.077 3.418c0 .383.117.883.602 1.453c.669.788 1.008 1.219 1.008 1.844c0 .398-.118 1.305-1.008 1.93");
}

.j1jnmrbau {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m14.686 6.908l-.47.975c-.06.2.08.401.28.401h.422c.199 0 .339-.203.28-.4l-.286-.976c-.06-.216-.162-.216-.226 0");
}

.jgx-fwbww {
  stop-color: var(--svg-color--855d4d, #855D4D);
}

.jk8wwdkvh {
  stop-color: var(--svg-color--ebaf51, #EBAF51);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.k_h8jt__y {
  d: path("m17.118 3.751l-1.766.589a.6.6 0 0 0 .27 1.165l1.756-.235z");
}

.keqz-8g7v {
  stop-color: var(--svg-color--e49c45, #E49C45);
}

.kf4vpey8i {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.471 6.157a.8.8 0 0 0-.777.608c-.026.1.05.195.153.195h1.28a.132.132 0 0 0 .13-.156a.804.804 0 0 0-.786-.647");
}

.kpx3m6bah {
  stop-color: var(--svg-color--653e3f, #653E3F);
  stop-opacity: 0;
}

.kt1qsbbol {
  stop-color: var(--svg-color--ebaf51, #EBAF51);
  stop-opacity: 0;
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l1mhifosa {
  stop-color: var(--svg-color--f0b438, #F0B438);
}

.l50mvkdpw {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m17.609 3.261l.246.123c.431.214.677.704.585 1.224l-.339 1.744c-.03.18-.149.302-.328.306h-.01s.03-.52.061-.826c.025-.249-.018-.324-.246-.55a.72.72 0 0 1-.215-.49v-.49a.33.33 0 0 0-.246-.306c-.37-.092-1.14-.245-2.247-.245c-1.108 0-1.878.153-2.247.245a.3.3 0 0 0-.246.306v.49a.6.6 0 0 1-.216.49l-.092.09c-.123.093-.185.276-.185.43c.031.336.062.826.062.826l-.028-.001a.36.36 0 0 1-.341-.305l-.339-1.745c-.061-.49.185-.979.616-1.193l.246-.123a4 4 0 0 0 .462-.336l.554-.582a1.125 1.125 0 0 1 1.261-.183c.308.092.647.092.954 0c.462-.153.985-.03 1.355.306l.461.459c.123.153.277.245.462.336");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7mq-8b5v {
  d: path("M11.918 6.627h.028s-.03-.49-.062-.826c0-.153.062-.336.185-.428l.092-.092a.6.6 0 0 0 .216-.49v-.49c0-.152.092-.275.246-.305c.37-.092 1.139-.245 2.247-.245s1.877.153 2.247.245a.33.33 0 0 1 .246.306v.49a.72.72 0 0 0 .215.49c.288.2.27.312.247.55c-.031.306-.062.826-.062.826h.01l-.152 2.271c-.092 1.016-.89 1.723-1.842 1.723h-1.842c-.983 0-1.75-.707-1.842-1.723z");
}

.l9l4bwbun {
  stop-color: var(--svg-color--794a56, #794A56);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.ltzv29bsf {
  d: path("M25.256 13.207a.34.34 0 0 0-.338.338v.018c0 .129.072.24.178.298c.017.009.017.04 0 .048a.34.34 0 0 0-.178.298v.018c0 .13.073.242.18.299c.007.004.005.015-.003.015a.405.405 0 0 0-.143.784c.019.008.022.041.005.052a.349.349 0 0 0 .186.645h.762a.349.349 0 0 0 .2-.636c-.035-.024-.041-.11-.01-.137a.404.404 0 0 0-.036-.634c-.026-.018-.022-.08.005-.097a.34.34 0 0 0 .166-.29v-.02a.34.34 0 0 0-.168-.291c-.026-.015-.029-.065-.005-.083a.34.34 0 0 0 .133-.269v-.018a.34.34 0 0 0-.338-.338z");
}

.luqq4ccam {
  stop-color: var(--svg-color--f6c059, #F6C059);
}

.lvdaoyblx {
  d: path("m24.646 2.19l-.753 1.019a.2.2 0 0 0 .163.319l.21-.002a.15.15 0 0 1 .152.15v3.855a1 1 0 0 1-1 1h-.032c-.902 0-1.538-.624-1.71-1.228c-.105-.37-.112-.644-.033-.905c.082-.27.275-.58.67-.983c.862-.883.866-1.887.87-3.02v-.04a.15.15 0 0 0-.243-.117l-1.3 1.025a.15.15 0 0 0 .092.268h.37c.085 0 .153.071.137.155c-.048.267-.2.693-.584 1.086c-.446.455-.75.889-.892 1.358c-.146.48-.109.943.028 1.425a2.76 2.76 0 0 0 2.661 1.967h2.772a2.76 2.76 0 0 0 2.661-1.967c.137-.482.175-.945.029-1.425c-.143-.47-.447-.903-.892-1.358a2.14 2.14 0 0 1-.585-1.086c-.015-.084.053-.155.138-.155h.37a.15.15 0 0 0 .092-.268l-1.3-1.025a.15.15 0 0 0-.243.118v.039c.004 1.133.008 2.137.87 3.02c.395.403.587.712.67.983c.079.26.072.535-.034.905c-.171.604-.798 1.228-1.776 1.228a.95.95 0 0 1-.951-.951V3.666a.15.15 0 0 1 .148-.15l.213-.002a.2.2 0 0 0 .159-.319l-.745-1.005a.25.25 0 0 0-.402 0");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lx7u95xxl {
  stop-color: var(--svg-color--845b4d, #845B4D);
}

.m3e9qlrif {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.243 4.218v.515c-.004.085-.04.276-.148.356");
}

.mb_u8gbtd {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m14.625 6.815l-.305.975a.31.31 0 0 0 .298.401h.451a.31.31 0 0 0 .3-.401l-.306-.975c-.065-.216-.37-.216-.439 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.md63exb4n {
  d: path("M14.057 6.765c0-.165-.134-.276-.17-.309l-.166.16l.102.207z");
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mq0387tuz {
  stop-color: var(--svg-color--93746c, #93746C);
  stop-opacity: 0;
}

.msr886b7s {
  stop-color: var(--svg-color--f6c059, #F6C059);
  stop-opacity: 0;
}

.mtgo0ubdn {
  cx: 17.578px;
  cy: 6.978px;
  r: 0.958px;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nnvmiz6zt {
  cx: 13.435px;
  cy: 6.532px;
  rx: 0.224px;
  ry: 0.113px;
}

.nsfj97bgf {
  cx: 17.578px;
  cy: 6.978px;
  r: 0.571px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.nvk-74bwn {
  stop-color: var(--svg-color--f2be56, #F2BE56);
}

.nwr0ulaka {
  stop-color: var(--svg-color--f0a23f, #F0A23F);
}

.ny9sszb6m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.189 24.494c.41.162 1.402.783 2.097 1.97");
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ozaj1r-nb {
  stop-color: var(--svg-color--f1c057, #F1C057);
}

.ph7r7fb0a {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M24.96 3.496v4.219c-.026.213.05.798.625 1.086c.575.287 1.211.078 1.422 0");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkl3f-q-p {
  stop-color: var(--svg-color--f1c057, #F1C057);
  stop-opacity: 0;
}

.pmht_lb4e {
  stop-color: var(--svg-color--936d64, #936D64);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.puzayy21j {
  stop-color: var(--svg-color--653536, #653536);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q6u_azx6h {
  fill: var(--svg-color--000, #000);
  d: path("M13.883 6.825a.29.29 0 0 0-.293-.293a.292.292 0 0 0-.261.428h.519a.3.3 0 0 0 .035-.135");
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qtupvmeij {
  fill: var(--svg-color--000, #000);
  d: path("M15.802 6.825c0-.163.13-.293.293-.293a.292.292 0 0 1 .26.428h-.518a.3.3 0 0 1-.035-.135");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-gax6bvb {
  d: path("m20.646 13.352l-2.182-2.114c-.68-.61-1.46-.703-1.914-.836l.946 3.59c.218.185.953.848 1.585 1.453c.579.489 1.254.535 1.61.535h4.312v-2.125c-.426-.06-2.951-.278-4.12-.392a.4.4 0 0 1-.237-.11");
}

.r4iderb0y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.773 26.93c-.007.649.436 1.948 2.266 1.948h3.177c1.01-.015 3.317-.517 4.469-2.415");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rt84dmblg {
  cx: 13.435px;
  cy: 6.532px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.224px;
  ry: 0.113px;
}

.rtj1uebvi {
  stop-color: var(--svg-color--e69440, #E69440);
  stop-opacity: 0;
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sy7qt-bzl {
  stop-color: var(--svg-color--d6803e, #D6803E);
  stop-opacity: 0;
}

.t8oj2cj7p {
  stop-color: var(--svg-color--98776c, #98776C);
  stop-opacity: 0;
}

.tfpize5dt {
  stop-color: var(--svg-color--ebad2f, #EBAD2F);
}

.tfrolbc-z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.336 23.975c-.308.353-1.133 1.1-1.885 1.832");
}

.ti8dkw8jh {
  stop-color: var(--svg-color--d77735, #D77735);
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.tz8c4ccqc {
  stop-color: var(--svg-color--98776c, #98776C);
}

.u562etbcn {
  stop-color: var(--svg-color--85635c, #85635C);
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.udxjy24sj {
  stop-color: var(--svg-color--ebad2f, #EBAD2F);
  stop-opacity: 0;
}

.ue5c2h_jl {
  stop-color: var(--svg-color--82565b, #82565B);
  stop-opacity: 0;
}

.uw8wenb6w {
  stop-color: var(--svg-color--d77735, #D77735);
  stop-opacity: 0;
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.v9ivl9bbn {
  stop-color: var(--svg-color--583630, #583630);
  stop-opacity: 0;
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vj07kubhl {
  stop-color: var(--svg-color--f8a33e, #F8A33E);
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vujuhsl8y {
  stop-color: var(--svg-color--93746c, #93746C);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w5k93kblc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.797 5.335c.246-.044.728-.031 1.06.228");
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wc9zh7c1h {
  cx: 12.12px;
  cy: 6.978px;
  r: 0.958px;
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wufs5mmvw {
  stop-color: var(--svg-color--5f313b, #5F313B);
}

.wyojejvbl {
  d: path("M12.966 10.434c-.475.528-1.424 2.02-1.424 3.763v3.052c0 .359.291.65.65.65h5.314a.65.65 0 0 0 .65-.65v-3.052c0-1.743-.95-3.235-1.424-3.763z");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xhiu3e_7t {
  stop-color: var(--svg-color--6b4347, #6B4347);
}

.xk6vuvbsk {
  d: path("M13.59 6.313a.512.512 0 0 0-.494.647h.99a.515.515 0 0 0-.496-.647");
}

.xxpmw9bmk {
  d: path("M18.661 26.73c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.485 3.187-.927 4.927-1.469 5.343");
}

.y_8gxtivd {
  stop-color: var(--svg-color--cc802a, #CC802A);
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y63dx6x-v {
  stop-color: var(--svg-color--936d64, #936D64);
  stop-opacity: 0;
}

.y6s2lqb2q {
  stop-color: var(--svg-color--653536, #653536);
  stop-opacity: 0;
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ypw3s-8il {
  stop-color: var(--svg-color--876151, #876151);
}

.yuhnzydjs {
  stop-color: var(--svg-color--8c695a, #8C695A);
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.ztklvab2u {
  d: path("M11.885 5.801c0-.153.061-.336.184-.428l.092-.092a.6.6 0 0 0 .216-.49v-.49c0-.152.092-.275.246-.305c.37-.092 1.139-.245 2.247-.245s1.877.153 2.247.245a.33.33 0 0 1 .246.306v.49a.72.72 0 0 0 .215.49c.288.2.27.312.247.55c-.031.306-.062.826-.062.826h.01l-.152 2.271c-.092 1.016-.89 1.723-1.842 1.723h-1.842c-.983 0-1.75-.707-1.842-1.723c-.08-1.042-.115-2.087-.21-3.128");
}

</style>
