<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6le-k8fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g6le-k8fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:stripe" /></template>
