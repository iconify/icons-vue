<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7t213qvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k7t213qvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:trophy-16" /></template>
