<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ref45cb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ref45cb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:octopus" /></template>
