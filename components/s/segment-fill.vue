<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqc487bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqc487bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:segment-fill" /></template>
