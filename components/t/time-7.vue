<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilad_8boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ilad_8boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:time-7" /></template>
