<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path class="d8omw7boy"/><path fill="url(#ist3JKv)" class="p7ie-abaj"/><path fill="url(#ipscm7b)" class="p7ie-abaj"/><path fill="url(#iR6a8Ne)" class="p7ie-abaj"/><path fill="url(#i2KtZ9b)" class="p7ie-abaj"/><path fill="url(#ib2Qood)" class="p7ie-abaj"/><path fill="url(#iXKlKjW)" class="yxxpybc9a"/><path class="xfs9v3wie"/><path fill="url(#iqPd9lb)" class="nv_pp8bfd"/><path fill="url(#iWr4cvd)" class="nv_pp8bfd"/><path fill="url(#iEIQMZb)" class="nv_pp8bfd"/><path fill="url(#iQM336V)" class="vbj81cvpa"/><path fill="url(#iAsq8WC)" class="vbj81cvpa"/><path fill="url(#isj98NR)" class="cpy9k-bjf"/><path fill="url(#indV0xc)" class="cpy9k-bjf"/><path fill="url(#i4sTH4T)" class="cpy9k-bjf"/><path fill="url(#iIImfHc)" class="cpy9k-bjf"/><path fill="url(#iiP5YSb)" class="cpy9k-bjf"/><path fill="url(#iWlxjjb)" class="cpy9k-bjf"/><path fill="url(#iZaC6vb)" class="cpy9k-bjf"/><g filter="url(#iDZkysc)"><path class="n0ec68fkr"/></g><g filter="url(#ifCjWvc)"><path class="hd3ml2boj"/></g><path fill="url(#i18aHud)" class="iecb_xbcw"/><path fill="url(#i5Wwpyd)" class="iecb_xbcw"/><path fill="url(#iQUueHc)" class="iecb_xbcw"/><path fill="url(#iz4ehxe)" class="vj72szwqa"/><path fill="url(#i85zpce)" class="vj72szwqa"/><path fill="url(#isDT9hc)" class="vj72szwqa"/><g filter="url(#iIWuIse)"><path fill="url(#isptK8d)" class="n_qpyzykw"/></g><path fill="url(#i10IEud)" class="hi-cny2ks"/><path fill="url(#idSEP2W)" class="hi-cny2ks"/><path fill="url(#iKI5FKd)" class="hi-cny2ks"/><g filter="url(#ijRUmwc)"><path clip-rule="evenodd" class="e-0wnvbdl"/></g><path stroke="url(#iqGwbie)" class="xwq91wb_x"/><path stroke="url(#i0eUy6c)" class="xwq91wb_x"/><path stroke="url(#icjjZXv)" class="c3du82btn"/><g filter="url(#iyiCEKk)"><path stroke="url(#imtTx4c)" class="kgapjfrdk"/></g><g filter="url(#irU2XNd)"><path class="kjd0kebjl"/></g><path fill="url(#iNChHAe)" class="j4e_b37rv"/><path fill="url(#inR1qmA)" class="j4e_b37rv"/><path fill="url(#imZVFtL)" class="j4e_b37rv"/><path fill="url(#iMYQJZb)" class="j4e_b37rv"/><path fill="url(#icylpjc)" class="j4e_b37rv"/><g filter="url(#izGNbbe)"><path fill="url(#iN7kfSd)" class="r8r_t8axo"/></g></g><defs><radialGradient id="iR6a8Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-7.125 -5.59375 3.77133 -4.8037 28.517 10.938)" gradientUnits="userSpaceOnUse"><stop offset=".909" class="ma110-chc"/><stop offset=".999" class="v0arv1rpy"/></radialGradient><radialGradient id="i2KtZ9b" cx="0" cy="0" r="1" gradientTransform="rotate(54.148 9.035 22.352)scale(11.258 7.63242)" gradientUnits="userSpaceOnUse"><stop offset=".909" class="ma110-chc"/><stop offset=".976" class="v0arv1rpy"/></radialGradient><radialGradient id="ib2Qood" cx="0" cy="0" r="1" gradientTransform="rotate(142.716 12.983 7.84)scale(3.45634 3.61664)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iWr4cvd" cx="0" cy="0" r="1" gradientTransform="rotate(-175.225 8.291 4.193)scale(13.5157 8.57156)" gradientUnits="userSpaceOnUse"><stop offset=".913" class="ma110-chc"/><stop offset=".976" class="v0arv1rpy"/></radialGradient><radialGradient id="iEIQMZb" cx="0" cy="0" r="1" gradientTransform="rotate(127.193 3.762 4.448)scale(3.82543 4.3788)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iQM336V" cx="0" cy="0" r="1" gradientTransform="matrix(3.99525 -1.76497 .751 1.69999 4.99 8.734)" gradientUnits="userSpaceOnUse"><stop class="g17mq7bwz"/><stop offset="1" class="ra20jyokg"/></radialGradient><radialGradient id="iAsq8WC" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 -3.34375 2.1781 1.75062 6.267 9.656)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="rt-ll90ye"/><stop offset="1" class="lpvelcc-y"/></radialGradient><radialGradient id="isj98NR" cx="0" cy="0" r="1" gradientTransform="matrix(0 28.0625 -27.4301 0 16.33 7.75)" gradientUnits="userSpaceOnUse"><stop class="mauzo7bsv"/><stop offset="1" class="qcg9-qkkd"/></radialGradient><radialGradient id="indV0xc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -20.0625 30.4634 0 15.995 39.75)" gradientUnits="userSpaceOnUse"><stop class="kt-2njnsi"/><stop offset="1" class="q-2g22jeb"/></radialGradient><radialGradient id="i4sTH4T" cx="0" cy="0" r="1" gradientTransform="matrix(0 24.2717 -27.628 0 15.995 5.978)" gradientUnits="userSpaceOnUse"><stop offset=".882" class="gk118lbys"/><stop offset="1" class="qcbchrk1j"/></radialGradient><radialGradient id="iIImfHc" cx="0" cy="0" r="1" gradientTransform="matrix(6.39667 26.3967 -28.79752 6.97845 15.995 5.978)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="q85-4xmei"/><stop offset="1" class="ode3c1y9k"/></radialGradient><radialGradient id="iiP5YSb" cx="0" cy="0" r="1" gradientTransform="matrix(-24.4375 0 0 -17.875 25.25 19.306)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="k1la4fbpv"/><stop offset="1" class="n9c80wbeq"/></radialGradient><radialGradient id="iWlxjjb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.06254 -15.39675 19.40575 -5.12034 16.392 20.688)" gradientUnits="userSpaceOnUse"><stop offset=".848" class="annh2rbci"/><stop offset="1" class="ra1d-fbuq"/></radialGradient><radialGradient id="iZaC6vb" cx="0" cy="0" r="1" gradientTransform="matrix(21.63454 7.16454 -6.25235 18.88006 8.58 17.21)" gradientUnits="userSpaceOnUse"><stop offset=".848" class="annh2rbci"/><stop offset="1" class="ra1d-fbuq"/></radialGradient><radialGradient id="iQUueHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.44799 -1.68959 1.82138 -.48293 12.156 15.838)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="isDT9hc" cx="0" cy="0" r="1" gradientTransform="matrix(-.44799 -1.68959 1.82138 -.48293 20.156 15.838)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="idSEP2W" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.9436 10.6104 0 15.438 26.75)" gradientUnits="userSpaceOnUse"><stop class="wnh0-b9bd"/><stop offset="1" class="icwzt66ad"/></radialGradient><radialGradient id="iKI5FKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.8064 10.113 0 15.995 26.963)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="edxagb8pk"/><stop offset=".97" class="ja2twu1bh"/></radialGradient><radialGradient id="iqGwbie" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.71875 -2.18838 0 14.244 22.201)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="e9ucyqbno"/><stop offset="1" class="smhtebbjh"/></radialGradient><radialGradient id="i0eUy6c" cx="0" cy="0" r="1" gradientTransform="rotate(70.994 -7.67 20.657)scale(2.97467 7.41114)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="p981guc6t"/><stop offset="1" class="mjp0ecb6a"/></radialGradient><radialGradient id="icjjZXv" cx="0" cy="0" r="1" gradientTransform="matrix(-.2035 1.69185 -4.7471 -.571 17.938 22.228)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="p981guc6t"/><stop offset="1" class="mjp0ecb6a"/></radialGradient><radialGradient id="iMYQJZb" cx="0" cy="0" r="1" gradientTransform="matrix(4.24468 -1.44104 .64706 1.90597 13.855 19.914)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="lm-pdjb-m"/><stop offset=".935" class="z17z3-a-u"/></radialGradient><radialGradient id="icylpjc" cx="0" cy="0" r="1" gradientTransform="rotate(145.376 5.618 12.06)scale(.79749 .48374)" gradientUnits="userSpaceOnUse"><stop class="xbybj_nwx"/><stop offset="1" class="unvvv2nza"/></radialGradient><linearGradient id="ist3JKv" x1="25.142" x2="25.517" y1="13.406" y2="7.781" gradientUnits="userSpaceOnUse"><stop class="omd0cwdvl"/><stop offset="1" class="ma110-chc"/></linearGradient><linearGradient id="ipscm7b" x1="19.392" x2="23.298" y1="6.281" y2="6.875" gradientUnits="userSpaceOnUse"><stop class="omd0cwdvl"/><stop offset="1" class="ma110-chc"/></linearGradient><linearGradient id="iXKlKjW" x1="25.423" x2="23.86" y1="6.531" y2="8.734" gradientUnits="userSpaceOnUse"><stop class="ra20jyokg"/><stop offset="1" class="jnoyffl8i"/></linearGradient><linearGradient id="iqPd9lb" x1="6.829" x2="6.767" y1="12.125" y2="5.062" gradientUnits="userSpaceOnUse"><stop class="omd0cwdvl"/><stop offset="1" class="ma110-chc"/></linearGradient><linearGradient id="i18aHud" x1="12.745" x2="11.877" y1="15.416" y2="15.416" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="i5Wwpyd" x1="12.979" x2="12.979" y1="16.956" y2="15.533" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iz4ehxe" x1="20.745" x2="19.877" y1="15.416" y2="15.416" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="i85zpce" x1="20.979" x2="20.979" y1="16.956" y2="15.533" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="isptK8d" x1="15.382" x2="11.892" y1="23.75" y2="27.875" gradientUnits="userSpaceOnUse"><stop class="xnh-_nb8r"/><stop offset="1" class="ksapsyb2m"/></linearGradient><linearGradient id="i10IEud" x1="15.995" x2="15.995" y1="17.493" y2="26.15" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="wj-2m1b_c"/></linearGradient><linearGradient id="imtTx4c" x1="12.322" x2="19.838" y1="22.143" y2="22.143" gradientUnits="userSpaceOnUse"><stop class="rj14edb9i"/><stop offset=".289" class="zkps8y4ss"/><stop offset=".445" class="zkps8y4ss"/><stop offset=".534" class="rj14edb9i"/><stop offset="1" class="zkps8y4ss"/></linearGradient><linearGradient id="iNChHAe" x1="15.578" x2="16.075" y1="18.431" y2="20.215" gradientUnits="userSpaceOnUse"><stop class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="inR1qmA" x1="15.759" x2="15.759" y1="18.79" y2="17.586" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="imZVFtL" x1="15.155" x2="15.155" y1="20.809" y2="18.989" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iN7kfSd" x1="28.673" x2="20.458" y1="12.245" y2="16.795" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="iDZkysc" width="2.5" height="3.986" x="10.433" y="14.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4149" stdDeviation=".25"/></filter><filter id="ifCjWvc" width="2.5" height="3.986" x="18.432" y="13.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4149" stdDeviation=".25"/></filter><filter id="iIWuIse" width="11.774" height="10.737" x="9.704" y="17.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4149" stdDeviation=".375"/></filter><filter id="ijRUmwc" width="8.561" height="3.694" x="11.7" y="20.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4149" stdDeviation=".2"/></filter><filter id="iyiCEKk" width="7.719" height="2.484" x="12.135" y="21.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4149" stdDeviation=".125"/></filter><filter id="irU2XNd" width="5.027" height="3.975" x="13.21" y="17.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4149" stdDeviation=".35"/></filter><filter id="izGNbbe" width="16.368" height="21.686" x="16.499" y="4.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4149" stdDeviation="2"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:polar-bear" /></template>
<style>
.annh2rbci {
  stop-color: var(--svg-color--d0d1d2, #D0D1D2);
  stop-opacity: 0;
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.c3du82btn {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M19.48 21.643c0 1.045-.78 1.894-1.74 1.894S16 22.688 16 21.643");
}

.cpy9k-bjf {
  d: path("M30.214 19.54v-.03c0-.536-.051-1.062-.153-1.568c-.314-2.055-1.28-5.718-4.225-8.677c-4.235-4.248-9.841-3.97-9.841-3.97s-5.606-.278-9.841 3.97c-2.956 2.959-3.91 6.622-4.225 8.677a8 8 0 0 0-.153 1.578v.03c0 3.405 2.021 6.354 4.957 7.763c0 0 3.168 1.817 9.262 1.817s9.263-1.817 9.263-1.817c2.935-1.42 4.956-4.368 4.956-7.773");
}

.d8omw7boy {
  fill: var(--svg-color--dcdddf, #DCDDDF);
  d: path("M24.42 13.206a4.533 4.533 0 1 0 0-9.066a4.533 4.533 0 0 0 0 9.066");
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e-0wnvbdl {
  fill: var(--svg-color--baadcb, #BAADCB);
  fill-rule: evenodd;
  d: path("M13.073 21.784c0-.276-.218-.5-.487-.5a.494.494 0 0 0-.486.5c0 1.28.939 2.394 2.18 2.394c.702 0 1.306-.355 1.7-.894c.394.54.998.894 1.7.894c1.241 0 2.18-1.114 2.18-2.394c0-.276-.218-.5-.486-.5a.494.494 0 0 0-.487.5c0 .81-.58 1.394-1.208 1.394s-1.207-.584-1.207-1.394c0-.276-.218-.5-.487-.5h-.01a.494.494 0 0 0-.487.5c0 .81-.58 1.394-1.207 1.394s-1.208-.584-1.208-1.394");
}

.e9ucyqbno {
  stop-color: var(--svg-color--423539, #423539);
}

.edxagb8pk {
  stop-color: var(--svg-color--d8d8dc, #D8D8DC);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwtna0oas {
  stop-color: var(--svg-color--2e2127, #2E2127);
}

.g17mq7bwz {
  stop-color: var(--svg-color--d2d2d5, #D2D2D5);
}

.gk118lbys {
  stop-color: var(--svg-color--b9a6d1, #B9A6D1);
  stop-opacity: 0;
}

.hd3ml2boj {
  fill: var(--svg-color--9e9ba4, #9E9BA4);
  d: path("M19.682 17.408c-.41 0-.75-.34-.75-.75v-1.486c0-.41.34-.75.75-.75s.75.34.75.75v1.486c0 .41-.33.75-.75.75");
}

.hi-cny2ks {
  d: path("M15.995 17.494a8.7 8.7 0 0 0-3.242.622c-1.458.588-2.115 2.242-1.696 3.756c.593 2.143 1.92 4.278 4.938 4.278s4.345-2.135 4.938-4.277c.419-1.515-.238-3.17-1.696-3.757c-1.27-.511-2.509-.635-3.242-.622");
}

.icwzt66ad {
  stop-color: var(--svg-color--dacbf0, #DACBF0);
  stop-opacity: 0;
}

.iecb_xbcw {
  d: path("M11.995 17.096c-.41 0-.75-.34-.75-.75V14.86c0-.41.34-.75.75-.75s.75.34.75.75v1.486c0 .41-.33.75-.75.75");
}

.j4e_b37rv {
  d: path("M15.108 18.117h1.774c.683 0 1.023.725.67 1.289a4.2 4.2 0 0 1-.982 1.065a.96.96 0 0 1-.575.212a.96.96 0 0 1-.575-.212s-.574-.412-.982-1.065c-.353-.564-.013-1.29.67-1.29");
}

.ja2twu1bh {
  stop-color: var(--svg-color--d8d8dc, #D8D8DC);
}

.jnoyffl8i {
  stop-color: var(--svg-color--c6c7c9, #C6C7C9);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.k1la4fbpv {
  stop-color: var(--svg-color--dbdadd, #DBDADD);
  stop-opacity: 0;
}

.kgapjfrdk {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.51 21.643c.042.521.534 1.582 1.61 1.657c1.343.093 1.812-.97 1.859-1.657c-.026.552.578 1.735 1.844 1.735c1.087 0 1.599-1.183 1.656-1.735");
}

.kjd0kebjl {
  fill: var(--svg-color--aeabb5, #AEABB5);
  d: path("m14.705 18.466l1.89-.178c.729-.07 1.157.596.832 1.176a4.3 4.3 0 0 1-.95 1.127a1.1 1.1 0 0 1-.594.262c-.2.02-.417-.03-.631-.147c0 0-.65-.339-1.145-.929c-.427-.509-.13-1.242.598-1.311");
}

.ksapsyb2m {
  stop-color: var(--svg-color--b7a7d1, #B7A7D1);
  stop-opacity: 0;
}

.kt-2njnsi {
  stop-color: var(--svg-color--c4afdd, #C4AFDD);
}

.lm-pdjb-m {
  stop-color: var(--svg-color--5c5458, #5C5458);
  stop-opacity: 0;
}

.lpvelcc-y {
  stop-color: var(--svg-color--98989c, #98989C);
}

.ma110-chc {
  stop-color: var(--svg-color--c8c8cd, #C8C8CD);
  stop-opacity: 0;
}

.mauzo7bsv {
  stop-color: var(--svg-color--eeedf4, #EEEDF4);
}

.mjp0ecb6a {
  stop-color: var(--svg-color--543057, #543057);
}

.n_qpyzykw {
  d: path("M15.68 18.209a8.4 8.4 0 0 0-3.142.504c-1.422.523-2.084.912-2.084 3.224c0 5.094 2.908 6.01 5.063 5.282c2.03-.688 4.218-1.77 5.093-4.594c.449-1.447-.437-3.112-1.825-3.72a8.4 8.4 0 0 0-3.105-.696");
}

.n0ec68fkr {
  fill: var(--svg-color--9e9ba4, #9E9BA4);
  d: path("M11.683 17.493c-.41 0-.75-.34-.75-.75v-1.486c0-.41.34-.75.75-.75s.75.34.75.75v1.486c0 .41-.33.75-.75.75");
}

.n9c80wbeq {
  stop-color: var(--svg-color--dbdadd, #DBDADD);
}

.nv_pp8bfd {
  d: path("M7.58 13.206a4.533 4.533 0 1 1 0-9.066a4.533 4.533 0 0 1 0 9.066");
}

.ode3c1y9k {
  stop-color: var(--svg-color--9a88af, #9A88AF);
}

.omd0cwdvl {
  stop-color: var(--svg-color--c8c8cd, #C8C8CD);
}

.p6vd50w9p {
  stop-color: var(--svg-color--5f5254, #5F5254);
}

.p7ie-abaj {
  d: path("M24.42 13.206a4.533 4.533 0 1 0 0-9.066a4.533 4.533 0 0 0 0 9.066");
}

.p981guc6t {
  stop-color: var(--svg-color--533530, #533530);
}

.q-2g22jeb {
  stop-color: var(--svg-color--b6a4cc, #B6A4CC);
  stop-opacity: 0;
}

.q85-4xmei {
  stop-color: var(--svg-color--9a88af, #9A88AF);
  stop-opacity: 0;
}

.qcbchrk1j {
  stop-color: var(--svg-color--ada0bd, #ADA0BD);
}

.qcg9-qkkd {
  stop-color: var(--svg-color--dfdae7, #DFDAE7);
}

.r8r_t8axo {
  d: path("M28.853 19.783c-.614-5.128-2.746-9.567-6.815-11.367c-.526-.233-1.126.015-1.398.522a1.23 1.23 0 0 0 .181 1.4c2.151 2.405 3.536 5.065 3.68 9.361c.053 1.581 1.633 2.756 3.096 2.155c.832-.342 1.363-1.178 1.256-2.071");
}

.ra1d-fbuq {
  stop-color: var(--svg-color--c9c9c9, #C9C9C9);
}

.ra20jyokg {
  stop-color: var(--svg-color--b8b8bd, #B8B8BD);
}

.rj14edb9i {
  stop-color: var(--svg-color--5f5356, #5F5356);
}

.rt-ll90ye {
  stop-color: var(--svg-color--adadb2, #ADADB2);
  stop-opacity: 0;
}

.smhtebbjh {
  stop-color: var(--svg-color--3c223c, #3C223C);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.ueu24dben {
  stop-color: var(--svg-color--34222c, #34222C);
  stop-opacity: 0;
}

.unvvv2nza {
  stop-color: var(--svg-color--6a5c5e, #6A5C5E);
  stop-opacity: 0;
}

.v0arv1rpy {
  stop-color: var(--svg-color--silver, silver);
}

.vbj81cvpa {
  d: path("M7.58 11.324a2.59 2.59 0 1 1 0-5.18a2.59 2.59 0 0 1 0 5.18");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.vj72szwqa {
  d: path("M19.995 17.096c-.41 0-.75-.34-.75-.75V14.86c0-.41.34-.75.75-.75s.75.34.75.75v1.486c0 .41-.33.75-.75.75");
}

.vylhu7i4w {
  stop-color: var(--svg-color--34222c, #34222C);
}

.wj-2m1b_c {
  stop-color: var(--svg-color--e9defa, #E9DEFA);
}

.wnh0-b9bd {
  stop-color: var(--svg-color--d3bef1, #D3BEF1);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xbybj_nwx {
  stop-color: var(--svg-color--6a5c5e, #6A5C5E);
}

.xfs9v3wie {
  fill: var(--svg-color--dcdddf, #DCDDDF);
  d: path("M7.58 13.206a4.533 4.533 0 1 1 0-9.066a4.533 4.533 0 0 1 0 9.066");
}

.xnh-_nb8r {
  stop-color: var(--svg-color--c7bed5, #C7BED5);
}

.xwq91wb_x {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M15.99 21.643c0 1.045-.78 1.894-1.74 1.894s-1.74-.849-1.74-1.894");
}

.yxxpybc9a {
  d: path("M24.42 11.324a2.59 2.59 0 1 0 0-5.18a2.59 2.59 0 0 0 0 5.18");
}

.z17z3-a-u {
  stop-color: var(--svg-color--5c5458, #5C5458);
}

.zkps8y4ss {
  stop-color: var(--svg-color--5f5356, #5F5356);
  stop-opacity: 0;
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

</style>
