<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="qahk_8bck"/><path class="fbh-jubgf"/><path class="cz39q9b1k"/><path class="whb7lyblv"/><path fill="url(#SVGbN7urc8u)" class="vp4k-gbpk"/><path class="b6p-lmb7l"/><path fill="url(#SVGbl1WpbIm)" class="ijuldybus"/><path class="ej35at0fc"/><path class="mo2orhbxe"/><path class="s0sh27bsa"/><path fill="url(#SVG49MAQiHJ)" class="vpagt3b2u"/><path fill="url(#SVGJBDxsOvt)" class="pf5te60wa"/><path fill="url(#SVGpbiJgcTD)" class="pn_vjs75i"/><path class="xvil0g9dq"/><path fill="url(#SVGcj1SKeML)" class="pbcfjwbre"/><path fill="url(#SVGW1Rh7d3x)" class="oxh1_yblm"/><path fill="url(#SVGGLdcvbTA)" class="k0em04baq"/><path class="labebjvvi"/><path fill="url(#SVGSKq6whrt)" class="pgapasisi"/><path fill="url(#SVGp28FwdTI)" class="j6b27ab3v"/><path class="usvif7b1w"/><path class="mrhqao7ds"/><path fill="url(#SVGxD0nrcIB)" class="rijnrbrlz"/><path class="p2_q1ubye"/><path fill="url(#SVGy0TgjcEs)" class="x04qlzbmu"/><path fill="url(#SVGOPlOydNe)" class="x1-6upbwv"/><path fill="url(#SVGhkSpjc1k)" class="j0vd-kb9z"/><path fill="url(#SVGqfzE1dTP)" class="h45i8totk"/><path fill="url(#SVGrMw6reiS)" class="n9lmrqbwf"/><path fill="url(#SVGjwHbhdsR)" class="j-k4_dbss"/><path fill="url(#SVGaR9wOeoF)" class="ycezleboo"/><path fill="url(#SVGaOnCecyj)" class="pb894904f"/><path fill="url(#SVGUJf1USxs)" class="a9fp7fjaf"/><path fill="url(#SVGqeOPobVt)" class="wymus5bmx"/><path fill="url(#SVGQAlpSbHd)" class="k27sltbof"/><path fill="url(#SVGX4QMjKNN)" class="bhtlbmr-w"/><path fill="url(#SVGmYRHyd2G)" class="yajfmkb1n"/><path fill="url(#SVGPAZ5tr1c)" class="z1ux9tbgu"/><path fill="url(#SVGo3QPneXt)" class="li0md-4sn"/></g><defs><linearGradient id="SVGbN7urc8u" x1="11.985" x2="11.985" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="mbfgnqblv"/><stop offset="1" class="tz6yjxbri"/></linearGradient><linearGradient id="SVGbl1WpbIm" x1="1.284" x2="3.742" y1="5.098" y2="21.124" gradientUnits="userSpaceOnUse"><stop class="wgby0_u7s"/><stop offset="1" class="xd4rw9n1k"/></linearGradient><linearGradient id="SVG49MAQiHJ" x1="15.58" x2="7.765" y1="7.972" y2="13.344" gradientUnits="userSpaceOnUse"><stop class="ini0dfwod"/><stop offset="1" class="o5z0z6biw"/></linearGradient><linearGradient id="SVGJBDxsOvt" x1="15.326" x2="7.828" y1="5.815" y2="13.467" gradientUnits="userSpaceOnUse"><stop class="h3qk6xenm"/><stop offset="1" class="s7rojdb0o"/></linearGradient><linearGradient id="SVGpbiJgcTD" x1="7.594" x2="15.276" y1="12.47" y2="10.088" gradientUnits="userSpaceOnUse"><stop class="u6t5lwtne"/><stop offset="1" class="xcjvifb1e"/></linearGradient><linearGradient id="SVGcj1SKeML" x1="5.2" x2="6.202" y1="6.891" y2="18.892" gradientUnits="userSpaceOnUse"><stop offset=".43" class="aq2olgb2w"/><stop offset="1" class="osswb2wul"/></linearGradient><linearGradient id="SVGW1Rh7d3x" x1="7.848" x2="16.234" y1="6.426" y2="17.249" gradientUnits="userSpaceOnUse"><stop class="ucv6gq8ix"/><stop offset="1" class="zl0cvub3u"/></linearGradient><linearGradient id="SVGGLdcvbTA" x1="8.871" x2="11.372" y1="5.795" y2="20.318" gradientUnits="userSpaceOnUse"><stop class="doj0y1t9d"/><stop offset="1" class="mc41qkcbv"/></linearGradient><linearGradient id="SVGSKq6whrt" x1="15.181" x2="6.868" y1="5.733" y2="15.165" gradientUnits="userSpaceOnUse"><stop class="ignuf-o4q"/><stop offset="1" class="f4t4fhbpo"/></linearGradient><linearGradient id="SVGp28FwdTI" x1="11.899" x2="11.899" y1="4.865" y2="20" gradientUnits="userSpaceOnUse"><stop class="ts03sxb0t"/><stop offset="1" class="vc500hbgt"/></linearGradient><linearGradient id="SVGxD0nrcIB" x1="12" x2="12" y1="4.092" y2="19.878" gradientUnits="userSpaceOnUse"><stop class="dy7fvtboq"/><stop offset="1" class="tztf5rb_y"/></linearGradient><linearGradient id="SVGy0TgjcEs" x1="16.479" x2="5.714" y1="6.509" y2="17.587" gradientUnits="userSpaceOnUse"><stop class="gzm-4kbcc"/><stop offset="1" class="xdw6qja-z"/></linearGradient><linearGradient id="SVGOPlOydNe" x1="11.953" x2="11.953" y1="4.024" y2="20" gradientUnits="userSpaceOnUse"><stop offset=".27" class="dbwv2mbnk"/><stop offset="1" class="c1odt_bbe"/></linearGradient><linearGradient id="SVGhkSpjc1k" x1="8.266" x2="15.162" y1="9.652" y2="8.689" gradientUnits="userSpaceOnUse"><stop class="u5lkqsbig"/><stop offset="1" class="mn1cj9ewo"/></linearGradient><linearGradient id="SVGqfzE1dTP" x1="12.771" x2="5.236" y1="4.466" y2="14.377" gradientUnits="userSpaceOnUse"><stop class="vr8b-qb8j"/><stop offset="1" class="k81b_1ngq"/></linearGradient><linearGradient id="SVGrMw6reiS" x1="9.102" x2="16.157" y1="18.432" y2="17.025" gradientUnits="userSpaceOnUse"><stop class="c3zzvtb6c"/><stop offset=".43" class="vk2cnxjcd"/><stop offset=".53" class="d7d9rcc_i"/><stop offset="1" class="td6tw4b6n"/></linearGradient><linearGradient id="SVGjwHbhdsR" x1="8.831" x2="18.762" y1="21.728" y2="19.551" gradientUnits="userSpaceOnUse"><stop class="x3be7rbcz"/><stop offset=".46" class="ynzknbb3e"/><stop offset="1" class="m01f-bc-w"/></linearGradient><linearGradient id="SVGaR9wOeoF" x1="12.052" x2="12.052" y1="4.816" y2="20.146" gradientUnits="userSpaceOnUse"><stop class="hrd585b5y"/><stop offset="1" class="xk6wj51lz"/></linearGradient><linearGradient id="SVGaOnCecyj" x1="15.316" x2="13.027" y1="5.571" y2="20.157" gradientUnits="userSpaceOnUse"><stop class="i81k06-ie"/><stop offset="1" class="hshqk8boy"/></linearGradient><linearGradient id="SVGUJf1USxs" x1="12.213" x2="12.213" y1="4.147" y2="19.852" gradientUnits="userSpaceOnUse"><stop class="bz2k1vbuq"/><stop offset="1" class="bm12vs8iu"/></linearGradient><linearGradient id="SVGqeOPobVt" x1="9.386" x2="13.969" y1="4.909" y2="19.411" gradientUnits="userSpaceOnUse"><stop class="eyr1vsbll"/><stop offset="1" class="fi-e_gb4m"/></linearGradient><linearGradient id="SVGQAlpSbHd" x1="8.298" x2="10.723" y1="16.969" y2="7.683" gradientUnits="userSpaceOnUse"><stop class="m-dwa-zfq"/><stop offset="1" class="qyode384h"/></linearGradient><linearGradient id="SVGX4QMjKNN" x1="11.799" x2="11.799" y1="4.461" y2="19.974" gradientUnits="userSpaceOnUse"><stop offset=".64" class="g99vxsg4r"/><stop offset="1" class="m-dwa-zfq"/></linearGradient><linearGradient id="SVGmYRHyd2G" x1="12.032" x2="12.032" y1="4.376" y2="20" gradientUnits="userSpaceOnUse"><stop class="jwteugrhd"/><stop offset="1" class="hkda93bdy"/></linearGradient><linearGradient id="SVGPAZ5tr1c" x1="12.724" x2="11.959" y1="4.089" y2="19.998" gradientUnits="userSpaceOnUse"><stop class="vju_n0bzz"/><stop offset="1" class="ik5880baq"/></linearGradient><linearGradient id="SVGo3QPneXt" x1="17.145" x2="16.643" y1="14.738" y2="16.649" gradientUnits="userSpaceOnUse"><stop class="ir7tmilpj"/><stop offset=".96" class="coxmw509a"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mix-background" /></template>
<style>
.a9fp7fjaf {
  d: path("M14.222 17.377L13 17l.622-2.035l.6.346z");
}

