<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftckpcdaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftckpcdaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-warning-fill-round" /></template>
