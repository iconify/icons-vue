<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvtqidc3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lvtqidc3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:tiger-face" /></template>
