<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a10l0tb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a10l0tb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:play-fill" /></template>
