<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_go7u7sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_go7u7sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-3-fill" /></template>
