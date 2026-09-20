<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9-nrmbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c9-nrmbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:rss-16" /></template>
