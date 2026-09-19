<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iiwiX7d)" class="wl32fjttw"/><path fill="url(#i1ChZae)" class="wl32fjttw"/><path fill="url(#iDlWdra)" class="wl32fjttw"/><path fill="url(#ilWQIQd)" class="x72raebcu"/><path class="y94htx4sf"/><path class="qfc3g-e-c"/><path class="y9d3krmme"/><path fill="url(#iMN0LXk)" class="tl3_c2bax"/><path fill="url(#i4YULSf)" class="tl3_c2bax"/><path fill="url(#iNUCgxd)" class="tl3_c2bax"/><path fill="url(#ixk2s3c)" class="gxgem-vpp"/><path class="q-xthkbph"/><path class="jr3edb4hp"/><path class="yno19sbsr"/><path fill="url(#iFvi3qe)" class="d0m3jxffq"/><path fill="url(#igT8NNA)" class="u-n6jzb9x"/><g filter="url(#iV9m02g)"><path stroke="url(#iBa8l0Y)" class="gq-thibsl"/></g><path fill="url(#iTwDEec)" class="wsxf9sbgv"/><path class="qg44-ccuf"/><g filter="url(#i8ONN0c)"><path stroke="url(#iHUBaQc)" class="zp97f0jrf"/></g><g filter="url(#iVb2Lae)"><path stroke="url(#iiDGInc)" class="z7aj6vbol"/><path stroke="url(#iio6gtc)" class="z7aj6vbol"/></g><g filter="url(#ixp8Bnb)"><path stroke="url(#iTP4ctb)" class="akds_hb1r"/></g><path fill="url(#iz3Jk3d)" class="gri3iib2s"/><g filter="url(#i3P2NdA)"><path stroke="url(#iwz2Xgb)" class="ftu05pb_x"/><path stroke="url(#iwvx89L)" class="ftu05pb_x"/></g><g filter="url(#iRAmESc)"><path stroke="url(#iz4bSQc)" class="vtl2zib0f"/></g><path fill="url(#ikWIj6d)" class="sntxqwb9h"/><path fill="url(#iivzpUb)" class="sntxqwb9h"/><path fill="url(#idjVihc)" class="sntxqwb9h"/><path fill="url(#i2APjce)" class="sntxqwb9h"/><path fill="url(#ifaZa5b)" class="j3x_i8uit"/><g filter="url(#iqLIfic)"><path fill="url(#i4kVipd)" class="wnfihdbwp"/><path fill="url(#iNV9IUc)" class="wnfihdbwp"/></g><path fill="url(#i1kMLDc)" class="ahfl309zi"/><path fill="url(#iGdP6ac)" class="ahfl309zi"/><path fill="url(#iJ4ZQdd)" class="ahfl309zi"/><path fill="url(#i2UYnge)" class="ahfl309zi"/><path fill="url(#i4yA5ib)" class="ahfl309zi"/><path fill="url(#ipoaN8N)" class="ahfl309zi"/><path fill="url(#iilaUcw)" class="cp-qizfee"/><path fill="url(#iuR6jFx)" class="yhtiq-nqz"/><path fill="url(#iRUxU7b)" class="lv0srkdhv"/><path fill="url(#iTOLn4b)" class="nar4f2zjp"/><path fill="url(#iIBzr3d)" class="la1novb6m"/><g filter="url(#iLA3lXc)"><ellipse transform="rotate(46.78 27.188 28.532)" class="eehn9pbkg"/></g><g filter="url(#i42uMPb)"><path class="waqf48b6v"/></g><defs><linearGradient id="iiwiX7d" x1="7.769" x2="7.769" y1="6.033" y2="22.536" gradientUnits="userSpaceOnUse"><stop class="ssingdc-s"/><stop offset=".627" class="j_t7jl7yg"/><stop offset=".907" class="sft8io-ur"/><stop offset="1" class="eu5fofbbr"/></linearGradient><linearGradient id="ilWQIQd" x1="5.077" x2="5.077" y1="9.004" y2="11.344" gradientUnits="userSpaceOnUse"><stop class="qps4s9_8r"/><stop offset="1" class="szm7sin1v"/></linearGradient><linearGradient id="iMN0LXk" x1="24.193" x2="24.193" y1="6.033" y2="22.536" gradientUnits="userSpaceOnUse"><stop offset=".047" class="ssingdc-s"/><stop offset=".596" class="j_t7jl7yg"/><stop offset=".858" class="sft8io-ur"/><stop offset="1" class="eu5fofbbr"/></linearGradient><linearGradient id="ixk2s3c" x1="26.884" x2="26.884" y1="9.004" y2="11.344" gradientUnits="userSpaceOnUse"><stop class="tydqibk7x"/><stop offset="1" class="d96iy3w6k"/></linearGradient><linearGradient id="iFvi3qe" x1="9.5" x2="8.438" y1="22.609" y2="26.813" gradientUnits="userSpaceOnUse"><stop offset=".193" class="d_56h0blh"/><stop offset=".863" class="z6peqkb0t"/></linearGradient><linearGradient id="igT8NNA" x1="22.518" x2="23.58" y1="22.609" y2="26.813" gradientUnits="userSpaceOnUse"><stop offset=".193" class="d_56h0blh"/><stop offset=".863" class="z6peqkb0t"/></linearGradient><linearGradient id="iBa8l0Y" x1="19.44" x2="27.858" y1="24.313" y2="24.313" gradientUnits="userSpaceOnUse"><stop class="ltkp2yymj"/><stop offset="1" class="a4_en_kui"/></linearGradient><linearGradient id="iTwDEec" x1="10.014" x2="10.014" y1="22.572" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".63" class="k2vzz31hz"/><stop offset="1" class="jgns5kb2s"/></linearGradient><linearGradient id="iHUBaQc" x1="11.416" x2="5.5" y1="12.96" y2="12.219" gradientUnits="userSpaceOnUse"><stop offset=".036" class="wo4nbxi6k"/><stop offset="1" class="rv206mbvc"/></linearGradient><linearGradient id="iiDGInc" x1="14.92" x2="5.617" y1="26.183" y2="26.183" gradientUnits="userSpaceOnUse"><stop class="ltkp2yymj"/><stop offset="1" class="a4_en_kui"/></linearGradient><linearGradient id="iio6gtc" x1="14.906" x2="14.906" y1="24.906" y2="26.469" gradientUnits="userSpaceOnUse"><stop class="k19r22bzo"/><stop offset=".62" class="rh19knbqk"/></linearGradient><linearGradient id="iTP4ctb" x1="14.125" x2="27.022" y1="22.438" y2="12.219" gradientUnits="userSpaceOnUse"><stop offset=".036" class="wo4nbxi6k"/><stop offset="1" class="rv206mbvc"/></linearGradient><linearGradient id="iz3Jk3d" x1="22.001" x2="22.001" y1="22.572" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".63" class="k2vzz31hz"/><stop offset="1" class="jgns5kb2s"/></linearGradient><linearGradient id="iwz2Xgb" x1="17.637" x2="26.941" y1="26.183" y2="26.183" gradientUnits="userSpaceOnUse"><stop class="ltkp2yymj"/><stop offset="1" class="a4_en_kui"/></linearGradient><linearGradient id="iwvx89L" x1="17.906" x2="17.906" y1="25" y2="26.156" gradientUnits="userSpaceOnUse"><stop class="i89-21b3b"/><stop offset=".419" class="ievw94b4o"/></linearGradient><linearGradient id="iz4bSQc" x1="12.764" x2="4.347" y1="24.564" y2="24.564" gradientUnits="userSpaceOnUse"><stop class="ltkp2yymj"/><stop offset="1" class="a4_en_kui"/></linearGradient><linearGradient id="ifaZa5b" x1="16.03" x2="16.03" y1="2.209" y2="12.25" gradientUnits="userSpaceOnUse"><stop offset=".222" class="jul6f8bcs"/><stop offset="1" class="iile0mbha"/></linearGradient><linearGradient id="i4kVipd" x1="10.25" x2="21.813" y1="8.93" y2="8.93" gradientUnits="userSpaceOnUse"><stop class="no55q-b_s"/><stop offset="1" class="ct4mwub5k"/></linearGradient><linearGradient id="iNV9IUc" x1="12.656" x2="11.609" y1="7.688" y2="7.266" gradientUnits="userSpaceOnUse"><stop class="ni727ccow"/><stop offset=".426" class="wym36zjoz"/><stop offset="1" class="qz52l1b4k"/></linearGradient><linearGradient id="i1kMLDc" x1="16" x2="16" y1="2" y2="18.75" gradientUnits="userSpaceOnUse"><stop class="c8x49ec4l"/><stop offset=".585" class="ni8e29i-b"/><stop offset="1" class="bp55dhbqa"/></linearGradient><linearGradient id="iJ4ZQdd" x1="16" x2="16" y1="15.688" y2="20.609" gradientUnits="userSpaceOnUse"><stop offset=".216" class="yv30td-ft"/><stop offset=".495" class="jqawilbee"/></linearGradient><linearGradient id="iilaUcw" x1="16.824" x2="19.064" y1="12.787" y2="12.787" gradientUnits="userSpaceOnUse"><stop class="i7wh4xb_p"/><stop offset="1" class="slml_sbyh"/></linearGradient><linearGradient id="iuR6jFx" x1="14.344" x2="15.71" y1="11.906" y2="11.906" gradientUnits="userSpaceOnUse"><stop class="egw2webet"/><stop offset="1" class="v160j6wlb"/></linearGradient><linearGradient id="iRUxU7b" x1="13.943" x2="16.156" y1="15.188" y2="15.188" gradientUnits="userSpaceOnUse"><stop class="spbiq7b2f"/><stop offset="1" class="y5rh0606m"/></linearGradient><radialGradient id="i1ChZae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18751 2.875 -23.52112 -9.71536 10.313 22.063)" gradientUnits="userSpaceOnUse"><stop class="gccn6fn1l"/><stop offset="1" class="myj6ntbkm"/></radialGradient><radialGradient id="iDlWdra" cx="0" cy="0" r="1" gradientTransform="matrix(2.75003 5.81248 -4.51034 2.13395 6.375 7.687)" gradientUnits="userSpaceOnUse"><stop class="bu_km-92y"/><stop offset="1" class="o-oygab4z"/></radialGradient><radialGradient id="i4YULSf" cx="0" cy="0" r="1" gradientTransform="matrix(1.66148 4.21875 -15.10201 5.94765 22.531 22.281)" gradientUnits="userSpaceOnUse"><stop class="t1_xnobja"/><stop offset="1" class="w4lpa1fnf"/></radialGradient><radialGradient id="iNUCgxd" cx="0" cy="0" r="1" gradientTransform="matrix(.75 4.75 -2.95233 .46616 28.125 8)" gradientUnits="userSpaceOnUse"><stop class="ni2b_h4dn"/><stop offset="1" class="vod0tcbil"/></radialGradient><radialGradient id="ikWIj6d" cx="0" cy="0" r="1" gradientTransform="rotate(139.728 5.642 13.91)scale(5.89789 12.4997)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="jlxezdb5v"/><stop offset=".52" class="u7l6deb9p"/><stop offset="1" class="n2y0_vbbn"/></radialGradient><radialGradient id="iivzpUb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 0 0 -2.87222 19.813 25)" gradientUnits="userSpaceOnUse"><stop class="zx6csqqso"/><stop offset="1" class="xnxqodh4l"/></radialGradient><radialGradient id="idjVihc" cx="0" cy="0" r="1" gradientTransform="matrix(1.9375 1.625 -1.69722 2.02361 11.688 24.688)" gradientUnits="userSpaceOnUse"><stop class="bfz5lbbsn"/><stop offset="1" class="ygxn59bfa"/></radialGradient><radialGradient id="i2APjce" cx="0" cy="0" r="1" gradientTransform="matrix(-.17967 2.75005 -2.13588 -.13954 11.187 22.25)" gradientUnits="userSpaceOnUse"><stop class="e64c2xbri"/><stop offset="1" class="mdezktb_u"/></radialGradient><radialGradient id="iGdP6ac" cx="0" cy="0" r="1" gradientTransform="matrix(1.25001 14.56255 -3.764 .3231 19.25 8.563)" gradientUnits="userSpaceOnUse"><stop class="ap4_yvbaa"/><stop offset="1" class="up5zbnqxy"/></radialGradient><radialGradient id="i2UYnge" cx="0" cy="0" r="1" gradientTransform="rotate(102.953 3.811 7.782)scale(6.41318 1.9693)" gradientUnits="userSpaceOnUse"><stop class="ktc1iywda"/><stop offset="1" class="icxkik7xu"/></radialGradient><radialGradient id="i4yA5ib" cx="0" cy="0" r="1" gradientTransform="matrix(3.0625 5.3125 -4.03233 2.32452 9.875 18.5)" gradientUnits="userSpaceOnUse"><stop class="a9z83sbjp"/><stop offset="1" class="iuec2un2l"/></radialGradient><radialGradient id="ipoaN8N" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 3.1875 -.86932 .61364 9.375 18.938)" gradientUnits="userSpaceOnUse"><stop class="wqp5phbij"/><stop offset="1" class="by6ci5b7l"/></radialGradient><radialGradient id="iTOLn4b" cx="0" cy="0" r="1" gradientTransform="rotate(153.347 4.25 12.888)scale(1.18428)" gradientUnits="userSpaceOnUse"><stop class="fyse9kb_r"/><stop offset=".537" class="bmbt6466i"/><stop offset=".769" class="mp7uncc1p"/><stop offset=".996" class="epq9tz8wg"/></radialGradient><radialGradient id="iIBzr3d" cx="0" cy="0" r="1" gradientTransform="rotate(153.347 6.713 13.472)scale(1.18428)" gradientUnits="userSpaceOnUse"><stop class="fyse9kb_r"/><stop offset=".537" class="bmbt6466i"/><stop offset=".769" class="mp7uncc1p"/><stop offset=".996" class="epq9tz8wg"/></radialGradient><filter id="iV9m02g" width="11.86" height="4.918" x="17.642" y="22.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28271" stdDeviation=".5"/></filter><filter id="i8ONN0c" width="8.906" height="11.344" x="3.969" y="10.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28271" stdDeviation=".375"/></filter><filter id="iVb2Lae" width="12.344" height="6.094" x="4.156" y="24.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28271" stdDeviation=".375"/></filter><filter id="ixp8Bnb" width="8.906" height="11.344" x="19.647" y="10.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28271" stdDeviation=".375"/></filter><filter id="i3P2NdA" width="11.568" height="5.406" x="16.308" y="24.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28271" stdDeviation=".25"/></filter><filter id="iRAmESc" width="11.86" height="4.918" x="2.703" y="22.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28271" stdDeviation=".5"/></filter><filter id="iqLIfic" width="13.627" height="13.108" x="9.216" y="2.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28271" stdDeviation=".125"/></filter><filter id="iLA3lXc" width="2.449" height="2.472" x="25.964" y="27.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28271" stdDeviation=".375"/></filter><filter id="i42uMPb" width="2.994" height="3.261" x="26.259" y="22.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28271" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:squid" /></template>
<style>
.a4_en_kui {
  stop-color: var(--svg-color--e352c5, #E352C5);
}

.a9z83sbjp {
  stop-color: var(--svg-color--d95ab5, #D95AB5);
}

.ahfl309zi {
  d: path("M15.986 2c-1.2 0-2.261.76-2.652 1.89c0 0-4.396 11.423-4.396 12.86c0 1.438.267 1.587 1.218 2.797c.688.875.89 1.062.89 1.062h9.93s.212-.156.785-.879c.976-1.23 1.302-1.746 1.302-2.98S18.649 3.89 18.649 3.89A2.825 2.825 0 0 0 15.986 2");
}

.akds_hb1r {
  stroke-linecap: round;
  d: path("M27.303 12.219v4.5c0 .625-.969 2.312-2.078 2.703l-4.328 1.64");
}

.ap4_yvbaa {
  stop-color: var(--svg-color--fc7dd3, #FC7DD3);
}

.bfz5lbbsn {
  stop-color: var(--svg-color--c81eac, #C81EAC);
}

.bmbt6466i {
  stop-color: var(--svg-color--372546, #372546);
}

.bp55dhbqa {
  stop-color: var(--svg-color--c732a0, #C732A0);
}

.bu_km-92y {
  stop-color: var(--svg-color--f073cb, #F073CB);
}

.by6ci5b7l {
  stop-color: var(--svg-color--b22b88, #B22B88);
  stop-opacity: 0;
}

.c8x49ec4l {
  stop-color: var(--svg-color--da58b0, #DA58B0);
}

.cp-qizfee {
  d: path("M17.944 13.725a1.12 1.12 0 1 0 0-2.24a1.12 1.12 0 0 0 0 2.24");
}

.ct4mwub5k {
  stop-color: var(--svg-color--ea5bc3, #EA5BC3);
}

.d_56h0blh {
  stop-color: var(--svg-color--b63377, #B63377);
}

.d0m3jxffq {
  d: path("M10.51 27.219c-3.135 0-3.252-2.078-4.291-2.078c-.633 0-.822.493-1.125.797c-.44.44-1.275.342-1.715-.098s-.461-1.04-.066-1.59c.437-.61 1.07-1.64 3.093-1.64c2.063 0 2.393 2.075 4.016 2.109c.937 0 1.186-.835 1.906-1.555c.44-.44 1.612-.334 2.052.106s.44 1.15 0 1.59l-1.02 1.02c-.77.76-1.78 1.339-2.85 1.339");
}

.d96iy3w6k {
  stop-color: var(--svg-color--c923ab, #C923AB);
}

.e64c2xbri {
  stop-color: var(--svg-color--d578b5, #D578B5);
}

.eehn9pbkg {
  cx: 27.188px;
  cy: 28.532px;
  fill: var(--svg-color--ee71c8, #EE71C8);
  rx: 0.566px;
  ry: 0.375px;
}

.egw2webet {
  stop-color: var(--svg-color--9e298b, #9E298B);
}

.epq9tz8wg {
  stop-color: var(--svg-color--5a595b, #5A595B);
}

.eu5fofbbr {
  stop-color: var(--svg-color--b91b92, #B91B92);
}

.ft5dv1b6b {
  fill: none;
}

.ftu05pb_x {
  stroke-linecap: round;
  d: path("M26.875 28.688h-7.219c-.437 0-1.42 0-1.687-.75s-.578-2.323-.661-2.657");
}

.fyse9kb_r {
  stop-color: var(--svg-color--504f52, #504F52);
}

.gccn6fn1l {
  stop-color: var(--svg-color--b91e98, #B91E98);
}

.gq-thibsl {
  stroke-linecap: round;
  d: path("M28.001 25.201c-.27-.49-1.062-1.359-2.187-1.234c-1.406.156-2.016 1.906-3.985 1.906c-1.575 0-2.354-.958-2.687-1.469");
}

.gri3iib2s {
  d: path("M26.881 30h-7.447c-1.5 0-2.881-1.003-3.271-2.453L16 26.745v-2.79c0-1.4 1.242-1.977 1.614-.58l.97 3.57c.12.46.38.672.86.672h7.437c.62 0 1.12.633 1.12 1.253s-.5 1.13-1.12 1.13");
}

.gxgem-vpp {
  d: path("M26.885 11.344a1.17 1.17 0 1 1 0-2.34a1.17 1.17 0 0 1 0 2.34");
}

.i7wh4xb_p {
  stop-color: var(--svg-color--b644a0, #B644A0);
}

.i89-21b3b {
  stop-color: var(--svg-color--c3128c, #C3128C);
}

.icxkik7xu {
  stop-color: var(--svg-color--dd81b9, #DD81B9);
  stop-opacity: 0;
}

.ievw94b4o {
  stop-color: var(--svg-color--c71d96, #C71D96);
  stop-opacity: 0;
}

.iile0mbha {
  stop-color: var(--svg-color--c8369e, #C8369E);
}

.iuec2un2l {
  stop-color: var(--svg-color--c045a0, #C045A0);
  stop-opacity: 0;
}

.j_t7jl7yg {
  stop-color: var(--svg-color--ca379f, #CA379F);
}

.j3x_i8uit {
  d: path("m22.57 8.084l-4.56-5.05a2.8 2.8 0 0 0-3.97 0l-4.55 5.05c-.61.61-.61 1.6 0 2.21l5.44 4.9c.61.61 1.6.61 2.21 0l5.44-4.9c.6-.62.6-1.6-.01-2.21");
}

.jgns5kb2s {
  stop-color: var(--svg-color--ee40ef, #EE40EF);
}

.jlxezdb5v {
  stop-color: var(--svg-color--fe6de1, #FE6DE1);
}

.jqawilbee {
  stop-color: var(--svg-color--d81db4, #D81DB4);
}

.jr3edb4hp {
  fill: var(--svg-color--ce32aa, #CE32AA);
  d: path("M27.664 8.93a.52.52 0 1 1 0-1.04a.52.52 0 0 1 0 1.04");
}

.jul6f8bcs {
  stop-color: var(--svg-color--f678c8, #F678C8);
}

.k19r22bzo {
  stop-color: var(--svg-color--c51a9d, #C51A9D);
}

.k2vzz31hz {
  stop-color: var(--svg-color--c01a8d, #C01A8D);
}

.ktc1iywda {
  stop-color: var(--svg-color--dc7eb7, #DC7EB7);
}

.la1novb6m {
  d: path("M18.448 23.494a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.ltkp2yymj {
  stop-color: var(--svg-color--d23db0, #D23DB0);
}

.lv0srkdhv {
  d: path("M15.05 16.114a1.107 1.107 0 1 0 0-2.213a1.107 1.107 0 0 0 0 2.213");
}

.mdezktb_u {
  stop-color: var(--svg-color--d578b5, #D578B5);
  stop-opacity: 0;
}

.mp7uncc1p {
  stop-color: var(--svg-color--362545, #362545);
}

.myj6ntbkm {
  stop-color: var(--svg-color--b81790, #B81790);
  stop-opacity: 0;
}

.n2y0_vbbn {
  stop-color: var(--svg-color--dc2acd, #DC2ACD);
}

.nar4f2zjp {
  d: path("M13.52 23.494a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.ni2b_h4dn {
  stop-color: var(--svg-color--f475ce, #F475CE);
}

.ni727ccow {
  stop-color: var(--svg-color--c13692, #C13692);
  stop-opacity: 0;
}

.ni8e29i-b {
  stop-color: var(--svg-color--e053b9, #E053B9);
}

.no55q-b_s {
  stop-color: var(--svg-color--d852b5, #D852B5);
}

.o-oygab4z {
  stop-color: var(--svg-color--e95acc, #E95ACC);
  stop-opacity: 0;
}

.q-xthkbph {
  fill: var(--svg-color--c730a8, #C730A8);
  d: path("M25.99 8.93a.52.52 0 1 1 0-1.04a.52.52 0 0 1 0 1.04");
}

.qfc3g-e-c {
  fill: var(--svg-color--c631a3, #C631A3);
  d: path("M4.22 8.93a.52.52 0 1 0 0-1.04a.52.52 0 0 0 0 1.04");
}

.qg44-ccuf {
  fill: var(--svg-color--c01a8d, #C01A8D);
  d: path("M26.881 30h-7.447c-1.5 0-2.881-1.003-3.271-2.453L16 26.745v-2.79c0-1.4 1.242-1.977 1.614-.58l.97 3.57c.12.46.38.672.86.672h7.437c.62 0 1.12.633 1.12 1.253s-.5 1.13-1.12 1.13");
}

.qps4s9_8r {
  stop-color: var(--svg-color--ca31b3, #CA31B3);
}

.qz52l1b4k {
  stop-color: var(--svg-color--c13493, #C13493);
  stop-opacity: 0;
}

.rh19knbqk {
  stop-color: var(--svg-color--bb0986, #BB0986);
  stop-opacity: 0;
}

.rv206mbvc {
  stop-color: var(--svg-color--e350c6, #E350C6);
}

.sft8io-ur {
  stop-color: var(--svg-color--a5035f, #A5035F);
}

.slml_sbyh {
  stop-color: var(--svg-color--c154a8, #C154A8);
}

.sntxqwb9h {
  d: path("M18.25 25h-4.46c-1.381 0-2.782-1.12-2.782-2.5v-2.2h9.96v2.2c0 1.38-1.398 2.5-2.718 2.5");
}

.spbiq7b2f {
  stop-color: var(--svg-color--a0288d, #A0288D);
}

.ssingdc-s {
  stop-color: var(--svg-color--e95acb, #E95ACB);
}

.szm7sin1v {
  stop-color: var(--svg-color--c521a9, #C521A9);
}

.t1_xnobja {
  stop-color: var(--svg-color--c8199d, #C8199D);
}

.tl3_c2bax {
  d: path("M29.321 9.646c0-.755-.821-2.064-1.445-2.97c-.47-.87-1.447-.845-2.016 0c-.502.746-1.43 2.026-1.43 2.97c0 .98.451 1.454.891 1.854c.31.28.328.606.328 1.026v3.7c0 1.19-.598 1.962-1.718 2.352l-4.11 1.656c-.59.21-.896.972-.696 1.552a1.127 1.127 0 0 0 1.43.69l4.21-1.48a5.07 5.07 0 0 0 3.38-4.77v-3.7c0-.43 0-.784.333-1.026c.49-.358.843-1.165.843-1.854");
}

.tydqibk7x {
  stop-color: var(--svg-color--cc31b4, #CC31B4);
}

.u-n6jzb9x {
  d: path("M21.508 27.219c3.135 0 3.252-2.078 4.29-2.078c.634 0 .822.493 1.126.797c.44.44 1.275.342 1.715-.098s.46-1.04.066-1.59c-.437-.61-1.07-1.64-3.094-1.64c-2.062 0-2.393 2.075-4.015 2.109c-.938 0-1.186-.835-1.907-1.555c-.44-.44-1.611-.334-2.051.106s-.44 1.15 0 1.59l1.02 1.02c.77.76 1.78 1.339 2.85 1.339");
}

.u7l6deb9p {
  stop-color: var(--svg-color--ed50d7, #ED50D7);
}

.up5zbnqxy {
  stop-color: var(--svg-color--fe7cd4, #FE7CD4);
  stop-opacity: 0;
}

.v160j6wlb {
  stop-color: var(--svg-color--a83194, #A83194);
}

.vod0tcbil {
  stop-color: var(--svg-color--eb5bcd, #EB5BCD);
  stop-opacity: 0;
}

.vtl2zib0f {
  stroke-linecap: round;
  d: path("M4.203 25.453c.271-.49 1.063-1.36 2.188-1.234c1.406.156 2.015 1.906 3.984 1.906c1.575 0 2.354-.958 2.688-1.469");
}

.w4lpa1fnf {
  stop-color: var(--svg-color--c6199b, #C6199B);
  stop-opacity: 0;
}

.waqf48b6v {
  fill: var(--svg-color--ee71c8, #EE71C8);
  d: path("M28.453 25.125c-.15.142-.473-.397-.687-.625s-.886-.952-.735-1.094c.151-.141.927.538 1.14.766c.215.228.433.811.282.953");
}

.wl32fjttw {
  d: path("M2.64 9.646c0-.755.822-2.064 1.446-2.97c.47-.87 1.447-.845 2.016 0c.502.746 1.43 2.026 1.43 2.97c0 .98-.451 1.454-.891 1.854c-.31.28-.328.606-.328 1.026v3.7c0 1.19.598 1.962 1.718 2.352l4.11 1.656c.59.21.896.972.696 1.552a1.127 1.127 0 0 1-1.43.69l-4.21-1.48a5.07 5.07 0 0 1-3.38-4.77v-3.7c0-.43 0-.784-.333-1.026c-.49-.358-.843-1.165-.843-1.854");
}

.wnfihdbwp {
  d: path("M22.164 8.136L17.886 3.4a2.627 2.627 0 0 0-3.724 0L9.895 8.136a1.466 1.466 0 0 0 0 2.073l5.103 4.596c.572.572 1.5.572 2.073 0l5.102-4.596c.563-.581.563-1.5-.01-2.073");
}

.wo4nbxi6k {
  stop-color: var(--svg-color--dc52ba, #DC52BA);
  stop-opacity: 0;
}

.wqp5phbij {
  stop-color: var(--svg-color--ac257d, #AC257D);
}

.wsxf9sbgv {
  d: path("M5.133 30h7.447c1.5 0 2.881-1.003 3.271-2.453l.163-.802v-2.79c0-1.4-1.241-1.977-1.614-.58l-.97 3.57c-.12.46-.38.672-.86.672H5.133c-.62 0-1.12.633-1.12 1.253s.5 1.13 1.12 1.13");
}

.wym36zjoz {
  stop-color: var(--svg-color--c12d91, #C12D91);
}

.x72raebcu {
  d: path("M5.078 11.344a1.17 1.17 0 1 0 0-2.34a1.17 1.17 0 0 0 0 2.34");
}

.xnxqodh4l {
  stop-color: var(--svg-color--d320ab, #D320AB);
  stop-opacity: 0;
}

.y5rh0606m {
  stop-color: var(--svg-color--ac3498, #AC3498);
}

.y94htx4sf {
  fill: var(--svg-color--ca31aa, #CA31AA);
  d: path("M5.816 8.93a.52.52 0 1 0 0-1.04a.52.52 0 0 0 0 1.04");
}

.y9d3krmme {
  fill: var(--svg-color--c62fa3, #C62FA3);
  d: path("M4.992 7.658a.52.52 0 1 0 0-1.04a.52.52 0 0 0 0 1.04");
}

.ygxn59bfa {
  stop-color: var(--svg-color--c620aa, #C620AA);
  stop-opacity: 0;
}

.yhtiq-nqz {
  d: path("M14.96 12.656a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.yno19sbsr {
  fill: var(--svg-color--c62ea4, #C62EA4);
  d: path("M26.783 7.658a.52.52 0 1 1 0-1.04a.52.52 0 0 1 0 1.04");
}

.yv30td-ft {
  stop-color: var(--svg-color--dd31bc, #DD31BC);
  stop-opacity: 0;
}

.z6peqkb0t {
  stop-color: var(--svg-color--c926a3, #C926A3);
}

.z7aj6vbol {
  stroke-linecap: round;
  d: path("M5.406 28.875h7.657c.437-.062 1.37.156 1.75-.906c.25-.7.354-2.354.437-2.688");
}

.zp97f0jrf {
  stroke-linecap: round;
  d: path("M5.219 12.219v4.5c0 .625.968 2.312 2.078 2.703l4.328 1.64");
}

.zx6csqqso {
  stop-color: var(--svg-color--d627ac, #D627AC);
}

</style>
