<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztzz4wb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ztzz4wb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mattermost" /></template>
