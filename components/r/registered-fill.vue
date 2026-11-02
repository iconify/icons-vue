<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3grej-wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3grej-wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:registered-fill" /></template>
