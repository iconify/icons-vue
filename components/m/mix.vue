<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="numl_ubdz"/><path class="ea5nfwkne"/><path class="m8jfe9b6m"/><path class="i74f9bbdb"/><path fill="url(#SVGPRjzyb1O)" class="efxlve-nj"/><path class="rxc9ig0uy"/><path fill="url(#SVG7iURIeJc)" class="s0ug_tbut"/><path class="uoecpmb3u"/><path class="on2b0l4ie"/><path class="byujbkbge"/><path fill="url(#SVGHuV4dd1j)" class="n-ecfjrth"/><path fill="url(#SVGPj5l5cRQ)" class="ta8nbdb0t"/><path fill="url(#SVGo95RFbxf)" class="a6p-_gb4g"/><path class="hxs6opfnm"/><path fill="url(#SVGtMPVwdLT)" class="cf7-7b2em"/><path fill="url(#SVG4Zu49bGB)" class="k-e0n4yjp"/><path fill="url(#SVGQXeVcewU)" class="iftgf_5hg"/><path class="n2ggpeckk"/><path fill="url(#SVGr15Qr90k)" class="u_1u8ybjs"/><path fill="url(#SVGSxLF2dwG)" class="j_9u_lbqq"/><path class="vti_ymb_c"/><path class="k1v0w9oyi"/><path fill="url(#SVGnuj6Ub1r)" class="pg8rt0bey"/><path class="c0w2o4b-r"/><path fill="url(#SVGh8z0Mc1h)" class="kzzd_jizp"/><path fill="url(#SVG2JwRVdmP)" class="dr2hgvblj"/><path fill="url(#SVGwtnlIdXh)" class="mtyev3bff"/><path fill="url(#SVGDX8qzewa)" class="o_35vybve"/><path fill="url(#SVGGXdP6d6y)" class="qc2hxubip"/><path fill="url(#SVGnUJiFenA)" class="dliph1bie"/><path fill="url(#SVGGQFPVJcD)" class="drl1v4bwy"/><path fill="url(#SVGCNHPxdDw)" class="m4xqz-aoo"/><path fill="url(#SVGMU3qMeLL)" class="apw_b6bvb"/><path fill="url(#SVGhJjeSdhv)" class="ujxpj4bci"/><path fill="url(#SVGM3YpC36h)" class="pxui2c9yy"/><path fill="url(#SVGltr8IbSj)" class="ozw8nxbsx"/><path fill="url(#SVG1sqIIc2V)" class="vlrfnjfad"/><path fill="url(#SVG9CRzKdsP)" class="x7__39bpi"/><path fill="url(#SVGabDUDd8M)" class="oihhwfbsv"/><defs><linearGradient id="SVGPRjzyb1O" x1="11.984" x2="11.984" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="mbfgnqblv"/><stop offset="1" class="tz6yjxbri"/></linearGradient><linearGradient id="SVG7iURIeJc" x1="-.055" x2="2.709" y1="4.235" y2="22.265" gradientUnits="userSpaceOnUse"><stop class="wgby0_u7s"/><stop offset="1" class="xd4rw9n1k"/></linearGradient><linearGradient id="SVGHuV4dd1j" x1="16.028" x2="7.235" y1="7.468" y2="13.512" gradientUnits="userSpaceOnUse"><stop class="ini0dfwod"/><stop offset="1" class="o5z0z6biw"/></linearGradient><linearGradient id="SVGPj5l5cRQ" x1="15.742" x2="7.307" y1="5.042" y2="13.65" gradientUnits="userSpaceOnUse"><stop class="h3qk6xenm"/><stop offset="1" class="s7rojdb0o"/></linearGradient><linearGradient id="SVGo95RFbxf" x1="7.044" x2="15.686" y1="12.529" y2="9.849" gradientUnits="userSpaceOnUse"><stop class="u6t5lwtne"/><stop offset="1" class="xcjvifb1e"/></linearGradient><linearGradient id="SVGtMPVwdLT" x1="4.35" x2="5.477" y1="6.252" y2="19.753" gradientUnits="userSpaceOnUse"><stop offset=".43" class="aq2olgb2w"/><stop offset="1" class="osswb2wul"/></linearGradient><linearGradient id="SVG4Zu49bGB" x1="7.328" x2="16.762" y1="5.73" y2="17.905" gradientUnits="userSpaceOnUse"><stop class="ucv6gq8ix"/><stop offset="1" class="zl0cvub3u"/></linearGradient><linearGradient id="SVGQXeVcewU" x1="8.48" x2="11.293" y1="5.02" y2="21.358" gradientUnits="userSpaceOnUse"><stop class="doj0y1t9d"/><stop offset="1" class="mc41qkcbv"/></linearGradient><linearGradient id="SVGr15Qr90k" x1="15.579" x2="6.227" y1="4.95" y2="15.561" gradientUnits="userSpaceOnUse"><stop class="ignuf-o4q"/><stop offset="1" class="f4t4fhbpo"/></linearGradient><linearGradient id="SVGSxLF2dwG" x1="11.886" x2="11.886" y1="3.973" y2="21" gradientUnits="userSpaceOnUse"><stop class="ts03sxb0t"/><stop offset="1" class="vc500hbgt"/></linearGradient><linearGradient id="SVGnuj6Ub1r" x1="12" x2="12" y1="3.103" y2="20.863" gradientUnits="userSpaceOnUse"><stop class="dy7fvtboq"/><stop offset="1" class="tztf5rb_y"/></linearGradient><linearGradient id="SVGh8z0Mc1h" x1="17.038" x2="4.929" y1="5.822" y2="18.285" gradientUnits="userSpaceOnUse"><stop class="gzm-4kbcc"/><stop offset="1" class="xdw6qja-z"/></linearGradient><linearGradient id="SVG2JwRVdmP" x1="11.947" x2="11.947" y1="3.027" y2="21" gradientUnits="userSpaceOnUse"><stop offset=".27" class="dbwv2mbnk"/><stop offset="1" class="c1odt_bbe"/></linearGradient><linearGradient id="SVGwtnlIdXh" x1="7.8" x2="15.557" y1="9.359" y2="8.276" gradientUnits="userSpaceOnUse"><stop class="u5lkqsbig"/><stop offset="1" class="mn1cj9ewo"/></linearGradient><linearGradient id="SVGDX8qzewa" x1="12.868" x2="4.392" y1="3.524" y2="14.675" gradientUnits="userSpaceOnUse"><stop class="vr8b-qb8j"/><stop offset="1" class="k81b_1ngq"/></linearGradient><linearGradient id="SVGGXdP6d6y" x1="8.74" x2="16.676" y1="19.236" y2="17.653" gradientUnits="userSpaceOnUse"><stop class="c3zzvtb6c"/><stop offset=".43" class="vk2cnxjcd"/><stop offset=".53" class="d7d9rcc_i"/><stop offset="1" class="td6tw4b6n"/></linearGradient><linearGradient id="SVGnUJiFenA" x1="8.435" x2="19.607" y1="22.944" y2="20.494" gradientUnits="userSpaceOnUse"><stop class="x3be7rbcz"/><stop offset=".46" class="ynzknbb3e"/><stop offset="1" class="m01f-bc-w"/></linearGradient><linearGradient id="SVGGQFPVJcD" x1="12.058" x2="12.058" y1="3.918" y2="21.164" gradientUnits="userSpaceOnUse"><stop class="hrd585b5y"/><stop offset="1" class="xk6wj51lz"/></linearGradient><linearGradient id="SVGCNHPxdDw" x1="15.73" x2="13.156" y1="4.767" y2="21.176" gradientUnits="userSpaceOnUse"><stop class="i81k06-ie"/><stop offset="1" class="hshqk8boy"/></linearGradient><linearGradient id="SVGMU3qMeLL" x1="12.24" x2="12.24" y1="3.165" y2="20.833" gradientUnits="userSpaceOnUse"><stop class="bz2k1vbuq"/><stop offset="1" class="bm12vs8iu"/></linearGradient><linearGradient id="SVGhJjeSdhv" x1="9.06" x2="14.215" y1="4.023" y2="20.338" gradientUnits="userSpaceOnUse"><stop class="eyr1vsbll"/><stop offset="1" class="fi-e_gb4m"/></linearGradient><linearGradient id="SVGM3YpC36h" x1="7.835" x2="10.563" y1="17.59" y2="7.143" gradientUnits="userSpaceOnUse"><stop class="m-dwa-zfq"/><stop offset="1" class="qyode384h"/></linearGradient><linearGradient id="SVGltr8IbSj" x1="11.773" x2="11.773" y1="3.517" y2="20.97" gradientUnits="userSpaceOnUse"><stop offset=".64" class="g99vxsg4r"/><stop offset="1" class="m-dwa-zfq"/></linearGradient><linearGradient id="SVG1sqIIc2V" x1="12.035" x2="12.035" y1="3.422" y2="20.999" gradientUnits="userSpaceOnUse"><stop class="jwteugrhd"/><stop offset="1" class="hkda93bdy"/></linearGradient><linearGradient id="SVG9CRzKdsP" x1="12.815" x2="11.954" y1="3.1" y2="20.997" gradientUnits="userSpaceOnUse"><stop class="vju_n0bzz"/><stop offset="1" class="ik5880baq"/></linearGradient><linearGradient id="SVGabDUDd8M" x1="17.788" x2="17.224" y1="15.081" y2="17.231" gradientUnits="userSpaceOnUse"><stop class="ir7tmilpj"/><stop offset=".96" class="coxmw509a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mix" /></template>
<style>
.a6p-_gb4g {
  d: path("m13.815 4.485l-.92 1.934l.735 1.46l.185-3.4z");
}

