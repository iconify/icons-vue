<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-dguhbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-dguhbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:todoist-dark" /></template>
