<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jydc_mb-y.css';
import '../../css/t/tbcp7-bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jydc_mb-y"/><path class="tbcp7-bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:single-select-24" /></template>
