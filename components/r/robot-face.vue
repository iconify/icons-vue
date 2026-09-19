<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb64-8qmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nb64-8qmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:robot-face" /></template>
