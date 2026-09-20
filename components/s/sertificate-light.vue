<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/j/j27ze1b2l.css';
import '../../css/j/jdxgfcblx.css';
import '../../css/f/fh-xrsb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="j27ze1b2l"/><circle class="jdxgfcblx"/><path class="fh-xrsb1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sertificate-light" /></template>
