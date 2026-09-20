<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh9bj1pjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh9bj1pjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:minus-hexagon-solid" /></template>
