<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iMLc2xG)"><path fill="url(#iQxgold)" class="n-rr88_we"/></g><g filter="url(#iv6elre)"><path fill="url(#iP6BzPI)" clip-rule="evenodd" class="tfzkarbyr"/></g><path fill="url(#iUYkJbb)" clip-rule="evenodd" class="tfzkarbyr"/><path fill="url(#ig7uUce)" clip-rule="evenodd" class="tfzkarbyr"/><path fill="url(#iBlXn9d)" clip-rule="evenodd" class="tfzkarbyr"/><path fill="url(#i45m3re)" clip-rule="evenodd" class="tfzkarbyr"/><g filter="url(#ipcfC7x)"><path class="dpkboob0l"/></g><g filter="url(#ixcqAPd)"><path fill="url(#i3CZLmb)" class="lbr1utj_x"/></g><g filter="url(#iwRZNKF)"><path fill="url(#ipL8Vbd)" class="jyefwpbgl"/></g><g filter="url(#i92B6de)"><path fill="url(#iVvnAic)" class="tw2cnnbtj"/></g><path fill="url(#i29dfyd)" class="i26yrab-i"/><path fill="url(#iiE4mIc)" class="vmvs6c-ze"/><g filter="url(#iRq8Htb)"><path fill="url(#ixwdMAt)" class="efqagibwq"/><path fill="url(#iCNm3ye)" class="efqagibwq"/><path fill="url(#ilzIz0d)" class="efqagibwq"/></g><path fill="url(#i9xRu0z)" class="ukifoquvt"/><g filter="url(#i7tlxKY)"><path fill="url(#iH8sDte)" class="i_od0waga"/></g><g filter="url(#ib0Ca6c)"><path fill="url(#i3IwePd)" class="ry7776byr"/></g><g filter="url(#iuBwkzc)"><path fill="url(#iJekYBb)" class="mgnjtnjzg"/></g><g filter="url(#iY0oNob)"><path class="pwv32cbyu"/></g><defs><linearGradient id="iQxgold" x1="8.27" x2="20.132" y1="22.882" y2="10.627" gradientUnits="userSpaceOnUse"><stop class="cix1bccwt"/><stop offset="1" class="ltdta3b0i"/></linearGradient><linearGradient id="iP6BzPI" x1="15.99" x2="15.99" y1="21.314" y2="27.3" gradientUnits="userSpaceOnUse"><stop offset=".605" class="apfivszur"/><stop offset="1" class="umcj0zf3d"/></linearGradient><linearGradient id="iUYkJbb" x1="17.014" x2="17.014" y1="27.777" y2="25.947" gradientUnits="userSpaceOnUse"><stop class="itxhvhfrr"/><stop offset="1" class="r9jjplaev"/></linearGradient><linearGradient id="i45m3re" x1="13.951" x2="13.951" y1="22.362" y2="25.233" gradientUnits="userSpaceOnUse"><stop class="i3t-tbcmt"/><stop offset="1" class="wo91hwc3d"/></linearGradient><linearGradient id="i3CZLmb" x1="21.244" x2="22.252" y1="23.156" y2="22.977" gradientUnits="userSpaceOnUse"><stop offset=".229" class="eplh9nbxj"/><stop offset="1" class="yuh9xubui"/></linearGradient><linearGradient id="ipL8Vbd" x1="10.919" x2="9.567" y1="22.383" y2="23.825" gradientUnits="userSpaceOnUse"><stop offset=".229" class="u_2--wb2y"/><stop offset="1" class="eaikkbckp"/></linearGradient><linearGradient id="iVvnAic" x1="10.917" x2="21.309" y1="20.088" y2="20.088" gradientUnits="userSpaceOnUse"><stop class="kx9keqbau"/><stop offset="1" class="ehxg5v6ar"/></linearGradient><linearGradient id="ixwdMAt" x1="11.995" x2="20.132" y1="7" y2="7" gradientUnits="userSpaceOnUse"><stop class="vaxvq0aqj"/><stop offset="1" class="ddx_jxcwo"/></linearGradient><linearGradient id="iCNm3ye" x1="11.865" x2="12.6" y1="7" y2="7" gradientUnits="userSpaceOnUse"><stop class="mje0pl8cb"/><stop offset="1" class="nn0ls-bsn"/></linearGradient><linearGradient id="ilzIz0d" x1="15.995" x2="15.995" y1="7.125" y2="6.695" gradientUnits="userSpaceOnUse"><stop class="j9htx225h"/><stop offset="1" class="ht4uk73mh"/></linearGradient><linearGradient id="i9xRu0z" x1="20.563" x2="11.383" y1="13.095" y2="13.095" gradientUnits="userSpaceOnUse"><stop class="efa5exb0r"/><stop offset="1" class="k8l-2kb-u"/></linearGradient><linearGradient id="iH8sDte" x1="12.08" x2="21.005" y1="12.495" y2="12.495" gradientUnits="userSpaceOnUse"><stop class="j_olh4-dh"/><stop offset="1" class="laqjglbwb"/></linearGradient><linearGradient id="i3IwePd" x1="22.275" x2="23.292" y1="25.159" y2="24.391" gradientUnits="userSpaceOnUse"><stop offset=".07" class="eplh9nbxj"/><stop offset="1" class="yuh9xubui"/></linearGradient><linearGradient id="iJekYBb" x1="10.265" x2="8.462" y1="23.46" y2="25.909" gradientUnits="userSpaceOnUse"><stop offset=".07" class="yw7hxmzfb"/><stop offset="1" class="yuh9xubui"/></linearGradient><filter id="iMLc2xG" width="29.5" height="29.5" x="1.245" y="1.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.133333 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9345"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.254902 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9345" result="effect2_innerShadow_18_9345"/></filter><filter id="iv6elre" width="17.988" height="7.254" x="6.996" y="20.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.298039 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9345"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.823529 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9345" result="effect2_innerShadow_18_9345"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.462745 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_9345" result="effect3_innerShadow_18_9345"/></filter><filter id="ipcfC7x" width="17.49" height="12.799" x="7.255" y="5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9345"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.462745 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9345" result="effect2_innerShadow_18_9345"/></filter><filter id="ixcqAPd" width="3.097" height="2.691" x="19.943" y="21.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9345" stdDeviation=".125"/></filter><filter id="iwRZNKF" width="3.097" height="2.691" x="8.871" y="21.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9345" stdDeviation=".125"/></filter><filter id="i92B6de" width="16.99" height="7" x="7.495" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.156863 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9345"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.305882 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9345" result="effect2_innerShadow_18_9345"/></filter><filter id="iRq8Htb" width="8.2" height="1.2" x="11.795" y="6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.192157 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9345"/></filter><filter id="i7tlxKY" width="10.91" height="7.91" x="10.595" y="8.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.647059 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9345"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.866667 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9345" result="effect2_innerShadow_18_9345"/></filter><filter id="ib0Ca6c" width="3.522" height="3.191" x="21.147" y="23.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9345" stdDeviation=".25"/></filter><filter id="iuBwkzc" width="3.522" height="3.191" x="7.243" y="23.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9345" stdDeviation=".25"/></filter><filter id="iY0oNob" width="16.392" height="1.5" x="7.804" y="25.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9345" stdDeviation=".25"/></filter><radialGradient id="ig7uUce" cx="0" cy="0" r="1" gradientTransform="matrix(1.4739 1.38496 -.93927 .9996 20.33 22.68)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="i3t-tbcmt"/><stop offset="1" class="wo91hwc3d"/></radialGradient><radialGradient id="iBlXn9d" cx="0" cy="0" r="1" gradientTransform="rotate(146.036 2.562 13.034)scale(2.38989 1.62081)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="i3t-tbcmt"/><stop offset="1" class="wo91hwc3d"/></radialGradient><radialGradient id="i29dfyd" cx="0" cy="0" r="1" gradientTransform="matrix(3.03431 0 0 2.33027 10.586 19.719)" gradientUnits="userSpaceOnUse"><stop class="fyf1asbgu"/><stop offset="1" class="tr9ozzhva"/></radialGradient><radialGradient id="iiE4mIc" cx="0" cy="0" r="1" gradientTransform="matrix(3.28125 0 0 3.21875 18.339 19.719)" gradientUnits="userSpaceOnUse"><stop class="pica-xfct"/><stop offset="1" class="fslmv6b4h"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:metro" /></template>
<style>
.apfivszur {
  stop-color: var(--svg-color--8f7a87, #8F7A87);
}

.cix1bccwt {
  stop-color: var(--svg-color--432367, #432367);
}

.ddx_jxcwo {
  stop-color: var(--svg-color--615e65, #615E65);
}

.dpkboob0l {
  fill: var(--svg-color--e5cffc, #E5CFFC);
  d: path("M23.995 17.049V6.79c0-.99-.81-1.79-1.81-1.79H9.815c-1 0-1.81.8-1.81 1.79v10.259z");
}

.eaikkbckp {
  stop-color: var(--svg-color--572046, #572046);
  stop-opacity: 0;
}

.efa5exb0r {
  stop-color: var(--svg-color--867894, #867894);
}

.efqagibwq {
  d: path("M19.495 7h-7c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h7c.28 0 .5.22.5.5s-.22.5-.5.5");
}

.ehxg5v6ar {
  stop-color: var(--svg-color--ff2b5d, #FF2B5D);
}

.eplh9nbxj {
  stop-color: var(--svg-color--6e3e5a, #6E3E5A);
}

.fslmv6b4h {
  stop-color: var(--svg-color--ff6026, #FF6026);
}

.ft5dv1b6b {
  fill: none;
}

.fyf1asbgu {
  stop-color: var(--svg-color--ffa805, #FFA805);
}

.ht4uk73mh {
  stop-color: var(--svg-color--48464a, #48464A);
  stop-opacity: 0;
}

.i_od0waga {
  d: path("M19.535 16h-7.07c-.81 0-1.47-.66-1.47-1.47v-4.07c0-.81.66-1.47 1.47-1.47h7.07c.81 0 1.47.66 1.47 1.47v4.07c-.01.82-.66 1.47-1.47 1.47");
}

.i26yrab-i {
  d: path("M12.995 20h-2c-.55 0-1-.45-1-1s.45-1 1-1h2c.55 0 1 .45 1 1c0 .56-.44 1-1 1");
}

.i3t-tbcmt {
  stop-color: var(--svg-color--674373, #674373);
}

.itxhvhfrr {
  stop-color: var(--svg-color--bc77f3, #BC77F3);
}

.j_olh4-dh {
  stop-color: var(--svg-color--4cc5ff, #4CC5FF);
}

.j9htx225h {
  stop-color: var(--svg-color--48464a, #48464A);
}

.jyefwpbgl {
  d: path("M11.689 22.438s-.897.939-1.16 1.387c-.58-.545-1.408-.172-1.408-.172c.173-.24.974-1.35 1.228-1.706s.694-.41 1.057-.156c.21.146.384.457.283.647");
}

.k8l-2kb-u {
  stop-color: var(--svg-color--645a70, #645A70);
}

.kx9keqbau {
  stop-color: var(--svg-color--db2998, #DB2998);
}

.laqjglbwb {
  stop-color: var(--svg-color--5cd9ff, #5CD9FF);
}

.lbr1utj_x {
  d: path("M20.223 22.438s.897.939 1.159 1.387c.58-.545 1.408-.172 1.408-.172c-.173-.24-.974-1.35-1.228-1.706s-.693-.41-1.056-.156c-.21.146-.385.457-.284.647");
}

.ltdta3b0i {
  stop-color: var(--svg-color--2c2632, #2C2632);
}

.mgnjtnjzg {
  d: path("m10.145 24.562l-.776 1.105l-1.626.242c.292-.398 1.091-1.522 1.345-1.878s.694-.409 1.057-.156c.21.146.101.496 0 .687");
}

.mje0pl8cb {
  stop-color: var(--svg-color--5d5b60, #5D5B60);
}

.n-rr88_we {
  d: path("M29.995 16c0 3.79-1.51 7.23-3.97 9.76c-.39.4-.8.78-1.24 1.13a13.93 13.93 0 0 1-8.79 3.11c-3.32 0-6.38-1.16-8.79-3.11c-.44-.35-.85-.73-1.24-1.13A13.95 13.95 0 0 1 1.995 16c0-7.73 6.27-14 14-14s14 6.27 14 14");
}

.nn0ls-bsn {
  stop-color: var(--svg-color--5d5b60, #5D5B60);
  stop-opacity: 0;
}

.pica-xfct {
  stop-color: var(--svg-color--ffad27, #FFAD27);
}

.pwv32cbyu {
  stroke: var(--svg-color--c0b1cf, #C0B1CF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.554 26.326h14.892");
}

.r9jjplaev {
  stop-color: var(--svg-color--bc77f3, #BC77F3);
  stop-opacity: 0;
}

.ry7776byr {
  d: path("m21.767 24.562l.775 1.105l1.627.242c-.293-.398-1.092-1.522-1.346-1.878s-.693-.409-1.056-.156c-.21.146-.102.496 0 .687");
}

.tfzkarbyr {
  fill-rule: evenodd;
  d: path("M11.033 20.55L7.91 25.366c-.215.301-.514.672-.514 1.04c0 .614.567.894 1.192.894h14.955c.504 0 1.04-.294 1.04-.907c0-.386-.266-.716-.48-1.014l-3.138-4.829c.672-.71-10.083-.16-9.932 0m11.277 5.073l-.36-.49a.86.86 0 0 0-.692-.348H10.723a.86.86 0 0 0-.693.349l-.36.49zm-11.277-2.1c-.132.21-.245.372-.286.427h10.479a12 12 0 0 0-.261-.387c-.179-.256-.343-.458-.803-.458h-8.298c-.247 0-.666.155-.83.417");
}

.tr9ozzhva {
  stop-color: var(--svg-color--fe7a0c, #FE7A0C);
}

.tw2cnnbtj {
  d: path("M7.995 16v3.24c0 2.08 1.71 3.76 3.81 3.76h8.37c2.11 0 3.81-1.68 3.81-3.76V16z");
}

.u_2--wb2y {
  stop-color: var(--svg-color--311827, #311827);
}

.ukifoquvt {
  d: path("M20.045 17h-8.09c-1.08 0-1.96-.88-1.96-1.96V9.95c0-1.08.88-1.96 1.96-1.96h8.09c1.08 0 1.96.88 1.96 1.96v5.09a1.963 1.963 0 0 1-1.96 1.96");
}

.umcj0zf3d {
  stop-color: var(--svg-color--baaaca, #BAAACA);
}

.vaxvq0aqj {
  stop-color: var(--svg-color--5c5a5f, #5C5A5F);
}

.vmvs6c-ze {
  d: path("M20.995 20h-2c-.55 0-1-.45-1-1s.45-1 1-1h2c.55 0 1 .45 1 1c0 .56-.44 1-1 1");
}

.wo91hwc3d {
  stop-color: var(--svg-color--674373, #674373);
  stop-opacity: 0;
}

.yuh9xubui {
  stop-color: var(--svg-color--865761, #865761);
  stop-opacity: 0;
}

.yw7hxmzfb {
  stop-color: var(--svg-color--663a59, #663A59);
}

</style>
