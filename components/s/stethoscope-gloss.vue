<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ood22d57s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ood22d57s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stethoscope-gloss" /></template>
