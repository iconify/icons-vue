<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v7zhpckwt.css';
import '../../css/o/o5mljgbpd.css';
import '../../css/o/oheub1d8k.css';
import '../../css/c/csac9jvtl.css';
import '../../css/v/vxuqhab0r.css';
import '../../css/j/jmku5acuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v7zhpckwt wm-k"/><path class="o5mljgbpd wm-a"/><path class="oheub1d8k wm-shadow"/><path class="csac9jvtl wm-k"/><path class="vxuqhab0r wm-a"/><path class="jmku5acuo wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:screen-share-engrave" /></template>
