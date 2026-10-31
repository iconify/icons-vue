<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub-ef1b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub-ef1b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-x-gloss" /></template>
