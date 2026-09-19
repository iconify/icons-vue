<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6yk-6b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g6yk-6b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:video-camera" /></template>
