<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGlKhRubUc)" class="sn6ot1bje"/><path class="z-p1diu_s"/><path class="x5dpcqz8l"/><path fill="url(#SVGgRz07btM)" class="uhwf96wtk"/><path class="r7o2t8b_k"/><path class="obaf6ngbs"/><path fill="url(#SVGZulLHoQU)" class="vp71lbb5s"/><path class="le6frkbgj"/><path class="h-f76qp9e"/><path class="jfxrqvr8o"/><path fill="url(#SVG6AGAMbGq)" class="sqaschbsn"/><path class="s89qps1hv"/><path class="mxaxt0mxd"/><path class="w63f3ac8s"/><path class="cim6eb4jl"/><path fill="url(#SVGHlkA4bFm)" class="jcx8i2p0n"/><path fill="url(#SVGeBNMwcLk)" class="yawvegbgw"/><path fill="url(#SVGImOydcup)" class="jib7h4m8c"/><path class="hdju55bar"/><path fill="url(#SVGPStKj6UR)" class="ic72ubb3g"/><path fill="url(#SVGq4TihenR)" class="ijpabpkgc"/><path fill="url(#SVGp3vQLe7z)" class="faor0c0ub"/><path fill="url(#SVGlVHBxeao)" class="csmxg8ecq"/><path fill="url(#SVGWJR9Neba)" class="jsq5rb6to"/><path fill="url(#SVGBTb74cWA)" class="m3pioybtx"/><path fill="url(#SVGPHIJhded)" class="jw-1edbdg"/><path class="cv8ng12ig"/><path fill="url(#SVGsZB7RfNZ)" class="a30b09bxv"/><path class="vwfhpkctu"/><path fill="url(#SVGvqSXNeZz)" class="ebw3pibqk"/><path class="kmct1yb3i"/><path class="v_cv6kb1l"/><path class="lugygpbxr"/><path class="avuf2-dcg"/><path fill="url(#SVGeFAwJd3g)" class="xh2s79_-b"/><path class="alkguff9j"/><path fill="url(#SVGN9sckbch)" class="eziougb8z"/><path fill="url(#SVGcHlZ1Q3D)" class="i6plz9b7w"/><path fill="url(#SVGDLw1Db3E)" class="ic7ujub9y"/><path fill="url(#SVGLsdvibhx)" class="d8z56xb1h"/><path fill="url(#SVGtgvX5dVS)" class="r_f83bbxa"/><path class="c6c0c5k4r"/><defs><linearGradient id="SVGlKhRubUc" x1="11.962" x2="15.153" y1="3" y2="21.325" gradientUnits="userSpaceOnUse"><stop offset=".15" class="i3n62_kyp"/><stop offset=".33" class="f0-v8ab7u"/></linearGradient><linearGradient id="SVGgRz07btM" x1="11.983" x2="15.18" y1="3.012" y2="21.329" gradientUnits="userSpaceOnUse"><stop offset=".15" class="i3n62_kyp"/><stop offset=".33" class="f0-v8ab7u"/></linearGradient><linearGradient id="SVGZulLHoQU" x1="2.987" x2="24.287" y1="9.221" y2="15.189" gradientUnits="userSpaceOnUse"><stop offset=".27" class="iz7sq7b9x"/><stop offset=".53" class="v3a0wp5yq"/></linearGradient><linearGradient id="SVG6AGAMbGq" x1="3" x2="22.591" y1="12.035" y2="12.035" gradientUnits="userSpaceOnUse"><stop class="r3cck9bop"/><stop offset="1" class="aj7p33brp"/></linearGradient><linearGradient id="SVGHlkA4bFm" x1="12" x2="12" y1="2.969" y2="21.001" gradientUnits="userSpaceOnUse"><stop class="cf00ly5al"/><stop offset="1" class="f_ng--b-l"/></linearGradient><linearGradient id="SVGeBNMwcLk" x1="12.001" x2="12.001" y1="3.001" y2="21.001" gradientUnits="userSpaceOnUse"><stop class="lw1-2wk0v"/><stop offset="1" class="geco_ib9q"/></linearGradient><linearGradient id="SVGImOydcup" x1="15.733" x2="10.79" y1="4.113" y2="22.721" gradientUnits="userSpaceOnUse"><stop offset=".27" class="iz7sq7b9x"/><stop offset=".53" class="v3a0wp5yq"/></linearGradient><linearGradient id="SVGPStKj6UR" x1="11.999" x2="11.999" y1="3.001" y2="21.001" gradientUnits="userSpaceOnUse"><stop class="cf00ly5al"/><stop offset="1" class="f_ng--b-l"/></linearGradient><linearGradient id="SVGq4TihenR" x1="12.011" x2="12.011" y1="3.002" y2="21.002" gradientUnits="userSpaceOnUse"><stop class="lw1-2wk0v"/><stop offset="1" class="geco_ib9q"/></linearGradient><linearGradient id="SVGp3vQLe7z" x1="12" x2="12" y1="3.001" y2="21.001" gradientUnits="userSpaceOnUse"><stop class="cf00ly5al"/><stop offset="1" class="f_ng--b-l"/></linearGradient><linearGradient id="SVGlVHBxeao" x1="12.015" x2="12.015" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="lw1-2wk0v"/><stop offset="1" class="geco_ib9q"/></linearGradient><linearGradient id="SVGWJR9Neba" x1="21" x2="3.885" y1="5.73" y2="9.583" gradientUnits="userSpaceOnUse"><stop offset=".47" class="hec2xfsub"/><stop offset=".88" class="o9-wmgb-b"/></linearGradient><linearGradient id="SVGBTb74cWA" x1="7.448" x2="15.187" y1="14.859" y2="17.044" gradientUnits="userSpaceOnUse"><stop class="rh-jggbvb"/><stop offset="1" class="c6zt37bfj"/></linearGradient><linearGradient id="SVGPHIJhded" x1="21.001" x2="3.857" y1="5.702" y2="9.569" gradientUnits="userSpaceOnUse"><stop offset=".47" class="hec2xfsub"/><stop offset=".88" class="o9-wmgb-b"/></linearGradient><linearGradient id="SVGsZB7RfNZ" x1="3" x2="24.278" y1="9.225" y2="15.164" gradientUnits="userSpaceOnUse"><stop offset=".27" class="iz7sq7b9x"/><stop offset=".53" class="v3a0wp5yq"/></linearGradient><linearGradient id="SVGvqSXNeZz" x1="12.001" x2="12.001" y1="3.001" y2="21.001" gradientUnits="userSpaceOnUse"><stop class="ivsau0b4h"/><stop offset=".46" class="tmwe-9bty"/><stop offset="1" class="lyunj6bsp"/></linearGradient><linearGradient id="SVGeFAwJd3g" x1="12.53" x2="10.134" y1="7.377" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="o6062kbnm"/><stop offset=".45" class="zd1q_zbqh"/><stop offset="1" class="xqn147p3a"/></linearGradient><linearGradient id="SVGN9sckbch" x1="16.084" x2="14.31" y1="3.001" y2="22.824" gradientUnits="userSpaceOnUse"><stop offset=".17" class="u6g61vb5a"/><stop offset=".35" class="pcy3hvbor"/><stop offset=".8" class="joqnk_s0g"/></linearGradient><linearGradient id="SVGcHlZ1Q3D" x1="14.971" x2="4.196" y1="3.926" y2="20.131" gradientUnits="userSpaceOnUse"><stop class="xj8wzcbum"/><stop offset="1" class="zwab__bsh"/></linearGradient><linearGradient id="SVGDLw1Db3E" x1="19.72" x2="-1.223" y1="3.001" y2="19.537" gradientUnits="userSpaceOnUse"><stop class="g29u1zbwd"/><stop offset=".42" class="huswk3b2o"/><stop offset="1" class="jl1nih5ut"/></linearGradient><linearGradient id="SVGLsdvibhx" x1="11.999" x2="15.096" y1="3.025" y2="21.083" gradientUnits="userSpaceOnUse"><stop offset=".16" class="z3skisbgm"/><stop offset=".34" class="t542jnk0x"/><stop offset=".46" class="rm6bw5b2v"/><stop offset=".54" class="jlcz2pbas"/><stop offset=".9" class="rmgbc1bdp"/></linearGradient><linearGradient id="SVGtgvX5dVS" x1="11.986" x2="9.25" y1="3.001" y2="20.887" gradientUnits="userSpaceOnUse"><stop offset=".16" class="z3skisbgm"/><stop offset=".34" class="t542jnk0x"/><stop offset=".46" class="rm6bw5b2v"/><stop offset=".54" class="jlcz2pbas"/><stop offset=".9" class="rmgbc1bdp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ret" /></template>
<style>
.a30b09bxv {
  d: path("M17.374 14.462c-.726-1.89-2.171-2.075-2.801-1.932c-.175.386-.53 1.324-.53 1.932c2.473.62 3.214.096 3.336 0z");
}

.aj7p33brp {
  stop-color: var(--svg-color--d78519, #d78519);
}

.alkguff9j {
  fill: var(--svg-color--cbcac9, #cbcac9);
  d: path("m7.903 13.234l.053-.074l.318.238a.5.5 0 0 1 .095-.063c.053-.021.127-.043.19-.016c.064.026.112.08.149.127a.6.6 0 0 1 .069.122c.291.116 1.186.318 2.589.227q.091.004.174.043l.053.021a.2.2 0 0 0 .043.005l.063-.01l.09-.037l.07-.027q.08-.03.163-.053l.09-.016l.037-.005q.237-.04.471-.09a.6.6 0 0 0 .17-.063l.053.079a.7.7 0 0 1-.201.074a4 4 0 0 1-.477.095h-.037l-.132.027q-.087.03-.17.069l-.106.037a.25.25 0 0 1-.159.005l-.058-.021l-.01-.005a.4.4 0 0 0-.127-.032c-1.435.095-2.356-.122-2.647-.244l-.016-.01l-.006-.016a.6.6 0 0 0-.063-.117a.26.26 0 0 0-.106-.095a.16.16 0 0 0-.116.016a.4.4 0 0 0-.106.069l-.027.026z");
}

.avuf2-dcg {
  fill: var(--svg-color--656d62, #656d62);
  d: path("M12.01 8.926c1.324 0 1.827.73 1.917 1.096c0 1.599-.841 1.958-1.297 1.958c-2.345 0-2.297-1.72-2.297-2.34s.455-.714 1.678-.714");
}

.c6c0c5k4r {
  fill: var(--svg-color--b25c06, #b25c06);
  d: path("m9.634 14.791l-.424.895l.17-.9h.254zm.778.228l-.656.863l.794-.784l-.143-.079z");
}

.c6zt37bfj {
  stop-color: var(--svg-color--cd7f13, #cd7f13);
}

.cf00ly5al {
  stop-color: var(--svg-color--faed84, #faed84);
}

.cim6eb4jl {
  fill: var(--svg-color--1a739f, #1a739f);
  d: path("M9.025 5.299L8.432 3.79L5.933 5.357l1.048 1.154zm0 13.31l-.593 1.514l-2.499-1.567L6.981 17.4zM6.574 6.865L5.478 5.844L3.826 8.28l1.43.635L6.573 6.87zM5.017 14.61l-1.403.53l-.582-2.886l1.562-.037zm1.562 2.383l-1.054 1.07l-1.741-2.373l1.403-.688zM5.09 9.45l-1.509-.61L3 11.72l1.562.043zm6.581-2.817V5.008l-2.06.333l.551 1.456zM7.765 8.205l-.906-.979L5.7 9.016l1.228.45zm-1.027 1.912l-1.165-.52l-.487 2.076l1.366.069z");
}

.csmxg8ecq {
  d: path("M15.41 7.447a1.43 1.43 0 0 0-.307 1.043c.079.493-.8.88-1.472 1.075a.5.5 0 0 1-.037-.291c.116-.9 1.186-1.562 1.816-1.827");
}

.cv8ng12ig {
  fill: var(--svg-color--b25f05, #b25f05);
  d: path("M17.676 11.668c-.355.28-1.06.72-1.567.72c-.493 0-1.26-.048-1.705-.08l.026.175c.117.614.99.471 1.477.392c.117-.021.212-.037.27-.037c.291 0 .911-.476 1.033-.593c.037-.042.106-.095.18-.159c.148-.116.317-.26.317-.317a.2.2 0 0 0-.031-.101");
}

.d8z56xb1h {
  d: path("M8.225 9.153c-1.128.037-1.207.762-1.207 1.218c0 .995.328 1.164.635 1.164c1.186 0 1.673-1.731 1.673-2.075c0-.35-.265-.35-1.101-.307");
}

.ebw3pibqk {
  d: path("M10.979 16.062a3.9 3.9 0 0 0 3.907-3.892a3.9 3.9 0 0 0-3.907-3.89a3.9 3.9 0 0 0-3.907 3.89a3.9 3.9 0 0 0 3.907 3.892");
}

.eziougb8z {
  d: path("M10.163 9.857H9.66c.095.18-.095.572-.095.689c-.381.143-.55.407-.55.672s.237.64.55.64c.455 0 .767-.264.767-.592c0-.334-.285-.477-.312-.646c-.016-.133.09-.567.143-.763");
}

.f_ng--b-l {
  stop-color: var(--svg-color--e79d20, #e79d20);
}

.f0-v8ab7u {
  stop-color: var(--svg-color--faca30, #faca30);
}

.faor0c0ub {
  d: path("M15.103 8.49c-.101-.587.338-1.137.571-1.333c-.084-.111-.513-.334-1.509-.334c-1.244 0-2.419.715-2.419 1.287c0 .46 1.006 1.228 1.509 1.551c.656-.143 1.943-.577 1.848-1.165z");
}

.ft5dv1b6b {
  fill: none;
}

.g29u1zbwd {
  stop-color: var(--svg-color--b35d0a, #b35d0a);
}

.geco_ib9q {
  stop-color: var(--svg-color--ae5c04, #ae5c04);
}

.h-f76qp9e {
  fill: var(--svg-color--1a739f, #1a739f);
  d: path("m6.717 13.748l-1.191.609l-.471-2.076h1.307zm3.018 3.033l-.598 1.515l-1.795-1.07l1.053-1.154z");
}

.hdju55bar {
  fill: var(--svg-color--d7841a, #d7841a);
  d: path("M6.849 16.373c.153-.603.921-1.244 1.133-1.382c-.095-.169-.434.053-.715.233l-.201.127c.085-.264.492-.598.593-.677l.016-.016c.026-.021-.138-.027-.328-.032c-.217-.01-.472-.016-.503-.053c-.032-.026.063-.222.158-.423c.112-.228.228-.466.191-.52a2 2 0 0 0-.09-.116c.085-.095.17-.17.233-.222l2.038 1.34c-.423.211-1.376.709-1.8.979a1.76 1.76 0 0 0-.572.603c-.058.096-.1.16-.143.16z");
}

.hec2xfsub {
  stop-color: var(--svg-color--fbf387, #fbf387);
}

.huswk3b2o {
  stop-color: var(--svg-color--d27f08, #d27f08);
}

.i3n62_kyp {
  stop-color: var(--svg-color--b45a0f, #b45a0f);
}

.i6plz9b7w {
  d: path("M8.009 15.946c0-.498.476-.99.72-1.17c.598-.17 2.033.354 2.133.45c.096.095.355.476.355.794c0 .62-1.075.879-1.482.953c-.408.069-1.006.688-1.176.688s-.55-1.096-.55-1.715");
}

.ic72ubb3g {
  d: path("M9.64 7.776c0 .498.349.715.528.763l1.912.243c.227-.82.683-2.53.72-2.795c.053-.334-.265-.36-.381-.36c-2.256.598-2.78 1.53-2.78 2.15");
}

.ic7ujub9y {
  d: path("M11 15.416c.106.159.217.397.217.598c0 .625-1.075.884-1.483.953c-.233.043-.529.265-.778.45l-.196.143c.246-.382.585-.695.985-.91c.566-.244 1.096-.715 1.255-1.234");
}

.ijpabpkgc {
  d: path("M12.742 5.733c-.424.79-1.128 2.219-1.102 2.558c.016.264.244.412.445.481c.222-.82.678-2.52.715-2.784c.016-.122-.01-.202-.064-.255z");
}

.ivsau0b4h {
  stop-color: var(--svg-color--ffd133, #ffd133);
}

.iz7sq7b9x {
  stop-color: var(--svg-color--db8611, #db8611);
}

.jcx8i2p0n {
  d: path("M7.791 8.47c0 .476.355.82.53.932h1.842l-.265-1.313c-.095-.567-.318-1.694-.45-1.694c-.566 0-1.657 1.572-1.657 2.075");
}

.jfxrqvr8o {
  fill: var(--svg-color--fad33f, #fad33f);
  d: path("m15.51 10.794l4.96-2.113l.53 3.092h-4.675zm-1.848-2.16l2.107-4.94l2.398 1.721l-3.234 3.367z");
}

.jib7h4m8c {
  d: path("M6.426 15.108a2.5 2.5 0 0 1 .91-1.816l2.039 1.34c-.424.211-1.377.709-1.8.979c-.524.333-.599.762-.715.762c-.122 0-.434-.17-.434-1.27z");
}

.jl1nih5ut {
  stop-color: var(--svg-color--b5650b, #b5650b);
}

.jlcz2pbas {
  stop-color: var(--svg-color--54d8ed, #54d8ed);
}

.joqnk_s0g {
  stop-color: var(--svg-color--d8880b, #d8880b);
}

.jsq5rb6to {
  d: path("M15.362 8.49c-1.34 0-1.625.657-1.604.98c-.095 1.482 1.7 2.033 2.35 1.244c.43-1.387.858-1.551 1.007-1.747c-.096-.403-.959-.477-1.747-.477z");
}

.jw-1edbdg {
  d: path("M15.6 10.688c-.762 0-1.005.312-1.053.36c-.159.459-.199.95-.117 1.429c.143.768 1.462.36 1.748.36c.285 0 .91-.476 1.032-.593c.116-.122.503-.386.503-.476c0-.292-1.345-1.08-2.107-1.08z");
}

.kmct1yb3i {
  fill: var(--svg-color--df9a1c, #df9a1c);
  d: path("M13.35 13.653c.212-.556.154-.932.095-1.053c.17-.35.477-.572.477-.265a1.54 1.54 0 0 1-.572 1.318");
}

.le6frkbgj {
  fill: var(--svg-color--b25f05, #b25f05);
  d: path("M14.17 14.373c.319.027.991.233 1.076.847c.048.477.26.922.598 1.26a.7.7 0 0 0 .211-.132a4 4 0 0 1-.306-.905c-.027-.286-.551-.98-.599-1.006a2.1 2.1 0 0 0-.9-.244z");
}

.lugygpbxr {
  fill: var(--svg-color--656d62, #656d62);
  d: path("M10.55 9.307a4.4 4.4 0 0 0-1.175.021l-.032-.138c.159-.037.614-.084 1.218-.026zm-.71.323c-.19.01-.37.042-.486.1l-.059-.132c.363-.13.755-.149 1.128-.053l-.037.138a2 2 0 0 0-.545-.053");
}

.lw1-2wk0v {
  stop-color: var(--svg-color--d8a935, #d8a935);
}

.lyunj6bsp {
  stop-color: var(--svg-color--efa914, #efa914);
}

.m3pioybtx {
  d: path("M17.088 8.903c-.323.223-.985.757-1.727 1.594a6 6 0 0 1-.56.503c.481.153 1.01.069 1.307-.286c.344-1.117.688-1.44.89-1.625l.116-.117a.3.3 0 0 0-.027-.069");
}

.mxaxt0mxd {
  fill: var(--svg-color--1a739f, #1a739f);
  d: path("M11.793 4.625V3l-2.9.55l.555 1.457z");
}

.o6062kbnm {
  stop-color: var(--svg-color--dedcd0, #dedcd0);
}

.o9-wmgb-b {
  stop-color: var(--svg-color--e59718, #e59718);
}

.obaf6ngbs {
  fill: var(--svg-color--fad33f, #fad33f);
  d: path("m15.193 13.596l5.008 1.99l-1.81 2.563l-3.315-3.4z");
}

.pcy3hvbor {
  stop-color: var(--svg-color--ffee7e, #ffee7e);
}

.r_f83bbxa {
  d: path("M12.021 9.047c1.218 0 1.684.672 1.763 1.006c0 1.477-.773 1.805-1.191 1.805c-2.16 0-2.118-1.583-2.118-2.155s.424-.656 1.546-.656");
}

.r3cck9bop {
  stop-color: var(--svg-color--f8e467, #f8e467);
}

.r7o2t8b_k {
  fill: var(--svg-color--b05a0d, #b05a0d);
  d: path("M12.746 15.388c.021.032.275.757.275 1.096c0 .302.16.826.424 1.202c.085-.143.037-.492-.048-.762c-.074-.25-.031-1.155 0-1.578a4 4 0 0 0-.397-.138l-.254.185z");
}

.rh-jggbvb {
  stop-color: var(--svg-color--b76708, #b76708);
}

.rm6bw5b2v {
  stop-color: var(--svg-color--d6eda5, #d6eda5);
}

.rmgbc1bdp {
  stop-color: var(--svg-color--1180ae, #1180ae);
}

.s89qps1hv {
  fill: var(--svg-color--63cbe6, #63cbe6);
  d: path("M12.25 4.625V3l2.996.53l-.53 1.545z");
}

.sn6ot1bje {
  d: path("M10.862 17.998c-.751-.058-.873-1.043-.841-1.535l.211-.9l1.133-.244c.191.291.562.937.53 1.245c-.053.38-.583.81-.63.931c-.048.117-.164.503-.403.503");
}

.sqaschbsn {
  d: path("M6.018 12.53c0-.423.879-.688 1.324-.767c.386.656.963 1.943.137 1.863c-1.027-.09-1.46-.566-1.46-1.096");
}

.t542jnk0x {
  stop-color: var(--svg-color--d2eda9, #d2eda9);
}

.tmwe-9bty {
  stop-color: var(--svg-color--f8c72d, #f8c72d);
}

.u6g61vb5a {
  stop-color: var(--svg-color--f9cc38, #f9cc38);
}

.uhwf96wtk {
  d: path("M11.413 15.897c.11 1.127 1.376 1.694 1.985 1.837c.143-.095.095-.503 0-.81c-.074-.249-.032-1.154 0-1.578c-.71-.286-2.102-.582-1.985.55");
}

.v_cv6kb1l {
  fill: var(--svg-color--656d62, #656d62);
  d: path("M8.247 9.069c-1.223.037-1.318.836-1.318 1.334c0 1.1.36 1.291.699 1.291c1.291 0 1.82-1.91 1.82-2.292s-.29-.381-1.201-.333");
}

.v3a0wp5yq {
  stop-color: var(--svg-color--fbe04c, #fbe04c);
}

.vp71lbb5s {
  d: path("M15.749 15.443c-.027-.286-.551-.98-.599-1.006c-1.344-.715-2.949.265-2.467 1.006c.477.741 1.626 1.197 2.345 1.197c.578 0 .927-.196 1.033-.292a4 4 0 0 1-.318-.905z");
}

.vwfhpkctu {
  fill: var(--svg-color--b25f05, #b25f05);
  d: path("M17.32 14.505c-.328.015-.82.031-1.46.031c-.922 0-1.53-.211-1.795-.354c-.011.1-.021.196-.021.28c2.223.556 3.044.19 3.276.043");
}

.w63f3ac8s {
  fill: var(--svg-color--63cbe6, #63cbe6);
  d: path("M11.793 19.217v1.62l-2.9-.546l.555-1.46z");
}

.x5dpcqz8l {
  fill: var(--svg-color--fad33f, #fad33f);
  d: path("m13.112 15.346l2.15 4.87l-3.05.784l.053-4.855z");
}

.xh2s79_-b {
  d: path("M10.455 13.065c-1.462 0-2.399-.54-2.684-.81c0 1.747 1.005 2.504 2.895 2.504c1.896 0 2.303-1.408 2.42-1.694c.122-.286.074-.334 0-.355c-.069-.026-.81.355-2.631.355");
}

.xj8wzcbum {
  stop-color: var(--svg-color--e89d0e, #e89d0e);
}

.xqn147p3a {
  stop-color: var(--svg-color--e7e9e6, #e7e9e6);
}

.yawvegbgw {
  d: path("M9.565 6.6c-.15.37-.23.762-.238 1.16c0 .424.36.694.678.831l-.106-.503a12 12 0 0 0-.328-1.482z");
}

.z-p1diu_s {
  fill: var(--svg-color--b46014, #b46014);
  d: path("M10.99 17.958a.73.73 0 0 1-.143-.419c0-.164.122-.344.243-.529c.133-.201.265-.408.265-.614c0-.233.069-.604.127-.884c.196.323.44.804.408 1.053c-.032.265-.291.55-.466.741c-.08.085-.143.154-.159.191l-.01.042c-.048.111-.128.328-.265.424z");
}

.z3skisbgm {
  stop-color: var(--svg-color--8df1ed, #8df1ed);
}

.zd1q_zbqh {
  stop-color: var(--svg-color--fcfafb, #fcfafb);
}

.zwab__bsh {
  stop-color: var(--svg-color--feee76, #feee76);
}

</style>
