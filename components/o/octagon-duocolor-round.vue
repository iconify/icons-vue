<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lafxaf8vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lafxaf8vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-duocolor-round" /></template>
