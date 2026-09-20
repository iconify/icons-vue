<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8scinpfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o8scinpfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:user-like-outline" /></template>
