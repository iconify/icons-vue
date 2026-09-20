<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6ui7xiyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6ui7xiyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:math-integral-box" /></template>
