<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bit21z5fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bit21z5fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:unlock-2" /></template>
