<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj77lc-6d.css';
import '../../css/e/e0nkev_-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xj77lc-6d"/><path class="e0nkev_-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:trpc-wordmark" /></template>
