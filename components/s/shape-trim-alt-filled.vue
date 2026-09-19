<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo11wvb4j.css';
import '../../css/h/htivmtpeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo11wvb4j"/><path class="htivmtpeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-trim-alt-filled" /></template>
