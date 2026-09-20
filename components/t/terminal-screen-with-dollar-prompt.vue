<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojjmu_19i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ojjmu_19i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:terminal-screen-with-dollar-prompt" /></template>
