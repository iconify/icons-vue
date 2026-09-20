<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="o0lsywbit"/><path class="hcxtl7bas"/><path fill="url(#SVGXfvS6cwW)" class="wxhg1ih7z"/><path class="nt7y7tute"/><path class="zffws2bji"/><path fill="url(#SVGbC4prtmA)" class="vlk3_0c9a"/><path fill="url(#SVG22NtgcbM)" class="yjv5m1vbe"/><path fill="url(#SVGN8VGhctm)" class="fbhcqm34u"/><path fill="url(#SVGkitr7c0y)" class="m_e8inbeg"/><path class="h3el16bxx"/><path class="on101em6b"/><path class="zk-p9g51w"/><path fill="url(#SVGUTdLocGu)" class="l82m64dgz"/><path class="s_w4yt8hy"/><path class="lh97sgbos"/><path class="j037w5wwm"/><path fill="url(#SVGFwLNNeIn)" class="jinj4441g"/><path fill="url(#SVGsNGnEvUH)" class="r5b_-9bzg"/><path class="o_fza2bep"/><path class="vtv3p2arw"/><path class="pg8nx9_bg"/><path fill="url(#SVGpf4qHdZn)" class="cnl9c6b4r"/><path fill="url(#SVGAnhprdeD)" class="ogz1b8bdj"/><path fill="url(#SVGwFihWdbj)" class="swxl9qb4w"/><path fill="url(#SVGHjhbOdHV)" class="j17bicc7z"/><path fill="url(#SVGVJ5ykevv)" clip-rule="evenodd" class="o9be1kfaq"/><path fill="url(#SVGSrmdOlGh)" class="mji3ol3pl"/><path fill="url(#SVGW8LAWcTH)" class="nmkea-h_f"/><path clip-rule="evenodd" class="ypotwtt1f"/><path fill="url(#SVGAnBLv7sH)" class="cjfvjiwuj"/><path fill="url(#SVG7pAvOfON)" class="n7e-6ab6b"/><path clip-rule="evenodd" class="g44q-eg-s"/><path fill="url(#SVG6gBkcben)" class="t_deszjmd"/><path fill="url(#SVGtvw3KFTY)" class="g9is7qb-d"/><path clip-rule="evenodd" class="qvho501et"/><path fill="url(#SVGI0tqhb0K)" clip-rule="evenodd" class="f67hmdm2s"/><path fill="url(#SVG30tgjc3u)" clip-rule="evenodd" class="nnbixcc4s"/><path clip-rule="evenodd" class="nwf2qybjd"/><path fill="url(#SVGfUivObYH)" class="djkcmmbfm"/><path class="eo9rz4bnc"/><path fill="url(#SVGnx8KZb8f)" class="za7ygdz6q"/><path fill="url(#SVGfR50dc1u)" class="dpgqv5bga"/><path fill="url(#SVGGZjuDeBt)" class="rxmrbbc7p"/><path fill="url(#SVGt9Tg6c6z)" class="h2_o6lbbi"/><path fill="url(#SVGKbD2igSa)" class="bknkajbla"/><path fill="url(#SVGVvensejF)" class="eabnrpyzr"/><path fill="url(#SVGyxe3idys)" class="aq4ygwbeu"/><path class="g_ev6hbxa"/><path fill="url(#SVGuH0Xba3K)" class="ge6shjb-r"/></g><defs><linearGradient id="SVGXfvS6cwW" x1="14.204" x2="6.755" y1="4.479" y2="17.83" gradientUnits="userSpaceOnUse"><stop class="ctnjnobff"/><stop offset="1" class="grxlq1b6y"/></linearGradient><linearGradient id="SVGbC4prtmA" x1="4.719" x2="22.291" y1="3.962" y2="8.948" gradientUnits="userSpaceOnUse"><stop class="nf9r_ybbj"/><stop offset="1" class="u7lib01wg"/></linearGradient><linearGradient id="SVG22NtgcbM" x1="5.731" x2="41.677" y1="3.856" y2="22.75" gradientUnits="userSpaceOnUse"><stop class="nf9r_ybbj"/><stop offset="1" class="u7lib01wg"/></linearGradient><linearGradient id="SVGN8VGhctm" x1="-26.575" x2="38.826" y1="-24.733" y2="-2.592" gradientUnits="userSpaceOnUse"><stop class="nf9r_ybbj"/><stop offset="1" class="u7lib01wg"/></linearGradient><linearGradient id="SVGkitr7c0y" x1="-13.34" x2="27.54" y1="-70.574" y2="-66.23" gradientUnits="userSpaceOnUse"><stop class="nf9r_ybbj"/><stop offset="1" class="u7lib01wg"/></linearGradient><linearGradient id="SVGUTdLocGu" x1="12.095" x2="12.095" y1="4.471" y2="19.529" gradientUnits="userSpaceOnUse"><stop class="uqsj89l5f"/><stop offset="1" class="u811vwk6d"/></linearGradient><linearGradient id="SVGFwLNNeIn" x1="11.971" x2="21.975" y1="4.426" y2="18.049" gradientUnits="userSpaceOnUse"><stop class="cay8-jbhr"/><stop offset="1" class="ini-h701j"/></linearGradient><linearGradient id="SVGsNGnEvUH" x1="18.718" x2="4.994" y1="7.492" y2="9.525" gradientUnits="userSpaceOnUse"><stop class="orn5pvbkj"/><stop offset=".37" class="km-diwl_t"/><stop offset="1" class="yclc5xbqn"/></linearGradient><linearGradient id="SVGpf4qHdZn" x1="11.98" x2="11.98" y1="4.471" y2="19.53" gradientUnits="userSpaceOnUse"><stop class="hrgj6hr3h"/><stop offset=".29" class="vgggjxbpf"/><stop offset=".53" class="jsmslkv_d"/><stop offset="1" class="t17ibebxu"/></linearGradient><linearGradient id="SVGAnhprdeD" x1="20" x2="2.03" y1="5.487" y2="10.243" gradientUnits="userSpaceOnUse"><stop class="zz5mp1bkb"/><stop offset=".27" class="w0nzm-bmd"/><stop offset=".74" class="xdb4kbb0s"/><stop offset="1" class="rqm__bczc"/></linearGradient><linearGradient id="SVGwFihWdbj" x1="14.019" x2="15.457" y1="5.638" y2="10.918" gradientUnits="userSpaceOnUse"><stop class="y6lomxbgh"/><stop offset=".34" class="cg358e3uu"/><stop offset=".52" class="fw-9bdlmf"/><stop offset=".72" class="rxuc65bjj"/><stop offset="1" class="myr4m5ksw"/></linearGradient><linearGradient id="SVGHjhbOdHV" x1="5.506" x2="19.583" y1="13.998" y2="13.7" gradientUnits="userSpaceOnUse"><stop class="i7ey02bhg"/><stop offset="1" class="hrig79nkz"/></linearGradient><linearGradient id="SVGVJ5ykevv" x1="10.414" x2="15.615" y1="6.556" y2="16.131" gradientUnits="userSpaceOnUse"><stop class="phdjydl5q"/><stop offset=".49" class="sou1-8b_q"/><stop offset="1" class="k5rjqimee"/></linearGradient><linearGradient id="SVGSrmdOlGh" x1="12" x2="12" y1="4.711" y2="19.53" gradientUnits="userSpaceOnUse"><stop class="p67gip28v"/><stop offset=".23" class="l_2n9daaj"/><stop offset=".49" class="k2-vtobij"/><stop offset=".63" class="bn89nzbta"/><stop offset=".87" class="nvu86ab7j"/><stop offset="1" class="c3xqvdqwh"/></linearGradient><linearGradient id="SVGW8LAWcTH" x1="7.715" x2="9.327" y1="5.486" y2="18.337" gradientUnits="userSpaceOnUse"><stop class="r1a85pb6y"/><stop offset=".23" class="siuq8p_np"/><stop offset=".42" class="zrpfm0eqr"/><stop offset=".63" class="w0fhw9b0k"/><stop offset=".81" class="ohnd0ubjj"/><stop offset="1" class="udl2bucst"/></linearGradient><linearGradient id="SVGAnBLv7sH" x1="12.175" x2="12.057" y1="4.488" y2="19.862" gradientUnits="userSpaceOnUse"><stop class="w62no5b4q"/><stop offset=".21" class="vtsjl8b0l"/><stop offset=".33" class="j914bjvha"/><stop offset=".49" class="i1v9ccnxa"/><stop offset=".57" class="r4ghx9z6l"/><stop offset=".77" class="gd_7vsb9z"/><stop offset=".89" class="c54voultg"/><stop offset="1" class="yu-p3ybhl"/></linearGradient><linearGradient id="SVG7pAvOfON" x1="5.266" x2="9.453" y1="6.513" y2="20.244" gradientUnits="userSpaceOnUse"><stop class="m4yr4sbbp"/><stop offset=".21" class="h_2h0ebya"/><stop offset=".33" class="j914bjvha"/><stop offset=".49" class="d0oe0wbsh"/><stop offset=".57" class="il6bxjr1h"/><stop offset=".77" class="q5yvr-b4s"/><stop offset=".89" class="t0mzh-bsg"/><stop offset="1" class="xpeaznbhr"/></linearGradient><linearGradient id="SVG6gBkcben" x1="9.341" x2="11.906" y1="5.219" y2="19.125" gradientUnits="userSpaceOnUse"><stop class="pwlwojbeh"/><stop offset=".19" class="f94ouzbcl"/><stop offset=".37" class="nddq-vs_r"/><stop offset=".68" class="y9_30gv5z"/><stop offset="1" class="b_8s0ybwf"/></linearGradient><linearGradient id="SVGtvw3KFTY" x1="9.341" x2="12.153" y1="5.255" y2="19.824" gradientUnits="userSpaceOnUse"><stop class="gs3umobfp"/><stop offset=".19" class="j5kg19b2d"/><stop offset=".37" class="sft9xgblt"/><stop offset=".68" class="k555vrjgo"/><stop offset="1" class="rbh2qkb9z"/></linearGradient><linearGradient id="SVGI0tqhb0K" x1="11.988" x2="11.988" y1="5.219" y2="19.53" gradientUnits="userSpaceOnUse"><stop class="ljnvkvi3w"/><stop offset=".44" class="emf7z-b4w"/><stop offset=".74" class="yflrh3bwq"/><stop offset="1" class="s9ah406ug"/></linearGradient><linearGradient id="SVG30tgjc3u" x1="8.517" x2="10.525" y1="5.603" y2="19.731" gradientUnits="userSpaceOnUse"><stop class="o_k8_db7f"/><stop offset=".3" class="le315gtod"/><stop offset="1" class="pg-4fq0md"/></linearGradient><linearGradient id="SVGfUivObYH" x1="15.115" x2="4.638" y1="4.471" y2="5.302" gradientUnits="userSpaceOnUse"><stop class="nmnt8dz9c"/><stop offset="1" class="lngswp6ud"/></linearGradient><linearGradient id="SVGnx8KZb8f" x1="12" x2="10.235" y1="4.471" y2="19.588" gradientUnits="userSpaceOnUse"><stop class="v7pbuprxq"/><stop offset=".31" class="nsozokb9r"/><stop offset=".65" class="ba7mozb-c"/><stop offset="1" class="kne89tbpx"/></linearGradient><linearGradient id="SVGfR50dc1u" x1="11.982" x2="11.982" y1="4.471" y2="19.529" gradientUnits="userSpaceOnUse"><stop class="e0epr8wlk"/><stop offset=".28" class="w886jtvog"/><stop offset=".57" class="f33tz3b9n"/><stop offset="1" class="gaiki3_rk"/></linearGradient><linearGradient id="SVGGZjuDeBt" x1="12.006" x2="12.006" y1="4.451" y2="19.528" gradientUnits="userSpaceOnUse"><stop class="b8noanbwp"/><stop offset=".33" class="qctn6zb_s"/><stop offset=".5" class="rnmrfabyb"/><stop offset="1" class="tp68qcbea"/></linearGradient><linearGradient id="SVGt9Tg6c6z" x1="12.033" x2="12.033" y1="4.471" y2="19.53" gradientUnits="userSpaceOnUse"><stop class="b8noanbwp"/><stop offset=".33" class="qctn6zb_s"/><stop offset=".5" class="rnmrfabyb"/><stop offset="1" class="tp68qcbea"/></linearGradient><linearGradient id="SVGKbD2igSa" x1="12.001" x2="12.001" y1="4.472" y2="19.53" gradientUnits="userSpaceOnUse"><stop class="ixvot5b7m"/><stop offset=".25" class="ip61n4v0g"/><stop offset=".51" class="b43pozbjz"/><stop offset=".74" class="t7hie9bir"/><stop offset="1" class="f45vi66xr"/></linearGradient><linearGradient id="SVGVvensejF" x1="15.408" x2="13.476" y1="4.489" y2="20.227" gradientUnits="userSpaceOnUse"><stop class="qp1im6b2d"/><stop offset=".39" class="aigaykqcn"/><stop offset="1" class="wsab7s0wp"/></linearGradient><linearGradient id="SVGyxe3idys" x1="11.987" x2="12.241" y1="4.453" y2="18.446" gradientUnits="userSpaceOnUse"><stop class="tm0zt33dn"/><stop offset=".3" class="px_loss3w"/><stop offset=".49" class="d0um-zb1y"/><stop offset=".7" class="m0bl40btn"/><stop offset="1" class="kovaaccvw"/></linearGradient><linearGradient id="SVGuH0Xba3K" x1="16.546" x2="16.546" y1="13.125" y2="16.815" gradientUnits="userSpaceOnUse"><stop class="kcnrnobdu"/><stop offset=".19" class="in25yj9wo"/><stop offset=".6" class="xit7nq7je"/><stop offset=".8" class="p374oab7y"/><stop offset="1" class="gw76e2zkx"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:revo-background" /></template>
<style>
.aigaykqcn {
  stop-color: var(--svg-color--25a3d5, #25a3d5);
}

.aq4ygwbeu {
  d: path("m12.998 13.417l.997-.095l1.003 3.492l-.8.094l-.16-.626l-.965.189l-.174.635l-.899.188zm.32 2.174l.517-.095l-.235-.917z");
}

.b_8s0ybwf {
  stop-color: var(--svg-color--a276ae, #a276ae);
}

.b43pozbjz {
  stop-color: var(--svg-color--59edfb, #59edfb);
}

.b8noanbwp {
  stop-color: var(--svg-color--99f3fd, #99f3fd);
}

.ba7mozb-c {
  stop-color: var(--svg-color--166189, #166189);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bknkajbla {
  d: path("M18.4 16.613v.004h-.706l.4-3.393l.706.094l-.004.014c.517.066 1.27.391 1.2 1.346c-.095 1.294-.918 1.883-1.6 1.94zm.08-.673c.353-.033.847-.255.918-.97c.061-.692-.348-.922-.687-.965l-.235 1.935z");
}

.bn89nzbta {
  stop-color: var(--svg-color--66211c, #66211c);
}

.c3xqvdqwh {
  stop-color: var(--svg-color--5e1b1c, #5e1b1c);
}

.c54voultg {
  stop-color: var(--svg-color--9e3641, #9e3641);
}

.cay8-jbhr {
  stop-color: var(--svg-color--fbffff, #fbffff);
}

.cg358e3uu {
  stop-color: var(--svg-color--229acc, #229acc);
}

.cjfvjiwuj {
  d: path("m10.4 10.024l-1.703.385l.301.678l.099 2.137l-.8 1.068h1.501l1.732-.39v-.773l-1.035-.192l-.396.192v-.583l1.2-.287l.094-.683l-1.096-.291l.8-.386v-.687l-.697-.198z");
}

.cnl9c6b4r {
  d: path("M8.099 8.372c.24.466.433 1.553.499 2.038v.87L6.8 11.186l.598-.584l-.094-.192l.094-.095c-.48-.08-.664-.423-.697-.583l.094-.198c0-.466.47-.903.706-1.068l.297-.386l.3.485z");
}

.ctnjnobff {
  stop-color: var(--svg-color--fdfcfe, #fdfcfe);
}

.d0oe0wbsh {
  stop-color: var(--svg-color--fcd77f, #fcd77f);
}

.d0um-zb1y {
  stop-color: var(--svg-color--3be0ff, #3be0ff);
}

.djkcmmbfm {
  d: path("m12.198 17.491l-1.901.584l-.396-.193l1.3-.39z");
}

.dpgqv5bga {
  d: path("M8 19.435L7.102 14h1.096l.904 5.53z");
}

.e0epr8wlk {
  stop-color: var(--svg-color--3b99cd, #3b99cd);
}

.eabnrpyzr {
  d: path("M12.997 13.416h-1.002L10.898 17.3H12l.997-3.887z");
}

.emf7z-b4w {
  stop-color: var(--svg-color--e85e39, #e85e39);
}

.eo9rz4bnc {
  fill: var(--svg-color--6dbedc, #6dbedc);
  d: path("M8.197 14H7.105l1.398-.39l1.101.094L8.202 14z");
}

.f33tz3b9n {
  stop-color: var(--svg-color--2bbef2, #2bbef2);
}

.f45vi66xr {
  stop-color: var(--svg-color--1d68a1, #1d68a1);
}

.f67hmdm2s {
  fill-rule: evenodd;
  d: path("M16 12.254c.174 0 .598-.23.598-.875s-.424-.875-.602-.875c-.175 0-.598.23-.598.875s.423.875.598.875zm0 .97c.88 0 1.6-.829 1.6-1.845S16.88 9.34 16 9.34c-.339 0-.706 0-1.002.094c-.424.335-.602 1.309-.602 1.944c0 .772.117 1.572.705 1.845z");
}

.f94ouzbcl {
  stop-color: var(--svg-color--be3427, #be3427);
}

.fbhcqm34u {
  d: path("M12.598 5.944c.268-.226.837-.64.997-.485s-.597.39-.997.485");
}

.ft5dv1b6b {
  fill: none;
}

.fw-9bdlmf {
  stop-color: var(--svg-color--0c5c9b, #0c5c9b);
}

.g_ev6hbxa {
  fill: var(--svg-color--ceebfe, #ceebfe);
  d: path("m14.197 13.223l1.2.094l.998-.189h-1.798z");
}

.g44q-eg-s {
  fill: var(--svg-color--ffdbc6, #ffdbc6);
  fill-rule: evenodd;
  d: path("m8.998 11.087l1.402-.292v-.772l-2.4.485l.296 3.788l2.203-.583v-.777l-1.403.292v-.875l1.2-.292v-.777l-1.298.292zm1.223.292l-1.303.291v-.644l1.402-.292v-.617l-2.235.452l.282 3.624l2.052-.546v-.621l-1.403.292v-1.031l1.2-.287v-.621z");
}

.g9is7qb-d {
  d: path("m11.497 9.826l-.998.193l1.299 3.497h.998l1.002-3.981l-.899.094l-.701 2.334z");
}

.gaiki3_rk {
  stop-color: var(--svg-color--1b5d83, #1b5d83);
}

.gd_7vsb9z {
  stop-color: var(--svg-color--dd7f8f, #dd7f8f);
}

.ge6shjb-r {
  d: path("m15.2 16.815l.198-3.497l.899-.188l.7 1.84l.198-1.845h.702l-.4 3.59h-.603L16 14.58l-.103 2.235z");
}

.grxlq1b6y {
  stop-color: var(--svg-color--e6d4c6, #e6d4c6);
}

.gs3umobfp {
  stop-color: var(--svg-color--fff379, #fff379);
}

.gw76e2zkx {
  stop-color: var(--svg-color--2179b8, #2179b8);
}

.h_2h0ebya {
  stop-color: var(--svg-color--ffd871, #ffd871);
}

.h2_o6lbbi {
  d: path("M18.598 14.292v-.974c.894.198.998.682.894 1.845a1.34 1.34 0 0 1-1.195 1.26v-.677c.165-.16.499-.565.499-.875s-.132-.518-.198-.579");
}

.h3el16bxx {
  fill: var(--svg-color--151b31, #151b31);
  d: path("M8.597 10.41h-.8c.301-2.038 1.6-4.076 2.602-4.368c-.32.156-.8.843-1.002 1.163h.202c-1.12 1.242-1.134 2.654-1.002 3.2z");
}

.hcxtl7bas {
  fill: var(--svg-color--addfff, #addfff);
  d: path("m17.651 6.466l-2.856.546l2.475-.772l1.826-.291c-.183.06-.607.353-.8.46a.9.9 0 0 0-.216.16l.06.048l.156.01h.24l-.17.164c-.065.061-.169.07-.282.019a2 2 0 0 1-.226-.047a.34.34 0 0 1-.131-.07a.27.27 0 0 1-.076-.227m.264-.146l-.028.057a.3.3 0 0 0-.033.108c-.005.043 0 .061.014.07l.005.005v-.018a.25.25 0 0 1 .07-.118q.07-.07.184-.141zm.734 1.869l-1.699 2.296l1.756-1.863l1.03-1.487c-.136.131-.583.385-.762.513a.9.9 0 0 1-.24.127l-.024-.076l.057-.14l.103-.213l-.226.08c-.09.033-.14.118-.136.245q-.033.106-.052.217a.3.3 0 0 0 .01.14a.28.28 0 0 0 .183.16m.245-.17h-.066a.3.3 0 0 1-.113-.014c-.043-.014-.056-.028-.061-.042v-.005a.27.27 0 0 0 .16 0q.091-.036.207-.108z");
}

.hrgj6hr3h {
  stop-color: var(--svg-color--619caa, #619caa);
}

.hrig79nkz {
  stop-color: var(--svg-color--254c6b, #254c6b);
}

.i1v9ccnxa {
  stop-color: var(--svg-color--5b1d22, #5b1d22);
}

.i7ey02bhg {
  stop-color: var(--svg-color--6d444c, #6d444c);
}

.il6bxjr1h {
  stop-color: var(--svg-color--f9976b, #f9976b);
}

.in25yj9wo {
  stop-color: var(--svg-color--35c3f3, #35c3f3);
}

.ini-h701j {
  stop-color: var(--svg-color--fefff9, #fefff9);
}

.ip61n4v0g {
  stop-color: var(--svg-color--3ab6f3, #3ab6f3);
}

.ixvot5b7m {
  stop-color: var(--svg-color--71d1ff, #71d1ff);
}

.j037w5wwm {
  fill: var(--svg-color--a1354e, #a1354e);
  d: path("M9.897 5.944c-.066 0-.216.019-.296.099c-.104.094-.033.22-.104.291c-.094.095-.4.292-.499.485s0 .193-.098.386c-.08.155-.033.259 0 .292c.597-.777.992-1.163 1.797-1.163c.603 0 1.068.16 1.2.292h.301c-.3-.292-.8-.485-1.5-.485c-.5 0-.8.288-.8.189c0-.076.47-.287.705-.386z");
}

.j17bicc7z {
  d: path("M4.4 17.106c0 .061.014.132.028.207c.207.622 1.393 1.671 2.367 1.633c2.597-.094 5.402-1.84 7.6-1.84c1.76 0 3.265-.164 3.797-.292c-.197.485-3.397.678-4.4.777c-.997.094-5.096 1.939-7.2 1.647A2.456 2.456 0 0 1 4.4 17.106");
}

.j5kg19b2d {
  stop-color: var(--svg-color--fec35f, #fec35f);
}

.j914bjvha {
  stop-color: var(--svg-color--b24143, #b24143);
}

.jinj4441g {
  d: path("M12.8 6.527c0-.094-.103-.677-.202-.776c-.08-.076-.7.033-1.002.094c-.198.099.904.682 1.002.682c.1 0 .198.094.198 0z");
}

.jsmslkv_d {
  stop-color: var(--svg-color--374568, #374568);
}

.k2-vtobij {
  stop-color: var(--svg-color--902524, #902524);
}

.k555vrjgo {
  stop-color: var(--svg-color--f25762, #f25762);
}

.k5rjqimee {
  stop-color: var(--svg-color--d6c8c9, #d6c8c9);
}

.kcnrnobdu {
  stop-color: var(--svg-color--a3f6fb, #a3f6fb);
}

.km-diwl_t {
  stop-color: var(--svg-color--e66a12, #e66a12);
}

.kne89tbpx {
  stop-color: var(--svg-color--1c6091, #1c6091);
}

.kovaaccvw {
  stop-color: var(--svg-color--2b7fbf, #2b7fbf);
}

.l_2n9daaj {
  stop-color: var(--svg-color--eb6234, #eb6234);
}

.l82m64dgz {
  d: path("M10.9 6.72c-.16 0-.203-.188-.203-.292c.16 0 .335.066.4.099c0 .066-.037.193-.197.193");
}

.le315gtod {
  stop-color: var(--svg-color--fc674f, #fc674f);
}

.lh97sgbos {
  fill: var(--svg-color--110f15, #110f15);
  d: path("m10.23 6.471l-.033-.042l.1-.038c.536 0 .818.118.917.193h.085v.08h-.076c-.117.207-.423.485-.837.386a.29.29 0 0 1-.236-.297a.64.64 0 0 1 .08-.282m.226 0c-.16.057-.226.188-.226.282c0 .113.062.193.18.222c.357.09.63-.16.738-.34c-.188-.13-.47-.164-.692-.164");
}

.ljnvkvi3w {
  stop-color: var(--svg-color--9a3441, #9a3441);
}

.lngswp6ud {
  stop-color: var(--svg-color--75bdfe, #75bdfe);
}

.m_e8inbeg {
  d: path("M13.6 5.85a3.1 3.1 0 0 0-1.002.193c.164.033.578.094.898.094s.735-.127.9-.188a3 3 0 0 0-.8-.099z");
}

.m0bl40btn {
  stop-color: var(--svg-color--34a7e8, #34a7e8);
}

.m4yr4sbbp {
  stop-color: var(--svg-color--faee84, #faee84);
}

.mji3ol3pl {
  d: path("m5.6 16.424l-.499-5.144l1.694-.485c.8 0 1.704.424 1.902.584l-.5 2.038l.8 1.938l-1.2.777l-.597-.188l-.4-.781l.099 1.36l-1.101.484l-1.299-.193z");
}

.myr4m5ksw {
  stop-color: var(--svg-color--0e4f75, #0e4f75);
}

.n7e-6ab6b {
  d: path("m10.4 10.023l-2.4.48l.296 3.789l2.203-.584v-.777l-1.403.292v-.875l1.2-.292v-.776l-1.298.292v-.485l1.402-.292z");
}

.nddq-vs_r {
  stop-color: var(--svg-color--982827, #982827);
}

.nf9r_ybbj {
  stop-color: var(--svg-color--fafe78, #fafe78);
}

.nmkea-h_f {
  d: path("m4 11.577l2.598-.781c.3-.061.94.019 1.1.875c.16.852-.329 1.647-.597 1.939l1.195 1.647l-1.096.682l-1.299-1.647l-.301.188v1.85l-1.101.485L4 11.571zm1.299.678l.099 1.162c.433-.094 1.28-.424 1.2-.97c-.09-.611-.838-.352-1.2-.23l-.094.038z");
}

.nmnt8dz9c {
  stop-color: var(--svg-color--59bdfb, #59bdfb);
}

.nnbixcc4s {
  fill-rule: evenodd;
  d: path("M15.548 12.047c.14-.165.25-.433.25-.767c0-.33-.114-.597-.25-.762c-.142-.17-.269-.207-.353-.207c-.08 0-.212.037-.349.207c-.14.165-.249.433-.249.762c0 .33.113.603.25.767c.136.165.268.207.348.207c.084 0 .216-.042.353-.207m-.353 1.177c.884 0 1.6-.87 1.6-1.944c0-1.068-.716-1.939-1.6-1.939c-.88 0-1.6.87-1.6 1.94c0 1.072.72 1.943 1.6 1.943");
}

.nsozokb9r {
  stop-color: var(--svg-color--4ee9fe, #4ee9fe);
}

.nt7y7tute {
  fill: var(--svg-color--424d8d, #424d8d);
  d: path("m9.2 8.47l-.203-.49l-.292.583l.499-.094z");
}

.nvu86ab7j {
  stop-color: var(--svg-color--782424, #782424);
}

.nwf2qybjd {
  fill: var(--svg-color--ffdbc6, #ffdbc6);
  fill-rule: evenodd;
  d: path("M15.877 11.28c0 .348-.118.635-.268.819c-.15.179-.301.235-.414.235c-.109 0-.264-.056-.41-.235a1.3 1.3 0 0 1-.268-.819c0-.343.118-.63.268-.814c.146-.179.301-.235.41-.235c.113 0 .263.056.414.235c.15.184.268.47.268.814m-.682 1.864c.823 0 1.52-.814 1.52-1.864c0-1.045-.697-1.859-1.52-1.859s-1.52.814-1.52 1.86c0 1.049.696 1.863 1.52 1.863m.602-1.864c0 .33-.113.603-.25.767c-.14.165-.268.207-.352.207c-.08 0-.212-.042-.349-.207c-.14-.165-.249-.433-.249-.767c0-.33.113-.597.25-.762c.136-.17.268-.207.348-.207c.084 0 .216.037.353.207c.14.165.25.433.25.762m.998 0c0 1.073-.716 1.944-1.6 1.944c-.88 0-1.6-.87-1.6-1.944c0-1.068.72-1.939 1.6-1.939c.884 0 1.6.87 1.6 1.94");
}

.o_fza2bep {
  fill: var(--svg-color--fdeadc, #fdeadc);
  d: path("M10.4 7.595c-.16 0-.334-.132-.4-.193c.696 0 1.299-.485 1.694-.485c-.452.217-1.096.678-1.294.678");
}

.o_k8_db7f {
  stop-color: var(--svg-color--faf37e, #faf37e);
}

.o0lsywbit {
  fill: var(--svg-color--d7c1c3, #d7c1c3);
  d: path("M14.795 10.21c-.56-.305-.565-.903-.499-1.256c1.501-.682 3.873-1.6 4.099-1.26c.202.286-2.899 2.908-3.6 2.522z");
}

.o9be1kfaq {
  fill-rule: evenodd;
  d: path("m4.603 15.46l-.4.484c0 1.003.48 3.007 2.4 3.007c1.294 0 2.824-.503 4.24-.969c1.205-.395 2.325-.767 3.153-.776h.838c1.731.023 3.934.047 4.362-1.36c.499-1.648.499-3.106-4.499-3.2c-4-.08-8.395 1.84-10.094 2.814m1.995 2.809a.99.99 0 0 0 1.003-.97a.99.99 0 0 0-1.003-.969a.99.99 0 0 0-.997.97a.99.99 0 0 0 .997.969");
}

.ogz1b8bdj {
  d: path("M14.998 7.982c-.565.235-.701 1.068-.701 1.459l.461-.391l.141-.193v.193l.198-.193l.701-.39l.297-.386v.193l.3-.193v.094c.32-.15 2-.838 2.8-1.163l.203-.484c-.32-.076-2.734 1.002-3.901 1.553c-.066.094-.259.291-.499.291s.099-.258.301-.39z");
}

.ohnd0ubjj {
  stop-color: var(--svg-color--fe4e4e, #fe4e4e);
}

.on101em6b {
  fill: var(--svg-color--fa4b3d, #fa4b3d);
  d: path("M8.9 7.205c-.08.155-.033.258 0 .291c.197-.353.8-1.082 1.6-1.162s1.265.16 1.397.292c.565-.08 1.3.033 1.6.094c-.597-.777-1.096-1.064-1.896-1.162c-.8-.095-1.704.385-1.901.484c-.203.094-.1.193-.203.292c-.094.094-.296.386-.4.485c-.094.094-.094.193-.197.386");
}

.orn5pvbkj {
  stop-color: var(--svg-color--ffff75, #ffff75);
}

.p374oab7y {
  stop-color: var(--svg-color--2b9fda, #2b9fda);
}

.p67gip28v {
  stop-color: var(--svg-color--992f34, #992f34);
}

.pg-4fq0md {
  stop-color: var(--svg-color--f15b64, #f15b64);
}

.pg8nx9_bg {
  fill: var(--svg-color--8a8b8d, #8a8b8d);
  d: path("m12.39 5.962l-.019-.066a.037.037 0 0 1 .024-.047c.023-.01.047 0 .052.024l.028.094q.053.006.103.023c.02.01.029.033.02.052c-.01.02-.034.028-.057.02l-.043-.015l.038.15a.037.037 0 0 1-.037.038a.05.05 0 0 1-.048-.037a1 1 0 0 0-.037-.16a.5.5 0 0 0-.16.023a.044.044 0 0 1-.057-.019a.03.03 0 0 1 .007-.04l.012-.007a.5.5 0 0 1 .174-.033");
}

.phdjydl5q {
  stop-color: var(--svg-color--6cbddb, #6cbddb);
}

.pwlwojbeh {
  stop-color: var(--svg-color--de5c64, #de5c64);
}

.px_loss3w {
  stop-color: var(--svg-color--1f90cc, #1f90cc);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q5yvr-b4s {
  stop-color: var(--svg-color--fe5953, #fe5953);
}

.qctn6zb_s {
  stop-color: var(--svg-color--207baa, #207baa);
}

.qp1im6b2d {
  stop-color: var(--svg-color--549ee9, #549ee9);
}

.qvho501et {
  fill: var(--svg-color--ffdbc6, #ffdbc6);
  fill-rule: evenodd;
  d: path("m11.497 9.826l-.998.193l1.299 3.497h.998l1.002-3.981l-.899.094l-.701 2.334zm1.459-.122l-.753 2.522l-.758-2.305l-.838.16l1.247 3.355h.88l.96-3.812l-.734.08z");
}

.r1a85pb6y {
  stop-color: var(--svg-color--feb05b, #feb05b);
}

.r4ghx9z6l {
  stop-color: var(--svg-color--cc3f35, #cc3f35);
}

.r5b_-9bzg {
  d: path("M10.099 7.303A.094.094 0 0 1 10 7.209l-.104.188c0 .297.302.49.603.49s.597-.193 1.101-.193c.499 0 1.097.287 1.398.287c.24 0 .498-.776.597-1.162c-.4-.292-1.035-.292-1.6-.292c-.395 0-1.797.776-1.896.776");
}

.rbh2qkb9z {
  stop-color: var(--svg-color--f35c62, #f35c62);
}

.rnmrfabyb {
  stop-color: var(--svg-color--1481be, #1481be);
}

.rqm__bczc {
  stop-color: var(--svg-color--10162f, #10162f);
}

.rxmrbbc7p {
  d: path("m12.695 13.317l.5 3.59h1.001l.4-.291l.702.197v-.39l1.6.193h1.195v-3.488h-3.497l-.4.095v.39l-.098.39l-.104-.682h-1.299z");
}

.rxuc65bjj {
  stop-color: var(--svg-color--0b4d8a, #0b4d8a);
}

.s_w4yt8hy {
  fill: var(--svg-color--d9d9d9, #d9d9d9);
  d: path("M10.847 6.574a.047.047 0 0 1-.047.047a.047.047 0 0 1-.052-.047a.05.05 0 0 1 .047-.047c.028 0 .052.023.052.047");
}

.s9ah406ug {
  stop-color: var(--svg-color--a45f8f, #a45f8f);
}

.sft9xgblt {
  stop-color: var(--svg-color--fd7354, #fd7354);
}

.siuq8p_np {
  stop-color: var(--svg-color--fe9c51, #fe9c51);
}

.sou1-8b_q {
  stop-color: var(--svg-color--cddde4, #cddde4);
}

.swxl9qb4w {
  d: path("M13.797 6.917c-1.2.777-3.6 6.631-4 7.469l4.598-.292V9.633c0-.621.4-1.36.602-1.647h.296l.095-.1h-.495l-.3.095a7 7 0 0 0-.8-1.064z");
}

.t_deszjmd {
  d: path("m12.597 10.024l-1.1-.198l.7 3.69h1.501l1.097-3.784l-.998-.197l-.899 2.037l-.3-1.553z");
}

.t0mzh-bsg {
  stop-color: var(--svg-color--fe5754, #fe5754);
}

.t17ibebxu {
  stop-color: var(--svg-color--637c90, #637c90);
}

.t7hie9bir {
  stop-color: var(--svg-color--41acff, #41acff);
}

.tm0zt33dn {
  stop-color: var(--svg-color--3697db, #3697db);
}

.tp68qcbea {
  stop-color: var(--svg-color--12386a, #12386a);
}

.u7lib01wg {
  stop-color: var(--svg-color--fffdce, #fffdce);
}

.u811vwk6d {
  stop-color: var(--svg-color--090f1f, #090f1f);
}

.udl2bucst {
  stop-color: var(--svg-color--fe4f4b, #fe4f4b);
}

.uqsj89l5f {
  stop-color: var(--svg-color--5d5b70, #5d5b70);
}

.v7pbuprxq {
  stop-color: var(--svg-color--3b89c7, #3b89c7);
}

.vgggjxbpf {
  stop-color: var(--svg-color--183f78, #183f78);
}

.vlk3_0c9a {
  d: path("M10.494 5.365A3 3 0 0 1 9.6 4.78c0-.193.997.094 1.298.292c.212.136.702.485.9.678a14 14 0 0 1-1.3-.386z");
}

.vtsjl8b0l {
  stop-color: var(--svg-color--e74425, #e74425);
}

.vtv3p2arw {
  fill: var(--svg-color--934800, #934800);
  d: path("M11.534 6.998a8 8 0 0 1 1.464-.277c-.485 0-.937.122-1.407.207c-.151.023-.32.099-.513.179c-.302.131-.645.282-1.021.291H10l.042.043c.08.066.226.155.358.155c.122 0 .41-.17.715-.353c.141-.085.283-.17.424-.245zm-1.134.56a.46.46 0 0 1-.216-.07a1 1 0 0 1-.08-.047a2.7 2.7 0 0 0 .988-.297l.282-.117l.075-.024l-.353.207q-.245.14-.494.278l-.122.047a.3.3 0 0 1-.08.023");
}

.w0fhw9b0k {
  stop-color: var(--svg-color--fd594f, #fd594f);
}

.w0nzm-bmd {
  stop-color: var(--svg-color--44608e, #44608e);
}

.w62no5b4q {
  stop-color: var(--svg-color--f67141, #f67141);
}

.w886jtvog {
  stop-color: var(--svg-color--34bfe8, #34bfe8);
}

.wsab7s0wp {
  stop-color: var(--svg-color--1f93cc, #1f93cc);
}

.wxhg1ih7z {
  d: path("M11.2 5.85c-2.08.075-3.135 3.073-3.403 4.56l5.299-.193l1.6-1.553c-.301-.97-1.421-2.894-3.497-2.814");
}

.xdb4kbb0s {
  stop-color: var(--svg-color--152549, #152549);
}

.xit7nq7je {
  stop-color: var(--svg-color--3ddff6, #3ddff6);
}

.xpeaznbhr {
  stop-color: var(--svg-color--fb5a52, #fb5a52);
}

.y6lomxbgh {
  stop-color: var(--svg-color--4caace, #4caace);
}

.y9_30gv5z {
  stop-color: var(--svg-color--da4f3a, #da4f3a);
}

.yclc5xbqn {
  stop-color: var(--svg-color--ae4213, #ae4213);
}

.yflrh3bwq {
  stop-color: var(--svg-color--cb3445, #cb3445);
}

.yjv5m1vbe {
  d: path("M11.294 4.88q.41.425.8.87a8 8 0 0 1-.998-.485c-.499-.292-.696-.678-.598-.776c.1-.094.598.193.8.39z");
}

.ypotwtt1f {
  fill: var(--svg-color--ffdbc6, #ffdbc6);
  fill-rule: evenodd;
  d: path("M7.101 13.609a2.46 2.46 0 0 0 .598-1.94c-.16-.856-.8-.94-1.101-.875L4 11.575l.499 5.243l1.101-.485V14.49l.301-.193L7.2 15.943l1.096-.678l-1.195-1.647zm1.083 1.628l-1.186-1.633l.042-.047c.127-.141.31-.4.442-.734c.137-.33.217-.73.142-1.14c-.08-.409-.269-.62-.462-.729a.82.82 0 0 0-.54-.084l-2.537.757l.484 5.069l.951-.42v-1.835l.395-.258l1.304 1.652zM5.327 13.51l-.113-1.313l.061-.02l.094-.032h.01c.179-.066.466-.165.72-.17c.132 0 .263.02.372.095a.5.5 0 0 1 .207.367c.047.315-.18.56-.443.724a2.6 2.6 0 0 1-.819.33zm.07-.094l.08-.02c.452-.117 1.196-.437 1.12-.95c-.089-.612-.837-.353-1.2-.23l-.093.037z");
}

.yu-p3ybhl {
  stop-color: var(--svg-color--722432, #722432);
}

.za7ygdz6q {
  d: path("m10.3 18.07l-.705-4.361l-1.294.268l-.104.023l.904 5.53l3.096-.876v-1.162l-1.896.584z");
}

.zffws2bji {
  fill: var(--svg-color--776b8e, #776b8e);
  d: path("M9.097 10.41v-.583l.503.484l-.503.094z");
}

.zk-p9g51w {
  fill: var(--svg-color--6991f0, #6991f0);
  d: path("M10.611 6.715c.033.062.09.104.188.104c.236 0 .297-.193.297-.292a2 2 0 0 0-.499-.094c-.005.028-.014.061-.014.099a.096.096 0 0 1 .085.094a.09.09 0 0 1-.057.094z");
}

.zrpfm0eqr {
  stop-color: var(--svg-color--ffea76, #ffea76);
}

.zz5mp1bkb {
  stop-color: var(--svg-color--b2c9e8, #b2c9e8);
}

</style>
