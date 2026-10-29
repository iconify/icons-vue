<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2uq3i48e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2uq3i48e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:square-x-solid" /></template>
