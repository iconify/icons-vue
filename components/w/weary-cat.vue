<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ihmpl8d)" class="w4ibqacut"/><path fill="url(#isjXGZw)" class="w4ibqacut"/><path fill="url(#immrWZc)" class="w4ibqacut"/><path fill="url(#iqmTUAe)" class="w4ibqacut"/><path fill="url(#icdr91d)" class="w4ibqacut"/><path fill="url(#i4kNHGe)" class="w4ibqacut"/><g filter="url(#idzxX4d)"><rect class="aq64f915x"/></g><g filter="url(#iF5A2Ge)"><path fill="url(#iHO1LCd)" class="vafnvabsk"/></g><path fill="url(#i93yhJe)" class="btru5l8ly"/><g filter="url(#in00Eox)"><path fill="url(#iPwZ8Ac)" class="vrg0atbjl"/></g><g filter="url(#iDqwgzd)"><path class="q8cwh1bju"/></g><g filter="url(#iUrlZrb)"><path fill="url(#iXXbxub)" class="m75fkbbue"/></g><path fill="url(#ikiRBxd)" class="pfu3kxb9j"/><g filter="url(#ilSQM5X)"><ellipse fill="url(#ipUb6Td)" class="q5ov0fb1f"/></g><g filter="url(#iaMbyTs)"><path stroke="url(#iDv53Nd)" class="izy-6f32b"/></g><g filter="url(#i94xXEe)"><path stroke="url(#ip8XVol)" class="mtj_ebcdw"/></g><path stroke="url(#imYlBVj)" class="uw0v0dbky"/><g filter="url(#iN1sX4K)"><path class="bu1--t9dv"/></g><path stroke="url(#inTCPxq)" class="ge2plnlyj"/><g filter="url(#ioGI5Kd)"><path class="pe7057y4c"/></g><path stroke="url(#irVnAKd)" class="czixm5bwj"/><g filter="url(#izFRN5d)"><path class="tp7z4jq4b"/></g><g filter="url(#iLkE7Od)"><ellipse transform="scale(-1 1)rotate(-19.477 67.863 31.58)" class="i4304abpf"/></g><path stroke="url(#iflBcmb)" class="vlvlu57nf"/><g filter="url(#iZAEFJe)"><path class="ywi345bfa"/></g><g filter="url(#iGfU7ne)"><ellipse transform="scale(-1 1)rotate(-70.238 12.573 16.016)" class="i4304abpf"/></g><g filter="url(#i4neO2F)"><path fill="url(#iJAiLIb)" class="x_idwdbad"/></g><path class="sdp081yre"/><path fill="url(#iGyglPc)" class="pjoba9bfv"/><g filter="url(#iUGrp7c)"><path fill="url(#i93zVdb)" class="k3nf1gvhh"/></g><g filter="url(#iUsar3i)"><path stroke="url(#iKcKEde)" class="giiok14ms"/></g><g filter="url(#ifF6bOd)"><path class="znp7aofuq"/></g><g filter="url(#isge0ab)"><path class="foi5tjb8f"/></g><g filter="url(#iZlpofc)"><circle fill="url(#ic6oHIb)" class="dusk7-bwo"/></g><path fill="url(#iTMxFJd)" class="zcqpgtb3c"/><path fill="url(#iwcEhlI)" class="zcqpgtb3c"/><path fill="url(#iGYl0fc)" class="zcqpgtb3c"/><g filter="url(#iobCq0b)"><path class="kx7j_mbbl"/></g><g filter="url(#iyf6Nob)"><path class="kwmsszb6v"/></g><g filter="url(#itIOTVb)"><ellipse transform="rotate(-27.209 27.122 22.258)" class="nq6czfb4e"/></g><path fill="url(#iHI8LLY)" class="yt1b23z3f"/><path fill="url(#ixT8dae)" class="yt1b23z3f"/><path fill="url(#i9Mch0b)" class="yt1b23z3f"/><path fill="url(#iKXcq1d)" class="e0bz75bbx"/><path fill="url(#il3fuyd)" class="e0bz75bbx"/><path fill="url(#i7yPFNn)" class="e0bz75bbx"/><g filter="url(#iQQXiyW)"><path stroke="url(#ibDu16b)" class="swwvgmbsg"/></g><g filter="url(#iP4MGoe)"><path stroke="url(#iOP6CEs)" class="nrzl36bfr"/></g><g filter="url(#iP4MGoe)"><path stroke="url(#iOP6CEs)" class="nrzl36bfr"/></g><g filter="url(#iala2Ic)"><circle fill="url(#izwYbMc)" class="vpkdutb0i"/></g><g filter="url(#ivtlsDc)"><circle fill="url(#i4SdZ7b)" class="k__5hbbsv"/></g><circle class="n8jz7lc3p"/><circle class="c8mv3mvmd"/><rect fill="url(#iyXEGga)" class="l2vw9nbcm"/><path fill="url(#iGHjIUI)" class="rjbed8bhp"/><path fill="url(#iTcXc0b)" class="rjbed8bhp"/><path fill="url(#i8lBWUc)" class="rjbed8bhp"/><g filter="url(#idsv61d)"><ellipse transform="rotate(-27.209 9.176 22.258)" class="h516gl6vy"/></g><g filter="url(#iFTTHwb)"><path class="nz9i78bwr"/></g><g filter="url(#iyljpKb)"><path class="ezifkgktq"/></g><path fill="url(#i4Ru0wd)" class="qs6gzebns"/><path fill="url(#i3D6hdb)" class="qs6gzebns"/><path fill="url(#iVWBevb)" class="qs6gzebns"/><path fill="url(#iXOPfBc)" class="a98-gdr5f"/><path fill="url(#i1NjGjf)" class="a98-gdr5f"/><path fill="url(#iioeyIb)" class="a98-gdr5f"/><g filter="url(#iv3ozgd)"><path stroke="url(#i0GWmee)" class="sn-6zt0xa"/></g><g filter="url(#i7Vn9xb)"><path stroke="url(#igqhc4c)" class="q8p4ktboz"/></g><defs><linearGradient id="ihmpl8d" x1="7.964" x2="7.964" y1="1.06" y2="31" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ce9hnwylf"/><stop offset=".762" class="gq9h7lsld"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="isjXGZw" x1="8.884" x2="1.259" y1="11.851" y2="11.851" gradientUnits="userSpaceOnUse"><stop class="f6xjhkepg"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="immrWZc" x1="26.759" x2="30.196" y1="11.851" y2="11.851" gradientUnits="userSpaceOnUse"><stop class="f6xjhkepg"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="iqmTUAe" x1="16.02" x2="16.019" y1="-1.914" y2="30.523" gradientUnits="userSpaceOnUse"><stop offset=".771" class="og2_-db3e"/><stop offset="1" class="iedbks3oi"/></linearGradient><linearGradient id="icdr91d" x1="16.019" x2="16.019" y1="11.062" y2="32.336" gradientUnits="userSpaceOnUse"><stop offset=".854" class="stui2mbih"/><stop offset=".985" class="vc--wpv5i"/></linearGradient><linearGradient id="iHO1LCd" x1="23.437" x2="28" y1="8.964" y2="13.66" gradientUnits="userSpaceOnUse"><stop class="x5la94b6u"/><stop offset="1" class="t246kz1qf"/></linearGradient><linearGradient id="i93yhJe" x1="10.602" x2="4.743" y1="10.547" y2="10" gradientUnits="userSpaceOnUse"><stop offset=".437" class="xon4_gnbq"/><stop offset="1" class="q5x9unbmu"/></linearGradient><linearGradient id="iPwZ8Ac" x1="27.04" x2="26.444" y1="4.891" y2="7.232" gradientUnits="userSpaceOnUse"><stop offset=".286" class="j_4i6w0ng"/><stop offset="1" class="z84gitb5w"/></linearGradient><linearGradient id="iXXbxub" x1="15.751" x2="15.079" y1="21.264" y2="22.357" gradientUnits="userSpaceOnUse"><stop class="fd6xzxk0h"/><stop offset="1" class="xvb0lxf4e"/></linearGradient><linearGradient id="ipUb6Td" x1="17.204" x2="15.68" y1="19.654" y2="19.654" gradientUnits="userSpaceOnUse"><stop class="mno0o_bwq"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iDv53Nd" x1="24.29" x2="28.024" y1="23.166" y2="21.25" gradientUnits="userSpaceOnUse"><stop class="p3zloackg"/><stop offset="1" class="enakum12e"/></linearGradient><linearGradient id="ip8XVol" x1="24.29" x2="28.024" y1="24.509" y2="26.425" gradientUnits="userSpaceOnUse"><stop offset=".286" class="mlskkyb7u"/><stop offset=".818" class="enakum12e"/></linearGradient><linearGradient id="imYlBVj" x1="25.29" x2="29.527" y1="22.875" y2="20.742" gradientUnits="userSpaceOnUse"><stop offset=".751" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="inTCPxq" x1="25.074" x2="29.824" y1="24.639" y2="26.977" gradientUnits="userSpaceOnUse"><stop offset=".792" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="irVnAKd" x1="7.018" x2="2.027" y1="24.651" y2="27.148" gradientUnits="userSpaceOnUse"><stop offset=".752" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="iflBcmb" x1="6.818" x2="2.728" y1="22.859" y2="20.942" gradientUnits="userSpaceOnUse"><stop offset=".665" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="iJAiLIb" x1="23.352" x2="22.956" y1="10.768" y2="22.819" gradientUnits="userSpaceOnUse"><stop offset=".548" class="n5rbp-b1w"/><stop offset="1" class="z84gitb5w"/></linearGradient><linearGradient id="iGyglPc" x1="26.54" x2="25.29" y1="15.438" y2="11.969" gradientUnits="userSpaceOnUse"><stop class="f1yr_dbcd"/><stop offset="1" class="id4j66bti"/></linearGradient><linearGradient id="iKcKEde" x1="25.055" x2="25.055" y1="10.406" y2="12.75" gradientUnits="userSpaceOnUse"><stop offset=".432" class="g5d5gfbbl"/><stop offset="1" class="uekqj6-lf"/></linearGradient><linearGradient id="ic6oHIb" x1="22.308" x2="15.205" y1="26.938" y2="30.458" gradientUnits="userSpaceOnUse"><stop class="wuznojbzz"/><stop offset="1" class="zye_r8bid"/></linearGradient><linearGradient id="iTMxFJd" x1="28.957" x2="20.988" y1="30.403" y2="30.403" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ce9hnwylf"/><stop offset=".642" class="gq9h7lsld"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="iwcEhlI" x1="28.957" x2="20.988" y1="30.403" y2="30.563" gradientUnits="userSpaceOnUse"><stop offset=".866" class="rf5mz6bgl"/><stop offset="1" class="hwtj4dvzp"/></linearGradient><linearGradient id="iGYl0fc" x1="26.621" x2="34.809" y1="30.403" y2="30.403" gradientUnits="userSpaceOnUse"><stop class="f6xjhkepg"/><stop offset="1" class="gq9h7lsld"/></linearGradient><linearGradient id="iHI8LLY" x1="23.785" x2="22.824" y1="22" y2="22" gradientUnits="userSpaceOnUse"><stop class="zs7rcel6a"/><stop offset="1" class="m9xtv6nue"/></linearGradient><linearGradient id="ixT8dae" x1="22.34" x2="23.621" y1="22.109" y2="22.031" gradientUnits="userSpaceOnUse"><stop offset=".367" class="gay4lpblx"/><stop offset="1" class="cdidq02iw"/></linearGradient><linearGradient id="i9Mch0b" x1="23.449" x2="23.449" y1="24.219" y2="22.648" gradientUnits="userSpaceOnUse"><stop class="eympjqm2t"/><stop offset="1" class="nm_1q05pb"/></linearGradient><linearGradient id="iKXcq1d" x1="26.832" x2="25.871" y1="22" y2="22" gradientUnits="userSpaceOnUse"><stop class="zs7rcel6a"/><stop offset="1" class="m9xtv6nue"/></linearGradient><linearGradient id="il3fuyd" x1="25.433" x2="26.371" y1="22.047" y2="22.047" gradientUnits="userSpaceOnUse"><stop offset=".367" class="gay4lpblx"/><stop offset="1" class="cdidq02iw"/></linearGradient><linearGradient id="i7yPFNn" x1="26.496" x2="26.496" y1="24.219" y2="22.648" gradientUnits="userSpaceOnUse"><stop class="eympjqm2t"/><stop offset="1" class="nm_1q05pb"/></linearGradient><linearGradient id="ibDu16b" x1="27.082" x2="26.541" y1="23.305" y2="18.998" gradientUnits="userSpaceOnUse"><stop class="puetets_x"/><stop offset=".77" class="uc_38mvnw"/></linearGradient><linearGradient id="iOP6CEs" x1="24.035" x2="23.494" y1="23.305" y2="18.998" gradientUnits="userSpaceOnUse"><stop class="puetets_x"/><stop offset=".77" class="uc_38mvnw"/></linearGradient><linearGradient id="izwYbMc" x1="16.742" x2="18.069" y1="17.596" y2="26.301" gradientUnits="userSpaceOnUse"><stop class="s02xijbni"/><stop offset="1" class="y6_6kr0hz"/></linearGradient><linearGradient id="i4SdZ7b" x1="25.421" x2="26.67" y1="17.616" y2="25.814" gradientUnits="userSpaceOnUse"><stop class="s02xijbni"/><stop offset="1" class="y6_6kr0hz"/></linearGradient><linearGradient id="iGHjIUI" x1="11.012" x2="3.043" y1="30.403" y2="30.403" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ce9hnwylf"/><stop offset=".642" class="gq9h7lsld"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="iTcXc0b" x1="11.012" x2="3.043" y1="30.403" y2="30.563" gradientUnits="userSpaceOnUse"><stop offset=".866" class="rf5mz6bgl"/><stop offset="1" class="hwtj4dvzp"/></linearGradient><linearGradient id="i8lBWUc" x1="8.676" x2="16.863" y1="30.403" y2="30.403" gradientUnits="userSpaceOnUse"><stop class="f6xjhkepg"/><stop offset="1" class="gq9h7lsld"/></linearGradient><linearGradient id="i4Ru0wd" x1="5.84" x2="4.879" y1="22" y2="22" gradientUnits="userSpaceOnUse"><stop class="zs7rcel6a"/><stop offset="1" class="m9xtv6nue"/></linearGradient><linearGradient id="i3D6hdb" x1="4.394" x2="5.676" y1="22.109" y2="22.031" gradientUnits="userSpaceOnUse"><stop offset=".367" class="gay4lpblx"/><stop offset="1" class="cdidq02iw"/></linearGradient><linearGradient id="iVWBevb" x1="5.504" x2="5.504" y1="24.219" y2="22.648" gradientUnits="userSpaceOnUse"><stop class="eympjqm2t"/><stop offset="1" class="nm_1q05pb"/></linearGradient><linearGradient id="iXOPfBc" x1="8.887" x2="7.926" y1="22" y2="22" gradientUnits="userSpaceOnUse"><stop class="zs7rcel6a"/><stop offset="1" class="m9xtv6nue"/></linearGradient><linearGradient id="i1NjGjf" x1="7.488" x2="8.426" y1="22.047" y2="22.047" gradientUnits="userSpaceOnUse"><stop offset=".367" class="gay4lpblx"/><stop offset="1" class="cdidq02iw"/></linearGradient><linearGradient id="iioeyIb" x1="8.551" x2="8.551" y1="24.219" y2="22.648" gradientUnits="userSpaceOnUse"><stop class="eympjqm2t"/><stop offset="1" class="nm_1q05pb"/></linearGradient><linearGradient id="i0GWmee" x1="9.137" x2="8.595" y1="23.305" y2="18.998" gradientUnits="userSpaceOnUse"><stop class="puetets_x"/><stop offset=".77" class="uc_38mvnw"/></linearGradient><linearGradient id="igqhc4c" x1="6.09" x2="5.548" y1="23.305" y2="18.998" gradientUnits="userSpaceOnUse"><stop class="puetets_x"/><stop offset=".77" class="uc_38mvnw"/></linearGradient><filter id="idzxX4d" width="5.727" height="6.698" x="3.554" y="20.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".75"/></filter><filter id="iF5A2Ge" width="9.009" height="11.636" x="18.933" y="4.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".5"/></filter><filter id="in00Eox" width="3.417" height="4.625" x="24.805" y="4.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".5"/></filter><filter id="iDqwgzd" width="8.95" height="10.729" x="2.906" y="3.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation="1"/></filter><filter id="iUrlZrb" width="3.661" height="3.024" x="13.748" y="18.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="ilSQM5X" width="2.723" height="1.748" x="14.909" y="18.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".3"/></filter><filter id="iaMbyTs" width="6.005" height="4.013" x="23.685" y="19.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="i94xXEe" width="4.127" height="3.566" x="23.685" y="23.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="iN1sX4K" width="5.105" height="3.113" x="24.916" y="20.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="ioGI5Kd" width="5.102" height="3.119" x="24.848" y="23.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="izFRN5d" width="5.102" height="3.119" x="2.142" y="23.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="iLkE7Od" width="1.364" height="1.336" x="5.964" y="23.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="iZAEFJe" width="5.114" height="3.094" x="2.21" y="19.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="iGfU7ne" width="1.336" height="1.364" x="6.083" y="21.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="i4neO2F" width="12.585" height="22.186" x="18.102" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation="2"/></filter><filter id="iUGrp7c" width="4.825" height="7.138" x="22.409" y="6.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".3"/></filter><filter id="iUsar3i" width="4.531" height="4.734" x="22.727" y="9.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".375"/></filter><filter id="ifF6bOd" width="4.469" height="6.908" x="4.723" y="6.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="isge0ab" width="1.15" height="6.337" x="4.648" y="7.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="iZlpofc" width="10.382" height="10.382" x="17.117" y="19.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation="1"/></filter><filter id="iobCq0b" width="1.399" height="4.117" x="25.551" y="19.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="iyf6Nob" width="1.406" height="4.016" x="22.473" y="19.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="itIOTVb" width="4.951" height="5.536" x="24.646" y="19.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".75"/></filter><filter id="iQQXiyW" width=".6" height="2.811" x="26.368" y="20.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".1"/></filter><filter id="iP4MGoe" width=".6" height="2.811" x="23.321" y="20.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".1"/></filter><filter id="iala2Ic" width="8.984" height="8.984" x="6.59" y="11.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".5"/></filter><filter id="ivtlsDc" width="8.578" height="8.578" x="15.801" y="11.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".5"/></filter><filter id="idsv61d" width="4.951" height="5.536" x="6.701" y="19.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".75"/></filter><filter id="iFTTHwb" width="1.406" height="4.016" x="7.715" y="19.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="iyljpKb" width="1.406" height="4.016" x="4.598" y="19.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".25"/></filter><filter id="iv3ozgd" width=".6" height="2.811" x="8.423" y="20.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".1"/></filter><filter id="i7Vn9xb" width=".6" height="2.811" x="5.376" y="20.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6903_5272" stdDeviation=".1"/></filter><radialGradient id="i4kNHGe" cx="0" cy="0" r="1" gradientTransform="matrix(3.03126 4.46874 -8.83051 5.98995 22.165 4.218)" gradientUnits="userSpaceOnUse"><stop class="x5la94b6u"/><stop offset=".921" class="t246kz1qf"/></radialGradient><radialGradient id="ikiRBxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.89063 -.95312 .95876 -1.9018 16.446 20.092)" gradientUnits="userSpaceOnUse"><stop class="rj5_8-btj"/><stop offset="1" class="px6tpwb-q"/></radialGradient><radialGradient id="i93zVdb" cx="0" cy="0" r="1" gradientTransform="matrix(4.40625 6.46875 -7.7559 5.283 22.868 7.703)" gradientUnits="userSpaceOnUse"><stop class="n_w31cdgy"/><stop offset="1" class="prf81acwx"/></radialGradient><radialGradient id="iyXEGga" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.91493 9.37069 0 16 28.5)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:weary-cat" /></template>
<style>
.a98-gdr5f {
  d: path("M8.215 20.055a.336.336 0 1 1 .672 0v2.765a.336.336 0 1 1-.672 0z");
}

.aq64f915x {
  width: 2.727px;
  height: 3.698px;
  x: 5.054px;
  y: 21.75px;
  fill: var(--svg-color--d67908, #D67908);
  rx: 1.363px;
}

.bc88ifbby {
  stop-color: var(--svg-color--d64a38, #D64A38);
}

.btru5l8ly {
  d: path("m6.133 13.433l2.8-2.6c.32-.3.32-.78 0-1.07L5.918 7.086c-.383-.336-1.175-.227-1.175.607v5.2c0 .834.88 1.02 1.39.54");
}

.bu1--t9dv {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m25.566 22.64l3.805-1.812");
}

.c8mv3mvmd {
  cx: 11.516px;
  cy: 15.578px;
  r: 3.492px;
  fill: var(--svg-color--fff, #fff);
}

.cdidq02iw {
  stop-color: var(--svg-color--cc861f, #CC861F);
  stop-opacity: 0;
}

.ce9hnwylf {
  stop-color: var(--svg-color--f2cc26, #F2CC26);
}

.czixm5bwj {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m6.528 24.61l-3.801 1.82");
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.dusk7-bwo {
  cx: 22.308px;
  cy: 24.985px;
  r: 3.191px;
}

.e0bz75bbx {
  d: path("M26.16 20.055a.336.336 0 1 1 .672 0v2.765a.336.336 0 1 1-.672 0z");
}

.enakum12e {
  stop-color: var(--svg-color--e37d02, #E37D02);
  stop-opacity: 0;
}

.eympjqm2t {
  stop-color: var(--svg-color--ff91b9, #FF91B9);
}

.ezifkgktq {
  fill: var(--svg-color--da7600, #DA7600);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M5.098 20.344a.203.203 0 0 1 .406 0v2.61a.203.203 0 1 1-.406 0z");
}

.f1yr_dbcd {
  stop-color: var(--svg-color--ef8a47, #EF8A47);
}

.f6xjhkepg {
  stop-color: var(--svg-color--e99e20, #E99E20);
  stop-opacity: 0;
}

.fd6xzxk0h {
  stop-color: var(--svg-color--e3900e, #E3900E);
}

.foi5tjb8f {
  stroke: var(--svg-color--ffe7a3, #FFE7A3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.223 7.656v5.188");
}

.ft5dv1b6b {
  fill: none;
}

.g5d5gfbbl {
  stop-color: var(--svg-color--ffe7a3, #FFE7A3);
}

.gay4lpblx {
  stop-color: var(--svg-color--d6850e, #D6850E);
}

.ge2plnlyj {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m25.564 24.599l3.801 1.819");
}

.giiok14ms {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m23.727 10.219l2.532 2.734");
}

.gq9h7lsld {
  stop-color: var(--svg-color--e99e20, #E99E20);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h516gl6vy {
  cx: 9.176px;
  cy: 22.258px;
  fill: var(--svg-color--fdd659, #FDD659);
  rx: 0.846px;
  ry: 1.357px;
}

.hwtj4dvzp {
  stop-color: var(--svg-color--d37516, #D37516);
}

.i4304abpf {
  fill: var(--svg-color--ffdd86, #FFDD86);
  rx: 0.184px;
  ry: 0.166px;
}

.id4j66bti {
  stop-color: var(--svg-color--ef8a47, #EF8A47);
  stop-opacity: 0;
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.izy-6f32b {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m24.785 22.822l3.805-1.813");
}

.j_4i6w0ng {
  stop-color: var(--svg-color--ffe792, #FFE792);
}

.k__5hbbsv {
  cx: 20.09px;
  cy: 16.09px;
  r: 3.289px;
}

.k3nf1gvhh {
  d: path("m26.634 7.297l-3.625 3.125l3.546 2.812z");
}

.kwmsszb6v {
  fill: var(--svg-color--da7600, #DA7600);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M22.973 20.344a.203.203 0 0 1 .406 0v2.61a.203.203 0 0 1-.406 0z");
}

.kx7j_mbbl {
  fill: var(--svg-color--da7600, #DA7600);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M26.05 20.34a.2.2 0 1 1 .399 0v2.719a.2.2 0 0 1-.399 0z");
}

.l2vw9nbcm {
  width: 4.344px;
  height: 5.453px;
  x: 13.828px;
  y: 21.836px;
  rx: 2.172px;
}

.m75fkbbue {
  d: path("m14.805 19.563l.065-.015c.473-.11.966-.106 1.438.015c.52.098.832.695.392 1.125l-.55.602c-.27.27-.864.27-1.134 0l-.543-.602c-.449-.508-.168-1.015.332-1.125");
}

.m9xtv6nue {
  stop-color: var(--svg-color--e9a239, #E9A239);
  stop-opacity: 0.922;
}

.mlskkyb7u {
  stop-color: var(--svg-color--de7d07, #DE7D07);
}

.mno0o_bwq {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.9;
}

.mtj_ebcdw {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m24.785 24.853l1.927 1.366");
}

.n_w31cdgy {
  stop-color: var(--svg-color--ffdf70, #FFDF70);
}

.n5rbp-b1w {
  stop-color: var(--svg-color--ffdd65, #FFDD65);
}

.n8jz7lc3p {
  cx: 20.484px;
  cy: 15.578px;
  r: 3.492px;
  fill: var(--svg-color--fff, #fff);
}

.nm_1q05pb {
  stop-color: var(--svg-color--fd679e, #FD679E);
  stop-opacity: 0;
}

.nq6czfb4e {
  cx: 27.122px;
  cy: 22.258px;
  fill: var(--svg-color--fdd659, #FDD659);
  rx: 0.846px;
  ry: 1.357px;
}

.nrzl36bfr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M23.621 22.68v-2.211");
}

.nz9i78bwr {
  fill: var(--svg-color--da7600, #DA7600);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M8.215 20.344a.203.203 0 0 1 .406 0v2.61a.203.203 0 0 1-.406 0z");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.p3zloackg {
  stop-color: var(--svg-color--e88105, #E88105);
}

.pe7057y4c {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m25.498 24.479l3.802 1.819");
}

.pfu3kxb9j {
  d: path("m15.227 19.119l.064-.015a3.04 3.04 0 0 1 1.438.015c.521.098.832.695.392 1.125l-.55.602c-.27.27-.864.27-1.134 0l-.542-.602c-.45-.507-.168-1.015.332-1.125");
}

.pjoba9bfv {
  d: path("m25.833 13.433l-2.8-2.6a.716.716 0 0 1 0-1.07l3.015-2.677c.382-.336 1.175-.227 1.175.607v5.2c0 .834-.88 1.02-1.39.54");
}

.prf81acwx {
  stop-color: var(--svg-color--ffdf70, #FFDF70);
  stop-opacity: 0;
}

.pt1exccow {
  stop-color: var(--svg-color--e3801d, #E3801D);
}

.puetets_x {
  stop-color: var(--svg-color--ffc270, #FFC270);
}

.px6tpwb-q {
  stop-color: var(--svg-color--e61e27, #E61E27);
}

.q5ov0fb1f {
  cx: 16.27px;
  cy: 19.654px;
  rx: 0.762px;
  ry: 0.274px;
}

.q5x9unbmu {
  stop-color: var(--svg-color--ffb03a, #FFB03A);
}

.q8cwh1bju {
  stroke: var(--svg-color--ffdf70, #FFDF70);
  stroke-linecap: round;
  d: path("m5.406 6.063l3.375 3.219c.754.72.768 1.918.031 2.656v0");
}

.q8p4ktboz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M5.676 22.68v-2.211");
}

.qs6gzebns {
  d: path("M5.168 20.055a.336.336 0 1 1 .672 0v2.765a.336.336 0 1 1-.672 0z");
}

.rf5mz6bgl {
  stop-color: var(--svg-color--e3821d, #E3821D);
  stop-opacity: 0;
}

.rj5_8-btj {
  stop-color: var(--svg-color--ea088b, #EA088B);
}

.rjbed8bhp {
  d: path("M3.043 23.797a3.984 3.984 0 1 1 7.969 0V30H3.043z");
}

.s02xijbni {
  stop-color: var(--svg-color--cf8209, #CF8209);
}

.sdp081yre {
  fill: var(--svg-color--ffb915, #FFB915);
  d: path("m25.833 13.433l-2.8-2.6a.716.716 0 0 1 0-1.07l3.015-2.677c.382-.336 1.175-.227 1.175.607v5.2c0 .834-.88 1.02-1.39.54");
}

.sn-6zt0xa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.723 22.68v-2.211");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.swwvgmbsg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M26.668 22.68v-2.211");
}

.t246kz1qf {
  stop-color: var(--svg-color--ffa720, #FFA720);
  stop-opacity: 0;
}

.tp7z4jq4b {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m6.593 24.49l-3.801 1.82");
}

.uc_38mvnw {
  stop-color: var(--svg-color--ffe2bb, #FFE2BB);
  stop-opacity: 0;
}

.uekqj6-lf {
  stop-color: var(--svg-color--ffdf83, #FFDF83);
  stop-opacity: 0;
}

.uw0v0dbky {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m25.566 22.469l3.805-1.813");
}

.vafnvabsk {
  d: path("M20.586 10.165c-2.984.108 5.226 4.954 5.226 4.954l1.125-9.063c.055-.46-.364-.953-1.25-.13l-4.014 3.952c-.187.184-.408.248-.701.287c-.15.02-.236-.005-.387 0");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vlvlu57nf {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("M6.54 22.454L2.726 20.66");
}

.vpkdutb0i {
  cx: 11.082px;
  cy: 15.977px;
  r: 3.492px;
}

.vrg0atbjl {
  d: path("M26.49 5.582a.38.38 0 0 1 .732.142v2.245l-1.417-.688z");
}

.w4ibqacut {
  d: path("M27.962 25.995V6.35c0-1.437-1.336-2.14-2.43-1.125L21.518 9.18a1 1 0 0 1-.701.287H11.22a1 1 0 0 1-.701-.287L6.505 5.226c-1.094-1.015-2.43-.312-2.43 1.125v19.644c0 2.212 1.76 4.005 3.931 4.005h16.025c2.17 0 3.93-1.793 3.93-4.005");
}

.wf44tw33q {
  stop-color: var(--svg-color--e3821d, #E3821D);
}

.wuznojbzz {
  stop-color: var(--svg-color--da7600, #DA7600);
}

.x_idwdbad {
  d: path("M22.102 10.031h4.585v14.186h-4.585z");
}

.x5la94b6u {
  stop-color: var(--svg-color--ffa720, #FFA720);
}

.xon4_gnbq {
  stop-color: var(--svg-color--ed8c1b, #ED8C1B);
}

.xvb0lxf4e {
  stop-color: var(--svg-color--ea9d26, #EA9D26);
  stop-opacity: 0;
}

.y6_6kr0hz {
  stop-color: var(--svg-color--c88216, #C88216);
  stop-opacity: 0;
}

.ycz1ylytj {
  stop-color: var(--svg-color--fb7425, #FB7425);
}

.yt1b23z3f {
  d: path("M23.113 20.055a.336.336 0 1 1 .672 0v2.765a.336.336 0 1 1-.672 0z");
}

.ywi345bfa {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M6.674 22.428L2.86 20.635");
}

.z84gitb5w {
  stop-color: var(--svg-color--ffdd65, #FFDD65);
  stop-opacity: 0;
}

.zcqpgtb3c {
  d: path("M20.988 23.797a3.984 3.984 0 1 1 7.969 0V30h-7.969z");
}

.znp7aofuq {
  fill: var(--svg-color--feb33e, #FEB33E);
  d: path("M5.223 7.429v5.908l3.469-3.09z");
}

.zs7rcel6a {
  stop-color: var(--svg-color--ffb445, #FFB445);
}

.zye_r8bid {
  stop-color: var(--svg-color--da8400, #DA8400);
  stop-opacity: 0;
}

</style>
