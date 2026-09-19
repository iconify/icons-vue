<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLuZoze)"><path class="akxi8m76s"/></g><path fill="url(#igX65Dc)" class="c643mffnw"/><g filter="url(#iFlfNmb)"><path fill="url(#iTOCd4d)" class="xxpmw9bmk"/></g><g filter="url(#iV4LR9c)"><path stroke="url(#ieE0Yhd)" class="r4iderb0y"/></g><g filter="url(#iF8XdQe)"><path stroke="url(#iRHdtfb)" class="ny9sszb6m"/></g><g filter="url(#ioENVAd)"><path stroke="url(#ieanqtr)" class="tfrolbc-z"/></g><g filter="url(#iz4w7fc)"><path class="ql-_o7ali"/><path fill="url(#iO9hmbe)" class="r-gax6bvb"/></g><path fill="url(#iiMzX4d)" class="ehl3r9-ue"/><path fill="url(#iIF5Vwd)" class="ehl3r9-ue"/><path fill="url(#ios9MOa)" class="ehl3r9-ue"/><path fill="url(#iFRANrb)" class="ehl3r9-ue"/><g filter="url(#iFyMlee)"><rect class="b3-b84bgv"/><rect fill="url(#iO0H3lc)" class="cjh0fgb4e"/></g><g filter="url(#isfm9ed)"><path fill="url(#iXfqq3j)" class="lvdaoyblx"/><path fill="url(#iMBqliN)" class="lvdaoyblx"/><path fill="url(#ikHIUre)" class="lvdaoyblx"/></g><g filter="url(#iHd6Q9d)"><path fill="url(#ilp5BAd)" class="ltzv29bsf"/><path fill="url(#ilDhFZd)" class="ltzv29bsf"/><path fill="url(#iBVRMtd)" class="ltzv29bsf"/><path fill="url(#iAI60sb)" class="ltzv29bsf"/><path fill="url(#i3xNitd)" class="ltzv29bsf"/></g><path fill="url(#ij6d8Vd)" class="bv_sh6uhi"/><path fill="url(#ifmoUMc)" class="bv_sh6uhi"/><path fill="url(#iRhTRoe)" class="a94pfab2a"/><path fill="url(#ilSyu0c)" class="a94pfab2a"/><g filter="url(#iL29LKe)"><path fill="url(#ijoMcHF)" class="hzfyqre6p"/><path fill="url(#i2sgFcc)" class="hzfyqre6p"/></g><path fill="url(#ic7Jcbd)" class="wyojejvbl"/><path fill="url(#iJPTO8v)" class="wyojejvbl"/><g filter="url(#iCVo2tb)"><path stroke="url(#iKLlMZb)" class="isx036d_i"/></g><g filter="url(#ikKrKGb)"><path stroke="url(#iojTvld)" class="d_rf9vbee"/></g><g filter="url(#iYtpL5c)"><path fill="url(#iCybRry)" class="c2k06z0us"/></g><g filter="url(#icKshKd)"><path stroke="url(#iW5WXXs)" class="ph7r7fb0a"/></g><g filter="url(#iNd4riR)"><path stroke="url(#iSxRyoe)" class="effrlx4na"/></g><g filter="url(#iEvuCEd)"><circle fill="url(#i5Ysqze)" class="wc9zh7c1h"/></g><g filter="url(#i9OyPIb)"><circle fill="url(#ils1fYc)" class="a0-6u3e5y"/></g><g filter="url(#iUMWrNe)"><circle fill="url(#icPYcfi)" class="mtgo0ubdn"/><circle fill="url(#i5Yu63q)" class="mtgo0ubdn"/></g><g filter="url(#iHgy3He)"><circle class="kwppq00ki"/><circle fill="url(#izJoB0c)" class="acig8mj4m"/><circle fill="url(#ip6iK0d)" class="acig8mj4m"/></g><g filter="url(#iwGsDSd)"><path fill="url(#iqofNBc)" class="l7mq-8b5v"/><path fill="url(#iHb1Aeb)" class="l7mq-8b5v"/><path fill="url(#iKYOWKb)" class="l7mq-8b5v"/><path fill="url(#imfQlIe)" class="l7mq-8b5v"/><path fill="url(#ihQME9d)" class="l7mq-8b5v"/><path fill="url(#i2iXmBc)" class="l7mq-8b5v"/></g><g filter="url(#iahYUzc)"><path fill="url(#i9zrwib)" class="k_h8jt__y"/></g><g filter="url(#iuSMwcc)"><path class="p9xu7-bqr"/><path fill="url(#i1iSwpb)" class="est74jqyf"/><path fill="url(#ieRUPuc)" class="est74jqyf"/><path fill="url(#i1872kb)" class="est74jqyf"/><path fill="url(#iPHbR1d)" class="est74jqyf"/></g><g filter="url(#iYivYvp)"><path class="b9ufqacgb"/></g><path class="i-ytc1bck"/><path fill="url(#i1VuIOd)" class="dx70v779w"/><path fill="url(#iursPmu)" class="dx70v779w"/><path fill="url(#iPtRa1D)" class="dx70v779w"/><path fill="url(#imE7Qjb)" class="dx70v779w"/><path fill="url(#idcqShb)" class="dx70v779w"/><path stroke="url(#iVY4Z7d)" class="dnoby_beq"/><path class="p68--9buh"/><g filter="url(#iFyQ33d)"><path class="dkwu9dbsi"/></g><g filter="url(#iMX4gdb)"><path class="t5o4bzbue"/></g><path class="a9e6g3bep"/><path fill="url(#i9MuLWD)" class="ds5elicqx"/><path class="bo-tteb2e"/><g filter="url(#i1lxqZb)"><path class="z9yhrsb2j"/><path fill="url(#iDdY4wc)" class="om7qvhvfi"/></g><g filter="url(#ibB5Cac)"><path fill="url(#i6xGKkb)" class="cc-5ijbhv"/></g><path class="kf4vpey8i"/><path fill="url(#ixKg9wU)" class="xk6vuvbsk"/><path class="q6u_azx6h"/><g filter="url(#iHRMQwd)"><path fill="url(#ixu0Ldd)" class="h2newi9mz"/></g><g filter="url(#idjid4d)"><ellipse transform="rotate(-27.914 13.434 6.532)" class="weorttrer"/><ellipse fill="url(#iMXQkLe)" transform="rotate(-27.914 13.434 6.532)" class="vvg03jbmu"/></g><g filter="url(#iMRVxWt)"><path stroke="url(#iO21sze)" class="wheetzimf"/></g><g filter="url(#iXdlLwd)"><path stroke="url(#ihIxLWg)" class="f1_bagbab"/></g><g filter="url(#iSs89vb)"><path stroke="url(#ihUY80c)" class="m3e9qlrif"/></g><g filter="url(#iafu6jc)"><path stroke="url(#iS5j2Pe)" class="g-ne0bc-o"/></g><defs><radialGradient id="igX65Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 86.56 -14.38)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="iTOCd4d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 20.046 20.637)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="iO9hmbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.84375 -.25 1.01869 7.51283 17.208 13.027)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="bka6bxbcy"/><stop offset="1" class="yy97x_b7x"/></radialGradient><radialGradient id="iiMzX4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.5273 1.08984 0 24.823 29.957)" gradientUnits="userSpaceOnUse"><stop class="vj07kubhl"/><stop offset="1" class="keqz-8g7v"/></radialGradient><radialGradient id="iIF5Vwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -17.8945 2.43359 0 24.823 28.324)" gradientUnits="userSpaceOnUse"><stop offset=".906" class="sy7qt-bzl"/><stop offset="1" class="i8gxpdlwn"/></radialGradient><radialGradient id="ios9MOa" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.3125 -1.10912 0 24.823 15.824)" gradientUnits="userSpaceOnUse"><stop class="ti8dkw8jh"/><stop offset="1" class="uw8wenb6w"/></radialGradient><radialGradient id="iO0H3lc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31815 0 0 -1.07813 26.163 9.871)" gradientUnits="userSpaceOnUse"><stop class="jk8wwdkvh"/><stop offset="1" class="kt1qsbbol"/></radialGradient><radialGradient id="iXfqq3j" cx="0" cy="0" r="1" gradientTransform="rotate(108.771 12.73 11.776)scale(5.04985 5.80366)" gradientUnits="userSpaceOnUse"><stop class="l1mhifosa"/><stop offset="1" class="nwr0ulaka"/></radialGradient><radialGradient id="iMBqliN" cx="0" cy="0" r="1" gradientTransform="matrix(2 8.14203 -5.28875 1.29912 23.35 2.088)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="tfpize5dt"/><stop offset="1" class="udxjy24sj"/></radialGradient><radialGradient id="ikHIUre" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 1 -.64044 -.57039 23.148 2.387)" gradientUnits="userSpaceOnUse"><stop offset=".048" class="ozaj1r-nb"/><stop offset="1" class="pkl3f-q-p"/></radialGradient><radialGradient id="ilDhFZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25757 0 0 -.32031 26.255 15.508)" gradientUnits="userSpaceOnUse"><stop class="dzx4x3b-q"/><stop offset="1" class="ylgm7jlye"/></radialGradient><radialGradient id="iBVRMtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06226 0 0 -.27056 26.255 14.707)" gradientUnits="userSpaceOnUse"><stop class="dzx4x3b-q"/><stop offset="1" class="ylgm7jlye"/></radialGradient><radialGradient id="iAI60sb" cx="0" cy="0" r="1" gradientTransform="matrix(-.97632 0 0 -.27344 26.255 13.98)" gradientUnits="userSpaceOnUse"><stop class="dzx4x3b-q"/><stop offset="1" class="ylgm7jlye"/></radialGradient><radialGradient id="i3xNitd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17944 0 0 -.28906 26.255 13.207)" gradientUnits="userSpaceOnUse"><stop class="dzx4x3b-q"/><stop offset="1" class="ylgm7jlye"/></radialGradient><radialGradient id="ifmoUMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.51031 0 0 -1.05273 25.702 13.94)" gradientUnits="userSpaceOnUse"><stop class="isbe3cceb"/><stop offset="1" class="bt5-dxofg"/></radialGradient><radialGradient id="iRhTRoe" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -.26562 .64937 1.60434 4.241 16.746)" gradientUnits="userSpaceOnUse"><stop class="ba5oinbjy"/><stop offset="1" class="py4o8r3-v"/></radialGradient><radialGradient id="ijoMcHF" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -3.1875 1.21246 2.63887 4.726 16.2)" gradientUnits="userSpaceOnUse"><stop class="c825x_9dc"/><stop offset="1" class="q5s3dbofm"/></radialGradient><radialGradient id="i2sgFcc" cx="0" cy="0" r="1" gradientTransform="rotate(138.102 3.518 9.165)scale(4.49229 1.70257)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="r02a4rbbd"/><stop offset="1" class="zdbgnmb9c"/></radialGradient><radialGradient id="ic7Jcbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 8.28125 -6.68817 1.3124 17.32 12.074)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="s3xe04bqa"/><stop offset="1" class="mqyaf0btj"/></radialGradient><radialGradient id="iJPTO8v" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49805 1.0781 -.58371 -1.3525 14.849 10.121)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="bugud5udq"/><stop offset="1" class="qszjc-b0t"/></radialGradient><radialGradient id="iCybRry" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 .23438 -.46507 -.83711 25.304 2.816)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="nvk-74bwn"/><stop offset="1" class="f1ri06bus"/></radialGradient><radialGradient id="i5Ysqze" cx="0" cy="0" r="1" gradientTransform="matrix(1.0069 0 0 1.76209 11.162 6.978)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="i5Yu63q" cx="0" cy="0" r="1" gradientTransform="matrix(.47434 -.3454 .39422 .5414 17.792 6.826)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="izJoB0c" cx="0" cy="0" r="1" gradientTransform="matrix(.47122 -.86671 .50729 .2758 17.555 7.45)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="ip6iK0d" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 .304 24.862)scale(.20933 .26986)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iKYOWKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.07678 -5.53401 0 14.671 6.864)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="imfQlIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.74997 .92304 0 16.19 6.249)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="ihQME9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.79805 .99245 0 13.575 6.23)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="i2iXmBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.63014 -.3941 .23156 -.95782 17.293 10.513)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="i1iSwpb" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 11.686 -9.007)scale(1.75712 .6516)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ieRUPuc" cx="0" cy="0" r="1" gradientTransform="matrix(2.1946 .20196 -.1086 1.18002 16.395 3.612)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i1872kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96347 -1.49215 0 14.844 2.043)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iPHbR1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.76376 -1.29253 2.02497 2.76324 11.144 5.955)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="imE7Qjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .11298 -.36297 0 15.032 7.9)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="i9MuLWD" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46541 -.74029 0 16.094 6.587)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iDdY4wc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13256 -.17082 .23518 -.1825 15.962 6.635)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixKg9wU" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46543 -.74032 0 13.59 6.587)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iMXQkLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00442 -.2824 .33946 -.00531 13.426 6.712)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iS5j2Pe" cx="0" cy="0" r="1" gradientTransform="matrix(4.84376 2.56248 -.9379 1.77288 19.114 12.808)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="cozfv0ytz"/><stop offset=".93" class="bkktwff2j"/></radialGradient><filter id="iLuZoze" width="16.97" height="13.626" x="4.983" y="16.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1292" result="effect2_innerShadow_4002_1292"/></filter><filter id="iFlfNmb" width="8.803" height="12.453" x="12.427" y="15.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".5"/></filter><filter id="iV4LR9c" width="11.112" height="3.615" x="8.173" y="25.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".2"/></filter><filter id="iF8XdQe" width="3.297" height="3.17" x="5.589" y="23.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".2"/></filter><filter id="ioENVAd" width="3.085" height="3.032" x="8.851" y="23.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".2"/></filter><filter id="iz4w7fc" width="8.453" height="5.978" x="16.55" y="10.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.0980392 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1292" result="effect2_innerShadow_4002_1292"/></filter><filter id="iFyMlee" width="2.963" height="1.158" x="23.363" y="9.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.541176 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/></filter><filter id="isfm9ed" width="8.438" height="7.533" x="20.669" y="1.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.517647 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/></filter><filter id="iHd6Q9d" width="1.765" height="3.013" x="24.69" y="13.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.156863 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/></filter><filter id="iL29LKe" width="10.053" height="7.208" x="2.993" y="10.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.14902 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/></filter><filter id="iCVo2tb" width="2.209" height="5.708" x="26.777" y="3.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".1"/></filter><filter id="ikKrKGb" width="1.759" height="1.3" x="26.569" y="2.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".1"/></filter><filter id="iYtpL5c" width="1.189" height="1.345" x="24.572" y="2.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".1"/></filter><filter id="icKshKd" width="2.586" height="5.952" x="24.656" y="3.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".1"/></filter><filter id="iNd4riR" width="2.948" height="6.859" x="20.962" y="2.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".1"/></filter><filter id="iEvuCEd" width="2.116" height="1.916" x="11.162" y="6.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/></filter><filter id="i9OyPIb" width="2.142" height="2.142" x="11.049" y="5.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".25"/></filter><filter id="iUMWrNe" width="2.166" height="2.166" x="16.62" y="5.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/></filter><filter id="iHgy3He" width="2.142" height="2.142" x="16.507" y="5.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".25"/></filter><filter id="iwGsDSd" width="5.952" height="7.001" x="11.884" y="3.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/></filter><filter id="iahYUzc" width="4.436" height="3.76" x="13.941" y="2.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".5"/></filter><filter id="iuSMwcc" width="7.231" height="5.115" x="11.229" y="1.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/></filter><filter id="iYivYvp" width="2.51" height="3.038" x="13.452" y="5.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".375"/></filter><filter id="iFyQ33d" width="1.816" height="1.245" x="15.522" y="4.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/></filter><filter id="iMX4gdb" width="1.816" height="1.245" x="12.569" y="4.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1292"/></filter><filter id="i1lxqZb" width=".535" height=".484" x="15.63" y="6.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".05"/></filter><filter id="ibB5Cac" width=".681" height=".693" x="16.07" y="6.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".1"/></filter><filter id="iHRMQwd" width=".735" height=".766" x="13.521" y="6.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".1"/></filter><filter id="idjid4d" width=".608" height=".488" x="13.131" y="6.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".05"/></filter><filter id="iMRVxWt" width="1.911" height="1.097" x="15.372" y="4.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".15"/></filter><filter id="iXdlLwd" width="1.956" height="1.13" x="12.377" y="4.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".15"/></filter><filter id="iSs89vb" width=".898" height="1.622" x="11.72" y="3.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".125"/></filter><filter id="iafu6jc" width="7.3" height="3.894" x="17.558" y="11.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1292" stdDeviation=".3"/></filter><linearGradient id="ieE0Yhd" x1="9.112" x2="18.219" y1="27.035" y2="28.878" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iRHdtfb" x1="7.862" x2="5.547" y1="25.828" y2="25.456" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="ieanqtr" x1="11.357" x2="10.826" y1="24.165" y2="26.275" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iFRANrb" x1="25.417" x2="25.113" y1="20.668" y2="20.668" gradientUnits="userSpaceOnUse"><stop class="y_8gxtivd"/><stop offset="1" class="rtj1uebvi"/></linearGradient><linearGradient id="ilp5BAd" x1="25.472" x2="25.472" y1="13.207" y2="16.02" gradientUnits="userSpaceOnUse"><stop class="oy5ype34t"/><stop offset="1" class="aeahvq4la"/></linearGradient><linearGradient id="ij6d8Vd" x1="24.195" x2="25.702" y1="13.94" y2="13.94" gradientUnits="userSpaceOnUse"><stop offset=".342" class="ocrikough"/><stop offset="1" class="z_9l1gcue"/></linearGradient><linearGradient id="ilSyu0c" x1="4.021" x2="4.289" y1="16.848" y2="16.824" gradientUnits="userSpaceOnUse"><stop class="cb2xecbgy"/><stop offset="1" class="z8sdo7b7z"/></linearGradient><linearGradient id="iKLlMZb" x1="27.226" x2="28.976" y1="3.668" y2="9.402" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset="1" class="msr886b7s"/></linearGradient><linearGradient id="iojTvld" x1="27.437" x2="27.067" y1="2.801" y2="3.017" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset="1" class="msr886b7s"/></linearGradient><linearGradient id="iW5WXXs" x1="25.17" x2="27.718" y1="3.753" y2="13.123" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset=".765" class="msr886b7s"/></linearGradient><linearGradient id="iSxRyoe" x1="21.517" x2="24.201" y1="3.135" y2="13.686" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset=".765" class="msr886b7s"/></linearGradient><linearGradient id="ils1fYc" x1="12.12" x2="11.752" y1="7.138" y2="7.138" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="icPYcfi" x1="18.202" x2="17.732" y1="6.352" y2="7.807" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iqofNBc" x1="17.16" x2="12.778" y1="7.202" y2="7.855" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iHb1Aeb" x1="11.748" x2="13.048" y1="8.749" y2="8.667" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="i9zrwib" x1="15.394" x2="20.338" y1="5.264" y2="3.562" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="i1VuIOd" x1="14.348" x2="14.886" y1="7.58" y2="7.58" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iursPmu" x1="15.382" x2="14.794" y1="7.765" y2="7.757" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iPtRa1D" x1="14.956" x2="14.956" y1="8.191" y2="7.862" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="idcqShb" x1="14.916" x2="14.916" y1="8.215" y2="8.119" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="iVY4Z7d" x1="14.249" x2="14.498" y1="9.118" y2="8.723" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="i6xGKkb" x1="16.539" x2="16.36" y1="6.617" y2="6.728" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixu0Ldd" x1="14.016" x2="13.837" y1="6.617" y2="6.728" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iO21sze" x1="16.549" x2="16.308" y1="5.39" y2="4.897" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ihIxLWg" x1="13.506" x2="12.824" y1="5.317" y2="5.031" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ihUY80c" x1="12.169" x2="12.169" y1="4.161" y2="5.399" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-merpeople-dark" /></template>
<style>
.a0-6u3e5y {
  cx: 12.12px;
  cy: 6.978px;
  r: 0.571px;
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

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.aeahvq4la {
  stop-color: var(--svg-color--402630, #402630);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akxi8m76s {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M10.7 19.156c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.288-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.246-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.946-1.388a3.1 3.1 0 0 1-.28-1.63c.021-.213.231-.344.44-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.747 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.209.223-.141.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.844-2.724c-.063-1.812-1.563-2.515-2.57-3.148c-.524-.329-2.055-1.145-2.055-2.926");
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b3-b84bgv {
  width: 2.963px;
  height: 0.908px;
  x: 23.363px;
  y: 9.522px;
  fill: var(--svg-color--eca63f, #ECA63F);
  rx: 0.454px;
}

.b9ufqacgb {
  fill: var(--svg-color--332024, #332024);
  d: path("m14.686 6.908l-.47.975c-.06.2.08.401.28.401h.422c.199 0 .339-.203.28-.4l-.286-.976c-.06-.216-.162-.216-.226 0");
}

.ba5oinbjy {
  stop-color: var(--svg-color--362425, #362425);
}

.bka6bxbcy {
  stop-color: var(--svg-color--4e312f, #4E312F);
}

.bkktwff2j {
  stop-color: var(--svg-color--5e4c4b, #5E4C4B);
  stop-opacity: 0;
}

.bo-tteb2e {
  fill: var(--svg-color--000, #000);
  d: path("M15.802 6.825c0-.163.13-.293.294-.293a.292.292 0 0 1 .26.428h-.519a.3.3 0 0 1-.035-.135");
}

.bt5-dxofg {
  stop-color: var(--svg-color--604e4c, #604E4C);
  stop-opacity: 0;
}

.bugud5udq {
  stop-color: var(--svg-color--180a09, #180A09);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bv_sh6uhi {
  d: path("M24.808 13.016h-.5c-.53 0-.779.382-.887.863l.848.266l.042-.178a.1.1 0 0 1 .11-.076l.2.028c.078.01.136.077.136.156v.316a.473.473 0 1 0 .945 0v-.453c0-.258-.027-.461-.304-.692a1 1 0 0 0-.59-.23");
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c2k06z0us {
  d: path("m25.562 3.223l-.617-.946l-.173.946z");
}

.c643mffnw {
  d: path("M10.7 19.156c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.288-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.246-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.946-1.388a3.1 3.1 0 0 1-.28-1.63c.021-.213.231-.344.44-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.747 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.209.223-.141.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.844-2.724c-.063-1.812-1.563-2.515-2.57-3.148c-.524-.329-2.055-1.145-2.055-2.926");
}

.c825x_9dc {
  stop-color: var(--svg-color--452d2e, #452D2E);
}

.cb2xecbgy {
  stop-color: var(--svg-color--5a4a46, #5A4A46);
}

.cc-5ijbhv {
  d: path("M16.55 6.757a.5.5 0 0 0-.132-.265l-.148.163l.067.13z");
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
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

.cozfv0ytz {
  stop-color: var(--svg-color--5e4c4b, #5E4C4B);
}

.d_rf9vbee {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m26.827 2.582l.993.719h-.72");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dkwu9dbsi {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m16.978 5.417l-.002-.001l-.002-.002l-.007-.006a1 1 0 0 0-.089-.061a1.63 1.63 0 0 0-1.097-.212a.306.306 0 0 0 .095.605a1 1 0 0 1 .677.126l.036.024a.306.306 0 0 0 .39-.473");
}

.dnoby_beq {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.844 8.774c-.291 0-.565-.068-.795-.188c-.078-.04-.163.048-.113.12c.192.29.527.485.908.485s.716-.194.908-.485c.05-.075-.035-.16-.113-.12c-.23.12-.501.188-.795.188Z");
}

.ds5elicqx {
  d: path("M16.095 6.313a.512.512 0 0 1 .494.647h-.99a.514.514 0 0 1 .496-.647");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dx70v779w {
  d: path("m14.625 6.815l-.305.975a.31.31 0 0 0 .298.401h.451a.31.31 0 0 0 .3-.401l-.306-.975c-.065-.216-.37-.216-.439 0");
}

.dzx4x3b-q {
  stop-color: var(--svg-color--5e4c49, #5E4C49);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.effrlx4na {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.953 2.574c0 .985-.058 1.819-.946 2.719c-1.11 1.125-.686 2.144-.562 2.422c.226.508.812 1.219 2.265 1.219");
}

.ehl3r9-ue {
  d: path("M24.359 10.43h.93v19.377a.15.15 0 0 1-.15.15h-.63a.15.15 0 0 1-.15-.15z");
}

.est74jqyf {
  d: path("m17.609 3.261l.246.123c.431.214.677.704.585 1.224l-.339 1.744c-.03.18-.149.302-.328.306h-.01s.03-.52.061-.826c.025-.249-.018-.324-.246-.55a.72.72 0 0 1-.215-.49v-.49a.33.33 0 0 0-.246-.306c-.37-.092-1.14-.245-2.247-.245c-1.108 0-1.878.153-2.247.245a.3.3 0 0 0-.246.306v.49a.6.6 0 0 1-.216.49l-.092.09c-.123.093-.185.276-.185.43c.031.336.062.826.062.826l-.028-.001a.36.36 0 0 1-.341-.305l-.339-1.745c-.061-.49.185-.979.616-1.193l.246-.123a4 4 0 0 0 .462-.336l.554-.582a1.125 1.125 0 0 1 1.261-.183c.308.092.647.092.954 0c.462-.153.985-.03 1.355.306l.461.459c.123.153.277.245.462.336");
}

.f1_bagbab {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.802 5.632c.188-.166.598-.34 1.106-.26");
}

.f1ri06bus {
  stop-color: var(--svg-color--f2be56, #F2BE56);
  stop-opacity: 0;
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-ne0bc-o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m18.458 12.434l1.884 1.942a.5.5 0 0 0 .359.151h3.257");
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.h2newi9mz {
  d: path("M14.056 6.764c0-.165-.134-.275-.17-.308l-.165.16l.101.206z");
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hzfyqre6p {
  d: path("M10.933 11.355c.775-.75 1.746-.924 2.113-.914v4.055h-1.422c-.112-.131-.218-.091-.258-.055c-.502.425-1.62 1.372-2.07 1.766s-1.208.497-1.531.5H6.13a.4.4 0 0 0-.273.108l-.472.44a.537.537 0 0 1-.748-.77l.358-.362a.102.102 0 0 0-.022-.161l-.068-.038a.32.32 0 0 0-.391.058l-.65.68a.506.506 0 0 1-.754-.674l.788-.944a.8.8 0 0 1 .518-.28l3.203-.37a.3.3 0 0 0 .172-.08c.758-.72 2.284-2.198 3.142-2.959");
}

.i-ytc1bck {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m14.625 6.815l-.305.975a.31.31 0 0 0 .298.401h.451a.31.31 0 0 0 .3-.401l-.306-.975c-.065-.216-.37-.216-.439 0");
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i8gxpdlwn {
  stop-color: var(--svg-color--d6803e, #D6803E);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.isbe3cceb {
  stop-color: var(--svg-color--604e4c, #604E4C);
}

.isx036d_i {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M27.077 3.418c0 .383.117.883.602 1.453c.669.788 1.008 1.219 1.008 1.844c0 .398-.118 1.305-1.008 1.93");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jk8wwdkvh {
  stop-color: var(--svg-color--ebaf51, #EBAF51);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.k_h8jt__y {
  d: path("m17.118 3.751l-1.766.589a.6.6 0 0 0 .27 1.165l1.756-.235z");
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.keqz-8g7v {
  stop-color: var(--svg-color--e49c45, #E49C45);
}

.kf4vpey8i {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.471 6.157a.8.8 0 0 0-.777.608c-.026.1.05.195.153.195h1.28a.132.132 0 0 0 .13-.156a.804.804 0 0 0-.786-.647");
}

.kt1qsbbol {
  stop-color: var(--svg-color--ebaf51, #EBAF51);
  stop-opacity: 0;
}

.kwppq00ki {
  cx: 17.578px;
  cy: 6.978px;
  r: 0.571px;
  fill: var(--svg-color--463133, #463133);
}

.l1mhifosa {
  stop-color: var(--svg-color--f0b438, #F0B438);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7mq-8b5v {
  d: path("M11.918 6.627h.028s-.03-.49-.062-.826c0-.153.062-.336.185-.428l.092-.092a.6.6 0 0 0 .216-.49v-.49c0-.152.092-.275.246-.305c.37-.092 1.139-.245 2.247-.245s1.877.153 2.247.245a.33.33 0 0 1 .246.306v.49a.72.72 0 0 0 .215.49c.288.2.27.312.247.55c-.031.306-.062.826-.062.826h.01l-.152 2.271c-.092 1.016-.89 1.723-1.842 1.723h-1.842c-.983 0-1.75-.707-1.842-1.723z");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
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

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m3e9qlrif {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.243 4.218v.515c-.004.085-.04.276-.148.356");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mqyaf0btj {
  stop-color: var(--svg-color--432d2d, #432D2D);
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

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
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

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.ocrikough {
  stop-color: var(--svg-color--41282f, #41282F);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.om7qvhvfi {
  d: path("M16.056 6.422c.037.049-.04.108-.126.172c-.086.065-.15.11-.187.062c-.036-.049.005-.14.091-.205c.087-.065.186-.078.222-.029");
}

.oy5ype34t {
  stop-color: var(--svg-color--4d3533, #4D3533);
}

.ozaj1r-nb {
  stop-color: var(--svg-color--f1c057, #F1C057);
}

.p68--9buh {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M14.844 8.774c-.291 0-.565-.068-.795-.188c-.078-.04-.163.048-.113.12c.192.29.527.485.908.485s.716-.194.908-.485c.05-.075-.035-.16-.113-.12c-.23.12-.501.188-.795.188");
}

.p9xu7-bqr {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m17.609 3.261l.246.123c.431.214.677.704.585 1.224l-.339 1.744c-.03.18-.149.302-.328.306h-.01s.03-.52.061-.826c.025-.249-.018-.324-.246-.55a.72.72 0 0 1-.215-.49v-.49a.33.33 0 0 0-.246-.306c-.37-.092-1.14-.245-2.247-.245c-1.108 0-1.878.153-2.247.245a.3.3 0 0 0-.246.306v.49a.6.6 0 0 1-.216.49l-.092.09c-.123.093-.185.276-.185.43c.031.336.062.826.062.826l-.028-.001a.36.36 0 0 1-.341-.305l-.339-1.745c-.061-.49.185-.979.616-1.193l.246-.123a4 4 0 0 0 .462-.336l.554-.582a1.125 1.125 0 0 1 1.261-.183c.308.092.647.092.954 0c.462-.153.985-.03 1.355.306l.461.459c.123.153.277.245.462.336");
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
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

.py4o8r3-v {
  stop-color: var(--svg-color--200e10, #200E10);
}

.q5s3dbofm {
  stop-color: var(--svg-color--472f32, #472F32);
}

.q6u_azx6h {
  fill: var(--svg-color--000, #000);
  d: path("M13.883 6.825a.29.29 0 0 0-.293-.293a.292.292 0 0 0-.261.428h.519a.3.3 0 0 0 .035-.135");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.ql-_o7ali {
  fill: var(--svg-color--41282e, #41282E);
  d: path("m20.646 13.352l-2.182-2.114c-.68-.61-1.46-.703-1.914-.836l.946 3.59c.218.185.953.848 1.585 1.453c.579.489 1.254.535 1.61.535h4.312v-2.125c-.426-.06-2.951-.278-4.12-.392a.4.4 0 0 1-.237-.11");
}

.qszjc-b0t {
  stop-color: var(--svg-color--3a2624, #3A2624);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-gax6bvb {
  d: path("m20.646 13.352l-2.182-2.114c-.68-.61-1.46-.703-1.914-.836l.946 3.59c.218.185.953.848 1.585 1.453c.579.489 1.254.535 1.61.535h4.312v-2.125c-.426-.06-2.951-.278-4.12-.392a.4.4 0 0 1-.237-.11");
}

.r02a4rbbd {
  stop-color: var(--svg-color--381f21, #381F21);
}

.r4iderb0y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.773 26.93c-.007.649.436 1.948 2.266 1.948h3.177c1.01-.015 3.317-.517 4.469-2.415");
}

.rtj1uebvi {
  stop-color: var(--svg-color--e69440, #E69440);
  stop-opacity: 0;
}

.s3xe04bqa {
  stop-color: var(--svg-color--4d312e, #4D312E);
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.sy7qt-bzl {
  stop-color: var(--svg-color--d6803e, #D6803E);
  stop-opacity: 0;
}

.t5o4bzbue {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.679 5.418v-.001l.002-.001l.002-.002l.007-.006a1 1 0 0 1 .09-.061a1.63 1.63 0 0 1 1.097-.212a.306.306 0 1 1-.096.605a1 1 0 0 0-.677.126l-.036.024a.306.306 0 0 1-.39-.472");
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

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.udxjy24sj {
  stop-color: var(--svg-color--ebad2f, #EBAD2F);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uw8wenb6w {
  stop-color: var(--svg-color--d77735, #D77735);
  stop-opacity: 0;
}

.vj07kubhl {
  stop-color: var(--svg-color--f8a33e, #F8A33E);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vvg03jbmu {
  cx: 13.434px;
  cy: 6.532px;
  rx: 0.223px;
  ry: 0.113px;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wc9zh7c1h {
  cx: 12.12px;
  cy: 6.978px;
  r: 0.958px;
}

.weorttrer {
  cx: 13.434px;
  cy: 6.532px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.223px;
  ry: 0.113px;
}

.wheetzimf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.797 5.335c.246-.044.728-.031 1.06.228");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wyojejvbl {
  d: path("M12.966 10.434c-.475.528-1.424 2.02-1.424 3.763v3.052c0 .359.291.65.65.65h5.314a.65.65 0 0 0 .65-.65v-3.052c0-1.743-.95-3.235-1.424-3.763z");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xk6vuvbsk {
  d: path("M13.59 6.313a.512.512 0 0 0-.494.647h.99a.515.515 0 0 0-.496-.647");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
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

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ylgm7jlye {
  stop-color: var(--svg-color--5e4c49, #5E4C49);
  stop-opacity: 0;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.yy97x_b7x {
  stop-color: var(--svg-color--4e312f, #4E312F);
  stop-opacity: 0;
}

.z_9l1gcue {
  stop-color: var(--svg-color--4f3633, #4F3633);
}

.z8sdo7b7z {
  stop-color: var(--svg-color--2c181a, #2C181A);
  stop-opacity: 0;
}

.z9yhrsb2j {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.056 6.422c.037.049-.04.108-.126.172c-.086.065-.15.11-.187.062c-.036-.049.005-.14.091-.205c.087-.065.186-.078.222-.029");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdbgnmb9c {
  stop-color: var(--svg-color--381f21, #381F21);
  stop-opacity: 0;
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
