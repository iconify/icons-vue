<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3e9_7b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":420,"height":512};
const content = `<path class="h3e9_7b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:storybook" /></template>
