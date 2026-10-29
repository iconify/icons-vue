<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/csac9jvtl.css';
import '../../css/v/vxuqhab0r.css';
import '../../css/j/jmku5acuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="csac9jvtl"/><path class="vxuqhab0r wm-a"/><path class="jmku5acuo wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:screen-share" /></template>
