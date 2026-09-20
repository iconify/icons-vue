<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3t6929wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3t6929wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:management" /></template>
