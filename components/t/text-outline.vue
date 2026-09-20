<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icm-ce5fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="icm-ce5fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:text-outline" /></template>
