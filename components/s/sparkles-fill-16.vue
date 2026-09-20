<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mscab2bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mscab2bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sparkles-fill-16" /></template>
