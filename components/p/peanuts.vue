<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iiSSu0d)" class="cas0kjbvh"/><path fill="url(#iiEoySd)" class="cas0kjbvh"/><path fill="url(#iBWMm8d)" class="cas0kjbvh"/><path fill="url(#igW2Nmc)" class="cas0kjbvh"/><path fill="url(#iDcv5Ob)" class="cas0kjbvh"/><path class="w3vf-lyka"/><path fill="url(#iTdHC8r)" class="jq3gmub_f"/><path fill="url(#iqdJLEd)" class="blrv6jbth"/><path fill="url(#iMVgwBb)" class="hx2x4db-u"/><path class="l9ds28b4h"/><path fill="url(#iOoaBqb)" class="y-90kyb5v"/><path fill="url(#iyZWtPd)" class="ibzce4b_p"/><path fill="url(#ikl9tne)" class="g1h53uzae"/><path fill="url(#igZbhZd)" class="ed8bq4beo"/><path fill="url(#iLr4aBb)" class="e6ffp0oxv"/><defs><radialGradient id="iiEoySd" cx="0" cy="0" r="1" gradientTransform="rotate(164.795 14.137 5.131)scale(12.6296)" gradientUnits="userSpaceOnUse"><stop class="x233enbhl"/><stop offset="1" class="c1ssspc3g"/></radialGradient><radialGradient id="iBWMm8d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43747 7.06251 -10.30144 -3.55532 21.563 17.438)" gradientUnits="userSpaceOnUse"><stop class="hax_yzbjw"/><stop offset="1" class="i4ilbw87z"/></radialGradient><radialGradient id="igW2Nmc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 5 -8.51879 -6.38912 13.938 21)" gradientUnits="userSpaceOnUse"><stop class="e3q88of1f"/><stop offset="1" class="dhpfeevow"/></radialGradient><radialGradient id="iDcv5Ob" cx="0" cy="0" r="1" gradientTransform="matrix(18.62502 -7.3125 4.24736 10.81808 3.188 32.188)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="djhb-gbaw"/><stop offset="1" class="qhhkyzz3u"/></radialGradient><radialGradient id="iTdHC8r" cx="0" cy="0" r="1" gradientTransform="matrix(-.54136 2.5625 -2.5812 -.5453 8.188 24.75)" gradientUnits="userSpaceOnUse"><stop class="okeq8844a"/><stop offset="1" class="tf_ntb3vi"/></radialGradient><radialGradient id="iqdJLEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.16861 -2.61555 0 14.48 21.438)" gradientUnits="userSpaceOnUse"><stop class="z_f42zb0t"/><stop offset="1" class="zbqr6n1ib"/></radialGradient><radialGradient id="iMVgwBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 2.07443 -2.49809 -1.0537 9.938 17.55)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="ky2ufhbod"/><stop offset="1" class="o3kd_15xz"/></radialGradient><radialGradient id="iOoaBqb" cx="0" cy="0" r="1" gradientTransform="matrix(2.91894 -.4408 .85957 5.69206 18.394 3.438)" gradientUnits="userSpaceOnUse"><stop class="gp0st-s_a"/><stop offset="1" class="oq2qhlqbg"/></radialGradient><radialGradient id="iyZWtPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68753 2.86428 -2.88517 -1.69984 26.063 7.26)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="mewhqoqib"/><stop offset="1" class="rfxd_re4j"/></radialGradient><radialGradient id="ikl9tne" cx="0" cy="0" r="1" gradientTransform="matrix(4.9226 -1.1875 .98023 4.0634 16.327 9.25)" gradientUnits="userSpaceOnUse"><stop class="n3ob4dban"/><stop offset=".675" class="tkm4sfbmp"/></radialGradient><radialGradient id="igZbhZd" cx="0" cy="0" r="1" gradientTransform="rotate(129.979 8.814 12.508)scale(3.21007 3.86565)" gradientUnits="userSpaceOnUse"><stop class="llqg_ebvr"/><stop offset="1" class="aay61ibla"/></radialGradient><radialGradient id="iLr4aBb" cx="0" cy="0" r="1" gradientTransform="matrix(3.5954 -2.8125 2.82994 3.6177 14.688 17.438)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="uwmwwxbjp"/><stop offset="1" class="okdex0b5m"/></radialGradient><linearGradient id="iiSSu0d" x1="27.813" x2="4.125" y1="4.063" y2="27.625" gradientUnits="userSpaceOnUse"><stop class="nuz1e0bff"/><stop offset=".296" class="k77t2d-em"/><stop offset=".44" class="tyip_ogrp"/><stop offset=".517" class="hpdb_zb4z"/><stop offset=".693" class="iarya84_g"/><stop offset=".931" class="gzswwn7dv"/><stop offset="1" class="gzswwn7dv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:peanuts" /></template>
<style>
.aay61ibla {
  stop-color: var(--svg-color--ac6256, #AC6256);
}

.blrv6jbth {
  d: path("M14.876 24.433c-.316.335-.562.132-.835-.167c-.215-.244-.587-.612-.89-.913l-.252-.25c-.316-.317.01-.784.229-1.013c.22-.23.72-.995.993-1.418c.248-.386.496-.171.698.003l.057.05c.112.093.34.34.576.596c.21.227.425.46.566.593c.299.282.158.748 0 1.021c-.158.274-.826 1.163-1.142 1.498");
}

.c1ssspc3g {
  stop-color: var(--svg-color--f8d3a8, #F8D3A8);
  stop-opacity: 0;
}

.cas0kjbvh {
  d: path("M7.813 29.736c-1.37-.326-2.905-1.322-3.514-1.885c-.914-.987-2.003-2.784-2.25-5.18c-.245-2.396.457-3.523 1.336-5.214s3.318-3.372 5.557-3.493c2.224-.12 2.97-.589 3.797-1.485c.874-.948 1.127-2.02 1.268-3.641c.14-1.621 1.033-3.616 2.828-5.055c1.581-1.268 3.882-2.342 7.326-1.461c3.444.88 4.842 3.578 5.404 5.058s.828 4.305-.788 7.018s-4.288 3.602-5.94 3.673c-1.651.07-2.9.795-3.674 1.711c-.773.916-.913 1.656-1.054 3.277c-.14 1.62-.931 3.646-3.25 5.443s-5.32 1.644-7.046 1.234");
}

.dhpfeevow {
  stop-color: var(--svg-color--dda889, #DDA889);
  stop-opacity: 0;
}

.djhb-gbaw {
  stop-color: var(--svg-color--c67084, #C67084);
}

.e3q88of1f {
  stop-color: var(--svg-color--dea988, #DEA988);
}

.e6ffp0oxv {
  d: path("M15.693 17.598c.308.29.72.352.958.114c.237-.238 1.168-1.171 1.353-1.348c.184-.176.448-.581.131-.916l-.265-.284c-.37-.4-.898-.968-1.131-1.16c-.3-.247-.668-.344-.923-.097a49 49 0 0 0-1.353 1.365c-.21.238-.483.582-.131.951c.277.293.74.755 1.1 1.114z");
}

.ed8bq4beo {
  d: path("M24.054 12.347c-.276-.245-.57-.386-.924-.116c-.184.141-.322.254-.446.354c-.113.092-.213.174-.324.257c-.116.088-.271.19-.419.287c-.146.096-.284.186-.37.254c-.173.135-.359.418-.18.63c.18.212 1.117 1.139 1.303 1.267c.186.129.571.393 1.065.039l.261-.186c.468-.332 1.028-.73 1.19-.908c.192-.212.34-.457.07-.701s-.93-.888-1.226-1.177");
}

.ft5dv1b6b {
  fill: none;
}

.g1h53uzae {
  d: path("M17.645 6.848c.316-.334.562-.132.834.168c.216.243.588.612.891.913l.251.25c.317.317-.008.783-.228 1.012c-.22.23-.72.996-.993 1.419c-.248.385-.496.17-.698-.004l-.057-.05a10 10 0 0 1-.576-.595c-.21-.228-.426-.46-.566-.593c-.3-.282-.159-.75 0-1.022c.158-.273.825-1.163 1.142-1.498");
}

.gp0st-s_a {
  stop-color: var(--svg-color--986c4c, #986C4C);
}

.gzswwn7dv {
  stop-color: var(--svg-color--ad785d, #AD785D);
}

.hax_yzbjw {
  stop-color: var(--svg-color--cf828c, #CF828C);
}

.hpdb_zb4z {
  stop-color: var(--svg-color--ba8c65, #BA8C65);
}

.hx2x4db-u {
  d: path("M8.833 18.994c.276.244.57.386.924.116c.184-.141.322-.254.446-.355c.113-.091.213-.173.324-.256a9 9 0 0 1 .42-.287c.145-.096.283-.187.369-.254c.173-.135.359-.418.18-.63c-.18-.212-1.117-1.139-1.303-1.267c-.186-.13-.571-.393-1.065-.039l-.261.186c-.468.332-1.028.73-1.19.908c-.192.212-.34.456-.07.7c.27.245.93.889 1.226 1.178");
}

.i4ilbw87z {
  stop-color: var(--svg-color--cf838a, #CF838A);
  stop-opacity: 0;
}

.iarya84_g {
  stop-color: var(--svg-color--b68d67, #B68D67);
}

.ibzce4b_p {
  d: path("M25.122 5.527c-.3-.238-.647-.319-.879-.08c-.342.33-1.063 1.031-1.203 1.208c-.176.22-.378.537-.115.801a263 263 0 0 1 1.555 1.568c.264.273.607.23.8.044c.193-.185 1.036-1.013 1.212-1.224l.02-.024c.172-.206.381-.456.068-.804a62 62 0 0 0-1.458-1.489");
}

.jq3gmub_f {
  d: path("M7.295 26.142c.298.238.646.319.878.08c.343-.33 1.063-1.032 1.204-1.208c.175-.22.377-.537.114-.801a260 260 0 0 1-1.555-1.568c-.264-.273-.606-.23-.8-.044c-.193.185-1.036 1.013-1.212 1.224l-.02.024c-.172.206-.38.456-.068.804c.26.29 1.08 1.113 1.459 1.489");
}

.k77t2d-em {
  stop-color: var(--svg-color--bf9773, #BF9773);
}

.ky2ufhbod {
  stop-color: var(--svg-color--b37c49, #B37C49);
}

.l9ds28b4h {
  fill: var(--svg-color--b67e54, #B67E54);
  d: path("M29.31 10.557c.057-.194.272-.08.4.061c.099.09.21.296.153.626s-.175.775-.334 1.176c-.158.4-.57 1.176-.619 1.26c-.048.083-.119.118-.224.043c-.084-.06-.231-.242-.294-.325a.46.46 0 0 1-.035-.542c.034-.056.11-.218.198-.406c.093-.199.2-.427.285-.59c.167-.317.413-1.11.47-1.303");
}

.llqg_ebvr {
  stop-color: var(--svg-color--b36e52, #B36E52);
}

.mewhqoqib {
  stop-color: var(--svg-color--d09a6c, #D09A6C);
}

.n3ob4dban {
  stop-color: var(--svg-color--955e3b, #955E3B);
}

.nuz1e0bff {
  stop-color: var(--svg-color--ba9570, #BA9570);
}

.o3kd_15xz {
  stop-color: var(--svg-color--ad774b, #AD774B);
}

.okdex0b5m {
  stop-color: var(--svg-color--a1613e, #A1613E);
}

.okeq8844a {
  stop-color: var(--svg-color--b76c5b, #B76C5B);
}

.oq2qhlqbg {
  stop-color: var(--svg-color--ae7b50, #AE7B50);
}

.qhhkyzz3u {
  stop-color: var(--svg-color--d08679, #D08679);
  stop-opacity: 0;
}

.rfxd_re4j {
  stop-color: var(--svg-color--bd8253, #BD8253);
}

.tf_ntb3vi {
  stop-color: var(--svg-color--a56443, #A56443);
}

.tkm4sfbmp {
  stop-color: var(--svg-color--a3683f, #A3683F);
}

.tyip_ogrp {
  stop-color: var(--svg-color--b88c6d, #B88C6D);
}

.uwmwwxbjp {
  stop-color: var(--svg-color--bc8059, #BC8059);
}

.w3vf-lyka {
  fill: var(--svg-color--89634b, #89634B);
  d: path("M2.805 20.984c-.057.194-.272.08-.4-.061c-.099-.09-.21-.295-.153-.626c.057-.33.176-.775.334-1.176s.57-1.175.62-1.26c.047-.083.118-.118.223-.043c.084.06.231.242.294.326a.46.46 0 0 1 .036.541c-.035.056-.11.218-.199.407c-.092.198-.199.426-.285.589c-.167.317-.413 1.11-.47 1.303");
}

.x233enbhl {
  stop-color: var(--svg-color--f8d3a8, #F8D3A8);
}

.y-90kyb5v {
  d: path("M21.573 2.312c.204.147.39.299.337.406s-.27.227-.657.347s-1.16.468-1.432.638c-.27.17-.666.28-.862.12a6 6 0 0 1-.274-.247a2 2 0 0 0-.206-.18c-.093-.063-.133-.152 0-.281c.134-.13.942-.562 1.205-.682c.262-.12.933-.326 1.213-.339s.471.071.676.218");
}

.z_f42zb0t {
  stop-color: var(--svg-color--ce9269, #CE9269);
}

.zbqr6n1ib {
  stop-color: var(--svg-color--c27753, #C27753);
}

</style>
