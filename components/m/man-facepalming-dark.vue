<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#itL8fTc)"><path class="piov5cblq"/><path fill="url(#iG54Ied)" class="au_9d4zci"/></g><path fill="url(#iae9Phv)" class="au_9d4zci"/><path fill="url(#iTBwIlc)" class="ar5j2xbqf"/><path fill="url(#iwrohPd)" class="ar5j2xbqf"/><g filter="url(#iOB8nFb)"><circle fill="url(#iRIGs7b)" class="fgsehyr1n"/></g><g filter="url(#izkv1Bd)"><circle fill="url(#iqe2VKc)" class="w-af_ebsi"/></g><g filter="url(#iY4bEcc)"><circle fill="url(#idCk4fR)" class="qomwhkbuy"/><circle fill="url(#iLcmGee)" class="qomwhkbuy"/></g><g filter="url(#iYQtyqc)"><circle class="c7p8b6bcg"/><circle fill="url(#iu2YwmR)" class="udof8ab5v"/><circle fill="url(#i8hCrTb)" class="udof8ab5v"/></g><g filter="url(#iAx7uod)"><path fill="url(#iKQYLZc)" class="sg24l6ijn"/><path fill="url(#idhr99b)" class="sg24l6ijn"/><path fill="url(#iw0rKke)" class="sg24l6ijn"/><path fill="url(#iAuAFlH)" class="sg24l6ijn"/><path fill="url(#iEMXiIe)" class="sg24l6ijn"/><path fill="url(#i2WPDPe)" class="sg24l6ijn"/></g><g filter="url(#i0Jz14d)"><path fill="url(#iL2ZPib)" class="v73frlbog"/></g><g filter="url(#iWDi7Ce)"><path class="iep8d2b7z"/><path fill="url(#ibGE4Pm)" class="diubl4cjd"/><path fill="url(#iNWDx8d)" class="diubl4cjd"/><path fill="url(#iivtjtb)" class="diubl4cjd"/><path fill="url(#i2jw4QP)" class="diubl4cjd"/></g><g filter="url(#iCu9tce)"><path class="rq_jr7h1o"/></g><g filter="url(#ingAJcc)"><path class="n_cws_bse"/></g><g filter="url(#iUsIdGb)"><path stroke="url(#i9ueRCb)" class="qa__rtsll"/></g><g filter="url(#iRnpXod)"><path stroke="url(#i6xir0b)" class="t1sofbcra"/></g><g filter="url(#ibbHZbb)"><path stroke="url(#izQN2Og)" class="odfon6tom"/></g><path fill="url(#iuVEInT)" class="pbzmiu-wi"/><path fill="url(#iLmHwkO)" class="pbzmiu-wi"/><g filter="url(#i51CPMe)"><path fill="url(#idiQbfc)" class="eegd6b54x"/></g><g filter="url(#ijvgmee)"><path fill="url(#irrmrKd)" clip-rule="evenodd" class="ne25_pecv"/></g><path class="o8yjtbcci"/><g filter="url(#isq0Rub)"><path class="qzoewsfzv"/><path fill="url(#iwAvpac)" class="l8wi70b-n"/><path fill="url(#ipJxIAe)" class="l8wi70b-n"/><path fill="url(#ifi2YJc)" class="l8wi70b-n"/><path fill="url(#iWDRR4E)" class="l8wi70b-n"/></g><g filter="url(#iEVe7ze)"><path fill="url(#iBn9wMc)" class="l8wi70b-n"/><path fill="url(#itIuW8d)" class="l8wi70b-n"/><path fill="url(#ikDDD9b)" class="l8wi70b-n"/><path fill="url(#iG9RwsX)" class="l8wi70b-n"/><path fill="url(#iiCULke)" class="l8wi70b-n"/><path fill="url(#i6GVmMe)" class="l8wi70b-n"/></g><path fill="url(#iMdcMwb)" class="t6z6pk8da"/><path fill="url(#ijY3QNe)" class="t6z6pk8da"/><path fill="url(#iuvhi3b)" class="ddnn8-b1a"/><path fill="url(#iyvmjTc)" class="ddnn8-b1a"/><path fill="url(#iB5YSle)" class="ddnn8-b1a"/><path fill="url(#iUdqpud)" class="ddnn8-b1a"/><g filter="url(#iEpn7yb)"><path class="ig1gfci2g"/></g><g filter="url(#ibwp05b)"><path class="c3a8zlbum"/></g><g filter="url(#iLmX33c)"><path class="lduksbcsu"/></g><g filter="url(#iOg5Oxb)"><path stroke="url(#iWojfGU)" class="f1ltlhbqm"/></g><g filter="url(#iM5pYNc)"><path stroke="url(#ipmZ5yc)" class="fdfvoirdt"/></g><defs><radialGradient id="iG54Ied" cx="0" cy="0" r="1" gradientTransform="matrix(-6.38721 2.45336 -5.57243 -14.5076 21.385 26.41)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="yo8dvabcv"/><stop offset="1" class="yzuqint-c"/></radialGradient><radialGradient id="iae9Phv" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.84375 -6.97792 0 16 18.207)" gradientUnits="userSpaceOnUse"><stop offset=".503" class="lci483bsi"/><stop offset="1" class="y0h0v45io"/></radialGradient><radialGradient id="iTBwIlc" cx="0" cy="0" r="1" gradientTransform="matrix(2.32812 3.40625 -3.8571 2.63627 14.688 20.394)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="rnjl--47p"/><stop offset=".878" class="ec0kytb4e"/></radialGradient><radialGradient id="iRIGs7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.22889 0 0 3.90057 7.838 12.982)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iLcmGee" cx="0" cy="0" r="1" gradientTransform="matrix(1.05001 -.76457 .87266 1.19846 22.514 12.646)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iu2YwmR" cx="0" cy="0" r="1" gradientTransform="matrix(1.04311 -1.91854 1.12293 .61054 21.99 14.026)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="i8hCrTb" cx="0" cy="0" r="1" gradientTransform="matrix(.32932 .32599 -.42024 .42454 22.041 12.982)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iw0rKke" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.02439 -12.2501 0 15.606 12.73)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="iAuAFlH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.66015 2.04326 0 18.969 11.367)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iEMXiIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.76657 2.19688 0 13.18 11.324)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="ibGE4Pm" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 15.824 -10.157)scale(3.88958 1.44238)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iNWDx8d" cx="0" cy="0" r="1" gradientTransform="matrix(4.858 .44705 -.24038 2.61211 19.421 5.531)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iivtjtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.13275 -3.30303 0 15.989 2.057)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="i2jw4QP" cx="0" cy="0" r="1" gradientTransform="matrix(3.90428 -2.86115 4.48249 6.11673 7.798 10.717)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iuVEInT" cx="0" cy="0" r="1" gradientTransform="matrix(-.92987 3.82055 -4.53851 -1.1046 22.424 13.945)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="iLmHwkO" cx="0" cy="0" r="1" gradientTransform="matrix(.35375 .48515 -.41214 .30052 21.524 14.27)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="irrmrKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60227 1.22796 -.50064 .65325 11.994 12.037)" gradientUnits="userSpaceOnUse"><stop class="l53bstutc"/><stop offset="1" class="m-bdpidvc"/></radialGradient><radialGradient id="iwAvpac" cx="0" cy="0" r="1" gradientTransform="matrix(1 2.48437 -.40982 .16496 15.486 11.769)" gradientUnits="userSpaceOnUse"><stop class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="ipJxIAe" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 17.314 9.613)" gradientUnits="userSpaceOnUse"><stop class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="ifi2YJc" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.595 8.8)" gradientUnits="userSpaceOnUse"><stop class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="iWDRR4E" cx="0" cy="0" r="1" gradientTransform="matrix(-.29552 3.9685 -.3574 -.02661 22.61 10.66)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="iBn9wMc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12305 8.4804 -7.48749 -1.87448 21.235 12.039)" gradientUnits="userSpaceOnUse"><stop class="wkradz6bg"/><stop offset="1" class="sl7z3ibwx"/></radialGradient><radialGradient id="itIuW8d" cx="0" cy="0" r="1" gradientTransform="matrix(1 2.48437 -.40982 .16496 15.486 11.769)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="rk9yz2b8g"/><stop offset="1" class="mleb6mb5e"/></radialGradient><radialGradient id="ikDDD9b" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 17.314 9.613)" gradientUnits="userSpaceOnUse"><stop class="rk9yz2b8g"/><stop offset="1" class="mleb6mb5e"/></radialGradient><radialGradient id="iG9RwsX" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.595 8.8)" gradientUnits="userSpaceOnUse"><stop class="rk9yz2b8g"/><stop offset="1" class="mleb6mb5e"/></radialGradient><radialGradient id="iiCULke" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 6.79 15.272)scale(3.93108 .49375)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="rk9yz2b8g"/><stop offset="1" class="mleb6mb5e"/></radialGradient><radialGradient id="i6GVmMe" cx="0" cy="0" r="1" gradientTransform="rotate(-171.87 11.552 6.882)scale(1.98874 3.13779)" gradientUnits="userSpaceOnUse"><stop class="m2_juxbhz"/><stop offset="1" class="rfz2yfljl"/></radialGradient><radialGradient id="iMdcMwb" cx="0" cy="0" r="1" gradientTransform="rotate(165.742 9.82 11.316)scale(3.42011 2.21707)" gradientUnits="userSpaceOnUse"><stop class="jyajb3b9r"/><stop offset="1" class="ltsdp7lah"/></radialGradient><radialGradient id="iyvmjTc" cx="0" cy="0" r="1" gradientTransform="matrix(2.29332 10.73456 -3.15485 .674 23.298 21.347)" gradientUnits="userSpaceOnUse"><stop class="nzzn1bz-b"/><stop offset="1" class="ec89a6biv"/></radialGradient><filter id="itL8fTc" width="20.98" height="11.16" x="6.01" y="19.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.501961 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4111"/></filter><filter id="iOB8nFb" width="4.441" height="4.241" x="7.838" y="10.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4111"/></filter><filter id="izkv1Bd" width="3.527" height="3.527" x="8.195" y="11.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".25"/></filter><filter id="iY4bEcc" width="4.491" height="4.491" x="19.921" y="10.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4111"/></filter><filter id="iYQtyqc" width="3.527" height="3.527" x="20.278" y="11.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".25"/></filter><filter id="iAx7uod" width="13.176" height="15.527" x="9.438" y="5.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4111"/></filter><filter id="i0Jz14d" width="9.393" height="7.895" x="14.205" y="3.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation="1"/></filter><filter id="iWDi7Ce" width="16.006" height="10.716" x="7.986" y="1.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4111"/></filter><filter id="iCu9tce" width="3.717" height="2.271" x="17.49" y="8.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4111"/></filter><filter id="ingAJcc" width="3.717" height="2.271" x="10.952" y="8.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4111"/></filter><filter id="iUsIdGb" width="3.249" height="1.448" x="17.648" y="8.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".15"/></filter><filter id="iRnpXod" width="3.548" height="1.72" x="10.919" y="8.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".15"/></filter><filter id="ibbHZbb" width="1.078" height="2.68" x="9.529" y="6.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".125"/></filter><filter id="i51CPMe" width="12.214" height="13.502" x="12.145" y="7.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".625"/></filter><filter id="ijvgmee" width="3.412" height="1.462" x="11.792" y="12.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.0235294 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4111"/></filter><filter id="isq0Rub" width="12.047" height="12.796" x="13.464" y="7.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.607843 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4111"/></filter><filter id="iEVe7ze" width="11.797" height="12.796" x="13.464" y="7.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0784314 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4111"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.215686 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4111" result="effect2_innerShadow_4002_4111"/></filter><filter id="iEpn7yb" width="2.469" height="5.75" x="17.844" y="8.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".25"/></filter><filter id="ibwp05b" width="2.75" height="4.625" x="15.781" y="9.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".25"/></filter><filter id="iLmX33c" width="2.844" height="3.75" x="13.969" y="11.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".25"/></filter><filter id="iOg5Oxb" width="3.688" height="7.656" x="21.064" y="11.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".25"/></filter><filter id="iM5pYNc" width="2.422" height="10.188" x="20.204" y="8.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4111" stdDeviation=".25"/></filter><linearGradient id="iwrohPd" x1="13.046" x2="14.526" y1="21.19" y2="21.19" gradientUnits="userSpaceOnUse"><stop class="exayt1mwz"/><stop offset="1" class="jhc6ulb2q"/></linearGradient><linearGradient id="iqe2VKc" x1="9.959" x2="9.145" y1="13.336" y2="13.336" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="idCk4fR" x1="23.421" x2="22.382" y1="11.595" y2="14.817" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iKQYLZc" x1="21.115" x2="11.415" y1="13.477" y2="14.922" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="idhr99b" x1="9.75" x2="12.063" y1="16.849" y2="16.63" gradientUnits="userSpaceOnUse"><stop offset=".092" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="i2WPDPe" x1="16.026" x2="16.026" y1="-7.193" y2="21.37" gradientUnits="userSpaceOnUse"><stop offset=".979" class="wvw1ebchz"/><stop offset="1" class="y2xm7ibwq"/></linearGradient><linearGradient id="iL2ZPib" x1="15.314" x2="25.658" y1="9.686" y2="5.982" gradientUnits="userSpaceOnUse"><stop class="p7wwt2b_k"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="i9ueRCb" x1="19.764" x2="19.231" y1="9.467" y2="8.376" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="i6xir0b" x1="13.027" x2="11.516" y1="9.304" y2="8.671" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="izQN2Og" x1="10.068" x2="10.068" y1="6.746" y2="9.485" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="idiQbfc" x1="18.252" x2="15.551" y1="8.525" y2="19.191" gradientUnits="userSpaceOnUse"><stop class="lmz3kcb9s"/><stop offset="1" class="lqej-hzud"/></linearGradient><linearGradient id="ijY3QNe" x1="20.454" x2="20.552" y1="19.499" y2="19.863" gradientUnits="userSpaceOnUse"><stop offset=".245" class="cif2-ibcw"/><stop offset="1" class="z12oxsbsi"/></linearGradient><linearGradient id="iuvhi3b" x1="19.704" x2="26.142" y1="28.191" y2="26.816" gradientUnits="userSpaceOnUse"><stop class="rx4h2ue1h"/><stop offset="1" class="n3x1ut3_u"/></linearGradient><linearGradient id="iB5YSle" x1="18.5" x2="19.719" y1="27.863" y2="27.488" gradientUnits="userSpaceOnUse"><stop class="dfx3e9_rs"/><stop offset="1" class="gipxjq48x"/></linearGradient><linearGradient id="iUdqpud" x1="20.154" x2="20.498" y1="20.457" y2="21.894" gradientUnits="userSpaceOnUse"><stop offset=".19" class="k68bkmf2g"/><stop offset="1" class="ll1_3bc-l"/></linearGradient><linearGradient id="iWojfGU" x1="21.939" x2="22.054" y1="13.668" y2="18.762" gradientUnits="userSpaceOnUse"><stop class="hgr8iwbbk"/><stop offset="1" class="oai-xmbha"/></linearGradient><linearGradient id="ipmZ5yc" x1="21.079" x2="21.751" y1="10.453" y2="17.672" gradientUnits="userSpaceOnUse"><stop class="hgr8iwbbk"/><stop offset="1" class="oai-xmbha"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-facepalming-dark" /></template>
<style>
.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ar5j2xbqf {
  d: path("M16 23.004c-1.438 0-2.605-.605-2.605-1.97V17.66c0-1.364 1.167-2.47 2.605-2.47s2.605 1.106 2.605 2.47v3.375c0 1.364-1.167 1.968-2.605 1.968");
}

