<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsvcz2bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsvcz2bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sitemap-filled" /></template>
