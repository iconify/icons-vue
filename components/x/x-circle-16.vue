<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/titm1qjhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="titm1qjhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:x-circle-16" /></template>
