<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa1unaboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa1unaboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:question-hexagon-solid" /></template>
