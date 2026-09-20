<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl4-efmll.css';
import '../../css/u/ux165acwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rl4-efmll"/><path class="ux165acwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-locked-16" /></template>
