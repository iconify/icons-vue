<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syc4zbbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="syc4zbbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:phpunit" /></template>
