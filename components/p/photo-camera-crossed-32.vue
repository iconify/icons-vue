<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0llrhkep.css';
import '../../css/p/pbyqebu6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b0llrhkep"/><path class="pbyqebu6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:photo-camera-crossed-32" /></template>
