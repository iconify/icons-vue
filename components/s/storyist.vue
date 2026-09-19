<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs0zpe4kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zs0zpe4kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:storyist" /></template>
