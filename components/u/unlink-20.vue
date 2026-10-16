<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge6gn80ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ge6gn80ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:unlink-20" /></template>
