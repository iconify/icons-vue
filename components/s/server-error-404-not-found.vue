<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/aqg2-5bbs.css';
import '../../css/k/kib7r1wvv.css';
import '../../css/k/kvsiuof9s.css';
import '../../css/v/vri-l7yab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="aqg2-5bbs"/><path class="kib7r1wvv"/><path class="kvsiuof9s"/><path class="vri-l7yab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:server-error-404-not-found" /></template>
