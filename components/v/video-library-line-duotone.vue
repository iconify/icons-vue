<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/ea_31gbnm.css';
import '../../css/k/ky0k78gvx.css';
import '../../css/v/vnsop5_4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ea_31gbnm"/><path class="ky0k78gvx"/><path class="vnsop5_4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-library-line-duotone" /></template>
