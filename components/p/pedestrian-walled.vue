<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc9lrubca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zc9lrubca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:pedestrian-walled" /></template>
