<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbf7qdnvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbf7qdnvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rare-fog-lights-line" /></template>
