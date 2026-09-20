<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9gy4gb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="q9gy4gb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:rain-cloud" /></template>
