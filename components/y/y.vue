<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obdes7tlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="obdes7tlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:y" /></template>
