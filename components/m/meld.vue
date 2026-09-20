<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w9n1s6bwj"/><path class="bzj63i9mr"/><path class="tsawedbvq"/><path class="lp5jy3btg"/><path class="cfvurac5x"/><path clip-rule="evenodd" class="c0z5q7bgg"/><path class="hro_nbc1r"/><path class="dkyptk_6c"/><path class="t3s38hb4u"/><path class="cmefyda7f"/><path class="wjssmyqla"/><path class="tm-im2bqx"/><path class="nwcaln80r"/><path class="w_9_c1b2x"/><path class="iommd2bvm"/><path class="d5b26xb1j"/><path class="bm20vsnkh"/><path class="fwctugbkb"/><path fill="url(#SVGkFOTg3DN)" class="zrifwsbgj"/><path class="vdkrq2j6f"/><path class="i2fgp-b5y"/><path class="ufx02takm"/><path class="v4aonsbrh"/><path fill="url(#SVGnrFIoewR)" class="r_0flokeb"/><path fill="url(#SVGfRvOIj4D)" class="h6k72nbef"/><path fill="url(#SVGUgFuabiI)" class="g7h__1z9x"/><path fill="url(#SVGyDxjueFF)" class="urn-62bou"/><path fill="url(#SVGfWzzRbXz)" class="n0gwwac_g"/><path fill="url(#SVGoDsSJcVJ)" class="xjx80lrii"/><path class="a8clbjbtz"/><path fill="url(#SVG0RXFebbi)" class="w_ebu-b1p"/><path fill="url(#SVGKPkpi9rK)" class="d4_05ubrt"/><path class="t8hi_mg_l"/><path class="i-1_p7j5v"/><path fill="url(#SVGhApJ3e7x)" class="hn08-0f_u"/><path class="d7mc79tip"/><path class="rhcdqgbhq"/><path class="qqxt80dlw"/><path class="ccii8vb6x"/><path class="e_bs78bxy"/><path class="u76xpgb6f"/><path class="q2owp2buk"/><path clip-rule="evenodd" class="hr9-kgpac"/><path class="sixvbm50m"/><path class="w0wgm0bag"/><path class="lpp95zb_z"/><path class="z4yciob-w"/><path class="anl1p8bmy"/><path class="svo-gvbgm"/><path class="guqdsvirm"/><path class="m701kmb6d"/><path class="ne-69vw5i"/><path class="jurehgk_a"/><path class="c8i7aubqx"/><defs><linearGradient id="SVGkFOTg3DN" x1="12.046" x2="12.046" y1="7.111" y2="16.845" gradientUnits="userSpaceOnUse"><stop offset=".22" class="xr0o4bcrv"/><stop offset=".8" class="rqppr1bin"/></linearGradient><linearGradient id="SVGnrFIoewR" x1="11.918" x2="11.918" y1="6.909" y2="17.087" gradientUnits="userSpaceOnUse"><stop class="a86pbib6y"/><stop offset=".81" class="dnq0c_b1u"/><stop offset="1" class="y6jvtdbnc"/></linearGradient><linearGradient id="SVGfRvOIj4D" x1="12" x2="12" y1="6.909" y2="17.087" gradientUnits="userSpaceOnUse"><stop class="k6ol0l7uu"/><stop offset=".76" class="d-m1pkbrp"/><stop offset="1" class="d08olyf5e"/></linearGradient><linearGradient id="SVGUgFuabiI" x1="12" x2="12" y1="6.91" y2="17.088" gradientUnits="userSpaceOnUse"><stop class="auxi0l4-z"/><stop offset=".92" class="qmk4ckb7x"/><stop offset="1" class="uzkj3t_je"/></linearGradient><linearGradient id="SVGyDxjueFF" x1="12.001" x2="12.001" y1="6.899" y2="17.088" gradientUnits="userSpaceOnUse"><stop class="cuafqcbcc"/><stop offset=".89" class="gu1b0xp4u"/><stop offset="1" class="bjiqsbcnu"/></linearGradient><linearGradient id="SVGfWzzRbXz" x1="11.995" x2="11.995" y1="6.911" y2="17.186" gradientUnits="userSpaceOnUse"><stop class="oonl140cd"/><stop offset=".47" class="bgoxf1b1p"/><stop offset="1" class="qnl0ek-2d"/></linearGradient><linearGradient id="SVGoDsSJcVJ" x1="12" x2="12" y1="6.914" y2="16.962" gradientUnits="userSpaceOnUse"><stop class="xweh1qbqe"/><stop offset=".63" class="fynuxacka"/><stop offset="1" class="m4fq87tyq"/></linearGradient><linearGradient id="SVG0RXFebbi" x1="-1.837" x2="-1.837" y1="6.91" y2="17.088" gradientUnits="userSpaceOnUse"><stop class="ysjxt4afr"/><stop offset=".69" class="jx5c-bbfe"/><stop offset="1" class="c5z_8skem"/></linearGradient><linearGradient id="SVGKPkpi9rK" x1="18.728" x2="5.433" y1="11.999" y2="17.802" gradientUnits="userSpaceOnUse"><stop class="zvuedpbgm"/><stop offset=".33" class="ne494hbbb"/><stop offset="1" class="jm-edbbvy"/></linearGradient><linearGradient id="SVGhApJ3e7x" x1="19.657" x2="12.075" y1="10.601" y2="21.899" gradientUnits="userSpaceOnUse"><stop offset=".56" class="ysjxt4afr"/><stop offset="1" class="c40yv-zzm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:meld" /></template>
<style>
.a86pbib6y {
  stop-color: var(--svg-color--913d01, #913d01);
}

.a8clbjbtz {
  fill: var(--svg-color--8c7c60, #8c7c60);
  d: path("m9.37 11.613l-.094-.31l.606.501l-.054.313z");
}

.anl1p8bmy {
  fill: var(--svg-color--dfd4bb, #dfd4bb);
  d: path("M16.848 11.77a1.15 1.15 0 0 0-1.021-.493l-.079.195c.56.016.834.286.9.419c.286-.04.322.07.369.07a1.19 1.19 0 0 1 1.166-.03h.16l.047-.161a1.22 1.22 0 0 0-.642-.364c-.34-.079-.743.211-.9.364");
}

.auxi0l4-z {
  stop-color: var(--svg-color--994808, #994808);
}

.bgoxf1b1p {
  stop-color: var(--svg-color--fff680, #fff680);
}

.bjiqsbcnu {
  stop-color: var(--svg-color--cd790a, #cd790a);
}

.bm20vsnkh {
  fill: var(--svg-color--afbedb, #afbedb);
  d: path("M13.879 10.686v.966l.97.055l.176-1.205h-.728l-.423.184z");
}

.bzj63i9mr {
  fill: var(--svg-color--7de271, #7de271);
  d: path("M3 13.524c.43.05 1.197.485 1.526.697l.043.078c-1.025.211-1.471-.43-1.569-.775");
}

.c0z5q7bgg {
  fill: var(--svg-color--999cb3, #999cb3);
  fill-rule: evenodd;
  d: path("M11.933 6.977a.064.064 0 0 0-.066-.066a.066.066 0 0 0-.067.066v.438a.38.38 0 0 0-.164.685l-.43 1.307l.129.04l.144-.443l.235.31l-.34.344l.098.094l.32-.333l.169.22l.105-.08l-.18-.234l.302-.313l.074.282l.125-.035L12.09 8.1a.38.38 0 0 0-.157-.685zm-.07 1.198a.4.4 0 0 1-.106-.016l-.039.125l.16.164l.138-.11l-.047-.18a.4.4 0 0 1-.106.017m-.313.704l.254.336l.325-.332l-.258-.258l-.325.25zm.422-.337l.13.126l-.051-.188zm-.3-.117l.105.106l-.192.148z");
}

.c40yv-zzm {
  stop-color: var(--svg-color--746248, #746248);
}

.c5z_8skem {
  stop-color: var(--svg-color--655038, #655038);
}

.c8i7aubqx {
  fill: var(--svg-color--ffb73a, #ffb73a);
  d: path("M15.56 8.311c0-.145.09-.434.474-.427c.388.008.454.286.438.427a.3.3 0 0 1-.129.184c-.11.078-.176.153-.18.196h-.325a.45.45 0 0 1 .165-.263c.137-.101.11-.215.031-.223c-.074-.011-.11.079-.102.106zm.412.826a.185.185 0 1 0 0-.372a.187.187 0 0 0-.188.184c0 .105.082.188.188.188");
}

.ccii8vb6x {
  fill: var(--svg-color--e6e4b3, #e6e4b3);
  d: path("m14.352 14.62l-.587.058l-.509-2.52c-.039-.141.024-.227.06-.25l.512-.102c.172-.024.274.059.301.102l.56.814v-.998h.802l-.27 2.9h-.654v-.619l-.317-.466l.102 1.084zm-2.669.508h.775v-.344h.18l.278.735h.83c.047-.027.117-.148.066-.293l-.47-1.894l-.786-.646l-.728.04l-.814 1.056l.09.211l.266-.043zm.642-1.15v-.493h.078l.172.493z");
}

.cfvurac5x {
  fill: var(--svg-color--74c173, #74c173);
  d: path("M18.625 11.852c-.689-.036-1.158.54-1.303.83l.336.618z");
}

.cmefyda7f {
  fill: var(--svg-color--c1cae9, #c1cae9);
  d: path("M6.886 10.732c.6 0 1.088-.484 1.088-1.08s-.487-1.08-1.088-1.08s-1.088.483-1.088 1.08c0 .596.487 1.08 1.088 1.08");
}

.cuafqcbcc {
  stop-color: var(--svg-color--974403, #974403);
}

.d-m1pkbrp {
  stop-color: var(--svg-color--9d4b08, #9d4b08);
}

.d08olyf5e {
  stop-color: var(--svg-color--da7502, #da7502);
}

.d4_05ubrt {
  d: path("m11.468 14.608l-.208-.372l-1.596.9l.258.548h1.546a.24.24 0 0 0 .242-.192z");
}

.d5b26xb1j {
  fill: var(--svg-color--a3abc7, #a3abc7);
  d: path("M13.957 10.73v.9l-1.002.939v-2.32zm1.02-.192l-.128 1.021h.653l.117-.68z");
}

.d7mc79tip {
  fill: var(--svg-color--e6e4b3, #e6e4b3);
  d: path("m14.739 15.558l.884.04c.368.019 1.213-.189 1.644-1.132c.536-1.173-.008-1.901-.955-2.136v-.168h-.689l-.274 2.797h-.61zm1.584-.892l.102-.85c.102.013.305.04.34.142c-.035.152-.156.536-.442.704z");
}

.dkyptk_6c {
  fill: var(--svg-color--c1cae9, #c1cae9);
  d: path("M10.513 8.21L9.402 9.727l1.46-.235l-.353-1.284z");
}

.dnq0c_b1u {
  stop-color: var(--svg-color--a65406, #a65406);
}

.e_bs78bxy {
  fill: var(--svg-color--e6e4b3, #e6e4b3);
  d: path("m9.77 11.915l-.134 2.966c-.011.22.082.235.133.247h1.495c.184-.016.204-.082.196-.141l-.196-.693c0-.125-.152-.156-.227-.149h-.286l.513-3.083H9.358c-.219-.016-.16.184-.105.286z");
}

.ft5dv1b6b {
  fill: none;
}

.fwctugbkb {
  fill: var(--svg-color--6ab670, #6ab670);
  d: path("M18.116 13.844c.689-.744 1.824-.83 2.305-.783l-.591.783zm-.039-1.186l.38-.164l.023.062l-.477.204l-.25.352l.441-.05l.008.066l-.59.066l.332-.462a1.5 1.5 0 0 1-.114-.293c-.027-.121-.039-.258.008-.36l.063.031c-.04.079-.035.196-.004.313c.024.094.059.18.09.247l.595-.822l.05.04z");
}

.fynuxacka {
  stop-color: var(--svg-color--fef164, #fef164);
}

.g7h__1z9x {
  d: path("m6.913 15.296l-.301-.548L7.95 11l.282.406v1.73l-.438 2.16z");
}

.gu1b0xp4u {
  stop-color: var(--svg-color--9d4d08, #9d4d08);
}

.guqdsvirm {
  fill: var(--svg-color--f7efff, #f7efff);
  d: path("m13.115 8.803l1.057-.148c0 .657.775 1.095 1.158 1.24c.027.137-.156.321-.239.38H13.37l-.255-.215l-.281-.9l.281-.353z");
}

.h6k72nbef {
  d: path("m6.275 14.485l-.32-.654l.805-.794l.29.054l-.38 1.394z");
}

.hn08-0f_u {
  d: path("M15.913 16.066h-.86l-.26-.47l1.35-.426l.94-.928l-.149-1.553a1.76 1.76 0 0 1 .697 2.035a1.93 1.93 0 0 1-1.718 1.342");
}

.hr9-kgpac {
  fill: var(--svg-color--fef038, #fef038);
  fill-rule: evenodd;
  d: path("m17.995 15.52l.066-1.565h.877l.352 1.565h-.403l-.086-.391h-.313l-.032.39zm.497-.724v-.481h.133l.098.48h-.235z");
}

.hro_nbc1r {
  fill: var(--svg-color--89e77a, #89e77a);
  d: path("m18.64 11.848l-.977 1.409l.195.383c.935-.626.912-1.455.783-1.792");
}

.i-1_p7j5v {
  fill: var(--svg-color--7a694e, #7a694e);
  d: path("m11.906 15.578l-.188-.4l1.632-1.839l.509 1.62l.148.728c.04.102.028.176 0 .223h-.657c-.133.012-.22-.023-.246-.078l-.282-.548h-.118c.067.239-.027.368-.086.403h-.485a.3.3 0 0 1-.227-.11m2.066-.54l-.195-.38l.144-.814l.419-.52l.536.344l.587-1.94l.235.48l-.294 2.83l-.528.168l-.29-.548v.505h-.402c-.095-.008-.18-.086-.212-.126");
}

.i2fgp-b5y {
  fill: var(--svg-color--75c274, #75c274);
  d: path("M21 15.655c-.13-.302-.517-.43-.693-.458v.458c.36.246.61.101.693 0");
}

.iommd2bvm {
  fill: var(--svg-color--add3e8, #add3e8);
  d: path("M12.599 8.867L12 9.122v3.44l1.174.406v-2.516z");
}

.jm-edbbvy {
  stop-color: var(--svg-color--775c3c, #775c3c);
}

.jurehgk_a {
  fill: var(--svg-color--fff2db, #fff2db);
  d: path("m14.72 7.48l-.302.235l.09 1.526l.212.223l2.684-.137l.235-.235V8.075l-.157-.18z");
}

.jx5c-bbfe {
  stop-color: var(--svg-color--8c7c60, #8c7c60);
}

.k6ol0l7uu {
  stop-color: var(--svg-color--8c3300, #8c3300);
}

.lp5jy3btg {
  fill: var(--svg-color--307e4b, #307e4b);
  d: path("M4.538 14.325c-.72-.09-.974.47-1.01.763c.43-.392.9-.587 1.084-.63l-.078-.133z");
}

.lpp95zb_z {
  fill: var(--svg-color--926056, #926056);
  d: path("M16.523 11.939c-.273-.141-.833-.43-.853-.458l.094-.255l2.845-.677l.215.173l-.371 1.213l-.4.129h-.927l-.078.11l-.438-.079z");
}

.m4fq87tyq {
  stop-color: var(--svg-color--feb31c, #feb31c);
}

.m701kmb6d {
  fill: var(--svg-color--d3671d, #d3671d);
  d: path("m14.614 9.962l-.443-.485l.13-.173c.023-.035.352.188.508.302h1.609l1.154-.223l.313-.752l.04.713l-.353.457h-.423v.548c-.027.262-.235.168-.332.09l-.568-.532l-1.635.05z");
}

.n0gwwac_g {
  d: path("M5.724 15.52H4.707c-.079-.107.09-.275.18-.373l-.376-3.874a.31.31 0 0 1 .102-.293l.692-.196c.102-.062.216.02.263.07l.704 1.3l.599-1.3c.035-.183.203-.218.285-.215l.838.337l-.376 3.76H6.601l.274-1.573l-.45.79h-.36l-.43-.64l.203 1.94c.015.23-.07.258-.118.266z");
}

.ne-69vw5i {
  fill: var(--svg-color--ffd058, #ffd058);
  d: path("m14.622 6.976l-.54.43l.133 1.957l.403.434l1.616-.117l.572.532c.207.231.313.094.34 0v-.575l.395-.047l.372-.383l.04-1.433l-.357-.371l-2.974-.43z");
}

.ne494hbbb {
  stop-color: var(--svg-color--9f9073, #9f9073);
}

.nwcaln80r {
  fill: var(--svg-color--a2a5c2, #a2a5c2);
  d: path("m11.554 9.79l-1.056-1.605l.332 1.3z");
}

.oonl140cd {
  stop-color: var(--svg-color--fecf2c, #fecf2c);
}

.q2owp2buk {
  fill: var(--svg-color--fef038, #fef038);
  d: path("M17.498 15.417c.198 0 .36-.16.36-.356a.36.36 0 0 0-.36-.356c-.2 0-.36.159-.36.356s.16.356.36.356");
}

.qmk4ckb7x {
  stop-color: var(--svg-color--9c4a08, #9c4a08);
}

.qnl0ek-2d {
  stop-color: var(--svg-color--ffa111, #ffa111);
}

.qqxt80dlw {
  fill: var(--svg-color--908164, #908164);
  d: path("m15.964 14.892l.188-1.534l.281.47l-.066.802c-.04.063-.297.211-.403.259z");
}

.r_0flokeb {
  d: path("m4.987 16.105l-.285-.587l.868-.285V13.15l.298.337l.25 2.383c.032.148-.09.219-.156.234h-.979z");
}

.rhcdqgbhq {
  fill: var(--svg-color--746248, #746248);
  d: path("M16.766 13.969c.075-.54-.368-.615-.598-.583l.258.43z");
}

.rqppr1bin {
  stop-color: var(--svg-color--519a69, #519a69);
}

.sixvbm50m {
  fill: var(--svg-color--fef038, #fef038);
  d: path("M19.709 13.955h-.65l.313 1.565h.333v-1.565z");
}

.svo-gvbgm {
  fill: var(--svg-color--d492ff, #d492ff);
  d: path("m12.873 8.397l1.33-.223v.313l-1.138.184l-.274.36l.332 1.018l.247.219h1.706c.207-.122.262-.298.262-.372l.317-.09v.298l-.364.383l-1.056.047l-.678.528h-.187l.078-.489a.7.7 0 0 1-.575-.274l-.415-1.268l.415-.638z");
}

.t3s38hb4u {
  fill: var(--svg-color--989bb2, #989bb2);
  d: path("M8.423 7.494v.266l1.041.196v-.462l-.5-.22z");
}

.t8hi_mg_l {
  fill: var(--svg-color--7a694e, #7a694e);
  d: path("m11.268 14.45l-.141-.532l1.354-.716l.47.653l-.525.352l-.92-.352l.087.595z");
}

.tm-im2bqx {
  fill: var(--svg-color--a4acc7, #a4acc7);
  d: path("M6.914 9.045v1.726l.782.184V9.28zM8.87 7.57v3.753h1.174V7.91zm1.957 1.894v1.553l.782.306V9.785z");
}

.tsawedbvq {
  fill: var(--svg-color--519a69, #519a69);
  d: path("M19.38 12.67c-.88-.067-1.408.684-1.561 1.064l.419.196c.184-.137 1.53-.63 2.183-.861a2.4 2.4 0 0 0-1.04-.4");
}

.u76xpgb6f {
  fill: var(--svg-color--a8500a, #a8500a);
  d: path("m17.498 15.77l-.254-.47l.56-.313l.242.39l.239-1.052l.606-.098l.806-.18l.168.278c.137.149.106.368.075.458v1.115h-.243l-.235-.313l.106.313h-.305c-.106 0-.169-.086-.188-.129l-.106-.242h-.254v.184c0 .129-.078.18-.121.187h-.31l-.172-.274c-.2.396-.493.263-.614.145");
}

.ufx02takm {
  fill: var(--svg-color--3e221b, #3e221b);
  d: path("M5.16 17.086c-.462-.04-.83-1.018-.955-1.503l.638.72h4.54l.379-.49h2.711l.384.298l1.397.118l-.137-.705l.41-.039l.494.681l1.553-.055l.767-.184l2.818.102l.05-1.456c.13.169.236.497.247.627l-.039 1.26a.24.24 0 0 1-.207.238h-2.43a.6.6 0 0 1-.337-.105c-.344.203-.665.47-.782.497h-1.41c-.195 0-.332-.298-.375-.368l-.352-.61c.012.093.04.332.09.528c.05.195-.063.43-.13.45h-1.427l-.43-.392h-2.388c-.008.352-.211.376-.313.392H5.164zm3.737-5.236l-.207-.462l-.169.935h.376zm3.29.356c-.003-.07-.171-.43-.253-.602l-.177.939h.43z");
}

.urn-62bou {
  d: path("m8.056 16.024l-.29-.548l.771-2.63l.979-.312l.223.313l-.07 1.025h-.505l.234.422v.353l.27.481v.896z");
}

.uzkj3t_je {
  stop-color: var(--svg-color--d67302, #d67302);
}

.v4aonsbrh {
  fill: var(--svg-color--8b543d, #8b543d);
  d: path("m4.596 16.329l-.332-.603c-.106-.196-.043-.348 0-.395l.332-.47l-.403-3.635c-.031-.23.086-.348.153-.376l1.095-.403c.188-.082.333.067.38.149l.38.806l.47-.853c.077-.207.304-.235.41-.227l.974.274a.76.76 0 0 1 .317.164l.372.642l-.066.567c-.028.16.086.216.148.22h.443l-.407-.908c-.126-.278.078-.403.195-.43h2.32c.196.156.486.586.611.782l-.098.763h.599c.188-.016.43.176.524.274l-.09-.7a.39.39 0 0 1 .243-.408l2.29-.172c.28-.023.406.352.434.54h.371a.47.47 0 0 1 .38.212c.888.29 1.252 1.213 1.319 1.635h1.846l.411.795v1.017c-.011.415-.07.693-.129.712H17.58c-.188 0-.297-.227-.333-.274a1.2 1.2 0 0 1-.782.274h-1.472c-.183 0-.3-.07-.336-.137l-.274-.575l.067.438c.015.247-.102.266-.165.274h-1.213c-.317.012-.544-.274-.618-.391h-2.41v.254c-.012.305-.294.368-.431.36h-4.57a.6.6 0 0 1-.447-.195");
}

.vdkrq2j6f {
  fill: var(--svg-color--569f6d, #569f6d);
  d: path("M20.852 16.223c.043-.454-.34-.548-.536-.54l-.133.254c.113.13.626.282.665.282z");
}

.w_9_c1b2x {
  fill: var(--svg-color--a2b8cd, #a2b8cd);
  d: path("m12 10.428l-.392.106v.587l.392.677z");
}

.w_ebu-b1p {
  d: path("m11.53 11.614l-.301-.493l-.587 3.099h.454z");
}

.w0wgm0bag {
  fill: var(--svg-color--6930eb, #6930eb);
  d: path("M12.889 10.424c.125.227.406.286.532.29l-.04.418l.141.118l.728-.536l1.002-.055c.14-.04.329-.239.403-.333v-.52l-.677-.11l-.524-.301l-.263-.986l-1.076.082l-.532.336l-.137.27l.443 1.323z");
}

.w9n1s6bwj {
  fill: var(--svg-color--6fba6e, #6fba6e);
  d: path("M3.023 13.522a1.23 1.23 0 0 1 1.507.4l.117.395zm.533 1.566c.422.078.9-.18 1.087-.321l-.074-.368a1.1 1.1 0 0 0-1.017.689z");
}

.wjssmyqla {
  fill: var(--svg-color--aec4de, #aec4de);
  d: path("M5.739 9.54v1.096l.493 1.24l.68-1.13V9.023zM7.695 8.1v2.645l.529.638l.665 1.15l.54-.226l-.56-1.131V7.568l-1.174.536zM9.43 9.681v1.374h1.42V9.474z");
}

.xjx80lrii {
  d: path("M7.747 15.519H9.41c.027-.263.066-.842 0-.877c-.067-.035-.208.176-.274.286h-.76l.06-.388h.508a.22.22 0 0 0 .18-.117l.04-.301c.01-.11-.099-.157-.157-.169h-.42l.08-.575h.653c.11 0 .16-.078.172-.117l.062-.76h-.958l-.36-.36c-.122-.164-.196-.07-.212 0l-.152 1.002c-.032.18.09.263.152.278z");
}

.xr0o4bcrv {
  stop-color: var(--svg-color--6ab670, #6ab670);
}

.xweh1qbqe {
  stop-color: var(--svg-color--ffce2b, #ffce2b);
}

.y6jvtdbnc {
  stop-color: var(--svg-color--da820a, #da820a);
}

.ysjxt4afr {
  stop-color: var(--svg-color--908164, #908164);
}

.z4yciob-w {
  fill: var(--svg-color--f1ebdb, #f1ebdb);
  d: path("M16.672 11.92c-.164-.345-.693-.443-.935-.447l.665-1.37c.528-.38.94-.058 1.08.15c.59-.502 1.12-.122 1.307.128l-.438 1.534h-.165a1.27 1.27 0 0 0-1.174.063c-.148-.117-.29-.09-.34-.063z");
}

.zrifwsbgj {
  d: path("m18.935 13.24l.336-.39l-.047-.044l-.43.497c-.31.145-.556.313-.705.442l.04.047q.368-.297.806-.481c.14.023.47.114.712.274l.039-.055a2.1 2.1 0 0 0-.642-.262c.425-.18.89-.239 1.346-.172l.012-.067a2.65 2.65 0 0 0-1.467.212");
}

.zvuedpbgm {
  stop-color: var(--svg-color--98896c, #98896c);
}

</style>
