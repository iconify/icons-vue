<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0kqb-isp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n0kqb-isp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sparkle-16" /></template>
