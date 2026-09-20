<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do3f0-lqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do3f0-lqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:pagerduty" /></template>
