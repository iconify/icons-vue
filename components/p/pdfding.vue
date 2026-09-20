<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzzcr4b4h.css';
import '../../css/y/ynjyyh6_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="jzzcr4b4h"/><path class="ynjyyh6_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pdfding" /></template>
