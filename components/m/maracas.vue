<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNehUiD)" class="w4f2a682v"/><path fill="url(#iRfHeTg)" class="w4f2a682v"/><path fill="url(#icnUWkc)" class="w4f2a682v"/><path fill="url(#iin7Tab)" class="w4f2a682v"/><path fill="url(#itslgfe)" class="w4f2a682v"/><path class="vkue6i6mi"/><path fill="url(#icdJwNN)" class="jf1gq4btv"/><path class="kg1zqjb4d"/><path fill="url(#ictxw3Y)" class="c7ecfobus"/><path fill="url(#izyxGAd)" class="caf98_8ga"/><path fill="url(#iS5Smxb)" class="c30p-x5ao"/><path fill="url(#iNtllcc)" class="iaux8-6xu"/><path fill="url(#iFw0F1b)" class="u58l5_b4g"/><path fill="url(#i42TCEG)" class="g5wgzrbtl"/><path fill="url(#i42TCEG)" class="o2aiyobvq"/><path fill="url(#i42TCEG)" class="mv3k54bnp"/><path fill="url(#i42TCEG)" class="fm-ykcbdq"/><path fill="url(#iIMEVDe)" class="m3qbwdbym"/><path fill="url(#iwrxZlc)" class="yx3r28bhh"/><path fill="url(#i4XSv3b)" class="m3qbwdbym"/><path fill="url(#ibUDJqc)" class="m3qbwdbym"/><path fill="url(#iubqacd)" class="m3qbwdbym"/><path fill="url(#i8Wd2Kd)" class="m3qbwdbym"/><path class="e696j7idv"/><path fill="url(#ibi2Qqc)" class="ye3ocsbvc"/><path class="y9zf-91ky"/><path fill="url(#iEvgYuD)" class="a6epqfbpi"/><path fill="url(#iPZUiMd)" class="h2okqbb8w"/><path fill="url(#iAsvGPb)" class="hy0ujrwgj"/><path fill="url(#iDEGhad)" class="adghc8bfc"/><path fill="url(#ipmkUuc)" class="d3-ltkqpu"/><path fill="url(#iQUMokb)" class="a1lxun_-j"/><path fill="url(#iQUMokb)" class="fzxf2vpcs"/><path fill="url(#iQUMokb)" class="pvpynkvsh"/><path fill="url(#iQUMokb)" class="morqsl4ue"/><defs><radialGradient id="iNehUiD" cx="0" cy="0" r="1" gradientTransform="matrix(2.6993 11.74993 -1.56118 .35865 12.467 23.094)" gradientUnits="userSpaceOnUse"><stop class="k4mhiun8h"/><stop offset=".078" class="se5gs_56y"/><stop offset="1" class="z6jt58s7g"/></radialGradient><radialGradient id="iRfHeTg" cx="0" cy="0" r="1" gradientTransform="matrix(-.3379 2.21875 -5.06559 -.77143 12.12 29.813)" gradientUnits="userSpaceOnUse"><stop class="kv0s5ljmo"/><stop offset="1" class="o9-b0wc4v"/></radialGradient><radialGradient id="icnUWkc" cx="0" cy="0" r="1" gradientTransform="matrix(1.18752 7.59375 -2.80038 .43793 9.28 23.375)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="ipgu3gb0y"/><stop offset=".85" class="lr4i_g-do"/></radialGradient><radialGradient id="iin7Tab" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 2 -1.08811 .23802 13.125 25.563)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="au8xwuldx"/><stop offset=".964" class="wafk8zb3l"/></radialGradient><radialGradient id="itslgfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 6.28125 -2.31637 .3803 14.344 21.969)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="tzslp-bpp"/><stop offset=".806" class="uir1wmb-f"/></radialGradient><radialGradient id="icdJwNN" cx="0" cy="0" r="1" gradientTransform="matrix(.89637 6.44617 -3.75781 .52254 11.217 14.281)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="i10xkgbly"/><stop offset=".517" class="jhb3i-bra"/><stop offset="1" class="ceetvf5vm"/></radialGradient><radialGradient id="ictxw3Y" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 7.95312 -6.77705 1.17167 10.967 11.266)" gradientUnits="userSpaceOnUse"><stop offset=".022" class="i10xkgbly"/><stop offset=".546" class="jhb3i-bra"/><stop offset="1" class="ceetvf5vm"/></radialGradient><radialGradient id="izyxGAd" cx="0" cy="0" r="1" gradientTransform="rotate(77.347 -.213 12.179)scale(9.41616 8.57147)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="nik8llb4c"/><stop offset=".551" class="pbtv557jp"/><stop offset=".806" class="aztbgibbi"/></radialGradient><radialGradient id="iS5Smxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 7.5625 -7.15471 1.35998 10.967 8.719)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="svbu43buv"/><stop offset="1" class="db9dl0bhf"/></radialGradient><radialGradient id="iNtllcc" cx="0" cy="0" r="1" gradientTransform="rotate(76.139 .733 10.593)scale(4.95685)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="yvvj93byx"/><stop offset="1" class="ltx_fac-p"/></radialGradient><radialGradient id="iFw0F1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -5.14655 0 10.799 7.656)" gradientUnits="userSpaceOnUse"><stop offset=".529" class="svbu43buv"/><stop offset="1" class="db9dl0bhf"/></radialGradient><radialGradient id="i42TCEG" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 8.8125 -5.44817 1.00463 10.875 9.938)" gradientUnits="userSpaceOnUse"><stop class="b364_-btn"/><stop offset=".787" class="hxtlm5_pi"/><stop offset="1" class="ozh3r1b8q"/></radialGradient><radialGradient id="iIMEVDe" cx="0" cy="0" r="1" gradientTransform="rotate(105.838 2.083 17.743)scale(12.056 1.60185)" gradientUnits="userSpaceOnUse"><stop class="k4mhiun8h"/><stop offset="1" class="z6jt58s7g"/></radialGradient><radialGradient id="iwrxZlc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31252 3.87499 -2.19862 -.7447 18.75 22.688)" gradientUnits="userSpaceOnUse"><stop offset=".486" class="vj-9flbnk"/><stop offset="1" class="uym4gwbgm"/></radialGradient><radialGradient id="i4XSv3b" cx="0" cy="0" r="1" gradientTransform="rotate(127.435 1.596 17.147)scale(2.24433 5.12399)" gradientUnits="userSpaceOnUse"><stop class="kv0s5ljmo"/><stop offset="1" class="o9-b0wc4v"/></radialGradient><radialGradient id="ibUDJqc" cx="0" cy="0" r="1" gradientTransform="rotate(109.888 1.628 15.539)scale(7.68604 2.83442)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="ipgu3gb0y"/><stop offset=".85" class="lr4i_g-do"/></radialGradient><radialGradient id="iubqacd" cx="0" cy="0" r="1" gradientTransform="rotate(108.138 .837 18.575)scale(1.90727 1.26026)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="au8xwuldx"/><stop offset=".964" class="wafk8zb3l"/></radialGradient><radialGradient id="i8Wd2Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11977 6.00201 -2.2134 -.78172 21.908 20.499)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="tzslp-bpp"/><stop offset=".806" class="uir1wmb-f"/></radialGradient><radialGradient id="ibi2Qqc" cx="0" cy="0" r="1" gradientTransform="rotate(110.859 7.212 14.007)scale(6.50819 3.79397)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="i10xkgbly"/><stop offset=".517" class="jhb3i-bra"/><stop offset="1" class="ceetvf5vm"/></radialGradient><radialGradient id="iEvgYuD" cx="0" cy="0" r="1" gradientTransform="rotate(108.967 8.664 13.347)scale(8.07111 6.87759)" gradientUnits="userSpaceOnUse"><stop offset=".022" class="i10xkgbly"/><stop offset=".546" class="jhb3i-bra"/><stop offset="1" class="ceetvf5vm"/></radialGradient><radialGradient id="iPZUiMd" cx="0" cy="0" r="1" gradientTransform="rotate(106.123 9.558 13.837)scale(9.41616 8.57147)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="nik8llb4c"/><stop offset=".551" class="pbtv557jp"/><stop offset=".806" class="aztbgibbi"/></radialGradient><radialGradient id="iAsvGPb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.38045 7.3206 -6.92586 -2.25209 25.327 7.258)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="svbu43buv"/><stop offset="1" class="db9dl0bhf"/></radialGradient><radialGradient id="iDEGhad" cx="0" cy="0" r="1" gradientTransform="rotate(104.915 10.636 12.941)scale(4.95685)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="yvvj93byx"/><stop offset="1" class="ltx_fac-p"/></radialGradient><radialGradient id="ipmkUuc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10607 3.83472 -4.511 -2.47748 25.691 6.248)" gradientUnits="userSpaceOnUse"><stop offset=".529" class="svbu43buv"/><stop offset="1" class="db9dl0bhf"/></radialGradient><radialGradient id="iQUMokb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.81787 8.5065 -5.25899 -1.7421 24.66 8.284)" gradientUnits="userSpaceOnUse"><stop class="b364_-btn"/><stop offset=".787" class="hxtlm5_pi"/><stop offset="1" class="ozh3r1b8q"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:maracas" /></template>
<style>
.a1lxun_-j {
  d: path("M26.8 8.208a.3.3 0 0 1 .376-.196l1.098.347a7.9 7.9 0 0 1-.61 2.348l-1.218-.385a.3.3 0 0 1-.195-.376z");
}

.a6epqfbpi {
  d: path("m17.805 10.977l7.84 2.477q.186-.168.365-.34a7.2 7.2 0 0 0 1.292-1.677l-4.487-2.652l-5.208-.411a7.2 7.2 0 0 0 .094 2.115q.047.242.104.488");
}

.adghc8bfc {
  d: path("m28.064 5.752l-7.815-2.47a5.7 5.7 0 0 1 1.97-1.07l2.52.413l2.329 1.119a5.7 5.7 0 0 1 .996 2.008");
}

.au8xwuldx {
  stop-color: var(--svg-color--ffdcc6, #FFDCC6);
}

.aztbgibbi {
  stop-color: var(--svg-color--e8a431, #E8A431);
}

.b364_-btn {
  stop-color: var(--svg-color--ff5e7b, #FF5E7B);
}

.c30p-x5ao {
  d: path("m4.162 9.412l9.548-1.898a7 7 0 0 0-1.07-1.434H8.384L4.602 7.677a7 7 0 0 0-.44 1.735");
}

.c7ecfobus {
  d: path("m6.162 15.599l8.065-1.603q.082-.237.157-.473a7.2 7.2 0 0 0 .325-2.092l-5.21-.165l-4.763 2.146a7.2 7.2 0 0 0 1.1 1.81q.16.19.326.377");
}

.caf98_8ga {
  d: path("m4.737 13.414l9.973-1.982a8 8 0 0 0-.046-.916c-.257-.314-.835-.943-.835-.943s.162-.74.279-1.243a8 8 0 0 0-.397-.816l-5.003.123L4.162 9.41a8 8 0 0 0-.055.943c.33.436.63.903.63.903s-.186.8-.3 1.32q.128.433.3.837");
}

.ceetvf5vm {
  stop-color: var(--svg-color--569858, #569858);
}

.d3-ltkqpu {
  d: path("m27.066 3.743l-4.849-1.532a4.5 4.5 0 0 1 2.668-.004c.88.278 1.618.819 2.181 1.536");
}

.db9dl0bhf {
  stop-color: var(--svg-color--59965c, #59965C);
}

.e696j7idv {
  fill: var(--svg-color--0078d4, #0078D4);
  d: path("M18.69 14.647c.106.588.173 1.172.169 1.747l2.81.888a9.5 9.5 0 0 1 1.141-1.333l-1.85-1.47z");
}

.fm-ykcbdq {
  d: path("M5.942 12.045a.3.3 0 0 1-.235.353l-1.25.248a8 8 0 0 1-.35-2.4l1.128-.225a.3.3 0 0 1 .352.236z");
}

.ft5dv1b6b {
  fill: none;
}

.fzxf2vpcs {
  d: path("M23.72 7.234a.3.3 0 0 1 .377-.195l1.737.549a.3.3 0 0 1 .196.376l-.549 1.738a.3.3 0 0 1-.377.196l-1.737-.55a.3.3 0 0 1-.196-.376z");
}

.g5wgzrbtl {
  d: path("M12.715 8.84a.3.3 0 0 1 .236-.352l1.129-.224a7.9 7.9 0 0 1 .594 2.352l-1.251.248a.3.3 0 0 1-.353-.236z");
}

.h2okqbb8w {
  d: path("m17.609 8.377l9.694 3.063q.222-.393.402-.824c-.075-.4-.279-1.228-.279-1.228s.499-.571.843-.956q.05-.46.045-.907l-4.444-2.3l-4.839-.633q-.271.378-.502.8c.079.54.118 1.094.118 1.094s-.55.613-.9 1.013q-.095.441-.139.878");
}

.hxtlm5_pi {
  stop-color: var(--svg-color--fb3c64, #FB3C64);
}

.hy0ujrwgj {
  d: path("m19.03 4.59l9.281 2.933a7 7 0 0 0-.247-1.772l-3.73-2.049l-4.084-.42c-.448.368-.86.807-1.22 1.308");
}

.i10xkgbly {
  stop-color: var(--svg-color--72dd6e, #72DD6E);
}

.iaux8-6xu {
  d: path("M12.64 6.08L4.602 7.677a5.7 5.7 0 0 1 1.21-1.887l2.409-.85l2.58-.141a5.7 5.7 0 0 1 1.839 1.28");
}

.ipgu3gb0y {
  stop-color: var(--svg-color--c68466, #C68466);
}

.jf1gq4btv {
  d: path("m8.706 18.387l4.238-.842c.176-.592.394-1.183.618-1.77l-3.251-.19l-2.852 1.403c.431.457.858.92 1.247 1.4");
}

.jhb3i-bra {
  stop-color: var(--svg-color--69bd70, #69BD70);
}

.k4mhiun8h {
  stop-color: var(--svg-color--ffc08f, #FFC08F);
}

.kg1zqjb4d {
  fill: var(--svg-color--ffb900, #FFB900);
  d: path("m7.458 16.99l6.102-1.213l.15-.39c.18-.467.358-.93.517-1.39L9.904 13.6l-3.742 2c.322.364.664.724 1.008 1.086z");
}

.kv0s5ljmo {
  stop-color: var(--svg-color--f17d98, #F17D98);
}

.lr4i_g-do {
  stop-color: var(--svg-color--da8a69, #DA8A69);
  stop-opacity: 0;
}

.ltx_fac-p {
  stop-color: var(--svg-color--3767ac, #3767AC);
}

.m3qbwdbym {
  d: path("M17.1 26.847c-1.063-.336-1.598-1.642-1.195-2.918c.415-1.312 1.486-2.542 2.006-3.666s1.015-2.8.938-4.31l3.103.945c-.945 1.199-1.424 2.94-1.731 4.095c-.307 1.156-.05 2.84-.465 4.153c-.404 1.275-1.592 2.037-2.655 1.701");
}

.morqsl4ue {
  d: path("M19.322 7.756a.3.3 0 0 1-.377.196l-1.214-.384a8 8 0 0 1 .849-2.272l1.095.346a.3.3 0 0 1 .196.376z");
}

.mv3k54bnp {
  d: path("M8.755 9.627a.3.3 0 0 0-.353-.236l-1.787.355a.3.3 0 0 0-.236.353l.355 1.788a.3.3 0 0 0 .353.235l1.787-.355a.3.3 0 0 0 .236-.353z");
}

.nik8llb4c {
  stop-color: var(--svg-color--ffe25a, #FFE25A);
}

.o2aiyobvq {
  d: path("M9.547 9.47a.3.3 0 0 1 .236-.353l1.787-.355a.3.3 0 0 1 .353.236l.355 1.788a.3.3 0 0 1-.236.352l-1.787.355a.3.3 0 0 1-.353-.235z");
}

.o9-b0wc4v {
  stop-color: var(--svg-color--ff9b90, #FF9B90);
  stop-opacity: 0;
}

.ozh3r1b8q {
  stop-color: var(--svg-color--cb3b52, #CB3B52);
}

.pbtv557jp {
  stop-color: var(--svg-color--ffc645, #FFC645);
}

.pvpynkvsh {
  d: path("M22.95 6.99a.3.3 0 0 0-.195-.376l-1.738-.55a.3.3 0 0 0-.376.197l-.55 1.738a.3.3 0 0 0 .196.376l1.738.55a.3.3 0 0 0 .377-.196z");
}

.se5gs_56y {
  stop-color: var(--svg-color--ffbf8f, #FFBF8F);
}

.svbu43buv {
  stop-color: var(--svg-color--77eb6d, #77EB6D);
}

.tzslp-bpp {
  stop-color: var(--svg-color--f3a772, #F3A772);
}

.u58l5_b4g {
  d: path("m10.799 4.8l-4.988.99a4.5 4.5 0 0 1 2.336-1.287a4.5 4.5 0 0 1 2.652.296");
}

.uir1wmb-f {
  stop-color: var(--svg-color--ffbc83, #FFBC83);
  stop-opacity: 0;
}

.uym4gwbgm {
  stop-color: var(--svg-color--ffc58c, #FFC58C);
  stop-opacity: 0;
}

.vj-9flbnk {
  stop-color: var(--svg-color--ffc58c, #FFC58C);
}

.vkue6i6mi {
  fill: var(--svg-color--0078d4, #0078D4);
  d: path("M8.705 18.388c.376.464.716.944.989 1.45l2.89-.574c.059-.572.19-1.146.36-1.718l-2.33-.398z");
}

.w4f2a682v {
  d: path("M13.187 29.848c-1.094.217-2.192-.67-2.453-1.983c-.268-1.35.079-2.943-.007-4.178c-.085-1.236-.458-2.944-1.252-4.23l3.175-.666c-.252 1.506.166 3.263.453 4.423s1.323 2.514 1.591 3.864c.261 1.312-.414 2.552-1.508 2.77");
}

.wafk8zb3l {
  stop-color: var(--svg-color--ffc9a7, #FFC9A7);
  stop-opacity: 0;
}

.y9zf-91ky {
  fill: var(--svg-color--ffb900, #FFB900);
  d: path("m18.272 12.82l5.932 1.875l.32-.27a44 44 0 0 0 1.12-.969l-3.597-2.43l-4.243-.047c.108.473.234.953.361 1.436z");
}

.ye3ocsbvc {
  d: path("m18.692 14.646l4.12 1.302c.439-.435.914-.848 1.393-1.254l-2.758-1.731l-3.175-.144c.158.608.31 1.219.42 1.827");
}

.yvvj93byx {
  stop-color: var(--svg-color--378df8, #378DF8);
}

.yx3r28bhh {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.1 26.847c-1.063-.336-1.598-1.642-1.195-2.918c.415-1.312 1.486-2.542 2.006-3.666s1.015-2.8.938-4.31l3.103.945c-.945 1.199-1.424 2.94-1.731 4.095c-.307 1.156-.05 2.84-.465 4.153c-.404 1.275-1.592 2.037-2.655 1.701");
}

.z6jt58s7g {
  stop-color: var(--svg-color--f6947f, #F6947F);
}

</style>
