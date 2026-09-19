<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psimoeocj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psimoeocj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pinterest" /></template>
