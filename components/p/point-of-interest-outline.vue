<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvpsj6bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvpsj6bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:point-of-interest-outline" /></template>
