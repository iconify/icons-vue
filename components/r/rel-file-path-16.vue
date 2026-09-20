<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo9dtoxdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xo9dtoxdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:rel-file-path-16" /></template>