.au_9d4zci {
  d: path("M25.99 30.006v-.39c0-5.39-4.47-9.77-9.99-9.77c-5.52.01-9.99 4.38-9.99 9.77v.39z");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c3a8zlbum {
  stroke: var(--svg-color--655553, #655553);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m16.656 10.661l1 2.875");
}

.c7p8b6bcg {
  cx: 22.042px;
  cy: 12.982px;
  r: 1.264px;
  fill: var(--svg-color--463133, #463133);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cif2-ibcw {
  stop-color: var(--svg-color--1b7db4, #1B7DB4);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.ddnn8-b1a {
  d: path("M17.317 22.576a1 1 0 0 1 .723-1.221l5.303-1.339a1 1 0 0 1 1.213.718l2.414 9.29h-7.719z");
}

.dfx3e9_rs {
  stop-color: var(--svg-color--3476ba, #3476BA);
}

.diubl4cjd {
  d: path("m22.11 4.754l.544.271c.954.474 1.5 1.558 1.295 2.71l-.75 3.861c-.066.399-.33.667-.726.677h-.023s.068-1.151.136-1.828c.056-.55-.04-.718-.545-1.22c-.272-.27-.477-.677-.477-1.084V7.057c0-.338-.272-.61-.545-.677c-.817-.203-2.52-.542-4.973-.542s-4.156.339-4.973.542c-.341.068-.545.339-.545.677v1.084c0 .407-.137.813-.477 1.084l-.205.203c-.272.204-.408.61-.408.949c.068.745.136 1.829.136 1.829l-.063-.002a.804.804 0 0 1-.755-.676l-.75-3.86c-.135-1.085.41-2.169 1.363-2.643l.545-.27c.341-.204.682-.475 1.022-.746l1.227-1.287c.75-.677 1.84-.88 2.793-.406c.681.203 1.43.203 2.112 0c1.022-.339 2.18-.068 2.998.677l1.021 1.016c.273.339.614.542 1.022.745");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ec0kytb4e {
  stop-color: var(--svg-color--302527, #302527);
}

.ec89a6biv {
  stop-color: var(--svg-color--1c9ae9, #1C9AE9);
  stop-opacity: 0;
}

.eegd6b54x {
  d: path("M17.44 8.542a.946.946 0 0 1 1.108.75l.356 1.849l-.086-1.383a.946.946 0 1 1 1.888-.117l.197 3.17l.327-.675a.989.989 0 0 1 1.78.863l-.817 1.684c-.174.42-.182.808-.19 1.218c-.009.374-.017.767-.152 1.221c-.236.796-.707 1.434-.913 1.653l-2.634.752c-2.028-.497-2.646-1.652-2.982-2.62a14 14 0 0 0-.658-1.585l-1.162-2.237a.946.946 0 1 1 1.678-.872l.194.371l-.463-1.348a.946.946 0 0 1 1.79-.614l.404 1.18l-.415-2.152a.946.946 0 0 1 .75-1.108");
}

.exayt1mwz {
  stop-color: var(--svg-color--2f1f20, #2F1F20);
}

.f1ltlhbqm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m23.876 12.566l-.937 1.89a3.56 3.56 0 0 0-.36 1.782c.079.968-.265 1.828-.64 2.234");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fdfvoirdt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m21.08 8.878l.671 8.438");
}

.fgsehyr1n {
  cx: 9.959px;
  cy: 12.982px;
  r: 2.12px;
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gipxjq48x {
  stop-color: var(--svg-color--3476ba, #3476BA);
  stop-opacity: 0;
}

.hgr8iwbbk {
  stop-color: var(--svg-color--655553, #655553);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iep8d2b7z {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m22.11 4.754l.544.271c.954.474 1.5 1.558 1.295 2.71l-.75 3.861c-.066.399-.33.667-.726.677h-.023s.068-1.151.136-1.828c.056-.55-.04-.718-.545-1.22c-.272-.27-.477-.677-.477-1.084V7.057c0-.338-.272-.61-.545-.677c-.817-.203-2.52-.542-4.973-.542s-4.156.339-4.973.542c-.341.068-.545.339-.545.677v1.084c0 .407-.137.813-.477 1.084l-.205.203c-.272.204-.408.61-.408.949c.068.745.136 1.829.136 1.829l-.063-.002a.804.804 0 0 1-.755-.676l-.75-3.86c-.135-1.085.41-2.169 1.363-2.643l.545-.27c.341-.204.682-.475 1.022-.746l1.227-1.287c.75-.677 1.84-.88 2.793-.406c.681.203 1.43.203 2.112 0c1.022-.339 2.18-.068 2.998.677l1.021 1.016c.273.339.614.542 1.022.745");
}

.ig1gfci2g {
  stroke: var(--svg-color--655553, #655553);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m18.719 8.88l.718 4");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jhc6ulb2q {
  stop-color: var(--svg-color--2f1f20, #2F1F20);
  stop-opacity: 0;
}

.jyajb3b9r {
  stop-color: var(--svg-color--489ed5, #489ED5);
}

.k68bkmf2g {
  stop-color: var(--svg-color--0792d5, #0792D5);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.l53bstutc {
  stop-color: var(--svg-color--282828, #282828);
}

.l8wi70b-n {
  d: path("M18.168 7.743a1.1 1.1 0 0 1 1.288.873l.415 2.15l-.1-1.609a1.1 1.1 0 1 1 2.195-.136l.23 3.687l.38-.785a1.15 1.15 0 1 1 2.07 1.004l-.95 1.958c-.203.488-.212.939-.222 1.417c-.01.435-.019.892-.176 1.42c-.275.925-.823 1.667-1.062 1.922l-3.063.875c-2.36-.578-3.078-1.922-3.468-3.047c-.313-.9-.641-1.604-.766-1.844l-1.351-2.602a1.1 1.1 0 0 1 1.952-1.014l.225.432l-.539-1.568a1.1 1.1 0 0 1 2.082-.714l.47 1.372l-.482-2.502a1.1 1.1 0 0 1 .872-1.289");
}

.lci483bsi {
  stop-color: var(--svg-color--115284, #115284);
}

.lduksbcsu {
  stroke: var(--svg-color--655553, #655553);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m14.844 12.692l1.094 2");
}

.ll1_3bc-l {
  stop-color: var(--svg-color--0792d5, #0792D5);
  stop-opacity: 0;
}

.lmz3kcb9s {
  stop-color: var(--svg-color--221212, #221212);
}

.lqej-hzud {
  stop-color: var(--svg-color--2b1726, #2B1726);
}

.ltsdp7lah {
  stop-color: var(--svg-color--20669e, #20669E);
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m-bdpidvc {
  stop-color: var(--svg-color--0f0914, #0F0914);
}

.m2_juxbhz {
  stop-color: var(--svg-color--6c5957, #6C5957);
}

.mleb6mb5e {
  stop-color: var(--svg-color--3f2a28, #3F2A28);
  stop-opacity: 0;
}

.n_cws_bse {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.196 9.528l.002-.001l.002-.002l.006-.005l.015-.012a2 2 0 0 1 .197-.136c.127-.08.306-.178.533-.268a3.6 3.6 0 0 1 1.896-.201a.678.678 0 1 1-.211 1.34c-.506-.08-.91.012-1.186.122a2 2 0 0 0-.392.21a.678.678 0 0 1-.862-1.046");
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n3x1ut3_u {
  stop-color: var(--svg-color--45aaed, #45AAED);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ne25_pecv {
  fill-rule: evenodd;
  d: path("M15.065 12.24c.15.109.184.319.074.469a2.02 2.02 0 0 1-1.641.828a2.05 2.05 0 0 1-1.639-.824a.336.336 0 0 1 .538-.403c.256.34.656.555 1.1.555c.457 0 .855-.216 1.099-.551a.337.337 0 0 1 .47-.075");
}

.nl6pfdccl {
  stop-color: var(--svg-color--f69202, #F69202);
}

.noux9m6yk {
  stop-color: var(--svg-color--f69202, #F69202);
  stop-opacity: 0;
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nzzn1bz-b {
  stop-color: var(--svg-color--47c9ff, #47C9FF);
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

.o8yjtbcci {
  fill: var(--svg-color--280017, #280017);
  d: path("M18.191 17.566a2.47 2.47 0 0 0-2.06-1.12c-.861 0-1.618.45-2.059 1.12c-.095.143.039.316.192.297h3.726c.164 0 .297-.144.201-.297");
}

.oai-xmbha {
  stop-color: var(--svg-color--655553, #655553);
  stop-opacity: 0;
}

.odfon6tom {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.232 6.871v1.14c-.01.189-.09.61-.328.79");
}

.p7wwt2b_k {
  stop-color: var(--svg-color--685654, #685654);
}

.pbzmiu-wi {
  d: path("M21.596 14.318c.404-.013.783-.15 1.09-.373v1.123a2.62 2.62 0 0 1-1.616 2.435q.309-.658.417-1.423z");
}

.piov5cblq {
  fill: var(--svg-color--1d79c4, #1D79C4);
  d: path("M25.99 30.006v-.39c0-5.39-4.47-9.77-9.99-9.77c-5.52.01-9.99 4.38-9.99 9.77v.39z");
}

.qa__rtsll {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M18.098 9.344c.546-.096 1.612-.069 2.35.505");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qomwhkbuy {
  cx: 22.042px;
  cy: 12.982px;
  r: 2.12px;
}

.qzoewsfzv {
  fill: var(--svg-color--ffca3d, #FFCA3D);
  d: path("M18.168 7.743a1.1 1.1 0 0 1 1.288.873l.415 2.15l-.1-1.609a1.1 1.1 0 1 1 2.195-.136l.23 3.687l.38-.785a1.15 1.15 0 1 1 2.07 1.004l-.95 1.958c-.203.488-.212.939-.222 1.417c-.01.435-.019.892-.176 1.42c-.275.925-.823 1.667-1.062 1.922l-3.063.875c-2.36-.578-3.078-1.922-3.468-3.047c-.313-.9-.641-1.604-.766-1.844l-1.351-2.602a1.1 1.1 0 0 1 1.952-1.014l.225.432l-.539-1.568a1.1 1.1 0 0 1 2.082-.714l.47 1.372l-.482-2.502a1.1 1.1 0 0 1 .872-1.289");
}

.rfz2yfljl {
  stop-color: var(--svg-color--503438, #503438);
  stop-opacity: 0;
}

.rk9yz2b8g {
  stop-color: var(--svg-color--3f2a28, #3F2A28);
}

.rnjl--47p {
  stop-color: var(--svg-color--261319, #261319);
}

.rq_jr7h1o {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m20.713 9.527l-.001-.001l-.003-.002l-.006-.005l-.015-.012a2 2 0 0 0-.196-.136a3.3 3.3 0 0 0-.534-.268a3.6 3.6 0 0 0-1.895-.201a.678.678 0 0 0 .211 1.34c.505-.08.91.012 1.186.122a2 2 0 0 1 .392.21a.678.678 0 0 0 .861-1.047");
}

.rx4h2ue1h {
  stop-color: var(--svg-color--2474c2, #2474C2);
}

.sg24l6ijn {
  d: path("m9.512 12.204l.062.002s-.068-1.084-.136-1.83c0-.338.136-.744.408-.948l.205-.203c.34-.27.477-.677.477-1.084V7.057c0-.338.204-.61.545-.677c.817-.203 2.52-.542 4.973-.542s4.156.339 4.974.542c.272.068.544.339.544.677v1.084c0 .407.205.813.477 1.084c.638.447.598.693.545 1.22c-.068.677-.136 1.829-.136 1.829h.023l-.337 5.027c-.204 2.248-1.971 3.814-4.078 3.814H13.98c-2.174 0-3.873-1.566-4.077-3.814z");
}

.sl7z3ibwx {
  stop-color: var(--svg-color--482b34, #482B34);
}

.t1sofbcra {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.469 10.002c.415-.367 1.323-.754 2.447-.575");
}

.t6z6pk8da {
  d: path("M17.88 20.502a.25.25 0 0 1 .182-.302l4.733-1.205a.25.25 0 0 1 .305.184l.274 1.13l-5.229 1.267z");
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.udof8ab5v {
  cx: 22.042px;
  cy: 12.982px;
  r: 1.264px;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.v73frlbog {
  d: path("m21.023 5.838l-3.909 1.303a1.33 1.33 0 0 0 .598 2.58l3.886-.52z");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.w-af_ebsi {
  cx: 9.959px;
  cy: 12.982px;
  r: 1.264px;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wkradz6bg {
  stop-color: var(--svg-color--4d3236, #4D3236);
}

.wvw1ebchz {
  stop-color: var(--svg-color--624d68, #624D68);
  stop-opacity: 0;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.y0h0v45io {
  stop-color: var(--svg-color--115284, #115284);
  stop-opacity: 0;
}

.y2xm7ibwq {
  stop-color: var(--svg-color--624d68, #624D68);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yo8dvabcv {
  stop-color: var(--svg-color--1d6fc7, #1D6FC7);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yzuqint-c {
  stop-color: var(--svg-color--1d6fc7, #1D6FC7);
  stop-opacity: 0;
}

.z12oxsbsi {
  stop-color: var(--svg-color--1b7db4, #1B7DB4);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
