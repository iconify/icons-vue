<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm69y4u3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wm69y4u3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:xrpl" /></template>
