<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx15pnu6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx15pnu6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:moon-star-solid" /></template>
