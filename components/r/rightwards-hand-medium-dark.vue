<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXGBTrd)"><path class="yan0tccse"/><path fill="url(#iI2inod)" class="jbc4qeb8i"/></g><path fill="url(#iNRLmzd)" class="e4m29sbft"/><g filter="url(#iAnXFOd)"><path fill="url(#ieeEaSd)" class="w8utp_bya"/></g><path fill="url(#i5wHbAd)" class="tpnqjiuaa"/><path fill="url(#ivpGsQd)" class="tpnqjiuaa"/><path fill="url(#izBwgnc)" class="tpnqjiuaa"/><path fill="url(#iYt5p6c)" class="tpnqjiuaa"/><path fill="url(#iME3lKd)" class="tpnqjiuaa"/><path fill="url(#iE4uvMc)" class="e8cbgunol"/><path fill="url(#itEXD0d)" class="e8cbgunol"/><path fill="url(#iD7lxac)" class="e8cbgunol"/><path fill="url(#imGRaCe)" class="e8cbgunol"/><g filter="url(#idBJ8Cb)"><path class="cgy0dpgab"/></g><g filter="url(#ibLu1Ac)"><path fill="url(#ifw6Sie)" class="qhyr-gbyp"/></g><path fill="url(#iPHuCtt)" class="sxetjwbkt"/><path fill="url(#iDqDlwe)" class="sxetjwbkt"/><path fill="url(#iUBaMXc)" class="sxetjwbkt"/><path fill="url(#ikZWatd)" class="sxetjwbkt"/><g filter="url(#iUfB7pb)"><path fill="url(#ihmBKic)" class="yq9nv50ex"/></g><path fill="url(#iVEUDKQ)" class="jbc4qeb8i"/><path fill="url(#i43A2Wd)" class="jbc4qeb8i"/><path fill="url(#icI2YgP)" class="jbc4qeb8i"/><path fill="url(#iFELdHb)" class="jbc4qeb8i"/><path fill="url(#iY8E7HM)" class="jbc4qeb8i"/><g filter="url(#i68Ts7b)"><path fill="url(#igHNCfl)" class="z7wb9pbsi"/></g><path fill="url(#iEPKGQc)" class="magedb-hz"/><path fill="url(#i7MIebb)" class="magedb-hz"/><path fill="url(#iLA5zRb)" class="magedb-hz"/><g filter="url(#i81cgEd)"><path fill="url(#itTqUgd)" class="imbbylbhf"/></g><defs><linearGradient id="ieeEaSd" x1="18.414" x2="11.624" y1="5.669" y2="9.977" gradientUnits="userSpaceOnUse"><stop class="wmpdpgd2s"/><stop offset="1" class="rc95nmb5x"/></linearGradient><linearGradient id="i5wHbAd" x1="20.155" x2="20.267" y1="8.296" y2="10.345" gradientUnits="userSpaceOnUse"><stop class="rbdf3jbka"/><stop offset="1" class="dn2fzfq2v"/></linearGradient><linearGradient id="ivpGsQd" x1="20.939" x2="20.924" y1="13.32" y2="12.335" gradientUnits="userSpaceOnUse"><stop class="ozrtwcc3u"/><stop offset="1" class="wuxfrd_oh"/></linearGradient><linearGradient id="iYt5p6c" x1="15.221" x2="17.221" y1="10.766" y2="10.148" gradientUnits="userSpaceOnUse"><stop offset=".236" class="fwtkxfbud"/><stop offset="1" class="befg0qb_v"/></linearGradient><linearGradient id="iE4uvMc" x1="22.111" x2="22.164" y1="11.992" y2="15.07" gradientUnits="userSpaceOnUse"><stop class="o779wcc_m"/><stop offset="1" class="y0sqikb1a"/></linearGradient><linearGradient id="iD7lxac" x1="22.485" x2="22.485" y1="18.174" y2="16.966" gradientUnits="userSpaceOnUse"><stop class="eph31t0ph"/><stop offset="1" class="o-2mplbjq"/></linearGradient><linearGradient id="imGRaCe" x1="14.924" x2="17.855" y1="14.523" y2="14.727" gradientUnits="userSpaceOnUse"><stop class="fwtkxfbud"/><stop offset="1" class="befg0qb_v"/></linearGradient><linearGradient id="ifw6Sie" x1="29.845" x2="23.682" y1="16.827" y2="25.457" gradientUnits="userSpaceOnUse"><stop class="dab0s-ypt"/><stop offset="1" class="dfai9wn8t"/></linearGradient><linearGradient id="iPHuCtt" x1="21.177" x2="21.229" y1="16.895" y2="19.679" gradientUnits="userSpaceOnUse"><stop class="wpop-zrkz"/><stop offset="1" class="ovtlo3tgf"/></linearGradient><linearGradient id="iDqDlwe" x1="21.149" x2="21.139" y1="22.808" y2="21.337" gradientUnits="userSpaceOnUse"><stop class="zy44pjbdi"/><stop offset="1" class="i6hsmyb5v"/></linearGradient><linearGradient id="iUBaMXc" x1="16.111" x2="18.85" y1="18.71" y2="19.24" gradientUnits="userSpaceOnUse"><stop class="fwtkxfbud"/><stop offset="1" class="befg0qb_v"/></linearGradient><linearGradient id="ihmBKic" x1="26.549" x2="12.986" y1="21.1" y2="21.1" gradientUnits="userSpaceOnUse"><stop class="mztcpwbis"/><stop offset="1" class="l_22_-0fa"/></linearGradient><linearGradient id="iVEUDKQ" x1="9.401" x2="9.401" y1="26.609" y2="21.255" gradientUnits="userSpaceOnUse"><stop class="luau5bboi"/><stop offset="1" class="jxo0k9edh"/></linearGradient><linearGradient id="igHNCfl" x1="15.869" x2="15.975" y1="26.45" y2="23.481" gradientUnits="userSpaceOnUse"><stop class="p8ewwlh1t"/><stop offset="1" class="rwxttgxpp"/></linearGradient><linearGradient id="iEPKGQc" x1="19.391" x2="19.145" y1="20.981" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="lf912ub6x"/><stop offset="1" class="pnpbx_b1e"/></linearGradient><linearGradient id="i7MIebb" x1="15.049" x2="17.216" y1="22.841" y2="23.286" gradientUnits="userSpaceOnUse"><stop class="izct9lbik"/><stop offset="1" class="z3yz03bwf"/></linearGradient><linearGradient id="itTqUgd" x1="23.477" x2="9.916" y1="25.28" y2="25.032" gradientUnits="userSpaceOnUse"><stop class="eegxolbhf"/><stop offset="1" class="dicqufbhu"/></linearGradient><radialGradient id="iI2inod" cx="0" cy="0" r="1" gradientTransform="matrix(2.62497 5.12502 -18.39164 9.41998 4.924 8.742)" gradientUnits="userSpaceOnUse"><stop class="n1-jsjlvj"/><stop offset="1" class="i3f-xdbsc"/></radialGradient><radialGradient id="iNRLmzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7422 -1.1133 3.24362 -2.1624 16.611 9.38)" gradientUnits="userSpaceOnUse"><stop class="fheffacoj"/><stop offset="1" class="f_1i3nthx"/></radialGradient><radialGradient id="izBwgnc" cx="0" cy="0" r="1" gradientTransform="rotate(-112.681 17.787 -2.333)scale(1.13462 1.78724)" gradientUnits="userSpaceOnUse"><stop class="asla8hrfn"/><stop offset="1" class="ibp4r2b3w"/></radialGradient><radialGradient id="iME3lKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68398 .97056 -2.27507 -3.94737 28.205 9.304)" gradientUnits="userSpaceOnUse"><stop class="l6dlypi3m"/><stop offset="1" class="w5xctx5py"/></radialGradient><radialGradient id="itEXD0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62144 .87499 -1.31993 -2.44595 29.983 13.898)" gradientUnits="userSpaceOnUse"><stop class="lyszbnb1o"/><stop offset="1" class="efu10_b8k"/></radialGradient><radialGradient id="ikZWatd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.354 .79135 -1.24433 -2.12908 27.75 18.619)" gradientUnits="userSpaceOnUse"><stop class="mhgp-hbvf"/><stop offset="1" class="xbm2wlp3c"/></radialGradient><radialGradient id="i43A2Wd" cx="0" cy="0" r="1" gradientTransform="matrix(2.2675 -.1875 .14684 1.77572 16 11.96)" gradientUnits="userSpaceOnUse"><stop class="epphb7amq"/><stop offset="1" class="h3y7wh22k"/></radialGradient><radialGradient id="icI2YgP" cx="0" cy="0" r="1" gradientTransform="matrix(2.17374 -.09375 .08645 2.00449 16 16.68)" gradientUnits="userSpaceOnUse"><stop class="epphb7amq"/><stop offset="1" class="h3y7wh22k"/></radialGradient><radialGradient id="iFELdHb" cx="0" cy="0" r="1" gradientTransform="rotate(-1.909 624.682 -462.882)scale(1.87604)" gradientUnits="userSpaceOnUse"><stop class="epphb7amq"/><stop offset="1" class="h3y7wh22k"/></radialGradient><radialGradient id="iY8E7HM" cx="0" cy="0" r="1" gradientTransform="matrix(1.06249 -2.12498 2.79983 1.39991 15.518 24.085)" gradientUnits="userSpaceOnUse"><stop class="epphb7amq"/><stop offset="1" class="h3y7wh22k"/></radialGradient><radialGradient id="iLA5zRb" cx="0" cy="0" r="1" gradientTransform="rotate(154.485 10.113 14.21)scale(1.95209 5.21489)" gradientUnits="userSpaceOnUse"><stop class="dr5gges4h"/><stop offset="1" class="nab63z5wz"/></radialGradient><filter id="iXGBTrd" width="28.215" height="24.039" x="2.017" y="2.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.270588 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6477"/></filter><filter id="iAnXFOd" width="7.823" height="5.458" x="11.832" y="4.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6477" stdDeviation=".375"/></filter><filter id="idBJ8Cb" width="12.102" height="3.414" x="15.398" y="9.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6477" stdDeviation=".5"/></filter><filter id="ibLu1Ac" width="15.808" height="4.064" x="14.438" y="14.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6477" stdDeviation=".5"/></filter><filter id="iUfB7pb" width="13.094" height="3.555" x="14.455" y="18.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6477" stdDeviation=".5"/></filter><filter id="i68Ts7b" width="21.827" height="6.11" x="3.418" y="20.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6477" stdDeviation=".5"/></filter><filter id="i81cgEd" width="13.092" height="3.521" x="11.391" y="23.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6477" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rightwards-hand-medium-dark" /></template>
<style>
.asla8hrfn {
  stop-color: var(--svg-color--593327, #593327);
}

.befg0qb_v {
  stop-color: var(--svg-color--8b5f5d, #8B5F5D);
  stop-opacity: 0;
}

.cgy0dpgab {
  fill: var(--svg-color--9f786e, #9F786E);
  d: path("m25.882 10.976l-9.484.13l.189 1.284l9.316-.194a.61.61 0 0 0-.021-1.22");
}

.dab0s-ypt {
  stop-color: var(--svg-color--9c7970, #9C7970);
}

.dfai9wn8t {
  stop-color: var(--svg-color--9c7970, #9C7970);
  stop-opacity: 0;
}

.dicqufbhu {
  stop-color: var(--svg-color--a37f72, #A37F72);
  stop-opacity: 0;
}

.dn2fzfq2v {
  stop-color: var(--svg-color--633e38, #633E38);
  stop-opacity: 0;
}

.dr5gges4h {
  stop-color: var(--svg-color--7a594d, #7A594D);
}

.e4m29sbft {
  d: path("M19.292 4.127q.03.038.06.08a2.536 2.536 0 0 1-.494 3.53L17.439 8.82l-4.512.162z");
}

.e8cbgunol {
  d: path("M26.702 17.695H26.7l.945-.027a2.406 2.406 0 0 0 .022-4.809l-.455.008l-.447.012l.008-.005l-12.6.172v4.688z");
}

.eegxolbhf {
  stop-color: var(--svg-color--a37f72, #A37F72);
}

.efu10_b8k {
  stop-color: var(--svg-color--77594d, #77594D);
  stop-opacity: 0;
}

.eph31t0ph {
  stop-color: var(--svg-color--7f574b, #7F574B);
}

.epphb7amq {
  stop-color: var(--svg-color--956c65, #956C65);
}

.f_1i3nthx {
  stop-color: var(--svg-color--543228, #543228);
  stop-opacity: 0;
}

.fheffacoj {
  stop-color: var(--svg-color--543228, #543228);
}

.ft5dv1b6b {
  fill: none;
}

.fwtkxfbud {
  stop-color: var(--svg-color--8b5f5d, #8B5F5D);
}

.h3y7wh22k {
  stop-color: var(--svg-color--956c65, #956C65);
  stop-opacity: 0;
}

.i3f-xdbsc {
  stop-color: var(--svg-color--754a4e, #754A4E);
  stop-opacity: 0;
}

.i6hsmyb5v {
  stop-color: var(--svg-color--7f584a, #7F584A);
  stop-opacity: 0;
}

.ibp4r2b3w {
  stop-color: var(--svg-color--593327, #593327);
  stop-opacity: 0;
}

.imbbylbhf {
  d: path("M23.483 24.904a.673.673 0 0 0-.664-.688c-2.142-.026-7.103-.092-9.627-.17c-.433-.014-.794.283-.8.659c-.007.37.333.677.76.685l9.644.177c.373.006.68-.29.687-.663");
}

.izct9lbik {
  stop-color: var(--svg-color--946963, #946963);
}

.jbc4qeb8i {
  d: path("M27.51 12.859a2.406 2.406 0 0 1 .135 4.809l-.945.026a2.406 2.406 0 0 1-1.4 4.393l-1.37-.025a2.405 2.405 0 0 1-1.736 4.16l-8.822-.336c-1.33-.005-3.695-.149-5.76-1.004c-3.267-1.207-5.595-4.34-5.595-8.015c0-3.716 2.379-6.877 5.701-8.055c2.11-.888 4.284-2.362 5.206-2.986l.06-.042l2.82-2.098a2.536 2.536 0 0 1 3.054 4.05l-1.424 1.088l7.953-.344a2.385 2.385 0 0 1 1.378 4.4z");
}

.jxo0k9edh {
  stop-color: var(--svg-color--9b7163, #9B7163);
  stop-opacity: 0;
}

.l_22_-0fa {
  stop-color: var(--svg-color--a07c72, #A07C72);
  stop-opacity: 0;
}

.l6dlypi3m {
  stop-color: var(--svg-color--785c50, #785C50);
}

.lf912ub6x {
  stop-color: var(--svg-color--76473d, #76473D);
}

.luau5bboi {
  stop-color: var(--svg-color--9b7163, #9B7163);
}

.lyszbnb1o {
  stop-color: var(--svg-color--77594d, #77594D);
}

.magedb-hz {
  d: path("m23.94 22.072l-8.548-.268l-.343 4.156l7.145.261a2.406 2.406 0 0 0 1.747-4.15");
}

.mhgp-hbvf {
  stop-color: var(--svg-color--775549, #775549);
}

.mztcpwbis {
  stop-color: var(--svg-color--a07c72, #A07C72);
}

.n1-jsjlvj {
  stop-color: var(--svg-color--754a4e, #754A4E);
}

.nab63z5wz {
  stop-color: var(--svg-color--7a594d, #7A594D);
  stop-opacity: 0;
}

.o-2mplbjq {
  stop-color: var(--svg-color--7f574b, #7F574B);
  stop-opacity: 0;
}

.o779wcc_m {
  stop-color: var(--svg-color--673c36, #673C36);
}

.ovtlo3tgf {
  stop-color: var(--svg-color--72443c, #72443C);
  stop-opacity: 0;
}

.ozrtwcc3u {
  stop-color: var(--svg-color--6b433c, #6B433C);
}

.p8ewwlh1t {
  stop-color: var(--svg-color--9f7467, #9F7467);
}

.pnpbx_b1e {
  stop-color: var(--svg-color--76473d, #76473D);
  stop-opacity: 0;
}

.qhyr-gbyp {
  d: path("M26.804 15.608c.302 0 .58-.061.81-.187c.38-.208.855-.43 1.244-.239c.311.153.487.51.33.819c-.542 1.065-1.67 1.197-2.384 1.17H16.211a.77.77 0 0 1-.773-.773c0-.434.355-.782.788-.776c3.493.048 9.664-.014 10.578-.014");
}

.rbdf3jbka {
  stop-color: var(--svg-color--633e38, #633E38);
}

.rc95nmb5x {
  stop-color: var(--svg-color--906c63, #906C63);
  stop-opacity: 0;
}

.rwxttgxpp {
  stop-color: var(--svg-color--9f7467, #9F7467);
  stop-opacity: 0;
}

.sxetjwbkt {
  d: path("m26.705 17.698l-12.156-.019v4.188l9.383.196l-.002-.001l1.37.025a2.406 2.406 0 0 0 1.405-4.39");
}

.tpnqjiuaa {
  d: path("m17.453 8.81l-2.78.12l1.72 4.124l10.377-.178a2.385 2.385 0 0 0-1.383-4.396l-7.953.344z");
}

.w5xctx5py {
  stop-color: var(--svg-color--785c50, #785C50);
  stop-opacity: 0;
}

.w8utp_bya {
  d: path("M15.683 8.876h-3.1l4.822-3.761a.93.93 0 0 1 1.152 1.458z");
}

.wmpdpgd2s {
  stop-color: var(--svg-color--916c63, #916C63);
}

.wpop-zrkz {
  stop-color: var(--svg-color--72443c, #72443C);
}

.wuxfrd_oh {
  stop-color: var(--svg-color--6b433c, #6B433C);
  stop-opacity: 0;
}

.xbm2wlp3c {
  stop-color: var(--svg-color--775549, #775549);
  stop-opacity: 0;
}

.y0sqikb1a {
  stop-color: var(--svg-color--673c36, #673C36);
  stop-opacity: 0;
}

.yan0tccse {
  fill: var(--svg-color--8b5f5d, #8B5F5D);
  d: path("M27.51 12.859a2.406 2.406 0 0 1 .135 4.809l-.945.026a2.406 2.406 0 0 1-1.4 4.393l-1.37-.025a2.405 2.405 0 0 1-1.736 4.16l-8.822-.336c-1.33-.005-3.695-.149-5.76-1.004c-3.267-1.207-5.595-4.34-5.595-8.015c0-3.716 2.379-6.877 5.701-8.055c2.11-.888 4.284-2.362 5.206-2.986l.06-.042l2.82-2.098a2.536 2.536 0 0 1 3.054 4.05l-1.424 1.088l7.953-.344a2.385 2.385 0 0 1 1.378 4.4z");
}

.yq9nv50ex {
  d: path("M26.549 20.666c0-.431-.35-.78-.782-.777c-2.195.015-7.039.043-9.523.006a.776.776 0 0 0-.789.776c0 .427.346.772.772.772h9.545a.777.777 0 0 0 .777-.777");
}

.z3yz03bwf {
  stop-color: var(--svg-color--946963, #946963);
  stop-opacity: 0;
}

.z7wb9pbsi {
  d: path("M11.986 25.443c-3.648-.17-6.402-1.909-7.568-3.711l19.827 1.882c0 2.014-1.511 2.252-2.452 2.226c-1.961-.052-6.16-.227-9.807-.397");
}

.zy44pjbdi {
  stop-color: var(--svg-color--7f584a, #7F584A);
}

</style>
