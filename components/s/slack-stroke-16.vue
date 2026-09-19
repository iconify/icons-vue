<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz7yqsbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vz7yqsbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:slack-stroke-16" /></template>
