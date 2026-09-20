<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6-qcibcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6-qcibcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:swap-horizontal-variant" /></template>
