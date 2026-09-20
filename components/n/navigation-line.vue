<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvy203q6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvy203q6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:navigation-line" /></template>
