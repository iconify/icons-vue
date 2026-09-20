<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVG1TBr7EZm)" class="tk9mb3xbs"/><path class="idbos8c1m"/><path class="rv261nb1f"/><path fill="url(#SVGYLnCPeYV)" class="i4btqdblx"/><path class="ic1lbq1uc"/><path class="yrvsgqhey"/><path fill="url(#SVGXHGpDcls)" class="awz9780yj"/><path class="vm8nt1zax"/><path class="tgs6w-b4c"/><path class="px3a39jkw"/><path fill="url(#SVGt8CkZblS)" class="b120eercz"/><path class="ig-masz0v"/><path class="rcffpbbvc"/><path class="q6w-fz64x"/><path class="lig0ag7zm"/><path fill="url(#SVGxngcDbkr)" class="xj5tv4bxm"/><path fill="url(#SVGBAG55dYM)" class="hqu-aif1b"/><path fill="url(#SVGJvLbkcvt)" class="ngdfl4bbc"/><path class="wog9mx5-h"/><path fill="url(#SVGpb8AibcG)" class="irqlrmbds"/><path fill="url(#SVGd2IviegI)" class="z7hor5q8v"/><path fill="url(#SVGpb8AibcG)" class="sw3crcamd"/><path fill="url(#SVGHLDuYb4O)" class="l9ffqbbel"/><path fill="url(#SVGEwfSOb5t)" class="x08nmebpl"/><path fill="url(#SVGUXO9HTxh)" class="idkrnaciu"/><path fill="url(#SVGYtvyOeHw)" class="mv2f-ubtg"/><path class="b4ph01u5n"/><path fill="url(#SVGjGCIwbvs)" class="edy81vb9z"/><path class="wjp5ik4ir"/><path fill="url(#SVG7XbYfYIw)" class="mqsjk2m_x"/><path class="nhjugbose"/><path class="kkg7___4j"/><path class="r01psjbsd"/><path class="m2na8b2se"/><path fill="url(#SVGnNSV2bTr)" class="dssmmu2tz"/><path class="z7yhkfbjr"/><path fill="url(#SVGojVUYdGq)" class="scw4rznwu"/><path fill="url(#SVG3rAVAFro)" class="zu5xbpbvm"/><path fill="url(#SVGr6UhNeWk)" class="o4sf4v0jd"/><path fill="url(#SVGlmEr9c2W)" class="odamnwb8p"/><path fill="url(#SVGG13QQc5s)" class="catdo4ouc"/><path class="cwh2-dcqc"/></g><defs><linearGradient id="SVG1TBr7EZm" x1="11.965" x2="14.801" y1="3.999" y2="20.288" gradientUnits="userSpaceOnUse"><stop offset=".15" class="i3n62_kyp"/><stop offset=".33" class="f0-v8ab7u"/></linearGradient><linearGradient id="SVGYLnCPeYV" x1="11.985" x2="14.827" y1="4.011" y2="20.292" gradientUnits="userSpaceOnUse"><stop offset=".15" class="i3n62_kyp"/><stop offset=".33" class="f0-v8ab7u"/></linearGradient><linearGradient id="SVGXHGpDcls" x1="3.989" x2="22.922" y1="9.53" y2="14.835" gradientUnits="userSpaceOnUse"><stop offset=".27" class="iz7sq7b9x"/><stop offset=".53" class="v3a0wp5yq"/></linearGradient><linearGradient id="SVGt8CkZblS" x1="4" x2="21.415" y1="12.031" y2="12.031" gradientUnits="userSpaceOnUse"><stop class="r3cck9bop"/><stop offset="1" class="aj7p33brp"/></linearGradient><linearGradient id="SVGxngcDbkr" x1="12" x2="12" y1="3.973" y2="20.001" gradientUnits="userSpaceOnUse"><stop class="cf00ly5al"/><stop offset="1" class="f_ng--b-l"/></linearGradient><linearGradient id="SVGBAG55dYM" x1="12.001" x2="12.001" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="lw1-2wk0v"/><stop offset="1" class="geco_ib9q"/></linearGradient><linearGradient id="SVGJvLbkcvt" x1="15.317" x2="10.923" y1="4.99" y2="21.529" gradientUnits="userSpaceOnUse"><stop offset=".27" class="iz7sq7b9x"/><stop offset=".53" class="v3a0wp5yq"/></linearGradient><linearGradient id="SVGpb8AibcG" x1="11.999" x2="11.999" y1="4.001" y2="20.001" gradientUnits="userSpaceOnUse"><stop class="cf00ly5al"/><stop offset="1" class="f_ng--b-l"/></linearGradient><linearGradient id="SVGd2IviegI" x1="12.009" x2="12.009" y1="4.001" y2="20.002" gradientUnits="userSpaceOnUse"><stop class="lw1-2wk0v"/><stop offset="1" class="geco_ib9q"/></linearGradient><linearGradient id="SVGHLDuYb4O" x1="12.013" x2="12.013" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="lw1-2wk0v"/><stop offset="1" class="geco_ib9q"/></linearGradient><linearGradient id="SVGEwfSOb5t" x1="20" x2="4.786" y1="6.426" y2="9.851" gradientUnits="userSpaceOnUse"><stop offset=".47" class="hec2xfsub"/><stop offset=".88" class="o9-wmgb-b"/></linearGradient><linearGradient id="SVGUXO9HTxh" x1="7.954" x2="14.833" y1="14.541" y2="16.484" gradientUnits="userSpaceOnUse"><stop class="rh-jggbvb"/><stop offset="1" class="c6zt37bfj"/></linearGradient><linearGradient id="SVGYtvyOeHw" x1="20.001" x2="4.762" y1="6.401" y2="9.839" gradientUnits="userSpaceOnUse"><stop offset=".47" class="hec2xfsub"/><stop offset=".88" class="o9-wmgb-b"/></linearGradient><linearGradient id="SVGjGCIwbvs" x1="4" x2="22.914" y1="9.533" y2="14.813" gradientUnits="userSpaceOnUse"><stop offset=".27" class="iz7sq7b9x"/><stop offset=".53" class="v3a0wp5yq"/></linearGradient><linearGradient id="SVG7XbYfYIw" x1="11.999" x2="11.999" y1="4.001" y2="20.001" gradientUnits="userSpaceOnUse"><stop class="ivsau0b4h"/><stop offset=".46" class="tmwe-9bty"/><stop offset="1" class="lyunj6bsp"/></linearGradient><linearGradient id="SVGnNSV2bTr" x1="12.472" x2="10.341" y1="7.891" y2="19.701" gradientUnits="userSpaceOnUse"><stop class="o6062kbnm"/><stop offset=".45" class="zd1q_zbqh"/><stop offset="1" class="xqn147p3a"/></linearGradient><linearGradient id="SVGojVUYdGq" x1="15.631" x2="14.053" y1="4.001" y2="21.622" gradientUnits="userSpaceOnUse"><stop offset=".17" class="u6g61vb5a"/><stop offset=".35" class="pcy3hvbor"/><stop offset=".8" class="joqnk_s0g"/></linearGradient><linearGradient id="SVG3rAVAFro" x1="14.64" x2="5.062" y1="4.823" y2="19.227" gradientUnits="userSpaceOnUse"><stop class="xj8wzcbum"/><stop offset="1" class="zwab__bsh"/></linearGradient><linearGradient id="SVGr6UhNeWk" x1="18.862" x2=".246" y1="4.001" y2="18.699" gradientUnits="userSpaceOnUse"><stop class="g29u1zbwd"/><stop offset=".42" class="huswk3b2o"/><stop offset="1" class="jl1nih5ut"/></linearGradient><linearGradient id="SVGlmEr9c2W" x1="12" x2="14.752" y1="4.022" y2="20.074" gradientUnits="userSpaceOnUse"><stop offset=".16" class="z3skisbgm"/><stop offset=".34" class="t542jnk0x"/><stop offset=".46" class="rm6bw5b2v"/><stop offset=".54" class="jlcz2pbas"/><stop offset=".9" class="rmgbc1bdp"/></linearGradient><linearGradient id="SVGG13QQc5s" x1="11.987" x2="9.556" y1="4.001" y2="19.899" gradientUnits="userSpaceOnUse"><stop offset=".16" class="z3skisbgm"/><stop offset=".34" class="t542jnk0x"/><stop offset=".46" class="rm6bw5b2v"/><stop offset=".54" class="jlcz2pbas"/><stop offset=".9" class="rmgbc1bdp"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ret-background" /></template>
<style>
.aj7p33brp {
  stop-color: var(--svg-color--d78519, #d78519);
}

.awz9780yj {
  d: path("M15.332 15.06c-.023-.254-.489-.87-.531-.894c-1.196-.635-2.622.236-2.193.894c.423.66 1.444 1.064 2.084 1.064c.513 0 .824-.174.918-.259a3.4 3.4 0 0 1-.282-.805z");
}

.b120eercz {
  d: path("M6.683 12.471c0-.376.78-.611 1.176-.682c.344.584.857 1.727.122 1.657c-.912-.08-1.298-.504-1.298-.975");
}

.b4ph01u5n {
  fill: var(--svg-color--b25f05, #b25f05);
  d: path("M17.045 11.705c-.315.25-.941.64-1.393.64c-.438 0-1.12-.042-1.515-.07l.023.155c.104.546.88.419 1.313.348c.104-.019.188-.033.24-.033c.259 0 .81-.423.918-.527c.033-.038.094-.085.16-.141c.131-.104.282-.23.282-.282a.17.17 0 0 0-.028-.09");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.c6zt37bfj {
  stop-color: var(--svg-color--cd7f13, #cd7f13);
}

.catdo4ouc {
  d: path("M12.019 9.375c1.082 0 1.496.598 1.567.894c0 1.313-.687 1.605-1.059 1.605c-1.92 0-1.882-1.407-1.882-1.915c0-.509.376-.584 1.374-.584");
}

.cf00ly5al {
  stop-color: var(--svg-color--faed84, #faed84);
}

.cwh2-dcqc {
  fill: var(--svg-color--b25c06, #b25c06);
  d: path("m9.896 14.481l-.376.796l.15-.8h.226zm.692.203l-.584.767l.706-.697l-.127-.07z");
}

.dssmmu2tz {
  d: path("M10.627 12.947c-1.3 0-2.132-.48-2.386-.72c0 1.553.894 2.225 2.574 2.225c1.685 0 2.047-1.251 2.15-1.505c.109-.255.066-.297 0-.316c-.06-.023-.72.316-2.338.316");
}

.edy81vb9z {
  d: path("M16.777 14.189c-.645-1.68-1.93-1.845-2.49-1.718c-.155.344-.47 1.177-.47 1.718c2.197.55 2.856.085 2.964 0z");
}

.f_ng--b-l {
  stop-color: var(--svg-color--e79d20, #e79d20);
}

.f0-v8ab7u {
  stop-color: var(--svg-color--faca30, #faca30);
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

.hec2xfsub {
  stop-color: var(--svg-color--fbf387, #fbf387);
}

.hqu-aif1b {
  d: path("M9.836 7.2a2.9 2.9 0 0 0-.212 1.03c0 .377.32.617.602.74l-.094-.447q-.105-.668-.292-1.318z");
}

.huswk3b2o {
  stop-color: var(--svg-color--d27f08, #d27f08);
}

.i3n62_kyp {
  stop-color: var(--svg-color--b45a0f, #b45a0f);
}

.i4btqdblx {
  d: path("M11.478 15.464c.099 1.002 1.223 1.506 1.765 1.633c.127-.085.084-.447 0-.72c-.066-.221-.029-1.026 0-1.403c-.631-.254-1.869-.517-1.765.49");
}

.ic1lbq1uc {
  fill: var(--svg-color--b05a0d, #b05a0d);
  d: path("M12.663 15.012c.019.028.245.673.245.974c0 .268.141.734.376 1.068c.076-.127.033-.437-.042-.677c-.066-.222-.028-1.026 0-1.403a4 4 0 0 0-.353-.122l-.226.164z");
}

.idbos8c1m {
  fill: var(--svg-color--b46014, #b46014);
  d: path("M11.1 17.295a.65.65 0 0 1-.126-.372c0-.145.108-.305.216-.47c.118-.179.235-.362.235-.546c0-.207.061-.537.113-.786c.175.287.39.715.363.937c-.028.235-.259.489-.415.658a1 1 0 0 0-.14.17l-.01.037c-.042.1-.113.292-.235.377z");
}

.idkrnaciu {
  d: path("M16.522 9.247c-.287.198-.875.673-1.534 1.417a5 5 0 0 1-.499.447c.428.136.9.06 1.163-.255c.306-.992.611-1.28.79-1.444l.104-.104a.3.3 0 0 0-.024-.06");
}

.ig-masz0v {
  fill: var(--svg-color--63cbe6, #63cbe6);
  d: path("M12.222 5.445V4l2.663.47l-.47 1.375z");
}

.irqlrmbds {
  d: path("M9.901 8.246c0 .442.31.635.47.677l1.7.217c.202-.73.607-2.25.64-2.485c.047-.297-.236-.32-.339-.32c-2.005.532-2.47 1.36-2.47 1.91");
}

.ivsau0b4h {
  stop-color: var(--svg-color--ffd133, #ffd133);
}

.iz7sq7b9x {
  stop-color: var(--svg-color--db8611, #db8611);
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

.kkg7___4j {
  fill: var(--svg-color--656d62, #656d62);
  d: path("M8.664 9.394c-1.087.033-1.172.744-1.172 1.186c0 .979.32 1.148.621 1.148c1.149 0 1.62-1.698 1.62-2.037c0-.34-.26-.34-1.069-.297");
}

.l9ffqbbel {
  d: path("M15.03 7.953a1.27 1.27 0 0 0-.272.927c.07.438-.71.781-1.308.955a.42.42 0 0 1-.033-.258c.103-.8 1.054-1.389 1.614-1.624");
}

.lig0ag7zm {
  fill: var(--svg-color--1a739f, #1a739f);
  d: path("m9.355 6.042l-.527-1.34l-2.22 1.392l.93 1.026zm0 11.831l-.527 1.346l-2.22-1.393l.93-1.026zM7.177 7.435l-.975-.908l-1.468 2.165l1.27.565L7.178 7.44zM5.793 14.32l-1.247.47l-.518-2.564l1.389-.033zm1.388 2.118l-.936.95l-1.549-2.108l1.248-.611zM5.86 9.732L4.518 9.19L4 11.75l1.388.037zm5.85-2.504V5.784l-1.831.296l.49 1.294zM8.234 8.626l-.804-.87L6.4 9.345l1.092.4zm-.913 1.699l-1.035-.461l-.433 1.844l1.214.062z");
}

.lw1-2wk0v {
  stop-color: var(--svg-color--d8a935, #d8a935);
}

.lyunj6bsp {
  stop-color: var(--svg-color--efa914, #efa914);
}

.m2na8b2se {
  fill: var(--svg-color--656d62, #656d62);
  d: path("M12.01 9.268c1.176 0 1.623.649 1.703.974c0 1.42-.748 1.74-1.153 1.74c-2.084 0-2.042-1.529-2.042-2.08c0-.55.405-.634 1.492-.634");
}

.mqsjk2m_x {
  d: path("M11.091 15.61a3.466 3.466 0 0 0 3.473-3.459a3.466 3.466 0 0 0-3.473-3.459a3.466 3.466 0 0 0-3.473 3.46a3.466 3.466 0 0 0 3.473 3.458");
}

.mv2f-ubtg {
  d: path("M15.2 10.833c-.677 0-.893.278-.936.32a2.56 2.56 0 0 0-.103 1.27c.127.683 1.299.32 1.553.32s.81-.423.917-.526c.104-.109.447-.344.447-.424c0-.259-1.195-.96-1.872-.96z");
}

.ngdfl4bbc {
  d: path("M7.044 14.763a2.23 2.23 0 0 1 .81-1.615l1.811 1.191c-.376.188-1.223.63-1.6.87c-.466.297-.532.678-.635.678c-.108 0-.386-.15-.386-1.13z");
}

.nhjugbose {
  fill: var(--svg-color--df9a1c, #df9a1c);
  d: path("M13.2 13.469c.188-.494.137-.828.085-.936c.15-.311.423-.509.423-.236a1.37 1.37 0 0 1-.508 1.172");
}

.o4sf4v0jd {
  d: path("M11.11 15.036c.095.141.194.353.194.532c0 .555-.956.786-1.318.847c-.207.038-.47.235-.692.4l-.174.127c.219-.34.52-.618.875-.81c.504-.216.975-.635 1.116-1.096");
}

.o6062kbnm {
  stop-color: var(--svg-color--dedcd0, #dedcd0);
}

.o9-wmgb-b {
  stop-color: var(--svg-color--e59718, #e59718);
}

.odamnwb8p {
  d: path("M8.644 9.47c-1.002.032-1.073.677-1.073 1.082c0 .884.292 1.035.565 1.035c1.054 0 1.487-1.54 1.487-1.845c0-.31-.235-.31-.979-.273");
}

.pcy3hvbor {
  stop-color: var(--svg-color--ffee7e, #ffee7e);
}

.px3a39jkw {
  fill: var(--svg-color--fad33f, #fad33f);
  d: path("m15.12 10.928l4.41-1.878l.47 2.75h-4.155zm-1.642-1.92l1.873-4.39l2.131 1.529l-2.875 2.993z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q6w-fz64x {
  fill: var(--svg-color--63cbe6, #63cbe6);
  d: path("M11.816 18.414v1.44l-2.579-.485l.494-1.299z");
}

.r01psjbsd {
  fill: var(--svg-color--656d62, #656d62);
  d: path("M10.71 9.606a4 4 0 0 0-1.045.02l-.028-.123c.141-.033.546-.075 1.082-.024zm-.63.287a1.2 1.2 0 0 0-.434.09l-.051-.118a1.7 1.7 0 0 1 1.002-.047l-.033.122a1.8 1.8 0 0 0-.485-.047");
}

.r3cck9bop {
  stop-color: var(--svg-color--f8e467, #f8e467);
}

.rcffpbbvc {
  fill: var(--svg-color--1a739f, #1a739f);
  d: path("M11.816 5.445V4l-2.579.49l.494 1.294z");
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

.rv261nb1f {
  fill: var(--svg-color--fad33f, #fad33f);
  d: path("m12.989 14.974l1.91 4.33l-2.71.696l.047-4.316z");
}

.scw4rznwu {
  d: path("M10.367 10.096H9.92c.085.16-.084.508-.084.611c-.34.127-.49.363-.49.598s.212.57.49.57c.404 0 .682-.236.682-.527c0-.297-.254-.424-.278-.575c-.014-.117.08-.503.127-.677");
}

.sw3crcamd {
  d: path("M14.757 8.88c-.09-.522.301-1.011.508-1.185c-.075-.099-.456-.297-1.341-.297c-1.106 0-2.15.636-2.15 1.144c0 .41.894 1.092 1.34 1.379c.584-.127 1.728-.513 1.643-1.035z");
}

.t542jnk0x {
  stop-color: var(--svg-color--d2eda9, #d2eda9);
}

.tgs6w-b4c {
  fill: var(--svg-color--1a739f, #1a739f);
  d: path("m7.303 13.554l-1.059.54l-.419-1.844h1.163zm2.682 2.696l-.531 1.346l-1.596-.95l.937-1.027z");
}

.tk9mb3xbs {
  d: path("M10.988 17.331c-.669-.051-.777-.927-.749-1.364l.189-.8l1.007-.217c.17.259.498.833.47 1.106c-.047.339-.517.72-.56.828c-.042.104-.146.447-.357.447");
}

.tmwe-9bty {
  stop-color: var(--svg-color--f8c72d, #f8c72d);
}

.u6g61vb5a {
  stop-color: var(--svg-color--f9cc38, #f9cc38);
}

.v3a0wp5yq {
  stop-color: var(--svg-color--fbe04c, #fbe04c);
}

.vm8nt1zax {
  fill: var(--svg-color--b25f05, #b25f05);
  d: path("M13.93 14.11c.282.023.88.206.955.752c.043.424.23.819.532 1.12a.7.7 0 0 0 .188-.118a3.4 3.4 0 0 1-.273-.804c-.024-.254-.49-.87-.532-.894a1.9 1.9 0 0 0-.8-.217z");
}

.wjp5ik4ir {
  fill: var(--svg-color--b25f05, #b25f05);
  d: path("M16.73 14.227c-.292.014-.73.028-1.3.028c-.818 0-1.36-.189-1.595-.316q-.017.136-.019.25c1.977.494 2.706.17 2.913.037");
}

.wog9mx5-h {
  fill: var(--svg-color--d7841a, #d7841a);
  d: path("M7.421 15.887c.137-.536.82-1.106 1.007-1.228c-.084-.15-.385.047-.635.207l-.179.113c.076-.235.438-.532.527-.602l.015-.014c.023-.02-.123-.024-.292-.029c-.193-.01-.42-.014-.447-.047c-.029-.023.056-.198.14-.376c.1-.203.203-.414.17-.461a2 2 0 0 0-.08-.104c.076-.085.15-.15.207-.198l1.812 1.191c-.376.188-1.223.63-1.6.87c-.287.184-.423.4-.508.537c-.052.085-.09.141-.127.141z");
}

.x08nmebpl {
  d: path("M14.988 8.88c-1.19 0-1.445.583-1.426.87c-.085 1.318 1.51 1.808 2.09 1.106c.38-1.233.762-1.378.893-1.553c-.084-.357-.851-.423-1.553-.423z");
}

.xj5tv4bxm {
  d: path("M8.259 8.862c0 .424.315.73.47.829h1.638l-.235-1.168c-.085-.503-.283-1.505-.4-1.505c-.504 0-1.473 1.397-1.473 1.844");
}

.xj8wzcbum {
  stop-color: var(--svg-color--e89d0e, #e89d0e);
}

.xqn147p3a {
  stop-color: var(--svg-color--e7e9e6, #e7e9e6);
}

.yrvsgqhey {
  fill: var(--svg-color--fad33f, #fad33f);
  d: path("m14.838 13.418l4.452 1.77l-1.61 2.277l-2.946-3.021z");
}

.z3skisbgm {
  stop-color: var(--svg-color--8df1ed, #8df1ed);
}

.z7hor5q8v {
  d: path("M12.658 6.43c-.376.7-1.002 1.972-.979 2.273c.014.235.217.367.396.428c.197-.73.602-2.24.635-2.475c.014-.109-.01-.18-.057-.226z");
}

.z7yhkfbjr {
  fill: var(--svg-color--cbcac9, #cbcac9);
  d: path("m8.358 13.097l.047-.066l.282.212a.4.4 0 0 1 .085-.056c.047-.02.113-.038.17-.014c.056.023.098.07.131.113a.5.5 0 0 1 .061.108c.26.103 1.054.282 2.302.202a.4.4 0 0 1 .155.038l.047.018a.1.1 0 0 0 .038.005l.056-.01l.08-.032l.061-.024q.072-.026.146-.047l.08-.014l.033-.005q.21-.036.419-.08a.6.6 0 0 0 .15-.056l.048.07a.6.6 0 0 1-.18.066q-.208.057-.423.085h-.033l-.117.024a1 1 0 0 0-.15.06l-.095.034a.22.22 0 0 1-.141.005l-.052-.02l-.01-.004a.3.3 0 0 0-.112-.028c-1.276.084-2.095-.108-2.353-.217l-.014-.01l-.005-.013a.5.5 0 0 0-.057-.104a.23.23 0 0 0-.094-.085a.14.14 0 0 0-.103.015a.4.4 0 0 0-.094.06l-.024.024z");
}

.zd1q_zbqh {
  stop-color: var(--svg-color--fcfafb, #fcfafb);
}

.zu5xbpbvm {
  d: path("M8.452 15.507c0-.442.423-.88.64-1.04c.531-.15 1.807.316 1.896.4c.085.085.316.424.316.706c0 .55-.956.782-1.318.847c-.363.061-.894.612-1.045.612s-.49-.974-.49-1.525");
}

.zwab__bsh {
  stop-color: var(--svg-color--feee76, #feee76);
}

</style>
