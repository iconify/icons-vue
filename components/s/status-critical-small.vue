<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fapfoe3xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fapfoe3xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:status-critical-small" /></template>
