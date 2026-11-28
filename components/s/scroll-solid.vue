<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1_myjilh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1_myjilh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scroll-solid" /></template>
