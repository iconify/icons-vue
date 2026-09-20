<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v28a9t3ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v28a9t3ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:view-files-16" /></template>
