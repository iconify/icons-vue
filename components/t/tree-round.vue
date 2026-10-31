<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvv_ktbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvv_ktbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-round" /></template>
