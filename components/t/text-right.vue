<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lal__dzbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lal__dzbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:text-right" /></template>
