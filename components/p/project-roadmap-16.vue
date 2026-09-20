<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6u24bczz.css';
import '../../css/k/k15odkf_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j6u24bczz"/><path class="k15odkf_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project-roadmap-16" /></template>
