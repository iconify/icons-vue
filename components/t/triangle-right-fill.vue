<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjf41hbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjf41hbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:triangle-right-fill" /></template>
