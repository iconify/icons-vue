<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4c2y4bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4c2y4bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:question-circle-solid" /></template>
