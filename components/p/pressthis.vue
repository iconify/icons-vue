<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6i0pt-4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e6i0pt-4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:pressthis" /></template>
