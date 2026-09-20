<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsek8xbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fsek8xbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:user-minus-outline" /></template>
