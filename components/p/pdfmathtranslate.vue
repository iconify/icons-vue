<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clrj_mvqf.css';
import '../../css/a/ay6n8vh9w.css';
import '../../css/v/v2bqu0buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="clrj_mvqf"/><path class="ay6n8vh9w"/><path class="v2bqu0buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pdfmathtranslate" /></template>
