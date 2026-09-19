<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgsp334ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="cgsp334ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:page" /></template>
