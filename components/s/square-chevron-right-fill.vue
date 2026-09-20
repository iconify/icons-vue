<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqg-h8wnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqg-h8wnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevron-right-fill" /></template>
