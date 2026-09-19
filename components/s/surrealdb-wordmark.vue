<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta51_fbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ta51_fbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:surrealdb-wordmark" /></template>
