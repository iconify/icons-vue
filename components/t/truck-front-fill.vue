<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh41ovbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kh41ovbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:truck-front-fill" /></template>
