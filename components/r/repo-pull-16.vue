<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv25lc1is.css';
import '../../css/e/ewgywhc6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tv25lc1is"/><path class="ewgywhc6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-pull-16" /></template>
