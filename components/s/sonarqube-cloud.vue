<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enih07b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enih07b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sonarqube-cloud" /></template>
