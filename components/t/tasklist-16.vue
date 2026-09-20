<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx5ve9brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dx5ve9brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tasklist-16" /></template>
