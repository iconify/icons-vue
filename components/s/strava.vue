<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ireb7vb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ireb7vb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:strava" /></template>
