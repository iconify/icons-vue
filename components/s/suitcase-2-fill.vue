<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdo0w_bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdo0w_bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:suitcase-2-fill" /></template>