.aq2olgb2w {
  stop-color: var(--svg-color--d13462, #d13462);
}

.b6p-lmb7l {
  fill: var(--svg-color--8354c3, #8354c3);
  d: path("m11.275 7.361l-.942.676l1.347.142z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bhtlbmr-w {
  d: path("m16.64 14.289l-1.663.386l2.356-2.777z");
}

.bm12vs8iu {
  stop-color: var(--svg-color--fbbf84, #fbbf84);
}

.bz2k1vbuq {
  stop-color: var(--svg-color--ee919b, #ee919b);
}

.c1odt_bbe {
  stop-color: var(--svg-color--ef8f58, #ef8f58);
}

.c3zzvtb6c {
  stop-color: var(--svg-color--c84083, #c84083);
}

.coxmw509a {
  stop-color: var(--svg-color--d78e83, #d78e83);
}

.cz39q9b1k {
  fill: var(--svg-color--ce7edd, #ce7edd);
  d: path("m11.702 9.177l-.022-.995l.72 1.142z");
}

.d7d9rcc_i {
  stop-color: var(--svg-color--bb55b6, #bb55b6);
}

.dbwv2mbnk {
  stop-color: var(--svg-color--db4b82, #db4b82);
}

.doj0y1t9d {
  stop-color: var(--svg-color--fa7b62, #fa7b62);
}

.dy7fvtboq {
  stop-color: var(--svg-color--f15979, #f15979);
}

.ej35at0fc {
  fill: var(--svg-color--365af7, #365af7);
  d: path("m12.301 5.674l-1.142-.8l1.142-.871z");
}

.eyr1vsbll {
  stop-color: var(--svg-color--db62b6, #db62b6);
}

.f4t4fhbpo {
  stop-color: var(--svg-color--fec46c, #fec46c);
}

.fbh-jubgf {
  fill: var(--svg-color--b96fd7, #b96fd7);
  d: path("M11.702 9.178L10.338 8.03l1.347.142z");
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

.h45i8totk {
  d: path("M14.252 12.889H9.648l2.324 1.83z");
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

.i81k06-ie {
  stop-color: var(--svg-color--8c3078, #8c3078);
}

.ignuf-o4q {
  stop-color: var(--svg-color--ff6088, #ff6088);
}

.ijuldybus {
  d: path("m11.17 4.857l-.832 3.174l.96-.676l-.133-2.498z");
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

.j-k4_dbss {
  d: path("M12.067 11.95c.938 0 1.698-.147 1.698-.33c0-.18-.76-.328-1.698-.328s-1.698.147-1.698.329c0 .181.76.329 1.698.329");
}

.j0vd-kb9z {
  d: path("m11.959 14.693l-.942 2.284l-1.369-4.088z");
}

.j6b27ab3v {
  d: path("M9.653 12.885L8.96 14.67l.644.68l.77-.338l-.72-2.124z");
}

.jwteugrhd {
  stop-color: var(--svg-color--230d75, #230d75);
}

.k0em04baq {
  d: path("m8.004 16.587l-1.333-1.271l.693-1.027z");
}

.k27sltbof {
  d: path("m17.324 11.91l-3.08.979l.733 1.786l2.347-2.769z");
}

.k81b_1ngq {
  stop-color: var(--svg-color--c55070, #c55070);
}

.labebjvvi {
  fill: var(--svg-color--fd627f, #fd627f);
  d: path("m9 14.666l-1.645-.356l.644 2.272z");
}

.li0md-4sn {
  d: path("m17.323 15.276l-.715-.987l-.631 2.365z");
}

.m-dwa-zfq {
  stop-color: var(--svg-color--9e408c, #9e408c);
}

.m01f-bc-w {
  stop-color: var(--svg-color--370e65, #370e65);
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

.mo2orhbxe {
  fill: var(--svg-color--2d4ef2, #2d4ef2);
  d: path("m11.516 4.169l-.333.72l1.129-.871l-.796.155z");
}

.mrhqao7ds {
  fill: var(--svg-color--ffd574, #ffd574);
  d: path("m11.999 20l-2.387-2.676l1.396-.355z");
}

.n9lmrqbwf {
  d: path("m9.267 10.667l-2.6 1.244l2.982.978h4.685l3-.987l-2.654-1.235z");
}

.o5z0z6biw {
  stop-color: var(--svg-color--6c42c4, #6c42c4);
}

.osswb2wul {
  stop-color: var(--svg-color--ff7073, #ff7073);
}

.oxh1_yblm {
  d: path("m7.378 14.324l-.711-2.413l2.289 2.756l-1.582-.338z");
}

.p2_q1ubye {
  fill: var(--svg-color--f4b356, #f4b356);
  d: path("m11.987 17.665l-.978-.688l.99 3.022l1-2.996z");
}

.pb894904f {
  d: path("m14.253 12.885l-1.245 4.12l-1.035-2.307l2.28-1.809z");
}

.pbcfjwbre {
  d: path("M6.667 15.32V11.9l.711 2.396z");
}

.pf5te60wa {
  d: path("m13.63 5.32l-1.346.347l.52 1.378z");
}

.pgapasisi {
  d: path("m9.586 15.32l-1.587 1.262l.96-1.929z");
}

.pn_vjs75i {
  d: path("m13.613 5.32l-.818 1.72l.654 1.298l.164-3.023z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qahk_8bck {
  fill: var(--svg-color--374ce8, #374ce8);
  d: path("m11.235 6.292l-.07-1.422l1.155.805z");
}

.qyode384h {
  stop-color: var(--svg-color--230e79, #230e79);
}

.rijnrbrlz {
  d: path("M11.03 16.982L10.365 15l-.746 2.333l1.413-.346z");
}

.s0sh27bsa {
  fill: var(--svg-color--3865ff, #3865ff);
  d: path("M13.63 5.333L12.298 4v1.707z");
}

.s7rojdb0o {
  stop-color: var(--svg-color--4a70f7, #4a70f7);
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

.u5lkqsbig {
  stop-color: var(--svg-color--e67c8e, #e67c8e);
}

.u6t5lwtne {
  stop-color: var(--svg-color--8359e3, #8359e3);
}

.ucv6gq8ix {
  stop-color: var(--svg-color--ad214a, #ad214a);
}

.usvif7b1w {
  fill: var(--svg-color--e14b55, #e14b55);
  d: path("m9.622 17.332l-.045-2.004l.791-.32z");
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

.vp4k-gbpk {
  d: path("m12.799 7.031l-1.125 1.156l1.774.146l-.645-1.302z");
}

.vpagt3b2u {
  d: path("m11.24 6.289l.031 1.089l.413.809l1.12-1.156l-.502-1.369l-1.067.622z");
}

.vr8b-qb8j {
  stop-color: var(--svg-color--591560, #591560);
}

.wgby0_u7s {
  stop-color: var(--svg-color--435df9, #435df9);
}

.whb7lyblv {
  fill: var(--svg-color--af69dc, #af69dc);
  d: path("m13.452 8.333l-1.778-.151l.72 1.142z");
}

.wymus5bmx {
  d: path("m15.981 16.667l-1.76-1.36l.765-.675l.995 2.026z");
}

.x04qlzbmu {
  d: path("m14.22 17.369l-2.222 2.63l1-3.004z");
}

.x1-6upbwv {
  d: path("m11.964 14.672l-.955 2.306l.977.698l1.023-.671l-1.045-2.338z");
}

.x3be7rbcz {
  stop-color: var(--svg-color--220633, #220633);
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

.xvil0g9dq {
  fill: var(--svg-color--f6609a, #f6609a);
  d: path("m9.662 12.889l-2.995-.978l2.298 2.782z");
}

.yajfmkb1n {
  d: path("m17.332 15.297l-.724-.99l.724-2.41z");
}

.ycezleboo {
  d: path("m14.222 15.325l-.605-.351l.622-2.09l.743 1.77l-.756.666z");
}

.ynzknbb3e {
  stop-color: var(--svg-color--3e0e55, #3e0e55);
}

.z1ux9tbgu {
  d: path("m16.613 14.284l-1.636.387l1.01 2l.622-2.387z");
}

.zl0cvub3u {
  stop-color: var(--svg-color--f67b72, #f67b72);
}

</style>
