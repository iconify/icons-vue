<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e869w8bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e869w8bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-push-16" /></template>
