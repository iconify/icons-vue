<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-bi-qb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="x-bi-qb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tag" /></template>
