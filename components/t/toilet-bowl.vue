<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp6tztbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vp6tztbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:toilet-bowl" /></template>
