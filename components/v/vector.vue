<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":301};
const content = `<defs><linearGradient id="SVG1Z1o1buX" x1="13.523%" x2="86.414%" y1="74.679%" y2="25.305%"><stop offset="0%" class="fq16ehsqr"/><stop offset="10.3%" class="jjfstsb9y"/><stop offset="25.5%" class="xv_wb8eov"/><stop offset="40.8%" class="ytuk01d9k"/><stop offset="56%" class="zewcoxy1c"/><stop offset="71%" class="j_yl-vbmb"/><stop offset="85.8%" class="el591ab3z"/><stop offset="100%" class="kw3wjh4xo"/></linearGradient><linearGradient id="SVGHlnDLDSp" x1="21.006%" x2="96.466%" y1="54.033%" y2="27.047%"><stop offset="0%" class="fq16ehsqr"/><stop offset="10.3%" class="jjfstsb9y"/><stop offset="25.5%" class="xv_wb8eov"/><stop offset="40.8%" class="ytuk01d9k"/><stop offset="56%" class="zewcoxy1c"/><stop offset="71%" class="j_yl-vbmb"/><stop offset="85.8%" class="el591ab3z"/><stop offset="100%" class="kw3wjh4xo"/></linearGradient></defs><path fill="url(#SVG1Z1o1buX)" class="qix4cvbzi"/><path fill="url(#SVGHlnDLDSp)" class="cetno9eaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:vector" /></template>
<style>
.cetno9eaa {
  d: path("m183.181 109.354l-44.85 78.866l14.614 25.701l59.464-104.567zm-50.142 0L88.19 188.22l14.614 25.701l59.465-104.567zm-89.448 0l59.464 104.567l14.614-25.7l-44.85-78.867zm0 0l59.464 104.567l14.614-25.7l-44.85-78.867zm89.448 0L88.19 188.22l14.614 25.701l59.465-104.567z");
}

.el591ab3z {
  stop-color: var(--svg-color--c489ff, #c489ff);
}

.fq16ehsqr {
  stop-color: var(--svg-color--10e7ff, #10e7ff);
}

.j_yl-vbmb {
  stop-color: var(--svg-color--b790ff, #b790ff);
}

.jjfstsb9y {
  stop-color: var(--svg-color--33d5ff, #33d5ff);
}

.kw3wjh4xo {
  stop-color: var(--svg-color--c887ff, #c887ff);
}

.qix4cvbzi {
  d: path("M128 300.346L0 225.26V75.087L128 0l128 75.087V225.26zM17.89 214.677l109.858 64.504l109.858-64.504V85.67L128 21.165L17.89 85.67z");
}

.xv_wb8eov {
  stop-color: var(--svg-color--60bdff, #60bdff);
}

.ytuk01d9k {
  stop-color: var(--svg-color--86aaff, #86aaff);
}

.zewcoxy1c {
  stop-color: var(--svg-color--a39aff, #a39aff);
}

</style>
