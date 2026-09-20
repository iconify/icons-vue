<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t39a96wvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t39a96wvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mp4-outline" /></template>
