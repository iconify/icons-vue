<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azxr97--q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="azxr97--q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unverified" /></template>
