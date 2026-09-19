<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVWWWje)"><path fill="url(#iH0BXae)" class="ggc8xgq4l"/><path fill="url(#i0KgPDV)" class="ggc8xgq4l"/></g><path fill="url(#iZiiqBd)" class="vuw6t0v1y"/><path fill="url(#irCT5uc)" class="vuw6t0v1y"/><path fill="url(#iIqRdKd)" class="vuw6t0v1y"/><path fill="url(#iu65Qjd)" class="vuw6t0v1y"/><path fill="url(#iCd2KMe)" class="vuw6t0v1y"/><path fill="url(#ifBqBrb)" class="vuw6t0v1y"/><path fill="url(#iI9COnc)" class="vuw6t0v1y"/><path fill="url(#iU9Wofc)" class="vuw6t0v1y"/><g filter="url(#iS5sk6a)"><path class="y8g-wbb8r"/></g><g filter="url(#iWD65hb)"><path class="hfocy-fft"/><path fill="url(#i0PAKwd)" class="b-qs2oboa"/><path fill="url(#iiu8APb)" class="b-qs2oboa"/><path fill="url(#iFO4a2d)" class="b-qs2oboa"/><path fill="url(#ip2NvSd)" class="b-qs2oboa"/></g><g filter="url(#ilxmssd)"><path fill="url(#is9xE7b)" class="s32t2abkc"/></g><g filter="url(#i4JCbNc)"><path stroke="url(#imFXYGh)" class="jlzky7_7f"/></g><path fill="url(#iWU560c)" class="c5dv8cb6d"/><g filter="url(#iWRbcjd)"><path class="njmxkm32c"/></g><g filter="url(#imOTChd)"><path class="nd_9beurl"/></g><path class="tngmm7b-r"/><path fill="url(#i3n1Vfd)" class="t2q95l7qm"/><path class="n_oa-xukp"/><g filter="url(#ikbxtob)"><path class="p4b1ftqwu"/><path fill="url(#iG9exdc)" class="ehrayybrd"/></g><g filter="url(#iu2Bytc)"><path fill="url(#iTh2gYd)" class="ftmylebgn"/></g><path class="n1xtcib0f"/><path fill="url(#iobcG6c)" class="xvirw0nsy"/><path class="qfde2rb0d"/><g filter="url(#iI2gakv)"><path fill="url(#itzPdmb)" class="lq-3jfbwe"/></g><g filter="url(#iEV7Rbi)"><ellipse transform="rotate(-27.914 11.415 16.595)" class="jlo0pu2an"/><ellipse fill="url(#iOdeWHc)" transform="rotate(-27.914 11.415 16.595)" class="cndb72b2f"/></g><path fill="url(#inrm6ye)" class="ltbk2o03c"/><path fill="url(#ifJRPvd)" class="ltbk2o03c"/><path fill="url(#i3zFpNQ)" class="ltbk2o03c"/><path fill="url(#iB1wVse)" class="ltbk2o03c"/><path fill="url(#i9ZYwqc)" class="ty329tbws"/><path fill="url(#iJWMjbb)" class="ty329tbws"/><g filter="url(#ima1d2d)"><path fill="url(#ilpFEjy)" class="z0yg8ixkd"/></g><g filter="url(#i2v1rvc)"><path fill="url(#ianWlFb)" class="zeomclmnm"/></g><g filter="url(#iAgfMqc)"><path class="ihh-8_8ss"/></g><g filter="url(#iC3DJUs)"><path class="anrqv4jxr"/></g><path fill="url(#i4od5Ad)" class="de4eq2nyn"/><path fill="url(#i9eWLce)" class="de4eq2nyn"/><path fill="url(#iGZsfee)" class="de4eq2nyn"/><path fill="url(#i4od5Ad)" class="de4eq2nyn"/><path fill="url(#i9eWLce)" class="de4eq2nyn"/><path fill="url(#iGZsfee)" class="de4eq2nyn"/><g filter="url(#itrqTvc)"><path fill="url(#i0o8XBd)" class="dp313qbix"/><path fill="url(#iDTbCXX)" class="dp313qbix"/></g><g filter="url(#is2vlIe)"><path fill="url(#i2tLZ1b)" class="ytnt9v71r"/></g><path fill="url(#iet0Zyd)" class="ytnt9v71r"/><path fill="url(#iwGGU4c)" class="ytnt9v71r"/><path fill="url(#iRz5SIb)" class="ytnt9v71r"/><g filter="url(#iKiuDlc)"><path fill="url(#i9R8Eme)" class="yypos9y_p"/></g><path fill="url(#iVMkb7h)" class="yypos9y_p"/><path fill="url(#imzhdQd)" class="yypos9y_p"/><path fill="url(#iUrQxlc)" class="yypos9y_p"/><path fill="url(#i0IHFkL)" class="yypos9y_p"/><path fill="url(#ieGdRqd)" class="yypos9y_p"/><g filter="url(#i5MiBbc)"><path fill="url(#if3Ubfd)" class="s6tzx7_tk"/><path fill="url(#ibywTHd)" class="s6tzx7_tk"/><path fill="url(#iJ7eTfM)" class="s6tzx7_tk"/><path fill="url(#itIhR6g)" class="s6tzx7_tk"/><path fill="url(#ipk6xJc)" class="s6tzx7_tk"/></g><g filter="url(#ihqb7pd)"><path fill="url(#ivMCLpd)" class="pquhn16ac"/></g><path fill="url(#iffJEed)" class="pquhn16ac"/><path fill="url(#ic2Q0eP)" class="pquhn16ac"/><defs><radialGradient id="iH0BXae" cx="0" cy="0" r="1" gradientTransform="matrix(-9.78252 0 0 -17.2823 21.266 18.486)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="i0KgPDV" cx="0" cy="0" r="1" gradientTransform="rotate(121.193 7.69 10.382)scale(6.29804 5.20274)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="irCT5uc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14599 2.65566 0 20.569 16.033)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iIqRdKd" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 13.937 2.19)scale(2.04495 2.22539)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iu65Qjd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 10.885 10.52)scale(15.9085 40.6383)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iCd2KMe" cx="0" cy="0" r="1" gradientTransform="matrix(6.32723 -5.45016 1.60988 1.86895 3.304 13.379)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="ifBqBrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.43852 4.6671 -1.86564 -.1753 26.358 13.034)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iI9COnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.2921 -23.702 0 16.07 13.718)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="kt5tj_b9j"/><stop offset="1" class="l0rm5dbiq"/></radialGradient><radialGradient id="iU9Wofc" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.625 -17.2749 0 16.1 13.732)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tbnxf-byb"/><stop offset="1" class="vubl-qepw"/></radialGradient><radialGradient id="iiu8APb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .45617 -1.43367 0 16.871 21.03)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="ip2NvSd" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.365 11.848)scale(3.12719 5.02565)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iWU560c" cx="0" cy="0" r="1" gradientTransform="rotate(-26.18 61.852 -19.803)scale(4.54372 18.2806)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i3n1Vfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51616 -2.41162 0 20.078 16.774)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iG9exdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4334 -.5585 .7689 -.59669 19.651 16.932)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iobcG6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51624 -2.41174 0 11.922 16.774)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iOdeWHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01446 -.92332 1.10987 -.01738 11.387 17.184)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifJRPvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.1746 4.19213 -3.99962 1.12067 24.63 16.8)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="i3zFpNQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.47217 -2.02032 1.69343 1.23398 25.303 17.818)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iB1wVse" cx="0" cy="0" r="1" gradientTransform="matrix(1.09696 -2.89737 3.87128 1.46568 25.516 18.14)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iJWMjbb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09887 0 0 -3.46033 6.814 18)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="ilpFEjy" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 2.641 9.292)scale(1.73773 1.78171)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="i4od5Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-.84218 3.75478 -8.78476 -1.97039 26.124 5.009)" gradientUnits="userSpaceOnUse"><stop class="s6vdf8bty"/><stop offset=".789" class="lxkykv_ud"/></radialGradient><radialGradient id="i9eWLce" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 .53125 -1.15317 4.54483 20.59 6.642)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="q2rl-9b2o"/><stop offset="1" class="fi285-b6u"/></radialGradient><radialGradient id="iGZsfee" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -2.625 6.33197 3.61827 22.527 10.486)" gradientUnits="userSpaceOnUse"><stop class="p6ygghbxv"/><stop offset="1" class="ih_njzbst"/></radialGradient><radialGradient id="i0o8XBd" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 2.91016 -14.53547 .85847 21.496 1.982)" gradientUnits="userSpaceOnUse"><stop class="nsg0945ca"/><stop offset="1" class="mcdrc7blw"/></radialGradient><radialGradient id="iDTbCXX" cx="0" cy="0" r="1" gradientTransform="matrix(1.45313 0 0 5.1925 21.043 3.298)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="w7pk8_-qm"/><stop offset="1" class="wfm74pxcd"/></radialGradient><radialGradient id="iet0Zyd" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 1.71875 -3.03125 4.35398 17.933 9.017)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="hc5vad6zv"/><stop offset="1" class="m71s56bwv"/></radialGradient><radialGradient id="iwGGU4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.93844 1.49148 0 24.896 14.466)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="uwloccuzy"/><stop offset="1" class="rrovopbjp"/></radialGradient><radialGradient id="iRz5SIb" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 0 0 .30337 18.996 8.642)" gradientUnits="userSpaceOnUse"><stop class="w98e9_6zv"/><stop offset="1" class="phr-zrige"/></radialGradient><radialGradient id="i9R8Eme" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28125 -.09372 .19553 -8.93238 21.808 5.548)" gradientUnits="userSpaceOnUse"><stop class="qnoj66lkr"/><stop offset="1" class="s_fkwccyi"/></radialGradient><radialGradient id="iVMkb7h" cx="0" cy="0" r="1" gradientTransform="matrix(11.55068 3.52232 -4.80864 15.76891 9.373 5.702)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="rjs9uccph"/><stop offset=".952" class="x7ia8vuzd"/></radialGradient><radialGradient id="imzhdQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.11064 -4.72815 1.61144 .37853 17.084 4.56)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></radialGradient><radialGradient id="iUrQxlc" cx="0" cy="0" r="1" gradientTransform="matrix(-.06346 1.33277 -6.75892 -.32185 9.436 7.352)" gradientUnits="userSpaceOnUse"><stop class="biviy7bfr"/><stop offset="1" class="ednzh9b6g"/></radialGradient><radialGradient id="i0IHFkL" cx="0" cy="0" r="1" gradientTransform="matrix(-13.48639 2.82409 -3.69438 -17.64244 17.782 7.48)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="rq033_icj"/><stop offset="1" class="dbmxbxbzy"/></radialGradient><radialGradient id="ieGdRqd" cx="0" cy="0" r="1" gradientTransform="matrix(.88851 -3.93483 2.3195 .52376 7.183 14.46)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="i65ehgbpk"/><stop offset="1" class="f_7o7vbro"/></radialGradient><radialGradient id="if3Ubfd" cx="0" cy="0" r="1" gradientTransform="rotate(137.988 8.681 4.67)scale(9.89862 9.45071)" gradientUnits="userSpaceOnUse"><stop class="rnyxtsb4p"/><stop offset="1" class="isvyw7ooh"/></radialGradient><radialGradient id="ibywTHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -4.75 18.683 3.455)" gradientUnits="userSpaceOnUse"><stop class="dqjzd9_8e"/><stop offset="1" class="jcrjf-b8x"/></radialGradient><radialGradient id="itIhR6g" cx="0" cy="0" r="1" gradientTransform="matrix(5.90625 .125 -.02777 1.31192 10.37 4.08)" gradientUnits="userSpaceOnUse"><stop class="qw_ssccar"/><stop offset="1" class="mvpyyqb8k"/></radialGradient><radialGradient id="ipk6xJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -.09375 .17757 2.4268 14.37 2.423)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jdd1i0reo"/><stop offset="1" class="ixxpbv8hf"/></radialGradient><radialGradient id="ivMCLpd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.06249 1.65631 -3.03846 -14.79042 14.777 2.548)" gradientUnits="userSpaceOnUse"><stop class="nsmntj3ul"/><stop offset="1" class="q9wqsddqp"/></radialGradient><radialGradient id="iffJEed" cx="0" cy="0" r="1" gradientTransform="matrix(8.03125 .96875 -1.11478 9.24187 7.496 3.205)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="atp4gmb-q"/><stop offset="1" class="qfleuzzqm"/></radialGradient><radialGradient id="ic2Q0eP" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 -2.3259 1.71042 1.99932 4.84 7.718)" gradientUnits="userSpaceOnUse"><stop class="lo97d1z0q"/><stop offset="1" class="qt9c-0dps"/></radialGradient><filter id="iVWWWje" width="20.11" height="19.349" x="6.551" y="10.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3099"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3099" result="effect2_innerShadow_4002_3099"/></filter><filter id="iS5sk6a" width="5.264" height="7.419" x="13.103" y="15.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".5"/></filter><filter id="iWD65hb" width="3.908" height="5.819" x="14.046" y="16.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".1"/></filter><filter id="ilxmssd" width="3.908" height="5.819" x="14.018" y="16.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".1"/></filter><filter id="i4JCbNc" width="6.514" height="2.505" x="12.743" y="23.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".05"/></filter><filter id="iWRbcjd" width="4.284" height="2.051" x="18.97" y="11.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3099"/></filter><filter id="imOTChd" width="4.284" height="2.023" x="9.147" y="11.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3099"/></filter><filter id="ikbxtob" width="1.297" height="1.127" x="18.793" y="16.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".05"/></filter><filter id="iu2Bytc" width="1.318" height="1.359" x="20.449" y="16.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".1"/></filter><filter id="iI2gakv" width="1.496" height="1.596" x="12.147" y="16.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".1"/></filter><filter id="iEV7Rbi" width="1.533" height="1.143" x="10.649" y="16.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".05"/></filter><filter id="ima1d2d" width="2.049" height="4.012" x="4.854" y="15.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".125"/></filter><filter id="i2v1rvc" width="2.769" height="4.557" x="24.737" y="15.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".25"/></filter><filter id="iAgfMqc" width="3.843" height="1.517" x="9.322" y="12.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".125"/></filter><filter id="iC3DJUs" width="3.843" height="1.517" x="19.186" y="12.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3099" stdDeviation=".125"/></filter><filter id="itrqTvc" width="7.307" height="5.168" x="20.66" y="1.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.8 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3099"/></filter><filter id="is2vlIe" width="12.925" height="6.714" x="14.708" y="8.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.992157 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3099"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.560784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3099" result="effect2_innerShadow_4002_3099"/></filter><filter id="iKiuDlc" width="17.006" height="13.059" x="4.349" y="1.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.45098 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3099"/></filter><filter id="i5MiBbc" width="13.757" height="8.679" x="4.499" y="1.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.588235 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3099"/></filter><filter id="ihqb7pd" width="10.523" height="5.986" x="4.599" y="1.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.619608 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3099"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.701961 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3099" result="effect2_innerShadow_4002_3099"/></filter><linearGradient id="iZiiqBd" x1="25.633" x2="20.907" y1="21.636" y2="21.636" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="i0PAKwd" x1="17.419" x2="16" y1="19.664" y2="19.664" gradientUnits="userSpaceOnUse"><stop offset=".037" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iFO4a2d" x1="16" x2="16" y1="21.876" y2="21.007" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="is9xE7b" x1="15.973" x2="15.973" y1="16.348" y2="19.194" gradientUnits="userSpaceOnUse"><stop class="ebnao173n"/><stop offset="1" class="x9x7pcbvv"/></linearGradient><linearGradient id="imFXYGh" x1="13.754" x2="14.349" y1="24.812" y2="23.252" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iTh2gYd" x1="21.531" x2="20.945" y1="16.875" y2="17.236" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itzPdmb" x1="13.313" x2="12.726" y1="16.875" y2="17.236" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inrm6ye" x1="28.028" x2="25.773" y1="16.925" y2="20.992" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="i9ZYwqc" x1="5.068" x2="7.793" y1="18.241" y2="18.003" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="ianWlFb" x1="26.122" x2="26.122" y1="16.212" y2="19.769" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="i2tLZ1b" x1="26.402" x2="15.652" y1="13.549" y2="13.549" gradientUnits="userSpaceOnUse"><stop class="qxbo6kk2p"/><stop offset="1" class="kkvh--b-a"/></linearGradient><linearGradient id="iJ7eTfM" x1="4.599" x2="8.777" y1="9.517" y2="8.548" gradientUnits="userSpaceOnUse"><stop class="d2rffhbfx"/><stop offset="1" class="m1v3gnbun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-wearing-turban-medium-dark" /></template>
<style>
.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.anrqv4jxr {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.655 13.15c-.48-.344-1.678-.95-3.094-.712");
}

.atp4gmb-q {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
  stop-opacity: 0;
}

.b-qs2oboa {
  d: path("m15.285 17.15l-.993 3.436c-.202.707.284 1.414.973 1.414h1.47c.689 0 1.175-.718.973-1.414l-.994-3.435c-.212-.761-1.206-.761-1.429 0");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.biviy7bfr {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c5dv8cb6d {
  d: path("M16 23.9c-.949 0-1.84-.224-2.59-.614c-.255-.13-.53.158-.37.39A3.54 3.54 0 0 0 16 25.257a3.54 3.54 0 0 0 2.959-1.58c.16-.243-.114-.522-.37-.391c-.75.39-1.631.613-2.59.613");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cndb72b2f {
  cx: 11.415px;
  cy: 16.595px;
  rx: 0.728px;
  ry: 0.368px;
}

.d2rffhbfx {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
}

.dbmxbxbzy {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
}

.de4eq2nyn {
  d: path("M4.795 10.61c.193 2.806 1.397 3.89 1.761 4.18c0-.514-.074-1.815.476-2.635c.801-1.197 1.711-1.286 2.601-1.286h12.96c2.465 0 3.081 1.796 3.081 2.694l-.093 1.146c.217 0 .866-.236 1.115-.727c.65-1.286 1.068-3.964 1.161-5.528s.031-2.764-1.192-4.451c-.979-1.35-2.795-2.021-4.42-2.021H10.693c-3.712 0-4.678 1.407-5.42 2.8c-.594 1.114-.675 2.201-.675 2.843c0 .76.013 2.129.196 2.985");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dp313qbix {
  d: path("m20.66 1.982l.055 2.427c1.224-.031 3.562.083 5.578 1.227c.85.482 1.29.993 1.574 1.414c-.073-.97-.367-1.895-1.202-3.047c-.979-1.35-2.795-2.021-4.42-2.021z");
}

.dqjzd9_8e {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.ebnao173n {
  stop-color: var(--svg-color--855c56, #855C56);
}

.ednzh9b6g {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
  stop-opacity: 0;
}

.ehrayybrd {
  d: path("M19.959 16.236c.119.159-.13.352-.412.563c-.282.212-.492.36-.61.201c-.12-.159.013-.459.295-.67c.283-.211.608-.253.727-.094");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.f_7o7vbro {
  stop-color: var(--svg-color--795a90, #795A90);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fi285-b6u {
  stop-color: var(--svg-color--ece8f1, #ECE8F1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftmylebgn {
  d: path("M21.567 17.331a1.57 1.57 0 0 0-.432-.865l-.486.533l.22.427z");
}

.ggc8xgq4l {
  d: path("m6.551 14.786l.005.004l-.001-.165c-.007-.59-.02-1.728.478-2.47c.802-1.197 1.713-1.286 2.604-1.286h12.977c2.128 0 2.88 1.335 3.047 2.279c-.158 3.377-.369 6.743-.58 10.12l-.025.385a7.324 7.324 0 0 1-7.27 6.365h-3.531a7.324 7.324 0 0 1-7.271-6.365c-.195-2.978-.382-5.908-.433-8.867");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hc5vad6zv {
  stop-color: var(--svg-color--bfb1c9, #BFB1C9);
}

.hfocy-fft {
  fill: var(--svg-color--7d5350, #7D5350);
  d: path("m15.285 17.15l-.993 3.436c-.202.707.284 1.414.973 1.414h1.47c.689 0 1.175-.718.973-1.414l-.994-3.435c-.212-.761-1.206-.761-1.429 0");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.i65ehgbpk {
  stop-color: var(--svg-color--795a90, #795A90);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ih_njzbst {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
  stop-opacity: 0;
}

.ihh-8_8ss {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.697 13.237c.48-.345 1.677-.95 3.093-.713");
}

.isvyw7ooh {
  stop-color: var(--svg-color--c0bbc4, #C0BBC4);
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.jcrjf-b8x {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
  stop-opacity: 0;
}

.jdd1i0reo {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
}

.jlo0pu2an {
  cx: 11.415px;
  cy: 16.595px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.728px;
  ry: 0.368px;
}

.jlzky7_7f {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.445 23.22v-.001a.36.36 0 0 0-.43.074a.33.33 0 0 0-.036.425a3.61 3.61 0 0 0 3.02 1.614a3.61 3.61 0 0 0 3.022-1.614a.335.335 0 0 0-.037-.429a.36.36 0 0 0-.43-.07a5.5 5.5 0 0 1-2.554.605a5.54 5.54 0 0 1-2.555-.605Z");
}

.kkvh--b-a {
  stop-color: var(--svg-color--ddd6e4, #DDD6E4);
}

.kt5tj_b9j {
  stop-color: var(--svg-color--764e4e, #764E4E);
  stop-opacity: 0;
}

.l0rm5dbiq {
  stop-color: var(--svg-color--784060, #784060);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lo97d1z0q {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
}

.lq-3jfbwe {
  d: path("M13.443 17.355c0-.54-.439-.899-.557-1.007l-.54.52l.332.676z");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.ltbk2o03c {
  d: path("M25.198 20.992c.123-1.989.241-3.975.345-5.964a3.008 3.008 0 0 1-.345 5.964");
}

.lxkykv_ud {
  stop-color: var(--svg-color--ebe6f2, #EBE6F2);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m1v3gnbun {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
  stop-opacity: 0;
}

.m71s56bwv {
  stop-color: var(--svg-color--e0dae8, #E0DAE8);
  stop-opacity: 0;
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcdrc7blw {
  stop-color: var(--svg-color--fafafa, #FAFAFA);
}

.mvpyyqb8k {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
  stop-opacity: 0;
}

.n_oa-xukp {
  fill: var(--svg-color--000, #000);
  d: path("M19.127 17.55c0-.53.424-.955.955-.955s.955.425.955.955c0 .16-.038.311-.106.44h-1.69a.86.86 0 0 1-.114-.44");
}

.n1xtcib0f {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.532 15.375A2.61 2.61 0 0 0 9 17.354a.512.512 0 0 0 .5.637h4.17a.43.43 0 0 0 .424-.508a2.62 2.62 0 0 0-2.562-2.108");
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nd_9beurl {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M9.626 12.714a5.2 5.2 0 0 1 3.25-.672a.518.518 0 0 1-.127 1.03a4.15 4.15 0 0 0-2.591.532a3 3 0 0 0-.171.112l-.006.003a.518.518 0 0 1-.634-.82z");
}

.njmxkm32c {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M22.976 12.918c-.328-.285-.708-.587-1.285-.769c-.569-.179-1.28-.227-2.266-.106a.518.518 0 0 0 .126 1.028c.9-.11 1.45-.053 1.829.067c.37.116.62.305.915.562a.518.518 0 1 0 .68-.782");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nsg0945ca {
  stop-color: var(--svg-color--dbdbdc, #DBDBDC);
}

.nsmntj3ul {
  stop-color: var(--svg-color--d2d1d3, #D2D1D3);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p4b1ftqwu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.959 16.236c.119.159-.13.352-.412.563c-.282.212-.492.36-.61.201c-.12-.159.013-.459.295-.67c.283-.211.608-.253.727-.094");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p6ygghbxv {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
}

.phr-zrige {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pquhn16ac {
  d: path("M4.6 7.718c.557-.67 1.563-1.613 2.897-1.974c1.879-.508 4.836-.732 6.069-.82c.449.026 1.556-.442 1.556-1.61c0-.433-.016-.89-.053-1.332h-4.375c-3.712 0-4.678 1.407-5.42 2.8c-.594 1.114-.675 2.201-.675 2.843z");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q2rl-9b2o {
  stop-color: var(--svg-color--cfcad4, #CFCAD4);
}

.q9wqsddqp {
  stop-color: var(--svg-color--b5b4b6, #B5B4B6);
}

.qfde2rb0d {
  fill: var(--svg-color--000, #000);
  d: path("M12.874 17.55a.95.95 0 0 0-.956-.955a.95.95 0 0 0-.955.955c0 .16.038.311.106.44h1.691a.95.95 0 0 0 .114-.44");
}

.qfleuzzqm {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
}

.qnoj66lkr {
  stop-color: var(--svg-color--f5f4f6, #F5F4F6);
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qt9c-0dps {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw_ssccar {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.qxbo6kk2p {
  stop-color: var(--svg-color--eee8f4, #EEE8F4);
}

.rjs9uccph {
  stop-color: var(--svg-color--d1cad9, #D1CAD9);
  stop-opacity: 0;
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rnyxtsb4p {
  stop-color: var(--svg-color--ddddde, #DDDDDE);
}

.rq033_icj {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
  stop-opacity: 0;
}

.rrovopbjp {
  stop-color: var(--svg-color--a186b8, #A186B8);
  stop-opacity: 0;
}

.s_fkwccyi {
  stop-color: var(--svg-color--cfc8d7, #CFC8D7);
}

.s32t2abkc {
  d: path("m15.258 16.918l-.993 3.436c-.203.707.284 1.413.973 1.413h1.47c.689 0 1.175-.717.972-1.413l-.993-3.436c-.213-.76-1.206-.76-1.429 0");
}

.s6tzx7_tk {
  d: path("M4.785 10.56c.457-.911 1.614-2.205 5.677-2.625c.406-.042 1.003-.06 1.672-.08c1.666-.05 3.775-.113 4.482-.593c.933-.445 1.973-3.246 1.54-5.28h-5.97L5.197 4.93C4.673 5.992 4.6 7.012 4.6 7.625c0 .745.013 2.077.186 2.936");
}

.s6vdf8bty {
  stop-color: var(--svg-color--f8f6fb, #F8F6FB);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t2q95l7qm {
  d: path("M20.082 15.883a1.668 1.668 0 0 1 1.607 2.107h-3.222a1.7 1.7 0 0 1-.06-.44c0-.917.75-1.667 1.674-1.667");
}

.tbnxf-byb {
  stop-color: var(--svg-color--784067, #784067);
  stop-opacity: 0;
}

.tngmm7b-r {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.468 15.375A2.61 2.61 0 0 1 23 17.354a.512.512 0 0 1-.5.636h-4.17a.43.43 0 0 1-.424-.507a2.61 2.61 0 0 1 2.562-2.108");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.ty329tbws {
  d: path("M6.573 15.004a3.03 3.03 0 0 0-2.601 2.986a3.007 3.007 0 0 0 2.842 3.003q-.181-2.994-.24-5.99");
}

.uwloccuzy {
  stop-color: var(--svg-color--a186b8, #A186B8);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vubl-qepw {
  stop-color: var(--svg-color--8d5a8c, #8D5A8C);
}

.vuw6t0v1y {
  d: path("m6.547 14.783l.009.007l-.001-.165c-.007-.59-.02-1.728.477-2.47c.801-1.197 1.711-1.286 2.601-1.286h12.96c2.185 0 2.917 1.412 3.055 2.358a473 473 0 0 1-.47 8.065q-.076 1.179-.15 2.361a7.32 7.32 0 0 1-7.262 6.365h-3.525a7.32 7.32 0 0 1-7.262-6.365c-.195-2.979-.382-5.91-.432-8.87");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w7pk8_-qm {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
}

.w98e9_6zv {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
}

.wfm74pxcd {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wvn8vtban {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
  stop-opacity: 0;
}

.x7ia8vuzd {
  stop-color: var(--svg-color--f1edf4, #F1EDF4);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.x9x7pcbvv {
  stop-color: var(--svg-color--855c56, #855C56);
  stop-opacity: 0;
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xvirw0nsy {
  d: path("M11.919 15.883a1.668 1.668 0 0 0-1.608 2.107h3.222a1.7 1.7 0 0 0 .06-.44a1.68 1.68 0 0 0-1.674-1.667");
}

.y8g-wbb8r {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.25 17.517l-1.104 3.435c-.189.707.264 1.413.905 1.413h1.367c.642 0 1.094-.717.906-1.413l-.924-3.435c-.198-.761-.943-.761-1.15 0");
}

.ytnt9v71r {
  d: path("M27.233 12.45c.005-1.483-1.085-2.607-1.93-3.106c-1.34-.79-3.268-1.003-4.104-.998h-1.486l-4.955.805l.256 1.719h7.579c2.465 0 3.102 1.792 3.044 2.694l-.056 1.145c.217 0 .866-.236 1.115-.727c.202-.4.383-.937.537-1.532");
}

.yypos9y_p {
  d: path("M21.189 1.982c.357 1.961.193 4.54-1.02 6.426c-.921 1.433-2.18 2.461-3.472 2.461H9.633c-.89 0-1.8.09-2.6 1.286c-.499.743-.485 1.88-.478 2.47l.001.165c-.364-.29-1.568-1.374-1.761-4.18c-.183-.856-.196-2.226-.196-2.985c0-.642.08-1.729.674-2.843c.743-1.393 1.71-2.8 5.42-2.8z");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z0yg8ixkd {
  d: path("M6.497 16.247a1.786 1.786 0 0 0 .156 3.512c-.065-1.172-.12-2.34-.156-3.512");
}

.zeomclmnm {
  d: path("M25.237 19.769q.109-1.779.207-3.557a1.786 1.786 0 0 1-.207 3.557");
}

.zz39r5b3o {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
}

</style>
