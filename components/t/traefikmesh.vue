<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3zpp1qvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s3zpp1qvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:traefikmesh" /></template>
