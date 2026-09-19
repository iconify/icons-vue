<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l48585b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l48585b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:quote" /></template>
