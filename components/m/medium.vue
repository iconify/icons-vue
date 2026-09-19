<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu-x9zbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="bu-x9zbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:medium" /></template>
