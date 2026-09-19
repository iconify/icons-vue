<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e39wb7b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e39wb7b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:trophy-2-solid" /></template>
