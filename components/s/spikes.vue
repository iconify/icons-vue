<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnly0yy0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cnly0yy0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:spikes" /></template>
