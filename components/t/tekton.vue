<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtq2kvbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtq2kvbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tekton" /></template>
