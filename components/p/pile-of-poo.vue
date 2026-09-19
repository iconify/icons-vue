<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ibjfvXc)" class="i29p1nb8u"/><path fill="url(#ix2pjXb)" class="vjgdjc8dx"/><path fill="url(#i6IFbtd)" class="i29p1nb8u"/><path fill="url(#ivZiNhb)" class="i29p1nb8u"/><path fill="url(#iXg7pCD)" class="khgt2ey5i"/><path fill="url(#iy4IaQe)" class="i29p1nb8u"/><path fill="url(#iVVWv8b)" class="i29p1nb8u"/><path fill="url(#ipmbN1d)" class="i29p1nb8u"/><path fill="url(#iUwl7Kd)" class="i29p1nb8u"/><path fill="url(#i4QHGFc)" class="i29p1nb8u"/><path fill="url(#iymLpsu)" class="i29p1nb8u"/><path fill="url(#iZ9fhXc)" class="i29p1nb8u"/><path fill="url(#iDNJrme)" class="i29p1nb8u"/><path fill="url(#iBNLXpc)" class="i29p1nb8u"/><path fill="url(#irUReZc)" class="i29p1nb8u"/><path fill="url(#ip0hv3d)" class="i29p1nb8u"/><path fill="url(#i0KEisc)" class="i29p1nb8u"/><path fill="url(#iMAo8uk)" class="i29p1nb8u"/><path fill="url(#iTMXXXc)" class="p6_tj57_f"/><path fill="url(#i65ECCc)" class="ow43-6juj"/><path fill="url(#i8P09Eb)" class="p6_tj57_f"/><path fill="url(#irULOYl)" class="pzjjoubty"/><path clip-rule="evenodd" class="h_ah1cmjl"/><path fill="url(#inL8Eeb)" clip-rule="evenodd" class="yr3_wsb7a"/><defs><radialGradient id="ix2pjXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.93279 -1.99692 0 16 19.316)" gradientUnits="userSpaceOnUse"><stop class="vts10ddjd"/><stop offset="1" class="yq8yv4hsr"/></radialGradient><radialGradient id="ivZiNhb" cx="0" cy="0" r="1" gradientTransform="rotate(45 -9.262 40.408)scale(.78907 .93419)" gradientUnits="userSpaceOnUse"><stop class="qcu7njknd"/><stop offset=".523" class="rdbk80vlp"/><stop offset=".95" class="qzc47kbif"/><stop offset="1" class="qzc47kbif"/></radialGradient><radialGradient id="iXg7pCD" cx="0" cy="0" r="1" gradientTransform="rotate(73.544 2.953 21.463)scale(5.19048 14.2032)" gradientUnits="userSpaceOnUse"><stop class="pdqzkwbff"/><stop offset=".358" class="n6i4dzjkn"/><stop offset=".617" class="ejsoz3bco"/></radialGradient><radialGradient id="iy4IaQe" cx="0" cy="0" r="1" gradientTransform="matrix(4.5301 -.25522 .61006 10.82863 9.893 15.736)" gradientUnits="userSpaceOnUse"><stop class="q1cg_fbjr"/><stop offset="1" class="tm5t5qbwm"/></radialGradient><radialGradient id="iVVWv8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.16215 5.2581 -16.89105 3.73328 23.649 23.203)" gradientUnits="userSpaceOnUse"><stop class="jo5a2we8r"/><stop offset=".818" class="dvo5-tbnw"/><stop offset="1" class="ejsoz3bco"/></radialGradient><radialGradient id="ipmbN1d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.56339 0 0 -5.74798 20.89 19.882)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="i-xe72b-v"/><stop offset=".908" class="tu-jnobzw"/><stop offset="1" class="q6fr7ubwa"/></radialGradient><radialGradient id="iUwl7Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22533 0 0 -5.39871 10.054 19.882)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="i-xe72b-v"/><stop offset=".908" class="tu-jnobzw"/><stop offset="1" class="q6fr7ubwa"/></radialGradient><radialGradient id="i4QHGFc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.79 8.29 3.52)scale(1.55639 .47514)" gradientUnits="userSpaceOnUse"><stop class="zp_thu8kx"/><stop offset=".347" class="tjs6mbctb"/><stop offset=".827" class="k5f4-0blm"/><stop offset="1" class="a0ld3zbim"/></radialGradient><radialGradient id="iymLpsu" cx="0" cy="0" r="1" gradientTransform="matrix(.55122 .84848 -1.85573 1.20559 20.441 10.438)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="h9fg3hbtm"/><stop offset=".389" class="yapnhdbrf"/><stop offset="1" class="w0b78qitq"/></radialGradient><radialGradient id="iZ9fhXc" cx="0" cy="0" r="1" gradientTransform="rotate(71.664 1.34 16.128)scale(2.66256 6.08868)" gradientUnits="userSpaceOnUse"><stop class="dzf4wz_lo"/><stop offset=".656" class="nvxoal5ng"/><stop offset="1" class="ejsoz3bco"/></radialGradient><radialGradient id="iDNJrme" cx="0" cy="0" r="1" gradientTransform="matrix(2.0668 1.18841 -2.71765 4.72635 19.318 8.78)" gradientUnits="userSpaceOnUse"><stop class="dzf4wz_lo"/><stop offset=".656" class="nvxoal5ng"/><stop offset=".868" class="cqxg5978i"/><stop offset="1" class="ejsoz3bco"/></radialGradient><radialGradient id="iBNLXpc" cx="0" cy="0" r="1" gradientTransform="rotate(-30.018 52.485 3.512)scale(2.45416 4.3786)" gradientUnits="userSpaceOnUse"><stop class="n1roefb9n"/><stop offset=".331" class="gmu-pq1ta"/><stop offset="1" class="fboe7xb-h"/></radialGradient><radialGradient id="irUReZc" cx="0" cy="0" r="1" gradientTransform="matrix(2.1672 .04072 -.09432 5.01933 3.82 22.95)" gradientUnits="userSpaceOnUse"><stop class="pab_xvq1g"/><stop offset=".225" class="z1iotfbis"/><stop offset="1" class="fboe7xb-h"/></radialGradient><radialGradient id="ip0hv3d" cx="0" cy="0" r="1" gradientTransform="rotate(107.167 2.604 11.703)scale(1.51953 5.72417)" gradientUnits="userSpaceOnUse"><stop class="sywvuablk"/><stop offset=".734" class="b82qbmbug"/><stop offset="1" class="u72gm6rai"/></radialGradient><radialGradient id="i0KEisc" cx="0" cy="0" r="1" gradientTransform="rotate(84.472 2.046 16.266)scale(1.22741 4.62324)" gradientUnits="userSpaceOnUse"><stop class="w0fyavbiz"/><stop offset=".705" class="cwmayg07s"/><stop offset="1" class="vrb56cbwk"/></radialGradient><radialGradient id="iMAo8uk" cx="0" cy="0" r="1" gradientTransform="matrix(.33398 .83496 -3.145 1.258 19.74 12.113)" gradientUnits="userSpaceOnUse"><stop class="w0fyavbiz"/><stop offset=".705" class="cwmayg07s"/><stop offset="1" class="vrb56cbwk"/></radialGradient><radialGradient id="iTMXXXc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.80632 7.20122 -3.29838 -4.03356 16.592 7.641)" gradientUnits="userSpaceOnUse"><stop offset=".408" class="amote7b1v"/><stop offset="1" class="lz-tgvbga"/></radialGradient><radialGradient id="i8P09Eb" cx="0" cy="0" r="1" gradientTransform="rotate(60.732 3.609 17.445)scale(5.97276 8.96174)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="kr2taiq9t"/><stop offset="1" class="wr-x9vb9c"/></radialGradient><linearGradient id="ibjfvXc" x1="16" x2="16" y1="3" y2="31.723" gradientUnits="userSpaceOnUse"><stop class="dkwoqxb5x"/><stop offset=".75" class="dkwoqxb5x"/><stop offset=".907" class="kakv7tbpb"/><stop offset=".977" class="g5s837qfj"/></linearGradient><linearGradient id="i6IFbtd" x1=".836" x2="16" y1="15.755" y2="31.069" gradientUnits="userSpaceOnUse"><stop class="nyzynkpue"/><stop offset=".277" class="bpufepbrg"/></linearGradient><linearGradient id="i65ECCc" x1="17.913" x2="17.498" y1="12.068" y2="10.436" gradientUnits="userSpaceOnUse"><stop class="syr11bbei"/><stop offset="1" class="fjfp6tgim"/></linearGradient><linearGradient id="irULOYl" x1="16.078" x2="16.078" y1="29.725" y2="24.537" gradientUnits="userSpaceOnUse"><stop class="ko-qjgbdd"/><stop offset="1" class="ovq2jn1ik"/></linearGradient><linearGradient id="inL8Eeb" x1="18.434" x2="17.797" y1="16.337" y2="22.18" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pile-of-poo" /></template>
<style>
.a0ld3zbim {
  stop-color: var(--svg-color--aa7367, #AA7367);
  stop-opacity: 0;
}

.amote7b1v {
  stop-color: var(--svg-color--905243, #905243);
  stop-opacity: 0;
}

.b82qbmbug {
  stop-color: var(--svg-color--ad7367, #AD7367);
  stop-opacity: 0.185;
}

.bpufepbrg {
  stop-color: var(--svg-color--7c574f, #7C574F);
  stop-opacity: 0;
}

.cqxg5978i {
  stop-color: var(--svg-color--dd978a, #DD978A);
  stop-opacity: 0.051;
}

.cwmayg07s {
  stop-color: var(--svg-color--c47e70, #C47E70);
  stop-opacity: 0.198;
}

.dkwoqxb5x {
  stop-color: var(--svg-color--a66150, #A66150);
}

.dvo5-tbnw {
  stop-color: var(--svg-color--e09b8e, #E09B8E);
  stop-opacity: 0.079;
}

.dzf4wz_lo {
  stop-color: var(--svg-color--dd978a, #DD978A);
  stop-opacity: 0.78;
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.ejsoz3bco {
  stop-color: var(--svg-color--dd978a, #DD978A);
  stop-opacity: 0;
}

.fboe7xb-h {
  stop-color: var(--svg-color--774e46, #774E46);
  stop-opacity: 0;
}

.fjfp6tgim {
  stop-color: var(--svg-color--390808, #390808);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g5s837qfj {
  stop-color: var(--svg-color--6a2b4c, #6A2B4C);
}

.gmu-pq1ta {
  stop-color: var(--svg-color--774e46, #774E46);
  stop-opacity: 0.576;
}

.h_ah1cmjl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.085 19.619a4.485 4.485 0 1 1-8.97 0a4.485 4.485 0 0 1 8.97 0m10.899 0a4.485 4.485 0 1 1-8.97 0a4.485 4.485 0 0 1 8.97 0");
}

.h9fg3hbtm {
  stop-color: var(--svg-color--622c27, #622C27);
}

.i-xe72b-v {
  stop-color: var(--svg-color--57292c, #57292C);
}

.i29p1nb8u {
  d: path("M21.572 6.66c.126 1.058-.063 1.734-.309 2.133c2.029.56 3.879 1.974 4.743 3.82c.625 1.532.66 3.359.192 5.027c2.483 1.207 4.302 3.907 4.302 6.789c0 3.722-2.723 6.399-6.574 6.624v.016H8.53v-.004C3.76 30.95 1.5 27.75 1.5 24.023c0-2.494 2.149-5.47 4.549-6.49c-.002-.22.02-.387.056-.512c-.929-1.88.021-3.78.618-4.5l.227-.294l.01-.013c.83-1.083 1.331-1.736 4.895-3.279c3.887-1.683 5.269-3.336 5.8-4.006c.146-.184.281-.425.42-.672c.366-.652.763-1.358 1.478-1.245c.987.156 1.761 1.465 2.02 3.647");
}

.jo5a2we8r {
  stop-color: var(--svg-color--f7b8ac, #F7B8AC);
  stop-opacity: 0.58;
}

.k5f4-0blm {
  stop-color: var(--svg-color--ad776b, #AD776B);
  stop-opacity: 0.135;
}

.kakv7tbpb {
  stop-color: var(--svg-color--883854, #883854);
}

.khgt2ey5i {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M21.572 6.66c.126 1.058-.063 1.734-.309 2.133c2.029.56 3.879 1.974 4.743 3.82c.625 1.532.66 3.359.192 5.027c2.483 1.207 4.302 3.907 4.302 6.789c0 3.722-2.723 6.399-6.574 6.624v.016H8.53v-.004C3.76 30.95 1.5 27.75 1.5 24.023c0-2.494 2.149-5.47 4.549-6.49c-.002-.22.02-.387.056-.512c-.929-1.88.021-3.78.618-4.5l.227-.294l.01-.013c.83-1.083 1.331-1.736 4.895-3.279c3.887-1.683 5.269-3.336 5.8-4.006c.146-.184.281-.425.42-.672c.366-.652.763-1.358 1.478-1.245c.987.156 1.761 1.465 2.02 3.647");
}

.kiu9e17zs {
  stop-color: var(--svg-color--3d2432, #3D2432);
}

.ko-qjgbdd {
  stop-color: var(--svg-color--db0c8a, #DB0C8A);
}

.kr2taiq9t {
  stop-color: var(--svg-color--965b4f, #965B4F);
  stop-opacity: 0;
}

.lz-tgvbga {
  stop-color: var(--svg-color--6c3e31, #6C3E31);
}

.n1roefb9n {
  stop-color: var(--svg-color--774e46, #774E46);
  stop-opacity: 0.47;
}

.n6i4dzjkn {
  stop-color: var(--svg-color--dd978a, #DD978A);
  stop-opacity: 0.414;
}

.nvxoal5ng {
  stop-color: var(--svg-color--dd978a, #DD978A);
  stop-opacity: 0.199;
}

.nyzynkpue {
  stop-color: var(--svg-color--7c574f, #7C574F);
}

.ovq2jn1ik {
  stop-color: var(--svg-color--8a077d, #8A077D);
}

.ow43-6juj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.225 10.91c-.213.546-4.54 1.781-6.18 1.298c-1.595-.261-1.25-1.465-.136-2.87c1.64-2.07 4.946-4.579 6.175-5.165c.962-.459 1.387 1.815 1.393 1.85c.19 1.096.183 1.727-.034 2.39c-.184.562-.858 1.831-1.218 2.498");
}

.p6_tj57_f {
  d: path("M20.225 10.91c-.213.546-4.54 1.781-6.18 1.298c-1.595-.261-1.25-1.465-.136-2.87c1.64-2.07 4.946-4.579 6.175-5.165c.962-.459 1.387 1.815 1.393 1.85c.19 1.096.183 1.727-.034 2.39c-.184.562-.858 1.831-1.218 2.498");
}

.pab_xvq1g {
  stop-color: var(--svg-color--774e46, #774E46);
  stop-opacity: 0.37;
}

.pdqzkwbff {
  stop-color: var(--svg-color--dd978a, #DD978A);
  stop-opacity: 0.74;
}

.pzjjoubty {
  d: path("M12.125 25.159h7.906c0 2.379-1.77 3.918-3.953 3.918s-3.953-1.476-3.953-3.918");
}

.q1cg_fbjr {
  stop-color: var(--svg-color--754238, #754238);
}

.q6fr7ubwa {
  stop-color: var(--svg-color--57292c, #57292C);
  stop-opacity: 0;
}

.qcu7njknd {
  stop-color: var(--svg-color--d9d9d9, #D9D9D9);
  stop-opacity: 0.54;
}

.qzc47kbif {
  stop-color: var(--svg-color--d9d9d9, #D9D9D9);
  stop-opacity: 0;
}

.rdbk80vlp {
  stop-color: var(--svg-color--d9d9d9, #D9D9D9);
  stop-opacity: 0.181;
}

.syr11bbei {
  stop-color: var(--svg-color--220404, #220404);
}

.sywvuablk {
  stop-color: var(--svg-color--b07366, #B07366);
}

.tjs6mbctb {
  stop-color: var(--svg-color--bc897e, #BC897E);
  stop-opacity: 0.729;
}

.tm5t5qbwm {
  stop-color: var(--svg-color--7b4a40, #7B4A40);
  stop-opacity: 0;
}

.tu-jnobzw {
  stop-color: var(--svg-color--57292c, #57292C);
  stop-opacity: 0.088;
}

.u72gm6rai {
  stop-color: var(--svg-color--ac7367, #AC7367);
  stop-opacity: 0;
}

.vjgdjc8dx {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M21.572 6.66c.126 1.058-.063 1.734-.309 2.133c2.029.56 3.879 1.974 4.743 3.82c.625 1.532.66 3.359.192 5.027c2.483 1.207 4.302 3.907 4.302 6.789c0 3.722-2.723 6.399-6.574 6.624v.016H8.53v-.004C3.76 30.95 1.5 27.75 1.5 24.023c0-2.494 2.149-5.47 4.549-6.49c-.002-.22.02-.387.056-.512c-.929-1.88.021-3.78.618-4.5l.227-.294l.01-.013c.83-1.083 1.331-1.736 4.895-3.279c3.887-1.683 5.269-3.336 5.8-4.006c.146-.184.281-.425.42-.672c.366-.652.763-1.358 1.478-1.245c.987.156 1.761 1.465 2.02 3.647");
}

.vrb56cbwk {
  stop-color: var(--svg-color--c47e70, #C47E70);
  stop-opacity: 0;
}

.vts10ddjd {
  stop-color: var(--svg-color--822079, #822079);
}

.w0b78qitq {
  stop-color: var(--svg-color--916053, #916053);
  stop-opacity: 0;
}

.w0fyavbiz {
  stop-color: var(--svg-color--c47e70, #C47E70);
}

.wr-x9vb9c {
  stop-color: var(--svg-color--653120, #653120);
}

.yapnhdbrf {
  stop-color: var(--svg-color--6c3730, #6C3730);
  stop-opacity: 0.787;
}

.yq8yv4hsr {
  stop-color: var(--svg-color--b20597, #B20597);
  stop-opacity: 0;
}

.yr3_wsb7a {
  fill-rule: evenodd;
  d: path("M11.515 22.131a2.483 2.483 0 1 0 0-4.967a2.483 2.483 0 0 0 0 4.967m9.011 0a2.483 2.483 0 1 0 0-4.967a2.483 2.483 0 0 0 0 4.967");
}

.z1iotfbis {
  stop-color: var(--svg-color--774e46, #774E46);
  stop-opacity: 0.46;
}

.zp_thu8kx {
  stop-color: var(--svg-color--c29186, #C29186);
}

</style>
