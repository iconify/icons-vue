<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvzcewbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mvzcewbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:photo-camera" /></template>
