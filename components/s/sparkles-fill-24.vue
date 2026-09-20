<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e58pc83mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e58pc83mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sparkles-fill-24" /></template>
