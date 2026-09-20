<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa4xafn4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa4xafn4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:selection-lasso" /></template>
