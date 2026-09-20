<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsznj30xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsznj30xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:plug-2" /></template>
