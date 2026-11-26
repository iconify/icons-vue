<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enie18bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="enie18bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:rectangle-vertical" /></template>
