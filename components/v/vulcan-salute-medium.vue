<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iV33t8L)"><path class="mg98evxph"/><path fill="url(#ib6axdb)" class="f3gz-ouqg"/><path fill="url(#iyzWLnd)" class="f3gz-ouqg"/><path fill="url(#inQN3Ub)" class="f3gz-ouqg"/></g><path fill="url(#inZuDNd)" class="sensxp3pp"/><path fill="url(#iYuYSJb)" class="sensxp3pp"/><path fill="url(#i3E2yrb)" class="sensxp3pp"/><g filter="url(#igXYOye)"><rect transform="rotate(-22.578 5.231 9)" class="qo0iyybvv"/></g><path fill="url(#iWdnwTb)" class="mrevzwbjt"/><path fill="url(#iwnbtIb)" class="mrevzwbjt"/><path fill="url(#i37erpe)" class="mrevzwbjt"/><path fill="url(#i3uzv2d)" class="mrevzwbjt"/><path fill="url(#iWBuM7b)" class="mrevzwbjt"/><path fill="url(#ir6Ix3b)" class="mrevzwbjt"/><g filter="url(#i4F1F1d)"><rect transform="rotate(-19.107 9.578 5.753)" class="ell6l_bcy"/></g><path fill="url(#ihhhLJe)" class="gc1ylq1xm"/><path fill="url(#iZOwdtc)" class="gc1ylq1xm"/><path fill="url(#iWLe9yd)" class="gc1ylq1xm"/><path fill="url(#ionhgld)" class="gc1ylq1xm"/><path fill="url(#ioJJflb)" class="gc1ylq1xm"/><g filter="url(#iBk1T9R)"><rect fill="url(#imV25mb)" transform="rotate(16.763 19.305 3.744)" class="bt8gljpwe"/></g><path fill="url(#i8fziro)" class="z-su05kvs"/><path fill="url(#ix3qdse)" class="z-su05kvs"/><path fill="url(#iF9RXQE)" class="z-su05kvs"/><path fill="url(#iQumEic)" class="z-su05kvs"/><g filter="url(#ipJvDcy)"><rect fill="url(#iaJpQ7R)" transform="rotate(20.79 23.577 5.836)" class="hno_kpbdk"/></g><g filter="url(#itebVce)"><path stroke="url(#iqR13id)" class="jba1m2-7r"/></g><path fill="url(#ii0ipkI)" class="dgxx7zp5f"/><path fill="url(#idW5Nxd)" class="dgxx7zp5f"/><g filter="url(#iasC54s)"><path stroke="url(#iBVa4gi)" class="bwyslobzl"/></g><g filter="url(#isf70Fc)"><path stroke="url(#idlbWHd)" class="xrd80dbnt"/></g><g filter="url(#iJibvzd)"><path stroke="url(#iiWG3xe)" class="qv-1-pb-u"/></g><g filter="url(#iA1FQdC)"><path stroke="url(#i2NR3sb)" class="w_50e7bpe"/></g><g filter="url(#iigTSld)"><path stroke="url(#ipssFCd)" class="wqtcpyb_l"/></g><path fill="url(#iS5gdGY)" class="axg4lrrdx"/><path fill="url(#iV5R1Uc)" class="axg4lrrdx"/><path fill="url(#i8FDqpb)" class="axg4lrrdx"/><path fill="url(#ifhDJgc)" class="axg4lrrdx"/><path fill="url(#ilsjtoG)" class="axg4lrrdx"/><path fill="url(#iVhk9hy)" class="axg4lrrdx"/><path fill="url(#iuikKoc)" class="axg4lrrdx"/><defs><radialGradient id="ib6axdb" cx="0" cy="0" r="1" gradientTransform="matrix(5.57964 -3.27694 6.45506 10.99104 7.378 26.957)" gradientUnits="userSpaceOnUse"><stop class="tt5c64buh"/><stop offset="1" class="pzmlzj15k"/></radialGradient><radialGradient id="iyzWLnd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.50706 8.21304 -8.36063 -3.57008 22.791 25.357)" gradientUnits="userSpaceOnUse"><stop class="hm8qqzb-t"/><stop offset="1" class="wmh0ovbgt"/></radialGradient><radialGradient id="inQN3Ub" cx="0" cy="0" r="1" gradientTransform="rotate(130.206 8.856 17.136)scale(8.79664 4.43868)" gradientUnits="userSpaceOnUse"><stop class="xz-x2xb4g"/><stop offset="1" class="qtnyoe6zz"/><stop offset="1" class="h0lg6rb3o"/></radialGradient><radialGradient id="i3E2yrb" cx="0" cy="0" r="1" gradientTransform="rotate(68.515 -2.948 7.353)scale(2.99536 5.57619)" gradientUnits="userSpaceOnUse"><stop class="ufscvacyd"/><stop offset="1" class="ig0gu812s"/></radialGradient><radialGradient id="iwnbtIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.88994 .30388 -1.63403 -4.7854 13.77 9.714)" gradientUnits="userSpaceOnUse"><stop class="i7zzcxt-k"/><stop offset="1" class="vjb-lqsbc"/></radialGradient><radialGradient id="i37erpe" cx="0" cy="0" r="1" gradientTransform="matrix(.41951 -.13185 1.49361 4.7524 8.997 12.348)" gradientUnits="userSpaceOnUse"><stop class="juj6nobtx"/><stop offset="1" class="snok8xmip"/></radialGradient><radialGradient id="ir6Ix3b" cx="0" cy="0" r="1" gradientTransform="matrix(.8227 2.71004 -3.53608 1.07347 9.071 4.19)" gradientUnits="userSpaceOnUse"><stop class="ufscvacyd"/><stop offset="1" class="ig0gu812s"/></radialGradient><radialGradient id="ioJJflb" cx="0" cy="0" r="1" gradientTransform="rotate(103.309 9.096 8.633)scale(3.79934 4.20751)" gradientUnits="userSpaceOnUse"><stop class="ufscvacyd"/><stop offset="1" class="ig0gu812s"/></radialGradient><radialGradient id="iF9RXQE" cx="0" cy="0" r="1" gradientTransform="rotate(-160.567 12.693 6.183)scale(.74532 1.9169)" gradientUnits="userSpaceOnUse"><stop class="ihfhw8erw"/><stop offset="1" class="vjxsyu6tb"/></radialGradient><radialGradient id="iQumEic" cx="0" cy="0" r="1" gradientTransform="rotate(101.271 10.245 11.694)scale(3.74953 4.50938)" gradientUnits="userSpaceOnUse"><stop class="ufscvacyd"/><stop offset="1" class="ig0gu812s"/></radialGradient><radialGradient id="ii0ipkI" cx="0" cy="0" r="1" gradientTransform="matrix(1.29719 1.10259 -3.33471 3.92326 24.304 13.79)" gradientUnits="userSpaceOnUse"><stop class="v8rnowzbc"/><stop offset="1" class="oc7e2-bqu"/></radialGradient><radialGradient id="idW5Nxd" cx="0" cy="0" r="1" gradientTransform="rotate(113.749 10.265 15.267)scale(4.01662 4.13507)" gradientUnits="userSpaceOnUse"><stop class="ufscvacyd"/><stop offset="1" class="ig0gu812s"/></radialGradient><radialGradient id="iS5gdGY" cx="0" cy="0" r="1" gradientTransform="rotate(93.244 2.504 13.039)scale(19.7866 19.1478)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ug90zzbvc"/><stop offset="1" class="k7e3vqbjx"/></radialGradient><radialGradient id="iV5R1Uc" cx="0" cy="0" r="1" gradientTransform="matrix(-.02402 2.56503 -.76778 -.0072 14.082 10.382)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="olp8x4bnw"/><stop offset="1" class="e5p-5ybqv"/></radialGradient><radialGradient id="i8FDqpb" cx="0" cy="0" r="1" gradientTransform="rotate(136.84 11.88 12.638)scale(3.56633 2.41749)" gradientUnits="userSpaceOnUse"><stop class="rt4kmjb4f"/><stop offset="1" class="gfk2zmbsn"/></radialGradient><radialGradient id="ifhDJgc" cx="0" cy="0" r="1" gradientTransform="rotate(124.344 11.077 9.646)scale(2.30423 2.42474)" gradientUnits="userSpaceOnUse"><stop class="rt4kmjb4f"/><stop offset="1" class="gfk2zmbsn"/></radialGradient><radialGradient id="ilsjtoG" cx="0" cy="0" r="1" gradientTransform="rotate(137.036 9.657 6.084)scale(2.66463 2.35358)" gradientUnits="userSpaceOnUse"><stop class="rt4kmjb4f"/><stop offset="1" class="gfk2zmbsn"/></radialGradient><radialGradient id="iVhk9hy" cx="0" cy="0" r="1" gradientTransform="matrix(-.90997 2.55112 -1.66421 -.59361 11.164 5.597)" gradientUnits="userSpaceOnUse"><stop class="rt4kmjb4f"/><stop offset="1" class="gfk2zmbsn"/></radialGradient><radialGradient id="iuikKoc" cx="0" cy="0" r="1" gradientTransform="rotate(113.794 -.06 6.753)scale(1.18141 1.33457)" gradientUnits="userSpaceOnUse"><stop class="rt4kmjb4f"/><stop offset="1" class="gfk2zmbsn"/></radialGradient><linearGradient id="inZuDNd" x1="9.457" x2="7.91" y1="11.893" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="tkcmv_mtt"/><stop offset="1" class="ll5wk8mqz"/></linearGradient><linearGradient id="iYuYSJb" x1="10.183" x2="8.834" y1="14.509" y2="13.23" gradientUnits="userSpaceOnUse"><stop class="hdbhm0bnq"/><stop offset="1" class="ojod5htzj"/></linearGradient><linearGradient id="iWdnwTb" x1="8.354" x2="10.835" y1="11.739" y2="10.823" gradientUnits="userSpaceOnUse"><stop class="fga7vnbfb"/><stop offset="1" class="ph0j8v09r"/></linearGradient><linearGradient id="i3uzv2d" x1="14.003" x2="11.46" y1="9.063" y2="9.824" gradientUnits="userSpaceOnUse"><stop class="h4q015bvj"/><stop offset="1" class="lira87b8c"/></linearGradient><linearGradient id="iWBuM7b" x1="12.565" x2="12.221" y1="14.688" y2="13.594" gradientUnits="userSpaceOnUse"><stop class="hdbhm0bnq"/><stop offset="1" class="ojod5htzj"/></linearGradient><linearGradient id="ihhhLJe" x1="14.358" x2="16.911" y1="8.389" y2="9.169" gradientUnits="userSpaceOnUse"><stop class="tmao5sbfk"/><stop offset="1" class="lkusxg3wv"/></linearGradient><linearGradient id="iZOwdtc" x1="20.29" x2="19.013" y1="10.579" y2="10.211" gradientUnits="userSpaceOnUse"><stop class="o4lpdtb8o"/><stop offset="1" class="hfl9c04ai"/></linearGradient><linearGradient id="iWLe9yd" x1="19.623" x2="19.397" y1="10.556" y2="10.48" gradientUnits="userSpaceOnUse"><stop class="prsx0v-lk"/><stop offset="1" class="ydp5o2ntb"/></linearGradient><linearGradient id="ionhgld" x1="17.721" x2="15.921" y1="15.177" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="hdbhm0bnq"/><stop offset="1" class="ojod5htzj"/></linearGradient><linearGradient id="imV25mb" x1="20.72" x2="20.651" y1="4.932" y2="15.559" gradientUnits="userSpaceOnUse"><stop class="iam_5db4g"/><stop offset="1" class="teg8wmb6s"/></linearGradient><linearGradient id="i8fziro" x1="18.903" x2="22.004" y1="10.639" y2="11.633" gradientUnits="userSpaceOnUse"><stop class="k31b-4v3l"/><stop offset="1" class="tpv-d_bdi"/></linearGradient><linearGradient id="ix3qdse" x1="19.981" x2="20.922" y1="16.039" y2="14.146" gradientUnits="userSpaceOnUse"><stop class="k9ynvzb0i"/><stop offset="1" class="cw2xv3hrq"/></linearGradient><linearGradient id="iaJpQ7R" x1="25.081" x2="25.016" y1="7.024" y2="17.65" gradientUnits="userSpaceOnUse"><stop class="sngw-jk3t"/><stop offset="1" class="ue1f8db3a"/></linearGradient><linearGradient id="iqR13id" x1="21.394" x2="20.636" y1="17.163" y2="16.637" gradientUnits="userSpaceOnUse"><stop class="h2dxo4bxp"/><stop offset="1" class="vq3f7j2yw"/></linearGradient><linearGradient id="iBVa4gi" x1="27.505" x2="23.406" y1="14.916" y2="20.062" gradientUnits="userSpaceOnUse"><stop class="xcz2vtqfi"/><stop offset="1" class="kzv-ujbig"/></linearGradient><linearGradient id="idlbWHd" x1="10.298" x2="8.678" y1="17.615" y2="18.138" gradientUnits="userSpaceOnUse"><stop class="abj5228pa"/><stop offset="1" class="a8z-_3b5i"/></linearGradient><linearGradient id="iiWG3xe" x1="13.291" x2="12.044" y1="15.086" y2="15.036" gradientUnits="userSpaceOnUse"><stop class="abj5228pa"/><stop offset="1" class="a8z-_3b5i"/></linearGradient><linearGradient id="i2NR3sb" x1="18.118" x2="16.865" y1="15.133" y2="16.218" gradientUnits="userSpaceOnUse"><stop class="abj5228pa"/><stop offset="1" class="a8z-_3b5i"/></linearGradient><linearGradient id="ipssFCd" x1="21.894" x2="20.642" y1="17.358" y2="18.443" gradientUnits="userSpaceOnUse"><stop class="abj5228pa"/><stop offset="1" class="a8z-_3b5i"/></linearGradient><filter id="iV33t8L" width="27.027" height="28.645" x="3.249" y="1.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.396078 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1647"/></filter><filter id="igXYOye" width="6.832" height="10.115" x="3.961" y="7.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1647" stdDeviation=".75"/></filter><filter id="i4F1F1d" width="6.862" height="11.328" x="8.281" y="3.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1647" stdDeviation=".75"/></filter><filter id="iBk1T9R" width="7.078" height="13.072" x="14.974" y="2.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1647" stdDeviation=".75"/></filter><filter id="ipJvDcy" width="7.735" height="12.875" x="18.597" y="4.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1647" stdDeviation=".75"/></filter><filter id="itebVce" width="2.968" height="5.692" x="20.248" y="12.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1647" stdDeviation=".3"/></filter><filter id="iasC54s" width="8.372" height="8.6" x="21.133" y="12.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1647" stdDeviation=".75"/></filter><filter id="isf70Fc" width="4.049" height="3.811" x="7.017" y="14.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1647" stdDeviation=".3"/></filter><filter id="iJibvzd" width="3.874" height="3.076" x="10.872" y="12.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1647" stdDeviation=".3"/></filter><filter id="iA1FQdC" width="4.556" height="2.719" x="14.299" y="13.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1647" stdDeviation=".3"/></filter><filter id="iigTSld" width="4.556" height="2.719" x="18.076" y="15.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1647" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:vulcan-salute-medium" /></template>
<style>
.a8z-_3b5i {
  stop-color: var(--svg-color--b58d7b, #B58D7B);
  stop-opacity: 0;
}

.abj5228pa {
  stop-color: var(--svg-color--b58d7b, #B58D7B);
}

.axg4lrrdx {
  d: path("M21.22 5.413a2.45 2.45 0 0 0-1.591-3.071A2.436 2.436 0 0 0 16.56 3.9a290 290 0 0 0-2.42 7.813c-.042.142-.241.147-.287.006c-.602-1.824-1.562-4.734-1.86-5.614c-.447-1.312-1.892-1.94-3.173-1.485a2.43 2.43 0 0 0-1.475 3.103l.369 1.034a2.46 2.46 0 0 0-2.891-.986A2.447 2.447 0 0 0 3.335 10.9l.68 1.904c.236.696.907 2.518 1.15 4.869q.034.318.066.645c.244 2.454.52 5.22 1.957 7.523a8.35 8.35 0 0 0 7.296 4.277a8.3 8.3 0 0 0 3.484-.758c1.363-.584 2.625-1.481 3.607-2.802c1.162-1.472 1.55-2.166 2.143-3.23c.102-.184.211-.378.331-.59c.578-1.02 1.767-2.611 2.45-3.496l2.29-2.58c.954-1.03 1.043-2.549-.105-3.61c-1.032-.952-2.74-.806-3.87.438l-2.289 2.457l3.153-8.221a2.456 2.456 0 0 0-1.465-3.181c-1.265-.458-2.671.182-3.128 1.446q-.199.55-.426 1.187z");
}

.bt8gljpwe {
  width: 1.494px;
  height: 10.452px;
  x: 19.305px;
  y: 3.744px;
  rx: 0.747px;
}

.bwyslobzl {
  stroke-linecap: round;
  d: path("m23.133 19.288l4.372-4.6");
}

.cw2xv3hrq {
  stop-color: var(--svg-color--b5867b, #B5867B);
  stop-opacity: 0;
}

.dgxx7zp5f {
  d: path("m22.549 15.929l-.008.011c-.349 1.417-.32 4.26 1.724 6.455c.62-1.007 1.633-2.361 2.242-3.152l2.284-2.58c.953-1.03 1.042-2.549-.104-3.61c-1.03-.952-2.735-.806-3.862.438l-2.284 2.457z");
}

.e5p-5ybqv {
  stop-color: var(--svg-color--7c5e50, #7C5E50);
  stop-opacity: 0;
}

.ell6l_bcy {
  width: 1.494px;
  height: 8.726px;
  x: 9.578px;
  y: 5.753px;
  fill: var(--svg-color--c69e87, #C69E87);
  rx: 0.747px;
}

.f3gz-ouqg {
  d: path("M21.238 5.413a2.45 2.45 0 0 0-1.588-3.071A2.43 2.43 0 0 0 16.588 3.9c-.65 2.013-1.61 5.042-2.414 7.812c-.042.142-.241.147-.287.006c-.6-1.825-1.558-4.734-1.857-5.613c-.445-1.312-1.886-1.94-3.165-1.485a2.43 2.43 0 0 0-1.472 3.103l.368 1.034a2.45 2.45 0 0 0-4.37 2.143l.68 1.904c.235.696.904 2.518 1.147 4.869l.065.645c.245 2.454.52 5.22 1.954 7.523a8.33 8.33 0 0 0 7.28 4.277a8.3 8.3 0 0 0 3.476-.758c1.36-.584 2.62-1.481 3.6-2.802c1.16-1.472 1.546-2.166 2.138-3.23l.33-.59c.577-1.02 1.764-2.611 2.446-3.496l2.284-2.58c.953-1.03 1.042-2.549-.104-3.61c-1.03-.952-2.735-.806-3.862.438l-2.284 2.457l3.147-8.221a2.457 2.457 0 0 0-1.462-3.181c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.fga7vnbfb {
  stop-color: var(--svg-color--82534b, #82534B);
}

.ft5dv1b6b {
  fill: none;
}

.gc1ylq1xm {
  d: path("M14.09 11.81c.084 2.688 2.763 3.825 3.942 3.481l2.864-8.797l.342-1.081a2.45 2.45 0 0 0-1.588-3.071A2.43 2.43 0 0 0 16.588 3.9c-.65 2.013-1.61 5.042-2.414 7.812a.15.15 0 0 1-.083.097");
}

.gfk2zmbsn {
  stop-color: var(--svg-color--c8a08a, #C8A08A);
  stop-opacity: 0;
}

.h0lg6rb3o {
  stop-color: var(--svg-color--a5757b, #A5757B);
  stop-opacity: 0;
}

.h2dxo4bxp {
  stop-color: var(--svg-color--c59d83, #C59D83);
}

.h4q015bvj {
  stop-color: var(--svg-color--a28370, #A28370);
}

.hdbhm0bnq {
  stop-color: var(--svg-color--b3857a, #B3857A);
}

.hfl9c04ai {
  stop-color: var(--svg-color--755045, #755045);
  stop-opacity: 0;
}

.hm8qqzb-t {
  stop-color: var(--svg-color--be8b81, #BE8B81);
}

.hno_kpbdk {
  width: 1.589px;
  height: 10.452px;
  x: 23.577px;
  y: 5.836px;
  rx: 0.794px;
}

.i7zzcxt-k {
  stop-color: var(--svg-color--8d7464, #8D7464);
}

.iam_5db4g {
  stop-color: var(--svg-color--b08278, #B08278);
}

.ig0gu812s {
  stop-color: var(--svg-color--a0826a, #A0826A);
  stop-opacity: 0;
}

.ihfhw8erw {
  stop-color: var(--svg-color--997d6b, #997D6B);
}

.jba1m2-7r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m21.148 17.163l1.168-3.891");
}

.juj6nobtx {
  stop-color: var(--svg-color--59312b, #59312B);
}

.k31b-4v3l {
  stop-color: var(--svg-color--774d3f, #774D3F);
}

.k7e3vqbjx {
  stop-color: var(--svg-color--9c5c8c, #9C5C8C);
}

.k9ynvzb0i {
  stop-color: var(--svg-color--b5867b, #B5867B);
}

.kzv-ujbig {
  stop-color: var(--svg-color--c09683, #C09683);
  stop-opacity: 0;
}

.lira87b8c {
  stop-color: var(--svg-color--a28370, #A28370);
  stop-opacity: 0;
}

.lkusxg3wv {
  stop-color: var(--svg-color--866658, #866658);
  stop-opacity: 0;
}

.ll5wk8mqz {
  stop-color: var(--svg-color--8c6654, #8C6654);
  stop-opacity: 0;
}

.mg98evxph {
  fill: var(--svg-color--b3857a, #B3857A);
  d: path("M21.238 5.413a2.45 2.45 0 0 0-1.588-3.071A2.43 2.43 0 0 0 16.588 3.9c-.65 2.013-1.61 5.042-2.414 7.812c-.042.142-.241.147-.287.006c-.6-1.825-1.558-4.734-1.857-5.613c-.445-1.312-1.886-1.94-3.165-1.485a2.43 2.43 0 0 0-1.472 3.103l.368 1.034a2.45 2.45 0 0 0-4.37 2.143l.68 1.904c.235.696.904 2.518 1.147 4.869l.065.645c.245 2.454.52 5.22 1.954 7.523a8.33 8.33 0 0 0 7.28 4.277a8.3 8.3 0 0 0 3.476-.758c1.36-.584 2.62-1.481 3.6-2.802c1.16-1.472 1.546-2.166 2.138-3.23l.33-.59c.577-1.02 1.764-2.611 2.446-3.496l2.284-2.58c.953-1.03 1.042-2.549-.104-3.61c-1.03-.952-2.735-.806-3.862.438l-2.284 2.457l3.147-8.221a2.457 2.457 0 0 0-1.462-3.181c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.mrevzwbjt {
  d: path("M13.886 11.72a.15.15 0 0 0 .038.06l.495 1.981c-1.612 1.435-3.435 1.475-4.143 1.387l-.238-.598l.003-.004L7.743 8.73l.018.028l-.368-1.034a2.43 2.43 0 0 1 1.472-3.103c1.278-.456 2.72.173 3.165 1.485c.299.88 1.257 3.788 1.856 5.613");
}

.o4lpdtb8o {
  stop-color: var(--svg-color--755045, #755045);
}

.oc7e2-bqu {
  stop-color: var(--svg-color--936f58, #936F58);
  stop-opacity: 0;
}

.ojod5htzj {
  stop-color: var(--svg-color--b3857a, #B3857A);
  stop-opacity: 0;
}

.olp8x4bnw {
  stop-color: var(--svg-color--7c5e50, #7C5E50);
}

.ph0j8v09r {
  stop-color: var(--svg-color--82534b, #82534B);
  stop-opacity: 0;
}

.prsx0v-lk {
  stop-color: var(--svg-color--51312a, #51312A);
}

.pzmlzj15k {
  stop-color: var(--svg-color--956667, #956667);
  stop-opacity: 0;
}

.qo0iyybvv {
  width: 1.494px;
  height: 7.581px;
  x: 5.231px;
  y: 9px;
  fill: var(--svg-color--c69e87, #C69E87);
  rx: 0.747px;
}

.qtnyoe6zz {
  stop-color: var(--svg-color--86575f, #86575F);
  stop-opacity: 0;
}

.qv-1-pb-u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M11.772 14.183c.363-.056 1.513-.346 2.074-1.276");
}

.rt4kmjb4f {
  stop-color: var(--svg-color--c8a08a, #C8A08A);
}

.sensxp3pp {
  d: path("M4.956 15.951a4.99 4.99 0 0 0 5.085-1.405L7.743 8.73a2.45 2.45 0 0 0-4.351 2.17l.678 1.904l.058.168c.196.571.557 1.623.828 2.978");
}

.sngw-jk3t {
  stop-color: var(--svg-color--b7897d, #B7897D);
}

.snok8xmip {
  stop-color: var(--svg-color--59312b, #59312B);
  stop-opacity: 0;
}

.teg8wmb6s {
  stop-color: var(--svg-color--b08278, #B08278);
  stop-opacity: 0;
}

.tkcmv_mtt {
  stop-color: var(--svg-color--8c6654, #8C6654);
}

.tmao5sbfk {
  stop-color: var(--svg-color--866658, #866658);
}

.tpv-d_bdi {
  stop-color: var(--svg-color--774d3f, #774D3F);
  stop-opacity: 0;
}

.tt5c64buh {
  stop-color: var(--svg-color--956667, #956667);
}

.ue1f8db3a {
  stop-color: var(--svg-color--b7897d, #B7897D);
  stop-opacity: 0;
}

.ufscvacyd {
  stop-color: var(--svg-color--a0826a, #A0826A);
}

.ug90zzbvc {
  stop-color: var(--svg-color--9c5c8c, #9C5C8C);
  stop-opacity: 0;
}

.v8rnowzbc {
  stop-color: var(--svg-color--936f58, #936F58);
}

.vjb-lqsbc {
  stop-color: var(--svg-color--8d7464, #8D7464);
  stop-opacity: 0;
}

.vjxsyu6tb {
  stop-color: var(--svg-color--9e7d69, #9E7D69);
  stop-opacity: 0;
}

.vq3f7j2yw {
  stop-color: var(--svg-color--c59d83, #C59D83);
  stop-opacity: 0;
}

.w_50e7bpe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M15.2 13.998c.404.297 1.523.897 2.755.918");
}

.wmh0ovbgt {
  stop-color: var(--svg-color--be8b81, #BE8B81);
  stop-opacity: 0;
}

.wqtcpyb_l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M18.976 16.223c.405.297 1.524.897 2.756.919");
}

.xcz2vtqfi {
  stop-color: var(--svg-color--c09683, #C09683);
}

.xrd80dbnt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M7.917 17.142c.332-.159 1.522-1.111 2.249-2.01");
}

.xz-x2xb4g {
  stop-color: var(--svg-color--a5757b, #A5757B);
}

.ydp5o2ntb {
  stop-color: var(--svg-color--51312a, #51312A);
  stop-opacity: 0;
}

.z-su05kvs {
  d: path("m20.806 6.777l-2.85 8.68c.46.614 1.787 1.854 3.799 1.94c0-.037.3-.584.787-1.45l3.146-8.22a2.457 2.457 0 0 0-1.462-3.181c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

</style>
