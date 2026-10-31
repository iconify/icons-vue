<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7-cenqsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7-cenqsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-alt-2-round" /></template>
