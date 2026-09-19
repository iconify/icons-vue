<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nml_d7_9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nml_d7_9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-start-circle-fill" /></template>
