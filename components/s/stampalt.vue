<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8n9p-9ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="x8n9p-9ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stampalt" /></template>
