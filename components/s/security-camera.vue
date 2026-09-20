<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arbt2q4zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="arbt2q4zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:security-camera" /></template>
