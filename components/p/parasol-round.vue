<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avn7179zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avn7179zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parasol-round" /></template>
