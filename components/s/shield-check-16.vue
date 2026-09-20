<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9etl60ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e9etl60ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:shield-check-16" /></template>
