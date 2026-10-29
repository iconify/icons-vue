<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b7ss4s--r.css';
import '../../css/o/osmt2wiov.css';
import '../../css/c/ca9g4jbzr.css';
import '../../css/o/ofl-evjxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b7ss4s--r"/><path class="osmt2wiov wm-k"/><path class="ca9g4jbzr wm-k"/><path class="ofl-evjxh wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:washing-machine-sketch" /></template>
