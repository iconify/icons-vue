<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esmqhdcpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="esmqhdcpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tag-16" /></template>
