<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3xjz0bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3xjz0bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-duotone-round" /></template>
