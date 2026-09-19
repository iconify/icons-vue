<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs3nyobbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vs3nyobbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:notification" /></template>
