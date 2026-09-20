<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmzvf-ivy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jmzvf-ivy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:security-signal-detected" /></template>
