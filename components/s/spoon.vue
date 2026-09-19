<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0b-z2s3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1792};
const content = `<path class="o0b-z2s3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:spoon" /></template>
