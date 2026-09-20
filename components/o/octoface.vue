<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td9g1kbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="td9g1kbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:octoface" /></template>