.apw_b6bvb {
  d: path("m14.5 18.049l-1.375-.425l.7-2.29l.675.39z");
}

.aq2olgb2w {
  stop-color: var(--svg-color--d13462, #d13462);
}

.bm12vs8iu {
  stop-color: var(--svg-color--fbbf84, #fbbf84);
}

.byujbkbge {
  fill: var(--svg-color--3865ff, #3865ff);
  d: path("m13.834 4.5l-1.5-1.5v1.92z");
}

.bz2k1vbuq {
  stop-color: var(--svg-color--ee919b, #ee919b);
}

.c0w2o4b-r {
  fill: var(--svg-color--f4b356, #f4b356);
  d: path("m11.985 18.374l-1.1-.775l1.115 3.4l1.125-3.37z");
}

.c1odt_bbe {
  stop-color: var(--svg-color--ef8f58, #ef8f58);
}

.c3zzvtb6c {
  stop-color: var(--svg-color--c84083, #c84083);
}

.cf7-7b2em {
  d: path("M6 15.734v-3.845l.8 2.695z");
}

.coxmw509a {
  stop-color: var(--svg-color--d78e83, #d78e83);
}

.d7d9rcc_i {
  stop-color: var(--svg-color--bb55b6, #bb55b6);
}

.dbwv2mbnk {
  stop-color: var(--svg-color--db4b82, #db4b82);
}

.dliph1bie {
  d: path("M12.075 11.943c1.055 0 1.91-.165 1.91-.37c0-.204-.855-.37-1.91-.37s-1.91.166-1.91.37s.855.37 1.91.37");
}

.doj0y1t9d {
  stop-color: var(--svg-color--fa7b62, #fa7b62);
}

.dr2hgvblj {
  d: path("M11.96 15.005L10.885 17.6l1.1.785l1.15-.755L11.96 15z");
}

.drl1v4bwy {
  d: path("m14.5 15.74l-.68-.395l.7-2.35l.834 1.99l-.85.75z");
}

.dy7fvtboq {
  stop-color: var(--svg-color--f15979, #f15979);
}

.ea5nfwkne {
  fill: var(--svg-color--b96fd7, #b96fd7);
  d: path("m11.665 8.825l-1.535-1.29l1.515.16z");
}

.efxlve-nj {
  d: path("m12.899 6.41l-1.265 1.3l1.995.165l-.725-1.465z");
}

.eyr1vsbll {
  stop-color: var(--svg-color--db62b6, #db62b6);
}

.f4t4fhbpo {
  stop-color: var(--svg-color--fec46c, #fec46c);
}

.fi-e_gb4m {
  stop-color: var(--svg-color--c03f89, #c03f89);
}

.ft5dv1b6b {
  fill: none;
}

.g99vxsg4r {
  stop-color: var(--svg-color--260e76, #260e76);
}

.gzm-4kbcc {
  stop-color: var(--svg-color--ff5c8c, #ff5c8c);
}

.h3qk6xenm {
  stop-color: var(--svg-color--3e78fd, #3e78fd);
}

.hkda93bdy {
  stop-color: var(--svg-color--a04f93, #a04f93);
}

.hrd585b5y {
  stop-color: var(--svg-color--c058bb, #c058bb);
}

.hshqk8boy {
  stop-color: var(--svg-color--e17269, #e17269);
}

.hxs6opfnm {
  fill: var(--svg-color--f6609a, #f6609a);
  d: path("M9.37 13L6 11.9l2.585 3.13z");
}

.i74f9bbdb {
  fill: var(--svg-color--af69dc, #af69dc);
  d: path("m13.634 7.874l-2-.17l.81 1.285z");
}

.i81k06-ie {
  stop-color: var(--svg-color--8c3078, #8c3078);
}

.iftgf_5hg {
  d: path("m7.505 17.16l-1.5-1.43l.78-1.155z");
}

.ignuf-o4q {
  stop-color: var(--svg-color--ff6088, #ff6088);
}

.ik5880baq {
  stop-color: var(--svg-color--db7391, #db7391);
}

.ini0dfwod {
  stop-color: var(--svg-color--2e42de, #2e42de);
}

.ir7tmilpj {
  stop-color: var(--svg-color--914089, #914089);
}

.j_9u_lbqq {
  d: path("m9.36 12.995l-.78 2.01l.725.765l.864-.38L9.36 13z");
}

.jwteugrhd {
  stop-color: var(--svg-color--230d75, #230d75);
}

.k-e0n4yjp {
  d: path("M6.8 14.615L6 11.9L8.575 15l-1.78-.38z");
}

.k1v0w9oyi {
  fill: var(--svg-color--ffd574, #ffd574);
  d: path("m11.999 21l-2.685-3.01l1.57-.4z");
}

.k81b_1ngq {
  stop-color: var(--svg-color--c55070, #c55070);
}

.kzzd_jizp {
  d: path("m14.498 18.04l-2.5 2.959l1.126-3.38z");
}

.m-dwa-zfq {
  stop-color: var(--svg-color--9e408c, #9e408c);
}

.m01f-bc-w {
  stop-color: var(--svg-color--370e65, #370e65);
}

.m4xqz-aoo {
  d: path("m14.534 12.995l-1.4 4.635l-1.165-2.595L14.534 13z");
}

.m8jfe9b6m {
  fill: var(--svg-color--ce7edd, #ce7edd);
  d: path("m11.665 8.824l-.025-1.12l.81 1.285z");
}

.mbfgnqblv {
  stop-color: var(--svg-color--7187fe, #7187fe);
}

.mc41qkcbv {
  stop-color: var(--svg-color--ffcc6d, #ffcc6d);
}

.mn1cj9ewo {
  stop-color: var(--svg-color--d55674, #d55674);
}

.mtyev3bff {
  d: path("m11.954 15.03l-1.06 2.57l-1.54-4.6z");
}

.n-ecfjrth {
  d: path("M11.145 5.575L11.18 6.8l.465.91l1.26-1.3l-.565-1.54l-1.2.7z");
}

.n2ggpeckk {
  fill: var(--svg-color--fd627f, #fd627f);
  d: path("m8.625 15l-1.85-.4l.725 2.556z");
}

.numl_ubdz {
  fill: var(--svg-color--374ce8, #374ce8);
  d: path("m11.14 5.578l-.08-1.6l1.3.905z");
}

.o_35vybve {
  d: path("M14.534 13h-5.18l2.615 2.06z");
}

.o5z0z6biw {
  stop-color: var(--svg-color--6c42c4, #6c42c4);
}

.oihhwfbsv {
  d: path("m17.989 15.685l-.805-1.11l-.71 2.66z");
}

.on2b0l4ie {
  fill: var(--svg-color--2d4ef2, #2d4ef2);
  d: path("M11.455 3.19L11.08 4l1.27-.98l-.895.175z");
}

.osswb2wul {
  stop-color: var(--svg-color--ff7073, #ff7073);
}

.ozw8nxbsx {
  d: path("m17.22 14.574l-1.87.435L18 11.884z");
}

.pg8rt0bey {
  d: path("m10.91 17.605l-.75-2.23L9.32 18l1.59-.39z");
}

.pxui2c9yy {
  d: path("M17.99 11.9L14.523 13l.825 2.01l2.64-3.115z");
}

.qc2hxubip {
  d: path("M8.925 10.5L6 11.9L9.355 13h5.27L18 11.89l-2.985-1.39z");
}

.qyode384h {
  stop-color: var(--svg-color--230e79, #230e79);
}

.rxc9ig0uy {
  fill: var(--svg-color--8354c3, #8354c3);
  d: path("m11.185 6.781l-1.06.76l1.515.16z");
}

.s0ug_tbut {
  d: path("m11.065 3.965l-.935 3.57l1.08-.76l-.15-2.81z");
}

.s7rojdb0o {
  stop-color: var(--svg-color--4a70f7, #4a70f7);
}

.ta8nbdb0t {
  d: path("m13.834 4.485l-1.515.39l.585 1.55z");
}

.td6tw4b6n {
  stop-color: var(--svg-color--744fd7, #744fd7);
}

.ts03sxb0t {
  stop-color: var(--svg-color--830e36, #830e36);
}

.tz6yjxbri {
  stop-color: var(--svg-color--8862e1, #8862e1);
}

.tztf5rb_y {
  stop-color: var(--svg-color--ed9748, #ed9748);
}

.u_1u8ybjs {
  d: path("m9.284 15.735l-1.785 1.42l1.08-2.17z");
}

.u5lkqsbig {
  stop-color: var(--svg-color--e67c8e, #e67c8e);
}

.u6t5lwtne {
  stop-color: var(--svg-color--8359e3, #8359e3);
}

.ucv6gq8ix {
  stop-color: var(--svg-color--ad214a, #ad214a);
}

.ujxpj4bci {
  d: path("m16.48 17.25l-1.981-1.53l.86-.76l1.12 2.28z");
}

.uoecpmb3u {
  fill: var(--svg-color--365af7, #365af7);
  d: path("m12.339 4.883l-1.285-.9l1.285-.98z");
}

.vc500hbgt {
  stop-color: var(--svg-color--ec4679, #ec4679);
}

.vju_n0bzz {
  stop-color: var(--svg-color--57156d, #57156d);
}

.vk2cnxjcd {
  stop-color: var(--svg-color--a53b98, #a53b98);
}

.vlrfnjfad {
  d: path("m17.998 15.709l-.814-1.115l.814-2.71z");
}

.vr8b-qb8j {
  stop-color: var(--svg-color--591560, #591560);
}

.vti_ymb_c {
  fill: var(--svg-color--e14b55, #e14b55);
  d: path("m9.324 17.999l-.05-2.255l.89-.36z");
}

.wgby0_u7s {
  stop-color: var(--svg-color--435df9, #435df9);
}

.x3be7rbcz {
  stop-color: var(--svg-color--220633, #220633);
}

.x7__39bpi {
  d: path("m17.19 14.57l-1.84.434l1.135 2.25l.7-2.685z");
}

.xcjvifb1e {
  stop-color: var(--svg-color--7562f3, #7562f3);
}

.xd4rw9n1k {
  stop-color: var(--svg-color--4c42d3, #4c42d3);
}

.xdw6qja-z {
  stop-color: var(--svg-color--f1984c, #f1984c);
}

.xk6wj51lz {
  stop-color: var(--svg-color--b63781, #b63781);
}

.ynzknbb3e {
  stop-color: var(--svg-color--3e0e55, #3e0e55);
}

.zl0cvub3u {
  stop-color: var(--svg-color--f67b72, #f67b72);
}

</style>
