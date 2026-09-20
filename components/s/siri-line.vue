<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhy0hdblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhy0hdblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:siri-line" /></template>
