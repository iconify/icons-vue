<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1fgqy-sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1fgqy-sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:waves-round" /></template>
