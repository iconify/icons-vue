<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrxm1hb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hrxm1hb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:truck-flatbed" /></template>
