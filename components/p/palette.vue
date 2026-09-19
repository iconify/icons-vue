<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erv-4vbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="erv-4vbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:palette" /></template>
