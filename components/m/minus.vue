<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndbsxlb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndbsxlb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:minus" /></template>
