<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e24bgbccy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e24bgbccy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paintbrush-fill" /></template>
