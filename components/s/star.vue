<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvf9qjbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvf9qjbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:star" /></template>
