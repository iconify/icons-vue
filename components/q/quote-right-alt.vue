<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvwej7una.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvwej7una"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:quote-right-alt" /></template>
