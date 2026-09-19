<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6xsvfb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m6xsvfb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:speaker-x-mark-16-solid" /></template>
