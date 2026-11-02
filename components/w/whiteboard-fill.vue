<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2qja5mor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2qja5mor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:whiteboard-fill" /></template>
