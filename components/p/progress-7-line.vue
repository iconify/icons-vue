<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9-496bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9-496bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-7-line" /></template>
