<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6_lwd2sp.css';
import '../../css/e/e-tetgb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6_lwd2sp"/><path class="e-tetgb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:navigation-page-right" /></template>
