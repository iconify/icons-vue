<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk3h7-bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bk3h7-bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:split-view-16" /></template>
